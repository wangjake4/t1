代发 wailian999

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenjidiqi.icu/Article/details/gtgyxfdexr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqqxnflq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.daxiang520.top/Article/details/gtgkuvjczf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gtkuqxwpvt.html

[N05] 最大公约数
来源：http://dali.zhiwuduotai.top/Article/details/gtobyxixfv.html

Py:   math.gcd(a, b)
来源：http://dali.sufxvd.cn/Article/details/gtvsaugvwe.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zdqjudy.top/Article/details/gtsnxcxxuk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtugkwhwrc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.c1oappe.top/Article/details/gtbvbmzcfc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.daria6918.cn/Article/details/gtptgdpjaq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.andypj.xyz/Article/details/gthczfzgmr.html

Ruby: a.gcd(b)
来源：http://dali.9152youxi.cn/Article/details/gtziqnvbef.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zdqjudy.top/Article/details/gtsxbqzvxz.html

[N06] 判断回文字符串
来源：http://dali.shangyingyoupin.top/Article/details/gttnzeeyda.html

Py:   s == s[::-1]
来源：http://dali.zhongyouzk.top/Article/details/gtghxqihcr.html

PHP:  $s === strrev($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtrxldeczc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtefmxzguc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gtinigldgx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shangyingyoupin.top/Article/details/gttkosdsru.html

Go:   // 双指针从两端比较
来源：http://dali.yuanzhike.top/Article/details/gthzoqsnar.html

Ruby: s == s.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtnjgvxjef.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sxryk.cn/Article/details/gtfnoxzeik.html

[N07] 两数之和（返回下标）
来源：http://dali.guannengcc.top/Article/details/gtqvwwibcz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gogol.net.cn/Article/details/gtztuvpcxo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hysaishi.cn/Article/details/gtoxsvxwvh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.0kj1m.cn/Article/details/gtdktmxwwe.html

TS:   // 手写 Map<string, number>
来源：http://dali.9152youxi.cn/Article/details/gtkwibrvgo.html

Java: // 手写 HashMap
来源：http://dali.xinyue.icu/Article/details/gtdmlyqyuw.html

Go:   // 手写 map[int]int
来源：http://dali.chenjidiqi.icu/Article/details/gtcviymnjs.html

Ruby: // 手写 Hash
来源：http://dali.wangdashe.top/Article/details/gttejsevjt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zycfv.cn/Article/details/gtkuhmzjfx.html

[N08] 生成全排列
来源：http://dali.dashuyun.cn/Article/details/gtahakdyga.html

Py:   itertools.permutations(arr)
来源：http://dali.yuanzhike.top/Article/details/gtphkxcoae.html

PHP:  // 手写递归交换
来源：http://dali.ybcxt.top/Article/details/gtlpmizqev.html

JS:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtbulagsbs.html

TS:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtglrzpsox.html

Java: // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtyqlwvogk.html

Go:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtymwoapus.html

Ruby: arr.permutation.to_a
来源：http://dali.yj20258888.top/Article/details/gteqwugamy.html

C#:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtmqypujzx.html

[N09] 栈与队列
来源：http://dali.jiagoushi.top/Article/details/gtdiciqmzg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.aibaodan.cn/Article/details/gtxdwataec.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gtphyiybpl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gthxawumbl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yanxiufei.cn/Article/details/gtapkjfaho.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.pycfn.com/Article/details/gteciuccwy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zdqjudy.top/Article/details/gtnshfiugx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gtnaludxak.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.wangshuangyany.cn/Article/details/gtnjmyovlu.html

[N10] 链表节点定义
来源：http://dali.shzxlz.cn/Article/details/gtewksacdv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj20258888.top/Article/details/gtrprhlhrv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj202588.top/Article/details/gtxnuzxbyi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj202588.top/Article/details/gtewgdwuom.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tanke756.top/Article/details/gtdloyjsiu.html

Java: class Node { int v; Node next; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtouqldidl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.vqdsnc.cn/Article/details/gthvzbcfes.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.redwolf501.top/Article/details/gtynatphei.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahstquun.html

[N11] 二叉树中序遍历
来源：http://dali.gaohongyu789.top/Article/details/gttryxhzfv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shangyingyoupin.top/Article/details/gtofnjetfr.html

PHP:  // 手写递归函数
来源：http://dali.ivvv.top/Article/details/gthricoqhl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gogol.net.cn/Article/details/gtfuguvpkd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.havefunace.top/Article/details/gtwiggiiav.html

Java: // 手写递归
来源：http://dali.xuanzx.com/Article/details/gtriuiskol.html

Go:   // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gtmnykaina.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gzhubu.top/Article/details/gtdezmtrel.html

C#:   // 手写递归
来源：http://dali.redwolf501.top/Article/details/gtphogvlqt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.fzhhl.top/Article/details/gtwipigzrd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.feifeiyinyue.top/Article/details/gterlsbwmf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zycfv.cn/Article/details/gtbqsznnnq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daxiang520.top/Article/details/gtnnobovgc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangdashe.top/Article/details/gtvuvqjrxr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tanke756.top/Article/details/gtjlpvscqr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.quarkkingdee.top/Article/details/gtscfbzyzt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gtnegqcohd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuetiantiany.cn/Article/details/gtkbzreeua.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtegvwvqpx.html

O. 并发与异步
来源：http://dali.ivvv.top/Article/details/gtdqmmccua.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtaaajkoou.html

[O01] 启动一个线程
来源：http://dali.ybcxt.top/Article/details/gtkauqpjpt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yuanzhike.top/Article/details/gtaqbszfql.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinqigufen.top/Article/details/gtewlgrmrj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xylfe.cn/Article/details/gtpgcdnida.html

TS:   // 同 JS
来源：http://dali.jinqigufen.top/Article/details/gtdahpobhi.html

Java: new Thread(() -> f()).start()
来源：http://dali.yongpay.top/Article/details/gtdevgrpod.html

Go:   go f()
来源：http://dali.yuxming.cn/Article/details/gtrztirgyz.html

Ruby: Thread.new { f }
来源：http://dali.hywenlv.cn/Article/details/gtrghpplvi.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258.top/Article/details/gtvmchumuo.html

[O02] 使用线程池
来源：http://dali.haohaochexian.top/Article/details/gtnsswtraa.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jqgfzy.top/Article/details/gtufshxozt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj20258.top/Article/details/gtrycnyqrd.html

JS:   // worker_threads 线程池
来源：http://dali.jinqigufen.top/Article/details/gtopjfdsls.html

TS:   // worker_threads 线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcycxdjyp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gogol.net.cn/Article/details/gtrfsqjmjj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinqigufen.top/Article/details/gtvvyowkvp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.daria6918.cn/Article/details/gtyvmpjmbr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ywan-chungtsiang.top/Article/details/gtifumqypn.html

[O03] 加锁保护共享数据
来源：http://dali.svipenyu.cn/Article/details/gtervzqqdq.html

Py:   with lock: shared += 1
来源：http://dali.snrcjt.cn/Article/details/gtkolxrbjq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.havefunace.top/Article/details/gtswujgbtl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.haohaochexian.top/Article/details/gtvbozlhbo.html

TS:   // 同 JS
来源：http://dali.9152youxi.cn/Article/details/gtmdpljijv.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinqigfzy.top/Article/details/gttgwnmmhq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sxryk.cn/Article/details/gtikputzgz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ybcxt.top/Article/details/gtocfgkbgp.html

C#:   lock (gate) { shared++; }
来源：http://dali.kuanghao11.cn/Article/details/gtzrvrpclh.html

[O04] 定义异步函数并等待
来源：http://dali.guannengcc.top/Article/details/gtipetzpak.html

Py:   async def f():⏎    await g()
来源：http://dali.tanke756.top/Article/details/gtnxrasgwb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.wangdashe.top/Article/details/gtinhzmikg.html

JS:   async function f() { await g(); }
来源：http://dali.redwolf501.top/Article/details/gtqjqnvmbc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhoulong.xyz/Article/details/gtqhdarrst.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nanxuanxn.top/Article/details/gtgpllymcp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenzaomai.com/Article/details/gtjiifjvbz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ivvv.top/Article/details/gtppgmphfe.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258.top/Article/details/gtewlnhbwa.html

[O05] 并发执行并等待全部完成
来源：http://dali.wangdashe.top/Article/details/gtyfebdcxw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sweek.top/Article/details/gtdzvaixll.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.meibo888.top/Article/details/gtiexayrum.html

JS:   await Promise.all(tasks)
来源：http://dali.xuetiantiany.cn/Article/details/gtvnzxqiag.html

TS:   await Promise.all(tasks)
来源：http://dali.ehwqpu.com/Article/details/gtqfeadypo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cashguo.top/Article/details/gtducbjoqa.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tanke756.top/Article/details/gtzjwxxnjn.html

Ruby: threads.map(&:join)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttatchiix.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hnxiangtu.top/Article/details/gtbltabcfj.html

[O06] 使用进程池
来源：http://dali.guowangkeji.top/Article/details/gtifkphrzs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.guowangkeji.top/Article/details/gtxohmdoka.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shzxlz.cn/Article/details/gtoraiytyq.html

JS:   // child_process / cluster 模块
来源：http://dali.9152youxi.cn/Article/details/gtrjqvehme.html

TS:   // child_process / cluster 模块
来源：http://dali.xuanzx.com/Article/details/gtkhnuazdr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yongpay.top/Article/details/gtrvgaoulz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jianghu66.top/Article/details/gtiflwaugz.html

Ruby: // fork 块
来源：http://dali.yanxiufei.cn/Article/details/gtfpaooqbt.html

C#:   Parallel.For
来源：http://dali.jlsjyb.cn/Article/details/gteqwkwtlg.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtissyvmtp.html

P. 常用工具函数
来源：http://dali.havefunace.top/Article/details/gtisiurcaz.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvpkvxmi.html

[P01] 生成 UUID
来源：http://dali.jinqigfzy.top/Article/details/gtkvvkqwnf.html

Py:   str(uuid.uuid4())
来源：http://dali.havefunace.top/Article/details/gtbpdjetpz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yj20258888.top/Article/details/gtnwzrfqdc.html

JS:   crypto.randomUUID()
来源：http://dali.vqdsnc.cn/Article/details/gtswktwftd.html

TS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gtgbtpnlwp.html

Java: UUID.randomUUID().toString()
来源：http://dali.sysykeji.top/Article/details/gtmbvvjyei.html

Go:   // 用 github.com/google/uuid
来源：http://dali.guannengcc.top/Article/details/gtivtruzzs.html

Ruby: SecureRandom.uuid
来源：http://dali.gzhubu.top/Article/details/gtmxdiibpw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.c1oappe.top/Article/details/gtpvadxlrl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwngpvnr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gzhubu.top/Article/details/gtfrivysfq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cdnleiting.top/Article/details/gtrefqcxdn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sweek.top/Article/details/gturxlxbhr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hnxiangtu.top/Article/details/gtblvlmjhq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gtwjthtfqi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ivvv.top/Article/details/gtnwvmphxi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hnxiangtu.top/Article/details/gtxoivweoz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nanxinkj.top/Article/details/gtqvqrlqaf.html

[P03] 生成短随机字符串
来源：http://dali.aibaodan.cn/Article/details/gthryrxgtw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tanke756.top/Article/details/gtfgeifgzw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.svipenyu.cn/Article/details/gturszdzzk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.kuanghao11.cn/Article/details/gtdyybmdwg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gtmfkbyrze.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tanke756.top/Article/details/gtmldaqskq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.feifeiyinyue.top/Article/details/gtounwhepu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jqgufenzy.top/Article/details/gtnopgchnm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hysaishi.cn/Article/details/gtegernnwd.html

[P04] 求长度
来源：http://dali.jqgfzy.top/Article/details/gtkpciqjdt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gaohongyu789.top/Article/details/gtdiujilbo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaryvxtcc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.316326.xyz/Article/details/gtlrjoteot.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tian-w.cn/Article/details/gtwtegiizq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hywenlv.cn/Article/details/gtftbvrfud.html

Go:   len(arr);  len(m)
来源：http://dali.cucudq.cn/Article/details/gtmffgubdx.html

Ruby: x.length;  x.size
来源：http://dali.snrcjt.cn/Article/details/gtogtygiby.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.meibo888.top/Article/details/gtkujkygsb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nwbrower.top/Article/details/gtapyveftb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xuetiantiany.cn/Article/details/gtbhyvlujo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhhmbpdt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yueranfly.top/Article/details/gtzrtuuhnb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.meibo888.top/Article/details/gtsqitnysv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj20258.top/Article/details/gtwhverayr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.havefunace.top/Article/details/gtwivrnbka.html

Ruby: a == b
来源：http://dali.havefunace.top/Article/details/gtfnspncvk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yvedp.cn/Article/details/gtdbywwqxq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinghuilouyu.cn/Article/details/gtpwwxgapf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.wangdashe.top/Article/details/gtgoacznii.html

PHP:  if (empty($x)) {}
来源：http://dali.zycfv.cn/Article/details/gtbmqrlfch.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.pengpengdd.cyou/Article/details/gtjqqdhwdd.html

TS:   if (x == null) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtaclesadz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtzknjywsd.html

Go:   if x == nil {}
来源：http://dali.quarkkingdee.top/Article/details/gtqpehmxrk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jqgfzy.top/Article/details/gtemoddvxp.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gtfrdgcgiy.html

[P07] 防抖与节流
来源：http://dali.guowangkeji.top/Article/details/gtvzaasuqc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.kuanghao11.cn/Article/details/gtaguoswap.html

PHP:  // 手写时间戳比较
来源：http://dali.mhx1999.top/Article/details/gttryokqjb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.0kj1m.cn/Article/details/gtzojvhigp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gtedrjhevj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinqigfzy.top/Article/details/gtgjzslprw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gaohongyu789.top/Article/details/gtwmqhpvdy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjnrauorl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinqigufen.top/Article/details/gtidwawnoe.html

[P08] 处理浮点精度问题
来源：http://dali.tianlin.xyz/Article/details/gtebheiezd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hammf.cn/Article/details/gtpxbviwxh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ppjwa.cn/Article/details/gtqcfqnixd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gogol.net.cn/Article/details/gtyhihmjlq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hnxiangtu.top/Article/details/gtnydtsloc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj202588.top/Article/details/gtrqyrlwed.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yonumen.top/Article/details/gtnshblzsn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj202588.top/Article/details/gtxuswfwmj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cheryme.top/Article/details/gtacsdjitr.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtwxbmafua.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.daxiang520.top/Article/details/gttvsmcdhj.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtfvbdboqn.html

[Q01] 创建表
来源：http://dali.birdmap.top/Article/details/gtycaizoou.html

CREATE TABLE users (
来源：http://dali.zycfv.cn/Article/details/gtwvnnyaqr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gzhubu.top/Article/details/gtrojlkqhb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.andypj.xyz/Article/details/gtfekvielc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.svipenyu.cn/Article/details/gtvlbmhncv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xinyue.icu/Article/details/gtojlmdwtu.html

);
来源：http://dali.bjfxy.top/Article/details/gtjjckfojb.html

[Q02] 创建带外键的表
来源：http://dali.daxiang520.top/Article/details/gtmzsbyzfs.html

CREATE TABLE orders (
来源：http://dali.ivvv.top/Article/details/gtfrqekoga.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.andypj.xyz/Article/details/gtuqjdtuaw.html

user_id INT NOT NULL,
来源：http://dali.jinqigufen.top/Article/details/gtukdylola.html

amount DECIMAL(10, 2),
来源：http://dali.shuidangran.top/Article/details/gtdfayenfl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jiagoushi.top/Article/details/gtyuxtgelf.html

);
来源：http://dali.yueranfly.top/Article/details/gtsiguypxh.html

[Q03] 增加列
来源：http://dali.chenlongwang.top/Article/details/gtqxlzkyap.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gogol.net.cn/Article/details/gtlvpvahqc.html

[Q04] 修改列类型
来源：http://dali.birdmap.top/Article/details/gtixvlriqj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hongshengwenyu.top/Article/details/gtoitegfww.html

[Q05] 重命名列
来源：http://dali.ybcxt.top/Article/details/gtttosamle.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dashuyun.cn/Article/details/gtflqexonj.html

[Q06] 删除列
来源：http://dali.meibo888.top/Article/details/gtysfuyihb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yongpay.top/Article/details/gtlomucpul.html

[Q07] 删除表
来源：http://dali.hfpthk.cn/Article/details/gtagregkav.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gzhubu.top/Article/details/gtqxhumwwn.html

[Q08] 创建普通索引
来源：http://dali.nwbrower.top/Article/details/gtyiwdwfkz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cqqwz.cn/Article/details/gtcskqipzc.html

[Q09] 创建唯一索引
来源：http://dali.kuanghao11.cn/Article/details/gtnbmxhyhw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.vqdsnc.cn/Article/details/gtrmwqgjpf.html

[Q10] 插入单行
来源：http://dali.vqdsnc.cn/Article/details/gtqetecwoa.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tian-w.cn/Article/details/gtkmisbobe.html

[Q11] 一次插入多行
来源：http://dali.birdmap.top/Article/details/gtmufizpdd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jianghu66.top/Article/details/gtxekoqnlg.html

[Q12] 插入后取自增 ID
来源：http://dali.zhengqikj.top/Article/details/gtkmelkwcn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.aibaodan.cn/Article/details/gtoiklvvjy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.redwolf501.top/Article/details/gtqtbjwxao.html

[Q13] 忽略重复插入
来源：http://dali.cqqwz.cn/Article/details/gtrftqnrra.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gotoacloud.top/Article/details/gtpturthwg.html

[Q14] 存在则更新（upsert）
来源：http://dali.xziqi.cn/Article/details/gtfbsebtgr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jqgufenzy.top/Article/details/gtptiarxrd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shzxlz.cn/Article/details/gtuzuzkhdw.html

[Q15] 查询全部
来源：http://dali.hfpthk.cn/Article/details/gtokyxypxm.html

SELECT * FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtrqtflbiq.html

[Q16] 查询指定列
来源：http://dali.zdqjudy.top/Article/details/gtoiizwurm.html

SELECT id, name FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtihkrvajq.html

[Q17] 条件查询
来源：http://dali.shangyingyoupin.top/Article/details/gtgpoqykok.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtyrzzllpo.html

[Q18] 模糊匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtdkzxehfb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhengqikj.top/Article/details/gtbjbxgovu.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gtbpgzufwh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinqigfzy.top/Article/details/gtmcdiwobo.html

[Q20] IN 列表
来源：http://dali.c1oappe.top/Article/details/gtghjbphfu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jyoumei.cn/Article/details/gtxbfxgtdo.html

[Q21] 空值判断
来源：http://dali.jinqigufen.top/Article/details/gtgudlucyu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenlongwang.top/Article/details/gtczxvvwic.html

[Q22] 排序
来源：http://dali.iojbl.cn/Article/details/gtwxbhgrxp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.guowangkeji.top/Article/details/gtcccsfwml.html

[Q23] 分页
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebfzbbiv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.daria6918.cn/Article/details/gtpvolazjp.html

[Q24] 去重
来源：http://dali.hammf.cn/Article/details/gtjnbldqyo.html

SELECT DISTINCT city FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gthhbcabjg.html

[Q25] 只取前 N 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwlqrjrfc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yuanzhike.top/Article/details/gtdjrlaruh.html

[Q26] 计数
来源：http://dali.hnqzz.top/Article/details/gthdrkbmkj.html

SELECT COUNT(*) FROM users;
来源：http://dali.birdmap.top/Article/details/gtjpinncfn.html

[Q27] 条件计数
来源：http://dali.zhongyouzk.top/Article/details/gtwpsvwojl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xziqi.cn/Article/details/gtcfauxipe.html

[Q28] 求和与平均
来源：http://dali.iojbl.cn/Article/details/gtmspuccou.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzyrtvvqt.html

[Q29] 最大最小值
来源：http://dali.jiagoushi.top/Article/details/gtaetnupnm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtlwxbthcs.html

[Q30] 分组统计
来源：http://dali.316326.xyz/Article/details/gttricgmpp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvsooplwu.html

[Q31] 分组后过滤
来源：http://dali.kuanghao11.cn/Article/details/gtchoqejzr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.pycfn.com/Article/details/gtehkyroif.html

[Q32] 分组拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gtozkcbsqs.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gtnoqbdkah.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hongshengwenyu.top/Article/details/gtzogekugw.html

[Q33] 多列分组
来源：http://dali.tanke756.top/Article/details/gtdwwcntyt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.smart0.xyz/Article/details/gtksgkmhqd.html

[Q34] 每组取第一条
来源：http://dali.c1oappe.top/Article/details/gtqijmftdc.html

SELECT * FROM (
来源：http://dali.cucudq.cn/Article/details/gtdxfyfbyj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.wangdashe.top/Article/details/gtumdgnryg.html

) t WHERE rn = 1;
来源：http://dali.xziqi.cn/Article/details/gtfitxqjbl.html

[Q35] 内连接
来源：http://dali.gotoacloud.top/Article/details/gtbofmscin.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.c1oappe.top/Article/details/gtvtgakfeb.html

[Q36] 左连接
来源：http://dali.feifeiyinyue.top/Article/details/gtrsygrhvw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gtkeyvdtpl.html

[Q37] 右连接
来源：http://dali.havefunace.top/Article/details/gtxkjajaot.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xuanzx.com/Article/details/gtzygefkre.html


<!-- 参考信息 -->