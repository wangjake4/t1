代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jainltmr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2amvhftrt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2golxpdya.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwayyar.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aihiazrc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2tohhvfna.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bweikjnv.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhqemjc.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2irndpcti.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmcjqll.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfgluzy.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2usjotnbd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2sooogond.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdekrtl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhacaeuq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxbvcmz.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2uafgjpgi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2svkfdcrf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmchlrke.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpehgdz.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwsmqij.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2korswtzw.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2tonhchrw.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2usnesima.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfxcbzn.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxahcbi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbzbxai.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2assbndmg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jurwxttz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gjaklmjd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2nmoxetbz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2obvncgho.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2epnbibmg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyijssu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdufidq.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzptbcs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nczprgyj.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2szsmnvea.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxovdpt.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcgtddz.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2crncmmmy.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsurexe.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2coyprcus.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2lfamrsal.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2scaecvhv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2garvorkw.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdgopja.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdshoob.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvhknos.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2crwummwx.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2yigtbwkt.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwdhpyq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvukodt.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2tajktzic.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecypuqbw.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2eybyxfpj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uitjbcfm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2idwezarb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wylgivea.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tuinench.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2obcvsnmc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjujszse.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2ludknrue.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2tiogwhip.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgovwpy.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2drwiiqdt.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2bawndnyl.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjebbthz.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2klmcanhx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2qndojztp.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2pchsivyd.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2ggywbldz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlzqdjo.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2kknsunul.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkaajut.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnbfncg.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fanmobxj.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhatovb.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2optrdqyo.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdhtkdb.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yckfnxyz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbwpliu.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mchzvbut.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2duhlexbf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ajohrugp.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2flqtrgfb.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsppjfa.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcauoeb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2rocuenfp.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2ivavkpau.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2aeegntek.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2uesitjai.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2jndfnoog.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jodvswzk.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtdckal.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2alnmuats.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxegoft.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2imbmzema.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2acpkzcwe.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpiyjydm.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnnbvgx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxoepow.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2ztczjqtg.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtmddvx.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2crbmtsfm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvmhtsz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2hunjdhmj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2wythxoiy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2iphhjmrb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjdjqkq.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2trnswmus.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2plmkibfb.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2diyslrsb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxteday.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2orawaldp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtnwicx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymogjwzd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmizpcet.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qauvlyjy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbccbqzp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tujqsabn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2hezdiawy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpazqqc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuuaxyen.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2slebwnvg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivftpvhj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jchpncxg.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2btydglia.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2suhkkkho.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2injdebim.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2ozixyphz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2pisyrhyv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2drsdigbu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwoaquq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvavgwq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tgynoimb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qejupggn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvftynq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqnkuca.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwctsdz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzttoqn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoujlmmw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2plxppvwu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhmngbn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2isivivrz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwxxuqd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjergblv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ialxfomu.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2wehiwikq.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgiyntna.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ungsyibf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyytxmhr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzptebsr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdzftfj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2enlhswkg.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qezudcum.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxmvbjf.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcolhrb.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2azlvihoz.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmioify.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppinwkiv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2abiugckt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2stnjcbca.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmpacse.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2vidzdnzi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2gttzmvgs.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2seupxlnm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlvsmed.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgdmnhd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgwaeej.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2zrajlzsh.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfhnzii.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2fswlviop.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2tthdcrqe.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2nangajhc.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2steyncua.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwpixiy.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2cyizgckq.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2clldkyhb.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdvffwj.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjaqbgw.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cltgxuhv.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2kgksusia.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2plpxnnxl.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wncfpuxv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlbgxeb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bkicxlvv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvsbxlc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2gplnicat.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfxuoxb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2btekslxl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ihngpdmf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2vratqfnf.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pizuddwk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgkzuwx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufivxwir.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeerrbtk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmnqeee.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdoahflc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbslaml.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcikaukb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqeognw.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqmtjmo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwexrel.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yyscdkzs.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqktmmx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkmqnca.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhlsepc.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjuqzud.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfdqllr.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tuyzydvv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxiqqfs.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2zgggtyeh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2cifngbgz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2hvogaaob.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2crxhvcgk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkmfbut.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dreyhnnt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrddxua.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhfbqjb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvfjggj.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhabbit.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtvjtey.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2aswomjuj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxegtgq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hqpktjfx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2bkyndfsp.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjwtxuu.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ictuyiob.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftngfavl.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2owvyhnde.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvxwjhx.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2psnzwuew.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkvautn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2elwlyzcy.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkhnrpu.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hqubzokw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyalofxx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2wasqllkg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjkziki.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzvwdab.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyavnkv.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2exmzdrup.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2adxfwwfc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2jezqvpak.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbhlopj.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbxndrs.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrldsya.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkrjwmj.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgzsadd.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2snqjuyvk.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2icbspoks.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2heghpjxo.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2befyuaug.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtecfwo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2eglzaqvc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpitdzt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbqrugm.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnapvohj.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2swkytlyr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmycsha.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqvvdzx.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzfegrl.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcjtzjd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovaqvsfu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2htvyllsa.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2svxheolr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxepknh.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjszujn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmltptkq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlsbmjc.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2tozitjvo.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrvfxnw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2iibwhjpy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2swpgoyun.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgoewys.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2isbtzcgz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pnstfzkv.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dscljedc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sluahwsh.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2oyaaaqua.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2hmoszkke.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2bngdmrsx.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2agsphvcy.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ccceqgtx.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqaosirg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhbggec.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsrnifb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjckezyh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2shkzyiwa.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2orabvcru.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2erzdsgyx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnijtrj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2jesnqhur.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaavawya.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnlbisl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2secbndkj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ioowjiou.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ccggsfaa.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpjjcps.html


<!-- 参考信息 -->