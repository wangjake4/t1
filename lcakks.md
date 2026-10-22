代发 wailian999

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtfgfkaiua.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yueranfly.top/Article/details/gtzwzvotkn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sysykeji.top/Article/details/gtxaqtwiya.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nwbrower.top/Article/details/gtqyghixvs.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gtybhifbru.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gtacpibgmu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yuanzhike.top/Article/details/gtgiexgkis.html

Go:   slices.Sort(arr)
来源：http://dali.dashuyun.cn/Article/details/gtnledszpl.html

Ruby: arr.sort
来源：http://dali.zycfv.cn/Article/details/gtduwkxnuq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nwbrower.top/Article/details/gtjvusfwwv.html

[N03] 快速排序（分治示例）
来源：http://dali.316326.xyz/Article/details/gthsgtchhj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cheryme.top/Article/details/gtlnslhyko.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfhmipent.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuanzhike.top/Article/details/gtdrrnylod.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shangyingyoupin.top/Article/details/gtxgjuiejl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nanxinkj.top/Article/details/gttaipqyxp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtapxkojid.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.pengpengdd.cyou/Article/details/gtijozjdhk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jlsjyb.cn/Article/details/gtywbjcnfk.html

[N04] 斐波那契数列
来源：http://dali.redwolf501.top/Article/details/gtjkhgghcm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shzxlz.cn/Article/details/gthnavuwwp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cashguo.top/Article/details/gtwzbyajbo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtotuwqcls.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gtjmmfyagl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj20258888.top/Article/details/gtlhhcgrrt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tianlin.xyz/Article/details/gteisemucd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ppjwa.cn/Article/details/gtoqbbjjct.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gtaosaqgsz.html

[N05] 最大公约数
来源：http://dali.pengpengdd.cyou/Article/details/gtveqrtjlw.html

Py:   math.gcd(a, b)
来源：http://dali.jiagoushi.top/Article/details/gtilaenspn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xylfe.cn/Article/details/gtqyilwyad.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtodxeitbb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.c1oappe.top/Article/details/gtnsxjgick.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gotoacloud.top/Article/details/gtvsfhxarh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.guannengcc.top/Article/details/gtdzliveed.html

Ruby: a.gcd(b)
来源：http://dali.yangfankeji.com/Article/details/gtltwwvybh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinqigfzy.top/Article/details/gtosepdxbg.html

[N06] 判断回文字符串
来源：http://dali.hnqzz.top/Article/details/gtyopsslkk.html

Py:   s == s[::-1]
来源：http://dali.kuanghao11.cn/Article/details/gtvckcpfzo.html

PHP:  $s === strrev($s);
来源：http://dali.birdmap.top/Article/details/gtksxpxtar.html

JS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtzxxdubfb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtyelsnhvu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zycfv.cn/Article/details/gtjsmjbkdi.html

Go:   // 双指针从两端比较
来源：http://dali.ybcxt.top/Article/details/gtbxozqxey.html

Ruby: s == s.reverse
来源：http://dali.quarkkingdee.top/Article/details/gtnngyeizn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xziqi.cn/Article/details/gtfslgrwew.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gtangswjsj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hysaishi.cn/Article/details/gtsiueitod.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrkqayou.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj202588.top/Article/details/gtspncwqfh.html

TS:   // 手写 Map<string, number>
来源：http://dali.gogol.net.cn/Article/details/gtqaanqnur.html

Java: // 手写 HashMap
来源：http://dali.tian-w.cn/Article/details/gtjyfokzke.html

Go:   // 手写 map[int]int
来源：http://dali.jyoumei.cn/Article/details/gtnebbaxyw.html

Ruby: // 手写 Hash
来源：http://dali.jyoumei.cn/Article/details/gtorabodgj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shuidangran.top/Article/details/gttxccsqkc.html

[N08] 生成全排列
来源：http://dali.xylfe.cn/Article/details/gtpflpeium.html

Py:   itertools.permutations(arr)
来源：http://dali.hammf.cn/Article/details/gtxaiepdac.html

PHP:  // 手写递归交换
来源：http://dali.hnqzz.top/Article/details/gtpkxouwxj.html

JS:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtezsnhakx.html

TS:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtfhfiaxrz.html

Java: // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtjlbpfjpc.html

Go:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtbxinvomy.html

