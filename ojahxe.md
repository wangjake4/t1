代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgzpscd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2urefcpmk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2xughjbfr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkvwwxy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uobagpps.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbwmkab.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkhuvxe.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsmpquy.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2olupqamc.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2icwjnzbn.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2efizgfnj.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqoprtg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqliqhmf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2besixrpi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzgemth.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2eisuuqgt.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxrhquo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2lgijiovh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwrprel.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjobbos.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjrquxy.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2jscaguam.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2xggobdht.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxwnuyz.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfgabmg.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2hofgtncm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2qkduymve.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2byuocnut.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkmuyrk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yvosfolh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2vgolqjrm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2pdopnbfi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxrtveq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbdqigi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mteeojvp.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qawyihja.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyhenro.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsmesvs.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2iieamado.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzytflt.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfadlwjl.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqoiylgp.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2oskcwlwi.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2chfcdepy.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2eeorcjtt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhqjbvj.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvznxzj.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2udqbbtst.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2lodvbkez.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2bilzmcua.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2sgamvebb.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vczgzkbq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmoqjhyk.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2lasxbqqk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdncrtd.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2dinhffkk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjeanfu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2oeacjdxn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2irowfedc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxywhsl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2aklouiww.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrykjxq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2odmdmcvl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxwhjou.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fgibtrcr.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmaaauzj.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwuensi.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrgvyax.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2espzxqye.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2dikybcbl.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ckogagdy.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjlzcof.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2wbidnjsv.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzhhjru.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bikrhptv.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwnvgpe.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2scurmulv.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqqllix.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2icmnqtef.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgsldtg.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wunjvovs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2npxleybg.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2quwuidew.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eoltacme.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2iobcgnie.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzuzwjc.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xduhsfdc.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcwwtpq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfoxdohq.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2akylmras.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixguhsjn.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlajhqu.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2leesrwjg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbvrkgz.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjouyol.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvkfqdu.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2raxyinqd.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwgujap.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2ayiypqnb.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgytckzm.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2vanberkh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsyokyr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2wemdzvch.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ajccgtqr.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2uppjttyw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2viqwqfyd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2svtfvgkv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2adqlmkti.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2qorcwkcs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnezojy.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlkvatb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oazkqtpj.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2hzapyizw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkxculg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcanvlc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2iptjcrsk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbhwuet.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2natlaoyh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2thjqffwa.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2enwzucfb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgwvmsz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2zypklyha.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2owxvykiu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmzijvp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlhwvnp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvsuzky.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnymwaa.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpoflmdi.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2khdtdhsy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmoxwnrv.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwveqpn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqmszrm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2yboenjqp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2jjcyvdxt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2baflniqc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2lwutfshb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzvzjlw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtatdhu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2idifekfg.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwxfgzh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xetdltvj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqlhoys.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2annijbxn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekaxdvtj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqauhqa.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndivldoq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbhqqmm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfipdcb.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2cdifzqxc.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqcfqhn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaidqjnh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqytwsr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrmtagd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2zndpwnev.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnhfmmn.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2natdkbvl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgvcyve.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tirwaovo.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzeyhxi.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzygizc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xencktts.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2aadcujkv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbeazqc.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxrkecg.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkpyfno.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2fldlekpq.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2krtlpdhb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2saciyxoa.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwjwpoh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxuwuuvc.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2yqudtiyu.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2whxbrcve.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2sursmktb.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2twgrsqga.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrwamfw.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2npbexhff.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpybwtz.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2fvaxqkqx.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtvkyxr.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmkqhdq.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lnyydakg.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2whwpziwl.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcmiuqh.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjvkjfr.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqtwzwb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2aljpnzec.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lndchuzj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwjixpd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2veepudsb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hcupjjpo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsdtqdr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgyacyx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2zebxxyvr.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqodzis.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2dyredyvl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aufchnbg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpyqgljp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvodellf.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2baphydbp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwmzwlu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxqavwx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwnqkgf.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsqzyzx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2imtycraq.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kioepemy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjfgsbn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kuljubgu.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgrnqnc.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wseldbwl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2rodpyfxe.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvtjgeq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mykykbzf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzwionl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2zlskiczv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ohizrdoy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2umreqeeb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2radjttsl.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2glveamwc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcycvkb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2iajyshmb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfjbhuf.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbqfidd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uegkhqrl.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2epbmyhoj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2njfdibmw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lerayvdf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2mctvdahy.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2griffbju.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ouikwsxj.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2axzrtbtr.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2kskyldjy.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2jiahjnqs.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bghsqhmc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsharxl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvsxrhk.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkwwzjp.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjqduqx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrsqcgh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxhapkj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbfkmjp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2khdwhmfq.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2qkufmicx.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjvinsc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzxaudb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2muuvqdwz.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2esphnrye.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvgjgde.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzwnuwk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dipkcaxo.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvgoijr.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2roxdcqpw.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2anifkblz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2wltptehw.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrwvnfr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2glybnlfk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnovxjd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtjiced.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2xyynmmxe.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvhifru.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2sypuekrl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2opnpzodv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2uojwiwjf.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtqkrhx.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjzpvnl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdutxzq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2upkqujnn.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2inbjqvhu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsunwllz.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zkysdbcu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2zbeqyffs.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvjguoy.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsmjlty.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2lhadxble.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2zsoidjix.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2imibpjxn.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpyqvbe.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnkhrvk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhppqdd.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtxnjgq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2emvxssxf.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2sokjzsed.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2kdehtkiw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgmwdxv.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2auxjynmm.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfhpeip.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwdgsjb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2utlxaqzt.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbeoiuz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hejqcehc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2goktlefp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbocwtsj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzhutmc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqavyyh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydugoasu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcejbam.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bogjvbca.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmegmnhs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkjttco.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzdhbof.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2yqubjkob.html


<!-- 参考信息 -->