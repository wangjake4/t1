代发 wailian999

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jnsjzxfn.html

[J04] 时间戳与日期互转
来源：http://dali.chenjidiqi.icu/Article/details/gt2tgkggulb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pyirngzg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.9152youxi.cn/Article/details/gt2dbhrcewt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ehwqpu.com/Article/details/gt2uubcbgba.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.iojbl.cn/Article/details/gt2fkgtxmyn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ivvv.top/Article/details/gt2jiihcjmg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fzhhl.top/Article/details/gt2zosjiqke.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenzaomai.com/Article/details/gt2dknreoaz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.vqdsnc.cn/Article/details/gt2pfrhsugo.html

[J05] 时间加减（加 7 天）
来源：http://dali.snrcjt.cn/Article/details/gt2nndstnxg.html

Py:   now + timedelta(days=7)
来源：http://dali.yj20258888.top/Article/details/gt2xgkhjkoq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.redwolf501.top/Article/details/gt2hjeiyave.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.redwolf501.top/Article/details/gt2usgaajsi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gt2dfphqqwx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.daria6918.cn/Article/details/gt2cvzsbhmz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gaohongyu789.top/Article/details/gt2toytbpdr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenlongwang.top/Article/details/gt2uwrwlfao.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qhjcshwf.html

[J06] 计算两时间之差
来源：http://dali.zhiwuduotai.top/Article/details/gt2kfmolcfi.html

Py:   (end - start).total_seconds()
来源：http://dali.guannengcc.top/Article/details/gt2vuwegbcr.html

PHP:  $end->diff($start)->days;
来源：http://dali.pycfn.com/Article/details/gt2fqtlcrcz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shangyingyoupin.top/Article/details/gt2xpthyhrd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hnqzz.top/Article/details/gt2pwqzkabb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cashguo.top/Article/details/gt2bvzqroah.html

Go:   end.Sub(start).Hours()
来源：http://dali.shzxlz.cn/Article/details/gt2teemyngf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yanxiufei.cn/Article/details/gt2hvlmdpda.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxuanxn.top/Article/details/gt2xfkjimms.html

[J07] 比较两个日期
来源：http://dali.zhijiandao.cn/Article/details/gt2edkuqrzy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gt2tvqakwly.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinqigufen.top/Article/details/gt2xhmlfzkv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gt2knufxgln.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gt2ykvnqwow.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.svipenyu.cn/Article/details/gt2ogvwbdbe.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shzxlz.cn/Article/details/gt2fmfyhhqz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gt2vzejemze.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gt2tqaoruhy.html

[J08] 提取年月日与星期
来源：http://dali.snrcjt.cn/Article/details/gt2qrwyupoa.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.316326.xyz/Article/details/gt2oargydel.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.iojbl.cn/Article/details/gt2qddeache.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yueranfly.top/Article/details/gt2hnxyjayt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gpwoqbcb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jqgfzy.top/Article/details/gt2nncukbgx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mruymcsv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.0kj1m.cn/Article/details/gt2itqdbupm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.quarkkingdee.top/Article/details/gt2ujstukin.html

[J09] 时区处理
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jrsmvyas.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sysykeji.top/Article/details/gt2jlagrqlk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sufxvd.cn/Article/details/gt2rhtwplrf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnqzz.top/Article/details/gt2vbspybxj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cqqwz.cn/Article/details/gt2ygweusrw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tjlxvwoc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gzhubu.top/Article/details/gt2hzqytxnf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sxryk.cn/Article/details/gt2xlwrkwzj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yuanzhike.top/Article/details/gt2gaegmiyg.html

[J10] 取今天 / 本月第一天
来源：http://dali.pengpengdd.cyou/Article/details/gt2lgbeorsx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xziqi.cn/Article/details/gt2oohnilel.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tian-w.cn/Article/details/gt2hxohhqzf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.316326.xyz/Article/details/gt2avathnmj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sysykeji.top/Article/details/gt2ilmerdvf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nwbrower.top/Article/details/gt2gcknpmsj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jianghu66.top/Article/details/gt2cknqxeij.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuxming.cn/Article/details/gt2iivfaxad.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tian-w.cn/Article/details/gt2kvbwafpb.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2wfzbgkyj.html

