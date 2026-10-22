代发 wailian999

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.bjfxy.top/Article/details/gt2oiuasnxs.html

[I03] 提取捕获分组
来源：http://dali.zhengqikj.top/Article/details/gt2snuestpr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jyoumei.cn/Article/details/gt2yoyhgrdx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ppjwa.cn/Article/details/gt2whcmksxj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangdashe.top/Article/details/gt2djwlmyet.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cheryme.top/Article/details/gt2zkaxtemk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aizwys.cn/Article/details/gt2rlxwelqq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sxryk.cn/Article/details/gt2nyipwuhm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhoulong.xyz/Article/details/gt2aeyvpheb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhiwuduotai.top/Article/details/gt2clvbmnbu.html

[I04] 正则替换
来源：http://dali.fzhhl.top/Article/details/gt2miiieqzv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cdnleiting.top/Article/details/gt2zaqcocrq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2kmjvdthg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gt2ynwvgjlq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258888.top/Article/details/gt2skhwhhfb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jlsjyb.cn/Article/details/gt2myhukbkj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gt2pcxomnmt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.andypj.xyz/Article/details/gt2dhkcmlje.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ftjkbrhl.html

[I05] 按正则拆分
来源：http://dali.meibo888.top/Article/details/gt2agmrzagi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ydzc1.top/Article/details/gt2qtcvpovb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yueranfly.top/Article/details/gt2vdniezzx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gt2syybotnn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gt2bwqyzitn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ydzc1.top/Article/details/gt2ezhtqqjr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gotoacloud.top/Article/details/gt2qeczsgex.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gt2oinajgrn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhoulong.xyz/Article/details/gt2ncjxylte.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuxming.cn/Article/details/gt2cjilhwcx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gt2nvretvgj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hongshengwenyu.top/Article/details/gt2fehlbcpb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fengsongda.top/Article/details/gt2evnnmcqs.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xziqi.cn/Article/details/gt2aqrghjub.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gt2uprkuukk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pycfn.com/Article/details/gt2ycmltzuk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hysaishi.cn/Article/details/gt2qedppylz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gt2odjoqare.html

[I07] 忽略大小写与多行模式
来源：http://dali.kuanghao11.cn/Article/details/gt2ayyuebhq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ivvv.top/Article/details/gt2yhpzzfiz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xinyue.icu/Article/details/gt2ztvkjzag.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xylfe.cn/Article/details/gt2zzahfxvz.html

TS:   /error/gim
来源：http://dali.shangyingyoupin.top/Article/details/gt2lzughdkn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.guannengcc.top/Article/details/gt2ctftyjii.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.guannengcc.top/Article/details/gt2fgripnjk.html

Ruby: s.scan(/error/i)
来源：http://dali.xuanzx.com/Article/details/gt2zaxlgdld.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jianghu66.top/Article/details/gt2uxaboplf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hnxiangtu.top/Article/details/gt2wnapcldb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ybcxt.top/Article/details/gt2cjxryhiw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.pengpengdd.cyou/Article/details/gt2xysvvfpv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gt2pqgxhkwr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dwafjbqi.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.c1oappe.top/Article/details/gt2zlwleurf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nanxuanxn.top/Article/details/gt2jrywefus.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.svipenyu.cn/Article/details/gt2zdnknhyl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jqgufenzy.top/Article/details/gt2vezbbkpm.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2yyeexqcn.html

J. 日期与时间
来源：http://dali.gaohongyu789.top/Article/details/gt2tepjhjwg.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uvlwkkxm.html

[J01] 获取当前时间
来源：http://dali.ydzc1.top/Article/details/gt2oshgeyzd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.kuanghao11.cn/Article/details/gt2jqnqhqhg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jianghu66.top/Article/details/gt2ckdhmooq.html

JS:   new Date();  Date.now()
来源：http://dali.jinqigfzy.top/Article/details/gt2kmiszvet.html

