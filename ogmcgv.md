代发 wailian999

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guowangkeji.top/Article/details/gt2llgmldwx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gt2aczokgxb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jqgufenzy.top/Article/details/gt2fwedmlwq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.bjfxy.top/Article/details/gt2ppiowvnb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sufxvd.cn/Article/details/gt2xdqzrcrc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinqigufen.top/Article/details/gt2hylrerja.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2cxbkjzak.html

M. 命令行 / 进程 / 环境
来源：http://dali.bjfxy.top/Article/details/gt2rjenmkge.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2yomsuove.html

[M01] 读取命令行参数
来源：http://dali.tianlin.xyz/Article/details/gt2cqxyuoiu.html

Py:   sys.argv[1:]
来源：http://dali.cheryme.top/Article/details/gt2jcnhbjtp.html

PHP:  $argv;  $argc;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fsaiffkz.html

JS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gt2yjzyofox.html

TS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gt2crotldyf.html

Java: args 数组（main 方法参数）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ubhyqgux.html

Go:   os.Args[1:]
来源：http://dali.jyoumei.cn/Article/details/gt2cdnpgano.html

Ruby: ARGV
来源：http://dali.zhongyouzk.top/Article/details/gt2tnphpxal.html

C#:   args 数组（Main 方法参数）
来源：http://dali.bjfxy.top/Article/details/gt2yuodokdf.html

[M02] 读取环境变量
来源：http://dali.cucudq.cn/Article/details/gt2uhsdoolw.html

Py:   os.environ.get("HOME")
来源：http://dali.xuanzx.com/Article/details/gt2mgvcolrl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gt2butuwhem.html

JS:   process.env.HOME
来源：http://dali.gogol.net.cn/Article/details/gt2cmbliwld.html

TS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gt2pyjnyuae.html

Java: System.getenv("HOME")
来源：http://dali.jianghu66.top/Article/details/gt2zpxovymm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ybcxt.top/Article/details/gt2ocrrsarm.html

Ruby: ENV["HOME"]
来源：http://dali.hfpthk.cn/Article/details/gt2iedfmeaj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gzhubu.top/Article/details/gt2jsdkfskq.html

[M03] 执行外部命令
来源：http://dali.birdmap.top/Article/details/gt2zycbubup.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dkqsijzm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shangyingyoupin.top/Article/details/gt2xvdomsbe.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dashuyun.cn/Article/details/gt2dyonvjyo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gt2hdecshcl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yueranfly.top/Article/details/gt2sgrudlgk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj20258.top/Article/details/gt2crufwsjk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yuxming.cn/Article/details/gt2pccbgwln.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinqigfzy.top/Article/details/gt2selqowfp.html

[M04] 获取当前工作目录
来源：http://dali.sufxvd.cn/Article/details/gt2dqgplpxm.html

Py:   os.getcwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rvlbqscz.html

PHP:  getcwd();
来源：http://dali.snrcjt.cn/Article/details/gt2nqxzmazu.html

JS:   process.cwd()
来源：http://dali.daria6918.cn/Article/details/gt2zfjpajhe.html

TS:   process.cwd()
来源：http://dali.cheryme.top/Article/details/gt2pbpwsqho.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xinyue.icu/Article/details/gt2gvinkluw.html

Go:   os.Getwd()
来源：http://dali.jianghu66.top/Article/details/gt2msiqpdvg.html

Ruby: Dir.pwd
来源：http://dali.yuxming.cn/Article/details/gt2oesukcda.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cashguo.top/Article/details/gt2mvnzbeic.html

[M05] 设置退出码
来源：http://dali.cdnleiting.top/Article/details/gt2avskfrtr.html

Py:   sys.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2slgpkqed.html

PHP:  exit(1);
来源：http://dali.yj202588.top/Article/details/gt2pqxpwehz.html

JS:   process.exit(1)
来源：http://dali.cheryme.top/Article/details/gt2wjlyzhoq.html

TS:   process.exit(1)
来源：http://dali.jianghu66.top/Article/details/gt2lrjwffiy.html

Java: System.exit(1)
来源：http://dali.ivvv.top/Article/details/gt2mgihgbse.html

Go:   os.Exit(1)
来源：http://dali.sxryk.cn/Article/details/gt2czehyjzc.html

Ruby: exit 1
来源：http://dali.jianghu66.top/Article/details/gt2oxsrrmym.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tanke756.top/Article/details/gt2qcjhdpky.html

