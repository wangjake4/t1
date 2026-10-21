代发 wailian999

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtmdlrhrtn.html

K. JSON 与序列化
来源：http://dali.cdnleiting.top/Article/details/gtkoctvewh.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtrbpffmhc.html

[K01] 对象转 JSON 字符串
来源：http://dali.yanxiufei.cn/Article/details/gtcejhegmb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shangyingyoupin.top/Article/details/gtujwaeyqt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gtgacwodqc.html

JS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gtnifjoxpo.html

TS:   JSON.stringify(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtcslfthpf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtclczblxv.html

Go:   json.Marshal(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiazyjuvj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zycfv.cn/Article/details/gtrxzfvfwj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hfpthk.cn/Article/details/gtncawkxis.html

[K02] JSON 字符串转对象
来源：http://dali.chenjidiqi.icu/Article/details/gtiqqsiwso.html

Py:   json.loads(s)
来源：http://dali.xziqi.cn/Article/details/gtouuxiwqe.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.havefunace.top/Article/details/gtaotjmtxy.html

JS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtkyaukenx.html

TS:   JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gtgugrcohm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtmbpxvyol.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenjidiqi.icu/Article/details/gtxkavymzz.html

Ruby: JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gtqcatwxfx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmemylntr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dashuyun.cn/Article/details/gtsaolkdep.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gtmryibpcq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gtcvxjbdnc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtdmzjdqni.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.havefunace.top/Article/details/gtrqnlknsb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.birdmap.top/Article/details/gthonfnbda.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.316326.xyz/Article/details/gtgcqwzqzo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cdnleiting.top/Article/details/gtbuxyjipj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hysaishi.cn/Article/details/gtiotcehdp.html

[K04] 读取 JSON 文件
来源：http://dali.ybcxt.top/Article/details/gtadopcein.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tianlin.xyz/Article/details/gtelkqilmw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jqgufenzy.top/Article/details/gtsfdkxcor.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aizwys.cn/Article/details/gtrlqdhtdi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nwbrower.top/Article/details/gtnoysbcsq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuanzx.com/Article/details/gtlubynaxr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jqgufenzy.top/Article/details/gtzgikbumu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.guowangkeji.top/Article/details/gtklxuukbg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gtpfsdduqx.html

[K05] 深拷贝对象
来源：http://dali.c1oappe.top/Article/details/gtuoghywgp.html

Py:   copy.deepcopy(obj)
来源：http://dali.zycfv.cn/Article/details/gtohwsvlva.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hywenlv.cn/Article/details/gtfckhxwyq.html

JS:   structuredClone(obj)
来源：http://dali.yongpay.top/Article/details/gtvucbvgls.html

TS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtkqyicrzo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shanyushiyangkeji.top/Article/details/gthoehpujm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gzhubu.top/Article/details/gtgaovyflm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ybcxt.top/Article/details/gtsttnpvbq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoqhclkcz.html

[K06] 解析 URL 查询串
来源：http://dali.chenzaomai.com/Article/details/gtfrasgcix.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangtech.top/Article/details/gtanyhqssc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.pengpengdd.cyou/Article/details/gtcrfewemo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xylfe.cn/Article/details/gtrcbjkjiy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.vqdsnc.cn/Article/details/gtavpqtrid.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sufxvd.cn/Article/details/gtbpuykwsp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gtpaznzkyk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gteoyqypao.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjfrzrjnp.html

[K07] 进制转换
来源：http://dali.vqdsnc.cn/Article/details/gtlgfgljyq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtvbnyelrm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.dashuyun.cn/Article/details/gtilnmnrxl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtpnbgnvqn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtpifhirpc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtifvlqghx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cashguo.top/Article/details/gtflflqqba.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhongyouzk.top/Article/details/gtattoiumk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtegibksgr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hammf.cn/Article/details/gtawlxrrna.html

Py:   pickle.dumps(obj)
来源：http://dali.guannengcc.top/Article/details/gtwaocxwqt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jqgfzy.top/Article/details/gtnqjlzfqa.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gogol.net.cn/Article/details/gtcrtbputd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gtxooretjo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.feifeiyinyue.top/Article/details/gtnvxuxrnc.html

Go:   encoding/gob
来源：http://dali.chenlongwang.top/Article/details/gtxujhuhgt.html

Ruby: Marshal.dump(obj)
来源：http://dali.andypj.xyz/Article/details/gtlmxjzqer.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhongyouzk.top/Article/details/gteazahbmw.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtczamilrn.html

L. 网络请求
来源：http://dali.fengsongda.top/Article/details/gtjopuvfsu.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtljsfqvtj.html

[L01] 发送 GET 请求
来源：http://dali.hfpthk.cn/Article/details/gtdufcgpyb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj20258.top/Article/details/gtbkgblgpp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hammf.cn/Article/details/gtpoqxzghn.html

JS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gtqigaskfz.html

TS:   await fetch(url)
来源：http://dali.ydzc1.top/Article/details/gtkoftlsry.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xziqi.cn/Article/details/gtgoiqjsmm.html

Go:   resp, err := http.Get(url)
来源：http://dali.gaohongyu789.top/Article/details/gtytoiujpv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnxiangtu.top/Article/details/gtpfwopmgj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinqigfzy.top/Article/details/gtizwkoini.html

[L02] 发送 POST JSON
来源：http://dali.fzhhl.top/Article/details/gtqpxwobqm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yongpay.top/Article/details/gtnqxmjivh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jqgfzy.top/Article/details/gtjuyzlivc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guannengcc.top/Article/details/gtmxrwjtnc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guannengcc.top/Article/details/gtahtyefwq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.guannengcc.top/Article/details/gtcchnylis.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sxryk.cn/Article/details/gthxvcyakb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hongshengwenyu.top/Article/details/gtwzeegfiv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.kuanghao11.cn/Article/details/gtlobuppro.html

[L03] 设置自定义请求头
来源：http://dali.gogol.net.cn/Article/details/gtagzocqrw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.aizwys.cn/Article/details/gtqmrongyx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cucudq.cn/Article/details/gtabvlfruw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gtlaymckak.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gtycbqvoyk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yangfankeji.com/Article/details/gtzqbybhai.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhongyouzk.top/Article/details/gtshphmnzr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sufxvd.cn/Article/details/gtukaqinkp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwiidehlj.html

[L04] 设置超时
来源：http://dali.chenjidiqi.icu/Article/details/gttbafblgb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hywenlv.cn/Article/details/gtyjoebhmg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.daxiang520.top/Article/details/gtdfhbtulh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gtlsqqudky.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gogol.net.cn/Article/details/gtugyartrb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yanxiufei.cn/Article/details/gtudiivyyk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.316326.xyz/Article/details/gtdrsksigq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.guannengcc.top/Article/details/gtrxknxftx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sysykeji.top/Article/details/gtxbelkpxo.html

[L05] 上传文件（multipart）
来源：http://dali.cheryme.top/Article/details/gtbmrlkprq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cdnleiting.top/Article/details/gtdvjnvmfe.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.daxiang520.top/Article/details/gtkarpwidq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhiwuduotai.top/Article/details/gtssbrpzai.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.andypj.xyz/Article/details/gtmcbpkrxh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ywan-chungtsiang.top/Article/details/gtllkcjosm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jqgufenzy.top/Article/details/gtuqzreeod.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xuanzx.com/Article/details/gtjmfsvpyx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.mhx1999.top/Article/details/gtwxytbdbi.html

[L06] 解析响应为 JSON
来源：http://dali.jinqigufen.top/Article/details/gtytgclzdu.html

Py:   resp.json()
来源：http://dali.bjfxy.top/Article/details/gtcuosqlyd.html

PHP:  json_decode($body, true);
来源：http://dali.dashuyun.cn/Article/details/gtkeekoqtc.html

JS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gtcufntdsu.html

TS:   await resp.json()
来源：http://dali.shzxlz.cn/Article/details/gthfqgquuq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gtmqaukjla.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhiwuduotai.top/Article/details/gtjqcdukks.html

Ruby: JSON.parse(resp.body)
来源：http://dali.snrcjt.cn/Article/details/gtdbucnndz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.daxiang520.top/Article/details/gtpmewtsut.html

[L07] 处理 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gtsgrwzfsw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zdqjudy.top/Article/details/gtjpaeaadu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xuanzx.com/Article/details/gtmrwfjmhg.html

JS:   resp.ok;  resp.status
来源：http://dali.gzhubu.top/Article/details/gtkpvskfkz.html

TS:   resp.ok;  resp.status
来源：http://dali.ydzc1.top/Article/details/gtrlfnirzo.html

Java: resp.statusCode()
来源：http://dali.hfpthk.cn/Article/details/gtgzpapyvb.html

Go:   resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gthujbfhva.html

Ruby: resp.code.to_i
来源：http://dali.haohaochexian.top/Article/details/gtdpcityig.html

C#:   (int)resp.StatusCode
来源：http://dali.sweek.top/Article/details/gtbjwmftem.html

[L08] 并发请求多个地址
来源：http://dali.hammf.cn/Article/details/gtgfquaomn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.smart0.xyz/Article/details/gtjizjmjkf.html

PHP:  curl_multi_init() 系列
来源：http://dali.yongpay.top/Article/details/gtuskdzqxp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gtvrmwskzd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gtuavlmrfg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hnxiangtu.top/Article/details/gtagoxmiuk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cashguo.top/Article/details/gtmxfndyxe.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfsvyvjcr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.meibo888.top/Article/details/gtgostqtze.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtndmlyiux.html

M. 命令行 / 进程 / 环境
来源：http://dali.cashguo.top/Article/details/gtbkmizlze.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmikirzxf.html

[M01] 读取命令行参数
来源：http://dali.haohaochexian.top/Article/details/gteerghrrq.html

Py:   sys.argv[1:]
来源：http://dali.sxryk.cn/Article/details/gtqvybinqz.html

PHP:  $argv;  $argc;
来源：http://dali.yj20258.top/Article/details/gtrgeplymr.html

JS:   process.argv.slice(2)
来源：http://dali.quarkkingdee.top/Article/details/gtgimqfigf.html

TS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gtkdhptjve.html

Java: args 数组（main 方法参数）
来源：http://dali.bjfxy.top/Article/details/gtfvjghcjy.html

Go:   os.Args[1:]
来源：http://dali.meibo888.top/Article/details/gtxjroxhnw.html

Ruby: ARGV
来源：http://dali.hfpthk.cn/Article/details/gtsfpnwhxy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xuanzx.com/Article/details/gtgwlgvlyi.html

[M02] 读取环境变量
来源：http://dali.vqdsnc.cn/Article/details/gtwpxtrprs.html

Py:   os.environ.get("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gtekuphini.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gtyrrdocmk.html

JS:   process.env.HOME
来源：http://dali.gogol.net.cn/Article/details/gtwzmlrqss.html

TS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gtplvomxqx.html

Java: System.getenv("HOME")
来源：http://dali.cucudq.cn/Article/details/gtsfqanzkr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yongpay.top/Article/details/gtntxzcmyz.html

Ruby: ENV["HOME"]
来源：http://dali.zycfv.cn/Article/details/gtuxwosnut.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cheryme.top/Article/details/gtyxstispm.html

[M03] 执行外部命令
来源：http://dali.vqdsnc.cn/Article/details/gtycyccipf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zycfv.cn/Article/details/gtvfmndkzj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhiwuduotai.top/Article/details/gtlsfrvxxx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhoulong.xyz/Article/details/gtelasblja.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jyoumei.cn/Article/details/gtkcixrdws.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xinyue.icu/Article/details/gtruxyfmvz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shuidangran.top/Article/details/gtqwhneluf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cdnleiting.top/Article/details/gttwbrkzte.html

C#:   Process.Start("ls", "-l");
来源：http://dali.fzhhl.top/Article/details/gtomqylcll.html

[M04] 获取当前工作目录
来源：http://dali.daria6918.cn/Article/details/gtaguaznyw.html

Py:   os.getcwd()
来源：http://dali.smart0.xyz/Article/details/gtpvgocpts.html

PHP:  getcwd();
来源：http://dali.shangyingyoupin.top/Article/details/gtmsvbbyhj.html

JS:   process.cwd()
来源：http://dali.ehwqpu.com/Article/details/gtdyfbtgys.html

TS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gttymnsfkm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.daria6918.cn/Article/details/gtzpzbirpr.html

Go:   os.Getwd()
来源：http://dali.pycfn.com/Article/details/gtiofnidwh.html

Ruby: Dir.pwd
来源：http://dali.chenlongwang.top/Article/details/gtcjwaecyc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hammf.cn/Article/details/gtddlbfscm.html

[M05] 设置退出码
来源：http://dali.cheryme.top/Article/details/gtixgoeqno.html

Py:   sys.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtpbuxxtka.html

PHP:  exit(1);
来源：http://dali.hysaishi.cn/Article/details/gtrymhjdtv.html

JS:   process.exit(1)
来源：http://dali.meibo888.top/Article/details/gtbmizvman.html

TS:   process.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtnynljlgm.html

Java: System.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtipmxygll.html

Go:   os.Exit(1)
来源：http://dali.yuxming.cn/Article/details/gttbzbhuwt.html

Ruby: exit 1
来源：http://dali.jinqigfzy.top/Article/details/gtlpzjskov.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhengqikj.top/Article/details/gtysovucnt.html

[M06] 向标准错误输出
来源：http://dali.cheryme.top/Article/details/gtqyxsyxfj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sysykeji.top/Article/details/gtzkgopmbq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.quarkkingdee.top/Article/details/gtmlcoczml.html

JS:   console.error("err")
来源：http://dali.daria6918.cn/Article/details/gtqmpowsts.html

TS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtahvmvngw.html

Java: System.err.println("err")
来源：http://dali.snrcjt.cn/Article/details/gtmwvdyvdn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenlongwang.top/Article/details/gtplkpetev.html

Ruby: warn "err"
来源：http://dali.yuxming.cn/Article/details/gtdiuczdzb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenjidiqi.icu/Article/details/gtttiirory.html

[M07] 判断是否为主入口
来源：http://dali.hongshengwenyu.top/Article/details/gtafkdfrir.html

Py:   if __name__ == "__main__":
来源：http://dali.dashuyun.cn/Article/details/gteaecqfzl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.quarkkingdee.top/Article/details/gtnqhiateo.html

JS:   require.main === module
来源：http://dali.yueranfly.top/Article/details/gtgvhzzpuz.html

TS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gtukymwjun.html

Java: public static void main(String[] args)
来源：http://dali.yj20258.top/Article/details/gtapvzkwvk.html

Go:   func main()
来源：http://dali.andypj.xyz/Article/details/gtyquqnccr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shangyingyoupin.top/Article/details/gtcypiwfbk.html

C#:   static void Main(string[] args)
来源：http://dali.jinqigfzy.top/Article/details/gtwyhidtyx.html

[M08] 获取系统与运行时信息
来源：http://dali.birdmap.top/Article/details/gtwivndwpf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daxiang520.top/Article/details/gthfxitajt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tanke756.top/Article/details/gtzohhroyc.html

JS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gtgpikjssf.html

TS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gtvcxnldsp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shangyingyoupin.top/Article/details/gtmmtjjjin.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cashguo.top/Article/details/gtdwolegjc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cheryme.top/Article/details/gtwjwsigfj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yanxiufei.cn/Article/details/gtmldtneqq.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtcuqipbuk.html

N. 数据结构与算法
来源：http://dali.quarkkingdee.top/Article/details/gtmoagpyrm.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtbhkigeew.html

[N01] 二分查找（有序数组）
来源：http://dali.bjfxy.top/Article/details/gtmyiyshhz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtfobuwrab.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.aizwys.cn/Article/details/gtoidhcaat.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.meibo888.top/Article/details/gtjqjsgbtt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gtsahpobbj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yongpay.top/Article/details/gtioeycset.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtbpkdhris.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yuanzhike.top/Article/details/gtjizpcmfk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtpsihuqvj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jiagoushi.top/Article/details/gtgpftjgdk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj202588.top/Article/details/gtewqymhqv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258888.top/Article/details/gtlmutegmu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gtqfqfdqhm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daxiang520.top/Article/details/gtzmaevrxi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.fengsongda.top/Article/details/gtuftyeeio.html

Go:   slices.Sort(arr)
来源：http://dali.zhengqikj.top/Article/details/gtjabsbcmo.html

Ruby: arr.sort
来源：http://dali.yuanzhike.top/Article/details/gtejmfzhkx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gtgvqztczf.html

[N03] 快速排序（分治示例）
来源：http://dali.ydzc1.top/Article/details/gtuiqnihya.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.smart0.xyz/Article/details/gtafporhds.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenzaomai.com/Article/details/gtlyzfckrk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzvpwvgly.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258.top/Article/details/gtsxqwkelf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zycfv.cn/Article/details/gtxgshixnf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hnxiangtu.top/Article/details/gtuqrihemn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.wangshuangyany.cn/Article/details/gtjzwedtvx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhongyouzk.top/Article/details/gtsgsfbjio.html

[N04] 斐波那契数列
来源：http://dali.9152youxi.cn/Article/details/gtkstjytak.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gttnwbinnj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jianghu66.top/Article/details/gtsbakfwvd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gtklworduj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmevzivy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yvedp.cn/Article/details/gtvvwlkmzt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj202588.top/Article/details/gtsymvwecu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xziqi.cn/Article/details/gtpxvhdgds.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gtmwesxmxx.html

[N05] 最大公约数
来源：http://dali.pengpengdd.cyou/Article/details/gtehhpkezo.html

Py:   math.gcd(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gtglopumkf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nwbrower.top/Article/details/gtztibcbiy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xziqi.cn/Article/details/gtpjdotikk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.snrcjt.cn/Article/details/gtnqarybxj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.meibo888.top/Article/details/gtebrcqknx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.kuanghao11.cn/Article/details/gtjgtskgwa.html

Ruby: a.gcd(b)
来源：http://dali.sweek.top/Article/details/gtszxzdsmf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gzhubu.top/Article/details/gtfqbcofni.html

[N06] 判断回文字符串
来源：http://dali.0kj1m.cn/Article/details/gtuwaeicvc.html

Py:   s == s[::-1]
来源：http://dali.ydzc1.top/Article/details/gtnbrymbiy.html

PHP:  $s === strrev($s);
来源：http://dali.nanxuanxn.top/Article/details/gtclkpzqbs.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gtijpdbfci.html

TS:   s === [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtmawebnvk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.pycfn.com/Article/details/gtxhgwqvxj.html

Go:   // 双指针从两端比较
来源：http://dali.andypj.xyz/Article/details/gtagjwcigz.html

Ruby: s == s.reverse
来源：http://dali.andypj.xyz/Article/details/gtrbouzopd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nwbrower.top/Article/details/gtorpxguxf.html

[N07] 两数之和（返回下标）
来源：http://dali.yonumen.top/Article/details/gtbljbivus.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ppjwa.cn/Article/details/gtrzxkwzux.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.wangshuangyany.cn/Article/details/gtjicxafqt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yongpay.top/Article/details/gtyzrfcdlb.html

TS:   // 手写 Map<string, number>
来源：http://dali.gotoacloud.top/Article/details/gtykziqubk.html

Java: // 手写 HashMap
来源：http://dali.jianghu66.top/Article/details/gtxpzxojfj.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gtmsjalhma.html

Ruby: // 手写 Hash
来源：http://dali.sweek.top/Article/details/gtfumcwggl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jqgufenzy.top/Article/details/gtwsqwdgkc.html

[N08] 生成全排列
来源：http://dali.cheryme.top/Article/details/gtyofwikua.html

Py:   itertools.permutations(arr)
来源：http://dali.gogol.net.cn/Article/details/gteobxamma.html

PHP:  // 手写递归交换
来源：http://dali.ehwqpu.com/Article/details/gtxrexoujo.html

JS:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtwfomdaob.html

TS:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gthioeqxpv.html

Java: // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtikohrzqv.html

Go:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gtvtbcsbbd.html

Ruby: arr.permutation.to_a
来源：http://dali.nwbrower.top/Article/details/gtgmmowemb.html

C#:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkuhksosh.html


<!-- 参考信息 -->