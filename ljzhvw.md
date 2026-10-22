代发 wailian999

TS:   s.match(/\d+/g)
来源：http://dali.gzhubu.top/Article/details/gt2osnfrhlx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigufen.top/Article/details/gt2yijeqyev.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yuanzhike.top/Article/details/gt2bzjbfnlh.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangdashe.top/Article/details/gt2powgvzxd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2egugrmfz.html

[I03] 提取捕获分组
来源：http://dali.cucudq.cn/Article/details/gt2xjkkxclu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yonumen.top/Article/details/gt2teuobvzo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tanke756.top/Article/details/gt2fcmtfhhh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cucudq.cn/Article/details/gt2oggvjydj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kyyiohmt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258.top/Article/details/gt2dqvonklf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.redwolf501.top/Article/details/gt2stzbbqty.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yanxiufei.cn/Article/details/gt2djgvjgnd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangdashe.top/Article/details/gt2bjrgbrkg.html

[I04] 正则替换
来源：http://dali.sweek.top/Article/details/gt2xjcxqvpj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.mhx1999.top/Article/details/gt2tztntnfr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258.top/Article/details/gt2midnblkf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hfpthk.cn/Article/details/gt2kyzylxtl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.vqdsnc.cn/Article/details/gt2xiekwxey.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.vqdsnc.cn/Article/details/gt2bwavcekh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ppjwa.cn/Article/details/gt2dqzsfnnk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.vqdsnc.cn/Article/details/gt2vbpkskly.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.svipenyu.cn/Article/details/gt2mbfhmanw.html

[I05] 按正则拆分
来源：http://dali.yuxming.cn/Article/details/gt2yrwgsqev.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.quarkkingdee.top/Article/details/gt2fkqfqeem.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.andypj.xyz/Article/details/gt2soaaxsun.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gt2xrydigfo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gt2azzkioof.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yanxiufei.cn/Article/details/gt2upbzntny.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.mhx1999.top/Article/details/gt2qmfsznlc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gt2odtgnbdv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xuetiantiany.cn/Article/details/gt2dgvcmvtt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.redwolf501.top/Article/details/gt2phqrgmrx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gt2hmnsmwqa.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.bjfxy.top/Article/details/gt2tkhfynzg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhiwuduotai.top/Article/details/gt2smdqddch.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ewummtqf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gt2qxvwlvez.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.feifeiyinyue.top/Article/details/gt2zsuczzgj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tian-w.cn/Article/details/gt2hteoohzm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gt2mflzgcjm.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj20258.top/Article/details/gt2juslskdl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hnqzz.top/Article/details/gt2qwnbwmby.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shzxlz.cn/Article/details/gt2ywcrwjad.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yueranfly.top/Article/details/gt2hnjxyejo.html

TS:   /error/gim
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rrbqmggs.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sxryk.cn/Article/details/gt2biseijhg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cashguo.top/Article/details/gt2hosfpyrg.html

Ruby: s.scan(/error/i)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qytyierh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnxiangtu.top/Article/details/gt2cftfemrx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jianghu66.top/Article/details/gt2sgqzhjyr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xinyue.icu/Article/details/gt2rjmwpibi.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gotoacloud.top/Article/details/gt2fvwyrvyx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gt2ptpngdtt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.havefunace.top/Article/details/gt2rokzzpbh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zycfv.cn/Article/details/gt2uiimtpae.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.smart0.xyz/Article/details/gt2zflxsais.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.fengsongda.top/Article/details/gt2neypthxv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tian-w.cn/Article/details/gt2uymlambt.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2pccchdhw.html

J. 日期与时间
来源：http://dali.chenjidiqi.icu/Article/details/gt2nryzwoil.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2akpnmdty.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bveeozcn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hnqzz.top/Article/details/gt2qdotjwxr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ehwqpu.com/Article/details/gt2kejygsnn.html

JS:   new Date();  Date.now()
来源：http://dali.guowangkeji.top/Article/details/gt2eoimvbwt.html

TS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gt2zenaiszt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gogol.net.cn/Article/details/gt2ntgzyujb.html

Go:   time.Now()
来源：http://dali.dianchejie.cn/Article/details/gt2hzgnllhu.html

Ruby: Time.now
来源：http://dali.daxiang520.top/Article/details/gt2qwenclfm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sweek.top/Article/details/gt2wgpbmvao.html

[J02] 格式化输出
来源：http://dali.sxryk.cn/Article/details/gt2hnrtmmmv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhoulong.xyz/Article/details/gt2zfmyvajl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zxpotjek.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ivvv.top/Article/details/gt2yvapgdxq.html

