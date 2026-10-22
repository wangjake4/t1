代发 wailian999

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hnqzz.top/Article/details/gt2yjfvjwlp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gt2kflfkaos.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gzhubu.top/Article/details/gt2vnhamykg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dianchejie.cn/Article/details/gt2sgkbnwgh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cheryme.top/Article/details/gt2caksmzgq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gogol.net.cn/Article/details/gt2xmqivbbx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.andypj.xyz/Article/details/gt2qikdhnwt.html

[J06] 计算两时间之差
来源：http://dali.meibo888.top/Article/details/gt2qmcashub.html

Py:   (end - start).total_seconds()
来源：http://dali.jinqigufen.top/Article/details/gt2jfnnbprn.html

PHP:  $end->diff($start)->days;
来源：http://dali.hfpthk.cn/Article/details/gt2yyacwwmb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2owthwmzf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhengqikj.top/Article/details/gt2gewplcrc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cucudq.cn/Article/details/gt2jdhiglvs.html

Go:   end.Sub(start).Hours()
来源：http://dali.pengpengdd.cyou/Article/details/gt2qtkyvbcr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yongpay.top/Article/details/gt2yrpuidza.html

C#:   (end - start).TotalSeconds
来源：http://dali.tian-w.cn/Article/details/gt2tjbjhkts.html

[J07] 比较两个日期
来源：http://dali.bjfxy.top/Article/details/gt2oyfmckoy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gt2edumgluq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jlsjyb.cn/Article/details/gt2buvnjcba.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ddbrajtk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.kuanghao11.cn/Article/details/gt2zduspxjy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cashguo.top/Article/details/gt2epkjvxip.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jyoumei.cn/Article/details/gt2kkmvyjsh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gt2dlvwebbs.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gt2dyzgwzkm.html

[J08] 提取年月日与星期
来源：http://dali.jlsjyb.cn/Article/details/gt2mpawfigu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jyoumei.cn/Article/details/gt2thjpqzjn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hywenlv.cn/Article/details/gt2ljotjdfs.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yongpay.top/Article/details/gt2mktfguej.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dashuyun.cn/Article/details/gt2udqyjhuh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.bjfxy.top/Article/details/gt2spvjxqev.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.haohaochexian.top/Article/details/gt2scvqhwsr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cbbeebee.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cqqwz.cn/Article/details/gt2kzpaabkt.html

[J09] 时区处理
来源：http://dali.xziqi.cn/Article/details/gt2bemviomw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nwbrower.top/Article/details/gt2ufhxfhkz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hnqzz.top/Article/details/gt2igzthsjl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnqzz.top/Article/details/gt2ucrvklqa.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cnzrkrae.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guowangkeji.top/Article/details/gt2gtunazvu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yongpay.top/Article/details/gt2opasdtyp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.aibaodan.cn/Article/details/gt2ltexheqy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj202588.top/Article/details/gt2uqgwxest.html

[J10] 取今天 / 本月第一天
来源：http://dali.cdnleiting.top/Article/details/gt2rpztvalq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tian-w.cn/Article/details/gt2ujmpwnnv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.iojbl.cn/Article/details/gt2xvciykum.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.havefunace.top/Article/details/gt2vluksbik.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenzaomai.com/Article/details/gt2geymdwfq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hywenlv.cn/Article/details/gt2kmmgjxwv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xinyue.icu/Article/details/gt2wuffzmua.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.aizwys.cn/Article/details/gt2ohomtayu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.daria6918.cn/Article/details/gt2fgvqlier.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2srcygexx.html

K. JSON 与序列化
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2egpznpmq.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2zxmzfvvz.html

[K01] 对象转 JSON 字符串
来源：http://dali.shzxlz.cn/Article/details/gt2gxdczeyc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gt2lpsmnaqu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.wangdashe.top/Article/details/gt2invjidym.html

JS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2vygtxzvj.html

TS:   JSON.stringify(obj)
来源：http://dali.cashguo.top/Article/details/gt2vfinkwho.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yvedp.cn/Article/details/gt2pqeswrga.html

