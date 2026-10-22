代发 wailian999

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.9152youxi.cn/Article/details/gt2lylnumnp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhengqikj.top/Article/details/gt2zfzzekcc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cvrhyddb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnazkel.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhixingplan.top/Article/details/gt2tvwfyebv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.snrcjt.cn/Article/details/gt2gmdhjcwp.html

[J09] 时区处理
来源：http://dali.aizwys.cn/Article/details/gt2anczbfxj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yuxming.cn/Article/details/gt2rfeftpvi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qhblmswv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fengsongda.top/Article/details/gt2pkhlrfls.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wbxpbmvm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jurfynrm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sweek.top/Article/details/gt2lyfxsjgo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ppjwa.cn/Article/details/gt2imgyrtbc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hysaishi.cn/Article/details/gt2gsivotlp.html

[J10] 取今天 / 本月第一天
来源：http://dali.svipenyu.cn/Article/details/gt2knfsunnt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj20258888.top/Article/details/gt2ptbiuzbw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.bjfxy.top/Article/details/gt2jnwbcmhm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zycfv.cn/Article/details/gt2olkpbjyl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.guannengcc.top/Article/details/gt2kryjbmrj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cheryme.top/Article/details/gt2xhvqwtay.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shzxlz.cn/Article/details/gt2svtxfmvi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cdnleiting.top/Article/details/gt2jhfiesas.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xylfe.cn/Article/details/gt2dyojgiwb.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2yhufwktf.html

K. JSON 与序列化
来源：http://dali.nanxuanxn.top/Article/details/gt2amazlsdb.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2sldtnyce.html

[K01] 对象转 JSON 字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2gjeaejjy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yuanzhike.top/Article/details/gt2etvmqfxu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yuxming.cn/Article/details/gt2vuplmoek.html

JS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2avcueuuz.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2tjrjmdhf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.wangdashe.top/Article/details/gt2ffzfpysr.html

