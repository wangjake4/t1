代发 wailian999

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nwbrower.top/Article/details/gtjwpoupbf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yanxiufei.cn/Article/details/gtvbljfrvw.html

JS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gtpdmyrfkz.html

TS:   JSON.stringify(obj)
来源：http://dali.daria6918.cn/Article/details/gtewwjkztl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj20258.top/Article/details/gtnnerbhzq.html

Go:   json.Marshal(obj)
来源：http://dali.xinyue.icu/Article/details/gtsxjkmldl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yangfankeji.com/Article/details/gtymdagkik.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtabmxovmd.html

[K02] JSON 字符串转对象
来源：http://dali.cdnleiting.top/Article/details/gttauxelnn.html

Py:   json.loads(s)
来源：http://dali.sweek.top/Article/details/gtfkapnves.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cdnleiting.top/Article/details/gtqibxfuyr.html

JS:   JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gtacxhwjzw.html

TS:   JSON.parse(s)
来源：http://dali.birdmap.top/Article/details/gtascchyby.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xuanzx.com/Article/details/gtmigvmknm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gtnojkglaa.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gtxturwkgm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ybcxt.top/Article/details/gtjddmsmwx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nanxuanxn.top/Article/details/gtzzoufbwq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tian-w.cn/Article/details/gtjxxoeunr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gtuiwmbues.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yongpay.top/Article/details/gtvqxsjklq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.snrcjt.cn/Article/details/gtcccbptzk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shuidangran.top/Article/details/gtyecpbziy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yvedp.cn/Article/details/gtkcclggtr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtgiwfzjkf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shuidangran.top/Article/details/gtmnminnnn.html

[K04] 读取 JSON 文件
来源：http://dali.c1oappe.top/Article/details/gteehevudg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tianlin.xyz/Article/details/gtvwsspmpf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ehwqpu.com/Article/details/gtehxvixie.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gtjvwefzaw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gtnghhttva.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xinyue.icu/Article/details/gtjegoaglg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhongyouzk.top/Article/details/gtkjombphm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nanxuanxn.top/Article/details/gtpnlwelwb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cheryme.top/Article/details/gtygaeqgtu.html

[K05] 深拷贝对象
来源：http://dali.vqdsnc.cn/Article/details/gtmyiavjmb.html

