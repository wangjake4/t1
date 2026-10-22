代发 wailian999

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenjidiqi.icu/Article/details/gt2lntjdddk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hywenlv.cn/Article/details/gt2xblzsgps.html

[J09] 时区处理
来源：http://dali.nanxinkj.top/Article/details/gt2kqzlyxph.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.smart0.xyz/Article/details/gt2tbfzqcae.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenjidiqi.icu/Article/details/gt2slckogas.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hammf.cn/Article/details/gt2rmohmqmj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuxming.cn/Article/details/gt2rbpfsknw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yvedp.cn/Article/details/gt2yxjblgsp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.daxiang520.top/Article/details/gt2zigaawsy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ewybevvu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258888.top/Article/details/gt2iqvcfnrv.html

[J10] 取今天 / 本月第一天
来源：http://dali.sufxvd.cn/Article/details/gt2rckwghrk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.smart0.xyz/Article/details/gt2mpmhicfe.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.iojbl.cn/Article/details/gt2maxtqahk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tdxpuwny.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shuidangran.top/Article/details/gt2yzrcwovk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nanxinkj.top/Article/details/gt2rvmmjyeq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xinyue.icu/Article/details/gt2mdnuuyvz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jqgufenzy.top/Article/details/gt2eopeaxtf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.mhx1999.top/Article/details/gt2mphofazj.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2fmhqqazt.html

K. JSON 与序列化
来源：http://dali.hysaishi.cn/Article/details/gt2gwmecshu.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2ltspzonj.html

[K01] 对象转 JSON 字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2ipduzltu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shzxlz.cn/Article/details/gt2prnhbwaf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.meibo888.top/Article/details/gt2eprmtnhv.html

JS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gt2xlqtsnlb.html

TS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gt2oocyryua.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.daria6918.cn/Article/details/gt2euklybzm.html

Go:   json.Marshal(obj)
来源：http://dali.cashguo.top/Article/details/gt2cugyhjiz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnqzz.top/Article/details/gt2gokibhrq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2twvffnyz.html

[K02] JSON 字符串转对象
来源：http://dali.zhiwuduotai.top/Article/details/gt2hjcjkhan.html

Py:   json.loads(s)
来源：http://dali.ivvv.top/Article/details/gt2zmqpxxih.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.fengsongda.top/Article/details/gt2mvdmxwmr.html

JS:   JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gt2jhmbvmnq.html

TS:   JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gt2hxfjadoo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.snrcjt.cn/Article/details/gt2zqvdnmrq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.iojbl.cn/Article/details/gt2kcjzclcq.html

Ruby: JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gt2tagrfsqe.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.daxiang520.top/Article/details/gt2dvjwqwai.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yanxiufei.cn/Article/details/gt2fixxutzw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gt2bjepajvz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hysaishi.cn/Article/details/gt2scaxjfgk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vtnvivle.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gt2sgrbrogl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuxming.cn/Article/details/gt2iolqcuyb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hongshengwenyu.top/Article/details/gt2vjoqxqgp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shuidangran.top/Article/details/gt2wcfdxbma.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.bjfxy.top/Article/details/gt2vdlozesy.html

[K04] 读取 JSON 文件
来源：http://dali.yvedp.cn/Article/details/gt2vejnmueg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hywenlv.cn/Article/details/gt2hmuxknfy.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangdashe.top/Article/details/gt2lfmzkodv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sxryk.cn/Article/details/gt2kscxrtac.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gt2ffufsmrz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.mhx1999.top/Article/details/gt2ihclycnq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cqqwz.cn/Article/details/gt2xidjgdmk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gt2cnuhnbph.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hgdrukri.html

[K05] 深拷贝对象
来源：http://dali.smart0.xyz/Article/details/gt2xkmbvpyb.html

