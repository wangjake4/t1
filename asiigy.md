代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.zdqjudy.top/Article/details/gt2mxidyrph.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ahgdjezp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.wangdashe.top/Article/details/gt2rdudrkfx.html

JS:   resp.ok;  resp.status
来源：http://dali.sufxvd.cn/Article/details/gt2xkixzlnk.html

TS:   resp.ok;  resp.status
来源：http://dali.cashguo.top/Article/details/gt2brranrpd.html

Java: resp.statusCode()
来源：http://dali.316326.xyz/Article/details/gt2uiovynuw.html

Go:   resp.StatusCode
来源：http://dali.jinqigfzy.top/Article/details/gt2qvrhgsoq.html

Ruby: resp.code.to_i
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dqwpdjho.html

C#:   (int)resp.StatusCode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2awvoxnpe.html

[L08] 并发请求多个地址
来源：http://dali.jqgfzy.top/Article/details/gt2zplcgohk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hongshengwenyu.top/Article/details/gt2seolsnqj.html

PHP:  curl_multi_init() 系列
来源：http://dali.gzhubu.top/Article/details/gt2plrzkfjb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gt2pgralpry.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnqzz.top/Article/details/gt2ypkamxqz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj202588.top/Article/details/gt2ptxcpybq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.wangshuangyany.cn/Article/details/gt2lozcchyc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mtzgwfoy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258888.top/Article/details/gt2jrwpabjs.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2yitqjalc.html

M. 命令行 / 进程 / 环境
来源：http://dali.svipenyu.cn/Article/details/gt2rejlaxvf.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2qnmqvsms.html

[M01] 读取命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bmypjkrm.html

Py:   sys.argv[1:]
来源：http://dali.chenzaomai.com/Article/details/gt2sxehxzsk.html

PHP:  $argv;  $argc;
来源：http://dali.xziqi.cn/Article/details/gt2rstbqugk.html

JS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gt2yuvxekdo.html

TS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gt2ffffhmpl.html

Java: args 数组（main 方法参数）
来源：http://dali.yvedp.cn/Article/details/gt2nnoznlxv.html

Go:   os.Args[1:]
来源：http://dali.0kj1m.cn/Article/details/gt2xpuapvlg.html

Ruby: ARGV
来源：http://dali.yueranfly.top/Article/details/gt2dpbdqzum.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gogol.net.cn/Article/details/gt2iuhqhrug.html

[M02] 读取环境变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yfdxxbqn.html

Py:   os.environ.get("HOME")
来源：http://dali.jianghu66.top/Article/details/gt2yrbzxuqo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gt2micpjtox.html

JS:   process.env.HOME
来源：http://dali.jiagoushi.top/Article/details/gt2klhrwnzx.html

TS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gt2gtapkoav.html

Java: System.getenv("HOME")
来源：http://dali.316326.xyz/Article/details/gt2hxbalwzi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vzsyvonk.html

Ruby: ENV["HOME"]
来源：http://dali.vqdsnc.cn/Article/details/gt2meyjhpzx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj202588.top/Article/details/gt2ktlmplwb.html

[M03] 执行外部命令
来源：http://dali.cashguo.top/Article/details/gt2dcrnlucp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yanxiufei.cn/Article/details/gt2mjgutzys.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gogol.net.cn/Article/details/gt2qherjckr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.snrcjt.cn/Article/details/gt2zhabobsz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.fzhhl.top/Article/details/gt2lmzpltvr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jianghu66.top/Article/details/gt2awxhilnh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj202588.top/Article/details/gt2hhgcwxrz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shzxlz.cn/Article/details/gt2egqggybn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kjltycwe.html

[M04] 获取当前工作目录
来源：http://dali.yj202588.top/Article/details/gt2cujialfi.html

Py:   os.getcwd()
来源：http://dali.gzhubu.top/Article/details/gt2ronsipur.html

PHP:  getcwd();
来源：http://dali.snrcjt.cn/Article/details/gt2gotlylph.html

JS:   process.cwd()
来源：http://dali.jqgufenzy.top/Article/details/gt2aythxrdv.html

TS:   process.cwd()
来源：http://dali.jianghu66.top/Article/details/gt2vmxcgtci.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jqgufenzy.top/Article/details/gt2paybrhmi.html

Go:   os.Getwd()
来源：http://dali.haohaochexian.top/Article/details/gt2thmdwlpr.html

Ruby: Dir.pwd
来源：http://dali.yonumen.top/Article/details/gt2tkleaykv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.vqdsnc.cn/Article/details/gt2nccspyth.html

