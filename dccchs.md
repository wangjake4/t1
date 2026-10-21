代发 wailian999

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwcgsmbk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gthezwrnal.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.c1oappe.top/Article/details/gtwffymvyq.html

TS:   d.toISOString()
来源：http://dali.xziqi.cn/Article/details/gtafdchkdd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.0kj1m.cn/Article/details/gtkmysghkp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gaohongyu789.top/Article/details/gtoxrdssch.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yangfankeji.com/Article/details/gtxnimyzek.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zycfv.cn/Article/details/gtgptbpiui.html

[J03] 字符串解析为日期
来源：http://dali.yuanzhike.top/Article/details/gthwcpotce.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.meibo888.top/Article/details/gtgsnwfyhl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.quarkkingdee.top/Article/details/gtscpopmnk.html

JS:   new Date("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtmwwnrdzz.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtzlsnjkhu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtypyenfjb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtlhaqcwur.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gtnnhkumdq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hysaishi.cn/Article/details/gtdiuabwtk.html

[J04] 时间戳与日期互转
来源：http://dali.redwolf501.top/Article/details/gthcdjlwgd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gotoacloud.top/Article/details/gtcjpxzqfv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jianghu66.top/Article/details/gtadmapdgm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.0kj1m.cn/Article/details/gtoluttklm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hysaishi.cn/Article/details/gtvnmtafol.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtwkpjfjnk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtpzfdxixb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.0kj1m.cn/Article/details/gtqshrsrbt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yonumen.top/Article/details/gtrtrjrual.html

[J05] 时间加减（加 7 天）
来源：http://dali.hnxiangtu.top/Article/details/gtxfzlbzpf.html

Py:   now + timedelta(days=7)
来源：http://dali.cheryme.top/Article/details/gtjulguajn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cqqwz.cn/Article/details/gtltargsyf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guowangkeji.top/Article/details/gtbwolltah.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gtrkklsvwu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ydzc1.top/Article/details/gtdvstsrol.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuanzhike.top/Article/details/gtddrzjvfl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjkcsgtwa.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guowangkeji.top/Article/details/gtbjhxopfc.html

[J06] 计算两时间之差
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxkrokjuu.html

Py:   (end - start).total_seconds()
来源：http://dali.gaohongyu789.top/Article/details/gtxdlinybp.html

PHP:  $end->diff($start)->days;
来源：http://dali.sysykeji.top/Article/details/gtgfzlbjjk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zycfv.cn/Article/details/gtzjusmyyv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yvedp.cn/Article/details/gtqvcqtkyl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangdashe.top/Article/details/gtasfiyimm.html

Go:   end.Sub(start).Hours()
来源：http://dali.cdnleiting.top/Article/details/gtkmtndmpj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmeaqlvm.html

C#:   (end - start).TotalSeconds
来源：http://dali.ivvv.top/Article/details/gtlvbadbei.html

[J07] 比较两个日期
来源：http://dali.cheryme.top/Article/details/gtzjhptfzn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gtrhwvptqv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.0kj1m.cn/Article/details/gtjpgbawxd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gtvevdffnv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gtwbvwlhhp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sysykeji.top/Article/details/gtykmmhibr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fzhhl.top/Article/details/gtjiddjiqt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gtiqdzzlxa.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtyganvaql.html

[J08] 提取年月日与星期
来源：http://dali.tianlin.xyz/Article/details/gtuvxplghh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.smart0.xyz/Article/details/gtlxgksevf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinqigfzy.top/Article/details/gtjkebkbyd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.feifeiyinyue.top/Article/details/gtgbrxknkr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.guowangkeji.top/Article/details/gtpgeaoupe.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.quarkkingdee.top/Article/details/gtynlqqsgi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yanxiufei.cn/Article/details/gtlmagcduj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tanke756.top/Article/details/gtzkcplgas.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhixingplan.top/Article/details/gtskjjwuts.html

[J09] 时区处理
来源：http://dali.yj20258.top/Article/details/gtvjeovhms.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.iojbl.cn/Article/details/gtookqkddn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.birdmap.top/Article/details/gtxqcxufxg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gtkvzrvnjm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.feifeiyinyue.top/Article/details/gtevmacuqm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj20258.top/Article/details/gtyedegnsw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jqgfzy.top/Article/details/gtajtdbnic.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenjidiqi.icu/Article/details/gtzgglutos.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yuxming.cn/Article/details/gtneptzoch.html

[J10] 取今天 / 本月第一天
来源：http://dali.aibaodan.cn/Article/details/gtzjduhmvy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.aibaodan.cn/Article/details/gtpapmfudg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ydzc1.top/Article/details/gtudwlnhgs.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.kuanghao11.cn/Article/details/gtivobjfot.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258888.top/Article/details/gtjjoznego.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtewonsepi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.wangshuangyany.cn/Article/details/gtilppxksr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hongshengwenyu.top/Article/details/gtkgyxyjkw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhengqikj.top/Article/details/gtvaduwdsi.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtbtyklsuk.html

K. JSON 与序列化
来源：http://dali.jqgufenzy.top/Article/details/gteqlvnnmr.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtbjpngisz.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinqigfzy.top/Article/details/gtxlwsqijx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jyoumei.cn/Article/details/gtviouahut.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gtmhwuopmr.html

JS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gtfagzxwwe.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgfzy.top/Article/details/gtwvvyyzyy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tian-w.cn/Article/details/gtzvewzify.html

Go:   json.Marshal(obj)
来源：http://dali.hammf.cn/Article/details/gtrxszxsrj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cucudq.cn/Article/details/gtlqqpqsbr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtlndqcova.html

[K02] JSON 字符串转对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnyjrums.html

Py:   json.loads(s)
来源：http://dali.xziqi.cn/Article/details/gtwyhrtivb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jqgufenzy.top/Article/details/gtqsgcgogn.html

JS:   JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gtvakvyqtz.html

TS:   JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtitrhhkbj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xziqi.cn/Article/details/gtkcswcztm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigufen.top/Article/details/gteurlhxcg.html

Ruby: JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gtwmqgrfrf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.guowangkeji.top/Article/details/gtscudffqh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shangyingyoupin.top/Article/details/gtogacfqce.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gtpplribec.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gtpmjuaktk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.pycfn.com/Article/details/gtwsijzxef.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gtlglbzqut.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtmdamzkew.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yueranfly.top/Article/details/gtglvujaps.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sweek.top/Article/details/gtldehbvtb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuanzhike.top/Article/details/gteyykcysm.html

[K04] 读取 JSON 文件
来源：http://dali.hnxiangtu.top/Article/details/gtdqwnpsjz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jqgfzy.top/Article/details/gtxwkxvlze.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.svipenyu.cn/Article/details/gtilvfyccn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.meibo888.top/Article/details/gtynhixjqe.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jiagoushi.top/Article/details/gtmaisswci.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cdnleiting.top/Article/details/gttiwmgzrl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj202588.top/Article/details/gtlbuzluyr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gtlhmuxgbx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tianlin.xyz/Article/details/gtdqlcmmjs.html

[K05] 深拷贝对象
来源：http://dali.zhengqikj.top/Article/details/gtwpkngaab.html

Py:   copy.deepcopy(obj)
来源：http://dali.ivvv.top/Article/details/gtliaowlyw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.aibaodan.cn/Article/details/gtlxaypvru.html

JS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gtlihsvjnf.html

TS:   structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gtyytcoypx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xinyue.icu/Article/details/gtkzlrkesd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cucudq.cn/Article/details/gtwnsuplrz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shanyushiyangtech.top/Article/details/gtdnsneuks.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.bjfxy.top/Article/details/gtoivupzjk.html

[K06] 解析 URL 查询串
来源：http://dali.quarkkingdee.top/Article/details/gtincnsgjz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zycfv.cn/Article/details/gtcobzqnwa.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cashguo.top/Article/details/gthojjwfrn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtsptddwgd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gtpgzykaoz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yuxming.cn/Article/details/gtfmqwvani.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gtzokvpjpk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gtzfgvibsi.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gtzevxtxhw.html

[K07] 进制转换
来源：http://dali.nwbrower.top/Article/details/gthwtkejkq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gtxywgvhbu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenlongwang.top/Article/details/gtrpnuitth.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtrflhumiq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtotdrzptm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtmreqzfzm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.pycfn.com/Article/details/gtuodhpkbr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xylfe.cn/Article/details/gtjchgbdjw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtgaykgqvd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cdnleiting.top/Article/details/gtfdslmssy.html

Py:   pickle.dumps(obj)
来源：http://dali.dianchejie.cn/Article/details/gtkncskpvd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.haohaochexian.top/Article/details/gttgedjwmb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hfpthk.cn/Article/details/gtbhqwseww.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gzhubu.top/Article/details/gtbapvryhc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgfzy.top/Article/details/gtlzcayuka.html

Go:   encoding/gob
来源：http://dali.yuanzhike.top/Article/details/gttafdsxdv.html

Ruby: Marshal.dump(obj)
来源：http://dali.ehwqpu.com/Article/details/gtrrafgxwm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj20258888.top/Article/details/gtwymhpcxv.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtmstnryey.html

L. 网络请求
来源：http://dali.ppjwa.cn/Article/details/gtgylvqeev.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtdzlefswi.html

[L01] 发送 GET 请求
来源：http://dali.zdqjudy.top/Article/details/gtusvdehds.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dianchejie.cn/Article/details/gtpjmtqexn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cheryme.top/Article/details/gtcnhfegeg.html

JS:   await fetch(url)
来源：http://dali.hnqzz.top/Article/details/gtjftuqjgt.html

TS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gtgdcuxvqr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sufxvd.cn/Article/details/gtqfzvmrht.html

Go:   resp, err := http.Get(url)
来源：http://dali.nwbrower.top/Article/details/gtcaqodhee.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.fengsongda.top/Article/details/gtrjjgflrc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gotoacloud.top/Article/details/gtslhzolxr.html

[L02] 发送 POST JSON
来源：http://dali.yonumen.top/Article/details/gtuhpbnlhr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xziqi.cn/Article/details/gtwryfqphi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.guannengcc.top/Article/details/gtbstoltxj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigfzy.top/Article/details/gtzbcigozx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gogol.net.cn/Article/details/gtssvxbofu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tanke756.top/Article/details/gtkffqqdrd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhoulong.xyz/Article/details/gtztepsfus.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tian-w.cn/Article/details/gtbinylsvc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.quarkkingdee.top/Article/details/gtufwjnpob.html

[L03] 设置自定义请求头
来源：http://dali.ybcxt.top/Article/details/gtumujjtrj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.daria6918.cn/Article/details/gtiiidpumv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sufxvd.cn/Article/details/gtmbbugheb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tianlin.xyz/Article/details/gtyigiwplr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhbfrqid.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.snrcjt.cn/Article/details/gtovplgkax.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.kuanghao11.cn/Article/details/gtaeucangq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yonumen.top/Article/details/gtgmjshmyq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tian-w.cn/Article/details/gtsobmlrmo.html

[L04] 设置超时
来源：http://dali.haohaochexian.top/Article/details/gtwapugqzj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tanke756.top/Article/details/gtwcbkplfn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ydzc1.top/Article/details/gtmnujpwcm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhzsixfb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.quarkkingdee.top/Article/details/gtffpmmero.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.meibo888.top/Article/details/gtyisanntx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ehwqpu.com/Article/details/gtjusxxsqx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.feifeiyinyue.top/Article/details/gtwxxzcaad.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xuanzx.com/Article/details/gtrkrhwgpl.html

[L05] 上传文件（multipart）
来源：http://dali.wangshuangyany.cn/Article/details/gtkmbhiyhp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.fzhhl.top/Article/details/gtksdqdtoo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xuetiantiany.cn/Article/details/gtioxmyeve.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gtbxkkfcnj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.mhx1999.top/Article/details/gtlhuajttn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dashuyun.cn/Article/details/gtojilqcwl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.snrcjt.cn/Article/details/gtdafdsico.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hysaishi.cn/Article/details/gtbbpfdshc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtlgiywxtr.html

[L06] 解析响应为 JSON
来源：http://dali.nanxinkj.top/Article/details/gtxsixslde.html

Py:   resp.json()
来源：http://dali.cheryme.top/Article/details/gtoqbjvzsq.html

PHP:  json_decode($body, true);
来源：http://dali.jlsjyb.cn/Article/details/gthjjqndjd.html

JS:   await resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gtyyatnrxv.html

TS:   await resp.json()
来源：http://dali.cucudq.cn/Article/details/gtouhzvmxt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxcvduue.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.andypj.xyz/Article/details/gttvdwbwaf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hywenlv.cn/Article/details/gtaqxerrir.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.iojbl.cn/Article/details/gtmxbqfyza.html

[L07] 处理 HTTP 状态码
来源：http://dali.kuanghao11.cn/Article/details/gtxymblmtp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hammf.cn/Article/details/gtiynnfdht.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.redwolf501.top/Article/details/gtjhjlspdp.html

JS:   resp.ok;  resp.status
来源：http://dali.jinqigufen.top/Article/details/gtfyefdqxi.html

TS:   resp.ok;  resp.status
来源：http://dali.ybcxt.top/Article/details/gtkcjxdrzq.html

Java: resp.statusCode()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphvpbdim.html

Go:   resp.StatusCode
来源：http://dali.snrcjt.cn/Article/details/gtkfurytsk.html

Ruby: resp.code.to_i
来源：http://dali.xziqi.cn/Article/details/gtxtgpgtvz.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgfzy.top/Article/details/gtcjdbnbim.html

[L08] 并发请求多个地址
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvkmfzhkb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.snrcjt.cn/Article/details/gtiuewzqlt.html

PHP:  curl_multi_init() 系列
来源：http://dali.gotoacloud.top/Article/details/gtqiuzrgrb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gteyvcwbww.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pycfn.com/Article/details/gtrrndmbpi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xylfe.cn/Article/details/gtnteixgpv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hongshengwenyu.top/Article/details/gtwzomfrwt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenjidiqi.icu/Article/details/gtqbvpvpkd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xinyue.icu/Article/details/gtwphznzmy.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtrcqekero.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj20258.top/Article/details/gtpzqkxvfg.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtgtvkmmzh.html

[M01] 读取命令行参数
来源：http://dali.cucudq.cn/Article/details/gtxguegghx.html

Py:   sys.argv[1:]
来源：http://dali.bjfxy.top/Article/details/gtooakbwjc.html

PHP:  $argv;  $argc;
来源：http://dali.iojbl.cn/Article/details/gtjuipdukq.html

JS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gtepfkuiuc.html

TS:   process.argv.slice(2)
来源：http://dali.jlsjyb.cn/Article/details/gtoympwkve.html

Java: args 数组（main 方法参数）
来源：http://dali.snrcjt.cn/Article/details/gtgplgtweg.html

Go:   os.Args[1:]
来源：http://dali.c1oappe.top/Article/details/gtqdodqgbd.html

Ruby: ARGV
来源：http://dali.xuanzx.com/Article/details/gtarykstto.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cdnleiting.top/Article/details/gtszfmqlvp.html

[M02] 读取环境变量
来源：http://dali.9152youxi.cn/Article/details/gtvtvnzqdj.html

Py:   os.environ.get("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkyvoeqsq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gtsxaxhxee.html

JS:   process.env.HOME
来源：http://dali.hfpthk.cn/Article/details/gtifhywolo.html

TS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvstzoyky.html

Java: System.getenv("HOME")
来源：http://dali.wangdashe.top/Article/details/gtllrklcvd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnskgpxnu.html

Ruby: ENV["HOME"]
来源：http://dali.hysaishi.cn/Article/details/gtybiruxkq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sweek.top/Article/details/gtlbxsvonv.html

[M03] 执行外部命令
来源：http://dali.ybcxt.top/Article/details/gtotyecqct.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhoulong.xyz/Article/details/gttsetsjol.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gtxkhhjiib.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hfpthk.cn/Article/details/gtlhsclptp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cucudq.cn/Article/details/gtadbizxra.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ehwqpu.com/Article/details/gtsnwwbfay.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.daxiang520.top/Article/details/gtliqhpdzb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xinyue.icu/Article/details/gtafnhwomq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aibaodan.cn/Article/details/gtymafendb.html

[M04] 获取当前工作目录
来源：http://dali.gaohongyu789.top/Article/details/gtafiuxsxb.html

Py:   os.getcwd()
来源：http://dali.hnxiangtu.top/Article/details/gtglokhpav.html

PHP:  getcwd();
来源：http://dali.cdnleiting.top/Article/details/gtpobwlahc.html

JS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gthdwrlpyv.html

TS:   process.cwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtushkxlev.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.andypj.xyz/Article/details/gttaugcnzs.html

Go:   os.Getwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwkjxkno.html

Ruby: Dir.pwd
来源：http://dali.feifeiyinyue.top/Article/details/gtftqpanaj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yanxiufei.cn/Article/details/gtbrzkbcqp.html

[M05] 设置退出码
来源：http://dali.andypj.xyz/Article/details/gtzmzxqjgb.html

Py:   sys.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtfbvbfcuo.html

PHP:  exit(1);
来源：http://dali.xziqi.cn/Article/details/gtnptnlfvl.html

JS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtxhdqddlb.html

TS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtyirwlrxz.html

Java: System.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtkqmxosgg.html

Go:   os.Exit(1)
来源：http://dali.jianghu66.top/Article/details/gtgijotvwc.html

Ruby: exit 1
来源：http://dali.jinqigfzy.top/Article/details/gtkgxjlocf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daxiang520.top/Article/details/gtkyauadup.html

[M06] 向标准错误输出
来源：http://dali.jyoumei.cn/Article/details/gtjiqehjrl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tianlin.xyz/Article/details/gtziihoaht.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jyoumei.cn/Article/details/gtgnetijmv.html

JS:   console.error("err")
来源：http://dali.gzhubu.top/Article/details/gthnjqgikx.html

TS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gtcotlvbdn.html

Java: System.err.println("err")
来源：http://dali.zhixingplan.top/Article/details/gtawfidwpn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gthlsskjuo.html

Ruby: warn "err"
来源：http://dali.xylfe.cn/Article/details/gtplpyotmm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.wangshuangyany.cn/Article/details/gtxkekxsrb.html

[M07] 判断是否为主入口
来源：http://dali.daria6918.cn/Article/details/gtkmhvgntf.html

Py:   if __name__ == "__main__":
来源：http://dali.tianlin.xyz/Article/details/gtiuefwjfs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.andypj.xyz/Article/details/gtylzlbnie.html

JS:   require.main === module
来源：http://dali.yvedp.cn/Article/details/gtknucxfig.html

TS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gtllqzaamd.html

Java: public static void main(String[] args)
来源：http://dali.bjfxy.top/Article/details/gtucdpycut.html

Go:   func main()
来源：http://dali.bjfxy.top/Article/details/gtlmjhxjor.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guannengcc.top/Article/details/gtifasfofs.html

C#:   static void Main(string[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtognmlbwd.html

[M08] 获取系统与运行时信息
来源：http://dali.ppjwa.cn/Article/details/gtfqbeoeaf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenjidiqi.icu/Article/details/gtcmbccfrk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.smart0.xyz/Article/details/gtavilvebu.html

JS:   process.platform;  process.version
来源：http://dali.sufxvd.cn/Article/details/gtvdjbzwhv.html


<!-- 参考信息 -->