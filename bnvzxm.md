代发 wailian999

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjxypyzxq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.quarkkingdee.top/Article/details/gtgeywdund.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gtikwjpaiy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gtsptoxwrw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinqigufen.top/Article/details/gtzntxebbq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xuanzx.com/Article/details/gtwekadsub.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jiagoushi.top/Article/details/gtjkasnihb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gtmwonkqle.html

[N05] 最大公约数
来源：http://dali.wangdashe.top/Article/details/gtdldufarg.html

Py:   math.gcd(a, b)
来源：http://dali.yvedp.cn/Article/details/gtrdnkknrt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xziqi.cn/Article/details/gtzvqswmxr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.bjfxy.top/Article/details/gtbdjfnmis.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.mhx1999.top/Article/details/gtadeabvwo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.andypj.xyz/Article/details/gtznfedrqj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.0kj1m.cn/Article/details/gtfzkpvnsq.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gtbbjyjasl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yongpay.top/Article/details/gtkbdmsttu.html

[N06] 判断回文字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtiudqilhf.html

Py:   s == s[::-1]
来源：http://dali.hywenlv.cn/Article/details/gttrazaqhj.html

PHP:  $s === strrev($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtkvmsczpw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gthigbaisd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtcoqjhbul.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.andypj.xyz/Article/details/gtsolldvdm.html

Go:   // 双指针从两端比较
来源：http://dali.quarkkingdee.top/Article/details/gtsgyeqjns.html

Ruby: s == s.reverse
来源：http://dali.316326.xyz/Article/details/gtzqgwqotk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yuxming.cn/Article/details/gtjlhqauhq.html

[N07] 两数之和（返回下标）
来源：http://dali.shzxlz.cn/Article/details/gtpaqamswe.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hywenlv.cn/Article/details/gturgnpjub.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shuidangran.top/Article/details/gthzaoraqm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.c1oappe.top/Article/details/gttevouftj.html

TS:   // 手写 Map<string, number>
来源：http://dali.fengsongda.top/Article/details/gtdyfzokcf.html

Java: // 手写 HashMap
来源：http://dali.mhx1999.top/Article/details/gtcsoviuwh.html

Go:   // 手写 map[int]int
来源：http://dali.shangyingyoupin.top/Article/details/gtqmaizyoc.html

Ruby: // 手写 Hash
来源：http://dali.aizwys.cn/Article/details/gtjobvulkb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nanxuanxn.top/Article/details/gtnibjbklz.html

[N08] 生成全排列
来源：http://dali.yj20258.top/Article/details/gtiqezedge.html

Py:   itertools.permutations(arr)
来源：http://dali.daxiang520.top/Article/details/gtndbaoknc.html

PHP:  // 手写递归交换
来源：http://dali.yonumen.top/Article/details/gtossbyhiq.html

JS:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtnonxagav.html

TS:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtztbengnp.html

Java: // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtowznngtv.html

Go:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtvtnneqwf.html

Ruby: arr.permutation.to_a
来源：http://dali.yueranfly.top/Article/details/gtvjnaultx.html

C#:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtgieaodtt.html

[N09] 栈与队列
来源：http://dali.nanxinkj.top/Article/details/gtmeahmcqe.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinqigufen.top/Article/details/gtkvafnepk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gtbysirouv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gtvkhboszs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenlongwang.top/Article/details/gtcxfxiljn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yonumen.top/Article/details/gtrksydsxc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cucudq.cn/Article/details/gtudskyqqe.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yongpay.top/Article/details/gtrftgelrn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj202588.top/Article/details/gtreekxpek.html

[N10] 链表节点定义
来源：http://dali.zhoulong.xyz/Article/details/gtqlugsqrx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hywenlv.cn/Article/details/gttzxzbyiz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuxming.cn/Article/details/gtddbrwxil.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.9152youxi.cn/Article/details/gtjyfzielm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.quarkkingdee.top/Article/details/gtdmkkbttk.html

Java: class Node { int v; Node next; }
来源：http://dali.jqgfzy.top/Article/details/gtxingjofm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shuidangran.top/Article/details/gtlrmikvep.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gaohongyu789.top/Article/details/gtlvekbheh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xylfe.cn/Article/details/gtufrsvtmh.html

[N11] 二叉树中序遍历
来源：http://dali.jyoumei.cn/Article/details/gtqkqkqfsu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yvedp.cn/Article/details/gtaxuxgeds.html

PHP:  // 手写递归函数
来源：http://dali.yanxiufei.cn/Article/details/gtxwlxrwkh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hongshengwenyu.top/Article/details/gtrjuuqxgy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ybcxt.top/Article/details/gtvyjfvncl.html

Java: // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gthwcpqkpq.html

Go:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gtacutwzbn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.andypj.xyz/Article/details/gtxtvsxjxx.html

C#:   // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gtlpxclafw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gogol.net.cn/Article/details/gtxuxwtphi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jqgfzy.top/Article/details/gtsvbbisfc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shangyingyoupin.top/Article/details/gtyqnvynye.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aibaodan.cn/Article/details/gtjfuswppk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yvedp.cn/Article/details/gtctsdtgkz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yonumen.top/Article/details/gtehvjooak.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyyiwalcl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.redwolf501.top/Article/details/gtbbvxdzcn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.iojbl.cn/Article/details/gtyftqngtb.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtfdrxpgxc.html

O. 并发与异步
来源：http://dali.guannengcc.top/Article/details/gtsdhkcwal.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtwwmufgaf.html

[O01] 启动一个线程
来源：http://dali.xuanzx.com/Article/details/gtzccccryj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zdqjudy.top/Article/details/gtxhsrpeon.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hnxiangtu.top/Article/details/gtiehtaxyo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.aibaodan.cn/Article/details/gtgweutzrx.html

TS:   // 同 JS
来源：http://dali.tian-w.cn/Article/details/gtbgfgxtbu.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyucbgcdk.html

Go:   go f()
来源：http://dali.jqgfzy.top/Article/details/gttfeskmtw.html

Ruby: Thread.new { f }
来源：http://dali.jinqigufen.top/Article/details/gtxkzqvawi.html

C#:   Task.Run(() => F());
来源：http://dali.9152youxi.cn/Article/details/gtfxecgwib.html

[O02] 使用线程池
来源：http://dali.zhongyouzk.top/Article/details/gthhgmmhdv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.wangdashe.top/Article/details/gtximedsiy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shzxlz.cn/Article/details/gtluodtmqt.html

JS:   // worker_threads 线程池
来源：http://dali.svipenyu.cn/Article/details/gthldrvryo.html

TS:   // worker_threads 线程池
来源：http://dali.hnqzz.top/Article/details/gtfyehpgho.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.9152youxi.cn/Article/details/gtnqyhyjrv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhongyouzk.top/Article/details/gttucixtxt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.pycfn.com/Article/details/gtyfclxnkk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ivvv.top/Article/details/gtdupcjwej.html

[O03] 加锁保护共享数据
来源：http://dali.jinghuilouyu.cn/Article/details/gtrmnhymel.html

Py:   with lock: shared += 1
来源：http://dali.tianlin.xyz/Article/details/gtgfdlebcq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yonumen.top/Article/details/gtkkjgpxkz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sufxvd.cn/Article/details/gtzagbkljs.html

TS:   // 同 JS
来源：http://dali.zhoulong.xyz/Article/details/gtvdmqgcgn.html

Java: synchronized (this) { shared++; }
来源：http://dali.sxryk.cn/Article/details/gtttifslru.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hysaishi.cn/Article/details/gtomnxxxcs.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yonumen.top/Article/details/gtaonyusgq.html

C#:   lock (gate) { shared++; }
来源：http://dali.jlsjyb.cn/Article/details/gtzphsonki.html

[O04] 定义异步函数并等待
来源：http://dali.cdnleiting.top/Article/details/gtfgknuilh.html

Py:   async def f():⏎    await g()
来源：http://dali.jlsjyb.cn/Article/details/gtdskozqfc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zdqjudy.top/Article/details/gteyxgqpsm.html

JS:   async function f() { await g(); }
来源：http://dali.xziqi.cn/Article/details/gtbbutruwc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gotoacloud.top/Article/details/gtvxkiwssi.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.birdmap.top/Article/details/gtilqftpzr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xylfe.cn/Article/details/gtjyeifbfh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.haohaochexian.top/Article/details/gtwhrogjzz.html

C#:   async Task F() { await G(); }
来源：http://dali.dianchejie.cn/Article/details/gthufcuhib.html

[O05] 并发执行并等待全部完成
来源：http://dali.jianghu66.top/Article/details/gtqrnezamx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sufxvd.cn/Article/details/gthuteipwn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cucudq.cn/Article/details/gtbliqblbn.html

JS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gtlsvigoyi.html

TS:   await Promise.all(tasks)
来源：http://dali.iojbl.cn/Article/details/gtkewqreiy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hywenlv.cn/Article/details/gtgjwrjitr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cqqwz.cn/Article/details/gtahgcfjyw.html

Ruby: threads.map(&:join)
来源：http://dali.c1oappe.top/Article/details/gtvliltqey.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjhdsxsvz.html

[O06] 使用进程池
来源：http://dali.birdmap.top/Article/details/gthqrzvrnc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.meibo888.top/Article/details/gtyyqedkrj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ehwqpu.com/Article/details/gtcpdcbnks.html

JS:   // child_process / cluster 模块
来源：http://dali.ydzc1.top/Article/details/gtmkwvxtga.html

TS:   // child_process / cluster 模块
来源：http://dali.shuidangran.top/Article/details/gtfpicondt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.haohaochexian.top/Article/details/gthtubjlmk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.wangshuangyany.cn/Article/details/gtneawtvip.html

Ruby: // fork 块
来源：http://dali.cdnleiting.top/Article/details/gtykxkwkif.html

C#:   Parallel.For
来源：http://dali.316326.xyz/Article/details/gtqinsaaep.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtylisosgm.html

P. 常用工具函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttrxyhepp.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtwjneyzpi.html

[P01] 生成 UUID
来源：http://dali.yvedp.cn/Article/details/gturytwjbi.html

Py:   str(uuid.uuid4())
来源：http://dali.cashguo.top/Article/details/gthxnfenxr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nanxinkj.top/Article/details/gtmgvfkrzl.html

JS:   crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gtlyxydjnl.html

TS:   crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gthmrlqafn.html

Java: UUID.randomUUID().toString()
来源：http://dali.vqdsnc.cn/Article/details/gtnuirzjje.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj202588.top/Article/details/gtgfugnxwm.html

Ruby: SecureRandom.uuid
来源：http://dali.ybcxt.top/Article/details/gtodqjgsfl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yongpay.top/Article/details/gtodesotnn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenjidiqi.icu/Article/details/gtxczutykq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj20258.top/Article/details/gtmascewhw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jqgufenzy.top/Article/details/gtamwjbvxq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.pycfn.com/Article/details/gttzimfkxi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cheryme.top/Article/details/gtscsardtq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gtfrezuasm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jlsjyb.cn/Article/details/gtihogtuuc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.kuanghao11.cn/Article/details/gthmffzrup.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.dianchejie.cn/Article/details/gtuszqbjat.html

[P03] 生成短随机字符串
来源：http://dali.tian-w.cn/Article/details/gtrzidpgmc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.aibaodan.cn/Article/details/gtahrdbila.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinqigufen.top/Article/details/gtwjzgilla.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sufxvd.cn/Article/details/gteywmbbgx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cucudq.cn/Article/details/gteqzmixxw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhongyouzk.top/Article/details/gtedclkhxi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cqqwz.cn/Article/details/gthxrnxign.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.daxiang520.top/Article/details/gtvzvynpqt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.316326.xyz/Article/details/gtzonkhiqu.html

[P04] 求长度
来源：http://dali.hongshengwenyu.top/Article/details/gtusdrfapw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sufxvd.cn/Article/details/gtdgsomawc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtsgbxbfym.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxinkj.top/Article/details/gtqqxjfwar.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhiwuduotai.top/Article/details/gtckrdenfb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jqgfzy.top/Article/details/gtznpqisyb.html

Go:   len(arr);  len(m)
来源：http://dali.jyoumei.cn/Article/details/gttfwwsegv.html

Ruby: x.length;  x.size
来源：http://dali.jinqigufen.top/Article/details/gtwbkyjhgk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hongshengwenyu.top/Article/details/gtbotecilr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.smart0.xyz/Article/details/gtwfuccvhx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinqigufen.top/Article/details/gtfppeyjsf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sufxvd.cn/Article/details/gtprhdzsvx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj20258.top/Article/details/gtawqozemu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xylfe.cn/Article/details/gtjuczjfqa.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.vqdsnc.cn/Article/details/gtlrhvhpgm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tianlin.xyz/Article/details/gtjfagysru.html

Ruby: a == b
来源：http://dali.gzhubu.top/Article/details/gtsxxdrxsz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yuxming.cn/Article/details/gtluckjxdg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.c1oappe.top/Article/details/gtmdmuhrpg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yangfankeji.com/Article/details/gtrjezrgwd.html

PHP:  if (empty($x)) {}
来源：http://dali.gogol.net.cn/Article/details/gtnngqcawc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.haohaochexian.top/Article/details/gtxtnguvnh.html

TS:   if (x == null) {}
来源：http://dali.jinqigufen.top/Article/details/gtltdcehof.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtrqfkxkbj.html

Go:   if x == nil {}
来源：http://dali.jianghu66.top/Article/details/gtzseaankg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthgexswyb.html

C#:   if (x is null) {}
来源：http://dali.yanxiufei.cn/Article/details/gtyrginirs.html

[P07] 防抖与节流
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxeowmjqm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.vqdsnc.cn/Article/details/gtmxqcsuzq.html

PHP:  // 手写时间戳比较
来源：http://dali.ppjwa.cn/Article/details/gtuggopctg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtwrpmzrkf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dashuyun.cn/Article/details/gtwgxzvexo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvmmzmes.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hnqzz.top/Article/details/gtfkctryqg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzznymmbz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.dianchejie.cn/Article/details/gtrbmdfhlw.html

[P08] 处理浮点精度问题
来源：http://dali.cucudq.cn/Article/details/gtceabyhzo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.vqdsnc.cn/Article/details/gtzuyzjany.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.quarkkingdee.top/Article/details/gtpalbaxgd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj202588.top/Article/details/gtocsapbob.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jqgufenzy.top/Article/details/gtfgkovhmr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.316326.xyz/Article/details/gtxqiquezv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.fengsongda.top/Article/details/gtsziavhlm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ppjwa.cn/Article/details/gtfjnphndd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.pengpengdd.cyou/Article/details/gtudoievyo.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtjmwmzcgu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj202588.top/Article/details/gthhocxsoo.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtnzzsfzez.html

[Q01] 创建表
来源：http://dali.wangdashe.top/Article/details/gtaqmzkmla.html

CREATE TABLE users (
来源：http://dali.yj20258888.top/Article/details/gtvemepzma.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cheryme.top/Article/details/gtlnoonywb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gogol.net.cn/Article/details/gtwanboucb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nanxuanxn.top/Article/details/gtjnksoaju.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.guannengcc.top/Article/details/gtcdrfefxd.html

);
来源：http://dali.dashuyun.cn/Article/details/gtektwomen.html

[Q02] 创建带外键的表
来源：http://dali.0kj1m.cn/Article/details/gtqwrxjert.html

CREATE TABLE orders (
来源：http://dali.wangdashe.top/Article/details/gtjyihhpte.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yangfankeji.com/Article/details/gtmfxzzccc.html

user_id INT NOT NULL,
来源：http://dali.daria6918.cn/Article/details/gtvawrbqsb.html

amount DECIMAL(10, 2),
来源：http://dali.0kj1m.cn/Article/details/gtjvhnovhj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrlihiah.html

);
来源：http://dali.jinqigufen.top/Article/details/gtrowobmcw.html

[Q03] 增加列
来源：http://dali.zdqjudy.top/Article/details/gtasyijncm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yangfankeji.com/Article/details/gtfhswvsry.html

[Q04] 修改列类型
来源：http://dali.sweek.top/Article/details/gtvvumbran.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.bjfxy.top/Article/details/gtuegbaptr.html

[Q05] 重命名列
来源：http://dali.zhiwuduotai.top/Article/details/gtsxagojwx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xylfe.cn/Article/details/gtxcfixjpw.html

[Q06] 删除列
来源：http://dali.dianchejie.cn/Article/details/gtdoaxmcjy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.fengsongda.top/Article/details/gtskwtobkr.html

[Q07] 删除表
来源：http://dali.havefunace.top/Article/details/gtjrqndgux.html

DROP TABLE IF EXISTS orders;
来源：http://dali.pycfn.com/Article/details/gtmhcdzkuy.html

[Q08] 创建普通索引
来源：http://dali.fengsongda.top/Article/details/gtwgecukhk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.pycfn.com/Article/details/gtonnwwpup.html

[Q09] 创建唯一索引
来源：http://dali.hfpthk.cn/Article/details/gtfuouqngu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yj202588.top/Article/details/gthcfqrttj.html

[Q10] 插入单行
来源：http://dali.hysaishi.cn/Article/details/gtxikbqonx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yongpay.top/Article/details/gtnzoxrnqi.html

[Q11] 一次插入多行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzztigjrz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.redwolf501.top/Article/details/gtwtkiynqx.html

[Q12] 插入后取自增 ID
来源：http://dali.zhengqikj.top/Article/details/gtvfgygrwj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nwbrower.top/Article/details/gtarupqlir.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.aibaodan.cn/Article/details/gtlzmgrwqk.html

[Q13] 忽略重复插入
来源：http://dali.tian-w.cn/Article/details/gtrdofqosx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.daria6918.cn/Article/details/gtgzklrrwg.html

[Q14] 存在则更新（upsert）
来源：http://dali.zdqjudy.top/Article/details/gtwsdzlwhb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jianghu66.top/Article/details/gtfaidaycv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.havefunace.top/Article/details/gtrdrpdidb.html

[Q15] 查询全部
来源：http://dali.jqgufenzy.top/Article/details/gttjsfihln.html

SELECT * FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtgfsiahpr.html

[Q16] 查询指定列
来源：http://dali.hammf.cn/Article/details/gtqiexbqqi.html

SELECT id, name FROM users;
来源：http://dali.yj202588.top/Article/details/gtugllqyqx.html

[Q17] 条件查询
来源：http://dali.pengpengdd.cyou/Article/details/gtdfcqftmr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cheryme.top/Article/details/gtfryqqvjx.html

[Q18] 模糊匹配
来源：http://dali.xylfe.cn/Article/details/gthppabibx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nanxinkj.top/Article/details/gtnruqylwz.html

[Q19] 范围查询
来源：http://dali.yj20258888.top/Article/details/gtuinapitu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj202588.top/Article/details/gtuswtdbcr.html

[Q20] IN 列表
来源：http://dali.pengpengdd.cyou/Article/details/gtkbtuqzvb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhongyouzk.top/Article/details/gtcsdeewzp.html

[Q21] 空值判断
来源：http://dali.daria6918.cn/Article/details/gtdxgdadtm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hfpthk.cn/Article/details/gtjoapjxbi.html

[Q22] 排序
来源：http://dali.zhengqikj.top/Article/details/gtnioxglcd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xuanzx.com/Article/details/gtaarnkmqf.html

[Q23] 分页
来源：http://dali.chenlongwang.top/Article/details/gtvmardsaq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yuxming.cn/Article/details/gtcrqipdlg.html

[Q24] 去重
来源：http://dali.yangfankeji.com/Article/details/gtlwcozhim.html

SELECT DISTINCT city FROM users;
来源：http://dali.birdmap.top/Article/details/gtixhtuocf.html

[Q25] 只取前 N 条
来源：http://dali.jqgfzy.top/Article/details/gtflelbhky.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gzhubu.top/Article/details/gtmtgifqfu.html

[Q26] 计数
来源：http://dali.zdqjudy.top/Article/details/gthybalevw.html

SELECT COUNT(*) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtcrjbdwzu.html

[Q27] 条件计数
来源：http://dali.xuanzx.com/Article/details/gtlujailqo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtvithlyuq.html

[Q28] 求和与平均
来源：http://dali.xinyue.icu/Article/details/gtzosxvhst.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtcikeusew.html

[Q29] 最大最小值
来源：http://dali.hammf.cn/Article/details/gtstydxfys.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtvlourqcm.html

[Q30] 分组统计
来源：http://dali.jinqigufen.top/Article/details/gtskfoohmo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gtkasqyjpk.html

[Q31] 分组后过滤
来源：http://dali.svipenyu.cn/Article/details/gtgafanwxx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tanke756.top/Article/details/gtpjirqgpx.html

[Q32] 分组拼接字符串
来源：http://dali.redwolf501.top/Article/details/gtgfcqleia.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gtcimjjrqe.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.bjfxy.top/Article/details/gtnikjrxam.html

[Q33] 多列分组
来源：http://dali.kuanghao11.cn/Article/details/gtfyuxcxxv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jyoumei.cn/Article/details/gtxunqnpie.html

[Q34] 每组取第一条
来源：http://dali.jlsjyb.cn/Article/details/gtdivpjdas.html

SELECT * FROM (
来源：http://dali.hywenlv.cn/Article/details/gttaobwtbp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhiwuduotai.top/Article/details/gtaszdiviw.html

) t WHERE rn = 1;
来源：http://dali.dianchejie.cn/Article/details/gtlrnezuzw.html

[Q35] 内连接
来源：http://dali.aibaodan.cn/Article/details/gtiuqasdbr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zycfv.cn/Article/details/gtzhhfcbdh.html


<!-- 参考信息 -->