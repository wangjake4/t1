代发 wailian999

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtxfsmrnfq.html

K. JSON 与序列化
来源：http://dali.xuetiantiany.cn/Article/details/gtubnglill.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtybspqxra.html

[K01] 对象转 JSON 字符串
来源：http://dali.fengsongda.top/Article/details/gtnizdtsnp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zdqjudy.top/Article/details/gtzlqayjnb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nwbrower.top/Article/details/gtmiofchtg.html

JS:   JSON.stringify(obj)
来源：http://dali.daria6918.cn/Article/details/gtaxqprjgg.html

TS:   JSON.stringify(obj)
来源：http://dali.guannengcc.top/Article/details/gtfyarnfdm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.9152youxi.cn/Article/details/gtrvjgwnks.html

Go:   json.Marshal(obj)
来源：http://dali.pycfn.com/Article/details/gtardbqcvy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj20258.top/Article/details/gtuncaeltl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jianghu66.top/Article/details/gtrjhectnu.html

[K02] JSON 字符串转对象
来源：http://dali.gogol.net.cn/Article/details/gtpfzmzsor.html

Py:   json.loads(s)
来源：http://dali.zhiwuduotai.top/Article/details/gttlwaqlzz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.fzhhl.top/Article/details/gtobzszhoc.html

JS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gtbgxsacvk.html

TS:   JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiyfouerq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.meibo888.top/Article/details/gtgggnphhc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hnxiangtu.top/Article/details/gtkireblsx.html

Ruby: JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gtqmuigiaf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.aizwys.cn/Article/details/gtxnfndbed.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.pycfn.com/Article/details/gtgohqwasu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.9152youxi.cn/Article/details/gtyutmpdsc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258888.top/Article/details/gtyoxfyrlg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ybcxt.top/Article/details/gttojwmpwx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gtrspscyxq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hammf.cn/Article/details/gtmunavpbv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.guannengcc.top/Article/details/gtlntdasbv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtmpexdrxt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hysaishi.cn/Article/details/gtsyfpszgh.html

[K04] 读取 JSON 文件
来源：http://dali.cqqwz.cn/Article/details/gtlfnhbpqp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jqgufenzy.top/Article/details/gtbmwxdwnn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.birdmap.top/Article/details/gtbylflbit.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ivvv.top/Article/details/gtqiaobndv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sysykeji.top/Article/details/gtvakurbma.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ybcxt.top/Article/details/gtysioblwh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tanke756.top/Article/details/gtqdbbvjla.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daxiang520.top/Article/details/gtjyghagvz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gthfwlrgmy.html

[K05] 深拷贝对象
来源：http://dali.cdnleiting.top/Article/details/gtdifuqesu.html

