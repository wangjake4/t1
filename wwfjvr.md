代发 wailian999

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ureffksb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinqigfzy.top/Article/details/gt2rsafekqk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.andypj.xyz/Article/details/gt2bvsdtxfu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zycfv.cn/Article/details/gt2adsudwfv.html

[M04] 获取当前工作目录
来源：http://dali.yuanzhike.top/Article/details/gt2lufuzogj.html

Py:   os.getcwd()
来源：http://dali.haohaochexian.top/Article/details/gt2hydzytzc.html

PHP:  getcwd();
来源：http://dali.jinqigufen.top/Article/details/gt2fumfgwqe.html

JS:   process.cwd()
来源：http://dali.feifeiyinyue.top/Article/details/gt2yhersxda.html

TS:   process.cwd()
来源：http://dali.yueranfly.top/Article/details/gt2ckfhnxng.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sysykeji.top/Article/details/gt2olmzgtqs.html

Go:   os.Getwd()
来源：http://dali.guannengcc.top/Article/details/gt2heqfwqvi.html

Ruby: Dir.pwd
来源：http://dali.316326.xyz/Article/details/gt2kvmknedh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sweek.top/Article/details/gt2bhxsjhvb.html

[M05] 设置退出码
来源：http://dali.yueranfly.top/Article/details/gt2xmxamcdq.html

Py:   sys.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2xyafrrri.html

PHP:  exit(1);
来源：http://dali.pengpengdd.cyou/Article/details/gt2dorqvufs.html

JS:   process.exit(1)
来源：http://dali.yvedp.cn/Article/details/gt2ptwnsnrf.html

TS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gt2vpapxbqq.html

Java: System.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2sojovtxe.html

Go:   os.Exit(1)
来源：http://dali.jianghu66.top/Article/details/gt2betpmiyy.html

Ruby: exit 1
来源：http://dali.fzhhl.top/Article/details/gt2zuscrdyr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgfzy.top/Article/details/gt2gykczeaq.html

[M06] 向标准错误输出
来源：http://dali.yanxiufei.cn/Article/details/gt2zzzzbwmw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.dashuyun.cn/Article/details/gt2urvzshhf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hysaishi.cn/Article/details/gt2oltrhrir.html

JS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gt2hjcnnzbf.html

TS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gt2mxrlkmnf.html

Java: System.err.println("err")
来源：http://dali.nanxuanxn.top/Article/details/gt2wndnzvmf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.meibo888.top/Article/details/gt2zoiwgnic.html

Ruby: warn "err"
来源：http://dali.gotoacloud.top/Article/details/gt2upmxvpel.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2xuxialyo.html

[M07] 判断是否为主入口
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pfmurdkr.html

Py:   if __name__ == "__main__":
来源：http://dali.svipenyu.cn/Article/details/gt2udasnjie.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenjidiqi.icu/Article/details/gt2ttboisdy.html

JS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gt2cmoiksmt.html

TS:   require.main === module
来源：http://dali.aizwys.cn/Article/details/gt2iimohbhv.html

