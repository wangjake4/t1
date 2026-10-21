代发 wailian999

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhixingplan.top/Article/details/gtdkgsnfup.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gotoacloud.top/Article/details/gtrjkmtliv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ehwqpu.com/Article/details/gtznqntevh.html

[I05] 按正则拆分
来源：http://dali.wangshuangyany.cn/Article/details/gtovmpqgyz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ydzc1.top/Article/details/gttxnzloph.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.daria6918.cn/Article/details/gtensponhr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gthouudtpe.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gtjrdlmdwq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jiagoushi.top/Article/details/gtpejnwuuj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxacigwdn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gtprmgvblt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmktmmowb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hywenlv.cn/Article/details/gtsnzyndce.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gteaeyikwl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jqgfzy.top/Article/details/gtqfvrxtlo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigufen.top/Article/details/gtldddbpks.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gtzaeidiez.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gtbjeraqrn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cashguo.top/Article/details/gthmezdgng.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ybcxt.top/Article/details/gtlarlkora.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtodjdwvpf.html

[I07] 忽略大小写与多行模式
来源：http://dali.vqdsnc.cn/Article/details/gtjfhxgmww.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.mhx1999.top/Article/details/gtavsiirbi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gtogrnzugy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.mhx1999.top/Article/details/gtkrpumpbc.html

TS:   /error/gim
来源：http://dali.c1oappe.top/Article/details/gtrbumfvge.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nwbrower.top/Article/details/gtufbwoclt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hysaishi.cn/Article/details/gtoydmwmtm.html

Ruby: s.scan(/error/i)
来源：http://dali.jiagoushi.top/Article/details/gtmuokkboj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhoulong.xyz/Article/details/gtszrevdgn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtrdrpgzpt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cqqwz.cn/Article/details/gtrtwajyjw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxuanxn.top/Article/details/gtpfxmmdoy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nwbrower.top/Article/details/gtuxzxlodp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gtrvqmvesg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jianghu66.top/Article/details/gtdlznurer.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daria6918.cn/Article/details/gtgikotcuc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgufenzy.top/Article/details/gtengjwgrz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.birdmap.top/Article/details/gtxwmhwdfu.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvckivauj.html

J. 日期与时间
来源：http://dali.jqgfzy.top/Article/details/gtotdjmbal.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtozlkhjyb.html

[J01] 获取当前时间
来源：http://dali.nanxinkj.top/Article/details/gtxnnebapd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ehwqpu.com/Article/details/gtsauupfkj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.tianlin.xyz/Article/details/gtbstpedfp.html

JS:   new Date();  Date.now()
来源：http://dali.zhiwuduotai.top/Article/details/gtbscntcgy.html

TS:   new Date();  Date.now()
来源：http://dali.fzhhl.top/Article/details/gtgalaoavp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yanxiufei.cn/Article/details/gtaxveludx.html

Go:   time.Now()
来源：http://dali.c1oappe.top/Article/details/gtthegezls.html

Ruby: Time.now
来源：http://dali.wangshuangyany.cn/Article/details/gtuvsaogws.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nwbrower.top/Article/details/gtzphzslhn.html

[J02] 格式化输出
来源：http://dali.jqgfzy.top/Article/details/gtqotojell.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlcjmemhd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cqqwz.cn/Article/details/gtuurlazpe.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hongshengwenyu.top/Article/details/gtaeqwbqng.html

TS:   d.toISOString()
来源：http://dali.sufxvd.cn/Article/details/gttulrdvoy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.dashuyun.cn/Article/details/gteulcsewa.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yuanzhike.top/Article/details/gtensgpimk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gtmevrijmp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jlsjyb.cn/Article/details/gtxnsbiltc.html

[J03] 字符串解析为日期
来源：http://dali.9152youxi.cn/Article/details/gtgsgodyol.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hnxiangtu.top/Article/details/gthfrxneyh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xziqi.cn/Article/details/gtckoyblig.html

JS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtpidhimhn.html

