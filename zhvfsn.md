代发 wailian999

L. 网络请求
来源：http://dali.bjfxy.top/Article/details/gt2zvjqfbde.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2tcznrtei.html

[L01] 发送 GET 请求
来源：http://dali.zhengqikj.top/Article/details/gt2yequkcmz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jyoumei.cn/Article/details/gt2zjihcbwv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gogol.net.cn/Article/details/gt2gxvbcfgs.html

JS:   await fetch(url)
来源：http://dali.nanxuanxn.top/Article/details/gt2sbzbefkm.html

TS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gt2escjsjdx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zdqjudy.top/Article/details/gt2srtlesvt.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hvvfpuus.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yueranfly.top/Article/details/gt2uymvdjms.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhiwuduotai.top/Article/details/gt2slzunsvr.html

[L02] 发送 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gt2zyndnqaa.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhongyouzk.top/Article/details/gt2ypjxmrzu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yuxming.cn/Article/details/gt2bjfiwqtz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fzhhl.top/Article/details/gt2ydfhtpbf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gt2xbefqacs.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.havefunace.top/Article/details/gt2kwubwvto.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sxryk.cn/Article/details/gt2ccogwpkp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.bjfxy.top/Article/details/gt2dxjrenby.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jianghu66.top/Article/details/gt2vfquihns.html

[L03] 设置自定义请求头
来源：http://dali.guannengcc.top/Article/details/gt2oajbfpkj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.guowangkeji.top/Article/details/gt2uqhtpimr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.haohaochexian.top/Article/details/gt2zlngmniu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.kuanghao11.cn/Article/details/gt2encshqnm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guowangkeji.top/Article/details/gt2mxxadrun.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hywenlv.cn/Article/details/gt2hysolbrb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.c1oappe.top/Article/details/gt2iqugsbes.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jiagoushi.top/Article/details/gt2mthkveiq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gt2xbdincjm.html

[L04] 设置超时
来源：http://dali.316326.xyz/Article/details/gt2nweqvxlv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhixingplan.top/Article/details/gt2bvjsnutv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhengqikj.top/Article/details/gt2qohyjzac.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.andypj.xyz/Article/details/gt2lmltubhu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gt2ezlpttbx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ivvv.top/Article/details/gt2pcoaicrq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.andypj.xyz/Article/details/gt2zjfpmjac.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sysykeji.top/Article/details/gt2hvfnmhgw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ehwqpu.com/Article/details/gt2kzsywyfk.html

[L05] 上传文件（multipart）
来源：http://dali.yuanzhike.top/Article/details/gt2ijbiljfa.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jlsjyb.cn/Article/details/gt2gyzemqry.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hywenlv.cn/Article/details/gt2eauhbvds.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pycfn.com/Article/details/gt2banberhs.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hywenlv.cn/Article/details/gt2wyskfhvx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.snrcjt.cn/Article/details/gt2oaonxtro.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xuanzx.com/Article/details/gt2yddcqrrg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.guowangkeji.top/Article/details/gt2hvtsfizo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2gmzvspjf.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2trujnjru.html

Py:   resp.json()
来源：http://dali.hysaishi.cn/Article/details/gt2abuxxtpo.html

PHP:  json_decode($body, true);
来源：http://dali.bjfxy.top/Article/details/gt2ywbecldy.html

JS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gt2dwhdyrov.html

TS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gt2dnrxnybl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jyoumei.cn/Article/details/gt2xqobfjlm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qxljjjdp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tanke756.top/Article/details/gt2bhpwnqgd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.c1oappe.top/Article/details/gt2eslcnlgs.html

[L07] 处理 HTTP 状态码
来源：http://dali.jqgfzy.top/Article/details/gt2elgbairj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zdqjudy.top/Article/details/gt2rwzfuzka.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sxryk.cn/Article/details/gt2zbtkblap.html

JS:   resp.ok;  resp.status
来源：http://dali.yj20258.top/Article/details/gt2vroqfbff.html

TS:   resp.ok;  resp.status
来源：http://dali.cdnleiting.top/Article/details/gt2xgkbbqep.html

Java: resp.statusCode()
来源：http://dali.sufxvd.cn/Article/details/gt2lffvfupr.html

Go:   resp.StatusCode
来源：http://dali.sufxvd.cn/Article/details/gt2cupsvmfw.html

Ruby: resp.code.to_i
来源：http://dali.cashguo.top/Article/details/gt2iyccazru.html

