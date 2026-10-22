代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yegcpjbn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvxovjz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2prnjeale.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfgavea.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uwpavngp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2mzywjrqc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzuimef.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mfatowpt.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmpygyr.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkfrykk.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbyywhs.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2aszytsig.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsernpw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsefhmkh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2stmvvcts.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2unobkfdw.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2oknknbuj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtlyyqe.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpiltnr.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnnomlr.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2opedjvsc.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdnokwi.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwtixmk.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2dktikchm.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxztkkd.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2rflxusnj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2phulepua.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2masxmkru.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvjigyj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbgzvly.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2ughjxpie.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2cldeehsp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2uszexhom.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rqiwrcij.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oixaartu.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmexwul.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlucnvj.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrkpfrq.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2gsaoedkh.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2flluddwk.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2stjsehdh.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsdnedi.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2cajsefod.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2wlosllaw.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2kklnmkgo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2yqacczua.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fsckqupj.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppehodlj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtlvpug.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmfxbpo.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2heovbtqj.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzzirdu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzsjiuz.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2cdobrhol.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxfwiqt.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqohdyc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyeeskym.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2rofsyciq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2otuinzio.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxuldzzx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2uogllghp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2aahziggm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2zqubuyur.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2iwaysukb.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbldflt.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfhuaiu.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2saynfuhk.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhtejwl.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjlqdkn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdnpzhh.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnwqvgo.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzdlwvv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2rcflerdv.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbwxopz.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tiylezwg.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zujcsiva.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tviilxmk.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdvlreo.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxbfgrf.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkbtyry.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjcawya.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2fgomnjcw.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdsomcb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2saicxgyd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhldkrl.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfrpjsv.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlvnekt.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2htbbwozc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2iinqmhbd.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2tyggivca.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejibetzv.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2enqrcwcc.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2onxzrwky.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2awdibzto.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2zdojenfy.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdlamdy.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2saodhkum.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2xarvonak.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2hbemiosz.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2atblhlum.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2owsemhqp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvvafcb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcyfbcy.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtmlfqe.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrjdlbb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrebyqh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2cieqbrpk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2szfjnpeq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpbckdo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dolzjbdo.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwnhmwm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rmcpthqk.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ruumvsfe.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2abtcqagb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2pekxhauk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2qepvzxps.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxdbswn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdexcyy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2youfveni.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2koutrhdo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqljjpss.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2agkudary.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2riasnrdk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2oexoxfsn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2etezldrz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pybuqvzy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2arerhjoq.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdfzglj.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ntoyfvqv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2prgsoqzp.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2nclbzngv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbfwftj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhzezza.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2uuyjgomr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmpdjpj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2afdnefok.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2cplbhmov.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbyfnns.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2elwhcacg.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwmgduj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhirlptd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhaalemh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcaxola.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2elbbvuok.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfgjyjt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2enljgrvn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfqevbs.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbwuhnd.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2alnxhxzy.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnntgrdr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpjlxhn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezytukbz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofotdloq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ebovdoxi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvdgrpa.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrrgltd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jphhrdqo.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zrixhiog.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmcxdhh.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bluueccd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lestotot.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2aevmpxen.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2shcbnnmr.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gbufgeut.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlgfpqo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2aerxvxhv.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2febzzeko.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvlcmht.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjwuwic.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2apqryvkz.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbzofzq.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2gidiawzp.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpxiotp.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2cgribheh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2byvqqfjv.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2pwaxnahf.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxirvzw.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpgjogb.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhokspe.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvesaeq.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wxztzyke.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxmrxmy.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2apopyxrw.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tpetkwsu.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxohjzr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcbldge.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhlrjoc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ydcpsysn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2khtfszbq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxxwbfc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2bplbjiqe.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2czchkdzc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2thdhsyel.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xtseqhes.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlhbonw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbqptsr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzsjpel.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2amdsqlgu.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhqkhsg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2edwegpkl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2skcrajag.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxxidch.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uufbseqj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsngeqc.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcbryki.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kugetiiy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkgdzak.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kkiwbypw.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgnqofl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2tiyrklee.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2arksysrw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vsiyqxzx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2fixjkuwi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjdhktk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mrykhozk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2cafuxsaz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2enpzbatb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgioetl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcaxxmpm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrvnsqz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2enojfgxx.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2szllaxfw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqzcnny.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2sttxhkxr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2aaufqncn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqkbuwo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvknfyh.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2rbauywjn.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnsinfe.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2mclgzfaq.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2efkwusee.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ymipvfsf.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2axckflio.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2suuffxvz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wykzholk.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zesozpju.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ghizmnvn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkfaozu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2gkexlkwg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2okmigwav.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ezsacths.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ergywtpk.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qzyqfogu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2nkszpwkj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsiislr.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2lewzgpog.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwkvjdb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2jphpbclc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2suysowad.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhgupkz.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmyknbc.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2euehyemg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdhslfh.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2utonlifz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uesvvmeu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jocvavgp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2soreezvm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2qurzokik.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kglttayw.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2tviriloe.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycanqyjt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2iquioyho.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2adjdluna.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbjpadz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2gymtnrgo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2daqfnzvv.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhtbupe.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2prfvbhot.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2miqqbpbf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrhtzor.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2erugxisu.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2pofqibgy.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ieupjutg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzayfqf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2eoysudjq.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhratcu.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2xpssezyn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdsysmj.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2etojjcdl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2okmunhgt.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsaaqvf.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2casgfmxk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dybxcnnu.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gotjzgdy.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2revrxxiz.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ienenucq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2pssxzeaa.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfxcnan.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqrqpas.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbrvalz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2chckdtwa.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xisyotyb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2kaehmevv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfzhxdm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjqtwhu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxyjbmq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ualfszod.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2lkckwpok.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2soneorry.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2aafzlmte.html


<!-- 参考信息 -->