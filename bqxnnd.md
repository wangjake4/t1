代发 wailian999

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ytpynyrg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.haohaochexian.top/Article/details/gt2upjoxlzx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.fzhhl.top/Article/details/gt2elwfpewx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2isdxcqvz.html

[L07] 处理 HTTP 状态码
来源：http://dali.ivvv.top/Article/details/gt2odiksdrl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.daria6918.cn/Article/details/gt2olvdotvf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cqqwz.cn/Article/details/gt2ufzgzupq.html

JS:   resp.ok;  resp.status
来源：http://dali.guannengcc.top/Article/details/gt2qgihkczh.html

TS:   resp.ok;  resp.status
来源：http://dali.hongshengwenyu.top/Article/details/gt2jnyczpiy.html

Java: resp.statusCode()
来源：http://dali.jqgufenzy.top/Article/details/gt2ixtslpza.html

Go:   resp.StatusCode
来源：http://dali.yonumen.top/Article/details/gt2bhwtgbea.html

Ruby: resp.code.to_i
来源：http://dali.jiagoushi.top/Article/details/gt2razhtjyx.html

C#:   (int)resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2suhenyij.html

[L08] 并发请求多个地址
来源：http://dali.iojbl.cn/Article/details/gt2jofrglgd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.dianchejie.cn/Article/details/gt2xaqkvcii.html

PHP:  curl_multi_init() 系列
来源：http://dali.meibo888.top/Article/details/gt2raesuhhg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aibaodan.cn/Article/details/gt2rxyatrms.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jianghu66.top/Article/details/gt2mvxahcca.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sufxvd.cn/Article/details/gt2xsjntvxd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nicsnqmy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj202588.top/Article/details/gt2lzwipbva.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cqqwz.cn/Article/details/gt2gytfdvew.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2iubbnsst.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vvkmopic.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2bifmzpfb.html

[M01] 读取命令行参数
来源：http://dali.yangfankeji.com/Article/details/gt2dibabesy.html

Py:   sys.argv[1:]
来源：http://dali.zdqjudy.top/Article/details/gt2nmcbeioq.html

PHP:  $argv;  $argc;
来源：http://dali.jyoumei.cn/Article/details/gt2uwdfxkbl.html

JS:   process.argv.slice(2)
来源：http://dali.xziqi.cn/Article/details/gt2gapabydx.html

TS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gt2xywwexts.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2siajtvrl.html

Go:   os.Args[1:]
来源：http://dali.zdqjudy.top/Article/details/gt2ncnxmyhp.html

Ruby: ARGV
来源：http://dali.zhengqikj.top/Article/details/gt2jipogumw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hywenlv.cn/Article/details/gt2hljqdkbk.html

[M02] 读取环境变量
来源：http://dali.yj202588.top/Article/details/gt2xaqiqsxe.html

Py:   os.environ.get("HOME")
来源：http://dali.bjfxy.top/Article/details/gt2gjzpwfnz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yvedp.cn/Article/details/gt2ufpavddc.html

JS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gt2yobvmosq.html

TS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gt2ncfumnuh.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgavpew.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gt2nsymscuh.html

Ruby: ENV["HOME"]
来源：http://dali.nanxinkj.top/Article/details/gt2cmljsxsf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gt2hkielzlj.html

[M03] 执行外部命令
来源：http://dali.jinghuilouyu.cn/Article/details/gt2puziyttw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guowangkeji.top/Article/details/gt2gmrxizoj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hysaishi.cn/Article/details/gt2wtxxrehu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj202588.top/Article/details/gt2zpvnevdb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.daria6918.cn/Article/details/gt2mxtqloop.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.smart0.xyz/Article/details/gt2dvwgebeb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sufxvd.cn/Article/details/gt2bduicmze.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qiokojjy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinqigufen.top/Article/details/gt2wqdzxdgi.html

[M04] 获取当前工作目录
来源：http://dali.sysykeji.top/Article/details/gt2kvvqozgt.html

Py:   os.getcwd()
来源：http://dali.zhongyouzk.top/Article/details/gt2jllojpad.html

PHP:  getcwd();
来源：http://dali.sufxvd.cn/Article/details/gt2sfiwukzp.html

JS:   process.cwd()
来源：http://dali.yuxming.cn/Article/details/gt2krhylwyh.html

TS:   process.cwd()
来源：http://dali.gogol.net.cn/Article/details/gt2lmfmgaaw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.havefunace.top/Article/details/gt2hopjemnk.html

