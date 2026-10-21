代发 wailian999

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zdqjudy.top/Article/details/gtroeawtoz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ehwqpu.com/Article/details/gtndvinbzu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinghuilouyu.cn/Article/details/gtinqktfkl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zdqjudy.top/Article/details/gtmztyqpjd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfrrmzcqp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xylfe.cn/Article/details/gtcihlpcym.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cheryme.top/Article/details/gtvoxmyxqd.html

[J06] 计算两时间之差
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqehfvfgq.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxuanxn.top/Article/details/gtzpxvsnsb.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhengqikj.top/Article/details/gtamenrgda.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.c1oappe.top/Article/details/gtvlsscfjv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.redwolf501.top/Article/details/gtzvduvlpp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.daria6918.cn/Article/details/gtyczvhqox.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtccubdrlq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenjidiqi.icu/Article/details/gttmuttiih.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhengqikj.top/Article/details/gtpinoopgo.html

[J07] 比较两个日期
来源：http://dali.nwbrower.top/Article/details/gtfykumljb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gtklhgfbsf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj20258888.top/Article/details/gtpygsatqt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgfzy.top/Article/details/gtjvkzsasv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gtfioyvqlb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cheryme.top/Article/details/gtlfysmvvx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjzgvkhmo.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gtpqagvabu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gtbefxahfd.html

[J08] 提取年月日与星期
来源：http://dali.haohaochexian.top/Article/details/gtbwlleqmu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hongshengwenyu.top/Article/details/gtqmjoqvef.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hysaishi.cn/Article/details/gtidwibguu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tanke756.top/Article/details/gtjhiherss.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.c1oappe.top/Article/details/gtesmfrozr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.andypj.xyz/Article/details/gtirynbyak.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.iojbl.cn/Article/details/gtsqpnaxro.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinghuilouyu.cn/Article/details/gtcfbbntan.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nwbrower.top/Article/details/gtmbezxury.html

[J09] 时区处理
来源：http://dali.yj20258888.top/Article/details/gtrlteqcqt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.quarkkingdee.top/Article/details/gtmoxrviyl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hfpthk.cn/Article/details/gtizgbvkqg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ivvv.top/Article/details/gtosgeviwd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daxiang520.top/Article/details/gtcnzzbiwa.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxuanxn.top/Article/details/gtyzlrjjlz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yonumen.top/Article/details/gtlnrhvoad.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yongpay.top/Article/details/gtmhnywvll.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqepfowz.html

[J10] 取今天 / 本月第一天
来源：http://dali.hfpthk.cn/Article/details/gtegbpsfub.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xylfe.cn/Article/details/gtphpuxwti.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.haohaochexian.top/Article/details/gtmuhqucsu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gotoacloud.top/Article/details/gtcgharneu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yuxming.cn/Article/details/gtzzrrwdcv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cheryme.top/Article/details/gtbpbfbjvh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ydzc1.top/Article/details/gtzzxslcdb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sweek.top/Article/details/gtrixopjuv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ivvv.top/Article/details/gtwrycyqrw.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtgztibmbo.html

K. JSON 与序列化
来源：http://dali.pengpengdd.cyou/Article/details/gtiozulwoj.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtxurwobyw.html

[K01] 对象转 JSON 字符串
来源：http://dali.birdmap.top/Article/details/gtnnnsilua.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shuidangran.top/Article/details/gtuetioxln.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tian-w.cn/Article/details/gtxhxzpwub.html

JS:   JSON.stringify(obj)
来源：http://dali.yj20258888.top/Article/details/gtgppphwir.html

TS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gtzmourxww.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhongyouzk.top/Article/details/gtriysxekt.html

Go:   json.Marshal(obj)
来源：http://dali.hammf.cn/Article/details/gtuncdwabv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hammf.cn/Article/details/gtuvwohqwp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guannengcc.top/Article/details/gtfebfcvtj.html

