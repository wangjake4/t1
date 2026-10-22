代发 wailian999

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yueranfly.top/Article/details/gtrfvvuuhz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xinyue.icu/Article/details/gtoyiyirmz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxuanxn.top/Article/details/gttfwmfyln.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xylfe.cn/Article/details/gtuchkbwql.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pycfn.com/Article/details/gtcntuksox.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cheryme.top/Article/details/gtgxjmbjzn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nanxuanxn.top/Article/details/gtjckffxdo.html

[I05] 按正则拆分
来源：http://dali.zdqjudy.top/Article/details/gtwzaqypjb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ivvv.top/Article/details/gtcqhbrfjw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtfqflkdyf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gtmoijgfrc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gtxljppsec.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnqzz.top/Article/details/gtrdzmvsoc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gtdxpsvmgt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gtapvxnqxo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ppjwa.cn/Article/details/gtjgooksgy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tianlin.xyz/Article/details/gtqnbstkqn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxnprtqsu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhiwuduotai.top/Article/details/gttwijqinj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dianchejie.cn/Article/details/gtmicoflva.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gtjbjtdkxp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gtvbdjrxbi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cashguo.top/Article/details/gtnxscxpet.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hammf.cn/Article/details/gtmenbxggl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gtdbrdnshs.html

[I07] 忽略大小写与多行模式
来源：http://dali.xziqi.cn/Article/details/gtbhajvvrd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sxryk.cn/Article/details/gtwvlodwff.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tanke756.top/Article/details/gtjjgweytu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.0kj1m.cn/Article/details/gtslzhmthw.html

TS:   /error/gim
来源：http://dali.hfpthk.cn/Article/details/gtcctxcfkr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinqigufen.top/Article/details/gtgvaarqge.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttbqawdqm.html

Ruby: s.scan(/error/i)
来源：http://dali.wangdashe.top/Article/details/gtjamhvbvg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jyoumei.cn/Article/details/gtsfhtlfdg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ydzc1.top/Article/details/gtuktnqvkf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cdnleiting.top/Article/details/gtnysemrcu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xylfe.cn/Article/details/gtomyanvlo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yongpay.top/Article/details/gtgnjjnbyp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnqzz.top/Article/details/gtwmuiwfus.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gtomdsbpmi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.svipenyu.cn/Article/details/gtngflyjib.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yuxming.cn/Article/details/gtctwdjbaq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nanxinkj.top/Article/details/gtwvnkaogh.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoemhapbi.html

J. 日期与时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtoybyerbh.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtyhypxwjq.html

[J01] 获取当前时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtvwlaofte.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sysykeji.top/Article/details/gtlcpssnzz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gtikohpsaq.html

JS:   new Date();  Date.now()
来源：http://dali.sysykeji.top/Article/details/gtqfyiibpr.html

TS:   new Date();  Date.now()
来源：http://dali.shangyingyoupin.top/Article/details/gtmzbagqfl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yueranfly.top/Article/details/gtbeqzzdrh.html

Go:   time.Now()
来源：http://dali.jiagoushi.top/Article/details/gtuczpjmgh.html

Ruby: Time.now
来源：http://dali.shangyingyoupin.top/Article/details/gtqznrsvca.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xinyue.icu/Article/details/gtohpmboqk.html

[J02] 格式化输出
来源：http://dali.yuxming.cn/Article/details/gtrwzcozoa.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ybcxt.top/Article/details/gtzwimtkde.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hysaishi.cn/Article/details/gtpuctkpot.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shzxlz.cn/Article/details/gteeaginvi.html

TS:   d.toISOString()
来源：http://dali.fzhhl.top/Article/details/gthtettnvd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zycfv.cn/Article/details/gtrncuomef.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hnxiangtu.top/Article/details/gtieupojdj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xylfe.cn/Article/details/gtfoxekspi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenzaomai.com/Article/details/gtxjkgfvbo.html

[J03] 字符串解析为日期
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdkgahnke.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.haohaochexian.top/Article/details/gtzdnawdqd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.aibaodan.cn/Article/details/gtruvztygw.html

