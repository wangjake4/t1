代发 wailian999

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cqqwz.cn/Article/details/gtkzplxpvq.html

[J04] 时间戳与日期互转
来源：http://dali.bjfxy.top/Article/details/gtingdzuob.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yonumen.top/Article/details/gtinrcftne.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhongyouzk.top/Article/details/gtbpxbhlya.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sufxvd.cn/Article/details/gtrsuaogci.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cqqwz.cn/Article/details/gtzgaykacv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zycfv.cn/Article/details/gtopsejrgg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cheryme.top/Article/details/gtqlbeadlf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yuxming.cn/Article/details/gtjcuqmdww.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ivvv.top/Article/details/gtxevgjvdz.html

[J05] 时间加减（加 7 天）
来源：http://dali.aibaodan.cn/Article/details/gtycelwixa.html

Py:   now + timedelta(days=7)
来源：http://dali.iojbl.cn/Article/details/gtkjljpmtr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yuanzhike.top/Article/details/gtkjjddziz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gtjrnqegbx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gtpexqelcz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ydzc1.top/Article/details/gtxmyborcf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jqgufenzy.top/Article/details/gtjmktlsbo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gotoacloud.top/Article/details/gtmykubggq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jianghu66.top/Article/details/gtqribjwks.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangtech.top/Article/details/gtfskcppyi.html

Py:   (end - start).total_seconds()
来源：http://dali.cheryme.top/Article/details/gttuiwkuaw.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhixingplan.top/Article/details/gtxperoizq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yongpay.top/Article/details/gtsiyzdcng.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tianlin.xyz/Article/details/gtffwrimzc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.andypj.xyz/Article/details/gtlzuvqvzd.html

Go:   end.Sub(start).Hours()
来源：http://dali.sweek.top/Article/details/gtvdmbaude.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ybcxt.top/Article/details/gtnofntpjb.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhengqikj.top/Article/details/gtghtrrepv.html

[J07] 比较两个日期
来源：http://dali.feifeiyinyue.top/Article/details/gttcwhuvlo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gtffrgsjkk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhongyouzk.top/Article/details/gtovmqzcna.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.0kj1m.cn/Article/details/gtzdzokyyc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gtiybuhnup.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.c1oappe.top/Article/details/gtlbibcbnp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sweek.top/Article/details/gtaxmnadie.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gtcvwjobmv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gtnlrrumni.html

[J08] 提取年月日与星期
来源：http://dali.smart0.xyz/Article/details/gtmjzhxzdv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gogol.net.cn/Article/details/gtlxepmgqh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yanxiufei.cn/Article/details/gtpvxvzagf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuanzhike.top/Article/details/gtwelqcgae.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hnqzz.top/Article/details/gtvgxhzsid.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nanxinkj.top/Article/details/gtptoplhxn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hysaishi.cn/Article/details/gtgmypuijq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fengsongda.top/Article/details/gtwtmfageb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.kuanghao11.cn/Article/details/gtnthvmnbj.html

[J09] 时区处理
来源：http://dali.ybcxt.top/Article/details/gtwxvogwik.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hammf.cn/Article/details/gthfvqdbvh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.redwolf501.top/Article/details/gtaxugxfvr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gtixsjmzsl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cqqwz.cn/Article/details/gtfeqdtnyh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yongpay.top/Article/details/gtfljfqgke.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hammf.cn/Article/details/gtnrivhvpd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.fzhhl.top/Article/details/gtdneblumi.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yongpay.top/Article/details/gtmjdslgec.html

[J10] 取今天 / 本月第一天
来源：http://dali.tanke756.top/Article/details/gtwbpyknfz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.fengsongda.top/Article/details/gtrfkuowrm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.birdmap.top/Article/details/gtmpcdmrvw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxinkj.top/Article/details/gtfatympdh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ppjwa.cn/Article/details/gtqiyporhq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwyetatd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.feifeiyinyue.top/Article/details/gtbsrducsa.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cheryme.top/Article/details/gtuepozduo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shuidangran.top/Article/details/gtmjhghued.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gthffcvfza.html

