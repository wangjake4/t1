代发 wailian999

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrmfoss.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsrfyxu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrakabsy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdsxnsg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jymquiwo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eljsuurz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2lldcwqct.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gepncotl.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ddendhii.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbezwcbm.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwngjim.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2plwawapo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2lustwpsr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzworsq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ygigvgxq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmmqsgs.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxrzqsk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqnlmwu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2bozdycpi.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2ezuktrag.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pchztqva.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2asjfatmx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhmvpea.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdwftfd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzefrdzh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpyogsp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iioybmuf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzcxhkv.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvznriq.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2voxpince.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmipxei.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfypjfa.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2siqhtxrr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxzypqf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cluezdmu.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2shkeosxb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2twvdearb.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pqoyuxem.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2mceirnol.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2efoxrytx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqpjsom.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgjxpeu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcudnil.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ygctodds.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2zzuaxbvd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpinokj.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwryiru.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjdzfgt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2akbkjsam.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbnkqaw.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2pesflfda.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2iiogxhef.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2woxyvcjr.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxwosbk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuhkuzt.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqsyoit.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pilgljkz.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdtcxkk.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zoteyfoo.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxmclrc.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2saeqiaqq.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2glkcockx.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbqsbxl.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkfulvq.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfanrei.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbwduww.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwwkzod.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ucadnxlc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2brtfpdoe.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqpmbkz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfcazdc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2coypvbhd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2kasombvy.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpwkkpw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2tuayhaqu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drcxigcy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlzjhni.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2siqpcsxz.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzldoar.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyliuaip.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqsgtyp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ippcocdd.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eohdtzvb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbpdgil.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcokxxw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lviiiaif.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2baoxeimn.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uunfcdgr.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlwayvu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrheefm.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hzskgcug.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzznrpz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlfexal.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkmomkh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmkedzk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqwmxem.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zyelnnig.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbzfwlm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2shclgmba.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rumacucr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qquzxfng.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2gofcqsvn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kamqsman.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2taapjotq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybeefukn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlbopoi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2mphhwxyy.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2nfphqhat.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhctxjzf.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgcoamc.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxwtbsl.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2epnjkqnp.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ioaijnzs.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhbquld.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ljstqruc.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrsdxlp.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nhifcbsf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2azoisnuh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ymloqqjm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2vatwyrjx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2lfogkmsp.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvtueeb.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzzswhe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2brhgbyyg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2iokunukt.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2aklejuzi.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdvxjga.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2azzcfxys.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzajjyw.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzhgpjl.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2livsgxva.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzoyvuq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrwqycn.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jablplqu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2axblmpry.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfdocba.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2zayrosyl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2gyusisjv.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqyrktn.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2gwursjhn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2skkvrqpv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvsmcrt.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcolxzt.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbqfyae.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvkxczj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlbezmd.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2gehwxmvk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2msqfdlej.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfqsiwn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2lojkrwqe.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gttrmmes.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvzccsp.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ismjgfyo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2qaukovgh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2dznyschn.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2crntvutx.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2igtlpnev.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjjidkl.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kuobcjdo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yhoanwuk.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwusmou.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2chtrvzsw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zawjpbcn.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdilojvy.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zfucrvwz.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvhkpbp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2djkxqgdw.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rvsthvns.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vztvnlqm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfoauuc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbhizgu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbuuykim.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2yedqsemn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfggwslb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2madrqops.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcqvzba.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2poakgfcs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhcyuse.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmahysb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2gpopglkq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2nytfzepk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkncake.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kifmitzk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwgihyo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcovtbw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtrynxt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2fghuyyof.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjzhzvf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzlwinj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2fowrjenx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2odowvjvv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhcrhdq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ukooenwz.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2inxghuta.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvabtje.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsxzrtp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2suuowcjj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ggssgsiw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdteqxv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2goqclbeo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mescrwno.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnawsve.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwmiqpv.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjwqukx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2gexpnkuz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2eslamaea.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2fclwlysg.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hauexgxm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2zficrmyl.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcmxizd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ysujakee.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrcizbn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2suxlfpdi.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqomrpu.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rkotrlxb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2evrubscf.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kvaoxnel.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqmwopi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpzoxnr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrrsnnv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2izqobcsq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnizvnq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzfwckw.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2dczpcnji.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfefsayb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pekfmdxe.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2hrldgtbx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdzkmgc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsdpnes.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2cptixzdh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhlwfmz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrlissx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tdajomwo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2lvthsyzu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wueogewb.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2yxngnsjn.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2gcusamrw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzpgvjf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmevucc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhjjnwv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2uqojzpvy.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2btbcqscc.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnsfwst.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ydeizdix.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2uiozjanq.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcobjmc.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgazvpi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpodsnp.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsobkype.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2otoyiqji.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyalazb.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gdminxgt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdjokqg.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2nofvkiqa.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcltmbp.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2knvsncus.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfeeoro.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2acmxknff.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qypaifrn.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2quprpzlw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfsvmun.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkxkhsa.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xscenpfm.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcftqri.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ifyarjwa.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrdrkfv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fashkyvf.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbhgagx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2yqimgtaa.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmhxqwa.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2rjeosvak.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lehmkslt.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2kcheirla.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2vxywsorm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2dttjytft.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcomesf.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvhiokq.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pcthujvg.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbnymoa.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2klabxhpk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkphlbpv.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjowhbp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyrnhic.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uwohyluz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfvnfcb.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mroxrqtr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2voquelop.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rvivpjwx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2oovpuhhi.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvcahed.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2upgsppbx.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ytglbuvp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2amwtekjk.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hsatpsvi.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjswqlil.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2exoojlcx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlqxpal.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvnfuly.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlgwcdr.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnjhikk.html


<!-- 参考信息 -->