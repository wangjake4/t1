代发 wailian999

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.havefunace.top/Article/details/gt2miadxyyg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenzaomai.com/Article/details/gt2hmmnpilf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gt2wgapsdvp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gt2zsbsqflc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2suusesvx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zyfafksi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2qjiduwlw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nanxinkj.top/Article/details/gt2sjamoriy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2axekrbks.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jyoumei.cn/Article/details/gt2cwdgvurw.html

[K04] 读取 JSON 文件
来源：http://dali.quarkkingdee.top/Article/details/gt2quidufpb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sufxvd.cn/Article/details/gt2mkxbzlax.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ryilmgde.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.0kj1m.cn/Article/details/gt2rwmynnww.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zdqjudy.top/Article/details/gt2dlcalmss.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jianghu66.top/Article/details/gt2tozwfhyz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenzaomai.com/Article/details/gt2tpbisytn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cashguo.top/Article/details/gt2xyiezfmu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gt2galqxpip.html

[K05] 深拷贝对象
来源：http://dali.hfpthk.cn/Article/details/gt2aymmvego.html

Py:   copy.deepcopy(obj)
来源：http://dali.smart0.xyz/Article/details/gt2fwdkttcf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.quarkkingdee.top/Article/details/gt2ldrpdyll.html

JS:   structuredClone(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kidmtiub.html

TS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wwpfvzmo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ydzc1.top/Article/details/gt2yauspwkp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.316326.xyz/Article/details/gt2qzkcpmrs.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nanxuanxn.top/Article/details/gt2maxfpqul.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.haohaochexian.top/Article/details/gt2lggtfjdp.html

[K06] 解析 URL 查询串
来源：http://dali.quarkkingdee.top/Article/details/gt2meuodipv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.0kj1m.cn/Article/details/gt2vibuvrok.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.mhx1999.top/Article/details/gt2oizpyvqz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhixingplan.top/Article/details/gt2nwpxpfpv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfhutvm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhoulong.xyz/Article/details/gt2yzlglqfb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gt2vwkcoyii.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gt2wcyrfcqs.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gt2vokgmfjx.html

[K07] 进制转换
来源：http://dali.xylfe.cn/Article/details/gt2rteqrcvu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gt2wrrcaitg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.0kj1m.cn/Article/details/gt2ngergqtn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2jxmnvnfv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gt2ltvmmfxk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gt2xrqpdxvn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jlsjyb.cn/Article/details/gt2korvikhh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daria6918.cn/Article/details/gt2eiwqmxfd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gt2axbiyvho.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sxryk.cn/Article/details/gt2xclqxmfb.html

Py:   pickle.dumps(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2hzpjqgai.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ebgnvrlt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nwbrower.top/Article/details/gt2sndyrexe.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gt2ocpldmpm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hfpthk.cn/Article/details/gt2qxjchfyn.html

Go:   encoding/gob
来源：http://dali.vqdsnc.cn/Article/details/gt2ohycudxt.html

Ruby: Marshal.dump(obj)
来源：http://dali.xylfe.cn/Article/details/gt2skebyyqd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tanke756.top/Article/details/gt2kenimufe.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2byjdstcq.html

L. 网络请求
来源：http://dali.redwolf501.top/Article/details/gt2puemwfre.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2zlssqanx.html

[L01] 发送 GET 请求
来源：http://dali.chenzaomai.com/Article/details/gt2apmpusmi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hnxiangtu.top/Article/details/gt2qzawmbxl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhixingplan.top/Article/details/gt2sutsmhvc.html

JS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gt2mzzdclpa.html

TS:   await fetch(url)
来源：http://dali.tanke756.top/Article/details/gt2fbnsvmpj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hnxiangtu.top/Article/details/gt2jijyxarj.html

Go:   resp, err := http.Get(url)
来源：http://dali.hysaishi.cn/Article/details/gt2qboowdrt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.feifeiyinyue.top/Article/details/gt2olxvikkd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hnxiangtu.top/Article/details/gt2bvgwhwzs.html

[L02] 发送 POST JSON
来源：http://dali.yanxiufei.cn/Article/details/gt2zvojzuuk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yuanzhike.top/Article/details/gt2cmhnfksw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xuanzx.com/Article/details/gt2pkdsfatm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.havefunace.top/Article/details/gt2rqbcrmdd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuanzhike.top/Article/details/gt2dbxkmeqd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nanxuanxn.top/Article/details/gt2trixqsaq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.snrcjt.cn/Article/details/gt2xvjtzduz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kscdklii.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgfzy.top/Article/details/gt2gxdhvzyq.html

[L03] 设置自定义请求头
来源：http://dali.zycfv.cn/Article/details/gt2cjtttssu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yvedp.cn/Article/details/gt2fcqwtxsx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yanxiufei.cn/Article/details/gt2xzaunzai.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj202588.top/Article/details/gt2kithgquf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mbqhwock.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dashuyun.cn/Article/details/gt2uuupcpph.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.mhx1999.top/Article/details/gt2ymqaxngo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yuxming.cn/Article/details/gt2aenbyfxm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guannengcc.top/Article/details/gt2kisjgwyo.html

[L04] 设置超时
来源：http://dali.guannengcc.top/Article/details/gt2dzpcavyk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cdnleiting.top/Article/details/gt2kcrxvejm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gzhubu.top/Article/details/gt2uozycmpy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tanke756.top/Article/details/gt2idioahmk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ybcxt.top/Article/details/gt2rqdaiezn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.birdmap.top/Article/details/gt2qvlbkjaa.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.havefunace.top/Article/details/gt2eskautdc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gaohongyu789.top/Article/details/gt2pamfaoiy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.vqdsnc.cn/Article/details/gt2uvrovytw.html

[L05] 上传文件（multipart）
来源：http://dali.yj20258888.top/Article/details/gt2kymctalr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.wangshuangyany.cn/Article/details/gt2loeklwpk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.haohaochexian.top/Article/details/gt2deihzdvp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuxming.cn/Article/details/gt2zradjtbk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.smart0.xyz/Article/details/gt2sdgkomsp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nwbrower.top/Article/details/gt2vejaevvg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.aibaodan.cn/Article/details/gt2hzaslgwt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gotoacloud.top/Article/details/gt2vadcipmz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2kgvvkamp.html

[L06] 解析响应为 JSON
来源：http://dali.havefunace.top/Article/details/gt2fbcckqsj.html

Py:   resp.json()
来源：http://dali.yonumen.top/Article/details/gt2ibusovay.html

PHP:  json_decode($body, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ghzwuysx.html

JS:   await resp.json()
来源：http://dali.cucudq.cn/Article/details/gt2nkejfmsm.html

TS:   await resp.json()
来源：http://dali.yonumen.top/Article/details/gt2dzleepfm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.aibaodan.cn/Article/details/gt2qymmpupd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pycfn.com/Article/details/gt2kojdpfkn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gaohongyu789.top/Article/details/gt2uddidslx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hhmqbgcl.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigufen.top/Article/details/gt2ehbvkmzq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tianlin.xyz/Article/details/gt2frebmeho.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cheryme.top/Article/details/gt2rryuqtnx.html

JS:   resp.ok;  resp.status
来源：http://dali.sysykeji.top/Article/details/gt2wcgydaul.html

TS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gt2xmzsdobu.html

Java: resp.statusCode()
来源：http://dali.jlsjyb.cn/Article/details/gt2dhctbfdj.html

Go:   resp.StatusCode
来源：http://dali.shangyingyoupin.top/Article/details/gt2mxwuhyqd.html

Ruby: resp.code.to_i
来源：http://dali.dianchejie.cn/Article/details/gt2vlbymtlm.html

C#:   (int)resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gt2csaalnla.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zndhptmu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2slbmmihk.html

PHP:  curl_multi_init() 系列
来源：http://dali.aizwys.cn/Article/details/gt2swnzsjfh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sweek.top/Article/details/gt2yaumgrsq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gt2vfbqlcls.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sufxvd.cn/Article/details/gt2sbdngtob.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ybcxt.top/Article/details/gt2mrjqyiqb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dashuyun.cn/Article/details/gt2diqgethl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cqqwz.cn/Article/details/gt2ynlroiop.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ebadxibi.html

M. 命令行 / 进程 / 环境
来源：http://dali.andypj.xyz/Article/details/gt2hzyshiod.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2mszxekun.html

[M01] 读取命令行参数
来源：http://dali.gogol.net.cn/Article/details/gt2aknohzuw.html

Py:   sys.argv[1:]
来源：http://dali.redwolf501.top/Article/details/gt2udcazcxw.html

PHP:  $argv;  $argc;
来源：http://dali.zhoulong.xyz/Article/details/gt2envwglzd.html

JS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gt2xprnetbg.html

TS:   process.argv.slice(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jctfhlan.html

Java: args 数组（main 方法参数）
来源：http://dali.zhongyouzk.top/Article/details/gt2kxtukfdg.html

Go:   os.Args[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ytpnviwu.html

Ruby: ARGV
来源：http://dali.pycfn.com/Article/details/gt2hyaqgbtm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gt2vxwoiocj.html

[M02] 读取环境变量
来源：http://dali.zhengqikj.top/Article/details/gt2ftoghsol.html

Py:   os.environ.get("HOME")
来源：http://dali.shzxlz.cn/Article/details/gt2sblmdjpu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.havefunace.top/Article/details/gt2kyjyqhmw.html

JS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gt2flfqtzaz.html

TS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gt2jyyssmnp.html

Java: System.getenv("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2htuvzpgj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2umfffssz.html

Ruby: ENV["HOME"]
来源：http://dali.yj20258.top/Article/details/gt2isdtkocj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daxiang520.top/Article/details/gt2jjxazbya.html

[M03] 执行外部命令
来源：http://dali.jinqigfzy.top/Article/details/gt2bfjohkuz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ghrnxsub.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yyefmuni.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.vqdsnc.cn/Article/details/gt2yzxyaqtw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2oqxjjfgh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cucudq.cn/Article/details/gt2kjhnemmc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xuetiantiany.cn/Article/details/gt2pjhhjzxa.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.mhx1999.top/Article/details/gt2zskoweeg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hysaishi.cn/Article/details/gt2fedmtomz.html

[M04] 获取当前工作目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gbbicxnj.html

Py:   os.getcwd()
来源：http://dali.jinqigfzy.top/Article/details/gt2rsyxfeby.html

PHP:  getcwd();
来源：http://dali.ydzc1.top/Article/details/gt2eixwnfxu.html

JS:   process.cwd()
来源：http://dali.andypj.xyz/Article/details/gt2mvpdqpjj.html

TS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gt2swlyjgvo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nanxuanxn.top/Article/details/gt2wuzzfvqg.html

Go:   os.Getwd()
来源：http://dali.jlsjyb.cn/Article/details/gt2tbqcrexj.html

Ruby: Dir.pwd
来源：http://dali.zhongyouzk.top/Article/details/gt2cjtvzatx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yonumen.top/Article/details/gt2jlcsrcvp.html

[M05] 设置退出码
来源：http://dali.zhixingplan.top/Article/details/gt2cjcswogd.html

Py:   sys.exit(1)
来源：http://dali.xziqi.cn/Article/details/gt2faqstwgs.html

PHP:  exit(1);
来源：http://dali.0kj1m.cn/Article/details/gt2hrgmifsa.html

JS:   process.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fkolepbg.html

TS:   process.exit(1)
来源：http://dali.iojbl.cn/Article/details/gt2cagageoq.html

Java: System.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gt2goyneqaz.html

Go:   os.Exit(1)
来源：http://dali.andypj.xyz/Article/details/gt2kafvkmng.html

Ruby: exit 1
来源：http://dali.iojbl.cn/Article/details/gt2vdicejzk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xziqi.cn/Article/details/gt2leuhqnhx.html

[M06] 向标准错误输出
来源：http://dali.yongpay.top/Article/details/gt2huezxwbw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuanzhike.top/Article/details/gt2orrjzcss.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gogol.net.cn/Article/details/gt2atkcjcxr.html

JS:   console.error("err")
来源：http://dali.snrcjt.cn/Article/details/gt2ngijmqig.html

TS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gt2lzndhucm.html

Java: System.err.println("err")
来源：http://dali.gaohongyu789.top/Article/details/gt2ilxqlbhe.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangshuangyany.cn/Article/details/gt2hcmtxizl.html

Ruby: warn "err"
来源：http://dali.vqdsnc.cn/Article/details/gt2lbrghync.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj20258888.top/Article/details/gt2lxfjfria.html

[M07] 判断是否为主入口
来源：http://dali.zdqjudy.top/Article/details/gt2zigigmql.html

Py:   if __name__ == "__main__":
来源：http://dali.shuidangran.top/Article/details/gt2znlbmrwj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yvedp.cn/Article/details/gt2bjjmlyew.html

JS:   require.main === module
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tecdgcuc.html

TS:   require.main === module
来源：http://dali.svipenyu.cn/Article/details/gt2bqxzcuku.html

Java: public static void main(String[] args)
来源：http://dali.zhixingplan.top/Article/details/gt2gmohhpgx.html

Go:   func main()
来源：http://dali.jiagoushi.top/Article/details/gt2oodecgyf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hysaishi.cn/Article/details/gt2tzgkbxyu.html

C#:   static void Main(string[] args)
来源：http://dali.hysaishi.cn/Article/details/gt2swalbsbs.html

[M08] 获取系统与运行时信息
来源：http://dali.daria6918.cn/Article/details/gt2bnnawesx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhengqikj.top/Article/details/gt2srcszwdy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.daria6918.cn/Article/details/gt2sitiwiuw.html

JS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gt2kcudxwpq.html

TS:   process.platform;  process.version
来源：http://dali.zycfv.cn/Article/details/gt2lgrlbljp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.iojbl.cn/Article/details/gt2ieytahar.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2omfhhkhf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.pycfn.com/Article/details/gt2vmgtlhgq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.vqdsnc.cn/Article/details/gt2uqozakfa.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2zulahbcq.html

N. 数据结构与算法
来源：http://dali.iojbl.cn/Article/details/gt2jkwfoegn.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nivuvhsx.html

[N01] 二分查找（有序数组）
来源：http://dali.nwbrower.top/Article/details/gt2fmojcywo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fzuzmxzx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nanxinkj.top/Article/details/gt2hxrhmnoe.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2smrsvqpa.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgfzy.top/Article/details/gt2vztavqxw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sysykeji.top/Article/details/gt2bmlppfsm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cheryme.top/Article/details/gt2yuvtackd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hfpthk.cn/Article/details/gt2pyztpliy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gt2erbbbvvg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gotoacloud.top/Article/details/gt2navrporn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gt2bboejsji.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jyoumei.cn/Article/details/gt2wsxrorxb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guannengcc.top/Article/details/gt2xchzwicf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gt2ncwiujwc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.kuanghao11.cn/Article/details/gt2lcmchgmf.html

Go:   slices.Sort(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2eqjzjvtk.html

Ruby: arr.sort
来源：http://dali.fengsongda.top/Article/details/gt2kwgtssnz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhengqikj.top/Article/details/gt2ijlhmkrg.html

[N03] 快速排序（分治示例）
来源：http://dali.yonumen.top/Article/details/gt2wumwdahp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cdnleiting.top/Article/details/gt2xwqupcrg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenjidiqi.icu/Article/details/gt2cxvfzsik.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgufenzy.top/Article/details/gt2tgddhuit.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cucudq.cn/Article/details/gt2nqsvupix.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj202588.top/Article/details/gt2rkcwcymt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258.top/Article/details/gt2ytwrwgyg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yvedp.cn/Article/details/gt2ksdfehps.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cheryme.top/Article/details/gt2xeezizao.html

[N04] 斐波那契数列
来源：http://dali.zhoulong.xyz/Article/details/gt2sfcfpbkd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jyoumei.cn/Article/details/gt2fbcdyjzr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bzcclebi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gt2iasqfsft.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uyxzbxmc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gt2babgwsew.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhixingplan.top/Article/details/gt2rtyxkdrz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj202588.top/Article/details/gt2cozibiev.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gt2pghduglt.html

[N05] 最大公约数
来源：http://dali.vqdsnc.cn/Article/details/gt2nmzjlytw.html

Py:   math.gcd(a, b)
来源：http://dali.mhx1999.top/Article/details/gt2esiyudon.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2nmubqsnh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuanzhike.top/Article/details/gt2josionbg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yueranfly.top/Article/details/gt2radhcvmy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.9152youxi.cn/Article/details/gt2lqiiihrj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pqreenfj.html

Ruby: a.gcd(b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wflhrqxu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gzhubu.top/Article/details/gt2kqsotmum.html

[N06] 判断回文字符串
来源：http://dali.redwolf501.top/Article/details/gt2rifdzjxs.html

Py:   s == s[::-1]
来源：http://dali.sweek.top/Article/details/gt2yqwbqtdx.html

PHP:  $s === strrev($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2asttbbag.html

JS:   s === [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gt2veglwomb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gt2ghbyhfgt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.pycfn.com/Article/details/gt2fnsozhad.html

Go:   // 双指针从两端比较
来源：http://dali.snrcjt.cn/Article/details/gt2rqdzmpey.html

Ruby: s == s.reverse
来源：http://dali.meibo888.top/Article/details/gt2lbsocyot.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tianlin.xyz/Article/details/gt2wpdbhtty.html

[N07] 两数之和（返回下标）
来源：http://dali.wangshuangyany.cn/Article/details/gt2yxblurhd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nwbrower.top/Article/details/gt2yxuqsxvp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lefnzucq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.wangdashe.top/Article/details/gt2tqoegqpb.html

TS:   // 手写 Map<string, number>
来源：http://dali.yuxming.cn/Article/details/gt2ndxcuvvc.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqvcfck.html

Go:   // 手写 map[int]int
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ondscieu.html

Ruby: // 手写 Hash
来源：http://dali.daria6918.cn/Article/details/gt2rnmhgvjh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hongshengwenyu.top/Article/details/gt2poyaknju.html

[N08] 生成全排列
来源：http://dali.chenzaomai.com/Article/details/gt2gtsqmmuc.html

Py:   itertools.permutations(arr)
来源：http://dali.redwolf501.top/Article/details/gt2ujwcdzqu.html

PHP:  // 手写递归交换
来源：http://dali.sweek.top/Article/details/gt2xdeczoig.html

JS:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2rvsfumxi.html

TS:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gt2floiggwm.html

Java: // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gt2xeaqozvu.html

Go:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gt2oqnzebmu.html

Ruby: arr.permutation.to_a
来源：http://dali.xziqi.cn/Article/details/gt2uxehcqlj.html

C#:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gt2elhnwqcw.html

[N09] 栈与队列
来源：http://dali.nwbrower.top/Article/details/gt2fmruiwzo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.9152youxi.cn/Article/details/gt2ltlcdjwk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sysykeji.top/Article/details/gt2edyxesem.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.svipenyu.cn/Article/details/gt2motkbdqg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenlongwang.top/Article/details/gt2pmgqvmvj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sgyrofmd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zycfv.cn/Article/details/gt2oswjlott.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gt2qsqefmgb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yahasvek.html

[N10] 链表节点定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cpfrmovv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.nanxuanxn.top/Article/details/gt2pfkqptgo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.daxiang520.top/Article/details/gt2pbztmxkp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gzhubu.top/Article/details/gt2yfhuoygn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.snrcjt.cn/Article/details/gt2vzrnbrzn.html

Java: class Node { int v; Node next; }
来源：http://dali.iojbl.cn/Article/details/gt2ppolkfcv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yueranfly.top/Article/details/gt2klqbuxan.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hfpthk.cn/Article/details/gt2rgxwdtqw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.9152youxi.cn/Article/details/gt2rmruodsh.html

[N11] 二叉树中序遍历
来源：http://dali.jianghu66.top/Article/details/gt2whtqskgw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cdnleiting.top/Article/details/gt2ldgcwazk.html


<!-- 参考信息 -->