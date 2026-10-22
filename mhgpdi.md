代发 wailian999

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2gaidxedy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bclrhcuo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gt2jtykjrrx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.iojbl.cn/Article/details/gt2hzvzajbw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gt2ewtbcems.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenlongwang.top/Article/details/gt2bmlqihqw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2aambraxq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.meibo888.top/Article/details/gt2advgbcqx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xinyue.icu/Article/details/gt2nrtqjram.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenjidiqi.icu/Article/details/gt2xkjallup.html

[K04] 读取 JSON 文件
来源：http://dali.cheryme.top/Article/details/gt2lqutpdct.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yuanzhike.top/Article/details/gt2ausionni.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ivvv.top/Article/details/gt2irpnrcpx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gt2bryaldqc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.smart0.xyz/Article/details/gt2jvmqwidp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gt2mfeorkfk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xylfe.cn/Article/details/gt2zrilvsmz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.guowangkeji.top/Article/details/gt2tdjfkapv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.wangdashe.top/Article/details/gt2qiueilpm.html

[K05] 深拷贝对象
来源：http://dali.c1oappe.top/Article/details/gt2vmwuvgjj.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2uxtfjnlf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xziqi.cn/Article/details/gt2vlnoimaf.html

JS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2uddnovee.html

TS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2dfeoboya.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cqqwz.cn/Article/details/gt2lajsylpo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpgbzbf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenlongwang.top/Article/details/gt2yopfkvay.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.kuanghao11.cn/Article/details/gt2rczflefg.html

[K06] 解析 URL 查询串
来源：http://dali.gaohongyu789.top/Article/details/gt2hgqrints.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.smart0.xyz/Article/details/gt2yhtyyspf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.snrcjt.cn/Article/details/gt2rylpwgbi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.316326.xyz/Article/details/gt2nmndeyhy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuxming.cn/Article/details/gt2jgzgqcou.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgfzy.top/Article/details/gt2ptslqfyx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gt2jxzeuosz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gt2nvdpgpkk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gt2jeueivvp.html

[K07] 进制转换
来源：http://dali.hywenlv.cn/Article/details/gt2jtghqkdx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gt2mcjngtqz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hfpthk.cn/Article/details/gt2nenybifa.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wbkvqapc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gt2fuvuyxjz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gt2vjhpereh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ffefxglo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kygjxdzv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.meibo888.top/Article/details/gt2uuoznkwn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xziqi.cn/Article/details/gt2rqwkabqx.html