Py:   copy.deepcopy(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2cexgtcpa.html

PHP:  unserialize(serialize($obj));
来源：http://dali.redwolf501.top/Article/details/gt2pblbtxnd.html

JS:   structuredClone(obj)
来源：http://dali.tian-w.cn/Article/details/gt2iqzitbzx.html

TS:   structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vuxsymvc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xuanzx.com/Article/details/gt2zewzuhmo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.bjfxy.top/Article/details/gt2tlvmnzsp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gogol.net.cn/Article/details/gt2aafeawrj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.feifeiyinyue.top/Article/details/gt2ozcifmxv.html

[K06] 解析 URL 查询串
来源：http://dali.hnxiangtu.top/Article/details/gt2tqxygzsv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.dianchejie.cn/Article/details/gt2uyxqmqmb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hnxiangtu.top/Article/details/gt2hjxemnkx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gogol.net.cn/Article/details/gt2bcfwlvec.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daria6918.cn/Article/details/gt2qilxnbeh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mfqcwjih.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gt2zqjncyty.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gt2wlhjagxa.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gt2ndunvsac.html

[K07] 进制转换
来源：http://dali.jianghu66.top/Article/details/gt2tfbcuycn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gt2vounprsx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yvedp.cn/Article/details/gt2qbcoqbvs.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gt2ohdnhpsb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2wqrsfyol.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gt2ohbzcbhd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daria6918.cn/Article/details/gt2aujfsmml.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ppjwa.cn/Article/details/gt2iapczsyi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2fekkqwhr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.andypj.xyz/Article/details/gt2jmuknclo.html

Py:   pickle.dumps(obj)
来源：http://dali.yvedp.cn/Article/details/gt2qqhmexbu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2ptzznggs.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xinyue.icu/Article/details/gt2poyicdly.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yueranfly.top/Article/details/gt2jnuhwhie.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jlsjyb.cn/Article/details/gt2lwliioqi.html

Go:   encoding/gob
来源：http://dali.jinqigufen.top/Article/details/gt2wrpeoigj.html

Ruby: Marshal.dump(obj)
来源：http://dali.yonumen.top/Article/details/gt2tkkdpubl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xinyue.icu/Article/details/gt2xqzbtpsz.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2vonwbimz.html

L. 网络请求
来源：http://dali.hysaishi.cn/Article/details/gt2jzxnowev.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2mjymxoae.html

[L01] 发送 GET 请求
来源：http://dali.sxryk.cn/Article/details/gt2kaoqsqvk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yanxiufei.cn/Article/details/gt2hwmkseep.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.0kj1m.cn/Article/details/gt2wtetdvmd.html

JS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gt2gnfwydhw.html

TS:   await fetch(url)
来源：http://dali.hfpthk.cn/Article/details/gt2bipnbbcg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.havefunace.top/Article/details/gt2dhkcjodm.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigufen.top/Article/details/gt2pvywvzem.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.havefunace.top/Article/details/gt2ddwaofnh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.daria6918.cn/Article/details/gt2tquioxkl.html

[L02] 发送 POST JSON
来源：http://dali.nwbrower.top/Article/details/gt2fisttsog.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yonumen.top/Article/details/gt2fxwwpqtl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ydzc1.top/Article/details/gt2llmzullv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cashguo.top/Article/details/gt2qcmvrvma.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dashuyun.cn/Article/details/gt2nkuqsgeb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rbngytml.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.fzhhl.top/Article/details/gt2jctnikic.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hfpthk.cn/Article/details/gt2rhvggwej.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj202588.top/Article/details/gt2buizcklb.html

[L03] 设置自定义请求头
来源：http://dali.zhixingplan.top/Article/details/gt2mbbuzncv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gotoacloud.top/Article/details/gt2ixfyyfiq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cheryme.top/Article/details/gt2jqmqggek.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xziqi.cn/Article/details/gt2tddoregi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenzaomai.com/Article/details/gt2aradkxbb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hnqzz.top/Article/details/gt2egoqyjmx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gt2ooiihzba.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.meibo888.top/Article/details/gt2rvjistkp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.birdmap.top/Article/details/gt2edpfcgyq.html

[L04] 设置超时
来源：http://dali.tanke756.top/Article/details/gt2jgebtiot.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuanzx.com/Article/details/gt2eurcjtda.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhixingplan.top/Article/details/gt2pnwjcces.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ehwqpu.com/Article/details/gt2cuuvcnaf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.kuanghao11.cn/Article/details/gt2nloypjvm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yueranfly.top/Article/details/gt2nvfbdkqv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.snrcjt.cn/Article/details/gt2ihgqotvf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kxevsstj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yangfankeji.com/Article/details/gt2yteoqauz.html

[L05] 上传文件（multipart）
来源：http://dali.yuxming.cn/Article/details/gt2ltkgynyo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.wangdashe.top/Article/details/gt2mkkbrxvq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ivvv.top/Article/details/gt2qyfbwdkq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgufenzy.top/Article/details/gt2tlvzzdet.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuetiantiany.cn/Article/details/gt2rzfpfces.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shuidangran.top/Article/details/gt2esvukvqk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jqgufenzy.top/Article/details/gt2vrgylcok.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.guannengcc.top/Article/details/gt2pnwgizoe.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2dqwyeqzk.html

[L06] 解析响应为 JSON
来源：http://dali.zhiwuduotai.top/Article/details/gt2dmwfptct.html

Py:   resp.json()
来源：http://dali.meibo888.top/Article/details/gt2ncrquhdo.html

PHP:  json_decode($body, true);
来源：http://dali.yuxming.cn/Article/details/gt2zpmcuvet.html

JS:   await resp.json()
来源：http://dali.yj202588.top/Article/details/gt2cmyfmxih.html

TS:   await resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gt2xyquqqjz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.c1oappe.top/Article/details/gt2ghqivkeu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hysaishi.cn/Article/details/gt2xythvhlg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinqigfzy.top/Article/details/gt2ctyglfjm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yongpay.top/Article/details/gt2iymspyom.html

[L07] 处理 HTTP 状态码
来源：http://dali.dashuyun.cn/Article/details/gt2yrkvhxfo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2idvwvfoy.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nwbrower.top/Article/details/gt2kfrraywd.html

JS:   resp.ok;  resp.status
来源：http://dali.snrcjt.cn/Article/details/gt2hzpwfmja.html

TS:   resp.ok;  resp.status
来源：http://dali.ppjwa.cn/Article/details/gt2qdioaofo.html

Java: resp.statusCode()
来源：http://dali.c1oappe.top/Article/details/gt2evhfwsqs.html

Go:   resp.StatusCode
来源：http://dali.yangfankeji.com/Article/details/gt2baaclyhr.html

Ruby: resp.code.to_i
来源：http://dali.mhx1999.top/Article/details/gt2ddoeiwcd.html

C#:   (int)resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gt2wcfbetwx.html

[L08] 并发请求多个地址
来源：http://dali.hongshengwenyu.top/Article/details/gt2qofeyfzh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uhgblmzj.html

PHP:  curl_multi_init() 系列
来源：http://dali.yvedp.cn/Article/details/gt2vpmunjhl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cqqwz.cn/Article/details/gt2jkeyhaod.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gt2stwkfxfj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fzhhl.top/Article/details/gt2jsvepjcq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shangyingyoupin.top/Article/details/gt2gkdhkqfu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.iojbl.cn/Article/details/gt2kkrihuux.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.vqdsnc.cn/Article/details/gt2tjlrfswf.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2ilapumum.html

M. 命令行 / 进程 / 环境
来源：http://dali.aizwys.cn/Article/details/gt2mngieqnu.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2fckwlnqh.html

[M01] 读取命令行参数
来源：http://dali.yonumen.top/Article/details/gt2knhstncf.html

Py:   sys.argv[1:]
来源：http://dali.ppjwa.cn/Article/details/gt2gyruckuv.html

PHP:  $argv;  $argc;
来源：http://dali.chenlongwang.top/Article/details/gt2arobjxit.html

JS:   process.argv.slice(2)
来源：http://dali.yvedp.cn/Article/details/gt2dzmctbox.html

TS:   process.argv.slice(2)
来源：http://dali.xylfe.cn/Article/details/gt2ymemzakq.html

Java: args 数组（main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gt2qniovzmu.html

Go:   os.Args[1:]
来源：http://dali.yueranfly.top/Article/details/gt2omifcpsn.html

Ruby: ARGV
来源：http://dali.wangshuangyany.cn/Article/details/gt2ccfnakkn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hfpthk.cn/Article/details/gt2gvaiefzi.html

[M02] 读取环境变量
来源：http://dali.dianchejie.cn/Article/details/gt2scxhymcy.html

Py:   os.environ.get("HOME")
来源：http://dali.yuanzhike.top/Article/details/gt2otlrgcst.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.feifeiyinyue.top/Article/details/gt2czuzwebd.html

JS:   process.env.HOME
来源：http://dali.hammf.cn/Article/details/gt2twzthcqj.html

TS:   process.env.HOME
来源：http://dali.jyoumei.cn/Article/details/gt2pcyzfyby.html

Java: System.getenv("HOME")
来源：http://dali.daria6918.cn/Article/details/gt2kylwowwg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xylfe.cn/Article/details/gt2fwubxtph.html

Ruby: ENV["HOME"]
来源：http://dali.cashguo.top/Article/details/gt2jvzkpmpn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gt2rqgftlkv.html

[M03] 执行外部命令
来源：http://dali.tanke756.top/Article/details/gt2johwhtkc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guowangkeji.top/Article/details/gt2bamiatam.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gzhubu.top/Article/details/gt2feklnedy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ivvv.top/Article/details/gt2wrhfxqtv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gt2fvugiplf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jianghu66.top/Article/details/gt2zbhintmy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hammf.cn/Article/details/gt2nynhrvlo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yanxiufei.cn/Article/details/gt2ihumqpjt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yongpay.top/Article/details/gt2ijdednob.html

[M04] 获取当前工作目录
来源：http://dali.dashuyun.cn/Article/details/gt2vvyuiqfk.html

Py:   os.getcwd()
来源：http://dali.yj202588.top/Article/details/gt2arksiwlk.html

PHP:  getcwd();
来源：http://dali.chenjidiqi.icu/Article/details/gt2xxcpgeur.html

JS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gt2qjxwqwif.html

TS:   process.cwd()
来源：http://dali.ivvv.top/Article/details/gt2wodxpejz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jqgfzy.top/Article/details/gt2djzhdzjt.html

Go:   os.Getwd()
来源：http://dali.zhiwuduotai.top/Article/details/gt2vwrighky.html

Ruby: Dir.pwd
来源：http://dali.chenjidiqi.icu/Article/details/gt2llcdhqul.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxuanxn.top/Article/details/gt2evxkxqdo.html

[M05] 设置退出码
来源：http://dali.yuxming.cn/Article/details/gt2marmnkdi.html

Py:   sys.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gt2hkfheefm.html

PHP:  exit(1);
来源：http://dali.jlsjyb.cn/Article/details/gt2xzlhmxft.html

JS:   process.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gt2nsrbpqux.html

TS:   process.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ezxlfdxe.html

Java: System.exit(1)
来源：http://dali.yongpay.top/Article/details/gt2gkqyvssh.html

Go:   os.Exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2oknlsrtv.html

Ruby: exit 1
来源：http://dali.xinyue.icu/Article/details/gt2cfknwcqx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.aizwys.cn/Article/details/gt2mosbecxb.html

[M06] 向标准错误输出
来源：http://dali.zdqjudy.top/Article/details/gt2ladsfany.html

Py:   print("err", file=sys.stderr)
来源：http://dali.316326.xyz/Article/details/gt2yzxeqbsi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.dashuyun.cn/Article/details/gt2hluwjnba.html

JS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gt2zuzylqwr.html

TS:   console.error("err")
来源：http://dali.hammf.cn/Article/details/gt2ncwcutlq.html

Java: System.err.println("err")
来源：http://dali.ybcxt.top/Article/details/gt2vtlmfkbb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jyoumei.cn/Article/details/gt2focndkqa.html

Ruby: warn "err"
来源：http://dali.yj202588.top/Article/details/gt2jrkfubbz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhengqikj.top/Article/details/gt2pumehiqn.html

[M07] 判断是否为主入口
来源：http://dali.yongpay.top/Article/details/gt2jnoawjjd.html

Py:   if __name__ == "__main__":
来源：http://dali.sufxvd.cn/Article/details/gt2srygravq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zdqjudy.top/Article/details/gt2uocrfddh.html

JS:   require.main === module
来源：http://dali.sufxvd.cn/Article/details/gt2wkjwhltd.html

TS:   require.main === module
来源：http://dali.xuanzx.com/Article/details/gt2yymcqzcx.html

Java: public static void main(String[] args)
来源：http://dali.jqgufenzy.top/Article/details/gt2wquicvau.html

Go:   func main()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fnghphmq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj20258888.top/Article/details/gt2oiffepno.html

C#:   static void Main(string[] args)
来源：http://dali.bjfxy.top/Article/details/gt2rjwpdxni.html

[M08] 获取系统与运行时信息
来源：http://dali.fengsongda.top/Article/details/gt2tanfiocn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cqqwz.cn/Article/details/gt2axbtoiti.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jiagoushi.top/Article/details/gt2jhrumtup.html

JS:   process.platform;  process.version
来源：http://dali.daria6918.cn/Article/details/gt2ilobvwwl.html

TS:   process.platform;  process.version
来源：http://dali.cucudq.cn/Article/details/gt2qsmmwlke.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj202588.top/Article/details/gt2hxbnpaki.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.tianlin.xyz/Article/details/gt2qvojibse.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shuidangran.top/Article/details/gt2bkprwpcx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xziqi.cn/Article/details/gt2cqdqlooj.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2ptqcoemn.html

N. 数据结构与算法
来源：http://dali.tian-w.cn/Article/details/gt2qexcozsc.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2noiaylia.html

[N01] 二分查找（有序数组）
来源：http://dali.mhx1999.top/Article/details/gt2qcxxkmpg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gt2fafsqhyf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.andypj.xyz/Article/details/gt2iinecdoq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jianghu66.top/Article/details/gt2vyiflsnl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ydzc1.top/Article/details/gt2cyuulaui.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yueranfly.top/Article/details/gt2obdecsin.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2rflnvnla.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hongshengwenyu.top/Article/details/gt2omyuncre.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gt2hnfukwba.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pycfn.com/Article/details/gt2fozeyndt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxuanxn.top/Article/details/gt2oyacgchu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bgpbsnvo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gt2vgokqikr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gt2ceczyxax.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.0kj1m.cn/Article/details/gt2ihfgizzr.html

Go:   slices.Sort(arr)
来源：http://dali.cucudq.cn/Article/details/gt2eqqjiyga.html

Ruby: arr.sort
来源：http://dali.jqgufenzy.top/Article/details/gt2mdiioesy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ehwqpu.com/Article/details/gt2kfcouvdl.html

[N03] 快速排序（分治示例）
来源：http://dali.feifeiyinyue.top/Article/details/gt2tesnfspa.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aibaodan.cn/Article/details/gt2lxgbldei.html

PHP:  // 递归实现，或用 usort
来源：http://dali.mhx1999.top/Article/details/gt2wtkxljom.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2famrhiwo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gt2tiwcnfke.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wyncnqwq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xylfe.cn/Article/details/gt2kvwetksf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.birdmap.top/Article/details/gt2zrogxcmh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.snrcjt.cn/Article/details/gt2onesrlpz.html

[N04] 斐波那契数列
来源：http://dali.sxryk.cn/Article/details/gt2ahjusorl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2bolzrcqn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuanzx.com/Article/details/gt2fgwmubzl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gt2rfivvozn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gt2vdwwijjm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gt2adwodkbi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yuxming.cn/Article/details/gt2nwjlatsu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigufen.top/Article/details/gt2wutitlpe.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gt2pssuejwv.html

[N05] 最大公约数
来源：http://dali.hywenlv.cn/Article/details/gt2lrqrebvv.html

Py:   math.gcd(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2iwqidhdz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenzaomai.com/Article/details/gt2gdubuzwi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxuanxn.top/Article/details/gt2jbpukcgu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yfdwcqrx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.wangshuangyany.cn/Article/details/gt2fubkdbai.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.meibo888.top/Article/details/gt2oeldgoic.html

Ruby: a.gcd(b)
来源：http://dali.shzxlz.cn/Article/details/gt2msmmvedq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cashguo.top/Article/details/gt2jcpyuwaa.html

[N06] 判断回文字符串
来源：http://dali.0kj1m.cn/Article/details/gt2vxxhtpba.html

Py:   s == s[::-1]
来源：http://dali.mhx1999.top/Article/details/gt2dxrndhto.html

PHP:  $s === strrev($s);
来源：http://dali.ybcxt.top/Article/details/gt2fkdxxonq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uijeulec.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gt2gbnsddrw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tianlin.xyz/Article/details/gt2cnqioodd.html

Go:   // 双指针从两端比较
来源：http://dali.jiagoushi.top/Article/details/gt2hcalxvce.html


<!-- 参考信息 -->