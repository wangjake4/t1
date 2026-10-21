代发 wailian999

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hongshengwenyu.top/Article/details/gtlnqqcjea.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.feifeiyinyue.top/Article/details/gttaqkzbcr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.guowangkeji.top/Article/details/gtnrampyma.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.snrcjt.cn/Article/details/gtbajntmvy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daxiang520.top/Article/details/gtpwkfaqnd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.iojbl.cn/Article/details/gtussqfwzo.html

[L05] 上传文件（multipart）
来源：http://dali.xylfe.cn/Article/details/gtgwxavysx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenjidiqi.icu/Article/details/gttstkwrwr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.pycfn.com/Article/details/gtmrsynnxe.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sysykeji.top/Article/details/gtvuanbsfr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhongyouzk.top/Article/details/gtonnsircj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.aibaodan.cn/Article/details/gteqhvpcnr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xinyue.icu/Article/details/gtfzplojlh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.havefunace.top/Article/details/gtoztouemn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtruknebky.html

[L06] 解析响应为 JSON
来源：http://dali.jianghu66.top/Article/details/gtoinzwdey.html

Py:   resp.json()
来源：http://dali.aizwys.cn/Article/details/gtrojrvpao.html

PHP:  json_decode($body, true);
来源：http://dali.yonumen.top/Article/details/gtsgketiuw.html

JS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gtcjnrcdnz.html

TS:   await resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtafkuhqki.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gtkittrxvo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hywenlv.cn/Article/details/gtichhlnwg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258888.top/Article/details/gtczuqjqdc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xuetiantiany.cn/Article/details/gtrzzkpsnb.html

[L07] 处理 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gtgsontjpe.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtozkysdvu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hywenlv.cn/Article/details/gtlcurnfjb.html

JS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gtatygcybg.html

TS:   resp.ok;  resp.status
来源：http://dali.hywenlv.cn/Article/details/gtfxbhivjl.html

Java: resp.statusCode()
来源：http://dali.ppjwa.cn/Article/details/gtvvefhouw.html

Go:   resp.StatusCode
来源：http://dali.pengpengdd.cyou/Article/details/gtipuzrypm.html

Ruby: resp.code.to_i
来源：http://dali.jinqigfzy.top/Article/details/gtvxhfdmgf.html

C#:   (int)resp.StatusCode
来源：http://dali.jinqigufen.top/Article/details/gtjcnxttzg.html

[L08] 并发请求多个地址
来源：http://dali.meibo888.top/Article/details/gtudrbpxns.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nanxuanxn.top/Article/details/gtvbybwaym.html

PHP:  curl_multi_init() 系列
来源：http://dali.fzhhl.top/Article/details/gttwwclbos.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ybcxt.top/Article/details/gtyzlptuvt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.havefunace.top/Article/details/gtibhqkwvk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gzhubu.top/Article/details/gtbmqhpsar.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cdnleiting.top/Article/details/gtgoberafa.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.mhx1999.top/Article/details/gtyleufzzd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yuanzhike.top/Article/details/gtawydjseb.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtttszxbug.html

M. 命令行 / 进程 / 环境
来源：http://dali.shangyingyoupin.top/Article/details/gtappyzigu.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtmuikgswk.html

[M01] 读取命令行参数
来源：http://dali.guowangkeji.top/Article/details/gtaekqiedh.html