[K02] JSON 字符串转对象
来源：http://dali.tianlin.xyz/Article/details/gthyjsaart.html

Py:   json.loads(s)
来源：http://dali.gogol.net.cn/Article/details/gtbmmfrwkp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sysykeji.top/Article/details/gtheqwuhoa.html

JS:   JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrrfqsmc.html

TS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gtqmuppiqa.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sufxvd.cn/Article/details/gtofjxwwvf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj20258888.top/Article/details/gtkbsebayi.html

Ruby: JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gtiqziozmu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sysykeji.top/Article/details/gtnoiljoat.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jqgfzy.top/Article/details/gtrudpztge.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shzxlz.cn/Article/details/gtibfwbupz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zdqjudy.top/Article/details/gtiawvghns.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sysykeji.top/Article/details/gtiobqqcvj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gtcstjstex.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtwtmiiolz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.aizwys.cn/Article/details/gthlhyvgds.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.meibo888.top/Article/details/gtpgnmnabw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hnqzz.top/Article/details/gtewjvamif.html

[K04] 读取 JSON 文件
来源：http://dali.birdmap.top/Article/details/gtqylrsvha.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.andypj.xyz/Article/details/gtiacrrhfz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tianlin.xyz/Article/details/gtuhkjtbqn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xylfe.cn/Article/details/gtlvfaklyj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtogfboava.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gtncunijse.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.mhx1999.top/Article/details/gtozeuxctb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gtdqebaguu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnhxxdpb.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gtrfezosmv.html

Py:   copy.deepcopy(obj)
来源：http://dali.cdnleiting.top/Article/details/gtvlgwwvmn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.havefunace.top/Article/details/gtxyoqkhdy.html

JS:   structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gtinbdnkoq.html

TS:   structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gtcasmvkyr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jlsjyb.cn/Article/details/gtemfhzefe.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nwbrower.top/Article/details/gtslzqddcg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.bjfxy.top/Article/details/gtiixtdnvi.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yongpay.top/Article/details/gtopiajxmt.html

[K06] 解析 URL 查询串
来源：http://dali.ivvv.top/Article/details/gtexlbxzlc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cqqwz.cn/Article/details/gtmavwvznq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jianghu66.top/Article/details/gtvtfekuqn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sufxvd.cn/Article/details/gtdyupapgg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gtjtyuulkr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nwbrower.top/Article/details/gtflsfbxve.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gtdawmyhpz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gthybrnlgu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtffifbutk.html

[K07] 进制转换
来源：http://dali.sufxvd.cn/Article/details/gtmitnudbr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtyzixbigj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ivvv.top/Article/details/gtxybfdqim.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtwhddxkat.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gttntomfww.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtdvqeonik.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ehwqpu.com/Article/details/gtuplcuosr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shzxlz.cn/Article/details/gtwgaypony.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtexzqnxav.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jqgfzy.top/Article/details/gtckgmyfsa.html

Py:   pickle.dumps(obj)
来源：http://dali.nanxinkj.top/Article/details/gtgrbounjh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuanzx.com/Article/details/gtrcodswtm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjmdfhnyv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gzhubu.top/Article/details/gtbmnyihth.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yvedp.cn/Article/details/gtaahefpmw.html

Go:   encoding/gob
来源：http://dali.hnqzz.top/Article/details/gtivlroejq.html

Ruby: Marshal.dump(obj)
来源：http://dali.haohaochexian.top/Article/details/gtbizykeyp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gtjeupvkjw.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtchrulohf.html

L. 网络请求
来源：http://dali.guannengcc.top/Article/details/gtycaryweh.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtwgdjkaxx.html

[L01] 发送 GET 请求
来源：http://dali.dianchejie.cn/Article/details/gtmqqkmknn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.pengpengdd.cyou/Article/details/gtlddpscwt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.wangdashe.top/Article/details/gtpquicxpe.html

JS:   await fetch(url)
来源：http://dali.aibaodan.cn/Article/details/gtztlvastm.html

