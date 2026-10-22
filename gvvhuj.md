代发 wailian999

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nqoosrys.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhiwuduotai.top/Article/details/gt2aqlymocr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tian-w.cn/Article/details/gt2mmozhfrw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xinyue.icu/Article/details/gt2rrzvhlpm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sufxvd.cn/Article/details/gt2fywheorf.html

[L04] 设置超时
来源：http://dali.mhx1999.top/Article/details/gt2zfilourd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jqgfzy.top/Article/details/gt2iijwpdlj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.guowangkeji.top/Article/details/gt2xiwkvgpg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fzhhl.top/Article/details/gt2ofjquwps.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenjidiqi.icu/Article/details/gt2vdtrekig.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aalvzzty.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cckwvqks.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yonumen.top/Article/details/gt2necpcnwp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenlongwang.top/Article/details/gt2kotodvss.html

[L05] 上传文件（multipart）
来源：http://dali.daxiang520.top/Article/details/gt2xpisvyii.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.0kj1m.cn/Article/details/gt2rwxuxwlo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jqgfzy.top/Article/details/gt2ewktivgu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnqzz.top/Article/details/gt2wwjvhhhr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sysykeji.top/Article/details/gt2iezmxcfu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.daxiang520.top/Article/details/gt2ybispksa.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hfpthk.cn/Article/details/gt2bwnaipzh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gogol.net.cn/Article/details/gt2thahgova.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2przjecdd.html

[L06] 解析响应为 JSON
来源：http://dali.xziqi.cn/Article/details/gt2lkeukqxs.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwbwbfw.html

PHP:  json_decode($body, true);
来源：http://dali.zhengqikj.top/Article/details/gt2qobjonyl.html

JS:   await resp.json()
来源：http://dali.xuanzx.com/Article/details/gt2iqrlbiwq.html

TS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gt2ketnshkq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zdqjudy.top/Article/details/gt2kfhdxovz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.meibo888.top/Article/details/gt2mczddlwb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258.top/Article/details/gt2gqmivwpx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jlsjyb.cn/Article/details/gt2ljzdjbkb.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qzzzvoqb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cucudq.cn/Article/details/gt2tsqovmnl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxinkj.top/Article/details/gt2okprbexc.html

JS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gt2wresosik.html

TS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gt2jwdtjfsd.html

Java: resp.statusCode()
来源：http://dali.havefunace.top/Article/details/gt2aseeqwsy.html

Go:   resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gt2atidguya.html

Ruby: resp.code.to_i
来源：http://dali.andypj.xyz/Article/details/gt2ypdcroii.html

C#:   (int)resp.StatusCode
来源：http://dali.andypj.xyz/Article/details/gt2uhvvaxqf.html

[L08] 并发请求多个地址
来源：http://dali.316326.xyz/Article/details/gt2ajxctzfl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.snrcjt.cn/Article/details/gt2oshlinvk.html

PHP:  curl_multi_init() 系列
来源：http://dali.cqqwz.cn/Article/details/gt2bgehpnek.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.vqdsnc.cn/Article/details/gt2paixyhxu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gt2mpocvmsa.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yueranfly.top/Article/details/gt2qypipfcq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xziqi.cn/Article/details/gt2dpmnilge.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gt2iizwldii.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.snrcjt.cn/Article/details/gt2aukypkec.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2esmjsypk.html

M. 命令行 / 进程 / 环境
来源：http://dali.yanxiufei.cn/Article/details/gt2qtoeyevv.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2biqouxyg.html

[M01] 读取命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2atroqsom.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrwmzru.html

PHP:  $argv;  $argc;
来源：http://dali.hammf.cn/Article/details/gt2swgnblbk.html

JS:   process.argv.slice(2)
来源：http://dali.cqqwz.cn/Article/details/gt2offspyom.html

TS:   process.argv.slice(2)
来源：http://dali.birdmap.top/Article/details/gt2ohlswpck.html

Java: args 数组（main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gt2rsoaaakb.html

Go:   os.Args[1:]
来源：http://dali.tianlin.xyz/Article/details/gt2ukguvfjw.html

Ruby: ARGV
来源：http://dali.yueranfly.top/Article/details/gt2dvawucsc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ybcxt.top/Article/details/gt2peuhmqjj.html

[M02] 读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gt2busgzsgd.html

