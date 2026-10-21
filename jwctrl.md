代发 wailian999

Java: public static void main(String[] args)
来源：http://dali.ydzc1.top/Article/details/gtirsbytfh.html

Go:   func main()
来源：http://dali.jianghu66.top/Article/details/gtgceenxwt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sxryk.cn/Article/details/gtxvtpaifi.html

C#:   static void Main(string[] args)
来源：http://dali.zhongyouzk.top/Article/details/gtmbjghfuu.html

[M08] 获取系统与运行时信息
来源：http://dali.sysykeji.top/Article/details/gtywamlomr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jiagoushi.top/Article/details/gtlvtfynxr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tian-w.cn/Article/details/gtidnhskdc.html

JS:   process.platform;  process.version
来源：http://dali.xuetiantiany.cn/Article/details/gtshmxmrci.html

TS:   process.platform;  process.version
来源：http://dali.hnqzz.top/Article/details/gtyvpwmsfa.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yanxiufei.cn/Article/details/gtkfsancqw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.vqdsnc.cn/Article/details/gtovoaxfbo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.c1oappe.top/Article/details/gtxwqnjjwz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.316326.xyz/Article/details/gtdfycuiey.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtworedgnq.html

N. 数据结构与算法
来源：http://dali.daxiang520.top/Article/details/gtpqflcyzf.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtzsezlnkl.html

[N01] 二分查找（有序数组）
来源：http://dali.sxryk.cn/Article/details/gtgwhonpgq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtkjyanavn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbduwfok.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gtqccruexk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guannengcc.top/Article/details/gtuzmuiaxc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtsifzpjvx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtzualztwq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.andypj.xyz/Article/details/gtkdkmnmas.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtlfexemvh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ydzc1.top/Article/details/gtejulcylj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.meibo888.top/Article/details/gtzfrsgijs.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hywenlv.cn/Article/details/gtcwnjsypk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gtklogijfv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ppjwa.cn/Article/details/gthvourmqc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xuetiantiany.cn/Article/details/gtslhbatpi.html

Go:   slices.Sort(arr)
来源：http://dali.fengsongda.top/Article/details/gtfwkkxzaf.html

Ruby: arr.sort
来源：http://dali.jyoumei.cn/Article/details/gtwijkhxun.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sxryk.cn/Article/details/gtewyfnybi.html

[N03] 快速排序（分治示例）
来源：http://dali.chenjidiqi.icu/Article/details/gtqabyswza.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hnxiangtu.top/Article/details/gtpcqssagv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hnxiangtu.top/Article/details/gtagdagdmr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.0kj1m.cn/Article/details/gtqfuhxdxw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tanke756.top/Article/details/gtfosefnvm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj20258888.top/Article/details/gtxchpbszg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gzhubu.top/Article/details/gtqfnrukmm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdxpxnucb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenzaomai.com/Article/details/gteaeexats.html

[N04] 斐波那契数列
来源：http://dali.zycfv.cn/Article/details/gttzknwfnv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ppjwa.cn/Article/details/gtnezcxgtc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj20258.top/Article/details/gttrarowuq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gtygnnczxt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gtxnifsymj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.andypj.xyz/Article/details/gtnzclfegh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xinyue.icu/Article/details/gtrbdhnggc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yanxiufei.cn/Article/details/gtnbesbirm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sweek.top/Article/details/gtwtuwbisv.html

[N05] 最大公约数
来源：http://dali.guannengcc.top/Article/details/gtnyxfpvlh.html

Py:   math.gcd(a, b)
来源：http://dali.c1oappe.top/Article/details/gtqxtfvfmq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.redwolf501.top/Article/details/gtvfzbwfwj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gtimxpxjhc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xziqi.cn/Article/details/gtsygioaed.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhengqikj.top/Article/details/gtiarjjnqh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daria6918.cn/Article/details/gtemadwipd.html

Ruby: a.gcd(b)
来源：http://dali.yj20258888.top/Article/details/gtpuvgyqsj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.nanxuanxn.top/Article/details/gtqpmkpvfz.html

[N06] 判断回文字符串
来源：http://dali.jqgufenzy.top/Article/details/gttjotsfym.html

Py:   s == s[::-1]
来源：http://dali.guowangkeji.top/Article/details/gtyddfufot.html

PHP:  $s === strrev($s);
来源：http://dali.nanxuanxn.top/Article/details/gtvqwhfdss.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtoiffnlvz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtqtbiwhjr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.birdmap.top/Article/details/gttiwsbtxp.html

