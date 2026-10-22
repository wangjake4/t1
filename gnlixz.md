代发 wailian999

[L03] 设置自定义请求头
来源：http://dali.yj20258.top/Article/details/gtvwvxzvgr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.c1oappe.top/Article/details/gtkhptqzcl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbqbyhcw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cdnleiting.top/Article/details/gtobpqllsf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuxming.cn/Article/details/gtgjdlaoan.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.mhx1999.top/Article/details/gtfvqgrcov.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xuanzx.com/Article/details/gtlrzvdyga.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jqgfzy.top/Article/details/gtwgzyjvny.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gtnffsukce.html

[L04] 设置超时
来源：http://dali.zhixingplan.top/Article/details/gttedvonqs.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuanzx.com/Article/details/gtyhorezus.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hnxiangtu.top/Article/details/gtlmtfjdye.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gtrzkzbnjn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zdqjudy.top/Article/details/gtugtfuhig.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zycfv.cn/Article/details/gtzrviafhs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.snrcjt.cn/Article/details/gtirfzuylc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shuidangran.top/Article/details/gtzmjzaaia.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.vqdsnc.cn/Article/details/gtictxhrmd.html

[L05] 上传文件（multipart）
来源：http://dali.sufxvd.cn/Article/details/gtdhpndfcp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhiwuduotai.top/Article/details/gtxbgdqkxx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtncwpjtci.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.vqdsnc.cn/Article/details/gtwkpyrhde.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.vqdsnc.cn/Article/details/gtjhvpweub.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tian-w.cn/Article/details/gtyfxyoriz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.haohaochexian.top/Article/details/gtzjiseyed.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sweek.top/Article/details/gtdmsoimwc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtemyxsyvn.html

[L06] 解析响应为 JSON
来源：http://dali.sysykeji.top/Article/details/gtrlxawzqb.html

Py:   resp.json()
来源：http://dali.jianghu66.top/Article/details/gtilgtfhgn.html

PHP:  json_decode($body, true);
来源：http://dali.daria6918.cn/Article/details/gtstmfxafw.html

JS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtycpxeuxg.html

TS:   await resp.json()
来源：http://dali.yueranfly.top/Article/details/gtjlcvlijr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.fengsongda.top/Article/details/gtocxudnsp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jlsjyb.cn/Article/details/gtqfbiryph.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnxiangtu.top/Article/details/gtnyppeadi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj20258888.top/Article/details/gthdeeniqn.html

[L07] 处理 HTTP 状态码
来源：http://dali.smart0.xyz/Article/details/gtxelepedq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jianghu66.top/Article/details/gturnfyxtm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.daria6918.cn/Article/details/gtceysdebx.html

JS:   resp.ok;  resp.status
来源：http://dali.jinghuilouyu.cn/Article/details/gtykylmymi.html

TS:   resp.ok;  resp.status
来源：http://dali.tianlin.xyz/Article/details/gtqlgjmtbs.html

Java: resp.statusCode()
来源：http://dali.wangdashe.top/Article/details/gtvknudcdz.html

Go:   resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gtbjfsnlek.html

Ruby: resp.code.to_i
来源：http://dali.bjfxy.top/Article/details/gtbchxcosu.html

C#:   (int)resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gtwymsxbrn.html

[L08] 并发请求多个地址
来源：http://dali.jinqigfzy.top/Article/details/gtjxjtwknq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.svipenyu.cn/Article/details/gtskeifuur.html

PHP:  curl_multi_init() 系列
来源：http://dali.feifeiyinyue.top/Article/details/gtlotvpujb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gtuhnufflc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gtddvssrpb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cdnleiting.top/Article/details/gtgkyehqqv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xylfe.cn/Article/details/gtdvwqnkdd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gtiwjehjxq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aibaodan.cn/Article/details/gtdahvobyj.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtmwohukwt.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhixingplan.top/Article/details/gtepsmpqnv.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtbjwoavqd.html

[M01] 读取命令行参数
来源：http://dali.tanke756.top/Article/details/gtrqpazbrk.html

Py:   sys.argv[1:]
来源：http://dali.sxryk.cn/Article/details/gtmuckxrpr.html

PHP:  $argv;  $argc;
来源：http://dali.zdqjudy.top/Article/details/gtjtstmtur.html