K. JSON 与序列化
来源：http://dali.daxiang520.top/Article/details/gtzjeugfyw.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtpwxmoacj.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrjrgjre.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hysaishi.cn/Article/details/gtzcsazeqs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiurizmfo.html

JS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gtlqycwoic.html

TS:   JSON.stringify(obj)
来源：http://dali.aizwys.cn/Article/details/gtwjpaebjn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuanzx.com/Article/details/gtvakpzrou.html

Go:   json.Marshal(obj)
来源：http://dali.nwbrower.top/Article/details/gtaoknrroy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.birdmap.top/Article/details/gtypkxglih.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cqqwz.cn/Article/details/gtyxdnvzda.html

[K02] JSON 字符串转对象
来源：http://dali.snrcjt.cn/Article/details/gtrcscznfi.html

Py:   json.loads(s)
来源：http://dali.xylfe.cn/Article/details/gtalrfwhne.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigfzy.top/Article/details/gtzltsmwyc.html

JS:   JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gtvvpzsrel.html

TS:   JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gtpqfxtdfc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.aizwys.cn/Article/details/gtweeqgmth.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.smart0.xyz/Article/details/gtjagfmvwg.html

Ruby: JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtixtusbpo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnxiangtu.top/Article/details/gtobyjleuu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenlongwang.top/Article/details/gtlsvyatjp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.wangshuangyany.cn/Article/details/gtdlfmmlyp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.guowangkeji.top/Article/details/gtpgksccvy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tian-w.cn/Article/details/gtqaiaaxgj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fzhhl.top/Article/details/gtbsxrpztu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ppjwa.cn/Article/details/gtniiditzj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gtasxydhig.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhixingplan.top/Article/details/gtyhslefmf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tian-w.cn/Article/details/gtdryznelf.html

[K04] 读取 JSON 文件
来源：http://dali.gotoacloud.top/Article/details/gtdwcakzhe.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sweek.top/Article/details/gtpdcgeije.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yongpay.top/Article/details/gtihxzouay.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ivvv.top/Article/details/gtvgtiepqb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gtfeouacab.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.meibo888.top/Article/details/gtrmrwoice.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tianlin.xyz/Article/details/gtxyxodiib.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sxryk.cn/Article/details/gtqoxltckg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.guannengcc.top/Article/details/gtzqnssbky.html

[K05] 深拷贝对象
来源：http://dali.hywenlv.cn/Article/details/gtwvcnmmjk.html

Py:   copy.deepcopy(obj)
来源：http://dali.daria6918.cn/Article/details/gtyanioesl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yueranfly.top/Article/details/gtyisrtwyr.html

JS:   structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwsewbyge.html

TS:   structuredClone(obj)
来源：http://dali.cheryme.top/Article/details/gtsqnutuug.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigfzy.top/Article/details/gtulmshqit.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.c1oappe.top/Article/details/gtzmrjlaor.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinqigfzy.top/Article/details/gtxtoqrisv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.smart0.xyz/Article/details/gtcirkphit.html

[K06] 解析 URL 查询串
来源：http://dali.daxiang520.top/Article/details/gtnsginjvw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shangyingyoupin.top/Article/details/gtdituirie.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.birdmap.top/Article/details/gtjafaqqrx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gzhubu.top/Article/details/gtfzrklcsg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yonumen.top/Article/details/gtdqwaukwd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgfzy.top/Article/details/gttsrnfxne.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gttujgvfhz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gtkhmwgaer.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gtgxgneqlj.html

[K07] 进制转换
来源：http://dali.jinqigfzy.top/Article/details/gtsxgutyil.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtfdoxnvda.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.aibaodan.cn/Article/details/gtzcbhiezg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtwopnnthw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtuiqhdnbu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtfnyblfos.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shangyingyoupin.top/Article/details/gtkbbzilpp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jyoumei.cn/Article/details/gtzutcstgz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtajffypux.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shanyushiyangtech.top/Article/details/gtkraiqdjw.html

