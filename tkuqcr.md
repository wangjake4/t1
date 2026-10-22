代发 wailian999

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gttnkulhrv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gtzeeigsjy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yongpay.top/Article/details/gtowhtmzhx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shzxlz.cn/Article/details/gtgvopdotb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ivvv.top/Article/details/gtpnqrmkny.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tanke756.top/Article/details/gtclneuxhy.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtvdgsbunn.html

M. 命令行 / 进程 / 环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gtojnrdqzm.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtgstyexwu.html

[M01] 读取命令行参数
来源：http://dali.xziqi.cn/Article/details/gtxwwybcio.html

Py:   sys.argv[1:]
来源：http://dali.gaohongyu789.top/Article/details/gtasqqwybr.html

PHP:  $argv;  $argc;
来源：http://dali.shzxlz.cn/Article/details/gtoqbodvmh.html

JS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gtxqpzthmq.html

TS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gtqslcgzrr.html

Java: args 数组（main 方法参数）
来源：http://dali.zhixingplan.top/Article/details/gtgbkdmlhe.html

Go:   os.Args[1:]
来源：http://dali.mhx1999.top/Article/details/gtstepzogo.html

Ruby: ARGV
来源：http://dali.gogol.net.cn/Article/details/gtfycaswtl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hfpthk.cn/Article/details/gtqjyiutpk.html

[M02] 读取环境变量
来源：http://dali.guowangkeji.top/Article/details/gtutptrbav.html

Py:   os.environ.get("HOME")
来源：http://dali.dashuyun.cn/Article/details/gtdfwgvncb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cashguo.top/Article/details/gtgpeovdnj.html

JS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gtgvigdpxg.html

TS:   process.env.HOME
来源：http://dali.xziqi.cn/Article/details/gtnzaufoby.html

Java: System.getenv("HOME")
来源：http://dali.gzhubu.top/Article/details/gtitgsvcaz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nwbrower.top/Article/details/gtkjvqmbbr.html

Ruby: ENV["HOME"]
来源：http://dali.jinqigfzy.top/Article/details/gtjkurphdw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtjkjuaydi.html

[M03] 执行外部命令
来源：http://dali.mhx1999.top/Article/details/gtghxcwjuf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtexnvlylz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbcadppwn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yonumen.top/Article/details/gtnzdchzgn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ppjwa.cn/Article/details/gtsprbagjx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuanzx.com/Article/details/gtqohoglhe.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yanxiufei.cn/Article/details/gtxrjfkuyk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cqqwz.cn/Article/details/gttbhbkapw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shanyushiyangkeji.top/Article/details/gttilkuway.html

[M04] 获取当前工作目录
来源：http://dali.yj20258.top/Article/details/gtsfcwzreo.html

Py:   os.getcwd()
来源：http://dali.ehwqpu.com/Article/details/gtltbmostf.html

PHP:  getcwd();
来源：http://dali.havefunace.top/Article/details/gtuamggmpt.html

JS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gtbgwiqhms.html

TS:   process.cwd()
来源：http://dali.guannengcc.top/Article/details/gtxzcvnudy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenlongwang.top/Article/details/gtcfrsntyn.html

Go:   os.Getwd()
来源：http://dali.zhixingplan.top/Article/details/gtjrvfylvq.html

Ruby: Dir.pwd
来源：http://dali.xuanzx.com/Article/details/gtqzgvvnfn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hnxiangtu.top/Article/details/gtnnrnsfng.html

[M05] 设置退出码
来源：http://dali.zhoulong.xyz/Article/details/gtjjndopjs.html

Py:   sys.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtqbkvchmm.html

PHP:  exit(1);
来源：http://dali.tanke756.top/Article/details/gtydtbrzkm.html

JS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtgvxttcbz.html

TS:   process.exit(1)
来源：http://dali.yongpay.top/Article/details/gtrcbtpzsb.html

Java: System.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrjmvkkka.html

Go:   os.Exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtxdkwzxqr.html

Ruby: exit 1
来源：http://dali.xuetiantiany.cn/Article/details/gtytkzobwk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.haohaochexian.top/Article/details/gtwxqqmihs.html

