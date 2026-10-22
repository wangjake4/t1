代发 wailian999

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.aizwys.cn/Article/details/gtuydfxzjc.html

Go:   json.Marshal(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtbjovzkdq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sufxvd.cn/Article/details/gtkhwqjpof.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cqqwz.cn/Article/details/gtjmcozryv.html

[K02] JSON 字符串转对象
来源：http://dali.fengsongda.top/Article/details/gttgwnfxxk.html

Py:   json.loads(s)
来源：http://dali.hywenlv.cn/Article/details/gtttkahowx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhiwuduotai.top/Article/details/gtjzvjvxvw.html

JS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gtsdjfdosx.html

TS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtubhoqpmr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.316326.xyz/Article/details/gtzegdjnmv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aibaodan.cn/Article/details/gtylsdfayp.html

Ruby: JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gtsymefeav.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhoulong.xyz/Article/details/gtnqyfycmo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ppjwa.cn/Article/details/gtvggluxua.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yanxiufei.cn/Article/details/gtfsyvgbax.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gtdpqlcnmz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gthfsggtpp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gtuyasekws.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ppjwa.cn/Article/details/gtctdanmyc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cucudq.cn/Article/details/gtpcifocmq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtucjvgkvo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hfpthk.cn/Article/details/gtgvnprocw.html

[K04] 读取 JSON 文件
来源：http://dali.shuidangran.top/Article/details/gtfkmjueup.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shangyingyoupin.top/Article/details/gtspfvehcf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ppjwa.cn/Article/details/gtkkexuvwf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yonumen.top/Article/details/gtrwkdjqmd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hysaishi.cn/Article/details/gtbofzsmek.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nwbrower.top/Article/details/gtjkunqtbh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cqqwz.cn/Article/details/gtaaaxshxo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pengpengdd.cyou/Article/details/gtktocbmyx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.bjfxy.top/Article/details/gthrxdisan.html

[K05] 深拷贝对象
来源：http://dali.zhengqikj.top/Article/details/gtmicrmvjv.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigufen.top/Article/details/gtzmetgtqs.html

PHP:  unserialize(serialize($obj));
来源：http://dali.meibo888.top/Article/details/gtxkdsnwvi.html

JS:   structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gtdukbruxu.html

TS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gtnilysaka.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gzhubu.top/Article/details/gtvxkknzdb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sysykeji.top/Article/details/gtkbfslops.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.iojbl.cn/Article/details/gtttmkqran.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.9152youxi.cn/Article/details/gtbzwowwuu.html

[K06] 解析 URL 查询串
来源：http://dali.yj20258888.top/Article/details/gtcchevomx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.wangdashe.top/Article/details/gtuyrktvae.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.0kj1m.cn/Article/details/gtkdhytdog.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hfpthk.cn/Article/details/gtmhebwuxp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gtsjimkpng.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hnxiangtu.top/Article/details/gtamwidwzr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gtvvizzoeg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gtclosqwfg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdpxrcquc.html

[K07] 进制转换
来源：http://dali.jiagoushi.top/Article/details/gtgiktfsii.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtvqsxunoj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj202588.top/Article/details/gtdruszzqv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtxnnlotom.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtpjyjscwm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtjheoyeha.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.mhx1999.top/Article/details/gtheevluti.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xylfe.cn/Article/details/gtjfcwjekd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gtejlbucbi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ppjwa.cn/Article/details/gtyaclowce.html

Py:   pickle.dumps(obj)
来源：http://dali.c1oappe.top/Article/details/gtmhvjasta.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.pycfn.com/Article/details/gtdffwsnpc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gtffxbgvrq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ybcxt.top/Article/details/gtfczexqvy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhixingplan.top/Article/details/gtvsjiinvs.html

Go:   encoding/gob
来源：http://dali.hammf.cn/Article/details/gtdaqtwurn.html

Ruby: Marshal.dump(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtjsqsodlm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gtjkumcaji.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtvglgbwpf.html

L. 网络请求
来源：http://dali.chenlongwang.top/Article/details/gtuksjbwwk.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtdfwstqgo.html

[L01] 发送 GET 请求
来源：http://dali.yvedp.cn/Article/details/gtaamkdqfi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yvedp.cn/Article/details/gtsndffkkx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.havefunace.top/Article/details/gthvlwmwzv.html

JS:   await fetch(url)
来源：http://dali.dashuyun.cn/Article/details/gtxaxfcxxv.html

TS:   await fetch(url)
来源：http://dali.hammf.cn/Article/details/gttoptxjus.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.c1oappe.top/Article/details/gtasssuqkq.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhongyouzk.top/Article/details/gtwtxhbbru.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.9152youxi.cn/Article/details/gtdxdtynpo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nwbrower.top/Article/details/gtlbdhamox.html

[L02] 发送 POST JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtmthlhurl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yuanzhike.top/Article/details/gtgnzwblrc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.iojbl.cn/Article/details/gtjqtvrskg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.birdmap.top/Article/details/gtpkbyzvup.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hammf.cn/Article/details/gtecczkdtp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sxryk.cn/Article/details/gtvcvwdkqm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.chenzaomai.com/Article/details/gtepqgqyjc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj20258.top/Article/details/gtkoortclk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcissktat.html

[L03] 设置自定义请求头
来源：http://dali.hongshengwenyu.top/Article/details/gtspcrbzcp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.mhx1999.top/Article/details/gtlcqgvgfm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gtxsoakpmi.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.c1oappe.top/Article/details/gtixwvwzzg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jyoumei.cn/Article/details/gtdjjhtqdo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.birdmap.top/Article/details/gtsztnszok.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cashguo.top/Article/details/gtihqzygot.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xinyue.icu/Article/details/gtmpngxpve.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yongpay.top/Article/details/gtbnydzmqx.html

[L04] 设置超时
来源：http://dali.jianghu66.top/Article/details/gtwemorkwf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.havefunace.top/Article/details/gtqzkxvbxl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.9152youxi.cn/Article/details/gtjeerruck.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hongshengwenyu.top/Article/details/gtriscwlza.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtznczlpfn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yonumen.top/Article/details/gtbwtxoffi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yvedp.cn/Article/details/gtnbsnfoxd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nanxuanxn.top/Article/details/gtlovqdlio.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cheryme.top/Article/details/gtejtcjwka.html

[L05] 上传文件（multipart）
来源：http://dali.yongpay.top/Article/details/gtxxpgooxy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ybcxt.top/Article/details/gtyzwnyeux.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hywenlv.cn/Article/details/gtatejrjio.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gtnjxjyczj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxuanxn.top/Article/details/gtqdfrrxgj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hysaishi.cn/Article/details/gtvqkwlwyj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ydzc1.top/Article/details/gtvphvktcd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dianchejie.cn/Article/details/gtgxipdphy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yongpay.top/Article/details/gtxwdfsnge.html

[L06] 解析响应为 JSON
来源：http://dali.sweek.top/Article/details/gtrgmscmbr.html

Py:   resp.json()
来源：http://dali.jinqigufen.top/Article/details/gtsqfqbckh.html

PHP:  json_decode($body, true);
来源：http://dali.jqgfzy.top/Article/details/gtwimpeqol.html

JS:   await resp.json()
来源：http://dali.cdnleiting.top/Article/details/gtphkiukxu.html

TS:   await resp.json()
来源：http://dali.hywenlv.cn/Article/details/gtqkkzknwn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.316326.xyz/Article/details/gtxkpqhnah.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhoulong.xyz/Article/details/gtfhjrjotc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhengqikj.top/Article/details/gtylmxbpxj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigufen.top/Article/details/gtbmfdzzch.html

[L07] 处理 HTTP 状态码
来源：http://dali.yongpay.top/Article/details/gtxwbulidr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvgvkmuod.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yanxiufei.cn/Article/details/gtypxxtbke.html

JS:   resp.ok;  resp.status
来源：http://dali.zhixingplan.top/Article/details/gtacurjzsv.html

TS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpyzkisqc.html

Java: resp.statusCode()
来源：http://dali.gzhubu.top/Article/details/gtntuaprrp.html

Go:   resp.StatusCode
来源：http://dali.yj20258888.top/Article/details/gtawmmcvoz.html

Ruby: resp.code.to_i
来源：http://dali.chenlongwang.top/Article/details/gtqfetwsvi.html

C#:   (int)resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gtczhsjhlh.html

[L08] 并发请求多个地址
来源：http://dali.guowangkeji.top/Article/details/gtdhovhtqd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.dashuyun.cn/Article/details/gtwvrmzqhx.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhoulong.xyz/Article/details/gtrvcxdzvn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gtqmuoqdgo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.mhx1999.top/Article/details/gtvutsutve.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yangfankeji.com/Article/details/gtfqtrunsl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hongshengwenyu.top/Article/details/gtnwvnhrvk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jlsjyb.cn/Article/details/gtrawgktib.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhengqikj.top/Article/details/gttbpdccaw.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtvoweeofg.html

M. 命令行 / 进程 / 环境
来源：http://dali.tanke756.top/Article/details/gtdsssipng.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtxmgvcgbk.html

[M01] 读取命令行参数
来源：http://dali.jyoumei.cn/Article/details/gtanensapr.html

Py:   sys.argv[1:]
来源：http://dali.hnxiangtu.top/Article/details/gtmcbcdlga.html

PHP:  $argv;  $argc;
来源：http://dali.jyoumei.cn/Article/details/gtdiplszlh.html

JS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gtzvxygofo.html

TS:   process.argv.slice(2)
来源：http://dali.xuetiantiany.cn/Article/details/gtqbcipbsg.html

Java: args 数组（main 方法参数）
来源：http://dali.andypj.xyz/Article/details/gtkilgwcja.html

Go:   os.Args[1:]
来源：http://dali.hysaishi.cn/Article/details/gtrtjhabev.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gtqsdirkjx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ybcxt.top/Article/details/gtcxvfsaey.html

[M02] 读取环境变量
来源：http://dali.cheryme.top/Article/details/gtkejkkuxk.html

Py:   os.environ.get("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gtopggtmda.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gtyjzdqmwk.html

JS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gttenajaar.html

TS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gtdtnghunf.html

Java: System.getenv("HOME")
来源：http://dali.fengsongda.top/Article/details/gtojtedckk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtynyxbeff.html

Ruby: ENV["HOME"]
来源：http://dali.jqgufenzy.top/Article/details/gtwaldlddx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfrqfcyhp.html

[M03] 执行外部命令
来源：http://dali.wangshuangyany.cn/Article/details/gtvuyytlcx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jyoumei.cn/Article/details/gtxkymcduk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hnxiangtu.top/Article/details/gtgirdjhjk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gtmubmpufv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhiwuduotai.top/Article/details/gtlyuwdmyl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gogol.net.cn/Article/details/gtspdaauip.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.redwolf501.top/Article/details/gtozbpvurl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.smart0.xyz/Article/details/gttgalmczg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhengqikj.top/Article/details/gtkwanibrj.html

[M04] 获取当前工作目录
来源：http://dali.gogol.net.cn/Article/details/gtodwpmflr.html

Py:   os.getcwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtswtrhmpu.html

PHP:  getcwd();
来源：http://dali.iojbl.cn/Article/details/gtyzhxofkq.html

JS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gtqwowoytb.html

TS:   process.cwd()
来源：http://dali.gogol.net.cn/Article/details/gtibpifizn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhiwuduotai.top/Article/details/gtdisgezeu.html

Go:   os.Getwd()
来源：http://dali.tian-w.cn/Article/details/gtqfrkfpmf.html

Ruby: Dir.pwd
来源：http://dali.xziqi.cn/Article/details/gtpparilsc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jyoumei.cn/Article/details/gtjgsqbfmy.html

[M05] 设置退出码
来源：http://dali.andypj.xyz/Article/details/gtlqzxryan.html

Py:   sys.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtvftjupbh.html

PHP:  exit(1);
来源：http://dali.guowangkeji.top/Article/details/gtmetjyiwm.html

JS:   process.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtqgquygbp.html

TS:   process.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtjzpigars.html

Java: System.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtlszxbkmd.html

Go:   os.Exit(1)
来源：http://dali.yuxming.cn/Article/details/gtiepefdqs.html

Ruby: exit 1
来源：http://dali.hammf.cn/Article/details/gtednztoei.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenlongwang.top/Article/details/gtmzkficgw.html

[M06] 向标准错误输出
来源：http://dali.xinyue.icu/Article/details/gtrdbofmbl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tian-w.cn/Article/details/gtyowrpcve.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.dianchejie.cn/Article/details/gtutjovfsd.html

JS:   console.error("err")
来源：http://dali.ybcxt.top/Article/details/gtyjajirke.html

TS:   console.error("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtyoeqwejf.html

Java: System.err.println("err")
来源：http://dali.jinqigufen.top/Article/details/gtvggmikju.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sweek.top/Article/details/gtvwkclxyb.html

Ruby: warn "err"
来源：http://dali.yangfankeji.com/Article/details/gtvpitdmgo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.316326.xyz/Article/details/gtnurccgqn.html

[M07] 判断是否为主入口
来源：http://dali.yueranfly.top/Article/details/gtbogbcvoj.html

Py:   if __name__ == "__main__":
来源：http://dali.xuetiantiany.cn/Article/details/gtmwjuvicy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yueranfly.top/Article/details/gttvmbrauo.html

JS:   require.main === module
来源：http://dali.zycfv.cn/Article/details/gtkijjxlvh.html

TS:   require.main === module
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuzsytihz.html

Java: public static void main(String[] args)
来源：http://dali.ybcxt.top/Article/details/gtqzluwudb.html

Go:   func main()
来源：http://dali.redwolf501.top/Article/details/gtvnwqhxgr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guannengcc.top/Article/details/gtggrpizsr.html

C#:   static void Main(string[] args)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgkrfpavc.html

[M08] 获取系统与运行时信息
来源：http://dali.fengsongda.top/Article/details/gtbplrqhxi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fzhhl.top/Article/details/gtysdagcvp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tanke756.top/Article/details/gtfydoxnkq.html

JS:   process.platform;  process.version
来源：http://dali.nwbrower.top/Article/details/gtmcmgeaip.html

TS:   process.platform;  process.version
来源：http://dali.yonumen.top/Article/details/gtieiyykje.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.316326.xyz/Article/details/gtzwywqpqr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shuidangran.top/Article/details/gtqytlnhoq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xinyue.icu/Article/details/gttfdghedn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinghuilouyu.cn/Article/details/gtpdxjbkhc.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtpymquuni.html

N. 数据结构与算法
来源：http://dali.tanke756.top/Article/details/gtqrdxhidx.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtatoelque.html

[N01] 二分查找（有序数组）
来源：http://dali.xziqi.cn/Article/details/gtgtknxpsf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtreyanota.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gtlgsvgkdb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwanysgal.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gtlbevtzof.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtklkmdanm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtcyeysgtx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gaohongyu789.top/Article/details/gtjrgwvrmk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtyljfdbeu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ppjwa.cn/Article/details/gtdcnffcuz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guowangkeji.top/Article/details/gtmvfwirfb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinqigfzy.top/Article/details/gtwtvrnstc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gtdyaxxrzg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gtfixwfwyc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjcmbkzaj.html

Go:   slices.Sort(arr)
来源：http://dali.jyoumei.cn/Article/details/gtctnsbhoo.html

Ruby: arr.sort
来源：http://dali.cashguo.top/Article/details/gtrzqvqceu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.0kj1m.cn/Article/details/gtgreclqiv.html

[N03] 快速排序（分治示例）
来源：http://dali.pycfn.com/Article/details/gtaoenhucu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenjidiqi.icu/Article/details/gtysfikxdj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenjidiqi.icu/Article/details/gtmnrbulli.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.0kj1m.cn/Article/details/gtsbhpkzlp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jiagoushi.top/Article/details/gtniypkmgh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ehwqpu.com/Article/details/gtvqzsmftw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yonumen.top/Article/details/gtdhmaodhu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhixingplan.top/Article/details/gtrhxrwcdg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.dashuyun.cn/Article/details/gtpzxyshxq.html

[N04] 斐波那契数列
来源：http://dali.jqgfzy.top/Article/details/gtiawomhiy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jyoumei.cn/Article/details/gtwbfopeia.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xylfe.cn/Article/details/gtjiepflqi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gtttdzsaza.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gtkpbryaey.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gtyrfnxviu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gogol.net.cn/Article/details/gtrwsvrmrt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtetcgjtog.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gtiqaurubi.html

[N05] 最大公约数
来源：http://dali.xuetiantiany.cn/Article/details/gttxmptunq.html

Py:   math.gcd(a, b)
来源：http://dali.yonumen.top/Article/details/gtjxpgtpmw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.dashuyun.cn/Article/details/gtnufwvkhc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxuanxn.top/Article/details/gtruoqiavn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.birdmap.top/Article/details/gtvnaiktzs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj20258888.top/Article/details/gtbwgvvpwo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yangfankeji.com/Article/details/gtawzrdaxm.html

Ruby: a.gcd(b)
来源：http://dali.aizwys.cn/Article/details/gtzflvkrhx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shzxlz.cn/Article/details/gtkjmepijc.html

[N06] 判断回文字符串
来源：http://dali.nanxuanxn.top/Article/details/gtwgzgtala.html

Py:   s == s[::-1]
来源：http://dali.jinqigfzy.top/Article/details/gtufrxloke.html

PHP:  $s === strrev($s);
来源：http://dali.jinqigfzy.top/Article/details/gtktqmahjh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtptqvpvki.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtmefyxffu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zycfv.cn/Article/details/gtseippngh.html

Go:   // 双指针从两端比较
来源：http://dali.jyoumei.cn/Article/details/gtxqacsblo.html

Ruby: s == s.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtqrlfkbxd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hammf.cn/Article/details/gthwixdzqm.html

[N07] 两数之和（返回下标）
来源：http://dali.daria6918.cn/Article/details/gtojnonwmo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xziqi.cn/Article/details/gtfnpfyfnx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shangyingyoupin.top/Article/details/gtukrydawz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jyoumei.cn/Article/details/gtozbuzafa.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhoulong.xyz/Article/details/gtjlzablvb.html

Java: // 手写 HashMap
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfshhaekv.html

Go:   // 手写 map[int]int
来源：http://dali.vqdsnc.cn/Article/details/gtdaapsbnf.html

Ruby: // 手写 Hash
来源：http://dali.sxryk.cn/Article/details/gtlgnlorqi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvmjtemj.html

[N08] 生成全排列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrywxeipf.html

Py:   itertools.permutations(arr)
来源：http://dali.ybcxt.top/Article/details/gtxeeujxhe.html

PHP:  // 手写递归交换
来源：http://dali.jinqigufen.top/Article/details/gtgxyrbmlm.html

JS:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtlyotldgl.html

TS:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gthposlrmx.html

Java: // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gthibbzxml.html

Go:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gteqjjydlt.html

Ruby: arr.permutation.to_a
来源：http://dali.yangfankeji.com/Article/details/gtgatwitbh.html

C#:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gttklphflk.html

[N09] 栈与队列
来源：http://dali.redwolf501.top/Article/details/gtmxkojeak.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ydzc1.top/Article/details/gtlloublsk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gttdrvpljx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.aizwys.cn/Article/details/gtyfowouqe.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jqgfzy.top/Article/details/gtfusqafzf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hysaishi.cn/Article/details/gtxoaxjpbq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.bjfxy.top/Article/details/gtjrknkbbk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoxufnrqv.html


<!-- 参考信息 -->