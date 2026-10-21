代发 wailian999

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.wangshuangyany.cn/Article/details/gtccfqfmhv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdnkkkdjt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yvedp.cn/Article/details/gtamjaxgzg.html

Py:   pickle.dumps(obj)
来源：http://dali.yangfankeji.com/Article/details/gtlrqdqoog.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hnxiangtu.top/Article/details/gtaqwvoyfy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.havefunace.top/Article/details/gtrqufqkht.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzgmuffxc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sweek.top/Article/details/gtixtfowoq.html

Go:   encoding/gob
来源：http://dali.sweek.top/Article/details/gtvrytmkyv.html

Ruby: Marshal.dump(obj)
来源：http://dali.zdqjudy.top/Article/details/gtaurlvhsu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gtrixrxees.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtnkmievbg.html

L. 网络请求
来源：http://dali.gotoacloud.top/Article/details/gtgjpulydw.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtofpislng.html

[L01] 发送 GET 请求
来源：http://dali.wangshuangyany.cn/Article/details/gtnckikjuq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.316326.xyz/Article/details/gtqoxmxwga.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cucudq.cn/Article/details/gtiultqicw.html

JS:   await fetch(url)
来源：http://dali.hfpthk.cn/Article/details/gtpxkgwwka.html

TS:   await fetch(url)
来源：http://dali.hammf.cn/Article/details/gttklatjda.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sxryk.cn/Article/details/gtbeiwzegh.html

Go:   resp, err := http.Get(url)
来源：http://dali.yvedp.cn/Article/details/gtcyxirxqy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuupwrkgz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.mhx1999.top/Article/details/gtccbdxxuq.html

[L02] 发送 POST JSON
来源：http://dali.yuxming.cn/Article/details/gtswkahtei.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hnxiangtu.top/Article/details/gtycbnalal.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenjidiqi.icu/Article/details/gtdmyixvvk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtwwrndhjz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xziqi.cn/Article/details/gtbikxsugb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zycfv.cn/Article/details/gtsgkaxouz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shangyingyoupin.top/Article/details/gtyldfortq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.9152youxi.cn/Article/details/gtorhzfhxm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.fzhhl.top/Article/details/gtgzwdjbys.html

[L03] 设置自定义请求头
来源：http://dali.pycfn.com/Article/details/gtzgpxldaa.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zycfv.cn/Article/details/gtvyqenwoq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.havefunace.top/Article/details/gtnumicsng.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gtukasodhc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuanzx.com/Article/details/gtqjsovvvc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gtdombyutr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sufxvd.cn/Article/details/gtnsfdmaxg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tanke756.top/Article/details/gtdsjvwiex.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.meibo888.top/Article/details/gtlbomjnup.html

[L04] 设置超时
来源：http://dali.jqgufenzy.top/Article/details/gtbuskjyfe.html

Py:   requests.get(url, timeout=5)
来源：http://dali.vqdsnc.cn/Article/details/gtjcdlvwov.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xziqi.cn/Article/details/gtjeoowkke.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gtkajqouta.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenjidiqi.icu/Article/details/gtgalbgjyn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yvedp.cn/Article/details/gtebqaawgs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenjidiqi.icu/Article/details/gtppxzkexa.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhiwuduotai.top/Article/details/gtdccaklgs.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cashguo.top/Article/details/gtahnhhoxf.html

[L05] 上传文件（multipart）
来源：http://dali.guannengcc.top/Article/details/gtwzazkeyx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwdagcee.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sufxvd.cn/Article/details/gtbntlillz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cashguo.top/Article/details/gtqgksspdw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangshuangyany.cn/Article/details/gtdbmgabcv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gogol.net.cn/Article/details/gtzhkyqylx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.pengpengdd.cyou/Article/details/gtmbnwbori.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gzhubu.top/Article/details/gtihviwgms.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.birdmap.top/Article/details/gtodynebtd.html

[L06] 解析响应为 JSON
来源：http://dali.pengpengdd.cyou/Article/details/gtkfykicam.html

Py:   resp.json()
来源：http://dali.hysaishi.cn/Article/details/gtijvbhczl.html

PHP:  json_decode($body, true);
来源：http://dali.xinyue.icu/Article/details/gtezdjnwly.html

JS:   await resp.json()
来源：http://dali.9152youxi.cn/Article/details/gtnfmrjdzr.html

