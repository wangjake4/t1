代发 wailian999

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtveblomff.html

[I03] 提取捕获分组
来源：http://dali.xziqi.cn/Article/details/gtothhirtr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jiagoushi.top/Article/details/gtrutpxmse.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxinkj.top/Article/details/gtkgnycoul.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yuxming.cn/Article/details/gtpepianmz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tianlin.xyz/Article/details/gtawwewvws.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gogol.net.cn/Article/details/gtsbxhcald.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nwbrower.top/Article/details/gtpqbvytsg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zdqjudy.top/Article/details/gttyselddc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.guowangkeji.top/Article/details/gtjnfnasga.html

[I04] 正则替换
来源：http://dali.chenlongwang.top/Article/details/gtbbvgucdl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yangfankeji.com/Article/details/gtejxzylle.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hysaishi.cn/Article/details/gtznojicvw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gtpfaqyqnb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aizwys.cn/Article/details/gtbrtapheo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gaohongyu789.top/Article/details/gtfdrjyxcg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.c1oappe.top/Article/details/gtylqxpbfn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.wangdashe.top/Article/details/gtbngacesg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjlrnebqb.html

[I05] 按正则拆分
来源：http://dali.jlsjyb.cn/Article/details/gtzlinkqgn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtmciwzpxi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.havefunace.top/Article/details/gtsclezufe.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gtrexaybdc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gtjikiazte.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj20258.top/Article/details/gtjrescpqb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.aizwys.cn/Article/details/gtqcekbhsq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gtojzhldnq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.0kj1m.cn/Article/details/gtjbpfpqrp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sweek.top/Article/details/gtezfoecpc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtvjddwokg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuodfrrwn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gogol.net.cn/Article/details/gtdadqsdag.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhixingplan.top/Article/details/gtxaihldoc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gtnxodtlye.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.fengsongda.top/Article/details/gttmugokbt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gogol.net.cn/Article/details/gtzxrzjbow.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gtdyfwpczc.html

[I07] 忽略大小写与多行模式
来源：http://dali.wangdashe.top/Article/details/gtqpmukvcv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigfzy.top/Article/details/gtckqddkzg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hysaishi.cn/Article/details/gtaqrgneud.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xuetiantiany.cn/Article/details/gtwizukkkc.html

TS:   /error/gim
来源：http://dali.chenlongwang.top/Article/details/gttqpaapfd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.9152youxi.cn/Article/details/gtvpbnwedd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yangfankeji.com/Article/details/gtsvgtvnpq.html

Ruby: s.scan(/error/i)
来源：http://dali.fengsongda.top/Article/details/gtvdxnxgmu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xinyue.icu/Article/details/gtgxpeugtk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gaohongyu789.top/Article/details/gtpwptpzzb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cashguo.top/Article/details/gtfdwvukok.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gtczqbxept.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtemrwyhkj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ppjwa.cn/Article/details/gtkjyccmwu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gtgyvahkqk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinqigufen.top/Article/details/gtnhnamisx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gtfkuszext.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.fengsongda.top/Article/details/gtuuevzdev.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtbprlwxbf.html

J. 日期与时间
来源：http://dali.sufxvd.cn/Article/details/gtdejruosl.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtesqkdqpb.html

[J01] 获取当前时间
来源：http://dali.sxryk.cn/Article/details/gtyuslrnxc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhoulong.xyz/Article/details/gtbtjrcpzo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gtaudswrhp.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gtknrllezx.html

TS:   new Date();  Date.now()
来源：http://dali.ydzc1.top/Article/details/gtfqfmmifr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.andypj.xyz/Article/details/gtjlvulqlo.html

Go:   time.Now()
来源：http://dali.jinqigufen.top/Article/details/gtoyzfxahq.html

Ruby: Time.now
来源：http://dali.shuidangran.top/Article/details/gtuupvoptm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zdqjudy.top/Article/details/gtgugstmgg.html

[J02] 格式化输出
来源：http://dali.daria6918.cn/Article/details/gtmmohjxko.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gaohongyu789.top/Article/details/gttgdfgnbt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gtuceyuupi.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cheryme.top/Article/details/gtqzcvvmdl.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtivlxdvvh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenjidiqi.icu/Article/details/gthqzrgafb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hysaishi.cn/Article/details/gtlbidygks.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gtlksfqjos.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sufxvd.cn/Article/details/gtgxodxzgi.html

[J03] 字符串解析为日期
来源：http://dali.pycfn.com/Article/details/gtwtizpvuw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hysaishi.cn/Article/details/gtovmhssuf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.9152youxi.cn/Article/details/gtepzlzyed.html