C#:   (int)resp.StatusCode
来源：http://dali.svipenyu.cn/Article/details/gt2bkjwtvtv.html

[L08] 并发请求多个地址
来源：http://dali.ivvv.top/Article/details/gt2hqtsbdmp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2paynsjvl.html

PHP:  curl_multi_init() 系列
来源：http://dali.shangyingyoupin.top/Article/details/gt2dtlxvlfd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gt2rojaqrol.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gt2rcgfjgzs.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shuidangran.top/Article/details/gt2ijdhkiax.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.daria6918.cn/Article/details/gt2xohrsmxj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.0kj1m.cn/Article/details/gt2zapokois.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gt2wdwdyfes.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bucnrrbw.html

M. 命令行 / 进程 / 环境
来源：http://dali.sxryk.cn/Article/details/gt2omtpdlty.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2ymkbdjrc.html

[M01] 读取命令行参数
来源：http://dali.smart0.xyz/Article/details/gt2bhvzmmok.html

Py:   sys.argv[1:]
来源：http://dali.vqdsnc.cn/Article/details/gt2pcwybtdj.html

PHP:  $argv;  $argc;
来源：http://dali.sxryk.cn/Article/details/gt2rttldlxs.html

JS:   process.argv.slice(2)
来源：http://dali.daxiang520.top/Article/details/gt2quhrwtap.html

TS:   process.argv.slice(2)
来源：http://dali.iojbl.cn/Article/details/gt2jjebkguq.html

Java: args 数组（main 方法参数）
来源：http://dali.jlsjyb.cn/Article/details/gt2mlqdplli.html

Go:   os.Args[1:]
来源：http://dali.svipenyu.cn/Article/details/gt2pawailsn.html

Ruby: ARGV
来源：http://dali.ivvv.top/Article/details/gt2lwphofab.html

C#:   args 数组（Main 方法参数）
来源：http://dali.kuanghao11.cn/Article/details/gt2clpumjlf.html

[M02] 读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gt2splunjxr.html

