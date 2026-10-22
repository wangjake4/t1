代发 wailian999

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zycfv.cn/Article/details/gt2bowldeev.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jqgufenzy.top/Article/details/gt2yytqhwba.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.redwolf501.top/Article/details/gt2audgbxgy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2hhzkvmyk.html

[N05] 最大公约数
来源：http://dali.jqgufenzy.top/Article/details/gt2nadapppr.html

Py:   math.gcd(a, b)
来源：http://dali.iojbl.cn/Article/details/gt2bgpuamgm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xahoymqk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgufenzy.top/Article/details/gt2qjgtnvhh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dashuyun.cn/Article/details/gt2nbvdbfey.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.meibo888.top/Article/details/gt2bjlmaoaj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinqigufen.top/Article/details/gt2hhaprkzy.html

Ruby: a.gcd(b)
来源：http://dali.zhoulong.xyz/Article/details/gt2lthultbo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuxming.cn/Article/details/gt2oxsmkxfa.html

[N06] 判断回文字符串
来源：http://dali.hysaishi.cn/Article/details/gt2vvxurjaw.html

Py:   s == s[::-1]
来源：http://dali.tianlin.xyz/Article/details/gt2uisicyrj.html

PHP:  $s === strrev($s);
来源：http://dali.aizwys.cn/Article/details/gt2uexpbdxv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gt2avbvkfzs.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gt2ytmjdhzx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tian-w.cn/Article/details/gt2hlennpnb.html

Go:   // 双指针从两端比较
来源：http://dali.xuanzx.com/Article/details/gt2tyzqplkl.html

Ruby: s == s.reverse
来源：http://dali.jinqigufen.top/Article/details/gt2gjztlqyz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gt2ddavervr.html

[N07] 两数之和（返回下标）
来源：http://dali.316326.xyz/Article/details/gt2jvkxnrfj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nwbrower.top/Article/details/gt2vuzixcdl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinqigufen.top/Article/details/gt2hzjvsnus.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenzaomai.com/Article/details/gt2johadshn.html

TS:   // 手写 Map<string, number>
来源：http://dali.smart0.xyz/Article/details/gt2wdxqfenn.html

Java: // 手写 HashMap
来源：http://dali.jqgufenzy.top/Article/details/gt2rybjdoqx.html

Go:   // 手写 map[int]int
来源：http://dali.sweek.top/Article/details/gt2pjgulkxk.html

Ruby: // 手写 Hash
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2izutwlqo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hfpthk.cn/Article/details/gt2kdfpuvka.html

[N08] 生成全排列
来源：http://dali.daxiang520.top/Article/details/gt2rkxkkhnh.html

