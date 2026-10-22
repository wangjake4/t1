代发 wailian999

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.daxiang520.top/Article/details/gt2lhcpcjvq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.daxiang520.top/Article/details/gt2eyrlbwul.html

[I04] 正则替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mjwktstu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ppjwa.cn/Article/details/gt2lxsqhodn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.bjfxy.top/Article/details/gt2iaidktqx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhixingplan.top/Article/details/gt2dsvtybtv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xylfe.cn/Article/details/gt2ffxwjtex.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hywenlv.cn/Article/details/gt2befqccfw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nanxinkj.top/Article/details/gt2awsrebcc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cashguo.top/Article/details/gt2zpszkyic.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.mhx1999.top/Article/details/gt2vmfgmjtn.html

[I05] 按正则拆分
来源：http://dali.ydzc1.top/Article/details/gt2gvlvhrld.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sxryk.cn/Article/details/gt2wvwvfomh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2jydunghh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gt2ailfdzph.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gt2ziglzavf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xuetiantiany.cn/Article/details/gt2dunxwiwp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2cagrzfzu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gt2qxwebijt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yuxming.cn/Article/details/gt2lubiruid.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nanxinkj.top/Article/details/gt2zbqkrgqc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gt2qlvkrftc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.pengpengdd.cyou/Article/details/gt2onzqwqgf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gt2cvgqfyza.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gt2wmczznoc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gt2ykubyswi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hywenlv.cn/Article/details/gt2uaejqajw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cdnleiting.top/Article/details/gt2ukruttdg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gt2njfmxthg.html

[I07] 忽略大小写与多行模式
来源：http://dali.ehwqpu.com/Article/details/gt2mitprtuj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xueviosi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hnqzz.top/Article/details/gt2mnonsndi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.guowangkeji.top/Article/details/gt2znuneydz.html

TS:   /error/gim
来源：http://dali.guowangkeji.top/Article/details/gt2blebzjdv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cheryme.top/Article/details/gt2pfvqdccm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wufilzkv.html

Ruby: s.scan(/error/i)
来源：http://dali.guowangkeji.top/Article/details/gt2hysibqjx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jianghu66.top/Article/details/gt2uapeycyr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hammf.cn/Article/details/gt2whrnraiw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daxiang520.top/Article/details/gt2bdelehsa.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.guowangkeji.top/Article/details/gt2ujxqetzk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yueranfly.top/Article/details/gt2npveyoyc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gt2akximaut.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gt2mkfzkidq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gzhubu.top/Article/details/gt2ahxeausv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gogol.net.cn/Article/details/gt2sjnkjums.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhoulong.xyz/Article/details/gt2nirpyvrr.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2jbyczeib.html

J. 日期与时间
来源：http://dali.hywenlv.cn/Article/details/gt2bsbhzdeq.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2ysfmrqcv.html

[J01] 获取当前时间
来源：http://dali.tian-w.cn/Article/details/gt2oopsqfvn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hnxiangtu.top/Article/details/gt2fprrygir.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gt2meljbwhn.html

JS:   new Date();  Date.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aqvcgqgh.html

TS:   new Date();  Date.now()
来源：http://dali.chenlongwang.top/Article/details/gt2jbawyepb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xinyue.icu/Article/details/gt2deumhgsm.html

Go:   time.Now()
来源：http://dali.ehwqpu.com/Article/details/gt2gouitpji.html

Ruby: Time.now
来源：http://dali.dashuyun.cn/Article/details/gt2pjnwtmtb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yanxiufei.cn/Article/details/gt2brmrbaql.html

[J02] 格式化输出
来源：http://dali.tianlin.xyz/Article/details/gt2nklqbeii.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dianchejie.cn/Article/details/gt2otqnlqpl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gt2prwdrebb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hfpthk.cn/Article/details/gt2skkaeyrm.html

