代发 wailian999

Ruby: arr.sort
来源：http://dali.redwolf501.top/Article/details/gt2qgbmpjup.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gwrserld.html

[N03] 快速排序（分治示例）
来源：http://dali.sysykeji.top/Article/details/gt2fgkzyair.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.svipenyu.cn/Article/details/gt2gxghvvdl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tanke756.top/Article/details/gt2tlmrtnag.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.havefunace.top/Article/details/gt2scgondan.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.smart0.xyz/Article/details/gt2gqgsrwrp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cvpjlviz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.daria6918.cn/Article/details/gt2cvbdbvxe.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jqgufenzy.top/Article/details/gt2pkavzonh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj202588.top/Article/details/gt2inxaslzi.html

[N04] 斐波那契数列
来源：http://dali.wangdashe.top/Article/details/gt2ppmlwkzf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yvedp.cn/Article/details/gt2vkvokxqh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.dianchejie.cn/Article/details/gt2rptcxuwp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kpkevoww.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gt2eayaaxhr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2minxzekt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.aizwys.cn/Article/details/gt2parnpfup.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yvedp.cn/Article/details/gt2oyyweqbw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2mzfqezie.html

[N05] 最大公约数
来源：http://dali.pengpengdd.cyou/Article/details/gt2dycjeizw.html

