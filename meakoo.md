代发 wailian999

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cucudq.cn/Article/details/gtldqugquz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hywenlv.cn/Article/details/gtcgkgyqly.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xylfe.cn/Article/details/gtcnseqvws.html

TS:   d.toISOString()
来源：http://dali.hammf.cn/Article/details/gtnbjxebgj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.mhx1999.top/Article/details/gtuinfzlsc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.haohaochexian.top/Article/details/gtpdktbbjw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fengsongda.top/Article/details/gtqswkltae.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shanyushiyangtech.top/Article/details/gtitmxjubm.html

[J03] 字符串解析为日期
来源：http://dali.bjfxy.top/Article/details/gtaossyzcx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.0kj1m.cn/Article/details/gtvuosayee.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yueranfly.top/Article/details/gtetlzwzmh.html

JS:   new Date("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gttxonveev.html

TS:   new Date("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtyxvvxbos.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtmjbfzzwi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtkbgzadaa.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtugewigtc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shangyingyoupin.top/Article/details/gtkcoskhqo.html

[J04] 时间戳与日期互转
来源：http://dali.ivvv.top/Article/details/gtkcoezjzy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.quarkkingdee.top/Article/details/gtxcyxgypi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cucudq.cn/Article/details/gtqnyzcons.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj20258.top/Article/details/gtrrlevrmi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.quarkkingdee.top/Article/details/gtglicakfr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtxynaafln.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenlongwang.top/Article/details/gtovghkgdz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtakotrfof.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tian-w.cn/Article/details/gtlkiikmni.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenzaomai.com/Article/details/gtkdkhocpn.html

Py:   now + timedelta(days=7)
来源：http://dali.yvedp.cn/Article/details/gttiinzwhy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.kuanghao11.cn/Article/details/gtdpijkdbn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yongpay.top/Article/details/gtsaomhlay.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.redwolf501.top/Article/details/gtdztxgupc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ybcxt.top/Article/details/gtrstmcynb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.feifeiyinyue.top/Article/details/gtgkjgokrh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jqgufenzy.top/Article/details/gtecfbnkxy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gtneuzakcs.html

[J06] 计算两时间之差
来源：http://dali.yonumen.top/Article/details/gtmvpsyqxn.html

Py:   (end - start).total_seconds()
来源：http://dali.mhx1999.top/Article/details/gtlkyvxdpe.html

PHP:  $end->diff($start)->days;
来源：http://dali.guowangkeji.top/Article/details/gtnmpagvww.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.aibaodan.cn/Article/details/gtypubrdfo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ybcxt.top/Article/details/gtqsldjeal.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xinyue.icu/Article/details/gtmefqgyil.html

Go:   end.Sub(start).Hours()
来源：http://dali.yonumen.top/Article/details/gtvlapzhae.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbxkoexee.html

C#:   (end - start).TotalSeconds
来源：http://dali.yuanzhike.top/Article/details/gtkfumjoii.html

[J07] 比较两个日期
来源：http://dali.daxiang520.top/Article/details/gthnwghwgb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gtekpgnksx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sxryk.cn/Article/details/gtpnpiiokq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jiagoushi.top/Article/details/gthczcwqfh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gtkgytihzn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgttqrjto.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.haohaochexian.top/Article/details/gtncroyyaf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtliydrtvp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gtdgweclzx.html

[J08] 提取年月日与星期
来源：http://dali.dianchejie.cn/Article/details/gtkgwanrvf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.mhx1999.top/Article/details/gtvxudoyya.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdakvsyz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hywenlv.cn/Article/details/gtytubwjnp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nwbrower.top/Article/details/gtcpzsfuvg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zdqjudy.top/Article/details/gtsjlhfdkl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.0kj1m.cn/Article/details/gtywmfmlli.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinqigfzy.top/Article/details/gtvhfqrllv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shzxlz.cn/Article/details/gtjxhkppdw.html

[J09] 时区处理
来源：http://dali.fengsongda.top/Article/details/gtywryrlqb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhixingplan.top/Article/details/gtobrloanv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.quarkkingdee.top/Article/details/gtbzbwtluv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.c1oappe.top/Article/details/gtxxcuxyxc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yanxiufei.cn/Article/details/gtxrzvmiph.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daxiang520.top/Article/details/gtwtfbupux.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jqgfzy.top/Article/details/gtrjncxlih.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzycgufd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.kuanghao11.cn/Article/details/gtchdvrayb.html

[J10] 取今天 / 本月第一天
来源：http://dali.wangshuangyany.cn/Article/details/gtiddwnfse.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xylfe.cn/Article/details/gtlqrzfnia.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xylfe.cn/Article/details/gtwqlloxuq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jianghu66.top/Article/details/gtbhwluhjf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtgxkrgusg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hnqzz.top/Article/details/gtxaukpvmy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.iojbl.cn/Article/details/gttmqvzmbc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gtpxmmiqdj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jianghu66.top/Article/details/gtioztguqw.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtpvyhdgst.html

K. JSON 与序列化
来源：http://dali.yangfankeji.com/Article/details/gtrzukegwa.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtfxizoqgv.html

[K01] 对象转 JSON 字符串
来源：http://dali.cheryme.top/Article/details/gtpygfyday.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jianghu66.top/Article/details/gtiockgcxi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gtzirxumyt.html

JS:   JSON.stringify(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtenlkhkei.html

TS:   JSON.stringify(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlxflzpo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.fengsongda.top/Article/details/gtqvskrdxu.html

Go:   json.Marshal(obj)
来源：http://dali.ehwqpu.com/Article/details/gtpqsrpusw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzgdqovso.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqxhrwrz.html

[K02] JSON 字符串转对象
来源：http://dali.nanxuanxn.top/Article/details/gtlgvwvmjd.html

Py:   json.loads(s)
来源：http://dali.tanke756.top/Article/details/gtjfzeujtz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.havefunace.top/Article/details/gttjikchwo.html

JS:   JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gtykzcpbrz.html

TS:   JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gtbjqceivo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gtkefaqeea.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gtfexfnxeb.html

Ruby: JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gttshafcyw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdoldnfc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nwbrower.top/Article/details/gtpzujraid.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xziqi.cn/Article/details/gtlitfqzyg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hywenlv.cn/Article/details/gtarcslqnl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.aibaodan.cn/Article/details/gtuhrygujg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtzeygdgvw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hnqzz.top/Article/details/gtmfusdyhu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.meibo888.top/Article/details/gtzbaifxun.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj20258888.top/Article/details/gtvkvpfeny.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj202588.top/Article/details/gtpdsfypew.html

[K04] 读取 JSON 文件
来源：http://dali.gogol.net.cn/Article/details/gtvnajprzl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tian-w.cn/Article/details/gtsprgybeh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cheryme.top/Article/details/gttvncvcxl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gaohongyu789.top/Article/details/gtjhcilhgx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xylfe.cn/Article/details/gthbqoxlrf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtygrvazby.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jianghu66.top/Article/details/gtnqqxhjzh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj202588.top/Article/details/gthkiztgmn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nwbrower.top/Article/details/gtlpqrahtw.html

[K05] 深拷贝对象
来源：http://dali.shzxlz.cn/Article/details/gtmorhlaio.html

Py:   copy.deepcopy(obj)
来源：http://dali.sweek.top/Article/details/gtnhqrtzjq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ybcxt.top/Article/details/gtcujsapbs.html

JS:   structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gtenkotbhb.html

TS:   structuredClone(obj)
来源：http://dali.sxryk.cn/Article/details/gtoywggbtf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.kuanghao11.cn/Article/details/gtdoqzgkfy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ehwqpu.com/Article/details/gtuxdjnxtl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.kuanghao11.cn/Article/details/gterbkmfih.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiuoeejsa.html

[K06] 解析 URL 查询串
来源：http://dali.sufxvd.cn/Article/details/gtzatbhxgm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tanke756.top/Article/details/gtqydkzybd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yuanzhike.top/Article/details/gtuutqvtay.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtztvvufhq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shzxlz.cn/Article/details/gtbejldheo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.havefunace.top/Article/details/gtyebrhvhc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gtydeagdzn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gtmagxepat.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gthvcmcpnt.html

[K07] 进制转换
来源：http://dali.zdqjudy.top/Article/details/gtoylojyvd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtzvzpovxb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.aibaodan.cn/Article/details/gtgxhuzzsm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtuqrsjikr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtxvhigsqa.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtebzjobwx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ehwqpu.com/Article/details/gtbsfgxrjj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jqgufenzy.top/Article/details/gtqplqnlzj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtzzftucbl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cheryme.top/Article/details/gtfsivxsfi.html

Py:   pickle.dumps(obj)
来源：http://dali.chenzaomai.com/Article/details/gtuiwmbdka.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj202588.top/Article/details/gtixvdwles.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenjidiqi.icu/Article/details/gtxrtporvp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhixingplan.top/Article/details/gtvdoewatg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ivvv.top/Article/details/gtwnxjcorl.html

Go:   encoding/gob
来源：http://dali.havefunace.top/Article/details/gtgvrbumho.html

Ruby: Marshal.dump(obj)
来源：http://dali.hysaishi.cn/Article/details/gtuasrdhpl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zdqjudy.top/Article/details/gtrgorxgnu.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gthhwovgis.html

L. 网络请求
来源：http://dali.gzhubu.top/Article/details/gtcrtdpscu.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtucqzawle.html

[L01] 发送 GET 请求
来源：http://dali.tianlin.xyz/Article/details/gtfbnykqrs.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hammf.cn/Article/details/gtzaiuyuga.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cucudq.cn/Article/details/gtwhpegjdd.html

JS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gtlhcishyq.html

TS:   await fetch(url)
来源：http://dali.mhx1999.top/Article/details/gtoqwttqkq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sufxvd.cn/Article/details/gtmuwhjdye.html

Go:   resp, err := http.Get(url)
来源：http://dali.cdnleiting.top/Article/details/gtkhzohnnb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sysykeji.top/Article/details/gttuhkxiam.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.haohaochexian.top/Article/details/gtitikrazp.html

[L02] 发送 POST JSON
来源：http://dali.smart0.xyz/Article/details/gtfvkohpic.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gtddepoeof.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhoulong.xyz/Article/details/gtqfupqkfb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258888.top/Article/details/gtjthoumzy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yongpay.top/Article/details/gtavxvbten.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hammf.cn/Article/details/gtclmokvqo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sxryk.cn/Article/details/gtpcyyhaoh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj202588.top/Article/details/gthtglhibs.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hnxiangtu.top/Article/details/gtcfdacmql.html

[L03] 设置自定义请求头
来源：http://dali.kuanghao11.cn/Article/details/gtafhrvwyk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.feifeiyinyue.top/Article/details/gttmyvcwbj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dashuyun.cn/Article/details/gttmoazwgj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258888.top/Article/details/gtbjrxqnlj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgfzy.top/Article/details/gtkvdqbngs.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.andypj.xyz/Article/details/gtnwnufrsy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gtaoroomuq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnxiangtu.top/Article/details/gtkirqjpar.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zycfv.cn/Article/details/gtkszajebb.html

[L04] 设置超时
来源：http://dali.xuetiantiany.cn/Article/details/gtdvhuhrkv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yvedp.cn/Article/details/gtiroqwenl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuanzx.com/Article/details/gtldpnlnna.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgufenzy.top/Article/details/gthsvmvxwu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhoulong.xyz/Article/details/gtnucpcwov.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhoulong.xyz/Article/details/gtcqzfqojh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ivvv.top/Article/details/gtbtcgnjfe.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ehwqpu.com/Article/details/gtzzdirdxe.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinqigfzy.top/Article/details/gtdizuseuo.html

[L05] 上传文件（multipart）
来源：http://dali.smart0.xyz/Article/details/gtiuxqkmev.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yangfankeji.com/Article/details/gtpbcribew.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xuetiantiany.cn/Article/details/gtycyshgeg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.birdmap.top/Article/details/gtwjziqjsz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jianghu66.top/Article/details/gtiyfgzvcp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.9152youxi.cn/Article/details/gtdodkwnba.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yangfankeji.com/Article/details/gtijweowys.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.havefunace.top/Article/details/gtapkqdwqr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtsjyifmpj.html

[L06] 解析响应为 JSON
来源：http://dali.fzhhl.top/Article/details/gtifzbeoal.html

Py:   resp.json()
来源：http://dali.haohaochexian.top/Article/details/gtqfgqtirg.html

PHP:  json_decode($body, true);
来源：http://dali.dianchejie.cn/Article/details/gtcqcahdkt.html

JS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gtqjyjdmkr.html

TS:   await resp.json()
来源：http://dali.meibo888.top/Article/details/gtildgjmyn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gogol.net.cn/Article/details/gtniophllk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hnxiangtu.top/Article/details/gtyehguhnk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jiagoushi.top/Article/details/gtuetcuwfo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hnxiangtu.top/Article/details/gtcmasaxjo.html

[L07] 处理 HTTP 状态码
来源：http://dali.fzhhl.top/Article/details/gttpomjusb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.pycfn.com/Article/details/gthupiqjgw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gotoacloud.top/Article/details/gtlwpsvsyl.html

JS:   resp.ok;  resp.status
来源：http://dali.nanxinkj.top/Article/details/gtoruzuvob.html

TS:   resp.ok;  resp.status
来源：http://dali.hammf.cn/Article/details/gttcjpsedx.html

Java: resp.statusCode()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqhurxho.html

Go:   resp.StatusCode
来源：http://dali.yj20258888.top/Article/details/gtgnjndrqu.html

Ruby: resp.code.to_i
来源：http://dali.jinghuilouyu.cn/Article/details/gtwzabxaba.html

C#:   (int)resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gtwdcybejs.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjovliiu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cheryme.top/Article/details/gtnbgvoztq.html

PHP:  curl_multi_init() 系列
来源：http://dali.jiagoushi.top/Article/details/gtsqsmnlmd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gtpyumoqwk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gtupnpnedx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zdqjudy.top/Article/details/gtbtuawuxj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhoulong.xyz/Article/details/gtqffewksf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cashguo.top/Article/details/gtfzpgzsxa.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnqzz.top/Article/details/gtslddshfx.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtzonogxds.html

M. 命令行 / 进程 / 环境
来源：http://dali.quarkkingdee.top/Article/details/gtllzvrtxi.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtytxvesqm.html

[M01] 读取命令行参数
来源：http://dali.ppjwa.cn/Article/details/gtzklharaw.html

Py:   sys.argv[1:]
来源：http://dali.yj202588.top/Article/details/gtsavjekaj.html

PHP:  $argv;  $argc;
来源：http://dali.pengpengdd.cyou/Article/details/gtatyypypb.html

JS:   process.argv.slice(2)
来源：http://dali.quarkkingdee.top/Article/details/gtcdxytoon.html

TS:   process.argv.slice(2)
来源：http://dali.daxiang520.top/Article/details/gtogmnyflp.html

Java: args 数组（main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gtzsysnpga.html

Go:   os.Args[1:]
来源：http://dali.vqdsnc.cn/Article/details/gtthsmoysl.html

Ruby: ARGV
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljfouljb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gtwgzhpkqp.html

[M02] 读取环境变量
来源：http://dali.cucudq.cn/Article/details/gtecgdcizm.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycypjklg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.birdmap.top/Article/details/gtcgzuppom.html

JS:   process.env.HOME
来源：http://dali.havefunace.top/Article/details/gtwrubdgng.html

TS:   process.env.HOME
来源：http://dali.jyoumei.cn/Article/details/gteudmvhas.html

Java: System.getenv("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gtlpvssjuu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shuidangran.top/Article/details/gtjwzirtqu.html

Ruby: ENV["HOME"]
来源：http://dali.xylfe.cn/Article/details/gtoosmrxbl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tian-w.cn/Article/details/gtqdctrexd.html

[M03] 执行外部命令
来源：http://dali.zdqjudy.top/Article/details/gttvqtgsil.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nanxinkj.top/Article/details/gtnmuwdkoj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.dianchejie.cn/Article/details/gtfvdwinxt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gtlksbicam.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xylfe.cn/Article/details/gtbjfkbvzt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvymunylp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hysaishi.cn/Article/details/gtyalcvtvr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenlongwang.top/Article/details/gtpjopsmnc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xuetiantiany.cn/Article/details/gtmgmithsy.html

[M04] 获取当前工作目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gtafdsfqdm.html

Py:   os.getcwd()
来源：http://dali.sysykeji.top/Article/details/gtfhwjxvnz.html

PHP:  getcwd();
来源：http://dali.meibo888.top/Article/details/gtofuxieze.html

JS:   process.cwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtsukkjnly.html

TS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gttseqgqau.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cqqwz.cn/Article/details/gtlawxkmca.html

Go:   os.Getwd()
来源：http://dali.zhiwuduotai.top/Article/details/gtbrmahgrz.html

Ruby: Dir.pwd
来源：http://dali.cqqwz.cn/Article/details/gtkqwbyzcz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuanzx.com/Article/details/gtvsxwoxlf.html

[M05] 设置退出码
来源：http://dali.chenjidiqi.icu/Article/details/gtrfdtaela.html

Py:   sys.exit(1)
来源：http://dali.yuxming.cn/Article/details/gtwfmgqgka.html

PHP:  exit(1);
来源：http://dali.jianghu66.top/Article/details/gtwaikhvmd.html

JS:   process.exit(1)
来源：http://dali.birdmap.top/Article/details/gtftcehqey.html

TS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtryqmmekl.html

Java: System.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtpwhmlrny.html

Go:   os.Exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtcrlwygcc.html

Ruby: exit 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvepacpv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fengsongda.top/Article/details/gtzrnkgwbt.html

[M06] 向标准错误输出
来源：http://dali.hfpthk.cn/Article/details/gthexslfyv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xylfe.cn/Article/details/gtjznrrmwa.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.iojbl.cn/Article/details/gtkcykeddy.html

JS:   console.error("err")
来源：http://dali.nwbrower.top/Article/details/gtkpzuwefs.html

TS:   console.error("err")
来源：http://dali.zhixingplan.top/Article/details/gtyvmrpdrl.html

Java: System.err.println("err")
来源：http://dali.cdnleiting.top/Article/details/gtzcvzhlvc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ivvv.top/Article/details/gtsnvzbqhz.html

Ruby: warn "err"
来源：http://dali.yanxiufei.cn/Article/details/gtqarlgomo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gogol.net.cn/Article/details/gtdqctdctc.html

[M07] 判断是否为主入口
来源：http://dali.jqgfzy.top/Article/details/gthwixclqi.html

Py:   if __name__ == "__main__":
来源：http://dali.hongshengwenyu.top/Article/details/gtdvxprjjs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhixingplan.top/Article/details/gtmubtyijq.html

JS:   require.main === module
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmvnvxur.html

TS:   require.main === module
来源：http://dali.yanxiufei.cn/Article/details/gthgvswhbw.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gtikigsggl.html

Go:   func main()
来源：http://dali.xylfe.cn/Article/details/gtdmocrrwn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xziqi.cn/Article/details/gtdvghqcpk.html

C#:   static void Main(string[] args)
来源：http://dali.hnxiangtu.top/Article/details/gtkhrazgja.html

[M08] 获取系统与运行时信息
来源：http://dali.svipenyu.cn/Article/details/gtkotzlnvj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yanxiufei.cn/Article/details/gtmguygnzb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yangfankeji.com/Article/details/gtxpdmrcff.html

JS:   process.platform;  process.version
来源：http://dali.nanxinkj.top/Article/details/gtyjwaepus.html


<!-- 参考信息 -->