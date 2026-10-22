代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfkbibc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlhhvtr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdjrvlc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbbfrng.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhbywnv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmochhe.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pwyfiwtv.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2skgquuaw.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2kecgidhz.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzyhjdd.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2iurcxldc.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgfdmef.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcrwifj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqdocwk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2szpqqidu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2tgoebwfh.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2iatbzinb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2syfhhotl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwsbjbd.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2sindpstv.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2txncgsxl.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhqbbhl.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2kutrbaei.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwdreof.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2toxbuvpp.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2bximsblk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxorxmc.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxoilgt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdluovd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2aepqryjk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvwyymz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2vlurxmny.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrxwygg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wekzsqhl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pdccmkrw.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyzhtyn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbekfdv.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fizmnifn.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwibibw.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2detwwyhb.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvuqfim.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uekgnarl.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlyipbl.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2zczziuve.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2jicjgvha.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2pcferfvb.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kadcpnmh.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfmedpc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2apouqlxn.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjactkt.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2tooxxzdt.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2idiatata.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbybjiq.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2lioydjzp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfoawva.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2krfbpwsz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnghlxyc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlvankx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cglnxdlc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uffosvqg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2xekuapcr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmqphjg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2bkosrdyu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpcphsi.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cenlkouz.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2foaxdpsn.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwfxsav.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2psfnsoor.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzirjuf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkycjwq.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvqewhp.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2pztillzf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnngzfex.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2hunidbpn.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2grywzhcl.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2crkfemna.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkquqwwq.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xivzqrpp.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsftmlc.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpiyhvkh.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbkkoep.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2lozdrjyz.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrtjmfd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iswectrl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2utotguhm.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2acvbleqe.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrqsset.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzldgeey.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjnlztl.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2munvorda.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvktesxv.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsjmcue.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2egiznnch.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcdljuw.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxwsgob.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhhckvx.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocomiglr.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2edimoets.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2csotezcb.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvumftx.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvulmfd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpavnlq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2peyloqbk.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2pgipbmyv.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbouxjv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2doswwazo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2myhjwhql.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2auajftml.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2hssqnjxa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ueldylde.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2heqatfyd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nlidabrz.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2lyeuujxl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hltcrtxo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfdmwzg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyuxbrvq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjphloya.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjbsrux.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zahmpyue.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkxaztp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghaxbjba.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnumrml.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2iywevevz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2udtjzveh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2suhynerd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqbgpip.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2aeltrhok.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhqwpyv.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rbslnpbm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqzvyze.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqheadsr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsuwtvv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2uupykuvs.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwqiore.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2lflrzwyr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2mglcdzsz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkffnaw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2secmtpgj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsbezya.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjcjeox.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yracgvkn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2amhokyls.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2exqfdkxx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2keqnscqo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yezhvilv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2czszgtby.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgexxts.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxpwmof.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfqxtvy.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfvdyaa.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkumlmr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfofrstb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfuxnkt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2tqybmkbn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gchasqkm.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2albskhnh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycekkqjf.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wfltyvmh.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2npvwooln.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyqqfhr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cufoadxf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kylatdgw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2iknsvvxz.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ullpaygs.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2cngvrhdg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhpexsw.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2arppzayw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2fqswzvgy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjwbvio.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnxulom.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcusequ.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2oawpxmwo.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2loxlidrs.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqessbu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2thfqwiyb.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2iocvjtla.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqiwyxf.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgbhjci.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxuhofu.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmnrzhd.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgesvsh.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ldznsxop.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2nqspnlwt.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbagwbt.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fqydruwt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ziapqzga.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hqajxrzp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqobwjb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2dwynqkzu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2chreuwfw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2gyaasczq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kevkxgry.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2lafydgid.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zovegmca.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwqggvp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgwsqfi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqzijlb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmqgktz.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohizhtvx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuhvhhv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2exeoewfx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqlwjsm.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hvorvowf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2bldpnxif.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqrtmtw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2stvxfmvm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2iondxsmi.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bzirihpm.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxgkwii.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrvvudk.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2coxigefc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2yesbrdix.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmyekcz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2iosevuwq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wsoewxpn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zbaityoe.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzfnsmx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzacumbu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtwbsbx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mmuysjqa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgdhoal.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrxfeyj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qieeidqs.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrywnej.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhnwnto.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eutgnobj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhtlzqu.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2umudxtfs.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ooejkgua.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2fsppontb.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwuokar.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbslxmo.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2esbppnzh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktalyxup.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2voakkkfg.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdyaagb.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gezvavjm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkabewx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2lmiecnsp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfyebiz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhkgfmi.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2svsbdcsr.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqsrzvm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2lczmfbqq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnbeqnh.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2riydcpfe.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrzglaw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2iejzfked.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rynjgwnw.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfjumfs.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xqoargyx.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcerkdn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhdqusb.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzamwzl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvstujn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2hedroxpm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2miyeqlhk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ryucnkwb.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdtbhqn.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvmttqm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2uquunwvg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ribxosgk.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyefmupg.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jscpuvja.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2xchtmmoz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2bssyfzzo.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdrenze.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjbzpjz.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pizboddv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmdtedd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjbgmls.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqlhkje.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2toctmiec.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbbyjtt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2xigufmhj.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2kpulqijj.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2mcufozrh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlrsgcs.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zypddeox.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrwduzc.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbcnvqs.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2rauuymwl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgspllf.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2owqfjrot.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tycswnxz.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxttxjz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyhhtuo.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2japhtrpp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbkftnt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjeurag.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2jbyzibcf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xanewmuw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2wyurhcen.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2pochbepl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcnozsg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2prpymvuh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzicoqv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpgrmou.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzdgomk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvdqqiw.html


<!-- 参考信息 -->