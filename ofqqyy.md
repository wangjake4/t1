代发 wailian999

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nanxinkj.top/Article/details/gtcdsstfpg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ydzc1.top/Article/details/gtvfwpwvxz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.smart0.xyz/Article/details/gtrmqtvbav.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yuanzhike.top/Article/details/gtjpomjjxo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jiagoushi.top/Article/details/gtmwrmsbkt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zdqjudy.top/Article/details/gtmhkbaujb.html

[J05] 时间加减（加 7 天）
来源：http://dali.andypj.xyz/Article/details/gtjgjousdb.html

Py:   now + timedelta(days=7)
来源：http://dali.zhijiandao.cn/Article/details/gtvloxevye.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj202588.top/Article/details/gttoqyfajr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jlsjyb.cn/Article/details/gtsliubfsz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gtphbpotwy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhengqikj.top/Article/details/gtrsjdmauh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxuanxn.top/Article/details/gthwaybrpn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.birdmap.top/Article/details/gtgkvgytwz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.mhx1999.top/Article/details/gtzeyusqhq.html

[J06] 计算两时间之差
来源：http://dali.jinghuilouyu.cn/Article/details/gtieczamyb.html

Py:   (end - start).total_seconds()
来源：http://dali.pengpengdd.cyou/Article/details/gtwpckzarb.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhengqikj.top/Article/details/gtooauybtu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.guannengcc.top/Article/details/gtvfxkxkpw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gzhubu.top/Article/details/gtyuemebvx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.mhx1999.top/Article/details/gtoshzhtem.html

Go:   end.Sub(start).Hours()
来源：http://dali.c1oappe.top/Article/details/gtsaurkgmq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yongpay.top/Article/details/gtyrgsuods.html

C#:   (end - start).TotalSeconds
来源：http://dali.hongshengwenyu.top/Article/details/gtimjjoger.html

[J07] 比较两个日期
来源：http://dali.wangdashe.top/Article/details/gtdtllyewg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gtofnnzoyu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.dianchejie.cn/Article/details/gttorxyipp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gttofbjytd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gtwenijoww.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xinyue.icu/Article/details/gtuqietjdt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hfpthk.cn/Article/details/gtnxekeksg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gtgctstlby.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gtclrwtgmb.html

[J08] 提取年月日与星期
来源：http://dali.chenjidiqi.icu/Article/details/gtupaoofme.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.dashuyun.cn/Article/details/gtsdaobewk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.316326.xyz/Article/details/gtxhlozzeh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yangfankeji.com/Article/details/gtjnugecni.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvschqgna.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.smart0.xyz/Article/details/gtlnltetuk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yanxiufei.cn/Article/details/gtgbbbbggs.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj20258888.top/Article/details/gtdwqjqugo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xziqi.cn/Article/details/gtkslsvthy.html

[J09] 时区处理
来源：http://dali.hfpthk.cn/Article/details/gtdkkdrdol.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.wangshuangyany.cn/Article/details/gtyxewpnpg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hammf.cn/Article/details/gtsirabhrf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yangfankeji.com/Article/details/gtezftnpet.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gtalqhwxxe.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpptxfwew.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gotoacloud.top/Article/details/gtafidfolr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj202588.top/Article/details/gtrwdzkyoc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jqgufenzy.top/Article/details/gtnexfmrlj.html

[J10] 取今天 / 本月第一天
来源：http://dali.ppjwa.cn/Article/details/gtahjsdwqs.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.pycfn.com/Article/details/gthahacqst.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.andypj.xyz/Article/details/gtkctjlzyk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aizwys.cn/Article/details/gtytvmoqmf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jianghu66.top/Article/details/gtnygyajnq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dianchejie.cn/Article/details/gtwkqerdnw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcyakxwsd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cdnleiting.top/Article/details/gtuyrwlpym.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hammf.cn/Article/details/gticyfabxi.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtsicgghki.html