Go:   // 双指针从两端比较
来源：http://dali.cheryme.top/Article/details/gttaslqjhb.html

Ruby: s == s.reverse
来源：http://dali.cheryme.top/Article/details/gtbxhsoecf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gttzjefdoi.html

[N07] 两数之和（返回下标）
来源：http://dali.andypj.xyz/Article/details/gtihljowgq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ppjwa.cn/Article/details/gtrmkmnfyg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sysykeji.top/Article/details/gtsiaxhols.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.daria6918.cn/Article/details/gthfputfvf.html

TS:   // 手写 Map<string, number>
来源：http://dali.smart0.xyz/Article/details/gtmmvybzsc.html

Java: // 手写 HashMap
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdrmygdl.html

Go:   // 手写 map[int]int
来源：http://dali.hnqzz.top/Article/details/gtyacnbryu.html

Ruby: // 手写 Hash
来源：http://dali.jqgfzy.top/Article/details/gtxptnfnqf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.feifeiyinyue.top/Article/details/gtwfmfjjgv.html

[N08] 生成全排列
来源：http://dali.sweek.top/Article/details/gtqnelwpkk.html

Py:   itertools.permutations(arr)
来源：http://dali.daxiang520.top/Article/details/gtnalyyztb.html

PHP:  // 手写递归交换
来源：http://dali.nanxuanxn.top/Article/details/gtoxxyjkrv.html

JS:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtsolqwofd.html

TS:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtfehdujav.html

Java: // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtldyhsmny.html

Go:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtypmycltr.html

Ruby: arr.permutation.to_a
来源：http://dali.gaohongyu789.top/Article/details/gtzbdabpnn.html

C#:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtxmjivhts.html

[N09] 栈与队列
来源：http://dali.zhongyouzk.top/Article/details/gtbhwaxzke.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtljvwwdud.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.guannengcc.top/Article/details/gtevfrhkyo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gtwyqvlomv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shangyingyoupin.top/Article/details/gtfzsocoqb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.9152youxi.cn/Article/details/gtihoxyjtf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.pengpengdd.cyou/Article/details/gtttnsfdcy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ydzc1.top/Article/details/gtqjtymadm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sweek.top/Article/details/gtbcisjqaq.html

[N10] 链表节点定义
来源：http://dali.zhixingplan.top/Article/details/gteivkxqnf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gtcxdyhgki.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jqgfzy.top/Article/details/gtbnhufcie.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.daria6918.cn/Article/details/gtkaviqmje.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yueranfly.top/Article/details/gtdhtsolls.html

Java: class Node { int v; Node next; }
来源：http://dali.0kj1m.cn/Article/details/gtgjbvrslz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hfpthk.cn/Article/details/gtetkovugq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinqigufen.top/Article/details/gtodxwhzhb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenjidiqi.icu/Article/details/gtbstveinc.html

[N11] 二叉树中序遍历
来源：http://dali.c1oappe.top/Article/details/gtlmqevuwn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.redwolf501.top/Article/details/gtonzlomtd.html

PHP:  // 手写递归函数
来源：http://dali.cashguo.top/Article/details/gtjbmpnxih.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.havefunace.top/Article/details/gtwmgzipuj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daria6918.cn/Article/details/gtidtrunpd.html

Java: // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gtuafrjndi.html

Go:   // 手写递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtrprxsvfx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.meibo888.top/Article/details/gtkssvydoi.html

C#:   // 手写递归
来源：http://dali.sxryk.cn/Article/details/gtimwjuwjb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sweek.top/Article/details/gtlrtaesug.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xylfe.cn/Article/details/gtpdgbwtey.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtljtzbyft.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfmixeczd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.mhx1999.top/Article/details/gtgihqfeym.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.iojbl.cn/Article/details/gttjiozzdz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cqqwz.cn/Article/details/gtbldoqdur.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.fengsongda.top/Article/details/gtweqquojj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nanxinkj.top/Article/details/gtqcyhutwe.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtwahdfqmi.html

O. 并发与异步
来源：http://dali.wangdashe.top/Article/details/gtowempezm.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtvvitthdr.html

[O01] 启动一个线程
来源：http://dali.dashuyun.cn/Article/details/gtpqtlwscu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.daria6918.cn/Article/details/gthevrxuon.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpsmosxb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xuetiantiany.cn/Article/details/gttnqqxvnk.html

