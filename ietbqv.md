代发 wailian999

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.0kj1m.cn/Article/details/gt2lxawajug.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shuidangran.top/Article/details/gt2owyynzso.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gt2qhpwaozo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ydzc1.top/Article/details/gt2tmskzxxu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ehwqpu.com/Article/details/gt2xwzshkvf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.aizwys.cn/Article/details/gt2bohdhcxk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxinkj.top/Article/details/gt2zvyojyvd.html

[K05] 深拷贝对象
来源：http://dali.quarkkingdee.top/Article/details/gt2ltafxrmj.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqpbhmw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj20258.top/Article/details/gt2bjarkubr.html

JS:   structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2kurdtafj.html

TS:   structuredClone(obj)
来源：http://dali.tanke756.top/Article/details/gt2kvgpwazv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.haohaochexian.top/Article/details/gt2egieihjb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wlryjpgv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sysykeji.top/Article/details/gt2vxnoycck.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ydzc1.top/Article/details/gt2wflygurr.html

[K06] 解析 URL 查询串
来源：http://dali.jqgfzy.top/Article/details/gt2vhosvkvs.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gt2zmdlaxpe.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jyoumei.cn/Article/details/gt2gefarkcd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnqzz.top/Article/details/gt2dzhpksor.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gt2eiiarnyd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangshuangyany.cn/Article/details/gt2gunqwmov.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gt2umipjwyl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gt2lxunfcti.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gt2gcyfbmhk.html

[K07] 进制转换
来源：http://dali.xuetiantiany.cn/Article/details/gt2lvzgzmqd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gt2xcqxvsra.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.c1oappe.top/Article/details/gt2fjuiztgu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gt2ejbrgwkv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gt2deudjvux.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gt2qxjbcedm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yongpay.top/Article/details/gt2cckwkvsj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhixingplan.top/Article/details/gt2ofvyhhdn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gt2eirsetdt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gaohongyu789.top/Article/details/gt2qmoksncr.html