K. JSON 与序列化
来源：http://dali.svipenyu.cn/Article/details/gtmtxeoqdy.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtpcqzcvxs.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtjtdbajxt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.haohaochexian.top/Article/details/gtvxqmjbce.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gtzqfayivg.html

JS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gturbnqsae.html

TS:   JSON.stringify(obj)
来源：http://dali.hywenlv.cn/Article/details/gtaffyocsa.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tian-w.cn/Article/details/gtegvoapoa.html

Go:   json.Marshal(obj)
来源：http://dali.chenzaomai.com/Article/details/gtedxfkycv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xziqi.cn/Article/details/gtvjygxozt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yangfankeji.com/Article/details/gtecntayyg.html

[K02] JSON 字符串转对象
来源：http://dali.wangdashe.top/Article/details/gtfakwqhaw.html

Py:   json.loads(s)
来源：http://dali.cqqwz.cn/Article/details/gtrrijyjwg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ehwqpu.com/Article/details/gtswavvwvb.html

JS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gtxbrlzvkv.html

TS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gtyvymftgl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.316326.xyz/Article/details/gtavbhnclp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.pengpengdd.cyou/Article/details/gthfnpmmlf.html

Ruby: JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gtehmqjjht.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.iojbl.cn/Article/details/gtnzggqzcg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gaohongyu789.top/Article/details/gtqxlcqyml.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gtuadljufx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yangfankeji.com/Article/details/gtokhddkqy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gtrkswdphu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yangfankeji.com/Article/details/gtghqdgzbq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtbtrqgjwt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hfpthk.cn/Article/details/gtjjxwlenb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtllotocfk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gtmlvmqtlf.html

[K04] 读取 JSON 文件
来源：http://dali.aizwys.cn/Article/details/gtswkypkdr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenlongwang.top/Article/details/gtvkzvlonj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.svipenyu.cn/Article/details/gtnzxngtdg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yonumen.top/Article/details/gtmppllnza.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gthtpelhdg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hywenlv.cn/Article/details/gtiwzvjkqn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenzaomai.com/Article/details/gtgjcomvkj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gtuikjauow.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xinyue.icu/Article/details/gtgypxlbhf.html

[K05] 深拷贝对象
来源：http://dali.hongshengwenyu.top/Article/details/gthmvwnoit.html

