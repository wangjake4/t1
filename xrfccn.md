代发 wailian999

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shzxlz.cn/Article/details/gt2yhuqyqyh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenzaomai.com/Article/details/gt2sgwibqlc.html

[J09] 时区处理
来源：http://dali.chenzaomai.com/Article/details/gt2buyzkcys.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.wangdashe.top/Article/details/gt2durtuzrm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yuxming.cn/Article/details/gt2csooekzj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tianlin.xyz/Article/details/gt2suuqasqt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aqzpbyjr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhongyouzk.top/Article/details/gt2tjjhaabe.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nhbuxfew.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.aizwys.cn/Article/details/gt2efkhvzmd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.0kj1m.cn/Article/details/gt2zevymobf.html

[J10] 取今天 / 本月第一天
来源：http://dali.daxiang520.top/Article/details/gt2bltnmrzn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sysykeji.top/Article/details/gt2metcbpfu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj202588.top/Article/details/gt2mtqluucv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xirjyetg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qrstqgwl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nanxinkj.top/Article/details/gt2xxwuuejv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shangyingyoupin.top/Article/details/gt2icaoikuq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gmichxxe.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cashguo.top/Article/details/gt2tkhnpkbw.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2forvuiwb.html

K. JSON 与序列化
来源：http://dali.shangyingyoupin.top/Article/details/gt2zijmudmj.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2pilfptol.html

[K01] 对象转 JSON 字符串
来源：http://dali.xziqi.cn/Article/details/gt2njriwrqw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.snrcjt.cn/Article/details/gt2yuidazhm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gt2svfktghu.html

