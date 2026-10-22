代发 wailian999

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2buztxcwm.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfuczyn.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2stmfmebh.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2gowlgseq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogffhcqn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2euickomp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvuruam.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2kerdczrf.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hraphtvf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvigygo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2rubbjxzb.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2rowmcvps.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbyfciw.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2gspsejid.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2kawcxuel.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwksurh.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtgcqms.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2otypawau.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmleqsy.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzfvpvh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wacbursv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdfcdjl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2yssoymjl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtrzxqt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2skpanvrz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnlgiff.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ccylijhe.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrgtvta.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2inbzpqrm.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2umrxxjnt.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2eauagtgu.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwysxeb.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uluzpmwr.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhilsfxb.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2uepdlndp.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjluveb.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2xgryiorz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqcmspe.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wttlzbgf.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgsfbsjb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfycjwr.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkuccqa.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfddlvt.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2slqnbusj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2euytokiq.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2hepfxzfa.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjidqgx.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ghidybel.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uakxrlru.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqghpfj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mldtpzgo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvoksdh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2jbaefuku.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2winzrgvy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdpflhm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbtxwqz.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkisrys.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvxehyk.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2ssflrqoi.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zckyrxts.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ueakeijx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2eifvpyvh.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2pziggtvw.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgdzlse.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2igkghsyf.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwfhucx.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfxonej.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uddgbjlo.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mepkcmdc.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkfltld.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2obnotfsh.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rljpfigw.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2puaemvlj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnfvwrn.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkgbvnk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvzotuz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2enpoilga.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2loahogab.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvexuqf.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwyvmlvd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2yugestax.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsewpiv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2kiyzxwbt.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsiwfoh.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwgbmsn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2illvyykn.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2jasenuwc.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhxubky.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlihbrqi.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbloplt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2panvsvgp.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnnrmeh.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdzocbq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrxthyh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2fhywmkgm.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ljupfuvy.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2vibqrpeh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnypqqi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqibmvm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2nqejshdp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdakvyb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnzbwdz.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2etuzpfiq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcchmos.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2iyprsrky.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnadmlu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpyviftk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqpahng.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2sirvteus.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcoezxr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uirkdrhp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvgkmtj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sghfdgte.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcgvdlf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ieizikpm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcmtzty.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwnhjfj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2becfjzzl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydaztfxe.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2onugcasd.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpvexcu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2uftpgkva.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmroosjs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2zfsorofw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2qoznuacx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2bddvvcep.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2utvdwxer.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjrdjns.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mszatgil.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2phaazfpx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2eodspart.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2uhiqoaeo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbhpvmc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhmwylu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzwhnar.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2suvwjufm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrcrefy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2slincagw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyykxalu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2teoqjfpb.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2vcycwsvd.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjrlggj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efvnseqc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrgnwbj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amdzgohq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxocnrb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnucfvdi.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvcpajm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oonifrfv.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kpoljcmq.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2vanfwrcv.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2aubadtvl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyjcvpw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbndesg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2huvntssd.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfgtamg.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrbqvmw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2yxabfzha.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfkbtms.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2bymjeyzv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2xawrrwsi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtouvxq.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2ewirvmnp.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2mazgkggq.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2kxykewov.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2mahrzjaq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxpvidr.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqtcxav.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kthirjgj.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2aipybcmb.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpzdsjr.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jyahsycc.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzvijha.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gbquiehn.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2gvavkruu.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yfywginh.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpnijlc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzfhidw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2szzzetoc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qapwucob.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxjtqxx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cabhlwdi.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvoqdzx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdtqurm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwupjvs.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjmzmkn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2smejnlgh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnaojeur.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqohmik.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxroqhfb.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzaaoso.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2lournrcz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxuscub.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mihjbwju.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tousjgvf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfgmbzt.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jhynpvkh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbuyzcl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2uojlrhsu.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcardec.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwgbbxg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2opcqqqty.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkvupgg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2altkzeng.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2lizyoalu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2pifrulya.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjtkfsp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxwsjrx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xczvxkyv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcxpztj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhmuqui.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxocjww.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2acxgjdfp.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkbudzj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvkoyqb.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwirefg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmdcpbd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qdaplaxu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2spbjtvts.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2uguctkzs.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2glsbihxn.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2owxopwcb.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpffaqah.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqujwct.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ygangcvk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnmyuii.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mwltvsjc.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2huivxcfj.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xikohdgn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2frsowdjo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2awqasvnb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2prmhdjgo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ghagqgag.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2gepviczi.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzyxqzh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2qdduhuwv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2utrjsnjo.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwgsnko.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpeltie.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrpzmry.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eixepjmw.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpokhthe.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2gsembawc.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2spxinzgi.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2qjalievu.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnujehox.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvufhvwz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfmzykf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqfctrl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2awlizqjw.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtmyruc.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbrqezs.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2stbgbynv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrrtxhd.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhjzcyg.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2coarhjdq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxvtadc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2yitoxhvk.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwnmgib.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dupyhahs.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jhuzpjuo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2wefhynsx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqoxpdm.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xavaqtqo.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwuqacf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2uiemektw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2afondlwc.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzrthck.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2duakotuu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtlideh.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hcljmgno.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vffrydhk.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2waniwtyb.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2lcreqwfa.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2achzsuwp.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2uogdqbwb.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnusewx.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxvztxi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2idnxxilh.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvzluvf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vztsuhqv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2airenelh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfndxkz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgxdrdd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2znaopxdq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2faotxidg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjofwyz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhgefng.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dckrqwcs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhsfsah.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vurtqoxr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbedixz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfaijfx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zybtddaa.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygusdrfi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjpyqgl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvanqjl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhrfoll.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2tkszylpk.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uxygwzia.html


<!-- 参考信息 -->