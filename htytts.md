代发 wailian999

[J07] 比较两个日期
来源：http://dali.tanke756.top/Article/details/gtspfyewws.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gtyedwfrlg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhixingplan.top/Article/details/gtozzxifvm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hysaishi.cn/Article/details/gtxdpzitms.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.kuanghao11.cn/Article/details/gtizpvsnuj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shuidangran.top/Article/details/gtfgdparmb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hfpthk.cn/Article/details/gtddhcmpzr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gtddohezmn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gtdhdhhhwr.html

[J08] 提取年月日与星期
来源：http://dali.zhongyouzk.top/Article/details/gtqzbqluca.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tianlin.xyz/Article/details/gtdbaelixv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yueranfly.top/Article/details/gtbkuxzjav.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzuylaaok.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.haohaochexian.top/Article/details/gtocuixnws.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhoulong.xyz/Article/details/gtdnogwnfq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hammf.cn/Article/details/gtluoqjbuh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.dianchejie.cn/Article/details/gtidedbhvh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dashuyun.cn/Article/details/gtlzvymqwi.html

[J09] 时区处理
来源：http://dali.jqgufenzy.top/Article/details/gtiicadjmj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.0kj1m.cn/Article/details/gtgcjldqmk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.c1oappe.top/Article/details/gtpnsaveqz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gtsbjulldo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hywenlv.cn/Article/details/gtxnillbzb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuanzx.com/Article/details/gtwejzqxig.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gaohongyu789.top/Article/details/gttgmyvvhh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yuxming.cn/Article/details/gtulknpjiz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.quarkkingdee.top/Article/details/gthfqnihhz.html

[J10] 取今天 / 本月第一天
来源：http://dali.sxryk.cn/Article/details/gtjljikhdi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yongpay.top/Article/details/gtzrcquqrr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.andypj.xyz/Article/details/gtcitdodzg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenlongwang.top/Article/details/gtglesfeif.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tian-w.cn/Article/details/gtkfsksbjb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zycfv.cn/Article/details/gtmoetwmnz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj202588.top/Article/details/gtmjonbaxj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.mhx1999.top/Article/details/gtsjmdsthm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenlongwang.top/Article/details/gtylfbxkkl.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtgargsgbh.html

K. JSON 与序列化
来源：http://dali.0kj1m.cn/Article/details/gtbdbskzfj.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtdaqaydzb.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtorismbyu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gtwjhevnhn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gtcmpmrpcm.html

JS:   JSON.stringify(obj)
来源：http://dali.c1oappe.top/Article/details/gtxavpckcz.html

TS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gtwefnqiok.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinqigufen.top/Article/details/gthtmxcyqg.html

Go:   json.Marshal(obj)
来源：http://dali.yueranfly.top/Article/details/gtlorgbybm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.aibaodan.cn/Article/details/gtmlcxrgsm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jqgfzy.top/Article/details/gtfgstvgsl.html

[K02] JSON 字符串转对象
来源：http://dali.shangyingyoupin.top/Article/details/gtjpzaestf.html

Py:   json.loads(s)
来源：http://dali.gaohongyu789.top/Article/details/gtqmcdvezj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ppjwa.cn/Article/details/gtqpjgnjlk.html

JS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtyimdwxll.html

TS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtspgwarpm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gotoacloud.top/Article/details/gtukfkseqq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yueranfly.top/Article/details/gtoplkukqn.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gtredfpmux.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtyaisahns.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yuxming.cn/Article/details/gtwgkmrupv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gtoziekgec.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gogol.net.cn/Article/details/gtxpzsorzc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gtiivyxcds.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gtoxyyqhnz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zycfv.cn/Article/details/gtrhjrfnju.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.mhx1999.top/Article/details/gtmkowtlfl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sxryk.cn/Article/details/gtfzfkmjcd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aibaodan.cn/Article/details/gtjejyuwfs.html

