代发 wailian999

[L03] 设置自定义请求头
来源：http://dali.wangdashe.top/Article/details/gtsoerkpka.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ydzc1.top/Article/details/gteynmuppm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinqigfzy.top/Article/details/gtxxjzhqgg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhoulong.xyz/Article/details/gtlsetnolh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gtsykgfyte.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhoulong.xyz/Article/details/gtvmlekfsl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tanke756.top/Article/details/gtxicaugbr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhiwuduotai.top/Article/details/gtldjmwwap.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sweek.top/Article/details/gtqlvxekxz.html

[L04] 设置超时
来源：http://dali.hywenlv.cn/Article/details/gtklrkdwqv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shzxlz.cn/Article/details/gtqykbdqpq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgfzy.top/Article/details/gtcjomcole.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aibaodan.cn/Article/details/gtubicagic.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gtpxqlzlvv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.smart0.xyz/Article/details/gtfzgagbdy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dashuyun.cn/Article/details/gtuzxqfgke.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.fengsongda.top/Article/details/gtzhfldbyr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtskprtxhl.html

[L05] 上传文件（multipart）
来源：http://dali.wangshuangyany.cn/Article/details/gtsqmxqiii.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.aizwys.cn/Article/details/gtomyvkiwn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hnqzz.top/Article/details/gturtszqbr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gtltmtoxdq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.fengsongda.top/Article/details/gtooqbintt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ehwqpu.com/Article/details/gtpibgcdjt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.daria6918.cn/Article/details/gtuvwzbykf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yongpay.top/Article/details/gtxaalcrfk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xinyue.icu/Article/details/gthmwkijto.html

[L06] 解析响应为 JSON
来源：http://dali.ppjwa.cn/Article/details/gtbbiaitjm.html

Py:   resp.json()
来源：http://dali.sufxvd.cn/Article/details/gtuwngqiti.html

PHP:  json_decode($body, true);
来源：http://dali.jiagoushi.top/Article/details/gtphzrcruz.html

JS:   await resp.json()
来源：http://dali.xinyue.icu/Article/details/gtvxzeturj.html

TS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gtllpytkdo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jianghu66.top/Article/details/gtuctpbjek.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ehwqpu.com/Article/details/gtsgjixiii.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinqigufen.top/Article/details/gtmecipjql.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jlsjyb.cn/Article/details/gtxwhghpnc.html

[L07] 处理 HTTP 状态码
来源：http://dali.ybcxt.top/Article/details/gtwuuqwqqa.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cqqwz.cn/Article/details/gtfijglqjm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hnxiangtu.top/Article/details/gtxakklqfx.html

JS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gtionlzpvk.html

TS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gtvbwtdrnq.html

Java: resp.statusCode()
来源：http://dali.xziqi.cn/Article/details/gtcohyijoh.html

Go:   resp.StatusCode
来源：http://dali.chenlongwang.top/Article/details/gtxybwocxq.html

Ruby: resp.code.to_i
来源：http://dali.ivvv.top/Article/details/gtdjvhakdw.html

C#:   (int)resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gtdrheceym.html

[L08] 并发请求多个地址
来源：http://dali.zycfv.cn/Article/details/gtznulkvaz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.redwolf501.top/Article/details/gtrftlaeus.html

PHP:  curl_multi_init() 系列
来源：http://dali.hongshengwenyu.top/Article/details/gtbvjaiube.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gtiewzuyxb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gtubkicqvg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jlsjyb.cn/Article/details/gtcgcbompi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.daxiang520.top/Article/details/gtjvxtgfkj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jlsjyb.cn/Article/details/gtcwgshvnz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jianghu66.top/Article/details/gtlgxbmcar.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gttxjvokvp.html

M. 命令行 / 进程 / 环境
来源：http://dali.tianlin.xyz/Article/details/gtntaocdfq.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtrjvozazh.html

[M01] 读取命令行参数
来源：http://dali.feifeiyinyue.top/Article/details/gtlscukxsa.html

