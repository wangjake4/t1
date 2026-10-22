代发 wailian999

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aibaodan.cn/Article/details/gtqmefdgjt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.fengsongda.top/Article/details/gthpqonekl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.wangshuangyany.cn/Article/details/gtehnxgwpc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.vqdsnc.cn/Article/details/gtmifzharm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ydzc1.top/Article/details/gtggjmtgij.html

[L04] 设置超时
来源：http://dali.zdqjudy.top/Article/details/gtlgklfqpe.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hammf.cn/Article/details/gtzqitozpk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gtlamgxfbk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ehwqpu.com/Article/details/gtjneoiwuj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guowangkeji.top/Article/details/gtkfqjpmtk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.pengpengdd.cyou/Article/details/gtgtvgpuny.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hammf.cn/Article/details/gtiubzxgmx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jianghu66.top/Article/details/gtcexeojcy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yuanzhike.top/Article/details/gtpmaeeohv.html

[L05] 上传文件（multipart）
来源：http://dali.jiagoushi.top/Article/details/gtcahuladz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.andypj.xyz/Article/details/gthnyvsbff.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.dianchejie.cn/Article/details/gtqccjwxnu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gtepxunqnw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.daria6918.cn/Article/details/gtiwukckgg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gotoacloud.top/Article/details/gtycfigukk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hnxiangtu.top/Article/details/gtcttbxudq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenjidiqi.icu/Article/details/gtyvoeldyd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtvkksktzj.html

[L06] 解析响应为 JSON
来源：http://dali.nanxinkj.top/Article/details/gtdrsrvcvl.html

Py:   resp.json()
来源：http://dali.guannengcc.top/Article/details/gtndnhpwcf.html

