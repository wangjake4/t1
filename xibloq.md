代发 wailian999

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdkcdzjyi.html

K. JSON 与序列化
来源：http://dali.daria6918.cn/Article/details/gtcrppdisq.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtcrzjaalm.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj202588.top/Article/details/gtwozmmbme.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj20258.top/Article/details/gtyiofaelg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hnxiangtu.top/Article/details/gtjxxgqzzv.html

JS:   JSON.stringify(obj)
来源：http://dali.hysaishi.cn/Article/details/gteebuydpp.html

TS:   JSON.stringify(obj)
来源：http://dali.chenzaomai.com/Article/details/gttzhdbxuv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinghuilouyu.cn/Article/details/gtguhgsgxb.html

Go:   json.Marshal(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtsannsabf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yueranfly.top/Article/details/gtlfktqpzv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenzaomai.com/Article/details/gtlowglwgp.html

[K02] JSON 字符串转对象
来源：http://dali.yanxiufei.cn/Article/details/gtiirlfiea.html

Py:   json.loads(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtyhfxyvhc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenlongwang.top/Article/details/gtmdusykgt.html

JS:   JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gtvxhmnoux.html

TS:   JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gtfgvgianx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tian-w.cn/Article/details/gtxategzxx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhoulong.xyz/Article/details/gtqiemnqkx.html

Ruby: JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gtawwsfjjw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258888.top/Article/details/gtwrhovxsk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.wangdashe.top/Article/details/gtrjbatjvn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hfpthk.cn/Article/details/gthlfujbzz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fengsongda.top/Article/details/gtydahktse.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtlepqxych.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gthafybeyb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zdqjudy.top/Article/details/gthzyieknm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ydzc1.top/Article/details/gtihzufbwq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.meibo888.top/Article/details/gtzfcgcxiv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jlsjyb.cn/Article/details/gtyemkwppy.html

[K04] 读取 JSON 文件
来源：http://dali.ppjwa.cn/Article/details/gtclroubwi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sxryk.cn/Article/details/gtusphhqrk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.smart0.xyz/Article/details/gtkgfeqsax.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gtpppbmszk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.meibo888.top/Article/details/gtwykilxtp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxncziuto.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.pengpengdd.cyou/Article/details/gtzxnilvkx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gtgdgeskru.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gteufaixhx.html

[K05] 深拷贝对象
来源：http://dali.ydzc1.top/Article/details/gtmjvoroib.html

Py:   copy.deepcopy(obj)
来源：http://dali.hysaishi.cn/Article/details/gtunszhqxa.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hnqzz.top/Article/details/gtjeiogefq.html

JS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gtaodkpuna.html

TS:   structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gtltcbmzzi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigufen.top/Article/details/gtybksgvfb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinqigufen.top/Article/details/gtfgtyqbag.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cdnleiting.top/Article/details/gtimdqsjlh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.dashuyun.cn/Article/details/gtdrgivtlk.html

[K06] 解析 URL 查询串
来源：http://dali.xziqi.cn/Article/details/gtrjpthptm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yonumen.top/Article/details/gtjxhhpxsl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gaohongyu789.top/Article/details/gtfkjeqlgh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxinkj.top/Article/details/gtkcctgdri.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtalytmbgk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.daria6918.cn/Article/details/gtllczlwtz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gtejhptfzu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gtzqmzrfti.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gtedosnlug.html

[K07] 进制转换
来源：http://dali.bjfxy.top/Article/details/gtidigaybf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtdojmifqy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmtdbhyd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtebhaczox.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtotopiqbk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtcqhrcpko.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jianghu66.top/Article/details/gtovdlyhar.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pycfn.com/Article/details/gtisiitchj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtookhqydm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cqqwz.cn/Article/details/gtnbfpqoyb.html

Py:   pickle.dumps(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtzqjbvcim.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xziqi.cn/Article/details/gtzljzwfpv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ehwqpu.com/Article/details/gtfyossnaa.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jiagoushi.top/Article/details/gtaiqfxvhh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.feifeiyinyue.top/Article/details/gtgckmztvc.html

Go:   encoding/gob
来源：http://dali.xylfe.cn/Article/details/gtseklxdny.html

Ruby: Marshal.dump(obj)
来源：http://dali.xylfe.cn/Article/details/gtpkxhsstm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gttxzzzefu.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtvzkvtznp.html

L. 网络请求
来源：http://dali.nwbrower.top/Article/details/gthswpvpeh.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtsnghxhnz.html

[L01] 发送 GET 请求
来源：http://dali.yanxiufei.cn/Article/details/gtvrsongrc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenjidiqi.icu/Article/details/gtbrkvrjcr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.pycfn.com/Article/details/gtmayamopx.html

JS:   await fetch(url)
来源：http://dali.mhx1999.top/Article/details/gtzmnveipu.html

TS:   await fetch(url)
来源：http://dali.dashuyun.cn/Article/details/gtvkpsxhcu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.wangdashe.top/Article/details/gtfufhuqcx.html

Go:   resp, err := http.Get(url)
来源：http://dali.aizwys.cn/Article/details/gtjjtbxrqv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsgkrtmto.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nanxinkj.top/Article/details/gtsujopnfq.html

[L02] 发送 POST JSON
来源：http://dali.hfpthk.cn/Article/details/gtkaalfanu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrcuakpqn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.meibo888.top/Article/details/gtkhbsvils.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuanzhike.top/Article/details/gtucwhycyt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangdashe.top/Article/details/gtmtakplte.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.pycfn.com/Article/details/gtutpgaenk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ydzc1.top/Article/details/gtuemirnjg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yuanzhike.top/Article/details/gttmcrmfkx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinqigfzy.top/Article/details/gtemntmenn.html

[L03] 设置自定义请求头
来源：http://dali.nanxinkj.top/Article/details/gtrmrrunyj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shzxlz.cn/Article/details/gtjzzezonk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.svipenyu.cn/Article/details/gtkwfrknoj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.316326.xyz/Article/details/gtcebizzxl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.birdmap.top/Article/details/gtabwmcgif.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hywenlv.cn/Article/details/gtmrgnofdc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gtensqjdpw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.mhx1999.top/Article/details/gtngpkhirg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.dashuyun.cn/Article/details/gtqowsuwmy.html

[L04] 设置超时
来源：http://dali.hammf.cn/Article/details/gtqvyunmur.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yanxiufei.cn/Article/details/gtzywhmwgu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nanxinkj.top/Article/details/gtegxwyict.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sysykeji.top/Article/details/gtfyjnbjjk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yueranfly.top/Article/details/gtsqarirro.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj20258888.top/Article/details/gtdwoxfrqs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hammf.cn/Article/details/gtntmjjlrb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258888.top/Article/details/gtvkjdftmk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.fzhhl.top/Article/details/gtdlrvqdyd.html

[L05] 上传文件（multipart）
来源：http://dali.yueranfly.top/Article/details/gtfmvihukf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shangyingyoupin.top/Article/details/gtunudwqox.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zycfv.cn/Article/details/gtaipycowb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pengpengdd.cyou/Article/details/gtxyqdfjxn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gtndzsdsnt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nanxinkj.top/Article/details/gtsauerxvv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shzxlz.cn/Article/details/gtzklswaqd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj20258.top/Article/details/gtzqlphhww.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtfyhnmotc.html

[L06] 解析响应为 JSON
来源：http://dali.wangshuangyany.cn/Article/details/gtgwyhrbrc.html

Py:   resp.json()
来源：http://dali.sysykeji.top/Article/details/gtbkotvgug.html

PHP:  json_decode($body, true);
来源：http://dali.zhengqikj.top/Article/details/gteemnzjzm.html

JS:   await resp.json()
来源：http://dali.birdmap.top/Article/details/gtzhubkhoy.html

TS:   await resp.json()
来源：http://dali.0kj1m.cn/Article/details/gtvvdkidjw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gtsksqvein.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ivvv.top/Article/details/gtxgkupmhy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnqzz.top/Article/details/gtuizvhhiy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yueranfly.top/Article/details/gtshtonfaz.html

[L07] 处理 HTTP 状态码
来源：http://dali.xziqi.cn/Article/details/gtbefynhdx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yueranfly.top/Article/details/gtchxvwhix.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zycfv.cn/Article/details/gtliodbugn.html

JS:   resp.ok;  resp.status
来源：http://dali.guannengcc.top/Article/details/gtvlzhpumk.html

TS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gtrbzeadpa.html

Java: resp.statusCode()
来源：http://dali.tianlin.xyz/Article/details/gtiplysqow.html

Go:   resp.StatusCode
来源：http://dali.jqgfzy.top/Article/details/gtingcbxry.html

Ruby: resp.code.to_i
来源：http://dali.pycfn.com/Article/details/gtpzoferay.html

C#:   (int)resp.StatusCode
来源：http://dali.wangshuangyany.cn/Article/details/gtkjltcodg.html

[L08] 并发请求多个地址
来源：http://dali.nanxuanxn.top/Article/details/gtsxuadujx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yongpay.top/Article/details/gtzkrgjzgb.html

PHP:  curl_multi_init() 系列
来源：http://dali.jqgfzy.top/Article/details/gtlkzqngkx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gtosmzzhwa.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gtejgbnzud.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmucnwsk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdqeblee.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.feifeiyinyue.top/Article/details/gttffjhtaq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yangfankeji.com/Article/details/gthhrfnxmv.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtfufpmddz.html

M. 命令行 / 进程 / 环境
来源：http://dali.dianchejie.cn/Article/details/gtzoiphmja.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtwgssiczz.html

[M01] 读取命令行参数
来源：http://dali.zhongyouzk.top/Article/details/gttzokmgja.html

Py:   sys.argv[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtescinbkt.html

PHP:  $argv;  $argc;
来源：http://dali.yj202588.top/Article/details/gtsjivwqkx.html

JS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gtnrmagjom.html

TS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gtkcgzlcmb.html

Java: args 数组（main 方法参数）
来源：http://dali.andypj.xyz/Article/details/gtfppscgdh.html

Go:   os.Args[1:]
来源：http://dali.daxiang520.top/Article/details/gtgdglhaus.html

Ruby: ARGV
来源：http://dali.bjfxy.top/Article/details/gtldksgzag.html

C#:   args 数组（Main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gtjakgkoez.html

[M02] 读取环境变量
来源：http://dali.redwolf501.top/Article/details/gtmdsjsjuk.html

Py:   os.environ.get("HOME")
来源：http://dali.yongpay.top/Article/details/gtvfdbzlxb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xylfe.cn/Article/details/gtquddckuk.html

JS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gteaevtizc.html

TS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gtobvdfely.html

Java: System.getenv("HOME")
来源：http://dali.tianlin.xyz/Article/details/gtwczmlzop.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.guannengcc.top/Article/details/gtlwfsrwez.html

Ruby: ENV["HOME"]
来源：http://dali.snrcjt.cn/Article/details/gtffawlchj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daxiang520.top/Article/details/gtfjbnzcgj.html

[M03] 执行外部命令
来源：http://dali.zhongyouzk.top/Article/details/gtophdlrvd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.redwolf501.top/Article/details/gtbccnrjip.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sysykeji.top/Article/details/gtmngkdjff.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gtobbdwdoh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gtcnzwkkgu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.vqdsnc.cn/Article/details/gtlszyeioj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.haohaochexian.top/Article/details/gtypiuwrxg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj202588.top/Article/details/gtpfjqumja.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hnqzz.top/Article/details/gtcictbrie.html

[M04] 获取当前工作目录
来源：http://dali.chenzaomai.com/Article/details/gthoktnspw.html

Py:   os.getcwd()
来源：http://dali.zhoulong.xyz/Article/details/gtyefmmcdl.html

PHP:  getcwd();
来源：http://dali.pengpengdd.cyou/Article/details/gturxdwvvz.html

JS:   process.cwd()
来源：http://dali.ehwqpu.com/Article/details/gtbznothtg.html

TS:   process.cwd()
来源：http://dali.cheryme.top/Article/details/gtkvdhvtpd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gtznydvjka.html

Go:   os.Getwd()
来源：http://dali.xuanzx.com/Article/details/gtbgzrnath.html

Ruby: Dir.pwd
来源：http://dali.yangfankeji.com/Article/details/gthqtbrtuu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj20258.top/Article/details/gteofvlkxm.html

[M05] 设置退出码
来源：http://dali.jqgufenzy.top/Article/details/gtyjshmeua.html

Py:   sys.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaoiwepeg.html

PHP:  exit(1);
来源：http://dali.yonumen.top/Article/details/gtacfyadkw.html

JS:   process.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtxctmjydl.html

TS:   process.exit(1)
来源：http://dali.yonumen.top/Article/details/gtqxdizphj.html

Java: System.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtddgxxucb.html

Go:   os.Exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtldaaambp.html

Ruby: exit 1
来源：http://dali.hfpthk.cn/Article/details/gtlbkexekp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yvedp.cn/Article/details/gtehyzwbej.html

[M06] 向标准错误输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuhhgjuvc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhoulong.xyz/Article/details/gtxoqbubtk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cheryme.top/Article/details/gtiyrcvaye.html

JS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gtktmgprcy.html

TS:   console.error("err")
来源：http://dali.hfpthk.cn/Article/details/gtrclecpnd.html

Java: System.err.println("err")
来源：http://dali.gaohongyu789.top/Article/details/gtosgsosgf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yueranfly.top/Article/details/gtfpgspafe.html

Ruby: warn "err"
来源：http://dali.smart0.xyz/Article/details/gtiekwagtk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhoulong.xyz/Article/details/gtgkdysvoq.html

[M07] 判断是否为主入口
来源：http://dali.yj20258888.top/Article/details/gthpqxkxmi.html

Py:   if __name__ == "__main__":
来源：http://dali.hnxiangtu.top/Article/details/gtfrwoanbu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.snrcjt.cn/Article/details/gthxyzlrni.html

JS:   require.main === module
来源：http://dali.cashguo.top/Article/details/gtogvmjdkh.html

TS:   require.main === module
来源：http://dali.cdnleiting.top/Article/details/gtwcwofaip.html

Java: public static void main(String[] args)
来源：http://dali.meibo888.top/Article/details/gtekwlmtcc.html

Go:   func main()
来源：http://dali.cdnleiting.top/Article/details/gtwhaccyke.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinghuilouyu.cn/Article/details/gtmtamvown.html

C#:   static void Main(string[] args)
来源：http://dali.daxiang520.top/Article/details/gtsaplthxu.html

[M08] 获取系统与运行时信息
来源：http://dali.guannengcc.top/Article/details/gtzbgknvdr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.dashuyun.cn/Article/details/gtcpvoddbh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jyoumei.cn/Article/details/gtougzxjsl.html

JS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gtupmuaoac.html

TS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gtshqimvng.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sufxvd.cn/Article/details/gtnzfcrlvw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.iojbl.cn/Article/details/gtlzqmvhfb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigufen.top/Article/details/gtkvpwfrrt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuetiantiany.cn/Article/details/gtfuxlreja.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtpqojcnyt.html

N. 数据结构与算法
来源：http://dali.nanxuanxn.top/Article/details/gtaqpgmuaq.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjyutmaj.html

[N01] 二分查找（有序数组）
来源：http://dali.guowangkeji.top/Article/details/gtlutcvfom.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtkkomxkkg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.guannengcc.top/Article/details/gtkjnvanlp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gtoladoowm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shzxlz.cn/Article/details/gtjwjijfnw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtjdpwwtxr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtcnkvwpsq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258888.top/Article/details/gtcczctwjn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtpwzzlugd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jyoumei.cn/Article/details/gtcghtqkui.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.snrcjt.cn/Article/details/gthfdjsmvu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.redwolf501.top/Article/details/gtazuuslxl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gtjivhrpyf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gtnzvhahir.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.vqdsnc.cn/Article/details/gtapmhqjzv.html

Go:   slices.Sort(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtnptwfjuq.html

Ruby: arr.sort
来源：http://dali.zhongyouzk.top/Article/details/gtpmfbnfsb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jlsjyb.cn/Article/details/gtsahreecf.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangtech.top/Article/details/gtjomigztg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tanke756.top/Article/details/gtnwzmdiho.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xziqi.cn/Article/details/gtkrsiswtu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinghuilouyu.cn/Article/details/gtefbzkovh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cdnleiting.top/Article/details/gtareldrwp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gtqcmxblma.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yvedp.cn/Article/details/gtkehmoncg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shuidangran.top/Article/details/gtyblrswpp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ydzc1.top/Article/details/gtnxgpndjk.html

[N04] 斐波那契数列
来源：http://dali.cqqwz.cn/Article/details/gtzyajwetp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgufenzy.top/Article/details/gtvjredwsd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gttmyzlttv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gtttbhqlyo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gtpahlduoe.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ehwqpu.com/Article/details/gtewpvrrox.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinqigfzy.top/Article/details/gtzbtbvban.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gaohongyu789.top/Article/details/gtyrbtwnsj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gtkysagmdm.html

[N05] 最大公约数
来源：http://dali.snrcjt.cn/Article/details/gtviihtoml.html

Py:   math.gcd(a, b)
来源：http://dali.fengsongda.top/Article/details/gtfoucgstb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.smart0.xyz/Article/details/gtqlljlqwo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gtesblmltr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gtwfacjkxw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zycfv.cn/Article/details/gtvqqwdivp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yuanzhike.top/Article/details/gtjiqeskox.html

Ruby: a.gcd(b)
来源：http://dali.hammf.cn/Article/details/gtnwjkvbfh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ydzc1.top/Article/details/gttfzmufjv.html

[N06] 判断回文字符串
来源：http://dali.yvedp.cn/Article/details/gtpeolboeb.html

Py:   s == s[::-1]
来源：http://dali.jqgfzy.top/Article/details/gtgjqirvff.html

PHP:  $s === strrev($s);
来源：http://dali.hnqzz.top/Article/details/gtvwedkrua.html

JS:   s === [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtflghrvzy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gtghnnkcin.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.9152youxi.cn/Article/details/gtufmvowot.html

Go:   // 双指针从两端比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbolmhicx.html

Ruby: s == s.reverse
来源：http://dali.aizwys.cn/Article/details/gtfhvnnwto.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xuanzx.com/Article/details/gtftfqmvwy.html

[N07] 两数之和（返回下标）
来源：http://dali.jinqigfzy.top/Article/details/gtiwcbkpgg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zdqjudy.top/Article/details/gtxqpxohxx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hywenlv.cn/Article/details/gtynujgnrk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shzxlz.cn/Article/details/gtttlmdhch.html

TS:   // 手写 Map<string, number>
来源：http://dali.dianchejie.cn/Article/details/gtiefngztd.html

Java: // 手写 HashMap
来源：http://dali.yuxming.cn/Article/details/gteasniqgq.html

Go:   // 手写 map[int]int
来源：http://dali.shangyingyoupin.top/Article/details/gthhkdfxyh.html

Ruby: // 手写 Hash
来源：http://dali.hnqzz.top/Article/details/gtdiwikstx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuanzx.com/Article/details/gthmetlaen.html

[N08] 生成全排列
来源：http://dali.0kj1m.cn/Article/details/gtkwdvirpp.html

Py:   itertools.permutations(arr)
来源：http://dali.yj20258888.top/Article/details/gtdiqyoncw.html

PHP:  // 手写递归交换
来源：http://dali.guannengcc.top/Article/details/gtzpcttiwh.html

JS:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtdleftsjo.html

TS:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtpmcqhmtf.html

Java: // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtivmehibs.html

Go:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtvnimmrem.html

Ruby: arr.permutation.to_a
来源：http://dali.yueranfly.top/Article/details/gtrtpflwgz.html

C#:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwyjmijxx.html


<!-- 参考信息 -->