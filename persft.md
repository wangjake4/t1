代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.sxryk.cn/Article/details/gt2zzhkvhoe.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jqgfzy.top/Article/details/gt2jkidkdyd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.haohaochexian.top/Article/details/gt2bddhfrws.html

JS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gt2njtzsxbd.html

TS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gt2uswuarev.html

Java: resp.statusCode()
来源：http://dali.redwolf501.top/Article/details/gt2vfqwhimv.html

Go:   resp.StatusCode
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aogyqqgl.html

Ruby: resp.code.to_i
来源：http://dali.zhoulong.xyz/Article/details/gt2dqrnwafv.html

C#:   (int)resp.StatusCode
来源：http://dali.quarkkingdee.top/Article/details/gt2gtdtjjts.html

[L08] 并发请求多个地址
来源：http://dali.vqdsnc.cn/Article/details/gt2olfcfmug.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj202588.top/Article/details/gt2tvxvzmkj.html

PHP:  curl_multi_init() 系列
来源：http://dali.birdmap.top/Article/details/gt2kjmbyvig.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gt2qmltlffm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zycfv.cn/Article/details/gt2fnkkeywn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.andypj.xyz/Article/details/gt2mmhfmqhi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jlsjyb.cn/Article/details/gt2hjixlswr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ybcxt.top/Article/details/gt2naipqqes.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yvedp.cn/Article/details/gt2aqohjewv.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2uswchtjd.html

M. 命令行 / 进程 / 环境
来源：http://dali.meibo888.top/Article/details/gt2gxayssgy.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2ybpcciqp.html

[M01] 读取命令行参数
来源：http://dali.cheryme.top/Article/details/gt2npejqack.html

Py:   sys.argv[1:]
来源：http://dali.0kj1m.cn/Article/details/gt2szuxamct.html

PHP:  $argv;  $argc;
来源：http://dali.shzxlz.cn/Article/details/gt2ofydqrgb.html

JS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gt2boflngmj.html

TS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2luvwjxjc.html

Java: args 数组（main 方法参数）
来源：http://dali.nanxuanxn.top/Article/details/gt2dveeefbw.html

Go:   os.Args[1:]
来源：http://dali.vqdsnc.cn/Article/details/gt2uinhxjjf.html

Ruby: ARGV
来源：http://dali.jqgufenzy.top/Article/details/gt2okrgirww.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gt2izgjpkqk.html

[M02] 读取环境变量
来源：http://dali.gaohongyu789.top/Article/details/gt2opylzilz.html

