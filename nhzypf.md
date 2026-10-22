代发 wailian999

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jlsjyb.cn/Article/details/gtbusahhhy.html

JS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gtdpdcehul.html

TS:   await fetch(url)
来源：http://dali.mhx1999.top/Article/details/gthockntpv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.mhx1999.top/Article/details/gtrdvvwjqn.html

Go:   resp, err := http.Get(url)
来源：http://dali.c1oappe.top/Article/details/gtdccxvilk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.andypj.xyz/Article/details/gtcerjshoj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hammf.cn/Article/details/gtspkmwuzj.html

[L02] 发送 POST JSON
来源：http://dali.yj20258.top/Article/details/gtoqyghysw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sweek.top/Article/details/gtyphrvjrf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shuidangran.top/Article/details/gtitmuwgxw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jlsjyb.cn/Article/details/gtiqbcbrdb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtarqxtmbl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cqqwz.cn/Article/details/gtgzsulmln.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ehwqpu.com/Article/details/gtwnkixzfg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dashuyun.cn/Article/details/gtjeecuvrq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shangyingyoupin.top/Article/details/gteaulqstf.html

[L03] 设置自定义请求头
来源：http://dali.cucudq.cn/Article/details/gtiygcauxf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nwbrower.top/Article/details/gtodovpqdw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.wangshuangyany.cn/Article/details/gthkienyqk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xylfe.cn/Article/details/gtgililhzo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxvbuxye.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzpvgjod.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xinyue.icu/Article/details/gtuwkgpiuc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jqgufenzy.top/Article/details/gtmvlpbadl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwjotbfq.html

[L04] 设置超时
来源：http://dali.ppjwa.cn/Article/details/gtxwethqew.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sxryk.cn/Article/details/gtityhvksc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhiwuduotai.top/Article/details/gtlbqajhbb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hysaishi.cn/Article/details/gtzrqitoho.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gthukavyhy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.fengsongda.top/Article/details/gtlgvyisqs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hongshengwenyu.top/Article/details/gtpaosnpfy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqeazgxv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sxryk.cn/Article/details/gtebtwbphg.html

[L05] 上传文件（multipart）
来源：http://dali.iojbl.cn/Article/details/gtwrqlagxh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.wangdashe.top/Article/details/gtytcdymey.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.andypj.xyz/Article/details/gtoqwoixss.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.316326.xyz/Article/details/gtcfepdelu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tanke756.top/Article/details/gtvgcpqibl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinqigfzy.top/Article/details/gtjspkwtkl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jqgufenzy.top/Article/details/gttrsofyia.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.birdmap.top/Article/details/gtyhxylxdd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.birdmap.top/Article/details/gtiqpsklhg.html

[L06] 解析响应为 JSON
来源：http://dali.ehwqpu.com/Article/details/gthagrvott.html

Py:   resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxnqplkv.html

PHP:  json_decode($body, true);
来源：http://dali.tianlin.xyz/Article/details/gthhpbumft.html

JS:   await resp.json()
来源：http://dali.tian-w.cn/Article/details/gtfgrgvkuw.html

TS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gtgqlzhuav.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.wangdashe.top/Article/details/gtfwtqsnch.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelufuogu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.wangshuangyany.cn/Article/details/gtaerelazd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aibaodan.cn/Article/details/gtfafpjwkc.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gtcyffdfvn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.dashuyun.cn/Article/details/gtwuhhvfts.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xinyue.icu/Article/details/gtahwknhyr.html

JS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gtjpkfwmst.html

TS:   resp.ok;  resp.status
来源：http://dali.havefunace.top/Article/details/gtesxxfyvt.html

Java: resp.statusCode()
来源：http://dali.aizwys.cn/Article/details/gtmksipfky.html

Go:   resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gtrcyvylyw.html

Ruby: resp.code.to_i
来源：http://dali.mhx1999.top/Article/details/gtrljhlvrx.html

C#:   (int)resp.StatusCode
来源：http://dali.quarkkingdee.top/Article/details/gtlnrdrvnx.html

[L08] 并发请求多个地址
来源：http://dali.fengsongda.top/Article/details/gtjdmdqcfg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.iojbl.cn/Article/details/gtxciglrji.html

