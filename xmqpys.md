代发 wailian999

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wduwtnkq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2bgquhwrc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2enlnsnvx.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2djdbpfrn.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxgrpof.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuioqodr.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2zizneclf.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjaxnbk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2toefylfk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2dozgjcxu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpllhrte.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgszuxiz.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pwascwmi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkjncxp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2reqggbjd.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqelitn.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2yvoybgpx.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvowghg.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2svomatso.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2ufauurlb.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2eghuudwv.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2qaawnvyk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2pohqavco.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2wneydsbh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2aobpquis.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2enpanltc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2glogzjhe.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2gpktcepu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrccpww.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqnbjug.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrmtmyz.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgqbsea.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2danidujj.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iklhivfd.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2arwewcqq.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2quhnylzl.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2owuddlex.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2psdehryw.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2moqvicyv.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvdnska.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpewgbf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2utximfis.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfhuvsw.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2abtpjvvk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzoxpkd.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2eghrlimg.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ssriimgq.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbixvao.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhhymzp.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2wohwjexb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfmhqte.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvugvun.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2iotewefw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2moiuidpw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dveuqkzs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdudttq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxkuogn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkxzsfr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2ouitkjqy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2urmuxwjy.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wkiacscw.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2brdqxwni.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2azouxkrt.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpuygen.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2tabrhbod.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2hseffxlf.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsiqbkb.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2uinjigez.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2czirmqek.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbgxwig.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wslzhtxr.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sysrnurw.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2giselqmz.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyopigq.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsodkngi.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnchrwak.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2niktpnvg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2bqynlbzo.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqnhkmn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfxdala.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcqqxcs.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2pegbmzjn.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgxvxkn.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2uflyepwg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhxmydf.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhwxoph.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxxapcw.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrmozwm.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpnecxs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wehhtpqn.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2alytflcm.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2yybspynq.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcizbbpk.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzevwlbe.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbxoiwu.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2buxsoihz.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyjsiey.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqmxkmv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2eprsfmpn.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ufccnwmw.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2elbhzoft.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2sewjxyty.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2eodoohzk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrnycqk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlrcavf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2akjukmgh.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2ofeorbmb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zilphggj.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqrrfgj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsyosnu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnvljss.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2opxrnqct.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2auotopwm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbgclzm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzovpvth.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2iakqvevx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2njhfcmmb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2uogeogsu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmesjff.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxbbfkd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfbtvxu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcywxfu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2llkbtwxl.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2agvuaiqx.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ldipwmxh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjwtrjd.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2riqwelxh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2glmpyhxw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcsliqq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsrvlss.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpfztgy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbczeax.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2aopnrkxu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2gxocqzfy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2eklizouq.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvksuue.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2arimxsrm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfhkmud.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpartez.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hubjdwax.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2divnneyl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvobvzxo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tquuyacq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdkzgem.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhoscvb.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tojdndrr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dujspane.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nplvfalh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iutbmcrg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpwhasc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlwelut.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2thmemszh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2scdcngvl.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iobwsdds.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwfzsct.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdaotpa.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vniqpzli.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjduxqfe.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmgggyn.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cglumzvc.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ioeecesh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2iryaypet.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgjutyp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2rikydnqk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbdxsmn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wasnqzww.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqipdug.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxyqudy.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtvtdqd.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpixhqr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2tflkhenq.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2tnikttwy.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytyrvvgz.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdrzgse.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2alemfdny.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2aljdmrcc.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ormdwszl.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rytppuun.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvoxeqo.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vqphzejb.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrnngjo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2njbdidjq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsxyyll.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kowkjihi.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyzrkuk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjkpnuf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2eravvupq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uyadnwav.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2iabyrarq.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdxbbsn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmyrxqc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntszkhxw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2aenbtlci.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zymittqq.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ablouzos.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2akjkhkdt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2anirmanu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpakwgyq.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsarzoa.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2akdhjgju.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sxymdydh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vipgocup.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzgqepk.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2geqqanlr.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqeyloq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjqertf.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqchacm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ikymtfmf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhzeppv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2twiomgmt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jaehybwo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzalhky.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nlngfkrm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qokkcwzr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdtfnhl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gunhtfae.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2leqtehfk.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2btayklla.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pkurlwuc.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2arrrayca.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2llppenuq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdydehw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2ixftivep.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfsgpiv.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2lawnlcvb.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcckwgi.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2nftevuxb.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2wjssltgp.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nirtheqx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2smxqwqsw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ftoythxj.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwcaika.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2efhppyji.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2grslwdul.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2joyiizeh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2mattjwpo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2flrvzvlg.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcwumzn.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zczgrhss.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgniufx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwloxjn.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2sifhjaoz.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oirehwur.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmdubcw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxzxowu.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwlvpdv.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2nyaqrisg.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2srixcwoa.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnkzicv.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iimqsfoa.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxthgfle.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2rajeqiow.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2qgspndvi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2gkslmokc.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdjghyl.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2aecsikkf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzisuhn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqqrszg.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2brirsivu.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2gupfangz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpuikdxh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqoekpjq.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2vleyfsyy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2izgxjbna.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2exfrknpr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpakfxdc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tqojsfiz.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtrlywa.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2qolvaola.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2pjionpus.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpgfxyl.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2vaardofy.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2jemqnadf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gejkjead.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpirsvv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdpapjs.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxgaoqc.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjxyeey.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpwvujj.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dycnwrqr.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2trokpnes.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lovcgzuq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkkrowu.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqdrjnc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2asxdczmy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2eyudjqvp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2buillosh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpccqqfi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2wbohdmiy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2olyjqkrb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvoedphe.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpytlme.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdiqkig.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqzvopz.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhbloja.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxirjbf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2pibloaom.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sffwtixw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kklatrhj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gifoibfo.html


<!-- 参考信息 -->