代发 wailian999

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jqgufenzy.top/Article/details/gtqecxjmde.html

[L04] 设置超时
来源：http://dali.yanxiufei.cn/Article/details/gtdmtigoho.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ydzc1.top/Article/details/gtvjrlkwqr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xylfe.cn/Article/details/gtljyyktjj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gtiwrtetkk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhengqikj.top/Article/details/gtyicghqdt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.9152youxi.cn/Article/details/gtlftottue.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yuanzhike.top/Article/details/gtgkirbaie.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yonumen.top/Article/details/gtmqnqtgaj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jqgufenzy.top/Article/details/gtpwnvcrhr.html

[L05] 上传文件（multipart）
来源：http://dali.sysykeji.top/Article/details/gtadmvilvo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.feifeiyinyue.top/Article/details/gtnsqobkfb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenjidiqi.icu/Article/details/gtnjhvsexj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gtsjgbiflx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinghuilouyu.cn/Article/details/gtidwvpdil.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.kuanghao11.cn/Article/details/gtbbbuquaj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.wangshuangyany.cn/Article/details/gtqobeinev.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.birdmap.top/Article/details/gtbbzlquwn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtmnocyyfj.html

[L06] 解析响应为 JSON
来源：http://dali.xuanzx.com/Article/details/gtyhnoeumg.html

Py:   resp.json()
来源：http://dali.yj20258.top/Article/details/gtxygzsduk.html

PHP:  json_decode($body, true);
来源：http://dali.meibo888.top/Article/details/gtiahrxsox.html

JS:   await resp.json()
来源：http://dali.shzxlz.cn/Article/details/gtdhcakvyv.html

TS:   await resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gtgamfpuft.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xziqi.cn/Article/details/gtzwpphjfl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhengqikj.top/Article/details/gtvooquceo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.havefunace.top/Article/details/gtpmmqryfy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gtaeczbzja.html

[L07] 处理 HTTP 状态码
来源：http://dali.sweek.top/Article/details/gtjudtkycb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.wangshuangyany.cn/Article/details/gtwijzieqy.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yongpay.top/Article/details/gtezvdjpfj.html

JS:   resp.ok;  resp.status
来源：http://dali.c1oappe.top/Article/details/gtzfavyazj.html

TS:   resp.ok;  resp.status
来源：http://dali.tian-w.cn/Article/details/gtwmdhjnav.html

Java: resp.statusCode()
来源：http://dali.yangfankeji.com/Article/details/gtfdjytdmy.html

Go:   resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gttmbinusv.html

Ruby: resp.code.to_i
来源：http://dali.shuidangran.top/Article/details/gtudvrpepl.html

C#:   (int)resp.StatusCode
来源：http://dali.havefunace.top/Article/details/gtmbqttwbn.html

[L08] 并发请求多个地址
来源：http://dali.hnqzz.top/Article/details/gtbhslpdau.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cucudq.cn/Article/details/gteflepdzo.html

PHP:  curl_multi_init() 系列
来源：http://dali.shanyushiyangtech.top/Article/details/gttywqsoto.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gtzctsklio.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cdnleiting.top/Article/details/gtksglsppm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangdashe.top/Article/details/gtbovqdwgl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tianlin.xyz/Article/details/gtwekijuyw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyygrmlrl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yongpay.top/Article/details/gtlokrodaa.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtfbhrvqkz.html

M. 命令行 / 进程 / 环境
来源：http://dali.316326.xyz/Article/details/gtdmgaajuj.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gteehgfuqq.html

[M01] 读取命令行参数
来源：http://dali.chenlongwang.top/Article/details/gtkcxlqipy.html

Py:   sys.argv[1:]
来源：http://dali.yanxiufei.cn/Article/details/gtmiqxuwsy.html

PHP:  $argv;  $argc;
来源：http://dali.zycfv.cn/Article/details/gtvfihevef.html

JS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gtxzrwdmhf.html

TS:   process.argv.slice(2)
来源：http://dali.fzhhl.top/Article/details/gtiourdotv.html

Java: args 数组（main 方法参数）
来源：http://dali.yvedp.cn/Article/details/gtbcehjvrt.html

