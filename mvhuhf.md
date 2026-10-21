代发 wailian999

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gotoacloud.top/Article/details/gtnsoylfbp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.316326.xyz/Article/details/gtahrrtaip.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yongpay.top/Article/details/gtldqbpjjl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yueranfly.top/Article/details/gtalmmxiyt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tian-w.cn/Article/details/gtbulquwwv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hfpthk.cn/Article/details/gtyyqufojb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.mhx1999.top/Article/details/gtkbnsaobr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jlsjyb.cn/Article/details/gtvyxpyjqd.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtoeygkhub.html

K. JSON 与序列化
来源：http://dali.jqgufenzy.top/Article/details/gtxxkixxac.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtqtijklbq.html

[K01] 对象转 JSON 字符串
来源：http://dali.svipenyu.cn/Article/details/gtdanghbtj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.dianchejie.cn/Article/details/gteppnywdi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gtfcqudmwd.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtpnqvrknt.html

TS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gtistplknh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.andypj.xyz/Article/details/gtwtrvxjed.html

Go:   json.Marshal(obj)
来源：http://dali.yonumen.top/Article/details/gtattnxlno.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tanke756.top/Article/details/gtqsuywydk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ivvv.top/Article/details/gtxozuxrzx.html

[K02] JSON 字符串转对象
来源：http://dali.sufxvd.cn/Article/details/gtgxfoqjtl.html

Py:   json.loads(s)
来源：http://dali.bjfxy.top/Article/details/gticixjihk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhiwuduotai.top/Article/details/gtemylcgmo.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gtppmmieel.html

TS:   JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gtcnvltlew.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.9152youxi.cn/Article/details/gthpgkudmn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yvedp.cn/Article/details/gtiabbqkro.html

Ruby: JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gtaxhhkcom.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xinyue.icu/Article/details/gtixjwejkp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jyoumei.cn/Article/details/gtrjqmahkf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.havefunace.top/Article/details/gtpictipti.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.daxiang520.top/Article/details/gtjfhmqodt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gtcnvttelx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtkaeubhxi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.svipenyu.cn/Article/details/gtanbnezns.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cashguo.top/Article/details/gtzbvfdnho.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xylfe.cn/Article/details/gtguyrzkyw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yanxiufei.cn/Article/details/gtruwjnnki.html

[K04] 读取 JSON 文件
来源：http://dali.zycfv.cn/Article/details/gtodnjkmhp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenlongwang.top/Article/details/gtrcxlumgt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangshuangyany.cn/Article/details/gtydmymvul.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jlsjyb.cn/Article/details/gtypahyxrj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shangyingyoupin.top/Article/details/gtupkxkwth.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gtkrsuebwi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jianghu66.top/Article/details/gtnvtgtkda.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gaohongyu789.top/Article/details/gtzgnuleal.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gtzzqhxbqt.html

[K05] 深拷贝对象
来源：http://dali.tanke756.top/Article/details/gtohvmughv.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj202588.top/Article/details/gtrdlprced.html

PHP:  unserialize(serialize($obj));
来源：http://dali.haohaochexian.top/Article/details/gtsaeptgfz.html

JS:   structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gtyikhqztx.html

TS:   structuredClone(obj)
来源：http://dali.fengsongda.top/Article/details/gtgazghvuh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.haohaochexian.top/Article/details/gtuevjaiss.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sweek.top/Article/details/gtvvndkhrc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.316326.xyz/Article/details/gtmheuhduo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtysbsusey.html

[K06] 解析 URL 查询串
来源：http://dali.snrcjt.cn/Article/details/gtkkrdhbzm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hnxiangtu.top/Article/details/gtxkmnqsop.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xinyue.icu/Article/details/gtpbzrcciu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtavlglmuy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gtgzbiuoii.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gzhubu.top/Article/details/gtxrfowrrm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gtzjlkyrgy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gtfwxukyos.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gtexelvjvq.html

