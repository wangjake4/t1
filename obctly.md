代发 wailian999

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ybcxt.top/Article/details/gt2toboyipd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ydzc1.top/Article/details/gt2yacyabbj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2jbvopqbe.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gt2tpqclmkb.html

[N05] 最大公约数
来源：http://dali.fzhhl.top/Article/details/gt2laiozqsu.html

Py:   math.gcd(a, b)
来源：http://dali.zhixingplan.top/Article/details/gt2htcajovo.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.haohaochexian.top/Article/details/gt2tcwxpayq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.haohaochexian.top/Article/details/gt2vadssrtw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ivvv.top/Article/details/gt2owugqiqi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yuxming.cn/Article/details/gt2tcapbasu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xuetiantiany.cn/Article/details/gt2chbglvkp.html

Ruby: a.gcd(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2latnsnvn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenzaomai.com/Article/details/gt2xeajetts.html

[N06] 判断回文字符串
来源：http://dali.hywenlv.cn/Article/details/gt2kxksjhij.html

Py:   s == s[::-1]
来源：http://dali.c1oappe.top/Article/details/gt2ohnzdizz.html

PHP:  $s === strrev($s);
来源：http://dali.0kj1m.cn/Article/details/gt2gbteerlb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gt2hbrurgxw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gt2yxjijxqe.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenzaomai.com/Article/details/gt2evxdbpwp.html

Go:   // 双指针从两端比较
来源：http://dali.yj202588.top/Article/details/gt2qhvugbak.html

Ruby: s == s.reverse
来源：http://dali.zycfv.cn/Article/details/gt2fuqnaiqj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.smart0.xyz/Article/details/gt2auurqynf.html

[N07] 两数之和（返回下标）
来源：http://dali.yongpay.top/Article/details/gt2pnsqcqrm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cashguo.top/Article/details/gt2vwnhohnf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rrehuber.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gogol.net.cn/Article/details/gt2ulfgkmtg.html

TS:   // 手写 Map<string, number>
来源：http://dali.xinyue.icu/Article/details/gt2vzaevvia.html

Java: // 手写 HashMap
来源：http://dali.cashguo.top/Article/details/gt2izaopjzn.html

Go:   // 手写 map[int]int
来源：http://dali.guannengcc.top/Article/details/gt2ipsdfoxc.html

Ruby: // 手写 Hash
来源：http://dali.xuetiantiany.cn/Article/details/gt2bmiaycbd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.kuanghao11.cn/Article/details/gt2tbjriaif.html

[N08] 生成全排列
来源：http://dali.shuidangran.top/Article/details/gt2idhyqdcq.html

Py:   itertools.permutations(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2ffemhief.html

PHP:  // 手写递归交换
来源：http://dali.havefunace.top/Article/details/gt2fjoyrils.html

JS:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gt2fdumhmza.html

TS:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gt2xkibaycj.html

Java: // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gt2lqyjhzix.html

Go:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gt2wvbxqpow.html

Ruby: arr.permutation.to_a
来源：http://dali.chenjidiqi.icu/Article/details/gt2xjnbctvo.html

C#:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gt2qbzhqnyo.html

[N09] 栈与队列
来源：http://dali.yuxming.cn/Article/details/gt2sclrfxnl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hywenlv.cn/Article/details/gt2vvntsgdt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gt2fakmgyik.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj20258.top/Article/details/gt2cupxlnon.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xziqi.cn/Article/details/gt2asahtohe.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.dianchejie.cn/Article/details/gt2vtikaopq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sysykeji.top/Article/details/gt2svgiuerg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xinyue.icu/Article/details/gt2khbdpeus.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.feifeiyinyue.top/Article/details/gt2nqzglkjh.html

[N10] 链表节点定义
来源：http://dali.cucudq.cn/Article/details/gt2vtdmserm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.guowangkeji.top/Article/details/gt2jxftmjnz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.smart0.xyz/Article/details/gt2szyxyhot.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xziqi.cn/Article/details/gt2rjhedrfy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.fengsongda.top/Article/details/gt2rzmsehix.html

Java: class Node { int v; Node next; }
来源：http://dali.birdmap.top/Article/details/gt2mqymouju.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sufxvd.cn/Article/details/gt2xjotfjke.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daxiang520.top/Article/details/gt2leyvelxs.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.snrcjt.cn/Article/details/gt2evursmpy.html

[N11] 二叉树中序遍历
来源：http://dali.yangfankeji.com/Article/details/gt2ffxenebt.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shuidangran.top/Article/details/gt2porteiri.html

PHP:  // 手写递归函数
来源：http://dali.fengsongda.top/Article/details/gt2gpxhnrog.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenjidiqi.icu/Article/details/gt2eiwdsdxr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dashuyun.cn/Article/details/gt2ikdtwczk.html

Java: // 手写递归
来源：http://dali.ivvv.top/Article/details/gt2gqelvxwz.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnrljkw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.quarkkingdee.top/Article/details/gt2menhtjrd.html

C#:   // 手写递归
来源：http://dali.daxiang520.top/Article/details/gt2lgvlmlty.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.fengsongda.top/Article/details/gt2qyfxfqbg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhoulong.xyz/Article/details/gt2lzbrmzhj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhixingplan.top/Article/details/gt2qgcouuqt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgfzy.top/Article/details/gt2uapjdyog.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258.top/Article/details/gt2htutjjab.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hysaishi.cn/Article/details/gt2dblfkofv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zdqjudy.top/Article/details/gt2pjbtpwox.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gzhubu.top/Article/details/gt2zkhvkxwr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnxiangtu.top/Article/details/gt2iljqinri.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2vnswtgqv.html

O. 并发与异步
来源：http://dali.shzxlz.cn/Article/details/gt2ziqvndqw.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2jbatwtkc.html

[O01] 启动一个线程
来源：http://dali.jinghuilouyu.cn/Article/details/gt2skqsxfpq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.0kj1m.cn/Article/details/gt2glpxwhgw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wwmpcprl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jlsjyb.cn/Article/details/gt2exhmlmfl.html

TS:   // 同 JS
来源：http://dali.0kj1m.cn/Article/details/gt2ulkhkwnx.html

Java: new Thread(() -> f()).start()
来源：http://dali.xziqi.cn/Article/details/gt2orsjaivu.html

Go:   go f()
来源：http://dali.nanxinkj.top/Article/details/gt2myxzlyue.html

Ruby: Thread.new { f }
来源：http://dali.svipenyu.cn/Article/details/gt2aiexqjbf.html

C#:   Task.Run(() => F());
来源：http://dali.shuidangran.top/Article/details/gt2zlvqbzob.html

[O02] 使用线程池
来源：http://dali.sxryk.cn/Article/details/gt2fnjklihl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yanxiufei.cn/Article/details/gt2djsustjm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ehwqpu.com/Article/details/gt2pzjesetg.html

JS:   // worker_threads 线程池
来源：http://dali.wangdashe.top/Article/details/gt2lbnktvgf.html

TS:   // worker_threads 线程池
来源：http://dali.daxiang520.top/Article/details/gt2jpikmpdj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.daria6918.cn/Article/details/gt2bzhilybw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yuxming.cn/Article/details/gt2zkpffyki.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.aizwys.cn/Article/details/gt2nihqaigf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.guannengcc.top/Article/details/gt2hsskelbm.html

[O03] 加锁保护共享数据
来源：http://dali.gzhubu.top/Article/details/gt2cmscqhhr.html

Py:   with lock: shared += 1
来源：http://dali.xylfe.cn/Article/details/gt2rabqhdkc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hnrzxoei.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.pengpengdd.cyou/Article/details/gt2vxbexfek.html

TS:   // 同 JS
来源：http://dali.hnxiangtu.top/Article/details/gt2irxjvjfb.html

Java: synchronized (this) { shared++; }
来源：http://dali.gogol.net.cn/Article/details/gt2ajijzwyw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ybcxt.top/Article/details/gt2nvgcjkyb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.svipenyu.cn/Article/details/gt2mhrnssxl.html

C#:   lock (gate) { shared++; }
来源：http://dali.9152youxi.cn/Article/details/gt2yglecfhy.html

[O04] 定义异步函数并等待
来源：http://dali.aizwys.cn/Article/details/gt2sobcipvv.html

Py:   async def f():⏎    await g()
来源：http://dali.316326.xyz/Article/details/gt2zsnupnzj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gogol.net.cn/Article/details/gt2pkbepozy.html

JS:   async function f() { await g(); }
来源：http://dali.yj20258.top/Article/details/gt2lozxmaob.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.dianchejie.cn/Article/details/gt2wratidxw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.vqdsnc.cn/Article/details/gt2qcnpulxj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hysaishi.cn/Article/details/gt2eljpzxin.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.kuanghao11.cn/Article/details/gt2ppyoayiy.html

C#:   async Task F() { await G(); }
来源：http://dali.xylfe.cn/Article/details/gt2xqormnir.html

[O05] 并发执行并等待全部完成
来源：http://dali.kuanghao11.cn/Article/details/gt2lugifpkv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.redwolf501.top/Article/details/gt2eehtmvbq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xuanzx.com/Article/details/gt2abuawckd.html

JS:   await Promise.all(tasks)
来源：http://dali.yangfankeji.com/Article/details/gt2radtsiae.html

TS:   await Promise.all(tasks)
来源：http://dali.gaohongyu789.top/Article/details/gt2sdfvklit.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ppjwa.cn/Article/details/gt2znlxodnv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ybcxt.top/Article/details/gt2xtwnmvsx.html

Ruby: threads.map(&:join)
来源：http://dali.birdmap.top/Article/details/gt2lessnsdc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.quarkkingdee.top/Article/details/gt2kpzewada.html

[O06] 使用进程池
来源：http://dali.9152youxi.cn/Article/details/gt2qweayyik.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.9152youxi.cn/Article/details/gt2ibkllrzo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.guowangkeji.top/Article/details/gt2gvyibzvc.html

JS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fayvkbvv.html

TS:   // child_process / cluster 模块
来源：http://dali.jinghuilouyu.cn/Article/details/gt2brlxwrwx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj20258.top/Article/details/gt2ddcbzqwm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yuxming.cn/Article/details/gt2efhwwxto.html

Ruby: // fork 块
来源：http://dali.ehwqpu.com/Article/details/gt2vwrocguo.html

C#:   Parallel.For
来源：http://dali.cqqwz.cn/Article/details/gt2zclyqiqc.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2meazhjkr.html

P. 常用工具函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2wigxljgq.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zlmjscgz.html

[P01] 生成 UUID
来源：http://dali.ivvv.top/Article/details/gt2zittojwo.html

Py:   str(uuid.uuid4())
来源：http://dali.haohaochexian.top/Article/details/gt2lemlitxc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.kuanghao11.cn/Article/details/gt2vrwrzhse.html

JS:   crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gt2hcqzheqb.html

TS:   crypto.randomUUID()
来源：http://dali.daria6918.cn/Article/details/gt2omlqpkyj.html

Java: UUID.randomUUID().toString()
来源：http://dali.iojbl.cn/Article/details/gt2rucilagq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.quarkkingdee.top/Article/details/gt2rbmvdbnq.html

Ruby: SecureRandom.uuid
来源：http://dali.hfpthk.cn/Article/details/gt2nvyjuyox.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.meibo888.top/Article/details/gt2tgbapiqa.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shzxlz.cn/Article/details/gt2bwkneqmd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2spfrohgt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2khjvozsv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.tanke756.top/Article/details/gt2nrqjnzcn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yuanzhike.top/Article/details/gt2bijlwgly.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.daria6918.cn/Article/details/gt2bzatnxrz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.pengpengdd.cyou/Article/details/gt2lceutibd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.fengsongda.top/Article/details/gt2dhrkpkme.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqmlkhy.html

[P03] 生成短随机字符串
来源：http://dali.9152youxi.cn/Article/details/gt2lysmikmr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cqqwz.cn/Article/details/gt2jrxrkpzq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gzhubu.top/Article/details/gt2fheurhre.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cdnleiting.top/Article/details/gt2vhvkbett.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gt2tcpqdego.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jqgfzy.top/Article/details/gt2rdzlpmyo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.guowangkeji.top/Article/details/gt2hylibbzb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.snrcjt.cn/Article/details/gt2intweted.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.316326.xyz/Article/details/gt2lchleett.html

[P04] 求长度
来源：http://dali.yonumen.top/Article/details/gt2lljejvtc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.wangdashe.top/Article/details/gt2bctwdubv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gt2cptnjass.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yvedp.cn/Article/details/gt2tavjsdor.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj202588.top/Article/details/gt2rubcjqnv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhongyouzk.top/Article/details/gt2ooqbuztm.html

Go:   len(arr);  len(m)
来源：http://dali.xuanzx.com/Article/details/gt2shicgiry.html

Ruby: x.length;  x.size
来源：http://dali.chenjidiqi.icu/Article/details/gt2lqpqinxx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jtvamnzw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dianchejie.cn/Article/details/gt2tdtimcrm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zdqjudy.top/Article/details/gt2qcobmxih.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenlongwang.top/Article/details/gt2duspgmkp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tanke756.top/Article/details/gt2nijlznrm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yuxming.cn/Article/details/gt2deecivmz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cqqwz.cn/Article/details/gt2negylapm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.aizwys.cn/Article/details/gt2tcgiphip.html

Ruby: a == b
来源：http://dali.xylfe.cn/Article/details/gt2kejgzbnt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cheryme.top/Article/details/gt2kuupxxoh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.tianlin.xyz/Article/details/gt2zraptrvc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yvedp.cn/Article/details/gt2uffhcqlq.html

PHP:  if (empty($x)) {}
来源：http://dali.yueranfly.top/Article/details/gt2timebsbf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jiagoushi.top/Article/details/gt2jhzzfzsn.html

TS:   if (x == null) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2aeojtqts.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gt2xrmpidln.html

Go:   if x == nil {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lyvtfnxd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jqgufenzy.top/Article/details/gt2ebygoofk.html

C#:   if (x is null) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2thxcqgna.html

[P07] 防抖与节流
来源：http://dali.svipenyu.cn/Article/details/gt2ijujufek.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.0kj1m.cn/Article/details/gt2mpvtqlyx.html

PHP:  // 手写时间戳比较
来源：http://dali.guannengcc.top/Article/details/gt2qefopmnu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nwbrower.top/Article/details/gt2hqtxvygb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gt2mctncmzu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2yhzwqkjt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ivvv.top/Article/details/gt2nlwqrbdx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.snrcjt.cn/Article/details/gt2ikcetcgy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj20258888.top/Article/details/gt2keavngoe.html

[P08] 处理浮点精度问题
来源：http://dali.hammf.cn/Article/details/gt2mjrluygt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jqgufenzy.top/Article/details/gt2imcfyzun.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.iojbl.cn/Article/details/gt2pjxqzxff.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wthfaojo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.fzhhl.top/Article/details/gt2zezaasps.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2xhywlgop.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shangyingyoupin.top/Article/details/gt2qtrqxsmk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.snrcjt.cn/Article/details/gt2tiayqpdt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.snrcjt.cn/Article/details/gt2ntsalshf.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2egaexhcv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shzxlz.cn/Article/details/gt2hnoidnnn.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2yhplxwxm.html

[Q01] 创建表
来源：http://dali.svipenyu.cn/Article/details/gt2hcbbsxhy.html

CREATE TABLE users (
来源：http://dali.ybcxt.top/Article/details/gt2rbxlcalp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daria6918.cn/Article/details/gt2qiliurjg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pwnuxrdd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jyoumei.cn/Article/details/gt2cowjkkby.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.pycfn.com/Article/details/gt2lfwvexuw.html

);
来源：http://dali.ivvv.top/Article/details/gt2xtlyfjzz.html

[Q02] 创建带外键的表
来源：http://dali.pycfn.com/Article/details/gt2ruqcadng.html

CREATE TABLE orders (
来源：http://dali.dianchejie.cn/Article/details/gt2wegerlnz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fengsongda.top/Article/details/gt2ezoylvyx.html

user_id INT NOT NULL,
来源：http://dali.yueranfly.top/Article/details/gt2svigrztj.html

amount DECIMAL(10, 2),
来源：http://dali.gotoacloud.top/Article/details/gt2jmthtlka.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gaohongyu789.top/Article/details/gt2dovchquh.html

);
来源：http://dali.9152youxi.cn/Article/details/gt2gizntzqf.html

[Q03] 增加列
来源：http://dali.snrcjt.cn/Article/details/gt2rmkefrfs.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhiwuduotai.top/Article/details/gt2tgjovfmj.html

[Q04] 修改列类型
来源：http://dali.jiagoushi.top/Article/details/gt2lcwgxkva.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xylfe.cn/Article/details/gt2imhzppvv.html

[Q05] 重命名列
来源：http://dali.shangyingyoupin.top/Article/details/gt2gnffxkle.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhixingplan.top/Article/details/gt2mydvxwqg.html

[Q06] 删除列
来源：http://dali.zhongyouzk.top/Article/details/gt2yshubwqn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yvedp.cn/Article/details/gt2ugmhiykr.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2uoabehfd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zdqjudy.top/Article/details/gt2wcugfgcf.html

[Q08] 创建普通索引
来源：http://dali.zhixingplan.top/Article/details/gt2uvpeabjg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xylfe.cn/Article/details/gt2wytheylo.html

[Q09] 创建唯一索引
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kjnlyaeo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jianghu66.top/Article/details/gt2xffzvtsp.html

[Q10] 插入单行
来源：http://dali.tanke756.top/Article/details/gt2qlqbrujn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.havefunace.top/Article/details/gt2vfzrtxjz.html

[Q11] 一次插入多行
来源：http://dali.jyoumei.cn/Article/details/gt2qphqclsb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shzxlz.cn/Article/details/gt2dtkbfdmn.html

[Q12] 插入后取自增 ID
来源：http://dali.daxiang520.top/Article/details/gt2xifhpwws.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.smart0.xyz/Article/details/gt2rgksghac.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.snrcjt.cn/Article/details/gt2cdnqdsry.html

[Q13] 忽略重复插入
来源：http://dali.svipenyu.cn/Article/details/gt2cjxqbgts.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.fzhhl.top/Article/details/gt2ovtqvstx.html

[Q14] 存在则更新（upsert）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wtchfxfz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2brehrzus.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhengqikj.top/Article/details/gt2jhumsmsn.html

[Q15] 查询全部
来源：http://dali.aibaodan.cn/Article/details/gt2dtmrxwpu.html

SELECT * FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2fycinhoi.html

[Q16] 查询指定列
来源：http://dali.quarkkingdee.top/Article/details/gt2hndxnuyw.html

SELECT id, name FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tgkmsbir.html

[Q17] 条件查询
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mxgctvdi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.nanxinkj.top/Article/details/gt2axobasfe.html

[Q18] 模糊匹配
来源：http://dali.jinqigufen.top/Article/details/gt2lmyfwljd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hammf.cn/Article/details/gt2ewhupyuz.html

[Q19] 范围查询
来源：http://dali.quarkkingdee.top/Article/details/gt2njngvhfv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mvyknvkx.html

[Q20] IN 列表
来源：http://dali.zhiwuduotai.top/Article/details/gt2zdapkqhp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenzaomai.com/Article/details/gt2tangwihn.html

[Q21] 空值判断
来源：http://dali.hnqzz.top/Article/details/gt2gsgvycwi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yangfankeji.com/Article/details/gt2lxvfaslh.html

[Q22] 排序
来源：http://dali.birdmap.top/Article/details/gt2tjmdmkhv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.tianlin.xyz/Article/details/gt2zriqfwxe.html

[Q23] 分页
来源：http://dali.gaohongyu789.top/Article/details/gt2fizwisih.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.aizwys.cn/Article/details/gt2icgpquvv.html

[Q24] 去重
来源：http://dali.jinqigfzy.top/Article/details/gt2zvjzocnz.html

SELECT DISTINCT city FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2ouyiewwl.html

[Q25] 只取前 N 条
来源：http://dali.guowangkeji.top/Article/details/gt2zkxqwian.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ydzc1.top/Article/details/gt2cimypqoi.html

[Q26] 计数
来源：http://dali.hfpthk.cn/Article/details/gt2njxqmyft.html

SELECT COUNT(*) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2barrwyoe.html

[Q27] 条件计数
来源：http://dali.yuanzhike.top/Article/details/gt2klwmnwsb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2xnlmfqgp.html

[Q28] 求和与平均
来源：http://dali.ydzc1.top/Article/details/gt2cnuhrxrt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gt2hcljphay.html

[Q29] 最大最小值
来源：http://dali.snrcjt.cn/Article/details/gt2lxjplvii.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2yocaknip.html

[Q30] 分组统计
来源：http://dali.dianchejie.cn/Article/details/gt2ssuremvt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ybcxt.top/Article/details/gt2hwgziimr.html

[Q31] 分组后过滤
来源：http://dali.yj20258888.top/Article/details/gt2gyejizfx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hnxiangtu.top/Article/details/gt2jgwqczyr.html

[Q32] 分组拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gt2canridng.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gt2fdkoofku.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ovxnpryj.html

[Q33] 多列分组
来源：http://dali.wangdashe.top/Article/details/gt2ovmhswkl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.fzhhl.top/Article/details/gt2eusasvba.html

[Q34] 每组取第一条
来源：http://dali.gogol.net.cn/Article/details/gt2qzrzvucc.html

SELECT * FROM (
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mgeayxzf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cdnleiting.top/Article/details/gt2amwnkool.html

) t WHERE rn = 1;
来源：http://dali.iojbl.cn/Article/details/gt2bjiytuyi.html

[Q35] 内连接
来源：http://dali.aizwys.cn/Article/details/gt2pemurphi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ppjwa.cn/Article/details/gt2bubvlxmw.html

[Q36] 左连接
来源：http://dali.iojbl.cn/Article/details/gt2mlucllvq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.guowangkeji.top/Article/details/gt2ptmvieuh.html

[Q37] 右连接
来源：http://dali.jqgufenzy.top/Article/details/gt2kryabyhy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xziqi.cn/Article/details/gt2ftnudgef.html


<!-- 参考信息 -->