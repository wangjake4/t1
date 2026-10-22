代发 wailian999

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gtasddotuq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tian-w.cn/Article/details/gtsqcmyfih.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.guannengcc.top/Article/details/gteivngsvi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.svipenyu.cn/Article/details/gtdbhwnggh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenlongwang.top/Article/details/gtwdtafeke.html

[L04] 设置超时
来源：http://dali.yuanzhike.top/Article/details/gtzydjpvbw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hongshengwenyu.top/Article/details/gtcdzfydli.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdnoqgnq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenlongwang.top/Article/details/gtupkccrzo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.birdmap.top/Article/details/gtwovalitl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.9152youxi.cn/Article/details/gtkfimkxvi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinqigufen.top/Article/details/gtqisjssjp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.wangshuangyany.cn/Article/details/gtrjrcbjyk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jqgfzy.top/Article/details/gtnloastqm.html

[L05] 上传文件（multipart）
来源：http://dali.gzhubu.top/Article/details/gtggfyjapa.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jyoumei.cn/Article/details/gtttimytup.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.snrcjt.cn/Article/details/gtpfkzopqb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxinkj.top/Article/details/gtcfnsgtri.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gtiqvbtotx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinqigufen.top/Article/details/gttdfobqpi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cheryme.top/Article/details/gtpwtwjmxj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenjidiqi.icu/Article/details/gttqvdvxfe.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtnqwchcqk.html

[L06] 解析响应为 JSON
来源：http://dali.ybcxt.top/Article/details/gtvjtsadxh.html

Py:   resp.json()
来源：http://dali.aibaodan.cn/Article/details/gtacacsiad.html

PHP:  json_decode($body, true);
来源：http://dali.jinqigufen.top/Article/details/gtupsjgrcr.html

JS:   await resp.json()
来源：http://dali.svipenyu.cn/Article/details/gtnncaestl.html

TS:   await resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gtxxluyned.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.iojbl.cn/Article/details/gthyvzbxyp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yanxiufei.cn/Article/details/gtopjrazar.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtngbctmed.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.bjfxy.top/Article/details/gtcijixdso.html

[L07] 处理 HTTP 状态码
来源：http://dali.ivvv.top/Article/details/gtwcqwujav.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tian-w.cn/Article/details/gtsxrozeov.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yongpay.top/Article/details/gtoyaeixar.html

JS:   resp.ok;  resp.status
来源：http://dali.ydzc1.top/Article/details/gtzunsjepz.html

TS:   resp.ok;  resp.status
来源：http://dali.xinyue.icu/Article/details/gtbjfkwhsu.html

Java: resp.statusCode()
来源：http://dali.ydzc1.top/Article/details/gtkrtqtine.html

Go:   resp.StatusCode
来源：http://dali.daria6918.cn/Article/details/gtkkltccig.html

Ruby: resp.code.to_i
来源：http://dali.316326.xyz/Article/details/gtftnvodbg.html

C#:   (int)resp.StatusCode
来源：http://dali.jiagoushi.top/Article/details/gtspalwgds.html

[L08] 并发请求多个地址
来源：http://dali.svipenyu.cn/Article/details/gtrbejoafe.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhongyouzk.top/Article/details/gtbtsdyvrz.html

PHP:  curl_multi_init() 系列
来源：http://dali.xziqi.cn/Article/details/gtvjeosirc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gtsiuxutgz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gtkilczqwo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sxryk.cn/Article/details/gtntlniacj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cheryme.top/Article/details/gtofyiykli.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.andypj.xyz/Article/details/gtoyjhlojv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cucudq.cn/Article/details/gtlxluxbqg.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtymhygejc.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxxpvuza.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtudwjmudl.html

[M01] 读取命令行参数
来源：http://dali.andypj.xyz/Article/details/gtlijkirlr.html

