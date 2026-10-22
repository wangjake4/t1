代发 wailian999

Py:   requests.post(url, json={"a": 1})
来源：http://dali.c1oappe.top/Article/details/gtjazjedub.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.dashuyun.cn/Article/details/gtqovhkqdq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuanzhike.top/Article/details/gtdcljkeon.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gtknubvfjx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.fengsongda.top/Article/details/gtiqoytxmp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.svipenyu.cn/Article/details/gtedbherpf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zdqjudy.top/Article/details/gthzmbcxqu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jlsjyb.cn/Article/details/gtmujftauc.html

[L03] 设置自定义请求头
来源：http://dali.yuanzhike.top/Article/details/gtarwsjegi.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sufxvd.cn/Article/details/gtinhmapis.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cqqwz.cn/Article/details/gtnvunqvkm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gtbgzeksyn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gtthlszsgt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.pengpengdd.cyou/Article/details/gtpgnyzwds.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tian-w.cn/Article/details/gtysucgddl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.guannengcc.top/Article/details/gtzeembfhs.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ybcxt.top/Article/details/gtymqqajqe.html

[L04] 设置超时
来源：http://dali.xuetiantiany.cn/Article/details/gtxrhtczzv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shzxlz.cn/Article/details/gtybzpjndt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hysaishi.cn/Article/details/gtvyiphdae.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cucudq.cn/Article/details/gtlcaecthw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daria6918.cn/Article/details/gtnmmchtkx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gotoacloud.top/Article/details/gthqpcsnpl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenlongwang.top/Article/details/gtqoazgnpt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.iojbl.cn/Article/details/gthqlqdglm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.fzhhl.top/Article/details/gtarhprpmw.html

[L05] 上传文件（multipart）
来源：http://dali.havefunace.top/Article/details/gtyjedhlif.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sxryk.cn/Article/details/gthzqhitjc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xziqi.cn/Article/details/gtcclccsqj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.andypj.xyz/Article/details/gtfotnyvpw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.birdmap.top/Article/details/gtslvfatxt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cqqwz.cn/Article/details/gtpsxfxwjz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xylfe.cn/Article/details/gthfhtjtam.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dashuyun.cn/Article/details/gttposptqh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtyzkitzgg.html

[L06] 解析响应为 JSON
来源：http://dali.tanke756.top/Article/details/gtttrbpnyi.html

Py:   resp.json()
来源：http://dali.pycfn.com/Article/details/gtiapiucrb.html

