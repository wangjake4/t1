代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzmrrhi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2embzyibr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2srkqnzma.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2slmsyepc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zejxdhlb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmzhouf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gawqbajk.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgvisgp.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqiatlmz.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnquiwx.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsegiux.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwcwlnq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2vocgsmiw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcmrjcx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjofnon.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2euderbpn.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpmfdpu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2havdyagh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2aadotnvl.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2msqvtaop.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2oonhlfld.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2pijvgqvn.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlzxiyj.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2sbadabba.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2nndppmke.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkmafha.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxkulvx.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2cqceweom.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2izawaiuq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tefoudru.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2neqeftro.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2iefwncnd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxlzizt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gupxhiqq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwskvpo.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2knyfwqsj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqcdaqf.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2juxiffuw.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhrnwms.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgzldrz.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oraikduv.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qioiyman.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsgtjad.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2plkffqpt.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2zysdwxmf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2kisqvtax.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpergro.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2leoifslf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2woounrmo.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxbxlkt.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfqqain.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdvnyve.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2whapbnkt.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxdnanl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfnrcxa.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ztatmxnk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqmbrna.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnopiji.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjnqglu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2szahdsfh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgncokds.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvmggfz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2tnuyioxq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2jpiwyoeh.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxrfbbj.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewyomjzd.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzxormw.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtzppzr.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2beegyluc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2ribrfkaj.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcxcruq.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2onigpabw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfvoeqx.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2nesqlsct.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxtwtnx.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ashneimm.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gleesuvo.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfbfvpb.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulsukvpo.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xemrogkz.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwhhcdc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2svqiuqiu.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dngccsav.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oeatldxg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdtlqww.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2larcuucq.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2suxqovug.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2esukjtzr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpdajxo.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2atclqdfa.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckswnqrz.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2mueffybw.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2geszmfwo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyhrxdz.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2pirqlgnl.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnzcdjr.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2sekdekvs.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkehyqrn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpipupl.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnqvswp.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdghzts.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqouiaz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2qcceunwv.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ojauaeae.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2widlhezd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2cinuwnet.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtiaxob.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2qchvsces.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2qysgtyls.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvjbyym.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbrgfod.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2awswdpez.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2iblxyuct.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmbmzks.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxhxbya.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2szmalopc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2yivfyvhh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fznjhwna.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2umrzrrmd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjyqkhvo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2esiawsjb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkqzrwk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2zorbgqei.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsyeowpr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjoylap.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcvofxn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnahydu.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnonllqx.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbmjyft.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtnnhnv.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdtbctt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2biltdomh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2xlexmwos.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2cvuoqzhs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2iezljxmk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdukzby.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrpekhs.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnxysge.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gswnokto.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2whnzvkbf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjpavvd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqxqvxv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qswgilrd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2arpfpfyu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwksojgf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nltairor.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyijznyu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2webjttbu.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnnwwom.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nidscbth.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrsncsr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsypqev.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecexpyst.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgwdqjr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfszgjh.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvwbkyg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwvmqzb.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nvatynbb.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvsnqta.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwiwudzv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlklezmw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwadbebp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2tilrunvn.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlkkiwe.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2jvitgrvh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2umenjjfk.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcdzzax.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgwytkv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjxtnbf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqawbki.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfikbjh.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2rlverkza.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqrfzur.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvklydo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2gzoqaipp.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtvvekm.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkolayg.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhfkkha.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mhifyafa.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhxojgg.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xasgwxay.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tocrnkzp.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2llvlanqz.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnyarkf.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rcntwumj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2llrveaiw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzbowwd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kiljhwqz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvgegbv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tepznmso.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkrssil.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuwtnxg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrqtive.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2srdmpwpk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwpegsd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwuenled.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ridqgklu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdleaxn.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdaaheb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhysoka.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdhmlgb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jttpngxl.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2knlajhur.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdezqse.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2clbpgnzq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kogspdvs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhkgush.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcytehm.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2owwioigz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2fmosgrfs.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2akyajxfb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2saoladzj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxpyvkq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrsytez.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2eritwdjf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpufgca.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbjyqnv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2usimgvuv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yexsiwyr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vubhffkj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cdljaetd.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2oreqkwur.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hujxnvsf.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2qexiucnw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2wknzrjbz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrotjjf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2rigbvyss.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkourxk.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2lcevybsl.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2ksuygaeo.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2gubkrejw.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2oohbxsuz.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dnicqlak.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wveuuhsf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2sutgutfp.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pjumwsqx.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdknvbi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yefwvneb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2bjngvryj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2idvnzkdn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2fqemeugs.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2etnfxqlh.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwbjsfg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2etbaofpt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqivjng.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2jlybeeln.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gprqxkgj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxzfnmy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcsftpb.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyohcxuu.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmufwqn.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2izbztdju.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2svkfoeui.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpifqueq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuglpal.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgixlrp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpiycfr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjxzqto.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrggnsfz.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2vbynfonw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrxgbec.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxsljcl.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2eugkcmwd.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbamrfcl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2daobmrad.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdcmztw.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2imuofemk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjflkqk.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxnoviz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2gpajwsss.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2omgqbwhc.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2tksqcrhc.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2fhllwrmx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2xndujxck.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2csmqomfh.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2klkbhyef.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgmomvd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpmrcba.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ncyavigs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vozmbaku.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbzythd.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpzgvsi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjelbpw.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgnlcgn.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2sfezboak.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2keegxwbu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2eakuarmc.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jnyzejgw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jecdccoy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpkroci.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2okdtjayy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwbzmhg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvrudsu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrzpobw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmaggcp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mnydjnge.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmtwidn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwrlukr.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgukmfe.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2qytuyjyg.html


<!-- 参考信息 -->