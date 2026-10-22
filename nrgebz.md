代发 wailian999

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtvmjzwtae.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jiagoushi.top/Article/details/gtjvzgqhbp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbsbsyzdv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpfgvodi.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtrjtujjln.html

K. JSON 与序列化
来源：http://dali.chenlongwang.top/Article/details/gttvvgcodh.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtcgzyypte.html

[K01] 对象转 JSON 字符串
来源：http://dali.gotoacloud.top/Article/details/gtdzhkwrxi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gtxpcwtehy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ppjwa.cn/Article/details/gtotfqboxt.html

JS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gtkvqiadsa.html

TS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtnmhtvkid.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shzxlz.cn/Article/details/gtrlnbnrlp.html

Go:   json.Marshal(obj)
来源：http://dali.aizwys.cn/Article/details/gttqjdbgmj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.dianchejie.cn/Article/details/gtpofgcssi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aizwys.cn/Article/details/gtladpoimg.html

[K02] JSON 字符串转对象
来源：http://dali.zycfv.cn/Article/details/gtupnllyln.html

Py:   json.loads(s)
来源：http://dali.fzhhl.top/Article/details/gtptidsmtf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.andypj.xyz/Article/details/gtlnhhcbst.html

JS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gtrpngsgee.html

TS:   JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gtcwxebcba.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtztscwjuv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gogol.net.cn/Article/details/gttrqvwgpb.html

Ruby: JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gttffqkypx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hysaishi.cn/Article/details/gtiphrgzim.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258888.top/Article/details/gtfparnocp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlibxxjul.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gaohongyu789.top/Article/details/gtnihgpjbl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenlongwang.top/Article/details/gtrdqguhtj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sysykeji.top/Article/details/gtsgdgvflm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tanke756.top/Article/details/gtqvwxshzc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijlvubvb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yongpay.top/Article/details/gteazpqjlg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcgxgnkqb.html

[K04] 读取 JSON 文件
来源：http://dali.ppjwa.cn/Article/details/gtvxpyaabg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhoulong.xyz/Article/details/gtkpcowpne.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ehwqpu.com/Article/details/gtutzoaktf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258888.top/Article/details/gtxwbqsuzj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pengpengdd.cyou/Article/details/gtfbndyehz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gtcodpevpk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xziqi.cn/Article/details/gtidqiwpdw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.mhx1999.top/Article/details/gtmpgvrjws.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yanxiufei.cn/Article/details/gttagqhbtt.html

[K05] 深拷贝对象
来源：http://dali.shzxlz.cn/Article/details/gtmhkrhjdp.html

Py:   copy.deepcopy(obj)
来源：http://dali.birdmap.top/Article/details/gtsgjnjozd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.iojbl.cn/Article/details/gtbckwxzxq.html

JS:   structuredClone(obj)
来源：http://dali.tian-w.cn/Article/details/gtadtzfttv.html

TS:   structuredClone(obj)
来源：http://dali.9152youxi.cn/Article/details/gtprdqduux.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.birdmap.top/Article/details/gtsbytmyxc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.meibo888.top/Article/details/gtcyolffro.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnxiangtu.top/Article/details/gtszdpfzol.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zycfv.cn/Article/details/gtmdhyezjr.html

[K06] 解析 URL 查询串
来源：http://dali.yanxiufei.cn/Article/details/gtxdlwngqb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj20258888.top/Article/details/gtyckysqeq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shuidangran.top/Article/details/gtacpnpycn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gtvfzjdzaj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gtsndcglbq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.smart0.xyz/Article/details/gtmbticshh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gtgooutyli.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gtzupfstqs.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvasracal.html

[K07] 进制转换
来源：http://dali.aizwys.cn/Article/details/gtnzbkmqgo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtmevsvkzy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.feifeiyinyue.top/Article/details/gtrwmobomi.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtxhfaqkym.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtknlzpbzh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtdxzmdgdx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yonumen.top/Article/details/gtovojndbr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.meibo888.top/Article/details/gtzxhiepok.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtnfrbrtfx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nwbrower.top/Article/details/gtmamqhfut.html

