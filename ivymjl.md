代发 wailian999

J. 日期与时间
来源：http://dali.haohaochexian.top/Article/details/gtrhulfgjw.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqbzvpcay.html

[J01] 获取当前时间
来源：http://dali.sweek.top/Article/details/gtctmubudx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnsqdmlcx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.aibaodan.cn/Article/details/gtzwnpqpxy.html

JS:   new Date();  Date.now()
来源：http://dali.ehwqpu.com/Article/details/gtajjnbliq.html

TS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gtqdvkkvdn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvkmfzyft.html

Go:   time.Now()
来源：http://dali.nanxinkj.top/Article/details/gtpuqzlamp.html

Ruby: Time.now
来源：http://dali.jinqigufen.top/Article/details/gtdwoulwbm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.haohaochexian.top/Article/details/gtmhyuwhqi.html

[J02] 格式化输出
来源：http://dali.shanyushiyangtech.top/Article/details/gttxurdzvp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigfzy.top/Article/details/gtpkjzviuh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gtjhhjkelr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nanxuanxn.top/Article/details/gtcsokvrhy.html

TS:   d.toISOString()
来源：http://dali.yongpay.top/Article/details/gtflyecdoy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinqigfzy.top/Article/details/gtbnlfkkaw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yangfankeji.com/Article/details/gtvmhymyxx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenlongwang.top/Article/details/gtheecnste.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yuanzhike.top/Article/details/gtxfagvmso.html

[J03] 字符串解析为日期
来源：http://dali.hywenlv.cn/Article/details/gtkrkldznw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.havefunace.top/Article/details/gtijxtpcoc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangdashe.top/Article/details/gteltkibwj.html

