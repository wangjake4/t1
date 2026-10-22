代发 wailian999

[K02] JSON 字符串转对象
来源：http://dali.svipenyu.cn/Article/details/gt2bngeidml.html

Py:   json.loads(s)
来源：http://dali.yuxming.cn/Article/details/gt2hjnulnyu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hfpthk.cn/Article/details/gt2kvbheczz.html

JS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gt2qqrriuwk.html

TS:   JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gt2bqekhmld.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.bjfxy.top/Article/details/gt2zndmkbjg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gogol.net.cn/Article/details/gt2xzrptaqc.html

Ruby: JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gt2fzqdtvyd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jyoumei.cn/Article/details/gt2wrybqnbx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zycfv.cn/Article/details/gt2vymtuzli.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.kuanghao11.cn/Article/details/gt2cvgqhvsx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gt2bnorgnkv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.dashuyun.cn/Article/details/gt2agihezbi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eiqnosfq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2wdctacjh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj202588.top/Article/details/gt2snequtox.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2lwudynrw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.redwolf501.top/Article/details/gt2rpnvezue.html

[K04] 读取 JSON 文件
来源：http://dali.zhengqikj.top/Article/details/gt2jzarjkch.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.kuanghao11.cn/Article/details/gt2eawftpld.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.guowangkeji.top/Article/details/gt2evkqhiaz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgufenzy.top/Article/details/gt2vtkjorzd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cucudq.cn/Article/details/gt2gcaznpqy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hnqzz.top/Article/details/gt2dvtysced.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yueranfly.top/Article/details/gt2imgapaxm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj20258.top/Article/details/gt2tudqehpq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dashuyun.cn/Article/details/gt2ebpibmtw.html

[K05] 深拷贝对象
来源：http://dali.gaohongyu789.top/Article/details/gt2lydfrbuy.html

