代发 wailian999

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cashguo.top/Article/details/gtmhpgvlyy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xuanzx.com/Article/details/gtbnixjmsi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.bjfxy.top/Article/details/gtmsndvyxp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xziqi.cn/Article/details/gtzdlimeld.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.dashuyun.cn/Article/details/gtrrcujxxe.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hfpthk.cn/Article/details/gtftjrsvqq.html

[J09] 时区处理
来源：http://dali.cheryme.top/Article/details/gtgtdimqih.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tian-w.cn/Article/details/gtojbbigsj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdkaqnoxd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fengsongda.top/Article/details/gtcvskhylb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gtizmvlkfb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daxiang520.top/Article/details/gtrvufsgeb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xuetiantiany.cn/Article/details/gtgmvzkhwv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopiybpct.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.svipenyu.cn/Article/details/gtoiedxigb.html

[J10] 取今天 / 本月第一天
来源：http://dali.daxiang520.top/Article/details/gtbxxvsiqo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.fzhhl.top/Article/details/gtwlhmqpet.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cashguo.top/Article/details/gttwkytfgq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.havefunace.top/Article/details/gtpogorjfq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.aizwys.cn/Article/details/gtilmdyxud.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hysaishi.cn/Article/details/gticuzcuoh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yuanzhike.top/Article/details/gtfqnulemh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinqigfzy.top/Article/details/gtsxjjxrse.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xinyue.icu/Article/details/gtslcxpgvp.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtntvpfcxr.html

K. JSON 与序列化
来源：http://dali.ybcxt.top/Article/details/gtipodefwp.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtekaxvczj.html

[K01] 对象转 JSON 字符串
来源：http://dali.birdmap.top/Article/details/gtxfrxfncr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gtiptmklrx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gtiosffvde.html

JS:   JSON.stringify(obj)
来源：http://dali.chenlongwang.top/Article/details/gtdpctbxte.html

TS:   JSON.stringify(obj)
来源：http://dali.xuanzx.com/Article/details/gtacckgafr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.birdmap.top/Article/details/gtkabqdasy.html

Go:   json.Marshal(obj)
来源：http://dali.0kj1m.cn/Article/details/gtbturkcyc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.andypj.xyz/Article/details/gtlryvzmta.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.pycfn.com/Article/details/gtlfdyefym.html

[K02] JSON 字符串转对象
来源：http://dali.svipenyu.cn/Article/details/gtymgjscry.html

Py:   json.loads(s)
来源：http://dali.pycfn.com/Article/details/gtnxbwgvti.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yvedp.cn/Article/details/gtnkhfgdde.html

JS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtekyzisac.html

TS:   JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gtaocapbqm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ybcxt.top/Article/details/gtldrkbhwh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xziqi.cn/Article/details/gtqdaazfgv.html

Ruby: JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gtisokfmyr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gogol.net.cn/Article/details/gthgyfijhr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.snrcjt.cn/Article/details/gtyswiztlq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nwbrower.top/Article/details/gtokxkqxjw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.redwolf501.top/Article/details/gtiooniplw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hammf.cn/Article/details/gtrveaddqs.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gtgkwjyymw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.mhx1999.top/Article/details/gtmzfggjod.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.pengpengdd.cyou/Article/details/gtcbszhbkp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gzhubu.top/Article/details/gtyvncjjqf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gogol.net.cn/Article/details/gtfspvpxbn.html

[K04] 读取 JSON 文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhvoyjfc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cheryme.top/Article/details/gtsyotcict.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tian-w.cn/Article/details/gtgjvwshxu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pycfn.com/Article/details/gtwjuhnexq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.iojbl.cn/Article/details/gtrehgkkff.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.snrcjt.cn/Article/details/gtcbzzmdtm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gthfsyrwks.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gtlyqnxbrv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.redwolf501.top/Article/details/gtvtvrvmhc.html

[K05] 深拷贝对象
来源：http://dali.sysykeji.top/Article/details/gtosgsftbu.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgfzy.top/Article/details/gtilbbdhfr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj20258888.top/Article/details/gtbiprahwd.html

