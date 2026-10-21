代发 wailian999

[L03] 设置自定义请求头
来源：http://dali.hfpthk.cn/Article/details/gtuovcwggl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yanxiufei.cn/Article/details/gtijurkfqe.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenzaomai.com/Article/details/gtaqwrgqce.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sweek.top/Article/details/gtxcxzquyg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yangfankeji.com/Article/details/gtgndhetbf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zycfv.cn/Article/details/gtlodhysgx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gtaupqzktb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cucudq.cn/Article/details/gtamjrutrc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.daria6918.cn/Article/details/gtnqjbraoj.html

[L04] 设置超时
来源：http://dali.xuetiantiany.cn/Article/details/gtndwbhnyh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yueranfly.top/Article/details/gtoxmwkskm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fzhhl.top/Article/details/gtpgbrffxi.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.c1oappe.top/Article/details/gtwvfxqzkd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtouzmmfxo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hnxiangtu.top/Article/details/gthsqjdiwz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hammf.cn/Article/details/gtkmjzwztp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.andypj.xyz/Article/details/gthtbflslg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cashguo.top/Article/details/gtbiwkcxzz.html

[L05] 上传文件（multipart）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvelkseok.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ybcxt.top/Article/details/gtfubwjwmd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shzxlz.cn/Article/details/gtcpgknezo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gtogjtpvnf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gtajoqucux.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258.top/Article/details/gtxfmyiumu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cucudq.cn/Article/details/gthimamguv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ehwqpu.com/Article/details/gtrkmggajq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtkeefncxh.html

[L06] 解析响应为 JSON
来源：http://dali.yangfankeji.com/Article/details/gtgofggwzn.html

Py:   resp.json()
来源：http://dali.nwbrower.top/Article/details/gtznomjijz.html

PHP:  json_decode($body, true);
来源：http://dali.snrcjt.cn/Article/details/gtrnyeajfn.html

JS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gthgkyenqn.html

TS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gtxcolzwbq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.wangdashe.top/Article/details/gtvrobfmeq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.haohaochexian.top/Article/details/gtxdoxlfbi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tian-w.cn/Article/details/gtmbwcitsr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.9152youxi.cn/Article/details/gtcioykrmw.html

[L07] 处理 HTTP 状态码
来源：http://dali.nanxuanxn.top/Article/details/gtdwaroywd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.mhx1999.top/Article/details/gttimatxpu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.pycfn.com/Article/details/gtdhqqlafl.html

JS:   resp.ok;  resp.status
来源：http://dali.cdnleiting.top/Article/details/gtnzjlwcmj.html

TS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gtllvkvaop.html

Java: resp.statusCode()
来源：http://dali.zhiwuduotai.top/Article/details/gtrlaiuqej.html

Go:   resp.StatusCode
来源：http://dali.gzhubu.top/Article/details/gtvcqnhhes.html

Ruby: resp.code.to_i
来源：http://dali.jinqigfzy.top/Article/details/gtygnnygiu.html

C#:   (int)resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gtbnyipuee.html

[L08] 并发请求多个地址
来源：http://dali.tianlin.xyz/Article/details/gtymusvrmm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hammf.cn/Article/details/gtkaxpvxbv.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhixingplan.top/Article/details/gtrepfwezn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gtiomdjozr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pycfn.com/Article/details/gtnhcnqbxn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jlsjyb.cn/Article/details/gtnbdssxrn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.pengpengdd.cyou/Article/details/gtaxhyhrqz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.0kj1m.cn/Article/details/gtnadkacac.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tianlin.xyz/Article/details/gtkurbmnkn.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtxxpraqiu.html

M. 命令行 / 进程 / 环境
来源：http://dali.tianlin.xyz/Article/details/gtdlysdoxk.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtieogngmk.html

[M01] 读取命令行参数
来源：http://dali.nanxuanxn.top/Article/details/gtviulqmio.html

Py:   sys.argv[1:]
来源：http://dali.yuxming.cn/Article/details/gthvrsuspi.html

PHP:  $argv;  $argc;
来源：http://dali.tanke756.top/Article/details/gtjkusyrnb.html

JS:   process.argv.slice(2)
来源：http://dali.aibaodan.cn/Article/details/gtkmjmbpkb.html

TS:   process.argv.slice(2)
来源：http://dali.chenlongwang.top/Article/details/gttqppbxwl.html

