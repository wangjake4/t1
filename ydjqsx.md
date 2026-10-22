代发 wailian999

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pycfn.com/Article/details/gt2ccvyztio.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gt2wgihbczq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hysaishi.cn/Article/details/gt2ppazkwve.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.birdmap.top/Article/details/gt2ecaxbbfm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jlsjyb.cn/Article/details/gt2uvfioaii.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dianchejie.cn/Article/details/gt2yropnejt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jianghu66.top/Article/details/gt2dgodfqqg.html

[J10] 取今天 / 本月第一天
来源：http://dali.smart0.xyz/Article/details/gt2dponqdhc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cqqwz.cn/Article/details/gt2rfptfhjn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj20258888.top/Article/details/gt2qawrdpfx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cheryme.top/Article/details/gt2avnsnpho.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkskjfnl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.haohaochexian.top/Article/details/gt2axspgdse.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sweek.top/Article/details/gt2lnntjmwg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jqgfzy.top/Article/details/gt2iljqospy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zdqjudy.top/Article/details/gt2exeellam.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jtzccges.html

K. JSON 与序列化
来源：http://dali.haohaochexian.top/Article/details/gt2sarclsnd.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2jxbbeswl.html

[K01] 对象转 JSON 字符串
来源：http://dali.jianghu66.top/Article/details/gt2xohodthd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gt2gctmexuf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258.top/Article/details/gt2zcsswwcu.html

JS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2qlsikypt.html