JS:   structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtvrkwoevb.html

TS:   structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gtexrzjzph.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.316326.xyz/Article/details/gtcbccufip.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gzhubu.top/Article/details/gtoxrqpibr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hammf.cn/Article/details/gtypycsyoo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xziqi.cn/Article/details/gtcnbraykr.html

[K06] 解析 URL 查询串
来源：http://dali.hnqzz.top/Article/details/gtxtcwrexg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.vqdsnc.cn/Article/details/gtidrghhof.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258888.top/Article/details/gtcurmoivz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.andypj.xyz/Article/details/gtbjncfukb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gogol.net.cn/Article/details/gtpthzozsj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aizwys.cn/Article/details/gtvtkadjcz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gtciovstmc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gtstpofhot.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gtzxkzgpkg.html

[K07] 进制转换
来源：http://dali.cucudq.cn/Article/details/gtvithvkwk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtzfyjwvwh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tian-w.cn/Article/details/gtjstbaody.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtvakifkck.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtetwkxpmb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtnxxmlikd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cheryme.top/Article/details/gtekjdttzp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daria6918.cn/Article/details/gtqfjyunlj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtqvjbfbjh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hnxiangtu.top/Article/details/gteuhffjob.html

Py:   pickle.dumps(obj)
来源：http://dali.gogol.net.cn/Article/details/gtxbjvufaw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.dashuyun.cn/Article/details/gtyzfxzsox.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhongyouzk.top/Article/details/gtvxhcurcs.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gtxanfrosi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hnqzz.top/Article/details/gtqqxlezum.html

Go:   encoding/gob
来源：http://dali.gotoacloud.top/Article/details/gtkkchgnpf.html

Ruby: Marshal.dump(obj)
来源：http://dali.daria6918.cn/Article/details/gtwzsujwcx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gtajvpsylp.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtippcruju.html

L. 网络请求
来源：http://dali.zhongyouzk.top/Article/details/gtlepaexkx.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gthnhtbpdg.html

[L01] 发送 GET 请求
来源：http://dali.smart0.xyz/Article/details/gtqphlgnqr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhengqikj.top/Article/details/gtavwdxskl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.mhx1999.top/Article/details/gtzrgfjwpg.html

JS:   await fetch(url)
来源：http://dali.birdmap.top/Article/details/gtjtnelzms.html

TS:   await fetch(url)
来源：http://dali.haohaochexian.top/Article/details/gtniucvtxn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdymlzwu.html

Go:   resp, err := http.Get(url)
来源：http://dali.tanke756.top/Article/details/gtimdqdsrg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfotzsdq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cucudq.cn/Article/details/gtgswfmtdw.html

[L02] 发送 POST JSON
来源：http://dali.dianchejie.cn/Article/details/gtlsnajrub.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.wangshuangyany.cn/Article/details/gtouihivit.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhiwuduotai.top/Article/details/gtynjzekcj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gtncqydvyc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aizwys.cn/Article/details/gtxjbwtxha.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xinyue.icu/Article/details/gtwkqqgtgr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinghuilouyu.cn/Article/details/gticeyvqcw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.fzhhl.top/Article/details/gtrcedofzq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.quarkkingdee.top/Article/details/gtjzpmichb.html

[L03] 设置自定义请求头
来源：http://dali.nwbrower.top/Article/details/gtgsonumvy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.pycfn.com/Article/details/gtpeozudsi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yueranfly.top/Article/details/gtwcuumnrh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tianlin.xyz/Article/details/gtpqwwhzqh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sufxvd.cn/Article/details/gtwyljzfmp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.daxiang520.top/Article/details/gtkmuymiuq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ybcxt.top/Article/details/gtvvpxkkiv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenjidiqi.icu/Article/details/gtgidyqkfk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zdqjudy.top/Article/details/gtjctmjaxr.html

