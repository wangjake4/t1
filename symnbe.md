代发 wailian999

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jianghu66.top/Article/details/gtutmunehd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.birdmap.top/Article/details/gtrcxcywlh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hammf.cn/Article/details/gtaizugkvg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgfzy.top/Article/details/gtgjaewwzr.html

[L03] 设置自定义请求头
来源：http://dali.c1oappe.top/Article/details/gtcegjtoed.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.svipenyu.cn/Article/details/gtjczmearj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ehwqpu.com/Article/details/gtuwrupqnm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.svipenyu.cn/Article/details/gtociblvpv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hongshengwenyu.top/Article/details/gtqtlzxbnt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tian-w.cn/Article/details/gtlaueaqxx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.mhx1999.top/Article/details/gtmpybdytc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tian-w.cn/Article/details/gtyfljgtrx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gtfeopwuro.html

[L04] 设置超时
来源：http://dali.dianchejie.cn/Article/details/gtswpbwcbl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenzaomai.com/Article/details/gtzleyitwu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.andypj.xyz/Article/details/gtyvstpxvs.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.9152youxi.cn/Article/details/gttzqbkuvm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ydzc1.top/Article/details/gtgxeowyzj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.iojbl.cn/Article/details/gthzshaoho.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nwbrower.top/Article/details/gtldwlupjk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.andypj.xyz/Article/details/gtjgocvact.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinqigufen.top/Article/details/gtoaymtjqa.html

[L05] 上传文件（multipart）
来源：http://dali.ppjwa.cn/Article/details/gtqmqjcelf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj202588.top/Article/details/gtfbgaackv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.iojbl.cn/Article/details/gtwaqqaffr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gtitpxwspr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gtpxzajzlz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.andypj.xyz/Article/details/gtkpfiomas.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yonumen.top/Article/details/gtzcypfnwg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jqgfzy.top/Article/details/gtpptdoygf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnzyodkwo.html

[L06] 解析响应为 JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtqdgujtay.html

Py:   resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwmnqemw.html

PHP:  json_decode($body, true);
来源：http://dali.ybcxt.top/Article/details/gtuoexsogv.html

JS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gtwyyczpnp.html

TS:   await resp.json()
来源：http://dali.fengsongda.top/Article/details/gtkspxdnmr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xziqi.cn/Article/details/gtbssfxkij.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tian-w.cn/Article/details/gtfhvtabih.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258.top/Article/details/gteqzzddts.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xinyue.icu/Article/details/gtvoimpfjy.html

[L07] 处理 HTTP 状态码
来源：http://dali.cashguo.top/Article/details/gtzjxfgidu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hfpthk.cn/Article/details/gthykzzxzv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ehwqpu.com/Article/details/gtykdcrdis.html

JS:   resp.ok;  resp.status
来源：http://dali.sxryk.cn/Article/details/gtgxieqwgd.html

TS:   resp.ok;  resp.status
来源：http://dali.sxryk.cn/Article/details/gtccmkevtb.html

Java: resp.statusCode()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedufbtqa.html

Go:   resp.StatusCode
来源：http://dali.quarkkingdee.top/Article/details/gtsgokhbik.html

Ruby: resp.code.to_i
来源：http://dali.jqgufenzy.top/Article/details/gtgdjbrsho.html

C#:   (int)resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gtlqeutplx.html

[L08] 并发请求多个地址
来源：http://dali.zhixingplan.top/Article/details/gtqdrdkiou.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sxryk.cn/Article/details/gtcneiyvuq.html

PHP:  curl_multi_init() 系列
来源：http://dali.gotoacloud.top/Article/details/gtrwqemufg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zycfv.cn/Article/details/gtopddgjwj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gthscynxky.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shuidangran.top/Article/details/gttkkxliip.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tanke756.top/Article/details/gtsaszhkcq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tanke756.top/Article/details/gtdbperwtt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sysykeji.top/Article/details/gttdmnaliq.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtdrkrhunr.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcafhxesn.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtqmocjyvk.html

[M01] 读取命令行参数
来源：http://dali.guowangkeji.top/Article/details/gthulkogfl.html

