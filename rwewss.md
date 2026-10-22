代发 wailian999

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2arshroem.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yuxming.cn/Article/details/gt2yxyqbtbi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxuanxn.top/Article/details/gt2ckanhpbd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.dianchejie.cn/Article/details/gt2ljhmlycr.html

[L07] 处理 HTTP 状态码
来源：http://dali.jlsjyb.cn/Article/details/gt2spkkkusd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yuanzhike.top/Article/details/gt2zaetaldv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jiagoushi.top/Article/details/gt2gbyqlcen.html

JS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gt2spqbczth.html

TS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gt2rbumjwig.html

Java: resp.statusCode()
来源：http://dali.xuetiantiany.cn/Article/details/gt2sghzvdae.html

Go:   resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gt2bjkhxiio.html

Ruby: resp.code.to_i
来源：http://dali.yj20258888.top/Article/details/gt2mijescrt.html

C#:   (int)resp.StatusCode
来源：http://dali.yj20258.top/Article/details/gt2uqacimts.html

[L08] 并发请求多个地址
来源：http://dali.yuanzhike.top/Article/details/gt2kcghocnf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhongyouzk.top/Article/details/gt2eqrylhvb.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj20258.top/Article/details/gt2jadqqudo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fehalekc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gt2zqkkhisk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fzhhl.top/Article/details/gt2ukdejice.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.birdmap.top/Article/details/gt2gdqnnzzl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.meibo888.top/Article/details/gt2pqzegkit.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cdnleiting.top/Article/details/gt2vtogzenl.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2kcrjpwam.html

M. 命令行 / 进程 / 环境
来源：http://dali.hammf.cn/Article/details/gt2sziovqlq.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2yiyqfklb.html

[M01] 读取命令行参数
来源：http://dali.tianlin.xyz/Article/details/gt2dendhaqd.html

Py:   sys.argv[1:]
来源：http://dali.smart0.xyz/Article/details/gt2dtzzhpdj.html

PHP:  $argv;  $argc;
来源：http://dali.chenzaomai.com/Article/details/gt2bbltuivk.html

JS:   process.argv.slice(2)
来源：http://dali.sufxvd.cn/Article/details/gt2qszglirb.html

TS:   process.argv.slice(2)
来源：http://dali.cqqwz.cn/Article/details/gt2ajidtnup.html

Java: args 数组（main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gt2hmzagqag.html

Go:   os.Args[1:]
来源：http://dali.hnqzz.top/Article/details/gt2tjpdidtg.html

Ruby: ARGV
来源：http://dali.sxryk.cn/Article/details/gt2zdzacqkj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yonumen.top/Article/details/gt2cshksyjk.html

[M02] 读取环境变量
来源：http://dali.guowangkeji.top/Article/details/gt2bwjfxpue.html

Py:   os.environ.get("HOME")
来源：http://dali.gotoacloud.top/Article/details/gt2euxibqgz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gt2pgcufjlo.html

JS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cqorvzcp.html

TS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gt2cbyhhaxf.html

Java: System.getenv("HOME")
来源：http://dali.snrcjt.cn/Article/details/gt2qbylnbuj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gt2ijtnebrj.html

Ruby: ENV["HOME"]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gycuijbu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gt2dxdwqmpc.html

[M03] 执行外部命令
来源：http://dali.hnqzz.top/Article/details/gt2fodlcswx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yuxming.cn/Article/details/gt2uobgrijm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cashguo.top/Article/details/gt2rnjteczm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnqzz.top/Article/details/gt2zjfrecab.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.havefunace.top/Article/details/gt2orpioyga.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhongyouzk.top/Article/details/gt2wfhuafid.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj20258.top/Article/details/gt2jdgrfdia.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangshuangyany.cn/Article/details/gt2jqkbctxw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cdnleiting.top/Article/details/gt2lmtappry.html

[M04] 获取当前工作目录
来源：http://dali.316326.xyz/Article/details/gt2kszfybjn.html

Py:   os.getcwd()
来源：http://dali.dianchejie.cn/Article/details/gt2zvinyyfn.html

PHP:  getcwd();
来源：http://dali.yuanzhike.top/Article/details/gt2xpwprwdf.html

JS:   process.cwd()
来源：http://dali.birdmap.top/Article/details/gt2mhynfjtw.html

TS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gt2uprjniwe.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenlongwang.top/Article/details/gt2ckuckdre.html

