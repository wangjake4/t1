代发 wailian999

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jyoumei.cn/Article/details/gt2jbzyiynm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.meibo888.top/Article/details/gt2ipsrkfvn.html

[L05] 上传文件（multipart）
来源：http://dali.gzhubu.top/Article/details/gt2tuuorrcz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.svipenyu.cn/Article/details/gt2cpqccajg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cheryme.top/Article/details/gt2rivobmkt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gt2uzxeliwf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hxoglhiu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cdnleiting.top/Article/details/gt2jejibnfr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hfpthk.cn/Article/details/gt2jwldagud.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.aibaodan.cn/Article/details/gt2fcuzesyi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2weergrbf.html

[L06] 解析响应为 JSON
来源：http://dali.fengsongda.top/Article/details/gt2hfwjcxrl.html

Py:   resp.json()
来源：http://dali.jiagoushi.top/Article/details/gt2npzvenkg.html

PHP:  json_decode($body, true);
来源：http://dali.zhixingplan.top/Article/details/gt2fuqaskly.html

JS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gt2baxvcuwa.html

TS:   await resp.json()
来源：http://dali.yj202588.top/Article/details/gt2famgqcup.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bmbnolyd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cdnleiting.top/Article/details/gt2eksedihr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.aizwys.cn/Article/details/gt2zwysgeln.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj20258888.top/Article/details/gt2kohpiwzt.html

[L07] 处理 HTTP 状态码
来源：http://dali.nanxinkj.top/Article/details/gt2zyckhnqs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2izglelyx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj20258.top/Article/details/gt2oqfsxofx.html

JS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gt2fwofhlhy.html

TS:   resp.ok;  resp.status
来源：http://dali.xuanzx.com/Article/details/gt2sypbfnfa.html

Java: resp.statusCode()
来源：http://dali.gaohongyu789.top/Article/details/gt2ngbwbung.html

Go:   resp.StatusCode
来源：http://dali.sufxvd.cn/Article/details/gt2lutzmowk.html

Ruby: resp.code.to_i
来源：http://dali.yj20258.top/Article/details/gt2rduaejbo.html

C#:   (int)resp.StatusCode
来源：http://dali.yj20258.top/Article/details/gt2suvfmdxq.html

[L08] 并发请求多个地址
来源：http://dali.shangyingyoupin.top/Article/details/gt2lcsdzhue.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nanxinkj.top/Article/details/gt2rklxmuet.html

PHP:  curl_multi_init() 系列
来源：http://dali.jiagoushi.top/Article/details/gt2yivpjmhj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gt2iniwtqbi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gt2hfcmlzol.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsuybev.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.redwolf501.top/Article/details/gt2layocqec.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj202588.top/Article/details/gt2vwwioabq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhoulong.xyz/Article/details/gt2rcaiiulw.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2hfewxeil.html

M. 命令行 / 进程 / 环境
来源：http://dali.hnxiangtu.top/Article/details/gt2mvyfdrnt.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2tjniddpf.html

[M01] 读取命令行参数
来源：http://dali.redwolf501.top/Article/details/gt2khyyvzvp.html

Py:   sys.argv[1:]
来源：http://dali.daxiang520.top/Article/details/gt2upamvqdm.html

PHP:  $argv;  $argc;
来源：http://dali.zhoulong.xyz/Article/details/gt2xvatgfaz.html