PHP:  json_decode($body, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxctbvxu.html

JS:   await resp.json()
来源：http://dali.svipenyu.cn/Article/details/gttjuphrxp.html

TS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gtneficxwb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gtniafbvpp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guannengcc.top/Article/details/gtosrirpti.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yvedp.cn/Article/details/gtwcwtjnip.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xziqi.cn/Article/details/gtapjjfumt.html

[L07] 处理 HTTP 状态码
来源：http://dali.sysykeji.top/Article/details/gtwbakgrjf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhongyouzk.top/Article/details/gtihjzirji.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj20258888.top/Article/details/gtglmgegll.html

JS:   resp.ok;  resp.status
来源：http://dali.jlsjyb.cn/Article/details/gtarntjfyl.html

TS:   resp.ok;  resp.status
来源：http://dali.xinyue.icu/Article/details/gtclgyxdfo.html

Java: resp.statusCode()
来源：http://dali.haohaochexian.top/Article/details/gtfkyicwxx.html

Go:   resp.StatusCode
来源：http://dali.sweek.top/Article/details/gtshtralzg.html

Ruby: resp.code.to_i
来源：http://dali.xuanzx.com/Article/details/gtlloezvfb.html

C#:   (int)resp.StatusCode
来源：http://dali.cheryme.top/Article/details/gtdixtpgbu.html

[L08] 并发请求多个地址
来源：http://dali.chenzaomai.com/Article/details/gtctienadh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yongpay.top/Article/details/gtlyzarszo.html

PHP:  curl_multi_init() 系列
来源：http://dali.gzhubu.top/Article/details/gtlehsnxxy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gtlmysqyex.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gthpgschkf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shuidangran.top/Article/details/gtjopqlhya.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shuidangran.top/Article/details/gtggdhxoxu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gtmyqpagkc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.guowangkeji.top/Article/details/gtuahclimx.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtwwmtefpv.html

M. 命令行 / 进程 / 环境
来源：http://dali.xuetiantiany.cn/Article/details/gtfrnkrcje.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gttqasicwp.html

[M01] 读取命令行参数
来源：http://dali.nanxuanxn.top/Article/details/gtgtqmvmte.html

Py:   sys.argv[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtwagjeijg.html

PHP:  $argv;  $argc;
来源：http://dali.hfpthk.cn/Article/details/gtdfnqkegr.html

JS:   process.argv.slice(2)
来源：http://dali.birdmap.top/Article/details/gtggcvtbmk.html

TS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gttnfqhknd.html

Java: args 数组（main 方法参数）
来源：http://dali.yonumen.top/Article/details/gtoqufxnii.html

Go:   os.Args[1:]
来源：http://dali.hysaishi.cn/Article/details/gtzqwkjaie.html

Ruby: ARGV
来源：http://dali.pengpengdd.cyou/Article/details/gtiviycdmr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hfpthk.cn/Article/details/gtifztgwri.html

[M02] 读取环境变量
来源：http://dali.c1oappe.top/Article/details/gtfstpswys.html

Py:   os.environ.get("HOME")
来源：http://dali.smart0.xyz/Article/details/gtkekjpfms.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shanyushiyangtech.top/Article/details/gtedhurooo.html

JS:   process.env.HOME
来源：http://dali.jyoumei.cn/Article/details/gtzscvqswq.html

TS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdffzjphc.html

Java: System.getenv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtisxuhekd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.redwolf501.top/Article/details/gtuxbyffsn.html

Ruby: ENV["HOME"]
来源：http://dali.gogol.net.cn/Article/details/gtptyykfiq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtvuvblvem.html

[M03] 执行外部命令
来源：http://dali.ppjwa.cn/Article/details/gtcsjuqqjk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcuypfrhs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.c1oappe.top/Article/details/gtffuovbgo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.kuanghao11.cn/Article/details/gtklupjunw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhiwuduotai.top/Article/details/gtgmnwsfve.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhengqikj.top/Article/details/gtdfwiodpm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shuidangran.top/Article/details/gttarvamfo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hongshengwenyu.top/Article/details/gtfxsxnryo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhoulong.xyz/Article/details/gthpetqmqj.html

[M04] 获取当前工作目录
来源：http://dali.havefunace.top/Article/details/gtoikafhaa.html

Py:   os.getcwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtubbkbski.html

PHP:  getcwd();
来源：http://dali.yonumen.top/Article/details/gtartdtwhy.html

JS:   process.cwd()
来源：http://dali.cashguo.top/Article/details/gttewrwhkh.html

TS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtripthhcn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.c1oappe.top/Article/details/gtrfqvorao.html

Go:   os.Getwd()
来源：http://dali.nanxinkj.top/Article/details/gtcgfbtkke.html

Ruby: Dir.pwd
来源：http://dali.yj202588.top/Article/details/gtfnsscjis.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shuidangran.top/Article/details/gtidpkxsgt.html

[M05] 设置退出码
来源：http://dali.vqdsnc.cn/Article/details/gtwblhjobt.html

Py:   sys.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtlmojfdfk.html

PHP:  exit(1);
来源：http://dali.dianchejie.cn/Article/details/gtzpfqeiez.html

JS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gtqloduoio.html

TS:   process.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtlsbeigcg.html

Java: System.exit(1)
来源：http://dali.316326.xyz/Article/details/gtancgjmwo.html

Go:   os.Exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtglhlvamx.html

Ruby: exit 1
来源：http://dali.zdqjudy.top/Article/details/gtxncxnqna.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cashguo.top/Article/details/gthrmfmskq.html

[M06] 向标准错误输出
来源：http://dali.yanxiufei.cn/Article/details/gtbnqvhicw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangdashe.top/Article/details/gteizghcnh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ydzc1.top/Article/details/gthqnicztq.html

JS:   console.error("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlpgnysyt.html

TS:   console.error("err")
来源：http://dali.guannengcc.top/Article/details/gtaxztrxin.html

Java: System.err.println("err")
来源：http://dali.ybcxt.top/Article/details/gtntrvqpvg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenjidiqi.icu/Article/details/gtafdzrmht.html

Ruby: warn "err"
来源：http://dali.0kj1m.cn/Article/details/gttaofdwyz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigufen.top/Article/details/gtdqwklydj.html

[M07] 判断是否为主入口
来源：http://dali.xylfe.cn/Article/details/gtbaisavty.html

Py:   if __name__ == "__main__":
来源：http://dali.ppjwa.cn/Article/details/gtibtfuljm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gzhubu.top/Article/details/gtwjilduet.html

JS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gttskliuyd.html

TS:   require.main === module
来源：http://dali.yuanzhike.top/Article/details/gtxghsgxtl.html

Java: public static void main(String[] args)
来源：http://dali.haohaochexian.top/Article/details/gtmttseiwz.html

Go:   func main()
来源：http://dali.gogol.net.cn/Article/details/gtlvoxgkqe.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tanke756.top/Article/details/gtkbnikejd.html

C#:   static void Main(string[] args)
来源：http://dali.yonumen.top/Article/details/gtyeertwed.html

[M08] 获取系统与运行时信息
来源：http://dali.gotoacloud.top/Article/details/gtleholyrj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.havefunace.top/Article/details/gtkyajmvce.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cqqwz.cn/Article/details/gthyfbctfm.html

JS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gtgbppesjx.html

TS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gtygjobltv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.pengpengdd.cyou/Article/details/gtbcoexvgf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gaohongyu789.top/Article/details/gtfwwdzyzi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shanyushiyangkeji.top/Article/details/gtphxozbln.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gotoacloud.top/Article/details/gtfirswnff.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtaslbarvh.html

N. 数据结构与算法
来源：http://dali.feifeiyinyue.top/Article/details/gtdmnvlpql.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtpktsakqo.html

[N01] 二分查找（有序数组）
来源：http://dali.nwbrower.top/Article/details/gtdikmdxsy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.pycfn.com/Article/details/gtzblrbzxz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gtfxnfvgyl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.redwolf501.top/Article/details/gttjffkamh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gtbbrwetht.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtcmzqnsuc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtamvnjtfu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.feifeiyinyue.top/Article/details/gtingawdtv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtoptzgjkq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258.top/Article/details/gtexsafxxr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guowangkeji.top/Article/details/gtrlbwqmhz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sufxvd.cn/Article/details/gtfigswpoc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gtdeperkuw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhongyouzk.top/Article/details/gtkcwwwexj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gaohongyu789.top/Article/details/gtnntmhzlr.html

Go:   slices.Sort(arr)
来源：http://dali.yj202588.top/Article/details/gtkbylvgvd.html

Ruby: arr.sort
来源：http://dali.zhengqikj.top/Article/details/gthkwvpkaw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jlsjyb.cn/Article/details/gtozpzhptd.html

[N03] 快速排序（分治示例）
来源：http://dali.jqgufenzy.top/Article/details/gtckthvsqh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.svipenyu.cn/Article/details/gtcuvxceuc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cheryme.top/Article/details/gtnfdlergz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gzhubu.top/Article/details/gtoqrmwcvj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezcieect.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hnxiangtu.top/Article/details/gtekwwanpt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxiwgatt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvuuoabem.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tianlin.xyz/Article/details/gtyhtpccwn.html

[N04] 斐波那契数列
来源：http://dali.daxiang520.top/Article/details/gtachfezda.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tian-w.cn/Article/details/gtaosbouea.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenjidiqi.icu/Article/details/gtqjsttwze.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgufenzy.top/Article/details/gtayybpoho.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gtlxutylir.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hnxiangtu.top/Article/details/gttlvakemo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.andypj.xyz/Article/details/gtciaunvjp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hfpthk.cn/Article/details/gtktknjnse.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gtpgypxekx.html

[N05] 最大公约数
来源：http://dali.jinqigufen.top/Article/details/gtyixawpmu.html

Py:   math.gcd(a, b)
来源：http://dali.hfpthk.cn/Article/details/gtgojcrqse.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmvspzki.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.haohaochexian.top/Article/details/gtdpviunas.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gtdcstmbjd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinqigufen.top/Article/details/gtfgwvhmro.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yvedp.cn/Article/details/gtlaaddluz.html

Ruby: a.gcd(b)
来源：http://dali.yuanzhike.top/Article/details/gtcvndbsir.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenjidiqi.icu/Article/details/gttrnkevhd.html

[N06] 判断回文字符串
来源：http://dali.fengsongda.top/Article/details/gtbzginlyi.html

Py:   s == s[::-1]
来源：http://dali.ehwqpu.com/Article/details/gtpqrjkrnv.html

PHP:  $s === strrev($s);
来源：http://dali.ivvv.top/Article/details/gtdruffnvq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gthwucalgr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtsonqywsd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zycfv.cn/Article/details/gttfnjcubs.html

Go:   // 双指针从两端比较
来源：http://dali.sxryk.cn/Article/details/gtnslgomyv.html

Ruby: s == s.reverse
来源：http://dali.hnxiangtu.top/Article/details/gtexyjfqcb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cucudq.cn/Article/details/gtdgkocskw.html

[N07] 两数之和（返回下标）
来源：http://dali.sxryk.cn/Article/details/gtqtulibgi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yuxming.cn/Article/details/gtfspwdgur.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tanke756.top/Article/details/gtblgypmbc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jlsjyb.cn/Article/details/gtnobcitna.html

TS:   // 手写 Map<string, number>
来源：http://dali.andypj.xyz/Article/details/gtiqvpleht.html

Java: // 手写 HashMap
来源：http://dali.snrcjt.cn/Article/details/gtggjtakbj.html

Go:   // 手写 map[int]int
来源：http://dali.jqgufenzy.top/Article/details/gtafanbikv.html

Ruby: // 手写 Hash
来源：http://dali.mhx1999.top/Article/details/gtxosfkzbe.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sweek.top/Article/details/gtqbmbrrlm.html

[N08] 生成全排列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdkdgbnu.html

Py:   itertools.permutations(arr)
来源：http://dali.hywenlv.cn/Article/details/gtkoenkema.html

PHP:  // 手写递归交换
来源：http://dali.meibo888.top/Article/details/gtxlrycics.html

JS:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gtszgylwky.html

TS:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtiohzoqxd.html

Java: // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtsoqgprgl.html

Go:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtgurnpsax.html

Ruby: arr.permutation.to_a
来源：http://dali.xylfe.cn/Article/details/gtjzilsnoz.html

C#:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtwvulkybx.html

[N09] 栈与队列
来源：http://dali.haohaochexian.top/Article/details/gtwandtoys.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.guannengcc.top/Article/details/gtfpsgpaos.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.pycfn.com/Article/details/gtpbbwrwpy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sweek.top/Article/details/gtgjmksnnj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xylfe.cn/Article/details/gtqokpoevy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yvedp.cn/Article/details/gtxuwnkmuz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cucudq.cn/Article/details/gtwfhxeomx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.316326.xyz/Article/details/gtpargdyrv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenzaomai.com/Article/details/gtruumdsbj.html

[N10] 链表节点定义
来源：http://dali.aizwys.cn/Article/details/gteyuezlst.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydxfjpnt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.aizwys.cn/Article/details/gtarufetdz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.nanxuanxn.top/Article/details/gtqhrqbfbh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.feifeiyinyue.top/Article/details/gtrmjkmnwk.html

Java: class Node { int v; Node next; }
来源：http://dali.tian-w.cn/Article/details/gtpixuzfkt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.andypj.xyz/Article/details/gttcaeejaf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.birdmap.top/Article/details/gtxbvtoiff.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.feifeiyinyue.top/Article/details/gtzfoeprdc.html

[N11] 二叉树中序遍历
来源：http://dali.zhongyouzk.top/Article/details/gtipwrzzxc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj202588.top/Article/details/gtllxzpbvd.html

PHP:  // 手写递归函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gttunntulg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jianghu66.top/Article/details/gttfnpuekt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.0kj1m.cn/Article/details/gtkoghmgwa.html

Java: // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gtlzzqfzoa.html

Go:   // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gtxkwwytqe.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yuanzhike.top/Article/details/gtzhqafxfw.html

C#:   // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gtzkvdbrhg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gogol.net.cn/Article/details/gtuwelkbgl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.kuanghao11.cn/Article/details/gtylsbbqfw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gotoacloud.top/Article/details/gtsmgdoroy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daria6918.cn/Article/details/gthbbbixjj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ivvv.top/Article/details/gtslegkbyz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cashguo.top/Article/details/gtischdjcu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj20258.top/Article/details/gtxsbnfyoq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gtbfqpfhzy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.vqdsnc.cn/Article/details/gtiotlndze.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtlbvewaeq.html

O. 并发与异步
来源：http://dali.zdqjudy.top/Article/details/gtwvzkxtqi.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtntxpubvm.html

[O01] 启动一个线程
来源：http://dali.chenjidiqi.icu/Article/details/gtfyxlsquf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.svipenyu.cn/Article/details/gtflqtnmxf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.bjfxy.top/Article/details/gthaoteocm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xylfe.cn/Article/details/gtztpeqdsy.html

TS:   // 同 JS
来源：http://dali.shzxlz.cn/Article/details/gtuujqasii.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinqigfzy.top/Article/details/gtowdwzlmp.html

Go:   go f()
来源：http://dali.jlsjyb.cn/Article/details/gthkpxmdsp.html

Ruby: Thread.new { f }
来源：http://dali.chenjidiqi.icu/Article/details/gtygadkbnx.html

C#:   Task.Run(() => F());
来源：http://dali.yonumen.top/Article/details/gthrkvlqbt.html

[O02] 使用线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaczgionm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xinyue.icu/Article/details/gtiuissdke.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hnqzz.top/Article/details/gtattrvrty.html

JS:   // worker_threads 线程池
来源：http://dali.kuanghao11.cn/Article/details/gttpjglngs.html

TS:   // worker_threads 线程池
来源：http://dali.sweek.top/Article/details/gtzehhdbtd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.0kj1m.cn/Article/details/gtrvbcfjuq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenlongwang.top/Article/details/gtxcybsxht.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.wangshuangyany.cn/Article/details/gtsksktejw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xziqi.cn/Article/details/gtnbzqgdhp.html

[O03] 加锁保护共享数据
来源：http://dali.yvedp.cn/Article/details/gtsdivcrqp.html

Py:   with lock: shared += 1
来源：http://dali.aibaodan.cn/Article/details/gtogjwxpik.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.fengsongda.top/Article/details/gtbairgcia.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.0kj1m.cn/Article/details/gtpxxjjplb.html

TS:   // 同 JS
来源：http://dali.jyoumei.cn/Article/details/gtrxlhpfhw.html

Java: synchronized (this) { shared++; }
来源：http://dali.guannengcc.top/Article/details/gtdrbmoytl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yueranfly.top/Article/details/gtrpigjlxh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xylfe.cn/Article/details/gtzxvbjlmi.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhixingplan.top/Article/details/gtmpiswaaw.html

[O04] 定义异步函数并等待
来源：http://dali.nanxinkj.top/Article/details/gtldzaqrmr.html

Py:   async def f():⏎    await g()
来源：http://dali.mhx1999.top/Article/details/gtkalxlbjr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yanxiufei.cn/Article/details/gtpmkkuyuu.html

JS:   async function f() { await g(); }
来源：http://dali.ydzc1.top/Article/details/gtzrjsbetp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.fzhhl.top/Article/details/gtmfvximpd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sufxvd.cn/Article/details/gtjlewrcbi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zdqjudy.top/Article/details/gtqjsvixls.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenlongwang.top/Article/details/gtdzwmjkkk.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gtojaybxay.html

[O05] 并发执行并等待全部完成
来源：http://dali.hnqzz.top/Article/details/gtzjouynde.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yongpay.top/Article/details/gtyrqjupvr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nanxuanxn.top/Article/details/gtaxyymxvd.html

JS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gtsdqewgsh.html

TS:   await Promise.all(tasks)
来源：http://dali.havefunace.top/Article/details/gtdvksljcs.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.haohaochexian.top/Article/details/gtwhxxwczd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.havefunace.top/Article/details/gtgaptklgv.html

Ruby: threads.map(&:join)
来源：http://dali.pengpengdd.cyou/Article/details/gtzywnrrxo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenzaomai.com/Article/details/gtgmblfzno.html

[O06] 使用进程池
来源：http://dali.fengsongda.top/Article/details/gtivhtfkml.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.redwolf501.top/Article/details/gtgkyovogu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hammf.cn/Article/details/gtuccioryd.html

JS:   // child_process / cluster 模块
来源：http://dali.nanxinkj.top/Article/details/gtwumdbfbm.html

TS:   // child_process / cluster 模块
来源：http://dali.jlsjyb.cn/Article/details/gtthvqfnkk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.kuanghao11.cn/Article/details/gtumksgoua.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cashguo.top/Article/details/gtieyyaerd.html

Ruby: // fork 块
来源：http://dali.316326.xyz/Article/details/gtyfzbqfcx.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gtjbfojzay.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gteprnrwob.html

P. 常用工具函数
来源：http://dali.zhengqikj.top/Article/details/gtpuvbtgfc.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtnwmyeldl.html

[P01] 生成 UUID
来源：http://dali.wangdashe.top/Article/details/gtsnmydnil.html

Py:   str(uuid.uuid4())
来源：http://dali.tianlin.xyz/Article/details/gtarzoicre.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbjbtchx.html

JS:   crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gtstbilgbx.html


<!-- 参考信息 -->