K. JSON 与序列化
来源：http://dali.nwbrower.top/Article/details/gt2hxxribnn.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2mewxjtcc.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oyrahnfl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cashguo.top/Article/details/gt2dehsrdpy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhengqikj.top/Article/details/gt2esimfjlx.html

JS:   JSON.stringify(obj)
来源：http://dali.cheryme.top/Article/details/gt2fzlievdf.html

TS:   JSON.stringify(obj)
来源：http://dali.sysykeji.top/Article/details/gt2rudgwile.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hammf.cn/Article/details/gt2xswvrthc.html

Go:   json.Marshal(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2fcaryttg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.fengsongda.top/Article/details/gt2ilpkpirb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sweek.top/Article/details/gt2dzmojjsz.html

[K02] JSON 字符串转对象
来源：http://dali.xinyue.icu/Article/details/gt2wtvynhth.html

Py:   json.loads(s)
来源：http://dali.sufxvd.cn/Article/details/gt2ydjpjukc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yvedp.cn/Article/details/gt2typqtlom.html

JS:   JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gt2bfoafoqo.html

TS:   JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gt2hzozugfg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yonumen.top/Article/details/gt2ruomjzzg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gotoacloud.top/Article/details/gt2domdadia.html

Ruby: JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gt2hsmdubte.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yueranfly.top/Article/details/gt2lszcimxs.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nanxuanxn.top/Article/details/gt2nvguleoz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.haohaochexian.top/Article/details/gt2oyqglafk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhoulong.xyz/Article/details/gt2wdhafdey.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cucudq.cn/Article/details/gt2jbvlzyux.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gt2auviguvn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vqhqllvi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sufxvd.cn/Article/details/gt2oyryjzmt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hammf.cn/Article/details/gt2tixkzmcl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cdnleiting.top/Article/details/gt2ydopghme.html

[K04] 读取 JSON 文件
来源：http://dali.jiagoushi.top/Article/details/gt2oqobbntp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gogol.net.cn/Article/details/gt2qezosqes.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shzxlz.cn/Article/details/gt2athevakx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jaqwwuhj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ibmyhxhl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sufxvd.cn/Article/details/gt2xtvvqbja.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.fengsongda.top/Article/details/gt2arcdhfmb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhoulong.xyz/Article/details/gt2cavawfvy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gt2yaaouhur.html

[K05] 深拷贝对象
来源：http://dali.9152youxi.cn/Article/details/gt2ytcosacl.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj202588.top/Article/details/gt2xtrnihur.html

PHP:  unserialize(serialize($obj));
来源：http://dali.tian-w.cn/Article/details/gt2nqdqhjkh.html

JS:   structuredClone(obj)
来源：http://dali.mhx1999.top/Article/details/gt2jymaaibz.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2upmnaeba.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkcnfjg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.316326.xyz/Article/details/gt2tiinuqls.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shangyingyoupin.top/Article/details/gt2mvpuszoi.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhiwuduotai.top/Article/details/gt2wmiwsqta.html

[K06] 解析 URL 查询串
来源：http://dali.sufxvd.cn/Article/details/gt2iuryflim.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yangfankeji.com/Article/details/gt2cagytwuw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxuanxn.top/Article/details/gt2ymobdvrf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gt2bajuplop.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tuwdckle.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cbhbfbyb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gt2fbtitoar.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gt2wssuhxqy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gt2eiwljooa.html

[K07] 进制转换
来源：http://dali.fengsongda.top/Article/details/gt2nysabofa.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gt2cprpniul.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.pycfn.com/Article/details/gt2ufdnoptc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gt2dwjvpxwu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gt2prqiqwmf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wottktyu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj202588.top/Article/details/gt2ithigwvm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jqgfzy.top/Article/details/gt2nipwinde.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ghsqdcky.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shzxlz.cn/Article/details/gt2ogbaqsgv.html

Py:   pickle.dumps(obj)
来源：http://dali.tanke756.top/Article/details/gt2dsdxfbcl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hnqzz.top/Article/details/gt2rguhzxxl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qbawpsvz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gt2rejwucqx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yanxiufei.cn/Article/details/gt2tpnhgvbx.html

Go:   encoding/gob
来源：http://dali.yangfankeji.com/Article/details/gt2otkmysqy.html

Ruby: Marshal.dump(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2onwvnqkm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.birdmap.top/Article/details/gt2jlujopqe.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2ntuczudf.html

L. 网络请求
来源：http://dali.nanxinkj.top/Article/details/gt2ystgosxi.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2kbncnhgt.html

[L01] 发送 GET 请求
来源：http://dali.daria6918.cn/Article/details/gt2jkfpntuj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinqigfzy.top/Article/details/gt2mewoqawc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.9152youxi.cn/Article/details/gt2uslnwcvv.html

JS:   await fetch(url)
来源：http://dali.pengpengdd.cyou/Article/details/gt2yrxidkge.html

TS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gt2algfyuek.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xziqi.cn/Article/details/gt2cezknlra.html

Go:   resp, err := http.Get(url)
来源：http://dali.ppjwa.cn/Article/details/gt2nsqwdqfu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tmcbkjut.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj20258888.top/Article/details/gt2osvaxdpq.html

[L02] 发送 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gt2miwdfihy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hysaishi.cn/Article/details/gt2xgrxawww.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cheryme.top/Article/details/gt2eejzzrgj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gt2uhmsuosi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigfzy.top/Article/details/gt2glbyetrx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sysykeji.top/Article/details/gt2qkaqrbja.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ehwqpu.com/Article/details/gt2pgwqzgsi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.haohaochexian.top/Article/details/gt2agotmsqh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hfpthk.cn/Article/details/gt2vbiuakga.html

[L03] 设置自定义请求头
来源：http://dali.cheryme.top/Article/details/gt2mchebmgp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhiwuduotai.top/Article/details/gt2uqwvmoor.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ppjwa.cn/Article/details/gt2anppaxif.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pycfn.com/Article/details/gt2ydpkbppr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenjidiqi.icu/Article/details/gt2goztjpho.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.haohaochexian.top/Article/details/gt2xyrwrwkc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gt2zycbbxjw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wscdphiy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gt2pkagbcuf.html

[L04] 设置超时
来源：http://dali.9152youxi.cn/Article/details/gt2specsbic.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gzhubu.top/Article/details/gt2ahmrqlra.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jianghu66.top/Article/details/gt2ftwmubnj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zdqjudy.top/Article/details/gt2ptfgkcjk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gt2xckoguik.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hammf.cn/Article/details/gt2uckhbevv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hywenlv.cn/Article/details/gt2vwxnxmjq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yueranfly.top/Article/details/gt2yvisembo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guowangkeji.top/Article/details/gt2kgzkbqlb.html

[L05] 上传文件（multipart）
来源：http://dali.dianchejie.cn/Article/details/gt2ryqlutuw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhiwuduotai.top/Article/details/gt2hppsijmh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aqykmvda.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.daxiang520.top/Article/details/gt2vvomjlgr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.0kj1m.cn/Article/details/gt2svjvvryc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sweek.top/Article/details/gt2ppmwbdpf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhoulong.xyz/Article/details/gt2fjdgufhd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.redwolf501.top/Article/details/gt2tozkjitb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2zkcooprw.html

[L06] 解析响应为 JSON
来源：http://dali.jianghu66.top/Article/details/gt2bgudyofk.html

Py:   resp.json()
来源：http://dali.daria6918.cn/Article/details/gt2uidceeyt.html

PHP:  json_decode($body, true);
来源：http://dali.sufxvd.cn/Article/details/gt2yvlqggks.html

JS:   await resp.json()
来源：http://dali.0kj1m.cn/Article/details/gt2ostxbnex.html

TS:   await resp.json()
来源：http://dali.sxryk.cn/Article/details/gt2gktgjuev.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gt2arpyizoh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj20258.top/Article/details/gt2ygwloqsn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnqzz.top/Article/details/gt2apjrmnre.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.havefunace.top/Article/details/gt2jdtvrczl.html

[L07] 处理 HTTP 状态码
来源：http://dali.sxryk.cn/Article/details/gt2hxjtuqwc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hammf.cn/Article/details/gt2ijoayrbd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gaohongyu789.top/Article/details/gt2gdmunnub.html

JS:   resp.ok;  resp.status
来源：http://dali.sweek.top/Article/details/gt2hfjfacxp.html

TS:   resp.ok;  resp.status
来源：http://dali.yj20258888.top/Article/details/gt2vfdcgxdj.html

Java: resp.statusCode()
来源：http://dali.316326.xyz/Article/details/gt2aruzsgoc.html

Go:   resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yytscbsk.html

Ruby: resp.code.to_i
来源：http://dali.xziqi.cn/Article/details/gt2fmdjbkac.html

C#:   (int)resp.StatusCode
来源：http://dali.yangfankeji.com/Article/details/gt2zgcrhtre.html

[L08] 并发请求多个地址
来源：http://dali.sxryk.cn/Article/details/gt2rqfzpujy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hammf.cn/Article/details/gt2cenakauz.html

PHP:  curl_multi_init() 系列
来源：http://dali.pycfn.com/Article/details/gt2mhxhcvbk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gt2miibabie.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gt2ypjmbpls.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.andypj.xyz/Article/details/gt2afjwdgje.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhoulong.xyz/Article/details/gt2qweaayia.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jqgfzy.top/Article/details/gt2uzexgxxf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cucudq.cn/Article/details/gt2tkuhmthf.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2okxbjyzl.html

M. 命令行 / 进程 / 环境
来源：http://dali.jyoumei.cn/Article/details/gt2vskbpjht.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2fbnjtzlt.html

[M01] 读取命令行参数
来源：http://dali.yuxming.cn/Article/details/gt2kydpasvz.html

Py:   sys.argv[1:]
来源：http://dali.zycfv.cn/Article/details/gt2lnwmvvyz.html

PHP:  $argv;  $argc;
来源：http://dali.dashuyun.cn/Article/details/gt2wmbpckgo.html

JS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gt2fqvobhdw.html

TS:   process.argv.slice(2)
来源：http://dali.jyoumei.cn/Article/details/gt2szmxmgmp.html

Java: args 数组（main 方法参数）
来源：http://dali.smart0.xyz/Article/details/gt2qatghkzz.html

Go:   os.Args[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gt2siyqjslt.html

Ruby: ARGV
来源：http://dali.chenjidiqi.icu/Article/details/gt2pehufhjy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.dianchejie.cn/Article/details/gt2wwzaaobl.html

[M02] 读取环境变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2zblycxfq.html

Py:   os.environ.get("HOME")
来源：http://dali.ydzc1.top/Article/details/gt2ogkurfps.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gt2csrbypgw.html

JS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gt2cymrkroe.html

TS:   process.env.HOME
来源：http://dali.aizwys.cn/Article/details/gt2nagsldks.html

Java: System.getenv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gt2eqwglxhy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ppjwa.cn/Article/details/gt2pmnjxnnk.html

Ruby: ENV["HOME"]
来源：http://dali.cqqwz.cn/Article/details/gt2gwjuzruc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zdqjudy.top/Article/details/gt2jvjdgfkz.html

[M03] 执行外部命令
来源：http://dali.yvedp.cn/Article/details/gt2fxcyscfj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guannengcc.top/Article/details/gt2jkixziyy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xziqi.cn/Article/details/gt2gjqidtpn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gt2htqzurmv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxinkj.top/Article/details/gt2szmyluuy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhiwuduotai.top/Article/details/gt2fnkkjery.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yqpisimt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangdashe.top/Article/details/gt2givqitad.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cucudq.cn/Article/details/gt2guqxytqi.html

[M04] 获取当前工作目录
来源：http://dali.gogol.net.cn/Article/details/gt2upjpxkkm.html

Py:   os.getcwd()
来源：http://dali.yj20258888.top/Article/details/gt2bxwqfjgf.html

PHP:  getcwd();
来源：http://dali.jinqigufen.top/Article/details/gt2xxiyfilc.html

JS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gt2xaunaiet.html

TS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gt2obkavnzx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cdnleiting.top/Article/details/gt2gnqgqslb.html

Go:   os.Getwd()
来源：http://dali.yangfankeji.com/Article/details/gt2jvwmfcns.html

Ruby: Dir.pwd
来源：http://dali.shuidangran.top/Article/details/gt2zillpmbx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.9152youxi.cn/Article/details/gt2xnfnvylt.html

[M05] 设置退出码
来源：http://dali.ivvv.top/Article/details/gt2ipnstpvx.html

Py:   sys.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rogmcpam.html

PHP:  exit(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yquksmue.html

JS:   process.exit(1)
来源：http://dali.shuidangran.top/Article/details/gt2jhdzpgbc.html

TS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gt2vkhfqvwp.html

Java: System.exit(1)
来源：http://dali.cheryme.top/Article/details/gt2nebqseja.html

Go:   os.Exit(1)
来源：http://dali.0kj1m.cn/Article/details/gt2czqxpwgx.html

Ruby: exit 1
来源：http://dali.sysykeji.top/Article/details/gt2qvhqvppa.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ybcxt.top/Article/details/gt2gfcjvnku.html

[M06] 向标准错误输出
来源：http://dali.cqqwz.cn/Article/details/gt2pczrebgu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.c1oappe.top/Article/details/gt2okrdeobu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cashguo.top/Article/details/gt2qrmnpaaa.html

JS:   console.error("err")
来源：http://dali.sxryk.cn/Article/details/gt2qgzblfrf.html

TS:   console.error("err")
来源：http://dali.yj20258.top/Article/details/gt2xeqmxajh.html

Java: System.err.println("err")
来源：http://dali.gzhubu.top/Article/details/gt2iubcobye.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.quarkkingdee.top/Article/details/gt2cunpmvoc.html

Ruby: warn "err"
来源：http://dali.iojbl.cn/Article/details/gt2biuuyoqq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cqqwz.cn/Article/details/gt2wvradxys.html

[M07] 判断是否为主入口
来源：http://dali.aibaodan.cn/Article/details/gt2dpgewgti.html

Py:   if __name__ == "__main__":
来源：http://dali.yuanzhike.top/Article/details/gt2syfuphrm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yvedp.cn/Article/details/gt2vtiahzrg.html

JS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gt2angwcxga.html

TS:   require.main === module
来源：http://dali.gogol.net.cn/Article/details/gt2mozpodwg.html

Java: public static void main(String[] args)
来源：http://dali.mhx1999.top/Article/details/gt2dvxmqjuv.html

Go:   func main()
来源：http://dali.iojbl.cn/Article/details/gt2wprbptnz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.haohaochexian.top/Article/details/gt2yqiekkwo.html

C#:   static void Main(string[] args)
来源：http://dali.jqgfzy.top/Article/details/gt2tjccanfn.html

[M08] 获取系统与运行时信息
来源：http://dali.yanxiufei.cn/Article/details/gt2vhokvkyj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sysykeji.top/Article/details/gt2qkcghdva.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jlsjyb.cn/Article/details/gt2zwfktfdp.html

JS:   process.platform;  process.version
来源：http://dali.meibo888.top/Article/details/gt2fbecasqy.html

TS:   process.platform;  process.version
来源：http://dali.haohaochexian.top/Article/details/gt2rhyegkwj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xziqi.cn/Article/details/gt2qysnegvq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenzaomai.com/Article/details/gt2vnvmhbfd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhiwuduotai.top/Article/details/gt2chjyagdy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cqqwz.cn/Article/details/gt2ayvdfgxw.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2wewsxvqg.html

N. 数据结构与算法
来源：http://dali.shzxlz.cn/Article/details/gt2itjipaqs.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2uoehpvnn.html

[N01] 二分查找（有序数组）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ovzajruf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gt2dpgxyeew.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrqemod.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gzhubu.top/Article/details/gt2fcaswpeh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gt2idqlcwkh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yueranfly.top/Article/details/gt2vjbegims.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.iojbl.cn/Article/details/gt2jjevpdtg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.guannengcc.top/Article/details/gt2nmrwojen.html


<!-- 参考信息 -->