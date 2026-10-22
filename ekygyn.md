代发 wailian999

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jqgfzy.top/Article/details/gt2gnbfichz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gnmbprgt.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2ksnilmvp.html

M. 命令行 / 进程 / 环境
来源：http://dali.zdqjudy.top/Article/details/gt2oojynnhk.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2kvpukqdw.html

[M01] 读取命令行参数
来源：http://dali.jyoumei.cn/Article/details/gt2nnjqsaqr.html

Py:   sys.argv[1:]
来源：http://dali.sxryk.cn/Article/details/gt2mxuvupyl.html

PHP:  $argv;  $argc;
来源：http://dali.xuetiantiany.cn/Article/details/gt2pmjhpwtt.html

JS:   process.argv.slice(2)
来源：http://dali.cdnleiting.top/Article/details/gt2cokwkuzt.html

TS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gt2sxwaujdz.html

Java: args 数组（main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gt2vvxvbtft.html

Go:   os.Args[1:]
来源：http://dali.wangdashe.top/Article/details/gt2aewgngfl.html

Ruby: ARGV
来源：http://dali.gogol.net.cn/Article/details/gt2ojbjzhjl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gt2kwqvnhtt.html

[M02] 读取环境变量
来源：http://dali.zhixingplan.top/Article/details/gt2gxvpbbhy.html

Py:   os.environ.get("HOME")
来源：http://dali.xziqi.cn/Article/details/gt2wkdjgfup.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.aizwys.cn/Article/details/gt2zsfcgkua.html

JS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gt2citgtkga.html

TS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gt2wuprdntj.html

Java: System.getenv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gt2vdwllrjw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gt2rqrchyru.html

Ruby: ENV["HOME"]
来源：http://dali.wangshuangyany.cn/Article/details/gt2gsbsadiv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yuxming.cn/Article/details/gt2vjlmdiva.html

[M03] 执行外部命令
来源：http://dali.jinqigufen.top/Article/details/gt2awhmspmp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2drtipqko.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ybcxt.top/Article/details/gt2smrmpblq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gotoacloud.top/Article/details/gt2onvxlwac.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuanzhike.top/Article/details/gt2xudsajwm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sxryk.cn/Article/details/gt2nayzytbx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenlongwang.top/Article/details/gt2ewttlfnj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigufen.top/Article/details/gt2iyyouxae.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vtvjozxx.html

[M04] 获取当前工作目录
来源：http://dali.0kj1m.cn/Article/details/gt2yhheskre.html

Py:   os.getcwd()
来源：http://dali.zhiwuduotai.top/Article/details/gt2shatnpuj.html

PHP:  getcwd();
来源：http://dali.cashguo.top/Article/details/gt2ucpxtrpt.html

JS:   process.cwd()
来源：http://dali.hongshengwenyu.top/Article/details/gt2kabqkphs.html

TS:   process.cwd()
来源：http://dali.hnqzz.top/Article/details/gt2wxrditny.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ppjwa.cn/Article/details/gt2yhcubfls.html

Go:   os.Getwd()
来源：http://dali.xuanzx.com/Article/details/gt2kwllqutn.html

Ruby: Dir.pwd
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zcrkwaeh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.quarkkingdee.top/Article/details/gt2stlvtflv.html

[M05] 设置退出码
来源：http://dali.tian-w.cn/Article/details/gt2usltqdls.html

Py:   sys.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gt2xdnjqnfp.html

PHP:  exit(1);
来源：http://dali.guowangkeji.top/Article/details/gt2nudomcja.html

JS:   process.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2ozcswmaz.html

TS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2dosecltt.html

Java: System.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wztrlszy.html

Go:   os.Exit(1)
来源：http://dali.zycfv.cn/Article/details/gt2wcwyxdiv.html

Ruby: exit 1
来源：http://dali.cucudq.cn/Article/details/gt2zrfeulvv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhoulong.xyz/Article/details/gt2oyqgspgu.html

[M06] 向标准错误输出
来源：http://dali.c1oappe.top/Article/details/gt2hwqezuhs.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ivvv.top/Article/details/gt2cftlusdi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sufxvd.cn/Article/details/gt2lgfsgmwy.html

JS:   console.error("err")
来源：http://dali.sweek.top/Article/details/gt2wfndgmwk.html

TS:   console.error("err")
来源：http://dali.iojbl.cn/Article/details/gt2zdhhhxip.html