Go:   os.Getwd()
来源：http://dali.gaohongyu789.top/Article/details/gt2hdtbgbqa.html

Ruby: Dir.pwd
来源：http://dali.jlsjyb.cn/Article/details/gt2pnvayffb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zycfv.cn/Article/details/gt2figwbads.html

[M05] 设置退出码
来源：http://dali.hywenlv.cn/Article/details/gt2xhlcudnk.html

Py:   sys.exit(1)
来源：http://dali.yj20258888.top/Article/details/gt2rgjsojcw.html

PHP:  exit(1);
来源：http://dali.jqgfzy.top/Article/details/gt2hrfcrqvn.html

JS:   process.exit(1)
来源：http://dali.birdmap.top/Article/details/gt2giijrizl.html

TS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gt2kofaywsg.html

Java: System.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gt2esxkkohr.html

Go:   os.Exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2geqalclm.html

Ruby: exit 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mpgykryr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhixingplan.top/Article/details/gt2kabfncqe.html

[M06] 向标准错误输出
来源：http://dali.smart0.xyz/Article/details/gt2iezuxqhc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cashguo.top/Article/details/gt2deeeelxd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hnqzz.top/Article/details/gt2txcuedkj.html

JS:   console.error("err")
来源：http://dali.wangshuangyany.cn/Article/details/gt2huwzatyj.html

TS:   console.error("err")
来源：http://dali.hywenlv.cn/Article/details/gt2sldcnswq.html

Java: System.err.println("err")
来源：http://dali.dianchejie.cn/Article/details/gt2uyakcmxa.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sxryk.cn/Article/details/gt2rpztzsgv.html

Ruby: warn "err"
来源：http://dali.bjfxy.top/Article/details/gt2ckyqxasp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nanxinkj.top/Article/details/gt2slyhvipm.html

[M07] 判断是否为主入口
来源：http://dali.tanke756.top/Article/details/gt2arltwryx.html

Py:   if __name__ == "__main__":
来源：http://dali.shuidangran.top/Article/details/gt2ooptgsot.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ppjwa.cn/Article/details/gt2ivypsiii.html

JS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gt2zahgudle.html

TS:   require.main === module
来源：http://dali.mhx1999.top/Article/details/gt2odavhrsz.html

Java: public static void main(String[] args)
来源：http://dali.zdqjudy.top/Article/details/gt2rbyzdvyv.html

Go:   func main()
来源：http://dali.sysykeji.top/Article/details/gt2jaivqppm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jianghu66.top/Article/details/gt2jthofgna.html

C#:   static void Main(string[] args)
来源：http://dali.jinqigfzy.top/Article/details/gt2njcbzbyh.html

[M08] 获取系统与运行时信息
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kizaxajv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hongshengwenyu.top/Article/details/gt2kcqdhgke.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xinyue.icu/Article/details/gt2iqxtfsdt.html

JS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gt2tqfvjxsa.html

TS:   process.platform;  process.version
来源：http://dali.cashguo.top/Article/details/gt2vlutieeo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nwbrower.top/Article/details/gt2fxxyqpjj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.wangshuangyany.cn/Article/details/gt2jxpcjhwb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.pycfn.com/Article/details/gt2opsqramx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tian-w.cn/Article/details/gt2prvsmdrw.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2difbdmow.html

N. 数据结构与算法
来源：http://dali.shzxlz.cn/Article/details/gt2xqvbcekc.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2wdabnjlh.html

[N01] 二分查找（有序数组）
来源：http://dali.sysykeji.top/Article/details/gt2lfxglwfd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yonumen.top/Article/details/gt2lucgzrsn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sxryk.cn/Article/details/gt2sowsxipq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cucudq.cn/Article/details/gt2ofawycms.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zycfv.cn/Article/details/gt2swrphqyr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2otwnlxih.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gt2eytgeaxg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.haohaochexian.top/Article/details/gt2qhqqtjiq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2vgjthowk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.mhx1999.top/Article/details/gt2avgpchmy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangshuangyany.cn/Article/details/gt2jscrnmxy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jianghu66.top/Article/details/gt2rcybvxnh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sysykeji.top/Article/details/gt2zkdvdztx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.redwolf501.top/Article/details/gt2twyipxzf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinqigufen.top/Article/details/gt2hkzgfaze.html

