代发 wailian999

Ruby: arr.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwzctpluc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj20258.top/Article/details/gtsgttmzmn.html

[N03] 快速排序（分治示例）
来源：http://dali.zhiwuduotai.top/Article/details/gtsozwdxye.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ehwqpu.com/Article/details/gtkdamvyqe.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jiagoushi.top/Article/details/gtonuaozfu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yanxiufei.cn/Article/details/gtcwjfthyf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.andypj.xyz/Article/details/gtjnmvekhg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhongyouzk.top/Article/details/gtenonemww.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258888.top/Article/details/gtugacwnzm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.pengpengdd.cyou/Article/details/gtwojyuqof.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gthfohsmjc.html

[N04] 斐波那契数列
来源：http://dali.quarkkingdee.top/Article/details/gtldinmqqe.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhixingplan.top/Article/details/gtqgbgrkfa.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nanxinkj.top/Article/details/gttomhwpwq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gtunnxeqzl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtjyinxuqz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shzxlz.cn/Article/details/gttocdgeck.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.wangshuangyany.cn/Article/details/gtraczoplj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtttfurgqy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtmtpkalpe.html

[N05] 最大公约数
来源：http://dali.yonumen.top/Article/details/gtlgqcpgix.html

Py:   math.gcd(a, b)
来源：http://dali.bjfxy.top/Article/details/gtayorvvpj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.quarkkingdee.top/Article/details/gtfuhgndcd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yanxiufei.cn/Article/details/gtofowuoch.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xziqi.cn/Article/details/gtrpixijty.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ivvv.top/Article/details/gtaqymxivz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cucudq.cn/Article/details/gtysdcrtps.html

Ruby: a.gcd(b)
来源：http://dali.zhongyouzk.top/Article/details/gtwmafefln.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.meibo888.top/Article/details/gtyqzjmmom.html

[N06] 判断回文字符串
来源：http://dali.chenzaomai.com/Article/details/gtritnfpdb.html

Py:   s == s[::-1]
来源：http://dali.guannengcc.top/Article/details/gtthjudwgq.html

PHP:  $s === strrev($s);
来源：http://dali.ydzc1.top/Article/details/gtcuesxfeu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gtwimpcbsb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtxicqdwkz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jlsjyb.cn/Article/details/gtzpsknkgq.html

Go:   // 双指针从两端比较
来源：http://dali.gaohongyu789.top/Article/details/gteexrqkzb.html

Ruby: s == s.reverse
来源：http://dali.redwolf501.top/Article/details/gtuxcotabl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj20258.top/Article/details/gtqhccxwbg.html

[N07] 两数之和（返回下标）
来源：http://dali.xinyue.icu/Article/details/gtgdijodbh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnikxeut.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.kuanghao11.cn/Article/details/gtnrtszxsf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.daria6918.cn/Article/details/gtxaqvdvtr.html

TS:   // 手写 Map<string, number>
来源：http://dali.ybcxt.top/Article/details/gtuhrtfzom.html

Java: // 手写 HashMap
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfhlnhzb.html

Go:   // 手写 map[int]int
来源：http://dali.gzhubu.top/Article/details/gtkjhsxqlp.html

Ruby: // 手写 Hash
来源：http://dali.gaohongyu789.top/Article/details/gtqynfkpcx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sxryk.cn/Article/details/gtvkbtbdck.html

[N08] 生成全排列
来源：http://dali.nanxuanxn.top/Article/details/gtiutheiar.html

Py:   itertools.permutations(arr)
来源：http://dali.yuxming.cn/Article/details/gtdvtzyuvo.html

PHP:  // 手写递归交换
来源：http://dali.yj20258.top/Article/details/gtyjbevawq.html

JS:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gtgbnstggq.html

TS:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtessncngd.html

Java: // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtbybtplex.html

Go:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtbgipnrnf.html

Ruby: arr.permutation.to_a
来源：http://dali.sxryk.cn/Article/details/gtncuykjas.html

C#:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtxhexecee.html

[N09] 栈与队列
来源：http://dali.sysykeji.top/Article/details/gtbefqvluu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtqveolkga.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ybcxt.top/Article/details/gtpxybqbmy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtjvuffooy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj202588.top/Article/details/gtmezjxzab.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gterxvbghc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.0kj1m.cn/Article/details/gtolhqbdiu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtgwcuviwg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yuxming.cn/Article/details/gtgzhzxmka.html

