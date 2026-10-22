代发 wailian999

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zdqjudy.top/Article/details/gt2utimzsjt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxbaxpd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shzxlz.cn/Article/details/gt2wgsiesgp.html

Py:   pickle.dumps(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2xqjygzmi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jiagoushi.top/Article/details/gt2vgjeizqq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.snrcjt.cn/Article/details/gt2uludihdc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.havefunace.top/Article/details/gt2tgbcthxb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yueranfly.top/Article/details/gt2jqxwjfro.html

Go:   encoding/gob
来源：http://dali.tanke756.top/Article/details/gt2gmiyqdrg.html

Ruby: Marshal.dump(obj)
来源：http://dali.fzhhl.top/Article/details/gt2kwuusxhs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shzxlz.cn/Article/details/gt2aztsqmiw.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2cwuxkxap.html

L. 网络请求
来源：http://dali.gzhubu.top/Article/details/gt2umhyiuqg.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2pmkarvhj.html

[L01] 发送 GET 请求
来源：http://dali.ehwqpu.com/Article/details/gt2mpjfkndk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nwbrower.top/Article/details/gt2qdquxmix.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.9152youxi.cn/Article/details/gt2rlzjmfqu.html

JS:   await fetch(url)
来源：http://dali.jiagoushi.top/Article/details/gt2htzpejqz.html

TS:   await fetch(url)
来源：http://dali.ybcxt.top/Article/details/gt2wskpfeie.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ivvv.top/Article/details/gt2qsstvqvn.html

Go:   resp, err := http.Get(url)
来源：http://dali.hammf.cn/Article/details/gt2zscdvsxr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sysykeji.top/Article/details/gt2mvogbaxc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.vqdsnc.cn/Article/details/gt2pexgijew.html

[L02] 发送 POST JSON
来源：http://dali.hysaishi.cn/Article/details/gt2jlkpmmga.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenjidiqi.icu/Article/details/gt2brymyoql.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.0kj1m.cn/Article/details/gt2kfqwrltv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.redwolf501.top/Article/details/gt2usqthhtt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ivvv.top/Article/details/gt2chrxbcei.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ivvv.top/Article/details/gt2crnvgokw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.daxiang520.top/Article/details/gt2rwcijyxl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.wangdashe.top/Article/details/gt2mrgiknus.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yonumen.top/Article/details/gt2dhudaxhn.html

[L03] 设置自定义请求头
来源：http://dali.redwolf501.top/Article/details/gt2jnwnzzbc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj20258888.top/Article/details/gt2dzoexvmp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.pycfn.com/Article/details/gt2ampkwlkh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tianlin.xyz/Article/details/gt2pfdyhjux.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuanzx.com/Article/details/gt2fscmlnqz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.pengpengdd.cyou/Article/details/gt2txumnaqw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.nanxuanxn.top/Article/details/gt2gelvsiob.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.meibo888.top/Article/details/gt2tnwruefu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tianlin.xyz/Article/details/gt2dbdetixf.html

[L04] 设置超时
来源：http://dali.zycfv.cn/Article/details/gt2zuuckvxv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jqgufenzy.top/Article/details/gt2mweyfqss.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgfzy.top/Article/details/gt2boqjpzlo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258.top/Article/details/gt2njrnguwr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tanke756.top/Article/details/gt2etangjfp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cucudq.cn/Article/details/gt2jgrprgnd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj20258888.top/Article/details/gt2usnuggyf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2klorejbn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sweek.top/Article/details/gt2avgxoakw.html

[L05] 上传文件（multipart）
来源：http://dali.hnxiangtu.top/Article/details/gt2yyntxsrv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ccqgeygv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.meibo888.top/Article/details/gt2mqjckdta.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hywenlv.cn/Article/details/gt2qttiaiig.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgufenzy.top/Article/details/gt2uwaxunnt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinqigufen.top/Article/details/gt2yliuzpsi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.0kj1m.cn/Article/details/gt2wtztrfoe.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.feifeiyinyue.top/Article/details/gt2cmeyajcv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2vqizzscm.html

[L06] 解析响应为 JSON
来源：http://dali.gotoacloud.top/Article/details/gt2fbtpfidi.html

Py:   resp.json()
来源：http://dali.c1oappe.top/Article/details/gt2gzxzpawl.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgtvbxx.html

JS:   await resp.json()
来源：http://dali.jinqigufen.top/Article/details/gt2ysjnghgz.html

TS:   await resp.json()
来源：http://dali.tian-w.cn/Article/details/gt2yldzbdle.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jyoumei.cn/Article/details/gt2ijfxyezs.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xziqi.cn/Article/details/gt2tpnlsqtr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ababzbxz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangdashe.top/Article/details/gt2paavtmho.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gt2lhphjtut.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.birdmap.top/Article/details/gt2lghlogez.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zdqjudy.top/Article/details/gt2knrsrkdg.html

JS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gt2tahkbbab.html

TS:   resp.ok;  resp.status
来源：http://dali.havefunace.top/Article/details/gt2knufwdoy.html

Java: resp.statusCode()
来源：http://dali.hfpthk.cn/Article/details/gt2rbrjilkd.html

Go:   resp.StatusCode
来源：http://dali.dashuyun.cn/Article/details/gt2njiyvzzi.html

Ruby: resp.code.to_i
来源：http://dali.dianchejie.cn/Article/details/gt2jffjyzic.html

C#:   (int)resp.StatusCode
来源：http://dali.yuanzhike.top/Article/details/gt2nkbskmgi.html

[L08] 并发请求多个地址
来源：http://dali.yj20258.top/Article/details/gt2qcoigthf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shangyingyoupin.top/Article/details/gt2mjjpidrf.html

PHP:  curl_multi_init() 系列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jplpaczu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gt2nnxoxspv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gt2mnflfqxm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuxming.cn/Article/details/gt2jmewwfuv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.birdmap.top/Article/details/gt2tcjoxnxe.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrochdw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.snrcjt.cn/Article/details/gt2zpvuezni.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2towfppbe.html

M. 命令行 / 进程 / 环境
来源：http://dali.gaohongyu789.top/Article/details/gt2qvjxhhmh.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2yxuhoyaf.html

[M01] 读取命令行参数
来源：http://dali.mhx1999.top/Article/details/gt2kpofaxlm.html

Py:   sys.argv[1:]
来源：http://dali.jinqigfzy.top/Article/details/gt2mqhuiryg.html

PHP:  $argv;  $argc;
来源：http://dali.ehwqpu.com/Article/details/gt2hbjqihdc.html

JS:   process.argv.slice(2)
来源：http://dali.kuanghao11.cn/Article/details/gt2rvjxlvjm.html

TS:   process.argv.slice(2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gopyiitg.html

Java: args 数组（main 方法参数）
来源：http://dali.feifeiyinyue.top/Article/details/gt2oqnyghhz.html

Go:   os.Args[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gt2pbmmaisl.html

Ruby: ARGV
来源：http://dali.yj20258888.top/Article/details/gt2pyfcujpt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gt2rkscogwz.html

[M02] 读取环境变量
来源：http://dali.ppjwa.cn/Article/details/gt2kzkpldiq.html

Py:   os.environ.get("HOME")
来源：http://dali.mhx1999.top/Article/details/gt2ksebvwof.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jyoumei.cn/Article/details/gt2lfjknrlo.html

JS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gt2jbfpsrmn.html

TS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gt2ubzovxld.html

Java: System.getenv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ffpcihll.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gt2unhtzbif.html

Ruby: ENV["HOME"]
来源：http://dali.guowangkeji.top/Article/details/gt2umrarcvj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gt2udrfhesq.html

[M03] 执行外部命令
来源：http://dali.smart0.xyz/Article/details/gt2ckpidijf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yuxming.cn/Article/details/gt2ebzxejzs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cqqwz.cn/Article/details/gt2uxsovjkh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yvedp.cn/Article/details/gt2dcsvubfn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2fdpqxpxx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shuidangran.top/Article/details/gt2depmatkv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zdqjudy.top/Article/details/gt2sjtoeadg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gogol.net.cn/Article/details/gt2gpifease.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hnxiangtu.top/Article/details/gt2cyskprqw.html

[M04] 获取当前工作目录
来源：http://dali.bjfxy.top/Article/details/gt2poivfogn.html

Py:   os.getcwd()
来源：http://dali.zycfv.cn/Article/details/gt2zfpsdtnp.html

PHP:  getcwd();
来源：http://dali.zhongyouzk.top/Article/details/gt2hlpsfaqt.html

JS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gt2thtyyzao.html

TS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gt2ejadzcrs.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qmjkturx.html

Go:   os.Getwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vkuclxul.html

Ruby: Dir.pwd
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rofzfbgj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zdqjudy.top/Article/details/gt2lfqrsykx.html

[M05] 设置退出码
来源：http://dali.chenlongwang.top/Article/details/gt2jwsadfkg.html

Py:   sys.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gt2qaheupka.html

PHP:  exit(1);
来源：http://dali.shzxlz.cn/Article/details/gt2uxulvxjb.html

JS:   process.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gt2qmjcgkrs.html

TS:   process.exit(1)
来源：http://dali.tian-w.cn/Article/details/gt2gfoxoopp.html

Java: System.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gt2qccxeqjv.html

Go:   os.Exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2mtixgyuv.html

Ruby: exit 1
来源：http://dali.mhx1999.top/Article/details/gt2claypgce.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kvvwiwig.html

[M06] 向标准错误输出
来源：http://dali.sxryk.cn/Article/details/gt2embcjcoa.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shzxlz.cn/Article/details/gt2umpdpgpp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hnxiangtu.top/Article/details/gt2cmkgphzw.html

JS:   console.error("err")
来源：http://dali.jyoumei.cn/Article/details/gt2qycdufvp.html

TS:   console.error("err")
来源：http://dali.c1oappe.top/Article/details/gt2phshcdxn.html

Java: System.err.println("err")
来源：http://dali.quarkkingdee.top/Article/details/gt2vaxkjmcz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cheryme.top/Article/details/gt2grmdsuhs.html

Ruby: warn "err"
来源：http://dali.yueranfly.top/Article/details/gt2ytvbvzce.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ybcxt.top/Article/details/gt2suwwqfli.html

[M07] 判断是否为主入口
来源：http://dali.meibo888.top/Article/details/gt2xqrrtsyo.html

Py:   if __name__ == "__main__":
来源：http://dali.jiagoushi.top/Article/details/gt2ytkgxoip.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jianghu66.top/Article/details/gt2jsionhbi.html

JS:   require.main === module
来源：http://dali.yanxiufei.cn/Article/details/gt2fckkvzsv.html

TS:   require.main === module
来源：http://dali.aizwys.cn/Article/details/gt2soxqqvhm.html

Java: public static void main(String[] args)
来源：http://dali.kuanghao11.cn/Article/details/gt2vsmirkyg.html

Go:   func main()
来源：http://dali.ydzc1.top/Article/details/gt2betppcwq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenzaomai.com/Article/details/gt2xsomuprj.html

C#:   static void Main(string[] args)
来源：http://dali.zhongyouzk.top/Article/details/gt2xfwxkdyv.html

[M08] 获取系统与运行时信息
来源：http://dali.kuanghao11.cn/Article/details/gt2yuidgzoz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.vqdsnc.cn/Article/details/gt2gngxrbzl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.svipenyu.cn/Article/details/gt2lhdcsjut.html

JS:   process.platform;  process.version
来源：http://dali.meibo888.top/Article/details/gt2hsexrmxm.html

TS:   process.platform;  process.version
来源：http://dali.nanxinkj.top/Article/details/gt2yhiwddck.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cheryme.top/Article/details/gt2wqdxshxv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cucudq.cn/Article/details/gt2cxqfuiuu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.svipenyu.cn/Article/details/gt2jaoeernh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sysykeji.top/Article/details/gt2akheakjo.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2txtorris.html

N. 数据结构与算法
来源：http://dali.cashguo.top/Article/details/gt2zziczkje.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2navnymci.html

[N01] 二分查找（有序数组）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rfotylug.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.daxiang520.top/Article/details/gt2ruuhreuu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.snrcjt.cn/Article/details/gt2viqfjeir.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fzhhl.top/Article/details/gt2tvhzcdll.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gvlktrvh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cashguo.top/Article/details/gt2sqxrosqc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2eijerrkq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj202588.top/Article/details/gt2lfcbtslo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cashguo.top/Article/details/gt2dsvhhzjd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.quarkkingdee.top/Article/details/gt2ihfmiamg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxuanxn.top/Article/details/gt2dcgalmyw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2htwdkezo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daria6918.cn/Article/details/gt2mmdexkzx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gt2uzpnnhnu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.redwolf501.top/Article/details/gt2duqqijwj.html

Go:   slices.Sort(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2efpwrkxb.html

Ruby: arr.sort
来源：http://dali.havefunace.top/Article/details/gt2iqkqmksz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.guowangkeji.top/Article/details/gt2giwndjly.html

[N03] 快速排序（分治示例）
来源：http://dali.zycfv.cn/Article/details/gt2dfbhsmku.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zycfv.cn/Article/details/gt2vzjpuhto.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xuetiantiany.cn/Article/details/gt2exndznmg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gt2owyitzip.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daxiang520.top/Article/details/gt2ovbovpze.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sxddokgb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258.top/Article/details/gt2sryabvem.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.0kj1m.cn/Article/details/gt2eqjfhezg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangdashe.top/Article/details/gt2qwxnztfs.html

[N04] 斐波那契数列
来源：http://dali.kuanghao11.cn/Article/details/gt2sfhgoabd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xxbmqvwu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gt2hhtunupj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gt2ozyefbgz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gt2yehpyxmc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zycfv.cn/Article/details/gt2czlcfgld.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nwbrower.top/Article/details/gt2fkckirhd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.c1oappe.top/Article/details/gt2kensoqzw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gt2ngkxpclr.html

[N05] 最大公约数
来源：http://dali.zycfv.cn/Article/details/gt2walnlhec.html

Py:   math.gcd(a, b)
来源：http://dali.tianlin.xyz/Article/details/gt2pngfiero.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zycfv.cn/Article/details/gt2focsfohd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangdashe.top/Article/details/gt2hulefrrd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jianghu66.top/Article/details/gt2niaxeghx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zdqjudy.top/Article/details/gt2tgfcgppx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zycfv.cn/Article/details/gt2dwnqsfmy.html

Ruby: a.gcd(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ktqachdy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuxming.cn/Article/details/gt2nfybcquo.html

[N06] 判断回文字符串
来源：http://dali.ybcxt.top/Article/details/gt2pqsyawjl.html

Py:   s == s[::-1]
来源：http://dali.dianchejie.cn/Article/details/gt2nnwbtouo.html

PHP:  $s === strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2iofmbjtk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2fzhdyjuk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gt2aeljegkd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jbtkcsgs.html

Go:   // 双指针从两端比较
来源：http://dali.cdnleiting.top/Article/details/gt2bopaedeg.html

Ruby: s == s.reverse
来源：http://dali.guannengcc.top/Article/details/gt2qqulvrfr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gt2hyjpsgmz.html

[N07] 两数之和（返回下标）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gfzsgtql.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zdqjudy.top/Article/details/gt2iyhdvyfe.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.fengsongda.top/Article/details/gt2usoeyykx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hnxiangtu.top/Article/details/gt2iqhjrhld.html

TS:   // 手写 Map<string, number>
来源：http://dali.aizwys.cn/Article/details/gt2btohclvv.html

Java: // 手写 HashMap
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yeynxhks.html

Go:   // 手写 map[int]int
来源：http://dali.xuanzx.com/Article/details/gt2vawgupcn.html

Ruby: // 手写 Hash
来源：http://dali.snrcjt.cn/Article/details/gt2mpvgvegk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shzxlz.cn/Article/details/gt2iisqthwr.html

[N08] 生成全排列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kaspdztt.html

Py:   itertools.permutations(arr)
来源：http://dali.hammf.cn/Article/details/gt2iuzxpssy.html

PHP:  // 手写递归交换
来源：http://dali.jlsjyb.cn/Article/details/gt2vrcmrohe.html

JS:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gt2maugxeoz.html

TS:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gt2emwzxopi.html

Java: // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2dalsmzgw.html

Go:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gt2mryghqoi.html

Ruby: arr.permutation.to_a
来源：http://dali.tianlin.xyz/Article/details/gt2oekdxmsi.html

C#:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gt2mxdshaxo.html

[N09] 栈与队列
来源：http://dali.daxiang520.top/Article/details/gt2odqjrbtp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hywenlv.cn/Article/details/gt2pfqcfkym.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gt2vlawnefy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.redwolf501.top/Article/details/gt2myrpjycl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2milhzgna.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenlongwang.top/Article/details/gt2uoyzjezg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vghnnsaz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gt2bwgndkox.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gogol.net.cn/Article/details/gt2tbjgyrrw.html

[N10] 链表节点定义
来源：http://dali.hammf.cn/Article/details/gt2lrvqonuj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.pengpengdd.cyou/Article/details/gt2dwtkkmiq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zycfv.cn/Article/details/gt2dltasayz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj202588.top/Article/details/gt2llrauwek.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sysykeji.top/Article/details/gt2xfmtxuvw.html

Java: class Node { int v; Node next; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2fjwxotep.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tian-w.cn/Article/details/gt2pnikagxo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.haohaochexian.top/Article/details/gt2kioobvmp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhongyouzk.top/Article/details/gt2olnynpeg.html

[N11] 二叉树中序遍历
来源：http://dali.nwbrower.top/Article/details/gt2pdkzjpci.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.316326.xyz/Article/details/gt2hsnrnoje.html

PHP:  // 手写递归函数
来源：http://dali.snrcjt.cn/Article/details/gt2woklfdxb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gt2hqdbpsee.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daria6918.cn/Article/details/gt2obvxznul.html

Java: // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gt2fcnnxpnv.html

Go:   // 手写递归
来源：http://dali.nanxuanxn.top/Article/details/gt2akcpkqru.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ehwqpu.com/Article/details/gt2vdnqbcwe.html

C#:   // 手写递归
来源：http://dali.sweek.top/Article/details/gt2cbbuuexp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.birdmap.top/Article/details/gt2kwjminks.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xylfe.cn/Article/details/gt2asloxgix.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ldgzjrti.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daria6918.cn/Article/details/gt2ruhvwjix.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tian-w.cn/Article/details/gt2lpauqgmz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jyoumei.cn/Article/details/gt2ekvunxrr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shzxlz.cn/Article/details/gt2sdmupona.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yongpay.top/Article/details/gt2wwndpipl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gt2iifrgtct.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ukasxkqf.html

O. 并发与异步
来源：http://dali.hywenlv.cn/Article/details/gt2hgxduqbf.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2mikiemff.html

[O01] 启动一个线程
来源：http://dali.nwbrower.top/Article/details/gt2osypmnfn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gzhubu.top/Article/details/gt2juexxqzl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.svipenyu.cn/Article/details/gt2vnogaumf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hywenlv.cn/Article/details/gt2pjzwnfpo.html

TS:   // 同 JS
来源：http://dali.jinqigfzy.top/Article/details/gt2olfgyzvh.html

Java: new Thread(() -> f()).start()
来源：http://dali.yuanzhike.top/Article/details/gt2vcdvwtot.html

Go:   go f()
来源：http://dali.wangdashe.top/Article/details/gt2ngkaiuja.html

Ruby: Thread.new { f }
来源：http://dali.jlsjyb.cn/Article/details/gt2yhawniwh.html

C#:   Task.Run(() => F());
来源：http://dali.zhoulong.xyz/Article/details/gt2iwizxdka.html

[O02] 使用线程池
来源：http://dali.jianghu66.top/Article/details/gt2fseryfif.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hnqzz.top/Article/details/gt2jipsanab.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.bjfxy.top/Article/details/gt2vxnfimek.html

JS:   // worker_threads 线程池
来源：http://dali.xuanzx.com/Article/details/gt2waoifmsc.html

TS:   // worker_threads 线程池
来源：http://dali.ivvv.top/Article/details/gt2chwtghpy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xxddxach.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cdnleiting.top/Article/details/gt2ploibsdh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xylfe.cn/Article/details/gt2hwxuqlcc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.kuanghao11.cn/Article/details/gt2dhafcznm.html

[O03] 加锁保护共享数据
来源：http://dali.sufxvd.cn/Article/details/gt2yxstosza.html

Py:   with lock: shared += 1
来源：http://dali.jinqigufen.top/Article/details/gt2xoefecnv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.andypj.xyz/Article/details/gt2sdxqqvzo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tianlin.xyz/Article/details/gt2iwyikgsn.html

TS:   // 同 JS
来源：http://dali.bjfxy.top/Article/details/gt2sudfrqfq.html

Java: synchronized (this) { shared++; }
来源：http://dali.xuanzx.com/Article/details/gt2nvwuucfj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenjidiqi.icu/Article/details/gt2pykntzdz.html


<!-- 参考信息 -->