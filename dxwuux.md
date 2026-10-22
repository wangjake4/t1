代发 wailian999

Java: public static void main(String[] args)
来源：http://dali.iojbl.cn/Article/details/gt2lqgfnuoa.html

Go:   func main()
来源：http://dali.cdnleiting.top/Article/details/gt2nvkaikqs.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.meibo888.top/Article/details/gt2zyahzevd.html

C#:   static void Main(string[] args)
来源：http://dali.xziqi.cn/Article/details/gt2mgvfrnjr.html

[M08] 获取系统与运行时信息
来源：http://dali.hnxiangtu.top/Article/details/gt2gpcldibx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.mhx1999.top/Article/details/gt2qjrcsorh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.andypj.xyz/Article/details/gt2vxhzlrhp.html

JS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gt2jmmtzrcy.html

TS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gt2izvkpszg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gotoacloud.top/Article/details/gt2vcbjnhnd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.haohaochexian.top/Article/details/gt2hwgqmvih.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sysykeji.top/Article/details/gt2xuywvqvi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.daria6918.cn/Article/details/gt2rzqwivhc.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2sceswgko.html

N. 数据结构与算法
来源：http://dali.hfpthk.cn/Article/details/gt2gnmflatq.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2biujutwt.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgfzy.top/Article/details/gt2rxmcropc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gt2nkvnmric.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinqigufen.top/Article/details/gt2awuakmbc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jianghu66.top/Article/details/gt2elnnvcrp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gt2jiwvidcb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gt2cwygitcl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gzhubu.top/Article/details/gt2repwfmai.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shangyingyoupin.top/Article/details/gt2mkjmntpm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zycfv.cn/Article/details/gt2kwhhprbq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yongpay.top/Article/details/gt2iwstdlfs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gt2tsgjmlkl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.birdmap.top/Article/details/gt2hjaweydi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gt2xmhtufdx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cheryme.top/Article/details/gt2mqttswly.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hysaishi.cn/Article/details/gt2pyckxanp.html

