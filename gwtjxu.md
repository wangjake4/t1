代发 wailian999

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenlongwang.top/Article/details/gt2bsmidtfl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.bjfxy.top/Article/details/gt2xuwnwwpl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gt2ydpukiuf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gt2uqzdunzu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.redwolf501.top/Article/details/gt2rweijnmr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.andypj.xyz/Article/details/gt2rydrsigh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gt2uhlglaqw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yuanzhike.top/Article/details/gt2fcgjbajj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xinyue.icu/Article/details/gt2dutruniq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gt2zhqictuq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ivvv.top/Article/details/gt2dezapbkg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ydzc1.top/Article/details/gt2oztzeufi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jyoumei.cn/Article/details/gt2ojssudzf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gt2earhlicv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenzaomai.com/Article/details/gt2ycppcfjc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj202588.top/Article/details/gt2wxwfnzmu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.birdmap.top/Article/details/gt2hazorqnn.html

[I07] 忽略大小写与多行模式
来源：http://dali.shzxlz.cn/Article/details/gt2sziujitm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ydzc1.top/Article/details/gt2xbzrqenz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhixingplan.top/Article/details/gt2ageohalx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.fzhhl.top/Article/details/gt2jauetpse.html

TS:   /error/gim
来源：http://dali.zdqjudy.top/Article/details/gt2rnguyomm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gzhubu.top/Article/details/gt2lkpmysnz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hammf.cn/Article/details/gt2qgmsycjf.html

Ruby: s.scan(/error/i)
来源：http://dali.zhongyouzk.top/Article/details/gt2yglrajfa.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aibaodan.cn/Article/details/gt2tgpdyzuq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj20258888.top/Article/details/gt2ejlweupa.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jiagoushi.top/Article/details/gt2jodrhhzi.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zdybyyli.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhengqikj.top/Article/details/gt2ejyzfyhn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gt2tlmbnicx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sysykeji.top/Article/details/gt2zzeelikk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gotoacloud.top/Article/details/gt2bdwpldxk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nanxinkj.top/Article/details/gt2iqnaldrs.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2gahbuost.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2npbytrkf.html

J. 日期与时间
来源：http://dali.ppjwa.cn/Article/details/gt2zumosbvf.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2cqwobtuy.html

[J01] 获取当前时间
来源：http://dali.ehwqpu.com/Article/details/gt2qiwxnhvu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gogol.net.cn/Article/details/gt2wgocuhwr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ppjwa.cn/Article/details/gt2rvizbeou.html

JS:   new Date();  Date.now()
来源：http://dali.yj202588.top/Article/details/gt2ahrpocbn.html

TS:   new Date();  Date.now()
来源：http://dali.xuetiantiany.cn/Article/details/gt2daruhvfn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhongyouzk.top/Article/details/gt2bpnkkiyk.html

Go:   time.Now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xzgkvxfi.html

Ruby: Time.now
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bfysynpb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.quarkkingdee.top/Article/details/gt2iiuonrux.html

[J02] 格式化输出
来源：http://dali.xuanzx.com/Article/details/gt2cbzcnyfe.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhengqikj.top/Article/details/gt2xinsiukm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jqgfzy.top/Article/details/gt2agmhdyub.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daria6918.cn/Article/details/gt2ikfboysv.html

TS:   d.toISOString()
来源：http://dali.ehwqpu.com/Article/details/gt2zmrohdse.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hfpthk.cn/Article/details/gt2hqqomjnf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenlongwang.top/Article/details/gt2fzigywoa.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhongyouzk.top/Article/details/gt2htvaanzi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.birdmap.top/Article/details/gt2zsorlvuu.html

[J03] 字符串解析为日期
来源：http://dali.dashuyun.cn/Article/details/gt2eoeqpuqc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jqgfzy.top/Article/details/gt2lgboaiqj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.bjfxy.top/Article/details/gt2yixxnilf.html

