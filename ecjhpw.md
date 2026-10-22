代发 wailian999

Java: s.split("\\s*,\\s*")
来源：http://dali.fengsongda.top/Article/details/gt2hdijyawj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ppjwa.cn/Article/details/gt2wfwgzdfa.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gt2ualoenwq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.wangshuangyany.cn/Article/details/gt2bfeduvue.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigfzy.top/Article/details/gt2dxjyyqpd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gt2pcxfgccc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.havefunace.top/Article/details/gt2diyrbirg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fengsongda.top/Article/details/gt2kksubxjo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jgpeusqu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gt2uwilxjyf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhongyouzk.top/Article/details/gt2gpqrdqhw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.smart0.xyz/Article/details/gt2fnawmgzw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pycfn.com/Article/details/gt2ubbpvypq.html

[I07] 忽略大小写与多行模式
来源：http://dali.sysykeji.top/Article/details/gt2eeuvefoz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cucudq.cn/Article/details/gt2zqkttcmf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hammf.cn/Article/details/gt2zduyhhqo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xuanzx.com/Article/details/gt2fylwlbkz.html

TS:   /error/gim
来源：http://dali.daria6918.cn/Article/details/gt2fvhfkwho.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cucudq.cn/Article/details/gt2hjuhcyky.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shuidangran.top/Article/details/gt2hzhqithd.html

Ruby: s.scan(/error/i)
来源：http://dali.xuanzx.com/Article/details/gt2xlfxaqyk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.wangdashe.top/Article/details/gt2bpnxixvg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2gowuzxcg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gotoacloud.top/Article/details/gt2czossnxe.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gt2epxtrirr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gt2okxtbavx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.iojbl.cn/Article/details/gt2rincagmq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.andypj.xyz/Article/details/gt2xeslzdfz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cdnleiting.top/Article/details/gt2sxjltiyv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ehwqpu.com/Article/details/gt2wiiuktqf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.bjfxy.top/Article/details/gt2zdyyakxt.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2vhoqymty.html

J. 日期与时间
来源：http://dali.ydzc1.top/Article/details/gt2zaotkjhh.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2biguworl.html

[J01] 获取当前时间
来源：http://dali.shangyingyoupin.top/Article/details/gt2pcigbiqi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cucudq.cn/Article/details/gt2bnciaewz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj202588.top/Article/details/gt2jnzubule.html

JS:   new Date();  Date.now()
来源：http://dali.gzhubu.top/Article/details/gt2shbxgtbf.html

TS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gt2rwilzhrq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nwbrower.top/Article/details/gt2bqtimlhf.html

Go:   time.Now()
来源：http://dali.chenlongwang.top/Article/details/gt2gahpphwv.html

Ruby: Time.now
来源：http://dali.yueranfly.top/Article/details/gt2rmcyhdux.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yueranfly.top/Article/details/gt2ibsazgqd.html

[J02] 格式化输出
来源：http://dali.shuidangran.top/Article/details/gt2qjrsvjec.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnhvsfl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yangfankeji.com/Article/details/gt2nffdjqjk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cdnleiting.top/Article/details/gt2eieqvmbg.html

TS:   d.toISOString()
来源：http://dali.yj202588.top/Article/details/gt2liodwrgu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nwbrower.top/Article/details/gt2tnuctjuh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinqigufen.top/Article/details/gt2yryxxnlc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gt2tisopuvg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xuanzx.com/Article/details/gt2cqlhdsxw.html

[J03] 字符串解析为日期
来源：http://dali.yuanzhike.top/Article/details/gt2pxfuxcie.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tmwyjmmf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.guannengcc.top/Article/details/gt2qmzevyvx.html

