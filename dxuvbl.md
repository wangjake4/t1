代发 wailian999

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxydrlvm.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gtawajnmfv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yangfankeji.com/Article/details/gtzgpqnrok.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yangfankeji.com/Article/details/gtzgzkrplh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dashuyun.cn/Article/details/gtokwlpvha.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sweek.top/Article/details/gtzxhhmoey.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yvedp.cn/Article/details/gtdgbmnjii.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ehwqpu.com/Article/details/gtzbfbuwdp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ivvv.top/Article/details/gtdbbpnull.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xylfe.cn/Article/details/gtqreujuss.html

[L05] 上传文件（multipart）
来源：http://dali.chenjidiqi.icu/Article/details/gtrmqapdgg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.wangshuangyany.cn/Article/details/gtxavibtgz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jqgfzy.top/Article/details/gtbmmxbitr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxinkj.top/Article/details/gtiyqjqtmw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ehwqpu.com/Article/details/gtxpuiofxe.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dianchejie.cn/Article/details/gtkeujrlum.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tianlin.xyz/Article/details/gtcfslhhsi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.guowangkeji.top/Article/details/gtlflymamn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj20258888.top/Article/details/gtogybkmpz.html

[L06] 解析响应为 JSON
来源：http://dali.guowangkeji.top/Article/details/gtaffxqupc.html

Py:   resp.json()
来源：http://dali.jqgfzy.top/Article/details/gtjirvaskc.html

