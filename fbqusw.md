代发 wailian999

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2njywpknv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfavbpt.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2uevefswx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdoledq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oywxgdws.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpozqev.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2gnoykddt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2grxtysdq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ioutzael.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrnfsxk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpdazig.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpfhaqe.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpljsob.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fakrfvze.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfquvlf.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2chtguglb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2epncvfaq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2obwjrznx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpawyhbm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2yymxnaoe.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fobqasrl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2avcrqedu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfyoxyv.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2pnudmmik.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2lpanwufx.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqljthd.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2nznrvufg.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2voyqmamd.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2luibcjbl.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2maepqwpe.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbbrrog.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhzyqci.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2nupxbplj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjjuqmo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2djhulqym.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtwjnme.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzovpsyr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxqzpqz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcjwwns.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fjafmhhk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qlskgrju.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbbdiag.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2qilqhvzi.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpkepzt.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kucujbus.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqugqons.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtiitot.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbeimxq.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhbzdva.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2kckmabwr.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhdbtuz.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfnmfuw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdqtrox.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ererbecy.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmrdqcc.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2faijniku.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2bolsivcx.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqphnsy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqqgygt.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2lemygqrf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2njxscjpb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqhdary.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgutuic.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqniywi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnyjwjl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqrszvc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2esufknrn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2sofitsga.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fazddzfr.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2puztymgo.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2vitrpzwf.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2quygpbqj.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2kmuxupnu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnhsnxe.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdylhej.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2onhafdhe.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2eutabnls.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2kpufqgka.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fimaocij.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nghuqstr.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsszqxb.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzncobh.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2znnzvmlu.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhkwyqj.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mumppdpi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2otosiupx.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pjcseitg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2knynezyu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2oszbogzx.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmyygqfn.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfomfln.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jowegfup.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvucfdkl.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2irkduosc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdafeue.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2qeytmema.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgedfll.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnpruhr.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2weqbtzab.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpeikkf.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2trpqulut.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2ckejgdzr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2yleczgmv.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2eygpbrtw.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2thjzrgol.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2wdprzrmp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2duxpvyti.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2dqugdlaf.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbswqmt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgeuiowp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2uazhykfg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlvpcyg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2qrawbney.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfpdbcp.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2kydlhjgy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2colmddie.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsrdsgs.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbndypm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhfciok.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxijzot.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjnvifo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2avmjqmty.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzngjxn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvidmga.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqqymzl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2ttyyvzrd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2vehfwinp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfyhlei.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjxcnnk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjggihyo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsebvctz.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwljisko.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjcfqne.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahotbdhs.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2fcaqttbx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2trbgrgmp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpvjzrf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtlrsdf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcdvnph.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rczfdyqz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2tliubhex.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2xeyiuebi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tazcvwza.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2opdyzpub.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzwegfe.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxvnvti.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcuncxyy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxlokwc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpallmff.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofumtxnd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdjurzr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvuaebx.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpywvfk.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdoaqtg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmplyav.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgaqhko.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgupfbz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnlhgrf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckodxesi.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrgbahi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrfxwet.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvsyntr.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyayqzs.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uearbrgl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2knxzubeg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2egpoduxb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2wzscgphh.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2csjpsoks.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcgtdky.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2kqnxziem.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2vstgkftz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2jwztvecg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2diutgoth.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2opwjsbhy.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzbuvzg.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2reuwloya.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2olbzsblw.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmlgdqi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzyamrv.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvphcqo.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfryarc.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2asseqntt.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbvzeay.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fqixzgdb.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xngekmge.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlpcnlm.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbblnrb.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjkjyut.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ntocddlh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zugjwnxq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkxrbnv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zoaxhrey.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2mzddbjwk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpbumjf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2csnotrop.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyxabbp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2haiitvfc.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kugwgwpn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwhggfp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqwmbhj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwvinsx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2whrslkbe.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqscnujz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfxfrec.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpicpkr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjeqtgj.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fxskiqyj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2orcdyqgj.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjunfbg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2sloukull.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfgsgsi.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfmbsri.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ewschrcf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzdonvg.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnrikan.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhldtwj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhfmezg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2yaigftei.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvnkmgp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyqlvfx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pizsdaih.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbkouap.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbserjxj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2chqevvml.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uqaktgcd.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdlkibf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iytbbluf.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ohoblhwf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfhmwrb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tilboorn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrubbex.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbvsorr.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2jexjbfrm.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2dirbpikf.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgukzyrq.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjorjlo.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrpduqu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrfotir.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2txnazdlt.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzbluxg.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfvbfcr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlycvaph.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2rocjbvfu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2yudqvidj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2wflxlqsn.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxrzlfr.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kjopsksu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2jiiqwydl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2htvvyryv.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2pltybypl.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qticycwy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2uffvvrkr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2exlflsdl.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lldcvdxs.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2rztkhvrh.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ndoylrcc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2yldolgpr.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwywhyq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmykkcfu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2luvgvuiu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ybuoawgg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2lmaozems.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlzcizm.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2ryricdfr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2equihjdv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ahktctbe.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2lloukwiz.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlqolaj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfvkgua.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2plcdghfx.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2oivkhxhb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpoliifp.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2noqahtyc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfpcubo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2urtslngc.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzgxlyl.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgeiqgw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ccyqkpgh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2bnnhafye.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwyqjdx.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2qjltlolo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhjikmy.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iqffnxgy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlavwcj.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2famnbubk.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2pilzvkjh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kejxdlvl.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcfvhnq.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfpwobz.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tsedjlvv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wemrcuyr.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2omstrqyj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcftucx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2gxohvfhy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2upudyogi.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpttico.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2vmulvyhi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2owlwucdy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrbucud.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfttgxl.html


<!-- 参考信息 -->