Go:   json.Marshal(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2famzbwpw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.smart0.xyz/Article/details/gt2iduafepa.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.birdmap.top/Article/details/gt2jizposos.html

[K02] JSON 字符串转对象
来源：http://dali.sufxvd.cn/Article/details/gt2nxxziuwa.html

Py:   json.loads(s)
来源：http://dali.zhengqikj.top/Article/details/gt2vlmfsxrw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.snrcjt.cn/Article/details/gt2towpbqap.html

JS:   JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gt2zgeeaucw.html

TS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2xdgkxcpw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.9152youxi.cn/Article/details/gt2jpdylkzn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gt2xvdocewo.html

Ruby: JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gt2yjxcdxlb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tanke756.top/Article/details/gt2uztbjdxj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhoulong.xyz/Article/details/gt2tgbtyfly.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shzxlz.cn/Article/details/gt2iajcrkjd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hfpthk.cn/Article/details/gt2mhkypxba.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hammf.cn/Article/details/gt2rfckntrb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiyiwwxq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2gzploemk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shuidangran.top/Article/details/gt2kwiwhmoa.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ivvv.top/Article/details/gt2dpxshwhh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gogol.net.cn/Article/details/gt2bvyftawl.html

[K04] 读取 JSON 文件
来源：http://dali.shzxlz.cn/Article/details/gt2gxcdnkbo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.daria6918.cn/Article/details/gt2ofpjnrvt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.haohaochexian.top/Article/details/gt2gnhxlyzw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.iojbl.cn/Article/details/gt2lmndkxgx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gt2enjwtgvj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tanke756.top/Article/details/gt2yxdvtyfb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ninuvkpx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2qvyawszf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yueranfly.top/Article/details/gt2hjglsyzt.html

[K05] 深拷贝对象
来源：http://dali.c1oappe.top/Article/details/gt2xcydaupg.html

Py:   copy.deepcopy(obj)
来源：http://dali.cheryme.top/Article/details/gt2nizjrmww.html

PHP:  unserialize(serialize($obj));
来源：http://dali.bjfxy.top/Article/details/gt2rybvwdzs.html

JS:   structuredClone(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2okywckbb.html

TS:   structuredClone(obj)
来源：http://dali.daxiang520.top/Article/details/gt2hgntehan.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.meibo888.top/Article/details/gt2hkjkvkbj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yuxming.cn/Article/details/gt2ksfanfit.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yanxiufei.cn/Article/details/gt2mzrjicxj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.c1oappe.top/Article/details/gt2jtrfcdmy.html

[K06] 解析 URL 查询串
来源：http://dali.zhiwuduotai.top/Article/details/gt2dlapohge.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.redwolf501.top/Article/details/gt2lqahswxp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.vqdsnc.cn/Article/details/gt2fbddlxpj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigfzy.top/Article/details/gt2hhjkuzgj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.0kj1m.cn/Article/details/gt2opgridfv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkzqqxq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gt2opebsdgs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gt2vunmvjkg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gt2treqaxhs.html

[K07] 进制转换
来源：http://dali.vqdsnc.cn/Article/details/gt2smazbtsx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gt2grvtikvb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ydzc1.top/Article/details/gt2jdshaaae.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2ypqvbugb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2zcdpxmpp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gt2kchbjgdi.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2imfztxzs.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.iojbl.cn/Article/details/gt2wpnksmcq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gt2hxbsawjm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.andypj.xyz/Article/details/gt2sibziico.html

Py:   pickle.dumps(obj)
来源：http://dali.sxryk.cn/Article/details/gt2jrfhfodn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2kikymekd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258888.top/Article/details/gt2sitmklbu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gt2wbredcfk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhengqikj.top/Article/details/gt2xefjakke.html

Go:   encoding/gob
来源：http://dali.ppjwa.cn/Article/details/gt2vykjekhv.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtegtbl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.haohaochexian.top/Article/details/gt2pvhcjtur.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2vhorpplx.html

L. 网络请求
来源：http://dali.chenlongwang.top/Article/details/gt2mckxzazf.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2twbhtqjs.html

[L01] 发送 GET 请求
来源：http://dali.guannengcc.top/Article/details/gt2urhuttdw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.0kj1m.cn/Article/details/gt2vdnywgir.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenzaomai.com/Article/details/gt2vaqrzhev.html

JS:   await fetch(url)
来源：http://dali.xinyue.icu/Article/details/gt2henbxkiq.html

TS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gt2ezhgexla.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tianlin.xyz/Article/details/gt2klemlyrp.html

Go:   resp, err := http.Get(url)
来源：http://dali.cdnleiting.top/Article/details/gt2kkqbysus.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.0kj1m.cn/Article/details/gt2rnhxkcmy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yonumen.top/Article/details/gt2qljzmqfm.html

[L02] 发送 POST JSON
来源：http://dali.hongshengwenyu.top/Article/details/gt2lduepwth.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yvedp.cn/Article/details/gt2hwjaqgnu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hongshengwenyu.top/Article/details/gt2evbdttcm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gt2satiyhtu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tian-w.cn/Article/details/gt2pqonpolg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tian-w.cn/Article/details/gt2lfwzkctp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ppjwa.cn/Article/details/gt2uzbdhcyg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.andypj.xyz/Article/details/gt2pautynvd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yuxming.cn/Article/details/gt2khszduye.html

[L03] 设置自定义请求头
来源：http://dali.guannengcc.top/Article/details/gt2nrisvlcs.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjzgzoy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinqigufen.top/Article/details/gt2dqbxpavv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hongshengwenyu.top/Article/details/gt2qezthnnl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gogol.net.cn/Article/details/gt2rmviynex.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.c1oappe.top/Article/details/gt2ihdlpjrs.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gt2asxzrqrp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258888.top/Article/details/gt2beljtmcg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gt2gktvroul.html

[L04] 设置超时
来源：http://dali.ivvv.top/Article/details/gt2mtimtztl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yonumen.top/Article/details/gt2knrawypu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.redwolf501.top/Article/details/gt2yomqncvw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258.top/Article/details/gt2gbvunvzj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ehwqpu.com/Article/details/gt2wbjerrmf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ivvv.top/Article/details/gt2nuqptdoz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cheryme.top/Article/details/gt2pgmsulro.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhongyouzk.top/Article/details/gt2csswicwo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shangyingyoupin.top/Article/details/gt2gqyeshmw.html

[L05] 上传文件（multipart）
来源：http://dali.c1oappe.top/Article/details/gt2upkkpted.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.aibaodan.cn/Article/details/gt2lgseaidr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuxming.cn/Article/details/gt2tzlepomw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sxryk.cn/Article/details/gt2bybtwhhi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jyoumei.cn/Article/details/gt2koznrgmq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenlongwang.top/Article/details/gt2tloyiqvh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ehwqpu.com/Article/details/gt2iranjnyr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.meibo888.top/Article/details/gt2wevetrmu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2ywdopami.html

[L06] 解析响应为 JSON
来源：http://dali.jqgfzy.top/Article/details/gt2tcddthkc.html

Py:   resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gt2zlaeqjbs.html

PHP:  json_decode($body, true);
来源：http://dali.snrcjt.cn/Article/details/gt2vomjgjbt.html

JS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gt2xlsnysyr.html

TS:   await resp.json()
来源：http://dali.fzhhl.top/Article/details/gt2gfpqnwvg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gt2twyczhkk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.redwolf501.top/Article/details/gt2umdajynb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.smart0.xyz/Article/details/gt2trtbbsnc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.c1oappe.top/Article/details/gt2oahygqym.html

[L07] 处理 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gt2fvciaqtc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sxryk.cn/Article/details/gt2sgjrhulp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jianghu66.top/Article/details/gt2xrlsocxe.html

JS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gt2wvcvadwq.html

TS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gt2urtdyxgy.html

Java: resp.statusCode()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fcugoklk.html

Go:   resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gt2uacjdozx.html

Ruby: resp.code.to_i
来源：http://dali.yuanzhike.top/Article/details/gt2onwucfje.html

C#:   (int)resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gt2zzzkyelc.html

[L08] 并发请求多个地址
来源：http://dali.yj202588.top/Article/details/gt2kprobfbc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hywenlv.cn/Article/details/gt2lcvfbwsa.html

PHP:  curl_multi_init() 系列
来源：http://dali.iojbl.cn/Article/details/gt2qlnezadt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gt2skpjphko.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gt2rpkklogq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yvedp.cn/Article/details/gt2rycuxrsg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gotoacloud.top/Article/details/gt2xgysjydw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tian-w.cn/Article/details/gt2alyitjud.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xziqi.cn/Article/details/gt2qsmsqday.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2pkupkcux.html

M. 命令行 / 进程 / 环境
来源：http://dali.birdmap.top/Article/details/gt2kedwkwdo.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2jwcmvnnm.html

[M01] 读取命令行参数
来源：http://dali.tianlin.xyz/Article/details/gt2sjnccmxu.html

Py:   sys.argv[1:]
来源：http://dali.redwolf501.top/Article/details/gt2aodnkznl.html

PHP:  $argv;  $argc;
来源：http://dali.sxryk.cn/Article/details/gt2eaurosns.html

JS:   process.argv.slice(2)
来源：http://dali.quarkkingdee.top/Article/details/gt2uwczrhsj.html

TS:   process.argv.slice(2)
来源：http://dali.cashguo.top/Article/details/gt2ocaiqfzj.html

Java: args 数组（main 方法参数）
来源：http://dali.ydzc1.top/Article/details/gt2reayqkps.html

Go:   os.Args[1:]
来源：http://dali.xylfe.cn/Article/details/gt2evrmqwhz.html

Ruby: ARGV
来源：http://dali.hnqzz.top/Article/details/gt2wjopsrcm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bwbkrdqc.html

[M02] 读取环境变量
来源：http://dali.chenzaomai.com/Article/details/gt2ypndmvth.html

Py:   os.environ.get("HOME")
来源：http://dali.yuxming.cn/Article/details/gt2jamtjwrn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.quarkkingdee.top/Article/details/gt2oxoygxws.html

JS:   process.env.HOME
来源：http://dali.redwolf501.top/Article/details/gt2zzjvxptk.html

TS:   process.env.HOME
来源：http://dali.tianlin.xyz/Article/details/gt2quodczlp.html

Java: System.getenv("HOME")
来源：http://dali.sxryk.cn/Article/details/gt2fkishvwg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sxryk.cn/Article/details/gt2iquplaot.html

Ruby: ENV["HOME"]
来源：http://dali.yvedp.cn/Article/details/gt2ojmjrhat.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sahspsvq.html

[M03] 执行外部命令
来源：http://dali.cheryme.top/Article/details/gt2xdixtoiw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gzhubu.top/Article/details/gt2tygpgtui.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.feifeiyinyue.top/Article/details/gt2nhrutbaq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cashguo.top/Article/details/gt2gconfanw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.andypj.xyz/Article/details/gt2ihtwnpgn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.c1oappe.top/Article/details/gt2iznoqjdd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gogol.net.cn/Article/details/gt2bulabjfy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangshuangyany.cn/Article/details/gt2jsvzorfm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nwbrower.top/Article/details/gt2heejyscr.html

[M04] 获取当前工作目录
来源：http://dali.ehwqpu.com/Article/details/gt2thfeyqzg.html

Py:   os.getcwd()
来源：http://dali.ydzc1.top/Article/details/gt2jimgnxpd.html

PHP:  getcwd();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lpboqyin.html

JS:   process.cwd()
来源：http://dali.fengsongda.top/Article/details/gt2cjpnddcy.html

TS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gt2fjafqgxq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zycfv.cn/Article/details/gt2mebnqvyx.html

Go:   os.Getwd()
来源：http://dali.tian-w.cn/Article/details/gt2zbkyfene.html

Ruby: Dir.pwd
来源：http://dali.havefunace.top/Article/details/gt2jnrhvdul.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhixingplan.top/Article/details/gt2pwumhqvm.html

[M05] 设置退出码
来源：http://dali.tanke756.top/Article/details/gt2fooebsud.html

Py:   sys.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ptabhhls.html

PHP:  exit(1);
来源：http://dali.gaohongyu789.top/Article/details/gt2rlgoozoc.html

JS:   process.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2nzngxhit.html

TS:   process.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gt2jpqlgnld.html

Java: System.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bruxbuvg.html

Go:   os.Exit(1)
来源：http://dali.chenlongwang.top/Article/details/gt2tyigwfde.html

Ruby: exit 1
来源：http://dali.bjfxy.top/Article/details/gt2mqmjtwef.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yuanzhike.top/Article/details/gt2radxqsjz.html

[M06] 向标准错误输出
来源：http://dali.mhx1999.top/Article/details/gt2eqjwtdlf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sufxvd.cn/Article/details/gt2pnpmvynm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenlongwang.top/Article/details/gt2nuqwxbqh.html

JS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gt2jybmexjr.html

TS:   console.error("err")
来源：http://dali.yvedp.cn/Article/details/gt2rrsisqoc.html

Java: System.err.println("err")
来源：http://dali.fengsongda.top/Article/details/gt2igcyyary.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hongshengwenyu.top/Article/details/gt2jpxtsqcj.html

Ruby: warn "err"
来源：http://dali.aizwys.cn/Article/details/gt2dcbimgwt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.wangdashe.top/Article/details/gt2kuuxtrgb.html

[M07] 判断是否为主入口
来源：http://dali.yanxiufei.cn/Article/details/gt2trodwlta.html

Py:   if __name__ == "__main__":
来源：http://dali.hysaishi.cn/Article/details/gt2mgffnems.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinqigufen.top/Article/details/gt2dsjuqivu.html

JS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gt2rkzmjnmt.html

TS:   require.main === module
来源：http://dali.quarkkingdee.top/Article/details/gt2ldnpokst.html

Java: public static void main(String[] args)
来源：http://dali.c1oappe.top/Article/details/gt2sudzopmv.html

Go:   func main()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zibnsomq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xinyue.icu/Article/details/gt2rboapgas.html

C#:   static void Main(string[] args)
来源：http://dali.sufxvd.cn/Article/details/gt2factdgdw.html

[M08] 获取系统与运行时信息
来源：http://dali.hnxiangtu.top/Article/details/gt2akkmvhxn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wexlzppq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shuidangran.top/Article/details/gt2ejkbamjm.html

JS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gt2vnqksdbn.html

TS:   process.platform;  process.version
来源：http://dali.hfpthk.cn/Article/details/gt2wvjtduia.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ehwqpu.com/Article/details/gt2xylacdsy.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shzxlz.cn/Article/details/gt2jzdeykgt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cheryme.top/Article/details/gt2fukdhhmg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2crxtovvv.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2qhgfcuci.html

N. 数据结构与算法
来源：http://dali.smart0.xyz/Article/details/gt2rhfgchag.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2rxnfygat.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgufenzy.top/Article/details/gt2wvbsonyt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gt2erysdjzr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.haohaochexian.top/Article/details/gt2iyutydog.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gt2eqfssvfu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xziqi.cn/Article/details/gt2neptrsty.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gt2lyhkusqy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2jfzjbhxa.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cheryme.top/Article/details/gt2dlbvawcb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2sbqefqks.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenjidiqi.icu/Article/details/gt2tzqugmok.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.andypj.xyz/Article/details/gt2zidhollu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gt2habwggks.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gt2opfuczcx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daxiang520.top/Article/details/gt2knzjaxnl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yongpay.top/Article/details/gt2veiyaqci.html

Go:   slices.Sort(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2bxtbxjhq.html

Ruby: arr.sort
来源：http://dali.jiagoushi.top/Article/details/gt2gvxrhoyn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aibaodan.cn/Article/details/gt2fwaliyzh.html

[N03] 快速排序（分治示例）
来源：http://dali.havefunace.top/Article/details/gt2rlljntwt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jiagoushi.top/Article/details/gt2crcqmpii.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hywenlv.cn/Article/details/gt2hamdaucf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jiagoushi.top/Article/details/gt2tnwgdzpz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yvedp.cn/Article/details/gt2eqwfwkyi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yonumen.top/Article/details/gt2kwiesbzc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhixingplan.top/Article/details/gt2zooyxyqt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cqqwz.cn/Article/details/gt2ykwzhkmv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ivvv.top/Article/details/gt2hvkjchvf.html

[N04] 斐波那契数列
来源：http://dali.sufxvd.cn/Article/details/gt2ffxlnolj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ppjwa.cn/Article/details/gt2vjtgdhqj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhongyouzk.top/Article/details/gt2fgxfoimg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gt2uwoapdzs.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gt2wygequyi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.smart0.xyz/Article/details/gt2kqpkemob.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhixingplan.top/Article/details/gt2izyzivue.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gt2rlqixptq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gt2rhzqahff.html

[N05] 最大公约数
来源：http://dali.316326.xyz/Article/details/gt2vscftiaq.html

Py:   math.gcd(a, b)
来源：http://dali.yj202588.top/Article/details/gt2umpvenpm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinqigfzy.top/Article/details/gt2xbddmdvc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cqqwz.cn/Article/details/gt2vednirjb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xziqi.cn/Article/details/gt2vxxaswxq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.pengpengdd.cyou/Article/details/gt2fioqmyvs.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.fzhhl.top/Article/details/gt2prxgjfqa.html

Ruby: a.gcd(b)
来源：http://dali.sweek.top/Article/details/gt2nsixhmch.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zycfv.cn/Article/details/gt2wxjwvbbr.html

[N06] 判断回文字符串
来源：http://dali.cdnleiting.top/Article/details/gt2ytwczgaw.html

Py:   s == s[::-1]
来源：http://dali.yangfankeji.com/Article/details/gt2iqbwivsf.html

PHP:  $s === strrev($s);
来源：http://dali.yvedp.cn/Article/details/gt2oivsmazb.html


<!-- 参考信息 -->