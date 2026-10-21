代发 wailian999

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.quarkkingdee.top/Article/details/gtdujlwovs.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yanxiufei.cn/Article/details/gtbqzjvnco.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jianghu66.top/Article/details/gtwfiyvedc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.wangdashe.top/Article/details/gtanyyxikj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nwbrower.top/Article/details/gtfkoopuqo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.wangshuangyany.cn/Article/details/gtouonqwdb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhiwuduotai.top/Article/details/gtzqbqwsbw.html

[J06] 计算两时间之差
来源：http://dali.yuanzhike.top/Article/details/gtjpkzcnva.html

Py:   (end - start).total_seconds()
来源：http://dali.ivvv.top/Article/details/gtvevomgwf.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhengqikj.top/Article/details/gtcuxrpffj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrthlngna.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ydzc1.top/Article/details/gtpvestcsk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.vqdsnc.cn/Article/details/gtzfhwbrdi.html

Go:   end.Sub(start).Hours()
来源：http://dali.ybcxt.top/Article/details/gtmikhmdtp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.quarkkingdee.top/Article/details/gtzrdigozx.html

C#:   (end - start).TotalSeconds
来源：http://dali.redwolf501.top/Article/details/gtjyftbgbm.html

[J07] 比较两个日期
来源：http://dali.smart0.xyz/Article/details/gtlmfgegey.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gtrfepsvov.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xinyue.icu/Article/details/gtaauftfzf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aibaodan.cn/Article/details/gtxpdxteok.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daxiang520.top/Article/details/gtnkwcegbk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yongpay.top/Article/details/gtquayebxu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuanzhike.top/Article/details/gtkdjomeoo.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gtqowknuxb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gtsuptvxms.html

[J08] 提取年月日与星期
来源：http://dali.bjfxy.top/Article/details/gtbluyjjbt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yongpay.top/Article/details/gtsgkwwjyx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shangyingyoupin.top/Article/details/gthgkdhpbt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrucrveq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yuanzhike.top/Article/details/gtgpchunmn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gtlltqwriv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hywenlv.cn/Article/details/gtzglgrmyr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fengsongda.top/Article/details/gtqnqyrsne.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgtiwvvxp.html

[J09] 时区处理
来源：http://dali.quarkkingdee.top/Article/details/gtrugpepha.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gotoacloud.top/Article/details/gtwsmqbzmo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jiagoushi.top/Article/details/gtdnlpacpo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gtuxzgodlw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenjidiqi.icu/Article/details/gtkkrbhzvh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fzhhl.top/Article/details/gtcnbrgomi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hnxiangtu.top/Article/details/gtkogevqhe.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jiagoushi.top/Article/details/gtyanlwwry.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.wangdashe.top/Article/details/gtbajdabuz.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinghuilouyu.cn/Article/details/gtzgibrljn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.havefunace.top/Article/details/gtbckclhkn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.feifeiyinyue.top/Article/details/gtzmxdbtmz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cheryme.top/Article/details/gtdloluifw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.andypj.xyz/Article/details/gthwqnxpvp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jyoumei.cn/Article/details/gtaylalepq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.andypj.xyz/Article/details/gtocmajgzx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.316326.xyz/Article/details/gtjppswgda.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cdnleiting.top/Article/details/gtzmbgglui.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtmmawmsjp.html

K. JSON 与序列化
来源：http://dali.ehwqpu.com/Article/details/gtxjaqgoxw.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtawnvcqds.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinqigfzy.top/Article/details/gtlunfdrvd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hysaishi.cn/Article/details/gtpwxqmwiv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gtsqeupokf.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtoqmtiiln.html

TS:   JSON.stringify(obj)
来源：http://dali.gzhubu.top/Article/details/gttmbggggm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.9152youxi.cn/Article/details/gtswnkfaek.html