Py:   pickle.dumps(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2obmsmzaq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gotoacloud.top/Article/details/gt2cjywsojr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gzhubu.top/Article/details/gt2hysdzqgg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gzhubu.top/Article/details/gt2kisdujek.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.dashuyun.cn/Article/details/gt2fajdwbya.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsqtawm.html

Ruby: Marshal.dump(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2jtepdeoh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hongshengwenyu.top/Article/details/gt2hyyktlat.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2zaqjiydu.html

L. 网络请求
来源：http://dali.dashuyun.cn/Article/details/gt2gckxajht.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2rjnmrfcm.html

[L01] 发送 GET 请求
来源：http://dali.yueranfly.top/Article/details/gt2jkmtlakx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ivvv.top/Article/details/gt2ziwssloa.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxuanxn.top/Article/details/gt2uksdrjsl.html

JS:   await fetch(url)
来源：http://dali.meibo888.top/Article/details/gt2lhlpozmk.html

TS:   await fetch(url)
来源：http://dali.yanxiufei.cn/Article/details/gt2tlbgmtqv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.fengsongda.top/Article/details/gt2kvjwfhxq.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2butqidoo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yuxming.cn/Article/details/gt2wbewovlq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yangfankeji.com/Article/details/gt2cpabvtld.html

[L02] 发送 POST JSON
来源：http://dali.zycfv.cn/Article/details/gt2eccmasrn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oficxjib.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xziqi.cn/Article/details/gt2kykkqxtr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhiwuduotai.top/Article/details/gt2dmrmhwyd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.iojbl.cn/Article/details/gt2hnjldwju.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.smart0.xyz/Article/details/gt2nlzjxerd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jianghu66.top/Article/details/gt2lwsdumtn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ckapnymg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aibaodan.cn/Article/details/gt2dueaavrr.html

[L03] 设置自定义请求头
来源：http://dali.yongpay.top/Article/details/gt2bpzgfxvq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.aizwys.cn/Article/details/gt2tjqaimjt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yongpay.top/Article/details/gt2odmmthie.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xziqi.cn/Article/details/gt2vrwbqvhf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnqzz.top/Article/details/gt2dfgsigsp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.bjfxy.top/Article/details/gt2onxtuwjp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.nwbrower.top/Article/details/gt2whxvczje.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cheryme.top/Article/details/gt2wusacrsp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oopgomrv.html

[L04] 设置超时
来源：http://dali.xuetiantiany.cn/Article/details/gt2sasvkisw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.vqdsnc.cn/Article/details/gt2dovyispe.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jlsjyb.cn/Article/details/gt2fvvcjsyc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gt2gkoyjrgb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.bjfxy.top/Article/details/gt2mbugpamm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gaohongyu789.top/Article/details/gt2zxubyhjj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.feifeiyinyue.top/Article/details/gt2pxkmnjhd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cqqwz.cn/Article/details/gt2mwubjmgu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.andypj.xyz/Article/details/gt2tvqczgis.html

[L05] 上传文件（multipart）
来源：http://dali.dianchejie.cn/Article/details/gt2bzavlupg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.haohaochexian.top/Article/details/gt2sepwfqgm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhengqikj.top/Article/details/gt2oncxdurv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hywenlv.cn/Article/details/gt2bcegyswd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.dianchejie.cn/Article/details/gt2qiygrprm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258.top/Article/details/gt2tzcunsvs.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cdnleiting.top/Article/details/gt2mijpwpfu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.feifeiyinyue.top/Article/details/gt2vpbjrtts.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2ntjjwqqp.html

[L06] 解析响应为 JSON
来源：http://dali.xuanzx.com/Article/details/gt2cmrkadqz.html

Py:   resp.json()
来源：http://dali.hfpthk.cn/Article/details/gt2bckcfquk.html

PHP:  json_decode($body, true);
来源：http://dali.dashuyun.cn/Article/details/gt2tkxntinc.html

JS:   await resp.json()
来源：http://dali.gzhubu.top/Article/details/gt2afswhuia.html

TS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gt2nbmshjla.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xinyue.icu/Article/details/gt2dcmmkuae.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sysykeji.top/Article/details/gt2fkvrdyhk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ybcxt.top/Article/details/gt2wbozqrfz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhiwuduotai.top/Article/details/gt2zzqtyiru.html

[L07] 处理 HTTP 状态码
来源：http://dali.yueranfly.top/Article/details/gt2hutjneft.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ldsdxyvi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tanke756.top/Article/details/gt2kptqahll.html

JS:   resp.ok;  resp.status
来源：http://dali.shzxlz.cn/Article/details/gt2rjatsyiy.html

TS:   resp.ok;  resp.status
来源：http://dali.xziqi.cn/Article/details/gt2xgbqasdi.html

Java: resp.statusCode()
来源：http://dali.yonumen.top/Article/details/gt2apfeeivy.html

Go:   resp.StatusCode
来源：http://dali.c1oappe.top/Article/details/gt2welkasge.html

Ruby: resp.code.to_i
来源：http://dali.nanxuanxn.top/Article/details/gt2txsvekcg.html

C#:   (int)resp.StatusCode
来源：http://dali.0kj1m.cn/Article/details/gt2mjasitri.html

[L08] 并发请求多个地址
来源：http://dali.meibo888.top/Article/details/gt2pvpwrldu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.redwolf501.top/Article/details/gt2jkcgldzs.html

PHP:  curl_multi_init() 系列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2megjspty.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gt2kidzzemv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gt2cvibhlgp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.smart0.xyz/Article/details/gt2rlvcdiws.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yueranfly.top/Article/details/gt2grsmqrfy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gogol.net.cn/Article/details/gt2rpuhcsuu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cheryme.top/Article/details/gt2qfdxhjrs.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2ialdzddr.html

M. 命令行 / 进程 / 环境
来源：http://dali.hongshengwenyu.top/Article/details/gt2fphzlspr.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2yznqreaa.html

[M01] 读取命令行参数
来源：http://dali.gzhubu.top/Article/details/gt2hqucczam.html

Py:   sys.argv[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gt2ziaegqel.html

PHP:  $argv;  $argc;
来源：http://dali.wangshuangyany.cn/Article/details/gt2hrmmxrpa.html

JS:   process.argv.slice(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2raoxgfjq.html

TS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gt2esphipbu.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gt2knpeizry.html

Go:   os.Args[1:]
来源：http://dali.shuidangran.top/Article/details/gt2rbqiwuxi.html

Ruby: ARGV
来源：http://dali.gogol.net.cn/Article/details/gt2ccmtfshg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xinyue.icu/Article/details/gt2chpmarlv.html

[M02] 读取环境变量
来源：http://dali.sufxvd.cn/Article/details/gt2bbibmjfd.html

Py:   os.environ.get("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gt2hscacggf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gaohongyu789.top/Article/details/gt2gowpgnnb.html

JS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gt2avhzhmcw.html

TS:   process.env.HOME
来源：http://dali.tian-w.cn/Article/details/gt2qqtkfnwj.html

Java: System.getenv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gt2uoxsblhp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.fzhhl.top/Article/details/gt2tddmfits.html

Ruby: ENV["HOME"]
来源：http://dali.cucudq.cn/Article/details/gt2maomzevz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gzhubu.top/Article/details/gt2mdouvvyg.html

[M03] 执行外部命令
来源：http://dali.kuanghao11.cn/Article/details/gt2towqqbyp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yvedp.cn/Article/details/gt2lsfcctcq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.birdmap.top/Article/details/gt2zoznfkll.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.daria6918.cn/Article/details/gt2cbavlttx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yvedp.cn/Article/details/gt2jehnfhpm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zdqjudy.top/Article/details/gt2nqiqzrum.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shzxlz.cn/Article/details/gt2mivgadix.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shangyingyoupin.top/Article/details/gt2htumyxbh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hammf.cn/Article/details/gt2rjdxutnk.html

[M04] 获取当前工作目录
来源：http://dali.cheryme.top/Article/details/gt2zkyxkizi.html

Py:   os.getcwd()
来源：http://dali.kuanghao11.cn/Article/details/gt2bbkqmmod.html

PHP:  getcwd();
来源：http://dali.ehwqpu.com/Article/details/gt2ygertdnx.html

JS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iyrushej.html

TS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gt2exuudpxq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shangyingyoupin.top/Article/details/gt2tepyrveg.html

Go:   os.Getwd()
来源：http://dali.jlsjyb.cn/Article/details/gt2zvnxkftv.html

Ruby: Dir.pwd
来源：http://dali.c1oappe.top/Article/details/gt2zotckoqe.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sufxvd.cn/Article/details/gt2qwlwjsyd.html

[M05] 设置退出码
来源：http://dali.jlsjyb.cn/Article/details/gt2nibdipux.html

Py:   sys.exit(1)
来源：http://dali.jianghu66.top/Article/details/gt2zjsqieer.html

PHP:  exit(1);
来源：http://dali.aizwys.cn/Article/details/gt2rgcpszyu.html

JS:   process.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gt2khjntjyo.html

TS:   process.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wfgsdyoa.html

Java: System.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zhwngkny.html

Go:   os.Exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hanqnrrm.html

Ruby: exit 1
来源：http://dali.0kj1m.cn/Article/details/gt2kvinxbns.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cqqwz.cn/Article/details/gt2iqhsqoyu.html

[M06] 向标准错误输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vsxabcxn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.9152youxi.cn/Article/details/gt2sqzpagvn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sweek.top/Article/details/gt2urgwbrua.html

JS:   console.error("err")
来源：http://dali.xylfe.cn/Article/details/gt2tpuibale.html

TS:   console.error("err")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xzwynrli.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bqtvrlnh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gotoacloud.top/Article/details/gt2cgcsnlis.html

Ruby: warn "err"
来源：http://dali.hnqzz.top/Article/details/gt2iyvyocuu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.9152youxi.cn/Article/details/gt2hfipisno.html

[M07] 判断是否为主入口
来源：http://dali.bjfxy.top/Article/details/gt2zvfbfyic.html

Py:   if __name__ == "__main__":
来源：http://dali.yuxming.cn/Article/details/gt2yoqssvnw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj202588.top/Article/details/gt2vionxojb.html

JS:   require.main === module
来源：http://dali.cheryme.top/Article/details/gt2zjefjaje.html

TS:   require.main === module
来源：http://dali.tian-w.cn/Article/details/gt2wwiuzkkf.html

Java: public static void main(String[] args)
来源：http://dali.yangfankeji.com/Article/details/gt2dtthmvpn.html

Go:   func main()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wsftgkcr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tian-w.cn/Article/details/gt2zvlgruyw.html

C#:   static void Main(string[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qdnnfjqi.html

[M08] 获取系统与运行时信息
来源：http://dali.xuetiantiany.cn/Article/details/gt2ofsbbxxo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hammf.cn/Article/details/gt2uvpfbhel.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zatzvjzm.html

JS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gt2ofddgqal.html

TS:   process.platform;  process.version
来源：http://dali.yongpay.top/Article/details/gt2qpbbtpqt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.bjfxy.top/Article/details/gt2amqixnno.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hysaishi.cn/Article/details/gt2vsrweefo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ehwqpu.com/Article/details/gt2nekhfagh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.wangshuangyany.cn/Article/details/gt2azvlindu.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2rkgtknww.html

N. 数据结构与算法
来源：http://dali.ybcxt.top/Article/details/gt2ugpkzdck.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2vclclbzz.html

[N01] 二分查找（有序数组）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aiogrhfj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gt2obliwdbe.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hnqzz.top/Article/details/gt2brzvhthj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gt2eubucnek.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nwbrower.top/Article/details/gt2dhsoccfy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tanke756.top/Article/details/gt2hcuslsea.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2inhgocua.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yanxiufei.cn/Article/details/gt2zeyrauif.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.fengsongda.top/Article/details/gt2vzchfuff.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.quarkkingdee.top/Article/details/gt2nafusonv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhengqikj.top/Article/details/gt2rmujpryp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nanxuanxn.top/Article/details/gt2gxzgazee.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gt2cchlwfim.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gt2nptxvtit.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sysykeji.top/Article/details/gt2bmhuyleg.html

Go:   slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gt2hxpsjdtg.html

Ruby: arr.sort
来源：http://dali.yuanzhike.top/Article/details/gt2znsgcplu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.c1oappe.top/Article/details/gt2tddzgrlp.html

[N03] 快速排序（分治示例）
来源：http://dali.bjfxy.top/Article/details/gt2bacrpvoo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yonumen.top/Article/details/gt2qwstuhcp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.pengpengdd.cyou/Article/details/gt2idvhlzdn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.birdmap.top/Article/details/gt2vyabnbrm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnxiangtu.top/Article/details/gt2mesymsfu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.guowangkeji.top/Article/details/gt2varfzsax.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2duqupeqs.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gogol.net.cn/Article/details/gt2cvpuiuzu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2deuefgoh.html

[N04] 斐波那契数列
来源：http://dali.tian-w.cn/Article/details/gt2wvqhfcxq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shzxlz.cn/Article/details/gt2myjhoetz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj20258.top/Article/details/gt2hsqifwbe.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gt2xvvjrzbb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gt2xgymwfxs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2jazzrquv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sufxvd.cn/Article/details/gt2fsydfrgm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cnnogrvu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gt2khguoere.html

[N05] 最大公约数
来源：http://dali.ydzc1.top/Article/details/gt2xyhjrkqm.html

Py:   math.gcd(a, b)
来源：http://dali.smart0.xyz/Article/details/gt2sjwwlhtq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.bjfxy.top/Article/details/gt2pgfhneck.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ybcxt.top/Article/details/gt2xnrdwhsm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gt2mvgrzynx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tian-w.cn/Article/details/gt2mwtfnmcb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sufxvd.cn/Article/details/gt2uuyzrzdc.html

Ruby: a.gcd(b)
来源：http://dali.zhoulong.xyz/Article/details/gt2bkxfuadh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.haohaochexian.top/Article/details/gt2crzatcmr.html

[N06] 判断回文字符串
来源：http://dali.yuxming.cn/Article/details/gt2aedjwvaa.html

Py:   s == s[::-1]
来源：http://dali.yonumen.top/Article/details/gt2uldvockv.html

PHP:  $s === strrev($s);
来源：http://dali.gzhubu.top/Article/details/gt2ryahlspp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gt2xzmpqeub.html

TS:   s === [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gt2lpklfkmv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cdnleiting.top/Article/details/gt2pcbygxoi.html

Go:   // 双指针从两端比较
来源：http://dali.jqgufenzy.top/Article/details/gt2oknpycrb.html

Ruby: s == s.reverse
来源：http://dali.zhixingplan.top/Article/details/gt2pfhvcasy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gt2knfsowyb.html

[N07] 两数之和（返回下标）
来源：http://dali.316326.xyz/Article/details/gt2lrlcnikx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jodarcpm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj202588.top/Article/details/gt2ybsjrkuw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hysaishi.cn/Article/details/gt2knqkykqj.html

TS:   // 手写 Map<string, number>
来源：http://dali.wangshuangyany.cn/Article/details/gt2tjkkwctc.html

Java: // 手写 HashMap
来源：http://dali.yvedp.cn/Article/details/gt2xqlmhwjq.html

Go:   // 手写 map[int]int
来源：http://dali.ehwqpu.com/Article/details/gt2bgonudtt.html

Ruby: // 手写 Hash
来源：http://dali.cqqwz.cn/Article/details/gt2pwrqjavb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ehwqpu.com/Article/details/gt2ppweyrse.html

[N08] 生成全排列
来源：http://dali.nanxinkj.top/Article/details/gt2hxtubffi.html

Py:   itertools.permutations(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2jrzamaqh.html

PHP:  // 手写递归交换
来源：http://dali.ydzc1.top/Article/details/gt2dihypjtp.html

JS:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gt2ucnzhjgt.html

TS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gt2wuvyyvqp.html

Java: // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gt2ifujvwkk.html

Go:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gt2vxwonvmy.html

Ruby: arr.permutation.to_a
来源：http://dali.jiagoushi.top/Article/details/gt2svcosiep.html

C#:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gt2hcryubpg.html

[N09] 栈与队列
来源：http://dali.gogol.net.cn/Article/details/gt2nnyrzmnv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.haohaochexian.top/Article/details/gt2wajbmgiw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gt2gegkcwne.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sysykeji.top/Article/details/gt2totkcdqe.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zdqjudy.top/Article/details/gt2zdplptxg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dvplommv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj20258.top/Article/details/gt2tguiqsnm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xuanzx.com/Article/details/gt2hszpkihm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hammf.cn/Article/details/gt2sfooinso.html

[N10] 链表节点定义
来源：http://dali.jlsjyb.cn/Article/details/gt2jazpaxfs.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.bjfxy.top/Article/details/gt2vhbutsri.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.meibo888.top/Article/details/gt2yhzpplko.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hywenlv.cn/Article/details/gt2jfxlgadv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xuanzx.com/Article/details/gt2ojespqge.html

Java: class Node { int v; Node next; }
来源：http://dali.316326.xyz/Article/details/gt2bjenbbje.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hysaishi.cn/Article/details/gt2idyleypm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cdnleiting.top/Article/details/gt2debkyqhj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj202588.top/Article/details/gt2ssfxvzgs.html

[N11] 二叉树中序遍历
来源：http://dali.nwbrower.top/Article/details/gt2nojmruer.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yuxming.cn/Article/details/gt2umwibllv.html


<!-- 参考信息 -->