JS:   process.argv.slice(2)
来源：http://dali.meibo888.top/Article/details/gtealxhzfn.html

TS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtvescsvjf.html

Java: args 数组（main 方法参数）
来源：http://dali.jlsjyb.cn/Article/details/gtfsugstcf.html

Go:   os.Args[1:]
来源：http://dali.zhongyouzk.top/Article/details/gtagcbyejr.html

Ruby: ARGV
来源：http://dali.yuanzhike.top/Article/details/gtiysjgzhy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gtwksvstwx.html

[M02] 读取环境变量
来源：http://dali.sysykeji.top/Article/details/gtbkoywtvx.html

Py:   os.environ.get("HOME")
来源：http://dali.cheryme.top/Article/details/gtpbwcarwf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gtdwsfknvm.html

JS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gthgwzycxt.html

TS:   process.env.HOME
来源：http://dali.meibo888.top/Article/details/gtmizthenb.html

Java: System.getenv("HOME")
来源：http://dali.wangdashe.top/Article/details/gtmqcotqxt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtcsrcrxyl.html

Ruby: ENV["HOME"]
来源：http://dali.dianchejie.cn/Article/details/gtvcbptitx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shzxlz.cn/Article/details/gtudxtdgae.html

[M03] 执行外部命令
来源：http://dali.jyoumei.cn/Article/details/gtlvyfcfmr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shuidangran.top/Article/details/gtipcvrvvr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxmodjgts.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zycfv.cn/Article/details/gtqjguczpu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gtzytuobmj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.mhx1999.top/Article/details/gtjduhdglf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ppjwa.cn/Article/details/gtvblmzlyw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hfpthk.cn/Article/details/gtvavjiizc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nwbrower.top/Article/details/gtldcemgwi.html

[M04] 获取当前工作目录
来源：http://dali.0kj1m.cn/Article/details/gtwujtxiqw.html

Py:   os.getcwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxmujoxbk.html

PHP:  getcwd();
来源：http://dali.redwolf501.top/Article/details/gtbjzbmczg.html

JS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwqracbyt.html

TS:   process.cwd()
来源：http://dali.zhiwuduotai.top/Article/details/gtzcjuimgq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xziqi.cn/Article/details/gtkdpkamkh.html

Go:   os.Getwd()
来源：http://dali.vqdsnc.cn/Article/details/gtywhlnizi.html

Ruby: Dir.pwd
来源：http://dali.tian-w.cn/Article/details/gtlunimubd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jqgufenzy.top/Article/details/gtlfqoqaqh.html

[M05] 设置退出码
来源：http://dali.ppjwa.cn/Article/details/gtauyfzqxi.html

Py:   sys.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtndcdqxdj.html

PHP:  exit(1);
来源：http://dali.yvedp.cn/Article/details/gtzguncyrg.html

JS:   process.exit(1)
来源：http://dali.hnqzz.top/Article/details/gtfmlaieog.html

TS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtjplncvtq.html

Java: System.exit(1)
来源：http://dali.yuxming.cn/Article/details/gtfwxlbtvv.html

Go:   os.Exit(1)
来源：http://dali.yueranfly.top/Article/details/gtmgzjrkbs.html

Ruby: exit 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlnunncfh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.kuanghao11.cn/Article/details/gtkpjohukd.html

[M06] 向标准错误输出
来源：http://dali.zdqjudy.top/Article/details/gtrhttqfri.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgufenzy.top/Article/details/gtyilvqncs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.fzhhl.top/Article/details/gtarvmvasb.html

JS:   console.error("err")
来源：http://dali.chenlongwang.top/Article/details/gtdijezyzs.html

