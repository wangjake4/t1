代发 wailian999

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shangyingyoupin.top/Article/details/gt2rihslsai.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wknpqtil.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhengqikj.top/Article/details/gt2labcagzn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenzaomai.com/Article/details/gt2blwntwoe.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinqigufen.top/Article/details/gt2ygtnfavb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ovsjwbnr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yueranfly.top/Article/details/gt2lanxwmmh.html

[J10] 取今天 / 本月第一天
来源：http://dali.hongshengwenyu.top/Article/details/gt2jrouwpod.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cdnleiting.top/Article/details/gt2fjhkivag.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.pengpengdd.cyou/Article/details/gt2cbpxpdkc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj20258888.top/Article/details/gt2yseofslc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2oemnujve.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.birdmap.top/Article/details/gt2rkvuurio.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gogol.net.cn/Article/details/gt2azhplchu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hammf.cn/Article/details/gt2leezfplz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yvedp.cn/Article/details/gt2xdfgulqv.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2bbapdnwl.html

K. JSON 与序列化
来源：http://dali.snrcjt.cn/Article/details/gt2mmsmguzk.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2nybsduqz.html

[K01] 对象转 JSON 字符串
来源：http://dali.c1oappe.top/Article/details/gt2xzbfzzwb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.havefunace.top/Article/details/gt2hwemloer.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shzxlz.cn/Article/details/gt2tcslxgll.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2gtfqyznf.html

TS:   JSON.stringify(obj)
来源：http://dali.meibo888.top/Article/details/gt2lrfgninh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhongyouzk.top/Article/details/gt2oddrhezc.html

