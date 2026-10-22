代发 wailian999

TS:   resp.ok;  resp.status
来源：http://dali.yuxming.cn/Article/details/gt2cybcozaz.html

Java: resp.statusCode()
来源：http://dali.shzxlz.cn/Article/details/gt2vtgvqodk.html

Go:   resp.StatusCode
来源：http://dali.cucudq.cn/Article/details/gt2yujuiuid.html

Ruby: resp.code.to_i
来源：http://dali.nanxinkj.top/Article/details/gt2cughbzlw.html

C#:   (int)resp.StatusCode
来源：http://dali.aizwys.cn/Article/details/gt2ljgafeyl.html

[L08] 并发请求多个地址
来源：http://dali.cqqwz.cn/Article/details/gt2ynkqihsx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.c1oappe.top/Article/details/gt2zhaxogcl.html

PHP:  curl_multi_init() 系列
来源：http://dali.pycfn.com/Article/details/gt2dmiogpph.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gt2wjnejawp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gt2baajgzdm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fengsongda.top/Article/details/gt2tmhwtvsn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.feifeiyinyue.top/Article/details/gt2vuoloidk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jlsjyb.cn/Article/details/gt2xakddfiv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xziqi.cn/Article/details/gt2lbzdjiyr.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2etuslycz.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinghuilouyu.cn/Article/details/gt2frimsbey.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2qxosxmno.html

[M01] 读取命令行参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2aivaffsm.html

Py:   sys.argv[1:]
来源：http://dali.xylfe.cn/Article/details/gt2arrjwqbw.html

PHP:  $argv;  $argc;
来源：http://dali.jiagoushi.top/Article/details/gt2hnxjiczv.html

JS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2uennwjbl.html

TS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gt2cfgfntpp.html

Java: args 数组（main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gt2fxhmdmdh.html

Go:   os.Args[1:]
来源：http://dali.sysykeji.top/Article/details/gt2gvkkzhgm.html

Ruby: ARGV
来源：http://dali.meibo888.top/Article/details/gt2nuxxpwpd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gt2wrqajunc.html

[M02] 读取环境变量
来源：http://dali.jinqigufen.top/Article/details/gt2ojfnbxii.html

Py:   os.environ.get("HOME")
来源：http://dali.dashuyun.cn/Article/details/gt2qgvwnfbp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gt2densohbd.html

JS:   process.env.HOME
来源：http://dali.yonumen.top/Article/details/gt2dgzvosfn.html

TS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gt2yamydjmt.html

Java: System.getenv("HOME")
来源：http://dali.cucudq.cn/Article/details/gt2tbnygqrn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nanxinkj.top/Article/details/gt2zsmtjjyy.html

Ruby: ENV["HOME"]
来源：http://dali.sysykeji.top/Article/details/gt2exbcxxyu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.andypj.xyz/Article/details/gt2wmgvzxih.html

[M03] 执行外部命令
来源：http://dali.cucudq.cn/Article/details/gt2spqaggez.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yueranfly.top/Article/details/gt2vidobkkz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yuanzhike.top/Article/details/gt2jzurqgru.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gt2xklkswfa.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yvedp.cn/Article/details/gt2fssuewfl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.mhx1999.top/Article/details/gt2yyjjmkln.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jyoumei.cn/Article/details/gt2hfxbzwfn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xylfe.cn/Article/details/gt2gyfsbrvw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangshuangyany.cn/Article/details/gt2dsjohjcb.html

[M04] 获取当前工作目录
来源：http://dali.svipenyu.cn/Article/details/gt2dtnlqeat.html

Py:   os.getcwd()
来源：http://dali.cheryme.top/Article/details/gt2cecukjey.html

PHP:  getcwd();
来源：http://dali.xuetiantiany.cn/Article/details/gt2kjkvipzy.html

JS:   process.cwd()
来源：http://dali.cdnleiting.top/Article/details/gt2qrcnshkj.html

TS:   process.cwd()
来源：http://dali.hammf.cn/Article/details/gt2cwapcxcu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hywenlv.cn/Article/details/gt2wxlrmrsg.html

Go:   os.Getwd()
来源：http://dali.hammf.cn/Article/details/gt2cijfsdnx.html

Ruby: Dir.pwd
来源：http://dali.svipenyu.cn/Article/details/gt2sgdcomin.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zdqjudy.top/Article/details/gt2nerrydjb.html

[M05] 设置退出码
来源：http://dali.shangyingyoupin.top/Article/details/gt2wybnruyc.html

