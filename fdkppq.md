代发 wailian999

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhiwuduotai.top/Article/details/gt2wkdnsntq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hywenlv.cn/Article/details/gt2wozidowa.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zycfv.cn/Article/details/gt2pbwatprb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.c1oappe.top/Article/details/gt2dqhwecss.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zycfv.cn/Article/details/gt2pkstnuxu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yonumen.top/Article/details/gt2sopbsriq.html

[I04] 正则替换
来源：http://dali.smart0.xyz/Article/details/gt2iuxkbxmv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.fzhhl.top/Article/details/gt2ikzlgkfs.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zycfv.cn/Article/details/gt2koepwvuu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.guowangkeji.top/Article/details/gt2fydyapsu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cqqwz.cn/Article/details/gt2atofpcyk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zdqjudy.top/Article/details/gt2wnccichh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gotoacloud.top/Article/details/gt2ypnkqspz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gaohongyu789.top/Article/details/gt2dbxztdkk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yangfankeji.com/Article/details/gt2bdpfrzwj.html

[I05] 按正则拆分
来源：http://dali.shuidangran.top/Article/details/gt2ploglxut.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jianghu66.top/Article/details/gt2yetmazaf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xuanzx.com/Article/details/gt2ditbknfj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gt2wexsobwc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gt2fqzxbahy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.guowangkeji.top/Article/details/gt2lmtrmvue.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yonumen.top/Article/details/gt2jtgkjghe.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gt2ckzuyrpt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.feifeiyinyue.top/Article/details/gt2zrcipvxg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.svipenyu.cn/Article/details/gt2khznnivs.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gt2cljvbtln.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qpwhxmnz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.iojbl.cn/Article/details/gt2llyfzmzp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xinyue.icu/Article/details/gt2akiqchmg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gt2gzmostbh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tanke756.top/Article/details/gt2nbiaqoik.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.kuanghao11.cn/Article/details/gt2bndoqryl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gt2sgmqjzxk.html

[I07] 忽略大小写与多行模式
来源：http://dali.jlsjyb.cn/Article/details/gt2svwuvjmq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pcoteuwr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.havefunace.top/Article/details/gt2dibkvqdm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.haohaochexian.top/Article/details/gt2lkpdghzc.html

TS:   /error/gim
来源：http://dali.zycfv.cn/Article/details/gt2tfyqqfky.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.0kj1m.cn/Article/details/gt2kmhvsoqy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tanke756.top/Article/details/gt2phbtdyol.html

Ruby: s.scan(/error/i)
来源：http://dali.smart0.xyz/Article/details/gt2yektupwk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yvedp.cn/Article/details/gt2tvyhohqq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yonumen.top/Article/details/gt2vcpyluem.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.pycfn.com/Article/details/gt2haxcsmgs.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gt2ymfgczuh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhoulong.xyz/Article/details/gt2klgjmtlb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mivzkylj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.wangshuangyany.cn/Article/details/gt2fhwenbfz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uidkshob.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gzhubu.top/Article/details/gt2rfijuqnp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hnqzz.top/Article/details/gt2tlzexpll.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2ajrchjfy.html

J. 日期与时间
来源：http://dali.chenlongwang.top/Article/details/gt2vsrzpdxb.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2uwugaahl.html

[J01] 获取当前时间
来源：http://dali.meibo888.top/Article/details/gt2lybgffci.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pttnkyss.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xuetiantiany.cn/Article/details/gt2knxuntdf.html

JS:   new Date();  Date.now()
来源：http://dali.hammf.cn/Article/details/gt2vbdepjwu.html

TS:   new Date();  Date.now()
来源：http://dali.iojbl.cn/Article/details/gt2sjkqwwyn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2joyhorpn.html

Go:   time.Now()
来源：http://dali.svipenyu.cn/Article/details/gt2cgryiggr.html

Ruby: Time.now
来源：http://dali.yj202588.top/Article/details/gt2znztxtkw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sxryk.cn/Article/details/gt2gietrjlw.html