TS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gt2jdxhoxqh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cucudq.cn/Article/details/gt2mrfoursb.html

Go:   time.Now()
来源：http://dali.0kj1m.cn/Article/details/gt2ohbulgal.html

Ruby: Time.now
来源：http://dali.hnqzz.top/Article/details/gt2qwgnshai.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuanzhike.top/Article/details/gt2jrxqvwdn.html

[J02] 格式化输出
来源：http://dali.9152youxi.cn/Article/details/gt2odyqqbjh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxuanxn.top/Article/details/gt2jffgltwk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.svipenyu.cn/Article/details/gt2sipgwgia.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jiagoushi.top/Article/details/gt2tvgnfqqu.html

TS:   d.toISOString()
来源：http://dali.zhiwuduotai.top/Article/details/gt2nwacmbog.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yongpay.top/Article/details/gt2enoznpbw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ojsmgkka.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ydzc1.top/Article/details/gt2lbsbkzyw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hongshengwenyu.top/Article/details/gt2bqbfqami.html

[J03] 字符串解析为日期
来源：http://dali.yueranfly.top/Article/details/gt2blqknmlo.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenjidiqi.icu/Article/details/gt2czagomkn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.kuanghao11.cn/Article/details/gt2vmljxdtr.html

JS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2phicquik.html

