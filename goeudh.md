代发 wailian999

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sweek.top/Article/details/gt2jpbrqqif.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ppjwa.cn/Article/details/gt2kalbzygi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zdqjudy.top/Article/details/gt2rvrabjvv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yongpay.top/Article/details/gt2pdjugghq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nanxuanxn.top/Article/details/gt2xqlbburf.html

[L04] 设置超时
来源：http://dali.yvedp.cn/Article/details/gt2iuqffdrt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhiwuduotai.top/Article/details/gt2bvhrmpum.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fzhhl.top/Article/details/gt2vgyrblth.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.9152youxi.cn/Article/details/gt2iuwkfabn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.snrcjt.cn/Article/details/gt2sefcqyjf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.quarkkingdee.top/Article/details/gt2jmowoxyv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhiwuduotai.top/Article/details/gt2juuvqrmm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zycfv.cn/Article/details/gt2ukfyksux.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.9152youxi.cn/Article/details/gt2jvtsfyqr.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2mvaujzjl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.wangshuangyany.cn/Article/details/gt2ipmdyqja.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shzxlz.cn/Article/details/gt2qlzuioed.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pengpengdd.cyou/Article/details/gt2fwatwmqf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gt2aufumsae.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yueranfly.top/Article/details/gt2ajzhtfok.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.316326.xyz/Article/details/gt2bormnnjj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhiwuduotai.top/Article/details/gt2lxhqmbyb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2eirzqtcw.html

[L06] 解析响应为 JSON
来源：http://dali.redwolf501.top/Article/details/gt2xdfyvjqg.html

Py:   resp.json()
来源：http://dali.cqqwz.cn/Article/details/gt2gerrvbnn.html

PHP:  json_decode($body, true);
来源：http://dali.yj20258.top/Article/details/gt2qsrnipkb.html

JS:   await resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nsqhgwck.html

TS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gt2gxkjcatv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gt2zwlluqve.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guannengcc.top/Article/details/gt2hatoyfla.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jianghu66.top/Article/details/gt2fkovaqkh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhiwuduotai.top/Article/details/gt2zkloccrt.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gt2ogbykljv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2felmrisr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenzaomai.com/Article/details/gt2omabgaxz.html

JS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gt2wbujekpv.html

TS:   resp.ok;  resp.status
来源：http://dali.nanxuanxn.top/Article/details/gt2gcngmzzs.html

Java: resp.statusCode()
来源：http://dali.jiagoushi.top/Article/details/gt2mtezuxvo.html

Go:   resp.StatusCode
来源：http://dali.jinqigufen.top/Article/details/gt2vxvnlfua.html

Ruby: resp.code.to_i
来源：http://dali.guowangkeji.top/Article/details/gt2spgbjcyw.html

C#:   (int)resp.StatusCode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ppsaioop.html

[L08] 并发请求多个地址
来源：http://dali.daria6918.cn/Article/details/gt2wfnkptrw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yongpay.top/Article/details/gt2qzwxqeej.html

PHP:  curl_multi_init() 系列
来源：http://dali.daria6918.cn/Article/details/gt2borpkymy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gt2uuridiqi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gt2irewvmfr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhongyouzk.top/Article/details/gt2cqfdofar.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gogol.net.cn/Article/details/gt2gqkacnvo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gt2tkujrgiz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xinyue.icu/Article/details/gt2qywgnaxt.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2ourztdno.html

M. 命令行 / 进程 / 环境
来源：http://dali.nanxinkj.top/Article/details/gt2nhypdamk.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2zxdtzmtf.html

[M01] 读取命令行参数
来源：http://dali.chenlongwang.top/Article/details/gt2ielkfndn.html