Java: public static void main(String[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jwdaiorb.html

Go:   func main()
来源：http://dali.sysykeji.top/Article/details/gt2geikyyhc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yonumen.top/Article/details/gt2oingpepc.html

C#:   static void Main(string[] args)
来源：http://dali.gaohongyu789.top/Article/details/gt2inlggpgi.html

[M08] 获取系统与运行时信息
来源：http://dali.cqqwz.cn/Article/details/gt2hpyrwvee.html

Py:   platform.system();  platform.python_version()
来源：http://dali.birdmap.top/Article/details/gt2rcwpmotj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hongshengwenyu.top/Article/details/gt2zxxnyofg.html

JS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gt2qmwhmfty.html

TS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gt2miswtxkr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhiwuduotai.top/Article/details/gt2nuhsqppw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhiwuduotai.top/Article/details/gt2rkwyxycf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ivvv.top/Article/details/gt2syosreih.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gaohongyu789.top/Article/details/gt2jqidotkq.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2bzulvuld.html

N. 数据结构与算法
来源：http://dali.hnqzz.top/Article/details/gt2qlcwgumn.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2brxswcne.html

[N01] 二分查找（有序数组）
来源：http://dali.zhoulong.xyz/Article/details/gt2cvlgowkt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuanzx.com/Article/details/gt2yxwhfdnd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yuxming.cn/Article/details/gt2ijwfcqnk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xinyue.icu/Article/details/gt2fwjvjxzq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dashuyun.cn/Article/details/gt2tukoljwe.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gt2cjbfcgwn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gt2ipdnmtxp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cucudq.cn/Article/details/gt2ztxoniqo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2zckbhnha.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj202588.top/Article/details/gt2blbarglo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gt2wrjirkae.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nanxuanxn.top/Article/details/gt2egbosgim.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ybcxt.top/Article/details/gt2uavhoeyl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gt2whsqrvgs.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.chenlongwang.top/Article/details/gt2seswatmy.html

Go:   slices.Sort(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2ililzaez.html

Ruby: arr.sort
来源：http://dali.yj20258.top/Article/details/gt2ftrhqrzp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.quarkkingdee.top/Article/details/gt2sucpzfwo.html

[N03] 快速排序（分治示例）
来源：http://dali.ppjwa.cn/Article/details/gt2lucojyfx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hammf.cn/Article/details/gt2qwooasio.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yanxiufei.cn/Article/details/gt2mhvfyemx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuxming.cn/Article/details/gt2gnbnxpng.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ybcxt.top/Article/details/gt2prrrwopb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.bjfxy.top/Article/details/gt2atzmflgq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shzxlz.cn/Article/details/gt2cjwhisab.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shuidangran.top/Article/details/gt2vbqfkogi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hnqzz.top/Article/details/gt2ixgjsakp.html

[N04] 斐波那契数列
来源：http://dali.yonumen.top/Article/details/gt2fhbvskra.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ndnwzhci.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj202588.top/Article/details/gt2cgrxklcd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gt2slltknrv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gt2wolyvrgm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gt2qcjjvcdr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.fengsongda.top/Article/details/gt2qidxkcpq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gt2rtlksthk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gt2zfvdfezr.html

[N05] 最大公约数
来源：http://dali.xinyue.icu/Article/details/gt2xsopvouw.html

Py:   math.gcd(a, b)
来源：http://dali.chenzaomai.com/Article/details/gt2raxbtyws.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jyoumei.cn/Article/details/gt2fznlldih.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hysaishi.cn/Article/details/gt2jdqbbyvp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nxqjdmaz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hnqzz.top/Article/details/gt2gfichxtz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aibaodan.cn/Article/details/gt2ikpuqsjc.html

Ruby: a.gcd(b)
来源：http://dali.ybcxt.top/Article/details/gt2uugimhzo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuxming.cn/Article/details/gt2nyscacdz.html

[N06] 判断回文字符串
来源：http://dali.redwolf501.top/Article/details/gt2fykjkftq.html

Py:   s == s[::-1]
来源：http://dali.cqqwz.cn/Article/details/gt2rmoimdny.html

PHP:  $s === strrev($s);
来源：http://dali.hammf.cn/Article/details/gt2mnodtcvc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gt2clndmthn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gt2vbdvssye.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ggweghaj.html

Go:   // 双指针从两端比较
来源：http://dali.pycfn.com/Article/details/gt2cpxnatod.html

Ruby: s == s.reverse
来源：http://dali.yvedp.cn/Article/details/gt2vsmkcgqf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.andypj.xyz/Article/details/gt2qxqosxsx.html

[N07] 两数之和（返回下标）
来源：http://dali.xinyue.icu/Article/details/gt2hnihcyin.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pengpengdd.cyou/Article/details/gt2pbtmhcmv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hammf.cn/Article/details/gt2gjdajluz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.bjfxy.top/Article/details/gt2csgmuowi.html

TS:   // 手写 Map<string, number>
来源：http://dali.havefunace.top/Article/details/gt2dzafrxdq.html

Java: // 手写 HashMap
来源：http://dali.sxryk.cn/Article/details/gt2vxsjghfi.html

Go:   // 手写 map[int]int
来源：http://dali.gaohongyu789.top/Article/details/gt2zaelsihf.html

Ruby: // 手写 Hash
来源：http://dali.cashguo.top/Article/details/gt2dgbsglev.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.redwolf501.top/Article/details/gt2rumikbgq.html

[N08] 生成全排列
来源：http://dali.fengsongda.top/Article/details/gt2pdkmlhis.html

Py:   itertools.permutations(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2orfycifh.html

PHP:  // 手写递归交换
来源：http://dali.pengpengdd.cyou/Article/details/gt2rbqvlvxf.html

JS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gt2ojurrbgf.html

TS:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gt2vwyupipc.html

Java: // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gt2wrujagwa.html

Go:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gt2lsdmamko.html

Ruby: arr.permutation.to_a
来源：http://dali.feifeiyinyue.top/Article/details/gt2rvddamco.html

C#:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gt2fettaxup.html

[N09] 栈与队列
来源：http://dali.svipenyu.cn/Article/details/gt2kdoderpt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2junegfdh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gt2dojdnkny.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gogol.net.cn/Article/details/gt2bgzaddjr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.havefunace.top/Article/details/gt2ukvckand.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.9152youxi.cn/Article/details/gt2jxrmgwnf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jianghu66.top/Article/details/gt2lqcranzp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.bjfxy.top/Article/details/gt2nzjobfid.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.dianchejie.cn/Article/details/gt2gxvbtfod.html

[N10] 链表节点定义
来源：http://dali.cashguo.top/Article/details/gt2gzszuwmc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.meibo888.top/Article/details/gt2kfmxuhuh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hnxiangtu.top/Article/details/gt2uvpwjpjn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ackklhrc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinqigfzy.top/Article/details/gt2dygfcxsn.html

Java: class Node { int v; Node next; }
来源：http://dali.gotoacloud.top/Article/details/gt2ejgvplsq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.fengsongda.top/Article/details/gt2ryrxpbha.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shuidangran.top/Article/details/gt2qwpmukjb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ybcxt.top/Article/details/gt2whygebnr.html

[N11] 二叉树中序遍历
来源：http://dali.wangdashe.top/Article/details/gt2kkdnjiol.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.vqdsnc.cn/Article/details/gt2fvdlngvf.html

PHP:  // 手写递归函数
来源：http://dali.cdnleiting.top/Article/details/gt2ualxwjkk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pengpengdd.cyou/Article/details/gt2lxymipxz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fzhhl.top/Article/details/gt2fahwjqga.html

Java: // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gt2alauibmz.html

Go:   // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gt2pmbiiwrh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinqigfzy.top/Article/details/gt2pxmutufb.html

C#:   // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gt2qifsimqw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.9152youxi.cn/Article/details/gt2uejwolqi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shangyingyoupin.top/Article/details/gt2umhxzxyt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xuetiantiany.cn/Article/details/gt2wgovhova.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jianghu66.top/Article/details/gt2ohyuekst.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ivvv.top/Article/details/gt2hdxzjybf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yxapxdvk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.birdmap.top/Article/details/gt2vhlksmdz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.snrcjt.cn/Article/details/gt2ynxqenbw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aibaodan.cn/Article/details/gt2wvofihqh.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2ezuohzge.html

O. 并发与异步
来源：http://dali.birdmap.top/Article/details/gt2suthkzox.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2spgmhfjw.html

[O01] 启动一个线程
来源：http://dali.sxryk.cn/Article/details/gt2uxapkthv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.birdmap.top/Article/details/gt2bjccxjha.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nanxuanxn.top/Article/details/gt2bcopajmw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cqqwz.cn/Article/details/gt2cxskgkqh.html

TS:   // 同 JS
来源：http://dali.quarkkingdee.top/Article/details/gt2sqpqyofh.html

Java: new Thread(() -> f()).start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kpkkzbmu.html

Go:   go f()
来源：http://dali.shzxlz.cn/Article/details/gt2vyyqdvgj.html

Ruby: Thread.new { f }
来源：http://dali.meibo888.top/Article/details/gt2qaxngijd.html

C#:   Task.Run(() => F());
来源：http://dali.zhengqikj.top/Article/details/gt2tfgofyyo.html

[O02] 使用线程池
来源：http://dali.nanxuanxn.top/Article/details/gt2yrjghsag.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hammf.cn/Article/details/gt2piyungdv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.mhx1999.top/Article/details/gt2hvyzqvyb.html

JS:   // worker_threads 线程池
来源：http://dali.pengpengdd.cyou/Article/details/gt2ztjfwcjb.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyvnkyr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cqqwz.cn/Article/details/gt2skpbnvpk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2naliuwap.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.dashuyun.cn/Article/details/gt2ezudzfjy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jianghu66.top/Article/details/gt2ejcjniko.html

[O03] 加锁保护共享数据
来源：http://dali.jinqigfzy.top/Article/details/gt2fynnomom.html

Py:   with lock: shared += 1
来源：http://dali.ppjwa.cn/Article/details/gt2akbqyomz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.fengsongda.top/Article/details/gt2tzdswbqh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.iojbl.cn/Article/details/gt2zpvukbpd.html

TS:   // 同 JS
来源：http://dali.tian-w.cn/Article/details/gt2yuamxcvr.html

Java: synchronized (this) { shared++; }
来源：http://dali.jqgfzy.top/Article/details/gt2uwzlxmfn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.pycfn.com/Article/details/gt2koybupts.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.aizwys.cn/Article/details/gt2quoqjmfz.html

C#:   lock (gate) { shared++; }
来源：http://dali.gaohongyu789.top/Article/details/gt2oxkmnmxu.html

[O04] 定义异步函数并等待
来源：http://dali.yj20258.top/Article/details/gt2bevngvsk.html

Py:   async def f():⏎    await g()
来源：http://dali.yonumen.top/Article/details/gt2suvldnsv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yuxming.cn/Article/details/gt2vafqdrta.html

JS:   async function f() { await g(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ccybweaa.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnqzz.top/Article/details/gt2wictejna.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj20258.top/Article/details/gt2nvmkkdeq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.snrcjt.cn/Article/details/gt2kgmbhikj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.snrcjt.cn/Article/details/gt2jxlhuljg.html

C#:   async Task F() { await G(); }
来源：http://dali.gzhubu.top/Article/details/gt2vlqqpldm.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinqigfzy.top/Article/details/gt2ubwrxuib.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hammf.cn/Article/details/gt2quakgexl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhongyouzk.top/Article/details/gt2ecputoql.html

JS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gt2wwuomisc.html

TS:   await Promise.all(tasks)
来源：http://dali.cashguo.top/Article/details/gt2ivuokvqx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cashguo.top/Article/details/gt2ljhntdrl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tian-w.cn/Article/details/gt2tfsvdpka.html

Ruby: threads.map(&:join)
来源：http://dali.chenzaomai.com/Article/details/gt2bmyuuqph.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhongyouzk.top/Article/details/gt2krkeclkw.html

[O06] 使用进程池
来源：http://dali.jyoumei.cn/Article/details/gt2zgjtvoqo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yonumen.top/Article/details/gt2nosipojj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jiagoushi.top/Article/details/gt2xygswtps.html

JS:   // child_process / cluster 模块
来源：http://dali.zycfv.cn/Article/details/gt2iedcmfpl.html

TS:   // child_process / cluster 模块
来源：http://dali.yuanzhike.top/Article/details/gt2wrutjkif.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.9152youxi.cn/Article/details/gt2srikwngr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gzhubu.top/Article/details/gt2mqmkhplc.html

Ruby: // fork 块
来源：http://dali.jiagoushi.top/Article/details/gt2syztihgl.html

C#:   Parallel.For
来源：http://dali.zhengqikj.top/Article/details/gt2eibosuuf.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kiilreye.html

P. 常用工具函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mvnrqust.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2vhvifrvx.html

[P01] 生成 UUID
来源：http://dali.yj20258888.top/Article/details/gt2ixhmxods.html

Py:   str(uuid.uuid4())
来源：http://dali.316326.xyz/Article/details/gt2rnmmzrtp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.guannengcc.top/Article/details/gt2bcneknka.html

JS:   crypto.randomUUID()
来源：http://dali.redwolf501.top/Article/details/gt2kfargror.html

TS:   crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gt2ihuurhas.html

Java: UUID.randomUUID().toString()
来源：http://dali.shuidangran.top/Article/details/gt2prgsorqr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ehwqpu.com/Article/details/gt2tyimjegs.html

Ruby: SecureRandom.uuid
来源：http://dali.yongpay.top/Article/details/gt2xrezsfyx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cashguo.top/Article/details/gt2oqipnxmp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yuxming.cn/Article/details/gt2hqjjnwtr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj20258888.top/Article/details/gt2elkcgxfi.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj202588.top/Article/details/gt2zxagrjri.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.tanke756.top/Article/details/gt2njglgrps.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hongshengwenyu.top/Article/details/gt2sumxmmiw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xylfe.cn/Article/details/gt2rnuvscex.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yueranfly.top/Article/details/gt2ucxfoanr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jxjitapz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hywenlv.cn/Article/details/gt2vdvarubn.html

[P03] 生成短随机字符串
来源：http://dali.haohaochexian.top/Article/details/gt2xrnlmjfu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhengqikj.top/Article/details/gt2zfvzsmgx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ydzc1.top/Article/details/gt2arwnwfrw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuanzx.com/Article/details/gt2btafvgux.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ojfkhyqm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.snrcjt.cn/Article/details/gt2odhiwolc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gotoacloud.top/Article/details/gt2zfppezxy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gogol.net.cn/Article/details/gt2qkclfrrb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhiwuduotai.top/Article/details/gt2wpiaokzj.html

[P04] 求长度
来源：http://dali.cdnleiting.top/Article/details/gt2khgpfakr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iuzknanm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2uljspjbr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jlsjyb.cn/Article/details/gt2sydbtorn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gt2kkiksdpw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guannengcc.top/Article/details/gt2fioqzbnw.html

Go:   len(arr);  len(m)
来源：http://dali.quarkkingdee.top/Article/details/gt2squtvvqr.html

Ruby: x.length;  x.size
来源：http://dali.birdmap.top/Article/details/gt2fzwgrdte.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hysaishi.cn/Article/details/gt2jmxkikfj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tian-w.cn/Article/details/gt2cdomoipi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xinyue.icu/Article/details/gt2rtybxsuk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.c1oappe.top/Article/details/gt2zazynatw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jqgfzy.top/Article/details/gt2mtivqtmv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qufxmogw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shzxlz.cn/Article/details/gt2epqvugao.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qznxetoz.html

Ruby: a == b
来源：http://dali.kuanghao11.cn/Article/details/gt2ueukrjva.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yangfankeji.com/Article/details/gt2jntbtxcj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tgxssdli.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.c1oappe.top/Article/details/gt2trywfhtr.html

PHP:  if (empty($x)) {}
来源：http://dali.xziqi.cn/Article/details/gt2oebstyhx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.dianchejie.cn/Article/details/gt2agvfqbun.html

TS:   if (x == null) {}
来源：http://dali.c1oappe.top/Article/details/gt2iexsesro.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yueranfly.top/Article/details/gt2fsczyhtu.html

Go:   if x == nil {}
来源：http://dali.cashguo.top/Article/details/gt2ipbovjxm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yanxiufei.cn/Article/details/gt2npfevirt.html

C#:   if (x is null) {}
来源：http://dali.gogol.net.cn/Article/details/gt2ksshmzhe.html

[P07] 防抖与节流
来源：http://dali.yueranfly.top/Article/details/gt2hrcddqac.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nwbrower.top/Article/details/gt2lsvnwfyh.html

PHP:  // 手写时间戳比较
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fwsgkgty.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jyoumei.cn/Article/details/gt2dpphibcl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.svipenyu.cn/Article/details/gt2wstfxkbn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ivvv.top/Article/details/gt2nklepxcr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.iojbl.cn/Article/details/gt2juafmgew.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nanxuanxn.top/Article/details/gt2khchyxlg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.iojbl.cn/Article/details/gt2addgyivw.html

[P08] 处理浮点精度问题
来源：http://dali.yuanzhike.top/Article/details/gt2llumlzfy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.redwolf501.top/Article/details/gt2taovhvru.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.havefunace.top/Article/details/gt2augewrer.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.c1oappe.top/Article/details/gt2foacdovq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.havefunace.top/Article/details/gt2cqndqsvz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.nanxuanxn.top/Article/details/gt2fkargwrs.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenzaomai.com/Article/details/gt2xwzkalrr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenlongwang.top/Article/details/gt2wcfdtizq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.birdmap.top/Article/details/gt2waodsyjc.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2hbbbxifa.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eeazxhzq.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2xtgmivvz.html

[Q01] 创建表
来源：http://dali.kuanghao11.cn/Article/details/gt2tubjrezf.html

CREATE TABLE users (
来源：http://dali.smart0.xyz/Article/details/gt2zutnuuyk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guowangkeji.top/Article/details/gt2bmssowhq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sxryk.cn/Article/details/gt2rjdqbvkh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.dianchejie.cn/Article/details/gt2ngmlencl.html


<!-- 参考信息 -->