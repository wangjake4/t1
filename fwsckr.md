代发 wailian999

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ussmxhzj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2krudsaqx.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlawcka.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2nukqzogf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwagsbs.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2lnixwlmy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhqewte.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgsybbx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ciizatzi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2iticzfgx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2anzdckec.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcoddyu.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbukgtq.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvkwbts.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2abwmkekv.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2faikrhcp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2flcdwcrq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2lphwdkru.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdxjpbb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2xritoxnl.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdidlse.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2yeppdjmg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2oweaazuh.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnvtepl.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdlnaqg.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2numfhxsi.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2sblxvfen.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqfppom.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzwdelp.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2kxncgzrg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2utvyoxfb.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2waiglpik.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnckbdi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqoruzl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2ymeoohoi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2vlowcfug.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2nonfvidi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtkkedv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xevjqfrc.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfprqqg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gzehbenu.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2klggvjeh.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2srwucrln.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsnvhym.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2djmbziwi.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxmkcqq.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhymatm.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqkuwuj.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbfpqoj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2poklrdox.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqsnscf.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxnadpx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhvoszx.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2khysgbgw.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpjkwis.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkalazzz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2afoiytah.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzvcbsp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxsqqiww.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2huilefhp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfjqzfj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjvlojr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rffpcywn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2btyvwabo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fyajxbyz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmirxdkf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmpdmlj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2obujzxpu.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2auayytvt.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2kendalem.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2dxixvyuk.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcxulxu.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2onemupot.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmrswcy.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2wloydtvz.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2ilippktv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnwmtpd.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2blasjmny.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2biyloctb.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlkcuoj.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfiuomeo.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkgzutx.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtaizoet.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvuukmq.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2axvfwnyo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxeelqt.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlvdjhw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvighrfm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2rpepsgiw.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2dynkhphn.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjtmnqi.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2otatttxf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2iozzlnst.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2joccaczx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvuqkcqf.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2hghdfzzg.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2pklfkfol.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdlumox.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ullnlgrn.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2plzrzxgw.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpiahld.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2xttbngmz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfmwkqw.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkrmmjx.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2osjqaqtn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2pafkjynx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2wutakqfo.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmwjwzj.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2gojfuadu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2hygdlkcg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrzpxgb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2giazbdfh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2favkivjv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bkleaqnz.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2nocgblar.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2epnopano.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzszmza.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwoxuxym.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2enxcjesb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkueatmw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2dynjlvta.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdzlkvo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmnbean.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2laoalczv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtqzspk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqftdrv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2wsswdeyg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrrhobb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2umnrvfmf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2meywfqub.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjwybqe.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qegvuind.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ygufvsqb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxnthyk.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2dqagpkvz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2phseqvle.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbfbxqj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjhqcfv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2cmelhyye.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qltkboka.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jiskiqll.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2vnluuibj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwswrzp.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2hinownwn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tldhzdki.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2njwafiqb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dznpxhoo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmmclqc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahopufic.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwdifom.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2drfcusdr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkvaaxz.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjzscdf.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oznwgcut.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cesgoaca.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nctqwrdz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzjrrsa.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2abntekzf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkosyfyo.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmlprrz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmfihlz.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwyzbqo.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgyxnkj.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nixswvll.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2joqrknqm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bckyuwgq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcxzqto.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kahwnywp.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ibghndxk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2rpydxfup.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2dveenjzr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2zozhxdfz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcuzguf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbpnboh.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2wiemydtp.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxpmpaa.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxbrcof.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtsvlwr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqfwpcn.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpfjpik.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aryxhnvz.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxhzhic.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ntilnoap.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gssvwfph.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxuinyz.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2trsvnzep.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2nmydjcev.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rahyiybt.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xglsalqb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ornqlwtn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oksssabt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fyimvjey.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2smckkyrw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vumrvsvk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2hdawmpyt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcqfvkl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvzgcmm.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2caynajly.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2ubeduemi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awascweo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2efkonflr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhsjsmni.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzvordk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqhvjjl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpwtrxk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iphagvfx.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vsarsjts.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2aijmjrru.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bruumiuj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcjwhoi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxsizpp.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfxsqxc.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgjmsls.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbemaga.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2trlcebjs.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2uurtkqwc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ozomcwgt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhauyvk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2weufrdcm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2suuitdwa.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdhysby.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2utmujqvj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkswwmd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wluwupvh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwbhxwi.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2olqvyjdp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jxaoqeyb.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2rrsmwcda.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzbatvf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lovbvkyx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2awoveuly.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ccawqstz.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtczqaqy.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2stilfndg.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2rknibokn.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2drlaqbxa.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2sgisxzne.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmksfghl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2rrohgxnr.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2eagaijdd.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lixpjhij.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmkshnb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2cawmvtyk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvappua.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbxmgxi.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2dspsfacb.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tieqiyen.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2xajusdal.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2okuxqaxz.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfiqala.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2myopoayx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2uwivbelg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekuhvprc.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkasmobd.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2feuqtvgd.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwffiluu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2grnjghns.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzozuslk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyouehg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwwupmr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2uovihigx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ytabyjwi.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2alxqytgm.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxnmdsv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfxmaeq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2rskwsrmt.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2sompfpzv.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpdyryh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxcapgh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2gcybygjb.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxhdxbp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2srnlemli.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2weuptxgy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2yveowhom.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvrtjgg.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2qbympajs.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2kiftwidi.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2gggztobv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgisygj.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2iohxcpmg.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmfasxa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fwntxcte.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnouoto.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdxxhey.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2abbzjvvc.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpwerbc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2icveixyj.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vnybbzre.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxvyghc.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hupsuzni.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xystnlfb.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2aqekihyb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ulscpewt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpkmolu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ranlhhha.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwdlhgs.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzcusmq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2crrvtiiw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpehhvjr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2luwvudlj.html


<!-- 参考信息 -->