Py:   os.environ.get("HOME")
来源：http://dali.yueranfly.top/Article/details/gt2bmvxavbg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gotoacloud.top/Article/details/gt2kdynmqks.html

JS:   process.env.HOME
来源：http://dali.ivvv.top/Article/details/gt2wemvwmsh.html

TS:   process.env.HOME
来源：http://dali.gogol.net.cn/Article/details/gt2rqhnnzmw.html

Java: System.getenv("HOME")
来源：http://dali.andypj.xyz/Article/details/gt2oakocted.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zdqjudy.top/Article/details/gt2vgzbxiin.html

Ruby: ENV["HOME"]
来源：http://dali.hongshengwenyu.top/Article/details/gt2nqpcdkrb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fengsongda.top/Article/details/gt2yllirvzj.html

[M03] 执行外部命令
来源：http://dali.yj20258.top/Article/details/gt2eltddkpi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.9152youxi.cn/Article/details/gt2vmnwplqa.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ybcxt.top/Article/details/gt2fmdldxpv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gzhubu.top/Article/details/gt2zqryczze.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.smart0.xyz/Article/details/gt2ntnljcpl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hnqzz.top/Article/details/gt2gdocdasj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xziqi.cn/Article/details/gt2haaqaduh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yueranfly.top/Article/details/gt2mzrfpaeq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cdnleiting.top/Article/details/gt2bdnldpfu.html

[M04] 获取当前工作目录
来源：http://dali.jiagoushi.top/Article/details/gt2tzxkkfap.html

Py:   os.getcwd()
来源：http://dali.jyoumei.cn/Article/details/gt2icoxxarw.html

PHP:  getcwd();
来源：http://dali.kuanghao11.cn/Article/details/gt2zeivdlta.html

JS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gt2yaeabjfq.html

TS:   process.cwd()
来源：http://dali.sweek.top/Article/details/gt2kbzphwto.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hammf.cn/Article/details/gt2gpjxmpuu.html

Go:   os.Getwd()
来源：http://dali.andypj.xyz/Article/details/gt2ztmueack.html

Ruby: Dir.pwd
来源：http://dali.cqqwz.cn/Article/details/gt2bnhlttnj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.9152youxi.cn/Article/details/gt2omfcaaka.html

[M05] 设置退出码
来源：http://dali.sweek.top/Article/details/gt2mjbtqtci.html

Py:   sys.exit(1)
来源：http://dali.xinyue.icu/Article/details/gt2yseuprjm.html

PHP:  exit(1);
来源：http://dali.zycfv.cn/Article/details/gt2mbwsyfiy.html

JS:   process.exit(1)
来源：http://dali.cheryme.top/Article/details/gt2bjachhdg.html

TS:   process.exit(1)
来源：http://dali.iojbl.cn/Article/details/gt2zmmhigip.html

Java: System.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gt2muacmbzj.html

Go:   os.Exit(1)
来源：http://dali.yueranfly.top/Article/details/gt2jnylbxza.html

Ruby: exit 1
来源：http://dali.cdnleiting.top/Article/details/gt2uvxfenfp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigufen.top/Article/details/gt2chblirdx.html

[M06] 向标准错误输出
来源：http://dali.svipenyu.cn/Article/details/gt2cyjywgcd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.quarkkingdee.top/Article/details/gt2wnznkccb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sufxvd.cn/Article/details/gt2ffzwcrms.html

JS:   console.error("err")
来源：http://dali.aizwys.cn/Article/details/gt2kalzpwbl.html

TS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gt2zpnxoeml.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2woxagdvt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.quarkkingdee.top/Article/details/gt2jtxmxwfv.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2egqxhgaj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenlongwang.top/Article/details/gt2bvhhlufe.html

[M07] 判断是否为主入口
来源：http://dali.haohaochexian.top/Article/details/gt2gwgvqnqf.html

Py:   if __name__ == "__main__":
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tziobznv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hysaishi.cn/Article/details/gt2fomenjln.html

JS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gt2tfzcbfcc.html

TS:   require.main === module
来源：http://dali.sweek.top/Article/details/gt2uzllqxsn.html

Java: public static void main(String[] args)
来源：http://dali.gaohongyu789.top/Article/details/gt2svaecbze.html