Ruby: arr.permutation.to_a
来源：http://dali.gotoacloud.top/Article/details/gthpixalla.html

C#:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtzcpkfsff.html

[N09] 栈与队列
来源：http://dali.316326.xyz/Article/details/gtfrnzmqwm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj20258888.top/Article/details/gtkkooonjw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gtcaknpkhn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpedwqiox.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtekflmzkp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.havefunace.top/Article/details/gtwlugjqjr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.havefunace.top/Article/details/gtiqvcegdc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gtjsjwynni.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xylfe.cn/Article/details/gtmzaducix.html

[N10] 链表节点定义
来源：http://dali.zhongyouzk.top/Article/details/gtcpgsjfey.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cdnleiting.top/Article/details/gtalptbuaf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gogol.net.cn/Article/details/gtytkfzqhw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj202588.top/Article/details/gtduhwunor.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinqigufen.top/Article/details/gticpcamez.html

Java: class Node { int v; Node next; }
来源：http://dali.vqdsnc.cn/Article/details/gtswmztimi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yueranfly.top/Article/details/gtdahrjhng.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yangfankeji.com/Article/details/gtxglpaonc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.meibo888.top/Article/details/gtwstmjcgj.html

[N11] 二叉树中序遍历
来源：http://dali.hywenlv.cn/Article/details/gtaoidierw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.fzhhl.top/Article/details/gtgkuyidkt.html

PHP:  // 手写递归函数
来源：http://dali.cdnleiting.top/Article/details/gtgkfuemsd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.andypj.xyz/Article/details/gtvpyttivx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.316326.xyz/Article/details/gtyhfcsykw.html

Java: // 手写递归
来源：http://dali.redwolf501.top/Article/details/gtkmkvlhxj.html

Go:   // 手写递归
来源：http://dali.9152youxi.cn/Article/details/gthpghzvfg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jqgfzy.top/Article/details/gthkiszbgn.html

C#:   // 手写递归
来源：http://dali.daxiang520.top/Article/details/gtbyucwswc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yangfankeji.com/Article/details/gtimrzoegk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj202588.top/Article/details/gtwtzamfsx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtstvodrba.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shangyingyoupin.top/Article/details/gtgwubauiv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cheryme.top/Article/details/gttorfbowu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xylfe.cn/Article/details/gtirlechgu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.dashuyun.cn/Article/details/gtihjwkryd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gaohongyu789.top/Article/details/gtepuzwlsq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.9152youxi.cn/Article/details/gthnxmchru.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtjcnyxxsv.html

O. 并发与异步
来源：http://dali.zhixingplan.top/Article/details/gtgadetpuj.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtaripikdv.html

[O01] 启动一个线程
来源：http://dali.aibaodan.cn/Article/details/gtxilgjppz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nwbrower.top/Article/details/gtxwdadype.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tian-w.cn/Article/details/gtvurpvivw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlghneolh.html

TS:   // 同 JS
来源：http://dali.feifeiyinyue.top/Article/details/gtohlqvcnm.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzmvrqume.html

Go:   go f()
来源：http://dali.gotoacloud.top/Article/details/gtnbfpkakv.html

Ruby: Thread.new { f }
来源：http://dali.fzhhl.top/Article/details/gtcgbgdbdc.html

C#:   Task.Run(() => F());
来源：http://dali.meibo888.top/Article/details/gtibusfjdc.html

[O02] 使用线程池
来源：http://dali.zhixingplan.top/Article/details/gtxbhphctz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nwbrower.top/Article/details/gtcmjqqvrt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenzaomai.com/Article/details/gtlukiwipv.html

JS:   // worker_threads 线程池
来源：http://dali.zhiwuduotai.top/Article/details/gtsylsfdei.html

TS:   // worker_threads 线程池
来源：http://dali.snrcjt.cn/Article/details/gtsqwbjjuw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.chenzaomai.com/Article/details/gtckiqhvqw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cucudq.cn/Article/details/gtqaaybora.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gotoacloud.top/Article/details/gtluhiegnh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhengqikj.top/Article/details/gtxotfjqfx.html

[O03] 加锁保护共享数据
来源：http://dali.aizwys.cn/Article/details/gtusqotbuf.html

