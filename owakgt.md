代发 wailian999

PHP:  // 递归实现，或用 usort
来源：http://dali.9152youxi.cn/Article/details/gt2frklumnv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigfzy.top/Article/details/gt2lolunldb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhongyouzk.top/Article/details/gt2mjyjspej.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yanxiufei.cn/Article/details/gt2dqqszymn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shangyingyoupin.top/Article/details/gt2jlqgdhwn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.9152youxi.cn/Article/details/gt2rnpaoooq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gzhubu.top/Article/details/gt2ozhvtfyb.html

[N04] 斐波那契数列
来源：http://dali.vqdsnc.cn/Article/details/gt2dxzjwvhi.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ydzc1.top/Article/details/gt2nzqjgrpf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.birdmap.top/Article/details/gt2ukvqzmmj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gt2psdwxezo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gt2wkzkalef.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lgbvnsgh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.kuanghao11.cn/Article/details/gt2ylmrzhdp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.guannengcc.top/Article/details/gt2akmzawqt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gt2ouwenqwp.html

[N05] 最大公约数
来源：http://dali.jqgfzy.top/Article/details/gt2dsvjrfqp.html

Py:   math.gcd(a, b)
来源：http://dali.aizwys.cn/Article/details/gt2xfjdkpbx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnxiangtu.top/Article/details/gt2zgabxmui.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ndlnlvpp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sysykeji.top/Article/details/gt2zdtvicoh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hammf.cn/Article/details/gt2jncpqrob.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bziwzrll.html

Ruby: a.gcd(b)
来源：http://dali.ivvv.top/Article/details/gt2tbqduzkf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.daxiang520.top/Article/details/gt2csopoefs.html

[N06] 判断回文字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bpakpkjy.html

Py:   s == s[::-1]
来源：http://dali.wangdashe.top/Article/details/gt2fooliocg.html

PHP:  $s === strrev($s);
来源：http://dali.shzxlz.cn/Article/details/gt2znfywzdr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gt2rxuotlmw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gt2lghpmcid.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yonumen.top/Article/details/gt2wlavovev.html

Go:   // 双指针从两端比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xexipqne.html

Ruby: s == s.reverse
来源：http://dali.pycfn.com/Article/details/gt2onliprzx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.snrcjt.cn/Article/details/gt2aoasyzwi.html

[N07] 两数之和（返回下标）
来源：http://dali.yuxming.cn/Article/details/gt2ptirechd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.andypj.xyz/Article/details/gt2xqdkyntn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuanzx.com/Article/details/gt2hnzrxqjk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gaohongyu789.top/Article/details/gt2euisngwj.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qqfzmbdh.html

Java: // 手写 HashMap
来源：http://dali.tian-w.cn/Article/details/gt2ilpxkuld.html

Go:   // 手写 map[int]int
来源：http://dali.yj20258.top/Article/details/gt2tnkywtta.html

Ruby: // 手写 Hash
来源：http://dali.ivvv.top/Article/details/gt2jshswgsq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenlongwang.top/Article/details/gt2bqliqxnh.html

[N08] 生成全排列
来源：http://dali.quarkkingdee.top/Article/details/gt2ybeawrzw.html

