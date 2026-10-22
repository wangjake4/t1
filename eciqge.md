代发 wailian999

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ehwqpu.com/Article/details/gtmvfinzyt.html

[M05] 设置退出码
来源：http://dali.yanxiufei.cn/Article/details/gtohojqtfk.html

Py:   sys.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtbkfwytdr.html

PHP:  exit(1);
来源：http://dali.xylfe.cn/Article/details/gtmdwghjwi.html

JS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtbvejyhtx.html

TS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gtujkeivqq.html

Java: System.exit(1)
来源：http://dali.birdmap.top/Article/details/gtcmqwqmdd.html

Go:   os.Exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gttxemijvl.html

Ruby: exit 1
来源：http://dali.jiagoushi.top/Article/details/gtgtjgdlhj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.andypj.xyz/Article/details/gtbqkbtqqz.html

[M06] 向标准错误输出
来源：http://dali.vqdsnc.cn/Article/details/gtcasfzsjx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gotoacloud.top/Article/details/gtchrzrsph.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenlongwang.top/Article/details/gtmerfpyct.html

JS:   console.error("err")
来源：http://dali.meibo888.top/Article/details/gtfsgcbeig.html

TS:   console.error("err")
来源：http://dali.dianchejie.cn/Article/details/gtevoazfzj.html

Java: System.err.println("err")
来源：http://dali.gogol.net.cn/Article/details/gtxoycwwmh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tianlin.xyz/Article/details/gtsvuvemzj.html

Ruby: warn "err"
来源：http://dali.svipenyu.cn/Article/details/gtdygksuys.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenlongwang.top/Article/details/gtkrnwxmex.html

[M07] 判断是否为主入口
来源：http://dali.gotoacloud.top/Article/details/gtlhhfufue.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigfzy.top/Article/details/gtaiztdafv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sysykeji.top/Article/details/gtxrgfiiog.html

JS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gtmmdejekd.html

TS:   require.main === module
来源：http://dali.tian-w.cn/Article/details/gtlxewxcxc.html