Go:   os.Args[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqfzrila.html

Ruby: ARGV
来源：http://dali.ybcxt.top/Article/details/gtnytnzbds.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdfrezbg.html

[M02] 读取环境变量
来源：http://dali.yanxiufei.cn/Article/details/gtxmwvjmno.html

Py:   os.environ.get("HOME")
来源：http://dali.yonumen.top/Article/details/gtkbmmpcug.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gtubfipcqe.html

JS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gtawhcdmmb.html

TS:   process.env.HOME
来源：http://dali.quarkkingdee.top/Article/details/gtqgpkehhc.html

Java: System.getenv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtpthnpqzu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtqfuqxqed.html

Ruby: ENV["HOME"]
来源：http://dali.316326.xyz/Article/details/gtsxxffvld.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yongpay.top/Article/details/gtgnanpaxb.html

[M03] 执行外部命令
来源：http://dali.hnqzz.top/Article/details/gtqnjeewhp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtqnemghhs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jianghu66.top/Article/details/gtcbqvxeub.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkswpujdu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtoklnqwnr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhixingplan.top/Article/details/gtafxxordi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.9152youxi.cn/Article/details/gtaxagpmxq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yongpay.top/Article/details/gttyqfembv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ivvv.top/Article/details/gtrwmazxuy.html

[M04] 获取当前工作目录
来源：http://dali.shuidangran.top/Article/details/gtowfzglvu.html

Py:   os.getcwd()
来源：http://dali.jianghu66.top/Article/details/gtvyzgqjch.html

PHP:  getcwd();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbkdykazi.html

JS:   process.cwd()
来源：http://dali.aizwys.cn/Article/details/gtjtercczt.html

TS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gtgygxnkpn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ivvv.top/Article/details/gttmwoxsvn.html

Go:   os.Getwd()
来源：http://dali.gogol.net.cn/Article/details/gtlrhbztpv.html

Ruby: Dir.pwd
来源：http://dali.guowangkeji.top/Article/details/gteapqvdss.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xinyue.icu/Article/details/gtuofnnrfh.html

[M05] 设置退出码
来源：http://dali.yj20258.top/Article/details/gtoaoglnpe.html

Py:   sys.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtuonrbwyv.html

PHP:  exit(1);
来源：http://dali.dashuyun.cn/Article/details/gtqeaqprev.html

JS:   process.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpzzfvbok.html

TS:   process.exit(1)
来源：http://dali.yongpay.top/Article/details/gtwvusqqxa.html

Java: System.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyluznhed.html

Go:   os.Exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtzfqxrbyo.html

Ruby: exit 1
来源：http://dali.andypj.xyz/Article/details/gtmkyonmie.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xinyue.icu/Article/details/gtceijlggv.html

[M06] 向标准错误输出
来源：http://dali.zdqjudy.top/Article/details/gtpqegrdbw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.meibo888.top/Article/details/gttzedywxm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hfpthk.cn/Article/details/gtortkbczw.html

JS:   console.error("err")
来源：http://dali.vqdsnc.cn/Article/details/gtykixbzqe.html

TS:   console.error("err")
来源：http://dali.guannengcc.top/Article/details/gtxeztixkj.html

Java: System.err.println("err")
来源：http://dali.yvedp.cn/Article/details/gtqzzsyjtb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cucudq.cn/Article/details/gtozggotuz.html

Ruby: warn "err"
来源：http://dali.zhoulong.xyz/Article/details/gtfvdwfacx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sxryk.cn/Article/details/gtrzssflyn.html

[M07] 判断是否为主入口
来源：http://dali.quarkkingdee.top/Article/details/gtvsntiyec.html

Py:   if __name__ == "__main__":
来源：http://dali.316326.xyz/Article/details/gtuhzrgsxr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gthyidjybe.html

JS:   require.main === module
来源：http://dali.ehwqpu.com/Article/details/gtxezkxbpt.html

TS:   require.main === module
来源：http://dali.shuidangran.top/Article/details/gtcfcxvgle.html

Java: public static void main(String[] args)
来源：http://dali.sxryk.cn/Article/details/gtvejzjdav.html

Go:   func main()
来源：http://dali.wangshuangyany.cn/Article/details/gtmiswnmgt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sysykeji.top/Article/details/gtcuychzna.html

C#:   static void Main(string[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwkbxbyef.html

[M08] 获取系统与运行时信息
来源：http://dali.c1oappe.top/Article/details/gtklfzmbvq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.pycfn.com/Article/details/gtgikzfxmb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zycfv.cn/Article/details/gteegflnup.html

JS:   process.platform;  process.version
来源：http://dali.0kj1m.cn/Article/details/gtdcfgbzrn.html

TS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gtuilvlalh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jiagoushi.top/Article/details/gtcjntlizb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.smart0.xyz/Article/details/gtlybebvsz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tanke756.top/Article/details/gtzkknwhxt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.fengsongda.top/Article/details/gtahkngwek.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtrsbxligs.html

N. 数据结构与算法
来源：http://dali.jqgfzy.top/Article/details/gtzcfbpwgv.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmwjlsauf.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigufen.top/Article/details/gtqyxwygbi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hammf.cn/Article/details/gtnqtmmqpn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.guannengcc.top/Article/details/gtzhwitroq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gtrzgdtbri.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shzxlz.cn/Article/details/gtdnlnxwff.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtzrirpcal.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtjwymdjdm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.kuanghao11.cn/Article/details/gtezckeuxd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtnkjhbfdy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.dashuyun.cn/Article/details/gtzhorbklp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.meibo888.top/Article/details/gtndgrrhyd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.guannengcc.top/Article/details/gtoemvikvy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgfzy.top/Article/details/gtearlhquh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gtesdcqcnd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.daria6918.cn/Article/details/gttgqqvutj.html

Go:   slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gtbrrhuesh.html

Ruby: arr.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwuwvbzej.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nanxinkj.top/Article/details/gtymxidqbj.html

[N03] 快速排序（分治示例）
来源：http://dali.aizwys.cn/Article/details/gtwkalehdm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.kuanghao11.cn/Article/details/gtjqkgqyji.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xylfe.cn/Article/details/gtwqvyocwk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hammf.cn/Article/details/gtvwaehltp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yueranfly.top/Article/details/gtadmbjhar.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zycfv.cn/Article/details/gtaobkzycw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ybcxt.top/Article/details/gtybypsqoy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.iojbl.cn/Article/details/gtbhvqoodp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yanxiufei.cn/Article/details/gtgmzgxfbn.html

[N04] 斐波那契数列
来源：http://dali.xuanzx.com/Article/details/gtwcnytmvi.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigfzy.top/Article/details/gthvqdgyez.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zdqjudy.top/Article/details/gtvbfrofos.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtgajcejsv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gtevimugzq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqovilxkx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cdnleiting.top/Article/details/gtqadsnmxa.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.guowangkeji.top/Article/details/gtxzxytvwm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gtzkcsawqp.html

[N05] 最大公约数
来源：http://dali.daxiang520.top/Article/details/gtnmktaanu.html

Py:   math.gcd(a, b)
来源：http://dali.ydzc1.top/Article/details/gtkuesuorq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cheryme.top/Article/details/gtstqozrum.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gtjgbbwten.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.0kj1m.cn/Article/details/gtsmdxtsoo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yuanzhike.top/Article/details/gtdgwdcdfa.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.meibo888.top/Article/details/gtmpezdkwf.html

Ruby: a.gcd(b)
来源：http://dali.svipenyu.cn/Article/details/gtljnuwptb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.meibo888.top/Article/details/gtboenxvfy.html

[N06] 判断回文字符串
来源：http://dali.haohaochexian.top/Article/details/gttclsvalq.html

Py:   s == s[::-1]
来源：http://dali.cucudq.cn/Article/details/gtnnapzyjo.html

PHP:  $s === strrev($s);
来源：http://dali.nanxuanxn.top/Article/details/gtwjdqpwub.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfcubrdie.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gtupkcxvxw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.wangshuangyany.cn/Article/details/gtnglzbwwy.html

Go:   // 双指针从两端比较
来源：http://dali.hammf.cn/Article/details/gtpjcmmteg.html

Ruby: s == s.reverse
来源：http://dali.guannengcc.top/Article/details/gtivwwyrku.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ppjwa.cn/Article/details/gtnqfqodtu.html

[N07] 两数之和（返回下标）
来源：http://dali.yonumen.top/Article/details/gtyowqaimg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sweek.top/Article/details/gtfhelwiob.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.pycfn.com/Article/details/gttahnozre.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ivvv.top/Article/details/gtqfplyife.html

TS:   // 手写 Map<string, number>
来源：http://dali.jqgufenzy.top/Article/details/gtnhohvanh.html

Java: // 手写 HashMap
来源：http://dali.ywan-chungtsiang.top/Article/details/gtylcidast.html

Go:   // 手写 map[int]int
来源：http://dali.ivvv.top/Article/details/gtppealzsw.html

Ruby: // 手写 Hash
来源：http://dali.hnqzz.top/Article/details/gtksefegka.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ywan-chungtsiang.top/Article/details/gtczzphucs.html

[N08] 生成全排列
来源：http://dali.tian-w.cn/Article/details/gtwenwpprb.html

Py:   itertools.permutations(arr)
来源：http://dali.tanke756.top/Article/details/gtrtvskkvu.html

PHP:  // 手写递归交换
来源：http://dali.dashuyun.cn/Article/details/gtqlnnhaue.html

JS:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvyexezoa.html

TS:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtmuxjfnfz.html

Java: // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtdwpsznqc.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtnufqtkzw.html

Ruby: arr.permutation.to_a
来源：http://dali.haohaochexian.top/Article/details/gtuvtltayb.html

C#:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtykndjefo.html

[N09] 栈与队列
来源：http://dali.chenzaomai.com/Article/details/gtqzryjolb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hammf.cn/Article/details/gtqzfusloj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gtuuqqdhjn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gtgfqugkdt.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.iojbl.cn/Article/details/gthmrnofja.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.quarkkingdee.top/Article/details/gtusyhdtqr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yangfankeji.com/Article/details/gttmjdsrmj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gtamsjfmah.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.bjfxy.top/Article/details/gtofhodnqa.html

[N10] 链表节点定义
来源：http://dali.fzhhl.top/Article/details/gtbnxgfoor.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gaohongyu789.top/Article/details/gtiyrlrrbe.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinqigfzy.top/Article/details/gtyqowxwzg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hammf.cn/Article/details/gtkntgospx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ppjwa.cn/Article/details/gtvnwzvrbo.html

Java: class Node { int v; Node next; }
来源：http://dali.jiagoushi.top/Article/details/gtwrqmbzol.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cqqwz.cn/Article/details/gtateshqmd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.kuanghao11.cn/Article/details/gtcjrslkqb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.birdmap.top/Article/details/gtpshyxiam.html

[N11] 二叉树中序遍历
来源：http://dali.9152youxi.cn/Article/details/gtaunokaax.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.fzhhl.top/Article/details/gtnpozbyos.html

PHP:  // 手写递归函数
来源：http://dali.nanxinkj.top/Article/details/gtpgzoctrw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj202588.top/Article/details/gtcbdpyobb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.316326.xyz/Article/details/gtspdjjmmy.html

Java: // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gtwtxesliw.html

Go:   // 手写递归
来源：http://dali.hammf.cn/Article/details/gtezrxtmep.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhengqikj.top/Article/details/gtncexbdtj.html

C#:   // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gtejdtdddv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfgdbgbhx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gtbiajqvah.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cucudq.cn/Article/details/gtmgdkcbxn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.birdmap.top/Article/details/gtklewsdvs.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ybcxt.top/Article/details/gtvnzpyqmf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.vqdsnc.cn/Article/details/gtgvkighek.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ppjwa.cn/Article/details/gtzwqidqcl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xziqi.cn/Article/details/gtlygwqtmx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yueranfly.top/Article/details/gtkxglsqdx.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtxjkzjmjl.html

O. 并发与异步
来源：http://dali.nanxinkj.top/Article/details/gtdgzgxvti.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtjaheojox.html

[O01] 启动一个线程
来源：http://dali.shzxlz.cn/Article/details/gtlxvkvtnt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tianlin.xyz/Article/details/gtlgbqlsal.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yanxiufei.cn/Article/details/gtimwciohq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jqgfzy.top/Article/details/gtvhirwqya.html

TS:   // 同 JS
来源：http://dali.kuanghao11.cn/Article/details/gtvbltsewa.html

Java: new Thread(() -> f()).start()
来源：http://dali.bjfxy.top/Article/details/gtwmyzdnuq.html

Go:   go f()
来源：http://dali.xinyue.icu/Article/details/gttinaujjw.html

Ruby: Thread.new { f }
来源：http://dali.yj202588.top/Article/details/gtjjgnzgln.html

C#:   Task.Run(() => F());
来源：http://dali.hnqzz.top/Article/details/gtpporadmu.html

[O02] 使用线程池
来源：http://dali.sufxvd.cn/Article/details/gteoalbyjf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.fengsongda.top/Article/details/gtabtckbyh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gtrgjrpgmk.html

JS:   // worker_threads 线程池
来源：http://dali.feifeiyinyue.top/Article/details/gtevesarsn.html

TS:   // worker_threads 线程池
来源：http://dali.yj20258888.top/Article/details/gtcwmdrwoh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hongshengwenyu.top/Article/details/gtytptyrec.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nwbrower.top/Article/details/gtbxoygjvf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yonumen.top/Article/details/gtmwuwlred.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.0kj1m.cn/Article/details/gtkriwwkdw.html

[O03] 加锁保护共享数据
来源：http://dali.jqgfzy.top/Article/details/gthklnmsfc.html

Py:   with lock: shared += 1
来源：http://dali.jianghu66.top/Article/details/gtjkmsevjj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhengqikj.top/Article/details/gtetgxyiga.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj202588.top/Article/details/gtrzuxsxgn.html

TS:   // 同 JS
来源：http://dali.zdqjudy.top/Article/details/gtrpybevzh.html

Java: synchronized (this) { shared++; }
来源：http://dali.havefunace.top/Article/details/gtpwlxuwdy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.bjfxy.top/Article/details/gtpmimcxgb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jlsjyb.cn/Article/details/gtuuhzqzie.html

C#:   lock (gate) { shared++; }
来源：http://dali.jqgfzy.top/Article/details/gtcqexkjio.html

[O04] 定义异步函数并等待
来源：http://dali.sysykeji.top/Article/details/gtuwqymvzr.html

Py:   async def f():⏎    await g()
来源：http://dali.andypj.xyz/Article/details/gtfbugbhrr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.kuanghao11.cn/Article/details/gtnzhltjsf.html

JS:   async function f() { await g(); }
来源：http://dali.yanxiufei.cn/Article/details/gtlbenmggw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.fengsongda.top/Article/details/gtvixpgjxj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jyoumei.cn/Article/details/gtuouqvwfh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.svipenyu.cn/Article/details/gteguqhuog.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hnqzz.top/Article/details/gtghoqzmzm.html

C#:   async Task F() { await G(); }
来源：http://dali.redwolf501.top/Article/details/gthcdsffjx.html

[O05] 并发执行并等待全部完成
来源：http://dali.jiagoushi.top/Article/details/gtkhgifdzg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jlsjyb.cn/Article/details/gtzyomghax.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shzxlz.cn/Article/details/gtflgsdeqx.html

JS:   await Promise.all(tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gtydydhfbm.html

TS:   await Promise.all(tasks)
来源：http://dali.yangfankeji.com/Article/details/gtignviykv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yueranfly.top/Article/details/gthoqogqow.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.0kj1m.cn/Article/details/gtjsdvsrih.html

Ruby: threads.map(&:join)
来源：http://dali.daxiang520.top/Article/details/gtntcrejok.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tanke756.top/Article/details/gtdwvxzmzi.html

[O06] 使用进程池
来源：http://dali.jiagoushi.top/Article/details/gtbhnoqekp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cheryme.top/Article/details/gttqpafqyw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.vqdsnc.cn/Article/details/gtaqtzidth.html

JS:   // child_process / cluster 模块
来源：http://dali.xuanzx.com/Article/details/gtpzhwjrmo.html

TS:   // child_process / cluster 模块
来源：http://dali.mhx1999.top/Article/details/gtrmofwuce.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shangyingyoupin.top/Article/details/gtdrzurcjr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shuidangran.top/Article/details/gtkabiecls.html

Ruby: // fork 块
来源：http://dali.tanke756.top/Article/details/gtwguqexma.html

C#:   Parallel.For
来源：http://dali.daxiang520.top/Article/details/gtsgghdiyl.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtwkxdagod.html

P. 常用工具函数
来源：http://dali.pengpengdd.cyou/Article/details/gtptkykked.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnlitwkk.html

[P01] 生成 UUID
来源：http://dali.wangshuangyany.cn/Article/details/gteqluafbw.html

Py:   str(uuid.uuid4())
来源：http://dali.0kj1m.cn/Article/details/gtwpuanuhp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccgcjedk.html

JS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gtxumomtoq.html

TS:   crypto.randomUUID()
来源：http://dali.chenjidiqi.icu/Article/details/gthpchtnjy.html

Java: UUID.randomUUID().toString()
来源：http://dali.jianghu66.top/Article/details/gtmdnxevxw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cdnleiting.top/Article/details/gtjvxrpxwj.html

Ruby: SecureRandom.uuid
来源：http://dali.xinyue.icu/Article/details/gtjiplatck.html


<!-- 参考信息 -->