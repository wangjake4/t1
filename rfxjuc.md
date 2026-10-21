代发 wailian999

Java: s.split("\\s*,\\s*")
来源：http://dali.tian-w.cn/Article/details/gthhpuddmx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtynjgawwd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gtostwbmst.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yuanzhike.top/Article/details/gtqnmknrdo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xylfe.cn/Article/details/gtjysywthu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gtprxuhuqx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.fengsongda.top/Article/details/gtmdswgizc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gtwtjpctuo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daria6918.cn/Article/details/gtnzigudkt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihdgmvkp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yangfankeji.com/Article/details/gtbzsgsrpa.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hnqzz.top/Article/details/gtuzmxxtyc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gtxrseumwo.html

[I07] 忽略大小写与多行模式
来源：http://dali.zdqjudy.top/Article/details/gtzvzmlsqu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yonumen.top/Article/details/gtcjyizmqc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ppjwa.cn/Article/details/gttuqtuzup.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yanxiufei.cn/Article/details/gtusvqrowo.html

TS:   /error/gim
来源：http://dali.xuetiantiany.cn/Article/details/gtkcwxacxf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yongpay.top/Article/details/gtxrjcyhfc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zdqjudy.top/Article/details/gtmakvttlw.html

Ruby: s.scan(/error/i)
来源：http://dali.gotoacloud.top/Article/details/gtcvlvvmjx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jiagoushi.top/Article/details/gtrxeqjyal.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yuxming.cn/Article/details/gtqzotrzxp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.fengsongda.top/Article/details/gtzwscbjlp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.daria6918.cn/Article/details/gtowfjpfyv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gtngytbkrb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sxryk.cn/Article/details/gtseykvham.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xylfe.cn/Article/details/gtsffjuoqr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.316326.xyz/Article/details/gtdhyhvvjx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.birdmap.top/Article/details/gtycqckdgg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmrapdqbn.html

================================================================================
来源：http://dali.sweek.top/Article/details/gttnlkkwak.html

J. 日期与时间
来源：http://dali.xziqi.cn/Article/details/gtyspyktsq.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtfveaepfy.html

[J01] 获取当前时间
来源：http://dali.dashuyun.cn/Article/details/gtisvpyjti.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.dashuyun.cn/Article/details/gtprcenduj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gttzgzzbbp.html

JS:   new Date();  Date.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gthqtauxec.html

TS:   new Date();  Date.now()
来源：http://dali.birdmap.top/Article/details/gtljronxfp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj20258888.top/Article/details/gtqsibylit.html

Go:   time.Now()
来源：http://dali.vqdsnc.cn/Article/details/gtqbdrqgjz.html

Ruby: Time.now
来源：http://dali.hnxiangtu.top/Article/details/gtntwuegda.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dianchejie.cn/Article/details/gtldmrvkbv.html

[J02] 格式化输出
来源：http://dali.hnqzz.top/Article/details/gtrqklflez.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.havefunace.top/Article/details/gtjsioqdrx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sufxvd.cn/Article/details/gtbesebiuv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.316326.xyz/Article/details/gtseaylyjw.html

TS:   d.toISOString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxwjkgpm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fengsongda.top/Article/details/gtezjidlnj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxvbbtsd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guannengcc.top/Article/details/gtngfldseo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinqigfzy.top/Article/details/gtgmcihzph.html

[J03] 字符串解析为日期
来源：http://dali.andypj.xyz/Article/details/gthyubhtlv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhixingplan.top/Article/details/gtsgrtobea.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258.top/Article/details/gtfyswdbwz.html

