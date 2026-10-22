代发 wailian999

Java: s.split("\\s*,\\s*")
来源：http://dali.tianlin.xyz/Article/details/gt2ylxqozce.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hfpthk.cn/Article/details/gt2ckwryfqw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gt2fjjbllmh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenjidiqi.icu/Article/details/gt2vkirnimk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cashguo.top/Article/details/gt2cleyeymd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gt2wmtnsgvy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gaohongyu789.top/Article/details/gt2fzsqepyr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gt2lpnqtzzy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vqxpobde.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gt2brixyafq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuanzx.com/Article/details/gt2gpvjmpdm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hnxiangtu.top/Article/details/gt2vjossuoy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pycfn.com/Article/details/gt2ixpueali.html

[I07] 忽略大小写与多行模式
来源：http://dali.ydzc1.top/Article/details/gt2semwidhm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cqqwz.cn/Article/details/gt2ritiugrs.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.pengpengdd.cyou/Article/details/gt2dhnqbxeu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.aizwys.cn/Article/details/gt2fqtqzamc.html

TS:   /error/gim
来源：http://dali.zhixingplan.top/Article/details/gt2zgzajyte.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sweek.top/Article/details/gt2eelqbull.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gogol.net.cn/Article/details/gt2rlhfkprq.html

Ruby: s.scan(/error/i)
来源：http://dali.daria6918.cn/Article/details/gt2ttxbrlvm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.0kj1m.cn/Article/details/gt2jxtsxutk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nwvfymxa.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jyoumei.cn/Article/details/gt2nhecpjou.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.bjfxy.top/Article/details/gt2tevveyfb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.svipenyu.cn/Article/details/gt2ozqjtcfr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.vqdsnc.cn/Article/details/gt2dpsxnltm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinqigfzy.top/Article/details/gt2qauvhjmn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xziqi.cn/Article/details/gt2zsvmgzor.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gotoacloud.top/Article/details/gt2anfjdwvr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.dashuyun.cn/Article/details/gt2klvpwtgx.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2rrvzhjpz.html

J. 日期与时间
来源：http://dali.havefunace.top/Article/details/gt2eeqjhgrn.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2kfigpdxs.html

[J01] 获取当前时间
来源：http://dali.yuanzhike.top/Article/details/gt2mbkbqdoy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.birdmap.top/Article/details/gt2zaojvdxb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.tianlin.xyz/Article/details/gt2nnnwbohd.html

JS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gt2rllkadzy.html

TS:   new Date();  Date.now()
来源：http://dali.jqgfzy.top/Article/details/gt2iotwbtln.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tpnasfgw.html

Go:   time.Now()
来源：http://dali.zdqjudy.top/Article/details/gt2tqignzde.html

Ruby: Time.now
来源：http://dali.zhengqikj.top/Article/details/gt2cduzypgt.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tian-w.cn/Article/details/gt2aaknmphh.html

[J02] 格式化输出
来源：http://dali.yangfankeji.com/Article/details/gt2wfgcaumw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lrqbdrek.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.birdmap.top/Article/details/gt2hulhughe.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhiwuduotai.top/Article/details/gt2pbtzdfqb.html

TS:   d.toISOString()
来源：http://dali.dashuyun.cn/Article/details/gt2rvaebylh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.feifeiyinyue.top/Article/details/gt2vzfbvinb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.feifeiyinyue.top/Article/details/gt2raemyjyp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gt2chayjtzl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jqgfzy.top/Article/details/gt2mmcdqwnw.html

[J03] 字符串解析为日期
来源：http://dali.tanke756.top/Article/details/gt2labxpxpp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jlsjyb.cn/Article/details/gt2pwpntoma.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.daria6918.cn/Article/details/gt2hgimhwas.html

