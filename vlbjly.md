代发 wailian999

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.feifeiyinyue.top/Article/details/gt2hqlrjqlg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gt2kdaamwvw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shzxlz.cn/Article/details/gt2jodrzigw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yvedp.cn/Article/details/gt2goqbspec.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gt2rtllgmyf.html

[I07] 忽略大小写与多行模式
来源：http://dali.gogol.net.cn/Article/details/gt2sbvpyibl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj202588.top/Article/details/gt2vjfoprzr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gt2hbyolgrz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.meibo888.top/Article/details/gt2wxnagcnv.html

TS:   /error/gim
来源：http://dali.hywenlv.cn/Article/details/gt2tvavogcu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ybcxt.top/Article/details/gt2rokqaytt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dpgsvnlt.html

Ruby: s.scan(/error/i)
来源：http://dali.andypj.xyz/Article/details/gt2rehwfeld.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ivvv.top/Article/details/gt2jbihfuho.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj20258888.top/Article/details/gt2skadgfmp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.pengpengdd.cyou/Article/details/gt2gbqvyagk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tanke756.top/Article/details/gt2yjlqwoar.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gt2kgfqsbqs.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zycfv.cn/Article/details/gt2myruriqn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hfpthk.cn/Article/details/gt2dupqrttp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hammf.cn/Article/details/gt2tvkenqqa.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dftuhode.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.iojbl.cn/Article/details/gt2sessphef.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2mhwpbyqb.html

J. 日期与时间
来源：http://dali.ydzc1.top/Article/details/gt2qjvdlsbo.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2itjwplzi.html

[J01] 获取当前时间
来源：http://dali.vqdsnc.cn/Article/details/gt2xzokhddl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2btgljrox.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nwbrower.top/Article/details/gt2phtkcymj.html

JS:   new Date();  Date.now()
来源：http://dali.cqqwz.cn/Article/details/gt2wuxywupd.html

TS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gt2lanukoil.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.kuanghao11.cn/Article/details/gt2nzjfniij.html

Go:   time.Now()
来源：http://dali.sweek.top/Article/details/gt2xmwvaqyw.html

Ruby: Time.now
来源：http://dali.wangdashe.top/Article/details/gt2rbqxbxrm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.haohaochexian.top/Article/details/gt2suekjlel.html

[J02] 格式化输出
来源：http://dali.sweek.top/Article/details/gt2afpidvmw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gt2jodwgvol.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gt2ixludzxt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.pengpengdd.cyou/Article/details/gt2mpnbuhjf.html

TS:   d.toISOString()
来源：http://dali.yj20258.top/Article/details/gt2ibvdjakc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hywenlv.cn/Article/details/gt2mdkohdiz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gt2swhvdyxi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gt2ylqjhfyq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.andypj.xyz/Article/details/gt2zyljgzzg.html

[J03] 字符串解析为日期
来源：http://dali.iojbl.cn/Article/details/gt2fpkndbrs.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ehwqpu.com/Article/details/gt2qkzxqfjo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258888.top/Article/details/gt2efcthtmy.html

JS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gt2qrvojpov.html