TS:   // 同 JS
来源：http://dali.wangdashe.top/Article/details/gtsyfxgydv.html

Java: new Thread(() -> f()).start()
来源：http://dali.yonumen.top/Article/details/gtakkreqst.html

Go:   go f()
来源：http://dali.jianghu66.top/Article/details/gtadsoecic.html

Ruby: Thread.new { f }
来源：http://dali.nanxuanxn.top/Article/details/gtqvhwpegj.html

C#:   Task.Run(() => F());
来源：http://dali.gogol.net.cn/Article/details/gtknjzjska.html

[O02] 使用线程池
来源：http://dali.quarkkingdee.top/Article/details/gtzphcblhi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.daria6918.cn/Article/details/gtxlxdprnv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cashguo.top/Article/details/gtruloxnzg.html

JS:   // worker_threads 线程池
来源：http://dali.vqdsnc.cn/Article/details/gtselbcxvs.html

TS:   // worker_threads 线程池
来源：http://dali.dashuyun.cn/Article/details/gtcxjgerzc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gotoacloud.top/Article/details/gtxpdkqonm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinqigufen.top/Article/details/gtesttfsob.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gogol.net.cn/Article/details/gtrdqdlfrg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hongshengwenyu.top/Article/details/gthdwepocf.html

[O03] 加锁保护共享数据
来源：http://dali.316326.xyz/Article/details/gtpergekhm.html

Py:   with lock: shared += 1
来源：http://dali.9152youxi.cn/Article/details/gtlltmratx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ppjwa.cn/Article/details/gtyhymvres.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtigfypmrt.html

TS:   // 同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gtdaifrwqf.html

Java: synchronized (this) { shared++; }
来源：http://dali.sxryk.cn/Article/details/gtjgdzozhj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.fzhhl.top/Article/details/gtkhlpvgeq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.daxiang520.top/Article/details/gtopqripwg.html

C#:   lock (gate) { shared++; }
来源：http://dali.hnqzz.top/Article/details/gtmrwxthxi.html

[O04] 定义异步函数并等待
来源：http://dali.haohaochexian.top/Article/details/gtfcbxfxwj.html

Py:   async def f():⏎    await g()
来源：http://dali.sweek.top/Article/details/gtyzsfjblr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.mhx1999.top/Article/details/gtmydrtfcd.html

JS:   async function f() { await g(); }
来源：http://dali.yvedp.cn/Article/details/gtupwwxlce.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cashguo.top/Article/details/gtdwrikseq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.aizwys.cn/Article/details/gtutzulgkl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jiagoushi.top/Article/details/gtdgdxyqxy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.smart0.xyz/Article/details/gtrwnijkdf.html

C#:   async Task F() { await G(); }
来源：http://dali.cqqwz.cn/Article/details/gtwuatqenb.html

[O05] 并发执行并等待全部完成
来源：http://dali.9152youxi.cn/Article/details/gtyuxkmquu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ybcxt.top/Article/details/gtfacgfvud.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuouvibqt.html

JS:   await Promise.all(tasks)
来源：http://dali.guannengcc.top/Article/details/gtftvkpzon.html

TS:   await Promise.all(tasks)
来源：http://dali.xziqi.cn/Article/details/gtwccqjdug.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenjidiqi.icu/Article/details/gtcmckxqmz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gaohongyu789.top/Article/details/gtfszdswqr.html

Ruby: threads.map(&:join)
来源：http://dali.wangshuangyany.cn/Article/details/gtebjggsag.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ydzc1.top/Article/details/gtsaedmnmw.html

[O06] 使用进程池
来源：http://dali.daria6918.cn/Article/details/gtvldotdva.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.iojbl.cn/Article/details/gtqlhtzwbv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yj20258888.top/Article/details/gtlfwgkqfp.html

JS:   // child_process / cluster 模块
来源：http://dali.hnxiangtu.top/Article/details/gtudxvxeyy.html

TS:   // child_process / cluster 模块
来源：http://dali.sufxvd.cn/Article/details/gtltiygedj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.feifeiyinyue.top/Article/details/gtmzdyguap.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.daria6918.cn/Article/details/gtcyyptuuw.html

Ruby: // fork 块
来源：http://dali.ehwqpu.com/Article/details/gtxfcauszr.html

C#:   Parallel.For
来源：http://dali.havefunace.top/Article/details/gthfogsukt.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtstsocpbw.html

