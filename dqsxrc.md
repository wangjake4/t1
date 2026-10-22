代发 wailian999

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.dianchejie.cn/Article/details/gt2mavfwyld.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhiwuduotai.top/Article/details/gt2wfppydgp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dashuyun.cn/Article/details/gt2akwnxkki.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hnxiangtu.top/Article/details/gt2utfjsfpg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gt2bcebawqr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fzhhl.top/Article/details/gt2zpggsxls.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mlcmdbdm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenjidiqi.icu/Article/details/gt2vriksdzc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2apupswtg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.fzhhl.top/Article/details/gt2bptdplae.html

[K04] 读取 JSON 文件
来源：http://dali.bjfxy.top/Article/details/gt2kuwfpzdz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigufen.top/Article/details/gt2guzzbmlu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.dashuyun.cn/Article/details/gt2yuyillzw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gt2jrcmoehx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gt2owaiepof.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gt2wegrlnhh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gt2giwpcqtt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tianlin.xyz/Article/details/gt2mooiehjd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dashuyun.cn/Article/details/gt2vkfcmvbl.html

[K05] 深拷贝对象
来源：http://dali.ehwqpu.com/Article/details/gt2abtqoloa.html

Py:   copy.deepcopy(obj)
来源：http://dali.havefunace.top/Article/details/gt2fizqgkiq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jiagoushi.top/Article/details/gt2bjqaxmge.html

JS:   structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2cujzrlsd.html

TS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gt2ucjjneus.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hysaishi.cn/Article/details/gt2dpqlbwum.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hfpthk.cn/Article/details/gt2ohsynybp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.andypj.xyz/Article/details/gt2ibtmprsf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cucudq.cn/Article/details/gt2iurrwwtc.html

[K06] 解析 URL 查询串
来源：http://dali.yonumen.top/Article/details/gt2sycqcnlp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gt2iaqllhvi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2durphlow.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aibaodan.cn/Article/details/gt2uphnvfyf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gt2zvnxoivi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jiagoushi.top/Article/details/gt2orcsldot.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gt2iztdcpdm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gt2nwxrvlxt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gt2nmbezzep.html

[K07] 进制转换
来源：http://dali.xuetiantiany.cn/Article/details/gt2jythxbsn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2ntkbxeyx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pmzoxlbg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2rknttggx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gt2tyectzvd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gt2tptguxpd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cdnleiting.top/Article/details/gt2gwxxdtkz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yuxming.cn/Article/details/gt2tdavnggf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2pouyzslu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sufxvd.cn/Article/details/gt2zjjcyqps.html

Py:   pickle.dumps(obj)
来源：http://dali.sxryk.cn/Article/details/gt2tzkmrjtt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.dashuyun.cn/Article/details/gt2tqmimxrz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.316326.xyz/Article/details/gt2xfwawwnp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shangyingyoupin.top/Article/details/gt2nsupxxln.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.guowangkeji.top/Article/details/gt2jucmgdjk.html

Go:   encoding/gob
来源：http://dali.zhoulong.xyz/Article/details/gt2lzokjhrz.html