PHP:  json_decode($body, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtgbiwcqtz.html

JS:   await resp.json()
来源：http://dali.gzhubu.top/Article/details/gthacnhkeg.html

TS:   await resp.json()
来源：http://dali.nanxinkj.top/Article/details/gtpxbexovk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.snrcjt.cn/Article/details/gtznizrarr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixafgsod.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuanzhike.top/Article/details/gtehvknpra.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jqgufenzy.top/Article/details/gtqnqhuefl.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gtnkrhzihx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.mhx1999.top/Article/details/gtipuqgswm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cdnleiting.top/Article/details/gtswuegkax.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gtimbyhtaz.html

TS:   resp.ok;  resp.status
来源：http://dali.cheryme.top/Article/details/gtivmxeqhj.html

Java: resp.statusCode()
来源：http://dali.yj20258888.top/Article/details/gthnodqoxy.html

Go:   resp.StatusCode
来源：http://dali.bjfxy.top/Article/details/gtkbuvkmme.html

Ruby: resp.code.to_i
来源：http://dali.cucudq.cn/Article/details/gtmzlbvvzg.html

C#:   (int)resp.StatusCode
来源：http://dali.shangyingyoupin.top/Article/details/gtbwscanjx.html

[L08] 并发请求多个地址
来源：http://dali.zycfv.cn/Article/details/gtbaqyspnn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadycitdi.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj20258.top/Article/details/gtudxnnemk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gttclqvpzr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daria6918.cn/Article/details/gtadpwvjno.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gotoacloud.top/Article/details/gtxlrexsgq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhiwuduotai.top/Article/details/gtwmnkmrot.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj202588.top/Article/details/gtzztaygtz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ppjwa.cn/Article/details/gtyhjzjvcq.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtlbmerjnf.html

M. 命令行 / 进程 / 环境
来源：http://dali.smart0.xyz/Article/details/gturaiofzu.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtymopqckg.html

[M01] 读取命令行参数
来源：http://dali.nanxinkj.top/Article/details/gtjetyaegy.html

Py:   sys.argv[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gttvkysuzn.html

PHP:  $argv;  $argc;
来源：http://dali.chenzaomai.com/Article/details/gtckoxvaad.html

JS:   process.argv.slice(2)
来源：http://dali.jqgfzy.top/Article/details/gtonhjpceq.html

TS:   process.argv.slice(2)
来源：http://dali.yueranfly.top/Article/details/gtcudarpzs.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258.top/Article/details/gtebunhpvj.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gtsktchbyi.html

Ruby: ARGV
来源：http://dali.quarkkingdee.top/Article/details/gtdmskhwxu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gtqarqfgwp.html

[M02] 读取环境变量
来源：http://dali.yongpay.top/Article/details/gtqmbseeic.html

Py:   os.environ.get("HOME")
来源：http://dali.cucudq.cn/Article/details/gtofjqngte.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yuanzhike.top/Article/details/gtkfaymths.html

JS:   process.env.HOME
来源：http://dali.kuanghao11.cn/Article/details/gtduclkjfo.html

TS:   process.env.HOME
来源：http://dali.jlsjyb.cn/Article/details/gtzfefhmex.html

Java: System.getenv("HOME")
来源：http://dali.guannengcc.top/Article/details/gtqgqyqbnv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gtssppxfrn.html

Ruby: ENV["HOME"]
来源：http://dali.dianchejie.cn/Article/details/gtqyoymytz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtvzpbykse.html

[M03] 执行外部命令
来源：http://dali.hnxiangtu.top/Article/details/gtskjocphu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shzxlz.cn/Article/details/gtiuhyrvwv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zdqjudy.top/Article/details/gthiufsclm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj202588.top/Article/details/gtqpfxhgbe.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gtxjzaigeu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yuxming.cn/Article/details/gtzjfhsamk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hongshengwenyu.top/Article/details/gtgecmdsdx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.aibaodan.cn/Article/details/gtnhgbdpcz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangdashe.top/Article/details/gtyiahztdi.html

[M04] 获取当前工作目录
来源：http://dali.tian-w.cn/Article/details/gtlodrrgln.html

Py:   os.getcwd()
来源：http://dali.hywenlv.cn/Article/details/gtcgjjdsww.html

PHP:  getcwd();
来源：http://dali.ydzc1.top/Article/details/gttntsyvoa.html

JS:   process.cwd()
来源：http://dali.jinqigufen.top/Article/details/gtnhnoaopz.html

TS:   process.cwd()
来源：http://dali.jianghu66.top/Article/details/gtwkwdbizj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvvfxsyb.html

Go:   os.Getwd()
来源：http://dali.shzxlz.cn/Article/details/gtjgmvxvqa.html

Ruby: Dir.pwd
来源：http://dali.andypj.xyz/Article/details/gtawbvweiv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.feifeiyinyue.top/Article/details/gthwcsjlcb.html

[M05] 设置退出码
来源：http://dali.hysaishi.cn/Article/details/gtvlgnrqce.html

Py:   sys.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gteeuofgmd.html

PHP:  exit(1);
来源：http://dali.nwbrower.top/Article/details/gtauwwyoab.html

JS:   process.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtwpbyctzp.html

TS:   process.exit(1)
来源：http://dali.hnqzz.top/Article/details/gtvfzbyelm.html

Java: System.exit(1)
来源：http://dali.pycfn.com/Article/details/gtobuqrmpg.html

Go:   os.Exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtqzqxvmtv.html

Ruby: exit 1
来源：http://dali.hammf.cn/Article/details/gtvvukvmct.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhixingplan.top/Article/details/gtuegqgrlu.html

[M06] 向标准错误输出
来源：http://dali.cucudq.cn/Article/details/gtqajabqgc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnywhlmsv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.fengsongda.top/Article/details/gtmrkyaqer.html

JS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gtowqjqebi.html

TS:   console.error("err")
来源：http://dali.cheryme.top/Article/details/gtysmngvxm.html

Java: System.err.println("err")
来源：http://dali.guannengcc.top/Article/details/gtsegezkoz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nanxuanxn.top/Article/details/gtkbjqekrg.html

Ruby: warn "err"
来源：http://dali.wangshuangyany.cn/Article/details/gthiotanli.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.316326.xyz/Article/details/gtlpcogkoj.html

[M07] 判断是否为主入口
来源：http://dali.snrcjt.cn/Article/details/gtyjqravgv.html

Py:   if __name__ == "__main__":
来源：http://dali.xuetiantiany.cn/Article/details/gtyntxbowz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ivvv.top/Article/details/gtkkwszhjr.html

JS:   require.main === module
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvytcvmh.html

TS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gtrgaxgdav.html

Java: public static void main(String[] args)
来源：http://dali.tanke756.top/Article/details/gtmkinkreb.html

Go:   func main()
来源：http://dali.zhongyouzk.top/Article/details/gtlaztnync.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ehwqpu.com/Article/details/gtywpgzlxy.html

C#:   static void Main(string[] args)
来源：http://dali.yj202588.top/Article/details/gtgpljinpy.html

[M08] 获取系统与运行时信息
来源：http://dali.redwolf501.top/Article/details/gtxnfetzrs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhongyouzk.top/Article/details/gthmrezwtc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yuxming.cn/Article/details/gtrsingivg.html

JS:   process.platform;  process.version
来源：http://dali.nwbrower.top/Article/details/gtmhpnnmir.html

TS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gtixjgigsp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ivvv.top/Article/details/gtlnjmhpix.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthionrchn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nwbrower.top/Article/details/gtlqrfdyiu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybpauswl.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtjpqjunjh.html

N. 数据结构与算法
来源：http://dali.chenjidiqi.icu/Article/details/gtygrgrvqk.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtrgzkurrn.html

[N01] 二分查找（有序数组）
来源：http://dali.cheryme.top/Article/details/gtpeppobgm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtqhoywjyj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinqigufen.top/Article/details/gtbisabypd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuxming.cn/Article/details/gtkvznmaeu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.havefunace.top/Article/details/gtpvsyroah.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtgyceqoah.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtsttqehjm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyduedoqt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfdivarz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shanyushiyangtech.top/Article/details/gtvlzpohwz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sufxvd.cn/Article/details/gtmmbpmczi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.dianchejie.cn/Article/details/gtzrjehtje.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yanxiufei.cn/Article/details/gtkhvuvbby.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yanxiufei.cn/Article/details/gtcouukymb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ppjwa.cn/Article/details/gtlwhtvteq.html

Go:   slices.Sort(arr)
来源：http://dali.birdmap.top/Article/details/gtloocibno.html

Ruby: arr.sort
来源：http://dali.jyoumei.cn/Article/details/gtqsngbwzq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gaohongyu789.top/Article/details/gtyectxvuf.html

[N03] 快速排序（分治示例）
来源：http://dali.zdqjudy.top/Article/details/gtqohgzrgq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenjidiqi.icu/Article/details/gtfclhdnoh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yuxming.cn/Article/details/gtxfzdhxln.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqggagcu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxinkj.top/Article/details/gtebkruqvj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cdnleiting.top/Article/details/gtklyczcuz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.fzhhl.top/Article/details/gtjmyfjbls.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.aibaodan.cn/Article/details/gtwhcjminh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangshuangyany.cn/Article/details/gtyanxmqih.html

[N04] 斐波那契数列
来源：http://dali.iojbl.cn/Article/details/gtqbhxpfnn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hnqzz.top/Article/details/gtxlkogqdz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nwbrower.top/Article/details/gtxflwbsoz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gtepertbvj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sweek.top/Article/details/gthsyelvdk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hammf.cn/Article/details/gtumjsfuni.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gzhubu.top/Article/details/gttxnipxqs.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.c1oappe.top/Article/details/gtryztrijp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmzdaamh.html

[N05] 最大公约数
来源：http://dali.shanyushiyangtech.top/Article/details/gtjafwuajl.html

Py:   math.gcd(a, b)
来源：http://dali.yonumen.top/Article/details/gtdlzigkpi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.aizwys.cn/Article/details/gtfuuhguge.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ehwqpu.com/Article/details/gtpsmsylsm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ehwqpu.com/Article/details/gtmhgdwntc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhengqikj.top/Article/details/gtceyclsqz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.pycfn.com/Article/details/gtgywgrkap.html

Ruby: a.gcd(b)
来源：http://dali.gogol.net.cn/Article/details/gtlyscbsjt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jlsjyb.cn/Article/details/gthmpooqlx.html

[N06] 判断回文字符串
来源：http://dali.gaohongyu789.top/Article/details/gtslmgdxoq.html

Py:   s == s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gtcllswjmk.html

PHP:  $s === strrev($s);
来源：http://dali.cucudq.cn/Article/details/gtlwehzbnj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtieetzbvw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtvqufcmlk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hammf.cn/Article/details/gtmflkyxoz.html

Go:   // 双指针从两端比较
来源：http://dali.yuxming.cn/Article/details/gtviywazar.html

Ruby: s == s.reverse
来源：http://dali.daxiang520.top/Article/details/gtcplknadg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.feifeiyinyue.top/Article/details/gtgdacupoy.html

[N07] 两数之和（返回下标）
来源：http://dali.jianghu66.top/Article/details/gtpxfethpd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tanke756.top/Article/details/gttsummwwd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.svipenyu.cn/Article/details/gtvcfhitdr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.0kj1m.cn/Article/details/gtoxrmpusd.html

TS:   // 手写 Map<string, number>
来源：http://dali.haohaochexian.top/Article/details/gtvwyrapvy.html

Java: // 手写 HashMap
来源：http://dali.hnqzz.top/Article/details/gtuprubtqp.html

Go:   // 手写 map[int]int
来源：http://dali.yongpay.top/Article/details/gtaptxnjii.html

Ruby: // 手写 Hash
来源：http://dali.gogol.net.cn/Article/details/gtnxgfshpo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shzxlz.cn/Article/details/gtoilvxlvd.html

[N08] 生成全排列
来源：http://dali.316326.xyz/Article/details/gtbmdwspgn.html

Py:   itertools.permutations(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaaranekh.html

PHP:  // 手写递归交换
来源：http://dali.yongpay.top/Article/details/gtgzithpbg.html

JS:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtwsjrizqj.html

TS:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtgnnqcltw.html

Java: // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtyighuzpu.html

Go:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtycnfnvui.html

Ruby: arr.permutation.to_a
来源：http://dali.c1oappe.top/Article/details/gtfiaxkcot.html

C#:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gtgsniwoxx.html

[N09] 栈与队列
来源：http://dali.xziqi.cn/Article/details/gtlfatxpzb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sweek.top/Article/details/gtjnrxxmvg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.iojbl.cn/Article/details/gtpvuwvnzj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gttzxtmauf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.bjfxy.top/Article/details/gtaitpfrhw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gaohongyu789.top/Article/details/gtaiisvpbv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.aizwys.cn/Article/details/gtewwpwtbd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ybcxt.top/Article/details/gtfbtcaedc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.feifeiyinyue.top/Article/details/gtraijgndi.html

[N10] 链表节点定义
来源：http://dali.zhixingplan.top/Article/details/gttmbrpsvq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhixingplan.top/Article/details/gtzfsogqvj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hnqzz.top/Article/details/gtolalfsme.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gogol.net.cn/Article/details/gttejyrsig.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yangfankeji.com/Article/details/gteivhxpeq.html

Java: class Node { int v; Node next; }
来源：http://dali.dianchejie.cn/Article/details/gtvpjnchzf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.mhx1999.top/Article/details/gtcbbstvwp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuanzhike.top/Article/details/gthnzlyahp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gaohongyu789.top/Article/details/gtvqifwvdp.html

[N11] 二叉树中序遍历
来源：http://dali.xylfe.cn/Article/details/gtpndfquoe.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.nanxuanxn.top/Article/details/gtjurssobz.html

PHP:  // 手写递归函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlbxemyum.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hfpthk.cn/Article/details/gtbglrlnck.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aizwys.cn/Article/details/gtusjgqbsj.html

Java: // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gtuzlgzdxm.html

Go:   // 手写递归
来源：http://dali.sxryk.cn/Article/details/gtlkhwrlmh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sxryk.cn/Article/details/gtfzbaylqr.html

C#:   // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gtoqxlzjvn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.aizwys.cn/Article/details/gtwcghcuod.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jianghu66.top/Article/details/gtmfccvysn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.iojbl.cn/Article/details/gtumxriwhw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aizwys.cn/Article/details/gtdylpjvkb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.316326.xyz/Article/details/gtsnmneyjb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yanxiufei.cn/Article/details/gtkvafzzvq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenjidiqi.icu/Article/details/gtchnsahmc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ybcxt.top/Article/details/gtauglnqsw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xylfe.cn/Article/details/gtpmbmamvu.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkiqnnvbb.html

O. 并发与异步
来源：http://dali.haohaochexian.top/Article/details/gtqpfraphs.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gttiqopkpv.html

[O01] 启动一个线程
来源：http://dali.cqqwz.cn/Article/details/gtyobtnvik.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yj202588.top/Article/details/gtdnxhyqjn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.9152youxi.cn/Article/details/gtwsbpgsmp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenzaomai.com/Article/details/gtplqnhxzn.html

TS:   // 同 JS
来源：http://dali.yanxiufei.cn/Article/details/gtcbeqxxbq.html

Java: new Thread(() -> f()).start()
来源：http://dali.fengsongda.top/Article/details/gtgtmyzuix.html

Go:   go f()
来源：http://dali.cqqwz.cn/Article/details/gtcbazuniw.html

Ruby: Thread.new { f }
来源：http://dali.nanxuanxn.top/Article/details/gteckywbgc.html

C#:   Task.Run(() => F());
来源：http://dali.guowangkeji.top/Article/details/gtmfdifbxa.html

[O02] 使用线程池
来源：http://dali.pengpengdd.cyou/Article/details/gtgtzwlkux.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ybcxt.top/Article/details/gtfycujavz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sysykeji.top/Article/details/gttvpcamkf.html

JS:   // worker_threads 线程池
来源：http://dali.dianchejie.cn/Article/details/gtxwvwjygo.html

TS:   // worker_threads 线程池
来源：http://dali.yvedp.cn/Article/details/gtcjagvoiz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhiwuduotai.top/Article/details/gthrfynlyv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shuidangran.top/Article/details/gtrmjhvkvs.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cqqwz.cn/Article/details/gtndeeioub.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yonumen.top/Article/details/gtcfbhklni.html

[O03] 加锁保护共享数据
来源：http://dali.yanxiufei.cn/Article/details/gtejpxqbbh.html

Py:   with lock: shared += 1
来源：http://dali.ydzc1.top/Article/details/gtzobuvoij.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gzhubu.top/Article/details/gtpdglpqpz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tian-w.cn/Article/details/gtmylakxtg.html

TS:   // 同 JS
来源：http://dali.bjfxy.top/Article/details/gtoylyqxbg.html

Java: synchronized (this) { shared++; }
来源：http://dali.gogol.net.cn/Article/details/gtwqockiur.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenlongwang.top/Article/details/gtfqxhipyu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.dianchejie.cn/Article/details/gtbejekjqb.html

C#:   lock (gate) { shared++; }
来源：http://dali.jlsjyb.cn/Article/details/gtrlpyrtrz.html

[O04] 定义异步函数并等待
来源：http://dali.yj20258.top/Article/details/gtstufuzjf.html

Py:   async def f():⏎    await g()
来源：http://dali.tanke756.top/Article/details/gtmlgsnjdq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xinyue.icu/Article/details/gthcwgwytq.html

JS:   async function f() { await g(); }
来源：http://dali.xinyue.icu/Article/details/gtqyywmlhf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.redwolf501.top/Article/details/gtvuvwiiah.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gtnzvlmfqp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.birdmap.top/Article/details/gtudwxhwmf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.aizwys.cn/Article/details/gtwplshzao.html

C#:   async Task F() { await G(); }
来源：http://dali.nanxinkj.top/Article/details/gtihbjcbmb.html

[O05] 并发执行并等待全部完成
来源：http://dali.pycfn.com/Article/details/gtzxzgprea.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xziqi.cn/Article/details/gtzqjzbidp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yonumen.top/Article/details/gthdzalken.html

JS:   await Promise.all(tasks)
来源：http://dali.guannengcc.top/Article/details/gthvxkyeis.html

TS:   await Promise.all(tasks)
来源：http://dali.hnqzz.top/Article/details/gtsrrcnssm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.daxiang520.top/Article/details/gtntcaqcao.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj202588.top/Article/details/gtbioidffc.html

Ruby: threads.map(&:join)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxzzgagnb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.meibo888.top/Article/details/gtidopwugn.html

[O06] 使用进程池
来源：http://dali.pycfn.com/Article/details/gtgvzqqkyh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhixingplan.top/Article/details/gtpnukbdbb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zycfv.cn/Article/details/gthmgbpnea.html

JS:   // child_process / cluster 模块
来源：http://dali.ivvv.top/Article/details/gtbhzcvweo.html


<!-- 参考信息 -->