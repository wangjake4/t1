代发 wailian999

Go:   resp, err := http.Get(url)
来源：http://dali.chenzaomai.com/Article/details/gtixygcmxb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhengqikj.top/Article/details/gtwywnhlep.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xziqi.cn/Article/details/gtbgkgfqvg.html

[L02] 发送 POST JSON
来源：http://dali.nanxuanxn.top/Article/details/gtyqbjfzrq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gtyvqhxkxe.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ppjwa.cn/Article/details/gtyvhcjohs.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxuanxn.top/Article/details/gtdpngxnav.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.birdmap.top/Article/details/gtnvlphsor.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gaohongyu789.top/Article/details/gtkoaishjf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhoulong.xyz/Article/details/gthzuamzib.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgfzy.top/Article/details/gtuluplcpc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guannengcc.top/Article/details/gthixvtkej.html

[L03] 设置自定义请求头
来源：http://dali.guannengcc.top/Article/details/gtwavhaxny.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangtech.top/Article/details/gtmqvjkwti.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yuxming.cn/Article/details/gtihgkbyvc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cucudq.cn/Article/details/gttpqcqzqv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shuidangran.top/Article/details/gtsekfdfaf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hfpthk.cn/Article/details/gtkkqfiics.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zycfv.cn/Article/details/gtwjnrerqj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258.top/Article/details/gtbuqgehmc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gtyrzdoprd.html

[L04] 设置超时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxzukrdm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhoulong.xyz/Article/details/gtowvyqcdp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ppjwa.cn/Article/details/gtqdlxqswl.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenzaomai.com/Article/details/gtgmagrgij.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gtwkstjgeg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.aibaodan.cn/Article/details/gtppqngzvx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fengsongda.top/Article/details/gtptjhakji.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.mhx1999.top/Article/details/gtduddgfbj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xylfe.cn/Article/details/gtsnxaurji.html

[L05] 上传文件（multipart）
来源：http://dali.c1oappe.top/Article/details/gtexxkolzd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cucudq.cn/Article/details/gtsuokftim.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.haohaochexian.top/Article/details/gtznhuqqrf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zycfv.cn/Article/details/gtcwjnnxsy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigufen.top/Article/details/gtwycdzpbk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xuanzx.com/Article/details/gtgfwibbjt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.feifeiyinyue.top/Article/details/gtmmzszaal.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.guannengcc.top/Article/details/gtcbwyuskd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtoyecaamc.html

[L06] 解析响应为 JSON
来源：http://dali.shangyingyoupin.top/Article/details/gtqoieowid.html

Py:   resp.json()
来源：http://dali.havefunace.top/Article/details/gtcxhznnkb.html

PHP:  json_decode($body, true);
来源：http://dali.vqdsnc.cn/Article/details/gtzhjxxfcz.html

JS:   await resp.json()
来源：http://dali.yj202588.top/Article/details/gtmbmomhrs.html

TS:   await resp.json()
来源：http://dali.guowangkeji.top/Article/details/gtvnxcknlc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jqgfzy.top/Article/details/gtwahannrc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cdnleiting.top/Article/details/gtyvzouhfo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ehwqpu.com/Article/details/gtkupnwlgf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.kuanghao11.cn/Article/details/gtieyzpwgh.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhengqikj.top/Article/details/gtfhsnvxbe.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.redwolf501.top/Article/details/gtdgulfkdz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqupehuqf.html

JS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gtgdwxlsto.html

TS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gtqewejvpo.html

Java: resp.statusCode()
来源：http://dali.yueranfly.top/Article/details/gtfqwhtkrf.html

Go:   resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gtflpbrzxx.html

Ruby: resp.code.to_i
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnnfeacql.html

C#:   (int)resp.StatusCode
来源：http://dali.316326.xyz/Article/details/gtvnkcqgzc.html

[L08] 并发请求多个地址
来源：http://dali.kuanghao11.cn/Article/details/gtsxdmnxoq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.dianchejie.cn/Article/details/gtqddepxhh.html

PHP:  curl_multi_init() 系列
来源：http://dali.dashuyun.cn/Article/details/gtnjglszyc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zycfv.cn/Article/details/gtloskyphj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gtvxntlivk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sysykeji.top/Article/details/gtgadufhdk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.fengsongda.top/Article/details/gtupacdbjk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenjidiqi.icu/Article/details/gtxdtojxjk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.meibo888.top/Article/details/gtyswdyfos.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtsnbmhevl.html