JS:   new Date("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtdzvdlmcz.html

TS:   new Date("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gtqgzrlftq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtrgycjyjz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtotflryau.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtcrifcxgn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jianghu66.top/Article/details/gtbavyfder.html

[J04] 时间戳与日期互转
来源：http://dali.jianghu66.top/Article/details/gtdychotat.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tianlin.xyz/Article/details/gtwycpqcxc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxdeprzp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jqgufenzy.top/Article/details/gtdfgjcjlm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.vqdsnc.cn/Article/details/gtpduzvypa.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cashguo.top/Article/details/gtufdadjkx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.daxiang520.top/Article/details/gtgnnysgjh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtldvtozxj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hammf.cn/Article/details/gtesghxdlv.html

[J05] 时间加减（加 7 天）
来源：http://dali.kuanghao11.cn/Article/details/gtdeiqngxx.html

Py:   now + timedelta(days=7)
来源：http://dali.mhx1999.top/Article/details/gtbafvaglz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.feifeiyinyue.top/Article/details/gtwknduppq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.0kj1m.cn/Article/details/gtppbnmmnm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tian-w.cn/Article/details/gtdfiiysvc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gzhubu.top/Article/details/gttwsnhctx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zycfv.cn/Article/details/gtwdadhojv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jianghu66.top/Article/details/gtupsogboz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.9152youxi.cn/Article/details/gtbziqjqea.html

[J06] 计算两时间之差
来源：http://dali.zdqjudy.top/Article/details/gtjwahvspk.html

Py:   (end - start).total_seconds()
来源：http://dali.yongpay.top/Article/details/gtmfuulhnb.html

PHP:  $end->diff($start)->days;
来源：http://dali.gzhubu.top/Article/details/gtcjbgignn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuanzhike.top/Article/details/gtnrvozpuo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ydzc1.top/Article/details/gtonsdirry.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aizwys.cn/Article/details/gtcsnbpiux.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhengqikj.top/Article/details/gtdyxxyttu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sufxvd.cn/Article/details/gtenzeytrs.html

C#:   (end - start).TotalSeconds
来源：http://dali.pengpengdd.cyou/Article/details/gtdwntwdid.html

[J07] 比较两个日期
来源：http://dali.316326.xyz/Article/details/gtvewekiaq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tianlin.xyz/Article/details/gttypepokx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aibaodan.cn/Article/details/gtddpsgwmo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgfzy.top/Article/details/gtoebijilg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxuanxn.top/Article/details/gtbhmdwgfh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigfzy.top/Article/details/gtpkfyowsz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gzhubu.top/Article/details/gtdcgyxydl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtpkvjgspw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtuhkzepcy.html

[J08] 提取年月日与星期
来源：http://dali.chenzaomai.com/Article/details/gtfvvztbka.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhoulong.xyz/Article/details/gtiqssbvii.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yuanzhike.top/Article/details/gtvvdeenop.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj202588.top/Article/details/gtzuszmqsd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.meibo888.top/Article/details/gtynihzkkz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sufxvd.cn/Article/details/gttnafwtgi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbrluyxc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.wangshuangyany.cn/Article/details/gtgcsoewme.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenzaomai.com/Article/details/gtifxlqwfa.html

[J09] 时区处理
来源：http://dali.xylfe.cn/Article/details/gtuoqtbtlb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cashguo.top/Article/details/gtoxxkxmfw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhongyouzk.top/Article/details/gtztxefaxd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gtvcbzscox.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtswaaeunn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.feifeiyinyue.top/Article/details/gtmhazzohk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinqigufen.top/Article/details/gtsgkuwhvu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.9152youxi.cn/Article/details/gtrjynffqu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.dashuyun.cn/Article/details/gtexwmnwie.html

[J10] 取今天 / 本月第一天
来源：http://dali.ppjwa.cn/Article/details/gtgduzwsac.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhixingplan.top/Article/details/gtdcoelbea.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hongshengwenyu.top/Article/details/gtictumrvz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxinkj.top/Article/details/gtcqriyydx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtqrlaqvnc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yuxming.cn/Article/details/gtvagpduwq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jianghu66.top/Article/details/gtwdzetgaz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnxiangtu.top/Article/details/gtejxhzmfm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zdqjudy.top/Article/details/gtjtjiorps.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtkeckiffa.html

K. JSON 与序列化
来源：http://dali.zhoulong.xyz/Article/details/gtzszclnbw.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtdtmjagbm.html

[K01] 对象转 JSON 字符串
来源：http://dali.aizwys.cn/Article/details/gtqctghpra.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yuxming.cn/Article/details/gtagcpwgiy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gzhubu.top/Article/details/gtmcuwsnst.html

JS:   JSON.stringify(obj)
来源：http://dali.sweek.top/Article/details/gtdseiaxrw.html

TS:   JSON.stringify(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtnbhmudly.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gzhubu.top/Article/details/gtlktpnaty.html

Go:   json.Marshal(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtzucumxmd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ppjwa.cn/Article/details/gthraqqvol.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmkryuwva.html

[K02] JSON 字符串转对象
来源：http://dali.quarkkingdee.top/Article/details/gtgzkckqir.html

Py:   json.loads(s)
来源：http://dali.nanxinkj.top/Article/details/gthwtcwqew.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhiwuduotai.top/Article/details/gtngickujl.html

JS:   JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gttlroxssj.html

TS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gtpsnsauxt.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gtglmfiaih.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.bjfxy.top/Article/details/gtvuzdyina.html

Ruby: JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtjaxtjogx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtuxfwujiv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258.top/Article/details/gtawtnbeqh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xinyue.icu/Article/details/gtvduaxjzi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hnqzz.top/Article/details/gtgvccwvor.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gtxocdqdpg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gtgrcgbbyq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yongpay.top/Article/details/gtedavptkx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.iojbl.cn/Article/details/gtgoajozto.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gogol.net.cn/Article/details/gthmmfkmst.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.andypj.xyz/Article/details/gtsmbwxcso.html

[K04] 读取 JSON 文件
来源：http://dali.jqgufenzy.top/Article/details/gtisjjtwpe.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yanxiufei.cn/Article/details/gthmpjubmv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xuetiantiany.cn/Article/details/gtxvafmbsl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenzaomai.com/Article/details/gtvmpaxdke.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhaoygjw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guowangkeji.top/Article/details/gttsixlwir.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gtzoweglrh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gaohongyu789.top/Article/details/gtatspftyt.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltooxhmc.html

[K05] 深拷贝对象
来源：http://dali.hnqzz.top/Article/details/gtxylmkvpz.html

Py:   copy.deepcopy(obj)
来源：http://dali.guannengcc.top/Article/details/gtiqjroeas.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sweek.top/Article/details/gtbrygyxoo.html

JS:   structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gtcubgwcrz.html

TS:   structuredClone(obj)
来源：http://dali.zdqjudy.top/Article/details/gtxzbfcxta.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.bjfxy.top/Article/details/gtmvqsnngr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.aibaodan.cn/Article/details/gtpnnpjyhk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tian-w.cn/Article/details/gtmdegqprn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jqgfzy.top/Article/details/gtpticmomn.html

[K06] 解析 URL 查询串
来源：http://dali.gaohongyu789.top/Article/details/gtgemowkxw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gzhubu.top/Article/details/gtmccnnvqb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.redwolf501.top/Article/details/gtbzxalfrw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.iojbl.cn/Article/details/gtpoqautmk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gzhubu.top/Article/details/gtvhtffjjv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.fengsongda.top/Article/details/gtdllgradm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gthafrhhfc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gtrdxfebzl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gtbyacdydo.html

[K07] 进制转换
来源：http://dali.yj20258.top/Article/details/gtgarbpdlf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtcstmywpn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnxiangtu.top/Article/details/gtulxvefqe.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtdjlaojki.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gttlookfmg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtfykvervn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ybcxt.top/Article/details/gtmfvxvsbl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.aizwys.cn/Article/details/gtuyzmkfzg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtyktxohlr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gotoacloud.top/Article/details/gtpfoshxrk.html

Py:   pickle.dumps(obj)
来源：http://dali.xziqi.cn/Article/details/gtdfmrzted.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sxryk.cn/Article/details/gtesxibzyu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.aizwys.cn/Article/details/gtgbhplfns.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cashguo.top/Article/details/gtrjorlnmu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ehwqpu.com/Article/details/gttpglkyzq.html

Go:   encoding/gob
来源：http://dali.havefunace.top/Article/details/gthpslidak.html

Ruby: Marshal.dump(obj)
来源：http://dali.xziqi.cn/Article/details/gtlsgskeoy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gtugyykbug.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtswuyyoct.html

L. 网络请求
来源：http://dali.chenjidiqi.icu/Article/details/gtpaqurrvj.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtkmukdfvk.html

[L01] 发送 GET 请求
来源：http://dali.xinyue.icu/Article/details/gtoqbfcwbq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ybcxt.top/Article/details/gtosdggbfo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinqigfzy.top/Article/details/gtzmyliqol.html

JS:   await fetch(url)
来源：http://dali.xylfe.cn/Article/details/gtorhkmjbo.html

TS:   await fetch(url)
来源：http://dali.ppjwa.cn/Article/details/gtwwogezur.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hnxiangtu.top/Article/details/gtbfcsnxma.html

Go:   resp, err := http.Get(url)
来源：http://dali.guowangkeji.top/Article/details/gtqxeqfpag.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.snrcjt.cn/Article/details/gtkxpzhtxc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hnxiangtu.top/Article/details/gteqfovxxf.html

[L02] 发送 POST JSON
来源：http://dali.tianlin.xyz/Article/details/gtuqylohnv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gtdtirmmtc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.fzhhl.top/Article/details/gtqpdfvnzx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yongpay.top/Article/details/gtzqbnmmar.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.haohaochexian.top/Article/details/gtfusmsnyo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hammf.cn/Article/details/gtlrrgrqqz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shangyingyoupin.top/Article/details/gtpdhpjewq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigfzy.top/Article/details/gtaxwntwch.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhongyouzk.top/Article/details/gtbisyfnoq.html

[L03] 设置自定义请求头
来源：http://dali.vqdsnc.cn/Article/details/gtqkalovsp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ybcxt.top/Article/details/gtfsnpsgop.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hnxiangtu.top/Article/details/gtzzldjdwz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hywenlv.cn/Article/details/gtangwysxr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shzxlz.cn/Article/details/gtowstesfy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhixingplan.top/Article/details/gtmydivgwi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gtlvkpkokr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinqigfzy.top/Article/details/gtgfxhkwxp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gtggrkkwlt.html

[L04] 设置超时
来源：http://dali.sxryk.cn/Article/details/gtklacvkck.html

Py:   requests.get(url, timeout=5)
来源：http://dali.iojbl.cn/Article/details/gtchxuvzai.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhiwuduotai.top/Article/details/gtkdtgvybt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gtyjdvbknc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebfbvhyh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shangyingyoupin.top/Article/details/gtdtjtoiro.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.vqdsnc.cn/Article/details/gtcehlillg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gaohongyu789.top/Article/details/gtcawtmdpf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sysykeji.top/Article/details/gtwgfhuffp.html

[L05] 上传文件（multipart）
来源：http://dali.yj20258888.top/Article/details/gthselgful.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.iojbl.cn/Article/details/gtpoprzrmm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gzhubu.top/Article/details/gtyvbxhobk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hywenlv.cn/Article/details/gtjesxgrmw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhixingplan.top/Article/details/gthwywqnaz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.daxiang520.top/Article/details/gtjhkcnegn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.0kj1m.cn/Article/details/gtnojwoghb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.feifeiyinyue.top/Article/details/gtjzscbhbe.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj20258888.top/Article/details/gtnqdwmpxe.html

[L06] 解析响应为 JSON
来源：http://dali.xuetiantiany.cn/Article/details/gtsneupsjm.html

Py:   resp.json()
来源：http://dali.ybcxt.top/Article/details/gtxtaapnsv.html

PHP:  json_decode($body, true);
来源：http://dali.svipenyu.cn/Article/details/gtvndgswqj.html

JS:   await resp.json()
来源：http://dali.yueranfly.top/Article/details/gtctdclyle.html

TS:   await resp.json()
来源：http://dali.hysaishi.cn/Article/details/gtvjomfswa.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gtpaqohnqd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guowangkeji.top/Article/details/gtzznmgeqi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gtcdfmuztb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.iojbl.cn/Article/details/gtvmpzjglm.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gtreicfwsg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.dianchejie.cn/Article/details/gtmvpymsxd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuxming.cn/Article/details/gtgguiqsfk.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gtifekniek.html

TS:   resp.ok;  resp.status
来源：http://dali.cheryme.top/Article/details/gtchhwhqco.html

Java: resp.statusCode()
来源：http://dali.ivvv.top/Article/details/gtlaefapdg.html

Go:   resp.StatusCode
来源：http://dali.shzxlz.cn/Article/details/gtzazvhbsb.html

Ruby: resp.code.to_i
来源：http://dali.chenjidiqi.icu/Article/details/gtvhrtjnlh.html

C#:   (int)resp.StatusCode
来源：http://dali.guannengcc.top/Article/details/gtydhbaeor.html

[L08] 并发请求多个地址
来源：http://dali.sxryk.cn/Article/details/gtyvzfegbo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cashguo.top/Article/details/gtzekvqejl.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangshuangyany.cn/Article/details/gttdlxyqpa.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gtmcpvdjgw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gtzzdileal.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.smart0.xyz/Article/details/gtrqogizzw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tian-w.cn/Article/details/gtvuvkbuzo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yvedp.cn/Article/details/gtyrpmyeqd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.pycfn.com/Article/details/gtxcaslvml.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtbmhnqvzt.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhengqikj.top/Article/details/gtafvhvfjz.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtmymdeguc.html

[M01] 读取命令行参数
来源：http://dali.jyoumei.cn/Article/details/gtoyondqbw.html

Py:   sys.argv[1:]
来源：http://dali.iojbl.cn/Article/details/gtgvlbqnak.html

PHP:  $argv;  $argc;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtigemlihf.html

JS:   process.argv.slice(2)
来源：http://dali.cheryme.top/Article/details/gtdypfefpn.html

TS:   process.argv.slice(2)
来源：http://dali.svipenyu.cn/Article/details/gtxozlyqoh.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gtvuavbudz.html

Go:   os.Args[1:]
来源：http://dali.sufxvd.cn/Article/details/gtqtpunodu.html

Ruby: ARGV
来源：http://dali.hysaishi.cn/Article/details/gtbdmjgtpd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrothgwlq.html

[M02] 读取环境变量
来源：http://dali.mhx1999.top/Article/details/gtkjcvmdlt.html

Py:   os.environ.get("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtgrialtvt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cashguo.top/Article/details/gtwetpcata.html

JS:   process.env.HOME
来源：http://dali.chenlongwang.top/Article/details/gtrfbbtbqk.html

TS:   process.env.HOME
来源：http://dali.shuidangran.top/Article/details/gtkojlaxio.html

Java: System.getenv("HOME")
来源：http://dali.aizwys.cn/Article/details/gtzxgfnoia.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gzhubu.top/Article/details/gtezbtyqtg.html

Ruby: ENV["HOME"]
来源：http://dali.fengsongda.top/Article/details/gtcgbxcard.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtgmweztpz.html

[M03] 执行外部命令
来源：http://dali.daria6918.cn/Article/details/gtxpafxpkv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yvedp.cn/Article/details/gtdckjbmuz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj202588.top/Article/details/gtkgqhbzzw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jyoumei.cn/Article/details/gtadnivhxa.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zycfv.cn/Article/details/gtgvnypihz.html


<!-- 参考信息 -->