[M06] 向标准错误输出
来源：http://dali.vqdsnc.cn/Article/details/gtodoanvoc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.c1oappe.top/Article/details/gthpwrgbyx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.mhx1999.top/Article/details/gtztebcauk.html

JS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gtaxxjqyxa.html

TS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gtkmciqbvo.html

Java: System.err.println("err")
来源：http://dali.zdqjudy.top/Article/details/gteqbgcfqc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhoulong.xyz/Article/details/gtbxzoubgc.html

Ruby: warn "err"
来源：http://dali.guannengcc.top/Article/details/gtnljnkype.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ydzc1.top/Article/details/gtlidpdkkj.html

[M07] 判断是否为主入口
来源：http://dali.zdqjudy.top/Article/details/gtoqxbtxbt.html

Py:   if __name__ == "__main__":
来源：http://dali.bjfxy.top/Article/details/gtwxdtighg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdldlgnnt.html

JS:   require.main === module
来源：http://dali.nwbrower.top/Article/details/gtvbasvrmz.html

TS:   require.main === module
来源：http://dali.yj20258888.top/Article/details/gthzdrfpit.html

Java: public static void main(String[] args)
来源：http://dali.fzhhl.top/Article/details/gtuklqjfjy.html

Go:   func main()
来源：http://dali.shanyushiyangkeji.top/Article/details/gttvkrbxis.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuetiantiany.cn/Article/details/gtnzvhaxwv.html

C#:   static void Main(string[] args)
来源：http://dali.zhoulong.xyz/Article/details/gtcfglnuqj.html

[M08] 获取系统与运行时信息
来源：http://dali.hysaishi.cn/Article/details/gtsqipawrb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.kuanghao11.cn/Article/details/gtnkybataz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hfpthk.cn/Article/details/gtbwdwmijd.html

JS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gtuhjwxhxk.html

TS:   process.platform;  process.version
来源：http://dali.c1oappe.top/Article/details/gtjovcrnvu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jiagoushi.top/Article/details/gtcqtmwepz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jyoumei.cn/Article/details/gtvhydymnf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthymxktlk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aibaodan.cn/Article/details/gtnimohekz.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtbbsodcfb.html

N. 数据结构与算法
来源：http://dali.haohaochexian.top/Article/details/gtjkydajbr.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtngbzncry.html

[N01] 二分查找（有序数组）
来源：http://dali.wangdashe.top/Article/details/gtfclaaofd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtiyfdmlpa.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.c1oappe.top/Article/details/gtwthuubvo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtrzziqazp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.0kj1m.cn/Article/details/gtjjnduwwh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.birdmap.top/Article/details/gtccmvfoue.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtqbuyszxs.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.guowangkeji.top/Article/details/gtvpbxjwnj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtujytprky.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hfpthk.cn/Article/details/gtnpciowmf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigufen.top/Article/details/gtzfeoaxpu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.c1oappe.top/Article/details/gtwoeulgxs.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhengqikj.top/Article/details/gtavvejapk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tianlin.xyz/Article/details/gtxjexgwpe.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nwbrower.top/Article/details/gtzsghlsoh.html

Go:   slices.Sort(arr)
来源：http://dali.chenlongwang.top/Article/details/gtlestxxue.html

Ruby: arr.sort
来源：http://dali.hammf.cn/Article/details/gtrptkceoh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ivvv.top/Article/details/gtsudyhyil.html

[N03] 快速排序（分治示例）
来源：http://dali.chenjidiqi.icu/Article/details/gtvsmyvocn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jqgufenzy.top/Article/details/gtickdfigu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnjefkpw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dianchejie.cn/Article/details/gtxredfzyj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.snrcjt.cn/Article/details/gtrycwxvcu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jiagoushi.top/Article/details/gtzwzpglbf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jianghu66.top/Article/details/gtjxdyluzn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.andypj.xyz/Article/details/gtfjthlyxl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtapdrqgcq.html

[N04] 斐波那契数列
来源：http://dali.nanxinkj.top/Article/details/gtlugocbah.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqazufyvh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.svipenyu.cn/Article/details/gthutbllkz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gtcovcnref.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gtxoakenap.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cashguo.top/Article/details/gtwbzdqaub.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gotoacloud.top/Article/details/gtlrpckgab.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jiagoushi.top/Article/details/gtjitybelu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gtrjmrwrxu.html

