代发 wailian999

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2xcupskzj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yuxming.cn/Article/details/gt2xqzricxy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2fkjpyktd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gt2wjibaixc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.fengsongda.top/Article/details/gt2dscuugzp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.fengsongda.top/Article/details/gt2ltgittwl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gzhubu.top/Article/details/gt2hoqnknie.html

[I05] 按正则拆分
来源：http://dali.quarkkingdee.top/Article/details/gt2rzphpqqx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ppjwa.cn/Article/details/gt2pzqjxfaq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.fzhhl.top/Article/details/gt2clfakmax.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gt2dfmthedy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gt2exbbjugq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.guannengcc.top/Article/details/gt2sszohkjp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gogol.net.cn/Article/details/gt2wbufexnk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gt2skzriiaj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhoulong.xyz/Article/details/gt2thbxhkgw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cqqwz.cn/Article/details/gt2sldzljci.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gt2qjstcihv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cashguo.top/Article/details/gt2ljdfjjdh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gt2lkdsxomd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigufen.top/Article/details/gt2pegzsyfg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gt2akdmlecl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.redwolf501.top/Article/details/gt2lpxtmeph.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gaohongyu789.top/Article/details/gt2yibeaafk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gt2xmjqcqki.html

[I07] 忽略大小写与多行模式
来源：http://dali.sufxvd.cn/Article/details/gt2ewfqolir.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhengqikj.top/Article/details/gt2gpegffjl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gt2wydjgwex.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigufen.top/Article/details/gt2ruffzmlc.html

TS:   /error/gim
来源：http://dali.nanxinkj.top/Article/details/gt2ezfcywli.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cheryme.top/Article/details/gt2hwrscspr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj20258888.top/Article/details/gt2eevnecuo.html

Ruby: s.scan(/error/i)
来源：http://dali.yanxiufei.cn/Article/details/gt2pdmxypzl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.wangshuangyany.cn/Article/details/gt2metehcjw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sufxvd.cn/Article/details/gt2gjzfmdfo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.haohaochexian.top/Article/details/gt2ooqljhcw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gt2bjnymiee.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ayzoqsix.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daria6918.cn/Article/details/gt2oyyrxlin.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.wangshuangyany.cn/Article/details/gt2dleamhbs.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vvyrfwaf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2evkfomga.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gt2sjpzkngf.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2vewglfzd.html

J. 日期与时间
来源：http://dali.wangshuangyany.cn/Article/details/gt2zxdprjrl.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2godsdpfz.html

[J01] 获取当前时间
来源：http://dali.aibaodan.cn/Article/details/gt2ewxsmnrs.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xinyue.icu/Article/details/gt2nxdfmjmp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yuzirgut.html

JS:   new Date();  Date.now()
来源：http://dali.fengsongda.top/Article/details/gt2lruzdncc.html

TS:   new Date();  Date.now()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ijlfpsmp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hywenlv.cn/Article/details/gt2afmuwhrc.html

Go:   time.Now()
来源：http://dali.snrcjt.cn/Article/details/gt2tcmyalzd.html

Ruby: Time.now
来源：http://dali.shuidangran.top/Article/details/gt2znxvhlcx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jiagoushi.top/Article/details/gt2wdojkjyf.html

[J02] 格式化输出
来源：http://dali.jianghu66.top/Article/details/gt2ofodmsxg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xziqi.cn/Article/details/gt2cabrotkz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj202588.top/Article/details/gt2occimaay.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jhhehvgo.html

TS:   d.toISOString()
来源：http://dali.ybcxt.top/Article/details/gt2lzfofpar.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.redwolf501.top/Article/details/gt2ybzhtiuj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.svipenyu.cn/Article/details/gt2ofmvwsrv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gt2xbldufyc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.wangdashe.top/Article/details/gt2kthjhlva.html

[J03] 字符串解析为日期
来源：http://dali.gogol.net.cn/Article/details/gt2qchzrwtp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sufxvd.cn/Article/details/gt2nknbqetw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhoulong.xyz/Article/details/gt2edtmnctn.html

