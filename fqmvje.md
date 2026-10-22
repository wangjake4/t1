代发 wailian999

Java: s.split("\\s*,\\s*")
来源：http://dali.zhongyouzk.top/Article/details/gt2ufdveqbm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yonumen.top/Article/details/gt2bdszolvq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gt2zcezrdzj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gotoacloud.top/Article/details/gt2yxuebruc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hammf.cn/Article/details/gt2wdwyaywl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gt2hbutmnmc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nwbrower.top/Article/details/gt2xcbercuh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dianchejie.cn/Article/details/gt2xtobgoan.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sxryk.cn/Article/details/gt2hksinokq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gt2olqpeobe.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cheryme.top/Article/details/gt2wxkfoefk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nanxuanxn.top/Article/details/gt2odmxtbrf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gt2tpqucfxw.html

[I07] 忽略大小写与多行模式
来源：http://dali.fengsongda.top/Article/details/gt2ixhmibpt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tanke756.top/Article/details/gt2zmdphran.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinqigfzy.top/Article/details/gt2txsryghx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jianghu66.top/Article/details/gt2apnmjovg.html

TS:   /error/gim
来源：http://dali.chenjidiqi.icu/Article/details/gt2tyyeyokv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.vqdsnc.cn/Article/details/gt2rpbpbvfw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dashuyun.cn/Article/details/gt2dbecezve.html

Ruby: s.scan(/error/i)
来源：http://dali.gotoacloud.top/Article/details/gt2adptphxc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ksvncepy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yvedp.cn/Article/details/gt2stpwkxvu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhengqikj.top/Article/details/gt2vjrpkcui.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.meibo888.top/Article/details/gt2ofabpxhw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sxryk.cn/Article/details/gt2odpzrhjy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guannengcc.top/Article/details/gt2cfdggspr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cucudq.cn/Article/details/gt2mjhkouwb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xylfe.cn/Article/details/gt2xxewrqgk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jyoumei.cn/Article/details/gt2lqoftyaw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.fengsongda.top/Article/details/gt2cfvzwsxa.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2psvuthvv.html

J. 日期与时间
来源：http://dali.yanxiufei.cn/Article/details/gt2ayxtsmac.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2sskvubgs.html

[J01] 获取当前时间
来源：http://dali.sweek.top/Article/details/gt2axrkiwtx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jianghu66.top/Article/details/gt2fftfehie.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gt2zyxkuedm.html

JS:   new Date();  Date.now()
来源：http://dali.aizwys.cn/Article/details/gt2vookhxhu.html

TS:   new Date();  Date.now()
来源：http://dali.smart0.xyz/Article/details/gt2zrjrcjbk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.smart0.xyz/Article/details/gt2vpninsnu.html

Go:   time.Now()
来源：http://dali.meibo888.top/Article/details/gt2kmlgglew.html

Ruby: Time.now
来源：http://dali.zhixingplan.top/Article/details/gt2undmotvp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj20258888.top/Article/details/gt2gmuqkkgj.html

[J02] 格式化输出
来源：http://dali.bjfxy.top/Article/details/gt2javpdxwm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pycfn.com/Article/details/gt2iugllaxl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jlsjyb.cn/Article/details/gt2sabxbyyr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.quarkkingdee.top/Article/details/gt2igyvkudx.html

TS:   d.toISOString()
来源：http://dali.sxryk.cn/Article/details/gt2xatstqmb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.birdmap.top/Article/details/gt2mvfkfktt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.guannengcc.top/Article/details/gt2fhnppghi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.redwolf501.top/Article/details/gt2euasrotf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.c1oappe.top/Article/details/gt2moantyrm.html

[J03] 字符串解析为日期
来源：http://dali.xziqi.cn/Article/details/gt2oczgggaq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.svipenyu.cn/Article/details/gt2wrtrzixw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.aizwys.cn/Article/details/gt2iwkugxfx.html