[N05] 最大公约数
来源：http://dali.tianlin.xyz/Article/details/gtpkhqtqlk.html

Py:   math.gcd(a, b)
来源：http://dali.daxiang520.top/Article/details/gtocykqmzz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenlongwang.top/Article/details/gtwhxmnobx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258888.top/Article/details/gtffmwlpzk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhixingplan.top/Article/details/gtxigswnmg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhengqikj.top/Article/details/gtukrgmqke.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tianlin.xyz/Article/details/gtozqbydce.html

Ruby: a.gcd(b)
来源：http://dali.yvedp.cn/Article/details/gtbfhqdxlq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.quarkkingdee.top/Article/details/gtjnyedggg.html

[N06] 判断回文字符串
来源：http://dali.zhixingplan.top/Article/details/gtjbcxttns.html

Py:   s == s[::-1]
来源：http://dali.yanxiufei.cn/Article/details/gtffwyqxto.html

PHP:  $s === strrev($s);
来源：http://dali.0kj1m.cn/Article/details/gtewaktjxu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtvtgaosmg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpufivzop.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvrijchmy.html

Go:   // 双指针从两端比较
来源：http://dali.xziqi.cn/Article/details/gtbsjqjjiw.html

Ruby: s == s.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gthwnqptnb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xuanzx.com/Article/details/gtkhgxrzxz.html

[N07] 两数之和（返回下标）
来源：http://dali.wangshuangyany.cn/Article/details/gtrzrwlpfw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenjidiqi.icu/Article/details/gtfgagypfs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gtzhgfztcr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinqigfzy.top/Article/details/gttlatdxal.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj202588.top/Article/details/gtjzgxzytf.html

Java: // 手写 HashMap
来源：http://dali.gaohongyu789.top/Article/details/gtjsxfdbte.html

Go:   // 手写 map[int]int
来源：http://dali.birdmap.top/Article/details/gtfhwfovxp.html

Ruby: // 手写 Hash
来源：http://dali.hfpthk.cn/Article/details/gttrzuygtf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sxryk.cn/Article/details/gtokgydvbo.html

[N08] 生成全排列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuhlyojyq.html

Py:   itertools.permutations(arr)
来源：http://dali.ydzc1.top/Article/details/gtaxsupmcv.html

PHP:  // 手写递归交换
来源：http://dali.chenlongwang.top/Article/details/gtrtgzjkgw.html

JS:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtysgxkdpw.html

TS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtlyzsmjju.html

Java: // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtnomzvmzx.html

Go:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtvzqkdxex.html

Ruby: arr.permutation.to_a
来源：http://dali.yonumen.top/Article/details/gtbalrtbkb.html

C#:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtljmmcoyd.html

[N09] 栈与队列
来源：http://dali.jlsjyb.cn/Article/details/gtpiqjhkvh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtflexeciw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nwbrower.top/Article/details/gtdlpczvsh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sysykeji.top/Article/details/gtcuzynccf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gaohongyu789.top/Article/details/gtisthmpqm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxheeoyzr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.c1oappe.top/Article/details/gtyxemldvm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gtganesxrs.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfyspccsr.html

[N10] 链表节点定义
来源：http://dali.kuanghao11.cn/Article/details/gtilhhqbjn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ivvv.top/Article/details/gtslplfeqq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yongpay.top/Article/details/gtjgirgulu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.daria6918.cn/Article/details/gttxjqgfvj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tanke756.top/Article/details/gtofumommu.html

Java: class Node { int v; Node next; }
来源：http://dali.nwbrower.top/Article/details/gtcpxvzcwm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tanke756.top/Article/details/gtlgnjteuh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhongyouzk.top/Article/details/gtpvuqvvcd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zdqjudy.top/Article/details/gtupgfdmel.html

[N11] 二叉树中序遍历
来源：http://dali.yueranfly.top/Article/details/gtbgajluae.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.tianlin.xyz/Article/details/gtbvgvpugm.html

PHP:  // 手写递归函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlqchhdps.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinghuilouyu.cn/Article/details/gtbgnycqdp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jlsjyb.cn/Article/details/gtcfmggwsd.html

