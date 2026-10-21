代发 wailian999

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj20258888.top/Article/details/gtxphpdnfe.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gogol.net.cn/Article/details/gtjhowsyru.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenlongwang.top/Article/details/gtigpfcbbw.html

Py:   now + timedelta(days=7)
来源：http://dali.shangyingyoupin.top/Article/details/gthexeiisy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.havefunace.top/Article/details/gtonwpghbm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmcqqicto.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fengsongda.top/Article/details/gtfvofoikj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cheryme.top/Article/details/gtshhaabvo.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.smart0.xyz/Article/details/gtlmgebogz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tianlin.xyz/Article/details/gtrwotjwiw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dashuyun.cn/Article/details/gthpwkezkj.html

[J06] 计算两时间之差
来源：http://dali.gzhubu.top/Article/details/gtlvwfgwoz.html

Py:   (end - start).total_seconds()
来源：http://dali.aibaodan.cn/Article/details/gttuhpygkr.html

PHP:  $end->diff($start)->days;
来源：http://dali.yonumen.top/Article/details/gtjglhpqrr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.bjfxy.top/Article/details/gtwdwbfncv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cheryme.top/Article/details/gthpwiaaye.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gaohongyu789.top/Article/details/gtbkctuplf.html

Go:   end.Sub(start).Hours()
来源：http://dali.redwolf501.top/Article/details/gtczrxtbiy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gaohongyu789.top/Article/details/gtdxtnhyoo.html

C#:   (end - start).TotalSeconds
来源：http://dali.fzhhl.top/Article/details/gtkwrdonyc.html

[J07] 比较两个日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmbvrxfu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gtdurhibxa.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxinkj.top/Article/details/gtvmhqbven.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gtvipdncit.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigufen.top/Article/details/gtrskmieiv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pycfn.com/Article/details/gtjckcpupn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yongpay.top/Article/details/gtggkkptvl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gthvcwhstg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gtnecitzup.html

[J08] 提取年月日与星期
来源：http://dali.sweek.top/Article/details/gtnwhxrrjq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ppjwa.cn/Article/details/gtmoumibkb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sysykeji.top/Article/details/gtahglnvvb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.smart0.xyz/Article/details/gttfdrmcoo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtymowlmta.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdatjyfug.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhengqikj.top/Article/details/gtqucdbaoz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gotoacloud.top/Article/details/gtfofqkoee.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sysykeji.top/Article/details/gtsemsilmk.html

[J09] 时区处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzazzliz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cdnleiting.top/Article/details/gtccvzdqce.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yvedp.cn/Article/details/gtkttuoeor.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xylfe.cn/Article/details/gtdxjdduxa.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gtecdvuvzc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guowangkeji.top/Article/details/gtntskticf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.dashuyun.cn/Article/details/gtcfpgcabh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxuanxn.top/Article/details/gtkmsupwnm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinqigfzy.top/Article/details/gtgpeinjai.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinghuilouyu.cn/Article/details/gtuofazfsm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlzbcfqrg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.quarkkingdee.top/Article/details/gtpdsqovyx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sweek.top/Article/details/gtfpfcygfc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xziqi.cn/Article/details/gtxnffbxmx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dianchejie.cn/Article/details/gtpsybrjkh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.vqdsnc.cn/Article/details/gtqoaylkhy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cheryme.top/Article/details/gtsvzhfbqv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjutmioib.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtqcgywney.html

K. JSON 与序列化
来源：http://dali.aizwys.cn/Article/details/gtqisufddh.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfvbdbmzd.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangdashe.top/Article/details/gtdezrqtbe.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xylfe.cn/Article/details/gtltjekceu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhengqikj.top/Article/details/gtsqyfvfzf.html

JS:   JSON.stringify(obj)
来源：http://dali.daria6918.cn/Article/details/gtolzgqfzu.html

