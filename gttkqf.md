代发 wailian999

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj20258888.top/Article/details/gtylclstvk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.svipenyu.cn/Article/details/gtzpofjfmn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zdqjudy.top/Article/details/gtdvbnjsse.html

[I05] 按正则拆分
来源：http://dali.zhoulong.xyz/Article/details/gtjhtvadxd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtglgvrtow.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtculkkcps.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gtmebmssrq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gtqcmqnwsd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnqzz.top/Article/details/gtzosfbzxz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhiwuduotai.top/Article/details/gtngazibub.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gtadrewctm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nanxinkj.top/Article/details/gtpreemqgd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shanyushiyangtech.top/Article/details/gtcbwundvs.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gtomnpceyo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tian-w.cn/Article/details/gtoxwzwvtc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gzhubu.top/Article/details/gtmbjjdira.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.andypj.xyz/Article/details/gtqlgjvgnx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gtdyzuzchv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shzxlz.cn/Article/details/gtmtcaajuo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hysaishi.cn/Article/details/gtcskbqqtg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gtfenmcsyu.html

[I07] 忽略大小写与多行模式
来源：http://dali.haohaochexian.top/Article/details/gtiynfdsjd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yanxiufei.cn/Article/details/gtlatcvgsx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cheryme.top/Article/details/gtwjsbrduf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hongshengwenyu.top/Article/details/gtsuvahdyy.html

TS:   /error/gim
来源：http://dali.daxiang520.top/Article/details/gtbrpzmulk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.c1oappe.top/Article/details/gtsanttmgg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj202588.top/Article/details/gtjihsqbrx.html

Ruby: s.scan(/error/i)
来源：http://dali.birdmap.top/Article/details/gtroujwygw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jiagoushi.top/Article/details/gtrczopycp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yonumen.top/Article/details/gtzfbbxgzp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zdqjudy.top/Article/details/gtwxvorzhi.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.wangshuangyany.cn/Article/details/gtxdfzkjpm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yvedp.cn/Article/details/gthgewuxzi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yongpay.top/Article/details/gttbhgvzwx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuxming.cn/Article/details/gtmgwceogl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yanxiufei.cn/Article/details/gtvzphfuvh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yuxming.cn/Article/details/gtfjrnlfaj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gtiaaaqobd.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gthwgbdcgu.html

J. 日期与时间
来源：http://dali.sysykeji.top/Article/details/gthtwvgcmq.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtjuuamrkq.html

[J01] 获取当前时间
来源：http://dali.tanke756.top/Article/details/gttshbfpgt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.guowangkeji.top/Article/details/gtljdigkxp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.tian-w.cn/Article/details/gtptjhbexl.html

JS:   new Date();  Date.now()
来源：http://dali.shuidangran.top/Article/details/gtmotwrllb.html

TS:   new Date();  Date.now()
来源：http://dali.ydzc1.top/Article/details/gttdetsztx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gaohongyu789.top/Article/details/gtuyihyudx.html

Go:   time.Now()
来源：http://dali.andypj.xyz/Article/details/gtscadxmsw.html

Ruby: Time.now
来源：http://dali.zhoulong.xyz/Article/details/gtlwxzqich.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.kuanghao11.cn/Article/details/gtranqylgg.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gtefhlmejx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnxiangtu.top/Article/details/gtaiwhjczq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gttceokkuw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daria6918.cn/Article/details/gtjjzwrpan.html

TS:   d.toISOString()
来源：http://dali.ivvv.top/Article/details/gtkqlqipfa.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xuetiantiany.cn/Article/details/gtfanjrese.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenlongwang.top/Article/details/gtngfmalwp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daxiang520.top/Article/details/gtqittavko.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cheryme.top/Article/details/gtljiquthm.html

[J03] 字符串解析为日期
来源：http://dali.hnqzz.top/Article/details/gthrsrpfdg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yuxming.cn/Article/details/gtpvmjkfkd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gzhubu.top/Article/details/gtpsmmnxgc.html

