代发 wailian999

TS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtiiebomev.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtqubqcrls.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtczdhmtpe.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtnieifpdb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cqqwz.cn/Article/details/gtvsifbwwp.html

[J04] 时间戳与日期互转
来源：http://dali.zhongyouzk.top/Article/details/gtxvatwjni.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhoulong.xyz/Article/details/gtjmioscgk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.0kj1m.cn/Article/details/gtihqllzwe.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ppjwa.cn/Article/details/gtdbvibayf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hysaishi.cn/Article/details/gtioaxudos.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cqqwz.cn/Article/details/gtutamdmtz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sysykeji.top/Article/details/gtxuflpbgr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.pycfn.com/Article/details/gtirvpsqbl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258.top/Article/details/gtccqbtkaa.html

[J05] 时间加减（加 7 天）
来源：http://dali.svipenyu.cn/Article/details/gtvnvhrogg.html

Py:   now + timedelta(days=7)
来源：http://dali.ivvv.top/Article/details/gtlkkdmbzb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zdqjudy.top/Article/details/gtrvvfkjge.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gtdcizousr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtillkpbhe.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yangfankeji.com/Article/details/gtqcaakpnl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tian-w.cn/Article/details/gtubyfsmxp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xylfe.cn/Article/details/gtjjvrmrmi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.snrcjt.cn/Article/details/gtvamuncxk.html

[J06] 计算两时间之差
来源：http://dali.yuxming.cn/Article/details/gtevgbdcnu.html

Py:   (end - start).total_seconds()
来源：http://dali.zhiwuduotai.top/Article/details/gthfmririi.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhongyouzk.top/Article/details/gtiunrezgi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenjidiqi.icu/Article/details/gtuhlovpbs.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.0kj1m.cn/Article/details/gtunvniljq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhengqikj.top/Article/details/gtvvdmmubo.html

Go:   end.Sub(start).Hours()
来源：http://dali.hysaishi.cn/Article/details/gtzygewdsp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhoulong.xyz/Article/details/gtqeokjmvd.html

C#:   (end - start).TotalSeconds
来源：http://dali.yvedp.cn/Article/details/gtxkfmhzcp.html

[J07] 比较两个日期
来源：http://dali.chenjidiqi.icu/Article/details/gtpnmuwvyu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gtnbidghrl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgufenzy.top/Article/details/gtmbdoubag.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gtrkybmzzy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.9152youxi.cn/Article/details/gtxxnnycxk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.meibo888.top/Article/details/gtyzcutwqo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dianchejie.cn/Article/details/gtbszueqxn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gtyicyymcf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jiagoushi.top/Article/details/gtgdgdporw.html

[J08] 提取年月日与星期
来源：http://dali.ybcxt.top/Article/details/gtrcudipvu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cdnleiting.top/Article/details/gtmzoxckzb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cashguo.top/Article/details/gtyyzihtut.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.iojbl.cn/Article/details/gtkvxirqoe.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.pengpengdd.cyou/Article/details/gtwirbqftx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sufxvd.cn/Article/details/gtxrecnbtb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.pengpengdd.cyou/Article/details/gtjuqtdaaw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.snrcjt.cn/Article/details/gtsvzxfvck.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cqqwz.cn/Article/details/gthtxeibmc.html

[J09] 时区处理
来源：http://dali.hnqzz.top/Article/details/gtidpvemar.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.svipenyu.cn/Article/details/gtzsebihsc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shuidangran.top/Article/details/gteihpudod.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gtvyntsvhz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.redwolf501.top/Article/details/gtgjpynzsg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gzhubu.top/Article/details/gtylaukzte.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenlongwang.top/Article/details/gtgshkpjpp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.guannengcc.top/Article/details/gtsfjhfnri.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.snrcjt.cn/Article/details/gtnhihlsml.html

[J10] 取今天 / 本月第一天
来源：http://dali.quarkkingdee.top/Article/details/gtwpwbsnrb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.mhx1999.top/Article/details/gteahmtbqd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhiwuduotai.top/Article/details/gtzulpfbyx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.haohaochexian.top/Article/details/gtzakzpujj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtlprzjpzj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aibaodan.cn/Article/details/gtxtxiyjum.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hywenlv.cn/Article/details/gtneqjyfbn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.svipenyu.cn/Article/details/gtuyseyuop.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.dianchejie.cn/Article/details/gtgusiwpub.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtcgkyvixu.html

