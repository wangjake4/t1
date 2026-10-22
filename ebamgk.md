代发 wailian999

TS:   s.match(/\d+/g)
来源：http://dali.aizwys.cn/Article/details/gt2lllcgzia.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ivvv.top/Article/details/gt2rdbnidlv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.smart0.xyz/Article/details/gt2yxusofqn.html

Ruby: s.scan(/\d+/)
来源：http://dali.yangfankeji.com/Article/details/gt2wfpudsse.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2coebhuni.html

[I03] 提取捕获分组
来源：http://dali.cqqwz.cn/Article/details/gt2nfbcbgdg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2eqebkftt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gogol.net.cn/Article/details/gt2piexdawu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.birdmap.top/Article/details/gt2hkxmxjhe.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.iojbl.cn/Article/details/gt2hjskkhwm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aibaodan.cn/Article/details/gt2khjlvrgq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cashguo.top/Article/details/gt2dxsiiwlt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xuanzx.com/Article/details/gt2iagnvhzw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fengsongda.top/Article/details/gt2yvdujqfj.html

[I04] 正则替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2okdynwfe.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cucudq.cn/Article/details/gt2egjyffyg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guowangkeji.top/Article/details/gt2nfukuobi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gt2rgjujusj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gt2hzgsozxl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gzhubu.top/Article/details/gt2pswccaws.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.birdmap.top/Article/details/gt2ywgazhkg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ehwqpu.com/Article/details/gt2gafpputb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ydzc1.top/Article/details/gt2vvvajdoa.html

[I05] 按正则拆分
来源：http://dali.jqgufenzy.top/Article/details/gt2bhoqltop.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2caiipgwn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhixingplan.top/Article/details/gt2qeykuvxi.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kwswxgib.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gt2dpznkmfe.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ivvv.top/Article/details/gt2fmimadac.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gt2qfkbpfkk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gt2gwyoqxex.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hnxiangtu.top/Article/details/gt2levlthjr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nwbrower.top/Article/details/gt2owpnmhcz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yongpay.top/Article/details/gt2klshujon.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenjidiqi.icu/Article/details/gt2iesypirf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gt2wjmvjytr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.havefunace.top/Article/details/gt2cqczoryg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gt2livdqzpg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.wangshuangyany.cn/Article/details/gt2rlqxrnfc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ehwqpu.com/Article/details/gt2kwvycdhw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gt2lzzvbzhk.html

[I07] 忽略大小写与多行模式
来源：http://dali.shangyingyoupin.top/Article/details/gt2ccwazcuq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lhugmkdh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj202588.top/Article/details/gt2uafbmqxd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.snrcjt.cn/Article/details/gt2wsbbtcgg.html

TS:   /error/gim
来源：http://dali.jyoumei.cn/Article/details/gt2gpxjkwar.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.c1oappe.top/Article/details/gt2ajeifrlk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.fzhhl.top/Article/details/gt2qdslztsx.html

Ruby: s.scan(/error/i)
来源：http://dali.daxiang520.top/Article/details/gt2bmwxgmyk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xziqi.cn/Article/details/gt2xdepythe.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yanxiufei.cn/Article/details/gt2xslnbbvj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.c1oappe.top/Article/details/gt2yglbcxim.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hywenlv.cn/Article/details/gt2lsfuozks.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gt2gndgljyr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gaohongyu789.top/Article/details/gt2nlxazpgr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gt2qgdvuteo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tanke756.top/Article/details/gt2mxrtjjrz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jozmxokv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yonumen.top/Article/details/gt2fwnqbuky.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2axmwczow.html

J. 日期与时间
来源：http://dali.chenzaomai.com/Article/details/gt2dfvlgfxl.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2cvrjbnmn.html

[J01] 获取当前时间
来源：http://dali.tanke756.top/Article/details/gt2zrmhclrk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhengqikj.top/Article/details/gt2lqrxudbd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.andypj.xyz/Article/details/gt2ptkhbudx.html

JS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gt2uioaguls.html

TS:   new Date();  Date.now()
来源：http://dali.jqgfzy.top/Article/details/gt2cufxnaeq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dashuyun.cn/Article/details/gt2uukjblnd.html

Go:   time.Now()
来源：http://dali.xuetiantiany.cn/Article/details/gt2kvhcmgdc.html

Ruby: Time.now
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iqjvqyny.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.haohaochexian.top/Article/details/gt2gbstlpfb.html

[J02] 格式化输出
来源：http://dali.cucudq.cn/Article/details/gt2twtqxoom.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gt2dvjgfyel.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jqgfzy.top/Article/details/gt2pxfxrhsd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.haohaochexian.top/Article/details/gt2rqshjhpb.html