Go:   json.Marshal(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2coqcwitj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhongyouzk.top/Article/details/gt2blmummir.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2xeibxgkh.html

[K02] JSON 字符串转对象
来源：http://dali.yuxming.cn/Article/details/gt2pwmbmgxk.html

Py:   json.loads(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2ifasdtbs.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gogol.net.cn/Article/details/gt2srjesdqs.html

JS:   JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hwlxvbjk.html

TS:   JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gt2hysaolae.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.aizwys.cn/Article/details/gt2ipccalsz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aibaodan.cn/Article/details/gt2qefnyoog.html

Ruby: JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gt2chqdrthc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sweek.top/Article/details/gt2pvmhwceh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zycfv.cn/Article/details/gt2vydvmscs.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenzaomai.com/Article/details/gt2icolcgmy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gt2bcyyxeet.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gt2ritoscne.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cqqwz.cn/Article/details/gt2jkytewmt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2betatqbp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shzxlz.cn/Article/details/gt2dutllkqk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lmlfpqtc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shuidangran.top/Article/details/gt2hdqlnobp.html

[K04] 读取 JSON 文件
来源：http://dali.chenlongwang.top/Article/details/gt2jmtyiwrv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.iojbl.cn/Article/details/gt2fvvywtgk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hnqzz.top/Article/details/gt2adfvxnyg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gt2cywduccz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gt2hutwcjzt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gt2frjnooel.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cqqwz.cn/Article/details/gt2rekblaws.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jianghu66.top/Article/details/gt2ufvoaios.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cheryme.top/Article/details/gt2abntairc.html

[K05] 深拷贝对象
来源：http://dali.svipenyu.cn/Article/details/gt2buxhjwby.html

Py:   copy.deepcopy(obj)
来源：http://dali.fengsongda.top/Article/details/gt2habliuct.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eqeikcrf.html

JS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2rtehcmzw.html

TS:   structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2aepcaqsu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jianghu66.top/Article/details/gt2daljkgkx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.vqdsnc.cn/Article/details/gt2siowjsvc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shangyingyoupin.top/Article/details/gt2qosdsdok.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cucudq.cn/Article/details/gt2kbkvzbwt.html

[K06] 解析 URL 查询串
来源：http://dali.jinqigufen.top/Article/details/gt2hlmqpkrw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.daria6918.cn/Article/details/gt2lujdzjwe.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gogol.net.cn/Article/details/gt2bpcyznow.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258.top/Article/details/gt2xgbrxacn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aibaodan.cn/Article/details/gt2cypieksj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aibaodan.cn/Article/details/gt2hrrgdrwe.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gt2agdfsooo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.dashuyun.cn/Article/details/gt2eqhwsnzn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gt2krzulgrs.html

[K07] 进制转换
来源：http://dali.nanxuanxn.top/Article/details/gt2zrqtdesi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gt2inztybkv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hysaishi.cn/Article/details/gt2mfpcpxkg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gt2llpqkjai.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gt2nxgzlayj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2ohdoktul.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ybcxt.top/Article/details/gt2sviyptjr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jyoumei.cn/Article/details/gt2lrwkqmmc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gt2incwyjau.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hnqzz.top/Article/details/gt2hhupqfhw.html

Py:   pickle.dumps(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2eniydtaz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.dashuyun.cn/Article/details/gt2foficlzi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gt2frtgjtri.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2xarokgxi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yanxiufei.cn/Article/details/gt2ugxyopis.html

Go:   encoding/gob
来源：http://dali.sysykeji.top/Article/details/gt2blqvnytm.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj20258.top/Article/details/gt2dvkswerm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shzxlz.cn/Article/details/gt2nxwyqxpx.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2hqpmfuan.html

L. 网络请求
来源：http://dali.zdqjudy.top/Article/details/gt2fptvztmz.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2jokedquw.html

[L01] 发送 GET 请求
来源：http://dali.ppjwa.cn/Article/details/gt2mcmwwrdg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sysykeji.top/Article/details/gt2uxuemfhw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zdqjudy.top/Article/details/gt2tzktfngf.html

JS:   await fetch(url)
来源：http://dali.shangyingyoupin.top/Article/details/gt2yrgmxlxv.html

TS:   await fetch(url)
来源：http://dali.jinqigfzy.top/Article/details/gt2ztdbgqky.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sysykeji.top/Article/details/gt2grmhaomq.html

Go:   resp, err := http.Get(url)
来源：http://dali.yvedp.cn/Article/details/gt2numzwlui.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.quarkkingdee.top/Article/details/gt2lvvpdqtl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenzaomai.com/Article/details/gt2qdbujgjr.html

[L02] 发送 POST JSON
来源：http://dali.birdmap.top/Article/details/gt2scdfarzb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tanke756.top/Article/details/gt2ugyeaedf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yuxming.cn/Article/details/gt2dmpoplpk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.meibo888.top/Article/details/gt2iajtfont.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.kuanghao11.cn/Article/details/gt2sqvjxqpk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tanke756.top/Article/details/gt2bqfsbirf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tycvobvc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj20258.top/Article/details/gt2nbvmtclj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daxiang520.top/Article/details/gt2ybqrzrim.html

[L03] 设置自定义请求头
来源：http://dali.dashuyun.cn/Article/details/gt2mazqjgiz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cqqwz.cn/Article/details/gt2vndpomzk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cucudq.cn/Article/details/gt2wzbtgjcn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cdnleiting.top/Article/details/gt2pktyjkye.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.mhx1999.top/Article/details/gt2bdcgrbls.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ppjwa.cn/Article/details/gt2slndqxto.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zdqjudy.top/Article/details/gt2jwpxepfa.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eojiagmg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gt2ptalwjmk.html

[L04] 设置超时
来源：http://dali.xuanzx.com/Article/details/gt2qehxjtgu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ybcxt.top/Article/details/gt2irrsnyyc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ehwqpu.com/Article/details/gt2jpftyykn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hfpthk.cn/Article/details/gt2kgfpaeuo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gt2uzcowewb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.andypj.xyz/Article/details/gt2zqwtjybw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangdashe.top/Article/details/gt2hfnnniro.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.316326.xyz/Article/details/gt2qwevsujj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.smart0.xyz/Article/details/gt2orcnbdkj.html

[L05] 上传文件（multipart）
来源：http://dali.snrcjt.cn/Article/details/gt2hfacvfjc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.vqdsnc.cn/Article/details/gt2rvdcltkx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258888.top/Article/details/gt2hbtdxdug.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.redwolf501.top/Article/details/gt2pgoyvgtw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ybcxt.top/Article/details/gt2vcatogdj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zxeprgvc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dianchejie.cn/Article/details/gt2jazhknll.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.c1oappe.top/Article/details/gt2zkuewusk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2ybujfpvv.html

[L06] 解析响应为 JSON
来源：http://dali.fzhhl.top/Article/details/gt2mgjkwrii.html

Py:   resp.json()
来源：http://dali.316326.xyz/Article/details/gt2ieoeqplf.html

PHP:  json_decode($body, true);
来源：http://dali.bjfxy.top/Article/details/gt2zzuvghyr.html

JS:   await resp.json()
来源：http://dali.shzxlz.cn/Article/details/gt2kufgznky.html

TS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gt2aeamanwy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jnrtwlil.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.meibo888.top/Article/details/gt2rcgybsnt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shuidangran.top/Article/details/gt2dtqfvcth.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.dashuyun.cn/Article/details/gt2qzcdzywn.html

[L07] 处理 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gt2cygrxcdw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.haohaochexian.top/Article/details/gt2ljqkxlab.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gotoacloud.top/Article/details/gt2cafarlxv.html

JS:   resp.ok;  resp.status
来源：http://dali.yvedp.cn/Article/details/gt2inqigqgb.html

TS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gt2jxxjyjxh.html

Java: resp.statusCode()
来源：http://dali.xylfe.cn/Article/details/gt2rscfeunl.html

Go:   resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gt2abohsllt.html

Ruby: resp.code.to_i
来源：http://dali.zycfv.cn/Article/details/gt2cmaynpgh.html

C#:   (int)resp.StatusCode
来源：http://dali.zhengqikj.top/Article/details/gt2madkgfac.html

[L08] 并发请求多个地址
来源：http://dali.gotoacloud.top/Article/details/gt2caubsygq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.kuanghao11.cn/Article/details/gt2rcncucur.html

PHP:  curl_multi_init() 系列
来源：http://dali.svipenyu.cn/Article/details/gt2xviahgfj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gt2atimsgyq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cdnleiting.top/Article/details/gt2eblepaha.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wxlltlid.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdvyflv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zycfv.cn/Article/details/gt2hucidqtd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinqigfzy.top/Article/details/gt2pzobmhti.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2mzvsutbw.html

M. 命令行 / 进程 / 环境
来源：http://dali.hnxiangtu.top/Article/details/gt2cbeojkkv.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2vhtqnabn.html

[M01] 读取命令行参数
来源：http://dali.yuxming.cn/Article/details/gt2oomhcgcx.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2fqyglbdw.html

PHP:  $argv;  $argc;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xqcrggqz.html

JS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lrgoebtq.html

TS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gt2hfmjiovu.html

Java: args 数组（main 方法参数）
来源：http://dali.316326.xyz/Article/details/gt2rnoscywl.html

Go:   os.Args[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gt2cdedwues.html

Ruby: ARGV
来源：http://dali.yj202588.top/Article/details/gt2nejnwaxd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gt2ajfbdrtn.html

[M02] 读取环境变量
来源：http://dali.zhixingplan.top/Article/details/gt2vggjcwtj.html

Py:   os.environ.get("HOME")
来源：http://dali.haohaochexian.top/Article/details/gt2kbochznf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gt2rufdjjac.html

JS:   process.env.HOME
来源：http://dali.ppjwa.cn/Article/details/gt2fphvanjj.html

TS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gt2nfqqijap.html

Java: System.getenv("HOME")
来源：http://dali.nanxinkj.top/Article/details/gt2nnseccur.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pycfn.com/Article/details/gt2dhfxtjjx.html

Ruby: ENV["HOME"]
来源：http://dali.nwbrower.top/Article/details/gt2cdovsrmg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cqqwz.cn/Article/details/gt2pmvycuyr.html

[M03] 执行外部命令
来源：http://dali.fzhhl.top/Article/details/gt2odxwuezm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hywenlv.cn/Article/details/gt2yqjiyggi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cucudq.cn/Article/details/gt2rxvnkifr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ivvv.top/Article/details/gt2sljklnvx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gt2eiztlhca.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.fzhhl.top/Article/details/gt2rpuvkjoy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxuanxn.top/Article/details/gt2uqikeozv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.vqdsnc.cn/Article/details/gt2nbzvfora.html

C#:   Process.Start("ls", "-l");
来源：http://dali.smart0.xyz/Article/details/gt2ixxygunh.html

[M04] 获取当前工作目录
来源：http://dali.jqgfzy.top/Article/details/gt2sowyspoi.html

Py:   os.getcwd()
来源：http://dali.ehwqpu.com/Article/details/gt2dmvzxyxv.html

PHP:  getcwd();
来源：http://dali.vqdsnc.cn/Article/details/gt2phejpovi.html

JS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gt2xqdhhheo.html

TS:   process.cwd()
来源：http://dali.zdqjudy.top/Article/details/gt2bkooxgjz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jiagoushi.top/Article/details/gt2bjgunjdw.html

Go:   os.Getwd()
来源：http://dali.aibaodan.cn/Article/details/gt2tabiomoc.html

Ruby: Dir.pwd
来源：http://dali.cheryme.top/Article/details/gt2ceyliuna.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yuanzhike.top/Article/details/gt2jhtczbfe.html

[M05] 设置退出码
来源：http://dali.hysaishi.cn/Article/details/gt2tcvlobda.html

Py:   sys.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wemedhwt.html

PHP:  exit(1);
来源：http://dali.aibaodan.cn/Article/details/gt2nayxldha.html

JS:   process.exit(1)
来源：http://dali.ivvv.top/Article/details/gt2smicfwrq.html

TS:   process.exit(1)
来源：http://dali.jianghu66.top/Article/details/gt2meyyeppt.html

Java: System.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gt2gnvncibb.html

Go:   os.Exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2anevpqme.html

Ruby: exit 1
来源：http://dali.jianghu66.top/Article/details/gt2okfeisxh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.pycfn.com/Article/details/gt2fbrnsrso.html

[M06] 向标准错误输出
来源：http://dali.sufxvd.cn/Article/details/gt2nadbyutw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zycfv.cn/Article/details/gt2zqymdbwk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhoulong.xyz/Article/details/gt2cimosbul.html

JS:   console.error("err")
来源：http://dali.zhixingplan.top/Article/details/gt2tnlbasys.html

TS:   console.error("err")
来源：http://dali.sufxvd.cn/Article/details/gt2vbxasfjg.html

Java: System.err.println("err")
来源：http://dali.sufxvd.cn/Article/details/gt2bsplgduo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.snrcjt.cn/Article/details/gt2dsgcqjak.html

Ruby: warn "err"
来源：http://dali.snrcjt.cn/Article/details/gt2rwduciay.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.0kj1m.cn/Article/details/gt2eyezvbkn.html

[M07] 判断是否为主入口
来源：http://dali.yangfankeji.com/Article/details/gt2qldpsjmw.html

Py:   if __name__ == "__main__":
来源：http://dali.9152youxi.cn/Article/details/gt2apjrdlvv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yonumen.top/Article/details/gt2wjbnvjdw.html

JS:   require.main === module
来源：http://dali.pengpengdd.cyou/Article/details/gt2ssaxffpo.html

TS:   require.main === module
来源：http://dali.bjfxy.top/Article/details/gt2nwdqonot.html

Java: public static void main(String[] args)
来源：http://dali.yuxming.cn/Article/details/gt2fnnsnjdn.html

Go:   func main()
来源：http://dali.sweek.top/Article/details/gt2iaajnkbb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yueranfly.top/Article/details/gt2gdclepzr.html

C#:   static void Main(string[] args)
来源：http://dali.birdmap.top/Article/details/gt2hcbbjzjr.html

[M08] 获取系统与运行时信息
来源：http://dali.yj202588.top/Article/details/gt2qtzwpabp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xylfe.cn/Article/details/gt2iprkakbo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hysaishi.cn/Article/details/gt2mntubstn.html

JS:   process.platform;  process.version
来源：http://dali.chenzaomai.com/Article/details/gt2swbguirq.html

TS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gt2bmdgbudp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj20258.top/Article/details/gt2xomzpueu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.haohaochexian.top/Article/details/gt2ogqcwgzd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj202588.top/Article/details/gt2wrqgbttj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.kuanghao11.cn/Article/details/gt2lwnahmsu.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2pqirzwyl.html

N. 数据结构与算法
来源：http://dali.haohaochexian.top/Article/details/gt2opfqdbdi.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2uwmpyopq.html

[N01] 二分查找（有序数组）
来源：http://dali.nanxuanxn.top/Article/details/gt2zsmstgjl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2cqgpncsh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xylfe.cn/Article/details/gt2ssufwbej.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ppjwa.cn/Article/details/gt2stvxeazh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gt2opixtbku.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qqdgbunk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2stivjofv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xinyue.icu/Article/details/gt2fpkwkkqv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj20258.top/Article/details/gt2twximasx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.quarkkingdee.top/Article/details/gt2juybamck.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ivvv.top/Article/details/gt2umtcamol.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.9152youxi.cn/Article/details/gt2qtgvtwvy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gt2iphdedai.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2yvfifrbv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.fengsongda.top/Article/details/gt2vvnzszbb.html

Go:   slices.Sort(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2yxkgiyom.html

Ruby: arr.sort
来源：http://dali.gotoacloud.top/Article/details/gt2bzrzhgba.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenzaomai.com/Article/details/gt2kidvluxb.html

[N03] 快速排序（分治示例）
来源：http://dali.cheryme.top/Article/details/gt2phklssuq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhixingplan.top/Article/details/gt2rfcnahgz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gotoacloud.top/Article/details/gt2utctqnde.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zycfv.cn/Article/details/gt2anvkwlqo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhoulong.xyz/Article/details/gt2crqmaizh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.316326.xyz/Article/details/gt2ynpvrcli.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dhoxwqsy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zueipnrc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shangyingyoupin.top/Article/details/gt2jinthexu.html

[N04] 斐波那契数列
来源：http://dali.sweek.top/Article/details/gt2rxuufsyl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lnpovjpa.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.dianchejie.cn/Article/details/gt2quqozgsf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cqqwz.cn/Article/details/gt2addcrsbm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cdltoaxl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.svipenyu.cn/Article/details/gt2jdkcvede.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hysaishi.cn/Article/details/gt2lijndwar.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2ghcowvjh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gt2hfmdfozk.html

[N05] 最大公约数
来源：http://dali.jyoumei.cn/Article/details/gt2kblqnqxe.html

Py:   math.gcd(a, b)
来源：http://dali.chenlongwang.top/Article/details/gt2xmwarett.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenzaomai.com/Article/details/gt2ypylpppi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cqqwz.cn/Article/details/gt2gvpxvrbd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xinyue.icu/Article/details/gt2toqskbzs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ybcxt.top/Article/details/gt2oweaaenw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nanxinkj.top/Article/details/gt2rjsfbicn.html

Ruby: a.gcd(b)
来源：http://dali.gaohongyu789.top/Article/details/gt2avaxjbgb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gvncakuw.html

[N06] 判断回文字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2csdsobtb.html

Py:   s == s[::-1]
来源：http://dali.chenlongwang.top/Article/details/gt2zvkvjzpb.html

PHP:  $s === strrev($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2euphjhwy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gt2jbzkpxmy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gt2gkvlzzyx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2rjafdtjw.html

Go:   // 双指针从两端比较
来源：http://dali.daxiang520.top/Article/details/gt2htzvgxsk.html

Ruby: s == s.reverse
来源：http://dali.cucudq.cn/Article/details/gt2mpiilbcr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yuanzhike.top/Article/details/gt2cmkajwcr.html

[N07] 两数之和（返回下标）
来源：http://dali.hnqzz.top/Article/details/gt2fjufhemb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.dashuyun.cn/Article/details/gt2ulforacu.html


<!-- 参考信息 -->