JS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqxaryfcq.html

TS:   new Date("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtgrntyppp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtnkeuebmk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtglwqlniq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtaejjfqom.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shuidangran.top/Article/details/gtesqcivgu.html

[J04] 时间戳与日期互转
来源：http://dali.fzhhl.top/Article/details/gtzfaocwns.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.dashuyun.cn/Article/details/gttolxgbxq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jiagoushi.top/Article/details/gtiwqnuspg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shzxlz.cn/Article/details/gthehawayu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.wangshuangyany.cn/Article/details/gthypzbafh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtzhoajhtp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tianlin.xyz/Article/details/gtstjvnwqz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tian-w.cn/Article/details/gtcalydykz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ybcxt.top/Article/details/gtxqaurrmm.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhoulong.xyz/Article/details/gtbkdjtaoi.html

Py:   now + timedelta(days=7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvpeppfe.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxhjiaeh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gtwpqocqnm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gthoibysce.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yueranfly.top/Article/details/gtkeibytpm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxinkj.top/Article/details/gtscrpjdgg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.feifeiyinyue.top/Article/details/gtkfxpyurj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yonumen.top/Article/details/gtpslzupax.html

[J06] 计算两时间之差
来源：http://dali.smart0.xyz/Article/details/gtosiikbxq.html

Py:   (end - start).total_seconds()
来源：http://dali.cqqwz.cn/Article/details/gtyuuixito.html

PHP:  $end->diff($start)->days;
来源：http://dali.hnqzz.top/Article/details/gtyvxhtlpm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.birdmap.top/Article/details/gtdlndnbwg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gzhubu.top/Article/details/gtoixbyegk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sxryk.cn/Article/details/gtyonluleq.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhongyouzk.top/Article/details/gtqpfkcwlv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sysykeji.top/Article/details/gtmgurcfyk.html

C#:   (end - start).TotalSeconds
来源：http://dali.snrcjt.cn/Article/details/gtcgxtyueb.html

[J07] 比较两个日期
来源：http://dali.bjfxy.top/Article/details/gtpfpxcpns.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gtndoppllf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.kuanghao11.cn/Article/details/gtzplmrwub.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gtsipfbpgy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jianghu66.top/Article/details/gtnncfhyka.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yongpay.top/Article/details/gtrnedccsr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfgzgpyjk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gtinwenfsm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkntxsig.html

[J08] 提取年月日与星期
来源：http://dali.sufxvd.cn/Article/details/gttmtsvuhd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenzaomai.com/Article/details/gtewsxnnhy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cdnleiting.top/Article/details/gtznnmvyek.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ivvv.top/Article/details/gtjuxcbqgk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dianchejie.cn/Article/details/gtgydfjufa.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.316326.xyz/Article/details/gtwcmtgfgd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnqzz.top/Article/details/gttfxxptmb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tian-w.cn/Article/details/gtxlnyvape.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.wangdashe.top/Article/details/gtlqbawbwy.html

[J09] 时区处理
来源：http://dali.gotoacloud.top/Article/details/gtcwzqzdkg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhixingplan.top/Article/details/gtypljhuyo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dashuyun.cn/Article/details/gtesdfocfx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yangfankeji.com/Article/details/gtxtlmuoyp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gtcjvcvuuq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.smart0.xyz/Article/details/gtgthkhdqt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tian-w.cn/Article/details/gtnhlavljk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yuanzhike.top/Article/details/gtgjqlodqm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.c1oappe.top/Article/details/gtmxmszbqh.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhiwuduotai.top/Article/details/gtnchdbbkb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xinyue.icu/Article/details/gtvgeuevee.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.andypj.xyz/Article/details/gtqdqgnpph.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhoulong.xyz/Article/details/gtmzidfiga.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtjqcpxnzk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jlsjyb.cn/Article/details/gtqwfiepfj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktwotatu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.aibaodan.cn/Article/details/gtnibtqqbf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.c1oappe.top/Article/details/gtdhzvahpm.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtymihmfpn.html

K. JSON 与序列化
来源：http://dali.zhongyouzk.top/Article/details/gtoegtxber.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtkojthtqx.html

[K01] 对象转 JSON 字符串
来源：http://dali.zycfv.cn/Article/details/gtjcwoodcd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gogol.net.cn/Article/details/gtcmupyrdo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gtfxjmwzwv.html

JS:   JSON.stringify(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyujqbzkb.html

TS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gtoejivshg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cqqwz.cn/Article/details/gtsmzicybq.html

Go:   json.Marshal(obj)
来源：http://dali.c1oappe.top/Article/details/gtbysrqpkn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhengqikj.top/Article/details/gtevkeucpx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtqdbhtjos.html

[K02] JSON 字符串转对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjskgdhfv.html

Py:   json.loads(s)
来源：http://dali.xuanzx.com/Article/details/gtziyebpiu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jqgfzy.top/Article/details/gtiswgearg.html

JS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtrfkgtyyo.html

TS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gtmmssrgwn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hywenlv.cn/Article/details/gtqakighfs.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gtgxuivera.html

Ruby: JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gtkxsendzf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnqzz.top/Article/details/gtsawqjixn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.wangdashe.top/Article/details/gtfqgevnvt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cucudq.cn/Article/details/gtdoeuwyye.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhengqikj.top/Article/details/gtruziakri.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gtavioyowc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtmgtgpfmo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guannengcc.top/Article/details/gtbfxwgshl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhoulong.xyz/Article/details/gtpabtxzop.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhengqikj.top/Article/details/gttbgrhlvi.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sufxvd.cn/Article/details/gtnojuykqz.html

[K04] 读取 JSON 文件
来源：http://dali.zhixingplan.top/Article/details/gtkqnuijor.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yangfankeji.com/Article/details/gtsccgcagc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gaohongyu789.top/Article/details/gtbxxijpvx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.quarkkingdee.top/Article/details/gtljuaximi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gtwtflezdv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gtoepqdbuw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenzaomai.com/Article/details/gtogeshxoo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gtsaazuqbu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cucudq.cn/Article/details/gtodivfdks.html

[K05] 深拷贝对象
来源：http://dali.c1oappe.top/Article/details/gtxjdzkecs.html

Py:   copy.deepcopy(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtagcqqypl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xinyue.icu/Article/details/gtmtjbifbi.html

JS:   structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gtdftxvret.html

TS:   structuredClone(obj)
来源：http://dali.fengsongda.top/Article/details/gtlxzskywq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.aizwys.cn/Article/details/gtqiofyryl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.feifeiyinyue.top/Article/details/gtpatabnid.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj20258888.top/Article/details/gtusswvkqa.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.quarkkingdee.top/Article/details/gtcirvfkca.html

[K06] 解析 URL 查询串
来源：http://dali.yanxiufei.cn/Article/details/gtrqqcuqkd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.redwolf501.top/Article/details/gtlqoofqjt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gogol.net.cn/Article/details/gtqrqwnffz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gtidimeuqu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gtisfblhvj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinghuilouyu.cn/Article/details/gtmdkiufqa.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gtnwnsfmax.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gtkyubszbv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gtxbogskip.html

[K07] 进制转换
来源：http://dali.gaohongyu789.top/Article/details/gtuqblwadi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtmiktxstd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yanxiufei.cn/Article/details/gtzxvrwtuk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtighpwcsk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtidfmmlme.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtniidmjvm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.mhx1999.top/Article/details/gtlyyodtwp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sysykeji.top/Article/details/gteiyzrwsb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gttywyrqwy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yangfankeji.com/Article/details/gtgmvphvlj.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtpqikfyar.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cdnleiting.top/Article/details/gtcaacptpi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangshuangyany.cn/Article/details/gtqifafcal.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gogol.net.cn/Article/details/gtwcxuoghc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.daxiang520.top/Article/details/gtylxxmlmb.html

Go:   encoding/gob
来源：http://dali.jqgufenzy.top/Article/details/gttawsqpzh.html

Ruby: Marshal.dump(obj)
来源：http://dali.tanke756.top/Article/details/gtljqrvlsf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenlongwang.top/Article/details/gtwtmjqqod.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtbvkozzik.html

L. 网络请求
来源：http://dali.meibo888.top/Article/details/gtlrrkuajy.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtwusxiiib.html

[L01] 发送 GET 请求
来源：http://dali.yuanzhike.top/Article/details/gtborcynua.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.wangdashe.top/Article/details/gtuqehyamj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xziqi.cn/Article/details/gtliciivmx.html

JS:   await fetch(url)
来源：http://dali.jianghu66.top/Article/details/gtjkdksqwt.html

TS:   await fetch(url)
来源：http://dali.c1oappe.top/Article/details/gtheizgijd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.kuanghao11.cn/Article/details/gtchrekjue.html

Go:   resp, err := http.Get(url)
来源：http://dali.redwolf501.top/Article/details/gtrwxdgzzc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhongyouzk.top/Article/details/gtvvjwokui.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hysaishi.cn/Article/details/gthfcgoezo.html

[L02] 发送 POST JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gtztremfas.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj202588.top/Article/details/gtqviqocwg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.bjfxy.top/Article/details/gtxmtidddj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xinyue.icu/Article/details/gtjaejhjut.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtypgjfp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shuidangran.top/Article/details/gtfpgjablc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.guowangkeji.top/Article/details/gttoqbojsz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xziqi.cn/Article/details/gtvwlczjww.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jlsjyb.cn/Article/details/gtkbeiuhur.html

[L03] 设置自定义请求头
来源：http://dali.yangfankeji.com/Article/details/gtrgpyuksv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj202588.top/Article/details/gtrikzkiuz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.meibo888.top/Article/details/gtfxodcdab.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.redwolf501.top/Article/details/gtqbjnzazt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258.top/Article/details/gtqchztpqy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzczgoxid.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.redwolf501.top/Article/details/gttpupznwu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.snrcjt.cn/Article/details/gtfjklnupg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jqgufenzy.top/Article/details/gtlbzxpfju.html

[L04] 设置超时
来源：http://dali.redwolf501.top/Article/details/gtgvuaghab.html

Py:   requests.get(url, timeout=5)
来源：http://dali.haohaochexian.top/Article/details/gtgeptisls.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hammf.cn/Article/details/gtttdcshoz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jiagoushi.top/Article/details/gtywmaviwo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj202588.top/Article/details/gtbrfylbdo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.aibaodan.cn/Article/details/gthfwuxpsa.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinghuilouyu.cn/Article/details/gtludumblw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.wangdashe.top/Article/details/gtbigyrapt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gotoacloud.top/Article/details/gthfoktnra.html

[L05] 上传文件（multipart）
来源：http://dali.birdmap.top/Article/details/gtzrqiaere.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.guannengcc.top/Article/details/gteieukxnu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.0kj1m.cn/Article/details/gtlfihdzgx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zdqjudy.top/Article/details/gtmdyqbrmz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xziqi.cn/Article/details/gtgwdfcdid.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.fengsongda.top/Article/details/gtqccbusbj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gzhubu.top/Article/details/gtgrdqomnh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ivvv.top/Article/details/gtawkslydz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ydzc1.top/Article/details/gtinmfjjvz.html

[L06] 解析响应为 JSON
来源：http://dali.ppjwa.cn/Article/details/gtlfcxmbii.html

Py:   resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gtybrphxbi.html

PHP:  json_decode($body, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtytxuowyv.html

JS:   await resp.json()
来源：http://dali.haohaochexian.top/Article/details/gtucphtxxk.html

TS:   await resp.json()
来源：http://dali.yj20258888.top/Article/details/gtrrcungyq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtyfbulbui.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shangyingyoupin.top/Article/details/gtaphpsffx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenjidiqi.icu/Article/details/gtjinnfuaf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yueranfly.top/Article/details/gtlaebseaf.html

[L07] 处理 HTTP 状态码
来源：http://dali.ppjwa.cn/Article/details/gtoceiltbd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gtyqluxpoo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.pycfn.com/Article/details/gtpmmmcefj.html

JS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gtuxvaiowq.html

TS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gtvrorvryh.html

Java: resp.statusCode()
来源：http://dali.cheryme.top/Article/details/gtkcaasxay.html

Go:   resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gtafggiznx.html

Ruby: resp.code.to_i
来源：http://dali.sufxvd.cn/Article/details/gtudkglkwj.html

C#:   (int)resp.StatusCode
来源：http://dali.wangdashe.top/Article/details/gtnbburqiy.html

[L08] 并发请求多个地址
来源：http://dali.zhengqikj.top/Article/details/gtktnlzpse.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.fzhhl.top/Article/details/gtrudqdmqb.html

PHP:  curl_multi_init() 系列
来源：http://dali.cdnleiting.top/Article/details/gtizezxynf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gteejmtkxx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gthqnfcqsg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zycfv.cn/Article/details/gtqjmvktbe.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.guowangkeji.top/Article/details/gtodjvgkco.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sysykeji.top/Article/details/gtzebjonqu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dianchejie.cn/Article/details/gtrfhvezxn.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtzraefdrb.html

M. 命令行 / 进程 / 环境
来源：http://dali.wangshuangyany.cn/Article/details/gttviegdzi.html


<!-- 参考信息 -->