Java: args 数组（main 方法参数）
来源：http://dali.daria6918.cn/Article/details/gtjrjmdypc.html

Go:   os.Args[1:]
来源：http://dali.ydzc1.top/Article/details/gtdbumwmya.html

Ruby: ARGV
来源：http://dali.chenjidiqi.icu/Article/details/gtncakkisd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.snrcjt.cn/Article/details/gtuqbgtvwv.html

[M02] 读取环境变量
来源：http://dali.jqgufenzy.top/Article/details/gtqhtaqhqb.html

Py:   os.environ.get("HOME")
来源：http://dali.yj20258888.top/Article/details/gtaqjwkvcn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gtmxyiennj.html

JS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gttmaajhdq.html

TS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gtbzhbtlwj.html

Java: System.getenv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtmaalawxi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtjgmyybgv.html

Ruby: ENV["HOME"]
来源：http://dali.daxiang520.top/Article/details/gtsatksxde.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gttbbulaem.html

[M03] 执行外部命令
来源：http://dali.316326.xyz/Article/details/gtngnaduqu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jyoumei.cn/Article/details/gtaococbbv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nanxuanxn.top/Article/details/gtlndqqhou.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gtftoroasn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.quarkkingdee.top/Article/details/gtgagsiitl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinghuilouyu.cn/Article/details/gttpnjxnfy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.daria6918.cn/Article/details/gtixiwdimy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgfzy.top/Article/details/gteieeorqs.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinyuanbaomall.cn/Article/details/gthcknbgbq.html

[M04] 获取当前工作目录
来源：http://dali.jyoumei.cn/Article/details/gturqszxfx.html

Py:   os.getcwd()
来源：http://dali.aibaodan.cn/Article/details/gtcixmfrrr.html

PHP:  getcwd();
来源：http://dali.guowangkeji.top/Article/details/gtnocvwqus.html

JS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gtuvwwqtcs.html

TS:   process.cwd()
来源：http://dali.ivvv.top/Article/details/gtvfkrldse.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.iojbl.cn/Article/details/gtukqjsdug.html

Go:   os.Getwd()
来源：http://dali.gaohongyu789.top/Article/details/gtjkwvtnzt.html

Ruby: Dir.pwd
来源：http://dali.sysykeji.top/Article/details/gtjhzuhord.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pycfn.com/Article/details/gtzzuleyfe.html

[M05] 设置退出码
来源：http://dali.andypj.xyz/Article/details/gtntooeyrv.html

Py:   sys.exit(1)
来源：http://dali.yongpay.top/Article/details/gtpslqkida.html

PHP:  exit(1);
来源：http://dali.yj20258888.top/Article/details/gtspbdghbs.html

JS:   process.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtjczukomi.html

TS:   process.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtokgekiht.html

Java: System.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtuybkubss.html

Go:   os.Exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtaienspln.html

Ruby: exit 1
来源：http://dali.jyoumei.cn/Article/details/gttwarntln.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hywenlv.cn/Article/details/gtefpaxffh.html

[M06] 向标准错误输出
来源：http://dali.zhengqikj.top/Article/details/gtjqhukmzw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.0kj1m.cn/Article/details/gtfivpimnu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.snrcjt.cn/Article/details/gttskpkqgv.html

JS:   console.error("err")
来源：http://dali.hammf.cn/Article/details/gtlogemnak.html

TS:   console.error("err")
来源：http://dali.quarkkingdee.top/Article/details/gtdwkybhta.html

Java: System.err.println("err")
来源：http://dali.pengpengdd.cyou/Article/details/gtzmfegrpf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hywenlv.cn/Article/details/gtahlawvjw.html

Ruby: warn "err"
来源：http://dali.jinqigufen.top/Article/details/gtjzyfrzot.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.haohaochexian.top/Article/details/gtpurxhifw.html

[M07] 判断是否为主入口
来源：http://dali.nanxinkj.top/Article/details/gtamyqcizy.html

Py:   if __name__ == "__main__":
来源：http://dali.aizwys.cn/Article/details/gtjmoyuwum.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.pycfn.com/Article/details/gtfeqisvdf.html

JS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gtkntakywa.html

TS:   require.main === module
来源：http://dali.sysykeji.top/Article/details/gtqzhcylvl.html

