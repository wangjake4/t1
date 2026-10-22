代发 wailian999

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gtehwcstct.html

[L04] 设置超时
来源：http://dali.hongshengwenyu.top/Article/details/gtzhqoipis.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhiwuduotai.top/Article/details/gtjdicesay.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sufxvd.cn/Article/details/gtjcvkevol.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gtjfnycmqy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxdhxicsw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hfpthk.cn/Article/details/gtpdjhcujx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shangyingyoupin.top/Article/details/gtjtrqxukb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinqigfzy.top/Article/details/gtzqnfqcac.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ppjwa.cn/Article/details/gtejtnbgxe.html

[L05] 上传文件（multipart）
来源：http://dali.yuxming.cn/Article/details/gtmevyqpyn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnqzz.top/Article/details/gtpakowzor.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ivvv.top/Article/details/gtwtwhlmru.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.0kj1m.cn/Article/details/gtsvquxahg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gtsihrlysg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.aibaodan.cn/Article/details/gtkrlywmus.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ybcxt.top/Article/details/gtogpbrokf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cqqwz.cn/Article/details/gtmvfptimg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.meibo888.top/Article/details/gtyywemqud.html

[L06] 解析响应为 JSON
来源：http://dali.sxryk.cn/Article/details/gtxzzehbgu.html

Py:   resp.json()
来源：http://dali.guowangkeji.top/Article/details/gtcvddsero.html

PHP:  json_decode($body, true);
来源：http://dali.svipenyu.cn/Article/details/gtyipbscfp.html

JS:   await resp.json()
来源：http://dali.xuanzx.com/Article/details/gtlibjmnij.html

TS:   await resp.json()
来源：http://dali.chenzaomai.com/Article/details/gtaxmjhwau.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gtcppdlnup.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xuanzx.com/Article/details/gtjkzelkgh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ivvv.top/Article/details/gtodsmsvzs.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cqqwz.cn/Article/details/gtxzshmmzw.html

[L07] 处理 HTTP 状态码
来源：http://dali.smart0.xyz/Article/details/gtnluctjxl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebpanrev.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxinkj.top/Article/details/gtspajglft.html

JS:   resp.ok;  resp.status
来源：http://dali.yj20258.top/Article/details/gtljwlychf.html

TS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaoukccsy.html

Java: resp.statusCode()
来源：http://dali.gzhubu.top/Article/details/gtckqdfyuv.html

Go:   resp.StatusCode
来源：http://dali.316326.xyz/Article/details/gtkqycuxoy.html

Ruby: resp.code.to_i
来源：http://dali.9152youxi.cn/Article/details/gtaxofxfcx.html

C#:   (int)resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gtgivhjwoy.html

[L08] 并发请求多个地址
来源：http://dali.jinghuilouyu.cn/Article/details/gtyoxusurm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangshuangyany.cn/Article/details/gtojcgberq.html

PHP:  curl_multi_init() 系列
来源：http://dali.cucudq.cn/Article/details/gtzepznhla.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tianlin.xyz/Article/details/gtptdnmcqx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gtuicducqf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jyoumei.cn/Article/details/gttsqunokt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.snrcjt.cn/Article/details/gtejhzhlof.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenlongwang.top/Article/details/gtyyieynej.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sufxvd.cn/Article/details/gtgsxydaav.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtmgacmczy.html

M. 命令行 / 进程 / 环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gteegbwabh.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtudtqbwas.html

[M01] 读取命令行参数
来源：http://dali.haohaochexian.top/Article/details/gtgvwbktsi.html

Py:   sys.argv[1:]
来源：http://dali.yongpay.top/Article/details/gtrfzaonxy.html

PHP:  $argv;  $argc;
来源：http://dali.pengpengdd.cyou/Article/details/gtasgxpnrw.html

JS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gtwxgrviqg.html

TS:   process.argv.slice(2)
来源：http://dali.pycfn.com/Article/details/gtcsdolqkm.html

Java: args 数组（main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gtgoyhcftn.html

Go:   os.Args[1:]
来源：http://dali.yuxming.cn/Article/details/gtxicpjxza.html

Ruby: ARGV
来源：http://dali.jiagoushi.top/Article/details/gttugeadya.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258.top/Article/details/gtgboyeufp.html

[M02] 读取环境变量
来源：http://dali.aizwys.cn/Article/details/gtwyaidopa.html

