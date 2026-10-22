代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2aowljmwg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2qettxame.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2eoomnzlv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzjgwsd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pysofoif.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2vbspworr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yczacwut.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pyipqjxy.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2yezcsrvk.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xeeubuqm.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxegkev.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2jolyykcm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtjndbn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbkxpms.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2arueolsl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkswgots.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsqqtsn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2tcphromv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfjyioy.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmihzdl.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjqgaus.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2jrowztht.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpbzmwb.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2jbaldaho.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2betrkxln.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnesrep.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvkzrrj.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2ryexevtk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2roqdkggh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrfyjgm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjebrce.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2oimjxvew.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2zganinnd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rgemuhpc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ayblmkxu.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmmvlqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2acpzjsnr.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhpsvxu.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrlhmkj.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzzbnux.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gruhxtlr.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2idbrqqen.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2xhoaqrog.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2frhjqxwt.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzqsnzq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdynmmf.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvdwgjm.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhagikz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2onrdhbai.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2mysnzjjo.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2uywvrwdi.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2skmtbdkc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkdnpeh.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2vqifeygo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwuduead.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2smwednes.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2usjvhbwn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2czrufswd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2omzpdpej.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzpiqqn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlbshcg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2izjlcyyo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgnokyh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxcdoxs.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxwaanr.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbwgmzq.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvqnkjr.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufeydhuz.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2felglyha.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwggehxq.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugennmep.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2gdojplkf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2exuhjjyi.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhrfwsx.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2auiofxrl.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzumybnl.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzvefdu.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfyugde.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfrtbmf.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvcmyid.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwcokzh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2czqamoxj.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkoefmy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzyjbmva.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2waeniwjr.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjpefvj.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsndhyf.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2axlokjoe.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnrobzr.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkurtkb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2sclormmb.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2nulovyck.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2vewqmhyu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmstmcv.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2makkiolf.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhkaarb.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqoprei.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2duexyfna.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2bbakaqpm.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzxvgmt.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqaylez.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdmkbus.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2rlujtdxm.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvgsygk.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkexzoa.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvwliqq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrhqgjw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpgrnej.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2bfraxihd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhajmvd.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2ropjnfkf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbkkpkh.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rpafshiv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqdplvx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2hehxyavj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2uanravds.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2dohgtnla.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ginbdyhk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2smoswdri.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvxcpvy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pahjowsb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2xqufulbm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzjfyei.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2sndmpwwf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwcwvyc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbnobbv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2astdbbop.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mccyizov.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dejctmhy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2cehaqzjy.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2brlbnvtj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrsbsgt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2lozejvvp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqmmdaw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2huvojbhk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzoqqui.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2kpufcllr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2loxkvzpw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpboywv.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2envatgfk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvobrozi.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uljxtokh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2awnicxik.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uigvqzxl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyxckiy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixryxxep.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2edthzztu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2algpxefv.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2nbexfvis.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxtxpnj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgayuzim.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdeqabk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srajxyeb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vigekwck.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xeyoeozs.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwujtasq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oytriqlv.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2trbyspgc.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2yhibbgmb.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgnbczd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqdqxhq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkahflw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2cvaniktm.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vxumdjql.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2gnphfxvq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbpjhgm.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwraxss.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2kubqcatb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2qitcmanc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsvbjtq.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2izqxhwni.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwyejbc.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdytiyd.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2okadlwbt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvjqrly.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlgmekk.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfvwkeo.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpklrtv.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qilhpmzd.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ondvfcve.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dzimombo.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlflbpu.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfjltsk.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fxeadlqa.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuugjxm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xepviykk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjunvha.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcdomas.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ockadbed.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrhluko.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2qinsbdmw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbsfukf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvdunrl.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rvuseehf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrvpwej.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgglywr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpcstyf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnspwai.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wokezxod.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2mccuncsr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwbmppq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrqsmlu.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vsperifs.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdswczw.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpdpwdq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2hanehuvw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxflqhq.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jihqzfko.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2plculwby.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjojldu.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxangmf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ongumpot.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2witqllcl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2aevtocry.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjassjq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2sotxdnsc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rjborgoz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjplsvy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzlljsk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlbzcxn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcqcsuo.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2txwaduul.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wckstlzb.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2kwiyzetz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2cekcczag.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ltuewhxw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhbzfke.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2qokbgbcw.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwxqyal.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvfkevu.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrajqot.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2snhhqynr.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkhykcw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2alewomhc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2onsdesjo.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbxxdtc.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpgivua.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgekidgl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ncaffyhv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrnmrbf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkjrcnh.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvadlww.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yuugebup.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqbtklo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2loqohalr.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xuphiiww.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvnlpdv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzczqks.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrvuomqj.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzppffuz.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2nigkrlnb.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhfchvc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2rodpslpj.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpyjnuhz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwahpcm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2gppgsjrd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2tunyybgf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmnvzpz.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxsunbfx.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcrvlsb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2klhprmtn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzygiwf.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2siesvmzj.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsuimujk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhswlzwx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2mteimufq.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbiusoj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxknzzhi.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xesywnlx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdgnzab.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ertwukeo.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvdvjaa.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2abzqhaiv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2atfzpreq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2fcatvsqw.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhhshhz.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxsqexy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2skointta.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrnzerc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhkxqbh.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2glnmdsbt.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrrljrb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtvhsmr.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dohfzwhf.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkzuwdy.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2crrfgjds.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2otrgznbi.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbetlrc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbziobw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjmlwrx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2givlmrud.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhebxkf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2bngwsbdt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2xacsubuk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnmszjl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yeynjuwc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdugqvf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdwdxsz.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwszujg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2hblaqwmk.html


<!-- 参考信息 -->