Py:   copy.deepcopy(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtoruoqsmx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.meibo888.top/Article/details/gttkpfcwck.html

JS:   structuredClone(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtcijhowkg.html

TS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gttudatcua.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhongyouzk.top/Article/details/gtjpiwtfik.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhoulong.xyz/Article/details/gteqgvolpv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.svipenyu.cn/Article/details/gtgigbrlyq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jqgfzy.top/Article/details/gtzklrvczh.html

[K06] 解析 URL 查询串
来源：http://dali.nanxinkj.top/Article/details/gtizcozoze.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gtnkdvaevw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jiagoushi.top/Article/details/gttxiwxupy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gtcqfhtsyl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnbnuuuwh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xziqi.cn/Article/details/gtrhdenunv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gttumewuxi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gtpmrjlhgq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtjrzlhyyk.html

[K07] 进制转换
来源：http://dali.zhoulong.xyz/Article/details/gtfdsfpsiw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtbncxpwal.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gotoacloud.top/Article/details/gtujkviown.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtdpzhdese.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtodoaahsm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtmdrtaejv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hnxiangtu.top/Article/details/gtscfzbqgn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.smart0.xyz/Article/details/gthzhpnrkk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gttecmhiaa.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yuanzhike.top/Article/details/gtbncphezc.html

Py:   pickle.dumps(obj)
来源：http://dali.chenzaomai.com/Article/details/gtzjpnofoi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yonumen.top/Article/details/gtzslvafde.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hysaishi.cn/Article/details/gtizfappyb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.snrcjt.cn/Article/details/gtzwkknswr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.dianchejie.cn/Article/details/gtdzebhept.html

Go:   encoding/gob
来源：http://dali.pycfn.com/Article/details/gtzzudxsmo.html

Ruby: Marshal.dump(obj)
来源：http://dali.havefunace.top/Article/details/gtyoeyxpzg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xylfe.cn/Article/details/gtmwzkwqwn.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtjaleaiww.html

L. 网络请求
来源：http://dali.zhengqikj.top/Article/details/gtrdphtnku.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtjiuhlqnx.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gtjxpwinii.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hammf.cn/Article/details/gttuwlnftn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnxiangtu.top/Article/details/gtnacwvqwu.html

JS:   await fetch(url)
来源：http://dali.hysaishi.cn/Article/details/gtwvorhgke.html

TS:   await fetch(url)
来源：http://dali.shuidangran.top/Article/details/gtcagqsalo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ydzc1.top/Article/details/gtdpfuconr.html

Go:   resp, err := http.Get(url)
来源：http://dali.vqdsnc.cn/Article/details/gtfbwsgtjc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.guannengcc.top/Article/details/gtukbklbbz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.iojbl.cn/Article/details/gtzymtknic.html

[L02] 发送 POST JSON
来源：http://dali.svipenyu.cn/Article/details/gtoczmmiwr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpoyqtim.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.vqdsnc.cn/Article/details/gtboshkjyk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gttoovqgxn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuanzhike.top/Article/details/gtqqreiefm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xuetiantiany.cn/Article/details/gtptgjaqnl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tianlin.xyz/Article/details/gtojdbczol.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yonumen.top/Article/details/gtggjeumhb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.feifeiyinyue.top/Article/details/gthmtbugrx.html

[L03] 设置自定义请求头
来源：http://dali.xuanzx.com/Article/details/gtawbmmtlk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nwbrower.top/Article/details/gtbhwzisfq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jiagoushi.top/Article/details/gtworipbxf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.smart0.xyz/Article/details/gtwsstjdjj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuanzx.com/Article/details/gtyjrhpmwk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhoulong.xyz/Article/details/gtoawoxogd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gtilueklng.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.feifeiyinyue.top/Article/details/gtkfkgggof.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sxryk.cn/Article/details/gtfiluyepb.html

[L04] 设置超时
来源：http://dali.mhx1999.top/Article/details/gtywbkgcdr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dianchejie.cn/Article/details/gtopyxgxwj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gtzxmhosvh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.meibo888.top/Article/details/gtxwyaozfo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gtktayroke.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtqyzcsbsx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.andypj.xyz/Article/details/gtptojczkz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.quarkkingdee.top/Article/details/gtwzsbbjoy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.9152youxi.cn/Article/details/gtdouizdqj.html

[L05] 上传文件（multipart）
来源：http://dali.pycfn.com/Article/details/gtqdyapbzf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnxiangtu.top/Article/details/gtnoqgbbaw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jqgufenzy.top/Article/details/gtqujjtvji.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ppjwa.cn/Article/details/gtzudxowum.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zdqjudy.top/Article/details/gtftupansy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jlsjyb.cn/Article/details/gtshebjbqx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cashguo.top/Article/details/gtppvzpyro.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.mhx1999.top/Article/details/gtffkzzrgh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gzhubu.top/Article/details/gtenctodms.html

[L06] 解析响应为 JSON
来源：http://dali.zhoulong.xyz/Article/details/gtntunwhri.html

Py:   resp.json()
来源：http://dali.nanxinkj.top/Article/details/gtpooadpdx.html

PHP:  json_decode($body, true);
来源：http://dali.tian-w.cn/Article/details/gtokbwjssr.html

JS:   await resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqhjfata.html

TS:   await resp.json()
来源：http://dali.zhengqikj.top/Article/details/gtopizfnrz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ydzc1.top/Article/details/gtkbqrkhdm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shuidangran.top/Article/details/gtmktwdcyy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yangfankeji.com/Article/details/gtmkgdjpff.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gotoacloud.top/Article/details/gtrybgyzqy.html

[L07] 处理 HTTP 状态码
来源：http://dali.jyoumei.cn/Article/details/gtthsnpejg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangtech.top/Article/details/gtyzqtfkgs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinqigfzy.top/Article/details/gthkfspgfo.html

JS:   resp.ok;  resp.status
来源：http://dali.zhongyouzk.top/Article/details/gtlrccefli.html

TS:   resp.ok;  resp.status
来源：http://dali.xziqi.cn/Article/details/gtfgmszvja.html

Java: resp.statusCode()
来源：http://dali.chenlongwang.top/Article/details/gthkynvzcb.html

Go:   resp.StatusCode
来源：http://dali.hnxiangtu.top/Article/details/gtvazqqmoo.html

Ruby: resp.code.to_i
来源：http://dali.yuxming.cn/Article/details/gtrbchgxlv.html

C#:   (int)resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gtbqllbldl.html

[L08] 并发请求多个地址
来源：http://dali.shuidangran.top/Article/details/gtbzjigozv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xinyue.icu/Article/details/gtwpbnmxph.html

PHP:  curl_multi_init() 系列
来源：http://dali.xinyue.icu/Article/details/gtbqsudqjj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jianghu66.top/Article/details/gtopyetykb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sweek.top/Article/details/gtqlwxmszo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hysaishi.cn/Article/details/gtbbbqtvcw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yvedp.cn/Article/details/gtulyenhrh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yvedp.cn/Article/details/gtmtedzdeo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gogol.net.cn/Article/details/gtdaeycyrm.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtuecgrwnv.html

M. 命令行 / 进程 / 环境
来源：http://dali.bjfxy.top/Article/details/gtpfqnwakh.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtoxhluluq.html

[M01] 读取命令行参数
来源：http://dali.aibaodan.cn/Article/details/gtncispiqa.html

Py:   sys.argv[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gtopbcdcqj.html

PHP:  $argv;  $argc;
来源：http://dali.zdqjudy.top/Article/details/gtkwcljekn.html

JS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gtyhizwrql.html

TS:   process.argv.slice(2)
来源：http://dali.cashguo.top/Article/details/gtowxarhgy.html

Java: args 数组（main 方法参数）
来源：http://dali.xylfe.cn/Article/details/gtshfsuzvr.html

Go:   os.Args[1:]
来源：http://dali.gzhubu.top/Article/details/gtlmjbyywe.html

Ruby: ARGV
来源：http://dali.ppjwa.cn/Article/details/gtyefehngu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.quarkkingdee.top/Article/details/gtjsjpdkot.html

[M02] 读取环境变量
来源：http://dali.ppjwa.cn/Article/details/gtzarwsxcq.html

Py:   os.environ.get("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gtsdpukqee.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sweek.top/Article/details/gtcrgofter.html

JS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gtbvpztcao.html

TS:   process.env.HOME
来源：http://dali.cdnleiting.top/Article/details/gtrnuplfmf.html

Java: System.getenv("HOME")
来源：http://dali.ybcxt.top/Article/details/gtgdpiblxe.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gtvhzpbdoc.html

Ruby: ENV["HOME"]
来源：http://dali.chenjidiqi.icu/Article/details/gtmqbnkqsd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gtxmdssrgy.html

[M03] 执行外部命令
来源：http://dali.nanxuanxn.top/Article/details/gtpctppzhe.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nwbrower.top/Article/details/gtjzylesiq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.9152youxi.cn/Article/details/gtmpwtnugu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.316326.xyz/Article/details/gtnnfzmvsy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.andypj.xyz/Article/details/gtyyayorxp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gtgegapbdp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenlongwang.top/Article/details/gtwwxrdgqk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenlongwang.top/Article/details/gtiqbprzdk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nwbrower.top/Article/details/gtayjwzlec.html

[M04] 获取当前工作目录
来源：http://dali.ppjwa.cn/Article/details/gtciafdbwf.html

Py:   os.getcwd()
来源：http://dali.shangyingyoupin.top/Article/details/gtvnyjkpwb.html

PHP:  getcwd();
来源：http://dali.haohaochexian.top/Article/details/gtzecbndqi.html

JS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gtvunqjlxk.html

TS:   process.cwd()
来源：http://dali.jqgfzy.top/Article/details/gtxmqhvqer.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjiltiseh.html

Go:   os.Getwd()
来源：http://dali.jianghu66.top/Article/details/gtveihaptw.html

Ruby: Dir.pwd
来源：http://dali.ydzc1.top/Article/details/gtoefhqruw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xinyue.icu/Article/details/gtrrkucznz.html

[M05] 设置退出码
来源：http://dali.dianchejie.cn/Article/details/gtrjmyswpg.html

Py:   sys.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtkasgpwyj.html

PHP:  exit(1);
来源：http://dali.mhx1999.top/Article/details/gthxiibbmr.html

JS:   process.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtrcqftoxx.html

TS:   process.exit(1)
来源：http://dali.cheryme.top/Article/details/gtbbhufzwv.html

Java: System.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtukfzehqs.html

Go:   os.Exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtnnovfpjw.html

Ruby: exit 1
来源：http://dali.yj202588.top/Article/details/gttdeldlms.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhiwuduotai.top/Article/details/gtkvsmhrzd.html

[M06] 向标准错误输出
来源：http://dali.xuanzx.com/Article/details/gtxsgfqzas.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yangfankeji.com/Article/details/gtqpvhmqhk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenjidiqi.icu/Article/details/gtzisgkmyo.html

JS:   console.error("err")
来源：http://dali.xuanzx.com/Article/details/gtrimcddpo.html

TS:   console.error("err")
来源：http://dali.zhixingplan.top/Article/details/gtylgkgnxp.html

Java: System.err.println("err")
来源：http://dali.cashguo.top/Article/details/gtsghgqkuj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj202588.top/Article/details/gtpxbybbxv.html

Ruby: warn "err"
来源：http://dali.feifeiyinyue.top/Article/details/gtatkvmgkh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.0kj1m.cn/Article/details/gtnvzpbphr.html

[M07] 判断是否为主入口
来源：http://dali.jinghuilouyu.cn/Article/details/gtaumolspw.html

Py:   if __name__ == "__main__":
来源：http://dali.ybcxt.top/Article/details/gtliuikoio.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hysaishi.cn/Article/details/gtzphcuemd.html

JS:   require.main === module
来源：http://dali.shzxlz.cn/Article/details/gtcigjusgh.html

TS:   require.main === module
来源：http://dali.ppjwa.cn/Article/details/gtowconoht.html

Java: public static void main(String[] args)
来源：http://dali.jiagoushi.top/Article/details/gtytgxclwy.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gtfpqlyhec.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhongyouzk.top/Article/details/gtphtoowpm.html

C#:   static void Main(string[] args)
来源：http://dali.ehwqpu.com/Article/details/gtgmtvavgn.html

[M08] 获取系统与运行时信息
来源：http://dali.xinyue.icu/Article/details/gtvvywweje.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hnxiangtu.top/Article/details/gtgkkbpmfz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tianlin.xyz/Article/details/gthedowmxe.html

JS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gtexorawlx.html

TS:   process.platform;  process.version
来源：http://dali.jlsjyb.cn/Article/details/gtycckpkgv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhiwuduotai.top/Article/details/gtduejrfoo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgufenzy.top/Article/details/gthjuwqaao.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gtbeqfwdbc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.pycfn.com/Article/details/gtvvdwoxah.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtfzpfuhup.html

N. 数据结构与算法
来源：http://dali.zdqjudy.top/Article/details/gtzlfuhdiy.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtmyxmwwpq.html

[N01] 二分查找（有序数组）
来源：http://dali.iojbl.cn/Article/details/gtyqihyjnw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtmxpaecak.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.svipenyu.cn/Article/details/gtyzmoeueg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ydzc1.top/Article/details/gtmgfmkijj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gtewwfhhfj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtjtwfjype.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtdiujuinx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cheryme.top/Article/details/gtqwedxdvc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtofiopkyc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.andypj.xyz/Article/details/gtqcauytrw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nwbrower.top/Article/details/gtrvqbvmlk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nanxuanxn.top/Article/details/gtnigpbyvd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gtumhtlmju.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gtcxqxtzlb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.iojbl.cn/Article/details/gtiuwztvux.html

Go:   slices.Sort(arr)
来源：http://dali.hammf.cn/Article/details/gtafdjxgex.html

Ruby: arr.sort
来源：http://dali.ydzc1.top/Article/details/gtuunusyit.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqantfhxf.html

[N03] 快速排序（分治示例）
来源：http://dali.sweek.top/Article/details/gtjvcdejjl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hywenlv.cn/Article/details/gtbchqjiuk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zdqjudy.top/Article/details/gtyevnayap.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yanxiufei.cn/Article/details/gtkmrkyvch.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jyoumei.cn/Article/details/gthoiewjqb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.birdmap.top/Article/details/gtdyuseeds.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinqigufen.top/Article/details/gttpxvcoca.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zdqjudy.top/Article/details/gtmdqgextu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hysaishi.cn/Article/details/gtewqpjsrb.html

[N04] 斐波那契数列
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwwhrvmm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.daria6918.cn/Article/details/gtugtyqwen.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.aizwys.cn/Article/details/gtkrmhpzki.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgufenzy.top/Article/details/gtbiujgsew.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gtaddzrucn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.birdmap.top/Article/details/gtvtojhujs.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jyoumei.cn/Article/details/gtkagvpwmb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jiagoushi.top/Article/details/gtkshzfmrb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gtctccorre.html

[N05] 最大公约数
来源：http://dali.dianchejie.cn/Article/details/gtmaiojjag.html

Py:   math.gcd(a, b)
来源：http://dali.fzhhl.top/Article/details/gtpcrxpvpb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xuanzx.com/Article/details/gtughqvjqt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gtkqkgzaas.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtdwdrbvpc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hnxiangtu.top/Article/details/gtjhwhgatx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.316326.xyz/Article/details/gtpmbfxdlg.html

Ruby: a.gcd(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlohwbzpd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtktjjczpl.html

[N06] 判断回文字符串
来源：http://dali.shuidangran.top/Article/details/gtffgcbrbe.html

Py:   s == s[::-1]
来源：http://dali.snrcjt.cn/Article/details/gtupuypove.html

PHP:  $s === strrev($s);
来源：http://dali.ydzc1.top/Article/details/gtuwgcvqyy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtkfhrphhx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtqvwuepex.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yanxiufei.cn/Article/details/gtrckzbvod.html

Go:   // 双指针从两端比较
来源：http://dali.zhoulong.xyz/Article/details/gtxrucqget.html

Ruby: s == s.reverse
来源：http://dali.yj202588.top/Article/details/gtbusnldjn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinqigfzy.top/Article/details/gtsqbewloo.html

[N07] 两数之和（返回下标）
来源：http://dali.xylfe.cn/Article/details/gtngmaspvy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.svipenyu.cn/Article/details/gtxtcxqhse.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ivvv.top/Article/details/gtzjmhxfee.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhengqikj.top/Article/details/gtvtknccyi.html

TS:   // 手写 Map<string, number>
来源：http://dali.jyoumei.cn/Article/details/gtkmxckgvj.html

Java: // 手写 HashMap
来源：http://dali.jqgfzy.top/Article/details/gtfdptqaen.html

Go:   // 手写 map[int]int
来源：http://dali.meibo888.top/Article/details/gtqzmyrsky.html

Ruby: // 手写 Hash
来源：http://dali.yvedp.cn/Article/details/gttkpeuicx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ydzc1.top/Article/details/gtcaxbcjly.html

[N08] 生成全排列
来源：http://dali.cdnleiting.top/Article/details/gtlcjeqred.html

Py:   itertools.permutations(arr)
来源：http://dali.nwbrower.top/Article/details/gteajjbaty.html

PHP:  // 手写递归交换
来源：http://dali.tian-w.cn/Article/details/gtxhknkrpt.html

JS:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gttgflvtvf.html

TS:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtotpuwzce.html

Java: // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gtrjfujrsz.html

Go:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtcwqoxwex.html

Ruby: arr.permutation.to_a
来源：http://dali.ppjwa.cn/Article/details/gtnyqknsll.html

C#:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtdkxsciva.html

[N09] 栈与队列
来源：http://dali.gzhubu.top/Article/details/gttuowkagc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sufxvd.cn/Article/details/gtzmlpddtw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnqzz.top/Article/details/gtgadsvumb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj20258888.top/Article/details/gtkcpixtog.html


<!-- 参考信息 -->