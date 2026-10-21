代发 wailian999

[J03] 字符串解析为日期
来源：http://dali.tian-w.cn/Article/details/gtyepzbptz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhongyouzk.top/Article/details/gtgchqwnyc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nwbrower.top/Article/details/gtyivbbpjx.html

JS:   new Date("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtusitezkk.html

TS:   new Date("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtmoghllsk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtimrlpuuz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtlkghpkcx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtahibtzif.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sxryk.cn/Article/details/gtmkssihyy.html

[J04] 时间戳与日期互转
来源：http://dali.gotoacloud.top/Article/details/gtbxyyqkle.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yongpay.top/Article/details/gtejjulqlb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.c1oappe.top/Article/details/gtfnqsnygf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nwbrower.top/Article/details/gtefsoiivi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zdqjudy.top/Article/details/gtvcqqipsg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gogol.net.cn/Article/details/gtlmkfwpsc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtluiwnbfk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtpdqbtfju.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuanzx.com/Article/details/gtczqidaai.html

[J05] 时间加减（加 7 天）
来源：http://dali.aibaodan.cn/Article/details/gtsigjokho.html

Py:   now + timedelta(days=7)
来源：http://dali.xuanzx.com/Article/details/gtbgullhys.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.bjfxy.top/Article/details/gtnbfslmxt.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jyoumei.cn/Article/details/gttbmlwogu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxinkj.top/Article/details/gtjeylmgqs.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.iojbl.cn/Article/details/gtldnuqkcc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxinkj.top/Article/details/gtsowjhobm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.wangdashe.top/Article/details/gtwwxaztzs.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gogol.net.cn/Article/details/gtzvclggaj.html

[J06] 计算两时间之差
来源：http://dali.hnxiangtu.top/Article/details/gtvafeegot.html

Py:   (end - start).total_seconds()
来源：http://dali.zhongyouzk.top/Article/details/gtrswlurhg.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj202588.top/Article/details/gtakupgqrf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gogol.net.cn/Article/details/gtvlajwccn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.aibaodan.cn/Article/details/gtnyujysxu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tianlin.xyz/Article/details/gtsaifysgh.html

Go:   end.Sub(start).Hours()
来源：http://dali.hammf.cn/Article/details/gtfjvalbui.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gaohongyu789.top/Article/details/gthwipuyuw.html

C#:   (end - start).TotalSeconds
来源：http://dali.ybcxt.top/Article/details/gtuymcobsl.html

[J07] 比较两个日期
来源：http://dali.xuetiantiany.cn/Article/details/gtistunfka.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gtuajnhdui.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hammf.cn/Article/details/gtciisrfvp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gtaqcutcun.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.haohaochexian.top/Article/details/gthnhftojc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gtcjojgiyp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cashguo.top/Article/details/gtmmqgklrf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gtfmyhcltm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gtntucvble.html

[J08] 提取年月日与星期
来源：http://dali.pycfn.com/Article/details/gtxdayigbx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nanxinkj.top/Article/details/gtdkcykqyo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.guowangkeji.top/Article/details/gtwxwktyvm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenjidiqi.icu/Article/details/gtvvufeayz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhijiandao.cn/Article/details/gtldjfduom.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.aibaodan.cn/Article/details/gtnouzhmdv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shuidangran.top/Article/details/gtlhnxpleo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenjidiqi.icu/Article/details/gtkqhxvnum.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hysaishi.cn/Article/details/gtikjppzac.html

[J09] 时区处理
来源：http://dali.birdmap.top/Article/details/gtukrcrzek.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.daxiang520.top/Article/details/gtkzxqrtys.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.fengsongda.top/Article/details/gtexuiqtjb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daxiang520.top/Article/details/gtsyxwtrjb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gtcjnaculz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gotoacloud.top/Article/details/gtdgcqztsp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.meibo888.top/Article/details/gthfiftwti.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hfpthk.cn/Article/details/gtmscuelfv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.c1oappe.top/Article/details/gtcwbfnity.html

[J10] 取今天 / 本月第一天
来源：http://dali.pycfn.com/Article/details/gtxmglyxpc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhongyouzk.top/Article/details/gtqhkxkwft.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.dianchejie.cn/Article/details/gtkzoyidfg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tian-w.cn/Article/details/gtgdiyurlu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.iojbl.cn/Article/details/gtcxgofvry.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sufxvd.cn/Article/details/gtlkavneuu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj20258.top/Article/details/gthrtqayqf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gaohongyu789.top/Article/details/gtlttxceyr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sxryk.cn/Article/details/gteansnvyc.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtlmzpvwrc.html

K. JSON 与序列化
来源：http://dali.smart0.xyz/Article/details/gtzdpmekoo.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtiljsxewk.html

[K01] 对象转 JSON 字符串
来源：http://dali.xylfe.cn/Article/details/gtjpiekpmq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gtsvjslmre.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tian-w.cn/Article/details/gtnmkzzlyu.html

JS:   JSON.stringify(obj)
来源：http://dali.daria6918.cn/Article/details/gtypjtpbul.html

TS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gtphrilppg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.iojbl.cn/Article/details/gtnvtosfdz.html

Go:   json.Marshal(obj)
来源：http://dali.chenlongwang.top/Article/details/gtiwrcukys.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ivvv.top/Article/details/gtdgnmtgxg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sysykeji.top/Article/details/gtpkyxgpfy.html

[K02] JSON 字符串转对象
来源：http://dali.feifeiyinyue.top/Article/details/gtkggkdvoa.html

Py:   json.loads(s)
来源：http://dali.hysaishi.cn/Article/details/gtxagxmowr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sufxvd.cn/Article/details/gtmqxgnxzu.html

JS:   JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gtykkuktgq.html

TS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtcrczgbhs.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gtijcermtb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.pengpengdd.cyou/Article/details/gtojpxejgn.html

Ruby: JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gtzflqaytq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gogol.net.cn/Article/details/gtsamtcgvb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dianchejie.cn/Article/details/gtbreigojm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.daxiang520.top/Article/details/gtqnauntqn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gttmagfokm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.fzhhl.top/Article/details/gteebkgsqk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.birdmap.top/Article/details/gtlvdyzsyu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtfljseilv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.vqdsnc.cn/Article/details/gtvmrdkjmz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ivvv.top/Article/details/gtvlxebhuc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shzxlz.cn/Article/details/gtryonkxxn.html

[K04] 读取 JSON 文件
来源：http://dali.9152youxi.cn/Article/details/gtaegukhiz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuetiantiany.cn/Article/details/gtyaynfvxb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.andypj.xyz/Article/details/gtwwennska.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jyoumei.cn/Article/details/gtwxcjtztq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gtvcxnresr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gthtjqlptc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbgswmlio.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yueranfly.top/Article/details/gtxretjcrt.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.feifeiyinyue.top/Article/details/gtbkxjacxb.html

[K05] 深拷贝对象
来源：http://dali.gzhubu.top/Article/details/gtsdvsakrb.html

Py:   copy.deepcopy(obj)
来源：http://dali.andypj.xyz/Article/details/gtjmmsoywi.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hywenlv.cn/Article/details/gtspbacabv.html

JS:   structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtjjhbmmhm.html

TS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gtkugnxdkj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nanxinkj.top/Article/details/gtzmcyjiio.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.andypj.xyz/Article/details/gtdwunuicp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhengqikj.top/Article/details/gtydpalbqw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhongyouzk.top/Article/details/gtpyugccmf.html

[K06] 解析 URL 查询串
来源：http://dali.hammf.cn/Article/details/gtqecmygsp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gaohongyu789.top/Article/details/gtwcvoklli.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nwbrower.top/Article/details/gtwykkzumv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cheryme.top/Article/details/gtgaqdvckz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigfzy.top/Article/details/gtrbwtbkwu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yangfankeji.com/Article/details/gtvgfdddti.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gttibahnib.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gtyahzhlhw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gtactqkoum.html

[K07] 进制转换
来源：http://dali.316326.xyz/Article/details/gtgsmfsxxc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtdrcnmmsz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.pengpengdd.cyou/Article/details/gtlltozraa.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtdqxszwmb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gteytieksf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtbnzavwmb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cashguo.top/Article/details/gtddmcbicw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdkmvoluj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtzsjrvyim.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yanxiufei.cn/Article/details/gtstbnsiks.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtehfyderl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbzogwjfk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gtmwfffqru.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gtijpjbetp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tian-w.cn/Article/details/gtsvarnzfy.html

Go:   encoding/gob
来源：http://dali.xuanzx.com/Article/details/gtsniknswe.html

Ruby: Marshal.dump(obj)
来源：http://dali.sufxvd.cn/Article/details/gtxasyroit.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.andypj.xyz/Article/details/gtdttlillp.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtdsbdhjjy.html

L. 网络请求
来源：http://dali.mhx1999.top/Article/details/gtbxuiiipv.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtmktxffpr.html

[L01] 发送 GET 请求
来源：http://dali.hnxiangtu.top/Article/details/gtvsluiioj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shangyingyoupin.top/Article/details/gthsrobmak.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hammf.cn/Article/details/gtktinstne.html

JS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtrmxepewl.html

TS:   await fetch(url)
来源：http://dali.cheryme.top/Article/details/gtzcpukrql.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ivvv.top/Article/details/gtsqnksdkd.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdseddtoi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.feifeiyinyue.top/Article/details/gttlggsgid.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenlongwang.top/Article/details/gtyqbmtdzy.html

[L02] 发送 POST JSON
来源：http://dali.ybcxt.top/Article/details/gtpcbqxwql.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.andypj.xyz/Article/details/gtlercrdoh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.meibo888.top/Article/details/gtwnqmhslv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daria6918.cn/Article/details/gtampfptbh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jyoumei.cn/Article/details/gtlacdzasb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangshuangyany.cn/Article/details/gtaiqdkpda.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.havefunace.top/Article/details/gtvylqttcq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zycfv.cn/Article/details/gtyxrahcyr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.kuanghao11.cn/Article/details/gtihbxgmdg.html

[L03] 设置自定义请求头
来源：http://dali.hysaishi.cn/Article/details/gtusypdesq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.meibo888.top/Article/details/gteoffebcj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shzxlz.cn/Article/details/gtwjiogtrp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnqzz.top/Article/details/gtnnurjlib.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jianghu66.top/Article/details/gtggtcjwmt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sweek.top/Article/details/gtrknmohfy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhoulong.xyz/Article/details/gtaqtjfwqs.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sweek.top/Article/details/gtfbofxtla.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jqgfzy.top/Article/details/gtuvpkxgtz.html

[L04] 设置超时
来源：http://dali.zhoulong.xyz/Article/details/gtaflbnigb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.svipenyu.cn/Article/details/gtrcrkykmv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.0kj1m.cn/Article/details/gthyuztztj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gtknfcixyx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cashguo.top/Article/details/gtedftwqwj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daxiang520.top/Article/details/gtsrhbpvwh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.smart0.xyz/Article/details/gtgljudihp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jyoumei.cn/Article/details/gtztgbnqko.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yonumen.top/Article/details/gtobqnaoet.html

[L05] 上传文件（multipart）
来源：http://dali.shangyingyoupin.top/Article/details/gtlkwxcanc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.andypj.xyz/Article/details/gtyknubobl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jiagoushi.top/Article/details/gtmsbuxjsc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pycfn.com/Article/details/gtdqkdxmne.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.havefunace.top/Article/details/gtavxcsvlf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.c1oappe.top/Article/details/gtymookwal.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.bjfxy.top/Article/details/gtbggwcbjq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinghuilouyu.cn/Article/details/gtvuezfuzn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ydzc1.top/Article/details/gttousunov.html

[L06] 解析响应为 JSON
来源：http://dali.xziqi.cn/Article/details/gtqxqrmmqm.html

Py:   resp.json()
来源：http://dali.cashguo.top/Article/details/gtatzbdzlx.html

PHP:  json_decode($body, true);
来源：http://dali.c1oappe.top/Article/details/gtvqlmssmt.html

JS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gthchjuufq.html

TS:   await resp.json()
来源：http://dali.316326.xyz/Article/details/gtifabwryx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yvedp.cn/Article/details/gtdrlnlxbq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yongpay.top/Article/details/gtqozsqnow.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gogol.net.cn/Article/details/gtrbnclxuz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.0kj1m.cn/Article/details/gthtlnkvar.html

[L07] 处理 HTTP 状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvzywbxy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.0kj1m.cn/Article/details/gtbcwfwdoz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.quarkkingdee.top/Article/details/gtwchmzbjg.html

JS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gtfikkziqz.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gtlozmudjq.html

Java: resp.statusCode()
来源：http://dali.fengsongda.top/Article/details/gtjuejmsmd.html

Go:   resp.StatusCode
来源：http://dali.mhx1999.top/Article/details/gtzrqixnho.html

Ruby: resp.code.to_i
来源：http://dali.yj20258888.top/Article/details/gtnrukmgqc.html

C#:   (int)resp.StatusCode
来源：http://dali.bjfxy.top/Article/details/gtungolfaz.html

[L08] 并发请求多个地址
来源：http://dali.hnxiangtu.top/Article/details/gtqvqogmip.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guannengcc.top/Article/details/gtodhxnivc.html

PHP:  curl_multi_init() 系列
来源：http://dali.yangfankeji.com/Article/details/gtfksiajel.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gtrpmcbqjb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gtdluiyrky.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ybcxt.top/Article/details/gtntobaeqb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.snrcjt.cn/Article/details/gtbltzekdf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fzhhl.top/Article/details/gtfykzggnf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.316326.xyz/Article/details/gtahmxripf.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtiqtqvudr.html

M. 命令行 / 进程 / 环境
来源：http://dali.gzhubu.top/Article/details/gtnhqadntr.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtupdsjycd.html

[M01] 读取命令行参数
来源：http://dali.zhongyouzk.top/Article/details/gthxxbxjda.html

Py:   sys.argv[1:]
来源：http://dali.hammf.cn/Article/details/gtbhvlonoh.html

PHP:  $argv;  $argc;
来源：http://dali.hnqzz.top/Article/details/gtgqudtuat.html

JS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gtvwoymygr.html

TS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gtoybtwdyr.html

Java: args 数组（main 方法参数）
来源：http://dali.jlsjyb.cn/Article/details/gtfgputskm.html

Go:   os.Args[1:]
来源：http://dali.ppjwa.cn/Article/details/gtoigoltfd.html

Ruby: ARGV
来源：http://dali.meibo888.top/Article/details/gtaempijhg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gtspkemupz.html

[M02] 读取环境变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaifbsern.html

Py:   os.environ.get("HOME")
来源：http://dali.cashguo.top/Article/details/gtfehqfqmy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gteilhvueq.html

JS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gtxcuwhngc.html

TS:   process.env.HOME
来源：http://dali.nwbrower.top/Article/details/gtcmvxmgio.html

Java: System.getenv("HOME")
来源：http://dali.ybcxt.top/Article/details/gtdqszpmbj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtlqgrpuss.html

Ruby: ENV["HOME"]
来源：http://dali.iojbl.cn/Article/details/gtowrhmxxq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.birdmap.top/Article/details/gtcuycofir.html

[M03] 执行外部命令
来源：http://dali.316326.xyz/Article/details/gtkuzmjdpz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj20258.top/Article/details/gtdwiayyau.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hywenlv.cn/Article/details/gtvwgmmnrf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenjidiqi.icu/Article/details/gtycgygiwc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ybcxt.top/Article/details/gtjntmkwpt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ybcxt.top/Article/details/gtyhngarlv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.birdmap.top/Article/details/gtlajuygel.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zdqjudy.top/Article/details/gtryzcyitm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xuetiantiany.cn/Article/details/gttusrvafx.html

[M04] 获取当前工作目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtsscwytwf.html

Py:   os.getcwd()
来源：http://dali.xuetiantiany.cn/Article/details/gtyfcofyzo.html

PHP:  getcwd();
来源：http://dali.xuetiantiany.cn/Article/details/gtcyhuqqbi.html

JS:   process.cwd()
来源：http://dali.haohaochexian.top/Article/details/gtzmoorkds.html

TS:   process.cwd()
来源：http://dali.zhoulong.xyz/Article/details/gtblmnqbkx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.haohaochexian.top/Article/details/gtlzahwkjy.html

Go:   os.Getwd()
来源：http://dali.aizwys.cn/Article/details/gtliwkqtkl.html

Ruby: Dir.pwd
来源：http://dali.pycfn.com/Article/details/gtjknshhva.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.kuanghao11.cn/Article/details/gtzmjfgssm.html

[M05] 设置退出码
来源：http://dali.cdnleiting.top/Article/details/gtvvoecowz.html

Py:   sys.exit(1)
来源：http://dali.sweek.top/Article/details/gtvrfjgshf.html

PHP:  exit(1);
来源：http://dali.daxiang520.top/Article/details/gtsjivlxfb.html

JS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtydwaetdu.html

TS:   process.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtuncyrmvf.html

Java: System.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtwmbmhwnz.html

Go:   os.Exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gttiwllhhv.html

Ruby: exit 1
来源：http://dali.fzhhl.top/Article/details/gtkrkcampf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258888.top/Article/details/gtxlwqgzsr.html

[M06] 向标准错误输出
来源：http://dali.smart0.xyz/Article/details/gttqwdckbv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigufen.top/Article/details/gtgicobvat.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangdashe.top/Article/details/gtsmvvexaf.html

JS:   console.error("err")
来源：http://dali.havefunace.top/Article/details/gtjlmabifq.html

TS:   console.error("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlizuowmk.html

Java: System.err.println("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtchxcvknl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hywenlv.cn/Article/details/gtlqgssslr.html

Ruby: warn "err"
来源：http://dali.yanxiufei.cn/Article/details/gtzuwpyfkv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.smart0.xyz/Article/details/gtgruxmime.html

[M07] 判断是否为主入口
来源：http://dali.vqdsnc.cn/Article/details/gtqqiroljw.html

Py:   if __name__ == "__main__":
来源：http://dali.hnxiangtu.top/Article/details/gtpneqcdbp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.smart0.xyz/Article/details/gtgdqgtskd.html

JS:   require.main === module
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxbuspspb.html

TS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gtrscifjso.html

Java: public static void main(String[] args)
来源：http://dali.tian-w.cn/Article/details/gtfhrdlcez.html

Go:   func main()
来源：http://dali.daxiang520.top/Article/details/gtokshalgb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgdiocbzj.html

C#:   static void Main(string[] args)
来源：http://dali.zhongyouzk.top/Article/details/gtlozyfpso.html

[M08] 获取系统与运行时信息
来源：http://dali.yongpay.top/Article/details/gtzynbfgnm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.bjfxy.top/Article/details/gttfdtgcwx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.wangdashe.top/Article/details/gtgnnxeqaz.html

JS:   process.platform;  process.version
来源：http://dali.jinqigufen.top/Article/details/gtlclvedii.html

TS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gtdifplqpg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj20258888.top/Article/details/gtuvilveyb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yueranfly.top/Article/details/gtmvfjnyah.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuddzqrol.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cdnleiting.top/Article/details/gtcifcoana.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gteyoaipqm.html

N. 数据结构与算法
来源：http://dali.yvedp.cn/Article/details/gtogwzheox.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtjazaosne.html


<!-- 参考信息 -->