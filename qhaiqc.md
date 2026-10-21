代发 wailian999

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gotoacloud.top/Article/details/gtxjgmiocz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangtech.top/Article/details/gtqkkhvpof.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gtufaranoh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzgsmaixp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hammf.cn/Article/details/gtfelhxiyq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yuanzhike.top/Article/details/gthbzdoiqr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.kuanghao11.cn/Article/details/gtooirdhne.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.dashuyun.cn/Article/details/gtwqciokeu.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtftjtpftg.html

K. JSON 与序列化
来源：http://dali.sysykeji.top/Article/details/gthxomfkwj.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtahtmdghd.html

[K01] 对象转 JSON 字符串
来源：http://dali.yongpay.top/Article/details/gtzuspfpxq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gtbdbmdlpa.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxuanxn.top/Article/details/gtunjcrzbf.html

JS:   JSON.stringify(obj)
来源：http://dali.jqgfzy.top/Article/details/gtsmpwnxwx.html

TS:   JSON.stringify(obj)
来源：http://dali.9152youxi.cn/Article/details/gtnccqrtwi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj202588.top/Article/details/gtjyvnjeas.html

Go:   json.Marshal(obj)
来源：http://dali.pycfn.com/Article/details/gtoaqwkten.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yuxming.cn/Article/details/gtqcklkkqc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xylfe.cn/Article/details/gtqfcahtvi.html

[K02] JSON 字符串转对象
来源：http://dali.ehwqpu.com/Article/details/gtthprwzro.html

