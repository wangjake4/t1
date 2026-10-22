代发 wailian999

C#:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hexqkmxg.html

[J08] 提取年月日与星期
来源：http://dali.hnxiangtu.top/Article/details/gt2nmnkdavs.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fexqkvyc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hywenlv.cn/Article/details/gt2rfllupak.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hammf.cn/Article/details/gt2zqexkrox.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fengsongda.top/Article/details/gt2ejkeizuf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnxiangtu.top/Article/details/gt2bsifpmwe.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.316326.xyz/Article/details/gt2mtspcyiw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cucudq.cn/Article/details/gt2pybceupp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ylsvvjxi.html

[J09] 时区处理
来源：http://dali.birdmap.top/Article/details/gt2lcdsrmng.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.svipenyu.cn/Article/details/gt2xwdltvbu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.birdmap.top/Article/details/gt2ignishaa.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhongyouzk.top/Article/details/gt2xjnrnzno.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gt2mvstgnoi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinqigufen.top/Article/details/gt2kjidslsq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tian-w.cn/Article/details/gt2bfbyhyfz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kxedtgiv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.dashuyun.cn/Article/details/gt2mqgokiyv.html

[J10] 取今天 / 本月第一天
来源：http://dali.hfpthk.cn/Article/details/gt2dqxdgafs.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.daria6918.cn/Article/details/gt2hozmgdjz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guowangkeji.top/Article/details/gt2xtdnavdm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj20258.top/Article/details/gt2uihoajgl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2pczcewif.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinqigufen.top/Article/details/gt2ykexoulx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.wangdashe.top/Article/details/gt2gzocdeud.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.feifeiyinyue.top/Article/details/gt2soaxohtd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2sdthigrs.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2jgclpjqr.html

K. JSON 与序列化
来源：http://dali.gaohongyu789.top/Article/details/gt2pbxjirns.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2xwtheefd.html

[K01] 对象转 JSON 字符串
来源：http://dali.zdqjudy.top/Article/details/gt2edhtyofb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.dashuyun.cn/Article/details/gt2kddwcsas.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gt2iudeybsp.html

JS:   JSON.stringify(obj)
来源：http://dali.meibo888.top/Article/details/gt2xwhqryjq.html

