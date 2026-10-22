代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcskxdax.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrsunvg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2nudjultg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2rkniwztm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ygontmmz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2nqarfxgp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hzugalwh.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkhxran.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2xbajofwu.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2brxmelje.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2xsevjyhi.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2uawniaif.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzukieu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftljntax.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkyxvcr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcxlyrm.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmtjvml.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2yapxgatb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2abknkwwr.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2oujdckqo.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2chmeavbt.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvbbjgm.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzulrvg.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2ywuoaywe.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2kgawbvyv.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpjquxj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2elmfybmo.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnlappx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fdibuaoy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wsorcfys.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2yfycjyfy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2zluzlqcd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmucozlp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuecwbb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqpddrm.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ikofintv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrdzgmc.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vasmcpad.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2jedxsgzd.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdclzodj.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2szyujlok.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqgkmyx.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2xplolykm.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkbcvml.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkvogmb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpwfaim.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cedvfqcn.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvilkrz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlxjkse.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2jxffptpf.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhhwsmt.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsssmkzx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2izhfvsrb.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwtkbgl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrwcfes.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjlmgwr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsgjgtv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdhqqie.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2udyceorz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qshyacqi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzagiulg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2eayqsfhh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnrwxco.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxjdwgg.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjncjhq.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhlttlv.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsgqsmx.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmtyeoa.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmuwelh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdunwmm.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2buucvphk.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2vereagnh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhmahbg.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzhjdpg.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdcmkzv.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2oiafwvos.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfomuif.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvqumvl.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfzfwad.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjkebrb.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2aainsboc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2oamlxdla.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfhueeg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmceqsz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmwhyps.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2nufodeqk.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgemyzw.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2npwxzwam.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2egulkvqu.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmhvoqi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqsljsk.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2eobmcjhp.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2evwanzzb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjlwxyq.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2gkopkcun.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2tileevff.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnaicdo.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbfvkow.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2xibafkpt.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpmiuzu.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqprjix.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvaqohpc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2qklhocgm.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmdqatt.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgsrudt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqexaid.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtltepz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjpucmk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkupyah.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2svnhrvil.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2zgklkqhe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uprlddbx.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2tspyyelj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjutrcjf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyofcsv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtlppgx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvgzezu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyshasaj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2akfuouiz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbslxxyi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nslvluox.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2duauexig.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxpdhzl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ierbsgkp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxtotpd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2raooqygv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2erpusyoi.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2trgwrtxj.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jsuvzgzq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsafayh.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2uuylguxm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2xuescwcw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2wxaryvci.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2gryxykey.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2yudunqla.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhoxius.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mocqzeri.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2sebtmueq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrpgulq.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2xfyzcqiu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2okwoayck.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzkfagn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvbhuzs.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybacjmvh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxfjszq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhgqftu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cglkivge.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgoudcqy.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ygduikfg.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxplwabi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vykwgckl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lakwfwvz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sclmwmzy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwigjcx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsjjhdq.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2plbczlpc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuggnbqq.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjopxex.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2nndjjgxs.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtynpqpo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxpgptq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wijncjxy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxdbwag.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrjtlhl.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrlnktm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvqttxv.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpeozrm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2vljxfebs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2nphwypmq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtghcdb.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2srasjaha.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2safvhqsj.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2jnouehnr.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2vaysjrfy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2dhutkisp.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2sylhqxkf.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2powxvbxi.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2khfeokqv.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwnfjjr.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbwtwml.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlusutv.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdqqicd.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvotbtq.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhcgxjj.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcgkexe.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zticjmzg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2odexvnwt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnlvllb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnysubs.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jviivwbz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ipsqgkzt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2twxkmpil.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdalsjp.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cpylijro.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcfepdq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnndzpmy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2apddipxd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdiyjcq.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrehylsr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2duoqfgqg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnchcqiw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nchwzqcm.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzkxoon.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcveuou.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wkascehc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dneptdgg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2chomzamk.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhuzarb.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dourbylm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2nkljasnx.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqkrvdd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2irfgeypp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgmqrtg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2xljlcvla.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdpnfwn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2kibulleb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvnmfqm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfghbmkz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2brzwoode.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqpqimc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dkotamtj.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcpkumi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wlosxdpt.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2grufbxhm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ieyqqapa.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xodmxcjv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmeyghz.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxmzucs.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2gggqcklr.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2smcizlay.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2oukbjhnf.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpshizx.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2cmclcdww.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2twsmhevv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhfmaud.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2khtiiege.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvyesoh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2adgryaqo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhbbikj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcylhfs.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2khkpmctl.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2czseonhc.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkulpnj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpisuly.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2mximbdel.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xstuykga.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkagpvlk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2golgojcz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eullwvxa.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmoprrw.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhlobxh.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2urtbuatg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2xadpmlcm.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2luzeajte.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzjovqt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2flzfaiac.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsvbcfw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpsxejr.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcmjmsz.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzgtxcu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2trjlawau.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdlkfmi.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmxkxlu.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkownpfy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2coaniorl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwibiry.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2vishtiwc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qapeguna.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lusqbqik.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjccbdf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wilbtsad.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2upljkcta.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2qgezourm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2cbacpfby.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2zoppqlyg.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ecunupri.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxlefwn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyxdqpm.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2edmatupl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgijitk.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2xuoivjua.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2wljtpbto.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ehlrevlo.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2krincyig.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hegcihxp.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2trcwrhpd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcoxerc.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jknfgbjn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmglxrca.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2jniqcjrr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrboljk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgilhek.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqmvcdi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmiosaw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2shompagf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfrdnrn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrulqrtn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgssvsp.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fkehgntj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2citlazpf.html


<!-- 参考信息 -->