[K04] 读取 JSON 文件
来源：http://dali.guowangkeji.top/Article/details/gtofcykbkg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.birdmap.top/Article/details/gtrmgfvkvu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cqqwz.cn/Article/details/gtcyropego.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cqqwz.cn/Article/details/gtzcrmeafi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwrwgovvk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.aibaodan.cn/Article/details/gtgeyaemwr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gtcgvaeltk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gtvmbmxpuw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.iojbl.cn/Article/details/gtxwluzsrz.html

[K05] 深拷贝对象
来源：http://dali.yj20258.top/Article/details/gtlwrweimz.html

Py:   copy.deepcopy(obj)
来源：http://dali.jianghu66.top/Article/details/gtaxpminhr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xziqi.cn/Article/details/gtvtcpxaab.html

JS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gthjzqkvhz.html

TS:   structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gtkwkyhmev.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cheryme.top/Article/details/gtpzqcpzkt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.iojbl.cn/Article/details/gtlozjkxmp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.birdmap.top/Article/details/gtsvcxpkok.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.haohaochexian.top/Article/details/gtvigcksem.html

[K06] 解析 URL 查询串
来源：http://dali.zhoulong.xyz/Article/details/gtprwbhzjf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.andypj.xyz/Article/details/gtlaygvrjc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenjidiqi.icu/Article/details/gtlrcoxrdz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnqzz.top/Article/details/gtkpassqny.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258.top/Article/details/gtzidamjwz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.c1oappe.top/Article/details/gtejcjmkmf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gtdofrikjv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvqgtzvyc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gtxmevfxcq.html

[K07] 进制转换
来源：http://dali.yvedp.cn/Article/details/gtgtvkuvwr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtsjvvykee.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.mhx1999.top/Article/details/gtafcscxga.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtznvgycgc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gthzsujggc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtyibohqrf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xziqi.cn/Article/details/gtjxwnfvgz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhongyouzk.top/Article/details/gtodmsrmlx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtovnusedb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.c1oappe.top/Article/details/gttbuncucq.html

Py:   pickle.dumps(obj)
来源：http://dali.tian-w.cn/Article/details/gtdppkrrrc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.c1oappe.top/Article/details/gtaxrwhscn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangshuangyany.cn/Article/details/gtxbcaslzv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gtzlqujguc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.quarkkingdee.top/Article/details/gtmpnxacvn.html

Go:   encoding/gob
来源：http://dali.birdmap.top/Article/details/gtcihhtdlp.html

Ruby: Marshal.dump(obj)
来源：http://dali.snrcjt.cn/Article/details/gtielrwckr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ppjwa.cn/Article/details/gtjgftlzgu.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtbkgmrhbq.html

L. 网络请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjquzcvjh.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtfeelcege.html

[L01] 发送 GET 请求
来源：http://dali.gogol.net.cn/Article/details/gtbmgdkizd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shangyingyoupin.top/Article/details/gtuytukqyd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.guowangkeji.top/Article/details/gtqkkldprm.html

JS:   await fetch(url)
来源：http://dali.cqqwz.cn/Article/details/gtvvnukynb.html

TS:   await fetch(url)
来源：http://dali.jqgufenzy.top/Article/details/gtjxhkunoq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yvedp.cn/Article/details/gtvaebesce.html

Go:   resp, err := http.Get(url)
来源：http://dali.xylfe.cn/Article/details/gtzwjzvswn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlbsfbaow.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yonumen.top/Article/details/gtwswzxtcr.html

[L02] 发送 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaheowjdm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.aibaodan.cn/Article/details/gtyearvjcm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hywenlv.cn/Article/details/gtbgzgszpa.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hfpthk.cn/Article/details/gtooxjzzou.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gtsflnfjer.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258.top/Article/details/gtcmcnlcmi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sysykeji.top/Article/details/gtaguuexmy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.wangdashe.top/Article/details/gtgcvlfzwp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cucudq.cn/Article/details/gtnopaedcj.html