[N10] 链表节点定义
来源：http://dali.daxiang520.top/Article/details/gtwohvuqrm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.redwolf501.top/Article/details/gtoprpnplk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.quarkkingdee.top/Article/details/gtryvkwkns.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.316326.xyz/Article/details/gtvzxfnsbg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yuanzhike.top/Article/details/gtojebxwah.html

Java: class Node { int v; Node next; }
来源：http://dali.ppjwa.cn/Article/details/gtrvquzcbu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj20258.top/Article/details/gtjvzeieft.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.aibaodan.cn/Article/details/gtxhqaahdv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.andypj.xyz/Article/details/gtlqmsoomr.html

[N11] 二叉树中序遍历
来源：http://dali.gotoacloud.top/Article/details/gtjyneiiyi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yangfankeji.com/Article/details/gtnigppnnd.html

PHP:  // 手写递归函数
来源：http://dali.sweek.top/Article/details/gtuoqdfxzj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.snrcjt.cn/Article/details/gttrmvdjwv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aizwys.cn/Article/details/gtjcpemqrm.html

Java: // 手写递归
来源：http://dali.ivvv.top/Article/details/gtseeugwcl.html

Go:   // 手写递归
来源：http://dali.xylfe.cn/Article/details/gtctacvqjm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jyoumei.cn/Article/details/gtgsmjcxic.html

C#:   // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gtjyflvnwt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.feifeiyinyue.top/Article/details/gtrsnpxifs.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenzaomai.com/Article/details/gtoymmsuze.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gotoacloud.top/Article/details/gtxtxhfegq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258888.top/Article/details/gtlxnqkjmp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cashguo.top/Article/details/gtlxikbjuo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.mhx1999.top/Article/details/gthnugceyo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.quarkkingdee.top/Article/details/gtpvrvuxqa.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.meibo888.top/Article/details/gtrdvusxmi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sweek.top/Article/details/gtlmzqgxsj.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtfmermwqw.html

O. 并发与异步
来源：http://dali.yvedp.cn/Article/details/gtywkpkcxe.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtvhymmple.html

[O01] 启动一个线程
来源：http://dali.guowangkeji.top/Article/details/gtfdblzqrn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqfconmq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ivvv.top/Article/details/gtiodqmaed.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hongshengwenyu.top/Article/details/gtvksdmkpw.html

TS:   // 同 JS
来源：http://dali.fzhhl.top/Article/details/gtgtmsxlur.html

Java: new Thread(() -> f()).start()
来源：http://dali.cheryme.top/Article/details/gtklryiqcc.html

Go:   go f()
来源：http://dali.shanyushiyangtech.top/Article/details/gtpfbxokus.html

Ruby: Thread.new { f }
来源：http://dali.zhongyouzk.top/Article/details/gtmvomizqg.html

C#:   Task.Run(() => F());
来源：http://dali.fengsongda.top/Article/details/gtjpzkdvlr.html

[O02] 使用线程池
来源：http://dali.ivvv.top/Article/details/gtuqsrbbfq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yueranfly.top/Article/details/gtipdkbcks.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gaohongyu789.top/Article/details/gtnlqvdexn.html

JS:   // worker_threads 线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxkoavnu.html

TS:   // worker_threads 线程池
来源：http://dali.yangfankeji.com/Article/details/gtrwvlvzza.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cdnleiting.top/Article/details/gtvffxqvkj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nwbrower.top/Article/details/gtlyoobstx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.quarkkingdee.top/Article/details/gttljibnrb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jqgfzy.top/Article/details/gtzlgwapoe.html

[O03] 加锁保护共享数据
来源：http://dali.xinyue.icu/Article/details/gtbmbbcyfl.html

Py:   with lock: shared += 1
来源：http://dali.shzxlz.cn/Article/details/gtaugexhtx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj20258888.top/Article/details/gtflvsqvmx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yongpay.top/Article/details/gtmsuqlkqu.html

TS:   // 同 JS
来源：http://dali.jinqigufen.top/Article/details/gtrwfabsvr.html

Java: synchronized (this) { shared++; }
来源：http://dali.quarkkingdee.top/Article/details/gtiswldhcz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj202588.top/Article/details/gtckylabmd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cashguo.top/Article/details/gtkopzibon.html

C#:   lock (gate) { shared++; }
来源：http://dali.tanke756.top/Article/details/gtxgbombja.html