Py:   sys.argv[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gt2rjmhornx.html

PHP:  $argv;  $argc;
来源：http://dali.jlsjyb.cn/Article/details/gt2khdtzzxf.html

JS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gt2rgpdwtio.html

TS:   process.argv.slice(2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2spqulmlx.html

Java: args 数组（main 方法参数）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2prscbkyn.html

Go:   os.Args[1:]
来源：http://dali.yj202588.top/Article/details/gt2woxdjowz.html

Ruby: ARGV
来源：http://dali.cashguo.top/Article/details/gt2tsyvjsiq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nanxuanxn.top/Article/details/gt2wmturblk.html

[M02] 读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gt2gbunkxgk.html

Py:   os.environ.get("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gt2amuauldk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sxryk.cn/Article/details/gt2huyxeuxa.html

JS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gt2ilvzgejl.html

TS:   process.env.HOME
来源：http://dali.nwbrower.top/Article/details/gt2oafozvlb.html

Java: System.getenv("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2chpxpvlz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.aibaodan.cn/Article/details/gt2cwvzogxr.html

Ruby: ENV["HOME"]
来源：http://dali.cucudq.cn/Article/details/gt2vyrnqhmt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vdcikptv.html

[M03] 执行外部命令
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zaciyuts.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daria6918.cn/Article/details/gt2jamfvvjq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fzhhl.top/Article/details/gt2fkxsmgjo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.c1oappe.top/Article/details/gt2zwdsxlyq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.pycfn.com/Article/details/gt2wcmarcrf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xinyue.icu/Article/details/gt2nzuatafh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2ziagyypl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yangfankeji.com/Article/details/gt2fghjdmcq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhoulong.xyz/Article/details/gt2latodwrb.html

[M04] 获取当前工作目录
来源：http://dali.snrcjt.cn/Article/details/gt2dbcvderu.html

Py:   os.getcwd()
来源：http://dali.feifeiyinyue.top/Article/details/gt2bsjonbdn.html

PHP:  getcwd();
来源：http://dali.hysaishi.cn/Article/details/gt2rjsdbdmk.html

JS:   process.cwd()
来源：http://dali.feifeiyinyue.top/Article/details/gt2zlhaoiuf.html

TS:   process.cwd()
来源：http://dali.xylfe.cn/Article/details/gt2qahhjhdx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.iojbl.cn/Article/details/gt2tvtgqmuw.html

Go:   os.Getwd()
来源：http://dali.gogol.net.cn/Article/details/gt2qaziltbt.html

Ruby: Dir.pwd
来源：http://dali.c1oappe.top/Article/details/gt2cqjvifxx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenjidiqi.icu/Article/details/gt2achybnrq.html

[M05] 设置退出码
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pfeqaxxg.html

Py:   sys.exit(1)
来源：http://dali.ydzc1.top/Article/details/gt2twpjvjdy.html

PHP:  exit(1);
来源：http://dali.daxiang520.top/Article/details/gt2sgybftga.html

JS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gt2khbdmydh.html

TS:   process.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wgrngsvj.html

Java: System.exit(1)
来源：http://dali.pycfn.com/Article/details/gt2wqealbov.html

Go:   os.Exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2usnoscbx.html

Ruby: exit 1
来源：http://dali.guowangkeji.top/Article/details/gt2neuzxxar.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dashuyun.cn/Article/details/gt2vhecmvxw.html

[M06] 向标准错误输出
来源：http://dali.316326.xyz/Article/details/gt2juoujtyo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258.top/Article/details/gt2avbhedfo.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhiwuduotai.top/Article/details/gt2oxubaqnb.html

JS:   console.error("err")
来源：http://dali.redwolf501.top/Article/details/gt2iiakyaig.html

TS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gt2dlhqkfnq.html

Java: System.err.println("err")
来源：http://dali.fengsongda.top/Article/details/gt2lbwmutjw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hfpthk.cn/Article/details/gt2nijuxteb.html

Ruby: warn "err"
来源：http://dali.zhengqikj.top/Article/details/gt2jnuxwqvi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gzhubu.top/Article/details/gt2sbslyeln.html

[M07] 判断是否为主入口
来源：http://dali.tian-w.cn/Article/details/gt2ynnttpqd.html

Py:   if __name__ == "__main__":
来源：http://dali.shuidangran.top/Article/details/gt2anbvgtjc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.meibo888.top/Article/details/gt2mswjktax.html

JS:   require.main === module
来源：http://dali.shuidangran.top/Article/details/gt2zqkgjwdu.html

TS:   require.main === module
来源：http://dali.9152youxi.cn/Article/details/gt2osvxivyb.html

Java: public static void main(String[] args)
来源：http://dali.haohaochexian.top/Article/details/gt2ahjgccnp.html

Go:   func main()
来源：http://dali.sweek.top/Article/details/gt2fmkjldtu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tian-w.cn/Article/details/gt2orvlgmto.html

C#:   static void Main(string[] args)
来源：http://dali.sysykeji.top/Article/details/gt2pwmqxmtj.html

[M08] 获取系统与运行时信息
来源：http://dali.zdqjudy.top/Article/details/gt2uzpbxsrs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hysaishi.cn/Article/details/gt2rcsphrsa.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenjidiqi.icu/Article/details/gt2xuanevwf.html

JS:   process.platform;  process.version
来源：http://dali.havefunace.top/Article/details/gt2dottexxq.html

TS:   process.platform;  process.version
来源：http://dali.316326.xyz/Article/details/gt2phseufao.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.quarkkingdee.top/Article/details/gt2pqocbeuq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.mhx1999.top/Article/details/gt2bqsmnmsx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ybcxt.top/Article/details/gt2pcllzlqp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ydzc1.top/Article/details/gt2cufeqpzn.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2dsysfrki.html

N. 数据结构与算法
来源：http://dali.yj20258.top/Article/details/gt2kiwdnsla.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2pvcvimrp.html

[N01] 二分查找（有序数组）
来源：http://dali.nanxinkj.top/Article/details/gt2xxcqyxdi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2qnbfbzyb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.mhx1999.top/Article/details/gt2mzvltkuc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dashuyun.cn/Article/details/gt2enpftznz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guannengcc.top/Article/details/gt2rbdpgdyx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.c1oappe.top/Article/details/gt2biquarpd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vbrnaatt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nwbrower.top/Article/details/gt2juhofsqu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tanke756.top/Article/details/gt2lmhkkbry.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xinyue.icu/Article/details/gt2oszpkvez.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuanzhike.top/Article/details/gt2ankthjnx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gzhubu.top/Article/details/gt2aswkyohi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ydzc1.top/Article/details/gt2wbpgzwff.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ybcxt.top/Article/details/gt2knqwkhyp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj20258.top/Article/details/gt2qxibxhgr.html

Go:   slices.Sort(arr)
来源：http://dali.yonumen.top/Article/details/gt2zlpzvmle.html

Ruby: arr.sort
来源：http://dali.hnqzz.top/Article/details/gt2nbkuzmpp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.bjfxy.top/Article/details/gt2rjwosdwn.html

[N03] 快速排序（分治示例）
来源：http://dali.ydzc1.top/Article/details/gt2rryqfgns.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj202588.top/Article/details/gt2almgnukv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shzxlz.cn/Article/details/gt2mormbnge.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.andypj.xyz/Article/details/gt2lgvuwnac.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cheryme.top/Article/details/gt2xpwjrcds.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ybcxt.top/Article/details/gt2lcuxqwkx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenzaomai.com/Article/details/gt2pbsjehng.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.fzhhl.top/Article/details/gt2qdacrled.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hammf.cn/Article/details/gt2krcodtje.html

[N04] 斐波那契数列
来源：http://dali.yj20258888.top/Article/details/gt2bzjykrmq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gt2uaewyoqs.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gt2oshovgfi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gt2tacbotuy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gt2cgfepzqf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.bjfxy.top/Article/details/gt2udkerikd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yongpay.top/Article/details/gt2swlfldba.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhengqikj.top/Article/details/gt2rcnldmmb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gt2jodhjyhy.html

[N05] 最大公约数
来源：http://dali.zhoulong.xyz/Article/details/gt2kdvdydol.html

Py:   math.gcd(a, b)
来源：http://dali.cashguo.top/Article/details/gt2qvjtxxat.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.0kj1m.cn/Article/details/gt2vtcemptx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gt2wzuqfctb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuanzx.com/Article/details/gt2eteuuuei.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.smart0.xyz/Article/details/gt2rpmhldix.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zkbgkrpy.html

Ruby: a.gcd(b)
来源：http://dali.quarkkingdee.top/Article/details/gt2isqebwmd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sweek.top/Article/details/gt2mgjukrhl.html

[N06] 判断回文字符串
来源：http://dali.zhengqikj.top/Article/details/gt2lgemarah.html

Py:   s == s[::-1]
来源：http://dali.shzxlz.cn/Article/details/gt2xgedmyfg.html

PHP:  $s === strrev($s);
来源：http://dali.jqgfzy.top/Article/details/gt2rjhclamb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gt2xgdintqv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gt2ejlaslav.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hysaishi.cn/Article/details/gt2xhbfugkp.html

Go:   // 双指针从两端比较
来源：http://dali.jyoumei.cn/Article/details/gt2xzodpova.html

Ruby: s == s.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gt2qzjtlprd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gt2dhdgtstr.html

[N07] 两数之和（返回下标）
来源：http://dali.gzhubu.top/Article/details/gt2lbrivpfx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.aizwys.cn/Article/details/gt2jbevtvti.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hnxiangtu.top/Article/details/gt2gavpgasu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.dianchejie.cn/Article/details/gt2tpgadblg.html

TS:   // 手写 Map<string, number>
来源：http://dali.hysaishi.cn/Article/details/gt2ztmagjed.html

Java: // 手写 HashMap
来源：http://dali.yanxiufei.cn/Article/details/gt2cmbzyiyf.html

Go:   // 手写 map[int]int
来源：http://dali.hywenlv.cn/Article/details/gt2rvxqtybw.html

Ruby: // 手写 Hash
来源：http://dali.nanxuanxn.top/Article/details/gt2aypifamz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hywenlv.cn/Article/details/gt2poqyshwp.html

[N08] 生成全排列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ctdidicj.html

Py:   itertools.permutations(arr)
来源：http://dali.yonumen.top/Article/details/gt2mzmucnda.html

PHP:  // 手写递归交换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aiyqjmax.html

JS:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2jrkftnpw.html

TS:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gt2astaemjb.html

Java: // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gt2didocxzo.html

Go:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gt2bjyvapzy.html

Ruby: arr.permutation.to_a
来源：http://dali.svipenyu.cn/Article/details/gt2hqggxjpb.html

C#:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gt2pnetrtho.html

[N09] 栈与队列
来源：http://dali.9152youxi.cn/Article/details/gt2rvcdjond.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sufxvd.cn/Article/details/gt2ilgvrvne.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.smart0.xyz/Article/details/gt2vxyzcpbp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gt2nelgoicx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nwbrower.top/Article/details/gt2nlwmshfi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ppjwa.cn/Article/details/gt2nhjpzfjn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ehwqpu.com/Article/details/gt2gytlzhva.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gt2dgmyucch.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.birdmap.top/Article/details/gt2cgeowghg.html

[N10] 链表节点定义
来源：http://dali.chenjidiqi.icu/Article/details/gt2nclpbtdj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.fengsongda.top/Article/details/gt2qbkbzjtn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mubchjrj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.chenlongwang.top/Article/details/gt2pnnyrwpa.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.pycfn.com/Article/details/gt2tgyoagnb.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258.top/Article/details/gt2esqiusbj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hfpthk.cn/Article/details/gt2fduvmpfx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shuidangran.top/Article/details/gt2qmnagdfl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.fengsongda.top/Article/details/gt2ifaripoc.html

[N11] 二叉树中序遍历
来源：http://dali.guannengcc.top/Article/details/gt2gwhxilxh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.birdmap.top/Article/details/gt2vmfzgeis.html

PHP:  // 手写递归函数
来源：http://dali.yuxming.cn/Article/details/gt2rcofrcdq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shzxlz.cn/Article/details/gt2ngihefkb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258888.top/Article/details/gt2subnwwhq.html

Java: // 手写递归
来源：http://dali.hfpthk.cn/Article/details/gt2kevjbcaf.html

Go:   // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cikydwnk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.wangshuangyany.cn/Article/details/gt2pjeulpqh.html

C#:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gt2nlhlrehw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.birdmap.top/Article/details/gt2giehlpgs.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.dianchejie.cn/Article/details/gt2ipnvqsas.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yonumen.top/Article/details/gt2fggnwlmr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yonumen.top/Article/details/gt2pezxbosv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ydzc1.top/Article/details/gt2vhsusyjf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj202588.top/Article/details/gt2fldzxtsn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.iojbl.cn/Article/details/gt2ihjhmkjv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.daria6918.cn/Article/details/gt2bxdlcktx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.andypj.xyz/Article/details/gt2kagjjkab.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2tlbhysdh.html

O. 并发与异步
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hmrdbzoy.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2rvrrijgm.html

[O01] 启动一个线程
来源：http://dali.shangyingyoupin.top/Article/details/gt2oejcobsx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.0kj1m.cn/Article/details/gt2ynpezyol.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2nhkqxcnq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinqigufen.top/Article/details/gt2ntbngumv.html

TS:   // 同 JS
来源：http://dali.redwolf501.top/Article/details/gt2kgbuhtxq.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhoulong.xyz/Article/details/gt2rojpnfmq.html

Go:   go f()
来源：http://dali.cashguo.top/Article/details/gt2qshqqggc.html

Ruby: Thread.new { f }
来源：http://dali.yj20258.top/Article/details/gt2ibhiatpu.html

C#:   Task.Run(() => F());
来源：http://dali.jinqigufen.top/Article/details/gt2rmmngoum.html

[O02] 使用线程池
来源：http://dali.316326.xyz/Article/details/gt2vgoghtbt.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gogol.net.cn/Article/details/gt2fvmbcoxo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bozhgbnz.html

JS:   // worker_threads 线程池
来源：http://dali.jqgfzy.top/Article/details/gt2osydgsju.html

TS:   // worker_threads 线程池
来源：http://dali.yvedp.cn/Article/details/gt2rhdfpfgm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cheryme.top/Article/details/gt2ggwjydsj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj202588.top/Article/details/gt2vwjmsfli.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.mhx1999.top/Article/details/gt2agbtfuzq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hysaishi.cn/Article/details/gt2rczpyiwm.html

[O03] 加锁保护共享数据
来源：http://dali.nwbrower.top/Article/details/gt2sjwgyylj.html

Py:   with lock: shared += 1
来源：http://dali.jinqigufen.top/Article/details/gt2peslvtkn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yuanzhike.top/Article/details/gt2wviocdyi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cqqwz.cn/Article/details/gt2aunscxvn.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gt2pdunmrbr.html

Java: synchronized (this) { shared++; }
来源：http://dali.guowangkeji.top/Article/details/gt2tblnoweq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.quarkkingdee.top/Article/details/gt2ehyqjaqp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ydzc1.top/Article/details/gt2orzwmzxo.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhixingplan.top/Article/details/gt2raibweqa.html

[O04] 定义异步函数并等待
来源：http://dali.guowangkeji.top/Article/details/gt2cmossszo.html

Py:   async def f():⏎    await g()
来源：http://dali.hnqzz.top/Article/details/gt2mmshwxtt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nanxinkj.top/Article/details/gt2utyxzisu.html

JS:   async function f() { await g(); }
来源：http://dali.xylfe.cn/Article/details/gt2nkoucvlx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gotoacloud.top/Article/details/gt2moguxmoz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jqgufenzy.top/Article/details/gt2wdwuwfct.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gotoacloud.top/Article/details/gt2afolfxyp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenzaomai.com/Article/details/gt2afppvses.html

C#:   async Task F() { await G(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2uhdniqly.html

[O05] 并发执行并等待全部完成
来源：http://dali.snrcjt.cn/Article/details/gt2zaszjkln.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ybcxt.top/Article/details/gt2amarjdyt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.c1oappe.top/Article/details/gt2jmsiktyk.html

JS:   await Promise.all(tasks)
来源：http://dali.hysaishi.cn/Article/details/gt2kplsrkyt.html

TS:   await Promise.all(tasks)
来源：http://dali.redwolf501.top/Article/details/gt2irdtsbor.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ydzc1.top/Article/details/gt2hgfwtvsn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.mhx1999.top/Article/details/gt2wfzbdtxu.html

Ruby: threads.map(&:join)
来源：http://dali.9152youxi.cn/Article/details/gt2qkevrkpi.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ppjwa.cn/Article/details/gt2bocemcmi.html

[O06] 使用进程池
来源：http://dali.gogol.net.cn/Article/details/gt2uexxfwso.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.vqdsnc.cn/Article/details/gt2caxfwbce.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jlsjyb.cn/Article/details/gt2yuzmvwzl.html

JS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gt2lxcsphhg.html

TS:   // child_process / cluster 模块
来源：http://dali.nwbrower.top/Article/details/gt2kbwpxefh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.316326.xyz/Article/details/gt2menznpxq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cdnleiting.top/Article/details/gt2jitxwfqd.html

Ruby: // fork 块
来源：http://dali.gzhubu.top/Article/details/gt2gqzfjzom.html

C#:   Parallel.For
来源：http://dali.cqqwz.cn/Article/details/gt2zphgsede.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2upaibnho.html

P. 常用工具函数
来源：http://dali.ybcxt.top/Article/details/gt2ymstpmbu.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zqhmcssj.html

[P01] 生成 UUID
来源：http://dali.yanxiufei.cn/Article/details/gt2ylqtwdfu.html

Py:   str(uuid.uuid4())
来源：http://dali.jyoumei.cn/Article/details/gt2yjetqeyu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hfpthk.cn/Article/details/gt2jerafeis.html

JS:   crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gt2yivnyhgj.html


<!-- 参考信息 -->