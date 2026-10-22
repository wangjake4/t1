代发 wailian999

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2wptayvfn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhengqikj.top/Article/details/gt2kmrzbgjr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhoulong.xyz/Article/details/gt2kuapvvqa.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.aizwys.cn/Article/details/gt2qozbissr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.wangdashe.top/Article/details/gt2qywosban.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj202588.top/Article/details/gt2zkqpaujo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpfkzdc.html

[I05] 按正则拆分
来源：http://dali.gzhubu.top/Article/details/gt2kyptpkbt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vjbfyxlo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258.top/Article/details/gt2qbwgiikc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gt2vygwskjz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gt2oxujkljs.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hysaishi.cn/Article/details/gt2kftyvoaz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xeintuwr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gt2dbgchkkq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhongyouzk.top/Article/details/gt2nerzdojp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tian-w.cn/Article/details/gt2yadxpsbj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gt2dqaoqikd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hnxiangtu.top/Article/details/gt2lkuivnbe.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daxiang520.top/Article/details/gt2horllado.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gt2ricdsbud.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iaoetstr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bbpzurin.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hywenlv.cn/Article/details/gt2zoiiojal.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yonumen.top/Article/details/gt2irexjkfn.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenzaomai.com/Article/details/gt2wvyyovtg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cucudq.cn/Article/details/gt2pzmalhgb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lwpzghbu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yuanzhike.top/Article/details/gt2njbenskj.html

TS:   /error/gim
来源：http://dali.feifeiyinyue.top/Article/details/gt2wuisorhl.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pvaspnei.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jyoumei.cn/Article/details/gt2zbqqxdoo.html

Ruby: s.scan(/error/i)
来源：http://dali.tian-w.cn/Article/details/gt2xvksjvku.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hywenlv.cn/Article/details/gt2mhvsnzhd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tian-w.cn/Article/details/gt2nahkwapf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hnqzz.top/Article/details/gt2iecctsgc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gt2mkcoeqoo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhixingplan.top/Article/details/gt2ajlgzrom.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dianchejie.cn/Article/details/gt2bqucrltv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jqgufenzy.top/Article/details/gt2vypuoilg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenjidiqi.icu/Article/details/gt2nuwwipri.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sufxvd.cn/Article/details/gt2asgreqaq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.kuanghao11.cn/Article/details/gt2lfumgzzl.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2ihhqsrqf.html

J. 日期与时间
来源：http://dali.ppjwa.cn/Article/details/gt2voptdjni.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2rkvdttli.html

[J01] 获取当前时间
来源：http://dali.bjfxy.top/Article/details/gt2yzjdjhuz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ootrikuv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2phoatccw.html

JS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gt2uykluvty.html

TS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gt2tskqygzn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jiagoushi.top/Article/details/gt2sanxtqxv.html

Go:   time.Now()
来源：http://dali.yj20258.top/Article/details/gt2ndecurec.html

Ruby: Time.now
来源：http://dali.xuanzx.com/Article/details/gt2exitlspx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dashuyun.cn/Article/details/gt2qdzlvcts.html

[J02] 格式化输出
来源：http://dali.jianghu66.top/Article/details/gt2rzljcklk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shzxlz.cn/Article/details/gt2hdmbjkyn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gt2yzdxlooj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daria6918.cn/Article/details/gt2ighjsvya.html

TS:   d.toISOString()
来源：http://dali.hnqzz.top/Article/details/gt2vxxnjuli.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hongshengwenyu.top/Article/details/gt2vxfwzres.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tanke756.top/Article/details/gt2wfrxoaxt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.andypj.xyz/Article/details/gt2ekkbjflj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.meibo888.top/Article/details/gt2strctmgs.html

[J03] 字符串解析为日期
来源：http://dali.ehwqpu.com/Article/details/gt2ubdfwjwl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenjidiqi.icu/Article/details/gt2tcthjdde.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.bjfxy.top/Article/details/gt2iseepygd.html

JS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gt2bjjepxws.html

TS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gt2ybbtlyuz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gt2geamvjtd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.meibo888.top/Article/details/gt2pphfyoya.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gt2fpzhtqui.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cashguo.top/Article/details/gt2cxwjyrpg.html

[J04] 时间戳与日期互转
来源：http://dali.sysykeji.top/Article/details/gt2rqoyvczn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xziqi.cn/Article/details/gt2vucqhqym.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rvbkzclf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.iojbl.cn/Article/details/gt2mrafueat.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nanxuanxn.top/Article/details/gt2ttmltnko.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hammf.cn/Article/details/gt2mrjsyrqs.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tian-w.cn/Article/details/gt2yizdttvn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.fengsongda.top/Article/details/gt2cccesouz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.aibaodan.cn/Article/details/gt2livtadet.html