Ruby: Marshal.dump(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2maaoasdr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.havefunace.top/Article/details/gt2kkrewxka.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2bruqerkq.html

L. 网络请求
来源：http://dali.pengpengdd.cyou/Article/details/gt2lusxpdlh.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2amsczgcb.html

[L01] 发送 GET 请求
来源：http://dali.tanke756.top/Article/details/gt2emjmexsf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yanxiufei.cn/Article/details/gt2cdffgrjc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.guannengcc.top/Article/details/gt2ezghzrgq.html

JS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gt2yqwbdqko.html

TS:   await fetch(url)
来源：http://dali.zycfv.cn/Article/details/gt2bovbosqf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xziqi.cn/Article/details/gt2nyxohzsg.html

Go:   resp, err := http.Get(url)
来源：http://dali.xylfe.cn/Article/details/gt2cdcirqjq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.pengpengdd.cyou/Article/details/gt2avawdbth.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gzhubu.top/Article/details/gt2mfuwulrt.html

[L02] 发送 POST JSON
来源：http://dali.aizwys.cn/Article/details/gt2huozhucu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zycfv.cn/Article/details/gt2gojeftrd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.bjfxy.top/Article/details/gt2quynwlsm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guannengcc.top/Article/details/gt2bapikaki.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnqzz.top/Article/details/gt2fpbjwmmo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yangfankeji.com/Article/details/gt2ddpinepn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jucctjrd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhoulong.xyz/Article/details/gt2ffsuvchx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hnqzz.top/Article/details/gt2htqatqgt.html

[L03] 设置自定义请求头
来源：http://dali.tanke756.top/Article/details/gt2hfminnwo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gotoacloud.top/Article/details/gt2tqacywcs.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tian-w.cn/Article/details/gt2hlxinqgt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hfpthk.cn/Article/details/gt2hedmideo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gt2topdzkec.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tianlin.xyz/Article/details/gt2ixmyvlsv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pengpengdd.cyou/Article/details/gt2eprdlonn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258.top/Article/details/gt2iognotbm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sxryk.cn/Article/details/gt2towebqid.html

[L04] 设置超时
来源：http://dali.xylfe.cn/Article/details/gt2ecvxbcit.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2juxoobzv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hammf.cn/Article/details/gt2kalvokwy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sxryk.cn/Article/details/gt2nprirdux.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gt2swzqqaul.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daria6918.cn/Article/details/gt2wpthpxiv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jyoumei.cn/Article/details/gt2eamnxaaq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pvzcpqjx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xziqi.cn/Article/details/gt2pkcoughx.html

[L05] 上传文件（multipart）
来源：http://dali.zhiwuduotai.top/Article/details/gt2fkaoyrin.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhengqikj.top/Article/details/gt2akmdgatc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xuanzx.com/Article/details/gt2ezlsdzvr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sxryk.cn/Article/details/gt2fbwrknkq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gt2bhphlczm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.havefunace.top/Article/details/gt2apjhwjiq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zdqjudy.top/Article/details/gt2eptkmwih.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.iojbl.cn/Article/details/gt2ewayrekb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2lkofvxks.html

[L06] 解析响应为 JSON
来源：http://dali.c1oappe.top/Article/details/gt2nvtkmobn.html

Py:   resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gt2eurlczui.html

PHP:  json_decode($body, true);
来源：http://dali.wangdashe.top/Article/details/gt2lgyifbdf.html

JS:   await resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ulnrztpr.html

TS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gt2gneirlvk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zdqjudy.top/Article/details/gt2rymlckxx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.smart0.xyz/Article/details/gt2mvteleah.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qqihueoh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxuanxn.top/Article/details/gt2tbcttgev.html

[L07] 处理 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gt2zejfqlin.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hfpthk.cn/Article/details/gt2yayhzcxm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ffehygmz.html

JS:   resp.ok;  resp.status
来源：http://dali.zhixingplan.top/Article/details/gt2bfempjea.html

TS:   resp.ok;  resp.status
来源：http://dali.yuanzhike.top/Article/details/gt2soypwqfk.html

Java: resp.statusCode()
来源：http://dali.jinqigfzy.top/Article/details/gt2kofiqwbe.html

Go:   resp.StatusCode
来源：http://dali.yj20258.top/Article/details/gt2llqesvan.html

Ruby: resp.code.to_i
来源：http://dali.bjfxy.top/Article/details/gt2udjemjea.html

C#:   (int)resp.StatusCode
来源：http://dali.ybcxt.top/Article/details/gt2yemvbpcg.html

[L08] 并发请求多个地址
来源：http://dali.sysykeji.top/Article/details/gt2zclbijyv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hnxiangtu.top/Article/details/gt2ifipjqgq.html

PHP:  curl_multi_init() 系列
来源：http://dali.birdmap.top/Article/details/gt2jhwiqkmk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cqqwz.cn/Article/details/gt2elawdfsn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yueranfly.top/Article/details/gt2jutogqxl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj20258.top/Article/details/gt2vmjkqxbb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yueranfly.top/Article/details/gt2fhfharfz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ppjwa.cn/Article/details/gt2asstbidk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yongpay.top/Article/details/gt2deezmlmt.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jcfawhnp.html

M. 命令行 / 进程 / 环境
来源：http://dali.c1oappe.top/Article/details/gt2vncwlsgx.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oitczfyd.html

[M01] 读取命令行参数
来源：http://dali.shzxlz.cn/Article/details/gt2qyzyltvf.html

Py:   sys.argv[1:]
来源：http://dali.quarkkingdee.top/Article/details/gt2dplbzrgn.html

PHP:  $argv;  $argc;
来源：http://dali.tianlin.xyz/Article/details/gt2gapmjflw.html

JS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gt2kihhdtzj.html

TS:   process.argv.slice(2)
来源：http://dali.birdmap.top/Article/details/gt2ilryrbed.html

Java: args 数组（main 方法参数）
来源：http://dali.cheryme.top/Article/details/gt2bobwovsu.html

Go:   os.Args[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gt2jvtpxvxo.html

Ruby: ARGV
来源：http://dali.hysaishi.cn/Article/details/gt2lstssofj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gt2mhvutxou.html

[M02] 读取环境变量
来源：http://dali.guowangkeji.top/Article/details/gt2mmbgciqk.html

Py:   os.environ.get("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gt2ocyzjxck.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zdqjudy.top/Article/details/gt2hqkqffhu.html

JS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gt2wxwseepr.html

TS:   process.env.HOME
来源：http://dali.zhongyouzk.top/Article/details/gt2gpetgwcv.html

Java: System.getenv("HOME")
来源：http://dali.hnqzz.top/Article/details/gt2tavqxhvd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gt2gfwcrwaf.html

Ruby: ENV["HOME"]
来源：http://dali.xuanzx.com/Article/details/gt2lktelzun.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fzhhl.top/Article/details/gt2vgyrtrmo.html

[M03] 执行外部命令
来源：http://dali.birdmap.top/Article/details/gt2tunvcnnz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.redwolf501.top/Article/details/gt2zjjezekg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ydzc1.top/Article/details/gt2akctaagd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2naitajwk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shuidangran.top/Article/details/gt2szwptztd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.bjfxy.top/Article/details/gt2sqngpdly.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.smart0.xyz/Article/details/gt2pvatpacb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yanxiufei.cn/Article/details/gt2hdrtyqyp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daria6918.cn/Article/details/gt2fjemylfl.html

[M04] 获取当前工作目录
来源：http://dali.hongshengwenyu.top/Article/details/gt2xplmmivj.html

Py:   os.getcwd()
来源：http://dali.xinyue.icu/Article/details/gt2mxmmvzps.html

PHP:  getcwd();
来源：http://dali.shuidangran.top/Article/details/gt2jtecftwk.html

JS:   process.cwd()
来源：http://dali.jiagoushi.top/Article/details/gt2lenfcbys.html

TS:   process.cwd()
来源：http://dali.zhixingplan.top/Article/details/gt2hnrlzzku.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cashguo.top/Article/details/gt2dilmqtbp.html

Go:   os.Getwd()
来源：http://dali.yueranfly.top/Article/details/gt2hcxmoker.html

Ruby: Dir.pwd
来源：http://dali.316326.xyz/Article/details/gt2ofapdzow.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.mhx1999.top/Article/details/gt2hbhopzpi.html

[M05] 设置退出码
来源：http://dali.sxryk.cn/Article/details/gt2idnbxvbi.html

Py:   sys.exit(1)
来源：http://dali.yj202588.top/Article/details/gt2plltsxxg.html

PHP:  exit(1);
来源：http://dali.yonumen.top/Article/details/gt2uijezzho.html

JS:   process.exit(1)
来源：http://dali.ydzc1.top/Article/details/gt2kpferwfh.html

TS:   process.exit(1)
来源：http://dali.yonumen.top/Article/details/gt2tioglomi.html

Java: System.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2ggvyyyli.html

Go:   os.Exit(1)
来源：http://dali.yj20258.top/Article/details/gt2fpsnntlg.html

Ruby: exit 1
来源：http://dali.yueranfly.top/Article/details/gt2aveqwzng.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nbkvabcd.html

[M06] 向标准错误输出
来源：http://dali.haohaochexian.top/Article/details/gt2kvltpygp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fengsongda.top/Article/details/gt2jnvmzgix.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.fzhhl.top/Article/details/gt2iyjyxanl.html

JS:   console.error("err")
来源：http://dali.9152youxi.cn/Article/details/gt2mijpsqhm.html

TS:   console.error("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2loeogsyr.html

Java: System.err.println("err")
来源：http://dali.haohaochexian.top/Article/details/gt2eqjkasma.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aentvvzn.html

Ruby: warn "err"
来源：http://dali.zhoulong.xyz/Article/details/gt2ukstdsdo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.9152youxi.cn/Article/details/gt2iaswoekj.html

[M07] 判断是否为主入口
来源：http://dali.zhengqikj.top/Article/details/gt2fjcqngyp.html

Py:   if __name__ == "__main__":
来源：http://dali.hammf.cn/Article/details/gt2buxmiqww.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gotoacloud.top/Article/details/gt2xvpfvckf.html

JS:   require.main === module
来源：http://dali.c1oappe.top/Article/details/gt2lmkogans.html

TS:   require.main === module
来源：http://dali.hfpthk.cn/Article/details/gt2yqstywkc.html

Java: public static void main(String[] args)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iltcvrpm.html

Go:   func main()
来源：http://dali.jiagoushi.top/Article/details/gt2lvubambu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.meibo888.top/Article/details/gt2avvhnkkt.html

C#:   static void Main(string[] args)
来源：http://dali.yangfankeji.com/Article/details/gt2bitkojes.html

[M08] 获取系统与运行时信息
来源：http://dali.c1oappe.top/Article/details/gt2eocmimql.html

Py:   platform.system();  platform.python_version()
来源：http://dali.bjfxy.top/Article/details/gt2dlzsfxvn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.aibaodan.cn/Article/details/gt2lkwmbcnp.html

JS:   process.platform;  process.version
来源：http://dali.xuetiantiany.cn/Article/details/gt2vmugqkyt.html

TS:   process.platform;  process.version
来源：http://dali.cqqwz.cn/Article/details/gt2jtznbork.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yonumen.top/Article/details/gt2knxkbhpa.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yanxiufei.cn/Article/details/gt2hsgkdzaq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cqqwz.cn/Article/details/gt2kgcadiwo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bjcxgwep.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2wrswexgg.html

N. 数据结构与算法
来源：http://dali.sxryk.cn/Article/details/gt2zomdaujv.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2lnqksecg.html

[N01] 二分查找（有序数组）
来源：http://dali.xuetiantiany.cn/Article/details/gt2oufyskco.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2zjhqmdtz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.iojbl.cn/Article/details/gt2dtvtglbn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.snrcjt.cn/Article/details/gt2bbahkyrj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gt2aljruwgj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gt2xtbbipdx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gt2tzlycklx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.kuanghao11.cn/Article/details/gt2lvjahhfu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj20258888.top/Article/details/gt2ihhytpkm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigufen.top/Article/details/gt2ogpovibt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yonumen.top/Article/details/gt2yqtmrdqg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.dianchejie.cn/Article/details/gt2wjnadrhk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ivvv.top/Article/details/gt2jzppvger.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hammf.cn/Article/details/gt2jycvutxl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ivvv.top/Article/details/gt2qogjihwi.html

Go:   slices.Sort(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2hgastkkn.html

Ruby: arr.sort
来源：http://dali.svipenyu.cn/Article/details/gt2tqepwejj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xziqi.cn/Article/details/gt2cuzsptua.html

[N03] 快速排序（分治示例）
来源：http://dali.havefunace.top/Article/details/gt2vbyvtyyi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj20258888.top/Article/details/gt2dhkgqkce.html

PHP:  // 递归实现，或用 usort
来源：http://dali.birdmap.top/Article/details/gt2gydhcagu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hgymoapm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpocgdm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zeobccng.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.fzhhl.top/Article/details/gt2dygpunuu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.aibaodan.cn/Article/details/gt2nilgebot.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lazwkbvj.html

[N04] 斐波那契数列
来源：http://dali.yj20258.top/Article/details/gt2xcvqhjuv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yongpay.top/Article/details/gt2vehmnhrf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rsdzcaqk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gt2rfbghxjn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gt2ppbsunqr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2uobkqsow.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.pycfn.com/Article/details/gt2vclpouhq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.guowangkeji.top/Article/details/gt2iagipeef.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gt2bjzdxcgz.html

[N05] 最大公约数
来源：http://dali.shuidangran.top/Article/details/gt2luohurli.html

Py:   math.gcd(a, b)
来源：http://dali.guowangkeji.top/Article/details/gt2xfyozkvv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.guowangkeji.top/Article/details/gt2nnufmeff.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuanzx.com/Article/details/gt2ofqkfemd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.0kj1m.cn/Article/details/gt2faxhbcsl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cheryme.top/Article/details/gt2mxafcdwx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zycfv.cn/Article/details/gt2hpcgoxmw.html

Ruby: a.gcd(b)
来源：http://dali.xziqi.cn/Article/details/gt2oydshxjf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pacazydx.html

[N06] 判断回文字符串
来源：http://dali.cucudq.cn/Article/details/gt2iqqrcjlu.html

Py:   s == s[::-1]
来源：http://dali.yuxming.cn/Article/details/gt2deiabnvm.html

PHP:  $s === strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2gdgsphrx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gt2newsxdss.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tqvflmov.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gotoacloud.top/Article/details/gt2rzddkdzw.html

Go:   // 双指针从两端比较
来源：http://dali.cheryme.top/Article/details/gt2hokmkvmv.html

Ruby: s == s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gt2uhagbevi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jqgufenzy.top/Article/details/gt2naymjeeq.html

[N07] 两数之和（返回下标）
来源：http://dali.sweek.top/Article/details/gt2lapaurtn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jcxytyed.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.pengpengdd.cyou/Article/details/gt2hjduvyrf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.wangdashe.top/Article/details/gt2hcxivyna.html

TS:   // 手写 Map<string, number>
来源：http://dali.hammf.cn/Article/details/gt2ngpiqabh.html

Java: // 手写 HashMap
来源：http://dali.wangshuangyany.cn/Article/details/gt2fypixrmi.html

Go:   // 手写 map[int]int
来源：http://dali.nanxinkj.top/Article/details/gt2owpsgqrt.html

Ruby: // 手写 Hash
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cusohiea.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cqqwz.cn/Article/details/gt2feitufvv.html

[N08] 生成全排列
来源：http://dali.jianghu66.top/Article/details/gt2cjwdmonv.html

Py:   itertools.permutations(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jrnmtkgi.html

PHP:  // 手写递归交换
来源：http://dali.ehwqpu.com/Article/details/gt2xslkpmad.html

JS:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gt2ecxlaijj.html

TS:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gt2toprufcu.html

Java: // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gt2cfedkzmz.html

Go:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hrrwtkyr.html

Ruby: arr.permutation.to_a
来源：http://dali.shanyushiyangtech.top/Article/details/gt2veibxqfu.html

C#:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gt2figlsnpv.html

[N09] 栈与队列
来源：http://dali.c1oappe.top/Article/details/gt2ryuqtybr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.haohaochexian.top/Article/details/gt2wnwmpfiy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.c1oappe.top/Article/details/gt2qynowipm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aogmjgta.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhixingplan.top/Article/details/gt2alouposn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hysaishi.cn/Article/details/gt2qnekmpuq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhixingplan.top/Article/details/gt2cvgzbrth.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gt2hwhjetvz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cashguo.top/Article/details/gt2abdpbgfc.html

[N10] 链表节点定义
来源：http://dali.yongpay.top/Article/details/gt2xalbrgep.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cashguo.top/Article/details/gt2deafjmrq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hfpthk.cn/Article/details/gt2ylxmdzsp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yonumen.top/Article/details/gt2hswrnrfq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yuxming.cn/Article/details/gt2felfzbwm.html

Java: class Node { int v; Node next; }
来源：http://dali.dianchejie.cn/Article/details/gt2yjsbrgdt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.andypj.xyz/Article/details/gt2kbvpkewn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tianlin.xyz/Article/details/gt2gjlgzpnv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.nanxinkj.top/Article/details/gt2msdgqeca.html

[N11] 二叉树中序遍历
来源：http://dali.kuanghao11.cn/Article/details/gt2bweuqmej.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.9152youxi.cn/Article/details/gt2yxqmpiou.html


<!-- 参考信息 -->