TS:   d.toISOString()
来源：http://dali.svipenyu.cn/Article/details/gt2jjbdkaho.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.smart0.xyz/Article/details/gt2ukxjudee.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yongpay.top/Article/details/gt2certthij.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gt2tlkilnix.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.redwolf501.top/Article/details/gt2ntfgapel.html

[J03] 字符串解析为日期
来源：http://dali.ybcxt.top/Article/details/gt2ggagfikt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.guowangkeji.top/Article/details/gt2xjclpozx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cucudq.cn/Article/details/gt2ykbhqkwm.html

JS:   new Date("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gt2alzyzqzl.html

TS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ujdjvvci.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gt2rkdrofkb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gt2pfansexu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gt2ekttduab.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.9152youxi.cn/Article/details/gt2ibbknbyi.html

[J04] 时间戳与日期互转
来源：http://dali.dashuyun.cn/Article/details/gt2ebnzlhvo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenlongwang.top/Article/details/gt2jsxxurqn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.iojbl.cn/Article/details/gt2iypgczhn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yfkrbeou.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenzaomai.com/Article/details/gt2dmsrljuy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hfpthk.cn/Article/details/gt2crbhukbr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sweek.top/Article/details/gt2nobagvye.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shzxlz.cn/Article/details/gt2rxbpdixr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tanke756.top/Article/details/gt2syhogfbu.html

[J05] 时间加减（加 7 天）
来源：http://dali.gzhubu.top/Article/details/gt2lcuulpyq.html

Py:   now + timedelta(days=7)
来源：http://dali.0kj1m.cn/Article/details/gt2mtfwjncy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.mhx1999.top/Article/details/gt2hcswegml.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guannengcc.top/Article/details/gt2xlpgaakf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ppjwa.cn/Article/details/gt2krislzxq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.redwolf501.top/Article/details/gt2gutcilyb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.mhx1999.top/Article/details/gt2zywdtmih.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gzhubu.top/Article/details/gt2xhczlsmp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhongyouzk.top/Article/details/gt2dyfqcwzt.html

[J06] 计算两时间之差
来源：http://dali.cucudq.cn/Article/details/gt2gieivoym.html

Py:   (end - start).total_seconds()
来源：http://dali.meibo888.top/Article/details/gt2bkzkeiwi.html

PHP:  $end->diff($start)->days;
来源：http://dali.fzhhl.top/Article/details/gt2ggyvkhjq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.0kj1m.cn/Article/details/gt2cbouecal.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hywenlv.cn/Article/details/gt2pmygauhz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.guannengcc.top/Article/details/gt2eioieali.html

Go:   end.Sub(start).Hours()
来源：http://dali.gaohongyu789.top/Article/details/gt2vgdatshp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenlongwang.top/Article/details/gt2eoohojoe.html

C#:   (end - start).TotalSeconds
来源：http://dali.9152youxi.cn/Article/details/gt2zjgnzoze.html

[J07] 比较两个日期
来源：http://dali.wangdashe.top/Article/details/gt2cidhudrj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gt2ebuiijjf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhixingplan.top/Article/details/gt2tsavtlal.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gt2arwcfmbx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gt2hynjmtdw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gaohongyu789.top/Article/details/gt2fdhsyuju.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuanzhike.top/Article/details/gt2qzzcvkzq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gt2jsncqlek.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gt2tqdrmklz.html

[J08] 提取年月日与星期
来源：http://dali.yonumen.top/Article/details/gt2pwcyxbys.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ybcxt.top/Article/details/gt2fdqardoh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.kuanghao11.cn/Article/details/gt2pdtlzflf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jyoumei.cn/Article/details/gt2brcnifvp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jqgfzy.top/Article/details/gt2fxpilpwr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2czzxikys.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tianlin.xyz/Article/details/gt2njkiavkq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.daria6918.cn/Article/details/gt2ccpwxzbi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tianlin.xyz/Article/details/gt2jtrkseir.html

[J09] 时区处理
来源：http://dali.ehwqpu.com/Article/details/gt2myoxrjsn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.svipenyu.cn/Article/details/gt2hymvwirs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhiwuduotai.top/Article/details/gt2wpjflyju.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gt2bsynladn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ydzc1.top/Article/details/gt2xndsbwlt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hysaishi.cn/Article/details/gt2rrwxsgyd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.redwolf501.top/Article/details/gt2wzgbtxfg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.fengsongda.top/Article/details/gt2hlhsvmzr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.andypj.xyz/Article/details/gt2qefootph.html

[J10] 取今天 / 本月第一天
来源：http://dali.pengpengdd.cyou/Article/details/gt2wvtibjze.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hywenlv.cn/Article/details/gt2zoffrdwa.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.haohaochexian.top/Article/details/gt2xjrjddwb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cucudq.cn/Article/details/gt2whybligq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2supxshmu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yueranfly.top/Article/details/gt2gfigjbia.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hammf.cn/Article/details/gt2xyvyjtdj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhengqikj.top/Article/details/gt2defxxqdf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ircbplmj.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2znzrlbue.html

K. JSON 与序列化
来源：http://dali.dianchejie.cn/Article/details/gt2vaxpvytw.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2bhmckafs.html

[K01] 对象转 JSON 字符串
来源：http://dali.jqgfzy.top/Article/details/gt2bogfavbg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenlongwang.top/Article/details/gt2hxlwhhjf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ehwqpu.com/Article/details/gt2ipirstjx.html

JS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gt2njapscwg.html

TS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2gxpkvrub.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xylfe.cn/Article/details/gt2sukrfwwj.html

Go:   json.Marshal(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2gmqzkgjm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ssyjresl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gzhubu.top/Article/details/gt2vxxcidvw.html

[K02] JSON 字符串转对象
来源：http://dali.yj202588.top/Article/details/gt2dqzwjdrg.html

Py:   json.loads(s)
来源：http://dali.bjfxy.top/Article/details/gt2ebsxxhcf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yuxming.cn/Article/details/gt2tuikmobq.html

JS:   JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gt2kaxnmdpt.html

TS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2lfaksaxr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hnqzz.top/Article/details/gt2vdwirmtk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gt2defmzctu.html

Ruby: JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gt2actoxkrj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yongpay.top/Article/details/gt2oatvqhey.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gzhubu.top/Article/details/gt2lmqocgvm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenzaomai.com/Article/details/gt2pewpnblz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.smart0.xyz/Article/details/gt2ufbgpfsu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gt2iuffnrlp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gt2njikewla.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sweek.top/Article/details/gt2pvvqcsmh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xuanzx.com/Article/details/gt2jgnlwpiw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnqzz.top/Article/details/gt2mdvtxkhu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ivvv.top/Article/details/gt2qrqppypn.html

[K04] 读取 JSON 文件
来源：http://dali.9152youxi.cn/Article/details/gt2lnnudvrn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xziqi.cn/Article/details/gt2gbpwmysz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cqqwz.cn/Article/details/gt2zzyowxix.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dianchejie.cn/Article/details/gt2zrbwtkbb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ydzc1.top/Article/details/gt2mlleaxyc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jqgfzy.top/Article/details/gt2twqvubuo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gt2usoqtqax.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cpocysiz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jqgfzy.top/Article/details/gt2vubfekge.html

[K05] 深拷贝对象
来源：http://dali.sweek.top/Article/details/gt2kmexrcfa.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2gdzvzgcj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jianghu66.top/Article/details/gt2ealqdzwx.html

JS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2cmyfwqof.html

TS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2pteadluu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cqqwz.cn/Article/details/gt2subgmomx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gogol.net.cn/Article/details/gt2vmqxtbmp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cucudq.cn/Article/details/gt2qtcqimfh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.aizwys.cn/Article/details/gt2kbrljhts.html

[K06] 解析 URL 查询串
来源：http://dali.fzhhl.top/Article/details/gt2cfaocvml.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sweek.top/Article/details/gt2vwzmtylh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xinyue.icu/Article/details/gt2ipxzzjgi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.havefunace.top/Article/details/gt2htbtzscd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cucudq.cn/Article/details/gt2fguoujrl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258.top/Article/details/gt2cglaphdt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gt2gbixenmi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gt2etkqlexb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gt2wluvgxrz.html

[K07] 进制转换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ylhemkbw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gt2axgbwnoz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.kuanghao11.cn/Article/details/gt2jnnxdmwt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ijfzuhse.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gt2sxuiopqs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gt2zevtoyvm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gaohongyu789.top/Article/details/gt2uwzzouah.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kweyroxb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258.top/Article/details/gt2xrtuckbo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.316326.xyz/Article/details/gt2kepxsrdg.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2oygljnqr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xylfe.cn/Article/details/gt2qxhjolqx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gt2eyjvvcbh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.9152youxi.cn/Article/details/gt2fwdlagdf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenjidiqi.icu/Article/details/gt2aynsknka.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2ydohdtde.html

Ruby: Marshal.dump(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2sppugulp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yanxiufei.cn/Article/details/gt2ofenmsjx.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2cspexjnz.html

L. 网络请求
来源：http://dali.vqdsnc.cn/Article/details/gt2jszqxhtk.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2dyyzgpwh.html

[L01] 发送 GET 请求
来源：http://dali.xuetiantiany.cn/Article/details/gt2soaoelnl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xylfe.cn/Article/details/gt2sqgwrjlb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xvnmrgur.html

JS:   await fetch(url)
来源：http://dali.birdmap.top/Article/details/gt2suogzlef.html

TS:   await fetch(url)
来源：http://dali.yueranfly.top/Article/details/gt2fasvyfyp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jyoumei.cn/Article/details/gt2moszifak.html

Go:   resp, err := http.Get(url)
来源：http://dali.redwolf501.top/Article/details/gt2brrbrngl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.meibo888.top/Article/details/gt2jdqsenfv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj202588.top/Article/details/gt2eujuuzou.html

[L02] 发送 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gt2wyblhpbo.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gt2jcyotyho.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.smart0.xyz/Article/details/gt2lgmpgqtj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nwbrower.top/Article/details/gt2ulsgwfcy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cucudq.cn/Article/details/gt2rfpvcawa.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xuanzx.com/Article/details/gt2xwlzlcsf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.aizwys.cn/Article/details/gt2yptliwqh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ppjwa.cn/Article/details/gt2zikakhps.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daxiang520.top/Article/details/gt2jrrziysi.html

[L03] 设置自定义请求头
来源：http://dali.ydzc1.top/Article/details/gt2ibtcssdk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.kuanghao11.cn/Article/details/gt2luqzgnja.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2cvbghghf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yvedp.cn/Article/details/gt2wxtwgmsa.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.snrcjt.cn/Article/details/gt2uthnzdqz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xuetiantiany.cn/Article/details/gt2luznxovn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sxryk.cn/Article/details/gt2pdflskxl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.haohaochexian.top/Article/details/gt2wnbdzhqq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yanxiufei.cn/Article/details/gt2zgaswtsc.html

[L04] 设置超时
来源：http://dali.wangdashe.top/Article/details/gt2tylfwbiu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hammf.cn/Article/details/gt2xzffppbx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinqigufen.top/Article/details/gt2mfyqyzte.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hfpthk.cn/Article/details/gt2unfvukxa.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sysykeji.top/Article/details/gt2oriidije.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.snrcjt.cn/Article/details/gt2wukivfbm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shangyingyoupin.top/Article/details/gt2ujwxjeoz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jiagoushi.top/Article/details/gt2ibniiiaf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cheryme.top/Article/details/gt2qmklylqk.html

[L05] 上传文件（multipart）
来源：http://dali.fzhhl.top/Article/details/gt2uxlqcyrn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sufxvd.cn/Article/details/gt2diwzdrbs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cucudq.cn/Article/details/gt2yakrifzs.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigufen.top/Article/details/gt2vrkievcq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yangfankeji.com/Article/details/gt2vdoynlqq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guowangkeji.top/Article/details/gt2vskphazy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sysykeji.top/Article/details/gt2oqychfxs.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ppjwa.cn/Article/details/gt2lejtkunz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2bspnblbj.html

[L06] 解析响应为 JSON
来源：http://dali.316326.xyz/Article/details/gt2dotnvbtu.html

Py:   resp.json()
来源：http://dali.birdmap.top/Article/details/gt2vimymhcr.html

PHP:  json_decode($body, true);
来源：http://dali.guowangkeji.top/Article/details/gt2seyyjkbt.html

JS:   await resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gt2nfhbsxly.html

TS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gt2yrfwgnul.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gt2hmgckgfc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yanxiufei.cn/Article/details/gt2pcelsgam.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wxgigkfp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhongyouzk.top/Article/details/gt2czrnsdwn.html

[L07] 处理 HTTP 状态码
来源：http://dali.xinyue.icu/Article/details/gt2kuewffvi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.meibo888.top/Article/details/gt2btzlrtfb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zpxkyrbi.html

JS:   resp.ok;  resp.status
来源：http://dali.hywenlv.cn/Article/details/gt2egmpfwyh.html

TS:   resp.ok;  resp.status
来源：http://dali.ydzc1.top/Article/details/gt2bxeghmdx.html

Java: resp.statusCode()
来源：http://dali.jianghu66.top/Article/details/gt2ppzcxsiv.html

Go:   resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gt2kehhjcsx.html

Ruby: resp.code.to_i
来源：http://dali.nanxuanxn.top/Article/details/gt2usnrpjrh.html

C#:   (int)resp.StatusCode
来源：http://dali.daria6918.cn/Article/details/gt2lyujxfle.html

[L08] 并发请求多个地址
来源：http://dali.yj20258888.top/Article/details/gt2aqoigbrv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ileloolh.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenlongwang.top/Article/details/gt2lljqtcke.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gt2sszxjngj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gt2hcvzgbng.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.haohaochexian.top/Article/details/gt2wfeqdtqh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.guannengcc.top/Article/details/gt2ncksvxgt.html


<!-- 参考信息 -->