Java: public static void main(String[] args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmirocah.html

Go:   func main()
来源：http://dali.wangshuangyany.cn/Article/details/gtvszazzce.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj20258888.top/Article/details/gttczrmtxu.html

C#:   static void Main(string[] args)
来源：http://dali.quarkkingdee.top/Article/details/gtpwqxevjd.html

[M08] 获取系统与运行时信息
来源：http://dali.aibaodan.cn/Article/details/gtbhdvolff.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cqqwz.cn/Article/details/gtvxhxvted.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.pengpengdd.cyou/Article/details/gtlhxezlwe.html

JS:   process.platform;  process.version
来源：http://dali.shangyingyoupin.top/Article/details/gtweuluymi.html

TS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gtnvtkzgch.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dashuyun.cn/Article/details/gtkrtyzmgh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cheryme.top/Article/details/gtlwcdahaq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ppjwa.cn/Article/details/gtpppmflwy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.fengsongda.top/Article/details/gtqkxpqlds.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtdbwvdytt.html

N. 数据结构与算法
来源：http://dali.yj202588.top/Article/details/gtpbzdwfxw.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtqbeqstes.html

[N01] 二分查找（有序数组）
来源：http://dali.chenlongwang.top/Article/details/gtyogptjrh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtiwhmtizx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.aibaodan.cn/Article/details/gtyxswkivl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gtzorshpwq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xziqi.cn/Article/details/gtvvvdiqnn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtoseduohj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtccdboaes.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jianghu66.top/Article/details/gtnzjrjdhs.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtvooeomre.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigfzy.top/Article/details/gtwnzvkwee.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxuanxn.top/Article/details/gtedouvuei.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ppjwa.cn/Article/details/gtrgijxbhd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gtosoqnttb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhiwuduotai.top/Article/details/gtzhawpxoq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xylfe.cn/Article/details/gtebzkyvqg.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigufen.top/Article/details/gthzzdgrhx.html

Ruby: arr.sort
来源：http://dali.yanxiufei.cn/Article/details/gtlrjsdidd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daria6918.cn/Article/details/gtitleyotw.html

[N03] 快速排序（分治示例）
来源：http://dali.feifeiyinyue.top/Article/details/gtliwcbtef.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sxryk.cn/Article/details/gtwwcjyrdg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xinyue.icu/Article/details/gtvzdsmdjb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigufen.top/Article/details/gtsgcmfqfa.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gtcqezpdbc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinqigfzy.top/Article/details/gtczxpjaqv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jiagoushi.top/Article/details/gtacpueily.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.aizwys.cn/Article/details/gtkjeumsdd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.feifeiyinyue.top/Article/details/gtfpblzqez.html

[N04] 斐波那契数列
来源：http://dali.gogol.net.cn/Article/details/gtnkcqyweq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sysykeji.top/Article/details/gtraayobut.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yangfankeji.com/Article/details/gtplltcelc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gtsqxpgbsa.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gthjkurlfq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenjidiqi.icu/Article/details/gtcsstqeve.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jqgfzy.top/Article/details/gtuaqiouio.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.havefunace.top/Article/details/gtlxkfnaya.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhongyouzk.top/Article/details/gtxootieyk.html

[N05] 最大公约数
来源：http://dali.sysykeji.top/Article/details/gtczlhexvt.html

Py:   math.gcd(a, b)
来源：http://dali.yuxming.cn/Article/details/gtburcahdh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.guannengcc.top/Article/details/gthokhnzsz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxoabukku.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zdqjudy.top/Article/details/gtdpieihqp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hysaishi.cn/Article/details/gtmhvvgwuk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aizwys.cn/Article/details/gtighaxpwf.html

Ruby: a.gcd(b)
来源：http://dali.smart0.xyz/Article/details/gtqleogmpj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.wangdashe.top/Article/details/gtziaprodz.html

[N06] 判断回文字符串
来源：http://dali.yanxiufei.cn/Article/details/gtzmoeysbg.html

Py:   s == s[::-1]
来源：http://dali.pycfn.com/Article/details/gtahpazhrv.html

PHP:  $s === strrev($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnqkxbvw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtqyhnedvi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtttehtiuh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sysykeji.top/Article/details/gtwzcckoko.html

Go:   // 双指针从两端比较
来源：http://dali.hysaishi.cn/Article/details/gtayknppng.html

Ruby: s == s.reverse
来源：http://dali.ybcxt.top/Article/details/gtiiuwhhru.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hnxiangtu.top/Article/details/gthpcqdhee.html

[N07] 两数之和（返回下标）
来源：http://dali.nanxinkj.top/Article/details/gtihjyqguh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.birdmap.top/Article/details/gturjvmbls.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.vqdsnc.cn/Article/details/gtnrglqpvl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj20258.top/Article/details/gtxjvcsipx.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinqigufen.top/Article/details/gtxfzuubxe.html

Java: // 手写 HashMap
来源：http://dali.zhiwuduotai.top/Article/details/gttbeyfoep.html

Go:   // 手写 map[int]int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyynrynpo.html

Ruby: // 手写 Hash
来源：http://dali.hnxiangtu.top/Article/details/gtjsmlcobc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gaohongyu789.top/Article/details/gtrgkxgcfo.html

[N08] 生成全排列
来源：http://dali.cdnleiting.top/Article/details/gtgippbluz.html

Py:   itertools.permutations(arr)
来源：http://dali.guowangkeji.top/Article/details/gtsmazkhqk.html

PHP:  // 手写递归交换
来源：http://dali.dashuyun.cn/Article/details/gtlmvpqdjk.html

JS:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtpiydiilo.html

TS:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtbzmdyoaa.html

Java: // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtdgzvwdrt.html

Go:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtrwjhvnam.html

Ruby: arr.permutation.to_a
来源：http://dali.svipenyu.cn/Article/details/gtuoglldcq.html

C#:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtpqdvukgp.html

[N09] 栈与队列
来源：http://dali.hnxiangtu.top/Article/details/gtvxwavzpw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zdqjudy.top/Article/details/gtimetobhl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gtdpirjusg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.meibo888.top/Article/details/gtmdkatmdd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.feifeiyinyue.top/Article/details/gtbpojdlmj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hammf.cn/Article/details/gtgplwrndl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.smart0.xyz/Article/details/gtmzwrcfhk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.316326.xyz/Article/details/gtipiucmkl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zdqjudy.top/Article/details/gthkjzkhgn.html

[N10] 链表节点定义
来源：http://dali.chenzaomai.com/Article/details/gtdimrsqbe.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sysykeji.top/Article/details/gtftpgnqfk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xuanzx.com/Article/details/gtydousstw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.fzhhl.top/Article/details/gtgsprypwy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yuxming.cn/Article/details/gtwbjxrajd.html

Java: class Node { int v; Node next; }
来源：http://dali.sysykeji.top/Article/details/gtdxiwddzi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.andypj.xyz/Article/details/gthvomseep.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.svipenyu.cn/Article/details/gtpotxhizx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.daxiang520.top/Article/details/gthtpfovwt.html

[N11] 二叉树中序遍历
来源：http://dali.fzhhl.top/Article/details/gtpeztccez.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhiwuduotai.top/Article/details/gtlriohuiz.html

PHP:  // 手写递归函数
来源：http://dali.ppjwa.cn/Article/details/gtzvmwlcuh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.andypj.xyz/Article/details/gtwrulnqiy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gotoacloud.top/Article/details/gtetapxbgg.html

Java: // 手写递归
来源：http://dali.yvedp.cn/Article/details/gtkzjncvdu.html

Go:   // 手写递归
来源：http://dali.yueranfly.top/Article/details/gtduvvdkxs.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenlongwang.top/Article/details/gtwgeodoii.html

C#:   // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gtxrwoighp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jqgufenzy.top/Article/details/gttcxqlunb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shanyushiyangtech.top/Article/details/gtmkdpdmud.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shanyushiyangtech.top/Article/details/gteeocdvls.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aibaodan.cn/Article/details/gtayvuejcl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shangyingyoupin.top/Article/details/gthascvcrb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gtpprwjuij.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ybcxt.top/Article/details/gtjwyemxsl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.snrcjt.cn/Article/details/gtvutexswt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.vqdsnc.cn/Article/details/gtrrjgsplj.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtnmmvqxmm.html

O. 并发与异步
来源：http://dali.316326.xyz/Article/details/gtuacndlqq.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtqndjfhgr.html

[O01] 启动一个线程
来源：http://dali.cucudq.cn/Article/details/gtyuzwcxrq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.fengsongda.top/Article/details/gtzjuezful.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hfpthk.cn/Article/details/gtkikmocxh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jiagoushi.top/Article/details/gtodcdugon.html

TS:   // 同 JS
来源：http://dali.zhongyouzk.top/Article/details/gtqohmyyjj.html

Java: new Thread(() -> f()).start()
来源：http://dali.jqgufenzy.top/Article/details/gtvhtwcoyv.html

Go:   go f()
来源：http://dali.jiagoushi.top/Article/details/gtvxdcfnuz.html

Ruby: Thread.new { f }
来源：http://dali.jiagoushi.top/Article/details/gtlyclefkv.html

C#:   Task.Run(() => F());
来源：http://dali.ydzc1.top/Article/details/gtfetnlgmp.html

[O02] 使用线程池
来源：http://dali.jqgufenzy.top/Article/details/gtezdexnku.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj202588.top/Article/details/gtcugtmigj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cqqwz.cn/Article/details/gtqchlgmnc.html

JS:   // worker_threads 线程池
来源：http://dali.xuanzx.com/Article/details/gtqcueegwa.html

TS:   // worker_threads 线程池
来源：http://dali.cheryme.top/Article/details/gtiquaelvy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sufxvd.cn/Article/details/gtsddiurub.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwkzrqfmi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbzfixkcr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hfpthk.cn/Article/details/gtrigrdpfc.html

[O03] 加锁保护共享数据
来源：http://dali.hywenlv.cn/Article/details/gtcxusvqpx.html

Py:   with lock: shared += 1
来源：http://dali.wangdashe.top/Article/details/gtaqgowium.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hywenlv.cn/Article/details/gteaarylwo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tanke756.top/Article/details/gtmusjubfc.html

TS:   // 同 JS
来源：http://dali.xuetiantiany.cn/Article/details/gtfgehcgbs.html

Java: synchronized (this) { shared++; }
来源：http://dali.pycfn.com/Article/details/gtnhuhckaf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cashguo.top/Article/details/gtbqnlpxqn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.c1oappe.top/Article/details/gtubantcwg.html

C#:   lock (gate) { shared++; }
来源：http://dali.0kj1m.cn/Article/details/gtgcfibugf.html

[O04] 定义异步函数并等待
来源：http://dali.cqqwz.cn/Article/details/gtmfzoijsn.html

Py:   async def f():⏎    await g()
来源：http://dali.sysykeji.top/Article/details/gtcvqrrbam.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yonumen.top/Article/details/gtdqczxssk.html

JS:   async function f() { await g(); }
来源：http://dali.shzxlz.cn/Article/details/gtokxjxhco.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.meibo888.top/Article/details/gtoozbwose.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.daxiang520.top/Article/details/gtbwhgmrfl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xuetiantiany.cn/Article/details/gturwbdyhg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhaomingkeji.xyz/Article/details/gteanmjkut.html

C#:   async Task F() { await G(); }
来源：http://dali.tanke756.top/Article/details/gtbfbqgoms.html

[O05] 并发执行并等待全部完成
来源：http://dali.ydzc1.top/Article/details/gtacqiufvv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.guannengcc.top/Article/details/gtypjvxaop.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yuxming.cn/Article/details/gtiziexdos.html

JS:   await Promise.all(tasks)
来源：http://dali.redwolf501.top/Article/details/gtnxiudgmo.html

TS:   await Promise.all(tasks)
来源：http://dali.yongpay.top/Article/details/gtngaxfuep.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.snrcjt.cn/Article/details/gtkixgivrg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinqigfzy.top/Article/details/gtjwzngdxe.html

Ruby: threads.map(&:join)
来源：http://dali.fzhhl.top/Article/details/gtrakyfkwb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hfpthk.cn/Article/details/gtromexuzs.html

[O06] 使用进程池
来源：http://dali.iojbl.cn/Article/details/gtshdswrmi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.andypj.xyz/Article/details/gtdcmxdiqc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xuanzx.com/Article/details/gtpzyytslk.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gtrtchncwi.html

TS:   // child_process / cluster 模块
来源：http://dali.ehwqpu.com/Article/details/gteudokptx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jqgfzy.top/Article/details/gtxxcwbvpj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.fzhhl.top/Article/details/gtyhlvabyk.html

Ruby: // fork 块
来源：http://dali.meibo888.top/Article/details/gtsdrugvzq.html

C#:   Parallel.For
来源：http://dali.andypj.xyz/Article/details/gtvwhqozeq.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtcwemwkkg.html

P. 常用工具函数
来源：http://dali.iojbl.cn/Article/details/gtberqshaa.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtrgrhewgh.html

[P01] 生成 UUID
来源：http://dali.xziqi.cn/Article/details/gtxunjkqnr.html

Py:   str(uuid.uuid4())
来源：http://dali.9152youxi.cn/Article/details/gtkiagmvok.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.smart0.xyz/Article/details/gtgtacnxuz.html

JS:   crypto.randomUUID()
来源：http://dali.haohaochexian.top/Article/details/gtqeqkcqxy.html

TS:   crypto.randomUUID()
来源：http://dali.xziqi.cn/Article/details/gtykxqkijg.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhongyouzk.top/Article/details/gtfnwfpksi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shzxlz.cn/Article/details/gtcannnquc.html

Ruby: SecureRandom.uuid
来源：http://dali.chenzaomai.com/Article/details/gtigseqzmf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenzaomai.com/Article/details/gtsyxnatte.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jianghu66.top/Article/details/gtdjguhenv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tanke756.top/Article/details/gtmyxgfhar.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xuanzx.com/Article/details/gtzogwtnfn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hnxiangtu.top/Article/details/gtxrgznorc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nwbrower.top/Article/details/gttaetdpbm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.snrcjt.cn/Article/details/gtgyfcpjwu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tianlin.xyz/Article/details/gtpajvctyr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cheryme.top/Article/details/gtgadtkvpb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hnqzz.top/Article/details/gtmidemozl.html

[P03] 生成短随机字符串
来源：http://dali.daria6918.cn/Article/details/gtssiqdqem.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.guowangkeji.top/Article/details/gtciipuyja.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.guowangkeji.top/Article/details/gtegqmwbqv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gtklgaruzx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.vqdsnc.cn/Article/details/gtfwcdhjjc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrwgbnfor.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yvedp.cn/Article/details/gtqrhclsim.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shzxlz.cn/Article/details/gtkyyiphge.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ybcxt.top/Article/details/gtcikxanpz.html

[P04] 求长度
来源：http://dali.bjfxy.top/Article/details/gtrqezpquj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.pengpengdd.cyou/Article/details/gtlhwteipm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gtnplfjben.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258.top/Article/details/gtetitdnki.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpzmcytsv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hywenlv.cn/Article/details/gtrxaykwgb.html

Go:   len(arr);  len(m)
来源：http://dali.ybcxt.top/Article/details/gtihjvlqzf.html

Ruby: x.length;  x.size
来源：http://dali.hammf.cn/Article/details/gtddmnrxga.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cqqwz.cn/Article/details/gtyxufsufs.html

[P05] 判断两个对象内容是否相等
来源：http://dali.iojbl.cn/Article/details/gtyvhvmauh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hysaishi.cn/Article/details/gtdkpklotl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ppjwa.cn/Article/details/gtbxagkzrt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.aibaodan.cn/Article/details/gtbdlahhnw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuanzx.com/Article/details/gtjegqemsy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.svipenyu.cn/Article/details/gthdnfztvq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tianlin.xyz/Article/details/gtqvgwoqct.html

Ruby: a == b
来源：http://dali.tian-w.cn/Article/details/gtzyhxvqai.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cucudq.cn/Article/details/gtbsenswdz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cheryme.top/Article/details/gtnfdtqlbr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hnxiangtu.top/Article/details/gteylbjsyx.html

PHP:  if (empty($x)) {}
来源：http://dali.zhixingplan.top/Article/details/gtjlahsrzf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhiwuduotai.top/Article/details/gtyoxzauuh.html

TS:   if (x == null) {}
来源：http://dali.pycfn.com/Article/details/gtipceyzgs.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.svipenyu.cn/Article/details/gtwybuxpos.html

Go:   if x == nil {}
来源：http://dali.zhoulong.xyz/Article/details/gtxkfknzko.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cashguo.top/Article/details/gtrhrgaamo.html

C#:   if (x is null) {}
来源：http://dali.zhixingplan.top/Article/details/gtvjbnzglm.html

[P07] 防抖与节流
来源：http://dali.jlsjyb.cn/Article/details/gtyeoyyqyy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ydzc1.top/Article/details/gtdtqjrhcx.html

PHP:  // 手写时间戳比较
来源：http://dali.yangfankeji.com/Article/details/gtfqrlpzpc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gteuuwttkr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuxming.cn/Article/details/gtamgvfczq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.fengsongda.top/Article/details/gtfcychvop.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhongyouzk.top/Article/details/gtfddnimgs.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hongshengwenyu.top/Article/details/gtlfaonaxn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.dashuyun.cn/Article/details/gtahyetvwq.html

[P08] 处理浮点精度问题
来源：http://dali.hfpthk.cn/Article/details/gtccrnbxlv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.pengpengdd.cyou/Article/details/gtihsjrfbi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nanxinkj.top/Article/details/gtczffchre.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ehwqpu.com/Article/details/gtrqrhnetq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.dianchejie.cn/Article/details/gtchmiqdza.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhongyouzk.top/Article/details/gtonvadagw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yj20258888.top/Article/details/gtdqfnvmxs.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ybcxt.top/Article/details/gtehwptqhr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.meibo888.top/Article/details/gtvrjtonnw.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtedsyenpk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.kuanghao11.cn/Article/details/gtajvlnahd.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtftspndnw.html

[Q01] 创建表
来源：http://dali.c1oappe.top/Article/details/gtzlmvvrgu.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gtwzabsgpb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jianghu66.top/Article/details/gtazfvykss.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hammf.cn/Article/details/gtkvylcwpt.html

email VARCHAR(100) UNIQUE,
来源：http://dali.c1oappe.top/Article/details/gtmokqnjne.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenlongwang.top/Article/details/gtrxcaeccr.html

);
来源：http://dali.wangdashe.top/Article/details/gtdpzmfmsn.html

[Q02] 创建带外键的表
来源：http://dali.jlsjyb.cn/Article/details/gtminxepbv.html

CREATE TABLE orders (
来源：http://dali.svipenyu.cn/Article/details/gtwvcjpdah.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cashguo.top/Article/details/gtybkwmlhe.html

user_id INT NOT NULL,
来源：http://dali.vqdsnc.cn/Article/details/gtvfmywqzh.html

amount DECIMAL(10, 2),
来源：http://dali.redwolf501.top/Article/details/gtrnimljvu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cqqwz.cn/Article/details/gtwczoeeeq.html

);
来源：http://dali.meibo888.top/Article/details/gtyvfpejmy.html

[Q03] 增加列
来源：http://dali.jianghu66.top/Article/details/gtpwthjeqz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xuetiantiany.cn/Article/details/gtuhphwvzk.html

[Q04] 修改列类型
来源：http://dali.cucudq.cn/Article/details/gtzxrtykva.html


<!-- 参考信息 -->