Java: public static void main(String[] args)
来源：http://dali.snrcjt.cn/Article/details/gtsmjascvj.html

Go:   func main()
来源：http://dali.guannengcc.top/Article/details/gtpdpfddal.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tanke756.top/Article/details/gtbthvunza.html

C#:   static void Main(string[] args)
来源：http://dali.hysaishi.cn/Article/details/gtuvtijfzi.html

[M08] 获取系统与运行时信息
来源：http://dali.nanxuanxn.top/Article/details/gtezpggswz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sufxvd.cn/Article/details/gtrvkbmshu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cqqwz.cn/Article/details/gtobklbkhu.html

JS:   process.platform;  process.version
来源：http://dali.hywenlv.cn/Article/details/gtpwjfhjzz.html

TS:   process.platform;  process.version
来源：http://dali.jianghu66.top/Article/details/gtfmsqdeok.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.316326.xyz/Article/details/gtjizeumem.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.svipenyu.cn/Article/details/gtmioxwvgu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.daxiang520.top/Article/details/gtexjlxwdf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gzhubu.top/Article/details/gtxdylbruw.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtxnqavojh.html

N. 数据结构与算法
来源：http://dali.birdmap.top/Article/details/gtgfxqatjs.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtrkwolcqi.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgfzy.top/Article/details/gtblmywrkp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtxqlreism.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yuanzhike.top/Article/details/gttxamnluc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sweek.top/Article/details/gtblyameeo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ydzc1.top/Article/details/gttedeloli.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtqsvmzaab.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtyiznlksx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yonumen.top/Article/details/gtmgvcgans.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtbfmebkff.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xuanzx.com/Article/details/gtgmcfhgrp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhiwuduotai.top/Article/details/gtfqcletvl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ehwqpu.com/Article/details/gtijpbxbez.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gtowjemejm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hammf.cn/Article/details/gtoqcriobm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.andypj.xyz/Article/details/gtqyfkeqgq.html

Go:   slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gtqomdgelm.html

Ruby: arr.sort
来源：http://dali.hammf.cn/Article/details/gtyxkloreg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nwbrower.top/Article/details/gtbufczxia.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangtech.top/Article/details/gthhtsttli.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shzxlz.cn/Article/details/gtfwgisarq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hywenlv.cn/Article/details/gtaxwzftax.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxuanxn.top/Article/details/gtkgdvicor.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrxakompx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gogol.net.cn/Article/details/gtxusgdeyv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuanzhike.top/Article/details/gtvwhqceyd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.aizwys.cn/Article/details/gtnhhfrxcq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ppjwa.cn/Article/details/gtodyorlsz.html

[N04] 斐波那契数列
来源：http://dali.guowangkeji.top/Article/details/gtxwkipjjx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvkvzmid.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zdqjudy.top/Article/details/gtbkzucyge.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gtabcocedm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdkpurjxm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nanxinkj.top/Article/details/gtxymxncqq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jlsjyb.cn/Article/details/gtelmgoazr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zycfv.cn/Article/details/gtfwhlpsto.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gtjadyingb.html

[N05] 最大公约数
来源：http://dali.feifeiyinyue.top/Article/details/gtklazzoxh.html

Py:   math.gcd(a, b)
来源：http://dali.316326.xyz/Article/details/gtmosjeunt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtgrcvtrmm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.c1oappe.top/Article/details/gtemirngyz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yongpay.top/Article/details/gtflivbexh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shzxlz.cn/Article/details/gtcqqqouda.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.haohaochexian.top/Article/details/gtvqmlsitj.html

Ruby: a.gcd(b)
来源：http://dali.chenjidiqi.icu/Article/details/gtujhergmi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.316326.xyz/Article/details/gthfyhvxdy.html

[N06] 判断回文字符串
来源：http://dali.hnqzz.top/Article/details/gtefvxdgeo.html

Py:   s == s[::-1]
来源：http://dali.nanxuanxn.top/Article/details/gtjawjaykn.html

PHP:  $s === strrev($s);
来源：http://dali.cashguo.top/Article/details/gtlwztjtql.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtankvzdga.html

