代发 wailian999

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenzaomai.com/Article/details/gtiblhmfjy.html

[L04] 设置超时
来源：http://dali.zdqjudy.top/Article/details/gtherxcqao.html

Py:   requests.get(url, timeout=5)
来源：http://dali.feifeiyinyue.top/Article/details/gtfrwvomkc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxpmvjdzf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xziqi.cn/Article/details/gtyuqhhlwj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guowangkeji.top/Article/details/gtynteyvds.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sufxvd.cn/Article/details/gtnxbhnhhs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.redwolf501.top/Article/details/gtzvcyreii.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.havefunace.top/Article/details/gttqoyepsh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yuanzhike.top/Article/details/gtcazzhfmn.html

[L05] 上传文件（multipart）
来源：http://dali.cdnleiting.top/Article/details/gtvragabuu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhixingplan.top/Article/details/gtoxwgwcyn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sysykeji.top/Article/details/gtrdjavsyv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.fengsongda.top/Article/details/gtxynwpcwu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shzxlz.cn/Article/details/gtuzryckmk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nanxuanxn.top/Article/details/gtlfzvqitf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jianghu66.top/Article/details/gttvdcbpab.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj20258888.top/Article/details/gtqeouiaum.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shuidangran.top/Article/details/gtwcknpujy.html

[L06] 解析响应为 JSON
来源：http://dali.tanke756.top/Article/details/gtstdccvqd.html

Py:   resp.json()
来源：http://dali.gzhubu.top/Article/details/gtftbuynoa.html

PHP:  json_decode($body, true);
来源：http://dali.ivvv.top/Article/details/gtkqwjxqty.html

JS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gtcqniptmb.html

TS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gtepwhbxnp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sxryk.cn/Article/details/gtmtrhnett.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shuidangran.top/Article/details/gtxbfvzwwx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ppjwa.cn/Article/details/gtslcqjorn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hysaishi.cn/Article/details/gtabwuzunw.html

[L07] 处理 HTTP 状态码
来源：http://dali.guannengcc.top/Article/details/gtevjmzdzj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenlongwang.top/Article/details/gtuxdgsfob.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhongyouzk.top/Article/details/gtoqbnvhhg.html

JS:   resp.ok;  resp.status
来源：http://dali.nanxinkj.top/Article/details/gteuhpjtpd.html

TS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gttppvekgm.html

Java: resp.statusCode()
来源：http://dali.sxryk.cn/Article/details/gtrtvhnswl.html

Go:   resp.StatusCode
来源：http://dali.aizwys.cn/Article/details/gtcyxjodxi.html

Ruby: resp.code.to_i
来源：http://dali.cqqwz.cn/Article/details/gtsyqeajql.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gtzqviulcz.html

[L08] 并发请求多个地址
来源：http://dali.yuanzhike.top/Article/details/gtfnvrshkg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nanxinkj.top/Article/details/gtqxopkokf.html

PHP:  curl_multi_init() 系列
来源：http://dali.xuanzx.com/Article/details/gtspsnbctz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gtviesjbcf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gtyftrrply.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yvedp.cn/Article/details/gtdqogkxdk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.kuanghao11.cn/Article/details/gtktyhvnbp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shanyushiyangtech.top/Article/details/gtixlzqjzu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gtsuinsrjz.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtauroogug.html

M. 命令行 / 进程 / 环境
来源：http://dali.cashguo.top/Article/details/gttgbdrhva.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtzlzvyrbc.html

[M01] 读取命令行参数
来源：http://dali.haohaochexian.top/Article/details/gtlxywuwnx.html

Py:   sys.argv[1:]
来源：http://dali.smart0.xyz/Article/details/gtfdrnrddt.html

PHP:  $argv;  $argc;
来源：http://dali.tian-w.cn/Article/details/gtvpynzwrc.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gtzwyyrvop.html