Py:   sys.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vnnqspjm.html

PHP:  exit(1);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ayaemkby.html

JS:   process.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2hmxxxnza.html

TS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2opbtelij.html

Java: System.exit(1)
来源：http://dali.mhx1999.top/Article/details/gt2dwydcmkb.html

Go:   os.Exit(1)
来源：http://dali.xuanzx.com/Article/details/gt2oaalneix.html

Ruby: exit 1
来源：http://dali.shzxlz.cn/Article/details/gt2dckaqduy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2okjqhtyp.html

[M06] 向标准错误输出
来源：http://dali.daria6918.cn/Article/details/gt2rbblaemc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.redwolf501.top/Article/details/gt2gyqffffa.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jiagoushi.top/Article/details/gt2gzontafr.html

JS:   console.error("err")
来源：http://dali.jlsjyb.cn/Article/details/gt2irayvmfa.html

TS:   console.error("err")
来源：http://dali.meibo888.top/Article/details/gt2mopulglm.html

Java: System.err.println("err")
来源：http://dali.tian-w.cn/Article/details/gt2lwqzjejd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jqgufenzy.top/Article/details/gt2qolvxqar.html

Ruby: warn "err"
来源：http://dali.yueranfly.top/Article/details/gt2wgffvjqd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jqgfzy.top/Article/details/gt2ejhwwfto.html

[M07] 判断是否为主入口
来源：http://dali.daxiang520.top/Article/details/gt2balvnsnr.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigfzy.top/Article/details/gt2xuyhfcue.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhengqikj.top/Article/details/gt2kacqjtyf.html

JS:   require.main === module
来源：http://dali.jlsjyb.cn/Article/details/gt2mpbodtiy.html

TS:   require.main === module
来源：http://dali.xylfe.cn/Article/details/gt2fmeltplo.html

Java: public static void main(String[] args)
来源：http://dali.xinyue.icu/Article/details/gt2ovrdsllm.html

Go:   func main()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cwjijmaz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.daria6918.cn/Article/details/gt2sjlydnlu.html

C#:   static void Main(string[] args)
来源：http://dali.yangfankeji.com/Article/details/gt2utnhguro.html

[M08] 获取系统与运行时信息
来源：http://dali.cashguo.top/Article/details/gt2tcbziwyn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sweek.top/Article/details/gt2hqalldlh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shangyingyoupin.top/Article/details/gt2yxsbgfpr.html

JS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gt2ugiwtpsj.html

TS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gt2iaouejxh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xuanzx.com/Article/details/gt2ssqiebsa.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhoulong.xyz/Article/details/gt2bpuyjkdg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cashguo.top/Article/details/gt2hwxbwytn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zycfv.cn/Article/details/gt2coeudxhd.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2ldpqflbt.html

N. 数据结构与算法
来源：http://dali.birdmap.top/Article/details/gt2lysgggej.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2rpuvgwjb.html

[N01] 二分查找（有序数组）
来源：http://dali.xziqi.cn/Article/details/gt2plhnndun.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ocivhwrz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jyoumei.cn/Article/details/gt2xxqxgavb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgfzy.top/Article/details/gt2bqkbtbbc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cheryme.top/Article/details/gt2dpobuofa.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2oiogwgld.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lbidrlpa.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.birdmap.top/Article/details/gt2bdjjjupg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gt2rfxrcqle.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgfzy.top/Article/details/gt2gegogmds.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hniuavfv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nanxuanxn.top/Article/details/gt2rohhbhsi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gt2psqmtagp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhengqikj.top/Article/details/gt2moccnojq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cucudq.cn/Article/details/gt2pabcioto.html