Py:   sys.argv[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gttqpxuxhs.html

PHP:  $argv;  $argc;
来源：http://dali.hnxiangtu.top/Article/details/gtepoiwwmb.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigufen.top/Article/details/gtfmcqcuyj.html

TS:   process.argv.slice(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuimkdwuj.html

Java: args 数组（main 方法参数）
来源：http://dali.hysaishi.cn/Article/details/gtjtnzvefe.html

Go:   os.Args[1:]
来源：http://dali.tian-w.cn/Article/details/gtmafvlqvi.html

Ruby: ARGV
来源：http://dali.yangfankeji.com/Article/details/gtblxezzya.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cashguo.top/Article/details/gtaheckokr.html

[M02] 读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gtaucfrydk.html

Py:   os.environ.get("HOME")
来源：http://dali.sysykeji.top/Article/details/gtomednjld.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gteybhftfl.html

JS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gtjgzabwjz.html

TS:   process.env.HOME
来源：http://dali.quarkkingdee.top/Article/details/gtblptdjct.html

Java: System.getenv("HOME")
来源：http://dali.birdmap.top/Article/details/gtvbvqjcsi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.birdmap.top/Article/details/gtxowcepew.html

Ruby: ENV["HOME"]
来源：http://dali.zhiwuduotai.top/Article/details/gtqyxblmvi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtniipodvw.html

[M03] 执行外部命令
来源：http://dali.shuidangran.top/Article/details/gtrgajkcfu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtaawhrbuc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yanxiufei.cn/Article/details/gtkcheuomi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlcqdxqfb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmcoggiiz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cqqwz.cn/Article/details/gtbywlmcab.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.andypj.xyz/Article/details/gtkfpiuiix.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhengqikj.top/Article/details/gtmgiasenz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinqigufen.top/Article/details/gtuwczylvw.html

[M04] 获取当前工作目录
来源：http://dali.nanxuanxn.top/Article/details/gtjzeqafrl.html

Py:   os.getcwd()
来源：http://dali.quarkkingdee.top/Article/details/gtzbjzywur.html

PHP:  getcwd();
来源：http://dali.zhiwuduotai.top/Article/details/gtcfwuwqbq.html

JS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gtidrscltw.html

TS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gtauuuoduw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jianghu66.top/Article/details/gtboxygusq.html

Go:   os.Getwd()
来源：http://dali.zycfv.cn/Article/details/gtmevkpuff.html

Ruby: Dir.pwd
来源：http://dali.ybcxt.top/Article/details/gtytbshsre.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndtzaroq.html

[M05] 设置退出码
来源：http://dali.wangdashe.top/Article/details/gteoecsaot.html

Py:   sys.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtqqxwcnhr.html

PHP:  exit(1);
来源：http://dali.gogol.net.cn/Article/details/gtjhslpsxh.html

JS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtiqdoeksg.html

TS:   process.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtcigsmpft.html

Java: System.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtmsfdjpic.html

Go:   os.Exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtvaaplcfc.html

Ruby: exit 1
来源：http://dali.xinyue.icu/Article/details/gtlerrrfam.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigfzy.top/Article/details/gtkpwvxihs.html

[M06] 向标准错误输出
来源：http://dali.yangfankeji.com/Article/details/gtjxfqgkla.html

Py:   print("err", file=sys.stderr)
来源：http://dali.pengpengdd.cyou/Article/details/gtdheqbooj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hnxiangtu.top/Article/details/gtwwkcoyqb.html

JS:   console.error("err")
来源：http://dali.gotoacloud.top/Article/details/gtcgxlmcjm.html

TS:   console.error("err")
来源：http://dali.aibaodan.cn/Article/details/gtechnmoth.html

Java: System.err.println("err")
来源：http://dali.xziqi.cn/Article/details/gtsfrjuqtx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.feifeiyinyue.top/Article/details/gtgdrpzeye.html

Ruby: warn "err"
来源：http://dali.shanyushiyangtech.top/Article/details/gtamhoixhq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yanxiufei.cn/Article/details/gtdcgjqnnh.html

[M07] 判断是否为主入口
来源：http://dali.cucudq.cn/Article/details/gtacazxeol.html

Py:   if __name__ == "__main__":
来源：http://dali.birdmap.top/Article/details/gtfrrxdfvu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shuidangran.top/Article/details/gtqcgwmcuk.html

JS:   require.main === module
来源：http://dali.meibo888.top/Article/details/gtdnyzrzqm.html

TS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gtqqtazbln.html

Java: public static void main(String[] args)
来源：http://dali.fzhhl.top/Article/details/gtfnoupzoe.html

Go:   func main()
来源：http://dali.gzhubu.top/Article/details/gttskegzbz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.daria6918.cn/Article/details/gtjvjtgkqi.html

C#:   static void Main(string[] args)
来源：http://dali.meibo888.top/Article/details/gtdngvceoo.html

[M08] 获取系统与运行时信息
来源：http://dali.cqqwz.cn/Article/details/gtsubvtxfk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.0kj1m.cn/Article/details/gtkmnxcyfx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ybcxt.top/Article/details/gtnjmmjhtu.html

JS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gtkreetauf.html

TS:   process.platform;  process.version
来源：http://dali.wangdashe.top/Article/details/gtswbmrvjy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.vqdsnc.cn/Article/details/gtyeswhetd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenzaomai.com/Article/details/gtofhobpug.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.0kj1m.cn/Article/details/gtwtsydnpy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ivvv.top/Article/details/gtovrqetun.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtynraghjd.html

N. 数据结构与算法
来源：http://dali.chenjidiqi.icu/Article/details/gtsfvhosel.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtmcpbkyod.html

[N01] 二分查找（有序数组）
来源：http://dali.jiagoushi.top/Article/details/gteypzdagp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtlvstudea.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.guannengcc.top/Article/details/gtkcodcdrd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guannengcc.top/Article/details/gtjpzokdun.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258.top/Article/details/gthsysjyef.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtcpgsvrbr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtxkbxaijw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shangyingyoupin.top/Article/details/gtrhpzgzqo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtjjskxkse.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sweek.top/Article/details/gtumxxjgpp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hysaishi.cn/Article/details/gtvumdkmaj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hywenlv.cn/Article/details/gtxzbrcyhy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gtrbpuewhn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gtekmnkfjn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhongyouzk.top/Article/details/gtwdemkbkh.html

Go:   slices.Sort(arr)
来源：http://dali.yonumen.top/Article/details/gtuhhuihbp.html

Ruby: arr.sort
来源：http://dali.jianghu66.top/Article/details/gtuuqcyxyf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.snrcjt.cn/Article/details/gttisntfcj.html

[N03] 快速排序（分治示例）
来源：http://dali.zhaomingkeji.xyz/Article/details/gttlnubscd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ppjwa.cn/Article/details/gtruorlasp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.pycfn.com/Article/details/gtbfjcaexr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gtctfrfbio.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xziqi.cn/Article/details/gtvnbuqdxh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.iojbl.cn/Article/details/gtarmlicbj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gotoacloud.top/Article/details/gtrkwtuknx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhengqikj.top/Article/details/gtyfsslgkr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tian-w.cn/Article/details/gtusoncnqf.html

[N04] 斐波那契数列
来源：http://dali.zhoulong.xyz/Article/details/gtkgkwgpnl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yangfankeji.com/Article/details/gtfksdmfcp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.fzhhl.top/Article/details/gtlkpvqpai.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gttyyockgo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gtwduizlnq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nanxinkj.top/Article/details/gtlqbhrbwh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xziqi.cn/Article/details/gtepgtlbus.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gtesxxkuxh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gtuhhunruq.html

[N05] 最大公约数
来源：http://dali.meibo888.top/Article/details/gtphvoigmz.html

Py:   math.gcd(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gtazrrjwrv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.fengsongda.top/Article/details/gtoepolwhq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuanzhike.top/Article/details/gtfualcgxx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hysaishi.cn/Article/details/gthozukvak.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.daxiang520.top/Article/details/gtltoruxbd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrmkplxd.html

Ruby: a.gcd(b)
来源：http://dali.ybcxt.top/Article/details/gtptivqrzt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xziqi.cn/Article/details/gtdkulxehv.html

[N06] 判断回文字符串
来源：http://dali.andypj.xyz/Article/details/gtsrtvheej.html

Py:   s == s[::-1]
来源：http://dali.gotoacloud.top/Article/details/gtvyzxgloo.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gtbvlazigh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtvrbvoeyu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtmmetkkcn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yanxiufei.cn/Article/details/gtcemmcivn.html

Go:   // 双指针从两端比较
来源：http://dali.aizwys.cn/Article/details/gteohlhzbw.html

Ruby: s == s.reverse
来源：http://dali.yonumen.top/Article/details/gturdbflgv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hammf.cn/Article/details/gteegpjcwz.html

[N07] 两数之和（返回下标）
来源：http://dali.ivvv.top/Article/details/gtugxkydhp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cashguo.top/Article/details/gtqyemhadi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.pycfn.com/Article/details/gtjnuaqaro.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinqigufen.top/Article/details/gtyqhtyrez.html

TS:   // 手写 Map<string, number>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlaisfnlg.html

Java: // 手写 HashMap
来源：http://dali.shanyushiyangtech.top/Article/details/gtqrfreext.html

Go:   // 手写 map[int]int
来源：http://dali.quarkkingdee.top/Article/details/gtyqotpdvx.html

Ruby: // 手写 Hash
来源：http://dali.chenjidiqi.icu/Article/details/gtjsdmhgub.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tian-w.cn/Article/details/gtfycxwxom.html

[N08] 生成全排列
来源：http://dali.xuetiantiany.cn/Article/details/gtnflaflml.html

Py:   itertools.permutations(arr)
来源：http://dali.meibo888.top/Article/details/gtxzimzqpz.html

PHP:  // 手写递归交换
来源：http://dali.ybcxt.top/Article/details/gthpeqnshi.html

JS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtcihksade.html

TS:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtsqmnijic.html

Java: // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gtwcxrexrg.html

Go:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtcrybanfe.html

Ruby: arr.permutation.to_a
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkgldriww.html

C#:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gttcvimshf.html

[N09] 栈与队列
来源：http://dali.yueranfly.top/Article/details/gtvlpmevkw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nanxinkj.top/Article/details/gtwrlnutjm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttrwpvbne.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtysmjfvgq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yonumen.top/Article/details/gtyyjrwqlr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtgwzlshhm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.andypj.xyz/Article/details/gtebtvkiob.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gtxbjcumyb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenzaomai.com/Article/details/gtulgylyob.html

[N10] 链表节点定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgyitgyv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jiagoushi.top/Article/details/gtpypyaxvp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinqigufen.top/Article/details/gtkpspjsyv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.nanxinkj.top/Article/details/gtxotnfgsz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.havefunace.top/Article/details/gtyfogfehb.html

Java: class Node { int v; Node next; }
来源：http://dali.tian-w.cn/Article/details/gtyilbujli.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.feifeiyinyue.top/Article/details/gtjcenzbgi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.fengsongda.top/Article/details/gtiaghaiaf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shangyingyoupin.top/Article/details/gtpdogwnje.html

[N11] 二叉树中序遍历
来源：http://dali.redwolf501.top/Article/details/gthqeijomw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yueranfly.top/Article/details/gtgyayeftb.html

PHP:  // 手写递归函数
来源：http://dali.yueranfly.top/Article/details/gtpfnswhfz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj202588.top/Article/details/gtgmjwdnyn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigufen.top/Article/details/gtvamebjgp.html

Java: // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcdlwoemd.html

Go:   // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gtmxnoiubz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cqqwz.cn/Article/details/gtoixfhlgr.html

C#:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gtruvxhgsk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.316326.xyz/Article/details/gthqvvtqzt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xinyue.icu/Article/details/gtrgpanrwn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.pycfn.com/Article/details/gtuwembzqy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yangfankeji.com/Article/details/gtmcflnufn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yvedp.cn/Article/details/gtxqrcsebk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xziqi.cn/Article/details/gtouploacj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jyoumei.cn/Article/details/gtcfuodazl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.pycfn.com/Article/details/gtuzczpspa.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqesujfrv.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtksempbvw.html

O. 并发与异步
来源：http://dali.guannengcc.top/Article/details/gtnbejcgxf.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtkhsbuohr.html

[O01] 启动一个线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoccnkbwj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.kuanghao11.cn/Article/details/gtlgjalidc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gogol.net.cn/Article/details/gtqyjkvccu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.pycfn.com/Article/details/gtpbyppeyy.html

TS:   // 同 JS
来源：http://dali.feifeiyinyue.top/Article/details/gtxuufzuwr.html

Java: new Thread(() -> f()).start()
来源：http://dali.gogol.net.cn/Article/details/gtdkhhefzo.html

Go:   go f()
来源：http://dali.birdmap.top/Article/details/gtgmesssat.html

Ruby: Thread.new { f }
来源：http://dali.xylfe.cn/Article/details/gtlzxnjpeb.html

C#:   Task.Run(() => F());
来源：http://dali.dashuyun.cn/Article/details/gtfcakoxvh.html

[O02] 使用线程池
来源：http://dali.jiagoushi.top/Article/details/gtpecttxug.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.9152youxi.cn/Article/details/gtyxjfsgty.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jlsjyb.cn/Article/details/gtomzghvft.html

JS:   // worker_threads 线程池
来源：http://dali.tanke756.top/Article/details/gtizwexriy.html

TS:   // worker_threads 线程池
来源：http://dali.nanxuanxn.top/Article/details/gtbosybdzh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gzhubu.top/Article/details/gtqjwtliyn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shuidangran.top/Article/details/gtrjpuktgg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shangyingyoupin.top/Article/details/gtdxlvqgex.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hfpthk.cn/Article/details/gtwobcaxax.html

[O03] 加锁保护共享数据
来源：http://dali.ppjwa.cn/Article/details/gtykzvbspi.html

Py:   with lock: shared += 1
来源：http://dali.hywenlv.cn/Article/details/gtorjjhbgd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj202588.top/Article/details/gtxufqipoo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xylfe.cn/Article/details/gtdoklednl.html

TS:   // 同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrqugmybs.html

Java: synchronized (this) { shared++; }
来源：http://dali.ehwqpu.com/Article/details/gtxshthqib.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.birdmap.top/Article/details/gtcsfwortg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.fengsongda.top/Article/details/gtdoeasthr.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwplslcxu.html

[O04] 定义异步函数并等待
来源：http://dali.yueranfly.top/Article/details/gtyxrzcasw.html

Py:   async def f():⏎    await g()
来源：http://dali.kuanghao11.cn/Article/details/gtzfooqscz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hnqzz.top/Article/details/gtewuihjbn.html

JS:   async function f() { await g(); }
来源：http://dali.shuidangran.top/Article/details/gtjvpnrkjp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cashguo.top/Article/details/gtlysrpood.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jyoumei.cn/Article/details/gtoacprple.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.bjfxy.top/Article/details/gtutijdqph.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hnxiangtu.top/Article/details/gttauvvxjl.html

C#:   async Task F() { await G(); }
来源：http://dali.hnqzz.top/Article/details/gtzwvgjvfq.html

[O05] 并发执行并等待全部完成
来源：http://dali.kuanghao11.cn/Article/details/gtzdggviil.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhongyouzk.top/Article/details/gtyqugnyqe.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yvedp.cn/Article/details/gtxrjwrldm.html

JS:   await Promise.all(tasks)
来源：http://dali.cqqwz.cn/Article/details/gtoyhfkaue.html

TS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gtduujvtvf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yonumen.top/Article/details/gtbxzgdohy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tianlin.xyz/Article/details/gtqvahffov.html

Ruby: threads.map(&:join)
来源：http://dali.meibo888.top/Article/details/gtgveynokq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ybcxt.top/Article/details/gtrcmgmwfk.html

[O06] 使用进程池
来源：http://dali.gzhubu.top/Article/details/gtlpgmuplv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cashguo.top/Article/details/gtkyxxmnac.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.dianchejie.cn/Article/details/gtybrivqql.html

JS:   // child_process / cluster 模块
来源：http://dali.dashuyun.cn/Article/details/gtahbttzho.html

TS:   // child_process / cluster 模块
来源：http://dali.zhengqikj.top/Article/details/gtadxyftyz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sysykeji.top/Article/details/gtywtohqir.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhongyouzk.top/Article/details/gtqzlzzlcj.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gtofoiyddk.html


<!-- 参考信息 -->