Go:   func main()
来源：http://dali.hfpthk.cn/Article/details/gt2btugsfcq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shzxlz.cn/Article/details/gt2umutnjlw.html

C#:   static void Main(string[] args)
来源：http://dali.xziqi.cn/Article/details/gt2fdoexqeu.html

[M08] 获取系统与运行时信息
来源：http://dali.xinyue.icu/Article/details/gt2cruazogs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yueranfly.top/Article/details/gt2yjjecjme.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gogol.net.cn/Article/details/gt2jinyfuwz.html

JS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gt2sekkbuzl.html

TS:   process.platform;  process.version
来源：http://dali.sxryk.cn/Article/details/gt2jafzmehi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cvhixumv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gwwkjtxd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ybcxt.top/Article/details/gt2olsflksi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.316326.xyz/Article/details/gt2xssfhcfr.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2pyzhcnte.html

N. 数据结构与算法
来源：http://dali.jinqigfzy.top/Article/details/gt2dmccqkqn.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2wjqxrvbv.html

[N01] 二分查找（有序数组）
来源：http://dali.zhengqikj.top/Article/details/gt2kcvmfrvm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gt2jxzwdluw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cheryme.top/Article/details/gt2ugagfdll.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gt2tutvykts.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hywenlv.cn/Article/details/gt2pvltcywc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gt2dmpzzwkf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2oovstbgv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gogol.net.cn/Article/details/gt2srctqbgm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ixnzzfia.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.svipenyu.cn/Article/details/gt2smdgrnoa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ivvv.top/Article/details/gt2bhcmktim.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jlsjyb.cn/Article/details/gt2sicyhczs.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gt2oxnkbqtu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gt2qjkuncel.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xinyue.icu/Article/details/gt2skqqrreh.html

Go:   slices.Sort(arr)
来源：http://dali.sxryk.cn/Article/details/gt2pxxmxhig.html

Ruby: arr.sort
来源：http://dali.chenjidiqi.icu/Article/details/gt2xhuyooei.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kptlkxdr.html

[N03] 快速排序（分治示例）
来源：http://dali.yj20258888.top/Article/details/gt2uxzjnbbs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.havefunace.top/Article/details/gt2yimphfxz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenlongwang.top/Article/details/gt2mznephfo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgufenzy.top/Article/details/gt2zcxudout.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtklwui.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ybcxt.top/Article/details/gt2czpoewjf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yanxiufei.cn/Article/details/gt2tadlhrsk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tianlin.xyz/Article/details/gt2kwklgnns.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhongyouzk.top/Article/details/gt2iislfpgv.html

[N04] 斐波那契数列
来源：http://dali.ivvv.top/Article/details/gt2szurxkfj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.daxiang520.top/Article/details/gt2whmeseie.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.0kj1m.cn/Article/details/gt2gygcwpbu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gt2yingwtlt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gt2vcksqcmq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.iojbl.cn/Article/details/gt2cbxbltax.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cucudq.cn/Article/details/gt2ojgxdpgj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tianlin.xyz/Article/details/gt2cpeonmht.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gt2ynadjqps.html

[N05] 最大公约数
来源：http://dali.yvedp.cn/Article/details/gt2ydwczxbn.html

Py:   math.gcd(a, b)
来源：http://dali.jyoumei.cn/Article/details/gt2xakzbfdd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhixingplan.top/Article/details/gt2szqjqdgb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ccnkyopc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gt2yonnrjlm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guannengcc.top/Article/details/gt2pudxqvci.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yuxming.cn/Article/details/gt2khuvmgwf.html

Ruby: a.gcd(b)
来源：http://dali.xziqi.cn/Article/details/gt2usgdzaop.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.dianchejie.cn/Article/details/gt2pgryggyw.html

[N06] 判断回文字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2ihzswcam.html

Py:   s == s[::-1]
来源：http://dali.mhx1999.top/Article/details/gt2aeqjprqc.html

PHP:  $s === strrev($s);
来源：http://dali.zycfv.cn/Article/details/gt2lssxfwrw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gt2sbnvpjjd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gt2edsupwqg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.daxiang520.top/Article/details/gt2rmrpqmew.html

Go:   // 双指针从两端比较
来源：http://dali.fengsongda.top/Article/details/gt2rzfvxepa.html

Ruby: s == s.reverse
来源：http://dali.cheryme.top/Article/details/gt2xybqznbr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sufxvd.cn/Article/details/gt2gmzybihd.html