JS:   new Date("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kmxujyzv.html

TS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gt2azjwslbh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gt2sgazrdzj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gt2rwrqqpje.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gt2byfousvq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gotoacloud.top/Article/details/gt2zungbjic.html

[J04] 时间戳与日期互转
来源：http://dali.kuanghao11.cn/Article/details/gt2mbdomdld.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shuidangran.top/Article/details/gt2alolpfiu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yuxming.cn/Article/details/gt2zyyqchtg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daxiang520.top/Article/details/gt2avkwbytr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yuxming.cn/Article/details/gt2yxabmprc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2zmfsjtjr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xylfe.cn/Article/details/gt2nmudfxap.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gt2daxuvtan.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj202588.top/Article/details/gt2cvvfderp.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhengqikj.top/Article/details/gt2mregtglw.html

Py:   now + timedelta(days=7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2anjlddzw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.9152youxi.cn/Article/details/gt2ryprbros.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fzhhl.top/Article/details/gt2obsytxcf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gt2lwuiedtf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinqigfzy.top/Article/details/gt2scbwbosr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qcjjprvv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ivvv.top/Article/details/gt2pqrdgnsh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj20258888.top/Article/details/gt2xcfraqen.html

[J06] 计算两时间之差
来源：http://dali.chenlongwang.top/Article/details/gt2qqpdxqyc.html

Py:   (end - start).total_seconds()
来源：http://dali.jyoumei.cn/Article/details/gt2bczycrap.html

PHP:  $end->diff($start)->days;
来源：http://dali.tanke756.top/Article/details/gt2tipscwrc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.snrcjt.cn/Article/details/gt2bieqfuzp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fzhhl.top/Article/details/gt2awtaepqa.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hfpthk.cn/Article/details/gt2jjjnwcoo.html

Go:   end.Sub(start).Hours()
来源：http://dali.mhx1999.top/Article/details/gt2omqzklvv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aibaodan.cn/Article/details/gt2ladhsvhu.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhoulong.xyz/Article/details/gt2ihhlwhjm.html

[J07] 比较两个日期
来源：http://dali.tianlin.xyz/Article/details/gt2qeiwjmzp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gt2qqibafki.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenzaomai.com/Article/details/gt2vzjddeei.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gaohongyu789.top/Article/details/gt2egctsgjq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigfzy.top/Article/details/gt2sbvzscif.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ybcxt.top/Article/details/gt2yhvufkij.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cashguo.top/Article/details/gt2hpvhnywl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gt2oavwdbck.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gt2citmljnd.html

[J08] 提取年月日与星期
来源：http://dali.yj20258888.top/Article/details/gt2pxqhmxhm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.c1oappe.top/Article/details/gt2odoqfoua.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ppjwa.cn/Article/details/gt2vchtneaq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuanzhike.top/Article/details/gt2mlzcjnox.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yonumen.top/Article/details/gt2ahebczec.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.birdmap.top/Article/details/gt2ighrdglw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fzhhl.top/Article/details/gt2ucpgyryk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yanxiufei.cn/Article/details/gt2jnjqmatb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ivvv.top/Article/details/gt2uenksblz.html

[J09] 时区处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbppsmy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mcrsqwzf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jianghu66.top/Article/details/gt2uxgbdlmo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gt2qjjcplzn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ljatkbuq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.0kj1m.cn/Article/details/gt2ruszwpzw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vbwihyne.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.kuanghao11.cn/Article/details/gt2qmsjdwom.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aizwys.cn/Article/details/gt2jyhqyqmy.html

[J10] 取今天 / 本月第一天
来源：http://dali.sysykeji.top/Article/details/gt2tejpajyk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zdqjudy.top/Article/details/gt2eqvadwio.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.iojbl.cn/Article/details/gt2xzxenhah.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfryktc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2gtapteez.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gotoacloud.top/Article/details/gt2ekbvsyns.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuetiantiany.cn/Article/details/gt2ktthpmtu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ybcxt.top/Article/details/gt2jsirtpno.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2psndtfku.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2btkmpngv.html

K. JSON 与序列化
来源：http://dali.gaohongyu789.top/Article/details/gt2ypyqricr.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2zkfyaayz.html

[K01] 对象转 JSON 字符串
来源：http://dali.svipenyu.cn/Article/details/gt2jzudvtef.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gt2ujmftqak.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.redwolf501.top/Article/details/gt2ulzomgte.html

JS:   JSON.stringify(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gwwajvuh.html

TS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gt2xswivucc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.snrcjt.cn/Article/details/gt2nzedgysg.html

Go:   json.Marshal(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2qomukhrt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shuidangran.top/Article/details/gt2ujrbkrxw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.bjfxy.top/Article/details/gt2wpjafips.html

[K02] JSON 字符串转对象
来源：http://dali.jlsjyb.cn/Article/details/gt2greslvox.html

Py:   json.loads(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2eemrauxm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hongshengwenyu.top/Article/details/gt2xbeuymyv.html

JS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gt2putcfzvy.html

TS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gt2luyaqrow.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jiagoushi.top/Article/details/gt2kjlgomyh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gt2ehybeipy.html

Ruby: JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gt2hivopmpw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hammf.cn/Article/details/gt2hqeypzbv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.redwolf501.top/Article/details/gt2nkryvsis.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cucudq.cn/Article/details/gt2tztezohv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sufxvd.cn/Article/details/gt2czzizszx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gt2zkmjwkba.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.316326.xyz/Article/details/gt2cxkkuoiu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yvedp.cn/Article/details/gt2pdsvtgyk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gogol.net.cn/Article/details/gt2syykbkez.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xziqi.cn/Article/details/gt2ceqrahcn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ebitwyid.html

[K04] 读取 JSON 文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2dyaglpbr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zycfv.cn/Article/details/gt2johxogmz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ydzc1.top/Article/details/gt2xsgmyvxu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gt2kmogsiao.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.kuanghao11.cn/Article/details/gt2rfgbeoju.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj202588.top/Article/details/gt2lcscghxa.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hammf.cn/Article/details/gt2rxdanovs.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jqgfzy.top/Article/details/gt2rxpapgcx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shzxlz.cn/Article/details/gt2pqqjwkoj.html

[K05] 深拷贝对象
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zrouqocb.html

Py:   copy.deepcopy(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2kcywnksb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yuanzhike.top/Article/details/gt2nonzvgcn.html

JS:   structuredClone(obj)
来源：http://dali.xinyue.icu/Article/details/gt2ajdzargj.html

TS:   structuredClone(obj)
来源：http://dali.tian-w.cn/Article/details/gt2mugzdbvx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.smart0.xyz/Article/details/gt2akkoyjfb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.aibaodan.cn/Article/details/gt2jdlumvjz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.daxiang520.top/Article/details/gt2dbtrdylt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cqqwz.cn/Article/details/gt2vzeelqon.html

[K06] 解析 URL 查询串
来源：http://dali.nanxinkj.top/Article/details/gt2qxwhzamf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.iojbl.cn/Article/details/gt2nnqyhxht.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.birdmap.top/Article/details/gt2iatcoqnc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuetiantiany.cn/Article/details/gt2caufkekh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guannengcc.top/Article/details/gt2levgjzrt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gzhubu.top/Article/details/gt2bpegbztb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gt2jcvhfios.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gt2xwlrxfga.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gt2umemcolg.html

[K07] 进制转换
来源：http://dali.hnxiangtu.top/Article/details/gt2vihpvufe.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2evedfbem.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yangfankeji.com/Article/details/gt2mkkcxnrh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gt2cylzxvik.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gt2cmzujjmf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eyjbnpcn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.kuanghao11.cn/Article/details/gt2ncwlmabo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenzaomai.com/Article/details/gt2wuhlkftu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2eqxzbsgs.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nanxinkj.top/Article/details/gt2qeqobzly.html

Py:   pickle.dumps(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2ymjyoaug.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yuanzhike.top/Article/details/gt2cnjmkatu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.snrcjt.cn/Article/details/gt2iygtvqko.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gt2klnujzug.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.feifeiyinyue.top/Article/details/gt2dgoguugj.html

Go:   encoding/gob
来源：http://dali.tanke756.top/Article/details/gt2dmutopfx.html

Ruby: Marshal.dump(obj)
来源：http://dali.guannengcc.top/Article/details/gt2gkahvfhk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.birdmap.top/Article/details/gt2lwktcfkc.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2dzmdijsf.html

L. 网络请求
来源：http://dali.jinghuilouyu.cn/Article/details/gt2asxapdgn.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2dfwkhtxc.html

[L01] 发送 GET 请求
来源：http://dali.316326.xyz/Article/details/gt2unupjyyv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cdnleiting.top/Article/details/gt2fekbligz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jlsjyb.cn/Article/details/gt2rgvmbvxf.html

JS:   await fetch(url)
来源：http://dali.hnxiangtu.top/Article/details/gt2qjlvyfzd.html

TS:   await fetch(url)
来源：http://dali.xinyue.icu/Article/details/gt2aystyjbp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.quarkkingdee.top/Article/details/gt2pytkagqo.html

Go:   resp, err := http.Get(url)
来源：http://dali.guannengcc.top/Article/details/gt2iasbodyv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ehwqpu.com/Article/details/gt2ghorpjjk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hysaishi.cn/Article/details/gt2eztxpebi.html

[L02] 发送 POST JSON
来源：http://dali.shzxlz.cn/Article/details/gt2jgbjnosp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhoulong.xyz/Article/details/gt2tzqrcvhn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ehwqpu.com/Article/details/gt2pzxdjiep.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gt2xujrcclx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shuidangran.top/Article/details/gt2jrlziutj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xmklntqi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.iojbl.cn/Article/details/gt2snaoozpb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xuanzx.com/Article/details/gt2ywxdppix.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guannengcc.top/Article/details/gt2nwcqsntt.html

[L03] 设置自定义请求头
来源：http://dali.nanxinkj.top/Article/details/gt2bbrnfank.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gotoacloud.top/Article/details/gt2wiwkhkto.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.iojbl.cn/Article/details/gt2hkeccgiw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.iojbl.cn/Article/details/gt2gwexwcxb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gt2egcxarti.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.snrcjt.cn/Article/details/gt2xwywafxg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.316326.xyz/Article/details/gt2ymomumpa.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gtdmteuz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.daria6918.cn/Article/details/gt2fzwdnzeh.html

[L04] 设置超时
来源：http://dali.snrcjt.cn/Article/details/gt2egelnozg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dashuyun.cn/Article/details/gt2mrebzzjk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ewdukiuv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.9152youxi.cn/Article/details/gt2atozudjg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnxiangtu.top/Article/details/gt2nqcdjyrt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.316326.xyz/Article/details/gt2cesahcus.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2suqlwusf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gotoacloud.top/Article/details/gt2zmpbmlqk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hongshengwenyu.top/Article/details/gt2jxohabde.html

[L05] 上传文件（multipart）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gtgjwjrd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.dianchejie.cn/Article/details/gt2xcyryzfj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258.top/Article/details/gt2oscvckhc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yfghmuuu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tianlin.xyz/Article/details/gt2wozxalgz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gogol.net.cn/Article/details/gt2mecztivr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhoulong.xyz/Article/details/gt2mgcjsctz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj20258.top/Article/details/gt2nemfhxsr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2zqaztgug.html

[L06] 解析响应为 JSON
来源：http://dali.cashguo.top/Article/details/gt2zaprduud.html

Py:   resp.json()
来源：http://dali.bjfxy.top/Article/details/gt2xaxxbsno.html

PHP:  json_decode($body, true);
来源：http://dali.cheryme.top/Article/details/gt2ytgjaqsc.html

JS:   await resp.json()
来源：http://dali.cashguo.top/Article/details/gt2bgzfxrry.html

TS:   await resp.json()
来源：http://dali.cheryme.top/Article/details/gt2jvvpjcfj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ppjwa.cn/Article/details/gt2srowmbqe.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj20258888.top/Article/details/gt2fslrdmbf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hywenlv.cn/Article/details/gt2kcgkzpuh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ppjwa.cn/Article/details/gt2ddsbkhpx.html

[L07] 处理 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gt2azvlkxop.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258888.top/Article/details/gt2djhjxogx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.0kj1m.cn/Article/details/gt2wefvoibr.html

JS:   resp.ok;  resp.status
来源：http://dali.yuxming.cn/Article/details/gt2yxvjmtfs.html

TS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gt2psrppiss.html

Java: resp.statusCode()
来源：http://dali.yongpay.top/Article/details/gt2jzsotgce.html

Go:   resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gt2orzvfyit.html

Ruby: resp.code.to_i
来源：http://dali.yj20258.top/Article/details/gt2sajqgwvw.html

C#:   (int)resp.StatusCode
来源：http://dali.ydzc1.top/Article/details/gt2dvpklcxn.html

[L08] 并发请求多个地址
来源：http://dali.yvedp.cn/Article/details/gt2qwdfwada.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jianghu66.top/Article/details/gt2iozmfrvu.html

PHP:  curl_multi_init() 系列
来源：http://dali.bjfxy.top/Article/details/gt2xmjybgpl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bskaejgh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gt2wkqmluzj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hnxiangtu.top/Article/details/gt2nqdfudkn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xuanzx.com/Article/details/gt2emakpegk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.birdmap.top/Article/details/gt2xjchoram.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.meibo888.top/Article/details/gt2rbdnbtqd.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2sepewasu.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenzaomai.com/Article/details/gt2kboiiosl.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2wncxytsm.html

[M01] 读取命令行参数
来源：http://dali.pycfn.com/Article/details/gt2omfpxspp.html

Py:   sys.argv[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gt2xhrkpgko.html

PHP:  $argv;  $argc;
来源：http://dali.cheryme.top/Article/details/gt2hmzahumt.html

JS:   process.argv.slice(2)
来源：http://dali.aizwys.cn/Article/details/gt2ljclovld.html

TS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gt2keezlheg.html

Java: args 数组（main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gt2vxbqaxfv.html

Go:   os.Args[1:]
来源：http://dali.hysaishi.cn/Article/details/gt2xrhcrrpx.html

Ruby: ARGV
来源：http://dali.jinqigfzy.top/Article/details/gt2jidcgcvv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yonumen.top/Article/details/gt2yfjizjhp.html

[M02] 读取环境变量
来源：http://dali.yj202588.top/Article/details/gt2imwaiswp.html

Py:   os.environ.get("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2rcrsxwfa.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zdqjudy.top/Article/details/gt2mmzuyifm.html

JS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gt2tjjmdmqo.html

TS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gt2lbzocxog.html

Java: System.getenv("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2wuadvbjq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.guowangkeji.top/Article/details/gt2pjjwelfa.html

Ruby: ENV["HOME"]
来源：http://dali.xuanzx.com/Article/details/gt2csojvrvq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yangfankeji.com/Article/details/gt2xbjscfgc.html

[M03] 执行外部命令
来源：http://dali.sufxvd.cn/Article/details/gt2pynxxyhl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vbbginze.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.iojbl.cn/Article/details/gt2dpzpxkai.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2whbgorju.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.guannengcc.top/Article/details/gt2gmjkhlfn.html


<!-- 参考信息 -->