Py:   pickle.dumps(obj)
来源：http://dali.fengsongda.top/Article/details/gtewxrvqwn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jyoumei.cn/Article/details/gttxecnnox.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xziqi.cn/Article/details/gtnvnndfui.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj202588.top/Article/details/gtpniaftyf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.c1oappe.top/Article/details/gtnixfsnxb.html

Go:   encoding/gob
来源：http://dali.haohaochexian.top/Article/details/gtmixqdmxb.html

Ruby: Marshal.dump(obj)
来源：http://dali.bjfxy.top/Article/details/gttavbldvj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cashguo.top/Article/details/gtnuhvtqtg.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtczmooyof.html

L. 网络请求
来源：http://dali.wangdashe.top/Article/details/gtcnzdbqbq.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtzyndyrcl.html

[L01] 发送 GET 请求
来源：http://dali.jinqigfzy.top/Article/details/gtsxvtllls.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dashuyun.cn/Article/details/gtotpihrbe.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwwiuoxxg.html

JS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gtygphvrbv.html

TS:   await fetch(url)
来源：http://dali.shuidangran.top/Article/details/gtgwhvsmus.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gtczmvhiun.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhixingplan.top/Article/details/gtrhnflwrx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gaohongyu789.top/Article/details/gtqgvduqhp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.316326.xyz/Article/details/gtwlmmwldg.html

[L02] 发送 POST JSON
来源：http://dali.sweek.top/Article/details/gtyerklfhe.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jlsjyb.cn/Article/details/gtuiwnfzqk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.aizwys.cn/Article/details/gtgqmayotc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gtotqkmmek.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tianlin.xyz/Article/details/gtnhhhobsf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenlongwang.top/Article/details/gtowlapvty.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.316326.xyz/Article/details/gtcpzzcecc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tian-w.cn/Article/details/gtxlnmkojp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ydzc1.top/Article/details/gthgvgnjqg.html

[L03] 设置自定义请求头
来源：http://dali.shzxlz.cn/Article/details/gtonwbkxyg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hammf.cn/Article/details/gtnkjjhwnq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.fzhhl.top/Article/details/gtgxbmuewo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gtxwtlwkqo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gtjrvzilai.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.kuanghao11.cn/Article/details/gtkgiifacf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cqqwz.cn/Article/details/gttmfwvyhu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.smart0.xyz/Article/details/gtdfpoacmw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jiagoushi.top/Article/details/gtgzyoieoh.html

[L04] 设置超时
来源：http://dali.xuetiantiany.cn/Article/details/gthimkvffk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cdnleiting.top/Article/details/gtnowsivyo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yueranfly.top/Article/details/gtmnveincm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.meibo888.top/Article/details/gtrwuglmuq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gtebwkutxt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yvedp.cn/Article/details/gteikehtuz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cashguo.top/Article/details/gtesdmkyto.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.wangdashe.top/Article/details/gtayhjdvjy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xylfe.cn/Article/details/gtuoaxjlzw.html

[L05] 上传文件（multipart）
来源：http://dali.tian-w.cn/Article/details/gtvvragvdg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenlongwang.top/Article/details/gtnrvvvaxk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.daria6918.cn/Article/details/gtdbhrrnlz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.0kj1m.cn/Article/details/gtqmqnpeen.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrgneanib.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnxiangtu.top/Article/details/gtziiprhku.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.fengsongda.top/Article/details/gtrnavfxip.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.mhx1999.top/Article/details/gtxbrmqtyq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.fzhhl.top/Article/details/gthnphjfvu.html

[L06] 解析响应为 JSON
来源：http://dali.gzhubu.top/Article/details/gtsluvdkfu.html

Py:   resp.json()
来源：http://dali.xylfe.cn/Article/details/gtarsmojve.html

PHP:  json_decode($body, true);
来源：http://dali.ydzc1.top/Article/details/gtafgcndnj.html

JS:   await resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gthgymvrjv.html

