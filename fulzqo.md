代发 wailian999

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jianghu66.top/Article/details/gtddiywsik.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigfzy.top/Article/details/gtmdxkxefz.html

JS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtuzlouvxz.html

TS:   JSON.stringify(obj)
来源：http://dali.cdnleiting.top/Article/details/gtoegnzqso.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangtech.top/Article/details/gtkvtnzafq.html

Go:   json.Marshal(obj)
来源：http://dali.daxiang520.top/Article/details/gtkzyyxgic.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cdnleiting.top/Article/details/gtxzniriul.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ybcxt.top/Article/details/gtjkfvzwom.html

[K02] JSON 字符串转对象
来源：http://dali.xuetiantiany.cn/Article/details/gtwsbkmiye.html

Py:   json.loads(s)
来源：http://dali.daria6918.cn/Article/details/gtwakhvaln.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.dashuyun.cn/Article/details/gtnakfkofa.html

JS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gtqabmesun.html

TS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtwkdiacpl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gtgarluhlx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shangyingyoupin.top/Article/details/gtoxbmvsey.html

Ruby: JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gtmqtpfpzw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xziqi.cn/Article/details/gtelykxgdi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jqgfzy.top/Article/details/gtrukitzno.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhixingplan.top/Article/details/gtpiitecfq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zdqjudy.top/Article/details/gtwahubkhi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cqqwz.cn/Article/details/gthbeelypr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gtbyiryazn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yvedp.cn/Article/details/gtgxrtmuqh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.daria6918.cn/Article/details/gttmmfebjj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhixingplan.top/Article/details/gtsoiefrfk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuxming.cn/Article/details/gtugnzmtvc.html

[K04] 读取 JSON 文件
来源：http://dali.yj202588.top/Article/details/gthvrjsnfm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.iojbl.cn/Article/details/gtusqazmvp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghbytijr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ppjwa.cn/Article/details/gtzcrvxwyh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gtnomectjd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yangfankeji.com/Article/details/gttcdoxvny.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yanxiufei.cn/Article/details/gtypapjpbg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xylfe.cn/Article/details/gtiislrhqd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj20258888.top/Article/details/gtflltevqk.html

[K05] 深拷贝对象
来源：http://dali.birdmap.top/Article/details/gtwswjwbrd.html

Py:   copy.deepcopy(obj)
来源：http://dali.redwolf501.top/Article/details/gtuprkmpyk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.iojbl.cn/Article/details/gtxxrdyozc.html

