代发 wailian999

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtneegxyyu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nwbrower.top/Article/details/gtoefbklix.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jiagoushi.top/Article/details/gtdgaspxtz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.fengsongda.top/Article/details/gtohqaousx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gtmoiwzuwt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gtytozmbpr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yueranfly.top/Article/details/gtbtsmwscn.html

Go:   slices.Sort(arr)
来源：http://dali.sysykeji.top/Article/details/gtjiqhacwd.html

Ruby: arr.sort
来源：http://dali.jqgfzy.top/Article/details/gtekskyyat.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cdnleiting.top/Article/details/gtqufrzzgj.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxuanxn.top/Article/details/gthbazpsrc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.svipenyu.cn/Article/details/gttnfgsyag.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ydzc1.top/Article/details/gtlnxbgqvi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigufen.top/Article/details/gtmhukzfus.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnqzz.top/Article/details/gteihtcrnc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhoulong.xyz/Article/details/gtfzswhxju.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.daria6918.cn/Article/details/gthfvzompt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinqigfzy.top/Article/details/gtovjwcert.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.meibo888.top/Article/details/gtzcpiqjga.html

[N04] 斐波那契数列
来源：http://dali.ehwqpu.com/Article/details/gtfeyzxmzz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shzxlz.cn/Article/details/gtbnnhjfvm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttrngpgvz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.smart0.xyz/Article/details/gtsskqhzsb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gtemmtqpln.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gtavgukzxg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hongshengwenyu.top/Article/details/gtdlndqgcf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ydzc1.top/Article/details/gtygwabbjd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gtgvndknys.html

[N05] 最大公约数
来源：http://dali.snrcjt.cn/Article/details/gtbuvubfcd.html

Py:   math.gcd(a, b)
来源：http://dali.ydzc1.top/Article/details/gtsbsbmhfn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.pycfn.com/Article/details/gticakswbb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnqzz.top/Article/details/gtsxwjbqto.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hysaishi.cn/Article/details/gtsmmwsoji.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jyoumei.cn/Article/details/gtbqnjrway.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xuanzx.com/Article/details/gtijygzgug.html

Ruby: a.gcd(b)
来源：http://dali.tanke756.top/Article/details/gtbvfotjdq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.redwolf501.top/Article/details/gtznyalujs.html

[N06] 判断回文字符串
来源：http://dali.hywenlv.cn/Article/details/gtrsrzczci.html

