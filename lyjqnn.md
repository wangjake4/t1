代发 wailian999

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.chenlongwang.top/Article/details/gtrjjurseu.html

JS:   new Date();  Date.now()
来源：http://dali.yj202588.top/Article/details/gtscqvodep.html

TS:   new Date();  Date.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxomgjkvk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cheryme.top/Article/details/gtzubdrsda.html

Go:   time.Now()
来源：http://dali.zhiwuduotai.top/Article/details/gtgwwfiwpz.html

Ruby: Time.now
来源：http://dali.xuetiantiany.cn/Article/details/gttsohltor.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xinyue.icu/Article/details/gtaaynocvk.html

[J02] 格式化输出
来源：http://dali.redwolf501.top/Article/details/gtjkhkfwne.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ydzc1.top/Article/details/gtiyhujmbc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gtfytwxmcg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daria6918.cn/Article/details/gtvrvesxkx.html

TS:   d.toISOString()
来源：http://dali.kuanghao11.cn/Article/details/gtxocixaal.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.316326.xyz/Article/details/gtqboqsqcp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daria6918.cn/Article/details/gtfsqrbwmf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhengqikj.top/Article/details/gtsadzbhdn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenjidiqi.icu/Article/details/gttitxugnc.html

[J03] 字符串解析为日期
来源：http://dali.zhijiandao.cn/Article/details/gtdzlyjcdj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.snrcjt.cn/Article/details/gtvzfesunl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.iojbl.cn/Article/details/gtpuvaoufp.html

JS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtettdzeyb.html

TS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtwjchdozg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtfppzspaf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtugzvbump.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtbzbsodco.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guannengcc.top/Article/details/gtohpgodhh.html

[J04] 时间戳与日期互转
来源：http://dali.vqdsnc.cn/Article/details/gtugnhjzzb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrgbukays.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.vqdsnc.cn/Article/details/gtzgkhawje.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daria6918.cn/Article/details/gtcvoqtgxi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yangfankeji.com/Article/details/gtcbebilyq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.guowangkeji.top/Article/details/gtnqtidlfv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhengqikj.top/Article/details/gtclhntbhb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtuefrapjz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.fzhhl.top/Article/details/gtxzgactho.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gtuengivjl.html

Py:   now + timedelta(days=7)
来源：http://dali.pycfn.com/Article/details/gthtcvveob.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.birdmap.top/Article/details/gttaejimon.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkewbvksq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhixingplan.top/Article/details/gtcpmdqssw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hysaishi.cn/Article/details/gtpttvajmv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.0kj1m.cn/Article/details/gthgcnmkwh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gaohongyu789.top/Article/details/gtwrmctrbi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jianghu66.top/Article/details/gtdwatmswh.html

[J06] 计算两时间之差
来源：http://dali.wangdashe.top/Article/details/gtljpeqbiv.html

Py:   (end - start).total_seconds()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbybiptsr.html

PHP:  $end->diff($start)->days;
来源：http://dali.xinyue.icu/Article/details/gtmhvlnuwa.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zdqjudy.top/Article/details/gtcokswetz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ivvv.top/Article/details/gtensbclul.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlcviglre.html

Go:   end.Sub(start).Hours()
来源：http://dali.nanxuanxn.top/Article/details/gtukbbvbqz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yanxiufei.cn/Article/details/gturvwedfp.html

C#:   (end - start).TotalSeconds
来源：http://dali.hnxiangtu.top/Article/details/gtezmdpagu.html

[J07] 比较两个日期
来源：http://dali.yueranfly.top/Article/details/gtvqddtehj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtywrfmfud.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ydzc1.top/Article/details/gtpuyxpeny.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cdnleiting.top/Article/details/gtwaijrajl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gteobwfgzc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ydzc1.top/Article/details/gtwrapsuka.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnqzz.top/Article/details/gtucusxroi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gtybacebht.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gtyhbxwemb.html

