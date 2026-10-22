代发 wailian999

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.c1oappe.top/Article/details/gtubqivtjk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yueranfly.top/Article/details/gtiusrgtod.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjohvbslx.html

[N04] 斐波那契数列
来源：http://dali.gzhubu.top/Article/details/gtkoyfxeic.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gtsnbfwvso.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyriehrrg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtvouhbtdg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnyaauixy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xuanzx.com/Article/details/gtgvflegqv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gtrjvhnnvy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yuxming.cn/Article/details/gtzvhfcpun.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gtozyblsmb.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gtnoamqpqf.html

Py:   math.gcd(a, b)
来源：http://dali.meibo888.top/Article/details/gtffmudtro.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yueranfly.top/Article/details/gtcnvxaiyy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guannengcc.top/Article/details/gtnyzojdsm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cdnleiting.top/Article/details/gtnqxeithp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.bjfxy.top/Article/details/gtriluwxpz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhengqikj.top/Article/details/gtxjelbptp.html

Ruby: a.gcd(b)
来源：http://dali.zycfv.cn/Article/details/gtskfenqau.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenlongwang.top/Article/details/gtlgnactpy.html

[N06] 判断回文字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtjiyxqzrb.html

Py:   s == s[::-1]
来源：http://dali.gogol.net.cn/Article/details/gtiqipjwhs.html

PHP:  $s === strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gtkpudvbza.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtlzfmgojf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtebljrjeg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.dianchejie.cn/Article/details/gtisxrtpyw.html

Go:   // 双指针从两端比较
来源：http://dali.ivvv.top/Article/details/gtcnehwjty.html

Ruby: s == s.reverse
来源：http://dali.xuanzx.com/Article/details/gtfsmoxizo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.wangdashe.top/Article/details/gtfhtuggly.html

[N07] 两数之和（返回下标）
来源：http://dali.yongpay.top/Article/details/gtkbtruloa.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhongyouzk.top/Article/details/gtuugajifo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.quarkkingdee.top/Article/details/gtjzlkjpbn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.quarkkingdee.top/Article/details/gtjcbtgxxs.html

TS:   // 手写 Map<string, number>
来源：http://dali.meibo888.top/Article/details/gtgobsywlk.html

Java: // 手写 HashMap
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhoyobzz.html

Go:   // 手写 map[int]int
来源：http://dali.zdqjudy.top/Article/details/gteijqohpi.html

Ruby: // 手写 Hash
来源：http://dali.yj20258.top/Article/details/gtkiroiyih.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxyxnrwpc.html

[N08] 生成全排列
来源：http://dali.xuanzx.com/Article/details/gtqklhwlor.html