JS:   new Date("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gt2gumycxma.html

TS:   new Date("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gt2jfiemcsz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2ycxskmxi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gt2yafxfddn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gt2culcfolm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.daxiang520.top/Article/details/gt2xfsxtoyg.html

[J04] 时间戳与日期互转
来源：http://dali.mhx1999.top/Article/details/gt2dxyewsbg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xziqi.cn/Article/details/gt2pqvgehsq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ouyodeil.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daxiang520.top/Article/details/gt2lmgagbia.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgfzy.top/Article/details/gt2dqjyeyge.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cqqwz.cn/Article/details/gt2vjlvwsut.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqittfk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yuxming.cn/Article/details/gt2pxryaqgx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xinyue.icu/Article/details/gt2xcvviuza.html

[J05] 时间加减（加 7 天）
来源：http://dali.gzhubu.top/Article/details/gt2lvolvazo.html

Py:   now + timedelta(days=7)
来源：http://dali.daxiang520.top/Article/details/gt2nfzukyyt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ppjwa.cn/Article/details/gt2lybxtbhr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daria6918.cn/Article/details/gt2ydgbbhmk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258888.top/Article/details/gt2bcuflzkj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gt2yqaumhfd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guannengcc.top/Article/details/gt2dfmrvble.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yongpay.top/Article/details/gt2cqiobvsg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.snrcjt.cn/Article/details/gt2nijfdmzz.html

[J06] 计算两时间之差
来源：http://dali.jyoumei.cn/Article/details/gt2ncjucywy.html

Py:   (end - start).total_seconds()
来源：http://dali.aizwys.cn/Article/details/gt2qzgdemjl.html

PHP:  $end->diff($start)->days;
来源：http://dali.tian-w.cn/Article/details/gt2efnvwvrq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.kuanghao11.cn/Article/details/gt2vgqalzhy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hnqzz.top/Article/details/gt2sjwfesye.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sweek.top/Article/details/gt2eisvpjlf.html

Go:   end.Sub(start).Hours()
来源：http://dali.zdqjudy.top/Article/details/gt2okuqjjhk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nanxinkj.top/Article/details/gt2geezgaap.html

C#:   (end - start).TotalSeconds
来源：http://dali.hywenlv.cn/Article/details/gt2vnxosbxn.html

[J07] 比较两个日期
来源：http://dali.dianchejie.cn/Article/details/gt2ddzvjllp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gt2hksxilza.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.snrcjt.cn/Article/details/gt2jgcszzkw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhixingplan.top/Article/details/gt2xmuvxkhs.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kskuiwmw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jianghu66.top/Article/details/gt2nnthwjte.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.aizwys.cn/Article/details/gt2kubhjdmg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gt2osmqdlll.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gt2shyfhlap.html

[J08] 提取年月日与星期
来源：http://dali.hammf.cn/Article/details/gt2gqymlayb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sysykeji.top/Article/details/gt2lvnqzhqa.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gogol.net.cn/Article/details/gt2vfvjaprd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenjidiqi.icu/Article/details/gt2seagwffd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jianghu66.top/Article/details/gt2jxnmbmzm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cashguo.top/Article/details/gt2alkcpqbw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgfzy.top/Article/details/gt2ncgtnjhz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.c1oappe.top/Article/details/gt2opyfnexi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hammf.cn/Article/details/gt2ygavctle.html

[J09] 时区处理
来源：http://dali.guowangkeji.top/Article/details/gt2ironxefb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jiagoushi.top/Article/details/gt2lwrkxdre.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shzxlz.cn/Article/details/gt2wgtlsmvv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gt2fgzdlgqg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dsybghvk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sxryk.cn/Article/details/gt2yfjxmeox.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shuidangran.top/Article/details/gt2hsxvsgqf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tianlin.xyz/Article/details/gt2zhlzflot.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhongyouzk.top/Article/details/gt2kiruwcgv.html

[J10] 取今天 / 本月第一天
来源：http://dali.snrcjt.cn/Article/details/gt2ihbfkhuu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jneydvpg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.iojbl.cn/Article/details/gt2mawnjlbu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2nottwwlv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2usozentt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dianchejie.cn/Article/details/gt2dbimrrvb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.fzhhl.top/Article/details/gt2husjsawr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gaohongyu789.top/Article/details/gt2xilazosp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pijqjwwm.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2wsvmjbph.html

K. JSON 与序列化
来源：http://dali.ydzc1.top/Article/details/gt2bdqrxxdl.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2uavuvuqq.html

[K01] 对象转 JSON 字符串
来源：http://dali.cashguo.top/Article/details/gt2helrtknq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2rymaxpne.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qdrcnaeh.html

JS:   JSON.stringify(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2podubqzv.html

TS:   JSON.stringify(obj)
来源：http://dali.ydzc1.top/Article/details/gt2kefrgbfl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.bjfxy.top/Article/details/gt2whwuyboz.html

Go:   json.Marshal(obj)
来源：http://dali.cheryme.top/Article/details/gt2goocysrt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnqzz.top/Article/details/gt2ptmzmrve.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj20258888.top/Article/details/gt2zunatzsa.html

[K02] JSON 字符串转对象
来源：http://dali.ivvv.top/Article/details/gt2esaflmxj.html

Py:   json.loads(s)
来源：http://dali.cucudq.cn/Article/details/gt2lcjpjjox.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj20258.top/Article/details/gt2eitdwris.html

JS:   JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gt2hbiegyzu.html

TS:   JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gt2awnhiaaw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zycfv.cn/Article/details/gt2xhfuwyhm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.daxiang520.top/Article/details/gt2zexutmby.html

Ruby: JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gt2latzuqel.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2snhdeqxq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gzhubu.top/Article/details/gt2lvjxtiyu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj20258.top/Article/details/gt2hzaljsok.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xinyue.icu/Article/details/gt2zpldhlte.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gt2ouuuaahq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zdqjudy.top/Article/details/gt2gvkjgyew.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2zyeypvfk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.bjfxy.top/Article/details/gt2lexhjjww.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yonumen.top/Article/details/gt2godmbxfx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.wangshuangyany.cn/Article/details/gt2ponmlclq.html

[K04] 读取 JSON 文件
来源：http://dali.gogol.net.cn/Article/details/gt2vnxiydtz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2njclxmfc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jyoumei.cn/Article/details/gt2pzsisclh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2waodnolb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gt2zjwucuno.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.snrcjt.cn/Article/details/gt2bvbzfngm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.havefunace.top/Article/details/gt2lnaljpfv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ydzc1.top/Article/details/gt2xywoxgju.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kbqeersl.html

[K05] 深拷贝对象
来源：http://dali.tianlin.xyz/Article/details/gt2jqngiryw.html

Py:   copy.deepcopy(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zwzwbtmh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sufxvd.cn/Article/details/gt2frfpjukp.html

JS:   structuredClone(obj)
来源：http://dali.sxryk.cn/Article/details/gt2ycyzkrzz.html

TS:   structuredClone(obj)
来源：http://dali.cheryme.top/Article/details/gt2ilsmzawd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sysykeji.top/Article/details/gt2eoribwwz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shangyingyoupin.top/Article/details/gt2tkovlygd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.snrcjt.cn/Article/details/gt2qqpuofrx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.aibaodan.cn/Article/details/gt2xovohthj.html

[K06] 解析 URL 查询串
来源：http://dali.cqqwz.cn/Article/details/gt2awnrczma.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cheryme.top/Article/details/gt2afsjlavu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gotoacloud.top/Article/details/gt2htpskdrt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhoulong.xyz/Article/details/gt2xndtwvdt.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnxiangtu.top/Article/details/gt2onylgjwb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.haohaochexian.top/Article/details/gt2djldbtfc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mrcetkxl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gt2xnzplvsv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gt2bfuioqyj.html

[K07] 进制转换
来源：http://dali.pengpengdd.cyou/Article/details/gt2vwskvtga.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qluspoll.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sysykeji.top/Article/details/gt2jpgziskr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gt2dlarammp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gt2obkicqpa.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gt2mpkoyxkn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gaohongyu789.top/Article/details/gt2weingkhj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.iojbl.cn/Article/details/gt2rtbdapip.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gt2krlbupes.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jiagoushi.top/Article/details/gt2mqliamgf.html

Py:   pickle.dumps(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2singdqvu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2maddywih.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangshuangyany.cn/Article/details/gt2ineudvtn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ybcxt.top/Article/details/gt2gxmwvjdh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhiwuduotai.top/Article/details/gt2unmqdhql.html

Go:   encoding/gob
来源：http://dali.ppjwa.cn/Article/details/gt2fuxmpjbz.html

Ruby: Marshal.dump(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2xtnxmbgx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ahmuorqz.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2kukhjfyu.html

L. 网络请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gvpebhod.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2rooxveur.html

[L01] 发送 GET 请求
来源：http://dali.aizwys.cn/Article/details/gt2hhpsjtdg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.316326.xyz/Article/details/gt2yqunacbo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gzhubu.top/Article/details/gt2rvrsfbrc.html

JS:   await fetch(url)
来源：http://dali.sysykeji.top/Article/details/gt2kqqzbkdo.html

TS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gt2gdoksdqt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jyoumei.cn/Article/details/gt2jzfdlirz.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj20258.top/Article/details/gt2lbgqtyvf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj202588.top/Article/details/gt2wkhrhiyj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yuxming.cn/Article/details/gt2jacninkj.html

[L02] 发送 POST JSON
来源：http://dali.chenzaomai.com/Article/details/gt2qrtndngv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sweek.top/Article/details/gt2tffgcund.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gzhubu.top/Article/details/gt2hscdyicd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gt2qiiiurom.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2teuprnwj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.kuanghao11.cn/Article/details/gt2venqqgia.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.pycfn.com/Article/details/gt2uspyclsw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xziqi.cn/Article/details/gt2felcwtfy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.iojbl.cn/Article/details/gt2qsqjsuod.html

[L03] 设置自定义请求头
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xtvpsell.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj202588.top/Article/details/gt2qhkohmnk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jyoumei.cn/Article/details/gt2irzqlwss.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.snrcjt.cn/Article/details/gt2swoavlyx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fwvwxtdd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.wangshuangyany.cn/Article/details/gt2lymelxnz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dsolzdgi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.kuanghao11.cn/Article/details/gt2jqtvtknn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.daxiang520.top/Article/details/gt2ydsusjsc.html

[L04] 设置超时
来源：http://dali.redwolf501.top/Article/details/gt2uulxmbsa.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ehwqpu.com/Article/details/gt2tyltdtqk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yongpay.top/Article/details/gt2orilalgi.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hfpthk.cn/Article/details/gt2yxvwuwvl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ppjwa.cn/Article/details/gt2lwsonqcs.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xinyue.icu/Article/details/gt2fcdqnltz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangshuangyany.cn/Article/details/gt2rjfsvzpe.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.wangdashe.top/Article/details/gt2ziaqftuf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sxryk.cn/Article/details/gt2yllcnvlt.html

[L05] 上传文件（multipart）
来源：http://dali.yueranfly.top/Article/details/gt2lmzqiujd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gzhubu.top/Article/details/gt2uzumkdzq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shzxlz.cn/Article/details/gt2eaqlrvqf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.andypj.xyz/Article/details/gt2atpwwxfl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hongshengwenyu.top/Article/details/gt2abntlzhb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sweek.top/Article/details/gt2zyarjvkl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.svipenyu.cn/Article/details/gt2tspxymfo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.smart0.xyz/Article/details/gt2hvmkapgi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2sgomhfkg.html

[L06] 解析响应为 JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uwegzfbd.html

Py:   resp.json()
来源：http://dali.guowangkeji.top/Article/details/gt2jqjuygta.html

PHP:  json_decode($body, true);
来源：http://dali.jinqigfzy.top/Article/details/gt2hkrriekm.html

JS:   await resp.json()
来源：http://dali.dashuyun.cn/Article/details/gt2sxjdouuo.html

TS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gt2watufvtm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gt2ruffaitx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yonumen.top/Article/details/gt2lwqckynh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.birdmap.top/Article/details/gt2hniuwgyk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xinyue.icu/Article/details/gt2fniubcab.html

[L07] 处理 HTTP 状态码
来源：http://dali.ybcxt.top/Article/details/gt2bjkugvay.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.guannengcc.top/Article/details/gt2yuvyktse.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.pengpengdd.cyou/Article/details/gt2hiqbtrle.html

JS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gt2vyzuxfnh.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjaccab.html

Java: resp.statusCode()
来源：http://dali.xuanzx.com/Article/details/gt2rymsziis.html

Go:   resp.StatusCode
来源：http://dali.wangdashe.top/Article/details/gt2rplvustv.html

Ruby: resp.code.to_i
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cfetmqtj.html

C#:   (int)resp.StatusCode
来源：http://dali.yuanzhike.top/Article/details/gt2gzhegnlp.html

[L08] 并发请求多个地址
来源：http://dali.pycfn.com/Article/details/gt2dxsfkuyo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.c1oappe.top/Article/details/gt2xfssjuex.html

PHP:  curl_multi_init() 系列
来源：http://dali.jqgfzy.top/Article/details/gt2ktvyxeyz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gt2edfrzxlq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gt2nvclkely.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jianghu66.top/Article/details/gt2cwufwwyz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jlsjyb.cn/Article/details/gt2rlhdawkw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.quarkkingdee.top/Article/details/gt2skjtousj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aizwys.cn/Article/details/gt2ogvtrlvm.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2axdocenp.html

M. 命令行 / 进程 / 环境
来源：http://dali.yonumen.top/Article/details/gt2yaoukqpw.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2yakigiwz.html

[M01] 读取命令行参数
来源：http://dali.guannengcc.top/Article/details/gt2zkrqnxwc.html

Py:   sys.argv[1:]
来源：http://dali.mhx1999.top/Article/details/gt2bswkxthc.html

PHP:  $argv;  $argc;
来源：http://dali.feifeiyinyue.top/Article/details/gt2lghbzigh.html

JS:   process.argv.slice(2)
来源：http://dali.jqgfzy.top/Article/details/gt2gbypvawg.html

TS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gt2yapkmhrl.html

Java: args 数组（main 方法参数）
来源：http://dali.tanke756.top/Article/details/gt2thvigees.html

Go:   os.Args[1:]
来源：http://dali.ybcxt.top/Article/details/gt2mkinwuhj.html

Ruby: ARGV
来源：http://dali.nanxuanxn.top/Article/details/gt2odckqbur.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xuetiantiany.cn/Article/details/gt2ssfngikw.html

[M02] 读取环境变量
来源：http://dali.hywenlv.cn/Article/details/gt2zjwfdmqv.html

Py:   os.environ.get("HOME")
来源：http://dali.c1oappe.top/Article/details/gt2rwwngrdh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.andypj.xyz/Article/details/gt2riaxesyx.html

JS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gt2ahdotzuo.html

TS:   process.env.HOME
来源：http://dali.gotoacloud.top/Article/details/gt2ehbeaiaw.html

Java: System.getenv("HOME")
来源：http://dali.cqqwz.cn/Article/details/gt2gwiuwhpg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nanxinkj.top/Article/details/gt2hngxcxoj.html

Ruby: ENV["HOME"]
来源：http://dali.c1oappe.top/Article/details/gt2jnvnxkqj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jianghu66.top/Article/details/gt2ctsdjuuh.html

[M03] 执行外部命令
来源：http://dali.shuidangran.top/Article/details/gt2jzlicbit.html


<!-- 参考信息 -->