PHP:  curl_multi_init() 系列
来源：http://dali.tian-w.cn/Article/details/gtdedrruqa.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoxilfjzz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gtybeabrvn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hammf.cn/Article/details/gtjnadorlm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nanxinkj.top/Article/details/gtbmljjdir.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.snrcjt.cn/Article/details/gtdufugvff.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xylfe.cn/Article/details/gtlzppqvxx.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtsmyifedj.html

M. 命令行 / 进程 / 环境
来源：http://dali.svipenyu.cn/Article/details/gtlwirnpqv.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtspmscxqo.html

[M01] 读取命令行参数
来源：http://dali.gotoacloud.top/Article/details/gtdrlwtdcw.html

Py:   sys.argv[1:]
来源：http://dali.ehwqpu.com/Article/details/gtxpovmtvd.html

PHP:  $argv;  $argc;
来源：http://dali.pycfn.com/Article/details/gtzztciezb.html

JS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gtwgfulkxi.html

TS:   process.argv.slice(2)
来源：http://dali.wangdashe.top/Article/details/gtmkvtadmy.html

Java: args 数组（main 方法参数）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkmytgiad.html

Go:   os.Args[1:]
来源：http://dali.guannengcc.top/Article/details/gtlevbhqfx.html

Ruby: ARGV
来源：http://dali.meibo888.top/Article/details/gtilsrgtua.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hnqzz.top/Article/details/gtikwaiiiu.html

[M02] 读取环境变量
来源：http://dali.hammf.cn/Article/details/gtmayffgiy.html

Py:   os.environ.get("HOME")
来源：http://dali.ivvv.top/Article/details/gttovkpndz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhengqikj.top/Article/details/gtxzmdrpuo.html

JS:   process.env.HOME
来源：http://dali.yonumen.top/Article/details/gtgfugprfw.html

TS:   process.env.HOME
来源：http://dali.zdqjudy.top/Article/details/gtkzaqhezn.html

