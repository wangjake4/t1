代发 wailian999

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.daxiang520.top/Article/details/gtynfpacnx.html

JS:   new Date();  Date.now()
来源：http://dali.jinqigufen.top/Article/details/gtbcydnnuk.html

TS:   new Date();  Date.now()
来源：http://dali.316326.xyz/Article/details/gtzytdmcxv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tian-w.cn/Article/details/gtmqawntxi.html

Go:   time.Now()
来源：http://dali.fzhhl.top/Article/details/gtefswvrhj.html

Ruby: Time.now
来源：http://dali.iojbl.cn/Article/details/gtuezwtxto.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yonumen.top/Article/details/gtqqrmxnja.html

[J02] 格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gtukahzsrr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtikcjnhfa.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xinyue.icu/Article/details/gttkzqithm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.birdmap.top/Article/details/gttkuraesn.html

TS:   d.toISOString()
来源：http://dali.daxiang520.top/Article/details/gtnajbqofr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cqqwz.cn/Article/details/gtopuwxjrz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.iojbl.cn/Article/details/gtxssybnao.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dianchejie.cn/Article/details/gtvnatzhkn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tian-w.cn/Article/details/gtpmwgeyqx.html

[J03] 字符串解析为日期
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzyzeioaz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cucudq.cn/Article/details/gtrnvtgrtn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tian-w.cn/Article/details/gtobejgvmk.html