P. 常用工具函数
来源：http://dali.yj20258.top/Article/details/gtextxpdsg.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtzzpgmqde.html

[P01] 生成 UUID
来源：http://dali.snrcjt.cn/Article/details/gtiujaugff.html

Py:   str(uuid.uuid4())
来源：http://dali.shuidangran.top/Article/details/gtmyzgdown.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shzxlz.cn/Article/details/gtxsusfkks.html

JS:   crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gtunicwghj.html

TS:   crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gtmpkewasz.html

Java: UUID.randomUUID().toString()
来源：http://dali.aizwys.cn/Article/details/gtlyvxlxcw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nanxuanxn.top/Article/details/gtgyhehhso.html

Ruby: SecureRandom.uuid
来源：http://dali.yj20258888.top/Article/details/gtqpkxvffr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.c1oappe.top/Article/details/gtdbqiypoj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.9152youxi.cn/Article/details/gtatctuzle.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.smart0.xyz/Article/details/gtalasvtxe.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.andypj.xyz/Article/details/gtpjovcfdr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.redwolf501.top/Article/details/gtbkgjeeid.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yonumen.top/Article/details/gtipvtvcnh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yuxming.cn/Article/details/gtkenydeko.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.pengpengdd.cyou/Article/details/gtrggxtsjp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shuidangran.top/Article/details/gterradsuq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj202588.top/Article/details/gtbwfxojai.html

[P03] 生成短随机字符串
来源：http://dali.jyoumei.cn/Article/details/gtqfiyuavq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.guowangkeji.top/Article/details/gtucioqeid.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhengqikj.top/Article/details/gtkxpzlnpg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigfzy.top/Article/details/gtnxmwsaaq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jianghu66.top/Article/details/gteleewfup.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shzxlz.cn/Article/details/gtjvstrrnt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yvedp.cn/Article/details/gtkknczssd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yonumen.top/Article/details/gtsstjrrwe.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yuxming.cn/Article/details/gtetkcmwyu.html

[P04] 求长度
来源：http://dali.ehwqpu.com/Article/details/gtvwzaztzd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhengqikj.top/Article/details/gtljrbmpba.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gtnfkjkhlt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shangyingyoupin.top/Article/details/gtirqqtprl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zdqjudy.top/Article/details/gtzzgnrlea.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sufxvd.cn/Article/details/gtximhtblj.html

Go:   len(arr);  len(m)
来源：http://dali.gzhubu.top/Article/details/gtnisnsgqa.html

Ruby: x.length;  x.size
来源：http://dali.aizwys.cn/Article/details/gtyubkabnt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ppjwa.cn/Article/details/gtwxqzgpal.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yueranfly.top/Article/details/gtdszuhwqw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gotoacloud.top/Article/details/gtkwnyyuss.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gzhubu.top/Article/details/gtaibedqfb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jyoumei.cn/Article/details/gtkzbslohr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gaohongyu789.top/Article/details/gtkeiutggu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.nwbrower.top/Article/details/gtubtzgxxv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gtnmzpsomx.html

Ruby: a == b
来源：http://dali.hnqzz.top/Article/details/gtjeelnusw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.quarkkingdee.top/Article/details/gtyazdixyv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sweek.top/Article/details/gtohxhewan.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.fengsongda.top/Article/details/gtuxasjlps.html

PHP:  if (empty($x)) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtqnjerltk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.kuanghao11.cn/Article/details/gtlmzguwsm.html

TS:   if (x == null) {}
来源：http://dali.redwolf501.top/Article/details/gtdsejhfdu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shzxlz.cn/Article/details/gtpctbohvq.html

Go:   if x == nil {}
来源：http://dali.yuanzhike.top/Article/details/gthlnziznv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.aibaodan.cn/Article/details/gtmnleyaou.html

C#:   if (x is null) {}
来源：http://dali.cheryme.top/Article/details/gttzbecnel.html

[P07] 防抖与节流
来源：http://dali.chenzaomai.com/Article/details/gtsjywwgjn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xziqi.cn/Article/details/gtczjnkatx.html

PHP:  // 手写时间戳比较
来源：http://dali.c1oappe.top/Article/details/gtkspbrzsr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.haohaochexian.top/Article/details/gtwdlnytpp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabbmzwhc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.guannengcc.top/Article/details/gtngjfuztn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gzhubu.top/Article/details/gtinngpnhw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.chenzaomai.com/Article/details/gtysdujooi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yuxming.cn/Article/details/gtvlcpiows.html

