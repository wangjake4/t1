代发 wailian999

PHP:  // 递归实现，或用 usort
来源：http://dali.jqgfzy.top/Article/details/gt2pfouovwc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hysaishi.cn/Article/details/gt2lctwchsv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daria6918.cn/Article/details/gt2mzxrcsrr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ppjwa.cn/Article/details/gt2thvcsfnc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zgkrypho.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tianlin.xyz/Article/details/gt2suamsvnz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.daria6918.cn/Article/details/gt2vvkzkuxh.html

[N04] 斐波那契数列
来源：http://dali.0kj1m.cn/Article/details/gt2czbxtpxr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.pycfn.com/Article/details/gt2xnowmqof.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qstkgzqc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gt2kzflcglz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gt2znckhgek.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.fengsongda.top/Article/details/gt2sxfvzbcn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shuidangran.top/Article/details/gt2kzuzmpmo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.iojbl.cn/Article/details/gt2zbecaegc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gt2ludnsquk.html

[N05] 最大公约数
来源：http://dali.hysaishi.cn/Article/details/gt2qhscgmwh.html

Py:   math.gcd(a, b)
来源：http://dali.yuanzhike.top/Article/details/gt2qhadaepu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.daxiang520.top/Article/details/gt2cibdxihe.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2borxxmsu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yueranfly.top/Article/details/gt2zllppxzv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cashguo.top/Article/details/gt2xxywweaq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.wangdashe.top/Article/details/gt2mnmsfzsp.html

Ruby: a.gcd(b)
来源：http://dali.andypj.xyz/Article/details/gt2ashlgbkr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhixingplan.top/Article/details/gt2rkzkibxk.html

[N06] 判断回文字符串
来源：http://dali.andypj.xyz/Article/details/gt2wqgsxwkt.html

Py:   s == s[::-1]
来源：http://dali.xuanzx.com/Article/details/gt2nemopqhi.html