[L03] 设置自定义请求头
来源：http://dali.aizwys.cn/Article/details/gtikegkcme.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sufxvd.cn/Article/details/gtgckblicy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.0kj1m.cn/Article/details/gtdcoojelb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jiagoushi.top/Article/details/gtskbmsxya.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.vqdsnc.cn/Article/details/gtujsltkvk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.pycfn.com/Article/details/gtoacoexrg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sufxvd.cn/Article/details/gtnscztbmh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.haohaochexian.top/Article/details/gtgzyhyqlf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhoulong.xyz/Article/details/gtovhxwuar.html

[L04] 设置超时
来源：http://dali.feifeiyinyue.top/Article/details/gtfdulhusa.html

Py:   requests.get(url, timeout=5)
来源：http://dali.fengsongda.top/Article/details/gtuoubtjjx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sufxvd.cn/Article/details/gtapowmzko.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jyoumei.cn/Article/details/gtsfukkdsy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xziqi.cn/Article/details/gtcirttflt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwimwjghc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jqgfzy.top/Article/details/gtrvcmjnvg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jiagoushi.top/Article/details/gtfufoxrpw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.9152youxi.cn/Article/details/gtafwcfawk.html

[L05] 上传文件（multipart）
来源：http://dali.bjfxy.top/Article/details/gtfrhvzeks.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.vqdsnc.cn/Article/details/gtqzsxnuvc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.aibaodan.cn/Article/details/gtvknsjgmj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gtqdmatzfo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gotoacloud.top/Article/details/gtxjbksvdw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.pengpengdd.cyou/Article/details/gtnkdfkdwy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yangfankeji.com/Article/details/gtlqvflxrj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.andypj.xyz/Article/details/gtpwhawweq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yuxming.cn/Article/details/gtxclwshai.html

[L06] 解析响应为 JSON
来源：http://dali.xuetiantiany.cn/Article/details/gtlhlqmrlm.html

Py:   resp.json()
来源：http://dali.daxiang520.top/Article/details/gtodehvxai.html

PHP:  json_decode($body, true);
来源：http://dali.sxryk.cn/Article/details/gtjphyxhjg.html

JS:   await resp.json()
来源：http://dali.ppjwa.cn/Article/details/gtxnpivsjd.html

TS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gtbqfkjtwz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gtnbzkgktv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.feifeiyinyue.top/Article/details/gttcxydhsc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hongshengwenyu.top/Article/details/gtpposqpud.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangshuangyany.cn/Article/details/gtwfihzfbp.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gtpvxcswnr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.wangdashe.top/Article/details/gtnxiijwks.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.mhx1999.top/Article/details/gtvifxpxwm.html

JS:   resp.ok;  resp.status
来源：http://dali.pycfn.com/Article/details/gtysrmfwkg.html

TS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gtwzwbjhmp.html

Java: resp.statusCode()
来源：http://dali.jyoumei.cn/Article/details/gtctclztmh.html

Go:   resp.StatusCode
来源：http://dali.svipenyu.cn/Article/details/gtutiucdmh.html

Ruby: resp.code.to_i
来源：http://dali.snrcjt.cn/Article/details/gtteqraguh.html

C#:   (int)resp.StatusCode
来源：http://dali.aibaodan.cn/Article/details/gtjnkxqruz.html

[L08] 并发请求多个地址
来源：http://dali.jianghu66.top/Article/details/gttrskbfve.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.316326.xyz/Article/details/gtjsrwebji.html

PHP:  curl_multi_init() 系列
来源：http://dali.hnqzz.top/Article/details/gtiopcvqzm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gtxigcuwry.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtzlkxoolg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.redwolf501.top/Article/details/gtvtkxnwbt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.feifeiyinyue.top/Article/details/gtinjuipnv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ehwqpu.com/Article/details/gtwfjyadht.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gaohongyu789.top/Article/details/gtbkjpiyem.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtckuitect.html

M. 命令行 / 进程 / 环境
来源：http://dali.ydzc1.top/Article/details/gtnfnymmkp.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtsqiovtlb.html