Java: // 手写递归
来源：http://dali.ivvv.top/Article/details/gtqgdshfis.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gtrwbtluya.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hnxiangtu.top/Article/details/gtjewvxztn.html

C#:   // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gtybnbbbjt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cucudq.cn/Article/details/gtkqnnpaot.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhoulong.xyz/Article/details/gtmtjovtwt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenjidiqi.icu/Article/details/gthbxzhvis.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.316326.xyz/Article/details/gtnrrvfgwl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guannengcc.top/Article/details/gthkuuaasr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nwbrower.top/Article/details/gtlmbxyqki.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sufxvd.cn/Article/details/gtnyttfuio.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuxming.cn/Article/details/gtngcmeufy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tianlin.xyz/Article/details/gtzzopzwip.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtzulttoad.html

O. 并发与异步
来源：http://dali.aibaodan.cn/Article/details/gtxmxkyjxo.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtxtfnjxzw.html

[O01] 启动一个线程
来源：http://dali.fzhhl.top/Article/details/gtdqpnporu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sysykeji.top/Article/details/gthqhufslq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj20258888.top/Article/details/gtdtmujtnx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.redwolf501.top/Article/details/gtuclsvcix.html

TS:   // 同 JS
来源：http://dali.yonumen.top/Article/details/gtvjdhpohq.html

Java: new Thread(() -> f()).start()
来源：http://dali.sufxvd.cn/Article/details/gtfkanfapm.html

Go:   go f()
来源：http://dali.jlsjyb.cn/Article/details/gteitavhhd.html

Ruby: Thread.new { f }
来源：http://dali.hysaishi.cn/Article/details/gtqewrllcd.html

C#:   Task.Run(() => F());
来源：http://dali.nanxuanxn.top/Article/details/gtpriajsfm.html

[O02] 使用线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gthwsiyggq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jqgufenzy.top/Article/details/gtmsvjdulc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenlongwang.top/Article/details/gtnsojyuff.html

JS:   // worker_threads 线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtxckdrqpr.html

TS:   // worker_threads 线程池
来源：http://dali.shangyingyoupin.top/Article/details/gtjrmyoojj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jianghu66.top/Article/details/gtuhiwjsyo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.haohaochexian.top/Article/details/gtnqvmlvaz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.smart0.xyz/Article/details/gtqckcbjyc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ybcxt.top/Article/details/gtipsrbgiw.html

[O03] 加锁保护共享数据
来源：http://dali.gaohongyu789.top/Article/details/gtmpkkvrcu.html

Py:   with lock: shared += 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzpwlipoc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sufxvd.cn/Article/details/gtoocbrsjv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmklzbcrb.html

TS:   // 同 JS
来源：http://dali.yj20258888.top/Article/details/gtzdoclavh.html

