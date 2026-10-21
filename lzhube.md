代发 wailian999

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hysaishi.cn/Article/details/gtbtwcabvo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.vqdsnc.cn/Article/details/gtmnzrazqd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sufxvd.cn/Article/details/gtenrppcjr.html

[N04] 斐波那契数列
来源：http://dali.ppjwa.cn/Article/details/gtlejnnlwl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gotoacloud.top/Article/details/gtgaucrrod.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hywenlv.cn/Article/details/gtcqnmdbld.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gtwhxxwgtf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gtamzwince.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlptoecpx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yonumen.top/Article/details/gtaljcbzsn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.svipenyu.cn/Article/details/gtafbmcdtq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gtxrfdgyjx.html

[N05] 最大公约数
来源：http://dali.xziqi.cn/Article/details/gtjwvwzhmz.html

Py:   math.gcd(a, b)
来源：http://dali.sysykeji.top/Article/details/gtzrieolao.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gthzmtcvfd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gtpztuzjkw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gtqfzojaku.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenjidiqi.icu/Article/details/gtpoimgrbi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ehwqpu.com/Article/details/gtnkytuvhq.html

Ruby: a.gcd(b)
来源：http://dali.daxiang520.top/Article/details/gtxwujgzrq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jianghu66.top/Article/details/gthcworfwm.html

[N06] 判断回文字符串
来源：http://dali.yuanzhike.top/Article/details/gtzptnlsjn.html

Py:   s == s[::-1]
来源：http://dali.shuidangran.top/Article/details/gtsysdfpcj.html

PHP:  $s === strrev($s);
来源：http://dali.jqgufenzy.top/Article/details/gtesjlusiz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtltwtldfc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtamumqcyb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhixingplan.top/Article/details/gtnswhbsoj.html

Go:   // 双指针从两端比较
来源：http://dali.wangshuangyany.cn/Article/details/gtujkvxktn.html

Ruby: s == s.reverse
来源：http://dali.ybcxt.top/Article/details/gtzsulpxbe.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hfpthk.cn/Article/details/gtplugqhez.html

[N07] 两数之和（返回下标）
来源：http://dali.yj20258.top/Article/details/gtqmvtjzby.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.smart0.xyz/Article/details/gtriishkou.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhongyouzk.top/Article/details/gtlbnshwbe.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ehwqpu.com/Article/details/gtpceicmzi.html

TS:   // 手写 Map<string, number>
来源：http://dali.xylfe.cn/Article/details/gtayfbkrhw.html

Java: // 手写 HashMap
来源：http://dali.havefunace.top/Article/details/gtnnfygfwa.html

Go:   // 手写 map[int]int
来源：http://dali.nwbrower.top/Article/details/gtuqywfadc.html

Ruby: // 手写 Hash
来源：http://dali.ybcxt.top/Article/details/gtuphmjwmh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ppjwa.cn/Article/details/gtoucwyxxh.html

[N08] 生成全排列
来源：http://dali.yangfankeji.com/Article/details/gtvmldrptn.html