TS:   s === [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gtiqzphurs.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhoulong.xyz/Article/details/gtecsqahfe.html

Go:   // 双指针从两端比较
来源：http://dali.birdmap.top/Article/details/gtdtbfllbi.html

Ruby: s == s.reverse
来源：http://dali.chenlongwang.top/Article/details/gteyohvifs.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cdnleiting.top/Article/details/gtcypzxbvz.html

[N07] 两数之和（返回下标）
来源：http://dali.kuanghao11.cn/Article/details/gtgxlrjsjr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yongpay.top/Article/details/gtnsxfycyz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ivvv.top/Article/details/gttwlkvzjy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xinyue.icu/Article/details/gtqeobtcpp.html

TS:   // 手写 Map<string, number>
来源：http://dali.wangdashe.top/Article/details/gtrmdexkll.html

Java: // 手写 HashMap
来源：http://dali.zhongyouzk.top/Article/details/gtozbslavl.html

Go:   // 手写 map[int]int
来源：http://dali.jinqigufen.top/Article/details/gtnilkcrwd.html

Ruby: // 手写 Hash
来源：http://dali.hfpthk.cn/Article/details/gtvseumxrf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shzxlz.cn/Article/details/gtyiddtcpt.html

[N08] 生成全排列
来源：http://dali.yuanzhike.top/Article/details/gtsgisgweh.html

Py:   itertools.permutations(arr)
来源：http://dali.haohaochexian.top/Article/details/gtwbftquse.html

PHP:  // 手写递归交换
来源：http://dali.nanxinkj.top/Article/details/gturigmhgf.html

JS:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtnawgpduz.html

TS:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtwtmcywyi.html

Java: // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtaxwajsrr.html

Go:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtrctswamg.html

Ruby: arr.permutation.to_a
来源：http://dali.ydzc1.top/Article/details/gtgkysudhc.html

C#:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtzahygorc.html

[N09] 栈与队列
来源：http://dali.yj20258888.top/Article/details/gtlxuddfjc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.fzhhl.top/Article/details/gtoejdzdfb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtzdaaxhhf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gtgdsdgwkz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.dianchejie.cn/Article/details/gticsbdlyv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xinyue.icu/Article/details/gtvygwsccz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhixingplan.top/Article/details/gtumvwaxsh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gtzpblgeod.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.c1oappe.top/Article/details/gtoaextvqg.html

[N10] 链表节点定义
来源：http://dali.yvedp.cn/Article/details/gtrsfknrrs.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zdqjudy.top/Article/details/gttvlvougp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ivvv.top/Article/details/gtdpgbjdda.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jqgfzy.top/Article/details/gtjxrbmqrj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.bjfxy.top/Article/details/gtahyikily.html

Java: class Node { int v; Node next; }
来源：http://dali.ppjwa.cn/Article/details/gtpwlkbsgm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.haohaochexian.top/Article/details/gtzpsgectr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cdnleiting.top/Article/details/gtypgtaqkz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zycfv.cn/Article/details/gtiwdlnycz.html

[N11] 二叉树中序遍历
来源：http://dali.sufxvd.cn/Article/details/gtgphqndsf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hnxiangtu.top/Article/details/gtrxqfxnpv.html

PHP:  // 手写递归函数
来源：http://dali.sufxvd.cn/Article/details/gtweewfvxh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrjgbzhf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cheryme.top/Article/details/gthtndepay.html

Java: // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gtiobnhziv.html

Go:   // 手写递归
来源：http://dali.jianghu66.top/Article/details/gtzqwvmzof.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhoulong.xyz/Article/details/gtskttbdci.html

C#:   // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gteirkeoce.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ppjwa.cn/Article/details/gttqyzcbfy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yuxming.cn/Article/details/gtulxjupug.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.tanke756.top/Article/details/gttbogquol.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jianghu66.top/Article/details/gtemgeuxox.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.316326.xyz/Article/details/gtavxengvw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhiwuduotai.top/Article/details/gthehbztcc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.wangdashe.top/Article/details/gtzokstpcl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.snrcjt.cn/Article/details/gtrqytkanh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hammf.cn/Article/details/gtctlecglc.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtnqpwjjne.html

O. 并发与异步
来源：http://dali.havefunace.top/Article/details/gtcvxavium.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtmgttzdqu.html

[O01] 启动一个线程
来源：http://dali.cheryme.top/Article/details/gtanwfwsgx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.fengsongda.top/Article/details/gtihtizcvm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxivascs.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nwbrower.top/Article/details/gtgjvinlbc.html

TS:   // 同 JS
来源：http://dali.316326.xyz/Article/details/gtdqmdijyu.html

Java: new Thread(() -> f()).start()
来源：http://dali.yonumen.top/Article/details/gtliqrwidl.html

Go:   go f()
来源：http://dali.bjfxy.top/Article/details/gtmvexdemu.html

Ruby: Thread.new { f }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcoyumjsl.html

C#:   Task.Run(() => F());
来源：http://dali.ehwqpu.com/Article/details/gtkddbduds.html

[O02] 使用线程池
来源：http://dali.sufxvd.cn/Article/details/gtlphmfrja.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yueranfly.top/Article/details/gtzkkrakta.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangtech.top/Article/details/gtbrhhigbg.html

JS:   // worker_threads 线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdsbbrfk.html

TS:   // worker_threads 线程池
来源：http://dali.aibaodan.cn/Article/details/gtxflmmzpx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.quarkkingdee.top/Article/details/gtqonvjjqc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xuanzx.com/Article/details/gtttxnkgga.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.pengpengdd.cyou/Article/details/gtqxmzpkry.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenzaomai.com/Article/details/gtsdoekpbn.html

[O03] 加锁保护共享数据
来源：http://dali.9152youxi.cn/Article/details/gthdaestwx.html

Py:   with lock: shared += 1
来源：http://dali.gotoacloud.top/Article/details/gtzniihhex.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhengqikj.top/Article/details/gtypdktjoo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.9152youxi.cn/Article/details/gtakwfieta.html

TS:   // 同 JS
来源：http://dali.shuidangran.top/Article/details/gtkluewgea.html

Java: synchronized (this) { shared++; }
来源：http://dali.shuidangran.top/Article/details/gtjenvscbg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xinyue.icu/Article/details/gtqmzroetx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yonumen.top/Article/details/gtjkjclccd.html

C#:   lock (gate) { shared++; }
来源：http://dali.yueranfly.top/Article/details/gtseqeujpn.html

[O04] 定义异步函数并等待
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijqpoaqp.html

Py:   async def f():⏎    await g()
来源：http://dali.fengsongda.top/Article/details/gtsfdcqbte.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gotoacloud.top/Article/details/gtjndumjip.html

JS:   async function f() { await g(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwmagnbv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gtvntxfswh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.meibo888.top/Article/details/gtmkkqybaa.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shanyushiyangtech.top/Article/details/gttmxsyetd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.snrcjt.cn/Article/details/gtukwxdwbm.html

C#:   async Task F() { await G(); }
来源：http://dali.meibo888.top/Article/details/gtznutcsio.html

[O05] 并发执行并等待全部完成
来源：http://dali.haohaochexian.top/Article/details/gtzobhkqmt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sxryk.cn/Article/details/gtjunobsug.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cashguo.top/Article/details/gticovfrci.html

JS:   await Promise.all(tasks)
来源：http://dali.xziqi.cn/Article/details/gtextqueee.html

TS:   await Promise.all(tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtghsjvcex.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.daxiang520.top/Article/details/gtusyjrdny.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.daxiang520.top/Article/details/gtagjmeltb.html

Ruby: threads.map(&:join)
来源：http://dali.cashguo.top/Article/details/gtadudxsck.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ppjwa.cn/Article/details/gtmxkktcjw.html

[O06] 使用进程池
来源：http://dali.fengsongda.top/Article/details/gthtnabyvx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.wangdashe.top/Article/details/gtwjxjywei.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinqigfzy.top/Article/details/gtzjerixid.html

JS:   // child_process / cluster 模块
来源：http://dali.c1oappe.top/Article/details/gtvktxsfkp.html

TS:   // child_process / cluster 模块
来源：http://dali.aibaodan.cn/Article/details/gtjrzmumdk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yongpay.top/Article/details/gtfibycanv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj20258888.top/Article/details/gtgrlynxgh.html

Ruby: // fork 块
来源：http://dali.vqdsnc.cn/Article/details/gtewtaglzz.html

C#:   Parallel.For
来源：http://dali.guowangkeji.top/Article/details/gtrqpywaxn.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtruzvezls.html

P. 常用工具函数
来源：http://dali.havefunace.top/Article/details/gtmbjoeqws.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtwntpoudt.html


<!-- 参考信息 -->