代发 wailian999

Go:   time.Now()
来源：http://dali.jinqigufen.top/Article/details/gt2mrldfzta.html

Ruby: Time.now
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jfddsayp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xziqi.cn/Article/details/gt2bpdymqlm.html

[J02] 格式化输出
来源：http://dali.mhx1999.top/Article/details/gt2cafmcweo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhoulong.xyz/Article/details/gt2ymztogxv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gt2tnbezvkm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yongpay.top/Article/details/gt2cmmgatxp.html

TS:   d.toISOString()
来源：http://dali.fzhhl.top/Article/details/gt2hxuncvma.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hongshengwenyu.top/Article/details/gt2qftfojxl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cashguo.top/Article/details/gt2ntzvofin.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gt2exurxgzw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sweek.top/Article/details/gt2dwnwmhja.html

[J03] 字符串解析为日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oligisnf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ykbglacj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zdqjudy.top/Article/details/gt2nypatoqk.html

JS:   new Date("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hdybkxfs.html

TS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gt2umjkmddf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gt2hqyreakf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gt2nlrzowjz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gt2kookigmy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shuidangran.top/Article/details/gt2nulhtgid.html

[J04] 时间戳与日期互转
来源：http://dali.jiagoushi.top/Article/details/gt2ybcxqkjk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hysaishi.cn/Article/details/gt2afpfabyp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sysykeji.top/Article/details/gt2zeuztelq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhongyouzk.top/Article/details/gt2amdwqhwz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yuanzhike.top/Article/details/gt2evptccnt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhongyouzk.top/Article/details/gt2hjyfvedg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rheeyqdl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.fzhhl.top/Article/details/gt2qgzmjuyl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tpeypiwm.html

[J05] 时间加减（加 7 天）
来源：http://dali.tanke756.top/Article/details/gt2mkftzfav.html

Py:   now + timedelta(days=7)
来源：http://dali.aizwys.cn/Article/details/gt2etpzcgjf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sweek.top/Article/details/gt2dfljiarm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ivvv.top/Article/details/gt2ezffvlkk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.svipenyu.cn/Article/details/gt2bgqrcqtu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shzxlz.cn/Article/details/gt2kvqgvzol.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj20258888.top/Article/details/gt2jflsqtsk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.vqdsnc.cn/Article/details/gt2eyicqebu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xqohqbav.html

[J06] 计算两时间之差
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uvlxwsju.html

Py:   (end - start).total_seconds()
来源：http://dali.chenjidiqi.icu/Article/details/gt2qckkkywo.html

PHP:  $end->diff($start)->days;
来源：http://dali.cdnleiting.top/Article/details/gt2ucxbdxvs.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.andypj.xyz/Article/details/gt2mbqxhdaa.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jqgufenzy.top/Article/details/gt2xxxemghn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gzhubu.top/Article/details/gt2kbpcxcix.html

Go:   end.Sub(start).Hours()
来源：http://dali.hammf.cn/Article/details/gt2rtfumule.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhijiandao.cn/Article/details/gt2hhatmkgo.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhongyouzk.top/Article/details/gt2ubrfoens.html

[J07] 比较两个日期
来源：http://dali.kuanghao11.cn/Article/details/gt2weryjxxa.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gt2hcifzqnt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guannengcc.top/Article/details/gt2mlvngugl.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tianlin.xyz/Article/details/gt2bebwakbs.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tianlin.xyz/Article/details/gt2yavhfbcg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.iojbl.cn/Article/details/gt2gpgtgmvk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sufxvd.cn/Article/details/gt2rsphrsti.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gt2guqhudib.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gt2wdevylyb.html

[J08] 提取年月日与星期
来源：http://dali.chenjidiqi.icu/Article/details/gt2dcuwtuic.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhixingplan.top/Article/details/gt2xqzhzpbi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hysaishi.cn/Article/details/gt2gvjvijdd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daria6918.cn/Article/details/gt2vphsaffg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.havefunace.top/Article/details/gt2khmcwlno.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shzxlz.cn/Article/details/gt2hgrildbz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.feifeiyinyue.top/Article/details/gt2phwrbeha.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tian-w.cn/Article/details/gt2ajqovnzh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ivvv.top/Article/details/gt2yryvryfx.html

[J09] 时区处理
来源：http://dali.cdnleiting.top/Article/details/gt2gtwilbup.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jyoumei.cn/Article/details/gt2ejvzldhp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xuanzx.com/Article/details/gt2ctvmmllt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gt2fvxfpqyn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangdashe.top/Article/details/gt2jqbxjfzj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hfpthk.cn/Article/details/gt2mvcqewub.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jiagoushi.top/Article/details/gt2knspvqtq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigfzy.top/Article/details/gt2eiwdptdo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sufxvd.cn/Article/details/gt2pdlnbubp.html

[J10] 取今天 / 本月第一天
来源：http://dali.pengpengdd.cyou/Article/details/gt2pcrgomvy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.quarkkingdee.top/Article/details/gt2tsadcshm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zfxyutnt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.iojbl.cn/Article/details/gt2dmvxsopk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2lqzrmjtn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2bhwjmece.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.guowangkeji.top/Article/details/gt2rvrfsgzu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ivvv.top/Article/details/gt2oncqjorl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2psafjfad.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2xwjuykpq.html

K. JSON 与序列化
来源：http://dali.haohaochexian.top/Article/details/gt2wmvfumkv.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2buejzbrs.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxinkj.top/Article/details/gt2cxqwgbnd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhengqikj.top/Article/details/gt2lbkizmlx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jianghu66.top/Article/details/gt2jbujgbjo.html

JS:   JSON.stringify(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2bjorwamg.html

TS:   JSON.stringify(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2mrjbbgow.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yonumen.top/Article/details/gt2uqtnlvwl.html

Go:   json.Marshal(obj)
来源：http://dali.ybcxt.top/Article/details/gt2ajktdpfh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ehwqpu.com/Article/details/gt2kgxnaqny.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sxryk.cn/Article/details/gt2vagwzzba.html

[K02] JSON 字符串转对象
来源：http://dali.yonumen.top/Article/details/gt2abwdoifq.html

Py:   json.loads(s)
来源：http://dali.ehwqpu.com/Article/details/gt2skpvfknw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shzxlz.cn/Article/details/gt2vyunaliv.html

JS:   JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qsbgsesy.html

TS:   JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gt2errdfbjh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zjwctggx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ewlctotw.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gt2qnhiohkn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenlongwang.top/Article/details/gt2gfxvhxuo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yangfankeji.com/Article/details/gt2olqnfodv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xziqi.cn/Article/details/gt2yhzddcpd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cqqwz.cn/Article/details/gt2fxiftnqx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gt2mggajcdn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dkvsutzq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2ipljxhbc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj202588.top/Article/details/gt2mgltgxhi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnqzz.top/Article/details/gt2ccxshssj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.dashuyun.cn/Article/details/gt2bldxdrwb.html

[K04] 读取 JSON 文件
来源：http://dali.jinqigufen.top/Article/details/gt2xwediftq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cucudq.cn/Article/details/gt2lytjyejl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ssepuopk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jiagoushi.top/Article/details/gt2ddgdbcwq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2rcupwjzc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gt2hcehbnkq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jlsjyb.cn/Article/details/gt2zhubfoem.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gt2cycqvamf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tnmrzrxt.html

[K05] 深拷贝对象
来源：http://dali.xinyue.icu/Article/details/gt2njkfhkcu.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj202588.top/Article/details/gt2fqxxykrh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dashuyun.cn/Article/details/gt2ehoajazh.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ufotcpfc.html

TS:   structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2fzgcnnzy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ysjqemig.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yueranfly.top/Article/details/gt2vmzrzobh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gvrvjeai.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhiwuduotai.top/Article/details/gt2jdqlqeip.html

[K06] 解析 URL 查询串
来源：http://dali.jinqigfzy.top/Article/details/gt2kjsuljfq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.iojbl.cn/Article/details/gt2fjglzgei.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxuanxn.top/Article/details/gt2jjpbyoxc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dianchejie.cn/Article/details/gt2gfoevect.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.havefunace.top/Article/details/gt2lcoalgvi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hfpthk.cn/Article/details/gt2srwqcmoy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gt2mbjuiyjk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gt2kjhzfthx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gt2wrkmmehc.html

[K07] 进制转换
来源：http://dali.birdmap.top/Article/details/gt2hmqywilv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2zqkqkeiy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.guannengcc.top/Article/details/gt2qlbnuoyz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gt2dqmlbdbo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2wrjbjzla.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gt2xikwskwq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.wangshuangyany.cn/Article/details/gt2meqfqqwy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yuanzhike.top/Article/details/gt2ztqchuig.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2vnzrtqzu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hammf.cn/Article/details/gt2bzcidnly.html

Py:   pickle.dumps(obj)
来源：http://dali.redwolf501.top/Article/details/gt2ukjqxzsp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cdnleiting.top/Article/details/gt2vdpbxycz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.fzhhl.top/Article/details/gt2aybywalo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gt2xkllqjrt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jyoumei.cn/Article/details/gt2ddsoiypw.html

Go:   encoding/gob
来源：http://dali.cashguo.top/Article/details/gt2qjynihli.html

Ruby: Marshal.dump(obj)
来源：http://dali.mhx1999.top/Article/details/gt2ojzkyank.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yongpay.top/Article/details/gt2rwyammze.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2qhcftkhf.html

L. 网络请求
来源：http://dali.ehwqpu.com/Article/details/gt2umtbnzhf.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2gykpclsx.html

[L01] 发送 GET 请求
来源：http://dali.haohaochexian.top/Article/details/gt2wiogslmh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenjidiqi.icu/Article/details/gt2xgitvmyn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.vqdsnc.cn/Article/details/gt2waafsmgh.html

JS:   await fetch(url)
来源：http://dali.yongpay.top/Article/details/gt2grpmhksv.html

TS:   await fetch(url)
来源：http://dali.guannengcc.top/Article/details/gt2lnfitvkd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hammf.cn/Article/details/gt2lzmdckbf.html

Go:   resp, err := http.Get(url)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kmjvkjlv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gzhubu.top/Article/details/gt2ncgzkqqb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yueranfly.top/Article/details/gt2polvijzq.html

[L02] 发送 POST JSON
来源：http://dali.0kj1m.cn/Article/details/gt2akwszfnr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nanxuanxn.top/Article/details/gt2pxistpfa.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinqigfzy.top/Article/details/gt2wxklbxzc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.feifeiyinyue.top/Article/details/gt2vligkyty.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhixingplan.top/Article/details/gt2vbqtcabl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sufxvd.cn/Article/details/gt2dkbsdnqb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.havefunace.top/Article/details/gt2kxwylnfl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yxmnjbmk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gotoacloud.top/Article/details/gt2lewbqhiz.html

[L03] 设置自定义请求头
来源：http://dali.cashguo.top/Article/details/gt2hjkongji.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.birdmap.top/Article/details/gt2inaehrtq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.fengsongda.top/Article/details/gt2lzarozgw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yueranfly.top/Article/details/gt2zkqwambv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.bjfxy.top/Article/details/gt2pwyusjxq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinqigufen.top/Article/details/gt2ecktosvl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jiagoushi.top/Article/details/gt2xjpvjjuz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhoulong.xyz/Article/details/gt2azjpxezf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nanxinkj.top/Article/details/gt2admipqzd.html

[L04] 设置超时
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oqzfigyr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.fengsongda.top/Article/details/gt2ycujjelm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wbscyipa.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ybcxt.top/Article/details/gt2rzzdmhte.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jiagoushi.top/Article/details/gt2dlqwmror.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cashguo.top/Article/details/gt2hcsbdxql.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenjidiqi.icu/Article/details/gt2srgpdnrl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.birdmap.top/Article/details/gt2fvtwxbjx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jiagoushi.top/Article/details/gt2nryjeemt.html

[L05] 上传文件（multipart）
来源：http://dali.zycfv.cn/Article/details/gt2gubwuwxt.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tanke756.top/Article/details/gt2fstpuxoo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.meibo888.top/Article/details/gt2rcnobiii.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ybcxt.top/Article/details/gt2rnurrdhb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gt2ttbrmtfp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hongshengwenyu.top/Article/details/gt2xxwybgtl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.fzhhl.top/Article/details/gt2ggfajpjc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xuetiantiany.cn/Article/details/gt2oqzcnprn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2foqnoise.html

[L06] 解析响应为 JSON
来源：http://dali.daxiang520.top/Article/details/gt2ixgljphd.html

Py:   resp.json()
来源：http://dali.ydzc1.top/Article/details/gt2oimkuton.html

PHP:  json_decode($body, true);
来源：http://dali.chenlongwang.top/Article/details/gt2nnbtrgqh.html

JS:   await resp.json()
来源：http://dali.svipenyu.cn/Article/details/gt2tlxyebsp.html

TS:   await resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gt2oiycmsbb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gt2jcfsacmd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yonumen.top/Article/details/gt2qzjugovs.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xinyue.icu/Article/details/gt2jxqdppgl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.pycfn.com/Article/details/gt2vpowjsek.html

[L07] 处理 HTTP 状态码
来源：http://dali.gzhubu.top/Article/details/gt2xfdxwaav.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jgqzthur.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.mhx1999.top/Article/details/gt2dksahdgl.html

JS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gt2ymsxsrst.html

TS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gt2wggzqyus.html

Java: resp.statusCode()
来源：http://dali.jinqigfzy.top/Article/details/gt2sxfdelsk.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqmttlw.html

Ruby: resp.code.to_i
来源：http://dali.hammf.cn/Article/details/gt2onnpclsc.html

C#:   (int)resp.StatusCode
来源：http://dali.zycfv.cn/Article/details/gt2mbmnqcoe.html

[L08] 并发请求多个地址
来源：http://dali.cashguo.top/Article/details/gt2iuroxbgj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.daria6918.cn/Article/details/gt2zymnsobe.html

PHP:  curl_multi_init() 系列
来源：http://dali.iojbl.cn/Article/details/gt2nboxfjgc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gt2wffmbbrx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gt2evykkilo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.meibo888.top/Article/details/gt2gombrbjg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hfpthk.cn/Article/details/gt2jubockvm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gt2tkfuncda.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xziqi.cn/Article/details/gt2nnjattad.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2xhoeigih.html

M. 命令行 / 进程 / 环境
来源：http://dali.andypj.xyz/Article/details/gt2tgkgycte.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bygczciw.html

[M01] 读取命令行参数
来源：http://dali.cheryme.top/Article/details/gt2opmdomfv.html

Py:   sys.argv[1:]
来源：http://dali.gogol.net.cn/Article/details/gt2usyednwz.html

PHP:  $argv;  $argc;
来源：http://dali.jyoumei.cn/Article/details/gt2bkjneymm.html

JS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gt2afbjijpo.html

TS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gt2nafgkbsw.html

Java: args 数组（main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gt2dihpndvc.html

Go:   os.Args[1:]
来源：http://dali.nwbrower.top/Article/details/gt2vtfdfgmd.html

Ruby: ARGV
来源：http://dali.guannengcc.top/Article/details/gt2oodrqcxs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258.top/Article/details/gt2dyvueqfy.html

[M02] 读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gt2vslwykfc.html

Py:   os.environ.get("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zageeist.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gt2umvrxknx.html

JS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gt2pgzqzzop.html

TS:   process.env.HOME
来源：http://dali.gzhubu.top/Article/details/gt2jvfdhown.html

Java: System.getenv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gt2arbhherv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xuanzx.com/Article/details/gt2wwuwwqru.html

Ruby: ENV["HOME"]
来源：http://dali.wangdashe.top/Article/details/gt2ixidqkug.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fzhhl.top/Article/details/gt2yznandms.html

[M03] 执行外部命令
来源：http://dali.hnxiangtu.top/Article/details/gt2zvsfizem.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hysaishi.cn/Article/details/gt2fonoszmp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hnqzz.top/Article/details/gt2oeafcjxa.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenjidiqi.icu/Article/details/gt2lhiknqam.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xylfe.cn/Article/details/gt2dqviotbk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.kuanghao11.cn/Article/details/gt2hjtrepxo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aizwys.cn/Article/details/gt2mskfaahl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhengqikj.top/Article/details/gt2misargcn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aizwys.cn/Article/details/gt2amzznmtx.html

[M04] 获取当前工作目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rpwpkaov.html

Py:   os.getcwd()
来源：http://dali.nanxinkj.top/Article/details/gt2gutususn.html

PHP:  getcwd();
来源：http://dali.jinqigfzy.top/Article/details/gt2eqgmcphn.html

JS:   process.cwd()
来源：http://dali.cqqwz.cn/Article/details/gt2gfujyxfd.html

TS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gt2dwfegrcy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.quarkkingdee.top/Article/details/gt2ymkyqomo.html

Go:   os.Getwd()
来源：http://dali.yueranfly.top/Article/details/gt2wahgvtly.html

Ruby: Dir.pwd
来源：http://dali.hammf.cn/Article/details/gt2dezffowc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.havefunace.top/Article/details/gt2bhfvmkee.html

[M05] 设置退出码
来源：http://dali.ybcxt.top/Article/details/gt2ytmwkmmy.html

Py:   sys.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gt2dbdvegbq.html

PHP:  exit(1);
来源：http://dali.shangyingyoupin.top/Article/details/gt2mzmpjwhl.html

JS:   process.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gt2hcafqlke.html

TS:   process.exit(1)
来源：http://dali.bjfxy.top/Article/details/gt2zighdbcz.html

Java: System.exit(1)
来源：http://dali.sweek.top/Article/details/gt2cgepzcun.html

Go:   os.Exit(1)
来源：http://dali.ivvv.top/Article/details/gt2ovbbmeak.html

Ruby: exit 1
来源：http://dali.yanxiufei.cn/Article/details/gt2eiueumqa.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yongpay.top/Article/details/gt2tbvhblkd.html

[M06] 向标准错误输出
来源：http://dali.hnxiangtu.top/Article/details/gt2dfecqqbn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hywenlv.cn/Article/details/gt2krnrmuho.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cotzgyri.html

JS:   console.error("err")
来源：http://dali.yonumen.top/Article/details/gt2fngpvdce.html

TS:   console.error("err")
来源：http://dali.redwolf501.top/Article/details/gt2gypzwxrd.html

Java: System.err.println("err")
来源：http://dali.xuanzx.com/Article/details/gt2ugiyhnmo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenlongwang.top/Article/details/gt2lusyqtff.html

Ruby: warn "err"
来源：http://dali.chenlongwang.top/Article/details/gt2qzguvwfe.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zdqjudy.top/Article/details/gt2tcrjmfvc.html

[M07] 判断是否为主入口
来源：http://dali.aizwys.cn/Article/details/gt2jtlpajhe.html

Py:   if __name__ == "__main__":
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vtlnnlcp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hammf.cn/Article/details/gt2ohmmztlf.html

JS:   require.main === module
来源：http://dali.xylfe.cn/Article/details/gt2vthbfvrv.html

TS:   require.main === module
来源：http://dali.haohaochexian.top/Article/details/gt2bohtkejl.html

Java: public static void main(String[] args)
来源：http://dali.tanke756.top/Article/details/gt2rlvcdtzx.html

Go:   func main()
来源：http://dali.yangfankeji.com/Article/details/gt2ypsvukob.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hrvmecvb.html

C#:   static void Main(string[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mnvockxt.html


<!-- 参考信息 -->