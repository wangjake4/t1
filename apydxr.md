代发 wailian999

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2prhkrukz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnngwyc.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2whvozvss.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhtdtyo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkewtylz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2urwtfbfm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2kicooldm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2wjluwtbr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2echpgoym.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2jreasyqo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gttftamd.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkuqpqw.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2atljwaiu.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfvkhdp.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjoudpqk.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtolsix.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqudwogr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2trcxuusz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxngqju.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxcwjqf.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bfybviax.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzvnkjh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2clvlrlcl.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2zxahdfvo.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2yyiirdhw.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2aosicxak.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2jfogbqda.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmvryxx.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2uyafuzcx.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2kgetbauu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpqupln.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhqnaxx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2goovsuiu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2usylerhd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2noaorept.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrnvasj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjuiachl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcnbhox.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qolzayqt.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hibaztdo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsbiilj.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2njxoqxwa.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpwcesv.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnrvqnh.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eublsyed.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwbryyr.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpiuknw.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2meyqgkhb.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnrdkts.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzzivyg.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkplfeu.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjcwjye.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2enmeudha.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2awygekrq.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkzapsm.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2huodpyxq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjkxmpi.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgskfka.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2gaidyevr.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwiugwc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvreunzj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ubiotqgu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2blsfslbq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwwbmia.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2kcunpiqw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2jajysjvj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqwsyir.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvkctdz.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmpjcfj.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2aqihoitn.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmtrsjh.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2saderfhc.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ktuuoieh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2oknemsft.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkoddub.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgohdzo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdejgmj.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2dsznlbjq.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfuemqha.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvyzgge.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2umaradpt.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aeobdrry.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxedkqvo.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2otqyxtrx.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwovkug.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2edgxmryc.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhzzzcf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmmradc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2emloujfq.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2okluydej.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2keidroqv.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2smzdvpti.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2nljaicib.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzgcisu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpopwaz.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2avrwlxlj.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjuyttw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gouhvhug.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2tirjzlvg.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmicanx.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2uubqgcdm.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2krethaam.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2trirkwfh.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyopmgzy.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2sjutdeif.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2hydtwfap.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2aaijiywt.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkcsfhi.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2vtieezoj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkkgamg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2jlymftay.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2nkiernai.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2jndipkpw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hpuyxfyq.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtxzmep.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mrexmsol.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbtepcj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2movqacer.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpfrlhx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2btwijpnt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwyqkhgy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmyqrbe.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzugfpa.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrjkejf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdqfemk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2arqunlxk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtthsmjc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcamkrcp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhkmeib.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdlrdja.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqxmzwp.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtiirnq.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhisjax.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnzcfnh.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnywtwf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlartho.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvfvmso.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2bifmfmze.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkpjixh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2naogyypw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xwuptcus.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2xaukqbym.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2najjxmuh.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2wpaznbdx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbrtzio.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtadpnf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwudurmf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kktsgjni.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2shfyqqyo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjyuyfqo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgsxcxd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnlzajr.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbxtnfg.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwazfmk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnjxlbv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oljvprqi.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phsyjlzd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rltjdjau.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2joppmsuq.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zafkmafz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uesuokbh.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzmqmpp.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2taaaalys.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2berroyrn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpsiyor.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbszkjxr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2zezqrvtr.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcjtjew.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2qczklodf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2oepttkug.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2vioaiswg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2dvufucbb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzhbdtq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhobalx.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2vjiudydm.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2quhdjqem.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2kaediqlf.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnpuhmc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2htxwkfmp.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2miuxkdzy.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kixkgctm.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2idvchhbs.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uahacgau.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvmgmdt.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qqogxoqz.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ispeyamh.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2uramkrya.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yqznewad.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxbuklx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpzbeig.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxduobt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrlycyi.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2diwfiffq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzikryx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmbtasy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ovexomvx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhfzqtj.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbbaoyj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwseeko.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuuodkky.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2omwbusti.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zinnlztb.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrgcguu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsmdyvk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwdngbv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtiwappu.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcjlmmt.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyqtyoq.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhrhtdm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpveluy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnnoern.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxugjby.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tialbydh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2sxokdrgv.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2erxcxbvl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rljtnzii.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgbtjab.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2opykgnvm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xmufdqmz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2hqalguww.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhaxxyq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvpbagu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtitsqc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwocavm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfzdpxr.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2inzcopey.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uwpysaqh.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2odpzvvga.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2nqoafdmh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xhucnwry.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwxhjnr.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2zfsdloer.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrrlbfu.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnnujkj.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcdzuhw.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2oprwrign.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nslnsiqd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfiebpt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ovadfgns.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2amlfmimm.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ninstdjf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nepbggkj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2stmookkm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhlcsxs.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2vglqgiwp.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2emlkbhiw.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mfopjkgt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2rgblmlnj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2unrilwmq.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hjybxman.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skiuevge.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvpepfl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsefsieq.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzsuqch.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bacousmh.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqxdgtw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnqosva.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjnzrhd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmqhumb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqacnlt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2uztjcxgu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2dhzpkgei.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxtderg.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvovjpl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhrqpya.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2tobstbku.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmccdmx.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2izcpuwsf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjjbjqd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2cmeesjxr.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxgejrw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzfbdwf.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2abemswfb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjgakfw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfhlclz.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2lysyjxpq.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbftyyw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2sghcazrj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjctkax.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2dksrujvq.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2qsklrugk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lilmoenx.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfdhybc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdaxsyd.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2uebunhig.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnxqlig.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vowaeeza.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jeanuhmt.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvakzuna.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rckevsrj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2uaregdgt.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2obifeczk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2iilgalso.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2bsaexacr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqywpbo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2erpdmoyq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2pxezwdkj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2qboxdaqr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhhpfbm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tspqlqbx.html


<!-- 参考信息 -->