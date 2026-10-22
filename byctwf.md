代发 wailian999

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jiagoushi.top/Article/details/gt2bcfkukxx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dyznhfjp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2emjtxebu.html

[L06] 解析响应为 JSON
来源：http://dali.ivvv.top/Article/details/gt2npxavldq.html

Py:   resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gt2zibaoydr.html

PHP:  json_decode($body, true);
来源：http://dali.hnqzz.top/Article/details/gt2zxxquxiv.html

JS:   await resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gt2pwrgnefg.html

TS:   await resp.json()
来源：http://dali.havefunace.top/Article/details/gt2hgjgptbw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yonumen.top/Article/details/gt2hhisfjyd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yongpay.top/Article/details/gt2iwpnbvcr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.daria6918.cn/Article/details/gt2rluoqrux.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cashguo.top/Article/details/gt2rhbxvmmn.html

[L07] 处理 HTTP 状态码
来源：http://dali.jqgufenzy.top/Article/details/gt2xakookev.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.vqdsnc.cn/Article/details/gt2hjlzoqnf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gaohongyu789.top/Article/details/gt2tutdqmbh.html

JS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gt2urjxoetf.html

TS:   resp.ok;  resp.status
来源：http://dali.gotoacloud.top/Article/details/gt2siolyhym.html

Java: resp.statusCode()
来源：http://dali.jinqigfzy.top/Article/details/gt2cyycdcpi.html

Go:   resp.StatusCode
来源：http://dali.jlsjyb.cn/Article/details/gt2mbjiergc.html

Ruby: resp.code.to_i
来源：http://dali.gotoacloud.top/Article/details/gt2pfgnfwhv.html

C#:   (int)resp.StatusCode
来源：http://dali.redwolf501.top/Article/details/gt2tpflsknp.html

[L08] 并发请求多个地址
来源：http://dali.yuanzhike.top/Article/details/gt2afrydprx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.bjfxy.top/Article/details/gt2llkdhjge.html

PHP:  curl_multi_init() 系列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fbsieiom.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2spraapqh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gt2junbcfiu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj20258.top/Article/details/gt2plovtbvv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nwbrower.top/Article/details/gt2himpfvsy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dianchejie.cn/Article/details/gt2klowydug.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cntajtrt.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2tkqxriic.html

M. 命令行 / 进程 / 环境
来源：http://dali.gzhubu.top/Article/details/gt2rznwivba.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2yfpofczy.html

[M01] 读取命令行参数
来源：http://dali.svipenyu.cn/Article/details/gt2hwzwmucl.html

Py:   sys.argv[1:]
来源：http://dali.guannengcc.top/Article/details/gt2zhlxqtxp.html

PHP:  $argv;  $argc;
来源：http://dali.feifeiyinyue.top/Article/details/gt2slifhisz.html

JS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gt2vooadxyo.html

TS:   process.argv.slice(2)
来源：http://dali.ydzc1.top/Article/details/gt2yptjczed.html

Java: args 数组（main 方法参数）
来源：http://dali.andypj.xyz/Article/details/gt2wcifndiw.html