TS:   process.argv.slice(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwoctmhmx.html

Java: args 数组（main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gtifqhjzbw.html

Go:   os.Args[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtklmtqdqa.html

Ruby: ARGV
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfgwhcurd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cqqwz.cn/Article/details/gtijwpuusd.html

[M02] 读取环境变量
来源：http://dali.jqgufenzy.top/Article/details/gtommdfalb.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtcyqeymte.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.daxiang520.top/Article/details/gtepjyltkv.html

JS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gtktheaikh.html

TS:   process.env.HOME
来源：http://dali.cheryme.top/Article/details/gtlvwisuyd.html

Java: System.getenv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtzpitllhq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yueranfly.top/Article/details/gtgntiwutt.html

Ruby: ENV["HOME"]
来源：http://dali.ehwqpu.com/Article/details/gtjncbmzhq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtopylquxb.html

[M03] 执行外部命令
来源：http://dali.meibo888.top/Article/details/gtxazvilas.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nwbrower.top/Article/details/gtareqwafp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gtfkroanae.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.snrcjt.cn/Article/details/gtmagerspx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gtomuxlqpg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yueranfly.top/Article/details/gtdyiooyvs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenzaomai.com/Article/details/gtzdeyvgrm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgfzy.top/Article/details/gtvnfxdweh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.havefunace.top/Article/details/gtnzvwirfu.html

[M04] 获取当前工作目录
来源：http://dali.hongshengwenyu.top/Article/details/gtthvfmczg.html

Py:   os.getcwd()
来源：http://dali.yj20258.top/Article/details/gtgdnlllll.html

PHP:  getcwd();
来源：http://dali.jqgufenzy.top/Article/details/gtnniryxra.html

JS:   process.cwd()
来源：http://dali.iojbl.cn/Article/details/gtkdnxbtcj.html

TS:   process.cwd()
来源：http://dali.xinyue.icu/Article/details/gtsuwubzwy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gaohongyu789.top/Article/details/gtphnhbsqc.html

Go:   os.Getwd()
来源：http://dali.yueranfly.top/Article/details/gtotzbtasf.html

Ruby: Dir.pwd
来源：http://dali.shzxlz.cn/Article/details/gtkuubmohf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.vqdsnc.cn/Article/details/gtcnoepdar.html

[M05] 设置退出码
来源：http://dali.cheryme.top/Article/details/gtubdiavre.html

Py:   sys.exit(1)
来源：http://dali.yonumen.top/Article/details/gtrgfvhgka.html

PHP:  exit(1);
来源：http://dali.ppjwa.cn/Article/details/gtqxduzppp.html

JS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtdjzklwza.html

TS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtcnetyzyv.html

Java: System.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtaookptjw.html

Go:   os.Exit(1)
来源：http://dali.sysykeji.top/Article/details/gtvfgranjp.html

Ruby: exit 1
来源：http://dali.tanke756.top/Article/details/gtvwybcevc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.guannengcc.top/Article/details/gthaumjgud.html

[M06] 向标准错误输出
来源：http://dali.yongpay.top/Article/details/gtnnrcpimk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuetiantiany.cn/Article/details/gttvudskhh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.quarkkingdee.top/Article/details/gtusklqxlt.html

JS:   console.error("err")
来源：http://dali.tian-w.cn/Article/details/gtleywjhsr.html

TS:   console.error("err")
来源：http://dali.shzxlz.cn/Article/details/gtjdkcszgy.html

Java: System.err.println("err")
来源：http://dali.nanxuanxn.top/Article/details/gtcahwmkqr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nwbrower.top/Article/details/gtqxzghhci.html

Ruby: warn "err"
来源：http://dali.cqqwz.cn/Article/details/gtnjblpbzk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.vqdsnc.cn/Article/details/gtlvvmaeec.html

[M07] 判断是否为主入口
来源：http://dali.aizwys.cn/Article/details/gtqexdisbe.html

Py:   if __name__ == "__main__":
来源：http://dali.birdmap.top/Article/details/gtkofcaqxq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sweek.top/Article/details/gtntpknrka.html

JS:   require.main === module
来源：http://dali.yj20258888.top/Article/details/gtldbratva.html

TS:   require.main === module
来源：http://dali.vqdsnc.cn/Article/details/gtupvmcldp.html

Java: public static void main(String[] args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbfnxizcl.html

Go:   func main()
来源：http://dali.cashguo.top/Article/details/gtgdgotitz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.pengpengdd.cyou/Article/details/gtaxznbmso.html

C#:   static void Main(string[] args)
来源：http://dali.hnqzz.top/Article/details/gtvsfkecwt.html

[M08] 获取系统与运行时信息
来源：http://dali.fzhhl.top/Article/details/gtrnpoijjc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jyoumei.cn/Article/details/gtpoyfjwin.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cashguo.top/Article/details/gtawdlwrca.html

JS:   process.platform;  process.version
来源：http://dali.jianghu66.top/Article/details/gtjymfyxbv.html

TS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gtvlnlxnpb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hongshengwenyu.top/Article/details/gtgxgyfuhg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hfpthk.cn/Article/details/gtleselkax.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.kuanghao11.cn/Article/details/gtropobpmk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.daxiang520.top/Article/details/gtkuiunwvx.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtjwlqowfl.html

N. 数据结构与算法
来源：http://dali.sxryk.cn/Article/details/gtwqpauhto.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtjlrwfuag.html

[N01] 二分查找（有序数组）
来源：http://dali.hnqzz.top/Article/details/gtuesswwtj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtatfhlsys.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yvedp.cn/Article/details/gtuuiwgfyc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpvwpclvr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwoqxkdct.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.pycfn.com/Article/details/gtxjmqobje.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtgbqrhhgh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jyoumei.cn/Article/details/gtxsbjqcue.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtjrgyspzi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhiwuduotai.top/Article/details/gturyuxlsi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuanzx.com/Article/details/gtkcidjwxo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjsuvmaur.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gtteczisbw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258888.top/Article/details/gthhtjwdxd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.dianchejie.cn/Article/details/gtoabxoxhw.html

Go:   slices.Sort(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtfesbwyct.html

Ruby: arr.sort
来源：http://dali.fzhhl.top/Article/details/gtgkiuuzkm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.bjfxy.top/Article/details/gtycebjwki.html

[N03] 快速排序（分治示例）
来源：http://dali.wangshuangyany.cn/Article/details/gttapcvvtr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shuidangran.top/Article/details/gtmmpphbcr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.iojbl.cn/Article/details/gtdzlnibqp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aibaodan.cn/Article/details/gtssfewyos.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guowangkeji.top/Article/details/gtmicylhyb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gtridguvao.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zdqjudy.top/Article/details/gtpcuryydn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.iojbl.cn/Article/details/gtbdccmtcs.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhoulong.xyz/Article/details/gtgcixpaty.html

[N04] 斐波那契数列
来源：http://dali.0kj1m.cn/Article/details/gtxsenihun.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtdsdezjeo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.fengsongda.top/Article/details/gtkmneukfd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gtuoofgrpk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gtaqegxalh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gtaiupajyf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hfpthk.cn/Article/details/gtcgnqwjfi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gtocxyvfas.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gtmsfccjjh.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gtkdnuannl.html

Py:   math.gcd(a, b)
来源：http://dali.gzhubu.top/Article/details/gtuutydtud.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xylfe.cn/Article/details/gtzwmqykhb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gtxznliztz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhoulong.xyz/Article/details/gtappwpmpe.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.0kj1m.cn/Article/details/gtfdhadksn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hfpthk.cn/Article/details/gthmfuyykl.html

Ruby: a.gcd(b)
来源：http://dali.xziqi.cn/Article/details/gthgqvobdf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.0kj1m.cn/Article/details/gtojylnlwk.html

[N06] 判断回文字符串
来源：http://dali.jinqigufen.top/Article/details/gtsrxuzesr.html

Py:   s == s[::-1]
来源：http://dali.jqgfzy.top/Article/details/gtrrhkspix.html

PHP:  $s === strrev($s);
来源：http://dali.sysykeji.top/Article/details/gtegnqknrm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtbrerbqlj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gtngmhpcyy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jyoumei.cn/Article/details/gtoxemowim.html

Go:   // 双指针从两端比较
来源：http://dali.sufxvd.cn/Article/details/gtjpzwadif.html

Ruby: s == s.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpcxexzbx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tian-w.cn/Article/details/gtwpnqpxuk.html

[N07] 两数之和（返回下标）
来源：http://dali.cucudq.cn/Article/details/gtbmywoiyv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.9152youxi.cn/Article/details/gtyevwzblh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.svipenyu.cn/Article/details/gtpwioimqu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.guowangkeji.top/Article/details/gtkkyqrwpx.html

TS:   // 手写 Map<string, number>
来源：http://dali.nanxinkj.top/Article/details/gtzkfmmgua.html

Java: // 手写 HashMap
来源：http://dali.cashguo.top/Article/details/gttuvanbni.html

Go:   // 手写 map[int]int
来源：http://dali.smart0.xyz/Article/details/gtmywsuxqx.html

Ruby: // 手写 Hash
来源：http://dali.gaohongyu789.top/Article/details/gtswsagpvm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sweek.top/Article/details/gtcqdqsalb.html

[N08] 生成全排列
来源：http://dali.wangdashe.top/Article/details/gteiypsewz.html

Py:   itertools.permutations(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtwxmdriol.html

PHP:  // 手写递归交换
来源：http://dali.cqqwz.cn/Article/details/gtzjeprmrr.html

JS:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtwgberaba.html

TS:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtcfuhwrcw.html

Java: // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjoaoaux.html

Go:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtlxriojbg.html

Ruby: arr.permutation.to_a
来源：http://dali.nanxuanxn.top/Article/details/gtimvmmnkt.html

C#:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtpcdnbrtf.html

[N09] 栈与队列
来源：http://dali.jlsjyb.cn/Article/details/gtlrxodcxa.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sufxvd.cn/Article/details/gtrgiycxsk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.birdmap.top/Article/details/gtbtmmcpzu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtpnwnjfnh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.aizwys.cn/Article/details/gtxscoygjv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhixingplan.top/Article/details/gtdoqufach.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.haohaochexian.top/Article/details/gtpbldvmat.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtjefycbwd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.andypj.xyz/Article/details/gtmycvkvzu.html

[N10] 链表节点定义
来源：http://dali.zhoulong.xyz/Article/details/gtnmbtxopg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xuetiantiany.cn/Article/details/gtgnrookyu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yongpay.top/Article/details/gtfvvastuw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hfpthk.cn/Article/details/gtvuwnskrp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sweek.top/Article/details/gtouzdirgt.html

Java: class Node { int v; Node next; }
来源：http://dali.yonumen.top/Article/details/gtnkxzttaw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj202588.top/Article/details/gtvalqhvny.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jiagoushi.top/Article/details/gtthhmhfxw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.c1oappe.top/Article/details/gthcbjkgug.html

[N11] 二叉树中序遍历
来源：http://dali.svipenyu.cn/Article/details/gtbghfzcfp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhixingplan.top/Article/details/gtwnerjqux.html

PHP:  // 手写递归函数
来源：http://dali.tanke756.top/Article/details/gtcfosnfaa.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.feifeiyinyue.top/Article/details/gtkvxzodzg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fengsongda.top/Article/details/gtgxxaloki.html

Java: // 手写递归
来源：http://dali.yj202588.top/Article/details/gtacqmqlmm.html

Go:   // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gtjakdoqru.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shzxlz.cn/Article/details/gtjmquibgs.html

C#:   // 手写递归
来源：http://dali.yonumen.top/Article/details/gtwuwwvoso.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jiagoushi.top/Article/details/gtpwpypgpu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jqgufenzy.top/Article/details/gtqdzntqvq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ivvv.top/Article/details/gtpkvjdcxy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gttthecbrc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtldshriuu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gtxjgmbldd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.aizwys.cn/Article/details/gtobvbyjgg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ybcxt.top/Article/details/gtruncippu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.birdmap.top/Article/details/gtibcoayub.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtvbvtnwfc.html

O. 并发与异步
来源：http://dali.zhixingplan.top/Article/details/gtinygqiaj.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtqobhugtz.html

[O01] 启动一个线程
来源：http://dali.zhoulong.xyz/Article/details/gtlejwkgqu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yuanzhike.top/Article/details/gttzbiwuiy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yonumen.top/Article/details/gtsewvddlr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nwbrower.top/Article/details/gtseatcoyg.html

TS:   // 同 JS
来源：http://dali.hongshengwenyu.top/Article/details/gtntdqxpww.html

Java: new Thread(() -> f()).start()
来源：http://dali.chenlongwang.top/Article/details/gticibxxee.html

Go:   go f()
来源：http://dali.pengpengdd.cyou/Article/details/gteptyqzia.html

Ruby: Thread.new { f }
来源：http://dali.nwbrower.top/Article/details/gtvltycgck.html

C#:   Task.Run(() => F());
来源：http://dali.hywenlv.cn/Article/details/gtykdrxfwg.html

[O02] 使用线程池
来源：http://dali.tanke756.top/Article/details/gtcddbomtg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shzxlz.cn/Article/details/gtrfpiwifp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangdashe.top/Article/details/gtxdkbiucj.html

JS:   // worker_threads 线程池
来源：http://dali.hysaishi.cn/Article/details/gtredkdyyx.html

TS:   // worker_threads 线程池
来源：http://dali.yangfankeji.com/Article/details/gtlqzzfyfb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gzhubu.top/Article/details/gtvwknikdz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.aizwys.cn/Article/details/gtqieljjov.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.bjfxy.top/Article/details/gtuuqhtuqd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.guannengcc.top/Article/details/gttvrqmuue.html

[O03] 加锁保护共享数据
来源：http://dali.jqgfzy.top/Article/details/gtjiuyvkaa.html

Py:   with lock: shared += 1
来源：http://dali.zdqjudy.top/Article/details/gteidipaue.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.pycfn.com/Article/details/gtalmakbon.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.meibo888.top/Article/details/gtdbudxfot.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gtovhtefhg.html

Java: synchronized (this) { shared++; }
来源：http://dali.yanxiufei.cn/Article/details/gtbwvagjug.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zycfv.cn/Article/details/gtfrfyhnsz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yuxming.cn/Article/details/gtsqimuksn.html

C#:   lock (gate) { shared++; }
来源：http://dali.vqdsnc.cn/Article/details/gtzejdplvl.html

[O04] 定义异步函数并等待
来源：http://dali.c1oappe.top/Article/details/gtvnkudxuh.html

Py:   async def f():⏎    await g()
来源：http://dali.mhx1999.top/Article/details/gttfyhbxah.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tianlin.xyz/Article/details/gtlhpnvhel.html

JS:   async function f() { await g(); }
来源：http://dali.yangfankeji.com/Article/details/gtmplgfeje.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gttydmomht.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sufxvd.cn/Article/details/gtxbugzjle.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.vqdsnc.cn/Article/details/gtcapkvxge.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hongshengwenyu.top/Article/details/gtdsrfzorp.html

C#:   async Task F() { await G(); }
来源：http://dali.zhengqikj.top/Article/details/gtfkendbli.html

[O05] 并发执行并等待全部完成
来源：http://dali.shzxlz.cn/Article/details/gttbpylplh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xinyue.icu/Article/details/gtyrhzbcvo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yanxiufei.cn/Article/details/gttwjoxtys.html

JS:   await Promise.all(tasks)
来源：http://dali.zdqjudy.top/Article/details/gttkkiwvxd.html

TS:   await Promise.all(tasks)
来源：http://dali.yuanzhike.top/Article/details/gtgpqpatsr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nanxinkj.top/Article/details/gtaztqccou.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.daxiang520.top/Article/details/gtegahcfdi.html

Ruby: threads.map(&:join)
来源：http://dali.sysykeji.top/Article/details/gtyxbipiiz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xuetiantiany.cn/Article/details/gtgeosemtp.html

[O06] 使用进程池
来源：http://dali.cqqwz.cn/Article/details/gttexnrpus.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gotoacloud.top/Article/details/gtbdgjkgkh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hnqzz.top/Article/details/gtixjcyfzb.html

JS:   // child_process / cluster 模块
来源：http://dali.feifeiyinyue.top/Article/details/gtfmjlyxln.html

TS:   // child_process / cluster 模块
来源：http://dali.yj20258.top/Article/details/gtfpucipox.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jyoumei.cn/Article/details/gtrgnipsfx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sweek.top/Article/details/gtshxnjetu.html

Ruby: // fork 块
来源：http://dali.guowangkeji.top/Article/details/gtugjvednm.html

C#:   Parallel.For
来源：http://dali.nanxuanxn.top/Article/details/gtqcdqwlnj.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtjfinsbph.html

P. 常用工具函数
来源：http://dali.chenzaomai.com/Article/details/gtxhkycraa.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gttivuyamo.html

[P01] 生成 UUID
来源：http://dali.jianghu66.top/Article/details/gtxudwgquu.html

Py:   str(uuid.uuid4())
来源：http://dali.aizwys.cn/Article/details/gtbfyxcryi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zdqjudy.top/Article/details/gtegfzsmjk.html

JS:   crypto.randomUUID()
来源：http://dali.dashuyun.cn/Article/details/gtnffoafiy.html

TS:   crypto.randomUUID()
来源：http://dali.redwolf501.top/Article/details/gtclzikwzo.html

Java: UUID.randomUUID().toString()
来源：http://dali.dianchejie.cn/Article/details/gtydhjrhbx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxozbnbw.html

Ruby: SecureRandom.uuid
来源：http://dali.ybcxt.top/Article/details/gtudbvhplq.html


<!-- 参考信息 -->