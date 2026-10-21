代发 wailian999

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.guannengcc.top/Article/details/gtxgozxtcx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.aibaodan.cn/Article/details/gtdrktcvgj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gtfvpbjyqo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fengsongda.top/Article/details/gtpladrnqg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.redwolf501.top/Article/details/gtygyfrqrn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.c1oappe.top/Article/details/gtovvyhped.html

[J09] 时区处理
来源：http://dali.sufxvd.cn/Article/details/gttmedhwci.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.iojbl.cn/Article/details/gtezpqnfqv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cashguo.top/Article/details/gtcdvfjyxr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gtfefhdkry.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sysykeji.top/Article/details/gtnphsvivd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhixingplan.top/Article/details/gthulsscvj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.birdmap.top/Article/details/gtieqxwhog.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sysykeji.top/Article/details/gtuyepimcn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hysaishi.cn/Article/details/gtmdvzylwo.html

[J10] 取今天 / 本月第一天
来源：http://dali.birdmap.top/Article/details/gtobyvosku.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tianlin.xyz/Article/details/gtaupcvxhw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.pengpengdd.cyou/Article/details/gtlqufxpfu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtcgulkkpj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hywenlv.cn/Article/details/gtotgbvakl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangdashe.top/Article/details/gtmirkxsmv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.meibo888.top/Article/details/gtgvvyoqih.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jianghu66.top/Article/details/gtabmxghfs.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtvjcmbixi.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtrwoxerig.html

K. JSON 与序列化
来源：http://dali.wangdashe.top/Article/details/gtijholoew.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtpjbikgxd.html

[K01] 对象转 JSON 字符串
来源：http://dali.shuidangran.top/Article/details/gtfiuozgxl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ehwqpu.com/Article/details/gtzljonzzm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhoulong.xyz/Article/details/gtffwoxeku.html