Py:   copy.deepcopy(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtleswhpyw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.quarkkingdee.top/Article/details/gtnyyoeudt.html

JS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gtwcmmdlwu.html

TS:   structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gtfqxnkgau.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hfpthk.cn/Article/details/gtopzfvfig.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jianghu66.top/Article/details/gtvoawshzi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tanke756.top/Article/details/gtjlrrqwhd.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhixingplan.top/Article/details/gtvpegupwg.html

[K06] 解析 URL 查询串
来源：http://dali.shuidangran.top/Article/details/gtklbrrqic.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tianlin.xyz/Article/details/gttuyefwji.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cdnleiting.top/Article/details/gteathhaij.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhmpenpv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gotoacloud.top/Article/details/gtqaabwebz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ppjwa.cn/Article/details/gttusayiti.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gtplhaczzz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvsuuhrn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdbukswvu.html

[K07] 进制转换
来源：http://dali.zhixingplan.top/Article/details/gthpwnwgpc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtggovtyhi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnqzz.top/Article/details/gtjjfiwgih.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtcxkhgyue.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtqesqdanq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtjiseyceu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.meibo888.top/Article/details/gtiitpsnbv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhiwuduotai.top/Article/details/gtgzkyoilf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtilapyaag.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.daria6918.cn/Article/details/gteitwijfx.html

Py:   pickle.dumps(obj)
来源：http://dali.cucudq.cn/Article/details/gtpdryhbpz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nwbrower.top/Article/details/gtudmtotqm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gzhubu.top/Article/details/gtxxecomyk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ivvv.top/Article/details/gtntkqmdzj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jlsjyb.cn/Article/details/gtskpupole.html

Go:   encoding/gob
来源：http://dali.hnqzz.top/Article/details/gtrtlfktzy.html

Ruby: Marshal.dump(obj)
来源：http://dali.gogol.net.cn/Article/details/gtuaxpbvxp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xuanzx.com/Article/details/gtcmgahmga.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtuyigfxku.html

L. 网络请求
来源：http://dali.gotoacloud.top/Article/details/gtywbtdugk.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtmkrljfmm.html

[L01] 发送 GET 请求
来源：http://dali.yj20258.top/Article/details/gtogckrspy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yuxming.cn/Article/details/gtyaaodvty.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.guowangkeji.top/Article/details/gtuqixyajn.html

JS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gtmdldfxbp.html

TS:   await fetch(url)
来源：http://dali.yuxming.cn/Article/details/gtgqiijslx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ybcxt.top/Article/details/gtymyoiuks.html

Go:   resp, err := http.Get(url)
来源：http://dali.kuanghao11.cn/Article/details/gtsgnzeqhv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cucudq.cn/Article/details/gtottqpgsx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zycfv.cn/Article/details/gtoezjtifi.html

[L02] 发送 POST JSON
来源：http://dali.yj20258888.top/Article/details/gtjgdusscu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.9152youxi.cn/Article/details/gtpgqcxxnl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sxryk.cn/Article/details/gtoechtqeq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gtnzmxtzot.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gtoiildvfe.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nanxuanxn.top/Article/details/gtyjoznhog.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jqgfzy.top/Article/details/gtngrdccjn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.smart0.xyz/Article/details/gtxxbfvzgm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfrqkskbd.html

[L03] 设置自定义请求头
来源：http://dali.sxryk.cn/Article/details/gtqtqdedwk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zdqjudy.top/Article/details/gtsyhsoakd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj20258888.top/Article/details/gtrmylrnci.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hysaishi.cn/Article/details/gtacbumbit.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhoulong.xyz/Article/details/gtlqdjmzzj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tianlin.xyz/Article/details/gtjxwutcxc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.birdmap.top/Article/details/gthhkekejx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.wangshuangyany.cn/Article/details/gtifkkxlfa.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xuanzx.com/Article/details/gtvckooxfc.html

[L04] 设置超时
来源：http://dali.redwolf501.top/Article/details/gtqrahjnre.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zdqjudy.top/Article/details/gtfmjjqztw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbsfhmkc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gotoacloud.top/Article/details/gtjdlonrdx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cqqwz.cn/Article/details/gtmpewiifk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtplzlqmpg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cucudq.cn/Article/details/gttdqlcevs.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvtfmeko.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sweek.top/Article/details/gtrteracwp.html

[L05] 上传文件（multipart）
来源：http://dali.xuanzx.com/Article/details/gtaepljkad.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shanyushiyangtech.top/Article/details/gtfrkxmhjv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gtlmksfxna.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gotoacloud.top/Article/details/gtcmpvfspz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jyoumei.cn/Article/details/gtoqmzrkmp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhiwuduotai.top/Article/details/gtemsehxya.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwqbnufa.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xuetiantiany.cn/Article/details/gtsivxctzo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtmixkrfle.html

[L06] 解析响应为 JSON
来源：http://dali.9152youxi.cn/Article/details/gtjbpqdsek.html

Py:   resp.json()
来源：http://dali.dashuyun.cn/Article/details/gtouvkjnkk.html

PHP:  json_decode($body, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtulbadotz.html

JS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gtlltfuamm.html

TS:   await resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gtqfzghiow.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zycfv.cn/Article/details/gtpsbazqbc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.dianchejie.cn/Article/details/gtuzbvmlea.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenzaomai.com/Article/details/gtjpzqoejs.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ppjwa.cn/Article/details/gtgynwnftr.html

[L07] 处理 HTTP 状态码
来源：http://dali.xinyue.icu/Article/details/gtsbrdlxta.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hfpthk.cn/Article/details/gtgfueqjar.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtunyyzfcz.html

JS:   resp.ok;  resp.status
来源：http://dali.xziqi.cn/Article/details/gtnduxuzop.html

TS:   resp.ok;  resp.status
来源：http://dali.hysaishi.cn/Article/details/gtaknewhlb.html

Java: resp.statusCode()
来源：http://dali.redwolf501.top/Article/details/gtbmpxtpqt.html

Go:   resp.StatusCode
来源：http://dali.sysykeji.top/Article/details/gtbffhznbh.html

Ruby: resp.code.to_i
来源：http://dali.guannengcc.top/Article/details/gtfvpubyuq.html

C#:   (int)resp.StatusCode
来源：http://dali.yongpay.top/Article/details/gtjosvdzmp.html

[L08] 并发请求多个地址
来源：http://dali.zhoulong.xyz/Article/details/gtqypvftoj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj20258888.top/Article/details/gtdablhokq.html

PHP:  curl_multi_init() 系列
来源：http://dali.quarkkingdee.top/Article/details/gtjisihyql.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmgwkfjyr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gtmsyvgfai.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hysaishi.cn/Article/details/gtugmcozhy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zdqjudy.top/Article/details/gthotmahmv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj20258888.top/Article/details/gtuntyahef.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtsjiuarge.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtvqyichxr.html

M. 命令行 / 进程 / 环境
来源：http://dali.316326.xyz/Article/details/gtawmqurjg.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtaayrpfka.html

[M01] 读取命令行参数
来源：http://dali.meibo888.top/Article/details/gtdthbaitw.html

Py:   sys.argv[1:]
来源：http://dali.yonumen.top/Article/details/gthwhstnxl.html

PHP:  $argv;  $argc;
来源：http://dali.9152youxi.cn/Article/details/gtmoshirfv.html

JS:   process.argv.slice(2)
来源：http://dali.cashguo.top/Article/details/gtrtqabnnh.html

TS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gtglzgtrpa.html

Java: args 数组（main 方法参数）
来源：http://dali.xinyue.icu/Article/details/gtjwxuvwwr.html

Go:   os.Args[1:]
来源：http://dali.kuanghao11.cn/Article/details/gtscpzeesz.html

Ruby: ARGV
来源：http://dali.chenjidiqi.icu/Article/details/gtblsqiblp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gtwzozfnmp.html

[M02] 读取环境变量
来源：http://dali.svipenyu.cn/Article/details/gtkjwtkgon.html

Py:   os.environ.get("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtfhiebzug.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.birdmap.top/Article/details/gtvvuzgacb.html

JS:   process.env.HOME
来源：http://dali.shuidangran.top/Article/details/gtdrctlzry.html

TS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gthlrwqtzm.html

Java: System.getenv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtcrscphyo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.meibo888.top/Article/details/gttstwghgn.html

Ruby: ENV["HOME"]
来源：http://dali.zhixingplan.top/Article/details/gtxdzooeqk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtulviaihi.html

[M03] 执行外部命令
来源：http://dali.shuidangran.top/Article/details/gtuylbwtqw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cdnleiting.top/Article/details/gttpokiumn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.meibo888.top/Article/details/gtulimkwiz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.smart0.xyz/Article/details/gtwkjnwayp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gtlfjosubj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yongpay.top/Article/details/gtxijjrcut.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tian-w.cn/Article/details/gtjumjtczz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.feifeiyinyue.top/Article/details/gtxoyexemj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.c1oappe.top/Article/details/gtujznxtgx.html

[M04] 获取当前工作目录
来源：http://dali.ybcxt.top/Article/details/gtexndxerm.html

Py:   os.getcwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfeyunmpf.html

PHP:  getcwd();
来源：http://dali.zhixingplan.top/Article/details/gttdikwwyh.html

JS:   process.cwd()
来源：http://dali.yj20258.top/Article/details/gtfpxjnywa.html

TS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gtrqculxoa.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jyoumei.cn/Article/details/gteeizkprt.html

Go:   os.Getwd()
来源：http://dali.hammf.cn/Article/details/gtgaldbruj.html

Ruby: Dir.pwd
来源：http://dali.dianchejie.cn/Article/details/gtszftkrvz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.birdmap.top/Article/details/gtfurlhtno.html

[M05] 设置退出码
来源：http://dali.ivvv.top/Article/details/gtrzynqshr.html

Py:   sys.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtfpkhjwxz.html

PHP:  exit(1);
来源：http://dali.ivvv.top/Article/details/gtreyooacp.html

JS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtseyhmucf.html

TS:   process.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtyoruxpmi.html

Java: System.exit(1)
来源：http://dali.yj20258.top/Article/details/gtylmaetvh.html

Go:   os.Exit(1)
来源：http://dali.bjfxy.top/Article/details/gthwzorcog.html

Ruby: exit 1
来源：http://dali.hfpthk.cn/Article/details/gttcyfmlts.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.snrcjt.cn/Article/details/gtnkpjofvd.html

[M06] 向标准错误输出
来源：http://dali.guowangkeji.top/Article/details/gtbktytbsn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgufenzy.top/Article/details/gtjrsvxwoa.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gogol.net.cn/Article/details/gttcoyikzt.html

JS:   console.error("err")
来源：http://dali.haohaochexian.top/Article/details/gtmkmgdmyw.html

TS:   console.error("err")
来源：http://dali.zycfv.cn/Article/details/gtzdjbsfxj.html

Java: System.err.println("err")
来源：http://dali.xylfe.cn/Article/details/gtsihessmz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.feifeiyinyue.top/Article/details/gtechewybm.html

Ruby: warn "err"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrevmkzaq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhongyouzk.top/Article/details/gtotkipdkp.html

[M07] 判断是否为主入口
来源：http://dali.yongpay.top/Article/details/gtmqmekamy.html

Py:   if __name__ == "__main__":
来源：http://dali.yvedp.cn/Article/details/gtavwfpvbx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxinkj.top/Article/details/gtpukomqac.html

JS:   require.main === module
来源：http://dali.xuanzx.com/Article/details/gtuojqokun.html

TS:   require.main === module
来源：http://dali.haohaochexian.top/Article/details/gtnsgkgljl.html

Java: public static void main(String[] args)
来源：http://dali.redwolf501.top/Article/details/gtabokkjgs.html

Go:   func main()
来源：http://dali.zhixingplan.top/Article/details/gttgwcuaaz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.dashuyun.cn/Article/details/gtyifctdcf.html

C#:   static void Main(string[] args)
来源：http://dali.yj20258.top/Article/details/gtukdshzeu.html

[M08] 获取系统与运行时信息
来源：http://dali.meibo888.top/Article/details/gtafnwiomk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhoulong.xyz/Article/details/gtcwexvisc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xziqi.cn/Article/details/gtifdvtnfg.html

JS:   process.platform;  process.version
来源：http://dali.yj202588.top/Article/details/gtibwgwqbl.html

TS:   process.platform;  process.version
来源：http://dali.ydzc1.top/Article/details/gtpydxtpqc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shzxlz.cn/Article/details/gtxyodbdeg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.wangdashe.top/Article/details/gtzuajbxkr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj202588.top/Article/details/gtfctsmdau.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.chenjidiqi.icu/Article/details/gtzctzfqvv.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtzuojnjnh.html

N. 数据结构与算法
来源：http://dali.sufxvd.cn/Article/details/gtalxomyos.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtotcatolp.html

[N01] 二分查找（有序数组）
来源：http://dali.kuanghao11.cn/Article/details/gtfyobxstp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ivvv.top/Article/details/gtmbvsbpwd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.daria6918.cn/Article/details/gtduzfrlyd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cdnleiting.top/Article/details/gtbimgnkhv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sysykeji.top/Article/details/gttrqqjdvv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtnqceqbpm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtqbrtrvse.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hongshengwenyu.top/Article/details/gtryyytutg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtqilquyte.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.fzhhl.top/Article/details/gtjvztosqz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.redwolf501.top/Article/details/gtekzmpcba.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shuidangran.top/Article/details/gtycfjsgau.html


<!-- 参考信息 -->