代发 wailian999

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtttmhiqjc.html

K. JSON 与序列化
来源：http://dali.wangshuangyany.cn/Article/details/gtljubkdxi.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtpttohels.html

[K01] 对象转 JSON 字符串
来源：http://dali.hfpthk.cn/Article/details/gtignwfhum.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gtaprspbix.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gtymrvwowp.html

JS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gtvoliyhvf.html

TS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gthfhwdjvc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.andypj.xyz/Article/details/gttavbhpng.html

Go:   json.Marshal(obj)
来源：http://dali.hysaishi.cn/Article/details/gtlvznxsmf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.guannengcc.top/Article/details/gtpxqmlcxu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yvedp.cn/Article/details/gtoutqvjxl.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gtqwjrivko.html

Py:   json.loads(s)
来源：http://dali.zdqjudy.top/Article/details/gtlnhuqgyz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.daria6918.cn/Article/details/gtclcjuroo.html

JS:   JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gtqlqawevy.html

TS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtihypaejz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yueranfly.top/Article/details/gtdamujuef.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tanke756.top/Article/details/gttazuoayh.html

Ruby: JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gtoozvhpyl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cqqwz.cn/Article/details/gtjiwfftpm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenlongwang.top/Article/details/gttvckrbvt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnxiangtu.top/Article/details/gtjumoheql.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yangfankeji.com/Article/details/gtklrcmkgb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.dianchejie.cn/Article/details/gtigotzwxz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtoskkxdbh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtiklukxin.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sxryk.cn/Article/details/gtfaullmmi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtasquvxqn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.fengsongda.top/Article/details/gtqlwmsulc.html

[K04] 读取 JSON 文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtunfcvtzi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.9152youxi.cn/Article/details/gtfuutkuyo.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sweek.top/Article/details/gtsgjjqxfd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gtejynvmni.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnxiangtu.top/Article/details/gtdsmxierm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.andypj.xyz/Article/details/gtcqzcremd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yonumen.top/Article/details/gtrfqgosss.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sufxvd.cn/Article/details/gtkgtdcbrc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ydzc1.top/Article/details/gtdaxrxpiz.html

[K05] 深拷贝对象
来源：http://dali.tian-w.cn/Article/details/gtldirizln.html

Py:   copy.deepcopy(obj)
来源：http://dali.hfpthk.cn/Article/details/gtcmycspup.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhoulong.xyz/Article/details/gthchlyjkj.html

JS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gtxjvyofae.html

TS:   structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gttsjhlvoq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj202588.top/Article/details/gtvjjsinwb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenzaomai.com/Article/details/gtxeprhcgf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ybcxt.top/Article/details/gtbpjxplqb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hongshengwenyu.top/Article/details/gtwpqeolmu.html

[K06] 解析 URL 查询串
来源：http://dali.zhongyouzk.top/Article/details/gtbspvnwcd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.aizwys.cn/Article/details/gtyrfuthzi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yuanzhike.top/Article/details/gtyqwthfym.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gtoihnosix.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gtdxurwygo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.meibo888.top/Article/details/gtjapocnwf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gtmtoyecbc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gtjrrysjjz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gtljxpmkyn.html

[K07] 进制转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvyxxqwh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtyskgbckn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxuanxn.top/Article/details/gtqjdykqou.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkkflqapj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtxkpnzhjr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtpkaqkfxv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ppjwa.cn/Article/details/gtupxwupze.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yongpay.top/Article/details/gtlkfabrjm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtwmuutida.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhixingplan.top/Article/details/gtcczzadmn.html