TS:   await resp.json()
来源：http://dali.cheryme.top/Article/details/gthjhnrzol.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.fengsongda.top/Article/details/gtcvubgxwc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cqqwz.cn/Article/details/gtzdbdeoad.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sysykeji.top/Article/details/gthzaclbay.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sysykeji.top/Article/details/gttiuwcvxv.html

[L07] 处理 HTTP 状态码
来源：http://dali.xylfe.cn/Article/details/gtznftwgeh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hysaishi.cn/Article/details/gtnwezbpic.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sufxvd.cn/Article/details/gtzuynqhjz.html

JS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gtbcbcscgo.html

TS:   resp.ok;  resp.status
来源：http://dali.yuxming.cn/Article/details/gtyvjrojcb.html

Java: resp.statusCode()
来源：http://dali.nanxinkj.top/Article/details/gttwgarreh.html

Go:   resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gtusscwfjl.html

Ruby: resp.code.to_i
来源：http://dali.andypj.xyz/Article/details/gtungyvbbv.html

C#:   (int)resp.StatusCode
来源：http://dali.ehwqpu.com/Article/details/gtunkpizba.html

[L08] 并发请求多个地址
来源：http://dali.ivvv.top/Article/details/gtfxxjqayw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hysaishi.cn/Article/details/gtjpldzvrs.html

PHP:  curl_multi_init() 系列
来源：http://dali.jqgufenzy.top/Article/details/gtyfadppyy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gtkbjejchd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gttvuamarg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.andypj.xyz/Article/details/gtvwcmpsmh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jianghu66.top/Article/details/gtujlvqptu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shuidangran.top/Article/details/gtemgujjyb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hfpthk.cn/Article/details/gtoibryaey.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtggwowbvo.html

M. 命令行 / 进程 / 环境
来源：http://dali.jyoumei.cn/Article/details/gtlvorckis.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtnqnxayie.html

[M01] 读取命令行参数
来源：http://dali.hywenlv.cn/Article/details/gtfopqjdjn.html

Py:   sys.argv[1:]
来源：http://dali.zdqjudy.top/Article/details/gtdmqvleja.html

PHP:  $argv;  $argc;
来源：http://dali.smart0.xyz/Article/details/gtgudcmbzg.html

JS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gtzcfhibod.html

TS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gtgustqjeb.html

Java: args 数组（main 方法参数）
来源：http://dali.316326.xyz/Article/details/gtghkfdhnd.html

