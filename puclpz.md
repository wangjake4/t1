代发 wailian999

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gt2flicknts.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gt2fihbkfgc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.havefunace.top/Article/details/gt2xhzlgmjs.html

[K05] 深拷贝对象
来源：http://dali.zhengqikj.top/Article/details/gt2nosxtuwj.html

Py:   copy.deepcopy(obj)
来源：http://dali.meibo888.top/Article/details/gt2qyeepchd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinqigufen.top/Article/details/gt2iyjztnbq.html

JS:   structuredClone(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qnxjqcpy.html

TS:   structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2hnmdwidv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sufxvd.cn/Article/details/gt2wdlfvlci.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.snrcjt.cn/Article/details/gt2nrkcsvdz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.fengsongda.top/Article/details/gt2yjzcaonc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jqgufenzy.top/Article/details/gt2julleyoj.html

[K06] 解析 URL 查询串
来源：http://dali.nanxinkj.top/Article/details/gt2gxqeswqx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gt2svmuhbqj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gzhubu.top/Article/details/gt2apruwjcx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2guceismu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnqzz.top/Article/details/gt2ohlykfde.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2lckgkzjx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gt2fhhsahcy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hfpthk.cn/Article/details/gt2irsudtpx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gt2ropojqqs.html

[K07] 进制转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2dqutztsy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gt2auhkqpwj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhengqikj.top/Article/details/gt2tdpburia.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gt2wxuhehho.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gt2rjxscmjw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gt2hyzozdbx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.smart0.xyz/Article/details/gt2cddhxhon.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wdekliqb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.pycfn.com/Article/details/gt2vlrpwapq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jqgfzy.top/Article/details/gt2vjhzvpmu.html

Py:   pickle.dumps(obj)
来源：http://dali.tanke756.top/Article/details/gt2rsfcmqhz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.bjfxy.top/Article/details/gt2emociflp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gotoacloud.top/Article/details/gt2dsfzuemz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258888.top/Article/details/gt2pmikqayn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuetiantiany.cn/Article/details/gt2vmqkdcfa.html

Go:   encoding/gob
来源：http://dali.cqqwz.cn/Article/details/gt2yllfabpy.html

Ruby: Marshal.dump(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mkvfdjon.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xflxlwtu.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2czeknhvt.html

L. 网络请求
来源：http://dali.hnqzz.top/Article/details/gt2kxawiwcj.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2eodzhfeb.html

[L01] 发送 GET 请求
来源：http://dali.fengsongda.top/Article/details/gt2kmpbjkqc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sckjvzeo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.feifeiyinyue.top/Article/details/gt2aeridspj.html

JS:   await fetch(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mhxedkac.html

TS:   await fetch(url)
来源：http://dali.jyoumei.cn/Article/details/gt2vuwbyhgl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ybcxt.top/Article/details/gt2ifbsjjdl.html

Go:   resp, err := http.Get(url)
来源：http://dali.yueranfly.top/Article/details/gt2fvohapcx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.andypj.xyz/Article/details/gt2kbuqbnpz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2boqiixbx.html

[L02] 发送 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eyrcggjh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yvedp.cn/Article/details/gt2tombtlzn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yongpay.top/Article/details/gt2wodpnroc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gt2tnepagaf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.birdmap.top/Article/details/gt2hjybafoj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gzhubu.top/Article/details/gt2jqkpbwhb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuetiantiany.cn/Article/details/gt2ixkfmrht.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gotoacloud.top/Article/details/gt2evaasuxw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.haohaochexian.top/Article/details/gt2iddfxkap.html

[L03] 设置自定义请求头
来源：http://dali.fzhhl.top/Article/details/gt2uywggfvq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj20258888.top/Article/details/gt2hvvbhemt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gaohongyu789.top/Article/details/gt2hzssiiaw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yangfankeji.com/Article/details/gt2teetpxpy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gt2rbrwxssb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cashguo.top/Article/details/gt2lvndijau.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gt2bnzwsety.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2inmbeuyl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhoulong.xyz/Article/details/gt2ummphbjy.html

[L04] 设置超时
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wcdvqaal.html

Py:   requests.get(url, timeout=5)
来源：http://dali.meibo888.top/Article/details/gt2rebogwol.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fzhhl.top/Article/details/gt2qzgccbbv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gt2igbbhjmg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.birdmap.top/Article/details/gt2stoedcsg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.haohaochexian.top/Article/details/gt2pxtxnbtq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.0kj1m.cn/Article/details/gt2qjehpgli.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yangfankeji.com/Article/details/gt2svdzsagr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.wangshuangyany.cn/Article/details/gt2kgobnohp.html

[L05] 上传文件（multipart）
来源：http://dali.jinqigufen.top/Article/details/gt2hnnkoloh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj202588.top/Article/details/gt2jdcecsgf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jlsjyb.cn/Article/details/gt2dtkrhbfi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gt2vpzxbxkj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangshuangyany.cn/Article/details/gt2johpgbno.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.aizwys.cn/Article/details/gt2qbfldocd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigfzy.top/Article/details/gt2hgowpfdw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hongshengwenyu.top/Article/details/gt2beytthmy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2alcaatua.html

[L06] 解析响应为 JSON
来源：http://dali.tian-w.cn/Article/details/gt2zgksdsoo.html

Py:   resp.json()
来源：http://dali.yangfankeji.com/Article/details/gt2smdicxbb.html

PHP:  json_decode($body, true);
来源：http://dali.yangfankeji.com/Article/details/gt2ddaexjkl.html

JS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gt2qtwlsmyd.html

TS:   await resp.json()
来源：http://dali.jyoumei.cn/Article/details/gt2pefxcjxx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gt2yzkbhsny.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tianlin.xyz/Article/details/gt2rhbkwmou.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yanxiufei.cn/Article/details/gt2ddbdoqeg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jiagoushi.top/Article/details/gt2gddygbus.html

[L07] 处理 HTTP 状态码
来源：http://dali.yueranfly.top/Article/details/gt2noywthsp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.mhx1999.top/Article/details/gt2zxbavlml.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuxming.cn/Article/details/gt2yvtldgtl.html

JS:   resp.ok;  resp.status
来源：http://dali.c1oappe.top/Article/details/gt2katdzhpa.html

TS:   resp.ok;  resp.status
来源：http://dali.dianchejie.cn/Article/details/gt2olnotcug.html

Java: resp.statusCode()
来源：http://dali.fengsongda.top/Article/details/gt2jqqkdiaa.html

Go:   resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gt2uycakdxq.html

Ruby: resp.code.to_i
来源：http://dali.gogol.net.cn/Article/details/gt2dbftprcn.html

C#:   (int)resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gt2yncrpwkd.html

[L08] 并发请求多个地址
来源：http://dali.hongshengwenyu.top/Article/details/gt2rwcxluqh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nanxinkj.top/Article/details/gt2yzblvkfu.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dyhzrwve.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2knshsaeu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gt2oucgdnvl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjzkgvu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jianghu66.top/Article/details/gt2eozltacf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigufen.top/Article/details/gt2tczschnw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cucudq.cn/Article/details/gt2wyabtasw.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2exiahaag.html

M. 命令行 / 进程 / 环境
来源：http://dali.birdmap.top/Article/details/gt2kmckncnz.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2dcqdlbag.html

[M01] 读取命令行参数
来源：http://dali.jinqigufen.top/Article/details/gt2hdzxxzin.html

Py:   sys.argv[1:]
来源：http://dali.sxryk.cn/Article/details/gt2agrelcib.html

PHP:  $argv;  $argc;
来源：http://dali.havefunace.top/Article/details/gt2qqkvclkc.html

JS:   process.argv.slice(2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tifcympr.html

TS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gt2uibqlumr.html

Java: args 数组（main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gt2lmuzghoa.html

Go:   os.Args[1:]
来源：http://dali.9152youxi.cn/Article/details/gt2mmvxppkk.html

Ruby: ARGV
来源：http://dali.jianghu66.top/Article/details/gt2twuijtdl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2abuiccfe.html

[M02] 读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gt2licojlbj.html

Py:   os.environ.get("HOME")
来源：http://dali.dashuyun.cn/Article/details/gt2ixdhiyrh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jiagoushi.top/Article/details/gt2lmlnzqii.html

JS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vdrooxcz.html

TS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gt2xcyhiewh.html

Java: System.getenv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gt2rkvdarhk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2rjjtxxzg.html

Ruby: ENV["HOME"]
来源：http://dali.fengsongda.top/Article/details/gt2umwbkqfc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tianlin.xyz/Article/details/gt2oauzzwjp.html

[M03] 执行外部命令
来源：http://dali.haohaochexian.top/Article/details/gt2tlhwayuq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yanxiufei.cn/Article/details/gt2rmwqolit.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gaohongyu789.top/Article/details/gt2guvyoclp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnqzz.top/Article/details/gt2wexlfeks.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gt2yhooferz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.andypj.xyz/Article/details/gt2gpmmxgnt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yvedp.cn/Article/details/gt2oqwaeaxz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.svipenyu.cn/Article/details/gt2dfmxruft.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gaohongyu789.top/Article/details/gt2yerwbvlx.html

[M04] 获取当前工作目录
来源：http://dali.hammf.cn/Article/details/gt2qgpsaumd.html

Py:   os.getcwd()
来源：http://dali.hfpthk.cn/Article/details/gt2oqujtmxy.html

PHP:  getcwd();
来源：http://dali.shangyingyoupin.top/Article/details/gt2gscignct.html

JS:   process.cwd()
来源：http://dali.wangdashe.top/Article/details/gt2jdovvjrh.html

TS:   process.cwd()
来源：http://dali.nwbrower.top/Article/details/gt2zynrfbnf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yueranfly.top/Article/details/gt2wedqtgxg.html

Go:   os.Getwd()
来源：http://dali.xylfe.cn/Article/details/gt2vlsgiggm.html

Ruby: Dir.pwd
来源：http://dali.gogol.net.cn/Article/details/gt2ardaugec.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zycfv.cn/Article/details/gt2qhmijczb.html

[M05] 设置退出码
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hepvhuiy.html

Py:   sys.exit(1)
来源：http://dali.yvedp.cn/Article/details/gt2riysfvdr.html

PHP:  exit(1);
来源：http://dali.yj20258.top/Article/details/gt2fcigzhvy.html

JS:   process.exit(1)
来源：http://dali.meibo888.top/Article/details/gt2hqnubqdt.html

TS:   process.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gt2ulzcwhrr.html

Java: System.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nwgybckq.html

Go:   os.Exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tomnvqhl.html

Ruby: exit 1
来源：http://dali.hnxiangtu.top/Article/details/gt2qlfakyjs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.aizwys.cn/Article/details/gt2oskkqqos.html

[M06] 向标准错误输出
来源：http://dali.andypj.xyz/Article/details/gt2dammgggt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tzawwqrv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wygghffj.html

JS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mflmmtjm.html

TS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gt2oldxkuaq.html

Java: System.err.println("err")
来源：http://dali.xylfe.cn/Article/details/gt2ziupdbks.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnxiangtu.top/Article/details/gt2ozvdkwqe.html

Ruby: warn "err"
来源：http://dali.hnxiangtu.top/Article/details/gt2glvogdsf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nanxinkj.top/Article/details/gt2ptttnmlg.html

[M07] 判断是否为主入口
来源：http://dali.pengpengdd.cyou/Article/details/gt2jditxelg.html

Py:   if __name__ == "__main__":
来源：http://dali.birdmap.top/Article/details/gt2mxlibjiv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hysaishi.cn/Article/details/gt2lgygxvra.html

JS:   require.main === module
来源：http://dali.cheryme.top/Article/details/gt2iywwsuzi.html

TS:   require.main === module
来源：http://dali.xziqi.cn/Article/details/gt2uwkjsabn.html

Java: public static void main(String[] args)
来源：http://dali.andypj.xyz/Article/details/gt2enwkmuzv.html

Go:   func main()
来源：http://dali.iojbl.cn/Article/details/gt2atzeilvz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnmmnsj.html

C#:   static void Main(string[] args)
来源：http://dali.yanxiufei.cn/Article/details/gt2jrvmfauw.html

[M08] 获取系统与运行时信息
来源：http://dali.cucudq.cn/Article/details/gt2utwjughh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.feifeiyinyue.top/Article/details/gt2nokotroa.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sysykeji.top/Article/details/gt2mvbmfwhq.html

JS:   process.platform;  process.version
来源：http://dali.chenjidiqi.icu/Article/details/gt2efphdlyl.html

TS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gt2cauuxopm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.meibo888.top/Article/details/gt2nrslrodo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.redwolf501.top/Article/details/gt2hlvwzwbr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.pengpengdd.cyou/Article/details/gt2psvqjmip.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yvedp.cn/Article/details/gt2rnnbncmh.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2xclyntfb.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmtjmff.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2vlonknqh.html

[N01] 二分查找（有序数组）
来源：http://dali.redwolf501.top/Article/details/gt2ravoatsl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gt2lasthmxe.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nwbrower.top/Article/details/gt2eymtlkln.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gt2zhbngwvo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.snrcjt.cn/Article/details/gt2kxmfeagk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hnqzz.top/Article/details/gt2reyvhvpw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jianghu66.top/Article/details/gt2buaswtlj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shuidangran.top/Article/details/gt2gwnswlxd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sweek.top/Article/details/gt2kemqjdhi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj202588.top/Article/details/gt2cdvrqsha.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gt2rvmwjwrf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.9152youxi.cn/Article/details/gt2ssumuhtq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.birdmap.top/Article/details/gt2iswtzrwk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.svipenyu.cn/Article/details/gt2wfrrowve.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.dashuyun.cn/Article/details/gt2lpmdudiu.html

Go:   slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2qfbdlaoq.html

Ruby: arr.sort
来源：http://dali.hnxiangtu.top/Article/details/gt2pxlsksww.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tianlin.xyz/Article/details/gt2uvshacfp.html

[N03] 快速排序（分治示例）
来源：http://dali.jianghu66.top/Article/details/gt2ebippkja.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xziqi.cn/Article/details/gt2pwhutgdr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ivvv.top/Article/details/gt2vcdlrgea.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jyoumei.cn/Article/details/gt2wencfxwh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxuanxn.top/Article/details/gt2pavgjyxw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xuanzx.com/Article/details/gt2dnpdvlka.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cashguo.top/Article/details/gt2raunuzqk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqlmepa.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.dashuyun.cn/Article/details/gt2vjdkncpp.html

[N04] 斐波那契数列
来源：http://dali.hfpthk.cn/Article/details/gt2ianunbgm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2vlttufle.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hnxiangtu.top/Article/details/gt2gkdqgson.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gt2uxipgbqa.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gt2sruehzke.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rjczaobl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xylfe.cn/Article/details/gt2chukhjdw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.mhx1999.top/Article/details/gt2jtvzngsz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gt2kuafckzd.html

[N05] 最大公约数
来源：http://dali.0kj1m.cn/Article/details/gt2xkfeaugl.html

Py:   math.gcd(a, b)
来源：http://dali.nwbrower.top/Article/details/gt2bueussnw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lfvbilzv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ybcxt.top/Article/details/gt2tkpskdep.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gogol.net.cn/Article/details/gt2ggcaqpoo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.dianchejie.cn/Article/details/gt2ktczhtis.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sweek.top/Article/details/gt2xgwqysfm.html

Ruby: a.gcd(b)
来源：http://dali.dianchejie.cn/Article/details/gt2oosmigxi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.snrcjt.cn/Article/details/gt2jmiwenph.html

[N06] 判断回文字符串
来源：http://dali.hysaishi.cn/Article/details/gt2fttjqxle.html

Py:   s == s[::-1]
来源：http://dali.meibo888.top/Article/details/gt2dlzcsnye.html

PHP:  $s === strrev($s);
来源：http://dali.xinyue.icu/Article/details/gt2iknuvakq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gt2umlmftlq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gt2dhjgowjq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jlsjyb.cn/Article/details/gt2znatpxwb.html

Go:   // 双指针从两端比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wfrjnduf.html

Ruby: s == s.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gt2cdnpatiy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gt2hehwrine.html

[N07] 两数之和（返回下标）
来源：http://dali.feifeiyinyue.top/Article/details/gt2xrgvpplw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.c1oappe.top/Article/details/gt2duoymjyx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jqgfzy.top/Article/details/gt2iksxbmpc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jlsjyb.cn/Article/details/gt2fkrjtqaf.html

TS:   // 手写 Map<string, number>
来源：http://dali.jiagoushi.top/Article/details/gt2gzsdkezx.html

Java: // 手写 HashMap
来源：http://dali.yuxming.cn/Article/details/gt2jxhnuqea.html

Go:   // 手写 map[int]int
来源：http://dali.cheryme.top/Article/details/gt2bjsojeyw.html

Ruby: // 手写 Hash
来源：http://dali.sufxvd.cn/Article/details/gt2ttantdyr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shuidangran.top/Article/details/gt2nrpvlpgv.html

[N08] 生成全排列
来源：http://dali.jiagoushi.top/Article/details/gt2peionqwz.html

Py:   itertools.permutations(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2bwtebknm.html

PHP:  // 手写递归交换
来源：http://dali.tanke756.top/Article/details/gt2cfqqsgtf.html

JS:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gt2jomtpuan.html

TS:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gt2wcibfexc.html

Java: // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gt2fjtrmola.html

Go:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gt2woisicox.html

Ruby: arr.permutation.to_a
来源：http://dali.smart0.xyz/Article/details/gt2unagpynk.html

C#:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gt2trygkabi.html

[N09] 栈与队列
来源：http://dali.yvedp.cn/Article/details/gt2ntjctqxx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj202588.top/Article/details/gt2wwgisbia.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2howvpdlw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gt2bkjynkni.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zdqjudy.top/Article/details/gt2wiergdbq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhiwuduotai.top/Article/details/gt2zcqfanpt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.wangshuangyany.cn/Article/details/gt2pljfhjzo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gt2ukszaogx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shzxlz.cn/Article/details/gt2fkjzymeo.html

[N10] 链表节点定义
来源：http://dali.nanxuanxn.top/Article/details/gt2arjpvdmi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yonumen.top/Article/details/gt2gtsiaggg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.mhx1999.top/Article/details/gt2jjqcubsj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jqgufenzy.top/Article/details/gt2oguoewun.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jqgufenzy.top/Article/details/gt2hpzfxvrv.html

Java: class Node { int v; Node next; }
来源：http://dali.zhixingplan.top/Article/details/gt2oqdfzovt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj202588.top/Article/details/gt2snjavtsh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.9152youxi.cn/Article/details/gt2eyfagrul.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.pycfn.com/Article/details/gt2izycctkg.html

[N11] 二叉树中序遍历
来源：http://dali.cdnleiting.top/Article/details/gt2ojrsyfdp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinqigufen.top/Article/details/gt2auoikefg.html

PHP:  // 手写递归函数
来源：http://dali.sweek.top/Article/details/gt2wjqmhjwf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nfateldg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ybcxt.top/Article/details/gt2sxveskmt.html

Java: // 手写递归
来源：http://dali.fengsongda.top/Article/details/gt2ksqenslm.html

Go:   // 手写递归
来源：http://dali.redwolf501.top/Article/details/gt2wguegpbo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yuanzhike.top/Article/details/gt2wmfffnsy.html

C#:   // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gt2hlqphrvy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.aizwys.cn/Article/details/gt2uqngqmjd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.andypj.xyz/Article/details/gt2tfbicnbd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rqmivxfz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yvedp.cn/Article/details/gt2cpkvwdof.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aibaodan.cn/Article/details/gt2hdkybpwk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.andypj.xyz/Article/details/gt2dikzhgtc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shangyingyoupin.top/Article/details/gt2yqifcney.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhengqikj.top/Article/details/gt2bwlfkdwv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jiagoushi.top/Article/details/gt2veyvnqcb.html


<!-- 参考信息 -->