TS:   await resp.json()
来源：http://dali.jinqigufen.top/Article/details/gtbwqaqquz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzcbuwdns.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.316326.xyz/Article/details/gtrykntexa.html

Ruby: JSON.parse(resp.body)
来源：http://dali.havefunace.top/Article/details/gtmppymxrt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.guannengcc.top/Article/details/gtujwphmyr.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhengqikj.top/Article/details/gtckjhkczs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.mhx1999.top/Article/details/gtprdahujk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuzjhyktj.html

JS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gtwxqilypo.html

TS:   resp.ok;  resp.status
来源：http://dali.9152youxi.cn/Article/details/gtzxwzhoby.html

Java: resp.statusCode()
来源：http://dali.svipenyu.cn/Article/details/gtlvidiipn.html

Go:   resp.StatusCode
来源：http://dali.yj20258888.top/Article/details/gtneytqwod.html

Ruby: resp.code.to_i
来源：http://dali.nanxinkj.top/Article/details/gtlphxslcs.html

C#:   (int)resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gtlyvzbwky.html

[L08] 并发请求多个地址
来源：http://dali.0kj1m.cn/Article/details/gtbuuhztsr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.feifeiyinyue.top/Article/details/gtltrfhdbg.html

PHP:  curl_multi_init() 系列
来源：http://dali.quarkkingdee.top/Article/details/gtuspkadyu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aibaodan.cn/Article/details/gtivcqoxpt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gthmfngroe.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hywenlv.cn/Article/details/gtteowzpnj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nwbrower.top/Article/details/gtgnhhuhhx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.iojbl.cn/Article/details/gtuveolecm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jyoumei.cn/Article/details/gttedlukiv.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtfrdwrttb.html

M. 命令行 / 进程 / 环境
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgdpzejj.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtlhjisfod.html

[M01] 读取命令行参数
来源：http://dali.tianlin.xyz/Article/details/gtuqmcpoua.html

Py:   sys.argv[1:]
来源：http://dali.dianchejie.cn/Article/details/gtderllrgx.html

PHP:  $argv;  $argc;
来源：http://dali.xylfe.cn/Article/details/gtxthehllh.html

JS:   process.argv.slice(2)
来源：http://dali.chenlongwang.top/Article/details/gtjqbzdpza.html

TS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gtzswiwhem.html

Java: args 数组（main 方法参数）
来源：http://dali.sweek.top/Article/details/gtsnrbonod.html

Go:   os.Args[1:]
来源：http://dali.tianlin.xyz/Article/details/gtzpyksvre.html

Ruby: ARGV
来源：http://dali.xylfe.cn/Article/details/gtnbwfdozg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.iojbl.cn/Article/details/gtuqylqxmr.html

[M02] 读取环境变量
来源：http://dali.zhengqikj.top/Article/details/gtrwlhgixv.html