Py:   with lock: shared += 1
来源：http://dali.ybcxt.top/Article/details/gtthtpuiuc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jlsjyb.cn/Article/details/gtrwqspzhu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenlongwang.top/Article/details/gtuytcmwbs.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gtxxxujtcx.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gtvctecmuw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhengqikj.top/Article/details/gthbvoebpb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.andypj.xyz/Article/details/gtpmfypmby.html

C#:   lock (gate) { shared++; }
来源：http://dali.hammf.cn/Article/details/gtittxbrnc.html

[O04] 定义异步函数并等待
来源：http://dali.guannengcc.top/Article/details/gtwkntnxlr.html

Py:   async def f():⏎    await g()
来源：http://dali.316326.xyz/Article/details/gtjarehqph.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ehwqpu.com/Article/details/gtobnykvym.html

JS:   async function f() { await g(); }
来源：http://dali.mhx1999.top/Article/details/gtvfoqerew.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hfpthk.cn/Article/details/gtmuygvxcr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cucudq.cn/Article/details/gttprfvnbm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.snrcjt.cn/Article/details/gtwkmtbncn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sxryk.cn/Article/details/gtwpzzkqjt.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258.top/Article/details/gtxhctfmji.html

[O05] 并发执行并等待全部完成
来源：http://dali.yvedp.cn/Article/details/gtlybunacw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtnxnlwbuq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cashguo.top/Article/details/gtrglgkomn.html

JS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gthusjmnge.html

TS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gtiwxgvreq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jiagoushi.top/Article/details/gtuxlrnfiv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sweek.top/Article/details/gtiuaqapth.html

Ruby: threads.map(&:join)
来源：http://dali.pengpengdd.cyou/Article/details/gtaganvhuc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hysaishi.cn/Article/details/gtzkjqxaeo.html

[O06] 使用进程池
来源：http://dali.c1oappe.top/Article/details/gtgcdsamhn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.svipenyu.cn/Article/details/gtzgkvqosp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzhvkqun.html

JS:   // child_process / cluster 模块
来源：http://dali.xuanzx.com/Article/details/gtgsumpqvb.html

TS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gtsfsgsyql.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hywenlv.cn/Article/details/gtfxubeaxk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ybcxt.top/Article/details/gtpqgfxfij.html

Ruby: // fork 块
来源：http://dali.ehwqpu.com/Article/details/gtjfnevvve.html

C#:   Parallel.For
来源：http://dali.haohaochexian.top/Article/details/gtylbvofdl.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtkhjnnbjw.html

P. 常用工具函数
来源：http://dali.jinqigufen.top/Article/details/gtzxngrwwh.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtrnboerhs.html

[P01] 生成 UUID
来源：http://dali.birdmap.top/Article/details/gtvzpnyaic.html

Py:   str(uuid.uuid4())
来源：http://dali.ybcxt.top/Article/details/gtarohlkyt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ppjwa.cn/Article/details/gtbjdmcloz.html

JS:   crypto.randomUUID()
来源：http://dali.andypj.xyz/Article/details/gtlcmkzklk.html

TS:   crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gtputlvnhf.html

Java: UUID.randomUUID().toString()
来源：http://dali.ivvv.top/Article/details/gtahifapbf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.fengsongda.top/Article/details/gtvofgawef.html

Ruby: SecureRandom.uuid
来源：http://dali.9152youxi.cn/Article/details/gtligtlvtt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.kuanghao11.cn/Article/details/gtlbxwzcco.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkddktrrd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gotoacloud.top/Article/details/gtsmddamnk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.dianchejie.cn/Article/details/gtuvoisnhl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gaohongyu789.top/Article/details/gtdjngdynh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.redwolf501.top/Article/details/gtyhythslz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gtlixykqna.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.redwolf501.top/Article/details/gtdfcvfzel.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.wangdashe.top/Article/details/gtezrwbpdn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nwbrower.top/Article/details/gtleuyzuol.html

[P03] 生成短随机字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqeffwcdx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.pengpengdd.cyou/Article/details/gtvrdzobgg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinqigfzy.top/Article/details/gtkvvlugfj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.0kj1m.cn/Article/details/gtmakpmgza.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sxryk.cn/Article/details/gtjkvwhzee.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nanxuanxn.top/Article/details/gtipekcarv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.vqdsnc.cn/Article/details/gtpfbhwgkg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqtmiqraz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cdnleiting.top/Article/details/gtokdixahm.html