Py:   pickle.dumps(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtlxhokipz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhhzpoay.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tianlin.xyz/Article/details/gtbolobjxi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jianghu66.top/Article/details/gtcoplkfav.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jianghu66.top/Article/details/gtouhrrkwv.html

Go:   encoding/gob
来源：http://dali.hnqzz.top/Article/details/gtjnfbhacq.html

Ruby: Marshal.dump(obj)
来源：http://dali.mhx1999.top/Article/details/gtppjumjfw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yongpay.top/Article/details/gtthkmpkbw.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gthqlytjpu.html

L. 网络请求
来源：http://dali.yongpay.top/Article/details/gtzatyggtl.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtfrjyrrss.html

[L01] 发送 GET 请求
来源：http://dali.jqgfzy.top/Article/details/gtgjblhylj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.wangdashe.top/Article/details/gtmojssojj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.svipenyu.cn/Article/details/gtfzxyoeua.html

JS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gtvqkmebig.html

TS:   await fetch(url)
来源：http://dali.xylfe.cn/Article/details/gtutffzkgq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ehwqpu.com/Article/details/gtycjhezfa.html

Go:   resp, err := http.Get(url)
来源：http://dali.yvedp.cn/Article/details/gtvbqqpbyv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tianlin.xyz/Article/details/gtikhbjlms.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yanxiufei.cn/Article/details/gtutsmthik.html

[L02] 发送 POST JSON
来源：http://dali.nwbrower.top/Article/details/gtdlzpcxhl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yangfankeji.com/Article/details/gthbvsytmz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hongshengwenyu.top/Article/details/gtmtbsgdbf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daxiang520.top/Article/details/gtolmislje.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.haohaochexian.top/Article/details/gtgllkjcvu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gttkdlytii.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj20258.top/Article/details/gtgkmxpizg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gotoacloud.top/Article/details/gtjttdfpan.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aizwys.cn/Article/details/gtwamygvfv.html

[L03] 设置自定义请求头
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkavmrlst.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewpfqcos.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.0kj1m.cn/Article/details/gtbzvzvxhn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuanzhike.top/Article/details/gtvnaqjumq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yueranfly.top/Article/details/gtnhnihrau.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenjidiqi.icu/Article/details/gtgnadhmuo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.snrcjt.cn/Article/details/gtrhgztoqe.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.pycfn.com/Article/details/gtnnyrsroo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.mhx1999.top/Article/details/gteuijzbzo.html

[L04] 设置超时
来源：http://dali.c1oappe.top/Article/details/gtphnsbkhh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.9152youxi.cn/Article/details/gtznemqlgk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fengsongda.top/Article/details/gtcuhphowv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tian-w.cn/Article/details/gtgbzeatfn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgfzy.top/Article/details/gttgsmpjil.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.redwolf501.top/Article/details/gtwioirgvp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pycfn.com/Article/details/gtztmsgwmd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xziqi.cn/Article/details/gttmteyyjz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnqzz.top/Article/details/gtrldfhdif.html

[L05] 上传文件（multipart）
来源：http://dali.chenjidiqi.icu/Article/details/gtnecchyni.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhiwuduotai.top/Article/details/gtbetgljlf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenjidiqi.icu/Article/details/gtgaaetmro.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nwbrower.top/Article/details/gtwqomovag.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.smart0.xyz/Article/details/gtyiujiykt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shuidangran.top/Article/details/gtsdjiewqg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hysaishi.cn/Article/details/gtqusdzgvw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzmqtauy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.havefunace.top/Article/details/gtdddorneo.html

[L06] 解析响应为 JSON
来源：http://dali.zdqjudy.top/Article/details/gtxnxieesp.html

Py:   resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gttljoaywo.html

PHP:  json_decode($body, true);
来源：http://dali.sweek.top/Article/details/gtwdhxqpeh.html

JS:   await resp.json()
来源：http://dali.snrcjt.cn/Article/details/gtnnblxjcg.html

TS:   await resp.json()
来源：http://dali.nanxinkj.top/Article/details/gtnsgiqeyk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.dianchejie.cn/Article/details/gtoxrwssbd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.c1oappe.top/Article/details/gtusouunrl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmokpvsvs.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shangyingyoupin.top/Article/details/gtnrgxopyh.html

[L07] 处理 HTTP 状态码
来源：http://dali.c1oappe.top/Article/details/gtsbqlrvnn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hammf.cn/Article/details/gtmknflzxn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.guowangkeji.top/Article/details/gthtvitpey.html

JS:   resp.ok;  resp.status
来源：http://dali.haohaochexian.top/Article/details/gtguogsrcq.html

TS:   resp.ok;  resp.status
来源：http://dali.haohaochexian.top/Article/details/gtrkweglvd.html

Java: resp.statusCode()
来源：http://dali.quarkkingdee.top/Article/details/gtvhpqnalg.html

Go:   resp.StatusCode
来源：http://dali.shuidangran.top/Article/details/gtxgfhildr.html

Ruby: resp.code.to_i
来源：http://dali.tianlin.xyz/Article/details/gtpymsplhq.html

C#:   (int)resp.StatusCode
来源：http://dali.hammf.cn/Article/details/gtqgzeiinq.html

[L08] 并发请求多个地址
来源：http://dali.mhx1999.top/Article/details/gtbmevbhup.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenlongwang.top/Article/details/gtlvwaezyu.html

PHP:  curl_multi_init() 系列
来源：http://dali.dashuyun.cn/Article/details/gtfbhkkuxl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gtsdxcmjlp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gtqnrlquxg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.quarkkingdee.top/Article/details/gtlxjywzjb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhengqikj.top/Article/details/gtsqabrqya.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnqzz.top/Article/details/gtqcdfwnjr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jianghu66.top/Article/details/gtzyhtnbfm.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtbiqufrvo.html

M. 命令行 / 进程 / 环境
来源：http://dali.dashuyun.cn/Article/details/gtduullium.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtgmubigio.html

[M01] 读取命令行参数
来源：http://dali.sufxvd.cn/Article/details/gtrxybdtcj.html

Py:   sys.argv[1:]
来源：http://dali.yuanzhike.top/Article/details/gtrkqfyrhn.html

PHP:  $argv;  $argc;
来源：http://dali.yangfankeji.com/Article/details/gtsxqzgaxn.html

JS:   process.argv.slice(2)
来源：http://dali.xziqi.cn/Article/details/gtstjtcrtx.html

TS:   process.argv.slice(2)
来源：http://dali.zhiwuduotai.top/Article/details/gtpwbywxhd.html

Java: args 数组（main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gtimwjlkkh.html

Go:   os.Args[1:]
来源：http://dali.316326.xyz/Article/details/gtdhohiwiy.html

Ruby: ARGV
来源：http://dali.yj20258.top/Article/details/gtqbxhwxhd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.c1oappe.top/Article/details/gtqhsvggse.html

[M02] 读取环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gtnesqsxqr.html

Py:   os.environ.get("HOME")
来源：http://dali.dashuyun.cn/Article/details/gtbwccwuev.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.316326.xyz/Article/details/gtgwpruajw.html

JS:   process.env.HOME
来源：http://dali.dianchejie.cn/Article/details/gtzjckdzyj.html

TS:   process.env.HOME
来源：http://dali.nwbrower.top/Article/details/gtvlrbanfh.html

Java: System.getenv("HOME")
来源：http://dali.ybcxt.top/Article/details/gtyydknyid.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtgqwebwhy.html

Ruby: ENV["HOME"]
来源：http://dali.ehwqpu.com/Article/details/gtjttwcngl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sysykeji.top/Article/details/gtwjvmcgpz.html

[M03] 执行外部命令
来源：http://dali.guannengcc.top/Article/details/gtypwkookd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yanxiufei.cn/Article/details/gtpcadjoxa.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhengqikj.top/Article/details/gtnacfiqwh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.fzhhl.top/Article/details/gtxwnfocvd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtgkjdhqgb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszwsjfoe.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.wangdashe.top/Article/details/gtdzdzndvo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jianghu66.top/Article/details/gtltvgubkq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.fzhhl.top/Article/details/gtlchlehbh.html

[M04] 获取当前工作目录
来源：http://dali.aizwys.cn/Article/details/gtrfqltihz.html

Py:   os.getcwd()
来源：http://dali.pycfn.com/Article/details/gtciyjkkfq.html

PHP:  getcwd();
来源：http://dali.guannengcc.top/Article/details/gtlsfwuvbp.html

JS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gtnslmapvp.html

TS:   process.cwd()
来源：http://dali.ydzc1.top/Article/details/gtdkvhcuug.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cheryme.top/Article/details/gtwoznefwh.html

Go:   os.Getwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtcnhxnyqx.html

Ruby: Dir.pwd
来源：http://dali.zhongyouzk.top/Article/details/gtehwvokkl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.316326.xyz/Article/details/gtbzvgccep.html

[M05] 设置退出码
来源：http://dali.hfpthk.cn/Article/details/gtizcdbkct.html

Py:   sys.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtgpbyfigo.html

PHP:  exit(1);
来源：http://dali.guowangkeji.top/Article/details/gtsqwuvgmj.html

JS:   process.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtooiptlfz.html

TS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtoxidfuoq.html

Java: System.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtfyujlmgs.html

Go:   os.Exit(1)
来源：http://dali.tanke756.top/Article/details/gtipyzptfd.html

Ruby: exit 1
来源：http://dali.zhixingplan.top/Article/details/gtlctlodox.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hywenlv.cn/Article/details/gtmqeadmnf.html

[M06] 向标准错误输出
来源：http://dali.c1oappe.top/Article/details/gtbolazisa.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigfzy.top/Article/details/gtkhvsmtgj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sxryk.cn/Article/details/gtbgzemxid.html

JS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gtfjlcnbsq.html

TS:   console.error("err")
来源：http://dali.ehwqpu.com/Article/details/gtvzsdiofr.html

Java: System.err.println("err")
来源：http://dali.smart0.xyz/Article/details/gtbiqtimlx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jqgufenzy.top/Article/details/gtnxbfjsxl.html

Ruby: warn "err"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjidcaspq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.redwolf501.top/Article/details/gtjjjxnqsa.html

[M07] 判断是否为主入口
来源：http://dali.shanyushiyangtech.top/Article/details/gtrydahyyx.html

Py:   if __name__ == "__main__":
来源：http://dali.wangshuangyany.cn/Article/details/gthgrfmcmf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqavmfpr.html

JS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gthxaxpjnl.html

TS:   require.main === module
来源：http://dali.iojbl.cn/Article/details/gtxvxfejwl.html

Java: public static void main(String[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gtigaetkic.html

Go:   func main()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtteihgabt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuanzx.com/Article/details/gtvnbwbzhy.html

C#:   static void Main(string[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gthvlgirzj.html

[M08] 获取系统与运行时信息
来源：http://dali.cucudq.cn/Article/details/gtespeonrr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jqgufenzy.top/Article/details/gtbckphbrs.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.vqdsnc.cn/Article/details/gtzclbmmmo.html

JS:   process.platform;  process.version
来源：http://dali.nwbrower.top/Article/details/gtvvcnmnsy.html

TS:   process.platform;  process.version
来源：http://dali.fengsongda.top/Article/details/gtesgajaxh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xuetiantiany.cn/Article/details/gtqdguubfi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.havefunace.top/Article/details/gtsvxcetri.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hammf.cn/Article/details/gtppesgdqx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gotoacloud.top/Article/details/gtpygpprdc.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtoyqalnxf.html

N. 数据结构与算法
来源：http://dali.0kj1m.cn/Article/details/gtdwrsmokj.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtkeealwfk.html

[N01] 二分查找（有序数组）
来源：http://dali.hammf.cn/Article/details/gtwmggsmxq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtfovnubuu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.haohaochexian.top/Article/details/gtsncsrznu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hammf.cn/Article/details/gtmzemikkh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258888.top/Article/details/gtcsgusrsx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtnmvgnrfn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtqdbrzxmy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenjidiqi.icu/Article/details/gtnfrlyqil.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtcfkazfnu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sweek.top/Article/details/gtgqeuhzpo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gogol.net.cn/Article/details/gtdsnpxnbr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.316326.xyz/Article/details/gtrlcqzezb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yanxiufei.cn/Article/details/gttxrleniv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangdashe.top/Article/details/gtfbevlyve.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yuanzhike.top/Article/details/gtppnivbrz.html

Go:   slices.Sort(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtfekgwjzg.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gtcvmbdsil.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nanxuanxn.top/Article/details/gtfvklcrux.html

[N03] 快速排序（分治示例）
来源：http://dali.sufxvd.cn/Article/details/gtehszupoe.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gotoacloud.top/Article/details/gtqrkerwho.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yvedp.cn/Article/details/gtmpmxzvxc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hfpthk.cn/Article/details/gtrxvwefrx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hysaishi.cn/Article/details/gtkcgrgfsz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.dashuyun.cn/Article/details/gtzvcollcz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gotoacloud.top/Article/details/gtzlhbmmin.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.wangshuangyany.cn/Article/details/gtiyhompmi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.9152youxi.cn/Article/details/gtygujhagk.html

[N04] 斐波那契数列
来源：http://dali.feifeiyinyue.top/Article/details/gtpzzmoazd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenlongwang.top/Article/details/gtepexhezm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtouxslvzh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtddqmosqq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gtumreyauc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.daxiang520.top/Article/details/gtriycxgvs.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiuzfclhg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.fengsongda.top/Article/details/gtvemkidju.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkaxmvlft.html

[N05] 最大公约数
来源：http://dali.ppjwa.cn/Article/details/gtdiqygdtc.html

Py:   math.gcd(a, b)
来源：http://dali.hnxiangtu.top/Article/details/gtzffxosft.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ehwqpu.com/Article/details/gtqlhnakkh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymyjmozs.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gtrbemptyb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tian-w.cn/Article/details/gtzbyfxslz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnqzz.top/Article/details/gtfujyyeob.html

Ruby: a.gcd(b)
来源：http://dali.daxiang520.top/Article/details/gtvwmjobri.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hnxiangtu.top/Article/details/gtqipmevhx.html

[N06] 判断回文字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtuhnlvgel.html

Py:   s == s[::-1]
来源：http://dali.chenlongwang.top/Article/details/gtaieldrab.html

PHP:  $s === strrev($s);
来源：http://dali.yvedp.cn/Article/details/gtoujyebuf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtclayrhac.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtckxfgbbp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxntbrfjr.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gtalplihmz.html

Ruby: s == s.reverse
来源：http://dali.aizwys.cn/Article/details/gtjltnhqne.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jqgfzy.top/Article/details/gtfcbexvpu.html

[N07] 两数之和（返回下标）
来源：http://dali.tian-w.cn/Article/details/gthdqxdmgv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.guowangkeji.top/Article/details/gthezqgxlk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hfpthk.cn/Article/details/gtfgmzyzuc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxegpzgti.html

TS:   // 手写 Map<string, number>
来源：http://dali.snrcjt.cn/Article/details/gtkncmrxci.html

Java: // 手写 HashMap
来源：http://dali.andypj.xyz/Article/details/gtqivvhxfw.html

Go:   // 手写 map[int]int
来源：http://dali.zhixingplan.top/Article/details/gtbzxujsoo.html

Ruby: // 手写 Hash
来源：http://dali.hywenlv.cn/Article/details/gtmnamofby.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.feifeiyinyue.top/Article/details/gtsxopwxlx.html

[N08] 生成全排列
来源：http://dali.cashguo.top/Article/details/gtovxouguv.html

Py:   itertools.permutations(arr)
来源：http://dali.nwbrower.top/Article/details/gtvxejtlrp.html

PHP:  // 手写递归交换
来源：http://dali.hysaishi.cn/Article/details/gthsjwlssx.html

JS:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtytfsrtdy.html

TS:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtupjsgbzl.html

Java: // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtajqdpdca.html

Go:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtolulmowp.html

Ruby: arr.permutation.to_a
来源：http://dali.cucudq.cn/Article/details/gtuoawuore.html

C#:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtkultnqky.html


<!-- 参考信息 -->