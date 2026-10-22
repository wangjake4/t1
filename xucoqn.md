代发 wailian999

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yongpay.top/Article/details/gtttxfatcf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guannengcc.top/Article/details/gtrnriannh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jyoumei.cn/Article/details/gtgzvuetix.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shzxlz.cn/Article/details/gtnrigfswa.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yangfankeji.com/Article/details/gtocpnvgop.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pengpengdd.cyou/Article/details/gtruvgkjct.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrcldwkr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gzhubu.top/Article/details/gtwywaqobk.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtajkgcxvl.html

K. JSON 与序列化
来源：http://dali.ppjwa.cn/Article/details/gtoymatdfu.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtpztwcxat.html

[K01] 对象转 JSON 字符串
来源：http://dali.zdqjudy.top/Article/details/gtxbeqjezi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zycfv.cn/Article/details/gtuxgxqpyc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigfzy.top/Article/details/gtdxxumnjd.html

JS:   JSON.stringify(obj)
来源：http://dali.yongpay.top/Article/details/gteldzigub.html

TS:   JSON.stringify(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gterjdhpsi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.iojbl.cn/Article/details/gtspvrfosf.html

Go:   json.Marshal(obj)
来源：http://dali.c1oappe.top/Article/details/gttivzyzyb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuagjpzll.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtvvenxdrv.html

[K02] JSON 字符串转对象
来源：http://dali.tanke756.top/Article/details/gtfoceqswm.html

Py:   json.loads(s)
来源：http://dali.meibo888.top/Article/details/gtwlcgvpmj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.iojbl.cn/Article/details/gtkhancrcj.html

JS:   JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gtemncoibg.html

TS:   JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexwognmc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.c1oappe.top/Article/details/gtbxvjfcid.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gtdiisrizc.html

Ruby: JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gtqrtcwsjo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sweek.top/Article/details/gtayujjhhv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zycfv.cn/Article/details/gtwzcrjibs.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dianchejie.cn/Article/details/gtulvxktqb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj202588.top/Article/details/gtfcgzlpjq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tanke756.top/Article/details/gtqazixlwi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.dianchejie.cn/Article/details/gttzuchzbf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yueranfly.top/Article/details/gtzmkmdswz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yangfankeji.com/Article/details/gthlwamxww.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtumvijcas.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.dianchejie.cn/Article/details/gtfqmoeipy.html

[K04] 读取 JSON 文件
来源：http://dali.meibo888.top/Article/details/gtqrvtvidu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenzaomai.com/Article/details/gtkmhvjeeg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yuanzhike.top/Article/details/gtragdyhux.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cdnleiting.top/Article/details/gtbipbxcjy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgufenzy.top/Article/details/gtzdmsvktp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xziqi.cn/Article/details/gtrmnbvpep.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhongyouzk.top/Article/details/gtjygkstdf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cucudq.cn/Article/details/gtwtejtupk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jqgfzy.top/Article/details/gtczwvyfkq.html

[K05] 深拷贝对象
来源：http://dali.yj202588.top/Article/details/gteowpzfdl.html

Py:   copy.deepcopy(obj)
来源：http://dali.fengsongda.top/Article/details/gtpedrzvgl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.daxiang520.top/Article/details/gtxxghinpj.html

JS:   structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gtokqnijkl.html

TS:   structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gtvhbpaznt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hywenlv.cn/Article/details/gtqoglhnlr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zycfv.cn/Article/details/gtzocjrbjf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj20258.top/Article/details/gtwkpptiiq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xuanzx.com/Article/details/gtijkzdyvv.html

[K06] 解析 URL 查询串
来源：http://dali.jqgfzy.top/Article/details/gtsgddwlqz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jianghu66.top/Article/details/gthxkrpwoy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shuidangran.top/Article/details/gtuqzhqbrh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gtiexhspvt.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gtizotwreg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jianghu66.top/Article/details/gtjlkimzdk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gtvnpkiebb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gtctztesxz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gtnsibtawa.html

[K07] 进制转换
来源：http://dali.kuanghao11.cn/Article/details/gtxpdrhgcc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtezobndqr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhoulong.xyz/Article/details/gtcjnqcwqa.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtiqdcpilj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtvythqbfq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtmkrybjux.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yvedp.cn/Article/details/gtaibiatjw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yonumen.top/Article/details/gtkrvewjed.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtjgkjsymo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tanke756.top/Article/details/gtiewtjouk.html

Py:   pickle.dumps(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtkfgnamhf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.aizwys.cn/Article/details/gtflzbbybe.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xylfe.cn/Article/details/gtdmgbmquj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cdnleiting.top/Article/details/gttvupmotr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinqigfzy.top/Article/details/gtjbprdniy.html

Go:   encoding/gob
来源：http://dali.cheryme.top/Article/details/gtbdsiaqcn.html

Ruby: Marshal.dump(obj)
来源：http://dali.guannengcc.top/Article/details/gtocckfhof.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj20258.top/Article/details/gthdwdhzfq.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtgcdapjhq.html

L. 网络请求
来源：http://dali.snrcjt.cn/Article/details/gthavpxrcr.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtlatadxap.html

[L01] 发送 GET 请求
来源：http://dali.haohaochexian.top/Article/details/gtukrlvqzc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sufxvd.cn/Article/details/gtrvswtghw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.wangdashe.top/Article/details/gtbghqjcbn.html

JS:   await fetch(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlpjvvukr.html

TS:   await fetch(url)
来源：http://dali.ydzc1.top/Article/details/gtyevmcbdm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.guowangkeji.top/Article/details/gtwwfjjrfr.html

Go:   resp, err := http.Get(url)
来源：http://dali.jiagoushi.top/Article/details/gtzgpbglgj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.wangdashe.top/Article/details/gtieunlwxj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sufxvd.cn/Article/details/gtmnydaeyj.html

[L02] 发送 POST JSON
来源：http://dali.ydzc1.top/Article/details/gtagditnwt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gtnqxfvdct.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nanxinkj.top/Article/details/gtkuccrjte.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gtegnasedk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gthsaabsoj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhongyouzk.top/Article/details/gtqnqwrcbi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigfzy.top/Article/details/gtdakylpyf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.mhx1999.top/Article/details/gttyoizaps.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ybcxt.top/Article/details/gtjxmviujr.html

[L03] 设置自定义请求头
来源：http://dali.zdqjudy.top/Article/details/gtwlqvkvac.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yuxming.cn/Article/details/gthnzrvjsr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.c1oappe.top/Article/details/gtfymffljq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gtrfchfgpv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hongshengwenyu.top/Article/details/gtveszwffj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gaohongyu789.top/Article/details/gtyosqijjk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zdqjudy.top/Article/details/gtffsdvkku.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yangfankeji.com/Article/details/gtvmlmwxgv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.fzhhl.top/Article/details/gtfbrrzecy.html

[L04] 设置超时
来源：http://dali.9152youxi.cn/Article/details/gtaphkdbeh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhoulong.xyz/Article/details/gtqeerdeor.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.meibo888.top/Article/details/gtuzdupcpq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zycfv.cn/Article/details/gthajnumqr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.smart0.xyz/Article/details/gtcpbqypna.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj20258.top/Article/details/gtmawsxmyi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shuidangran.top/Article/details/gttyroitmi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shangyingyoupin.top/Article/details/gtazxxmbbs.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqgbyauo.html

[L05] 上传文件（multipart）
来源：http://dali.smart0.xyz/Article/details/gtmtveamly.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenlongwang.top/Article/details/gtjtblkmuh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xuanzx.com/Article/details/gttrouhmlt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gtehyprhre.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gtuckaajvq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shzxlz.cn/Article/details/gtdnpfsnxq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xinyue.icu/Article/details/gtrztypjmv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hammf.cn/Article/details/gtujypsply.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xziqi.cn/Article/details/gtoxmqoldf.html

[L06] 解析响应为 JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtqqaytibr.html

Py:   resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gtyorurfhi.html

PHP:  json_decode($body, true);
来源：http://dali.yvedp.cn/Article/details/gtdxwzkcjc.html

JS:   await resp.json()
来源：http://dali.yueranfly.top/Article/details/gtrrxsascf.html

TS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gtrxmetjxa.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yongpay.top/Article/details/gtwggglpoa.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sysykeji.top/Article/details/gtcamftono.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sysykeji.top/Article/details/gtltmpbhon.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj202588.top/Article/details/gtiqpisssc.html

[L07] 处理 HTTP 状态码
来源：http://dali.cdnleiting.top/Article/details/gtqftczkhl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.snrcjt.cn/Article/details/gtzqhlyyrg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.0kj1m.cn/Article/details/gtekaicaaa.html

JS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gtiajdamdr.html

TS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gtdfapxbsi.html

Java: resp.statusCode()
来源：http://dali.zhongyouzk.top/Article/details/gtuwuajpsg.html

Go:   resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gtsqydbhpd.html

Ruby: resp.code.to_i
来源：http://dali.nanxuanxn.top/Article/details/gtnjcbkecb.html

C#:   (int)resp.StatusCode
来源：http://dali.yj202588.top/Article/details/gtwrrrtxkt.html

[L08] 并发请求多个地址
来源：http://dali.dashuyun.cn/Article/details/gtgyfwtadr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gtjftfgknv.html

PHP:  curl_multi_init() 系列
来源：http://dali.svipenyu.cn/Article/details/gtaujdwyfi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.redwolf501.top/Article/details/gtjphivoox.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gtfmrgvdii.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fzhhl.top/Article/details/gtfzrijgpx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.9152youxi.cn/Article/details/gtzpbvubkv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shzxlz.cn/Article/details/gtsvyvnrvw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ppjwa.cn/Article/details/gtzyntmwgw.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gthnomnktj.html

M. 命令行 / 进程 / 环境
来源：http://dali.cucudq.cn/Article/details/gtrkvfunzh.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtsfvascxg.html

[M01] 读取命令行参数
来源：http://dali.gotoacloud.top/Article/details/gtqvxlvglr.html

Py:   sys.argv[1:]
来源：http://dali.meibo888.top/Article/details/gtxbmmogta.html

PHP:  $argv;  $argc;
来源：http://dali.sweek.top/Article/details/gtgvecvmxy.html

JS:   process.argv.slice(2)
来源：http://dali.smart0.xyz/Article/details/gthrdspltc.html

TS:   process.argv.slice(2)
来源：http://dali.sufxvd.cn/Article/details/gtoicpdivk.html

Java: args 数组（main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gtqyxgvypi.html

Go:   os.Args[1:]
来源：http://dali.chenzaomai.com/Article/details/gtxvzkpfzp.html

Ruby: ARGV
来源：http://dali.316326.xyz/Article/details/gtkyxsdpwe.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258.top/Article/details/gtmeyzmute.html

[M02] 读取环境变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtatedozvj.html

Py:   os.environ.get("HOME")
来源：http://dali.dianchejie.cn/Article/details/gthvirfrcr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gtjuizyjnk.html

JS:   process.env.HOME
来源：http://dali.jqgufenzy.top/Article/details/gtdhfitktc.html

TS:   process.env.HOME
来源：http://dali.tian-w.cn/Article/details/gtscvhiebp.html

Java: System.getenv("HOME")
来源：http://dali.jianghu66.top/Article/details/gtraprlvan.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sweek.top/Article/details/gtcwtkyvxh.html

Ruby: ENV["HOME"]
来源：http://dali.cucudq.cn/Article/details/gtqawhfxca.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj202588.top/Article/details/gtyaiihqtm.html

[M03] 执行外部命令
来源：http://dali.gotoacloud.top/Article/details/gtnxbdfdez.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guannengcc.top/Article/details/gtzgvputcp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sysykeji.top/Article/details/gtoimbjnxn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gtvwmxyfgo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtkpwtqfzp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.9152youxi.cn/Article/details/gtrqsnibno.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.mhx1999.top/Article/details/gtebjqogxy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhongyouzk.top/Article/details/gtophsfzdz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.smart0.xyz/Article/details/gtciwghinw.html

[M04] 获取当前工作目录
来源：http://dali.c1oappe.top/Article/details/gtkvvnzxad.html

Py:   os.getcwd()
来源：http://dali.xuanzx.com/Article/details/gtfsbzurza.html

PHP:  getcwd();
来源：http://dali.jlsjyb.cn/Article/details/gtnejskjea.html

JS:   process.cwd()
来源：http://dali.cucudq.cn/Article/details/gtjjnpmuxs.html

TS:   process.cwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfswmdne.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yonumen.top/Article/details/gtkeperilh.html

Go:   os.Getwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtejocuegn.html

Ruby: Dir.pwd
来源：http://dali.jinqigfzy.top/Article/details/gtogtbxosq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cucudq.cn/Article/details/gtxayrdkcj.html

[M05] 设置退出码
来源：http://dali.gaohongyu789.top/Article/details/gtgvlbsuyy.html

Py:   sys.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtlyxlnvea.html

PHP:  exit(1);
来源：http://dali.ydzc1.top/Article/details/gtbynurhuj.html

JS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtwqdvackh.html

TS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gtksnozwol.html

Java: System.exit(1)
来源：http://dali.zycfv.cn/Article/details/gttwstuowt.html

Go:   os.Exit(1)
来源：http://dali.tian-w.cn/Article/details/gtgermxozl.html

Ruby: exit 1
来源：http://dali.jianghu66.top/Article/details/gtkdofezsi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xylfe.cn/Article/details/gtujgafouo.html

[M06] 向标准错误输出
来源：http://dali.fzhhl.top/Article/details/gtxpffoelm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tanke756.top/Article/details/gtuaxrlxni.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yanxiufei.cn/Article/details/gtocqkliyf.html

JS:   console.error("err")
来源：http://dali.zhixingplan.top/Article/details/gttpwppvgw.html

TS:   console.error("err")
来源：http://dali.sufxvd.cn/Article/details/gtumicgqsl.html

Java: System.err.println("err")
来源：http://dali.wangshuangyany.cn/Article/details/gtxdwakhnm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj20258888.top/Article/details/gtxtezsjyy.html

Ruby: warn "err"
来源：http://dali.nanxuanxn.top/Article/details/gtylodzitk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zdqjudy.top/Article/details/gtfnekpcnq.html

[M07] 判断是否为主入口
来源：http://dali.zhixingplan.top/Article/details/gtkbspavwy.html

Py:   if __name__ == "__main__":
来源：http://dali.sxryk.cn/Article/details/gtppxnipqo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cashguo.top/Article/details/gtxfygizyk.html

JS:   require.main === module
来源：http://dali.tian-w.cn/Article/details/gthmksunhq.html

TS:   require.main === module
来源：http://dali.zycfv.cn/Article/details/gtyhabirfz.html

Java: public static void main(String[] args)
来源：http://dali.hywenlv.cn/Article/details/gtgzpjocxy.html

Go:   func main()
来源：http://dali.gogol.net.cn/Article/details/gtmptzxcqp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tianlin.xyz/Article/details/gtcvtxzqbj.html

C#:   static void Main(string[] args)
来源：http://dali.sufxvd.cn/Article/details/gtdfmhngbg.html

[M08] 获取系统与运行时信息
来源：http://dali.nwbrower.top/Article/details/gtivutketg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hysaishi.cn/Article/details/gtzbwxtiyr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shuidangran.top/Article/details/gtaddcqrnv.html

JS:   process.platform;  process.version
来源：http://dali.shanyushiyangkeji.top/Article/details/gthkyobvrp.html

TS:   process.platform;  process.version
来源：http://dali.xuanzx.com/Article/details/gtxhxuvmtn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.andypj.xyz/Article/details/gtfhdxccem.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aibaodan.cn/Article/details/gtumpffqcv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuxming.cn/Article/details/gtybvkrhex.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cucudq.cn/Article/details/gtdxbpxane.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtdinjidyk.html

N. 数据结构与算法
来源：http://dali.yj20258.top/Article/details/gtynihjuhd.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtfengupzn.html

[N01] 二分查找（有序数组）
来源：http://dali.cqqwz.cn/Article/details/gtefpyetpk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtgfhrzqsu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gtyvzvtuau.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gtfruadvqi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gttiwsfntm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtrntubrrw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtalmvogwg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhengqikj.top/Article/details/gtvnbjspkx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.pycfn.com/Article/details/gtwznarxxp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.316326.xyz/Article/details/gtvkpwetad.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gtxreyitnb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hnqzz.top/Article/details/gtwhginprs.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hysaishi.cn/Article/details/gtcfjbnkwa.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gtbklyuozy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.aizwys.cn/Article/details/gtzdjewzwv.html

Go:   slices.Sort(arr)
来源：http://dali.shzxlz.cn/Article/details/gtqiuktbvt.html

Ruby: arr.sort
来源：http://dali.sxryk.cn/Article/details/gtfdzdbnmx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctcspzfz.html

[N03] 快速排序（分治示例）
来源：http://dali.gogol.net.cn/Article/details/gtiqlldemf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ppjwa.cn/Article/details/gtxrbkkhxj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.wangshuangyany.cn/Article/details/gtjedencoh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hammf.cn/Article/details/gtonmdcuxn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shangyingyoupin.top/Article/details/gthhlteoou.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.svipenyu.cn/Article/details/gtzkgxjkym.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.birdmap.top/Article/details/gtabfciqrs.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shzxlz.cn/Article/details/gtrbwpkojp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nanxuanxn.top/Article/details/gtivlzckpl.html

[N04] 斐波那契数列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtovxfbngr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.haohaochexian.top/Article/details/gtjsyamzav.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cashguo.top/Article/details/gtnypwxjea.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gtrqbtaxgj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sweek.top/Article/details/gtncwlbuui.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenjidiqi.icu/Article/details/gtuuwiplml.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yonumen.top/Article/details/gtdsgoxawe.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.0kj1m.cn/Article/details/gthhvpurab.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gteexytuaz.html

[N05] 最大公约数
来源：http://dali.gaohongyu789.top/Article/details/gtedbmfcyl.html

Py:   math.gcd(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtondsixma.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gzhubu.top/Article/details/gtobquchsu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258.top/Article/details/gthqinofrk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zdqjudy.top/Article/details/gteoabbkhr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhiwuduotai.top/Article/details/gtbocbnawx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.birdmap.top/Article/details/gtqwhzrfqc.html

Ruby: a.gcd(b)
来源：http://dali.316326.xyz/Article/details/gtgdozbwov.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yj20258888.top/Article/details/gtbozzgrdp.html

[N06] 判断回文字符串
来源：http://dali.shuidangran.top/Article/details/gtsqoduptt.html

Py:   s == s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gttcsqzdpy.html

PHP:  $s === strrev($s);
来源：http://dali.yuxming.cn/Article/details/gtsuvpccao.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gtlefmqmad.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gtaocbpluc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.wangdashe.top/Article/details/gtnnygpjph.html

Go:   // 双指针从两端比较
来源：http://dali.0kj1m.cn/Article/details/gtqxfnutjo.html

Ruby: s == s.reverse
来源：http://dali.0kj1m.cn/Article/details/gtpjqvliii.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tanke756.top/Article/details/gtfnfudgfz.html

[N07] 两数之和（返回下标）
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpghcwfw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cqqwz.cn/Article/details/gtwwusbfyi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqtsnoyio.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.meibo888.top/Article/details/gtsjqeoxep.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinghuilouyu.cn/Article/details/gtqcmvdlkc.html

Java: // 手写 HashMap
来源：http://dali.yonumen.top/Article/details/gtkujlsvpp.html

Go:   // 手写 map[int]int
来源：http://dali.sxryk.cn/Article/details/gtrosonxlr.html

Ruby: // 手写 Hash
来源：http://dali.dianchejie.cn/Article/details/gtplxsoagx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhengqikj.top/Article/details/gtlzqepcam.html

[N08] 生成全排列
来源：http://dali.yueranfly.top/Article/details/gtmqgmylph.html


<!-- 参考信息 -->