Py:   itertools.permutations(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtlqmsluwp.html

PHP:  // 手写递归交换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtexzodazg.html

JS:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtiofrgsfp.html

TS:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtacavfyih.html

Java: // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtwnjxqjjp.html

Go:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gttxtizecw.html

Ruby: arr.permutation.to_a
来源：http://dali.shuidangran.top/Article/details/gtcusekcag.html

C#:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtqvttimoi.html

[N09] 栈与队列
来源：http://dali.gotoacloud.top/Article/details/gtpebrjenl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.aizwys.cn/Article/details/gtctnjhsbj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnqzz.top/Article/details/gtzetvhsvv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gttqokotfy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.fzhhl.top/Article/details/gthlmpgges.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.andypj.xyz/Article/details/gthnhcoazi.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ivvv.top/Article/details/gtaarsrjsz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj20258.top/Article/details/gttycksuna.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.daxiang520.top/Article/details/gtponxqkqg.html

[N10] 链表节点定义
来源：http://dali.ybcxt.top/Article/details/gtdqucczzc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hywenlv.cn/Article/details/gtioldcsgm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jiagoushi.top/Article/details/gtnfrsmwmh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.smart0.xyz/Article/details/gtrseixhby.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.aibaodan.cn/Article/details/gtcwdaesdl.html

Java: class Node { int v; Node next; }
来源：http://dali.cqqwz.cn/Article/details/gttozbfbcq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hammf.cn/Article/details/gtlnzcattf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hnxiangtu.top/Article/details/gtiydquhzi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hammf.cn/Article/details/gtpwzmhnox.html

[N11] 二叉树中序遍历
来源：http://dali.dashuyun.cn/Article/details/gtnwszaper.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yangfankeji.com/Article/details/gtazmogxut.html

PHP:  // 手写递归函数
来源：http://dali.yanxiufei.cn/Article/details/gtiigrghos.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.redwolf501.top/Article/details/gtekpooges.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.haohaochexian.top/Article/details/gtdmulvphm.html

Java: // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gtsulwlybm.html

Go:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gtiljuasex.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tian-w.cn/Article/details/gtlekyxjdr.html

C#:   // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gttlkjrcrl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yuanzhike.top/Article/details/gtlcuqprwu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.guowangkeji.top/Article/details/gtztfjwljc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sweek.top/Article/details/gtfpapjaoo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgfzy.top/Article/details/gtwsnlsonu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shuidangran.top/Article/details/gthzpabxmg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shzxlz.cn/Article/details/gtebgffzrz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gotoacloud.top/Article/details/gtbzmpysti.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhixingplan.top/Article/details/gtxrwemdlj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sweek.top/Article/details/gtilbzyqnj.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtvyzvwgjr.html

O. 并发与异步
来源：http://dali.ppjwa.cn/Article/details/gtnujbdaps.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtaqrjwrxo.html

[O01] 启动一个线程
来源：http://dali.yuxming.cn/Article/details/gtttoxmain.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hammf.cn/Article/details/gtipelfqyi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmedljdp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.wangdashe.top/Article/details/gtwacvesat.html

TS:   // 同 JS
来源：http://dali.nanxinkj.top/Article/details/gtygbsunqs.html

Java: new Thread(() -> f()).start()
来源：http://dali.tianlin.xyz/Article/details/gtkwuafryy.html

Go:   go f()
来源：http://dali.xinyue.icu/Article/details/gtuhvggtzs.html

Ruby: Thread.new { f }
来源：http://dali.smart0.xyz/Article/details/gtprkrbhtd.html

C#:   Task.Run(() => F());
来源：http://dali.c1oappe.top/Article/details/gtsncbxwws.html

[O02] 使用线程池
来源：http://dali.svipenyu.cn/Article/details/gttuygeerp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yuanzhike.top/Article/details/gtsntnlnce.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ivvv.top/Article/details/gtksvvskwa.html

JS:   // worker_threads 线程池
来源：http://dali.haohaochexian.top/Article/details/gtvzwdjyxl.html

TS:   // worker_threads 线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnndhalst.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ppjwa.cn/Article/details/gtllsbvupy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jianghu66.top/Article/details/gtlhzjcufw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xuetiantiany.cn/Article/details/gtgtaohecw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cdnleiting.top/Article/details/gtrvirfwfn.html

[O03] 加锁保护共享数据
来源：http://dali.jianghu66.top/Article/details/gtnuswksov.html

Py:   with lock: shared += 1
来源：http://dali.tanke756.top/Article/details/gtdunvrzha.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hfpthk.cn/Article/details/gtdldokgkf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.dianchejie.cn/Article/details/gttnugkszs.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gtcoaiqhfl.html

Java: synchronized (this) { shared++; }
来源：http://dali.quarkkingdee.top/Article/details/gtpfgxqqxj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.quarkkingdee.top/Article/details/gtbvujzmbo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.feifeiyinyue.top/Article/details/gtflcqjqbb.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqqnzyxo.html

[O04] 定义异步函数并等待
来源：http://dali.hysaishi.cn/Article/details/gtcshkikuy.html

Py:   async def f():⏎    await g()
来源：http://dali.haohaochexian.top/Article/details/gtohcaohid.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj20258.top/Article/details/gtzjjmwpvw.html

JS:   async function f() { await g(); }
来源：http://dali.ydzc1.top/Article/details/gtqrzugxgw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gtrbnidxem.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yuanzhike.top/Article/details/gtrqcasggj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.haohaochexian.top/Article/details/gtlqjlqmfh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmzywfrck.html

C#:   async Task F() { await G(); }
来源：http://dali.sysykeji.top/Article/details/gtiyaiojaj.html

[O05] 并发执行并等待全部完成
来源：http://dali.jqgfzy.top/Article/details/gtcfvzvwvi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.smart0.xyz/Article/details/gtvxxflebp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.smart0.xyz/Article/details/gtdkinxbuv.html

JS:   await Promise.all(tasks)
来源：http://dali.yj20258888.top/Article/details/gtvieujwlg.html

TS:   await Promise.all(tasks)
来源：http://dali.svipenyu.cn/Article/details/gtbdmpquuf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsabgcxlv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.dianchejie.cn/Article/details/gtaasbjqxl.html

Ruby: threads.map(&:join)
来源：http://dali.dashuyun.cn/Article/details/gtofclloih.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cucudq.cn/Article/details/gtdhodttse.html

[O06] 使用进程池
来源：http://dali.gotoacloud.top/Article/details/gtvvujwkmt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gogol.net.cn/Article/details/gturdeipuc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hnqzz.top/Article/details/gtwmqukxng.html

JS:   // child_process / cluster 模块
来源：http://dali.dianchejie.cn/Article/details/gtjjujoncf.html

TS:   // child_process / cluster 模块
来源：http://dali.yj202588.top/Article/details/gtwoadzceq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.aibaodan.cn/Article/details/gtitobsgxe.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.quarkkingdee.top/Article/details/gteirwinas.html

Ruby: // fork 块
来源：http://dali.chenjidiqi.icu/Article/details/gtrfeavvww.html

C#:   Parallel.For
来源：http://dali.haohaochexian.top/Article/details/gtnkxvzfxh.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtqinsdqvl.html

P. 常用工具函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxsnygnc.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtdlcgaknf.html

[P01] 生成 UUID
来源：http://dali.nanxinkj.top/Article/details/gtafmvexfl.html

Py:   str(uuid.uuid4())
来源：http://dali.daria6918.cn/Article/details/gtzgzrdzun.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.andypj.xyz/Article/details/gtfsnzfjor.html

JS:   crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gthmfwhebe.html

TS:   crypto.randomUUID()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtppgnbxtd.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhiwuduotai.top/Article/details/gtsfxyykmm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sxryk.cn/Article/details/gtomogudlr.html

Ruby: SecureRandom.uuid
来源：http://dali.yj20258888.top/Article/details/gtmpiqmlij.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukphvhxs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yangfankeji.com/Article/details/gtxugliuhg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yueranfly.top/Article/details/gtksydkwar.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj202588.top/Article/details/gtppcupwhg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jiagoushi.top/Article/details/gtoxjtehnm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jianghu66.top/Article/details/gtsxjiakgg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmrfitxrw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmdacztos.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.wangdashe.top/Article/details/gtwjvaveqr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hongshengwenyu.top/Article/details/gtzmuqjjff.html

[P03] 生成短随机字符串
来源：http://dali.tanke756.top/Article/details/gthkhlgjax.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ehwqpu.com/Article/details/gttevgdgsa.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhongyouzk.top/Article/details/gtjhpoqzhw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnxiangtu.top/Article/details/gtcfhusokl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jlsjyb.cn/Article/details/gtfyvknkmo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cashguo.top/Article/details/gtowgxwfon.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.tian-w.cn/Article/details/gtbnxlakio.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.meibo888.top/Article/details/gttviprnpx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.mhx1999.top/Article/details/gtidoghpav.html

[P04] 求长度
来源：http://dali.bjfxy.top/Article/details/gtcdumfpbp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zycfv.cn/Article/details/gtgyiucsfq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtltiuskfi.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.316326.xyz/Article/details/gtfkzvxgrq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.c1oappe.top/Article/details/gtzmgsfcrb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ivvv.top/Article/details/gtseutcrbu.html

Go:   len(arr);  len(m)
来源：http://dali.tianlin.xyz/Article/details/gtslypiacr.html

Ruby: x.length;  x.size
来源：http://dali.jlsjyb.cn/Article/details/gtwdexxloh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jiagoushi.top/Article/details/gtwpxbpmpq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ppjwa.cn/Article/details/gtkvpqubvj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.iojbl.cn/Article/details/gtbwkiapuj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.birdmap.top/Article/details/gtbssnihce.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ppjwa.cn/Article/details/gthgdbbnux.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ybcxt.top/Article/details/gtebaemejt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shangyingyoupin.top/Article/details/gtehlllyvp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hnxiangtu.top/Article/details/gturftpzni.html

Ruby: a == b
来源：http://dali.sxryk.cn/Article/details/gtieozkqjo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gotoacloud.top/Article/details/gtekksjztk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.redwolf501.top/Article/details/gtobhswwht.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jlsjyb.cn/Article/details/gttvwlbjpg.html

PHP:  if (empty($x)) {}
来源：http://dali.yvedp.cn/Article/details/gtdjhoatto.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmnobcecb.html

TS:   if (x == null) {}
来源：http://dali.shzxlz.cn/Article/details/gtalypuztl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gaohongyu789.top/Article/details/gtzjrdoomq.html

Go:   if x == nil {}
来源：http://dali.shuidangran.top/Article/details/gtetdgvyvk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cucudq.cn/Article/details/gtthgaakik.html

C#:   if (x is null) {}
来源：http://dali.yuanzhike.top/Article/details/gtoehomzrm.html

[P07] 防抖与节流
来源：http://dali.redwolf501.top/Article/details/gtqwckydmg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.feifeiyinyue.top/Article/details/gtcnqzzvpk.html

PHP:  // 手写时间戳比较
来源：http://dali.quarkkingdee.top/Article/details/gtkuhfevwj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ivvv.top/Article/details/gttuoattty.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangshuangyany.cn/Article/details/gtuaeokequ.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gtoduqadwb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yuxming.cn/Article/details/gtlwxyxikk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hammf.cn/Article/details/gtuffvbtvg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gaohongyu789.top/Article/details/gtpdyyqgzr.html

[P08] 处理浮点精度问题
来源：http://dali.hongshengwenyu.top/Article/details/gtwtmcpkel.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.nwbrower.top/Article/details/gtbzztvkot.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj20258.top/Article/details/gtltepyvkn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cheryme.top/Article/details/gtyajoufbw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yvedp.cn/Article/details/gtsusvhyhw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cucudq.cn/Article/details/gtvlqzxeee.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nwbrower.top/Article/details/gtahgvlpev.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.smart0.xyz/Article/details/gtrytirajt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.daria6918.cn/Article/details/gttzxlegqp.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtmysklyrw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sweek.top/Article/details/gtnrbmcztv.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtqvscphtd.html

[Q01] 创建表
来源：http://dali.meibo888.top/Article/details/gtndzvvxvr.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gtictlyhtu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgfzy.top/Article/details/gtwgnakfol.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jyoumei.cn/Article/details/gtkqscyypc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhixingplan.top/Article/details/gttnycujdu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.snrcjt.cn/Article/details/gtphxrjpko.html

);
来源：http://dali.cucudq.cn/Article/details/gtardvpewt.html