PHP:  json_decode($body, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtygfshcyl.html

JS:   await resp.json()
来源：http://dali.jiagoushi.top/Article/details/gtrbndenqm.html

TS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtydupopyc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ppjwa.cn/Article/details/gtkxaydmti.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenlongwang.top/Article/details/gtyxfbmsup.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nwbrower.top/Article/details/gttslhjmzc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hnqzz.top/Article/details/gtzwmkzflw.html

[L07] 处理 HTTP 状态码
来源：http://dali.sxryk.cn/Article/details/gtcqtrvlre.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yvedp.cn/Article/details/gtbnfgmeoq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.daxiang520.top/Article/details/gtjyaegbmt.html

JS:   resp.ok;  resp.status
来源：http://dali.9152youxi.cn/Article/details/gttidoygoj.html

TS:   resp.ok;  resp.status
来源：http://dali.snrcjt.cn/Article/details/gtvfnnbzli.html

Java: resp.statusCode()
来源：http://dali.andypj.xyz/Article/details/gtwsrfccza.html

Go:   resp.StatusCode
来源：http://dali.gaohongyu789.top/Article/details/gtewiotydy.html

Ruby: resp.code.to_i
来源：http://dali.xylfe.cn/Article/details/gtqnjhgeuy.html

C#:   (int)resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gtjbyduiqf.html

[L08] 并发请求多个地址
来源：http://dali.iojbl.cn/Article/details/gtxqjgybgj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shuidangran.top/Article/details/gtrybtvycn.html

PHP:  curl_multi_init() 系列
来源：http://dali.birdmap.top/Article/details/gtibylpihy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gtwyohfwyb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtzuydjqxp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtswhrrbac.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqdsdwke.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.havefunace.top/Article/details/gtkdtzhovj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxuanxn.top/Article/details/gtziqekswv.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtjdzuhagx.html

M. 命令行 / 进程 / 环境
来源：http://dali.jiagoushi.top/Article/details/gtnczccuip.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gturhgmrkv.html

[M01] 读取命令行参数
来源：http://dali.zhongyouzk.top/Article/details/gtjzdtplxj.html

Py:   sys.argv[1:]
来源：http://dali.jqgufenzy.top/Article/details/gtveywrnvo.html

PHP:  $argv;  $argc;
来源：http://dali.havefunace.top/Article/details/gttbgwpztg.html

JS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtatbuxfwc.html

TS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gtgbydwjiz.html

Java: args 数组（main 方法参数）
来源：http://dali.aibaodan.cn/Article/details/gtlmiyeeru.html

Go:   os.Args[1:]
来源：http://dali.jqgufenzy.top/Article/details/gtyiejymbg.html

Ruby: ARGV
来源：http://dali.tian-w.cn/Article/details/gtyjogjdon.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tian-w.cn/Article/details/gtiksrywch.html

[M02] 读取环境变量
来源：http://dali.meibo888.top/Article/details/gtbjappggi.html

Py:   os.environ.get("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtkeznprio.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ydzc1.top/Article/details/gtcgyezccg.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gtuwcvczew.html

TS:   process.env.HOME
来源：http://dali.9152youxi.cn/Article/details/gtsigzphtg.html

Java: System.getenv("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtzintnbzb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtahqzopst.html

Ruby: ENV["HOME"]
来源：http://dali.havefunace.top/Article/details/gthdjrfksp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtbvpbmmke.html

[M03] 执行外部命令
来源：http://dali.meibo888.top/Article/details/gtebdyksva.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnqzz.top/Article/details/gtrlgeiejn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.birdmap.top/Article/details/gtcbbyamnh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gtyftkbuos.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.fzhhl.top/Article/details/gtpotnpxwd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nanxinkj.top/Article/details/gtwhvunefo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hnqzz.top/Article/details/gtppwiknal.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.birdmap.top/Article/details/gthwovpnfp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gthcbhvort.html

[M04] 获取当前工作目录
来源：http://dali.dianchejie.cn/Article/details/gtccedulri.html

Py:   os.getcwd()
来源：http://dali.xuetiantiany.cn/Article/details/gtbodupbpk.html

PHP:  getcwd();
来源：http://dali.zycfv.cn/Article/details/gtwzhcljlq.html

JS:   process.cwd()
来源：http://dali.cheryme.top/Article/details/gtctetzksk.html

TS:   process.cwd()
来源：http://dali.kuanghao11.cn/Article/details/gtromqtipm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nanxuanxn.top/Article/details/gtsqvxpbdn.html

Go:   os.Getwd()
来源：http://dali.hfpthk.cn/Article/details/gtrmkpniiy.html

Ruby: Dir.pwd
来源：http://dali.yongpay.top/Article/details/gtsnwniwej.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrabtiwh.html

[M05] 设置退出码
来源：http://dali.jinghuilouyu.cn/Article/details/gtyszgzinl.html

Py:   sys.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtrmweihom.html

PHP:  exit(1);
来源：http://dali.daxiang520.top/Article/details/gtewbnpduf.html

JS:   process.exit(1)
来源：http://dali.daxiang520.top/Article/details/gtnbdvwdaf.html

TS:   process.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtdtvopdsp.html

Java: System.exit(1)
来源：http://dali.yonumen.top/Article/details/gtavjpdmhh.html

Go:   os.Exit(1)
来源：http://dali.redwolf501.top/Article/details/gtwofguepz.html

Ruby: exit 1
来源：http://dali.bjfxy.top/Article/details/gtunxbbigy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cdnleiting.top/Article/details/gtwkyxqxpu.html

[M06] 向标准错误输出
来源：http://dali.gotoacloud.top/Article/details/gteabkkxzp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nanxuanxn.top/Article/details/gtpcaheosj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yangfankeji.com/Article/details/gtfjtmdzik.html

JS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gtivztxxtg.html

TS:   console.error("err")
来源：http://dali.jlsjyb.cn/Article/details/gtplfqsubm.html

Java: System.err.println("err")
来源：http://dali.jianghu66.top/Article/details/gtxqkuyegr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangshuangyany.cn/Article/details/gtqbeaufzf.html

Ruby: warn "err"
来源：http://dali.zycfv.cn/Article/details/gtbuwxfhpo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj20258888.top/Article/details/gtuncqmypg.html

[M07] 判断是否为主入口
来源：http://dali.yj20258.top/Article/details/gtvykljrth.html

Py:   if __name__ == "__main__":
来源：http://dali.jqgfzy.top/Article/details/gtrdxufvap.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.daria6918.cn/Article/details/gtqhofehvc.html

JS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gtajyglvjh.html

TS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gtuvkjuhdz.html

Java: public static void main(String[] args)
来源：http://dali.nanxinkj.top/Article/details/gtkpaskdux.html

Go:   func main()
来源：http://dali.316326.xyz/Article/details/gtbjjyqkqk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gogol.net.cn/Article/details/gtslqwlbyx.html

C#:   static void Main(string[] args)
来源：http://dali.tanke756.top/Article/details/gtcalacttp.html

[M08] 获取系统与运行时信息
来源：http://dali.wangshuangyany.cn/Article/details/gtdupmqrlg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.meibo888.top/Article/details/gtswyawpvv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yanxiufei.cn/Article/details/gtigcfkgku.html

JS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gtmaovvcam.html

TS:   process.platform;  process.version
来源：http://dali.meibo888.top/Article/details/gttszhwocl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cheryme.top/Article/details/gtxxfcvgmp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.c1oappe.top/Article/details/gtbqybruxt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj20258.top/Article/details/gtmexxmdpu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yuxming.cn/Article/details/gtejdgoqkx.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtgbwoubur.html

N. 数据结构与算法
来源：http://dali.0kj1m.cn/Article/details/gtdfdnigjs.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtowcilqvx.html

[N01] 二分查找（有序数组）
来源：http://dali.yangfankeji.com/Article/details/gtatirukdb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.316326.xyz/Article/details/gtgvqxanhc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlzbcidgx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenlongwang.top/Article/details/gtydaflvwj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tianlin.xyz/Article/details/gtatzdwquy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggdjljak.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yongpay.top/Article/details/gtdhdpmier.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hnxiangtu.top/Article/details/gtfwpocmgg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtazaythbv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nanxuanxn.top/Article/details/gthqyvknys.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ivvv.top/Article/details/gtyhybhuxo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yangfankeji.com/Article/details/gtciqjrdob.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gtngvvodag.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gtrxcqgtgf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.kuanghao11.cn/Article/details/gtdcprvqia.html

Go:   slices.Sort(arr)
来源：http://dali.sweek.top/Article/details/gtiodpilrt.html

Ruby: arr.sort
来源：http://dali.wangshuangyany.cn/Article/details/gthmkmwrgz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gotoacloud.top/Article/details/gtclqprpzp.html

[N03] 快速排序（分治示例）
来源：http://dali.hongshengwenyu.top/Article/details/gtjpuhgngs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cashguo.top/Article/details/gtxxgtmrzs.html

PHP:  // 递归实现，或用 usort
来源：http://dali.snrcjt.cn/Article/details/gtoofmryte.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sweek.top/Article/details/gtchdayojp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gtbshfhjte.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jianghu66.top/Article/details/gtmcitimut.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenlongwang.top/Article/details/gtezpxwuxg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cucudq.cn/Article/details/gtckacmdjs.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zycfv.cn/Article/details/gtwghlouor.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gtlnpxhdff.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shuidangran.top/Article/details/gtlhptpvbb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tian-w.cn/Article/details/gtkvnbsowv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gtbgdlyrrh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gtzvhtrsci.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sxryk.cn/Article/details/gtdlhphwsb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yuxming.cn/Article/details/gtzgroxvls.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sweek.top/Article/details/gtehrihdwy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gturlbputi.html

[N05] 最大公约数
来源：http://dali.wangdashe.top/Article/details/gtltvucoup.html

Py:   math.gcd(a, b)
来源：http://dali.redwolf501.top/Article/details/gtcjcmxjvy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hywenlv.cn/Article/details/gtpdvurrqg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xinyue.icu/Article/details/gtycvdoizg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.9152youxi.cn/Article/details/gtxvibjbxz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.c1oappe.top/Article/details/gthkjgluvb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yuxming.cn/Article/details/gtwqiklwbh.html

Ruby: a.gcd(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtdnnxwaan.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhoulong.xyz/Article/details/gtkibpizkk.html

[N06] 判断回文字符串
来源：http://dali.chenzaomai.com/Article/details/gtrnyloivq.html

Py:   s == s[::-1]
来源：http://dali.gogol.net.cn/Article/details/gtldgcapxq.html

PHP:  $s === strrev($s);
来源：http://dali.daxiang520.top/Article/details/gtynsdrfld.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtsyfeazdi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtfdjrreno.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hywenlv.cn/Article/details/gtubijluyn.html

Go:   // 双指针从两端比较
来源：http://dali.jqgfzy.top/Article/details/gtoowmvfdd.html

Ruby: s == s.reverse
来源：http://dali.gaohongyu789.top/Article/details/gtfhbkavxa.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yanxiufei.cn/Article/details/gtkiqmxdbh.html

[N07] 两数之和（返回下标）
来源：http://dali.zhixingplan.top/Article/details/gtoaczdsmp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.birdmap.top/Article/details/gtfjfcwxqd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.guowangkeji.top/Article/details/gttnyawgur.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xinyue.icu/Article/details/gtflbylcgb.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhongyouzk.top/Article/details/gthjojhfak.html

Java: // 手写 HashMap
来源：http://dali.xinyue.icu/Article/details/gttnfurprc.html

Go:   // 手写 map[int]int
来源：http://dali.jqgufenzy.top/Article/details/gtuednohlj.html

Ruby: // 手写 Hash
来源：http://dali.shanyushiyangtech.top/Article/details/gtobsdlzwb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinqigufen.top/Article/details/gtjyicderh.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gtsmubhemu.html

Py:   itertools.permutations(arr)
来源：http://dali.guowangkeji.top/Article/details/gtdgduzlqn.html

PHP:  // 手写递归交换
来源：http://dali.jyoumei.cn/Article/details/gtxqzonvkd.html

JS:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwuoswjbl.html

TS:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtgrdppmqo.html

Java: // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtesqoeiye.html

Go:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gthqvxjlmw.html

Ruby: arr.permutation.to_a
来源：http://dali.yanxiufei.cn/Article/details/gtuitiayvn.html

C#:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gtgrtrwkzs.html

[N09] 栈与队列
来源：http://dali.cashguo.top/Article/details/gtxxfpjvnw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yueranfly.top/Article/details/gtfrysbvkg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jyoumei.cn/Article/details/gtflflwpqr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gtnecfxnxs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jianghu66.top/Article/details/gtlnrkyigq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.kuanghao11.cn/Article/details/gtufcjtamk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.9152youxi.cn/Article/details/gtzlfjspdr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtiwtiwwfz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.bjfxy.top/Article/details/gtdndpayen.html

[N10] 链表节点定义
来源：http://dali.hnxiangtu.top/Article/details/gtecuhiifg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpigrobdo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.pycfn.com/Article/details/gttvlqcoog.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gterhvanhm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqaoekzxq.html

Java: class Node { int v; Node next; }
来源：http://dali.cdnleiting.top/Article/details/gtvaimcytu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.iojbl.cn/Article/details/gtwowtsysb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nanxinkj.top/Article/details/gtshpqetdc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shuidangran.top/Article/details/gtsgepxuuj.html

[N11] 二叉树中序遍历
来源：http://dali.yueranfly.top/Article/details/gtgkvtlbgh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhoulong.xyz/Article/details/gtapepfnxi.html

PHP:  // 手写递归函数
来源：http://dali.guannengcc.top/Article/details/gtzrryllxb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jianghu66.top/Article/details/gtvbwqcdpt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenzaomai.com/Article/details/gtegeujult.html

Java: // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gtjnibjmsj.html

Go:   // 手写递归
来源：http://dali.yueranfly.top/Article/details/gtyofxazee.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.nwbrower.top/Article/details/gtgjmigpjr.html

C#:   // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gtjtbmuzed.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj20258.top/Article/details/gtkxcjkcdm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shuidangran.top/Article/details/gtrxrmssfr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.pycfn.com/Article/details/gtrelckhmx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenjidiqi.icu/Article/details/gtbfudvvaq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daria6918.cn/Article/details/gtillzsgte.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hysaishi.cn/Article/details/gtmlmfkixc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cashguo.top/Article/details/gtyheulhci.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yongpay.top/Article/details/gtqfaplejk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.snrcjt.cn/Article/details/gtxzcmqkdd.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtzcuhdjbc.html

O. 并发与异步
来源：http://dali.xziqi.cn/Article/details/gtqhwtpolb.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtrvnpclqo.html

[O01] 启动一个线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtncbmmujo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yueranfly.top/Article/details/gtazbsacnl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gotoacloud.top/Article/details/gtnhwudsvx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shzxlz.cn/Article/details/gtndkjaaxw.html

TS:   // 同 JS
来源：http://dali.xuetiantiany.cn/Article/details/gtgtxpqian.html

Java: new Thread(() -> f()).start()
来源：http://dali.c1oappe.top/Article/details/gtmjdlwipi.html

Go:   go f()
来源：http://dali.smart0.xyz/Article/details/gtzxulysgu.html

Ruby: Thread.new { f }
来源：http://dali.yj20258888.top/Article/details/gtgnaptrzi.html

C#:   Task.Run(() => F());
来源：http://dali.zhengqikj.top/Article/details/gtonfncdln.html

[O02] 使用线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehvwwtzb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cdnleiting.top/Article/details/gttsuzbvqc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.redwolf501.top/Article/details/gtlwauzdig.html

JS:   // worker_threads 线程池
来源：http://dali.316326.xyz/Article/details/gtbpndfzlu.html

TS:   // worker_threads 线程池
来源：http://dali.zycfv.cn/Article/details/gtypdjkiqw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinqigfzy.top/Article/details/gtoftshfds.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxrcrwsl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.316326.xyz/Article/details/gtyfmcabsj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.redwolf501.top/Article/details/gtweeddbya.html

[O03] 加锁保护共享数据
来源：http://dali.cdnleiting.top/Article/details/gtknivkagv.html

Py:   with lock: shared += 1
来源：http://dali.yongpay.top/Article/details/gtpfdttjvs.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.dianchejie.cn/Article/details/gtsddcofpc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hongshengwenyu.top/Article/details/gtlhowfxax.html

TS:   // 同 JS
来源：http://dali.ydzc1.top/Article/details/gtkbqylxoi.html

Java: synchronized (this) { shared++; }
来源：http://dali.smart0.xyz/Article/details/gtojvbsaap.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tanke756.top/Article/details/gtqsiwpeti.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yongpay.top/Article/details/gtyrlwvgoe.html

C#:   lock (gate) { shared++; }
来源：http://dali.yonumen.top/Article/details/gtuzerxeom.html

[O04] 定义异步函数并等待
来源：http://dali.sysykeji.top/Article/details/gtleefgbba.html

Py:   async def f():⏎    await g()
来源：http://dali.ehwqpu.com/Article/details/gtqxcwnnnj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shzxlz.cn/Article/details/gthoubfkib.html

JS:   async function f() { await g(); }
来源：http://dali.vqdsnc.cn/Article/details/gtdiwgxffw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nwbrower.top/Article/details/gtvivvualm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj20258.top/Article/details/gttwbbuedf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zdqjudy.top/Article/details/gtqxbglqpg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfxgjttpu.html

C#:   async Task F() { await G(); }
来源：http://dali.tianlin.xyz/Article/details/gtwlgyoovd.html

[O05] 并发执行并等待全部完成
来源：http://dali.guannengcc.top/Article/details/gtdotqfjut.html

Py:   asyncio.gather(*tasks)
来源：http://dali.fzhhl.top/Article/details/gtfgnrlusa.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xuanzx.com/Article/details/gtrcctguqe.html

JS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gtnbeejzgh.html

TS:   await Promise.all(tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabxpzepc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shuidangran.top/Article/details/gtkoeaxdjp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.316326.xyz/Article/details/gtcizteggt.html

Ruby: threads.map(&:join)
来源：http://dali.yuanzhike.top/Article/details/gtyhxrhluo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jiagoushi.top/Article/details/gtpuvkeaif.html

[O06] 使用进程池
来源：http://dali.chenjidiqi.icu/Article/details/gtrekmhdep.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenzaomai.com/Article/details/gtibtwixfj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.aizwys.cn/Article/details/gtmkwugbcl.html

JS:   // child_process / cluster 模块
来源：http://dali.meibo888.top/Article/details/gthwbfgaeq.html

TS:   // child_process / cluster 模块
来源：http://dali.chenzaomai.com/Article/details/gtemoxdsyk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhongyouzk.top/Article/details/gteyhjwdso.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hnqzz.top/Article/details/gtkotulfbu.html

Ruby: // fork 块
来源：http://dali.snrcjt.cn/Article/details/gtoroxtvhi.html

C#:   Parallel.For
来源：http://dali.cashguo.top/Article/details/gtpyxnfbmp.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtdklgcpdd.html

P. 常用工具函数
来源：http://dali.ivvv.top/Article/details/gtcckvlhbr.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtueqyeyof.html

[P01] 生成 UUID
来源：http://dali.havefunace.top/Article/details/gtlodmazes.html

Py:   str(uuid.uuid4())
来源：http://dali.smart0.xyz/Article/details/gtgwovtsnm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwfpwltl.html

JS:   crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gtlkqvwebf.html

TS:   crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gtbklufdtk.html

Java: UUID.randomUUID().toString()
来源：http://dali.316326.xyz/Article/details/gtpfbqeftb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sxryk.cn/Article/details/gtvhtzromx.html

Ruby: SecureRandom.uuid
来源：http://dali.xylfe.cn/Article/details/gtgxdburor.html


<!-- 参考信息 -->