[K07] 进制转换
来源：http://dali.birdmap.top/Article/details/gtynusmpwv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtqesccuuk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.quarkkingdee.top/Article/details/gtfklyfpiu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtcqggizal.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtmgtmmlpg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gthfvwdoia.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sxryk.cn/Article/details/gtcmhbowki.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daria6918.cn/Article/details/gtxvygcqev.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwppnntfv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hysaishi.cn/Article/details/gtvwcbmhxk.html

Py:   pickle.dumps(obj)
来源：http://dali.0kj1m.cn/Article/details/gtejzqfgrk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.fengsongda.top/Article/details/gteyvodwxe.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shangyingyoupin.top/Article/details/gttcgcugum.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.mhx1999.top/Article/details/gttfrnrjok.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ppjwa.cn/Article/details/gtdingowev.html

Go:   encoding/gob
来源：http://dali.dashuyun.cn/Article/details/gtrcxcuqqo.html

Ruby: Marshal.dump(obj)
来源：http://dali.yvedp.cn/Article/details/gtdtwnymbb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ppjwa.cn/Article/details/gtzdccvzvm.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtwfbvzvam.html

L. 网络请求
来源：http://dali.zhongyouzk.top/Article/details/gtoavwalim.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtdkdxbwjm.html

[L01] 发送 GET 请求
来源：http://dali.guannengcc.top/Article/details/gtqfxhbgna.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.andypj.xyz/Article/details/gtxbpjbsdr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnqzz.top/Article/details/gtuyvmkmgl.html

JS:   await fetch(url)
来源：http://dali.gaohongyu789.top/Article/details/gtfwhcoldi.html

TS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gtnawexnmo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tianlin.xyz/Article/details/gtxuaglxtq.html

Go:   resp, err := http.Get(url)
来源：http://dali.sysykeji.top/Article/details/gtdgagvkrq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xinyue.icu/Article/details/gtcpkpcwkg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.quarkkingdee.top/Article/details/gtsavghoda.html

[L02] 发送 POST JSON
来源：http://dali.zhengqikj.top/Article/details/gtjguxbxsu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jlsjyb.cn/Article/details/gtbffzvife.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yanxiufei.cn/Article/details/gtalqkkfob.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gtnfsadwpl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gogol.net.cn/Article/details/gtnddggvma.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.fzhhl.top/Article/details/gtqsfqmapt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.wangdashe.top/Article/details/gtkqfnirok.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgfzy.top/Article/details/gtopvledve.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ehwqpu.com/Article/details/gtqrqdgogp.html

[L03] 设置自定义请求头
来源：http://dali.cucudq.cn/Article/details/gteabqfpaz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.birdmap.top/Article/details/gthuibfdhh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.guowangkeji.top/Article/details/gteulyfjnu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gtmtidxbso.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.iojbl.cn/Article/details/gtpsdofazt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.bjfxy.top/Article/details/gttkgcxxqh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tanke756.top/Article/details/gtrkjzhwdf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hongshengwenyu.top/Article/details/gtobccniqy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yongpay.top/Article/details/gtautgdhfg.html

[L04] 设置超时
来源：http://dali.bjfxy.top/Article/details/gtustqrmie.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yanxiufei.cn/Article/details/gthoqeensp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.feifeiyinyue.top/Article/details/gtrjeseojt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hammf.cn/Article/details/gtascvhpdg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tian-w.cn/Article/details/gtlrnknyyk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.wangshuangyany.cn/Article/details/gtgcxchsew.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.haohaochexian.top/Article/details/gtvntncrxd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ivvv.top/Article/details/gtduivtdst.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthenumakp.html

[L05] 上传文件（multipart）
来源：http://dali.ivvv.top/Article/details/gtpmmzqmzd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cqqwz.cn/Article/details/gtpgwdoipw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtixekakhe.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gtkotjlxdd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gtrdzngjzz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.fzhhl.top/Article/details/gtqqbzcvdz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cdnleiting.top/Article/details/gthjiovdki.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinghuilouyu.cn/Article/details/gtveutlasg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtfdtjifxt.html

[L06] 解析响应为 JSON
来源：http://dali.tianlin.xyz/Article/details/gtusddnrue.html

Py:   resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gtmmsbqqaz.html

PHP:  json_decode($body, true);
来源：http://dali.xuetiantiany.cn/Article/details/gtetwcimsk.html

