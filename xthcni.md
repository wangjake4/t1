代发 wailian999

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnkylrm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2mzetswxl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nihxljzj.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwyuvva.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2egmokjwt.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2soyyzsck.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwffqnuc.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2eqroxxgc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2kggebjim.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2tiuftklb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2dayiipso.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjbxwst.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgcyyna.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2minqwdyz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2clexemye.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2eljemgin.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2oktvqslk.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2trouxpnm.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2utdpnmcs.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2jfizzbam.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2acspcxje.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2xxynnvwl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2azmdaftd.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmtkhzy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zvexlyrg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2secglyui.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfdyftg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxpsjrh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvwbnqd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2afpgdnnt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcpmjqp.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkkyxwt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxujypv.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvotbql.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2pclcsene.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhnawyc.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2maoortfi.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2remggnyc.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2tedxtnos.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqgqolk.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwerdwz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkenzfx.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cjavylms.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzoqqvao.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2wllqcdyz.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyfvmsj.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2tulxshwr.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkzdlmt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2cradflvm.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2bczolgth.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2rabjaqml.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2cplugxoy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfvbtvo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxqpxaz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2khdoobqj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2btuibdpl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2sftgpcbb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2arwmpwpu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbtivrk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2poldwvbi.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgsdqoc.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2oycwhblk.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzmmzae.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlpxeur.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2onwggecp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjbwqcj.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2erhoncdd.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyubwno.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsccatr.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2qizxjiol.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrduuhz.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrwxkvc.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2awqbvrsq.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjjuyfe.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rweodcjp.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkvaxad.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2blutcujg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2lzndnksa.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zlswcnyr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2adeaujyp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2pedxbjsq.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdgtufr.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2brlcbrke.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2otoetjeo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2semdtkoj.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrrprvy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qagwlrkm.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2paywsgnp.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzoqdlw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2htxkchez.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2svumzhme.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2gvyvnngy.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxawssm.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2zblfaemp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2xndpbplu.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbxmkit.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2yxekpmsz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbsqppu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfbwhmu.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2sblhvtgb.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2lynnzhnb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqygxhud.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkhydbh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjvghek.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2gizhgpph.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvjkuzm.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbavxmu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrwrysv.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcjvmqe.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rescvwqj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2vevusimw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdlfhpn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlouklga.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdjdoij.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkuzckny.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2kevjdzpm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2obxmmczl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2wogrriux.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgsihhl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdoybqbk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtherjec.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2osbtuamw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdftcvb.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhumatb.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dexlkfqa.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2crcjwnvk.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2yugdvcjt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2krgakwyq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2udwkjxnw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxkjzzy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdgocin.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfgallb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jraslkck.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2igrlqruu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2levukyoe.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2pvasxcta.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzrrzas.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmmnwie.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qicovovu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzndzja.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2umfqnpsj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyxrrde.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyquqsu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kngunvpb.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2jepcqwgq.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2utqqfnca.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eamrxdia.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgfacot.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuokpuzt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2typhxxzm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwfepqq.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqevubw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2skxdbhcb.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kittswcn.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2bomybfdx.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuztljrz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqxxipm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfekkuwo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2wypqulze.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tskaokoz.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2forihedm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2henfxoaf.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgofppy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfitjdr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2beyhmjvc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekffkvwz.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2brplfkze.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrrghwn.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjpoibd.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2hooyjjvr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnyrxes.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2anqksyai.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxehuvrg.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2fumlmppk.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfvmwrf.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrkkfgf.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fnehnvsy.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtolqav.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzmsqzy.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vknfiitd.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwixzxo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2geppnovp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2shonjimg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2duesjwfm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2heiisozc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqvtlku.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhltvjh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dggsinmz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2cryfyyjj.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhijawm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbljkbx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2suwatuuv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdrxsmj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2alnnyvpj.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsslewi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtnewhr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2qotzfedn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtggloe.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2axbwazyy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2eshumgkj.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzvzjyo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2plxczyvd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwjwpvz.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpzfstr.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rrukkulu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ipldbpqg.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgkkomj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2oakbvxtj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2emzkhysn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2rlytvvor.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jxekclwj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xavhpjgh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kcywhrgo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcltyrcf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkdhkkm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2raduvfzj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zmudwwzk.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2znhumgoh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2axttndkl.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2sroxdrji.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbhcper.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdhtuxu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2unmiqchp.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlhxsqq.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mulvwlab.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2weadgvfk.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2zinnpxft.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkqskpw.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2iimepgqc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfkipbnw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zlovyzgn.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2thoaycux.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gewtnxwi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvvdfks.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfvcxfi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqqneya.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzfgrgn.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2blxnplhh.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bylksicz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2yaspqldp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2aalhrxgy.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwgsxlr.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwvimic.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjsgopt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssuzrddp.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2exzrrmua.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqgkefk.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwiyqtii.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2pizbdyhh.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwzrpzj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbrplkc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2daymxnoj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ltoziltv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2huzounip.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbojqku.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2pfryzwsd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxejfom.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkcccrz.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgyldte.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ueolqhkf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmuyjiwy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxdziup.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2yklkowcp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvsxbjp.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2phhzjpwv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfbkzrv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnikaon.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2uiijbohf.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2unxlpofw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2qryumsja.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2njhxguje.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpxsgds.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2bovytbiv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2awqmtotr.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bwiiwokg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrgokzg.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgnbxvl.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2lsghkvaf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2byhknoxp.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsxqeie.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xohyjjdw.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wtuvknuh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lswoydix.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2uftwceng.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2htenkuul.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvvlrxd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyxdabo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvbghur.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2quzvvnmj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2oisbhhpz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkwvlug.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpltpsd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpapjsq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqkvody.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yyelvawp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2hourkwim.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmvwwxk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ciaunkoy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxasgfz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzwuhwt.html


<!-- 参考信息 -->