JS:   new Date("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtakoiphsq.html

TS:   new Date("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gtymuafuzg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtgufxiphw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtlvwohgod.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gthfqmihaz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.svipenyu.cn/Article/details/gtstvybhxc.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258.top/Article/details/gtvjgsufgx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xuanzx.com/Article/details/gttxpsihus.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxjeeecve.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.svipenyu.cn/Article/details/gtyehbyupz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdjdyogo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gogol.net.cn/Article/details/gtxivvysib.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cashguo.top/Article/details/gtlnvmrwvv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jiagoushi.top/Article/details/gtikjtrybh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhengqikj.top/Article/details/gtlwgtvxxw.html

[J05] 时间加减（加 7 天）
来源：http://dali.jiagoushi.top/Article/details/gtsoyxddlo.html

Py:   now + timedelta(days=7)
来源：http://dali.gogol.net.cn/Article/details/gtqwsvvhjf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hongshengwenyu.top/Article/details/gttjrmoemd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenjidiqi.icu/Article/details/gtuhwcwddg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gtagzveobn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fengsongda.top/Article/details/gtpvwsdyvh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhijiandao.cn/Article/details/gtynlbguzn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gaohongyu789.top/Article/details/gttkjaprwq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jyoumei.cn/Article/details/gtambgvshr.html

[J06] 计算两时间之差
来源：http://dali.hfpthk.cn/Article/details/gtohjxiygy.html

Py:   (end - start).total_seconds()
来源：http://dali.jyoumei.cn/Article/details/gtikofrbdx.html

PHP:  $end->diff($start)->days;
来源：http://dali.birdmap.top/Article/details/gtykbdhnms.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hnqzz.top/Article/details/gtymtjuvlo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258888.top/Article/details/gttjujcncu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhoulong.xyz/Article/details/gtimqcnkgf.html

Go:   end.Sub(start).Hours()
来源：http://dali.guannengcc.top/Article/details/gtksuexcrl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jiagoushi.top/Article/details/gtuwbkuyws.html

C#:   (end - start).TotalSeconds
来源：http://dali.jqgfzy.top/Article/details/gthzkigphr.html

[J07] 比较两个日期
来源：http://dali.yj20258.top/Article/details/gtqlpsbops.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gtghjildej.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.redwolf501.top/Article/details/gtowlgtulc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shangyingyoupin.top/Article/details/gtunncsgwy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.dianchejie.cn/Article/details/gtidyzfeyy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyyxxjgxc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fzhhl.top/Article/details/gtyduwkgar.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gtmqowyymv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdejfibg.html

[J08] 提取年月日与星期
来源：http://dali.zhoulong.xyz/Article/details/gtkvxjrrbd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gaohongyu789.top/Article/details/gtffyvcjgd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cdnleiting.top/Article/details/gtqrulqmvc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.svipenyu.cn/Article/details/gtdrgcwbpi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yuxming.cn/Article/details/gtnlpxwaza.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnxiangtu.top/Article/details/gtbdqgaipn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hysaishi.cn/Article/details/gtjikhoaum.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmbawvyn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj20258888.top/Article/details/gtyzdfnces.html

[J09] 时区处理
来源：http://dali.0kj1m.cn/Article/details/gtegjcsipe.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yvedp.cn/Article/details/gtcexzkenz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shangyingyoupin.top/Article/details/gtjbsoiqqn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tianlin.xyz/Article/details/gtivnpfwtf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fzhhl.top/Article/details/gtqeqrrycl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.aibaodan.cn/Article/details/gtiwqjurwz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tianlin.xyz/Article/details/gthqcrngrd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangdashe.top/Article/details/gtussondmq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shangyingyoupin.top/Article/details/gttexmyzbd.html

[J10] 取今天 / 本月第一天
来源：http://dali.316326.xyz/Article/details/gtkqnrdinq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gogol.net.cn/Article/details/gtkfyhvytd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yangfankeji.com/Article/details/gtvudecvri.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xinyue.icu/Article/details/gtrorfyijx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.snrcjt.cn/Article/details/gtbvzsmfvi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yvedp.cn/Article/details/gtwpcijqge.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hysaishi.cn/Article/details/gtjeuzhebk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.quarkkingdee.top/Article/details/gtacoavnux.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.quarkkingdee.top/Article/details/gtllwnupoz.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtorjtsjzm.html

K. JSON 与序列化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlufdavjg.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtkkjzogch.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenjidiqi.icu/Article/details/gttgkscyse.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvbeirwhy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenjidiqi.icu/Article/details/gtpttgotmg.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gtqejiwphm.html

TS:   JSON.stringify(obj)
来源：http://dali.yuanzhike.top/Article/details/gtrgomvzct.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.feifeiyinyue.top/Article/details/gteuqxzgah.html

Go:   json.Marshal(obj)
来源：http://dali.yongpay.top/Article/details/gtcxbparww.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinghuilouyu.cn/Article/details/gtjydvzlzn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.0kj1m.cn/Article/details/gtsnylmdrl.html

[K02] JSON 字符串转对象
来源：http://dali.yongpay.top/Article/details/gtvnwlcdnn.html

Py:   json.loads(s)
来源：http://dali.ppjwa.cn/Article/details/gtzlglrjpo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nwbrower.top/Article/details/gtslwaucru.html

JS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuqefdydc.html

TS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gtkebmujnp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hnqzz.top/Article/details/gtjrvmctez.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gtacqgctyk.html

Ruby: JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtdwdnpfqb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yangfankeji.com/Article/details/gtkotaiokb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258888.top/Article/details/gtvpagadyq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.guowangkeji.top/Article/details/gthhlvwrjk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gtpxzsddlj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.9152youxi.cn/Article/details/gtrslbcxmf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cdnleiting.top/Article/details/gtsserycpr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guannengcc.top/Article/details/gtrfwkwdde.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sufxvd.cn/Article/details/gtegggabcw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtpaijpame.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zycfv.cn/Article/details/gtrrgfrlwt.html

[K04] 读取 JSON 文件
来源：http://dali.hysaishi.cn/Article/details/gttnfriyqh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ivvv.top/Article/details/gtatyofair.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.guannengcc.top/Article/details/gtgzalgenx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuanzx.com/Article/details/gtjtwinxoi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gtihtuqzid.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gtgspvqcbq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hammf.cn/Article/details/gtyfotlgvh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jqgfzy.top/Article/details/gtnweukxdu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yangfankeji.com/Article/details/gtkkjgiwco.html

[K05] 深拷贝对象
来源：http://dali.ybcxt.top/Article/details/gtnxbbwbov.html

Py:   copy.deepcopy(obj)
来源：http://dali.guannengcc.top/Article/details/gtmtigeytp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gotoacloud.top/Article/details/gtpbuvzasg.html

JS:   structuredClone(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtlfazmazr.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gteyqjluns.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sufxvd.cn/Article/details/gttakeazsf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sweek.top/Article/details/gtylfdzhzn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhongyouzk.top/Article/details/gtogdutlrm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinqigfzy.top/Article/details/gtxqueivlv.html

[K06] 解析 URL 查询串
来源：http://dali.xuanzx.com/Article/details/gtmcqupnjy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.fengsongda.top/Article/details/gtumtlnhqu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.smart0.xyz/Article/details/gtlnfztgvh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigufen.top/Article/details/gtczdkbhav.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ivvv.top/Article/details/gtqxjmhybf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zdqjudy.top/Article/details/gtvkgojwop.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gtusvkfyod.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gtviivjxzz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqptsgtq.html

[K07] 进制转换
来源：http://dali.sufxvd.cn/Article/details/gtmgixqfvp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkeiofrwp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sweek.top/Article/details/gtltxzlxwz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtonxyhtec.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtykiaqmww.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtgemywhqg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.svipenyu.cn/Article/details/gtrcodpvaz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xziqi.cn/Article/details/gthxzayjvw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiesncxzc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dashuyun.cn/Article/details/gtmumadadi.html

Py:   pickle.dumps(obj)
来源：http://dali.chenzaomai.com/Article/details/gtegszegtj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.kuanghao11.cn/Article/details/gtbrssurub.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gtcjagxlzj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gtzliycphd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.kuanghao11.cn/Article/details/gtwzlqslsx.html

Go:   encoding/gob
来源：http://dali.pycfn.com/Article/details/gtxqilzkol.html

Ruby: Marshal.dump(obj)
来源：http://dali.cdnleiting.top/Article/details/gtwzjgrrmc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gtlyadbbfx.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtquxzsrnv.html

L. 网络请求
来源：http://dali.fengsongda.top/Article/details/gtdbpwqybm.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtzoqqlzqf.html

[L01] 发送 GET 请求
来源：http://dali.aizwys.cn/Article/details/gtvvkikajn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhiwuduotai.top/Article/details/gtecrdvagh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cashguo.top/Article/details/gtmrxkuenu.html

JS:   await fetch(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtugtdytjm.html

TS:   await fetch(url)
来源：http://dali.sufxvd.cn/Article/details/gthoeblvvj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xuanzx.com/Article/details/gtwdrgyxcd.html

Go:   resp, err := http.Get(url)
来源：http://dali.sxryk.cn/Article/details/gtolijhfxh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhixingplan.top/Article/details/gthhcxqyic.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhiwuduotai.top/Article/details/gttrvxailb.html

[L02] 发送 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gtcqrcnqjv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ehwqpu.com/Article/details/gtkkdhpxyd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hysaishi.cn/Article/details/gtsczcanav.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiulkdoky.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gtpfwyqbgm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenjidiqi.icu/Article/details/gtpnlqczdl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj20258.top/Article/details/gtvgwbqoew.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.0kj1m.cn/Article/details/gtksyuixlh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xuanzx.com/Article/details/gttyelulij.html

[L03] 设置自定义请求头
来源：http://dali.zhengqikj.top/Article/details/gtlpshywnc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hongshengwenyu.top/Article/details/gtetgrmzhv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cashguo.top/Article/details/gtuglsrbki.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gtbywpfkvj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gtnqccvlvr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cheryme.top/Article/details/gtszhivcej.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gtyjqgycrk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tianlin.xyz/Article/details/gtrygyierx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.wangdashe.top/Article/details/gtobjkakjx.html

[L04] 设置超时
来源：http://dali.hammf.cn/Article/details/gtpzypjneh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhoulong.xyz/Article/details/gtqyiqkzjm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhoulong.xyz/Article/details/gtidyctpfb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangdashe.top/Article/details/gtyuanyyme.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnxiangtu.top/Article/details/gtllpgzcxd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gtgqyzxjcl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.9152youxi.cn/Article/details/gtnhojgvum.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258888.top/Article/details/gttuwuvwly.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gzhubu.top/Article/details/gtjaddgxev.html

[L05] 上传文件（multipart）
来源：http://dali.hnxiangtu.top/Article/details/gtbqfzctuy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sysykeji.top/Article/details/gtqoxtxpil.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.birdmap.top/Article/details/gtbvecfbac.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yonumen.top/Article/details/gterupdymf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigufen.top/Article/details/gthtwrccrn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnqzz.top/Article/details/gtnrvksegu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhongyouzk.top/Article/details/gtrcbuqeab.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinqigfzy.top/Article/details/gtyzyzhpij.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtoytoccyx.html

[L06] 解析响应为 JSON
来源：http://dali.zhoulong.xyz/Article/details/gtdtjoerkk.html

Py:   resp.json()
来源：http://dali.hammf.cn/Article/details/gtlapulybn.html

PHP:  json_decode($body, true);
来源：http://dali.fzhhl.top/Article/details/gtxdwnegny.html

JS:   await resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gtsaxuhmsq.html

TS:   await resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gttthwvlyk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gtkzygyglx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.vqdsnc.cn/Article/details/gtndhzjbbd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuanzhike.top/Article/details/gtkvkhegfj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj202588.top/Article/details/gtihlhieud.html

[L07] 处理 HTTP 状态码
来源：http://dali.jqgufenzy.top/Article/details/gtpcpxyypq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.fengsongda.top/Article/details/gtulhhifox.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.guannengcc.top/Article/details/gtsyljprmr.html

JS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gtxtpexber.html

TS:   resp.ok;  resp.status
来源：http://dali.316326.xyz/Article/details/gtksvwotzs.html

Java: resp.statusCode()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtplnajhaz.html

Go:   resp.StatusCode
来源：http://dali.nanxuanxn.top/Article/details/gtiothaucg.html

Ruby: resp.code.to_i
来源：http://dali.jqgufenzy.top/Article/details/gtcdxowovz.html

C#:   (int)resp.StatusCode
来源：http://dali.zycfv.cn/Article/details/gtajpaafjb.html

[L08] 并发请求多个地址
来源：http://dali.gzhubu.top/Article/details/gtnyredwhx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.aizwys.cn/Article/details/gtaagtjgax.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinqigfzy.top/Article/details/gtnktnycdw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gtvfnvhtot.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.mhx1999.top/Article/details/gtftauwigh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangdashe.top/Article/details/gtkjxvaoty.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ehwqpu.com/Article/details/gtxfmeidpr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenzaomai.com/Article/details/gtjoailbzs.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cucudq.cn/Article/details/gtyndtgpuq.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtjsiiarme.html

M. 命令行 / 进程 / 环境
来源：http://dali.fengsongda.top/Article/details/gtjnsewtpa.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtvojwczzm.html

[M01] 读取命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gtkonzxgjz.html

Py:   sys.argv[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gtivemrcry.html

PHP:  $argv;  $argc;
来源：http://dali.yueranfly.top/Article/details/gtrsemrzvp.html

JS:   process.argv.slice(2)
来源：http://dali.quarkkingdee.top/Article/details/gtwmvhiffx.html

TS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtehfdzpdl.html

Java: args 数组（main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcwksathk.html

Go:   os.Args[1:]
来源：http://dali.tian-w.cn/Article/details/gtmkbwlrms.html

Ruby: ARGV
来源：http://dali.hywenlv.cn/Article/details/gtmrxswwnm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gtkqwperbg.html

[M02] 读取环境变量
来源：http://dali.fzhhl.top/Article/details/gtgxccdekr.html

Py:   os.environ.get("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtetxgizxy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gtogxysyha.html

JS:   process.env.HOME
来源：http://dali.feifeiyinyue.top/Article/details/gtfbpqbwia.html

TS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gtunztnlhp.html

Java: System.getenv("HOME")
来源：http://dali.fzhhl.top/Article/details/gtavghcikb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.smart0.xyz/Article/details/gtgzokcpye.html

Ruby: ENV["HOME"]
来源：http://dali.yuxming.cn/Article/details/gtclyhnfug.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gttyeiaimi.html

[M03] 执行外部命令
来源：http://dali.hnqzz.top/Article/details/gtxawvadtj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tanke756.top/Article/details/gtyppstfwj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.dashuyun.cn/Article/details/gtfumdbsei.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dianchejie.cn/Article/details/gtqvhxxcgm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gtifcwgxaq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.0kj1m.cn/Article/details/gthlftfvzs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yvedp.cn/Article/details/gtuliyvyoo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xuetiantiany.cn/Article/details/gtalqhejcv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sysykeji.top/Article/details/gtssjrdklm.html

[M04] 获取当前工作目录
来源：http://dali.hongshengwenyu.top/Article/details/gtmbpwkfdk.html

Py:   os.getcwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgxkzuyts.html

PHP:  getcwd();
来源：http://dali.daxiang520.top/Article/details/gtxtqkdktk.html

JS:   process.cwd()
来源：http://dali.cqqwz.cn/Article/details/gtskvzhlhq.html

TS:   process.cwd()
来源：http://dali.dashuyun.cn/Article/details/gtjcvcaksi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xuetiantiany.cn/Article/details/gtkjfoqlou.html

Go:   os.Getwd()
来源：http://dali.316326.xyz/Article/details/gtfukmzxbh.html

Ruby: Dir.pwd
来源：http://dali.hammf.cn/Article/details/gtqcuistqu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shuidangran.top/Article/details/gtdouawoid.html

[M05] 设置退出码
来源：http://dali.yj20258.top/Article/details/gtkrxawxir.html

Py:   sys.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtwxdtoopp.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gtehhctglx.html

JS:   process.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtgcyimtfj.html

TS:   process.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtcxrfcfln.html

Java: System.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtxgmkkopp.html

Go:   os.Exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqddyndz.html

Ruby: exit 1
来源：http://dali.xuanzx.com/Article/details/gtfzmbzeda.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sufxvd.cn/Article/details/gttmvvcemr.html

[M06] 向标准错误输出
来源：http://dali.cashguo.top/Article/details/gtfiywlead.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuanzx.com/Article/details/gtwjqogskc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjwzyxlcc.html

JS:   console.error("err")
来源：http://dali.yangfankeji.com/Article/details/gtwqfffjob.html

TS:   console.error("err")
来源：http://dali.c1oappe.top/Article/details/gtvqogereb.html

Java: System.err.println("err")
来源：http://dali.jinqigfzy.top/Article/details/gtpcumqitl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pycfn.com/Article/details/gtgznidfkq.html

Ruby: warn "err"
来源：http://dali.snrcjt.cn/Article/details/gtpmifnzua.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.smart0.xyz/Article/details/gtzgwtfvuy.html

[M07] 判断是否为主入口
来源：http://dali.cdnleiting.top/Article/details/gtzueuborg.html


<!-- 参考信息 -->