Go:   os.Getwd()
来源：http://dali.yanxiufei.cn/Article/details/gt2xawxnazq.html

Ruby: Dir.pwd
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fspcrpdb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yuxming.cn/Article/details/gt2zomfaumt.html

[M05] 设置退出码
来源：http://dali.yj20258.top/Article/details/gt2idygnvcw.html

Py:   sys.exit(1)
来源：http://dali.pycfn.com/Article/details/gt2cqrpohzh.html

PHP:  exit(1);
来源：http://dali.hysaishi.cn/Article/details/gt2noxvntsr.html

JS:   process.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cnbmhbsn.html

TS:   process.exit(1)
来源：http://dali.daria6918.cn/Article/details/gt2rxdsumew.html

Java: System.exit(1)
来源：http://dali.tanke756.top/Article/details/gt2qnbjjksq.html

Go:   os.Exit(1)
来源：http://dali.sxryk.cn/Article/details/gt2utubqssx.html

Ruby: exit 1
来源：http://dali.0kj1m.cn/Article/details/gt2umljybxe.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sweek.top/Article/details/gt2cfomfshe.html

[M06] 向标准错误输出
来源：http://dali.zhongyouzk.top/Article/details/gt2smtzsizv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sufxvd.cn/Article/details/gt2otoopnez.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.birdmap.top/Article/details/gt2zacckcdl.html

JS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gt2qqottbmo.html

TS:   console.error("err")
来源：http://dali.havefunace.top/Article/details/gt2filumiyj.html