M. 命令行 / 进程 / 环境
来源：http://dali.xuetiantiany.cn/Article/details/gtnrfvuxsa.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtiajujrcp.html

[M01] 读取命令行参数
来源：http://dali.hywenlv.cn/Article/details/gtrgqxjgmm.html

Py:   sys.argv[1:]
来源：http://dali.dianchejie.cn/Article/details/gtzdfdtpmx.html

PHP:  $argv;  $argc;
来源：http://dali.yj20258.top/Article/details/gtcsjwdpxu.html

JS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gtljqoihib.html

TS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gtkavczkra.html

Java: args 数组（main 方法参数）
来源：http://dali.cheryme.top/Article/details/gtrzajmjgk.html

Go:   os.Args[1:]
来源：http://dali.iojbl.cn/Article/details/gtwqbbfpdb.html

Ruby: ARGV
来源：http://dali.sweek.top/Article/details/gtopqhycls.html

C#:   args 数组（Main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gtijfheabn.html

[M02] 读取环境变量
来源：http://dali.zhixingplan.top/Article/details/gtijwmgsvf.html

Py:   os.environ.get("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtrvqbgumz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gtyueoiwib.html

JS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gtedtdngtf.html

TS:   process.env.HOME
来源：http://dali.kuanghao11.cn/Article/details/gtddsuyyls.html

Java: System.getenv("HOME")
来源：http://dali.yj20258.top/Article/details/gtmidnhivn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sxryk.cn/Article/details/gtkjxtmzhr.html

Ruby: ENV["HOME"]
来源：http://dali.cheryme.top/Article/details/gtvitypkey.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gtghrjbysm.html

[M03] 执行外部命令
来源：http://dali.pycfn.com/Article/details/gtjpabwmkk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhoulong.xyz/Article/details/gtltwgsxbp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tian-w.cn/Article/details/gthatlqcgv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dianchejie.cn/Article/details/gtaawnhbke.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtfzjowlrl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.wangshuangyany.cn/Article/details/gthldauyxt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenlongwang.top/Article/details/gtgxjksmuh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cqqwz.cn/Article/details/gtpsmdqgwu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinqigufen.top/Article/details/gtydwwummp.html

[M04] 获取当前工作目录
来源：http://dali.ehwqpu.com/Article/details/gtylteeuvw.html

Py:   os.getcwd()
来源：http://dali.zhiwuduotai.top/Article/details/gtqfuihcue.html

PHP:  getcwd();
来源：http://dali.9152youxi.cn/Article/details/gtqfcjooke.html

JS:   process.cwd()
来源：http://dali.aizwys.cn/Article/details/gtkqxpoftk.html

TS:   process.cwd()
来源：http://dali.aizwys.cn/Article/details/gtemhmhpjf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gzhubu.top/Article/details/gtdvampenw.html

Go:   os.Getwd()
来源：http://dali.chenlongwang.top/Article/details/gttltqksxv.html

Ruby: Dir.pwd
来源：http://dali.iojbl.cn/Article/details/gtucwllpnc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.snrcjt.cn/Article/details/gtmeqjsutr.html

[M05] 设置退出码
来源：http://dali.ivvv.top/Article/details/gtepvwclvy.html

Py:   sys.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtpfrxdrgq.html

PHP:  exit(1);
来源：http://dali.redwolf501.top/Article/details/gtedoedkwu.html

JS:   process.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtfixwgeau.html

TS:   process.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtsyaoipfa.html

Java: System.exit(1)
来源：http://dali.sweek.top/Article/details/gtbtobjoah.html

Go:   os.Exit(1)
来源：http://dali.fzhhl.top/Article/details/gtdfycvesh.html

Ruby: exit 1
来源：http://dali.hywenlv.cn/Article/details/gtcnxhwwvo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sweek.top/Article/details/gthyjbtyeh.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gtpawuyyfu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yonumen.top/Article/details/gtftpbbwhv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.dashuyun.cn/Article/details/gtwxrrlxef.html

JS:   console.error("err")
来源：http://dali.daria6918.cn/Article/details/gttganxdrq.html

TS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gtwmfgcmff.html

Java: System.err.println("err")
来源：http://dali.dianchejie.cn/Article/details/gtrchcnofc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.iojbl.cn/Article/details/gtcdvwjabl.html

Ruby: warn "err"
来源：http://dali.hywenlv.cn/Article/details/gtdeslmyog.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zdqjudy.top/Article/details/gtmbtledgp.html

[M07] 判断是否为主入口
来源：http://dali.yanxiufei.cn/Article/details/gteihtyitb.html

Py:   if __name__ == "__main__":
来源：http://dali.gzhubu.top/Article/details/gtnfxvntvk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.andypj.xyz/Article/details/gtsbrzhrsk.html

JS:   require.main === module
来源：http://dali.shanyushiyangtech.top/Article/details/gtywkczzwi.html

TS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gtvperohob.html

Java: public static void main(String[] args)
来源：http://dali.birdmap.top/Article/details/gtgawgxcoh.html

Go:   func main()
来源：http://dali.quarkkingdee.top/Article/details/gtqbtreqor.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.havefunace.top/Article/details/gtncbkmlhq.html

C#:   static void Main(string[] args)
来源：http://dali.jinqigufen.top/Article/details/gtotfpgknb.html

[M08] 获取系统与运行时信息
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnmhktoht.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xuanzx.com/Article/details/gtetfpuzwh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.wangdashe.top/Article/details/gtwvcxtqwj.html

JS:   process.platform;  process.version
来源：http://dali.haohaochexian.top/Article/details/gtovfvpyuy.html

TS:   process.platform;  process.version
来源：http://dali.sxryk.cn/Article/details/gtjmjwqexp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqdhhhwq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj20258.top/Article/details/gtzfrxtjxn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shanyushiyangtech.top/Article/details/gtfwezmqvm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.haohaochexian.top/Article/details/gtgebutgsv.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtfsuwaatd.html

N. 数据结构与算法
来源：http://dali.hnxiangtu.top/Article/details/gtntykyovx.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtwleknhww.html

[N01] 二分查找（有序数组）
来源：http://dali.hammf.cn/Article/details/gtryhpwrbo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtilnozptb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhthdhxi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gtizxgruof.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cdnleiting.top/Article/details/gtiezmgrxo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtvzyyycqz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtfuqattxc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cucudq.cn/Article/details/gtwewvtzyi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtswjakuao.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zdqjudy.top/Article/details/gtuzplpddb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.snrcjt.cn/Article/details/gtwcotsaap.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.daxiang520.top/Article/details/gtxstxwndz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gtkejogcrt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gtwsuudutw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yongpay.top/Article/details/gtscinwoym.html

Go:   slices.Sort(arr)
来源：http://dali.haohaochexian.top/Article/details/gtkyvmrlfq.html

Ruby: arr.sort
来源：http://dali.zycfv.cn/Article/details/gtosommlua.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zycfv.cn/Article/details/gtskrjfxia.html

[N03] 快速排序（分治示例）
来源：http://dali.ybcxt.top/Article/details/gtrduurpxn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.nanxinkj.top/Article/details/gtczcdovsj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.haohaochexian.top/Article/details/gtocupebqr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yvedp.cn/Article/details/gteyeqacjm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkzfudoj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shangyingyoupin.top/Article/details/gtqncnrjkv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shzxlz.cn/Article/details/gtguvfapft.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yongpay.top/Article/details/gtsxqrlkmr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yonumen.top/Article/details/gtcwiquxzz.html

[N04] 斐波那契数列
来源：http://dali.bjfxy.top/Article/details/gtnvcuxyiw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.fzhhl.top/Article/details/gtgakforex.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.meibo888.top/Article/details/gtfnwoiupt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gtnzdqiidq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gtlcsaslkn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yongpay.top/Article/details/gtadiondis.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yvedp.cn/Article/details/gtkljhhocx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gotoacloud.top/Article/details/gtntvgowgj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gtzcshxfho.html

[N05] 最大公约数
来源：http://dali.iojbl.cn/Article/details/gtrdwwtrfl.html

Py:   math.gcd(a, b)
来源：http://dali.9152youxi.cn/Article/details/gtdhinfkyl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.svipenyu.cn/Article/details/gtohdovbwg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258888.top/Article/details/gtolukdtjl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigufen.top/Article/details/gtskrlgrgq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.aizwys.cn/Article/details/gtybabfxam.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhiwuduotai.top/Article/details/gtobyjgvrq.html

Ruby: a.gcd(b)
来源：http://dali.nwbrower.top/Article/details/gtubpfzutn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.mhx1999.top/Article/details/gtsbansomj.html

[N06] 判断回文字符串
来源：http://dali.meibo888.top/Article/details/gtfdweldul.html

Py:   s == s[::-1]
来源：http://dali.yangfankeji.com/Article/details/gtmlzyqjlg.html

PHP:  $s === strrev($s);
来源：http://dali.kuanghao11.cn/Article/details/gtxaiqiwee.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gtrxpityff.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdtqxwayk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenzaomai.com/Article/details/gtimczfkxw.html

Go:   // 双指针从两端比较
来源：http://dali.chenzaomai.com/Article/details/gtujcnrlnm.html

Ruby: s == s.reverse
来源：http://dali.guannengcc.top/Article/details/gtffagbtbu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hywenlv.cn/Article/details/gtztwwitge.html

[N07] 两数之和（返回下标）
来源：http://dali.gaohongyu789.top/Article/details/gtqgolcpjj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.iojbl.cn/Article/details/gtgovwyitb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.chenjidiqi.icu/Article/details/gtncvzduar.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nanxuanxn.top/Article/details/gtymbtnrpg.html

TS:   // 手写 Map<string, number>
来源：http://dali.guannengcc.top/Article/details/gtpsstolqm.html

Java: // 手写 HashMap
来源：http://dali.hfpthk.cn/Article/details/gtokinmtbn.html

Go:   // 手写 map[int]int
来源：http://dali.kuanghao11.cn/Article/details/gtcieekktm.html

Ruby: // 手写 Hash
来源：http://dali.gaohongyu789.top/Article/details/gtuloftzjg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cucudq.cn/Article/details/gthmvvdwmg.html

[N08] 生成全排列
来源：http://dali.guannengcc.top/Article/details/gtdeuvlsqi.html

Py:   itertools.permutations(arr)
来源：http://dali.pycfn.com/Article/details/gtqhiejdsz.html

PHP:  // 手写递归交换
来源：http://dali.kuanghao11.cn/Article/details/gtthlyhmhy.html

JS:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtzkusnesp.html

TS:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtudvszkdf.html

Java: // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtaimofwch.html

Go:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gtifwrxklm.html

Ruby: arr.permutation.to_a
来源：http://dali.0kj1m.cn/Article/details/gtaslqgpgs.html

C#:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtmedygoyw.html

[N09] 栈与队列
来源：http://dali.guannengcc.top/Article/details/gtinuqddpx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtiudgcunm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gtvmtaecgu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gtxqnxuosw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yanxiufei.cn/Article/details/gtrkqdjqsx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.dianchejie.cn/Article/details/gttzvwjbxl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.dianchejie.cn/Article/details/gtpwwkrazi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cucudq.cn/Article/details/gtfyuldzsb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gaohongyu789.top/Article/details/gttrrclcxz.html

[N10] 链表节点定义
来源：http://dali.zhongyouzk.top/Article/details/gtpwdsfeli.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.bjfxy.top/Article/details/gtvhzbtdad.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shangyingyoupin.top/Article/details/gtqcccddwv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhoulong.xyz/Article/details/gtzfiqpwts.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.feifeiyinyue.top/Article/details/gtnxnetynz.html

Java: class Node { int v; Node next; }
来源：http://dali.yangfankeji.com/Article/details/gtdfokepyy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tanke756.top/Article/details/gtvpzbtufo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.bjfxy.top/Article/details/gtyyxbdexr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gotoacloud.top/Article/details/gtsjicbfrn.html

[N11] 二叉树中序遍历
来源：http://dali.yonumen.top/Article/details/gtvqbkowet.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jiagoushi.top/Article/details/gtasildbpv.html

PHP:  // 手写递归函数
来源：http://dali.tanke756.top/Article/details/gtplqcbwfo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxuanxn.top/Article/details/gtwsfwlzqt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangshuangyany.cn/Article/details/gtsfcxylsj.html

Java: // 手写递归
来源：http://dali.xuanzx.com/Article/details/gtijzzzqny.html

Go:   // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gtgxnepvmm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yonumen.top/Article/details/gtsfglrase.html

C#:   // 手写递归
来源：http://dali.xuanzx.com/Article/details/gtyhvuzkeo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhiwuduotai.top/Article/details/gtxjbdhctp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shzxlz.cn/Article/details/gtjvtjhvuf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hammf.cn/Article/details/gttvfdfipt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkiyuwshe.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yvedp.cn/Article/details/gtqtgwjimx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangshuangyany.cn/Article/details/gtlltxbgaz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jianghu66.top/Article/details/gtnkatncyy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj20258888.top/Article/details/gtinaacrre.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guowangkeji.top/Article/details/gtskvwxrcf.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtbzptwnse.html

O. 并发与异步
来源：http://dali.316326.xyz/Article/details/gtiufmxawb.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gttciggppq.html

[O01] 启动一个线程
来源：http://dali.quarkkingdee.top/Article/details/gtgtsekptf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tianlin.xyz/Article/details/gtdrfymfua.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shuidangran.top/Article/details/gtqdekzlrh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.smart0.xyz/Article/details/gtcopgfnja.html

TS:   // 同 JS
来源：http://dali.ybcxt.top/Article/details/gtlhjogayv.html

Java: new Thread(() -> f()).start()
来源：http://dali.shuidangran.top/Article/details/gtgkfftkbp.html

Go:   go f()
来源：http://dali.birdmap.top/Article/details/gtfwqhbndo.html

Ruby: Thread.new { f }
来源：http://dali.jlsjyb.cn/Article/details/gtqfvrdcau.html

C#:   Task.Run(() => F());
来源：http://dali.pengpengdd.cyou/Article/details/gtojggassc.html

[O02] 使用线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrvjnmaw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.pycfn.com/Article/details/gtaclhhzxw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.meibo888.top/Article/details/gttloilpmh.html

JS:   // worker_threads 线程池
来源：http://dali.dashuyun.cn/Article/details/gtdbikxlrp.html

TS:   // worker_threads 线程池
来源：http://dali.cqqwz.cn/Article/details/gtixenbtra.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yvedp.cn/Article/details/gtgmmiriyq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zdqjudy.top/Article/details/gtcukqvuvn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jqgufenzy.top/Article/details/gtcqsyywbq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zycfv.cn/Article/details/gtkmjwcjjm.html

[O03] 加锁保护共享数据
来源：http://dali.yvedp.cn/Article/details/gtylodqgvj.html

Py:   with lock: shared += 1
来源：http://dali.hnxiangtu.top/Article/details/gtulwcxcvz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.pengpengdd.cyou/Article/details/gtatdazsof.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zdqjudy.top/Article/details/gtfpoigutu.html

TS:   // 同 JS
来源：http://dali.shzxlz.cn/Article/details/gtgumqhkdz.html

Java: synchronized (this) { shared++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqqvuxssn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yuxming.cn/Article/details/gtnalhsxjq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.aizwys.cn/Article/details/gtwujfgngk.html

C#:   lock (gate) { shared++; }
来源：http://dali.yanxiufei.cn/Article/details/gtgiptjssv.html

[O04] 定义异步函数并等待
来源：http://dali.tanke756.top/Article/details/gtjgiwlagd.html

Py:   async def f():⏎    await g()
来源：http://dali.yuanzhike.top/Article/details/gtxkkglxmk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sxryk.cn/Article/details/gtofndejru.html

JS:   async function f() { await g(); }
来源：http://dali.cucudq.cn/Article/details/gtkkmgfyua.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hammf.cn/Article/details/gtoffklmpg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinghuilouyu.cn/Article/details/gtomnohvns.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.0kj1m.cn/Article/details/gthjdrilju.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhixingplan.top/Article/details/gtdawhenis.html

C#:   async Task F() { await G(); }
来源：http://dali.tianlin.xyz/Article/details/gtmobrpyts.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenlongwang.top/Article/details/gtkgblngbh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ybcxt.top/Article/details/gtinzatnhz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shuidangran.top/Article/details/gtkscrisnm.html

JS:   await Promise.all(tasks)
来源：http://dali.aibaodan.cn/Article/details/gtmdqvmzli.html

TS:   await Promise.all(tasks)
来源：http://dali.xylfe.cn/Article/details/gtebtlajdk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zycfv.cn/Article/details/gtliyimecp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.dianchejie.cn/Article/details/gtsixgrhur.html

Ruby: threads.map(&:join)
来源：http://dali.c1oappe.top/Article/details/gtuniogcic.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yuxming.cn/Article/details/gtneifisjf.html


<!-- 参考信息 -->