Py:   os.environ.get("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hamxdhxf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gt2giudwlls.html

JS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gt2emaftobm.html

TS:   process.env.HOME
来源：http://dali.cheryme.top/Article/details/gt2hurcytki.html

Java: System.getenv("HOME")
来源：http://dali.aizwys.cn/Article/details/gt2qihyryyz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ivvv.top/Article/details/gt2mwlpbnlh.html

Ruby: ENV["HOME"]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nkgfgsho.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ehwqpu.com/Article/details/gt2tgqiyvds.html

[M03] 执行外部命令
来源：http://dali.zdqjudy.top/Article/details/gt2tecgdfwv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nanxuanxn.top/Article/details/gt2fakqyiqn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.0kj1m.cn/Article/details/gt2dlllmtmx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xinyue.icu/Article/details/gt2wmwqsqbr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sweek.top/Article/details/gt2aviycpoy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yanxiufei.cn/Article/details/gt2iriebcwx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gotoacloud.top/Article/details/gt2gnhzxvvv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sysykeji.top/Article/details/gt2xaguzeyx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sysykeji.top/Article/details/gt2lxozpqzw.html

[M04] 获取当前工作目录
来源：http://dali.yongpay.top/Article/details/gt2flngqevo.html

Py:   os.getcwd()
来源：http://dali.xylfe.cn/Article/details/gt2agketsrm.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2podqiwuj.html

JS:   process.cwd()
来源：http://dali.ivvv.top/Article/details/gt2ecvgrvry.html

TS:   process.cwd()
来源：http://dali.svipenyu.cn/Article/details/gt2kaaakvev.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ybcxt.top/Article/details/gt2ttidmuiy.html

Go:   os.Getwd()
来源：http://dali.tian-w.cn/Article/details/gt2pyqlqdww.html

Ruby: Dir.pwd
来源：http://dali.xylfe.cn/Article/details/gt2qhtipnoc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.birdmap.top/Article/details/gt2dgfgbutm.html

[M05] 设置退出码
来源：http://dali.havefunace.top/Article/details/gt2csibbiod.html

Py:   sys.exit(1)
来源：http://dali.yj20258.top/Article/details/gt2iolvmpvm.html

PHP:  exit(1);
来源：http://dali.yj20258888.top/Article/details/gt2mmdoiwux.html

JS:   process.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gt2hwdauktj.html

TS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gt2aaikjpsw.html

Java: System.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2aqjjhume.html

Go:   os.Exit(1)
来源：http://dali.zhixingplan.top/Article/details/gt2krlvvtmu.html

Ruby: exit 1
来源：http://dali.zhongyouzk.top/Article/details/gt2sttxwrxs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhongyouzk.top/Article/details/gt2tcfgiira.html

[M06] 向标准错误输出
来源：http://dali.hnxiangtu.top/Article/details/gt2zhuabhay.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ydzc1.top/Article/details/gt2nceixwsu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jlsjyb.cn/Article/details/gt2owccklkj.html

JS:   console.error("err")
来源：http://dali.jqgfzy.top/Article/details/gt2qxrxfvwj.html

TS:   console.error("err")
来源：http://dali.cheryme.top/Article/details/gt2rpnbtfnj.html

Java: System.err.println("err")
来源：http://dali.ybcxt.top/Article/details/gt2xpfnqelz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnxiangtu.top/Article/details/gt2igtumcei.html

Ruby: warn "err"
来源：http://dali.yuxming.cn/Article/details/gt2wtbvjqyr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cheryme.top/Article/details/gt2kkqiishe.html

[M07] 判断是否为主入口
来源：http://dali.pengpengdd.cyou/Article/details/gt2trxyqcfq.html

Py:   if __name__ == "__main__":
来源：http://dali.jlsjyb.cn/Article/details/gt2lpifmodr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.havefunace.top/Article/details/gt2ggavitqf.html

JS:   require.main === module
来源：http://dali.0kj1m.cn/Article/details/gt2rchvqlhz.html

TS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gt2ixpctstf.html

Java: public static void main(String[] args)
来源：http://dali.yuanzhike.top/Article/details/gt2huzozses.html

Go:   func main()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rifzffae.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hnxiangtu.top/Article/details/gt2fhnlrmyz.html

C#:   static void Main(string[] args)
来源：http://dali.gotoacloud.top/Article/details/gt2ehvvfjpq.html

[M08] 获取系统与运行时信息
来源：http://dali.jlsjyb.cn/Article/details/gt2cczwqnaj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kijihncw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hongshengwenyu.top/Article/details/gt2poyjorhk.html

JS:   process.platform;  process.version
来源：http://dali.tian-w.cn/Article/details/gt2azqewqmf.html

TS:   process.platform;  process.version
来源：http://dali.iojbl.cn/Article/details/gt2hfsyefig.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sweek.top/Article/details/gt2kghqhjbs.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.wangshuangyany.cn/Article/details/gt2tvxcowtu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hfpthk.cn/Article/details/gt2azhkmmbs.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhengqikj.top/Article/details/gt2ueotvzdf.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2lhtdbkep.html

N. 数据结构与算法
来源：http://dali.meibo888.top/Article/details/gt2rguqmpud.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2dyhfqvgu.html

[N01] 二分查找（有序数组）
来源：http://dali.hammf.cn/Article/details/gt2xrvqgpok.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gt2isgaxqkt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tian-w.cn/Article/details/gt2drhdelen.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xinyue.icu/Article/details/gt2ezvkmzlt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gogol.net.cn/Article/details/gt2ftdenyod.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2shgejahf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.fengsongda.top/Article/details/gt2zvmeyxcy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.smart0.xyz/Article/details/gt2vlcnqnsl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gt2yqorujhk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jiagoushi.top/Article/details/gt2mbyrgmbc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxuanxn.top/Article/details/gt2msgpwrpf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.daxiang520.top/Article/details/gt2kbfkagfp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gt2hoxvrkgx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gt2cntllihi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gaohongyu789.top/Article/details/gt2fvmhdkgq.html

Go:   slices.Sort(arr)
来源：http://dali.smart0.xyz/Article/details/gt2jwsswnkw.html

Ruby: arr.sort
来源：http://dali.snrcjt.cn/Article/details/gt2hcqpvqnd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yuxming.cn/Article/details/gt2vwtpdice.html

[N03] 快速排序（分治示例）
来源：http://dali.guannengcc.top/Article/details/gt2qvodqiha.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ydzc1.top/Article/details/gt2hjzbaugg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.pengpengdd.cyou/Article/details/gt2lyegtjjf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258888.top/Article/details/gt2rwfvghiu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258888.top/Article/details/gt2leksjgzl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.chenzaomai.com/Article/details/gt2mkyretaw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jyoumei.cn/Article/details/gt2ryzxatgw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jqgufenzy.top/Article/details/gt2fuuhvazc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jqgufenzy.top/Article/details/gt2nmonjhpu.html

[N04] 斐波那契数列
来源：http://dali.svipenyu.cn/Article/details/gt2utdenmzx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2fnuwdhxt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2gsuqaoau.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gt2mlgmylnc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gt2rjyyrruq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hywenlv.cn/Article/details/gt2oqpqogba.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.fengsongda.top/Article/details/gt2slsssydy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cheryme.top/Article/details/gt2wyvbcliv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gt2xcbyxakp.html

[N05] 最大公约数
来源：http://dali.mhx1999.top/Article/details/gt2igkhhmwf.html

Py:   math.gcd(a, b)
来源：http://dali.wangdashe.top/Article/details/gt2amtqjhsz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ybgyapap.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yongpay.top/Article/details/gt2zeplvrso.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ojnitqzd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hfpthk.cn/Article/details/gt2idcmyyuy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ppjwa.cn/Article/details/gt2zmxbkpnr.html

Ruby: a.gcd(b)
来源：http://dali.yanxiufei.cn/Article/details/gt2fhwchkqw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fwpiveqm.html

[N06] 判断回文字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2ubxtsmyj.html

Py:   s == s[::-1]
来源：http://dali.snrcjt.cn/Article/details/gt2igdciuit.html

PHP:  $s === strrev($s);
来源：http://dali.316326.xyz/Article/details/gt2xsuqdolr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ixdtnlll.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gt2hyvujhby.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.quarkkingdee.top/Article/details/gt2xseznowu.html

Go:   // 双指针从两端比较
来源：http://dali.c1oappe.top/Article/details/gt2qteqvwtl.html

Ruby: s == s.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bdxurred.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xziqi.cn/Article/details/gt2pdnwwgnr.html

[N07] 两数之和（返回下标）
来源：http://dali.hywenlv.cn/Article/details/gt2bfwpdxxg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj20258888.top/Article/details/gt2ymuhnawk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ppjwa.cn/Article/details/gt2rlpuomxh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.andypj.xyz/Article/details/gt2tmodbpev.html

TS:   // 手写 Map<string, number>
来源：http://dali.hfpthk.cn/Article/details/gt2wxipusmq.html

Java: // 手写 HashMap
来源：http://dali.zhongyouzk.top/Article/details/gt2rzfiepsr.html

Go:   // 手写 map[int]int
来源：http://dali.xuanzx.com/Article/details/gt2dpwefwzl.html

Ruby: // 手写 Hash
来源：http://dali.xinyue.icu/Article/details/gt2xlvpvrig.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.pengpengdd.cyou/Article/details/gt2yixwocbj.html

[N08] 生成全排列
来源：http://dali.chenjidiqi.icu/Article/details/gt2alybdfpc.html

Py:   itertools.permutations(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2nhaxknbh.html

PHP:  // 手写递归交换
来源：http://dali.nanxuanxn.top/Article/details/gt2jazqcgxc.html

JS:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gt2wzodfunh.html

TS:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gt2ygxzbhly.html

Java: // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2wcgemzrg.html

Go:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2xwidkecf.html

Ruby: arr.permutation.to_a
来源：http://dali.dianchejie.cn/Article/details/gt2flxgzakt.html

C#:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gt2axzqbslu.html

[N09] 栈与队列
来源：http://dali.hywenlv.cn/Article/details/gt2swjpdpae.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zdqjudy.top/Article/details/gt2rzpvnpyg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.daria6918.cn/Article/details/gt2lkxcfzpy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gt2nfskapeg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hongshengwenyu.top/Article/details/gt2kcaaizue.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sysykeji.top/Article/details/gt2vgvlvopp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.andypj.xyz/Article/details/gt2kbinmkib.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.aizwys.cn/Article/details/gt2bsmswkrz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hywenlv.cn/Article/details/gt2scjtaktw.html

[N10] 链表节点定义
来源：http://dali.pengpengdd.cyou/Article/details/gt2dfwbjerf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ppjwa.cn/Article/details/gt2tifdjgmt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.havefunace.top/Article/details/gt2ubzzpzwk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yuanzhike.top/Article/details/gt2vkweofol.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhixingplan.top/Article/details/gt2kdwbkhcr.html

Java: class Node { int v; Node next; }
来源：http://dali.birdmap.top/Article/details/gt2pjokalpt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhengqikj.top/Article/details/gt2lrykvcsr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.birdmap.top/Article/details/gt2nclbyspw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tianlin.xyz/Article/details/gt2pgcnbnye.html

[N11] 二叉树中序遍历
来源：http://dali.chenlongwang.top/Article/details/gt2fwoynntt.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.aibaodan.cn/Article/details/gt2vvrrkeoa.html

PHP:  // 手写递归函数
来源：http://dali.aibaodan.cn/Article/details/gt2hypvijqe.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.kuanghao11.cn/Article/details/gt2yykcvexr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xinyue.icu/Article/details/gt2nvqfeyug.html

Java: // 手写递归
来源：http://dali.redwolf501.top/Article/details/gt2bjyivfff.html

Go:   // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gt2nuqqvjkd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ehwqpu.com/Article/details/gt2nhbxlzkk.html

C#:   // 手写递归
来源：http://dali.yj20258888.top/Article/details/gt2hwtottdv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nwbrower.top/Article/details/gt2gemoyvsm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.havefunace.top/Article/details/gt2rcbkqcni.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shuidangran.top/Article/details/gt2zlxewarv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gt2xcrmjscj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hongshengwenyu.top/Article/details/gt2suppypas.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258.top/Article/details/gt2ndduaiqu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hfpthk.cn/Article/details/gt2uahcyfnh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zycfv.cn/Article/details/gt2nkawmjqi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ehwqpu.com/Article/details/gt2rjmeroyr.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2xhhcnyap.html

O. 并发与异步
来源：http://dali.hongshengwenyu.top/Article/details/gt2azwcmoop.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2nnhopzxh.html

[O01] 启动一个线程
来源：http://dali.shuidangran.top/Article/details/gt2pfsievsn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ivvv.top/Article/details/gt2uxxwkrbo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xziqi.cn/Article/details/gt2azljjgrv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ppjwa.cn/Article/details/gt2evwnolwh.html

TS:   // 同 JS
来源：http://dali.yueranfly.top/Article/details/gt2njfxvxov.html

Java: new Thread(() -> f()).start()
来源：http://dali.xuetiantiany.cn/Article/details/gt2uhwhglip.html

Go:   go f()
来源：http://dali.fengsongda.top/Article/details/gt2vlvnnawz.html

Ruby: Thread.new { f }
来源：http://dali.bjfxy.top/Article/details/gt2zeurxohy.html

C#:   Task.Run(() => F());
来源：http://dali.svipenyu.cn/Article/details/gt2lpkfrrzd.html

[O02] 使用线程池
来源：http://dali.dianchejie.cn/Article/details/gt2dmrfuyqc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cheryme.top/Article/details/gt2lpqrohzv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenlongwang.top/Article/details/gt2hrfrhaxc.html

JS:   // worker_threads 线程池
来源：http://dali.chenlongwang.top/Article/details/gt2xyhynphp.html

TS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gt2tvnesjop.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.iojbl.cn/Article/details/gt2gdpomfty.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yanxiufei.cn/Article/details/gt2ezwujmhc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hammf.cn/Article/details/gt2fzztzbod.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.nwbrower.top/Article/details/gt2xssurumr.html

[O03] 加锁保护共享数据
来源：http://dali.tian-w.cn/Article/details/gt2osqlutym.html

Py:   with lock: shared += 1
来源：http://dali.316326.xyz/Article/details/gt2etjbeqfj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.pycfn.com/Article/details/gt2frfomrth.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xuanzx.com/Article/details/gt2kedfqfsz.html

TS:   // 同 JS
来源：http://dali.hammf.cn/Article/details/gt2ofrenquo.html

Java: synchronized (this) { shared++; }
来源：http://dali.quarkkingdee.top/Article/details/gt2gaovekot.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ozddtvjr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jqgufenzy.top/Article/details/gt2vfnbnkcs.html

C#:   lock (gate) { shared++; }
来源：http://dali.meibo888.top/Article/details/gt2owoymxnc.html

[O04] 定义异步函数并等待
来源：http://dali.chenjidiqi.icu/Article/details/gt2geopntvg.html

Py:   async def f():⏎    await g()
来源：http://dali.xylfe.cn/Article/details/gt2qkhugznd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gyfjuils.html

JS:   async function f() { await g(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2swfgcjli.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.aizwys.cn/Article/details/gt2hmgpxncv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinqigfzy.top/Article/details/gt2clqsemxj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.andypj.xyz/Article/details/gt2estyzrvp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shzxlz.cn/Article/details/gt2rzdkokkc.html

C#:   async Task F() { await G(); }
来源：http://dali.0kj1m.cn/Article/details/gt2xrbybnlc.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fefcfunf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgfzy.top/Article/details/gt2csguguuc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.meibo888.top/Article/details/gt2mcsyooob.html

JS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gt2spluemdq.html

TS:   await Promise.all(tasks)
来源：http://dali.quarkkingdee.top/Article/details/gt2aaihwnig.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xziqi.cn/Article/details/gt2zgtgwamj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ehwqpu.com/Article/details/gt2ahonefen.html

Ruby: threads.map(&:join)
来源：http://dali.cucudq.cn/Article/details/gt2evhajhvz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj202588.top/Article/details/gt2qlxkgwoc.html

[O06] 使用进程池
来源：http://dali.andypj.xyz/Article/details/gt2ucmegklg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.snrcjt.cn/Article/details/gt2nwiqsjzs.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xziqi.cn/Article/details/gt2nvrqgrug.html

JS:   // child_process / cluster 模块
来源：http://dali.sxryk.cn/Article/details/gt2drmamnik.html

TS:   // child_process / cluster 模块
来源：http://dali.dashuyun.cn/Article/details/gt2axwwnnfl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hywenlv.cn/Article/details/gt2hlqrrvrb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hywenlv.cn/Article/details/gt2uzhqtara.html

Ruby: // fork 块
来源：http://dali.ydzc1.top/Article/details/gt2lvokirqo.html

C#:   Parallel.For
来源：http://dali.0kj1m.cn/Article/details/gt2nnicsrya.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2gdujvdaq.html

P. 常用工具函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2lkbmyxcc.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2jgmmyhdc.html

[P01] 生成 UUID
来源：http://dali.guannengcc.top/Article/details/gt2llgnytwo.html

Py:   str(uuid.uuid4())
来源：http://dali.gzhubu.top/Article/details/gt2wuuhcusy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.fengsongda.top/Article/details/gt2xylnbcpo.html

JS:   crypto.randomUUID()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tqlakith.html

TS:   crypto.randomUUID()
来源：http://dali.tanke756.top/Article/details/gt2zuukzyiq.html

Java: UUID.randomUUID().toString()
来源：http://dali.tanke756.top/Article/details/gt2insdxmxw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.daria6918.cn/Article/details/gt2skhatyxa.html

Ruby: SecureRandom.uuid
来源：http://dali.jianghu66.top/Article/details/gt2tyyetsbs.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.snrcjt.cn/Article/details/gt2arvqqfsq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hongshengwenyu.top/Article/details/gt2zljtynjv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shzxlz.cn/Article/details/gt2uopnmdbm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.9152youxi.cn/Article/details/gt2beguhcdu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ehwqpu.com/Article/details/gt2izomtjsm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gaohongyu789.top/Article/details/gt2cbhhjysb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tianlin.xyz/Article/details/gt2anxkrsva.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.kuanghao11.cn/Article/details/gt2wezuuhvo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2rfdaiava.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.redwolf501.top/Article/details/gt2wjlrspbt.html

[P03] 生成短随机字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2zugqqjsq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.birdmap.top/Article/details/gt2ibihiznv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yj202588.top/Article/details/gt2swgquatr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.316326.xyz/Article/details/gt2eqmazodi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sysykeji.top/Article/details/gt2qiqvvrrm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nanxinkj.top/Article/details/gt2zunldbho.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yonumen.top/Article/details/gt2hfbfnipg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.snrcjt.cn/Article/details/gt2swguchri.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yueranfly.top/Article/details/gt2nwbcncpp.html

[P04] 求长度
来源：http://dali.pycfn.com/Article/details/gt2airtnzvk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jqgfzy.top/Article/details/gt2fehpeaof.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gt2fyfozvug.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gogol.net.cn/Article/details/gt2sdflotex.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgfzy.top/Article/details/gt2xiykgtxj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenzaomai.com/Article/details/gt2avyhgqae.html

Go:   len(arr);  len(m)
来源：http://dali.shzxlz.cn/Article/details/gt2ntlzldnd.html

Ruby: x.length;  x.size
来源：http://dali.nanxinkj.top/Article/details/gt2xdyjdyef.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.vqdsnc.cn/Article/details/gt2epqiimmz.html


<!-- 参考信息 -->