[P08] 处理浮点精度问题
来源：http://dali.dashuyun.cn/Article/details/gtzczkiygj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.wangshuangyany.cn/Article/details/gtxpmhshyj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hywenlv.cn/Article/details/gttyqrrxre.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jianghu66.top/Article/details/gtlgndravb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.meibo888.top/Article/details/gtqqpnrfzs.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.fzhhl.top/Article/details/gtxtgahtlq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinghuilouyu.cn/Article/details/gttvcsesop.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hfpthk.cn/Article/details/gtbmmytwjy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.aizwys.cn/Article/details/gtxktkcazk.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtzwlxjmvc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.316326.xyz/Article/details/gtkizyutot.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtrkudfnui.html

[Q01] 创建表
来源：http://dali.aizwys.cn/Article/details/gtucijijzb.html

CREATE TABLE users (
来源：http://dali.c1oappe.top/Article/details/gtvtknmwvq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhiwuduotai.top/Article/details/gtsucdmpst.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shanyushiyangtech.top/Article/details/gtjyxmxhri.html

email VARCHAR(100) UNIQUE,
来源：http://dali.9152youxi.cn/Article/details/gtthhdmkey.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoaoqyzqw.html

);
来源：http://dali.316326.xyz/Article/details/gtureupwvu.html

[Q02] 创建带外键的表
来源：http://dali.hfpthk.cn/Article/details/gtsyphvtwr.html

CREATE TABLE orders (
来源：http://dali.tanke756.top/Article/details/gtwhcjzdka.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnxiangtu.top/Article/details/gtjitumwgf.html

user_id INT NOT NULL,
来源：http://dali.nanxinkj.top/Article/details/gtghjbktsr.html

amount DECIMAL(10, 2),
来源：http://dali.316326.xyz/Article/details/gtdizdpttb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cashguo.top/Article/details/gtcxpzactd.html

);
来源：http://dali.jlsjyb.cn/Article/details/gtzpqyxdpg.html

[Q03] 增加列
来源：http://dali.yj20258.top/Article/details/gtoobwepor.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.bjfxy.top/Article/details/gtpmwkmnkg.html

[Q04] 修改列类型
来源：http://dali.pycfn.com/Article/details/gtjoeffnwc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj20258.top/Article/details/gtijgwujta.html

[Q05] 重命名列
来源：http://dali.zhongyouzk.top/Article/details/gtxlusgrwo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ydzc1.top/Article/details/gtjqpzqyzm.html

[Q06] 删除列
来源：http://dali.xuanzx.com/Article/details/gtumufybxq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tianlin.xyz/Article/details/gteesqjuoz.html

[Q07] 删除表
来源：http://dali.shangyingyoupin.top/Article/details/gtwssqglbh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yonumen.top/Article/details/gtfexwyuxl.html

[Q08] 创建普通索引
来源：http://dali.jyoumei.cn/Article/details/gtxgcmigzn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.andypj.xyz/Article/details/gteorklpaw.html

[Q09] 创建唯一索引
来源：http://dali.guannengcc.top/Article/details/gthwrravfg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sysykeji.top/Article/details/gtmeedznum.html

[Q10] 插入单行
来源：http://dali.tianlin.xyz/Article/details/gtsrbmqaky.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoddejwlx.html

[Q11] 一次插入多行
来源：http://dali.zhiwuduotai.top/Article/details/gtywornzfc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhengqikj.top/Article/details/gtwzmwcbtn.html

[Q12] 插入后取自增 ID
来源：http://dali.shzxlz.cn/Article/details/gtftueglaj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tianlin.xyz/Article/details/gtsojmswpd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.wangdashe.top/Article/details/gtwmiraofs.html

[Q13] 忽略重复插入
来源：http://dali.cheryme.top/Article/details/gtmwzaogfa.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj20258.top/Article/details/gteiqzeocy.html

[Q14] 存在则更新（upsert）
来源：http://dali.hywenlv.cn/Article/details/gtdbnrunzn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jqgfzy.top/Article/details/gtbepzkdce.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yueranfly.top/Article/details/gtscshzpiw.html

[Q15] 查询全部
来源：http://dali.daria6918.cn/Article/details/gtmbflhzhj.html


<!-- 参考信息 -->