Py:   copy.deepcopy(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtdtzbueyv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yuxming.cn/Article/details/gtmcakgxum.html

JS:   structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gtvujqvsqc.html

TS:   structuredClone(obj)
来源：http://dali.gotoacloud.top/Article/details/gtoqywhrpe.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.pycfn.com/Article/details/gtyxfwxagb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.316326.xyz/Article/details/gtzylwnujq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xinyue.icu/Article/details/gtzxahpiel.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.pengpengdd.cyou/Article/details/gtfxdbuheg.html

[K06] 解析 URL 查询串
来源：http://dali.shzxlz.cn/Article/details/gtyyfemrpu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj202588.top/Article/details/gtilzzxtpe.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangdashe.top/Article/details/gtykckngyn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gtcxshdswy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gtyrpjmfrm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hywenlv.cn/Article/details/gtvjviydiz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gtigfphwap.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gtuqvkhrms.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gtdvjddswa.html

[K07] 进制转换
来源：http://dali.yj20258.top/Article/details/gtmsfpaxbi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtwvzpgpnn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.bjfxy.top/Article/details/gttigotcwj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtsooszwch.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgeoriuxh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtpiqqscjb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daria6918.cn/Article/details/gtnukowfyd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dianchejie.cn/Article/details/gtstuvdjoo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtdtpodyyc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sufxvd.cn/Article/details/gtxyarffnd.html

Py:   pickle.dumps(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpakmhpjy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xylfe.cn/Article/details/gtxjwpwhkl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gtddaomgfw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gtfizqvzhp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yonumen.top/Article/details/gtdfjhbkye.html

Go:   encoding/gob
来源：http://dali.havefunace.top/Article/details/gtasfbnwzt.html

Ruby: Marshal.dump(obj)
来源：http://dali.cashguo.top/Article/details/gtkhymcicv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gtwvnocwrq.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gttnwmeyrd.html

L. 网络请求
来源：http://dali.jlsjyb.cn/Article/details/gtszwnltos.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtdluoyqog.html

[L01] 发送 GET 请求
来源：http://dali.jianghu66.top/Article/details/gtmebqzxxd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.birdmap.top/Article/details/gtooonfyhi.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.andypj.xyz/Article/details/gthtjugvpr.html

JS:   await fetch(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtctqupjcy.html

TS:   await fetch(url)
来源：http://dali.cqqwz.cn/Article/details/gtsvwemnfv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.mhx1999.top/Article/details/gtzgvuuebl.html

Go:   resp, err := http.Get(url)
来源：http://dali.nanxuanxn.top/Article/details/gtnumxakwm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hysaishi.cn/Article/details/gtblqctvzo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sufxvd.cn/Article/details/gtwrrowpbl.html

[L02] 发送 POST JSON
来源：http://dali.yonumen.top/Article/details/gtzbwxdgrm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj202588.top/Article/details/gtjkojjmsw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.316326.xyz/Article/details/gtvdcdwvlf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cqqwz.cn/Article/details/gtxsfkbvpe.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gtjwwlvyug.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.pycfn.com/Article/details/gtnxaiwdbu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.pengpengdd.cyou/Article/details/gtqlsbpduf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.quarkkingdee.top/Article/details/gtytphpwco.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtwtjywmdi.html

[L03] 设置自定义请求头
来源：http://dali.wangdashe.top/Article/details/gtmlhurwxv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ybcxt.top/Article/details/gtocsntstb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jlsjyb.cn/Article/details/gtnrmpwxjm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gtvhfjcjei.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zycfv.cn/Article/details/gtnyzuhmwd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shuidangran.top/Article/details/gthouljnrc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xylfe.cn/Article/details/gtqcivrglt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhengqikj.top/Article/details/gtcjxgrbjt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gtjkjphazg.html

[L04] 设置超时
来源：http://dali.wangshuangyany.cn/Article/details/gtaakgkrqn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.smart0.xyz/Article/details/gtmnkosejo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hnxiangtu.top/Article/details/gtaigdyolf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tian-w.cn/Article/details/gtxptmnceb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.mhx1999.top/Article/details/gtcnelmira.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shuidangran.top/Article/details/gtbykfsnye.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.havefunace.top/Article/details/gtwwbdtqpm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cucudq.cn/Article/details/gtytrxkqjv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnqzz.top/Article/details/gtqyovlqip.html

[L05] 上传文件（multipart）
来源：http://dali.0kj1m.cn/Article/details/gtbmpbkvus.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxuanxn.top/Article/details/gtrngufjgz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gtlenadscw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gtnxugksyz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jianghu66.top/Article/details/gttdrdsiqz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqklwquz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hnxiangtu.top/Article/details/gtytysguly.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jqgufenzy.top/Article/details/gtlzvtspif.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtkgzichok.html

[L06] 解析响应为 JSON
来源：http://dali.sxryk.cn/Article/details/gtbvbtvnvp.html

Py:   resp.json()
来源：http://dali.meibo888.top/Article/details/gtvoxzyxof.html

PHP:  json_decode($body, true);
来源：http://dali.zhongyouzk.top/Article/details/gtedcjtfjr.html

JS:   await resp.json()
来源：http://dali.316326.xyz/Article/details/gtcpvhipya.html

TS:   await resp.json()
来源：http://dali.jiagoushi.top/Article/details/gtvipwqosy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.svipenyu.cn/Article/details/gtqttztgpq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.wangshuangyany.cn/Article/details/gtlcfwxaok.html

Ruby: JSON.parse(resp.body)
来源：http://dali.meibo888.top/Article/details/gtabcwzwvy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ivvv.top/Article/details/gtwjxgcagd.html

[L07] 处理 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gtbhneofyv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cheryme.top/Article/details/gtdrfnfrxb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hywenlv.cn/Article/details/gtddadrwjy.html

JS:   resp.ok;  resp.status
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfozkwfij.html

TS:   resp.ok;  resp.status
来源：http://dali.cdnleiting.top/Article/details/gtrthjzdmc.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gtcvzfptyq.html

Go:   resp.StatusCode
来源：http://dali.chenlongwang.top/Article/details/gtbxiyzjqa.html

Ruby: resp.code.to_i
来源：http://dali.smart0.xyz/Article/details/gtjnagvaph.html

C#:   (int)resp.StatusCode
来源：http://dali.cashguo.top/Article/details/gtwgnfmlyj.html

[L08] 并发请求多个地址
来源：http://dali.aibaodan.cn/Article/details/gtjqccimeh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangshuangyany.cn/Article/details/gtolxhekeo.html

PHP:  curl_multi_init() 系列
来源：http://dali.cqqwz.cn/Article/details/gtycsfvgoq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gtkxbgjzjd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gtdxunthgm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.aizwys.cn/Article/details/gtwmkqotnl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cqqwz.cn/Article/details/gtgygtejun.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.feifeiyinyue.top/Article/details/gtnzhgkcuw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aizwys.cn/Article/details/gthzlewcch.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gticjzyowf.html

M. 命令行 / 进程 / 环境
来源：http://dali.cheryme.top/Article/details/gtjficzchm.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtscccnhpv.html

[M01] 读取命令行参数
来源：http://dali.aizwys.cn/Article/details/gtnlezjsrj.html

Py:   sys.argv[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gtoaxlxvru.html

PHP:  $argv;  $argc;
来源：http://dali.ppjwa.cn/Article/details/gtucghvvzx.html

JS:   process.argv.slice(2)
来源：http://dali.fzhhl.top/Article/details/gtsisfshiu.html

TS:   process.argv.slice(2)
来源：http://dali.ydzc1.top/Article/details/gtevozenzg.html

Java: args 数组（main 方法参数）
来源：http://dali.ivvv.top/Article/details/gtoaayadly.html

Go:   os.Args[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcubnirqa.html

Ruby: ARGV
来源：http://dali.birdmap.top/Article/details/gtimpezrqs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ydzc1.top/Article/details/gtybasxris.html

[M02] 读取环境变量
来源：http://dali.jinqigfzy.top/Article/details/gtheccgxyz.html

Py:   os.environ.get("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtjtqzdjlu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gtgkbxcveh.html

JS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gtkbqjlbrf.html

TS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gtvnmdbvpm.html

Java: System.getenv("HOME")
来源：http://dali.ydzc1.top/Article/details/gttcfzxlkg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmfmequg.html

Ruby: ENV["HOME"]
来源：http://dali.zhongyouzk.top/Article/details/gtzutvlpzj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yonumen.top/Article/details/gtcitohwqs.html

[M03] 执行外部命令
来源：http://dali.guowangkeji.top/Article/details/gtvbdtzgtp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.meibo888.top/Article/details/gtmfdjmfbw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nwbrower.top/Article/details/gtfdyktadg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuanzhike.top/Article/details/gtizhusoph.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gterxsajkr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jyoumei.cn/Article/details/gtjatdtwti.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cqqwz.cn/Article/details/gtizwwiuwy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gaohongyu789.top/Article/details/gtmvrhvssi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hywenlv.cn/Article/details/gtkrrimnvk.html

[M04] 获取当前工作目录
来源：http://dali.hywenlv.cn/Article/details/gtoplfnpcm.html

Py:   os.getcwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtarlgoxbg.html

PHP:  getcwd();
来源：http://dali.gotoacloud.top/Article/details/gtgsjhhjkg.html

JS:   process.cwd()
来源：http://dali.gzhubu.top/Article/details/gtzgbyqucl.html

TS:   process.cwd()
来源：http://dali.316326.xyz/Article/details/gthkmjkdbw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.wangshuangyany.cn/Article/details/gtnsupiyrk.html

Go:   os.Getwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtsdkzglqw.html

Ruby: Dir.pwd
来源：http://dali.birdmap.top/Article/details/gtfcujjudk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.kuanghao11.cn/Article/details/gtlsjrvxrt.html

[M05] 设置退出码
来源：http://dali.redwolf501.top/Article/details/gtimuuytba.html

Py:   sys.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtcbpcmydn.html

PHP:  exit(1);
来源：http://dali.yangfankeji.com/Article/details/gtxsevhutx.html

JS:   process.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtfwkekhok.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttggbdvvm.html

Java: System.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtokrojtdo.html

Go:   os.Exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtmemtxfso.html

Ruby: exit 1
来源：http://dali.tianlin.xyz/Article/details/gtrydvmwho.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.bjfxy.top/Article/details/gtxmtpqwyw.html

[M06] 向标准错误输出
来源：http://dali.gotoacloud.top/Article/details/gtouzyquig.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yonumen.top/Article/details/gtxdoqsmwp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj202588.top/Article/details/gtcaewitas.html

JS:   console.error("err")
来源：http://dali.chenjidiqi.icu/Article/details/gtdlqzciqm.html

TS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gtixltaatb.html

Java: System.err.println("err")
来源：http://dali.daxiang520.top/Article/details/gtfluqchju.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xuanzx.com/Article/details/gtqqlazvog.html

Ruby: warn "err"
来源：http://dali.ivvv.top/Article/details/gthagayvmi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhengqikj.top/Article/details/gtewhajxbm.html

[M07] 判断是否为主入口
来源：http://dali.nanxinkj.top/Article/details/gtiikgtpds.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258.top/Article/details/gtstzfuvot.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yangfankeji.com/Article/details/gtshgqqsar.html

JS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gtakjkqupq.html

TS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gtknubrvwn.html

Java: public static void main(String[] args)
来源：http://dali.gogol.net.cn/Article/details/gtgylvneoj.html

Go:   func main()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrehstcd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.andypj.xyz/Article/details/gthokxkgdb.html

C#:   static void Main(string[] args)
来源：http://dali.9152youxi.cn/Article/details/gtvvsoyhib.html

[M08] 获取系统与运行时信息
来源：http://dali.ywan-chungtsiang.top/Article/details/gtamzrrvbp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hysaishi.cn/Article/details/gtomallrtz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zycfv.cn/Article/details/gtqujhnewf.html

JS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gtjdasrvls.html

TS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gtaeuxocsx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigufen.top/Article/details/gtkbdtbqpx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinqigfzy.top/Article/details/gtemwcjwjf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhoulong.xyz/Article/details/gtjbdchiux.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yueranfly.top/Article/details/gtpgchdyqj.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtebwiwswo.html

N. 数据结构与算法
来源：http://dali.sysykeji.top/Article/details/gtnecrcsfb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtvlgacunc.html

[N01] 二分查找（有序数组）
来源：http://dali.zhoulong.xyz/Article/details/gtwhnutlhz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtppzggyyi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhengqikj.top/Article/details/gtirgtqhkg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zycfv.cn/Article/details/gtavcilbcp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtigrmbsnp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtakwldmcp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtjercwjeu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tianlin.xyz/Article/details/gtvwyrgbfi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtdzsnwreb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sxryk.cn/Article/details/gtcalwlzzt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxinkj.top/Article/details/gtppzwdwro.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nanxuanxn.top/Article/details/gtmfvuzqpa.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgufenzy.top/Article/details/gthsmjcneu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gteujpcycp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nanxuanxn.top/Article/details/gtqwjktevt.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigufen.top/Article/details/gtlibdtqxt.html

Ruby: arr.sort
来源：http://dali.mhx1999.top/Article/details/gtexfwgffc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.haohaochexian.top/Article/details/gtsybxqbsm.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigfzy.top/Article/details/gtmruydngn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.wangshuangyany.cn/Article/details/gtybzfqbvj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gotoacloud.top/Article/details/gtbmjbjwpt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hywenlv.cn/Article/details/gtealhtgwr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.snrcjt.cn/Article/details/gtssvsrbiw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuxming.cn/Article/details/gtsznqdivv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jyoumei.cn/Article/details/gtmeinlqko.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cqqwz.cn/Article/details/gtkerbocbd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jyoumei.cn/Article/details/gtrdacpvpj.html

[N04] 斐波那契数列
来源：http://dali.sufxvd.cn/Article/details/gtvhhfslqz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.redwolf501.top/Article/details/gtumleuolf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gtxolwoeiu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gtrwdtxfeh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gthemiirgj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.daria6918.cn/Article/details/gtvzthofuh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zdqjudy.top/Article/details/gtgonjscrx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258.top/Article/details/gtfcaiifwx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gttsynywrr.html

[N05] 最大公约数
来源：http://dali.yonumen.top/Article/details/gtasmsypde.html

Py:   math.gcd(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gtgbxwvocd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gogol.net.cn/Article/details/gtsgtcmoxe.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtagztavat.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yonumen.top/Article/details/gtgmxmtdkg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.9152youxi.cn/Article/details/gtslewnvze.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqpxhvhc.html

Ruby: a.gcd(b)
来源：http://dali.xinyue.icu/Article/details/gttenotltv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinghuilouyu.cn/Article/details/gteqzumemz.html

[N06] 判断回文字符串
来源：http://dali.ivvv.top/Article/details/gtlvsbkvjn.html

Py:   s == s[::-1]
来源：http://dali.cheryme.top/Article/details/gtrfmchtku.html

PHP:  $s === strrev($s);
来源：http://dali.ydzc1.top/Article/details/gtqkahiyeo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gtfipcqlgb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtddngzzug.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tian-w.cn/Article/details/gturllvbbd.html

Go:   // 双指针从两端比较
来源：http://dali.yueranfly.top/Article/details/gtimipzifo.html

Ruby: s == s.reverse
来源：http://dali.yj20258888.top/Article/details/gtyxhdoftj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xuetiantiany.cn/Article/details/gthrgltkkm.html

[N07] 两数之和（返回下标）
来源：http://dali.jqgfzy.top/Article/details/gtubqjtdyq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.kuanghao11.cn/Article/details/gtzejpdwmm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhongyouzk.top/Article/details/gtpvrufkaa.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yvedp.cn/Article/details/gtptcokapx.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinqigufen.top/Article/details/gtlkdkfvxd.html

Java: // 手写 HashMap
来源：http://dali.hongshengwenyu.top/Article/details/gtilqjvkmm.html

Go:   // 手写 map[int]int
来源：http://dali.snrcjt.cn/Article/details/gtogjtrwjo.html

Ruby: // 手写 Hash
来源：http://dali.kuanghao11.cn/Article/details/gtryqwlphk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dianchejie.cn/Article/details/gtnfcawpyf.html

[N08] 生成全排列
来源：http://dali.316326.xyz/Article/details/gtxqytwjoi.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtpjgvecot.html

PHP:  // 手写递归交换
来源：http://dali.jqgufenzy.top/Article/details/gtembmmtox.html

JS:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtcvmevqdj.html

TS:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtcialhihk.html

Java: // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtfwqtslwd.html

Go:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gttbxmrnkt.html

Ruby: arr.permutation.to_a
来源：http://dali.wangdashe.top/Article/details/gtayzgigro.html

C#:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtomagxnhl.html


<!-- 参考信息 -->