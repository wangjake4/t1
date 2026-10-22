代发 wailian999

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gt2saznrsdu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2udaxqvtt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daria6918.cn/Article/details/gt2navhenuz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hysaishi.cn/Article/details/gt2srysmsqj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gt2odqnmval.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aykdlpjk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yongpay.top/Article/details/gt2qzlwpntc.html

Go:   slices.Sort(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2axestqpt.html

Ruby: arr.sort
来源：http://dali.hfpthk.cn/Article/details/gt2hkyosmxs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daxiang520.top/Article/details/gt2rzyybvkv.html

[N03] 快速排序（分治示例）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zemsgvyv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.daxiang520.top/Article/details/gt2guneblsy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.birdmap.top/Article/details/gt2volprtpp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cheryme.top/Article/details/gt2oyjcltez.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhongyouzk.top/Article/details/gt2wfvwvmqg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.iojbl.cn/Article/details/gt2qjuhlnur.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ivvv.top/Article/details/gt2qdqrtbap.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gogol.net.cn/Article/details/gt2ocvdipwr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yuanzhike.top/Article/details/gt2vvgcliam.html

[N04] 斐波那契数列
来源：http://dali.havefunace.top/Article/details/gt2guixfckb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.birdmap.top/Article/details/gt2igrrscic.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.dashuyun.cn/Article/details/gt2dxatzbrc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gt2euhqlycd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gt2caointbv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.0kj1m.cn/Article/details/gt2ycqijdik.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hikjjhzd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yvedp.cn/Article/details/gt2ruygwztr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gt2duvwauqx.html

[N05] 最大公约数
来源：http://dali.pycfn.com/Article/details/gt2msfhnrjm.html

Py:   math.gcd(a, b)
来源：http://dali.shzxlz.cn/Article/details/gt2ivsupajb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hysaishi.cn/Article/details/gt2qwezygfy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hfpthk.cn/Article/details/gt2hfgayhen.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigufen.top/Article/details/gt2jwpxkwqi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.fengsongda.top/Article/details/gt2uwelsugf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhoulong.xyz/Article/details/gt2yfzvlwnc.html

Ruby: a.gcd(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ujxxkygp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gotoacloud.top/Article/details/gt2uphpvvqg.html

[N06] 判断回文字符串
来源：http://dali.fengsongda.top/Article/details/gt2tdjxklzc.html

Py:   s == s[::-1]
来源：http://dali.ydzc1.top/Article/details/gt2chenefau.html

PHP:  $s === strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gt2onqvqpfr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gt2hiondqvf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gt2snyxynxg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cqqwz.cn/Article/details/gt2ghvkjyiy.html

Go:   // 双指针从两端比较
来源：http://dali.jinqigufen.top/Article/details/gt2aotfgyyo.html

Ruby: s == s.reverse
来源：http://dali.yanxiufei.cn/Article/details/gt2artjzadr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gotoacloud.top/Article/details/gt2huutqlie.html

[N07] 两数之和（返回下标）
来源：http://dali.yj20258.top/Article/details/gt2bqtsmmbj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tianlin.xyz/Article/details/gt2jsupzkop.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jqgufenzy.top/Article/details/gt2xcmlalgs.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hammf.cn/Article/details/gt2atxnmbil.html

TS:   // 手写 Map<string, number>
来源：http://dali.tianlin.xyz/Article/details/gt2kptnlojn.html

Java: // 手写 HashMap
来源：http://dali.0kj1m.cn/Article/details/gt2jflaczla.html

Go:   // 手写 map[int]int
来源：http://dali.gzhubu.top/Article/details/gt2hpixfwly.html

Ruby: // 手写 Hash
来源：http://dali.c1oappe.top/Article/details/gt2tbopblun.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sukreydc.html

[N08] 生成全排列
来源：http://dali.quarkkingdee.top/Article/details/gt2lfhjcifi.html

Py:   itertools.permutations(arr)
来源：http://dali.tian-w.cn/Article/details/gt2vkjzscoj.html

PHP:  // 手写递归交换
来源：http://dali.smart0.xyz/Article/details/gt2docvyksc.html

JS:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gt2cniipcus.html

TS:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gt2dlmyabez.html

Java: // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gt2sahraczl.html

Go:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gt2bajwsfew.html

Ruby: arr.permutation.to_a
来源：http://dali.yanxiufei.cn/Article/details/gt2vekmkmny.html

C#:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gt2tqytoqqp.html

[N09] 栈与队列
来源：http://dali.xylfe.cn/Article/details/gt2cpqvzihf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tjaqhjjv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hjrjgskt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gt2ydokbdmg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhixingplan.top/Article/details/gt2kykjoblh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xvwdonei.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xinyue.icu/Article/details/gt2dzyjknbz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cashguo.top/Article/details/gt2kkzvseoj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xuetiantiany.cn/Article/details/gt2vwpakvga.html

[N10] 链表节点定义
来源：http://dali.jianghu66.top/Article/details/gt2mdhmspfo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ehwqpu.com/Article/details/gt2pjenmfld.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zdqjudy.top/Article/details/gt2emfsnqac.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gotoacloud.top/Article/details/gt2gqteawlz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhengqikj.top/Article/details/gt2cndqxlsn.html

Java: class Node { int v; Node next; }
来源：http://dali.jlsjyb.cn/Article/details/gt2vwknrosz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sufxvd.cn/Article/details/gt2yechkssc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhengqikj.top/Article/details/gt2hystqmnr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shzxlz.cn/Article/details/gt2xazlqucn.html

[N11] 二叉树中序遍历
来源：http://dali.nanxuanxn.top/Article/details/gt2ilivbqrv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2frooyzoq.html

PHP:  // 手写递归函数
来源：http://dali.iojbl.cn/Article/details/gt2iesuxdvx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258888.top/Article/details/gt2obqokikr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gt2xgpolkzv.html

Java: // 手写递归
来源：http://dali.jlsjyb.cn/Article/details/gt2ltsdtndz.html

Go:   // 手写递归
来源：http://dali.sweek.top/Article/details/gt2tpwfeley.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhiwuduotai.top/Article/details/gt2rrdvzhib.html

C#:   // 手写递归
来源：http://dali.bjfxy.top/Article/details/gt2pxwdyikq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wgjgriop.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.guannengcc.top/Article/details/gt2vaybxtjz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nanxuanxn.top/Article/details/gt2hkggpboo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gt2rweolhxc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jyoumei.cn/Article/details/gt2bpvswiov.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gt2fcecfsxr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.haohaochexian.top/Article/details/gt2hcowkzoi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.0kj1m.cn/Article/details/gt2spolpaov.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.0kj1m.cn/Article/details/gt2mbgmozwm.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbqwiqgf.html

O. 并发与异步
来源：http://dali.yueranfly.top/Article/details/gt2weddnjtc.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2osjwcxou.html

[O01] 启动一个线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dgawauor.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhoulong.xyz/Article/details/gt2ptimkvdt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yvedp.cn/Article/details/gt2kjfrnoct.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yuanzhike.top/Article/details/gt2oblswbkf.html

TS:   // 同 JS
来源：http://dali.yueranfly.top/Article/details/gt2lmhnvagq.html

Java: new Thread(() -> f()).start()
来源：http://dali.chenjidiqi.icu/Article/details/gt2gzfahnin.html

Go:   go f()
来源：http://dali.yanxiufei.cn/Article/details/gt2nviszjne.html

Ruby: Thread.new { f }
来源：http://dali.redwolf501.top/Article/details/gt2lnctxqyo.html

C#:   Task.Run(() => F());
来源：http://dali.shzxlz.cn/Article/details/gt2xabykgcf.html

[O02] 使用线程池
来源：http://dali.gaohongyu789.top/Article/details/gt2jghtmdpr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gogol.net.cn/Article/details/gt2vtctlhqo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yongpay.top/Article/details/gt2mejfaqcn.html

JS:   // worker_threads 线程池
来源：http://dali.yuxming.cn/Article/details/gt2owosjtnn.html

TS:   // worker_threads 线程池
来源：http://dali.gaohongyu789.top/Article/details/gt2azwuwyoq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.bjfxy.top/Article/details/gt2gcsltcgc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nwbrower.top/Article/details/gt2wtxstubo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.0kj1m.cn/Article/details/gt2zmkozvgt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hysaishi.cn/Article/details/gt2elubbqwr.html

[O03] 加锁保护共享数据
来源：http://dali.aibaodan.cn/Article/details/gt2zldgcwyb.html

Py:   with lock: shared += 1
来源：http://dali.yueranfly.top/Article/details/gt2ijyshpvh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hnqzz.top/Article/details/gt2eksxambg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yueranfly.top/Article/details/gt2gkmqmppa.html

TS:   // 同 JS
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kzouacmb.html

Java: synchronized (this) { shared++; }
来源：http://dali.hysaishi.cn/Article/details/gt2dfctqauf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jqgufenzy.top/Article/details/gt2agtfsnqj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nwbrower.top/Article/details/gt2tofzkhfe.html

C#:   lock (gate) { shared++; }
来源：http://dali.yonumen.top/Article/details/gt2dluqosjo.html

[O04] 定义异步函数并等待
来源：http://dali.tianlin.xyz/Article/details/gt2abwpfutx.html

Py:   async def f():⏎    await g()
来源：http://dali.zhengqikj.top/Article/details/gt2opsgndfm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.pengpengdd.cyou/Article/details/gt2utszuinh.html

JS:   async function f() { await g(); }
来源：http://dali.gzhubu.top/Article/details/gt2qekmfpqs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xziqi.cn/Article/details/gt2ewucobej.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dianchejie.cn/Article/details/gt2unmnfdlb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jqgfzy.top/Article/details/gt2yygspxcf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenjidiqi.icu/Article/details/gt2yqioloom.html

C#:   async Task F() { await G(); }
来源：http://dali.guowangkeji.top/Article/details/gt2zkfwipqa.html

[O05] 并发执行并等待全部完成
来源：http://dali.smart0.xyz/Article/details/gt2ruwbatlx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.guowangkeji.top/Article/details/gt2fphloclm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.mhx1999.top/Article/details/gt2czdsbbpg.html

JS:   await Promise.all(tasks)
来源：http://dali.jinqigufen.top/Article/details/gt2hemcznwc.html

TS:   await Promise.all(tasks)
来源：http://dali.gzhubu.top/Article/details/gt2jzbnlbja.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zdqjudy.top/Article/details/gt2pirwcicv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhengqikj.top/Article/details/gt2fzhqumqc.html

Ruby: threads.map(&:join)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hcsogabe.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jqgufenzy.top/Article/details/gt2hqjpdujg.html

[O06] 使用进程池
来源：http://dali.jlsjyb.cn/Article/details/gt2xfmanufi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hywenlv.cn/Article/details/gt2xtwgkhhi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuxming.cn/Article/details/gt2knzelkys.html

JS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ydmagjmi.html

TS:   // child_process / cluster 模块
来源：http://dali.ivvv.top/Article/details/gt2okwwauyd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hnqzz.top/Article/details/gt2zyyduhob.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.chenzaomai.com/Article/details/gt2snfvytlj.html

Ruby: // fork 块
来源：http://dali.nanxinkj.top/Article/details/gt2wlcnhxyf.html

C#:   Parallel.For
来源：http://dali.chenjidiqi.icu/Article/details/gt2kjgremwq.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2xunfswmo.html

P. 常用工具函数
来源：http://dali.yanxiufei.cn/Article/details/gt2ywbbylfs.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2tkfwodxg.html

[P01] 生成 UUID
来源：http://dali.zhoulong.xyz/Article/details/gt2xtnsjgnt.html

Py:   str(uuid.uuid4())
来源：http://dali.hongshengwenyu.top/Article/details/gt2uiimdsyv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xinyue.icu/Article/details/gt2hlmjnmev.html

JS:   crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gt2qyccdxdh.html

TS:   crypto.randomUUID()
来源：http://dali.birdmap.top/Article/details/gt2aazflvru.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhoulong.xyz/Article/details/gt2orolwsgg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yueranfly.top/Article/details/gt2iocumerq.html

Ruby: SecureRandom.uuid
来源：http://dali.yueranfly.top/Article/details/gt2oxhyjfsn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hongshengwenyu.top/Article/details/gt2lkattvwf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xylfe.cn/Article/details/gt2ysqustwn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.smart0.xyz/Article/details/gt2dajztcex.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jqgfzy.top/Article/details/gt2mqmbjyrv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gaohongyu789.top/Article/details/gt2lbtndsfq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gogol.net.cn/Article/details/gt2juormwmd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.fzhhl.top/Article/details/gt2etijaabn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.kuanghao11.cn/Article/details/gt2zmqjazvt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.redwolf501.top/Article/details/gt2szokswud.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.andypj.xyz/Article/details/gt2utodstti.html

[P03] 生成短随机字符串
来源：http://dali.nwbrower.top/Article/details/gt2liodbrcf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yangfankeji.com/Article/details/gt2yiebwauy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgscbmei.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.snrcjt.cn/Article/details/gt2jppsyahf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gt2ckxwwnnp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zvhfvfny.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhiwuduotai.top/Article/details/gt2jficsnyv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenlongwang.top/Article/details/gt2aldqmmyb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.kuanghao11.cn/Article/details/gt2auvrjjbn.html

[P04] 求长度
来源：http://dali.iojbl.cn/Article/details/gt2guoohgtg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jqgufenzy.top/Article/details/gt2swgccykl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gt2kwxqlmih.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cucudq.cn/Article/details/gt2opkxrawb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zycfv.cn/Article/details/gt2tiiudmmn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.nanxuanxn.top/Article/details/gt2mmzdrwqv.html

Go:   len(arr);  len(m)
来源：http://dali.sweek.top/Article/details/gt2dtzbdccf.html

Ruby: x.length;  x.size
来源：http://dali.xylfe.cn/Article/details/gt2udnbhxym.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xuanzx.com/Article/details/gt2bjrrjtcp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinqigufen.top/Article/details/gt2mpqticst.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xinyue.icu/Article/details/gt2cdmszzuw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sufxvd.cn/Article/details/gt2tiuckzwj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.c1oappe.top/Article/details/gt2kwsetzpg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sufxvd.cn/Article/details/gt2hlkirrze.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gaohongyu789.top/Article/details/gt2exiiptss.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2afbmudof.html

Ruby: a == b
来源：http://dali.gogol.net.cn/Article/details/gt2gfnptbme.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinqigufen.top/Article/details/gt2lapznjug.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xziqi.cn/Article/details/gt2qexzwuwc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.mhx1999.top/Article/details/gt2pdkralim.html

PHP:  if (empty($x)) {}
来源：http://dali.sxryk.cn/Article/details/gt2cnwhvpkw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hammf.cn/Article/details/gt2qeujxnyk.html

TS:   if (x == null) {}
来源：http://dali.jyoumei.cn/Article/details/gt2udwmerlb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ppjwa.cn/Article/details/gt2dacrtupm.html

Go:   if x == nil {}
来源：http://dali.ppjwa.cn/Article/details/gt2xilmqjap.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gotoacloud.top/Article/details/gt2pwrvseqf.html

C#:   if (x is null) {}
来源：http://dali.yj20258888.top/Article/details/gt2arguwiyw.html

[P07] 防抖与节流
来源：http://dali.shangyingyoupin.top/Article/details/gt2noqgzrbf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhoulong.xyz/Article/details/gt2hzbgjabk.html

PHP:  // 手写时间戳比较
来源：http://dali.gzhubu.top/Article/details/gt2jwfthejk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hfpthk.cn/Article/details/gt2wbccmeve.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wymqwthl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.9152youxi.cn/Article/details/gt2yxoevind.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.daria6918.cn/Article/details/gt2tpmhhdfd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yongpay.top/Article/details/gt2nfocezrf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hfpthk.cn/Article/details/gt2pdlhegkn.html

[P08] 处理浮点精度问题
来源：http://dali.pengpengdd.cyou/Article/details/gt2wvfbgjdz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.nwbrower.top/Article/details/gt2twfwkkdt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.pycfn.com/Article/details/gt2rjgqvsxm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.nwbrower.top/Article/details/gt2tzfbtalu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jqgufenzy.top/Article/details/gt2fvrrupit.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jlsjyb.cn/Article/details/gt2wtbjkozr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.feifeiyinyue.top/Article/details/gt2plcbwsjs.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bwhvipvy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yangfankeji.com/Article/details/gt2kuyhjzho.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2hbrhanie.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.aizwys.cn/Article/details/gt2cotunfob.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2jqxsqube.html

[Q01] 创建表
来源：http://dali.hnxiangtu.top/Article/details/gt2bdhfzalc.html

CREATE TABLE users (
来源：http://dali.cqqwz.cn/Article/details/gt2tbudmnwl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqpvjwd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jiagoushi.top/Article/details/gt2sgmzmzjh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xylfe.cn/Article/details/gt2hlxwttit.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ivvv.top/Article/details/gt2vudscini.html

);
来源：http://dali.hfpthk.cn/Article/details/gt2agwffdyp.html

[Q02] 创建带外键的表
来源：http://dali.ybcxt.top/Article/details/gt2fgogkkti.html

CREATE TABLE orders (
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pzkdcjvl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sxryk.cn/Article/details/gt2jidvjihl.html

user_id INT NOT NULL,
来源：http://dali.jqgufenzy.top/Article/details/gt2redqnnge.html

amount DECIMAL(10, 2),
来源：http://dali.aizwys.cn/Article/details/gt2zemwqrtr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zycfv.cn/Article/details/gt2xvxayhhs.html

);
来源：http://dali.gotoacloud.top/Article/details/gt2hohschzl.html

[Q03] 增加列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dhuyrsjh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj20258.top/Article/details/gt2mggmkqgd.html

[Q04] 修改列类型
来源：http://dali.hfpthk.cn/Article/details/gt2dnxepdka.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenjidiqi.icu/Article/details/gt2vqebfymt.html

[Q05] 重命名列
来源：http://dali.daxiang520.top/Article/details/gt2tanakcqh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.wangdashe.top/Article/details/gt2zqeuregy.html

[Q06] 删除列
来源：http://dali.chenjidiqi.icu/Article/details/gt2rsoeixdq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ncjdoxkr.html

[Q07] 删除表
来源：http://dali.dashuyun.cn/Article/details/gt2ujhhxrgj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bqfzuhag.html

[Q08] 创建普通索引
来源：http://dali.hnqzz.top/Article/details/gt2bwgwgrip.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gogol.net.cn/Article/details/gt2acskkikc.html

[Q09] 创建唯一索引
来源：http://dali.jinqigfzy.top/Article/details/gt2knzqybzz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.svipenyu.cn/Article/details/gt2chndawoq.html

[Q10] 插入单行
来源：http://dali.jyoumei.cn/Article/details/gt2cszceeby.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gt2mhgzghmx.html

[Q11] 一次插入多行
来源：http://dali.daxiang520.top/Article/details/gt2ulemowqd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nwbrower.top/Article/details/gt2rhedweum.html

[Q12] 插入后取自增 ID
来源：http://dali.xuetiantiany.cn/Article/details/gt2junhecpy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hammf.cn/Article/details/gt2gbkywajp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.redwolf501.top/Article/details/gt2ndnhmjdf.html

[Q13] 忽略重复插入
来源：http://dali.shzxlz.cn/Article/details/gt2twpbblfh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.fzhhl.top/Article/details/gt2jfqndpyq.html

[Q14] 存在则更新（upsert）
来源：http://dali.hysaishi.cn/Article/details/gt2yqugijsq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hnxiangtu.top/Article/details/gt2whtgodbn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinqigfzy.top/Article/details/gt2iggjzvrr.html

[Q15] 查询全部
来源：http://dali.xuanzx.com/Article/details/gt2ejkoakyz.html

SELECT * FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2hoqtmfpm.html

[Q16] 查询指定列
来源：http://dali.yj20258.top/Article/details/gt2ippjbivb.html

SELECT id, name FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2qchokrnp.html

[Q17] 条件查询
来源：http://dali.aizwys.cn/Article/details/gt2dyrfocwz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gt2wfkjpski.html

[Q18] 模糊匹配
来源：http://dali.guannengcc.top/Article/details/gt2ortcvbdb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xziqi.cn/Article/details/gt2nlexjfdi.html

[Q19] 范围查询
来源：http://dali.vqdsnc.cn/Article/details/gt2qjfvobbu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jyoumei.cn/Article/details/gt2nwjjowji.html

[Q20] IN 列表
来源：http://dali.hammf.cn/Article/details/gt2hzkyavku.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hysaishi.cn/Article/details/gt2bfwsbywu.html

[Q21] 空值判断
来源：http://dali.cdnleiting.top/Article/details/gt2qafhvjur.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sxryk.cn/Article/details/gt2nhqdbcfj.html

[Q22] 排序
来源：http://dali.zhengqikj.top/Article/details/gt2gmnbcxag.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zycfv.cn/Article/details/gt2qnzevusu.html

[Q23] 分页
来源：http://dali.aibaodan.cn/Article/details/gt2qblblequ.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhengqikj.top/Article/details/gt2mfgpbggf.html

[Q24] 去重
来源：http://dali.ivvv.top/Article/details/gt2staezced.html

SELECT DISTINCT city FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2sonhjzyz.html

[Q25] 只取前 N 条
来源：http://dali.daria6918.cn/Article/details/gt2taqddzjp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.redwolf501.top/Article/details/gt2ybqpkzxd.html

[Q26] 计数
来源：http://dali.gogol.net.cn/Article/details/gt2emrodhty.html

SELECT COUNT(*) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2dkkqisyt.html

[Q27] 条件计数
来源：http://dali.cdnleiting.top/Article/details/gt2zamheryv.html


<!-- 参考信息 -->