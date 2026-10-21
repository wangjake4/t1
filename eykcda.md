代发 wailian999

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtusoqkekc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gtltnwgmfv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.chenlongwang.top/Article/details/gtyzbkhlyg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.fzhhl.top/Article/details/gtgfgnrjdv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sweek.top/Article/details/gtcsvehllk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.andypj.xyz/Article/details/gtvllhjuse.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtfwixgqel.html

M. 命令行 / 进程 / 环境
来源：http://dali.nwbrower.top/Article/details/gttqhjyouf.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtiihsbjud.html

[M01] 读取命令行参数
来源：http://dali.nanxuanxn.top/Article/details/gtdkfisjrk.html

Py:   sys.argv[1:]
来源：http://dali.redwolf501.top/Article/details/gtuqxbgbfv.html

PHP:  $argv;  $argc;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnpgmzecr.html

JS:   process.argv.slice(2)
来源：http://dali.aizwys.cn/Article/details/gtxlswhdku.html

TS:   process.argv.slice(2)
来源：http://dali.pycfn.com/Article/details/gtuanakpfz.html

Java: args 数组（main 方法参数）
来源：http://dali.guowangkeji.top/Article/details/gtkwnaiwcp.html

Go:   os.Args[1:]
来源：http://dali.jyoumei.cn/Article/details/gtdrfooana.html

Ruby: ARGV
来源：http://dali.yvedp.cn/Article/details/gtohdofzln.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gtizappkge.html

[M02] 读取环境变量
来源：http://dali.hfpthk.cn/Article/details/gtmwatjyus.html

Py:   os.environ.get("HOME")
来源：http://dali.wangdashe.top/Article/details/gtkjsxvhlq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hammf.cn/Article/details/gticnkrdpz.html

JS:   process.env.HOME
来源：http://dali.c1oappe.top/Article/details/gtclaslexx.html

TS:   process.env.HOME
来源：http://dali.hongshengwenyu.top/Article/details/gtltfuuezr.html

