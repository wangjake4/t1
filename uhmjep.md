代发 wailian999

Py:   (end - start).total_seconds()
来源：http://dali.xylfe.cn/Article/details/gtyxqijuhq.html

PHP:  $end->diff($start)->days;
来源：http://dali.birdmap.top/Article/details/gtefjtzdnd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhixingplan.top/Article/details/gtqqukuugn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.feifeiyinyue.top/Article/details/gtqfyffcgt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sxryk.cn/Article/details/gtbvfhuodm.html

Go:   end.Sub(start).Hours()
来源：http://dali.nwbrower.top/Article/details/gtjiedlats.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ivvv.top/Article/details/gtltoeqblc.html

C#:   (end - start).TotalSeconds
来源：http://dali.9152youxi.cn/Article/details/gtqgiwbjof.html

[J07] 比较两个日期
来源：http://dali.cdnleiting.top/Article/details/gtxmkpxqef.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gtyaxljbgn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jiagoushi.top/Article/details/gtjuqhppvp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangtech.top/Article/details/gtnallazbc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gtpbgmtyvl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tian-w.cn/Article/details/gtzvakbgbt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhiwuduotai.top/Article/details/gtmlngjyxq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtkwodwdkj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gtylfwqzne.html

[J08] 提取年月日与星期
来源：http://dali.aizwys.cn/Article/details/gtsvsfhdhp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.meibo888.top/Article/details/gtljtlafxg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shanyushiyangtech.top/Article/details/gtcgdcidde.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzleqxobt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tianlin.xyz/Article/details/gtrpazwfjf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yonumen.top/Article/details/gtgxnzsafe.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.feifeiyinyue.top/Article/details/gthyfwbmpw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgufenzy.top/Article/details/gthrgvxmpo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxuanxn.top/Article/details/gtonnjvdjd.html

[J09] 时区处理
来源：http://dali.jyoumei.cn/Article/details/gtophmeizg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangtech.top/Article/details/gtutaubzmw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.redwolf501.top/Article/details/gtghjxuocw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xylfe.cn/Article/details/gtqkttlatk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gtuynnjbew.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyyzksdoz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenzaomai.com/Article/details/gthmawxtrl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.aizwys.cn/Article/details/gtgkynvjsf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yongpay.top/Article/details/gtdugofbmr.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmqeoomv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtabhvecjj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpuzhoarw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.guowangkeji.top/Article/details/gtjulwakhq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sysykeji.top/Article/details/gtpjjcrwio.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258888.top/Article/details/gtjtxkptuj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhoulong.xyz/Article/details/gtylwireyj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.haohaochexian.top/Article/details/gtwgmqbpzg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhoulong.xyz/Article/details/gtijjkgocg.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtvuazwsmu.html

K. JSON 与序列化
来源：http://dali.aibaodan.cn/Article/details/gttqfxhhus.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gteeqtdjqx.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbccpzicm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jqgfzy.top/Article/details/gtrlpttxps.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.c1oappe.top/Article/details/gtydmlfkhl.html

