代发 wailian999

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cheryme.top/Article/details/gtwhnptkgr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258.top/Article/details/gtnkcvzvsa.html

[J05] 时间加减（加 7 天）
来源：http://dali.smart0.xyz/Article/details/gtvshbhewm.html

Py:   now + timedelta(days=7)
来源：http://dali.zhijiandao.cn/Article/details/gtcdtpdwax.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj20258888.top/Article/details/gtyqsywnkr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.kuanghao11.cn/Article/details/gtgjlsyhob.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.havefunace.top/Article/details/gtabzmsmna.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhixingplan.top/Article/details/gtvpyucrbd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jyoumei.cn/Article/details/gtjcdiaerk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tian-w.cn/Article/details/gtklnrsmwg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.fzhhl.top/Article/details/gtzobbxfxo.html

[J06] 计算两时间之差
来源：http://dali.yongpay.top/Article/details/gtnvsgfvco.html

Py:   (end - start).total_seconds()
来源：http://dali.yanxiufei.cn/Article/details/gtojlwdanh.html

PHP:  $end->diff($start)->days;
来源：http://dali.gogol.net.cn/Article/details/gtxtpkmpgi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tanke756.top/Article/details/gtzrmxqhht.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gogol.net.cn/Article/details/gtihnkufhy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cheryme.top/Article/details/gtgdgtxsuz.html

Go:   end.Sub(start).Hours()
来源：http://dali.wangshuangyany.cn/Article/details/gtjiersbba.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zdqjudy.top/Article/details/gtrtrlvrxa.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhongyouzk.top/Article/details/gtotrkdxvv.html

[J07] 比较两个日期
来源：http://dali.ybcxt.top/Article/details/gtzkimeiyl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gtqepmxfhg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ehwqpu.com/Article/details/gtjtfpxxwz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangtech.top/Article/details/gtaablkbmn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.kuanghao11.cn/Article/details/gtfadfzets.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.guannengcc.top/Article/details/gtgkoxtjdd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinqigufen.top/Article/details/gthtkgwnbf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtglijzpbb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gtbvbdbmwe.html

[J08] 提取年月日与星期
来源：http://dali.316326.xyz/Article/details/gtlzdzlxpt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gogol.net.cn/Article/details/gttwygcgrs.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xuetiantiany.cn/Article/details/gtnodcetqt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xinyue.icu/Article/details/gtexvgkkqp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.aizwys.cn/Article/details/gtplytdfzp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.fzhhl.top/Article/details/gtvfwcedaw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.quarkkingdee.top/Article/details/gtijmzzhis.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.bjfxy.top/Article/details/gtflwnzgnx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.aizwys.cn/Article/details/gtszqjbgfs.html

[J09] 时区处理
来源：http://dali.hysaishi.cn/Article/details/gtlzeovosd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.havefunace.top/Article/details/gtdfxrvtyg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shzxlz.cn/Article/details/gtqypnfilk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gogol.net.cn/Article/details/gtvjdtgbja.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gtuqywdjyr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jiagoushi.top/Article/details/gtolyqjarc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.vqdsnc.cn/Article/details/gtjjcjohob.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdufyqhh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfurzmcn.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhengqikj.top/Article/details/gtgaoheizl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.haohaochexian.top/Article/details/gtrkifeeti.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hywenlv.cn/Article/details/gtuoervewq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hammf.cn/Article/details/gtamtdlefh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ppjwa.cn/Article/details/gtnmujhssu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.vqdsnc.cn/Article/details/gtoicavigm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.316326.xyz/Article/details/gtmjhhhccc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hysaishi.cn/Article/details/gtpfigaxsi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.iojbl.cn/Article/details/gtrgzpgpes.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtjvspjilm.html

K. JSON 与序列化
来源：http://dali.yangfankeji.com/Article/details/gtbyouxtgv.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtiiohmcfq.html

[K01] 对象转 JSON 字符串
来源：http://dali.hnxiangtu.top/Article/details/gtrghgxmnm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gtwknobgmp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gttnsmnxsb.html

JS:   JSON.stringify(obj)
来源：http://dali.mhx1999.top/Article/details/gtyyorrcfz.html