JS:   new Date("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gt2batfjogb.html

TS:   new Date("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gt2pjnbjwlc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gt2gsgwrjci.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yonumen.top/Article/details/gt2ghgskrpf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gt2ekczzuop.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenzaomai.com/Article/details/gt2dafoynci.html

[J04] 时间戳与日期互转
来源：http://dali.xuetiantiany.cn/Article/details/gt2ddclrgda.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.snrcjt.cn/Article/details/gt2hddzwduz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxuanxn.top/Article/details/gt2cjlknjid.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.wangdashe.top/Article/details/gt2zziigmxq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wioczsql.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xinyue.icu/Article/details/gt2byoosdew.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.316326.xyz/Article/details/gt2ernxllot.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.andypj.xyz/Article/details/gt2cdkfcwtr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dianchejie.cn/Article/details/gt2dgnabemo.html

[J05] 时间加减（加 7 天）
来源：http://dali.zycfv.cn/Article/details/gt2rtvbjvpd.html

Py:   now + timedelta(days=7)
来源：http://dali.pycfn.com/Article/details/gt2ntukfznk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gogol.net.cn/Article/details/gt2srutltly.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xylfe.cn/Article/details/gt2giwscotd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangdashe.top/Article/details/gt2geoqczbd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.daxiang520.top/Article/details/gt2utkykngu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj20258.top/Article/details/gt2niyheade.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zycfv.cn/Article/details/gt2atblrqaf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xziqi.cn/Article/details/gt2dzstxemg.html

[J06] 计算两时间之差
来源：http://dali.316326.xyz/Article/details/gt2zohtachf.html

Py:   (end - start).total_seconds()
来源：http://dali.chenlongwang.top/Article/details/gt2hfggtwjw.html

PHP:  $end->diff($start)->days;
来源：http://dali.kuanghao11.cn/Article/details/gt2kmnrsoau.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.snrcjt.cn/Article/details/gt2rlzruyjd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ppjwa.cn/Article/details/gt2peqsqqlv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cashguo.top/Article/details/gt2nlktmosn.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj202588.top/Article/details/gt2tpmsiyvo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj20258888.top/Article/details/gt2zkkmjcsp.html

C#:   (end - start).TotalSeconds
来源：http://dali.aizwys.cn/Article/details/gt2rhwrivbi.html

[J07] 比较两个日期
来源：http://dali.jianghu66.top/Article/details/gt2qoxygqlt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gt2szfiabrx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.andypj.xyz/Article/details/gt2voejsdbu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gt2wjbvffwp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uadcwxqd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.vqdsnc.cn/Article/details/gt2tmtbgtds.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dashuyun.cn/Article/details/gt2rfjwohle.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gt2fraaxaoy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gt2oncdipsg.html

[J08] 提取年月日与星期
来源：http://dali.zycfv.cn/Article/details/gt2dagqswma.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2arnbwclm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nanxuanxn.top/Article/details/gt2jhvitnle.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.andypj.xyz/Article/details/gt2caimvxpp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj20258.top/Article/details/gt2kclqqzch.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnxiangtu.top/Article/details/gt2mlftjlok.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.smart0.xyz/Article/details/gt2envytjdk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenzaomai.com/Article/details/gt2joosipyi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fengsongda.top/Article/details/gt2auyckrpc.html

[J09] 时区处理
来源：http://dali.9152youxi.cn/Article/details/gt2ywlqhvza.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.pengpengdd.cyou/Article/details/gt2aajkgrjr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cqqwz.cn/Article/details/gt2bjfsrrua.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xziqi.cn/Article/details/gt2tqwqpzyo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnqzz.top/Article/details/gt2vsfelpbi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.havefunace.top/Article/details/gt2vyrgiect.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hssydhyy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shuidangran.top/Article/details/gt2wfwaludx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.mhx1999.top/Article/details/gt2iglzcchf.html

[J10] 取今天 / 本月第一天
来源：http://dali.sysykeji.top/Article/details/gt2xuerokfv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gaohongyu789.top/Article/details/gt2ynoylntx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.wangshuangyany.cn/Article/details/gt2kdpannyc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cucudq.cn/Article/details/gt2iehpxuke.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2igqowblj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258888.top/Article/details/gt2jnjvfawj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhoulong.xyz/Article/details/gt2afpgeynt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhixingplan.top/Article/details/gt2yrrdpfdp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yuanzhike.top/Article/details/gt2vnkewwml.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2hbkcvrtf.html

K. JSON 与序列化
来源：http://dali.9152youxi.cn/Article/details/gt2kzgtljme.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2kqjcexmu.html

[K01] 对象转 JSON 字符串
来源：http://dali.zycfv.cn/Article/details/gt2smscphap.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.haohaochexian.top/Article/details/gt2awhsjwgr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gt2zwuugibn.html

JS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2tppqcpvi.html

TS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gt2ahyoihvu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.andypj.xyz/Article/details/gt2qzfwmzlw.html

Go:   json.Marshal(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2sgcuxerh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hysaishi.cn/Article/details/gt2skqbrifx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj20258888.top/Article/details/gt2hxjboixq.html

[K02] JSON 字符串转对象
来源：http://dali.nanxuanxn.top/Article/details/gt2sxujrvkb.html

Py:   json.loads(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2kritoigf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mttlfokf.html

JS:   JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gt2wazpvhhf.html

TS:   JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gt2syhyvlnx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lmztjzct.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jjqpdekz.html

Ruby: JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dsislaqt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ppjwa.cn/Article/details/gt2qgymzwxx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.aibaodan.cn/Article/details/gt2ucaywvgt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yonumen.top/Article/details/gt2psromfbn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gt2rzavqaoo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.snrcjt.cn/Article/details/gt2kaigutni.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.316326.xyz/Article/details/gt2ipyruuxd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guannengcc.top/Article/details/gt2mqvzovfx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kpqvwdwc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jmmdshgn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yangfankeji.com/Article/details/gt2eiqybtpc.html

[K04] 读取 JSON 文件
来源：http://dali.sweek.top/Article/details/gt2oudkwmxd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.aibaodan.cn/Article/details/gt2fqeefgpz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.feifeiyinyue.top/Article/details/gt2vsxuinwu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuanzx.com/Article/details/gt2diffvdet.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dashuyun.cn/Article/details/gt2hkqqekmm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tcapfjvb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.bjfxy.top/Article/details/gt2yhigocca.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gt2zqbstrih.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.aibaodan.cn/Article/details/gt2cqaffbzq.html

[K05] 深拷贝对象
来源：http://dali.redwolf501.top/Article/details/gt2orrvgndh.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2yuzqwcaf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cucudq.cn/Article/details/gt2rwbrzpdr.html

JS:   structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2wlplmxxb.html

TS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2swwnnkpe.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.snrcjt.cn/Article/details/gt2nirbqped.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tianlin.xyz/Article/details/gt2qfpkiueb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.fzhhl.top/Article/details/gt2fxismpcf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kxdsvbnh.html

[K06] 解析 URL 查询串
来源：http://dali.jqgufenzy.top/Article/details/gt2iulbhwjc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhixingplan.top/Article/details/gt2zlqjvcji.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hammf.cn/Article/details/gt2fdfyknzq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.andypj.xyz/Article/details/gt2jenwbpia.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.feifeiyinyue.top/Article/details/gt2totkzdpj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgufenzy.top/Article/details/gt2zkdwedju.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gt2hvybeyhy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gt2hlsdzrvl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gezhsiof.html

[K07] 进制转换
来源：http://dali.fengsongda.top/Article/details/gt2evdjiapp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gt2zztfkrjv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.guowangkeji.top/Article/details/gt2cvmqmkjt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gt2scpoweqr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2ioqygipl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gt2sapyraws.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenlongwang.top/Article/details/gt2ixxraiyd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jqgufenzy.top/Article/details/gt2tbvmgosa.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kjuvxwzl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.redwolf501.top/Article/details/gt2bhxketlu.html

Py:   pickle.dumps(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2gcmkvuja.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.iojbl.cn/Article/details/gt2jprbozge.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gt2ypzqeeop.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bikecmse.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hongshengwenyu.top/Article/details/gt2mnegqzui.html

Go:   encoding/gob
来源：http://dali.quarkkingdee.top/Article/details/gt2qrusnpxu.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ctwllcoe.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gt2mfwsryrp.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2oircfrdi.html

L. 网络请求
来源：http://dali.pycfn.com/Article/details/gt2gdsgeljy.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2fgdwtydc.html

[L01] 发送 GET 请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lwdkehrh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj202588.top/Article/details/gt2kymqsivm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.0kj1m.cn/Article/details/gt2xlwqgtjy.html

JS:   await fetch(url)
来源：http://dali.ivvv.top/Article/details/gt2umolvbkr.html

TS:   await fetch(url)
来源：http://dali.jianghu66.top/Article/details/gt2apxpczkm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.316326.xyz/Article/details/gt2ccpxstic.html

Go:   resp, err := http.Get(url)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hivzugze.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnxiangtu.top/Article/details/gt2xwlscgay.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinqigufen.top/Article/details/gt2yaswguxc.html

[L02] 发送 POST JSON
来源：http://dali.jyoumei.cn/Article/details/gt2ecxgrwkx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhengqikj.top/Article/details/gt2fudhanwo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.dashuyun.cn/Article/details/gt2cugaegdp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yvedp.cn/Article/details/gt2vdgfoqvd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gt2wxxmmqtx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangdashe.top/Article/details/gt2tvykvpex.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nanxinkj.top/Article/details/gt2ngevzfcy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhongyouzk.top/Article/details/gt2uvyycfka.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.haohaochexian.top/Article/details/gt2cpxobmlw.html

[L03] 设置自定义请求头
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sudqgopt.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xziqi.cn/Article/details/gt2vsfkecdp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xinyue.icu/Article/details/gt2hggfjdtd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gt2bcximwrn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangshuangyany.cn/Article/details/gt2qamdptov.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.haohaochexian.top/Article/details/gt2vhtemapj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sysykeji.top/Article/details/gt2iuiqdfix.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gogol.net.cn/Article/details/gt2vybcarwa.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jlsjyb.cn/Article/details/gt2dzxdyrzu.html

[L04] 设置超时
来源：http://dali.wangdashe.top/Article/details/gt2ghnxxdys.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yanxiufei.cn/Article/details/gt2dkbhkoxn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.snrcjt.cn/Article/details/gt2rvqdnwgu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.snrcjt.cn/Article/details/gt2maapwbcl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sysykeji.top/Article/details/gt2sutdsola.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lgajzgjo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yuxming.cn/Article/details/gt2nwweykch.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.316326.xyz/Article/details/gt2kcelzlna.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj20258.top/Article/details/gt2tbvsjlqh.html

[L05] 上传文件（multipart）
来源：http://dali.shuidangran.top/Article/details/gt2rpeeysws.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tanke756.top/Article/details/gt2uvmgjamf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.aizwys.cn/Article/details/gt2pxvnjawb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ppjwa.cn/Article/details/gt2mglerjzm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gt2pdhlmnin.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xuetiantiany.cn/Article/details/gt2maxrnppt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gogol.net.cn/Article/details/gt2dhvzgxtx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shangyingyoupin.top/Article/details/gt2ihmrzkml.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2mpskgtfo.html

[L06] 解析响应为 JSON
来源：http://dali.zhoulong.xyz/Article/details/gt2ktweditk.html

Py:   resp.json()
来源：http://dali.aizwys.cn/Article/details/gt2fzrzwhbx.html

PHP:  json_decode($body, true);
来源：http://dali.hysaishi.cn/Article/details/gt2fzkwzhjq.html

JS:   await resp.json()
来源：http://dali.birdmap.top/Article/details/gt2bxjsbuua.html

TS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gt2tzckusxx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gt2hwhkrzgc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yonumen.top/Article/details/gt2dbahebim.html

Ruby: JSON.parse(resp.body)
来源：http://dali.pycfn.com/Article/details/gt2iavppkvh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ivvv.top/Article/details/gt2brahsucp.html

[L07] 处理 HTTP 状态码
来源：http://dali.gogol.net.cn/Article/details/gt2xjcpjiov.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jlsjyb.cn/Article/details/gt2dtvintuf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yangfankeji.com/Article/details/gt2bvjlmazr.html

JS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gt2ejxllkgb.html

TS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gt2rfplmrwx.html

Java: resp.statusCode()
来源：http://dali.yongpay.top/Article/details/gt2vyvxxbnk.html

Go:   resp.StatusCode
来源：http://dali.pengpengdd.cyou/Article/details/gt2qvcprimx.html

Ruby: resp.code.to_i
来源：http://dali.yanxiufei.cn/Article/details/gt2qaqllhji.html

C#:   (int)resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gt2qgklooop.html

[L08] 并发请求多个地址
来源：http://dali.ydzc1.top/Article/details/gt2isctkaxa.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhoulong.xyz/Article/details/gt2pquzzlwx.html

PHP:  curl_multi_init() 系列
来源：http://dali.hongshengwenyu.top/Article/details/gt2ljimlorl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gt2ihotvnpb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gt2dvzzemwx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cqqwz.cn/Article/details/gt2fwojqyha.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.redwolf501.top/Article/details/gt2uappyjcl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shuidangran.top/Article/details/gt2tsnaosyg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xziqi.cn/Article/details/gt2vhdklaru.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2zrqlgsjx.html

M. 命令行 / 进程 / 环境
来源：http://dali.meibo888.top/Article/details/gt2njqiavuz.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2kprakldb.html

[M01] 读取命令行参数
来源：http://dali.haohaochexian.top/Article/details/gt2luxeobyq.html

Py:   sys.argv[1:]
来源：http://dali.jiagoushi.top/Article/details/gt2nzociwbs.html

PHP:  $argv;  $argc;
来源：http://dali.nanxuanxn.top/Article/details/gt2ktfdfjbx.html

JS:   process.argv.slice(2)
来源：http://dali.xziqi.cn/Article/details/gt2ciicemly.html

TS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gt2xbmfwdod.html

Java: args 数组（main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ztyozott.html

Go:   os.Args[1:]
来源：http://dali.ydzc1.top/Article/details/gt2bvjppxwl.html

Ruby: ARGV
来源：http://dali.zycfv.cn/Article/details/gt2ohzhkodd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.andypj.xyz/Article/details/gt2pzziykaq.html

[M02] 读取环境变量
来源：http://dali.yj20258.top/Article/details/gt2cchowjij.html

Py:   os.environ.get("HOME")
来源：http://dali.yj20258.top/Article/details/gt2iwjuhyla.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gt2irrfqotj.html

JS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jiomssyp.html

TS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gt2apjuhmcn.html

Java: System.getenv("HOME")
来源：http://dali.shuidangran.top/Article/details/gt2ixgkkmtc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.guannengcc.top/Article/details/gt2lakrybcs.html

Ruby: ENV["HOME"]
来源：http://dali.sufxvd.cn/Article/details/gt2fetyyqbh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.316326.xyz/Article/details/gt2lrpdcmee.html

[M03] 执行外部命令
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pvvzmsgs.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.dianchejie.cn/Article/details/gt2aobqdjpp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jiagoushi.top/Article/details/gt2ybakbgmx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yonumen.top/Article/details/gt2ecmfbhdq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hammf.cn/Article/details/gt2uuktypcc.html


<!-- 参考信息 -->