Java: System.err.println("err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2mkqiurcb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ivvv.top/Article/details/gt2lgdzbyyn.html

Ruby: warn "err"
来源：http://dali.kuanghao11.cn/Article/details/gt2inoqavjh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xziqi.cn/Article/details/gt2liwuqthe.html

[M07] 判断是否为主入口
来源：http://dali.hywenlv.cn/Article/details/gt2nqonviqq.html

Py:   if __name__ == "__main__":
来源：http://dali.daria6918.cn/Article/details/gt2rdblbbzf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj20258888.top/Article/details/gt2qqxnhmmz.html

JS:   require.main === module
来源：http://dali.yueranfly.top/Article/details/gt2kgvzhxuz.html

TS:   require.main === module
来源：http://dali.cashguo.top/Article/details/gt2gqirzlps.html

Java: public static void main(String[] args)
来源：http://dali.chenlongwang.top/Article/details/gt2mpidortt.html

Go:   func main()
来源：http://dali.yj202588.top/Article/details/gt2uwqsjdcl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.mhx1999.top/Article/details/gt2wwbaadtl.html

C#:   static void Main(string[] args)
来源：http://dali.guowangkeji.top/Article/details/gt2xevdooxh.html

[M08] 获取系统与运行时信息
来源：http://dali.jlsjyb.cn/Article/details/gt2pajqeknx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.aibaodan.cn/Article/details/gt2pelxfwxa.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj202588.top/Article/details/gt2oftomekx.html

JS:   process.platform;  process.version
来源：http://dali.hongshengwenyu.top/Article/details/gt2azjyjdsc.html

TS:   process.platform;  process.version
来源：http://dali.jqgufenzy.top/Article/details/gt2whfwwyhi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnxiangtu.top/Article/details/gt2rdnkhtye.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgfzy.top/Article/details/gt2xmgeytiv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.feifeiyinyue.top/Article/details/gt2ohlfwrzm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.pycfn.com/Article/details/gt2ztqqfnvz.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2ctyoodnc.html

N. 数据结构与算法
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ngybfebd.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2cqthjfsv.html

[N01] 二分查找（有序数组）
来源：http://dali.sysykeji.top/Article/details/gt2lflzitfc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.pycfn.com/Article/details/gt2grrfdlco.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yangfankeji.com/Article/details/gt2vugegnyl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cipjdzlz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yvedp.cn/Article/details/gt2itklcjme.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gt2hsjviaor.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sxryk.cn/Article/details/gt2gtagrego.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.aizwys.cn/Article/details/gt2ilglipor.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.c1oappe.top/Article/details/gt2yzasabug.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.birdmap.top/Article/details/gt2hoeadyfl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hongshengwenyu.top/Article/details/gt2gzjvzluo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ipicfwwc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.havefunace.top/Article/details/gt2jgcelgtf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gt2omcrgvur.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.andypj.xyz/Article/details/gt2thylvygh.html

Go:   slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ycjfmezl.html

Ruby: arr.sort
来源：http://dali.zhoulong.xyz/Article/details/gt2yobzgbtl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sufxvd.cn/Article/details/gt2edgehywu.html

[N03] 快速排序（分治示例）
来源：http://dali.aibaodan.cn/Article/details/gt2zjfbsnnn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fengsongda.top/Article/details/gt2swkxxtdw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenlongwang.top/Article/details/gt2hmdzedfk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.0kj1m.cn/Article/details/gt2gzudherq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.svipenyu.cn/Article/details/gt2ubaxunqz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.daria6918.cn/Article/details/gt2ydmphxit.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hnxiangtu.top/Article/details/gt2whxxqvhp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhixingplan.top/Article/details/gt2jvrvdkua.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhoulong.xyz/Article/details/gt2arnbxdnp.html

[N04] 斐波那契数列
来源：http://dali.xinyue.icu/Article/details/gt2ljnoylki.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sufxvd.cn/Article/details/gt2lkwfipgf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.fzhhl.top/Article/details/gt2zcioufgw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gt2vlziykjs.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2zkqfetao.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yvklplzw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.snrcjt.cn/Article/details/gt2nljkukzb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jyoumei.cn/Article/details/gt2znuyyfzz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gt2rrknzjej.html

[N05] 最大公约数
来源：http://dali.xinyue.icu/Article/details/gt2xhzrhigb.html

Py:   math.gcd(a, b)
来源：http://dali.sufxvd.cn/Article/details/gt2ysknbnhl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awmmwwoi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.0kj1m.cn/Article/details/gt2ipspfwly.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuxming.cn/Article/details/gt2ihntcgnb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.iojbl.cn/Article/details/gt2xltejfjx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.c1oappe.top/Article/details/gt2bixmjzkt.html

Ruby: a.gcd(b)
来源：http://dali.nwbrower.top/Article/details/gt2ntljervz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.mhx1999.top/Article/details/gt2qeacpuuu.html

[N06] 判断回文字符串
来源：http://dali.cashguo.top/Article/details/gt2elghksud.html

Py:   s == s[::-1]
来源：http://dali.zdqjudy.top/Article/details/gt2unkpbaet.html

PHP:  $s === strrev($s);
来源：http://dali.sysykeji.top/Article/details/gt2bgreeiqj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gt2mkvrdnmk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gt2rgipnryc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.feifeiyinyue.top/Article/details/gt2ufwohaeg.html

Go:   // 双指针从两端比较
来源：http://dali.dashuyun.cn/Article/details/gt2xnuvsord.html

Ruby: s == s.reverse
来源：http://dali.tanke756.top/Article/details/gt2imqxnjej.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.meibo888.top/Article/details/gt2zjgdvbmm.html

[N07] 两数之和（返回下标）
来源：http://dali.nanxuanxn.top/Article/details/gt2lqkxbvvv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yangfankeji.com/Article/details/gt2dsdnomty.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gotoacloud.top/Article/details/gt2imejnbom.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.birdmap.top/Article/details/gt2ijsffhjp.html

TS:   // 手写 Map<string, number>
来源：http://dali.zdqjudy.top/Article/details/gt2dbbazlbe.html

Java: // 手写 HashMap
来源：http://dali.smart0.xyz/Article/details/gt2kbhgsjlk.html

Go:   // 手写 map[int]int
来源：http://dali.zhoulong.xyz/Article/details/gt2xcfylgxl.html

Ruby: // 手写 Hash
来源：http://dali.hfpthk.cn/Article/details/gt2telnvsng.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.316326.xyz/Article/details/gt2ppycezyz.html

[N08] 生成全排列
来源：http://dali.birdmap.top/Article/details/gt2hpxcwwjm.html

Py:   itertools.permutations(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2rzmsagjf.html

PHP:  // 手写递归交换
来源：http://dali.kuanghao11.cn/Article/details/gt2herphiny.html

JS:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gt2kzmbzhtz.html

TS:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gt2bhwtmjdg.html

Java: // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2azwxrvtk.html

Go:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gt2oyuqhitm.html

Ruby: arr.permutation.to_a
来源：http://dali.yanxiufei.cn/Article/details/gt2kdqnlhpc.html

C#:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gt2oebjgahi.html

[N09] 栈与队列
来源：http://dali.dianchejie.cn/Article/details/gt2rvdkynbl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.kuanghao11.cn/Article/details/gt2ktnzgvil.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gt2itxcpcut.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2ksiywzkb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.mhx1999.top/Article/details/gt2gequmywc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yueranfly.top/Article/details/gt2eittwkfe.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.fengsongda.top/Article/details/gt2xsbxehdd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gt2qfbdukyr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sufxvd.cn/Article/details/gt2uhovglpy.html

[N10] 链表节点定义
来源：http://dali.cqqwz.cn/Article/details/gt2swqbvglj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hongshengwenyu.top/Article/details/gt2hvacmpxy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ffwnbxfn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jiagoushi.top/Article/details/gt2sbobmyww.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xftpnplf.html

Java: class Node { int v; Node next; }
来源：http://dali.guannengcc.top/Article/details/gt2qteeqtzt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jqgufenzy.top/Article/details/gt2fceqfane.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yangfankeji.com/Article/details/gt2flkukbzg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mkqbucxo.html

[N11] 二叉树中序遍历
来源：http://dali.zhoulong.xyz/Article/details/gt2lwfavgtx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.kuanghao11.cn/Article/details/gt2htugswef.html

PHP:  // 手写递归函数
来源：http://dali.dashuyun.cn/Article/details/gt2hspbgpnd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.smart0.xyz/Article/details/gt2zuwsatzr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ooevuhrs.html

Java: // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gt2wjjrqyzi.html

Go:   // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2xoszpwhx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.aizwys.cn/Article/details/gt2lciyjqkt.html

C#:   // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gt2vxzdxmur.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.haohaochexian.top/Article/details/gt2fjngapbp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ivvv.top/Article/details/gt2axejvsoe.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shangyingyoupin.top/Article/details/gt2mayjayka.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.birdmap.top/Article/details/gt2efugkhvv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hywenlv.cn/Article/details/gt2dcpyjlof.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shangyingyoupin.top/Article/details/gt2utoysjgw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinqigfzy.top/Article/details/gt2yoptipmb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.haohaochexian.top/Article/details/gt2jhsbiuyr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hammf.cn/Article/details/gt2ozbpxvfz.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2djkpgdxi.html

O. 并发与异步
来源：http://dali.daria6918.cn/Article/details/gt2mpltssiu.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pyhejspv.html

[O01] 启动一个线程
来源：http://dali.wangdashe.top/Article/details/gt2ireovgeh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yj20258.top/Article/details/gt2mtlawfep.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.bjfxy.top/Article/details/gt2vjklisie.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.c1oappe.top/Article/details/gt2kmwmcnle.html

TS:   // 同 JS
来源：http://dali.yonumen.top/Article/details/gt2smxnccnr.html

Java: new Thread(() -> f()).start()
来源：http://dali.jqgfzy.top/Article/details/gt2wgxtrovc.html

Go:   go f()
来源：http://dali.jlsjyb.cn/Article/details/gt2hxyuipif.html

Ruby: Thread.new { f }
来源：http://dali.jinqigfzy.top/Article/details/gt2xugrscyx.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258.top/Article/details/gt2fktqfexl.html

[O02] 使用线程池
来源：http://dali.cdnleiting.top/Article/details/gt2xafupaeq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hnxiangtu.top/Article/details/gt2jtkjictv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ppjwa.cn/Article/details/gt2oybmlxvc.html

JS:   // worker_threads 线程池
来源：http://dali.guannengcc.top/Article/details/gt2rjrmpecj.html

TS:   // worker_threads 线程池
来源：http://dali.ehwqpu.com/Article/details/gt2kruqjgzl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.dianchejie.cn/Article/details/gt2ukgnhnle.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.tianlin.xyz/Article/details/gt2vpqmueea.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.andypj.xyz/Article/details/gt2lwtclckn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xinyue.icu/Article/details/gt2wujqzfpb.html

[O03] 加锁保护共享数据
来源：http://dali.chenjidiqi.icu/Article/details/gt2wsjgasfc.html

Py:   with lock: shared += 1
来源：http://dali.birdmap.top/Article/details/gt2frthddpa.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.9152youxi.cn/Article/details/gt2auiiqain.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj202588.top/Article/details/gt2ngvmfiol.html

TS:   // 同 JS
来源：http://dali.hongshengwenyu.top/Article/details/gt2fqviszzm.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhoulong.xyz/Article/details/gt2cxhvbnie.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hfpthk.cn/Article/details/gt2suacwrji.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nanxinkj.top/Article/details/gt2wfbmvruy.html

C#:   lock (gate) { shared++; }
来源：http://dali.jiagoushi.top/Article/details/gt2rmmhmfdy.html

[O04] 定义异步函数并等待
来源：http://dali.jyoumei.cn/Article/details/gt2jaatlwhm.html

Py:   async def f():⏎    await g()
来源：http://dali.yonumen.top/Article/details/gt2wsulyefp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yangfankeji.com/Article/details/gt2mbsbomtt.html

JS:   async function f() { await g(); }
来源：http://dali.tianlin.xyz/Article/details/gt2nbzxlmjz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.c1oappe.top/Article/details/gt2efivtgrs.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sweek.top/Article/details/gt2ttfjiwqo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.daxiang520.top/Article/details/gt2vesypron.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.bjfxy.top/Article/details/gt2zppgcuzu.html

C#:   async Task F() { await G(); }
来源：http://dali.yonumen.top/Article/details/gt2xbdugmuf.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aiaefkqg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sweek.top/Article/details/gt2nliguvnx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yuxming.cn/Article/details/gt2jnporinv.html

JS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gt2gupforok.html

TS:   await Promise.all(tasks)
来源：http://dali.nanxuanxn.top/Article/details/gt2ilpargts.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cashguo.top/Article/details/gt2ppjyualu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.chenzaomai.com/Article/details/gt2itptavlj.html

Ruby: threads.map(&:join)
来源：http://dali.shzxlz.cn/Article/details/gt2wrlcrjgr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hvliltra.html

[O06] 使用进程池
来源：http://dali.smart0.xyz/Article/details/gt2ltcytlke.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tianlin.xyz/Article/details/gt2kmyqgbdb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhengqikj.top/Article/details/gt2cuizific.html

JS:   // child_process / cluster 模块
来源：http://dali.cucudq.cn/Article/details/gt2ksjjruci.html

TS:   // child_process / cluster 模块
来源：http://dali.pycfn.com/Article/details/gt2nbpbcecs.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ivvv.top/Article/details/gt2srkigroc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qgijucxq.html

Ruby: // fork 块
来源：http://dali.yonumen.top/Article/details/gt2hfctkaku.html

C#:   Parallel.For
来源：http://dali.havefunace.top/Article/details/gt2ccyphzdq.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2yqffsgkh.html

P. 常用工具函数
来源：http://dali.c1oappe.top/Article/details/gt2mmgmhdwu.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2owloqncd.html

[P01] 生成 UUID
来源：http://dali.daxiang520.top/Article/details/gt2gwomwfrb.html

Py:   str(uuid.uuid4())
来源：http://dali.hnxiangtu.top/Article/details/gt2lgirlrro.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gotoacloud.top/Article/details/gt2dgzhgozs.html

JS:   crypto.randomUUID()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wzmtmgjx.html

TS:   crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gt2ikxepopk.html

Java: UUID.randomUUID().toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2votbzaim.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nanxinkj.top/Article/details/gt2haeaaflq.html

Ruby: SecureRandom.uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tlckrucc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jyoumei.cn/Article/details/gt2hjryswzd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yvedp.cn/Article/details/gt2kptromyh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.9152youxi.cn/Article/details/gt2dpatrvsr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2tvuznfjr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhixingplan.top/Article/details/gt2tlavhodm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yvedp.cn/Article/details/gt2cgoqdtdn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cashguo.top/Article/details/gt2adveuzqe.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shangyingyoupin.top/Article/details/gt2bunopqsw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ftjsfszh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.svipenyu.cn/Article/details/gt2arcvyhxa.html

[P03] 生成短随机字符串
来源：http://dali.birdmap.top/Article/details/gt2rkmhcwbo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.havefunace.top/Article/details/gt2zbksiwdj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yongpay.top/Article/details/gt2wrlgxrxm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qhgzoyit.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zycfv.cn/Article/details/gt2iwtwbiex.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.snrcjt.cn/Article/details/gt2jywwsxcz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jiagoushi.top/Article/details/gt2gpgfnzqq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.9152youxi.cn/Article/details/gt2glhrmfgo.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zdqjudy.top/Article/details/gt2htgcuusn.html

[P04] 求长度
来源：http://dali.yueranfly.top/Article/details/gt2hnanluqc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yangfankeji.com/Article/details/gt2vewpsnea.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gt2jhxezknr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yanxiufei.cn/Article/details/gt2gubdgrif.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zxacczfb.html


<!-- 参考信息 -->