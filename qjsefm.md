代发 wailian999

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.fzhhl.top/Article/details/gt2owpbwdpo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhixingplan.top/Article/details/gt2zbxwtsdl.html

[I04] 正则替换
来源：http://dali.tianlin.xyz/Article/details/gt2itllhcyk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jianghu66.top/Article/details/gt2pkdmxbmt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2mshmhlvn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ydzc1.top/Article/details/gt2coibnnpq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jyoumei.cn/Article/details/gt2vphtbhtc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.c1oappe.top/Article/details/gt2bdbmiorf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jyoumei.cn/Article/details/gt2okxsbvbk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sweek.top/Article/details/gt2zmkujzhu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gt2wpqnmujf.html

[I05] 按正则拆分
来源：http://dali.jlsjyb.cn/Article/details/gt2ngkelfns.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tianlin.xyz/Article/details/gt2kijftxgh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2zbmotgqa.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gt2eflkqhxk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gt2rvcsoxvd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ehwqpu.com/Article/details/gt2pjpmzfqc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.haohaochexian.top/Article/details/gt2ebnthudl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gt2fnpvmmui.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.birdmap.top/Article/details/gt2flxbmuaf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.andypj.xyz/Article/details/gt2riemrzwl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yongpay.top/Article/details/gt2jsbfxkyv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xuetiantiany.cn/Article/details/gt2etrzlmhn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.havefunace.top/Article/details/gt2xnipdecx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gt2wfpagtea.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gt2oqgorfkh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.svipenyu.cn/Article/details/gt2lztqrhbj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sufxvd.cn/Article/details/gt2esaoirbj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gt2ghdugjkq.html

[I07] 忽略大小写与多行模式
来源：http://dali.haohaochexian.top/Article/details/gt2djxeodup.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zycfv.cn/Article/details/gt2vtgprvde.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tanke756.top/Article/details/gt2wyhrtmqx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.guannengcc.top/Article/details/gt2tawudwfc.html

TS:   /error/gim
来源：http://dali.xziqi.cn/Article/details/gt2xnprezib.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhixingplan.top/Article/details/gt2ejmxvsby.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xuetiantiany.cn/Article/details/gt2czjlkaxc.html

Ruby: s.scan(/error/i)
来源：http://dali.yangfankeji.com/Article/details/gt2ucjzmaez.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.birdmap.top/Article/details/gt2xidlfmjr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gzhubu.top/Article/details/gt2nysvqpld.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ydzc1.top/Article/details/gt2jwxjysjq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuanzx.com/Article/details/gt2dfpbtjhm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangdashe.top/Article/details/gt2tyekjpon.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pycfn.com/Article/details/gt2knzkpyhr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hywenlv.cn/Article/details/gt2khlstuqg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jlsjyb.cn/Article/details/gt2kublhgxz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cheryme.top/Article/details/gt2lwpijlmf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nwbrower.top/Article/details/gt2ezyjaadl.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2qtkaiedh.html

J. 日期与时间
来源：http://dali.316326.xyz/Article/details/gt2uneumhst.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2hswgrkuc.html

[J01] 获取当前时间
来源：http://dali.snrcjt.cn/Article/details/gt2dmhyjvzl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.316326.xyz/Article/details/gt2yvuvxvpf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gt2zpznvaig.html

JS:   new Date();  Date.now()
来源：http://dali.daxiang520.top/Article/details/gt2wchaxmba.html

TS:   new Date();  Date.now()
来源：http://dali.hysaishi.cn/Article/details/gt2sebkzvzl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cashguo.top/Article/details/gt2nkoavglp.html

Go:   time.Now()
来源：http://dali.yonumen.top/Article/details/gt2vfxqoudu.html

Ruby: Time.now
来源：http://dali.snrcjt.cn/Article/details/gt2tpqsheow.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.andypj.xyz/Article/details/gt2ehbpfntb.html

[J02] 格式化输出
来源：http://dali.zdqjudy.top/Article/details/gt2uwueztkc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gt2msaxhonh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gt2njhqrhgc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenjidiqi.icu/Article/details/gt2shtnuyun.html

TS:   d.toISOString()
来源：http://dali.vqdsnc.cn/Article/details/gt2srdmgxmq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.iojbl.cn/Article/details/gt2keamnwpo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yxxtnpyv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gt2aizpfmtx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xueyqxsj.html

[J03] 字符串解析为日期
来源：http://dali.yuxming.cn/Article/details/gt2irqfkqac.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.dianchejie.cn/Article/details/gt2anqwveqr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yanxiufei.cn/Article/details/gt2sdbvcxdx.html