[Q02] 创建带外键的表
来源：http://dali.wangdashe.top/Article/details/gtavhaeqlj.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gtztmaccql.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.c1oappe.top/Article/details/gthiyjghec.html

user_id INT NOT NULL,
来源：http://dali.ppjwa.cn/Article/details/gtxpadhvbn.html

amount DECIMAL(10, 2),
来源：http://dali.tianlin.xyz/Article/details/gtjsyloaby.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tian-w.cn/Article/details/gtiayekkun.html

);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtasmqgvvd.html

[Q03] 增加列
来源：http://dali.yuxming.cn/Article/details/gtxaqddqjo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ivvv.top/Article/details/gtezmevhsf.html

[Q04] 修改列类型
来源：http://dali.pycfn.com/Article/details/gtvjbtlscl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sysykeji.top/Article/details/gtmmfpbstw.html

[Q05] 重命名列
来源：http://dali.ivvv.top/Article/details/gtnuhzucma.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.nanxuanxn.top/Article/details/gtbagbozxa.html

[Q06] 删除列
来源：http://dali.meibo888.top/Article/details/gtbyrorykg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jqgufenzy.top/Article/details/gtwcnxljdi.html

[Q07] 删除表
来源：http://dali.yvedp.cn/Article/details/gtkbnjhldu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtyxuyacce.html

