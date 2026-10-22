代发 wailian999

[J07] 比较两个日期
来源：http://dali.tianlin.xyz/Article/details/gt2ejhmxeyl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gt2wypiafff.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.andypj.xyz/Article/details/gt2hacnujpq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gt2msiybwjo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gt2nxgvdptw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.dashuyun.cn/Article/details/gt2rigozkqe.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cheryme.top/Article/details/gt2yykrrure.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gt2qxryejag.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gt2trrfdexp.html

[J08] 提取年月日与星期
来源：http://dali.jinqigufen.top/Article/details/gt2hbefkmsc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zycfv.cn/Article/details/gt2iqmppctq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.daxiang520.top/Article/details/gt2xkqdmljv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinqigufen.top/Article/details/gt2iekywaao.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sweek.top/Article/details/gt2rxfhlild.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinqigfzy.top/Article/details/gt2cyqznhvf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cheryme.top/Article/details/gt2akjxkjpg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yvedp.cn/Article/details/gt2vluaylks.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinqigufen.top/Article/details/gt2ikzrzyrf.html

[J09] 时区处理
来源：http://dali.jyoumei.cn/Article/details/gt2jzowwqlg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shzxlz.cn/Article/details/gt2vtbtbpsh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cdnleiting.top/Article/details/gt2lsmqpcyc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.9152youxi.cn/Article/details/gt2hqqascft.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.redwolf501.top/Article/details/gt2mlqgwifh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jqgufenzy.top/Article/details/gt2hxelwvlm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.kuanghao11.cn/Article/details/gt2yqesrdxf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lrvtohxc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxinkj.top/Article/details/gt2dgjpmsuz.html

[J10] 取今天 / 本月第一天
来源：http://dali.shzxlz.cn/Article/details/gt2uktvelsg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yvedp.cn/Article/details/gt2ontwddyp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hammf.cn/Article/details/gt2jqxnvvly.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nwbrower.top/Article/details/gt2kmeqhrxz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cucudq.cn/Article/details/gt2dsrnvtfr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jiagoushi.top/Article/details/gt2pwunimgw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuanzx.com/Article/details/gt2fgvesjwd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dianchejie.cn/Article/details/gt2dconiorg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zycfv.cn/Article/details/gt2hrrqeswz.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2owexpeab.html

K. JSON 与序列化
来源：http://dali.sysykeji.top/Article/details/gt2eostanoy.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2gybpkqsl.html

[K01] 对象转 JSON 字符串
来源：http://dali.daria6918.cn/Article/details/gt2eahgeuyr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jianghu66.top/Article/details/gt2luztsawa.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigufen.top/Article/details/gt2icqioske.html

JS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2tugxskqf.html

TS:   JSON.stringify(obj)
来源：http://dali.hammf.cn/Article/details/gt2kpeggsnh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gzhubu.top/Article/details/gt2ljahhsev.html

Go:   json.Marshal(obj)
来源：http://dali.xziqi.cn/Article/details/gt2iyhxzcpm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuanzx.com/Article/details/gt2favrdrfu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xziqi.cn/Article/details/gt2amtsbtnf.html

[K02] JSON 字符串转对象
来源：http://dali.tianlin.xyz/Article/details/gt2ixbqsvof.html