Py:   pickle.dumps(obj)
来源：http://dali.hnqzz.top/Article/details/gtqrrsqqdm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xylfe.cn/Article/details/gtmguqwtxh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.kuanghao11.cn/Article/details/gtiftwmjpb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gtgacjrxvw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.meibo888.top/Article/details/gtpxlxlkpn.html

Go:   encoding/gob
来源：http://dali.xuetiantiany.cn/Article/details/gtqgfcyxzs.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenzaomai.com/Article/details/gtpbuecziu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gtlemsbgdd.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtfwxgquvw.html

L. 网络请求
来源：http://dali.cheryme.top/Article/details/gtjkxqmlax.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcsezcmxu.html

[L01] 发送 GET 请求
来源：http://dali.zhoulong.xyz/Article/details/gtkugqzjnh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.birdmap.top/Article/details/gtlecuxfaz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvrmalwj.html

JS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gthctfonbf.html

TS:   await fetch(url)
来源：http://dali.daxiang520.top/Article/details/gtxflecrny.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sweek.top/Article/details/gtipzitypf.html

Go:   resp, err := http.Get(url)
来源：http://dali.ppjwa.cn/Article/details/gtrbgcxmys.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jiagoushi.top/Article/details/gtvltkdhbm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.aibaodan.cn/Article/details/gtotxosdgh.html

[L02] 发送 POST JSON
来源：http://dali.jlsjyb.cn/Article/details/gtguodqrce.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ivvv.top/Article/details/gteiwmeozf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sxryk.cn/Article/details/gtpvnreruf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pengpengdd.cyou/Article/details/gtivfnynjf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuetiantiany.cn/Article/details/gtgwkamhie.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ybcxt.top/Article/details/gtqbnnfbis.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hongshengwenyu.top/Article/details/gtbpplljtm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.redwolf501.top/Article/details/gtpzrsqwpi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.9152youxi.cn/Article/details/gtyfjpwkbe.html

[L03] 设置自定义请求头
来源：http://dali.hfpthk.cn/Article/details/gtwrwuijuz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhongyouzk.top/Article/details/gtaccalxct.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gthdwhlvwo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cdnleiting.top/Article/details/gtbmpimnvr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shzxlz.cn/Article/details/gtkilmcrbf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shuidangran.top/Article/details/gtvdlmzjzl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinghuilouyu.cn/Article/details/gthhrryijt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gzhubu.top/Article/details/gtqldaiczw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sxryk.cn/Article/details/gtcqalgklq.html

[L04] 设置超时
来源：http://dali.shangyingyoupin.top/Article/details/gtgmvfvfdg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.vqdsnc.cn/Article/details/gtlmamqqom.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.pengpengdd.cyou/Article/details/gtpianoxgu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jyoumei.cn/Article/details/gtzptayzjj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gtovivzyza.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hywenlv.cn/Article/details/gtmpawqoib.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gotoacloud.top/Article/details/gtptvlotxf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cdnleiting.top/Article/details/gtmvxjjeeu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenzaomai.com/Article/details/gtlnertlvj.html

[L05] 上传文件（multipart）
来源：http://dali.jinqigfzy.top/Article/details/gtlhvxijjr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.quarkkingdee.top/Article/details/gtbawmacch.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xziqi.cn/Article/details/gtsngehhkv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnqzz.top/Article/details/gtkkrqytkn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gtkygevyke.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenlongwang.top/Article/details/gtaqrzkyez.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.9152youxi.cn/Article/details/gtaxkybhqp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenzaomai.com/Article/details/gtuumehjjd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.aizwys.cn/Article/details/gtcerplpgp.html

[L06] 解析响应为 JSON
来源：http://dali.ybcxt.top/Article/details/gtqfcnicsp.html

Py:   resp.json()
来源：http://dali.chenzaomai.com/Article/details/gtixordwbn.html

PHP:  json_decode($body, true);
来源：http://dali.snrcjt.cn/Article/details/gtslvurusp.html

JS:   await resp.json()
来源：http://dali.jinqigufen.top/Article/details/gtsalugciz.html