Py:   s == s[::-1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtcsvnkwwb.html

PHP:  $s === strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjrorbwr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gtmfryjogb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gtvaehsdvv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.meibo888.top/Article/details/gtxngynqvz.html

Go:   // 双指针从两端比较
来源：http://dali.zhixingplan.top/Article/details/gtfkifwprj.html

Ruby: s == s.reverse
来源：http://dali.yanxiufei.cn/Article/details/gtaywluear.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.vqdsnc.cn/Article/details/gtkwfxwoqy.html

[N07] 两数之和（返回下标）
来源：http://dali.andypj.xyz/Article/details/gttfrfutwf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpiegwtbf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hywenlv.cn/Article/details/gtjaztwuay.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tanke756.top/Article/details/gtsxwbmrub.html

TS:   // 手写 Map<string, number>
来源：http://dali.cheryme.top/Article/details/gtnnhrjplr.html

Java: // 手写 HashMap
来源：http://dali.jinqigufen.top/Article/details/gtsjljxilx.html

Go:   // 手写 map[int]int
来源：http://dali.zhoulong.xyz/Article/details/gtpjfxvivs.html

Ruby: // 手写 Hash
来源：http://dali.quarkkingdee.top/Article/details/gtlosxblbc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cucudq.cn/Article/details/gtgzviwgbo.html

[N08] 生成全排列
来源：http://dali.xylfe.cn/Article/details/gtylzyeypy.html

Py:   itertools.permutations(arr)
来源：http://dali.zycfv.cn/Article/details/gtxpogolde.html

PHP:  // 手写递归交换
来源：http://dali.redwolf501.top/Article/details/gtikboazig.html

JS:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtomwvzpaj.html

TS:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtcxtpbjop.html

Java: // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gthkbecpcn.html

Go:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtoverewpk.html

Ruby: arr.permutation.to_a
来源：http://dali.c1oappe.top/Article/details/gtxwzskhpo.html

C#:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtpdcqtyfw.html

[N09] 栈与队列
来源：http://dali.yuxming.cn/Article/details/gtjtkqcixu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbqwfgtuo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cashguo.top/Article/details/gtlqiiqqtt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtifjfobzk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.vqdsnc.cn/Article/details/gtzberahdg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj20258.top/Article/details/gtgoxedvlt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.9152youxi.cn/Article/details/gtoljsbjqk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ivvv.top/Article/details/gtifcpeqyr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenjidiqi.icu/Article/details/gtlkyvzibi.html

[N10] 链表节点定义
来源：http://dali.tian-w.cn/Article/details/gtckyypxec.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhongyouzk.top/Article/details/gtyllplwwt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sysykeji.top/Article/details/gtvbfiwqvv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwjhhqbc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.redwolf501.top/Article/details/gtcuwezbdp.html

Java: class Node { int v; Node next; }
来源：http://dali.sxryk.cn/Article/details/gtnwbgjjnw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yangfankeji.com/Article/details/gtfkoyigul.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.birdmap.top/Article/details/gtzohycise.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.iojbl.cn/Article/details/gthsinibev.html

[N11] 二叉树中序遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtxhzkqvzt.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhongyouzk.top/Article/details/gttjuhumdq.html

PHP:  // 手写递归函数
来源：http://dali.fengsongda.top/Article/details/gtjobgpldf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jyoumei.cn/Article/details/gtfjphxeii.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aibaodan.cn/Article/details/gtbtfqxizm.html

Java: // 手写递归
来源：http://dali.yueranfly.top/Article/details/gtxprswmff.html

Go:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gtvrdiblpf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cheryme.top/Article/details/gtdjzlpphi.html

C#:   // 手写递归
来源：http://dali.guannengcc.top/Article/details/gtzlwobzvm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tianlin.xyz/Article/details/gtqxtqlmex.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavpigsps.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yongpay.top/Article/details/gtsjuycoae.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zycfv.cn/Article/details/gtohuauyua.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.snrcjt.cn/Article/details/gtdxbvmhhm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxsmexign.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ivvv.top/Article/details/gtfnxijhrr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yueranfly.top/Article/details/gtpfzxcrig.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gtnyukwfyi.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtzduxqxbx.html

O. 并发与异步
来源：http://dali.xinyue.icu/Article/details/gtawziykwk.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtnpmihwfy.html

[O01] 启动一个线程
来源：http://dali.cashguo.top/Article/details/gtuqxcxbqh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.kuanghao11.cn/Article/details/gtnvfrltve.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aibaodan.cn/Article/details/gtmlbgoxmi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.0kj1m.cn/Article/details/gtiusjnczb.html

TS:   // 同 JS
来源：http://dali.316326.xyz/Article/details/gtzwdlnucl.html

Java: new Thread(() -> f()).start()
来源：http://dali.0kj1m.cn/Article/details/gttcuufcqb.html

Go:   go f()
来源：http://dali.gotoacloud.top/Article/details/gtlduwlnvg.html

Ruby: Thread.new { f }
来源：http://dali.chenlongwang.top/Article/details/gtboyshesp.html

C#:   Task.Run(() => F());
来源：http://dali.redwolf501.top/Article/details/gtdbzwobwb.html

[O02] 使用线程池
来源：http://dali.snrcjt.cn/Article/details/gtvnydcggn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zdqjudy.top/Article/details/gtfpwabfmr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yonumen.top/Article/details/gtnaqxmfke.html

JS:   // worker_threads 线程池
来源：http://dali.sufxvd.cn/Article/details/gtmceognyv.html

TS:   // worker_threads 线程池
来源：http://dali.sufxvd.cn/Article/details/gtgxvwuxsr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cheryme.top/Article/details/gtkchqybtz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.andypj.xyz/Article/details/gtidqqyqrg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhglonat.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hfpthk.cn/Article/details/gtpzloovet.html

[O03] 加锁保护共享数据
来源：http://dali.jqgfzy.top/Article/details/gthgvipopz.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gtkfkgsrop.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cheryme.top/Article/details/gtuogeehgi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sxryk.cn/Article/details/gtrdmdhiws.html

TS:   // 同 JS
来源：http://dali.quarkkingdee.top/Article/details/gtagvkzwrj.html

Java: synchronized (this) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuzczvzkn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.wangdashe.top/Article/details/gtdoienvhx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.bjfxy.top/Article/details/gtjkmnxbzr.html

C#:   lock (gate) { shared++; }
来源：http://dali.0kj1m.cn/Article/details/gtohysrhda.html

[O04] 定义异步函数并等待
来源：http://dali.cdnleiting.top/Article/details/gtqntodhaw.html

Py:   async def f():⏎    await g()
来源：http://dali.shangyingyoupin.top/Article/details/gtzyvcjrwi.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gotoacloud.top/Article/details/gtogvujghg.html

JS:   async function f() { await g(); }
来源：http://dali.birdmap.top/Article/details/gtvqdxcwmb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhoulong.xyz/Article/details/gtrywcudwp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sxryk.cn/Article/details/gtbqoccnbs.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cucudq.cn/Article/details/gtnkfpbrqc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ydzc1.top/Article/details/gtqasigdhi.html

C#:   async Task F() { await G(); }
来源：http://dali.hfpthk.cn/Article/details/gtnykeuaae.html

[O05] 并发执行并等待全部完成
来源：http://dali.xinyue.icu/Article/details/gtxcoczoow.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hysaishi.cn/Article/details/gtvlekemmv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hongshengwenyu.top/Article/details/gteqpdewkf.html

JS:   await Promise.all(tasks)
来源：http://dali.vqdsnc.cn/Article/details/gtjxdtzmdm.html

TS:   await Promise.all(tasks)
来源：http://dali.zhiwuduotai.top/Article/details/gtdddmpjcw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.9152youxi.cn/Article/details/gtinkhrskd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjcgiofgt.html

Ruby: threads.map(&:join)
来源：http://dali.shangyingyoupin.top/Article/details/gtsakeudll.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cashguo.top/Article/details/gtdgxwkfyu.html

[O06] 使用进程池
来源：http://dali.cheryme.top/Article/details/gtbebsoimk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.meibo888.top/Article/details/gtigfiynkc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gtaokayvzu.html

JS:   // child_process / cluster 模块
来源：http://dali.svipenyu.cn/Article/details/gttlrcazmz.html

TS:   // child_process / cluster 模块
来源：http://dali.hfpthk.cn/Article/details/gtvcaynpnq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.quarkkingdee.top/Article/details/gtlnhgqkdf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xuetiantiany.cn/Article/details/gtdhfevccz.html

Ruby: // fork 块
来源：http://dali.aibaodan.cn/Article/details/gtsjwgrcqc.html

C#:   Parallel.For
来源：http://dali.yanxiufei.cn/Article/details/gtbmryecss.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtybbihxlq.html

P. 常用工具函数
来源：http://dali.tianlin.xyz/Article/details/gtnaqudluu.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtevsznosa.html

[P01] 生成 UUID
来源：http://dali.meibo888.top/Article/details/gtrpgahhqm.html

Py:   str(uuid.uuid4())
来源：http://dali.c1oappe.top/Article/details/gtuwidwdyi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.316326.xyz/Article/details/gtwwuekqgy.html

JS:   crypto.randomUUID()
来源：http://dali.tanke756.top/Article/details/gtulhcpkkk.html

TS:   crypto.randomUUID()
来源：http://dali.vqdsnc.cn/Article/details/gtuhgeoakk.html

Java: UUID.randomUUID().toString()
来源：http://dali.shuidangran.top/Article/details/gtyyssxgfe.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tian-w.cn/Article/details/gtycalhren.html

Ruby: SecureRandom.uuid
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrumjrsng.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrlmuxfv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj20258888.top/Article/details/gtwsktttqy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwgwggfps.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yongpay.top/Article/details/gtgzlimoqt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.tian-w.cn/Article/details/gtcqgjkced.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xuanzx.com/Article/details/gtyzlofzuy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.svipenyu.cn/Article/details/gtcsckbbem.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.quarkkingdee.top/Article/details/gttdracqku.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxomlrgvb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nanxinkj.top/Article/details/gtioeofrrm.html

[P03] 生成短随机字符串
来源：http://dali.cashguo.top/Article/details/gticsmtrgj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj202588.top/Article/details/gtvimkeumk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tanke756.top/Article/details/gtlcuijkbv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.havefunace.top/Article/details/gtjrnvdfko.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.smart0.xyz/Article/details/gtlsankpkn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.dashuyun.cn/Article/details/gtpngyghlu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shzxlz.cn/Article/details/gtanwxvajz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yuxming.cn/Article/details/gttqrulchq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhiwuduotai.top/Article/details/gttskyccwz.html

[P04] 求长度
来源：http://dali.ppjwa.cn/Article/details/gtkkbtvhjb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhoulong.xyz/Article/details/gtkylqtisl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gtkyixjssm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sxryk.cn/Article/details/gtmgjvmqrs.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cqqwz.cn/Article/details/gtxbizkmrp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhixingplan.top/Article/details/gtwacaoqqd.html

Go:   len(arr);  len(m)
来源：http://dali.jinqigfzy.top/Article/details/gttkxwhcmf.html

Ruby: x.length;  x.size
来源：http://dali.guannengcc.top/Article/details/gtyooxuyqw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yangfankeji.com/Article/details/gtowvltitz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj202588.top/Article/details/gtoooszxug.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ydzc1.top/Article/details/gtugrifike.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sxryk.cn/Article/details/gtvztmrguy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zycfv.cn/Article/details/gtcshpwjhw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cqqwz.cn/Article/details/gtfxhvwvny.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhengqikj.top/Article/details/gtxncfgsjk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.snrcjt.cn/Article/details/gtbykrhyof.html

Ruby: a == b
来源：http://dali.guowangkeji.top/Article/details/gtquvrkpzo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.kuanghao11.cn/Article/details/gtblduzmlk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.quarkkingdee.top/Article/details/gtmkiiqhps.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xinyue.icu/Article/details/gtvkvongsy.html

PHP:  if (empty($x)) {}
来源：http://dali.daxiang520.top/Article/details/gttxuemjny.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cdnleiting.top/Article/details/gtydhmgqnz.html

TS:   if (x == null) {}
来源：http://dali.havefunace.top/Article/details/gtddlivliq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cdnleiting.top/Article/details/gttfnfkloo.html

Go:   if x == nil {}
来源：http://dali.c1oappe.top/Article/details/gtsrlpvwfd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrkbldan.html

C#:   if (x is null) {}
来源：http://dali.sufxvd.cn/Article/details/gtjfvavtyd.html

[P07] 防抖与节流
来源：http://dali.sysykeji.top/Article/details/gturxnlcvy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinghuilouyu.cn/Article/details/gtzcipfpwx.html

PHP:  // 手写时间戳比较
来源：http://dali.pengpengdd.cyou/Article/details/gtxnnjoxtm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhixingplan.top/Article/details/gtolvbasxw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewlaqmse.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.daxiang520.top/Article/details/gtutjfvdff.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xylfe.cn/Article/details/gtooyakwnj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.pengpengdd.cyou/Article/details/gtfnmsnrwj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.birdmap.top/Article/details/gtzjmuhmfp.html

[P08] 处理浮点精度问题
来源：http://dali.birdmap.top/Article/details/gtwtnxddzo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hysaishi.cn/Article/details/gthoktnjkq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hnqzz.top/Article/details/gtnnorqabp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ivvv.top/Article/details/gtdjjtuzxp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.fengsongda.top/Article/details/gtgjoyuyne.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hnxiangtu.top/Article/details/gtrlslnhhh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jyoumei.cn/Article/details/gtfhdnlney.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.fengsongda.top/Article/details/gtxuqqyabf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cqqwz.cn/Article/details/gtxmkjoemc.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtvipfytyb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sweek.top/Article/details/gtncxfujnt.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtfqjfcqmj.html

[Q01] 创建表
来源：http://dali.andypj.xyz/Article/details/gtftdwnlxj.html

CREATE TABLE users (
来源：http://dali.iojbl.cn/Article/details/gtlghshzwo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dianchejie.cn/Article/details/gttfvvzrwu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.aizwys.cn/Article/details/gtfkorucdq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gogol.net.cn/Article/details/gtinfjnnez.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.pycfn.com/Article/details/gtttozhlzo.html

);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdsohipty.html

[Q02] 创建带外键的表
来源：http://dali.c1oappe.top/Article/details/gtrywjafyw.html

CREATE TABLE orders (
来源：http://dali.jqgufenzy.top/Article/details/gtcksyuswc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxuanxn.top/Article/details/gtxxfrhvim.html

user_id INT NOT NULL,
来源：http://dali.fzhhl.top/Article/details/gteianjftp.html

amount DECIMAL(10, 2),
来源：http://dali.zhiwuduotai.top/Article/details/gtznohmzri.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yueranfly.top/Article/details/gtuvtrchiz.html

);
来源：http://dali.quarkkingdee.top/Article/details/gtrnnmzsgc.html

[Q03] 增加列
来源：http://dali.tian-w.cn/Article/details/gtkbodsjcs.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.fzhhl.top/Article/details/gtdxriobmp.html

[Q04] 修改列类型
来源：http://dali.tanke756.top/Article/details/gtexycsltz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwrapnaro.html

[Q05] 重命名列
来源：http://dali.aizwys.cn/Article/details/gtqrkvcens.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hfpthk.cn/Article/details/gtdmxybcna.html

[Q06] 删除列
来源：http://dali.9152youxi.cn/Article/details/gtkpmtwktu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.smart0.xyz/Article/details/gtmlwbjhiq.html

[Q07] 删除表
来源：http://dali.zhengqikj.top/Article/details/gtqshrodmf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.tanke756.top/Article/details/gtcnsniymt.html

[Q08] 创建普通索引
来源：http://dali.sweek.top/Article/details/gthoggsuqw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhixingplan.top/Article/details/gtfwlbeeqh.html

[Q09] 创建唯一索引
来源：http://dali.sweek.top/Article/details/gtupsnthhw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.wangshuangyany.cn/Article/details/gtnjjtffcl.html

[Q10] 插入单行
来源：http://dali.yuxming.cn/Article/details/gtrinzyaic.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sxryk.cn/Article/details/gtpgqqkxtb.html

[Q11] 一次插入多行
来源：http://dali.dashuyun.cn/Article/details/gtdgttrghq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xylfe.cn/Article/details/gtswjaadki.html

[Q12] 插入后取自增 ID
来源：http://dali.aibaodan.cn/Article/details/gtujuaadjv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hnxiangtu.top/Article/details/gtbhiomgfd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhiwuduotai.top/Article/details/gtpvngbcuo.html

[Q13] 忽略重复插入
来源：http://dali.andypj.xyz/Article/details/gtisqvrual.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yuxming.cn/Article/details/gtpfywgrdz.html

[Q14] 存在则更新（upsert）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcvwwutdt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tianlin.xyz/Article/details/gtiksivyvt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hfpthk.cn/Article/details/gtockphzgc.html

[Q15] 查询全部
来源：http://dali.fengsongda.top/Article/details/gtasbejtsq.html

SELECT * FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgabzwyrr.html

[Q16] 查询指定列
来源：http://dali.hnxiangtu.top/Article/details/gtwcuphgrp.html

SELECT id, name FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtijaalqde.html

[Q17] 条件查询
来源：http://dali.hywenlv.cn/Article/details/gtwofggokk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj20258.top/Article/details/gtiriofpxb.html

[Q18] 模糊匹配
来源：http://dali.ppjwa.cn/Article/details/gtuvdbcxpb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.svipenyu.cn/Article/details/gtscmkordh.html

[Q19] 范围查询
来源：http://dali.meibo888.top/Article/details/gthguvjthx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cashguo.top/Article/details/gtrgcaztde.html

[Q20] IN 列表
来源：http://dali.chenlongwang.top/Article/details/gtzlpibcpe.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jqgfzy.top/Article/details/gtnbymthgn.html

[Q21] 空值判断
来源：http://dali.zdqjudy.top/Article/details/gtbpjyvusq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sweek.top/Article/details/gtuoxvegqp.html

[Q22] 排序
来源：http://dali.svipenyu.cn/Article/details/gtegyeptdb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shangyingyoupin.top/Article/details/gtegfjvrqx.html

[Q23] 分页
来源：http://dali.yongpay.top/Article/details/gtcmljfxyc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shuidangran.top/Article/details/gtoottjdty.html

[Q24] 去重
来源：http://dali.cqqwz.cn/Article/details/gtnuezkvks.html

SELECT DISTINCT city FROM users;
来源：http://dali.wangdashe.top/Article/details/gtujvovbjn.html

[Q25] 只取前 N 条
来源：http://dali.chenjidiqi.icu/Article/details/gttkekpron.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.aizwys.cn/Article/details/gtcmqkljdw.html

[Q26] 计数
来源：http://dali.yvedp.cn/Article/details/gtzcuxxjpl.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtnixopmmn.html

[Q27] 条件计数
来源：http://dali.zhengqikj.top/Article/details/gtzpulfcqy.html


<!-- 参考信息 -->