Py:   json.loads(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtfdogxrrc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yangfankeji.com/Article/details/gtoqhujmjv.html

JS:   JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gtvfdudqwv.html

TS:   JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gtcsowgtdx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gotoacloud.top/Article/details/gtcatzctep.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.dashuyun.cn/Article/details/gtdxklqjzz.html

Ruby: JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gtgixzwicb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtyvyeknxx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.haohaochexian.top/Article/details/gtdanzxghk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.redwolf501.top/Article/details/gtmazymxfj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gtomhvlewf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ybcxt.top/Article/details/gtidkitqrg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.bjfxy.top/Article/details/gtqmvmxjxx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hywenlv.cn/Article/details/gtpytlmoib.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj20258888.top/Article/details/gtqcmhanua.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sxryk.cn/Article/details/gtuevfeizv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zdqjudy.top/Article/details/gtbjlyngad.html

[K04] 读取 JSON 文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmthwyfjw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hongshengwenyu.top/Article/details/gtnuuztdac.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cqqwz.cn/Article/details/gtclurtict.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gtbundutxi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gzhubu.top/Article/details/gtbdqzjtaw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sweek.top/Article/details/gtckmbabeg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sysykeji.top/Article/details/gtibzwynbj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sysykeji.top/Article/details/gtdaelmtjs.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxuanxn.top/Article/details/gtvrshlgit.html

[K05] 深拷贝对象
来源：http://dali.jqgufenzy.top/Article/details/gtywilpkct.html

Py:   copy.deepcopy(obj)
来源：http://dali.sysykeji.top/Article/details/gtorovjyxv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.aizwys.cn/Article/details/gtdoehumnl.html

JS:   structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gtdnzyekft.html

TS:   structuredClone(obj)
来源：http://dali.cashguo.top/Article/details/gtsonakbcx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhoulong.xyz/Article/details/gtavczccfc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.dianchejie.cn/Article/details/gtcorxpwgb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.dashuyun.cn/Article/details/gtgcpxflfm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.andypj.xyz/Article/details/gtxgsqqgqk.html

[K06] 解析 URL 查询串
来源：http://dali.hammf.cn/Article/details/gtgtnohtkf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.pycfn.com/Article/details/gtmwtedvkd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sxryk.cn/Article/details/gtqxozyngi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuanzhike.top/Article/details/gtagcyycwv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gtaexwrjlu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.dianchejie.cn/Article/details/gtdmorvhpf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgshjtxat.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdllawzgn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gtcpwusuqy.html

[K07] 进制转换
来源：http://dali.mhx1999.top/Article/details/gthxhadwdf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtizfxsvif.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj20258.top/Article/details/gtapyaydor.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtrsiuydyy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtrgsxohnn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtbtbmqjvk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gaohongyu789.top/Article/details/gtpvxtrtnw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ivvv.top/Article/details/gtzkhqrrqe.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtxdjatfje.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.havefunace.top/Article/details/gtuuafzkeb.html

Py:   pickle.dumps(obj)
来源：http://dali.yuanzhike.top/Article/details/gtkenahmil.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sysykeji.top/Article/details/gtleszrutk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.guowangkeji.top/Article/details/gtzoendndn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shangyingyoupin.top/Article/details/gtjkxsjmvv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenlongwang.top/Article/details/gtxdkzaulg.html

Go:   encoding/gob
来源：http://dali.jyoumei.cn/Article/details/gtnyffgynm.html

Ruby: Marshal.dump(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gturlwfvsu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gtddwbjvco.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtcazqfroe.html

L. 网络请求
来源：http://dali.ehwqpu.com/Article/details/gtjagsdauc.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtchxdciye.html

[L01] 发送 GET 请求
来源：http://dali.quarkkingdee.top/Article/details/gtwtlxaqxt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xuanzx.com/Article/details/gtpevbkfqf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.pengpengdd.cyou/Article/details/gthxkdqxcc.html

JS:   await fetch(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzjbqprc.html

TS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gtcymwwvfp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zycfv.cn/Article/details/gtjkccoizs.html

Go:   resp, err := http.Get(url)
来源：http://dali.mhx1999.top/Article/details/gtnzwleypa.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jyoumei.cn/Article/details/gtipeezmrh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shzxlz.cn/Article/details/gtnweoxxkr.html

[L02] 发送 POST JSON
来源：http://dali.cheryme.top/Article/details/gtnzuepvmc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.birdmap.top/Article/details/gtckrthlud.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.bjfxy.top/Article/details/gtgwvhcpkm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.birdmap.top/Article/details/gtbzwqtqov.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yanxiufei.cn/Article/details/gtdfvjpwjq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jqgfzy.top/Article/details/gtiyftlfha.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.316326.xyz/Article/details/gtfonzgkyo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hnxiangtu.top/Article/details/gtyrkxsmqx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenjidiqi.icu/Article/details/gtakujufvs.html

[L03] 设置自定义请求头
来源：http://dali.zhengqikj.top/Article/details/gtmdvthqry.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nwbrower.top/Article/details/gtmcxszmjw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtapegrvcj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.kuanghao11.cn/Article/details/gtjnxosohe.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gtbpzndkuo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenlongwang.top/Article/details/gtdxosssbf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shzxlz.cn/Article/details/gtcdsamzbv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258888.top/Article/details/gtntjnxirl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwzgwuuf.html

[L04] 设置超时
来源：http://dali.zhoulong.xyz/Article/details/gtpplwzbyn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nanxinkj.top/Article/details/gtvivgphhs.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenlongwang.top/Article/details/gtxtdbherr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxinkj.top/Article/details/gtougcipzm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gtxaxkdmfy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yvedp.cn/Article/details/gtfzfkzkiw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fzhhl.top/Article/details/gtdnkiabjc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tanke756.top/Article/details/gtlxmiqvin.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwpneyog.html

[L05] 上传文件（multipart）
来源：http://dali.guowangkeji.top/Article/details/gtuzykdduc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.9152youxi.cn/Article/details/gtnynppgvj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.haohaochexian.top/Article/details/gtidpkxjyq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnxiangtu.top/Article/details/gtmxhwisnv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.vqdsnc.cn/Article/details/gtsiukgtlo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zycfv.cn/Article/details/gtxctaqpbm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xylfe.cn/Article/details/gtqlkqfhfu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmpehjwiy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.aizwys.cn/Article/details/gttlajckyp.html

[L06] 解析响应为 JSON
来源：http://dali.ybcxt.top/Article/details/gtzobyukpk.html

Py:   resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gtiddzziqy.html

PHP:  json_decode($body, true);
来源：http://dali.xziqi.cn/Article/details/gthvnlzkyt.html

JS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gtbzmrebcc.html

TS:   await resp.json()
来源：http://dali.fzhhl.top/Article/details/gtistcmdri.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guannengcc.top/Article/details/gthqsjoiem.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nwbrower.top/Article/details/gtiukjjheu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.meibo888.top/Article/details/gtytyixtoq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ybcxt.top/Article/details/gtwnwhsafi.html

[L07] 处理 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gtuoralqut.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hfpthk.cn/Article/details/gtzjujpqsq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shuidangran.top/Article/details/gtyyrhhbka.html

JS:   resp.ok;  resp.status
来源：http://dali.yuxming.cn/Article/details/gtkdhbabgs.html

TS:   resp.ok;  resp.status
来源：http://dali.sweek.top/Article/details/gtjqtzcfig.html

Java: resp.statusCode()
来源：http://dali.zhixingplan.top/Article/details/gtkyoupsoe.html

Go:   resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gtagvjjdfk.html

Ruby: resp.code.to_i
来源：http://dali.tianlin.xyz/Article/details/gtncdzgian.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gtjbqvindr.html

[L08] 并发请求多个地址
来源：http://dali.havefunace.top/Article/details/gtuvrnbvag.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.c1oappe.top/Article/details/gtqshmtfel.html

PHP:  curl_multi_init() 系列
来源：http://dali.yuanzhike.top/Article/details/gtmdoxeydu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gtmkclowrw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gtmhwzuscl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hongshengwenyu.top/Article/details/gtbeyckmmv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj20258888.top/Article/details/gttvulgskd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gogol.net.cn/Article/details/gtawotzgzz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gtdjmplvmp.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtzuooloor.html

M. 命令行 / 进程 / 环境
来源：http://dali.gogol.net.cn/Article/details/gthsaiffxg.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtquutdvdg.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gtybtexamf.html

Py:   sys.argv[1:]
来源：http://dali.shzxlz.cn/Article/details/gtojwqzabt.html

PHP:  $argv;  $argc;
来源：http://dali.sufxvd.cn/Article/details/gteoccciga.html

JS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gtkqjxrypm.html

TS:   process.argv.slice(2)
来源：http://dali.gzhubu.top/Article/details/gthpqnbbmm.html

Java: args 数组（main 方法参数）
来源：http://dali.feifeiyinyue.top/Article/details/gtjrabahcx.html

Go:   os.Args[1:]
来源：http://dali.hfpthk.cn/Article/details/gtynsxwjuo.html

Ruby: ARGV
来源：http://dali.xziqi.cn/Article/details/gtdnrnreqp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gtghvnlilz.html

[M02] 读取环境变量
来源：http://dali.gaohongyu789.top/Article/details/gtexocajfb.html

Py:   os.environ.get("HOME")
来源：http://dali.snrcjt.cn/Article/details/gtjcpocaak.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj202588.top/Article/details/gtzbpmzfvq.html

JS:   process.env.HOME
来源：http://dali.yj202588.top/Article/details/gtopfjvbsr.html

TS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gtfopulfne.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtlatxeslk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yongpay.top/Article/details/gtazzwysrl.html

Ruby: ENV["HOME"]
来源：http://dali.xuanzx.com/Article/details/gtwgvhhych.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfudvktfd.html

[M03] 执行外部命令
来源：http://dali.jyoumei.cn/Article/details/gtvlmrjodm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gttwpwsqie.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.daria6918.cn/Article/details/gtboprjlas.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtetqmgwqo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gtjigbkjtb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jianghu66.top/Article/details/gtqkpjjext.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.redwolf501.top/Article/details/gtwtgavtpu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cqqwz.cn/Article/details/gteelzqshg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtignpcohd.html

[M04] 获取当前工作目录
来源：http://dali.wangdashe.top/Article/details/gtyunnowty.html

Py:   os.getcwd()
来源：http://dali.yj202588.top/Article/details/gttsopvowq.html

PHP:  getcwd();
来源：http://dali.dianchejie.cn/Article/details/gtcrdeadcg.html

JS:   process.cwd()
来源：http://dali.hywenlv.cn/Article/details/gtauvuqhim.html

TS:   process.cwd()
来源：http://dali.ppjwa.cn/Article/details/gtkqaxufnt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cdnleiting.top/Article/details/gtzbxfucaa.html

Go:   os.Getwd()
来源：http://dali.yanxiufei.cn/Article/details/gtynchpjrf.html

Ruby: Dir.pwd
来源：http://dali.zhengqikj.top/Article/details/gtzaebotyo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.kuanghao11.cn/Article/details/gtxxavcuou.html

[M05] 设置退出码
来源：http://dali.ivvv.top/Article/details/gtibfeytja.html

Py:   sys.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtmzdudywa.html

PHP:  exit(1);
来源：http://dali.yj202588.top/Article/details/gtpcizcjnn.html

JS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtjycerhpt.html

TS:   process.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtkwpzrdip.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtxbnaemgq.html

Go:   os.Exit(1)
来源：http://dali.tanke756.top/Article/details/gtklnjumqh.html

Ruby: exit 1
来源：http://dali.wangshuangyany.cn/Article/details/gtcmllkuwp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shzxlz.cn/Article/details/gtjelpxcft.html

[M06] 向标准错误输出
来源：http://dali.jiagoushi.top/Article/details/gtnmxetfoy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hnxiangtu.top/Article/details/gtybhyodyy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tian-w.cn/Article/details/gtteaqpqne.html

JS:   console.error("err")
来源：http://dali.pengpengdd.cyou/Article/details/gtvpfdvabs.html

TS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gtfguuuhuf.html

Java: System.err.println("err")
来源：http://dali.tianlin.xyz/Article/details/gtvptqjsea.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.c1oappe.top/Article/details/gtreiqoiya.html

Ruby: warn "err"
来源：http://dali.zhixingplan.top/Article/details/gtfoxtkwks.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xziqi.cn/Article/details/gtprgpuapu.html

[M07] 判断是否为主入口
来源：http://dali.hfpthk.cn/Article/details/gtpukfgmvt.html

Py:   if __name__ == "__main__":
来源：http://dali.cdnleiting.top/Article/details/gtkbpllzwr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.9152youxi.cn/Article/details/gtsqahxpwy.html

JS:   require.main === module
来源：http://dali.yvedp.cn/Article/details/gtrlenwfkq.html

TS:   require.main === module
来源：http://dali.yuanzhike.top/Article/details/gtdbkaejsp.html

Java: public static void main(String[] args)
来源：http://dali.pycfn.com/Article/details/gtpsenlgvk.html

Go:   func main()
来源：http://dali.tian-w.cn/Article/details/gtisvkszst.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nanxinkj.top/Article/details/gtgkysglyk.html

C#:   static void Main(string[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gthidnbwcs.html

[M08] 获取系统与运行时信息
来源：http://dali.yj20258888.top/Article/details/gtyexvkxhh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yanxiufei.cn/Article/details/gtfxhzcydu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cqqwz.cn/Article/details/gtogfynigs.html

JS:   process.platform;  process.version
来源：http://dali.feifeiyinyue.top/Article/details/gtfxrpyusb.html

TS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gtjdhhmdqt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.fengsongda.top/Article/details/gtunpocheo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgfzy.top/Article/details/gtoluritrz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.haohaochexian.top/Article/details/gtxvmccjoo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gttpcrpsab.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtgzrheswx.html

N. 数据结构与算法
来源：http://dali.daxiang520.top/Article/details/gtpqltohjd.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtfdrlrgsl.html

[N01] 二分查找（有序数组）
来源：http://dali.zhongyouzk.top/Article/details/gtolrdtgjl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtjrxmwvjd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinqigufen.top/Article/details/gtosrcnmxx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxupejrzt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hywenlv.cn/Article/details/gtumvvzmes.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtpwtkatbc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttngmtbgn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.dashuyun.cn/Article/details/gtnwilxrtp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtcrndazln.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.svipenyu.cn/Article/details/gtxporceme.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenlongwang.top/Article/details/gtkggrjmfb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cqqwz.cn/Article/details/gtjuvkoozi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gtxzrcoyaf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gtbphdbgfz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnxiangtu.top/Article/details/gtawqnbucn.html

Go:   slices.Sort(arr)
来源：http://dali.yuxming.cn/Article/details/gtyqkkochp.html

Ruby: arr.sort
来源：http://dali.yj20258.top/Article/details/gtvawmlqwr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.0kj1m.cn/Article/details/gtrgqxvhoa.html

[N03] 快速排序（分治示例）
来源：http://dali.xinyue.icu/Article/details/gtkeutkjoc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hysaishi.cn/Article/details/gtcywdvyop.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cheryme.top/Article/details/gtwijfexox.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gtwaensiqq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.meibo888.top/Article/details/gtfnirkdqi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinqigfzy.top/Article/details/gtvqzgajwv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jyoumei.cn/Article/details/gtbqlrdobi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cucudq.cn/Article/details/gtikdwnzzt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cdnleiting.top/Article/details/gtizigueak.html

[N04] 斐波那契数列
来源：http://dali.jinqigufen.top/Article/details/gtqkjbxyeh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.c1oappe.top/Article/details/gtknqylztw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xinyue.icu/Article/details/gtpdrzonbc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gtnipxjyrh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gtganfqzmi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.smart0.xyz/Article/details/gtrslognka.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jianghu66.top/Article/details/gtdxxjayhr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.redwolf501.top/Article/details/gtcchwmeue.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtldwjvdlw.html

[N05] 最大公约数
来源：http://dali.ppjwa.cn/Article/details/gtfxxvjtlf.html

Py:   math.gcd(a, b)
来源：http://dali.yangfankeji.com/Article/details/gtehdffkhl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yuanzhike.top/Article/details/gtuqghmzww.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenzaomai.com/Article/details/gtlfnuwffo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gogol.net.cn/Article/details/gtndamecpc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cheryme.top/Article/details/gtdcwuccjh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aizwys.cn/Article/details/gtfouerypu.html

Ruby: a.gcd(b)
来源：http://dali.wangshuangyany.cn/Article/details/gtmdoobrgn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xylfe.cn/Article/details/gtsppxralb.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gttizkdhiu.html

Py:   s == s[::-1]
来源：http://dali.cashguo.top/Article/details/gtfboorwnh.html

PHP:  $s === strrev($s);
来源：http://dali.tanke756.top/Article/details/gtjusmgzxr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gttuexslgb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gtlkfdyoji.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmubsiwgg.html

Go:   // 双指针从两端比较
来源：http://dali.9152youxi.cn/Article/details/gtdauxmddp.html

Ruby: s == s.reverse
来源：http://dali.cqqwz.cn/Article/details/gtexpmnqxf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmmkrxec.html

[N07] 两数之和（返回下标）
来源：http://dali.jinqigufen.top/Article/details/gttphoqoal.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shangyingyoupin.top/Article/details/gtdvpxlhhg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xinyue.icu/Article/details/gtunbfhnnk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.fzhhl.top/Article/details/gthifsfpub.html

TS:   // 手写 Map<string, number>
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfcbwrihn.html

Java: // 手写 HashMap
来源：http://dali.cheryme.top/Article/details/gtitrxlwwg.html

Go:   // 手写 map[int]int
来源：http://dali.hongshengwenyu.top/Article/details/gtgfqkwshf.html

Ruby: // 手写 Hash
来源：http://dali.aibaodan.cn/Article/details/gtgxwtfdet.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ydzc1.top/Article/details/gtkxaekzpv.html

[N08] 生成全排列
来源：http://dali.0kj1m.cn/Article/details/gtrsdvjeyz.html


<!-- 参考信息 -->