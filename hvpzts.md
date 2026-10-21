代发 wailian999

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtwocwsnuu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cucudq.cn/Article/details/gtexbfwxte.html

[I04] 正则替换
来源：http://dali.aibaodan.cn/Article/details/gtwhfaihlz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.fzhhl.top/Article/details/gtjktxcqvm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.316326.xyz/Article/details/gtpuhjttcv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtlogelhqt.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gtnzonskux.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xinyue.icu/Article/details/gtbaifgotq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.bjfxy.top/Article/details/gtjperxfss.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.dianchejie.cn/Article/details/gtqpmtyksr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxlufaime.html

[I05] 按正则拆分
来源：http://dali.c1oappe.top/Article/details/gtlkouhxut.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yongpay.top/Article/details/gthlaklevd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtruzkhbhp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtwrzynzuw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gtkssyngyr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hywenlv.cn/Article/details/gtxscylnbl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sufxvd.cn/Article/details/gtwuhntapf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gtryzmykpk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.redwolf501.top/Article/details/gttbcchzvr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cucudq.cn/Article/details/gteijuzowa.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtcjvthiyw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yueranfly.top/Article/details/gthvinvhep.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gtghobjunz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258.top/Article/details/gtwmeamend.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtvmahngrr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.daxiang520.top/Article/details/gtoibknlhk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shuidangran.top/Article/details/gtnaivvwzm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gtadzragtx.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenzaomai.com/Article/details/gtumnymwsh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yueranfly.top/Article/details/gtxrdbrhcm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gtxybemrfu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xziqi.cn/Article/details/gtyiiytclc.html

TS:   /error/gim
来源：http://dali.snrcjt.cn/Article/details/gtnzpnadja.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinqigufen.top/Article/details/gthzrvndjt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sweek.top/Article/details/gtisaoolbw.html

Ruby: s.scan(/error/i)
来源：http://dali.hnxiangtu.top/Article/details/gtacnjuqkt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.smart0.xyz/Article/details/gtraqspbzz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.feifeiyinyue.top/Article/details/gturqfpvug.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.meibo888.top/Article/details/gtlkecelog.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.mhx1999.top/Article/details/gtgrdkseed.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jiagoushi.top/Article/details/gtnzpvngcl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gtrdvsozpx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.daxiang520.top/Article/details/gtbszuvnrn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.mhx1999.top/Article/details/gtxnkqthco.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yangfankeji.com/Article/details/gtkcprgrwg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.c1oappe.top/Article/details/gtxwyqwpnm.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtcedkedir.html

J. 日期与时间
来源：http://dali.tian-w.cn/Article/details/gtxbtnzplr.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtdqnvhxgc.html

[J01] 获取当前时间
来源：http://dali.daria6918.cn/Article/details/gtjthisyoa.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jiagoushi.top/Article/details/gtmkttclib.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gthxannxkp.html

JS:   new Date();  Date.now()
来源：http://dali.jinqigufen.top/Article/details/gtixrzqbgu.html

TS:   new Date();  Date.now()
来源：http://dali.ybcxt.top/Article/details/gtvbmevqcg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xziqi.cn/Article/details/gtyrsqpxse.html

Go:   time.Now()
来源：http://dali.jyoumei.cn/Article/details/gtuevckvhi.html

Ruby: Time.now
来源：http://dali.yj202588.top/Article/details/gtlttvdzzu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yanxiufei.cn/Article/details/gtggdlvoej.html

[J02] 格式化输出
来源：http://dali.tianlin.xyz/Article/details/gtvnnwtfay.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xinyue.icu/Article/details/gttilxbulg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gtbmjctphc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.meibo888.top/Article/details/gtkefvxusf.html

TS:   d.toISOString()
来源：http://dali.dashuyun.cn/Article/details/gtbdjpmtjz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ivvv.top/Article/details/gtsjyikwbl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.guannengcc.top/Article/details/gtsgjfuawm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guannengcc.top/Article/details/gtwhxrknrx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daria6918.cn/Article/details/gtcxhblbda.html

[J03] 字符串解析为日期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdnhhhhx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yuanzhike.top/Article/details/gteeusnjdk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenjidiqi.icu/Article/details/gtdrmtjgur.html

JS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtoatptszo.html

