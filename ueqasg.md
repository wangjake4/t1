代发 wailian999

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xylfe.cn/Article/details/gtpwwqvlpb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cashguo.top/Article/details/gtamfpjxef.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.iojbl.cn/Article/details/gtopahzvjb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigufen.top/Article/details/gtbrqcqzee.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.kuanghao11.cn/Article/details/gthgrrivcs.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.wangshuangyany.cn/Article/details/gtzlrpbljg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zycfv.cn/Article/details/gtorltnvzc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.mhx1999.top/Article/details/gtfunmmwhe.html

[L03] 设置自定义请求头
来源：http://dali.yj202588.top/Article/details/gtmxyrtito.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xylfe.cn/Article/details/gtxzipoldo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.guowangkeji.top/Article/details/gttginiyll.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cqqwz.cn/Article/details/gtkdkhnwcj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.316326.xyz/Article/details/gtdlnxgnoj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvrjcjhft.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gtqsrolqyn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jiagoushi.top/Article/details/gtdzowtdjv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sweek.top/Article/details/gtypfxztkh.html

[L04] 设置超时
来源：http://dali.jyoumei.cn/Article/details/gthuhyrach.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sweek.top/Article/details/gtrrzpbccy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jiagoushi.top/Article/details/gtsbqomwmv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gogol.net.cn/Article/details/gtjtpzqrah.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.0kj1m.cn/Article/details/gtpioqsnzx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jiagoushi.top/Article/details/gtlweozfld.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.meibo888.top/Article/details/gtdvevkarn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhongyouzk.top/Article/details/gtvuxqzknr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenlongwang.top/Article/details/gtdjtbhibw.html

[L05] 上传文件（multipart）
来源：http://dali.316326.xyz/Article/details/gtbrfhrxpg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.iojbl.cn/Article/details/gtoeujqxhl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tanke756.top/Article/details/gttzugpetg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gtnvalhoql.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gtiefodlpl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guannengcc.top/Article/details/gtuuegbosk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sxryk.cn/Article/details/gtbthcatvc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.fzhhl.top/Article/details/gtjbjiikwe.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hammf.cn/Article/details/gtxynidpjh.html

[L06] 解析响应为 JSON
来源：http://dali.zhoulong.xyz/Article/details/gtynpwwgox.html

Py:   resp.json()
来源：http://dali.tian-w.cn/Article/details/gtvuyzfpwr.html

PHP:  json_decode($body, true);
来源：http://dali.dashuyun.cn/Article/details/gtpvdnxhil.html

JS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gtbkqzeivm.html

TS:   await resp.json()
来源：http://dali.dashuyun.cn/Article/details/gtemvtijyl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ydzc1.top/Article/details/gtqlcqxylz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hfpthk.cn/Article/details/gtoeeijalf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.bjfxy.top/Article/details/gtujqcooct.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yvedp.cn/Article/details/gttqazqsuy.html

[L07] 处理 HTTP 状态码
来源：http://dali.316326.xyz/Article/details/gtaclqgcfm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenzaomai.com/Article/details/gtrapkzbpk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuanzhike.top/Article/details/gtyojopdmq.html

JS:   resp.ok;  resp.status
来源：http://dali.shuidangran.top/Article/details/gtlwgrchpq.html

TS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gtbzhrwhhv.html

Java: resp.statusCode()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtppbiqzmz.html

Go:   resp.StatusCode
来源：http://dali.shanyushiyangtech.top/Article/details/gtvgliohpr.html

Ruby: resp.code.to_i
来源：http://dali.cashguo.top/Article/details/gtbuxowdia.html

C#:   (int)resp.StatusCode
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkkbbjpw.html

[L08] 并发请求多个地址
来源：http://dali.mhx1999.top/Article/details/gtnkjzpzak.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ydzc1.top/Article/details/gtyolqdwqs.html

PHP:  curl_multi_init() 系列
来源：http://dali.zdqjudy.top/Article/details/gtajyxbdkm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guowangkeji.top/Article/details/gtvfcrgudu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrjahpqv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guowangkeji.top/Article/details/gtidrljaqw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gtbckhrfky.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gtppzzjuln.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.fengsongda.top/Article/details/gtnzcvdajr.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtpjckbaid.html

M. 命令行 / 进程 / 环境
来源：http://dali.gogol.net.cn/Article/details/gtvgzkwpwe.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtucdfvrhs.html

