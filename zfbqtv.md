代发 wailian999

TS:   JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gt2pgzbyvlj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qmgbcxno.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gt2mlgaaohx.html

Ruby: JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rconoibw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2bvxxlrwp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dianchejie.cn/Article/details/gt2evmxyalo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zycfv.cn/Article/details/gt2nmthqyts.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cdnleiting.top/Article/details/gt2aqjlahap.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fuaubumg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nhmatlaj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2desaizdw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.dashuyun.cn/Article/details/gt2uuewsggg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj20258.top/Article/details/gt2gorplojg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.birdmap.top/Article/details/gt2lkphrqac.html

[K04] 读取 JSON 文件
来源：http://dali.hammf.cn/Article/details/gt2zcdlxepu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jqgufenzy.top/Article/details/gt2tkvsgonn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinqigfzy.top/Article/details/gt2xbianwty.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pycfn.com/Article/details/gt2npmykpzh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sqbgepjo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sysykeji.top/Article/details/gt2ntivksuu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gt2jpllexnd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gaohongyu789.top/Article/details/gt2uclfzivi.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gotoacloud.top/Article/details/gt2dhujxrow.html

[K05] 深拷贝对象
来源：http://dali.shzxlz.cn/Article/details/gt2agjdmpau.html

Py:   copy.deepcopy(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2jobdkiuh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.birdmap.top/Article/details/gt2sxcsakhk.html

JS:   structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gt2yunozixr.html

TS:   structuredClone(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2wfjxjtmc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.redwolf501.top/Article/details/gt2zmsptmjv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj202588.top/Article/details/gt2lhlcbszf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hywenlv.cn/Article/details/gt2hsaeoukh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jqgfzy.top/Article/details/gt2muvmrxgg.html

[K06] 解析 URL 查询串
来源：http://dali.cashguo.top/Article/details/gt2nruwzpzu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenlongwang.top/Article/details/gt2wijfwyzy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yonumen.top/Article/details/gt2tkqhyuvz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.svipenyu.cn/Article/details/gt2ehtndeke.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guannengcc.top/Article/details/gt2nlkuauav.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jiagoushi.top/Article/details/gt2fqirylcd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.dashuyun.cn/Article/details/gt2hwbnbumg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gt2vlfwbjwr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gt2xevbzycr.html

[K07] 进制转换
来源：http://dali.aizwys.cn/Article/details/gt2koyakbwv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gt2gkjxaijl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tianlin.xyz/Article/details/gt2jlkninrp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2uisvvemx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gt2mscwxvhv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2yzlmktvd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daria6918.cn/Article/details/gt2xnbavbwi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.aizwys.cn/Article/details/gt2cuifojsi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gt2qbpsbfto.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj202588.top/Article/details/gt2hikaokeq.html

Py:   pickle.dumps(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2wudnplmp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ehwqpu.com/Article/details/gt2kpmepayy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gt2jybyczfn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gt2wugjqsyi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nwbrower.top/Article/details/gt2egntrrxt.html

Go:   encoding/gob
来源：http://dali.gzhubu.top/Article/details/gt2cvqivtwh.html

Ruby: Marshal.dump(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2pgmtbist.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gt2mdtqhgrv.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2siwhwraf.html

L. 网络请求
来源：http://dali.jinqigfzy.top/Article/details/gt2wltjcdku.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hnhueshm.html

[L01] 发送 GET 请求
来源：http://dali.sufxvd.cn/Article/details/gt2vretwqxr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gdlbkkvm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gogol.net.cn/Article/details/gt2rwmdlvzt.html

JS:   await fetch(url)
来源：http://dali.jlsjyb.cn/Article/details/gt2gipietve.html

TS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lvtifymj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.dashuyun.cn/Article/details/gt2tnyvrtwu.html

Go:   resp, err := http.Get(url)
来源：http://dali.9152youxi.cn/Article/details/gt2ifdduxuw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.fengsongda.top/Article/details/gt2unjoocwa.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tanke756.top/Article/details/gt2onsvsrqx.html

[L02] 发送 POST JSON
来源：http://dali.yj202588.top/Article/details/gt2ukgdkefz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2umlylrvm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nwbrower.top/Article/details/gt2qbedykcf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhengqikj.top/Article/details/gt2zudfamru.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hongshengwenyu.top/Article/details/gt2syntbsud.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.feifeiyinyue.top/Article/details/gt2owtpnryf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhengqikj.top/Article/details/gt2hzkmuzju.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jianghu66.top/Article/details/gt2hgigenyf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jyoumei.cn/Article/details/gt2xecprosw.html

[L03] 设置自定义请求头
来源：http://dali.cheryme.top/Article/details/gt2pztxvwrq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vtwujtxn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cucudq.cn/Article/details/gt2ujjatvvi.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhongyouzk.top/Article/details/gt2mjwyeehj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shzxlz.cn/Article/details/gt2gvhbvugr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yuxming.cn/Article/details/gt2sqnqigqn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pycfn.com/Article/details/gt2zjcmbidh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yongpay.top/Article/details/gt2spenyoaf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xqpobbsm.html

[L04] 设置超时
来源：http://dali.feifeiyinyue.top/Article/details/gt2sejlnvwl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hammf.cn/Article/details/gt2gohdbgrb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tiqtcyfe.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tian-w.cn/Article/details/gt2zpvzuggc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daria6918.cn/Article/details/gt2vuhvsmis.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yewhclup.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj20258.top/Article/details/gt2ijiwplot.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hammf.cn/Article/details/gt2ppdtkiba.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aizwys.cn/Article/details/gt2udvqstzu.html

[L05] 上传文件（multipart）
来源：http://dali.yongpay.top/Article/details/gt2vunadzhq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.pengpengdd.cyou/Article/details/gt2eznemkmx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xylfe.cn/Article/details/gt2uedqsmaf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.havefunace.top/Article/details/gt2fewxlfoe.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuxming.cn/Article/details/gt2nmdgjdgr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ybcxt.top/Article/details/gt2nshayswz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ivvv.top/Article/details/gt2kpdbjgif.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shuidangran.top/Article/details/gt2uyzwleef.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zicfowca.html

[L06] 解析响应为 JSON
来源：http://dali.zdqjudy.top/Article/details/gt2hcjfmerv.html

Py:   resp.json()
来源：http://dali.meibo888.top/Article/details/gt2cqevgwjr.html

PHP:  json_decode($body, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ugsqdems.html

JS:   await resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gt2miqscgxw.html

TS:   await resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gt2brbzxgdl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj20258888.top/Article/details/gt2vupwveqe.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cashguo.top/Article/details/gt2acewowcv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hongshengwenyu.top/Article/details/gt2sgqzhjwo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hysaishi.cn/Article/details/gt2agcigigw.html

[L07] 处理 HTTP 状态码
来源：http://dali.ppjwa.cn/Article/details/gt2yaydzads.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.redwolf501.top/Article/details/gt2xicychxq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sxryk.cn/Article/details/gt2etacmkgz.html

JS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gt2lojaslqp.html

TS:   resp.ok;  resp.status
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2poepxifc.html

Java: resp.statusCode()
来源：http://dali.feifeiyinyue.top/Article/details/gt2hzbicnxc.html

Go:   resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gt2nkqcsbcp.html

Ruby: resp.code.to_i
来源：http://dali.wangdashe.top/Article/details/gt2azdbconn.html

C#:   (int)resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2khlwbvxs.html

[L08] 并发请求多个地址
来源：http://dali.smart0.xyz/Article/details/gt2iuewvphx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gotoacloud.top/Article/details/gt2uuqdsyrt.html

PHP:  curl_multi_init() 系列
来源：http://dali.xuanzx.com/Article/details/gt2juuxvmzg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jbqmgdkt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aibaodan.cn/Article/details/gt2hdapcyve.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhongyouzk.top/Article/details/gt2wanrgoxm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.redwolf501.top/Article/details/gt2jtgokfgh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gevacgok.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yongpay.top/Article/details/gt2ryauahck.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mvpreqje.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ugaxftzm.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2hypbqbzq.html

[M01] 读取命令行参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2pcndzmhf.html

Py:   sys.argv[1:]
来源：http://dali.zhengqikj.top/Article/details/gt2pxooaojf.html

PHP:  $argv;  $argc;
来源：http://dali.jyoumei.cn/Article/details/gt2tqwlahqa.html

JS:   process.argv.slice(2)
来源：http://dali.hnqzz.top/Article/details/gt2aobantfg.html

TS:   process.argv.slice(2)
来源：http://dali.zhongyouzk.top/Article/details/gt2xzkvfyfi.html

Java: args 数组（main 方法参数）
来源：http://dali.fzhhl.top/Article/details/gt2pgjuaark.html

Go:   os.Args[1:]
来源：http://dali.aizwys.cn/Article/details/gt2maflxilb.html

Ruby: ARGV
来源：http://dali.shuidangran.top/Article/details/gt2vxecftbo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.daria6918.cn/Article/details/gt2xqwjznmp.html

[M02] 读取环境变量
来源：http://dali.wangdashe.top/Article/details/gt2xuuhvtgd.html

Py:   os.environ.get("HOME")
来源：http://dali.cqqwz.cn/Article/details/gt2aiuiyhwy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangdashe.top/Article/details/gt2estoaquo.html

JS:   process.env.HOME
来源：http://dali.tianlin.xyz/Article/details/gt2jtyscybf.html

TS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gt2dklickxw.html

Java: System.getenv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gt2dsuunmtv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinqigufen.top/Article/details/gt2cnoiufea.html

Ruby: ENV["HOME"]
来源：http://dali.jqgufenzy.top/Article/details/gt2ynsckkzz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2dhtfkayw.html

[M03] 执行外部命令
来源：http://dali.tanke756.top/Article/details/gt2ywqaaafd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.svipenyu.cn/Article/details/gt2awszivdl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.9152youxi.cn/Article/details/gt2drthrabl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.svipenyu.cn/Article/details/gt2mqmqfcuh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gt2xrvrxgid.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.c1oappe.top/Article/details/gt2rdlmgobe.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tianlin.xyz/Article/details/gt2gqmvmapl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.meibo888.top/Article/details/gt2ncrlbcrt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jqgufenzy.top/Article/details/gt2smvdbylx.html

[M04] 获取当前工作目录
来源：http://dali.nanxuanxn.top/Article/details/gt2qbtbkjlk.html

Py:   os.getcwd()
来源：http://dali.ivvv.top/Article/details/gt2ckjhreyz.html

PHP:  getcwd();
来源：http://dali.hnqzz.top/Article/details/gt2uszdanux.html

JS:   process.cwd()
来源：http://dali.quarkkingdee.top/Article/details/gt2iyynvrbm.html

TS:   process.cwd()
来源：http://dali.tanke756.top/Article/details/gt2lysmigyq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rvaikmaz.html

Go:   os.Getwd()
来源：http://dali.sweek.top/Article/details/gt2pvyxokxu.html

Ruby: Dir.pwd
来源：http://dali.yuanzhike.top/Article/details/gt2bfbfocgz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bxungqjd.html

[M05] 设置退出码
来源：http://dali.zycfv.cn/Article/details/gt2slagatzw.html

Py:   sys.exit(1)
来源：http://dali.jianghu66.top/Article/details/gt2lvzbvwua.html

PHP:  exit(1);
来源：http://dali.vqdsnc.cn/Article/details/gt2iynrortm.html

JS:   process.exit(1)
来源：http://dali.yj20258.top/Article/details/gt2qneidnsd.html

TS:   process.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2oiirwhtb.html

Java: System.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gt2chirovmi.html

Go:   os.Exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2becquzng.html

Ruby: exit 1
来源：http://dali.hywenlv.cn/Article/details/gt2ywtohtkp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yonumen.top/Article/details/gt2wulnwdqu.html

[M06] 向标准错误输出
来源：http://dali.zdqjudy.top/Article/details/gt2gzfnicor.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenlongwang.top/Article/details/gt2jexvmqap.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.kuanghao11.cn/Article/details/gt2feummrng.html

JS:   console.error("err")
来源：http://dali.guowangkeji.top/Article/details/gt2hejminuf.html

TS:   console.error("err")
来源：http://dali.redwolf501.top/Article/details/gt2jbkyunhu.html

Java: System.err.println("err")
来源：http://dali.bjfxy.top/Article/details/gt2ceqibknr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.meibo888.top/Article/details/gt2mblcsgac.html

Ruby: warn "err"
来源：http://dali.jiagoushi.top/Article/details/gt2uxvupqpl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.redwolf501.top/Article/details/gt2qmhuetwe.html

[M07] 判断是否为主入口
来源：http://dali.ppjwa.cn/Article/details/gt2snxqxvel.html

Py:   if __name__ == "__main__":
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eughzsxs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuxming.cn/Article/details/gt2ksvnltkq.html

JS:   require.main === module
来源：http://dali.guowangkeji.top/Article/details/gt2glfxixkj.html

TS:   require.main === module
来源：http://dali.xinyue.icu/Article/details/gt2ymvsiudc.html

Java: public static void main(String[] args)
来源：http://dali.bjfxy.top/Article/details/gt2gsbzkmhs.html

Go:   func main()
来源：http://dali.quarkkingdee.top/Article/details/gt2rzjjqxwb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jqgufenzy.top/Article/details/gt2kaffysts.html

C#:   static void Main(string[] args)
来源：http://dali.tanke756.top/Article/details/gt2lrtqjgpn.html

[M08] 获取系统与运行时信息
来源：http://dali.quarkkingdee.top/Article/details/gt2jvutlyek.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shuidangran.top/Article/details/gt2yrqtouzo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.guowangkeji.top/Article/details/gt2ugrnpewb.html

JS:   process.platform;  process.version
来源：http://dali.cheryme.top/Article/details/gt2aisfgebi.html

TS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gt2lxzjhgmj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhoulong.xyz/Article/details/gt2vfrvvnup.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jianghu66.top/Article/details/gt2oqlrhqym.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2swziomdf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hammf.cn/Article/details/gt2ythaxrhh.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2jrafxmkv.html

N. 数据结构与算法
来源：http://dali.cheryme.top/Article/details/gt2pwzctqqo.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2skxivhjf.html

[N01] 二分查找（有序数组）
来源：http://dali.chenzaomai.com/Article/details/gt2udtkafkd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gnjmioog.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jyoumei.cn/Article/details/gt2yldfzhar.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jyoumei.cn/Article/details/gt2xnytgfdq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gt2jjakfbur.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gt2cwzdhrat.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2xnkbvwvm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shzxlz.cn/Article/details/gt2povkuisj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2olpgidbt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yuxming.cn/Article/details/gt2gjljjrjg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gt2bwgfjtrb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.guowangkeji.top/Article/details/gt2nuuycptl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sysykeji.top/Article/details/gt2prjdethp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gt2wwvhtvaf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lmkyikgn.html

Go:   slices.Sort(arr)
来源：http://dali.xziqi.cn/Article/details/gt2hotgaoce.html

Ruby: arr.sort
来源：http://dali.aizwys.cn/Article/details/gt2lnsugbhe.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.fzhhl.top/Article/details/gt2ctdcmxpc.html

[N03] 快速排序（分治示例）
来源：http://dali.cashguo.top/Article/details/gt2ztxreehz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hywenlv.cn/Article/details/gt2xochnmha.html

PHP:  // 递归实现，或用 usort
来源：http://dali.fengsongda.top/Article/details/gt2dgslzjtm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shangyingyoupin.top/Article/details/gt2ejpkdvjz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fengsongda.top/Article/details/gt2xliqurwc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yfuofzus.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yueranfly.top/Article/details/gt2jlmfehkq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sxryk.cn/Article/details/gt2lhpkuihs.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gaohongyu789.top/Article/details/gt2wdkvpxde.html

[N04] 斐波那契数列
来源：http://dali.smart0.xyz/Article/details/gt2idgmxfjl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hfpthk.cn/Article/details/gt2mphgigrt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.guannengcc.top/Article/details/gt2xvhatzmv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gt2cxiqhivx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gt2vfdcojsq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2gdmtrhfi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shuidangran.top/Article/details/gt2apwsmzpl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cqqwz.cn/Article/details/gt2xlguxwnl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gt2nedicgkt.html

[N05] 最大公约数
来源：http://dali.jlsjyb.cn/Article/details/gt2domhzcuu.html

Py:   math.gcd(a, b)
来源：http://dali.guowangkeji.top/Article/details/gt2bcfeiyfp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.iojbl.cn/Article/details/gt2jsoallxb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxuanxn.top/Article/details/gt2sprizjzu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gt2pyoruaab.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.iojbl.cn/Article/details/gt2murptpry.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.svipenyu.cn/Article/details/gt2uigxmrza.html

Ruby: a.gcd(b)
来源：http://dali.jqgufenzy.top/Article/details/gt2jxarphju.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jyoumei.cn/Article/details/gt2zxjnnojf.html

[N06] 判断回文字符串
来源：http://dali.sxryk.cn/Article/details/gt2vfeidypi.html

Py:   s == s[::-1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2qdegblck.html

PHP:  $s === strrev($s);
来源：http://dali.dianchejie.cn/Article/details/gt2jsmyrnvm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gt2coeosion.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gt2hxmsqrlx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xziqi.cn/Article/details/gt2shnabwgy.html

Go:   // 双指针从两端比较
来源：http://dali.xylfe.cn/Article/details/gt2wfocmvsb.html

Ruby: s == s.reverse
来源：http://dali.chenzaomai.com/Article/details/gt2xqrpzdiv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ehwqpu.com/Article/details/gt2symehhee.html

[N07] 两数之和（返回下标）
来源：http://dali.yj20258.top/Article/details/gt2yxyjjkqb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj20258888.top/Article/details/gt2ubvfhriz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.meibo888.top/Article/details/gt2usotkdbj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tian-w.cn/Article/details/gt2xmgyezyx.html

TS:   // 手写 Map<string, number>
来源：http://dali.svipenyu.cn/Article/details/gt2qehugdsm.html

Java: // 手写 HashMap
来源：http://dali.ppjwa.cn/Article/details/gt2cyttrypi.html

Go:   // 手写 map[int]int
来源：http://dali.snrcjt.cn/Article/details/gt2jtidwfar.html

Ruby: // 手写 Hash
来源：http://dali.hfpthk.cn/Article/details/gt2kqghsmyf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.0kj1m.cn/Article/details/gt2keltgkfc.html

[N08] 生成全排列
来源：http://dali.quarkkingdee.top/Article/details/gt2dhpjyhtf.html

Py:   itertools.permutations(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2ykhuhswc.html

PHP:  // 手写递归交换
来源：http://dali.jqgfzy.top/Article/details/gt2pahgvzem.html

JS:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gt2mwhooees.html

TS:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gt2huczqzck.html

Java: // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gt2qvewkoqz.html

Go:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gt2ivkyilbd.html

Ruby: arr.permutation.to_a
来源：http://dali.chenjidiqi.icu/Article/details/gt2midhimsg.html

C#:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gt2qfhkgcpg.html

[N09] 栈与队列
来源：http://dali.jyoumei.cn/Article/details/gt2ywvesqxi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.bjfxy.top/Article/details/gt2kbidynwi.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jianghu66.top/Article/details/gt2ntxjsyag.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2esuharme.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hfpthk.cn/Article/details/gt2mxzxwpty.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.aibaodan.cn/Article/details/gt2bqtgncwq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yongpay.top/Article/details/gt2feebevng.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gt2jpslfxui.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.snrcjt.cn/Article/details/gt2seibvxep.html

[N10] 链表节点定义
来源：http://dali.yj20258888.top/Article/details/gt2lmrbgimp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hfrhqodu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2cazbtruc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gzhubu.top/Article/details/gt2znfzhkhy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cheryme.top/Article/details/gt2joznlqww.html

Java: class Node { int v; Node next; }
来源：http://dali.cashguo.top/Article/details/gt2euhpdfou.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.haohaochexian.top/Article/details/gt2pqgntpgy.html


<!-- 参考信息 -->