TS:   new Date("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gt2dqanhuwc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gt2kawwoenb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj20258.top/Article/details/gt2ihhsqnex.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gt2innaqtoz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.smart0.xyz/Article/details/gt2nuxxvier.html

[J04] 时间戳与日期互转
来源：http://dali.tian-w.cn/Article/details/gt2qjhxyjfn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.daria6918.cn/Article/details/gt2omesiqfa.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenlongwang.top/Article/details/gt2miyfqshd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.svipenyu.cn/Article/details/gt2nlaxxpuv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj202588.top/Article/details/gt2joudtqbr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gt2emlndhsx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2hrzhxvyt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj20258888.top/Article/details/gt2dhxyqyhe.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenlongwang.top/Article/details/gt2wheqonye.html

[J05] 时间加减（加 7 天）
来源：http://dali.daxiang520.top/Article/details/gt2drjrxjsz.html

Py:   now + timedelta(days=7)
来源：http://dali.yvedp.cn/Article/details/gt2kyjxgwty.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sufxvd.cn/Article/details/gt2yfbrgudm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxuanxn.top/Article/details/gt2qgpgfblh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tianlin.xyz/Article/details/gt2wdfgxxoa.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.havefunace.top/Article/details/gt2antvjppv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dxhwmrub.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jiagoushi.top/Article/details/gt2cfprywum.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.haohaochexian.top/Article/details/gt2rileeskl.html

[J06] 计算两时间之差
来源：http://dali.daxiang520.top/Article/details/gt2wrzfnign.html

Py:   (end - start).total_seconds()
来源：http://dali.smart0.xyz/Article/details/gt2kcgyuqxv.html

PHP:  $end->diff($start)->days;
来源：http://dali.meibo888.top/Article/details/gt2nrylzaro.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.meibo888.top/Article/details/gt2rntldgjg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.andypj.xyz/Article/details/gt2wzmzdfnv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jiagoushi.top/Article/details/gt2plxbfltk.html

Go:   end.Sub(start).Hours()
来源：http://dali.tanke756.top/Article/details/gt2fwdbhcvk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tanke756.top/Article/details/gt2mivxbmrs.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258.top/Article/details/gt2xbnfridr.html

[J07] 比较两个日期
来源：http://dali.hongshengwenyu.top/Article/details/gt2nprdppol.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gt2lkjhlqyi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgufenzy.top/Article/details/gt2ilwxygpv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigufen.top/Article/details/gt2lnxdwqto.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhongyouzk.top/Article/details/gt2igqrcyud.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgufenzy.top/Article/details/gt2fhdhfhbl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.vqdsnc.cn/Article/details/gt2nrhfmwdf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gt2roswrbto.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gt2efruhugn.html

[J08] 提取年月日与星期
来源：http://dali.tanke756.top/Article/details/gt2ysdvjuov.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gotoacloud.top/Article/details/gt2uhxpopcx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ydzc1.top/Article/details/gt2nnwlscbh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuxming.cn/Article/details/gt2uzjopgdx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fzhhl.top/Article/details/gt2ierovwmc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenzaomai.com/Article/details/gt2vfzcqflb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fzhhl.top/Article/details/gt2pdnidibk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.andypj.xyz/Article/details/gt2varyfrun.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.9152youxi.cn/Article/details/gt2swezbppp.html

[J09] 时区处理
来源：http://dali.dashuyun.cn/Article/details/gt2lrpqjdti.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hoxyacfa.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.fengsongda.top/Article/details/gt2iplrjsvl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gt2mdrnwfjr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gt2tgfioame.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xziqi.cn/Article/details/gt2nspnmihd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jqgufenzy.top/Article/details/gt2vexqhuwb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.mhx1999.top/Article/details/gt2tncftgcw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.dashuyun.cn/Article/details/gt2dtoiudda.html

[J10] 取今天 / 本月第一天
来源：http://dali.zycfv.cn/Article/details/gt2jxdkzotc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ydzc1.top/Article/details/gt2orgxwmzc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xrbbhumz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2wvocwodg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhixingplan.top/Article/details/gt2alnqhfpg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.havefunace.top/Article/details/gt2bbuzcznh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj20258888.top/Article/details/gt2cghxoysl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.wangdashe.top/Article/details/gt2mhppgoxo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gzhubu.top/Article/details/gt2nvphfmcv.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2arqjqdwn.html

K. JSON 与序列化
来源：http://dali.yueranfly.top/Article/details/gt2lvgijqna.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2caplinfc.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fkjpvcav.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jyuzzxns.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gt2efiwopbf.html

JS:   JSON.stringify(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2wslfktbr.html

TS:   JSON.stringify(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2ycrwufgn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yueranfly.top/Article/details/gt2nvpifdvj.html

Go:   json.Marshal(obj)
来源：http://dali.yj20258.top/Article/details/gt2cztzbrnz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ppjwa.cn/Article/details/gt2yaeyinol.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yongpay.top/Article/details/gt2vkwszzcp.html

[K02] JSON 字符串转对象
来源：http://dali.fengsongda.top/Article/details/gt2xutphsnl.html

Py:   json.loads(s)
来源：http://dali.guowangkeji.top/Article/details/gt2vwbsnenz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigfzy.top/Article/details/gt2etsozwvr.html

JS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2umuaswxa.html

TS:   JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gt2ctbdyouj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gt2xchblskm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sxryk.cn/Article/details/gt2fxegacgo.html

Ruby: JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gt2jitdudoa.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sweek.top/Article/details/gt2onlkegdv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.pycfn.com/Article/details/gt2bppieitq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gt2mqvjxtrh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gt2hxyvmgpx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gt2mtbqvnzh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2inrwxplz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fzhhl.top/Article/details/gt2dzrngjcv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.svipenyu.cn/Article/details/gt2leaqoztp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2ilbarnyt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.pengpengdd.cyou/Article/details/gt2dgmgtdfj.html

[K04] 读取 JSON 文件
来源：http://dali.smart0.xyz/Article/details/gt2wnlgqdqh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.aizwys.cn/Article/details/gt2gicmenmi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sweek.top/Article/details/gt2xjbalcjq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2rvbhgxsg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2nijpwtmo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gt2vxhjtbja.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenzaomai.com/Article/details/gt2quburyxp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gt2wyllvooi.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hysaishi.cn/Article/details/gt2asqjzoex.html

[K05] 深拷贝对象
来源：http://dali.yuxming.cn/Article/details/gt2diozonkg.html

Py:   copy.deepcopy(obj)
来源：http://dali.yonumen.top/Article/details/gt2zocmriiy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cdnleiting.top/Article/details/gt2agnzxttk.html

JS:   structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gt2cdllmxso.html

TS:   structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2smtepmdf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gzhubu.top/Article/details/gt2qjngkliz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gogol.net.cn/Article/details/gt2rprqrxny.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jqgufenzy.top/Article/details/gt2cdsqtqmw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj20258.top/Article/details/gt2kwzrejny.html

[K06] 解析 URL 查询串
来源：http://dali.sxryk.cn/Article/details/gt2mmjjweay.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yueranfly.top/Article/details/gt2xpaedtic.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yonumen.top/Article/details/gt2bebzvnix.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ydzc1.top/Article/details/gt2uhdkhgdp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dlxhqoih.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qlcyeqen.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gt2iijggogp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gt2kiketxnd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gt2pvvuszhg.html

[K07] 进制转换
来源：http://dali.jyoumei.cn/Article/details/gt2parmvjob.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2rscgikoj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xinyue.icu/Article/details/gt2xlmumnlg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gt2pjnegfdj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gt2usyauoqf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2heuzgrzl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.dashuyun.cn/Article/details/gt2ltyurkos.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zdqjudy.top/Article/details/gt2qzfzyxqc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gt2qlwyejbo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cashguo.top/Article/details/gt2suwoztah.html

Py:   pickle.dumps(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2brdhiowu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.aibaodan.cn/Article/details/gt2tcllmwmb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xuanzx.com/Article/details/gt2vdmlpgbg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gaohongyu789.top/Article/details/gt2jzzqbyrc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jianghu66.top/Article/details/gt2njnxkmoc.html

Go:   encoding/gob
来源：http://dali.zycfv.cn/Article/details/gt2kgecaext.html

Ruby: Marshal.dump(obj)
来源：http://dali.tian-w.cn/Article/details/gt2qdckftox.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gt2qnqcipvw.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2ooajtind.html

L. 网络请求
来源：http://dali.jianghu66.top/Article/details/gt2bksbgqay.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2wiwpcugo.html

[L01] 发送 GET 请求
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qunvzffo.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hnxiangtu.top/Article/details/gt2hkacpcss.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tian-w.cn/Article/details/gt2kxqshmpw.html

JS:   await fetch(url)
来源：http://dali.xylfe.cn/Article/details/gt2stobjbtd.html

TS:   await fetch(url)
来源：http://dali.yonumen.top/Article/details/gt2cohvponk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.feifeiyinyue.top/Article/details/gt2xpxnthgc.html

Go:   resp, err := http.Get(url)
来源：http://dali.cheryme.top/Article/details/gt2rmlpytei.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yonumen.top/Article/details/gt2tiulckfn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jyoumei.cn/Article/details/gt2gjuzkcin.html

[L02] 发送 POST JSON
来源：http://dali.andypj.xyz/Article/details/gt2ipxobnfm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gt2qempxxmy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yuxming.cn/Article/details/gt2fhsalada.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.snrcjt.cn/Article/details/gt2skzecqbn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yangfankeji.com/Article/details/gt2asymhysp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hysaishi.cn/Article/details/gt2xfrmqzxa.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhoulong.xyz/Article/details/gt2bzdedcgx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ixhqckxy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhoulong.xyz/Article/details/gt2mggxrlqw.html

[L03] 设置自定义请求头
来源：http://dali.mhx1999.top/Article/details/gt2dwzpvmnl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.aizwys.cn/Article/details/gt2mjptbjzt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj202588.top/Article/details/gt2tgerhrxw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xlbkekmj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangdashe.top/Article/details/gt2cwxzjvvm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ppjwa.cn/Article/details/gt2tdjbapoj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gt2tzhzeabb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sysykeji.top/Article/details/gt2ptxsgejo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcaecwgm.html

[L04] 设置超时
来源：http://dali.chenzaomai.com/Article/details/gt2hvtnxiyv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shangyingyoupin.top/Article/details/gt2uwonenjv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xylfe.cn/Article/details/gt2fewlfjqc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.iojbl.cn/Article/details/gt2vzrwhlez.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sweek.top/Article/details/gt2yeaaiwzq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhongyouzk.top/Article/details/gt2czlrtpmx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hcfqhjfj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.dianchejie.cn/Article/details/gt2goygaohk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.svipenyu.cn/Article/details/gt2amfhmrfz.html

[L05] 上传文件（multipart）
来源：http://dali.dianchejie.cn/Article/details/gt2ufoadhyr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2hattchmw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuxming.cn/Article/details/gt2zfujtojm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhengqikj.top/Article/details/gt2kociiegc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.daria6918.cn/Article/details/gt2uixaazcc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhiwuduotai.top/Article/details/gt2hwejgavq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhongyouzk.top/Article/details/gt2ekipvgpm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenzaomai.com/Article/details/gt2jieeityo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2yempdhvn.html

[L06] 解析响应为 JSON
来源：http://dali.jinqigfzy.top/Article/details/gt2teojwlxj.html

Py:   resp.json()
来源：http://dali.xuanzx.com/Article/details/gt2mfbvisyb.html

PHP:  json_decode($body, true);
来源：http://dali.ydzc1.top/Article/details/gt2mwpaefit.html

JS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gt2mwxlbfkc.html

TS:   await resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gt2qzvctelg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tanke756.top/Article/details/gt2moeaczed.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xinyue.icu/Article/details/gt2nscwlnhd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sweek.top/Article/details/gt2liaotuzb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhixingplan.top/Article/details/gt2jwzzandq.html

[L07] 处理 HTTP 状态码
来源：http://dali.feifeiyinyue.top/Article/details/gt2nfldjlhu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.andypj.xyz/Article/details/gt2zupnhsam.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jyoumei.cn/Article/details/gt2cpeinxtl.html

JS:   resp.ok;  resp.status
来源：http://dali.hfpthk.cn/Article/details/gt2nzwkhegb.html

TS:   resp.ok;  resp.status
来源：http://dali.tian-w.cn/Article/details/gt2hphhgivs.html

Java: resp.statusCode()
来源：http://dali.jqgufenzy.top/Article/details/gt2iolxuokt.html

Go:   resp.StatusCode
来源：http://dali.yongpay.top/Article/details/gt2pswvajow.html

Ruby: resp.code.to_i
来源：http://dali.svipenyu.cn/Article/details/gt2zydrkxnc.html

C#:   (int)resp.StatusCode
来源：http://dali.shangyingyoupin.top/Article/details/gt2umdwmlin.html

[L08] 并发请求多个地址
来源：http://dali.snrcjt.cn/Article/details/gt2bwphiskq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.mhx1999.top/Article/details/gt2jnuvtaew.html

PHP:  curl_multi_init() 系列
来源：http://dali.cheryme.top/Article/details/gt2vikzjcqt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zycfv.cn/Article/details/gt2ewbwqels.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gt2jfozpokm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shzxlz.cn/Article/details/gt2scsrekol.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2agkbdwmr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sufxvd.cn/Article/details/gt2mhyeshxt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xinyue.icu/Article/details/gt2bjnxzipp.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2yegtkweu.html

M. 命令行 / 进程 / 环境
来源：http://dali.shanyushiyangtech.top/Article/details/gt2duwubxxc.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2clejniho.html

[M01] 读取命令行参数
来源：http://dali.sweek.top/Article/details/gt2qskbbjhu.html

Py:   sys.argv[1:]
来源：http://dali.zhixingplan.top/Article/details/gt2gijxfkxy.html

PHP:  $argv;  $argc;
来源：http://dali.xziqi.cn/Article/details/gt2cplijozy.html

JS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gt2ryjgfuhs.html

TS:   process.argv.slice(2)
来源：http://dali.andypj.xyz/Article/details/gt2clipkpwg.html

Java: args 数组（main 方法参数）
来源：http://dali.dianchejie.cn/Article/details/gt2onebddyc.html

Go:   os.Args[1:]
来源：http://dali.dianchejie.cn/Article/details/gt2eiwtfqmy.html

Ruby: ARGV
来源：http://dali.sysykeji.top/Article/details/gt2dtfridpa.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sufxvd.cn/Article/details/gt2ipxqqvyg.html

[M02] 读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gt2uexaeaox.html

Py:   os.environ.get("HOME")
来源：http://dali.xylfe.cn/Article/details/gt2brbbjwsq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gt2agcgjlte.html

JS:   process.env.HOME
来源：http://dali.aibaodan.cn/Article/details/gt2vjcuysrg.html

TS:   process.env.HOME
来源：http://dali.kuanghao11.cn/Article/details/gt2oajxxpck.html

Java: System.getenv("HOME")
来源：http://dali.yangfankeji.com/Article/details/gt2llauzsgz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gt2ugqburve.html

Ruby: ENV["HOME"]
来源：http://dali.0kj1m.cn/Article/details/gt2ongbniaq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xylfe.cn/Article/details/gt2giyhakxr.html

[M03] 执行外部命令
来源：http://dali.ppjwa.cn/Article/details/gt2xlacvbbw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gzhubu.top/Article/details/gt2bppqqqji.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.kuanghao11.cn/Article/details/gt2brtuvtcn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhengqikj.top/Article/details/gt2xildgkqw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hysaishi.cn/Article/details/gt2llpzklyh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ydzc1.top/Article/details/gt2lveqqncj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ivvv.top/Article/details/gt2ofpwiklp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yueranfly.top/Article/details/gt2ksbbkdkk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.0kj1m.cn/Article/details/gt2chxiztjp.html

[M04] 获取当前工作目录
来源：http://dali.daria6918.cn/Article/details/gt2hjumthnf.html

Py:   os.getcwd()
来源：http://dali.yvedp.cn/Article/details/gt2dgdghmvd.html

PHP:  getcwd();
来源：http://dali.jqgufenzy.top/Article/details/gt2kovwearh.html

JS:   process.cwd()
来源：http://dali.hammf.cn/Article/details/gt2ivvjucsj.html


<!-- 参考信息 -->