代发 wailian999

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shuidangran.top/Article/details/gt2sngdlhmm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.dianchejie.cn/Article/details/gt2rczgyukj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yuxming.cn/Article/details/gt2rltnzfpx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hammf.cn/Article/details/gt2dubhqzol.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj20258.top/Article/details/gt2emsoqvma.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cashguo.top/Article/details/gt2mecbvxbm.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oerzjucm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nwbrower.top/Article/details/gt2jtkbkbvo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tianlin.xyz/Article/details/gt2towvzmgi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yangfankeji.com/Article/details/gt2tdalejej.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gt2rikxiwdg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yangfankeji.com/Article/details/gt2vffbbunh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.snrcjt.cn/Article/details/gt2bsdidsjr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yvedp.cn/Article/details/gt2khwgbdon.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shzxlz.cn/Article/details/gt2ksuulltp.html

[I05] 按正则拆分
来源：http://dali.xuanzx.com/Article/details/gt2nfzhfskc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ppjwa.cn/Article/details/gt2qsnlzbtd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nwbrower.top/Article/details/gt2iwglvmsz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ztkiymbf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2bvjnyhts.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhixingplan.top/Article/details/gt2wxduklch.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hrivnzsb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gt2etvaptlk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.snrcjt.cn/Article/details/gt2bcjqduyk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.smart0.xyz/Article/details/gt2doyslgly.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gt2jpqdplff.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cucudq.cn/Article/details/gt2mwzqvlha.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhoulong.xyz/Article/details/gt2qvojpthw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pycfn.com/Article/details/gt2ffggizey.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gt2hztpysqo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.havefunace.top/Article/details/gt2etruriqd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.c1oappe.top/Article/details/gt2dzomfslw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gt2leccyvkk.html

[I07] 忽略大小写与多行模式
来源：http://dali.dianchejie.cn/Article/details/gt2cteekwsk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dashuyun.cn/Article/details/gt2bqeuonpa.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gt2ldbkjswq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sufxvd.cn/Article/details/gt2xlbpdjmi.html

TS:   /error/gim
来源：http://dali.zdqjudy.top/Article/details/gt2pkttlfsf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.bjfxy.top/Article/details/gt2jhaohrnr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.kuanghao11.cn/Article/details/gt2zqclpyfa.html

Ruby: s.scan(/error/i)
来源：http://dali.redwolf501.top/Article/details/gt2qphfhgxa.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cheryme.top/Article/details/gt2qrdewubl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhiwuduotai.top/Article/details/gt2apfhiuda.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hammf.cn/Article/details/gt2hxofziec.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.havefunace.top/Article/details/gt2obtnipzm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cdnleiting.top/Article/details/gt2ztcsuuys.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sweek.top/Article/details/gt2vppnydhu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuetiantiany.cn/Article/details/gt2pwfyomou.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangshuangyany.cn/Article/details/gt2nkrowbbt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.quarkkingdee.top/Article/details/gt2lciyemri.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenzaomai.com/Article/details/gt2iqnacjio.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2sruobibp.html

J. 日期与时间
来源：http://dali.pengpengdd.cyou/Article/details/gt2jqlixuyp.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2romxheid.html

[J01] 获取当前时间
来源：http://dali.redwolf501.top/Article/details/gt2vmwfwzki.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuanzx.com/Article/details/gt2ihgpxbeb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gt2jmrcvlfn.html

JS:   new Date();  Date.now()
来源：http://dali.gogol.net.cn/Article/details/gt2xfjukbpv.html

TS:   new Date();  Date.now()
来源：http://dali.yuxming.cn/Article/details/gt2xaimjscf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhongyouzk.top/Article/details/gt2mxyssusg.html

Go:   time.Now()
来源：http://dali.yvedp.cn/Article/details/gt2ghbrutti.html

Ruby: Time.now
来源：http://dali.jlsjyb.cn/Article/details/gt2fccofmum.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jqgufenzy.top/Article/details/gt2bxwsoyge.html