Py:   itertools.permutations(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2agaifgpt.html

PHP:  // 手写递归交换
来源：http://dali.jqgfzy.top/Article/details/gt2qftyqqnj.html

JS:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gt2xihntqlx.html

TS:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gt2yesaphpi.html

Java: // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2lathonxr.html

Go:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2lwymszeg.html

Ruby: arr.permutation.to_a
来源：http://dali.daxiang520.top/Article/details/gt2uddfyran.html

C#:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2grpwjcuf.html

[N09] 栈与队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fmrantqp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shuidangran.top/Article/details/gt2suoracuz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.smart0.xyz/Article/details/gt2lqsmqypg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gt2tpdbjdrw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nanxinkj.top/Article/details/gt2jwbfgojm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.daxiang520.top/Article/details/gt2ewczqjut.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ivvv.top/Article/details/gt2kiqxzwbc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xuanzx.com/Article/details/gt2kijwvllr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sysykeji.top/Article/details/gt2sqrddgef.html

[N10] 链表节点定义
来源：http://dali.316326.xyz/Article/details/gt2yqfecewr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yuxming.cn/Article/details/gt2kpeciops.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jlsjyb.cn/Article/details/gt2bhuvrdve.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.smart0.xyz/Article/details/gt2uyufqymx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.aibaodan.cn/Article/details/gt2xmmwqljg.html

Java: class Node { int v; Node next; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sipyncoq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.pengpengdd.cyou/Article/details/gt2exdieqqb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cdnleiting.top/Article/details/gt2gjrpotvv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhongyouzk.top/Article/details/gt2yefixnxg.html

[N11] 二叉树中序遍历
来源：http://dali.gzhubu.top/Article/details/gt2bpjfbogf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhoulong.xyz/Article/details/gt2qdnvugis.html

PHP:  // 手写递归函数
来源：http://dali.bjfxy.top/Article/details/gt2eqcbodhw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jianghu66.top/Article/details/gt2szvexsun.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgufenzy.top/Article/details/gt2knvrryvz.html

Java: // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gt2lqjchzdx.html

Go:   // 手写递归
来源：http://dali.hnxiangtu.top/Article/details/gt2ohaeddxx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj202588.top/Article/details/gt2dhzmzlnz.html

C#:   // 手写递归
来源：http://dali.9152youxi.cn/Article/details/gt2irqdcazy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ryfptusb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.c1oappe.top/Article/details/gt2shynflvo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cheryme.top/Article/details/gt2hafngnhl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhixingplan.top/Article/details/gt2uuetkzhe.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yanxiufei.cn/Article/details/gt2lfvimsxt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuetiantiany.cn/Article/details/gt2pmlffyzw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinqigfzy.top/Article/details/gt2mybclwys.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jianghu66.top/Article/details/gt2dkwcppdp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guowangkeji.top/Article/details/gt2emshpreu.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2uopmhgfx.html

O. 并发与异步
来源：http://dali.quarkkingdee.top/Article/details/gt2zhtptima.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2ylkpdgux.html

[O01] 启动一个线程
来源：http://dali.pengpengdd.cyou/Article/details/gt2dqmtmyor.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sweek.top/Article/details/gt2qoacfqhh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nwbrower.top/Article/details/gt2afbyosnb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.c1oappe.top/Article/details/gt2bbtjcvmv.html

TS:   // 同 JS
来源：http://dali.tianlin.xyz/Article/details/gt2lhneomdq.html

Java: new Thread(() -> f()).start()
来源：http://dali.cqqwz.cn/Article/details/gt2ckjmhchq.html

Go:   go f()
来源：http://dali.shzxlz.cn/Article/details/gt2ujrayomb.html

Ruby: Thread.new { f }
来源：http://dali.birdmap.top/Article/details/gt2zmhfyngk.html

C#:   Task.Run(() => F());
来源：http://dali.ydzc1.top/Article/details/gt2fpebguld.html

[O02] 使用线程池
来源：http://dali.chenlongwang.top/Article/details/gt2bpdbpown.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qbresqem.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nlsefmvj.html

JS:   // worker_threads 线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kbktiijr.html

TS:   // worker_threads 线程池
来源：http://dali.nanxuanxn.top/Article/details/gt2athpfsyv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cqqwz.cn/Article/details/gt2tneghwho.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.aizwys.cn/Article/details/gt2stivvgrl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.smart0.xyz/Article/details/gt2ddieqwug.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.daria6918.cn/Article/details/gt2mwyjpwgl.html

[O03] 加锁保护共享数据
来源：http://dali.sxryk.cn/Article/details/gt2mqzctffl.html

Py:   with lock: shared += 1
来源：http://dali.ybcxt.top/Article/details/gt2mjintjjx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenlongwang.top/Article/details/gt2kmeouvzx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.aizwys.cn/Article/details/gt2pudpzfhl.html

TS:   // 同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ifiwlsmh.html

Java: synchronized (this) { shared++; }
来源：http://dali.jyoumei.cn/Article/details/gt2xuwqumoz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhengqikj.top/Article/details/gt2hsqzrhaa.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wiepqcng.html

C#:   lock (gate) { shared++; }
来源：http://dali.wangdashe.top/Article/details/gt2njnegdvx.html

[O04] 定义异步函数并等待
来源：http://dali.xuanzx.com/Article/details/gt2kjaexdhh.html

Py:   async def f():⏎    await g()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2egyoujfp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nanxuanxn.top/Article/details/gt2pweeutqh.html

JS:   async function f() { await g(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2nczvhvis.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gt2ttkywihg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zycfv.cn/Article/details/gt2wfyfuvkm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenlongwang.top/Article/details/gt2bpdrsabi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gotoacloud.top/Article/details/gt2lysbivea.html

C#:   async Task F() { await G(); }
来源：http://dali.nanxinkj.top/Article/details/gt2waeyardm.html

[O05] 并发执行并等待全部完成
来源：http://dali.tian-w.cn/Article/details/gt2tvqnbnhx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.fengsongda.top/Article/details/gt2ltutphlp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.0kj1m.cn/Article/details/gt2fauzucay.html

JS:   await Promise.all(tasks)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lvkgvjtt.html

TS:   await Promise.all(tasks)
来源：http://dali.kuanghao11.cn/Article/details/gt2kelfysny.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhiwuduotai.top/Article/details/gt2zzoozqjj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.bjfxy.top/Article/details/gt2nwjkpiqg.html

Ruby: threads.map(&:join)
来源：http://dali.yvedp.cn/Article/details/gt2xbvkzbze.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tian-w.cn/Article/details/gt2vhlkkket.html

[O06] 使用进程池
来源：http://dali.xylfe.cn/Article/details/gt2ovujujnm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.vqdsnc.cn/Article/details/gt2gfepvnzj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xylfe.cn/Article/details/gt2vujdekez.html

JS:   // child_process / cluster 模块
来源：http://dali.sxryk.cn/Article/details/gt2enhhzxjx.html

TS:   // child_process / cluster 模块
来源：http://dali.yuanzhike.top/Article/details/gt2ruokbhjs.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.svipenyu.cn/Article/details/gt2vflzdggr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shzxlz.cn/Article/details/gt2indxhqvz.html

Ruby: // fork 块
来源：http://dali.zhengqikj.top/Article/details/gt2ucxdignq.html

C#:   Parallel.For
来源：http://dali.hnqzz.top/Article/details/gt2kwaqdmix.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2qtcxsaae.html

P. 常用工具函数
来源：http://dali.xinyue.icu/Article/details/gt2kniiceob.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2ptymuvdc.html

[P01] 生成 UUID
来源：http://dali.yonumen.top/Article/details/gt2ktbqkzzl.html

Py:   str(uuid.uuid4())
来源：http://dali.sysykeji.top/Article/details/gt2xrqhxfuj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yuxming.cn/Article/details/gt2cfgxynds.html

JS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gt2zpqewkug.html

TS:   crypto.randomUUID()
来源：http://dali.zhiwuduotai.top/Article/details/gt2zirrvavd.html

Java: UUID.randomUUID().toString()
来源：http://dali.shuidangran.top/Article/details/gt2iruzwurz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.fengsongda.top/Article/details/gt2mutegrfs.html

Ruby: SecureRandom.uuid
来源：http://dali.shzxlz.cn/Article/details/gt2cbclyuur.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.316326.xyz/Article/details/gt2cbrvevtd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.wangdashe.top/Article/details/gt2pgpgayab.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigfzy.top/Article/details/gt2ygfsgoav.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jyoumei.cn/Article/details/gt2cejvtqak.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kcrcqqpa.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.aizwys.cn/Article/details/gt2txbwcojn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tian-w.cn/Article/details/gt2mtmqsusy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nwbrower.top/Article/details/gt2loanydvv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xylfe.cn/Article/details/gt2hszeqrlg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ybcxt.top/Article/details/gt2bnudvqhj.html

[P03] 生成短随机字符串
来源：http://dali.jinqigufen.top/Article/details/gt2kvbwiiuu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenzaomai.com/Article/details/gt2hqvgewuw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.smart0.xyz/Article/details/gt2dewaihrw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhixingplan.top/Article/details/gt2lzobwvou.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.vqdsnc.cn/Article/details/gt2jezaetyf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinqigfzy.top/Article/details/gt2xgtenxva.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.birdmap.top/Article/details/gt2tnuugepm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhoulong.xyz/Article/details/gt2sxjuctdn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xuetiantiany.cn/Article/details/gt2nluscmtd.html

[P04] 求长度
来源：http://dali.0kj1m.cn/Article/details/gt2poicnzay.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.0kj1m.cn/Article/details/gt2lsundaod.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gt2fevrakpa.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ydzc1.top/Article/details/gt2otbjtdfs.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hfpthk.cn/Article/details/gt2qsvlxqzi.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinqigfzy.top/Article/details/gt2ojvutkdy.html

Go:   len(arr);  len(m)
来源：http://dali.zhengqikj.top/Article/details/gt2procbnjr.html

Ruby: x.length;  x.size
来源：http://dali.gaohongyu789.top/Article/details/gt2grdfetka.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.pycfn.com/Article/details/gt2hldqycsq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dianchejie.cn/Article/details/gt2nwkvxvtb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tianlin.xyz/Article/details/gt2cuhdswbw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hnxiangtu.top/Article/details/gt2fpntfxga.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.guowangkeji.top/Article/details/gt2gmobulvr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ilpezobg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fzhhl.top/Article/details/gt2igivpgcg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.nanxuanxn.top/Article/details/gt2erhvjawa.html

Ruby: a == b
来源：http://dali.hywenlv.cn/Article/details/gt2wtqvbbtp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hysaishi.cn/Article/details/gt2ctjumeuq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ukrgwccg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xylfe.cn/Article/details/gt2cicyfhro.html

PHP:  if (empty($x)) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2etjgqefx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mjtwafzl.html

TS:   if (x == null) {}
来源：http://dali.yuanzhike.top/Article/details/gt2uxsevoov.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.dianchejie.cn/Article/details/gt2lsmwtssf.html

Go:   if x == nil {}
来源：http://dali.xinyue.icu/Article/details/gt2xybizvbc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ehwqpu.com/Article/details/gt2evyaewwq.html

C#:   if (x is null) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2qgwovpxl.html

[P07] 防抖与节流
来源：http://dali.aibaodan.cn/Article/details/gt2cycskngz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yueranfly.top/Article/details/gt2jljunkgc.html

PHP:  // 手写时间戳比较
来源：http://dali.c1oappe.top/Article/details/gt2heodwbzr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenzaomai.com/Article/details/gt2zfbcwecb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cdnleiting.top/Article/details/gt2ydjacsva.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.smart0.xyz/Article/details/gt2jfrigilj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.snrcjt.cn/Article/details/gt2javzwlpl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cheryme.top/Article/details/gt2agguosho.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.wangdashe.top/Article/details/gt2fefvbyhm.html

[P08] 处理浮点精度问题
来源：http://dali.bjfxy.top/Article/details/gt2rwqymhpq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.kuanghao11.cn/Article/details/gt2sqbzsdem.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hongshengwenyu.top/Article/details/gt2zsmrwfti.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhiwuduotai.top/Article/details/gt2tvfyiulm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gaohongyu789.top/Article/details/gt2ofrnyhqk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yvedp.cn/Article/details/gt2oiecvyrr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hysaishi.cn/Article/details/gt2zcahnqal.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gaohongyu789.top/Article/details/gt2xxcyeneu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.dianchejie.cn/Article/details/gt2zvpyhxct.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2sratjhyi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cqqwz.cn/Article/details/gt2kxiriwej.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2uaesxygz.html

[Q01] 创建表
来源：http://dali.fengsongda.top/Article/details/gt2tkfmbrgf.html

CREATE TABLE users (
来源：http://dali.jianghu66.top/Article/details/gt2fulbaeim.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cashguo.top/Article/details/gt2mxckcczt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.wangdashe.top/Article/details/gt2fouldtfh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hongshengwenyu.top/Article/details/gt2kipcmgfc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bbrxpiqf.html

);
来源：http://dali.dianchejie.cn/Article/details/gt2fggyyons.html

[Q02] 创建带外键的表
来源：http://dali.bjfxy.top/Article/details/gt2ckkumcvb.html

CREATE TABLE orders (
来源：http://dali.chenzaomai.com/Article/details/gt2afzcoewx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zycfv.cn/Article/details/gt2ijmjajby.html

user_id INT NOT NULL,
来源：http://dali.haohaochexian.top/Article/details/gt2gqagnnvq.html

amount DECIMAL(10, 2),
来源：http://dali.cdnleiting.top/Article/details/gt2mtpsomtf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hpjnyjnf.html

);
来源：http://dali.andypj.xyz/Article/details/gt2rymtnydw.html

[Q03] 增加列
来源：http://dali.mhx1999.top/Article/details/gt2iuvadbhr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hongshengwenyu.top/Article/details/gt2tmnvkyjh.html

[Q04] 修改列类型
来源：http://dali.c1oappe.top/Article/details/gt2zeeoxjha.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.dashuyun.cn/Article/details/gt2humrnkvc.html

[Q05] 重命名列
来源：http://dali.chenjidiqi.icu/Article/details/gt2jaelvssw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ivvv.top/Article/details/gt2piafwsib.html

[Q06] 删除列
来源：http://dali.chenlongwang.top/Article/details/gt2kxryvepm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.smart0.xyz/Article/details/gt2neahoszp.html

[Q07] 删除表
来源：http://dali.chenzaomai.com/Article/details/gt2hfcnjuol.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jqgfzy.top/Article/details/gt2nbhhipzx.html

[Q08] 创建普通索引
来源：http://dali.feifeiyinyue.top/Article/details/gt2wdgpuhog.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj202588.top/Article/details/gt2kagirihn.html

[Q09] 创建唯一索引
来源：http://dali.yvedp.cn/Article/details/gt2yqtlwvgo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhixingplan.top/Article/details/gt2zfumzoht.html

[Q10] 插入单行
来源：http://dali.jiagoushi.top/Article/details/gt2elbplfnw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.feifeiyinyue.top/Article/details/gt2lliziiag.html

[Q11] 一次插入多行
来源：http://dali.jlsjyb.cn/Article/details/gt2szqxucia.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gotoacloud.top/Article/details/gt2woyjxjof.html

[Q12] 插入后取自增 ID
来源：http://dali.yj202588.top/Article/details/gt2obtgbfak.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.fengsongda.top/Article/details/gt2jsuyqely.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.kuanghao11.cn/Article/details/gt2sntpikgm.html

[Q13] 忽略重复插入
来源：http://dali.shzxlz.cn/Article/details/gt2bmsjfjrl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yvedp.cn/Article/details/gt2hxcjznxl.html

[Q14] 存在则更新（upsert）
来源：http://dali.havefunace.top/Article/details/gt2ppmfedcn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hongshengwenyu.top/Article/details/gt2witukhwp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ybcxt.top/Article/details/gt2zquvgfnz.html

[Q15] 查询全部
来源：http://dali.zhengqikj.top/Article/details/gt2itgffjbv.html

SELECT * FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2tadodrqn.html

[Q16] 查询指定列
来源：http://dali.kuanghao11.cn/Article/details/gt2yujfjojc.html

SELECT id, name FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ugbpcshy.html

[Q17] 条件查询
来源：http://dali.chenlongwang.top/Article/details/gt2chcvvrcc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj20258.top/Article/details/gt2aqhhvcwj.html

[Q18] 模糊匹配
来源：http://dali.meibo888.top/Article/details/gt2tqkvhzav.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.pycfn.com/Article/details/gt2dmazouwv.html

[Q19] 范围查询
来源：http://dali.jianghu66.top/Article/details/gt2bjmemybr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yuanzhike.top/Article/details/gt2umrgsgmm.html

[Q20] IN 列表
来源：http://dali.yueranfly.top/Article/details/gt2jphyvulc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.daria6918.cn/Article/details/gt2jbzaabmo.html

[Q21] 空值判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mnppgods.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenlongwang.top/Article/details/gt2vjdlqzxf.html

[Q22] 排序
来源：http://dali.andypj.xyz/Article/details/gt2exeykhnu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.havefunace.top/Article/details/gt2zqterago.html

[Q23] 分页
来源：http://dali.birdmap.top/Article/details/gt2lmslgcwq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.haohaochexian.top/Article/details/gt2ablhflgw.html

[Q24] 去重
来源：http://dali.hammf.cn/Article/details/gt2mshsrlry.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj20258.top/Article/details/gt2svcomtld.html

[Q25] 只取前 N 条
来源：http://dali.aizwys.cn/Article/details/gt2qinfnzsg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jyoumei.cn/Article/details/gt2gqxpzkpd.html

[Q26] 计数
来源：http://dali.haohaochexian.top/Article/details/gt2blkdgkmn.html

SELECT COUNT(*) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2iwjwycan.html

[Q27] 条件计数
来源：http://dali.jiagoushi.top/Article/details/gt2orzmkecm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2minajuzj.html

[Q28] 求和与平均
来源：http://dali.dianchejie.cn/Article/details/gt2bfzbwfwq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2meyuevfl.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2bguxmqmb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2fhowfrff.html

[Q30] 分组统计
来源：http://dali.gogol.net.cn/Article/details/gt2gafmjpty.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gt2qqoiegpn.html

[Q31] 分组后过滤
来源：http://dali.yueranfly.top/Article/details/gt2tsbxqipl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.daxiang520.top/Article/details/gt2uyaqfrmv.html

[Q32] 分组拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2zdfqbpwq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.iojbl.cn/Article/details/gt2szgzmlft.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cdnleiting.top/Article/details/gt2sbnvheuo.html

[Q33] 多列分组
来源：http://dali.shuidangran.top/Article/details/gt2ldtxirjl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.havefunace.top/Article/details/gt2vlhvpmoc.html

[Q34] 每组取第一条
来源：http://dali.xziqi.cn/Article/details/gt2xgutevox.html

SELECT * FROM (
来源：http://dali.aizwys.cn/Article/details/gt2jstgjysq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.aizwys.cn/Article/details/gt2xobccope.html

) t WHERE rn = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eyrmbsyr.html

[Q35] 内连接
来源：http://dali.gzhubu.top/Article/details/gt2jykgdwfh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgfzy.top/Article/details/gt2saqhtnvx.html

[Q36] 左连接
来源：http://dali.jianghu66.top/Article/details/gt2xaalpqzc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shangyingyoupin.top/Article/details/gt2wtnileaq.html

[Q37] 右连接
来源：http://dali.yonumen.top/Article/details/gt2keqlciil.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gogol.net.cn/Article/details/gt2luoqqtst.html


<!-- 参考信息 -->