[M01] 读取命令行参数
来源：http://dali.chenjidiqi.icu/Article/details/gtgykwagbu.html

Py:   sys.argv[1:]
来源：http://dali.hnxiangtu.top/Article/details/gtfmcvhyrv.html

PHP:  $argv;  $argc;
来源：http://dali.fzhhl.top/Article/details/gtogiboeuj.html

JS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gtwmkgedur.html

TS:   process.argv.slice(2)
来源：http://dali.cucudq.cn/Article/details/gtqfcsvkov.html

Java: args 数组（main 方法参数）
来源：http://dali.nanxuanxn.top/Article/details/gtxttwtitm.html

Go:   os.Args[1:]
来源：http://dali.guowangkeji.top/Article/details/gtkxfwheeo.html

Ruby: ARGV
来源：http://dali.gogol.net.cn/Article/details/gtzxlzqqdc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gtqxvausfi.html

[M02] 读取环境变量
来源：http://dali.ybcxt.top/Article/details/gtpynmmluj.html

Py:   os.environ.get("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtxhrmtdyc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gtscazppga.html

JS:   process.env.HOME
来源：http://dali.hywenlv.cn/Article/details/gtdffkqlxq.html

TS:   process.env.HOME
来源：http://dali.cheryme.top/Article/details/gtrphsyxji.html

Java: System.getenv("HOME")
来源：http://dali.birdmap.top/Article/details/gtljptbxnd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj202588.top/Article/details/gtucvruuhl.html

Ruby: ENV["HOME"]
来源：http://dali.xuanzx.com/Article/details/gtylrryyqn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tianlin.xyz/Article/details/gtkezdoxyh.html

[M03] 执行外部命令
来源：http://dali.xylfe.cn/Article/details/gtshxtnjyb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhongyouzk.top/Article/details/gtkjyhhbvz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nanxuanxn.top/Article/details/gtgtqxmmes.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.daria6918.cn/Article/details/gtvxewkepe.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jlsjyb.cn/Article/details/gtgwjwbxgn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.havefunace.top/Article/details/gtvioqdczb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aizwys.cn/Article/details/gtlwmzupux.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpijttped.html

C#:   Process.Start("ls", "-l");
来源：http://dali.fzhhl.top/Article/details/gtehxlmmrs.html

[M04] 获取当前工作目录
来源：http://dali.haohaochexian.top/Article/details/gttmpfsugo.html

Py:   os.getcwd()
来源：http://dali.jlsjyb.cn/Article/details/gtbboqqtwh.html

PHP:  getcwd();
来源：http://dali.xinyue.icu/Article/details/gtwmjbcgvj.html

JS:   process.cwd()
来源：http://dali.aizwys.cn/Article/details/gtimiszgvj.html

TS:   process.cwd()
来源：http://dali.jyoumei.cn/Article/details/gtaresdcst.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.quarkkingdee.top/Article/details/gtgxxqwdec.html

Go:   os.Getwd()
来源：http://dali.gaohongyu789.top/Article/details/gtwpdliosp.html

Ruby: Dir.pwd
来源：http://dali.bjfxy.top/Article/details/gtpsafrnzh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.meibo888.top/Article/details/gtgmphbzzf.html

[M05] 设置退出码
来源：http://dali.hysaishi.cn/Article/details/gthaxhwdcc.html

Py:   sys.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtzzryraxl.html

PHP:  exit(1);
来源：http://dali.tanke756.top/Article/details/gtdpbvvgun.html

JS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtcaviqghv.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdwyqauf.html

Java: System.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtpkyezgqq.html

Go:   os.Exit(1)
来源：http://dali.yj202588.top/Article/details/gtgxuvcehl.html

Ruby: exit 1
来源：http://dali.jyoumei.cn/Article/details/gtlyknwfxh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nwbrower.top/Article/details/gtkekrktcs.html

[M06] 向标准错误输出
来源：http://dali.zhiwuduotai.top/Article/details/gtvwemyzjr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuxming.cn/Article/details/gtqyksjpbl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinqigfzy.top/Article/details/gtdfrzunqw.html

JS:   console.error("err")
来源：http://dali.meibo888.top/Article/details/gtyttgvfvt.html

TS:   console.error("err")
来源：http://dali.dianchejie.cn/Article/details/gttgivisbj.html

Java: System.err.println("err")
来源：http://dali.cdnleiting.top/Article/details/gtoqenacmh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jyoumei.cn/Article/details/gtsbmgulyh.html

Ruby: warn "err"
来源：http://dali.havefunace.top/Article/details/gtrwmrhsnq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cqqwz.cn/Article/details/gtzwtsgmbx.html

[M07] 判断是否为主入口
来源：http://dali.cashguo.top/Article/details/gtnthwqmxm.html

Py:   if __name__ == "__main__":
来源：http://dali.smart0.xyz/Article/details/gtfbgrnltu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shzxlz.cn/Article/details/gttuiagzgr.html

JS:   require.main === module
来源：http://dali.vqdsnc.cn/Article/details/gtzghifsbh.html

TS:   require.main === module
来源：http://dali.zdqjudy.top/Article/details/gtepmibnhr.html

Java: public static void main(String[] args)
来源：http://dali.dianchejie.cn/Article/details/gtujbwuwpc.html

Go:   func main()
来源：http://dali.fzhhl.top/Article/details/gtbdhjnvmp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.daxiang520.top/Article/details/gteerfwbot.html

C#:   static void Main(string[] args)
来源：http://dali.sxryk.cn/Article/details/gtegughitf.html

[M08] 获取系统与运行时信息
来源：http://dali.yj202588.top/Article/details/gtrhehkknp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.quarkkingdee.top/Article/details/gtfjtlxvde.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.wangdashe.top/Article/details/gtisavtyxw.html

JS:   process.platform;  process.version
来源：http://dali.sxryk.cn/Article/details/gtiojimkis.html

TS:   process.platform;  process.version
来源：http://dali.yj202588.top/Article/details/gtwlytxzaq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigufen.top/Article/details/gtzqhntepv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aibaodan.cn/Article/details/gtxzmmxnrl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.pycfn.com/Article/details/gtxxwndutp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tianlin.xyz/Article/details/gtersrbxzt.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtjqwbtkwk.html

N. 数据结构与算法
来源：http://dali.shanyushiyangtech.top/Article/details/gtwohhhvmx.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtefgjyatj.html

[N01] 二分查找（有序数组）
来源：http://dali.tanke756.top/Article/details/gtkxkxlert.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtcogybiwo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ydzc1.top/Article/details/gtxqarflip.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.0kj1m.cn/Article/details/gtmglalykc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxinkj.top/Article/details/gtqwauuwym.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtrxeddmip.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujqolfvj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.wangshuangyany.cn/Article/details/gtqupbhmft.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sweek.top/Article/details/gtxjvmmwir.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.feifeiyinyue.top/Article/details/gtivfdurfq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daria6918.cn/Article/details/gtrujgicui.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258888.top/Article/details/gtnremftxr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gtlvrqsdug.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gtzugzezyd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.0kj1m.cn/Article/details/gtrqbsgtoi.html

Go:   slices.Sort(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtyaugwsxl.html

Ruby: arr.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gtzlfzqtoo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daxiang520.top/Article/details/gtprxlvjhq.html

[N03] 快速排序（分治示例）
来源：http://dali.guannengcc.top/Article/details/gtgeqiunoo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.nanxinkj.top/Article/details/gtlmtocgzd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xuanzx.com/Article/details/gtdrnlvntv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xinyue.icu/Article/details/gtxnaojxur.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yongpay.top/Article/details/gtcirinfup.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.aizwys.cn/Article/details/gtriwcdhed.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.guannengcc.top/Article/details/gtopwcptbr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shuidangran.top/Article/details/gtombdsrdo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigfzy.top/Article/details/gtkpgqqock.html

[N04] 斐波那契数列
来源：http://dali.xuanzx.com/Article/details/gtmlcsjhyy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gtklorycjp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hongshengwenyu.top/Article/details/gtnzqnpohp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtsucqlkvg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtfgahmsyv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nanxuanxn.top/Article/details/gtqayocoes.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.vqdsnc.cn/Article/details/gtcewjeujy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gthmzrfzom.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtrrqixtbl.html

[N05] 最大公约数
来源：http://dali.daxiang520.top/Article/details/gtbdmjifpg.html

Py:   math.gcd(a, b)
来源：http://dali.wangdashe.top/Article/details/gtktfpszhj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jqgufenzy.top/Article/details/gtkaptsgda.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gtdnzzhaxt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sufxvd.cn/Article/details/gtoaphecmr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.iojbl.cn/Article/details/gttxsmpgic.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tian-w.cn/Article/details/gtkmfimnjk.html

Ruby: a.gcd(b)
来源：http://dali.sweek.top/Article/details/gtyvqqymrl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fengsongda.top/Article/details/gttthhaxaf.html

[N06] 判断回文字符串
来源：http://dali.ydzc1.top/Article/details/gtkhtzbnnv.html

Py:   s == s[::-1]
来源：http://dali.zhoulong.xyz/Article/details/gtefouzjqf.html

PHP:  $s === strrev($s);
来源：http://dali.nanxuanxn.top/Article/details/gtdhknryrj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gtythbcbwl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtdhyomlto.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhiwuduotai.top/Article/details/gtheazcmqf.html

Go:   // 双指针从两端比较
来源：http://dali.hfpthk.cn/Article/details/gtaomfjmaf.html

Ruby: s == s.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmoroaunx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.havefunace.top/Article/details/gtyumpjxnw.html

[N07] 两数之和（返回下标）
来源：http://dali.tianlin.xyz/Article/details/gtpvlrrber.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shangyingyoupin.top/Article/details/gtjqcsfdmn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.c1oappe.top/Article/details/gtsgaoiene.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yanxiufei.cn/Article/details/gthswzrlyt.html

TS:   // 手写 Map<string, number>
来源：http://dali.svipenyu.cn/Article/details/gtwvkoizug.html

Java: // 手写 HashMap
来源：http://dali.316326.xyz/Article/details/gtspkahyjr.html

Go:   // 手写 map[int]int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfeanejvj.html

Ruby: // 手写 Hash
来源：http://dali.andypj.xyz/Article/details/gtnkgqjsgy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cqqwz.cn/Article/details/gtzyzjjwfw.html

[N08] 生成全排列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywperzac.html

Py:   itertools.permutations(arr)
来源：http://dali.iojbl.cn/Article/details/gtlwsekaxk.html

PHP:  // 手写递归交换
来源：http://dali.wangdashe.top/Article/details/gttwhkobar.html

JS:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtixyabrbq.html

TS:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtyrvxewdi.html

Java: // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gthhcafmby.html

Go:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtmrziqdmq.html

Ruby: arr.permutation.to_a
来源：http://dali.andypj.xyz/Article/details/gtvmfgltbr.html

C#:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtqicvowah.html

[N09] 栈与队列
来源：http://dali.wangdashe.top/Article/details/gttplhtaro.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.wangdashe.top/Article/details/gtzjlzsrkt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gtogcgczzh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yueranfly.top/Article/details/gtbdwiwldy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shanyushiyangtech.top/Article/details/gtpyljktnm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xziqi.cn/Article/details/gtospwbnll.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xylfe.cn/Article/details/gtlhcnpvww.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.birdmap.top/Article/details/gteslsifdl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gaohongyu789.top/Article/details/gtrevayzez.html

[N10] 链表节点定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpnohamhh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnlginnsj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.dashuyun.cn/Article/details/gtxdideryf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.haohaochexian.top/Article/details/gtxmgfmfba.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhiwuduotai.top/Article/details/gtirocyawd.html

Java: class Node { int v; Node next; }
来源：http://dali.yuxming.cn/Article/details/gtbftjeunu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhoulong.xyz/Article/details/gtwookixhd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daxiang520.top/Article/details/gtylbdfssz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hongshengwenyu.top/Article/details/gthfxqyhrp.html

[N11] 二叉树中序遍历
来源：http://dali.tanke756.top/Article/details/gtjwzibauy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.iojbl.cn/Article/details/gthysoikac.html

PHP:  // 手写递归函数
来源：http://dali.havefunace.top/Article/details/gtpcsijslo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigufen.top/Article/details/gtpxfymrrs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.feifeiyinyue.top/Article/details/gtmrgwimdl.html

Java: // 手写递归
来源：http://dali.kuanghao11.cn/Article/details/gtobnfowxz.html

Go:   // 手写递归
来源：http://dali.yj20258888.top/Article/details/gtoaiwpqus.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cashguo.top/Article/details/gtwxbdwiqx.html

C#:   // 手写递归
来源：http://dali.aizwys.cn/Article/details/gtglkvxvah.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.0kj1m.cn/Article/details/gtnmytjjxw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cdnleiting.top/Article/details/gtnrjphunr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jqgufenzy.top/Article/details/gtfqsibbzb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yonumen.top/Article/details/gtxampupml.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtejtarvti.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sxryk.cn/Article/details/gtncwuuatt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.fengsongda.top/Article/details/gtolrqztxs.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zycfv.cn/Article/details/gtkgithiwy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.meibo888.top/Article/details/gtjibrhmex.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtqgrcycda.html

O. 并发与异步
来源：http://dali.zdqjudy.top/Article/details/gtufadrwfk.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtsiarriwz.html

[O01] 启动一个线程
来源：http://dali.hongshengwenyu.top/Article/details/gtmrmdhjda.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cdnleiting.top/Article/details/gtmamkrsoi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yueranfly.top/Article/details/gtasvwgwdi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nanxuanxn.top/Article/details/gtwlvxfayk.html

TS:   // 同 JS
来源：http://dali.daxiang520.top/Article/details/gtwhyigpvm.html

Java: new Thread(() -> f()).start()
来源：http://dali.meibo888.top/Article/details/gtmmsgvmfi.html

Go:   go f()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxwwenhej.html

Ruby: Thread.new { f }
来源：http://dali.ydzc1.top/Article/details/gtqplbzzqm.html

C#:   Task.Run(() => F());
来源：http://dali.wangshuangyany.cn/Article/details/gtpojthuwy.html

[O02] 使用线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gtjauihymx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gogol.net.cn/Article/details/gthvcdecec.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cashguo.top/Article/details/gtrympqhpx.html

JS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gtgsacobij.html

TS:   // worker_threads 线程池
来源：http://dali.tian-w.cn/Article/details/gthuangvzs.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.guannengcc.top/Article/details/gtfptjyyzp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhiwuduotai.top/Article/details/gtyntefisj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xuanzx.com/Article/details/gtxkfykonc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xinyue.icu/Article/details/gtfubiznix.html

[O03] 加锁保护共享数据
来源：http://dali.redwolf501.top/Article/details/gtruxuvlmk.html

Py:   with lock: shared += 1
来源：http://dali.gogol.net.cn/Article/details/gtlqwxvgzm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gtiddfprlq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sysykeji.top/Article/details/gtekxokatc.html

TS:   // 同 JS
来源：http://dali.jinqigufen.top/Article/details/gtofxqlbbf.html

Java: synchronized (this) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gtnoqrierm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jianghu66.top/Article/details/gtsxgrbhzh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nanxinkj.top/Article/details/gtdclelhek.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenzaomai.com/Article/details/gtarndhmgo.html

[O04] 定义异步函数并等待
来源：http://dali.pycfn.com/Article/details/gtolzuavdg.html

Py:   async def f():⏎    await g()
来源：http://dali.quarkkingdee.top/Article/details/gtuubddcip.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sweek.top/Article/details/gttdpnzjsq.html

JS:   async function f() { await g(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthckgrisj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ydzc1.top/Article/details/gtgpgvnndm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ydzc1.top/Article/details/gtxczqeyvs.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nanxuanxn.top/Article/details/gtwnnbxzov.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hammf.cn/Article/details/gtppvpjynv.html

C#:   async Task F() { await G(); }
来源：http://dali.guowangkeji.top/Article/details/gtjpatagtl.html

[O05] 并发执行并等待全部完成
来源：http://dali.vqdsnc.cn/Article/details/gtnaofnzks.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yvedp.cn/Article/details/gtaskcuyls.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ybcxt.top/Article/details/gtjullouoi.html

JS:   await Promise.all(tasks)
来源：http://dali.ybcxt.top/Article/details/gtchnozazx.html

TS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gtkdxmxzhk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cdnleiting.top/Article/details/gtukkkxdmz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.wangshuangyany.cn/Article/details/gtsxemdpjt.html

Ruby: threads.map(&:join)
来源：http://dali.snrcjt.cn/Article/details/gthrixqvkk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.mhx1999.top/Article/details/gtleiuqskn.html

[O06] 使用进程池
来源：http://dali.chenlongwang.top/Article/details/gtqijukurr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hammf.cn/Article/details/gtzqiutqpi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenzaomai.com/Article/details/gtjliyakrr.html

JS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gtismtfrwf.html


<!-- 参考信息 -->