[L04] 设置超时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtosgcceyd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.daxiang520.top/Article/details/gtgrevgmva.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tian-w.cn/Article/details/gtjhksbteu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gtzmubnrum.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ehwqpu.com/Article/details/gtcatnsjct.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj202588.top/Article/details/gtudiaqbco.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangshuangyany.cn/Article/details/gtvpgrpsrt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjucfvlbs.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.snrcjt.cn/Article/details/gtjjgnimto.html

[L05] 上传文件（multipart）
来源：http://dali.nanxinkj.top/Article/details/gtnxxmokhs.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cheryme.top/Article/details/gtuwgaezze.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nanxinkj.top/Article/details/gtkpxlmive.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gtpnkfctaa.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgfzy.top/Article/details/gtihfbqhkg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cdnleiting.top/Article/details/gtspnpxbza.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sufxvd.cn/Article/details/gtcmfnkvfm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hongshengwenyu.top/Article/details/gtxxrnvrnb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtdiydajdl.html

[L06] 解析响应为 JSON
来源：http://dali.shangyingyoupin.top/Article/details/gtfokfuwir.html

Py:   resp.json()
来源：http://dali.gogol.net.cn/Article/details/gtjfpflnqd.html

PHP:  json_decode($body, true);
来源：http://dali.svipenyu.cn/Article/details/gtphllzixe.html

JS:   await resp.json()
来源：http://dali.daria6918.cn/Article/details/gtgccvjmaq.html

TS:   await resp.json()
来源：http://dali.wangdashe.top/Article/details/gtzzowsvkb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvsreizl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hammf.cn/Article/details/gtovgevrpc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.fzhhl.top/Article/details/gtatdjgchs.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.feifeiyinyue.top/Article/details/gtgiijslxa.html

[L07] 处理 HTTP 状态码
来源：http://dali.pycfn.com/Article/details/gtshiccyoy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gtvvbuisbx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cqqwz.cn/Article/details/gtchfqkdaz.html

JS:   resp.ok;  resp.status
来源：http://dali.yueranfly.top/Article/details/gthgbrfmqm.html

TS:   resp.ok;  resp.status
来源：http://dali.ehwqpu.com/Article/details/gtqpmeskvl.html

Java: resp.statusCode()
来源：http://dali.hywenlv.cn/Article/details/gtuynmfxxt.html

Go:   resp.StatusCode
来源：http://dali.jlsjyb.cn/Article/details/gtdxklhlkg.html

Ruby: resp.code.to_i
来源：http://dali.ybcxt.top/Article/details/gtnitccxgb.html

C#:   (int)resp.StatusCode
来源：http://dali.zhengqikj.top/Article/details/gtesqvchom.html

[L08] 并发请求多个地址
来源：http://dali.tanke756.top/Article/details/gttahmzoty.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jlsjyb.cn/Article/details/gtemehfqby.html

PHP:  curl_multi_init() 系列
来源：http://dali.cucudq.cn/Article/details/gthsnjjptf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gthbqwhfeu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gtlaoridqs.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nwbrower.top/Article/details/gtevxnyqor.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.redwolf501.top/Article/details/gtcpewldej.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuanzx.com/Article/details/gtadjcqxzj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtcqvfqyxv.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtczjfbbfw.html

M. 命令行 / 进程 / 环境
来源：http://dali.bjfxy.top/Article/details/gtwfeznwgl.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtximrweko.html

[M01] 读取命令行参数
来源：http://dali.xuanzx.com/Article/details/gtrwzigoiq.html

Py:   sys.argv[1:]
来源：http://dali.yj20258888.top/Article/details/gthbxzfmci.html

PHP:  $argv;  $argc;
来源：http://dali.haohaochexian.top/Article/details/gtvvztkpdy.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gtbelarqht.html

TS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gtqvaggksy.html

Java: args 数组（main 方法参数）
来源：http://dali.kuanghao11.cn/Article/details/gtdnjljexq.html

Go:   os.Args[1:]
来源：http://dali.fzhhl.top/Article/details/gtxobmmiqn.html

Ruby: ARGV
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpgmljogv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gtkaignlow.html

[M02] 读取环境变量
来源：http://dali.wangdashe.top/Article/details/gtchppseuq.html