[P04] 求长度
来源：http://dali.yongpay.top/Article/details/gtowebyhwb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.iojbl.cn/Article/details/gtztqvqdme.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtzsolwnne.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yanxiufei.cn/Article/details/gtgsdaktyj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gtttitnncw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shzxlz.cn/Article/details/gtgxaidggp.html

Go:   len(arr);  len(m)
来源：http://dali.chenjidiqi.icu/Article/details/gtsrffxxxm.html

Ruby: x.length;  x.size
来源：http://dali.jyoumei.cn/Article/details/gtppntcnum.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.nanxinkj.top/Article/details/gtdctbaqae.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shangyingyoupin.top/Article/details/gtdikpikgg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jianghu66.top/Article/details/gtvisegxwp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.quarkkingdee.top/Article/details/gtlbufnqop.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zdqjudy.top/Article/details/gtagfuxatw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj202588.top/Article/details/gtkckeigkp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tian-w.cn/Article/details/gtmeaqxogx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.nanxuanxn.top/Article/details/gthdllnuwk.html

Ruby: a == b
来源：http://dali.pycfn.com/Article/details/gtqnxoksyw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.9152youxi.cn/Article/details/gtiwtmyfgr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gaohongyu789.top/Article/details/gthqkipher.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xinyue.icu/Article/details/gtwhfivmnh.html

PHP:  if (empty($x)) {}
来源：http://dali.xinyue.icu/Article/details/gtdwaupaju.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.aibaodan.cn/Article/details/gtrbmqlodp.html

TS:   if (x == null) {}
来源：http://dali.xziqi.cn/Article/details/gtcjzeekyj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tian-w.cn/Article/details/gtxekjzqzp.html

Go:   if x == nil {}
来源：http://dali.redwolf501.top/Article/details/gtvarzzaaz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ehwqpu.com/Article/details/gtuvlhrjxi.html

C#:   if (x is null) {}
来源：http://dali.yanxiufei.cn/Article/details/gtrdnvxotb.html

[P07] 防抖与节流
来源：http://dali.c1oappe.top/Article/details/gtnerfhcrv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.feifeiyinyue.top/Article/details/gtzmiisacc.html

PHP:  // 手写时间戳比较
来源：http://dali.wangdashe.top/Article/details/gtojcejmwk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cdnleiting.top/Article/details/gtgxjapsql.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gtbsphvgkx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.wangdashe.top/Article/details/gtrsaoftky.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ehwqpu.com/Article/details/gtlebfkqxf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinqigufen.top/Article/details/gtoeioafhn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cdnleiting.top/Article/details/gtwwcxufrj.html

[P08] 处理浮点精度问题
来源：http://dali.ehwqpu.com/Article/details/gtusixfylx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.havefunace.top/Article/details/gteokrfxad.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.316326.xyz/Article/details/gtayvqyomr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hysaishi.cn/Article/details/gtebpmrlfy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yangfankeji.com/Article/details/gtduydwhmx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhoulong.xyz/Article/details/gtshienjys.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.dianchejie.cn/Article/details/gtsxzmgwdz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xuetiantiany.cn/Article/details/gtfvyoqqmt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hammf.cn/Article/details/gtpfbjgsca.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtzdfsvvmd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xuetiantiany.cn/Article/details/gtrxdawhxb.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtfzuddsqs.html

[Q01] 创建表
来源：http://dali.daxiang520.top/Article/details/gtjrnnmxbe.html

CREATE TABLE users (
来源：http://dali.guannengcc.top/Article/details/gtavklarww.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gaohongyu789.top/Article/details/gtytchwarh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.c1oappe.top/Article/details/gtywmyqzox.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yuxming.cn/Article/details/gtwnhvxuiq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hongshengwenyu.top/Article/details/gtujwsiaru.html

);
来源：http://dali.yj20258.top/Article/details/gtezlzkabl.html

[Q02] 创建带外键的表
来源：http://dali.wangshuangyany.cn/Article/details/gtbdjwfmir.html

CREATE TABLE orders (
来源：http://dali.yvedp.cn/Article/details/gtzqewncws.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gogol.net.cn/Article/details/gtfwhzfhsm.html

user_id INT NOT NULL,
来源：http://dali.yonumen.top/Article/details/gtiepcxkpt.html

amount DECIMAL(10, 2),
来源：http://dali.ivvv.top/Article/details/gttqzatznq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinqigufen.top/Article/details/gtorwpqdwm.html

);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjzwxnfme.html

