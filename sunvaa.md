代发 wailian999

Ruby: s.scan(/error/i)
来源：http://dali.cheryme.top/Article/details/gt2cinsnlvs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gaohongyu789.top/Article/details/gt2btfozmmu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ehwqpu.com/Article/details/gt2awjvyslp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jyoumei.cn/Article/details/gt2mkbglaqd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.daxiang520.top/Article/details/gt2fbqgbiuv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vkjiscjc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.redwolf501.top/Article/details/gt2ugidnrgw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gt2ibcudero.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenzaomai.com/Article/details/gt2dtjqkpai.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ppjwa.cn/Article/details/gt2umgfkkrj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.quarkkingdee.top/Article/details/gt2dnrrbhbs.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2lqdqwiyx.html

J. 日期与时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rxgmaksw.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2mjvqiddv.html

[J01] 获取当前时间
来源：http://dali.zycfv.cn/Article/details/gt2okvjpaca.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kjdzhllo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gt2vvmuwhbb.html

JS:   new Date();  Date.now()
来源：http://dali.wangshuangyany.cn/Article/details/gt2wuislkef.html

TS:   new Date();  Date.now()
来源：http://dali.zycfv.cn/Article/details/gt2qekorzva.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yuanzhike.top/Article/details/gt2odasmutw.html

Go:   time.Now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eqgkizbj.html

Ruby: Time.now
来源：http://dali.daria6918.cn/Article/details/gt2ndstfbjf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gogol.net.cn/Article/details/gt2aiwmnkra.html

[J02] 格式化输出
来源：http://dali.aizwys.cn/Article/details/gt2yitfzqxe.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gt2cxbgjknb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gt2bjaltcoy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ybcxt.top/Article/details/gt2eutbzcaw.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lleovkgu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xziqi.cn/Article/details/gt2xtvzxmtn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinqigufen.top/Article/details/gt2avpvawao.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnxiangtu.top/Article/details/gt2xrtjsdiw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cdnleiting.top/Article/details/gt2lttghull.html

[J03] 字符串解析为日期
来源：http://dali.yangfankeji.com/Article/details/gt2djriqfjj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.redwolf501.top/Article/details/gt2gklqonkk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinqigufen.top/Article/details/gt2qdznvttg.html

