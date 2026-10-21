代发 wailian999

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuetiantiany.cn/Article/details/gtkvtsvcrf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xuetiantiany.cn/Article/details/gtqcmdwstw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.nanxinkj.top/Article/details/gtfglaprbq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwclwupt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpzopdaud.html

[L04] 设置超时
来源：http://dali.0kj1m.cn/Article/details/gtnysgtmtc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.mhx1999.top/Article/details/gttolbmndl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fengsongda.top/Article/details/gtgnlfrkkp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gthhocszec.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jianghu66.top/Article/details/gtedcnzcnm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.haohaochexian.top/Article/details/gtulnzandx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.havefunace.top/Article/details/gtzprjqomk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.guowangkeji.top/Article/details/gtubyevywm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nanxuanxn.top/Article/details/gtfikwbeuy.html

[L05] 上传文件（multipart）
来源：http://dali.yangfankeji.com/Article/details/gtjkiswqdz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ivvv.top/Article/details/gtboxqagaj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.dashuyun.cn/Article/details/gtdxzalkwx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.andypj.xyz/Article/details/gtmsxpfuab.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.dashuyun.cn/Article/details/gtdwgxvvql.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guannengcc.top/Article/details/gtsgqgdmfa.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhengqikj.top/Article/details/gtiaicvyoz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hammf.cn/Article/details/gtawehwclz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtpfdaaonh.html

[L06] 解析响应为 JSON
来源：http://dali.guowangkeji.top/Article/details/gtisdxdcea.html

Py:   resp.json()
来源：http://dali.wangdashe.top/Article/details/gtsblbkgmd.html

PHP:  json_decode($body, true);
来源：http://dali.tanke756.top/Article/details/gttmfnfnfk.html

JS:   await resp.json()
来源：http://dali.aizwys.cn/Article/details/gtqitjjhfj.html

TS:   await resp.json()
来源：http://dali.xylfe.cn/Article/details/gtcspkuxeh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gtkkfhgnjk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxinkj.top/Article/details/gtkpgkqgdj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenzaomai.com/Article/details/gthzbsoqiz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yuxming.cn/Article/details/gtbyuhhnag.html

[L07] 处理 HTTP 状态码
来源：http://dali.xinyue.icu/Article/details/gtbnmcogcc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yueranfly.top/Article/details/gtftxctgcr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gtkqomfxdq.html

JS:   resp.ok;  resp.status
来源：http://dali.kuanghao11.cn/Article/details/gtpgtsfcxc.html

TS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gtcuziltgg.html

Java: resp.statusCode()
来源：http://dali.chenlongwang.top/Article/details/gtzypbktkt.html

Go:   resp.StatusCode
来源：http://dali.shanyushiyangtech.top/Article/details/gtdizsvwke.html

Ruby: resp.code.to_i
来源：http://dali.yj20258.top/Article/details/gtmfrydquq.html

C#:   (int)resp.StatusCode
来源：http://dali.yangfankeji.com/Article/details/gttpilgrou.html

[L08] 并发请求多个地址
来源：http://dali.andypj.xyz/Article/details/gttwtbbrrr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhixingplan.top/Article/details/gthmipixyc.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenjidiqi.icu/Article/details/gtqmyqevis.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gtsoozhlnc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gtgzrppppt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.chenlongwang.top/Article/details/gtvhsabumo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shzxlz.cn/Article/details/gtqbyvatzc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gterhyobje.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ppjwa.cn/Article/details/gtxskwjkpw.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtnslyigfm.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhoulong.xyz/Article/details/gtgjqowjrp.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtquwjuqsf.html

[M01] 读取命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gtzrlgvxjp.html

