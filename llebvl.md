代发 wailian999

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbfzvje.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2nyquoifz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjstbsz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvwkngm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzldamqi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wviywpkd.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtwosce.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2pkeigyco.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhiacge.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwdfulz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2nqppmdpz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2hraooyfa.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2plelmonq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2gvddqqjt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2difsdlpk.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ketwlevo.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2mknmalci.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgavxkph.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2eaeviirv.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2itppncgi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2maalwwco.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqilaaqp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucokojoy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsohmuqb.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fiysivlp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsfnkod.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2hehdzsjm.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2phibimwo.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2umcyhmvk.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2irddxutm.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqcpgda.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2meccympj.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjdhsqz.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqxgupt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfjamny.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2oakbvbtm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwcwxsb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2oimzqjqs.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkagrwi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrfqcde.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2jinziian.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbwhwan.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nmduflxa.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrawiun.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bhncterb.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2clznvrtr.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcuyvoj.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnlwirs.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcfdkrp.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2weetetqr.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhsfzef.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzbsuxe.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvxvesj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2uybqalzq.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nmquanfi.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfodqmof.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxypxquf.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2udeotjhj.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2tvoqaxry.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhoyzzo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlwroil.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnrphpx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2akzewinp.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrzynwv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlxpecj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2jenvvwfp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2likwoxvx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kevywzcb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2osxituno.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2ojelxcli.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2xrslpkkp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2mkeelzak.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhdfnkc.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnkrqen.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhinkti.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2irxddgru.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbopbzv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmhlgmf.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwhljux.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2czqyjfbd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfjiqeg.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2acejehmj.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeyzdaua.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsohineh.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpbvvwj.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrhkgxy.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzxacpc.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbglvncp.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mksbqvmy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2idjbyzva.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwvwekx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrderaaq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvjkfve.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqpsvve.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfafwmwl.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrlkvmm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvppjdc.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpszkii.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgutfkr.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2xqivsrit.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2chtqjsta.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzzgczo.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2xibgraov.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2slihcmve.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2xubwisog.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqjacmn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2rvctirxr.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2mytqpkdc.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlipzuv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2xslzpkxd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgnmrqk.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2xciaiebv.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvcuopx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2btnqgybe.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2lylltnuh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2fdegyfao.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmzgexy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2irdqsqgt.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmunoym.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnprtze.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2bthmogbo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfcfgam.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhplhpl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxkvogn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvhyoxt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pufsjomi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzskrmz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgzxuuq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eirkxvbv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2yaolzpox.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjstrzsc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdgsfqs.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzzkwyu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqhgntt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tposalif.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmceapbs.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrajmyr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqyyhvt.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmvzmlz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2wyupjwmu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2varyxelc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ounscqyr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2hzabvrpn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtnpizt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdgxkvv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyvtczr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2yyksyxum.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjihnpt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvngcwl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xphxoeiz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pykyawxl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyewbryz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwghgmfp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kihitcgq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qldwhzbw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkaegpfd.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnpsatu.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqesjvz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgbirjm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvclcju.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvuufyxh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2nwionrao.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gldqjore.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tthemksw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2olkblpsh.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtsqiap.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2oerzkjap.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcqkjba.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgitoxlt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ablxknpc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbsohnp.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvohwyy.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2tkytctpo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxoytjr.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfmvqnw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwbmihg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2aysqwdqd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwaacskm.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2svwcjqqn.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxqxfmk.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2lehhlrfw.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmplvgu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2gtelkvpf.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtfenpd.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uccewfjh.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2vsffpbyi.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2drdohdpc.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2suwmdrgf.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlotixn.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jiymwwqe.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgbxaeg.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hpeexyij.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2igakdsud.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iudkyths.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdkmciz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mtejfhuu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2yndaayfd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pilkzixc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzdhfli.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyooovg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjanubns.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kihrwqvg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgzhwtg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udcnddkz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbuvkfbt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2abivxekt.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzcboyc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2gihawytp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2phslqdwx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twxilqrz.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2khbqfjgx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwubgpc.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2muhcsnrc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bvyuofgz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvpqune.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2agqxcqci.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2brnoqrvk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2kswhyxwv.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ooexbanx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2llfvavus.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfkneyn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2emljkhtl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2iryjoqed.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2yltvqkph.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yllqyekr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpnahyo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnihftj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2oauipnmd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzhzoyv.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpskszv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tnobhzhu.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrrdfht.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhvthpd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpibgog.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfqzqsv.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2duvgbbel.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdlqzot.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjunujvz.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbvbpqf.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmiogow.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzselim.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyllgbxs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xuucpoox.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2iskttgcd.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2yonqmmhs.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wasbhofx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxxhgrx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2afyibmnr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsbqbvt.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2eddaplyf.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmjqoxt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2mgepvuzs.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgrwvad.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2dndzfrey.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgsrrki.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpcqulw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjubiei.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afadlbbd.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2zghfmhvu.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2xugqffgo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpamzxv.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnlqtqo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfqhtqq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2caxdyyig.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jhieydvf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkzoqso.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2skibkwpk.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2fvblhlxi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqesypsa.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ygozmqqr.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhkidhu.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2tichcuwu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2uomiihtk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfomtfae.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqnkgwk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgruzhw.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2emfbfgoz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmtltys.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2idfqkmpe.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdjtrzj.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2wzosxguh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2phjlqtnc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbjtxjw.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmqvfxo.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnoqsyd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtpvcui.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrmgibr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzknvdw.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsufgmg.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2keymyobi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wnflwpgw.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcxywvm.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrhxfzs.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfyukqdj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2bpyecwwr.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2mitltatc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2odnnynpf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2izzsslkp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2uoaydtsn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2eanhrplh.html


<!-- 参考信息 -->