Py:   copy.deepcopy(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2rakzhzpq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.0kj1m.cn/Article/details/gt2kokobnke.html

JS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gt2zdxaqgjv.html

TS:   structuredClone(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2frieclfq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.redwolf501.top/Article/details/gt2mdzxmwur.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shuidangran.top/Article/details/gt2hadwulid.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.fzhhl.top/Article/details/gt2vbdizahs.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sxryk.cn/Article/details/gt2vxcovsrd.html

[K06] 解析 URL 查询串
来源：http://dali.9152youxi.cn/Article/details/gt2rwrzslgm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenjidiqi.icu/Article/details/gt2xgwlehcu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yueranfly.top/Article/details/gt2mxqpuinl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dashuyun.cn/Article/details/gt2ujcovwwz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.0kj1m.cn/Article/details/gt2gsmxmdqp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinqigfzy.top/Article/details/gt2llhyyrea.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gt2nophlovw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gt2uilisdbu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gt2quwxgznb.html

[K07] 进制转换
来源：http://dali.daxiang520.top/Article/details/gt2gtokxkrs.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gt2xyomviia.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cashguo.top/Article/details/gt2dswjqham.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gt2jklucxmt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gt2ovxzcbpv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2mbszgptd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhixingplan.top/Article/details/gt2gbjrfjmo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tian-w.cn/Article/details/gt2kypogriu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2bosttfiq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.guowangkeji.top/Article/details/gt2drztoeop.html

Py:   pickle.dumps(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2ysvkfjmn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tianlin.xyz/Article/details/gt2qwrvgybg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gt2rdyrbhts.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shzxlz.cn/Article/details/gt2pklyinzj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.pycfn.com/Article/details/gt2mkccgpdf.html

Go:   encoding/gob
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wpdpmubx.html

Ruby: Marshal.dump(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bzwmbabl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.pycfn.com/Article/details/gt2fkseeujf.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2axmwysdl.html

L. 网络请求
来源：http://dali.sxryk.cn/Article/details/gt2omxnsuia.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2dymicuzt.html

[L01] 发送 GET 请求
来源：http://dali.xziqi.cn/Article/details/gt2ctpbyjud.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.redwolf501.top/Article/details/gt2kbuexxsf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jqgufenzy.top/Article/details/gt2dfndnuel.html

JS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tssjcces.html

TS:   await fetch(url)
来源：http://dali.cqqwz.cn/Article/details/gt2tsqftnak.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jiagoushi.top/Article/details/gt2rytbtylv.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhixingplan.top/Article/details/gt2wccrcjah.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnxiangtu.top/Article/details/gt2mjaxfcyy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.smart0.xyz/Article/details/gt2megcdrli.html

[L02] 发送 POST JSON
来源：http://dali.zhiwuduotai.top/Article/details/gt2xtpggars.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.aibaodan.cn/Article/details/gt2xizqfthy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj20258.top/Article/details/gt2wjeuowqs.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gogol.net.cn/Article/details/gt2vkvpgjaz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.snrcjt.cn/Article/details/gt2fbpenvyt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jlsjyb.cn/Article/details/gt2spcmhbab.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tian-w.cn/Article/details/gt2wguzzluu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sxryk.cn/Article/details/gt2kdmzkmsx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.birdmap.top/Article/details/gt2vexjridk.html

[L03] 设置自定义请求头
来源：http://dali.aizwys.cn/Article/details/gt2fpvoxods.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.pengpengdd.cyou/Article/details/gt2lcwdlzem.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.daxiang520.top/Article/details/gt2lowlbuny.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yueranfly.top/Article/details/gt2csovnxgb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tianlin.xyz/Article/details/gt2vyesrkcy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tian-w.cn/Article/details/gt2jumuraeh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cqqwz.cn/Article/details/gt2jvwnajdt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.havefunace.top/Article/details/gt2xehcunvm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xinyue.icu/Article/details/gt2zbjpnhtq.html

[L04] 设置超时
来源：http://dali.zdqjudy.top/Article/details/gt2pgxhsskx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nanxuanxn.top/Article/details/gt2ivjrgrnl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhiwuduotai.top/Article/details/gt2iemazhti.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zycfv.cn/Article/details/gt2wsaycchw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aibaodan.cn/Article/details/gt2npumzaho.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gaohongyu789.top/Article/details/gt2csdozica.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj20258.top/Article/details/gt2vxxvilfk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ehwqpu.com/Article/details/gt2xwolardp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.iojbl.cn/Article/details/gt2gsoesdps.html

[L05] 上传文件（multipart）
来源：http://dali.hnxiangtu.top/Article/details/gt2vfyamggh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhengqikj.top/Article/details/gt2llkmciza.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2shxpshrg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gt2biihhsil.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gt2wvjqmhql.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guowangkeji.top/Article/details/gt2juueohte.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.quarkkingdee.top/Article/details/gt2ypiamshu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dianchejie.cn/Article/details/gt2rqideoml.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2inwlrbou.html

[L06] 解析响应为 JSON
来源：http://dali.daxiang520.top/Article/details/gt2olshsgws.html

Py:   resp.json()
来源：http://dali.snrcjt.cn/Article/details/gt2qpqjbnkv.html

PHP:  json_decode($body, true);
来源：http://dali.snrcjt.cn/Article/details/gt2baikmgla.html

JS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gt2mkddmraq.html

TS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wfvzxohs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sxryk.cn/Article/details/gt2skzooqiy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.wangdashe.top/Article/details/gt2zzchruih.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yangfankeji.com/Article/details/gt2bkipvbpw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shuidangran.top/Article/details/gt2gspozeud.html

[L07] 处理 HTTP 状态码
来源：http://dali.xylfe.cn/Article/details/gt2vgbszudu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ydzc1.top/Article/details/gt2rovomdys.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuxming.cn/Article/details/gt2rwirezor.html

JS:   resp.ok;  resp.status
来源：http://dali.cheryme.top/Article/details/gt2libmlozo.html

TS:   resp.ok;  resp.status
来源：http://dali.shuidangran.top/Article/details/gt2btuqhedw.html

Java: resp.statusCode()
来源：http://dali.cucudq.cn/Article/details/gt2bmrmpsih.html

Go:   resp.StatusCode
来源：http://dali.jqgfzy.top/Article/details/gt2vhlvfdvd.html

Ruby: resp.code.to_i
来源：http://dali.zhengqikj.top/Article/details/gt2jwjbbprf.html

C#:   (int)resp.StatusCode
来源：http://dali.zhixingplan.top/Article/details/gt2ktvvgtyc.html

[L08] 并发请求多个地址
来源：http://dali.shuidangran.top/Article/details/gt2hbwwxncy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ivvv.top/Article/details/gt2eeudodfb.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhengqikj.top/Article/details/gt2kdlivczw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gt2wtvukwze.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gt2zngeftyj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cheryme.top/Article/details/gt2gozinslp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yonumen.top/Article/details/gt2inhjkteb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2keijhhrf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bnotwzei.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2lyextydp.html

M. 命令行 / 进程 / 环境
来源：http://dali.birdmap.top/Article/details/gt2tordtthi.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2ziyzylue.html

[M01] 读取命令行参数
来源：http://dali.c1oappe.top/Article/details/gt2sbmabtye.html

Py:   sys.argv[1:]
来源：http://dali.shzxlz.cn/Article/details/gt2hifhjonf.html

PHP:  $argv;  $argc;
来源：http://dali.hnqzz.top/Article/details/gt2engccxli.html

JS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gt2kzxnbzel.html

TS:   process.argv.slice(2)
来源：http://dali.andypj.xyz/Article/details/gt2fwbocvrz.html

Java: args 数组（main 方法参数）
来源：http://dali.tianlin.xyz/Article/details/gt2okoyozkr.html

Go:   os.Args[1:]
来源：http://dali.aibaodan.cn/Article/details/gt2eboaahkx.html

Ruby: ARGV
来源：http://dali.svipenyu.cn/Article/details/gt2catizwuu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2etlmnuje.html

[M02] 读取环境变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dhsmdjdw.html

Py:   os.environ.get("HOME")
来源：http://dali.hnqzz.top/Article/details/gt2sakskrfd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jianghu66.top/Article/details/gt2hrtmaduq.html

JS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gt2qiurmsfh.html

TS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gt2itidghds.html

Java: System.getenv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gt2rlogfjkv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yongpay.top/Article/details/gt2jruoewac.html

Ruby: ENV["HOME"]
来源：http://dali.haohaochexian.top/Article/details/gt2cnkwpucr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gt2jfgcnpng.html

[M03] 执行外部命令
来源：http://dali.cucudq.cn/Article/details/gt2ynivedji.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yuxming.cn/Article/details/gt2jqqpltzo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sysykeji.top/Article/details/gt2nizktood.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nwbrower.top/Article/details/gt2dsbygqfz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gt2fbxeepyd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ppjwa.cn/Article/details/gt2whvexkik.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zdqjudy.top/Article/details/gt2idrqplfy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.pycfn.com/Article/details/gt2kfojrqer.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daria6918.cn/Article/details/gt2vpiitvlf.html

[M04] 获取当前工作目录
来源：http://dali.yj20258888.top/Article/details/gt2dbsvqfrf.html

Py:   os.getcwd()
来源：http://dali.kuanghao11.cn/Article/details/gt2fobrzqaj.html

PHP:  getcwd();
来源：http://dali.wangshuangyany.cn/Article/details/gt2ghqinamj.html

JS:   process.cwd()
来源：http://dali.hywenlv.cn/Article/details/gt2fxufihin.html

TS:   process.cwd()
来源：http://dali.jqgfzy.top/Article/details/gt2ollwuawe.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xylfe.cn/Article/details/gt2lgajmulc.html

Go:   os.Getwd()
来源：http://dali.tian-w.cn/Article/details/gt2hvxdjcev.html

Ruby: Dir.pwd
来源：http://dali.nwbrower.top/Article/details/gt2ydtdwxab.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.wangdashe.top/Article/details/gt2cgdsnmoc.html

[M05] 设置退出码
来源：http://dali.meibo888.top/Article/details/gt2cbrpomhc.html

Py:   sys.exit(1)
来源：http://dali.aizwys.cn/Article/details/gt2iilmbxzb.html

PHP:  exit(1);
来源：http://dali.zhengqikj.top/Article/details/gt2zejrxmvl.html

JS:   process.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vztbjdqm.html

TS:   process.exit(1)
来源：http://dali.yongpay.top/Article/details/gt2iucvpxha.html

Java: System.exit(1)
来源：http://dali.yj20258888.top/Article/details/gt2gdkvsgfx.html

Go:   os.Exit(1)
来源：http://dali.iojbl.cn/Article/details/gt2tujxeubd.html

Ruby: exit 1
来源：http://dali.fzhhl.top/Article/details/gt2awedhwsf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhongyouzk.top/Article/details/gt2xmwmieww.html

[M06] 向标准错误输出
来源：http://dali.shangyingyoupin.top/Article/details/gt2ezslteyu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.daria6918.cn/Article/details/gt2zvkmjvit.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.haohaochexian.top/Article/details/gt2krdpdwsl.html

JS:   console.error("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qnqdpxsx.html

TS:   console.error("err")
来源：http://dali.yueranfly.top/Article/details/gt2sdyrzckx.html

Java: System.err.println("err")
来源：http://dali.xuanzx.com/Article/details/gt2opsnopbe.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ybcxt.top/Article/details/gt2juzbbfyc.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2usmspeoq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hammf.cn/Article/details/gt2aiageonk.html

[M07] 判断是否为主入口
来源：http://dali.yongpay.top/Article/details/gt2ycrdeyha.html

Py:   if __name__ == "__main__":
来源：http://dali.xylfe.cn/Article/details/gt2lohljexj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.mhx1999.top/Article/details/gt2poiuhdhq.html

JS:   require.main === module
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fdaezpcs.html

TS:   require.main === module
来源：http://dali.hnqzz.top/Article/details/gt2cqrygoql.html

Java: public static void main(String[] args)
来源：http://dali.bjfxy.top/Article/details/gt2zloakrui.html

Go:   func main()
来源：http://dali.pycfn.com/Article/details/gt2zybrczcd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj20258.top/Article/details/gt2wusghvum.html

C#:   static void Main(string[] args)
来源：http://dali.9152youxi.cn/Article/details/gt2qgdswogh.html

[M08] 获取系统与运行时信息
来源：http://dali.gaohongyu789.top/Article/details/gt2pdrsduiv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yueranfly.top/Article/details/gt2hdmulttv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cashguo.top/Article/details/gt2khgtajzg.html

JS:   process.platform;  process.version
来源：http://dali.ydzc1.top/Article/details/gt2xveaxhsh.html

TS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gt2idfmgcoq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hysaishi.cn/Article/details/gt2iwueqoay.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.haohaochexian.top/Article/details/gt2fqqjtrjc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ehwqpu.com/Article/details/gt2ehhvgnor.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shangyingyoupin.top/Article/details/gt2vazdmxay.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2nibphjgr.html

N. 数据结构与算法
来源：http://dali.hfpthk.cn/Article/details/gt2lwulrqck.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2tdhmbmul.html

[N01] 二分查找（有序数组）
来源：http://dali.nwbrower.top/Article/details/gt2kgbkzxdt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gt2cgxgfgll.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj20258.top/Article/details/gt2yaqdauls.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yvedp.cn/Article/details/gt2jxhrbgok.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yangfankeji.com/Article/details/gt2otczzklr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2indjdisy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.tian-w.cn/Article/details/gt2laprjwya.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.kuanghao11.cn/Article/details/gt2osdaccxs.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.pycfn.com/Article/details/gt2erqbzonx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.feifeiyinyue.top/Article/details/gt2qyhjfbso.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pycfn.com/Article/details/gt2mpgxqnfi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gllbvxei.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gt2jnhtniaw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gt2hwxuuyue.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jlsjyb.cn/Article/details/gt2utnzvrsn.html

Go:   slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2susyiluw.html

Ruby: arr.sort
来源：http://dali.ehwqpu.com/Article/details/gt2zguyfvkl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.pengpengdd.cyou/Article/details/gt2tqzxvuzl.html

[N03] 快速排序（分治示例）
来源：http://dali.quarkkingdee.top/Article/details/gt2enyysixt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sweek.top/Article/details/gt2jvgjhnuc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.meibo888.top/Article/details/gt2roxduisn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.haohaochexian.top/Article/details/gt2ueoxhohq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tokgzebp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.feifeiyinyue.top/Article/details/gt2xsvgzkrd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.fzhhl.top/Article/details/gt2watqwcmb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jiagoushi.top/Article/details/gt2jwlizrqm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.meibo888.top/Article/details/gt2wzivgyua.html

[N04] 斐波那契数列
来源：http://dali.yongpay.top/Article/details/gt2uhwkzzvc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.9152youxi.cn/Article/details/gt2dowzapph.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2fhikhrfv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gt2uhfaxwug.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gt2pvcxvbov.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yuanzhike.top/Article/details/gt2sinsbjnt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hnqzz.top/Article/details/gt2fxdeuxne.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.redwolf501.top/Article/details/gt2ognvucts.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gt2qdscpxfz.html

[N05] 最大公约数
来源：http://dali.haohaochexian.top/Article/details/gt2ibmbpozx.html

Py:   math.gcd(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gt2lijpbscw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinqigufen.top/Article/details/gt2vyzrkucg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2fhbdethb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jlsjyb.cn/Article/details/gt2szogqjhx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nanxinkj.top/Article/details/gt2jyavpcys.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnxiangtu.top/Article/details/gt2rwaxlnzt.html

Ruby: a.gcd(b)
来源：http://dali.snrcjt.cn/Article/details/gt2qjtstaff.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jiagoushi.top/Article/details/gt2jqfjqcgv.html

[N06] 判断回文字符串
来源：http://dali.dashuyun.cn/Article/details/gt2klujjneu.html

Py:   s == s[::-1]
来源：http://dali.yj202588.top/Article/details/gt2eymgwtcu.html

PHP:  $s === strrev($s);
来源：http://dali.shuidangran.top/Article/details/gt2wnxbvqmj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gt2ndyaqgye.html

TS:   s === [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gt2ryyjsonm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenlongwang.top/Article/details/gt2gsnyyjjh.html

Go:   // 双指针从两端比较
来源：http://dali.gogol.net.cn/Article/details/gt2iggtwvgp.html

Ruby: s == s.reverse
来源：http://dali.mhx1999.top/Article/details/gt2gjamqkfs.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yonumen.top/Article/details/gt2dhoprorq.html

[N07] 两数之和（返回下标）
来源：http://dali.daxiang520.top/Article/details/gt2qkomwuzw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj202588.top/Article/details/gt2nlzwpimi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.dianchejie.cn/Article/details/gt2trnexsxg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cdnleiting.top/Article/details/gt2zfselirv.html

TS:   // 手写 Map<string, number>
来源：http://dali.aizwys.cn/Article/details/gt2wmtynzbc.html

Java: // 手写 HashMap
来源：http://dali.pengpengdd.cyou/Article/details/gt2mewlmwft.html

Go:   // 手写 map[int]int
来源：http://dali.xinyue.icu/Article/details/gt2nntfpxbk.html

Ruby: // 手写 Hash
来源：http://dali.daxiang520.top/Article/details/gt2ojkduvpz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gotoacloud.top/Article/details/gt2wsdhuzjz.html

[N08] 生成全排列
来源：http://dali.ppjwa.cn/Article/details/gt2ptrrxsbk.html

Py:   itertools.permutations(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2vjxdgaeo.html

PHP:  // 手写递归交换
来源：http://dali.yueranfly.top/Article/details/gt2gpbqjkxc.html

JS:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gt2dxyagdpi.html

TS:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2srttzxpt.html

Java: // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gt2zvbmyvzn.html

Go:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gt2xscelmoq.html

Ruby: arr.permutation.to_a
来源：http://dali.yonumen.top/Article/details/gt2sfwuhcao.html

C#:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2csvduwwh.html

[N09] 栈与队列
来源：http://dali.zhoulong.xyz/Article/details/gt2vidpsvbs.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.haohaochexian.top/Article/details/gt2dapkqxep.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ivvv.top/Article/details/gt2nxpxpjco.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gt2vzffxavv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrgueqd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.guowangkeji.top/Article/details/gt2uvfpeqzs.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jiagoushi.top/Article/details/gt2nxtttkcf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.aizwys.cn/Article/details/gt2vbscwyxe.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.daxiang520.top/Article/details/gt2qjqrbeva.html

[N10] 链表节点定义
来源：http://dali.ybcxt.top/Article/details/gt2zcddtdya.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xuetiantiany.cn/Article/details/gt2rimjagen.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zycfv.cn/Article/details/gt2ncrnipzd.html


<!-- 参考信息 -->