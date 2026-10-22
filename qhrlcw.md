代发 wailian999

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.fzhhl.top/Article/details/gtarbrykit.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.bjfxy.top/Article/details/gtaufsxavc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.daxiang520.top/Article/details/gtcsqlmwja.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.wangdashe.top/Article/details/gtlrabuixj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.guannengcc.top/Article/details/gtrrkceelb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.aibaodan.cn/Article/details/gtqlnhecmr.html

[J09] 时区处理
来源：http://dali.zycfv.cn/Article/details/gtmcgfjxfg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yuanzhike.top/Article/details/gtlvlvyvkp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cucudq.cn/Article/details/gtpscbkzep.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.mhx1999.top/Article/details/gtuumrlvsu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenjidiqi.icu/Article/details/gtyorsysya.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxinkj.top/Article/details/gtzoswvkux.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xziqi.cn/Article/details/gtdadfmmhv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.fzhhl.top/Article/details/gtyqwcmlls.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.wangshuangyany.cn/Article/details/gtgxucerqo.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmxobpguq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hfpthk.cn/Article/details/gtrvjjtmhr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj202588.top/Article/details/gtccvndbym.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.redwolf501.top/Article/details/gtxoaruauj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xziqi.cn/Article/details/gtasnfkdsl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gogol.net.cn/Article/details/gtqevijndf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhiwuduotai.top/Article/details/gtndmcbfmo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuanzhike.top/Article/details/gtwaqmkvdx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xuanzx.com/Article/details/gtdftnhmao.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gttmsmvexi.html

K. JSON 与序列化
来源：http://dali.sxryk.cn/Article/details/gtpnuphsgv.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtlkyvtghr.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhoulong.xyz/Article/details/gtellcvgtc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yanxiufei.cn/Article/details/gtpryjsefp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sxryk.cn/Article/details/gttilfiwkq.html

JS:   JSON.stringify(obj)
来源：http://dali.zhixingplan.top/Article/details/gtodzesdfy.html

TS:   JSON.stringify(obj)
来源：http://dali.sysykeji.top/Article/details/gtdjsrshqh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sufxvd.cn/Article/details/gtgljafsmc.html

Go:   json.Marshal(obj)
来源：http://dali.hywenlv.cn/Article/details/gtvjwevrru.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jyoumei.cn/Article/details/gtwkerjpwg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shuidangran.top/Article/details/gtptongfrc.html

[K02] JSON 字符串转对象
来源：http://dali.iojbl.cn/Article/details/gtzvilhayn.html

