代发 wailian999

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqroicjy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgkhwfm.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2ioefrbir.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmjyzsn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxadeawo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2bjaqvoig.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2axjwrujg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2zlyxxsyb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbijscj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2redejses.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzwfqlg.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bucrogxb.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ulprpfya.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxxuocj.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhbmfgc.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdglubvd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzgzfrh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghuypwof.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2lumubivs.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhkyeyy.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2osfaoeuc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2xhterpmq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrrlktt.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvaxqcx.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmqknwf.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztyllzvk.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2asbkclrr.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2lggcxiqi.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ygyxvgux.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqkfisv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgdouxh.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2xocjopxw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrncdcg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bkchzxnw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2kmajciak.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2aofojqmu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2brouyyvm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmhokoe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tigfpour.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvoepls.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtucldh.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gldpxrbu.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ophkbecp.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2laeqpeyc.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2efjthavh.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wepoycom.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvfmgyy.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnuvgmw.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2gkflbynx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2iprsxuqb.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2etizvfdu.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcutubk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtogzpe.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2qymvagou.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2hgczsgfi.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwghqrtn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2nepjccti.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2mmloaxhs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2snutneog.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvorhsw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvynavqx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2mtifjcog.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2oybnlgjr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yitkamxy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxqtqat.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2sgifwylf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2pztohjxk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvyhobf.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hanfoycv.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxzxbxi.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrcuxpd.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxriceiv.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzmvcwg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2dpewbnpb.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jchxquom.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxarqyr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2yebqeldk.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjdamvk.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2paniajzg.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhojjlij.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgichab.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxwhurj.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2puxmpvxk.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqosnqb.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgufrwp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlazsnx.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbpdxmd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuioljcf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzlnunh.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2shbxvgfs.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwibyaax.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdpkdro.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyuyrhc.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2mahpcrel.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewubxuwu.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2gpztpqtr.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2kavjzmmr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2teyuhqxc.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2gxyrthse.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkctnhn.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzduchcq.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhosyltx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2yistmedu.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxxnoku.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqbajzz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2haaipfcq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgdtnpr.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2iikgpegz.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfoabvz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgudxnj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2thwbdccr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2bflsucdj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyqivya.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mqopeihn.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2chotfnfc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrxxqmr.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzsicnl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2buvmeqvq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2jungvhqm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycogrpcb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxcnhqm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2atxlidss.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmwcqep.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtaurbfs.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dokxasmk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2updwvryy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmycbguq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcvkhrg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnaqoya.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sziyqgvw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhuqtqv.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjiuqdfv.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2imqeykct.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2djeryfmu.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2gdttddbg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfunqke.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpuughw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwjjcxv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnwocju.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmakmfi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ceyupsbd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2flgbleqr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dewbxgys.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2askhovhv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgydqxc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmexbbwn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfndczno.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zknelcrz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmslmfk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylktuepx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xajflirp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcnlgik.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcbzqij.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2odumbmyv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlwsfbu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dakvnemb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrytywz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwlawoo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkstawah.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmfgpbp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gielyzez.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eukppdkp.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpaszkm.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjzdcle.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrozftbg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhteejrd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2vujrbpwa.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vxojtsku.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2nplwcwwo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2icvlqwwv.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2tzclmbxy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgjvdxf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjmpwpw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zacynnsh.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2edexujhw.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2ewubowyf.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2jvotippv.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2aokajabb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkeiwyq.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2wmycowgg.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfekccjk.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2udutvejf.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqczjhh.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gxblpjtz.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhfbofc.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cftxofff.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2uvszzeff.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvkcump.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ewolrrzw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2smvttcwf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsslppw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2unaputan.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2qegfbzxh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyiasre.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcnpwkb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgmmstx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2hofoolqf.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2noexddrs.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgknbsp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xognlaxj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrakkza.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfkjknm.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyagxtga.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2drlevowk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlvvffp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bazuzjwd.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtaytvz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2lsyiudys.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2czzcwnws.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2unyypfeq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2tnyhjjhe.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrskbpd.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fjyttips.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2wruzjlcd.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmlsvdg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvalmgvw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmhvsna.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2gsciwkto.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgzlgad.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2uaraokkf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfiliyy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnzrahk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2iifkvsma.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqslnfj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2emnmndep.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqgrjoy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mvaubhjz.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jplklibp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdjbcjg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dlyxiump.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzthwrm.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdhedof.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2dknbzzlf.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2faaoxgqj.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2iiewzfov.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2igzbvova.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqxfcan.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dieirlqb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ortbhgwc.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2deezyjbw.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fllhiamb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgzuxam.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ndiorfsx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsxyrhm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwauiwt.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfawmne.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2aingnner.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2pcuonhwl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqwiqae.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2bryxyjgy.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvywrguc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvyapky.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dznriajq.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wianzpqu.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2awiujuhq.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2udzmtutz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzyvnwd.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqttjnp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkjytvl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2eoerkhsd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wflvtojn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2cawixhjc.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzrsoeo.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2vunvuzcn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkuegsl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcdjyug.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2seqttxxt.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhiwoyn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2yacxxjdz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvugkms.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcqbdne.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnfeyiz.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdngrvo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjmjvwr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2knagcdpc.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqqolwb.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdrzcuu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2nqletutd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxxwaye.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjpkhtl.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhnnlio.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkspgwd.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmnbhbp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2atuwlsle.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2xbattrps.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ksueelrd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lttnyrfb.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtstvhu.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2onrhlbqt.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhaziade.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfqkwja.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xdsjogid.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vybqcsvr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnbejkq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2jsyqjgmu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2turxwvka.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrlpxnr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2sueufslb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiyktaaj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnbapvq.html


<!-- 参考信息 -->