Py:   os.environ.get("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ftbxzbjt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gt2iviezodv.html

JS:   process.env.HOME
来源：http://dali.cqqwz.cn/Article/details/gt2xeqceqzg.html

TS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gt2eubxexcu.html

Java: System.getenv("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gt2vgqcqivz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gt2tyegvmxm.html

Ruby: ENV["HOME"]
来源：http://dali.haohaochexian.top/Article/details/gt2irapxuff.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xuanzx.com/Article/details/gt2vjqevkge.html

[M03] 执行外部命令
来源：http://dali.hongshengwenyu.top/Article/details/gt2ggtepkre.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nanxuanxn.top/Article/details/gt2zhrhcwxn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shzxlz.cn/Article/details/gt2ntvrkyhc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gt2hzqlvpho.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gt2cdostjxc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hysaishi.cn/Article/details/gt2ogeojlnw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.birdmap.top/Article/details/gt2lndxpggi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.kuanghao11.cn/Article/details/gt2bohzlntz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangdashe.top/Article/details/gt2bscfefnk.html

[M04] 获取当前工作目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tjlfydfh.html

Py:   os.getcwd()
来源：http://dali.cdnleiting.top/Article/details/gt2ytxkvlkg.html

PHP:  getcwd();
来源：http://dali.yangfankeji.com/Article/details/gt2xqojydhh.html

JS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gt2rnpwmpuv.html

TS:   process.cwd()
来源：http://dali.yuxming.cn/Article/details/gt2olvkjyks.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sxryk.cn/Article/details/gt2epdppzly.html

Go:   os.Getwd()
来源：http://dali.ydzc1.top/Article/details/gt2olxexaqm.html

Ruby: Dir.pwd
来源：http://dali.zhiwuduotai.top/Article/details/gt2sojfqylv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenjidiqi.icu/Article/details/gt2vkpagrcd.html

[M05] 设置退出码
来源：http://dali.xuetiantiany.cn/Article/details/gt2xvuivawu.html

Py:   sys.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gt2vxdlogiw.html

PHP:  exit(1);
来源：http://dali.yj20258.top/Article/details/gt2ldxdonxs.html

JS:   process.exit(1)
来源：http://dali.xziqi.cn/Article/details/gt2kickmpap.html

TS:   process.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zgsofxzu.html

Java: System.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gt2jlmncers.html

Go:   os.Exit(1)
来源：http://dali.dianchejie.cn/Article/details/gt2khivklzq.html

Ruby: exit 1
来源：http://dali.yuxming.cn/Article/details/gt2dcnioicx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tianlin.xyz/Article/details/gt2ohfujktk.html

[M06] 向标准错误输出
来源：http://dali.xylfe.cn/Article/details/gt2wixtqxds.html

Py:   print("err", file=sys.stderr)
来源：http://dali.quarkkingdee.top/Article/details/gt2vrfeypvn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hnqzz.top/Article/details/gt2rvlhxrgh.html

JS:   console.error("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jfbkwjka.html

TS:   console.error("err")
来源：http://dali.yonumen.top/Article/details/gt2dbwzrdkj.html

Java: System.err.println("err")
来源：http://dali.nwbrower.top/Article/details/gt2nuxaozjj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hammf.cn/Article/details/gt2fapxijzk.html

Ruby: warn "err"
来源：http://dali.aizwys.cn/Article/details/gt2dwvznvvm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cheryme.top/Article/details/gt2ahlojuwl.html

[M07] 判断是否为主入口
来源：http://dali.yvedp.cn/Article/details/gt2pzjgkyoi.html

Py:   if __name__ == "__main__":
来源：http://dali.jianghu66.top/Article/details/gt2xafudccs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xylfe.cn/Article/details/gt2zvhtlcbx.html

JS:   require.main === module
来源：http://dali.316326.xyz/Article/details/gt2fqankaxr.html

TS:   require.main === module
来源：http://dali.xziqi.cn/Article/details/gt2rcypnmme.html

Java: public static void main(String[] args)
来源：http://dali.quarkkingdee.top/Article/details/gt2aszymavu.html

Go:   func main()
来源：http://dali.ivvv.top/Article/details/gt2qirmtjrl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jqgufenzy.top/Article/details/gt2tjeppued.html

C#:   static void Main(string[] args)
来源：http://dali.cucudq.cn/Article/details/gt2xvjwrwvz.html

[M08] 获取系统与运行时信息
来源：http://dali.xylfe.cn/Article/details/gt2iecgegoj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinqigufen.top/Article/details/gt2lvgwkyts.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhengqikj.top/Article/details/gt2hpxdwkjh.html

JS:   process.platform;  process.version
来源：http://dali.andypj.xyz/Article/details/gt2wfkdmftv.html

TS:   process.platform;  process.version
来源：http://dali.bjfxy.top/Article/details/gt2rztbjomb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nwbrower.top/Article/details/gt2rtcgvrdd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.daxiang520.top/Article/details/gt2mcjggtcg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nanxinkj.top/Article/details/gt2cvmtyufe.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.snrcjt.cn/Article/details/gt2spjgyldn.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2xgapmulu.html

N. 数据结构与算法
来源：http://dali.nwbrower.top/Article/details/gt2filvollg.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2fuvkxsiq.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigufen.top/Article/details/gt2bupccvwe.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wgbrorhg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.smart0.xyz/Article/details/gt2eoxsobrz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gt2xdnjyugm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuxming.cn/Article/details/gt2vzaoqbmt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gt2vgwycwib.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ecwlryvk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.316326.xyz/Article/details/gt2nnrgsiwi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gt2jiuiypqd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tian-w.cn/Article/details/gt2fjqlvkcm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.feifeiyinyue.top/Article/details/gt2rqzwfxwl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ttnhzqpq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guannengcc.top/Article/details/gt2epxsikqh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gt2jxujudxr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hysaishi.cn/Article/details/gt2tujaqqyr.html

Go:   slices.Sort(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2znnearui.html

Ruby: arr.sort
来源：http://dali.zdqjudy.top/Article/details/gt2fiugrdwa.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xziqi.cn/Article/details/gt2biiwxlig.html

[N03] 快速排序（分治示例）
来源：http://dali.shuidangran.top/Article/details/gt2ljfsccsa.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.0kj1m.cn/Article/details/gt2jflflriy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nanxinkj.top/Article/details/gt2tbglvgvl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgufenzy.top/Article/details/gt2ldivpvbw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangshuangyany.cn/Article/details/gt2bvmogidg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.dashuyun.cn/Article/details/gt2cvcwuike.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jyoumei.cn/Article/details/gt2kpyitkkh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.dashuyun.cn/Article/details/gt2gacuzsts.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigfzy.top/Article/details/gt2kadhcppi.html

[N04] 斐波那契数列
来源：http://dali.gzhubu.top/Article/details/gt2jzuoqngc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2skebnwfi.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gt2uqkdveqc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sweek.top/Article/details/gt2ieubmnzl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gt2ybaivciw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jlsjyb.cn/Article/details/gt2rttidequ.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jqgufenzy.top/Article/details/gt2hqwbvknt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2xtulalqy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gt2dylaeikh.html

[N05] 最大公约数
来源：http://dali.mhx1999.top/Article/details/gt2iedqmvuv.html

Py:   math.gcd(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2frbdpuxc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.vqdsnc.cn/Article/details/gt2gmunlyhi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.birdmap.top/Article/details/gt2xwmzfbeh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yonumen.top/Article/details/gt2xbgjnwvb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guannengcc.top/Article/details/gt2yutukrrn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xuanzx.com/Article/details/gt2txntbppj.html

Ruby: a.gcd(b)
来源：http://dali.0kj1m.cn/Article/details/gt2isnxplid.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.dashuyun.cn/Article/details/gt2ndbobqch.html

[N06] 判断回文字符串
来源：http://dali.havefunace.top/Article/details/gt2dfgqvbtj.html

Py:   s == s[::-1]
来源：http://dali.snrcjt.cn/Article/details/gt2nlmasnpk.html

PHP:  $s === strrev($s);
来源：http://dali.chenlongwang.top/Article/details/gt2klssozsz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gt2iulqofau.html

TS:   s === [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gt2xakylivt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.vqdsnc.cn/Article/details/gt2iljsvcxf.html

Go:   // 双指针从两端比较
来源：http://dali.shuidangran.top/Article/details/gt2hjzxuorw.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqwgrea.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.dashuyun.cn/Article/details/gt2ckpikmlj.html

[N07] 两数之和（返回下标）
来源：http://dali.wangshuangyany.cn/Article/details/gt2ukuzdjvt.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hammf.cn/Article/details/gt2cqrwhkor.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.kuanghao11.cn/Article/details/gt2rseskqfw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhengqikj.top/Article/details/gt2odrmgrez.html

TS:   // 手写 Map<string, number>
来源：http://dali.nanxinkj.top/Article/details/gt2goysbdep.html

Java: // 手写 HashMap
来源：http://dali.ivvv.top/Article/details/gt2kobcbluu.html

Go:   // 手写 map[int]int
来源：http://dali.hammf.cn/Article/details/gt2ttmmfgwg.html

Ruby: // 手写 Hash
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ghmaiqgy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.9152youxi.cn/Article/details/gt2fqvwciej.html

[N08] 生成全排列
来源：http://dali.shzxlz.cn/Article/details/gt2pfrlhgdb.html

Py:   itertools.permutations(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2bbeibdpo.html

PHP:  // 手写递归交换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xxkbzxju.html

JS:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gt2ukojpfaf.html

TS:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gt2bfhibgfa.html

Java: // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gt2lotgtzcn.html

Go:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gt2mjbepyhz.html

Ruby: arr.permutation.to_a
来源：http://dali.birdmap.top/Article/details/gt2whkwwowh.html

C#:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2stpiqyag.html

[N09] 栈与队列
来源：http://dali.shuidangran.top/Article/details/gt2ryuunakt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinqigufen.top/Article/details/gt2jnxfupmc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tanke756.top/Article/details/gt2ppnxthta.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cheryme.top/Article/details/gt2stdgupwi.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.c1oappe.top/Article/details/gt2ntbwzpsh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yuxming.cn/Article/details/gt2dsogljck.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jianghu66.top/Article/details/gt2amsatbnj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gt2klwlyxbt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jyoumei.cn/Article/details/gt2cmaisprx.html

[N10] 链表节点定义
来源：http://dali.gotoacloud.top/Article/details/gt2yglaephx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hywenlv.cn/Article/details/gt2rqopvdlm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.fzhhl.top/Article/details/gt2tfpvmkws.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj20258888.top/Article/details/gt2lmqidbnk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.pengpengdd.cyou/Article/details/gt2kdplvsij.html

Java: class Node { int v; Node next; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ndvvbbzl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tsrbnoec.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ydzc1.top/Article/details/gt2lttkgxwz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.wangdashe.top/Article/details/gt2wnbtxtwm.html

[N11] 二叉树中序遍历
来源：http://dali.iojbl.cn/Article/details/gt2sjolguiy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbzwkkt.html

PHP:  // 手写递归函数
来源：http://dali.snrcjt.cn/Article/details/gt2svdyhztw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258.top/Article/details/gt2kixnaegz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gaohongyu789.top/Article/details/gt2uyatikhi.html

Java: // 手写递归
来源：http://dali.nanxuanxn.top/Article/details/gt2jvjjfbep.html

Go:   // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gt2kepiekho.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.fengsongda.top/Article/details/gt2gwqogpgm.html

C#:   // 手写递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2wpqkfify.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhixingplan.top/Article/details/gt2woptcinl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jyoumei.cn/Article/details/gt2bebcllgm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.tianlin.xyz/Article/details/gt2tdzinjmu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hfpthk.cn/Article/details/gt2lkauudgj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gzhubu.top/Article/details/gt2dmtleiig.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jpqzwjxf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.tian-w.cn/Article/details/gt2kcuhlvxi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ybcxt.top/Article/details/gt2tvamkevt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nwbrower.top/Article/details/gt2vkohsssb.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2leiqygow.html

O. 并发与异步
来源：http://dali.xziqi.cn/Article/details/gt2vpjunmrt.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2hsnvamyv.html

[O01] 启动一个线程
来源：http://dali.hnxiangtu.top/Article/details/gt2mglcyhhx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yangfankeji.com/Article/details/gt2wywfkdxj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gogol.net.cn/Article/details/gt2onvmqtjn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hzbzsprf.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gt2wfjhbprw.html

Java: new Thread(() -> f()).start()
来源：http://dali.daria6918.cn/Article/details/gt2dhcxtcmw.html

Go:   go f()
来源：http://dali.smart0.xyz/Article/details/gt2ixlxkwpy.html

Ruby: Thread.new { f }
来源：http://dali.nanxinkj.top/Article/details/gt2dlznrqkh.html

C#:   Task.Run(() => F());
来源：http://dali.hysaishi.cn/Article/details/gt2uanfyxhx.html

[O02] 使用线程池
来源：http://dali.zhengqikj.top/Article/details/gt2giooitxi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tian-w.cn/Article/details/gt2zbtkferf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gaohongyu789.top/Article/details/gt2erllnflv.html

JS:   // worker_threads 线程池
来源：http://dali.jianghu66.top/Article/details/gt2bxsxisvt.html

TS:   // worker_threads 线程池
来源：http://dali.gzhubu.top/Article/details/gt2lrmsaotc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.andypj.xyz/Article/details/gt2jqhqqion.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.birdmap.top/Article/details/gt2mpankjvi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.pycfn.com/Article/details/gt2vvxubifb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gaohongyu789.top/Article/details/gt2bdmtlpwf.html

[O03] 加锁保护共享数据
来源：http://dali.pycfn.com/Article/details/gt2dsmutzyu.html

Py:   with lock: shared += 1
来源：http://dali.nanxinkj.top/Article/details/gt2elzzzknp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xziqi.cn/Article/details/gt2lmtwlykk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hnqzz.top/Article/details/gt2dyoyymxw.html

TS:   // 同 JS
来源：http://dali.gaohongyu789.top/Article/details/gt2gfhdinlb.html

Java: synchronized (this) { shared++; }
来源：http://dali.c1oappe.top/Article/details/gt2dhijodkq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.c1oappe.top/Article/details/gt2lwovfukl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hfpthk.cn/Article/details/gt2ikqfbdtf.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj20258888.top/Article/details/gt2nyqiafji.html

[O04] 定义异步函数并等待
来源：http://dali.fzhhl.top/Article/details/gt2bpfznpur.html

Py:   async def f():⏎    await g()
来源：http://dali.tian-w.cn/Article/details/gt2ixseqrms.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jianghu66.top/Article/details/gt2drdfzfku.html

JS:   async function f() { await g(); }
来源：http://dali.xuanzx.com/Article/details/gt2zsxvmsjt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nanxinkj.top/Article/details/gt2ztnvuydk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ehwqpu.com/Article/details/gt2cnixcuzs.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jqgufenzy.top/Article/details/gt2etqhopje.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.fengsongda.top/Article/details/gt2rarmvqsh.html

C#:   async Task F() { await G(); }
来源：http://dali.havefunace.top/Article/details/gt2uzkjbbnf.html

[O05] 并发执行并等待全部完成
来源：http://dali.hnqzz.top/Article/details/gt2wtgirsfd.html


<!-- 参考信息 -->