[J02] 格式化输出
来源：http://dali.snrcjt.cn/Article/details/gt2ceaxkwjy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigfzy.top/Article/details/gt2mtwseufx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gt2bngnpwmg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxlmvto.html

TS:   d.toISOString()
来源：http://dali.dashuyun.cn/Article/details/gt2wefxpstm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hnqzz.top/Article/details/gt2uupgtkom.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenjidiqi.icu/Article/details/gt2xrreesxx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhoulong.xyz/Article/details/gt2dihcgmti.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hongshengwenyu.top/Article/details/gt2lmuqzwos.html

[J03] 字符串解析为日期
来源：http://dali.nanxinkj.top/Article/details/gt2wzbrueft.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jyoumei.cn/Article/details/gt2shihvdfv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hammf.cn/Article/details/gt2fwjkapqw.html

JS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gt2rbvbviig.html

TS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uzroscdz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gt2uzbjqeoz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gt2yhjohbbb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2atfdheuj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xylfe.cn/Article/details/gt2fvaypaxw.html

[J04] 时间戳与日期互转
来源：http://dali.jianghu66.top/Article/details/gt2uspzjflr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cqqwz.cn/Article/details/gt2ocewuiws.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gaohongyu789.top/Article/details/gt2apsrecye.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jlsjyb.cn/Article/details/gt2dsesubuq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.kuanghao11.cn/Article/details/gt2asdetbcr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hywenlv.cn/Article/details/gt2mmzgezhw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ybcxt.top/Article/details/gt2nmeitxrw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ydzc1.top/Article/details/gt2bawwcmmm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tian-w.cn/Article/details/gt2tbykcigc.html

[J05] 时间加减（加 7 天）
来源：http://dali.xziqi.cn/Article/details/gt2bngvubmo.html

Py:   now + timedelta(days=7)
来源：http://dali.quarkkingdee.top/Article/details/gt2kdayxgll.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cashguo.top/Article/details/gt2ntgazdvi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258888.top/Article/details/gt2cvtnhsau.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.snrcjt.cn/Article/details/gt2iaikkqyy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yonumen.top/Article/details/gt2rxxaosbi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vpnwltpe.html

Ruby: Time.now + 7 * 86400
来源：http://dali.daria6918.cn/Article/details/gt2ainutzyb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gt2nifuxhqs.html

[J06] 计算两时间之差
来源：http://dali.guowangkeji.top/Article/details/gt2iurkffau.html

Py:   (end - start).total_seconds()
来源：http://dali.dianchejie.cn/Article/details/gt2ndghseiv.html

PHP:  $end->diff($start)->days;
来源：http://dali.cashguo.top/Article/details/gt2nkzzjuvj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.wangdashe.top/Article/details/gt2vvoudhrp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hywenlv.cn/Article/details/gt2qeqwofsl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yueranfly.top/Article/details/gt2jtxyanzv.html

Go:   end.Sub(start).Hours()
来源：http://dali.tanke756.top/Article/details/gt2gfrpusgd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.mhx1999.top/Article/details/gt2ykdbttba.html

C#:   (end - start).TotalSeconds
来源：http://dali.pengpengdd.cyou/Article/details/gt2upzkiwgp.html

[J07] 比较两个日期
来源：http://dali.9152youxi.cn/Article/details/gt2jurmzaqj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gt2coomvkzt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sysykeji.top/Article/details/gt2resubtea.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gt2xzhiokks.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xylfe.cn/Article/details/gt2ouqgixzk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.havefunace.top/Article/details/gt2ewiygsgh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fzhhl.top/Article/details/gt2uxjtpziz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gt2axkipyxn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gt2pbhwabsz.html

