代发 wailian999

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gt2pxzyepem.html

[I07] 忽略大小写与多行模式
来源：http://dali.xylfe.cn/Article/details/gt2sloycikk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hnxiangtu.top/Article/details/gt2fabkxpwd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.kuanghao11.cn/Article/details/gt2yhgbhhzo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhixingplan.top/Article/details/gt2eicdkeqh.html

TS:   /error/gim
来源：http://dali.yj202588.top/Article/details/gt2eoxdwwbh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cdnleiting.top/Article/details/gt2obnfubbc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenjidiqi.icu/Article/details/gt2corwyldv.html

Ruby: s.scan(/error/i)
来源：http://dali.guannengcc.top/Article/details/gt2onknbltn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhoulong.xyz/Article/details/gt2qesatpjf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gaohongyu789.top/Article/details/gt2qumoreeq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.aizwys.cn/Article/details/gt2yljqffof.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.snrcjt.cn/Article/details/gt2dsxfpyfk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gt2fbjblzbr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sufxvd.cn/Article/details/gt2gohiqzwr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.pengpengdd.cyou/Article/details/gt2uakenbsk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jyoumei.cn/Article/details/gt2dfrndgkx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.redwolf501.top/Article/details/gt2crxjkpvv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.guowangkeji.top/Article/details/gt2aqlnyjvc.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2krqrtofb.html

J. 日期与时间
来源：http://dali.chenjidiqi.icu/Article/details/gt2lyxfplhn.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2bmocekux.html

[J01] 获取当前时间
来源：http://dali.chenlongwang.top/Article/details/gt2wolegasy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuanzx.com/Article/details/gt2yowcfode.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.kuanghao11.cn/Article/details/gt2sdboqxnf.html

JS:   new Date();  Date.now()
来源：http://dali.jiagoushi.top/Article/details/gt2rpwchnit.html

TS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gt2skmztyth.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhoulong.xyz/Article/details/gt2ejwbpyre.html

Go:   time.Now()
来源：http://dali.yuxming.cn/Article/details/gt2dttgwovr.html

Ruby: Time.now
来源：http://dali.jinqigfzy.top/Article/details/gt2ueqacuby.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenjidiqi.icu/Article/details/gt2ltshsuia.html

[J02] 格式化输出
来源：http://dali.ppjwa.cn/Article/details/gt2jjfvrtqk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tkxefyin.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aibaodan.cn/Article/details/gt2opgxghgg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yanxiufei.cn/Article/details/gt2tdfancvg.html

TS:   d.toISOString()
来源：http://dali.ppjwa.cn/Article/details/gt2cdoksdnc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhengqikj.top/Article/details/gt2akyclpos.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shzxlz.cn/Article/details/gt2mxwdonao.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgufenzy.top/Article/details/gt2ncuimnws.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.kuanghao11.cn/Article/details/gt2ohmxslni.html

[J03] 字符串解析为日期
来源：http://dali.yj20258888.top/Article/details/gt2yfxcyhsx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xinyue.icu/Article/details/gt2agjtkcnl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.mhx1999.top/Article/details/gt2hmfshhfq.html