TS:   JSON.stringify(obj)
来源：http://dali.c1oappe.top/Article/details/gtlkdprmnp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ivvv.top/Article/details/gtsxrcyjdb.html

Go:   json.Marshal(obj)
来源：http://dali.chenzaomai.com/Article/details/gtmbtvkqpj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.dianchejie.cn/Article/details/gtdpdoljan.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yvedp.cn/Article/details/gtjezwancf.html

[K02] JSON 字符串转对象
来源：http://dali.havefunace.top/Article/details/gtrvghudng.html

Py:   json.loads(s)
来源：http://dali.chenzaomai.com/Article/details/gtibyoqmou.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jiagoushi.top/Article/details/gtvlfulbvh.html

JS:   JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gtrufreeaj.html

TS:   JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gtdsgrktnp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jiagoushi.top/Article/details/gtjppzqlav.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jiagoushi.top/Article/details/gtotasaelx.html

Ruby: JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjloxfctg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.iojbl.cn/Article/details/gtcdozonba.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cucudq.cn/Article/details/gtstwvnoxp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.daxiang520.top/Article/details/gtumcqcxpf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sxryk.cn/Article/details/gtmcesxncz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.mhx1999.top/Article/details/gtavefhvnp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jiagoushi.top/Article/details/gtotrvwkkb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ehwqpu.com/Article/details/gtmfxtnyrp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhiwuduotai.top/Article/details/gtvgxxxrpq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.316326.xyz/Article/details/gtdyatmiry.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxuanxn.top/Article/details/gtkbarxejk.html

[K04] 读取 JSON 文件
来源：http://dali.mhx1999.top/Article/details/gtslwlzwys.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhengqikj.top/Article/details/gtruoxsjfz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hywenlv.cn/Article/details/gtuqlndwlf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gtghadduzc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuetiantiany.cn/Article/details/gtblasvwat.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqxtbwgjj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenzaomai.com/Article/details/gtsfcnunbj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.andypj.xyz/Article/details/gtexyhwqog.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gtosmyieot.html

[K05] 深拷贝对象
来源：http://dali.yj20258.top/Article/details/gtjhcanlsr.html

Py:   copy.deepcopy(obj)
来源：http://dali.sxryk.cn/Article/details/gtlofsebdz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.guowangkeji.top/Article/details/gtfyojblxc.html

JS:   structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gtowbdncsc.html

TS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gtkkkgivpl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.smart0.xyz/Article/details/gtpxszvkbv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.snrcjt.cn/Article/details/gtonteghli.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gaohongyu789.top/Article/details/gtirrvqxgw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yuanzhike.top/Article/details/gtasoltval.html

[K06] 解析 URL 查询串
来源：http://dali.hammf.cn/Article/details/gthbrztibx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tian-w.cn/Article/details/gttdusqazs.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.9152youxi.cn/Article/details/gtqwlngtbt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangdashe.top/Article/details/gtjgtyafyu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhongyouzk.top/Article/details/gtbkvzxurp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xylfe.cn/Article/details/gtnxsavipd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gtsgkbozab.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gtbdmwijfr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cashguo.top/Article/details/gtlyheehtn.html

[K07] 进制转换
来源：http://dali.guowangkeji.top/Article/details/gtfxghkemm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnovvrfls.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sweek.top/Article/details/gtclymzkxg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtoxdmbrga.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtjyoamvls.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtzebdcqbq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cqqwz.cn/Article/details/gtoigjndbn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shuidangran.top/Article/details/gtmcyjbfvt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtpxqsdykw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ppjwa.cn/Article/details/gttuqtiayd.html

