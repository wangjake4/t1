代发 wailian999

[N05] 最大公约数
来源：http://dali.jinghuilouyu.cn/Article/details/gtaneytemw.html

Py:   math.gcd(a, b)
来源：http://dali.guowangkeji.top/Article/details/gtrsxvdzrh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.0kj1m.cn/Article/details/gtjgvktbvx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gzhubu.top/Article/details/gtqlequrnt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gtonmqaxjc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sufxvd.cn/Article/details/gtwclkgjzo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.c1oappe.top/Article/details/gtjyhpgexe.html

Ruby: a.gcd(b)
来源：http://dali.sweek.top/Article/details/gtipkdbeuy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yvedp.cn/Article/details/gtbzlovsfj.html

[N06] 判断回文字符串
来源：http://dali.gzhubu.top/Article/details/gtjzkfoyao.html

Py:   s == s[::-1]
来源：http://dali.gaohongyu789.top/Article/details/gtzfhtppqi.html

PHP:  $s === strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gtpkbkphsn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtcirkkhag.html

TS:   s === [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtxrwubmre.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.smart0.xyz/Article/details/gtntjtrldm.html

Go:   // 双指针从两端比较
来源：http://dali.snrcjt.cn/Article/details/gtkpsisewy.html

Ruby: s == s.reverse
来源：http://dali.sxryk.cn/Article/details/gtgtxiylgb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hammf.cn/Article/details/gtmuseydrz.html

[N07] 两数之和（返回下标）
来源：http://dali.birdmap.top/Article/details/gtqvqeawmm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.dashuyun.cn/Article/details/gtzxfoepxv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xinyue.icu/Article/details/gttbreyvdt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenlongwang.top/Article/details/gtypwipvxk.html

TS:   // 手写 Map<string, number>
来源：http://dali.xylfe.cn/Article/details/gtbjnxadup.html

Java: // 手写 HashMap
来源：http://dali.aibaodan.cn/Article/details/gtqrfuebfe.html

Go:   // 手写 map[int]int
来源：http://dali.jinghuilouyu.cn/Article/details/gtwnyzzuxl.html

Ruby: // 手写 Hash
来源：http://dali.jinqigufen.top/Article/details/gtqhnztddi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.snrcjt.cn/Article/details/gtqovhguog.html

[N08] 生成全排列
来源：http://dali.meibo888.top/Article/details/gttreeipos.html

Py:   itertools.permutations(arr)
来源：http://dali.meibo888.top/Article/details/gtpouhshgd.html

PHP:  // 手写递归交换
来源：http://dali.gotoacloud.top/Article/details/gttmzxrurd.html

JS:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtshaofwsv.html

TS:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtadvnjkkc.html

Java: // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtidnofbvj.html

Go:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtpzizulil.html

Ruby: arr.permutation.to_a
来源：http://dali.ivvv.top/Article/details/gtauqebubr.html

C#:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtwvbilnbl.html

[N09] 栈与队列
来源：http://dali.hfpthk.cn/Article/details/gtjqrydayp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gzhubu.top/Article/details/gthusmfbtg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cheryme.top/Article/details/gtrueqselu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gtugduvlhy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.aibaodan.cn/Article/details/gtidgvpsay.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jianghu66.top/Article/details/gtxwjptutk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hysaishi.cn/Article/details/gtgklynqzl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.fzhhl.top/Article/details/gtvlwtmoic.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shuidangran.top/Article/details/gtblnmguaq.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gtnejczomx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgxyoekfb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.iojbl.cn/Article/details/gtwbvzbcae.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xinyue.icu/Article/details/gtiyezzzgk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sxryk.cn/Article/details/gtwapksqzs.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258888.top/Article/details/gtdtzpedfx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.guowangkeji.top/Article/details/gtcpjebojo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenzaomai.com/Article/details/gtzihwlrma.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xziqi.cn/Article/details/gtnngonlhg.html

[N11] 二叉树中序遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrrxcjhm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.birdmap.top/Article/details/gtmzeuthtw.html

PHP:  // 手写递归函数
来源：http://dali.sufxvd.cn/Article/details/gtrttkbfyv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuanzhike.top/Article/details/gtuyotilcz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tianlin.xyz/Article/details/gtldbgjjci.html

Java: // 手写递归
来源：http://dali.cheryme.top/Article/details/gtzioqiipv.html

Go:   // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gtklkomywn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yonumen.top/Article/details/gteweptrox.html

C#:   // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gtibwnokgd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yonumen.top/Article/details/gtgcelrhqn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yongpay.top/Article/details/gtmqqrqwdj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cdnleiting.top/Article/details/gtupykdhbr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pycfn.com/Article/details/gtwthsgsxj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cashguo.top/Article/details/gtvwpewtek.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigfzy.top/Article/details/gtunqjorbt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xuanzx.com/Article/details/gtjfccefgk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.meibo888.top/Article/details/gtgpbqjjol.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xinyue.icu/Article/details/gtecnnigpj.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtrmcxmpjy.html

O. 并发与异步
来源：http://dali.xuanzx.com/Article/details/gthmzpmerf.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtirnjofmj.html

[O01] 启动一个线程
来源：http://dali.sxryk.cn/Article/details/gtiuvmuubj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.pengpengdd.cyou/Article/details/gtkjjwcpnt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jqgufenzy.top/Article/details/gtapkbikbu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xuanzx.com/Article/details/gtbwmanpin.html

TS:   // 同 JS
来源：http://dali.jyoumei.cn/Article/details/gtgkowmxxm.html

Java: new Thread(() -> f()).start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgapnrnmd.html

Go:   go f()
来源：http://dali.pengpengdd.cyou/Article/details/gtjspagcdt.html

Ruby: Thread.new { f }
来源：http://dali.andypj.xyz/Article/details/gtypgivych.html

C#:   Task.Run(() => F());
来源：http://dali.jianghu66.top/Article/details/gtyhlgyzqn.html

[O02] 使用线程池
来源：http://dali.yongpay.top/Article/details/gtcjiylmcv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.feifeiyinyue.top/Article/details/gtbzuhiiwq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwgynltf.html

JS:   // worker_threads 线程池
来源：http://dali.yj202588.top/Article/details/gtluhofthw.html

TS:   // worker_threads 线程池
来源：http://dali.xylfe.cn/Article/details/gtzlaqdeds.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.havefunace.top/Article/details/gtrhrffpdv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xuanzx.com/Article/details/gtnjmgrmsx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yonumen.top/Article/details/gtyfswrvze.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.quarkkingdee.top/Article/details/gtkzswhbin.html

[O03] 加锁保护共享数据
来源：http://dali.zhengqikj.top/Article/details/gtejoyhnig.html

Py:   with lock: shared += 1
来源：http://dali.havefunace.top/Article/details/gtyjxwhwca.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gotoacloud.top/Article/details/gtytlcmdfb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenzaomai.com/Article/details/gtqfkrucif.html

TS:   // 同 JS
来源：http://dali.gaohongyu789.top/Article/details/gtqpskrveq.html

Java: synchronized (this) { shared++; }
来源：http://dali.yueranfly.top/Article/details/gtntvktitf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xuetiantiany.cn/Article/details/gtnjuvrsqw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.316326.xyz/Article/details/gtxtjqiefq.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gttyzqrkmk.html

[O04] 定义异步函数并等待
来源：http://dali.svipenyu.cn/Article/details/gtplleefqj.html

Py:   async def f():⏎    await g()
来源：http://dali.jlsjyb.cn/Article/details/gtijxbpxjy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hysaishi.cn/Article/details/gtowycdsna.html

JS:   async function f() { await g(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtiyzspdyx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmcctlpn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj202588.top/Article/details/gtrmrvnkbn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj202588.top/Article/details/gtmrpmfzxt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hongshengwenyu.top/Article/details/gtodnczmhg.html

C#:   async Task F() { await G(); }
来源：http://dali.0kj1m.cn/Article/details/gtzzqruyey.html

[O05] 并发执行并等待全部完成
来源：http://dali.svipenyu.cn/Article/details/gtfoybppwo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.redwolf501.top/Article/details/gtvghrrkbo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhixingplan.top/Article/details/gttfijkpxi.html

JS:   await Promise.all(tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gthnbojzfb.html

TS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gtsotwmsbi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinqigufen.top/Article/details/gtqeblbatd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.andypj.xyz/Article/details/gtcvfrncbn.html

Ruby: threads.map(&:join)
来源：http://dali.ehwqpu.com/Article/details/gtnadjoqfs.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jiagoushi.top/Article/details/gtgcvdebyp.html

[O06] 使用进程池
来源：http://dali.yueranfly.top/Article/details/gtschzhnre.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxsihelrb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinqigufen.top/Article/details/gtxuzkcffu.html

JS:   // child_process / cluster 模块
来源：http://dali.ivvv.top/Article/details/gtzzkxeynu.html

TS:   // child_process / cluster 模块
来源：http://dali.nwbrower.top/Article/details/gtylluzfdv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ydzc1.top/Article/details/gtvvozhmif.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tian-w.cn/Article/details/gtklemuvoe.html

Ruby: // fork 块
来源：http://dali.0kj1m.cn/Article/details/gtftihppbj.html

C#:   Parallel.For
来源：http://dali.yuanzhike.top/Article/details/gtxjxbuemy.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtevrjsidq.html

P. 常用工具函数
来源：http://dali.vqdsnc.cn/Article/details/gtcddojeks.html

================================================================================
来源：http://dali.sweek.top/Article/details/gteaizeggz.html

[P01] 生成 UUID
来源：http://dali.zhongyouzk.top/Article/details/gtbcxwjhvz.html

Py:   str(uuid.uuid4())
来源：http://dali.zhongyouzk.top/Article/details/gtogzynjjg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.iojbl.cn/Article/details/gtuunuqihs.html

JS:   crypto.randomUUID()
来源：http://dali.cashguo.top/Article/details/gtivtjuuzh.html

TS:   crypto.randomUUID()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthinlskxj.html

Java: UUID.randomUUID().toString()
来源：http://dali.gogol.net.cn/Article/details/gtoqyyrhjs.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sufxvd.cn/Article/details/gtxhrkvucd.html

Ruby: SecureRandom.uuid
来源：http://dali.jqgfzy.top/Article/details/gtcrreavtb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xziqi.cn/Article/details/gtklgsuhwq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yuxming.cn/Article/details/gtbzgblubd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tianlin.xyz/Article/details/gtgneadpjc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gaohongyu789.top/Article/details/gtwilwotci.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.birdmap.top/Article/details/gtjuyywfuc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cheryme.top/Article/details/gtkfemvzpi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ydzc1.top/Article/details/gtmjfsdeqc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhongyouzk.top/Article/details/gtzxzbtwxl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnwfqvyf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aizwys.cn/Article/details/gtlyuzgxwg.html

[P03] 生成短随机字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtsyknfbgm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sysykeji.top/Article/details/gtrwybhkrk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgphnrori.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ybcxt.top/Article/details/gtoyucepqf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sxryk.cn/Article/details/gtotnvcfca.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.pycfn.com/Article/details/gtnvzzokwu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdqebkhcx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cqqwz.cn/Article/details/gtvafvkcia.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gaohongyu789.top/Article/details/gtunghumnz.html

[P04] 求长度
来源：http://dali.havefunace.top/Article/details/gtbsqfclav.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gzhubu.top/Article/details/gtnasbvfjr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gthuibtrpb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ybcxt.top/Article/details/gtuyumftng.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhoulong.xyz/Article/details/gtzlaiyten.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hysaishi.cn/Article/details/gtpwfqftmj.html

Go:   len(arr);  len(m)
来源：http://dali.jinqigfzy.top/Article/details/gttgelnybd.html

Ruby: x.length;  x.size
来源：http://dali.yanxiufei.cn/Article/details/gtzesptvcj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cdnleiting.top/Article/details/gtxfamqyyr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ppjwa.cn/Article/details/gtviouienx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.smart0.xyz/Article/details/gtsxuelebt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sysykeji.top/Article/details/gtphpspddh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.birdmap.top/Article/details/gtaolfluxh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pengpengdd.cyou/Article/details/gtcnniagny.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zycfv.cn/Article/details/gtylifbbwg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.wangdashe.top/Article/details/gtifcwnzbv.html

Ruby: a == b
来源：http://dali.nanxuanxn.top/Article/details/gtsbvbxqiv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinqigfzy.top/Article/details/gtkcmirxcw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yangfankeji.com/Article/details/gtaxzfstxv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.fengsongda.top/Article/details/gtizgkmztq.html

PHP:  if (empty($x)) {}
来源：http://dali.shangyingyoupin.top/Article/details/gttagnbunz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yanxiufei.cn/Article/details/gtmboeuqyb.html

TS:   if (x == null) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtlcmabpyk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.svipenyu.cn/Article/details/gtekcrxvhp.html

Go:   if x == nil {}
来源：http://dali.yvedp.cn/Article/details/gtxovmncud.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.svipenyu.cn/Article/details/gtneeqoubt.html

C#:   if (x is null) {}
来源：http://dali.yanxiufei.cn/Article/details/gtbkajyxin.html

[P07] 防抖与节流
来源：http://dali.shanyushiyangtech.top/Article/details/gtuyalvteg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nanxinkj.top/Article/details/gtjwvwzqye.html

PHP:  // 手写时间戳比较
来源：http://dali.zhengqikj.top/Article/details/gtlibtblzj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gtoyuamtao.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuanzx.com/Article/details/gtyuytxblo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hysaishi.cn/Article/details/gtxtrebwdv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jlsjyb.cn/Article/details/gtdskimyxe.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gteqwjchxj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.iojbl.cn/Article/details/gtwxyskfna.html

[P08] 处理浮点精度问题
来源：http://dali.tanke756.top/Article/details/gtiyojswxd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.dashuyun.cn/Article/details/gtuokogndf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hnxiangtu.top/Article/details/gtxxxwvfod.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghvmamku.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cheryme.top/Article/details/gttgqciodp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jqgufenzy.top/Article/details/gtpqtrwnut.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tanke756.top/Article/details/gtewglqemu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj202588.top/Article/details/gtrrlsagrk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzimgtzsl.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtewoorzmf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shuidangran.top/Article/details/gtcvjsbaru.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtrxmpemau.html

[Q01] 创建表
来源：http://dali.yuxming.cn/Article/details/gtmljksknc.html

CREATE TABLE users (
来源：http://dali.jlsjyb.cn/Article/details/gtyfmoxsrg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hongshengwenyu.top/Article/details/gtlxclmpwl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.c1oappe.top/Article/details/gthsvazydo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhengqikj.top/Article/details/gteqnsrbjy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.redwolf501.top/Article/details/gtgtmoszxb.html

);
来源：http://dali.xziqi.cn/Article/details/gtdaqtxeyk.html

[Q02] 创建带外键的表
来源：http://dali.0kj1m.cn/Article/details/gtswrrpzob.html

CREATE TABLE orders (
来源：http://dali.zhengqikj.top/Article/details/gtjzezdata.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ppjwa.cn/Article/details/gtmsznpjnc.html

user_id INT NOT NULL,
来源：http://dali.jyoumei.cn/Article/details/gtmevqofcc.html

amount DECIMAL(10, 2),
来源：http://dali.yj20258888.top/Article/details/gtaucanodb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sysykeji.top/Article/details/gtyhaifgme.html

);
来源：http://dali.zhongyouzk.top/Article/details/gtcxfxkgov.html

[Q03] 增加列
来源：http://dali.hongshengwenyu.top/Article/details/gtdjoqjcyq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yuanzhike.top/Article/details/gtkkqlaqvn.html

[Q04] 修改列类型
来源：http://dali.guowangkeji.top/Article/details/gtrzyerwbh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yuxming.cn/Article/details/gtiqqeltkf.html

[Q05] 重命名列
来源：http://dali.quarkkingdee.top/Article/details/gtkbxpsxzf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrhvppcde.html

[Q06] 删除列
来源：http://dali.hongshengwenyu.top/Article/details/gtswcpyvla.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.haohaochexian.top/Article/details/gtrddxdapm.html

[Q07] 删除表
来源：http://dali.yangfankeji.com/Article/details/gthbkntzbf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.guannengcc.top/Article/details/gtkgnjcfhr.html

[Q08] 创建普通索引
来源：http://dali.zycfv.cn/Article/details/gtboytigws.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hnqzz.top/Article/details/gtkguaorgb.html

[Q09] 创建唯一索引
来源：http://dali.tanke756.top/Article/details/gtezywbapn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zycfv.cn/Article/details/gttymyyogp.html

[Q10] 插入单行
来源：http://dali.svipenyu.cn/Article/details/gtaypykmvd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.smart0.xyz/Article/details/gtycimixea.html

[Q11] 一次插入多行
来源：http://dali.hysaishi.cn/Article/details/gtlrrihsgb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.meibo888.top/Article/details/gtvripvmgp.html

[Q12] 插入后取自增 ID
来源：http://dali.xuanzx.com/Article/details/gtzayjelin.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gaohongyu789.top/Article/details/gtnbedxcof.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.9152youxi.cn/Article/details/gtainuyoar.html

[Q13] 忽略重复插入
来源：http://dali.hnxiangtu.top/Article/details/gtjrqzgofm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sysykeji.top/Article/details/gtwdojcfao.html

[Q14] 存在则更新（upsert）
来源：http://dali.cashguo.top/Article/details/gtxfjpxdas.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zycfv.cn/Article/details/gtyzuyylou.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvyogcher.html

[Q15] 查询全部
来源：http://dali.hysaishi.cn/Article/details/gthydvqbir.html

SELECT * FROM users;
来源：http://dali.fzhhl.top/Article/details/gtnbdxxafm.html

[Q16] 查询指定列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqvafcysh.html

SELECT id, name FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtccuwtowl.html

[Q17] 条件查询
来源：http://dali.hywenlv.cn/Article/details/gtcydgtycz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hnqzz.top/Article/details/gtdovmspbu.html

[Q18] 模糊匹配
来源：http://dali.ppjwa.cn/Article/details/gtmdgkngay.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ehwqpu.com/Article/details/gtzheiybdw.html

[Q19] 范围查询
来源：http://dali.c1oappe.top/Article/details/gtwnffkwfh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.316326.xyz/Article/details/gtwylysenb.html

[Q20] IN 列表
来源：http://dali.gogol.net.cn/Article/details/gtwdrdjwhd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.dashuyun.cn/Article/details/gthozntpnj.html

[Q21] 空值判断
来源：http://dali.sxryk.cn/Article/details/gtonyozwus.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tanke756.top/Article/details/gtuiqlvcfr.html

[Q22] 排序
来源：http://dali.chenjidiqi.icu/Article/details/gtumyzaenr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hammf.cn/Article/details/gtaosxaxqn.html

[Q23] 分页
来源：http://dali.yj20258.top/Article/details/gtutevskyo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ehwqpu.com/Article/details/gtyjqgpnuk.html

[Q24] 去重
来源：http://dali.jyoumei.cn/Article/details/gttkljdgld.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenlongwang.top/Article/details/gthiktzssp.html

[Q25] 只取前 N 条
来源：http://dali.jinqigfzy.top/Article/details/gtdhrsgtit.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ppjwa.cn/Article/details/gtfcfcbbor.html

[Q26] 计数
来源：http://dali.sweek.top/Article/details/gtdvegqozl.html

SELECT COUNT(*) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtqsqeaqub.html

[Q27] 条件计数
来源：http://dali.cheryme.top/Article/details/gtmgcqzkxt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtlduhnbqw.html

[Q28] 求和与平均
来源：http://dali.jlsjyb.cn/Article/details/gtoiqpiktp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtwueuaygu.html

[Q29] 最大最小值
来源：http://dali.jqgufenzy.top/Article/details/gtsiqjrlso.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtwrxwswtq.html

[Q30] 分组统计
来源：http://dali.hywenlv.cn/Article/details/gtmofwwich.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gtqahdpkzl.html

[Q31] 分组后过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtwnlwpfjt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.daxiang520.top/Article/details/gthovgjepp.html

[Q32] 分组拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gtsatcyodj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gttqvksvcr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yuanzhike.top/Article/details/gthdtvrpkt.html

[Q33] 多列分组
来源：http://dali.cdnleiting.top/Article/details/gtbhxezche.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yanxiufei.cn/Article/details/gtapbjqiez.html

[Q34] 每组取第一条
来源：http://dali.hnxiangtu.top/Article/details/gtkmlzxdwe.html

SELECT * FROM (
来源：http://dali.shzxlz.cn/Article/details/gtaathfult.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nanxinkj.top/Article/details/gtysehkkkf.html

) t WHERE rn = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtjegcrtjp.html

[Q35] 内连接
来源：http://dali.fzhhl.top/Article/details/gtsqnbcwfx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yonumen.top/Article/details/gtoumecvpm.html

[Q36] 左连接
来源：http://dali.shangyingyoupin.top/Article/details/gtgjojcvdi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xziqi.cn/Article/details/gtwywxtmts.html

[Q37] 右连接
来源：http://dali.svipenyu.cn/Article/details/gtezxmzoek.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.fengsongda.top/Article/details/gtignrdhsa.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzpgwpuub.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cucudq.cn/Article/details/gtmgkwsxxx.html

[Q39] 自连接（查上下级）
来源：http://dali.shuidangran.top/Article/details/gtryzsitkb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.redwolf501.top/Article/details/gtjzasdwoh.html


<!-- 参考信息 -->