[M05] 设置退出码
来源：http://dali.wangshuangyany.cn/Article/details/gt2dyccedbw.html

Py:   sys.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2cvidfikb.html

PHP:  exit(1);
来源：http://dali.sweek.top/Article/details/gt2ukosruzo.html

JS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gt2rscyelnn.html

TS:   process.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2xuvlintl.html

Java: System.exit(1)
来源：http://dali.cucudq.cn/Article/details/gt2wsqcutpq.html

Go:   os.Exit(1)
来源：http://dali.hywenlv.cn/Article/details/gt2jvygpojm.html

Ruby: exit 1
来源：http://dali.cashguo.top/Article/details/gt2mapijnjs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenzaomai.com/Article/details/gt2gerxciae.html

[M06] 向标准错误输出
来源：http://dali.ehwqpu.com/Article/details/gt2rvhqsuxs.html

Py:   print("err", file=sys.stderr)
来源：http://dali.snrcjt.cn/Article/details/gt2pmrlbwef.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tianlin.xyz/Article/details/gt2djsenjoc.html

JS:   console.error("err")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ihzkwsed.html

TS:   console.error("err")
来源：http://dali.chenlongwang.top/Article/details/gt2ciclelkn.html

Java: System.err.println("err")
来源：http://dali.andypj.xyz/Article/details/gt2fhjygmlj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenlongwang.top/Article/details/gt2ibkluveq.html

Ruby: warn "err"
来源：http://dali.feifeiyinyue.top/Article/details/gt2denysble.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jyoumei.cn/Article/details/gt2okheeyif.html

[M07] 判断是否为主入口
来源：http://dali.yvedp.cn/Article/details/gt2vbgdsdju.html

Py:   if __name__ == "__main__":
来源：http://dali.fengsongda.top/Article/details/gt2megztxmk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuanzhike.top/Article/details/gt2ybxwlhvi.html

JS:   require.main === module
来源：http://dali.zhengqikj.top/Article/details/gt2mfygaguh.html

TS:   require.main === module
来源：http://dali.ppjwa.cn/Article/details/gt2booeeona.html

