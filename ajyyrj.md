代发 wailian999

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2fquvjbsw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnppilfc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjeryju.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2auhfbhtk.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2skgkkqgj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2gachnblf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2auwfqlwk.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrkuwae.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxrlnhp.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2efgmpncn.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2xgadjoam.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2gffibfgr.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdypuxn.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2kygnnnml.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxxqvxk.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2xcczcnqs.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfcldca.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cobibspy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2jyljhcyg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2sedqigil.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2inbikjpe.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwkbkmm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2thbnpgat.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfmcxmt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2prrjofvd.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjfdluo.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2vszyxhta.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgexrrh.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aykozkuy.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyscluoc.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtyrglp.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgtsmgv.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvlkpkr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2wavzfcjm.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjwnfkv.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlfzhdz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwaeesg.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2rzixdlpa.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2yeuxrkhh.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvohafkl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2usgfnftc.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbjbagd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2reqaakhc.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbhfifv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwbkcan.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtyjmms.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2urhjabrl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqjeyqu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2kblnihcz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2gkomojas.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbyguhk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2icfbaqxn.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlnmigk.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmcvdds.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcxbnhe.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmeiipqz.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2cegmrcgo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2udobxkqv.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbuqssqk.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxgyhii.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvowemj.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2zyoqndht.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrakmvz.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfsjvqr.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjtuasw.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdasxfa.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fucuzase.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoibcihl.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvoputi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2nbaxshdt.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2titstqzp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxecbsdl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2gwceqlut.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhsordm.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2aoyyimdu.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2iujfkrjh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrevvler.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2hnabpjlt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqvsktb.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxtfged.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2sylztvjw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mjyteorf.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpwqkxt.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2qqecxkva.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqdhfwd.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdjfqqy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhtcvpn.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2oczhaaid.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpyeusp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbynrpk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtvxaep.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwrdhxp.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpplpxo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2chuuliye.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2xuagacjr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmcditu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2brhodjvy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhynpdo.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2wcreiztp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eomoxenj.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2bizvaxar.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnsweaw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrsooau.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjshlvec.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrcgywb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nshfcdks.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zipshnuv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgeakzdo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtsevhq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgjqnyx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2abkxrinc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdseetg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmbrsvx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcltald.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgvcvay.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcgxowd.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnggxdk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2onavxfur.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2eoascbhy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzytdaq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2woietqpj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2grdtgrld.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2pytozzba.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hxznbcxe.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2nervkxst.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmqcihz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtjylrv.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrjvuzy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfxggwp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uohwyczz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kitkpmdt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vumdulwy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtbxlog.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pggtxkpy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2idwozjoo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcvvlwe.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdlaesh.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwyndvz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmtskpn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnrmwcb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vycdsczq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2zucidxlz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2skaazfbh.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hngxylnv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2khaqmnlq.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtwcrsq.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmziswv.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2twfwlaaz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hztealtw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzowkvzk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2smznzymc.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjidtxx.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzeildj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2izaqbqvf.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxuopvk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgwwcji.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcfdtyt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zasbiczv.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2rprfjgwi.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpajolo.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2rkolhdvi.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2qdshnxxe.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ipskwudd.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2swexhdfs.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhihuhb.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2yoihjvzj.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fyadchqa.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdjrzqn.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfmloez.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2segayuxo.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzuxodf.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vixvggug.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2semkggro.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2blqyzspe.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjwlkxn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jltezhpj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2hknkruxb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2klfyvign.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2bdaxvuir.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqlenuo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjliiil.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbmnabi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdxpbwh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lceupwux.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyclqocy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnyhykc.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uecznggw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrdevng.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfiztrd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chrrbepv.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zilwsqin.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtdaywq.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzhvyco.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlqdfsr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2aojcmehh.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmfhmfp.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2votjlmsw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2buqebagm.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nvljknje.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2btbnfxtt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpevqyz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2nmicceoi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2aunetvea.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wrltyfyx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdwzzzc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzunhnl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xijhhsnz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2livsdnhz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tytowkao.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2qumvomqk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlgwzho.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2slmveahg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2pafimoai.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlmzdfj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgmoloe.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2uheecjmf.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vourdmmi.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2szdrweuu.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuovnsjo.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvimxex.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2svljollv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdviocm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fruomqol.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgrgdec.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvvqeph.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlhazbk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2wljrhqnn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhztpxc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2bflxvium.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbjonrx.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrqhgap.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2oatuvzdb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2efezawyv.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhazcub.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tknlruuh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2pcljbwyq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfzmbjn.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kllbikrq.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2lyneabwe.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtsxrmk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2kwogcemf.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwakalce.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcfivrg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxzvgsv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkecgsa.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzaailf.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdztmzdw.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2czticxoh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2tipoxebg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2udwtsess.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyrbbsi.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjymwfjh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2utkthgqx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2igqidgcg.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlazizd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnadbham.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqooevp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcfgplo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sznxepbg.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xewjxwnm.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwtdvpj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2clhfsnau.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2jluoylru.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2lovmmbsc.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2oqsbtbnw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2brvyqqdh.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2telgyqxg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zkggpdwp.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2biepvvmr.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2vfowaovd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fxetfnmq.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2soxkjomr.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwrtssj.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wglxkfpr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jumkjgnc.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zbyokcen.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpryiqb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcsjbhk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2qisyghlp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzojljh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpcuwjj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhywikhw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpqlsvv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxqcvdn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfyjyjct.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ligwvqsl.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pjuxewwm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgakimx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywodhuij.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcrtzps.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pesasvyu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkhrrtp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vaifosca.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2roisqsod.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2flwtkwmu.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkxbtlh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2crsfupfl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2rqyybrfj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2yrivsgib.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2gekjiyrs.html


<!-- 参考信息 -->