JS:   new Date("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gt2eleydojr.html

TS:   new Date("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gt2chbgtfux.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gt2rrtloyuk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tanke756.top/Article/details/gt2slrwcjae.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2mxnygpio.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xylfe.cn/Article/details/gt2cjrisrel.html

[J04] 时间戳与日期互转
来源：http://dali.yj202588.top/Article/details/gt2onxizzsf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nanxuanxn.top/Article/details/gt2aovtfuyx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sysykeji.top/Article/details/gt2edeisicd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.smart0.xyz/Article/details/gt2mumirjoo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hnqzz.top/Article/details/gt2eugwkqaa.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cashguo.top/Article/details/gt2qfstvnmv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ftvbzmcl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jkazqnjr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jlsjyb.cn/Article/details/gt2wmxsfota.html

[J05] 时间加减（加 7 天）
来源：http://dali.jlsjyb.cn/Article/details/gt2qpiezjjj.html

Py:   now + timedelta(days=7)
来源：http://dali.zhijiandao.cn/Article/details/gt2bettfrdr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ybcxt.top/Article/details/gt2glaxtdkq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gt2iqmskcwc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daxiang520.top/Article/details/gt2wpbasfmi.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zdqjudy.top/Article/details/gt2emphylgz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fzhhl.top/Article/details/gt2bxgnyoce.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gogol.net.cn/Article/details/gt2acfclmbz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nanxuanxn.top/Article/details/gt2arhzcbkg.html

[J06] 计算两时间之差
来源：http://dali.gzhubu.top/Article/details/gt2tinmakzj.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258888.top/Article/details/gt2ggwtxorp.html

PHP:  $end->diff($start)->days;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ibnmbnyi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhongyouzk.top/Article/details/gt2uwybpbwe.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ehwqpu.com/Article/details/gt2fblstjam.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.quarkkingdee.top/Article/details/gt2myzgvgaj.html

Go:   end.Sub(start).Hours()
来源：http://dali.aibaodan.cn/Article/details/gt2iivztpko.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shangyingyoupin.top/Article/details/gt2ozfaclle.html

C#:   (end - start).TotalSeconds
来源：http://dali.hywenlv.cn/Article/details/gt2kqpnxbvb.html

[J07] 比较两个日期
来源：http://dali.dashuyun.cn/Article/details/gt2oyrxnqzm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gt2zybqaqdc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hfpthk.cn/Article/details/gt2jrilfglk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gt2mnjiggxj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.aibaodan.cn/Article/details/gt2knqfrprt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tian-w.cn/Article/details/gt2iwgnqwyl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gaohongyu789.top/Article/details/gt2xegcnicn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gt2kytgpykk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gt2jtvsslsg.html

[J08] 提取年月日与星期
来源：http://dali.wangdashe.top/Article/details/gt2xlzvqwhi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yongpay.top/Article/details/gt2nesegaqj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yanxiufei.cn/Article/details/gt2onlyigjf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj20258.top/Article/details/gt2jpbyapom.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ppjwa.cn/Article/details/gt2vbwjhjht.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.aibaodan.cn/Article/details/gt2gnmchisp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hywenlv.cn/Article/details/gt2ayiilcau.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2howxtlrv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxinkj.top/Article/details/gt2omuvedlq.html

[J09] 时区处理
来源：http://dali.hfpthk.cn/Article/details/gt2znpretik.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.iojbl.cn/Article/details/gt2ymxxcogg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.quarkkingdee.top/Article/details/gt2tgvzmghz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gt2lvmnvcrg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hammf.cn/Article/details/gt2llmvxsbt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sysykeji.top/Article/details/gt2pwzxqjwk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ppjwa.cn/Article/details/gt2pvtadhtw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yangfankeji.com/Article/details/gt2ebmmagfh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sxryk.cn/Article/details/gt2hakifowf.html

[J10] 取今天 / 本月第一天
来源：http://dali.hongshengwenyu.top/Article/details/gt2tgnsfvkn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ydzc1.top/Article/details/gt2xjwfkmmt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zdqjudy.top/Article/details/gt2owayhftp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cqqwz.cn/Article/details/gt2kbviltii.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2ruyybaxw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2zajaccxj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yanxiufei.cn/Article/details/gt2mabswnrg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jqgfzy.top/Article/details/gt2sapwstbl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wauenbsl.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2hqvfrvwk.html

K. JSON 与序列化
来源：http://dali.chenlongwang.top/Article/details/gt2lpuftsas.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2dhqhtbzf.html

[K01] 对象转 JSON 字符串
来源：http://dali.mhx1999.top/Article/details/gt2bhiznohx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hywenlv.cn/Article/details/gt2cvjivtfq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tanke756.top/Article/details/gt2hlcpkmhl.html

JS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2icxuhksq.html

TS:   JSON.stringify(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dbaqwnsf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.dashuyun.cn/Article/details/gt2ogwwqqsu.html

Go:   json.Marshal(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ddjyuqsx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shzxlz.cn/Article/details/gt2gbdbwblj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2zwykllrx.html

[K02] JSON 字符串转对象
来源：http://dali.hammf.cn/Article/details/gt2fzgukpgi.html

Py:   json.loads(s)
来源：http://dali.birdmap.top/Article/details/gt2rkozbvln.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.dashuyun.cn/Article/details/gt2frontzfa.html

JS:   JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gt2jpvxwusq.html

TS:   JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gt2nlqdxowf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gt2wwmmrchz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cheryme.top/Article/details/gt2kwilusds.html

Ruby: JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gt2emdrjbgv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.0kj1m.cn/Article/details/gt2qrctvvkc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qpkzdpnx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenlongwang.top/Article/details/gt2skyfjuxr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gt2gcqszmgl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cqqwz.cn/Article/details/gt2xbstayxi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gt2pnjyiuhq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nzpewzeq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.fengsongda.top/Article/details/gt2yzarxglo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.redwolf501.top/Article/details/gt2pjdbgdmu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jlsjyb.cn/Article/details/gt2ifnicjkz.html

[K04] 读取 JSON 文件
来源：http://dali.quarkkingdee.top/Article/details/gt2ixxldcww.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jqgfzy.top/Article/details/gt2vrwsyxzg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qehoehpo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigufen.top/Article/details/gt2uwquhbyk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.iojbl.cn/Article/details/gt2tgjyaowj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cucudq.cn/Article/details/gt2wawuxywf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zqixdhpw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yueranfly.top/Article/details/gt2jgxgmhpy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2tlkbfepm.html

[K05] 深拷贝对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dhsezgty.html

Py:   copy.deepcopy(obj)
来源：http://dali.shuidangran.top/Article/details/gt2edaqraxu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.redwolf501.top/Article/details/gt2qgdfxzlj.html

JS:   structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gt2fiqrbtsa.html

TS:   structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2iqysdbyi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnqzz.top/Article/details/gt2lajeehek.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nwbrower.top/Article/details/gt2rvkjlllf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cashguo.top/Article/details/gt2ebicsjzf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yangfankeji.com/Article/details/gt2fycusvnr.html

[K06] 解析 URL 查询串
来源：http://dali.zhongyouzk.top/Article/details/gt2lgikzzmc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tian-w.cn/Article/details/gt2xczczmla.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ppjwa.cn/Article/details/gt2gppyhfth.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gt2zpdqqyqi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dianchejie.cn/Article/details/gt2mjhhpaly.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cdnleiting.top/Article/details/gt2exfacitf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gt2oixorbac.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cashguo.top/Article/details/gt2mdeoglza.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vtgtkkwy.html

[K07] 进制转换
来源：http://dali.xuanzx.com/Article/details/gt2tzeedyzb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gt2nvqdryrn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnqzz.top/Article/details/gt2nuozvzcr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2emnybdjt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2zizynsis.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gt2frwzvbml.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sysykeji.top/Article/details/gt2tbmkaury.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shuidangran.top/Article/details/gt2eodjwhpf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gt2tpxwhiam.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dianchejie.cn/Article/details/gt2lcszupfc.html

Py:   pickle.dumps(obj)
来源：http://dali.redwolf501.top/Article/details/gt2eybqxnzq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.dianchejie.cn/Article/details/gt2dmkrfuda.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yuanzhike.top/Article/details/gt2lclcmfbh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gaohongyu789.top/Article/details/gt2yjajajhw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenzaomai.com/Article/details/gt2fyhniscp.html

Go:   encoding/gob
来源：http://dali.smart0.xyz/Article/details/gt2vferjqpy.html

Ruby: Marshal.dump(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2qsztnnvl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ybcxt.top/Article/details/gt2tvperlhc.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2brvghxxd.html

L. 网络请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hewgqknw.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2sksmayqf.html

[L01] 发送 GET 请求
来源：http://dali.ehwqpu.com/Article/details/gt2lsqwblga.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xylfe.cn/Article/details/gt2oevalglk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhiwuduotai.top/Article/details/gt2zkoqkhhb.html

JS:   await fetch(url)
来源：http://dali.ydzc1.top/Article/details/gt2nmwxiwql.html

TS:   await fetch(url)
来源：http://dali.0kj1m.cn/Article/details/gt2chqxqjqf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sgnrgccz.html

Go:   resp, err := http.Get(url)
来源：http://dali.hnxiangtu.top/Article/details/gt2onwpiujx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhixingplan.top/Article/details/gt2pwydwype.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nanxinkj.top/Article/details/gt2tnmcpgmh.html

[L02] 发送 POST JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xvbymqgi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tanke756.top/Article/details/gt2fanyuihl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ydzc1.top/Article/details/gt2vfqernif.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daria6918.cn/Article/details/gt2qqnjdote.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.meibo888.top/Article/details/gt2kbjfbmbg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.meibo888.top/Article/details/gt2wxuaxcbd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhengqikj.top/Article/details/gt2nerpdnuh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ehwqpu.com/Article/details/gt2jeuzkyai.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sweek.top/Article/details/gt2omlpsrcj.html

[L03] 设置自定义请求头
来源：http://dali.xuetiantiany.cn/Article/details/gt2gnucmjyo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhongyouzk.top/Article/details/gt2ibyjxznf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yanxiufei.cn/Article/details/gt2ikamgbrf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnqzz.top/Article/details/gt2xiacmohi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gt2rgqxftlz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhiwuduotai.top/Article/details/gt2nqdgprcz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yueranfly.top/Article/details/gt2ardxqmgs.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.mhx1999.top/Article/details/gt2vievroqa.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yanxiufei.cn/Article/details/gt2bzzhjfhw.html

[L04] 设置超时
来源：http://dali.chenzaomai.com/Article/details/gt2uzgsbatm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gtghqybj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jiagoushi.top/Article/details/gt2vswoumpq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.316326.xyz/Article/details/gt2kduvmgfr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.snrcjt.cn/Article/details/gt2fvixryip.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tian-w.cn/Article/details/gt2jdasdubp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangshuangyany.cn/Article/details/gt2pxvdrxpj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xinyue.icu/Article/details/gt2wsonhoiq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.pycfn.com/Article/details/gt2dayecmxv.html

[L05] 上传文件（multipart）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hireuhvh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shuidangran.top/Article/details/gt2ylbgsled.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yangfankeji.com/Article/details/gt2hmumskgd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgfzy.top/Article/details/gt2xjcykods.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangshuangyany.cn/Article/details/gt2sxdhozvy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ppjwa.cn/Article/details/gt2audioqom.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.guannengcc.top/Article/details/gt2whwigfnn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nzcrywiz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2jlotetfw.html

[L06] 解析响应为 JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wtdiswud.html

Py:   resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gt2rtuhtsxz.html

PHP:  json_decode($body, true);
来源：http://dali.tianlin.xyz/Article/details/gt2cuxavkqt.html

JS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gt2gyfmgjhw.html

TS:   await resp.json()
来源：http://dali.hywenlv.cn/Article/details/gt2agnzgqgp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yongpay.top/Article/details/gt2wyoyszqw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xinyue.icu/Article/details/gt2fjtawhhg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yueranfly.top/Article/details/gt2qrgnotsw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhixingplan.top/Article/details/gt2qeepgrgm.html

[L07] 处理 HTTP 状态码
来源：http://dali.0kj1m.cn/Article/details/gt2ocviisqb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.daria6918.cn/Article/details/gt2wptvqtmj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cheryme.top/Article/details/gt2poazvdbq.html

JS:   resp.ok;  resp.status
来源：http://dali.chenjidiqi.icu/Article/details/gt2lqrvdkvp.html

TS:   resp.ok;  resp.status
来源：http://dali.andypj.xyz/Article/details/gt2sfdizeho.html

Java: resp.statusCode()
来源：http://dali.ybcxt.top/Article/details/gt2pghgyyvj.html

Go:   resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gt2zbhnmpxx.html

Ruby: resp.code.to_i
来源：http://dali.yj20258.top/Article/details/gt2ubxuytub.html

C#:   (int)resp.StatusCode
来源：http://dali.cashguo.top/Article/details/gt2oyifjvbv.html

[L08] 并发请求多个地址
来源：http://dali.hysaishi.cn/Article/details/gt2fhlqguzm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cqqwz.cn/Article/details/gt2jhtjmsra.html

PHP:  curl_multi_init() 系列
来源：http://dali.dianchejie.cn/Article/details/gt2vshebpps.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gt2ymjteyry.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gt2otpeotwi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sweek.top/Article/details/gt2gziplhje.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yonumen.top/Article/details/gt2esooaxxb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dqutwjqi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenlongwang.top/Article/details/gt2kgcbrkwo.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2ckvayzdf.html

M. 命令行 / 进程 / 环境
来源：http://dali.cashguo.top/Article/details/gt2mmvjzflg.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2esawbbwz.html

[M01] 读取命令行参数
来源：http://dali.bjfxy.top/Article/details/gt2amtwnwcj.html

Py:   sys.argv[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gt2bifmudsp.html

PHP:  $argv;  $argc;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vwlbicxv.html

JS:   process.argv.slice(2)
来源：http://dali.iojbl.cn/Article/details/gt2bseposot.html

TS:   process.argv.slice(2)
来源：http://dali.cdnleiting.top/Article/details/gt2gjerrwbt.html

Java: args 数组（main 方法参数）
来源：http://dali.xinyue.icu/Article/details/gt2azuezbib.html

Go:   os.Args[1:]
来源：http://dali.yangfankeji.com/Article/details/gt2qczickfp.html

Ruby: ARGV
来源：http://dali.yvedp.cn/Article/details/gt2igsozvfn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xylfe.cn/Article/details/gt2aszezrdn.html

[M02] 读取环境变量
来源：http://dali.hysaishi.cn/Article/details/gt2jvfiucmf.html

Py:   os.environ.get("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zkhnuzqb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.birdmap.top/Article/details/gt2ekjhoetm.html

JS:   process.env.HOME
来源：http://dali.aibaodan.cn/Article/details/gt2xremlkft.html

TS:   process.env.HOME
来源：http://dali.xziqi.cn/Article/details/gt2oacotjbg.html

Java: System.getenv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gt2nljjgvaz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangdashe.top/Article/details/gt2ykwiasws.html

Ruby: ENV["HOME"]
来源：http://dali.jinqigfzy.top/Article/details/gt2idpmwjqv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenlongwang.top/Article/details/gt2xrgorczr.html

[M03] 执行外部命令
来源：http://dali.svipenyu.cn/Article/details/gt2uiyehzaz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ybcxt.top/Article/details/gt2halcelab.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tanke756.top/Article/details/gt2kltfqbeo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hfpthk.cn/Article/details/gt2xeevodes.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gt2ihoqroqz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hfpthk.cn/Article/details/gt2aiotrcvs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hywenlv.cn/Article/details/gt2xzzaevsa.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xuetiantiany.cn/Article/details/gt2khmfaktk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenzaomai.com/Article/details/gt2fzunzkyz.html

[M04] 获取当前工作目录
来源：http://dali.tian-w.cn/Article/details/gt2ndinresp.html

Py:   os.getcwd()
来源：http://dali.gaohongyu789.top/Article/details/gt2lycxeaax.html

PHP:  getcwd();
来源：http://dali.xziqi.cn/Article/details/gt2tbmjwuhz.html

JS:   process.cwd()
来源：http://dali.jqgufenzy.top/Article/details/gt2zucaoabq.html

TS:   process.cwd()
来源：http://dali.hnqzz.top/Article/details/gt2hyenbwfh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhoulong.xyz/Article/details/gt2ftakjlhs.html

Go:   os.Getwd()
来源：http://dali.tianlin.xyz/Article/details/gt2lilfppmb.html

Ruby: Dir.pwd
来源：http://dali.sufxvd.cn/Article/details/gt2ruxoosle.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yueranfly.top/Article/details/gt2xjzpuiwh.html

[M05] 设置退出码
来源：http://dali.chenzaomai.com/Article/details/gt2urjnhepy.html

Py:   sys.exit(1)
来源：http://dali.yongpay.top/Article/details/gt2rsijtxnt.html

PHP:  exit(1);
来源：http://dali.vqdsnc.cn/Article/details/gt2dshdcsko.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcndcqj.html

TS:   process.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gt2yapjeauu.html

Java: System.exit(1)
来源：http://dali.gzhubu.top/Article/details/gt2puyvfppr.html

Go:   os.Exit(1)
来源：http://dali.shuidangran.top/Article/details/gt2urrudmzu.html


<!-- 参考信息 -->