TS:   d.toISOString()
来源：http://dali.sweek.top/Article/details/gt2pffpndtt.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.andypj.xyz/Article/details/gt2lvdbxdup.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.aizwys.cn/Article/details/gt2brkhtcxt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hysaishi.cn/Article/details/gt2xlrtylpg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cqqwz.cn/Article/details/gt2vtcxhsqm.html

[J03] 字符串解析为日期
来源：http://dali.mhx1999.top/Article/details/gt2lxbstrhn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.316326.xyz/Article/details/gt2sotlgzsr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yongpay.top/Article/details/gt2hctktlcd.html

JS:   new Date("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gt2bjmijozx.html

TS:   new Date("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gt2zjkamnep.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gt2kasdyiuf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gt2dxhzvswr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gt2vbjsniwa.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenzaomai.com/Article/details/gt2qzipjddh.html

[J04] 时间戳与日期互转
来源：http://dali.yuanzhike.top/Article/details/gt2zsfiufse.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hfpthk.cn/Article/details/gt2vunrfisb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.dashuyun.cn/Article/details/gt2vjwpfedh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sxryk.cn/Article/details/gt2kelwdrxl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xeheipjj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cqqwz.cn/Article/details/gt2xsozkmfu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cashguo.top/Article/details/gt2avlhpill.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gt2okivpgzo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.vqdsnc.cn/Article/details/gt2inhzqusv.html

[J05] 时间加减（加 7 天）
来源：http://dali.mhx1999.top/Article/details/gt2xhkweugj.html

Py:   now + timedelta(days=7)
来源：http://dali.cashguo.top/Article/details/gt2fbqbmvsu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shzxlz.cn/Article/details/gt2fnyboqpn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jiagoushi.top/Article/details/gt2nsuclqlq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.andypj.xyz/Article/details/gt2drwdvssc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sufxvd.cn/Article/details/gt2qpisbhgj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gplqreer.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aubhgquv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ppjwa.cn/Article/details/gt2lxgankrj.html

[J06] 计算两时间之差
来源：http://dali.hnxiangtu.top/Article/details/gt2ekyhdamz.html

Py:   (end - start).total_seconds()
来源：http://dali.ppjwa.cn/Article/details/gt2nioyfprd.html

PHP:  $end->diff($start)->days;
来源：http://dali.fzhhl.top/Article/details/gt2tfvnhtjn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.fzhhl.top/Article/details/gt2fmfzmewf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zdqjudy.top/Article/details/gt2ysxdzykh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhiwuduotai.top/Article/details/gt2euuqpcny.html

Go:   end.Sub(start).Hours()
来源：http://dali.hysaishi.cn/Article/details/gt2hcqixgjt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.guannengcc.top/Article/details/gt2benomayo.html

C#:   (end - start).TotalSeconds
来源：http://dali.ehwqpu.com/Article/details/gt2oyudptqq.html

[J07] 比较两个日期
来源：http://dali.hysaishi.cn/Article/details/gt2fomplyai.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tianlin.xyz/Article/details/gt2djzvszlx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cashguo.top/Article/details/gt2ilnqqmlr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gt2japdpxcf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.iojbl.cn/Article/details/gt2jymtlzxm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ybcxt.top/Article/details/gt2ermtspod.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.andypj.xyz/Article/details/gt2ocqfmlgg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gt2dsjypakk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gt2iuwiigmc.html

[J08] 提取年月日与星期
来源：http://dali.ydzc1.top/Article/details/gt2xmgspnpw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.316326.xyz/Article/details/gt2dhobgyiz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.bjfxy.top/Article/details/gt2tsfhyvgp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhixingplan.top/Article/details/gt2mfpeyodo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.snrcjt.cn/Article/details/gt2vxwjcdwa.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuxming.cn/Article/details/gt2mqekduuh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xuetiantiany.cn/Article/details/gt2bflozmzk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinqigfzy.top/Article/details/gt2dqjfdjbn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.havefunace.top/Article/details/gt2vuhspzpm.html

[J09] 时区处理
来源：http://dali.bjfxy.top/Article/details/gt2qdmhkrqc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fwflcywf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.fengsongda.top/Article/details/gt2edfhamtx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2grnsqwqa.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhongyouzk.top/Article/details/gt2umracewh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fengsongda.top/Article/details/gt2sfbpkpdi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tianlin.xyz/Article/details/gt2ztsndnht.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.meibo888.top/Article/details/gt2yooesteb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shangyingyoupin.top/Article/details/gt2erwtnuwd.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhoulong.xyz/Article/details/gt2gkryhbia.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yuxming.cn/Article/details/gt2rovrcflg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.andypj.xyz/Article/details/gt2ktbkkshl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.svipenyu.cn/Article/details/gt2ytqvrhqa.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnqzz.top/Article/details/gt2ctmufufg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.fengsongda.top/Article/details/gt2hunnavtx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.snrcjt.cn/Article/details/gt2hoqpzbjd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jlsjyb.cn/Article/details/gt2hqxdsprs.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.0kj1m.cn/Article/details/gt2eodbxaib.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2jnkjngyl.html

K. JSON 与序列化
来源：http://dali.gogol.net.cn/Article/details/gt2hduncoqg.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2wbopagat.html

[K01] 对象转 JSON 字符串
来源：http://dali.hysaishi.cn/Article/details/gt2azftaeln.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hywenlv.cn/Article/details/gt2wzsryhyr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hfpthk.cn/Article/details/gt2umgxcgbj.html

JS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2cvdbkosd.html

TS:   JSON.stringify(obj)
来源：http://dali.tian-w.cn/Article/details/gt2pptmwgwt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zycfv.cn/Article/details/gt2whmrlydu.html

Go:   json.Marshal(obj)
来源：http://dali.daria6918.cn/Article/details/gt2xfkwjubl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gotoacloud.top/Article/details/gt2nxghbepv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jfsidqsb.html

[K02] JSON 字符串转对象
来源：http://dali.fengsongda.top/Article/details/gt2yujopvya.html

Py:   json.loads(s)
来源：http://dali.pycfn.com/Article/details/gt2bezxpzfv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2rvvrwzly.html

JS:   JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gt2bgszcvnv.html

TS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2soevgpbm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hammf.cn/Article/details/gt2gcphrbyz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gt2mqlrhzpl.html

Ruby: JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gt2rvvaafqk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.mhx1999.top/Article/details/gt2hjtqehez.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jlsjyb.cn/Article/details/gt2javfcfoa.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gt2xveaxjie.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2whzgmdyf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2zysgfjbn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2coilejpr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2opyyusix.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tanke756.top/Article/details/gt2uiqtfzal.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2pwxgfpow.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ehwqpu.com/Article/details/gt2owxjqaep.html

[K04] 读取 JSON 文件
来源：http://dali.cashguo.top/Article/details/gt2vswombca.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.iojbl.cn/Article/details/gt2dldthtku.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhoulong.xyz/Article/details/gt2gmdtrqgm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sxryk.cn/Article/details/gt2bmqbleum.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gaohongyu789.top/Article/details/gt2ftyrsulc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.mhx1999.top/Article/details/gt2saooqvih.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.dashuyun.cn/Article/details/gt2jdalxpjf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kwsajkus.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xinyue.icu/Article/details/gt2rvdgeywc.html

[K05] 深拷贝对象
来源：http://dali.aizwys.cn/Article/details/gt2yjtpqkgk.html

Py:   copy.deepcopy(obj)
来源：http://dali.xinyue.icu/Article/details/gt2knhsxfup.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj202588.top/Article/details/gt2kyudaogk.html

JS:   structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gt2oruiwbvn.html

TS:   structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gt2pwjoroxd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cqqwz.cn/Article/details/gt2kuczmtvx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.316326.xyz/Article/details/gt2kxprmcnc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jqgfzy.top/Article/details/gt2ryuccmjd.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yuxming.cn/Article/details/gt2phpkvyqc.html

[K06] 解析 URL 查询串
来源：http://dali.snrcjt.cn/Article/details/gt2vwcgbhjp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hysaishi.cn/Article/details/gt2ecjqlmot.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hnqzz.top/Article/details/gt2ekehpnfi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gt2tggudmge.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gt2cpefpjnn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgfzy.top/Article/details/gt2dumwywjv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gt2ssuscelx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rbzwdbtb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gt2pkpvhfni.html

[K07] 进制转换
来源：http://dali.wangdashe.top/Article/details/gt2ubtitfeu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gt2oqdjcbnv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.feifeiyinyue.top/Article/details/gt2ykvbakhk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gt2wdsmaesz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gt2tpsywblu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tanke756.top/Article/details/gt2bnqgncqs.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yanxiufei.cn/Article/details/gt2jpdbcqbe.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.haohaochexian.top/Article/details/gt2gtkztkhx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gt2bdguswxm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.c1oappe.top/Article/details/gt2wpksztta.html

Py:   pickle.dumps(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2ctlafnvg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2gtopmhui.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jianghu66.top/Article/details/gt2dvrpktyg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gt2emhxugku.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhixingplan.top/Article/details/gt2fzecbkbg.html

Go:   encoding/gob
来源：http://dali.tianlin.xyz/Article/details/gt2mitgzemj.html

Ruby: Marshal.dump(obj)
来源：http://dali.yongpay.top/Article/details/gt2ouvvrhxg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gt2ajrqjark.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2nvdsymdx.html

L. 网络请求
来源：http://dali.cheryme.top/Article/details/gt2jyvikrar.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2edqqbdac.html

[L01] 发送 GET 请求
来源：http://dali.ppjwa.cn/Article/details/gt2tlzqvgby.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zdqjudy.top/Article/details/gt2ulibrufd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ydzc1.top/Article/details/gt2mckanrjo.html

JS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gt2qncewsxl.html

TS:   await fetch(url)
来源：http://dali.jiagoushi.top/Article/details/gt2ciivvglv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqqzsnr.html

Go:   resp, err := http.Get(url)
来源：http://dali.yanxiufei.cn/Article/details/gt2vcwebxnq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhongyouzk.top/Article/details/gt2lpwpodwb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yuxming.cn/Article/details/gt2aaftlqsb.html

[L02] 发送 POST JSON
来源：http://dali.andypj.xyz/Article/details/gt2fjixklyn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhengqikj.top/Article/details/gt2ymqnnwgs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mmwhabbn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigfzy.top/Article/details/gt2ahonqark.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gt2gilsrgeq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.fzhhl.top/Article/details/gt2dzvhnyhz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tanke756.top/Article/details/gt2nzcjobag.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhixingplan.top/Article/details/gt2uuaaztvn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.dashuyun.cn/Article/details/gt2sudsuhog.html

[L03] 设置自定义请求头
来源：http://dali.ppjwa.cn/Article/details/gt2bqgistcs.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhoulong.xyz/Article/details/gt2wzwzqpez.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj20258888.top/Article/details/gt2yxmudgko.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenzaomai.com/Article/details/gt2qpsidynn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gt2dmwrprga.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jyoumei.cn/Article/details/gt2erltmram.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gt2vknwqvlm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.guannengcc.top/Article/details/gt2wcchdisd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cashguo.top/Article/details/gt2gjgjujzv.html

[L04] 设置超时
来源：http://dali.wangshuangyany.cn/Article/details/gt2ynsdzxwj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cucudq.cn/Article/details/gt2ljtimtsv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.meibo888.top/Article/details/gt2qrjjppbe.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cashguo.top/Article/details/gt2puiabdqh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xziqi.cn/Article/details/gt2xifmsrlv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hywenlv.cn/Article/details/gt2noyrexiy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenjidiqi.icu/Article/details/gt2xakyuriw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.birdmap.top/Article/details/gt2uopvzhek.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xziqi.cn/Article/details/gt2pcdzcaxx.html

[L05] 上传文件（multipart）
来源：http://dali.yongpay.top/Article/details/gt2zssacgbf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hongshengwenyu.top/Article/details/gt2rwmexfal.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ybcxt.top/Article/details/gt2dutrwlvs.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yjxxqzmt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.mhx1999.top/Article/details/gt2ldtkkuec.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.9152youxi.cn/Article/details/gt2birhytld.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yonumen.top/Article/details/gt2mzyhediu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2pkktchuh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2jxtxlwir.html

[L06] 解析响应为 JSON
来源：http://dali.fengsongda.top/Article/details/gt2pdflybvy.html

Py:   resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gt2rtkugpxm.html

PHP:  json_decode($body, true);
来源：http://dali.sxryk.cn/Article/details/gt2dfnuwksx.html

JS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gt2vzrrqegw.html

TS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gt2cppeikxn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guannengcc.top/Article/details/gt2rhvwhvvw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xziqi.cn/Article/details/gt2addqvpxv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xuanzx.com/Article/details/gt2pfhxjtlh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tianlin.xyz/Article/details/gt2kcblyokg.html

[L07] 处理 HTTP 状态码
来源：http://dali.haohaochexian.top/Article/details/gt2vikvmxgt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xinyue.icu/Article/details/gt2daebslcr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hongshengwenyu.top/Article/details/gt2nssvspex.html

JS:   resp.ok;  resp.status
来源：http://dali.vqdsnc.cn/Article/details/gt2dqzpbjcm.html

TS:   resp.ok;  resp.status
来源：http://dali.sweek.top/Article/details/gt2ihjxrrdk.html

Java: resp.statusCode()
来源：http://dali.birdmap.top/Article/details/gt2yprvbgvv.html

Go:   resp.StatusCode
来源：http://dali.nanxuanxn.top/Article/details/gt2hhwkizah.html

Ruby: resp.code.to_i
来源：http://dali.cqqwz.cn/Article/details/gt2rvfdnpjp.html

C#:   (int)resp.StatusCode
来源：http://dali.yj20258.top/Article/details/gt2uhxhpily.html

[L08] 并发请求多个地址
来源：http://dali.jinqigufen.top/Article/details/gt2bbtdldbr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xylfe.cn/Article/details/gt2yqequrln.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvckrrr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gt2ddykguop.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gt2vdpghvqr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cqqwz.cn/Article/details/gt2lzrglpyn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xinyue.icu/Article/details/gt2blouugng.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenlongwang.top/Article/details/gt2zffzqrrx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hfpthk.cn/Article/details/gt2pxagszbz.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wmuuohpf.html

M. 命令行 / 进程 / 环境
来源：http://dali.birdmap.top/Article/details/gt2yyfbzirt.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2vopuscop.html

[M01] 读取命令行参数
来源：http://dali.yueranfly.top/Article/details/gt2mwlycinm.html

Py:   sys.argv[1:]
来源：http://dali.9152youxi.cn/Article/details/gt2jjouwuoa.html

PHP:  $argv;  $argc;
来源：http://dali.zhengqikj.top/Article/details/gt2olvxtqzd.html

JS:   process.argv.slice(2)
来源：http://dali.guowangkeji.top/Article/details/gt2awtruqgp.html

TS:   process.argv.slice(2)
来源：http://dali.meibo888.top/Article/details/gt2xadwqdtc.html

Java: args 数组（main 方法参数）
来源：http://dali.xuanzx.com/Article/details/gt2zobkwzmd.html

Go:   os.Args[1:]
来源：http://dali.wangdashe.top/Article/details/gt2spononyp.html


<!-- 参考信息 -->