TS:   JSON.stringify(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2yvhjfewu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xlvnrbza.html

Go:   json.Marshal(obj)
来源：http://dali.jianghu66.top/Article/details/gt2nlpkmohg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenlongwang.top/Article/details/gt2yzpbhxba.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2jltegdbo.html

[K02] JSON 字符串转对象
来源：http://dali.yj20258.top/Article/details/gt2lmrmfcph.html

Py:   json.loads(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kovlmqji.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenjidiqi.icu/Article/details/gt2oadegndh.html

JS:   JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gt2riaqblfh.html

TS:   JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gt2nyhginvp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ppjwa.cn/Article/details/gt2teogwybj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cashguo.top/Article/details/gt2hpzhunfy.html

Ruby: JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gt2ohbwjvos.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ptyfgzun.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhoulong.xyz/Article/details/gt2foiehpfk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yvedp.cn/Article/details/gt2tzhzzjvg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.c1oappe.top/Article/details/gt2zvzottlp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dbucqask.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.daria6918.cn/Article/details/gt2yrsloqst.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.meibo888.top/Article/details/gt2xzfnaqst.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ydzc1.top/Article/details/gt2ickkpuig.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ydzc1.top/Article/details/gt2fcaoaddq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nwbrower.top/Article/details/gt2nzpozgfr.html

[K04] 读取 JSON 文件
来源：http://dali.xziqi.cn/Article/details/gt2qqdpugrq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigfzy.top/Article/details/gt2qdexguel.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shangyingyoupin.top/Article/details/gt2fiomrnct.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gt2nrpywupq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.0kj1m.cn/Article/details/gt2memecrst.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.birdmap.top/Article/details/gt2wqhouowy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shuidangran.top/Article/details/gt2pbnithae.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gt2qzdifumj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gzhubu.top/Article/details/gt2tvxnqgjm.html

[K05] 深拷贝对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2otwdfsox.html

Py:   copy.deepcopy(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2spodpcyo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yueranfly.top/Article/details/gt2iifyrubv.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2huzhvjlj.html

TS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2qvndulmc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yuanzhike.top/Article/details/gt2vikedjuc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shuidangran.top/Article/details/gt2aqybkjmg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.redwolf501.top/Article/details/gt2jyyebumf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenlongwang.top/Article/details/gt2fqmxpvhv.html

[K06] 解析 URL 查询串
来源：http://dali.jqgufenzy.top/Article/details/gt2uwjibkpm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.wangshuangyany.cn/Article/details/gt2ybnlhmrw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangdashe.top/Article/details/gt2cqshdkfz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gt2vrseeeuk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gt2kdoqzuzg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.guowangkeji.top/Article/details/gt2svrcxhtw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gt2jonbrxgn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gt2kbirugyq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gt2qljldajy.html

[K07] 进制转换
来源：http://dali.sufxvd.cn/Article/details/gt2osuwnecb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vbcmofmj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.meibo888.top/Article/details/gt2xjqajvcy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gt2fwjvrfdx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2tzqkldlq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hompvzyp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ydzc1.top/Article/details/gt2tzlkwvoo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xylfe.cn/Article/details/gt2wktjpgdv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gt2akgnkunx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj20258888.top/Article/details/gt2fsmggxhj.html

Py:   pickle.dumps(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2eapeqgnz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ndhkrchb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cqqwz.cn/Article/details/gt2cxagptze.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ehwqpu.com/Article/details/gt2hjrejdsh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.c1oappe.top/Article/details/gt2eeplecyl.html

Go:   encoding/gob
来源：http://dali.zycfv.cn/Article/details/gt2apkknopm.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2edhyqeow.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ivvv.top/Article/details/gt2htxtwaoh.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2mowpycsw.html

L. 网络请求
来源：http://dali.tian-w.cn/Article/details/gt2ukcyfvpo.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2nmzzgiii.html

[L01] 发送 GET 请求
来源：http://dali.cqqwz.cn/Article/details/gt2taxhmpbs.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ydzc1.top/Article/details/gt2vedouiiq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jqgfzy.top/Article/details/gt2fbjimvbe.html

JS:   await fetch(url)
来源：http://dali.zhoulong.xyz/Article/details/gt2kyneksgc.html

TS:   await fetch(url)
来源：http://dali.zycfv.cn/Article/details/gt2miikrumk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinqigfzy.top/Article/details/gt2rmlbmzum.html

Go:   resp, err := http.Get(url)
来源：http://dali.fengsongda.top/Article/details/gt2umhwnuoh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnqzz.top/Article/details/gt2gqzqhgqx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cqqwz.cn/Article/details/gt2tfbueoyo.html

[L02] 发送 POST JSON
来源：http://dali.gogol.net.cn/Article/details/gt2umktpgsz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258.top/Article/details/gt2xnunsmtf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.0kj1m.cn/Article/details/gt2xbhpxfag.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ivvv.top/Article/details/gt2nrqaguxi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sxryk.cn/Article/details/gt2phfjxfhd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ivvv.top/Article/details/gt2qyzlebmm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.haohaochexian.top/Article/details/gt2kusvcrca.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gotoacloud.top/Article/details/gt2iahayxoh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yangfankeji.com/Article/details/gt2vmbpkvie.html

[L03] 设置自定义请求头
来源：http://dali.jlsjyb.cn/Article/details/gt2rahibost.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.9152youxi.cn/Article/details/gt2tvrqlxlm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ehwqpu.com/Article/details/gt2hwhaaced.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gt2browjxuq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gt2bvshbmsa.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.guowangkeji.top/Article/details/gt2kwmaidnr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xvjmohea.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tianlin.xyz/Article/details/gt2cjevdxrm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jyoumei.cn/Article/details/gt2aktjakag.html

[L04] 设置超时
来源：http://dali.sxryk.cn/Article/details/gt2quxzxgvj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.guowangkeji.top/Article/details/gt2xoqssfkf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.dashuyun.cn/Article/details/gt2sghpmzpw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258.top/Article/details/gt2ddsijrdv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnxiangtu.top/Article/details/gt2szhjadzn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.nanxuanxn.top/Article/details/gt2zofmgeue.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dashuyun.cn/Article/details/gt2qoclpdxq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jahroagp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhixingplan.top/Article/details/gt2hywaplir.html

[L05] 上传文件（multipart）
来源：http://dali.andypj.xyz/Article/details/gt2ruupolvr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.kuanghao11.cn/Article/details/gt2ojkzajpz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.redwolf501.top/Article/details/gt2tjsfvpoj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhongyouzk.top/Article/details/gt2yklrveio.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.aibaodan.cn/Article/details/gt2osrncjko.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dashuyun.cn/Article/details/gt2ptaaxjhg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ckryuzfd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhoulong.xyz/Article/details/gt2mhfhyayv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2uvbaigdw.html

[L06] 解析响应为 JSON
来源：http://dali.yvedp.cn/Article/details/gt2xbiyuttq.html

Py:   resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gt2qwmaqseq.html

PHP:  json_decode($body, true);
来源：http://dali.ivvv.top/Article/details/gt2pogmgybf.html

JS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gt2sbntkthw.html

TS:   await resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gt2crvvcvpf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.meibo888.top/Article/details/gt2zvxysysh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xuanzx.com/Article/details/gt2tzkmngxz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuanzhike.top/Article/details/gt2norzncgg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.feifeiyinyue.top/Article/details/gt2lclbnfsl.html

[L07] 处理 HTTP 状态码
来源：http://dali.ivvv.top/Article/details/gt2klzrjnvu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ydzc1.top/Article/details/gt2qetrvpdq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shzxlz.cn/Article/details/gt2yzoztrks.html

JS:   resp.ok;  resp.status
来源：http://dali.yj20258888.top/Article/details/gt2drvkouxx.html

TS:   resp.ok;  resp.status
来源：http://dali.shzxlz.cn/Article/details/gt2fnjbnlmx.html

Java: resp.statusCode()
来源：http://dali.yongpay.top/Article/details/gt2ejtanflf.html

Go:   resp.StatusCode
来源：http://dali.ybcxt.top/Article/details/gt2jsjabnii.html

Ruby: resp.code.to_i
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xscgnkgh.html

C#:   (int)resp.StatusCode
来源：http://dali.0kj1m.cn/Article/details/gt2tvozlrhn.html

[L08] 并发请求多个地址
来源：http://dali.aibaodan.cn/Article/details/gt2sbsuofst.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangdashe.top/Article/details/gt2fpxwolmv.html

PHP:  curl_multi_init() 系列
来源：http://dali.cucudq.cn/Article/details/gt2oiyxedry.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gt2tjtiycnp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gt2dstkcosn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.haohaochexian.top/Article/details/gt2nttcmvaj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hywenlv.cn/Article/details/gt2ewhlhbqm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fengsongda.top/Article/details/gt2yxclwruo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gzhubu.top/Article/details/gt2bkqlqtxq.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2bxdtzaec.html

M. 命令行 / 进程 / 环境
来源：http://dali.ybcxt.top/Article/details/gt2dfgjkrad.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2znaerrjk.html

[M01] 读取命令行参数
来源：http://dali.gotoacloud.top/Article/details/gt2erbjxnan.html

Py:   sys.argv[1:]
来源：http://dali.kuanghao11.cn/Article/details/gt2zqvphjrj.html

PHP:  $argv;  $argc;
来源：http://dali.guannengcc.top/Article/details/gt2nechwagw.html

JS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gt2baemhrds.html

TS:   process.argv.slice(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wkirfgts.html

Java: args 数组（main 方法参数）
来源：http://dali.iojbl.cn/Article/details/gt2pewtoiul.html

Go:   os.Args[1:]
来源：http://dali.sweek.top/Article/details/gt2ugnzokwd.html

Ruby: ARGV
来源：http://dali.yj20258888.top/Article/details/gt2fqvnnvqg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tchibvjm.html

[M02] 读取环境变量
来源：http://dali.gogol.net.cn/Article/details/gt2bluvnxjs.html

Py:   os.environ.get("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gt2tgxrndin.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cqqwz.cn/Article/details/gt2hkhkoljr.html

JS:   process.env.HOME
来源：http://dali.sufxvd.cn/Article/details/gt2gambshti.html

TS:   process.env.HOME
来源：http://dali.9152youxi.cn/Article/details/gt2wbjpmmiu.html

Java: System.getenv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gt2nifzwqsu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gt2bezifeps.html

Ruby: ENV["HOME"]
来源：http://dali.nanxuanxn.top/Article/details/gt2bmajdlbz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.wangdashe.top/Article/details/gt2kwnzpmtc.html

[M03] 执行外部命令
来源：http://dali.zhongyouzk.top/Article/details/gt2ywsuvlpq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ivvv.top/Article/details/gt2ekjqullk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cdnleiting.top/Article/details/gt2avwjhnjz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jlsjyb.cn/Article/details/gt2ttzogjhr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.fzhhl.top/Article/details/gt2nysxycqw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.guannengcc.top/Article/details/gt2gnmrtogb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xuetiantiany.cn/Article/details/gt2xmumfwve.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yvedp.cn/Article/details/gt2yzlgynou.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sxryk.cn/Article/details/gt2wbqvkuhs.html

[M04] 获取当前工作目录
来源：http://dali.jiagoushi.top/Article/details/gt2vsyleolb.html

Py:   os.getcwd()
来源：http://dali.ehwqpu.com/Article/details/gt2ksvfpfvz.html

PHP:  getcwd();
来源：http://dali.jqgufenzy.top/Article/details/gt2rmmqrvce.html

JS:   process.cwd()
来源：http://dali.tanke756.top/Article/details/gt2whertpfp.html

TS:   process.cwd()
来源：http://dali.yangfankeji.com/Article/details/gt2fhqgjdvl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhengqikj.top/Article/details/gt2kzmhxztt.html

Go:   os.Getwd()
来源：http://dali.yanxiufei.cn/Article/details/gt2sdowfwpj.html

Ruby: Dir.pwd
来源：http://dali.xuetiantiany.cn/Article/details/gt2fjiuxzlv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj202588.top/Article/details/gt2bhdgsuwt.html

[M05] 设置退出码
来源：http://dali.smart0.xyz/Article/details/gt2knptgotc.html

Py:   sys.exit(1)
来源：http://dali.pycfn.com/Article/details/gt2znssbjkc.html

PHP:  exit(1);
来源：http://dali.nanxuanxn.top/Article/details/gt2kfwjohis.html

JS:   process.exit(1)
来源：http://dali.cashguo.top/Article/details/gt2pyhdflzl.html

TS:   process.exit(1)
来源：http://dali.sxryk.cn/Article/details/gt2dwvpqyfr.html

Java: System.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nqzrymjb.html

Go:   os.Exit(1)
来源：http://dali.yj202588.top/Article/details/gt2axjxsibj.html

Ruby: exit 1
来源：http://dali.shuidangran.top/Article/details/gt2dlmgakib.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dianchejie.cn/Article/details/gt2yjqqbxxn.html

[M06] 向标准错误输出
来源：http://dali.yanxiufei.cn/Article/details/gt2lkzrxnxg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhengqikj.top/Article/details/gt2dkthkqml.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.haohaochexian.top/Article/details/gt2pfpbmpaa.html

JS:   console.error("err")
来源：http://dali.hysaishi.cn/Article/details/gt2izvsoyeq.html

TS:   console.error("err")
来源：http://dali.cucudq.cn/Article/details/gt2gxbcxkuq.html

Java: System.err.println("err")
来源：http://dali.jinqigufen.top/Article/details/gt2mlprgruk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gaohongyu789.top/Article/details/gt2xyxazrne.html

Ruby: warn "err"
来源：http://dali.shuidangran.top/Article/details/gt2tqcwsaot.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.bjfxy.top/Article/details/gt2uzrbnrru.html

[M07] 判断是否为主入口
来源：http://dali.iojbl.cn/Article/details/gt2xhjyrbtw.html

Py:   if __name__ == "__main__":
来源：http://dali.yuanzhike.top/Article/details/gt2kelpenxq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.guowangkeji.top/Article/details/gt2psrljwzc.html

JS:   require.main === module
来源：http://dali.cdnleiting.top/Article/details/gt2lmhkrcpd.html

TS:   require.main === module
来源：http://dali.guowangkeji.top/Article/details/gt2aljzlbaj.html

Java: public static void main(String[] args)
来源：http://dali.wangshuangyany.cn/Article/details/gt2bjzmcgqy.html

Go:   func main()
来源：http://dali.vqdsnc.cn/Article/details/gt2qanywcfb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.fengsongda.top/Article/details/gt2wlbaaelt.html

C#:   static void Main(string[] args)
来源：http://dali.sxryk.cn/Article/details/gt2ignuiveg.html

[M08] 获取系统与运行时信息
来源：http://dali.nwbrower.top/Article/details/gt2utglwths.html

Py:   platform.system();  platform.python_version()
来源：http://dali.vqdsnc.cn/Article/details/gt2odjueycu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xinyue.icu/Article/details/gt2kikegtqr.html

JS:   process.platform;  process.version
来源：http://dali.yonumen.top/Article/details/gt2kpdhjmcl.html

TS:   process.platform;  process.version
来源：http://dali.316326.xyz/Article/details/gt2bsiitrxb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.fengsongda.top/Article/details/gt2rbywangd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbpzimx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xuetiantiany.cn/Article/details/gt2gswdjpsq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hnqzz.top/Article/details/gt2zpboclmj.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2bskrzarf.html

N. 数据结构与算法
来源：http://dali.jianghu66.top/Article/details/gt2gaekmswl.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2ggbiygys.html

[N01] 二分查找（有序数组）
来源：http://dali.ehwqpu.com/Article/details/gt2zffzybxf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.redwolf501.top/Article/details/gt2hyjmtgua.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yuxming.cn/Article/details/gt2louwyfiw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jyoumei.cn/Article/details/gt2elqvngvx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gt2tdumnkcv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gt2nsszdwtz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hammf.cn/Article/details/gt2qqgvmikv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258.top/Article/details/gt2twffzznv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wptmumyb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yuanzhike.top/Article/details/gt2dsfrljly.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yueranfly.top/Article/details/gt2irngmwcm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhongyouzk.top/Article/details/gt2trvqkafo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gt2qtmhapdp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gt2kbrolpir.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gotoacloud.top/Article/details/gt2wdfwavob.html

Go:   slices.Sort(arr)
来源：http://dali.cashguo.top/Article/details/gt2jbcijcrt.html

Ruby: arr.sort
来源：http://dali.ybcxt.top/Article/details/gt2gidiywaw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sysykeji.top/Article/details/gt2ynqgcumb.html

[N03] 快速排序（分治示例）
来源：http://dali.ybcxt.top/Article/details/gt2qdldxkmw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.dashuyun.cn/Article/details/gt2bwrurgsl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yuxming.cn/Article/details/gt2aoonsuse.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ehwqpu.com/Article/details/gt2wesdxnaf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gt2tynsaitm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.dianchejie.cn/Article/details/gt2ypkkwkcx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cashguo.top/Article/details/gt2bserbxcv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ppjwa.cn/Article/details/gt2mmxtjmwr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.daxiang520.top/Article/details/gt2astyguvp.html

[N04] 斐波那契数列
来源：http://dali.wangshuangyany.cn/Article/details/gt2onllejvz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2oojxywsu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.svipenyu.cn/Article/details/gt2jqjryhwf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gt2illktjhz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gt2ahuidcdr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.svipenyu.cn/Article/details/gt2firnypuq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2flofrjrm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2hnwuxdgk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gt2hnbbuynu.html

[N05] 最大公约数
来源：http://dali.zhiwuduotai.top/Article/details/gt2upmdwvva.html

Py:   math.gcd(a, b)
来源：http://dali.xziqi.cn/Article/details/gt2slyocteh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yanxiufei.cn/Article/details/gt2icdbglir.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jianghu66.top/Article/details/gt2gpbbzqwd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.bjfxy.top/Article/details/gt2lrjhzpzc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yvedp.cn/Article/details/gt2xisyomqp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.vqdsnc.cn/Article/details/gt2djmmqasy.html

Ruby: a.gcd(b)
来源：http://dali.redwolf501.top/Article/details/gt2oegkhcae.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.dianchejie.cn/Article/details/gt2whyufusk.html

[N06] 判断回文字符串
来源：http://dali.smart0.xyz/Article/details/gt2ohvptfhe.html

Py:   s == s[::-1]
来源：http://dali.redwolf501.top/Article/details/gt2ychhhmml.html

PHP:  $s === strrev($s);
来源：http://dali.birdmap.top/Article/details/gt2vqzbgprr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gt2lqmelymy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gt2txdzfcok.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ivvv.top/Article/details/gt2zmzofkgk.html

Go:   // 双指针从两端比较
来源：http://dali.iojbl.cn/Article/details/gt2pugzfekw.html

Ruby: s == s.reverse
来源：http://dali.xinyue.icu/Article/details/gt2flffhyuj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shangyingyoupin.top/Article/details/gt2ljpfyvop.html

[N07] 两数之和（返回下标）
来源：http://dali.gaohongyu789.top/Article/details/gt2bqteqnsb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2udsqtivj.html


<!-- 参考信息 -->