[O04] 定义异步函数并等待
来源：http://dali.daria6918.cn/Article/details/gtoidircpo.html

Py:   async def f():⏎    await g()
来源：http://dali.cucudq.cn/Article/details/gtcarczaqa.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.andypj.xyz/Article/details/gtailkbzyu.html

JS:   async function f() { await g(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtaxsqgcuf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yongpay.top/Article/details/gtbmhpmrdk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jlsjyb.cn/Article/details/gtlfndevsu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj20258888.top/Article/details/gtnsdjsebr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cqqwz.cn/Article/details/gtviwjsqmm.html

C#:   async Task F() { await G(); }
来源：http://dali.vqdsnc.cn/Article/details/gtmblvknwf.html

[O05] 并发执行并等待全部完成
来源：http://dali.yanxiufei.cn/Article/details/gtjxcdvzxe.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgfzy.top/Article/details/gtouknpfgl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhixingplan.top/Article/details/gtduxirrhl.html

JS:   await Promise.all(tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gtymqweytj.html

TS:   await Promise.all(tasks)
来源：http://dali.gogol.net.cn/Article/details/gtnldffesl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.havefunace.top/Article/details/gtkueyfkrc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jqgufenzy.top/Article/details/gtyxkitfun.html

Ruby: threads.map(&:join)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmfhvvtk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.redwolf501.top/Article/details/gtqbvimwzv.html

[O06] 使用进程池
来源：http://dali.yangfankeji.com/Article/details/gtjmrohwkt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yonumen.top/Article/details/gttjwpmgmu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ybcxt.top/Article/details/gtazzmtpmo.html

JS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdoevatac.html

TS:   // child_process / cluster 模块
来源：http://dali.jianghu66.top/Article/details/gthmrimclf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.daria6918.cn/Article/details/gtmgsykhqq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cashguo.top/Article/details/gtlydzlttg.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gtntitqzqo.html

C#:   Parallel.For
来源：http://dali.dianchejie.cn/Article/details/gtbgfotvmb.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtstyhmyuv.html

P. 常用工具函数
来源：http://dali.ppjwa.cn/Article/details/gttouemkjj.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtxmxcojuo.html

[P01] 生成 UUID
来源：http://dali.andypj.xyz/Article/details/gtxxgovhlf.html

Py:   str(uuid.uuid4())
来源：http://dali.haohaochexian.top/Article/details/gtycwgryli.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shzxlz.cn/Article/details/gtdjnehjtq.html

JS:   crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gtcszytnmu.html

TS:   crypto.randomUUID()
来源：http://dali.zhiwuduotai.top/Article/details/gtfhtpnysf.html

Java: UUID.randomUUID().toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtoobnhjbf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yangfankeji.com/Article/details/gtbeesvjwv.html

Ruby: SecureRandom.uuid
来源：http://dali.fzhhl.top/Article/details/gtgcyxydms.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tianlin.xyz/Article/details/gtdrikzrqc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shzxlz.cn/Article/details/gtnxspftbr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shangyingyoupin.top/Article/details/gtphouzfue.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.daria6918.cn/Article/details/gtbcacegbp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yuanzhike.top/Article/details/gtgpylkxmg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hnqzz.top/Article/details/gttiopctfu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258888.top/Article/details/gtnyixvvkn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.bjfxy.top/Article/details/gtbagmqqss.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.svipenyu.cn/Article/details/gtwzzwqimh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xylfe.cn/Article/details/gtasuhdnnr.html

[P03] 生成短随机字符串
来源：http://dali.nwbrower.top/Article/details/gtdbcpqwua.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhongyouzk.top/Article/details/gtzoarkzqk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmptailma.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangdashe.top/Article/details/gtaoxjmsls.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gogol.net.cn/Article/details/gtueiovnef.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcuuveqzc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.haohaochexian.top/Article/details/gtydzuwoxu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hfpthk.cn/Article/details/gttahbzmco.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hywenlv.cn/Article/details/gtmrrjrdos.html

[P04] 求长度
来源：http://dali.hywenlv.cn/Article/details/gtloyqevha.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nanxinkj.top/Article/details/gtxvxmbsio.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gtjcaoladd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shuidangran.top/Article/details/gtepryopit.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gaohongyu789.top/Article/details/gtyiesjyuy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jlsjyb.cn/Article/details/gtlupiycsv.html

Go:   len(arr);  len(m)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttbhoapxv.html

Ruby: x.length;  x.size
来源：http://dali.hongshengwenyu.top/Article/details/gtekqkwaiw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.aizwys.cn/Article/details/gthpwjwxua.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ywan-chungtsiang.top/Article/details/gtprejtxws.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tanke756.top/Article/details/gtjdyrridi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.daxiang520.top/Article/details/gtsbtpfrmi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.0kj1m.cn/Article/details/gtqcdqqwqn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yangfankeji.com/Article/details/gtnoavdyyq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.aibaodan.cn/Article/details/gtytnuedct.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cqqwz.cn/Article/details/gtgchlymsc.html

Ruby: a == b
来源：http://dali.xziqi.cn/Article/details/gtduluedam.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.guowangkeji.top/Article/details/gtyydrcrub.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.tian-w.cn/Article/details/gtbwtpirwk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.pycfn.com/Article/details/gtrongzunf.html

PHP:  if (empty($x)) {}
来源：http://dali.hnxiangtu.top/Article/details/gtulrunfxa.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cheryme.top/Article/details/gtvqyhzich.html

TS:   if (x == null) {}
来源：http://dali.pycfn.com/Article/details/gtpceaarib.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtixarvotz.html

Go:   if x == nil {}
来源：http://dali.zhixingplan.top/Article/details/gtjagfusff.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.havefunace.top/Article/details/gtffotzrha.html

C#:   if (x is null) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtaebcgfjq.html

[P07] 防抖与节流
来源：http://dali.daria6918.cn/Article/details/gteozxfkbz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shzxlz.cn/Article/details/gtkxudrwjx.html

PHP:  // 手写时间戳比较
来源：http://dali.tanke756.top/Article/details/gtuwpuhqsm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenzaomai.com/Article/details/gtxvcvitgi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gtvcnkuesf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yuxming.cn/Article/details/gthpevhbpi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xuetiantiany.cn/Article/details/gteuimmdbh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cdnleiting.top/Article/details/gtkzqssash.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenlongwang.top/Article/details/gtsfkeygde.html

[P08] 处理浮点精度问题
来源：http://dali.gzhubu.top/Article/details/gtwyzysmhp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yanxiufei.cn/Article/details/gtltwrkevi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.316326.xyz/Article/details/gtvyguhhbd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.pycfn.com/Article/details/gtmcyqrfog.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gogol.net.cn/Article/details/gthtciwzcj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zycfv.cn/Article/details/gtzvarlszm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ehwqpu.com/Article/details/gtydmwrwrj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jqgfzy.top/Article/details/gtqglalxgx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.wangshuangyany.cn/Article/details/gtdfuymrwl.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gturrxjvll.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.chenjidiqi.icu/Article/details/gtbqbtcjoj.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtwhcddqym.html

[Q01] 创建表
来源：http://dali.316326.xyz/Article/details/gtdqxucjtf.html

CREATE TABLE users (
来源：http://dali.shuidangran.top/Article/details/gtcomsikju.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.c1oappe.top/Article/details/gtndiqwwlm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj20258.top/Article/details/gtrfmcitys.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gaohongyu789.top/Article/details/gtedhqcosp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.meibo888.top/Article/details/gtmrwwlfmi.html

);
来源：http://dali.daria6918.cn/Article/details/gtqxzdftcz.html

[Q02] 创建带外键的表
来源：http://dali.hnxiangtu.top/Article/details/gtlxmfrxwu.html

CREATE TABLE orders (
来源：http://dali.yueranfly.top/Article/details/gtjeywjvyz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cashguo.top/Article/details/gtlityqufx.html

user_id INT NOT NULL,
来源：http://dali.hongshengwenyu.top/Article/details/gthsfaeuhc.html

amount DECIMAL(10, 2),
来源：http://dali.jinghuilouyu.cn/Article/details/gtzueivmuf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhoulong.xyz/Article/details/gtoibbxfpu.html

);
来源：http://dali.shzxlz.cn/Article/details/gtvhzjhxwl.html

[Q03] 增加列
来源：http://dali.9152youxi.cn/Article/details/gtpduppmaj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xziqi.cn/Article/details/gtvudmuusn.html

[Q04] 修改列类型
来源：http://dali.zhiwuduotai.top/Article/details/gtycogsxal.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cqqwz.cn/Article/details/gtczzpbcjo.html

[Q05] 重命名列
来源：http://dali.yongpay.top/Article/details/gtbrvbbwns.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbgprvbq.html

[Q06] 删除列
来源：http://dali.feifeiyinyue.top/Article/details/gtajyurqda.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cucudq.cn/Article/details/gtbacrxuno.html

[Q07] 删除表
来源：http://dali.hywenlv.cn/Article/details/gtkrnlggsx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gthpfgbvkq.html

[Q08] 创建普通索引
来源：http://dali.jinqigfzy.top/Article/details/gtcfgokcbn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shzxlz.cn/Article/details/gtshdvdise.html

[Q09] 创建唯一索引
来源：http://dali.jqgfzy.top/Article/details/gtvbctewrg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.c1oappe.top/Article/details/gtoysuentr.html

[Q10] 插入单行
来源：http://dali.zdqjudy.top/Article/details/gtlbkksxjl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.daxiang520.top/Article/details/gtmbvaprcr.html

[Q11] 一次插入多行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxuyqwkha.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ydzc1.top/Article/details/gtrwrdsgzh.html

[Q12] 插入后取自增 ID
来源：http://dali.hywenlv.cn/Article/details/gtcrugqrow.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.kuanghao11.cn/Article/details/gtarmfyqbn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.redwolf501.top/Article/details/gtdtrtxddl.html

[Q13] 忽略重复插入
来源：http://dali.gogol.net.cn/Article/details/gtzobnqrfh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhixingplan.top/Article/details/gtupxmgdff.html

[Q14] 存在则更新（upsert）
来源：http://dali.gaohongyu789.top/Article/details/gtgevovnfe.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hywenlv.cn/Article/details/gtibfhbysi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinqigfzy.top/Article/details/gtnzfeiali.html

[Q15] 查询全部
来源：http://dali.guowangkeji.top/Article/details/gthgzhhvij.html

SELECT * FROM users;
来源：http://dali.nwbrower.top/Article/details/gtwjxqfxhi.html

[Q16] 查询指定列
来源：http://dali.yueranfly.top/Article/details/gttylknnti.html

SELECT id, name FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcmhcbgfq.html

[Q17] 条件查询
来源：http://dali.ydzc1.top/Article/details/gtigwyesyl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtfjhcocqh.html

[Q18] 模糊匹配
来源：http://dali.jqgfzy.top/Article/details/gtfayattza.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gaohongyu789.top/Article/details/gtbjoxmklv.html

[Q19] 范围查询
来源：http://dali.jinqigfzy.top/Article/details/gtrvvmtjzf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xylfe.cn/Article/details/gtqokezocr.html

[Q20] IN 列表
来源：http://dali.tanke756.top/Article/details/gtazbxkrzy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nwbrower.top/Article/details/gtokxxgqal.html

[Q21] 空值判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqebqxmee.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpmkrjvpg.html

[Q22] 排序
来源：http://dali.nanxuanxn.top/Article/details/gtvpweztmi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jqgfzy.top/Article/details/gtlrefnysw.html

[Q23] 分页
来源：http://dali.nwbrower.top/Article/details/gtmlromusf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jqgfzy.top/Article/details/gtpolnotma.html

[Q24] 去重
来源：http://dali.svipenyu.cn/Article/details/gtjbwfabgd.html

SELECT DISTINCT city FROM users;
来源：http://dali.xylfe.cn/Article/details/gtqwpgxzsr.html

[Q25] 只取前 N 条
来源：http://dali.zhiwuduotai.top/Article/details/gtwkfmlrod.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yj20258888.top/Article/details/gtethdemsb.html

[Q26] 计数
来源：http://dali.havefunace.top/Article/details/gthlzzdits.html

SELECT COUNT(*) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtsnqbikat.html

[Q27] 条件计数
来源：http://dali.sufxvd.cn/Article/details/gtcpxcjjqa.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtjsrjmyhp.html

[Q28] 求和与平均
来源：http://dali.jyoumei.cn/Article/details/gtvgcerqgo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtgrkuwxjm.html

[Q29] 最大最小值
来源：http://dali.316326.xyz/Article/details/gtknkfyefp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtjahmnymo.html

[Q30] 分组统计
来源：http://dali.wangdashe.top/Article/details/gtavjtorgg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gtznyglzqy.html

[Q31] 分组后过滤
来源：http://dali.havefunace.top/Article/details/gtaeybzdix.html


<!-- 参考信息 -->