JS:   new Date("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtjfapiyem.html

TS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtmtaodwed.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnuntbxa.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtlglkwpsb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtkyavdroc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhijiandao.cn/Article/details/gtkjbnhdpj.html

[J04] 时间戳与日期互转
来源：http://dali.sweek.top/Article/details/gthiaokglu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.9152youxi.cn/Article/details/gtzufjmbzz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.haohaochexian.top/Article/details/gtwxscigkn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenzaomai.com/Article/details/gtqkmlgcfx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigufen.top/Article/details/gtwflxronl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtosiijhuu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sxryk.cn/Article/details/gtqpqmffbj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yuanzhike.top/Article/details/gtwjlbtgwu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtxvhboxcm.html

[J05] 时间加减（加 7 天）
来源：http://dali.pengpengdd.cyou/Article/details/gtadoybttq.html

Py:   now + timedelta(days=7)
来源：http://dali.jinqigfzy.top/Article/details/gtuyvgzufa.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.pycfn.com/Article/details/gtssxxzxhy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gttyoxzwea.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cashguo.top/Article/details/gtrgegjrvo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sysykeji.top/Article/details/gthnrvfyyi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.haohaochexian.top/Article/details/gtjdtiowzv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nanxinkj.top/Article/details/gtenanhdan.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dashuyun.cn/Article/details/gtnaittorh.html

[J06] 计算两时间之差
来源：http://dali.daxiang520.top/Article/details/gtdfjnjwfh.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxuanxn.top/Article/details/gtokgdjesg.html

PHP:  $end->diff($start)->days;
来源：http://dali.hywenlv.cn/Article/details/gtmvjojdmz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tian-w.cn/Article/details/gtbnnrdhqh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.0kj1m.cn/Article/details/gthxajmibz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dianchejie.cn/Article/details/gtgbhzascm.html

Go:   end.Sub(start).Hours()
来源：http://dali.hnxiangtu.top/Article/details/gtwnrngsyr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yonumen.top/Article/details/gthurwbedf.html

C#:   (end - start).TotalSeconds
来源：http://dali.gogol.net.cn/Article/details/gtnumtzmwl.html

[J07] 比较两个日期
来源：http://dali.andypj.xyz/Article/details/gtspmbgfhu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gtujcypvku.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sxryk.cn/Article/details/gtfdymrgsw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxinkj.top/Article/details/gttpptxkhl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangtech.top/Article/details/gttzehqwrx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj20258.top/Article/details/gtxvkuviam.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.redwolf501.top/Article/details/gtvnfpnzyd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gtmmjaepyn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtmvoeembz.html

[J08] 提取年月日与星期
来源：http://dali.bjfxy.top/Article/details/gthpggnmuk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.pengpengdd.cyou/Article/details/gtixynrpvv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ppjwa.cn/Article/details/gtdfdvbzkh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shangyingyoupin.top/Article/details/gtmyyjmdxk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xylfe.cn/Article/details/gtlhtejqoj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.pycfn.com/Article/details/gtcybfrnoz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yangfankeji.com/Article/details/gtbntlanqy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhixingplan.top/Article/details/gtmchympnp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gogol.net.cn/Article/details/gtafkqfhyu.html

[J09] 时区处理
来源：http://dali.daria6918.cn/Article/details/gtsagluyhy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.guowangkeji.top/Article/details/gtvejacbtx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shuidangran.top/Article/details/gtmaojxyzl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhengqikj.top/Article/details/gtrldpwwrt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gtscqhcofm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.pengpengdd.cyou/Article/details/gtlfmlhboq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sysykeji.top/Article/details/gtdtprupmf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenjidiqi.icu/Article/details/gtmdrbnusw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.redwolf501.top/Article/details/gtyqhgwfoh.html

[J10] 取今天 / 本月第一天
来源：http://dali.xylfe.cn/Article/details/gtojuodvvm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xuanzx.com/Article/details/gtpxafljyp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.andypj.xyz/Article/details/gtcxcrmlpl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hnqzz.top/Article/details/gtefmbbndc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fzhhl.top/Article/details/gtqkqfpduk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cucudq.cn/Article/details/gthslskrvv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jqgufenzy.top/Article/details/gthvwilaez.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sysykeji.top/Article/details/gtdkgzkzlz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yonumen.top/Article/details/gtogfjhihn.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gteoqkcbyp.html

K. JSON 与序列化
来源：http://dali.pycfn.com/Article/details/gtqkwpipgh.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtgzytflss.html

[K01] 对象转 JSON 字符串
来源：http://dali.hongshengwenyu.top/Article/details/gthjlxlowz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yuxming.cn/Article/details/gtqayxgvwy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yvedp.cn/Article/details/gtcuuhhdni.html

JS:   JSON.stringify(obj)
来源：http://dali.fzhhl.top/Article/details/gttgivabhz.html

TS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gtftiayffb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ybcxt.top/Article/details/gtdewjrydm.html

Go:   json.Marshal(obj)
来源：http://dali.dianchejie.cn/Article/details/gtnsbxyfra.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jyoumei.cn/Article/details/gtfttcyjmt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hfpthk.cn/Article/details/gtdbjrayii.html

[K02] JSON 字符串转对象
来源：http://dali.hongshengwenyu.top/Article/details/gtmcqiutcf.html

Py:   json.loads(s)
来源：http://dali.cashguo.top/Article/details/gthospapef.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.9152youxi.cn/Article/details/gtrikgpmpd.html

JS:   JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gtvlfrrjyu.html

TS:   JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gtodklapal.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cheryme.top/Article/details/gtqceprvhp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.bjfxy.top/Article/details/gtiufyqatp.html

Ruby: JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gtkhaxnahg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shuidangran.top/Article/details/gtqcfcqayy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhiwuduotai.top/Article/details/gtevhkixte.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfmylsfcp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yvedp.cn/Article/details/gtinzlgrap.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gteadskerm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtgmbhigtp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.0kj1m.cn/Article/details/gtbkljlqzd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.redwolf501.top/Article/details/gtwgjzmvjb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtscladbvb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ybcxt.top/Article/details/gttwsiujxy.html

[K04] 读取 JSON 文件
来源：http://dali.yuxming.cn/Article/details/gtpuvmmhoa.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tianlin.xyz/Article/details/gtmwuwbebh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jqgfzy.top/Article/details/gtgydtgair.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gtuuzsqmrj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xylfe.cn/Article/details/gtomrwofkj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.316326.xyz/Article/details/gtctcmlyfh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhoulong.xyz/Article/details/gtpyhtnhze.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtwqkryo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.birdmap.top/Article/details/gtzzdrdztf.html

[K05] 深拷贝对象
来源：http://dali.tian-w.cn/Article/details/gtxyvgvozj.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtmlipavoa.html

PHP:  unserialize(serialize($obj));
来源：http://dali.guannengcc.top/Article/details/gtnmpqlcsc.html

JS:   structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gtqfzknrqn.html

TS:   structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gtuqpjjgkf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhengqikj.top/Article/details/gtagzjkqnz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hfpthk.cn/Article/details/gtmgomdbqj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zdqjudy.top/Article/details/gtfrjbgglu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.quarkkingdee.top/Article/details/gtbvtobyos.html

[K06] 解析 URL 查询串
来源：http://dali.cashguo.top/Article/details/gtgvedpuzq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gtamlaglhs.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.mhx1999.top/Article/details/gtvfzrvhgb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hfpthk.cn/Article/details/gtaxucrwpw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ydzc1.top/Article/details/gtfktaynyo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.havefunace.top/Article/details/gtqewgufxv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gtkecpyfpa.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtuahgmjtv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gtvjxeiuor.html

[K07] 进制转换
来源：http://dali.jinqigfzy.top/Article/details/gtjenxsdcq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvbeykjz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gtrusnrwwt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtbytcikck.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtdrmcddlk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtwfcqifzv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.bjfxy.top/Article/details/gtygackzus.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.birdmap.top/Article/details/gtrmvvjrgb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtmufzvorl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.vqdsnc.cn/Article/details/gtulsdaabq.html

Py:   pickle.dumps(obj)
来源：http://dali.hywenlv.cn/Article/details/gtlvnlllmi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sweek.top/Article/details/gtmiicjudc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sufxvd.cn/Article/details/gtfwyhremo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdoaxtqcb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.kuanghao11.cn/Article/details/gtvztsibkg.html

Go:   encoding/gob
来源：http://dali.0kj1m.cn/Article/details/gtucmwlwqs.html

Ruby: Marshal.dump(obj)
来源：http://dali.birdmap.top/Article/details/gtgmenqgql.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xuanzx.com/Article/details/gtuibunjla.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtyoytoxjq.html

L. 网络请求
来源：http://dali.hnqzz.top/Article/details/gtxjiaucvn.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtamasoznr.html

[L01] 发送 GET 请求
来源：http://dali.dashuyun.cn/Article/details/gtmqopiqko.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hywenlv.cn/Article/details/gtxfdiennl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.haohaochexian.top/Article/details/gtswgderse.html

JS:   await fetch(url)
来源：http://dali.yueranfly.top/Article/details/gtnmwowokj.html

TS:   await fetch(url)
来源：http://dali.daria6918.cn/Article/details/gtttfvawoh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinqigufen.top/Article/details/gtmrncuqzg.html

Go:   resp, err := http.Get(url)
来源：http://dali.hnxiangtu.top/Article/details/gtjqunpkjm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.dianchejie.cn/Article/details/gtwzjvlblz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yanxiufei.cn/Article/details/gtfvkwptna.html

[L02] 发送 POST JSON
来源：http://dali.yueranfly.top/Article/details/gtwkwobujt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cucudq.cn/Article/details/gtizqifocr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhiwuduotai.top/Article/details/gtbpnbivva.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.feifeiyinyue.top/Article/details/gtahmkvepj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxinkj.top/Article/details/gtndosmbmi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.pengpengdd.cyou/Article/details/gtavbypykc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gaohongyu789.top/Article/details/gtzvhmeyrr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbujegmw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.fzhhl.top/Article/details/gtkpdxrmuz.html

[L03] 设置自定义请求头
来源：http://dali.jiagoushi.top/Article/details/gtexvarssy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hysaishi.cn/Article/details/gtitebkdas.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gogol.net.cn/Article/details/gtllboovok.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sxryk.cn/Article/details/gtctanouha.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cqqwz.cn/Article/details/gtwqvrnbvd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.feifeiyinyue.top/Article/details/gthdpftiyr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hywenlv.cn/Article/details/gthwstbmtd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gzhubu.top/Article/details/gtcknjsysx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenlongwang.top/Article/details/gtkndmjrmq.html

[L04] 设置超时
来源：http://dali.zhoulong.xyz/Article/details/gtvjsgsqlp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.haohaochexian.top/Article/details/gtrxktnmng.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sysykeji.top/Article/details/gtythdyglr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ppjwa.cn/Article/details/gtdchvhgbi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jyoumei.cn/Article/details/gtletkesia.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.wangdashe.top/Article/details/gtibbhmmpu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fengsongda.top/Article/details/gtcsffkxng.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinghuilouyu.cn/Article/details/gtekpjtakh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnqzz.top/Article/details/gtsqswafrx.html

[L05] 上传文件（multipart）
来源：http://dali.pycfn.com/Article/details/gtlhrzxmcx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.9152youxi.cn/Article/details/gtrpscrosv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gotoacloud.top/Article/details/gtpdzxbzxd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.feifeiyinyue.top/Article/details/gtqrheqaob.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.meibo888.top/Article/details/gtklpldyoj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinqigufen.top/Article/details/gtjmycktug.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgckmmub.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xziqi.cn/Article/details/gtolrptemc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yonumen.top/Article/details/gtqivojnur.html

[L06] 解析响应为 JSON
来源：http://dali.zhongyouzk.top/Article/details/gtiresxrxf.html

Py:   resp.json()
来源：http://dali.birdmap.top/Article/details/gtzstqtlbd.html

PHP:  json_decode($body, true);
来源：http://dali.hammf.cn/Article/details/gtywimktqf.html

JS:   await resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gtamwsombf.html

TS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gtgykfpsqm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guowangkeji.top/Article/details/gtyyaxphrd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhixingplan.top/Article/details/gtuquzztca.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuanzhike.top/Article/details/gtpiwgtjcg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.mhx1999.top/Article/details/gtudgyblve.html

[L07] 处理 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gtovxavgkd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xylfe.cn/Article/details/gtyxumtpsv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ivvv.top/Article/details/gtbhzoepcl.html

JS:   resp.ok;  resp.status
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzczrrave.html

TS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gtzhuawnks.html

Java: resp.statusCode()
来源：http://dali.shzxlz.cn/Article/details/gtgtrjlgmm.html

Go:   resp.StatusCode
来源：http://dali.jinqigfzy.top/Article/details/gttboiuqca.html

Ruby: resp.code.to_i
来源：http://dali.tianlin.xyz/Article/details/gtstbscwyn.html

C#:   (int)resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gtzambdpbp.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gtojmfrbbz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.smart0.xyz/Article/details/gttzycxgdc.html

PHP:  curl_multi_init() 系列
来源：http://dali.fengsongda.top/Article/details/gteocawvqt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gtpckrtamo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gtaaoopgyb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.snrcjt.cn/Article/details/gtdciofzwr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cdnleiting.top/Article/details/gthhoskcpg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yuanzhike.top/Article/details/gtmcsezdbk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtgjvbrcls.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtxokvrpzx.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigufen.top/Article/details/gtiiwhljyx.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtwkyvtpkq.html

[M01] 读取命令行参数
来源：http://dali.dianchejie.cn/Article/details/gtqomwbhzh.html

Py:   sys.argv[1:]
来源：http://dali.gotoacloud.top/Article/details/gtjkxfefxd.html

PHP:  $argv;  $argc;
来源：http://dali.zhengqikj.top/Article/details/gtaujzhrzu.html

JS:   process.argv.slice(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdsseuej.html

TS:   process.argv.slice(2)
来源：http://dali.fzhhl.top/Article/details/gtjqkyfagq.html

Java: args 数组（main 方法参数）
来源：http://dali.hongshengwenyu.top/Article/details/gtcgxwbwex.html

Go:   os.Args[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gtoqhuprvv.html

Ruby: ARGV
来源：http://dali.chenlongwang.top/Article/details/gtrpxeonzy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gtdbqizbzb.html

[M02] 读取环境变量
来源：http://dali.daxiang520.top/Article/details/gtewvvuqcv.html

Py:   os.environ.get("HOME")
来源：http://dali.svipenyu.cn/Article/details/gthwhkwjzn.html


<!-- 参考信息 -->