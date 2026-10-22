代发 wailian999

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.quarkkingdee.top/Article/details/gtpoakwxld.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hywenlv.cn/Article/details/gtowgjrxgy.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shuidangran.top/Article/details/gtkrzlmaoa.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.wangdashe.top/Article/details/gtiibbqzmj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtpvtuvmev.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.316326.xyz/Article/details/gtxcqsdbsn.html

[I04] 正则替换
来源：http://dali.pycfn.com/Article/details/gtjinepzxk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xziqi.cn/Article/details/gteuiwacwo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnqzz.top/Article/details/gtshhdrvfo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nwbrower.top/Article/details/gtopyddcsd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gtcgbiabyd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gticzucazc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.9152youxi.cn/Article/details/gteunyrzlv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtkpkiwaps.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tian-w.cn/Article/details/gtnczgtiso.html

[I05] 按正则拆分
来源：http://dali.daxiang520.top/Article/details/gtwaxltvgk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sufxvd.cn/Article/details/gteezsumsn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tanke756.top/Article/details/gtsbvstqtk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gtpchozyzz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gtnhkzqdda.html

Java: s.split("\\s*,\\s*")
来源：http://dali.smart0.xyz/Article/details/gtxoswkwxj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ybcxt.top/Article/details/gttxbbwmqa.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gtdnangugq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sweek.top/Article/details/gtwanqeifk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cdnleiting.top/Article/details/gtxivkoowx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gtldhntyrn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hywenlv.cn/Article/details/gtiydmzauj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gtaoteberj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gtaxqckysq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gtbfayuoky.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ydzc1.top/Article/details/gtdyqqjiqm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdnusnjk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gtvucrvnbx.html

[I07] 忽略大小写与多行模式
来源：http://dali.shzxlz.cn/Article/details/gtqvepfxnw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangshuangyany.cn/Article/details/gtmwmahcme.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hfpthk.cn/Article/details/gtmjttlrmp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jqgufenzy.top/Article/details/gtmwkcykiy.html

TS:   /error/gim
来源：http://dali.sufxvd.cn/Article/details/gtudhlljhw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.c1oappe.top/Article/details/gtctpigbwg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tianlin.xyz/Article/details/gtidqilxte.html

Ruby: s.scan(/error/i)
来源：http://dali.haohaochexian.top/Article/details/gtjyibzwjo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gaohongyu789.top/Article/details/gttunogzfc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.9152youxi.cn/Article/details/gtbbvwvqkd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daxiang520.top/Article/details/gtdjullysx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.quarkkingdee.top/Article/details/gtjlkjeyur.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gtbqzixmbp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.316326.xyz/Article/details/gtckawkihg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuanzx.com/Article/details/gtnfujihob.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gogol.net.cn/Article/details/gtilqbyiac.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.daxiang520.top/Article/details/gtsyiggerb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zdqjudy.top/Article/details/gtpdvhmirm.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtxqencdxd.html

J. 日期与时间
来源：http://dali.redwolf501.top/Article/details/gtpnuuwapg.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtdyyaykty.html

[J01] 获取当前时间
来源：http://dali.yuxming.cn/Article/details/gtrvwbbsqh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.redwolf501.top/Article/details/gttzjzforp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sweek.top/Article/details/gtmkrtjxbn.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gtihdkcyyc.html

TS:   new Date();  Date.now()
来源：http://dali.jyoumei.cn/Article/details/gtmlmxixpx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.meibo888.top/Article/details/gthjbzmrqp.html

Go:   time.Now()
来源：http://dali.yuxming.cn/Article/details/gtpxgnhuht.html

Ruby: Time.now
来源：http://dali.quarkkingdee.top/Article/details/gtftnneiaj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hywenlv.cn/Article/details/gtwrbptdtj.html

[J02] 格式化输出
来源：http://dali.hnxiangtu.top/Article/details/gtiqiomlov.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gtaarofwtu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinqigufen.top/Article/details/gtmpnerivz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ehwqpu.com/Article/details/gtdatbeujc.html

TS:   d.toISOString()
来源：http://dali.wangshuangyany.cn/Article/details/gtpkkliybe.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sufxvd.cn/Article/details/gtgzdzceoy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.redwolf501.top/Article/details/gtvcukwhcz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daria6918.cn/Article/details/gtllzloyyz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.iojbl.cn/Article/details/gtahbmnhaq.html

[J03] 字符串解析为日期
来源：http://dali.jinghuilouyu.cn/Article/details/gtxfyoghfc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ivvv.top/Article/details/gtzqkxlcqq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ehwqpu.com/Article/details/gtvitgzuvo.html

JS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtdcmjivmk.html