[J08] 提取年月日与星期
来源：http://dali.nanxinkj.top/Article/details/gt2inshlmij.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhongyouzk.top/Article/details/gt2jhnnkscf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ydzc1.top/Article/details/gt2acrsxjah.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.havefunace.top/Article/details/gt2yuqsvrum.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tianlin.xyz/Article/details/gt2cqujcjbh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhiwuduotai.top/Article/details/gt2bsiclyri.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guowangkeji.top/Article/details/gt2rwrruslk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fengsongda.top/Article/details/gt2macnecqg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhoulong.xyz/Article/details/gt2pfzxtclb.html

[J09] 时区处理
来源：http://dali.cashguo.top/Article/details/gt2nrbfgaro.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.smart0.xyz/Article/details/gt2hiybtgcb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jqgfzy.top/Article/details/gt2mnkoeeuv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gt2ntheipuy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258.top/Article/details/gt2dxewrdon.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.vqdsnc.cn/Article/details/gt2hjbqnldv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nwbrower.top/Article/details/gt2deydzcwf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj202588.top/Article/details/gt2tizybotr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.dianchejie.cn/Article/details/gt2imqzjotb.html

[J10] 取今天 / 本月第一天
来源：http://dali.mhx1999.top/Article/details/gt2lvtzfqoz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yvedp.cn/Article/details/gt2souoyaps.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhixingplan.top/Article/details/gt2nwmiucdk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhengqikj.top/Article/details/gt2xlactldp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sxryk.cn/Article/details/gt2mcfwrhxc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shzxlz.cn/Article/details/gt2ikoxhjpd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.birdmap.top/Article/details/gt2fqmrsnzd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhongyouzk.top/Article/details/gt2xuammzxl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.9152youxi.cn/Article/details/gt2balqswby.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2dhajdgyc.html

K. JSON 与序列化
来源：http://dali.xylfe.cn/Article/details/gt2juodjevv.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2duskvsml.html

[K01] 对象转 JSON 字符串
来源：http://dali.cashguo.top/Article/details/gt2vgeqkddj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gt2mjdtsybn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.meibo888.top/Article/details/gt2bhtdphvy.html

JS:   JSON.stringify(obj)
来源：http://dali.havefunace.top/Article/details/gt2anagubyx.html