Go:   slices.Sort(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2mwyezkxa.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gt2lcohyago.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vtxjlvtf.html

[N03] 快速排序（分治示例）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hrsnioqp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tanke756.top/Article/details/gt2qiuqogsv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.quarkkingdee.top/Article/details/gt2yxxydnhm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xziqi.cn/Article/details/gt2wplpvmdr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhengqikj.top/Article/details/gt2ybbfkvba.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yvedp.cn/Article/details/gt2tuxdpbps.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.guowangkeji.top/Article/details/gt2vakzylsq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.316326.xyz/Article/details/gt2iejwbpqx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpruabr.html

[N04] 斐波那契数列
来源：http://dali.cashguo.top/Article/details/gt2mevcugwp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gzhubu.top/Article/details/gt2bmskizrm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gt2bszswact.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gt2iavhlseb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gt2bfekefcl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.c1oappe.top/Article/details/gt2ipukfafc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zdqjudy.top/Article/details/gt2wogmasmj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2bigrdbpj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kylahxxy.html

[N05] 最大公约数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kfijhwex.html

Py:   math.gcd(a, b)
来源：http://dali.cqqwz.cn/Article/details/gt2dzfaimmk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yvedp.cn/Article/details/gt2jnptpqdx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.birdmap.top/Article/details/gt2dyyrypnt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guowangkeji.top/Article/details/gt2vtcjhwmb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.snrcjt.cn/Article/details/gt2bedeytlt.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.redwolf501.top/Article/details/gt2fsfrbwda.html

Ruby: a.gcd(b)
来源：http://dali.hfpthk.cn/Article/details/gt2fsmwrmjp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yj20258.top/Article/details/gt2bjmljdrs.html

[N06] 判断回文字符串
来源：http://dali.yuxming.cn/Article/details/gt2kizjgtuf.html

Py:   s == s[::-1]
来源：http://dali.316326.xyz/Article/details/gt2xfqvkpwp.html

PHP:  $s === strrev($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2goheczli.html

JS:   s === [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gt2azstwsns.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gt2toqesfhj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hnqzz.top/Article/details/gt2axealhhq.html

Go:   // 双指针从两端比较
来源：http://dali.bjfxy.top/Article/details/gt2lpbseoxs.html

Ruby: s == s.reverse
来源：http://dali.xuanzx.com/Article/details/gt2hcmayfan.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj202588.top/Article/details/gt2ykwjzshe.html

[N07] 两数之和（返回下标）
来源：http://dali.wangshuangyany.cn/Article/details/gt2odkpuprn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ydzc1.top/Article/details/gt2alststsi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sxryk.cn/Article/details/gt2bwqxygjq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.aizwys.cn/Article/details/gt2ljjogcjp.html

TS:   // 手写 Map<string, number>
来源：http://dali.cucudq.cn/Article/details/gt2lolewbfw.html

Java: // 手写 HashMap
来源：http://dali.feifeiyinyue.top/Article/details/gt2jpdrhtpb.html

Go:   // 手写 map[int]int
来源：http://dali.tian-w.cn/Article/details/gt2dhuqrjxh.html

Ruby: // 手写 Hash
来源：http://dali.tanke756.top/Article/details/gt2rcmxpyin.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vrswxjfe.html

[N08] 生成全排列
来源：http://dali.kuanghao11.cn/Article/details/gt2rmhbsbcn.html

Py:   itertools.permutations(arr)
来源：http://dali.yuxming.cn/Article/details/gt2cxqpkows.html

PHP:  // 手写递归交换
来源：http://dali.hammf.cn/Article/details/gt2efprqjeq.html

JS:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gt2zojvmnqm.html

TS:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gt2wuhjzhkh.html

Java: // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gt2vppscfnh.html

Go:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gt2xcydptix.html

Ruby: arr.permutation.to_a
来源：http://dali.xuanzx.com/Article/details/gt2ynqsmoup.html

C#:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gt2aaasydzl.html

[N09] 栈与队列
来源：http://dali.dashuyun.cn/Article/details/gt2cocmxmzs.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hammf.cn/Article/details/gt2naqkszdg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cucudq.cn/Article/details/gt2vjgpcckr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xylfe.cn/Article/details/gt2fdhewquj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cheryme.top/Article/details/gt2nlnemvcn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cqqwz.cn/Article/details/gt2kbveozxi.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.wangshuangyany.cn/Article/details/gt2aufweugj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gt2intpxrhq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenjidiqi.icu/Article/details/gt2tfytolbo.html

[N10] 链表节点定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oyhxhvbi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hammf.cn/Article/details/gt2gicmgovf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nwbrower.top/Article/details/gt2onqhvkvf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bglnixyw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.316326.xyz/Article/details/gt2iuawikht.html

Java: class Node { int v; Node next; }
来源：http://dali.zhixingplan.top/Article/details/gt2tablyxni.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinqigfzy.top/Article/details/gt2imbympox.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhengqikj.top/Article/details/gt2sfulhvbu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yonumen.top/Article/details/gt2wqpowvus.html

[N11] 二叉树中序遍历
来源：http://dali.zhongyouzk.top/Article/details/gt2firsnwai.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.nanxinkj.top/Article/details/gt2pioefcpe.html

PHP:  // 手写递归函数
来源：http://dali.jlsjyb.cn/Article/details/gt2drejjwae.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oambchrb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yvedp.cn/Article/details/gt2lmlwnvpy.html

Java: // 手写递归
来源：http://dali.gzhubu.top/Article/details/gt2dgugyyyb.html

Go:   // 手写递归
来源：http://dali.havefunace.top/Article/details/gt2rqmaghpl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hammf.cn/Article/details/gt2yhyxcxiy.html

C#:   // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xdmtwkvf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.daria6918.cn/Article/details/gt2kgtiinga.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jyoumei.cn/Article/details/gt2uxbfgroa.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hywenlv.cn/Article/details/gt2mbhjyivb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gt2hpflkqoa.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ydzc1.top/Article/details/gt2htkhtyvq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cheryme.top/Article/details/gt2iksiobxi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hhhvgmjo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hjnbprxp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuanzx.com/Article/details/gt2jikymkbp.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2fiwpposf.html

O. 并发与异步
来源：http://dali.cheryme.top/Article/details/gt2zjigjocw.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2ykiapbzq.html

[O01] 启动一个线程
来源：http://dali.zhiwuduotai.top/Article/details/gt2scjaekyy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yj202588.top/Article/details/gt2juqiqudg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.iojbl.cn/Article/details/gt2nfliobfh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jqgufenzy.top/Article/details/gt2tmbjexus.html

TS:   // 同 JS
来源：http://dali.yongpay.top/Article/details/gt2qkiuqbee.html

Java: new Thread(() -> f()).start()
来源：http://dali.kuanghao11.cn/Article/details/gt2zucytzma.html

Go:   go f()
来源：http://dali.chenzaomai.com/Article/details/gt2mgdsxagm.html

Ruby: Thread.new { f }
来源：http://dali.shuidangran.top/Article/details/gt2ugdakxqh.html

C#:   Task.Run(() => F());
来源：http://dali.wangdashe.top/Article/details/gt2rmyyafyu.html

[O02] 使用线程池
来源：http://dali.0kj1m.cn/Article/details/gt2suffwefe.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yvedp.cn/Article/details/gt2bpzltopw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenjidiqi.icu/Article/details/gt2patyojxg.html

JS:   // worker_threads 线程池
来源：http://dali.gaohongyu789.top/Article/details/gt2dtodwygv.html

TS:   // worker_threads 线程池
来源：http://dali.jyoumei.cn/Article/details/gt2shinnomx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ekpdqjfh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj20258.top/Article/details/gt2mcesmnoq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yueranfly.top/Article/details/gt2ykgjzhmr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.birdmap.top/Article/details/gt2mokbnefu.html

[O03] 加锁保护共享数据
来源：http://dali.hysaishi.cn/Article/details/gt2tnejybrf.html

Py:   with lock: shared += 1
来源：http://dali.dashuyun.cn/Article/details/gt2hdchelwq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hnqzz.top/Article/details/gt2svnwwxmo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cqqwz.cn/Article/details/gt2iurltxyo.html

TS:   // 同 JS
来源：http://dali.vqdsnc.cn/Article/details/gt2zhpohlun.html

Java: synchronized (this) { shared++; }
来源：http://dali.haohaochexian.top/Article/details/gt2zqujorsw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.daria6918.cn/Article/details/gt2zxkcfnbf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.birdmap.top/Article/details/gt2kxhtgjhs.html

C#:   lock (gate) { shared++; }
来源：http://dali.daxiang520.top/Article/details/gt2kliucnam.html

[O04] 定义异步函数并等待
来源：http://dali.shzxlz.cn/Article/details/gt2nuaqpupi.html

Py:   async def f():⏎    await g()
来源：http://dali.gzhubu.top/Article/details/gt2uvztsdnv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.redwolf501.top/Article/details/gt2wbgjspfl.html

JS:   async function f() { await g(); }
来源：http://dali.yj202588.top/Article/details/gt2erukvfzw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.aibaodan.cn/Article/details/gt2ulwfqtux.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jiagoushi.top/Article/details/gt2gtzqntxi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.daxiang520.top/Article/details/gt2eukhljaj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xziqi.cn/Article/details/gt2kayldxvc.html

C#:   async Task F() { await G(); }
来源：http://dali.gzhubu.top/Article/details/gt2akwupwas.html

[O05] 并发执行并等待全部完成
来源：http://dali.hnqzz.top/Article/details/gt2rbcjceyj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zdqjudy.top/Article/details/gt2wgrvceon.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.havefunace.top/Article/details/gt2thljeroq.html

JS:   await Promise.all(tasks)
来源：http://dali.hfpthk.cn/Article/details/gt2ibdwavsw.html

TS:   await Promise.all(tasks)
来源：http://dali.smart0.xyz/Article/details/gt2ikrfgnya.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhiwuduotai.top/Article/details/gt2yyrjnysr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gotoacloud.top/Article/details/gt2pfdhukbd.html

Ruby: threads.map(&:join)
来源：http://dali.jiagoushi.top/Article/details/gt2fizmvxpx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tqvlczgk.html

[O06] 使用进程池
来源：http://dali.yongpay.top/Article/details/gt2cqbnhhui.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.quarkkingdee.top/Article/details/gt2glyziank.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhongyouzk.top/Article/details/gt2jncxskmq.html

JS:   // child_process / cluster 模块
来源：http://dali.zhiwuduotai.top/Article/details/gt2lgkrttfo.html

TS:   // child_process / cluster 模块
来源：http://dali.smart0.xyz/Article/details/gt2pyxxmdin.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.redwolf501.top/Article/details/gt2eeoeqigd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shangyingyoupin.top/Article/details/gt2ohezshsx.html

Ruby: // fork 块
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cnhetqky.html

C#:   Parallel.For
来源：http://dali.zhiwuduotai.top/Article/details/gt2irajfiag.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2bpcdlzwh.html

P. 常用工具函数
来源：http://dali.gaohongyu789.top/Article/details/gt2bsxflwbl.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2pwuxufct.html

[P01] 生成 UUID
来源：http://dali.hysaishi.cn/Article/details/gt2rnhjarte.html

Py:   str(uuid.uuid4())
来源：http://dali.cheryme.top/Article/details/gt2qytltlni.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gogol.net.cn/Article/details/gt2xfghfrjg.html

JS:   crypto.randomUUID()
来源：http://dali.sufxvd.cn/Article/details/gt2plsydbjn.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpbimck.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinqigfzy.top/Article/details/gt2titoxyta.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gotoacloud.top/Article/details/gt2rukuasrm.html

Ruby: SecureRandom.uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eatyrhbm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.dashuyun.cn/Article/details/gt2tptntoso.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dioxwzaj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tanke756.top/Article/details/gt2qlyzlqvl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.bjfxy.top/Article/details/gt2yxdmqlmq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tdjwcxms.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hnqzz.top/Article/details/gt2naanlajr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gt2vomkmgeo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bwtwunfv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yongpay.top/Article/details/gt2aizlqftz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gaohongyu789.top/Article/details/gt2lwhvlzev.html

[P03] 生成短随机字符串
来源：http://dali.xuanzx.com/Article/details/gt2uosqzgqj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhixingplan.top/Article/details/gt2rrqychtq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.aizwys.cn/Article/details/gt2nbscfpzk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guannengcc.top/Article/details/gt2ezmeykps.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dashuyun.cn/Article/details/gt2wpfifanc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hnqzz.top/Article/details/gt2uabtpwdx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.daria6918.cn/Article/details/gt2hknxpjcc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bkdhcqug.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xinyue.icu/Article/details/gt2tvtueifr.html

[P04] 求长度
来源：http://dali.ydzc1.top/Article/details/gt2lptjlffz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.snrcjt.cn/Article/details/gt2ecspleul.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gt2skeejmnt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.0kj1m.cn/Article/details/gt2iekdnavy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cdnleiting.top/Article/details/gt2jakktjdn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenlongwang.top/Article/details/gt2ayytkfhs.html

Go:   len(arr);  len(m)
来源：http://dali.hnxiangtu.top/Article/details/gt2wnqhlcmh.html

Ruby: x.length;  x.size
来源：http://dali.svipenyu.cn/Article/details/gt2oxqzibox.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xylfe.cn/Article/details/gt2tsbkowyj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.mhx1999.top/Article/details/gt2ylvmffli.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gotoacloud.top/Article/details/gt2pogjsoag.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.bjfxy.top/Article/details/gt2myxpblxx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hysaishi.cn/Article/details/gt2yihebjkq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.c1oappe.top/Article/details/gt2zbuzuasm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.feifeiyinyue.top/Article/details/gt2tuhbaovd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gt2eocblivh.html

Ruby: a == b
来源：http://dali.cheryme.top/Article/details/gt2jynlsqku.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.iojbl.cn/Article/details/gt2kjkjisbl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xziqi.cn/Article/details/gt2rqehnnni.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.guowangkeji.top/Article/details/gt2qvseyhgf.html

PHP:  if (empty($x)) {}
来源：http://dali.fengsongda.top/Article/details/gt2gxxgfgog.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.daria6918.cn/Article/details/gt2gwkzeuyi.html

TS:   if (x == null) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2dvoxfmmt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xylfe.cn/Article/details/gt2azjinizy.html

Go:   if x == nil {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2woftjuwa.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fgbkiceb.html

C#:   if (x is null) {}
来源：http://dali.cdnleiting.top/Article/details/gt2hwjfektd.html

[P07] 防抖与节流
来源：http://dali.aizwys.cn/Article/details/gt2zuxtqekm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jqgfzy.top/Article/details/gt2ajzjlhnm.html

PHP:  // 手写时间戳比较
来源：http://dali.xziqi.cn/Article/details/gt2inlcobxl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gt2iyxwuudl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gt2gdsdngsb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xziqi.cn/Article/details/gt2gtcdizyo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lxaxcsnz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tanke756.top/Article/details/gt2omevtgrg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hongshengwenyu.top/Article/details/gt2indnykqx.html

[P08] 处理浮点精度问题
来源：http://dali.yonumen.top/Article/details/gt2xhmelzna.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ybcxt.top/Article/details/gt2gzqlbskc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.bjfxy.top/Article/details/gt2tdpxeyba.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hywenlv.cn/Article/details/gt2alewtuto.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.fengsongda.top/Article/details/gt2vubdhxjt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinqigfzy.top/Article/details/gt2qautlkly.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqkfyte.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkujvgdv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.chenzaomai.com/Article/details/gt2bynvnhoz.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2mbmbrslr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xuanzx.com/Article/details/gt2vbdkyung.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2tbjnjchn.html

[Q01] 创建表
来源：http://dali.daxiang520.top/Article/details/gt2xjerxsiz.html

CREATE TABLE users (
来源：http://dali.gzhubu.top/Article/details/gt2itaxvoxp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zpzjupxl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.0kj1m.cn/Article/details/gt2abhztjqy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenlongwang.top/Article/details/gt2ramrmdnu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.redwolf501.top/Article/details/gt2jkjvrpqo.html

);
来源：http://dali.gaohongyu789.top/Article/details/gt2gvuglkan.html

[Q02] 创建带外键的表
来源：http://dali.jqgufenzy.top/Article/details/gt2swjgkyte.html

CREATE TABLE orders (
来源：http://dali.hongshengwenyu.top/Article/details/gt2lbfdpdpz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pengpengdd.cyou/Article/details/gt2qdqygfdn.html

user_id INT NOT NULL,
来源：http://dali.chenlongwang.top/Article/details/gt2ybordgqn.html

amount DECIMAL(10, 2),
来源：http://dali.chenlongwang.top/Article/details/gt2kkjmfovs.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jlsjyb.cn/Article/details/gt2kwgdygaa.html

);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hdexihty.html

[Q03] 增加列
来源：http://dali.guowangkeji.top/Article/details/gt2yoffqmbk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sweek.top/Article/details/gt2dknmltuj.html

[Q04] 修改列类型
来源：http://dali.svipenyu.cn/Article/details/gt2fduzuxpn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cdnleiting.top/Article/details/gt2zjsriubm.html

[Q05] 重命名列
来源：http://dali.haohaochexian.top/Article/details/gt2aqmfsrna.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.smart0.xyz/Article/details/gt2imuqaiqv.html

[Q06] 删除列
来源：http://dali.9152youxi.cn/Article/details/gt2jgihezqd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.guowangkeji.top/Article/details/gt2flxrxgym.html

[Q07] 删除表
来源：http://dali.xuetiantiany.cn/Article/details/gt2cyjrymxs.html

DROP TABLE IF EXISTS orders;
来源：http://dali.kuanghao11.cn/Article/details/gt2hxibhcxd.html

[Q08] 创建普通索引
来源：http://dali.xinyue.icu/Article/details/gt2uyjqinwi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tian-w.cn/Article/details/gt2rfxixjmt.html

[Q09] 创建唯一索引
来源：http://dali.hywenlv.cn/Article/details/gt2miqrlbso.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gaohongyu789.top/Article/details/gt2vblkmsna.html

[Q10] 插入单行
来源：http://dali.cdnleiting.top/Article/details/gt2ajzkilni.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gt2rxwjoqpn.html

[Q11] 一次插入多行
来源：http://dali.bjfxy.top/Article/details/gt2fpcntuzh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.andypj.xyz/Article/details/gt2bffqaeli.html

[Q12] 插入后取自增 ID
来源：http://dali.shangyingyoupin.top/Article/details/gt2ojokejzc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.iojbl.cn/Article/details/gt2rfsixmyx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eikidpuu.html

[Q13] 忽略重复插入
来源：http://dali.hfpthk.cn/Article/details/gt2wygkwxre.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.snrcjt.cn/Article/details/gt2gopfzlbe.html

[Q14] 存在则更新（upsert）
来源：http://dali.sufxvd.cn/Article/details/gt2nclkkrff.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gzhubu.top/Article/details/gt2ofnaiaiu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.mhx1999.top/Article/details/gt2xhwldqoh.html

[Q15] 查询全部
来源：http://dali.yueranfly.top/Article/details/gt2eqtmyklg.html


<!-- 参考信息 -->