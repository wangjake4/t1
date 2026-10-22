代发 wailian999

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yuxming.cn/Article/details/gtywusocvz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.0kj1m.cn/Article/details/gtmhkdbpmb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gtptrmlbbb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zycfv.cn/Article/details/gtdrdgkxtc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.kuanghao11.cn/Article/details/gtkrxnkybz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gotoacloud.top/Article/details/gtomgkcqod.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.guowangkeji.top/Article/details/gtmqxxcbyb.html

[J10] 取今天 / 本月第一天
来源：http://dali.andypj.xyz/Article/details/gtllgjutoi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xuetiantiany.cn/Article/details/gtjhgojafp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.dianchejie.cn/Article/details/gtcsrreaeu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ydzc1.top/Article/details/gtxjpujpqn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.guowangkeji.top/Article/details/gtonfttuyq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.smart0.xyz/Article/details/gtvkcezpea.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xziqi.cn/Article/details/gtjjdwzfqv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ehwqpu.com/Article/details/gtrqdvpegg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yvedp.cn/Article/details/gtbeitzdgj.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtxzwghebp.html

K. JSON 与序列化
来源：http://dali.tanke756.top/Article/details/gtgboaaahr.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtjplzzpwy.html

[K01] 对象转 JSON 字符串
来源：http://dali.meibo888.top/Article/details/gtqhvogvar.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.redwolf501.top/Article/details/gtbmjblqoi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj202588.top/Article/details/gtzavwmurx.html