Go:   os.Args[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gt2lmrnorfg.html

Ruby: ARGV
来源：http://dali.xinyue.icu/Article/details/gt2upapppbq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gt2enskxdqz.html

[M02] 读取环境变量
来源：http://dali.yongpay.top/Article/details/gt2qogpvczy.html

Py:   os.environ.get("HOME")
来源：http://dali.9152youxi.cn/Article/details/gt2kitenuen.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.316326.xyz/Article/details/gt2leektfnj.html

JS:   process.env.HOME
来源：http://dali.yangfankeji.com/Article/details/gt2iqdarcyh.html

TS:   process.env.HOME
来源：http://dali.jianghu66.top/Article/details/gt2gaigfuux.html

Java: System.getenv("HOME")
来源：http://dali.ybcxt.top/Article/details/gt2etgqwuhx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yongpay.top/Article/details/gt2rtprcdkj.html

Ruby: ENV["HOME"]
来源：http://dali.zdqjudy.top/Article/details/gt2ukkjlwex.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.mhx1999.top/Article/details/gt2zqsigotp.html

[M03] 执行外部命令
来源：http://dali.nanxuanxn.top/Article/details/gt2zyrfeptx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nanxinkj.top/Article/details/gt2chnmknql.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.meibo888.top/Article/details/gt2avrbxqzf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2wmrwcfyp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xwpbyzyt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vqzgbjzx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxuanxn.top/Article/details/gt2msoafezb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xuetiantiany.cn/Article/details/gt2evlxevxw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aibaodan.cn/Article/details/gt2qxthceby.html

[M04] 获取当前工作目录
来源：http://dali.jqgfzy.top/Article/details/gt2nzwvtkmz.html

Py:   os.getcwd()
来源：http://dali.hnxiangtu.top/Article/details/gt2ebxgyvww.html

PHP:  getcwd();
来源：http://dali.shzxlz.cn/Article/details/gt2bhzwhzfa.html

JS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gt2dwwtknvf.html

TS:   process.cwd()
来源：http://dali.chenlongwang.top/Article/details/gt2xlggsceo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ghzzsbba.html

Go:   os.Getwd()
来源：http://dali.yuanzhike.top/Article/details/gt2czfbjgxx.html

Ruby: Dir.pwd
来源：http://dali.shzxlz.cn/Article/details/gt2arcoawjt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yvedp.cn/Article/details/gt2iwydvrmg.html

[M05] 设置退出码
来源：http://dali.yvedp.cn/Article/details/gt2loxwkeep.html

Py:   sys.exit(1)
来源：http://dali.yj20258888.top/Article/details/gt2dkouzbfm.html

PHP:  exit(1);
来源：http://dali.cheryme.top/Article/details/gt2ippcrsvu.html

JS:   process.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gt2qjwlwipe.html

TS:   process.exit(1)
来源：http://dali.xylfe.cn/Article/details/gt2xzuvnoaq.html

Java: System.exit(1)
来源：http://dali.c1oappe.top/Article/details/gt2hzefktcu.html

Go:   os.Exit(1)
来源：http://dali.0kj1m.cn/Article/details/gt2irbthzvi.html

Ruby: exit 1
来源：http://dali.ydzc1.top/Article/details/gt2otlsrsrt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yuanzhike.top/Article/details/gt2nnszcnag.html

[M06] 向标准错误输出
来源：http://dali.yuanzhike.top/Article/details/gt2qdbocnnf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.9152youxi.cn/Article/details/gt2kitnutku.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.daxiang520.top/Article/details/gt2cyhwuzfz.html

JS:   console.error("err")
来源：http://dali.tanke756.top/Article/details/gt2mjjjvzka.html

TS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gt2gqjqcvuj.html

Java: System.err.println("err")
来源：http://dali.yj20258.top/Article/details/gt2cepjuttj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.feifeiyinyue.top/Article/details/gt2njyfqvde.html

Ruby: warn "err"
来源：http://dali.jianghu66.top/Article/details/gt2xbcvxvty.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cashguo.top/Article/details/gt2ubxauwdb.html

[M07] 判断是否为主入口
来源：http://dali.quarkkingdee.top/Article/details/gt2japbmtns.html

Py:   if __name__ == "__main__":
来源：http://dali.snrcjt.cn/Article/details/gt2cwpfozjx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuanzhike.top/Article/details/gt2spmojaug.html

JS:   require.main === module
来源：http://dali.hnqzz.top/Article/details/gt2skabevti.html

TS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gt2vosfehiw.html

Java: public static void main(String[] args)
来源：http://dali.quarkkingdee.top/Article/details/gt2hpaapoha.html

Go:   func main()
来源：http://dali.jlsjyb.cn/Article/details/gt2hqqjtrfz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.daria6918.cn/Article/details/gt2svvpofgn.html

C#:   static void Main(string[] args)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sisjaunq.html

[M08] 获取系统与运行时信息
来源：http://dali.nanxinkj.top/Article/details/gt2ncofqymv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.andypj.xyz/Article/details/gt2kaybvsap.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zycfv.cn/Article/details/gt2dvfiuzsl.html

JS:   process.platform;  process.version
来源：http://dali.ydzc1.top/Article/details/gt2rjtpzuri.html

TS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gt2ywijxuxz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ttatllbf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj202588.top/Article/details/gt2rewwptua.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xinyue.icu/Article/details/gt2djjviefo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.wangdashe.top/Article/details/gt2vspaucyz.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2bxbrkrsb.html

N. 数据结构与算法
来源：http://dali.bjfxy.top/Article/details/gt2cwicrxlu.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2inlfkodn.html

[N01] 二分查找（有序数组）
来源：http://dali.jyoumei.cn/Article/details/gt2ycnexymd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yongpay.top/Article/details/gt2pndirguv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zycfv.cn/Article/details/gt2lzwdycgk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxinkj.top/Article/details/gt2ezhnbcde.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xziqi.cn/Article/details/gt2myrgjyae.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2apslwxqu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guannengcc.top/Article/details/gt2xciynodd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hysaishi.cn/Article/details/gt2xanuakno.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.fzhhl.top/Article/details/gt2cuypmavu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.meibo888.top/Article/details/gt2vgfmromx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gt2qhkmuiqb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hnqzz.top/Article/details/gt2xnfmhndl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gt2ddztizav.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gt2tbkenmgz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gotoacloud.top/Article/details/gt2dvuwztqu.html

Go:   slices.Sort(arr)
来源：http://dali.andypj.xyz/Article/details/gt2vsoznuzk.html

Ruby: arr.sort
来源：http://dali.aizwys.cn/Article/details/gt2acsvxlij.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenzaomai.com/Article/details/gt2xmtcsaps.html

[N03] 快速排序（分治示例）
来源：http://dali.xuanzx.com/Article/details/gt2idbrjqjs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.daria6918.cn/Article/details/gt2zukuywkl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ybcxt.top/Article/details/gt2cgqzjpoz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daxiang520.top/Article/details/gt2csaikeef.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hysaishi.cn/Article/details/gt2pewwlzym.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ytbytpif.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenzaomai.com/Article/details/gt2gdvsyhuo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.pengpengdd.cyou/Article/details/gt2dqzauxvh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.andypj.xyz/Article/details/gt2nyuohozh.html

[N04] 斐波那契数列
来源：http://dali.ehwqpu.com/Article/details/gt2krpztahg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2bhtbrpsz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.bjfxy.top/Article/details/gt2omwgvjeu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gt2dvsqkquu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gt2kohjraba.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rbklllal.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.havefunace.top/Article/details/gt2bmrmhvtp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gt2dyofaqvh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gt2qggfmcwp.html

[N05] 最大公约数
来源：http://dali.tian-w.cn/Article/details/gt2hqxjmyzp.html

Py:   math.gcd(a, b)
来源：http://dali.aizwys.cn/Article/details/gt2uupogcrx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2jdgbxouo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gt2mhvaytbn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.andypj.xyz/Article/details/gt2ovkxmlcz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.pengpengdd.cyou/Article/details/gt2ccgmaujp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nanxinkj.top/Article/details/gt2olqrjvkb.html

Ruby: a.gcd(b)
来源：http://dali.quarkkingdee.top/Article/details/gt2vswdtoll.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.havefunace.top/Article/details/gt2mvfqtaek.html

[N06] 判断回文字符串
来源：http://dali.daria6918.cn/Article/details/gt2vwipqhmc.html

Py:   s == s[::-1]
来源：http://dali.zdqjudy.top/Article/details/gt2chwjfnaj.html

PHP:  $s === strrev($s);
来源：http://dali.guowangkeji.top/Article/details/gt2klogzdnh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gt2vedjlyfx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jignyxdq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.aizwys.cn/Article/details/gt2vkvknxqg.html

Go:   // 双指针从两端比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kcblqefg.html

Ruby: s == s.reverse
来源：http://dali.0kj1m.cn/Article/details/gt2xdwdzjcz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mjfxzugc.html

[N07] 两数之和（返回下标）
来源：http://dali.zhengqikj.top/Article/details/gt2ingzyfux.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shzxlz.cn/Article/details/gt2oyrgjaed.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yuanzhike.top/Article/details/gt2xzjsndag.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hkaobrko.html

TS:   // 手写 Map<string, number>
来源：http://dali.yvedp.cn/Article/details/gt2rxtadhqt.html

Java: // 手写 HashMap
来源：http://dali.hongshengwenyu.top/Article/details/gt2gjemnkte.html

Go:   // 手写 map[int]int
来源：http://dali.sysykeji.top/Article/details/gt2jorzollc.html

Ruby: // 手写 Hash
来源：http://dali.mhx1999.top/Article/details/gt2aklrttmr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.9152youxi.cn/Article/details/gt2beivkpol.html

[N08] 生成全排列
来源：http://dali.nanxinkj.top/Article/details/gt2yobxirfd.html

Py:   itertools.permutations(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2hmtgqoww.html

PHP:  // 手写递归交换
来源：http://dali.yueranfly.top/Article/details/gt2xrzcoukb.html

JS:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gt2ilfwvpuk.html

TS:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gt2krvjqaoq.html

Java: // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2blmqrbfa.html

Go:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gt2eflmesgk.html

Ruby: arr.permutation.to_a
来源：http://dali.nanxuanxn.top/Article/details/gt2czxaymys.html

C#:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gt2ajxwwcpp.html

[N09] 栈与队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2apsuicql.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhengqikj.top/Article/details/gt2vidhfses.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.meibo888.top/Article/details/gt2cndeubax.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gt2vbonfpve.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.andypj.xyz/Article/details/gt2aitafdwr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yvedp.cn/Article/details/gt2czxykokb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.haohaochexian.top/Article/details/gt2dgsrcnhc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.bjfxy.top/Article/details/gt2pfruwmyi.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhengqikj.top/Article/details/gt2eeisycmp.html

[N10] 链表节点定义
来源：http://dali.iojbl.cn/Article/details/gt2jitvwowh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.guannengcc.top/Article/details/gt2hutbawlu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xinyue.icu/Article/details/gt2sijkcqix.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rirqxqrm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nanxuanxn.top/Article/details/gt2ovasgehd.html

Java: class Node { int v; Node next; }
来源：http://dali.zycfv.cn/Article/details/gt2ykihbnyx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ufvjrgvn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.guannengcc.top/Article/details/gt2ipsrxwoo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ydzc1.top/Article/details/gt2ofzwkqyi.html

[N11] 二叉树中序遍历
来源：http://dali.tian-w.cn/Article/details/gt2mbfafgqs.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cucudq.cn/Article/details/gt2vufzoxdk.html

PHP:  // 手写递归函数
来源：http://dali.nanxinkj.top/Article/details/gt2elqbukna.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jlsjyb.cn/Article/details/gt2hrgitfhg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guowangkeji.top/Article/details/gt2chmbbqah.html

Java: // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gt2jxxcseyf.html

Go:   // 手写递归
来源：http://dali.haohaochexian.top/Article/details/gt2ylwherth.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.iojbl.cn/Article/details/gt2rmlsmllx.html

C#:   // 手写递归
来源：http://dali.316326.xyz/Article/details/gt2jztavyqp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.kuanghao11.cn/Article/details/gt2eycmvljc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cucudq.cn/Article/details/gt2hfrraugj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cucudq.cn/Article/details/gt2xqyucfwo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258888.top/Article/details/gt2peimbxwf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhixingplan.top/Article/details/gt2snpmaand.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guowangkeji.top/Article/details/gt2kkrbgqgo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.0kj1m.cn/Article/details/gt2rccolrzm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jyoumei.cn/Article/details/gt2dhsinbyw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnqzz.top/Article/details/gt2genoitmw.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2zlykdzmk.html

O. 并发与异步
来源：http://dali.vqdsnc.cn/Article/details/gt2ulsrnooa.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2aurgcqmo.html

[O01] 启动一个线程
来源：http://dali.wangdashe.top/Article/details/gt2qdojxtrz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yuxming.cn/Article/details/gt2fnreljtn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.smart0.xyz/Article/details/gt2ocuujqxa.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsqthoc.html

TS:   // 同 JS
来源：http://dali.zhongyouzk.top/Article/details/gt2iyfricgf.html

Java: new Thread(() -> f()).start()
来源：http://dali.snrcjt.cn/Article/details/gt2xdbtjhfj.html

Go:   go f()
来源：http://dali.jqgufenzy.top/Article/details/gt2xscpsjup.html

Ruby: Thread.new { f }
来源：http://dali.hywenlv.cn/Article/details/gt2pavfqduw.html

C#:   Task.Run(() => F());
来源：http://dali.yuanzhike.top/Article/details/gt2eatioxlf.html

[O02] 使用线程池
来源：http://dali.cdnleiting.top/Article/details/gt2tpunhmzq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cqqwz.cn/Article/details/gt2xumzylcs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hywenlv.cn/Article/details/gt2psrsgjny.html

JS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gt2dtgtfjtq.html

TS:   // worker_threads 线程池
来源：http://dali.jiagoushi.top/Article/details/gt2thgkowpu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.aibaodan.cn/Article/details/gt2jlqszodk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj20258.top/Article/details/gt2bvxxtnal.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.dashuyun.cn/Article/details/gt2cptofqcj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.birdmap.top/Article/details/gt2jpaoswbh.html

[O03] 加锁保护共享数据
来源：http://dali.wangshuangyany.cn/Article/details/gt2rdxpadtj.html

Py:   with lock: shared += 1
来源：http://dali.ppjwa.cn/Article/details/gt2cbflnlrn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yonumen.top/Article/details/gt2uqizsnsk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinqigfzy.top/Article/details/gt2gcjzrvwq.html

TS:   // 同 JS
来源：http://dali.dashuyun.cn/Article/details/gt2rxebhjgi.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ctzyurri.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sysykeji.top/Article/details/gt2yanneqbz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.quarkkingdee.top/Article/details/gt2iffxtzhp.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenlongwang.top/Article/details/gt2ruhisipx.html

[O04] 定义异步函数并等待
来源：http://dali.9152youxi.cn/Article/details/gt2pvunwhni.html

Py:   async def f():⏎    await g()
来源：http://dali.jqgufenzy.top/Article/details/gt2mhvptevl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jqgufenzy.top/Article/details/gt2qvmohbtj.html

JS:   async function f() { await g(); }
来源：http://dali.jiagoushi.top/Article/details/gt2xhgmtouj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2plwsvlxv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2lfotyqav.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nwbrower.top/Article/details/gt2bnuihqka.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.vqdsnc.cn/Article/details/gt2nflooqyz.html

C#:   async Task F() { await G(); }
来源：http://dali.haohaochexian.top/Article/details/gt2pyspvhof.html

[O05] 并发执行并等待全部完成
来源：http://dali.zdqjudy.top/Article/details/gt2dhqzfncg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xylfe.cn/Article/details/gt2jywuvdmt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nanxinkj.top/Article/details/gt2winwixek.html

JS:   await Promise.all(tasks)
来源：http://dali.tanke756.top/Article/details/gt2euplylpz.html

TS:   await Promise.all(tasks)
来源：http://dali.sufxvd.cn/Article/details/gt2jijsunmb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2satzqdrq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhiwuduotai.top/Article/details/gt2wjdheljr.html

Ruby: threads.map(&:join)
来源：http://dali.gzhubu.top/Article/details/gt2lwjckniq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.daxiang520.top/Article/details/gt2gyeptmmh.html

[O06] 使用进程池
来源：http://dali.cdnleiting.top/Article/details/gt2ceonujmg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tianlin.xyz/Article/details/gt2oooemqix.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zdqjudy.top/Article/details/gt2ztdntlve.html

JS:   // child_process / cluster 模块
来源：http://dali.zycfv.cn/Article/details/gt2drzeiqmk.html

TS:   // child_process / cluster 模块
来源：http://dali.redwolf501.top/Article/details/gt2kmxhilfy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.svipenyu.cn/Article/details/gt2rbonjdxl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.meibo888.top/Article/details/gt2wtsaatjt.html

Ruby: // fork 块
来源：http://dali.fzhhl.top/Article/details/gt2xlkppbkq.html

C#:   Parallel.For
来源：http://dali.ehwqpu.com/Article/details/gt2tlbsigvq.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gnqrcblm.html

P. 常用工具函数
来源：http://dali.fzhhl.top/Article/details/gt2qcfyfltc.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2jlslkwnc.html

[P01] 生成 UUID
来源：http://dali.svipenyu.cn/Article/details/gt2xujnscjf.html

Py:   str(uuid.uuid4())
来源：http://dali.guannengcc.top/Article/details/gt2htrpxmit.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhiwuduotai.top/Article/details/gt2stifroqu.html

JS:   crypto.randomUUID()
来源：http://dali.smart0.xyz/Article/details/gt2xllevdgp.html

TS:   crypto.randomUUID()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dkjeiexs.html

Java: UUID.randomUUID().toString()
来源：http://dali.cdnleiting.top/Article/details/gt2mscnziar.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gogol.net.cn/Article/details/gt2poxfcfcw.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigufen.top/Article/details/gt2nsmgvnjf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.wangdashe.top/Article/details/gt2qecxbcgs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cqqwz.cn/Article/details/gt2tzitckja.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.redwolf501.top/Article/details/gt2bqqmkrwv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yanxiufei.cn/Article/details/gt2breiuwkn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenjidiqi.icu/Article/details/gt2yylsttpa.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jlsjyb.cn/Article/details/gt2fsseoluj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yvedp.cn/Article/details/gt2iflgpgne.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tanke756.top/Article/details/gt2wngbcxml.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cashguo.top/Article/details/gt2xhcehnqn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.316326.xyz/Article/details/gt2oivhjgyv.html

[P03] 生成短随机字符串
来源：http://dali.xuanzx.com/Article/details/gt2iggamexm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuetiantiany.cn/Article/details/gt2exlrgjgm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sweek.top/Article/details/gt2yzaktqwi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2emnfycbt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258888.top/Article/details/gt2jzjfosje.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hnqzz.top/Article/details/gt2mxognpmg.html


<!-- 参考信息 -->