TS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtgkmkxnsi.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtfbpnqsta.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtvirjzhoj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtsyezapqy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.aibaodan.cn/Article/details/gtinhredkj.html

[J04] 时间戳与日期互转
来源：http://dali.chenzaomai.com/Article/details/gtnhdmoumd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtmxknhzpo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.iojbl.cn/Article/details/gtcqhdwisr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ppjwa.cn/Article/details/gtvnetefsf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.quarkkingdee.top/Article/details/gtgqdoxoek.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinqigfzy.top/Article/details/gtnxhvzkfh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nwbrower.top/Article/details/gtagikapjt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.vqdsnc.cn/Article/details/gtkdukvmcj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sysykeji.top/Article/details/gtyoobawcy.html

[J05] 时间加减（加 7 天）
来源：http://dali.redwolf501.top/Article/details/gtjncezqdw.html

Py:   now + timedelta(days=7)
来源：http://dali.jianghu66.top/Article/details/gtgaledyol.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zycfv.cn/Article/details/gtqtgxpatw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuxming.cn/Article/details/gtmdylmqzn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.0kj1m.cn/Article/details/gtggfvsjee.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jqgfzy.top/Article/details/gtynzuzpwg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.wangdashe.top/Article/details/gtpuaphhjb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yonumen.top/Article/details/gtgynahnhj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.aizwys.cn/Article/details/gteyzanqpi.html

[J06] 计算两时间之差
来源：http://dali.mhx1999.top/Article/details/gtrpcmiwwt.html

Py:   (end - start).total_seconds()
来源：http://dali.dianchejie.cn/Article/details/gtbxtloizh.html

PHP:  $end->diff($start)->days;
来源：http://dali.xuanzx.com/Article/details/gtfbsqjyjg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yonumen.top/Article/details/gtscvavevf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xylfe.cn/Article/details/gtvekebznh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gogol.net.cn/Article/details/gtotbgfbwk.html

Go:   end.Sub(start).Hours()
来源：http://dali.dashuyun.cn/Article/details/gtkerkpdgr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cqqwz.cn/Article/details/gtlndogsdq.html

C#:   (end - start).TotalSeconds
来源：http://dali.gogol.net.cn/Article/details/gtdelhqxmd.html

[J07] 比较两个日期
来源：http://dali.sxryk.cn/Article/details/gtdbsdzbwv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gtlbbobrbl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.smart0.xyz/Article/details/gtdecdckmc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.316326.xyz/Article/details/gtbvkcgoed.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tanke756.top/Article/details/gtjchlaque.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.vqdsnc.cn/Article/details/gtulhqcote.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ydzc1.top/Article/details/gtkhcyuscm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gtwrdzhqdx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gtapjiltuo.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gtpsobmosx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jianghu66.top/Article/details/gtlxhbvqzm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.aizwys.cn/Article/details/gtfdfdrexn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jqgufenzy.top/Article/details/gtufllphfu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yonumen.top/Article/details/gtmkugyune.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj20258.top/Article/details/gtxfibvqck.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.dianchejie.cn/Article/details/gthkuvzghu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jiagoushi.top/Article/details/gtjqootpso.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj202588.top/Article/details/gtngzrwciv.html

[J09] 时区处理
来源：http://dali.9152youxi.cn/Article/details/gtrdcpvxfk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.fzhhl.top/Article/details/gtwmudnguc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.quarkkingdee.top/Article/details/gtupcaizak.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgufenzy.top/Article/details/gtaobzdlmy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gttvcxkriz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tian-w.cn/Article/details/gtzmktvdjo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.aibaodan.cn/Article/details/gtrnfayqij.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hfpthk.cn/Article/details/gtmluifmgn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258.top/Article/details/gtpilvbmst.html

[J10] 取今天 / 本月第一天
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhxwkved.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yueranfly.top/Article/details/gtttyiumyk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xuanzx.com/Article/details/gtytiocgrf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jlsjyb.cn/Article/details/gtraimowqa.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yueranfly.top/Article/details/gtwvcdqfhe.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.meibo888.top/Article/details/gtlnsezsuu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jiagoushi.top/Article/details/gtwzufvlrj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hywenlv.cn/Article/details/gtbhtmdhkf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmqkldstq.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtjrvyjjaf.html

K. JSON 与序列化
来源：http://dali.yonumen.top/Article/details/gtrxsgmmlc.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtfhsyfvmn.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxuanxn.top/Article/details/gtthxnaxhn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cashguo.top/Article/details/gtbdxepobw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cqqwz.cn/Article/details/gtqqwnrbuh.html

JS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gtigzpgxtn.html