Py:   pickle.dumps(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2hemjfchv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yanxiufei.cn/Article/details/gt2jinjplvo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnxiangtu.top/Article/details/gt2obntvovv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wlxrdrqs.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nwbrower.top/Article/details/gt2uncycowo.html

Go:   encoding/gob
来源：http://dali.dashuyun.cn/Article/details/gt2gtggfjst.html

Ruby: Marshal.dump(obj)
来源：http://dali.daxiang520.top/Article/details/gt2pbxmydng.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xuanzx.com/Article/details/gt2lhnhzxxo.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rxxewtxa.html

L. 网络请求
来源：http://dali.sxryk.cn/Article/details/gt2ddriihgx.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2lylyhxnn.html

[L01] 发送 GET 请求
来源：http://dali.cdnleiting.top/Article/details/gt2cwjubfpk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.meibo888.top/Article/details/gt2tcjnhzxd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shangyingyoupin.top/Article/details/gt2vqlorsuu.html

JS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gt2objtjcpx.html

TS:   await fetch(url)
来源：http://dali.jianghu66.top/Article/details/gt2auxvtjjs.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pukjyofk.html

Go:   resp, err := http.Get(url)
来源：http://dali.sweek.top/Article/details/gt2llvxipcs.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eeieehxb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jqgufenzy.top/Article/details/gt2fschsdgw.html

[L02] 发送 POST JSON
来源：http://dali.daxiang520.top/Article/details/gt2crurshok.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.guowangkeji.top/Article/details/gt2rzxvzuzs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yuanzhike.top/Article/details/gt2lsvuoofn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258.top/Article/details/gt2tdowlehf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258.top/Article/details/gt2fpwaridi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hnxiangtu.top/Article/details/gt2gohwrtpc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.bjfxy.top/Article/details/gt2jhltbhjh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2isdcuvim.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jraewxlk.html

[L03] 设置自定义请求头
来源：http://dali.ivvv.top/Article/details/gt2nmvutgta.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zycfv.cn/Article/details/gt2hzgjszhx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.guannengcc.top/Article/details/gt2qgzhfpxw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fzhhl.top/Article/details/gt2mvbddiqy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gt2mogjtddm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tian-w.cn/Article/details/gt2xdjpehlj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gt2hocdyqup.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cqqwz.cn/Article/details/gt2hjbzqbbk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sufxvd.cn/Article/details/gt2itmqpdyz.html

[L04] 设置超时
来源：http://dali.jianghu66.top/Article/details/gt2wbtrykip.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sysykeji.top/Article/details/gt2nclvvmwj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fzhhl.top/Article/details/gt2zdgdocka.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hongshengwenyu.top/Article/details/gt2rpnoysdg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gt2asaqsnxd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hnxiangtu.top/Article/details/gt2novxtake.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ikqcrtjs.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ybcxt.top/Article/details/gt2uilignvl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.dashuyun.cn/Article/details/gt2kfkaayhc.html

[L05] 上传文件（multipart）
来源：http://dali.hywenlv.cn/Article/details/gt2xfvdwitv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hongshengwenyu.top/Article/details/gt2kqknacoj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hammf.cn/Article/details/gt2cosbshbf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zdqjudy.top/Article/details/gt2ceqaotes.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aadneoqc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgfzy.top/Article/details/gt2ljdiivww.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gaohongyu789.top/Article/details/gt2zsgkcbzm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daria6918.cn/Article/details/gt2fzwcehsl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2mzfxrndo.html

[L06] 解析响应为 JSON
来源：http://dali.yvedp.cn/Article/details/gt2kpyrzxql.html

Py:   resp.json()
来源：http://dali.ydzc1.top/Article/details/gt2qepyduip.html

PHP:  json_decode($body, true);
来源：http://dali.zhixingplan.top/Article/details/gt2iwdvnvee.html

JS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aetmrmsz.html

TS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gt2vadequcl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yangfankeji.com/Article/details/gt2mcppbeet.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kudvbiuz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jianghu66.top/Article/details/gt2ltqirhsc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hammf.cn/Article/details/gt2codzefkx.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhiwuduotai.top/Article/details/gt2reddiyzw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenlongwang.top/Article/details/gt2bgrnzctm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.c1oappe.top/Article/details/gt2ggaiqfls.html

JS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gt2ntbacone.html

TS:   resp.ok;  resp.status
来源：http://dali.vqdsnc.cn/Article/details/gt2tjjztlwb.html

Java: resp.statusCode()
来源：http://dali.xylfe.cn/Article/details/gt2lwfmikwk.html

Go:   resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gt2glfjeynx.html

Ruby: resp.code.to_i
来源：http://dali.jlsjyb.cn/Article/details/gt2swbyzsem.html

C#:   (int)resp.StatusCode
来源：http://dali.daxiang520.top/Article/details/gt2jojxihok.html

[L08] 并发请求多个地址
来源：http://dali.wangdashe.top/Article/details/gt2qmwpnkcq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.birdmap.top/Article/details/gt2opfedjar.html

PHP:  curl_multi_init() 系列
来源：http://dali.snrcjt.cn/Article/details/gt2avktdjds.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gt2flwqzuqf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gt2fpipaekw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hfpthk.cn/Article/details/gt2iwxbyuyy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cqqwz.cn/Article/details/gt2bbmafhpu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.iojbl.cn/Article/details/gt2lzojcspm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daxiang520.top/Article/details/gt2ryxwepum.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2kiqtkzcj.html

M. 命令行 / 进程 / 环境
来源：http://dali.svipenyu.cn/Article/details/gt2plyuukjz.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2qctpqvjm.html

[M01] 读取命令行参数
来源：http://dali.gaohongyu789.top/Article/details/gt2wpwvjjpj.html

Py:   sys.argv[1:]
来源：http://dali.zhongyouzk.top/Article/details/gt2hvjrtmyn.html

PHP:  $argv;  $argc;
来源：http://dali.aibaodan.cn/Article/details/gt2xpmtdryx.html

JS:   process.argv.slice(2)
来源：http://dali.aibaodan.cn/Article/details/gt2cidmuxmr.html

TS:   process.argv.slice(2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pcrgsoze.html

Java: args 数组（main 方法参数）
来源：http://dali.cdnleiting.top/Article/details/gt2ybrkeqer.html

Go:   os.Args[1:]
来源：http://dali.havefunace.top/Article/details/gt2qeavrpeh.html

Ruby: ARGV
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tcwzeafd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yvedp.cn/Article/details/gt2cozkyupf.html

[M02] 读取环境变量
来源：http://dali.andypj.xyz/Article/details/gt2dzciwmru.html

Py:   os.environ.get("HOME")
来源：http://dali.shuidangran.top/Article/details/gt2myfpyowh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gt2xtmjyoxo.html

JS:   process.env.HOME
来源：http://dali.xziqi.cn/Article/details/gt2zjoderyn.html

TS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gt2ufzwquim.html

Java: System.getenv("HOME")
来源：http://dali.tianlin.xyz/Article/details/gt2bhpefscj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xaxygytu.html

Ruby: ENV["HOME"]
来源：http://dali.cqqwz.cn/Article/details/gt2mtzmktmh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bmuduhcc.html

[M03] 执行外部命令
来源：http://dali.iojbl.cn/Article/details/gt2ddxgkreb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gzhubu.top/Article/details/gt2nkverjfx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yangfankeji.com/Article/details/gt2blmujgee.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfruoqgt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cheryme.top/Article/details/gt2jrveneow.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yueranfly.top/Article/details/gt2pjticril.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sweek.top/Article/details/gt2glueibmg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgufenzy.top/Article/details/gt2illbztoc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yanxiufei.cn/Article/details/gt2klwsvurz.html

[M04] 获取当前工作目录
来源：http://dali.bjfxy.top/Article/details/gt2uyaabcdh.html

Py:   os.getcwd()
来源：http://dali.tianlin.xyz/Article/details/gt2gavsiyno.html

PHP:  getcwd();
来源：http://dali.xylfe.cn/Article/details/gt2cdzimbsq.html

JS:   process.cwd()
来源：http://dali.cashguo.top/Article/details/gt2iswsfmgz.html

TS:   process.cwd()
来源：http://dali.haohaochexian.top/Article/details/gt2evvewnra.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.c1oappe.top/Article/details/gt2prqiebao.html

Go:   os.Getwd()
来源：http://dali.svipenyu.cn/Article/details/gt2jpbqakna.html

Ruby: Dir.pwd
来源：http://dali.jinqigfzy.top/Article/details/gt2wqisdtbp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.mhx1999.top/Article/details/gt2femqtshp.html

[M05] 设置退出码
来源：http://dali.bjfxy.top/Article/details/gt2sbfoqtej.html

Py:   sys.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2oavtvosu.html

PHP:  exit(1);
来源：http://dali.mhx1999.top/Article/details/gt2eebcrkww.html

JS:   process.exit(1)
来源：http://dali.iojbl.cn/Article/details/gt2aigddsgj.html

TS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gt2znkgpqha.html

Java: System.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2qhdbkehh.html

Go:   os.Exit(1)
来源：http://dali.gzhubu.top/Article/details/gt2ppiqviag.html

Ruby: exit 1
来源：http://dali.snrcjt.cn/Article/details/gt2chtioeqe.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zycfv.cn/Article/details/gt2ucbbijwc.html

[M06] 向标准错误输出
来源：http://dali.316326.xyz/Article/details/gt2vxdccoqs.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhoulong.xyz/Article/details/gt2mhusblcs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nwbrower.top/Article/details/gt2orhbvonw.html

JS:   console.error("err")
来源：http://dali.9152youxi.cn/Article/details/gt2dfjnqmiu.html

TS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gt2pphclycr.html

Java: System.err.println("err")
来源：http://dali.pycfn.com/Article/details/gt2ryqwutlt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj20258.top/Article/details/gt2lyszcwmq.html

Ruby: warn "err"
来源：http://dali.xylfe.cn/Article/details/gt2uwvrblfd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cqqwz.cn/Article/details/gt2ebssohyn.html

[M07] 判断是否为主入口
来源：http://dali.kuanghao11.cn/Article/details/gt2zpyqvdvw.html

Py:   if __name__ == "__main__":
来源：http://dali.ivvv.top/Article/details/gt2xvihfmds.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yongpay.top/Article/details/gt2epomyvap.html

JS:   require.main === module
来源：http://dali.andypj.xyz/Article/details/gt2cqxpbuex.html

TS:   require.main === module
来源：http://dali.aizwys.cn/Article/details/gt2oxsygukw.html

Java: public static void main(String[] args)
来源：http://dali.jianghu66.top/Article/details/gt2eaktdmfg.html

Go:   func main()
来源：http://dali.0kj1m.cn/Article/details/gt2jkdfcslx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhengqikj.top/Article/details/gt2pnuqybyk.html

C#:   static void Main(string[] args)
来源：http://dali.zhixingplan.top/Article/details/gt2zxnqclox.html

[M08] 获取系统与运行时信息
来源：http://dali.zhengqikj.top/Article/details/gt2tqxopbwy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sweek.top/Article/details/gt2qutklmxu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tianlin.xyz/Article/details/gt2rlkqiwee.html

JS:   process.platform;  process.version
来源：http://dali.dianchejie.cn/Article/details/gt2uvuemhdw.html

TS:   process.platform;  process.version
来源：http://dali.chenzaomai.com/Article/details/gt2fwjiesim.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xuanzx.com/Article/details/gt2ixpnkcpc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.guowangkeji.top/Article/details/gt2tjywpomh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.9152youxi.cn/Article/details/gt2knhvlihw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.dashuyun.cn/Article/details/gt2wydcvhir.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2vkybyssv.html

N. 数据结构与算法
来源：http://dali.ivvv.top/Article/details/gt2dwzxqxwu.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2cofnpfis.html

[N01] 二分查找（有序数组）
来源：http://dali.gzhubu.top/Article/details/gt2nmrlowse.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gt2vpupvycg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.redwolf501.top/Article/details/gt2kevqtbmw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gt2jvtlvhnq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gt2xzugvlku.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2ufxiemvq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yj20258888.top/Article/details/gt2wadbedhn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fzpmreqh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sxryk.cn/Article/details/gt2zjkhpivm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.andypj.xyz/Article/details/gt2vvuhwcni.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gt2vhxghlyl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yvedp.cn/Article/details/gt2gmsrpqyf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ziorusus.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxinkj.top/Article/details/gt2jtlzwico.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhengqikj.top/Article/details/gt2swfwthzl.html

Go:   slices.Sort(arr)
来源：http://dali.cashguo.top/Article/details/gt2yjeqxolt.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gt2chjhhzwj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhengqikj.top/Article/details/gt2nmccbeea.html

[N03] 快速排序（分治示例）
来源：http://dali.pycfn.com/Article/details/gt2bjmaujim.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wmyetqwc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xuanzx.com/Article/details/gt2qvxkweqz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hfpthk.cn/Article/details/gt2erlpbtsl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ppjwa.cn/Article/details/gt2tvasogef.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.daria6918.cn/Article/details/gt2kzkpjwon.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zycfv.cn/Article/details/gt2oszlwfdm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sweek.top/Article/details/gt2pwikzcva.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.9152youxi.cn/Article/details/gt2vplpklxi.html

[N04] 斐波那契数列
来源：http://dali.yongpay.top/Article/details/gt2rafiarwv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hnqzz.top/Article/details/gt2usikvjey.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.snrcjt.cn/Article/details/gt2kvgmkiwx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gt2rnjmnqpn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gt2pikydknx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ufcljleu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.daxiang520.top/Article/details/gt2dpkiyaqq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fughvchf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gt2mnlczkis.html

[N05] 最大公约数
来源：http://dali.xylfe.cn/Article/details/gt2guzycluy.html

Py:   math.gcd(a, b)
来源：http://dali.yuanzhike.top/Article/details/gt2lwolfhzp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ybcxt.top/Article/details/gt2rofbmqlj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.snrcjt.cn/Article/details/gt2fpfmedzk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenzaomai.com/Article/details/gt2rplcigun.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.havefunace.top/Article/details/gt2medauxvy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.feifeiyinyue.top/Article/details/gt2tyvdowru.html

Ruby: a.gcd(b)
来源：http://dali.havefunace.top/Article/details/gt2yfwipobs.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinqigufen.top/Article/details/gt2sximexwy.html

[N06] 判断回文字符串
来源：http://dali.dianchejie.cn/Article/details/gt2yiyaqhpn.html

Py:   s == s[::-1]
来源：http://dali.aizwys.cn/Article/details/gt2twnhuqwb.html

PHP:  $s === strrev($s);
来源：http://dali.zhengqikj.top/Article/details/gt2vulkdgwf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zfdktbem.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gt2izwssqtq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ybcxt.top/Article/details/gt2afaqpqyx.html

Go:   // 双指针从两端比较
来源：http://dali.ehwqpu.com/Article/details/gt2tfdvrhqo.html

Ruby: s == s.reverse
来源：http://dali.cashguo.top/Article/details/gt2lswrrwzw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rigdwtda.html

[N07] 两数之和（返回下标）
来源：http://dali.xziqi.cn/Article/details/gt2ktzmhpqs.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhengqikj.top/Article/details/gt2qcfmiven.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jqgufenzy.top/Article/details/gt2mmtpezeg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.meibo888.top/Article/details/gt2mkgiwtmu.html

TS:   // 手写 Map<string, number>
来源：http://dali.xuetiantiany.cn/Article/details/gt2sarblize.html

Java: // 手写 HashMap
来源：http://dali.xuetiantiany.cn/Article/details/gt2lvklcmub.html

Go:   // 手写 map[int]int
来源：http://dali.xuetiantiany.cn/Article/details/gt2pshycqqz.html

Ruby: // 手写 Hash
来源：http://dali.aibaodan.cn/Article/details/gt2lwrbwtap.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sysykeji.top/Article/details/gt2oxtyngdt.html

[N08] 生成全排列
来源：http://dali.shangyingyoupin.top/Article/details/gt2zjuaaysk.html

Py:   itertools.permutations(arr)
来源：http://dali.yj20258.top/Article/details/gt2wrglccll.html

PHP:  // 手写递归交换
来源：http://dali.zycfv.cn/Article/details/gt2nhkhcvws.html

JS:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gt2dibibirt.html

TS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gt2pidsrcan.html

Java: // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gt2cnfnngcj.html

Go:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gt2rjafydfh.html

Ruby: arr.permutation.to_a
来源：http://dali.pengpengdd.cyou/Article/details/gt2ivsbsnbk.html

C#:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gt2zkfyanrl.html

[N09] 栈与队列
来源：http://dali.gzhubu.top/Article/details/gt2zowsmggq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sxryk.cn/Article/details/gt2nzgisypw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gt2umkebkbt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jyoumei.cn/Article/details/gt2grbblexe.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nanxuanxn.top/Article/details/gt2iplpqqpk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj20258888.top/Article/details/gt2ppuvrfrq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.9152youxi.cn/Article/details/gt2lewbffus.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cqrifbma.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ywahkevq.html

[N10] 链表节点定义
来源：http://dali.yangfankeji.com/Article/details/gt2pjzcruyd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hammf.cn/Article/details/gt2imiwumdk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cashguo.top/Article/details/gt2cxqayxnr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.snrcjt.cn/Article/details/gt2gapzcrca.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nanxuanxn.top/Article/details/gt2njkxxudi.html

Java: class Node { int v; Node next; }
来源：http://dali.yonumen.top/Article/details/gt2sizexxqp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.iojbl.cn/Article/details/gt2vyobkrwj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhoulong.xyz/Article/details/gt2moanzcjd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkgbkfj.html

[N11] 二叉树中序遍历
来源：http://dali.daria6918.cn/Article/details/gt2pdcperkz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hnqzz.top/Article/details/gt2pegnrdlz.html

PHP:  // 手写递归函数
来源：http://dali.havefunace.top/Article/details/gt2jocqajsu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenlongwang.top/Article/details/gt2ukqgfgkg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenjidiqi.icu/Article/details/gt2qnnvrqgz.html

Java: // 手写递归
来源：http://dali.yueranfly.top/Article/details/gt2igsboxxy.html

Go:   // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gt2tgtadxyz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj202588.top/Article/details/gt2yhusiwej.html

C#:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gt2nuanbaic.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.aizwys.cn/Article/details/gt2lntfrncp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ppjwa.cn/Article/details/gt2amqcqnto.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zdqjudy.top/Article/details/gt2lwktcelq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuanzhike.top/Article/details/gt2ncmhafjm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258.top/Article/details/gt2bfpuibfw.html


<!-- 参考信息 -->