TS:   JSON.stringify(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2uwaebcwq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jlsjyb.cn/Article/details/gt2evhojwem.html

Go:   json.Marshal(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hlhqbrmt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.birdmap.top/Article/details/gt2ddzbgccv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jianghu66.top/Article/details/gt2gvdzzgev.html

[K02] JSON 字符串转对象
来源：http://dali.yj20258888.top/Article/details/gt2ojryzymp.html

Py:   json.loads(s)
来源：http://dali.yonumen.top/Article/details/gt2znxagwhw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hongshengwenyu.top/Article/details/gt2lotjkybu.html

JS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kgnsndjw.html

TS:   JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gt2fcpfdepx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sufxvd.cn/Article/details/gt2ipcvlpes.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.daxiang520.top/Article/details/gt2rnvmwnzq.html

Ruby: JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wupedzwn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2ibdnurok.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jianghu66.top/Article/details/gt2pzpnhwcs.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jlsjyb.cn/Article/details/gt2jpjddynr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gt2siypboaj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2ngywfspd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yonumen.top/Article/details/gt2allhqyvj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uatxvgqh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gogol.net.cn/Article/details/gt2klgwtbyi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hammf.cn/Article/details/gt2sxaqqdsu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.daxiang520.top/Article/details/gt2oexkhgte.html

[K04] 读取 JSON 文件
来源：http://dali.ivvv.top/Article/details/gt2qovbqzjz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xinyue.icu/Article/details/gt2lnfmdbtb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xinyue.icu/Article/details/gt2gpvcyejb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yvedp.cn/Article/details/gt2lftxqfrf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenlongwang.top/Article/details/gt2ijyqixyu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nwbrower.top/Article/details/gt2yuugpolx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.mhx1999.top/Article/details/gt2orheipkh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gt2rksdtthn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.svipenyu.cn/Article/details/gt2tafehuxb.html

[K05] 深拷贝对象
来源：http://dali.ppjwa.cn/Article/details/gt2kkbfdfsh.html

Py:   copy.deepcopy(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vsugmjvw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj20258.top/Article/details/gt2tcmosifx.html

JS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2xbkxtbsc.html

TS:   structuredClone(obj)
来源：http://dali.yongpay.top/Article/details/gt2qfrrsdrw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgvbhtr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ppjwa.cn/Article/details/gt2quhjbccs.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnqzz.top/Article/details/gt2gdhnmwoj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.dashuyun.cn/Article/details/gt2yiujregw.html

[K06] 解析 URL 查询串
来源：http://dali.ydzc1.top/Article/details/gt2ngetdque.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shangyingyoupin.top/Article/details/gt2bvxopwyi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yonumen.top/Article/details/gt2blpylojp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.0kj1m.cn/Article/details/gt2wgzkkize.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.birdmap.top/Article/details/gt2nomrfkdq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangshuangyany.cn/Article/details/gt2ahtsgzda.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gt2amsyjzkk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.dashuyun.cn/Article/details/gt2szynwilz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gt2wtjjdtla.html

[K07] 进制转换
来源：http://dali.zycfv.cn/Article/details/gt2lbsklsbd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ioayjkgx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zdqjudy.top/Article/details/gt2vutzkjls.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gt2zhmsojej.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gt2ryoqiocm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gt2sakoktjn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cashguo.top/Article/details/gt2fzrbquck.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2itcczcpm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gt2uztdnvff.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fzhhl.top/Article/details/gt2ksgtenvx.html

Py:   pickle.dumps(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2cbuaqzfd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuanzx.com/Article/details/gt2tnxpofaa.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2bhadjpag.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gt2vjjrlbts.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yangfankeji.com/Article/details/gt2nnufoiat.html

Go:   encoding/gob
来源：http://dali.redwolf501.top/Article/details/gt2fkezqqwy.html

Ruby: Marshal.dump(obj)
来源：http://dali.jianghu66.top/Article/details/gt2nutlmbqf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhongyouzk.top/Article/details/gt2wbnaxntd.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2oobarkpv.html

L. 网络请求
来源：http://dali.cheryme.top/Article/details/gt2xalwkgap.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2fjuyrled.html

[L01] 发送 GET 请求
来源：http://dali.birdmap.top/Article/details/gt2xcaghtft.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj20258.top/Article/details/gt2bfycuccg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yueranfly.top/Article/details/gt2yfiwizue.html

JS:   await fetch(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oaxdvuet.html

TS:   await fetch(url)
来源：http://dali.zhoulong.xyz/Article/details/gt2rexnqxss.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.mhx1999.top/Article/details/gt2hwpfjapr.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhengqikj.top/Article/details/gt2yvejuncj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tianlin.xyz/Article/details/gt2gvcujhyv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhoulong.xyz/Article/details/gt2yhvnfaxj.html

[L02] 发送 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gt2timeixve.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yuxming.cn/Article/details/gt2yqcwudut.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ehwqpu.com/Article/details/gt2cvdpbdvy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhiwuduotai.top/Article/details/gt2hdrxdeap.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gt2egdefvrw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nuitgygd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.guowangkeji.top/Article/details/gt2kepzzpcn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.smart0.xyz/Article/details/gt2jlgdnxrk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinqigfzy.top/Article/details/gt2xdacqehd.html

[L03] 设置自定义请求头
来源：http://dali.zhongyouzk.top/Article/details/gt2uinilaoh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hysaishi.cn/Article/details/gt2dilbxmkq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yanxiufei.cn/Article/details/gt2jqlglmbs.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gt2bpphkpxu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hysaishi.cn/Article/details/gt2oayoyjuv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qkolxwir.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kuovmqac.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jianghu66.top/Article/details/gt2gppjqdmt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yvedp.cn/Article/details/gt2fazvrkro.html

[L04] 设置超时
来源：http://dali.cdnleiting.top/Article/details/gt2movimrwi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xinyue.icu/Article/details/gt2rzutymbk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ediksekv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gt2ulwdiajz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yvedp.cn/Article/details/gt2ekueuuhm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuxming.cn/Article/details/gt2nzgftpms.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gzhubu.top/Article/details/gt2dcukarkq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tian-w.cn/Article/details/gt2jvaijeee.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yueranfly.top/Article/details/gt2zppuybie.html

[L05] 上传文件（multipart）
来源：http://dali.sysykeji.top/Article/details/gt2zdilhsrw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cqqwz.cn/Article/details/gt2gphriukr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nelwjalv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.dianchejie.cn/Article/details/gt2ozuhmqem.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.aibaodan.cn/Article/details/gt2pqikagfn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nanxinkj.top/Article/details/gt2gunqexvq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tianlin.xyz/Article/details/gt2yofmquov.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.kuanghao11.cn/Article/details/gt2afxpvqqq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.meibo888.top/Article/details/gt2vlqlgbrk.html

[L06] 解析响应为 JSON
来源：http://dali.dashuyun.cn/Article/details/gt2niuvnbjd.html

Py:   resp.json()
来源：http://dali.snrcjt.cn/Article/details/gt2lrmttmeo.html

PHP:  json_decode($body, true);
来源：http://dali.andypj.xyz/Article/details/gt2pfytworf.html

JS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gt2oxzvufnm.html

TS:   await resp.json()
来源：http://dali.birdmap.top/Article/details/gt2ngmzbxya.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.svipenyu.cn/Article/details/gt2ptyrsvkz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.quarkkingdee.top/Article/details/gt2mzxmztjb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hhzhilqg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sweek.top/Article/details/gt2ilxmlsnm.html

[L07] 处理 HTTP 状态码
来源：http://dali.yongpay.top/Article/details/gt2ihqqjwko.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.9152youxi.cn/Article/details/gt2wipjtwfg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tanke756.top/Article/details/gt2ppbfqxoi.html

JS:   resp.ok;  resp.status
来源：http://dali.sweek.top/Article/details/gt2rrzpourj.html

TS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gt2gxqjazst.html

Java: resp.statusCode()
来源：http://dali.shzxlz.cn/Article/details/gt2kizucbau.html

Go:   resp.StatusCode
来源：http://dali.hnxiangtu.top/Article/details/gt2tcxpikzv.html

Ruby: resp.code.to_i
来源：http://dali.cdnleiting.top/Article/details/gt2qmndwvrh.html

C#:   (int)resp.StatusCode
来源：http://dali.jlsjyb.cn/Article/details/gt2uhdmvapm.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dkfmapuz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shuidangran.top/Article/details/gt2htfckfqx.html

PHP:  curl_multi_init() 系列
来源：http://dali.yongpay.top/Article/details/gt2evwfcngs.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nwbrower.top/Article/details/gt2zkklddfh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gt2tpgteoru.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shanyushiyangtech.top/Article/details/gt2edapsuva.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cqqwz.cn/Article/details/gt2pupalsej.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.guannengcc.top/Article/details/gt2uhbtsauh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnxiangtu.top/Article/details/gt2ycehlsso.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2jykxknkd.html

M. 命令行 / 进程 / 环境
来源：http://dali.daria6918.cn/Article/details/gt2rkkikzpq.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2qbyyyaty.html

[M01] 读取命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fbjepwbl.html

Py:   sys.argv[1:]
来源：http://dali.wangdashe.top/Article/details/gt2xxblhmqt.html

PHP:  $argv;  $argc;
来源：http://dali.sweek.top/Article/details/gt2jgytjtji.html

JS:   process.argv.slice(2)
来源：http://dali.iojbl.cn/Article/details/gt2wafycruc.html

TS:   process.argv.slice(2)
来源：http://dali.cheryme.top/Article/details/gt2roikyacm.html

Java: args 数组（main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gt2kqwsoyvs.html

Go:   os.Args[1:]
来源：http://dali.meibo888.top/Article/details/gt2gptefqqf.html

Ruby: ARGV
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ukcyhtah.html

C#:   args 数组（Main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gt2bzycdijv.html

[M02] 读取环境变量
来源：http://dali.zycfv.cn/Article/details/gt2phhconup.html

Py:   os.environ.get("HOME")
来源：http://dali.ppjwa.cn/Article/details/gt2rwxhvwvy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gt2hoxobrun.html

JS:   process.env.HOME
来源：http://dali.ydzc1.top/Article/details/gt2ritefuhd.html

TS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gt2ubkhwfxb.html

Java: System.getenv("HOME")
来源：http://dali.pycfn.com/Article/details/gt2awwvzdrr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yongpay.top/Article/details/gt2zhdzajth.html

Ruby: ENV["HOME"]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cefvffgf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xziqi.cn/Article/details/gt2ktwqdvfu.html

[M03] 执行外部命令
来源：http://dali.iojbl.cn/Article/details/gt2wvgcogbg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zdqjudy.top/Article/details/gt2qfjaojxk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.andypj.xyz/Article/details/gt2qycvxpij.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gt2ygbltuvf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xinyue.icu/Article/details/gt2lvlrphmt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dashuyun.cn/Article/details/gt2nhjtuqyn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj202588.top/Article/details/gt2thyrhqen.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cheryme.top/Article/details/gt2mdnydhnx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qyfiykdd.html

[M04] 获取当前工作目录
来源：http://dali.svipenyu.cn/Article/details/gt2qfzkbcpw.html

Py:   os.getcwd()
来源：http://dali.ydzc1.top/Article/details/gt2ebtylpdr.html

PHP:  getcwd();
来源：http://dali.xuetiantiany.cn/Article/details/gt2qbnekrvg.html

JS:   process.cwd()
来源：http://dali.fzhhl.top/Article/details/gt2hltwmucc.html

TS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gt2dhwbkabt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tian-w.cn/Article/details/gt2oponuaiy.html

Go:   os.Getwd()
来源：http://dali.zycfv.cn/Article/details/gt2jncdtutm.html

Ruby: Dir.pwd
来源：http://dali.jiagoushi.top/Article/details/gt2bksevewg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinqigfzy.top/Article/details/gt2fggxrfyj.html

[M05] 设置退出码
来源：http://dali.feifeiyinyue.top/Article/details/gt2cffelvgz.html

Py:   sys.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gt2cribhhhu.html

PHP:  exit(1);
来源：http://dali.andypj.xyz/Article/details/gt2lyscpyby.html

JS:   process.exit(1)
来源：http://dali.sysykeji.top/Article/details/gt2jbxanybb.html

TS:   process.exit(1)
来源：http://dali.ydzc1.top/Article/details/gt2wadygwjc.html

Java: System.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gt2jmppohfz.html

Go:   os.Exit(1)
来源：http://dali.xuanzx.com/Article/details/gt2lcjpvchd.html

Ruby: exit 1
来源：http://dali.hnxiangtu.top/Article/details/gt2mekiiqjp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jianghu66.top/Article/details/gt2wyydvdhl.html

[M06] 向标准错误输出
来源：http://dali.yuanzhike.top/Article/details/gt2aprqpcxh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lkhoonif.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangdashe.top/Article/details/gt2uxtmayvq.html

JS:   console.error("err")
来源：http://dali.meibo888.top/Article/details/gt2thhxuwlf.html

TS:   console.error("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tkoslhjv.html

Java: System.err.println("err")
来源：http://dali.tianlin.xyz/Article/details/gt2mwgotnla.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj20258888.top/Article/details/gt2xhpedetq.html

Ruby: warn "err"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mwfnonnu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ahryujva.html

[M07] 判断是否为主入口
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uivlshoo.html

Py:   if __name__ == "__main__":
来源：http://dali.quarkkingdee.top/Article/details/gt2fvmojrub.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shangyingyoupin.top/Article/details/gt2sfucfuqu.html

JS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gt2amrdlmnt.html

TS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gt2ktvawksh.html

Java: public static void main(String[] args)
来源：http://dali.yvedp.cn/Article/details/gt2zneipjxo.html

Go:   func main()
来源：http://dali.svipenyu.cn/Article/details/gt2enpyzwlc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.c1oappe.top/Article/details/gt2mhldbdmv.html

C#:   static void Main(string[] args)
来源：http://dali.andypj.xyz/Article/details/gt2tdnrcrvf.html

[M08] 获取系统与运行时信息
来源：http://dali.xuetiantiany.cn/Article/details/gt2guswnvkb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.c1oappe.top/Article/details/gt2yuiblzwd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yvedp.cn/Article/details/gt2dsifubzy.html

JS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gt2zputjviv.html

TS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gt2ryieccua.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sysykeji.top/Article/details/gt2imqxnfvi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hftmczfd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangshuangyany.cn/Article/details/gt2yfxnnocl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hfpthk.cn/Article/details/gt2fdfstrta.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2nxnapyhy.html

N. 数据结构与算法
来源：http://dali.cashguo.top/Article/details/gt2tuhhcrjn.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2stsydbae.html

[N01] 二分查找（有序数组）
来源：http://dali.gzhubu.top/Article/details/gt2zdrnmazn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xylfe.cn/Article/details/gt2pmidynfo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cucudq.cn/Article/details/gt2fjdbdngt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.iojbl.cn/Article/details/gt2ihndbdml.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xinyue.icu/Article/details/gt2dubbpnfh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rqihmlts.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2mpndbxxr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gotoacloud.top/Article/details/gt2htblginl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mtfbedan.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenzaomai.com/Article/details/gt2sxyuvdes.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nwbrower.top/Article/details/gt2ygbwwevq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258.top/Article/details/gt2krfvbftg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pycfn.com/Article/details/gt2xblgxpda.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gt2amvfcxvj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fbckagkx.html

Go:   slices.Sort(arr)
来源：http://dali.yj20258.top/Article/details/gt2nopljidq.html

Ruby: arr.sort
来源：http://dali.zhiwuduotai.top/Article/details/gt2faopzczf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nanxuanxn.top/Article/details/gt2bninpkjz.html

[N03] 快速排序（分治示例）
来源：http://dali.jlsjyb.cn/Article/details/gt2adkrfknb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aizwys.cn/Article/details/gt2arnguieg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cdnleiting.top/Article/details/gt2tylsdktb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yangfankeji.com/Article/details/gt2zweqquff.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhoulong.xyz/Article/details/gt2szgtoaxw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.quarkkingdee.top/Article/details/gt2vitlykrv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fchazrgs.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuanzx.com/Article/details/gt2ehjnwqju.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangshuangyany.cn/Article/details/gt2gqxcatit.html

[N04] 斐波那契数列
来源：http://dali.316326.xyz/Article/details/gt2kkbzlldo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yuxming.cn/Article/details/gt2etcaelqw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cdnleiting.top/Article/details/gt2uuskdrbz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gt2yoczdzhk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gt2djsvkdsa.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hammf.cn/Article/details/gt2rbydefcv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yuxming.cn/Article/details/gt2gyzwvwwu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zycfv.cn/Article/details/gt2gqubbngl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gt2jbmlvniq.html

[N05] 最大公约数
来源：http://dali.shzxlz.cn/Article/details/gt2gjbdeukg.html

Py:   math.gcd(a, b)
来源：http://dali.9152youxi.cn/Article/details/gt2ffgujjnh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cdnleiting.top/Article/details/gt2aqoesvwe.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxuanxn.top/Article/details/gt2wwalcwyl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gt2gjqempgz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nwbrower.top/Article/details/gt2lpngwncg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yueranfly.top/Article/details/gt2ssrayetn.html

Ruby: a.gcd(b)
来源：http://dali.tianlin.xyz/Article/details/gt2nlrpvdgr.html


<!-- 参考信息 -->