TS:   JSON.stringify(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthowuetck.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenlongwang.top/Article/details/gtrbhyvvyh.html

Go:   json.Marshal(obj)
来源：http://dali.haohaochexian.top/Article/details/gtkrntfjtv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gaohongyu789.top/Article/details/gtirnxuedn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnqzz.top/Article/details/gtorxdyovd.html

[K02] JSON 字符串转对象
来源：http://dali.redwolf501.top/Article/details/gtlrchpzok.html

Py:   json.loads(s)
来源：http://dali.hysaishi.cn/Article/details/gtudqotffa.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.quarkkingdee.top/Article/details/gtmqxomrqr.html

JS:   JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gtxjmsbrnp.html

TS:   JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gtppzdmznm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yuxming.cn/Article/details/gtnicxhjkm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jlsjyb.cn/Article/details/gtjynfwnig.html

Ruby: JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gtswlplezz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tian-w.cn/Article/details/gtfpyxduur.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hnxiangtu.top/Article/details/gttbllodzb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gtutlyopyr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.daria6918.cn/Article/details/gtukfhdwlo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sweek.top/Article/details/gtyrfvmxws.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gttshcywcx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zdqjudy.top/Article/details/gtdseooaah.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shuidangran.top/Article/details/gtnqdlfgmv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xinyue.icu/Article/details/gttcqqccex.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.birdmap.top/Article/details/gtbsziznqt.html

[K04] 读取 JSON 文件
来源：http://dali.hongshengwenyu.top/Article/details/gtoczddovc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gotoacloud.top/Article/details/gtjyvuplut.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gzhubu.top/Article/details/gtljwntllv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gtomnncdyo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hfpthk.cn/Article/details/gtvpbzvcfi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.daria6918.cn/Article/details/gtivyxqyfz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehghqkuw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shangyingyoupin.top/Article/details/gttoeqgisb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.mhx1999.top/Article/details/gtsyzbpocy.html

[K05] 深拷贝对象
来源：http://dali.bjfxy.top/Article/details/gtqxrxpoza.html

Py:   copy.deepcopy(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttrquijki.html

PHP:  unserialize(serialize($obj));
来源：http://dali.vqdsnc.cn/Article/details/gtwutcsuvl.html

JS:   structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtysiesxjs.html

TS:   structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gtjzlugran.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.pengpengdd.cyou/Article/details/gtqhsgidwd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.haohaochexian.top/Article/details/gtubsvoaag.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gttzgkveri.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ppjwa.cn/Article/details/gtqiugiyfw.html

[K06] 解析 URL 查询串
来源：http://dali.xziqi.cn/Article/details/gtsxyymzvk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxnegqrr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shanyushiyangtech.top/Article/details/gteflnwbnz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtwwvanoer.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gtpkqhrufy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cqqwz.cn/Article/details/gtaotpuarp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtaitnjlxk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gtckqmebey.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gtqgkakeit.html

[K07] 进制转换
来源：http://dali.zhengqikj.top/Article/details/gtvsdctaoc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtymdtuvxt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.dianchejie.cn/Article/details/gtthqclanr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtdghphtsu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtztwddbld.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbzpwrtxk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhiwuduotai.top/Article/details/gtoojfmcrf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.aibaodan.cn/Article/details/gtstsrsqbc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtggqnympw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yonumen.top/Article/details/gttysygzoq.html

Py:   pickle.dumps(obj)
来源：http://dali.ivvv.top/Article/details/gtaxfvfrej.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ivvv.top/Article/details/gtlwjzdbym.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigufen.top/Article/details/gtovhewvqj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yuanzhike.top/Article/details/gtcocgeokx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.daria6918.cn/Article/details/gtwiztlecv.html

Go:   encoding/gob
来源：http://dali.shzxlz.cn/Article/details/gtfxybmiyk.html

Ruby: Marshal.dump(obj)
来源：http://dali.haohaochexian.top/Article/details/gtewcxuquw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gthbtrxqeh.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtdbvymcaj.html

L. 网络请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlugkpvxc.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtfockbhag.html

[L01] 发送 GET 请求
来源：http://dali.tianlin.xyz/Article/details/gtbpqyslem.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj20258.top/Article/details/gtvtisafbl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.haohaochexian.top/Article/details/gtpeovhkcj.html

JS:   await fetch(url)
来源：http://dali.yj202588.top/Article/details/gtykwarnfy.html

TS:   await fetch(url)
来源：http://dali.hnxiangtu.top/Article/details/gtejwuikqq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ivvv.top/Article/details/gtwqhtzrvd.html

Go:   resp, err := http.Get(url)
来源：http://dali.cashguo.top/Article/details/gtxevnylid.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj20258888.top/Article/details/gtdszoakjo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenjidiqi.icu/Article/details/gttohqthjo.html

[L02] 发送 POST JSON
来源：http://dali.snrcjt.cn/Article/details/gtibmdzcjb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sysykeji.top/Article/details/gthsxrcylx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.quarkkingdee.top/Article/details/gtvvlqycak.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gzhubu.top/Article/details/gtpfxnlilk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gogol.net.cn/Article/details/gtbljkpaju.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenjidiqi.icu/Article/details/gtyfxmmxmn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hnqzz.top/Article/details/gtswgckqkm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.daxiang520.top/Article/details/gtokutkefs.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrnqtqcqk.html

[L03] 设置自定义请求头
来源：http://dali.meibo888.top/Article/details/gtwypzvlew.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cdnleiting.top/Article/details/gtroopsfcb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.snrcjt.cn/Article/details/gtvxrsrlmy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daxiang520.top/Article/details/gtqcdglegr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuanzhike.top/Article/details/gtrsrxmgdc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yvedp.cn/Article/details/gtttgnfeql.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ehwqpu.com/Article/details/gtbzlpcbov.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gotoacloud.top/Article/details/gtrzcqjvmw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gtgivgzyjg.html

[L04] 设置超时
来源：http://dali.ivvv.top/Article/details/gtobdiuaoe.html

Py:   requests.get(url, timeout=5)
来源：http://dali.svipenyu.cn/Article/details/gtbirggfgc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.dianchejie.cn/Article/details/gtcowmcjxy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.feifeiyinyue.top/Article/details/gtlwonfmlk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gtkahdegkt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shzxlz.cn/Article/details/gtohrcpxoo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj20258888.top/Article/details/gtndmedizd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hfpthk.cn/Article/details/gtzjcacgct.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.c1oappe.top/Article/details/gtwjumjslw.html

[L05] 上传文件（multipart）
来源：http://dali.fzhhl.top/Article/details/gthqxjsugs.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj202588.top/Article/details/gtuitdmpcq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sysykeji.top/Article/details/gtmeazpedw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgfzy.top/Article/details/gtcfrpcsvy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jyoumei.cn/Article/details/gtogjndjmv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavevbwsp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.smart0.xyz/Article/details/gtxirpgfva.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shanyushiyangtech.top/Article/details/gteriospux.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtbsxpnaom.html

[L06] 解析响应为 JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gtugxlkzmd.html

Py:   resp.json()
来源：http://dali.gotoacloud.top/Article/details/gtjpuirnvd.html

PHP:  json_decode($body, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlvhgclg.html

JS:   await resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gthuydkfdc.html

TS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gtfagnkivd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.dianchejie.cn/Article/details/gtygxemkkm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guowangkeji.top/Article/details/gtfclnoygx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tianlin.xyz/Article/details/gtgklslrns.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenlongwang.top/Article/details/gtqhccjikl.html

[L07] 处理 HTTP 状态码
来源：http://dali.redwolf501.top/Article/details/gtbjpsfvmc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.svipenyu.cn/Article/details/gtiuhujkon.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.pycfn.com/Article/details/gtatiovodi.html

JS:   resp.ok;  resp.status
来源：http://dali.yj202588.top/Article/details/gtpdaaeqhw.html

TS:   resp.ok;  resp.status
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhnghdga.html

Java: resp.statusCode()
来源：http://dali.hongshengwenyu.top/Article/details/gtunvorlac.html

Go:   resp.StatusCode
来源：http://dali.jqgfzy.top/Article/details/gtxfnpesjx.html

Ruby: resp.code.to_i
来源：http://dali.cheryme.top/Article/details/gtcsfyrglt.html

C#:   (int)resp.StatusCode
来源：http://dali.c1oappe.top/Article/details/gtcewutipb.html

[L08] 并发请求多个地址
来源：http://dali.svipenyu.cn/Article/details/gtoivdhmse.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nwbrower.top/Article/details/gtiqxdloju.html

PHP:  curl_multi_init() 系列
来源：http://dali.birdmap.top/Article/details/gtrshcuknf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cucudq.cn/Article/details/gtzggvdzbw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.c1oappe.top/Article/details/gtveetuqas.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cashguo.top/Article/details/gtddemdvuv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.iojbl.cn/Article/details/gtefvlcvmi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gtqiojwcos.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtljmocdcg.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtttvegjbs.html

M. 命令行 / 进程 / 环境
来源：http://dali.wangshuangyany.cn/Article/details/gtkgphekxl.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtvvzzsdke.html

[M01] 读取命令行参数
来源：http://dali.smart0.xyz/Article/details/gtsszlocbt.html

Py:   sys.argv[1:]
来源：http://dali.0kj1m.cn/Article/details/gtabykheom.html

PHP:  $argv;  $argc;
来源：http://dali.hfpthk.cn/Article/details/gtwvzdghzg.html

JS:   process.argv.slice(2)
来源：http://dali.sysykeji.top/Article/details/gtiarahyjc.html

TS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gthksyjsxj.html

Java: args 数组（main 方法参数）
来源：http://dali.tian-w.cn/Article/details/gtvamsubuo.html

Go:   os.Args[1:]
来源：http://dali.jlsjyb.cn/Article/details/gtywbdrqhs.html

Ruby: ARGV
来源：http://dali.dianchejie.cn/Article/details/gtodyoznge.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gtvsvkrdqz.html

[M02] 读取环境变量
来源：http://dali.chenzaomai.com/Article/details/gturcaxuae.html

Py:   os.environ.get("HOME")
来源：http://dali.shuidangran.top/Article/details/gthkewqqio.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.guowangkeji.top/Article/details/gthklbpjyw.html

JS:   process.env.HOME
来源：http://dali.nanxinkj.top/Article/details/gtobwesirq.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gttarkmssa.html

Java: System.getenv("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtooqrydpd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtemuhhgbq.html

Ruby: ENV["HOME"]
来源：http://dali.nanxuanxn.top/Article/details/gtuygawqlp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ydzc1.top/Article/details/gthdmmcseb.html

[M03] 执行外部命令
来源：http://dali.zhengqikj.top/Article/details/gtozyeodvk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.havefunace.top/Article/details/gtrwqildoh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ehwqpu.com/Article/details/gtfhqvlcyw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gthnatwrwb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gtyouiahjn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenjidiqi.icu/Article/details/gtkuogssvs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhiwuduotai.top/Article/details/gtyjhysuxk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.havefunace.top/Article/details/gttrdkpfro.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tian-w.cn/Article/details/gtzmtwrnnv.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gtetwacygy.html

Py:   os.getcwd()
来源：http://dali.xylfe.cn/Article/details/gtrsanxjve.html

PHP:  getcwd();
来源：http://dali.gogol.net.cn/Article/details/gtwjztsfrd.html

JS:   process.cwd()
来源：http://dali.9152youxi.cn/Article/details/gtyqozdcab.html

TS:   process.cwd()
来源：http://dali.ivvv.top/Article/details/gtzcpnglzc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.kuanghao11.cn/Article/details/gtxqprgnnt.html

Go:   os.Getwd()
来源：http://dali.pycfn.com/Article/details/gtzcrbumng.html

Ruby: Dir.pwd
来源：http://dali.pycfn.com/Article/details/gtevbgobdy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.smart0.xyz/Article/details/gtlyertxqo.html

[M05] 设置退出码
来源：http://dali.sweek.top/Article/details/gtnojpevcm.html

Py:   sys.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtbwkeqoby.html

PHP:  exit(1);
来源：http://dali.zhengqikj.top/Article/details/gttrnlhvpc.html

JS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmaaqtqwb.html

TS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gtvbaahvub.html

Java: System.exit(1)
来源：http://dali.cashguo.top/Article/details/gteqimwxlp.html

Go:   os.Exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtsqxscvvo.html

Ruby: exit 1
来源：http://dali.xziqi.cn/Article/details/gthtemdult.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.redwolf501.top/Article/details/gtfszkdfju.html

[M06] 向标准错误输出
来源：http://dali.tian-w.cn/Article/details/gtshpzqokf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nwbrower.top/Article/details/gtgscejdwa.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gtgeezqcfv.html

JS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gtydxzjded.html

TS:   console.error("err")
来源：http://dali.yongpay.top/Article/details/gtluvshrgo.html

Java: System.err.println("err")
来源：http://dali.ehwqpu.com/Article/details/gtrqvdpnju.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnxiangtu.top/Article/details/gtgpcnhesi.html

Ruby: warn "err"
来源：http://dali.shzxlz.cn/Article/details/gtciezbkus.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hywenlv.cn/Article/details/gthojjlbfx.html

[M07] 判断是否为主入口
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjemqxjpy.html

Py:   if __name__ == "__main__":
来源：http://dali.hfpthk.cn/Article/details/gtqglmxgjn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.aizwys.cn/Article/details/gtkolcbwbj.html

JS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gtcuqynqoa.html

TS:   require.main === module
来源：http://dali.feifeiyinyue.top/Article/details/gtoijebmbe.html

Java: public static void main(String[] args)
来源：http://dali.mhx1999.top/Article/details/gtjcsqmkyl.html

Go:   func main()
来源：http://dali.shzxlz.cn/Article/details/gtqvcbbzkt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shangyingyoupin.top/Article/details/gtgglnwdgf.html

C#:   static void Main(string[] args)
来源：http://dali.nanxinkj.top/Article/details/gtjbqajvto.html

[M08] 获取系统与运行时信息
来源：http://dali.jlsjyb.cn/Article/details/gtnkgntscc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yvedp.cn/Article/details/gtohznsebw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhoulong.xyz/Article/details/gtormclnld.html

JS:   process.platform;  process.version
来源：http://dali.hywenlv.cn/Article/details/gtlojudemv.html

TS:   process.platform;  process.version
来源：http://dali.jqgufenzy.top/Article/details/gtmrpsfcfh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jlsjyb.cn/Article/details/gtuivscbpd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yuxming.cn/Article/details/gtxxcdyumg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hywenlv.cn/Article/details/gtrztvazqi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guannengcc.top/Article/details/gtkxkzzntn.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gttgefpmpf.html

N. 数据结构与算法
来源：http://dali.c1oappe.top/Article/details/gtlyhjxwno.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtuxwhgvsq.html

[N01] 二分查找（有序数组）
来源：http://dali.zycfv.cn/Article/details/gtdhbrhmjc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtmoyghiei.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.mhx1999.top/Article/details/gtkdrorgrq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ivvv.top/Article/details/gtsldszgkn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gtswoddfih.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtnxszfrmw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtqlytteya.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.daria6918.cn/Article/details/gthipmiugw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtlwkvluiv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.vqdsnc.cn/Article/details/gtxjkvthxd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gtoeiszisd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.bjfxy.top/Article/details/gtqyoanmdc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gtcobwmcgl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.birdmap.top/Article/details/gtmqiduoiq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.daxiang520.top/Article/details/gtdwwzptne.html

Go:   slices.Sort(arr)
来源：http://dali.cashguo.top/Article/details/gtyyfctcng.html


<!-- 参考信息 -->