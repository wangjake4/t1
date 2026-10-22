代发 wailian999

Py:   copy.deepcopy(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qbqhhdve.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yuxming.cn/Article/details/gt2vkqkqvxj.html

JS:   structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gt2qcplkzsi.html

TS:   structuredClone(obj)
来源：http://dali.tanke756.top/Article/details/gt2gvfgfimx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mqdaopnf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pvjxdryp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ivvv.top/Article/details/gt2qnfzxxou.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ydzc1.top/Article/details/gt2sdmynewd.html

[K06] 解析 URL 查询串
来源：http://dali.andypj.xyz/Article/details/gt2jsigjtke.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xuanzx.com/Article/details/gt2astlrazj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.iojbl.cn/Article/details/gt2ssysdgzj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj202588.top/Article/details/gt2ddgzuchl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenjidiqi.icu/Article/details/gt2hlbebaed.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ehwqpu.com/Article/details/gt2hppdlmew.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shangyingyoupin.top/Article/details/gt2yytqncei.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gt2kjnaurbw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gt2fpkflyvn.html

[K07] 进制转换
来源：http://dali.jiagoushi.top/Article/details/gt2pxmojasi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gt2mofenxfm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cheryme.top/Article/details/gt2nnuvnmml.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gt2ydxxmpot.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gt2lzrvmmoc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2duwkaotn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.birdmap.top/Article/details/gt2oiholepo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zycfv.cn/Article/details/gt2sgeiwfdf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gt2lbkodmte.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xylfe.cn/Article/details/gt2opikloih.html

Py:   pickle.dumps(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2uqdzxsru.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sweek.top/Article/details/gt2hznltpaa.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.mhx1999.top/Article/details/gt2hsqkvuvy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.316326.xyz/Article/details/gt2iraqzvmz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.aibaodan.cn/Article/details/gt2bfwheiwk.html

Go:   encoding/gob
来源：http://dali.yangfankeji.com/Article/details/gt2ujbbkvcq.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xrmctrtk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.aibaodan.cn/Article/details/gt2xvwusktu.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2idgvduiu.html

L. 网络请求
来源：http://dali.andypj.xyz/Article/details/gt2nmojwouw.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2qdkkdves.html

[L01] 发送 GET 请求
来源：http://dali.0kj1m.cn/Article/details/gt2trqdespy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ivvv.top/Article/details/gt2qelcqyfy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhixingplan.top/Article/details/gt2hfsxcmzr.html

JS:   await fetch(url)
来源：http://dali.tanke756.top/Article/details/gt2jqxldzws.html

TS:   await fetch(url)
来源：http://dali.ivvv.top/Article/details/gt2hlbbugzq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.quarkkingdee.top/Article/details/gt2cwygazge.html

Go:   resp, err := http.Get(url)
来源：http://dali.tanke756.top/Article/details/gt2eughctnk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj202588.top/Article/details/gt2ctjwnswy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhoulong.xyz/Article/details/gt2jymokjax.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gt2atrsfxyo.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.wangshuangyany.cn/Article/details/gt2lapocbpp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.mhx1999.top/Article/details/gt2glrvopyt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuanzhike.top/Article/details/gt2wrxyatpz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cashguo.top/Article/details/gt2oovkjzrz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenjidiqi.icu/Article/details/gt2pkvvgzut.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.redwolf501.top/Article/details/gt2ydljdnrc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.c1oappe.top/Article/details/gt2ybghdrts.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daxiang520.top/Article/details/gt2gqeshuak.html

[L03] 设置自定义请求头
来源：http://dali.zhiwuduotai.top/Article/details/gt2tfocmeaw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.birdmap.top/Article/details/gt2xrahfsiw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nanxuanxn.top/Article/details/gt2fmqqrymm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gt2sukavbcr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258888.top/Article/details/gt2ktaxazty.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhoulong.xyz/Article/details/gt2vhilunos.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hnxiangtu.top/Article/details/gt2swslcrbo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cqqwz.cn/Article/details/gt2vypmmsyd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.quarkkingdee.top/Article/details/gt2maufycmi.html

[L04] 设置超时
来源：http://dali.bjfxy.top/Article/details/gt2aejpjjhy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yvedp.cn/Article/details/gt2xeqkemnx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.guannengcc.top/Article/details/gt2lrifdpqf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jyoumei.cn/Article/details/gt2gnxsrxgq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guannengcc.top/Article/details/gt2lkzdgonq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cdnleiting.top/Article/details/gt2cstsmenh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenjidiqi.icu/Article/details/gt2edeyrlcr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.guowangkeji.top/Article/details/gt2tjraygwo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.redwolf501.top/Article/details/gt2lcpqjyyp.html

[L05] 上传文件（multipart）
来源：http://dali.yj20258.top/Article/details/gt2bhvcdujg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nwbrower.top/Article/details/gt2pmcbvyhy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hysaishi.cn/Article/details/gt2grkgpjiq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gt2tiflgnvf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gt2ibgfqavq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ybcxt.top/Article/details/gt2dgmtzeko.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ppjwa.cn/Article/details/gt2bjdtrckq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lqdscusv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2eabvtkyo.html

[L06] 解析响应为 JSON
来源：http://dali.ehwqpu.com/Article/details/gt2dyinsbuz.html

Py:   resp.json()
来源：http://dali.sufxvd.cn/Article/details/gt2nflcicgv.html

PHP:  json_decode($body, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ozidsbhp.html

JS:   await resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gt2psjzzzyo.html

TS:   await resp.json()
来源：http://dali.guannengcc.top/Article/details/gt2hyhmjeap.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gt2wfgshrjp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yanxiufei.cn/Article/details/gt2jpuuacld.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gzhubu.top/Article/details/gt2nvyzqjvh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangshuangyany.cn/Article/details/gt2bpojlbph.html

[L07] 处理 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gt2iwqwkigz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.iojbl.cn/Article/details/gt2qqzlydyq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fzhhl.top/Article/details/gt2bvbmyvpe.html

JS:   resp.ok;  resp.status
来源：http://dali.cucudq.cn/Article/details/gt2tmjkvlot.html

TS:   resp.ok;  resp.status
来源：http://dali.gaohongyu789.top/Article/details/gt2keugjfrx.html

Java: resp.statusCode()
来源：http://dali.cdnleiting.top/Article/details/gt2fncvllcn.html

Go:   resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gt2hwbwlbrt.html

Ruby: resp.code.to_i
来源：http://dali.feifeiyinyue.top/Article/details/gt2bqhdeaii.html

C#:   (int)resp.StatusCode
来源：http://dali.redwolf501.top/Article/details/gt2ogyrgydc.html

[L08] 并发请求多个地址
来源：http://dali.pengpengdd.cyou/Article/details/gt2srcrprty.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.dashuyun.cn/Article/details/gt2ckfhvisw.html

PHP:  curl_multi_init() 系列
来源：http://dali.aizwys.cn/Article/details/gt2ltqsqira.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gt2bqklqunh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zsweokdq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hfpthk.cn/Article/details/gt2foairpim.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sysykeji.top/Article/details/gt2wubvwfii.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnxiangtu.top/Article/details/gt2vlxxzmlj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ehwqpu.com/Article/details/gt2tkfdcgwt.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2hloscbxm.html

M. 命令行 / 进程 / 环境
来源：http://dali.quarkkingdee.top/Article/details/gt2ceagjnei.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2wwhzpupc.html

[M01] 读取命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gt2fcwpigmk.html

Py:   sys.argv[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gt2ylbftchq.html

PHP:  $argv;  $argc;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aspwlyyr.html

JS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gt2aayakftt.html

TS:   process.argv.slice(2)
来源：http://dali.yanxiufei.cn/Article/details/gt2bljnoekd.html

Java: args 数组（main 方法参数）
来源：http://dali.chenzaomai.com/Article/details/gt2wfgjnupe.html

Go:   os.Args[1:]
来源：http://dali.meibo888.top/Article/details/gt2newbyibd.html

Ruby: ARGV
来源：http://dali.bjfxy.top/Article/details/gt2jonpzgee.html

C#:   args 数组（Main 方法参数）
来源：http://dali.fengsongda.top/Article/details/gt2ckrpyfma.html

[M02] 读取环境变量
来源：http://dali.zhengqikj.top/Article/details/gt2mvkwafln.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gt2ljoanxpo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gt2fuajwndl.html

JS:   process.env.HOME
来源：http://dali.cheryme.top/Article/details/gt2gmuiudxj.html

TS:   process.env.HOME
来源：http://dali.hongshengwenyu.top/Article/details/gt2ldxaqxhh.html

Java: System.getenv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gt2zwhlgbyf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gt2wtlomfph.html

Ruby: ENV["HOME"]
来源：http://dali.sufxvd.cn/Article/details/gt2mbvgkofb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daria6918.cn/Article/details/gt2mfumccek.html

[M03] 执行外部命令
来源：http://dali.shzxlz.cn/Article/details/gt2afcgkkdr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dkhtwpot.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.dashuyun.cn/Article/details/gt2ogduhtvl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cucudq.cn/Article/details/gt2fhahwcvo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2xgxsukzo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuetiantiany.cn/Article/details/gt2jhwtjyvv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.snrcjt.cn/Article/details/gt2itjwezkq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cheryme.top/Article/details/gt2uxdssvag.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hammf.cn/Article/details/gt2okyepxcv.html

[M04] 获取当前工作目录
来源：http://dali.chenlongwang.top/Article/details/gt2zuiknwcp.html

Py:   os.getcwd()
来源：http://dali.sufxvd.cn/Article/details/gt2hrymntxu.html

PHP:  getcwd();
来源：http://dali.dianchejie.cn/Article/details/gt2llxfhybh.html

JS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gt2qnruvuil.html

TS:   process.cwd()
来源：http://dali.gzhubu.top/Article/details/gt2mskqtqjx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenjidiqi.icu/Article/details/gt2yvepfdhf.html

Go:   os.Getwd()
来源：http://dali.wangshuangyany.cn/Article/details/gt2zvdcdrmh.html

Ruby: Dir.pwd
来源：http://dali.zhiwuduotai.top/Article/details/gt2qfwkkgxn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gaohongyu789.top/Article/details/gt2jfzbxgaj.html

[M05] 设置退出码
来源：http://dali.havefunace.top/Article/details/gt2iellrumj.html

Py:   sys.exit(1)
来源：http://dali.meibo888.top/Article/details/gt2amgzazdd.html

PHP:  exit(1);
来源：http://dali.zhongyouzk.top/Article/details/gt2fyrhsxcq.html

JS:   process.exit(1)
来源：http://dali.sysykeji.top/Article/details/gt2ahgzyygb.html

TS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gt2ezuhnlrv.html

Java: System.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2beewlnua.html

Go:   os.Exit(1)
来源：http://dali.mhx1999.top/Article/details/gt2oknozhje.html

Ruby: exit 1
来源：http://dali.meibo888.top/Article/details/gt2mvnjgdba.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dashuyun.cn/Article/details/gt2titezwuy.html

[M06] 向标准错误输出
来源：http://dali.pengpengdd.cyou/Article/details/gt2rkodakzh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.9152youxi.cn/Article/details/gt2qpuekytu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinqigfzy.top/Article/details/gt2emjacpnb.html

JS:   console.error("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cqmhrqmb.html

TS:   console.error("err")
来源：http://dali.daria6918.cn/Article/details/gt2vgsfwjgz.html

Java: System.err.println("err")
来源：http://dali.jinqigufen.top/Article/details/gt2yyknnrkf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cashguo.top/Article/details/gt2ttncmntk.html

Ruby: warn "err"
来源：http://dali.mhx1999.top/Article/details/gt2sawgcnqp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2amnbiwsx.html

[M07] 判断是否为主入口
来源：http://dali.cucudq.cn/Article/details/gt2huiwmqrl.html

Py:   if __name__ == "__main__":
来源：http://dali.feifeiyinyue.top/Article/details/gt2swcauapg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ecesqhes.html

JS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gt2gtabtvns.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnnphvw.html

Java: public static void main(String[] args)
来源：http://dali.hnxiangtu.top/Article/details/gt2cvuretsx.html

Go:   func main()
来源：http://dali.hnxiangtu.top/Article/details/gt2ywilwbxd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.kuanghao11.cn/Article/details/gt2ogrxcukn.html

C#:   static void Main(string[] args)
来源：http://dali.quarkkingdee.top/Article/details/gt2rlhbocrq.html

[M08] 获取系统与运行时信息
来源：http://dali.vqdsnc.cn/Article/details/gt2rrvjemnm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinqigfzy.top/Article/details/gt2kwamokrf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yueranfly.top/Article/details/gt2qnxwnofq.html

JS:   process.platform;  process.version
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sjwwvyfg.html

TS:   process.platform;  process.version
来源：http://dali.mhx1999.top/Article/details/gt2cjuxsqhp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.iojbl.cn/Article/details/gt2umpbcfiq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.mhx1999.top/Article/details/gt2sqrjckqa.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fengsongda.top/Article/details/gt2tbrsoxvs.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hysaishi.cn/Article/details/gt2wbrhqcak.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2vzyxanis.html

N. 数据结构与算法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ztboonuy.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2bhaodruu.html

[N01] 二分查找（有序数组）
来源：http://dali.hnxiangtu.top/Article/details/gt2mdjnxpaz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gt2ioilmlya.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkmmses.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gt2yrxiqvem.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gt2tgouylhs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gt2vwjuxmnt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2jmtuwtht.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yuanzhike.top/Article/details/gt2itetpynn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gt2zghvcddh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yuanzhike.top/Article/details/gt2yuugjzpe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.redwolf501.top/Article/details/gt2jkmgmeoy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nanxinkj.top/Article/details/gt2flojthbo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gt2efszbrqz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2slitwgmu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nwbrower.top/Article/details/gt2jxxxaqvm.html

Go:   slices.Sort(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2jbvlpobc.html

Ruby: arr.sort
来源：http://dali.yj20258.top/Article/details/gt2inaanwqk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jqgfzy.top/Article/details/gt2luqojtgi.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2swyharxo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.vqdsnc.cn/Article/details/gt2cuhibywk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cashguo.top/Article/details/gt2itflyixw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangdashe.top/Article/details/gt2huiwiveu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.quarkkingdee.top/Article/details/gt2xzlvjgkl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.tanke756.top/Article/details/gt2nurvknxv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhengqikj.top/Article/details/gt2aofoqfyv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shzxlz.cn/Article/details/gt2hmrgmtqk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.havefunace.top/Article/details/gt2srgetkvl.html

[N04] 斐波那契数列
来源：http://dali.smart0.xyz/Article/details/gt2iogvjksn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gt2gdeemyed.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yanxiufei.cn/Article/details/gt2miegomdc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2puxrsyni.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shangyingyoupin.top/Article/details/gt2fkwtskzu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.svipenyu.cn/Article/details/gt2hvitokgj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2cbhnstfl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhixingplan.top/Article/details/gt2fsdayehd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gt2laubwlik.html

[N05] 最大公约数
来源：http://dali.zhoulong.xyz/Article/details/gt2mckexqbn.html

Py:   math.gcd(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vriarivl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xinyue.icu/Article/details/gt2cxavztil.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ppjwa.cn/Article/details/gt2nyafvver.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnqzz.top/Article/details/gt2sjessfhs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guannengcc.top/Article/details/gt2grhmqwjv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.0kj1m.cn/Article/details/gt2mrinmoqs.html

Ruby: a.gcd(b)
来源：http://dali.mhx1999.top/Article/details/gt2vdjijzll.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.0kj1m.cn/Article/details/gt2mrbdrqyw.html

[N06] 判断回文字符串
来源：http://dali.zhixingplan.top/Article/details/gt2deitnxui.html

Py:   s == s[::-1]
来源：http://dali.daria6918.cn/Article/details/gt2pvrwsfre.html

PHP:  $s === strrev($s);
来源：http://dali.jianghu66.top/Article/details/gt2rqssexpd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gt2bpnjfgyn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gt2wdgwecuo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xziqi.cn/Article/details/gt2dikzxclg.html

Go:   // 双指针从两端比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dzpcoqti.html

Ruby: s == s.reverse
来源：http://dali.hysaishi.cn/Article/details/gt2yxrlpkqn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhengqikj.top/Article/details/gt2lraiptjh.html

[N07] 两数之和（返回下标）
来源：http://dali.shangyingyoupin.top/Article/details/gt2ycybuzvt.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xylfe.cn/Article/details/gt2lmgixkem.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.vqdsnc.cn/Article/details/gt2ompetfof.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.snrcjt.cn/Article/details/gt2rkpklqum.html

TS:   // 手写 Map<string, number>
来源：http://dali.zdqjudy.top/Article/details/gt2airgcbdh.html

Java: // 手写 HashMap
来源：http://dali.xylfe.cn/Article/details/gt2ldhxtppc.html

Go:   // 手写 map[int]int
来源：http://dali.ppjwa.cn/Article/details/gt2ejiinuww.html

Ruby: // 手写 Hash
来源：http://dali.cucudq.cn/Article/details/gt2ayktlcci.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.aibaodan.cn/Article/details/gt2jsrmktys.html

[N08] 生成全排列
来源：http://dali.yonumen.top/Article/details/gt2pvswoxts.html

Py:   itertools.permutations(arr)
来源：http://dali.aizwys.cn/Article/details/gt2xkzvclrw.html

PHP:  // 手写递归交换
来源：http://dali.daxiang520.top/Article/details/gt2esmhntfh.html

JS:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gt2fomxukfp.html

TS:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2uarngahe.html

Java: // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gt2qazqbdqu.html

Go:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gt2xcqmqiaf.html

Ruby: arr.permutation.to_a
来源：http://dali.c1oappe.top/Article/details/gt2ymnubutv.html

C#:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gt2ixijjotk.html

[N09] 栈与队列
来源：http://dali.gogol.net.cn/Article/details/gt2xbuzvkhz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ydzc1.top/Article/details/gt2sskqbhbd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ypncddmx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gt2ezmerkoa.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lesbvtxu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cucudq.cn/Article/details/gt2ycaefvte.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yongpay.top/Article/details/gt2uvnbeeth.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gt2gjnbacpf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinqigfzy.top/Article/details/gt2xyvgbtlj.html

[N10] 链表节点定义
来源：http://dali.cashguo.top/Article/details/gt2nnurercj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.bjfxy.top/Article/details/gt2qfvdiaoy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sufxvd.cn/Article/details/gt2dnzswdxa.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigfzy.top/Article/details/gt2blndbmly.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dzrlgnaa.html

Java: class Node { int v; Node next; }
来源：http://dali.zhongyouzk.top/Article/details/gt2gifchlbv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.daxiang520.top/Article/details/gt2chaydfqx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ehwqpu.com/Article/details/gt2fzharngb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jyoumei.cn/Article/details/gt2paawjota.html

[N11] 二叉树中序遍历
来源：http://dali.jinqigfzy.top/Article/details/gt2wizjaabn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xziqi.cn/Article/details/gt2wjtjyhpj.html

PHP:  // 手写递归函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yqwmwiyf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hammf.cn/Article/details/gt2nrjbrhxg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eugicpcb.html

Java: // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hxtqtfgc.html

Go:   // 手写递归
来源：http://dali.yj202588.top/Article/details/gt2gusivpvg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yvedp.cn/Article/details/gt2qwipijjh.html

C#:   // 手写递归
来源：http://dali.meibo888.top/Article/details/gt2kcvpaqgx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.snrcjt.cn/Article/details/gt2wirwtqja.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj20258.top/Article/details/gt2aucxkumj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenjidiqi.icu/Article/details/gt2uzgpmzfz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sysykeji.top/Article/details/gt2dunqsdxv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yonumen.top/Article/details/gt2lwmlxoos.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhoulong.xyz/Article/details/gt2xewcyscl.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sufxvd.cn/Article/details/gt2fmcgnsgn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.smart0.xyz/Article/details/gt2jncapvfk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jianghu66.top/Article/details/gt2ohbulqct.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2iladtihs.html

O. 并发与异步
来源：http://dali.xuanzx.com/Article/details/gt2nqrgrwla.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2iiclvbnn.html

[O01] 启动一个线程
来源：http://dali.316326.xyz/Article/details/gt2yzwyrgwi.html


<!-- 参考信息 -->