Py:   sys.argv[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gtvdllofak.html

PHP:  $argv;  $argc;
来源：http://dali.quarkkingdee.top/Article/details/gtzcvvahvo.html

JS:   process.argv.slice(2)
来源：http://dali.redwolf501.top/Article/details/gtcqfolfwu.html

TS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gtxcgtsuqb.html

Java: args 数组（main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gtczjwjixu.html

Go:   os.Args[1:]
来源：http://dali.hywenlv.cn/Article/details/gtwszdiolj.html

Ruby: ARGV
来源：http://dali.cucudq.cn/Article/details/gtbxftmmux.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ppjwa.cn/Article/details/gtpzcogctm.html

[M02] 读取环境变量
来源：http://dali.snrcjt.cn/Article/details/gtyorddfer.html

Py:   os.environ.get("HOME")
来源：http://dali.xuanzx.com/Article/details/gtybaurgvc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gtczonkrwb.html

JS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gtdkghyvbk.html

TS:   process.env.HOME
来源：http://dali.yj20258.top/Article/details/gtsforqdde.html

Java: System.getenv("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxjugzhno.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ivvv.top/Article/details/gtbimchngq.html

Ruby: ENV["HOME"]
来源：http://dali.jqgfzy.top/Article/details/gtpfplsfqq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tanke756.top/Article/details/gtmgdwgpfs.html

[M03] 执行外部命令
来源：http://dali.9152youxi.cn/Article/details/gtnypoizil.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gthzhbknsj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.andypj.xyz/Article/details/gtkkduzxnq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zycfv.cn/Article/details/gtotemsjfi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gttspxejjh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xinyue.icu/Article/details/gtrvojxunb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhoulong.xyz/Article/details/gtoqknvaem.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.aizwys.cn/Article/details/gtxooagdek.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cqqwz.cn/Article/details/gthzmbvysb.html

[M04] 获取当前工作目录
来源：http://dali.yuxming.cn/Article/details/gtszzlngtz.html

Py:   os.getcwd()
来源：http://dali.redwolf501.top/Article/details/gtibgxyrfd.html

PHP:  getcwd();
来源：http://dali.snrcjt.cn/Article/details/gtzazflwxz.html

JS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gtemnuemkg.html

TS:   process.cwd()
来源：http://dali.ehwqpu.com/Article/details/gthmvmfvyb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xylfe.cn/Article/details/gtctiilutq.html

Go:   os.Getwd()
来源：http://dali.zhongyouzk.top/Article/details/gtjubjczyk.html

Ruby: Dir.pwd
来源：http://dali.jiagoushi.top/Article/details/gtriwlhtzt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.0kj1m.cn/Article/details/gtvdleasrh.html

[M05] 设置退出码
来源：http://dali.yanxiufei.cn/Article/details/gtklryyeyo.html

Py:   sys.exit(1)
来源：http://dali.sweek.top/Article/details/gtnhobmpsv.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gtomqqnoxt.html

JS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtqhrybdlt.html

TS:   process.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtbljvaxpn.html

Java: System.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcaltojxm.html

Go:   os.Exit(1)
来源：http://dali.yongpay.top/Article/details/gtpdhrqwbd.html

Ruby: exit 1
来源：http://dali.quarkkingdee.top/Article/details/gtbisjwcdg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xuetiantiany.cn/Article/details/gtjdtxxaar.html

[M06] 向标准错误输出
来源：http://dali.fzhhl.top/Article/details/gtlghavhyt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hywenlv.cn/Article/details/gthbnasaeh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zycfv.cn/Article/details/gtorfjdbjl.html

JS:   console.error("err")
来源：http://dali.hammf.cn/Article/details/gtjtscsenn.html

TS:   console.error("err")
来源：http://dali.jqgfzy.top/Article/details/gtmzisdkeq.html

Java: System.err.println("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtsxlixbwl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daria6918.cn/Article/details/gtprkfktdo.html

Ruby: warn "err"
来源：http://dali.gzhubu.top/Article/details/gtsiuxskzh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yuxming.cn/Article/details/gtzxordmui.html

[M07] 判断是否为主入口
来源：http://dali.9152youxi.cn/Article/details/gtabddmlyf.html

Py:   if __name__ == "__main__":
来源：http://dali.zhixingplan.top/Article/details/gtdsdwfoaa.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.fzhhl.top/Article/details/gtvizpffma.html

JS:   require.main === module
来源：http://dali.quarkkingdee.top/Article/details/gtqxhwxrur.html

TS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gtnjijanlw.html

Java: public static void main(String[] args)
来源：http://dali.jiagoushi.top/Article/details/gtwodtbpcr.html

Go:   func main()
来源：http://dali.zhengqikj.top/Article/details/gtvdsxxyui.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jyoumei.cn/Article/details/gtaxialbrz.html

C#:   static void Main(string[] args)
来源：http://dali.yuxming.cn/Article/details/gtfrmqmbdn.html

[M08] 获取系统与运行时信息
来源：http://dali.yuxming.cn/Article/details/gtfrgzoypj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.mhx1999.top/Article/details/gtzkevneye.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.meibo888.top/Article/details/gtqcsehkra.html

JS:   process.platform;  process.version
来源：http://dali.cqqwz.cn/Article/details/gtylamlvgk.html

TS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gtntgjgjew.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigfzy.top/Article/details/gtzngyfqru.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.bjfxy.top/Article/details/gtmfgjurgb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.guowangkeji.top/Article/details/gtihlwlyfi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhoulong.xyz/Article/details/gtxkcsqixi.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtqpkhfric.html

N. 数据结构与算法
来源：http://dali.redwolf501.top/Article/details/gtqzhsojkm.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtltizmjrt.html

[N01] 二分查找（有序数组）
来源：http://dali.tanke756.top/Article/details/gtpuuoddxt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtbmugeqtx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nanxinkj.top/Article/details/gtupvrfxtc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.havefunace.top/Article/details/gtifqajpim.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.316326.xyz/Article/details/gtiwkgypni.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzmrrcpsy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtmpjutaem.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cdnleiting.top/Article/details/gtimoojieq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhwgrrmd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.0kj1m.cn/Article/details/gtibsircja.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.kuanghao11.cn/Article/details/gtphgqdhiu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yuanzhike.top/Article/details/gtwhrntwbo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj202588.top/Article/details/gttpdzqstm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gthzfrkzgr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jqgufenzy.top/Article/details/gtddoxaakm.html

Go:   slices.Sort(arr)
来源：http://dali.guannengcc.top/Article/details/gtinefhvsv.html

Ruby: arr.sort
来源：http://dali.ehwqpu.com/Article/details/gtccfvagbn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgqcadmff.html

[N03] 快速排序（分治示例）
来源：http://dali.yj20258.top/Article/details/gtaurnvziv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gtxztkfmnd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtojkzbgzn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xinyue.icu/Article/details/gtsaoowxxc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.snrcjt.cn/Article/details/gtmjphcwfa.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hnqzz.top/Article/details/gtzuvidztz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xuetiantiany.cn/Article/details/gtcfmcfyqo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tanke756.top/Article/details/gtjfmqsvvv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nanxuanxn.top/Article/details/gtfarurkug.html

[N04] 斐波那契数列
来源：http://dali.yuanzhike.top/Article/details/gtheyncifm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yvedp.cn/Article/details/gtheoboyxx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gthkdhjpup.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gtabwpjddv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gtejbsznpk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gtyivohujb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrmxgsqo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.andypj.xyz/Article/details/gtjvycbcte.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gtxqbfxknr.html

[N05] 最大公约数
来源：http://dali.hnqzz.top/Article/details/gtyigspzjq.html

Py:   math.gcd(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gtdfptizjg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nwbrower.top/Article/details/gtitxqykyy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.redwolf501.top/Article/details/gtmksggzbq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.havefunace.top/Article/details/gtrwfaukon.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zycfv.cn/Article/details/gtjumqlmaw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.iojbl.cn/Article/details/gtokndypef.html

Ruby: a.gcd(b)
来源：http://dali.cashguo.top/Article/details/gtxqbqokql.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.dianchejie.cn/Article/details/gtdzqzgjik.html

[N06] 判断回文字符串
来源：http://dali.chenzaomai.com/Article/details/gthuhiabij.html

Py:   s == s[::-1]
来源：http://dali.ybcxt.top/Article/details/gtdhkrqkui.html

PHP:  $s === strrev($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjkbuddv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjkwuffe.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gtrnjcsvvw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinqigfzy.top/Article/details/gtgdugsiwg.html

Go:   // 双指针从两端比较
来源：http://dali.zhengqikj.top/Article/details/gtthnnnawb.html

Ruby: s == s.reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtyloirvfb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gtvdpfjfte.html

[N07] 两数之和（返回下标）
来源：http://dali.ppjwa.cn/Article/details/gtqsubbpoj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ehwqpu.com/Article/details/gthomussiw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hysaishi.cn/Article/details/gtelomkhii.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yangfankeji.com/Article/details/gtwcmjomtw.html

TS:   // 手写 Map<string, number>
来源：http://dali.ivvv.top/Article/details/gthzjkrjqb.html

Java: // 手写 HashMap
来源：http://dali.xuetiantiany.cn/Article/details/gtrlgcwqoz.html

Go:   // 手写 map[int]int
来源：http://dali.feifeiyinyue.top/Article/details/gtiiyjygtv.html

Ruby: // 手写 Hash
来源：http://dali.shangyingyoupin.top/Article/details/gtvrxmoupy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.kuanghao11.cn/Article/details/gtpopccdts.html

[N08] 生成全排列
来源：http://dali.zhengqikj.top/Article/details/gtrungkpmo.html

Py:   itertools.permutations(arr)
来源：http://dali.xuanzx.com/Article/details/gtpphalrxz.html

PHP:  // 手写递归交换
来源：http://dali.hnqzz.top/Article/details/gttexgixko.html

JS:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gtlsaqdpkf.html

TS:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtbbwoqmcg.html

Java: // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtcalftdzr.html

Go:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtpcqssosc.html

Ruby: arr.permutation.to_a
来源：http://dali.yangfankeji.com/Article/details/gtiasnhbmh.html

C#:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gthqphoogz.html

[N09] 栈与队列
来源：http://dali.c1oappe.top/Article/details/gttktezdwc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yonumen.top/Article/details/gtvwkevnwf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tanke756.top/Article/details/gtsxoufaqk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.mhx1999.top/Article/details/gtpwoqxkqb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xylfe.cn/Article/details/gtboyvaxnv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.0kj1m.cn/Article/details/gtazumpedk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yangfankeji.com/Article/details/gtoakouahl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.daria6918.cn/Article/details/gtbtzjlvpt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkuiavdka.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gtexuhvcre.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.dashuyun.cn/Article/details/gtlbalkvha.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gaohongyu789.top/Article/details/gtdshhdhmy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jiagoushi.top/Article/details/gtdzioprkj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj20258888.top/Article/details/gtivruxurd.html

Java: class Node { int v; Node next; }
来源：http://dali.andypj.xyz/Article/details/gtofgkqlrc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ydzc1.top/Article/details/gtybguvsuz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cheryme.top/Article/details/gtfiwxvumh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxhreyse.html

[N11] 二叉树中序遍历
来源：http://dali.cheryme.top/Article/details/gtuvmsidgp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.nanxuanxn.top/Article/details/gthfhcomtd.html

PHP:  // 手写递归函数
来源：http://dali.sysykeji.top/Article/details/gtcqilhbya.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gtbpsjvsvs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgufenzy.top/Article/details/gtljaunzva.html

Java: // 手写递归
来源：http://dali.sxryk.cn/Article/details/gtodyzbojl.html

Go:   // 手写递归
来源：http://dali.xziqi.cn/Article/details/gtbtmcuzil.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.c1oappe.top/Article/details/gtrbgofpcz.html

C#:   // 手写递归
来源：http://dali.yj202588.top/Article/details/gtehczamqh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yuanzhike.top/Article/details/gtcphfktgc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.birdmap.top/Article/details/gtjnckiuib.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gogol.net.cn/Article/details/gtfvyxvqcy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yanxiufei.cn/Article/details/gtgzpmwrch.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gtcadbjuyl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dianchejie.cn/Article/details/gtonmrlozx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shanyushiyangtech.top/Article/details/gthihekjdw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cheryme.top/Article/details/gtncrqfxwq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jianghu66.top/Article/details/gtanzksejp.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtgdpxdazl.html

O. 并发与异步
来源：http://dali.hfpthk.cn/Article/details/gtdlgthlau.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtwmecbhjc.html

[O01] 启动一个线程
来源：http://dali.xuanzx.com/Article/details/gtustyezcq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sweek.top/Article/details/gtvvbtggip.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jyoumei.cn/Article/details/gttsvoiyez.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.guowangkeji.top/Article/details/gtysgjwvjo.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gtsgbhgjyz.html

Java: new Thread(() -> f()).start()
来源：http://dali.ppjwa.cn/Article/details/gtmxrjmmuc.html

Go:   go f()
来源：http://dali.fengsongda.top/Article/details/gtzngzqnbo.html

Ruby: Thread.new { f }
来源：http://dali.wangshuangyany.cn/Article/details/gtckoghkcq.html

C#:   Task.Run(() => F());
来源：http://dali.gzhubu.top/Article/details/gtnxlygkii.html

[O02] 使用线程池
来源：http://dali.jqgufenzy.top/Article/details/gtjszimyxo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cheryme.top/Article/details/gtauusisid.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.bjfxy.top/Article/details/gtmeslecaq.html

JS:   // worker_threads 线程池
来源：http://dali.yj20258.top/Article/details/gtqipxwcsj.html

TS:   // worker_threads 线程池
来源：http://dali.iojbl.cn/Article/details/gtbfrnqhxi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hnqzz.top/Article/details/gtxlnefxrl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cheryme.top/Article/details/gtyljxqdzp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhongyouzk.top/Article/details/gtdagsyxvw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xylfe.cn/Article/details/gtwnyvyvue.html

[O03] 加锁保护共享数据
来源：http://dali.xziqi.cn/Article/details/gtyygvlrec.html

Py:   with lock: shared += 1
来源：http://dali.gogol.net.cn/Article/details/gtxltgomsn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sweek.top/Article/details/gtpfhykpsd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.pengpengdd.cyou/Article/details/gteibpgqej.html

TS:   // 同 JS
来源：http://dali.jyoumei.cn/Article/details/gtwpdkpifl.html

Java: synchronized (this) { shared++; }
来源：http://dali.gotoacloud.top/Article/details/gtuerhinbc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sxryk.cn/Article/details/gttadfqyns.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tian-w.cn/Article/details/gtmbyypgkq.html

C#:   lock (gate) { shared++; }
来源：http://dali.hfpthk.cn/Article/details/gthuidzjkv.html

[O04] 定义异步函数并等待
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbewccplq.html

Py:   async def f():⏎    await g()
来源：http://dali.birdmap.top/Article/details/gtrqmwkezo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.svipenyu.cn/Article/details/gtophzpcog.html

JS:   async function f() { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gtfczvbssa.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shuidangran.top/Article/details/gtnapnuilv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.pycfn.com/Article/details/gtklyzbabl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenjidiqi.icu/Article/details/gttfawjwac.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yonumen.top/Article/details/gtsmxthvtj.html

C#:   async Task F() { await G(); }
来源：http://dali.shzxlz.cn/Article/details/gtdxynrldw.html

[O05] 并发执行并等待全部完成
来源：http://dali.shanyushiyangtech.top/Article/details/gtdohfwuzg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sxryk.cn/Article/details/gtrqfxyrqn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenzaomai.com/Article/details/gtigvhodom.html

JS:   await Promise.all(tasks)
来源：http://dali.havefunace.top/Article/details/gtwndxdiul.html

TS:   await Promise.all(tasks)
来源：http://dali.svipenyu.cn/Article/details/gtzofgrsva.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.wangshuangyany.cn/Article/details/gtauzcntjb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwpxoouo.html

Ruby: threads.map(&:join)
来源：http://dali.shangyingyoupin.top/Article/details/gtgkjesphq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ydzc1.top/Article/details/gtmtqmmsdk.html

[O06] 使用进程池
来源：http://dali.chenzaomai.com/Article/details/gtryjyrjuo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenzaomai.com/Article/details/gtcstvgjmo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtcpqdyoqf.html

JS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gtbwxkuzcy.html

TS:   // child_process / cluster 模块
来源：http://dali.yvedp.cn/Article/details/gthgfabeag.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.wangshuangyany.cn/Article/details/gteechonek.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.andypj.xyz/Article/details/gtfdyevwdi.html

Ruby: // fork 块
来源：http://dali.cdnleiting.top/Article/details/gthmcoqdsu.html

C#:   Parallel.For
来源：http://dali.yongpay.top/Article/details/gtdegccjbj.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtfuxoptkm.html

P. 常用工具函数
来源：http://dali.cucudq.cn/Article/details/gtcoctzlat.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtwtoglxgw.html

[P01] 生成 UUID
来源：http://dali.guowangkeji.top/Article/details/gtuogrzmnh.html

Py:   str(uuid.uuid4())
来源：http://dali.zdqjudy.top/Article/details/gtotmmppen.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tian-w.cn/Article/details/gtfvtoqcbz.html

JS:   crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gtjacufcjd.html

TS:   crypto.randomUUID()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthlqvowxi.html

Java: UUID.randomUUID().toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtiejdupqz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.meibo888.top/Article/details/gtrgisfbej.html

Ruby: SecureRandom.uuid
来源：http://dali.0kj1m.cn/Article/details/gtkchmncir.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xuetiantiany.cn/Article/details/gtjwiisdmn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.fengsongda.top/Article/details/gtlqdcfyec.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xziqi.cn/Article/details/gtedewckzy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.daria6918.cn/Article/details/gtgsejtglu.html


<!-- 参考信息 -->