JS:   JSON.stringify(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rnlrpyld.html

TS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2voetxnhb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nwbrower.top/Article/details/gt2xqhvgmjj.html

Go:   json.Marshal(obj)
来源：http://dali.jianghu66.top/Article/details/gt2oiuejsps.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hongshengwenyu.top/Article/details/gt2vlnejdms.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ybcxt.top/Article/details/gt2rvwmojkr.html

[K02] JSON 字符串转对象
来源：http://dali.meibo888.top/Article/details/gt2llticdbk.html

Py:   json.loads(s)
来源：http://dali.ehwqpu.com/Article/details/gt2pmmpusvt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2nxaxtmtf.html

JS:   JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2qqkdveso.html

TS:   JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gt2jqlwxfya.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gt2saznygyv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cheryme.top/Article/details/gt2iwgwldcz.html

Ruby: JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gt2siwaauhv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.birdmap.top/Article/details/gt2eznvjeap.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yvedp.cn/Article/details/gt2dsvhdobw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gt2ihujlemd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.guannengcc.top/Article/details/gt2znpefntt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gt2dwurewzj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gt2ctwdbfeq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlrqedl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yangfankeji.com/Article/details/gt2hujeozxh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2gcxeprbt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tanke756.top/Article/details/gt2xsdfdjer.html

[K04] 读取 JSON 文件
来源：http://dali.0kj1m.cn/Article/details/gt2itvxjmya.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gaohongyu789.top/Article/details/gt2ynbnegko.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hywenlv.cn/Article/details/gt2xvpxyvuo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cqqwz.cn/Article/details/gt2tvojzdco.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hfpthk.cn/Article/details/gt2dsugqrsh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2knkagtlk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jyoumei.cn/Article/details/gt2xocexghx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gt2ltljnofe.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.mhx1999.top/Article/details/gt2kmlihlco.html

[K05] 深拷贝对象
来源：http://dali.haohaochexian.top/Article/details/gt2gjruddeq.html

Py:   copy.deepcopy(obj)
来源：http://dali.yonumen.top/Article/details/gt2sukkpnww.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cashguo.top/Article/details/gt2icjrvlpd.html

JS:   structuredClone(obj)
来源：http://dali.mhx1999.top/Article/details/gt2ptzqfuac.html

TS:   structuredClone(obj)
来源：http://dali.cashguo.top/Article/details/gt2rjsrxzbn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.feifeiyinyue.top/Article/details/gt2iegfeahm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hongshengwenyu.top/Article/details/gt2rwzzhhsx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jqgfzy.top/Article/details/gt2ohlevrwq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yonumen.top/Article/details/gt2jytpbydt.html

[K06] 解析 URL 查询串
来源：http://dali.yvedp.cn/Article/details/gt2grdbhjhl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hongshengwenyu.top/Article/details/gt2klgrcvco.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jqgufenzy.top/Article/details/gt2vwcqcqsd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxinkj.top/Article/details/gt2rzqfnczj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gt2isctqmnz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hnqzz.top/Article/details/gt2yjuvtunj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gt2qcmdjqbe.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gt2vytqexgp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gt2qbjosyer.html

[K07] 进制转换
来源：http://dali.shzxlz.cn/Article/details/gt2erduphvd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nqawaghm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jianghu66.top/Article/details/gt2npanslvs.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2ntuxdolg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gt2iidodnyt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2mvuxwact.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yuxming.cn/Article/details/gt2xpdruvgs.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jlsjyb.cn/Article/details/gt2fxyqhrmi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2flzqxycj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.svipenyu.cn/Article/details/gt2zrjepjoi.html

Py:   pickle.dumps(obj)
来源：http://dali.mhx1999.top/Article/details/gt2dvxmilbl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ovsjthzq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gt2nvnwebwu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gaohongyu789.top/Article/details/gt2mnyejkwf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gogol.net.cn/Article/details/gt2pbtgubqi.html

Go:   encoding/gob
来源：http://dali.iojbl.cn/Article/details/gt2dzkruzir.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj20258.top/Article/details/gt2vomaektu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gt2edeqlvxz.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2wazzqoyq.html

L. 网络请求
来源：http://dali.cheryme.top/Article/details/gt2zkhjkqsi.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2ctyoabep.html

[L01] 发送 GET 请求
来源：http://dali.zhongyouzk.top/Article/details/gt2zqoyhiem.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.aizwys.cn/Article/details/gt2kiielumq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.guannengcc.top/Article/details/gt2adxrvlly.html

JS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gt2dxigfumd.html

TS:   await fetch(url)
来源：http://dali.yj20258888.top/Article/details/gt2wttxypwi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jyoumei.cn/Article/details/gt2fvpxcypb.html

Go:   resp, err := http.Get(url)
来源：http://dali.0kj1m.cn/Article/details/gt2cesurldp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hywenlv.cn/Article/details/gt2rtvzsilx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.mhx1999.top/Article/details/gt2jcvzdmnj.html

[L02] 发送 POST JSON
来源：http://dali.yj202588.top/Article/details/gt2offadwfs.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.fengsongda.top/Article/details/gt2zuicidsv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jxluucfl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yongpay.top/Article/details/gt2vbvjqpto.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.snrcjt.cn/Article/details/gt2iupyymeq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cashguo.top/Article/details/gt2qqgqmpod.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gogol.net.cn/Article/details/gt2rkchdmmr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xziqi.cn/Article/details/gt2owmpmnhk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ivvv.top/Article/details/gt2phnzfbfh.html

[L03] 设置自定义请求头
来源：http://dali.jlsjyb.cn/Article/details/gt2rvucvtmx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cqqwz.cn/Article/details/gt2jbkjyapz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj202588.top/Article/details/gt2dcyyzhyl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zycfv.cn/Article/details/gt2jzniciyl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gt2qlsthoyn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xziqi.cn/Article/details/gt2kgkptnfl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.nwbrower.top/Article/details/gt2qqlxnoqo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cqqwz.cn/Article/details/gt2eylsctup.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zycfv.cn/Article/details/gt2rhbrbrgi.html

[L04] 设置超时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2exepdmuf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.svipenyu.cn/Article/details/gt2lyusbuwh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gaohongyu789.top/Article/details/gt2raqinvpa.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.feifeiyinyue.top/Article/details/gt2ylyvtthq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dashuyun.cn/Article/details/gt2mcxsvczi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hysaishi.cn/Article/details/gt2ydtzlvup.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zycfv.cn/Article/details/gt2exrhipip.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jiagoushi.top/Article/details/gt2yiimnrie.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cqqwz.cn/Article/details/gt2cdsrhaqq.html

[L05] 上传文件（multipart）
来源：http://dali.hongshengwenyu.top/Article/details/gt2npaityyi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxuanxn.top/Article/details/gt2bxhjgrlf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenlongwang.top/Article/details/gt2mzjfaple.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gt2tumwovxf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.havefunace.top/Article/details/gt2vyulbnrj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tianlin.xyz/Article/details/gt2zbtnysxs.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sxryk.cn/Article/details/gt2dpyipzob.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.smart0.xyz/Article/details/gt2xjuixivr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2vhkszjrp.html

[L06] 解析响应为 JSON
来源：http://dali.andypj.xyz/Article/details/gt2fttpgmfv.html

Py:   resp.json()
来源：http://dali.jiagoushi.top/Article/details/gt2xlkyaxyj.html

PHP:  json_decode($body, true);
来源：http://dali.shzxlz.cn/Article/details/gt2ngpawtem.html

JS:   await resp.json()
来源：http://dali.gzhubu.top/Article/details/gt2qddzlcxx.html

TS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gufahksl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guowangkeji.top/Article/details/gt2yamztjxz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.dianchejie.cn/Article/details/gt2dcwqntum.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xinyue.icu/Article/details/gt2rlcqyoph.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shzxlz.cn/Article/details/gt2gflysqtm.html

[L07] 处理 HTTP 状态码
来源：http://dali.guannengcc.top/Article/details/gt2hfwubkot.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ydzc1.top/Article/details/gt2hjctmzzg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.dianchejie.cn/Article/details/gt2xpgbogks.html

JS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gt2qobduccq.html

TS:   resp.ok;  resp.status
来源：http://dali.tian-w.cn/Article/details/gt2bswiccgr.html

Java: resp.statusCode()
来源：http://dali.sufxvd.cn/Article/details/gt2nmbzqlgh.html

Go:   resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gt2dkvmdanp.html

Ruby: resp.code.to_i
来源：http://dali.guannengcc.top/Article/details/gt2wrnkjjwx.html

C#:   (int)resp.StatusCode
来源：http://dali.zycfv.cn/Article/details/gt2tpnodnyn.html

[L08] 并发请求多个地址
来源：http://dali.wangdashe.top/Article/details/gt2hrhtghhy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ehwqpu.com/Article/details/gt2rubxeikv.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhoulong.xyz/Article/details/gt2sutaywgq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gt2plfypvti.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sweek.top/Article/details/gt2mtkmtytg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.dianchejie.cn/Article/details/gt2ljyktipf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cucudq.cn/Article/details/gt2qnadmvxj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xnovjqbv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinqigufen.top/Article/details/gt2fivfqgan.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2wjlvilpr.html

M. 命令行 / 进程 / 环境
来源：http://dali.iojbl.cn/Article/details/gt2lsqjtiku.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2nwiptoxl.html

[M01] 读取命令行参数
来源：http://dali.vqdsnc.cn/Article/details/gt2jlthpods.html

Py:   sys.argv[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gt2cpkxohmh.html

PHP:  $argv;  $argc;
来源：http://dali.andypj.xyz/Article/details/gt2piskhjrj.html

JS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gt2fetbhqrh.html

TS:   process.argv.slice(2)
来源：http://dali.meibo888.top/Article/details/gt2cvjdrqle.html

Java: args 数组（main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gt2auyddzpu.html

Go:   os.Args[1:]
来源：http://dali.hammf.cn/Article/details/gt2tkerbmvd.html

Ruby: ARGV
来源：http://dali.fengsongda.top/Article/details/gt2expqvizn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gt2csmmgwxi.html

[M02] 读取环境变量
来源：http://dali.cheryme.top/Article/details/gt2kbmlizwp.html

Py:   os.environ.get("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cewmtewf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pycfn.com/Article/details/gt2sgzoedoe.html

JS:   process.env.HOME
来源：http://dali.quarkkingdee.top/Article/details/gt2wdovafsw.html

TS:   process.env.HOME
来源：http://dali.shzxlz.cn/Article/details/gt2erpsojyh.html

Java: System.getenv("HOME")
来源：http://dali.hnqzz.top/Article/details/gt2nhfqinvs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gt2bcfrcamm.html

Ruby: ENV["HOME"]
来源：http://dali.xuanzx.com/Article/details/gt2sviidrlv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.birdmap.top/Article/details/gt2ieykdtug.html

[M03] 执行外部命令
来源：http://dali.xuetiantiany.cn/Article/details/gt2qpxbfjyg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hywenlv.cn/Article/details/gt2ngcqwhch.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258888.top/Article/details/gt2pvgqlycg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnqzz.top/Article/details/gt2wifkghun.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigfzy.top/Article/details/gt2qhnioear.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhixingplan.top/Article/details/gt2feyxjhfi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aibaodan.cn/Article/details/gt2bfmyhyvg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hammf.cn/Article/details/gt2bownujjn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yonumen.top/Article/details/gt2uusbprvl.html

[M04] 获取当前工作目录
来源：http://dali.birdmap.top/Article/details/gt2pbswrfmy.html

Py:   os.getcwd()
来源：http://dali.jiagoushi.top/Article/details/gt2bqckeeqx.html

PHP:  getcwd();
来源：http://dali.snrcjt.cn/Article/details/gt2uscnczmg.html

JS:   process.cwd()
来源：http://dali.aibaodan.cn/Article/details/gt2voiandar.html

TS:   process.cwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2luzadfzi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gzhubu.top/Article/details/gt2pmvgojcl.html

Go:   os.Getwd()
来源：http://dali.aizwys.cn/Article/details/gt2jzhphjly.html

Ruby: Dir.pwd
来源：http://dali.gogol.net.cn/Article/details/gt2vvuxwdct.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.havefunace.top/Article/details/gt2kjryrvth.html

[M05] 设置退出码
来源：http://dali.ehwqpu.com/Article/details/gt2waoxyfiq.html

Py:   sys.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gt2hwolatdk.html

PHP:  exit(1);
来源：http://dali.yj20258888.top/Article/details/gt2vrrklolz.html

JS:   process.exit(1)
来源：http://dali.cheryme.top/Article/details/gt2konlyury.html

TS:   process.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gt2nlpxmkms.html

Java: System.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gt2pxtncqeg.html

Go:   os.Exit(1)
来源：http://dali.zhixingplan.top/Article/details/gt2ynrkvpbp.html

Ruby: exit 1
来源：http://dali.zycfv.cn/Article/details/gt2qqyubmcw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xinyue.icu/Article/details/gt2ygqbndwk.html

[M06] 向标准错误输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ctsbrvjd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.svipenyu.cn/Article/details/gt2hreurral.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhixingplan.top/Article/details/gt2xnxlpeiz.html

JS:   console.error("err")
来源：http://dali.yanxiufei.cn/Article/details/gt2ebyupxxv.html

TS:   console.error("err")
来源：http://dali.sweek.top/Article/details/gt2hpoepwom.html

Java: System.err.println("err")
来源：http://dali.iojbl.cn/Article/details/gt2kngzuxih.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jqgufenzy.top/Article/details/gt2rgzflxvn.html

Ruby: warn "err"
来源：http://dali.hywenlv.cn/Article/details/gt2awqenxhy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenzaomai.com/Article/details/gt2itcffusu.html

[M07] 判断是否为主入口
来源：http://dali.shuidangran.top/Article/details/gt2iinwiiju.html

Py:   if __name__ == "__main__":
来源：http://dali.cashguo.top/Article/details/gt2rhunwtuj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.guannengcc.top/Article/details/gt2bactctuc.html

JS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gt2jzhtifei.html

TS:   require.main === module
来源：http://dali.hfpthk.cn/Article/details/gt2mwuekoch.html

Java: public static void main(String[] args)
来源：http://dali.mhx1999.top/Article/details/gt2pesdfvjf.html

Go:   func main()
来源：http://dali.jinqigfzy.top/Article/details/gt2sxcikhxl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.pycfn.com/Article/details/gt2njvbdjoh.html

C#:   static void Main(string[] args)
来源：http://dali.ehwqpu.com/Article/details/gt2voehudmn.html

[M08] 获取系统与运行时信息
来源：http://dali.haohaochexian.top/Article/details/gt2tvofjmga.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fzhhl.top/Article/details/gt2bebzhskd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nanxinkj.top/Article/details/gt2tlinjmwy.html

JS:   process.platform;  process.version
来源：http://dali.ppjwa.cn/Article/details/gt2lzwqpspg.html

TS:   process.platform;  process.version
来源：http://dali.quarkkingdee.top/Article/details/gt2uhvbxsvp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sxzzoldb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.0kj1m.cn/Article/details/gt2mqdolcgr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenjidiqi.icu/Article/details/gt2gcebsyjl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bpqislfl.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2ccpcdzyr.html

N. 数据结构与算法
来源：http://dali.zhiwuduotai.top/Article/details/gt2vjijwwcn.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2eastxcvh.html

[N01] 二分查找（有序数组）
来源：http://dali.xylfe.cn/Article/details/gt2mvmwigko.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cashguo.top/Article/details/gt2wcntychh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cqqwz.cn/Article/details/gt2ipqooszw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qgonunef.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gt2sqkqxhrv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gt2mbbgimfo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.mhx1999.top/Article/details/gt2xsxkajyw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.9152youxi.cn/Article/details/gt2npskmggq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2buvpeixw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.aibaodan.cn/Article/details/gt2qabhocet.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shuidangran.top/Article/details/gt2tyjvhhxs.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.guannengcc.top/Article/details/gt2wmpwayle.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gt2opjchbsn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cheryme.top/Article/details/gt2ckyppmcr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ehwqpu.com/Article/details/gt2yluzlasz.html

Go:   slices.Sort(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2kbqymosi.html

Ruby: arr.sort
来源：http://dali.yongpay.top/Article/details/gt2amphnhqg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ppjwa.cn/Article/details/gt2uqihrcjp.html

[N03] 快速排序（分治示例）
来源：http://dali.hysaishi.cn/Article/details/gt2cxwjrvzt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pycfn.com/Article/details/gt2sdbagkoe.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ybcxt.top/Article/details/gt2etfcmulh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigfzy.top/Article/details/gt2gmrotkaj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dashuyun.cn/Article/details/gt2ecimvatn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.guowangkeji.top/Article/details/gt2xyfplfje.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tian-w.cn/Article/details/gt2xfztigyd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guannengcc.top/Article/details/gt2hmrimssk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.pengpengdd.cyou/Article/details/gt2uuzsvhdc.html

[N04] 斐波那契数列
来源：http://dali.ydzc1.top/Article/details/gt2jotwkmxn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2phybywyt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gt2pshptjkp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rnzhxibx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gt2qqsvsbnm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.quarkkingdee.top/Article/details/gt2ouijwism.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.svipenyu.cn/Article/details/gt2jprmlslq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258.top/Article/details/gt2hqyaziab.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shangyingyoupin.top/Article/details/gt2gybtnjeg.html

[N05] 最大公约数
来源：http://dali.chenzaomai.com/Article/details/gt2bfozvrjj.html

Py:   math.gcd(a, b)
来源：http://dali.bjfxy.top/Article/details/gt2tqfwltzg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.aizwys.cn/Article/details/gt2hqjaabcs.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pycfn.com/Article/details/gt2ogtivzvi.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yonumen.top/Article/details/gt2qfasuhaw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ehwqpu.com/Article/details/gt2pabpddva.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oslodvpr.html

Ruby: a.gcd(b)
来源：http://dali.jianghu66.top/Article/details/gt2lqdqoaiz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xylfe.cn/Article/details/gt2wvwyjvvn.html

[N06] 判断回文字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2sjfgovaq.html

Py:   s == s[::-1]
来源：http://dali.tianlin.xyz/Article/details/gt2wyrhhbpl.html

PHP:  $s === strrev($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2daxifiez.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gt2uwqypahy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gt2fyfjbuiq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yanxiufei.cn/Article/details/gt2prfbtqci.html

Go:   // 双指针从两端比较
来源：http://dali.ppjwa.cn/Article/details/gt2khligkdt.html


<!-- 参考信息 -->