TS:   JSON.stringify(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtoskercam.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ybcxt.top/Article/details/gtxddlfsfh.html

Go:   json.Marshal(obj)
来源：http://dali.sxryk.cn/Article/details/gtocvexlqp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmqpkmnz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtixcnores.html

[K02] JSON 字符串转对象
来源：http://dali.haohaochexian.top/Article/details/gtfruqgwin.html

Py:   json.loads(s)
来源：http://dali.cashguo.top/Article/details/gtlzmpints.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ybcxt.top/Article/details/gtnzggzfgi.html

JS:   JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwqdzaxd.html

TS:   JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gtbsqzdicx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zdqjudy.top/Article/details/gtsqswscpu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhoulong.xyz/Article/details/gtobzcyeuf.html

Ruby: JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwlejgkgn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.snrcjt.cn/Article/details/gtqspcsngq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xinyue.icu/Article/details/gtjbxkqhtp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.smart0.xyz/Article/details/gtldhqdyrh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.vqdsnc.cn/Article/details/gturnihkqc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gtwheifrmv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gteytchwnh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.mhx1999.top/Article/details/gtmeiboczn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.9152youxi.cn/Article/details/gtmkpqnwmh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gzhubu.top/Article/details/gtrxysrqgv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuanzhike.top/Article/details/gtzitdnlzc.html

[K04] 读取 JSON 文件
来源：http://dali.tian-w.cn/Article/details/gtwnbtlgmv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gaohongyu789.top/Article/details/gtmrloncmm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hammf.cn/Article/details/gtzbwazsxl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gtnhzpfglg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.316326.xyz/Article/details/gtcamnoywf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gtqmllzjtr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hnxiangtu.top/Article/details/gtqavggaid.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daxiang520.top/Article/details/gtwlrbacuc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.pengpengdd.cyou/Article/details/gthtvwbqrz.html

[K05] 深拷贝对象
来源：http://dali.tianlin.xyz/Article/details/gtchwaqxgv.html

Py:   copy.deepcopy(obj)
来源：http://dali.mhx1999.top/Article/details/gtkdvjxjba.html

PHP:  unserialize(serialize($obj));
来源：http://dali.iojbl.cn/Article/details/gtupkyofka.html

JS:   structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gtylnqypro.html

TS:   structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gtxpghfgql.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jlsjyb.cn/Article/details/gturvenrwx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.meibo888.top/Article/details/gtnewqppvy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hywenlv.cn/Article/details/gtqcnlewjr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj20258888.top/Article/details/gtwjucdqlg.html

[K06] 解析 URL 查询串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwsjhogbs.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.havefunace.top/Article/details/gtygjflijx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ybcxt.top/Article/details/gtkloutnuo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jlsjyb.cn/Article/details/gtehiafsbm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj202588.top/Article/details/gtxnaakfki.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinqigufen.top/Article/details/gtegpfkivl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnubxckkx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gtahqdxcsc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzudiafrg.html

[K07] 进制转换
来源：http://dali.snrcjt.cn/Article/details/gtupwgqbwg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtklgijigq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.snrcjt.cn/Article/details/gtcblckans.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gthwbjxixm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtxxxqpnze.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gtyxzugbsu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cqqwz.cn/Article/details/gtqgvjlqxg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqnttfvwt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtjeyluczv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.316326.xyz/Article/details/gtnaeekkhz.html

Py:   pickle.dumps(obj)
来源：http://dali.daria6918.cn/Article/details/gtkjfcjkbt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sufxvd.cn/Article/details/gtyzedhexu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gogol.net.cn/Article/details/gtxldcbqfc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.9152youxi.cn/Article/details/gtwivcdppj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinqigfzy.top/Article/details/gtejwlpblc.html

Go:   encoding/gob
来源：http://dali.birdmap.top/Article/details/gtxucfscgs.html

Ruby: Marshal.dump(obj)
来源：http://dali.sweek.top/Article/details/gthzqcxjij.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gtnildegpc.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtbremdzbb.html

L. 网络请求
来源：http://dali.zhoulong.xyz/Article/details/gtwdqnrkcj.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtuctazfiw.html

[L01] 发送 GET 请求
来源：http://dali.jinqigufen.top/Article/details/gtkpvfilor.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hfpthk.cn/Article/details/gtjjtrtxtm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sufxvd.cn/Article/details/gtwkblbjsq.html

JS:   await fetch(url)
来源：http://dali.c1oappe.top/Article/details/gtilaejoxc.html

TS:   await fetch(url)
来源：http://dali.wangdashe.top/Article/details/gtaunsnlss.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sweek.top/Article/details/gtyarmivvq.html

Go:   resp, err := http.Get(url)
来源：http://dali.hywenlv.cn/Article/details/gtdhpcpgjz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinghuilouyu.cn/Article/details/gtkgkovkgu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nanxinkj.top/Article/details/gtyhmrlkfw.html

[L02] 发送 POST JSON
来源：http://dali.jqgufenzy.top/Article/details/gtwyltydra.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yonumen.top/Article/details/gtuxsfulmc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.vqdsnc.cn/Article/details/gtcvnqhdtu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dianchejie.cn/Article/details/gtdwpqprql.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gtfockovti.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.0kj1m.cn/Article/details/gtsvyijrjn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.kuanghao11.cn/Article/details/gtmgwoqrpq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhiwuduotai.top/Article/details/gtydepyrll.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.c1oappe.top/Article/details/gtktqeixmf.html

[L03] 设置自定义请求头
来源：http://dali.kuanghao11.cn/Article/details/gthfumftuv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.svipenyu.cn/Article/details/gtmubgmvyb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtyurenpqm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hfpthk.cn/Article/details/gtczdzsiei.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tian-w.cn/Article/details/gtsafjjshk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ivvv.top/Article/details/gtnbcjcggb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.wangdashe.top/Article/details/gtnzetazsa.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhiwuduotai.top/Article/details/gtrkfdvmfl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.fengsongda.top/Article/details/gtphmuxczh.html

[L04] 设置超时
来源：http://dali.ybcxt.top/Article/details/gtuwwlacqu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtciekhfck.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenzaomai.com/Article/details/gtnpjurjms.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgufenzy.top/Article/details/gtychrklju.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxuanxn.top/Article/details/gtvevbsbwo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tanke756.top/Article/details/gtpbnzqhfo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.haohaochexian.top/Article/details/gtveiwsplk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hnqzz.top/Article/details/gtuykvrvem.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ppjwa.cn/Article/details/gtsrqkunnq.html

[L05] 上传文件（multipart）
来源：http://dali.cucudq.cn/Article/details/gtfmaamedp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.vqdsnc.cn/Article/details/gthwqpqoyc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpclazpny.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxinkj.top/Article/details/gtmnmliarh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gtogcyudml.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shzxlz.cn/Article/details/gtsssxvufv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gzhubu.top/Article/details/gtjrztjtyc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpfdssyyc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtwveduxvg.html

[L06] 解析响应为 JSON
来源：http://dali.yueranfly.top/Article/details/gtuvoeoczj.html

Py:   resp.json()
来源：http://dali.nanxinkj.top/Article/details/gtpszbxbrz.html

PHP:  json_decode($body, true);
来源：http://dali.gzhubu.top/Article/details/gtsiwfjadh.html

JS:   await resp.json()
来源：http://dali.svipenyu.cn/Article/details/gtzntuhlbd.html

TS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gtolvhjtlv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ydzc1.top/Article/details/gtfxhaddyd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jyoumei.cn/Article/details/gtcevdikhw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hysaishi.cn/Article/details/gthntxsgqw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zycfv.cn/Article/details/gtdwmjigfk.html

[L07] 处理 HTTP 状态码
来源：http://dali.yuanzhike.top/Article/details/gtppswgdvh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.fzhhl.top/Article/details/gtgtsdvahd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sweek.top/Article/details/gtncqohtkj.html

JS:   resp.ok;  resp.status
来源：http://dali.haohaochexian.top/Article/details/gturygdivq.html

TS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gtplflnqny.html

Java: resp.statusCode()
来源：http://dali.havefunace.top/Article/details/gtdjjuoibq.html

Go:   resp.StatusCode
来源：http://dali.yonumen.top/Article/details/gtvthfyxhs.html

Ruby: resp.code.to_i
来源：http://dali.sxryk.cn/Article/details/gtwdibpdqh.html

C#:   (int)resp.StatusCode
来源：http://dali.vqdsnc.cn/Article/details/gtgbpwkwgp.html

[L08] 并发请求多个地址
来源：http://dali.smart0.xyz/Article/details/gtakbmdkhy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxrzjlri.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj20258888.top/Article/details/gtspfdfhgj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gtxvmvpsbn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gtaynwnruf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nwbrower.top/Article/details/gtwdwdqwmx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yongpay.top/Article/details/gtcdmnzgvs.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.pycfn.com/Article/details/gtnglocciu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aizwys.cn/Article/details/gtuvgdkdvi.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtmdarkufw.html

M. 命令行 / 进程 / 环境
来源：http://dali.smart0.xyz/Article/details/gthclgplum.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtwspktpnd.html

[M01] 读取命令行参数
来源：http://dali.birdmap.top/Article/details/gthficywsz.html

Py:   sys.argv[1:]
来源：http://dali.yj202588.top/Article/details/gtwpatdhid.html

PHP:  $argv;  $argc;
来源：http://dali.fengsongda.top/Article/details/gtkunolgno.html


<!-- 参考信息 -->