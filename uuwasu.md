代发 wailian999

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.svipenyu.cn/Article/details/gt2auyugsmt.html

JS:   await fetch(url)
来源：http://dali.nanxinkj.top/Article/details/gt2rhuzktbm.html

TS:   await fetch(url)
来源：http://dali.yvedp.cn/Article/details/gt2fairdmty.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tian-w.cn/Article/details/gt2ewjvbwhq.html

Go:   resp, err := http.Get(url)
来源：http://dali.hnxiangtu.top/Article/details/gt2veoxiicn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tian-w.cn/Article/details/gt2gruuccky.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yanxiufei.cn/Article/details/gt2orvwjgyg.html

[L02] 发送 POST JSON
来源：http://dali.xinyue.icu/Article/details/gt2ujdeaxdz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gt2djtpkrcx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.havefunace.top/Article/details/gt2modqdruw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnxiangtu.top/Article/details/gt2yvqdbeuw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mfmmgtrj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tian-w.cn/Article/details/gt2temrrlkn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.9152youxi.cn/Article/details/gt2nsjppchk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ppjwa.cn/Article/details/gt2qdwphmhj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yuxming.cn/Article/details/gt2jeqvirvn.html

[L03] 设置自定义请求头
来源：http://dali.ppjwa.cn/Article/details/gt2cjdqwmaf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.aibaodan.cn/Article/details/gt2zwfpzqol.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.kuanghao11.cn/Article/details/gt2khmjcjos.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnqzz.top/Article/details/gt2hesqstab.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.9152youxi.cn/Article/details/gt2cizhdolm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yanxiufei.cn/Article/details/gt2mvhbqfwp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cucudq.cn/Article/details/gt2ejcidhik.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.0kj1m.cn/Article/details/gt2itrrrphf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hfpthk.cn/Article/details/gt2hkewmcqj.html

[L04] 设置超时
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tqudofcj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sufxvd.cn/Article/details/gt2eoltkqld.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuetiantiany.cn/Article/details/gt2hhsjhtdf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gaohongyu789.top/Article/details/gt2idqfbkpa.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.snrcjt.cn/Article/details/gt2disoiyen.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.snrcjt.cn/Article/details/gt2lpzdaelk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ydzc1.top/Article/details/gt2aplnapzv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hywenlv.cn/Article/details/gt2thnftlmt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daria6918.cn/Article/details/gt2ppwemviz.html

[L05] 上传文件（multipart）
来源：http://dali.gotoacloud.top/Article/details/gt2nuuhastz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yuanzhike.top/Article/details/gt2mnwalesf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.quarkkingdee.top/Article/details/gt2nskoyiqr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gotoacloud.top/Article/details/gt2lizolknl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gt2ozxvwsgn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sysykeji.top/Article/details/gt2hljyvqxa.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xuanzx.com/Article/details/gt2rukjnsgf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yangfankeji.com/Article/details/gt2bbvzjpug.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2ccospuzm.html

[L06] 解析响应为 JSON
来源：http://dali.quarkkingdee.top/Article/details/gt2boqvrgxh.html

Py:   resp.json()
来源：http://dali.cdnleiting.top/Article/details/gt2zyxhztrk.html

PHP:  json_decode($body, true);
来源：http://dali.aizwys.cn/Article/details/gt2hksnjlcd.html

JS:   await resp.json()
来源：http://dali.jyoumei.cn/Article/details/gt2wthnfiyh.html

TS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gt2rkwgetzo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gt2tswsfnfp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenlongwang.top/Article/details/gt2mulgguqr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rzfqufgj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.meibo888.top/Article/details/gt2kvivqoix.html

[L07] 处理 HTTP 状态码
来源：http://dali.yangfankeji.com/Article/details/gt2goayaxyh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj202588.top/Article/details/gt2dgpgqivl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cucudq.cn/Article/details/gt2ntqyzzrw.html

JS:   resp.ok;  resp.status
来源：http://dali.chenjidiqi.icu/Article/details/gt2vhenqjgb.html

TS:   resp.ok;  resp.status
来源：http://dali.yvedp.cn/Article/details/gt2jvijtddp.html

Java: resp.statusCode()
来源：http://dali.zdqjudy.top/Article/details/gt2adqufvyy.html

Go:   resp.StatusCode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fesnmrlr.html

Ruby: resp.code.to_i
来源：http://dali.gzhubu.top/Article/details/gt2khkerlno.html

C#:   (int)resp.StatusCode
来源：http://dali.guowangkeji.top/Article/details/gt2sayvukyb.html