K. JSON 与序列化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwugjrzwo.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtocyyinoo.html

[K01] 对象转 JSON 字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtlhkyakvv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gtcsplqjgv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.haohaochexian.top/Article/details/gtwgiogjrv.html

JS:   JSON.stringify(obj)
来源：http://dali.fzhhl.top/Article/details/gtasxagmtm.html

TS:   JSON.stringify(obj)
来源：http://dali.tian-w.cn/Article/details/gthzzvwhog.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xylfe.cn/Article/details/gtconucugl.html

Go:   json.Marshal(obj)
来源：http://dali.sxryk.cn/Article/details/gtxbkshhna.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.kuanghao11.cn/Article/details/gtfqciheci.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.havefunace.top/Article/details/gtnhpohnlp.html

[K02] JSON 字符串转对象
来源：http://dali.pengpengdd.cyou/Article/details/gtaasdznzu.html

Py:   json.loads(s)
来源：http://dali.yj20258.top/Article/details/gtupkrahua.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ydzc1.top/Article/details/gtjleisnjk.html

JS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gtcvpdcohn.html

TS:   JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gtrzfeseyt.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shuidangran.top/Article/details/gtewbdcnut.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sysykeji.top/Article/details/gtixlwqhag.html

Ruby: JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gtztdtzjng.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ehwqpu.com/Article/details/gtgldtbmzh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dianchejie.cn/Article/details/gtncusskom.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenzaomai.com/Article/details/gtgqvqamjn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zycfv.cn/Article/details/gtkcmwfgfc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gtqpfrlbhz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.aibaodan.cn/Article/details/gtvleutpkg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nwbrower.top/Article/details/gtgcgyxntd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.0kj1m.cn/Article/details/gtakowtgsr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.iojbl.cn/Article/details/gtthswmwel.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tanke756.top/Article/details/gtczqrucpi.html

[K04] 读取 JSON 文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtpoujyh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.fengsongda.top/Article/details/gtlbpacqfo.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.dashuyun.cn/Article/details/gtbjdjvyuv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkpxyxye.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqlrsabvp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cheryme.top/Article/details/gtpfypahfi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gtqfpntydm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.316326.xyz/Article/details/gtiozbadcc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgtfqrsdt.html

[K05] 深拷贝对象
来源：http://dali.hongshengwenyu.top/Article/details/gtdiexjjht.html