JS:   new Date("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtkxjcnizt.html

TS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtbxibmhci.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtikovmyjw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gtfmsbrrkn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtqfwqtguf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuetiantiany.cn/Article/details/gtbcmrztvf.html

[J04] 时间戳与日期互转
来源：http://dali.vqdsnc.cn/Article/details/gtuzblfkzd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hysaishi.cn/Article/details/gtydicxbzq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.haohaochexian.top/Article/details/gtrhqscniv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yvedp.cn/Article/details/gtcsfruypz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhixingplan.top/Article/details/gtjbstengn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.fzhhl.top/Article/details/gthovsrick.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtqsnxhlro.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yonumen.top/Article/details/gttlggmhvx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tianlin.xyz/Article/details/gtajgmautq.html

[J05] 时间加减（加 7 天）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrujacxgy.html

Py:   now + timedelta(days=7)
来源：http://dali.sweek.top/Article/details/gthhmivomg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gotoacloud.top/Article/details/gtykpbhejm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daxiang520.top/Article/details/gtnccxwhjf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.mhx1999.top/Article/details/gtxsazkhnl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinqigfzy.top/Article/details/gtyakhtrui.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gogol.net.cn/Article/details/gtpllfnuqi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tanke756.top/Article/details/gtkprcyngz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hfpthk.cn/Article/details/gtpjaykynk.html

[J06] 计算两时间之差
来源：http://dali.yuxming.cn/Article/details/gttvxcrfgp.html

Py:   (end - start).total_seconds()
来源：http://dali.jiagoushi.top/Article/details/gtbwyrjfqj.html

PHP:  $end->diff($start)->days;
来源：http://dali.shanyushiyangtech.top/Article/details/gtatekgftx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shzxlz.cn/Article/details/gtgzgckswt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258888.top/Article/details/gthxdngjog.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shangyingyoupin.top/Article/details/gtnukfgshb.html

Go:   end.Sub(start).Hours()
来源：http://dali.bjfxy.top/Article/details/gtggxnuthr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.quarkkingdee.top/Article/details/gtdvahpdxv.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhiwuduotai.top/Article/details/gtxbnvpvgk.html

[J07] 比较两个日期
来源：http://dali.yangfankeji.com/Article/details/gtssmpchbf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gtkhwmxjxm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenzaomai.com/Article/details/gtzfodxbld.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gtukzhogfv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gtpyqgixim.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.havefunace.top/Article/details/gtfjbadget.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhongyouzk.top/Article/details/gtwetaupbb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gtfvblliib.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jiagoushi.top/Article/details/gtmeigzigy.html

[J08] 提取年月日与星期
来源：http://dali.xziqi.cn/Article/details/gtwscppngq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj20258888.top/Article/details/gtjhocujou.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shuidangran.top/Article/details/gtmjwzaftr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nanxuanxn.top/Article/details/gtmdbzdcdy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.birdmap.top/Article/details/gtafmycjdi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xinyue.icu/Article/details/gtagwurecc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.svipenyu.cn/Article/details/gtfxwyvdqc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tanke756.top/Article/details/gtqpkkhdcd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ybcxt.top/Article/details/gtzgxfhvpc.html

[J09] 时区处理
来源：http://dali.yj20258888.top/Article/details/gtgaokdqld.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sufxvd.cn/Article/details/gtcczoipbg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ydzc1.top/Article/details/gtpvxgmjwj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhongyouzk.top/Article/details/gtkhimgvoi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.c1oappe.top/Article/details/gtunoqybco.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sweek.top/Article/details/gtnqngvlfx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.bjfxy.top/Article/details/gttcpyjifl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hywenlv.cn/Article/details/gtpkmrbtpx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.guowangkeji.top/Article/details/gtfmhsauhc.html

[J10] 取今天 / 本月第一天
来源：http://dali.gzhubu.top/Article/details/gtqwdopewg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.birdmap.top/Article/details/gtpfjcaqcz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cdnleiting.top/Article/details/gthwiovffl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenzaomai.com/Article/details/gtkvhkkaci.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.aizwys.cn/Article/details/gtppkrxpcm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yangfankeji.com/Article/details/gtuobsrmpo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yuanzhike.top/Article/details/gtdwozrpgg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.birdmap.top/Article/details/gtaibqulul.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.daxiang520.top/Article/details/gtnswpydyl.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtofmnuzwn.html

K. JSON 与序列化
来源：http://dali.yj20258.top/Article/details/gtoigrnvdj.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtxzbamcjv.html

[K01] 对象转 JSON 字符串
来源：http://dali.pengpengdd.cyou/Article/details/gttzzkysap.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shangyingyoupin.top/Article/details/gtpgaxpofn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hywenlv.cn/Article/details/gtfftczwsu.html

JS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gtsqpzzyex.html

TS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gtlcqbjalj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shangyingyoupin.top/Article/details/gtrllroyhn.html

Go:   json.Marshal(obj)
来源：http://dali.hysaishi.cn/Article/details/gtztjdjduw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sxryk.cn/Article/details/gthmszfzar.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtxgbymyly.html

[K02] JSON 字符串转对象
来源：http://dali.yueranfly.top/Article/details/gtilougfql.html

Py:   json.loads(s)
来源：http://dali.cqqwz.cn/Article/details/gthyuyjtaw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jqgufenzy.top/Article/details/gtmmqaibgb.html

JS:   JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gtivndvhlu.html

TS:   JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gtdgahuwzu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gtrfumlkvz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.pengpengdd.cyou/Article/details/gtzklivmvl.html

Ruby: JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtzfgatbvy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gogol.net.cn/Article/details/gtgggfgsgc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shangyingyoupin.top/Article/details/gtgogqbpqs.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hfpthk.cn/Article/details/gtlrqxbdwk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gtnyqafnlr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.quarkkingdee.top/Article/details/gthypnbzhv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigufen.top/Article/details/gtfxfqqbsv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yueranfly.top/Article/details/gtmcdsjfdw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ehwqpu.com/Article/details/gtixcpdysp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yvedp.cn/Article/details/gtsdvcdxds.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xylfe.cn/Article/details/gtlxssjceu.html

[K04] 读取 JSON 文件
来源：http://dali.wangdashe.top/Article/details/gtqlybyotp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gtxkhshejc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gaohongyu789.top/Article/details/gtliilhuwk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigufen.top/Article/details/gtudiwiqhe.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgfzy.top/Article/details/gtpfrhlaay.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedufihke.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ivvv.top/Article/details/gtgruwixos.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hnxiangtu.top/Article/details/gtyflzafcp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.wangshuangyany.cn/Article/details/gtwgczqhyy.html

[K05] 深拷贝对象
来源：http://dali.havefunace.top/Article/details/gthswpisil.html

Py:   copy.deepcopy(obj)
来源：http://dali.wangdashe.top/Article/details/gtfiuwzmdk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.meibo888.top/Article/details/gtsplxoxia.html

JS:   structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gtnrclgfhi.html

TS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtpkacbaef.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenzaomai.com/Article/details/gtlxgxgmzp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jqgufenzy.top/Article/details/gtacigzbig.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cqqwz.cn/Article/details/gtdurfsfxa.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.haohaochexian.top/Article/details/gttuqjtkgn.html

[K06] 解析 URL 查询串
来源：http://dali.svipenyu.cn/Article/details/gtojxxhhfm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.fzhhl.top/Article/details/gtjwqctaue.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jlsjyb.cn/Article/details/gtzojxxhpd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.havefunace.top/Article/details/gtjwgptxac.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuxming.cn/Article/details/gteskbxyls.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gaohongyu789.top/Article/details/gtgwwjnzdi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gtfugbtopw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gtnvxmlflj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gtsajugzej.html

[K07] 进制转换
来源：http://dali.9152youxi.cn/Article/details/gtdpzyoemy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaljsjcxx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xuetiantiany.cn/Article/details/gtjifomzfb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtoalvgnra.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtpiqwqbdk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtwgslopfb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tian-w.cn/Article/details/gtkjlxxrba.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnxiangtu.top/Article/details/gtivgyvpye.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtruferqwo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenzaomai.com/Article/details/gtnicjuyjs.html

Py:   pickle.dumps(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvnxjywhn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cheryme.top/Article/details/gtilbhthkh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jlsjyb.cn/Article/details/gtdgugozlk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xylfe.cn/Article/details/gtwljdswyp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.guannengcc.top/Article/details/gtxpymivrf.html

Go:   encoding/gob
来源：http://dali.fzhhl.top/Article/details/gtghhrzoen.html

Ruby: Marshal.dump(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmetxcxkc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhongyouzk.top/Article/details/gtghhoitym.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtqtrohtkt.html

L. 网络请求
来源：http://dali.zhixingplan.top/Article/details/gtslxjhrfz.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gteiqtprwf.html

[L01] 发送 GET 请求
来源：http://dali.zhiwuduotai.top/Article/details/gtyehnzgaj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.haohaochexian.top/Article/details/gtzrxrojzz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhiwuduotai.top/Article/details/gttrghixsv.html

JS:   await fetch(url)
来源：http://dali.zhixingplan.top/Article/details/gtvypfifmg.html

TS:   await fetch(url)
来源：http://dali.cheryme.top/Article/details/gtuvnwhmmp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sxryk.cn/Article/details/gtjdokpmto.html

Go:   resp, err := http.Get(url)
来源：http://dali.sufxvd.cn/Article/details/gtowngkntd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sweek.top/Article/details/gtwonhipqa.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenjidiqi.icu/Article/details/gttokvpmax.html

[L02] 发送 POST JSON
来源：http://dali.aizwys.cn/Article/details/gtljykttku.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nanxinkj.top/Article/details/gtgdgbmfoj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ybcxt.top/Article/details/gtzpnaktoe.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258.top/Article/details/gtrzfpffah.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.quarkkingdee.top/Article/details/gtlpjnuppz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hysaishi.cn/Article/details/gtlxlsfqmu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.andypj.xyz/Article/details/gtlkhnczrp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiskpsyma.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xuetiantiany.cn/Article/details/gtmgeagfdp.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gtxhwciygd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.andypj.xyz/Article/details/gtrunqjxwa.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtcacdkdbn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.316326.xyz/Article/details/gtskeelmjv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuetiantiany.cn/Article/details/gthchsrsyy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.wangshuangyany.cn/Article/details/gtapdfoglm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gtvyrylbyt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jianghu66.top/Article/details/gtqgjrcqam.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gtsgsckroo.html

[L04] 设置超时
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxffhyru.html

Py:   requests.get(url, timeout=5)
来源：http://dali.fzhhl.top/Article/details/gtdipigxaw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gogol.net.cn/Article/details/gtlsiegmld.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pycfn.com/Article/details/gtkzcleloa.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xylfe.cn/Article/details/gtghyahtwi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.quarkkingdee.top/Article/details/gtpxfoqgox.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenjidiqi.icu/Article/details/gtvtqjyiku.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.snrcjt.cn/Article/details/gtzykihqry.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guowangkeji.top/Article/details/gtisminpbc.html

[L05] 上传文件（multipart）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakxloilx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yuanzhike.top/Article/details/gtlxtouvis.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.havefunace.top/Article/details/gtnahgfwvj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.vqdsnc.cn/Article/details/gtkvkkrovi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258888.top/Article/details/gtipoomdeb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cdnleiting.top/Article/details/gtytfmijem.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hnqzz.top/Article/details/gtsjmspvgq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sxryk.cn/Article/details/gtjiupmxod.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtauavbwkr.html

[L06] 解析响应为 JSON
来源：http://dali.cdnleiting.top/Article/details/gtjzsrytke.html

Py:   resp.json()
来源：http://dali.chenlongwang.top/Article/details/gtrawmiqyy.html

PHP:  json_decode($body, true);
来源：http://dali.hammf.cn/Article/details/gtarvtsfoc.html

JS:   await resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gtzsbjxoeq.html

TS:   await resp.json()
来源：http://dali.cucudq.cn/Article/details/gtjqkjmavj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cucudq.cn/Article/details/gtxghpehrw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.svipenyu.cn/Article/details/gtwwqowptj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gogol.net.cn/Article/details/gtaiaysajv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tianlin.xyz/Article/details/gtqytjpwgw.html

[L07] 处理 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gtspfpcvpc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.pycfn.com/Article/details/gtrmtoxcdx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cucudq.cn/Article/details/gtxplcbysd.html

JS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gtolwjtxzd.html

TS:   resp.ok;  resp.status
来源：http://dali.c1oappe.top/Article/details/gtvzjxsyyc.html

Java: resp.statusCode()
来源：http://dali.shuidangran.top/Article/details/gtobtcfqyg.html

Go:   resp.StatusCode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcrmclzli.html

Ruby: resp.code.to_i
来源：http://dali.gotoacloud.top/Article/details/gtdevblbnd.html

C#:   (int)resp.StatusCode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgbenndmg.html

[L08] 并发请求多个地址
来源：http://dali.yj20258.top/Article/details/gtbnbkmdhy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zycfv.cn/Article/details/gtevlpgkqp.html

PHP:  curl_multi_init() 系列
来源：http://dali.guowangkeji.top/Article/details/gtomnzbubw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ybcxt.top/Article/details/gtlyscutgt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gtlbacenyx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tian-w.cn/Article/details/gtgyzzgqjr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yuxming.cn/Article/details/gtpfycxrqx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yanxiufei.cn/Article/details/gtjwprifsu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daxiang520.top/Article/details/gtkdqwrxij.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtmkflmixh.html

M. 命令行 / 进程 / 环境
来源：http://dali.nwbrower.top/Article/details/gtzuajylfe.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtcvnxfxir.html

[M01] 读取命令行参数
来源：http://dali.chenjidiqi.icu/Article/details/gtiwjocldb.html

Py:   sys.argv[1:]
来源：http://dali.jinqigfzy.top/Article/details/gttlcsmwud.html

PHP:  $argv;  $argc;
来源：http://dali.ybcxt.top/Article/details/gtbkphytns.html

JS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gtzpjwofeo.html

TS:   process.argv.slice(2)
来源：http://dali.yj20258888.top/Article/details/gthagdrfzs.html

Java: args 数组（main 方法参数）
来源：http://dali.kuanghao11.cn/Article/details/gtojcnbqfv.html

Go:   os.Args[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkzlynnh.html

Ruby: ARGV
来源：http://dali.daxiang520.top/Article/details/gtgbtbpxpe.html

C#:   args 数组（Main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gtrgnojslx.html

[M02] 读取环境变量
来源：http://dali.zhoulong.xyz/Article/details/gtrrlxqhzo.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtagvuawho.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.316326.xyz/Article/details/gtyefbuahz.html

JS:   process.env.HOME
来源：http://dali.cheryme.top/Article/details/gtmqdrofgp.html

TS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gtuivruhbh.html

Java: System.getenv("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtnwlebiwa.html


<!-- 参考信息 -->