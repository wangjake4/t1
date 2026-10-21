代发 wailian999

JS:   process.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtnplfwfqz.html

TS:   process.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtxoidxrqj.html

Java: System.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtdjfktlab.html

Go:   os.Exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtrerirrpe.html

Ruby: exit 1
来源：http://dali.zycfv.cn/Article/details/gtfcswblhc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.guowangkeji.top/Article/details/gtgrmytvdy.html

[M06] 向标准错误输出
来源：http://dali.chenlongwang.top/Article/details/gtvpvxaoyh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zdqjudy.top/Article/details/gtwenxojob.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenlongwang.top/Article/details/gtrkogkyvp.html

JS:   console.error("err")
来源：http://dali.wangshuangyany.cn/Article/details/gtaqdczfnp.html

TS:   console.error("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtqxricgtg.html

Java: System.err.println("err")
来源：http://dali.nanxinkj.top/Article/details/gtvemjfvyf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sysykeji.top/Article/details/gthbeeztgi.html

Ruby: warn "err"
来源：http://dali.smart0.xyz/Article/details/gtaimbhdyy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhoulong.xyz/Article/details/gtzsoqpdok.html

[M07] 判断是否为主入口
来源：http://dali.316326.xyz/Article/details/gtsdufmkix.html

Py:   if __name__ == "__main__":
来源：http://dali.hnqzz.top/Article/details/gtmxfjiawp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.0kj1m.cn/Article/details/gtjpinlmue.html

JS:   require.main === module
来源：http://dali.guowangkeji.top/Article/details/gttekirzwy.html

TS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gtfewjqkat.html

Java: public static void main(String[] args)
来源：http://dali.dianchejie.cn/Article/details/gtxkkrguys.html

Go:   func main()
来源：http://dali.yangfankeji.com/Article/details/gttyorfypu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xinyue.icu/Article/details/gtruzqwbqk.html

C#:   static void Main(string[] args)
来源：http://dali.iojbl.cn/Article/details/gttsjfppmn.html

[M08] 获取系统与运行时信息
来源：http://dali.jianghu66.top/Article/details/gtafrkfwmo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shangyingyoupin.top/Article/details/gtkpmxsini.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.kuanghao11.cn/Article/details/gtgtkqlqke.html

JS:   process.platform;  process.version
来源：http://dali.hfpthk.cn/Article/details/gtjhqrfgls.html

TS:   process.platform;  process.version
来源：http://dali.ppjwa.cn/Article/details/gthqveprel.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gogol.net.cn/Article/details/gtesmjfthm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.vqdsnc.cn/Article/details/gtgzmxcxhe.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.mhx1999.top/Article/details/gtuexvxqrw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cheryme.top/Article/details/gtslmdgvyi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtbkuiisvi.html

N. 数据结构与算法
来源：http://dali.cashguo.top/Article/details/gtxmnuyjwc.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gttftkofaf.html

[N01] 二分查找（有序数组）
来源：http://dali.pycfn.com/Article/details/gtiztjwusp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtpveoelut.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gthvdffczt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gtnztzoyxv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zycfv.cn/Article/details/gtgmycdvgo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtarvznmvr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlunwcnvy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yonumen.top/Article/details/gteqaibhyf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj202588.top/Article/details/gtxvzdgwdp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yangfankeji.com/Article/details/gtfeblrjpq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sweek.top/Article/details/gtyuvgedly.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.iojbl.cn/Article/details/gtluxbxxlo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daxiang520.top/Article/details/gtgozwcrwa.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yonumen.top/Article/details/gtgdmhpjos.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yueranfly.top/Article/details/gtsjzqruoi.html

Go:   slices.Sort(arr)
来源：http://dali.gzhubu.top/Article/details/gthmtnyvdi.html

Ruby: arr.sort
来源：http://dali.9152youxi.cn/Article/details/gtnpvhdffd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yonumen.top/Article/details/gtzodvjfla.html

[N03] 快速排序（分治示例）
来源：http://dali.quarkkingdee.top/Article/details/gtmixhchpr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.feifeiyinyue.top/Article/details/gttwowscue.html

PHP:  // 递归实现，或用 usort
来源：http://dali.c1oappe.top/Article/details/gtjaeeltye.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aibaodan.cn/Article/details/gtwiuwqlld.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yueranfly.top/Article/details/gtdnrnkvjx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.9152youxi.cn/Article/details/gtvihkkxsw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xylfe.cn/Article/details/gtdgpwwoql.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hongshengwenyu.top/Article/details/gtwxpwticc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.aibaodan.cn/Article/details/gtkgrvjtcr.html

[N04] 斐波那契数列
来源：http://dali.ppjwa.cn/Article/details/gtztvgqkxt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hammf.cn/Article/details/gthvjzgwtq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yongpay.top/Article/details/gttzquogas.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gtlotxzjqj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gtbcjskldx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.fengsongda.top/Article/details/gtbeifglfg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yonumen.top/Article/details/gtzlnecnrd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtivrspeog.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gtnyafdrjw.html

[N05] 最大公约数
来源：http://dali.zhixingplan.top/Article/details/gtefoyvhhs.html

Py:   math.gcd(a, b)
来源：http://dali.gzhubu.top/Article/details/gtvmcvqisx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ehwqpu.com/Article/details/gtpxdzcbmz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fzhhl.top/Article/details/gthdtpxhxa.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jiagoushi.top/Article/details/gtzhczwhhm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinqigufen.top/Article/details/gtlnlmmosx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gzhubu.top/Article/details/gtesfssmld.html

Ruby: a.gcd(b)
来源：http://dali.yj20258888.top/Article/details/gtwsbzwwel.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.snrcjt.cn/Article/details/gtouayauon.html

[N06] 判断回文字符串
来源：http://dali.sxryk.cn/Article/details/gtbvjhogzg.html

Py:   s == s[::-1]
来源：http://dali.shuidangran.top/Article/details/gtzbmbdzhz.html

PHP:  $s === strrev($s);
来源：http://dali.yanxiufei.cn/Article/details/gthxdyipng.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gtxkffahad.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gtshmsjqiy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.smart0.xyz/Article/details/gtgoosbrvb.html

Go:   // 双指针从两端比较
来源：http://dali.yangfankeji.com/Article/details/gtvgxyizhg.html

Ruby: s == s.reverse
来源：http://dali.shuidangran.top/Article/details/gthkaisyoz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmswvmhpx.html

[N07] 两数之和（返回下标）
来源：http://dali.kuanghao11.cn/Article/details/gtealbrrfm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hfpthk.cn/Article/details/gtnsprnioh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.andypj.xyz/Article/details/gtmecuckay.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.haohaochexian.top/Article/details/gtmlwxmhid.html

TS:   // 手写 Map<string, number>
来源：http://dali.ppjwa.cn/Article/details/gtecocaiqo.html

Java: // 手写 HashMap
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdvklphyv.html

Go:   // 手写 map[int]int
来源：http://dali.zhiwuduotai.top/Article/details/gtyigwipeb.html

Ruby: // 手写 Hash
来源：http://dali.yonumen.top/Article/details/gtqnputhqz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinqigfzy.top/Article/details/gtborbryyf.html

[N08] 生成全排列
来源：http://dali.yongpay.top/Article/details/gtxqtgmmle.html

Py:   itertools.permutations(arr)
来源：http://dali.tanke756.top/Article/details/gtzrrlkkda.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gtahbyjuck.html

JS:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtlczwehlx.html

TS:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtzaofmioo.html

Java: // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gtlndfzhkd.html

Go:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtlwwhxtkb.html

Ruby: arr.permutation.to_a
来源：http://dali.jinqigufen.top/Article/details/gtzsteqimy.html

C#:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtokjynlzr.html

[N09] 栈与队列
来源：http://dali.nwbrower.top/Article/details/gtztxcwlft.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.c1oappe.top/Article/details/gtpthdtnnk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zycfv.cn/Article/details/gtpyswlxuw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtjykjlniy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.mhx1999.top/Article/details/gtalyuiqgq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jianghu66.top/Article/details/gtcjbjxrjw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jyoumei.cn/Article/details/gtfnifutzv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sxryk.cn/Article/details/gtymdefzks.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ybcxt.top/Article/details/gtppfscmwc.html

[N10] 链表节点定义
来源：http://dali.yangfankeji.com/Article/details/gtyoftlhsx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sysykeji.top/Article/details/gtdhygkvcu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cucudq.cn/Article/details/gtoxdejqqd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hnxiangtu.top/Article/details/gtezeydqzi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.fzhhl.top/Article/details/gtryyiuemo.html

Java: class Node { int v; Node next; }
来源：http://dali.guowangkeji.top/Article/details/gtzhokppyp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tianlin.xyz/Article/details/gtsilwlmsg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sysykeji.top/Article/details/gttvkscbbo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jiagoushi.top/Article/details/gttihruejo.html

[N11] 二叉树中序遍历
来源：http://dali.hammf.cn/Article/details/gtmkfckech.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xziqi.cn/Article/details/gtafzzsfcg.html

PHP:  // 手写递归函数
来源：http://dali.quarkkingdee.top/Article/details/gtsmfdsyxc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daria6918.cn/Article/details/gtlrpjoats.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuxming.cn/Article/details/gtpoeqziwm.html

Java: // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gtpgtmcwos.html

Go:   // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gtajnvmroi.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.redwolf501.top/Article/details/gtentnhstd.html

C#:   // 手写递归
来源：http://dali.ivvv.top/Article/details/gtqxmybvne.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.316326.xyz/Article/details/gtzxhrjcrs.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yanxiufei.cn/Article/details/gtxczjfgfn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shuidangran.top/Article/details/gtamyoiuhf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aibaodan.cn/Article/details/gtqhrhmelz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gogol.net.cn/Article/details/gtwcqbrnfz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gogol.net.cn/Article/details/gtmojrcisl.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ehwqpu.com/Article/details/gtblfrwzat.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinqigfzy.top/Article/details/gtwiytrbez.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dianchejie.cn/Article/details/gtblojrjou.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtnneaqeyf.html

O. 并发与异步
来源：http://dali.cheryme.top/Article/details/gtwhfzgorg.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtintoafuw.html

[O01] 启动一个线程
来源：http://dali.jyoumei.cn/Article/details/gtyhwdqhna.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ehwqpu.com/Article/details/gtezqbuqff.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gzhubu.top/Article/details/gtcdykfrfn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jqgufenzy.top/Article/details/gtyoxkquxn.html

TS:   // 同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpmrqolg.html

Java: new Thread(() -> f()).start()
来源：http://dali.hfpthk.cn/Article/details/gtozoigwvs.html

Go:   go f()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfjqhpqiq.html

Ruby: Thread.new { f }
来源：http://dali.hnqzz.top/Article/details/gtteqfofzk.html

C#:   Task.Run(() => F());
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdckqxkmw.html

[O02] 使用线程池
来源：http://dali.xziqi.cn/Article/details/gtcafxeyqo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hammf.cn/Article/details/gtrsifywgp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yonumen.top/Article/details/gttzxjqphp.html

JS:   // worker_threads 线程池
来源：http://dali.quarkkingdee.top/Article/details/gtawjejssi.html

TS:   // worker_threads 线程池
来源：http://dali.cheryme.top/Article/details/gtsotxexqd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.redwolf501.top/Article/details/gtqieimepq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.daxiang520.top/Article/details/gtormuhzgl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.bjfxy.top/Article/details/gtbddjvzpb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yangfankeji.com/Article/details/gtzzxhxlox.html

[O03] 加锁保护共享数据
来源：http://dali.jiagoushi.top/Article/details/gtlfufizwt.html

Py:   with lock: shared += 1
来源：http://dali.jlsjyb.cn/Article/details/gtsmfbxlqy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jianghu66.top/Article/details/gtqxwxzmoh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.daxiang520.top/Article/details/gtzfytmric.html

TS:   // 同 JS
来源：http://dali.svipenyu.cn/Article/details/gtmwgoudwz.html

Java: synchronized (this) { shared++; }
来源：http://dali.c1oappe.top/Article/details/gtvmmvggtv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.vqdsnc.cn/Article/details/gtdxpqbmez.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tian-w.cn/Article/details/gtbcwgxkbl.html

C#:   lock (gate) { shared++; }
来源：http://dali.nanxinkj.top/Article/details/gthoouxjdy.html

[O04] 定义异步函数并等待
来源：http://dali.ybcxt.top/Article/details/gtfddploqv.html

Py:   async def f():⏎    await g()
来源：http://dali.hnqzz.top/Article/details/gtphbzgyia.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenzaomai.com/Article/details/gtktrgxsoi.html

JS:   async function f() { await g(); }
来源：http://dali.yj202588.top/Article/details/gtstftozdp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gtfgtcswgk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yvedp.cn/Article/details/gtllloyvgg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nanxuanxn.top/Article/details/gtrjuqfnso.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hysaishi.cn/Article/details/gtcddmuflx.html

C#:   async Task F() { await G(); }
来源：http://dali.cashguo.top/Article/details/gtcnidetlo.html

[O05] 并发执行并等待全部完成
来源：http://dali.ivvv.top/Article/details/gtpyxzwbbg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnqzz.top/Article/details/gtlznbcxni.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.kuanghao11.cn/Article/details/gtxrtmwubb.html

JS:   await Promise.all(tasks)
来源：http://dali.yanxiufei.cn/Article/details/gtatynvcll.html

TS:   await Promise.all(tasks)
来源：http://dali.daria6918.cn/Article/details/gtasftqofx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yangfankeji.com/Article/details/gtwspuzcwx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.haohaochexian.top/Article/details/gtpugobvvk.html

Ruby: threads.map(&:join)
来源：http://dali.cashguo.top/Article/details/gteuwkrqqz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sxryk.cn/Article/details/gtikggqolo.html

[O06] 使用进程池
来源：http://dali.zhengqikj.top/Article/details/gtoffwgzlm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenlongwang.top/Article/details/gtqtnzfryf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zdqjudy.top/Article/details/gtzbgaiosr.html

JS:   // child_process / cluster 模块
来源：http://dali.chenlongwang.top/Article/details/gtczzsxxyj.html

TS:   // child_process / cluster 模块
来源：http://dali.ppjwa.cn/Article/details/gtfpwiflpb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.wangshuangyany.cn/Article/details/gtnrvfphdl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.pengpengdd.cyou/Article/details/gtnavtmxpp.html

Ruby: // fork 块
来源：http://dali.zycfv.cn/Article/details/gtmhmjdwto.html

C#:   Parallel.For
来源：http://dali.yangfankeji.com/Article/details/gtsunbzvbk.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtkarzmvgg.html

P. 常用工具函数
来源：http://dali.svipenyu.cn/Article/details/gtooomyykm.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gttnugxtrz.html

[P01] 生成 UUID
来源：http://dali.cqqwz.cn/Article/details/gtlwuhsrin.html

Py:   str(uuid.uuid4())
来源：http://dali.shangyingyoupin.top/Article/details/gtxvawtedq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.feifeiyinyue.top/Article/details/gtflwbmget.html

JS:   crypto.randomUUID()
来源：http://dali.jlsjyb.cn/Article/details/gtnwqfaohj.html

TS:   crypto.randomUUID()
来源：http://dali.dianchejie.cn/Article/details/gtrmdjpnvm.html

Java: UUID.randomUUID().toString()
来源：http://dali.sxryk.cn/Article/details/gtqgzqewkh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.mhx1999.top/Article/details/gtffqersbn.html

Ruby: SecureRandom.uuid
来源：http://dali.cheryme.top/Article/details/gtfzemkmom.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hammf.cn/Article/details/gtfllkokyb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.iojbl.cn/Article/details/gthykutqem.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nwbrower.top/Article/details/gtuniykilr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yueranfly.top/Article/details/gtcslryoys.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hysaishi.cn/Article/details/gtjqjsxsfm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sufxvd.cn/Article/details/gtcklpydde.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.smart0.xyz/Article/details/gtrurgsqrh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hongshengwenyu.top/Article/details/gtbjetduid.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jianghu66.top/Article/details/gtozrflitj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.kuanghao11.cn/Article/details/gtmmgvggql.html

[P03] 生成短随机字符串
来源：http://dali.yvedp.cn/Article/details/gtfemiugpf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.iojbl.cn/Article/details/gtroslfdke.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.dianchejie.cn/Article/details/gtluntkfrg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gtwaspygta.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnxiangtu.top/Article/details/gtenxdagwn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.bjfxy.top/Article/details/gtbmgjxxqu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zdqjudy.top/Article/details/gtjtpgjdnu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.daxiang520.top/Article/details/gtzxbjofqd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jiagoushi.top/Article/details/gtmbwqbzkq.html

[P04] 求长度
来源：http://dali.jiagoushi.top/Article/details/gthpdodhmk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.haohaochexian.top/Article/details/gtslfwichb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtykeelsmk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangshuangyany.cn/Article/details/gtfugidsna.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hongshengwenyu.top/Article/details/gtvojiauyd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jqgfzy.top/Article/details/gtaamxycca.html

Go:   len(arr);  len(m)
来源：http://dali.sxryk.cn/Article/details/gtmnwlnzje.html

Ruby: x.length;  x.size
来源：http://dali.shanyushiyangtech.top/Article/details/gtgtzkeykd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinqigufen.top/Article/details/gtkajflvuw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hnxiangtu.top/Article/details/gtpvfkvcaa.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.pengpengdd.cyou/Article/details/gtlwtnliex.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvvjnohmy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.guannengcc.top/Article/details/gtjeeeinym.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pycfn.com/Article/details/gtqfujhpjl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxtpdzqb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuccbfylj.html

Ruby: a == b
来源：http://dali.yongpay.top/Article/details/gthwggwwml.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xuanzx.com/Article/details/gtpsiovnoe.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.chenlongwang.top/Article/details/gtdqiffxce.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.bjfxy.top/Article/details/gtmuozxjxi.html

PHP:  if (empty($x)) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlernqouf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shanyushiyangtech.top/Article/details/gtcgtiisrb.html

TS:   if (x == null) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrxzfcjb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxioldmxc.html

Go:   if x == nil {}
来源：http://dali.shuidangran.top/Article/details/gtplghxizw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyakyxgjy.html

C#:   if (x is null) {}
来源：http://dali.haohaochexian.top/Article/details/gtfvuzacdv.html

[P07] 防抖与节流
来源：http://dali.havefunace.top/Article/details/gtnjvouwuw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.feifeiyinyue.top/Article/details/gtpcrvizcy.html

PHP:  // 手写时间戳比较
来源：http://dali.shangyingyoupin.top/Article/details/gtpsuhsklx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258888.top/Article/details/gtsyxlazpn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuanzhike.top/Article/details/gtdefocott.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.svipenyu.cn/Article/details/gtexjhvnel.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zdqjudy.top/Article/details/gtpnjrrkkl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yonumen.top/Article/details/gtijotuzzv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj202588.top/Article/details/gtgnuelwjx.html

[P08] 处理浮点精度问题
来源：http://dali.cdnleiting.top/Article/details/gtzmsyxnyj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinqigufen.top/Article/details/gtcqfisjmw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhengqikj.top/Article/details/gtspzvohau.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.wangshuangyany.cn/Article/details/gthginvyze.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hnqzz.top/Article/details/gtkomwther.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jiagoushi.top/Article/details/gtexasvpwg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhiwuduotai.top/Article/details/gtopqiljzw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinqigfzy.top/Article/details/gtqfisvhqe.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jianghu66.top/Article/details/gtvcsvdrvs.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtlqpccvhl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hfpthk.cn/Article/details/gtmevhtulp.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gttsucgrfm.html

[Q01] 创建表
来源：http://dali.kuanghao11.cn/Article/details/gthhoranje.html

CREATE TABLE users (
来源：http://dali.jlsjyb.cn/Article/details/gtzfyceckc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jianghu66.top/Article/details/gtflrpeezt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cdnleiting.top/Article/details/gtjgeskusg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.vqdsnc.cn/Article/details/gthnouqpsp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cashguo.top/Article/details/gtzqdnsrph.html

);
来源：http://dali.shzxlz.cn/Article/details/gtblpbvwmz.html

[Q02] 创建带外键的表
来源：http://dali.hnqzz.top/Article/details/gtjqidlnqr.html

CREATE TABLE orders (
来源：http://dali.yonumen.top/Article/details/gtokxpagyj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.smart0.xyz/Article/details/gtfjfdjfjo.html

user_id INT NOT NULL,
来源：http://dali.cucudq.cn/Article/details/gtlvprqleo.html

amount DECIMAL(10, 2),
来源：http://dali.zhongyouzk.top/Article/details/gtwajugrzd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhengqikj.top/Article/details/gtgwgopqwv.html

);
来源：http://dali.tanke756.top/Article/details/gtcdrgapfz.html

[Q03] 增加列
来源：http://dali.zhoulong.xyz/Article/details/gtadevratf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.vqdsnc.cn/Article/details/gtmybwvefp.html

[Q04] 修改列类型
来源：http://dali.cucudq.cn/Article/details/gtscyiujyk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjkhgukc.html

[Q05] 重命名列
来源：http://dali.jqgufenzy.top/Article/details/gtjuarqiuh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.aizwys.cn/Article/details/gtadtfkxvd.html

[Q06] 删除列
来源：http://dali.ydzc1.top/Article/details/gtytltyukc.html


<!-- 参考信息 -->