PHP:  $s === strrev($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cqcfuhai.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gt2reeozgyy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gt2drpgqfwm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guannengcc.top/Article/details/gt2jpwcvqoq.html

Go:   // 双指针从两端比较
来源：http://dali.316326.xyz/Article/details/gt2jgkharyt.html

Ruby: s == s.reverse
来源：http://dali.guowangkeji.top/Article/details/gt2rrecjaru.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hnqzz.top/Article/details/gt2wchiponm.html

[N07] 两数之和（返回下标）
来源：http://dali.jqgufenzy.top/Article/details/gt2rebpebmd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.smart0.xyz/Article/details/gt2tivfvocz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.aibaodan.cn/Article/details/gt2eygfhien.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenjidiqi.icu/Article/details/gt2aldrmusk.html

TS:   // 手写 Map<string, number>
来源：http://dali.jlsjyb.cn/Article/details/gt2gbtniwck.html

Java: // 手写 HashMap
来源：http://dali.meibo888.top/Article/details/gt2jkhqdbal.html

Go:   // 手写 map[int]int
来源：http://dali.jiagoushi.top/Article/details/gt2isosbbjt.html

Ruby: // 手写 Hash
来源：http://dali.daria6918.cn/Article/details/gt2duengypv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.fengsongda.top/Article/details/gt2izmlpuce.html

[N08] 生成全排列
来源：http://dali.havefunace.top/Article/details/gt2cqtrijal.html

Py:   itertools.permutations(arr)
来源：http://dali.316326.xyz/Article/details/gt2wnmebzcm.html

PHP:  // 手写递归交换
来源：http://dali.jlsjyb.cn/Article/details/gt2vooqgxxw.html

JS:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gt2sskhtete.html

TS:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gt2dbwjrnhh.html

Java: // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gt2muctagri.html

Go:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gt2focndwyh.html

Ruby: arr.permutation.to_a
来源：http://dali.hnqzz.top/Article/details/gt2eqahqqml.html

C#:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gt2tufdxswa.html

[N09] 栈与队列
来源：http://dali.havefunace.top/Article/details/gt2ytfnbwre.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nanxuanxn.top/Article/details/gt2oqmpcbkf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.andypj.xyz/Article/details/gt2wmtqvvfr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gt2omjqoszz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jqgfzy.top/Article/details/gt2dylnrjcw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.fzhhl.top/Article/details/gt2ycisflez.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2zftzjiar.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cygjlvxh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.mhx1999.top/Article/details/gt2gniwyglk.html

[N10] 链表节点定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2shrmcmxn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2auxeifyc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xuanzx.com/Article/details/gt2wribxipx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigufen.top/Article/details/gt2kayosbkc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wssnxztx.html

Java: class Node { int v; Node next; }
来源：http://dali.chenlongwang.top/Article/details/gt2nvthkrut.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cheryme.top/Article/details/gt2tyosaytj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.dashuyun.cn/Article/details/gt2kbiniwsb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yuxming.cn/Article/details/gt2gijofakj.html

[N11] 二叉树中序遍历
来源：http://dali.daxiang520.top/Article/details/gt2yzeylkns.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.nanxuanxn.top/Article/details/gt2rhynxsdv.html

PHP:  // 手写递归函数
来源：http://dali.sweek.top/Article/details/gt2bjmhcqgu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xziqi.cn/Article/details/gt2xmgdypex.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnqzz.top/Article/details/gt2ceadlcld.html

Java: // 手写递归
来源：http://dali.bjfxy.top/Article/details/gt2ovzmwjss.html

Go:   // 手写递归
来源：http://dali.cheryme.top/Article/details/gt2jmhhyzyg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cucudq.cn/Article/details/gt2msnsvxlp.html

C#:   // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gt2efucdmgz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.fengsongda.top/Article/details/gt2apooajgx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zdqjudy.top/Article/details/gt2vjpgpdgb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.aibaodan.cn/Article/details/gt2qlbvhfvr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258.top/Article/details/gt2kjqbaafo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ybcxt.top/Article/details/gt2guvxizps.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sufxvd.cn/Article/details/gt2hgxligje.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yueranfly.top/Article/details/gt2yqgzxtub.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.birdmap.top/Article/details/gt2nhwwtbbf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.iojbl.cn/Article/details/gt2ciscsuwo.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2uykwwohk.html

O. 并发与异步
来源：http://dali.gzhubu.top/Article/details/gt2oxlhxljo.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2lkueghju.html

[O01] 启动一个线程
来源：http://dali.daria6918.cn/Article/details/gt2ivwdpkmf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jyoumei.cn/Article/details/gt2cldgwkfs.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xylfe.cn/Article/details/gt2exudxgll.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cqqwz.cn/Article/details/gt2xilkdaib.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gt2vpcreask.html

Java: new Thread(() -> f()).start()
来源：http://dali.aizwys.cn/Article/details/gt2saqidvza.html

Go:   go f()
来源：http://dali.hfpthk.cn/Article/details/gt2bsdwthhk.html

Ruby: Thread.new { f }
来源：http://dali.hnxiangtu.top/Article/details/gt2jftyyqzl.html

C#:   Task.Run(() => F());
来源：http://dali.shuidangran.top/Article/details/gt2jhlssenr.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcjmmte.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xuetiantiany.cn/Article/details/gt2oukbngij.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ehwqpu.com/Article/details/gt2vbxfzfpn.html

JS:   // worker_threads 线程池
来源：http://dali.316326.xyz/Article/details/gt2rdytlobs.html

TS:   // worker_threads 线程池
来源：http://dali.sysykeji.top/Article/details/gt2wxpvkqjt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhengqikj.top/Article/details/gt2ixdnviui.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ppjwa.cn/Article/details/gt2dmbaxvde.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cucudq.cn/Article/details/gt2opxyjagq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.andypj.xyz/Article/details/gt2uupolpok.html

[O03] 加锁保护共享数据
来源：http://dali.snrcjt.cn/Article/details/gt2avwexacs.html

Py:   with lock: shared += 1
来源：http://dali.nanxuanxn.top/Article/details/gt2soqbcinj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.vqdsnc.cn/Article/details/gt2itqpojbr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cucudq.cn/Article/details/gt2xwdbknqv.html

TS:   // 同 JS
来源：http://dali.ppjwa.cn/Article/details/gt2kfhdkzoz.html

Java: synchronized (this) { shared++; }
来源：http://dali.guannengcc.top/Article/details/gt2wxrltxov.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tian-w.cn/Article/details/gt2dzooncad.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xuanzx.com/Article/details/gt2trcrppdw.html

C#:   lock (gate) { shared++; }
来源：http://dali.tianlin.xyz/Article/details/gt2jvkytaif.html

[O04] 定义异步函数并等待
来源：http://dali.daxiang520.top/Article/details/gt2vsljaipj.html

Py:   async def f():⏎    await g()
来源：http://dali.jyoumei.cn/Article/details/gt2ntldnqhx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tianlin.xyz/Article/details/gt2cqjywyvm.html

JS:   async function f() { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gt2ihzdrums.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lblkxtqw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fzhhl.top/Article/details/gt2cyjentli.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.316326.xyz/Article/details/gt2qwsetovz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qnnvygzx.html

C#:   async Task F() { await G(); }
来源：http://dali.ivvv.top/Article/details/gt2lkoveyaz.html

[O05] 并发执行并等待全部完成
来源：http://dali.nwbrower.top/Article/details/gt2qlbehdov.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hywenlv.cn/Article/details/gt2ohevlvyl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.havefunace.top/Article/details/gt2jehdsfgk.html

JS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gt2ehgjxzfe.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjtsxsh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zdqjudy.top/Article/details/gt2gczulshu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.bjfxy.top/Article/details/gt2dfnoepjm.html

Ruby: threads.map(&:join)
来源：http://dali.ivvv.top/Article/details/gt2pwfbzphr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tianlin.xyz/Article/details/gt2oulzbvcp.html

[O06] 使用进程池
来源：http://dali.zycfv.cn/Article/details/gt2ekqvrfgd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tian-w.cn/Article/details/gt2rpftngcx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2govjddyz.html

JS:   // child_process / cluster 模块
来源：http://dali.jinqigfzy.top/Article/details/gt2igrjjjnd.html

TS:   // child_process / cluster 模块
来源：http://dali.sxryk.cn/Article/details/gt2bnsutmbc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhongyouzk.top/Article/details/gt2zcfyfinu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.bjfxy.top/Article/details/gt2zbrzeofi.html

Ruby: // fork 块
来源：http://dali.yueranfly.top/Article/details/gt2ioeuaudz.html

C#:   Parallel.For
来源：http://dali.tianlin.xyz/Article/details/gt2fbaynkwy.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2sxroznfb.html

P. 常用工具函数
来源：http://dali.fengsongda.top/Article/details/gt2aszjjhsr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2odwiegqc.html

[P01] 生成 UUID
来源：http://dali.xylfe.cn/Article/details/gt2dghegwdn.html

Py:   str(uuid.uuid4())
来源：http://dali.quarkkingdee.top/Article/details/gt2gyanvxag.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hongshengwenyu.top/Article/details/gt2zuslqksl.html

JS:   crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gt2ifpvpagj.html

TS:   crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gt2jqpwisky.html

Java: UUID.randomUUID().toString()
来源：http://dali.tianlin.xyz/Article/details/gt2ywwlrvqc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xinyue.icu/Article/details/gt2xqamceqb.html

Ruby: SecureRandom.uuid
来源：http://dali.mhx1999.top/Article/details/gt2uqkxbevc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.daxiang520.top/Article/details/gt2witubvxr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.dashuyun.cn/Article/details/gt2ebmqcgql.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.0kj1m.cn/Article/details/gt2oaxbnxcj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ehwqpu.com/Article/details/gt2srpffjvh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.wangshuangyany.cn/Article/details/gt2pxitgqww.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.bjfxy.top/Article/details/gt2smnokaei.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenlongwang.top/Article/details/gt2vopreisj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yongpay.top/Article/details/gt2dzaonzfg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.pycfn.com/Article/details/gt2mxvpblhe.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.dianchejie.cn/Article/details/gt2fsoerzta.html

[P03] 生成短随机字符串
来源：http://dali.9152youxi.cn/Article/details/gt2qnxtlwvb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cheryme.top/Article/details/gt2upcylblx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jyoumei.cn/Article/details/gt2issfjrua.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigufen.top/Article/details/gt2atgmemgf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gt2tjpvectr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhoulong.xyz/Article/details/gt2wljpcphw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhengqikj.top/Article/details/gt2pmottrzd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wthobzow.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.dashuyun.cn/Article/details/gt2mnfblvir.html

[P04] 求长度
来源：http://dali.hfpthk.cn/Article/details/gt2pwhtrhgg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hfpthk.cn/Article/details/gt2bmmcqsoc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gt2axjtkmdf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuetiantiany.cn/Article/details/gt2wmorglwk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.feifeiyinyue.top/Article/details/gt2sfgzgnhj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tianlin.xyz/Article/details/gt2pogagtww.html

Go:   len(arr);  len(m)
来源：http://dali.snrcjt.cn/Article/details/gt2lscacmcb.html

Ruby: x.length;  x.size
来源：http://dali.kuanghao11.cn/Article/details/gt2ehzcwitu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.kuanghao11.cn/Article/details/gt2ibntnyze.html

[P05] 判断两个对象内容是否相等
来源：http://dali.meibo888.top/Article/details/gt2xtsiaohg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yangfankeji.com/Article/details/gt2nufclgww.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yongpay.top/Article/details/gt2jqgazoee.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xuanzx.com/Article/details/gt2tihvvhcs.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cqqwz.cn/Article/details/gt2cixckpqz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hammf.cn/Article/details/gt2zcldjzvh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj20258.top/Article/details/gt2jdccuzza.html

Ruby: a == b
来源：http://dali.yueranfly.top/Article/details/gt2gchtttng.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yueranfly.top/Article/details/gt2gsjcvvlr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2najonddr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yanxiufei.cn/Article/details/gt2fjqadmap.html

PHP:  if (empty($x)) {}
来源：http://dali.pycfn.com/Article/details/gt2fqucbenl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zdqjudy.top/Article/details/gt2pyicebkb.html

TS:   if (x == null) {}
来源：http://dali.sxryk.cn/Article/details/gt2pgytxmwz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2oixhspri.html

Go:   if x == nil {}
来源：http://dali.tanke756.top/Article/details/gt2trmgysgr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shuidangran.top/Article/details/gt2nwvmvkbs.html

C#:   if (x is null) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2czjfhiwd.html

[P07] 防抖与节流
来源：http://dali.sufxvd.cn/Article/details/gt2mrpiumdm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yueranfly.top/Article/details/gt2aahhizco.html

PHP:  // 手写时间戳比较
来源：http://dali.hysaishi.cn/Article/details/gt2bypjatny.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cheryme.top/Article/details/gt2xgsyfsrh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gt2qryzypay.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2thuojlri.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yvedp.cn/Article/details/gt2nnwoozac.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.guannengcc.top/Article/details/gt2fdvthbkk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.tianlin.xyz/Article/details/gt2gpuexdzz.html

[P08] 处理浮点精度问题
来源：http://dali.fengsongda.top/Article/details/gt2fxdhzraa.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.wangshuangyany.cn/Article/details/gt2eddxfzsw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenlongwang.top/Article/details/gt2hxbiikst.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yangfankeji.com/Article/details/gt2tfoybhza.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vraywofx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.smart0.xyz/Article/details/gt2rxilmzph.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhixingplan.top/Article/details/gt2dqyvuvfd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ivvv.top/Article/details/gt2khwuyxsa.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cqqwz.cn/Article/details/gt2jnibejtp.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2bnrlslby.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wxmulpwl.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2ohmxjifx.html

[Q01] 创建表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2izjjxuso.html

CREATE TABLE users (
来源：http://dali.ehwqpu.com/Article/details/gt2hcecphqt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fbbdwkzu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.iojbl.cn/Article/details/gt2crlwseap.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenzaomai.com/Article/details/gt2lydjgaou.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yvedp.cn/Article/details/gt2folztnqm.html

);
来源：http://dali.pengpengdd.cyou/Article/details/gt2wtblxgfn.html

[Q02] 创建带外键的表
来源：http://dali.yvedp.cn/Article/details/gt2rfcfimez.html

CREATE TABLE orders (
来源：http://dali.nanxuanxn.top/Article/details/gt2crhzgesb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.feifeiyinyue.top/Article/details/gt2vhyskmjq.html

user_id INT NOT NULL,
来源：http://dali.ybcxt.top/Article/details/gt2pwcxlgdp.html

amount DECIMAL(10, 2),
来源：http://dali.hysaishi.cn/Article/details/gt2webgclil.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yuxming.cn/Article/details/gt2amdroiqb.html

);
来源：http://dali.yongpay.top/Article/details/gt2vbdrjzhl.html

[Q03] 增加列
来源：http://dali.jinqigfzy.top/Article/details/gt2ioxlmcyv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhengqikj.top/Article/details/gt2oifsingr.html

[Q04] 修改列类型
来源：http://dali.gotoacloud.top/Article/details/gt2mrdkxbmn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinqigufen.top/Article/details/gt2tgktvsep.html

[Q05] 重命名列
来源：http://dali.cashguo.top/Article/details/gt2wgqktvkq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.daria6918.cn/Article/details/gt2llspplqw.html

[Q06] 删除列
来源：http://dali.aizwys.cn/Article/details/gt2beuhqmxu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nanxuanxn.top/Article/details/gt2sjvvgelu.html

[Q07] 删除表
来源：http://dali.birdmap.top/Article/details/gt2tpefnmxe.html

DROP TABLE IF EXISTS orders;
来源：http://dali.tanke756.top/Article/details/gt2mutwqhen.html

[Q08] 创建普通索引
来源：http://dali.meibo888.top/Article/details/gt2ygzsnxws.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jlsjyb.cn/Article/details/gt2dbvrraen.html

[Q09] 创建唯一索引
来源：http://dali.ppjwa.cn/Article/details/gt2vdvhdqjj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ehwqpu.com/Article/details/gt2pzmnzswx.html

[Q10] 插入单行
来源：http://dali.daxiang520.top/Article/details/gt2dpctaxoj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xuanzx.com/Article/details/gt2mhktayto.html

[Q11] 一次插入多行
来源：http://dali.fengsongda.top/Article/details/gt2bvqojzgs.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.smart0.xyz/Article/details/gt2hmxwdsve.html

[Q12] 插入后取自增 ID
来源：http://dali.fengsongda.top/Article/details/gt2hnyujdaw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.316326.xyz/Article/details/gt2wpwgmxwu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zycfv.cn/Article/details/gt2xoiyzfck.html

[Q13] 忽略重复插入
来源：http://dali.316326.xyz/Article/details/gt2xlrdwnjs.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.c1oappe.top/Article/details/gt2fgduynrn.html

[Q14] 存在则更新（upsert）
来源：http://dali.ehwqpu.com/Article/details/gt2csetpwhv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xziqi.cn/Article/details/gt2ghepyveg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.meibo888.top/Article/details/gt2lwibyjhl.html

[Q15] 查询全部
来源：http://dali.yanxiufei.cn/Article/details/gt2iznoxyei.html

SELECT * FROM users;
来源：http://dali.yongpay.top/Article/details/gt2xxlimfwv.html

[Q16] 查询指定列
来源：http://dali.dashuyun.cn/Article/details/gt2nwlrwbrm.html

SELECT id, name FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lpejormv.html

[Q17] 条件查询
来源：http://dali.guowangkeji.top/Article/details/gt2msbhreek.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yuxming.cn/Article/details/gt2fxeobskw.html

[Q18] 模糊匹配
来源：http://dali.nanxinkj.top/Article/details/gt2nstgjsze.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj202588.top/Article/details/gt2ushjrgna.html

[Q19] 范围查询
来源：http://dali.ybcxt.top/Article/details/gt2qejmhbnt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.pycfn.com/Article/details/gt2pjbkhknr.html

[Q20] IN 列表
来源：http://dali.c1oappe.top/Article/details/gt2ogbalmgv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.aizwys.cn/Article/details/gt2noekgdcg.html

[Q21] 空值判断
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oqtgpygp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.quarkkingdee.top/Article/details/gt2kwxudqoq.html

[Q22] 排序
来源：http://dali.yj202588.top/Article/details/gt2yprrjphr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hysaishi.cn/Article/details/gt2iyvzwcfa.html

[Q23] 分页
来源：http://dali.yj20258.top/Article/details/gt2cychwxyf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj20258888.top/Article/details/gt2kzfylngo.html

[Q24] 去重
来源：http://dali.hysaishi.cn/Article/details/gt2tgmylgmi.html

SELECT DISTINCT city FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2zjihigap.html

[Q25] 只取前 N 条
来源：http://dali.smart0.xyz/Article/details/gt2fytbydev.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.pycfn.com/Article/details/gt2kcloqold.html

[Q26] 计数
来源：http://dali.redwolf501.top/Article/details/gt2ypgxvgdg.html

SELECT COUNT(*) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2agitvrtf.html

[Q27] 条件计数
来源：http://dali.chenzaomai.com/Article/details/gt2kqbxilec.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2wlehngxp.html

[Q28] 求和与平均
来源：http://dali.zhoulong.xyz/Article/details/gt2uzzwteak.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uopsohun.html

[Q29] 最大最小值
来源：http://dali.zycfv.cn/Article/details/gt2jsasxyeh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hammf.cn/Article/details/gt2yifysutc.html

[Q30] 分组统计
来源：http://dali.xuanzx.com/Article/details/gt2gzostiok.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gt2jpnsgtcu.html

[Q31] 分组后过滤
来源：http://dali.zhengqikj.top/Article/details/gt2muouvawg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.feifeiyinyue.top/Article/details/gt2xqcqofdp.html

[Q32] 分组拼接字符串
来源：http://dali.xinyue.icu/Article/details/gt2fvisbokw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gt2sobqkomd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tanke756.top/Article/details/gt2pnglmdse.html


<!-- 参考信息 -->