JS:   new Date("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2bxpbnfbt.html

TS:   new Date("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gt2ccalhypj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gt2aexbhzwa.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.pycfn.com/Article/details/gt2chjslhnp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2ptlcqzif.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2owdqyeqm.html

[J04] 时间戳与日期互转
来源：http://dali.bjfxy.top/Article/details/gt2gbfgfody.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhoulong.xyz/Article/details/gt2ksqeymzq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yuxming.cn/Article/details/gt2lpxbcprg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj202588.top/Article/details/gt2dfnkgzdv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.wangdashe.top/Article/details/gt2vhudgyru.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hywenlv.cn/Article/details/gt2dortlrkt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2vyzxjizf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ydzc1.top/Article/details/gt2ehqkrjhu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ppjwa.cn/Article/details/gt2ekmpxlxh.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgfzy.top/Article/details/gt2ekdmywnq.html

Py:   now + timedelta(days=7)
来源：http://dali.0kj1m.cn/Article/details/gt2jrcjoabi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.smart0.xyz/Article/details/gt2petnkmjq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.smart0.xyz/Article/details/gt2pljrxmgs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nwbrower.top/Article/details/gt2afjuekpz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yuxming.cn/Article/details/gt2xetavcde.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.bjfxy.top/Article/details/gt2sxifjtwm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.redwolf501.top/Article/details/gt2xdvvhxsq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gt2jroojftw.html

[J06] 计算两时间之差
来源：http://dali.andypj.xyz/Article/details/gt2goeyruld.html

Py:   (end - start).total_seconds()
来源：http://dali.0kj1m.cn/Article/details/gt2shsrrezc.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2salbjmyj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nanxinkj.top/Article/details/gt2yskjtdnl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fzhhl.top/Article/details/gt2haasqeft.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.svipenyu.cn/Article/details/gt2hgryjotk.html

Go:   end.Sub(start).Hours()
来源：http://dali.redwolf501.top/Article/details/gt2bpihcrsn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.vqdsnc.cn/Article/details/gt2makqjwjd.html

C#:   (end - start).TotalSeconds
来源：http://dali.xylfe.cn/Article/details/gt2tuizwwou.html

[J07] 比较两个日期
来源：http://dali.fengsongda.top/Article/details/gt2hwmgvoal.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gt2ldubzxjc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnqzz.top/Article/details/gt2sgmtbocg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gt2odzfuoag.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gt2mipekamm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jianghu66.top/Article/details/gt2gbhbbtbl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lmipfbdz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gt2wvlxvefr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gt2hprrqkyt.html

[J08] 提取年月日与星期
来源：http://dali.svipenyu.cn/Article/details/gt2xelnxqjf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgfzy.top/Article/details/gt2ilwyinqs.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xinyue.icu/Article/details/gt2agejletf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jlsjyb.cn/Article/details/gt2kebnbkyf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yaaejiax.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nfwvaygh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hhnzlnsr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ybcxt.top/Article/details/gt2bplzoeyz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xinyue.icu/Article/details/gt2iznstvcc.html

[J09] 时区处理
来源：http://dali.dianchejie.cn/Article/details/gt2gtnyrwsa.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aidusiko.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pengpengdd.cyou/Article/details/gt2ckizmvlt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daxiang520.top/Article/details/gt2aeodakwn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yanxiufei.cn/Article/details/gt2nmnvlxwq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xziqi.cn/Article/details/gt2rzelebrr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.andypj.xyz/Article/details/gt2hvfekbnx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sufxvd.cn/Article/details/gt2ifgimwjs.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sysykeji.top/Article/details/gt2xvkiaflk.html

[J10] 取今天 / 本月第一天
来源：http://dali.cucudq.cn/Article/details/gt2wipuxoox.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.aizwys.cn/Article/details/gt2tilruixq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jyoumei.cn/Article/details/gt2axfibrsd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ehwqpu.com/Article/details/gt2dmccndbl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnqzz.top/Article/details/gt2fxkrkdjg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cucudq.cn/Article/details/gt2mmfgcalf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.bjfxy.top/Article/details/gt2uupqqkhg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jlsjyb.cn/Article/details/gt2gkqhcrye.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2srvsvffm.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2zjrasntu.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtupscb.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2egxebrbb.html

[K01] 对象转 JSON 字符串
来源：http://dali.jqgfzy.top/Article/details/gt2hfifxuqi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xylfe.cn/Article/details/gt2cjfclbul.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hywenlv.cn/Article/details/gt2lcruyfnq.html

JS:   JSON.stringify(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2gzyszdky.html

TS:   JSON.stringify(obj)
来源：http://dali.bjfxy.top/Article/details/gt2opbecpmf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.0kj1m.cn/Article/details/gt2saeaetzv.html

Go:   json.Marshal(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tsbxjjoy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hongshengwenyu.top/Article/details/gt2lbzagnaz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gzhubu.top/Article/details/gt2dolkvwod.html

[K02] JSON 字符串转对象
来源：http://dali.tanke756.top/Article/details/gt2typwnigi.html

Py:   json.loads(s)
来源：http://dali.c1oappe.top/Article/details/gt2hiskfjdb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.iojbl.cn/Article/details/gt2otjxpaxr.html

JS:   JSON.parse(s)
来源：http://dali.birdmap.top/Article/details/gt2risowyrz.html

TS:   JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gt2oiqstcwz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yvedp.cn/Article/details/gt2vmjkqtuo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gt2bwelzrxu.html

Ruby: JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gt2nlljlumc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xinyue.icu/Article/details/gt2wfwlhwel.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yueranfly.top/Article/details/gt2gezuuwpy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2shwqdwnu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gt2pfypzjug.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gt2rsysmmeu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2owgvkvzk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shuidangran.top/Article/details/gt2uormnqsj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jlsjyb.cn/Article/details/gt2sowxnvqa.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cashguo.top/Article/details/gt2ymyqsbvk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yonumen.top/Article/details/gt2vyesxppa.html

[K04] 读取 JSON 文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wxqnwwvd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.andypj.xyz/Article/details/gt2qbzpwyup.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.quarkkingdee.top/Article/details/gt2ycwzsexs.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.mhx1999.top/Article/details/gt2njvtpgiv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gt2aimhultt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pycfn.com/Article/details/gt2qkfepksa.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ppjwa.cn/Article/details/gt2cxavbtky.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.iojbl.cn/Article/details/gt2hegbviyn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnxiangtu.top/Article/details/gt2hkczuvfn.html

[K05] 深拷贝对象
来源：http://dali.meibo888.top/Article/details/gt2achqnbkv.html

Py:   copy.deepcopy(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2clyegvpj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cheryme.top/Article/details/gt2rwzpsubv.html

JS:   structuredClone(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2fcklizrm.html

TS:   structuredClone(obj)
来源：http://dali.yvedp.cn/Article/details/gt2fqpkhusd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shuidangran.top/Article/details/gt2ticduwwl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jqgfzy.top/Article/details/gt2rckpwrgx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yanxiufei.cn/Article/details/gt2ciidpzqo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.svipenyu.cn/Article/details/gt2uhmqyntl.html

[K06] 解析 URL 查询串
来源：http://dali.chenzaomai.com/Article/details/gt2teehktfr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gt2ijpaizrv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pyjnpfnm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhiwuduotai.top/Article/details/gt2yakwxisf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gogol.net.cn/Article/details/gt2hakjymaw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tpyxwqqx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gt2xejdwvod.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gt2nhvamwhm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gt2wtwrkuyx.html

[K07] 进制转换
来源：http://dali.jqgufenzy.top/Article/details/gt2uireeaiq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gt2wwrublpi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zycfv.cn/Article/details/gt2lycafszb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gt2oshynmpg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2giekkxqv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gt2nzccxxwd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.svipenyu.cn/Article/details/gt2ctuqyzez.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daria6918.cn/Article/details/gt2owhitrvx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2blydgmic.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jlsjyb.cn/Article/details/gt2lggrbwaw.html

Py:   pickle.dumps(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2aoaxcecr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hammf.cn/Article/details/gt2vqxttqdt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.pengpengdd.cyou/Article/details/gt2vvjmzdth.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gt2gyldszki.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mqzazyhp.html

Go:   encoding/gob
来源：http://dali.yj20258.top/Article/details/gt2yguvysgf.html

Ruby: Marshal.dump(obj)
来源：http://dali.yueranfly.top/Article/details/gt2cgofoapy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gt2gqyobidi.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qrxjmpdy.html

L. 网络请求
来源：http://dali.xziqi.cn/Article/details/gt2kefsqfex.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2dfagdwbj.html

[L01] 发送 GET 请求
来源：http://dali.jianghu66.top/Article/details/gt2ygslshyb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cucudq.cn/Article/details/gt2mrfhxxmo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenjidiqi.icu/Article/details/gt2yloutkth.html

JS:   await fetch(url)
来源：http://dali.yj20258.top/Article/details/gt2rpdoorny.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgypruka.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xuanzx.com/Article/details/gt2jjaxnlew.html

Go:   resp, err := http.Get(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ifcrsvxt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shuidangran.top/Article/details/gt2tuntvsrr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ppjwa.cn/Article/details/gt2dpttfnlh.html

[L02] 发送 POST JSON
来源：http://dali.yanxiufei.cn/Article/details/gt2nrnkqqyd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gotoacloud.top/Article/details/gt2hyvtxvle.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhixingplan.top/Article/details/gt2muqrtjgr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ogmcegbc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.feifeiyinyue.top/Article/details/gt2dudkihkh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangshuangyany.cn/Article/details/gt2egdmmqos.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gotoacloud.top/Article/details/gt2ihqzmwmy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.fzhhl.top/Article/details/gt2levksyht.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aizwys.cn/Article/details/gt2ayblghzv.html

[L03] 设置自定义请求头
来源：http://dali.jinqigfzy.top/Article/details/gt2qikghvix.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hnxiangtu.top/Article/details/gt2nmhrxtzl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dianchejie.cn/Article/details/gt2ywkvjniz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pgetyefo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnxiangtu.top/Article/details/gt2ekzfsfxx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cqqwz.cn/Article/details/gt2acxupvpr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuanzhike.top/Article/details/gt2unsmlqvl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ppjwa.cn/Article/details/gt2ahbukson.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.dianchejie.cn/Article/details/gt2mkablvjq.html

[L04] 设置超时
来源：http://dali.zhiwuduotai.top/Article/details/gt2oswxlghr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jlsjyb.cn/Article/details/gt2tywofldu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.mhx1999.top/Article/details/gt2ldikteyr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gt2mafdygbg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxinkj.top/Article/details/gt2lgurtsit.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhiwuduotai.top/Article/details/gt2suquyski.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.aizwys.cn/Article/details/gt2prhgwedn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhiwuduotai.top/Article/details/gt2bugrofbs.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jqgfzy.top/Article/details/gt2ebfrxssx.html

[L05] 上传文件（multipart）
来源：http://dali.yj20258888.top/Article/details/gt2iuchwurz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.9152youxi.cn/Article/details/gt2xwauxbnf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.0kj1m.cn/Article/details/gt2opophddj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjktnwk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ehwqpu.com/Article/details/gt2afszeode.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhengqikj.top/Article/details/gt2vumsadzs.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cashguo.top/Article/details/gt2vmnlcwdg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ydzc1.top/Article/details/gt2dbnzqlnf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.havefunace.top/Article/details/gt2thkvpzcn.html

[L06] 解析响应为 JSON
来源：http://dali.zhongyouzk.top/Article/details/gt2gttrkiiz.html

Py:   resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gt2gkflkgvh.html

PHP:  json_decode($body, true);
来源：http://dali.gogol.net.cn/Article/details/gt2lulxjkhl.html

JS:   await resp.json()
来源：http://dali.tianlin.xyz/Article/details/gt2nqwmqxty.html

TS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gt2ucktvbmb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnqzz.top/Article/details/gt2sabtsscy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.snrcjt.cn/Article/details/gt2vuffalsj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.birdmap.top/Article/details/gt2zgkjukhs.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nhgvlsgy.html

[L07] 处理 HTTP 状态码
来源：http://dali.jlsjyb.cn/Article/details/gt2jkcripwi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cucudq.cn/Article/details/gt2vuydzfik.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ppjwa.cn/Article/details/gt2uwoahwlm.html

JS:   resp.ok;  resp.status
来源：http://dali.jyoumei.cn/Article/details/gt2hjjpubij.html

TS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gt2iedcqvwg.html

Java: resp.statusCode()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2njzudazk.html

Go:   resp.StatusCode
来源：http://dali.ehwqpu.com/Article/details/gt2ustiqmfm.html

Ruby: resp.code.to_i
来源：http://dali.guannengcc.top/Article/details/gt2wkfdjooc.html

C#:   (int)resp.StatusCode
来源：http://dali.zdqjudy.top/Article/details/gt2uwdovqls.html

[L08] 并发请求多个地址
来源：http://dali.vqdsnc.cn/Article/details/gt2lgyctpdv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.quarkkingdee.top/Article/details/gt2iwltokbm.html

PHP:  curl_multi_init() 系列
来源：http://dali.svipenyu.cn/Article/details/gt2coghkutc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gt2qppoyaeg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gt2vmupreiq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yonumen.top/Article/details/gt2igjmduvb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.mhx1999.top/Article/details/gt2qjbinjob.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj202588.top/Article/details/gt2zodwhcap.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.guowangkeji.top/Article/details/gt2xxbegiax.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2uecjmhhl.html

M. 命令行 / 进程 / 环境
来源：http://dali.svipenyu.cn/Article/details/gt2msrsjetj.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2ysycdxwu.html

[M01] 读取命令行参数
来源：http://dali.jinqigfzy.top/Article/details/gt2jkhxuxyz.html

Py:   sys.argv[1:]
来源：http://dali.jlsjyb.cn/Article/details/gt2xplphajb.html

PHP:  $argv;  $argc;
来源：http://dali.zhoulong.xyz/Article/details/gt2ynatgqrc.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gt2xtnkphgw.html

TS:   process.argv.slice(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uovgbbzb.html

Java: args 数组（main 方法参数）
来源：http://dali.hongshengwenyu.top/Article/details/gt2poenqagd.html

Go:   os.Args[1:]
来源：http://dali.cdnleiting.top/Article/details/gt2ebuchovw.html

Ruby: ARGV
来源：http://dali.wangshuangyany.cn/Article/details/gt2wfgcqhbk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.quarkkingdee.top/Article/details/gt2twqbggfu.html

[M02] 读取环境变量
来源：http://dali.ivvv.top/Article/details/gt2ddfjcudx.html

Py:   os.environ.get("HOME")
来源：http://dali.daxiang520.top/Article/details/gt2ksgrbofu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gt2lbdzdwmu.html

JS:   process.env.HOME
来源：http://dali.jinqigufen.top/Article/details/gt2upmiigir.html

TS:   process.env.HOME
来源：http://dali.aibaodan.cn/Article/details/gt2wbumvqow.html

Java: System.getenv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gt2jajasjdl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jianghu66.top/Article/details/gt2delzchub.html

Ruby: ENV["HOME"]
来源：http://dali.gzhubu.top/Article/details/gt2vmzlswgv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gt2snzilydj.html

[M03] 执行外部命令
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oftrkffc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pengpengdd.cyou/Article/details/gt2whxzlflv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yonumen.top/Article/details/gt2exmrgaay.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gzhubu.top/Article/details/gt2ouvnynyf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uvjjrpfh.html


<!-- 参考信息 -->