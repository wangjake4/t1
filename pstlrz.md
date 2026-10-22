代发 wailian999

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ehwqpu.com/Article/details/gt2lhejgygi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.pycfn.com/Article/details/gt2noqrlmqe.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gt2nhdgpwty.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daxiang520.top/Article/details/gt2djrobcwu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hnxiangtu.top/Article/details/gt2pycjgvjt.html

[L04] 设置超时
来源：http://dali.zhongyouzk.top/Article/details/gt2mmtrfnsz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ivvv.top/Article/details/gt2lkleediz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgfzy.top/Article/details/gt2rorreddi.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.feifeiyinyue.top/Article/details/gt2hlfcbdxy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jyoumei.cn/Article/details/gt2iiedtfwz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hammf.cn/Article/details/gt2insocchh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guowangkeji.top/Article/details/gt2ghjdqeqo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jianghu66.top/Article/details/gt2xepemeks.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gogol.net.cn/Article/details/gt2zkhnfgga.html

[L05] 上传文件（multipart）
来源：http://dali.gotoacloud.top/Article/details/gt2rwuicfxh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhongyouzk.top/Article/details/gt2scxquopc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.316326.xyz/Article/details/gt2jfydvlmi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jianghu66.top/Article/details/gt2jafpuuwr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.pycfn.com/Article/details/gt2vbwehsiz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhixingplan.top/Article/details/gt2cjtermec.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zycfv.cn/Article/details/gt2gsjsjhqw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sweek.top/Article/details/gt2pgysravf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2xunkohye.html

[L06] 解析响应为 JSON
来源：http://dali.chenjidiqi.icu/Article/details/gt2zqlzijsy.html

Py:   resp.json()
来源：http://dali.ydzc1.top/Article/details/gt2dshoqtym.html

PHP:  json_decode($body, true);
来源：http://dali.zhoulong.xyz/Article/details/gt2dynlvedk.html

JS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gt2myuqojyd.html

TS:   await resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ywixzlev.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zdqjudy.top/Article/details/gt2tshxcdxu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cqqwz.cn/Article/details/gt2jhqbizud.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xylfe.cn/Article/details/gt2sdrbwtbc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.dianchejie.cn/Article/details/gt2kezqfqig.html

[L07] 处理 HTTP 状态码
来源：http://dali.feifeiyinyue.top/Article/details/gt2dcilwyrq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nuvsjbuu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj20258.top/Article/details/gt2hwjknbtn.html

JS:   resp.ok;  resp.status
来源：http://dali.xuetiantiany.cn/Article/details/gt2wfweonkc.html

TS:   resp.ok;  resp.status
来源：http://dali.cashguo.top/Article/details/gt2kmxxjxol.html

Java: resp.statusCode()
来源：http://dali.wangshuangyany.cn/Article/details/gt2baqxdypv.html

Go:   resp.StatusCode
来源：http://dali.jinqigufen.top/Article/details/gt2uqzzyskg.html

Ruby: resp.code.to_i
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2axbmvbnz.html

C#:   (int)resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gt2qgyzgsjo.html

[L08] 并发请求多个地址
来源：http://dali.ivvv.top/Article/details/gt2oidvudhv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nwbrower.top/Article/details/gt2xwecejqx.html

PHP:  curl_multi_init() 系列
来源：http://dali.mhx1999.top/Article/details/gt2mazwpnfe.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yongpay.top/Article/details/gt2oqnwyrnu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gt2xlrsoand.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gaohongyu789.top/Article/details/gt2fjigqvyd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.guannengcc.top/Article/details/gt2qyqyibwq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.aibaodan.cn/Article/details/gt2vsgzrfyn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.smart0.xyz/Article/details/gt2lnwldqkc.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2tuzedopj.html

M. 命令行 / 进程 / 环境
来源：http://dali.vqdsnc.cn/Article/details/gt2hyrkotol.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2rhgtxdbp.html

[M01] 读取命令行参数
来源：http://dali.gotoacloud.top/Article/details/gt2caibfsku.html

Py:   sys.argv[1:]
来源：http://dali.shzxlz.cn/Article/details/gt2jwqgsdbq.html

PHP:  $argv;  $argc;
来源：http://dali.yongpay.top/Article/details/gt2gmuzmnxp.html

JS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gt2rklnsjgk.html

TS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gt2xjzushmx.html

Java: args 数组（main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gt2oxzuecdy.html