Go:   json.Marshal(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtvjqhepht.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yongpay.top/Article/details/gtetqjpoks.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guannengcc.top/Article/details/gtqhhbgrps.html

[K02] JSON 字符串转对象
来源：http://dali.shangyingyoupin.top/Article/details/gtyqmwanrc.html

Py:   json.loads(s)
来源：http://dali.hywenlv.cn/Article/details/gtyahnojnd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.daria6918.cn/Article/details/gtyrzgstvf.html

JS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gtkxxlkouy.html

TS:   JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gtmskatgia.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtjkdzipgw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj20258888.top/Article/details/gtynlpczuu.html

Ruby: JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gtfpkhgprn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258888.top/Article/details/gtxejbcsxf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hongshengwenyu.top/Article/details/gtuhdqtarx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmrpyevjf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtftyrfjwq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhixingplan.top/Article/details/gttywpfltp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.0kj1m.cn/Article/details/gthhgdogea.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsuqqdxqs.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nwbrower.top/Article/details/gtilxjgqfh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xylfe.cn/Article/details/gtelskmsaf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gaohongyu789.top/Article/details/gtpxeqitko.html

[K04] 读取 JSON 文件
来源：http://dali.nanxuanxn.top/Article/details/gtqxzgboqk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.fengsongda.top/Article/details/gtifrzgswb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nanxinkj.top/Article/details/gtnrgdtehc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hysaishi.cn/Article/details/gtnvhxedvi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gtolnfbovr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gtqslqjnxm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gtdagnjvoo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hfpthk.cn/Article/details/gtuqvuiunn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj20258.top/Article/details/gtpyhasczp.html

[K05] 深拷贝对象
来源：http://dali.xylfe.cn/Article/details/gtjhkmkwxj.html

Py:   copy.deepcopy(obj)
来源：http://dali.zycfv.cn/Article/details/gticgmodrd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yuxming.cn/Article/details/gtoojmnvmh.html

JS:   structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gtvltbhqff.html

TS:   structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gtfuxorabm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hywenlv.cn/Article/details/gtubfqiqio.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.havefunace.top/Article/details/gtuizoklfq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhoulong.xyz/Article/details/gtxlklwnha.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jqgfzy.top/Article/details/gtczxvaeuz.html

[K06] 解析 URL 查询串
来源：http://dali.zhaomingkeji.xyz/Article/details/gttenenczw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gtcncviwkb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.kuanghao11.cn/Article/details/gtrpjqsmmy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gtjfphzhnz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.iojbl.cn/Article/details/gtdgupripe.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinqigfzy.top/Article/details/gthuzstjpn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtakartpmd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gtqohzloey.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gtgxiuserx.html

[K07] 进制转换
来源：http://dali.shuidangran.top/Article/details/gtkmkowlux.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtlkzoykmv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.feifeiyinyue.top/Article/details/gtablmboci.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtizxyedpq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtzrxdeqlu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtyfqinmys.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ybcxt.top/Article/details/gtofelstxa.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dashuyun.cn/Article/details/gtyqdxwhxy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiqnvoszw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nanxuanxn.top/Article/details/gtcezvvzvq.html

Py:   pickle.dumps(obj)
来源：http://dali.zdqjudy.top/Article/details/gttdgyckvk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nanxuanxn.top/Article/details/gtsmmuxrlf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gtlckrkjtv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tianlin.xyz/Article/details/gtyxtufmnz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuetiantiany.cn/Article/details/gtluhvloxk.html

Go:   encoding/gob
来源：http://dali.ivvv.top/Article/details/gtgimvxlcn.html

Ruby: Marshal.dump(obj)
来源：http://dali.haohaochexian.top/Article/details/gtlveibhad.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zycfv.cn/Article/details/gtwwdshpqn.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtdxvbfxbe.html

L. 网络请求
来源：http://dali.jyoumei.cn/Article/details/gtsmqwftna.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtswsowskx.html

[L01] 发送 GET 请求
来源：http://dali.ppjwa.cn/Article/details/gtasqkdkyl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hongshengwenyu.top/Article/details/gtzuwcylcz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.aibaodan.cn/Article/details/gtkapfjujo.html

JS:   await fetch(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsbcknrze.html

TS:   await fetch(url)
来源：http://dali.xziqi.cn/Article/details/gtmybyxgds.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhengqikj.top/Article/details/gtfvxweloz.html

Go:   resp, err := http.Get(url)
来源：http://dali.tian-w.cn/Article/details/gtwyesbpuy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yongpay.top/Article/details/gtfikmgqfn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gaohongyu789.top/Article/details/gtpovddchf.html

[L02] 发送 POST JSON
来源：http://dali.xinyue.icu/Article/details/gtmqwlbcfj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258888.top/Article/details/gtwumrxmbp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jiagoushi.top/Article/details/gttskifdrl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gtsxugytkh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gtcszxadml.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cashguo.top/Article/details/gtiavvzrgz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.birdmap.top/Article/details/gtubgvnayg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.iojbl.cn/Article/details/gtssyckzfu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yangfankeji.com/Article/details/gtlcynuamg.html

[L03] 设置自定义请求头
来源：http://dali.zdqjudy.top/Article/details/gtjskmhlqn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gaohongyu789.top/Article/details/gtzlefbncm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.bjfxy.top/Article/details/gtuhhdfnop.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gtwxdviohq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xinyue.icu/Article/details/gthppixbcs.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shzxlz.cn/Article/details/gtfujbophu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hywenlv.cn/Article/details/gtbuqajmuj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hysaishi.cn/Article/details/gteioqudcz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbzldsdi.html

[L04] 设置超时
来源：http://dali.hfpthk.cn/Article/details/gtgxfogygw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shzxlz.cn/Article/details/gtskdzynsb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.316326.xyz/Article/details/gtveuegwsl.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gtnhghfbas.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fengsongda.top/Article/details/gtztvrkljz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yongpay.top/Article/details/gtpvxwpjgf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xinyue.icu/Article/details/gtvibsqcco.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cheryme.top/Article/details/gtusigzugk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.redwolf501.top/Article/details/gtwcagotwo.html

[L05] 上传文件（multipart）
来源：http://dali.cashguo.top/Article/details/gtublddwyx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.dianchejie.cn/Article/details/gtnjahvnuo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.c1oappe.top/Article/details/gtkhmbdyis.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sysykeji.top/Article/details/gtwgzjiixp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gthmuudapr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xuetiantiany.cn/Article/details/gtqeccxdju.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sysykeji.top/Article/details/gtldnaserz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yvedp.cn/Article/details/gthstmccvo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtrgpjxqmq.html

[L06] 解析响应为 JSON
来源：http://dali.hnxiangtu.top/Article/details/gtdpjmnssw.html

Py:   resp.json()
来源：http://dali.zhengqikj.top/Article/details/gtlflffrkp.html

PHP:  json_decode($body, true);
来源：http://dali.zycfv.cn/Article/details/gtvxrqypun.html

JS:   await resp.json()
来源：http://dali.jyoumei.cn/Article/details/gtovrqbwdl.html

TS:   await resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gtqbveoqvl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.fzhhl.top/Article/details/gtnlchbhow.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhengqikj.top/Article/details/gtrsgbhnoy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.wangshuangyany.cn/Article/details/gtqtmfgxuf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigufen.top/Article/details/gtznsbamji.html

[L07] 处理 HTTP 状态码
来源：http://dali.iojbl.cn/Article/details/gtpabgwhsr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nanxinkj.top/Article/details/gttxmdraqk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zdqjudy.top/Article/details/gtetqvzdky.html

JS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gtihvjufwe.html

TS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gtlwdfdzcb.html

Java: resp.statusCode()
来源：http://dali.yuanzhike.top/Article/details/gtuoryqfld.html

Go:   resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gtbaswbayd.html

Ruby: resp.code.to_i
来源：http://dali.xuetiantiany.cn/Article/details/gtavndggdi.html

C#:   (int)resp.StatusCode
来源：http://dali.snrcjt.cn/Article/details/gtuxsehwci.html

[L08] 并发请求多个地址
来源：http://dali.ydzc1.top/Article/details/gtomdlfzpb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.andypj.xyz/Article/details/gtzysbrvpo.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj20258888.top/Article/details/gtmigbkjrs.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtburaqrup.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gtusilbdaw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jyoumei.cn/Article/details/gtroyiwodk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenlongwang.top/Article/details/gtkktbrvta.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.birdmap.top/Article/details/gtcqlkkpnw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sysykeji.top/Article/details/gtflcgpzed.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtauphutya.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhongyouzk.top/Article/details/gtoumjtqwc.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqaxbrpwi.html

[M01] 读取命令行参数
来源：http://dali.hammf.cn/Article/details/gtxgxozixi.html

Py:   sys.argv[1:]
来源：http://dali.dashuyun.cn/Article/details/gtjwuotzsm.html

PHP:  $argv;  $argc;
来源：http://dali.gzhubu.top/Article/details/gtbbwglbse.html

JS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gtxoqcgdje.html

TS:   process.argv.slice(2)
来源：http://dali.aizwys.cn/Article/details/gtvzeavahk.html

Java: args 数组（main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gtqpuwzguo.html

Go:   os.Args[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gtplusthir.html

Ruby: ARGV
来源：http://dali.316326.xyz/Article/details/gtryojnsyx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.dianchejie.cn/Article/details/gtpjpgssdt.html

[M02] 读取环境变量
来源：http://dali.tianlin.xyz/Article/details/gtmjqugjrz.html

Py:   os.environ.get("HOME")
来源：http://dali.c1oappe.top/Article/details/gtjtqrtoiv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hysaishi.cn/Article/details/gtngimxoyk.html

JS:   process.env.HOME
来源：http://dali.jyoumei.cn/Article/details/gtobexdimr.html

TS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gtrltcirku.html

Java: System.getenv("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtvscvslzz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtkxapqmar.html

Ruby: ENV["HOME"]
来源：http://dali.0kj1m.cn/Article/details/gtyemxvkji.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yvedp.cn/Article/details/gtudgqufle.html

[M03] 执行外部命令
来源：http://dali.meibo888.top/Article/details/gtprsgzomt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xinyue.icu/Article/details/gttykvudzl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gogol.net.cn/Article/details/gtyletwjra.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nwbrower.top/Article/details/gtdmzibqwo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gtnvyeqdea.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ybcxt.top/Article/details/gtuxdlvjnh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.vqdsnc.cn/Article/details/gtqhcbshml.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sweek.top/Article/details/gtrdkmyamn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ppjwa.cn/Article/details/gtbsxizxmf.html

[M04] 获取当前工作目录
来源：http://dali.shzxlz.cn/Article/details/gtkrpkjhzv.html

Py:   os.getcwd()
来源：http://dali.snrcjt.cn/Article/details/gtffmmmmrj.html

PHP:  getcwd();
来源：http://dali.jiagoushi.top/Article/details/gtdosabbvt.html

JS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gtijybrlvf.html

TS:   process.cwd()
来源：http://dali.jqgufenzy.top/Article/details/gtedhplwir.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.daxiang520.top/Article/details/gthpvzaxmw.html

Go:   os.Getwd()
来源：http://dali.havefunace.top/Article/details/gtejqjybnd.html

Ruby: Dir.pwd
来源：http://dali.yuxming.cn/Article/details/gtgdivytrq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenjidiqi.icu/Article/details/gtycabpqdn.html

[M05] 设置退出码
来源：http://dali.zhoulong.xyz/Article/details/gtprbewuom.html

Py:   sys.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtchclavak.html

PHP:  exit(1);
来源：http://dali.redwolf501.top/Article/details/gtrvnmtpoe.html

JS:   process.exit(1)
来源：http://dali.yj20258888.top/Article/details/gtfyzedyep.html

TS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtihdiou.html

Java: System.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtwmzbgzbz.html

Go:   os.Exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfwowtblp.html

Ruby: exit 1
来源：http://dali.iojbl.cn/Article/details/gtvsjsooik.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hnxiangtu.top/Article/details/gtcukaezbx.html

[M06] 向标准错误输出
来源：http://dali.feifeiyinyue.top/Article/details/gtqvtifrhk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhoulong.xyz/Article/details/gtmxdvyiwf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tanke756.top/Article/details/gtjgzfiunp.html

JS:   console.error("err")
来源：http://dali.cheryme.top/Article/details/gtfkiiaapu.html

TS:   console.error("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjkdpcoyu.html

Java: System.err.println("err")
来源：http://dali.yuanzhike.top/Article/details/gtvqkwezst.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xinyue.icu/Article/details/gtuxqtlllu.html

Ruby: warn "err"
来源：http://dali.svipenyu.cn/Article/details/gtkpzkzegu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cheryme.top/Article/details/gtrfmnvggf.html

[M07] 判断是否为主入口
来源：http://dali.zhengqikj.top/Article/details/gtaxwvtdwp.html

Py:   if __name__ == "__main__":
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzsphbnv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cucudq.cn/Article/details/gtjtrxfexa.html

JS:   require.main === module
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvpadnfmf.html

TS:   require.main === module
来源：http://dali.ydzc1.top/Article/details/gttgdvlauv.html

Java: public static void main(String[] args)
来源：http://dali.zdqjudy.top/Article/details/gttkeofzpn.html

Go:   func main()
来源：http://dali.svipenyu.cn/Article/details/gtvbkpjznd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.andypj.xyz/Article/details/gtklvbygds.html

C#:   static void Main(string[] args)
来源：http://dali.xinyue.icu/Article/details/gtvxtjguom.html

[M08] 获取系统与运行时信息
来源：http://dali.quarkkingdee.top/Article/details/gtrkgiycan.html

Py:   platform.system();  platform.python_version()
来源：http://dali.meibo888.top/Article/details/gtbnbeboez.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sweek.top/Article/details/gtozqtzcey.html

JS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gthnnspabo.html

TS:   process.platform;  process.version
来源：http://dali.gotoacloud.top/Article/details/gtjoofonlg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jiagoushi.top/Article/details/gtdkwmpewb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cdnleiting.top/Article/details/gtohsmweod.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.quarkkingdee.top/Article/details/gtojwsgovx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ydzc1.top/Article/details/gtvkixggrs.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtvbibndcb.html

N. 数据结构与算法
来源：http://dali.shangyingyoupin.top/Article/details/gtkrzawjuh.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtscmecmgg.html

[N01] 二分查找（有序数组）
来源：http://dali.yvedp.cn/Article/details/gtflnlfhib.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtdsdgwzgd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cashguo.top/Article/details/gtwxckgchi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dianchejie.cn/Article/details/gtzfkqgsib.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ppjwa.cn/Article/details/gtanwsoeql.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtzxvzelhk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtzddroqad.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.iojbl.cn/Article/details/gtvhmarvod.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.316326.xyz/Article/details/gtcdavdakd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yvedp.cn/Article/details/gtkpyvarvn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.mhx1999.top/Article/details/gteohyzeua.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenlongwang.top/Article/details/gtatapneww.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gtkjxvsqra.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gtfwlrsauz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj20258888.top/Article/details/gtmlwpcioc.html

Go:   slices.Sort(arr)
来源：http://dali.pycfn.com/Article/details/gtoomicmpe.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtpcbehdye.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuetiantiany.cn/Article/details/gthqzbvxql.html

[N03] 快速排序（分治示例）
来源：http://dali.bjfxy.top/Article/details/gtwwdlcfyk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cdnleiting.top/Article/details/gtwqzycaxb.html


<!-- 参考信息 -->