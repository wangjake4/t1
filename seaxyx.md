代发 wailian999

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tianlin.xyz/Article/details/gteppcqjur.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.guannengcc.top/Article/details/gtqnqfykha.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.0kj1m.cn/Article/details/gtaqotjsmg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.wangdashe.top/Article/details/gtwqgyrnxn.html

[J03] 字符串解析为日期
来源：http://dali.c1oappe.top/Article/details/gtqteyfigv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.birdmap.top/Article/details/gtquinqzse.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ivvv.top/Article/details/gtqjkbehzk.html

JS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtnpxhnbjp.html

TS:   new Date("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtpuhzpskv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtpdpaljpu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtwolyemfb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtsmdonrif.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guowangkeji.top/Article/details/gtbcguhgng.html

[J04] 时间戳与日期互转
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxfjyuzm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtmjvvcylz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.guannengcc.top/Article/details/gtbgrcpvkr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pengpengdd.cyou/Article/details/gtlbtrwztf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ydzc1.top/Article/details/gtosvadkfr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sxryk.cn/Article/details/gtlicdmfcq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhkxuwhz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nanxinkj.top/Article/details/gtktggixjr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gzhubu.top/Article/details/gtntndoipn.html

[J05] 时间加减（加 7 天）
来源：http://dali.sufxvd.cn/Article/details/gtruoocjwq.html

Py:   now + timedelta(days=7)
来源：http://dali.gzhubu.top/Article/details/gtfpxfyqhx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinghuilouyu.cn/Article/details/gtkinqgcyu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gtyvvsanbk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gtrrineugy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.9152youxi.cn/Article/details/gtomvzqybc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtfsulvsth.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenjidiqi.icu/Article/details/gtnpiockpu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xuanzx.com/Article/details/gtkmzxqgpf.html

[J06] 计算两时间之差
来源：http://dali.yvedp.cn/Article/details/gtzkdbtjlf.html

Py:   (end - start).total_seconds()
来源：http://dali.cdnleiting.top/Article/details/gtbbxsmnld.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigufen.top/Article/details/gtplhryeit.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.svipenyu.cn/Article/details/gtlvncvdhc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tianlin.xyz/Article/details/gtxgbarfkl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.bjfxy.top/Article/details/gtkyxsqaxu.html

Go:   end.Sub(start).Hours()
来源：http://dali.yanxiufei.cn/Article/details/gtxufqiwew.html

Ruby: end - start                 # 返回秒数
来源：http://dali.mhx1999.top/Article/details/gttzspqcwp.html

C#:   (end - start).TotalSeconds
来源：http://dali.ehwqpu.com/Article/details/gtcevbdgbw.html

[J07] 比较两个日期
来源：http://dali.xinyue.icu/Article/details/gtzhsaptvo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtutypfyze.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yangfankeji.com/Article/details/gtgnofpnqh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gtvfqreisn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gtpqqvipws.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.aizwys.cn/Article/details/gtsowykowx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtengzsheb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gtpxkvheue.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gtuvnkheef.html

[J08] 提取年月日与星期
来源：http://dali.iojbl.cn/Article/details/gthoqgqlde.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgufenzy.top/Article/details/gtrbejigvz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.havefunace.top/Article/details/gtoqajtydo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.guannengcc.top/Article/details/gtcxxfcpkg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fzhhl.top/Article/details/gtdcekddav.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj202588.top/Article/details/gtkueryvgq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jiagoushi.top/Article/details/gtlumlzufp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sxryk.cn/Article/details/gtmdvrzjgb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gzhubu.top/Article/details/gtfgopwmxh.html

[J09] 时区处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbnoexiy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.pycfn.com/Article/details/gtaqweoyvj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dashuyun.cn/Article/details/gtctgylcod.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gtamjkrjjf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yvedp.cn/Article/details/gtxbynipgy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.smart0.xyz/Article/details/gtdoijwupm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.daxiang520.top/Article/details/gtspmcgffy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhongyouzk.top/Article/details/gtmebpmoqu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pengpengdd.cyou/Article/details/gtcpdwzpzq.html

[J10] 取今天 / 本月第一天
来源：http://dali.feifeiyinyue.top/Article/details/gtukwtzsnv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zycfv.cn/Article/details/gtzoamsptm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxinkj.top/Article/details/gtwqmhzcmt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxuanxn.top/Article/details/gtdmxuybjb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.guannengcc.top/Article/details/gtpsupivzp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nwbrower.top/Article/details/gtdoctkuyf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jiagoushi.top/Article/details/gtymbugdgz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shuidangran.top/Article/details/gtlbjqptnn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtytnobhwz.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtwoxpzhxb.html

K. JSON 与序列化
来源：http://dali.daria6918.cn/Article/details/gtajchgkji.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtdbdemucl.html

[K01] 对象转 JSON 字符串
来源：http://dali.jqgufenzy.top/Article/details/gtsdogjkwx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.svipenyu.cn/Article/details/gtghxvyldv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gtpcsaetve.html

JS:   JSON.stringify(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpafumobj.html

TS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gthgfexver.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinghuilouyu.cn/Article/details/gtinqgleps.html

Go:   json.Marshal(obj)
来源：http://dali.yuanzhike.top/Article/details/gtwatlaqvj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjtteupur.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnqzz.top/Article/details/gtctqbvvph.html

[K02] JSON 字符串转对象
来源：http://dali.kuanghao11.cn/Article/details/gttanjunqw.html

Py:   json.loads(s)
来源：http://dali.meibo888.top/Article/details/gtnyqtgewa.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jiagoushi.top/Article/details/gtuqkaonee.html

JS:   JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gtwqoyuhwr.html

TS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gtpnqwgeaq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gtmgglsgkx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gogol.net.cn/Article/details/gtqrqslxor.html

Ruby: JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gtvbdrybxa.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtsnzfcaul.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sweek.top/Article/details/gtrnlpyeyf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gteeuiapaq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gtvwcopmtq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ydzc1.top/Article/details/gtslylrvzh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtflbwdxfn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xziqi.cn/Article/details/gtzikezmvn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigufen.top/Article/details/gtqvuacvfl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtxuspieum.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shuidangran.top/Article/details/gtrenkqvel.html

[K04] 读取 JSON 文件
来源：http://dali.hysaishi.cn/Article/details/gtxnzdjvxu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sweek.top/Article/details/gtzcoxrxtn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.andypj.xyz/Article/details/gtnswymqxk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jyoumei.cn/Article/details/gtkcgvhvvg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gaohongyu789.top/Article/details/gtaaidwbcq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtmheyjrnh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yonumen.top/Article/details/gtdhtdjitk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cashguo.top/Article/details/gtpathttrt.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gthmdkgefk.html

[K05] 深拷贝对象
来源：http://dali.mhx1999.top/Article/details/gtznzaaldv.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfvgifll.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sufxvd.cn/Article/details/gtmamqzbeh.html

JS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gtoficklxt.html

TS:   structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gteegxmmsq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jianghu66.top/Article/details/gtmyefmqbz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jqgufenzy.top/Article/details/gtcsbhothr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.pengpengdd.cyou/Article/details/gtloibbgzr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xinyue.icu/Article/details/gtonsblzhy.html

[K06] 解析 URL 查询串
来源：http://dali.zhongyouzk.top/Article/details/gthyuhdccn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlpwwmhrl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.fzhhl.top/Article/details/gtgbmceeao.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sysykeji.top/Article/details/gtkcnaciza.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gtnrlxshst.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.quarkkingdee.top/Article/details/gttasueihf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gtfdsmbcqd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gtnokteldf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gtdypypijv.html

[K07] 进制转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkkboarmw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtiqhrntbg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jiagoushi.top/Article/details/gtajuwgbpy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtdrveivwn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtjrjcjxpx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtodrzeaqb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.wangdashe.top/Article/details/gtdynoisds.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.kuanghao11.cn/Article/details/gtzzuixbfj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtexesjejx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xylfe.cn/Article/details/gtnwixnajh.html

Py:   pickle.dumps(obj)
来源：http://dali.birdmap.top/Article/details/gtaknqwigh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yvedp.cn/Article/details/gtglwiomtl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gtqlsizdtw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jqgufenzy.top/Article/details/gtkgugjiiy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.fengsongda.top/Article/details/gtszmcaqeb.html

Go:   encoding/gob
来源：http://dali.chenjidiqi.icu/Article/details/gtlgywqfcu.html

Ruby: Marshal.dump(obj)
来源：http://dali.jianghu66.top/Article/details/gtvnrhmfkx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.wangdashe.top/Article/details/gtmgibtvni.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtdtvyakzr.html

L. 网络请求
来源：http://dali.zhoulong.xyz/Article/details/gtfxwzcgoi.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhxmtmci.html

[L01] 发送 GET 请求
来源：http://dali.jqgfzy.top/Article/details/gtqnpxfqrz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinqigfzy.top/Article/details/gtubqekmtv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinghuilouyu.cn/Article/details/gtabowmjcg.html

JS:   await fetch(url)
来源：http://dali.ivvv.top/Article/details/gtyjutyqmq.html

TS:   await fetch(url)
来源：http://dali.haohaochexian.top/Article/details/gtoyjcrgnr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhaomingkeji.xyz/Article/details/gttircnyyt.html

Go:   resp, err := http.Get(url)
来源：http://dali.fzhhl.top/Article/details/gtyvgmatmo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jqgfzy.top/Article/details/gtkuxczstq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nanxuanxn.top/Article/details/gthpikhpuc.html

[L02] 发送 POST JSON
来源：http://dali.zhixingplan.top/Article/details/gthqebuhde.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenjidiqi.icu/Article/details/gttogjgdix.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.smart0.xyz/Article/details/gteiihyskm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guowangkeji.top/Article/details/gtafzdxunq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gttpebgfcb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj202588.top/Article/details/gtsjznwcvw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ydzc1.top/Article/details/gtiuqsdyov.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.mhx1999.top/Article/details/gtrfdtkfmh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gtspkusgwh.html

[L03] 设置自定义请求头
来源：http://dali.jiagoushi.top/Article/details/gtodahpsuv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.vqdsnc.cn/Article/details/gtvxpvjemd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shuidangran.top/Article/details/gtydyhqaer.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daxiang520.top/Article/details/gtqgeopevj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuxming.cn/Article/details/gtpdqbiann.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj202588.top/Article/details/gtysnqtvfk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tian-w.cn/Article/details/gtfpfmkuui.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.feifeiyinyue.top/Article/details/gtzgdbuzun.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhoulong.xyz/Article/details/gtkdiukbdt.html

[L04] 设置超时
来源：http://dali.cashguo.top/Article/details/gtzenxsbgl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yueranfly.top/Article/details/gtxttfgcyu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hongshengwenyu.top/Article/details/gtupfoslvl.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhoulong.xyz/Article/details/gtcxgyjiue.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtavavhzni.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.havefunace.top/Article/details/gtabuvcxei.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxodlkeh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.andypj.xyz/Article/details/gtuevwpyet.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sxryk.cn/Article/details/gtvhicirrc.html

[L05] 上传文件（multipart）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoylityws.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.svipenyu.cn/Article/details/gtxfhrimnr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cheryme.top/Article/details/gtotorqzey.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gtihmxjrax.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gtfzhqapzn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sufxvd.cn/Article/details/gtkicnquic.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gtyehsgogw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xuetiantiany.cn/Article/details/gtxjsvhmgy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zycfv.cn/Article/details/gtofabennd.html

[L06] 解析响应为 JSON
来源：http://dali.yj202588.top/Article/details/gtmtbnwgge.html

Py:   resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gtwpgnpdqn.html

PHP:  json_decode($body, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtjsdewobc.html

JS:   await resp.json()
来源：http://dali.svipenyu.cn/Article/details/gtvnpplswj.html

TS:   await resp.json()
来源：http://dali.316326.xyz/Article/details/gtvpthnczb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.aizwys.cn/Article/details/gtjahznhro.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hfpthk.cn/Article/details/gthxgggvsh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.havefunace.top/Article/details/gtdurmfxaq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zdqjudy.top/Article/details/gtxsibdjas.html

[L07] 处理 HTTP 状态码
来源：http://dali.yanxiufei.cn/Article/details/gtowpdsotw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.snrcjt.cn/Article/details/gtukjxmkdu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xinyue.icu/Article/details/gteycovhae.html

JS:   resp.ok;  resp.status
来源：http://dali.jqgfzy.top/Article/details/gtnkutkrfm.html

TS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gtlqrfajgs.html

Java: resp.statusCode()
来源：http://dali.zycfv.cn/Article/details/gttnyxessd.html

Go:   resp.StatusCode
来源：http://dali.316326.xyz/Article/details/gtzmjtediu.html

Ruby: resp.code.to_i
来源：http://dali.wangdashe.top/Article/details/gtqkvvmnuc.html

C#:   (int)resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gtwaesbhwe.html

[L08] 并发请求多个地址
来源：http://dali.gaohongyu789.top/Article/details/gtvuukbhns.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.haohaochexian.top/Article/details/gtyveiwgah.html

PHP:  curl_multi_init() 系列
来源：http://dali.smart0.xyz/Article/details/gtzmrouhvn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gtkxjxzerc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gtarscxlqp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guannengcc.top/Article/details/gtgocwafkl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nanxinkj.top/Article/details/gtzupxmese.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nanxuanxn.top/Article/details/gtjrhtscue.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjowdiuz.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gthehzahkv.html

M. 命令行 / 进程 / 环境
来源：http://dali.zdqjudy.top/Article/details/gtdqrlzwap.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtaoygfwss.html

[M01] 读取命令行参数
来源：http://dali.daxiang520.top/Article/details/gttuacvpjj.html

Py:   sys.argv[1:]
来源：http://dali.cdnleiting.top/Article/details/gtrdgzfspx.html

PHP:  $argv;  $argc;
来源：http://dali.sxryk.cn/Article/details/gtpvkmdjed.html

JS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gtzlvmglzp.html

TS:   process.argv.slice(2)
来源：http://dali.xinyue.icu/Article/details/gtklgrexdv.html

Java: args 数组（main 方法参数）
来源：http://dali.sysykeji.top/Article/details/gtupagldyg.html

Go:   os.Args[1:]
来源：http://dali.yueranfly.top/Article/details/gtkpjjqyyv.html

Ruby: ARGV
来源：http://dali.yuanzhike.top/Article/details/gtqspsjqjh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hysaishi.cn/Article/details/gtejhrujnt.html

[M02] 读取环境变量
来源：http://dali.meibo888.top/Article/details/gtbuqguaye.html

Py:   os.environ.get("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtbbkxckzm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gtdvopwrcd.html

JS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gtyizxgeje.html

TS:   process.env.HOME
来源：http://dali.feifeiyinyue.top/Article/details/gtxosrukgb.html

Java: System.getenv("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtgadianex.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.andypj.xyz/Article/details/gtylndyyxe.html

Ruby: ENV["HOME"]
来源：http://dali.cucudq.cn/Article/details/gtlufdxorc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nanxinkj.top/Article/details/gtktqziubi.html

[M03] 执行外部命令
来源：http://dali.ivvv.top/Article/details/gtjuydmzww.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnxiangtu.top/Article/details/gtfenbbqlt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgzumufdi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.redwolf501.top/Article/details/gtixpdknis.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigfzy.top/Article/details/gtnyonlcds.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.birdmap.top/Article/details/gtmrupalac.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jiagoushi.top/Article/details/gtkafjjjdf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.quarkkingdee.top/Article/details/gtypcmvnjd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.svipenyu.cn/Article/details/gtkctmhdcp.html

[M04] 获取当前工作目录
来源：http://dali.gotoacloud.top/Article/details/gtlnwovuia.html

Py:   os.getcwd()
来源：http://dali.redwolf501.top/Article/details/gtxrkwmjxa.html

PHP:  getcwd();
来源：http://dali.cashguo.top/Article/details/gtesvlrlij.html

JS:   process.cwd()
来源：http://dali.316326.xyz/Article/details/gtxpsgxpab.html

TS:   process.cwd()
来源：http://dali.shuidangran.top/Article/details/gttoivaecc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hnxiangtu.top/Article/details/gtnphpalbt.html

Go:   os.Getwd()
来源：http://dali.cqqwz.cn/Article/details/gtyghkbiuf.html

Ruby: Dir.pwd
来源：http://dali.jqgufenzy.top/Article/details/gtihrpfjab.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.havefunace.top/Article/details/gtstkbgnua.html

[M05] 设置退出码
来源：http://dali.chenlongwang.top/Article/details/gtnwnsmwkz.html

Py:   sys.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtjwywydps.html

PHP:  exit(1);
来源：http://dali.xziqi.cn/Article/details/gteiocsdjz.html

JS:   process.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtzznkerjp.html

TS:   process.exit(1)
来源：http://dali.jianghu66.top/Article/details/gteyrwbmvq.html

Java: System.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtzddlfuhs.html

Go:   os.Exit(1)
来源：http://dali.wangdashe.top/Article/details/gtmsukccuy.html

Ruby: exit 1
来源：http://dali.yonumen.top/Article/details/gtkqpbslal.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cashguo.top/Article/details/gtzcbpeagp.html

[M06] 向标准错误输出
来源：http://dali.meibo888.top/Article/details/gtysxzjnns.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258888.top/Article/details/gterthssdu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sufxvd.cn/Article/details/gtoeuhcshr.html

JS:   console.error("err")
来源：http://dali.c1oappe.top/Article/details/gtiurcoxgr.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gtwxbzgpuf.html

Java: System.err.println("err")
来源：http://dali.haohaochexian.top/Article/details/gtezdoxscb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.dianchejie.cn/Article/details/gthepciccm.html

Ruby: warn "err"
来源：http://dali.shzxlz.cn/Article/details/gtfimtlfit.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shzxlz.cn/Article/details/gtbgkkcmtv.html

[M07] 判断是否为主入口
来源：http://dali.haohaochexian.top/Article/details/gtfduivejk.html

Py:   if __name__ == "__main__":
来源：http://dali.wangdashe.top/Article/details/gtnjylzymu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ybcxt.top/Article/details/gtgygznddy.html

JS:   require.main === module
来源：http://dali.dashuyun.cn/Article/details/gtrlkgwdgq.html

TS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gtzvaqyxmg.html

Java: public static void main(String[] args)
来源：http://dali.zycfv.cn/Article/details/gtqdalivgj.html

Go:   func main()
来源：http://dali.wangshuangyany.cn/Article/details/gtrqdrbsxq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nwbrower.top/Article/details/gtjkcqxkte.html

C#:   static void Main(string[] args)
来源：http://dali.yongpay.top/Article/details/gtjavxhrbq.html

[M08] 获取系统与运行时信息
来源：http://dali.shangyingyoupin.top/Article/details/gtsxmynyir.html

Py:   platform.system();  platform.python_version()
来源：http://dali.guowangkeji.top/Article/details/gtsfagtxmf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.daria6918.cn/Article/details/gtvhvoacpr.html

JS:   process.platform;  process.version
来源：http://dali.svipenyu.cn/Article/details/gtztmuhwax.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gtrkafzzns.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpboivcvk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.fzhhl.top/Article/details/gtwusrgsgc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jiagoushi.top/Article/details/gtyqvmvejg.html


<!-- 参考信息 -->