JS:   structuredClone(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtazjvuugf.html

TS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gtegudfuyk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.havefunace.top/Article/details/gtnvlvxswq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.0kj1m.cn/Article/details/gtsfbbwbgz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shzxlz.cn/Article/details/gttsmfoqzl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwupeerbu.html

[K06] 解析 URL 查询串
来源：http://dali.guowangkeji.top/Article/details/gtmecjglmr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj202588.top/Article/details/gtwygxxsrv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.fengsongda.top/Article/details/gtzfxgjrlj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangdashe.top/Article/details/gtditupips.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gtoxchwfrr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj202588.top/Article/details/gtdgjezywj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gtyriodrap.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gtioddjfta.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtdsfgeyvf.html

[K07] 进制转换
来源：http://dali.fengsongda.top/Article/details/gtkuyucwgf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdyoywqi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cqqwz.cn/Article/details/gteqtnruru.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtradaedum.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtczuzpyyn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtyldcllue.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.wangdashe.top/Article/details/gtjmldkgnt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jiagoushi.top/Article/details/gtnlkeerad.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtfgymmgdn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ydzc1.top/Article/details/gtfeseusof.html

Py:   pickle.dumps(obj)
来源：http://dali.hnqzz.top/Article/details/gtskkmynzn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.snrcjt.cn/Article/details/gtngkdskbi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jlsjyb.cn/Article/details/gtstufnzue.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yvedp.cn/Article/details/gtjouuinqk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.daria6918.cn/Article/details/gtlepvliok.html

Go:   encoding/gob
来源：http://dali.feifeiyinyue.top/Article/details/gtbitzfggv.html

Ruby: Marshal.dump(obj)
来源：http://dali.yuanzhike.top/Article/details/gtiyhobtyz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gtvwzhqloz.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtbtjuexxr.html

L. 网络请求
来源：http://dali.chenzaomai.com/Article/details/gtbmqbudci.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gttyktthkq.html

[L01] 发送 GET 请求
来源：http://dali.cashguo.top/Article/details/gtdcicnbrf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cheryme.top/Article/details/gterilgcyi.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenlongwang.top/Article/details/gthqtathdf.html

JS:   await fetch(url)
来源：http://dali.hnxiangtu.top/Article/details/gtugeigbrw.html

TS:   await fetch(url)
来源：http://dali.jyoumei.cn/Article/details/gtvmvmblpp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cashguo.top/Article/details/gtskhsbsqk.html

Go:   resp, err := http.Get(url)
来源：http://dali.ppjwa.cn/Article/details/gtwtnzqdlz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yuxming.cn/Article/details/gtaxypcukf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yueranfly.top/Article/details/gtexmhzjvs.html

[L02] 发送 POST JSON
来源：http://dali.yongpay.top/Article/details/gttoaryssh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gtxqnjdapd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhixingplan.top/Article/details/gtunmlpapn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zdqjudy.top/Article/details/gteayfywhe.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cqqwz.cn/Article/details/gttypkcusb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhengqikj.top/Article/details/gtyvyjvymr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sysykeji.top/Article/details/gtucvzrriq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgilmfjvc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guannengcc.top/Article/details/gtalaelizq.html

[L03] 设置自定义请求头
来源：http://dali.chenzaomai.com/Article/details/gtgazkylsb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nanxinkj.top/Article/details/gtgkagzyjf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zdqjudy.top/Article/details/gtvwqbjdht.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hywenlv.cn/Article/details/gtbeszhhjg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258.top/Article/details/gtfdqfhlqk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.kuanghao11.cn/Article/details/gtdlgmvbhd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jlsjyb.cn/Article/details/gthjjyphzx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinghuilouyu.cn/Article/details/gtamnwjyyb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tian-w.cn/Article/details/gtiddwqdnu.html

[L04] 设置超时
来源：http://dali.mhx1999.top/Article/details/gtwaqemoxd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tian-w.cn/Article/details/gtsoyrrfwh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yangfankeji.com/Article/details/gtosdcwwum.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtsvhufglm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jiagoushi.top/Article/details/gtpvuhpyiu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoinuymvo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangdashe.top/Article/details/gtnittqcnq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgbeamvbu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jyoumei.cn/Article/details/gtfqygxntb.html

[L05] 上传文件（multipart）
来源：http://dali.ehwqpu.com/Article/details/gtgtbyfgsl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj202588.top/Article/details/gtcdiqrrig.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.redwolf501.top/Article/details/gtgoeudcrs.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ybcxt.top/Article/details/gtadlntpco.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.birdmap.top/Article/details/gtedmasebh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guannengcc.top/Article/details/gtwxysibdj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenjidiqi.icu/Article/details/gtgiqylrla.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ydzc1.top/Article/details/gttcqqorvm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj202588.top/Article/details/gtwuktwgme.html

[L06] 解析响应为 JSON
来源：http://dali.yongpay.top/Article/details/gtszsdptdz.html

Py:   resp.json()
来源：http://dali.ybcxt.top/Article/details/gtzunjyaqp.html

PHP:  json_decode($body, true);
来源：http://dali.tanke756.top/Article/details/gtbhbdchbg.html

JS:   await resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gtknrzvske.html

TS:   await resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gtlbdnpfjg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.c1oappe.top/Article/details/gtvgfmsfuo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hywenlv.cn/Article/details/gtfoenswbp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhoulong.xyz/Article/details/gtucbrcqsm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jlsjyb.cn/Article/details/gtmswtvixy.html

[L07] 处理 HTTP 状态码
来源：http://dali.yueranfly.top/Article/details/gtdasgawyf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.pycfn.com/Article/details/gtymjjrqpa.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gttinehxbc.html

JS:   resp.ok;  resp.status
来源：http://dali.yonumen.top/Article/details/gtwbitimmj.html

TS:   resp.ok;  resp.status
来源：http://dali.pycfn.com/Article/details/gtvrtdsvyl.html

Java: resp.statusCode()
来源：http://dali.jianghu66.top/Article/details/gtnahogkvt.html

Go:   resp.StatusCode
来源：http://dali.snrcjt.cn/Article/details/gtukvncufm.html

Ruby: resp.code.to_i
来源：http://dali.pengpengdd.cyou/Article/details/gthquzddsh.html

C#:   (int)resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gtolsbdqrf.html

[L08] 并发请求多个地址
来源：http://dali.hnxiangtu.top/Article/details/gtlqsdlrdt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yuxming.cn/Article/details/gtzapyysaw.html

PHP:  curl_multi_init() 系列
来源：http://dali.smart0.xyz/Article/details/gtfgjcvkvv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gtdhbjiiuk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gthoaclcig.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zycfv.cn/Article/details/gtrporjckh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.daria6918.cn/Article/details/gtdyhfuvng.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.bjfxy.top/Article/details/gtcimyszbz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sufxvd.cn/Article/details/gtacojomgs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtmjcucsmd.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgfzy.top/Article/details/gtuoptrqtv.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtvbbhzpqe.html

[M01] 读取命令行参数
来源：http://dali.ydzc1.top/Article/details/gtvjafxzfn.html

Py:   sys.argv[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtogyfcdha.html

PHP:  $argv;  $argc;
来源：http://dali.dashuyun.cn/Article/details/gtwsopgttc.html

JS:   process.argv.slice(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtszlgdnfo.html

TS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gtqtwuldyh.html

Java: args 数组（main 方法参数）
来源：http://dali.daria6918.cn/Article/details/gttaionelf.html

Go:   os.Args[1:]
来源：http://dali.dashuyun.cn/Article/details/gtnngyqgov.html

Ruby: ARGV
来源：http://dali.kuanghao11.cn/Article/details/gtlulvkrqk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj202588.top/Article/details/gtcivqooph.html

[M02] 读取环境变量
来源：http://dali.cqqwz.cn/Article/details/gtoxhjzfxa.html

Py:   os.environ.get("HOME")
来源：http://dali.yuxming.cn/Article/details/gtkvdggtws.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gtljniwnyj.html

JS:   process.env.HOME
来源：http://dali.yuanzhike.top/Article/details/gttwypjctf.html

TS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gtepuqigtc.html

Java: System.getenv("HOME")
来源：http://dali.redwolf501.top/Article/details/gtbfvfitud.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.havefunace.top/Article/details/gtzkvuntsn.html

Ruby: ENV["HOME"]
来源：http://dali.yanxiufei.cn/Article/details/gtmzghjjll.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gtcfyiuzrv.html

[M03] 执行外部命令
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfybzdcef.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cheryme.top/Article/details/gtehkjoick.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.316326.xyz/Article/details/gthcpmvqzh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.andypj.xyz/Article/details/gtnjxrubwc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gtwttwrylz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zdqjudy.top/Article/details/gteyqmnxzt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenjidiqi.icu/Article/details/gtapuwkqrk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.c1oappe.top/Article/details/gthllgolhm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ehwqpu.com/Article/details/gtwhpjfqqo.html

[M04] 获取当前工作目录
来源：http://dali.jinqigufen.top/Article/details/gtgbwraeej.html

Py:   os.getcwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtcogapmej.html

PHP:  getcwd();
来源：http://dali.svipenyu.cn/Article/details/gtpoaspgmr.html

JS:   process.cwd()
来源：http://dali.wangdashe.top/Article/details/gtwaacwuas.html

TS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gtyshqpkup.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.havefunace.top/Article/details/gtvaehdcse.html

Go:   os.Getwd()
来源：http://dali.bjfxy.top/Article/details/gtiijtcjvr.html

Ruby: Dir.pwd
来源：http://dali.yuxming.cn/Article/details/gtcvxxjmwc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.iojbl.cn/Article/details/gtcznicnsb.html

[M05] 设置退出码
来源：http://dali.hnxiangtu.top/Article/details/gtvrmybrtt.html

Py:   sys.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtdqzjuhmj.html

PHP:  exit(1);
来源：http://dali.andypj.xyz/Article/details/gtrsmiiwha.html

JS:   process.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtfqloixkc.html

TS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtzjljzsfw.html

Java: System.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtojwiblom.html

Go:   os.Exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtdxmsonvw.html

Ruby: exit 1
来源：http://dali.sxryk.cn/Article/details/gtykpuhutx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yuxming.cn/Article/details/gtfwfccmny.html

[M06] 向标准错误输出
来源：http://dali.havefunace.top/Article/details/gtlpenwfmv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cqqwz.cn/Article/details/gtbnnszvmd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gtokaszpiz.html

JS:   console.error("err")
来源：http://dali.jlsjyb.cn/Article/details/gtuailxpxg.html

TS:   console.error("err")
来源：http://dali.pycfn.com/Article/details/gtmmttzqab.html

Java: System.err.println("err")
来源：http://dali.aizwys.cn/Article/details/gtfghsetes.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gtysmkzgxo.html

Ruby: warn "err"
来源：http://dali.xziqi.cn/Article/details/gtokyqkyve.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigufen.top/Article/details/gtxtpcuqcu.html

[M07] 判断是否为主入口
来源：http://dali.nwbrower.top/Article/details/gtchyqmlvz.html

Py:   if __name__ == "__main__":
来源：http://dali.svipenyu.cn/Article/details/gtrwrvgrks.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhongyouzk.top/Article/details/gtkthmjzlf.html

JS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gtphvsuaoq.html

TS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gtayscnbgj.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gtqehyamis.html

Go:   func main()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgqysjsvp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hfpthk.cn/Article/details/gtsfisxjur.html

C#:   static void Main(string[] args)
来源：http://dali.zhixingplan.top/Article/details/gtorsahrbm.html

[M08] 获取系统与运行时信息
来源：http://dali.zycfv.cn/Article/details/gtbloodxhl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cdnleiting.top/Article/details/gtnjjbovpy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.mhx1999.top/Article/details/gtavhbfkeq.html

JS:   process.platform;  process.version
来源：http://dali.sxryk.cn/Article/details/gtctszovhm.html

TS:   process.platform;  process.version
来源：http://dali.gaohongyu789.top/Article/details/gtpmbfmxvy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhengqikj.top/Article/details/gtvsgerikw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xylfe.cn/Article/details/gtattgwxba.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.guannengcc.top/Article/details/gtmqevcjid.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuanzx.com/Article/details/gtonhispae.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtasxcetxp.html

N. 数据结构与算法
来源：http://dali.yueranfly.top/Article/details/gtnpggauve.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtwizflglu.html

[N01] 二分查找（有序数组）
来源：http://dali.gaohongyu789.top/Article/details/gtgshdgbnq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtpfgozhya.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gtwgfkezyd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xziqi.cn/Article/details/gtysnutlsi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.c1oappe.top/Article/details/gtgwmsvqnv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtakegixzq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtxjgyvrqa.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zdqjudy.top/Article/details/gtvbfavouc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtchpndrdg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnxiangtu.top/Article/details/gtyvdmtkys.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gtqayhzagu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ydzc1.top/Article/details/gteuapybpm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gtipjrbdwf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhongyouzk.top/Article/details/gtdaqyshkr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.chenzaomai.com/Article/details/gtqvkcifzx.html

Go:   slices.Sort(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtfakhjvmh.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtsaduvqgc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.0kj1m.cn/Article/details/gtgcrwnkxx.html

[N03] 快速排序（分治示例）
来源：http://dali.mhx1999.top/Article/details/gtyzknrzrj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.daria6918.cn/Article/details/gtdqchgric.html

PHP:  // 递归实现，或用 usort
来源：http://dali.9152youxi.cn/Article/details/gtzalaapdq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sysykeji.top/Article/details/gtlextqawx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jianghu66.top/Article/details/gtdflpyltf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yangfankeji.com/Article/details/gtnotjwzed.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jlsjyb.cn/Article/details/gtvavshxqj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.aizwys.cn/Article/details/gtfqsobejb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yueranfly.top/Article/details/gtiihssftx.html

[N04] 斐波那契数列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbavrermy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzzeozeex.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sxryk.cn/Article/details/gtxkgrgvcl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gtxabajhoo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gtqjobmizp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sxryk.cn/Article/details/gtkylnvorq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xziqi.cn/Article/details/gtcgsocmpz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hfpthk.cn/Article/details/gttriwcqoj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gtdhijseet.html

[N05] 最大公约数
来源：http://dali.yj202588.top/Article/details/gtnxraiziy.html

Py:   math.gcd(a, b)
来源：http://dali.zhengqikj.top/Article/details/gtjunmjayp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yvedp.cn/Article/details/gtpyjkczgq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgfzy.top/Article/details/gtdyuzpxsg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gtjcjewqsj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xinyue.icu/Article/details/gtyeklrign.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.pycfn.com/Article/details/gtmxsjklxv.html

Ruby: a.gcd(b)
来源：http://dali.ppjwa.cn/Article/details/gtxtkblutp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yonumen.top/Article/details/gtuxwhikpf.html

[N06] 判断回文字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtczwtyrlt.html

Py:   s == s[::-1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdibbgwx.html

PHP:  $s === strrev($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtmadrdeuq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtdkuphlay.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gtwrbypshe.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinghuilouyu.cn/Article/details/gtbcyitgyl.html

Go:   // 双指针从两端比较
来源：http://dali.jiagoushi.top/Article/details/gtyedooujt.html

Ruby: s == s.reverse
来源：http://dali.fzhhl.top/Article/details/gtlaxthxsq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cucudq.cn/Article/details/gthafasxhj.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gthjxxoxix.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ydzc1.top/Article/details/gtyzxfmwjt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gtuvtozgve.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sxryk.cn/Article/details/gtmxbohcry.html

TS:   // 手写 Map<string, number>
来源：http://dali.guannengcc.top/Article/details/gtjubehkhe.html

Java: // 手写 HashMap
来源：http://dali.yangfankeji.com/Article/details/gtoaoylfgd.html

Go:   // 手写 map[int]int
来源：http://dali.zhoulong.xyz/Article/details/gtrylomomj.html

Ruby: // 手写 Hash
来源：http://dali.dashuyun.cn/Article/details/gtxdjsxrtk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj20258.top/Article/details/gtzutjonxo.html

[N08] 生成全排列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkfxwrvdw.html

Py:   itertools.permutations(arr)
来源：http://dali.jqgufenzy.top/Article/details/gthevjgbvj.html

PHP:  // 手写递归交换
来源：http://dali.jqgfzy.top/Article/details/gtneizisrg.html

JS:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtdsgghogj.html

TS:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtchuoheje.html

Java: // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gttsjbemlt.html

Go:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gtogebbvjd.html

Ruby: arr.permutation.to_a
来源：http://dali.daria6918.cn/Article/details/gtpdulgcjb.html

C#:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gttmbwlwkj.html

[N09] 栈与队列
来源：http://dali.pengpengdd.cyou/Article/details/gtbwvrfeey.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.iojbl.cn/Article/details/gtzbrhezka.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gtcthiiegi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gtujnxtxxc.html


<!-- 参考信息 -->