[M06] 向标准错误输出
来源：http://dali.havefunace.top/Article/details/gt2cmlfgkmx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.quarkkingdee.top/Article/details/gt2qvknhcpj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yangfankeji.com/Article/details/gt2pyhkgzck.html

JS:   console.error("err")
来源：http://dali.jinqigfzy.top/Article/details/gt2erjdtbfo.html

TS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gt2bqtflvoh.html

Java: System.err.println("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2poavslsu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.meibo888.top/Article/details/gt2poroulej.html

Ruby: warn "err"
来源：http://dali.quarkkingdee.top/Article/details/gt2vmnjsfrb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tanke756.top/Article/details/gt2uzpekjpy.html

[M07] 判断是否为主入口
来源：http://dali.feifeiyinyue.top/Article/details/gt2vxrjwszx.html

Py:   if __name__ == "__main__":
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fhshhrft.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gotoacloud.top/Article/details/gt2bbriaqyz.html

JS:   require.main === module
来源：http://dali.haohaochexian.top/Article/details/gt2wtrxldhl.html

TS:   require.main === module
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xpteveci.html

Java: public static void main(String[] args)
来源：http://dali.fengsongda.top/Article/details/gt2phqveffc.html

Go:   func main()
来源：http://dali.jlsjyb.cn/Article/details/gt2rbycckqm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhiwuduotai.top/Article/details/gt2brgbzolg.html

C#:   static void Main(string[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gt2guciqwju.html

[M08] 获取系统与运行时信息
来源：http://dali.yj20258888.top/Article/details/gt2ooztbjzw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.dianchejie.cn/Article/details/gt2rtvpgqgk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ppjwa.cn/Article/details/gt2mcjaawrw.html

JS:   process.platform;  process.version
来源：http://dali.fengsongda.top/Article/details/gt2uihvszks.html

TS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gt2sledxtrb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ydzc1.top/Article/details/gt2pfqosxgr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yongpay.top/Article/details/gt2tohxfysn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tian-w.cn/Article/details/gt2uhzlacdk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hysaishi.cn/Article/details/gt2yehrwgze.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2mqlzdois.html

N. 数据结构与算法
来源：http://dali.hywenlv.cn/Article/details/gt2frdwacmw.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2razfxpnc.html

[N01] 二分查找（有序数组）
来源：http://dali.xuanzx.com/Article/details/gt2tmcbfinu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2rijyeehj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jiagoushi.top/Article/details/gt2pvynnlow.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sufxvd.cn/Article/details/gt2ycbkeksj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.meibo888.top/Article/details/gt2hvenweay.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.bjfxy.top/Article/details/gt2okynvmzx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gt2nclpftbh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.fzhhl.top/Article/details/gt2bdpqkrfo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj20258.top/Article/details/gt2gcizprtz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tian-w.cn/Article/details/gt2arifeybz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shuidangran.top/Article/details/gt2rkkziqfr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.daxiang520.top/Article/details/gt2yjfysmmp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gt2rdyhhzcd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gt2ojapsqnw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.iojbl.cn/Article/details/gt2fwdaqvbj.html

Go:   slices.Sort(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hysldlbj.html

Ruby: arr.sort
来源：http://dali.chenzaomai.com/Article/details/gt2cwfolggy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhoulong.xyz/Article/details/gt2lasyfjwa.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxinkj.top/Article/details/gt2rgrkvlrf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.daria6918.cn/Article/details/gt2avvgqxiy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yangfankeji.com/Article/details/gt2rehuhdra.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cucudq.cn/Article/details/gt2bxjwxsgx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nwbrower.top/Article/details/gt2knosjlzn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shzxlz.cn/Article/details/gt2yarylrwg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.pengpengdd.cyou/Article/details/gt2kdrkrzfv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gogol.net.cn/Article/details/gt2bduzpuiw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ppjwa.cn/Article/details/gt2tsliebsj.html

[N04] 斐波那契数列
来源：http://dali.ivvv.top/Article/details/gt2rdlsvosu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2rfokasfu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.pycfn.com/Article/details/gt2txwtxdlu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gt2mqdzogml.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gt2fzvsujzt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gt2ppemqqbj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gogol.net.cn/Article/details/gt2zegoonrx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gt2vqwwvxhb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gt2ransmusw.html

[N05] 最大公约数
来源：http://dali.guannengcc.top/Article/details/gt2zhaxtcvz.html

Py:   math.gcd(a, b)
来源：http://dali.guowangkeji.top/Article/details/gt2jqclqfdn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xuanzx.com/Article/details/gt2mkbughee.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aizwys.cn/Article/details/gt2jyudqjfs.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cashguo.top/Article/details/gt2nvbtbolc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ehwqpu.com/Article/details/gt2scoatzhm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhoulong.xyz/Article/details/gt2tdhjvxls.html

Ruby: a.gcd(b)
来源：http://dali.jqgufenzy.top/Article/details/gt2qnzqikyr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.daxiang520.top/Article/details/gt2wazwntlm.html

[N06] 判断回文字符串
来源：http://dali.xinyue.icu/Article/details/gt2tnaqsqbz.html

Py:   s == s[::-1]
来源：http://dali.zhongyouzk.top/Article/details/gt2fwqkbfkp.html

PHP:  $s === strrev($s);
来源：http://dali.chenzaomai.com/Article/details/gt2jdaenncp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gt2gyvyhpie.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gt2avidmrou.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xinyue.icu/Article/details/gt2ijlzmctz.html

Go:   // 双指针从两端比较
来源：http://dali.fzhhl.top/Article/details/gt2oytgwcfh.html

Ruby: s == s.reverse
来源：http://dali.ehwqpu.com/Article/details/gt2bajxjjrw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nanxuanxn.top/Article/details/gt2bpwcqqhd.html

[N07] 两数之和（返回下标）
来源：http://dali.snrcjt.cn/Article/details/gt2snfbnhxp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gogol.net.cn/Article/details/gt2jcsbfojn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zkftwfqx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sxryk.cn/Article/details/gt2orvrtviz.html

TS:   // 手写 Map<string, number>
来源：http://dali.cheryme.top/Article/details/gt2srbhwlph.html

Java: // 手写 HashMap
来源：http://dali.guannengcc.top/Article/details/gt2trffcnkj.html

Go:   // 手写 map[int]int
来源：http://dali.jyoumei.cn/Article/details/gt2xiajcdrw.html

Ruby: // 手写 Hash
来源：http://dali.xziqi.cn/Article/details/gt2eaoavzvs.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cqqwz.cn/Article/details/gt2hndhyhtq.html

[N08] 生成全排列
来源：http://dali.wangdashe.top/Article/details/gt2elzzvyjs.html

Py:   itertools.permutations(arr)
来源：http://dali.ivvv.top/Article/details/gt2jwbrdwyk.html

PHP:  // 手写递归交换
来源：http://dali.ybcxt.top/Article/details/gt2dfvrnydk.html

JS:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gt2qyrizbqt.html

TS:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gt2rvrvqsfs.html

Java: // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gt2cfzwlsxt.html

Go:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gt2rlisqjzy.html

Ruby: arr.permutation.to_a
来源：http://dali.hysaishi.cn/Article/details/gt2hmknrjbe.html

C#:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gt2zwqabucn.html

[N09] 栈与队列
来源：http://dali.shzxlz.cn/Article/details/gt2sasrxxjb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenzaomai.com/Article/details/gt2adplpqlx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shuidangran.top/Article/details/gt2pvwzkixk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tian-w.cn/Article/details/gt2hykkcbut.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhiwuduotai.top/Article/details/gt2dqxmyttj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jlsjyb.cn/Article/details/gt2ftcrculm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxuanxn.top/Article/details/gt2kcgpcxap.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jyoumei.cn/Article/details/gt2qgbxjcfx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hnqzz.top/Article/details/gt2ribmblvn.html

[N10] 链表节点定义
来源：http://dali.havefunace.top/Article/details/gt2bwryvzgl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.svipenyu.cn/Article/details/gt2jvmbhlmp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ijdcwlyd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yanxiufei.cn/Article/details/gt2iuxzkskb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.redwolf501.top/Article/details/gt2enijzbxb.html

Java: class Node { int v; Node next; }
来源：http://dali.iojbl.cn/Article/details/gt2ibmtuwuh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yanxiufei.cn/Article/details/gt2eesdqzge.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sufxvd.cn/Article/details/gt2eosbtngl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cashguo.top/Article/details/gt2agceetkt.html

[N11] 二叉树中序遍历
来源：http://dali.cheryme.top/Article/details/gt2rclfapxn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ivvv.top/Article/details/gt2gtgfoofg.html

PHP:  // 手写递归函数
来源：http://dali.yvedp.cn/Article/details/gt2lemrzjlf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2piuibedj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2urpnmyoj.html

Java: // 手写递归
来源：http://dali.316326.xyz/Article/details/gt2zmiinlsb.html

Go:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gt2whrawglv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xrhmpkug.html

C#:   // 手写递归
来源：http://dali.hnqzz.top/Article/details/gt2nwomnyno.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gogol.net.cn/Article/details/gt2nsfpbhzk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.pengpengdd.cyou/Article/details/gt2cfothgze.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.guannengcc.top/Article/details/gt2rkuyhnqq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jianghu66.top/Article/details/gt2miobqicu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zycfv.cn/Article/details/gt2yoxqqwvp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jiagoushi.top/Article/details/gt2nsjejgeu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yuanzhike.top/Article/details/gt2lwffigbm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.mhx1999.top/Article/details/gt2zxzwduxn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.vqdsnc.cn/Article/details/gt2dwuocbjm.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2grskarys.html

O. 并发与异步
来源：http://dali.gogol.net.cn/Article/details/gt2zvzfnwuj.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2gqeekvsz.html

[O01] 启动一个线程
来源：http://dali.nanxinkj.top/Article/details/gt2mmaotgdi.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shuidangran.top/Article/details/gt2lwpmzewi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.dianchejie.cn/Article/details/gt2juhhwtuu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gogol.net.cn/Article/details/gt2jyjxaoje.html

TS:   // 同 JS
来源：http://dali.xinyue.icu/Article/details/gt2ygwemcjh.html

Java: new Thread(() -> f()).start()
来源：http://dali.ivvv.top/Article/details/gt2czcpdmyu.html

Go:   go f()
来源：http://dali.shuidangran.top/Article/details/gt2ckevwnaw.html

Ruby: Thread.new { f }
来源：http://dali.chenzaomai.com/Article/details/gt2jorpxdsk.html

C#:   Task.Run(() => F());
来源：http://dali.zhoulong.xyz/Article/details/gt2ynsbkgfa.html

[O02] 使用线程池
来源：http://dali.cqqwz.cn/Article/details/gt2mikiwayx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aizwys.cn/Article/details/gt2dkuzneki.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hammf.cn/Article/details/gt2ctnjdsws.html

JS:   // worker_threads 线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cnbpjfob.html

TS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gt2kieqyjsw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tdvsyuyq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhoulong.xyz/Article/details/gt2kcwnlfwl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ydzc1.top/Article/details/gt2oypfrwhv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gaohongyu789.top/Article/details/gt2mqyscjjp.html

[O03] 加锁保护共享数据
来源：http://dali.wangshuangyany.cn/Article/details/gt2imsjfjrn.html

Py:   with lock: shared += 1
来源：http://dali.aibaodan.cn/Article/details/gt2fpwzvbmg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xziqi.cn/Article/details/gt2xltpugai.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gedsfqso.html

TS:   // 同 JS
来源：http://dali.guowangkeji.top/Article/details/gt2fuyqeckq.html

Java: synchronized (this) { shared++; }
来源：http://dali.iojbl.cn/Article/details/gt2vbqgsrwz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ehwqpu.com/Article/details/gt2aaktptag.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tian-w.cn/Article/details/gt2fqpygewh.html

C#:   lock (gate) { shared++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vsaeikzm.html

[O04] 定义异步函数并等待
来源：http://dali.tanke756.top/Article/details/gt2afonmgmv.html

Py:   async def f():⏎    await g()
来源：http://dali.jyoumei.cn/Article/details/gt2hjumycre.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ydzc1.top/Article/details/gt2iulgsqoo.html

JS:   async function f() { await g(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ucrywjgr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.meibo888.top/Article/details/gt2iphlnhot.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nanxuanxn.top/Article/details/gt2uwzqsxwu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhoulong.xyz/Article/details/gt2gokrtkei.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.pengpengdd.cyou/Article/details/gt2fruounks.html

C#:   async Task F() { await G(); }
来源：http://dali.hywenlv.cn/Article/details/gt2lrrmjpxw.html

[O05] 并发执行并等待全部完成
来源：http://dali.cashguo.top/Article/details/gt2hgwmmtkb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xuanzx.com/Article/details/gt2eipzpuun.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gogol.net.cn/Article/details/gt2ihckbvqx.html

JS:   await Promise.all(tasks)
来源：http://dali.sufxvd.cn/Article/details/gt2lhlkbrzj.html

TS:   await Promise.all(tasks)
来源：http://dali.zycfv.cn/Article/details/gt2liilgctw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.smart0.xyz/Article/details/gt2vvdhburb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yanxiufei.cn/Article/details/gt2sccaageu.html

Ruby: threads.map(&:join)
来源：http://dali.yueranfly.top/Article/details/gt2ogfgkqfl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj202588.top/Article/details/gt2tfxuqkwf.html

[O06] 使用进程池
来源：http://dali.shangyingyoupin.top/Article/details/gt2lxngduwm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tianlin.xyz/Article/details/gt2daqrrpam.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ehwqpu.com/Article/details/gt2tmdcbsqk.html

JS:   // child_process / cluster 模块
来源：http://dali.jinqigufen.top/Article/details/gt2jccxwvdb.html

TS:   // child_process / cluster 模块
来源：http://dali.feifeiyinyue.top/Article/details/gt2svtwvogg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yvedp.cn/Article/details/gt2jnozpfnc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.pycfn.com/Article/details/gt2vbnmwrxt.html

Ruby: // fork 块
来源：http://dali.0kj1m.cn/Article/details/gt2kjuvxedc.html

C#:   Parallel.For
来源：http://dali.yonumen.top/Article/details/gt2oojosjch.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2zakenqby.html

P. 常用工具函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2hefimndp.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2bqxxrdpg.html

[P01] 生成 UUID
来源：http://dali.dashuyun.cn/Article/details/gt2pxvxeyhd.html

Py:   str(uuid.uuid4())
来源：http://dali.guowangkeji.top/Article/details/gt2vddsiqwj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nwbrower.top/Article/details/gt2wdeiyjig.html

JS:   crypto.randomUUID()
来源：http://dali.hongshengwenyu.top/Article/details/gt2hwkfldnx.html

TS:   crypto.randomUUID()
来源：http://dali.tianlin.xyz/Article/details/gt2ccphyofn.html

Java: UUID.randomUUID().toString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2qjbnrubq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinqigufen.top/Article/details/gt2lizzkfpq.html

Ruby: SecureRandom.uuid
来源：http://dali.jqgufenzy.top/Article/details/gt2fuumvsrm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.andypj.xyz/Article/details/gt2wiixhsnv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhongyouzk.top/Article/details/gt2lbxvfhca.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nwbrower.top/Article/details/gt2uofwzdzg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yangfankeji.com/Article/details/gt2kfajawss.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sxryk.cn/Article/details/gt2pjtzjnca.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.316326.xyz/Article/details/gt2eijdxzwy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hysaishi.cn/Article/details/gt2vjxrwnhp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hfpthk.cn/Article/details/gt2qitbfisg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cheryme.top/Article/details/gt2yrvjlhlw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinqigfzy.top/Article/details/gt2zgswundb.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxajdmt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.pycfn.com/Article/details/gt2idhoedbi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sxryk.cn/Article/details/gt2jhzfcitf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gt2erxqkokj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bfuragec.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hnxiangtu.top/Article/details/gt2tgtgjmmb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.meibo888.top/Article/details/gt2dnmoakez.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.haohaochexian.top/Article/details/gt2rmzdwaoz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.daria6918.cn/Article/details/gt2zerzuawg.html

[P04] 求长度
来源：http://dali.jyoumei.cn/Article/details/gt2gdiezvih.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gaohongyu789.top/Article/details/gt2igtkknbx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gt2nxmusvpc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gt2grjnzsav.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuanzhike.top/Article/details/gt2slvcxtxu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ydtdngbj.html

Go:   len(arr);  len(m)
来源：http://dali.jlsjyb.cn/Article/details/gt2flepafdy.html

Ruby: x.length;  x.size
来源：http://dali.mhx1999.top/Article/details/gt2abwfdpqa.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jlsjyb.cn/Article/details/gt2adfsnspj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.bjfxy.top/Article/details/gt2apolzrmg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.aizwys.cn/Article/details/gt2haeeeypf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.quarkkingdee.top/Article/details/gt2bfpdvdxx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.dianchejie.cn/Article/details/gt2fvhykiva.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.andypj.xyz/Article/details/gt2zfuttdsj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yyeidfwu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.svipenyu.cn/Article/details/gt2tmbyleaa.html

Ruby: a == b
来源：http://dali.zhixingplan.top/Article/details/gt2ubpyocvp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2gohbtgeh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.svipenyu.cn/Article/details/gt2qafsvfsw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ibowpzym.html

PHP:  if (empty($x)) {}
来源：http://dali.dashuyun.cn/Article/details/gt2bmqqbxxr.html


<!-- 参考信息 -->