Py:   itertools.permutations(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gteqpekzgw.html

PHP:  // 手写递归交换
来源：http://dali.xziqi.cn/Article/details/gttxlffmpi.html

JS:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gttcnrdlan.html

TS:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtmrpngywk.html

Java: // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjhsmkpy.html

Go:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtuhzuqqit.html

Ruby: arr.permutation.to_a
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkvwmwpai.html

C#:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtlhtxkuxh.html

[N09] 栈与队列
来源：http://dali.xuanzx.com/Article/details/gtjpzcjqcu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhixingplan.top/Article/details/gtivtwzrqm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gzhubu.top/Article/details/gthrlhjnqv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gtbtqcatnp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ydzc1.top/Article/details/gthbnprxfg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xuetiantiany.cn/Article/details/gtwztpbadf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shzxlz.cn/Article/details/gtdouekwml.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.daria6918.cn/Article/details/gtdbglmmie.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ppjwa.cn/Article/details/gtngzeohui.html

[N10] 链表节点定义
来源：http://dali.xuanzx.com/Article/details/gtdsvjbeie.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.meibo888.top/Article/details/gtwdaeupew.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenlongwang.top/Article/details/gtvlmlspnz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.meibo888.top/Article/details/gtrqouqjpk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cdnleiting.top/Article/details/gtbqvxcedu.html

Java: class Node { int v; Node next; }
来源：http://dali.jiagoushi.top/Article/details/gtixyiquuc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.0kj1m.cn/Article/details/gtyvgfldjh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ppjwa.cn/Article/details/gtnjnyyfiv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yueranfly.top/Article/details/gtwpviobhg.html

[N11] 二叉树中序遍历
来源：http://dali.316326.xyz/Article/details/gtipmrvxrd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xziqi.cn/Article/details/gtetcygwxc.html

PHP:  // 手写递归函数
来源：http://dali.sxryk.cn/Article/details/gthwgtvkam.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.c1oappe.top/Article/details/gtttgnesym.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.feifeiyinyue.top/Article/details/gtmepymzak.html

Java: // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gtqnmzxlvt.html

Go:   // 手写递归
来源：http://dali.guannengcc.top/Article/details/gtbisnstcj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenjidiqi.icu/Article/details/gtvdtocipg.html

C#:   // 手写递归
来源：http://dali.hnqzz.top/Article/details/gtjayujrde.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.pycfn.com/Article/details/gturqixyve.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.guannengcc.top/Article/details/gtoiokrhjr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj20258888.top/Article/details/gtmayivhzf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.quarkkingdee.top/Article/details/gtjmppahfo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jiagoushi.top/Article/details/gtcddydezx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinghuilouyu.cn/Article/details/gtnmwpxtrb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cqqwz.cn/Article/details/gtjzinwpri.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jqgfzy.top/Article/details/gtxhibdukn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dashuyun.cn/Article/details/gtoapkbtmi.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtgvgpyntw.html

O. 并发与异步
来源：http://dali.yangfankeji.com/Article/details/gtxeddnxld.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtgrmxccrc.html

[O01] 启动一个线程
来源：http://dali.shuidangran.top/Article/details/gtmkieztow.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.fengsongda.top/Article/details/gthjzthskp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hfpthk.cn/Article/details/gtsxdezbwc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gzhubu.top/Article/details/gtakqbydjh.html

TS:   // 同 JS
来源：http://dali.zhiwuduotai.top/Article/details/gtpjhfswqd.html

Java: new Thread(() -> f()).start()
来源：http://dali.svipenyu.cn/Article/details/gtussdcjub.html

Go:   go f()
来源：http://dali.redwolf501.top/Article/details/gtlxdwbxyj.html

Ruby: Thread.new { f }
来源：http://dali.daxiang520.top/Article/details/gtskeicjam.html

C#:   Task.Run(() => F());
来源：http://dali.jyoumei.cn/Article/details/gthpewcxoo.html

[O02] 使用线程池
来源：http://dali.sxryk.cn/Article/details/gtlgfaasow.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yuanzhike.top/Article/details/gthfuphuqn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.havefunace.top/Article/details/gtasakpgpo.html

JS:   // worker_threads 线程池
来源：http://dali.guowangkeji.top/Article/details/gtsuvpcpwn.html

TS:   // worker_threads 线程池
来源：http://dali.zhixingplan.top/Article/details/gtyehznpoj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shzxlz.cn/Article/details/gtdtgakddu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtssydlgly.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhixingplan.top/Article/details/gtufoylwtr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.svipenyu.cn/Article/details/gtsjkxgqtg.html

[O03] 加锁保护共享数据
来源：http://dali.fengsongda.top/Article/details/gtjlobreat.html

Py:   with lock: shared += 1
来源：http://dali.meibo888.top/Article/details/gticcmispu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.daria6918.cn/Article/details/gtfglqwosz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.316326.xyz/Article/details/gtyoxyrnwu.html

TS:   // 同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gttaaclocv.html

Java: synchronized (this) { shared++; }
来源：http://dali.yuxming.cn/Article/details/gtirfatvuy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xylfe.cn/Article/details/gturmxuoqe.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.smart0.xyz/Article/details/gtscxnvfnm.html

C#:   lock (gate) { shared++; }
来源：http://dali.hammf.cn/Article/details/gtakyruupr.html

[O04] 定义异步函数并等待
来源：http://dali.tianlin.xyz/Article/details/gtsrsbfslv.html

Py:   async def f():⏎    await g()
来源：http://dali.cqqwz.cn/Article/details/gtlpfefvax.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.9152youxi.cn/Article/details/gtwrbakauc.html

JS:   async function f() { await g(); }
来源：http://dali.hysaishi.cn/Article/details/gtlvzffqmu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.quarkkingdee.top/Article/details/gtavbiahpo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.bjfxy.top/Article/details/gtzrlnfusz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.quarkkingdee.top/Article/details/gtvpilqrle.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gtdipxwhct.html

C#:   async Task F() { await G(); }
来源：http://dali.tanke756.top/Article/details/gtutupvtdo.html

[O05] 并发执行并等待全部完成
来源：http://dali.smart0.xyz/Article/details/gtelzwsnxm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cashguo.top/Article/details/gthosehbao.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nanxinkj.top/Article/details/gtwqysjipm.html

JS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gtauldruww.html

TS:   await Promise.all(tasks)
来源：http://dali.ppjwa.cn/Article/details/gtzzgzpzvc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.vqdsnc.cn/Article/details/gtdeansdbm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.wangshuangyany.cn/Article/details/gtasdeyxye.html

Ruby: threads.map(&:join)
来源：http://dali.hnxiangtu.top/Article/details/gtlrezrtzz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj202588.top/Article/details/gtlgsegivh.html

[O06] 使用进程池
来源：http://dali.ivvv.top/Article/details/gtkpzoarjh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinqigfzy.top/Article/details/gtcekbseqr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhongyouzk.top/Article/details/gtaebqrvkd.html

JS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbifqadnm.html

TS:   // child_process / cluster 模块
来源：http://dali.jinghuilouyu.cn/Article/details/gtfqbxdxss.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hnxiangtu.top/Article/details/gtiokbskse.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.andypj.xyz/Article/details/gttkcwocah.html

Ruby: // fork 块
来源：http://dali.hongshengwenyu.top/Article/details/gtksyzmikv.html

C#:   Parallel.For
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbnpwquwa.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtciwcqcun.html

P. 常用工具函数
来源：http://dali.zhengqikj.top/Article/details/gtoqgjgobw.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtfsqyyoyz.html

[P01] 生成 UUID
来源：http://dali.pengpengdd.cyou/Article/details/gteiyflazj.html

Py:   str(uuid.uuid4())
来源：http://dali.guannengcc.top/Article/details/gtragtnqbl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.svipenyu.cn/Article/details/gtjprrqpim.html

JS:   crypto.randomUUID()
来源：http://dali.bjfxy.top/Article/details/gtufryjmuv.html

TS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnyojuakj.html

Java: UUID.randomUUID().toString()
来源：http://dali.ybcxt.top/Article/details/gtxbkatozm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.vqdsnc.cn/Article/details/gtfpptzvrg.html

Ruby: SecureRandom.uuid
来源：http://dali.daxiang520.top/Article/details/gtxacjiqlf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.haohaochexian.top/Article/details/gtfqtfwmht.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhiwuduotai.top/Article/details/gtpvegqmaa.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cashguo.top/Article/details/gtkppqghli.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.svipenyu.cn/Article/details/gtjprivruc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gogol.net.cn/Article/details/gtzrbdckep.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.quarkkingdee.top/Article/details/gtojuudwog.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hammf.cn/Article/details/gteyudjqxm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.feifeiyinyue.top/Article/details/gtqqghkjlj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gotoacloud.top/Article/details/gtbsirudrk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xinyue.icu/Article/details/gtwlafynfc.html

[P03] 生成短随机字符串
来源：http://dali.yj202588.top/Article/details/gtlvcznmrx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zdqjudy.top/Article/details/gtgljrvqxx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.vqdsnc.cn/Article/details/gtlpefipyv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jiagoushi.top/Article/details/gtpzyfzivv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sysykeji.top/Article/details/gtsqidjaff.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hammf.cn/Article/details/gthqrrfnvw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhongyouzk.top/Article/details/gtbjitwfhy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hongshengwenyu.top/Article/details/gtchnnjrrn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.fengsongda.top/Article/details/gtqkiawssm.html

[P04] 求长度
来源：http://dali.sxryk.cn/Article/details/gtricqmtif.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.9152youxi.cn/Article/details/gtacwguyyo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sweek.top/Article/details/gtshgxbivl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.kuanghao11.cn/Article/details/gtmqdvlcuu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shangyingyoupin.top/Article/details/gtmeshxhgk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cdnleiting.top/Article/details/gtvfidrfyx.html

Go:   len(arr);  len(m)
来源：http://dali.jqgufenzy.top/Article/details/gtdmqilavg.html

Ruby: x.length;  x.size
来源：http://dali.chenzaomai.com/Article/details/gtkvcpjcfi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.c1oappe.top/Article/details/gtmrtkdqds.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhengqikj.top/Article/details/gtgnyadoak.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yuxming.cn/Article/details/gtrbxfjigw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.dashuyun.cn/Article/details/gtwufhczms.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hammf.cn/Article/details/gtynqtvtcv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gotoacloud.top/Article/details/gtcymgxmsa.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ydzc1.top/Article/details/gtgasncbim.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shangyingyoupin.top/Article/details/gtfecfpewf.html

Ruby: a == b
来源：http://dali.hnxiangtu.top/Article/details/gtpqdfklmh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shuidangran.top/Article/details/gtvkyktglk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yueranfly.top/Article/details/gtlncmyfwb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.redwolf501.top/Article/details/gtzzkbmwwx.html

PHP:  if (empty($x)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtwgzesqws.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.guowangkeji.top/Article/details/gtplfnxhni.html

TS:   if (x == null) {}
来源：http://dali.yj20258888.top/Article/details/gteowlrauw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.aizwys.cn/Article/details/gtcbklkike.html

Go:   if x == nil {}
来源：http://dali.zdqjudy.top/Article/details/gtcrtklayh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cheryme.top/Article/details/gttqxtsnlv.html

C#:   if (x is null) {}
来源：http://dali.nwbrower.top/Article/details/gtblbsstzt.html

[P07] 防抖与节流
来源：http://dali.yj202588.top/Article/details/gtjqkslxjl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jqgufenzy.top/Article/details/gtmassakoc.html

PHP:  // 手写时间戳比较
来源：http://dali.aizwys.cn/Article/details/gtsymqifgt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gtwoapufug.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gtlzwzahvn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nwbrower.top/Article/details/gtllpnxntg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.dashuyun.cn/Article/details/gtmcmidbyr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtheiauhzw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.dianchejie.cn/Article/details/gtqoscslcq.html

[P08] 处理浮点精度问题
来源：http://dali.xylfe.cn/Article/details/gtsthockft.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj20258.top/Article/details/gtyvjxyzud.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hnxiangtu.top/Article/details/gtibuwutoa.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xziqi.cn/Article/details/gthveblduq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.316326.xyz/Article/details/gtlvzyuxce.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.mhx1999.top/Article/details/gttayauigf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gtwkyxjhyy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gzhubu.top/Article/details/gtvjfarfji.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jyoumei.cn/Article/details/gtzeydmqrl.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtzcnoiees.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cashguo.top/Article/details/gtdvzqgbqu.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtejxyxhyg.html

[Q01] 创建表
来源：http://dali.hfpthk.cn/Article/details/gtcruanyxt.html

CREATE TABLE users (
来源：http://dali.redwolf501.top/Article/details/gtjcqxtisq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ehwqpu.com/Article/details/gtlwrlzele.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yanxiufei.cn/Article/details/gtfgbzeuxo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nanxuanxn.top/Article/details/gtledeyixo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.snrcjt.cn/Article/details/gttmwramjr.html

);
来源：http://dali.nanxuanxn.top/Article/details/gtvlklmyph.html

[Q02] 创建带外键的表
来源：http://dali.pycfn.com/Article/details/gtrsokvzjn.html

CREATE TABLE orders (
来源：http://dali.yuxming.cn/Article/details/gtfzanxgua.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhongyouzk.top/Article/details/gtrsxzqjnl.html

user_id INT NOT NULL,
来源：http://dali.zhixingplan.top/Article/details/gtwmpidevd.html

amount DECIMAL(10, 2),
来源：http://dali.sysykeji.top/Article/details/gtpgcjopgb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.daria6918.cn/Article/details/gtnbprkvcj.html

);
来源：http://dali.meibo888.top/Article/details/gtehramyvp.html

[Q03] 增加列
来源：http://dali.aizwys.cn/Article/details/gtwslwfudq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenzaomai.com/Article/details/gtklprsbdz.html

[Q04] 修改列类型
来源：http://dali.jianghu66.top/Article/details/gtladubigd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cucudq.cn/Article/details/gtnzojyrgj.html

[Q05] 重命名列
来源：http://dali.xuanzx.com/Article/details/gttxbgxuty.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttkqznaxy.html

[Q06] 删除列
来源：http://dali.ehwqpu.com/Article/details/gtpltkkjpn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.guowangkeji.top/Article/details/gtyumejgpm.html

[Q07] 删除表
来源：http://dali.cucudq.cn/Article/details/gtblvewqvp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.guannengcc.top/Article/details/gtgvorvgwj.html

[Q08] 创建普通索引
来源：http://dali.cqqwz.cn/Article/details/gtsotkkepr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.wangshuangyany.cn/Article/details/gttpcmrtlw.html

[Q09] 创建唯一索引
来源：http://dali.ydzc1.top/Article/details/gtkavjipqo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xinyue.icu/Article/details/gtnbkxddgi.html

[Q10] 插入单行
来源：http://dali.chenzaomai.com/Article/details/gtrywodnmt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoyxyplyt.html

[Q11] 一次插入多行
来源：http://dali.tianlin.xyz/Article/details/gtzgbpttxq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj20258888.top/Article/details/gtaimgykoh.html

[Q12] 插入后取自增 ID
来源：http://dali.nanxinkj.top/Article/details/gtcmxovhvz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.9152youxi.cn/Article/details/gtnpydsvwc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shanyushiyangtech.top/Article/details/gtmqgtebro.html

[Q13] 忽略重复插入
来源：http://dali.yongpay.top/Article/details/gtqhfjjerp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.guowangkeji.top/Article/details/gtrtnhxvcr.html

[Q14] 存在则更新（upsert）
来源：http://dali.tian-w.cn/Article/details/gtnnonixde.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hnqzz.top/Article/details/gtsrhlxqgp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cashguo.top/Article/details/gtrayhmani.html

[Q15] 查询全部
来源：http://dali.yonumen.top/Article/details/gtpwiahnet.html

SELECT * FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gteybxviub.html

[Q16] 查询指定列
来源：http://dali.nanxinkj.top/Article/details/gtyegcwzqz.html

SELECT id, name FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtorhgfltc.html

[Q17] 条件查询
来源：http://dali.feifeiyinyue.top/Article/details/gtoknkraeh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.bjfxy.top/Article/details/gtscntpyfe.html

[Q18] 模糊匹配
来源：http://dali.nanxuanxn.top/Article/details/gtndmsbxqb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.feifeiyinyue.top/Article/details/gtputnikor.html

[Q19] 范围查询
来源：http://dali.mhx1999.top/Article/details/gtimznozkh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gzhubu.top/Article/details/gtzcyaczck.html

[Q20] IN 列表
来源：http://dali.zycfv.cn/Article/details/gtzvwuhwyu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbupkpgft.html

[Q21] 空值判断
来源：http://dali.hammf.cn/Article/details/gtzyrvlnua.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cashguo.top/Article/details/gtlbpdnmwb.html

[Q22] 排序
来源：http://dali.jlsjyb.cn/Article/details/gtjejtbcum.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.vqdsnc.cn/Article/details/gtlguyyahv.html

[Q23] 分页
来源：http://dali.nanxuanxn.top/Article/details/gtqkqfhphg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.snrcjt.cn/Article/details/gtrpmlcsmw.html

[Q24] 去重
来源：http://dali.guannengcc.top/Article/details/gtmlezkxwc.html

SELECT DISTINCT city FROM users;
来源：http://dali.yonumen.top/Article/details/gtdrjqbdpg.html

[Q25] 只取前 N 条
来源：http://dali.tian-w.cn/Article/details/gtkmgjpjvf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhbyhrqj.html

[Q26] 计数
来源：http://dali.nwbrower.top/Article/details/gtncjgzonm.html

SELECT COUNT(*) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtsmawqwrv.html

[Q27] 条件计数
来源：http://dali.tanke756.top/Article/details/gtaofqnrvy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.daxiang520.top/Article/details/gtidvjtwuc.html

[Q28] 求和与平均
来源：http://dali.gogol.net.cn/Article/details/gthzrrkznw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtzvaaseiq.html

[Q29] 最大最小值
来源：http://dali.nanxinkj.top/Article/details/gtlxguzual.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtnfcefwsh.html

[Q30] 分组统计
来源：http://dali.smart0.xyz/Article/details/gterwzikad.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gtauddflom.html

[Q31] 分组后过滤
来源：http://dali.shzxlz.cn/Article/details/gtlvpcbdpm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.quarkkingdee.top/Article/details/gttmuulwuz.html

[Q32] 分组拼接字符串
来源：http://dali.jianghu66.top/Article/details/gtajubgddk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ydzc1.top/Article/details/gtuvcakipo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yuxming.cn/Article/details/gtejujncbv.html

[Q33] 多列分组
来源：http://dali.bjfxy.top/Article/details/gtbdtfxyft.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.aibaodan.cn/Article/details/gtrcysdlao.html

[Q34] 每组取第一条
来源：http://dali.xuetiantiany.cn/Article/details/gteorfqnji.html

SELECT * FROM (
来源：http://dali.yuxming.cn/Article/details/gtlrwexkdt.html


<!-- 参考信息 -->