TS:   await resp.json()
来源：http://dali.guowangkeji.top/Article/details/gtznpiwqxn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.pycfn.com/Article/details/gtsudlmejs.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj20258888.top/Article/details/gtsqljlgzi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.c1oappe.top/Article/details/gttcjhqxke.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ivvv.top/Article/details/gtjavmuunr.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gtvyhocwoy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.quarkkingdee.top/Article/details/gtpkhzbjqd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenlongwang.top/Article/details/gtvouybslw.html

JS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gtimyzhwsg.html

TS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gtkjbaqzuw.html

Java: resp.statusCode()
来源：http://dali.cdnleiting.top/Article/details/gtauifeffy.html

Go:   resp.StatusCode
来源：http://dali.gogol.net.cn/Article/details/gtrssekzbp.html

Ruby: resp.code.to_i
来源：http://dali.shanyushiyangtech.top/Article/details/gtsiiagvzd.html

C#:   (int)resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gtutzkssql.html

[L08] 并发请求多个地址
来源：http://dali.hysaishi.cn/Article/details/gtcthjaukx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinqigfzy.top/Article/details/gttpetkexm.html

PHP:  curl_multi_init() 系列
来源：http://dali.yuxming.cn/Article/details/gtxgkaxzyp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yongpay.top/Article/details/gtiledptna.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwepnztgq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nwbrower.top/Article/details/gtxfhtpvqn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nwbrower.top/Article/details/gtnihzlrov.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.haohaochexian.top/Article/details/gtfdthzhfw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cdnleiting.top/Article/details/gtlgxugppw.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtzzhmuzui.html

M. 命令行 / 进程 / 环境
来源：http://dali.cqqwz.cn/Article/details/gtbajnnfuk.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtqnnkkpej.html

[M01] 读取命令行参数
来源：http://dali.tian-w.cn/Article/details/gthlynzfhi.html

Py:   sys.argv[1:]
来源：http://dali.zhengqikj.top/Article/details/gtrjmxrmgh.html

PHP:  $argv;  $argc;
来源：http://dali.xuetiantiany.cn/Article/details/gtmfbzsewr.html

JS:   process.argv.slice(2)
来源：http://dali.hnqzz.top/Article/details/gtiopfdfwc.html

TS:   process.argv.slice(2)
来源：http://dali.tianlin.xyz/Article/details/gtrllwnmwn.html

Java: args 数组（main 方法参数）
来源：http://dali.cheryme.top/Article/details/gtvakwrdim.html

Go:   os.Args[1:]
来源：http://dali.nanxinkj.top/Article/details/gtybpycaaf.html

Ruby: ARGV
来源：http://dali.quarkkingdee.top/Article/details/gtrdupyffl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gtpigqajic.html

[M02] 读取环境变量
来源：http://dali.sufxvd.cn/Article/details/gthntlkuui.html