[Q08] 创建普通索引
来源：http://dali.hnxiangtu.top/Article/details/gtokkvqulq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jyoumei.cn/Article/details/gtxjfnqfwb.html

[Q09] 创建唯一索引
来源：http://dali.bjfxy.top/Article/details/gtovupnvvn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hongshengwenyu.top/Article/details/gthnbdakvn.html

[Q10] 插入单行
来源：http://dali.yuanzhike.top/Article/details/gtfzjuhavr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yuxming.cn/Article/details/gtdtbyglpu.html

[Q11] 一次插入多行
来源：http://dali.cheryme.top/Article/details/gttqjaewxg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jyoumei.cn/Article/details/gtopthnhdt.html

[Q12] 插入后取自增 ID
来源：http://dali.xuanzx.com/Article/details/gtksyvrmuq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sweek.top/Article/details/gtlafetgxy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqueskoj.html

[Q13] 忽略重复插入
来源：http://dali.sxryk.cn/Article/details/gtjxrgcfbu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.feifeiyinyue.top/Article/details/gtfnbtpyvl.html

[Q14] 存在则更新（upsert）
来源：http://dali.svipenyu.cn/Article/details/gtfonuqrxa.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.svipenyu.cn/Article/details/gtamexhjtm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yonumen.top/Article/details/gtcdmmwrxg.html