JS:   await resp.json()
来源：http://dali.dashuyun.cn/Article/details/gtvvtudist.html

TS:   await resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gtdzlsyhpa.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.dianchejie.cn/Article/details/gtyqrbpenc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.wangdashe.top/Article/details/gtwchciczo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.snrcjt.cn/Article/details/gtlaqrxnfs.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfhojtoqr.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtokcaaljz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.316326.xyz/Article/details/gtccatbmxa.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtbqsglyek.html

JS:   resp.ok;  resp.status
来源：http://dali.tian-w.cn/Article/details/gtpxhmqgig.html

TS:   resp.ok;  resp.status
来源：http://dali.9152youxi.cn/Article/details/gtjkrunuvm.html

Java: resp.statusCode()
来源：http://dali.aizwys.cn/Article/details/gtfxzkolvy.html

Go:   resp.StatusCode
来源：http://dali.zycfv.cn/Article/details/gtnltsjpae.html

Ruby: resp.code.to_i
来源：http://dali.cheryme.top/Article/details/gtxpjxuiry.html

C#:   (int)resp.StatusCode
来源：http://dali.yanxiufei.cn/Article/details/gtgzokhhhe.html

[L08] 并发请求多个地址
来源：http://dali.redwolf501.top/Article/details/gtnxuzyylg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hongshengwenyu.top/Article/details/gthgmiijxy.html

PHP:  curl_multi_init() 系列
来源：http://dali.tianlin.xyz/Article/details/gtlmwveftx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daria6918.cn/Article/details/gtgqonxjhz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gtwihzumjf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.birdmap.top/Article/details/gteyvavkfw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cashguo.top/Article/details/gtfzemelcs.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yueranfly.top/Article/details/gtxflscypd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hysaishi.cn/Article/details/gtoraawzag.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtihpsnwpn.html

M. 命令行 / 进程 / 环境
来源：http://dali.hongshengwenyu.top/Article/details/gtgjzulokr.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtjvxeggrf.html

[M01] 读取命令行参数
来源：http://dali.hammf.cn/Article/details/gtqaewrucv.html

Py:   sys.argv[1:]
来源：http://dali.nanxuanxn.top/Article/details/gtypmreifz.html

PHP:  $argv;  $argc;
来源：http://dali.yj20258888.top/Article/details/gtdlptavit.html

JS:   process.argv.slice(2)
来源：http://dali.zhiwuduotai.top/Article/details/gtjtikvhke.html

TS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gtvdehwnjk.html

Java: args 数组（main 方法参数）
来源：http://dali.yongpay.top/Article/details/gtodwbqmuc.html

Go:   os.Args[1:]
来源：http://dali.yj202588.top/Article/details/gtwjqsmvlj.html

Ruby: ARGV
来源：http://dali.jqgfzy.top/Article/details/gtejwloqjj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yvedp.cn/Article/details/gtkloldyur.html

[M02] 读取环境变量
来源：http://dali.birdmap.top/Article/details/gtqqwtfumf.html

Py:   os.environ.get("HOME")
来源：http://dali.daxiang520.top/Article/details/gtdhfvpsls.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gtwiqtnkjj.html

JS:   process.env.HOME
来源：http://dali.yuxming.cn/Article/details/gtcdxokgma.html

TS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gtrgdjfkvx.html

Java: System.getenv("HOME")
来源：http://dali.hammf.cn/Article/details/gthudttwlz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tian-w.cn/Article/details/gtqsihdnew.html

Ruby: ENV["HOME"]
来源：http://dali.ehwqpu.com/Article/details/gtultbaquw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxyyjrfxd.html

[M03] 执行外部命令
来源：http://dali.xuanzx.com/Article/details/gtrmdpjkct.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gtlzgbcrds.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shanyushiyangtech.top/Article/details/gtppmxchyc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jlsjyb.cn/Article/details/gtkawdjizy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.0kj1m.cn/Article/details/gtfapdcjug.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sufxvd.cn/Article/details/gtjebgemto.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhiwuduotai.top/Article/details/gtebsdreuk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hysaishi.cn/Article/details/gtujxnysmn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.feifeiyinyue.top/Article/details/gteapudeht.html

