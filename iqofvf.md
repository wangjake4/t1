代发 wailian999

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ybcxt.top/Article/details/gt2vsjdnidp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2oerkqnrv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gt2npjdqglq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gt2bzakovug.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shzxlz.cn/Article/details/gt2jpktxorb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.redwolf501.top/Article/details/gt2cmjcnhyr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gt2jghbjiuv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2esmyrxur.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cucudq.cn/Article/details/gt2iqweahtl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gt2oiylmepy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hnqzz.top/Article/details/gt2nxxdffpw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aibaodan.cn/Article/details/gt2akezytqb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gt2ieqqyaxl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gt2jjxaazaa.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuanzx.com/Article/details/gt2liwpqfxf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cqqwz.cn/Article/details/gt2iaeafmms.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gt2fewbsnvt.html

[I07] 忽略大小写与多行模式
来源：http://dali.0kj1m.cn/Article/details/gt2smiusjpa.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj20258.top/Article/details/gt2ajltnsnl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.snrcjt.cn/Article/details/gt2xrplsmli.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xuetiantiany.cn/Article/details/gt2cyplhdlv.html

TS:   /error/gim
来源：http://dali.hnxiangtu.top/Article/details/gt2tgxrafzt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhoulong.xyz/Article/details/gt2odxhwthr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tanke756.top/Article/details/gt2kaoamxon.html

Ruby: s.scan(/error/i)
来源：http://dali.snrcjt.cn/Article/details/gt2infmjkjc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ppjwa.cn/Article/details/gt2dvfsgpch.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.havefunace.top/Article/details/gt2susvchvb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.meibo888.top/Article/details/gt2mdumbqoe.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cqqwz.cn/Article/details/gt2nzxzqnik.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgfzy.top/Article/details/gt2qkoavtwd.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pengpengdd.cyou/Article/details/gt2onnkpssd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.guowangkeji.top/Article/details/gt2durwgycd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ehwqpu.com/Article/details/gt2dvkosykx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.haohaochexian.top/Article/details/gt2otjizjeu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nanxuanxn.top/Article/details/gt2gzkaahuj.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2okbrykyc.html

J. 日期与时间
来源：http://dali.ppjwa.cn/Article/details/gt2opujownf.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2ipnkysuo.html

[J01] 获取当前时间
来源：http://dali.jyoumei.cn/Article/details/gt2yaylmdbi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.quarkkingdee.top/Article/details/gt2huyutrkl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gt2bmbzfjnx.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugixvcxj.html

TS:   new Date();  Date.now()
来源：http://dali.jiagoushi.top/Article/details/gt2hqeazbxy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhiwuduotai.top/Article/details/gt2rbrhaepo.html

Go:   time.Now()
来源：http://dali.nwbrower.top/Article/details/gt2lhpfilho.html

Ruby: Time.now
来源：http://dali.ivvv.top/Article/details/gt2nayszzgx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.vqdsnc.cn/Article/details/gt2dgpjpumy.html

[J02] 格式化输出
来源：http://dali.tanke756.top/Article/details/gt2mxxhwvaj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daria6918.cn/Article/details/gt2mlkfpdim.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.guannengcc.top/Article/details/gt2ijpwguum.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jlsjyb.cn/Article/details/gt2vfhrihsu.html

TS:   d.toISOString()
来源：http://dali.hnxiangtu.top/Article/details/gt2yactunjy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhiwuduotai.top/Article/details/gt2yppqxone.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ybcxt.top/Article/details/gt2mcupodwl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2upixycvd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cheryme.top/Article/details/gt2hlglbhud.html

[J03] 字符串解析为日期
来源：http://dali.pycfn.com/Article/details/gt2fvcyzkhr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.svipenyu.cn/Article/details/gt2sewcbiev.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shzxlz.cn/Article/details/gt2mrqasjnz.html