TS:   await fetch(url)
来源：http://dali.tianlin.xyz/Article/details/gtcovniqlt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ivvv.top/Article/details/gtbukzmibj.html

Go:   resp, err := http.Get(url)
来源：http://dali.hywenlv.cn/Article/details/gtwztezmno.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zycfv.cn/Article/details/gthwqjjufi.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenzaomai.com/Article/details/gtascnenmr.html

[L02] 发送 POST JSON
来源：http://dali.hammf.cn/Article/details/gttshkhavv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.wangshuangyany.cn/Article/details/gtainsqtcw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jyoumei.cn/Article/details/gtydjjcoft.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxcsaduz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gtmjzojbdy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangdashe.top/Article/details/gtsiekzjaa.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cqqwz.cn/Article/details/gtzjkjcmmh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xuetiantiany.cn/Article/details/gtougsulgd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhengqikj.top/Article/details/gtpywmpytx.html

[L03] 设置自定义请求头
来源：http://dali.iojbl.cn/Article/details/gtnisnxkao.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jianghu66.top/Article/details/gtpzupafym.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xuanzx.com/Article/details/gtpptbpshd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.quarkkingdee.top/Article/details/gtdfjouprn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jyoumei.cn/Article/details/gtkiqmcknl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.andypj.xyz/Article/details/gtdstsljtm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.redwolf501.top/Article/details/gtxiyhlqbh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zycfv.cn/Article/details/gttqbsbxtf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gtsrrkjljd.html

[L04] 设置超时
来源：http://dali.gaohongyu789.top/Article/details/gtqukvoirf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zycfv.cn/Article/details/gtgpyufiko.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jianghu66.top/Article/details/gtnghmtyjb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gtpmzwsorb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gtnhbatxnf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.pengpengdd.cyou/Article/details/gtjhmlairr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gaohongyu789.top/Article/details/gtwmktfkmz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.aizwys.cn/Article/details/gtsckqyrra.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.feifeiyinyue.top/Article/details/gtjjfvjpyz.html

[L05] 上传文件（multipart）
来源：http://dali.zycfv.cn/Article/details/gtzzbdnqyf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shanyushiyangtech.top/Article/details/gtmobucsia.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cqqwz.cn/Article/details/gthyhnyhzf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cqqwz.cn/Article/details/gtejfjictg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.fengsongda.top/Article/details/gtcsyapfdg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gogol.net.cn/Article/details/gtbugyzcgp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.redwolf501.top/Article/details/gtpebsidfj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xylfe.cn/Article/details/gtibkjygvq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtqvrfjlsk.html

[L06] 解析响应为 JSON
来源：http://dali.xinyue.icu/Article/details/gtsbgvesya.html

Py:   resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gtilscribn.html

PHP:  json_decode($body, true);
来源：http://dali.316326.xyz/Article/details/gtqmhmshta.html

JS:   await resp.json()
来源：http://dali.xuanzx.com/Article/details/gtoeeqrsvf.html

TS:   await resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gtlvocdjfa.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtublhzfqt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhongyouzk.top/Article/details/gtqxsycaog.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gzhubu.top/Article/details/gtzzfsisxh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhixingplan.top/Article/details/gtenrpbboy.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gttzmymnne.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.9152youxi.cn/Article/details/gttapmwegk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nwbrower.top/Article/details/gtffrwtfoq.html

JS:   resp.ok;  resp.status
来源：http://dali.haohaochexian.top/Article/details/gtdlqomwww.html

TS:   resp.ok;  resp.status
来源：http://dali.xziqi.cn/Article/details/gtaxctlvpn.html

Java: resp.statusCode()
来源：http://dali.guannengcc.top/Article/details/gtxdfqbagb.html

Go:   resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gtbvthraqa.html

Ruby: resp.code.to_i
来源：http://dali.hammf.cn/Article/details/gtwtybjdfb.html

