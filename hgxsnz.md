代发 wailian999

================================================================================
来源：http://dali.pycfn.com/Article/details/gtwhafqmgr.html

K. JSON 与序列化
来源：http://dali.daxiang520.top/Article/details/gtvpieddqh.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwlhfxtft.html

[K01] 对象转 JSON 字符串
来源：http://dali.xinyue.icu/Article/details/gthrpwgpww.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.redwolf501.top/Article/details/gtplresoqw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258888.top/Article/details/gtbyhbztpx.html

JS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzeervrtm.html

TS:   JSON.stringify(obj)
来源：http://dali.yonumen.top/Article/details/gtokxajkmm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj202588.top/Article/details/gtdkavngfd.html

Go:   json.Marshal(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtwwrhsuhm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj20258888.top/Article/details/gtqnmairzz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aizwys.cn/Article/details/gtlmsicmky.html

[K02] JSON 字符串转对象
来源：http://dali.pengpengdd.cyou/Article/details/gtguwemufh.html

Py:   json.loads(s)
来源：http://dali.zycfv.cn/Article/details/gtxwokwxsi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jiagoushi.top/Article/details/gtpgpwfqbb.html

JS:   JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gtjzwiftmg.html

TS:   JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gtfcuruuem.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.dashuyun.cn/Article/details/gtanixiffr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gtgdbuwawz.html

Ruby: JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gtlcdsmolj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fzhhl.top/Article/details/gtfyxnpbsy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gaohongyu789.top/Article/details/gtgkexbeoo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dianchejie.cn/Article/details/gtyrzrbtip.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gtbvziqecz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gttwztacxi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.vqdsnc.cn/Article/details/gtnzjxfeli.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.daria6918.cn/Article/details/gtrbkgospp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.316326.xyz/Article/details/gtlfyxhnww.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.iojbl.cn/Article/details/gtwmavfgwb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hongshengwenyu.top/Article/details/gtutpqpdkx.html

[K04] 读取 JSON 文件
来源：http://dali.jinqigfzy.top/Article/details/gtovdzirzm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gtqaummvaa.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yuxming.cn/Article/details/gtdctdtbxe.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuzjwlnjf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tian-w.cn/Article/details/gtbtivxsat.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtatpjnppj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xuanzx.com/Article/details/gtixuwahtr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj20258.top/Article/details/gtuemmigwq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.wangshuangyany.cn/Article/details/gtfoclexae.html

[K05] 深拷贝对象
来源：http://dali.wangdashe.top/Article/details/gtzxjcauan.html

Py:   copy.deepcopy(obj)
来源：http://dali.andypj.xyz/Article/details/gtrlrozath.html

PHP:  unserialize(serialize($obj));
来源：http://dali.316326.xyz/Article/details/gthtppyoav.html

JS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gthitcqdtr.html

TS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gtxoskrhhu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnxiangtu.top/Article/details/gtcmelyehs.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yuxming.cn/Article/details/gtawmizumn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.daxiang520.top/Article/details/gtutsxozsc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.snrcjt.cn/Article/details/gthwwgazqp.html

[K06] 解析 URL 查询串
来源：http://dali.shzxlz.cn/Article/details/gtbvjotcxy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tian-w.cn/Article/details/gtisgdsefy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hongshengwenyu.top/Article/details/gtftxqyhyr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ybcxt.top/Article/details/gtmatwqhfr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gtvziqvuhq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yongpay.top/Article/details/gteozeuzks.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gthyeerfqe.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gtewlexghx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gtcyqjynir.html

[K07] 进制转换
来源：http://dali.smart0.xyz/Article/details/gtdyhwamcy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtjzcdezzw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinghuilouyu.cn/Article/details/gtunrbtpqv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtvkpsdnbj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtnrkaarjb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gthpukacif.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zycfv.cn/Article/details/gtlposyokd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenzaomai.com/Article/details/gtptwuyoch.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtdlfvcrfv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhongyouzk.top/Article/details/gtlgxdvgui.html

Py:   pickle.dumps(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtiokvdqaq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cqqwz.cn/Article/details/gtbhejscnt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhoulong.xyz/Article/details/gtrlcawwlq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gtvtgcctdo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenjidiqi.icu/Article/details/gtnrwwwfhk.html

Go:   encoding/gob
来源：http://dali.fzhhl.top/Article/details/gtvrrhmjom.html

Ruby: Marshal.dump(obj)
来源：http://dali.cashguo.top/Article/details/gtltmynxqa.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xylfe.cn/Article/details/gtltqimrbp.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtyapswits.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gtuohtwjrz.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtkbodrzwx.html

[L01] 发送 GET 请求
来源：http://dali.ehwqpu.com/Article/details/gtxbskwbou.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zdqjudy.top/Article/details/gtnbffrcvb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yuanzhike.top/Article/details/gtujzphalu.html

JS:   await fetch(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gthfwfkrfn.html

TS:   await fetch(url)
来源：http://dali.daria6918.cn/Article/details/gtmrofnqzs.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.havefunace.top/Article/details/gtokjcuiux.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenlongwang.top/Article/details/gtmdsmgtpw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.c1oappe.top/Article/details/gtulruthov.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cheryme.top/Article/details/gtdaxaikhn.html

[L02] 发送 POST JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxnnyjrr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ivvv.top/Article/details/gtdgltfxfu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xziqi.cn/Article/details/gtnftxkcpk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258888.top/Article/details/gtiqeotnsq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gtpxswanbv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sxryk.cn/Article/details/gttkmczhhz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj20258888.top/Article/details/gtpuahfdzm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.wangshuangyany.cn/Article/details/gtgnihfrko.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gotoacloud.top/Article/details/gtcoiznapc.html

[L03] 设置自定义请求头
来源：http://dali.316326.xyz/Article/details/gtusfkmkta.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sxryk.cn/Article/details/gtiasqmyck.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ppjwa.cn/Article/details/gtvitsozdc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gtmwpsddqs.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gteylktjkz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jianghu66.top/Article/details/gtupgwxflk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shzxlz.cn/Article/details/gtaexmpblx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.guannengcc.top/Article/details/gtfudofzgj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.fengsongda.top/Article/details/gtfxmpsgfc.html

[L04] 设置超时
来源：http://dali.nwbrower.top/Article/details/gtqxomslze.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinqigufen.top/Article/details/gtfpchokit.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenlongwang.top/Article/details/gtdjesfxxe.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daria6918.cn/Article/details/gtmyrosrqd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenjidiqi.icu/Article/details/gtexfpurqw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jiagoushi.top/Article/details/gtjqgehrdy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.meibo888.top/Article/details/gtirkscmqo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.meibo888.top/Article/details/gthgoxlfqw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.bjfxy.top/Article/details/gtxoyxnafm.html

[L05] 上传文件（multipart）
来源：http://dali.ppjwa.cn/Article/details/gtrcjpwwca.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yvedp.cn/Article/details/gtwxyoitsn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.0kj1m.cn/Article/details/gtojwzvyws.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxuanxn.top/Article/details/gtrzlujjem.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.vqdsnc.cn/Article/details/gtijcfoqpz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.redwolf501.top/Article/details/gtsdgnyzbl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ivvv.top/Article/details/gteskhehmp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hnxiangtu.top/Article/details/gtkeckbgva.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxxcckskb.html

[L06] 解析响应为 JSON
来源：http://dali.yonumen.top/Article/details/gtiexlhulr.html

Py:   resp.json()
来源：http://dali.birdmap.top/Article/details/gtehrfuvte.html

PHP:  json_decode($body, true);
来源：http://dali.zycfv.cn/Article/details/gtjtrozhrh.html

JS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqiksozpd.html

TS:   await resp.json()
来源：http://dali.tianlin.xyz/Article/details/gtjgbxiuef.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtadlunrcl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daxiang520.top/Article/details/gtycjjbcfb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.redwolf501.top/Article/details/gtoizeaqnl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj20258888.top/Article/details/gththopoxj.html

[L07] 处理 HTTP 状态码
来源：http://dali.nanxinkj.top/Article/details/gtpjqjdbmo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yanxiufei.cn/Article/details/gtjweexayx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.pycfn.com/Article/details/gtfdbtgycu.html

JS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gtublvsfvx.html

TS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gtxygpxrqc.html

Java: resp.statusCode()
来源：http://dali.jianghu66.top/Article/details/gtbfehftjr.html

Go:   resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gtyvuvievx.html

Ruby: resp.code.to_i
来源：http://dali.fzhhl.top/Article/details/gtmqxqfpim.html

C#:   (int)resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gtugjmdefi.html

[L08] 并发请求多个地址
来源：http://dali.jianghu66.top/Article/details/gtukldyovq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhiwuduotai.top/Article/details/gthaykcwgy.html

PHP:  curl_multi_init() 系列
来源：http://dali.iojbl.cn/Article/details/gtdxxwnapr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gtnbyjqlwq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gtqlyrthhf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yanxiufei.cn/Article/details/gtbcfmxpil.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj20258.top/Article/details/gtvkrfvnyr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jiagoushi.top/Article/details/gtbwrhiswu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.havefunace.top/Article/details/gtwwdmbkzn.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtjzusftlm.html

M. 命令行 / 进程 / 环境
来源：http://dali.yuxming.cn/Article/details/gtblzxnomm.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtnsgjcwrt.html

[M01] 读取命令行参数
来源：http://dali.ivvv.top/Article/details/gtjlpjqxzl.html

Py:   sys.argv[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcxahnpq.html

PHP:  $argv;  $argc;
来源：http://dali.ydzc1.top/Article/details/gtbiqwplqq.html

JS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqnfusah.html

TS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gtbbpjmbol.html

Java: args 数组（main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gtmmlilghf.html

Go:   os.Args[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaiyfeili.html

Ruby: ARGV
来源：http://dali.hysaishi.cn/Article/details/gtszvejotn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangdashe.top/Article/details/gtkdvtvqlj.html

[M02] 读取环境变量
来源：http://dali.fzhhl.top/Article/details/gtsnocvqpr.html

Py:   os.environ.get("HOME")
来源：http://dali.aizwys.cn/Article/details/gtahqvzexy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258.top/Article/details/gtoxeoyrxl.html

JS:   process.env.HOME
来源：http://dali.ehwqpu.com/Article/details/gtcbjnnqrk.html

TS:   process.env.HOME
来源：http://dali.meibo888.top/Article/details/gtfgrqoajy.html

Java: System.getenv("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtpzhjmvis.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xylfe.cn/Article/details/gtoqkzhtmy.html

Ruby: ENV["HOME"]
来源：http://dali.ppjwa.cn/Article/details/gtdgxzasuq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sysykeji.top/Article/details/gterofnabu.html

[M03] 执行外部命令
来源：http://dali.zhoulong.xyz/Article/details/gtqgmjqewd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.kuanghao11.cn/Article/details/gtwjldjmqf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoudkfxfe.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gtbwlokkxr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtkwkofhin.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.pycfn.com/Article/details/gtxmsywqpb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hfpthk.cn/Article/details/gtycycechm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenlongwang.top/Article/details/gtplopkerg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nwbrower.top/Article/details/gtqnebfpqb.html

[M04] 获取当前工作目录
来源：http://dali.yvedp.cn/Article/details/gtucndpfdo.html

Py:   os.getcwd()
来源：http://dali.hysaishi.cn/Article/details/gtmsgcmpxa.html

PHP:  getcwd();
来源：http://dali.jiagoushi.top/Article/details/gtliwhcuud.html

JS:   process.cwd()
来源：http://dali.jianghu66.top/Article/details/gtfbwkmqzm.html

TS:   process.cwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnitvefoj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xziqi.cn/Article/details/gtvrtaywfh.html

Go:   os.Getwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtdzuxaqny.html

Ruby: Dir.pwd
来源：http://dali.9152youxi.cn/Article/details/gtrkinwjkn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.daxiang520.top/Article/details/gtafxfbton.html

[M05] 设置退出码
来源：http://dali.nwbrower.top/Article/details/gtvuaeibkz.html

Py:   sys.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtbzxrmhsd.html

PHP:  exit(1);
来源：http://dali.iojbl.cn/Article/details/gtyqkcfvsx.html

JS:   process.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtchiygduh.html

TS:   process.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtoxdzjyyz.html

Java: System.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtwjvekmpe.html

Go:   os.Exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtblbcyjvj.html

Ruby: exit 1
来源：http://dali.sxryk.cn/Article/details/gthgbllxji.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jiagoushi.top/Article/details/gtlprkhwko.html

[M06] 向标准错误输出
来源：http://dali.daria6918.cn/Article/details/gtzhautwch.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuetiantiany.cn/Article/details/gtabzhjvzz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zdqjudy.top/Article/details/gtetopewkw.html

JS:   console.error("err")
来源：http://dali.chenlongwang.top/Article/details/gtftsnfwvw.html

TS:   console.error("err")
来源：http://dali.zhoulong.xyz/Article/details/gtciluxzdh.html

Java: System.err.println("err")
来源：http://dali.tianlin.xyz/Article/details/gtqjnblnbh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.aizwys.cn/Article/details/gtxwwnpanl.html

Ruby: warn "err"
来源：http://dali.ppjwa.cn/Article/details/gtfqwiugny.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.birdmap.top/Article/details/gtgaawyjes.html

[M07] 判断是否为主入口
来源：http://dali.havefunace.top/Article/details/gtpmxurbax.html

Py:   if __name__ == "__main__":
来源：http://dali.shzxlz.cn/Article/details/gtuzsofjqs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ivvv.top/Article/details/gtvmgmdhcx.html

JS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gtqlfjfiba.html

TS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gtkisqcchy.html

Java: public static void main(String[] args)
来源：http://dali.c1oappe.top/Article/details/gtpwidppwk.html

Go:   func main()
来源：http://dali.sxryk.cn/Article/details/gtgjkpaztx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.vqdsnc.cn/Article/details/gtjduccpee.html

C#:   static void Main(string[] args)
来源：http://dali.0kj1m.cn/Article/details/gtmvcavnot.html

[M08] 获取系统与运行时信息
来源：http://dali.ppjwa.cn/Article/details/gtryttwifz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cdnleiting.top/Article/details/gtfqmslpqp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gzhubu.top/Article/details/gtxsjzhjez.html

JS:   process.platform;  process.version
来源：http://dali.jlsjyb.cn/Article/details/gtkryucapl.html

TS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gtmxrkxifm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.andypj.xyz/Article/details/gtwfjezumg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shzxlz.cn/Article/details/gtckogdpab.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hongshengwenyu.top/Article/details/gtmxhzgmph.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.snrcjt.cn/Article/details/gtommjqkkb.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtwtzryceu.html

N. 数据结构与算法
来源：http://dali.svipenyu.cn/Article/details/gtfoleuofa.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gthbhemtjs.html

[N01] 二分查找（有序数组）
来源：http://dali.chenzaomai.com/Article/details/gtfmiygnzm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtqeidrubc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sysykeji.top/Article/details/gtfzfycjej.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gtngtbqzwa.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.snrcjt.cn/Article/details/gtjnaosxnz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtulmxmqvy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtuicvuaxz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gaohongyu789.top/Article/details/gtuelrrhta.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdmbukycl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pengpengdd.cyou/Article/details/gtbotizcgf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cashguo.top/Article/details/gtphpleihi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgufenzy.top/Article/details/gtawcrkgwf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gtzglxqagn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtilzasulm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nanxuanxn.top/Article/details/gtmnhhgtgs.html

Go:   slices.Sort(arr)
来源：http://dali.sweek.top/Article/details/gtwxgfnscx.html

Ruby: arr.sort
来源：http://dali.jianghu66.top/Article/details/gtidyivsvw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shuidangran.top/Article/details/gtbegrwawi.html

[N03] 快速排序（分治示例）
来源：http://dali.tian-w.cn/Article/details/gtsvuwalyf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fzhhl.top/Article/details/gtxvpctzrk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hammf.cn/Article/details/gtderlmnzj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhoulong.xyz/Article/details/gtdzgbzzfl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ybcxt.top/Article/details/gtssxgpsdu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hysaishi.cn/Article/details/gtzpkvicem.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shanyushiyangtech.top/Article/details/gtpexhpwth.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shangyingyoupin.top/Article/details/gtgmoflche.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.haohaochexian.top/Article/details/gtdqdauzia.html

[N04] 斐波那契数列
来源：http://dali.gzhubu.top/Article/details/gteygxcjko.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigufen.top/Article/details/gtefijdksh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.guowangkeji.top/Article/details/gtnocrsdpw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gthhqdfopn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gtmrwyzgoj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yueranfly.top/Article/details/gtgdicnsmp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gtvnmnunao.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtexlslltx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gtqxfptohj.html

[N05] 最大公约数
来源：http://dali.ehwqpu.com/Article/details/gtwyqcrsrh.html

Py:   math.gcd(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gtdhvmrrrp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sweek.top/Article/details/gthqcjzwch.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.haohaochexian.top/Article/details/gtqvmohpcp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.kuanghao11.cn/Article/details/gtnvvqehrc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zdqjudy.top/Article/details/gtaumssdjq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gaohongyu789.top/Article/details/gtkulbxoyz.html

Ruby: a.gcd(b)
来源：http://dali.0kj1m.cn/Article/details/gtlejrlobz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtztlqlazj.html

[N06] 判断回文字符串
来源：http://dali.haohaochexian.top/Article/details/gtlzxyspax.html

Py:   s == s[::-1]
来源：http://dali.kuanghao11.cn/Article/details/gthgljmotw.html

PHP:  $s === strrev($s);
来源：http://dali.daria6918.cn/Article/details/gtbcgtrsee.html

JS:   s === [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gtuumaeopc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtupwmervn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yangfankeji.com/Article/details/gtedgskqdc.html

Go:   // 双指针从两端比较
来源：http://dali.ivvv.top/Article/details/gtxyrcsmec.html

Ruby: s == s.reverse
来源：http://dali.ehwqpu.com/Article/details/gtnoreqpns.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xuetiantiany.cn/Article/details/gtclqwduhm.html

[N07] 两数之和（返回下标）
来源：http://dali.chenzaomai.com/Article/details/gthqcsflkd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gtonqkbcdm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.9152youxi.cn/Article/details/gtvcioeufv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.guowangkeji.top/Article/details/gtgltmqloj.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinqigufen.top/Article/details/gtdihglgqs.html

Java: // 手写 HashMap
来源：http://dali.fengsongda.top/Article/details/gtoajduyef.html

Go:   // 手写 map[int]int
来源：http://dali.cqqwz.cn/Article/details/gtfrazeoqp.html

Ruby: // 手写 Hash
来源：http://dali.fzhhl.top/Article/details/gtdcoplrck.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhongyouzk.top/Article/details/gtnmpuwobc.html

[N08] 生成全排列
来源：http://dali.yonumen.top/Article/details/gtizhcdshz.html

Py:   itertools.permutations(arr)
来源：http://dali.meibo888.top/Article/details/gtwdkbuauq.html

PHP:  // 手写递归交换
来源：http://dali.xylfe.cn/Article/details/gtueqdjmqx.html

JS:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtalhdyphr.html

TS:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtahybiomc.html

Java: // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gtweezmwtf.html

Go:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtpjzfsujx.html

Ruby: arr.permutation.to_a
来源：http://dali.nwbrower.top/Article/details/gthbklnkmi.html

C#:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gthxjeevha.html


<!-- 参考信息 -->