[L08] 并发请求多个地址
来源：http://dali.feifeiyinyue.top/Article/details/gt2ooehmbeu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.aizwys.cn/Article/details/gt2kghlxduz.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj202588.top/Article/details/gt2sjwtkizr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guannengcc.top/Article/details/gt2ewmctepo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gt2ggtuszjg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tanke756.top/Article/details/gt2fzjebsby.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigfzy.top/Article/details/gt2vmgkvkjc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhixingplan.top/Article/details/gt2ajzdcgpp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hammf.cn/Article/details/gt2rvdekkmh.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2aetsvcun.html

M. 命令行 / 进程 / 环境
来源：http://dali.gogol.net.cn/Article/details/gt2ndrdsodr.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2hgagpkhd.html

[M01] 读取命令行参数
来源：http://dali.sufxvd.cn/Article/details/gt2ttznayqm.html

Py:   sys.argv[1:]
来源：http://dali.aibaodan.cn/Article/details/gt2dhpbgkdr.html

PHP:  $argv;  $argc;
来源：http://dali.sxryk.cn/Article/details/gt2kfsdhsfj.html

JS:   process.argv.slice(2)
来源：http://dali.cashguo.top/Article/details/gt2ynsqhtej.html

TS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gt2jydqgkxa.html

Java: args 数组（main 方法参数）
来源：http://dali.hongshengwenyu.top/Article/details/gt2ubbygqrn.html

Go:   os.Args[1:]
来源：http://dali.daria6918.cn/Article/details/gt2qcfaddld.html

Ruby: ARGV
来源：http://dali.zhiwuduotai.top/Article/details/gt2grujxwxt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.c1oappe.top/Article/details/gt2yeezqmyf.html

[M02] 读取环境变量
来源：http://dali.chenlongwang.top/Article/details/gt2dcwwhzcm.html

Py:   os.environ.get("HOME")
来源：http://dali.sxryk.cn/Article/details/gt2jvrnqdde.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gt2hsjruqal.html

JS:   process.env.HOME
来源：http://dali.meibo888.top/Article/details/gt2zgeihnto.html

TS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gt2gzibmzxb.html

Java: System.getenv("HOME")
来源：http://dali.tianlin.xyz/Article/details/gt2vimaypnr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.316326.xyz/Article/details/gt2tvnemhlz.html

Ruby: ENV["HOME"]
来源：http://dali.nwbrower.top/Article/details/gt2wxinvyal.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nanxinkj.top/Article/details/gt2vcmabdmj.html

[M03] 执行外部命令
来源：http://dali.hongshengwenyu.top/Article/details/gt2tlnchbuv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uyeelold.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guowangkeji.top/Article/details/gt2zjsskket.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shzxlz.cn/Article/details/gt2fpjgozag.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hysaishi.cn/Article/details/gt2xseuzezj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.9152youxi.cn/Article/details/gt2bpzyaorj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ppjwa.cn/Article/details/gt2sacfsvsd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhongyouzk.top/Article/details/gt2ridzejbw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shuidangran.top/Article/details/gt2azgilppa.html

[M04] 获取当前工作目录
来源：http://dali.redwolf501.top/Article/details/gt2infsvmhm.html

Py:   os.getcwd()
来源：http://dali.hfpthk.cn/Article/details/gt2lfsaoenx.html

PHP:  getcwd();
来源：http://dali.hnqzz.top/Article/details/gt2nxlgeqnr.html

JS:   process.cwd()
来源：http://dali.hongshengwenyu.top/Article/details/gt2dxndtloj.html

TS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gt2ufygbxfn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.snrcjt.cn/Article/details/gt2kjnaucxh.html

Go:   os.Getwd()
来源：http://dali.svipenyu.cn/Article/details/gt2gcmuscsk.html

Ruby: Dir.pwd
来源：http://dali.zdqjudy.top/Article/details/gt2xpznnluf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jqgufenzy.top/Article/details/gt2elahskpu.html

[M05] 设置退出码
来源：http://dali.xylfe.cn/Article/details/gt2trqigjaz.html

Py:   sys.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gt2wsersmxr.html

PHP:  exit(1);
来源：http://dali.hysaishi.cn/Article/details/gt2japklrvc.html

JS:   process.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lafshqng.html

TS:   process.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2iqkqqfay.html

Java: System.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gt2cngttpmx.html

Go:   os.Exit(1)
来源：http://dali.meibo888.top/Article/details/gt2enlbzsdp.html

Ruby: exit 1
来源：http://dali.yj20258.top/Article/details/gt2scmvaosh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hnqzz.top/Article/details/gt2ojpzvvfu.html