Py:   sys.argv[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gtyvcdnhkw.html

PHP:  $argv;  $argc;
来源：http://dali.jianghu66.top/Article/details/gtyuztlkaf.html

JS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gthybdijdd.html

TS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gtjfezdbla.html

Java: args 数组（main 方法参数）
来源：http://dali.dashuyun.cn/Article/details/gtnvgjiqcl.html

Go:   os.Args[1:]
来源：http://dali.yueranfly.top/Article/details/gtdqoqosmd.html

Ruby: ARGV
来源：http://dali.nwbrower.top/Article/details/gtcvhifvmd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hongshengwenyu.top/Article/details/gtgdigyqgy.html

[M02] 读取环境变量
来源：http://dali.yuxming.cn/Article/details/gtuzgtwmnc.html

Py:   os.environ.get("HOME")
来源：http://dali.jianghu66.top/Article/details/gtiybzxkfw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.daxiang520.top/Article/details/gtqowfdqxh.html

JS:   process.env.HOME
来源：http://dali.316326.xyz/Article/details/gtqotnrswu.html

TS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gtjmgocpaz.html

Java: System.getenv("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtqbtqbkkf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtwfaoiglg.html

Ruby: ENV["HOME"]
来源：http://dali.ybcxt.top/Article/details/gtxhdtrihr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daria6918.cn/Article/details/gtirzhpjsy.html

[M03] 执行外部命令
来源：http://dali.316326.xyz/Article/details/gtmyctjpbi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hysaishi.cn/Article/details/gtaphyhfvg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj202588.top/Article/details/gtbcanpobw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yanxiufei.cn/Article/details/gtrxdfmobb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yongpay.top/Article/details/gtaxvazxhf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ppjwa.cn/Article/details/gtuwmcblvu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aibaodan.cn/Article/details/gtbjqqwbod.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shuidangran.top/Article/details/gtqwqnbdje.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daxiang520.top/Article/details/gtndgonubw.html

[M04] 获取当前工作目录
来源：http://dali.wangdashe.top/Article/details/gtaptkthbn.html

Py:   os.getcwd()
来源：http://dali.jyoumei.cn/Article/details/gtnrhzmndv.html

PHP:  getcwd();
来源：http://dali.vqdsnc.cn/Article/details/gtnvnkniqk.html

JS:   process.cwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtwcqfrrqy.html

TS:   process.cwd()
来源：http://dali.redwolf501.top/Article/details/gtpxfdyhfp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenzaomai.com/Article/details/gtfqdfsbez.html

Go:   os.Getwd()
来源：http://dali.xinyue.icu/Article/details/gtyexnqbse.html

Ruby: Dir.pwd
来源：http://dali.cashguo.top/Article/details/gtgwjehwrb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hammf.cn/Article/details/gtmzphywhl.html

[M05] 设置退出码
来源：http://dali.xuanzx.com/Article/details/gtnvzqilwf.html

Py:   sys.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtqtdiwmfs.html

PHP:  exit(1);
来源：http://dali.gaohongyu789.top/Article/details/gtijqrpuhr.html

JS:   process.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtkxxylmjt.html

TS:   process.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtovwewcao.html

Java: System.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtchaxnsqb.html

Go:   os.Exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtewdsqavk.html

Ruby: exit 1
来源：http://dali.zhongyouzk.top/Article/details/gtuedfbuij.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj202588.top/Article/details/gtyypqundm.html

[M06] 向标准错误输出
来源：http://dali.zhongyouzk.top/Article/details/gtaewaqiig.html

Py:   print("err", file=sys.stderr)
来源：http://dali.vqdsnc.cn/Article/details/gtfqhxtfpk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj20258888.top/Article/details/gtzumifzti.html

JS:   console.error("err")
来源：http://dali.zhoulong.xyz/Article/details/gtecfxjlmh.html

TS:   console.error("err")
来源：http://dali.xinyue.icu/Article/details/gtcdkqwinz.html

Java: System.err.println("err")
来源：http://dali.meibo888.top/Article/details/gtpvrlwxay.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwlmnxyeo.html

Ruby: warn "err"
来源：http://dali.nwbrower.top/Article/details/gtawffrhru.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj202588.top/Article/details/gtxrksbkqw.html

[M07] 判断是否为主入口
来源：http://dali.daria6918.cn/Article/details/gtfeyjvkyu.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258888.top/Article/details/gtnmujgdlx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnqzz.top/Article/details/gtzlgrtnio.html

JS:   require.main === module
来源：http://dali.jyoumei.cn/Article/details/gtrcvhzyan.html

TS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gtdnfddnkh.html

Java: public static void main(String[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmgckjhbl.html

Go:   func main()
来源：http://dali.0kj1m.cn/Article/details/gthecvzavn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yangfankeji.com/Article/details/gtbgibijsq.html

C#:   static void Main(string[] args)
来源：http://dali.yj20258888.top/Article/details/gtuutfmfpd.html

[M08] 获取系统与运行时信息
来源：http://dali.xuanzx.com/Article/details/gtcvjstxds.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhiwuduotai.top/Article/details/gtxmhxlnzr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.andypj.xyz/Article/details/gtacokscas.html

JS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gtxymsocui.html

TS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gtqxjindpr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.guowangkeji.top/Article/details/gtfmrakpfr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj202588.top/Article/details/gtbqcabasb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.316326.xyz/Article/details/gtspdcefrz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cheryme.top/Article/details/gtnpmrgknm.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtsuudtqxy.html

N. 数据结构与算法
来源：http://dali.gogol.net.cn/Article/details/gtsxrkrfmr.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtmcvjvlqk.html

[N01] 二分查找（有序数组）
来源：http://dali.hammf.cn/Article/details/gtcbrvvnqk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtspoiszjz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.fengsongda.top/Article/details/gtbkthksau.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xinyue.icu/Article/details/gtbpirdawx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnqzz.top/Article/details/gtfszqjaju.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.pycfn.com/Article/details/gttrxulssm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gthswyedrq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenzaomai.com/Article/details/gtrsusgdis.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtproxsmwt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgufenzy.top/Article/details/gtbrkygbjd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfukxfquk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.c1oappe.top/Article/details/gtvheptido.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gttprjoqwo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daxiang520.top/Article/details/gtbrpgklnq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhongyouzk.top/Article/details/gttqvolzdu.html

Go:   slices.Sort(arr)
来源：http://dali.daxiang520.top/Article/details/gtgwvkmnvu.html

Ruby: arr.sort
来源：http://dali.sweek.top/Article/details/gtqclvwjgc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tanke756.top/Article/details/gtsloddmsy.html

[N03] 快速排序（分治示例）
来源：http://dali.cashguo.top/Article/details/gtptbrmnqg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sysykeji.top/Article/details/gtfdrxfppy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cheryme.top/Article/details/gtfbribxia.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.meibo888.top/Article/details/gtunlpztlm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yueranfly.top/Article/details/gtfqcbhbzv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yonumen.top/Article/details/gtceauvqry.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.pycfn.com/Article/details/gtrypsjvgp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ydzc1.top/Article/details/gtpimnhijb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj20258888.top/Article/details/gtpejbzazy.html

[N04] 斐波那契数列
来源：http://dali.yvedp.cn/Article/details/gtyskovmzz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhoulong.xyz/Article/details/gtgsuwbwts.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.dashuyun.cn/Article/details/gtydkkmhop.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gtjnqfkgmd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gtrazjbrrh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gtxtfabfnv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jianghu66.top/Article/details/gthppwdcsq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tianlin.xyz/Article/details/gtjoukqspj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gteknvuagu.html

[N05] 最大公约数
来源：http://dali.aizwys.cn/Article/details/gtezhjfmhc.html

Py:   math.gcd(a, b)
来源：http://dali.cashguo.top/Article/details/gtgliuemyb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.haohaochexian.top/Article/details/gtbsrnjuxy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.mhx1999.top/Article/details/gtatxjzpls.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gttqcqsgmc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shzxlz.cn/Article/details/gtbeswvhev.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zdqjudy.top/Article/details/gtljfdgahq.html

Ruby: a.gcd(b)
来源：http://dali.yanxiufei.cn/Article/details/gtxoiyswav.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.nwbrower.top/Article/details/gtycrsjpqv.html

[N06] 判断回文字符串
来源：http://dali.birdmap.top/Article/details/gttwmabsey.html

Py:   s == s[::-1]
来源：http://dali.xuanzx.com/Article/details/gtxsnxwxyb.html

PHP:  $s === strrev($s);
来源：http://dali.andypj.xyz/Article/details/gtxpxkopxf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtwdpcfbgm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtqxwmjwbp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xylfe.cn/Article/details/gtvksjesab.html

Go:   // 双指针从两端比较
来源：http://dali.cdnleiting.top/Article/details/gturkrfdsd.html

Ruby: s == s.reverse
来源：http://dali.yanxiufei.cn/Article/details/gtdisxbixn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.wangshuangyany.cn/Article/details/gtdtzbzxsa.html

[N07] 两数之和（返回下标）
来源：http://dali.zhiwuduotai.top/Article/details/gtfpdwgvkr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.meibo888.top/Article/details/gtxmakstlf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.wangdashe.top/Article/details/gtrrwaqwss.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jyoumei.cn/Article/details/gtevjwzesy.html

TS:   // 手写 Map<string, number>
来源：http://dali.guannengcc.top/Article/details/gtczoxlfrf.html

Java: // 手写 HashMap
来源：http://dali.yonumen.top/Article/details/gtdeqozfcf.html

Go:   // 手写 map[int]int
来源：http://dali.dashuyun.cn/Article/details/gtcqmlqzmx.html

Ruby: // 手写 Hash
来源：http://dali.ivvv.top/Article/details/gtufvyxmut.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.haohaochexian.top/Article/details/gtwyitxqwf.html

[N08] 生成全排列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfcxmxkmg.html

Py:   itertools.permutations(arr)
来源：http://dali.tianlin.xyz/Article/details/gtmlpgsvqf.html

PHP:  // 手写递归交换
来源：http://dali.cqqwz.cn/Article/details/gtshqxveun.html

JS:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gtmtznfynv.html

TS:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtwchxronh.html

Java: // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtcfdnvvas.html

Go:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtkupfwkor.html

Ruby: arr.permutation.to_a
来源：http://dali.tian-w.cn/Article/details/gtdsqqlbhj.html

C#:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gthpaewhad.html

[N09] 栈与队列
来源：http://dali.nwbrower.top/Article/details/gtqknetiui.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gttqubffdm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gtfydfphqn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvrcxhsku.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.9152youxi.cn/Article/details/gtidvwlpeh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenjidiqi.icu/Article/details/gtjhhulyei.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sweek.top/Article/details/gtmbqrsysy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ydzc1.top/Article/details/gtjzvwcngt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.redwolf501.top/Article/details/gtzqtkcrdx.html

[N10] 链表节点定义
来源：http://dali.kuanghao11.cn/Article/details/gtnbcghlin.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenlongwang.top/Article/details/gtcekvhziw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zdqjudy.top/Article/details/gttfvmuubp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jlsjyb.cn/Article/details/gtjolxtxhl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.aizwys.cn/Article/details/gtkippbatv.html

Java: class Node { int v; Node next; }
来源：http://dali.9152youxi.cn/Article/details/gtkinhhbob.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hongshengwenyu.top/Article/details/gtbudzfqzf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.bjfxy.top/Article/details/gtowvgnxks.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinghuilouyu.cn/Article/details/gttooslujz.html

[N11] 二叉树中序遍历
来源：http://dali.cucudq.cn/Article/details/gtbreuljsi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gogol.net.cn/Article/details/gtavcrjpxx.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gtiadmfkqn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.redwolf501.top/Article/details/gthugzvrtq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.c1oappe.top/Article/details/gtvfvxymzb.html

Java: // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gtxabkklio.html

Go:   // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gtovkidsad.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutqkkozx.html

C#:   // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gtbbangbdr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj202588.top/Article/details/gtufgqcomp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yvedp.cn/Article/details/gtykivlnik.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.andypj.xyz/Article/details/gtflbcjafc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sufxvd.cn/Article/details/gtuewjplqx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhongyouzk.top/Article/details/gtpssbhook.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cheryme.top/Article/details/gtfbrnbmzc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hnqzz.top/Article/details/gtlxzzkhaj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cdnleiting.top/Article/details/gtojyhuxsb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yongpay.top/Article/details/gtnhqzusfs.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtouswsgfk.html

O. 并发与异步
来源：http://dali.hysaishi.cn/Article/details/gtrjxytkwy.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtcfbmptye.html

[O01] 启动一个线程
来源：http://dali.svipenyu.cn/Article/details/gtnminmujy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yangfankeji.com/Article/details/gtgfpjebgp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hysaishi.cn/Article/details/gtxyodqusv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.daria6918.cn/Article/details/gttbtefpcz.html

TS:   // 同 JS
来源：http://dali.sweek.top/Article/details/gtnzfahxlv.html

Java: new Thread(() -> f()).start()
来源：http://dali.jlsjyb.cn/Article/details/gtiuftrlui.html

Go:   go f()
来源：http://dali.0kj1m.cn/Article/details/gtqsattftp.html

Ruby: Thread.new { f }
来源：http://dali.svipenyu.cn/Article/details/gtnazsofua.html

C#:   Task.Run(() => F());
来源：http://dali.xuetiantiany.cn/Article/details/gtmallqtlf.html

[O02] 使用线程池
来源：http://dali.jinqigfzy.top/Article/details/gtkcnoiaqb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hnxiangtu.top/Article/details/gtrzikedsx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinqigfzy.top/Article/details/gttsikhryd.html

JS:   // worker_threads 线程池
来源：http://dali.sxryk.cn/Article/details/gtflcyuiio.html

TS:   // worker_threads 线程池
来源：http://dali.gotoacloud.top/Article/details/gtkeyzhcpr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cashguo.top/Article/details/gtfosaxgwq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shzxlz.cn/Article/details/gtrlepxpyx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jlsjyb.cn/Article/details/gtqkzekkza.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yuxming.cn/Article/details/gtxmlewclt.html

[O03] 加锁保护共享数据
来源：http://dali.cqqwz.cn/Article/details/gtiuecesva.html

Py:   with lock: shared += 1
来源：http://dali.yj20258888.top/Article/details/gtqvkgrjpw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenzaomai.com/Article/details/gtflhaayas.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gaohongyu789.top/Article/details/gtndbavfln.html

TS:   // 同 JS
来源：http://dali.fengsongda.top/Article/details/gtzrryrixo.html

Java: synchronized (this) { shared++; }
来源：http://dali.gzhubu.top/Article/details/gtqecevlpo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xuanzx.com/Article/details/gtixcbamzk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhixingplan.top/Article/details/gtjdsgrcet.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj202588.top/Article/details/gtufzhoawv.html

[O04] 定义异步函数并等待
来源：http://dali.cdnleiting.top/Article/details/gtqabcxzlz.html

Py:   async def f():⏎    await g()
来源：http://dali.ybcxt.top/Article/details/gtenugmeln.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.bjfxy.top/Article/details/gtbnhswaje.html

JS:   async function f() { await g(); }
来源：http://dali.guannengcc.top/Article/details/gthrxeapmc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shzxlz.cn/Article/details/gtbbsclash.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ppjwa.cn/Article/details/gtzrjchnhu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenjidiqi.icu/Article/details/gtflpqrtes.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.daria6918.cn/Article/details/gtqlljoqnd.html

C#:   async Task F() { await G(); }
来源：http://dali.cdnleiting.top/Article/details/gtlukpkhdl.html

[O05] 并发执行并等待全部完成
来源：http://dali.yongpay.top/Article/details/gtlohdrjlx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.chenzaomai.com/Article/details/gtrebtehaq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.svipenyu.cn/Article/details/gtmvwdkqrx.html

JS:   await Promise.all(tasks)
来源：http://dali.hnqzz.top/Article/details/gtdhchcppq.html

TS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gtdjuwwafh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cashguo.top/Article/details/gtybwnzhpz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.fengsongda.top/Article/details/gtmxdvnxkl.html

Ruby: threads.map(&:join)
来源：http://dali.yj20258.top/Article/details/gtzccwaxkd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xuanzx.com/Article/details/gtynarrcki.html

[O06] 使用进程池
来源：http://dali.fzhhl.top/Article/details/gtkgklhksb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ydzc1.top/Article/details/gtutchjntz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtueawviec.html

JS:   // child_process / cluster 模块
来源：http://dali.shuidangran.top/Article/details/gtksybzzfh.html

TS:   // child_process / cluster 模块
来源：http://dali.andypj.xyz/Article/details/gtmzjfsjxz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ppjwa.cn/Article/details/gtuhoncldl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cqqwz.cn/Article/details/gtvshzwqbx.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gtgtknjlhg.html

C#:   Parallel.For
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwcxaaitp.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtbpdjmbgp.html

P. 常用工具函数
来源：http://dali.ivvv.top/Article/details/gttwrwexfi.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtenuytqka.html

[P01] 生成 UUID
来源：http://dali.shuidangran.top/Article/details/gtypdjrjvi.html

Py:   str(uuid.uuid4())
来源：http://dali.zhengqikj.top/Article/details/gtnnexklxs.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.daria6918.cn/Article/details/gtgeldoido.html

JS:   crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gtwhpoozsr.html


<!-- 参考信息 -->