TS:   JSON.stringify(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2shlcmksj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hfpthk.cn/Article/details/gt2sjmywoet.html

Go:   json.Marshal(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2vnjunvag.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.redwolf501.top/Article/details/gt2bqosezfk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.smart0.xyz/Article/details/gt2mrmihxpk.html

[K02] JSON 字符串转对象
来源：http://dali.yj20258888.top/Article/details/gt2zlvkxmje.html

Py:   json.loads(s)
来源：http://dali.ybcxt.top/Article/details/gt2gcvkbbqn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.haohaochexian.top/Article/details/gt2gtmxiqfh.html

JS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2udsvekxz.html

TS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gt2pdcfarva.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jiagoushi.top/Article/details/gt2hkdfbsko.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yvedp.cn/Article/details/gt2evcmqxoo.html

Ruby: JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zrbmablf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.daxiang520.top/Article/details/gt2ndbpuwki.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sxryk.cn/Article/details/gt2kpcwvmtz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hywenlv.cn/Article/details/gt2szpkalkt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hywenlv.cn/Article/details/gt2pznscafi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.bjfxy.top/Article/details/gt2fsxahmhx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gt2ksndldei.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2vnaemcoz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.haohaochexian.top/Article/details/gt2zkzrqgfo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2nyspkeqi.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuanzhike.top/Article/details/gt2eahhyics.html

[K04] 读取 JSON 文件
来源：http://dali.kuanghao11.cn/Article/details/gt2pjoihgub.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cdnleiting.top/Article/details/gt2nmkojfij.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.smart0.xyz/Article/details/gt2hpbavifp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gt2ddlvxkyy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.kuanghao11.cn/Article/details/gt2pnwancze.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dianchejie.cn/Article/details/gt2qmojbofs.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lcngdgwz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jlsjyb.cn/Article/details/gt2cylfxckl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhongyouzk.top/Article/details/gt2epqldych.html

[K05] 深拷贝对象
来源：http://dali.hywenlv.cn/Article/details/gt2ptjvadim.html

Py:   copy.deepcopy(obj)
来源：http://dali.redwolf501.top/Article/details/gt2oirljjvh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhongyouzk.top/Article/details/gt2vcshfbyb.html

JS:   structuredClone(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2desgkxai.html

TS:   structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2bnvgbcnd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xuanzx.com/Article/details/gt2axhjvviz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenjidiqi.icu/Article/details/gt2lygeeflq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.svipenyu.cn/Article/details/gt2rkegivwr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shangyingyoupin.top/Article/details/gt2boakprwx.html

[K06] 解析 URL 查询串
来源：http://dali.vqdsnc.cn/Article/details/gt2qidkpmcv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gaohongyu789.top/Article/details/gt2awdclvlk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sxryk.cn/Article/details/gt2mlzjucny.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenjidiqi.icu/Article/details/gt2hfbcpaco.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daria6918.cn/Article/details/gt2uslsehig.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258.top/Article/details/gt2bxtxklyu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gt2ydjyscjh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gt2zyskdyql.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gt2ewunkabo.html

[K07] 进制转换
来源：http://dali.xinyue.icu/Article/details/gt2aochcpid.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hhtuniqw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.wangshuangyany.cn/Article/details/gt2qienhxlc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gt2qxoswnsv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gt2iasinrwz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2iuazcdqx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cevcdclf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zycfv.cn/Article/details/gt2zicpyvvw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2uvdxnfut.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ppjwa.cn/Article/details/gt2gvjcubgv.html

Py:   pickle.dumps(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2vmtknufs.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yongpay.top/Article/details/gt2tdvdcqcy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zdqjudy.top/Article/details/gt2xaghkpum.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nwbrower.top/Article/details/gt2omgnhedv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.aizwys.cn/Article/details/gt2stexfmsv.html

Go:   encoding/gob
来源：http://dali.ppjwa.cn/Article/details/gt2mgogrwgi.html

Ruby: Marshal.dump(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2opeqsgmb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gt2kdfkvxiw.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2ydpiltqi.html

L. 网络请求
来源：http://dali.zdqjudy.top/Article/details/gt2sjlopfzj.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2fibrcswp.html

[L01] 发送 GET 请求
来源：http://dali.smart0.xyz/Article/details/gt2urpphjji.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.birdmap.top/Article/details/gt2dtppozqn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yangfankeji.com/Article/details/gt2syaifpfw.html

JS:   await fetch(url)
来源：http://dali.meibo888.top/Article/details/gt2ziqoxhfk.html

TS:   await fetch(url)
来源：http://dali.ehwqpu.com/Article/details/gt2ruuxvjsa.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.redwolf501.top/Article/details/gt2wfoqmfjk.html

Go:   resp, err := http.Get(url)
来源：http://dali.birdmap.top/Article/details/gt2ylwfpzya.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.316326.xyz/Article/details/gt2wypkgimc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hywenlv.cn/Article/details/gt2bnifsvkz.html

[L02] 发送 POST JSON
来源：http://dali.nwbrower.top/Article/details/gt2felvslim.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hfpthk.cn/Article/details/gt2lvygldft.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.meibo888.top/Article/details/gt2zkwiomad.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhengqikj.top/Article/details/gt2niogdwsr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gt2yvsswxqi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.fengsongda.top/Article/details/gt2btvvzamf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.snrcjt.cn/Article/details/gt2tiujajqz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yonumen.top/Article/details/gt2kbumxdwa.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yongpay.top/Article/details/gt2atldhmvv.html

[L03] 设置自定义请求头
来源：http://dali.ppjwa.cn/Article/details/gt2lcmauliw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.birdmap.top/Article/details/gt2emuidqwd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.aizwys.cn/Article/details/gt2moszekxx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cheryme.top/Article/details/gt2xvhyizqy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gogol.net.cn/Article/details/gt2zpbulatl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cqqwz.cn/Article/details/gt2pbxzgoun.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sufxvd.cn/Article/details/gt2gkihbeav.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gaohongyu789.top/Article/details/gt2swposzej.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sxryk.cn/Article/details/gt2kezepvpq.html

[L04] 设置超时
来源：http://dali.jinqigfzy.top/Article/details/gt2hkymidjy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.redwolf501.top/Article/details/gt2mpyjbhog.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jyoumei.cn/Article/details/gt2syyeyutx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gt2zfijeqep.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ydzc1.top/Article/details/gt2fodbdyar.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daxiang520.top/Article/details/gt2xyyucajf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zdqjudy.top/Article/details/gt2jtxhkboo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yuxming.cn/Article/details/gt2avzwbdxe.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.0kj1m.cn/Article/details/gt2zpknihea.html

[L05] 上传文件（multipart）
来源：http://dali.hongshengwenyu.top/Article/details/gt2wihgssrr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cucudq.cn/Article/details/gt2zajskoku.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xuanzx.com/Article/details/gt2lyzgilno.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.smart0.xyz/Article/details/gt2twclzmlg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gt2hhxkzrux.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnxiangtu.top/Article/details/gt2ncounwcm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2findzkat.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nanxinkj.top/Article/details/gt2wafpqagu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2jwvwjtax.html

[L06] 解析响应为 JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gbeaczwm.html

Py:   resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2njmwkwsi.html

PHP:  json_decode($body, true);
来源：http://dali.bjfxy.top/Article/details/gt2khfmhopk.html

JS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gt2bmfzksmg.html

TS:   await resp.json()
来源：http://dali.tian-w.cn/Article/details/gt2dtzatlrc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.smart0.xyz/Article/details/gt2mhazirit.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xuetiantiany.cn/Article/details/gt2yxupvljh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.dashuyun.cn/Article/details/gt2gwwnwdwi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.dianchejie.cn/Article/details/gt2uskjjllb.html

[L07] 处理 HTTP 状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rvhxvtzq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.pengpengdd.cyou/Article/details/gt2usqegiuh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj20258.top/Article/details/gt2tlrvqcio.html

JS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gt2tsgdduiq.html

TS:   resp.ok;  resp.status
来源：http://dali.andypj.xyz/Article/details/gt2avgsjxyx.html

Java: resp.statusCode()
来源：http://dali.yangfankeji.com/Article/details/gt2xvvdkqjo.html

Go:   resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gt2etwphrnq.html

Ruby: resp.code.to_i
来源：http://dali.tianlin.xyz/Article/details/gt2wontgggn.html

C#:   (int)resp.StatusCode
来源：http://dali.zhixingplan.top/Article/details/gt2jbhpfakm.html

[L08] 并发请求多个地址
来源：http://dali.c1oappe.top/Article/details/gt2gpyvefjb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cashguo.top/Article/details/gt2bumlpvvr.html

PHP:  curl_multi_init() 系列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bxnktdxn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tianlin.xyz/Article/details/gt2oxjloobr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gt2sftnvmuz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhiwuduotai.top/Article/details/gt2ufpmartg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.svipenyu.cn/Article/details/gt2vmuilakr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gogol.net.cn/Article/details/gt2imfekodm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ppjwa.cn/Article/details/gt2lxthjdvx.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qdpfvjvi.html

M. 命令行 / 进程 / 环境
来源：http://dali.jianghu66.top/Article/details/gt2azldrbhb.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2huejzzes.html

[M01] 读取命令行参数
来源：http://dali.dashuyun.cn/Article/details/gt2agbeezln.html

Py:   sys.argv[1:]
来源：http://dali.yongpay.top/Article/details/gt2uxtnfzrs.html

PHP:  $argv;  $argc;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2folcmsqk.html


<!-- 参考信息 -->