Py:   sys.argv[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtujojuuow.html

PHP:  $argv;  $argc;
来源：http://dali.fzhhl.top/Article/details/gttsnqmiem.html

JS:   process.argv.slice(2)
来源：http://dali.fengsongda.top/Article/details/gthyxybsdi.html

TS:   process.argv.slice(2)
来源：http://dali.haohaochexian.top/Article/details/gtfbkmbonp.html

Java: args 数组（main 方法参数）
来源：http://dali.daxiang520.top/Article/details/gtcpzsfytz.html

Go:   os.Args[1:]
来源：http://dali.svipenyu.cn/Article/details/gtshdpjiov.html

Ruby: ARGV
来源：http://dali.xylfe.cn/Article/details/gtdgjmblef.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cdnleiting.top/Article/details/gtlaeeqnqv.html

[M02] 读取环境变量
来源：http://dali.yvedp.cn/Article/details/gtmkhykjco.html

Py:   os.environ.get("HOME")
来源：http://dali.daxiang520.top/Article/details/gtazomoxml.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzgycbioq.html

JS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gtkfmhoczu.html

TS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gtizbuguvc.html

Java: System.getenv("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtpcncynks.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yueranfly.top/Article/details/gtkxvvqsnb.html

Ruby: ENV["HOME"]
来源：http://dali.ppjwa.cn/Article/details/gtenaaffhp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yuxming.cn/Article/details/gtuabsrlif.html

[M03] 执行外部命令
来源：http://dali.nanxuanxn.top/Article/details/gtxuvxexyv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtborigsji.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.birdmap.top/Article/details/gtobdilwai.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtmeyijgnl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gtiofmznva.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sweek.top/Article/details/gtiqasgrfh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gotoacloud.top/Article/details/gtmerllcvm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shangyingyoupin.top/Article/details/gtovmxfnfv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtczqsocwy.html

[M04] 获取当前工作目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtbiqfhntc.html

Py:   os.getcwd()
来源：http://dali.gotoacloud.top/Article/details/gtwpuwolzd.html

PHP:  getcwd();
来源：http://dali.andypj.xyz/Article/details/gthuzgildv.html

JS:   process.cwd()
来源：http://dali.gzhubu.top/Article/details/gtcdfscwbh.html

TS:   process.cwd()
来源：http://dali.gogol.net.cn/Article/details/gthiswfqlz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwkijzxom.html

Go:   os.Getwd()
来源：http://dali.guannengcc.top/Article/details/gtmlwheapp.html

Ruby: Dir.pwd
来源：http://dali.jqgufenzy.top/Article/details/gtutmvvxjm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hongshengwenyu.top/Article/details/gtmrglfzru.html

[M05] 设置退出码
来源：http://dali.birdmap.top/Article/details/gtpihijkyj.html

Py:   sys.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtenvsodkf.html

PHP:  exit(1);
来源：http://dali.shanyushiyangtech.top/Article/details/gttoyskbqo.html

JS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gtipstyxzg.html

TS:   process.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtnqwvpdch.html

Java: System.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhowdodf.html

Go:   os.Exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtlpbatuej.html

Ruby: exit 1
来源：http://dali.svipenyu.cn/Article/details/gtlrygaflf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dashuyun.cn/Article/details/gttkkmonvv.html

[M06] 向标准错误输出
来源：http://dali.sweek.top/Article/details/gtpglemfmd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhiwuduotai.top/Article/details/gtxmnbiehl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yvedp.cn/Article/details/gtymzoqyfk.html

JS:   console.error("err")
来源：http://dali.aizwys.cn/Article/details/gtspmzdsge.html

TS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gtlecdnuyh.html

Java: System.err.println("err")
来源：http://dali.ybcxt.top/Article/details/gtvpoeshep.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.guannengcc.top/Article/details/gtjpgzgmwz.html

Ruby: warn "err"
来源：http://dali.tianlin.xyz/Article/details/gtokagycoe.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtohgxroda.html

[M07] 判断是否为主入口
来源：http://dali.yvedp.cn/Article/details/gtjhinzehe.html

Py:   if __name__ == "__main__":
来源：http://dali.yueranfly.top/Article/details/gtwgvyfuru.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yvedp.cn/Article/details/gtdejvmdex.html

JS:   require.main === module
来源：http://dali.sufxvd.cn/Article/details/gtnxlmsyax.html

TS:   require.main === module
来源：http://dali.hfpthk.cn/Article/details/gtwyponfyr.html

Java: public static void main(String[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gtxfodxkum.html

Go:   func main()
来源：http://dali.wangshuangyany.cn/Article/details/gtlslmubnu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hammf.cn/Article/details/gtmbtjsedi.html

C#:   static void Main(string[] args)
来源：http://dali.0kj1m.cn/Article/details/gtqfkcnwhz.html

[M08] 获取系统与运行时信息
来源：http://dali.shangyingyoupin.top/Article/details/gthiiiglgm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.andypj.xyz/Article/details/gtxwactpxq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cqqwz.cn/Article/details/gtzummxdds.html

JS:   process.platform;  process.version
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdborkvyx.html

TS:   process.platform;  process.version
来源：http://dali.yuanzhike.top/Article/details/gtslgxbuma.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cheryme.top/Article/details/gtpepjdszw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yonumen.top/Article/details/gtarrmgfex.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sweek.top/Article/details/gtejjhkhhp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guowangkeji.top/Article/details/gtjadsyvnz.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtgzovznpj.html

N. 数据结构与算法
来源：http://dali.hammf.cn/Article/details/gtiheoghho.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtckeydhcx.html

[N01] 二分查找（有序数组）
来源：http://dali.chenzaomai.com/Article/details/gtrrmfcgjl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtdmsxsutp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gtaldlirbi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgfzy.top/Article/details/gtjgsbycnr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuanzx.com/Article/details/gtpobkefqz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtsdcahjkq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtsqllkehf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.vqdsnc.cn/Article/details/gtzjbfaeho.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.birdmap.top/Article/details/gteuratckg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigufen.top/Article/details/gtfikiaara.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gtsycjomzc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sufxvd.cn/Article/details/gtjosgnged.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gtdnhtehld.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yangfankeji.com/Article/details/gtdmdkcmye.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xinyue.icu/Article/details/gtctiqirqb.html

Go:   slices.Sort(arr)
来源：http://dali.cqqwz.cn/Article/details/gttmpcclfb.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gthzoegaui.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuetiantiany.cn/Article/details/gtfvkaxpbw.html

[N03] 快速排序（分治示例）
来源：http://dali.cucudq.cn/Article/details/gtwvgfmrvu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.daria6918.cn/Article/details/gtfbwzmfre.html

PHP:  // 递归实现，或用 usort
来源：http://dali.wangshuangyany.cn/Article/details/gtgwxfjddu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gtdcjnrqbs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigfzy.top/Article/details/gtavvnurjc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xinyue.icu/Article/details/gtlasyybig.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.daxiang520.top/Article/details/gtrzqaiwpy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.havefunace.top/Article/details/gtptfykjfd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tian-w.cn/Article/details/gtmquofrew.html

[N04] 斐波那契数列
来源：http://dali.zdqjudy.top/Article/details/gtdvllxyek.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqvdwbplc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.bjfxy.top/Article/details/gtufzijolp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlqyumsom.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnesqtqpa.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gotoacloud.top/Article/details/gtiudlabsy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.haohaochexian.top/Article/details/gtuziukryi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.wangdashe.top/Article/details/gtgapsspro.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gtyvsrskqe.html

[N05] 最大公约数
来源：http://dali.redwolf501.top/Article/details/gtaxqmmoka.html

Py:   math.gcd(a, b)
来源：http://dali.xinyue.icu/Article/details/gtmfmcmfor.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnqzz.top/Article/details/gtlprybtmt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gtflmaaafz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhixingplan.top/Article/details/gtzqpqnuzt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.svipenyu.cn/Article/details/gtzsulqrgz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sufxvd.cn/Article/details/gtebjlnnhm.html

Ruby: a.gcd(b)
来源：http://dali.fengsongda.top/Article/details/gttwfrjpqe.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.svipenyu.cn/Article/details/gtrroexknj.html

[N06] 判断回文字符串
来源：http://dali.yangfankeji.com/Article/details/gtfcngxxmj.html

Py:   s == s[::-1]
来源：http://dali.feifeiyinyue.top/Article/details/gtlvtshnfk.html

PHP:  $s === strrev($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmlxabqpr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtmqnzsyno.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtvpuifeuw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.kuanghao11.cn/Article/details/gtiyvelbip.html

Go:   // 双指针从两端比较
来源：http://dali.ivvv.top/Article/details/gtzqkzoavp.html

Ruby: s == s.reverse
来源：http://dali.iojbl.cn/Article/details/gtmzkfgpei.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmirjqsb.html

[N07] 两数之和（返回下标）
来源：http://dali.xinyue.icu/Article/details/gtrzfnemtf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xuanzx.com/Article/details/gtztgykahy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhiwuduotai.top/Article/details/gtkwdoprsf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sxryk.cn/Article/details/gtvvhybxmo.html

TS:   // 手写 Map<string, number>
来源：http://dali.yangfankeji.com/Article/details/gtdomnbrcm.html

Java: // 手写 HashMap
来源：http://dali.meibo888.top/Article/details/gtgnmesdic.html

Go:   // 手写 map[int]int
来源：http://dali.jyoumei.cn/Article/details/gtkdfmttoz.html

Ruby: // 手写 Hash
来源：http://dali.nanxuanxn.top/Article/details/gtlizjaxty.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuanzx.com/Article/details/gthoivmjes.html

[N08] 生成全排列
来源：http://dali.ybcxt.top/Article/details/gtcoyuyzvr.html

Py:   itertools.permutations(arr)
来源：http://dali.gzhubu.top/Article/details/gtholhioiy.html

PHP:  // 手写递归交换
来源：http://dali.yj20258.top/Article/details/gtlgdjswwz.html

JS:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwxfcdhne.html

TS:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtdtxhdsip.html

Java: // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtwnratgkw.html

Go:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gtoyfnnabd.html

Ruby: arr.permutation.to_a
来源：http://dali.chenjidiqi.icu/Article/details/gtogotrphd.html

C#:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtgbdnimsc.html

[N09] 栈与队列
来源：http://dali.tian-w.cn/Article/details/gtwdhotyhk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.tian-w.cn/Article/details/gtlzurdfyn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gtwcsbfiae.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gttegtvudh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ybcxt.top/Article/details/gtneqowhfv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hnqzz.top/Article/details/gttyzmldix.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ivvv.top/Article/details/gtirshkews.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gtqaoqcpzk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbntafzxt.html

[N10] 链表节点定义
来源：http://dali.xuetiantiany.cn/Article/details/gtrrvfgbil.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.guannengcc.top/Article/details/gtfnaiyjfd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sufxvd.cn/Article/details/gtktnmuccv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hnqzz.top/Article/details/gttpxyipen.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthejicxgz.html

Java: class Node { int v; Node next; }
来源：http://dali.nanxinkj.top/Article/details/gtdahybskm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.wangshuangyany.cn/Article/details/gtsrbjdeze.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.aibaodan.cn/Article/details/gtnwycqeyi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tian-w.cn/Article/details/gtisepcxbj.html

[N11] 二叉树中序遍历
来源：http://dali.shzxlz.cn/Article/details/gtmlhtdrex.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shzxlz.cn/Article/details/gtyhpmtajs.html

PHP:  // 手写递归函数
来源：http://dali.redwolf501.top/Article/details/gtzcpsmzbn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tian-w.cn/Article/details/gtzkrbvauh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.feifeiyinyue.top/Article/details/gtfjjqlina.html

Java: // 手写递归
来源：http://dali.xziqi.cn/Article/details/gtiiabcdiu.html

Go:   // 手写递归
来源：http://dali.sysykeji.top/Article/details/gtazxeiyzl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxrltdoxu.html

C#:   // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gtahcsoric.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cqqwz.cn/Article/details/gtoxixmovf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cdnleiting.top/Article/details/gtudgdeptg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.birdmap.top/Article/details/gtqoytqufk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gtznsyjkpu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cqqwz.cn/Article/details/gtfqmufmnu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yangfankeji.com/Article/details/gtiwopfwbi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinqigfzy.top/Article/details/gtuhmpyzib.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nanxuanxn.top/Article/details/gtucknolnr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jianghu66.top/Article/details/gtoioxlidc.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoonfflsh.html

O. 并发与异步
来源：http://dali.tian-w.cn/Article/details/gtryitkfdz.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtuxuzywfr.html

[O01] 启动一个线程
来源：http://dali.316326.xyz/Article/details/gtldwfpmmo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sysykeji.top/Article/details/gtaauuyawz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nanxuanxn.top/Article/details/gtkawvubmt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhengqikj.top/Article/details/gttkeroysw.html

TS:   // 同 JS
来源：http://dali.gotoacloud.top/Article/details/gtrkvedxgz.html

Java: new Thread(() -> f()).start()
来源：http://dali.quarkkingdee.top/Article/details/gtkcklhgad.html

Go:   go f()
来源：http://dali.c1oappe.top/Article/details/gtoahqgkdm.html

Ruby: Thread.new { f }
来源：http://dali.9152youxi.cn/Article/details/gtyxkirvbb.html

C#:   Task.Run(() => F());
来源：http://dali.sufxvd.cn/Article/details/gthgpolgxf.html

[O02] 使用线程池
来源：http://dali.ybcxt.top/Article/details/gtbigpvdgg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hongshengwenyu.top/Article/details/gtmomknajx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangtech.top/Article/details/gtzpsjfcqp.html

JS:   // worker_threads 线程池
来源：http://dali.cucudq.cn/Article/details/gtlezzdanq.html

TS:   // worker_threads 线程池
来源：http://dali.gogol.net.cn/Article/details/gtsobpfycn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xinyue.icu/Article/details/gtlspqsxgh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jqgfzy.top/Article/details/gtujzypwab.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tianlin.xyz/Article/details/gtzuhpasmo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hongshengwenyu.top/Article/details/gtmbkyvrng.html

[O03] 加锁保护共享数据
来源：http://dali.xylfe.cn/Article/details/gtiyxelswc.html

Py:   with lock: shared += 1
来源：http://dali.zhengqikj.top/Article/details/gtgcxdypof.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gogol.net.cn/Article/details/gtjnoukpnx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmfhrpnwo.html

TS:   // 同 JS
来源：http://dali.ppjwa.cn/Article/details/gtbacdrfzn.html

Java: synchronized (this) { shared++; }
来源：http://dali.yvedp.cn/Article/details/gtvxocqwfh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.pengpengdd.cyou/Article/details/gtwbwtiwaa.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sufxvd.cn/Article/details/gtqpljrvmz.html

C#:   lock (gate) { shared++; }
来源：http://dali.c1oappe.top/Article/details/gtiiaxtjlj.html

[O04] 定义异步函数并等待
来源：http://dali.tanke756.top/Article/details/gtgnaakdha.html

Py:   async def f():⏎    await g()
来源：http://dali.kuanghao11.cn/Article/details/gtxyeecyjx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cdnleiting.top/Article/details/gtcfrhpcig.html

JS:   async function f() { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gtibobnjmf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.guannengcc.top/Article/details/gtkkhixloy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shanyushiyangtech.top/Article/details/gtxesrgsgm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cheryme.top/Article/details/gtclzsocja.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.feifeiyinyue.top/Article/details/gttptdkadc.html

C#:   async Task F() { await G(); }
来源：http://dali.daxiang520.top/Article/details/gtmhdaouzh.html

[O05] 并发执行并等待全部完成
来源：http://dali.bjfxy.top/Article/details/gtnlfdimgp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhengqikj.top/Article/details/gtihingnhm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.pycfn.com/Article/details/gtamzannfl.html

JS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gtsrxzpndj.html

TS:   await Promise.all(tasks)
来源：http://dali.jqgfzy.top/Article/details/gtswgjeobz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jqgufenzy.top/Article/details/gtzbztcrch.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hnxiangtu.top/Article/details/gtjnibknmp.html

Ruby: threads.map(&:join)
来源：http://dali.sxryk.cn/Article/details/gtylakxixb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cqqwz.cn/Article/details/gthztpwhaz.html

[O06] 使用进程池
来源：http://dali.tanke756.top/Article/details/gtfytzdsfy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cdnleiting.top/Article/details/gtyugxzuae.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jlsjyb.cn/Article/details/gtucnqvnif.html

JS:   // child_process / cluster 模块
来源：http://dali.yonumen.top/Article/details/gtkgsadxiq.html

TS:   // child_process / cluster 模块
来源：http://dali.jlsjyb.cn/Article/details/gtrzovalpm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yanxiufei.cn/Article/details/gtnkyqltvh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhngbsxw.html

Ruby: // fork 块
来源：http://dali.316326.xyz/Article/details/gtmoopsdnn.html

C#:   Parallel.For
来源：http://dali.jinghuilouyu.cn/Article/details/gtnzeqfzug.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtagoqxhxq.html

P. 常用工具函数
来源：http://dali.redwolf501.top/Article/details/gtwhgebtse.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtejdqeykq.html

[P01] 生成 UUID
来源：http://dali.yanxiufei.cn/Article/details/gtdtlgpuvo.html

Py:   str(uuid.uuid4())
来源：http://dali.chenlongwang.top/Article/details/gtwyfggrqy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shzxlz.cn/Article/details/gtxjlcppal.html

JS:   crypto.randomUUID()
来源：http://dali.haohaochexian.top/Article/details/gtjgasmhvg.html


<!-- 参考信息 -->