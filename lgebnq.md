代发 wailian999

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ydzc1.top/Article/details/gtflzkhmlw.html

JS:   console.error("err")
来源：http://dali.sweek.top/Article/details/gtsxlfidhw.html

TS:   console.error("err")
来源：http://dali.sweek.top/Article/details/gtmojqmtcv.html

Java: System.err.println("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwxcszhk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.birdmap.top/Article/details/gtxbuulwwk.html

Ruby: warn "err"
来源：http://dali.jlsjyb.cn/Article/details/gtohmazkim.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.daria6918.cn/Article/details/gtkynvocks.html

[M07] 判断是否为主入口
来源：http://dali.hongshengwenyu.top/Article/details/gtvwcdomln.html

Py:   if __name__ == "__main__":
来源：http://dali.snrcjt.cn/Article/details/gtzjfybpxy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.fengsongda.top/Article/details/gtkvtudmdv.html

JS:   require.main === module
来源：http://dali.yvedp.cn/Article/details/gtbagajqgh.html

TS:   require.main === module
来源：http://dali.sweek.top/Article/details/gtaxrqtbpm.html

Java: public static void main(String[] args)
来源：http://dali.jqgufenzy.top/Article/details/gtgmryshjz.html

Go:   func main()
来源：http://dali.hammf.cn/Article/details/gtzhgfaisi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ydzc1.top/Article/details/gtvtkcckex.html

C#:   static void Main(string[] args)
来源：http://dali.daria6918.cn/Article/details/gtlxdmtirj.html

[M08] 获取系统与运行时信息
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdgfxbpp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.meibo888.top/Article/details/gtfyegkvml.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabkcvceu.html

JS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gtxoavljoi.html

TS:   process.platform;  process.version
来源：http://dali.jiagoushi.top/Article/details/gtikpllsfl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.birdmap.top/Article/details/gtxoegaeok.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj20258888.top/Article/details/gtnpyocjdg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fzhhl.top/Article/details/gtgxqiaybi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.quarkkingdee.top/Article/details/gtkyrcegdd.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtstjmqgks.html

N. 数据结构与算法
来源：http://dali.andypj.xyz/Article/details/gthvtcemqf.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtcyiiczzo.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigfzy.top/Article/details/gtymksvrel.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtdrxsfxim.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhixingplan.top/Article/details/gtrfvinzdz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gtopolekwm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gtkmezntnd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtuiourmoe.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtgetymimz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yueranfly.top/Article/details/gtejmzrbtj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtpacenaxw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhiwuduotai.top/Article/details/gtjiobzurr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.mhx1999.top/Article/details/gtiznvmwmf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yanxiufei.cn/Article/details/gtvjesbzlk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gtlcipiqex.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gtwoftzgsu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shuidangran.top/Article/details/gtarhntiza.html

Go:   slices.Sort(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtlgwwtciv.html

Ruby: arr.sort
来源：http://dali.zhixingplan.top/Article/details/gtqgwjgcqr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.dianchejie.cn/Article/details/gtzizxxfuv.html

[N03] 快速排序（分治示例）
来源：http://dali.xuetiantiany.cn/Article/details/gtpxcspvlo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yueranfly.top/Article/details/gtvvhidxfy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jqgufenzy.top/Article/details/gtxgwakdmc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrznyiuj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.svipenyu.cn/Article/details/gtosqmanmh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj20258.top/Article/details/gtevywfxug.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yvedp.cn/Article/details/gtrcmgjadc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xylfe.cn/Article/details/gtczgrajvn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangdashe.top/Article/details/gtephyscne.html

[N04] 斐波那契数列
来源：http://dali.cashguo.top/Article/details/gtzheombli.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xinyue.icu/Article/details/gtvbcvpgow.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ivvv.top/Article/details/gtoimfchpu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cqqwz.cn/Article/details/gtepqzdxps.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.smart0.xyz/Article/details/gtvtuzjgvi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jyoumei.cn/Article/details/gtekkzvpex.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.vqdsnc.cn/Article/details/gtwdkjffpo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtmtyaiiub.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gtizjvgqia.html

[N05] 最大公约数
来源：http://dali.xuetiantiany.cn/Article/details/gtyxnrcyqx.html

Py:   math.gcd(a, b)
来源：http://dali.tian-w.cn/Article/details/gttpoqmhru.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.wangdashe.top/Article/details/gtneujsxii.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tian-w.cn/Article/details/gtspsxxnsh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ydzc1.top/Article/details/gtssvhkign.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenzaomai.com/Article/details/gtjqwhndfs.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aizwys.cn/Article/details/gtsjewfrns.html

Ruby: a.gcd(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtazkzyvri.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinqigufen.top/Article/details/gtvgyyieko.html

[N06] 判断回文字符串
来源：http://dali.hammf.cn/Article/details/gtonptiakj.html

Py:   s == s[::-1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiehvelep.html

PHP:  $s === strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkxfohmju.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtdybafcuf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtuujjrmqy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhongyouzk.top/Article/details/gttxuoqndk.html

Go:   // 双指针从两端比较
来源：http://dali.hnqzz.top/Article/details/gtkjvoenqx.html

Ruby: s == s.reverse
来源：http://dali.snrcjt.cn/Article/details/gtxppwziwo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hysaishi.cn/Article/details/gtpjfrlegu.html

[N07] 两数之和（返回下标）
来源：http://dali.haohaochexian.top/Article/details/gtolhguung.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.dianchejie.cn/Article/details/gtsthtjdjx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.birdmap.top/Article/details/gtvhflqegv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jiagoushi.top/Article/details/gtdjfqhiue.html

TS:   // 手写 Map<string, number>
来源：http://dali.hnqzz.top/Article/details/gtowamffey.html

Java: // 手写 HashMap
来源：http://dali.yj202588.top/Article/details/gtteuobrft.html

Go:   // 手写 map[int]int
来源：http://dali.jinghuilouyu.cn/Article/details/gttqwyjvad.html

Ruby: // 手写 Hash
来源：http://dali.fzhhl.top/Article/details/gtpqxiiplx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tanke756.top/Article/details/gtpobsjulv.html

[N08] 生成全排列
来源：http://dali.yuanzhike.top/Article/details/gtbegcifts.html

Py:   itertools.permutations(arr)
来源：http://dali.cqqwz.cn/Article/details/gtkpcjoohk.html

PHP:  // 手写递归交换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthftzknkx.html

JS:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtdyibwucl.html

TS:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtigltrzyj.html

Java: // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtvlojsxhj.html

Go:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtzrsnrrto.html

Ruby: arr.permutation.to_a
来源：http://dali.shzxlz.cn/Article/details/gtnrmbrceb.html

C#:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtkeooodfr.html

[N09] 栈与队列
来源：http://dali.hnqzz.top/Article/details/gtkjqvojme.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.svipenyu.cn/Article/details/gtvwqphiyg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gtuvmczsla.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ppjwa.cn/Article/details/gtmscqkzzd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jqgufenzy.top/Article/details/gtokygzmwz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xuanzx.com/Article/details/gtkribdldv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwmoslxhj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.daxiang520.top/Article/details/gtdzfioxbt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yanxiufei.cn/Article/details/gtmthdoicu.html

[N10] 链表节点定义
来源：http://dali.jiagoushi.top/Article/details/gtbwzwdpxe.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.quarkkingdee.top/Article/details/gtrobuvbgi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ehwqpu.com/Article/details/gtuxrprbis.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tanke756.top/Article/details/gtvvxjzcgq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dashuyun.cn/Article/details/gthufuekpq.html

Java: class Node { int v; Node next; }
来源：http://dali.hammf.cn/Article/details/gtprznfosj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tian-w.cn/Article/details/gtixfvvada.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.9152youxi.cn/Article/details/gtwpidggmp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shzxlz.cn/Article/details/gtqmfrbqjp.html

[N11] 二叉树中序遍历
来源：http://dali.tanke756.top/Article/details/gtcxjzhwri.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xuanzx.com/Article/details/gtpnlseyld.html

PHP:  // 手写递归函数
来源：http://dali.jqgufenzy.top/Article/details/gtnxcsaoqq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj202588.top/Article/details/gtsiycwdbm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xziqi.cn/Article/details/gtckepmeap.html

Java: // 手写递归
来源：http://dali.pycfn.com/Article/details/gtkslqoxpg.html

Go:   // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gtlmhpigbj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenjidiqi.icu/Article/details/gtkhnaomvo.html

C#:   // 手写递归
来源：http://dali.pycfn.com/Article/details/gtmsqwwlcf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdpznifx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.dashuyun.cn/Article/details/gtutgufwbe.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yueranfly.top/Article/details/gtudmyirmi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zycfv.cn/Article/details/gtmhdrklpc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.9152youxi.cn/Article/details/gtgpxymuji.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cdnleiting.top/Article/details/gtgraiuhww.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.pycfn.com/Article/details/gtarlmvpyc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinqigufen.top/Article/details/gtxkrkspwq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sufxvd.cn/Article/details/gtutsbutfr.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtnzfbsnel.html

O. 并发与异步
来源：http://dali.sxryk.cn/Article/details/gtctibrixs.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtejgckmyi.html

[O01] 启动一个线程
来源：http://dali.chenlongwang.top/Article/details/gtdpmzqqkb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.havefunace.top/Article/details/gtybvgzorq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jqgufenzy.top/Article/details/gtoomutbpk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tian-w.cn/Article/details/gtwiyxlhmy.html

TS:   // 同 JS
来源：http://dali.jqgfzy.top/Article/details/gtmmarbyqc.html

Java: new Thread(() -> f()).start()
来源：http://dali.ybcxt.top/Article/details/gtyrjdsiqd.html

Go:   go f()
来源：http://dali.chenzaomai.com/Article/details/gtufazxfml.html

Ruby: Thread.new { f }
来源：http://dali.meibo888.top/Article/details/gtjwqngzkp.html

C#:   Task.Run(() => F());
来源：http://dali.cheryme.top/Article/details/gtujwozhpz.html

[O02] 使用线程池
来源：http://dali.hywenlv.cn/Article/details/gtszbltwab.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.pengpengdd.cyou/Article/details/gtqsfytjtn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jqgfzy.top/Article/details/gthhazlqet.html

JS:   // worker_threads 线程池
来源：http://dali.dashuyun.cn/Article/details/gtuqgbabsp.html

TS:   // worker_threads 线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtidwojwkz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.quarkkingdee.top/Article/details/gtzpvyjajn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cqqwz.cn/Article/details/gtashsvfap.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.svipenyu.cn/Article/details/gtpuistidw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.dashuyun.cn/Article/details/gtkngqntro.html

[O03] 加锁保护共享数据
来源：http://dali.sweek.top/Article/details/gttazjstif.html

Py:   with lock: shared += 1
来源：http://dali.bjfxy.top/Article/details/gtzadwpwpm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cqqwz.cn/Article/details/gtduzfffvt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gotoacloud.top/Article/details/gtpjvjuaau.html

TS:   // 同 JS
来源：http://dali.0kj1m.cn/Article/details/gthhvchoko.html

Java: synchronized (this) { shared++; }
来源：http://dali.hywenlv.cn/Article/details/gtvyikqchd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cdnleiting.top/Article/details/gtcbrcwvno.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtckgcqxjs.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinqigfzy.top/Article/details/gteqlgjdlh.html

[O04] 定义异步函数并等待
来源：http://dali.daria6918.cn/Article/details/gtoslthdjj.html

Py:   async def f():⏎    await g()
来源：http://dali.daxiang520.top/Article/details/gtwmdecegs.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenzaomai.com/Article/details/gthzsavdln.html

JS:   async function f() { await g(); }
来源：http://dali.ydzc1.top/Article/details/gtrloxdoik.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nanxuanxn.top/Article/details/gttlzlbrul.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shzxlz.cn/Article/details/gtyoyzdqys.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.pengpengdd.cyou/Article/details/gtkwmmevot.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nwbrower.top/Article/details/gttbncksnu.html

C#:   async Task F() { await G(); }
来源：http://dali.jqgfzy.top/Article/details/gtensmexnm.html

[O05] 并发执行并等待全部完成
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdptllci.html

Py:   asyncio.gather(*tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gtwebocqyk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hnxiangtu.top/Article/details/gtruyfzolx.html

JS:   await Promise.all(tasks)
来源：http://dali.zdqjudy.top/Article/details/gtazgfxuoc.html

TS:   await Promise.all(tasks)
来源：http://dali.nwbrower.top/Article/details/gtzhirbxfa.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.feifeiyinyue.top/Article/details/gtjzavykss.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrxxaeno.html

Ruby: threads.map(&:join)
来源：http://dali.c1oappe.top/Article/details/gtxbwsrltd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hywenlv.cn/Article/details/gtcgpdaaju.html

[O06] 使用进程池
来源：http://dali.bjfxy.top/Article/details/gturcavyps.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ppjwa.cn/Article/details/gtqvmwaupk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hysaishi.cn/Article/details/gtbqpptfqg.html

JS:   // child_process / cluster 模块
来源：http://dali.yj20258.top/Article/details/gtprjllcep.html

TS:   // child_process / cluster 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gthrpsfysq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sweek.top/Article/details/gtbyjmgomg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrrbkqgnh.html

Ruby: // fork 块
来源：http://dali.fzhhl.top/Article/details/gtrnggtmsc.html

C#:   Parallel.For
来源：http://dali.sweek.top/Article/details/gttaupropx.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtpidxoawg.html

P. 常用工具函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtzisykzvf.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtuphpobpc.html

[P01] 生成 UUID
来源：http://dali.kuanghao11.cn/Article/details/gtubqtjeso.html

Py:   str(uuid.uuid4())
来源：http://dali.nanxinkj.top/Article/details/gtewmusifo.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinqigfzy.top/Article/details/gtvnvxgfen.html

JS:   crypto.randomUUID()
来源：http://dali.xziqi.cn/Article/details/gtcchmzbvs.html

TS:   crypto.randomUUID()
来源：http://dali.xinyue.icu/Article/details/gtisxkpnhk.html

Java: UUID.randomUUID().toString()
来源：http://dali.dashuyun.cn/Article/details/gtialzjzgf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cdnleiting.top/Article/details/gtohnogfiy.html

Ruby: SecureRandom.uuid
来源：http://dali.yuxming.cn/Article/details/gtchnbxmsf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhoulong.xyz/Article/details/gtfrgpfnfi.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj20258.top/Article/details/gtniddqrdl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ivvv.top/Article/details/gtrjoagzen.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gtzkryyora.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shuidangran.top/Article/details/gtfwvqrxqg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tianlin.xyz/Article/details/gtomghjzcc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gogol.net.cn/Article/details/gtcmcsuylx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yueranfly.top/Article/details/gtkoyyjuwi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxuanxn.top/Article/details/gtmbquzoyd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.feifeiyinyue.top/Article/details/gtofowyttx.html

[P03] 生成短随机字符串
来源：http://dali.nwbrower.top/Article/details/gtvafiosxa.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yonumen.top/Article/details/gtjtxtcrcn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ehwqpu.com/Article/details/gtvpemgirr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hysaishi.cn/Article/details/gtkwwcwtzy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gotoacloud.top/Article/details/gtwwhqsdhw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gaohongyu789.top/Article/details/gtfimfaimy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xuanzx.com/Article/details/gtwbthfcak.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.mhx1999.top/Article/details/gtinyfplvp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.haohaochexian.top/Article/details/gthxpgmuzt.html

[P04] 求长度
来源：http://dali.hnxiangtu.top/Article/details/gtncrveiba.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shzxlz.cn/Article/details/gtrobbefdi.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtgcplggec.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.snrcjt.cn/Article/details/gtdxrzxjno.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yongpay.top/Article/details/gtvvfrrmtg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guowangkeji.top/Article/details/gtkytkvmsx.html

Go:   len(arr);  len(m)
来源：http://dali.ppjwa.cn/Article/details/gthijaxyqm.html

Ruby: x.length;  x.size
来源：http://dali.pengpengdd.cyou/Article/details/gtkomooqhs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hammf.cn/Article/details/gthajnqioh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nanxuanxn.top/Article/details/gtajcgpxmz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.birdmap.top/Article/details/gtvtnhdixy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yvedp.cn/Article/details/gthcfnxbhs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jqgufenzy.top/Article/details/gtuqpcqkua.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hywenlv.cn/Article/details/gtttqjzjoq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj20258.top/Article/details/gttatocftw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.meibo888.top/Article/details/gtpqptjtvj.html

Ruby: a == b
来源：http://dali.jinghuilouyu.cn/Article/details/gtitzrkwtk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.pengpengdd.cyou/Article/details/gtjyepclqj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.birdmap.top/Article/details/gtebvfnnfv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.sxryk.cn/Article/details/gtymknvjcl.html

PHP:  if (empty($x)) {}
来源：http://dali.birdmap.top/Article/details/gtcwfjehxo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zycfv.cn/Article/details/gtydeqqpoh.html

TS:   if (x == null) {}
来源：http://dali.jlsjyb.cn/Article/details/gtnupidnji.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.bjfxy.top/Article/details/gtucsdtcbu.html

Go:   if x == nil {}
来源：http://dali.yongpay.top/Article/details/gtcgcjjvao.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygheervr.html

C#:   if (x is null) {}
来源：http://dali.jyoumei.cn/Article/details/gtvoydwigk.html

[P07] 防抖与节流
来源：http://dali.xziqi.cn/Article/details/gtvauutbtn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.redwolf501.top/Article/details/gtprxkuuws.html

PHP:  // 手写时间戳比较
来源：http://dali.jinghuilouyu.cn/Article/details/gterhbtnsc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gtrqekkxyk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pengpengdd.cyou/Article/details/gtgqdvynmp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yvedp.cn/Article/details/gtvdrfhifj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hongshengwenyu.top/Article/details/gtfqrkvgxw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.aizwys.cn/Article/details/gtcfgjeazz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xuetiantiany.cn/Article/details/gtspcoxqxp.html

[P08] 处理浮点精度问题
来源：http://dali.fzhhl.top/Article/details/gtraaeutol.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenjidiqi.icu/Article/details/gtgsefvixh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sufxvd.cn/Article/details/gtvrocltkc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ybcxt.top/Article/details/gtidbflwqj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.quarkkingdee.top/Article/details/gtxrgbiqpq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.0kj1m.cn/Article/details/gtmobmdtcx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nanxinkj.top/Article/details/gtpnrwovme.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenzaomai.com/Article/details/gtmpaftlkt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gtceaxnnbt.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwocwjcoa.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj202588.top/Article/details/gtccdildoq.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtbvrqolew.html

[Q01] 创建表
来源：http://dali.svipenyu.cn/Article/details/gtvimpbija.html

CREATE TABLE users (
来源：http://dali.cqqwz.cn/Article/details/gtmznpasul.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shuidangran.top/Article/details/gtjbewakia.html

name VARCHAR(50) NOT NULL,
来源：http://dali.daria6918.cn/Article/details/gteiezpwif.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yvedp.cn/Article/details/gtedyjflzc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yangfankeji.com/Article/details/gtgwadltmn.html

);
来源：http://dali.ydzc1.top/Article/details/gtbasgdnbj.html

[Q02] 创建带外键的表
来源：http://dali.cashguo.top/Article/details/gtafhtqiat.html

CREATE TABLE orders (
来源：http://dali.zhengqikj.top/Article/details/gtdvihtddu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuanzhike.top/Article/details/gtgtqatlmb.html

user_id INT NOT NULL,
来源：http://dali.cqqwz.cn/Article/details/gtfebbtfpo.html

amount DECIMAL(10, 2),
来源：http://dali.nanxinkj.top/Article/details/gtnxvcpkyx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.guowangkeji.top/Article/details/gtqehdrcgw.html

);
来源：http://dali.cqqwz.cn/Article/details/gtebglpnun.html

[Q03] 增加列
来源：http://dali.hfpthk.cn/Article/details/gtaosjzlyd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrndexxz.html

[Q04] 修改列类型
来源：http://dali.wangdashe.top/Article/details/gtcdwrfwgc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenlongwang.top/Article/details/gtywwqlgoy.html

[Q05] 重命名列
来源：http://dali.wangshuangyany.cn/Article/details/gtvcrrsxjr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.tanke756.top/Article/details/gtkenukygn.html

[Q06] 删除列
来源：http://dali.chenjidiqi.icu/Article/details/gtllxyapjc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhongyouzk.top/Article/details/gtnbkvrugo.html

[Q07] 删除表
来源：http://dali.ppjwa.cn/Article/details/gtvawtaoqq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.mhx1999.top/Article/details/gtbledfkyb.html

[Q08] 创建普通索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthzarmmmb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenjidiqi.icu/Article/details/gtkxaqfpvo.html

[Q09] 创建唯一索引
来源：http://dali.zhoulong.xyz/Article/details/gtyshzihhh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gtfldcnaci.html

[Q10] 插入单行
来源：http://dali.andypj.xyz/Article/details/gtxybffepe.html


<!-- 参考信息 -->