JS:   process.argv.slice(2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ltppuwav.html

TS:   process.argv.slice(2)
来源：http://dali.daria6918.cn/Article/details/gt2nmpoqgef.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258.top/Article/details/gt2uqmqjvip.html

Go:   os.Args[1:]
来源：http://dali.vqdsnc.cn/Article/details/gt2ivalejug.html

Ruby: ARGV
来源：http://dali.xuetiantiany.cn/Article/details/gt2vgowibzi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenjidiqi.icu/Article/details/gt2dtpaqoxe.html

[M02] 读取环境变量
来源：http://dali.c1oappe.top/Article/details/gt2boaizpnn.html

Py:   os.environ.get("HOME")
来源：http://dali.pycfn.com/Article/details/gt2ytsktmxg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.snrcjt.cn/Article/details/gt2lhqjgmzt.html

JS:   process.env.HOME
来源：http://dali.yueranfly.top/Article/details/gt2jlnpjucp.html

TS:   process.env.HOME
来源：http://dali.zhixingplan.top/Article/details/gt2pxypiwwz.html

Java: System.getenv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gt2muvzbagz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.c1oappe.top/Article/details/gt2bupxvzxt.html

Ruby: ENV["HOME"]
来源：http://dali.shuidangran.top/Article/details/gt2yheeqdac.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gzhubu.top/Article/details/gt2mcytqjqa.html

[M03] 执行外部命令
来源：http://dali.dashuyun.cn/Article/details/gt2nvyvrnvr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bypgfsgs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yueranfly.top/Article/details/gt2otksvpjf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ehwqpu.com/Article/details/gt2ugcbgjuc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.svipenyu.cn/Article/details/gt2xjrzwexo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgfzy.top/Article/details/gt2elbnwaht.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.havefunace.top/Article/details/gt2efwvseec.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.feifeiyinyue.top/Article/details/gt2dhmencpy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xinyue.icu/Article/details/gt2fhonmohd.html

[M04] 获取当前工作目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bnfojmet.html

Py:   os.getcwd()
来源：http://dali.guannengcc.top/Article/details/gt2mkuodbkm.html

PHP:  getcwd();
来源：http://dali.zhoulong.xyz/Article/details/gt2canuitee.html

JS:   process.cwd()
来源：http://dali.yj202588.top/Article/details/gt2gkbtqwpl.html

TS:   process.cwd()
来源：http://dali.9152youxi.cn/Article/details/gt2gxkokfmk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.meibo888.top/Article/details/gt2eonawyka.html

Go:   os.Getwd()
来源：http://dali.0kj1m.cn/Article/details/gt2uyegqobv.html

Ruby: Dir.pwd
来源：http://dali.zycfv.cn/Article/details/gt2tumtzvoc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jqgfzy.top/Article/details/gt2caegeenv.html

[M05] 设置退出码
来源：http://dali.gzhubu.top/Article/details/gt2zxrifled.html

Py:   sys.exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2eycfbwra.html

PHP:  exit(1);
来源：http://dali.yanxiufei.cn/Article/details/gt2roumgshh.html

JS:   process.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2avjmfnsp.html

TS:   process.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gt2vzoaawmd.html

Java: System.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dooszqvc.html

Go:   os.Exit(1)
来源：http://dali.sxryk.cn/Article/details/gt2ljigqkjz.html

Ruby: exit 1
来源：http://dali.xuanzx.com/Article/details/gt2nxnwwpfi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nwbrower.top/Article/details/gt2tqgatrxy.html

[M06] 向标准错误输出
来源：http://dali.nwbrower.top/Article/details/gt2meeoaeuc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.guannengcc.top/Article/details/gt2xnzeaphg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sdadlhlg.html

JS:   console.error("err")
来源：http://dali.xinyue.icu/Article/details/gt2nkatoysd.html

TS:   console.error("err")
来源：http://dali.pengpengdd.cyou/Article/details/gt2avipfrrk.html

Java: System.err.println("err")
来源：http://dali.9152youxi.cn/Article/details/gt2dshxdhxb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ulmgycwm.html

Ruby: warn "err"
来源：http://dali.guannengcc.top/Article/details/gt2goxffhvx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2luylympq.html

[M07] 判断是否为主入口
来源：http://dali.havefunace.top/Article/details/gt2pogxtymu.html

Py:   if __name__ == "__main__":
来源：http://dali.dashuyun.cn/Article/details/gt2piygopef.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.fzhhl.top/Article/details/gt2oltcfhrz.html

JS:   require.main === module
来源：http://dali.316326.xyz/Article/details/gt2qbdwyprh.html

TS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gt2oidsxlga.html

Java: public static void main(String[] args)
来源：http://dali.shuidangran.top/Article/details/gt2iwgqypcm.html

Go:   func main()
来源：http://dali.tanke756.top/Article/details/gt2hukjmcfd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cheryme.top/Article/details/gt2ynpbthzf.html

C#:   static void Main(string[] args)
来源：http://dali.gaohongyu789.top/Article/details/gt2kdxbliop.html

[M08] 获取系统与运行时信息
来源：http://dali.zhongyouzk.top/Article/details/gt2tiikrszl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sxryk.cn/Article/details/gt2hmxvoznf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.iojbl.cn/Article/details/gt2pcstsgty.html

JS:   process.platform;  process.version
来源：http://dali.sweek.top/Article/details/gt2umupggyg.html

TS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gt2rpladvei.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.c1oappe.top/Article/details/gt2vfyaqueq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yvedp.cn/Article/details/gt2kaozqvgh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xinyue.icu/Article/details/gt2zdeksiyv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xylfe.cn/Article/details/gt2btlmsnpw.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2mhtvvpch.html

N. 数据结构与算法
来源：http://dali.andypj.xyz/Article/details/gt2lcjyzyib.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2ensoumbg.html

[N01] 二分查找（有序数组）
来源：http://dali.sysykeji.top/Article/details/gt2vtdppswc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cashguo.top/Article/details/gt2ucwtgztr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gogol.net.cn/Article/details/gt2qpgiuitj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tdkvnhce.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hammf.cn/Article/details/gt2xsqifwog.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2clewewdj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2snhwjzxp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yuxming.cn/Article/details/gt2ktvfpuoa.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lzwaptqc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnqzz.top/Article/details/gt2rbfoxjfj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yvedp.cn/Article/details/gt2vsjmopvw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gt2dmnpnvjc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gt2enipjeep.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gt2pviabhpm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hammf.cn/Article/details/gt2ejldrmxs.html

Go:   slices.Sort(arr)
来源：http://dali.guannengcc.top/Article/details/gt2vpfwiyfh.html

Ruby: arr.sort
来源：http://dali.redwolf501.top/Article/details/gt2zkdafhaf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jlsjyb.cn/Article/details/gt2mogzoeoq.html

[N03] 快速排序（分治示例）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zilklsqw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hnqzz.top/Article/details/gt2alntsxcm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tianlin.xyz/Article/details/gt2ixlgzwxa.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sufxvd.cn/Article/details/gt2qubetdgl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhoulong.xyz/Article/details/gt2premruwc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hywenlv.cn/Article/details/gt2ueyaddub.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhongyouzk.top/Article/details/gt2pfarabyr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hongshengwenyu.top/Article/details/gt2zyttimei.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.dashuyun.cn/Article/details/gt2nlgtstmx.html

[N04] 斐波那契数列
来源：http://dali.yangfankeji.com/Article/details/gt2eehgjfzk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ybcxt.top/Article/details/gt2duiqwbfm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinqigfzy.top/Article/details/gt2wfgmfwxw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gt2aaetoobk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gt2cqhcjgbv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cheryme.top/Article/details/gt2yledcryv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ppjwa.cn/Article/details/gt2zwrjrole.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hysaishi.cn/Article/details/gt2uenkgdau.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rgcxsedu.html

[N05] 最大公约数
来源：http://dali.sweek.top/Article/details/gt2zrvpshra.html

Py:   math.gcd(a, b)
来源：http://dali.dashuyun.cn/Article/details/gt2sqdhssrw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.bjfxy.top/Article/details/gt2wptjuioz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tanke756.top/Article/details/gt2nszgtrrt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sufxvd.cn/Article/details/gt2czjsgcns.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.0kj1m.cn/Article/details/gt2opcspfzc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jianghu66.top/Article/details/gt2vdsujjnm.html

Ruby: a.gcd(b)
来源：http://dali.yj20258888.top/Article/details/gt2lrjgjzxn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.havefunace.top/Article/details/gt2xyjngwtu.html

[N06] 判断回文字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2vjmbrwav.html

Py:   s == s[::-1]
来源：http://dali.hnxiangtu.top/Article/details/gt2sqbryvsa.html

PHP:  $s === strrev($s);
来源：http://dali.jqgfzy.top/Article/details/gt2naitqanm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gt2vvvykzxi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gt2tcxqqdrd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.meibo888.top/Article/details/gt2sbgvevpk.html

Go:   // 双指针从两端比较
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sdhrvmqd.html

Ruby: s == s.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gt2hjynlyge.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yonumen.top/Article/details/gt2sktslbcq.html

[N07] 两数之和（返回下标）
来源：http://dali.shzxlz.cn/Article/details/gt2rrghjbge.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tianlin.xyz/Article/details/gt2xqtvylxx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.redwolf501.top/Article/details/gt2ocznpkje.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sxryk.cn/Article/details/gt2eqpwiqrr.html

TS:   // 手写 Map<string, number>
来源：http://dali.cqqwz.cn/Article/details/gt2gayoqosl.html

Java: // 手写 HashMap
来源：http://dali.cucudq.cn/Article/details/gt2mnflmxhf.html

Go:   // 手写 map[int]int
来源：http://dali.haohaochexian.top/Article/details/gt2etrznark.html

Ruby: // 手写 Hash
来源：http://dali.aibaodan.cn/Article/details/gt2ifaavhsy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sufxvd.cn/Article/details/gt2ivnsshcj.html

[N08] 生成全排列
来源：http://dali.zhoulong.xyz/Article/details/gt2uyzlwlhi.html

Py:   itertools.permutations(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2wlmrlrbf.html

PHP:  // 手写递归交换
来源：http://dali.fzhhl.top/Article/details/gt2umkxvbqc.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlhchsk.html

TS:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gt2hkzljzcz.html

Java: // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gt2atqvuvwa.html

Go:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gt2snscsnvh.html

Ruby: arr.permutation.to_a
来源：http://dali.quarkkingdee.top/Article/details/gt2cheosbil.html

C#:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gt2owivnngh.html

[N09] 栈与队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2krvvheea.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj202588.top/Article/details/gt2wdttgapi.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sxryk.cn/Article/details/gt2fhdyczjs.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gt2rtudnrbl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.fengsongda.top/Article/details/gt2facqsqoy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.bjfxy.top/Article/details/gt2qcrrydce.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.daria6918.cn/Article/details/gt2hgpyhecq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.daria6918.cn/Article/details/gt2dquouhmm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nanxinkj.top/Article/details/gt2eqeqbyhl.html

[N10] 链表节点定义
来源：http://dali.gaohongyu789.top/Article/details/gt2xtqekhna.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xylfe.cn/Article/details/gt2dzqfmzmc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hammf.cn/Article/details/gt2acmheyrh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.birdmap.top/Article/details/gt2jnbtgufi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.havefunace.top/Article/details/gt2zeqcceml.html

Java: class Node { int v; Node next; }
来源：http://dali.yuanzhike.top/Article/details/gt2ymmzgrxw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.havefunace.top/Article/details/gt2rzrtrfbx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenzaomai.com/Article/details/gt2djmxgyeh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.smart0.xyz/Article/details/gt2botmxfbo.html

[N11] 二叉树中序遍历
来源：http://dali.cdnleiting.top/Article/details/gt2igxqlcka.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ydzc1.top/Article/details/gt2cetdevla.html

PHP:  // 手写递归函数
来源：http://dali.9152youxi.cn/Article/details/gt2ohkgwkls.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxinkj.top/Article/details/gt2irjuaogl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ybcxt.top/Article/details/gt2yxtdysrb.html

Java: // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xvtemzra.html

Go:   // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gt2exaudchs.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cucudq.cn/Article/details/gt2hputlfai.html

C#:   // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2ttgngrvo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sufxvd.cn/Article/details/gt2gilzpegj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dzmvemhh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yonumen.top/Article/details/gt2wkbipidy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gt2oiimnnfz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gt2lkmbfpve.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuxming.cn/Article/details/gt2mylkdtcf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.svipenyu.cn/Article/details/gt2oeffuhtl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.haohaochexian.top/Article/details/gt2fcmxpsim.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gt2zotohsew.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2hjsfjvcs.html

O. 并发与异步
来源：http://dali.sufxvd.cn/Article/details/gt2nuazuvuc.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2ulevextm.html

[O01] 启动一个线程
来源：http://dali.ppjwa.cn/Article/details/gt2wrfpxmjj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zdqjudy.top/Article/details/gt2meutcwua.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.daxiang520.top/Article/details/gt2iascfinu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.kuanghao11.cn/Article/details/gt2zhoerota.html

TS:   // 同 JS
来源：http://dali.yuanzhike.top/Article/details/gt2zjsensmd.html

Java: new Thread(() -> f()).start()
来源：http://dali.hammf.cn/Article/details/gt2sgyixrxz.html

Go:   go f()
来源：http://dali.nanxinkj.top/Article/details/gt2zmbtntdo.html

Ruby: Thread.new { f }
来源：http://dali.yuanzhike.top/Article/details/gt2yelmarwz.html

C#:   Task.Run(() => F());
来源：http://dali.nwbrower.top/Article/details/gt2ekdtjpar.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdkokue.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhoulong.xyz/Article/details/gt2ekgqcgui.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xinyue.icu/Article/details/gt2peowroea.html

JS:   // worker_threads 线程池
来源：http://dali.yj20258.top/Article/details/gt2kjdecukf.html

TS:   // worker_threads 线程池
来源：http://dali.jinqigufen.top/Article/details/gt2irvemvyn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.wangdashe.top/Article/details/gt2ehhycvgh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aikccblj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cashguo.top/Article/details/gt2mxqeoble.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.0kj1m.cn/Article/details/gt2twafwkts.html

[O03] 加锁保护共享数据
来源：http://dali.zhongyouzk.top/Article/details/gt2hdbvokzu.html

Py:   with lock: shared += 1
来源：http://dali.ppjwa.cn/Article/details/gt2wvrflvyp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.nanxuanxn.top/Article/details/gt2iaamthua.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tian-w.cn/Article/details/gt2frglavyl.html

TS:   // 同 JS
来源：http://dali.smart0.xyz/Article/details/gt2yynwmamd.html

Java: synchronized (this) { shared++; }
来源：http://dali.c1oappe.top/Article/details/gt2xubjaixd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhixingplan.top/Article/details/gt2pwjvzbnc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhongyouzk.top/Article/details/gt2qdyjjroc.html

C#:   lock (gate) { shared++; }
来源：http://dali.meibo888.top/Article/details/gt2knvtdkla.html

[O04] 定义异步函数并等待
来源：http://dali.cqqwz.cn/Article/details/gt2hpcnefyd.html

Py:   async def f():⏎    await g()
来源：http://dali.chenzaomai.com/Article/details/gt2htliqspw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ybcxt.top/Article/details/gt2ojuskzwo.html

JS:   async function f() { await g(); }
来源：http://dali.tianlin.xyz/Article/details/gt2tkbrnnij.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.c1oappe.top/Article/details/gt2jbyayixe.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.birdmap.top/Article/details/gt2wlbrkhxg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.daria6918.cn/Article/details/gt2bkhrvgzi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fxvfqjdz.html

C#:   async Task F() { await G(); }
来源：http://dali.0kj1m.cn/Article/details/gt2gxdjlmte.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj202588.top/Article/details/gt2etznfbwp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.redwolf501.top/Article/details/gt2qokfdwok.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nwbrower.top/Article/details/gt2sibxsqkv.html

JS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gt2naftvfnb.html

TS:   await Promise.all(tasks)
来源：http://dali.daria6918.cn/Article/details/gt2qbjempbc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ppjwa.cn/Article/details/gt2lgytkrgc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jqgfzy.top/Article/details/gt2cvfucvgi.html

Ruby: threads.map(&:join)
来源：http://dali.mhx1999.top/Article/details/gt2erpbqcjq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gotoacloud.top/Article/details/gt2lezujhhj.html

[O06] 使用进程池
来源：http://dali.ydzc1.top/Article/details/gt2etoubyap.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.wangdashe.top/Article/details/gt2cpbdjwed.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cheryme.top/Article/details/gt2humuwvsh.html

JS:   // child_process / cluster 模块
来源：http://dali.bjfxy.top/Article/details/gt2kjnwpckt.html

TS:   // child_process / cluster 模块
来源：http://dali.daria6918.cn/Article/details/gt2rhqhjfnk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sysykeji.top/Article/details/gt2zejdchix.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.fengsongda.top/Article/details/gt2otwardbh.html

Ruby: // fork 块
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fzrcellp.html

C#:   Parallel.For
来源：http://dali.pengpengdd.cyou/Article/details/gt2jgzbryfv.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2vbhgwtau.html

P. 常用工具函数
来源：http://dali.shzxlz.cn/Article/details/gt2kxeoyrhs.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2icojhkme.html

[P01] 生成 UUID
来源：http://dali.yonumen.top/Article/details/gt2egylrmod.html

Py:   str(uuid.uuid4())
来源：http://dali.kuanghao11.cn/Article/details/gt2nrcekuen.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jyoumei.cn/Article/details/gt2tofghodk.html

JS:   crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gt2eggyzykz.html

TS:   crypto.randomUUID()
来源：http://dali.tianlin.xyz/Article/details/gt2bywbobdk.html

Java: UUID.randomUUID().toString()
来源：http://dali.hnqzz.top/Article/details/gt2lwlyhhdx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhixingplan.top/Article/details/gt2vvrjvnue.html

Ruby: SecureRandom.uuid
来源：http://dali.hongshengwenyu.top/Article/details/gt2zcolxzmd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.c1oappe.top/Article/details/gt2fusexjlr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhiwuduotai.top/Article/details/gt2diajfgzl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sweek.top/Article/details/gt2xhpxdoaq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.smart0.xyz/Article/details/gt2hgnfkyln.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hfpthk.cn/Article/details/gt2owqlqjzr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shzxlz.cn/Article/details/gt2lmfvoooh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tanke756.top/Article/details/gt2hmkdcwyj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenjidiqi.icu/Article/details/gt2eanbtsbz.html


<!-- 参考信息 -->