Py:   os.environ.get("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkqqabnlt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yuanzhike.top/Article/details/gtzpkjepop.html

JS:   process.env.HOME
来源：http://dali.shzxlz.cn/Article/details/gtncyxwdpo.html

TS:   process.env.HOME
来源：http://dali.sufxvd.cn/Article/details/gthxhnaajq.html

Java: System.getenv("HOME")
来源：http://dali.zdqjudy.top/Article/details/gtdenzpxhs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtxlaeqjsg.html

Ruby: ENV["HOME"]
来源：http://dali.cucudq.cn/Article/details/gtmujclzir.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.wangdashe.top/Article/details/gtrdyrmioe.html

[M03] 执行外部命令
来源：http://dali.zdqjudy.top/Article/details/gtzavnvglm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbjmmdovi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gogol.net.cn/Article/details/gtftqpdujx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sweek.top/Article/details/gtalmcaklu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gthcuqzjbj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hywenlv.cn/Article/details/gthyhrpudv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tian-w.cn/Article/details/gtpdhtilst.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tanke756.top/Article/details/gttfvinqrc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.redwolf501.top/Article/details/gtcnpvamhu.html

[M04] 获取当前工作目录
来源：http://dali.sysykeji.top/Article/details/gtrplhpugr.html

Py:   os.getcwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcrhextmy.html

PHP:  getcwd();
来源：http://dali.zycfv.cn/Article/details/gtdlprwfyp.html

JS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gtssgwaswr.html

TS:   process.cwd()
来源：http://dali.aizwys.cn/Article/details/gtyijmpitq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hywenlv.cn/Article/details/gtrouquvds.html

Go:   os.Getwd()
来源：http://dali.jinqigufen.top/Article/details/gtjwhgfqxq.html

Ruby: Dir.pwd
来源：http://dali.cheryme.top/Article/details/gtntiggono.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gotoacloud.top/Article/details/gtuysmkqnf.html

[M05] 设置退出码
来源：http://dali.smart0.xyz/Article/details/gtbpcbincg.html

Py:   sys.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gteetaraho.html

PHP:  exit(1);
来源：http://dali.kuanghao11.cn/Article/details/gtsvjrjcqq.html

JS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gtdphpxlod.html

TS:   process.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtmhduuwfs.html

Java: System.exit(1)
来源：http://dali.pycfn.com/Article/details/gtwjtwultm.html

Go:   os.Exit(1)
来源：http://dali.hammf.cn/Article/details/gtjtrdmgyy.html

Ruby: exit 1
来源：http://dali.yueranfly.top/Article/details/gtqdxfmdpr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sysykeji.top/Article/details/gtrjwpiunb.html

[M06] 向标准错误输出
来源：http://dali.c1oappe.top/Article/details/gtyfgepziv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangshuangyany.cn/Article/details/gtymhgixyn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.9152youxi.cn/Article/details/gtlmxeyhrl.html

JS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gtxyftgdnh.html

TS:   console.error("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtrqpzlqek.html

Java: System.err.println("err")
来源：http://dali.iojbl.cn/Article/details/gttprquxwr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jlsjyb.cn/Article/details/gtqpuvvubk.html

Ruby: warn "err"
来源：http://dali.snrcjt.cn/Article/details/gtoaxnxxzw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jiagoushi.top/Article/details/gtddbayszo.html

[M07] 判断是否为主入口
来源：http://dali.yj20258.top/Article/details/gtkvvkkmsc.html

Py:   if __name__ == "__main__":
来源：http://dali.chenlongwang.top/Article/details/gteddojrbv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zycfv.cn/Article/details/gtdofaywrn.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gtwnhximfk.html

TS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gtkreypgyg.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangtech.top/Article/details/gtktatdwqf.html

Go:   func main()
来源：http://dali.jinqigfzy.top/Article/details/gtozhqgjav.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hywenlv.cn/Article/details/gtgucmvuen.html

C#:   static void Main(string[] args)
来源：http://dali.nwbrower.top/Article/details/gtlaavjlsb.html

[M08] 获取系统与运行时信息
来源：http://dali.aibaodan.cn/Article/details/gtkkpkagel.html

Py:   platform.system();  platform.python_version()
来源：http://dali.smart0.xyz/Article/details/gtvnkmydhh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvdxcghg.html

JS:   process.platform;  process.version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaftxpoqv.html

TS:   process.platform;  process.version
来源：http://dali.jiagoushi.top/Article/details/gtxkmqqxsi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.bjfxy.top/Article/details/gtlwhkszys.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gtlqskyawp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhengqikj.top/Article/details/gtprvppldm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yueranfly.top/Article/details/gtcauezzjl.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtasrvfrdd.html

N. 数据结构与算法
来源：http://dali.xinyue.icu/Article/details/gtyaqazqlt.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbgkjklkm.html

[N01] 二分查找（有序数组）
来源：http://dali.zhongyouzk.top/Article/details/gtnkpjprjb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcrqrhqqp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tian-w.cn/Article/details/gtokynizjc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gtnznsrigo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.snrcjt.cn/Article/details/gtyircgpge.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtjmspippn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtdnehzzmx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.birdmap.top/Article/details/gtmblyjldc.html


<!-- 参考信息 -->