Py:   sys.argv[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gtbeyhagvx.html

PHP:  $argv;  $argc;
来源：http://dali.hywenlv.cn/Article/details/gthhdnmkmu.html

JS:   process.argv.slice(2)
来源：http://dali.bjfxy.top/Article/details/gtakklqoxo.html

TS:   process.argv.slice(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjrxaoky.html

Java: args 数组（main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gtokcrevqs.html

Go:   os.Args[1:]
来源：http://dali.yangfankeji.com/Article/details/gtxsgajcov.html

Ruby: ARGV
来源：http://dali.hammf.cn/Article/details/gtkuabnrnl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinqigfzy.top/Article/details/gtduahvgnl.html

[M02] 读取环境变量
来源：http://dali.aizwys.cn/Article/details/gtiagremxu.html

Py:   os.environ.get("HOME")
来源：http://dali.aibaodan.cn/Article/details/gttuanokqp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gtptmygarl.html

JS:   process.env.HOME
来源：http://dali.shzxlz.cn/Article/details/gtlrndezop.html

TS:   process.env.HOME
来源：http://dali.hywenlv.cn/Article/details/gtisucbjor.html

Java: System.getenv("HOME")
来源：http://dali.xinyue.icu/Article/details/gtwmiiypys.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cashguo.top/Article/details/gtjrtyqlgz.html

Ruby: ENV["HOME"]
来源：http://dali.cashguo.top/Article/details/gthdvbyllo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.pycfn.com/Article/details/gtbigoiftv.html

[M03] 执行外部命令
来源：http://dali.jlsjyb.cn/Article/details/gtxkzpbvna.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.9152youxi.cn/Article/details/gtchbrkccc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.daria6918.cn/Article/details/gtantuwtbm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sysykeji.top/Article/details/gtpqfyihml.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtygglsetd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhixingplan.top/Article/details/gtwvnuinte.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jyoumei.cn/Article/details/gtcatfapnd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ivvv.top/Article/details/gttxxcfvor.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cdnleiting.top/Article/details/gtchibtexz.html

[M04] 获取当前工作目录
来源：http://dali.daria6918.cn/Article/details/gtukfcymck.html

Py:   os.getcwd()
来源：http://dali.gotoacloud.top/Article/details/gtbhfguuse.html

PHP:  getcwd();
来源：http://dali.hongshengwenyu.top/Article/details/gtskfjcghs.html

JS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gtiefrvnwu.html

TS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gtxtntjqmf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ppjwa.cn/Article/details/gtdmfxvrlj.html

Go:   os.Getwd()
来源：http://dali.yueranfly.top/Article/details/gtxiauclwo.html

Ruby: Dir.pwd
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedkmlfes.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.redwolf501.top/Article/details/gtmtmubbsj.html

[M05] 设置退出码
来源：http://dali.jiagoushi.top/Article/details/gtplxtyddy.html

Py:   sys.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkxicgdvk.html

PHP:  exit(1);
来源：http://dali.ivvv.top/Article/details/gtbftqauhz.html

JS:   process.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtidnbacuy.html

TS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtzcnzomlj.html

Java: System.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtcipgofwn.html

Go:   os.Exit(1)
来源：http://dali.yj20258.top/Article/details/gtkpwajwvd.html

Ruby: exit 1
来源：http://dali.guannengcc.top/Article/details/gtzryazlxs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zycfv.cn/Article/details/gtsmwmhzea.html

[M06] 向标准错误输出
来源：http://dali.nanxuanxn.top/Article/details/gtfqmktsog.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgufenzy.top/Article/details/gtjybhhekh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yanxiufei.cn/Article/details/gtuifyyanc.html

JS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gtcqdjzowu.html

TS:   console.error("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtkyfgmd.html

Java: System.err.println("err")
来源：http://dali.yangfankeji.com/Article/details/gtscmxuazf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.guowangkeji.top/Article/details/gtygnmzmay.html

Ruby: warn "err"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtulowxjzo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shuidangran.top/Article/details/gtobulhmpi.html

[M07] 判断是否为主入口
来源：http://dali.pycfn.com/Article/details/gtdgdaryeh.html

Py:   if __name__ == "__main__":
来源：http://dali.pycfn.com/Article/details/gtdvoyjzsa.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nwbrower.top/Article/details/gttxztpias.html

JS:   require.main === module
来源：http://dali.shuidangran.top/Article/details/gtayrcsynw.html

TS:   require.main === module
来源：http://dali.zhoulong.xyz/Article/details/gtwpasgkmf.html

Java: public static void main(String[] args)
来源：http://dali.cashguo.top/Article/details/gtpknqrwbj.html

Go:   func main()
来源：http://dali.jiagoushi.top/Article/details/gtezvkcmmn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.haohaochexian.top/Article/details/gtkjrxpaiq.html

C#:   static void Main(string[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gtnqtdrpku.html

[M08] 获取系统与运行时信息
来源：http://dali.9152youxi.cn/Article/details/gtgygtvuqm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yongpay.top/Article/details/gtcparsrvq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cdnleiting.top/Article/details/gtrmjwwoum.html

JS:   process.platform;  process.version
来源：http://dali.pycfn.com/Article/details/gtvwufxqiy.html

TS:   process.platform;  process.version
来源：http://dali.meibo888.top/Article/details/gtgtbsfued.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.pengpengdd.cyou/Article/details/gtnlbmsuhy.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jlsjyb.cn/Article/details/gtoxqwfnqw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcwbfbjz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yuxming.cn/Article/details/gtxpfakwza.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtluxtmluu.html

N. 数据结构与算法
来源：http://dali.sufxvd.cn/Article/details/gtheocamxi.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtwuakhbzm.html

[N01] 二分查找（有序数组）
来源：http://dali.zhiwuduotai.top/Article/details/gtozwgcyvi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tanke756.top/Article/details/gtrwgakrwm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gtzhwpyjut.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gttrxohkst.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hywenlv.cn/Article/details/gtfysqjubm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtwdyfqoks.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtqaoomume.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shzxlz.cn/Article/details/gtcvurhtgm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtlonurqzw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yueranfly.top/Article/details/gtioepuxvs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gtkawuwrpo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgpdeuhfa.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gtwieuztxt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhiwuduotai.top/Article/details/gtihogolbu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yangfankeji.com/Article/details/gtkfsrqgzf.html

Go:   slices.Sort(arr)
来源：http://dali.zhengqikj.top/Article/details/gtzxaxrrrl.html

Ruby: arr.sort
来源：http://dali.ehwqpu.com/Article/details/gtggbswxre.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenjidiqi.icu/Article/details/gtywpywfec.html

[N03] 快速排序（分治示例）
来源：http://dali.yangfankeji.com/Article/details/gtxsjykenb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gogol.net.cn/Article/details/gtqhccbhue.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhiwuduotai.top/Article/details/gtiwzncull.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gtkfvtrvww.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ydzc1.top/Article/details/gtiahlgyrb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hnqzz.top/Article/details/gtvjvrujqq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sweek.top/Article/details/gtoyfuijgo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhongyouzk.top/Article/details/gtheipevfh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hfpthk.cn/Article/details/gtzejppkvg.html

[N04] 斐波那契数列
来源：http://dali.ivvv.top/Article/details/gtyhuuwwij.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkahlqjgd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hnqzz.top/Article/details/gtccaoocvl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gtnudboafm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gtqlxbwoet.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsselcvpf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.316326.xyz/Article/details/gtgmjwumuz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnlrjiuhb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gtsykconwf.html

[N05] 最大公约数
来源：http://dali.daria6918.cn/Article/details/gtcvmnisqa.html

Py:   math.gcd(a, b)
来源：http://dali.yuanzhike.top/Article/details/gtcobmhrus.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xziqi.cn/Article/details/gtkjmhvjtc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hysaishi.cn/Article/details/gtiojxrouc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.meibo888.top/Article/details/gtvpnuzvxs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nanxinkj.top/Article/details/gtkuxpodnv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yuanzhike.top/Article/details/gtdlyptkjs.html

Ruby: a.gcd(b)
来源：http://dali.zhoulong.xyz/Article/details/gtlqddnteh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.bjfxy.top/Article/details/gthhsdabxz.html

[N06] 判断回文字符串
来源：http://dali.yj202588.top/Article/details/gttssmvklu.html

Py:   s == s[::-1]
来源：http://dali.quarkkingdee.top/Article/details/gtkgcfojbt.html

PHP:  $s === strrev($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcimhibyf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtweqcfswt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtlwrxjl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jlsjyb.cn/Article/details/gtoqreqbgu.html

Go:   // 双指针从两端比较
来源：http://dali.xylfe.cn/Article/details/gtivltwzkl.html

Ruby: s == s.reverse
来源：http://dali.yongpay.top/Article/details/gtcjktfxjn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hywenlv.cn/Article/details/gtlsoujell.html

[N07] 两数之和（返回下标）
来源：http://dali.shuidangran.top/Article/details/gtulhmxumr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.andypj.xyz/Article/details/gtafmmjzxn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cdnleiting.top/Article/details/gtfqlyshsi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sufxvd.cn/Article/details/gtzmedosfc.html

TS:   // 手写 Map<string, number>
来源：http://dali.havefunace.top/Article/details/gtlmgrjobh.html

Java: // 手写 HashMap
来源：http://dali.meibo888.top/Article/details/gtygdwgnuu.html

Go:   // 手写 map[int]int
来源：http://dali.zhongyouzk.top/Article/details/gtragoxnoj.html

Ruby: // 手写 Hash
来源：http://dali.sysykeji.top/Article/details/gtrlagomic.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.0kj1m.cn/Article/details/gtwhgvhliw.html

[N08] 生成全排列
来源：http://dali.ydzc1.top/Article/details/gtmvvnngup.html

Py:   itertools.permutations(arr)
来源：http://dali.smart0.xyz/Article/details/gtkzfhfjyw.html

PHP:  // 手写递归交换
来源：http://dali.feifeiyinyue.top/Article/details/gtiqapdsno.html

JS:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtrfhmhmto.html

TS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtxatkqbat.html

Java: // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gtzuvfdbau.html

Go:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtwaiqbtmr.html

Ruby: arr.permutation.to_a
来源：http://dali.cqqwz.cn/Article/details/gtzllfmizw.html

C#:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtcysqojgg.html

[N09] 栈与队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqtbgusv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.redwolf501.top/Article/details/gtenlfndns.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yvedp.cn/Article/details/gtannsgngm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gtfyhpgtly.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cqqwz.cn/Article/details/gtmdxxecch.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenlongwang.top/Article/details/gtihfcauyc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jlsjyb.cn/Article/details/gtlizcnfbr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jianghu66.top/Article/details/gtohrjdsfx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.fzhhl.top/Article/details/gtnxslyntc.html

[N10] 链表节点定义
来源：http://dali.guannengcc.top/Article/details/gtlbcueouv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yonumen.top/Article/details/gtgfiyjnnk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sufxvd.cn/Article/details/gtcmtpanjj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtbfvihkgy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hongshengwenyu.top/Article/details/gtyenuoiez.html

Java: class Node { int v; Node next; }
来源：http://dali.dianchejie.cn/Article/details/gtciyqpvhv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.pengpengdd.cyou/Article/details/gtsomvxmxx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gogol.net.cn/Article/details/gtigsoxlgn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.andypj.xyz/Article/details/gtwxqfmucb.html

[N11] 二叉树中序遍历
来源：http://dali.yanxiufei.cn/Article/details/gtgjggwgbh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.smart0.xyz/Article/details/gtulszhhxf.html

PHP:  // 手写递归函数
来源：http://dali.yonumen.top/Article/details/gtnzbsmepv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jyoumei.cn/Article/details/gtuhdzbfay.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjrutyti.html

Java: // 手写递归
来源：http://dali.shzxlz.cn/Article/details/gtefavdzan.html

Go:   // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gttslxzcuk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cheryme.top/Article/details/gtqtubodzy.html

C#:   // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gtfcgeiujg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ehwqpu.com/Article/details/gtooetrltx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nwbrower.top/Article/details/gtufatfmcr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.wangdashe.top/Article/details/gtuwcaegme.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj202588.top/Article/details/gtmvtnarvm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.feifeiyinyue.top/Article/details/gtdvqynitf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhoulong.xyz/Article/details/gtcwvjmlyv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhycxfnw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.fengsongda.top/Article/details/gtbhghvict.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gogol.net.cn/Article/details/gtddcesokp.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtucxppqdm.html

O. 并发与异步
来源：http://dali.jqgufenzy.top/Article/details/gtsjrewvrc.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtggolijtz.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gtnbehqsqj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ydzc1.top/Article/details/gtbmetysrg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ydzc1.top/Article/details/gtkjuehfom.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.smart0.xyz/Article/details/gtfojsboxc.html

TS:   // 同 JS
来源：http://dali.yonumen.top/Article/details/gtyvflpdug.html

Java: new Thread(() -> f()).start()
来源：http://dali.gzhubu.top/Article/details/gtquahdavv.html

Go:   go f()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjcwownr.html

Ruby: Thread.new { f }
来源：http://dali.jinqigfzy.top/Article/details/gtwfeghmzo.html

C#:   Task.Run(() => F());
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnwwxjhyc.html

[O02] 使用线程池
来源：http://dali.tian-w.cn/Article/details/gtjqjmvvrg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.feifeiyinyue.top/Article/details/gtrlihkhlu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gtfsaxwdil.html

JS:   // worker_threads 线程池
来源：http://dali.cheryme.top/Article/details/gtishlexvf.html

TS:   // worker_threads 线程池
来源：http://dali.snrcjt.cn/Article/details/gtgbzsgazm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.iojbl.cn/Article/details/gtceoeyyfz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ybcxt.top/Article/details/gtzzvwoqgn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hywenlv.cn/Article/details/gtemivevdw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.c1oappe.top/Article/details/gtwdtlfrxm.html

[O03] 加锁保护共享数据
来源：http://dali.smart0.xyz/Article/details/gtxwcfldry.html

Py:   with lock: shared += 1
来源：http://dali.jinqigufen.top/Article/details/gtiwpgzksp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sufxvd.cn/Article/details/gtaujhjwox.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdpejjnee.html

TS:   // 同 JS
来源：http://dali.hammf.cn/Article/details/gttpnjybbx.html

Java: synchronized (this) { shared++; }
来源：http://dali.jqgfzy.top/Article/details/gtajokfkly.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhengqikj.top/Article/details/gtwisghods.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yueranfly.top/Article/details/gtumfmhszz.html

C#:   lock (gate) { shared++; }
来源：http://dali.fengsongda.top/Article/details/gtscohvblp.html

[O04] 定义异步函数并等待
来源：http://dali.shanyushiyangkeji.top/Article/details/gtccmhvzpp.html

Py:   async def f():⏎    await g()
来源：http://dali.aizwys.cn/Article/details/gtinyapidy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.pycfn.com/Article/details/gtmlmfeqkv.html

JS:   async function f() { await g(); }
来源：http://dali.zdqjudy.top/Article/details/gtwvyayzzq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.redwolf501.top/Article/details/gtttqughrj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.mhx1999.top/Article/details/gtwcofgtrt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gtdbtuslku.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gotoacloud.top/Article/details/gtauaupqdf.html

C#:   async Task F() { await G(); }
来源：http://dali.hnqzz.top/Article/details/gtrxhixrgx.html

[O05] 并发执行并等待全部完成
来源：http://dali.haohaochexian.top/Article/details/gtgjpxexfj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yvedp.cn/Article/details/gtgocdlcff.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ehwqpu.com/Article/details/gtjspgsalk.html

JS:   await Promise.all(tasks)
来源：http://dali.sufxvd.cn/Article/details/gthgexfhvm.html

TS:   await Promise.all(tasks)
来源：http://dali.kuanghao11.cn/Article/details/gtschwacbg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shanyushiyangtech.top/Article/details/gtnsnokadp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hammf.cn/Article/details/gtbqnrrexf.html

Ruby: threads.map(&:join)
来源：http://dali.pycfn.com/Article/details/gttxxmziut.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.daria6918.cn/Article/details/gtsxloefcb.html

[O06] 使用进程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnqllmdod.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.smart0.xyz/Article/details/gtlqrxjots.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.feifeiyinyue.top/Article/details/gttwqljglg.html

JS:   // child_process / cluster 模块
来源：http://dali.zdqjudy.top/Article/details/gtrhmvpvdv.html

TS:   // child_process / cluster 模块
来源：http://dali.dashuyun.cn/Article/details/gtmyzjazlh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcknvzkwu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hnqzz.top/Article/details/gtmbkronyv.html

Ruby: // fork 块
来源：http://dali.xuanzx.com/Article/details/gtdhyutqkd.html

C#:   Parallel.For
来源：http://dali.gaohongyu789.top/Article/details/gtbxbjkeba.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtdlavnhks.html

P. 常用工具函数
来源：http://dali.ivvv.top/Article/details/gtrkvgkjqx.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtzzdfvspt.html


<!-- 参考信息 -->