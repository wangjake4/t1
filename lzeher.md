代发 wailian999

Java: s.split("\\s*,\\s*")
来源：http://dali.nwbrower.top/Article/details/gt2vhsffcda.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gt2aweberwf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2oaahauci.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.havefunace.top/Article/details/gt2mbplrhai.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.andypj.xyz/Article/details/gt2wvkxxrhx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gt2hmaduuuh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tian-w.cn/Article/details/gt2kazlezea.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.smart0.xyz/Article/details/gt2zmoedihq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.smart0.xyz/Article/details/gt2lewcbido.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gt2pozvoqfc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gleuqiwm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hfpthk.cn/Article/details/gt2ypjbihip.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gt2lzxggqgw.html

[I07] 忽略大小写与多行模式
来源：http://dali.snrcjt.cn/Article/details/gt2cnladflk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dgvuwbsz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.birdmap.top/Article/details/gt2hyoyeapr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258888.top/Article/details/gt2iugoqcwk.html

TS:   /error/gim
来源：http://dali.yj20258888.top/Article/details/gt2yvlnecxe.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.daxiang520.top/Article/details/gt2ccllpowy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jianghu66.top/Article/details/gt2otuovwoh.html

Ruby: s.scan(/error/i)
来源：http://dali.daria6918.cn/Article/details/gt2kiyxncrz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenlongwang.top/Article/details/gt2etqlyqdb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shuidangran.top/Article/details/gt2pwsfbjrm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ppjwa.cn/Article/details/gt2kmsuzyta.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qzfyrcgr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhoulong.xyz/Article/details/gt2yyvphhjh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gt2adbljkdt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hongshengwenyu.top/Article/details/gt2fdvvssfh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hysaishi.cn/Article/details/gt2jrqebuwo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hnqzz.top/Article/details/gt2xqefboun.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kixwltgt.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2tfwrmaoy.html

J. 日期与时间
来源：http://dali.yangfankeji.com/Article/details/gt2tliwmcnm.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2fjurjoat.html

[J01] 获取当前时间
来源：http://dali.cucudq.cn/Article/details/gt2jpfpwzbh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ppjwa.cn/Article/details/gt2hkwdtcha.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pycfn.com/Article/details/gt2noadqscb.html

JS:   new Date();  Date.now()
来源：http://dali.jyoumei.cn/Article/details/gt2tytrvoni.html

TS:   new Date();  Date.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2djjghiue.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.fengsongda.top/Article/details/gt2wnsbkbot.html

Go:   time.Now()
来源：http://dali.gogol.net.cn/Article/details/gt2hzgilbvj.html

Ruby: Time.now
来源：http://dali.jianghu66.top/Article/details/gt2xoztrngy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nanxinkj.top/Article/details/gt2vbecjemo.html

[J02] 格式化输出
来源：http://dali.9152youxi.cn/Article/details/gt2ymkccnch.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gt2vxudnekv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ncrfjpmu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qrgyukow.html

TS:   d.toISOString()
来源：http://dali.jiagoushi.top/Article/details/gt2ofjsnjhx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhongyouzk.top/Article/details/gt2hddqjgpo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yanxiufei.cn/Article/details/gt2lgeglsuj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guannengcc.top/Article/details/gt2lqkjkfld.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhoulong.xyz/Article/details/gt2pquzvwtn.html

[J03] 字符串解析为日期
来源：http://dali.wangshuangyany.cn/Article/details/gt2vafqruxh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xuanzx.com/Article/details/gt2aokhdiot.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yangfankeji.com/Article/details/gt2tucutbtv.html