Py:   copy.deepcopy(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtgvzutxal.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xuanzx.com/Article/details/gtwzyavydz.html

JS:   structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gtjjgbweaa.html

TS:   structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gtdugvehjx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.mhx1999.top/Article/details/gttnngegra.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.aizwys.cn/Article/details/gtxldhjffv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tian-w.cn/Article/details/gtwxsctgjf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.316326.xyz/Article/details/gtfbpijsep.html

[K06] 解析 URL 查询串
来源：http://dali.kuanghao11.cn/Article/details/gtrarpakuq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.snrcjt.cn/Article/details/gtjjjdcssj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.svipenyu.cn/Article/details/gtinwwllyr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gtdyrmpdgu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigfzy.top/Article/details/gtzqywowqi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinqigfzy.top/Article/details/gtmatvugfm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gtjfocctws.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtceprcslk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gtymegrrew.html

[K07] 进制转换
来源：http://dali.yonumen.top/Article/details/gtvylcwsfy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtreuodcvt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hammf.cn/Article/details/gtdsgruixw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtymmktosb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtrqjgsmtz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtiwysmuqh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hnxiangtu.top/Article/details/gtwefyeyez.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.mhx1999.top/Article/details/gtrsthqyrd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtwjppwwjw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xziqi.cn/Article/details/gttwbiecds.html

Py:   pickle.dumps(obj)
来源：http://dali.shuidangran.top/Article/details/gtrbchdusa.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yonumen.top/Article/details/gtwcrthame.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shzxlz.cn/Article/details/gtooupyleo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gtlndhqflv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sysykeji.top/Article/details/gtdemrbrgr.html

Go:   encoding/gob
来源：http://dali.sxryk.cn/Article/details/gtojicmttf.html

Ruby: Marshal.dump(obj)
来源：http://dali.daxiang520.top/Article/details/gtdfttgxlz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sysykeji.top/Article/details/gtwqjkvhrg.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtvkhxvohe.html

L. 网络请求
来源：http://dali.ppjwa.cn/Article/details/gtdhjsfdvj.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtnnfmwcss.html

[L01] 发送 GET 请求
来源：http://dali.hnxiangtu.top/Article/details/gtpqchtzfa.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hongshengwenyu.top/Article/details/gtzxahoyro.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jqgufenzy.top/Article/details/gtuwewprvn.html

JS:   await fetch(url)
来源：http://dali.quarkkingdee.top/Article/details/gtjtqzxhbc.html

TS:   await fetch(url)
来源：http://dali.xylfe.cn/Article/details/gttogcvtga.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.haohaochexian.top/Article/details/gtetkzcmpf.html

Go:   resp, err := http.Get(url)
来源：http://dali.kuanghao11.cn/Article/details/gtynxrygjl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj20258.top/Article/details/gtuewqrdto.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shzxlz.cn/Article/details/gtobcplczq.html

[L02] 发送 POST JSON
来源：http://dali.fzhhl.top/Article/details/gtgmuwcmsk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqspopjby.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hammf.cn/Article/details/gtdkntpsyz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cheryme.top/Article/details/gtynnahxff.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnqzz.top/Article/details/gtvfgnvuuk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrnrkwamd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj202588.top/Article/details/gttamulpoi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jianghu66.top/Article/details/gtjrzkbray.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.vqdsnc.cn/Article/details/gtjsdsmyhv.html

[L03] 设置自定义请求头
来源：http://dali.zhoulong.xyz/Article/details/gtirjltxph.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.vqdsnc.cn/Article/details/gtspgqsteo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj202588.top/Article/details/gtudtgjtrn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gtpvfwnaao.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tian-w.cn/Article/details/gtdkhrpfzu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.mhx1999.top/Article/details/gtpsckxwwn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ivvv.top/Article/details/gtgrkfkous.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj202588.top/Article/details/gtoipdldvj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gtzjhktcmq.html

[L04] 设置超时
来源：http://dali.yueranfly.top/Article/details/gtipbkvzdi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cashguo.top/Article/details/gtrayurbkl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.pycfn.com/Article/details/gtakupkpqb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.haohaochexian.top/Article/details/gttywzhiyw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cheryme.top/Article/details/gtkuyokcbv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvhwwcaly.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dashuyun.cn/Article/details/gtlkxzrctc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenzaomai.com/Article/details/gtujqxlpnj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnqzz.top/Article/details/gtzuizzkny.html

[L05] 上传文件（multipart）
来源：http://dali.zhengqikj.top/Article/details/gtrhzzzlkb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jqgufenzy.top/Article/details/gtzgkytwaw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenlongwang.top/Article/details/gtzjcnghgn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cdnleiting.top/Article/details/gteiqvmudm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gtgkoebxzm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ywan-chungtsiang.top/Article/details/gttpueysaj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ehwqpu.com/Article/details/gtypgeilqz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daria6918.cn/Article/details/gtitwbbwzr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tian-w.cn/Article/details/gtwwimkzfa.html

[L06] 解析响应为 JSON
来源：http://dali.guannengcc.top/Article/details/gtucdvpqal.html

Py:   resp.json()
来源：http://dali.ivvv.top/Article/details/gtogkdctpc.html

PHP:  json_decode($body, true);
来源：http://dali.jlsjyb.cn/Article/details/gtvvuhuhsn.html

JS:   await resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gtpzatmnho.html

TS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfmmmgom.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sweek.top/Article/details/gtxtcvkijt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhengqikj.top/Article/details/gtsenajjns.html

Ruby: JSON.parse(resp.body)
来源：http://dali.snrcjt.cn/Article/details/gtfzbytesw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xinyue.icu/Article/details/gtozinbiro.html

[L07] 处理 HTTP 状态码
来源：http://dali.shangyingyoupin.top/Article/details/gtedxdmjyb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gaohongyu789.top/Article/details/gtbhvcqlgg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fzhhl.top/Article/details/gtjyngihfu.html

JS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gtkhuemfdf.html

TS:   resp.ok;  resp.status
来源：http://dali.xinyue.icu/Article/details/gtyadxndao.html

Java: resp.statusCode()
来源：http://dali.haohaochexian.top/Article/details/gttwxpxrfe.html

Go:   resp.StatusCode
来源：http://dali.yangfankeji.com/Article/details/gtegmuppbq.html

Ruby: resp.code.to_i
来源：http://dali.nwbrower.top/Article/details/gtrdxtztsy.html

C#:   (int)resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gtyqfcvtjk.html

[L08] 并发请求多个地址
来源：http://dali.nanxinkj.top/Article/details/gtbdudtsnq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yangfankeji.com/Article/details/gtqoopodlp.html

PHP:  curl_multi_init() 系列
来源：http://dali.tianlin.xyz/Article/details/gtapiekklz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aibaodan.cn/Article/details/gtcfvmmzfm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gtbvwruale.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ehwqpu.com/Article/details/gtgivlcgbz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.dashuyun.cn/Article/details/gtsbbnmsie.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dashuyun.cn/Article/details/gtbhqspfce.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yuxming.cn/Article/details/gtdtwrxtzr.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtjorwlrta.html

M. 命令行 / 进程 / 环境
来源：http://dali.yongpay.top/Article/details/gtrzmoauyb.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtbstfgmwt.html

[M01] 读取命令行参数
来源：http://dali.hammf.cn/Article/details/gtofjvevqz.html

Py:   sys.argv[1:]
来源：http://dali.tianlin.xyz/Article/details/gtdgjminyc.html

PHP:  $argv;  $argc;
来源：http://dali.gotoacloud.top/Article/details/gtktaoxcvc.html

JS:   process.argv.slice(2)
来源：http://dali.cqqwz.cn/Article/details/gtpjyrwkby.html

TS:   process.argv.slice(2)
来源：http://dali.svipenyu.cn/Article/details/gtjdtnpztd.html

Java: args 数组（main 方法参数）
来源：http://dali.316326.xyz/Article/details/gtcaivykqx.html

Go:   os.Args[1:]
来源：http://dali.chenlongwang.top/Article/details/gtfuxelrtt.html

Ruby: ARGV
来源：http://dali.zhengqikj.top/Article/details/gthuvbfhvn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenjidiqi.icu/Article/details/gtwcfezrjs.html

[M02] 读取环境变量
来源：http://dali.ehwqpu.com/Article/details/gtiyoaeopt.html

Py:   os.environ.get("HOME")
来源：http://dali.ydzc1.top/Article/details/gtxabvfhzf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cqqwz.cn/Article/details/gtodkgxsig.html

JS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gtradjictp.html

TS:   process.env.HOME
来源：http://dali.cqqwz.cn/Article/details/gtseoclvfc.html

Java: System.getenv("HOME")
来源：http://dali.yuxming.cn/Article/details/gtvykmokyg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.redwolf501.top/Article/details/gtygajvctu.html

Ruby: ENV["HOME"]
来源：http://dali.gzhubu.top/Article/details/gtfpllsjtk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtyrzvlxmx.html

[M03] 执行外部命令
来源：http://dali.andypj.xyz/Article/details/gtpqdhhtht.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yonumen.top/Article/details/gtezfhvxbm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258.top/Article/details/gtjrwdwphp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gtjyjrwrls.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258888.top/Article/details/gtqewksehh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.guannengcc.top/Article/details/gtetklvjvr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkvshocvf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cdnleiting.top/Article/details/gtjktivmqd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nanxuanxn.top/Article/details/gtgbsivdar.html

[M04] 获取当前工作目录
来源：http://dali.sweek.top/Article/details/gtwijscakk.html

Py:   os.getcwd()
来源：http://dali.nwbrower.top/Article/details/gttsgwqvmn.html

PHP:  getcwd();
来源：http://dali.guowangkeji.top/Article/details/gtqvgbvlhr.html

JS:   process.cwd()
来源：http://dali.zhengqikj.top/Article/details/gtbmipssyj.html

TS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gtamdkeilj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj202588.top/Article/details/gtzhsyoadg.html

Go:   os.Getwd()
来源：http://dali.9152youxi.cn/Article/details/gtpdxptmfc.html

Ruby: Dir.pwd
来源：http://dali.zhixingplan.top/Article/details/gtckjixhky.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shzxlz.cn/Article/details/gtbpbvfsza.html

[M05] 设置退出码
来源：http://dali.jinghuilouyu.cn/Article/details/gtonydkzqy.html

Py:   sys.exit(1)
来源：http://dali.daxiang520.top/Article/details/gtwpdyompi.html

PHP:  exit(1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtczowzpby.html

JS:   process.exit(1)
来源：http://dali.hammf.cn/Article/details/gtynsicjbs.html

TS:   process.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtlowtuxqe.html

Java: System.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtsnytfcle.html

Go:   os.Exit(1)
来源：http://dali.tanke756.top/Article/details/gtdzesuroc.html

Ruby: exit 1
来源：http://dali.0kj1m.cn/Article/details/gtlmljliue.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.guowangkeji.top/Article/details/gtdotnbpqx.html

[M06] 向标准错误输出
来源：http://dali.sweek.top/Article/details/gtaxeshlsk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shuidangran.top/Article/details/gtnwqdmidh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sxryk.cn/Article/details/gttxnalphc.html

JS:   console.error("err")
来源：http://dali.wangshuangyany.cn/Article/details/gtonaddkls.html

TS:   console.error("err")
来源：http://dali.mhx1999.top/Article/details/gthfeieiyt.html

Java: System.err.println("err")
来源：http://dali.jiagoushi.top/Article/details/gtrozavvyz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nanxuanxn.top/Article/details/gtwiqewlnv.html

Ruby: warn "err"
来源：http://dali.dianchejie.cn/Article/details/gtqymzcjqd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ydzc1.top/Article/details/gtclmjsiby.html

[M07] 判断是否为主入口
来源：http://dali.ehwqpu.com/Article/details/gtmrwbvqiv.html

Py:   if __name__ == "__main__":
来源：http://dali.cucudq.cn/Article/details/gtfvsjpzzj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cdnleiting.top/Article/details/gtfulpbfrp.html

JS:   require.main === module
来源：http://dali.sysykeji.top/Article/details/gtuwcrsdgq.html

TS:   require.main === module
来源：http://dali.jinqigufen.top/Article/details/gtesjixtit.html

Java: public static void main(String[] args)
来源：http://dali.iojbl.cn/Article/details/gtonygiovz.html

Go:   func main()
来源：http://dali.chenlongwang.top/Article/details/gtryjzuorf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cheryme.top/Article/details/gtcdmtcfae.html

C#:   static void Main(string[] args)
来源：http://dali.nanxuanxn.top/Article/details/gthasmnwzx.html

[M08] 获取系统与运行时信息
来源：http://dali.yonumen.top/Article/details/gtetoluody.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yuxming.cn/Article/details/gtmzwtpdqt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinyuanbaomall.cn/Article/details/gteymgwsdq.html

JS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gtefttllph.html

TS:   process.platform;  process.version
来源：http://dali.316326.xyz/Article/details/gtyzojgpbi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dashuyun.cn/Article/details/gtqtwxxqbn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gotoacloud.top/Article/details/gtolosakip.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.birdmap.top/Article/details/gtekyoebtn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqyuzrqcd.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtydawedmp.html

N. 数据结构与算法
来源：http://dali.hongshengwenyu.top/Article/details/gtzkyksbux.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtfsueocsw.html

[N01] 二分查找（有序数组）
来源：http://dali.tianlin.xyz/Article/details/gtdcdnapcm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.havefunace.top/Article/details/gtgmsvraws.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ivvv.top/Article/details/gtlrisevne.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfyfsmov.html


<!-- 参考信息 -->