Py:   itertools.permutations(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pywkhxic.html

PHP:  // 手写递归交换
来源：http://dali.sweek.top/Article/details/gt2vllqgevs.html

JS:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gt2codnzyxe.html

TS:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2cbmdffjt.html

Java: // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gt2gxnhbdux.html

Go:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gt2ftahixaw.html

Ruby: arr.permutation.to_a
来源：http://dali.cheryme.top/Article/details/gt2nhvjgsrt.html

C#:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gt2mrxlhbcz.html

[N09] 栈与队列
来源：http://dali.gotoacloud.top/Article/details/gt2cjiizybq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.tian-w.cn/Article/details/gt2ipxhxnjd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shuidangran.top/Article/details/gt2xixyurya.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gt2yeimbfio.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tian-w.cn/Article/details/gt2turrujzd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.havefunace.top/Article/details/gt2aztoisnc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jyoumei.cn/Article/details/gt2okqkyqeg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tian-w.cn/Article/details/gt2raletspg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vqlwvscj.html

[N10] 链表节点定义
来源：http://dali.tanke756.top/Article/details/gt2jpxiccnu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ehwqpu.com/Article/details/gt2mbzgigus.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.meibo888.top/Article/details/gt2rwlcsgkp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cheryme.top/Article/details/gt2dqmweslq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yanxiufei.cn/Article/details/gt2vhcqtuck.html

Java: class Node { int v; Node next; }
来源：http://dali.jinqigfzy.top/Article/details/gt2jvfxhyoa.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.wangdashe.top/Article/details/gt2etzgqeho.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.meibo888.top/Article/details/gt2wavybyak.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.c1oappe.top/Article/details/gt2ntijjrtz.html

[N11] 二叉树中序遍历
来源：http://dali.jinqigufen.top/Article/details/gt2aowlkcvx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenjidiqi.icu/Article/details/gt2ncirtkrp.html

PHP:  // 手写递归函数
来源：http://dali.jqgufenzy.top/Article/details/gt2ybhglkpi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuxming.cn/Article/details/gt2xjsxqrpf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cashguo.top/Article/details/gt2xxlgsmoi.html

Java: // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gt2mzzfldwn.html

Go:   // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gt2bizixjxc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ybcxt.top/Article/details/gt2xhcqimav.html

C#:   // 手写递归
来源：http://dali.mhx1999.top/Article/details/gt2uuygglku.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cucudq.cn/Article/details/gt2joprsvmi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jqgufenzy.top/Article/details/gt2cavgborj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.9152youxi.cn/Article/details/gt2vmvyfnek.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tian-w.cn/Article/details/gt2zyblehds.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shzxlz.cn/Article/details/gt2dlskscxb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sysykeji.top/Article/details/gt2urqaxgjc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nanxinkj.top/Article/details/gt2enkdczlb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gotoacloud.top/Article/details/gt2oklontmi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jiagoushi.top/Article/details/gt2bhdyusoe.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2zmmdwnxq.html

O. 并发与异步
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oyksmjuk.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2thywnzex.html

[O01] 启动一个线程
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pctguhkn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ppjwa.cn/Article/details/gt2bmulcdby.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenzaomai.com/Article/details/gt2fugrdbeo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shuidangran.top/Article/details/gt2mquokfgo.html

TS:   // 同 JS
来源：http://dali.hysaishi.cn/Article/details/gt2zqohuexc.html

Java: new Thread(() -> f()).start()
来源：http://dali.jqgufenzy.top/Article/details/gt2scutzbsk.html

Go:   go f()
来源：http://dali.redwolf501.top/Article/details/gt2qwgcibwu.html

Ruby: Thread.new { f }
来源：http://dali.yj20258.top/Article/details/gt2veicanat.html

C#:   Task.Run(() => F());
来源：http://dali.hywenlv.cn/Article/details/gt2vkgvhlum.html

[O02] 使用线程池
来源：http://dali.sxryk.cn/Article/details/gt2fqntpbrb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.smart0.xyz/Article/details/gt2cvamlbvv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yanxiufei.cn/Article/details/gt2weoudpjo.html

JS:   // worker_threads 线程池
来源：http://dali.sufxvd.cn/Article/details/gt2yqdpqbvj.html

TS:   // worker_threads 线程池
来源：http://dali.yueranfly.top/Article/details/gt2sdxxbfio.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hywenlv.cn/Article/details/gt2zjhaorrk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.wangshuangyany.cn/Article/details/gt2dommllwn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.wangdashe.top/Article/details/gt2sujvcyka.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jiagoushi.top/Article/details/gt2bcgpuqna.html

[O03] 加锁保护共享数据
来源：http://dali.zhixingplan.top/Article/details/gt2ccktuhnx.html

Py:   with lock: shared += 1
来源：http://dali.gogol.net.cn/Article/details/gt2osndsorx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.meibo888.top/Article/details/gt2gyjdhmud.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shangyingyoupin.top/Article/details/gt2gandgxwh.html

TS:   // 同 JS
来源：http://dali.zhongyouzk.top/Article/details/gt2tyvflvrq.html

Java: synchronized (this) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gt2kzzzgujm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.quarkkingdee.top/Article/details/gt2ieipmfvn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.haohaochexian.top/Article/details/gt2qvrcbvvy.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ddpriptf.html

[O04] 定义异步函数并等待
来源：http://dali.hfpthk.cn/Article/details/gt2hhjtbemr.html

Py:   async def f():⏎    await g()
来源：http://dali.gzhubu.top/Article/details/gt2azijxqjr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zdqjudy.top/Article/details/gt2bddqbbdk.html

JS:   async function f() { await g(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2arpqkbpx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shzxlz.cn/Article/details/gt2dhnksbvn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yvedp.cn/Article/details/gt2pdfvzufd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hongshengwenyu.top/Article/details/gt2akokpvxs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hywenlv.cn/Article/details/gt2iuiwvcty.html

C#:   async Task F() { await G(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2vaksuncu.html

[O05] 并发执行并等待全部完成
来源：http://dali.jiagoushi.top/Article/details/gt2inktneut.html

Py:   asyncio.gather(*tasks)
来源：http://dali.andypj.xyz/Article/details/gt2mlocznej.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xuanzx.com/Article/details/gt2slhqwtum.html

JS:   await Promise.all(tasks)
来源：http://dali.zhengqikj.top/Article/details/gt2kzqeayha.html

TS:   await Promise.all(tasks)
来源：http://dali.yangfankeji.com/Article/details/gt2etykmwfz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zdqjudy.top/Article/details/gt2kronpjct.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jqgufenzy.top/Article/details/gt2dubqevim.html

Ruby: threads.map(&:join)
来源：http://dali.xylfe.cn/Article/details/gt2stcwmgjy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.wangdashe.top/Article/details/gt2mmxlowmr.html

[O06] 使用进程池
来源：http://dali.sweek.top/Article/details/gt2ilinkaty.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.smart0.xyz/Article/details/gt2jiclofog.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.fzhhl.top/Article/details/gt2hhmzowru.html

JS:   // child_process / cluster 模块
来源：http://dali.hongshengwenyu.top/Article/details/gt2qnoargde.html

TS:   // child_process / cluster 模块
来源：http://dali.chenjidiqi.icu/Article/details/gt2insarnsz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.c1oappe.top/Article/details/gt2jveolajv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2offqkbpv.html

Ruby: // fork 块
来源：http://dali.xinyue.icu/Article/details/gt2acojwwfi.html

C#:   Parallel.For
来源：http://dali.snrcjt.cn/Article/details/gt2uasptbey.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xhojccnp.html

P. 常用工具函数
来源：http://dali.yuxming.cn/Article/details/gt2ljxyeogq.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2prysbzzz.html

[P01] 生成 UUID
来源：http://dali.aizwys.cn/Article/details/gt2ifwohrym.html

Py:   str(uuid.uuid4())
来源：http://dali.zycfv.cn/Article/details/gt2ooldxctm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cashguo.top/Article/details/gt2hssfrpna.html

JS:   crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gt2ipvggkkm.html

TS:   crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hptjcuum.html

Java: UUID.randomUUID().toString()
来源：http://dali.wangdashe.top/Article/details/gt2sfshxvzo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nanxuanxn.top/Article/details/gt2miyvgbvg.html

Ruby: SecureRandom.uuid
来源：http://dali.shzxlz.cn/Article/details/gt2yegfajcq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhixingplan.top/Article/details/gt2hsgdywpj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.pycfn.com/Article/details/gt2wyneywlg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hysaishi.cn/Article/details/gt2mtmynyyu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zdqjudy.top/Article/details/gt2rlgozzko.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zdqjudy.top/Article/details/gt2jwwfvjrj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jiswqkhg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zycfv.cn/Article/details/gt2tivsyeji.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhengqikj.top/Article/details/gt2dodufdmk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shuidangran.top/Article/details/gt2ehzufinm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hnqzz.top/Article/details/gt2ivqukhly.html

[P03] 生成短随机字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2bjkufnrc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.316326.xyz/Article/details/gt2qxnyzelg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.meibo888.top/Article/details/gt2tzqsfwwm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2qbwlogsm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhengqikj.top/Article/details/gt2yhwkppsw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xinyue.icu/Article/details/gt2gjgxmcix.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yuanzhike.top/Article/details/gt2ibwbecpy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj202588.top/Article/details/gt2mulimxdq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhongyouzk.top/Article/details/gt2bnilayum.html

[P04] 求长度
来源：http://dali.fzhhl.top/Article/details/gt2cggohbpu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zfhbgtvp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gt2oykczjtj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigufen.top/Article/details/gt2jlcorffi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guowangkeji.top/Article/details/gt2ycavacqf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guannengcc.top/Article/details/gt2bsbwnyab.html

Go:   len(arr);  len(m)
来源：http://dali.jinqigufen.top/Article/details/gt2wvqaghcn.html

Ruby: x.length;  x.size
来源：http://dali.aibaodan.cn/Article/details/gt2jreiurxb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jqgfzy.top/Article/details/gt2dfxefbkr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.iojbl.cn/Article/details/gt2emkvjphq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinqigufen.top/Article/details/gt2rgylqvoq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xuetiantiany.cn/Article/details/gt2lxtagwfg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jyoumei.cn/Article/details/gt2abjdfeqn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yueranfly.top/Article/details/gt2lsatpcfh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cheryme.top/Article/details/gt2yuswoorj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.316326.xyz/Article/details/gt2atvomkic.html

Ruby: a == b
来源：http://dali.pycfn.com/Article/details/gt2cgpthhrx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jiagoushi.top/Article/details/gt2lqvrcqtf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinqigfzy.top/Article/details/gt2ihfmuxaj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinqigfzy.top/Article/details/gt2ewhoefwi.html

PHP:  if (empty($x)) {}
来源：http://dali.dianchejie.cn/Article/details/gt2rbbinoxb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.snrcjt.cn/Article/details/gt2rbrbkuzr.html

TS:   if (x == null) {}
来源：http://dali.gzhubu.top/Article/details/gt2eqhaxfrs.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.aizwys.cn/Article/details/gt2jaiwzydb.html

Go:   if x == nil {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xjtbxkus.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cheryme.top/Article/details/gt2yyzpstas.html

C#:   if (x is null) {}
来源：http://dali.redwolf501.top/Article/details/gt2dwpwaynf.html

[P07] 防抖与节流
来源：http://dali.yj202588.top/Article/details/gt2ydnmzzpr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ppjwa.cn/Article/details/gt2towxpvbb.html

PHP:  // 手写时间戳比较
来源：http://dali.guannengcc.top/Article/details/gt2fpzqupej.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgufenzy.top/Article/details/gt2mwqkcyms.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dashuyun.cn/Article/details/gt2zynbsfsf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.tian-w.cn/Article/details/gt2fcuttzsb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hnxiangtu.top/Article/details/gt2stumxesy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhiwuduotai.top/Article/details/gt2xbzfmwdk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.aizwys.cn/Article/details/gt2vplovsbf.html

[P08] 处理浮点精度问题
来源：http://dali.zycfv.cn/Article/details/gt2zmdjwgvf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.havefunace.top/Article/details/gt2vmhcxfrq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sweek.top/Article/details/gt2wzpqqipc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jiagoushi.top/Article/details/gt2qvsffkmq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gotoacloud.top/Article/details/gt2mmkqiqaz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yongpay.top/Article/details/gt2uzjlmcwa.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ivvv.top/Article/details/gt2gkgeezti.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tian-w.cn/Article/details/gt2zgconzkj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jlsjyb.cn/Article/details/gt2tjbckbnt.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2iqpykgqk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigufen.top/Article/details/gt2kduwtpdf.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2jdflbcin.html

[Q01] 创建表
来源：http://dali.birdmap.top/Article/details/gt2ibdwasci.html

CREATE TABLE users (
来源：http://dali.ivvv.top/Article/details/gt2jbolunlh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxuanxn.top/Article/details/gt2bxsrfyaq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinqigfzy.top/Article/details/gt2vepxlvmn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.birdmap.top/Article/details/gt2ivawoufi.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.daxiang520.top/Article/details/gt2zahuwiau.html

);
来源：http://dali.havefunace.top/Article/details/gt2iqlzswsp.html

[Q02] 创建带外键的表
来源：http://dali.jqgfzy.top/Article/details/gt2cafmmium.html

CREATE TABLE orders (
来源：http://dali.quarkkingdee.top/Article/details/gt2rsodoqqm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.andypj.xyz/Article/details/gt2qtosqios.html

user_id INT NOT NULL,
来源：http://dali.yj20258888.top/Article/details/gt2kmzbjezu.html

amount DECIMAL(10, 2),
来源：http://dali.yvedp.cn/Article/details/gt2ycvzrgvo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.daxiang520.top/Article/details/gt2oolsctgc.html

);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kwuhxinl.html

[Q03] 增加列
来源：http://dali.zhiwuduotai.top/Article/details/gt2fjaevxyg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hongshengwenyu.top/Article/details/gt2gemrcwkt.html

[Q04] 修改列类型
来源：http://dali.jiagoushi.top/Article/details/gt2wnwpwugg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zycfv.cn/Article/details/gt2jpwnfmyd.html

[Q05] 重命名列
来源：http://dali.pycfn.com/Article/details/gt2euupxadv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.chenzaomai.com/Article/details/gt2gmzdbhyd.html

[Q06] 删除列
来源：http://dali.kuanghao11.cn/Article/details/gt2texurqsy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gaohongyu789.top/Article/details/gt2ggzuwiqp.html

[Q07] 删除表
来源：http://dali.zycfv.cn/Article/details/gt2jhlyilzj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yangfankeji.com/Article/details/gt2ctdtdipy.html

[Q08] 创建普通索引
来源：http://dali.jyoumei.cn/Article/details/gt2xakkwzji.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.aizwys.cn/Article/details/gt2eoiwfzjm.html

[Q09] 创建唯一索引
来源：http://dali.pengpengdd.cyou/Article/details/gt2kxwanbld.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenlongwang.top/Article/details/gt2jhvibjoi.html

[Q10] 插入单行
来源：http://dali.jyoumei.cn/Article/details/gt2nmhlpayh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.0kj1m.cn/Article/details/gt2tokhskzh.html

[Q11] 一次插入多行
来源：http://dali.yongpay.top/Article/details/gt2wlxaxhon.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.chenlongwang.top/Article/details/gt2coppykfl.html

[Q12] 插入后取自增 ID
来源：http://dali.sweek.top/Article/details/gt2gciwrkzr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zdqjudy.top/Article/details/gt2fekmgjvq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.smart0.xyz/Article/details/gt2kfppfxnb.html

[Q13] 忽略重复插入
来源：http://dali.zycfv.cn/Article/details/gt2uqwomudd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.meibo888.top/Article/details/gt2btzpysmg.html

[Q14] 存在则更新（upsert）
来源：http://dali.yangfankeji.com/Article/details/gt2twnhpnhe.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ppjwa.cn/Article/details/gt2ylrwlhhw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.iojbl.cn/Article/details/gt2nkfrdxrc.html

[Q15] 查询全部
来源：http://dali.shzxlz.cn/Article/details/gt2nweccobh.html

SELECT * FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ztksjtrf.html

[Q16] 查询指定列
来源：http://dali.wangdashe.top/Article/details/gt2tkuucius.html

SELECT id, name FROM users;
来源：http://dali.tanke756.top/Article/details/gt2mfkfxbgu.html

[Q17] 条件查询
来源：http://dali.yangfankeji.com/Article/details/gt2lxeztulv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.pycfn.com/Article/details/gt2bxmhoydo.html

[Q18] 模糊匹配
来源：http://dali.pycfn.com/Article/details/gt2rsyeozwc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jiagoushi.top/Article/details/gt2xbryynbp.html

[Q19] 范围查询
来源：http://dali.chenlongwang.top/Article/details/gt2zexfjlvm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhiwuduotai.top/Article/details/gt2kfzfihba.html

[Q20] IN 列表
来源：http://dali.jiagoushi.top/Article/details/gt2qwmfnrai.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jelvhrpv.html

[Q21] 空值判断
来源：http://dali.xylfe.cn/Article/details/gt2uabpnusn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zycfv.cn/Article/details/gt2agndigql.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2srvdktco.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2czunygbb.html

[Q23] 分页
来源：http://dali.daria6918.cn/Article/details/gt2xjwkwelu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.havefunace.top/Article/details/gt2rowhuami.html

[Q24] 去重
来源：http://dali.yangfankeji.com/Article/details/gt2yvdykmaq.html

SELECT DISTINCT city FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2nzawarsz.html

[Q25] 只取前 N 条
来源：http://dali.daria6918.cn/Article/details/gt2vpqvyqpf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.mhx1999.top/Article/details/gt2gusqjzje.html

[Q26] 计数
来源：http://dali.ehwqpu.com/Article/details/gt2pvkqapyl.html

SELECT COUNT(*) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2azfvxrug.html

[Q27] 条件计数
来源：http://dali.dashuyun.cn/Article/details/gt2kkhroktu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2ghelkcrf.html

[Q28] 求和与平均
来源：http://dali.feifeiyinyue.top/Article/details/gt2qipsxxyc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gt2emcjnsck.html

[Q29] 最大最小值
来源：http://dali.chenlongwang.top/Article/details/gt2viuuimyg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2opnaqqax.html

[Q30] 分组统计
来源：http://dali.hywenlv.cn/Article/details/gt2xzgqlfxq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gt2eeerslji.html

[Q31] 分组后过滤
来源：http://dali.jiagoushi.top/Article/details/gt2jbldbkwx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cqqwz.cn/Article/details/gt2ltyxsknz.html

[Q32] 分组拼接字符串
来源：http://dali.shuidangran.top/Article/details/gt2szyfrxue.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gt2tnsmlhut.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuanzx.com/Article/details/gt2bpmqbqmc.html


<!-- 参考信息 -->