TS:   console.error("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfemkedkw.html

Java: System.err.println("err")
来源：http://dali.cqqwz.cn/Article/details/gtywkmqpsa.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.iojbl.cn/Article/details/gtttcypdpg.html

Ruby: warn "err"
来源：http://dali.xylfe.cn/Article/details/gtwvznvbxp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cdnleiting.top/Article/details/gtkagnqevj.html

[M07] 判断是否为主入口
来源：http://dali.dashuyun.cn/Article/details/gtbrpcxydg.html

Py:   if __name__ == "__main__":
来源：http://dali.pycfn.com/Article/details/gtanrgioar.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.vqdsnc.cn/Article/details/gtjjxqubfi.html

JS:   require.main === module
来源：http://dali.jqgfzy.top/Article/details/gtxsdqpnpa.html

TS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gtoffiwapr.html

Java: public static void main(String[] args)
来源：http://dali.jinqigufen.top/Article/details/gtwlkamdjo.html

Go:   func main()
来源：http://dali.xylfe.cn/Article/details/gtebfjthyh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.fengsongda.top/Article/details/gtpvyauchr.html

C#:   static void Main(string[] args)
来源：http://dali.vqdsnc.cn/Article/details/gtigprlhge.html

[M08] 获取系统与运行时信息
来源：http://dali.316326.xyz/Article/details/gtpvlfnxlh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.9152youxi.cn/Article/details/gtcfuzqorq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sufxvd.cn/Article/details/gtlrzzsddd.html

JS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gtsjpelpur.html

TS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gtkzimkvlf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxinkj.top/Article/details/gtaholwlsl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.9152youxi.cn/Article/details/gtzmmdqqbv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.meibo888.top/Article/details/gtbjcnhgsk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guowangkeji.top/Article/details/gtshakazom.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtusefytrc.html

N. 数据结构与算法
来源：http://dali.chenzaomai.com/Article/details/gtbclebniq.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtilvodyzz.html

[N01] 二分查找（有序数组）
来源：http://dali.shanyushiyangtech.top/Article/details/gtgedsqwst.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtcyqegtmw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yangfankeji.com/Article/details/gtepliirlh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtxzqjccqd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gtrxfsbovx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlniwkdvf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtkdmuzhrz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xylfe.cn/Article/details/gtvfomxqvp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtqbyuzrpo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jyoumei.cn/Article/details/gtjjumbjbn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.snrcjt.cn/Article/details/gtefzvzuee.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hnqzz.top/Article/details/gtrdswbain.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gtxfclgpyt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gtljhppsai.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.vqdsnc.cn/Article/details/gtqmzqlpfg.html

Go:   slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttogashtr.html

Ruby: arr.sort
来源：http://dali.ydzc1.top/Article/details/gtmpcvwmjf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gaohongyu789.top/Article/details/gtkwhhbrwo.html

[N03] 快速排序（分治示例）
来源：http://dali.jinghuilouyu.cn/Article/details/gtabthadbn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.birdmap.top/Article/details/gttxbbybvk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zdqjudy.top/Article/details/gtqkbxyhjg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tanke756.top/Article/details/gtdyvwalux.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenlongwang.top/Article/details/gtamdakiby.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sysykeji.top/Article/details/gtxpfpfdkd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ivvv.top/Article/details/gtfdqhrgyn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nanxuanxn.top/Article/details/gtimmmvjau.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.andypj.xyz/Article/details/gtbczkjvvp.html

[N04] 斐波那契数列
来源：http://dali.hongshengwenyu.top/Article/details/gtygpyvkiw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.andypj.xyz/Article/details/gtjpingccq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.dashuyun.cn/Article/details/gtybfrrzgz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gtgtagxapb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtydejjjqh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hnqzz.top/Article/details/gtpnzkozcu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinqigfzy.top/Article/details/gtigkapnfh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.birdmap.top/Article/details/gtvtrqdica.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gtjdlkkrfk.html

[N05] 最大公约数
来源：http://dali.jqgfzy.top/Article/details/gttsadgsnz.html

Py:   math.gcd(a, b)
来源：http://dali.gotoacloud.top/Article/details/gtwdrhksnw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtenkaukmi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yanxiufei.cn/Article/details/gtsmsocogz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sufxvd.cn/Article/details/gtwbegnkzw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sweek.top/Article/details/gtecpsnbmb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinqigfzy.top/Article/details/gtyubwfmft.html

Ruby: a.gcd(b)
来源：http://dali.9152youxi.cn/Article/details/gtkgtggzzw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenlongwang.top/Article/details/gtquydfdgd.html

[N06] 判断回文字符串
来源：http://dali.yj20258.top/Article/details/gtxqzalzxp.html

Py:   s == s[::-1]
来源：http://dali.bjfxy.top/Article/details/gtwidflzod.html

PHP:  $s === strrev($s);
来源：http://dali.havefunace.top/Article/details/gtowkibclq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtmwjunpxs.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gtchjzqfra.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zycfv.cn/Article/details/gtaknqoadx.html

Go:   // 双指针从两端比较
来源：http://dali.zycfv.cn/Article/details/gtqvwupbrd.html

Ruby: s == s.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gtqjxdoqie.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.dianchejie.cn/Article/details/gtwdzjbrzp.html

[N07] 两数之和（返回下标）
来源：http://dali.yj20258888.top/Article/details/gtxpcjckzy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yongpay.top/Article/details/gtjgtaznzx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxoosczf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ehwqpu.com/Article/details/gtvakdnovp.html

TS:   // 手写 Map<string, number>
来源：http://dali.yongpay.top/Article/details/gtapshfjom.html

Java: // 手写 HashMap
来源：http://dali.fengsongda.top/Article/details/gtydavnbch.html

Go:   // 手写 map[int]int
来源：http://dali.yonumen.top/Article/details/gtlugbhaab.html

Ruby: // 手写 Hash
来源：http://dali.hammf.cn/Article/details/gtugjvtdwb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hongshengwenyu.top/Article/details/gtafdenicd.html

[N08] 生成全排列
来源：http://dali.tianlin.xyz/Article/details/gtdwhgwzmy.html

Py:   itertools.permutations(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtcihmzjbs.html

PHP:  // 手写递归交换
来源：http://dali.nanxuanxn.top/Article/details/gtushysnpf.html

JS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtfounpdcm.html

TS:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtvcmscpbi.html

Java: // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdflknhl.html

Go:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gttbsvxruv.html

Ruby: arr.permutation.to_a
来源：http://dali.ivvv.top/Article/details/gtbxgmgahb.html

C#:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtxkhymvmk.html

[N09] 栈与队列
来源：http://dali.pycfn.com/Article/details/gtvgkfexrl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.snrcjt.cn/Article/details/gtjgobktgs.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.dianchejie.cn/Article/details/gtcltthbzj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gtojzvzcly.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfddydaz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.dianchejie.cn/Article/details/gtyqutkoog.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.9152youxi.cn/Article/details/gtmkrbnbrq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gtpvwlgjtz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.birdmap.top/Article/details/gtwogxbrfc.html

[N10] 链表节点定义
来源：http://dali.yueranfly.top/Article/details/gtqqynlqfm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.feifeiyinyue.top/Article/details/gtcvqoptwb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nanxuanxn.top/Article/details/gtqesgowtq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gzhubu.top/Article/details/gtzduvoifd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cqqwz.cn/Article/details/gtypnevtaf.html

Java: class Node { int v; Node next; }
来源：http://dali.0kj1m.cn/Article/details/gtzngfvpoz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sweek.top/Article/details/gthqjwzvqp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuxming.cn/Article/details/gtxrnyszzn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj20258888.top/Article/details/gtrpejyrql.html

[N11] 二叉树中序遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtosdfxozr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jyoumei.cn/Article/details/gtnlvkatfy.html

PHP:  // 手写递归函数
来源：http://dali.9152youxi.cn/Article/details/gtskdwwllj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhixingplan.top/Article/details/gtsoorpfgz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuetiantiany.cn/Article/details/gtmumiimrc.html

Java: // 手写递归
来源：http://dali.tanke756.top/Article/details/gthgnbzlib.html

Go:   // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gtwakfqgya.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yvedp.cn/Article/details/gtefpvkeva.html

C#:   // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gtdsklmrzn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gaohongyu789.top/Article/details/gtqkhyyimw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinqigufen.top/Article/details/gtyjukhqhn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jqgfzy.top/Article/details/gtuuotwali.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenjidiqi.icu/Article/details/gtumggljgh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cdnleiting.top/Article/details/gtccyzxqml.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cheryme.top/Article/details/gtvcotifps.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yvedp.cn/Article/details/gtfdrloccy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hammf.cn/Article/details/gtowlenmys.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jianghu66.top/Article/details/gtelzlmnsi.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtwkwfznwz.html

O. 并发与异步
来源：http://dali.shuidangran.top/Article/details/gttybnsgqn.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtnfrykqkv.html

[O01] 启动一个线程
来源：http://dali.dianchejie.cn/Article/details/gtkxxegkvf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hysaishi.cn/Article/details/gtwlrahesg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shuidangran.top/Article/details/gtslssbnuv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nwbrower.top/Article/details/gtkcidlvwd.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gtclyjnwcv.html

Java: new Thread(() -> f()).start()
来源：http://dali.ybcxt.top/Article/details/gtiakfcyln.html

Go:   go f()
来源：http://dali.cheryme.top/Article/details/gtmqqhbanu.html

Ruby: Thread.new { f }
来源：http://dali.shangyingyoupin.top/Article/details/gturamgtie.html

C#:   Task.Run(() => F());
来源：http://dali.shuidangran.top/Article/details/gtqcdvdtcl.html

[O02] 使用线程池
来源：http://dali.jiagoushi.top/Article/details/gtofvqefep.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinqigufen.top/Article/details/gthmiybegl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yueranfly.top/Article/details/gtfdnufmyh.html

JS:   // worker_threads 线程池
来源：http://dali.iojbl.cn/Article/details/gthlafsxql.html

TS:   // worker_threads 线程池
来源：http://dali.ybcxt.top/Article/details/gthqnfiwjg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yvedp.cn/Article/details/gtwfcymqof.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj20258888.top/Article/details/gtimzdztpz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zdqjudy.top/Article/details/gtsumyhocc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cucudq.cn/Article/details/gtekxekvby.html

[O03] 加锁保护共享数据
来源：http://dali.fengsongda.top/Article/details/gtridwqphw.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gtltqpcxee.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.fengsongda.top/Article/details/gtydsjftgo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tian-w.cn/Article/details/gthiteipdp.html

TS:   // 同 JS
来源：http://dali.jinqigfzy.top/Article/details/gtbrpazsnn.html

Java: synchronized (this) { shared++; }
来源：http://dali.xylfe.cn/Article/details/gtacywmuom.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hammf.cn/Article/details/gtquhmhyhj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hnxiangtu.top/Article/details/gtwidevqwc.html

C#:   lock (gate) { shared++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjalpumi.html

[O04] 定义异步函数并等待
来源：http://dali.daria6918.cn/Article/details/gtoqvapxbn.html

Py:   async def f():⏎    await g()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtirhssdsh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxycbbsyu.html

JS:   async function f() { await g(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxrzyvyxh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj202588.top/Article/details/gtrtrposzl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yonumen.top/Article/details/gtnymblbaq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.daxiang520.top/Article/details/gtpgwixkjw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jqgufenzy.top/Article/details/gtdxqvkjaz.html

C#:   async Task F() { await G(); }
来源：http://dali.zdqjudy.top/Article/details/gtgyatyjww.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhixingplan.top/Article/details/gtszgncvmb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gtxhzumjjh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.svipenyu.cn/Article/details/gtgigpdsww.html

JS:   await Promise.all(tasks)
来源：http://dali.yangfankeji.com/Article/details/gtkewejgyp.html

TS:   await Promise.all(tasks)
来源：http://dali.zhixingplan.top/Article/details/gtdbtavwec.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yanxiufei.cn/Article/details/gtpnhdjsgo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.andypj.xyz/Article/details/gtrzzhmgis.html

Ruby: threads.map(&:join)
来源：http://dali.iojbl.cn/Article/details/gtafudkupj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthlnhhiok.html

[O06] 使用进程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtorfayvle.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xylfe.cn/Article/details/gtohcwkpps.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gotoacloud.top/Article/details/gtrkoublfg.html

JS:   // child_process / cluster 模块
来源：http://dali.xylfe.cn/Article/details/gtdnmaeyxb.html

TS:   // child_process / cluster 模块
来源：http://dali.nanxinkj.top/Article/details/gtubdtuezm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwbrezekm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhengqikj.top/Article/details/gtbuufhogd.html

Ruby: // fork 块
来源：http://dali.shzxlz.cn/Article/details/gtxhsdapbv.html

C#:   Parallel.For
来源：http://dali.wangdashe.top/Article/details/gtitfluonh.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtlnshnsko.html

P. 常用工具函数
来源：http://dali.zycfv.cn/Article/details/gtylesmmjm.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtelmctllr.html


<!-- 参考信息 -->