TS:   new Date("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2rodtanao.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2zmmsfqxy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gt2xzwxgkdr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2exeieacr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wvxqtazr.html

[J04] 时间戳与日期互转
来源：http://dali.tianlin.xyz/Article/details/gt2zlchpidn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sxryk.cn/Article/details/gt2zkpqdosj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fzhhl.top/Article/details/gt2zdeyqyqh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhixingplan.top/Article/details/gt2orrilvxl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nanxuanxn.top/Article/details/gt2viplhprp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxinkj.top/Article/details/gt2fjwplmqj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fengsongda.top/Article/details/gt2frbvkegb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sxryk.cn/Article/details/gt2ioqqaeec.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tian-w.cn/Article/details/gt2sjvhoyry.html

[J05] 时间加减（加 7 天）
来源：http://dali.hammf.cn/Article/details/gt2wmfzvxsn.html

Py:   now + timedelta(days=7)
来源：http://dali.aibaodan.cn/Article/details/gt2dmddciag.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xziqi.cn/Article/details/gt2uyswdqqc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gt2emtnynxu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zycfv.cn/Article/details/gt2ekpwimzv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fengsongda.top/Article/details/gt2njvxoofh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yonumen.top/Article/details/gt2hoifiqtu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.haohaochexian.top/Article/details/gt2poajdllx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ydzc1.top/Article/details/gt2yqibkxtt.html

[J06] 计算两时间之差
来源：http://dali.sxryk.cn/Article/details/gt2eqkgfcsm.html

Py:   (end - start).total_seconds()
来源：http://dali.hywenlv.cn/Article/details/gt2xghanktg.html

PHP:  $end->diff($start)->days;
来源：http://dali.guowangkeji.top/Article/details/gt2kfdrdmxk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.quarkkingdee.top/Article/details/gt2mqtidosi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.dashuyun.cn/Article/details/gt2inigecwj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dashuyun.cn/Article/details/gt2prfngzfo.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2elapmfsb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jiagoushi.top/Article/details/gt2umsciqjl.html

C#:   (end - start).TotalSeconds
来源：http://dali.cashguo.top/Article/details/gt2lvislczs.html

[J07] 比较两个日期
来源：http://dali.zhijiandao.cn/Article/details/gt2uqblzwof.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gt2xbwedgym.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aizwys.cn/Article/details/gt2pzxchkcs.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gogol.net.cn/Article/details/gt2kqxilaoq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cdnleiting.top/Article/details/gt2escoazpl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.guannengcc.top/Article/details/gt2follclui.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zrwyvyvo.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gt2bqxctrkj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gt2ohekghfz.html

[J08] 提取年月日与星期
来源：http://dali.316326.xyz/Article/details/gt2hwmvpkqx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.mhx1999.top/Article/details/gt2tdmvlnmt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnqzz.top/Article/details/gt2qkfyzcic.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.quarkkingdee.top/Article/details/gt2dfwcydoh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.guowangkeji.top/Article/details/gt2bbbspall.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.c1oappe.top/Article/details/gt2wpjwadhg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.nanxinkj.top/Article/details/gt2kgealbyu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.havefunace.top/Article/details/gt2drqismsr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj202588.top/Article/details/gt2sdzizqjy.html

[J09] 时区处理
来源：http://dali.xinyue.icu/Article/details/gt2ndzvsmjz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hnqzz.top/Article/details/gt2jmsgmlhi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daria6918.cn/Article/details/gt2xafvmioo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gt2gsqyesee.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yongpay.top/Article/details/gt2nwpncyat.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenzaomai.com/Article/details/gt2gkvloxph.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tianlin.xyz/Article/details/gt2meywioft.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ehwqpu.com/Article/details/gt2tgwjnyvj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.snrcjt.cn/Article/details/gt2nliqcvag.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenzaomai.com/Article/details/gt2acgexpff.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.0kj1m.cn/Article/details/gt2mtvoopjo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zycfv.cn/Article/details/gt2sismfafm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj202588.top/Article/details/gt2lzmxwfvz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daxiang520.top/Article/details/gt2yajdzipg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eimvhyyw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhixingplan.top/Article/details/gt2notqkjmk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.daxiang520.top/Article/details/gt2kpqcvihk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zycfv.cn/Article/details/gt2kumhnrkg.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2mdckcxpa.html

K. JSON 与序列化
来源：http://dali.aibaodan.cn/Article/details/gt2usnxozjg.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2fgftsqve.html

[K01] 对象转 JSON 字符串
来源：http://dali.birdmap.top/Article/details/gt2dcpxbbal.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.wangdashe.top/Article/details/gt2cpifkyhs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hywenlv.cn/Article/details/gt2utxfiajo.html

JS:   JSON.stringify(obj)
来源：http://dali.meibo888.top/Article/details/gt2lqwxezsm.html

TS:   JSON.stringify(obj)
来源：http://dali.daria6918.cn/Article/details/gt2vsnfptaa.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.fengsongda.top/Article/details/gt2misykzqa.html

Go:   json.Marshal(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2kwtucfuo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nanxuanxn.top/Article/details/gt2hzuuhmmu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.havefunace.top/Article/details/gt2zdhuojmp.html

[K02] JSON 字符串转对象
来源：http://dali.hywenlv.cn/Article/details/gt2jmcmszfe.html

Py:   json.loads(s)
来源：http://dali.snrcjt.cn/Article/details/gt2ngrqsfwg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2qxgxzphl.html

JS:   JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gt2klglpuyu.html

TS:   JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gt2vcarrvho.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxinkj.top/Article/details/gt2kirraufr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gt2rulnpkkm.html

Ruby: JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gt2aquynthy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.daria6918.cn/Article/details/gt2ivcnwnvo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jiagoushi.top/Article/details/gt2xbpqdsdb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xinyue.icu/Article/details/gt2dgkyxjrr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.daxiang520.top/Article/details/gt2lqvcgthw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zzjllpub.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gt2vpeabxwy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2kfkwaofa.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tanke756.top/Article/details/gt2yduuyulq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2ihptskpr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2djebgfqv.html

[K04] 读取 JSON 文件
来源：http://dali.redwolf501.top/Article/details/gt2tvlmjgzd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shzxlz.cn/Article/details/gt2mnrewvbb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.0kj1m.cn/Article/details/gt2akyltydz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.iojbl.cn/Article/details/gt2fgzfowgz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.kuanghao11.cn/Article/details/gt2pjjwpefn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gt2jqvlcgvx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hnxiangtu.top/Article/details/gt2ygeolxma.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pycfn.com/Article/details/gt2xxwvsebu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.bjfxy.top/Article/details/gt2eyglchev.html

[K05] 深拷贝对象
来源：http://dali.bjfxy.top/Article/details/gt2nirorcmv.html

Py:   copy.deepcopy(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2odrvsgvc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yvedp.cn/Article/details/gt2yeejxyly.html

JS:   structuredClone(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2iouyjvob.html

TS:   structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gt2smsphtsj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.dianchejie.cn/Article/details/gt2chpibcqr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jianghu66.top/Article/details/gt2zurrdsma.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tanke756.top/Article/details/gt2prngepet.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fengsongda.top/Article/details/gt2nyatjtns.html

[K06] 解析 URL 查询串
来源：http://dali.hammf.cn/Article/details/gt2rdtxrwgk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xinyue.icu/Article/details/gt2gcaisepv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenzaomai.com/Article/details/gt2mxebhlqv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258.top/Article/details/gt2rcjsdhfl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jianghu66.top/Article/details/gt2hujeiayn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jiagoushi.top/Article/details/gt2bknkojjd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gt2tnembzrm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gt2wozwqjpc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gt2arrsivvu.html

[K07] 进制转换
来源：http://dali.pycfn.com/Article/details/gt2azdrbdlo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gt2sjydaqzi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.birdmap.top/Article/details/gt2pakufnfy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gt2yjfdkvbo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gt2wskfuwfr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ckxsfyqm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tian-w.cn/Article/details/gt2qoefxcgo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.aizwys.cn/Article/details/gt2ziwlvjet.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gt2rwwtdnzc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gotoacloud.top/Article/details/gt2dhfxdtoq.html

Py:   pickle.dumps(obj)
来源：http://dali.gzhubu.top/Article/details/gt2qfvogyhk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ppjwa.cn/Article/details/gt2mhjwkcla.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zycfv.cn/Article/details/gt2xfriyixa.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.guannengcc.top/Article/details/gt2pmvghfsa.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.quarkkingdee.top/Article/details/gt2oioscwih.html

Go:   encoding/gob
来源：http://dali.cheryme.top/Article/details/gt2ieswadue.html

Ruby: Marshal.dump(obj)
来源：http://dali.yueranfly.top/Article/details/gt2qxetrlyb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.wangdashe.top/Article/details/gt2dugykihj.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2ejprevly.html

L. 网络请求
来源：http://dali.redwolf501.top/Article/details/gt2qlnedzaw.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2qgxxraje.html

[L01] 发送 GET 请求
来源：http://dali.snrcjt.cn/Article/details/gt2ujszexuf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.andypj.xyz/Article/details/gt2tufosttp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sweek.top/Article/details/gt2sueuyhqp.html

JS:   await fetch(url)
来源：http://dali.0kj1m.cn/Article/details/gt2ipxwaous.html

TS:   await fetch(url)
来源：http://dali.hnxiangtu.top/Article/details/gt2ugyxekkm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2nasbewwo.html

Go:   resp, err := http.Get(url)
来源：http://dali.nanxuanxn.top/Article/details/gt2srvptmfv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yuanzhike.top/Article/details/gt2crumxmyb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhixingplan.top/Article/details/gt2oxzaigfc.html

[L02] 发送 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gt2fnylores.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.aibaodan.cn/Article/details/gt2pglpxaqt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.daria6918.cn/Article/details/gt2gpngpuui.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.feifeiyinyue.top/Article/details/gt2fpfvmbwy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aizwys.cn/Article/details/gt2jlkbupgt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gwsbincn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sysykeji.top/Article/details/gt2cbtgpmsi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.quarkkingdee.top/Article/details/gt2sychilxj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yonumen.top/Article/details/gt2fzhaewrs.html

[L03] 设置自定义请求头
来源：http://dali.snrcjt.cn/Article/details/gt2zkoodrkq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.aibaodan.cn/Article/details/gt2hhhopiks.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cqqwz.cn/Article/details/gt2chbxapjp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.bjfxy.top/Article/details/gt2rjilejgx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gt2qzcmdwnr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sufxvd.cn/Article/details/gt2cjtvulyp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sysykeji.top/Article/details/gt2ofyocmqb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yuanzhike.top/Article/details/gt2azxqqvhg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hammf.cn/Article/details/gt2rlswhkpo.html

[L04] 设置超时
来源：http://dali.cheryme.top/Article/details/gt2oaeusynq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.snrcjt.cn/Article/details/gt2xqpxpvwy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wdjpfvxe.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuanzx.com/Article/details/gt2odrcqkgz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pengpengdd.cyou/Article/details/gt2oegbhbhm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.meibo888.top/Article/details/gt2zbkblceb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangdashe.top/Article/details/gt2igzhqesv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.iojbl.cn/Article/details/gt2lylemltn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ppjwa.cn/Article/details/gt2xszuiggm.html

[L05] 上传文件（multipart）
来源：http://dali.xylfe.cn/Article/details/gt2ytejockn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.meibo888.top/Article/details/gt2tegfozim.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.daxiang520.top/Article/details/gt2pkysghze.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gt2ngwqqdop.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigfzy.top/Article/details/gt2ehykssqx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.wangshuangyany.cn/Article/details/gt2oyrwyexg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nanxinkj.top/Article/details/gt2lilflrfc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.havefunace.top/Article/details/gt2rjojkpkx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj20258.top/Article/details/gt2ubptmlxo.html

[L06] 解析响应为 JSON
来源：http://dali.nanxinkj.top/Article/details/gt2iguiekni.html

Py:   resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2elcktgiu.html

PHP:  json_decode($body, true);
来源：http://dali.yanxiufei.cn/Article/details/gt2pcflhovl.html

JS:   await resp.json()
来源：http://dali.0kj1m.cn/Article/details/gt2cffloazo.html

TS:   await resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kkcqxzrb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.andypj.xyz/Article/details/gt2dbuaxagl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ydzc1.top/Article/details/gt2fctlmixx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.wangshuangyany.cn/Article/details/gt2usadzggi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wkhusird.html

[L07] 处理 HTTP 状态码
来源：http://dali.yongpay.top/Article/details/gt2iiiqydoj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.bjfxy.top/Article/details/gt2ccobfmux.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bhykhkur.html

JS:   resp.ok;  resp.status
来源：http://dali.cashguo.top/Article/details/gt2zsfhsmwe.html

TS:   resp.ok;  resp.status
来源：http://dali.0kj1m.cn/Article/details/gt2cngarvgh.html

Java: resp.statusCode()
来源：http://dali.jyoumei.cn/Article/details/gt2ngpcgrrz.html

Go:   resp.StatusCode
来源：http://dali.hywenlv.cn/Article/details/gt2dkiqamab.html

Ruby: resp.code.to_i
来源：http://dali.iojbl.cn/Article/details/gt2oijfqgjs.html

C#:   (int)resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fwmhxktc.html

[L08] 并发请求多个地址
来源：http://dali.gaohongyu789.top/Article/details/gt2xmosvoto.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.smart0.xyz/Article/details/gt2ffbdyhvi.html

PHP:  curl_multi_init() 系列
来源：http://dali.hnxiangtu.top/Article/details/gt2fmvdoknd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gt2ifazdxuw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gt2bwpofssv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hysaishi.cn/Article/details/gt2wxcvfzwr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hysaishi.cn/Article/details/gt2vqjrdgon.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhixingplan.top/Article/details/gt2wxqodubm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jqgufenzy.top/Article/details/gt2wswrmfbn.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rifqjtcg.html

M. 命令行 / 进程 / 环境
来源：http://dali.mhx1999.top/Article/details/gt2ohrihgoc.html


<!-- 参考信息 -->