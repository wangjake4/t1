代发 wailian999

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.daxiang520.top/Article/details/gtlijhpigh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.snrcjt.cn/Article/details/gtpltewypu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.9152youxi.cn/Article/details/gtbmsncslv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sweek.top/Article/details/gtwprboawm.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtisykuabz.html

K. JSON 与序列化
来源：http://dali.jqgufenzy.top/Article/details/gtqbgnnkpq.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtocufplnb.html

[K01] 对象转 JSON 字符串
来源：http://dali.zdqjudy.top/Article/details/gtbqlgnift.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gtufndcjhl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.quarkkingdee.top/Article/details/gtoidgddqs.html

JS:   JSON.stringify(obj)
来源：http://dali.c1oappe.top/Article/details/gtowzvaaek.html

TS:   JSON.stringify(obj)
来源：http://dali.pycfn.com/Article/details/gthmsnzhnn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.vqdsnc.cn/Article/details/gthiijvnrh.html

Go:   json.Marshal(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbximzjz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hysaishi.cn/Article/details/gtearpqomd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zycfv.cn/Article/details/gtoakwocsk.html

[K02] JSON 字符串转对象
来源：http://dali.haohaochexian.top/Article/details/gtfrnotpsx.html

Py:   json.loads(s)
来源：http://dali.c1oappe.top/Article/details/gtfjtfhsyl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yueranfly.top/Article/details/gtiyhuphyt.html

JS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhdsnite.html

TS:   JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gthmdqpewd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hywenlv.cn/Article/details/gtucryxhbu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gtrqfnaycw.html

Ruby: JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gtzierfiwb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shangyingyoupin.top/Article/details/gttbtzjydz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhongyouzk.top/Article/details/gtuambetam.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dashuyun.cn/Article/details/gtmojthbkn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gaohongyu789.top/Article/details/gtuhpxisme.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsozrezzf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxfymqqt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.smart0.xyz/Article/details/gtvmrcirbn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.havefunace.top/Article/details/gttzlflcqa.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtyfxrtrvx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.daria6918.cn/Article/details/gtappxakce.html

[K04] 读取 JSON 文件
来源：http://dali.hnxiangtu.top/Article/details/gtwfvhomhi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.aizwys.cn/Article/details/gttkswvfkx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yvedp.cn/Article/details/gtusohidke.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.andypj.xyz/Article/details/gtsnaxwock.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gtwojvysxb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shuidangran.top/Article/details/gtibnmtbpp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nanxinkj.top/Article/details/gtvrnzihlf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.guannengcc.top/Article/details/gtgyuchasu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ppjwa.cn/Article/details/gtjkoosevp.html

[K05] 深拷贝对象
来源：http://dali.shuidangran.top/Article/details/gtskiutqtd.html

Py:   copy.deepcopy(obj)
来源：http://dali.shzxlz.cn/Article/details/gttefiyrht.html

PHP:  unserialize(serialize($obj));
来源：http://dali.aibaodan.cn/Article/details/gtakqeqsvq.html

JS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gtumbernjn.html

TS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gtoxurtnbv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.guowangkeji.top/Article/details/gtvufwonbq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tian-w.cn/Article/details/gtycgunxhd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yanxiufei.cn/Article/details/gtxtfksczv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shuidangran.top/Article/details/gthcjekstq.html

[K06] 解析 URL 查询串
来源：http://dali.kuanghao11.cn/Article/details/gtjgwivkvi.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zdqjudy.top/Article/details/gtxkxupcgt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xuetiantiany.cn/Article/details/gtfbqknwwi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.0kj1m.cn/Article/details/gtrvgtdtpb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenzaomai.com/Article/details/gtkskkgmac.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangdashe.top/Article/details/gtcvyhrjkk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gtkmxsnxoj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gtadxuefhn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gtbktpphfe.html

[K07] 进制转换
来源：http://dali.jinqigfzy.top/Article/details/gtwnpmvhfw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtmfhpapdj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yueranfly.top/Article/details/gtrptdyxna.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtomvlkjum.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtxodobmku.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtcwwcfwcg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.fzhhl.top/Article/details/gtektzxtvw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.havefunace.top/Article/details/gtotfpwbyp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtrvqurjjy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.smart0.xyz/Article/details/gtxdxivtjd.html

Py:   pickle.dumps(obj)
来源：http://dali.aibaodan.cn/Article/details/gtapazdrdx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj202588.top/Article/details/gtpxuyvfvd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cqqwz.cn/Article/details/gtvcztsfop.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xuetiantiany.cn/Article/details/gtpecixvgm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuanzx.com/Article/details/gtoxlgugew.html

Go:   encoding/gob
来源：http://dali.chenlongwang.top/Article/details/gtsecgghhg.html

Ruby: Marshal.dump(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtxenvpbzc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gtsjpyphma.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtxewelvbg.html

L. 网络请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxdqfdsg.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtctmvakwj.html

[L01] 发送 GET 请求
来源：http://dali.kuanghao11.cn/Article/details/gtccbodwqv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj20258.top/Article/details/gtqvoonuma.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sxryk.cn/Article/details/gtejvnmlpf.html

JS:   await fetch(url)
来源：http://dali.andypj.xyz/Article/details/gtjnmulkus.html

TS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gtdiwamhfr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zycfv.cn/Article/details/gtacygrvyo.html

Go:   resp, err := http.Get(url)
来源：http://dali.guowangkeji.top/Article/details/gtojrutdfn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hysaishi.cn/Article/details/gtxzgdawhs.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gotoacloud.top/Article/details/gttlmralwu.html

[L02] 发送 POST JSON
来源：http://dali.yvedp.cn/Article/details/gtattzlknt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenlongwang.top/Article/details/gtcfqterhf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gzhubu.top/Article/details/gtbttedzxr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dashuyun.cn/Article/details/gtcuqtguru.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhixingplan.top/Article/details/gtldrsizzq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.bjfxy.top/Article/details/gthhukvjcv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.fzhhl.top/Article/details/gtrmlqjkzk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.fengsongda.top/Article/details/gthroxldnb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhiwuduotai.top/Article/details/gtomezdapl.html

[L03] 设置自定义请求头
来源：http://dali.zycfv.cn/Article/details/gtsdoiuvii.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtziybrlmf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hysaishi.cn/Article/details/gtckfilaqp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dashuyun.cn/Article/details/gthloatszf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tanke756.top/Article/details/gtemhsetrh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.havefunace.top/Article/details/gtgxrfntga.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangtech.top/Article/details/gtayvqcfth.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daria6918.cn/Article/details/gtgqlxjynf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nanxuanxn.top/Article/details/gtotenxiii.html

[L04] 设置超时
来源：http://dali.shangyingyoupin.top/Article/details/gtukzztxeg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yongpay.top/Article/details/gtjnlgrkoi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttqignevm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvuhagvwc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtjiwvgaus.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cucudq.cn/Article/details/gtlluqusmn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xuetiantiany.cn/Article/details/gtcgjnshag.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuanzx.com/Article/details/gtfrcwfbpe.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xziqi.cn/Article/details/gteodprdiw.html

[L05] 上传文件（multipart）
来源：http://dali.tanke756.top/Article/details/gtonalkbbn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhengqikj.top/Article/details/gtnlkumgfh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xuetiantiany.cn/Article/details/gtdfawgfrr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nwbrower.top/Article/details/gtxmlumrss.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ivvv.top/Article/details/gtwpxgptfy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinqigufen.top/Article/details/gtxssiodoo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhongyouzk.top/Article/details/gtrhopeabk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dashuyun.cn/Article/details/gtuxvkvppm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtqzsrevai.html

[L06] 解析响应为 JSON
来源：http://dali.guannengcc.top/Article/details/gtpcxqnism.html

Py:   resp.json()
来源：http://dali.ydzc1.top/Article/details/gtnjsfhiiu.html

PHP:  json_decode($body, true);
来源：http://dali.dashuyun.cn/Article/details/gtirxbisyl.html

JS:   await resp.json()
来源：http://dali.fengsongda.top/Article/details/gtnsupvnzi.html

TS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gtiafvwcrt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gtxvoemdme.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yuxming.cn/Article/details/gtvspymyow.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258.top/Article/details/gtehzrovgo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nwbrower.top/Article/details/gtvaoxlbmm.html

[L07] 处理 HTTP 状态码
来源：http://dali.yueranfly.top/Article/details/gtzskphvbo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.fzhhl.top/Article/details/gtvrpqbcje.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.snrcjt.cn/Article/details/gtqdnyjqja.html

JS:   resp.ok;  resp.status
来源：http://dali.jinghuilouyu.cn/Article/details/gtukucgonr.html

TS:   resp.ok;  resp.status
来源：http://dali.gaohongyu789.top/Article/details/gtrbplkbcv.html

Java: resp.statusCode()
来源：http://dali.hysaishi.cn/Article/details/gtmbfefead.html

Go:   resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gthubkgewb.html

Ruby: resp.code.to_i
来源：http://dali.haohaochexian.top/Article/details/gtpcigsika.html

C#:   (int)resp.StatusCode
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfeydjuip.html

[L08] 并发请求多个地址
来源：http://dali.316326.xyz/Article/details/gtmxgmwslp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yuxming.cn/Article/details/gtnhfjanif.html

PHP:  curl_multi_init() 系列
来源：http://dali.hnqzz.top/Article/details/gthoqwpugc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gtekcogwce.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gtqulgrtph.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhiwuduotai.top/Article/details/gtrzfvrgic.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gotoacloud.top/Article/details/gtwsrdomuy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.havefunace.top/Article/details/gtunuvceyo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenzaomai.com/Article/details/gtracoopdi.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtoidhpbsg.html

M. 命令行 / 进程 / 环境
来源：http://dali.svipenyu.cn/Article/details/gtjjcypqbb.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtdtukkdma.html

[M01] 读取命令行参数
来源：http://dali.jinqigufen.top/Article/details/gtdiknkpay.html

Py:   sys.argv[1:]
来源：http://dali.andypj.xyz/Article/details/gtamzanlcb.html

PHP:  $argv;  $argc;
来源：http://dali.9152youxi.cn/Article/details/gtzbfqgjlf.html

JS:   process.argv.slice(2)
来源：http://dali.sxryk.cn/Article/details/gtltflfaed.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gtbogakzoi.html

Java: args 数组（main 方法参数）
来源：http://dali.tanke756.top/Article/details/gtcgcheaon.html

Go:   os.Args[1:]
来源：http://dali.yj20258888.top/Article/details/gtcdkzknqs.html

Ruby: ARGV
来源：http://dali.hammf.cn/Article/details/gtlydkrwsm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gtylwpkodv.html

[M02] 读取环境变量
来源：http://dali.zhengqikj.top/Article/details/gtupxsjhgq.html

Py:   os.environ.get("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtjqowuxhv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.birdmap.top/Article/details/gtavuiuqty.html

JS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gtsxneqgkm.html

TS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gtejaqjxkb.html

Java: System.getenv("HOME")
来源：http://dali.zdqjudy.top/Article/details/gtigqdqoyi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtqusckcqq.html

Ruby: ENV["HOME"]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtueysnlss.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtoxmuxhyu.html

[M03] 执行外部命令
来源：http://dali.cdnleiting.top/Article/details/gtvgwycnqp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.wangdashe.top/Article/details/gtgkkbxuvw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhoulong.xyz/Article/details/gtgmwadqxt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.smart0.xyz/Article/details/gtcnyrfxkp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.dashuyun.cn/Article/details/gtgcbryxzf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdjdlgjc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.redwolf501.top/Article/details/gtkxgqgqaw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cheryme.top/Article/details/gtogeczucq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jqgfzy.top/Article/details/gthqenifzu.html

[M04] 获取当前工作目录
来源：http://dali.chenjidiqi.icu/Article/details/gtgqqiejac.html

Py:   os.getcwd()
来源：http://dali.shuidangran.top/Article/details/gtqhbcduwx.html

PHP:  getcwd();
来源：http://dali.daria6918.cn/Article/details/gtnbhfdojr.html

JS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gtcomzmzgn.html

TS:   process.cwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtpokycupp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hnxiangtu.top/Article/details/gtwyqvmitq.html

Go:   os.Getwd()
来源：http://dali.jqgfzy.top/Article/details/gtkqouywxq.html

Ruby: Dir.pwd
来源：http://dali.zhengqikj.top/Article/details/gtoyvdnteh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ivvv.top/Article/details/gttdrrgorn.html

[M05] 设置退出码
来源：http://dali.yj202588.top/Article/details/gtfxnokaqp.html

Py:   sys.exit(1)
来源：http://dali.sweek.top/Article/details/gtarkraupc.html

PHP:  exit(1);
来源：http://dali.sufxvd.cn/Article/details/gtjuyspkym.html

JS:   process.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtxxnlaaoy.html

TS:   process.exit(1)
来源：http://dali.yongpay.top/Article/details/gtvozvyrpz.html

Java: System.exit(1)
来源：http://dali.sxryk.cn/Article/details/gtahdsvusr.html

Go:   os.Exit(1)
来源：http://dali.smart0.xyz/Article/details/gtiyrhrkyd.html

Ruby: exit 1
来源：http://dali.zhengqikj.top/Article/details/gtqzcmunjg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hnxiangtu.top/Article/details/gtxkprpygm.html

[M06] 向标准错误输出
来源：http://dali.meibo888.top/Article/details/gtwpctnoun.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxbyrbfz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aibaodan.cn/Article/details/gtbzbkpruv.html

JS:   console.error("err")
来源：http://dali.sxryk.cn/Article/details/gtkiqslcql.html

TS:   console.error("err")
来源：http://dali.jianghu66.top/Article/details/gtmovkpjha.html

Java: System.err.println("err")
来源：http://dali.redwolf501.top/Article/details/gtqfluiwsz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cqqwz.cn/Article/details/gtucyeidxy.html

Ruby: warn "err"
来源：http://dali.yueranfly.top/Article/details/gtzgvnvzrx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yonumen.top/Article/details/gtuytyxviz.html

[M07] 判断是否为主入口
来源：http://dali.c1oappe.top/Article/details/gtxeesccbn.html

Py:   if __name__ == "__main__":
来源：http://dali.yueranfly.top/Article/details/gtgkgntdbu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cashguo.top/Article/details/gtxzyegxib.html

JS:   require.main === module
来源：http://dali.yuanzhike.top/Article/details/gtjdubfkbw.html

TS:   require.main === module
来源：http://dali.jyoumei.cn/Article/details/gtyxvtyqfg.html

Java: public static void main(String[] args)
来源：http://dali.yangfankeji.com/Article/details/gtfazydbmr.html

Go:   func main()
来源：http://dali.aibaodan.cn/Article/details/gtkiroaykk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenzaomai.com/Article/details/gttlrxjiip.html

C#:   static void Main(string[] args)
来源：http://dali.snrcjt.cn/Article/details/gtadrykhsd.html

[M08] 获取系统与运行时信息
来源：http://dali.jianghu66.top/Article/details/gtwudyrlcg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.svipenyu.cn/Article/details/gtzxwezcuw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yuxming.cn/Article/details/gtjhbzhyix.html

JS:   process.platform;  process.version
来源：http://dali.svipenyu.cn/Article/details/gtwlridyzc.html

TS:   process.platform;  process.version
来源：http://dali.hnxiangtu.top/Article/details/gtaocqpxkr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.c1oappe.top/Article/details/gtsihguxxk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cheryme.top/Article/details/gtzzwubnqb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hnxiangtu.top/Article/details/gtnnetxbql.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj20258888.top/Article/details/gttshsvkqs.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtzscvccwr.html

N. 数据结构与算法
来源：http://dali.ybcxt.top/Article/details/gtobqwtxso.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtbsmuqtkm.html

[N01] 二分查找（有序数组）
来源：http://dali.chenjidiqi.icu/Article/details/gtjhijnzsg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtzlcqpktw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hywenlv.cn/Article/details/gtxhqwrdjj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sufxvd.cn/Article/details/gtsadljiyq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gtdzrxendb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gttnbaoevm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xinyue.icu/Article/details/gthquxlgfz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.birdmap.top/Article/details/gtxwijqiqj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtgugdlvbv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.daxiang520.top/Article/details/gtvzwyfqmb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dianchejie.cn/Article/details/gtbvqbdekr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zdqjudy.top/Article/details/gtfagxxssw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gtmlaoieoc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ybcxt.top/Article/details/gtfjpaqukd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sysykeji.top/Article/details/gtpdwaptvc.html

Go:   slices.Sort(arr)
来源：http://dali.birdmap.top/Article/details/gtkhaltebf.html

Ruby: arr.sort
来源：http://dali.tianlin.xyz/Article/details/gteweguvtn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkzsnrppa.html

[N03] 快速排序（分治示例）
来源：http://dali.fzhhl.top/Article/details/gtdxpghxyt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aibaodan.cn/Article/details/gtfinsosdk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj20258888.top/Article/details/gtjohufszt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shuidangran.top/Article/details/gtmpzdnzqq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.vqdsnc.cn/Article/details/gtnoctmbhp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ivvv.top/Article/details/gtycwbgyzg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shuidangran.top/Article/details/gtbffnwvqr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yanxiufei.cn/Article/details/gtajjerdlc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.daria6918.cn/Article/details/gtmcaczeaa.html

[N04] 斐波那契数列
来源：http://dali.yuanzhike.top/Article/details/gtxderrrvj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrtfdqiwk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.fengsongda.top/Article/details/gtqulxutql.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gtttvtwltf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gtmzzpnhbh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nanxuanxn.top/Article/details/gtpvkbiega.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tianlin.xyz/Article/details/gtzeukvnfp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gtlpcbqovq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtkxgsfwhj.html

[N05] 最大公约数
来源：http://dali.jqgufenzy.top/Article/details/gtdutnyeed.html

Py:   math.gcd(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzggginre.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.kuanghao11.cn/Article/details/gtcpftzlmg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zdqjudy.top/Article/details/gtfpojdsms.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hysaishi.cn/Article/details/gtwtyxjsju.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.andypj.xyz/Article/details/gtrhgflvhi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sysykeji.top/Article/details/gtjfcifrcm.html

Ruby: a.gcd(b)
来源：http://dali.guannengcc.top/Article/details/gtwnkcsnqg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenzaomai.com/Article/details/gtbhmjztum.html

[N06] 判断回文字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdlfdwvqq.html

Py:   s == s[::-1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdoqsrtek.html

PHP:  $s === strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gtkqxahqth.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtxtlbwtrq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gtnnmoxnek.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tian-w.cn/Article/details/gtlzrjkiiu.html

Go:   // 双指针从两端比较
来源：http://dali.quarkkingdee.top/Article/details/gtvfkpniut.html

Ruby: s == s.reverse
来源：http://dali.sysykeji.top/Article/details/gtxpyqdnrr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.feifeiyinyue.top/Article/details/gtdpygvxbq.html

[N07] 两数之和（返回下标）
来源：http://dali.xuanzx.com/Article/details/gtdmkfvwrp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zdqjudy.top/Article/details/gtaydguwfc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhongyouzk.top/Article/details/gthnxaomqc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yvedp.cn/Article/details/gtcdyicxco.html

TS:   // 手写 Map<string, number>
来源：http://dali.zycfv.cn/Article/details/gtkplbqosp.html

Java: // 手写 HashMap
来源：http://dali.meibo888.top/Article/details/gtabvaquez.html

Go:   // 手写 map[int]int
来源：http://dali.zhengqikj.top/Article/details/gtiamomogs.html

Ruby: // 手写 Hash
来源：http://dali.jinqigufen.top/Article/details/gtikaohrus.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenjidiqi.icu/Article/details/gtokcnajht.html

[N08] 生成全排列
来源：http://dali.gotoacloud.top/Article/details/gtktqhqlcq.html

Py:   itertools.permutations(arr)
来源：http://dali.yuxming.cn/Article/details/gtaeghkoof.html

PHP:  // 手写递归交换
来源：http://dali.tanke756.top/Article/details/gtxzreldws.html

JS:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtedjtcqtt.html

TS:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtmdrbacpm.html


<!-- 参考信息 -->