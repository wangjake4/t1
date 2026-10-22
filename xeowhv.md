代发 wailian999

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ybcxt.top/Article/details/gtddzijiav.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yanxiufei.cn/Article/details/gtjkfhydpr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.aizwys.cn/Article/details/gtgecxpkmp.html

[I05] 按正则拆分
来源：http://dali.xziqi.cn/Article/details/gteglnrsne.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hysaishi.cn/Article/details/gtpvaqncyq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.daxiang520.top/Article/details/gtkollldup.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gtrxfcxxjv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtlpggmykq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yangfankeji.com/Article/details/gtaqqkmolt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gthuecrwns.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gtfrbpricc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.mhx1999.top/Article/details/gtfdriwfdf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.aizwys.cn/Article/details/gtagkkwtdj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gtatjuyvko.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.c1oappe.top/Article/details/gtekjoilwa.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daxiang520.top/Article/details/gtfdlsqbda.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ydzc1.top/Article/details/gtqsyqbfdz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gtocgdykbk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cheryme.top/Article/details/gtipackkvo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.smart0.xyz/Article/details/gtvyzdapcj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tanke756.top/Article/details/gtshyuhfip.html

[I07] 忽略大小写与多行模式
来源：http://dali.xuanzx.com/Article/details/gtvpqzyvfu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gogol.net.cn/Article/details/gtdycipqlv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yueranfly.top/Article/details/gtknriixyd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gaohongyu789.top/Article/details/gtlnpnirqu.html

TS:   /error/gim
来源：http://dali.jyoumei.cn/Article/details/gtaqrnuzbp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jqgufenzy.top/Article/details/gtwqrvtkjr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jianghu66.top/Article/details/gtgahgpbor.html

Ruby: s.scan(/error/i)
来源：http://dali.redwolf501.top/Article/details/gtubtijgcd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnqzz.top/Article/details/gtnvkhdsmt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxinkj.top/Article/details/gthaambzqy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nwbrower.top/Article/details/gtzgnfzjfb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zdqjudy.top/Article/details/gtpjkzipqm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yongpay.top/Article/details/gtigjsxdsl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tianlin.xyz/Article/details/gtwbtukgkf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.c1oappe.top/Article/details/gtescnyloj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shzxlz.cn/Article/details/gtjwbdixjx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yangfankeji.com/Article/details/gtmubmjurv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shangyingyoupin.top/Article/details/gtuvpxouvl.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtoygrqmby.html

J. 日期与时间
来源：http://dali.zhengqikj.top/Article/details/gtlzduaxft.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtiwfjcjsi.html

[J01] 获取当前时间
来源：http://dali.quarkkingdee.top/Article/details/gtknwrokzf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.guannengcc.top/Article/details/gtnmbsfzei.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nwbrower.top/Article/details/gtozeqxjta.html

JS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gtapwanlrn.html

TS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gtphftowit.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.andypj.xyz/Article/details/gtvlihtcok.html

Go:   time.Now()
来源：http://dali.jinqigufen.top/Article/details/gtexkfvbps.html

Ruby: Time.now
来源：http://dali.hongshengwenyu.top/Article/details/gtxtrnpxzs.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.birdmap.top/Article/details/gtplqqoxxb.html

[J02] 格式化输出
来源：http://dali.hysaishi.cn/Article/details/gtjfpluhql.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangshuangyany.cn/Article/details/gtxwjzknoj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.wangshuangyany.cn/Article/details/gtfzdvpliw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.pycfn.com/Article/details/gtlrdphfzt.html

TS:   d.toISOString()
来源：http://dali.jyoumei.cn/Article/details/gtxgbyyqcn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.iojbl.cn/Article/details/gtehgyuizz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cheryme.top/Article/details/gtverxdfln.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sweek.top/Article/details/gtfgtonbcq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jqgufenzy.top/Article/details/gthztmllzr.html

[J03] 字符串解析为日期
来源：http://dali.guowangkeji.top/Article/details/gtsehgadls.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigufen.top/Article/details/gtvnozqamo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvwsqrqbh.html