Py:   json.loads(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nlvtazst.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.svipenyu.cn/Article/details/gt2pcqbeeqw.html

JS:   JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gt2vwhieatl.html

TS:   JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pdvzabzw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.birdmap.top/Article/details/gt2pbscjuug.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kqdqzzts.html

Ruby: JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gewaczqz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nwbrower.top/Article/details/gt2ohceosyt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.meibo888.top/Article/details/gt2asrznzam.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ppjwa.cn/Article/details/gt2mtemynmi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gt2ipcvugit.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sufxvd.cn/Article/details/gt2oagcozju.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ybcxt.top/Article/details/gt2ezbanwcp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2iodhnbpv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jqgfzy.top/Article/details/gt2hjhehxxw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.aizwys.cn/Article/details/gt2uurhueix.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.dianchejie.cn/Article/details/gt2ivjyehtl.html

[K04] 读取 JSON 文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2amrhjphu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.snrcjt.cn/Article/details/gt2tmjpjnbg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yuxming.cn/Article/details/gt2cuerhfhw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daxiang520.top/Article/details/gt2zbulgifp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dianchejie.cn/Article/details/gt2bpkjkixt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jianghu66.top/Article/details/gt2xhpdtqva.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fbohbadj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hnxiangtu.top/Article/details/gt2bmabtnay.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jqgfzy.top/Article/details/gt2paqytqdp.html

[K05] 深拷贝对象
来源：http://dali.xuanzx.com/Article/details/gt2qotqgoxk.html

Py:   copy.deepcopy(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2wtllakqm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj20258.top/Article/details/gt2mcrlxrdy.html

JS:   structuredClone(obj)
来源：http://dali.mhx1999.top/Article/details/gt2ldbhblos.html

TS:   structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fakwrdyt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nwbrower.top/Article/details/gt2fkaijbdd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258.top/Article/details/gt2rtovuohs.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.dianchejie.cn/Article/details/gt2owgxtqby.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenzaomai.com/Article/details/gt2wyoczrus.html

[K06] 解析 URL 查询串
来源：http://dali.sxryk.cn/Article/details/gt2pexddmcs.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hnqzz.top/Article/details/gt2mnjommtz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.havefunace.top/Article/details/gt2hsmgaujq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wxqdkdrx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xinyue.icu/Article/details/gt2tbecuaki.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.haohaochexian.top/Article/details/gt2yvhwbdja.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gt2noqhfccp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gt2zcrwgknc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gt2tiskbewo.html

[K07] 进制转换
来源：http://dali.sysykeji.top/Article/details/gt2rrbevvcx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2vcsnlcdn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zdqjudy.top/Article/details/gt2rhehaldz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nzemagqu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gt2ymfhkpst.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gt2inwmflkz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daxiang520.top/Article/details/gt2gkwpfvjn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rzqhoquo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258.top/Article/details/gt2lsldktat.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.wangshuangyany.cn/Article/details/gt2gbwowfuv.html

Py:   pickle.dumps(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2lbcbbsma.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2aljoqzxl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.c1oappe.top/Article/details/gt2kwznemoy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yuanzhike.top/Article/details/gt2fztzuqor.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hammf.cn/Article/details/gt2dggszczv.html

Go:   encoding/gob
来源：http://dali.fengsongda.top/Article/details/gt2towjclxr.html

Ruby: Marshal.dump(obj)
来源：http://dali.tanke756.top/Article/details/gt2snxoydhr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.quarkkingdee.top/Article/details/gt2fqiakgju.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2nsomqfcb.html

L. 网络请求
来源：http://dali.daxiang520.top/Article/details/gt2vuuyqzar.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2whjnhzol.html

[L01] 发送 GET 请求
来源：http://dali.xuanzx.com/Article/details/gt2lovatywx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.birdmap.top/Article/details/gt2fefczsri.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.haohaochexian.top/Article/details/gt2dlbbwffg.html

JS:   await fetch(url)
来源：http://dali.gogol.net.cn/Article/details/gt2snjsxmgw.html

TS:   await fetch(url)
来源：http://dali.quarkkingdee.top/Article/details/gt2vuogpnrx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yangfankeji.com/Article/details/gt2juwdidwt.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj20258.top/Article/details/gt2hthbpzzp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.andypj.xyz/Article/details/gt2omxwferc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.guannengcc.top/Article/details/gt2zkldemtf.html

[L02] 发送 POST JSON
来源：http://dali.zhoulong.xyz/Article/details/gt2cxfzwsdt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xziqi.cn/Article/details/gt2tltbxrft.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hammf.cn/Article/details/gt2biazzdja.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dashuyun.cn/Article/details/gt2juwvpomy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sweek.top/Article/details/gt2bevwgtlz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenjidiqi.icu/Article/details/gt2rggjllnj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.vqdsnc.cn/Article/details/gt2tlnjinwr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ydzc1.top/Article/details/gt2rttormed.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgfzy.top/Article/details/gt2tcvoxvqm.html

[L03] 设置自定义请求头
来源：http://dali.snrcjt.cn/Article/details/gt2umsjxwch.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cheryme.top/Article/details/gt2hhooncaa.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nanxuanxn.top/Article/details/gt2wbqickws.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cheryme.top/Article/details/gt2ddkppanb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gotoacloud.top/Article/details/gt2amzfbsel.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhoulong.xyz/Article/details/gt2omnzncgv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gt2rctzmypf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenlongwang.top/Article/details/gt2xvqvsfoj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yvedp.cn/Article/details/gt2vzoprnln.html

[L04] 设置超时
来源：http://dali.quarkkingdee.top/Article/details/gt2bsaijwci.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cucudq.cn/Article/details/gt2mtvvhjbl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gzhubu.top/Article/details/gt2cokaabnj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gt2eiwjqyig.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dbhzvlwm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daxiang520.top/Article/details/gt2tichwhhb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hfpthk.cn/Article/details/gt2bzqfkunt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yvedp.cn/Article/details/gt2icfrdufu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gogol.net.cn/Article/details/gt2zgbygtgz.html

[L05] 上传文件（multipart）
来源：http://dali.kuanghao11.cn/Article/details/gt2ybwppjed.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.kuanghao11.cn/Article/details/gt2pooylonk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jianghu66.top/Article/details/gt2fuczfpih.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gt2sqjiobxz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sufxvd.cn/Article/details/gt2eihvybbx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.aizwys.cn/Article/details/gt2cvvfvadt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hammf.cn/Article/details/gt2tvsmdgon.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinqigufen.top/Article/details/gt2yrdsmnhc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2djobjdyr.html

[L06] 解析响应为 JSON
来源：http://dali.ehwqpu.com/Article/details/gt2gdwsxxiq.html

Py:   resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gt2rvlphbvg.html

PHP:  json_decode($body, true);
来源：http://dali.yongpay.top/Article/details/gt2alpmtlkd.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2egoigcll.html

TS:   await resp.json()
来源：http://dali.hysaishi.cn/Article/details/gt2njnwzhlg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cucudq.cn/Article/details/gt2lgaigaqh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zdqjudy.top/Article/details/gt2bihyumpj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.meibo888.top/Article/details/gt2taxesjcw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigufen.top/Article/details/gt2tmpzrnqi.html

[L07] 处理 HTTP 状态码
来源：http://dali.gzhubu.top/Article/details/gt2sdlaqzwg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gotoacloud.top/Article/details/gt2knmhlyzn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.0kj1m.cn/Article/details/gt2vpvtbvvv.html

JS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gt2mnlkiuyw.html

TS:   resp.ok;  resp.status
来源：http://dali.guannengcc.top/Article/details/gt2xeabfawj.html

Java: resp.statusCode()
来源：http://dali.jyoumei.cn/Article/details/gt2keummtrt.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2eazqmoxp.html

Ruby: resp.code.to_i
来源：http://dali.yj20258888.top/Article/details/gt2lrqylswl.html

C#:   (int)resp.StatusCode
来源：http://dali.daxiang520.top/Article/details/gt2wfnbetlg.html

[L08] 并发请求多个地址
来源：http://dali.tian-w.cn/Article/details/gt2gozgqkjh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cdnleiting.top/Article/details/gt2chjclgdj.html

PHP:  curl_multi_init() 系列
来源：http://dali.vqdsnc.cn/Article/details/gt2yaqxoorf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gt2hpbsrjce.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.c1oappe.top/Article/details/gt2zjflatth.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.kuanghao11.cn/Article/details/gt2vjprsnif.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nanxuanxn.top/Article/details/gt2wdlyvhwf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yuxming.cn/Article/details/gt2qnyngaor.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.9152youxi.cn/Article/details/gt2xvzotcsg.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2inackaug.html

M. 命令行 / 进程 / 环境
来源：http://dali.yuxming.cn/Article/details/gt2zcrjxuos.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wdcpxvzk.html

[M01] 读取命令行参数
来源：http://dali.jyoumei.cn/Article/details/gt2mnwwoebp.html

Py:   sys.argv[1:]
来源：http://dali.daria6918.cn/Article/details/gt2yxkbumze.html

PHP:  $argv;  $argc;
来源：http://dali.havefunace.top/Article/details/gt2ciexvizb.html

JS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gt2cfgoaihb.html

TS:   process.argv.slice(2)
来源：http://dali.ydzc1.top/Article/details/gt2yyhtvflz.html

Java: args 数组（main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gt2suatvuuh.html

Go:   os.Args[1:]
来源：http://dali.nanxuanxn.top/Article/details/gt2uiicyeep.html

Ruby: ARGV
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fkckqmer.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jianghu66.top/Article/details/gt2ekdpqxog.html

[M02] 读取环境变量
来源：http://dali.yj202588.top/Article/details/gt2gsfeolct.html

Py:   os.environ.get("HOME")
来源：http://dali.sxryk.cn/Article/details/gt2bqjflfsd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gt2jdpuhldo.html

JS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gt2csjywdlx.html

TS:   process.env.HOME
来源：http://dali.shzxlz.cn/Article/details/gt2dduljzqx.html

Java: System.getenv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gt2kkmtwsfq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gbkdaytr.html

Ruby: ENV["HOME"]
来源：http://dali.pycfn.com/Article/details/gt2chefbxfy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jqgfzy.top/Article/details/gt2wuuycgmp.html

[M03] 执行外部命令
来源：http://dali.wangshuangyany.cn/Article/details/gt2vahlweys.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.dashuyun.cn/Article/details/gt2bexxoztf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.c1oappe.top/Article/details/gt2achfngbh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xinyue.icu/Article/details/gt2oevphdxi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.meibo888.top/Article/details/gt2jamcdvui.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.daria6918.cn/Article/details/gt2dbyupxjj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xylfe.cn/Article/details/gt2gjnaxewc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gaohongyu789.top/Article/details/gt2gpueufeo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gaohongyu789.top/Article/details/gt2tfqfilqk.html

[M04] 获取当前工作目录
来源：http://dali.andypj.xyz/Article/details/gt2rgomndda.html

Py:   os.getcwd()
来源：http://dali.chenzaomai.com/Article/details/gt2emuyxzxi.html

PHP:  getcwd();
来源：http://dali.haohaochexian.top/Article/details/gt2jipsntwi.html

JS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gt2zybsymak.html

TS:   process.cwd()
来源：http://dali.aizwys.cn/Article/details/gt2utdhtfos.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.snrcjt.cn/Article/details/gt2wibeooif.html

Go:   os.Getwd()
来源：http://dali.xziqi.cn/Article/details/gt2njismxcd.html

Ruby: Dir.pwd
来源：http://dali.hysaishi.cn/Article/details/gt2tddkvvbi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenlongwang.top/Article/details/gt2zqgwtsyz.html

[M05] 设置退出码
来源：http://dali.hnxiangtu.top/Article/details/gt2pjshmibw.html

Py:   sys.exit(1)
来源：http://dali.xuanzx.com/Article/details/gt2lyzpgxou.html

PHP:  exit(1);
来源：http://dali.wangdashe.top/Article/details/gt2hccciqae.html

JS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gt2wnomjqib.html

TS:   process.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gt2rfyzsbqy.html

Java: System.exit(1)
来源：http://dali.birdmap.top/Article/details/gt2soepbtai.html

Go:   os.Exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2xifabbcy.html

Ruby: exit 1
来源：http://dali.vqdsnc.cn/Article/details/gt2gsxjvpwg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.pycfn.com/Article/details/gt2qbrgxazd.html

[M06] 向标准错误输出
来源：http://dali.quarkkingdee.top/Article/details/gt2yxpgpyby.html

Py:   print("err", file=sys.stderr)
来源：http://dali.smart0.xyz/Article/details/gt2hqvhawmg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.guowangkeji.top/Article/details/gt2qcjkigmt.html

JS:   console.error("err")
来源：http://dali.andypj.xyz/Article/details/gt2ypfmnrap.html

TS:   console.error("err")
来源：http://dali.ybcxt.top/Article/details/gt2qcpphbod.html

Java: System.err.println("err")
来源：http://dali.yanxiufei.cn/Article/details/gt2exzvfoad.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cqqwz.cn/Article/details/gt2wiptfdjb.html

Ruby: warn "err"
来源：http://dali.shangyingyoupin.top/Article/details/gt2boknzpge.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dynjbtsg.html

[M07] 判断是否为主入口
来源：http://dali.gogol.net.cn/Article/details/gt2hnbdbzzu.html

Py:   if __name__ == "__main__":
来源：http://dali.0kj1m.cn/Article/details/gt2tbxmqkwe.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuxming.cn/Article/details/gt2rehtajyp.html

JS:   require.main === module
来源：http://dali.jianghu66.top/Article/details/gt2jvyqmlyb.html

TS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gt2mdvmahky.html

Java: public static void main(String[] args)
来源：http://dali.cashguo.top/Article/details/gt2gqpwnpde.html

Go:   func main()
来源：http://dali.nanxinkj.top/Article/details/gt2zthwvkrn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xoavnelm.html

C#:   static void Main(string[] args)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bgxtdlkd.html

[M08] 获取系统与运行时信息
来源：http://dali.jlsjyb.cn/Article/details/gt2tnfgjpso.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cashguo.top/Article/details/gt2rtcgmyci.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hysaishi.cn/Article/details/gt2erragcev.html

JS:   process.platform;  process.version
来源：http://dali.nwbrower.top/Article/details/gt2fsowzmre.html

TS:   process.platform;  process.version
来源：http://dali.quarkkingdee.top/Article/details/gt2zbtgjvoi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xylfe.cn/Article/details/gt2bfojeqre.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.316326.xyz/Article/details/gt2pkdhpbpr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.dianchejie.cn/Article/details/gt2ghclfplf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuetiantiany.cn/Article/details/gt2cejzmoqk.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2uchqwley.html

N. 数据结构与算法
来源：http://dali.yuxming.cn/Article/details/gt2myuvbfhi.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2yrkbbxxm.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigufen.top/Article/details/gt2zbdfwkcy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gt2wljsofdm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sufxvd.cn/Article/details/gt2umjspomu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tanke756.top/Article/details/gt2dxqeoupw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zycfv.cn/Article/details/gt2mawsglej.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ivvv.top/Article/details/gt2adwzowlk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gt2lmroblal.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cashguo.top/Article/details/gt2cibcyewu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj20258888.top/Article/details/gt2klmgqirx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2ezicgqpd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.kuanghao11.cn/Article/details/gt2tuiggxbk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gzhubu.top/Article/details/gt2mhcpfrle.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gt2najbqzjw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gt2srsyiscp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rmecdjps.html

Go:   slices.Sort(arr)
来源：http://dali.birdmap.top/Article/details/gt2uzvsofwf.html

Ruby: arr.sort
来源：http://dali.cheryme.top/Article/details/gt2etzeijby.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.dianchejie.cn/Article/details/gt2godaumep.html

[N03] 快速排序（分治示例）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xshtyyqf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhiwuduotai.top/Article/details/gt2wqomytro.html

PHP:  // 递归实现，或用 usort
来源：http://dali.smart0.xyz/Article/details/gt2cicwrvbr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhengqikj.top/Article/details/gt2psavwrms.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hysaishi.cn/Article/details/gt2podwctrz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shzxlz.cn/Article/details/gt2qtlsavhp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qqietxfy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tianlin.xyz/Article/details/gt2jtwfuhfo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.pengpengdd.cyou/Article/details/gt2yrlhnzwi.html

[N04] 斐波那契数列
来源：http://dali.birdmap.top/Article/details/gt2xmikztjt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zycfv.cn/Article/details/gt2nyjdrrhn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yueranfly.top/Article/details/gt2tmtrzugn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tsygtuol.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gt2zeskaswa.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.vqdsnc.cn/Article/details/gt2suxqcygp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.svipenyu.cn/Article/details/gt2hkcyzvhk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.bjfxy.top/Article/details/gt2voajikyw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ffmemcao.html


<!-- 参考信息 -->