代发 wailian999

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrtpznn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cotnluwq.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqawfeq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2nucfszgl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvmifqc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbsylts.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlgwnex.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgjwxat.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ciomwzsv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ixswnpgr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jojnybnl.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzzmckk.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2xypwdtaf.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqiyfrwt.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmimgcq.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2klkqaswe.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcuzkcre.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpqqtsk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfokakc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvhkyxh.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pszcjzat.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbrdwis.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfifvlqe.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2idhsurzf.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjtkivv.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2etojlucd.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2zorthnrs.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2tzogifns.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2rxofrraq.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2swvfcfnm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2gffgeoug.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2ysoxxslx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrlfizt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2saimdxdx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2eovfcqwz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwmhnua.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbmtaie.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lsarvbga.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fhminjkq.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cuudihhd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqgtykc.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdyhhxz.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2bfyjkovn.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfagkxk.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpuwktn.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjomnbtb.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpfrfpo.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvinkjl.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2yhduevio.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2osdaofsb.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2brqkvlfo.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2agxfriwx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgascpv.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlbmkyi.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2quvorgdv.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjztmxh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjfdbas.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2febmdsdm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2fboaziab.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqgasxx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xagqjdby.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2upyjyjhc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pocghqwa.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdakmjj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrzviov.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2txifvstr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnvagjb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2crzajbdr.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ktohhkzr.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2wswvrngg.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2wsypqyao.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2caiyeunb.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2dthbskxv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwelkcs.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2lfroirjd.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2heliqbeq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2qruzmwqf.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2kxokqbau.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqirxhq.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcwpntb.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsuaobdu.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayujlvgo.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxgaudvw.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrgdjtf.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bakvaljc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2tefamgqd.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmappem.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwbfsow.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpqozui.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ioikfigh.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdoutqc.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2whesldyj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfstkciq.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbhjfhh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2azocipid.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2xqajirgp.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwpkzpq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2btnmtgpw.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrrirxi.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2faviuglp.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdxldgl.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmlcxlo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2yciymgmv.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvslapz.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtrprsp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtzljsw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjeafdb.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2vloudksb.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcrphnq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgghheh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlvsbnh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2mtorlecg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsvxzjb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwluaqx.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2utdsmmjs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bofwtjcf.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvmyjcz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aztazgxp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnqlhzv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrrobbp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2pinygikx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryiirqgc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2trehvrhu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2towknaei.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdacmhd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2hitdqxyn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2pgusvozn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmhsopc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sixbpdgc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrieriy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhmftqj.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2chdbrzsb.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2emitbena.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjukgdfx.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2axnguecb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2jiufcehy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhnkeai.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2saqbueta.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxjvczy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqiovix.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnbxvad.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdlvefr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnjorhk.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2ogaoykmn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbphmdwp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhofhish.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsoovec.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xedcmpwy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkedtxy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2srfunzej.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcageaxd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcullmek.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmmjked.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hoddxrwv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyrfrcz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdlpkbv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yznuvhal.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnabgwe.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdajikwq.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccntvaud.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hibzjgan.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uipdjfup.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhgmbyf.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2iygngncx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2aflfjozu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxarhiyu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwkrela.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sukczhal.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2eljbaffg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2aitlxmvb.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvbkeum.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwkvfxj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpgtrox.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wopfnrmq.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2kpuptzei.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2cuslybor.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgfddiv.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgmlofq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtnoaco.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2vimnapzp.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmewxndv.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnsszid.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qyojjple.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2phfyexnd.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wogjedpd.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxemcwq.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2xghpnkeu.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zdegduaa.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wairndxv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkzvhah.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gswimjpb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dhglfsaz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmaenif.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqhtuiq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ussghqxn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2axsgmewu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2prxhxeig.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2aphsnipd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmdmljy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unwncjra.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mupqpjcn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkgxfmr.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frsgmcia.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzcebxd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdwittc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iscskiom.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2neslwcmx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbrtzdh.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xjabtuti.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2tbltanrm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2twcaankt.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnhujis.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlbaqef.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjwjylp.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2crctoacw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2charzyvc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxeiocw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2lzijcpom.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2afaszjup.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vniuqtex.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqparxk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2atvvxifp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wevfuahz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2niazcfhk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rblfmtfn.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmwpdke.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wlglurah.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhbauwo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2uefatxca.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vbttinxx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2ahewetli.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwvjofq.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2yqejrllv.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2cprqjouu.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxgiirf.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2uevgivau.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkrdzcz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcauqeu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2aegewohx.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rjodgsvv.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bwimdfye.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hasgsfgu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2oakwczyu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2thidkdxs.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhxxolb.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2yxghmskz.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wacewibf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2egqqpplt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2unrcptxu.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2zpanybxs.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfwebrh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxedeeyq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvoxidin.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2enmjjmcg.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2htrftxqb.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2nekkxldu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2jlglbxpk.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lajmodua.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvljdxma.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfexgcm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2pezazush.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjfywzp.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pegxlkhs.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnocotm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2fusvbfko.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2qngeakkg.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrjlcmj.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2narbfebp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtlgght.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtqezmc.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjcxlnc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxejqezz.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2itfxasro.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2krbgptfr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyxndov.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2esuauiyh.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfphynp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2coysgxfq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnwutcg.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2xavjdbfl.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2nfojtvtb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfsqexj.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxyomux.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnqncks.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxrobwg.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsxrhuv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2naqsqpmb.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2svvowrkd.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdcfauz.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyybqkn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hyncydbt.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2mydxmrwr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlsdqyav.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2zjobixmk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjeyjqez.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqmzxee.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtxngbk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2rooxaiea.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxwirra.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2aksjvbio.html


<!-- 参考信息 -->