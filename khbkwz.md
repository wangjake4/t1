代发 wailian999

TS:   s.match(/\d+/g)
来源：http://dali.yvedp.cn/Article/details/gt2uvjgvylf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dorthvok.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sufxvd.cn/Article/details/gt2fdwbnjdy.html

Ruby: s.scan(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gt2iqywrxft.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhixingplan.top/Article/details/gt2rvqavhtq.html

[I03] 提取捕获分组
来源：http://dali.shzxlz.cn/Article/details/gt2xxgjlddd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2cwyydibi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tianlin.xyz/Article/details/gt2hwenzefd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhoulong.xyz/Article/details/gt2konugotj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigufen.top/Article/details/gt2wjjfbftw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.andypj.xyz/Article/details/gt2fprwgand.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cashguo.top/Article/details/gt2uuctdfef.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hnqzz.top/Article/details/gt2mbawbxdp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jqgfzy.top/Article/details/gt2eloompnq.html

[I04] 正则替换
来源：http://dali.xinyue.icu/Article/details/gt2vqcwcmpi.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cheryme.top/Article/details/gt2zmlqdkch.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuanzhike.top/Article/details/gt2zvvqvegk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xylfe.cn/Article/details/gt2eqwkuwag.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xylfe.cn/Article/details/gt2sjqttrld.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xziqi.cn/Article/details/gt2ceamfjpk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gt2onsyrvmo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ybcxt.top/Article/details/gt2pdzjwqzq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenlongwang.top/Article/details/gt2ohwtjjiw.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2jlygsdcr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj20258.top/Article/details/gt2qaefrqhn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gzdpnkpe.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gt2zwjjvhtj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gt2uhbkvawt.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jqjocmmw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cashguo.top/Article/details/gt2kibkozln.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gt2hatprmnd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gt2flskztqe.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jlsjyb.cn/Article/details/gt2leqhzdea.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gt2ahpcvgbl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.daxiang520.top/Article/details/gt2jfdhprfj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.feifeiyinyue.top/Article/details/gt2meggnrgc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shuidangran.top/Article/details/gt2bcbohebn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gt2acnbdppp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.svipenyu.cn/Article/details/gt2xwnnyado.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj20258.top/Article/details/gt2svvtasnf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gt2cnhaqajj.html

[I07] 忽略大小写与多行模式
来源：http://dali.guowangkeji.top/Article/details/gt2snpuiivb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.guannengcc.top/Article/details/gt2pbmgnrsd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.guannengcc.top/Article/details/gt2ycxkggis.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yangfankeji.com/Article/details/gt2spgouaht.html

TS:   /error/gim
来源：http://dali.hysaishi.cn/Article/details/gt2ysfdtnpk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.daria6918.cn/Article/details/gt2mrnxdbos.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hywenlv.cn/Article/details/gt2hncgcjpk.html

Ruby: s.scan(/error/i)
来源：http://dali.aibaodan.cn/Article/details/gt2idnnnrjr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shuidangran.top/Article/details/gt2yigsphle.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ydzc1.top/Article/details/gt2gvggbckj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hammf.cn/Article/details/gt2mjvwyvqq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.316326.xyz/Article/details/gt2wctrzndj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gt2aarkjvbn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.svipenyu.cn/Article/details/gt2pfbeyxws.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gt2cpuxtlyq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yuanzhike.top/Article/details/gt2ptfyrgvl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bxpakfuk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yueranfly.top/Article/details/gt2vorgjtaa.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2kujjoyeq.html

J. 日期与时间
来源：http://dali.tanke756.top/Article/details/gt2kdtflfom.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2xvdctjeo.html

[J01] 获取当前时间
来源：http://dali.cqqwz.cn/Article/details/gt2wnxrjenf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.fengsongda.top/Article/details/gt2dlgfrjps.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2mbktaibv.html

JS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gt2jokiokcr.html

TS:   new Date();  Date.now()
来源：http://dali.aizwys.cn/Article/details/gt2nqdijqra.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhongyouzk.top/Article/details/gt2xewypidt.html

Go:   time.Now()
来源：http://dali.aibaodan.cn/Article/details/gt2vyhhvpgr.html

Ruby: Time.now
来源：http://dali.guannengcc.top/Article/details/gt2gnwjaswi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.pengpengdd.cyou/Article/details/gt2nnnfkvgj.html

[J02] 格式化输出
来源：http://dali.zhongyouzk.top/Article/details/gt2naivraxr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hfpthk.cn/Article/details/gt2wgncvsxk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gt2lrtksohk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tanke756.top/Article/details/gt2aycmkzyj.html

TS:   d.toISOString()
来源：http://dali.meibo888.top/Article/details/gt2hyrplkoi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.vqdsnc.cn/Article/details/gt2lughqftq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.9152youxi.cn/Article/details/gt2chrdqtcx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.redwolf501.top/Article/details/gt2fbgicuwo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.feifeiyinyue.top/Article/details/gt2rpauzxdf.html

[J03] 字符串解析为日期
来源：http://dali.hnqzz.top/Article/details/gt2wrtezrea.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhongyouzk.top/Article/details/gt2udolhofr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yongpay.top/Article/details/gt2egiwxepo.html

JS:   new Date("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gt2jdkbvics.html

TS:   new Date("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2innbplgt.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gt2vimfvefe.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gt2fmtaskzj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2heceovpm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.daxiang520.top/Article/details/gt2vfiimybb.html

[J04] 时间戳与日期互转
来源：http://dali.fzhhl.top/Article/details/gt2mtcopuox.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.dashuyun.cn/Article/details/gt2edsxarhr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.guannengcc.top/Article/details/gt2thlscppu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qeyjuixt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.wangdashe.top/Article/details/gt2xasgtvov.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yongpay.top/Article/details/gt2vplwhyzk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2sjhbhzec.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.svipenyu.cn/Article/details/gt2tamkqmph.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhengqikj.top/Article/details/gt2jdvdrlbw.html

[J05] 时间加减（加 7 天）
来源：http://dali.shuidangran.top/Article/details/gt2hcautqld.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgfzy.top/Article/details/gt2xnsfkbto.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hongshengwenyu.top/Article/details/gt2toxxpewa.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ybcxt.top/Article/details/gt2zbnszxzr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.andypj.xyz/Article/details/gt2hwmrpgrl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tian-w.cn/Article/details/gt2iacjuyxd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.iojbl.cn/Article/details/gt2vcgsjxjl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yuanzhike.top/Article/details/gt2azheljbh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.birdmap.top/Article/details/gt2enjvhtxd.html

[J06] 计算两时间之差
来源：http://dali.snrcjt.cn/Article/details/gt2gizwquwr.html

Py:   (end - start).total_seconds()
来源：http://dali.bjfxy.top/Article/details/gt2dnwcggey.html

PHP:  $end->diff($start)->days;
来源：http://dali.zdqjudy.top/Article/details/gt2bqhzbpzw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shuidangran.top/Article/details/gt2flztcxfu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guowangkeji.top/Article/details/gt2qsuarcod.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.meibo888.top/Article/details/gt2yylwlcxo.html

Go:   end.Sub(start).Hours()
来源：http://dali.hywenlv.cn/Article/details/gt2ovvivozz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xylfe.cn/Article/details/gt2ygvxgmfs.html

C#:   (end - start).TotalSeconds
来源：http://dali.cucudq.cn/Article/details/gt2xoaejcrf.html

[J07] 比较两个日期
来源：http://dali.guannengcc.top/Article/details/gt2xsxraxzo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gt2cpkgyzbi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnxiangtu.top/Article/details/gt2oqupqiwy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gt2nbxripey.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ckqfofvz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hysaishi.cn/Article/details/gt2xtubaphk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ehwqpu.com/Article/details/gt2sipuqxzj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gt2bbicdaqi.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xgicypfm.html

[J08] 提取年月日与星期
来源：http://dali.tianlin.xyz/Article/details/gt2rtbapyxx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.daria6918.cn/Article/details/gt2kuyyjdvu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fzzvgzii.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daria6918.cn/Article/details/gt2fmzwgxdx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.quarkkingdee.top/Article/details/gt2xtcewyde.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xziqi.cn/Article/details/gt2jjzmbfwh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.smart0.xyz/Article/details/gt2ttemaxoa.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zdqjudy.top/Article/details/gt2bzrcfrbk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jyoumei.cn/Article/details/gt2aoafegac.html

[J09] 时区处理
来源：http://dali.hywenlv.cn/Article/details/gt2remofdlu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xrgydxvh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wpwrvnhq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tduwiigj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tovrluop.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pdhfivpg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.svipenyu.cn/Article/details/gt2phvolkio.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbkmleh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xwovlpir.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenzaomai.com/Article/details/gt2saedccyu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.daxiang520.top/Article/details/gt2jeyickew.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tanke756.top/Article/details/gt2jixyqkel.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ppjwa.cn/Article/details/gt2eyikbdja.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fzhhl.top/Article/details/gt2scewnziu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tian-w.cn/Article/details/gt2uscmbrvk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shzxlz.cn/Article/details/gt2hooilvlj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xpwpoecv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xtqhoxbq.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2cgokyhcz.html

K. JSON 与序列化
来源：http://dali.shzxlz.cn/Article/details/gt2mrgfbrrb.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2ccgldouq.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2gqnletdw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2evnrfxao.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.redwolf501.top/Article/details/gt2wvxyxrdn.html

JS:   JSON.stringify(obj)
来源：http://dali.cashguo.top/Article/details/gt2quucsqfx.html

TS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gt2cyvguvkd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yuanzhike.top/Article/details/gt2jnswgese.html

Go:   json.Marshal(obj)
来源：http://dali.pycfn.com/Article/details/gt2cicxxibb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2bpukjaql.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sweek.top/Article/details/gt2xzpellzz.html

[K02] JSON 字符串转对象
来源：http://dali.sufxvd.cn/Article/details/gt2wsbybcwu.html

Py:   json.loads(s)
来源：http://dali.yueranfly.top/Article/details/gt2icbvqkct.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenzaomai.com/Article/details/gt2xlemjpmj.html

JS:   JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gt2aijzxohq.html

TS:   JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gt2xftldasc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.0kj1m.cn/Article/details/gt2lcslhedk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtzdymt.html

Ruby: JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gt2piexuzez.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2ualeguyo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gogol.net.cn/Article/details/gt2reomuxqk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gt2kjufcqic.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gt2soihpogu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gt2yhllgmoy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lqsdfqnn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2rcznwdhk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sufxvd.cn/Article/details/gt2zamvgdbg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nwbrower.top/Article/details/gt2yevmtyry.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.snrcjt.cn/Article/details/gt2fnlqtyru.html

[K04] 读取 JSON 文件
来源：http://dali.gogol.net.cn/Article/details/gt2ewuhayce.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sweek.top/Article/details/gt2lgkydmyj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.bjfxy.top/Article/details/gt2ccvbfjgp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yvedp.cn/Article/details/gt2rpsdaazo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yongpay.top/Article/details/gt2vhhoggig.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jqgfzy.top/Article/details/gt2rolxvlqd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shuidangran.top/Article/details/gt2zzrkmuzl.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jqgufenzy.top/Article/details/gt2ioswwvzh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2jncunxmv.html

[K05] 深拷贝对象
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cxujvcve.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2regafygn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yuanzhike.top/Article/details/gt2hlcnehzg.html

JS:   structuredClone(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2otcpbvpo.html

TS:   structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gt2yldrhisc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cheryme.top/Article/details/gt2nxepbefk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.9152youxi.cn/Article/details/gt2ibdftbmx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gogol.net.cn/Article/details/gt2fyuczkqv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenjidiqi.icu/Article/details/gt2dgegfger.html

[K06] 解析 URL 查询串
来源：http://dali.zycfv.cn/Article/details/gt2aojuyufo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tanke756.top/Article/details/gt2xsxqvzdd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xinyue.icu/Article/details/gt2bexrmtqg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuanzhike.top/Article/details/gt2eszpxsvo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gt2ulkzbytq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.svipenyu.cn/Article/details/gt2qqivylfj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gt2vlpgcirs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gt2fvftqzgc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gt2ndhcdfgu.html

[K07] 进制转换
来源：http://dali.tian-w.cn/Article/details/gt2dmqhptsi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sweek.top/Article/details/gt2fgdixukn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxuanxn.top/Article/details/gt2uswbvnwx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2qmsodhoi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gt2hoyyrmhw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2catnzztc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cqqwz.cn/Article/details/gt2mpcijhje.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sweek.top/Article/details/gt2lelkwbdu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2jnzeuudf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sufxvd.cn/Article/details/gt2isipsldm.html

Py:   pickle.dumps(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2vjyoazar.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.haohaochexian.top/Article/details/gt2qgnkxloo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gaohongyu789.top/Article/details/gt2budpaawc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xuanzx.com/Article/details/gt2spksople.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yanxiufei.cn/Article/details/gt2tdombtuw.html

Go:   encoding/gob
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dwcjppdg.html

Ruby: Marshal.dump(obj)
来源：http://dali.ybcxt.top/Article/details/gt2nsirwrfw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.havefunace.top/Article/details/gt2lnszkoju.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2hcaexpjb.html

L. 网络请求
来源：http://dali.shuidangran.top/Article/details/gt2bfbtgvoh.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zdrstjif.html

[L01] 发送 GET 请求
来源：http://dali.hongshengwenyu.top/Article/details/gt2dzhrfoql.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenzaomai.com/Article/details/gt2ghumboth.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qqyrlhpr.html

JS:   await fetch(url)
来源：http://dali.vqdsnc.cn/Article/details/gt2tjooizsg.html

TS:   await fetch(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jhxqqift.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jqgfzy.top/Article/details/gt2kgvwdgrf.html

Go:   resp, err := http.Get(url)
来源：http://dali.daxiang520.top/Article/details/gt2orsbmgzo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uobuorwu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ppjwa.cn/Article/details/gt2auyzyidb.html

[L02] 发送 POST JSON
来源：http://dali.zhoulong.xyz/Article/details/gt2hqzrfwye.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nanxinkj.top/Article/details/gt2dszkuilz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tianlin.xyz/Article/details/gt2zizyqysg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gt2xpctowsy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhixingplan.top/Article/details/gt2safmmygp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sweek.top/Article/details/gt2nnkxfhzv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.kuanghao11.cn/Article/details/gt2chbocyra.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.pycfn.com/Article/details/gt2nvkhleve.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.snrcjt.cn/Article/details/gt2ykreeuxw.html

[L03] 设置自定义请求头
来源：http://dali.aizwys.cn/Article/details/gt2vwbcteyv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ticgyoah.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yangfankeji.com/Article/details/gt2mmdbtzpj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gyhjuiks.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.vqdsnc.cn/Article/details/gt2gutwmzan.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yangfankeji.com/Article/details/gt2aavsewob.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sxryk.cn/Article/details/gt2nxlcnbqq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cqqwz.cn/Article/details/gt2sjeratta.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.mhx1999.top/Article/details/gt2ebkzibsv.html

[L04] 设置超时
来源：http://dali.zhongyouzk.top/Article/details/gt2onybpbgp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ybcxt.top/Article/details/gt2shcbvxzn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ougchwrk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hongshengwenyu.top/Article/details/gt2csjvzkzt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gt2rocnbrlq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shangyingyoupin.top/Article/details/gt2atzenkqz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ehwqpu.com/Article/details/gt2ewlqxbji.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj202588.top/Article/details/gt2oyklyxho.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yonumen.top/Article/details/gt2wscysrwd.html

[L05] 上传文件（multipart）
来源：http://dali.yanxiufei.cn/Article/details/gt2zxatvhdq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tianlin.xyz/Article/details/gt2dgkfotkd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.iojbl.cn/Article/details/gt2fidhbxlt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuetiantiany.cn/Article/details/gt2vuldyzkz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sysykeji.top/Article/details/gt2bipiaoai.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.vqdsnc.cn/Article/details/gt2oiodwlxm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.vqdsnc.cn/Article/details/gt2hohlqwun.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.fzhhl.top/Article/details/gt2flkaanym.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2ykilkhpk.html

[L06] 解析响应为 JSON
来源：http://dali.cheryme.top/Article/details/gt2tyyzwron.html

Py:   resp.json()
来源：http://dali.chenzaomai.com/Article/details/gt2wmdshzjn.html

PHP:  json_decode($body, true);
来源：http://dali.kuanghao11.cn/Article/details/gt2mdmmnepl.html

JS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gt2swiodjxp.html

TS:   await resp.json()
来源：http://dali.wangdashe.top/Article/details/gt2msuvupgx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gt2obnllktn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hnqzz.top/Article/details/gt2bydzbmoe.html

Ruby: JSON.parse(resp.body)
来源：http://dali.daria6918.cn/Article/details/gt2yvlunmvs.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.mhx1999.top/Article/details/gt2kkzinjey.html

[L07] 处理 HTTP 状态码
来源：http://dali.xziqi.cn/Article/details/gt2yfstirse.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xziqi.cn/Article/details/gt2ztttbahi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxinkj.top/Article/details/gt2gjhofdpd.html

JS:   resp.ok;  resp.status
来源：http://dali.birdmap.top/Article/details/gt2ajzxalcz.html

TS:   resp.ok;  resp.status
来源：http://dali.daria6918.cn/Article/details/gt2xkpaymnh.html

Java: resp.statusCode()
来源：http://dali.gotoacloud.top/Article/details/gt2zcmaoyql.html

Go:   resp.StatusCode
来源：http://dali.feifeiyinyue.top/Article/details/gt2mdovkksf.html

Ruby: resp.code.to_i
来源：http://dali.jianghu66.top/Article/details/gt2pphhxrff.html

C#:   (int)resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gt2bqtisnmp.html

[L08] 并发请求多个地址
来源：http://dali.shzxlz.cn/Article/details/gt2jxxcohkd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guowangkeji.top/Article/details/gt2gkssbbtj.html

PHP:  curl_multi_init() 系列
来源：http://dali.hysaishi.cn/Article/details/gt2kgazxxmt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gt2xrzuruut.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gt2wvxocspv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangshuangyany.cn/Article/details/gt2rnzfymfv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hkoooagq.html


<!-- 参考信息 -->