JS:   JSON.stringify(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtemkwkpfb.html

TS:   JSON.stringify(obj)
来源：http://dali.zycfv.cn/Article/details/gtnplvkgbh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gttflaskyw.html

Go:   json.Marshal(obj)
来源：http://dali.xuanzx.com/Article/details/gtiskfqnca.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jqgufenzy.top/Article/details/gtuvcpuzwm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zycfv.cn/Article/details/gtxgcefcgf.html

[K02] JSON 字符串转对象
来源：http://dali.dashuyun.cn/Article/details/gtebtzlwzw.html

Py:   json.loads(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthqibjcw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhoulong.xyz/Article/details/gtitgrugvf.html

JS:   JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gtgalsvpba.html

TS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gtdbbljpma.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gtdbsdqvpq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xuetiantiany.cn/Article/details/gtsjfqtikj.html

Ruby: JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gtwlyhovjt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.aibaodan.cn/Article/details/gtgdaaiuil.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtccyyyopb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jiagoushi.top/Article/details/gtvilwkbdq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.mhx1999.top/Article/details/gtmewjnugi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtenosntlq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.9152youxi.cn/Article/details/gtkpwbnzmj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj202588.top/Article/details/gtltpmppwq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xuetiantiany.cn/Article/details/gtqnjflets.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnqzz.top/Article/details/gtjpiipfyn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zdqjudy.top/Article/details/gthcjlkghx.html

[K04] 读取 JSON 文件
来源：http://dali.shuidangran.top/Article/details/gtegluonkr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.mhx1999.top/Article/details/gtrcophnqd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.pycfn.com/Article/details/gtovjipdan.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pengpengdd.cyou/Article/details/gtbmnoishg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jianghu66.top/Article/details/gtrjfkahdz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.snrcjt.cn/Article/details/gtpgchysqj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hnxiangtu.top/Article/details/gtbmhnaqjb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwbennls.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jlsjyb.cn/Article/details/gtudlprpsk.html

[K05] 深拷贝对象
来源：http://dali.nanxuanxn.top/Article/details/gtqsvdhnhc.html

Py:   copy.deepcopy(obj)
来源：http://dali.hywenlv.cn/Article/details/gtacyjouoc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.iojbl.cn/Article/details/gtpvbrmnsb.html

JS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtbuirpimk.html

TS:   structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gtmafpcokj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ydzc1.top/Article/details/gtgkfdsmxc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jqgufenzy.top/Article/details/gttlcmmyoo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yueranfly.top/Article/details/gtbrxsksdn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gotoacloud.top/Article/details/gthgduuvbk.html

[K06] 解析 URL 查询串
来源：http://dali.sysykeji.top/Article/details/gtzrxkdxgd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ydzc1.top/Article/details/gtvajehrlq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.haohaochexian.top/Article/details/gtwhswiwkz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gtijbdvfuy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gtygjtsvwf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sweek.top/Article/details/gtlhdqjlrt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gtbdvtepkp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gtgrohedso.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gtaryeeete.html

[K07] 进制转换
来源：http://dali.jyoumei.cn/Article/details/gtnummhvtl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtanoaxghh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.dashuyun.cn/Article/details/gtvchrqbip.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtuoirudra.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtgtzzpfdt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtonnkeztt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hywenlv.cn/Article/details/gtjxyvdgxw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yj20258.top/Article/details/gtpwomngjx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtwqtuvrml.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cqqwz.cn/Article/details/gtrlyintyu.html

Py:   pickle.dumps(obj)
来源：http://dali.guowangkeji.top/Article/details/gtnpyknibq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nwbrower.top/Article/details/gtmfitmddq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigfzy.top/Article/details/gtwazjhdfm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhixingplan.top/Article/details/gthilupzat.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxdlqhgf.html

Go:   encoding/gob
来源：http://dali.jinqigfzy.top/Article/details/gtfxlxbzjv.html

Ruby: Marshal.dump(obj)
来源：http://dali.0kj1m.cn/Article/details/gtqzavhlbr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nanxinkj.top/Article/details/gtliwxamyy.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtuwccypfy.html

L. 网络请求
来源：http://dali.jinqigfzy.top/Article/details/gtrptynodh.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtdxghgoou.html

[L01] 发送 GET 请求
来源：http://dali.yuxming.cn/Article/details/gtzdmdsmlw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.aibaodan.cn/Article/details/gtvcbnvtqi.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cucudq.cn/Article/details/gtccrthjwf.html

JS:   await fetch(url)
来源：http://dali.fzhhl.top/Article/details/gtbnrrsvro.html

TS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gtnvlyrhqn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hongshengwenyu.top/Article/details/gtrriynndr.html

Go:   resp, err := http.Get(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtxqtvcjyl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnxiangtu.top/Article/details/gtsawnxluo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.quarkkingdee.top/Article/details/gtyebufbfj.html

[L02] 发送 POST JSON
来源：http://dali.yvedp.cn/Article/details/gtxszcwsgr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.havefunace.top/Article/details/gtgsngfyix.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhoulong.xyz/Article/details/gtmcbzneve.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnxiangtu.top/Article/details/gtbmusvklc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ppjwa.cn/Article/details/gtuiejpepz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj202588.top/Article/details/gthisuoqxg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yvedp.cn/Article/details/gtvtbgaxkl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj20258.top/Article/details/gticlhrnwr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.316326.xyz/Article/details/gtsjwdwkgj.html

[L03] 设置自定义请求头
来源：http://dali.iojbl.cn/Article/details/gtsrmrhwhx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzenanonn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtcunczyab.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gotoacloud.top/Article/details/gtuctybyxc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhoulong.xyz/Article/details/gtbernjzyg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.wangdashe.top/Article/details/gtqcmwflbo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hammf.cn/Article/details/gtuqkdmynv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gaohongyu789.top/Article/details/gtglftlsmr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gtwoqijvny.html

[L04] 设置超时
来源：http://dali.sysykeji.top/Article/details/gtrimqtcyy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj202588.top/Article/details/gtuneeemcx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.c1oappe.top/Article/details/gtancsrdus.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqfywnxs.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.haohaochexian.top/Article/details/gtidwdkqyk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.wangdashe.top/Article/details/gtmzpxxgqn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.kuanghao11.cn/Article/details/gtujbemxia.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinqigufen.top/Article/details/gtggpxwvlj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daxiang520.top/Article/details/gtdihpwniv.html

[L05] 上传文件（multipart）
来源：http://dali.dashuyun.cn/Article/details/gtmmagvbja.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinqigufen.top/Article/details/gtnmobrvmj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hnxiangtu.top/Article/details/gtvreacdqi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlpbfntre.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgfzy.top/Article/details/gtaodbxnxc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.pycfn.com/Article/details/gtngzfxbcd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqhapmcf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhoulong.xyz/Article/details/gtbtjaafci.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtjyjylmwa.html

[L06] 解析响应为 JSON
来源：http://dali.meibo888.top/Article/details/gtyrxavcvb.html

Py:   resp.json()
来源：http://dali.sweek.top/Article/details/gtifpabjvy.html

PHP:  json_decode($body, true);
来源：http://dali.ybcxt.top/Article/details/gtybnwatiq.html

JS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gteuxgslou.html

TS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gtzyoimlhf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gtfqbxzpeh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.bjfxy.top/Article/details/gtnxwyittd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.316326.xyz/Article/details/gtvelarqwd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yueranfly.top/Article/details/gtlvqvzxyf.html

[L07] 处理 HTTP 状态码
来源：http://dali.hnqzz.top/Article/details/gtxpwxegae.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhengqikj.top/Article/details/gtvplbjacq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hysaishi.cn/Article/details/gtqisqbpip.html

JS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gtjusfecla.html

TS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gtgrxvzbts.html

Java: resp.statusCode()
来源：http://dali.0kj1m.cn/Article/details/gtdkbmlgjl.html

Go:   resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gtgmyatvce.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gttyzujrgo.html

C#:   (int)resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gtvzdkbfpk.html

[L08] 并发请求多个地址
来源：http://dali.andypj.xyz/Article/details/gtawildgte.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cqqwz.cn/Article/details/gtzuswsiyu.html

PHP:  curl_multi_init() 系列
来源：http://dali.jqgufenzy.top/Article/details/gtlgmchjes.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nwbrower.top/Article/details/gtmktcrsje.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gtelbjlvzu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ppjwa.cn/Article/details/gtdoshcabu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jqgfzy.top/Article/details/gtnidjbdit.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.wangdashe.top/Article/details/gtkpefrdva.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gogol.net.cn/Article/details/gtbbzeuwlj.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtoopslwtw.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigufen.top/Article/details/gtvpkfxlvk.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtbyrddfvm.html

[M01] 读取命令行参数
来源：http://dali.chenlongwang.top/Article/details/gtefyfiufy.html

Py:   sys.argv[1:]
来源：http://dali.jlsjyb.cn/Article/details/gtmsbrcwvy.html

PHP:  $argv;  $argc;
来源：http://dali.xuetiantiany.cn/Article/details/gttrujcmql.html

JS:   process.argv.slice(2)
来源：http://dali.ybcxt.top/Article/details/gthztcfcwg.html

TS:   process.argv.slice(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtkbnirymn.html

Java: args 数组（main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gtlmuiqpql.html

Go:   os.Args[1:]
来源：http://dali.dashuyun.cn/Article/details/gtidealmus.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gtrkkunoji.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sufxvd.cn/Article/details/gtwkuuydil.html

[M02] 读取环境变量
来源：http://dali.hysaishi.cn/Article/details/gtfhimnxgb.html

Py:   os.environ.get("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtqvixnjem.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gthbhbhsbv.html

JS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gtcpudxjjv.html

TS:   process.env.HOME
来源：http://dali.yuxming.cn/Article/details/gtyfwlyrei.html

Java: System.getenv("HOME")
来源：http://dali.jianghu66.top/Article/details/gtwmdwrukg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.snrcjt.cn/Article/details/gtttdvvvge.html

Ruby: ENV["HOME"]
来源：http://dali.tian-w.cn/Article/details/gtucvzmuvn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.snrcjt.cn/Article/details/gtzhyikjbq.html

[M03] 执行外部命令
来源：http://dali.yuxming.cn/Article/details/gtotpqawpw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hysaishi.cn/Article/details/gtjcnzpsxz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhiwuduotai.top/Article/details/gtcipnyatq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gtudbhqiok.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtxxpaxjst.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.pycfn.com/Article/details/gtyrklvazk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenjidiqi.icu/Article/details/gtbbyqkobp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangshuangyany.cn/Article/details/gtnuruxbuv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shzxlz.cn/Article/details/gtqqkohvtt.html

[M04] 获取当前工作目录
来源：http://dali.aizwys.cn/Article/details/gtoigikfye.html

Py:   os.getcwd()
来源：http://dali.havefunace.top/Article/details/gthzowdvts.html

PHP:  getcwd();
来源：http://dali.9152youxi.cn/Article/details/gtsjcuyzlb.html

JS:   process.cwd()
来源：http://dali.yanxiufei.cn/Article/details/gtzeoteteb.html

TS:   process.cwd()
来源：http://dali.yonumen.top/Article/details/gtbabahsmy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.iojbl.cn/Article/details/gtcafsqrgh.html

Go:   os.Getwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgipxgjoa.html

Ruby: Dir.pwd
来源：http://dali.yuanzhike.top/Article/details/gtafnggqdt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jianghu66.top/Article/details/gtbqzpxlez.html

[M05] 设置退出码
来源：http://dali.tianlin.xyz/Article/details/gtneuwavsk.html

Py:   sys.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtfhijfgnc.html

PHP:  exit(1);
来源：http://dali.yonumen.top/Article/details/gtgbctzyok.html

JS:   process.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtfaqkanjy.html

TS:   process.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtpqcaplif.html

Java: System.exit(1)
来源：http://dali.yonumen.top/Article/details/gteeczrnew.html

Go:   os.Exit(1)
来源：http://dali.yvedp.cn/Article/details/gtktuboeax.html

Ruby: exit 1
来源：http://dali.shzxlz.cn/Article/details/gtzxgxvxpg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigfzy.top/Article/details/gtaebvkirf.html

[M06] 向标准错误输出
来源：http://dali.yangfankeji.com/Article/details/gtgefewchp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuxming.cn/Article/details/gtxlbbuydq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tian-w.cn/Article/details/gtnaaczezn.html

JS:   console.error("err")
来源：http://dali.meibo888.top/Article/details/gthdwuquwh.html

TS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gtmxrsozpb.html

Java: System.err.println("err")
来源：http://dali.nanxinkj.top/Article/details/gtzqtjrtni.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jianghu66.top/Article/details/gtryplfvel.html

Ruby: warn "err"
来源：http://dali.hnqzz.top/Article/details/gtuszswqfk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yueranfly.top/Article/details/gtymsnfhce.html

[M07] 判断是否为主入口
来源：http://dali.dashuyun.cn/Article/details/gtimpvplbg.html

Py:   if __name__ == "__main__":
来源：http://dali.shzxlz.cn/Article/details/gtvttwltmq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sysykeji.top/Article/details/gtmpcspyof.html

JS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gtvgcwibep.html

TS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gtmbbaquak.html

Java: public static void main(String[] args)
来源：http://dali.vqdsnc.cn/Article/details/gtsvrcgriv.html

Go:   func main()
来源：http://dali.zhengqikj.top/Article/details/gtgakktxlj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yuxming.cn/Article/details/gtbabompsu.html

C#:   static void Main(string[] args)
来源：http://dali.c1oappe.top/Article/details/gtnnbmvewk.html

[M08] 获取系统与运行时信息
来源：http://dali.nanxinkj.top/Article/details/gtouadmxvd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yueranfly.top/Article/details/gtirevbuwf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shanyushiyangtech.top/Article/details/gtjknjslnl.html

JS:   process.platform;  process.version
来源：http://dali.fzhhl.top/Article/details/gtxrmcguxp.html

TS:   process.platform;  process.version
来源：http://dali.svipenyu.cn/Article/details/gtyhzkkesw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.svipenyu.cn/Article/details/gtckcpfwrw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinqigfzy.top/Article/details/gtiupewsov.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.feifeiyinyue.top/Article/details/gtlkyrvicj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.meibo888.top/Article/details/gtsebkvjvv.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtvzenzirf.html

N. 数据结构与算法
来源：http://dali.dashuyun.cn/Article/details/gtugpsycry.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtsmihlvax.html

[N01] 二分查找（有序数组）
来源：http://dali.feifeiyinyue.top/Article/details/gtiazuoorv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgncxpgce.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.mhx1999.top/Article/details/gtxnsuoujx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gtyxezjrwp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258888.top/Article/details/gtxxcaomxp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtgopnevfz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ivvv.top/Article/details/gtrvuyauyx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimxkekpq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtukucqxsr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgfzy.top/Article/details/gtvjmnvjsp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daxiang520.top/Article/details/gtkqnlzsum.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.haohaochexian.top/Article/details/gtfjmqcgrp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gtkqmvpmku.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gtselmcnov.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shuidangran.top/Article/details/gtblwvdycj.html

Go:   slices.Sort(arr)
来源：http://dali.ydzc1.top/Article/details/gtxfawdrmu.html

Ruby: arr.sort
来源：http://dali.yuanzhike.top/Article/details/gtaxjpwrgo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yuxming.cn/Article/details/gtanktmljp.html

[N03] 快速排序（分治示例）
来源：http://dali.ybcxt.top/Article/details/gtybzqtbsj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gogol.net.cn/Article/details/gtnbfzkskq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.snrcjt.cn/Article/details/gtvnvtobve.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigfzy.top/Article/details/gtgytepplf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinghuilouyu.cn/Article/details/gtxioervad.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltrpxawc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenzaomai.com/Article/details/gtwyjinmqk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xinyue.icu/Article/details/gtlxsmrevf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jqgufenzy.top/Article/details/gtfzexujsp.html

[N04] 斐波那契数列
来源：http://dali.dashuyun.cn/Article/details/gtrrohofoe.html


<!-- 参考信息 -->