[J05] 时间加减（加 7 天）
来源：http://dali.xinyue.icu/Article/details/gt2aywnonrx.html

Py:   now + timedelta(days=7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fexaseta.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhongyouzk.top/Article/details/gt2ijqvrqbo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258888.top/Article/details/gt2hxkeemjf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gt2imbwlfsk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lnrvsfxh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jiagoushi.top/Article/details/gt2vxxbgfvp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnxiangtu.top/Article/details/gt2frlyxryd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yueranfly.top/Article/details/gt2lqxvbyer.html

[J06] 计算两时间之差
来源：http://dali.gzhubu.top/Article/details/gt2hpohitiz.html

Py:   (end - start).total_seconds()
来源：http://dali.xuetiantiany.cn/Article/details/gt2abkwjjpc.html

PHP:  $end->diff($start)->days;
来源：http://dali.havefunace.top/Article/details/gt2rmjdxiek.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bjnxhrrn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xylfe.cn/Article/details/gt2zozxkvak.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhengqikj.top/Article/details/gt2ximlfkka.html

Go:   end.Sub(start).Hours()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pbpkukii.html

Ruby: end - start                 # 返回秒数
来源：http://dali.c1oappe.top/Article/details/gt2cofpleur.html

C#:   (end - start).TotalSeconds
来源：http://dali.sysykeji.top/Article/details/gt2dnttlclb.html

[J07] 比较两个日期
来源：http://dali.cqqwz.cn/Article/details/gt2jcwuwbdg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dwjqlzor.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aibaodan.cn/Article/details/gt2zsgvpcdz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.guowangkeji.top/Article/details/gt2lyzfogen.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.guowangkeji.top/Article/details/gt2hwmvltaj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tian-w.cn/Article/details/gt2zaggxtbj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shuidangran.top/Article/details/gt2rykpsjli.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gt2dysowsrp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gt2klsfvpzf.html

[J08] 提取年月日与星期
来源：http://dali.cashguo.top/Article/details/gt2gkhjuzjr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zycfv.cn/Article/details/gt2wmyjvtjs.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.daria6918.cn/Article/details/gt2ejvoqrez.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jqgufenzy.top/Article/details/gt2dtfdqwvb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zjuceesm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xylfe.cn/Article/details/gt2kdugwffz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yueranfly.top/Article/details/gt2gcejemrc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xuetiantiany.cn/Article/details/gt2cpzzrvpg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinqigufen.top/Article/details/gt2vvgmjair.html

[J09] 时区处理
来源：http://dali.yongpay.top/Article/details/gt2qbaimpzt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hnxiangtu.top/Article/details/gt2lxxihorn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gzhubu.top/Article/details/gt2vbzhltis.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gt2jucbexrf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yanxiufei.cn/Article/details/gt2wuljajzk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.c1oappe.top/Article/details/gt2zhevvyiv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qhmkwxzx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangshuangyany.cn/Article/details/gt2wqjvmpnr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gaohongyu789.top/Article/details/gt2udpbafdl.html

[J10] 取今天 / 本月第一天
来源：http://dali.cdnleiting.top/Article/details/gt2kgwmcyxv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gotoacloud.top/Article/details/gt2sdvuvygc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tianlin.xyz/Article/details/gt2vhmyxpta.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jyoumei.cn/Article/details/gt2dvddscih.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cyhwtezf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.havefunace.top/Article/details/gt2kmuuowcb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.guannengcc.top/Article/details/gt2nqmrzygg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.redwolf501.top/Article/details/gt2rmwcboor.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2tzdoloyz.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2namwidoq.html

K. JSON 与序列化
来源：http://dali.guannengcc.top/Article/details/gt2klgqlqyh.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2wjudzyze.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2rnxnwjud.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gt2rearhtam.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.vqdsnc.cn/Article/details/gt2asroxoke.html

JS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2juzovjgv.html

TS:   JSON.stringify(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qtejqayf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hihytpjc.html

Go:   json.Marshal(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2pdhtqnfk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yueranfly.top/Article/details/gt2xekjchcm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ghbyethf.html

[K02] JSON 字符串转对象
来源：http://dali.havefunace.top/Article/details/gt2nojwahxf.html

Py:   json.loads(s)
来源：http://dali.chenlongwang.top/Article/details/gt2mrkcviye.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2pydlxkwk.html

JS:   JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gt2waxsrvns.html

TS:   JSON.parse(s)
来源：http://dali.birdmap.top/Article/details/gt2jtdfmhoz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.smart0.xyz/Article/details/gt2lvhccqxf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.haohaochexian.top/Article/details/gt2xdwayaxe.html

Ruby: JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gt2kijkscba.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yonumen.top/Article/details/gt2gwltjqcg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ycovnifl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.daxiang520.top/Article/details/gt2uqjyrrxc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gt2gvkhskoh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2znxjfdrs.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.tian-w.cn/Article/details/gt2sennyylw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pjiwlsjx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iitzaksu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2depzrivf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.wangshuangyany.cn/Article/details/gt2wbnwboyh.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258.top/Article/details/gt2dluvmxqy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sufxvd.cn/Article/details/gt2nozdybdl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.feifeiyinyue.top/Article/details/gt2mwpsoqtf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pycfn.com/Article/details/gt2gkatrsel.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gaohongyu789.top/Article/details/gt2ulflldhx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gt2yrcivkbj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhoulong.xyz/Article/details/gt2wuxlnhgx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nwbrower.top/Article/details/gt2rhnqzwid.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.aibaodan.cn/Article/details/gt2xvhifhfh.html

[K05] 深拷贝对象
来源：http://dali.sweek.top/Article/details/gt2xlgfwzhh.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yjtytnhp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.c1oappe.top/Article/details/gt2wsmmnyui.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jsmbughn.html

TS:   structuredClone(obj)
来源：http://dali.daxiang520.top/Article/details/gt2sxemsfkv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shuidangran.top/Article/details/gt2jxlvhzlk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuanzx.com/Article/details/gt2olgigvck.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2omscfclm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.havefunace.top/Article/details/gt2cucahdui.html

[K06] 解析 URL 查询串
来源：http://dali.redwolf501.top/Article/details/gt2xnqpkxjy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.wangshuangyany.cn/Article/details/gt2dbhkudde.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gogol.net.cn/Article/details/gt2vhpuwoly.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gt2qqkyeumx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gt2xelewgfp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yuxming.cn/Article/details/gt2byskxsfz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gt2ivwjhrib.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gt2cmmesaag.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gt2amvskbvm.html

[K07] 进制转换
来源：http://dali.guannengcc.top/Article/details/gt2bvgojdrc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lksvrbbx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ppjwa.cn/Article/details/gt2pxtoxcuk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tgavtvfb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2oapwdnea.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gt2mfyftmuu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.c1oappe.top/Article/details/gt2sfjzzxrd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ueeonaus.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gt2qmhkkdss.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenzaomai.com/Article/details/gt2jnvllavw.html

Py:   pickle.dumps(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2fyjmjmub.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sweek.top/Article/details/gt2oagxebqd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.guannengcc.top/Article/details/gt2nswklwda.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shangyingyoupin.top/Article/details/gt2bduahhtb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.aizwys.cn/Article/details/gt2acyqhfhi.html

Go:   encoding/gob
来源：http://dali.yj20258.top/Article/details/gt2lskcaudf.html

Ruby: Marshal.dump(obj)
来源：http://dali.sxryk.cn/Article/details/gt2ocmngaxw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhoulong.xyz/Article/details/gt2fkdfhefi.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2ozzshbxv.html

L. 网络请求
来源：http://dali.hfpthk.cn/Article/details/gt2ejebjjui.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2xdccqjbu.html

[L01] 发送 GET 请求
来源：http://dali.xuetiantiany.cn/Article/details/gt2yrkefmpc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tanke756.top/Article/details/gt2zlestqcz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.pengpengdd.cyou/Article/details/gt2sofnirli.html

JS:   await fetch(url)
来源：http://dali.jinqigufen.top/Article/details/gt2oecfwelu.html

TS:   await fetch(url)
来源：http://dali.gogol.net.cn/Article/details/gt2wmvdwfmt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gaohongyu789.top/Article/details/gt2qgnfzxvf.html

Go:   resp, err := http.Get(url)
来源：http://dali.daxiang520.top/Article/details/gt2qafvbcbs.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xuetiantiany.cn/Article/details/gt2cqmtjwnc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.andypj.xyz/Article/details/gt2vyirmfks.html

[L02] 发送 POST JSON
来源：http://dali.yonumen.top/Article/details/gt2potencja.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.guowangkeji.top/Article/details/gt2nekalpio.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnxiangtu.top/Article/details/gt2pvbylknm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hammf.cn/Article/details/gt2pbvcdmuk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dashuyun.cn/Article/details/gt2joskydzp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shuidangran.top/Article/details/gt2vkyvakau.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.wangshuangyany.cn/Article/details/gt2czijswmo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nwbrower.top/Article/details/gt2cmmyqhdo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.wangdashe.top/Article/details/gt2zieqtekl.html

[L03] 设置自定义请求头
来源：http://dali.yangfankeji.com/Article/details/gt2wpczokoo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhixingplan.top/Article/details/gt2aopkdplw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gzhubu.top/Article/details/gt2vtopplkv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangdashe.top/Article/details/gt2yrriajbb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cqqwz.cn/Article/details/gt2yhqizvhl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.birdmap.top/Article/details/gt2dadvueqx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hdjaripa.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gogol.net.cn/Article/details/gt2njdltwxr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gt2eleoqyiz.html

[L04] 设置超时
来源：http://dali.hysaishi.cn/Article/details/gt2bkgldmhu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhengqikj.top/Article/details/gt2qkirrtxb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jianghu66.top/Article/details/gt2lkmdjmnn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.quarkkingdee.top/Article/details/gt2cdixqsfe.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxinkj.top/Article/details/gt2qghupbmu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mhxyxjvx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.9152youxi.cn/Article/details/gt2qdngdqzo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qhwoooug.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yongpay.top/Article/details/gt2pzylxrnk.html

[L05] 上传文件（multipart）
来源：http://dali.nanxinkj.top/Article/details/gt2fbztnoxs.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ppjwa.cn/Article/details/gt2nsyxqiaa.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.9152youxi.cn/Article/details/gt2mvmxdhpf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ehwqpu.com/Article/details/gt2efveyfgf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxuanxn.top/Article/details/gt2zgdnthrn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.bjfxy.top/Article/details/gt2zisqnzrf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.snrcjt.cn/Article/details/gt2womkgyfv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hfpthk.cn/Article/details/gt2ixekabeh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2zyvhqftj.html

[L06] 解析响应为 JSON
来源：http://dali.jinqigfzy.top/Article/details/gt2nrazsdcd.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2wchrbswm.html

PHP:  json_decode($body, true);
来源：http://dali.yongpay.top/Article/details/gt2passxyka.html

JS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gt2bxdjxgsb.html

TS:   await resp.json()
来源：http://dali.sweek.top/Article/details/gt2acuxvuhn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2audezcpe.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sweek.top/Article/details/gt2mlrdkxdg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sysykeji.top/Article/details/gt2ldpweliv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.vqdsnc.cn/Article/details/gt2ylzebnfu.html

[L07] 处理 HTTP 状态码
来源：http://dali.yvedp.cn/Article/details/gt2dszcblhh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinqigufen.top/Article/details/gt2ynaudpov.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gotoacloud.top/Article/details/gt2ftxtbuad.html

JS:   resp.ok;  resp.status
来源：http://dali.yueranfly.top/Article/details/gt2pnpmxnme.html

TS:   resp.ok;  resp.status
来源：http://dali.ppjwa.cn/Article/details/gt2ofxfcgva.html

Java: resp.statusCode()
来源：http://dali.yuanzhike.top/Article/details/gt2skdbtcia.html

Go:   resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gt2uehqrjvi.html

Ruby: resp.code.to_i
来源：http://dali.hywenlv.cn/Article/details/gt2zwqfgbkn.html

C#:   (int)resp.StatusCode
来源：http://dali.gzhubu.top/Article/details/gt2zzqnfvnw.html

[L08] 并发请求多个地址
来源：http://dali.cqqwz.cn/Article/details/gt2yzhljdda.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxbbktd.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhongyouzk.top/Article/details/gt2ijradzpj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gt2tdfyzmmb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nwbrower.top/Article/details/gt2biaoxrao.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cdnleiting.top/Article/details/gt2xppmpdfh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj202588.top/Article/details/gt2kigxraps.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nwbrower.top/Article/details/gt2mswgnqze.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xinyue.icu/Article/details/gt2rwmfugpo.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2mrezwwws.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhiwuduotai.top/Article/details/gt2xtfocdqh.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2oieboexn.html

[M01] 读取命令行参数
来源：http://dali.shzxlz.cn/Article/details/gt2symhldjz.html

Py:   sys.argv[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dcsqupsi.html

PHP:  $argv;  $argc;
来源：http://dali.sweek.top/Article/details/gt2pcbzypyf.html

JS:   process.argv.slice(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2klnvjbiz.html

TS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gt2gybikomp.html

Java: args 数组（main 方法参数）
来源：http://dali.jlsjyb.cn/Article/details/gt2ugmgnfge.html

Go:   os.Args[1:]
来源：http://dali.yonumen.top/Article/details/gt2dupnxwoy.html

Ruby: ARGV
来源：http://dali.vqdsnc.cn/Article/details/gt2vzbjysrh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.meibo888.top/Article/details/gt2ucwgkzhl.html

[M02] 读取环境变量
来源：http://dali.haohaochexian.top/Article/details/gt2jgrdtuoa.html

Py:   os.environ.get("HOME")
来源：http://dali.hfpthk.cn/Article/details/gt2esylwqyx.html


<!-- 参考信息 -->