Java: System.err.println("err")
来源：http://dali.jiagoushi.top/Article/details/gt2agapgzgc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenjidiqi.icu/Article/details/gt2imjfagxa.html

Ruby: warn "err"
来源：http://dali.yuxming.cn/Article/details/gt2eprxlaed.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.feifeiyinyue.top/Article/details/gt2qnhofgjd.html

[M07] 判断是否为主入口
来源：http://dali.yuxming.cn/Article/details/gt2trirtqjn.html

Py:   if __name__ == "__main__":
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2klwtlydp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shuidangran.top/Article/details/gt2trfklalh.html

JS:   require.main === module
来源：http://dali.jyoumei.cn/Article/details/gt2wubmvrzn.html

TS:   require.main === module
来源：http://dali.shzxlz.cn/Article/details/gt2tjwoainy.html

Java: public static void main(String[] args)
来源：http://dali.guowangkeji.top/Article/details/gt2phastypw.html

Go:   func main()
来源：http://dali.zhiwuduotai.top/Article/details/gt2rawzasxj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.9152youxi.cn/Article/details/gt2oagndqlk.html

C#:   static void Main(string[] args)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lshvaire.html

[M08] 获取系统与运行时信息
来源：http://dali.hnqzz.top/Article/details/gt2iwfdlzuv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhongyouzk.top/Article/details/gt2uzmvgjfe.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gotoacloud.top/Article/details/gt2rjucolaj.html

JS:   process.platform;  process.version
来源：http://dali.shzxlz.cn/Article/details/gt2zjhalmmt.html

TS:   process.platform;  process.version
来源：http://dali.fzhhl.top/Article/details/gt2bunbgwqo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jianghu66.top/Article/details/gt2rjskzxot.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.tian-w.cn/Article/details/gt2ykjhvqrt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.9152youxi.cn/Article/details/gt2fapkubkh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.iojbl.cn/Article/details/gt2kcjuueij.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2vdivdlyh.html

N. 数据结构与算法
来源：http://dali.meibo888.top/Article/details/gt2wlnhcfjh.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2gktwcmkr.html

[N01] 二分查找（有序数组）
来源：http://dali.yangfankeji.com/Article/details/gt2jlfixyhu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangdashe.top/Article/details/gt2jmrcybjk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.daria6918.cn/Article/details/gt2yxbbgjpk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gotoacloud.top/Article/details/gt2zmkdjobt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pycfn.com/Article/details/gt2jlcdapuz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2arqfwbnb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gzhubu.top/Article/details/gt2wlwfhywe.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ehwqpu.com/Article/details/gt2altgghhv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gt2qhnobegt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nanxuanxn.top/Article/details/gt2hhtkgwml.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shzxlz.cn/Article/details/gt2ysaqvzfq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.fengsongda.top/Article/details/gt2jederlsk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yangfankeji.com/Article/details/gt2canjuezc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gt2pvpdqihi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.c1oappe.top/Article/details/gt2dporrhgd.html

