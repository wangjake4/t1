代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxywpoy.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2wesodjqw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2wieazrqb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwunuba.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmhoqfz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpkipdn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmtuarb.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2divdclte.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqjbtez.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gheufpze.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmsivrw.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2oajlxwcl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2shvityeb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpebjdy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2ossnmouj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnhrwvu.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zpuujzal.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2bybmwtmt.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2farojcgp.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjsqfav.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2unogdtgw.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjfebug.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsjwnev.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2mmteczqv.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2eopytoeq.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2snylyoud.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2exsarzpl.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkplknf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cezcwbbj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jflhhyvs.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcyuxaq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuiqvyd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvbrlmy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yotwsuty.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2przejrlq.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyvpawi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hdulnunp.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxzpuix.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2vsiqejmb.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrommsg.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdrsuyv.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgacjmtc.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2maoalccu.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2aafjbyyy.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2hoiiaemi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfadhphw.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2csvhbidn.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdmxlsu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgaxurnw.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxhdpys.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2itlmvoea.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2epjcizdv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwirwoa.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2mentbsuy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2wysyaajf.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnajfsi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2omsiczjn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlwcnep.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzpbwnw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2naqbdbqg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2xeaslavr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2bnempnfq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsqpftm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnviuys.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ydglzcpu.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2nodactwj.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhxygqa.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbyskoy.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2frsnfmkh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2bysaltuj.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rwlogatx.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2eunlxiyj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2jinnctoi.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgtyplc.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdcyqen.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmjjbkz.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgpsaai.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvuzgavu.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwntswt.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgiwaafe.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyaiyuq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrjwhsr.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzezpci.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mztienul.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2iokjxxgz.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2czluewcx.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjbxxfp.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2kkskhois.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2cydnxaau.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2fksvbpei.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqweahj.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzqqruo.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgsavwy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzosetx.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2wyevtadl.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2wchcmsae.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkbnqnm.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwlupcj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2manawwlk.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhlbfol.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2sozdwlwl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbambif.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkunnjn.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2weeyzyqw.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnsocid.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2stnphoxu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhtyaot.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2dxefuwng.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2gjldbrnf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdyuasx.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpheioa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxxvsip.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2keizppub.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwoqmvo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2chwthcbb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcevlbt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqkhgef.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tviscpgd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwedgmd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2mudvyhou.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpiyovui.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpqletf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2osmsjxbw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbkqplg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvenewyv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fibnypki.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtodorh.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhsucoyb.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qcezqdex.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyapacp.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpygdqs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvyeujg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2zoypfqju.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqrjlxc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbhdzyn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2oidntvhq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmalbst.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnjljkt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2grkqdchl.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxadxik.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyyewios.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqoelhu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpjnfuo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvswxnr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2apxiwgvr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2absgmday.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqbamyg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqllxgx.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbkzsvb.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxetvzao.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqzudgs.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcydxzbg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odferebs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpsuvga.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2psicdkll.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2avjkgzdn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbpdxmf.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2amjkmqlj.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2smxcbslp.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdegizo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yearxxmg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwytrvtn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmmjdgq.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2byqboctt.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwdttpq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvaanrd.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzqtsus.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxyzptv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcfdpjn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwigtrr.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2casdxufk.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2wxewherq.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2paajjmki.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2mphsqpky.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2efzljyjj.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsgqgxi.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2plgnlqcs.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmoxyvk.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzniiny.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rblfqfys.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rknrcmsc.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mziswfyr.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkneuzv.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tkehquvu.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxegsis.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oojdohyz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvjruvu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xcygkprl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgougnt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gstkkykh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2gumrjeyk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pjipyuhm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlsminl.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2azzpysqz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2vyecxtem.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnhcben.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsgctmk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgbfrfi.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfeofcld.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhiuolf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2wufkvtxx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmldtoxx.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nlordxna.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2rgeueyyt.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2egqsfwdz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqrickx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsdozxf.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbrfbdp.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mhsmcfhw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2flfmiclk.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2obojlzan.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ghiumxyp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2poznhsca.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2juzvukuc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfmsfwx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2cottfqsj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2eyewufmm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2twctzost.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqzcwtp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xpumvodl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kifgtxmw.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2cuchmwnz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhlblad.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdbczao.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2budldxib.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ohysukgu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxjoqhy.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbtrjyd.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvknjqo.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzlotwp.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhidttvv.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2srkjporq.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxqutev.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfafygj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2bekxxrvz.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pksvzvuk.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2biviqgzq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbwxgya.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ggepafxj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjxmrwu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2fztqplop.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2silxzetb.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqspksc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrjnvxd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2tnadsmvr.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnmxdrc.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oagmzmod.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2yllrxzts.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zreagcea.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsitvmn.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2tuyeiqrb.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2evzbrlbs.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwmftrn.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkwqvnr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcjknxa.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtovdrz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlyvsby.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2avjyeyyi.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkurgra.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2krnkbovw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2tliwzuif.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqipqpz.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ospkelng.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmnrfwn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2fryjvuds.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2eufvmqat.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdiocbaq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgtxpmx.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkbmkqq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2froedrhh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgbxwjt.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2cppkvubw.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmzkiyl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwrpvmz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxgvrzv.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2mmeqvzgy.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2nllyzliy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2trdvnqud.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwtsrtq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2caowmyra.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgbzkim.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpzeexc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhiilhc.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvdtyzj.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxtulqk.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzxyfcd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtyctls.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwvwopf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbwzoyj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsoslqm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2tojfdkaf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlavrxyi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcmghro.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuctdlb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsfopmp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2exejevyz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgjviqb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2xlisgbke.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzmlnox.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2iorfkphb.html


<!-- 参考信息 -->