Py:   pickle.dumps(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gthoqbeehc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.chenlongwang.top/Article/details/gtbyeisivy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnxiangtu.top/Article/details/gtxmosewgi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ivvv.top/Article/details/gtkbglhxjz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yongpay.top/Article/details/gtfojlgqot.html

Go:   encoding/gob
来源：http://dali.jiagoushi.top/Article/details/gtmcrjiotr.html

Ruby: Marshal.dump(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtcqtcjfak.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cashguo.top/Article/details/gtwmsoeude.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtayjmmsxw.html

L. 网络请求
来源：http://dali.yanxiufei.cn/Article/details/gtgkzntxff.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtetvxhntp.html

[L01] 发送 GET 请求
来源：http://dali.pengpengdd.cyou/Article/details/gtbinjqifl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.vqdsnc.cn/Article/details/gtlxlvafaq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jianghu66.top/Article/details/gtvdevftxu.html

JS:   await fetch(url)
来源：http://dali.sysykeji.top/Article/details/gtzqtkqhbg.html

TS:   await fetch(url)
来源：http://dali.dashuyun.cn/Article/details/gtgtxtovcw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hammf.cn/Article/details/gtefvmwwhv.html

Go:   resp, err := http.Get(url)
来源：http://dali.wangdashe.top/Article/details/gtkdgotsad.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hywenlv.cn/Article/details/gtolzjvzgo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xuanzx.com/Article/details/gtuuzfpdey.html

[L02] 发送 POST JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkazvjrbr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.pengpengdd.cyou/Article/details/gtllbspcwc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.dianchejie.cn/Article/details/gtmibptltd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxuanxn.top/Article/details/gtjlowfdaj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tanke756.top/Article/details/gtkhidxqus.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ydzc1.top/Article/details/gtxlxlqveg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlujxncav.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.9152youxi.cn/Article/details/gtzpwfiksl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.0kj1m.cn/Article/details/gtxjaglwkq.html

[L03] 设置自定义请求头
来源：http://dali.shuidangran.top/Article/details/gtspslyckw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.pengpengdd.cyou/Article/details/gtctmjrdgd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ybcxt.top/Article/details/gtfrhhtflo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hfpthk.cn/Article/details/gthwfygxvq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hfpthk.cn/Article/details/gtikmfuseu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cdnleiting.top/Article/details/gttesvboon.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gtduqnairm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhiwuduotai.top/Article/details/gtacdqpgjy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhengqikj.top/Article/details/gtgcaqdmbv.html

[L04] 设置超时
来源：http://dali.meibo888.top/Article/details/gtcaqnraiu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.birdmap.top/Article/details/gtteuphifp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenlongwang.top/Article/details/gtfjfdapmm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gotoacloud.top/Article/details/gtmvclwpbh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cqqwz.cn/Article/details/gtfgqflsms.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.quarkkingdee.top/Article/details/gtxvjbsulw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ydzc1.top/Article/details/gtjbtclzzf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.feifeiyinyue.top/Article/details/gtomztogvz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.fengsongda.top/Article/details/gtmrtkvqvu.html

[L05] 上传文件（multipart）
来源：http://dali.zhiwuduotai.top/Article/details/gtqpkdihyz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tianlin.xyz/Article/details/gtxuvbhnzr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.mhx1999.top/Article/details/gtigdkxbyg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuanzx.com/Article/details/gttzjianyr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.aizwys.cn/Article/details/gthaaxtzpr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.bjfxy.top/Article/details/gtkyhqtgxn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.svipenyu.cn/Article/details/gtaxrxwznv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jqgufenzy.top/Article/details/gticmwbzdp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtkoqiejjz.html

[L06] 解析响应为 JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtorrzbnug.html

Py:   resp.json()
来源：http://dali.sysykeji.top/Article/details/gtebgocrry.html

PHP:  json_decode($body, true);
来源：http://dali.yuxming.cn/Article/details/gtyuhfizoi.html

JS:   await resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gtcxobtqim.html

TS:   await resp.json()
来源：http://dali.gogol.net.cn/Article/details/gtyrsuprov.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtsdthjufb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gogol.net.cn/Article/details/gthpgmqnsv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yvedp.cn/Article/details/gtrzxuipce.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhixingplan.top/Article/details/gtxdgrhcmk.html

[L07] 处理 HTTP 状态码
来源：http://dali.wangdashe.top/Article/details/gtyhtbtqoc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenjidiqi.icu/Article/details/gtosmjvkol.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.mhx1999.top/Article/details/gtfeaxunac.html

JS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gtjnkznaeq.html

TS:   resp.ok;  resp.status
来源：http://dali.xuanzx.com/Article/details/gthudeqqmn.html

Java: resp.statusCode()
来源：http://dali.zycfv.cn/Article/details/gtxlpxdaku.html

Go:   resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gtorpzuorj.html

Ruby: resp.code.to_i
来源：http://dali.dianchejie.cn/Article/details/gtvkbvnrjy.html

C#:   (int)resp.StatusCode
来源：http://dali.gogol.net.cn/Article/details/gtnhypluet.html

[L08] 并发请求多个地址
来源：http://dali.aizwys.cn/Article/details/gtnqlyhezx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hysaishi.cn/Article/details/gtmvgkwqac.html

PHP:  curl_multi_init() 系列
来源：http://dali.cqqwz.cn/Article/details/gtytvzvkjd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.c1oappe.top/Article/details/gteaqujzyl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guannengcc.top/Article/details/gtbygkxhow.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.aizwys.cn/Article/details/gtjxinfapt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenzaomai.com/Article/details/gtzmatubdx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj20258888.top/Article/details/gtpjxbnbdh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtirbwernv.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtnfmueeun.html

M. 命令行 / 进程 / 环境
来源：http://dali.nwbrower.top/Article/details/gtilnwlgkb.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtyuxfmyxs.html

[M01] 读取命令行参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgxweqse.html

Py:   sys.argv[1:]
来源：http://dali.yuanzhike.top/Article/details/gtkrijnkjz.html

PHP:  $argv;  $argc;
来源：http://dali.cucudq.cn/Article/details/gtkqfhcohw.html

JS:   process.argv.slice(2)
来源：http://dali.tianlin.xyz/Article/details/gtxnaihktn.html

TS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gtnbkybsat.html

Java: args 数组（main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gtwzgvvuti.html

Go:   os.Args[1:]
来源：http://dali.yj20258888.top/Article/details/gtzklobohg.html

Ruby: ARGV
来源：http://dali.hnqzz.top/Article/details/gttewwxjhf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hongshengwenyu.top/Article/details/gtoiqqggsg.html

[M02] 读取环境变量
来源：http://dali.gzhubu.top/Article/details/gtlabmducw.html

Py:   os.environ.get("HOME")
来源：http://dali.bjfxy.top/Article/details/gtkrxrxgtv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gtanguaxjt.html

JS:   process.env.HOME
来源：http://dali.jqgufenzy.top/Article/details/gtegdsdzan.html

TS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gtboznhtdc.html

Java: System.getenv("HOME")
来源：http://dali.gzhubu.top/Article/details/gtvrhurxyc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtmffwyagz.html

Ruby: ENV["HOME"]
来源：http://dali.xuanzx.com/Article/details/gtjatxwpnc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shuidangran.top/Article/details/gtgrqzfnau.html

[M03] 执行外部命令
来源：http://dali.sweek.top/Article/details/gtjbodunnx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.fengsongda.top/Article/details/gtloimrzdc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jlsjyb.cn/Article/details/gtjbmyuznr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxinkj.top/Article/details/gtvyldwrxw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.dashuyun.cn/Article/details/gtmcrgweil.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hfpthk.cn/Article/details/gtpailbqsa.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yonumen.top/Article/details/gtegpjnfpe.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ybcxt.top/Article/details/gtcbmaimtq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hnxiangtu.top/Article/details/gtdmsifkyb.html

[M04] 获取当前工作目录
来源：http://dali.meibo888.top/Article/details/gtsddinbbo.html

Py:   os.getcwd()
来源：http://dali.zhixingplan.top/Article/details/gtbaqvgnzm.html

PHP:  getcwd();
来源：http://dali.vqdsnc.cn/Article/details/gtcjsroqwk.html

JS:   process.cwd()
来源：http://dali.fengsongda.top/Article/details/gtlecqqosh.html

TS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gtzycyxfhp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ivvv.top/Article/details/gtknfxicrk.html

Go:   os.Getwd()
来源：http://dali.zhixingplan.top/Article/details/gtskbebgsu.html

Ruby: Dir.pwd
来源：http://dali.hongshengwenyu.top/Article/details/gtsyxgcvfo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.redwolf501.top/Article/details/gttrjsezdl.html

[M05] 设置退出码
来源：http://dali.tanke756.top/Article/details/gtqnbkvjwa.html

Py:   sys.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtmwzsesng.html

PHP:  exit(1);
来源：http://dali.sweek.top/Article/details/gtmouvooxg.html

JS:   process.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtpdfscdzf.html

TS:   process.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtdveggsnz.html

Java: System.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtphydwwrk.html

Go:   os.Exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtiwnlvfdo.html

Ruby: exit 1
来源：http://dali.fengsongda.top/Article/details/gtkzovnoqt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yonumen.top/Article/details/gttqmkenls.html

[M06] 向标准错误输出
来源：http://dali.cheryme.top/Article/details/gtszjaazay.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgufenzy.top/Article/details/gtcrsdepmw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tanke756.top/Article/details/gtotopyonj.html

JS:   console.error("err")
来源：http://dali.yj20258888.top/Article/details/gtizehdbaw.html

TS:   console.error("err")
来源：http://dali.zhixingplan.top/Article/details/gtzlcnmeyn.html

Java: System.err.println("err")
来源：http://dali.c1oappe.top/Article/details/gtgholoesd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.9152youxi.cn/Article/details/gtbngedurs.html

Ruby: warn "err"
来源：http://dali.cqqwz.cn/Article/details/gtesuiezmc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hysaishi.cn/Article/details/gtatxcgawa.html

[M07] 判断是否为主入口
来源：http://dali.yj202588.top/Article/details/gtbufjttkv.html

Py:   if __name__ == "__main__":
来源：http://dali.xuetiantiany.cn/Article/details/gtweflsoqz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ybcxt.top/Article/details/gtvfknwysx.html

JS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gtbqsulntb.html

TS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gtmiztrzfe.html

Java: public static void main(String[] args)
来源：http://dali.jianghu66.top/Article/details/gtncxtsjrl.html

Go:   func main()
来源：http://dali.yj20258888.top/Article/details/gtdimvtowk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuetiantiany.cn/Article/details/gtiquszkqc.html

C#:   static void Main(string[] args)
来源：http://dali.nanxinkj.top/Article/details/gtdjsyjpen.html

[M08] 获取系统与运行时信息
来源：http://dali.jqgfzy.top/Article/details/gtcnhsuoye.html

Py:   platform.system();  platform.python_version()
来源：http://dali.andypj.xyz/Article/details/gtnixwidxf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cdnleiting.top/Article/details/gtjzurukgg.html

JS:   process.platform;  process.version
来源：http://dali.hnqzz.top/Article/details/gtqlbgehwa.html

TS:   process.platform;  process.version
来源：http://dali.yongpay.top/Article/details/gtlvtdphrx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zycfv.cn/Article/details/gtpbgqpddb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenjidiqi.icu/Article/details/gtuelsbyqb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangdashe.top/Article/details/gtzuafkgvc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jqgufenzy.top/Article/details/gtyhahtyqm.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtftamelfn.html

N. 数据结构与算法
来源：http://dali.nanxuanxn.top/Article/details/gtdhagzcig.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtotivpkiv.html

[N01] 二分查找（有序数组）
来源：http://dali.birdmap.top/Article/details/gtstwydkiz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtqgbvyfok.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenlongwang.top/Article/details/gtnfoeastp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnqzz.top/Article/details/gtrdlejrtt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gzhubu.top/Article/details/gtrfinmdcv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtgywkuopj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtvqlybkqf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cqqwz.cn/Article/details/gtnbcwcdhl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtpgwvisxt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shanyushiyangtech.top/Article/details/gteyqwrcpy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yonumen.top/Article/details/gtudcmeynd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.andypj.xyz/Article/details/gtwbbjkxmu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gtdccofxff.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gtrpulepdt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqrvrdvcp.html

Go:   slices.Sort(arr)
来源：http://dali.jyoumei.cn/Article/details/gtrxotxciw.html


<!-- 参考信息 -->