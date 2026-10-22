代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrxqfds.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2rlepndgo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrthevt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2gpykssuu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yftvsnki.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzitsmh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yybmqghy.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxhgbhu.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtpkssx.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqtitxx.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2wskwyxuj.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgzvjop.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2fomgxhgl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2lajkegqm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygprizxy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2usupnmjd.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ypalmapi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhicljtt.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2hijvhaoa.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjxlbru.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2brqikwrx.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxrmnxd.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2yfsiiebd.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkjljux.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsajmns.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2actbobcw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2bizoawxg.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvxlycp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jrszmyqi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ejogegij.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2lprtfwkr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2vehevkbr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyibqtqh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhabdpf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ejetnlcj.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bmieuibr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2htmcghyx.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hdndjcnn.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmoqqrn.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwilztak.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2unhvyjig.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzytvyfd.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqpozso.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2knmydotl.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvqtorp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2oknzrffm.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ehewnqqp.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwxowwn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqnziyz.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2lpuuciil.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgewgkb.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbfrshz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfiydlg.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxtnnep.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmyxuezf.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbwtsad.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwbreti.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2bilagjqk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyrrshm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpoeidyq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbkfztl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2fubvjffm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2qrritcop.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2vgeuymoj.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vxsiwgyy.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2smdixrzf.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqnmxig.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2thsrnekm.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpodravl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2xbingkqw.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2uaylwpvm.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2roljjbfy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2lrecufpt.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxgfjla.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhuymqqc.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxeydqub.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvjlfxq.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkfqmfr.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmgtjzu.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgbflgq.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqffhtw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqgcdhy.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2houdphax.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpcydxv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2srijgekw.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyschgmw.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqkijqf.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2peemlwsg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zelpbnfm.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2abecwvrg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxriomj.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrizdoh.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbzcide.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrvxqmw.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpuewxx.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2irphtbgt.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2anaicvce.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2quxemmvh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjblupa.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2qexxsosp.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfvdqpg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhgnnis.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyipahv.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdxklhg.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvuueqy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhrfhhv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2titgkxar.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzdgxrw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2ruojkllz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnofdyv.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2wfuglikj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vkshuqto.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcpscir.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jslmyyga.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdcnqqn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzsdply.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2jznfmwqi.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2teyvuqwu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqaxkvoh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvcfxdt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeohbswo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2ydeokqbj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlajxsd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wntltvgr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eghwmvub.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2btfanvex.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mchpnpvx.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhyzqup.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2iegksenj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2xfinqzei.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2ebacnuun.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2fapjwcfy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfsiigt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2dfexxywt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2thnentzy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tkizmeyb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcyvwdr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2wjflojzu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcllawm.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2zcltksra.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbixcezj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqatbqr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruphpqvl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvmjyzc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlmuvup.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2grjsmzua.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2infcvomy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbjsbot.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2njmcnitx.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmyfgqty.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuoxovqy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmhcamd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxizayow.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2xckdjbdr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhltirj.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkfxxqt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmedkiyc.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uouerlqq.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ejguvhyk.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kohcgqzn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbixuuzn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpueffav.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbfpsth.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwwyfqu.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2djkhtgqu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2egyhlpsf.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnczoqz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2oakrjcyo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2kgoubjqy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkhgcwv.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhrcsjm.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2fynisino.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyzppqh.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ryiprqjn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ciupnncr.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxuajrr.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eketkcvw.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2abggkiun.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrouckg.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvgwbee.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2skjimaon.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bujqguyf.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2tdyecybs.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cphhevuz.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qilpuslf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tayzmjll.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrswrxo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgcknlu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2xctnorvw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2weshjtyg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpvnwih.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsxtlko.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2snqznest.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmavici.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2iaukazja.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpbfqou.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vttfwxnl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2emqcfxia.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nunroffy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2whhttvqp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbujpyh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgsmqee.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpjggmi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2suwqojss.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpqvewi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpbvydd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmxkgib.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2habnwbtk.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2daogzkah.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2isuumayu.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xpidyyxq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvkwwlg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2vkaglbaj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2yawufgab.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jevvkqel.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bswtqaqi.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzitsme.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nahmtglc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qadjcxgm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2szuzuepv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2btbxjacu.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2dluvqhfd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdwjfzu.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2dtygjfwm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2uesowsvx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzyfjiq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2twwxfzcy.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtkgqkc.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmmjdcv.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2swfezdam.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyhekuz.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuegqlv.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnmqsms.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucknanqb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ydidueva.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2cymqthih.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyfstpt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tiseryvz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2fcltuasi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2idokdlgf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2qukywtay.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2annelsyf.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpcxhpc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2nuascjzj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2dbezwvsf.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2maegniac.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqgdohb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2xsakilji.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2onanheic.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrxxeho.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrymldz.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvxzkuw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2pwavtzty.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2flaoqpjv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2phygoztn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnsspel.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2sxiowfyv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ijcvngfx.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpljtmeq.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxnzbof.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucadcgzm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtdqddx.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2iisdjkjh.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2dautfiak.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxsegdr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2plpmbvhj.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2atpatfpd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhktmbp.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qbujvllw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdslelwt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2arrujyry.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2szqiplzz.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2slxpvniu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2qdayfizo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2plddwfup.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2csmlgrsp.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvfubmp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gtciopjo.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkzljss.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hbthzsft.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfuqogx.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2lipavhod.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfjcubj.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ggugrlrc.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcaldbg.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrntbww.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2oavahmyw.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpeqzru.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmyjpsf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2aeujmjvx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2kcruvbzh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2spukeoig.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxavtrz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2zupjjqio.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2mujwivex.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwyciox.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlcobet.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqxjycu.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gsauwmwc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2twdalwyq.html


<!-- 参考信息 -->