JS:   new Date("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gt2wnywmnap.html

TS:   new Date("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gt2xjjjthll.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gt2fhumnbjg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gt2tjneigxh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2urgxncnp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yangfankeji.com/Article/details/gt2eyvyhwgx.html

[J04] 时间戳与日期互转
来源：http://dali.ehwqpu.com/Article/details/gt2fegaqqfk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinqigfzy.top/Article/details/gt2qcibvfjc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gzhubu.top/Article/details/gt2tigmkwmg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xuetiantiany.cn/Article/details/gt2yrppmpcl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ppjwa.cn/Article/details/gt2webhfxrw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gaohongyu789.top/Article/details/gt2ymecowbz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2urfukoib.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cucudq.cn/Article/details/gt2xlwqiwmd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ehwqpu.com/Article/details/gt2zrifnftc.html

[J05] 时间加减（加 7 天）
来源：http://dali.pengpengdd.cyou/Article/details/gt2mkwqyzca.html

Py:   now + timedelta(days=7)
来源：http://dali.ehwqpu.com/Article/details/gt2fqmrksic.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhixingplan.top/Article/details/gt2seszndnz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eedyfxih.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.svipenyu.cn/Article/details/gt2npbegvev.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.svipenyu.cn/Article/details/gt2oypkhbra.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hysaishi.cn/Article/details/gt2utlansca.html

Ruby: Time.now + 7 * 86400
来源：http://dali.andypj.xyz/Article/details/gt2idqttjuc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ivvv.top/Article/details/gt2rgynqilh.html

[J06] 计算两时间之差
来源：http://dali.cheryme.top/Article/details/gt2kgnavgbm.html

Py:   (end - start).total_seconds()
来源：http://dali.andypj.xyz/Article/details/gt2bvptrdtc.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenjidiqi.icu/Article/details/gt2kgayqseq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sikzammp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tian-w.cn/Article/details/gt2vpynzllz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aibaodan.cn/Article/details/gt2uqouzjzn.html

Go:   end.Sub(start).Hours()
来源：http://dali.yueranfly.top/Article/details/gt2fwzqrkut.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tianlin.xyz/Article/details/gt2bveobxar.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenlongwang.top/Article/details/gt2qflecyfw.html

[J07] 比较两个日期
来源：http://dali.dianchejie.cn/Article/details/gt2tfxnzdff.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gt2ctlzmzdz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vlzdjlbd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hongshengwenyu.top/Article/details/gt2wgymsuqc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gt2ighykran.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ydzc1.top/Article/details/gt2naixodjf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yvedp.cn/Article/details/gt2csmhhuuj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gt2yvkkmlvx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gt2misodeot.html

[J08] 提取年月日与星期
来源：http://dali.xuetiantiany.cn/Article/details/gt2jgsabeqj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tianlin.xyz/Article/details/gt2ywkrftau.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tianlin.xyz/Article/details/gt2uzfmvtrp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cqqwz.cn/Article/details/gt2ejusarzi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xuanzx.com/Article/details/gt2pvjtepfj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cqqwz.cn/Article/details/gt2gtmvadit.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tanke756.top/Article/details/gt2xnsgnbmn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj20258.top/Article/details/gt2svbcdgoi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.feifeiyinyue.top/Article/details/gt2sudqdlbn.html

[J09] 时区处理
来源：http://dali.yj20258.top/Article/details/gt2sdqahlab.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.bjfxy.top/Article/details/gt2ucjincoy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj20258888.top/Article/details/gt2kfsentht.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zdqjudy.top/Article/details/gt2aeqppmom.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigufen.top/Article/details/gt2rictxbwl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.feifeiyinyue.top/Article/details/gt2isazsgka.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shzxlz.cn/Article/details/gt2dwdfrmmx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2irtofubw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jyoumei.cn/Article/details/gt2gmalfnka.html

[J10] 取今天 / 本月第一天
来源：http://dali.tian-w.cn/Article/details/gt2zzpphcjg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jlsjyb.cn/Article/details/gt2hcnogdfk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhengqikj.top/Article/details/gt2ooxdmmkh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shuidangran.top/Article/details/gt2mqujkmxc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.havefunace.top/Article/details/gt2hwedhkee.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kmiyxxuk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinqigfzy.top/Article/details/gt2qgujyjxu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuetiantiany.cn/Article/details/gt2rehxmugu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.0kj1m.cn/Article/details/gt2krkknwmw.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2aqswbunr.html

K. JSON 与序列化
来源：http://dali.dashuyun.cn/Article/details/gt2tuxbadll.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zxdhoewy.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuanzx.com/Article/details/gt2zajmvpkq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dneauvfd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gt2fkbmclrz.html

JS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2ohdezvgg.html

TS:   JSON.stringify(obj)
来源：http://dali.gzhubu.top/Article/details/gt2lwvyprwo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ybcxt.top/Article/details/gt2vwndtytb.html

Go:   json.Marshal(obj)
来源：http://dali.pycfn.com/Article/details/gt2shyrlfyi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.havefunace.top/Article/details/gt2zwgyxkmr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2epzseqnq.html

[K02] JSON 字符串转对象
来源：http://dali.ivvv.top/Article/details/gt2fogbdqfv.html

Py:   json.loads(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kbrtybox.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shuidangran.top/Article/details/gt2bikiwcky.html

JS:   JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gt2etisnuwr.html

TS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gt2dcwyuvtg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj20258888.top/Article/details/gt2fhlcpiuf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gt2sfcylyri.html

Ruby: JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gt2xzwvdrxq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2qijlbzhm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.iojbl.cn/Article/details/gt2utymemec.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2neqgbnga.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yongpay.top/Article/details/gt2cnwcddhm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aohkmiwe.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gt2otonmjyg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zycfv.cn/Article/details/gt2shladaxd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.guowangkeji.top/Article/details/gt2fbhzyngd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2rzkipqfo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xylfe.cn/Article/details/gt2cylkwall.html

[K04] 读取 JSON 文件
来源：http://dali.jinqigufen.top/Article/details/gt2rqfpremd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tanke756.top/Article/details/gt2jvjcjlvx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gaohongyu789.top/Article/details/gt2ruiilsom.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gt2wvbetzlp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnqzz.top/Article/details/gt2ylmgzzff.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jiagoushi.top/Article/details/gt2eijedghy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cucudq.cn/Article/details/gt2pkrllzoe.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gt2ayujewxg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ybcxt.top/Article/details/gt2lkqjhquj.html

[K05] 深拷贝对象
来源：http://dali.ppjwa.cn/Article/details/gt2icwnopcm.html

Py:   copy.deepcopy(obj)
来源：http://dali.hammf.cn/Article/details/gt2whflteuk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhixingplan.top/Article/details/gt2hwmcires.html

JS:   structuredClone(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2cprnezln.html

TS:   structuredClone(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2crhcvdgx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cdnleiting.top/Article/details/gt2wmtornrr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cheryme.top/Article/details/gt2rlhaidcw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cashguo.top/Article/details/gt2fljkoafp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.vqdsnc.cn/Article/details/gt2vqztlfzp.html

[K06] 解析 URL 查询串
来源：http://dali.dashuyun.cn/Article/details/gt2vljspynr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cucudq.cn/Article/details/gt2iphpgmjk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nwbrower.top/Article/details/gt2lzsycpkv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kcpbbpzm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.feifeiyinyue.top/Article/details/gt2whtbgjbg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cucudq.cn/Article/details/gt2lvsqxtgv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gt2ayujfupc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gt2bnqetzln.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gt2vzfjihqr.html

[K07] 进制转换
来源：http://dali.zhoulong.xyz/Article/details/gt2ozzkcfaq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hammf.cn/Article/details/gt2awezlvkh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cucudq.cn/Article/details/gt2udodpyzf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2enasysdk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gt2ifhculay.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gt2jtpcsjiy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgfzy.top/Article/details/gt2aeqnhhor.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ioycbccj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vaygzbrm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.wangdashe.top/Article/details/gt2tdpjufep.html

Py:   pickle.dumps(obj)
来源：http://dali.xuanzx.com/Article/details/gt2znnxuxjb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yanxiufei.cn/Article/details/gt2hwxrkpdr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhongyouzk.top/Article/details/gt2wlarfiju.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.wangdashe.top/Article/details/gt2ddqmzydh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkhkllt.html

Go:   encoding/gob
来源：http://dali.316326.xyz/Article/details/gt2csqpohcq.html

Ruby: Marshal.dump(obj)
来源：http://dali.meibo888.top/Article/details/gt2zztwerkw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinqigfzy.top/Article/details/gt2axggmoil.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2qkgcuvfw.html

L. 网络请求
来源：http://dali.guowangkeji.top/Article/details/gt2temdmoik.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2icufoagw.html

[L01] 发送 GET 请求
来源：http://dali.fzhhl.top/Article/details/gt2uxjgwixy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nanxuanxn.top/Article/details/gt2edvypggu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nhchpqzh.html

JS:   await fetch(url)
来源：http://dali.daria6918.cn/Article/details/gt2rmefvokc.html

TS:   await fetch(url)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fftokots.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xuanzx.com/Article/details/gt2nckgnstw.html

Go:   resp, err := http.Get(url)
来源：http://dali.yueranfly.top/Article/details/gt2nxddmwag.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.9152youxi.cn/Article/details/gt2imdumsuv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj20258888.top/Article/details/gt2yzsqrdmp.html

[L02] 发送 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gt2mmvrhafh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nwbrower.top/Article/details/gt2whxrsild.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhengqikj.top/Article/details/gt2prnwsuvx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fzhhl.top/Article/details/gt2xmozpvxw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tdxyowdr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinqigfzy.top/Article/details/gt2qxqsbgjs.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2frzweajs.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.birdmap.top/Article/details/gt2btpcbrsh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinqigufen.top/Article/details/gt2hgfqdgth.html

[L03] 设置自定义请求头
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qzuccpcx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jyoumei.cn/Article/details/gt2yhgizjbj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gzhubu.top/Article/details/gt2dmzoacul.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.bjfxy.top/Article/details/gt2pdutuyoe.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yueranfly.top/Article/details/gt2cddgvnhx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yueranfly.top/Article/details/gt2oozafdzv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hongshengwenyu.top/Article/details/gt2trvgsujm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shzxlz.cn/Article/details/gt2sfqshnpx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gt2dcimcsoi.html

[L04] 设置超时
来源：http://dali.xylfe.cn/Article/details/gt2azztbrlh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gabydgbg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.guannengcc.top/Article/details/gt2uuoyxogu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ydzc1.top/Article/details/gt2fttyxjmg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daria6918.cn/Article/details/gt2zjwbsimb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhoulong.xyz/Article/details/gt2mjrmakbg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.feifeiyinyue.top/Article/details/gt2snlipuac.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ltquiuon.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tanke756.top/Article/details/gt2srrlzwpu.html

[L05] 上传文件（multipart）
来源：http://dali.haohaochexian.top/Article/details/gt2dgzlyrdx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2seppcunu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yangfankeji.com/Article/details/gt2oikxsvzx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tianlin.xyz/Article/details/gt2fswjjizu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnxiangtu.top/Article/details/gt2mrhohtho.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2jaiojdmt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jlsjyb.cn/Article/details/gt2rcpgwzgo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yvedp.cn/Article/details/gt2xgwifynj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2aijrgsyg.html

[L06] 解析响应为 JSON
来源：http://dali.xziqi.cn/Article/details/gt2lusxsnkx.html

Py:   resp.json()
来源：http://dali.tian-w.cn/Article/details/gt2zfoiwfgq.html

PHP:  json_decode($body, true);
来源：http://dali.cashguo.top/Article/details/gt2wpgyrxgh.html

JS:   await resp.json()
来源：http://dali.hywenlv.cn/Article/details/gt2jtnvtehb.html

TS:   await resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kyullmzo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jqgfzy.top/Article/details/gt2watllxde.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj20258.top/Article/details/gt2zyawdvbd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yvedp.cn/Article/details/gt2baksibmx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tian-w.cn/Article/details/gt2ewkrixzd.html

[L07] 处理 HTTP 状态码
来源：http://dali.kuanghao11.cn/Article/details/gt2whcgpkyg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.haohaochexian.top/Article/details/gt2vrplcaqj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jlsjyb.cn/Article/details/gt2znhmoqxl.html

JS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gt2hexsgtmz.html

TS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gt2mstpjsce.html

Java: resp.statusCode()
来源：http://dali.chenzaomai.com/Article/details/gt2pzbouonx.html

Go:   resp.StatusCode
来源：http://dali.redwolf501.top/Article/details/gt2kajhpves.html

Ruby: resp.code.to_i
来源：http://dali.andypj.xyz/Article/details/gt2qrjgsbdx.html

C#:   (int)resp.StatusCode
来源：http://dali.yanxiufei.cn/Article/details/gt2xacrcsuk.html

[L08] 并发请求多个地址
来源：http://dali.mhx1999.top/Article/details/gt2kpeyacks.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ybcxt.top/Article/details/gt2gsjnycbi.html

PHP:  curl_multi_init() 系列
来源：http://dali.redwolf501.top/Article/details/gt2xwxqkiwd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gt2lyeijzpv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gt2hirpetcc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cucudq.cn/Article/details/gt2zbzdkmbj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hywenlv.cn/Article/details/gt2yehmgvzc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gt2byfryhad.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ppjwa.cn/Article/details/gt2sthsnomh.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2cxmiynht.html

M. 命令行 / 进程 / 环境
来源：http://dali.0kj1m.cn/Article/details/gt2rnxvfhuf.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2opayaulv.html

[M01] 读取命令行参数
来源：http://dali.jinqigfzy.top/Article/details/gt2zsfqnsdy.html

Py:   sys.argv[1:]
来源：http://dali.yueranfly.top/Article/details/gt2hpbyvxni.html

PHP:  $argv;  $argc;
来源：http://dali.zhixingplan.top/Article/details/gt2ohrnidjo.html

JS:   process.argv.slice(2)
来源：http://dali.shuidangran.top/Article/details/gt2dcccjmvj.html

TS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gt2qyozrhnp.html

Java: args 数组（main 方法参数）
来源：http://dali.daria6918.cn/Article/details/gt2uobeyxyf.html

Go:   os.Args[1:]
来源：http://dali.snrcjt.cn/Article/details/gt2ehfvoqdn.html

Ruby: ARGV
来源：http://dali.shzxlz.cn/Article/details/gt2jytnjokl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hammf.cn/Article/details/gt2eqdyddqi.html

[M02] 读取环境变量
来源：http://dali.cucudq.cn/Article/details/gt2hurimvwf.html

Py:   os.environ.get("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fvqacblh.html


<!-- 参考信息 -->