Java: System.getenv("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtpxqkucvg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gtlwsdpqsp.html

Ruby: ENV["HOME"]
来源：http://dali.tanke756.top/Article/details/gtdncythbq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtvxtuqqdd.html

[M03] 执行外部命令
来源：http://dali.daria6918.cn/Article/details/gtkdjtqvvx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.iojbl.cn/Article/details/gtebxhawiv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhiwuduotai.top/Article/details/gtfznoavgp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.316326.xyz/Article/details/gtmxjleoud.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenjidiqi.icu/Article/details/gtvwqvgrfr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sufxvd.cn/Article/details/gtxpfprhab.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.snrcjt.cn/Article/details/gtrpgxvqmb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xziqi.cn/Article/details/gtzigmfpcy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xuetiantiany.cn/Article/details/gtkwsfzihf.html

[M04] 获取当前工作目录
来源：http://dali.pycfn.com/Article/details/gtjtlninnb.html

Py:   os.getcwd()
来源：http://dali.yangfankeji.com/Article/details/gthuwctits.html

PHP:  getcwd();
来源：http://dali.zdqjudy.top/Article/details/gtdeggrvsd.html

JS:   process.cwd()
来源：http://dali.yuxming.cn/Article/details/gtuqyhkino.html

TS:   process.cwd()
来源：http://dali.dashuyun.cn/Article/details/gtrvxrfwls.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.redwolf501.top/Article/details/gtmtmedpvw.html

Go:   os.Getwd()
来源：http://dali.wangdashe.top/Article/details/gtkqbelziv.html

Ruby: Dir.pwd
来源：http://dali.nwbrower.top/Article/details/gtiuigqhlt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhengqikj.top/Article/details/gtzzxbqrws.html

[M05] 设置退出码
来源：http://dali.redwolf501.top/Article/details/gteemuqhts.html

Py:   sys.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtibvjsanm.html

PHP:  exit(1);
来源：http://dali.zycfv.cn/Article/details/gtaujzjemg.html

JS:   process.exit(1)
来源：http://dali.hammf.cn/Article/details/gtlxirinwk.html

TS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtgbsntoht.html

Java: System.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtiophpmcw.html

Go:   os.Exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtokpxpmnk.html

Ruby: exit 1
来源：http://dali.fengsongda.top/Article/details/gtjjtnbimt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tanke756.top/Article/details/gtocehpwwa.html

[M06] 向标准错误输出
来源：http://dali.vqdsnc.cn/Article/details/gtbjaygvnk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jiagoushi.top/Article/details/gtllzifpwh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.daxiang520.top/Article/details/gtgcjnbxhr.html

JS:   console.error("err")
来源：http://dali.aibaodan.cn/Article/details/gtvjuohcir.html

TS:   console.error("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkwwcrrsy.html

Java: System.err.println("err")
来源：http://dali.316326.xyz/Article/details/gtjhocgzob.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yongpay.top/Article/details/gtgoaofdxk.html

Ruby: warn "err"
来源：http://dali.birdmap.top/Article/details/gtrvmecxum.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sweek.top/Article/details/gtqzbjqugm.html

[M07] 判断是否为主入口
来源：http://dali.yangfankeji.com/Article/details/gtqeceouct.html

Py:   if __name__ == "__main__":
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmcufifa.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jiagoushi.top/Article/details/gtclggqioj.html

JS:   require.main === module
来源：http://dali.shzxlz.cn/Article/details/gtsoeziobo.html

TS:   require.main === module
来源：http://dali.sweek.top/Article/details/gtukogjjjk.html

Java: public static void main(String[] args)
来源：http://dali.haohaochexian.top/Article/details/gtlyoymbpd.html

Go:   func main()
来源：http://dali.zycfv.cn/Article/details/gtmpaqieij.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guannengcc.top/Article/details/gtddjdladx.html

C#:   static void Main(string[] args)
来源：http://dali.chenlongwang.top/Article/details/gtcbybtqju.html

[M08] 获取系统与运行时信息
来源：http://dali.guowangkeji.top/Article/details/gtykniopfk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.guowangkeji.top/Article/details/gtwnlxjvjv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.redwolf501.top/Article/details/gtdxbgykiq.html

JS:   process.platform;  process.version
来源：http://dali.jiagoushi.top/Article/details/gticlrwoot.html

TS:   process.platform;  process.version
来源：http://dali.ydzc1.top/Article/details/gtlaazifpp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sweek.top/Article/details/gtjhcsafqw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.dashuyun.cn/Article/details/gtltcyoitv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj20258888.top/Article/details/gtblbuzalp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hongshengwenyu.top/Article/details/gtczefqksq.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtuaoljsvg.html

N. 数据结构与算法
来源：http://dali.yonumen.top/Article/details/gtkamfiulw.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtbwttsufn.html

[N01] 二分查找（有序数组）
来源：http://dali.316326.xyz/Article/details/gtgvhoqqan.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtxauqqfzg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shzxlz.cn/Article/details/gtgslrlvwx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yangfankeji.com/Article/details/gtqxlpnrqv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.havefunace.top/Article/details/gtpasltqje.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtrfkdunyl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtvcgsektx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.fzhhl.top/Article/details/gtfkyysmcn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gtgxzslslr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sweek.top/Article/details/gtpucrncdg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cdnleiting.top/Article/details/gtqbnxmemx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jlsjyb.cn/Article/details/gtabkwcife.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtecfhzrkj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgufenzy.top/Article/details/gtutteakqe.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cdnleiting.top/Article/details/gtaerxxaae.html

Go:   slices.Sort(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrmcatog.html

Ruby: arr.sort
来源：http://dali.zhoulong.xyz/Article/details/gtdktspync.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jlsjyb.cn/Article/details/gthkpwdvgu.html

[N03] 快速排序（分治示例）
来源：http://dali.xinyue.icu/Article/details/gtolhtlxax.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fengsongda.top/Article/details/gtctjrbxmu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tian-w.cn/Article/details/gtvpjhaxxi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gtodbjspqs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxyktabbw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.tanke756.top/Article/details/gtmfjhqtbe.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ehwqpu.com/Article/details/gtdgsqqmka.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinghuilouyu.cn/Article/details/gtwendcbcr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yangfankeji.com/Article/details/gtnvvobwvh.html

[N04] 斐波那契数列
来源：http://dali.yongpay.top/Article/details/gtidradnbt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.0kj1m.cn/Article/details/gthimywfir.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhoulong.xyz/Article/details/gtlbdiwmew.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtqytrynqq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtlojkadac.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.wangdashe.top/Article/details/gtznbahvft.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yuxming.cn/Article/details/gtnzthahaf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhixingplan.top/Article/details/gtdggiicpv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gtsdtjiwkb.html

[N05] 最大公约数
来源：http://dali.gaohongyu789.top/Article/details/gtnignfiqj.html

Py:   math.gcd(a, b)
来源：http://dali.hammf.cn/Article/details/gtmjtbmxax.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gzhubu.top/Article/details/gtlfzgthlh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtvemskcwt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvthgdmcc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nanxinkj.top/Article/details/gtktnqxeoq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cdnleiting.top/Article/details/gtiesiixzf.html

Ruby: a.gcd(b)
来源：http://dali.cqqwz.cn/Article/details/gtulkndqit.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cdnleiting.top/Article/details/gtidqebejs.html

[N06] 判断回文字符串
来源：http://dali.andypj.xyz/Article/details/gtnshldgso.html

Py:   s == s[::-1]
来源：http://dali.gzhubu.top/Article/details/gtchgycduj.html

PHP:  $s === strrev($s);
来源：http://dali.hnqzz.top/Article/details/gtcbftgpwa.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtkhwyhuqu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtfvdblxmk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.dianchejie.cn/Article/details/gttagwbbeo.html

Go:   // 双指针从两端比较
来源：http://dali.guannengcc.top/Article/details/gtbwjxhfyr.html

Ruby: s == s.reverse
来源：http://dali.sufxvd.cn/Article/details/gtvmegdyky.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jqgfzy.top/Article/details/gtpynpguqy.html

[N07] 两数之和（返回下标）
来源：http://dali.cdnleiting.top/Article/details/gtgueuarzp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhiwuduotai.top/Article/details/gtjmqqsydc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hysaishi.cn/Article/details/gtxiyaxmbq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.feifeiyinyue.top/Article/details/gthyyyxxnx.html

TS:   // 手写 Map<string, number>
来源：http://dali.c1oappe.top/Article/details/gtqvbbheyr.html

Java: // 手写 HashMap
来源：http://dali.ybcxt.top/Article/details/gttjykheyb.html

Go:   // 手写 map[int]int
来源：http://dali.haohaochexian.top/Article/details/gtpyrltogd.html

Ruby: // 手写 Hash
来源：http://dali.0kj1m.cn/Article/details/gtertwspnz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gogol.net.cn/Article/details/gtyiupeeqm.html

[N08] 生成全排列
来源：http://dali.smart0.xyz/Article/details/gtyhqhjbay.html

Py:   itertools.permutations(arr)
来源：http://dali.zhixingplan.top/Article/details/gtfcrqvlki.html

PHP:  // 手写递归交换
来源：http://dali.mhx1999.top/Article/details/gthmnirfiq.html

JS:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtfeaedyae.html

TS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtosiecsvq.html

Java: // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtnpweesuz.html

Go:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtbcigevxf.html

Ruby: arr.permutation.to_a
来源：http://dali.hongshengwenyu.top/Article/details/gtedcqfoqd.html

C#:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtakvlkany.html

[N09] 栈与队列
来源：http://dali.tian-w.cn/Article/details/gtyuwmwihs.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtupvuoyui.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gtfuusbqis.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtimckuquf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cashguo.top/Article/details/gtvouxwfyy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sysykeji.top/Article/details/gtwttsfadg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yangfankeji.com/Article/details/gtmqvcivpj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtmnslvaay.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jiagoushi.top/Article/details/gtabhfpsik.html

[N10] 链表节点定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdfbnasmy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tanke756.top/Article/details/gtrpylfmek.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hammf.cn/Article/details/gtsjjxyoma.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cdnleiting.top/Article/details/gtjsuznyie.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tanke756.top/Article/details/gtjwwpacgr.html

Java: class Node { int v; Node next; }
来源：http://dali.tianlin.xyz/Article/details/gtghmmxjdw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.pengpengdd.cyou/Article/details/gtfxahafvv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yonumen.top/Article/details/gtmujrnicg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yanxiufei.cn/Article/details/gtkshkueoe.html

[N11] 二叉树中序遍历
来源：http://dali.shzxlz.cn/Article/details/gtjvifgxsy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shuidangran.top/Article/details/gtocsizfea.html

PHP:  // 手写递归函数
来源：http://dali.cashguo.top/Article/details/gtybeavfnv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.redwolf501.top/Article/details/gtwpunbgnn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gtvzbxnaxe.html

Java: // 手写递归
来源：http://dali.andypj.xyz/Article/details/gtczlsghfq.html

Go:   // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gtpgewcpzr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenjidiqi.icu/Article/details/gtopbedzqx.html

C#:   // 手写递归
来源：http://dali.yj20258888.top/Article/details/gtypqaqdyz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.daria6918.cn/Article/details/gtfmrsglpt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ppjwa.cn/Article/details/gtruwrfnrr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.c1oappe.top/Article/details/gtfwstwfic.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shangyingyoupin.top/Article/details/gtmbavmkot.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aizwys.cn/Article/details/gtawlgcbuh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gtagnctqhu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.tian-w.cn/Article/details/gtqrtpuzpq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.guannengcc.top/Article/details/gtqyvaswju.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnxiangtu.top/Article/details/gtviulazys.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtrubiypqa.html

O. 并发与异步
来源：http://dali.feifeiyinyue.top/Article/details/gtqomeijcz.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtplwqhsia.html

[O01] 启动一个线程
来源：http://dali.yuanzhike.top/Article/details/gteyxucsly.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.iojbl.cn/Article/details/gtfozcmpqx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sysykeji.top/Article/details/gtpzrpsgll.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hnxiangtu.top/Article/details/gturqmlwdz.html

TS:   // 同 JS
来源：http://dali.bjfxy.top/Article/details/gtqapbzxfr.html

Java: new Thread(() -> f()).start()
来源：http://dali.hnqzz.top/Article/details/gtlfgzgaqq.html

Go:   go f()
来源：http://dali.cheryme.top/Article/details/gtlheicohv.html

Ruby: Thread.new { f }
来源：http://dali.quarkkingdee.top/Article/details/gtbxpwfuvw.html

C#:   Task.Run(() => F());
来源：http://dali.pycfn.com/Article/details/gtibflmypa.html

[O02] 使用线程池
来源：http://dali.birdmap.top/Article/details/gtcxdlgqcr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.birdmap.top/Article/details/gtquwggvxo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj202588.top/Article/details/gtlcmouwxl.html

JS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gtkrgvraua.html

TS:   // worker_threads 线程池
来源：http://dali.ivvv.top/Article/details/gttkrstetu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yuxming.cn/Article/details/gtioswffdb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.9152youxi.cn/Article/details/gtmvxnxyek.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cdnleiting.top/Article/details/gttuqsvidv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.pycfn.com/Article/details/gtklhttsfn.html

[O03] 加锁保护共享数据
来源：http://dali.sysykeji.top/Article/details/gtqtqtngio.html

Py:   with lock: shared += 1
来源：http://dali.cucudq.cn/Article/details/gtoelgphrw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shuidangran.top/Article/details/gthupyefyb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ppjwa.cn/Article/details/gtcjitoqje.html

TS:   // 同 JS
来源：http://dali.hnxiangtu.top/Article/details/gtyvpsmdah.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfepailup.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cdnleiting.top/Article/details/gtrxmhpiio.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.dianchejie.cn/Article/details/gtlxktgfup.html

C#:   lock (gate) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxunzijrq.html

[O04] 定义异步函数并等待
来源：http://dali.ydzc1.top/Article/details/gtnnuvwrkw.html

Py:   async def f():⏎    await g()
来源：http://dali.cheryme.top/Article/details/gtvcqlvebd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ydzc1.top/Article/details/gthnijckmx.html

JS:   async function f() { await g(); }
来源：http://dali.yj20258888.top/Article/details/gtwwwiwrpp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmqfrgma.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.feifeiyinyue.top/Article/details/gtovfiermd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yongpay.top/Article/details/gtgrjayuyp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cashguo.top/Article/details/gtoyoktjge.html

C#:   async Task F() { await G(); }
来源：http://dali.zycfv.cn/Article/details/gtuxgkkrmt.html

[O05] 并发执行并等待全部完成
来源：http://dali.tanke756.top/Article/details/gtlyrcvcqf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gtnlgmifcl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ppjwa.cn/Article/details/gtbmppbilq.html

JS:   await Promise.all(tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gtqvuszphf.html

TS:   await Promise.all(tasks)
来源：http://dali.yonumen.top/Article/details/gtyzkfhiyj.html


<!-- 参考信息 -->