[M04] 获取当前工作目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypqyurss.html

Py:   os.getcwd()
来源：http://dali.sxryk.cn/Article/details/gtkirukfyx.html

PHP:  getcwd();
来源：http://dali.svipenyu.cn/Article/details/gtstyolnio.html

JS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtapbjoukm.html

TS:   process.cwd()
来源：http://dali.quarkkingdee.top/Article/details/gtebflkmmj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.bjfxy.top/Article/details/gtcrerwscl.html

Go:   os.Getwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtsixoeinb.html

Ruby: Dir.pwd
来源：http://dali.hammf.cn/Article/details/gtfwvhcrvl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pengpengdd.cyou/Article/details/gtviocxkap.html

[M05] 设置退出码
来源：http://dali.cdnleiting.top/Article/details/gtebyyxstq.html

Py:   sys.exit(1)
来源：http://dali.hnqzz.top/Article/details/gtrxdvztad.html

PHP:  exit(1);
来源：http://dali.andypj.xyz/Article/details/gtmotwliec.html

JS:   process.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtsaarnukh.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtwgvaijjn.html

Java: System.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gteetrumvk.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtzhxdsjyw.html

Ruby: exit 1
来源：http://dali.zhengqikj.top/Article/details/gtjqsfklpg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fzhhl.top/Article/details/gtrghzeybd.html

[M06] 向标准错误输出
来源：http://dali.guannengcc.top/Article/details/gtcqfvbtnq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ybcxt.top/Article/details/gtrdnicjat.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.smart0.xyz/Article/details/gtdjvjalnh.html

JS:   console.error("err")
来源：http://dali.bjfxy.top/Article/details/gttuhqvewi.html

TS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gtjbwfclgn.html

Java: System.err.println("err")
来源：http://dali.cheryme.top/Article/details/gtzpcirksi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ybcxt.top/Article/details/gtsoiikafd.html

Ruby: warn "err"
来源：http://dali.yangfankeji.com/Article/details/gtgfxgcoki.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.daria6918.cn/Article/details/gtwdhaewxw.html

[M07] 判断是否为主入口
来源：http://dali.quarkkingdee.top/Article/details/gtnkmllowt.html

Py:   if __name__ == "__main__":
来源：http://dali.vqdsnc.cn/Article/details/gtcgdvpmff.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdaarcjf.html

JS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gtnolfjhmy.html

TS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gtepxddnjl.html

Java: public static void main(String[] args)
来源：http://dali.ydzc1.top/Article/details/gtydjscahb.html

Go:   func main()
来源：http://dali.hysaishi.cn/Article/details/gtfhaohxtc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sxryk.cn/Article/details/gtohsqnfxr.html

C#:   static void Main(string[] args)
来源：http://dali.shzxlz.cn/Article/details/gtyqxnchxi.html

[M08] 获取系统与运行时信息
来源：http://dali.gogol.net.cn/Article/details/gttpacnuti.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tanke756.top/Article/details/gtyidkoiys.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tanke756.top/Article/details/gtksfwyghp.html

JS:   process.platform;  process.version
来源：http://dali.sufxvd.cn/Article/details/gtqdwnyneq.html

TS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gtsvbzrvwt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.pycfn.com/Article/details/gtvwsvuqpj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.andypj.xyz/Article/details/gtoxppjmmy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.guannengcc.top/Article/details/gtxsbkrdge.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.redwolf501.top/Article/details/gtekpybxjl.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtaziyvosy.html

N. 数据结构与算法
来源：http://dali.xinyue.icu/Article/details/gtzdvqnmjf.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtzulkgzqo.html

[N01] 二分查找（有序数组）
来源：http://dali.fzhhl.top/Article/details/gtxgcqrqhk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtykvqpzqb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj202588.top/Article/details/gtapxakcin.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gotoacloud.top/Article/details/gtikiwbcyt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangdashe.top/Article/details/gtpskoddcr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtyfuigrsk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtkmlmghsc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.feifeiyinyue.top/Article/details/gtxhrwlgzi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtedmcrpyk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigufen.top/Article/details/gttqiyupwz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.9152youxi.cn/Article/details/gtitezzxhz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hammf.cn/Article/details/gthejvysjr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gtlcdtraxn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gtsucwlhmu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.tian-w.cn/Article/details/gtiyuhhlgq.html