[J02] 格式化输出
来源：http://dali.hysaishi.cn/Article/details/gt2awwtojzh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ppjwa.cn/Article/details/gt2cfanehhp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zycfv.cn/Article/details/gt2cnilfcbd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.316326.xyz/Article/details/gt2ssoeornh.html

TS:   d.toISOString()
来源：http://dali.sweek.top/Article/details/gt2pzdhavnu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.haohaochexian.top/Article/details/gt2iifdkkvc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj20258888.top/Article/details/gt2xzumqjjs.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dwginlqh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.birdmap.top/Article/details/gt2typnqtrv.html

[J03] 字符串解析为日期
来源：http://dali.gogol.net.cn/Article/details/gt2tlpxuwts.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cucudq.cn/Article/details/gt2qduqdnwg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.redwolf501.top/Article/details/gt2xaaiprrc.html

JS:   new Date("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gt2gswrkvcy.html

TS:   new Date("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2liojdjya.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gt2hvqheovx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gt2syzsxlri.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gt2ixspklex.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.aizwys.cn/Article/details/gt2knflrdbg.html

[J04] 时间戳与日期互转
来源：http://dali.sysykeji.top/Article/details/gt2zyskvlvn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tanke756.top/Article/details/gt2iuwtxkqf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.redwolf501.top/Article/details/gt2yukidnyv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jianghu66.top/Article/details/gt2qrsvzmdh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.guowangkeji.top/Article/details/gt2pcfvoxbc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.iojbl.cn/Article/details/gt2iktscacg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2osryiqkq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zycfv.cn/Article/details/gt2gduuyyha.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yueranfly.top/Article/details/gt2ravwjveo.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgfzy.top/Article/details/gt2bcgjrzyb.html

Py:   now + timedelta(days=7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2duwbskjb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hysaishi.cn/Article/details/gt2dmvctpic.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhoulong.xyz/Article/details/gt2lvcueivt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.mhx1999.top/Article/details/gt2mdhkukmt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nanxinkj.top/Article/details/gt2xlvskscy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jyoumei.cn/Article/details/gt2sexfvtgy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhengqikj.top/Article/details/gt2tacgfbzw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.mhx1999.top/Article/details/gt2ixsleokj.html

[J06] 计算两时间之差
来源：http://dali.redwolf501.top/Article/details/gt2qypyfbeo.html

Py:   (end - start).total_seconds()
来源：http://dali.redwolf501.top/Article/details/gt2caxixlci.html

PHP:  $end->diff($start)->days;
来源：http://dali.cqqwz.cn/Article/details/gt2jfudbciq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jyoumei.cn/Article/details/gt2gdjleucs.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhixingplan.top/Article/details/gt2rauyazcm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.c1oappe.top/Article/details/gt2yjqxhqtu.html

Go:   end.Sub(start).Hours()
来源：http://dali.sweek.top/Article/details/gt2nksvoilo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yonumen.top/Article/details/gt2dqehvklo.html

C#:   (end - start).TotalSeconds
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wnuzfnkb.html

[J07] 比较两个日期
来源：http://dali.316326.xyz/Article/details/gt2xrxihizr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gt2fofwztco.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.vqdsnc.cn/Article/details/gt2cfwsdtts.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sweek.top/Article/details/gt2muatafrs.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gt2gjjxmirt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.smart0.xyz/Article/details/gt2omlmbxpl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aeplcxpw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gt2uxtjpbfp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gt2bdbmxbkn.html

[J08] 提取年月日与星期
来源：http://dali.yj202588.top/Article/details/gt2slelevnt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgfzy.top/Article/details/gt2qbhbymop.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jiagoushi.top/Article/details/gt2vfmteugx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hysaishi.cn/Article/details/gt2loeyskzh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shangyingyoupin.top/Article/details/gt2jnrmkqxk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ehwqpu.com/Article/details/gt2lfsxgrpy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hfpthk.cn/Article/details/gt2cpnscphf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinqigufen.top/Article/details/gt2fstjzmvv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.redwolf501.top/Article/details/gt2xqwneyic.html

[J09] 时区处理
来源：http://dali.tian-w.cn/Article/details/gt2hcpqcudf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.daria6918.cn/Article/details/gt2ykfjmzvn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.quarkkingdee.top/Article/details/gt2uqcfaxdt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258888.top/Article/details/gt2mclqwiqj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gt2bdmisxmd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xylfe.cn/Article/details/gt2qfpgpfnh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.316326.xyz/Article/details/gt2bcmbdtlj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ikoyeqjx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.0kj1m.cn/Article/details/gt2pdepdllb.html

[J10] 取今天 / 本月第一天
来源：http://dali.kuanghao11.cn/Article/details/gt2yukmaajt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.guowangkeji.top/Article/details/gt2bfohwgdi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.pengpengdd.cyou/Article/details/gt2rtpsfyov.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gogol.net.cn/Article/details/gt2yecahhhw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2dnxjakiy.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.meibo888.top/Article/details/gt2tuceikhg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sweek.top/Article/details/gt2zodigikk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xinyue.icu/Article/details/gt2uzvcvols.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.svipenyu.cn/Article/details/gt2yqlfxmgu.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2ybvpflgg.html

K. JSON 与序列化
来源：http://dali.cheryme.top/Article/details/gt2hhuagyjm.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2sktrvkyn.html

[K01] 对象转 JSON 字符串
来源：http://dali.mhx1999.top/Article/details/gt2myygdrha.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gt2njfbwsro.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.svipenyu.cn/Article/details/gt2nevrapmw.html

JS:   JSON.stringify(obj)
来源：http://dali.cucudq.cn/Article/details/gt2dfkbabej.html

TS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lnrconrs.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.quarkkingdee.top/Article/details/gt2shieqyte.html

Go:   json.Marshal(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2kbupphzf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ybcxt.top/Article/details/gt2odftndzv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2htzmcblg.html

[K02] JSON 字符串转对象
来源：http://dali.yanxiufei.cn/Article/details/gt2fqayyxbm.html

Py:   json.loads(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rsxrsktk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuanzx.com/Article/details/gt2lttlugdx.html

JS:   JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gt2bswsxvpa.html

TS:   JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gt2ltmwxojs.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhengqikj.top/Article/details/gt2ivnncvfx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hnddjqou.html

Ruby: JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gt2rqvhzvdn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cdnleiting.top/Article/details/gt2afcyorzs.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenjidiqi.icu/Article/details/gt2umoedlvq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dianchejie.cn/Article/details/gt2peflmvui.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gt2ukkbwyzs.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.bjfxy.top/Article/details/gt2xevrtoeu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gt2iaiklclu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2allvdfql.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.bjfxy.top/Article/details/gt2rwpaachh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.pycfn.com/Article/details/gt2tezhuodc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sweek.top/Article/details/gt2wrvcfgas.html

[K04] 读取 JSON 文件
来源：http://dali.zhengqikj.top/Article/details/gt2tymzomuv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj20258888.top/Article/details/gt2kvskzbhj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shangyingyoupin.top/Article/details/gt2bgrxtepa.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgfzy.top/Article/details/gt2ssceabjm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.birdmap.top/Article/details/gt2koqbzufh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zycfv.cn/Article/details/gt2mxksupyt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xziqi.cn/Article/details/gt2exoopetq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj20258888.top/Article/details/gt2osdfztnc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ivvv.top/Article/details/gt2jmthcwnv.html

[K05] 深拷贝对象
来源：http://dali.zdqjudy.top/Article/details/gt2rfabovpn.html

Py:   copy.deepcopy(obj)
来源：http://dali.nwbrower.top/Article/details/gt2qghrqqui.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dashuyun.cn/Article/details/gt2mrdbdatq.html

JS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2ldqasuha.html

TS:   structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2lzvchwtc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sufxvd.cn/Article/details/gt2xjxqbnnv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangshuangyany.cn/Article/details/gt2edmycivn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xylfe.cn/Article/details/gt2jofbetil.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.havefunace.top/Article/details/gt2nongfodv.html

[K06] 解析 URL 查询串
来源：http://dali.tianlin.xyz/Article/details/gt2txkjqlcc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zdqjudy.top/Article/details/gt2scgedxty.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ivvv.top/Article/details/gt2rjsxkags.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ehwqpu.com/Article/details/gt2vnumnzsj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gt2xqaaqbcy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.havefunace.top/Article/details/gt2sastfatp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ubedofjh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gt2evlcfmsd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gt2iezhomcc.html

[K07] 进制转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rukeasdl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gt2clhfvtlu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yuxming.cn/Article/details/gt2qrvkkvku.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2nmmlotov.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gt2vvxuepfk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gt2mtjvnwpw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cheryme.top/Article/details/gt2wwhgrytb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tian-w.cn/Article/details/gt2slolqixt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gt2tzenyppt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nanxuanxn.top/Article/details/gt2kulysqgh.html

Py:   pickle.dumps(obj)
来源：http://dali.smart0.xyz/Article/details/gt2uyuxxpcq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ehwqpu.com/Article/details/gt2njyqmgmg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.aizwys.cn/Article/details/gt2uxppearl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gt2yvaksmax.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yangfankeji.com/Article/details/gt2kjqdfqde.html

Go:   encoding/gob
来源：http://dali.kuanghao11.cn/Article/details/gt2kcxihmpo.html

Ruby: Marshal.dump(obj)
来源：http://dali.ivvv.top/Article/details/gt2bjtajnqd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gt2fhrrstij.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2bpsiwwuo.html

L. 网络请求
来源：http://dali.kuanghao11.cn/Article/details/gt2fdprzdbw.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2foxngrrx.html

[L01] 发送 GET 请求
来源：http://dali.jiagoushi.top/Article/details/gt2nxcrcdnf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenzaomai.com/Article/details/gt2enmpzcgs.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hfpthk.cn/Article/details/gt2uowlyxzw.html

JS:   await fetch(url)
来源：http://dali.kuanghao11.cn/Article/details/gt2njuzlpob.html

TS:   await fetch(url)
来源：http://dali.ybcxt.top/Article/details/gt2wsrlrkcu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jqgufenzy.top/Article/details/gt2bixpwcbl.html

Go:   resp, err := http.Get(url)
来源：http://dali.dashuyun.cn/Article/details/gt2ccnspxje.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hywenlv.cn/Article/details/gt2naydqhuw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.redwolf501.top/Article/details/gt2lzozmtoz.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gogyecvg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gt2qjtzovmj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gfyjopbg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gt2blwytfxm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigufen.top/Article/details/gt2mjsgepcp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hysaishi.cn/Article/details/gt2kilownmn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.aizwys.cn/Article/details/gt2rhugomrn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hfpthk.cn/Article/details/gt2mvnnndrg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhengqikj.top/Article/details/gt2igchgrql.html

[L03] 设置自定义请求头
来源：http://dali.yangfankeji.com/Article/details/gt2wypkqfjg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jiagoushi.top/Article/details/gt2acdqpamg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xobhqpss.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sufxvd.cn/Article/details/gt2gxgcbstw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.iojbl.cn/Article/details/gt2srmurgol.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xuetiantiany.cn/Article/details/gt2mtuyuhex.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.dashuyun.cn/Article/details/gt2yxiubjij.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.havefunace.top/Article/details/gt2oikiimxb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj202588.top/Article/details/gt2ouiwncho.html

[L04] 设置超时
来源：http://dali.jiagoushi.top/Article/details/gt2ytvdvyel.html

Py:   requests.get(url, timeout=5)
来源：http://dali.feifeiyinyue.top/Article/details/gt2czyzpujt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ehwqpu.com/Article/details/gt2exmafrns.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gt2dcjijdlq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.0kj1m.cn/Article/details/gt2yxvibdow.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.wangdashe.top/Article/details/gt2mhchiwmc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yongpay.top/Article/details/gt2sudqsgdh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenlongwang.top/Article/details/gt2opxirueq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xuanzx.com/Article/details/gt2bgclndgi.html

[L05] 上传文件（multipart）
来源：http://dali.feifeiyinyue.top/Article/details/gt2yzcosofx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxinkj.top/Article/details/gt2krxadseg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aobstlij.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhixingplan.top/Article/details/gt2npkwuhnj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gt2pqvhwsph.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sufxvd.cn/Article/details/gt2kniggumk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jyoumei.cn/Article/details/gt2xrmbufvi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jiagoushi.top/Article/details/gt2grubaihi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.birdmap.top/Article/details/gt2btyforql.html

[L06] 解析响应为 JSON
来源：http://dali.jqgfzy.top/Article/details/gt2oficfsxl.html

Py:   resp.json()
来源：http://dali.shuidangran.top/Article/details/gt2qitfnixu.html

PHP:  json_decode($body, true);
来源：http://dali.gotoacloud.top/Article/details/gt2vtzngxdj.html

JS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gt2uvgampkj.html

TS:   await resp.json()
来源：http://dali.tianlin.xyz/Article/details/gt2jqqlhzct.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hywenlv.cn/Article/details/gt2gtlsahjm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yueranfly.top/Article/details/gt2igrrxcnm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shuidangran.top/Article/details/gt2jjezhdff.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xuanzx.com/Article/details/gt2afovwwmv.html

[L07] 处理 HTTP 状态码
来源：http://dali.jyoumei.cn/Article/details/gt2vexjiuvo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cheryme.top/Article/details/gt2daiizwaj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj20258.top/Article/details/gt2eqeyvwav.html

JS:   resp.ok;  resp.status
来源：http://dali.dianchejie.cn/Article/details/gt2rkccxcrc.html

TS:   resp.ok;  resp.status
来源：http://dali.sysykeji.top/Article/details/gt2fpystifc.html

Java: resp.statusCode()
来源：http://dali.quarkkingdee.top/Article/details/gt2txozjmpm.html

Go:   resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gt2fsaqfohk.html

Ruby: resp.code.to_i
来源：http://dali.jlsjyb.cn/Article/details/gt2gjrxceuh.html

C#:   (int)resp.StatusCode
来源：http://dali.cheryme.top/Article/details/gt2dtokouij.html

[L08] 并发请求多个地址
来源：http://dali.zhongyouzk.top/Article/details/gt2dyuexlbm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gaohongyu789.top/Article/details/gt2girjkaem.html

PHP:  curl_multi_init() 系列
来源：http://dali.jlsjyb.cn/Article/details/gt2zdwklugx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.quarkkingdee.top/Article/details/gt2hrvyelhr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gt2pnyhbjyo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.smart0.xyz/Article/details/gt2ohtazylt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gogol.net.cn/Article/details/gt2tmuwkzhp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.guannengcc.top/Article/details/gt2bgzoarbh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.kuanghao11.cn/Article/details/gt2xvtuikkk.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2lixmoauu.html

M. 命令行 / 进程 / 环境
来源：http://dali.yanxiufei.cn/Article/details/gt2xhtwfptb.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2tvfvhtob.html

[M01] 读取命令行参数
来源：http://dali.tanke756.top/Article/details/gt2ffwqjwny.html

Py:   sys.argv[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gt2bxaljcpl.html

PHP:  $argv;  $argc;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ktilarau.html


<!-- 参考信息 -->