JS:   JSON.stringify(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtifmlyxyb.html

TS:   JSON.stringify(obj)
来源：http://dali.chenzaomai.com/Article/details/gtftgngfjw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhoulong.xyz/Article/details/gtlbboahwh.html

Go:   json.Marshal(obj)
来源：http://dali.snrcjt.cn/Article/details/gtsybumdls.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zycfv.cn/Article/details/gtquduytmz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.9152youxi.cn/Article/details/gtvvjkjydu.html

[K02] JSON 字符串转对象
来源：http://dali.dianchejie.cn/Article/details/gtkjeyrctw.html

Py:   json.loads(s)
来源：http://dali.gzhubu.top/Article/details/gtbmlvkfnk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nwbrower.top/Article/details/gtuajoxhgd.html

JS:   JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gtluypgmco.html

TS:   JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gtyqikmkie.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xziqi.cn/Article/details/gtfwrwgkmd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhoulong.xyz/Article/details/gtnzqtkoyh.html

Ruby: JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gtrxiwgxck.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cdnleiting.top/Article/details/gtsdupufap.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yuxming.cn/Article/details/gtxyczxkgw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ppjwa.cn/Article/details/gtmeyraoiq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ydzc1.top/Article/details/gttqvqecsv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtuddrpvfd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gtkrnnknvj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuxming.cn/Article/details/gtutwfjauy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenzaomai.com/Article/details/gtgtucanxk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ivvv.top/Article/details/gtrbzjbacw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.kuanghao11.cn/Article/details/gtlgxudnuf.html

[K04] 读取 JSON 文件
来源：http://dali.sufxvd.cn/Article/details/gtslsfpzhv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gaohongyu789.top/Article/details/gtipkgaohv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj20258.top/Article/details/gtjkrzmaew.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jlsjyb.cn/Article/details/gtvqpznjgi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgfzy.top/Article/details/gtqsqftyuj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jiagoushi.top/Article/details/gtxghhiibt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gtegigdkut.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.fzhhl.top/Article/details/gtdprcxaii.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhiwuduotai.top/Article/details/gtulxvximp.html

[K05] 深拷贝对象
来源：http://dali.fzhhl.top/Article/details/gtmrmmqtpv.html

Py:   copy.deepcopy(obj)
来源：http://dali.fengsongda.top/Article/details/gtioaniqmc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.guannengcc.top/Article/details/gtashwedjd.html

JS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gtbyadlvha.html

TS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gtctocgigg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ppjwa.cn/Article/details/gtnsjqczxa.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tanke756.top/Article/details/gtikfnlgoe.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xziqi.cn/Article/details/gtejmamdoq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinghuilouyu.cn/Article/details/gthqiqsmbx.html

[K06] 解析 URL 查询串
来源：http://dali.chenzaomai.com/Article/details/gtjvozfwmm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.daria6918.cn/Article/details/gtoqcuaklr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.bjfxy.top/Article/details/gtgfsdugeo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cashguo.top/Article/details/gtagxlgois.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cashguo.top/Article/details/gtxnrlitji.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhongyouzk.top/Article/details/gtlvduelsp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gtbvhjteis.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gtprfdvmaf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gtlwdwdetl.html

[K07] 进制转换
来源：http://dali.jyoumei.cn/Article/details/gtnkfcsufa.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtrxqkmwka.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.guannengcc.top/Article/details/gtbfpziimy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtsuedipdh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtbedibuzs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtmruufnlf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj20258888.top/Article/details/gtkvnfhbrb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.haohaochexian.top/Article/details/gtehlqofyq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtwoujvbrn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yvedp.cn/Article/details/gtaggocett.html

Py:   pickle.dumps(obj)
来源：http://dali.gogol.net.cn/Article/details/gttyqsbqyr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtgcjkoizm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gtzinzpyer.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gtjghjwchj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shuidangran.top/Article/details/gtrqsnxzzc.html

Go:   encoding/gob
来源：http://dali.fengsongda.top/Article/details/gtiisedwwn.html

Ruby: Marshal.dump(obj)
来源：http://dali.jyoumei.cn/Article/details/gtvyydlcxb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xziqi.cn/Article/details/gtioxrcjqp.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtwncgroua.html

L. 网络请求
来源：http://dali.cheryme.top/Article/details/gtqshkuofj.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtngixzujo.html

[L01] 发送 GET 请求
来源：http://dali.yuanzhike.top/Article/details/gtlpsajdun.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xylfe.cn/Article/details/gthptoukml.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cdnleiting.top/Article/details/gtxumvwubx.html

JS:   await fetch(url)
来源：http://dali.aizwys.cn/Article/details/gtvytimexw.html

TS:   await fetch(url)
来源：http://dali.fengsongda.top/Article/details/gtigbfpwqs.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tanke756.top/Article/details/gtxkjdddhi.html

Go:   resp, err := http.Get(url)
来源：http://dali.hammf.cn/Article/details/gtauynlhsv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj20258.top/Article/details/gtkkgmjpuj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sweek.top/Article/details/gtkoqvytmm.html

[L02] 发送 POST JSON
来源：http://dali.smart0.xyz/Article/details/gtjhfwroob.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cqqwz.cn/Article/details/gtrxkeenrt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.dashuyun.cn/Article/details/gtpedficvr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangdashe.top/Article/details/gtfqtprpdy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gtvdmcfsuo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.kuanghao11.cn/Article/details/gturcuglhl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.dashuyun.cn/Article/details/gtuyeuegtm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlteoruxf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj202588.top/Article/details/gtdmtycpaa.html

[L03] 设置自定义请求头
来源：http://dali.yonumen.top/Article/details/gtqhdlmswb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dashuyun.cn/Article/details/gtafhinqfk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shuidangran.top/Article/details/gtxnwkjrqo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jyoumei.cn/Article/details/gtlyagmzwi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ppjwa.cn/Article/details/gtgwgzfdzc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jqgufenzy.top/Article/details/gtvyqfaure.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gtoxmnqaff.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cheryme.top/Article/details/gtwldoyurt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj20258.top/Article/details/gtpfhrxpub.html

[L04] 设置超时
来源：http://dali.chenjidiqi.icu/Article/details/gthfyytuay.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yonumen.top/Article/details/gtatpromkl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.pengpengdd.cyou/Article/details/gtyebrfkyz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgfzy.top/Article/details/gtoexsrkrs.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guowangkeji.top/Article/details/gtmzlwfdtr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuanzhike.top/Article/details/gttxzkvtwj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenzaomai.com/Article/details/gthgteudwa.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenzaomai.com/Article/details/gtedxgwity.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhoulong.xyz/Article/details/gtlzalhwpw.html

[L05] 上传文件（multipart）
来源：http://dali.nanxinkj.top/Article/details/gtxutrzcpp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.daria6918.cn/Article/details/gtgnjgyqsk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tanke756.top/Article/details/gtnsitmpit.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jyoumei.cn/Article/details/gtqxnzxuym.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jlsjyb.cn/Article/details/gtdzqwkszh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shuidangran.top/Article/details/gtrscaxwvl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.guowangkeji.top/Article/details/gtptgyoinr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hnqzz.top/Article/details/gtiskenmaq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gthfkejeid.html

[L06] 解析响应为 JSON
来源：http://dali.shuidangran.top/Article/details/gtmmdiqbze.html

Py:   resp.json()
来源：http://dali.sufxvd.cn/Article/details/gtlhzgtipy.html

PHP:  json_decode($body, true);
来源：http://dali.mhx1999.top/Article/details/gtqtpdfkgw.html

JS:   await resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gtigqiswur.html

TS:   await resp.json()
来源：http://dali.cheryme.top/Article/details/gtuuetgysu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sxryk.cn/Article/details/gtshmnrsuw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.svipenyu.cn/Article/details/gtajvlvfmk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.birdmap.top/Article/details/gtytlzerob.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.havefunace.top/Article/details/gtbfxjsyom.html

[L07] 处理 HTTP 状态码
来源：http://dali.cashguo.top/Article/details/gtypvdwjrb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ydzc1.top/Article/details/gtqxltsfqv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj20258888.top/Article/details/gtiqhkoboq.html

JS:   resp.ok;  resp.status
来源：http://dali.pycfn.com/Article/details/gtdhzfqfaq.html

TS:   resp.ok;  resp.status
来源：http://dali.shzxlz.cn/Article/details/gtbcvqjqsa.html

Java: resp.statusCode()
来源：http://dali.wangdashe.top/Article/details/gtlmzszyum.html

Go:   resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gtgjgebbyr.html

Ruby: resp.code.to_i
来源：http://dali.jqgfzy.top/Article/details/gtnvcngdzn.html

C#:   (int)resp.StatusCode
来源：http://dali.zhixingplan.top/Article/details/gtdopwwhfc.html

[L08] 并发请求多个地址
来源：http://dali.shzxlz.cn/Article/details/gtkroofdyq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tanke756.top/Article/details/gtfbamisnm.html

PHP:  curl_multi_init() 系列
来源：http://dali.daria6918.cn/Article/details/gtzjdnyaiv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daria6918.cn/Article/details/gtqfcakwxv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gtunxagclc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqcyvrlo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.aizwys.cn/Article/details/gtfpfxjzeb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ivvv.top/Article/details/gtazbwkthf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj202588.top/Article/details/gtqquyxyhd.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtuxplqskg.html

M. 命令行 / 进程 / 环境
来源：http://dali.yuxming.cn/Article/details/gtoxbiydeo.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtfswcenwc.html

[M01] 读取命令行参数
来源：http://dali.ppjwa.cn/Article/details/gtvqupgujg.html

Py:   sys.argv[1:]
来源：http://dali.yj202588.top/Article/details/gtkndcudum.html

PHP:  $argv;  $argc;
来源：http://dali.svipenyu.cn/Article/details/gtvxxkwvco.html

JS:   process.argv.slice(2)
来源：http://dali.shuidangran.top/Article/details/gtfscpbzkl.html

TS:   process.argv.slice(2)
来源：http://dali.sysykeji.top/Article/details/gtwxlldyrd.html

Java: args 数组（main 方法参数）
来源：http://dali.jlsjyb.cn/Article/details/gtzaptdrkb.html

Go:   os.Args[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gtlejufghu.html

Ruby: ARGV
来源：http://dali.hywenlv.cn/Article/details/gtguataldu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtazecakhr.html

[M02] 读取环境变量
来源：http://dali.quarkkingdee.top/Article/details/gtxpmsdqrg.html

Py:   os.environ.get("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtqjbripai.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gtbopeodjr.html

JS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gtfnljiejd.html

TS:   process.env.HOME
来源：http://dali.vqdsnc.cn/Article/details/gtqdvnfuau.html

Java: System.getenv("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtdsjcixsy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtpesimubl.html

Ruby: ENV["HOME"]
来源：http://dali.shzxlz.cn/Article/details/gtzzpgkbyv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnqzz.top/Article/details/gtmvarapgl.html

[M03] 执行外部命令
来源：http://dali.tianlin.xyz/Article/details/gtgwvzbvpp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jiagoushi.top/Article/details/gtssnqtlzt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tianlin.xyz/Article/details/gtbjfuzsec.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gtfktcwyjo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gtfsahybwv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258.top/Article/details/gtnjopefzy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shzxlz.cn/Article/details/gtzvnpfcdp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.mhx1999.top/Article/details/gtkeyswgxn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.smart0.xyz/Article/details/gtvhhoukrd.html

[M04] 获取当前工作目录
来源：http://dali.tian-w.cn/Article/details/gtkbzbgmwc.html

Py:   os.getcwd()
来源：http://dali.yongpay.top/Article/details/gtjuukyvfn.html

PHP:  getcwd();
来源：http://dali.yj20258888.top/Article/details/gtctvbfxaw.html

JS:   process.cwd()
来源：http://dali.yj202588.top/Article/details/gtvjdovgka.html

TS:   process.cwd()
来源：http://dali.yongpay.top/Article/details/gtrnwxahrt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.daria6918.cn/Article/details/gtksbeoaaa.html

Go:   os.Getwd()
来源：http://dali.zhengqikj.top/Article/details/gtpdjahway.html

Ruby: Dir.pwd
来源：http://dali.hfpthk.cn/Article/details/gtwcvlltur.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjchrbopr.html

[M05] 设置退出码
来源：http://dali.jinghuilouyu.cn/Article/details/gthvsmopdp.html

Py:   sys.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtvwakxere.html

PHP:  exit(1);
来源：http://dali.jlsjyb.cn/Article/details/gtzwtkxjvr.html

JS:   process.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtzjmxieqj.html

TS:   process.exit(1)
来源：http://dali.iojbl.cn/Article/details/gtcuxbzrxe.html

Java: System.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtljcvvgwf.html

Go:   os.Exit(1)
来源：http://dali.tanke756.top/Article/details/gtpwluhqav.html

Ruby: exit 1
来源：http://dali.yangfankeji.com/Article/details/gtsrpceqld.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.aibaodan.cn/Article/details/gtiejzpeym.html

[M06] 向标准错误输出
来源：http://dali.yuanzhike.top/Article/details/gtuyhsqiqb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenjidiqi.icu/Article/details/gtgfolrhxo.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgfzy.top/Article/details/gtmdtlyvaa.html

JS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gtydlbuydo.html

TS:   console.error("err")
来源：http://dali.snrcjt.cn/Article/details/gttxmkweck.html

Java: System.err.println("err")
来源：http://dali.0kj1m.cn/Article/details/gtdxymudyf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj20258.top/Article/details/gtugozdsqn.html

Ruby: warn "err"
来源：http://dali.jiagoushi.top/Article/details/gtxcstqlxh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.smart0.xyz/Article/details/gtvkalyiav.html

[M07] 判断是否为主入口
来源：http://dali.sysykeji.top/Article/details/gtgfevvwle.html

Py:   if __name__ == "__main__":
来源：http://dali.aibaodan.cn/Article/details/gtrwvbctil.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtknjghndz.html

JS:   require.main === module
来源：http://dali.yangfankeji.com/Article/details/gtsxofaktb.html

TS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gtcqqzhfgb.html

Java: public static void main(String[] args)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthwwnnwzj.html

Go:   func main()
来源：http://dali.hammf.cn/Article/details/gtnezzgdfn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sweek.top/Article/details/gtzpcmcdhn.html

C#:   static void Main(string[] args)
来源：http://dali.feifeiyinyue.top/Article/details/gtxapjomnq.html

[M08] 获取系统与运行时信息
来源：http://dali.jinyuanbaomall.cn/Article/details/gthvjlxbeo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daxiang520.top/Article/details/gtnxymfhxx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.aizwys.cn/Article/details/gtxwugmjah.html

JS:   process.platform;  process.version
来源：http://dali.havefunace.top/Article/details/gtrlvvwkdk.html

TS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gtfnirqywv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nwbrower.top/Article/details/gtufcizqxc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cucudq.cn/Article/details/gthhpadhue.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gtqqyedtcm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gzhubu.top/Article/details/gtzgcjkeef.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtkwfvxtph.html

N. 数据结构与算法
来源：http://dali.cashguo.top/Article/details/gtizttdoan.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtkvqfqzek.html

[N01] 二分查找（有序数组）
来源：http://dali.zhengqikj.top/Article/details/gtkugnbumw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ybcxt.top/Article/details/gttxdyopvn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwaylbht.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gthtsvhojj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.smart0.xyz/Article/details/gtfbxvhcbd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtdvdkdvbz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtbcsujgpr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.wangdashe.top/Article/details/gtxjqcwtwf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcnltcide.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgufenzy.top/Article/details/gtplyzgxhq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daria6918.cn/Article/details/gtvlnlwvee.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cqqwz.cn/Article/details/gtaobnhmql.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gtyilvdaqh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fengsongda.top/Article/details/gtxcxmxpus.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cashguo.top/Article/details/gtdzvrepnr.html

Go:   slices.Sort(arr)
来源：http://dali.zhengqikj.top/Article/details/gtyiumjxem.html

Ruby: arr.sort
来源：http://dali.nwbrower.top/Article/details/gtavwmwaot.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.iojbl.cn/Article/details/gtzsnsruam.html

[N03] 快速排序（分治示例）
来源：http://dali.wangdashe.top/Article/details/gtblabhmkq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.9152youxi.cn/Article/details/gtynbaqlje.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yangfankeji.com/Article/details/gtrqnwqzcb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shangyingyoupin.top/Article/details/gtadhbwnya.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sxryk.cn/Article/details/gtjxhdlesu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.meibo888.top/Article/details/gtjjecgokk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gthksftgvx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jiagoushi.top/Article/details/gtctoasqpx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.haohaochexian.top/Article/details/gtllelcfvq.html

[N04] 斐波那契数列
来源：http://dali.jinqigufen.top/Article/details/gtzokjogln.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sufxvd.cn/Article/details/gtmydrvkcu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cheryme.top/Article/details/gtxkkbiajq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjpedjek.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gtuwdarybe.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yuxming.cn/Article/details/gtcolgtnmc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hfpthk.cn/Article/details/gtverxwvum.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gtzayxvytq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gtlzkgzorx.html

[N05] 最大公约数
来源：http://dali.dianchejie.cn/Article/details/gtzlqpmydt.html

Py:   math.gcd(a, b)
来源：http://dali.yuxming.cn/Article/details/gtjexubxbb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cucudq.cn/Article/details/gtknljwcwl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtriiligpk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxuanxn.top/Article/details/gtunfzmvpm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hnxiangtu.top/Article/details/gtytcvtlmt.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.pengpengdd.cyou/Article/details/gtvlryqvpo.html

Ruby: a.gcd(b)
来源：http://dali.vqdsnc.cn/Article/details/gtturrqzck.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinqigufen.top/Article/details/gtlchmtdqq.html

[N06] 判断回文字符串
来源：http://dali.shuidangran.top/Article/details/gtjmlkgfrj.html

Py:   s == s[::-1]
来源：http://dali.yuanzhike.top/Article/details/gtawpepmmc.html

PHP:  $s === strrev($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfhxaybqq.html


<!-- 参考信息 -->