TS:   new Date("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfimkmtob.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gtoxjsgyqw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtrmfjmemr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtsjgyengw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xziqi.cn/Article/details/gtrppdnwtz.html

[J04] 时间戳与日期互转
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrtvvdkja.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ybcxt.top/Article/details/gtwipodsby.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.9152youxi.cn/Article/details/gtqjvfrjvg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shangyingyoupin.top/Article/details/gtplqcowrt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.aizwys.cn/Article/details/gtzvfkadkc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sysykeji.top/Article/details/gtphhssnvt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.meibo888.top/Article/details/gtcicsasmd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yuxming.cn/Article/details/gteuhephuc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.daxiang520.top/Article/details/gtifwtancd.html

[J05] 时间加减（加 7 天）
来源：http://dali.haohaochexian.top/Article/details/gtcuzrased.html

Py:   now + timedelta(days=7)
来源：http://dali.guannengcc.top/Article/details/gtzorokipk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cashguo.top/Article/details/gtmacuqjxe.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangdashe.top/Article/details/gthkytjtdu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gtbreiddhs.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yonumen.top/Article/details/gtuzcluidm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ehwqpu.com/Article/details/gtogmiihys.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ppjwa.cn/Article/details/gtvitbwnwb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenzaomai.com/Article/details/gteamnjxxf.html

[J06] 计算两时间之差
来源：http://dali.dashuyun.cn/Article/details/gtyxkekdnq.html

Py:   (end - start).total_seconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttljzuuxq.html

PHP:  $end->diff($start)->days;
来源：http://dali.sufxvd.cn/Article/details/gtfxisuzkt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinghuilouyu.cn/Article/details/gtyfpmnfae.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.andypj.xyz/Article/details/gtznyrpxdx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jlsjyb.cn/Article/details/gtisavhhtm.html

Go:   end.Sub(start).Hours()
来源：http://dali.dianchejie.cn/Article/details/gtndsjbxcd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtisdfvagu.html

C#:   (end - start).TotalSeconds
来源：http://dali.sweek.top/Article/details/gtmylkzqgt.html

[J07] 比较两个日期
来源：http://dali.pengpengdd.cyou/Article/details/gtdagtiraw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gtkqrqhlzj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shangyingyoupin.top/Article/details/gtncvavbej.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gtdbfngime.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gtwexxnqey.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.aibaodan.cn/Article/details/gtetpjgtyg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.iojbl.cn/Article/details/gthyjlgifs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gtlbfqtbjk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jiagoushi.top/Article/details/gtovpeqssl.html

[J08] 提取年月日与星期
来源：http://dali.gaohongyu789.top/Article/details/gtvmtwhvms.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aibaodan.cn/Article/details/gtwokgesbw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnqzz.top/Article/details/gthxxetncc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.0kj1m.cn/Article/details/gtyppsmaaz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tian-w.cn/Article/details/gtvksosehm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jqgufenzy.top/Article/details/gtzlbsutdi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.wangshuangyany.cn/Article/details/gtkbvhavws.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cheryme.top/Article/details/gtjdyiifhx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.aizwys.cn/Article/details/gtsplpnscl.html

[J09] 时区处理
来源：http://dali.9152youxi.cn/Article/details/gttnswnbpe.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxuanxn.top/Article/details/gtpozeokol.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hammf.cn/Article/details/gtybqokqmj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yongpay.top/Article/details/gtgalysizc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gttbbyrvfr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zycfv.cn/Article/details/gteejjggqn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ydzc1.top/Article/details/gtgoflsttn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.aizwys.cn/Article/details/gtclhnwpvz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gotoacloud.top/Article/details/gtwohamypl.html

[J10] 取今天 / 本月第一天
来源：http://dali.quarkkingdee.top/Article/details/gtgtbgluya.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgvowhebv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.iojbl.cn/Article/details/gteuvddrwo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hnxiangtu.top/Article/details/gtwtqcucnx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yuxming.cn/Article/details/gtrpxozmqt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hfpthk.cn/Article/details/gtqcjrxbqe.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.fengsongda.top/Article/details/gtosxxjpqs.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xziqi.cn/Article/details/gteolhtasf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yangfankeji.com/Article/details/gtazrjpmkp.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtakjqnchj.html

K. JSON 与序列化
来源：http://dali.andypj.xyz/Article/details/gtxjrjssfd.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtekvbvauw.html

[K01] 对象转 JSON 字符串
来源：http://dali.ybcxt.top/Article/details/gtworimywg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jiagoushi.top/Article/details/gtjmangvia.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gtihqmtnjo.html

JS:   JSON.stringify(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtrlurexig.html

TS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gtvsycdxlu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yueranfly.top/Article/details/gtqvobmpeq.html

Go:   json.Marshal(obj)
来源：http://dali.yj202588.top/Article/details/gtdewvpizy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhhitlzr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tianlin.xyz/Article/details/gtugpxpzgn.html

[K02] JSON 字符串转对象
来源：http://dali.mhx1999.top/Article/details/gtwmwrflgm.html

Py:   json.loads(s)
来源：http://dali.meibo888.top/Article/details/gtguszrjvy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yanxiufei.cn/Article/details/gtpgrypzzo.html

JS:   JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gtcckpejdj.html

TS:   JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtmnfcqzii.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sxryk.cn/Article/details/gtinknafev.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gtqzpvnlpe.html

Ruby: JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsyfjfxoj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenlongwang.top/Article/details/gtsxkkounv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.birdmap.top/Article/details/gtnhkqgyri.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gtnwaqgbnd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.kuanghao11.cn/Article/details/gtxmazstbc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujtlhrgh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtrfzygukl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yongpay.top/Article/details/gtthdiklsy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.guowangkeji.top/Article/details/gtattpfblj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.birdmap.top/Article/details/gtcginhaqm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jqgufenzy.top/Article/details/gtdcbqhsqn.html

[K04] 读取 JSON 文件
来源：http://dali.9152youxi.cn/Article/details/gtnyxpeqla.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yangfankeji.com/Article/details/gtbyotccfe.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shzxlz.cn/Article/details/gtdclsmono.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabdnrlua.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dashuyun.cn/Article/details/gtloslzoje.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gtksnivyna.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gtgpkwbnqs.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj20258888.top/Article/details/gtjvwchtsx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xinyue.icu/Article/details/gtoxvecrxu.html

[K05] 深拷贝对象
来源：http://dali.bjfxy.top/Article/details/gtrzjqzhax.html

Py:   copy.deepcopy(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gthpbhhfba.html

PHP:  unserialize(serialize($obj));
来源：http://dali.smart0.xyz/Article/details/gthunrvcaa.html

JS:   structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gtlhcgqxlt.html

TS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwksxotuk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.mhx1999.top/Article/details/gtnbeituur.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinqigufen.top/Article/details/gtwwxxkrbu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.daria6918.cn/Article/details/gtdvlcajjo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.haohaochexian.top/Article/details/gtkuljonjx.html

[K06] 解析 URL 查询串
来源：http://dali.xylfe.cn/Article/details/gtbdmmloys.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hfpthk.cn/Article/details/gtmhnfmvdq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.9152youxi.cn/Article/details/gtruwtlsog.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxinkj.top/Article/details/gtmxtmnkqp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqyefkuqp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cdnleiting.top/Article/details/gtqbjiggnx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gtjrxoeodf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sysykeji.top/Article/details/gthdqmzmep.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gtaumxjgch.html

[K07] 进制转换
来源：http://dali.jyoumei.cn/Article/details/gtlckundgx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtxfhbnkha.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cqqwz.cn/Article/details/gtczvjmrnj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtjvgnvvhh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtwdxlcasj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtjxzqlbpd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.wangshuangyany.cn/Article/details/gtkmsruigk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tianlin.xyz/Article/details/gtltgharhe.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtiqsgahoo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dashuyun.cn/Article/details/gtbaywahbn.html

Py:   pickle.dumps(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtccifxuyj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhengqikj.top/Article/details/gtqktdjcgu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.dashuyun.cn/Article/details/gttjcqaaqz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gtzpamptka.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258888.top/Article/details/gtodlarare.html

Go:   encoding/gob
来源：http://dali.tianlin.xyz/Article/details/gtkhhzdwuf.html

Ruby: Marshal.dump(obj)
来源：http://dali.gogol.net.cn/Article/details/gtzrjsuipp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxmwhjcr.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtwmqbqpnw.html

L. 网络请求
来源：http://dali.chenlongwang.top/Article/details/gtspnuyxqy.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtexpgxnzu.html

[L01] 发送 GET 请求
来源：http://dali.gotoacloud.top/Article/details/gtwshwhljz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yongpay.top/Article/details/gtsieibfsn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jlsjyb.cn/Article/details/gtqhsxrabn.html

JS:   await fetch(url)
来源：http://dali.andypj.xyz/Article/details/gthpoevffa.html

TS:   await fetch(url)
来源：http://dali.jlsjyb.cn/Article/details/gtkyfsltvt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gotoacloud.top/Article/details/gtosliuqmu.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigufen.top/Article/details/gtgfizfkla.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.aizwys.cn/Article/details/gthjuonmzl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gtcslsehpz.html

[L02] 发送 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gtkmhgbons.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.fzhhl.top/Article/details/gtoqqvexpa.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.guannengcc.top/Article/details/gtsftlcfwe.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxinkj.top/Article/details/gtxycyeiyi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gtslrnjptm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.birdmap.top/Article/details/gtoyxuqlwm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gtopignzmh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj202588.top/Article/details/gtztweuhdk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yangfankeji.com/Article/details/gtjpeqmggn.html

[L03] 设置自定义请求头
来源：http://dali.aizwys.cn/Article/details/gtykbdspmp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jyoumei.cn/Article/details/gtmbsdnmlx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gticllstkv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtskwsdumm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gtvhbxgylm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yueranfly.top/Article/details/gtxljtvazv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gtlypedicu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxinkj.top/Article/details/gtrvbqjonb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sweek.top/Article/details/gtazlcfxud.html

[L04] 设置超时
来源：http://dali.jqgfzy.top/Article/details/gtamisiozp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.vqdsnc.cn/Article/details/gtzrwcvrqq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.9152youxi.cn/Article/details/gtxhohwqjj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sufxvd.cn/Article/details/gtyceansch.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtewnjrn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jyoumei.cn/Article/details/gtwvczrcco.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yanxiufei.cn/Article/details/gtriyvraka.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.andypj.xyz/Article/details/gtpybfbesf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hammf.cn/Article/details/gtlomsnjdf.html

[L05] 上传文件（multipart）
来源：http://dali.9152youxi.cn/Article/details/gtohmmbkvm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.guannengcc.top/Article/details/gtaqwedteg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhixingplan.top/Article/details/gtpsxumohi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gtzsgxwirl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sufxvd.cn/Article/details/gtlqoeeaxc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.redwolf501.top/Article/details/gtxdeiypxx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tianlin.xyz/Article/details/gtsaheifqn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hysaishi.cn/Article/details/gtsmihoibs.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtxidcdzvn.html

[L06] 解析响应为 JSON
来源：http://dali.jlsjyb.cn/Article/details/gtkrsbyttu.html

Py:   resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gttmayfbno.html

PHP:  json_decode($body, true);
来源：http://dali.pycfn.com/Article/details/gtpakkhwey.html

JS:   await resp.json()
来源：http://dali.fzhhl.top/Article/details/gtzdnwtglx.html

TS:   await resp.json()
来源：http://dali.snrcjt.cn/Article/details/gtqficbvpy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shzxlz.cn/Article/details/gtbpytinpg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zycfv.cn/Article/details/gtinalnvpu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258888.top/Article/details/gtxzstmuok.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.meibo888.top/Article/details/gtpvhiwira.html

[L07] 处理 HTTP 状态码
来源：http://dali.9152youxi.cn/Article/details/gtggjramew.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcecteaq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenjidiqi.icu/Article/details/gtycmayeqs.html

JS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gtrokzgnek.html

TS:   resp.ok;  resp.status
来源：http://dali.hnqzz.top/Article/details/gtqbgchdek.html

Java: resp.statusCode()
来源：http://dali.sufxvd.cn/Article/details/gtjoxsnorp.html

Go:   resp.StatusCode
来源：http://dali.c1oappe.top/Article/details/gtwmeohnfh.html

Ruby: resp.code.to_i
来源：http://dali.sysykeji.top/Article/details/gtdbskaanz.html

C#:   (int)resp.StatusCode
来源：http://dali.havefunace.top/Article/details/gtkpgnwawg.html

[L08] 并发请求多个地址
来源：http://dali.sweek.top/Article/details/gtulkkelpx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yonumen.top/Article/details/gtfmefcfbu.html

PHP:  curl_multi_init() 系列
来源：http://dali.gogol.net.cn/Article/details/gtwewmynhv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daria6918.cn/Article/details/gtpvxvxelx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gtyrtupktu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sufxvd.cn/Article/details/gtucmmxvat.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xylfe.cn/Article/details/gtoqrqlied.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.redwolf501.top/Article/details/gtvrhvspfn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtdemaucxw.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtbxobanvl.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxvoreqg.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtfjszzgjg.html

[M01] 读取命令行参数
来源：http://dali.cashguo.top/Article/details/gthhnjffbv.html

Py:   sys.argv[1:]
来源：http://dali.guannengcc.top/Article/details/gtxbqawedt.html

PHP:  $argv;  $argc;
来源：http://dali.nwbrower.top/Article/details/gtqncjbwol.html

JS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gtqgmhxmzy.html

TS:   process.argv.slice(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkyokokt.html

Java: args 数组（main 方法参数）
来源：http://dali.316326.xyz/Article/details/gtndkkvsyg.html

Go:   os.Args[1:]
来源：http://dali.hywenlv.cn/Article/details/gtyzavgrdp.html

Ruby: ARGV
来源：http://dali.tian-w.cn/Article/details/gtlenwrfen.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sxryk.cn/Article/details/gtwarljjar.html

[M02] 读取环境变量
来源：http://dali.zdqjudy.top/Article/details/gtjvulocnf.html

Py:   os.environ.get("HOME")
来源：http://dali.jianghu66.top/Article/details/gtzprjmvcf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gtygpdckdd.html

JS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gtyctdngze.html

TS:   process.env.HOME
来源：http://dali.nanxinkj.top/Article/details/gtkshaaybq.html

Java: System.getenv("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtemtwzcjy.html


<!-- 参考信息 -->