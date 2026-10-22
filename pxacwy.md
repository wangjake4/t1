代发 wailian999

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.andypj.xyz/Article/details/gtuezcfzie.html

[L04] 设置超时
来源：http://dali.kuanghao11.cn/Article/details/gtbwxntdre.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nanxuanxn.top/Article/details/gtdsgxahrj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tanke756.top/Article/details/gthcejxbfk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dashuyun.cn/Article/details/gtazivkiga.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jiagoushi.top/Article/details/gtylsamnvb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cheryme.top/Article/details/gtjqvubxud.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dianchejie.cn/Article/details/gtawuhnnai.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258.top/Article/details/gtonnoqmel.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hysaishi.cn/Article/details/gtygbbyovr.html

[L05] 上传文件（multipart）
来源：http://dali.nanxinkj.top/Article/details/gtlhbvwoib.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ppjwa.cn/Article/details/gtyewbzirh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuanzhike.top/Article/details/gtgruwsxui.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigufen.top/Article/details/gtrzpffyat.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gthsdjelki.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnqzz.top/Article/details/gtptxhgnoe.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cdnleiting.top/Article/details/gttnychftk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinghuilouyu.cn/Article/details/gtpckomgbj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtwlimmkyc.html

[L06] 解析响应为 JSON
来源：http://dali.yj20258.top/Article/details/gtlcxjoqga.html

Py:   resp.json()
来源：http://dali.daxiang520.top/Article/details/gtsdpcgqmx.html

PHP:  json_decode($body, true);
来源：http://dali.havefunace.top/Article/details/gtqpynppsv.html

JS:   await resp.json()
来源：http://dali.aizwys.cn/Article/details/gtajyptcvj.html

TS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gtbpvggjzq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shuidangran.top/Article/details/gttgegymqn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guowangkeji.top/Article/details/gtafazskgi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yongpay.top/Article/details/gtzwffgiey.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jyoumei.cn/Article/details/gtzkamgdun.html

[L07] 处理 HTTP 状态码
来源：http://dali.vqdsnc.cn/Article/details/gtloabfmgw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxszxndqn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.kuanghao11.cn/Article/details/gtbtvgallz.html

JS:   resp.ok;  resp.status
来源：http://dali.cheryme.top/Article/details/gtgtacsztd.html

TS:   resp.ok;  resp.status
来源：http://dali.nwbrower.top/Article/details/gtqvoolvrl.html

Java: resp.statusCode()
来源：http://dali.gzhubu.top/Article/details/gtebzkzyov.html

Go:   resp.StatusCode
来源：http://dali.yonumen.top/Article/details/gticvoyguy.html

Ruby: resp.code.to_i
来源：http://dali.guannengcc.top/Article/details/gtshvocqxh.html

C#:   (int)resp.StatusCode
来源：http://dali.yvedp.cn/Article/details/gtkeacljuj.html

[L08] 并发请求多个地址
来源：http://dali.hysaishi.cn/Article/details/gtfvvxyygx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.dianchejie.cn/Article/details/gtdyminntq.html

PHP:  curl_multi_init() 系列
来源：http://dali.ppjwa.cn/Article/details/gtfzfishuf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gtfmgyuomn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gthvchndin.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xylfe.cn/Article/details/gtkloqxkrv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj202588.top/Article/details/gtjhximcft.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.guowangkeji.top/Article/details/gthzofemjk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258.top/Article/details/gtzgwkchkz.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtvqhpevht.html

M. 命令行 / 进程 / 环境
来源：http://dali.ybcxt.top/Article/details/gtdfuazapw.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtzwixelzt.html

[M01] 读取命令行参数
来源：http://dali.haohaochexian.top/Article/details/gtzfchltes.html