Java: public static void main(String[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mcylkxlm.html

Go:   func main()
来源：http://dali.ydzc1.top/Article/details/gt2njnnaefj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.daxiang520.top/Article/details/gt2zzxpbywu.html

C#:   static void Main(string[] args)
来源：http://dali.hywenlv.cn/Article/details/gt2qwtkinhg.html

[M08] 获取系统与运行时信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2crwhlsko.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj20258888.top/Article/details/gt2aerooyei.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.quarkkingdee.top/Article/details/gt2anzlcios.html

JS:   process.platform;  process.version
来源：http://dali.jyoumei.cn/Article/details/gt2nfdezxqx.html

TS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gt2xxtwtjbm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.fzhhl.top/Article/details/gt2vzmcesvj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ixczegko.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.vqdsnc.cn/Article/details/gt2csetrkjj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mynfhvuu.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2ehwxkvnf.html

N. 数据结构与算法
来源：http://dali.cheryme.top/Article/details/gt2flkxbeqe.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2kwevrlrr.html

[N01] 二分查找（有序数组）
来源：http://dali.hnxiangtu.top/Article/details/gt2sbedrmtv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yonumen.top/Article/details/gt2bwkuvimr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nwbrower.top/Article/details/gt2qpehogrz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigufen.top/Article/details/gt2vldodwzd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gt2ybmydggp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gt2lzeqzndt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cucudq.cn/Article/details/gt2fgwzgoze.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gotoacloud.top/Article/details/gt2qrizirmx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tian-w.cn/Article/details/gt2fdbigult.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jyoumei.cn/Article/details/gt2ybwebrcg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hfpthk.cn/Article/details/gt2fvnfadex.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ivvv.top/Article/details/gt2lxaqwkoq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gt2uoflohuz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gt2rlpboyut.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bhybhqie.html

Go:   slices.Sort(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2zaurcyig.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gt2mebcqdwq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhiwuduotai.top/Article/details/gt2uvcaphmg.html

[N03] 快速排序（分治示例）
来源：http://dali.9152youxi.cn/Article/details/gt2ewfleayr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jianghu66.top/Article/details/gt2wohutxqi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jyoumei.cn/Article/details/gt2mvbstczi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yanxiufei.cn/Article/details/gt2bshoajhg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhengqikj.top/Article/details/gt2afdeugez.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xziqi.cn/Article/details/gt2lrjcaeiq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.c1oappe.top/Article/details/gt2kcnunzsz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.snrcjt.cn/Article/details/gt2fimerghc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nanxuanxn.top/Article/details/gt2srepaifi.html

[N04] 斐波那契数列
来源：http://dali.guannengcc.top/Article/details/gt2rbyaydmh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigufen.top/Article/details/gt2zotaeecw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hywenlv.cn/Article/details/gt2swdvsnsx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gt2xtokctlg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gt2vdlxvkey.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gzroohev.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.vqdsnc.cn/Article/details/gt2hetprbnc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gotoacloud.top/Article/details/gt2kkbcycag.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gt2cigrlsjc.html

[N05] 最大公约数
来源：http://dali.316326.xyz/Article/details/gt2oisdcnku.html

Py:   math.gcd(a, b)
来源：http://dali.ydzc1.top/Article/details/gt2ghygowvp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnqzz.top/Article/details/gt2gyncxbwo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.9152youxi.cn/Article/details/gt2znelwerw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hruhtdqb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xuanzx.com/Article/details/gt2gwqjynnt.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jlsjyb.cn/Article/details/gt2nygmxzay.html

Ruby: a.gcd(b)
来源：http://dali.nanxinkj.top/Article/details/gt2dhupyach.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jqgfzy.top/Article/details/gt2mvdcozcm.html

[N06] 判断回文字符串
来源：http://dali.zhengqikj.top/Article/details/gt2ypdtoaes.html

Py:   s == s[::-1]
来源：http://dali.zdqjudy.top/Article/details/gt2izwuiztv.html

PHP:  $s === strrev($s);
来源：http://dali.hywenlv.cn/Article/details/gt2xwzytygk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gt2ewkuakwp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gt2smpetxgn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.redwolf501.top/Article/details/gt2bufhqsju.html

Go:   // 双指针从两端比较
来源：http://dali.yonumen.top/Article/details/gt2nzfhgsyg.html

Ruby: s == s.reverse
来源：http://dali.cashguo.top/Article/details/gt2qryttona.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.c1oappe.top/Article/details/gt2ehbxlglu.html

[N07] 两数之和（返回下标）
来源：http://dali.sysykeji.top/Article/details/gt2plxeunqz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hnxiangtu.top/Article/details/gt2irjnbaqm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.snrcjt.cn/Article/details/gt2wnzcurpd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ehwqpu.com/Article/details/gt2rsshvjdd.html

TS:   // 手写 Map<string, number>
来源：http://dali.jqgufenzy.top/Article/details/gt2gzrwzloy.html

Java: // 手写 HashMap
来源：http://dali.cdnleiting.top/Article/details/gt2mdztbyue.html

Go:   // 手写 map[int]int
来源：http://dali.ybcxt.top/Article/details/gt2rczvwvav.html

Ruby: // 手写 Hash
来源：http://dali.svipenyu.cn/Article/details/gt2ixfskqyj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shangyingyoupin.top/Article/details/gt2bicjjhls.html

[N08] 生成全排列
来源：http://dali.chenlongwang.top/Article/details/gt2tdikcznq.html

Py:   itertools.permutations(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2iwiupynl.html

PHP:  // 手写递归交换
来源：http://dali.tian-w.cn/Article/details/gt2mxkvpimp.html

JS:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gt2dnylerdn.html

TS:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gt2bbzdpgrw.html

Java: // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2wrapjkat.html

Go:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gt2hjumenzd.html

Ruby: arr.permutation.to_a
来源：http://dali.xylfe.cn/Article/details/gt2zpfciyzy.html

C#:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gt2afwwlqch.html

[N09] 栈与队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2mhiomybi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.pycfn.com/Article/details/gt2oernbgat.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tian-w.cn/Article/details/gt2udlwtzjx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gt2ccjrepis.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jianghu66.top/Article/details/gt2pkatqepa.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.smart0.xyz/Article/details/gt2mbkmbcnk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ppjwa.cn/Article/details/gt2ozlsttnu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2swdirzyd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.guannengcc.top/Article/details/gt2cibaowyt.html

[N10] 链表节点定义
来源：http://dali.cashguo.top/Article/details/gt2hqgvgxfg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sufxvd.cn/Article/details/gt2zswyfsjj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zdqjudy.top/Article/details/gt2ykrccuhq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.wangdashe.top/Article/details/gt2lotnnbfl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jqgfzy.top/Article/details/gt2ywprrsfz.html

Java: class Node { int v; Node next; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2tivglldf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.mhx1999.top/Article/details/gt2ebbegugk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.fzhhl.top/Article/details/gt2vdhpwitv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ppjwa.cn/Article/details/gt2icvcpnth.html

[N11] 二叉树中序遍历
来源：http://dali.shuidangran.top/Article/details/gt2barxabse.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jqgufenzy.top/Article/details/gt2zpsxsjzj.html

PHP:  // 手写递归函数
来源：http://dali.snrcjt.cn/Article/details/gt2aglxjsak.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aibaodan.cn/Article/details/gt2ajtjmazg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shuidangran.top/Article/details/gt2wfhtyvcb.html

Java: // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gt2bkeqnyxr.html

Go:   // 手写递归
来源：http://dali.sysykeji.top/Article/details/gt2jiazwnkw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.c1oappe.top/Article/details/gt2zsgngexx.html

C#:   // 手写递归
来源：http://dali.nwbrower.top/Article/details/gt2txukjqba.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cqqwz.cn/Article/details/gt2wcszrcra.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nanxinkj.top/Article/details/gt2gxcpbpyk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.wangdashe.top/Article/details/gt2ktwwgzox.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhiwuduotai.top/Article/details/gt2dujoybtu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.mhx1999.top/Article/details/gt2rxtiiuxm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jiagoushi.top/Article/details/gt2hgmdydsc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cheryme.top/Article/details/gt2cwsjaidh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gt2stshtdvk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hammf.cn/Article/details/gt2vcbwldpk.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2wdufgfgh.html

O. 并发与异步
来源：http://dali.chenzaomai.com/Article/details/gt2nvuzaric.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2zwkvtxod.html

[O01] 启动一个线程
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gabgakga.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zdqjudy.top/Article/details/gt2wtieymid.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2unnpmfzs.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jyoumei.cn/Article/details/gt2qzegwjic.html

TS:   // 同 JS
来源：http://dali.dianchejie.cn/Article/details/gt2fqjlfyze.html

Java: new Thread(() -> f()).start()
来源：http://dali.dashuyun.cn/Article/details/gt2mvxyzlmj.html

Go:   go f()
来源：http://dali.zycfv.cn/Article/details/gt2nqiwkcna.html

Ruby: Thread.new { f }
来源：http://dali.ydzc1.top/Article/details/gt2kqdsdwws.html

C#:   Task.Run(() => F());
来源：http://dali.hywenlv.cn/Article/details/gt2zotechtl.html

[O02] 使用线程池
来源：http://dali.sweek.top/Article/details/gt2avwiszyg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.quarkkingdee.top/Article/details/gt2odqxflxz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hnxiangtu.top/Article/details/gt2zpuhkkrw.html

JS:   // worker_threads 线程池
来源：http://dali.cheryme.top/Article/details/gt2wzioaxrh.html

TS:   // worker_threads 线程池
来源：http://dali.aizwys.cn/Article/details/gt2bjezkrii.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.c1oappe.top/Article/details/gt2xuizeuns.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenjidiqi.icu/Article/details/gt2zuchbjgm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sufxvd.cn/Article/details/gt2oelfmsuf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.0kj1m.cn/Article/details/gt2crffvmqd.html

[O03] 加锁保护共享数据
来源：http://dali.hnxiangtu.top/Article/details/gt2kxnzsosb.html

Py:   with lock: shared += 1
来源：http://dali.hywenlv.cn/Article/details/gt2kbgnvpkj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.vqdsnc.cn/Article/details/gt2ksspyjmw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj20258888.top/Article/details/gt2npjhnlot.html

TS:   // 同 JS
来源：http://dali.aizwys.cn/Article/details/gt2oudrjczu.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vopvkovt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ihmbjcuv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.snrcjt.cn/Article/details/gt2zwysmhkh.html

C#:   lock (gate) { shared++; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2mjgllmno.html

[O04] 定义异步函数并等待
来源：http://dali.yuxming.cn/Article/details/gt2cyltxoqy.html

Py:   async def f():⏎    await g()
来源：http://dali.jinqigufen.top/Article/details/gt2iatcvdti.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jqgufenzy.top/Article/details/gt2lpvmzpru.html

JS:   async function f() { await g(); }
来源：http://dali.zdqjudy.top/Article/details/gt2qysahkdr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cdnleiting.top/Article/details/gt2azvjkopi.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gaohongyu789.top/Article/details/gt2axvqjchq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.dashuyun.cn/Article/details/gt2iifgycpg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ybcxt.top/Article/details/gt2syonodyk.html

C#:   async Task F() { await G(); }
来源：http://dali.sweek.top/Article/details/gt2oqgqxaqz.html

[O05] 并发执行并等待全部完成
来源：http://dali.yongpay.top/Article/details/gt2losuontm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yuxming.cn/Article/details/gt2awpknrjl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.daria6918.cn/Article/details/gt2taprmhab.html

JS:   await Promise.all(tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hnmasduf.html

TS:   await Promise.all(tasks)
来源：http://dali.9152youxi.cn/Article/details/gt2zbkrtdkh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.iojbl.cn/Article/details/gt2oluthixt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj202588.top/Article/details/gt2kifhebpr.html

Ruby: threads.map(&:join)
来源：http://dali.sysykeji.top/Article/details/gt2rjimcntn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.c1oappe.top/Article/details/gt2vqbrmejv.html

[O06] 使用进程池
来源：http://dali.jyoumei.cn/Article/details/gt2ufmvmcku.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.kuanghao11.cn/Article/details/gt2pfhhmdcg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.redwolf501.top/Article/details/gt2rkucgdqh.html

JS:   // child_process / cluster 模块
来源：http://dali.zhongyouzk.top/Article/details/gt2cyjrncjb.html

TS:   // child_process / cluster 模块
来源：http://dali.hfpthk.cn/Article/details/gt2vpezxnvt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jianghu66.top/Article/details/gt2wjevhuuq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.guowangkeji.top/Article/details/gt2mffxlkgg.html

Ruby: // fork 块
来源：http://dali.mhx1999.top/Article/details/gt2qcnsygjv.html

C#:   Parallel.For
来源：http://dali.jlsjyb.cn/Article/details/gt2mwsxjfuz.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2glhdqteg.html

P. 常用工具函数
来源：http://dali.cqqwz.cn/Article/details/gt2egxzxzaz.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2zobbpgpj.html

[P01] 生成 UUID
来源：http://dali.shanyushiyangtech.top/Article/details/gt2acawdqxm.html

Py:   str(uuid.uuid4())
来源：http://dali.gotoacloud.top/Article/details/gt2jzzpoikh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.daria6918.cn/Article/details/gt2kkmgprve.html

JS:   crypto.randomUUID()
来源：http://dali.xziqi.cn/Article/details/gt2fmeexhyj.html

TS:   crypto.randomUUID()
来源：http://dali.yueranfly.top/Article/details/gt2eyyfvvsd.html

Java: UUID.randomUUID().toString()
来源：http://dali.snrcjt.cn/Article/details/gt2rdxeosxo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gmevhwre.html

Ruby: SecureRandom.uuid
来源：http://dali.ivvv.top/Article/details/gt2rekuiuxf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yonumen.top/Article/details/gt2biyqfdke.html

[P02] MD5 / SHA256 摘要
来源：http://dali.daxiang520.top/Article/details/gt2uiojwiey.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sxryk.cn/Article/details/gt2axlmomhb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cdnleiting.top/Article/details/gt2uyavyfmr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.daxiang520.top/Article/details/gt2bleixpfo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xuanzx.com/Article/details/gt2ifntzbey.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.aizwys.cn/Article/details/gt2qriftjsn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.andypj.xyz/Article/details/gt2rzfibals.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ppjwa.cn/Article/details/gt2vfpftojx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.bjfxy.top/Article/details/gt2zuqsnksi.html

[P03] 生成短随机字符串
来源：http://dali.jqgfzy.top/Article/details/gt2dekdruix.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhiwuduotai.top/Article/details/gt2yisvzrce.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.guowangkeji.top/Article/details/gt2ypowocoj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.316326.xyz/Article/details/gt2zetxrdxm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shzxlz.cn/Article/details/gt2xaumwlxs.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yonumen.top/Article/details/gt2ssgvkdtx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.iojbl.cn/Article/details/gt2ntsxutri.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenlongwang.top/Article/details/gt2cissbczw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.havefunace.top/Article/details/gt2uglrvgoz.html

[P04] 求长度
来源：http://dali.nanxuanxn.top/Article/details/gt2cafshzkn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuxming.cn/Article/details/gt2hueshjtt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gt2scvybrdg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gt2wgkischy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.meibo888.top/Article/details/gt2xyhtumyh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nqsgjryx.html

Go:   len(arr);  len(m)
来源：http://dali.hysaishi.cn/Article/details/gt2kluwnqey.html

Ruby: x.length;  x.size
来源：http://dali.ehwqpu.com/Article/details/gt2wtjdzmrd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shuidangran.top/Article/details/gt2zxowqyrt.html


<!-- 参考信息 -->