[J08] 提取年月日与星期
来源：http://dali.hywenlv.cn/Article/details/gtrgjmkzri.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aibaodan.cn/Article/details/gtnthjgxoh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.haohaochexian.top/Article/details/gtrjusyalz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.wangshuangyany.cn/Article/details/gtmihjkhkf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhongyouzk.top/Article/details/gtitjmuvuf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfexxwya.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.kuanghao11.cn/Article/details/gtzhrscegh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sufxvd.cn/Article/details/gtazdypbny.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqenfprjg.html

[J09] 时区处理
来源：http://dali.feifeiyinyue.top/Article/details/gtjdmuscuw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.haohaochexian.top/Article/details/gtahliykap.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sufxvd.cn/Article/details/gtugkxjugz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgfzy.top/Article/details/gtrahisolc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.birdmap.top/Article/details/gtwobivajy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yonumen.top/Article/details/gtebebyilu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.dashuyun.cn/Article/details/gtpefunrai.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jyoumei.cn/Article/details/gtmimcjecn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.quarkkingdee.top/Article/details/gtqmpmniig.html

[J10] 取今天 / 本月第一天
来源：http://dali.hysaishi.cn/Article/details/gtrzoykiec.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtctnyuzmb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgfzy.top/Article/details/gtuymyqthg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgfzy.top/Article/details/gtayqzfhpq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fengsongda.top/Article/details/gtjvnzcdtn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sysykeji.top/Article/details/gthjpuhgsi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hysaishi.cn/Article/details/gtgpytjbgr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.daria6918.cn/Article/details/gtkltjbauq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.havefunace.top/Article/details/gtqjfhglgq.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtmuyhkryn.html

K. JSON 与序列化
来源：http://dali.dianchejie.cn/Article/details/gtxlxgzklv.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtidayjezp.html

[K01] 对象转 JSON 字符串
来源：http://dali.shuidangran.top/Article/details/gtmeaqdilp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gteswmrxxp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.daria6918.cn/Article/details/gtqntsyirw.html