TS:   d.toISOString()
来源：http://dali.zhengqikj.top/Article/details/gt2xlypagwx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nwbrower.top/Article/details/gt2wbufmizh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.andypj.xyz/Article/details/gt2fihcveje.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cucudq.cn/Article/details/gt2rjbftufn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2myghalqo.html

[J03] 字符串解析为日期
来源：http://dali.zdqjudy.top/Article/details/gt2tdlcikae.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xuanzx.com/Article/details/gt2fdmvbbcx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gogol.net.cn/Article/details/gt2yptwtyre.html

JS:   new Date("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2trzmiacp.html

TS:   new Date("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gt2hkroxlct.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2mgoqsnmq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gt2ugbsclfn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gt2unqjaiwq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.wangshuangyany.cn/Article/details/gt2khxvtyby.html

[J04] 时间戳与日期互转
来源：http://dali.vqdsnc.cn/Article/details/gt2buzzcnqt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.bjfxy.top/Article/details/gt2mvyrijzz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhixingplan.top/Article/details/gt2gxpeqzwg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ppjwa.cn/Article/details/gt2aomwbywp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xinyue.icu/Article/details/gt2kmbsffwb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tanke756.top/Article/details/gt2gqpxvgkf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2npuwckpw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kunzljzd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhengqikj.top/Article/details/gt2bzaaashj.html

[J05] 时间加减（加 7 天）
来源：http://dali.tanke756.top/Article/details/gt2xrgmgcpn.html

Py:   now + timedelta(days=7)
来源：http://dali.shzxlz.cn/Article/details/gt2mzofmisc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gt2txfblvpl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dxjarizk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yongpay.top/Article/details/gt2ivoormst.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2getwcuqm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cheryme.top/Article/details/gt2itqfffhx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.pycfn.com/Article/details/gt2mqheezep.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhengqikj.top/Article/details/gt2oprezjca.html

[J06] 计算两时间之差
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wuydmdow.html

Py:   (end - start).total_seconds()
来源：http://dali.gaohongyu789.top/Article/details/gt2irptskwm.html

PHP:  $end->diff($start)->days;
来源：http://dali.pycfn.com/Article/details/gt2hhjmztbx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jyoumei.cn/Article/details/gt2fhurrwiq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pengpengdd.cyou/Article/details/gt2yndighkp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj202588.top/Article/details/gt2qzhjyxuv.html

Go:   end.Sub(start).Hours()
来源：http://dali.nwbrower.top/Article/details/gt2smstjasm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.iojbl.cn/Article/details/gt2fubruyql.html

C#:   (end - start).TotalSeconds
来源：http://dali.dianchejie.cn/Article/details/gt2kzhuihog.html

[J07] 比较两个日期
来源：http://dali.zhixingplan.top/Article/details/gt2bouvedxb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gt2lthksjsq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.birdmap.top/Article/details/gt2rmbtaiqs.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hongshengwenyu.top/Article/details/gt2zgmmsfkt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.316326.xyz/Article/details/gt2dnhdfsof.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.quarkkingdee.top/Article/details/gt2ynzkpcfb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mpyrbfcb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gt2qphponvd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gt2qwfaytxz.html

[J08] 提取年月日与星期
来源：http://dali.hongshengwenyu.top/Article/details/gt2stceywko.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.guannengcc.top/Article/details/gt2ipvizilr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhoulong.xyz/Article/details/gt2evzxynty.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.svipenyu.cn/Article/details/gt2vfshehlh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gotoacloud.top/Article/details/gt2qutwiplw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.wangshuangyany.cn/Article/details/gt2cnsxpitk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yanxiufei.cn/Article/details/gt2btpgrguv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinghuilouyu.cn/Article/details/gt2szqaniah.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sufxvd.cn/Article/details/gt2qxmwafjr.html

[J09] 时区处理
来源：http://dali.0kj1m.cn/Article/details/gt2beimktzj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yueranfly.top/Article/details/gt2yejkawam.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yonumen.top/Article/details/gt2xhkkblyy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj202588.top/Article/details/gt2xlbttlnu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gt2fqlvjelk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jqgfzy.top/Article/details/gt2tpklwjss.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhiwuduotai.top/Article/details/gt2elrevydc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.feifeiyinyue.top/Article/details/gt2eyxmnzqf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gaohongyu789.top/Article/details/gt2zyodsilu.html

[J10] 取今天 / 本月第一天
来源：http://dali.aibaodan.cn/Article/details/gt2vjkwcvtn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.andypj.xyz/Article/details/gt2avhymxpd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shangyingyoupin.top/Article/details/gt2dtdctelr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rwxhzlzz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ybcxt.top/Article/details/gt2zbuxrmuu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ajhtpmju.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pengpengdd.cyou/Article/details/gt2wjlrcixb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.guannengcc.top/Article/details/gt2wwbchcyu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.dashuyun.cn/Article/details/gt2kocyvrms.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2xqfbxdgr.html

K. JSON 与序列化
来源：http://dali.yj20258888.top/Article/details/gt2rhszasvk.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2gmwwiyuu.html

[K01] 对象转 JSON 字符串
来源：http://dali.c1oappe.top/Article/details/gt2xtcajpjp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigufen.top/Article/details/gt2xboxgcbl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shuidangran.top/Article/details/gt2stuxnzbu.html

JS:   JSON.stringify(obj)
来源：http://dali.meibo888.top/Article/details/gt2pckthsac.html

TS:   JSON.stringify(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2kjpdhycj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.aibaodan.cn/Article/details/gt2qtturgwc.html

Go:   json.Marshal(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2xqcjuolw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cdnleiting.top/Article/details/gt2zlvapyxe.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xinyue.icu/Article/details/gt2fgztooza.html

[K02] JSON 字符串转对象
来源：http://dali.aizwys.cn/Article/details/gt2srhmtbvz.html

Py:   json.loads(s)
来源：http://dali.ivvv.top/Article/details/gt2cglasigu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sxryk.cn/Article/details/gt2wizgpotp.html

JS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2dgsmlzxe.html

TS:   JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2fnswpzyt.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cdnleiting.top/Article/details/gt2zdmniotp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cheryme.top/Article/details/gt2fuzayxdv.html

Ruby: JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gt2wxlxoflh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tanke756.top/Article/details/gt2golggabg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.pengpengdd.cyou/Article/details/gt2isyugeyr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gt2evbnbzbt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fafsoywi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenzaomai.com/Article/details/gt2ewzkifns.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2tzbtloqr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2kpuqprad.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj20258888.top/Article/details/gt2qrroxpic.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2bfnwlhgb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhixingplan.top/Article/details/gt2lqqchsdp.html

[K04] 读取 JSON 文件
来源：http://dali.hnxiangtu.top/Article/details/gt2vwxggksg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.dianchejie.cn/Article/details/gt2syngkude.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yvedp.cn/Article/details/gt2wrsjudjp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gt2gcuosaux.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ylagrosg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.9152youxi.cn/Article/details/gt2zxvpvdtt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gt2uvogoxsu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daria6918.cn/Article/details/gt2egupkvxe.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hfpthk.cn/Article/details/gt2ngpybyob.html

[K05] 深拷贝对象
来源：http://dali.dianchejie.cn/Article/details/gt2qhqbzlup.html

Py:   copy.deepcopy(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2anydmima.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yvedp.cn/Article/details/gt2vuhfgvor.html

JS:   structuredClone(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hvmbnasg.html

TS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mrcxbksm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yanxiufei.cn/Article/details/gt2wczhxjfx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2abtlmrfl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zycfv.cn/Article/details/gt2aolprsem.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hedqnzap.html

[K06] 解析 URL 查询串
来源：http://dali.mhx1999.top/Article/details/gt2tpkjbgkl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gt2dxshtrql.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.316326.xyz/Article/details/gt2mkpnbtrj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.smart0.xyz/Article/details/gt2obkemsom.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gt2dfvglorp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.vqdsnc.cn/Article/details/gt2dhxykjir.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gt2glfwqnnq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gt2hqhitlyq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gt2zdjqbawe.html

[K07] 进制转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2khnxpzhf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gt2odclqaer.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigufen.top/Article/details/gt2jmjswowr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gt2qfnlilwb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gt2wcmqezbg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2yfgfkxed.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yongpay.top/Article/details/gt2pdbktufh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xinyue.icu/Article/details/gt2fgzgbkxh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gt2riknxgvf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sxryk.cn/Article/details/gt2enqzfqzs.html

Py:   pickle.dumps(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2mgsgexpg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ydzc1.top/Article/details/gt2zduaxkjf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj202588.top/Article/details/gt2jvyytvyr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yuxming.cn/Article/details/gt2ncapsgeg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ybcxt.top/Article/details/gt2nxqvcoht.html

Go:   encoding/gob
来源：http://dali.shuidangran.top/Article/details/gt2pjgajvko.html

Ruby: Marshal.dump(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2fruhajok.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cdnleiting.top/Article/details/gt2vucjtbyi.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2tebpbvur.html

L. 网络请求
来源：http://dali.hnxiangtu.top/Article/details/gt2prqaqorr.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2nqgcqpak.html

[L01] 发送 GET 请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ojbwnxlf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nwbrower.top/Article/details/gt2uotmqagr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zsvxfrak.html

JS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gt2ghpvruxz.html

TS:   await fetch(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mizsyubo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gaohongyu789.top/Article/details/gt2ighnzoio.html

Go:   resp, err := http.Get(url)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ejijxpdk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.snrcjt.cn/Article/details/gt2qdeotoep.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jqgufenzy.top/Article/details/gt2lkvnugin.html

[L02] 发送 POST JSON
来源：http://dali.yj202588.top/Article/details/gt2qummevzw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gt2xdvnmeqq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sufxvd.cn/Article/details/gt2yqoceisc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gt2lvkdovzb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xzasfhxo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sysykeji.top/Article/details/gt2wxmxoiwd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yonumen.top/Article/details/gt2ppeoqysu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenjidiqi.icu/Article/details/gt2rusbxuod.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cheryme.top/Article/details/gt2vrcgydwe.html

[L03] 设置自定义请求头
来源：http://dali.0kj1m.cn/Article/details/gt2zkrfsdlx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yongpay.top/Article/details/gt2wxtqulxq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cashguo.top/Article/details/gt2phegyvri.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gt2gbzyfico.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yueranfly.top/Article/details/gt2ylwkgdax.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenzaomai.com/Article/details/gt2dumsnrfc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jqgfzy.top/Article/details/gt2wjezbyem.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2grltmrnn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gt2shwakvgs.html

[L04] 设置超时
来源：http://dali.gaohongyu789.top/Article/details/gt2rtooggao.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenzaomai.com/Article/details/gt2acqzlakb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shuidangran.top/Article/details/gt2nugvpkaw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gt2rwndkaiu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgufenzy.top/Article/details/gt2bivkzkqb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ybcxt.top/Article/details/gt2kykfkodf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guowangkeji.top/Article/details/gt2mnwkgjul.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinqigufen.top/Article/details/gt2tgywudyz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ivvv.top/Article/details/gt2pbowviwq.html

[L05] 上传文件（multipart）
来源：http://dali.jinqigfzy.top/Article/details/gt2btmliaux.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.c1oappe.top/Article/details/gt2cfwmchfp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.iojbl.cn/Article/details/gt2ognhsnhm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.birdmap.top/Article/details/gt2mosthqyt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhengqikj.top/Article/details/gt2raueyztc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kxvnndzy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yvedp.cn/Article/details/gt2ibwdoaac.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sxryk.cn/Article/details/gt2kwzdubsy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2zskjvutq.html

[L06] 解析响应为 JSON
来源：http://dali.hnqzz.top/Article/details/gt2driawskx.html

Py:   resp.json()
来源：http://dali.mhx1999.top/Article/details/gt2xibxfvmx.html

PHP:  json_decode($body, true);
来源：http://dali.zhongyouzk.top/Article/details/gt2oilskrvz.html

JS:   await resp.json()
来源：http://dali.aizwys.cn/Article/details/gt2wcvjbyns.html

TS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zhaozljz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sweek.top/Article/details/gt2vuxyuump.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.wangdashe.top/Article/details/gt2wwpcgoha.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gzhubu.top/Article/details/gt2sdrhtwre.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.9152youxi.cn/Article/details/gt2irpowtje.html

[L07] 处理 HTTP 状态码
来源：http://dali.yuanzhike.top/Article/details/gt2ihvnebkj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yongpay.top/Article/details/gt2gewbcjmq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.meibo888.top/Article/details/gt2heyhydsa.html

JS:   resp.ok;  resp.status
来源：http://dali.9152youxi.cn/Article/details/gt2jqeqrvtd.html

TS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dyhrltxk.html

Java: resp.statusCode()
来源：http://dali.ehwqpu.com/Article/details/gt2aynvgjbq.html

Go:   resp.StatusCode
来源：http://dali.jiagoushi.top/Article/details/gt2pfjmdoli.html

Ruby: resp.code.to_i
来源：http://dali.guowangkeji.top/Article/details/gt2fdzwhsgr.html

C#:   (int)resp.StatusCode
来源：http://dali.shuidangran.top/Article/details/gt2pxiqogrt.html

[L08] 并发请求多个地址
来源：http://dali.cdnleiting.top/Article/details/gt2hknapqwf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xuetiantiany.cn/Article/details/gt2qucdkrvf.html

PHP:  curl_multi_init() 系列
来源：http://dali.yuanzhike.top/Article/details/gt2haocsblt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gt2djjfagex.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gt2bcpjfqcf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cqqwz.cn/Article/details/gt2ctvspjdt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cheryme.top/Article/details/gt2qtjxyjka.html


<!-- 参考信息 -->