Go:   slices.Sort(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2ywhcivdd.html

Ruby: arr.sort
来源：http://dali.wangshuangyany.cn/Article/details/gt2wctzhdng.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xziqi.cn/Article/details/gt2wkgwvpmw.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigufen.top/Article/details/gt2ghtgikgk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xziqi.cn/Article/details/gt2fuxbqbvb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.svipenyu.cn/Article/details/gt2tlyngaem.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shangyingyoupin.top/Article/details/gt2mmtgldrv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cqqwz.cn/Article/details/gt2ddbwvizt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.wangdashe.top/Article/details/gt2fdhasflq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tian-w.cn/Article/details/gt2cwtgwphc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinqigufen.top/Article/details/gt2kuoxfmcp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sysykeji.top/Article/details/gt2rtxnxxrg.html

[N04] 斐波那契数列
来源：http://dali.daxiang520.top/Article/details/gt2lepymfcd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gt2jkyjqwhy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gt2oljyvcbk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gt2vrdzwilg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gt2gmhtbkhf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yangfankeji.com/Article/details/gt2ibhrylax.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ybcxt.top/Article/details/gt2cskuegyo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.dashuyun.cn/Article/details/gt2hryiibvw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2vzxhodoo.html

[N05] 最大公约数
来源：http://dali.xylfe.cn/Article/details/gt2tqvannbk.html

Py:   math.gcd(a, b)
来源：http://dali.xylfe.cn/Article/details/gt2mbsyogil.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xziqi.cn/Article/details/gt2habijxpz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2afxjzcey.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgfzy.top/Article/details/gt2ivbahrxf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yuxming.cn/Article/details/gt2nphmrnxj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cucudq.cn/Article/details/gt2irgvefwh.html

Ruby: a.gcd(b)
来源：http://dali.nwbrower.top/Article/details/gt2zzzymckz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.0kj1m.cn/Article/details/gt2ggxexjqd.html

[N06] 判断回文字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2megiiufj.html

Py:   s == s[::-1]
来源：http://dali.hongshengwenyu.top/Article/details/gt2banuhavb.html

PHP:  $s === strrev($s);
来源：http://dali.nanxinkj.top/Article/details/gt2gpcwgici.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gt2jugservt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gt2ignvfzgi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cheryme.top/Article/details/gt2ivdeyrty.html

Go:   // 双指针从两端比较
来源：http://dali.fengsongda.top/Article/details/gt2mhokknsz.html

Ruby: s == s.reverse
来源：http://dali.aizwys.cn/Article/details/gt2atzqxrjh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2onjyiqth.html

[N07] 两数之和（返回下标）
来源：http://dali.wangshuangyany.cn/Article/details/gt2zhxbpfxu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xylfe.cn/Article/details/gt2uqxoqcox.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jlsjyb.cn/Article/details/gt2izutxkyc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shuidangran.top/Article/details/gt2utdhqlxb.html

TS:   // 手写 Map<string, number>
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ipqhpirg.html

Java: // 手写 HashMap
来源：http://dali.yj20258888.top/Article/details/gt2mlknhabv.html

Go:   // 手写 map[int]int
来源：http://dali.sysykeji.top/Article/details/gt2pgrjdyrw.html

Ruby: // 手写 Hash
来源：http://dali.daria6918.cn/Article/details/gt2opkznxnf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.daxiang520.top/Article/details/gt2vurnozdq.html

[N08] 生成全排列
来源：http://dali.nanxuanxn.top/Article/details/gt2jhcrbysj.html

Py:   itertools.permutations(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2bfvqpskl.html

PHP:  // 手写递归交换
来源：http://dali.zhixingplan.top/Article/details/gt2mbfitmlx.html

JS:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2hasjtoqi.html

TS:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gt2ggnyvbmp.html

Java: // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gt2jeflnyac.html

Go:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gt2yirtvacw.html

Ruby: arr.permutation.to_a
来源：http://dali.yueranfly.top/Article/details/gt2vxtglndn.html

C#:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gt2iqdjlxzt.html

[N09] 栈与队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2naxagvud.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhongyouzk.top/Article/details/gt2wnvshfoe.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pfwoailu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cucudq.cn/Article/details/gt2baxvhbbe.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tianlin.xyz/Article/details/gt2rfoqhsow.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hammf.cn/Article/details/gt2ejgufbqe.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ivvv.top/Article/details/gt2eaoyglnm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jianghu66.top/Article/details/gt2gsqgmtke.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yueranfly.top/Article/details/gt2mdpunklw.html

[N10] 链表节点定义
来源：http://dali.shuidangran.top/Article/details/gt2cwiokktc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhiwuduotai.top/Article/details/gt2qubvtbca.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.daxiang520.top/Article/details/gt2svfuzagx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xylfe.cn/Article/details/gt2axtjukfa.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sufxvd.cn/Article/details/gt2xfijwtrq.html

Java: class Node { int v; Node next; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2daocjgap.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sweek.top/Article/details/gt2zlhwrxyu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hnxiangtu.top/Article/details/gt2afuqytjl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uobnixoi.html

[N11] 二叉树中序遍历
来源：http://dali.zhengqikj.top/Article/details/gt2seurmlet.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.wangdashe.top/Article/details/gt2oacxbigw.html

PHP:  // 手写递归函数
来源：http://dali.gogol.net.cn/Article/details/gt2kjviqydy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258888.top/Article/details/gt2owauufpq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnqzz.top/Article/details/gt2mknqmygv.html

Java: // 手写递归
来源：http://dali.aizwys.cn/Article/details/gt2nqormurh.html

Go:   // 手写递归
来源：http://dali.xuanzx.com/Article/details/gt2diyxiilv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.meibo888.top/Article/details/gt2pbvtvemo.html

C#:   // 手写递归
来源：http://dali.ivvv.top/Article/details/gt2fzpbwqni.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinqigfzy.top/Article/details/gt2ruokpkon.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yueranfly.top/Article/details/gt2aesceugz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gotoacloud.top/Article/details/gt2tnkurnse.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.haohaochexian.top/Article/details/gt2xolmyupy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2loyckbql.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.meibo888.top/Article/details/gt2bvfcfcem.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xylfe.cn/Article/details/gt2lkpmrkeu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhengqikj.top/Article/details/gt2vwklayof.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenjidiqi.icu/Article/details/gt2gzidzcmc.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2akxumqlg.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2djumlply.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2bgxpgkuo.html

[O01] 启动一个线程
来源：http://dali.shangyingyoupin.top/Article/details/gt2xmlogpbm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.fengsongda.top/Article/details/gt2vxzjfdsn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.vqdsnc.cn/Article/details/gt2ygbjjgtb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.pycfn.com/Article/details/gt2gtvefmcw.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gt2ukmuxkvk.html

Java: new Thread(() -> f()).start()
来源：http://dali.nanxinkj.top/Article/details/gt2jurgqsck.html

Go:   go f()
来源：http://dali.iojbl.cn/Article/details/gt2kycyymjn.html

Ruby: Thread.new { f }
来源：http://dali.meibo888.top/Article/details/gt2dgkohqhn.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258888.top/Article/details/gt2ausocyhb.html

[O02] 使用线程池
来源：http://dali.wangshuangyany.cn/Article/details/gt2mnkdcyed.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.daria6918.cn/Article/details/gt2komeqoky.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.meibo888.top/Article/details/gt2qwvhwwio.html

JS:   // worker_threads 线程池
来源：http://dali.yongpay.top/Article/details/gt2ohdjvygb.html

TS:   // worker_threads 线程池
来源：http://dali.shuidangran.top/Article/details/gt2cqhwqrav.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhixingplan.top/Article/details/gt2dangpcui.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shzxlz.cn/Article/details/gt2mamnrevk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cdnleiting.top/Article/details/gt2zitgtfpu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jqgfzy.top/Article/details/gt2kbvvufkk.html

[O03] 加锁保护共享数据
来源：http://dali.mhx1999.top/Article/details/gt2nobwatij.html

Py:   with lock: shared += 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ngyactto.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cheryme.top/Article/details/gt2uukkirix.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xylfe.cn/Article/details/gt2zmadgttc.html

TS:   // 同 JS
来源：http://dali.pengpengdd.cyou/Article/details/gt2mxtvmtub.html

Java: synchronized (this) { shared++; }
来源：http://dali.hnxiangtu.top/Article/details/gt2hlssrgcq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hongshengwenyu.top/Article/details/gt2cvsbhikv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.dianchejie.cn/Article/details/gt2euxieimr.html

C#:   lock (gate) { shared++; }
来源：http://dali.aibaodan.cn/Article/details/gt2bystkgan.html

[O04] 定义异步函数并等待
来源：http://dali.guowangkeji.top/Article/details/gt2olukhdfp.html

Py:   async def f():⏎    await g()
来源：http://dali.xziqi.cn/Article/details/gt2wxxowpwr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gogol.net.cn/Article/details/gt2miqctlrk.html

JS:   async function f() { await g(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2sugdxpko.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2ubqoqygy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hammf.cn/Article/details/gt2qzsmdoqc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj20258.top/Article/details/gt2pqdqlxwc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yj20258888.top/Article/details/gt2kmiimkjc.html

C#:   async Task F() { await G(); }
来源：http://dali.9152youxi.cn/Article/details/gt2leohhuga.html

[O05] 并发执行并等待全部完成
来源：http://dali.yueranfly.top/Article/details/gt2wfacskdj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hysaishi.cn/Article/details/gt2msooduhh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.daria6918.cn/Article/details/gt2gygxaqxc.html

JS:   await Promise.all(tasks)
来源：http://dali.haohaochexian.top/Article/details/gt2mgdczyuo.html

TS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gt2bmgevevg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hongshengwenyu.top/Article/details/gt2wiaqqklk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ydzc1.top/Article/details/gt2nkewqiav.html

Ruby: threads.map(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wouldpun.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.birdmap.top/Article/details/gt2aeuvmwiv.html

[O06] 使用进程池
来源：http://dali.snrcjt.cn/Article/details/gt2rtilgqxh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenzaomai.com/Article/details/gt2blonsceq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hnqzz.top/Article/details/gt2gdxnncgt.html

JS:   // child_process / cluster 模块
来源：http://dali.pengpengdd.cyou/Article/details/gt2gpchhiew.html

TS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gt2zwjulfnt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuanzhike.top/Article/details/gt2johtyxty.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvlijtp.html

Ruby: // fork 块
来源：http://dali.wangdashe.top/Article/details/gt2xpshosik.html

C#:   Parallel.For
来源：http://dali.yuanzhike.top/Article/details/gt2psatqtsc.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2jrvimibm.html

P. 常用工具函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oxfavawu.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2xlfgkbdl.html

[P01] 生成 UUID
来源：http://dali.xylfe.cn/Article/details/gt2dlhlaobd.html

Py:   str(uuid.uuid4())
来源：http://dali.guowangkeji.top/Article/details/gt2nkimujkz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xremlggq.html

JS:   crypto.randomUUID()
来源：http://dali.cdnleiting.top/Article/details/gt2mdiarmzx.html

TS:   crypto.randomUUID()
来源：http://dali.jiagoushi.top/Article/details/gt2gvwoaydm.html

Java: UUID.randomUUID().toString()
来源：http://dali.cqqwz.cn/Article/details/gt2gzqntedp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yongpay.top/Article/details/gt2fljrytlz.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigufen.top/Article/details/gt2fqywhpxr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xuanzx.com/Article/details/gt2obvwkguu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.redwolf501.top/Article/details/gt2jailfprf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigufen.top/Article/details/gt2yhwfrhiw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yangfankeji.com/Article/details/gt2kzuhnqtj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.iojbl.cn/Article/details/gt2nffqxvpb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinqigfzy.top/Article/details/gt2kiboabow.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hywenlv.cn/Article/details/gt2evlonlgu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xziqi.cn/Article/details/gt2mynbjtbr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.316326.xyz/Article/details/gt2aeluahbm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.meibo888.top/Article/details/gt2oiptghqn.html

[P03] 生成短随机字符串
来源：http://dali.dashuyun.cn/Article/details/gt2fmryzssa.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jianghu66.top/Article/details/gt2awwoqiwo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.vqdsnc.cn/Article/details/gt2dpqkawqs.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.quarkkingdee.top/Article/details/gt2xeuhwlek.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guannengcc.top/Article/details/gt2pxydyule.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.fzhhl.top/Article/details/gt2njwxgctr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xylfe.cn/Article/details/gt2nyxlqhcv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.iojbl.cn/Article/details/gt2gzdsvjgj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cheryme.top/Article/details/gt2fhferzeq.html

[P04] 求长度
来源：http://dali.nwbrower.top/Article/details/gt2lsrghouj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.svipenyu.cn/Article/details/gt2hsyzipyy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gt2vyvjgbqq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jlsjyb.cn/Article/details/gt2httuuxgt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gt2biuvhhkq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinqigfzy.top/Article/details/gt2tmxqhshp.html

Go:   len(arr);  len(m)
来源：http://dali.daxiang520.top/Article/details/gt2xaianecp.html

Ruby: x.length;  x.size
来源：http://dali.guannengcc.top/Article/details/gt2febrakdt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.fengsongda.top/Article/details/gt2hwvyyyza.html

[P05] 判断两个对象内容是否相等
来源：http://dali.feifeiyinyue.top/Article/details/gt2pzthlhbm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cheryme.top/Article/details/gt2aujhciqv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.pycfn.com/Article/details/gt2ohfgwvxt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yvedp.cn/Article/details/gt2nmwfiqai.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.quarkkingdee.top/Article/details/gt2oplbmrpj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hnqzz.top/Article/details/gt2sbmrrpyr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ybcxt.top/Article/details/gt2dhtgxncy.html

Ruby: a == b
来源：http://dali.nanxinkj.top/Article/details/gt2vrsulghe.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ybcxt.top/Article/details/gt2fzoruniw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ehwqpu.com/Article/details/gt2owgdexad.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shzxlz.cn/Article/details/gt2uqoavmfn.html

PHP:  if (empty($x)) {}
来源：http://dali.cdnleiting.top/Article/details/gt2tdkcxsiq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hnxiangtu.top/Article/details/gt2mwkoarru.html

TS:   if (x == null) {}
来源：http://dali.zdqjudy.top/Article/details/gt2gbvzdvff.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.andypj.xyz/Article/details/gt2uomyzfvw.html

Go:   if x == nil {}
来源：http://dali.tian-w.cn/Article/details/gt2nmbpedzh.html


<!-- 参考信息 -->