JS:   new Date("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gt2phhczpwf.html

TS:   new Date("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gt2nqaqsxwx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gt2hynugpxx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cashguo.top/Article/details/gt2exmxfvau.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gt2hzywllgp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.fzhhl.top/Article/details/gt2hxfguuyt.html

[J04] 时间戳与日期互转
来源：http://dali.hnxiangtu.top/Article/details/gt2bupmuhdr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenlongwang.top/Article/details/gt2dejqwqek.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cashguo.top/Article/details/gt2mdrbnciv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hywenlv.cn/Article/details/gt2gaxwpoql.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.dianchejie.cn/Article/details/gt2sxfsvqgc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinqigufen.top/Article/details/gt2tvkzdzie.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2npwyzfvt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinqigufen.top/Article/details/gt2sxaixheu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xwvpfued.html

[J05] 时间加减（加 7 天）
来源：http://dali.wangdashe.top/Article/details/gt2ykzmbilt.html

Py:   now + timedelta(days=7)
来源：http://dali.fzhhl.top/Article/details/gt2sbgfuxxi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.snrcjt.cn/Article/details/gt2zsevssye.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gt2isbjywlc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sufxvd.cn/Article/details/gt2lhkimwyj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhengqikj.top/Article/details/gt2rprqwsru.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxinkj.top/Article/details/gt2nomrfssf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.316326.xyz/Article/details/gt2placrfss.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ckudiwdu.html

[J06] 计算两时间之差
来源：http://dali.tian-w.cn/Article/details/gt2weetbkrr.html

Py:   (end - start).total_seconds()
来源：http://dali.aizwys.cn/Article/details/gt2wrtoqkdw.html

PHP:  $end->diff($start)->days;
来源：http://dali.sufxvd.cn/Article/details/gt2mxemaqou.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nzicahge.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jlsjyb.cn/Article/details/gt2ajxncnxn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yangfankeji.com/Article/details/gt2hnfgnvgr.html

Go:   end.Sub(start).Hours()
来源：http://dali.cashguo.top/Article/details/gt2zkmxhyuj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.daxiang520.top/Article/details/gt2xnfpftar.html

C#:   (end - start).TotalSeconds
来源：http://dali.cucudq.cn/Article/details/gt2imbwbjmx.html

[J07] 比较两个日期
来源：http://dali.cucudq.cn/Article/details/gt2cyobuadg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gt2tjrjzgye.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nwbrower.top/Article/details/gt2nxdbedlz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gt2ntsnnzwm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258888.top/Article/details/gt2tpnoyskq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ybcxt.top/Article/details/gt2cusimwet.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258888.top/Article/details/gt2dboiatrt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gt2fuybkpev.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gt2cuhvyjky.html

[J08] 提取年月日与星期
来源：http://dali.gaohongyu789.top/Article/details/gt2xnogzwmq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yueranfly.top/Article/details/gt2fqimnijw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gzhubu.top/Article/details/gt2lsxvdwoz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dovbscsf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hywenlv.cn/Article/details/gt2uezkloao.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.svipenyu.cn/Article/details/gt2kwepyhgh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cheryme.top/Article/details/gt2ejmhxeyb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.svipenyu.cn/Article/details/gt2slmqfzrq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fzhhl.top/Article/details/gt2jjyuhpqx.html

[J09] 时区处理
来源：http://dali.feifeiyinyue.top/Article/details/gt2sdxbdyrk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sxryk.cn/Article/details/gt2vfqcqssi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yonumen.top/Article/details/gt2obkavlar.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jlsjyb.cn/Article/details/gt2uptqfycc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gt2wfrfmpoh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ehwqpu.com/Article/details/gt2ojtjskwm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sxryk.cn/Article/details/gt2lvfyyovl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ctqklgue.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daxiang520.top/Article/details/gt2tmlkhpfq.html

[J10] 取今天 / 本月第一天
来源：http://dali.daria6918.cn/Article/details/gt2kunoglhm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.kuanghao11.cn/Article/details/gt2fizwbxqj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.0kj1m.cn/Article/details/gt2kjexqzet.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.pycfn.com/Article/details/gt2vijmrupr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.0kj1m.cn/Article/details/gt2tptvvdsz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cdnleiting.top/Article/details/gt2qppcxqur.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhixingplan.top/Article/details/gt2gvjoqobe.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xylfe.cn/Article/details/gt2yoitvjmv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xinyue.icu/Article/details/gt2pymqnort.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2yheijpgk.html

K. JSON 与序列化
来源：http://dali.chenjidiqi.icu/Article/details/gt2yvykzliz.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2fjtvorzm.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhixingplan.top/Article/details/gt2lxgzxymh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.haohaochexian.top/Article/details/gt2eaikkaku.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zdqjudy.top/Article/details/gt2bztftzwv.html

JS:   JSON.stringify(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2cldoymbv.html

TS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gt2hsoovowv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xziqi.cn/Article/details/gt2bugvkduu.html

Go:   json.Marshal(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2zlejnktt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.fzhhl.top/Article/details/gt2uheyxsap.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2pjmcyexd.html

[K02] JSON 字符串转对象
来源：http://dali.yuanzhike.top/Article/details/gt2palkdahd.html

Py:   json.loads(s)
来源：http://dali.fengsongda.top/Article/details/gt2kwpguzdq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jqgfzy.top/Article/details/gt2uxqvthlf.html

JS:   JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gt2uaybkxdu.html

TS:   JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2xkroblwy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gt2qguvawey.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gt2djetkept.html

Ruby: JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gt2xjoeybkn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sxryk.cn/Article/details/gt2eezgarvv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daria6918.cn/Article/details/gt2vhcyzocv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2puvogxdj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gt2genraqdd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2athtrabm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.aibaodan.cn/Article/details/gt2jrbdzdtn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.mhx1999.top/Article/details/gt2iwvqpbev.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ehwqpu.com/Article/details/gt2pejzagta.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ndcxoqmy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.dashuyun.cn/Article/details/gt2zoclnxzb.html

[K04] 读取 JSON 文件
来源：http://dali.xuanzx.com/Article/details/gt2uysitnjf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cucudq.cn/Article/details/gt2wjvcfldf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangshuangyany.cn/Article/details/gt2qchyfhig.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.andypj.xyz/Article/details/gt2fubvpljv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gt2bdbwpmpv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sufxvd.cn/Article/details/gt2jppqaxre.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.dashuyun.cn/Article/details/gt2gvhibgak.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj202588.top/Article/details/gt2kjkbdezb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gotoacloud.top/Article/details/gt2caykmrov.html

[K05] 深拷贝对象
来源：http://dali.gaohongyu789.top/Article/details/gt2srrgicjt.html

Py:   copy.deepcopy(obj)
来源：http://dali.ivvv.top/Article/details/gt2upiqkadx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.redwolf501.top/Article/details/gt2xphqsbil.html

JS:   structuredClone(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2kjgldvrp.html

TS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gt2psbnywiz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenlongwang.top/Article/details/gt2sfeoprxu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yanxiufei.cn/Article/details/gt2ggquhptr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nanxinkj.top/Article/details/gt2lbwiskul.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cucudq.cn/Article/details/gt2lzjtbaxz.html

[K06] 解析 URL 查询串
来源：http://dali.mhx1999.top/Article/details/gt2kszvlltn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yanxiufei.cn/Article/details/gt2lirkknny.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.daxiang520.top/Article/details/gt2vwnoplzj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gt2afvxiodp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gt2ytbrdswb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yuanzhike.top/Article/details/gt2xyhlvcrq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gt2dmfnfcpa.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gt2ljjretsv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gt2jnbgleuh.html

[K07] 进制转换
来源：http://dali.jiagoushi.top/Article/details/gt2ifdortyi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gt2kdibwwtr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xinyue.icu/Article/details/gt2yjnjsdbj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gt2qfaxhwki.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gt2encefeni.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gt2pypdonsf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.havefunace.top/Article/details/gt2afsrmwcm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2bjjcujdg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gt2tjtspnkb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ydzc1.top/Article/details/gt2cqcjcihc.html

Py:   pickle.dumps(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2zjvtkavx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gzhubu.top/Article/details/gt2dbesxrzs.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jlsjyb.cn/Article/details/gt2xnjoxswc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gt2ruwdyxah.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.guowangkeji.top/Article/details/gt2swmvjmgn.html

Go:   encoding/gob
来源：http://dali.nanxuanxn.top/Article/details/gt2nwtbogej.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2puxwcasu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gt2hgtzepxu.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2jyktjfsr.html

L. 网络请求
来源：http://dali.zhiwuduotai.top/Article/details/gt2hihhuumj.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2lyysvsar.html

[L01] 发送 GET 请求
来源：http://dali.tanke756.top/Article/details/gt2mqaitlhh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yanxiufei.cn/Article/details/gt2egjtcyqc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.guannengcc.top/Article/details/gt2syoyiusv.html

JS:   await fetch(url)
来源：http://dali.gogol.net.cn/Article/details/gt2ldpltveh.html

TS:   await fetch(url)
来源：http://dali.tian-w.cn/Article/details/gt2vnvcvpwr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jiagoushi.top/Article/details/gt2kgraufpt.html

Go:   resp, err := http.Get(url)
来源：http://dali.xylfe.cn/Article/details/gt2ndttjjms.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhoulong.xyz/Article/details/gt2qzhsixqs.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.meibo888.top/Article/details/gt2llevhwxv.html

[L02] 发送 POST JSON
来源：http://dali.mhx1999.top/Article/details/gt2rwjjdhot.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jianghu66.top/Article/details/gt2xijjcoaw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.iojbl.cn/Article/details/gt2hjejhpua.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fzhhl.top/Article/details/gt2pkhtlfrr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pengpengdd.cyou/Article/details/gt2yvxlnpav.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jqgufenzy.top/Article/details/gt2wwgimosr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cucudq.cn/Article/details/gt2icnxjmbc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sweek.top/Article/details/gt2iaxffcvc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.svipenyu.cn/Article/details/gt2snhotnim.html

[L03] 设置自定义请求头
来源：http://dali.ppjwa.cn/Article/details/gt2wzibdltq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gwwxhspz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.daxiang520.top/Article/details/gt2teqrpqtc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jlsjyb.cn/Article/details/gt2wuqvzumg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.vqdsnc.cn/Article/details/gt2qxfvyoaz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cqqwz.cn/Article/details/gt2kilcaghz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pycfn.com/Article/details/gt2lsdfbtwz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxinkj.top/Article/details/gt2uaiwwjuk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.pycfn.com/Article/details/gt2szdfsmel.html

[L04] 设置超时
来源：http://dali.birdmap.top/Article/details/gt2onimvcwd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.aibaodan.cn/Article/details/gt2jwhwwrco.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hammf.cn/Article/details/gt2cqhgfksz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gt2umzxxjlw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hywenlv.cn/Article/details/gt2xkqwadwd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenzaomai.com/Article/details/gt2rhpyffiw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenjidiqi.icu/Article/details/gt2bsoowdcw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ehwqpu.com/Article/details/gt2amsdahrg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tianlin.xyz/Article/details/gt2mlxqdrgr.html

[L05] 上传文件（multipart）
来源：http://dali.guannengcc.top/Article/details/gt2pnyfhjtg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cdnleiting.top/Article/details/gt2hplacnrf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xziqi.cn/Article/details/gt2uphcaxox.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.aizwys.cn/Article/details/gt2pjzbvwfq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.smart0.xyz/Article/details/gt2pvxokeby.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zycfv.cn/Article/details/gt2hbdbrwel.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.bjfxy.top/Article/details/gt2bfjqyjln.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj20258888.top/Article/details/gt2zmhymdmo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2qieetpwc.html

[L06] 解析响应为 JSON
来源：http://dali.hywenlv.cn/Article/details/gt2vwblufly.html

Py:   resp.json()
来源：http://dali.zycfv.cn/Article/details/gt2zyhherbf.html

PHP:  json_decode($body, true);
来源：http://dali.snrcjt.cn/Article/details/gt2brbnkgym.html

JS:   await resp.json()
来源：http://dali.smart0.xyz/Article/details/gt2dtavplku.html

TS:   await resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gt2psqnniwh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yueranfly.top/Article/details/gt2yxwbtijf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.mhx1999.top/Article/details/gt2jwgolzix.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qrpsscxo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aizwys.cn/Article/details/gt2srknjozu.html

[L07] 处理 HTTP 状态码
来源：http://dali.nanxuanxn.top/Article/details/gt2avyghgdo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yanxiufei.cn/Article/details/gt2litlhkkq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xziqi.cn/Article/details/gt2ujpckdel.html

JS:   resp.ok;  resp.status
来源：http://dali.xziqi.cn/Article/details/gt2zvhhwhre.html

TS:   resp.ok;  resp.status
来源：http://dali.yvedp.cn/Article/details/gt2perkwunh.html

Java: resp.statusCode()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xeqtohep.html

Go:   resp.StatusCode
来源：http://dali.cashguo.top/Article/details/gt2yfdenird.html

Ruby: resp.code.to_i
来源：http://dali.iojbl.cn/Article/details/gt2ztknluat.html

C#:   (int)resp.StatusCode
来源：http://dali.quarkkingdee.top/Article/details/gt2qouvnjfs.html

[L08] 并发请求多个地址
来源：http://dali.andypj.xyz/Article/details/gt2izrgbabm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xziqi.cn/Article/details/gt2oomkujrn.html

PHP:  curl_multi_init() 系列
来源：http://dali.dianchejie.cn/Article/details/gt2mkmzfsll.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gt2bhitwuny.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gt2ldmfcovp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.iojbl.cn/Article/details/gt2smbgeoii.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nwbrower.top/Article/details/gt2bnwqmvsi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fzhhl.top/Article/details/gt2hpfqsmgy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cashguo.top/Article/details/gt2yifivcvu.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2zmmzjvtn.html

M. 命令行 / 进程 / 环境
来源：http://dali.hnxiangtu.top/Article/details/gt2wpmewpxb.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2bjkmoham.html

[M01] 读取命令行参数
来源：http://dali.bjfxy.top/Article/details/gt2bfcbrbyt.html

Py:   sys.argv[1:]
来源：http://dali.yonumen.top/Article/details/gt2ubhmrzco.html

PHP:  $argv;  $argc;
来源：http://dali.xuetiantiany.cn/Article/details/gt2dfwaaoku.html

JS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gt2uddunlcp.html

TS:   process.argv.slice(2)
来源：http://dali.wangdashe.top/Article/details/gt2wrpxwzgm.html

Java: args 数组（main 方法参数）
来源：http://dali.xinyue.icu/Article/details/gt2amydjqum.html

Go:   os.Args[1:]
来源：http://dali.daxiang520.top/Article/details/gt2xyvwqqiu.html

Ruby: ARGV
来源：http://dali.yj20258.top/Article/details/gt2xonivcui.html

C#:   args 数组（Main 方法参数）
来源：http://dali.daxiang520.top/Article/details/gt2tpqqhtai.html

[M02] 读取环境变量
来源：http://dali.andypj.xyz/Article/details/gt2upfoafui.html

Py:   os.environ.get("HOME")
来源：http://dali.jianghu66.top/Article/details/gt2ytsjdfay.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gt2aepooefl.html

JS:   process.env.HOME
来源：http://dali.chenzaomai.com/Article/details/gt2qpxrxnpp.html

TS:   process.env.HOME
来源：http://dali.316326.xyz/Article/details/gt2opemqudp.html

Java: System.getenv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gt2ckovvdqb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gt2kjzywfxa.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2zzekurwf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cqqwz.cn/Article/details/gt2tjpalbrs.html

[M03] 执行外部命令
来源：http://dali.sufxvd.cn/Article/details/gt2irdfhytn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yuxming.cn/Article/details/gt2popdlmld.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.0kj1m.cn/Article/details/gt2ssvdqeeo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hywenlv.cn/Article/details/gt2glwqxywl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gt2kiryevnj.html


<!-- 参考信息 -->