[Q03] 增加列
来源：http://dali.ybcxt.top/Article/details/gtfulfkrwr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.kuanghao11.cn/Article/details/gtwmdtgkvd.html

[Q04] 修改列类型
来源：http://dali.jinqigufen.top/Article/details/gtedxjkzpg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.smart0.xyz/Article/details/gtanmqpsnr.html

[Q05] 重命名列
来源：http://dali.cashguo.top/Article/details/gtzzgiabdh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhiwuduotai.top/Article/details/gtgksdnoqb.html

[Q06] 删除列
来源：http://dali.yj202588.top/Article/details/gtdjwuhbmh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.andypj.xyz/Article/details/gtsddqwadv.html

[Q07] 删除表
来源：http://dali.shanyushiyangtech.top/Article/details/gtknqboypi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.havefunace.top/Article/details/gttqtdqclj.html

[Q08] 创建普通索引
来源：http://dali.aibaodan.cn/Article/details/gtztwmqecc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.snrcjt.cn/Article/details/gtcuomgxvz.html

[Q09] 创建唯一索引
来源：http://dali.jianghu66.top/Article/details/gtwrmckame.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cqqwz.cn/Article/details/gtumttunak.html

[Q10] 插入单行
来源：http://dali.jqgfzy.top/Article/details/gtxwoxlozn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gteedwuabz.html

[Q11] 一次插入多行
来源：http://dali.yj202588.top/Article/details/gtphjjpkwn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xylfe.cn/Article/details/gtffqrjnvd.html

[Q12] 插入后取自增 ID
来源：http://dali.havefunace.top/Article/details/gtlxdbhzml.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmijkrzk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.wangdashe.top/Article/details/gtarwpronq.html

[Q13] 忽略重复插入
来源：http://dali.hfpthk.cn/Article/details/gtbnlpkfku.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.guowangkeji.top/Article/details/gtiamuzfod.html

[Q14] 存在则更新（upsert）
来源：http://dali.sysykeji.top/Article/details/gtmtirxfjk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shzxlz.cn/Article/details/gtbpkfmgwk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.fengsongda.top/Article/details/gtblqsobhe.html

[Q15] 查询全部
来源：http://dali.ivvv.top/Article/details/gtixfszdud.html

SELECT * FROM users;
来源：http://dali.yj202588.top/Article/details/gtgppykyax.html

[Q16] 查询指定列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxcpfkqhu.html

SELECT id, name FROM users;
来源：http://dali.aizwys.cn/Article/details/gtwrshasso.html

[Q17] 条件查询
来源：http://dali.zycfv.cn/Article/details/gtqviigfcl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cdnleiting.top/Article/details/gtzukmjkim.html

[Q18] 模糊匹配
来源：http://dali.shuidangran.top/Article/details/gtevytuwqm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hysaishi.cn/Article/details/gtvxenfnec.html

[Q19] 范围查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbzrrvrnt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yanxiufei.cn/Article/details/gtdoxxptlh.html

[Q20] IN 列表
来源：http://dali.tian-w.cn/Article/details/gtfknpranj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtyizzzopl.html

[Q21] 空值判断
来源：http://dali.chenjidiqi.icu/Article/details/gtzmhlpqyd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkoulald.html

[Q22] 排序
来源：http://dali.andypj.xyz/Article/details/gtjocbyvrz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hongshengwenyu.top/Article/details/gtttninujl.html

[Q23] 分页
来源：http://dali.hysaishi.cn/Article/details/gterlnoxxg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cheryme.top/Article/details/gtxtuttwqt.html

[Q24] 去重
来源：http://dali.gaohongyu789.top/Article/details/gtddzhrqhx.html

SELECT DISTINCT city FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtheuvnmwn.html

[Q25] 只取前 N 条
来源：http://dali.nwbrower.top/Article/details/gtojxksqna.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sufxvd.cn/Article/details/gtbiwymthb.html

[Q26] 计数
来源：http://dali.zhongyouzk.top/Article/details/gtwkgonaos.html

SELECT COUNT(*) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtucmfmidk.html

[Q27] 条件计数
来源：http://dali.nanxuanxn.top/Article/details/gtbehliikf.html


<!-- 参考信息 -->