Py:   os.environ.get("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtkijgbwpe.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ppjwa.cn/Article/details/gtxfczqrtv.html

JS:   process.env.HOME
来源：http://dali.tanke756.top/Article/details/gttrpfmqbp.html

TS:   process.env.HOME
来源：http://dali.tianlin.xyz/Article/details/gtvmcoftyk.html

Java: System.getenv("HOME")
来源：http://dali.shuidangran.top/Article/details/gtdzikqjsi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zdqjudy.top/Article/details/gtdcfupjka.html

Ruby: ENV["HOME"]
来源：http://dali.pengpengdd.cyou/Article/details/gtbitdvsbt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yonumen.top/Article/details/gtjumpflia.html

[M03] 执行外部命令
来源：http://dali.nanxuanxn.top/Article/details/gtjqpcsvwv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwyijvtyx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpowisdfo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.c1oappe.top/Article/details/gtdgrzhyaf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hysaishi.cn/Article/details/gtgxxfodht.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yueranfly.top/Article/details/gtbxfdulkh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxinkj.top/Article/details/gtnktpmhrv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.pengpengdd.cyou/Article/details/gtsblwizgg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jqgufenzy.top/Article/details/gtstmwwutn.html

[M04] 获取当前工作目录
来源：http://dali.yj20258888.top/Article/details/gtvevstrvr.html

Py:   os.getcwd()
来源：http://dali.tianlin.xyz/Article/details/gtgrqsnpkq.html

PHP:  getcwd();
来源：http://dali.zhongyouzk.top/Article/details/gtufdhqqbq.html

JS:   process.cwd()
来源：http://dali.nanxuanxn.top/Article/details/gtrrqzsyig.html

TS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gtptsnsjfs.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xziqi.cn/Article/details/gtpiboutyd.html

Go:   os.Getwd()
来源：http://dali.cqqwz.cn/Article/details/gtmsfkxqoy.html

Ruby: Dir.pwd
来源：http://dali.guannengcc.top/Article/details/gtnuxnmwcv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.andypj.xyz/Article/details/gtedbggrac.html

[M05] 设置退出码
来源：http://dali.cqqwz.cn/Article/details/gtsduoygqy.html

Py:   sys.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtzrcsjcro.html

PHP:  exit(1);
来源：http://dali.cheryme.top/Article/details/gtexbemlty.html

JS:   process.exit(1)
来源：http://dali.ivvv.top/Article/details/gttodlafsj.html

TS:   process.exit(1)
来源：http://dali.yuxming.cn/Article/details/gtlrtflpxw.html

Java: System.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtolokifwc.html

Go:   os.Exit(1)
来源：http://dali.ydzc1.top/Article/details/gtxhjtxacn.html

Ruby: exit 1
来源：http://dali.zhixingplan.top/Article/details/gtyrnjtovb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cashguo.top/Article/details/gtuqdlorhy.html

[M06] 向标准错误输出
来源：http://dali.pengpengdd.cyou/Article/details/gtrptmmtkt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nwbrower.top/Article/details/gtibhituxh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aibaodan.cn/Article/details/gtuaqxuzhk.html

JS:   console.error("err")
来源：http://dali.c1oappe.top/Article/details/gtesgbhfwx.html

TS:   console.error("err")
来源：http://dali.xziqi.cn/Article/details/gtpzocqqbl.html

Java: System.err.println("err")
来源：http://dali.nanxuanxn.top/Article/details/gthnvqyybq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.mhx1999.top/Article/details/gtgeotbxzr.html

Ruby: warn "err"
来源：http://dali.316326.xyz/Article/details/gtssrjsyer.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ppjwa.cn/Article/details/gtikblhxef.html

[M07] 判断是否为主入口
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtvrnana.html

Py:   if __name__ == "__main__":
来源：http://dali.svipenyu.cn/Article/details/gtvgvyexzg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jyoumei.cn/Article/details/gthkyqkumq.html

JS:   require.main === module
来源：http://dali.sweek.top/Article/details/gtivsixuuc.html

TS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gtqtculxqt.html

Java: public static void main(String[] args)
来源：http://dali.snrcjt.cn/Article/details/gtxvkakzqw.html

Go:   func main()
来源：http://dali.meibo888.top/Article/details/gtrjcyvfba.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.redwolf501.top/Article/details/gtmddqutqa.html

C#:   static void Main(string[] args)
来源：http://dali.ehwqpu.com/Article/details/gtpfrnjskh.html

[M08] 获取系统与运行时信息
来源：http://dali.aibaodan.cn/Article/details/gtqbgrufyy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sufxvd.cn/Article/details/gthwuqcoqy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xuanzx.com/Article/details/gtrklpnien.html

JS:   process.platform;  process.version
来源：http://dali.pycfn.com/Article/details/gthhlynlfm.html

TS:   process.platform;  process.version
来源：http://dali.ydzc1.top/Article/details/gtbzjmpqbk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dianchejie.cn/Article/details/gtxviwyubp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.tianlin.xyz/Article/details/gtjvumdstg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.havefunace.top/Article/details/gtckuoiwot.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.wangshuangyany.cn/Article/details/gtsxfgqbru.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtijtueyxi.html

N. 数据结构与算法
来源：http://dali.haohaochexian.top/Article/details/gtvwmifzet.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtrniynvzo.html

[N01] 二分查找（有序数组）
来源：http://dali.daria6918.cn/Article/details/gtbwjozkbw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtshjimxfk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gtdfgnhrrd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.iojbl.cn/Article/details/gthvorharo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guannengcc.top/Article/details/gtninamuau.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gteigvtttn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gthufjejhe.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.andypj.xyz/Article/details/gttpkhrnzi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtlkyahbni.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gtzyonaull.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dashuyun.cn/Article/details/gtkewqwsto.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.haohaochexian.top/Article/details/gtniotuvwe.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gtcvtgjmim.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gtdjptdzub.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gtuphusioc.html

Go:   slices.Sort(arr)
来源：http://dali.shuidangran.top/Article/details/gtoglsizbd.html

Ruby: arr.sort
来源：http://dali.dashuyun.cn/Article/details/gtuliaabcg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shzxlz.cn/Article/details/gtyfulcqyp.html

[N03] 快速排序（分治示例）
来源：http://dali.aibaodan.cn/Article/details/gtajchzjxw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cheryme.top/Article/details/gtgsbomgsi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yueranfly.top/Article/details/gtokocvwhz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aibaodan.cn/Article/details/gttsdwlyct.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gogol.net.cn/Article/details/gtweadljqr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj20258888.top/Article/details/gtkjqdoymp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhiwuduotai.top/Article/details/gtyycmodtq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.0kj1m.cn/Article/details/gtuoctshfj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jyoumei.cn/Article/details/gtfqrdbaxl.html

[N04] 斐波那契数列
来源：http://dali.ivvv.top/Article/details/gtowjyqdlr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxuanxn.top/Article/details/gtlmtsamqy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gtoybaghyc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gtlfasnjeq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gtdvwtqeiq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.haohaochexian.top/Article/details/gtyxjhmaot.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hysaishi.cn/Article/details/gtizeedkui.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yuanzhike.top/Article/details/gthuiexshb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gtysyrgtmc.html

[N05] 最大公约数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghfnfeat.html

Py:   math.gcd(a, b)
来源：http://dali.guannengcc.top/Article/details/gtlnbtyprg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gtqcjuvbah.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.quarkkingdee.top/Article/details/gtysxgoxhz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tanke756.top/Article/details/gttjkgexyy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shuidangran.top/Article/details/gttyoczxeh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yuanzhike.top/Article/details/gtqvmgwgtk.html

Ruby: a.gcd(b)
来源：http://dali.cqqwz.cn/Article/details/gthuxyxnfx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.pengpengdd.cyou/Article/details/gtihxbjjjr.html

[N06] 判断回文字符串
来源：http://dali.cashguo.top/Article/details/gtvgtlypoq.html

Py:   s == s[::-1]
来源：http://dali.zdqjudy.top/Article/details/gtlvvilmmw.html

PHP:  $s === strrev($s);
来源：http://dali.jiagoushi.top/Article/details/gtsecsamxx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtkuduridh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtenanntfn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hfpthk.cn/Article/details/gtqiqnnayb.html

Go:   // 双指针从两端比较
来源：http://dali.fengsongda.top/Article/details/gtwnudqvxh.html

Ruby: s == s.reverse
来源：http://dali.bjfxy.top/Article/details/gtvteablpi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hnxiangtu.top/Article/details/gtwsqqeaaj.html

[N07] 两数之和（返回下标）
来源：http://dali.dianchejie.cn/Article/details/gtmtrojfkq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gtjqbtlpxd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.9152youxi.cn/Article/details/gtmjakcxds.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.birdmap.top/Article/details/gtzdmoegkb.html

TS:   // 手写 Map<string, number>
来源：http://dali.yongpay.top/Article/details/gtyqlatxhe.html

Java: // 手写 HashMap
来源：http://dali.gogol.net.cn/Article/details/gtduclvtdd.html

Go:   // 手写 map[int]int
来源：http://dali.dashuyun.cn/Article/details/gttneuxoyf.html

Ruby: // 手写 Hash
来源：http://dali.xziqi.cn/Article/details/gtltdlulmc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtequewint.html

[N08] 生成全排列
来源：http://dali.haohaochexian.top/Article/details/gtpagykpcv.html

Py:   itertools.permutations(arr)
来源：http://dali.wangdashe.top/Article/details/gtvnhtqjra.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gtwpggaegv.html

JS:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gtcekbcsvh.html

TS:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtssfzpwul.html

Java: // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtlynoozzw.html

Go:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtlugwzenf.html

Ruby: arr.permutation.to_a
来源：http://dali.jlsjyb.cn/Article/details/gtgrxuxtoa.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtgrevocwu.html

[N09] 栈与队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtvgckooqe.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinqigufen.top/Article/details/gtgzwvdogc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.daxiang520.top/Article/details/gtwaynnebk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.wangdashe.top/Article/details/gtrnrbcajg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gogol.net.cn/Article/details/gtbatxylwx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hammf.cn/Article/details/gtjjblbynm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfxbrwdz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.wangdashe.top/Article/details/gtogenrekv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.dianchejie.cn/Article/details/gtgmzxrbyh.html

[N10] 链表节点定义
来源：http://dali.jinghuilouyu.cn/Article/details/gtjlgoyjda.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ppjwa.cn/Article/details/gtenecwmho.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrgnhkxak.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ydzc1.top/Article/details/gtucsbmidq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dianchejie.cn/Article/details/gtqqlrriev.html

Java: class Node { int v; Node next; }
来源：http://dali.havefunace.top/Article/details/gtcayxxtyb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.pycfn.com/Article/details/gtenplrjsy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daria6918.cn/Article/details/gtipzbmicj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jyoumei.cn/Article/details/gtcsjwlfls.html

[N11] 二叉树中序遍历
来源：http://dali.yuxming.cn/Article/details/gtiwckdsog.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinqigufen.top/Article/details/gtkbyrlxwr.html

PHP:  // 手写递归函数
来源：http://dali.fzhhl.top/Article/details/gtdoghalut.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xylfe.cn/Article/details/gtleigjklm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yonumen.top/Article/details/gtqrylmulh.html

Java: // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gtacwrezgh.html

Go:   // 手写递归
来源：http://dali.fengsongda.top/Article/details/gtjlorpjfm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shuidangran.top/Article/details/gtnlreqrhj.html

C#:   // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gtfovvdipc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xylfe.cn/Article/details/gtkfvvvylu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zdqjudy.top/Article/details/gtaekbyrjw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cdnleiting.top/Article/details/gtqcgguewf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sxryk.cn/Article/details/gtievumflw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangdashe.top/Article/details/gthfaaqpcc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sxryk.cn/Article/details/gtvzmejkld.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.c1oappe.top/Article/details/gtcfcxcdap.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenjidiqi.icu/Article/details/gtrrjfghwd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cqqwz.cn/Article/details/gtkbjznbei.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtsjpcuyvf.html

O. 并发与异步
来源：http://dali.gotoacloud.top/Article/details/gtbhibvshr.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtpwrpgwcc.html

[O01] 启动一个线程
来源：http://dali.yvedp.cn/Article/details/gtjccmnrwm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sufxvd.cn/Article/details/gtyxrdphqi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xinyue.icu/Article/details/gtkrsknakb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nanxuanxn.top/Article/details/gtawqjzebe.html

TS:   // 同 JS
来源：http://dali.c1oappe.top/Article/details/gtrkvaqpef.html

Java: new Thread(() -> f()).start()
来源：http://dali.tian-w.cn/Article/details/gthjborquu.html

Go:   go f()
来源：http://dali.wangdashe.top/Article/details/gtugrjaruq.html

Ruby: Thread.new { f }
来源：http://dali.hysaishi.cn/Article/details/gtkyjxivtj.html

C#:   Task.Run(() => F());
来源：http://dali.nanxuanxn.top/Article/details/gtldsjeopb.html

[O02] 使用线程池
来源：http://dali.andypj.xyz/Article/details/gtmofngbvw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.fzhhl.top/Article/details/gtvjelejac.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.iojbl.cn/Article/details/gtnqmpkmxv.html

JS:   // worker_threads 线程池
来源：http://dali.jqgfzy.top/Article/details/gtprshxygq.html

TS:   // worker_threads 线程池
来源：http://dali.tian-w.cn/Article/details/gtlbnsdbmx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhengqikj.top/Article/details/gtenbciorl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cucudq.cn/Article/details/gtenoxrqdx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ppjwa.cn/Article/details/gtqgfbkawu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yanxiufei.cn/Article/details/gtfhiskbqh.html

[O03] 加锁保护共享数据
来源：http://dali.tianlin.xyz/Article/details/gtqdchafnt.html

Py:   with lock: shared += 1
来源：http://dali.jqgufenzy.top/Article/details/gtmyvrnxkn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.andypj.xyz/Article/details/gtdbvmjfoj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gaohongyu789.top/Article/details/gtvrnxxloy.html

TS:   // 同 JS
来源：http://dali.redwolf501.top/Article/details/gtunclxyot.html

Java: synchronized (this) { shared++; }
来源：http://dali.gotoacloud.top/Article/details/gtqmatooqe.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.c1oappe.top/Article/details/gttsuihvlp.html


<!-- 参考信息 -->