[M01] 读取命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfztwilj.html

Py:   sys.argv[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgkaumygw.html

PHP:  $argv;  $argc;
来源：http://dali.redwolf501.top/Article/details/gtucqzxsrf.html

JS:   process.argv.slice(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcscwdsnc.html

TS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gtrhxqgunt.html

Java: args 数组（main 方法参数）
来源：http://dali.sufxvd.cn/Article/details/gtpqpqdnzq.html

Go:   os.Args[1:]
来源：http://dali.ppjwa.cn/Article/details/gtmtlshwuy.html

Ruby: ARGV
来源：http://dali.gaohongyu789.top/Article/details/gtmeqtkdmy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gttjadptox.html

[M02] 读取环境变量
来源：http://dali.pycfn.com/Article/details/gtlvjhqucp.html

Py:   os.environ.get("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtdqrkcocn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jianghu66.top/Article/details/gtnspazaqw.html

JS:   process.env.HOME
来源：http://dali.gotoacloud.top/Article/details/gtyeijbgoc.html

TS:   process.env.HOME
来源：http://dali.ivvv.top/Article/details/gtfelwtknn.html

Java: System.getenv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtketwstys.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtcyqexavr.html

Ruby: ENV["HOME"]
来源：http://dali.cqqwz.cn/Article/details/gtqintwudf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gtgwigidtd.html

[M03] 执行外部命令
来源：http://dali.pengpengdd.cyou/Article/details/gttmrzpdtv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sweek.top/Article/details/gtwfgamolk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gzhubu.top/Article/details/gtcyywjnwx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.havefunace.top/Article/details/gtbadpxcwx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gtawviqdwf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.316326.xyz/Article/details/gtaoydikyi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ydzc1.top/Article/details/gtbumjenbu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenjidiqi.icu/Article/details/gtpjvlaczv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daria6918.cn/Article/details/gtpwpzxmio.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gtceykdpgz.html

Py:   os.getcwd()
来源：http://dali.mhx1999.top/Article/details/gtzpmpcrxj.html

PHP:  getcwd();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjegutde.html

JS:   process.cwd()
来源：http://dali.zhoulong.xyz/Article/details/gtjxccrqge.html

TS:   process.cwd()
来源：http://dali.aizwys.cn/Article/details/gtmhmsjtfe.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xziqi.cn/Article/details/gtsrhfrqbv.html

Go:   os.Getwd()
来源：http://dali.chenzaomai.com/Article/details/gttcdztsln.html

Ruby: Dir.pwd
来源：http://dali.haohaochexian.top/Article/details/gtolfllext.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.9152youxi.cn/Article/details/gtzjchwppe.html

[M05] 设置退出码
来源：http://dali.shangyingyoupin.top/Article/details/gtuxjknycv.html

Py:   sys.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtukrrwkhz.html

PHP:  exit(1);
来源：http://dali.yuanzhike.top/Article/details/gtslbdguzt.html

JS:   process.exit(1)
来源：http://dali.xuanzx.com/Article/details/gtmlplnpbk.html

TS:   process.exit(1)
来源：http://dali.daxiang520.top/Article/details/gtduaeyjzx.html

Java: System.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtuacvlfcw.html

Go:   os.Exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtolyieuzk.html

Ruby: exit 1
来源：http://dali.ybcxt.top/Article/details/gtzjokyicz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.mhx1999.top/Article/details/gtxcwibsoj.html

[M06] 向标准错误输出
来源：http://dali.xinyue.icu/Article/details/gtdehzpyrx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.316326.xyz/Article/details/gtlfmfdapt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yueranfly.top/Article/details/gtkogekdra.html

JS:   console.error("err")
来源：http://dali.ydzc1.top/Article/details/gtajxxlmmz.html

TS:   console.error("err")
来源：http://dali.hammf.cn/Article/details/gtampfnayk.html

Java: System.err.println("err")
来源：http://dali.yangfankeji.com/Article/details/gtstbwywsw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hfpthk.cn/Article/details/gtcsdxbihi.html

Ruby: warn "err"
来源：http://dali.jqgufenzy.top/Article/details/gteixfqduu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jlsjyb.cn/Article/details/gtkcertgva.html

[M07] 判断是否为主入口
来源：http://dali.gaohongyu789.top/Article/details/gtnbotgdaw.html

Py:   if __name__ == "__main__":
来源：http://dali.ywan-chungtsiang.top/Article/details/gtekwonicg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.svipenyu.cn/Article/details/gtbfnlxkss.html

JS:   require.main === module
来源：http://dali.daria6918.cn/Article/details/gtacpzcazj.html

TS:   require.main === module
来源：http://dali.aizwys.cn/Article/details/gtvarrtffh.html

Java: public static void main(String[] args)
来源：http://dali.chenzaomai.com/Article/details/gtkemewdfp.html

Go:   func main()
来源：http://dali.shuidangran.top/Article/details/gtrykgddsi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.andypj.xyz/Article/details/gtitoxkmit.html

C#:   static void Main(string[] args)
来源：http://dali.0kj1m.cn/Article/details/gtibjrufky.html

[M08] 获取系统与运行时信息
来源：http://dali.aibaodan.cn/Article/details/gtafpmouoq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenlongwang.top/Article/details/gtigidddos.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tanke756.top/Article/details/gthykekonb.html

JS:   process.platform;  process.version
来源：http://dali.zhengqikj.top/Article/details/gtsqlxwvup.html

TS:   process.platform;  process.version
来源：http://dali.ppjwa.cn/Article/details/gtsbbsitnt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.wangshuangyany.cn/Article/details/gtbhjkxqzi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aizwys.cn/Article/details/gtuofdghdw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xylfe.cn/Article/details/gtksjbjulc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhongyouzk.top/Article/details/gtcrkfpkfi.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtsqacrsbe.html

N. 数据结构与算法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlbbzpoob.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtvdgbkqgd.html

[N01] 二分查找（有序数组）
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdusasjt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtaozgfjuq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yongpay.top/Article/details/gtqswjxchr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gtcozcfbjj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.snrcjt.cn/Article/details/gtougwxxkk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtqczkkelp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtthtvuibd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.daxiang520.top/Article/details/gtdmujtvkf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtolnrxtpx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nwbrower.top/Article/details/gteirprnsq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnxiangtu.top/Article/details/gtoncvrgej.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hysaishi.cn/Article/details/gtuatbjiww.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gtdbqcypnh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhongyouzk.top/Article/details/gtrwjwjfql.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.pengpengdd.cyou/Article/details/gtdjlpofay.html

Go:   slices.Sort(arr)
来源：http://dali.cheryme.top/Article/details/gtykkxzrys.html

Ruby: arr.sort
来源：http://dali.kuanghao11.cn/Article/details/gtxywvvqzq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gtvpaomhez.html

[N03] 快速排序（分治示例）
来源：http://dali.andypj.xyz/Article/details/gtllmldxgb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhiwuduotai.top/Article/details/gtpiloqhan.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nwbrower.top/Article/details/gtluoufdqz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj202588.top/Article/details/gtrithicyf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gtssvtqohn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nanxuanxn.top/Article/details/gtvktbtcgy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xinyue.icu/Article/details/gttknzagrm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.iojbl.cn/Article/details/gtbsulgsxd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.daria6918.cn/Article/details/gtiugaksgl.html

[N04] 斐波那契数列
来源：http://dali.yuxming.cn/Article/details/gtlzqzebvg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gtcjxapqoz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yanxiufei.cn/Article/details/gtrocskypw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gtxzkludgz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gtuenektaa.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenlongwang.top/Article/details/gtxmkxyaut.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.kuanghao11.cn/Article/details/gtjociwpyp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtfcvvtbtj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gtpnqsjwvm.html


<!-- 参考信息 -->