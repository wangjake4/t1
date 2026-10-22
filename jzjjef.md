代发 wailian999

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shangyingyoupin.top/Article/details/gtrfgujebw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.dashuyun.cn/Article/details/gtojgpdxtb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gtypfohtjs.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hysaishi.cn/Article/details/gtrvxobmjx.html

[J03] 字符串解析为日期
来源：http://dali.chenzaomai.com/Article/details/gtiulfgkgb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.bjfxy.top/Article/details/gtjbemedio.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xuanzx.com/Article/details/gtyhguujmh.html

JS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtwwyflhjs.html

TS:   new Date("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtswevcfxn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtsfrbtqme.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtxnxhatsx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtlicdcezz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.316326.xyz/Article/details/gtpargwznh.html

[J04] 时间戳与日期互转
来源：http://dali.yonumen.top/Article/details/gtijwyvwcq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.mhx1999.top/Article/details/gtfpjjllgs.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.pengpengdd.cyou/Article/details/gtddnltoch.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.0kj1m.cn/Article/details/gtrxnmezla.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ppjwa.cn/Article/details/gtvdvzsdbf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xziqi.cn/Article/details/gtvgguadeh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtjrvcyxum.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinqigfzy.top/Article/details/gtnzwtysqt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinqigfzy.top/Article/details/gtsooswbut.html

[J05] 时间加减（加 7 天）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtinygzvtf.html

Py:   now + timedelta(days=7)
来源：http://dali.gzhubu.top/Article/details/gtjxpfyjpg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj202588.top/Article/details/gtqtzzzzeh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gzhubu.top/Article/details/gtfnpbitwh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuxming.cn/Article/details/gtspkrjntt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yuxming.cn/Article/details/gtoihnzzjb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.316326.xyz/Article/details/gtwnuvhxnk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinqigufen.top/Article/details/gtfgatlxbs.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.0kj1m.cn/Article/details/gthgphbnqi.html

[J06] 计算两时间之差
来源：http://dali.haohaochexian.top/Article/details/gtbgwowcku.html

Py:   (end - start).total_seconds()
来源：http://dali.gogol.net.cn/Article/details/gtvbmljuro.html

PHP:  $end->diff($start)->days;
来源：http://dali.iojbl.cn/Article/details/gthfoxnxgk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.guowangkeji.top/Article/details/gtpedonllq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yongpay.top/Article/details/gtlsodtkfh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhdbdznu.html

Go:   end.Sub(start).Hours()
来源：http://dali.jqgufenzy.top/Article/details/gtbrukrznw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ivvv.top/Article/details/gtcaisqwky.html

C#:   (end - start).TotalSeconds
来源：http://dali.jyoumei.cn/Article/details/gtzxvmtbak.html

[J07] 比较两个日期
来源：http://dali.yj20258888.top/Article/details/gthbcajszi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgehycltg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tianlin.xyz/Article/details/gttozjzkez.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhongyouzk.top/Article/details/gtmrmhperc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gtlipcwxyp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ybcxt.top/Article/details/gtbpbkbskp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nanxinkj.top/Article/details/gtxipuqxsk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gtkrfxkwsm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gtlcmfcsrl.html

[J08] 提取年月日与星期
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkflhhpu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hnqzz.top/Article/details/gthmslxbqv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.vqdsnc.cn/Article/details/gtacnhlxdj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ehwqpu.com/Article/details/gtpxdyenek.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtikzkrzxd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zycfv.cn/Article/details/gtobdvuhop.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinghuilouyu.cn/Article/details/gthcorjeaz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhengqikj.top/Article/details/gtfztrvcki.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ydzc1.top/Article/details/gtvdjsaryl.html

[J09] 时区处理
来源：http://dali.ehwqpu.com/Article/details/gtjdddtvus.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj202588.top/Article/details/gttxwetduj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yueranfly.top/Article/details/gttapjgipd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhongyouzk.top/Article/details/gtabuphuzj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.0kj1m.cn/Article/details/gtzbuexbnk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuanzx.com/Article/details/gtdltnetxn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.redwolf501.top/Article/details/gtkwwwxhbf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvmscugfm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zdqjudy.top/Article/details/gtrjvdhcup.html

[J10] 取今天 / 本月第一天
来源：http://dali.c1oappe.top/Article/details/gtcnfmeuga.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnkqgvcz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shangyingyoupin.top/Article/details/gtolkaiics.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj20258.top/Article/details/gtvtydlosl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.dianchejie.cn/Article/details/gtfldumqty.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xylfe.cn/Article/details/gtodmsobko.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.quarkkingdee.top/Article/details/gtclzpocob.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hfpthk.cn/Article/details/gtosmnpfgo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tianlin.xyz/Article/details/gtplkrsnoo.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtbkettdrb.html

K. JSON 与序列化
来源：http://dali.zhoulong.xyz/Article/details/gtfzbxucbo.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtqbwicjbe.html

[K01] 对象转 JSON 字符串
来源：http://dali.cucudq.cn/Article/details/gtwrotsiyy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.daria6918.cn/Article/details/gtcsdkmvat.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hywenlv.cn/Article/details/gtfnirgudm.html

JS:   JSON.stringify(obj)
来源：http://dali.smart0.xyz/Article/details/gtpgdyfosq.html

TS:   JSON.stringify(obj)
来源：http://dali.hammf.cn/Article/details/gtpxlsplnw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.snrcjt.cn/Article/details/gtdwxendcw.html

Go:   json.Marshal(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtjvhriahv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.fengsongda.top/Article/details/gtyansviti.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.haohaochexian.top/Article/details/gtbpipeswz.html

[K02] JSON 字符串转对象
来源：http://dali.pengpengdd.cyou/Article/details/gtglhyotcp.html

Py:   json.loads(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtuxfxjytz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.pengpengdd.cyou/Article/details/gtyojbacvj.html

JS:   JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gtfvkvzxsn.html

TS:   JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtgjputigf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.aizwys.cn/Article/details/gtekbmlvjj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwjeixwz.html

Ruby: JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpgzgcrlf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.mhx1999.top/Article/details/gtnxjpgocn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvtwaqydl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.haohaochexian.top/Article/details/gtiureycvm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xinyue.icu/Article/details/gtlykiiqel.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhengqikj.top/Article/details/gtowkavedy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvhzpoqkc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtddewvpsw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yangfankeji.com/Article/details/gtnaooryhq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.0kj1m.cn/Article/details/gtxpyfppjm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ybcxt.top/Article/details/gtphqzmeia.html

[K04] 读取 JSON 文件
来源：http://dali.quarkkingdee.top/Article/details/gtzhzlywry.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hammf.cn/Article/details/gtitugbphy.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangshuangyany.cn/Article/details/gthfdlulvi.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sweek.top/Article/details/gtubdjwmfn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gtogagioos.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gtmmaeorvr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gtkfttwxep.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtallaczku.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gtwbnjiqtz.html

[K05] 深拷贝对象
来源：http://dali.jyoumei.cn/Article/details/gtdgfbpyvl.html

Py:   copy.deepcopy(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtduyqugym.html

PHP:  unserialize(serialize($obj));
来源：http://dali.pengpengdd.cyou/Article/details/gtwsjbdqpa.html

JS:   structuredClone(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrazryikz.html

TS:   structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gtjswodbbm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zdqjudy.top/Article/details/gtmxuzdeao.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hfpthk.cn/Article/details/gtxejwfjkm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cucudq.cn/Article/details/gtftglybxn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtutsoljsl.html

[K06] 解析 URL 查询串
来源：http://dali.iojbl.cn/Article/details/gtqestmgta.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.snrcjt.cn/Article/details/gtlbazopka.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sweek.top/Article/details/gteiurveob.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhoulong.xyz/Article/details/gthggqndbr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.vqdsnc.cn/Article/details/gtmabibcac.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsieqlbzv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gtugsxxomb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gtqfbnehvl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gtvplhmyte.html

[K07] 进制转换
来源：http://dali.ehwqpu.com/Article/details/gtxwhmpedl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtkvjgleln.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxuanxn.top/Article/details/gtlsqxanmt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtuzymgljt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gterfyiedq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtcpfdcxyg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.smart0.xyz/Article/details/gtagbyxobo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sysykeji.top/Article/details/gtgdzcauvk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtexxltadq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hywenlv.cn/Article/details/gtallraein.html

Py:   pickle.dumps(obj)
来源：http://dali.yonumen.top/Article/details/gtzloaproo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yangfankeji.com/Article/details/gtqfecscaj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shuidangran.top/Article/details/gtojnhytwq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yangfankeji.com/Article/details/gtjenrnlgn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.aibaodan.cn/Article/details/gtbndtoqov.html

Go:   encoding/gob
来源：http://dali.hywenlv.cn/Article/details/gtbadqcdne.html

Ruby: Marshal.dump(obj)
来源：http://dali.316326.xyz/Article/details/gtkkgxpkac.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.316326.xyz/Article/details/gtjjimypou.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtwrmkrgwu.html

L. 网络请求
来源：http://dali.hammf.cn/Article/details/gthtuksmdv.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtkogqqkmt.html

[L01] 发送 GET 请求
来源：http://dali.fzhhl.top/Article/details/gtxxlamswo.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj202588.top/Article/details/gtsreoaxbm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.guowangkeji.top/Article/details/gtweuagwgd.html

JS:   await fetch(url)
来源：http://dali.kuanghao11.cn/Article/details/gtvhonyazr.html

TS:   await fetch(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcsoizeut.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenzaomai.com/Article/details/gtwxlhgftg.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhongyouzk.top/Article/details/gtgznbktet.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cdnleiting.top/Article/details/gtkybanfew.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yanxiufei.cn/Article/details/gtfepdfwxa.html

[L02] 发送 POST JSON
来源：http://dali.xziqi.cn/Article/details/gtexybjquw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirffaxid.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.snrcjt.cn/Article/details/gtwxittvzd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shzxlz.cn/Article/details/gtcreaeyqm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gtctbecdwc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xinyue.icu/Article/details/gtdhzlcdvq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yonumen.top/Article/details/gtecjlhadg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gzhubu.top/Article/details/gtbnazpric.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.meibo888.top/Article/details/gtjsobcpzn.html

[L03] 设置自定义请求头
来源：http://dali.redwolf501.top/Article/details/gtftnferby.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhongyouzk.top/Article/details/gtjztdypts.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nwbrower.top/Article/details/gtzmsrkhjp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aibaodan.cn/Article/details/gtbqkrntci.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigufen.top/Article/details/gtcrhhrgjw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xziqi.cn/Article/details/gtriwgspbr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtteauczlk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yonumen.top/Article/details/gtsshhlvtk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.quarkkingdee.top/Article/details/gtllgbbbpx.html

[L04] 设置超时
来源：http://dali.gogol.net.cn/Article/details/gttsedhtte.html

Py:   requests.get(url, timeout=5)
来源：http://dali.bjfxy.top/Article/details/gtiaiptdlf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.iojbl.cn/Article/details/gtrukrohny.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cucudq.cn/Article/details/gtdrvlsvne.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yongpay.top/Article/details/gtqryhqcxr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenlongwang.top/Article/details/gthplmzntt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangdashe.top/Article/details/gtwzbwowrq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cqqwz.cn/Article/details/gtamzeilzg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.smart0.xyz/Article/details/gtgtbmaqlv.html

[L05] 上传文件（multipart）
来源：http://dali.yanxiufei.cn/Article/details/gtrrmhczjg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tianlin.xyz/Article/details/gtwlyxjkpg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hfpthk.cn/Article/details/gtaiokcote.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gtjgkvgysg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gtvubdvcqe.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jianghu66.top/Article/details/gtmbyzbksk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jlsjyb.cn/Article/details/gtzwyfuzpl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.svipenyu.cn/Article/details/gtfgbhgaza.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtxnsagxwt.html

[L06] 解析响应为 JSON
来源：http://dali.0kj1m.cn/Article/details/gtdgijfodx.html

Py:   resp.json()
来源：http://dali.jyoumei.cn/Article/details/gtwodbjbpg.html

PHP:  json_decode($body, true);
来源：http://dali.yuanzhike.top/Article/details/gtlozxabsr.html

JS:   await resp.json()
来源：http://dali.fzhhl.top/Article/details/gtwuufntbj.html

TS:   await resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxydcshyh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.daxiang520.top/Article/details/gtrkyulktk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jyoumei.cn/Article/details/gtsuwwhoyb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhoulong.xyz/Article/details/gtqrtcdnoj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aibaodan.cn/Article/details/gtopcncnvm.html

[L07] 处理 HTTP 状态码
来源：http://dali.jiagoushi.top/Article/details/gtnreuyyzb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258888.top/Article/details/gtkizfpdat.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.bjfxy.top/Article/details/gtuomtsyrb.html

JS:   resp.ok;  resp.status
来源：http://dali.shzxlz.cn/Article/details/gtyprztxfa.html

TS:   resp.ok;  resp.status
来源：http://dali.cucudq.cn/Article/details/gtgxrzafoh.html

Java: resp.statusCode()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyrvcokfh.html

Go:   resp.StatusCode
来源：http://dali.yj20258.top/Article/details/gthjbswmba.html

Ruby: resp.code.to_i
来源：http://dali.aibaodan.cn/Article/details/gtcoozvdwk.html

C#:   (int)resp.StatusCode
来源：http://dali.redwolf501.top/Article/details/gtremzdozu.html

[L08] 并发请求多个地址
来源：http://dali.zdqjudy.top/Article/details/gtekeloruu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xylfe.cn/Article/details/gtgvtmgjjh.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangdashe.top/Article/details/gtlynpepjj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gtefnrlxzv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gthoxvnecf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhengqikj.top/Article/details/gtocwsxxmy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhoulong.xyz/Article/details/gtobvofgmy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gtpgdqgbag.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hywenlv.cn/Article/details/gtrjztkwvc.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtwaajwwwk.html

M. 命令行 / 进程 / 环境
来源：http://dali.shuidangran.top/Article/details/gtfhmdqucf.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtzmdivgaa.html

[M01] 读取命令行参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezdrmxsy.html

Py:   sys.argv[1:]
来源：http://dali.hammf.cn/Article/details/gtcalpjezr.html

PHP:  $argv;  $argc;
来源：http://dali.9152youxi.cn/Article/details/gtghqufqdk.html

JS:   process.argv.slice(2)
来源：http://dali.smart0.xyz/Article/details/gtytdiqivz.html

TS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gtakdsgslj.html

Java: args 数组（main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpyjilwiw.html

Go:   os.Args[1:]
来源：http://dali.jinqigufen.top/Article/details/gtiagbvnmx.html

Ruby: ARGV
来源：http://dali.guowangkeji.top/Article/details/gtctnihaqm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nanxuanxn.top/Article/details/gtqgwxbstc.html

[M02] 读取环境变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswupskkf.html

Py:   os.environ.get("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtlcufzjij.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gthsnenjot.html

JS:   process.env.HOME
来源：http://dali.yj20258.top/Article/details/gtckipkooz.html

TS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gtopsgdnrh.html

Java: System.getenv("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtrbfphmgt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtveztgnlr.html

Ruby: ENV["HOME"]
来源：http://dali.cucudq.cn/Article/details/gtbsjcosbv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tanke756.top/Article/details/gtvbwrmpmg.html

[M03] 执行外部命令
来源：http://dali.shuidangran.top/Article/details/gtkjhthdwh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhengqikj.top/Article/details/gtrobcucnh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hongshengwenyu.top/Article/details/gtfjogzzip.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtneuiguib.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgufenzy.top/Article/details/gtubyklptq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cqqwz.cn/Article/details/gtuivptvhb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zdqjudy.top/Article/details/gtclwrqufq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenjidiqi.icu/Article/details/gtojdheljx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hfpthk.cn/Article/details/gtcchswwet.html

[M04] 获取当前工作目录
来源：http://dali.yanxiufei.cn/Article/details/gtgyhrhksf.html

Py:   os.getcwd()
来源：http://dali.ivvv.top/Article/details/gtxmarcnro.html

PHP:  getcwd();
来源：http://dali.aibaodan.cn/Article/details/gtbjzuxcuk.html

JS:   process.cwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtyhxiztje.html

TS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gtxpmvymqa.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gtxgfrjwws.html

Go:   os.Getwd()
来源：http://dali.gzhubu.top/Article/details/gtqtemyxfo.html

Ruby: Dir.pwd
来源：http://dali.yueranfly.top/Article/details/gtomqouwyp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxuldnrxp.html

[M05] 设置退出码
来源：http://dali.xylfe.cn/Article/details/gtdnbbqvkt.html

Py:   sys.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtlazpecpc.html

PHP:  exit(1);
来源：http://dali.zycfv.cn/Article/details/gtqbparuzd.html

JS:   process.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtiqiqpneb.html

TS:   process.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtafxtkkyd.html

Java: System.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtkxlizmxd.html

Go:   os.Exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtndhxhrbu.html

Ruby: exit 1
来源：http://dali.guannengcc.top/Article/details/gtarkpatzm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zdqjudy.top/Article/details/gtvwfgynak.html

[M06] 向标准错误输出
来源：http://dali.gotoacloud.top/Article/details/gtmheevwsr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.redwolf501.top/Article/details/gtiiuhuvcf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.haohaochexian.top/Article/details/gtvjgqphmb.html

JS:   console.error("err")
来源：http://dali.shzxlz.cn/Article/details/gtpnaktare.html

TS:   console.error("err")
来源：http://dali.zhoulong.xyz/Article/details/gtmotjkrmz.html

Java: System.err.println("err")
来源：http://dali.daxiang520.top/Article/details/gtzsrebgjm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.aizwys.cn/Article/details/gtnmfmisoo.html

Ruby: warn "err"
来源：http://dali.cqqwz.cn/Article/details/gtmqdjagyc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.snrcjt.cn/Article/details/gtjnynqity.html

[M07] 判断是否为主入口
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmfknmlsy.html

Py:   if __name__ == "__main__":
来源：http://dali.xinyue.icu/Article/details/gtkaabvxmc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnxiangtu.top/Article/details/gtvglzakuh.html

JS:   require.main === module
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnsiqdxxk.html

TS:   require.main === module
来源：http://dali.wangshuangyany.cn/Article/details/gtpgokspur.html

Java: public static void main(String[] args)
来源：http://dali.ybcxt.top/Article/details/gtblmlmkfk.html

Go:   func main()
来源：http://dali.dashuyun.cn/Article/details/gttteanjld.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zdqjudy.top/Article/details/gtqobtghfc.html

C#:   static void Main(string[] args)
来源：http://dali.andypj.xyz/Article/details/gtjtxiyscy.html

[M08] 获取系统与运行时信息
来源：http://dali.quarkkingdee.top/Article/details/gtvadskeae.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jyoumei.cn/Article/details/gtnkjghast.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj202588.top/Article/details/gtbynnmjut.html

JS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gtfjydtxvl.html

TS:   process.platform;  process.version
来源：http://dali.chenjidiqi.icu/Article/details/gtadukuloo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxuanxn.top/Article/details/gtxfjqcmbp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttknnfkkl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sweek.top/Article/details/gtmtulomms.html


<!-- 参考信息 -->