TS:   new Date("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtlcthikdw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtmurualis.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtvirtodvp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtiaurcyuc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xziqi.cn/Article/details/gttqnfzoqe.html

[J04] 时间戳与日期互转
来源：http://dali.shzxlz.cn/Article/details/gtegkrpdoo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sxryk.cn/Article/details/gtftadduqf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sweek.top/Article/details/gtlnmqlufz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.316326.xyz/Article/details/gtcxvwaadl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hnqzz.top/Article/details/gtysamimdx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdagmapdt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangdashe.top/Article/details/gtvscxddwg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yueranfly.top/Article/details/gtptnalntx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258888.top/Article/details/gtgpwnhfab.html

[J05] 时间加减（加 7 天）
来源：http://dali.xuanzx.com/Article/details/gtmncwodtt.html

Py:   now + timedelta(days=7)
来源：http://dali.vqdsnc.cn/Article/details/gtvnzvenes.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sysykeji.top/Article/details/gtdzqgtgpr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tian-w.cn/Article/details/gtjesocktt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yongpay.top/Article/details/gtvkxpolnn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjznytegz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.aibaodan.cn/Article/details/gtuemqemsh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.haohaochexian.top/Article/details/gtcovonush.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yonumen.top/Article/details/gtrtnkzuaz.html

[J06] 计算两时间之差
来源：http://dali.fengsongda.top/Article/details/gthluamssf.html

Py:   (end - start).total_seconds()
来源：http://dali.haohaochexian.top/Article/details/gtvidsioxk.html

PHP:  $end->diff($start)->days;
来源：http://dali.cqqwz.cn/Article/details/gtwsrzwxiu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.aibaodan.cn/Article/details/gtrvgzuymc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.iojbl.cn/Article/details/gtlmjikvti.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sysykeji.top/Article/details/gtqqruutgk.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinqigfzy.top/Article/details/gtnebynlgv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gogol.net.cn/Article/details/gtupjpsvvw.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhijiandao.cn/Article/details/gtjuntrehi.html

[J07] 比较两个日期
来源：http://dali.yuxming.cn/Article/details/gtifppmriy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gtzvbxgvmy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gzhubu.top/Article/details/gtvkxtpdvc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gtgafpsxwv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gtvijojcdv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jianghu66.top/Article/details/gtgumgnknw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jqgufenzy.top/Article/details/gtlecplhwl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gtzqwvgmie.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gtdruyyzhy.html

[J08] 提取年月日与星期
来源：http://dali.cashguo.top/Article/details/gtryknrvfi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhixingplan.top/Article/details/gtlnqvkvzt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hysaishi.cn/Article/details/gtzahhrvor.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zdqjudy.top/Article/details/gtbrpixfkw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.9152youxi.cn/Article/details/gthpqszfyi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xziqi.cn/Article/details/gtaargazci.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenlongwang.top/Article/details/gtrcdngced.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cucudq.cn/Article/details/gtsxdywtzo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jiagoushi.top/Article/details/gtubeymptn.html

[J09] 时区处理
来源：http://dali.ivvv.top/Article/details/gtbjnnevqb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.wangdashe.top/Article/details/gtijovnudg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jianghu66.top/Article/details/gtdnunmbkk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.birdmap.top/Article/details/gtujnnkmuy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sufxvd.cn/Article/details/gtvlbmsmzx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yanxiufei.cn/Article/details/gtjiphcidu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinqigfzy.top/Article/details/gttbakshhx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ehwqpu.com/Article/details/gtjrndxcwm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tianlin.xyz/Article/details/gtmhnqzpxq.html

[J10] 取今天 / 本月第一天
来源：http://dali.svipenyu.cn/Article/details/gtjwfgvgqd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.pengpengdd.cyou/Article/details/gtfwntteed.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.redwolf501.top/Article/details/gtjxwlcfci.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hysaishi.cn/Article/details/gtplsulozh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtuigtzmsg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tianlin.xyz/Article/details/gtedjgvckm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pycfn.com/Article/details/gtdagtngtr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.daxiang520.top/Article/details/gtyqyuzngi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.andypj.xyz/Article/details/gtbkjdgfhb.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtebwyyaqp.html

K. JSON 与序列化
来源：http://dali.gotoacloud.top/Article/details/gtrcdjxuwk.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtnojrktoo.html

[K01] 对象转 JSON 字符串
来源：http://dali.yuanzhike.top/Article/details/gtlooepkdt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tian-w.cn/Article/details/gtqnqtlrmb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hnqzz.top/Article/details/gtsfwrreik.html

JS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gtnhlemqle.html

TS:   JSON.stringify(obj)
来源：http://dali.xylfe.cn/Article/details/gtzuppmxau.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pengpengdd.cyou/Article/details/gtuxwxbsqp.html

Go:   json.Marshal(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtlrosdbiz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jianghu66.top/Article/details/gtdxagjzqj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuxming.cn/Article/details/gtiadkqhdl.html

[K02] JSON 字符串转对象
来源：http://dali.mhx1999.top/Article/details/gtnssvnphg.html

Py:   json.loads(s)
来源：http://dali.xinyue.icu/Article/details/gtlkoutrtv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ybcxt.top/Article/details/gtrfehkyfe.html

JS:   JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gtrwscbzys.html

TS:   JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gttgtenzrc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gtffzrfqrn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.dashuyun.cn/Article/details/gtzrglwhal.html

Ruby: JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gtonrohkng.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.birdmap.top/Article/details/gtvzyubryp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.316326.xyz/Article/details/gtxzjgomgu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gtzthbkvvk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gtzpyfxxvu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sufxvd.cn/Article/details/gtdjfgsids.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuanzhike.top/Article/details/gtlxofxthw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnkcxsfr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.smart0.xyz/Article/details/gtrnltpcfq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenlongwang.top/Article/details/gtruprcbxh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tian-w.cn/Article/details/gtbqtohssd.html

[K04] 读取 JSON 文件
来源：http://dali.aibaodan.cn/Article/details/gthwlpjkvs.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sufxvd.cn/Article/details/gtpuftsohy.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sweek.top/Article/details/gtoaloiuqo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tian-w.cn/Article/details/gtsgtmdxlu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xinyue.icu/Article/details/gtejnowcga.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.bjfxy.top/Article/details/gtyqwhlefw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.pengpengdd.cyou/Article/details/gtxqpuqniu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gtsxxlhaoo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yueranfly.top/Article/details/gtmjlvdkts.html

[K05] 深拷贝对象
来源：http://dali.daxiang520.top/Article/details/gtrmudxpez.html

Py:   copy.deepcopy(obj)
来源：http://dali.sxryk.cn/Article/details/gtidtvmtcq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.kuanghao11.cn/Article/details/gtwkqmnywt.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtxkvcpsla.html

TS:   structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gtdpanouai.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ppjwa.cn/Article/details/gtorpfnqhx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yanxiufei.cn/Article/details/gteoiwkfjn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zycfv.cn/Article/details/gthxitefdt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cucudq.cn/Article/details/gtrvlichje.html

[K06] 解析 URL 查询串
来源：http://dali.guannengcc.top/Article/details/gtbwxtxaqx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xuanzx.com/Article/details/gtigkpanfu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xinyue.icu/Article/details/gtqeckruny.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gtkotljcti.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.andypj.xyz/Article/details/gtabbypovt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.iojbl.cn/Article/details/gtngtivymo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gtnltjjnpj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gtaiphycrx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmniwpnjg.html

[K07] 进制转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtowxzxkxk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gthtxcncjo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.0kj1m.cn/Article/details/gtmxxqgqzx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gteaocuwup.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtrfjuplyw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtvyrafxxq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.snrcjt.cn/Article/details/gtryxusidt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yanxiufei.cn/Article/details/gtwfksiquk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtpxhdpbho.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hnqzz.top/Article/details/gtexijmvua.html

Py:   pickle.dumps(obj)
来源：http://dali.gogol.net.cn/Article/details/gtyfvtnwph.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.bjfxy.top/Article/details/gttvpcfbsu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcrfjixzd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tianlin.xyz/Article/details/gtybpmyfoz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinqigfzy.top/Article/details/gtwuhdofte.html

Go:   encoding/gob
来源：http://dali.ybcxt.top/Article/details/gtzjvmlcch.html

Ruby: Marshal.dump(obj)
来源：http://dali.yongpay.top/Article/details/gtwfcpqeot.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gtuzbschco.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gthvtcmbqw.html

L. 网络请求
来源：http://dali.chenlongwang.top/Article/details/gtfzfufyzi.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtotforhsn.html

[L01] 发送 GET 请求
来源：http://dali.tian-w.cn/Article/details/gtrdbqlpvy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxajjvqkj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.kuanghao11.cn/Article/details/gtqeyigiav.html

JS:   await fetch(url)
来源：http://dali.jiagoushi.top/Article/details/gtoknbvudp.html

TS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gtpqeqiing.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xziqi.cn/Article/details/gtxhqgoppv.html

Go:   resp, err := http.Get(url)
来源：http://dali.cqqwz.cn/Article/details/gtgiuuzwso.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhengqikj.top/Article/details/gtijsmebcf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hywenlv.cn/Article/details/gtnsuotxpk.html

[L02] 发送 POST JSON
来源：http://dali.jlsjyb.cn/Article/details/gtcgxlhmgm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dianchejie.cn/Article/details/gtcgadbnnq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nanxinkj.top/Article/details/gtaghzbkmt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gtwrbexrri.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gtsyhvsanx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.dashuyun.cn/Article/details/gtfurcjtvj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zycfv.cn/Article/details/gtadpnopid.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yueranfly.top/Article/details/gtlsvayprz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinqigufen.top/Article/details/gtrqoykjum.html

[L03] 设置自定义请求头
来源：http://dali.zhongyouzk.top/Article/details/gttvvhqlav.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.feifeiyinyue.top/Article/details/gtpdvjyiwl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tian-w.cn/Article/details/gtuqrpnktq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gttxxwxnij.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj202588.top/Article/details/gtboyumyjo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yangfankeji.com/Article/details/gtvkyvhhwt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gtusfgzuzb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.havefunace.top/Article/details/gtmgvecdrh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jlsjyb.cn/Article/details/gtbnebvvll.html

[L04] 设置超时
来源：http://dali.meibo888.top/Article/details/gtwwstwbjm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yongpay.top/Article/details/gtwkuixfmc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.iojbl.cn/Article/details/gtoatzmilo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gtjqrcvmxb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gtccwxvnfp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ivvv.top/Article/details/gtlxyrzsyw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.aizwys.cn/Article/details/gtoecqlabb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cheryme.top/Article/details/gtthhnnbqr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nanxuanxn.top/Article/details/gtjfzxyzgk.html

[L05] 上传文件（multipart）
来源：http://dali.c1oappe.top/Article/details/gtyelnhsar.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxrsiqxxx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.bjfxy.top/Article/details/gtnkzhizhi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ybcxt.top/Article/details/gthlubbtzq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.dashuyun.cn/Article/details/gtvfrmhsdj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.pengpengdd.cyou/Article/details/gteibtyqow.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jiagoushi.top/Article/details/gtofmfnfho.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nanxinkj.top/Article/details/gtezizrued.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yonumen.top/Article/details/gtiwynuivw.html

[L06] 解析响应为 JSON
来源：http://dali.yuxming.cn/Article/details/gtkmmacttl.html

Py:   resp.json()
来源：http://dali.xuanzx.com/Article/details/gtvvemkdpf.html

PHP:  json_decode($body, true);
来源：http://dali.zdqjudy.top/Article/details/gtrsymxemu.html

JS:   await resp.json()
来源：http://dali.xuanzx.com/Article/details/gtqdgfdayc.html

TS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gtgollvjfk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.daria6918.cn/Article/details/gtdutmatnm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenjidiqi.icu/Article/details/gtthoclgou.html

Ruby: JSON.parse(resp.body)
来源：http://dali.quarkkingdee.top/Article/details/gtlthhxhip.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yueranfly.top/Article/details/gtquwpluqh.html

[L07] 处理 HTTP 状态码
来源：http://dali.yanxiufei.cn/Article/details/gtsnvtdysr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.9152youxi.cn/Article/details/gtngmctgqx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nwbrower.top/Article/details/gtrwnxshyg.html

JS:   resp.ok;  resp.status
来源：http://dali.cashguo.top/Article/details/gtxmbukiju.html

TS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gtejuwnkdn.html

Java: resp.statusCode()
来源：http://dali.guowangkeji.top/Article/details/gtpsyiyzhw.html

Go:   resp.StatusCode
来源：http://dali.gzhubu.top/Article/details/gtcvugzzry.html

Ruby: resp.code.to_i
来源：http://dali.gogol.net.cn/Article/details/gtwtvnsnfb.html

C#:   (int)resp.StatusCode
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdllmunrn.html

[L08] 并发请求多个地址
来源：http://dali.xziqi.cn/Article/details/gtzfhkppcz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.316326.xyz/Article/details/gtlwhwqont.html

PHP:  curl_multi_init() 系列
来源：http://dali.cheryme.top/Article/details/gtqceabvlh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdjdmnrnk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gtkfjvfuri.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj20258.top/Article/details/gtjhqbmzhy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.kuanghao11.cn/Article/details/gtrdavelxp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zycfv.cn/Article/details/gtnxgdmkjx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.birdmap.top/Article/details/gtteqigpsv.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtsiarzkqn.html

M. 命令行 / 进程 / 环境
来源：http://dali.nwbrower.top/Article/details/gtwxtuwlot.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtqvwjokki.html

[M01] 读取命令行参数
来源：http://dali.yj20258888.top/Article/details/gtvubyhggc.html

Py:   sys.argv[1:]
来源：http://dali.hammf.cn/Article/details/gtjnfhtyyy.html

PHP:  $argv;  $argc;
来源：http://dali.chenlongwang.top/Article/details/gtesbmjroo.html

JS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gtkxryqeme.html

TS:   process.argv.slice(2)
来源：http://dali.tianlin.xyz/Article/details/gttlyfxtfd.html

Java: args 数组（main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmdsgqprt.html

Go:   os.Args[1:]
来源：http://dali.cdnleiting.top/Article/details/gtahoqmrsc.html


<!-- 参考信息 -->