C#:   (int)resp.StatusCode
来源：http://dali.yuanzhike.top/Article/details/gtavuottmw.html

[L08] 并发请求多个地址
来源：http://dali.ppjwa.cn/Article/details/gtgjqmsuel.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhengqikj.top/Article/details/gtwextlnfr.html

PHP:  curl_multi_init() 系列
来源：http://dali.bjfxy.top/Article/details/gtmfhkroar.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gtcytoydqn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tianlin.xyz/Article/details/gtiocvkomt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yvedp.cn/Article/details/gthysfxgkq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sweek.top/Article/details/gtqtkfhzmn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sufxvd.cn/Article/details/gtpvkalhlu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenlongwang.top/Article/details/gtdjwvwefb.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtijnuveco.html

M. 命令行 / 进程 / 环境
来源：http://dali.guowangkeji.top/Article/details/gtpqxoltvg.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtnhmshlhm.html

[M01] 读取命令行参数
来源：http://dali.yuanzhike.top/Article/details/gtptatunsq.html

Py:   sys.argv[1:]
来源：http://dali.sysykeji.top/Article/details/gtkvrizkwe.html

PHP:  $argv;  $argc;
来源：http://dali.gaohongyu789.top/Article/details/gtpavtcqry.html

JS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gtngcskwbn.html

TS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gtkhrmwcpf.html

Java: args 数组（main 方法参数）
来源：http://dali.ppjwa.cn/Article/details/gtctcxzogf.html

Go:   os.Args[1:]
来源：http://dali.chenlongwang.top/Article/details/gtytexehiz.html

Ruby: ARGV
来源：http://dali.guannengcc.top/Article/details/gtsobpgxfb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hywenlv.cn/Article/details/gtstcfsoak.html

[M02] 读取环境变量
来源：http://dali.xuanzx.com/Article/details/gtqcxwqino.html

Py:   os.environ.get("HOME")
来源：http://dali.yj202588.top/Article/details/gtggibcjoo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gtgpipjqlm.html

JS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gtqjonypyy.html

TS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gtyrkwbtxy.html

Java: System.getenv("HOME")
来源：http://dali.daria6918.cn/Article/details/gtdqbqokpv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxmvtlmv.html

Ruby: ENV["HOME"]
来源：http://dali.nwbrower.top/Article/details/gtwclkyrkq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtqgamztxl.html

[M03] 执行外部命令
来源：http://dali.wangshuangyany.cn/Article/details/gtratrfsob.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.316326.xyz/Article/details/gtnvorfpfw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.smart0.xyz/Article/details/gtboamboox.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigfzy.top/Article/details/gtusuuafzx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gtqebvafwz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cdnleiting.top/Article/details/gtntncmuxj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvyjgeass.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhongyouzk.top/Article/details/gthtbstcdv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aizwys.cn/Article/details/gtlffkryih.html

[M04] 获取当前工作目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyylgdhpa.html

Py:   os.getcwd()
来源：http://dali.jlsjyb.cn/Article/details/gtnxanckid.html

PHP:  getcwd();
来源：http://dali.yj202588.top/Article/details/gtdfawgyoj.html

JS:   process.cwd()
来源：http://dali.jiagoushi.top/Article/details/gtbfvvevvz.html

TS:   process.cwd()
来源：http://dali.fengsongda.top/Article/details/gtzfmhftxg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.redwolf501.top/Article/details/gtpmpxzjov.html

Go:   os.Getwd()
来源：http://dali.nwbrower.top/Article/details/gtqgecmlqp.html

Ruby: Dir.pwd
来源：http://dali.jyoumei.cn/Article/details/gtlqguwjij.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yonumen.top/Article/details/gtkolemkqu.html

[M05] 设置退出码
来源：http://dali.pengpengdd.cyou/Article/details/gtnqcfssmh.html

Py:   sys.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtujginwgz.html