Go:   slices.Sort(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2iscwpstv.html

Ruby: arr.sort
来源：http://dali.yj20258888.top/Article/details/gt2afbxvjxo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuanzx.com/Article/details/gt2njkmrzle.html

[N03] 快速排序（分治示例）
来源：http://dali.daria6918.cn/Article/details/gt2gbtazfmu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zbkbezgb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.andypj.xyz/Article/details/gt2lrdftleq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gzhubu.top/Article/details/gt2wztcraby.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gt2fvkzwltz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuxming.cn/Article/details/gt2cpgxcols.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jiagoushi.top/Article/details/gt2lsghfjtj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yongpay.top/Article/details/gt2hlpoomvv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhongyouzk.top/Article/details/gt2scjzioxv.html

[N04] 斐波那契数列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2stjxbffe.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258888.top/Article/details/gt2wpflyywu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj20258888.top/Article/details/gt2aafiwwbr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgufenzy.top/Article/details/gt2psiiycoh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gt2uokedyxs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenzaomai.com/Article/details/gt2wupldnwr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2htsuzfvj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lacayjiq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nczboepu.html

[N05] 最大公约数
来源：http://dali.sysykeji.top/Article/details/gt2jinkrllu.html

Py:   math.gcd(a, b)
来源：http://dali.nwbrower.top/Article/details/gt2pevqhoxh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xinyue.icu/Article/details/gt2qmzgmwte.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sweek.top/Article/details/gt2dalxuadj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dianchejie.cn/Article/details/gt2romxffdu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xuanzx.com/Article/details/gt2cskvbwdh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnxiangtu.top/Article/details/gt2vqxqcxqu.html

Ruby: a.gcd(b)
来源：http://dali.svipenyu.cn/Article/details/gt2ipfzdtjv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinqigufen.top/Article/details/gt2embhinbk.html

[N06] 判断回文字符串
来源：http://dali.yongpay.top/Article/details/gt2dxlbdkfa.html

Py:   s == s[::-1]
来源：http://dali.hfpthk.cn/Article/details/gt2escbswjf.html

PHP:  $s === strrev($s);
来源：http://dali.smart0.xyz/Article/details/gt2qvaftewz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gt2srppbiov.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fjpyivvw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tanke756.top/Article/details/gt2obmgmyxp.html

Go:   // 双指针从两端比较
来源：http://dali.gaohongyu789.top/Article/details/gt2fhuoudfz.html

Ruby: s == s.reverse
来源：http://dali.zdqjudy.top/Article/details/gt2xhglhkej.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xziqi.cn/Article/details/gt2ybypvirw.html

[N07] 两数之和（返回下标）
来源：http://dali.9152youxi.cn/Article/details/gt2wuxwpjbu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jlsjyb.cn/Article/details/gt2tnbewxae.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj202588.top/Article/details/gt2pszulrvc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nanxuanxn.top/Article/details/gt2pcztogcl.html

TS:   // 手写 Map<string, number>
来源：http://dali.tanke756.top/Article/details/gt2ultyomin.html

Java: // 手写 HashMap
来源：http://dali.hnqzz.top/Article/details/gt2wurifiex.html

Go:   // 手写 map[int]int
来源：http://dali.yj20258.top/Article/details/gt2gqbtoiti.html

Ruby: // 手写 Hash
来源：http://dali.ivvv.top/Article/details/gt2aqvqjonl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tanke756.top/Article/details/gt2beexnujz.html

[N08] 生成全排列
来源：http://dali.chenlongwang.top/Article/details/gt2qvvnpukl.html

Py:   itertools.permutations(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2evgmenzv.html

PHP:  // 手写递归交换
来源：http://dali.redwolf501.top/Article/details/gt2fmdyoset.html

JS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gt2rjqbpkse.html

TS:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gt2owkmjutv.html

Java: // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gt2tnxwpbii.html

Go:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gt2jzrqvoho.html

Ruby: arr.permutation.to_a
来源：http://dali.tianlin.xyz/Article/details/gt2hqmzfmce.html

C#:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gt2axqjshtk.html

[N09] 栈与队列
来源：http://dali.cashguo.top/Article/details/gt2icyctndt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2tjfoxaak.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xylfe.cn/Article/details/gt2imyyjcgm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qazomaxy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj20258888.top/Article/details/gt2pwxqqtdg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hywenlv.cn/Article/details/gt2fshqnfzj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.feifeiyinyue.top/Article/details/gt2tjforrwe.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hnqzz.top/Article/details/gt2ohjjjmmn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jyoumei.cn/Article/details/gt2jitbwppk.html

[N10] 链表节点定义
来源：http://dali.hnqzz.top/Article/details/gt2jmumksrw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.fzhhl.top/Article/details/gt2hwcskims.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.fzhhl.top/Article/details/gt2utpaumwp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.c1oappe.top/Article/details/gt2ildyrdvg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tianlin.xyz/Article/details/gt2xcikntdj.html

Java: class Node { int v; Node next; }
来源：http://dali.shzxlz.cn/Article/details/gt2bwkqzfqg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.haohaochexian.top/Article/details/gt2rxvnwfae.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nanxinkj.top/Article/details/gt2mqxiring.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zycfv.cn/Article/details/gt2odwgvbmx.html

[N11] 二叉树中序遍历
来源：http://dali.fengsongda.top/Article/details/gt2pghwlkah.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ehwqpu.com/Article/details/gt2ayutknjn.html

PHP:  // 手写递归函数
来源：http://dali.0kj1m.cn/Article/details/gt2sszuvkrb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhengqikj.top/Article/details/gt2duoqrlvj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hywenlv.cn/Article/details/gt2rmimrcoy.html

Java: // 手写递归
来源：http://dali.fengsongda.top/Article/details/gt2fdfjmjku.html

Go:   // 手写递归
来源：http://dali.wangdashe.top/Article/details/gt2cchqlfxw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hongshengwenyu.top/Article/details/gt2lvhgrmpg.html

C#:   // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gt2qzvpoulu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.iojbl.cn/Article/details/gt2nbmbglnw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.feifeiyinyue.top/Article/details/gt2urbmbeam.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhengqikj.top/Article/details/gt2zlgyuzxn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tanke756.top/Article/details/gt2ytxkbsor.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gogol.net.cn/Article/details/gt2ikpzpkco.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yanxiufei.cn/Article/details/gt2xmhayngr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shuidangran.top/Article/details/gt2cosioaba.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.aibaodan.cn/Article/details/gt2qnyojrmp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuanzx.com/Article/details/gt2mewivsuq.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2muzybyja.html

O. 并发与异步
来源：http://dali.cashguo.top/Article/details/gt2kuebdwey.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2nobbjntz.html

[O01] 启动一个线程
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ptoeuaut.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zpxzwdzw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenlongwang.top/Article/details/gt2nybrumeb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.daria6918.cn/Article/details/gt2easidaga.html

TS:   // 同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ewefigoj.html

Java: new Thread(() -> f()).start()
来源：http://dali.nwbrower.top/Article/details/gt2vvtrjhsw.html

Go:   go f()
来源：http://dali.iojbl.cn/Article/details/gt2eptbesno.html

Ruby: Thread.new { f }
来源：http://dali.xziqi.cn/Article/details/gt2hmciivfu.html

C#:   Task.Run(() => F());
来源：http://dali.zhixingplan.top/Article/details/gt2yjsctscm.html

[O02] 使用线程池
来源：http://dali.aibaodan.cn/Article/details/gt2gbqjljbn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xuanzx.com/Article/details/gt2yuhxlymz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.snrcjt.cn/Article/details/gt2golwlxjm.html

JS:   // worker_threads 线程池
来源：http://dali.cqqwz.cn/Article/details/gt2vpicmpwy.html

TS:   // worker_threads 线程池
来源：http://dali.yanxiufei.cn/Article/details/gt2sjwwxztz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj202588.top/Article/details/gt2onolisxb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cdnleiting.top/Article/details/gt2zobyjabn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.mhx1999.top/Article/details/gt2uuvbiubw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yuanzhike.top/Article/details/gt2smjxjlyu.html

[O03] 加锁保护共享数据
来源：http://dali.fengsongda.top/Article/details/gt2pdpqlzws.html

Py:   with lock: shared += 1
来源：http://dali.fzhhl.top/Article/details/gt2tawyluht.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xuetiantiany.cn/Article/details/gt2jdjhjoct.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.guannengcc.top/Article/details/gt2vdkooffs.html

TS:   // 同 JS
来源：http://dali.wangdashe.top/Article/details/gt2jrzoudug.html

Java: synchronized (this) { shared++; }
来源：http://dali.gotoacloud.top/Article/details/gt2dkgzsevu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.guannengcc.top/Article/details/gt2xyugvjxi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yongpay.top/Article/details/gt2educogrh.html

C#:   lock (gate) { shared++; }
来源：http://dali.dashuyun.cn/Article/details/gt2epxtlsuz.html

[O04] 定义异步函数并等待
来源：http://dali.hnqzz.top/Article/details/gt2eypnbkhz.html

Py:   async def f():⏎    await g()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vwpjzlfh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cqqwz.cn/Article/details/gt2quvlxzop.html

JS:   async function f() { await g(); }
来源：http://dali.hysaishi.cn/Article/details/gt2lmtulcne.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jianghu66.top/Article/details/gt2ybhwbauv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gogol.net.cn/Article/details/gt2adablevl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhongyouzk.top/Article/details/gt2gpwfdluf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hammf.cn/Article/details/gt2ddlwmacb.html

C#:   async Task F() { await G(); }
来源：http://dali.cucudq.cn/Article/details/gt2xtvzfveo.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhiwuduotai.top/Article/details/gt2zdmlmjkf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.daria6918.cn/Article/details/gt2oggvqjsc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cashguo.top/Article/details/gt2zlcvhrex.html

JS:   await Promise.all(tasks)
来源：http://dali.bjfxy.top/Article/details/gt2nfxwhaqk.html

TS:   await Promise.all(tasks)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vpnizetc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hysaishi.cn/Article/details/gt2booaxgwf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cashguo.top/Article/details/gt2rmcuhmzw.html

Ruby: threads.map(&:join)
来源：http://dali.fzhhl.top/Article/details/gt2bbqsnwpl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tianlin.xyz/Article/details/gt2gfdwsvvk.html

[O06] 使用进程池
来源：http://dali.bjfxy.top/Article/details/gt2jhagjhzx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xuanzx.com/Article/details/gt2zojcgwkq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xylfe.cn/Article/details/gt2cncsevch.html

JS:   // child_process / cluster 模块
来源：http://dali.fzhhl.top/Article/details/gt2lmskobby.html

TS:   // child_process / cluster 模块
来源：http://dali.gotoacloud.top/Article/details/gt2hmuhscwg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bzyqbgjb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kxwlrkcr.html

Ruby: // fork 块
来源：http://dali.chenjidiqi.icu/Article/details/gt2uibsotor.html

C#:   Parallel.For
来源：http://dali.aizwys.cn/Article/details/gt2frgnoban.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2gpcnqzbw.html

P. 常用工具函数
来源：http://dali.hysaishi.cn/Article/details/gt2ctxbjqdu.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2osjyjqbr.html

[P01] 生成 UUID
来源：http://dali.chenlongwang.top/Article/details/gt2tezxuver.html

Py:   str(uuid.uuid4())
来源：http://dali.xziqi.cn/Article/details/gt2bywkonqs.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jianghu66.top/Article/details/gt2ybnbigdl.html

JS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gt2fpmirfsl.html

TS:   crypto.randomUUID()
来源：http://dali.yuanzhike.top/Article/details/gt2bkaupxsc.html

Java: UUID.randomUUID().toString()
来源：http://dali.iojbl.cn/Article/details/gt2iiscdlfy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gt2asdrdxpx.html

Ruby: SecureRandom.uuid
来源：http://dali.xinyue.icu/Article/details/gt2khdopmhu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhixingplan.top/Article/details/gt2czmemhej.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hysaishi.cn/Article/details/gt2ermfcvao.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yvedp.cn/Article/details/gt2zmdzqxhu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shzxlz.cn/Article/details/gt2gkqsngrf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nanxinkj.top/Article/details/gt2plnyhmcp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.quarkkingdee.top/Article/details/gt2ubdswrxz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xylfe.cn/Article/details/gt2fejzrmed.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.9152youxi.cn/Article/details/gt2ewxktwzw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sxryk.cn/Article/details/gt2daqpsjvx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2sszaayvr.html

[P03] 生成短随机字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2svylonzz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.andypj.xyz/Article/details/gt2esmsouuj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.guowangkeji.top/Article/details/gt2cjfvvyut.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shuidangran.top/Article/details/gt2dktjfitd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daxiang520.top/Article/details/gt2ojqkmaaq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yj20258888.top/Article/details/gt2fubpsgat.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.bjfxy.top/Article/details/gt2wyhjqkdr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.dianchejie.cn/Article/details/gt2gcdyqdgz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.quarkkingdee.top/Article/details/gt2xehqovxp.html

[P04] 求长度
来源：http://dali.jinqigufen.top/Article/details/gt2ytdzndap.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tanke756.top/Article/details/gt2gutwlypg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gt2xhzxrerk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nwbrower.top/Article/details/gt2xcbyoxyd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.316326.xyz/Article/details/gt2shsqirfe.html


<!-- 参考信息 -->