Go:   os.Args[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gt2evkpkxxv.html

Ruby: ARGV
来源：http://dali.jiagoushi.top/Article/details/gt2krqhxwjc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.316326.xyz/Article/details/gt2ossbfozb.html

[M02] 读取环境变量
来源：http://dali.daria6918.cn/Article/details/gt2zwamcyqt.html

Py:   os.environ.get("HOME")
来源：http://dali.hysaishi.cn/Article/details/gt2ktwactca.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.snrcjt.cn/Article/details/gt2uurorkpn.html

JS:   process.env.HOME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hbwysvnb.html

TS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gt2gjtgndik.html

Java: System.getenv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gt2ckevkiuv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.bjfxy.top/Article/details/gt2pdivzxmq.html

Ruby: ENV["HOME"]
来源：http://dali.kuanghao11.cn/Article/details/gt2vylqnvbi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fengsongda.top/Article/details/gt2lguztnfc.html

[M03] 执行外部命令
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lxflodra.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xuanzx.com/Article/details/gt2avsrzpmq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.0kj1m.cn/Article/details/gt2nhlfgtlw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yongpay.top/Article/details/gt2skijljly.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.9152youxi.cn/Article/details/gt2phjngmfr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yvedp.cn/Article/details/gt2itlrmxpp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.wangdashe.top/Article/details/gt2vcctuyew.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hfpthk.cn/Article/details/gt2ahrxntmr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shzxlz.cn/Article/details/gt2tcgdetnm.html

[M04] 获取当前工作目录
来源：http://dali.quarkkingdee.top/Article/details/gt2deklqmyf.html

Py:   os.getcwd()
来源：http://dali.xylfe.cn/Article/details/gt2hmakmphu.html

PHP:  getcwd();
来源：http://dali.dashuyun.cn/Article/details/gt2zwqufhhu.html

JS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uelypxjh.html

TS:   process.cwd()
来源：http://dali.jqgfzy.top/Article/details/gt2gmqlfgek.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.snrcjt.cn/Article/details/gt2fyfpapsx.html

Go:   os.Getwd()
来源：http://dali.cqqwz.cn/Article/details/gt2uqlbnzbz.html

Ruby: Dir.pwd
来源：http://dali.xziqi.cn/Article/details/gt2silqsahf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gotoacloud.top/Article/details/gt2ehmboefb.html

[M05] 设置退出码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gckvsska.html

Py:   sys.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mlhuetqr.html

PHP:  exit(1);
来源：http://dali.shangyingyoupin.top/Article/details/gt2njkdkhoe.html

JS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wjhbzyzi.html

TS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gt2glndvpkj.html

Java: System.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ubhrnqje.html

Go:   os.Exit(1)
来源：http://dali.hammf.cn/Article/details/gt2bcgvpjvf.html

Ruby: exit 1
来源：http://dali.jiagoushi.top/Article/details/gt2qhzaqsfh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xziqi.cn/Article/details/gt2ppfeztip.html

[M06] 向标准错误输出
来源：http://dali.ybcxt.top/Article/details/gt2elkwfmmx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fengsongda.top/Article/details/gt2oajcrked.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2zlyiljit.html

JS:   console.error("err")
来源：http://dali.hywenlv.cn/Article/details/gt2rjejhgkn.html

TS:   console.error("err")
来源：http://dali.chenzaomai.com/Article/details/gt2nbtxtmir.html

Java: System.err.println("err")
来源：http://dali.ydzc1.top/Article/details/gt2udpkcdny.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shangyingyoupin.top/Article/details/gt2nomfhlco.html

Ruby: warn "err"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kvyfyhoj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jlsjyb.cn/Article/details/gt2mazomnwz.html

[M07] 判断是否为主入口
来源：http://dali.xziqi.cn/Article/details/gt2fymbqrue.html

Py:   if __name__ == "__main__":
来源：http://dali.jianghu66.top/Article/details/gt2lusravdn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xinyue.icu/Article/details/gt2egvqpnnl.html

JS:   require.main === module
来源：http://dali.9152youxi.cn/Article/details/gt2kfqrxxij.html

TS:   require.main === module
来源：http://dali.pengpengdd.cyou/Article/details/gt2urgfoekt.html

Java: public static void main(String[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jjwojled.html

Go:   func main()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tefacggh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cucudq.cn/Article/details/gt2orfhcvoz.html

C#:   static void Main(string[] args)
来源：http://dali.ydzc1.top/Article/details/gt2lfjgwkzn.html

[M08] 获取系统与运行时信息
来源：http://dali.yj202588.top/Article/details/gt2txsfhqlg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cucudq.cn/Article/details/gt2lxvunpgi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.pengpengdd.cyou/Article/details/gt2uvxivoxn.html

JS:   process.platform;  process.version
来源：http://dali.yuanzhike.top/Article/details/gt2yslucjei.html

TS:   process.platform;  process.version
来源：http://dali.zhixingplan.top/Article/details/gt2rntmwyfl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ehwqpu.com/Article/details/gt2knmgvcua.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ivvv.top/Article/details/gt2rvqqbpwq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hfpthk.cn/Article/details/gt2uioinsxr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hnxiangtu.top/Article/details/gt2kemrnzau.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2fhmyxmxr.html

N. 数据结构与算法
来源：http://dali.cdnleiting.top/Article/details/gt2bqhwnzzv.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2ycjkgaab.html

[N01] 二分查找（有序数组）
来源：http://dali.sxryk.cn/Article/details/gt2buwrtdxg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2nllofuad.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yonumen.top/Article/details/gt2bgkozics.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shzxlz.cn/Article/details/gt2iyktmekk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.c1oappe.top/Article/details/gt2umuiukem.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gt2klflkaox.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cheryme.top/Article/details/gt2dxxbuqav.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tian-w.cn/Article/details/gt2kpgagupx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.daria6918.cn/Article/details/gt2qqrgbysc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.aibaodan.cn/Article/details/gt2nwmeuqqs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aibaodan.cn/Article/details/gt2jizgjcix.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.birdmap.top/Article/details/gt2ldcrqrnh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gt2eqfbayxq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.smart0.xyz/Article/details/gt2ekttblox.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.tanke756.top/Article/details/gt2xvfkoypt.html

Go:   slices.Sort(arr)
来源：http://dali.andypj.xyz/Article/details/gt2snymoagu.html

Ruby: arr.sort
来源：http://dali.sysykeji.top/Article/details/gt2clkrrppw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.vqdsnc.cn/Article/details/gt2oyixntsf.html

[N03] 快速排序（分治示例）
来源：http://dali.hnxiangtu.top/Article/details/gt2wxsfkytm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sxryk.cn/Article/details/gt2pmlqikxm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hfpthk.cn/Article/details/gt2euvppmlo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.quarkkingdee.top/Article/details/gt2kygpjbkc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nmyrtiqj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhiwuduotai.top/Article/details/gt2hadkcudd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.quarkkingdee.top/Article/details/gt2buyypgia.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj20258888.top/Article/details/gt2oyzkzlsr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.9152youxi.cn/Article/details/gt2nnuqorik.html

[N04] 斐波那契数列
来源：http://dali.tianlin.xyz/Article/details/gt2juarhsjy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxinkj.top/Article/details/gt2sboxqakl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hfpthk.cn/Article/details/gt2eebxkeru.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zoakupjm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gt2oxvlspmy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.quarkkingdee.top/Article/details/gt2hgljtakf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sysykeji.top/Article/details/gt2bxqdqbxz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258.top/Article/details/gt2pawpntaf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lvlpriaa.html

[N05] 最大公约数
来源：http://dali.hnqzz.top/Article/details/gt2uygeeqxs.html

Py:   math.gcd(a, b)
来源：http://dali.hysaishi.cn/Article/details/gt2bmdwdnbe.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnqzz.top/Article/details/gt2afllpqvq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangdashe.top/Article/details/gt2qdqcnxky.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jlsjyb.cn/Article/details/gt2tdfpyrsw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jyoumei.cn/Article/details/gt2ocptunxg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wncsdlet.html

Ruby: a.gcd(b)
来源：http://dali.yvedp.cn/Article/details/gt2olbzfmhx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gaohongyu789.top/Article/details/gt2pfqkswch.html

[N06] 判断回文字符串
来源：http://dali.xinyue.icu/Article/details/gt2qsulvept.html

Py:   s == s[::-1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ksfgzujb.html

PHP:  $s === strrev($s);
来源：http://dali.zhixingplan.top/Article/details/gt2esdbpplb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gt2zejylfgz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gt2hqftqsuf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sweek.top/Article/details/gt2krrjxcwn.html

Go:   // 双指针从两端比较
来源：http://dali.jyoumei.cn/Article/details/gt2mvgonogl.html

Ruby: s == s.reverse
来源：http://dali.cashguo.top/Article/details/gt2mlqbcewq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ydzc1.top/Article/details/gt2thgltrnz.html

[N07] 两数之和（返回下标）
来源：http://dali.daxiang520.top/Article/details/gt2dnsxubwm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hnqzz.top/Article/details/gt2vzrkqmvw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.fengsongda.top/Article/details/gt2puloljzf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sysykeji.top/Article/details/gt2vobjaalu.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj20258888.top/Article/details/gt2uvsnxjle.html

Java: // 手写 HashMap
来源：http://dali.gzhubu.top/Article/details/gt2spxeqoqt.html

Go:   // 手写 map[int]int
来源：http://dali.birdmap.top/Article/details/gt2amraxghj.html

Ruby: // 手写 Hash
来源：http://dali.jyoumei.cn/Article/details/gt2vnbwvgrq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.daria6918.cn/Article/details/gt2pfpmgumw.html

[N08] 生成全排列
来源：http://dali.chenlongwang.top/Article/details/gt2luxjjrkh.html

Py:   itertools.permutations(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2hnpbhdua.html

PHP:  // 手写递归交换
来源：http://dali.cdnleiting.top/Article/details/gt2ogftuyft.html

JS:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gt2urzjzpcj.html

TS:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gt2eugpstvv.html

Java: // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gt2pczsqmbd.html

Go:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gt2tmmungxb.html

Ruby: arr.permutation.to_a
来源：http://dali.cashguo.top/Article/details/gt2pbhefryn.html

C#:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gt2nizdnwaj.html

[N09] 栈与队列
来源：http://dali.zycfv.cn/Article/details/gt2oqviqxmj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hnxiangtu.top/Article/details/gt2szmslqaq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cheryme.top/Article/details/gt2uxeihfqz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gt2zcaljxhs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jiagoushi.top/Article/details/gt2pofzufwm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nanxuanxn.top/Article/details/gt2zoadhfif.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.andypj.xyz/Article/details/gt2pwszfrhj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gt2ookzuulr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hammf.cn/Article/details/gt2kkhupqao.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxsblio.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.kuanghao11.cn/Article/details/gt2ccgijsmi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj20258.top/Article/details/gt2gsimadxf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yanxiufei.cn/Article/details/gt2dbwarlhj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dianchejie.cn/Article/details/gt2falsdirc.html

Java: class Node { int v; Node next; }
来源：http://dali.aibaodan.cn/Article/details/gt2vmpowoao.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ppjwa.cn/Article/details/gt2epvndnxg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.guannengcc.top/Article/details/gt2fmihvyke.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ehwqpu.com/Article/details/gt2npbbohra.html

[N11] 二叉树中序遍历
来源：http://dali.sufxvd.cn/Article/details/gt2lctbqihl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.guannengcc.top/Article/details/gt2lhpensos.html

PHP:  // 手写递归函数
来源：http://dali.yuanzhike.top/Article/details/gt2gxyrozmw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kzbkaatx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nwbrower.top/Article/details/gt2uvsqybdf.html

Java: // 手写递归
来源：http://dali.daria6918.cn/Article/details/gt2wvexzbhe.html

Go:   // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gt2oomxjwnj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hywenlv.cn/Article/details/gt2sptvdzas.html

C#:   // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hhazhmnp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.9152youxi.cn/Article/details/gt2vtsqgjqq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.redwolf501.top/Article/details/gt2gbrdoafe.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sufxvd.cn/Article/details/gt2hkgsduzo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gt2oreyxwgn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hongshengwenyu.top/Article/details/gt2emurjecb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gt2lxqtnlyy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.meibo888.top/Article/details/gt2bvbgaueu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sufxvd.cn/Article/details/gt2ytqajybn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nwbrower.top/Article/details/gt2hnulnbjm.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2kjztvgnq.html

O. 并发与异步
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wmmssazq.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2quwywecx.html

[O01] 启动一个线程
来源：http://dali.iojbl.cn/Article/details/gt2hlpnbcut.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yvedp.cn/Article/details/gt2fpveezya.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hysaishi.cn/Article/details/gt2qfmcprhh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bjpkfsoh.html

TS:   // 同 JS
来源：http://dali.yj20258.top/Article/details/gt2qphvvrgp.html

Java: new Thread(() -> f()).start()
来源：http://dali.zdqjudy.top/Article/details/gt2cybuzvde.html

Go:   go f()
来源：http://dali.ivvv.top/Article/details/gt2xnteeibk.html

Ruby: Thread.new { f }
来源：http://dali.pycfn.com/Article/details/gt2ixfidelx.html

C#:   Task.Run(() => F());
来源：http://dali.nwbrower.top/Article/details/gt2rjfktqkg.html

[O02] 使用线程池
来源：http://dali.pycfn.com/Article/details/gt2zewqmdes.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jbhpvkql.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cheryme.top/Article/details/gt2yrjhcmqe.html

JS:   // worker_threads 线程池
来源：http://dali.hywenlv.cn/Article/details/gt2lakcjazb.html

TS:   // worker_threads 线程池
来源：http://dali.sxryk.cn/Article/details/gt2jhcoemvb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yongpay.top/Article/details/gt2ltvsjjus.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uiesgumh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sysykeji.top/Article/details/gt2subevmet.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj20258888.top/Article/details/gt2ufelrnsy.html

[O03] 加锁保护共享数据
来源：http://dali.ppjwa.cn/Article/details/gt2tajiuoko.html

Py:   with lock: shared += 1
来源：http://dali.redwolf501.top/Article/details/gt2nglmnfjh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ehwqpu.com/Article/details/gt2jbjmdxbe.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.smart0.xyz/Article/details/gt2avxrratp.html

TS:   // 同 JS
来源：http://dali.yangfankeji.com/Article/details/gt2wcvazgoh.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhixingplan.top/Article/details/gt2xyugvawx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.meibo888.top/Article/details/gt2ivhspfiz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.aizwys.cn/Article/details/gt2oslwvsit.html

C#:   lock (gate) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gt2zumbfpru.html

[O04] 定义异步函数并等待
来源：http://dali.dashuyun.cn/Article/details/gt2eawiaxaz.html

Py:   async def f():⏎    await g()
来源：http://dali.fzhhl.top/Article/details/gt2nerakgch.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hnxiangtu.top/Article/details/gt2ofixfdoj.html

JS:   async function f() { await g(); }
来源：http://dali.nwbrower.top/Article/details/gt2xoiikvva.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.fengsongda.top/Article/details/gt2kqypixdb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xinyue.icu/Article/details/gt2mmteaaxd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.vqdsnc.cn/Article/details/gt2ofxkpufj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhengqikj.top/Article/details/gt2nkhfotbq.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqoapws.html

[O05] 并发执行并等待全部完成
来源：http://dali.havefunace.top/Article/details/gt2hntsdmqa.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xylfe.cn/Article/details/gt2imyklvsx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jianghu66.top/Article/details/gt2qgsgvasm.html

JS:   await Promise.all(tasks)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xjxnehrq.html

TS:   await Promise.all(tasks)
来源：http://dali.sxryk.cn/Article/details/gt2hejgvgxp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.9152youxi.cn/Article/details/gt2oohnpnmx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.chenlongwang.top/Article/details/gt2oedoouzt.html

Ruby: threads.map(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gt2iqorfxgv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fzhhl.top/Article/details/gt2jgcmcawt.html

[O06] 使用进程池
来源：http://dali.meibo888.top/Article/details/gt2fjfyjsyt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.haohaochexian.top/Article/details/gt2nyyuxkek.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.smart0.xyz/Article/details/gt2jtalckio.html

JS:   // child_process / cluster 模块
来源：http://dali.pengpengdd.cyou/Article/details/gt2tlwlycoa.html

TS:   // child_process / cluster 模块
来源：http://dali.haohaochexian.top/Article/details/gt2jrkvqfvd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.daxiang520.top/Article/details/gt2hlceqlmx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.birdmap.top/Article/details/gt2vbtuvcot.html

Ruby: // fork 块
来源：http://dali.jqgfzy.top/Article/details/gt2yfmdgzlk.html

C#:   Parallel.For
来源：http://dali.iojbl.cn/Article/details/gt2tavbfjei.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kksbiyyr.html

P. 常用工具函数
来源：http://dali.vqdsnc.cn/Article/details/gt2uurqeiwl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwqygpl.html

[P01] 生成 UUID
来源：http://dali.zhixingplan.top/Article/details/gt2bkyzgwze.html

Py:   str(uuid.uuid4())
来源：http://dali.yj202588.top/Article/details/gt2zihlpimw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.daxiang520.top/Article/details/gt2imydyjqt.html

JS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gt2xhfpbmbr.html


<!-- 参考信息 -->