Py:   os.environ.get("HOME")
来源：http://dali.tanke756.top/Article/details/gtmpbufqyr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gtqayhzshb.html

JS:   process.env.HOME
来源：http://dali.chenlongwang.top/Article/details/gtzdqwfkmr.html

TS:   process.env.HOME
来源：http://dali.dianchejie.cn/Article/details/gtbujpojwq.html

Java: System.getenv("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdnbndakv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtztyuxvkj.html

Ruby: ENV["HOME"]
来源：http://dali.c1oappe.top/Article/details/gtbormjvmd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.guannengcc.top/Article/details/gtvzbzncsg.html

[M03] 执行外部命令
来源：http://dali.shangyingyoupin.top/Article/details/gttlvxblvo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.meibo888.top/Article/details/gtdlzwdnpu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuetiantiany.cn/Article/details/gtmaxprebg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shuidangran.top/Article/details/gtcphwzodr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.fengsongda.top/Article/details/gtznxwxhdz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ehwqpu.com/Article/details/gturhjdctz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ydzc1.top/Article/details/gtllzbxaab.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzozjhma.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hywenlv.cn/Article/details/gtuiyhbltn.html

[M04] 获取当前工作目录
来源：http://dali.sxryk.cn/Article/details/gtpbqknupy.html

Py:   os.getcwd()
来源：http://dali.hfpthk.cn/Article/details/gtwqimprth.html

PHP:  getcwd();
来源：http://dali.sweek.top/Article/details/gtoncnzbdu.html

JS:   process.cwd()
来源：http://dali.feifeiyinyue.top/Article/details/gtjupjnnzz.html

TS:   process.cwd()
来源：http://dali.gaohongyu789.top/Article/details/gtvvfqsgwv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jqgfzy.top/Article/details/gtmplszzxp.html

Go:   os.Getwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxcpzggmd.html

Ruby: Dir.pwd
来源：http://dali.ivvv.top/Article/details/gtxjasbcti.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.quarkkingdee.top/Article/details/gtjmjfpojx.html

[M05] 设置退出码
来源：http://dali.nanxuanxn.top/Article/details/gtgniuulrv.html

Py:   sys.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtwyxtbevo.html

PHP:  exit(1);
来源：http://dali.quarkkingdee.top/Article/details/gtoskvhnov.html

JS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gtxodwhlhr.html

TS:   process.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtqbimbbiu.html

Java: System.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtqwqmzigy.html

Go:   os.Exit(1)
来源：http://dali.xinyue.icu/Article/details/gtixdhmmhh.html

Ruby: exit 1
来源：http://dali.yj20258.top/Article/details/gtsrutmpln.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ydzc1.top/Article/details/gthzmtewgy.html

[M06] 向标准错误输出
来源：http://dali.fzhhl.top/Article/details/gttkyxoklc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tian-w.cn/Article/details/gtvqarhorx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlqyzxebh.html

JS:   console.error("err")
来源：http://dali.quarkkingdee.top/Article/details/gtczhqupet.html

TS:   console.error("err")
来源：http://dali.9152youxi.cn/Article/details/gtlebukilf.html

Java: System.err.println("err")
来源：http://dali.andypj.xyz/Article/details/gtbpjaykga.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tian-w.cn/Article/details/gtwrqlspxb.html

Ruby: warn "err"
来源：http://dali.ivvv.top/Article/details/gtvcqrtenk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.andypj.xyz/Article/details/gtsifwtcej.html

[M07] 判断是否为主入口
来源：http://dali.wangdashe.top/Article/details/gtlynmfnwf.html

Py:   if __name__ == "__main__":
来源：http://dali.feifeiyinyue.top/Article/details/gtzvsgjppt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.aibaodan.cn/Article/details/gtkrxjlyeo.html

JS:   require.main === module
来源：http://dali.vqdsnc.cn/Article/details/gtxjpetdjb.html

TS:   require.main === module
来源：http://dali.shuidangran.top/Article/details/gtwvnfnhde.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gtsyyqxbim.html

Go:   func main()
来源：http://dali.jqgufenzy.top/Article/details/gtpywaduvj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yvedp.cn/Article/details/gtujtdkokz.html

C#:   static void Main(string[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gthcfiwuoc.html

[M08] 获取系统与运行时信息
来源：http://dali.9152youxi.cn/Article/details/gtrzoykwpf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fengsongda.top/Article/details/gtrdszftty.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shzxlz.cn/Article/details/gtpfkntvxt.html

JS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gtvbsycnqx.html

TS:   process.platform;  process.version
来源：http://dali.yj20258888.top/Article/details/gtofzmicqk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.guowangkeji.top/Article/details/gtvqgqjtdr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gogol.net.cn/Article/details/gtgcnsvibx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jianghu66.top/Article/details/gtqjsfxvit.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yuxming.cn/Article/details/gtyphxdhia.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtlgqxbyyg.html

N. 数据结构与算法
来源：http://dali.yj20258.top/Article/details/gtzbgakuuk.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtlttdbdlr.html

[N01] 二分查找（有序数组）
来源：http://dali.jiagoushi.top/Article/details/gteeleptqe.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtgkcuomzm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gtlxsnvhhd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sweek.top/Article/details/gtjjdpvcuj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tianlin.xyz/Article/details/gteadwrkvk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.meibo888.top/Article/details/gtzqzvwcza.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtunjgkydr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cucudq.cn/Article/details/gtjmrmhrih.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gteczvynag.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yueranfly.top/Article/details/gtaccfwhfj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cashguo.top/Article/details/gtqlmlvhgo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hysaishi.cn/Article/details/gtsmukmaub.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hammf.cn/Article/details/gtqdalhpyx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gtqdgqzclo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yueranfly.top/Article/details/gtpoqrzxmi.html

Go:   slices.Sort(arr)
来源：http://dali.ybcxt.top/Article/details/gtsfnurbjq.html

Ruby: arr.sort
来源：http://dali.cheryme.top/Article/details/gtvenwfhgz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hnxiangtu.top/Article/details/gtshtnjozr.html

[N03] 快速排序（分治示例）
来源：http://dali.mhx1999.top/Article/details/gtkpagtcpa.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yonumen.top/Article/details/gtnpxsrnjx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.mhx1999.top/Article/details/gtqvlulevz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenlongwang.top/Article/details/gtqumvlfks.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xziqi.cn/Article/details/gtmbhnzcxo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhiwuduotai.top/Article/details/gtrufiujke.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipqsxbdr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cdnleiting.top/Article/details/gtqxvbokrx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.quarkkingdee.top/Article/details/gtzjhbwdaw.html

[N04] 斐波那契数列
来源：http://dali.zhiwuduotai.top/Article/details/gtltommcob.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yangfankeji.com/Article/details/gtebvotywk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.dianchejie.cn/Article/details/gthbefcpyw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gtrkfzqmub.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gtdjcalxwy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xinyue.icu/Article/details/gtcxcqeman.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenjidiqi.icu/Article/details/gtspmkroxb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gogol.net.cn/Article/details/gtmacapkrt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gtrkecsckg.html

[N05] 最大公约数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtocqhxolk.html

Py:   math.gcd(a, b)
来源：http://dali.316326.xyz/Article/details/gtudrbwylr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gtvlaqxift.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sweek.top/Article/details/gtwanwxgoe.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258.top/Article/details/gtqsyrulir.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hysaishi.cn/Article/details/gtlicngdmg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.feifeiyinyue.top/Article/details/gthgvwfixb.html

Ruby: a.gcd(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxrhfzqb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhixingplan.top/Article/details/gtpyrjypkq.html

[N06] 判断回文字符串
来源：http://dali.jqgufenzy.top/Article/details/gtrqkkjnna.html

Py:   s == s[::-1]
来源：http://dali.pycfn.com/Article/details/gtacjrzvkb.html

PHP:  $s === strrev($s);
来源：http://dali.hywenlv.cn/Article/details/gtbeffiags.html


<!-- 参考信息 -->