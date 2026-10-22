代发 wailian999

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvbjmuu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2baaoxgdg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lznjjpgd.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mhesgsou.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvashym.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpgfwlu.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2jthbemlf.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrcjqvd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2wozdrnqb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhvrgfv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwbolqt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2zylbdjju.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ktoaitsc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2bndiltly.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvzbuon.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmdnxmx.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwszfpe.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2wyopvawv.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ayeseofq.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbgyslj.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2yawxthet.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmccjmu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2qodetbot.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2knbpvnec.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2znzhiqrh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwpmiyn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2xawzocuf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbbxhpe.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlrprkx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhqulxi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gstopbby.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2byxrpwsm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2itdbzscx.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2euhqxgoy.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvgzxol.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2enaboxgj.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2avmpslps.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrymroh.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2iduhvwle.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzwohgz.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmasvtc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2btidjnrj.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqrcabh.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxnfepn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2yedqzmtz.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhhxknk.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcqwkre.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpaoxii.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtxseba.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2ntikfonq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vefmwjlv.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcboned.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsweavq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2sheltdxh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkcalda.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcjnzfv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfwcssu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2eerlhmxh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2zxsybmgv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2dphuuzal.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmnsrww.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2cznovdar.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnwzgwk.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2bycdvafs.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xunyigkp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2pddnnfyz.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gajzichj.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2pndxiica.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbewjyl.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2vekpltxz.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzimbpf.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xormzadk.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmrsnyt.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayagieqe.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbmtyfq.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmvnndt.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gonrvpmx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqcuzbg.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhbsaxd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2enzgvojl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2uuaooqcu.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxlnsad.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqeckzq.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqqpioo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlygrar.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2prvxuonm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkerrtuz.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2vhifsari.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdlnrjk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdxgygi.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2bcowlaxs.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2foacbvdl.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2aexakeev.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2parqxdpc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxvjvlc.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgedawr.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2msyvzmgf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2iknsvvmp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2tivvuuvn.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2xajgncsj.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlfwleq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2ramonnsn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxqrvyu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfjqpek.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2wautyknd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yapkymck.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2djjfmwfh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsismyb.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsfdrtm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtcbehg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2exznlbil.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkuyzxu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdcuxozs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrxzfjd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2avxqgpxr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbpnowu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyaakrs.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2pknkbyqu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2swkrvape.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqbvvum.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzynnntz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2snrssjhc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2drypjljk.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrujkqdh.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2nftjhcvv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbqpyot.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2sztnqwwl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2mctmwpad.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2dedhozxh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmxbkro.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2hnerjejt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2uewhlpkd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2gwirncqq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2vadsfjah.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2iurnckak.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2xeyytqjy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzuppyze.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgtoyki.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwktasrh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2excuxtsr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kezyugaf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbwwofs.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2salyqewt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtedxjh.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2icmiqxvr.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eudsbjut.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okkfuxrf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqszhzv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfppdhs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2bvljntww.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwznawd.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdquylf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2subwlmvc.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxgryse.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkiztzk.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkunria.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvhxevr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mldvbacz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2oburejaf.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bricixxx.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbpkxxb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2qujjzncp.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2isnydwea.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2rixduidi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqyruyf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgulpgqb.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjiaqrq.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2sgyywoma.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ceygoqsf.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2coddzsbj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ghujfzkh.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhgwqib.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkziyvfm.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvzjzgn.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbwgvxz.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2trcqdkjx.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhodmfk.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwmhwvb.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2mytxuehw.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzlsahk.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjiihhx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqhpauk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2epsozxql.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkglkkg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2nvndyvsa.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wmudyelw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2unewamsw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvsobcl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqbzntx.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwwryqx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlcqkvy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apzgsekz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrtnjea.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrefyrc.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdnxjzo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvilvknh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxqrbdd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cldbyaya.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqpmwfc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmximrq.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vioygokr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2psmpuuno.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxjwbsr.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhfsvrw.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2miwbkojh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2fclqdiss.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mufsaeqb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgsvwie.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgzhqii.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqevwuo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2boiggkcc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2evjiuqnr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2awwuyoix.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2drclfyqj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfhrxhr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ximuxwnt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jirwclnh.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2dyztwxiw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qutgquso.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbpwpim.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpuzdnjm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2csynohgh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkeciie.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2wiucpghr.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2sqigprar.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtooxnme.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbvzsuz.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxhagmy.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbqcnsa.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnkbjna.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ityimnlr.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmitsdp.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2oapejgvh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2taemtkwm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyhquva.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ylajgcgd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmtwwbj.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvmocms.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnmxwbe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2gehmwbnf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvfmeze.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcgrnhf.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2upytdfvh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2caumlliq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsspkbt.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwikpyn.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2szdowddb.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdzxpxd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbgeflx.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wukfjvsm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnafduzv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2mbppgvbd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2zabmhmuf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2bkreuelc.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnqudzb.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjxhqxg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2biuwpzsy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2abzivrkb.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2pypbmzyy.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2dksqnsjj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2fejjpxin.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2gegttilc.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2qibyghzb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aorhqjvg.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2japmdkkv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwhdgfz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2krswzfyh.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzxhvru.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2magtiauz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2pvopplak.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2scfkakxp.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2dycxysyx.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2haiizysg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfayxug.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfkkoiq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cistlgin.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2igrevpbu.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjsabpr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfuywzg.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2awadldim.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvrkvdi.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwbgbdi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ewifhkab.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fdixmoqd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjiulgm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2djyjrthd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2bydekbkq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbbgofr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcadfdo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvevtxjy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2sahieabb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yoyghkjt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xumjsbin.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2tioessag.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wfalyylz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvphrmn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppghvskl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2szdvjhuc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2suvdyaht.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2caxxkzxx.html


<!-- 参考信息 -->