JS:   new Date("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gt2wfdssida.html

TS:   new Date("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gt2hezpshti.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gt2vkuuskur.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gt2xcnbguas.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gt2tyraeozf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.quarkkingdee.top/Article/details/gt2lixqqxxp.html

[J04] 时间戳与日期互转
来源：http://dali.xziqi.cn/Article/details/gt2ktesdsha.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ivvv.top/Article/details/gt2axxrbkdd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shangyingyoupin.top/Article/details/gt2gnlrayui.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sxryk.cn/Article/details/gt2leorkuht.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhongyouzk.top/Article/details/gt2auodguel.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hfpthk.cn/Article/details/gt2tjpcpnjh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yueranfly.top/Article/details/gt2dsoebero.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.fengsongda.top/Article/details/gt2zsyozodx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2toejnefr.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhoulong.xyz/Article/details/gt2ntsipgby.html

Py:   now + timedelta(days=7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ttxbtghx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jlsjyb.cn/Article/details/gt2tsuhazfv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oiuaycrf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gt2wqtukcma.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.svipenyu.cn/Article/details/gt2zqfpxhgy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuxming.cn/Article/details/gt2myscjkcg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zycfv.cn/Article/details/gt2cxphexxs.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yueranfly.top/Article/details/gt2ldnaqdcz.html

[J06] 计算两时间之差
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bzjwpudx.html

Py:   (end - start).total_seconds()
来源：http://dali.gaohongyu789.top/Article/details/gt2yxpvmyqk.html

PHP:  $end->diff($start)->days;
来源：http://dali.andypj.xyz/Article/details/gt2icupguxu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.quarkkingdee.top/Article/details/gt2fovwwmgs.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.iojbl.cn/Article/details/gt2jaogtqyk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dldltake.html

Go:   end.Sub(start).Hours()
来源：http://dali.jlsjyb.cn/Article/details/gt2jpkbvzrl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gaohongyu789.top/Article/details/gt2spxpcbkz.html

C#:   (end - start).TotalSeconds
来源：http://dali.hfpthk.cn/Article/details/gt2kawoyvcc.html

[J07] 比较两个日期
来源：http://dali.pycfn.com/Article/details/gt2fpxqmcct.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gt2hheskatt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shuidangran.top/Article/details/gt2albtbjwm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hywenlv.cn/Article/details/gt2ngrxdfqw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gt2thhdnnfv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cashguo.top/Article/details/gt2ujkpokuo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jqgufenzy.top/Article/details/gt2dffmeuke.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gt2zppqtvbl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ugoleojs.html

[J08] 提取年月日与星期
来源：http://dali.ybcxt.top/Article/details/gt2cqgjdgvo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shuidangran.top/Article/details/gt2rlgpmwob.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.pycfn.com/Article/details/gt2ptssmgal.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinqigufen.top/Article/details/gt2crwhmzxy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.vqdsnc.cn/Article/details/gt2hlrkbwmk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinqigfzy.top/Article/details/gt2cjkslswl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.nanxinkj.top/Article/details/gt2kqnawpgg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.dianchejie.cn/Article/details/gt2fyfifzcs.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuanzhike.top/Article/details/gt2jpvpduyl.html

[J09] 时区处理
来源：http://dali.sufxvd.cn/Article/details/gt2uviixfft.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gotoacloud.top/Article/details/gt2vssbcsos.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gotoacloud.top/Article/details/gt2nqsbbkwe.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2deedjyxh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lqtfqqcy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tianlin.xyz/Article/details/gt2ujuxmxha.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenlongwang.top/Article/details/gt2bwmnahpq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xuetiantiany.cn/Article/details/gt2xertoiie.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinqigfzy.top/Article/details/gt2hghdqzrx.html

[J10] 取今天 / 本月第一天
来源：http://dali.jlsjyb.cn/Article/details/gt2uaobeytu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gotoacloud.top/Article/details/gt2uqdykebb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.bjfxy.top/Article/details/gt2qlgisvom.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sxryk.cn/Article/details/gt2kkihbdsv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yueranfly.top/Article/details/gt2xvnadutq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2zetjcdqd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hywenlv.cn/Article/details/gt2mkhefvai.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yongpay.top/Article/details/gt2appgyjds.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2odkaoofn.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2ppewxczc.html

K. JSON 与序列化
来源：http://dali.xylfe.cn/Article/details/gt2nszelkea.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2nmtkzmtl.html

[K01] 对象转 JSON 字符串
来源：http://dali.fengsongda.top/Article/details/gt2qurpbwdk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.c1oappe.top/Article/details/gt2lgqwdcms.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yonumen.top/Article/details/gt2dequztjt.html

JS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gt2cpznbmwf.html

TS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2sqlifkra.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj20258888.top/Article/details/gt2bkgochfa.html

Go:   json.Marshal(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hctqgbig.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yueranfly.top/Article/details/gt2dixuazsm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ynfpifnl.html

[K02] JSON 字符串转对象
来源：http://dali.xylfe.cn/Article/details/gt2haaeflwv.html

Py:   json.loads(s)
来源：http://dali.gotoacloud.top/Article/details/gt2gkbbbkvb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sysykeji.top/Article/details/gt2tstydooc.html

JS:   JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gt2kwrinait.html

TS:   JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gt2adbxdxdg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bhqaezje.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gt2ezawqbnn.html

Ruby: JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gt2rvqjhmkt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258888.top/Article/details/gt2nxneijhv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj202588.top/Article/details/gt2eymiaeze.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2epwfafmp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhoulong.xyz/Article/details/gt2rcgswiqj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gt2hjxwuhuh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.guannengcc.top/Article/details/gt2ngtcqece.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2bopzsvni.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gotoacloud.top/Article/details/gt2zprxsxjw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ppfckmao.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258888.top/Article/details/gt2ilknribn.html

[K04] 读取 JSON 文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2xgfasdkp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.daria6918.cn/Article/details/gt2lvoqlxpg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.snrcjt.cn/Article/details/gt2nodeyytd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2qcbtnpmh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gt2uwybeodx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gt2hlxwmeej.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ijkmkmwe.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.c1oappe.top/Article/details/gt2ezvkhown.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xziqi.cn/Article/details/gt2jknsktdj.html

[K05] 深拷贝对象
来源：http://dali.daria6918.cn/Article/details/gt2xkedqvgd.html

Py:   copy.deepcopy(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2txnntzeh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ehwqpu.com/Article/details/gt2gmjwettm.html

JS:   structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gt2cvscmcjl.html

TS:   structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fnaqyjrq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yuanzhike.top/Article/details/gt2rubpxzsr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.fzhhl.top/Article/details/gt2lymgstat.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hfpthk.cn/Article/details/gt2izhnpcvu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cashguo.top/Article/details/gt2mrfljeee.html

[K06] 解析 URL 查询串
来源：http://dali.zdqjudy.top/Article/details/gt2timcycxr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.redwolf501.top/Article/details/gt2oleseuri.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jianghu66.top/Article/details/gt2dcirzote.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gt2kexfqndp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gt2yihhwkoh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hongshengwenyu.top/Article/details/gt2abierivo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gt2psxhkwzy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gt2sodilkwt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gt2zpmdloya.html

[K07] 进制转换
来源：http://dali.havefunace.top/Article/details/gt2lksqcmyc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gt2lunbnmbf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.andypj.xyz/Article/details/gt2hjiszryj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2szdrzces.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gt2rqmoifue.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2xtvpryls.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jianghu66.top/Article/details/gt2djdfworw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.fzhhl.top/Article/details/gt2cevzfvzq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gt2rofxpbgt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ybcxt.top/Article/details/gt2ioxnugdf.html

Py:   pickle.dumps(obj)
来源：http://dali.xziqi.cn/Article/details/gt2oryqiprz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2kfojxvfq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gt2qyhhxyhe.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.0kj1m.cn/Article/details/gt2bkvnjrrz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.andypj.xyz/Article/details/gt2iklwvmnw.html

Go:   encoding/gob
来源：http://dali.sufxvd.cn/Article/details/gt2bsskompd.html

Ruby: Marshal.dump(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hkqzuocp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.wangdashe.top/Article/details/gt2fntppyel.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2gryenhic.html

L. 网络请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lngtzltl.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2sjekddiy.html

[L01] 发送 GET 请求
来源：http://dali.fzhhl.top/Article/details/gt2yampknwg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xinyue.icu/Article/details/gt2oaybbncs.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhongyouzk.top/Article/details/gt2helcntfc.html

JS:   await fetch(url)
来源：http://dali.aibaodan.cn/Article/details/gt2lxzhwkyi.html

TS:   await fetch(url)
来源：http://dali.c1oappe.top/Article/details/gt2sxuvhpad.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.feifeiyinyue.top/Article/details/gt2rbnyjmtt.html

Go:   resp, err := http.Get(url)
来源：http://dali.mhx1999.top/Article/details/gt2mukvzdzk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj20258.top/Article/details/gt2qyntiqne.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jyoumei.cn/Article/details/gt2brvcbkwe.html

[L02] 发送 POST JSON
来源：http://dali.yj20258.top/Article/details/gt2vkrhdxdi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.fzhhl.top/Article/details/gt2hgwxbghc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cheryme.top/Article/details/gt2rvfsytlf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxuanxn.top/Article/details/gt2nfmmnzxe.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shuidangran.top/Article/details/gt2ekkrmvpj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.quarkkingdee.top/Article/details/gt2czbryohq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.redwolf501.top/Article/details/gt2ljjmbchg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sufxvd.cn/Article/details/gt2aizknrcg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.haohaochexian.top/Article/details/gt2plazsgea.html

[L03] 设置自定义请求头
来源：http://dali.yueranfly.top/Article/details/gt2drbfgfev.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yonumen.top/Article/details/gt2iktjggrl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gotoacloud.top/Article/details/gt2ozqshywj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shzxlz.cn/Article/details/gt2ruzeonpj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tianlin.xyz/Article/details/gt2btmiboha.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dianchejie.cn/Article/details/gt2jxdwbzkg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gt2hzzorrre.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zdqjudy.top/Article/details/gt2wffsmobg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yongpay.top/Article/details/gt2izfbzsqm.html

[L04] 设置超时
来源：http://dali.yvedp.cn/Article/details/gt2tkxkkcsv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.0kj1m.cn/Article/details/gt2rvocnvzp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tian-w.cn/Article/details/gt2imzrsngy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuetiantiany.cn/Article/details/gt2ckfgqppw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gt2ssfcdcyt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yueranfly.top/Article/details/gt2toksxkeq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.snrcjt.cn/Article/details/gt2kyadjspp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tian-w.cn/Article/details/gt2mpxmafvw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.iojbl.cn/Article/details/gt2cvchemuv.html

[L05] 上传文件（multipart）
来源：http://dali.hfpthk.cn/Article/details/gt2tvuewymo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.316326.xyz/Article/details/gt2duvmucls.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qlanifgg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sxryk.cn/Article/details/gt2saogwuth.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shzxlz.cn/Article/details/gt2slfnwyie.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sxryk.cn/Article/details/gt2rormsgwk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.andypj.xyz/Article/details/gt2jraiihwt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hammf.cn/Article/details/gt2kfutzspt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2qfcyoroi.html

[L06] 解析响应为 JSON
来源：http://dali.tianlin.xyz/Article/details/gt2sipbfjsu.html

Py:   resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gt2bgtzkcky.html

PHP:  json_decode($body, true);
来源：http://dali.havefunace.top/Article/details/gt2prgyhzul.html

JS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gt2lmnoovyk.html

TS:   await resp.json()
来源：http://dali.xuanzx.com/Article/details/gt2mvcocunm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gt2qwimexoi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pnbaqgfl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sysykeji.top/Article/details/gt2jsivlttw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.quarkkingdee.top/Article/details/gt2gmpioprr.html

[L07] 处理 HTTP 状态码
来源：http://dali.ppjwa.cn/Article/details/gt2tfuaddbu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jlsjyb.cn/Article/details/gt2xdcfpbly.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.daria6918.cn/Article/details/gt2rnvrliff.html

JS:   resp.ok;  resp.status
来源：http://dali.pycfn.com/Article/details/gt2uwmohxrx.html

TS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gt2cjamwnne.html

Java: resp.statusCode()
来源：http://dali.feifeiyinyue.top/Article/details/gt2iugprwhr.html

Go:   resp.StatusCode
来源：http://dali.tianlin.xyz/Article/details/gt2plemnfyk.html

Ruby: resp.code.to_i
来源：http://dali.jyoumei.cn/Article/details/gt2vsthqxrc.html

C#:   (int)resp.StatusCode
来源：http://dali.pycfn.com/Article/details/gt2lamsvfab.html

[L08] 并发请求多个地址
来源：http://dali.ydzc1.top/Article/details/gt2eiotmpri.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.quarkkingdee.top/Article/details/gt2masvdjcn.html

PHP:  curl_multi_init() 系列
来源：http://dali.hfpthk.cn/Article/details/gt2cjudfeff.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pycfn.com/Article/details/gt2zmgeimmo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dianchejie.cn/Article/details/gt2weuseetf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fzhhl.top/Article/details/gt2zbknincv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hnxiangtu.top/Article/details/gt2huyktkdj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gt2ptbnmnwp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hfpthk.cn/Article/details/gt2uwyjcxiq.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2kxoucabq.html

M. 命令行 / 进程 / 环境
来源：http://dali.quarkkingdee.top/Article/details/gt2wqtnnffx.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2cyhvqxjh.html

[M01] 读取命令行参数
来源：http://dali.ivvv.top/Article/details/gt2zhsbstsd.html

Py:   sys.argv[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2togxphcu.html

PHP:  $argv;  $argc;
来源：http://dali.aibaodan.cn/Article/details/gt2dvvznmta.html

JS:   process.argv.slice(2)
来源：http://dali.yvedp.cn/Article/details/gt2psaivmbg.html

TS:   process.argv.slice(2)
来源：http://dali.yongpay.top/Article/details/gt2gacebxdq.html

Java: args 数组（main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gt2nocenenu.html

Go:   os.Args[1:]
来源：http://dali.jianghu66.top/Article/details/gt2dikectzc.html


<!-- 参考信息 -->