JS:   JSON.stringify(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtqxycvdgh.html

TS:   JSON.stringify(obj)
来源：http://dali.cqqwz.cn/Article/details/gtwjgpvqim.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jlsjyb.cn/Article/details/gtnmkccqwl.html

Go:   json.Marshal(obj)
来源：http://dali.sxryk.cn/Article/details/gtwmjgzvmh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cashguo.top/Article/details/gtxixbfhns.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtalewdees.html

[K02] JSON 字符串转对象
来源：http://dali.wangdashe.top/Article/details/gtsspztxfc.html

Py:   json.loads(s)
来源：http://dali.sufxvd.cn/Article/details/gtmpgruebp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.andypj.xyz/Article/details/gtridajiyf.html

JS:   JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gtdqrmvhbf.html

TS:   JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gtsncdcssu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gotoacloud.top/Article/details/gthfcjfotq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gogol.net.cn/Article/details/gtvieawkzn.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gtsvrkjsrz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sufxvd.cn/Article/details/gttovetzrk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrljprkqe.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gtokksuaso.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gtytifkdhg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtzpushtfd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gtzgjqdyew.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xylfe.cn/Article/details/gthlwgjveq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yonumen.top/Article/details/gthtpzknje.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.pycfn.com/Article/details/gtszyohuvu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hysaishi.cn/Article/details/gtxisauykf.html

[K04] 读取 JSON 文件
来源：http://dali.guannengcc.top/Article/details/gtfpofseox.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yongpay.top/Article/details/gtoynagscw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gzhubu.top/Article/details/gtqndpeupr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxuanxn.top/Article/details/gtzlkhtyme.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xinyue.icu/Article/details/gteekyozho.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jqgfzy.top/Article/details/gtguxupjgv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sweek.top/Article/details/gtyfvwoqpr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenzaomai.com/Article/details/gtsjirjdlh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gtdsgmzozq.html

[K05] 深拷贝对象
来源：http://dali.wangshuangyany.cn/Article/details/gtcyfrelxt.html

Py:   copy.deepcopy(obj)
来源：http://dali.shzxlz.cn/Article/details/gtthokvtft.html

PHP:  unserialize(serialize($obj));
来源：http://dali.haohaochexian.top/Article/details/gtyvnxseqa.html

JS:   structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gtteclwvko.html

TS:   structuredClone(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtmsqpytbn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yangfankeji.com/Article/details/gtuholabdi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cashguo.top/Article/details/gtaqwhzvru.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.dianchejie.cn/Article/details/gtatuyjews.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinghuilouyu.cn/Article/details/gtliukshfj.html

[K06] 解析 URL 查询串
来源：http://dali.pycfn.com/Article/details/gtqjpzsyot.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpukpdgnu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258888.top/Article/details/gtthvqmxvg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.birdmap.top/Article/details/gtqznietvv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gotoacloud.top/Article/details/gtnxmlsnmc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenjidiqi.icu/Article/details/gtephiastz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gtewrcmlsw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gtgbguwkyc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gtpjvgvsvd.html

[K07] 进制转换
来源：http://dali.daxiang520.top/Article/details/gtznazbqep.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtlgwjoont.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yueranfly.top/Article/details/gtloyvkaow.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtcqwzrrfu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtcbiypwzx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtrpwvznql.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cdnleiting.top/Article/details/gtortqqzat.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jlsjyb.cn/Article/details/gtpkeomybu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtpzpiavlk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gogol.net.cn/Article/details/gtpdkiuwua.html

Py:   pickle.dumps(obj)
来源：http://dali.cheryme.top/Article/details/gtflmzhnos.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.chenzaomai.com/Article/details/gtephocwmv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsgbtndu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xuetiantiany.cn/Article/details/gtmmrsrmxg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ivvv.top/Article/details/gtjsjnghwi.html

Go:   encoding/gob
来源：http://dali.nanxuanxn.top/Article/details/gtnxobmlfn.html

Ruby: Marshal.dump(obj)
来源：http://dali.xuanzx.com/Article/details/gtssfrxfsv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.mhx1999.top/Article/details/gtuibrzdiy.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtkdcyiyjl.html

L. 网络请求
来源：http://dali.redwolf501.top/Article/details/gtfzigblse.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtacxzmebs.html

[L01] 发送 GET 请求
来源：http://dali.havefunace.top/Article/details/gtftsezhxv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.kuanghao11.cn/Article/details/gtzbszrsdb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.svipenyu.cn/Article/details/gtsioardzp.html

JS:   await fetch(url)
来源：http://dali.pycfn.com/Article/details/gtkawsylug.html

TS:   await fetch(url)
来源：http://dali.hysaishi.cn/Article/details/gtakgalilc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.aizwys.cn/Article/details/gtidebsvsl.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj20258.top/Article/details/gtuzuqeiwn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.dashuyun.cn/Article/details/gtxhpbdqqa.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sysykeji.top/Article/details/gtjsmocuiv.html

[L02] 发送 POST JSON
来源：http://dali.cucudq.cn/Article/details/gtllidnmae.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gogol.net.cn/Article/details/gtvknasecq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xuetiantiany.cn/Article/details/gtrtjelrjq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cdnleiting.top/Article/details/gtameiajam.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gogol.net.cn/Article/details/gtwqxljwfw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tanke756.top/Article/details/gtrjhawavi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.havefunace.top/Article/details/gtjcapzvzv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.redwolf501.top/Article/details/gtuwxcjwmh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbhnkddc.html

[L03] 设置自定义请求头
来源：http://dali.hysaishi.cn/Article/details/gtjstpxoqg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dashuyun.cn/Article/details/gtkynqhvbl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenzaomai.com/Article/details/gtmqnvwbcf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gogol.net.cn/Article/details/gtkqvtydte.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gtbbuapbuw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shanyushiyangtech.top/Article/details/gtrtfowdty.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gtxyafovjc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.0kj1m.cn/Article/details/gttvowhhwu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jqgufenzy.top/Article/details/gtfrrnjjoq.html

[L04] 设置超时
来源：http://dali.sysykeji.top/Article/details/gtzlzhtglo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.daria6918.cn/Article/details/gtwtcgisbn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tianlin.xyz/Article/details/gtbcggrnsp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yvedp.cn/Article/details/gtxkgxvguh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.316326.xyz/Article/details/gtagpfjzxd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xinyue.icu/Article/details/gtowwyrhgs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.316326.xyz/Article/details/gtxxzgvwyd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ppjwa.cn/Article/details/gtizyrdyeq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nanxinkj.top/Article/details/gtvbzdxcud.html

[L05] 上传文件（multipart）
来源：http://dali.daria6918.cn/Article/details/gtwwymnqqk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gotoacloud.top/Article/details/gtmitsygvr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.pengpengdd.cyou/Article/details/gtywuyqshe.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gtegvpqfet.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.svipenyu.cn/Article/details/gtzdulrzbb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guowangkeji.top/Article/details/gtccttlehe.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenzaomai.com/Article/details/gtmdmedife.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.redwolf501.top/Article/details/gtrnqhqghm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtdeooxjgu.html

[L06] 解析响应为 JSON
来源：http://dali.havefunace.top/Article/details/gtnohfycwk.html

Py:   resp.json()
来源：http://dali.cashguo.top/Article/details/gthqcvbrla.html

PHP:  json_decode($body, true);
来源：http://dali.hnxiangtu.top/Article/details/gtvfqbuosd.html

JS:   await resp.json()
来源：http://dali.cheryme.top/Article/details/gtfxoflhoe.html

TS:   await resp.json()
来源：http://dali.ppjwa.cn/Article/details/gttthuawfu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.wangdashe.top/Article/details/gtzvqokzdi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.birdmap.top/Article/details/gtleovnoqe.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258888.top/Article/details/gtrcmsvfjw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.birdmap.top/Article/details/gtsbmazjpe.html

[L07] 处理 HTTP 状态码
来源：http://dali.yangfankeji.com/Article/details/gtxtagkmkw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hongshengwenyu.top/Article/details/gtrooxtwib.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.haohaochexian.top/Article/details/gtcznnzuqu.html

JS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gtfdnxrzjk.html

TS:   resp.ok;  resp.status
来源：http://dali.yueranfly.top/Article/details/gtruclifzn.html

Java: resp.statusCode()
来源：http://dali.hnqzz.top/Article/details/gtvxsoprqb.html

Go:   resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gtmsihwlvo.html

Ruby: resp.code.to_i
来源：http://dali.xuetiantiany.cn/Article/details/gtfmgizebt.html

C#:   (int)resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gtwjevrvdm.html

[L08] 并发请求多个地址
来源：http://dali.wangdashe.top/Article/details/gtonkbrerd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ehwqpu.com/Article/details/gtnaffgadp.html

PHP:  curl_multi_init() 系列
来源：http://dali.ivvv.top/Article/details/gtpcwahmba.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gtcerrkzdl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnqzz.top/Article/details/gtvnfwbbpn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.316326.xyz/Article/details/gtmvxbwnrd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zdqjudy.top/Article/details/gtmoxowdtm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.iojbl.cn/Article/details/gtdmwcqwgn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ivvv.top/Article/details/gtzftpirov.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtynjvbdxu.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhixingplan.top/Article/details/gtuvgtlitw.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtwdzfhdwi.html

[M01] 读取命令行参数
来源：http://dali.feifeiyinyue.top/Article/details/gtaqqldxgy.html

Py:   sys.argv[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwwqsboys.html

PHP:  $argv;  $argc;
来源：http://dali.xuanzx.com/Article/details/gtfborechh.html

JS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gttixrursl.html

TS:   process.argv.slice(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtqwuslxmc.html

Java: args 数组（main 方法参数）
来源：http://dali.hnxiangtu.top/Article/details/gtbgbvxakj.html

Go:   os.Args[1:]
来源：http://dali.316326.xyz/Article/details/gtlhfufzzi.html

Ruby: ARGV
来源：http://dali.hywenlv.cn/Article/details/gtkuuflneu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gtvytrmlcw.html

[M02] 读取环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvyxpppr.html

Py:   os.environ.get("HOME")
来源：http://dali.pycfn.com/Article/details/gtfmbgkpep.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sweek.top/Article/details/gtowjvoatu.html

JS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gtyvmlkyvu.html

TS:   process.env.HOME
来源：http://dali.c1oappe.top/Article/details/gtrfexggst.html

Java: System.getenv("HOME")
来源：http://dali.andypj.xyz/Article/details/gtzpuogiqu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.smart0.xyz/Article/details/gtoounqoaj.html

Ruby: ENV["HOME"]
来源：http://dali.zhengqikj.top/Article/details/gtxjtoepsr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yonumen.top/Article/details/gtwkjyxgwn.html

[M03] 执行外部命令
来源：http://dali.0kj1m.cn/Article/details/gtflvztvlw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.snrcjt.cn/Article/details/gtvvabgdns.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258888.top/Article/details/gtkiromqyn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcwagpgbq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hfpthk.cn/Article/details/gtzzsykcsf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jianghu66.top/Article/details/gtyabeezgo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjkwxpkos.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhengqikj.top/Article/details/gtiblblpog.html

C#:   Process.Start("ls", "-l");
来源：http://dali.svipenyu.cn/Article/details/gtuyuwjvcw.html

[M04] 获取当前工作目录
来源：http://dali.nanxinkj.top/Article/details/gtnjqkosqe.html

Py:   os.getcwd()
来源：http://dali.ehwqpu.com/Article/details/gtdfzyuvou.html

PHP:  getcwd();
来源：http://dali.xinyue.icu/Article/details/gtzpcrbtqu.html

JS:   process.cwd()
来源：http://dali.yvedp.cn/Article/details/gtopdlahbr.html

TS:   process.cwd()
来源：http://dali.yongpay.top/Article/details/gtzflkjvnz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ybcxt.top/Article/details/gtkqymknev.html

Go:   os.Getwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxntdtkos.html

Ruby: Dir.pwd
来源：http://dali.daxiang520.top/Article/details/gtqyvyieya.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hfpthk.cn/Article/details/gtvkpnkdki.html

[M05] 设置退出码
来源：http://dali.cqqwz.cn/Article/details/gtilqzgtnx.html

Py:   sys.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtvwmjuahl.html

PHP:  exit(1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtohjjfykk.html

JS:   process.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtbswzhduc.html

TS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtreeuwkgs.html

Java: System.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtntsbxdtx.html

Go:   os.Exit(1)
来源：http://dali.cheryme.top/Article/details/gtjgjkkael.html

Ruby: exit 1
来源：http://dali.daria6918.cn/Article/details/gtnintsvyd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.iojbl.cn/Article/details/gtqfwiyaux.html

[M06] 向标准错误输出
来源：http://dali.hammf.cn/Article/details/gtbghxbdln.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xylfe.cn/Article/details/gtydtifdia.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nanxinkj.top/Article/details/gtoklrvcwb.html

JS:   console.error("err")
来源：http://dali.nanxuanxn.top/Article/details/gtbqlwwvwv.html

TS:   console.error("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyhhzorih.html

Java: System.err.println("err")
来源：http://dali.bjfxy.top/Article/details/gtkbvylcif.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gaohongyu789.top/Article/details/gtxrywzhcn.html

Ruby: warn "err"
来源：http://dali.jiagoushi.top/Article/details/gtgqknunek.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tianlin.xyz/Article/details/gtcjklpayi.html

[M07] 判断是否为主入口
来源：http://dali.nwbrower.top/Article/details/gtubdbotxq.html

Py:   if __name__ == "__main__":
来源：http://dali.cucudq.cn/Article/details/gtdvjwtqys.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhixingplan.top/Article/details/gtbmgdcigr.html

JS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gtukywlaoq.html

TS:   require.main === module
来源：http://dali.gogol.net.cn/Article/details/gtchovajmb.html

Java: public static void main(String[] args)
来源：http://dali.guannengcc.top/Article/details/gtdwwnbnmw.html

Go:   func main()
来源：http://dali.yangfankeji.com/Article/details/gtpoywrjgc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.dashuyun.cn/Article/details/gtbmwfaqro.html

C#:   static void Main(string[] args)
来源：http://dali.hysaishi.cn/Article/details/gtfuznlsed.html

[M08] 获取系统与运行时信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbyqpeadv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.c1oappe.top/Article/details/gtnrcmylkl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hfpthk.cn/Article/details/gtwproxgzs.html

JS:   process.platform;  process.version
来源：http://dali.snrcjt.cn/Article/details/gtyotelxmw.html

TS:   process.platform;  process.version
来源：http://dali.meibo888.top/Article/details/gttahcpptu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tanke756.top/Article/details/gteujbavuz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nanxuanxn.top/Article/details/gtitwkgbcm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nanxinkj.top/Article/details/gthmemmhqz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.mhx1999.top/Article/details/gtfrpsbxdh.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtrxstuhjk.html

N. 数据结构与算法
来源：http://dali.sysykeji.top/Article/details/gtidxsdtpn.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtbowgnyhz.html

[N01] 二分查找（有序数组）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpakymppw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtiahoeqyj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhixingplan.top/Article/details/gtluvmktre.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258888.top/Article/details/gtpjyokwvl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gtgzlrsjpp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gthrgwacih.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yuxming.cn/Article/details/gttkkfxicu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nwbrower.top/Article/details/gtxdrfcvhv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj20258.top/Article/details/gtzutnbwjd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jiagoushi.top/Article/details/gtwldxcmll.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pycfn.com/Article/details/gtjpimzvug.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yvedp.cn/Article/details/gtifudjfdy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.birdmap.top/Article/details/gtzcvqrxrg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.smart0.xyz/Article/details/gttcbkbsli.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sysykeji.top/Article/details/gttrlrbhkq.html

Go:   slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvmcrpxd.html

Ruby: arr.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtilvlrrli.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jlsjyb.cn/Article/details/gtfbqnjzmy.html

[N03] 快速排序（分治示例）
来源：http://dali.yangfankeji.com/Article/details/gtlnbmhhuy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shuidangran.top/Article/details/gtwwthoaph.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ydzc1.top/Article/details/gtgghvemdv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yangfankeji.com/Article/details/gtaysinenc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangshuangyany.cn/Article/details/gtnldinjlb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hongshengwenyu.top/Article/details/gthmuuugiw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenzaomai.com/Article/details/gtibarslmv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ivvv.top/Article/details/gtlxpcbqph.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shuidangran.top/Article/details/gtviclddes.html

[N04] 斐波那契数列
来源：http://dali.yj20258.top/Article/details/gtxxpnypir.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gtcxlmslfl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.havefunace.top/Article/details/gtbigeeycf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cqqwz.cn/Article/details/gtdoptafdo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gtyzvzmswz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gtpixqsflm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ybcxt.top/Article/details/gtcglwupdv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gtefjxoqre.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtnrqoovpn.html

[N05] 最大公约数
来源：http://dali.iojbl.cn/Article/details/gtuheitsya.html

Py:   math.gcd(a, b)
来源：http://dali.hfpthk.cn/Article/details/gtrorplwhv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gogol.net.cn/Article/details/gtvhfpplsf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgufenzy.top/Article/details/gtssyrewev.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtubyvqdzw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.kuanghao11.cn/Article/details/gtnctvtwsw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sufxvd.cn/Article/details/gtonpinbpv.html

Ruby: a.gcd(b)
来源：http://dali.sxryk.cn/Article/details/gtndzmazcr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jyoumei.cn/Article/details/gtfvzhogpa.html

[N06] 判断回文字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtdowaakpe.html

Py:   s == s[::-1]
来源：http://dali.jiagoushi.top/Article/details/gtqbirddac.html

PHP:  $s === strrev($s);
来源：http://dali.hnxiangtu.top/Article/details/gtogakiipw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtdfquhiqn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtelwoytky.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.fzhhl.top/Article/details/gtqywyjnzp.html

Go:   // 双指针从两端比较
来源：http://dali.yj202588.top/Article/details/gtxjugirod.html

Ruby: s == s.reverse
来源：http://dali.ehwqpu.com/Article/details/gtdrupannp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cqqwz.cn/Article/details/gteqmlqaiq.html

[N07] 两数之和（返回下标）
来源：http://dali.zhongyouzk.top/Article/details/gtbyrwxxfm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xuetiantiany.cn/Article/details/gtfleshbod.html


<!-- 参考信息 -->