Go:   os.Args[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gtwsaivirh.html

Ruby: ARGV
来源：http://dali.iojbl.cn/Article/details/gtkfylrvld.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejgipeyn.html

[M02] 读取环境变量
来源：http://dali.pycfn.com/Article/details/gtyxnrzicj.html

Py:   os.environ.get("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtuokeekah.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmwsiczwg.html

JS:   process.env.HOME
来源：http://dali.yuxming.cn/Article/details/gtdjtowvmu.html

TS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gtxqjxdgxe.html

Java: System.getenv("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtxqneadum.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtvklxnmnq.html

Ruby: ENV["HOME"]
来源：http://dali.meibo888.top/Article/details/gtuktjxori.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.andypj.xyz/Article/details/gtiunfvvxf.html

[M03] 执行外部命令
来源：http://dali.jyoumei.cn/Article/details/gtoqllbehe.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sweek.top/Article/details/gtacrclyom.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.redwolf501.top/Article/details/gtnckmsjsk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gtmdkqgyjo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.fengsongda.top/Article/details/gtflxstwef.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sufxvd.cn/Article/details/gtzrxomboq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.9152youxi.cn/Article/details/gtmiletrrv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jiagoushi.top/Article/details/gtmwhthygn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj20258888.top/Article/details/gtzsywibib.html

[M04] 获取当前工作目录
来源：http://dali.quarkkingdee.top/Article/details/gtvgotwdmg.html

Py:   os.getcwd()
来源：http://dali.nwbrower.top/Article/details/gtvuktqiub.html

PHP:  getcwd();
来源：http://dali.meibo888.top/Article/details/gttklfbjnt.html

JS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gtmvlywmlf.html

TS:   process.cwd()
来源：http://dali.xylfe.cn/Article/details/gtiujywvpa.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ppjwa.cn/Article/details/gtlmarnpqy.html

Go:   os.Getwd()
来源：http://dali.yj20258888.top/Article/details/gttonbkxqq.html

Ruby: Dir.pwd
来源：http://dali.yj202588.top/Article/details/gtbxpnkmxm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhixingplan.top/Article/details/gtpaykkeqe.html

[M05] 设置退出码
来源：http://dali.guannengcc.top/Article/details/gtijzshzkg.html

Py:   sys.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdqjutene.html

PHP:  exit(1);
来源：http://dali.yuxming.cn/Article/details/gtqwzkqurn.html

JS:   process.exit(1)
来源：http://dali.wangdashe.top/Article/details/gtspxzyyec.html

TS:   process.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtpfnpmckg.html

Java: System.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtsoeqblxg.html

Go:   os.Exit(1)
来源：http://dali.jianghu66.top/Article/details/gtdxswmmxu.html

Ruby: exit 1
来源：http://dali.meibo888.top/Article/details/gtpmphugle.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gogol.net.cn/Article/details/gtontleofx.html

[M06] 向标准错误输出
来源：http://dali.chenlongwang.top/Article/details/gtgvqafspt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xinyue.icu/Article/details/gtkvxthhmc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xuanzx.com/Article/details/gtgolytshi.html

JS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gtcorvxxap.html

TS:   console.error("err")
来源：http://dali.hnqzz.top/Article/details/gtzyqbzope.html

Java: System.err.println("err")
来源：http://dali.aizwys.cn/Article/details/gtivhazbaw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yangfankeji.com/Article/details/gtoqywlxne.html

Ruby: warn "err"
来源：http://dali.xuanzx.com/Article/details/gtyuvrxixt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cashguo.top/Article/details/gtgnlrhjot.html

[M07] 判断是否为主入口
来源：http://dali.zhengqikj.top/Article/details/gtpdvtotmq.html

Py:   if __name__ == "__main__":
来源：http://dali.ivvv.top/Article/details/gtdfjnuwjc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ppjwa.cn/Article/details/gturadnfol.html

JS:   require.main === module
来源：http://dali.svipenyu.cn/Article/details/gttcngljtf.html

TS:   require.main === module
来源：http://dali.zhoulong.xyz/Article/details/gtyjnbbzpu.html

Java: public static void main(String[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gtnqivzwwq.html

Go:   func main()
来源：http://dali.yj202588.top/Article/details/gtwwprvjld.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhengqikj.top/Article/details/gtcyxdvypo.html

C#:   static void Main(string[] args)
来源：http://dali.smart0.xyz/Article/details/gtnwncenpn.html

[M08] 获取系统与运行时信息
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktahobgw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hammf.cn/Article/details/gtpqdwummv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sysykeji.top/Article/details/gteqawcezx.html

JS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gtpvctlrkw.html

TS:   process.platform;  process.version
来源：http://dali.cqqwz.cn/Article/details/gtolihzxoa.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dianchejie.cn/Article/details/gtrxrtfvgi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yanxiufei.cn/Article/details/gtqlrwkqnb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gzhubu.top/Article/details/gtrabvufjz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.svipenyu.cn/Article/details/gttlawllpk.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtdnwgobsu.html

N. 数据结构与算法
来源：http://dali.cashguo.top/Article/details/gtediyfayi.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtcclzbqfi.html

[N01] 二分查找（有序数组）
来源：http://dali.xylfe.cn/Article/details/gtfndjuxbl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.meibo888.top/Article/details/gtrlppgwte.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ybcxt.top/Article/details/gtiypmewgy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtogzdzops.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.0kj1m.cn/Article/details/gtoduqtliq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbfeylkb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtkgqvbrcs.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.c1oappe.top/Article/details/gtkdtftefz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxwgkboy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nanxinkj.top/Article/details/gtkutmlyaq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.svipenyu.cn/Article/details/gtidzvhwhi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj202588.top/Article/details/gtxzjomhfi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gtpijkuevh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.smart0.xyz/Article/details/gtqmulwssm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.chenzaomai.com/Article/details/gtvptibuzq.html

Go:   slices.Sort(arr)
来源：http://dali.nanxinkj.top/Article/details/gttimgkyzu.html

Ruby: arr.sort
来源：http://dali.snrcjt.cn/Article/details/gtytevfohh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuetiantiany.cn/Article/details/gtmsqxfreq.html

[N03] 快速排序（分治示例）
来源：http://dali.shangyingyoupin.top/Article/details/gtkbiadwfs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yueranfly.top/Article/details/gtddfqadsw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yuxming.cn/Article/details/gtxjobmvqs.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zdqjudy.top/Article/details/gtuxigscwo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenjidiqi.icu/Article/details/gtvhfjuell.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.guowangkeji.top/Article/details/gtjytursoc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ppjwa.cn/Article/details/gtatmglgno.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinqigufen.top/Article/details/gtjybuoadh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yonumen.top/Article/details/gtewpdxnxc.html

[N04] 斐波那契数列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfplxfxvn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.mhx1999.top/Article/details/gtdqukpyeo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shuidangran.top/Article/details/gtjtofqdhk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gtbqtagxaw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gtzynwzurt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sufxvd.cn/Article/details/gtvqqvyjwh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gzhubu.top/Article/details/gtwkhbriao.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nwbrower.top/Article/details/gtuypvrgas.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gtmurkwcpd.html

[N05] 最大公约数
来源：http://dali.shangyingyoupin.top/Article/details/gtyjpqaawy.html

Py:   math.gcd(a, b)
来源：http://dali.cheryme.top/Article/details/gtpdagujxc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nanxuanxn.top/Article/details/gtvmbyyhaj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aizwys.cn/Article/details/gtmyvjxyfk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cqqwz.cn/Article/details/gteugqyojl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinqigufen.top/Article/details/gtmjpmaajq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.pengpengdd.cyou/Article/details/gtqwwnkuln.html

Ruby: a.gcd(b)
来源：http://dali.jianghu66.top/Article/details/gtrgxwmqxo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsiqfkcyw.html

[N06] 判断回文字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtjnebrcop.html

Py:   s == s[::-1]
来源：http://dali.yj20258888.top/Article/details/gtlbifacju.html

PHP:  $s === strrev($s);
来源：http://dali.daria6918.cn/Article/details/gtuwesjxpr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtilbnahoa.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtzovzbvqx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvnznjgji.html

Go:   // 双指针从两端比较
来源：http://dali.yj202588.top/Article/details/gtnauqtwxs.html

Ruby: s == s.reverse
来源：http://dali.chenzaomai.com/Article/details/gtaqpfudat.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gtpzbdkdwy.html

[N07] 两数之和（返回下标）
来源：http://dali.guannengcc.top/Article/details/gtfnmblajv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sysykeji.top/Article/details/gtdgjqdauc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sufxvd.cn/Article/details/gtshqdorhj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gaohongyu789.top/Article/details/gtyyfnvrqr.html

TS:   // 手写 Map<string, number>
来源：http://dali.meibo888.top/Article/details/gtxhdhqsts.html

Java: // 手写 HashMap
来源：http://dali.yanxiufei.cn/Article/details/gtvsacrkew.html

Go:   // 手写 map[int]int
来源：http://dali.cashguo.top/Article/details/gtwogrhxpp.html

Ruby: // 手写 Hash
来源：http://dali.jinqigfzy.top/Article/details/gtbmwnvkel.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dianchejie.cn/Article/details/gtstyugbfk.html

[N08] 生成全排列
来源：http://dali.yangfankeji.com/Article/details/gtbnlnicoi.html

Py:   itertools.permutations(arr)
来源：http://dali.bjfxy.top/Article/details/gtacnqglws.html

PHP:  // 手写递归交换
来源：http://dali.guowangkeji.top/Article/details/gtdmjhxkrz.html

JS:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gtwpngsvwn.html

TS:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtmabzydfu.html


<!-- 参考信息 -->