JS:   new Date("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtqkwjntjy.html

TS:   new Date("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtjmgyrgrb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtyiebgtjl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtwnmmxxvl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtfoykashm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuetiantiany.cn/Article/details/gtixpbadje.html

[J04] 时间戳与日期互转
来源：http://dali.hammf.cn/Article/details/gtxmfhzdit.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.birdmap.top/Article/details/gtxnqqzmnh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.9152youxi.cn/Article/details/gtmfczpant.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.feifeiyinyue.top/Article/details/gtwvbigyws.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yonumen.top/Article/details/gtlkaoqtqw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shzxlz.cn/Article/details/gtugyzkwct.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.havefunace.top/Article/details/gtwrpajmem.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tian-w.cn/Article/details/gtmgtvcosb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtmljjhwep.html

[J05] 时间加减（加 7 天）
来源：http://dali.yongpay.top/Article/details/gtoazjijff.html

Py:   now + timedelta(days=7)
来源：http://dali.yj202588.top/Article/details/gtppqrvpup.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cqqwz.cn/Article/details/gtefdjmuln.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sweek.top/Article/details/gtwxwfpgpp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhoulong.xyz/Article/details/gtimlmaclk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.316326.xyz/Article/details/gtjlrxtesx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sufxvd.cn/Article/details/gtwgeimjbj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tianlin.xyz/Article/details/gtmzturgco.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cdnleiting.top/Article/details/gtcqwpyznf.html

[J06] 计算两时间之差
来源：http://dali.yongpay.top/Article/details/gtkeyobvof.html

Py:   (end - start).total_seconds()
来源：http://dali.ehwqpu.com/Article/details/gtljrvfjul.html

PHP:  $end->diff($start)->days;
来源：http://dali.tianlin.xyz/Article/details/gthupjchle.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yueranfly.top/Article/details/gtvufsjdgu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hysaishi.cn/Article/details/gtwuiawmsk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.kuanghao11.cn/Article/details/gtqxftsjze.html

Go:   end.Sub(start).Hours()
来源：http://dali.ydzc1.top/Article/details/gtgwuqjxeq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.bjfxy.top/Article/details/gtpftosful.html

C#:   (end - start).TotalSeconds
来源：http://dali.hnxiangtu.top/Article/details/gtarigjatc.html

[J07] 比较两个日期
来源：http://dali.yuanzhike.top/Article/details/gtzdlvoxlj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtnfqfaiyx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sufxvd.cn/Article/details/gtcmlfztzm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gtpyvmwody.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xinyue.icu/Article/details/gthetamrby.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ehwqpu.com/Article/details/gtnsssstip.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yanxiufei.cn/Article/details/gtfyoxtfkr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.tianlin.xyz/Article/details/gtyizudofv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtgbgxdjkh.html

[J08] 提取年月日与星期
来源：http://dali.xinyue.icu/Article/details/gtiegfwnmo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpflpydjr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sufxvd.cn/Article/details/gtrqbmpjsu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hysaishi.cn/Article/details/gttstgknxy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yuxming.cn/Article/details/gtwubcxftz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cucudq.cn/Article/details/gtczislobc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmznhwcxr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nanxuanxn.top/Article/details/gtzzcgciwv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sufxvd.cn/Article/details/gtccpstecs.html

[J09] 时区处理
来源：http://dali.zhengqikj.top/Article/details/gtswcengtj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ehwqpu.com/Article/details/gtvibwcnda.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hongshengwenyu.top/Article/details/gtqxigitmd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gtizrqnrpd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gtuksxdgtx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nwbrower.top/Article/details/gtazcdcosg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj202588.top/Article/details/gtwzmrbnop.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.havefunace.top/Article/details/gtztkmqcee.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ybcxt.top/Article/details/gthahlqutg.html

[J10] 取今天 / 本月第一天
来源：http://dali.ivvv.top/Article/details/gtmokgobml.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jqgfzy.top/Article/details/gthxmmglvq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xylfe.cn/Article/details/gttpjzoexh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.kuanghao11.cn/Article/details/gttddtzzfi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hfpthk.cn/Article/details/gtqjldrqey.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dashuyun.cn/Article/details/gtobzafhyr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.c1oappe.top/Article/details/gtqfwbqtle.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cheryme.top/Article/details/gttaflvfre.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yuxming.cn/Article/details/gtdncekgqr.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtivmwgiji.html

K. JSON 与序列化
来源：http://dali.tian-w.cn/Article/details/gtebwlcpoy.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtzdidysav.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuanzx.com/Article/details/gtxxzbllrf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.wangdashe.top/Article/details/gtpzshaaey.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhoulong.xyz/Article/details/gtuctjmyus.html

JS:   JSON.stringify(obj)
来源：http://dali.mhx1999.top/Article/details/gtelmggmuk.html

TS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gthecdvztx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinghuilouyu.cn/Article/details/gtkftnfped.html

Go:   json.Marshal(obj)
来源：http://dali.yuanzhike.top/Article/details/gtnowsydjw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sysykeji.top/Article/details/gtwgkjzaey.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.316326.xyz/Article/details/gtpvfwfgdn.html

[K02] JSON 字符串转对象
来源：http://dali.jqgufenzy.top/Article/details/gtvykybkgg.html

Py:   json.loads(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthortitrx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.redwolf501.top/Article/details/gtqqlmncvp.html

JS:   JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gtvonchvlj.html

TS:   JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbyqvcuyx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yvedp.cn/Article/details/gtgaavvfcf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.iojbl.cn/Article/details/gtfavrvfku.html

Ruby: JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gtphjrigkj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.c1oappe.top/Article/details/gtjyfyshvr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinqigfzy.top/Article/details/gtrcvwhugp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.9152youxi.cn/Article/details/gtmkmremtx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.guannengcc.top/Article/details/gttlhhoumr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gtpuwtrega.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cashguo.top/Article/details/gtypnunuvq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtytkjdgvd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdmtfmkcg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sufxvd.cn/Article/details/gtsjjatauy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxuanxn.top/Article/details/gtftnfnjkw.html

[K04] 读取 JSON 文件
来源：http://dali.aizwys.cn/Article/details/gtuyjuhkvz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.316326.xyz/Article/details/gthdyiwzux.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.bjfxy.top/Article/details/gtlnuaaehx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sysykeji.top/Article/details/gtrurabiya.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdzdknkku.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.aibaodan.cn/Article/details/gtdgpifhrm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xziqi.cn/Article/details/gtmuvrgmgr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtwyhdlxqb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjuxifmh.html

[K05] 深拷贝对象
来源：http://dali.zhoulong.xyz/Article/details/gtlisjnfac.html

Py:   copy.deepcopy(obj)
来源：http://dali.pycfn.com/Article/details/gtxgpxmogg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfziarqu.html

JS:   structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpbixxwd.html

TS:   structuredClone(obj)
来源：http://dali.aibaodan.cn/Article/details/gtsiaafdor.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.smart0.xyz/Article/details/gtgmddampz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenjidiqi.icu/Article/details/gtphgjfqds.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hongshengwenyu.top/Article/details/gtnndivciq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcepnqzox.html

[K06] 解析 URL 查询串
来源：http://dali.chenjidiqi.icu/Article/details/gtiydtjset.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinghuilouyu.cn/Article/details/gtghdmzyso.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.svipenyu.cn/Article/details/gtxnxsdhsk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.kuanghao11.cn/Article/details/gtcmvvyxzj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gtiununfou.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shzxlz.cn/Article/details/gtcbcqqfzl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gtissxmrwl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gtnrsdgfyx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gttoccxvju.html

[K07] 进制转换
来源：http://dali.tanke756.top/Article/details/gtganazfeb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtfvewozzw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gogol.net.cn/Article/details/gtdrwyssvo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtukmmosom.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtecybhyxe.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfgomggwi.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cucudq.cn/Article/details/gthvdngark.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cashguo.top/Article/details/gtuopwstqx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphzotede.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jyoumei.cn/Article/details/gtngogyyou.html

Py:   pickle.dumps(obj)
来源：http://dali.hysaishi.cn/Article/details/gtwrfaygnx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hfpthk.cn/Article/details/gtxkubsabq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhoulong.xyz/Article/details/gtjfhlikar.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gtmyboipbu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yvedp.cn/Article/details/gtajyyebxk.html

Go:   encoding/gob
来源：http://dali.snrcjt.cn/Article/details/gtahhcyyog.html

Ruby: Marshal.dump(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsenuwtrv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbfqoxbtd.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtjsfgiics.html

L. 网络请求
来源：http://dali.tianlin.xyz/Article/details/gtdeecmwyj.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtanbakonf.html

[L01] 发送 GET 请求
来源：http://dali.jlsjyb.cn/Article/details/gtfdabhewg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yonumen.top/Article/details/gtrdfgrrsu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shanyushiyangtech.top/Article/details/gtqxombyxl.html

JS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtxzrkjckz.html

TS:   await fetch(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtsmmmevuj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ybcxt.top/Article/details/gtatmnbgms.html

Go:   resp, err := http.Get(url)
来源：http://dali.c1oappe.top/Article/details/gtfiiqbaht.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhiwuduotai.top/Article/details/gtstqwjbzg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinqigfzy.top/Article/details/gtvipmxyvv.html

[L02] 发送 POST JSON
来源：http://dali.sysykeji.top/Article/details/gtkacwdujp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.iojbl.cn/Article/details/gtziwpfaxh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xuanzx.com/Article/details/gtwlfbofuz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sweek.top/Article/details/gtrtewvwzk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yvedp.cn/Article/details/gtiiczgpqr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gaohongyu789.top/Article/details/gtcuaihpce.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cqqwz.cn/Article/details/gtsdexjbfk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigufen.top/Article/details/gtqarhfvdc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jiagoushi.top/Article/details/gtrxfvkyvx.html

[L03] 设置自定义请求头
来源：http://dali.gaohongyu789.top/Article/details/gtzumhgzgz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.fzhhl.top/Article/details/gtnaampobn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cashguo.top/Article/details/gtufstwhxa.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.smart0.xyz/Article/details/gtufrtwkfz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhixingplan.top/Article/details/gtuesdjcaw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrgmiftfo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.fzhhl.top/Article/details/gtmpoowjbz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cashguo.top/Article/details/gtepdntiku.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jiagoushi.top/Article/details/gtwogettzr.html

[L04] 设置超时
来源：http://dali.c1oappe.top/Article/details/gtmpmpqsac.html

Py:   requests.get(url, timeout=5)
来源：http://dali.svipenyu.cn/Article/details/gtsomlvacm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hfpthk.cn/Article/details/gtjsrlbnap.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pengpengdd.cyou/Article/details/gtpuxybojc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258.top/Article/details/gtvvvlbpah.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ydzc1.top/Article/details/gtkaanraza.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cheryme.top/Article/details/gtvcvbhtch.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ivvv.top/Article/details/gtqcvtqomd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tanke756.top/Article/details/gtsxhkdmlm.html

[L05] 上传文件（multipart）
来源：http://dali.snrcjt.cn/Article/details/gtgyvyqbys.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj20258.top/Article/details/gtzlnpggsz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.mhx1999.top/Article/details/gtpnffndjp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gtiipeglwx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuanzhike.top/Article/details/gtjjbkeocv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nanxinkj.top/Article/details/gtzzhkubyo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hywenlv.cn/Article/details/gtgcaycpyr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.guowangkeji.top/Article/details/gtfuwkirac.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtvoasbsmg.html

[L06] 解析响应为 JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjvrcsvq.html

Py:   resp.json()
来源：http://dali.xuanzx.com/Article/details/gtnzzzsxfw.html

PHP:  json_decode($body, true);
来源：http://dali.cashguo.top/Article/details/gtpfksbnna.html

JS:   await resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gtllftpnuh.html

TS:   await resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimpsgysp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.aizwys.cn/Article/details/gtzutbqkge.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxinkj.top/Article/details/gtbwtzwnto.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxuanxn.top/Article/details/gtdyjdraso.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gtbkzbefmx.html

[L07] 处理 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gttbgnppiw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zdqjudy.top/Article/details/gtnhslewub.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhengqikj.top/Article/details/gtoygkgbkw.html

JS:   resp.ok;  resp.status
来源：http://dali.cheryme.top/Article/details/gtwqxukals.html

TS:   resp.ok;  resp.status
来源：http://dali.316326.xyz/Article/details/gtvzocxosp.html

Java: resp.statusCode()
来源：http://dali.ybcxt.top/Article/details/gtgrnycgtj.html

Go:   resp.StatusCode
来源：http://dali.yj20258888.top/Article/details/gtyzetngti.html

Ruby: resp.code.to_i
来源：http://dali.shzxlz.cn/Article/details/gtyolvfcil.html

C#:   (int)resp.StatusCode
来源：http://dali.daria6918.cn/Article/details/gttazvxetw.html

[L08] 并发请求多个地址
来源：http://dali.yuanzhike.top/Article/details/gtuwryzkuz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.meibo888.top/Article/details/gttqffiapw.html

PHP:  curl_multi_init() 系列
来源：http://dali.xuetiantiany.cn/Article/details/gtbdtrvkjn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gtlyayynlw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gtouaebwnn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.quarkkingdee.top/Article/details/gtlhwlbovr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shuidangran.top/Article/details/gttyssstpg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fzhhl.top/Article/details/gtwfworogb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhengqikj.top/Article/details/gtiyozgitj.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykgifnfo.html

M. 命令行 / 进程 / 环境
来源：http://dali.wangdashe.top/Article/details/gtvvnpmktt.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtrqlrtcvf.html

[M01] 读取命令行参数
来源：http://dali.c1oappe.top/Article/details/gtnigqcyof.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gthdxbfgfl.html

PHP:  $argv;  $argc;
来源：http://dali.chenjidiqi.icu/Article/details/gtswwnloss.html

JS:   process.argv.slice(2)
来源：http://dali.redwolf501.top/Article/details/gthxzrapla.html

TS:   process.argv.slice(2)
来源：http://dali.xuetiantiany.cn/Article/details/gtjfvigedu.html

Java: args 数组（main 方法参数）
来源：http://dali.guowangkeji.top/Article/details/gtkimpwwka.html

Go:   os.Args[1:]
来源：http://dali.sysykeji.top/Article/details/gtfjpphpbb.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gtljcjphdo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gtwdrbdvmc.html

[M02] 读取环境变量
来源：http://dali.nwbrower.top/Article/details/gtdixgpoyx.html

Py:   os.environ.get("HOME")
来源：http://dali.birdmap.top/Article/details/gtsthzsacr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.birdmap.top/Article/details/gtymgdinbn.html

JS:   process.env.HOME
来源：http://dali.chenlongwang.top/Article/details/gtwmueclju.html

TS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gtprmwriqj.html

Java: System.getenv("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtsrarxlig.html


<!-- 参考信息 -->