Py:   json.loads(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgskyqbp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.guannengcc.top/Article/details/gtnibaudgu.html

JS:   JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gthfqgrape.html

TS:   JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gtivfnzhjc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbxzeoim.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.dianchejie.cn/Article/details/gtbnmlmjpm.html

Ruby: JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtkhzviuqe.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.aizwys.cn/Article/details/gtgsqsnqrj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dashuyun.cn/Article/details/gtllykojxn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yuanzhike.top/Article/details/gtfbmjvnnj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yangfankeji.com/Article/details/gtvqgonpmu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gtwfotfacl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuxming.cn/Article/details/gthpimntsp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuanzhike.top/Article/details/gtlbxavsac.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.pycfn.com/Article/details/gtdpjyxurl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtbubdfymk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xuetiantiany.cn/Article/details/gtefszqasp.html

[K04] 读取 JSON 文件
来源：http://dali.fengsongda.top/Article/details/gthbkevusv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.svipenyu.cn/Article/details/gtmpvkeqiw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.guowangkeji.top/Article/details/gtqkvefvsc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yueranfly.top/Article/details/gtuczzdwwe.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gtfsgplkin.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydpjqyuq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gtbcvayowr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.redwolf501.top/Article/details/gtvjbrlddq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jianghu66.top/Article/details/gtdsulnixf.html

[K05] 深拷贝对象
来源：http://dali.wangshuangyany.cn/Article/details/gtvowwnomi.html

Py:   copy.deepcopy(obj)
来源：http://dali.aizwys.cn/Article/details/gtsvupawlp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenjidiqi.icu/Article/details/gtuhhimwnw.html

JS:   structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gtotbuxoha.html

TS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtxjzwqhkg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tanke756.top/Article/details/gtwqoaftiw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jlsjyb.cn/Article/details/gtgvzgkgwo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.pycfn.com/Article/details/gtasrmqcyw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.redwolf501.top/Article/details/gtretdhxnl.html

[K06] 解析 URL 查询串
来源：http://dali.zhiwuduotai.top/Article/details/gterlklacl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shangyingyoupin.top/Article/details/gtqzioovca.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gzhubu.top/Article/details/gtbpsvoant.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcfnrwsx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrtodgzjw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinghuilouyu.cn/Article/details/gtbpufacbr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gtlvfnqytl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gtwaskvpvd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gtfurvtmhd.html

[K07] 进制转换
来源：http://dali.yangfankeji.com/Article/details/gtuqoacczk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gtkcbuerse.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gogol.net.cn/Article/details/gtkjfwvgfu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtkzsysmfi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtzulrbati.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gthlzyrbjo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zycfv.cn/Article/details/gtswtemmrw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgzhqaueg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtkmxhmhrr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.mhx1999.top/Article/details/gtvihsflhe.html

Py:   pickle.dumps(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrzzezwxk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtlnohkfbv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gtkhqihkzf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfrzejzvs.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.iojbl.cn/Article/details/gtrexzsoea.html

Go:   encoding/gob
来源：http://dali.316326.xyz/Article/details/gtsondlptg.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmbolkxua.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gtmcmxieys.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtuymzgljp.html

L. 网络请求
来源：http://dali.smart0.xyz/Article/details/gtvbkydbnk.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtbhwhemab.html

[L01] 发送 GET 请求
来源：http://dali.tanke756.top/Article/details/gtuaiyccay.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cqqwz.cn/Article/details/gtoltctiui.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhengqikj.top/Article/details/gtavociwks.html

JS:   await fetch(url)
来源：http://dali.nwbrower.top/Article/details/gtkmhoyquh.html

TS:   await fetch(url)
来源：http://dali.yueranfly.top/Article/details/gttpixpqqn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenlongwang.top/Article/details/gtgwjsmxaz.html

Go:   resp, err := http.Get(url)
来源：http://dali.yangfankeji.com/Article/details/gttdijeuhr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj20258888.top/Article/details/gtuuteiddc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.svipenyu.cn/Article/details/gtztbwhndn.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlpvvmstv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.snrcjt.cn/Article/details/gtxvkfkmue.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ehwqpu.com/Article/details/gtxezyzvqz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jyoumei.cn/Article/details/gtlkpcbpca.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yanxiufei.cn/Article/details/gtfoxhgpgh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.quarkkingdee.top/Article/details/gtblgiqbrr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.guowangkeji.top/Article/details/gtgukokgkc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dianchejie.cn/Article/details/gtixuwahmk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sufxvd.cn/Article/details/gteznzwtgf.html

[L03] 设置自定义请求头
来源：http://dali.ivvv.top/Article/details/gtfticduyt.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.iojbl.cn/Article/details/gttjzxgzpb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.havefunace.top/Article/details/gtjjwrtfhq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangdashe.top/Article/details/gtmzyfsdac.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnqzz.top/Article/details/gtrlnayovp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhiwuduotai.top/Article/details/gtehulunlf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.0kj1m.cn/Article/details/gtfnjmlarv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.316326.xyz/Article/details/gtjrgmevzx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hfpthk.cn/Article/details/gtoekctwyh.html

[L04] 设置超时
来源：http://dali.guannengcc.top/Article/details/gtudvbvlau.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvgvzdxub.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.316326.xyz/Article/details/gtkqxcacrs.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gogol.net.cn/Article/details/gtuwowmlds.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gtnpbprjly.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.nanxinkj.top/Article/details/gtbzwulekx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jyoumei.cn/Article/details/gtpwltwzbi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yongpay.top/Article/details/gtylidtwwk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnqzz.top/Article/details/gtyyqwrzaw.html

[L05] 上传文件（multipart）
来源：http://dali.yuanzhike.top/Article/details/gtcvlrhomk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.iojbl.cn/Article/details/gtreldwfjq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.9152youxi.cn/Article/details/gtuxhgvocq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pengpengdd.cyou/Article/details/gtwlbwbyab.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shzxlz.cn/Article/details/gtheydpfnf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shzxlz.cn/Article/details/gtzbleaahw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ybcxt.top/Article/details/gtenedchpn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gtjumitvaf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtwrgxhrrf.html

[L06] 解析响应为 JSON
来源：http://dali.zycfv.cn/Article/details/gtipcbxspi.html

Py:   resp.json()
来源：http://dali.cqqwz.cn/Article/details/gtmkyjnvhq.html

PHP:  json_decode($body, true);
来源：http://dali.daria6918.cn/Article/details/gtdertwfcy.html

JS:   await resp.json()
来源：http://dali.meibo888.top/Article/details/gtdzdyjcty.html

TS:   await resp.json()
来源：http://dali.cucudq.cn/Article/details/gtctyeuyme.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zycfv.cn/Article/details/gtjfzwukum.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sufxvd.cn/Article/details/gttemcszob.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ehwqpu.com/Article/details/gtnxkutwbs.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.vqdsnc.cn/Article/details/gtxhhokysv.html

[L07] 处理 HTTP 状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuaspuvhb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zdqjudy.top/Article/details/gtwuiwmjtz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cashguo.top/Article/details/gtrpqpygjt.html

JS:   resp.ok;  resp.status
来源：http://dali.hnxiangtu.top/Article/details/gtezwttthi.html

TS:   resp.ok;  resp.status
来源：http://dali.hnqzz.top/Article/details/gtafvffpym.html

Java: resp.statusCode()
来源：http://dali.cucudq.cn/Article/details/gtnozodroe.html

Go:   resp.StatusCode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdhshill.html

Ruby: resp.code.to_i
来源：http://dali.yueranfly.top/Article/details/gtsgtddtzp.html

C#:   (int)resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gtavnhvpwi.html

[L08] 并发请求多个地址
来源：http://dali.redwolf501.top/Article/details/gthurhrbur.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nanxinkj.top/Article/details/gtpqhnbacs.html

PHP:  curl_multi_init() 系列
来源：http://dali.jianghu66.top/Article/details/gtjtwtmcbm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gtjggsmytg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gtsuxcoiqy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.iojbl.cn/Article/details/gtwldnojfr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenlongwang.top/Article/details/gtbatdzuha.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.havefunace.top/Article/details/gtdslynuxz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyfzvfprn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtlbyhurcw.html

M. 命令行 / 进程 / 环境
来源：http://dali.snrcjt.cn/Article/details/gtqjclqpjo.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtcqinjgug.html

[M01] 读取命令行参数
来源：http://dali.kuanghao11.cn/Article/details/gtvkshcbdf.html

Py:   sys.argv[1:]
来源：http://dali.zhoulong.xyz/Article/details/gtnggvjenq.html

PHP:  $argv;  $argc;
来源：http://dali.cucudq.cn/Article/details/gtpfgngfwh.html

JS:   process.argv.slice(2)
来源：http://dali.hongshengwenyu.top/Article/details/gtxkehzemq.html

TS:   process.argv.slice(2)
来源：http://dali.zhengqikj.top/Article/details/gttsfttcrc.html

Java: args 数组（main 方法参数）
来源：http://dali.feifeiyinyue.top/Article/details/gtrhdpqlhm.html

Go:   os.Args[1:]
来源：http://dali.0kj1m.cn/Article/details/gtwacdxfde.html

Ruby: ARGV
来源：http://dali.xziqi.cn/Article/details/gtwyotxzgw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.pycfn.com/Article/details/gtaopkinxu.html

[M02] 读取环境变量
来源：http://dali.316326.xyz/Article/details/gtatyqfxdx.html

Py:   os.environ.get("HOME")
来源：http://dali.ydzc1.top/Article/details/gtcnsssmcm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.havefunace.top/Article/details/gtgmrfdxvt.html

JS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gtctilrwsm.html

TS:   process.env.HOME
来源：http://dali.meibo888.top/Article/details/gtqhfbufku.html

Java: System.getenv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmksezkg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ybcxt.top/Article/details/gtogclgrkf.html

Ruby: ENV["HOME"]
来源：http://dali.jyoumei.cn/Article/details/gteavkgnpb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cucudq.cn/Article/details/gttpntxomu.html

[M03] 执行外部命令
来源：http://dali.havefunace.top/Article/details/gtdagxldam.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cucudq.cn/Article/details/gtgocewyst.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zycfv.cn/Article/details/gtpuhxguiu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.kuanghao11.cn/Article/details/gtywmwtkac.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sysykeji.top/Article/details/gtxbxqpgvb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhoulong.xyz/Article/details/gtvkztfbfo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenjidiqi.icu/Article/details/gtztgylbim.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangshuangyany.cn/Article/details/gtagleoivj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.316326.xyz/Article/details/gtxinmbazk.html

[M04] 获取当前工作目录
来源：http://dali.cqqwz.cn/Article/details/gtpxvptjfn.html

Py:   os.getcwd()
来源：http://dali.sxryk.cn/Article/details/gtqfqdqtns.html

PHP:  getcwd();
来源：http://dali.guannengcc.top/Article/details/gtfvciyait.html

JS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gttvffovch.html

TS:   process.cwd()
来源：http://dali.gotoacloud.top/Article/details/gtpnrnwers.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cqqwz.cn/Article/details/gtjzwgscdd.html

Go:   os.Getwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtngnxqooa.html

Ruby: Dir.pwd
来源：http://dali.jianghu66.top/Article/details/gtmnjwyemh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jiagoushi.top/Article/details/gthicokmox.html

[M05] 设置退出码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtktajxytg.html

Py:   sys.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqipvokc.html

PHP:  exit(1);
来源：http://dali.hammf.cn/Article/details/gtmnmrdygj.html

JS:   process.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtwxlnptqv.html

TS:   process.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtnrinyiix.html

Java: System.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtwmhgpwfu.html

Go:   os.Exit(1)
来源：http://dali.daxiang520.top/Article/details/gtstzcqalj.html

Ruby: exit 1
来源：http://dali.hywenlv.cn/Article/details/gtridmjgmd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cashguo.top/Article/details/gtqxqoctbm.html

[M06] 向标准错误输出
来源：http://dali.hywenlv.cn/Article/details/gtfdefydqn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyhxmniff.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.mhx1999.top/Article/details/gtjlyrcadh.html

JS:   console.error("err")
来源：http://dali.cdnleiting.top/Article/details/gtoktafjll.html

TS:   console.error("err")
来源：http://dali.tian-w.cn/Article/details/gtsiyzvvjl.html

Java: System.err.println("err")
来源：http://dali.dianchejie.cn/Article/details/gtvtnipuwt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yanxiufei.cn/Article/details/gtnmvvcwbc.html

Ruby: warn "err"
来源：http://dali.hongshengwenyu.top/Article/details/gtopjatgxk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cucudq.cn/Article/details/gtjhjgfnsb.html

[M07] 判断是否为主入口
来源：http://dali.shzxlz.cn/Article/details/gtqeivawyn.html

Py:   if __name__ == "__main__":
来源：http://dali.jqgufenzy.top/Article/details/gtpyaboukc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.guannengcc.top/Article/details/gtacgzddfc.html

JS:   require.main === module
来源：http://dali.guowangkeji.top/Article/details/gtjagebzsv.html

TS:   require.main === module
来源：http://dali.gogol.net.cn/Article/details/gtgrcglonq.html

Java: public static void main(String[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gtmmufliqq.html

Go:   func main()
来源：http://dali.yanxiufei.cn/Article/details/gtfsedsyip.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sxryk.cn/Article/details/gtamlnzdon.html

C#:   static void Main(string[] args)
来源：http://dali.gogol.net.cn/Article/details/gtkodauudk.html

[M08] 获取系统与运行时信息
来源：http://dali.9152youxi.cn/Article/details/gtcknxhlwc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.andypj.xyz/Article/details/gtjmujyvix.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yanxiufei.cn/Article/details/gthwslomow.html

JS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gtynhsdzef.html

TS:   process.platform;  process.version
来源：http://dali.ydzc1.top/Article/details/gtryhfgpqc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.aibaodan.cn/Article/details/gtyqdpwdsf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nanxuanxn.top/Article/details/gttrebpbnn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.haohaochexian.top/Article/details/gtkkbkcnwm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guowangkeji.top/Article/details/gtcfmlmzbp.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtbbdhoiou.html

N. 数据结构与算法
来源：http://dali.yanxiufei.cn/Article/details/gtxmjmeutw.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtyxdhjwdw.html

[N01] 二分查找（有序数组）
来源：http://dali.xziqi.cn/Article/details/gthvbpldoy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvzloyyh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nanxinkj.top/Article/details/gtjucvpxpq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yangfankeji.com/Article/details/gtvnirilqs.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjfhjnzy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtvykexyfy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtkckgwcts.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hammf.cn/Article/details/gtblnlsigw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtluheylwu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.snrcjt.cn/Article/details/gtrmmzulsu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.bjfxy.top/Article/details/gtanrfmxkt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.c1oappe.top/Article/details/gtjlienhyw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gtzpltbyul.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gtqauophnc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgjjdxlah.html

Go:   slices.Sort(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtjodrzkpy.html

Ruby: arr.sort
来源：http://dali.yanxiufei.cn/Article/details/gtbrivmxwn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hongshengwenyu.top/Article/details/gtoqhwisvr.html

[N03] 快速排序（分治示例）
来源：http://dali.cqqwz.cn/Article/details/gtgpfwrrzg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hongshengwenyu.top/Article/details/gtlyxrptog.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenzaomai.com/Article/details/gtqfzseoxm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yanxiufei.cn/Article/details/gtdilqqthb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tianlin.xyz/Article/details/gtnqxdrjld.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hammf.cn/Article/details/gtaudrfyeh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.feifeiyinyue.top/Article/details/gtqtcbitxc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuetiantiany.cn/Article/details/gtuudfzoyf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.meibo888.top/Article/details/gtrccjtrre.html

[N04] 斐波那契数列
来源：http://dali.gaohongyu789.top/Article/details/gtpoucszue.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nwbrower.top/Article/details/gtibalvcyv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenlongwang.top/Article/details/gtzkhxcaux.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gtrdbjhezb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gthopnxcmf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shuidangran.top/Article/details/gtmzmvykwx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hysaishi.cn/Article/details/gtwoqsfwbn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gotoacloud.top/Article/details/gtmtmqdghe.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gtsxsjqxhv.html

[N05] 最大公约数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvjisfsl.html

Py:   math.gcd(a, b)
来源：http://dali.ivvv.top/Article/details/gtyqeepvuu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.meibo888.top/Article/details/gtblcmyfbk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangdashe.top/Article/details/gtwhoaitap.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgfzy.top/Article/details/gtwqtzjghi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinghuilouyu.cn/Article/details/gtedvztbmt.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhongyouzk.top/Article/details/gthsplmtot.html

Ruby: a.gcd(b)
来源：http://dali.nwbrower.top/Article/details/gtqulewrns.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.mhx1999.top/Article/details/gtzaedvueo.html

[N06] 判断回文字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtewhkylyk.html

Py:   s == s[::-1]
来源：http://dali.zhoulong.xyz/Article/details/gtuifmpznz.html

PHP:  $s === strrev($s);
来源：http://dali.yangfankeji.com/Article/details/gtqpedxmjj.html


<!-- 参考信息 -->