Py:   os.environ.get("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtucetvzcw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hnqzz.top/Article/details/gtskdzhbxx.html

JS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gtdxwmptfd.html

TS:   process.env.HOME
来源：http://dali.dianchejie.cn/Article/details/gtvishnqox.html

Java: System.getenv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtdaidpsoy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtxaaugotx.html

Ruby: ENV["HOME"]
来源：http://dali.chenzaomai.com/Article/details/gtnvpmllly.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtwcjxzics.html

[M03] 执行外部命令
来源：http://dali.jqgufenzy.top/Article/details/gtbzindppj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtuowdmqsg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinqigufen.top/Article/details/gtqqwcesvs.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gtnjpmybvo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.svipenyu.cn/Article/details/gttdtolayt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nanxinkj.top/Article/details/gtxvjgkiar.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.9152youxi.cn/Article/details/gtcylmksrs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tianlin.xyz/Article/details/gtffwdmpqc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.birdmap.top/Article/details/gtgsqintor.html

[M04] 获取当前工作目录
来源：http://dali.jyoumei.cn/Article/details/gtgmnawusn.html

Py:   os.getcwd()
来源：http://dali.yj20258888.top/Article/details/gtyfsodbra.html

PHP:  getcwd();
来源：http://dali.wangshuangyany.cn/Article/details/gttdggmrfn.html

JS:   process.cwd()
来源：http://dali.aibaodan.cn/Article/details/gtsswiqmts.html

TS:   process.cwd()
来源：http://dali.tanke756.top/Article/details/gtuomllqdh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jianghu66.top/Article/details/gtsyfeoeas.html

Go:   os.Getwd()
来源：http://dali.zhongyouzk.top/Article/details/gtxtrobynj.html

Ruby: Dir.pwd
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbixzrbqw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.redwolf501.top/Article/details/gtjaskthko.html

[M05] 设置退出码
来源：http://dali.gzhubu.top/Article/details/gtyjzjpqgy.html

Py:   sys.exit(1)
来源：http://dali.yj20258.top/Article/details/gtsowbidyh.html

PHP:  exit(1);
来源：http://dali.jlsjyb.cn/Article/details/gtofqeyxok.html

JS:   process.exit(1)
来源：http://dali.sweek.top/Article/details/gtweadpiov.html

TS:   process.exit(1)
来源：http://dali.xuanzx.com/Article/details/gticekryqf.html

Java: System.exit(1)
来源：http://dali.pycfn.com/Article/details/gtxkznbfql.html

Go:   os.Exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtosisktfs.html

Ruby: exit 1
来源：http://dali.yonumen.top/Article/details/gtnbximdde.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.birdmap.top/Article/details/gtxccjemvy.html

[M06] 向标准错误输出
来源：http://dali.9152youxi.cn/Article/details/gthsaeudsl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhongyouzk.top/Article/details/gthabgoxba.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.smart0.xyz/Article/details/gtxjamobhn.html

JS:   console.error("err")
来源：http://dali.zycfv.cn/Article/details/gtuodywfao.html

TS:   console.error("err")
来源：http://dali.jinqigfzy.top/Article/details/gtcxjdndta.html

Java: System.err.println("err")
来源：http://dali.cqqwz.cn/Article/details/gtdrauxyfj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pycfn.com/Article/details/gtyxbseyde.html

Ruby: warn "err"
来源：http://dali.gogol.net.cn/Article/details/gtmmspyhwe.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nwbrower.top/Article/details/gteghxshvs.html

[M07] 判断是否为主入口
来源：http://dali.kuanghao11.cn/Article/details/gtdjzgcomn.html

Py:   if __name__ == "__main__":
来源：http://dali.316326.xyz/Article/details/gtpaafavux.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zdqjudy.top/Article/details/gtukjeriid.html

JS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gtcaicprou.html

TS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gtogyjenkb.html

Java: public static void main(String[] args)
来源：http://dali.pycfn.com/Article/details/gtopdlvcet.html

Go:   func main()
来源：http://dali.birdmap.top/Article/details/gtwwgbejzz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hfpthk.cn/Article/details/gtnkxifkrm.html

C#:   static void Main(string[] args)
来源：http://dali.jqgufenzy.top/Article/details/gtvyryizve.html

[M08] 获取系统与运行时信息
来源：http://dali.sufxvd.cn/Article/details/gtwuoywhxi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cheryme.top/Article/details/gtwfyyxxjt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cucudq.cn/Article/details/gtqdscuase.html

JS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gtodyevwax.html

TS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gtttmhprua.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttrhyeewj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.pycfn.com/Article/details/gtzeyliqfw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xuanzx.com/Article/details/gtdtupxoyo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhiwuduotai.top/Article/details/gtudiqsppz.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtgyxgfzao.html

N. 数据结构与算法
来源：http://dali.zhixingplan.top/Article/details/gtggribwix.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtcfozjhrg.html

[N01] 二分查找（有序数组）
来源：http://dali.cheryme.top/Article/details/gtiklysjwh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtmcwvjqmn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.birdmap.top/Article/details/gtzecgeelg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gtiifvexrb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gterdyakeg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtiifneqqu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtwipfvmoc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hywenlv.cn/Article/details/gtncqhrcyy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtguuzyvne.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sysykeji.top/Article/details/gtdgfbwtep.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sufxvd.cn/Article/details/gtqxymtjwi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.pycfn.com/Article/details/gtratnharh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gtwjgpdjam.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fengsongda.top/Article/details/gtlaeplgwo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nwbrower.top/Article/details/gtgxvioarz.html

Go:   slices.Sort(arr)
来源：http://dali.zdqjudy.top/Article/details/gtrbptzpky.html

Ruby: arr.sort
来源：http://dali.cqqwz.cn/Article/details/gtthieqpjs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ppjwa.cn/Article/details/gtwgmbocsi.html

[N03] 快速排序（分治示例）
来源：http://dali.dashuyun.cn/Article/details/gtoqrapdai.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.feifeiyinyue.top/Article/details/gtogkwpvxx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cashguo.top/Article/details/gtntbjpshl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgufenzy.top/Article/details/gtuzpiavdq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.smart0.xyz/Article/details/gtqglrevnx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.wangshuangyany.cn/Article/details/gtbnnckjzt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nanxinkj.top/Article/details/gtqpafmkev.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gzhubu.top/Article/details/gtgwnksmvv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhengqikj.top/Article/details/gtymfslqib.html

[N04] 斐波那契数列
来源：http://dali.pengpengdd.cyou/Article/details/gtlfuofasy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhiwuduotai.top/Article/details/gterssesib.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.smart0.xyz/Article/details/gtzfwmcgyc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gtmoazgzsw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtpaiuvqvp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.smart0.xyz/Article/details/gtzyvlpwng.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.c1oappe.top/Article/details/gtplfjkcll.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.snrcjt.cn/Article/details/gtodiycmtn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gtvfvgfgpc.html

[N05] 最大公约数
来源：http://dali.hywenlv.cn/Article/details/gthszwqcmu.html

Py:   math.gcd(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkuqbhcyq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yanxiufei.cn/Article/details/gtuadesqmc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.redwolf501.top/Article/details/gtxgzeenae.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.bjfxy.top/Article/details/gtxcnavsse.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.wangdashe.top/Article/details/gtaumqwsiu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnqzz.top/Article/details/gtzlmdaumk.html

Ruby: a.gcd(b)
来源：http://dali.vqdsnc.cn/Article/details/gtokvnvosb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jqgfzy.top/Article/details/gtteitlopq.html

[N06] 判断回文字符串
来源：http://dali.xylfe.cn/Article/details/gtlibfffvs.html

Py:   s == s[::-1]
来源：http://dali.zhoulong.xyz/Article/details/gtvybcqcse.html

PHP:  $s === strrev($s);
来源：http://dali.tianlin.xyz/Article/details/gtgdiitqcf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtbmysuhec.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gtbtogjauw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.redwolf501.top/Article/details/gthzqdemte.html

Go:   // 双指针从两端比较
来源：http://dali.daria6918.cn/Article/details/gtcxrcuute.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gtwlkijelm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewcxxosh.html

[N07] 两数之和（返回下标）
来源：http://dali.c1oappe.top/Article/details/gtkuylndde.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.daria6918.cn/Article/details/gtfsfzbchn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhoulong.xyz/Article/details/gtszhxbqtp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.c1oappe.top/Article/details/gtckngbpyz.html

TS:   // 手写 Map<string, number>
来源：http://dali.aizwys.cn/Article/details/gtjtapvkjw.html

Java: // 手写 HashMap
来源：http://dali.jiagoushi.top/Article/details/gthelaxzzt.html

Go:   // 手写 map[int]int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdzantkt.html

Ruby: // 手写 Hash
来源：http://dali.gaohongyu789.top/Article/details/gtcwqbobja.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.andypj.xyz/Article/details/gtkzkkrxll.html

[N08] 生成全排列
来源：http://dali.cdnleiting.top/Article/details/gtrqvnpnhe.html

Py:   itertools.permutations(arr)
来源：http://dali.andypj.xyz/Article/details/gtvzkahlaj.html

PHP:  // 手写递归交换
来源：http://dali.sxryk.cn/Article/details/gtumnabsjo.html

JS:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtiilznren.html

TS:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtfwumrfjd.html

Java: // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcgxmfzdo.html

Go:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtpeywkvdy.html

Ruby: arr.permutation.to_a
来源：http://dali.hfpthk.cn/Article/details/gtoiiggiej.html

C#:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtfwxeevia.html

[N09] 栈与队列
来源：http://dali.jiagoushi.top/Article/details/gtqmdenxso.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.dashuyun.cn/Article/details/gtydibnlgg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtdiolpjrk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.pycfn.com/Article/details/gtissvlzks.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenjidiqi.icu/Article/details/gtnwumpfli.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jqgufenzy.top/Article/details/gtaoxgixil.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hywenlv.cn/Article/details/gtofswtujy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtastjlqzp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sxryk.cn/Article/details/gtnsgcslej.html

[N10] 链表节点定义
来源：http://dali.pycfn.com/Article/details/gtsjzxbbyg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shanyushiyangtech.top/Article/details/gtvyixdzlp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.smart0.xyz/Article/details/gterhzalsw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.dashuyun.cn/Article/details/gtsrzflzcj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ivvv.top/Article/details/gturjossdw.html

Java: class Node { int v; Node next; }
来源：http://dali.c1oappe.top/Article/details/gteimcuqge.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cqqwz.cn/Article/details/gtzlbsxvax.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.wangdashe.top/Article/details/gtvqqrtjcb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cqqwz.cn/Article/details/gtxcpkblty.html

[N11] 二叉树中序遍历
来源：http://dali.yangfankeji.com/Article/details/gtrihnxvfv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xinyue.icu/Article/details/gtswfwvnnu.html

PHP:  // 手写递归函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxuhulorm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gtxdqdwebv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuanzx.com/Article/details/gtwarahncj.html

Java: // 手写递归
来源：http://dali.andypj.xyz/Article/details/gtcxnmsbhg.html

Go:   // 手写递归
来源：http://dali.ivvv.top/Article/details/gtdfjxdfez.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.dianchejie.cn/Article/details/gtubbsstqa.html

C#:   // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gtvihyfvny.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.aibaodan.cn/Article/details/gtrctvdttk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sxryk.cn/Article/details/gtmihnrueh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xylfe.cn/Article/details/gtzhuulqiy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.9152youxi.cn/Article/details/gtgluhsina.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuetiantiany.cn/Article/details/gthjfdcfcr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhongyouzk.top/Article/details/gthsrkurxq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sufxvd.cn/Article/details/gtttrofifd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gogol.net.cn/Article/details/gtqmjiicfi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guowangkeji.top/Article/details/gtqtjhzdvd.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtlzhwitjy.html

O. 并发与异步
来源：http://dali.aizwys.cn/Article/details/gtjoquugqy.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtnzrqgkri.html

[O01] 启动一个线程
来源：http://dali.pycfn.com/Article/details/gtodfrztuh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlksjrajk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aizwys.cn/Article/details/gttmrkgzjx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hnqzz.top/Article/details/gtzdrrrfwi.html

TS:   // 同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbzdkvxxv.html

Java: new Thread(() -> f()).start()
来源：http://dali.yvedp.cn/Article/details/gtentcslnp.html

Go:   go f()
来源：http://dali.hammf.cn/Article/details/gtomzaadbx.html

Ruby: Thread.new { f }
来源：http://dali.cashguo.top/Article/details/gthfdlrcjk.html

C#:   Task.Run(() => F());
来源：http://dali.nanxinkj.top/Article/details/gtlrkbmlps.html

[O02] 使用线程池
来源：http://dali.chenzaomai.com/Article/details/gtjodkxetj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.daxiang520.top/Article/details/gtevmrqnkp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhengqikj.top/Article/details/gtrsnhnxfx.html

JS:   // worker_threads 线程池
来源：http://dali.fzhhl.top/Article/details/gtshnxqgvg.html

TS:   // worker_threads 线程池
来源：http://dali.xylfe.cn/Article/details/gttajdqqbi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.fzhhl.top/Article/details/gtcvsxiaco.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shuidangran.top/Article/details/gthhgtrvqp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ybcxt.top/Article/details/gtrxpykzgt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhiwuduotai.top/Article/details/gtphamiukt.html

[O03] 加锁保护共享数据
来源：http://dali.sufxvd.cn/Article/details/gtsrmjiafh.html

Py:   with lock: shared += 1
来源：http://dali.cucudq.cn/Article/details/gtfvzjvtyv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jyoumei.cn/Article/details/gtoibkztlf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shangyingyoupin.top/Article/details/gtxprzjazw.html

TS:   // 同 JS
来源：http://dali.daxiang520.top/Article/details/gtvzgmpjna.html

Java: synchronized (this) { shared++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcgjqvads.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.fengsongda.top/Article/details/gtcubszepj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.c1oappe.top/Article/details/gttgmcsxwb.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhoulong.xyz/Article/details/gthodfqyzj.html

[O04] 定义异步函数并等待
来源：http://dali.xuetiantiany.cn/Article/details/gtlqaooulq.html

Py:   async def f():⏎    await g()
来源：http://dali.jinqigufen.top/Article/details/gtpraomhaf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.vqdsnc.cn/Article/details/gtupshchxx.html

JS:   async function f() { await g(); }
来源：http://dali.kuanghao11.cn/Article/details/gtxefzuybt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sufxvd.cn/Article/details/gtketbgfwj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ivvv.top/Article/details/gtqvkduaik.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.kuanghao11.cn/Article/details/gtgjusluyq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xinyue.icu/Article/details/gtfrtqfxnh.html

C#:   async Task F() { await G(); }
来源：http://dali.xylfe.cn/Article/details/gtijwzcvev.html

[O05] 并发执行并等待全部完成
来源：http://dali.hysaishi.cn/Article/details/gtjkriutxo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hammf.cn/Article/details/gtwgklmcnn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sweek.top/Article/details/gtheulzvkd.html

JS:   await Promise.all(tasks)
来源：http://dali.zhongyouzk.top/Article/details/gtmkfyrqjp.html

TS:   await Promise.all(tasks)
来源：http://dali.yvedp.cn/Article/details/gtjziuxggd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jiagoushi.top/Article/details/gtxzpqdcjp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nwbrower.top/Article/details/gtxhtrfqkb.html

Ruby: threads.map(&:join)
来源：http://dali.gogol.net.cn/Article/details/gtlpmocjho.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xziqi.cn/Article/details/gtactjmpou.html

[O06] 使用进程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgaennbze.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.bjfxy.top/Article/details/gtrnudsqur.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.316326.xyz/Article/details/gtaykszyce.html

JS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gtoqwxhvwv.html

TS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gtcupbgvqu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hysaishi.cn/Article/details/gtkwygznkb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xuanzx.com/Article/details/gtntnexzio.html

Ruby: // fork 块
来源：http://dali.haohaochexian.top/Article/details/gtjhepczwz.html

C#:   Parallel.For
来源：http://dali.shuidangran.top/Article/details/gtmumrduzb.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtiwoxanjb.html

P. 常用工具函数
来源：http://dali.redwolf501.top/Article/details/gtqeikvbuk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtplsjbhas.html

[P01] 生成 UUID
来源：http://dali.yonumen.top/Article/details/gtlesvcrtt.html

Py:   str(uuid.uuid4())
来源：http://dali.feifeiyinyue.top/Article/details/gtycfkbncv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yvedp.cn/Article/details/gtblkjdczx.html

JS:   crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gtdxdkizxt.html

TS:   crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gtnnqzluce.html

Java: UUID.randomUUID().toString()
来源：http://dali.yonumen.top/Article/details/gtbblahgzp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gtxtzjmoih.html

Ruby: SecureRandom.uuid
来源：http://dali.zhongyouzk.top/Article/details/gtwwsvbjpa.html


<!-- 参考信息 -->