[M06] 向标准错误输出
来源：http://dali.gogol.net.cn/Article/details/gt2phczmwra.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgufenzy.top/Article/details/gt2rymmqkjt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shangyingyoupin.top/Article/details/gt2gsoblcmj.html

JS:   console.error("err")
来源：http://dali.hfpthk.cn/Article/details/gt2jxcbmlut.html

TS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2dfjlhhjj.html

Java: System.err.println("err")
来源：http://dali.0kj1m.cn/Article/details/gt2wvqmfrtn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cashguo.top/Article/details/gt2optfisiy.html

Ruby: warn "err"
来源：http://dali.tian-w.cn/Article/details/gt2uswxbyii.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.haohaochexian.top/Article/details/gt2gectfqat.html

[M07] 判断是否为主入口
来源：http://dali.feifeiyinyue.top/Article/details/gt2ladfetco.html

Py:   if __name__ == "__main__":
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lakceadz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxinkj.top/Article/details/gt2zqyeecxi.html

JS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gt2pjrvrevg.html

TS:   require.main === module
来源：http://dali.xuanzx.com/Article/details/gt2tlojaqdd.html

Java: public static void main(String[] args)
来源：http://dali.shuidangran.top/Article/details/gt2mmuaujwp.html

Go:   func main()
来源：http://dali.0kj1m.cn/Article/details/gt2oauvyzvj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guannengcc.top/Article/details/gt2ftspslbl.html

C#:   static void Main(string[] args)
来源：http://dali.shzxlz.cn/Article/details/gt2ifgxvpjk.html

[M08] 获取系统与运行时信息
来源：http://dali.wangshuangyany.cn/Article/details/gt2tpcyiwmr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yanxiufei.cn/Article/details/gt2sdepaskh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.bjfxy.top/Article/details/gt2pucgsynr.html

JS:   process.platform;  process.version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ptcywzub.html

TS:   process.platform;  process.version
来源：http://dali.zdqjudy.top/Article/details/gt2jgtgycaw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenjidiqi.icu/Article/details/gt2oarzrllj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj20258.top/Article/details/gt2dwupivbs.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hnxiangtu.top/Article/details/gt2vwjgguum.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nanxuanxn.top/Article/details/gt2bdjvwwot.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2yvszriru.html

N. 数据结构与算法
来源：http://dali.smart0.xyz/Article/details/gt2nfpieadp.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2bkdnwhov.html

[N01] 二分查找（有序数组）
来源：http://dali.pycfn.com/Article/details/gt2jduccrqy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2ibertvnz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gt2srnbpvfd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gt2fbfvpbcb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gt2dtawrvvy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gsmbmwyd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gt2txtqxivf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vthtaoxr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.redwolf501.top/Article/details/gt2vtvimnou.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hysaishi.cn/Article/details/gt2rwyzztdw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aizwys.cn/Article/details/gt2ddcjfvgh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.vqdsnc.cn/Article/details/gt2wngzzvxv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gt2wdoaaanc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zlshppqj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.pycfn.com/Article/details/gt2kgjebvpn.html