JS:   new Date("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtvyyabjon.html

TS:   new Date("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtvrjoxfyo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtpqvgxcww.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtlolcvfxc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvmwbppn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.aizwys.cn/Article/details/gtsespzehz.html

[J04] 时间戳与日期互转
来源：http://dali.chenjidiqi.icu/Article/details/gtvssnkgsj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guannengcc.top/Article/details/gtxlzezdpo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yongpay.top/Article/details/gtoicspsbt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daria6918.cn/Article/details/gtejummeor.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gtcggfgsqc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.havefunace.top/Article/details/gtverhghkq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqrsccuo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgfzy.top/Article/details/gteoidmkjz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nwbrower.top/Article/details/gtcgmpyiqv.html

[J05] 时间加减（加 7 天）
来源：http://dali.hnxiangtu.top/Article/details/gtwhytrvqd.html

Py:   now + timedelta(days=7)
来源：http://dali.daxiang520.top/Article/details/gtocqwolgw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shzxlz.cn/Article/details/gtbtjahhad.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenzaomai.com/Article/details/gtiyqymthj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gtahwqnkbe.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jianghu66.top/Article/details/gtmcctvfhm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkqpxrinz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jyoumei.cn/Article/details/gtyqdsdgfv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoitoeldv.html

[J06] 计算两时间之差
来源：http://dali.smart0.xyz/Article/details/gtiabsnlsf.html

Py:   (end - start).total_seconds()
来源：http://dali.fengsongda.top/Article/details/gtqbghrodg.html

PHP:  $end->diff($start)->days;
来源：http://dali.vqdsnc.cn/Article/details/gtlpyqwlkd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xylfe.cn/Article/details/gtclaejhyn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yanxiufei.cn/Article/details/gthzbipuwb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hammf.cn/Article/details/gtbbzprlte.html

Go:   end.Sub(start).Hours()
来源：http://dali.tianlin.xyz/Article/details/gtoflwkgfq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jianghu66.top/Article/details/gtnipbskxn.html

C#:   (end - start).TotalSeconds
来源：http://dali.zdqjudy.top/Article/details/gtsaomvtpr.html

[J07] 比较两个日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxbmlwtl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gtykduklhs.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.redwolf501.top/Article/details/gtxnbqbnbr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gtgencnzuu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gtcsyocdgh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.fzhhl.top/Article/details/gtglotupbw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.316326.xyz/Article/details/gtwaoangwe.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gtojvpkfzd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gteojefgzf.html

[J08] 提取年月日与星期
来源：http://dali.yj20258888.top/Article/details/gtntwrpmnx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.dianchejie.cn/Article/details/gttskasnwm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xuanzx.com/Article/details/gtfijzbuvr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.iojbl.cn/Article/details/gtjurqnrip.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.0kj1m.cn/Article/details/gtedpnekuc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwyjdsfgx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.daria6918.cn/Article/details/gtnvwpygjd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nanxuanxn.top/Article/details/gtmgodakyb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shzxlz.cn/Article/details/gtnckhwajy.html

[J09] 时区处理
来源：http://dali.snrcjt.cn/Article/details/gtxzsalijk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.wangshuangyany.cn/Article/details/gtixtipeck.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepqqvvvg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gzhubu.top/Article/details/gtygiybeio.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.kuanghao11.cn/Article/details/gtyjgqexnf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jianghu66.top/Article/details/gtysloqknu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.pycfn.com/Article/details/gtidlhrchu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxiybsmur.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinqigfzy.top/Article/details/gtvuqhoeib.html

[J10] 取今天 / 本月第一天
来源：http://dali.cashguo.top/Article/details/gtiyholujg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnqzz.top/Article/details/gtmiwtmcwh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tanke756.top/Article/details/gtagjrramc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxinkj.top/Article/details/gtgdwplaxt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.birdmap.top/Article/details/gtnbvaknjn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.iojbl.cn/Article/details/gtieajwlxe.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.chenlongwang.top/Article/details/gtwmezhuco.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuanzhike.top/Article/details/gtttaouxkp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xylfe.cn/Article/details/gtnehcgick.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtaoviiqpd.html

K. JSON 与序列化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvsvkgxi.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtuqeqtnms.html

[K01] 对象转 JSON 字符串
来源：http://dali.cashguo.top/Article/details/gtadozxshg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.daria6918.cn/Article/details/gthhhgwgmp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.mhx1999.top/Article/details/gtnjkddvdt.html

JS:   JSON.stringify(obj)
来源：http://dali.aizwys.cn/Article/details/gtdxxpmzmk.html

TS:   JSON.stringify(obj)
来源：http://dali.zhixingplan.top/Article/details/gturxmwesm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.mhx1999.top/Article/details/gtkxsbdvpp.html

Go:   json.Marshal(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtalprunar.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.dianchejie.cn/Article/details/gtoqcajkhk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtmwihbezs.html

[K02] JSON 字符串转对象
来源：http://dali.wangdashe.top/Article/details/gtwuttowfy.html

Py:   json.loads(s)
来源：http://dali.bjfxy.top/Article/details/gtrbbpplod.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tian-w.cn/Article/details/gtnlgmsqkz.html

JS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtvhrstrak.html

TS:   JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gtmmgwfwdb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.wangdashe.top/Article/details/gtudeqjspz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jianghu66.top/Article/details/gtbmvgrlmd.html

Ruby: JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gtsxzmdwqn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shzxlz.cn/Article/details/gtszepadip.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhiwuduotai.top/Article/details/gtvkvohwsp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gaohongyu789.top/Article/details/gtsbcamdos.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ehwqpu.com/Article/details/gtavnojioc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ehwqpu.com/Article/details/gtpiytcqrd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.havefunace.top/Article/details/gtmxswjggh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ybcxt.top/Article/details/gtnlnhalqi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyuopwfuv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tanke756.top/Article/details/gtvennnqee.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hnxiangtu.top/Article/details/gtxwxotpyd.html

[K04] 读取 JSON 文件
来源：http://dali.zhoulong.xyz/Article/details/gtbmnzqbne.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.pycfn.com/Article/details/gtjmlrzzga.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenzaomai.com/Article/details/gtbrckhybb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkivcvcwv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hfpthk.cn/Article/details/gtusnbfnxy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yueranfly.top/Article/details/gtiuxcbacl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jqgufenzy.top/Article/details/gtkfrplnqs.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangshuangyany.cn/Article/details/gtegcvvkyx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenzaomai.com/Article/details/gtkfpvepif.html

[K05] 深拷贝对象
来源：http://dali.bjfxy.top/Article/details/gtztxbzxsr.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj20258.top/Article/details/gthdlbyuji.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cucudq.cn/Article/details/gtjrzujsqm.html

JS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gtbyfdvwed.html

TS:   structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gtlxziychj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ppjwa.cn/Article/details/gtqgnwiskd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hongshengwenyu.top/Article/details/gtoozcidan.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenzaomai.com/Article/details/gtyzmwzjuc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hongshengwenyu.top/Article/details/gtrumfzezx.html

[K06] 解析 URL 查询串
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrforiaw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.dashuyun.cn/Article/details/gtsllhkedc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sweek.top/Article/details/gtfgwdhsgf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zycfv.cn/Article/details/gtysetszii.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guannengcc.top/Article/details/gtguufyuca.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpoitviep.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gtiadmfchj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gtrcdkonfd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gtyptbukdy.html

[K07] 进制转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbwnbddrx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtvehkmavg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gotoacloud.top/Article/details/gtcjhxrywm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtomnycstd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtirncerte.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtmclgdziu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.pycfn.com/Article/details/gtaeuvulqb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gzhubu.top/Article/details/gtjslbautz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtmnonvfdc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhixingplan.top/Article/details/gthdofihjt.html

Py:   pickle.dumps(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtydzxfmfk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hywenlv.cn/Article/details/gtxhfyzsnm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gttwgpvobl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yonumen.top/Article/details/gtijlkolqv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hnqzz.top/Article/details/gtavrbzvyg.html

Go:   encoding/gob
来源：http://dali.hysaishi.cn/Article/details/gtirzqakpq.html

Ruby: Marshal.dump(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtcizsphbk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gaohongyu789.top/Article/details/gtchracpfj.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtrfvigexj.html

L. 网络请求
来源：http://dali.nwbrower.top/Article/details/gtdbwucwrk.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtowfwwigq.html

[L01] 发送 GET 请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyoiwglqg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj202588.top/Article/details/gtfgggeutz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sufxvd.cn/Article/details/gtphxpcxen.html

JS:   await fetch(url)
来源：http://dali.zhengqikj.top/Article/details/gtpbvagdxv.html

TS:   await fetch(url)
来源：http://dali.zhoulong.xyz/Article/details/gtxxuqotco.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yueranfly.top/Article/details/gtjrzguifg.html

Go:   resp, err := http.Get(url)
来源：http://dali.ppjwa.cn/Article/details/gtxuhjzgex.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhixingplan.top/Article/details/gtoslchxhk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hnqzz.top/Article/details/gtrjcrjirx.html

[L02] 发送 POST JSON
来源：http://dali.yangfankeji.com/Article/details/gtmmkxkfia.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenjidiqi.icu/Article/details/gtlxiuiiwi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhixingplan.top/Article/details/gtvkowudjc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuetiantiany.cn/Article/details/gtmvogtdso.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tian-w.cn/Article/details/gtxxutubra.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gogol.net.cn/Article/details/gtdzzvwubb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.haohaochexian.top/Article/details/gtikrcavcs.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sysykeji.top/Article/details/gtdqcodmxd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yuanzhike.top/Article/details/gtimzccfuu.html

[L03] 设置自定义请求头
来源：http://dali.gogol.net.cn/Article/details/gtotreijhj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.iojbl.cn/Article/details/gtjuealvay.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinqigufen.top/Article/details/gtnfrxlaca.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gtxdozoqfu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gtlgherblg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jianghu66.top/Article/details/gtwcraenkw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xuanzx.com/Article/details/gtnaofzyfd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.c1oappe.top/Article/details/gtnuvftupm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gtmepqygis.html

[L04] 设置超时
来源：http://dali.tianlin.xyz/Article/details/gtmwsbnihd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hywenlv.cn/Article/details/gtycuexzde.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhongyouzk.top/Article/details/gtnxpmynvc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sweek.top/Article/details/gtlppulkfv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yangfankeji.com/Article/details/gtgpzkaqqi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sxryk.cn/Article/details/gtjyqsomob.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yonumen.top/Article/details/gtxvosubsa.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jiagoushi.top/Article/details/gtmnonrzhx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhixingplan.top/Article/details/gtqklakppj.html

[L05] 上传文件（multipart）
来源：http://dali.shanyushiyangtech.top/Article/details/gtxmrhbmqn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xuetiantiany.cn/Article/details/gtsyxetbou.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yonumen.top/Article/details/gtbgbhufyo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gteykzjpnz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangshuangyany.cn/Article/details/gtriyqqyez.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xinyue.icu/Article/details/gtpkzetynb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yuxming.cn/Article/details/gtvszpuqbq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tian-w.cn/Article/details/gtrpwbajvo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zycfv.cn/Article/details/gttbgaolpj.html

[L06] 解析响应为 JSON
来源：http://dali.cdnleiting.top/Article/details/gtnzznfokt.html

Py:   resp.json()
来源：http://dali.sysykeji.top/Article/details/gtudmnprmn.html

PHP:  json_decode($body, true);
来源：http://dali.0kj1m.cn/Article/details/gtezbnkpxz.html

JS:   await resp.json()
来源：http://dali.sweek.top/Article/details/gtdtokqobk.html

TS:   await resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gtmufpfysf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtyixrawpq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ppjwa.cn/Article/details/gtwkfwxuyv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cqqwz.cn/Article/details/gtnlcpikes.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangshuangyany.cn/Article/details/gtxnbxgwwb.html

[L07] 处理 HTTP 状态码
来源：http://dali.aizwys.cn/Article/details/gtrfnderle.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zycfv.cn/Article/details/gtzfktlkui.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.wangshuangyany.cn/Article/details/gtbnxkepjv.html

JS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gtjuszclwu.html

TS:   resp.ok;  resp.status
来源：http://dali.nwbrower.top/Article/details/gtwefhhptd.html

Java: resp.statusCode()
来源：http://dali.ydzc1.top/Article/details/gtlldbxxim.html

Go:   resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gtrvmfxlnx.html

Ruby: resp.code.to_i
来源：http://dali.c1oappe.top/Article/details/gttbnuilcp.html

C#:   (int)resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gtslcguwlr.html

[L08] 并发请求多个地址
来源：http://dali.shzxlz.cn/Article/details/gtyfkbnlin.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangdashe.top/Article/details/gtpyhellbj.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangdashe.top/Article/details/gtpfrofiyw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ydzc1.top/Article/details/gttjvrzmvr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nwbrower.top/Article/details/gtuhchgixi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.redwolf501.top/Article/details/gtvdnlbsoq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.aizwys.cn/Article/details/gtljseseqf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sufxvd.cn/Article/details/gthsvncuxn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xziqi.cn/Article/details/gtmdprtvlw.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtzlujaeeo.html

M. 命令行 / 进程 / 环境
来源：http://dali.yongpay.top/Article/details/gtewxdoigt.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtpsaytnrg.html

[M01] 读取命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gtiqpupspz.html

Py:   sys.argv[1:]
来源：http://dali.yongpay.top/Article/details/gtuwcynjvm.html

PHP:  $argv;  $argc;
来源：http://dali.birdmap.top/Article/details/gtibpuanoa.html

JS:   process.argv.slice(2)
来源：http://dali.xuanzx.com/Article/details/gtnktmefce.html

TS:   process.argv.slice(2)
来源：http://dali.yj202588.top/Article/details/gtmtnirakn.html

Java: args 数组（main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gtjfdoxkyg.html

Go:   os.Args[1:]
来源：http://dali.jqgfzy.top/Article/details/gtfrouvxtt.html

Ruby: ARGV
来源：http://dali.sxryk.cn/Article/details/gttpcdxaxo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhiwuduotai.top/Article/details/gtghzbfjsv.html

[M02] 读取环境变量
来源：http://dali.nwbrower.top/Article/details/gtdjhefyus.html

Py:   os.environ.get("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtrammgcgz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gtluvqbtbh.html

JS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gtnnjktobp.html

TS:   process.env.HOME
来源：http://dali.yj202588.top/Article/details/gtrxppqpir.html

Java: System.getenv("HOME")
来源：http://dali.iojbl.cn/Article/details/gtwreidjih.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtpdbnauqf.html

Ruby: ENV["HOME"]
来源：http://dali.yueranfly.top/Article/details/gtxekmwhmd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtvxuoenwl.html

[M03] 执行外部命令
来源：http://dali.wangshuangyany.cn/Article/details/gtgnyyegub.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hysaishi.cn/Article/details/gtyiamcdyq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hysaishi.cn/Article/details/gtatikviqu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hfpthk.cn/Article/details/gtvefonyln.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hfpthk.cn/Article/details/gtukgbvaqt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhongyouzk.top/Article/details/gtdkdobhrf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dianchejie.cn/Article/details/gtyeeqfwpb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhengqikj.top/Article/details/gtepmirfoe.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yongpay.top/Article/details/gtbiukdgiy.html

[M04] 获取当前工作目录
来源：http://dali.ehwqpu.com/Article/details/gtgcfsgxhz.html

Py:   os.getcwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvslnynce.html

PHP:  getcwd();
来源：http://dali.gaohongyu789.top/Article/details/gtsslpwngy.html

JS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gtaorapgxi.html

TS:   process.cwd()
来源：http://dali.fengsongda.top/Article/details/gtcbanssvq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xinyue.icu/Article/details/gtqlhsgtda.html

Go:   os.Getwd()
来源：http://dali.c1oappe.top/Article/details/gtgycwxnvo.html

Ruby: Dir.pwd
来源：http://dali.xinyue.icu/Article/details/gtezokkeza.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xinyue.icu/Article/details/gtypbbzeat.html

[M05] 设置退出码
来源：http://dali.jiagoushi.top/Article/details/gtyffdkkbl.html

Py:   sys.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtoywyhpuf.html

PHP:  exit(1);
来源：http://dali.yj20258.top/Article/details/gtscralyfq.html

JS:   process.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhllhfjh.html

TS:   process.exit(1)
来源：http://dali.yonumen.top/Article/details/gtwjimrspy.html

Java: System.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtywwecybl.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtsvnopjvj.html

Ruby: exit 1
来源：http://dali.cucudq.cn/Article/details/gtdozlzanc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dashuyun.cn/Article/details/gtfigwsffk.html

[M06] 向标准错误输出
来源：http://dali.tian-w.cn/Article/details/gtrfnyejud.html

Py:   print("err", file=sys.stderr)
来源：http://dali.pycfn.com/Article/details/gtnvckduhq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.quarkkingdee.top/Article/details/gtpasdgwsw.html

JS:   console.error("err")
来源：http://dali.tanke756.top/Article/details/gtawnjmdjb.html

TS:   console.error("err")
来源：http://dali.cdnleiting.top/Article/details/gtyhxusiso.html

Java: System.err.println("err")
来源：http://dali.zdqjudy.top/Article/details/gtuzzhplly.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhongyouzk.top/Article/details/gtiijheqld.html

Ruby: warn "err"
来源：http://dali.zdqjudy.top/Article/details/gtkxjqzoid.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gogol.net.cn/Article/details/gtpfmnvbdn.html

[M07] 判断是否为主入口
来源：http://dali.zdqjudy.top/Article/details/gtpxfqzrgy.html

Py:   if __name__ == "__main__":
来源：http://dali.shangyingyoupin.top/Article/details/gtngxtzkun.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hywenlv.cn/Article/details/gtqpomagkj.html

JS:   require.main === module
来源：http://dali.yanxiufei.cn/Article/details/gtpidtiqjd.html

TS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gtzmdsjrhb.html


<!-- 参考信息 -->