Go:   slices.Sort(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2zxzoxbpo.html

Ruby: arr.sort
来源：http://dali.sxryk.cn/Article/details/gt2hmwjetgd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hnxiangtu.top/Article/details/gt2rtevgujt.html

[N03] 快速排序（分治示例）
来源：http://dali.nwbrower.top/Article/details/gt2azqbcrxn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yonumen.top/Article/details/gt2azeaynpm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shangyingyoupin.top/Article/details/gt2hujjftkc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gt2mfpbyaip.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxuanxn.top/Article/details/gt2qqcjftbw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cheryme.top/Article/details/gt2yxxrinzk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.guannengcc.top/Article/details/gt2pgatttcx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sufxvd.cn/Article/details/gt2erhwgwkr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sweek.top/Article/details/gt2wlxejovh.html

[N04] 斐波那契数列
来源：http://dali.chenzaomai.com/Article/details/gt2sfxkxhfg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenlongwang.top/Article/details/gt2latddcve.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nwbrower.top/Article/details/gt2lvysjqfs.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gt2dzgdryec.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gt2wulrxtup.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2huitdktg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2etonytzj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fkediner.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gt2bjmqpobk.html

[N05] 最大公约数
来源：http://dali.fzhhl.top/Article/details/gt2qcafbokz.html

Py:   math.gcd(a, b)
来源：http://dali.zycfv.cn/Article/details/gt2unaxjxxr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hysaishi.cn/Article/details/gt2hqfeeqgi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sufxvd.cn/Article/details/gt2zjcfpreb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2rklixrji.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shzxlz.cn/Article/details/gt2ehobfrig.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xinyue.icu/Article/details/gt2qszszaqh.html

Ruby: a.gcd(b)
来源：http://dali.yj20258888.top/Article/details/gt2rrpjsgyi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xuanzx.com/Article/details/gt2xgnpqtmp.html

[N06] 判断回文字符串
来源：http://dali.guowangkeji.top/Article/details/gt2acprgoaz.html

Py:   s == s[::-1]
来源：http://dali.sweek.top/Article/details/gt2beykazdx.html

PHP:  $s === strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2oogkwslp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gt2avqashkg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2qsvhtyqz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhiwuduotai.top/Article/details/gt2mjvnlkga.html

Go:   // 双指针从两端比较
来源：http://dali.cashguo.top/Article/details/gt2xdgqirbp.html

Ruby: s == s.reverse
来源：http://dali.daria6918.cn/Article/details/gt2ivnjynol.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nanxuanxn.top/Article/details/gt2gdsfctsl.html

[N07] 两数之和（返回下标）
来源：http://dali.havefunace.top/Article/details/gt2bwiqzygg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.fengsongda.top/Article/details/gt2kbubjbrp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.dashuyun.cn/Article/details/gt2ldimxgkz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yuxming.cn/Article/details/gt2atikjidc.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhiwuduotai.top/Article/details/gt2xblhqzly.html

Java: // 手写 HashMap
来源：http://dali.sysykeji.top/Article/details/gt2gmvwpnrr.html

Go:   // 手写 map[int]int
来源：http://dali.havefunace.top/Article/details/gt2jnmbhecq.html

Ruby: // 手写 Hash
来源：http://dali.chenjidiqi.icu/Article/details/gt2tambwmud.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.aibaodan.cn/Article/details/gt2yrgldogm.html

[N08] 生成全排列
来源：http://dali.jiagoushi.top/Article/details/gt2hvzpcjte.html

Py:   itertools.permutations(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2tdipcmpg.html

PHP:  // 手写递归交换
来源：http://dali.sysykeji.top/Article/details/gt2mazmovxd.html

JS:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gt2busmmebb.html

TS:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gt2ejxrgldl.html

Java: // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gt2gwfpbvcn.html

Go:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gt2cpubzbvt.html

Ruby: arr.permutation.to_a
来源：http://dali.kuanghao11.cn/Article/details/gt2bccpfxqb.html

C#:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gt2qpottfkg.html

[N09] 栈与队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rzvoqjib.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sufxvd.cn/Article/details/gt2kuflnood.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.aizwys.cn/Article/details/gt2mywpeujg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shuidangran.top/Article/details/gt2qmgiodhi.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nanxinkj.top/Article/details/gt2mxlblysi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.quarkkingdee.top/Article/details/gt2scllqecv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinqigfzy.top/Article/details/gt2joashchm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2fuzatkrp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ehwqpu.com/Article/details/gt2ulwgnlwf.html

[N10] 链表节点定义
来源：http://dali.xinyue.icu/Article/details/gt2uniggzoz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hfpthk.cn/Article/details/gt2bynqsorw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.fengsongda.top/Article/details/gt2fjacakww.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.mhx1999.top/Article/details/gt2vezsonhf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nwbrower.top/Article/details/gt2cghaehef.html

Java: class Node { int v; Node next; }
来源：http://dali.pycfn.com/Article/details/gt2crnptnyz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ydzc1.top/Article/details/gt2sdqwpgkg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2okjeuduq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinqigfzy.top/Article/details/gt2djfzuhuk.html

[N11] 二叉树中序遍历
来源：http://dali.redwolf501.top/Article/details/gt2gnnnnlpk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xziqi.cn/Article/details/gt2xurmtobw.html

PHP:  // 手写递归函数
来源：http://dali.fengsongda.top/Article/details/gt2szahamru.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xinyue.icu/Article/details/gt2uadhjftj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gaohongyu789.top/Article/details/gt2qpwozoow.html

Java: // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gt2ouspnfiq.html

Go:   // 手写递归
来源：http://dali.daxiang520.top/Article/details/gt2qcabsmcd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ivvv.top/Article/details/gt2mfoiijes.html

C#:   // 手写递归
来源：http://dali.pycfn.com/Article/details/gt2hxdcyjhe.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.chenlongwang.top/Article/details/gt2oeboeudz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.havefunace.top/Article/details/gt2cqgzkmeo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.vqdsnc.cn/Article/details/gt2pkdmkklh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ivvv.top/Article/details/gt2xadorizn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenjidiqi.icu/Article/details/gt2qbaxfejm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shzxlz.cn/Article/details/gt2qpuhotez.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sweek.top/Article/details/gt2eswlayru.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuxming.cn/Article/details/gt2nbipbtvv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dfmbsifb.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2mncubnpj.html

O. 并发与异步
来源：http://dali.birdmap.top/Article/details/gt2hwobwqnl.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2utgyeyjj.html

[O01] 启动一个线程
来源：http://dali.aizwys.cn/Article/details/gt2jwqzdfvt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gotoacloud.top/Article/details/gt2myuinlns.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.mhx1999.top/Article/details/gt2vfjchfvl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.mhx1999.top/Article/details/gt2rvyamnjh.html

TS:   // 同 JS
来源：http://dali.cucudq.cn/Article/details/gt2gesgccnm.html

Java: new Thread(() -> f()).start()
来源：http://dali.redwolf501.top/Article/details/gt2kouzovmn.html

Go:   go f()
来源：http://dali.yueranfly.top/Article/details/gt2qrvxnbjx.html

Ruby: Thread.new { f }
来源：http://dali.xuetiantiany.cn/Article/details/gt2lsthfeng.html

C#:   Task.Run(() => F());
来源：http://dali.aibaodan.cn/Article/details/gt2jrkfawzi.html

[O02] 使用线程池
来源：http://dali.jiagoushi.top/Article/details/gt2nfkzumaa.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.feifeiyinyue.top/Article/details/gt2eqagzaur.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zlptflgn.html

JS:   // worker_threads 线程池
来源：http://dali.nanxinkj.top/Article/details/gt2zaochpws.html

TS:   // worker_threads 线程池
来源：http://dali.xuanzx.com/Article/details/gt2csqsgirj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinqigufen.top/Article/details/gt2xksnbpvf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ybcxt.top/Article/details/gt2felsopto.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nnzinyzo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xylfe.cn/Article/details/gt2jwsuqbvm.html

[O03] 加锁保护共享数据
来源：http://dali.daxiang520.top/Article/details/gt2ullzbqhz.html

Py:   with lock: shared += 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2fphupwdd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.aibaodan.cn/Article/details/gt2cyugfzck.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.pengpengdd.cyou/Article/details/gt2fodvvnvk.html

TS:   // 同 JS
来源：http://dali.hammf.cn/Article/details/gt2hxpjglof.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vlmxiebb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sysykeji.top/Article/details/gt2xpolbtkt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yonumen.top/Article/details/gt2jgdiurrn.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tmknldfm.html

[O04] 定义异步函数并等待
来源：http://dali.nanxuanxn.top/Article/details/gt2ijtcaojo.html

Py:   async def f():⏎    await g()
来源：http://dali.pycfn.com/Article/details/gt2lyiizcxh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hammf.cn/Article/details/gt2sgmlinjt.html

JS:   async function f() { await g(); }
来源：http://dali.hammf.cn/Article/details/gt2pxnygmoe.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnqzz.top/Article/details/gt2gczmvyfi.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.316326.xyz/Article/details/gt2ktzmsxvj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mtpaicso.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bhbmrnkd.html

C#:   async Task F() { await G(); }
来源：http://dali.daxiang520.top/Article/details/gt2vpmdewgx.html

[O05] 并发执行并等待全部完成
来源：http://dali.xuetiantiany.cn/Article/details/gt2ndzkioje.html

Py:   asyncio.gather(*tasks)
来源：http://dali.dashuyun.cn/Article/details/gt2vkhdwbit.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kxdftuxm.html

JS:   await Promise.all(tasks)
来源：http://dali.yuanzhike.top/Article/details/gt2ftikyzss.html

TS:   await Promise.all(tasks)
来源：http://dali.cashguo.top/Article/details/gt2zobwzchz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shuidangran.top/Article/details/gt2trgrtqcc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tianlin.xyz/Article/details/gt2zqldbcoo.html

Ruby: threads.map(&:join)
来源：http://dali.dianchejie.cn/Article/details/gt2uoujspva.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenlongwang.top/Article/details/gt2fcfwtxeb.html

[O06] 使用进程池
来源：http://dali.yj20258.top/Article/details/gt2ufipwzdw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yongpay.top/Article/details/gt2kuvtmtbv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.9152youxi.cn/Article/details/gt2sohwjdld.html

JS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gt2qhgfuiex.html

TS:   // child_process / cluster 模块
来源：http://dali.zhixingplan.top/Article/details/gt2idfmoqhf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.nanxuanxn.top/Article/details/gt2mqkvnpmj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ppjwa.cn/Article/details/gt2zdkdzsst.html

Ruby: // fork 块
来源：http://dali.xylfe.cn/Article/details/gt2zgordkif.html

C#:   Parallel.For
来源：http://dali.nwbrower.top/Article/details/gt2fqmxjhfw.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2vjcjgfpo.html

P. 常用工具函数
来源：http://dali.fzhhl.top/Article/details/gt2rssxxnwd.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2hcklfkdu.html

[P01] 生成 UUID
来源：http://dali.ybcxt.top/Article/details/gt2axxbaebx.html

Py:   str(uuid.uuid4())
来源：http://dali.zhongyouzk.top/Article/details/gt2dfodehep.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.wangdashe.top/Article/details/gt2bfurbqwz.html

JS:   crypto.randomUUID()
来源：http://dali.hysaishi.cn/Article/details/gt2uwtqbcvx.html

TS:   crypto.randomUUID()
来源：http://dali.wangshuangyany.cn/Article/details/gt2csblekri.html

Java: UUID.randomUUID().toString()
来源：http://dali.shangyingyoupin.top/Article/details/gt2xiftiuhg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cqqwz.cn/Article/details/gt2erkvkydb.html

Ruby: SecureRandom.uuid
来源：http://dali.fzhhl.top/Article/details/gt2riymtzye.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.andypj.xyz/Article/details/gt2ywdwhfdq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cashguo.top/Article/details/gt2hlddeghj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigfzy.top/Article/details/gt2fzihmdin.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jlsjyb.cn/Article/details/gt2eqdqukvs.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zdqjudy.top/Article/details/gt2mfnerchw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.kuanghao11.cn/Article/details/gt2xfzdfwgn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hhjwmvgy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jqgufenzy.top/Article/details/gt2zlviiqoq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hammf.cn/Article/details/gt2yccatzeq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ehwqpu.com/Article/details/gt2bqgpixkp.html

[P03] 生成短随机字符串
来源：http://dali.aibaodan.cn/Article/details/gt2vtyfnbic.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangdashe.top/Article/details/gt2txmqhnla.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sysykeji.top/Article/details/gt2umlmeseo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yueranfly.top/Article/details/gt2irzrovas.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.9152youxi.cn/Article/details/gt2qgksxyjm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xinyue.icu/Article/details/gt2cjcvppuh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.kuanghao11.cn/Article/details/gt2juliemga.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj20258.top/Article/details/gt2efyyxeve.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.c1oappe.top/Article/details/gt2hfatkqie.html

[P04] 求长度
来源：http://dali.ybcxt.top/Article/details/gt2yhfqeklt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.smart0.xyz/Article/details/gt2wcyclhpu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gt2dngcuzjq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.316326.xyz/Article/details/gt2bwqvnqqg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuetiantiany.cn/Article/details/gt2ugqveqln.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yuanzhike.top/Article/details/gt2jhszufto.html

Go:   len(arr);  len(m)
来源：http://dali.jqgufenzy.top/Article/details/gt2cchcwwhw.html

Ruby: x.length;  x.size
来源：http://dali.zhongyouzk.top/Article/details/gt2wiczpkri.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ehwqpu.com/Article/details/gt2enkxzjow.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jlsjyb.cn/Article/details/gt2ygrudryx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhengqikj.top/Article/details/gt2sgezmzer.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hammf.cn/Article/details/gt2ffbrkaeg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.snrcjt.cn/Article/details/gt2lnqfeuhs.html


<!-- 参考信息 -->