Py:   math.gcd(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pdvayzxf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sufxvd.cn/Article/details/gt2vyrbyvcr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenlongwang.top/Article/details/gt2daswfxlx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gt2zkhemmol.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shzxlz.cn/Article/details/gt2ussvwsxp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cqqwz.cn/Article/details/gt2vegwcguf.html

Ruby: a.gcd(b)
来源：http://dali.wangdashe.top/Article/details/gt2fjwpvkld.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhongyouzk.top/Article/details/gt2opwesyom.html

[N06] 判断回文字符串
来源：http://dali.xuanzx.com/Article/details/gt2lmsswshl.html

Py:   s == s[::-1]
来源：http://dali.dashuyun.cn/Article/details/gt2urjwiuzo.html

PHP:  $s === strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gt2mpivdlkn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gt2jiazzpat.html

TS:   s === [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gt2xxfbboka.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nrjogney.html

Go:   // 双指针从两端比较
来源：http://dali.birdmap.top/Article/details/gt2ryzsebie.html

Ruby: s == s.reverse
来源：http://dali.yanxiufei.cn/Article/details/gt2glmjcurp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.smart0.xyz/Article/details/gt2julpwghm.html

[N07] 两数之和（返回下标）
来源：http://dali.wangshuangyany.cn/Article/details/gt2xgajsccy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gzhubu.top/Article/details/gt2pzwqzlsy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tian-w.cn/Article/details/gt2xtvzydvg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ybcxt.top/Article/details/gt2hbstsjjt.html

TS:   // 手写 Map<string, number>
来源：http://dali.9152youxi.cn/Article/details/gt2mkerjlnv.html

Java: // 手写 HashMap
来源：http://dali.zhengqikj.top/Article/details/gt2qxnntzvs.html

Go:   // 手写 map[int]int
来源：http://dali.daxiang520.top/Article/details/gt2veuxaxky.html

Ruby: // 手写 Hash
来源：http://dali.yangfankeji.com/Article/details/gt2dhqvxrom.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.haohaochexian.top/Article/details/gt2gihydykm.html

[N08] 生成全排列
来源：http://dali.shuidangran.top/Article/details/gt2athjsfdb.html

Py:   itertools.permutations(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fgtbqfri.html

PHP:  // 手写递归交换
来源：http://dali.hnxiangtu.top/Article/details/gt2owjlxyuu.html

JS:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2sjabqhcz.html

TS:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2etvsvvsj.html

Java: // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gt2bjrssoxa.html

Go:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gt2svjbpewk.html

Ruby: arr.permutation.to_a
来源：http://dali.fengsongda.top/Article/details/gt2ujnlsajb.html

C#:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gt2wcwqptus.html

[N09] 栈与队列
来源：http://dali.zhoulong.xyz/Article/details/gt2euilespa.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zdqjudy.top/Article/details/gt2pymjqwmf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.bjfxy.top/Article/details/gt2xlgyozsn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fbvxnhjn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ybcxt.top/Article/details/gt2cvhgskgl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cucudq.cn/Article/details/gt2oavizrjr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ivvv.top/Article/details/gt2aakbsrux.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gogol.net.cn/Article/details/gt2hgcepijn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nanxinkj.top/Article/details/gt2arhedtqi.html

[N10] 链表节点定义
来源：http://dali.ppjwa.cn/Article/details/gt2rrnnzgsv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gzhubu.top/Article/details/gt2ojatljvq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yueranfly.top/Article/details/gt2jcozymlq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sxryk.cn/Article/details/gt2deebnmba.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yuanzhike.top/Article/details/gt2efecppyh.html

Java: class Node { int v; Node next; }
来源：http://dali.pycfn.com/Article/details/gt2spwfgkqx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.birdmap.top/Article/details/gt2etltbyly.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gogol.net.cn/Article/details/gt2eyjfxblj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.birdmap.top/Article/details/gt2nuconddh.html

[N11] 二叉树中序遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2otbhcecx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cheryme.top/Article/details/gt2prjtdysy.html

PHP:  // 手写递归函数
来源：http://dali.havefunace.top/Article/details/gt2wppmwres.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258888.top/Article/details/gt2cvuvrfqy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cqqwz.cn/Article/details/gt2synsogkz.html

Java: // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2coiygxxm.html

Go:   // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2bqunexte.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gchktqrb.html

C#:   // 手写递归
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zximhsid.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.redwolf501.top/Article/details/gt2oxcqpgen.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.0kj1m.cn/Article/details/gt2qrwigacs.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.bjfxy.top/Article/details/gt2unwmousl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cucudq.cn/Article/details/gt2sbvezehl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cdnleiting.top/Article/details/gt2skclbmkq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sxryk.cn/Article/details/gt2ithxppsw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.snrcjt.cn/Article/details/gt2artmkvfq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gzhubu.top/Article/details/gt2glafrrqi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shzxlz.cn/Article/details/gt2icakxmgd.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2pjhsqfma.html

O. 并发与异步
来源：http://dali.zhengqikj.top/Article/details/gt2bupqimac.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2ibdrshfq.html

[O01] 启动一个线程
来源：http://dali.tian-w.cn/Article/details/gt2fodeatty.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zycfv.cn/Article/details/gt2dxsvhifo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.daxiang520.top/Article/details/gt2zqrzzsdf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cashguo.top/Article/details/gt2mlhecblm.html

TS:   // 同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vtgmnlve.html

Java: new Thread(() -> f()).start()
来源：http://dali.fengsongda.top/Article/details/gt2yhseixpn.html

Go:   go f()
来源：http://dali.quarkkingdee.top/Article/details/gt2apguqeyn.html

Ruby: Thread.new { f }
来源：http://dali.jinqigfzy.top/Article/details/gt2ldnluvmu.html

C#:   Task.Run(() => F());
来源：http://dali.jianghu66.top/Article/details/gt2pwkeahzs.html

[O02] 使用线程池
来源：http://dali.zhixingplan.top/Article/details/gt2gjcirkpx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xuetiantiany.cn/Article/details/gt2usbveuyf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yongpay.top/Article/details/gt2pftfdkyk.html

JS:   // worker_threads 线程池
来源：http://dali.nwbrower.top/Article/details/gt2rwlbnchb.html

TS:   // worker_threads 线程池
来源：http://dali.zhengqikj.top/Article/details/gt2sactiwhr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.chenzaomai.com/Article/details/gt2bkfhkdwa.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jqgfzy.top/Article/details/gt2ufgttgsd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shzxlz.cn/Article/details/gt2piheywla.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xylfe.cn/Article/details/gt2vuvxnpnw.html

[O03] 加锁保护共享数据
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mmvjwiiq.html

Py:   with lock: shared += 1
来源：http://dali.dianchejie.cn/Article/details/gt2axpvepnt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hammf.cn/Article/details/gt2chjovcqd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shuidangran.top/Article/details/gt2dtchsvtk.html

TS:   // 同 JS
来源：http://dali.fengsongda.top/Article/details/gt2edtxzxnm.html

Java: synchronized (this) { shared++; }
来源：http://dali.jiagoushi.top/Article/details/gt2hjgspfdv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cqqwz.cn/Article/details/gt2bhslyhmo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yueranfly.top/Article/details/gt2djdijoem.html

C#:   lock (gate) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gt2kgcwqfkq.html

[O04] 定义异步函数并等待
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bbxluxnh.html

Py:   async def f():⏎    await g()
来源：http://dali.ivvv.top/Article/details/gt2ocqfnpuj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pjbqpjxx.html

JS:   async function f() { await g(); }
来源：http://dali.svipenyu.cn/Article/details/gt2vwzshetc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ndqvtofz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhoulong.xyz/Article/details/gt2apruwguu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qocwyewf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinqigfzy.top/Article/details/gt2fvkitktv.html

C#:   async Task F() { await G(); }
来源：http://dali.yj202588.top/Article/details/gt2neuyibln.html

[O05] 并发执行并等待全部完成
来源：http://dali.0kj1m.cn/Article/details/gt2iokekcay.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ehwqpu.com/Article/details/gt2ulqilbsz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hnxiangtu.top/Article/details/gt2gyvzpnhp.html

JS:   await Promise.all(tasks)
来源：http://dali.jqgufenzy.top/Article/details/gt2shzwodyk.html

TS:   await Promise.all(tasks)
来源：http://dali.hysaishi.cn/Article/details/gt2xcuxacrm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pycfn.com/Article/details/gt2ctgnovng.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xuanzx.com/Article/details/gt2wrdbjhef.html

Ruby: threads.map(&:join)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fpkcfkqm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.meibo888.top/Article/details/gt2eucpfagc.html

[O06] 使用进程池
来源：http://dali.feifeiyinyue.top/Article/details/gt2qmsofrnq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yanxiufei.cn/Article/details/gt2yelhniuh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jyoumei.cn/Article/details/gt2llvfbiox.html

JS:   // child_process / cluster 模块
来源：http://dali.zycfv.cn/Article/details/gt2vjxhavgu.html

TS:   // child_process / cluster 模块
来源：http://dali.xuetiantiany.cn/Article/details/gt2qyuofsej.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.fengsongda.top/Article/details/gt2hplsdkbr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gogol.net.cn/Article/details/gt2guugqqzz.html

Ruby: // fork 块
来源：http://dali.sufxvd.cn/Article/details/gt2mbfqkgtm.html

C#:   Parallel.For
来源：http://dali.svipenyu.cn/Article/details/gt2symggjty.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2mtzvpwvo.html

P. 常用工具函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sltwlxkx.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2zgvtqwmd.html

[P01] 生成 UUID
来源：http://dali.tian-w.cn/Article/details/gt2qzmpzaov.html

Py:   str(uuid.uuid4())
来源：http://dali.fzhhl.top/Article/details/gt2ocaysuaq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jlsjyb.cn/Article/details/gt2shqsbsoy.html

JS:   crypto.randomUUID()
来源：http://dali.zhiwuduotai.top/Article/details/gt2klcvbwnf.html

TS:   crypto.randomUUID()
来源：http://dali.0kj1m.cn/Article/details/gt2eapwduxv.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gcwclrxk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cucudq.cn/Article/details/gt2dxxmlrke.html

Ruby: SecureRandom.uuid
来源：http://dali.fzhhl.top/Article/details/gt2ndbqojkf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hnxiangtu.top/Article/details/gt2dcsgtpsy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.vqdsnc.cn/Article/details/gt2djrnotnd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj20258888.top/Article/details/gt2fhbqcgcw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cqqwz.cn/Article/details/gt2xczopldt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yanxiufei.cn/Article/details/gt2uzclaymx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nanxuanxn.top/Article/details/gt2dtcoyqpi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hammf.cn/Article/details/gt2cmxllcmh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ppjwa.cn/Article/details/gt2mwyijjbj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2yovqfoix.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhengqikj.top/Article/details/gt2hkcobsxl.html

[P03] 生成短随机字符串
来源：http://dali.smart0.xyz/Article/details/gt2uzchulum.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.redwolf501.top/Article/details/gt2fkewvkmj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xuetiantiany.cn/Article/details/gt2xbktxvqq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gogol.net.cn/Article/details/gt2gmobvpbz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jyoumei.cn/Article/details/gt2kbrfnxtu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tian-w.cn/Article/details/gt2cdmburfe.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.fzhhl.top/Article/details/gt2dlrrwlkc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jwxhvbki.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jqgufenzy.top/Article/details/gt2ltqkknel.html

[P04] 求长度
来源：http://dali.pycfn.com/Article/details/gt2xonxtlof.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fzzeafwo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gt2jedwyapp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuanzx.com/Article/details/gt2liwpnode.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tian-w.cn/Article/details/gt2kqldygug.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hongshengwenyu.top/Article/details/gt2fhncykel.html

Go:   len(arr);  len(m)
来源：http://dali.haohaochexian.top/Article/details/gt2wfhicjoy.html

Ruby: x.length;  x.size
来源：http://dali.guowangkeji.top/Article/details/gt2xwdlmkpv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhoulong.xyz/Article/details/gt2rjexkoop.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhiwuduotai.top/Article/details/gt2ozhsscax.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xuanzx.com/Article/details/gt2ipdgtlud.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.pengpengdd.cyou/Article/details/gt2gbosewsu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.birdmap.top/Article/details/gt2jkatiatv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.redwolf501.top/Article/details/gt2tfhlnkfv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yanxiufei.cn/Article/details/gt2btdvride.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hysaishi.cn/Article/details/gt2bzharcic.html

Ruby: a == b
来源：http://dali.316326.xyz/Article/details/gt2kyzktqvw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zdqjudy.top/Article/details/gt2tzsfzisd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhoulong.xyz/Article/details/gt2pkmmpmvg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zunhxrhh.html

PHP:  if (empty($x)) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ixifctpx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.meibo888.top/Article/details/gt2glpznjle.html

TS:   if (x == null) {}
来源：http://dali.gogol.net.cn/Article/details/gt2qqdcukaa.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2lrlbhmvj.html

Go:   if x == nil {}
来源：http://dali.jqgfzy.top/Article/details/gt2cdfhmhdl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.svipenyu.cn/Article/details/gt2jmbcghfx.html

C#:   if (x is null) {}
来源：http://dali.gzhubu.top/Article/details/gt2lthsfyet.html

[P07] 防抖与节流
来源：http://dali.nanxuanxn.top/Article/details/gt2dabbwigm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jiagoushi.top/Article/details/gt2kbzrvpjz.html

PHP:  // 手写时间戳比较
来源：http://dali.chenzaomai.com/Article/details/gt2jhmuoauv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gt2jpnyqgad.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gt2pgoczzwl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2museueuk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ppjwa.cn/Article/details/gt2oxvkyebg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hywenlv.cn/Article/details/gt2izqwyqem.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.fzhhl.top/Article/details/gt2nuowmrsl.html

[P08] 处理浮点精度问题
来源：http://dali.tian-w.cn/Article/details/gt2hkcnxyab.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.iojbl.cn/Article/details/gt2jpomktcf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.0kj1m.cn/Article/details/gt2cuduowvl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.smart0.xyz/Article/details/gt2caeqhdaw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.smart0.xyz/Article/details/gt2pxvpqfpa.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhiwuduotai.top/Article/details/gt2ztgferrk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cdnleiting.top/Article/details/gt2zqxkwsck.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gaohongyu789.top/Article/details/gt2dbdcmvam.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.quarkkingdee.top/Article/details/gt2uirjpnam.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2dltevuzt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.chenzaomai.com/Article/details/gt2klwpjlty.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2mkxzcrtc.html

[Q01] 创建表
来源：http://dali.c1oappe.top/Article/details/gt2ppfypyop.html

CREATE TABLE users (
来源：http://dali.zhixingplan.top/Article/details/gt2gpgaypsg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xziqi.cn/Article/details/gt2cfxsqpmp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yanxiufei.cn/Article/details/gt2minabofu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenlongwang.top/Article/details/gt2tbcftear.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tfbrgiqp.html

);
来源：http://dali.jyoumei.cn/Article/details/gt2jksoyvgm.html

[Q02] 创建带外键的表
来源：http://dali.fzhhl.top/Article/details/gt2igzmvbkp.html

CREATE TABLE orders (
来源：http://dali.hfpthk.cn/Article/details/gt2flmrxyki.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigufen.top/Article/details/gt2ihflhmpq.html

user_id INT NOT NULL,
来源：http://dali.gzhubu.top/Article/details/gt2omzyiedf.html

amount DECIMAL(10, 2),
来源：http://dali.xziqi.cn/Article/details/gt2vujvypop.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hysaishi.cn/Article/details/gt2gfvjmrto.html

);
来源：http://dali.sweek.top/Article/details/gt2htdziqxb.html

[Q03] 增加列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jostfudq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yueranfly.top/Article/details/gt2ocfyrakd.html

[Q04] 修改列类型
来源：http://dali.jinqigufen.top/Article/details/gt2xywbmrxa.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.wangshuangyany.cn/Article/details/gt2qojfoqsv.html

[Q05] 重命名列
来源：http://dali.guowangkeji.top/Article/details/gt2hemlotza.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2juaoktsc.html

[Q06] 删除列
来源：http://dali.cheryme.top/Article/details/gt2wrkdjibx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hysaishi.cn/Article/details/gt2jlplhqaw.html

[Q07] 删除表
来源：http://dali.quarkkingdee.top/Article/details/gt2agdjfvjf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yonumen.top/Article/details/gt2xkbbzaev.html

[Q08] 创建普通索引
来源：http://dali.sufxvd.cn/Article/details/gt2feewvoux.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shuidangran.top/Article/details/gt2iouinvxh.html

[Q09] 创建唯一索引
来源：http://dali.0kj1m.cn/Article/details/gt2vpsclzhj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sxryk.cn/Article/details/gt2osybinkf.html

[Q10] 插入单行
来源：http://dali.snrcjt.cn/Article/details/gt2ugrvibkd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhixingplan.top/Article/details/gt2kivjmrpu.html

[Q11] 一次插入多行
来源：http://dali.zycfv.cn/Article/details/gt2prtwxaog.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.9152youxi.cn/Article/details/gt2cqynckww.html

[Q12] 插入后取自增 ID
来源：http://dali.jinqigfzy.top/Article/details/gt2gkrkomfp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.fengsongda.top/Article/details/gt2wowmunen.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.mhx1999.top/Article/details/gt2xqthbeaf.html

[Q13] 忽略重复插入
来源：http://dali.yuanzhike.top/Article/details/gt2dezhrzbe.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ivvv.top/Article/details/gt2lwwdaqse.html

[Q14] 存在则更新（upsert）
来源：http://dali.mhx1999.top/Article/details/gt2wqvrgxcv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xuetiantiany.cn/Article/details/gt2pjjjhgke.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.feifeiyinyue.top/Article/details/gt2bcvvlgge.html

[Q15] 查询全部
来源：http://dali.yonumen.top/Article/details/gt2nlywxyuf.html

SELECT * FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dkoonftv.html

[Q16] 查询指定列
来源：http://dali.cucudq.cn/Article/details/gt2rgohbtns.html

SELECT id, name FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2bgzissqw.html

[Q17] 条件查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kstrsjhf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cdnleiting.top/Article/details/gt2qqkfpaxs.html

[Q18] 模糊匹配
来源：http://dali.fzhhl.top/Article/details/gt2haruvlkx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenjidiqi.icu/Article/details/gt2jtgeylux.html

[Q19] 范围查询
来源：http://dali.shzxlz.cn/Article/details/gt2nfczfzzb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.birdmap.top/Article/details/gt2lsnukgpp.html

[Q20] IN 列表
来源：http://dali.ppjwa.cn/Article/details/gt2ichgzdry.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2zcwexlzm.html

[Q21] 空值判断
来源：http://dali.snrcjt.cn/Article/details/gt2ngazrebo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.316326.xyz/Article/details/gt2uwxhlodk.html

[Q22] 排序
来源：http://dali.dashuyun.cn/Article/details/gt2demthzcp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hywenlv.cn/Article/details/gt2xxsyavfh.html

[Q23] 分页
来源：http://dali.guowangkeji.top/Article/details/gt2kzcgbosz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hulzvgwk.html

[Q24] 去重
来源：http://dali.gzhubu.top/Article/details/gt2ixnkwogn.html

SELECT DISTINCT city FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2jselglkl.html

[Q25] 只取前 N 条
来源：http://dali.yongpay.top/Article/details/gt2rgvvgfdg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zdqjudy.top/Article/details/gt2jlbptjnf.html

[Q26] 计数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fltjzrru.html

SELECT COUNT(*) FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2nhohsvog.html

[Q27] 条件计数
来源：http://dali.svipenyu.cn/Article/details/gt2lvhkybng.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cheryme.top/Article/details/gt2mqklpwjz.html

[Q28] 求和与平均
来源：http://dali.hnqzz.top/Article/details/gt2eivtsrto.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gt2wyktlhmk.html

[Q29] 最大最小值
来源：http://dali.cqqwz.cn/Article/details/gt2fnmvvqqk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mpaozlfk.html

[Q30] 分组统计
来源：http://dali.jianghu66.top/Article/details/gt2viokwsdn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gt2pyygeimz.html

[Q31] 分组后过滤
来源：http://dali.zhengqikj.top/Article/details/gt2kduyfkgw.html


<!-- 参考信息 -->