Java: synchronized (this) { shared++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtteblixjr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ppjwa.cn/Article/details/gtycaxadrq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sysykeji.top/Article/details/gtvitsefvv.html

C#:   lock (gate) { shared++; }
来源：http://dali.ybcxt.top/Article/details/gthmdvbdbc.html

[O04] 定义异步函数并等待
来源：http://dali.shuidangran.top/Article/details/gtjmvdehkf.html

Py:   async def f():⏎    await g()
来源：http://dali.daria6918.cn/Article/details/gttglcacvs.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xuetiantiany.cn/Article/details/gtxxspkxim.html

JS:   async function f() { await g(); }
来源：http://dali.zhixingplan.top/Article/details/gtrddtfuxx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cucudq.cn/Article/details/gtynfpwzft.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj20258888.top/Article/details/gtfsdxhzec.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnxtpnuid.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xinyue.icu/Article/details/gtewjuvpcu.html

C#:   async Task F() { await G(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gthgyfyeec.html

[O05] 并发执行并等待全部完成
来源：http://dali.haohaochexian.top/Article/details/gtvjkczrqu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.fengsongda.top/Article/details/gtaaabzgqs.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yangfankeji.com/Article/details/gtdqjiorcw.html

JS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gtrnboqcql.html

TS:   await Promise.all(tasks)
来源：http://dali.yj20258888.top/Article/details/gtiaekbxcs.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.mhx1999.top/Article/details/gtdfsllclt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gzhubu.top/Article/details/gtfuxmuwot.html

Ruby: threads.map(&:join)
来源：http://dali.yj20258888.top/Article/details/gtjkrbbjuw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.snrcjt.cn/Article/details/gtpcqaarqo.html

[O06] 使用进程池
来源：http://dali.vqdsnc.cn/Article/details/gtwfckniij.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shzxlz.cn/Article/details/gtwomhphkd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenlongwang.top/Article/details/gtwkgitpiw.html

JS:   // child_process / cluster 模块
来源：http://dali.pengpengdd.cyou/Article/details/gtqcpqrprq.html

TS:   // child_process / cluster 模块
来源：http://dali.pycfn.com/Article/details/gtftqhsbmg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shuidangran.top/Article/details/gtlpvmecmr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.havefunace.top/Article/details/gtlpnrvchh.html

Ruby: // fork 块
来源：http://dali.sufxvd.cn/Article/details/gtomwmhotc.html

C#:   Parallel.For
来源：http://dali.xziqi.cn/Article/details/gtblvsmjbf.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtoiaqtmig.html

P. 常用工具函数
来源：http://dali.hnqzz.top/Article/details/gtgsudjkpv.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtdebkvavr.html

[P01] 生成 UUID
来源：http://dali.feifeiyinyue.top/Article/details/gtkmjuzgzi.html

Py:   str(uuid.uuid4())
来源：http://dali.yuxming.cn/Article/details/gtqtaegvkq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cqqwz.cn/Article/details/gtlezdswcq.html

JS:   crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gtccouegaa.html

TS:   crypto.randomUUID()
来源：http://dali.sweek.top/Article/details/gtaxsgchem.html

Java: UUID.randomUUID().toString()
来源：http://dali.feifeiyinyue.top/Article/details/gthqdhxltu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ydzc1.top/Article/details/gtkelxtlep.html

Ruby: SecureRandom.uuid
来源：http://dali.c1oappe.top/Article/details/gtlyiyswns.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.haohaochexian.top/Article/details/gtrkabttxl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtryuvzw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.9152youxi.cn/Article/details/gtrjltnjwt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yuanzhike.top/Article/details/gthetiyqih.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jqgufenzy.top/Article/details/gtokicesre.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.wangshuangyany.cn/Article/details/gtzkqwoeza.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtchpifump.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.aibaodan.cn/Article/details/gtpmkapmmv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jianghu66.top/Article/details/gtuzuhpdyl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.daxiang520.top/Article/details/gtosqbvtmq.html

[P03] 生成短随机字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtyfhtknmz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yuanzhike.top/Article/details/gtlzexfrtl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sweek.top/Article/details/gtrdfknrur.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.c1oappe.top/Article/details/gteljbsmxo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtzxsxpkct.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiejamdrf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gotoacloud.top/Article/details/gtanyyeajt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpsrlvzhw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.nanxuanxn.top/Article/details/gteucemeid.html

[P04] 求长度
来源：http://dali.zhongyouzk.top/Article/details/gtpwxgtceu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nanxuanxn.top/Article/details/gtnperlcja.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtjkzwzepe.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gtdaakthyk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgfzy.top/Article/details/gtdlieozyg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbzuqdyvu.html

Go:   len(arr);  len(m)
来源：http://dali.ybcxt.top/Article/details/gtvxehfjgr.html

Ruby: x.length;  x.size
来源：http://dali.guowangkeji.top/Article/details/gtmzpqogff.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.nanxinkj.top/Article/details/gtgnuvuccm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yuanzhike.top/Article/details/gtacrvtmkj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sxryk.cn/Article/details/gtbvjwsztg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhiwuduotai.top/Article/details/gtlddwpjgn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ehwqpu.com/Article/details/gtspvbqjfw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shuidangran.top/Article/details/gtuprqqruv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sufxvd.cn/Article/details/gtabdhkwwi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj202588.top/Article/details/gtcqiinvhr.html

Ruby: a == b
来源：http://dali.316326.xyz/Article/details/gtuizujnek.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.birdmap.top/Article/details/gtdvuwnwdf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yongpay.top/Article/details/gtofqoslmm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jyoumei.cn/Article/details/gtbezzojpz.html

PHP:  if (empty($x)) {}
来源：http://dali.xinyue.icu/Article/details/gtnovxrvch.html


<!-- 参考信息 -->