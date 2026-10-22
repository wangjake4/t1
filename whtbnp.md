代发 wailian999

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.feifeiyinyue.top/Article/details/gtkccxkovo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hfpthk.cn/Article/details/gtakrabjrx.html

[L05] 上传文件（multipart）
来源：http://dali.sweek.top/Article/details/gtspamassa.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gtilekoopx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sysykeji.top/Article/details/gtauvgstix.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gtbkwektif.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj202588.top/Article/details/gtnpxcwfit.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258.top/Article/details/gtisrretvy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hnqzz.top/Article/details/gtnqgqbhce.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenzaomai.com/Article/details/gtvkblljsm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nwbrower.top/Article/details/gtgpdojysd.html

[L06] 解析响应为 JSON
来源：http://dali.9152youxi.cn/Article/details/gtaemyugeu.html

Py:   resp.json()
来源：http://dali.9152youxi.cn/Article/details/gtemdrmywo.html

PHP:  json_decode($body, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtipgqygxl.html

JS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gtglrtteus.html

TS:   await resp.json()
来源：http://dali.xylfe.cn/Article/details/gtmqsbyliv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gtlwsoaofs.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxinkj.top/Article/details/gtooyoagsy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.fzhhl.top/Article/details/gtfakfbybz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cucudq.cn/Article/details/gtgbqvvyll.html

[L07] 处理 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gtlmgmgyau.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hongshengwenyu.top/Article/details/gtzwdzhypz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sxryk.cn/Article/details/gtmtlujpre.html

JS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gtivpqllxi.html

TS:   resp.ok;  resp.status
来源：http://dali.yj20258.top/Article/details/gtfyehxxgr.html

Java: resp.statusCode()
来源：http://dali.vqdsnc.cn/Article/details/gtgihtgijc.html

Go:   resp.StatusCode
来源：http://dali.kuanghao11.cn/Article/details/gtstbekwpl.html

Ruby: resp.code.to_i
来源：http://dali.shanyushiyangkeji.top/Article/details/gtigoldclj.html

C#:   (int)resp.StatusCode
来源：http://dali.dashuyun.cn/Article/details/gtrqqgyktv.html

[L08] 并发请求多个地址
来源：http://dali.quarkkingdee.top/Article/details/gtkipbrnqy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj20258888.top/Article/details/gtatsxrqmu.html

PHP:  curl_multi_init() 系列
来源：http://dali.nanxinkj.top/Article/details/gtcjjnwruj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtvxurrsgn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.redwolf501.top/Article/details/gtquxggjvt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fengsongda.top/Article/details/gtvisrgbai.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvlkcseaw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gogol.net.cn/Article/details/gtjkvndbfu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xuanzx.com/Article/details/gtstxnmrzp.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtncarvyqv.html

M. 命令行 / 进程 / 环境
来源：http://dali.wangshuangyany.cn/Article/details/gtojulpbvu.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtftpejbzo.html

[M01] 读取命令行参数
来源：http://dali.zhixingplan.top/Article/details/gtxwygzxen.html

Py:   sys.argv[1:]
来源：http://dali.yonumen.top/Article/details/gtnprqclft.html

PHP:  $argv;  $argc;
来源：http://dali.tian-w.cn/Article/details/gtmoqqruec.html

JS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gtszknziga.html

TS:   process.argv.slice(2)
来源：http://dali.bjfxy.top/Article/details/gtnocwglgh.html

Java: args 数组（main 方法参数）
来源：http://dali.sxryk.cn/Article/details/gtgkmjtgln.html

Go:   os.Args[1:]
来源：http://dali.hnqzz.top/Article/details/gtlegvjegq.html

Ruby: ARGV
来源：http://dali.pycfn.com/Article/details/gtbhmwxfxx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.aibaodan.cn/Article/details/gtcphgbfdm.html

[M02] 读取环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfhttrmm.html

Py:   os.environ.get("HOME")
来源：http://dali.hywenlv.cn/Article/details/gtdishbwan.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xuanzx.com/Article/details/gtbovhalpr.html

JS:   process.env.HOME
来源：http://dali.zdqjudy.top/Article/details/gtgfbczbcl.html

TS:   process.env.HOME
来源：http://dali.yvedp.cn/Article/details/gtanrgbark.html

Java: System.getenv("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtopeixohu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwwogscre.html

Ruby: ENV["HOME"]
来源：http://dali.jiagoushi.top/Article/details/gtayeohvbp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258.top/Article/details/gtqmuosxzb.html

[M03] 执行外部命令
来源：http://dali.shzxlz.cn/Article/details/gtsstormur.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gzhubu.top/Article/details/gtmpnnrnfq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.snrcjt.cn/Article/details/gttyjkhctm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gtxjjomdvg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sweek.top/Article/details/gthuhbsafy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.havefunace.top/Article/details/gtxzhrkqwl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gotoacloud.top/Article/details/gtswdzlxuk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenzaomai.com/Article/details/gtfhkndkng.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ivvv.top/Article/details/gtavznifnb.html

[M04] 获取当前工作目录
来源：http://dali.sufxvd.cn/Article/details/gtdcuppdem.html

Py:   os.getcwd()
来源：http://dali.meibo888.top/Article/details/gtbgzbrdye.html

PHP:  getcwd();
来源：http://dali.ehwqpu.com/Article/details/gtrfmtlklp.html

JS:   process.cwd()
来源：http://dali.daxiang520.top/Article/details/gtsvwmwszc.html

TS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gtwfzepaju.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zdqjudy.top/Article/details/gtpvdoxxkt.html

Go:   os.Getwd()
来源：http://dali.hnxiangtu.top/Article/details/gtqkpcdspj.html

Ruby: Dir.pwd
来源：http://dali.ivvv.top/Article/details/gtotcmhdjc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxuanxn.top/Article/details/gtohrrsylq.html

[M05] 设置退出码
来源：http://dali.gzhubu.top/Article/details/gteicchfxs.html

Py:   sys.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtyadunwgo.html

PHP:  exit(1);
来源：http://dali.sweek.top/Article/details/gtenmopfkd.html

JS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtrxhpbgau.html

TS:   process.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtoknmpjgw.html

Java: System.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtrdnnsgyt.html

Go:   os.Exit(1)
来源：http://dali.fzhhl.top/Article/details/gtrauuexdp.html

Ruby: exit 1
来源：http://dali.c1oappe.top/Article/details/gtelpzxuno.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj202588.top/Article/details/gttndemqix.html

[M06] 向标准错误输出
来源：http://dali.yj202588.top/Article/details/gtannnrczu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shuidangran.top/Article/details/gtklslomzg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cucudq.cn/Article/details/gtfcnnppee.html

JS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gtyoftuzms.html

TS:   console.error("err")
来源：http://dali.yonumen.top/Article/details/gtvzuzbstg.html

Java: System.err.println("err")
来源：http://dali.sysykeji.top/Article/details/gtvhykezsv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jyoumei.cn/Article/details/gtacmuljkw.html

Ruby: warn "err"
来源：http://dali.hysaishi.cn/Article/details/gtpfktxnws.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenzaomai.com/Article/details/gtyckzsnuw.html

[M07] 判断是否为主入口
来源：http://dali.snrcjt.cn/Article/details/gtujvzwrsz.html

Py:   if __name__ == "__main__":
来源：http://dali.pengpengdd.cyou/Article/details/gteahtoqwe.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxuanxn.top/Article/details/gtnngnugjs.html

JS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gtrnbzzicg.html

TS:   require.main === module
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoqxyuivk.html

Java: public static void main(String[] args)
来源：http://dali.cheryme.top/Article/details/gtgkeinbdo.html

Go:   func main()
来源：http://dali.sweek.top/Article/details/gthwyvgnfh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guowangkeji.top/Article/details/gticbznqrd.html

C#:   static void Main(string[] args)
来源：http://dali.gaohongyu789.top/Article/details/gtaylffnnf.html

[M08] 获取系统与运行时信息
来源：http://dali.birdmap.top/Article/details/gtylicfyll.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yuxming.cn/Article/details/gtjppxgytt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yongpay.top/Article/details/gtxnvskyzx.html

JS:   process.platform;  process.version
来源：http://dali.yvedp.cn/Article/details/gtpgekdgpe.html

TS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gttdqpmzhs.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj20258.top/Article/details/gtmdunuywk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nanxuanxn.top/Article/details/gtvtrgwtnk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nanxuanxn.top/Article/details/gttewyzjfy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.quarkkingdee.top/Article/details/gttooouzdm.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtkluvcaav.html

N. 数据结构与算法
来源：http://dali.hysaishi.cn/Article/details/gtmgloamso.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtqzpxurmh.html

[N01] 二分查找（有序数组）
来源：http://dali.hnqzz.top/Article/details/gtfnnmfshm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gthqqpnmce.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gtlqanvvlt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtsmnmjqnm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hywenlv.cn/Article/details/gttharjbmu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtkhglvtus.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hammf.cn/Article/details/gtqrndvmip.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xylfe.cn/Article/details/gtbusddxwd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtypnvxcpv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xziqi.cn/Article/details/gtbiftpezi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258888.top/Article/details/gtjzzsyooe.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhengqikj.top/Article/details/gtpjxtobym.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gtzgewdetq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxinkj.top/Article/details/gtkklyvklc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftmngeuv.html

Go:   slices.Sort(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtylhqdnxh.html

Ruby: arr.sort
来源：http://dali.pengpengdd.cyou/Article/details/gtvshqewum.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.dashuyun.cn/Article/details/gtzxzvxiaa.html

[N03] 快速排序（分治示例）
来源：http://dali.mhx1999.top/Article/details/gtwurezisc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.daria6918.cn/Article/details/gtpczifuls.html

PHP:  // 递归实现，或用 usort
来源：http://dali.dianchejie.cn/Article/details/gtcjshtkft.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.feifeiyinyue.top/Article/details/gteagiuqze.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yanxiufei.cn/Article/details/gtvrjvaegx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.smart0.xyz/Article/details/gtpocwdphv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shangyingyoupin.top/Article/details/gtcjplqnyf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.daxiang520.top/Article/details/gtwyhafwtf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.bjfxy.top/Article/details/gtobwjutil.html

[N04] 斐波那契数列
来源：http://dali.aizwys.cn/Article/details/gtjmmpxiym.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sweek.top/Article/details/gtzjiuzavp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.bjfxy.top/Article/details/gtaejekkwf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gtysprgyqy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gtxykaecne.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenzaomai.com/Article/details/gttgucaifu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.smart0.xyz/Article/details/gtncxzkkuw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.0kj1m.cn/Article/details/gtcbhbtujd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtiompeyjj.html

[N05] 最大公约数
来源：http://dali.dianchejie.cn/Article/details/gtkgbdmgom.html

Py:   math.gcd(a, b)
来源：http://dali.tanke756.top/Article/details/gttwhvkpsw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.daxiang520.top/Article/details/gtpbovyfad.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ivvv.top/Article/details/gtsfgrhrse.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gtemwlghfv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yanxiufei.cn/Article/details/gtvompahdw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ivvv.top/Article/details/gtwsipynsn.html

Ruby: a.gcd(b)
来源：http://dali.cqqwz.cn/Article/details/gtrjnkeghc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guowangkeji.top/Article/details/gtnsitzlzx.html

[N06] 判断回文字符串
来源：http://dali.aizwys.cn/Article/details/gtilkzdjpb.html

Py:   s == s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gtnraxhguf.html

PHP:  $s === strrev($s);
来源：http://dali.jinqigufen.top/Article/details/gtrebelzyb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtplbfzrov.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtsoqhwzvr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.pengpengdd.cyou/Article/details/gtbjvzbmep.html

Go:   // 双指针从两端比较
来源：http://dali.nanxuanxn.top/Article/details/gtgjqejnog.html

Ruby: s == s.reverse
来源：http://dali.andypj.xyz/Article/details/gtztypamaf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hnxiangtu.top/Article/details/gtvyzithdd.html

[N07] 两数之和（返回下标）
来源：http://dali.daria6918.cn/Article/details/gtmoiyhers.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nanxinkj.top/Article/details/gtrovejzbi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hongshengwenyu.top/Article/details/gtwacokvfi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinqigfzy.top/Article/details/gtjfjnrtzp.html

TS:   // 手写 Map<string, number>
来源：http://dali.gogol.net.cn/Article/details/gtmjpgsxsj.html

Java: // 手写 HashMap
来源：http://dali.zhaomingkeji.xyz/Article/details/gttlmrfolt.html

Go:   // 手写 map[int]int
来源：http://dali.wangdashe.top/Article/details/gtdeybokwl.html

Ruby: // 手写 Hash
来源：http://dali.aizwys.cn/Article/details/gtarwvonot.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hnxiangtu.top/Article/details/gtnpenoxqm.html

[N08] 生成全排列
来源：http://dali.cucudq.cn/Article/details/gthgfjcfys.html

Py:   itertools.permutations(arr)
来源：http://dali.316326.xyz/Article/details/gttiefdmjo.html

PHP:  // 手写递归交换
来源：http://dali.nwbrower.top/Article/details/gtetbziifl.html

JS:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtdqyjdfsv.html

TS:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtschzhyxb.html

Java: // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtautfntvx.html

Go:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtzzatrgjq.html

Ruby: arr.permutation.to_a
来源：http://dali.dashuyun.cn/Article/details/gtrmmykxvc.html

C#:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtwgvaptxe.html

[N09] 栈与队列
来源：http://dali.jqgfzy.top/Article/details/gtxayvwjel.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hnqzz.top/Article/details/gttlgcqjii.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xylfe.cn/Article/details/gtsrlbzrso.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tian-w.cn/Article/details/gtetgbmyby.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.mhx1999.top/Article/details/gtqmgaloew.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hnxiangtu.top/Article/details/gtfmrxbbkc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yanxiufei.cn/Article/details/gttfxzevsk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cashguo.top/Article/details/gtfheeumwi.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cheryme.top/Article/details/gtsnvqrnmn.html

[N10] 链表节点定义
来源：http://dali.yj202588.top/Article/details/gtadhrxisn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gzhubu.top/Article/details/gtuchpwijy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.316326.xyz/Article/details/gtgxqmqfax.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.birdmap.top/Article/details/gtdfqkrjwx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yangfankeji.com/Article/details/gtdfygunov.html

Java: class Node { int v; Node next; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtoqtfdbqj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jianghu66.top/Article/details/gtleciswlf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.9152youxi.cn/Article/details/gtelzuvwcv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.vqdsnc.cn/Article/details/gtrkgblkbw.html

[N11] 二叉树中序遍历
来源：http://dali.xziqi.cn/Article/details/gtpvrweaox.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sysykeji.top/Article/details/gtqqvzpzcu.html

PHP:  // 手写递归函数
来源：http://dali.yueranfly.top/Article/details/gtwyrtduxy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jiagoushi.top/Article/details/gtrhthsfyg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ppjwa.cn/Article/details/gtsnymqwxj.html

Java: // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtyqvmhicu.html

Go:   // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gtdnvukeja.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.bjfxy.top/Article/details/gthpfoyigm.html

C#:   // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gtiseonjjy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ppjwa.cn/Article/details/gtyjydnquc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cucudq.cn/Article/details/gtdbpiqcgd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gotoacloud.top/Article/details/gtztzfeqcw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenzaomai.com/Article/details/gtyhnfoyng.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhoulong.xyz/Article/details/gtdhglukxy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.meibo888.top/Article/details/gtpsygetxi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.guowangkeji.top/Article/details/gtvocdsohu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cdnleiting.top/Article/details/gtcnljanvd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hongshengwenyu.top/Article/details/gtlmaglihz.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtddzserfr.html

O. 并发与异步
来源：http://dali.tianlin.xyz/Article/details/gtvwkdnjph.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gthjsrhowg.html

[O01] 启动一个线程
来源：http://dali.andypj.xyz/Article/details/gtpqoilffw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yvedp.cn/Article/details/gtuidltzif.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hywenlv.cn/Article/details/gtvzofwkgd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.haohaochexian.top/Article/details/gtryhlbvpu.html

TS:   // 同 JS
来源：http://dali.yueranfly.top/Article/details/gtehemjwim.html

Java: new Thread(() -> f()).start()
来源：http://dali.mhx1999.top/Article/details/gtqgdlmuim.html

Go:   go f()
来源：http://dali.zhiwuduotai.top/Article/details/gtkavikuqj.html

Ruby: Thread.new { f }
来源：http://dali.andypj.xyz/Article/details/gtuvfuledd.html

C#:   Task.Run(() => F());
来源：http://dali.ydzc1.top/Article/details/gtmswczgth.html

[O02] 使用线程池
来源：http://dali.gzhubu.top/Article/details/gtuymgikdh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jlsjyb.cn/Article/details/gtfnftogfm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zycfv.cn/Article/details/gtzhvpabal.html

JS:   // worker_threads 线程池
来源：http://dali.nwbrower.top/Article/details/gtlixjyqgc.html

TS:   // worker_threads 线程池
来源：http://dali.tanke756.top/Article/details/gttpcfbhcd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.dianchejie.cn/Article/details/gtlvvxlsgz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sweek.top/Article/details/gtgyfltlbc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jqgufenzy.top/Article/details/gtiimcotmv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ehwqpu.com/Article/details/gtbihyxiny.html

[O03] 加锁保护共享数据
来源：http://dali.kuanghao11.cn/Article/details/gtjgksukfx.html

Py:   with lock: shared += 1
来源：http://dali.shuidangran.top/Article/details/gtkzwtwhfp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jlsjyb.cn/Article/details/gtbkmwnnnm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.pengpengdd.cyou/Article/details/gtfhjygyce.html

TS:   // 同 JS
来源：http://dali.andypj.xyz/Article/details/gthyzxecpo.html

Java: synchronized (this) { shared++; }
来源：http://dali.smart0.xyz/Article/details/gtdcdipahs.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nanxinkj.top/Article/details/gtbysrsovq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.kuanghao11.cn/Article/details/gtwevidobi.html

C#:   lock (gate) { shared++; }
来源：http://dali.cucudq.cn/Article/details/gtlalpjcnb.html

[O04] 定义异步函数并等待
来源：http://dali.dashuyun.cn/Article/details/gtovzngdzt.html

Py:   async def f():⏎    await g()
来源：http://dali.sxryk.cn/Article/details/gtmybwuwfp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.snrcjt.cn/Article/details/gtcvluzyve.html

JS:   async function f() { await g(); }
来源：http://dali.jlsjyb.cn/Article/details/gtqjtmajlq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.haohaochexian.top/Article/details/gtkatqncmm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhapohvd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ybcxt.top/Article/details/gtpshaakpl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.dianchejie.cn/Article/details/gtmwgmmwwa.html

C#:   async Task F() { await G(); }
来源：http://dali.316326.xyz/Article/details/gtgocosmms.html

[O05] 并发执行并等待全部完成
来源：http://dali.yuanzhike.top/Article/details/gtschmkvmt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sxryk.cn/Article/details/gtvzcpgamj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gtcqjtojkz.html

JS:   await Promise.all(tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gtqxzzyjsc.html

TS:   await Promise.all(tasks)
来源：http://dali.xuetiantiany.cn/Article/details/gtnihaqvrh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jianghu66.top/Article/details/gtbrnkdevh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sweek.top/Article/details/gttpxqewfw.html

Ruby: threads.map(&:join)
来源：http://dali.gogol.net.cn/Article/details/gtnxjlcgvw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhixingplan.top/Article/details/gtkubgqsuu.html

[O06] 使用进程池
来源：http://dali.zhoulong.xyz/Article/details/gtowmqngsx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hnxiangtu.top/Article/details/gtgjaaifxg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenlongwang.top/Article/details/gtmywibeyb.html

JS:   // child_process / cluster 模块
来源：http://dali.pycfn.com/Article/details/gtbdxmlnaq.html

TS:   // child_process / cluster 模块
来源：http://dali.feifeiyinyue.top/Article/details/gtssozfyql.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hysaishi.cn/Article/details/gtduhaxqmh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tianlin.xyz/Article/details/gtvpwzrttk.html

Ruby: // fork 块
来源：http://dali.chenlongwang.top/Article/details/gtgjsaqlhx.html

C#:   Parallel.For
来源：http://dali.hnxiangtu.top/Article/details/gtscliysio.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwsnmnnwh.html

P. 常用工具函数
来源：http://dali.tian-w.cn/Article/details/gtjzomrdzk.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtrxlyzeei.html

[P01] 生成 UUID
来源：http://dali.hysaishi.cn/Article/details/gthylrcccr.html

Py:   str(uuid.uuid4())
来源：http://dali.hnxiangtu.top/Article/details/gtakbzjbbs.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yanxiufei.cn/Article/details/gtafpgzjph.html

JS:   crypto.randomUUID()
来源：http://dali.vqdsnc.cn/Article/details/gtvlgaxgxj.html

TS:   crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gthvuftjpo.html

Java: UUID.randomUUID().toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtpkvhwuef.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yonumen.top/Article/details/gtcuhowazr.html

Ruby: SecureRandom.uuid
来源：http://dali.yj20258.top/Article/details/gteeazkavu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nwbrower.top/Article/details/gtwrfnfvqq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.meibo888.top/Article/details/gtlyxpkezg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sweek.top/Article/details/gtnmyzilbt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.mhx1999.top/Article/details/gtadcnveab.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yangfankeji.com/Article/details/gtfnkbzbrh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sufxvd.cn/Article/details/gtzdysjuhg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yongpay.top/Article/details/gtizfnsyii.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.havefunace.top/Article/details/gtzhunifpc.html


<!-- 参考信息 -->