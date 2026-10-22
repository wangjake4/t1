代发 wailian999

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjncciy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrspltx.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlzndgr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2xhutgaqf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxahmkd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2kvaflmbd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2ibunryal.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2agaoyzro.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xljcpinu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2cofcopjd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpqssxm.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xsidiyyz.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2fctyzbyh.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkuupvvq.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxuhmst.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzhnust.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2uejmnbfd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbuhnix.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxppjao.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjshtxls.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdfjfxh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2churvxdb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmikzcg.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2eiagvuky.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2tlyectxd.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2unmgaonk.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ssntrqjn.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhutpoo.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2juovljyh.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxmmgxs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2oiuugrbs.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkftvob.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fioaigcp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qktqabem.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2nndjebws.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2myfklsvi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgiaswz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpkvxcp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmrkaui.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bumbdktv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2anuielqj.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pzytxzum.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgycnnj.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlhvzjc.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkbjxkh.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkdkcdv.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2aerfbwez.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2xeituyit.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2snexuqcx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2diniutgj.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wazkqbui.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrgztas.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqmputf.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqyfwlu.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzhrssp.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2wejrpowj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2epxefsll.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2wvongkkw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrynhnm.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvyotjx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfaebizb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2foifexlp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2diphhchu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfhjcor.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbrtvgz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvubgoup.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgsksaa.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2lesvrqia.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2crciwknp.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2sllmyefs.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdiocuz.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwvfumh.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2alnezjka.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2csakukjf.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2obehrnrh.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2epegcvyh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrjfvpk.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2lsobkvys.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytahptsk.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2aylbvtxb.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbvqekm.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2euregqar.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmygkebb.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fszwaxnm.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkrthew.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxstvlo.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmkeohc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmtdnvw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqcyqvt.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnghheus.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqfqwfv.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvnogeb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wufghuiz.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvymtjy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjkcnmp.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzpeybu.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2axyywblq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqcprhj.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqbtjpt.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpgynvk.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyauwdca.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2msecwnhp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkjhpki.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdyfhry.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2kahecgnt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2xumrhfix.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2pghleiki.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlsnalh.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpklbsk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2uaidtety.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcbfdvx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2kyeerbqv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxbrgjj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2izrhpdpp.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfhtyfz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lykpblpg.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2pekcpdru.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2igzhkcxz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2tulkdatk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2zaiwlyeh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkrrszs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzurastr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvgdcfe.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2veicbqgs.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpocxzbq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2olbvsgun.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlzivdj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwrrzlj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmubxzpm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpmzwfr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhnbmxe.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oebozgfa.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2suagsqzh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkdican.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2eawiggwc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2metynmdw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2drpqxgnk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsgugam.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzsixmw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2imwnlrfa.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqeqkbi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2pafonefk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfgtinu.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwrvspv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwizkub.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2biedjluv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2whuhuwgm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2droqwqkl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2opidpgdm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwdrafc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hggfvobx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gonavqpm.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyaiwki.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnvxekx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2weegldjd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjhhoee.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbsqsqh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ofagxwrl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2faykgwun.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmqixqy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwckovb.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2summqwqs.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2wxaindyv.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nppyyqvq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgyitvmf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xytptpkn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2tlsnhnjy.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uguhwbwo.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzdfdsb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2gthgphgc.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxvidlj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2kowrqvvi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2amsrxqdk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwcqdap.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2aanetfvu.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjjtfjw.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2wjiawhus.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlpuhzf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2aelcexgg.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2taxzighc.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjyeltvg.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2ugidxkjf.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gdequupy.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2iistdaqf.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2czcvrxvh.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xclpysxe.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2lkszkxju.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzyjxbr.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pepvvhhb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bjanohlq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2muikzyac.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2euiutvsf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2vmawzlxo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbrrsqz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2aligbhpl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2czrdayfr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkohagq.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qepltsoo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmhdcay.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2enqlyymp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkobhmsd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjlxumg.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pulvpvww.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiukjjvo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2aerhknlc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyxaqrh.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ermwfxcp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2qykbogoh.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjccilr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mutkocsu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ynycxanw.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fwccewwj.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mzyrcikb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcdhqjy.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdphkjk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lgemsjrv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxcjrdk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2rfiunanq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfxdlgp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsvknyt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hztgolqh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sntqztqr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwiexdp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvqqxqq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yelblcwx.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2oksqxvog.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jkosdpmd.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjtroib.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrkzdlk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbyqibl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2srumafwd.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzpdadi.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzknurb.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2femhsrae.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdgsuyd.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsbecsp.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gyoiyxqw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2simlmrjl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzguzbk.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vopivyeg.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxmqwbb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2drfvavjj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2jjndfobx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdkwrds.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2igifsebp.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxngwhp.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2epgfakqn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2eznztsod.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrvhrtv.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2gekwuniv.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dugyoaaz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2jghgqfnq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmirssg.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrqurdk.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2dvelwsem.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvbbeos.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2quwxbqkn.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbljixvw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyubnoxg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2irqkjbre.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2sepwuvnc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvmgsfs.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmirzebv.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2kblmvvzk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2khmvyvvm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2vbochknh.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyojvbgb.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2npehlwck.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldixsrpj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2iklpuilt.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwhnahe.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnnkmny.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2yesnvggx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwrcxth.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ekyhyife.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2adscjidw.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnvhfvm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2mnulahas.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2amgknujv.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwndehv.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdsyuwl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2msjehrsx.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vryyvase.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzarcpo.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2fhddtvak.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnnrgfn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2anupziqj.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhiyxvdy.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ncckvyrl.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2whadzjso.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2igwoguwr.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrovcdz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtaciny.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2anwbabtr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfdscrx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwradzmr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ckowzfdo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdnjahp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwkhcbd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rcquwwxy.html


<!-- 参考信息 -->