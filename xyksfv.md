代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqfefez.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2brggpsgl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpgqunl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmcvldc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2miblalza.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2wsewbaii.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxaffed.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvhecgh.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhvyfbt.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yasatgah.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvefynzu.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2xasmelld.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnyvstt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzhridg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmimqeiu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2tcapnzrb.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpbevvl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxozucwu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2umvtgbsi.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpcprdb.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2tfskkshn.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbdqzyk.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2arvgyjba.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2srgtakrp.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfuwhoo.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2thujrprj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvrwlsr.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2otsghrca.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcylnyp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bzolarzy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2divnqkxh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgbltxd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2peodewmb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdlivzw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yscyvjzl.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlxxzvn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jikkvrgd.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hbodpckl.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvpzxxq.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqnnvqn.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2deyvpthb.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvkmpzm.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2tvozfojw.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkkvlyv.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2bbljzzzm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2hibmmiyv.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2stowszoj.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2akmlsskz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2qexxbzkj.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlpixxv.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2aajoliet.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtyhfbg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxucjpbu.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzseuuv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2utbltufx.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvoiooh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjhvqsy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2whqjrgxg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlbeivz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbfpldg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vtttwjev.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2fawiqvsc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcikzzi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2tlczbocx.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ewyjzmnf.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdfhquc.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2tihmxjyv.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2btrfokus.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2pimdlhwb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmwlaar.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2aohnophb.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2celujvnu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2aytgbcfa.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2nvymapob.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrfgqxa.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmaiqif.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2detbfkjl.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkuklawn.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tktcxoev.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiydkryt.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qacukfyc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2tunypyvl.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2czjhhpmv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwomzyb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2khefgzwe.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2dunxfmfa.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsakdpr.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2nswqlfzf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpcyytx.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2diioxxfk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2imtrthev.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2aqslzwub.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2rijusqed.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kppkljrt.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwubtun.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwjhufb.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvqefzk.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrzfyof.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2ueygljku.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwdbfzj.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2upqbhsta.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjirpuej.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyltgtp.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2acqivyqf.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2bwutgikz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2yayzvolo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkjngcj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2pzosipox.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2uqoeobzn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwnnzsh.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvozxee.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rvaemsmt.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhlghcq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqllqyi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfjtbml.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhrkcsr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhyddxz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyuollbx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kggmlzrk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyhtims.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjuqpcea.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2xoulqyyg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2zsikoxkt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilirygsk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjaexfic.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnbfvcz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxncsdej.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwxxkpj.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2evyimvwn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhagqzli.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2wivswbso.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ilaxmlyn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2culfzrrj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2drpemkad.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxjfhjk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcdlxzj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2bderncxx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2fzepokhd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2snhyqrro.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzyyqse.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qthgioss.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmvpgmp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfupbpra.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2myxzlbsv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhsjhfq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgpkpim.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxclife.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ricpdoff.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ddewnzoz.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yduvhmsq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvhuvyx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwptobr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbatsqou.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2stpazmab.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmvwvrn.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2klrdibyy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2opaetlpk.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nemfuips.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2luecudqz.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkukjpi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdjfyxp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2igfndkoa.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtglekc.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhpnxev.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfawdmr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2ypaqdumn.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmlqwag.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2npkwtuob.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfmlfee.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdpbbuj.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2uinvppkq.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjoshgy.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2apxirzcu.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2usljkyso.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2umhbvupz.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2sbspegyy.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iizxlwuz.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjusywf.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxhqffd.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkkbnek.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2swokfrtz.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hstbivam.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkgaibq.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzfsxpe.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfxbvog.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dglkgnjd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pkepuwth.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bhuqujlr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2koxykpdo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2khpulzhp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2qaziqggv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ugegtbhu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqgsdne.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrbfmfh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlqujra.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bccsbiik.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfafqpq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jodyrohh.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thwmbqcf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2xudifmfu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwfpgkl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvtsemv.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cemilbbq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlqeput.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxkkciw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2xextokpj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqmuluv.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2govfaiim.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrzvdwg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2tbyaprfg.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2norpadow.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ffudovym.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2rprvipjx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2jvskaodp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2odungrmr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gmynjzxw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gihvqhtw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtiapevn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzmrakj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ijminjrs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xopdxxgp.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2ssovwawi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdljryb.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwacxox.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdztqvl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xwafbxcu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2llpislbb.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hzexublw.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhmidnk.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsquckz.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxiwealg.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2kelkgsyb.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmruhlq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2iavwvrtq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mrurzbgo.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mfolzpqc.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdwyfri.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xadgikpi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzvfnpt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2jahdbyxs.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsdawfh.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2qslwjgli.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpvmllu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfmyhcs.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpjpvjq.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2bswjlevd.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zptsvkmq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2aauwwrws.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yntuprah.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdpuste.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qevjdldp.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpcbmpy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2stxvnvaw.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyobljye.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpujankv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsbisps.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsxfzvl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgtiruu.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2poqqmjqc.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfrjlbb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2gchkygzw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvrpncm.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbzgxvh.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2aypevpdl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2niurgmhh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2jeccwpjd.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2khuksjok.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpabfzil.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kcombgrc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwsepvv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdnvwca.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxhrqii.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2wztrlqks.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfkwkdz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdvnskv.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2abiaoffk.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzwedft.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhialyr.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nekwmxwy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhzorqr.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2snhljnon.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2dskwfyuc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vihxnnqx.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2lcogskdg.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2madgxatf.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwotnxd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpethjr.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwfhnus.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzosuqgo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2nbybvvcz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpbkvxe.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2muhwmzqy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfxzodi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2rstwclot.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhacfguk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fgiivrcp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2arajpett.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlkfriq.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxmaalk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ydteecog.html


<!-- 参考信息 -->