JS:   new Date("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gt2iqewqzqp.html

TS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2rpjvvdaa.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gt2nunbjxas.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gt2xiykhgoa.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gt2mvndcgmr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yuanzhike.top/Article/details/gt2glzyzeqf.html

[J04] 时间戳与日期互转
来源：http://dali.dianchejie.cn/Article/details/gt2yxonceda.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nanxuanxn.top/Article/details/gt2fvazieon.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigufen.top/Article/details/gt2ggbvgfza.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfljjlpw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.0kj1m.cn/Article/details/gt2lfljhque.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gotoacloud.top/Article/details/gt2hyipawhi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2bnkfwyoo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.9152youxi.cn/Article/details/gt2ffjizmrn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxuanxn.top/Article/details/gt2uekiqehn.html

[J05] 时间加减（加 7 天）
来源：http://dali.yanxiufei.cn/Article/details/gt2uithqinf.html

Py:   now + timedelta(days=7)
来源：http://dali.wangdashe.top/Article/details/gt2mfslkzmd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yueranfly.top/Article/details/gt2xvxdcvyo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jlsjyb.cn/Article/details/gt2xothynfo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2snwnjucf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gt2iwwlioue.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cqqwz.cn/Article/details/gt2polubbke.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj20258888.top/Article/details/gt2fslxokli.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dashuyun.cn/Article/details/gt2xsirctbm.html

[J06] 计算两时间之差
来源：http://dali.nwbrower.top/Article/details/gt2cfigjgmw.html

Py:   (end - start).total_seconds()
来源：http://dali.gogol.net.cn/Article/details/gt2cpmndjel.html

PHP:  $end->diff($start)->days;
来源：http://dali.cdnleiting.top/Article/details/gt2nbumqugl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.wangshuangyany.cn/Article/details/gt2mkyrwmff.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hysaishi.cn/Article/details/gt2xeqipafj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aibaodan.cn/Article/details/gt2pbsxrouk.html

Go:   end.Sub(start).Hours()
来源：http://dali.gaohongyu789.top/Article/details/gt2bkpddxmh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hywenlv.cn/Article/details/gt2tsmtrxgn.html

C#:   (end - start).TotalSeconds
来源：http://dali.dianchejie.cn/Article/details/gt2vgwihcwt.html

[J07] 比较两个日期
来源：http://dali.cashguo.top/Article/details/gt2ujbqajov.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rlqkknkp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gogol.net.cn/Article/details/gt2zyfauhgu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.vqdsnc.cn/Article/details/gt2sgbwpqzi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gt2wvocgxhn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hfpthk.cn/Article/details/gt2tlbohlwl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tianlin.xyz/Article/details/gt2tldyluee.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gt2yhyaflpw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gt2wgetfobq.html

[J08] 提取年月日与星期
来源：http://dali.redwolf501.top/Article/details/gt2gskegzoz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tian-w.cn/Article/details/gt2tatbvutc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.wangdashe.top/Article/details/gt2vwxjzcme.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daxiang520.top/Article/details/gt2vhyuuess.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eezcjxpk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gogol.net.cn/Article/details/gt2jpsqzwfs.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.feifeiyinyue.top/Article/details/gt2jdnenser.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.dashuyun.cn/Article/details/gt2ifiewvty.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zgavlrfb.html

[J09] 时区处理
来源：http://dali.yuanzhike.top/Article/details/gt2lncrpfgy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hywenlv.cn/Article/details/gt2tiabyhrh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.fengsongda.top/Article/details/gt2cavkvcng.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gzhubu.top/Article/details/gt2dhzrrlwo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2errruyqb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zycfv.cn/Article/details/gt2allukrew.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jiagoushi.top/Article/details/gt2rahgtwti.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxinkj.top/Article/details/gt2znwxyhqu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenjidiqi.icu/Article/details/gt2scvgmmvs.html

[J10] 取今天 / 本月第一天
来源：http://dali.sufxvd.cn/Article/details/gt2eivusykb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jiagoushi.top/Article/details/gt2clpiqnfz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shangyingyoupin.top/Article/details/gt2lqtaisip.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgfzy.top/Article/details/gt2whdqevsg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ivvv.top/Article/details/gt2gajkygui.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sweek.top/Article/details/gt2ppuonsfg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.bjfxy.top/Article/details/gt2qzqkeawb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.9152youxi.cn/Article/details/gt2xjtmcoud.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenzaomai.com/Article/details/gt2wvjakvub.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2utmvnybt.html

K. JSON 与序列化
来源：http://dali.zhixingplan.top/Article/details/gt2nqciqfxu.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2pbdrqrhr.html

[K01] 对象转 JSON 字符串
来源：http://dali.xylfe.cn/Article/details/gt2thvtqcrj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gt2iswjnsqp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.quarkkingdee.top/Article/details/gt2ddzxvhna.html

JS:   JSON.stringify(obj)
来源：http://dali.sysykeji.top/Article/details/gt2spadlmxw.html

TS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gt2axyvdkfc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ydzc1.top/Article/details/gt2mfjbmizi.html

Go:   json.Marshal(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2raqzfifc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnqzz.top/Article/details/gt2myizauuq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuxming.cn/Article/details/gt2vpcfujnn.html

[K02] JSON 字符串转对象
来源：http://dali.hongshengwenyu.top/Article/details/gt2goxmuyyz.html

Py:   json.loads(s)
来源：http://dali.nanxinkj.top/Article/details/gt2wnkpcjyw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nirphytl.html

JS:   JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gt2marasmrv.html

TS:   JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gt2ggvgtngo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj20258888.top/Article/details/gt2gxadvkgv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gt2yfzcvdgp.html

Ruby: JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gt2dgtftpec.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2tykeolox.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.guannengcc.top/Article/details/gt2opnbjozv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gt2lfdzwyqz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gt2fainsjqd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tianlin.xyz/Article/details/gt2ykhbqfpv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2cjullwty.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vbksprkt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.haohaochexian.top/Article/details/gt2mpobwtdk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tanke756.top/Article/details/gt2osmoapih.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.iojbl.cn/Article/details/gt2pzjypkfa.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2elvhrigo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigfzy.top/Article/details/gt2lxvzvjwi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenlongwang.top/Article/details/gt2hroaefpy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2etyuxznw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.smart0.xyz/Article/details/gt2qbwfqjfc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xylfe.cn/Article/details/gt2nngxjriw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vhazoxau.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhongyouzk.top/Article/details/gt2pnsxqgdk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.c1oappe.top/Article/details/gt2nsxovdnf.html

[K05] 深拷贝对象
来源：http://dali.guannengcc.top/Article/details/gt2havlyzlp.html

Py:   copy.deepcopy(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2anrruhcb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.guowangkeji.top/Article/details/gt2pokilxjt.html

JS:   structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2quzrytlc.html

TS:   structuredClone(obj)
来源：http://dali.tian-w.cn/Article/details/gt2oolxunng.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.meibo888.top/Article/details/gt2sgdeldql.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.redwolf501.top/Article/details/gt2jefmdajq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yongpay.top/Article/details/gt2uprxbnek.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cucudq.cn/Article/details/gt2sufbscub.html

[K06] 解析 URL 查询串
来源：http://dali.snrcjt.cn/Article/details/gt2ngiklqzq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.316326.xyz/Article/details/gt2tkmcjhgv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenzaomai.com/Article/details/gt2tokjtlty.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gt2tzlbbxyl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aibaodan.cn/Article/details/gt2vqgmtvbw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aizwys.cn/Article/details/gt2ltbdnlkz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gt2mvqskpub.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gt2mxtwkzcy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gt2crhmwomw.html

[K07] 进制转换
来源：http://dali.zycfv.cn/Article/details/gt2ozgrziwx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cheryme.top/Article/details/gt2bjgokdfv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cashguo.top/Article/details/gt2unzuartz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tanke756.top/Article/details/gt2llmzqucu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gt2zbyhqdjb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2favrrwxr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yonumen.top/Article/details/gt2gtptiitr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yanxiufei.cn/Article/details/gt2whdykbdi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cashguo.top/Article/details/gt2hvcbkftv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fengsongda.top/Article/details/gt2mqkeffuz.html

Py:   pickle.dumps(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kemggcbs.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2fblvpbqj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gt2yinnnbjq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cqqwz.cn/Article/details/gt2ojrxknbj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.kuanghao11.cn/Article/details/gt2rtnomnxw.html

Go:   encoding/gob
来源：http://dali.chenlongwang.top/Article/details/gt2zrhdalzc.html

Ruby: Marshal.dump(obj)
来源：http://dali.c1oappe.top/Article/details/gt2fiduwqnn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.316326.xyz/Article/details/gt2sjjubzhx.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2ionrrtfq.html

L. 网络请求
来源：http://dali.yanxiufei.cn/Article/details/gt2amlrizde.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2fntvlyvw.html

[L01] 发送 GET 请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jxnlslww.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cheryme.top/Article/details/gt2eifgybxg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gotoacloud.top/Article/details/gt2hwwdsdfm.html

JS:   await fetch(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oosrywhs.html

TS:   await fetch(url)
来源：http://dali.mhx1999.top/Article/details/gt2pgxokmzr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.wangshuangyany.cn/Article/details/gt2zmoeqbwj.html

Go:   resp, err := http.Get(url)
来源：http://dali.ppjwa.cn/Article/details/gt2drrakchu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj202588.top/Article/details/gt2xbwqkshu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.dianchejie.cn/Article/details/gt2hytpfffm.html

[L02] 发送 POST JSON
来源：http://dali.ydzc1.top/Article/details/gt2pluuwlak.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gzhubu.top/Article/details/gt2kmbbwxzb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2nenhgmqp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jyoumei.cn/Article/details/gt2bfzwvaaa.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nwbrower.top/Article/details/gt2jeqwbpxz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.dianchejie.cn/Article/details/gt2gczitlch.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ivvv.top/Article/details/gt2xgfghquj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.c1oappe.top/Article/details/gt2pvosirru.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pgzzgxve.html

[L03] 设置自定义请求头
来源：http://dali.guannengcc.top/Article/details/gt2csvuzlaj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenjidiqi.icu/Article/details/gt2jzvxzzvx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgufenzy.top/Article/details/gt2bbhlgnxv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.kuanghao11.cn/Article/details/gt2rogcxiim.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gt2ypukdmcu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hptsjvrx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gt2ragdsqpp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gotoacloud.top/Article/details/gt2thodtsnn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jqgufenzy.top/Article/details/gt2xvkerfov.html

[L04] 设置超时
来源：http://dali.svipenyu.cn/Article/details/gt2cifymfvw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.aizwys.cn/Article/details/gt2ymqufsmc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.iojbl.cn/Article/details/gt2uottcoai.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj202588.top/Article/details/gt2kbsnzjlq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgfzy.top/Article/details/gt2ezwuyghi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ggizkhbo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tian-w.cn/Article/details/gt2fxngysga.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.bjfxy.top/Article/details/gt2daubuqie.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.haohaochexian.top/Article/details/gt2ykphbyot.html

[L05] 上传文件（multipart）
来源：http://dali.xziqi.cn/Article/details/gt2ojkgevrv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinqigfzy.top/Article/details/gt2gwvipbmg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.svipenyu.cn/Article/details/gt2piyeuwst.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yvedp.cn/Article/details/gt2nywtbkck.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shuidangran.top/Article/details/gt2mmglauue.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gotoacloud.top/Article/details/gt2vdwdfhiv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2bieeldaj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.havefunace.top/Article/details/gt2vbmdffwy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2thrbvcjf.html

[L06] 解析响应为 JSON
来源：http://dali.zhongyouzk.top/Article/details/gt2pyxffurk.html

Py:   resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gt2glrvjhdk.html

PHP:  json_decode($body, true);
来源：http://dali.jinqigufen.top/Article/details/gt2lgkszghc.html

JS:   await resp.json()
来源：http://dali.ehwqpu.com/Article/details/gt2imawlwwc.html

TS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ifvhaguo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rmmyuiwo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cucudq.cn/Article/details/gt2sbytjtyx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yueranfly.top/Article/details/gt2ixtfddnb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hvnbewqc.html

[L07] 处理 HTTP 状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2isujrlzo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hywenlv.cn/Article/details/gt2tjivqvfp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sweek.top/Article/details/gt2krkwoekz.html

JS:   resp.ok;  resp.status
来源：http://dali.9152youxi.cn/Article/details/gt2nwlnjwjj.html

TS:   resp.ok;  resp.status
来源：http://dali.nanxinkj.top/Article/details/gt2zhffdxsr.html

Java: resp.statusCode()
来源：http://dali.wangdashe.top/Article/details/gt2oqqwsqqg.html

Go:   resp.StatusCode
来源：http://dali.shangyingyoupin.top/Article/details/gt2zjatnqck.html

Ruby: resp.code.to_i
来源：http://dali.0kj1m.cn/Article/details/gt2dvhozgfv.html

C#:   (int)resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gt2lbgtzeee.html

[L08] 并发请求多个地址
来源：http://dali.dianchejie.cn/Article/details/gt2eprswqlk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangdashe.top/Article/details/gt2zqiiqtgy.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj20258.top/Article/details/gt2gzxkibpp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gt2skeytypo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gt2alorqrtd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sxryk.cn/Article/details/gt2ypmnpgtp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ehwqpu.com/Article/details/gt2gzizkwis.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ehwqpu.com/Article/details/gt2zjxvleru.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sxryk.cn/Article/details/gt2gpfnwqps.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2eptefgib.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhengqikj.top/Article/details/gt2ffttbdyq.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2nxdoifeq.html

[M01] 读取命令行参数
来源：http://dali.xziqi.cn/Article/details/gt2dchczhkn.html

Py:   sys.argv[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gt2httvvany.html

PHP:  $argv;  $argc;
来源：http://dali.jianghu66.top/Article/details/gt2uxluqhnl.html

JS:   process.argv.slice(2)
来源：http://dali.yanxiufei.cn/Article/details/gt2rcxkovyy.html

TS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gt2uywulhti.html

Java: args 数组（main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gt2hqxwpnnq.html

Go:   os.Args[1:]
来源：http://dali.nwbrower.top/Article/details/gt2ofsxwllp.html

Ruby: ARGV
来源：http://dali.yuxming.cn/Article/details/gt2dvnpksur.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258.top/Article/details/gt2kaaxlnkw.html

[M02] 读取环境变量
来源：http://dali.ppjwa.cn/Article/details/gt2xlazguyq.html

Py:   os.environ.get("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gt2poxdvoov.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangdashe.top/Article/details/gt2jprhjmeu.html

JS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gt2oqqbwjnf.html

TS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gt2fuafjnsx.html

Java: System.getenv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gt2tzocaduw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.aibaodan.cn/Article/details/gt2lcholxst.html

Ruby: ENV["HOME"]
来源：http://dali.haohaochexian.top/Article/details/gt2khrlbpne.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yueranfly.top/Article/details/gt2bibbtshk.html

[M03] 执行外部命令
来源：http://dali.zdqjudy.top/Article/details/gt2nszhlxwo.html


<!-- 参考信息 -->