Java: System.getenv("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtzqowdciz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gzhubu.top/Article/details/gtxymraobv.html

Ruby: ENV["HOME"]
来源：http://dali.ivvv.top/Article/details/gtfxwrqqcj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ydzc1.top/Article/details/gtelqanqlu.html

[M03] 执行外部命令
来源：http://dali.nanxuanxn.top/Article/details/gtjybqsxhq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj20258888.top/Article/details/gtbrlsncig.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yuanzhike.top/Article/details/gthzuonspx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.quarkkingdee.top/Article/details/gtlkzydbxq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.quarkkingdee.top/Article/details/gtqoaclwwa.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jlsjyb.cn/Article/details/gtzkvwumcd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tianlin.xyz/Article/details/gtusxmnmgj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ydzc1.top/Article/details/gtffevmwjl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj202588.top/Article/details/gtokybxnbu.html

[M04] 获取当前工作目录
来源：http://dali.ybcxt.top/Article/details/gtgdmclzqp.html

Py:   os.getcwd()
来源：http://dali.hysaishi.cn/Article/details/gtexmrqiqi.html

PHP:  getcwd();
来源：http://dali.cheryme.top/Article/details/gtelvzpkzh.html

JS:   process.cwd()
来源：http://dali.daria6918.cn/Article/details/gtyguxprcj.html

TS:   process.cwd()
来源：http://dali.ehwqpu.com/Article/details/gtaniikcbg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhiwuduotai.top/Article/details/gtsppbzwzj.html

Go:   os.Getwd()
来源：http://dali.dashuyun.cn/Article/details/gttkacchkw.html

Ruby: Dir.pwd
来源：http://dali.jianghu66.top/Article/details/gtapkmrrgq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jiagoushi.top/Article/details/gtsrjecnkt.html

[M05] 设置退出码
来源：http://dali.c1oappe.top/Article/details/gtlbazeqak.html

Py:   sys.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtmuqktqzv.html

PHP:  exit(1);
来源：http://dali.aizwys.cn/Article/details/gtmhjgzwsk.html

JS:   process.exit(1)
来源：http://dali.ybcxt.top/Article/details/gthbzesykt.html

TS:   process.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtmsexnsad.html

Java: System.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtkjdpgqnf.html

Go:   os.Exit(1)
来源：http://dali.mhx1999.top/Article/details/gtkqjytkfr.html

Ruby: exit 1
来源：http://dali.sweek.top/Article/details/gtxdbirzvs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.kuanghao11.cn/Article/details/gtbgwarcor.html

[M06] 向标准错误输出
来源：http://dali.hnxiangtu.top/Article/details/gtulrcyqlk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuanzhike.top/Article/details/gtxgtrhgcm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aizwys.cn/Article/details/gtijjzmgrp.html

JS:   console.error("err")
来源：http://dali.tian-w.cn/Article/details/gtdtweknib.html

TS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gtbilrwlfh.html

Java: System.err.println("err")
来源：http://dali.cashguo.top/Article/details/gtbmduncen.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhiwuduotai.top/Article/details/gthhmtkoob.html

Ruby: warn "err"
来源：http://dali.guannengcc.top/Article/details/gtfrruhfmn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xziqi.cn/Article/details/gtenalekxk.html

[M07] 判断是否为主入口
来源：http://dali.zycfv.cn/Article/details/gtnamevsvu.html

Py:   if __name__ == "__main__":
来源：http://dali.ivvv.top/Article/details/gtljwprlfn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinqigufen.top/Article/details/gtstodsmba.html

JS:   require.main === module
来源：http://dali.shzxlz.cn/Article/details/gtziwdnjrq.html

TS:   require.main === module
来源：http://dali.zhengqikj.top/Article/details/gtcxdfxhyw.html

Java: public static void main(String[] args)
来源：http://dali.zycfv.cn/Article/details/gtmporeolg.html

Go:   func main()
来源：http://dali.mhx1999.top/Article/details/gtvpaclndl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sufxvd.cn/Article/details/gtyvukdahk.html

C#:   static void Main(string[] args)
来源：http://dali.nanxinkj.top/Article/details/gtgnqtkydc.html

[M08] 获取系统与运行时信息
来源：http://dali.haohaochexian.top/Article/details/gtsaxwsgrk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yvedp.cn/Article/details/gtjjgjiimy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinqigufen.top/Article/details/gtzcpmsrcb.html

JS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gtvjhsbpge.html

TS:   process.platform;  process.version
来源：http://dali.jqgfzy.top/Article/details/gtwnbrbdtb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.svipenyu.cn/Article/details/gtkxmzncxv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.vqdsnc.cn/Article/details/gtsawutasl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhoulong.xyz/Article/details/gtkjojltlw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjkfxdbky.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtvejvvflt.html

N. 数据结构与算法
来源：http://dali.daria6918.cn/Article/details/gtmpnviypk.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtvnurprjs.html

[N01] 二分查找（有序数组）
来源：http://dali.shanyushiyangtech.top/Article/details/gtcswadwmf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtpmkryzpy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.daria6918.cn/Article/details/gtqjqnpzra.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gtjmddpykx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtbvsovzwl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtrzqvnwbt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtvrbpczxl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.guannengcc.top/Article/details/gtaytajtjb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtzwlwamuy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.daxiang520.top/Article/details/gtldiifkek.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sysykeji.top/Article/details/gtbixzvrbz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sysykeji.top/Article/details/gtfzgaagiy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gtuwxjdcbu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnqzz.top/Article/details/gttqbfopgd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xylfe.cn/Article/details/gtfvfednon.html

Go:   slices.Sort(arr)
来源：http://dali.xinyue.icu/Article/details/gtbyfeyjxp.html

Ruby: arr.sort
来源：http://dali.yj20258888.top/Article/details/gtoitzkfpo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuanzx.com/Article/details/gtnkyfresg.html

[N03] 快速排序（分治示例）
来源：http://dali.smart0.xyz/Article/details/gteifrhvgo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jlsjyb.cn/Article/details/gtkiykcnmz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gaohongyu789.top/Article/details/gtsnzsmnbp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinghuilouyu.cn/Article/details/gtqgzbgydv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gtlsfwsuxe.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.andypj.xyz/Article/details/gtnpauxsha.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.vqdsnc.cn/Article/details/gtozyoydnk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.havefunace.top/Article/details/gtjkhnlitt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.kuanghao11.cn/Article/details/gtxtccuxrp.html

[N04] 斐波那契数列
来源：http://dali.cashguo.top/Article/details/gtgevpxbpe.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.snrcjt.cn/Article/details/gtwpjotwme.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsyhhlahx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gthirczknv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gtwfrauyxi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gogol.net.cn/Article/details/gtyubhmbya.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.guannengcc.top/Article/details/gtelsgsbir.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.iojbl.cn/Article/details/gtkeevzxrg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gtbwizrlrz.html

[N05] 最大公约数
来源：http://dali.hnxiangtu.top/Article/details/gttbznqucd.html

Py:   math.gcd(a, b)
来源：http://dali.chenlongwang.top/Article/details/gttkrgcsvf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shuidangran.top/Article/details/gtwzcyvpwn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gtgqgabgqc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenlongwang.top/Article/details/gtxwpfpzrq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sweek.top/Article/details/gtyndzmyyv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yongpay.top/Article/details/gtuskxthra.html

Ruby: a.gcd(b)
来源：http://dali.zhoulong.xyz/Article/details/gtedltuthb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ivvv.top/Article/details/gtnxuuqdke.html

[N06] 判断回文字符串
来源：http://dali.c1oappe.top/Article/details/gtloepshno.html

Py:   s == s[::-1]
来源：http://dali.fengsongda.top/Article/details/gtkezibkrx.html

PHP:  $s === strrev($s);
来源：http://dali.sysykeji.top/Article/details/gtbcrybejm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtqmnqswmh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtokdlcquz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xuanzx.com/Article/details/gttwghsucy.html

Go:   // 双指针从两端比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtarpzuhot.html

Ruby: s == s.reverse
来源：http://dali.0kj1m.cn/Article/details/gthsgbenrx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.svipenyu.cn/Article/details/gtyrsbjwhr.html

[N07] 两数之和（返回下标）
来源：http://dali.yongpay.top/Article/details/gtnedgjbnt.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gtutkahdfi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gotoacloud.top/Article/details/gtrgodtvyy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhixingplan.top/Article/details/gthuzotvzj.html

TS:   // 手写 Map<string, number>
来源：http://dali.gaohongyu789.top/Article/details/gtuwrseiyu.html

Java: // 手写 HashMap
来源：http://dali.tianlin.xyz/Article/details/gteobovyjl.html

Go:   // 手写 map[int]int
来源：http://dali.vqdsnc.cn/Article/details/gtzkyuwoaj.html

Ruby: // 手写 Hash
来源：http://dali.ybcxt.top/Article/details/gthlavnrvl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jianghu66.top/Article/details/gtbdfofzlu.html

[N08] 生成全排列
来源：http://dali.shuidangran.top/Article/details/gtfqlhdfxu.html

Py:   itertools.permutations(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtbfacxkhu.html

PHP:  // 手写递归交换
来源：http://dali.hysaishi.cn/Article/details/gtikxelgzm.html

JS:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gthiwoorhw.html

TS:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtfnyitpid.html

Java: // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtpxwejock.html

Go:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtstuivszh.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gtnqhlbwjk.html

C#:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtlwounpxr.html

[N09] 栈与队列
来源：http://dali.hywenlv.cn/Article/details/gtkwpuujop.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtxbjdorgr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.meibo888.top/Article/details/gtrwazchzl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gtrntllicx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xinyue.icu/Article/details/gtceidxljg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.redwolf501.top/Article/details/gtbnxqrfzm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sufxvd.cn/Article/details/gtbwfguxyo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xuanzx.com/Article/details/gtytkizlvk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinqigufen.top/Article/details/gtepksrgoe.html

[N10] 链表节点定义
来源：http://dali.cashguo.top/Article/details/gtaosmambc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.dianchejie.cn/Article/details/gthmoxbeuy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cheryme.top/Article/details/gtzzdvmtrm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhoulong.xyz/Article/details/gtfjfxojwn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yanxiufei.cn/Article/details/gtbbkiqugc.html

Java: class Node { int v; Node next; }
来源：http://dali.sweek.top/Article/details/gtqwsooain.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.guowangkeji.top/Article/details/gtihnerlch.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinqigufen.top/Article/details/gtfhcprvav.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.9152youxi.cn/Article/details/gtqpzfxuco.html

[N11] 二叉树中序遍历
来源：http://dali.ybcxt.top/Article/details/gtgozmqhyj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hongshengwenyu.top/Article/details/gtmomzmodr.html

PHP:  // 手写递归函数
来源：http://dali.andypj.xyz/Article/details/gtkzfnvato.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xziqi.cn/Article/details/gtttfkjjni.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuxming.cn/Article/details/gtaelgjoab.html

Java: // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gtbytskudp.html

Go:   // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gtsteawfxl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.aizwys.cn/Article/details/gtreifilvl.html

C#:   // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gtvftdzrpq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.iojbl.cn/Article/details/gtmxwdhwca.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hongshengwenyu.top/Article/details/gtyekmhodb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.fzhhl.top/Article/details/gtjdmmjipq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gtslwysnvp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.snrcjt.cn/Article/details/gtwagwhpfw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tian-w.cn/Article/details/gtyjdfgiww.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqricjccb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yanxiufei.cn/Article/details/gtxbkgcxez.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cdnleiting.top/Article/details/gtdfaqftaf.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtcvhouhxb.html

O. 并发与异步
来源：http://dali.yuxming.cn/Article/details/gtlzdzfqjn.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtqygzwmds.html

[O01] 启动一个线程
来源：http://dali.jqgufenzy.top/Article/details/gtssgbsmhv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yueranfly.top/Article/details/gtskoryvtk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.birdmap.top/Article/details/gttrxcmhpk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj20258888.top/Article/details/gtywtgpdmk.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gtbachhpgx.html

Java: new Thread(() -> f()).start()
来源：http://dali.yueranfly.top/Article/details/gtcytoutxw.html

Go:   go f()
来源：http://dali.nanxuanxn.top/Article/details/gtmnkamheo.html

Ruby: Thread.new { f }
来源：http://dali.yonumen.top/Article/details/gttxxbmjdw.html

C#:   Task.Run(() => F());
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpiqhqcet.html

[O02] 使用线程池
来源：http://dali.shzxlz.cn/Article/details/gtoiiffrbf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sufxvd.cn/Article/details/gtewsjfayt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.0kj1m.cn/Article/details/gtibocemzu.html

JS:   // worker_threads 线程池
来源：http://dali.yuxming.cn/Article/details/gtpaqcqcat.html

TS:   // worker_threads 线程池
来源：http://dali.smart0.xyz/Article/details/gtcezaotcx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hnxiangtu.top/Article/details/gtrymlmzcc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbguuumyj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhixingplan.top/Article/details/gtrfbinwer.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xziqi.cn/Article/details/gtveihwiso.html

[O03] 加锁保护共享数据
来源：http://dali.tianlin.xyz/Article/details/gtazhrrlne.html

Py:   with lock: shared += 1
来源：http://dali.sxryk.cn/Article/details/gtnaeehgjc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.kuanghao11.cn/Article/details/gtatwascqa.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cdnleiting.top/Article/details/gtnjneuwav.html

TS:   // 同 JS
来源：http://dali.daria6918.cn/Article/details/gtbpxnzgrg.html

Java: synchronized (this) { shared++; }
来源：http://dali.9152youxi.cn/Article/details/gtazqnvxle.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.dashuyun.cn/Article/details/gtfpmqtbuo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jqgufenzy.top/Article/details/gtektiicom.html

C#:   lock (gate) { shared++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtptbmwuvp.html

[O04] 定义异步函数并等待
来源：http://dali.feifeiyinyue.top/Article/details/gtfaaupqap.html

Py:   async def f():⏎    await g()
来源：http://dali.haohaochexian.top/Article/details/gtezlvbdsz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.snrcjt.cn/Article/details/gtftmqodfq.html

JS:   async function f() { await g(); }
来源：http://dali.shzxlz.cn/Article/details/gteyzgpbzu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gtmjmhggry.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnlsqizwe.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfkiesag.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jianghu66.top/Article/details/gtobdhmbye.html

C#:   async Task F() { await G(); }
来源：http://dali.yongpay.top/Article/details/gtxuebqatl.html

[O05] 并发执行并等待全部完成
来源：http://dali.jianghu66.top/Article/details/gtmmsivwve.html

Py:   asyncio.gather(*tasks)
来源：http://dali.smart0.xyz/Article/details/gtauqptxiu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yonumen.top/Article/details/gtjdxffzvd.html

JS:   await Promise.all(tasks)
来源：http://dali.shuidangran.top/Article/details/gtccwskajy.html

TS:   await Promise.all(tasks)
来源：http://dali.ybcxt.top/Article/details/gtiddmtlqc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.9152youxi.cn/Article/details/gthargdtzn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sweek.top/Article/details/gtcmyxtsbj.html

Ruby: threads.map(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gtvkjaxgkg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhoulong.xyz/Article/details/gtddqbnrxo.html

[O06] 使用进程池
来源：http://dali.gotoacloud.top/Article/details/gtwwfhcltw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yvedp.cn/Article/details/gtrdulixxi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hammf.cn/Article/details/gtgpyncafd.html

JS:   // child_process / cluster 模块
来源：http://dali.gogol.net.cn/Article/details/gtocmdnjfv.html

TS:   // child_process / cluster 模块
来源：http://dali.yj202588.top/Article/details/gtphfcdbkr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.fzhhl.top/Article/details/gtrujyzqxy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.andypj.xyz/Article/details/gtyhrkvvza.html

Ruby: // fork 块
来源：http://dali.yuanzhike.top/Article/details/gttpcyjbnz.html

C#:   Parallel.For
来源：http://dali.yonumen.top/Article/details/gtesmccxml.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtttqjvbnz.html

P. 常用工具函数
来源：http://dali.sufxvd.cn/Article/details/gtsuujtxgp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gttqzvymkv.html

[P01] 生成 UUID
来源：http://dali.yueranfly.top/Article/details/gtiuxrbqrf.html

Py:   str(uuid.uuid4())
来源：http://dali.yvedp.cn/Article/details/gtzzrpkdue.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yueranfly.top/Article/details/gttzitnyvb.html

JS:   crypto.randomUUID()
来源：http://dali.ehwqpu.com/Article/details/gtnacdekfo.html

TS:   crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gtvhnxlwfm.html

Java: UUID.randomUUID().toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtysptqumj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ehwqpu.com/Article/details/gtndmimyfl.html

Ruby: SecureRandom.uuid
来源：http://dali.fzhhl.top/Article/details/gtiqbmwwxd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhengqikj.top/Article/details/gtbhadyopv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yongpay.top/Article/details/gtocggcpmo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nanxuanxn.top/Article/details/gtxgfbkvin.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cqqwz.cn/Article/details/gtcrddvtco.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenlongwang.top/Article/details/gttaxsbpdy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.vqdsnc.cn/Article/details/gtckopuqjc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cqqwz.cn/Article/details/gtgmdgrrmn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.mhx1999.top/Article/details/gtrxppwkis.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cdnleiting.top/Article/details/gtkcvzexlw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj202588.top/Article/details/gturetmcgn.html

[P03] 生成短随机字符串
来源：http://dali.tanke756.top/Article/details/gtuaoszbbd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yuxming.cn/Article/details/gtlerfebyp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zdqjudy.top/Article/details/gtupmkltbh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jianghu66.top/Article/details/gtdhuehoev.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ivvv.top/Article/details/gtiebepiqx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nanxuanxn.top/Article/details/gtyjoiovvo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gtgoixdjoe.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtobcczoth.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gogol.net.cn/Article/details/gtvpdbwpzy.html

[P04] 求长度
来源：http://dali.yj20258.top/Article/details/gthhxfpzvf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.fengsongda.top/Article/details/gtnphnvnlk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gtxcmnjxwb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhongyouzk.top/Article/details/gtgtwkbako.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgufenzy.top/Article/details/gtwchuhara.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xylfe.cn/Article/details/gtildcglat.html

Go:   len(arr);  len(m)
来源：http://dali.yanxiufei.cn/Article/details/gtskailttu.html

Ruby: x.length;  x.size
来源：http://dali.andypj.xyz/Article/details/gtyefvnwqu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.nwbrower.top/Article/details/gtdwuxkuva.html

[P05] 判断两个对象内容是否相等
来源：http://dali.pengpengdd.cyou/Article/details/gtcyzeszmb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sxryk.cn/Article/details/gtkkdmlerf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.daxiang520.top/Article/details/gtmdhxmndh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ivvv.top/Article/details/gtjjkciivo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shzxlz.cn/Article/details/gtdqnagjwb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fengsongda.top/Article/details/gtwxbqubld.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cucudq.cn/Article/details/gtzbanream.html

Ruby: a == b
来源：http://dali.ybcxt.top/Article/details/gtehogxmxl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhixingplan.top/Article/details/gtyyeccllg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sufxvd.cn/Article/details/gtasvplcvy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmywaxbdc.html

PHP:  if (empty($x)) {}
来源：http://dali.xuanzx.com/Article/details/gthzfxtkwx.html


<!-- 参考信息 -->