Go:   slices.Sort(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2uthwfcpb.html

Ruby: arr.sort
来源：http://dali.xuanzx.com/Article/details/gt2acetyyxs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gaohongyu789.top/Article/details/gt2dfvbvaqi.html

[N03] 快速排序（分治示例）
来源：http://dali.redwolf501.top/Article/details/gt2vttgqwqd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhongyouzk.top/Article/details/gt2rxwqfwft.html

PHP:  // 递归实现，或用 usort
来源：http://dali.0kj1m.cn/Article/details/gt2xlcxqqkt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gt2zqrumqbo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yangfankeji.com/Article/details/gt2lddgwjpy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.iojbl.cn/Article/details/gt2lvzhthqw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.snrcjt.cn/Article/details/gt2syxuesqh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cucudq.cn/Article/details/gt2pwjdlcdu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.redwolf501.top/Article/details/gt2yfbodkqi.html

[N04] 斐波那契数列
来源：http://dali.wangshuangyany.cn/Article/details/gt2btymryli.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenzaomai.com/Article/details/gt2dqfikfqx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yvedp.cn/Article/details/gt2kdzbtmyb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gt2kpufblay.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gt2mtgoaiya.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wneqpoou.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.dianchejie.cn/Article/details/gt2mwlipsau.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tianlin.xyz/Article/details/gt2iflxildy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gt2atejtuez.html

[N05] 最大公约数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jnepygni.html

Py:   math.gcd(a, b)
来源：http://dali.yj20258888.top/Article/details/gt2yqmzxbgo.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yanxiufei.cn/Article/details/gt2tvozgjkv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gt2rlgbytef.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.havefunace.top/Article/details/gt2eaxecedp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.316326.xyz/Article/details/gt2oqcrwnsj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xuetiantiany.cn/Article/details/gt2isdhveql.html

Ruby: a.gcd(b)
来源：http://dali.ydzc1.top/Article/details/gt2kzuxhepk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cucudq.cn/Article/details/gt2eypkihkr.html

[N06] 判断回文字符串
来源：http://dali.zdqjudy.top/Article/details/gt2jrkmsbov.html

Py:   s == s[::-1]
来源：http://dali.svipenyu.cn/Article/details/gt2kwbftqlr.html

PHP:  $s === strrev($s);
来源：http://dali.yangfankeji.com/Article/details/gt2pectzsdv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gt2chrozhaq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gt2qivllpar.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hywenlv.cn/Article/details/gt2bjlavevi.html

Go:   // 双指针从两端比较
来源：http://dali.zhoulong.xyz/Article/details/gt2kocizfng.html

Ruby: s == s.reverse
来源：http://dali.daria6918.cn/Article/details/gt2zgteazou.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zycfv.cn/Article/details/gt2etcbdxzf.html

[N07] 两数之和（返回下标）
来源：http://dali.haohaochexian.top/Article/details/gt2hwpyzpuf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xinyue.icu/Article/details/gt2qklpmtxa.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2emmallpx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ppjwa.cn/Article/details/gt2uzfcltga.html

TS:   // 手写 Map<string, number>
来源：http://dali.gaohongyu789.top/Article/details/gt2cpxrqujn.html

Java: // 手写 HashMap
来源：http://dali.yueranfly.top/Article/details/gt2btgmncec.html

Go:   // 手写 map[int]int
来源：http://dali.zycfv.cn/Article/details/gt2vpieklnq.html

Ruby: // 手写 Hash
来源：http://dali.hammf.cn/Article/details/gt2rjetfxua.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hongshengwenyu.top/Article/details/gt2bvvymija.html

[N08] 生成全排列
来源：http://dali.yonumen.top/Article/details/gt2hnyuaqbb.html

Py:   itertools.permutations(arr)
来源：http://dali.yueranfly.top/Article/details/gt2jinvdtrh.html

PHP:  // 手写递归交换
来源：http://dali.nanxinkj.top/Article/details/gt2eqciiqze.html

JS:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gt2jllsyucz.html

TS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gt2lcjqfhrp.html

Java: // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gt2wdbpdqwv.html

Go:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gt2ieqcunpy.html

Ruby: arr.permutation.to_a
来源：http://dali.wangshuangyany.cn/Article/details/gt2zlwtgstk.html

C#:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gt2aszoqjln.html

[N09] 栈与队列
来源：http://dali.yvedp.cn/Article/details/gt2vpgkmwpz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.mhx1999.top/Article/details/gt2hvkoeedv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2wgruzvnd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.aizwys.cn/Article/details/gt2tlmiphyy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.quarkkingdee.top/Article/details/gt2ntqukklr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xinyue.icu/Article/details/gt2qcmoknht.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenjidiqi.icu/Article/details/gt2gaxtzdfb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj20258888.top/Article/details/gt2iknlmqii.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yongpay.top/Article/details/gt2tfcdfaqb.html

[N10] 链表节点定义
来源：http://dali.zhixingplan.top/Article/details/gt2dodougzx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.smart0.xyz/Article/details/gt2yaltrkkx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.guannengcc.top/Article/details/gt2bltsdifs.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhongyouzk.top/Article/details/gt2jgocmggz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xuanzx.com/Article/details/gt2ojvsainn.html

Java: class Node { int v; Node next; }
来源：http://dali.316326.xyz/Article/details/gt2ljsjjlei.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jqgfzy.top/Article/details/gt2ulvahoyp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tian-w.cn/Article/details/gt2jaklohcd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odsfpnpg.html

[N11] 二叉树中序遍历
来源：http://dali.ehwqpu.com/Article/details/gt2mgkkvnfm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.daxiang520.top/Article/details/gt2pkdcifcp.html

PHP:  // 手写递归函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2relsyqpe.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258.top/Article/details/gt2yiauemhm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zdqjudy.top/Article/details/gt2kgeeylax.html

Java: // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gt2vnvcadrq.html

Go:   // 手写递归
来源：http://dali.xziqi.cn/Article/details/gt2aodjjqtr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ehwqpu.com/Article/details/gt2pgvhnkts.html

C#:   // 手写递归
来源：http://dali.shzxlz.cn/Article/details/gt2ndqplndn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xuetiantiany.cn/Article/details/gt2pgtqbfqy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.andypj.xyz/Article/details/gt2hvcycmfy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hfpthk.cn/Article/details/gt2waalygfr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cucudq.cn/Article/details/gt2nwlmawxu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gaohongyu789.top/Article/details/gt2gbqoelxx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnqzz.top/Article/details/gt2iqestkam.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sxryk.cn/Article/details/gt2ucnuwwvc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.wangdashe.top/Article/details/gt2jgijxfeo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rmkrozcr.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2cxjzmgdw.html

O. 并发与异步
来源：http://dali.nwbrower.top/Article/details/gt2iltcbnju.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2pmtzcjau.html

[O01] 启动一个线程
来源：http://dali.yangfankeji.com/Article/details/gt2hqedtgvg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.pengpengdd.cyou/Article/details/gt2dflujlqu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shzxlz.cn/Article/details/gt2xnatpggc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shzxlz.cn/Article/details/gt2fvtabzsu.html

TS:   // 同 JS
来源：http://dali.jinqigufen.top/Article/details/gt2anzsybpu.html

Java: new Thread(() -> f()).start()
来源：http://dali.jiagoushi.top/Article/details/gt2kcuqrmin.html

Go:   go f()
来源：http://dali.chenjidiqi.icu/Article/details/gt2cdfhhldu.html

Ruby: Thread.new { f }
来源：http://dali.sysykeji.top/Article/details/gt2mkhvfxbv.html

C#:   Task.Run(() => F());
来源：http://dali.vqdsnc.cn/Article/details/gt2ouzzcmin.html

[O02] 使用线程池
来源：http://dali.svipenyu.cn/Article/details/gt2katfqpgi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hfxeezwz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinqigufen.top/Article/details/gt2dmyvintp.html

JS:   // worker_threads 线程池
来源：http://dali.tianlin.xyz/Article/details/gt2qbikahoq.html

TS:   // worker_threads 线程池
来源：http://dali.chenjidiqi.icu/Article/details/gt2dikznurf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.pycfn.com/Article/details/gt2gogmlxtd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.c1oappe.top/Article/details/gt2asnmbvbj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.vqdsnc.cn/Article/details/gt2tllkambt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xinyue.icu/Article/details/gt2ewrimpvq.html

[O03] 加锁保护共享数据
来源：http://dali.mhx1999.top/Article/details/gt2uycznoyk.html

Py:   with lock: shared += 1
来源：http://dali.hammf.cn/Article/details/gt2pvemwysj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhongyouzk.top/Article/details/gt2dnfbckbo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jiagoushi.top/Article/details/gt2mxuhjatc.html

TS:   // 同 JS
来源：http://dali.xuanzx.com/Article/details/gt2lusipsdq.html

Java: synchronized (this) { shared++; }
来源：http://dali.redwolf501.top/Article/details/gt2vuzyhwdr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gaohongyu789.top/Article/details/gt2invgtmsi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tanke756.top/Article/details/gt2pxuhinfy.html

C#:   lock (gate) { shared++; }
来源：http://dali.sweek.top/Article/details/gt2sdowcbcp.html

[O04] 定义异步函数并等待
来源：http://dali.xinyue.icu/Article/details/gt2wyyvhnah.html

Py:   async def f():⏎    await g()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dtniudgk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gogol.net.cn/Article/details/gt2iididufx.html

JS:   async function f() { await g(); }
来源：http://dali.shuidangran.top/Article/details/gt2mcfahiyr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.haohaochexian.top/Article/details/gt2lidkpmpt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ybcxt.top/Article/details/gt2tebxqcbn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eetwodjp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhixingplan.top/Article/details/gt2hcqxeyto.html

C#:   async Task F() { await G(); }
来源：http://dali.9152youxi.cn/Article/details/gt2ljgknkew.html

[O05] 并发执行并等待全部完成
来源：http://dali.wangshuangyany.cn/Article/details/gt2qfuuadqv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yuanzhike.top/Article/details/gt2htemopwu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yuanzhike.top/Article/details/gt2vgwojkxd.html

JS:   await Promise.all(tasks)
来源：http://dali.yuxming.cn/Article/details/gt2rweusekt.html

TS:   await Promise.all(tasks)
来源：http://dali.hnxiangtu.top/Article/details/gt2zykgziqm.html


<!-- 参考信息 -->