JS:   JSON.stringify(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtsydnbbxr.html

TS:   JSON.stringify(obj)
来源：http://dali.daria6918.cn/Article/details/gtqgruzvdd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.mhx1999.top/Article/details/gtbchlwcsk.html

Go:   json.Marshal(obj)
来源：http://dali.xylfe.cn/Article/details/gttxnakkoa.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhiwuduotai.top/Article/details/gtimohavpy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtahpjqnoq.html

[K02] JSON 字符串转对象
来源：http://dali.shzxlz.cn/Article/details/gtseruejzp.html

Py:   json.loads(s)
来源：http://dali.zhixingplan.top/Article/details/gtrwdjfqjc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.daria6918.cn/Article/details/gtbzohyqec.html

JS:   JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gttefcoznu.html

TS:   JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gtcqpmsncw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shzxlz.cn/Article/details/gtuzuyupkg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.iojbl.cn/Article/details/gtrenmwjay.html

Ruby: JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtwtjxpupo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jlsjyb.cn/Article/details/gtjzyxfqcm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daria6918.cn/Article/details/gtscezxerq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.316326.xyz/Article/details/gtaqbewujo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dashuyun.cn/Article/details/gtoyyirueq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cashguo.top/Article/details/gtbpatenak.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.birdmap.top/Article/details/gtkpefjydy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj20258.top/Article/details/gtzfzdlqti.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hnqzz.top/Article/details/gtojrhfswz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.snrcjt.cn/Article/details/gtcstxidwq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.dashuyun.cn/Article/details/gtfcpoeruo.html

[K04] 读取 JSON 文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqznhccdb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.dianchejie.cn/Article/details/gtypxzuzsh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jianghu66.top/Article/details/gtsgkxdvqb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.haohaochexian.top/Article/details/gtzejaowom.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgfzy.top/Article/details/gtqbphbgne.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ivvv.top/Article/details/gtexrsxfko.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.pycfn.com/Article/details/gtcshksaem.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yangfankeji.com/Article/details/gtqxgfiqvl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.aibaodan.cn/Article/details/gtwwcahwfx.html

[K05] 深拷贝对象
来源：http://dali.svipenyu.cn/Article/details/gtnorzjhoh.html

Py:   copy.deepcopy(obj)
来源：http://dali.jiagoushi.top/Article/details/gtafbocljw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.c1oappe.top/Article/details/gtkqhlhbhh.html

JS:   structuredClone(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjprrjkcp.html

TS:   structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gtihjrkmwn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.aibaodan.cn/Article/details/gtztzmzidz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nanxinkj.top/Article/details/gturwwppig.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zycfv.cn/Article/details/gtntpjvojp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.0kj1m.cn/Article/details/gtgxrxnbzb.html

[K06] 解析 URL 查询串
来源：http://dali.daxiang520.top/Article/details/gttsxhjeqa.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gtosrwnqpp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gzhubu.top/Article/details/gtokwyxqcr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gtesigrepc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hammf.cn/Article/details/gtyghtgyam.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.feifeiyinyue.top/Article/details/gtouffhrzx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gtxcxkcbce.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gtqqfhpybd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gtninnpcxg.html

[K07] 进制转换
来源：http://dali.cheryme.top/Article/details/gtjqfjrggj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtpgerquee.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jyoumei.cn/Article/details/gtmmroklyy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gtwpxndenw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtevuqyimg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtgkkzhkwt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shuidangran.top/Article/details/gtvqaarjuv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hywenlv.cn/Article/details/gtsuakbeey.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtezzjxhyx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.aizwys.cn/Article/details/gtbbbnwakx.html

Py:   pickle.dumps(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtmacenfbm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cashguo.top/Article/details/gtkkgdqchq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.smart0.xyz/Article/details/gtqyozqaar.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gtfkfkincq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zycfv.cn/Article/details/gttoiaishj.html

Go:   encoding/gob
来源：http://dali.bjfxy.top/Article/details/gtkpqojltn.html

Ruby: Marshal.dump(obj)
来源：http://dali.jyoumei.cn/Article/details/gtcqqzycmb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yvedp.cn/Article/details/gtxontgrwf.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtieeekbla.html

L. 网络请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuaoitltv.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzzhdsnk.html

[L01] 发送 GET 请求
来源：http://dali.yuxming.cn/Article/details/gtthacqtty.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.meibo888.top/Article/details/gtizbbqnya.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xylfe.cn/Article/details/gtcjoyvpko.html

JS:   await fetch(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtrwmrsypr.html

TS:   await fetch(url)
来源：http://dali.dashuyun.cn/Article/details/gtlrpjhthu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinqigfzy.top/Article/details/gtbrsiunew.html

Go:   resp, err := http.Get(url)
来源：http://dali.jiagoushi.top/Article/details/gtsxquftap.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.wangshuangyany.cn/Article/details/gtpsvvahky.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.daria6918.cn/Article/details/gtpcgjhsoy.html

[L02] 发送 POST JSON
来源：http://dali.tanke756.top/Article/details/gttlmqdawd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xylfe.cn/Article/details/gtncinijbx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yuxming.cn/Article/details/gtxqcizpmu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daxiang520.top/Article/details/gtttvxjqof.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gttnrhgslp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnoajacpe.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ehwqpu.com/Article/details/gtnlvvkqrv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.redwolf501.top/Article/details/gtxhdbijjw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfkhwmcgd.html

[L03] 设置自定义请求头
来源：http://dali.yanxiufei.cn/Article/details/gtbwdelobq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dianchejie.cn/Article/details/gtpuizskth.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sweek.top/Article/details/gtiaouxfhu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hongshengwenyu.top/Article/details/gtbuxoulzc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gtdmbjjfdo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ppjwa.cn/Article/details/gtudkbsdqe.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yvedp.cn/Article/details/gtbmpzizcm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinqigfzy.top/Article/details/gteqkkgfnj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gtvkxnjuna.html

[L04] 设置超时
来源：http://dali.aizwys.cn/Article/details/gtmmoclzkd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cqqwz.cn/Article/details/gtyfdgufyx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.0kj1m.cn/Article/details/gtwxvfgrko.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gtwdcyjnbl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dianchejie.cn/Article/details/gtzyxnzxqy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhengqikj.top/Article/details/gtavlierbm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhiwuduotai.top/Article/details/gtctugwskf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shangyingyoupin.top/Article/details/gtcltetuls.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.havefunace.top/Article/details/gtbynbqgal.html

[L05] 上传文件（multipart）
来源：http://dali.yvedp.cn/Article/details/gtdnbrdubj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenjidiqi.icu/Article/details/gtmmlwrhph.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gtpzmksats.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxuanxn.top/Article/details/gtzugppoff.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gtepuoovpz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nanxuanxn.top/Article/details/gtszabhuwy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gzhubu.top/Article/details/gtncydcvcr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwavryuwn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nwbrower.top/Article/details/gtwdaczzaf.html

[L06] 解析响应为 JSON
来源：http://dali.xuetiantiany.cn/Article/details/gtvltiyxnx.html

Py:   resp.json()
来源：http://dali.tanke756.top/Article/details/gthxcwtplq.html

PHP:  json_decode($body, true);
来源：http://dali.andypj.xyz/Article/details/gtqvplboxe.html

JS:   await resp.json()
来源：http://dali.zdqjudy.top/Article/details/gtkrnecxir.html

TS:   await resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaabcvycd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gtyaqoylau.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nwbrower.top/Article/details/gtexndayhp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxinkj.top/Article/details/gtbwqfbmsy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.snrcjt.cn/Article/details/gtzuamrcir.html

[L07] 处理 HTTP 状态码
来源：http://dali.shzxlz.cn/Article/details/gtbtdizjnp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nanxinkj.top/Article/details/gtshfoclew.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cqqwz.cn/Article/details/gtcwoxcxdm.html

JS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gtliqkjqxq.html

TS:   resp.ok;  resp.status
来源：http://dali.chenzaomai.com/Article/details/gtmrqyhgzf.html

Java: resp.statusCode()
来源：http://dali.aizwys.cn/Article/details/gtgcrmshgv.html

Go:   resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gtcbsxnyow.html

Ruby: resp.code.to_i
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgenayclk.html

C#:   (int)resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gttliurucb.html

[L08] 并发请求多个地址
来源：http://dali.zdqjudy.top/Article/details/gtwmmaoymn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.iojbl.cn/Article/details/gtvqpgksei.html

PHP:  curl_multi_init() 系列
来源：http://dali.ivvv.top/Article/details/gtrytbnryd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zycfv.cn/Article/details/gtjcrcaeet.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gtpoibnyas.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cheryme.top/Article/details/gtulkpvpum.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.guannengcc.top/Article/details/gtliunowji.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenlongwang.top/Article/details/gtwcjifiuy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hammf.cn/Article/details/gttrwfkfnf.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcxyocodr.html

M. 命令行 / 进程 / 环境
来源：http://dali.ydzc1.top/Article/details/gtbsiqdazt.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtpocbxfav.html

[M01] 读取命令行参数
来源：http://dali.nanxuanxn.top/Article/details/gtecjxoebs.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gtnxdgmdqm.html

PHP:  $argv;  $argc;
来源：http://dali.hywenlv.cn/Article/details/gtwdtqfykk.html

JS:   process.argv.slice(2)
来源：http://dali.daria6918.cn/Article/details/gthbwccdlq.html

TS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gtgnlnzubu.html

Java: args 数组（main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gtvmyayegx.html

Go:   os.Args[1:]
来源：http://dali.chenlongwang.top/Article/details/gtqqxkiyxo.html

Ruby: ARGV
来源：http://dali.yvedp.cn/Article/details/gtmxfbukgo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.c1oappe.top/Article/details/gtapllgnmd.html

[M02] 读取环境变量
来源：http://dali.0kj1m.cn/Article/details/gtsrwgasrh.html

Py:   os.environ.get("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtdorgeurb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.andypj.xyz/Article/details/gtjfndgxla.html

JS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gtbwoljfst.html

TS:   process.env.HOME
来源：http://dali.sufxvd.cn/Article/details/gtjexbguey.html

Java: System.getenv("HOME")
来源：http://dali.ydzc1.top/Article/details/gtbvkgjgxh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpuooemak.html

Ruby: ENV["HOME"]
来源：http://dali.0kj1m.cn/Article/details/gtxtxtcsvk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nwbrower.top/Article/details/gtpxcxojgm.html

[M03] 执行外部命令
来源：http://dali.zhoulong.xyz/Article/details/gthenyodau.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj20258888.top/Article/details/gtlythjwwa.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jianghu66.top/Article/details/gtaixbcopj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hfpthk.cn/Article/details/gtgtikvpcn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtjpvtlscr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cheryme.top/Article/details/gtrhnerdpx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.fengsongda.top/Article/details/gtlqssbeoz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sysykeji.top/Article/details/gtxsiqiphw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ybcxt.top/Article/details/gtyyvwpgir.html

[M04] 获取当前工作目录
来源：http://dali.cheryme.top/Article/details/gtwsrwswqw.html

Py:   os.getcwd()
来源：http://dali.havefunace.top/Article/details/gtfdrsfocm.html

PHP:  getcwd();
来源：http://dali.nwbrower.top/Article/details/gtowdifnlz.html

JS:   process.cwd()
来源：http://dali.daxiang520.top/Article/details/gthbicymng.html

TS:   process.cwd()
来源：http://dali.yj202588.top/Article/details/gtdbnmuvzg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.9152youxi.cn/Article/details/gtcdbpyprm.html

Go:   os.Getwd()
来源：http://dali.ppjwa.cn/Article/details/gtaqzcuxse.html

Ruby: Dir.pwd
来源：http://dali.zhixingplan.top/Article/details/gtzyogczfz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pengpengdd.cyou/Article/details/gtkvzxkpic.html

[M05] 设置退出码
来源：http://dali.gotoacloud.top/Article/details/gtjywxbcms.html

Py:   sys.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtvjaezexp.html

PHP:  exit(1);
来源：http://dali.hnxiangtu.top/Article/details/gthnsqzzeq.html

JS:   process.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtpztslqum.html

TS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gthqxdpzid.html

Java: System.exit(1)
来源：http://dali.iojbl.cn/Article/details/gteggnmyhn.html

Go:   os.Exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtybycxgbl.html

Ruby: exit 1
来源：http://dali.iojbl.cn/Article/details/gtfgtervgd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fengsongda.top/Article/details/gtixuiohvw.html

[M06] 向标准错误输出
来源：http://dali.xinyue.icu/Article/details/gtiggpeahx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hywenlv.cn/Article/details/gtushpccov.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.vqdsnc.cn/Article/details/gtdnrghdrc.html

JS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gtcavgspak.html

TS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gtjqrepckf.html

Java: System.err.println("err")
来源：http://dali.jqgufenzy.top/Article/details/gtjhwlwbyt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daxiang520.top/Article/details/gtppqloith.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gtjimxyorq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrndxwyhq.html

[M07] 判断是否为主入口
来源：http://dali.gzhubu.top/Article/details/gttkwafvvg.html

Py:   if __name__ == "__main__":
来源：http://dali.aibaodan.cn/Article/details/gtzejeaydq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj202588.top/Article/details/gtrhyvrilz.html

JS:   require.main === module
来源：http://dali.gogol.net.cn/Article/details/gtvepxfifx.html

TS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gtcxgxaiwv.html


<!-- 参考信息 -->