JS:   new Date("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gt2ppuxalmo.html

TS:   new Date("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gt2egehrqpr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eufghnzn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.birdmap.top/Article/details/gt2wtcjhlfb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gt2mfkaosig.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hammf.cn/Article/details/gt2zfxskibp.html

[J04] 时间戳与日期互转
来源：http://dali.gaohongyu789.top/Article/details/gt2jcxzkpsh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cucudq.cn/Article/details/gt2jnxnapnn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gzhubu.top/Article/details/gt2stansgdr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.fengsongda.top/Article/details/gt2fcsttnvk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ehwqpu.com/Article/details/gt2gjgxaqla.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.wangdashe.top/Article/details/gt2kaiqqeuj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.daria6918.cn/Article/details/gt2tkkbxjbd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nanxinkj.top/Article/details/gt2mdnwptbu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jlsjyb.cn/Article/details/gt2urfwciuv.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgfzy.top/Article/details/gt2ywxdzply.html

Py:   now + timedelta(days=7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2muxooinu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zdqjudy.top/Article/details/gt2dqiazcbi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fengsongda.top/Article/details/gt2fludafhg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yvedp.cn/Article/details/gt2kbzevmbn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yvedp.cn/Article/details/gt2qwmjmntv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.daria6918.cn/Article/details/gt2zdqqrheg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xuetiantiany.cn/Article/details/gt2fprobzrc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhengqikj.top/Article/details/gt2udmtzhjd.html

[J06] 计算两时间之差
来源：http://dali.yuxming.cn/Article/details/gt2mwymnmxo.html

Py:   (end - start).total_seconds()
来源：http://dali.xuanzx.com/Article/details/gt2khbhtvlr.html

PHP:  $end->diff($start)->days;
来源：http://dali.9152youxi.cn/Article/details/gt2npkkwmlf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.316326.xyz/Article/details/gt2jkvcwikt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vvzxvsis.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cashguo.top/Article/details/gt2fudtfksg.html

Go:   end.Sub(start).Hours()
来源：http://dali.havefunace.top/Article/details/gt2gxoiuvcn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.mhx1999.top/Article/details/gt2tpxydqov.html

C#:   (end - start).TotalSeconds
来源：http://dali.tian-w.cn/Article/details/gt2wttfrzii.html

[J07] 比较两个日期
来源：http://dali.fzhhl.top/Article/details/gt2zbvjzxph.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gt2ziotkkow.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xziqi.cn/Article/details/gt2bpzzgula.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gt2cqfzfwip.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sweek.top/Article/details/gt2gvfcawtj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ehwqpu.com/Article/details/gt2zrsqqwsf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sufxvd.cn/Article/details/gt2iauaofik.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gt2fnpumxuw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojjnvsmw.html

[J08] 提取年月日与星期
来源：http://dali.cdnleiting.top/Article/details/gt2lxiiejqv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xziqi.cn/Article/details/gt2skvtwqii.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.aibaodan.cn/Article/details/gt2eksyaxrx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhengqikj.top/Article/details/gt2zjqfocav.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhijiandao.cn/Article/details/gt2ekoudrmj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jqgfzy.top/Article/details/gt2efggyypc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shangyingyoupin.top/Article/details/gt2iewmzkjh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nanxinkj.top/Article/details/gt2rnhblqxl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhongyouzk.top/Article/details/gt2tlsvtkff.html

[J09] 时区处理
来源：http://dali.havefunace.top/Article/details/gt2kvbwstji.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cdnleiting.top/Article/details/gt2zzxsnqao.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shuidangran.top/Article/details/gt2pikzhddo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gt2ivcrhszl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gt2qfogpjyg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.snrcjt.cn/Article/details/gt2bljxwlpt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qsthuicb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.daria6918.cn/Article/details/gt2uoygfysz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhiwuduotai.top/Article/details/gt2hxifmoko.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenlongwang.top/Article/details/gt2gsouybze.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2evieuonz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.havefunace.top/Article/details/gt2shqaecvd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.havefunace.top/Article/details/gt2usarirpv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2kwskqsyq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yvedp.cn/Article/details/gt2xgqxomsk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sweek.top/Article/details/gt2oexxyirs.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nanxuanxn.top/Article/details/gt2piflmdft.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.redwolf501.top/Article/details/gt2ndjgtdfe.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2ypepunbi.html

K. JSON 与序列化
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eweabeks.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2bdxetpru.html

[K01] 对象转 JSON 字符串
来源：http://dali.aibaodan.cn/Article/details/gt2wxxeompf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gt2mjiypjuh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yueranfly.top/Article/details/gt2bkppbbal.html

JS:   JSON.stringify(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2dehwdtyy.html

TS:   JSON.stringify(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2wnnsbkus.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yvedp.cn/Article/details/gt2jesualpg.html

Go:   json.Marshal(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2dsvthooi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnqzz.top/Article/details/gt2alqwnvgc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2tmpglbox.html

[K02] JSON 字符串转对象
来源：http://dali.yj20258888.top/Article/details/gt2tenrkngn.html

Py:   json.loads(s)
来源：http://dali.ehwqpu.com/Article/details/gt2nhvrcfsw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gotoacloud.top/Article/details/gt2nbtyalbf.html

JS:   JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gt2pzyqieef.html

TS:   JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gt2kaahxbbi.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigufen.top/Article/details/gt2cvfbpdjz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cheryme.top/Article/details/gt2mgzecfpw.html

Ruby: JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gt2veicwzsu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gogol.net.cn/Article/details/gt2kywtemaw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.kuanghao11.cn/Article/details/gt2vbaelxrn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cqqwz.cn/Article/details/gt2jjollstj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258.top/Article/details/gt2cokiiyvu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangdashe.top/Article/details/gt2itwuzejl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ppjwa.cn/Article/details/gt2luhlygbp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2ymbgmpyf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.pycfn.com/Article/details/gt2hpjebdon.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sweek.top/Article/details/gt2ikfgweqq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sxryk.cn/Article/details/gt2nihvrcuc.html

[K04] 读取 JSON 文件
来源：http://dali.svipenyu.cn/Article/details/gt2akbbtlom.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xziqi.cn/Article/details/gt2mdmgmkmq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj20258.top/Article/details/gt2nilqxprd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gt2eeydwmow.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigufen.top/Article/details/gt2rwicekfl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shuidangran.top/Article/details/gt2vxxwqibj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.316326.xyz/Article/details/gt2sctnpiuz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zfuurkqt.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gt2kjeydhft.html

[K05] 深拷贝对象
来源：http://dali.yvedp.cn/Article/details/gt2pdxqcpax.html

Py:   copy.deepcopy(obj)
来源：http://dali.cucudq.cn/Article/details/gt2ffxrabpu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenlongwang.top/Article/details/gt2jlpbygfm.html

JS:   structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2uxernktu.html

TS:   structuredClone(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2myrwtwjw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yonumen.top/Article/details/gt2lcdlzapm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shuidangran.top/Article/details/gt2xodzcrat.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hfpthk.cn/Article/details/gt2gbskhmvw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zdqjudy.top/Article/details/gt2jzpocaky.html

[K06] 解析 URL 查询串
来源：http://dali.jqgfzy.top/Article/details/gt2uyyhhdxu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yvedp.cn/Article/details/gt2igbbypna.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.kuanghao11.cn/Article/details/gt2sfhfjqry.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cashguo.top/Article/details/gt2ynrrfpnm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.kuanghao11.cn/Article/details/gt2yefnfzjz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.daria6918.cn/Article/details/gt2ddzdlhhy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gt2vvoktcwh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gt2sksdjrso.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gt2aaquusvo.html

[K07] 进制转换
来源：http://dali.xinyue.icu/Article/details/gt2zgtpemue.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2krrmnbuj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fbdzginl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gt2ifmfrnqq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gt2ugmqojej.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gt2ezcescfp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.snrcjt.cn/Article/details/gt2kbcglghq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.nanxinkj.top/Article/details/gt2snmoxall.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gt2qekzawva.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hammf.cn/Article/details/gt2itkgejsk.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2pekhvnhy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.havefunace.top/Article/details/gt2uwgklbsv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cdnleiting.top/Article/details/gt2jtwjyvqb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gotoacloud.top/Article/details/gt2xcigapmb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhongyouzk.top/Article/details/gt2ucjhdrcz.html

Go:   encoding/gob
来源：http://dali.yueranfly.top/Article/details/gt2zotdwazj.html

Ruby: Marshal.dump(obj)
来源：http://dali.zycfv.cn/Article/details/gt2xkssatiw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jianghu66.top/Article/details/gt2dsqftikq.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2kizsczdr.html

L. 网络请求
来源：http://dali.yj20258888.top/Article/details/gt2qpvbpups.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2jgkdtckr.html

[L01] 发送 GET 请求
来源：http://dali.zhiwuduotai.top/Article/details/gt2bstxkdsp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.daria6918.cn/Article/details/gt2fwxmawkg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.c1oappe.top/Article/details/gt2crkfdbee.html

JS:   await fetch(url)
来源：http://dali.havefunace.top/Article/details/gt2byvxzpyh.html

TS:   await fetch(url)
来源：http://dali.gotoacloud.top/Article/details/gt2mfkiieyq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.vqdsnc.cn/Article/details/gt2wcmyepeg.html

Go:   resp, err := http.Get(url)
来源：http://dali.svipenyu.cn/Article/details/gt2cuczzcea.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.snrcjt.cn/Article/details/gt2flhmbfxj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.haohaochexian.top/Article/details/gt2qqpkqqaj.html

[L02] 发送 POST JSON
来源：http://dali.andypj.xyz/Article/details/gt2numhovcz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gt2dsgwyhdx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.daxiang520.top/Article/details/gt2ssnaqque.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sufxvd.cn/Article/details/gt2qeqenfyt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tanke756.top/Article/details/gt2mxrkaiic.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gogol.net.cn/Article/details/gt2kzgjmayv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigfzy.top/Article/details/gt2mtvdrflb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tligrrxd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daria6918.cn/Article/details/gt2dcpgdtav.html

[L03] 设置自定义请求头
来源：http://dali.daxiang520.top/Article/details/gt2uqjdiwnp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sweek.top/Article/details/gt2kmjobfkr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.c1oappe.top/Article/details/gt2trnlrtuj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yangfankeji.com/Article/details/gt2odjilsmy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnxiangtu.top/Article/details/gt2mqlwvyrh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jiagoushi.top/Article/details/gt2lxcvkwep.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.snrcjt.cn/Article/details/gt2yvpnwotv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daxiang520.top/Article/details/gt2zvdoalwn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinqigfzy.top/Article/details/gt2glzeyqqf.html

[L04] 设置超时
来源：http://dali.yonumen.top/Article/details/gt2rhalpdia.html

Py:   requests.get(url, timeout=5)
来源：http://dali.0kj1m.cn/Article/details/gt2zjzafjvf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hfpthk.cn/Article/details/gt2ttmrcfbi.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pengpengdd.cyou/Article/details/gt2kdjdpevp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenlongwang.top/Article/details/gt2brkvcmhk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sweek.top/Article/details/gt2kjbhhkyy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.bjfxy.top/Article/details/gt2ndvnxdti.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ydzc1.top/Article/details/gt2ibqvpnpm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hywenlv.cn/Article/details/gt2dvmmjlsb.html

[L05] 上传文件（multipart）
来源：http://dali.hongshengwenyu.top/Article/details/gt2wryaaneq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.meibo888.top/Article/details/gt2agfdgyhk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sufxvd.cn/Article/details/gt2wbnwsfnx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gt2sloigffo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.vqdsnc.cn/Article/details/gt2jbwxjlrd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2wzueeyuk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hammf.cn/Article/details/gt2mdgvdmth.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj202588.top/Article/details/gt2ikmmvnqc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2bolioicx.html

[L06] 解析响应为 JSON
来源：http://dali.ydzc1.top/Article/details/gt2ldxudcbu.html

Py:   resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gt2uholwezj.html

PHP:  json_decode($body, true);
来源：http://dali.ybcxt.top/Article/details/gt2gdaxqtiv.html

JS:   await resp.json()
来源：http://dali.cheryme.top/Article/details/gt2giikenzk.html

TS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gt2bpeetphi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shuidangran.top/Article/details/gt2vadlsyyp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxuanxn.top/Article/details/gt2prglkkkl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ydzc1.top/Article/details/gt2rtnorsjz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.pengpengdd.cyou/Article/details/gt2smqkvjmy.html

[L07] 处理 HTTP 状态码
来源：http://dali.redwolf501.top/Article/details/gt2hebgxcnf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zycfv.cn/Article/details/gt2vdbwvmbu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xylfe.cn/Article/details/gt2mrpjncal.html

JS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gt2tnmmyaex.html

TS:   resp.ok;  resp.status
来源：http://dali.xuanzx.com/Article/details/gt2ychqmanj.html

Java: resp.statusCode()
来源：http://dali.yj202588.top/Article/details/gt2yfstacnd.html

Go:   resp.StatusCode
来源：http://dali.hnqzz.top/Article/details/gt2aoredvll.html

Ruby: resp.code.to_i
来源：http://dali.xinyue.icu/Article/details/gt2cnacsjet.html

C#:   (int)resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gt2esbnfbat.html

[L08] 并发请求多个地址
来源：http://dali.tianlin.xyz/Article/details/gt2bejajuco.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.redwolf501.top/Article/details/gt2qsamdksn.html

PHP:  curl_multi_init() 系列
来源：http://dali.shzxlz.cn/Article/details/gt2jzplcflk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gt2wefuiqkv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gt2xssihlpn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhoulong.xyz/Article/details/gt2ihcgyxjn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yongpay.top/Article/details/gt2vgbinoto.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zycfv.cn/Article/details/gt2sgmsgpvu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tanke756.top/Article/details/gt2urcwgten.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2wwbtapod.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhongyouzk.top/Article/details/gt2sybmsgba.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2pngkuotd.html

[M01] 读取命令行参数
来源：http://dali.zhengqikj.top/Article/details/gt2rerryyko.html

Py:   sys.argv[1:]
来源：http://dali.9152youxi.cn/Article/details/gt2oneotcdt.html

PHP:  $argv;  $argc;
来源：http://dali.smart0.xyz/Article/details/gt2rnlhorne.html

JS:   process.argv.slice(2)
来源：http://dali.aizwys.cn/Article/details/gt2flyjifns.html

TS:   process.argv.slice(2)
来源：http://dali.xuanzx.com/Article/details/gt2twbofkau.html

Java: args 数组（main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gt2bzhyrjnl.html

Go:   os.Args[1:]
来源：http://dali.yj20258.top/Article/details/gt2hgagzbkc.html

Ruby: ARGV
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kzciolqm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ydzc1.top/Article/details/gt2uglaxmoj.html

[M02] 读取环境变量
来源：http://dali.tian-w.cn/Article/details/gt2hcxobejq.html

Py:   os.environ.get("HOME")
来源：http://dali.dianchejie.cn/Article/details/gt2rhyagjpj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.meibo888.top/Article/details/gt2uvniokag.html

JS:   process.env.HOME
来源：http://dali.jyoumei.cn/Article/details/gt2qjmgxmlc.html

TS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gt2bnsltouw.html

Java: System.getenv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gt2aqhadiyr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yongpay.top/Article/details/gt2bcjygdqz.html

Ruby: ENV["HOME"]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2chrbaxih.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gt2rloiwfkc.html

[M03] 执行外部命令
来源：http://dali.sxryk.cn/Article/details/gt2abmjyavu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jtemdvku.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yonumen.top/Article/details/gt2gicsumah.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gt2ngifejpj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2retkfqaj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xziqi.cn/Article/details/gt2rhbahjbk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.havefunace.top/Article/details/gt2lnrffvmf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cashguo.top/Article/details/gt2bnpbvoyc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinqigufen.top/Article/details/gt2kejvzfmm.html

[M04] 获取当前工作目录
来源：http://dali.tianlin.xyz/Article/details/gt2jsjoleyr.html

Py:   os.getcwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2avgkjnib.html

PHP:  getcwd();
来源：http://dali.gotoacloud.top/Article/details/gt2izowwgrc.html

JS:   process.cwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jesadnww.html

TS:   process.cwd()
来源：http://dali.hywenlv.cn/Article/details/gt2gbdmkgjr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zdqjudy.top/Article/details/gt2frvfaluq.html

Go:   os.Getwd()
来源：http://dali.vqdsnc.cn/Article/details/gt2vokfpiji.html

Ruby: Dir.pwd
来源：http://dali.dianchejie.cn/Article/details/gt2gknekxfj.html


<!-- 参考信息 -->