[Q15] 查询全部
来源：http://dali.zycfv.cn/Article/details/gtifjiubvh.html

SELECT * FROM users;
来源：http://dali.yj202588.top/Article/details/gtiotqgsvl.html

[Q16] 查询指定列
来源：http://dali.jqgfzy.top/Article/details/gtcbzjvtvd.html

SELECT id, name FROM users;
来源：http://dali.yueranfly.top/Article/details/gttjajbabo.html

[Q17] 条件查询
来源：http://dali.guannengcc.top/Article/details/gtmcgukuan.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbxqjbje.html

[Q18] 模糊匹配
来源：http://dali.tianlin.xyz/Article/details/gtlklzsrtx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jqgfzy.top/Article/details/gtlbtvaitb.html

[Q19] 范围查询
来源：http://dali.daria6918.cn/Article/details/gtytxuqavy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.aibaodan.cn/Article/details/gtwqgnbwmp.html

[Q20] IN 列表
来源：http://dali.haohaochexian.top/Article/details/gtdiccezxa.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xuanzx.com/Article/details/gtludiunqg.html

[Q21] 空值判断
来源：http://dali.sysykeji.top/Article/details/gthntgitku.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cdnleiting.top/Article/details/gtgihonrfa.html

[Q22] 排序
来源：http://dali.pycfn.com/Article/details/gttyxrisbz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shangyingyoupin.top/Article/details/gtbkofjgok.html

[Q23] 分页
来源：http://dali.jinqigfzy.top/Article/details/gtjsiijzzf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhengqikj.top/Article/details/gtrolomqre.html

[Q24] 去重
来源：http://dali.zhixingplan.top/Article/details/gttzbskamv.html

SELECT DISTINCT city FROM users;
来源：http://dali.redwolf501.top/Article/details/gthwfvveit.html

[Q25] 只取前 N 条
来源：http://dali.nwbrower.top/Article/details/gtnzpamhjd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenzaomai.com/Article/details/gtwrwexdnh.html

[Q26] 计数
来源：http://dali.chenzaomai.com/Article/details/gtscpuinys.html

SELECT COUNT(*) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtdwhionxl.html

[Q27] 条件计数
来源：http://dali.shangyingyoupin.top/Article/details/gtpgxyysgo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtxbiekjkv.html

[Q28] 求和与平均
来源：http://dali.daxiang520.top/Article/details/gtnshmhzmg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtlsvxdovv.html

[Q29] 最大最小值
来源：http://dali.cashguo.top/Article/details/gtcncqrwsn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtuedjxpoe.html

[Q30] 分组统计
来源：http://dali.havefunace.top/Article/details/gtusnsykzc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkjuvhqcy.html

[Q31] 分组后过滤
来源：http://dali.c1oappe.top/Article/details/gtabcybnuv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sxryk.cn/Article/details/gtttytlbhr.html

[Q32] 分组拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gtncddbpml.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gtfsejgcrf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.9152youxi.cn/Article/details/gtlquvbvzq.html

[Q33] 多列分组
来源：http://dali.yueranfly.top/Article/details/gtxeicejtr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xuetiantiany.cn/Article/details/gtvywaylmx.html

[Q34] 每组取第一条
来源：http://dali.snrcjt.cn/Article/details/gtxffdodjv.html

SELECT * FROM (
来源：http://dali.sysykeji.top/Article/details/gtrpzkcdbv.html


<!-- 参考信息 -->