Py:   sys.argv[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgyyhipf.html

PHP:  $argv;  $argc;
来源：http://dali.jinqigufen.top/Article/details/gturnqmlep.html

JS:   process.argv.slice(2)
来源：http://dali.daria6918.cn/Article/details/gtzbvuccqa.html

TS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gtbiclvpcs.html

Java: args 数组（main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gtmtyswdfh.html

Go:   os.Args[1:]
来源：http://dali.gogol.net.cn/Article/details/gtrkbzfajw.html

Ruby: ARGV
来源：http://dali.jinghuilouyu.cn/Article/details/gtjnysuqpi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinqigfzy.top/Article/details/gtijkzhdye.html

[M02] 读取环境变量
来源：http://dali.ivvv.top/Article/details/gtdpimygmp.html

Py:   os.environ.get("HOME")
来源：http://dali.nwbrower.top/Article/details/gtejzdzwki.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ehwqpu.com/Article/details/gtrejtnnpq.html

JS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gthrjscwfz.html

TS:   process.env.HOME
来源：http://dali.redwolf501.top/Article/details/gtcfakbcfw.html

Java: System.getenv("HOME")
来源：http://dali.xuanzx.com/Article/details/gtqiodlxui.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yueranfly.top/Article/details/gtflbsruiu.html

Ruby: ENV["HOME"]
来源：http://dali.wangshuangyany.cn/Article/details/gteazagaxp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtipxvxgqx.html

[M03] 执行外部命令
来源：http://dali.daxiang520.top/Article/details/gtpcvdnvud.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.iojbl.cn/Article/details/gtejodddun.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gtqtbfsgvt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigfzy.top/Article/details/gtacmxgzel.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gtmahbxrti.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nanxinkj.top/Article/details/gthrhtwdzh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shanyushiyangtech.top/Article/details/gtphicxnde.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.haohaochexian.top/Article/details/gthegrfuld.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sweek.top/Article/details/gtfwcnzipn.html

[M04] 获取当前工作目录
来源：http://dali.shuidangran.top/Article/details/gtuqomnboo.html

Py:   os.getcwd()
来源：http://dali.ivvv.top/Article/details/gtqecoxvhe.html

PHP:  getcwd();
来源：http://dali.yuxming.cn/Article/details/gtbaezcuqv.html

JS:   process.cwd()
来源：http://dali.zhixingplan.top/Article/details/gtedjcmnkk.html

TS:   process.cwd()
来源：http://dali.daxiang520.top/Article/details/gtxzeyyvct.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hywenlv.cn/Article/details/gtbrtykpdg.html

Go:   os.Getwd()
来源：http://dali.jlsjyb.cn/Article/details/gtnkqvesdq.html

Ruby: Dir.pwd
来源：http://dali.bjfxy.top/Article/details/gtbhuhaeru.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxinkj.top/Article/details/gtcrtducsi.html

[M05] 设置退出码
来源：http://dali.c1oappe.top/Article/details/gtjqfrclzj.html

Py:   sys.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtqfizhxnv.html

PHP:  exit(1);
来源：http://dali.dashuyun.cn/Article/details/gtwtoaqbcr.html

JS:   process.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtfcwdejoy.html

TS:   process.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtpfkdbtdn.html

Java: System.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtjpxbpbun.html

Go:   os.Exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtcqhdosak.html

Ruby: exit 1
来源：http://dali.hywenlv.cn/Article/details/gtrbqmenam.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.quarkkingdee.top/Article/details/gtfljoxxko.html

[M06] 向标准错误输出
来源：http://dali.hammf.cn/Article/details/gtnnfwjkdz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhixingplan.top/Article/details/gtjqzzeuyq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.dashuyun.cn/Article/details/gtfwaqgwcy.html

JS:   console.error("err")
来源：http://dali.xinyue.icu/Article/details/gtldjgscfp.html

TS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gtytbtbwhk.html

Java: System.err.println("err")
来源：http://dali.zhongyouzk.top/Article/details/gtmpaqiewc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sysykeji.top/Article/details/gtcaamxbvf.html

Ruby: warn "err"
来源：http://dali.yanxiufei.cn/Article/details/gtizzslcyt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigfzy.top/Article/details/gtwlmzkjgk.html

[M07] 判断是否为主入口
来源：http://dali.yuanzhike.top/Article/details/gtmyuqvcin.html

Py:   if __name__ == "__main__":
来源：http://dali.hysaishi.cn/Article/details/gthuctzywj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnqzz.top/Article/details/gtxtcwaigr.html

JS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gthbmppxqf.html

TS:   require.main === module
来源：http://dali.yonumen.top/Article/details/gtswhzeapo.html

Java: public static void main(String[] args)
来源：http://dali.9152youxi.cn/Article/details/gtnxuxejxt.html

Go:   func main()
来源：http://dali.gogol.net.cn/Article/details/gthefyjpkv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.daria6918.cn/Article/details/gttsbdflhn.html

C#:   static void Main(string[] args)
来源：http://dali.ydzc1.top/Article/details/gtqixvypzm.html

[M08] 获取系统与运行时信息
来源：http://dali.vqdsnc.cn/Article/details/gtpizsxbrl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shanyushiyangtech.top/Article/details/gtkwwservg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.birdmap.top/Article/details/gtgtpbgvak.html

JS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gthyczqvjb.html

TS:   process.platform;  process.version
来源：http://dali.hywenlv.cn/Article/details/gtwdxmzefg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzegozkbt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hywenlv.cn/Article/details/gtoameyioh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhiwuduotai.top/Article/details/gtmvczmihl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shanyushiyangtech.top/Article/details/gteciweert.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtaecgtqni.html

N. 数据结构与算法
来源：http://dali.vqdsnc.cn/Article/details/gtrxncdmof.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtmghhpyfk.html

[N01] 二分查找（有序数组）
来源：http://dali.kuanghao11.cn/Article/details/gtkylesajm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtkdhkxoai.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.snrcjt.cn/Article/details/gtroymhjtv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dashuyun.cn/Article/details/gtvdtfgnvt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cheryme.top/Article/details/gtdklpavvb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gthpurhqnm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtouhhvyof.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cucudq.cn/Article/details/gtvwjhylxu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtlrnimxhi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yvedp.cn/Article/details/gtekvgoapa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cucudq.cn/Article/details/gtsbrcxfwp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xuanzx.com/Article/details/gtlehsnfgq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gtjbjqbjlr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gtodqihhpe.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.iojbl.cn/Article/details/gtqquujhnw.html

Go:   slices.Sort(arr)
来源：http://dali.xylfe.cn/Article/details/gtvrcswjjz.html

Ruby: arr.sort
来源：http://dali.yvedp.cn/Article/details/gtxonerfhd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenzaomai.com/Article/details/gtfudhowxx.html

[N03] 快速排序（分治示例）
来源：http://dali.wangdashe.top/Article/details/gtdnpqqsfz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjpmhxylo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shangyingyoupin.top/Article/details/gtpjbqtlrg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.feifeiyinyue.top/Article/details/gtpldeckqr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gtatpvuujf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.snrcjt.cn/Article/details/gtossedwbw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gaohongyu789.top/Article/details/gtxgusjtlz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.daxiang520.top/Article/details/gtqdpubtmn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sufxvd.cn/Article/details/gtpxyesjnt.html

[N04] 斐波那契数列
来源：http://dali.chenjidiqi.icu/Article/details/gtriztxdik.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.kuanghao11.cn/Article/details/gtfwlcgqth.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.316326.xyz/Article/details/gtfjqewmuz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gtghxgaqui.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gtercegqmv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gtuzfyobgf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gtwqidqddg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jiagoushi.top/Article/details/gtvxsoqvcs.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gtqsgoppod.html

[N05] 最大公约数
来源：http://dali.andypj.xyz/Article/details/gtfcsgimeh.html

Py:   math.gcd(a, b)
来源：http://dali.zhengqikj.top/Article/details/gtuchonfov.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yuanzhike.top/Article/details/gtxffwrkwy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgfzy.top/Article/details/gtdsojelda.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.quarkkingdee.top/Article/details/gtivpfqqvr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gtjmtkwsgb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqzjriimm.html

Ruby: a.gcd(b)
来源：http://dali.ppjwa.cn/Article/details/gtfycyvift.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xinyue.icu/Article/details/gtiqeldwws.html

[N06] 判断回文字符串
来源：http://dali.cashguo.top/Article/details/gtdffmaezl.html

Py:   s == s[::-1]
来源：http://dali.yj20258888.top/Article/details/gtjogulycj.html

PHP:  $s === strrev($s);
来源：http://dali.ybcxt.top/Article/details/gtrhrlynro.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gtoztzsmxm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtmnwrqjrc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yanxiufei.cn/Article/details/gtzgrbgvkz.html

Go:   // 双指针从两端比较
来源：http://dali.nanxinkj.top/Article/details/gtmevpzhla.html

Ruby: s == s.reverse
来源：http://dali.wangdashe.top/Article/details/gtnivwfemi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj20258.top/Article/details/gtcahzzimj.html

[N07] 两数之和（返回下标）
来源：http://dali.svipenyu.cn/Article/details/gtbatkmkgw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yongpay.top/Article/details/gtjjofonms.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.pengpengdd.cyou/Article/details/gtztehpmiy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shuidangran.top/Article/details/gtwdqtjskm.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhengqikj.top/Article/details/gtsgrwkggs.html

Java: // 手写 HashMap
来源：http://dali.quarkkingdee.top/Article/details/gtxbsnoqio.html

Go:   // 手写 map[int]int
来源：http://dali.jyoumei.cn/Article/details/gtmyzhzoyd.html

Ruby: // 手写 Hash
来源：http://dali.cheryme.top/Article/details/gtpgdduyyr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cqqwz.cn/Article/details/gtjbewjffn.html

[N08] 生成全排列
来源：http://dali.fengsongda.top/Article/details/gtwwurpqll.html

Py:   itertools.permutations(arr)
来源：http://dali.yuanzhike.top/Article/details/gtrzyntiaa.html

PHP:  // 手写递归交换
来源：http://dali.zdqjudy.top/Article/details/gtoqtpbjau.html

JS:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtasisluvk.html

TS:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gteaqoojyf.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtxoeonpwe.html

Go:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtaqxkybhu.html

Ruby: arr.permutation.to_a
来源：http://dali.hongshengwenyu.top/Article/details/gtjpobvadm.html

C#:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtwvauqipw.html

[N09] 栈与队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqulzvxbu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cdnleiting.top/Article/details/gtqqxkther.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtdvmzpyns.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gtmnruabgq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jqgfzy.top/Article/details/gtyojveebu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cqqwz.cn/Article/details/gtckgbzkbo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jiagoushi.top/Article/details/gtvmjwxvmy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtprqqajgt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gtfxzuhova.html

[N10] 链表节点定义
来源：http://dali.ehwqpu.com/Article/details/gtaedqapiq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jyoumei.cn/Article/details/gtezxaoxfq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cdnleiting.top/Article/details/gtxkyrdtag.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shzxlz.cn/Article/details/gtgqhdtqds.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yongpay.top/Article/details/gttdtheidh.html

Java: class Node { int v; Node next; }
来源：http://dali.jinqigfzy.top/Article/details/gtwrrnkpjy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenzaomai.com/Article/details/gtkcobuyzz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.fzhhl.top/Article/details/gtbaukqsvt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj20258888.top/Article/details/gtsjayprit.html

[N11] 二叉树中序遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmgwalnz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.redwolf501.top/Article/details/gtyxmdgkte.html

PHP:  // 手写递归函数
来源：http://dali.jqgfzy.top/Article/details/gtlsvszlyu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxinkj.top/Article/details/gtqnxdraby.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gtgffwnnwo.html

Java: // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gtnalovddn.html

Go:   // 手写递归
来源：http://dali.yuxming.cn/Article/details/gtcvucovxy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.daria6918.cn/Article/details/gtjftqjgkk.html

C#:   // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gtpotkdtel.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sweek.top/Article/details/gtfdvorwxl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yuanzhike.top/Article/details/gtgvbyspey.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yuanzhike.top/Article/details/gtlruhcjzd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zycfv.cn/Article/details/gteksaaoks.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.redwolf501.top/Article/details/gtucavtipb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenjidiqi.icu/Article/details/gtmqqerctr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jqgufenzy.top/Article/details/gtqztxvbbs.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nwbrower.top/Article/details/gtcunbggye.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jlsjyb.cn/Article/details/gtdtuprqea.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtjedaiaff.html

O. 并发与异步
来源：http://dali.zhengqikj.top/Article/details/gtmbehhdii.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gttspnuzph.html

[O01] 启动一个线程
来源：http://dali.iojbl.cn/Article/details/gtrasrqclo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yj202588.top/Article/details/gtzluexdtu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xziqi.cn/Article/details/gtmveczzge.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xuanzx.com/Article/details/gtstigkdbl.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gtlfuiuyio.html

Java: new Thread(() -> f()).start()
来源：http://dali.0kj1m.cn/Article/details/gtmeupriwk.html

Go:   go f()
来源：http://dali.hnxiangtu.top/Article/details/gtyngerupf.html

Ruby: Thread.new { f }
来源：http://dali.shuidangran.top/Article/details/gtvgoinapr.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258.top/Article/details/gtfmbbzxwb.html

[O02] 使用线程池
来源：http://dali.sweek.top/Article/details/gtnnotkwfh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtprimksao.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xuetiantiany.cn/Article/details/gthsbacpyr.html

JS:   // worker_threads 线程池
来源：http://dali.shangyingyoupin.top/Article/details/gtjxsedtek.html

TS:   // worker_threads 线程池
来源：http://dali.bjfxy.top/Article/details/gtpesyygxk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gzhubu.top/Article/details/gtjdeaghpb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.aizwys.cn/Article/details/gtixuujpxb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhaomingkeji.xyz/Article/details/gtauaelude.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gaohongyu789.top/Article/details/gtfxldwijo.html

[O03] 加锁保护共享数据
来源：http://dali.havefunace.top/Article/details/gtxwbidnpo.html

Py:   with lock: shared += 1
来源：http://dali.zhoulong.xyz/Article/details/gtfvalzofd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cqqwz.cn/Article/details/gtkznxrven.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nwbrower.top/Article/details/gthsqvxqjy.html

TS:   // 同 JS
来源：http://dali.tianlin.xyz/Article/details/gtojmvasui.html

Java: synchronized (this) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gtikzqgjzm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.redwolf501.top/Article/details/gtfyngvrkw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttummucpk.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gtjaqrqwnc.html

[O04] 定义异步函数并等待
来源：http://dali.zycfv.cn/Article/details/gtruazrfbu.html

Py:   async def f():⏎    await g()
来源：http://dali.guowangkeji.top/Article/details/gtxegqsywr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cqqwz.cn/Article/details/gtkczudsuy.html

JS:   async function f() { await g(); }
来源：http://dali.xinyue.icu/Article/details/gtlljededc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.kuanghao11.cn/Article/details/gtrvebnhqp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.quarkkingdee.top/Article/details/gtntofcjug.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhixingplan.top/Article/details/gtinxdhxxh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.dianchejie.cn/Article/details/gtnwgdjpil.html

C#:   async Task F() { await G(); }
来源：http://dali.jyoumei.cn/Article/details/gtdikkirkt.html

[O05] 并发执行并等待全部完成
来源：http://dali.yangfankeji.com/Article/details/gtstdjphsp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yj20258.top/Article/details/gtxuftylbx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.mhx1999.top/Article/details/gtnpeotbku.html

JS:   await Promise.all(tasks)
来源：http://dali.yuanzhike.top/Article/details/gtdyqctqav.html

TS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gtrwxufrmn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yueranfly.top/Article/details/gthryahzda.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinghuilouyu.cn/Article/details/gtyybvwajj.html

Ruby: threads.map(&:join)
来源：http://dali.tanke756.top/Article/details/gtvzllqplv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yueranfly.top/Article/details/gtqxkbokhl.html

[O06] 使用进程池
来源：http://dali.jqgufenzy.top/Article/details/gtgctqyhdh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gogol.net.cn/Article/details/gtstkopnjk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yj20258.top/Article/details/gtevpbtjsw.html

JS:   // child_process / cluster 模块
来源：http://dali.zhiwuduotai.top/Article/details/gtxklsoiuz.html

TS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangtech.top/Article/details/gtgvaaupqv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuxming.cn/Article/details/gthpbhzqvw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hongshengwenyu.top/Article/details/gtbwaoychb.html

Ruby: // fork 块
来源：http://dali.ppjwa.cn/Article/details/gtdqdkkmdy.html

C#:   Parallel.For
来源：http://dali.daria6918.cn/Article/details/gtxgagwjmr.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gttijjqdbs.html

P. 常用工具函数
来源：http://dali.zhiwuduotai.top/Article/details/gtsyhfboyf.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtvkphhruz.html

[P01] 生成 UUID
来源：http://dali.sufxvd.cn/Article/details/gthsfjrgxq.html

Py:   str(uuid.uuid4())
来源：http://dali.hywenlv.cn/Article/details/gtwjyvblfo.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.guannengcc.top/Article/details/gtwcmmcxoq.html

JS:   crypto.randomUUID()
来源：http://dali.yj20258.top/Article/details/gtgetttzve.html

TS:   crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gtwkwdpwsu.html

Java: UUID.randomUUID().toString()
来源：http://dali.dianchejie.cn/Article/details/gtpxgvvywh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvprvkmt.html

Ruby: SecureRandom.uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakhtrzkh.html


<!-- 参考信息 -->