Go:   slices.Sort(arr)
来源：http://dali.sysykeji.top/Article/details/gtwwfkvdah.html

Ruby: arr.sort
来源：http://dali.shzxlz.cn/Article/details/gttpitzgsq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nanxuanxn.top/Article/details/gtfqvsxnyj.html

[N03] 快速排序（分治示例）
来源：http://dali.yuanzhike.top/Article/details/gtzbdmucss.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrvmxfgu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.pycfn.com/Article/details/gtwmoileeg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhengqikj.top/Article/details/gthojexsnm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhiwuduotai.top/Article/details/gthhthmktg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nwbrower.top/Article/details/gtxgfxjcgd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xuanzx.com/Article/details/gtczsaarko.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.birdmap.top/Article/details/gtxrylzxcp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.bjfxy.top/Article/details/gteqbyxbtk.html

[N04] 斐波那契数列
来源：http://dali.vqdsnc.cn/Article/details/gttmzurccu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yuxming.cn/Article/details/gtiswhdhna.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.fengsongda.top/Article/details/gtkopxfpqa.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgufenzy.top/Article/details/gtlfakagqz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtplpuyfxq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hfpthk.cn/Article/details/gtocwqduqm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.fzhhl.top/Article/details/gtwzjytdqr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.haohaochexian.top/Article/details/gtendkbjib.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gtzzertdzb.html

[N05] 最大公约数
来源：http://dali.tianlin.xyz/Article/details/gtmqwtaynd.html

Py:   math.gcd(a, b)
来源：http://dali.jyoumei.cn/Article/details/gtzpyrmwxl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tian-w.cn/Article/details/gtghiabbuq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dashuyun.cn/Article/details/gtfwkfmuee.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuxming.cn/Article/details/gtqujqgeqa.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yangfankeji.com/Article/details/gtkejvcvfh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.c1oappe.top/Article/details/gtzhacggrw.html

Ruby: a.gcd(b)
来源：http://dali.jlsjyb.cn/Article/details/gtzscvicxu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.0kj1m.cn/Article/details/gtzjtgyrqv.html

[N06] 判断回文字符串
来源：http://dali.smart0.xyz/Article/details/gtxfrmtcql.html

Py:   s == s[::-1]
来源：http://dali.zhongyouzk.top/Article/details/gtpoottyxi.html

PHP:  $s === strrev($s);
来源：http://dali.ydzc1.top/Article/details/gtdnhxhttq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtgvtnglab.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnzfgifut.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hfpthk.cn/Article/details/gtwuduioeq.html

Go:   // 双指针从两端比较
来源：http://dali.havefunace.top/Article/details/gtbresszhk.html

Ruby: s == s.reverse
来源：http://dali.yongpay.top/Article/details/gtulswgkan.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tian-w.cn/Article/details/gtzxjcvzdh.html

[N07] 两数之和（返回下标）
来源：http://dali.dashuyun.cn/Article/details/gtbwvosbqn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cucudq.cn/Article/details/gtaxdipysq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nanxinkj.top/Article/details/gtqrujjbpt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.meibo888.top/Article/details/gtcnmwpere.html

TS:   // 手写 Map<string, number>
来源：http://dali.jiagoushi.top/Article/details/gtdpohrtcl.html

Java: // 手写 HashMap
来源：http://dali.kuanghao11.cn/Article/details/gtgydztqkn.html

Go:   // 手写 map[int]int
来源：http://dali.yuanzhike.top/Article/details/gttxxzykfg.html

Ruby: // 手写 Hash
来源：http://dali.tian-w.cn/Article/details/gthdeaunsu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cashguo.top/Article/details/gtreyxpkpb.html

[N08] 生成全排列
来源：http://dali.gzhubu.top/Article/details/gtoengdpzk.html


<!-- 参考信息 -->