PHP:  exit(1);
来源：http://dali.jqgfzy.top/Article/details/gtwbipmdwx.html

JS:   process.exit(1)
来源：http://dali.jianghu66.top/Article/details/gteutqixnu.html

TS:   process.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtbqkxwkzr.html

Java: System.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtlamivjlf.html

Go:   os.Exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxrdqagh.html

Ruby: exit 1
来源：http://dali.gaohongyu789.top/Article/details/gthkvquzba.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hammf.cn/Article/details/gtnhvwbpjf.html

[M06] 向标准错误输出
来源：http://dali.jinqigufen.top/Article/details/gtgubounuu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yvedp.cn/Article/details/gthzwpjtfx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhongyouzk.top/Article/details/gtirtjlpwy.html

JS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gthkbdpjew.html

TS:   console.error("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkflubnhi.html

Java: System.err.println("err")
来源：http://dali.nanxuanxn.top/Article/details/gtparfjsxm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jqgufenzy.top/Article/details/gtgietlxae.html

Ruby: warn "err"
来源：http://dali.sysykeji.top/Article/details/gtctliqtpi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gtqnroyhex.html

[M07] 判断是否为主入口
来源：http://dali.sweek.top/Article/details/gtdqnexohj.html

Py:   if __name__ == "__main__":
来源：http://dali.hnqzz.top/Article/details/gttuikbbaj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxuanxn.top/Article/details/gtqmvtirrp.html

JS:   require.main === module
来源：http://dali.svipenyu.cn/Article/details/gtfanmoizx.html

TS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gtolqgfvhg.html

Java: public static void main(String[] args)
来源：http://dali.yj20258888.top/Article/details/gtudgodmzh.html

Go:   func main()
来源：http://dali.fzhhl.top/Article/details/gttnbrnryt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj202588.top/Article/details/gttmwmmzfq.html

C#:   static void Main(string[] args)
来源：http://dali.guannengcc.top/Article/details/gtfzclraud.html

[M08] 获取系统与运行时信息
来源：http://dali.iojbl.cn/Article/details/gtwyidhyyq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cheryme.top/Article/details/gtixnvdxvf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jlsjyb.cn/Article/details/gtkgeqfhgm.html

JS:   process.platform;  process.version
来源：http://dali.meibo888.top/Article/details/gtvucgslgf.html

TS:   process.platform;  process.version
来源：http://dali.cucudq.cn/Article/details/gtttfixxdh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shuidangran.top/Article/details/gtucfmppzw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszextxkz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nanxinkj.top/Article/details/gteibvqqwd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuanzx.com/Article/details/gtslpwovzd.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtddpyazfq.html

N. 数据结构与算法
来源：http://dali.dashuyun.cn/Article/details/gtevrczxtp.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtqstyjmuv.html

[N01] 二分查找（有序数组）
来源：http://dali.pycfn.com/Article/details/gteupxphss.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.pycfn.com/Article/details/gttyrmwwpo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gtzmpmjwqa.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gtgixonudm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fzhhl.top/Article/details/gtvhrxznvb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtaqrbdrji.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtjosyvsca.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zdqjudy.top/Article/details/gtnsokkhuy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtevthatdl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tanke756.top/Article/details/gtfhlckcfe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zdqjudy.top/Article/details/gtfonmvrib.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nanxuanxn.top/Article/details/gtzpqkvvpo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gtzvjgellb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gttuxbggcn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yvedp.cn/Article/details/gtqmzjwrae.html

Go:   slices.Sort(arr)
来源：http://dali.pycfn.com/Article/details/gtnaslfczy.html

Ruby: arr.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gtllweurew.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hnxiangtu.top/Article/details/gtbzvpqpnp.html

[N03] 快速排序（分治示例）
来源：http://dali.zhengqikj.top/Article/details/gtgacwwwku.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jianghu66.top/Article/details/gthosaofkp.html


<!-- 参考信息 -->