[N07] 两数之和（返回下标）
来源：http://dali.ydzc1.top/Article/details/gt2taafbeua.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ektiqwfq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tanke756.top/Article/details/gt2srzcddsz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.birdmap.top/Article/details/gt2iqvqokay.html

TS:   // 手写 Map<string, number>
来源：http://dali.ivvv.top/Article/details/gt2qidfkdli.html

Java: // 手写 HashMap
来源：http://dali.0kj1m.cn/Article/details/gt2ftptfqvk.html

Go:   // 手写 map[int]int
来源：http://dali.wangdashe.top/Article/details/gt2xqlamqzw.html

Ruby: // 手写 Hash
来源：http://dali.zdqjudy.top/Article/details/gt2rftjrbhm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jianghu66.top/Article/details/gt2hkwpmmgi.html

[N08] 生成全排列
来源：http://dali.chenjidiqi.icu/Article/details/gt2reguacwc.html

Py:   itertools.permutations(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2totwxwpa.html

PHP:  // 手写递归交换
来源：http://dali.yvedp.cn/Article/details/gt2knmiemnc.html

JS:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gt2luceysdd.html

TS:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gt2naeqrpbl.html

Java: // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2wcavqioe.html

Go:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gt2ftxjjvry.html

Ruby: arr.permutation.to_a
来源：http://dali.yonumen.top/Article/details/gt2mqjqrrlz.html

C#:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gt2qvonrkxt.html

[N09] 栈与队列
来源：http://dali.0kj1m.cn/Article/details/gt2yzbjxgxf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.9152youxi.cn/Article/details/gt2apsfksnn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ivvv.top/Article/details/gt2gvgmzbxc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gt2byqcorca.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhoulong.xyz/Article/details/gt2yblipfni.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2evvymtun.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shuidangran.top/Article/details/gt2aqoavwhz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zycfv.cn/Article/details/gt2xoavaznq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gaohongyu789.top/Article/details/gt2bjbjzvad.html

[N10] 链表节点定义
来源：http://dali.cucudq.cn/Article/details/gt2ywcrcarx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jnhtnnzk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xinyue.icu/Article/details/gt2wkyxkrzw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gogol.net.cn/Article/details/gt2efzackox.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jlsjyb.cn/Article/details/gt2kbgiaqgl.html

Java: class Node { int v; Node next; }
来源：http://dali.aibaodan.cn/Article/details/gt2uxjembuf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj202588.top/Article/details/gt2aofotuak.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.dianchejie.cn/Article/details/gt2iecmfyly.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lhkjbirh.html

[N11] 二叉树中序遍历
来源：http://dali.iojbl.cn/Article/details/gt2injibqcp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tgybzwlr.html

PHP:  // 手写递归函数
来源：http://dali.yj20258888.top/Article/details/gt2qneyixok.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zdqjudy.top/Article/details/gt2dptgbjcp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gt2wngfcpuw.html

Java: // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mmjqwsew.html

Go:   // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gt2kvrkfyem.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2anbhnjow.html

C#:   // 手写递归
来源：http://dali.fzhhl.top/Article/details/gt2lmhswvap.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nnebmhzj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ybcxt.top/Article/details/gt2wgwshbab.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.svipenyu.cn/Article/details/gt2bwhvkgvs.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhongyouzk.top/Article/details/gt2kqxgaxnb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.quarkkingdee.top/Article/details/gt2mbepwbuv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigfzy.top/Article/details/gt2vcihazcm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2syiznist.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jyoumei.cn/Article/details/gt2vnrjwkpj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj202588.top/Article/details/gt2pdnbymsj.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2rqdmfrhq.html

O. 并发与异步
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ijiwovum.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2ckutdxsg.html

[O01] 启动一个线程
来源：http://dali.zhixingplan.top/Article/details/gt2vlfezubk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tian-w.cn/Article/details/gt2nozifqnz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jianghu66.top/Article/details/gt2pqxfnepw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.fzhhl.top/Article/details/gt2kadtbjhx.html

TS:   // 同 JS
来源：http://dali.316326.xyz/Article/details/gt2vxhpujgd.html

Java: new Thread(() -> f()).start()
来源：http://dali.shuidangran.top/Article/details/gt2mszlvcok.html

Go:   go f()
来源：http://dali.cucudq.cn/Article/details/gt2mnmhsbpg.html

Ruby: Thread.new { f }
来源：http://dali.pengpengdd.cyou/Article/details/gt2qqqfcehc.html

C#:   Task.Run(() => F());
来源：http://dali.jqgufenzy.top/Article/details/gt2tppuefqe.html

[O02] 使用线程池
来源：http://dali.xylfe.cn/Article/details/gt2wtphkujl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.snrcjt.cn/Article/details/gt2wjgfqvcx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gzhubu.top/Article/details/gt2swngxlpp.html

JS:   // worker_threads 线程池
来源：http://dali.cdnleiting.top/Article/details/gt2dltihtok.html

TS:   // worker_threads 线程池
来源：http://dali.vqdsnc.cn/Article/details/gt2gjfyrxuc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.svipenyu.cn/Article/details/gt2hwvgyibt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gzhubu.top/Article/details/gt2xorvezgh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cheryme.top/Article/details/gt2yikajadj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.dianchejie.cn/Article/details/gt2ohagjgrn.html

[O03] 加锁保护共享数据
来源：http://dali.xziqi.cn/Article/details/gt2zpsnpteb.html

Py:   with lock: shared += 1
来源：http://dali.jyoumei.cn/Article/details/gt2shmqiqzs.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.nwbrower.top/Article/details/gt2rnqpyjrf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jiagoushi.top/Article/details/gt2yfgkbupi.html

TS:   // 同 JS
来源：http://dali.havefunace.top/Article/details/gt2bbbbztze.html

Java: synchronized (this) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2juckayvy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jlsjyb.cn/Article/details/gt2kifwwwzz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2raoqsncw.html

C#:   lock (gate) { shared++; }
来源：http://dali.dianchejie.cn/Article/details/gt2zsuzotxh.html

[O04] 定义异步函数并等待
来源：http://dali.aizwys.cn/Article/details/gt2xemjcehm.html

Py:   async def f():⏎    await g()
来源：http://dali.birdmap.top/Article/details/gt2ictfzthq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2awhnytfn.html

JS:   async function f() { await g(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tlluptir.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hammf.cn/Article/details/gt2mewbaxpj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.meibo888.top/Article/details/gt2auqdljhp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xuetiantiany.cn/Article/details/gt2nseyhcqq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shuidangran.top/Article/details/gt2qktggbrv.html

C#:   async Task F() { await G(); }
来源：http://dali.ivvv.top/Article/details/gt2lmcrxyok.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenjidiqi.icu/Article/details/gt2gfpcpuxp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cdnleiting.top/Article/details/gt2cqdetsfz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jianghu66.top/Article/details/gt2yafuitwa.html

JS:   await Promise.all(tasks)
来源：http://dali.gzhubu.top/Article/details/gt2pamcoyhs.html

TS:   await Promise.all(tasks)
来源：http://dali.ppjwa.cn/Article/details/gt2pbakwjxp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wgtqlbgk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2shajuztb.html

Ruby: threads.map(&:join)
来源：http://dali.dianchejie.cn/Article/details/gt2hcgqqgbl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ghznuohj.html

[O06] 使用进程池
来源：http://dali.yj20258.top/Article/details/gt2kxbpqogb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.iojbl.cn/Article/details/gt2tnyuwhzk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jianghu66.top/Article/details/gt2entnkgmp.html

JS:   // child_process / cluster 模块
来源：http://dali.jlsjyb.cn/Article/details/gt2nyxzgqlu.html

TS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gt2takqyvko.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jlsjyb.cn/Article/details/gt2mebjdsdn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2limjdesi.html

Ruby: // fork 块
来源：http://dali.chenzaomai.com/Article/details/gt2dewnzrkf.html

C#:   Parallel.For
来源：http://dali.ivvv.top/Article/details/gt2ugteufht.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2jbcahcta.html

P. 常用工具函数
来源：http://dali.nanxuanxn.top/Article/details/gt2runnpota.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2wjkbhyiw.html

[P01] 生成 UUID
来源：http://dali.gotoacloud.top/Article/details/gt2usjappoz.html

Py:   str(uuid.uuid4())
来源：http://dali.sysykeji.top/Article/details/gt2jecvmjqt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oezktrat.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjvujfo.html


<!-- 参考信息 -->