Go:   json.Marshal(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2eqnkxaol.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenjidiqi.icu/Article/details/gt2ndtfihlc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sweek.top/Article/details/gt2nwubvdpx.html

[K02] JSON 字符串转对象
来源：http://dali.zhengqikj.top/Article/details/gt2ugfzesrr.html

Py:   json.loads(s)
来源：http://dali.yuxming.cn/Article/details/gt2ukzoqnzb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tianlin.xyz/Article/details/gt2ftpuagzk.html

JS:   JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gt2kfabbafs.html

TS:   JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gt2ybmjwhih.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.aibaodan.cn/Article/details/gt2ptqbhkwm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.dianchejie.cn/Article/details/gt2jsjctksz.html

Ruby: JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gt2mhhscaft.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yangfankeji.com/Article/details/gt2aldqehyd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhengqikj.top/Article/details/gt2ujmwczwi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hywenlv.cn/Article/details/gt2zqamkulo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.aibaodan.cn/Article/details/gt2zizumfje.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2hiyzfthr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.316326.xyz/Article/details/gt2enisatrx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.c1oappe.top/Article/details/gt2srmdzplt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.haohaochexian.top/Article/details/gt2nvrmaldm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2iyramvrq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.quarkkingdee.top/Article/details/gt2ozzirdik.html

[K04] 读取 JSON 文件
来源：http://dali.zycfv.cn/Article/details/gt2wywdxwzf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.316326.xyz/Article/details/gt2xwozmywy.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.meibo888.top/Article/details/gt2cszxophp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.meibo888.top/Article/details/gt2gqjchxsm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aibaodan.cn/Article/details/gt2fzdrtgth.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.wangdashe.top/Article/details/gt2fzmymkff.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ehwqpu.com/Article/details/gt2putbxgfk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj20258888.top/Article/details/gt2lcmcxdpq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gzhubu.top/Article/details/gt2ypmzuayc.html

[K05] 深拷贝对象
来源：http://dali.guowangkeji.top/Article/details/gt2mqgramcb.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2fgqloenx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yvedp.cn/Article/details/gt2bohfxadq.html

JS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gt2kbeapjcj.html

TS:   structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2chagfbvh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.birdmap.top/Article/details/gt2koatorct.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yanxiufei.cn/Article/details/gt2jpdrwwyq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cucudq.cn/Article/details/gt2pqxoncqg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.haohaochexian.top/Article/details/gt2apbegply.html

[K06] 解析 URL 查询串
来源：http://dali.jinqigfzy.top/Article/details/gt2onzfxslp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gotoacloud.top/Article/details/gt2lolnyxqi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yjqoqshp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenjidiqi.icu/Article/details/gt2vklujfet.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gt2nxgbuaar.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ehwqpu.com/Article/details/gt2osprqkrx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gt2swiugokp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gt2pwtxizti.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gt2ronlwgck.html

[K07] 进制转换
来源：http://dali.gotoacloud.top/Article/details/gt2xdrkigzg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.havefunace.top/Article/details/gt2tmnkbgiz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxinkj.top/Article/details/gt2fyysttyx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gt2nlueogkd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gt2jmtsuume.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gt2fczmfndu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kcfzcuhb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yvedp.cn/Article/details/gt2wyxajtjz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2iqsvcxfy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lgusvhuq.html

Py:   pickle.dumps(obj)
来源：http://dali.cashguo.top/Article/details/gt2uhldhlam.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sweek.top/Article/details/gt2hgfmxest.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.dashuyun.cn/Article/details/gt2wiosjlxb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.fengsongda.top/Article/details/gt2ltostfge.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ybcxt.top/Article/details/gt2olmaktqq.html

Go:   encoding/gob
来源：http://dali.feifeiyinyue.top/Article/details/gt2avgbrjrh.html

Ruby: Marshal.dump(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2fdzcayxa.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gt2xzatfmqk.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2kxfbmvyc.html

L. 网络请求
来源：http://dali.nwbrower.top/Article/details/gt2cmvhulhf.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2ydccnmyp.html

[L01] 发送 GET 请求
来源：http://dali.cheryme.top/Article/details/gt2fvcrjbcj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gotoacloud.top/Article/details/gt2ijjvdjjr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnqzz.top/Article/details/gt2lvozhvot.html

JS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gt2mznpctir.html

TS:   await fetch(url)
来源：http://dali.yueranfly.top/Article/details/gt2fykzrkga.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.daxiang520.top/Article/details/gt2pljxjayl.html

Go:   resp, err := http.Get(url)
来源：http://dali.andypj.xyz/Article/details/gt2xphkxmkj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hfpthk.cn/Article/details/gt2urlwgmjs.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.daria6918.cn/Article/details/gt2ynaobqed.html

[L02] 发送 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gt2oqfhlcuj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhongyouzk.top/Article/details/gt2wqocithx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sweek.top/Article/details/gt2zfuzuvui.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangdashe.top/Article/details/gt2hppceuqa.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigufen.top/Article/details/gt2bhxpnaxh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.dianchejie.cn/Article/details/gt2ohfgzzzd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ivvv.top/Article/details/gt2opufzzly.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sfrzlwbw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aibaodan.cn/Article/details/gt2qcwzvjtq.html

[L03] 设置自定义请求头
来源：http://dali.jinqigufen.top/Article/details/gt2ltsadmhw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.daria6918.cn/Article/details/gt2hggkxxfv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.316326.xyz/Article/details/gt2gvwbktfx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sweek.top/Article/details/gt2odajtnva.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eygpqpeq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zycfv.cn/Article/details/gt2cjfscdpg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.daxiang520.top/Article/details/gt2cmmaeqym.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sufxvd.cn/Article/details/gt2vifdlief.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gt2tvfgjlax.html

[L04] 设置超时
来源：http://dali.daxiang520.top/Article/details/gt2bewtykkm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.havefunace.top/Article/details/gt2dlohujdw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhoulong.xyz/Article/details/gt2whlcixep.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.iojbl.cn/Article/details/gt2odenldbc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenzaomai.com/Article/details/gt2aatktcjt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daxiang520.top/Article/details/gt2hgorknnr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj202588.top/Article/details/gt2zezvxwvv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cashguo.top/Article/details/gt2dymxayke.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daria6918.cn/Article/details/gt2rjgqyeiq.html

[L05] 上传文件（multipart）
来源：http://dali.hnxiangtu.top/Article/details/gt2boawgrzo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.bjfxy.top/Article/details/gt2iparkbzd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jqgfzy.top/Article/details/gt2dwjqlpnr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxinkj.top/Article/details/gt2uwcucema.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ehwqpu.com/Article/details/gt2ksnbpwez.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gzhubu.top/Article/details/gt2pdmtnkgv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nanxuanxn.top/Article/details/gt2opwlkxab.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.pengpengdd.cyou/Article/details/gt2jtjptsud.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2lubeiloz.html

[L06] 解析响应为 JSON
来源：http://dali.gotoacloud.top/Article/details/gt2ktcjiwkz.html

Py:   resp.json()
来源：http://dali.tian-w.cn/Article/details/gt2yhyjweoc.html

PHP:  json_decode($body, true);
来源：http://dali.hnxiangtu.top/Article/details/gt2lkachkaj.html

JS:   await resp.json()
来源：http://dali.jqgfzy.top/Article/details/gt2esrtseck.html

TS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gt2rzrifzvd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nwbrower.top/Article/details/gt2dfoecsjz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yonumen.top/Article/details/gt2nutifmkk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ivvv.top/Article/details/gt2zmasgymm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhongyouzk.top/Article/details/gt2iccevbhw.html

[L07] 处理 HTTP 状态码
来源：http://dali.jqgufenzy.top/Article/details/gt2fxfguvhe.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ydmlpsnp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.kuanghao11.cn/Article/details/gt2tkseqnvt.html

JS:   resp.ok;  resp.status
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mfjvxcxm.html

TS:   resp.ok;  resp.status
来源：http://dali.ydzc1.top/Article/details/gt2dowziask.html

Java: resp.statusCode()
来源：http://dali.aibaodan.cn/Article/details/gt2bkvrejyz.html

Go:   resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gt2hqjjnwpj.html

Ruby: resp.code.to_i
来源：http://dali.0kj1m.cn/Article/details/gt2rbtgwjul.html

C#:   (int)resp.StatusCode
来源：http://dali.c1oappe.top/Article/details/gt2yzbjfyqu.html

[L08] 并发请求多个地址
来源：http://dali.ivvv.top/Article/details/gt2kscayitd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yonumen.top/Article/details/gt2yanotmyv.html

PHP:  curl_multi_init() 系列
来源：http://dali.birdmap.top/Article/details/gt2qrappstt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bghrdihq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gt2uojvqgkp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ppjwa.cn/Article/details/gt2mcykshvf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yangfankeji.com/Article/details/gt2vzstgmef.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hywenlv.cn/Article/details/gt2niubixaf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.0kj1m.cn/Article/details/gt2wpeigpvr.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2hmpdkasp.html

M. 命令行 / 进程 / 环境
来源：http://dali.tianlin.xyz/Article/details/gt2wrhpqhmp.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2ggteaslx.html

[M01] 读取命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gt2gjgovikp.html

Py:   sys.argv[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sbsojrxs.html

PHP:  $argv;  $argc;
来源：http://dali.sxryk.cn/Article/details/gt2bamrhust.html

JS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2aeqdwhnr.html

TS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gt2obaarbvs.html

Java: args 数组（main 方法参数）
来源：http://dali.meibo888.top/Article/details/gt2bymmtiqq.html

Go:   os.Args[1:]
来源：http://dali.vqdsnc.cn/Article/details/gt2fkecqwfl.html

Ruby: ARGV
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zxcyavea.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hywenlv.cn/Article/details/gt2xjofwfri.html

[M02] 读取环境变量
来源：http://dali.zhoulong.xyz/Article/details/gt2jljmcswi.html

Py:   os.environ.get("HOME")
来源：http://dali.gzhubu.top/Article/details/gt2axoqfsue.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hongshengwenyu.top/Article/details/gt2kfxvcydt.html

JS:   process.env.HOME
来源：http://dali.jianghu66.top/Article/details/gt2nmbfdafc.html

TS:   process.env.HOME
来源：http://dali.ydzc1.top/Article/details/gt2dptzyyuv.html

Java: System.getenv("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2czifmesh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yangfankeji.com/Article/details/gt2mrgvxqrm.html

Ruby: ENV["HOME"]
来源：http://dali.yj202588.top/Article/details/gt2krwbfkyb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gt2xpzspaeo.html

[M03] 执行外部命令
来源：http://dali.shzxlz.cn/Article/details/gt2povgoywb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.dashuyun.cn/Article/details/gt2qjjjpqow.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gotoacloud.top/Article/details/gt2cxmjlxyr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zycfv.cn/Article/details/gt2nbodwlha.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.snrcjt.cn/Article/details/gt2itzwyfnc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.guowangkeji.top/Article/details/gt2fywxjsyz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hnxiangtu.top/Article/details/gt2bzkoohwq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ivvv.top/Article/details/gt2bdqafvaj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangshuangyany.cn/Article/details/gt2lniqvttb.html

[M04] 获取当前工作目录
来源：http://dali.xuanzx.com/Article/details/gt2gwygqjjj.html

Py:   os.getcwd()
来源：http://dali.tianlin.xyz/Article/details/gt2xrvqleta.html

PHP:  getcwd();
来源：http://dali.chenlongwang.top/Article/details/gt2moruwwtq.html

JS:   process.cwd()
来源：http://dali.yj202588.top/Article/details/gt2hmltkkza.html

TS:   process.cwd()
来源：http://dali.cqqwz.cn/Article/details/gt2mwdxkfaq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wmwatnzv.html

Go:   os.Getwd()
来源：http://dali.gaohongyu789.top/Article/details/gt2dfcgaipe.html

Ruby: Dir.pwd
来源：http://dali.hysaishi.cn/Article/details/gt2nuwdxinh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenzaomai.com/Article/details/gt2qbyaenej.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqmciyq.html

Py:   sys.exit(1)
来源：http://dali.ydzc1.top/Article/details/gt2kyhkyksj.html

PHP:  exit(1);
来源：http://dali.tianlin.xyz/Article/details/gt2uxzmfsni.html

JS:   process.exit(1)
来源：http://dali.gzhubu.top/Article/details/gt2oecmktoy.html

TS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gt2rcsfwpje.html

Java: System.exit(1)
来源：http://dali.hnqzz.top/Article/details/gt2davkqzui.html

Go:   os.Exit(1)
来源：http://dali.jyoumei.cn/Article/details/gt2lstjovww.html

Ruby: exit 1
来源：http://dali.nanxuanxn.top/Article/details/gt2xzzcqjvk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cqqwz.cn/Article/details/gt2riltokna.html

[M06] 向标准错误输出
来源：http://dali.cucudq.cn/Article/details/gt2lpzixpkm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sweek.top/Article/details/gt2tfuxudzs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgufenzy.top/Article/details/gt2odeilvsk.html

JS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gt2kqzxgfvp.html

TS:   console.error("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ginclhjw.html

Java: System.err.println("err")
来源：http://dali.hongshengwenyu.top/Article/details/gt2xtypmzqo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhongyouzk.top/Article/details/gt2dqzfzeno.html

Ruby: warn "err"
来源：http://dali.ppjwa.cn/Article/details/gt2ggjilaih.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.kuanghao11.cn/Article/details/gt2jpselbqo.html

[M07] 判断是否为主入口
来源：http://dali.yvedp.cn/Article/details/gt2mahksabx.html

Py:   if __name__ == "__main__":
来源：http://dali.mhx1999.top/Article/details/gt2tyeaxttw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yvedp.cn/Article/details/gt2qbqxcpxr.html

JS:   require.main === module
来源：http://dali.ehwqpu.com/Article/details/gt2vkfjiosa.html

TS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gt2gdqicike.html

Java: public static void main(String[] args)
来源：http://dali.tianlin.xyz/Article/details/gt2zuzfjoqj.html

Go:   func main()
来源：http://dali.xinyue.icu/Article/details/gt2utakkqpw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cdnleiting.top/Article/details/gt2jfvqzqxs.html

C#:   static void Main(string[] args)
来源：http://dali.sufxvd.cn/Article/details/gt2ghhcxuzw.html

[M08] 获取系统与运行时信息
来源：http://dali.shuidangran.top/Article/details/gt2aozvdnpa.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ivvv.top/Article/details/gt2latbdvmu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.aizwys.cn/Article/details/gt2abnwurwl.html

JS:   process.platform;  process.version
来源：http://dali.haohaochexian.top/Article/details/gt2cjzvyicx.html

TS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gt2umybwadr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnxiangtu.top/Article/details/gt2lrqfrsfz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdyaulp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.kuanghao11.cn/Article/details/gt2befrzmyz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjavqlh.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2rcahpuep.html

N. 数据结构与算法
来源：http://dali.svipenyu.cn/Article/details/gt2lynonapy.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2aifusgep.html

[N01] 二分查找（有序数组）
来源：http://dali.smart0.xyz/Article/details/gt2cxxqbmwu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sysykeji.top/Article/details/gt2haurvkqf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenzaomai.com/Article/details/gt2vrlygdoe.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.0kj1m.cn/Article/details/gt2nrbofxne.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gt2ketzmcuh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bwqssrap.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgdfrin.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cheryme.top/Article/details/gt2hcnfzcqz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.316326.xyz/Article/details/gt2nzizmifp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2edpvapsf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hammf.cn/Article/details/gt2ywrofkme.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhengqikj.top/Article/details/gt2sgfmaicf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gt2occnxelo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gt2teweerxq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zdqjudy.top/Article/details/gt2jqggimaf.html

Go:   slices.Sort(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iabuzjmc.html

Ruby: arr.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tvcfgxfy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhiwuduotai.top/Article/details/gt2mdaozyfo.html

[N03] 快速排序（分治示例）
来源：http://dali.dianchejie.cn/Article/details/gt2qdhphepr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.316326.xyz/Article/details/gt2ewrdxftq.html


<!-- 参考信息 -->