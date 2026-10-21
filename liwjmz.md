代发 wailian999

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxuanxn.top/Article/details/gtnseanvza.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.mhx1999.top/Article/details/gtiuehocrl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gtsgaontpj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gtwolwzlpa.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gtwxqpgham.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmocdpbvg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sweek.top/Article/details/gtkzjxjrqx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtvutxibln.html

[N05] 最大公约数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlsvhheqp.html

Py:   math.gcd(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjtihtilk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.guowangkeji.top/Article/details/gttlbzetqw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gtqbmbezxj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdmmiuuvn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gtvwxhqanz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xinyue.icu/Article/details/gtivoukcyv.html

Ruby: a.gcd(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtnrultnwg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jqgufenzy.top/Article/details/gtculvridd.html

[N06] 判断回文字符串
来源：http://dali.shuidangran.top/Article/details/gtvpwdsrfp.html

Py:   s == s[::-1]
来源：http://dali.316326.xyz/Article/details/gtaxvxylvu.html

PHP:  $s === strrev($s);
来源：http://dali.dashuyun.cn/Article/details/gtgjhehlqi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gtmbsuvbem.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gtuxhatyom.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gaohongyu789.top/Article/details/gtspdlqjjh.html

Go:   // 双指针从两端比较
来源：http://dali.cdnleiting.top/Article/details/gtszuhuyrq.html

Ruby: s == s.reverse
来源：http://dali.guannengcc.top/Article/details/gtvuxkaznk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nanxuanxn.top/Article/details/gtgrlhzlxc.html

[N07] 两数之和（返回下标）
来源：http://dali.hongshengwenyu.top/Article/details/gtajqjsoag.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yongpay.top/Article/details/gtxomuufhf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinyuanbaomall.cn/Article/details/gtllwoizvr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.pengpengdd.cyou/Article/details/gtxhlyaigj.html

TS:   // 手写 Map<string, number>
来源：http://dali.gogol.net.cn/Article/details/gtztkcyoew.html

Java: // 手写 HashMap
来源：http://dali.ppjwa.cn/Article/details/gtklclbszi.html

Go:   // 手写 map[int]int
来源：http://dali.daria6918.cn/Article/details/gtucoujtkh.html

Ruby: // 手写 Hash
来源：http://dali.bjfxy.top/Article/details/gtzrrmpsna.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyerzctcq.html

[N08] 生成全排列
来源：http://dali.gzhubu.top/Article/details/gtxcabpsuf.html

Py:   itertools.permutations(arr)
来源：http://dali.cqqwz.cn/Article/details/gtpacjyyut.html

PHP:  // 手写递归交换
来源：http://dali.ydzc1.top/Article/details/gtxlfninda.html

JS:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtauqvgdqo.html

TS:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtowizwlll.html

Java: // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtreeevnzw.html

Go:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtuintclhu.html

Ruby: arr.permutation.to_a
来源：http://dali.xuanzx.com/Article/details/gtzwgwhned.html

C#:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtzmmypzal.html

[N09] 栈与队列
来源：http://dali.ydzc1.top/Article/details/gtienbnwpj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.mhx1999.top/Article/details/gtmiqccdez.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gtfhrkxizh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yvedp.cn/Article/details/gtunsevrvw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.c1oappe.top/Article/details/gtptvqmpkr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj20258.top/Article/details/gtsgpjslqh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenzaomai.com/Article/details/gtzisbtlkq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yuxming.cn/Article/details/gtconiygyg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hywenlv.cn/Article/details/gtdfdylcpz.html

[N10] 链表节点定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gthsdvimwj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hammf.cn/Article/details/gtmnfybpwv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhengqikj.top/Article/details/gttjxblljn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jlsjyb.cn/Article/details/gtvgjjhnjg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.fengsongda.top/Article/details/gtluoznsxk.html

Java: class Node { int v; Node next; }
来源：http://dali.jianghu66.top/Article/details/gtrfyfczvk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zycfv.cn/Article/details/gtocmwkkko.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sxryk.cn/Article/details/gtmesdrycb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.daxiang520.top/Article/details/gthtupaqaz.html

[N11] 二叉树中序遍历
来源：http://dali.0kj1m.cn/Article/details/gtmelgtzrx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gogol.net.cn/Article/details/gtjzokaliy.html

PHP:  // 手写递归函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtdnenyjab.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgfzy.top/Article/details/gtxmhkebzn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jianghu66.top/Article/details/gtyuliqztu.html

Java: // 手写递归
来源：http://dali.pengpengdd.cyou/Article/details/gtqftoypmo.html

Go:   // 手写递归
来源：http://dali.daxiang520.top/Article/details/gtjhzqixtb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.smart0.xyz/Article/details/gtheeucucl.html

C#:   // 手写递归
来源：http://dali.haohaochexian.top/Article/details/gtshgqdmhm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.havefunace.top/Article/details/gtuidrkgvb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwelvphx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ivvv.top/Article/details/gtigueeaky.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yonumen.top/Article/details/gtgxkxnaoo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.haohaochexian.top/Article/details/gtdnrchygs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hammf.cn/Article/details/gtxdufbvxz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sxryk.cn/Article/details/gtsmbrscca.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.daria6918.cn/Article/details/gtzmcqbmbe.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sufxvd.cn/Article/details/gtftpmwotp.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtalnegbmp.html

O. 并发与异步
来源：http://dali.cucudq.cn/Article/details/gtngqgwtrn.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gturazozkc.html

[O01] 启动一个线程
来源：http://dali.pengpengdd.cyou/Article/details/gtfrzcpqdq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hnxiangtu.top/Article/details/gtumcbuffo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sufxvd.cn/Article/details/gtzdewbvex.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nanxuanxn.top/Article/details/gtckbzfufr.html

TS:   // 同 JS
来源：http://dali.jianghu66.top/Article/details/gtvjiqbvoy.html

Java: new Thread(() -> f()).start()
来源：http://dali.aizwys.cn/Article/details/gtqluloila.html

Go:   go f()
来源：http://dali.mhx1999.top/Article/details/gtfimwotmz.html

Ruby: Thread.new { f }
来源：http://dali.yuanzhike.top/Article/details/gtpryfwcmi.html

C#:   Task.Run(() => F());
来源：http://dali.yonumen.top/Article/details/gtpinakgbr.html

[O02] 使用线程池
来源：http://dali.bjfxy.top/Article/details/gtcmiauozs.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.haohaochexian.top/Article/details/gttdbtjcxd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinqigufen.top/Article/details/gthruqetsq.html

JS:   // worker_threads 线程池
来源：http://dali.yvedp.cn/Article/details/gtvsedfigj.html

TS:   // worker_threads 线程池
来源：http://dali.fengsongda.top/Article/details/gtsuhifpsu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jlsjyb.cn/Article/details/gtwnoyummm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cheryme.top/Article/details/gtaptwzskj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jlsjyb.cn/Article/details/gtizfdmxtj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.wangdashe.top/Article/details/gtaazqreph.html

[O03] 加锁保护共享数据
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwdpraaq.html

Py:   with lock: shared += 1
来源：http://dali.zhongyouzk.top/Article/details/gtipsbjrjn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmbbfpjdw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.9152youxi.cn/Article/details/gtcqbcykcs.html

TS:   // 同 JS
来源：http://dali.ppjwa.cn/Article/details/gtvbbfnwod.html

Java: synchronized (this) { shared++; }
来源：http://dali.meibo888.top/Article/details/gtfdrjjnww.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gzhubu.top/Article/details/gtrrbmdyff.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xuetiantiany.cn/Article/details/gtzspsajzm.html

C#:   lock (gate) { shared++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtkdkhtgym.html

[O04] 定义异步函数并等待
来源：http://dali.nanxuanxn.top/Article/details/gtcmwevfut.html

Py:   async def f():⏎    await g()
来源：http://dali.havefunace.top/Article/details/gtfthiwzwh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ybcxt.top/Article/details/gtpmmfsvse.html

JS:   async function f() { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gtahebxhan.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtqthyizfx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.feifeiyinyue.top/Article/details/gtqrdhjvii.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.dianchejie.cn/Article/details/gtjwxlpoxo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvodgulz.html

C#:   async Task F() { await G(); }
来源：http://dali.meibo888.top/Article/details/gtipsccvkz.html

[O05] 并发执行并等待全部完成
来源：http://dali.xuetiantiany.cn/Article/details/gtrdojuzng.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sweek.top/Article/details/gtvxoelenl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yonumen.top/Article/details/gtbgucsvnr.html

JS:   await Promise.all(tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmqgztmu.html

TS:   await Promise.all(tasks)
来源：http://dali.zhiwuduotai.top/Article/details/gttwswogkl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.guowangkeji.top/Article/details/gtsbweqnld.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jiagoushi.top/Article/details/gtdvunbnae.html

Ruby: threads.map(&:join)
来源：http://dali.xinyue.icu/Article/details/gtmvhkwtmd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gaohongyu789.top/Article/details/gtqjgkvzto.html

[O06] 使用进程池
来源：http://dali.jinghuilouyu.cn/Article/details/gteeqzergn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jqgufenzy.top/Article/details/gtmrncqwjj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sweek.top/Article/details/gtluqcrjbc.html

JS:   // child_process / cluster 模块
来源：http://dali.hfpthk.cn/Article/details/gtstygsggs.html

TS:   // child_process / cluster 模块
来源：http://dali.hongshengwenyu.top/Article/details/gtgfkyudqm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuxming.cn/Article/details/gtdphcmcek.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbqlaaqbm.html

Ruby: // fork 块
来源：http://dali.shzxlz.cn/Article/details/gtdhlmlnpo.html

C#:   Parallel.For
来源：http://dali.ivvv.top/Article/details/gtaixklxif.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtboicvqrq.html

P. 常用工具函数
来源：http://dali.sufxvd.cn/Article/details/gtytjumhda.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtrqbzglmv.html

[P01] 生成 UUID
来源：http://dali.yvedp.cn/Article/details/gtuumnjdts.html

Py:   str(uuid.uuid4())
来源：http://dali.gogol.net.cn/Article/details/gtulzpifcl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhoulong.xyz/Article/details/gtmyzycamt.html

JS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gtgdukwahm.html

TS:   crypto.randomUUID()
来源：http://dali.feifeiyinyue.top/Article/details/gtvealdkmn.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj202588.top/Article/details/gtgdnrykof.html

Go:   // 用 github.com/google/uuid
来源：http://dali.9152youxi.cn/Article/details/gtboayzyoz.html

Ruby: SecureRandom.uuid
来源：http://dali.tian-w.cn/Article/details/gtbdpqixoz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gaohongyu789.top/Article/details/gtklurjhmh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hnxiangtu.top/Article/details/gtskkeszzz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shuidangran.top/Article/details/gtsdmeafpx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj20258888.top/Article/details/gtfwuefcdw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.smart0.xyz/Article/details/gtntnwvkpk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gaohongyu789.top/Article/details/gtjceljbzz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gtqzbgiwqg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.meibo888.top/Article/details/gttzijytdq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gtrftawzkn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.pengpengdd.cyou/Article/details/gtylsqznnb.html

[P03] 生成短随机字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtrxwzajil.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ivvv.top/Article/details/gtchlououx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.snrcjt.cn/Article/details/gtvhhafnya.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxuanxn.top/Article/details/gtqiyoggsa.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nwbrower.top/Article/details/gtegpscils.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sufxvd.cn/Article/details/gtpcgpvmdd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.dianchejie.cn/Article/details/gtesmynplg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zdqjudy.top/Article/details/gtqoyoreaf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.haohaochexian.top/Article/details/gtxaruvjux.html

[P04] 求长度
来源：http://dali.shzxlz.cn/Article/details/gtoyshuget.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cucudq.cn/Article/details/gtmdbrjdjv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gtxrqfarei.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tian-w.cn/Article/details/gtgwyoeatz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tanke756.top/Article/details/gtwyydyaws.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ehwqpu.com/Article/details/gtwvwfsnqs.html

Go:   len(arr);  len(m)
来源：http://dali.gogol.net.cn/Article/details/gtknjhthzo.html

Ruby: x.length;  x.size
来源：http://dali.nanxuanxn.top/Article/details/gtzvqeikxx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gtseaoiehf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ybcxt.top/Article/details/gtewmjnrwl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.pycfn.com/Article/details/gthvypcagu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.aizwys.cn/Article/details/gtxaswxffk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xinyue.icu/Article/details/gtuqgrxrpy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pengpengdd.cyou/Article/details/gtleorhgah.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygweirkd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xinyue.icu/Article/details/gtbmvmvnwn.html

Ruby: a == b
来源：http://dali.shzxlz.cn/Article/details/gtbdvszrox.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.mhx1999.top/Article/details/gtnfrtghlc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ehwqpu.com/Article/details/gtuzrzuanw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinqigfzy.top/Article/details/gtgewnbhxv.html

PHP:  if (empty($x)) {}
来源：http://dali.0kj1m.cn/Article/details/gtstiskmlz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.dashuyun.cn/Article/details/gtlscpxmyl.html

TS:   if (x == null) {}
来源：http://dali.jianghu66.top/Article/details/gtpqlxmkur.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ehwqpu.com/Article/details/gtdhakidcz.html

Go:   if x == nil {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzmiiqgcl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.meibo888.top/Article/details/gtgywaecid.html

C#:   if (x is null) {}
来源：http://dali.chenlongwang.top/Article/details/gtbduaygxi.html

[P07] 防抖与节流
来源：http://dali.daxiang520.top/Article/details/gtnmpqqbsb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nwbrower.top/Article/details/gtesnfwxwd.html

PHP:  // 手写时间戳比较
来源：http://dali.fzhhl.top/Article/details/gtzhvjuuoq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cashguo.top/Article/details/gtnhuuxosn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gtfseqwfyl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hysaishi.cn/Article/details/gtukstgrjr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xuanzx.com/Article/details/gtperbzyom.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmtvrruk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gtarxqccgf.html

[P08] 处理浮点精度问题
来源：http://dali.yvedp.cn/Article/details/gtnhtqlije.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.316326.xyz/Article/details/gtpalgsdio.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.quarkkingdee.top/Article/details/gtbclceuiq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.vqdsnc.cn/Article/details/gtajluhsxw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfucrhscx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jqgufenzy.top/Article/details/gtrxzjiyvx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.dashuyun.cn/Article/details/gtpugqabqx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.daria6918.cn/Article/details/gtzgpkuuyr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yueranfly.top/Article/details/gtcsfutueo.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gthgqjlqqj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sufxvd.cn/Article/details/gthgowfees.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtctmnzvxa.html

[Q01] 创建表
来源：http://dali.zhixingplan.top/Article/details/gttryiksoh.html

CREATE TABLE users (
来源：http://dali.jqgufenzy.top/Article/details/gtcrkojkxg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zycfv.cn/Article/details/gtjnvlekus.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gaohongyu789.top/Article/details/gtyfpzsrvv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yuanzhike.top/Article/details/gtpqoroxwm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hysaishi.cn/Article/details/gtodzegjoh.html

);
来源：http://dali.jqgufenzy.top/Article/details/gtgruesjsx.html

[Q02] 创建带外键的表
来源：http://dali.jinghuilouyu.cn/Article/details/gtgakdearj.html

CREATE TABLE orders (
来源：http://dali.0kj1m.cn/Article/details/gtsivbebyd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhongyouzk.top/Article/details/gtfaszoeox.html

user_id INT NOT NULL,
来源：http://dali.yuanzhike.top/Article/details/gtfopwaknm.html

amount DECIMAL(10, 2),
来源：http://dali.shzxlz.cn/Article/details/gtqvpnxzwb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dashuyun.cn/Article/details/gttaiajjyh.html

);
来源：http://dali.meibo888.top/Article/details/gtodmwsnze.html

[Q03] 增加列
来源：http://dali.sufxvd.cn/Article/details/gtlxiuoapc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yongpay.top/Article/details/gtxanudsnq.html

[Q04] 修改列类型
来源：http://dali.ehwqpu.com/Article/details/gtrccdxojw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jyoumei.cn/Article/details/gtjhxbhnzt.html

[Q05] 重命名列
来源：http://dali.jinqigfzy.top/Article/details/gtzfglbypj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.bjfxy.top/Article/details/gtdiytjeaz.html

[Q06] 删除列
来源：http://dali.sweek.top/Article/details/gttpfjgkoo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gotoacloud.top/Article/details/gtfxgilleh.html

[Q07] 删除表
来源：http://dali.hnxiangtu.top/Article/details/gtcndwjhyl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.316326.xyz/Article/details/gtsnbvipbd.html

[Q08] 创建普通索引
来源：http://dali.nanxuanxn.top/Article/details/gtybqjqemd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.0kj1m.cn/Article/details/gtvddxjtrn.html

[Q09] 创建唯一索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoihuqfvu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shzxlz.cn/Article/details/gtexaqajfi.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gtzjjhvxbm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenlongwang.top/Article/details/gtrugkpvdw.html

[Q11] 一次插入多行
来源：http://dali.pengpengdd.cyou/Article/details/gtqgpvzpif.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.daria6918.cn/Article/details/gtesixiari.html

[Q12] 插入后取自增 ID
来源：http://dali.andypj.xyz/Article/details/gtqwuuzvgh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tianlin.xyz/Article/details/gtrvvaibau.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shzxlz.cn/Article/details/gtcyonsmgk.html

[Q13] 忽略重复插入
来源：http://dali.aibaodan.cn/Article/details/gtfcnwdsyf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj20258888.top/Article/details/gtpqdoyqhi.html

[Q14] 存在则更新（upsert）
来源：http://dali.wangdashe.top/Article/details/gtfdiqbtyx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yueranfly.top/Article/details/gtezacacwj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xuetiantiany.cn/Article/details/gthfnxlhce.html

[Q15] 查询全部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhivfsrs.html

SELECT * FROM users;
来源：http://dali.meibo888.top/Article/details/gtrvhmzgci.html

[Q16] 查询指定列
来源：http://dali.hammf.cn/Article/details/gthcrmzawr.html

SELECT id, name FROM users;
来源：http://dali.hnqzz.top/Article/details/gtjfprbhhx.html

[Q17] 条件查询
来源：http://dali.havefunace.top/Article/details/gtbirtvdqo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cheryme.top/Article/details/gtmxtvghst.html

[Q18] 模糊匹配
来源：http://dali.shzxlz.cn/Article/details/gtnythtpji.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yueranfly.top/Article/details/gtigtqlpyu.html

[Q19] 范围查询
来源：http://dali.cqqwz.cn/Article/details/gtczpukvuf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ivvv.top/Article/details/gtvtwvtqui.html

[Q20] IN 列表
来源：http://dali.ybcxt.top/Article/details/gtkcaspych.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinqigfzy.top/Article/details/gtgnczvnkz.html

[Q21] 空值判断
来源：http://dali.bjfxy.top/Article/details/gtmvedpzox.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.fzhhl.top/Article/details/gtofddoygk.html

[Q22] 排序
来源：http://dali.gzhubu.top/Article/details/gtemblsmff.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.tian-w.cn/Article/details/gtzkvwsrkq.html

[Q23] 分页
来源：http://dali.gzhubu.top/Article/details/gtlkampewk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zycfv.cn/Article/details/gthtgnggco.html

[Q24] 去重
来源：http://dali.jlsjyb.cn/Article/details/gtrvdhbibq.html

SELECT DISTINCT city FROM users;
来源：http://dali.sysykeji.top/Article/details/gtoyqzznqk.html

[Q25] 只取前 N 条
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsmeimttc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.snrcjt.cn/Article/details/gtmfyuwxhd.html

[Q26] 计数
来源：http://dali.zhoulong.xyz/Article/details/gthsrecrxi.html

SELECT COUNT(*) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtqptzswpp.html

[Q27] 条件计数
来源：http://dali.yangfankeji.com/Article/details/gtpzixszts.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtadxyprln.html

[Q28] 求和与平均
来源：http://dali.yuxming.cn/Article/details/gtdwkreblq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtkiendkpb.html

[Q29] 最大最小值
来源：http://dali.pengpengdd.cyou/Article/details/gtreafgsvh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtycrjtooi.html

[Q30] 分组统计
来源：http://dali.hysaishi.cn/Article/details/gtazwpdrri.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gttjqhanax.html

[Q31] 分组后过滤
来源：http://dali.sufxvd.cn/Article/details/gtalfpnonh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xylfe.cn/Article/details/gtsueptktj.html

[Q32] 分组拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtbhkizqnx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tanke756.top/Article/details/gtzyzpkprn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gaohongyu789.top/Article/details/gtntuwygus.html

[Q33] 多列分组
来源：http://dali.meibo888.top/Article/details/gtwdqdyigy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.feifeiyinyue.top/Article/details/gtkjxvlcdy.html

[Q34] 每组取第一条
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwoogurpe.html

SELECT * FROM (
来源：http://dali.xuanzx.com/Article/details/gtmqnxepzv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ppjwa.cn/Article/details/gtshupyync.html

) t WHERE rn = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtjszyrwfe.html

[Q35] 内连接
来源：http://dali.jianghu66.top/Article/details/gtedpzyabu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ybcxt.top/Article/details/gtvgyvzocf.html


<!-- 参考信息 -->