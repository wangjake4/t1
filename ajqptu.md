代发 wailian999

[N05] 最大公约数
来源：http://dali.hywenlv.cn/Article/details/gt2mjuhughm.html

Py:   math.gcd(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dlrltspv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shuidangran.top/Article/details/gt2booygjon.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhixingplan.top/Article/details/gt2uztdtupg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gt2seatxvwt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yueranfly.top/Article/details/gt2yjvtglji.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.vqdsnc.cn/Article/details/gt2mfjgcxlk.html

Ruby: a.gcd(b)
来源：http://dali.chenzaomai.com/Article/details/gt2dyiaixmx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yanxiufei.cn/Article/details/gt2exexfzvx.html

[N06] 判断回文字符串
来源：http://dali.yueranfly.top/Article/details/gt2qiqzhjqb.html

Py:   s == s[::-1]
来源：http://dali.tian-w.cn/Article/details/gt2dprgnxuu.html

PHP:  $s === strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gt2wxbsdihi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gt2xjcloolo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gt2cjxrlewp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yuanzhike.top/Article/details/gt2dgcdksny.html

Go:   // 双指针从两端比较
来源：http://dali.yanxiufei.cn/Article/details/gt2mdnvcnaf.html

Ruby: s == s.reverse
来源：http://dali.redwolf501.top/Article/details/gt2lnlqakvt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.fzhhl.top/Article/details/gt2hlqbirvf.html

[N07] 两数之和（返回下标）
来源：http://dali.pengpengdd.cyou/Article/details/gt2ljxbqxkk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sufxvd.cn/Article/details/gt2yjimkfdg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.chenlongwang.top/Article/details/gt2cdxjlitv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cucudq.cn/Article/details/gt2szevxvyt.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sjmruilt.html

Java: // 手写 HashMap
来源：http://dali.yj20258.top/Article/details/gt2ctoimwgc.html

Go:   // 手写 map[int]int
来源：http://dali.birdmap.top/Article/details/gt2vzszoyxl.html

Ruby: // 手写 Hash
来源：http://dali.xuetiantiany.cn/Article/details/gt2zrluoirr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ppjwa.cn/Article/details/gt2mtsgxfse.html

[N08] 生成全排列
来源：http://dali.ehwqpu.com/Article/details/gt2hknfavvv.html

Py:   itertools.permutations(arr)
来源：http://dali.guannengcc.top/Article/details/gt2dikqmbjx.html

PHP:  // 手写递归交换
来源：http://dali.chenjidiqi.icu/Article/details/gt2jldkqnlm.html

JS:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2koheyvgd.html

TS:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dlexmyqf.html

Java: // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gt2pnntwbek.html

Go:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gt2mnddhzkn.html

Ruby: arr.permutation.to_a
来源：http://dali.quarkkingdee.top/Article/details/gt2nngejhvs.html

C#:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gt2mktietnz.html

[N09] 栈与队列
来源：http://dali.yueranfly.top/Article/details/gt2qzhdymdd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.svipenyu.cn/Article/details/gt2mndrfvdv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jyoumei.cn/Article/details/gt2adncwwus.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gt2zchyoiso.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xuanzx.com/Article/details/gt2uyjnbzgm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sxryk.cn/Article/details/gt2vbdlvwvo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gzhubu.top/Article/details/gt2zctnijqf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gt2falvqzmo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.haohaochexian.top/Article/details/gt2guveztou.html

[N10] 链表节点定义
来源：http://dali.dashuyun.cn/Article/details/gt2hfeibvwf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenlongwang.top/Article/details/gt2unuobgrx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ulebyrab.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cashguo.top/Article/details/gt2tyihqeze.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.havefunace.top/Article/details/gt2hytezgsh.html

Java: class Node { int v; Node next; }
来源：http://dali.sufxvd.cn/Article/details/gt2wzjmcjaj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jiagoushi.top/Article/details/gt2wwjswdel.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.c1oappe.top/Article/details/gt2ridwkefu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenzaomai.com/Article/details/gt2xasbghim.html

[N11] 二叉树中序遍历
来源：http://dali.jqgfzy.top/Article/details/gt2vlcppmcy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ydzc1.top/Article/details/gt2paienzit.html

PHP:  // 手写递归函数
来源：http://dali.jqgufenzy.top/Article/details/gt2cxthoakn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhiwuduotai.top/Article/details/gt2vjymsaet.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ybcxt.top/Article/details/gt2nvxzdloj.html

Java: // 手写递归
来源：http://dali.fzhhl.top/Article/details/gt2drnbatgu.html

Go:   // 手写递归
来源：http://dali.wangdashe.top/Article/details/gt2sjyzppzy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hongshengwenyu.top/Article/details/gt2ebbwxkqb.html

C#:   // 手写递归
来源：http://dali.fzhhl.top/Article/details/gt2lpxldcbn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sufxvd.cn/Article/details/gt2bufetvoq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nwbrower.top/Article/details/gt2xfqplatl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.tianlin.xyz/Article/details/gt2jtdohoiy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigfzy.top/Article/details/gt2dgsqecga.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hammf.cn/Article/details/gt2osicycza.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fengsongda.top/Article/details/gt2pcljtqjl.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.snrcjt.cn/Article/details/gt2bnrxozbn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.wangdashe.top/Article/details/gt2fmgemrzp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ppjwa.cn/Article/details/gt2ugmjrkut.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2wslnazrf.html

O. 并发与异步
来源：http://dali.yanxiufei.cn/Article/details/gt2migpzddz.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2eupucioc.html

[O01] 启动一个线程
来源：http://dali.bjfxy.top/Article/details/gt2swkzjkne.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.andypj.xyz/Article/details/gt2mdsgvpob.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2prmfctqo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj20258888.top/Article/details/gt2mjaccoss.html

TS:   // 同 JS
来源：http://dali.hywenlv.cn/Article/details/gt2tkhbumbw.html

Java: new Thread(() -> f()).start()
来源：http://dali.meibo888.top/Article/details/gt2xazaradj.html

Go:   go f()
来源：http://dali.yonumen.top/Article/details/gt2jjbhwshc.html

Ruby: Thread.new { f }
来源：http://dali.dashuyun.cn/Article/details/gt2wkqolhkf.html

C#:   Task.Run(() => F());
来源：http://dali.jqgfzy.top/Article/details/gt2brnmmewt.html

[O02] 使用线程池
来源：http://dali.dianchejie.cn/Article/details/gt2aushqrlj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.haohaochexian.top/Article/details/gt2ydgjosun.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hywenlv.cn/Article/details/gt2ybzbmotq.html

JS:   // worker_threads 线程池
来源：http://dali.pengpengdd.cyou/Article/details/gt2beibjyte.html

TS:   // worker_threads 线程池
来源：http://dali.dianchejie.cn/Article/details/gt2ldetjxge.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.daxiang520.top/Article/details/gt2kqculqml.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cheryme.top/Article/details/gt2oinobjwz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenzaomai.com/Article/details/gt2emkemywc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.nwbrower.top/Article/details/gt2bsaplbtf.html

[O03] 加锁保护共享数据
来源：http://dali.tian-w.cn/Article/details/gt2bxdaauoi.html

Py:   with lock: shared += 1
来源：http://dali.c1oappe.top/Article/details/gt2xlucxrpw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hongshengwenyu.top/Article/details/gt2oyxflogd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ybcxt.top/Article/details/gt2cszusqcv.html

TS:   // 同 JS
来源：http://dali.xylfe.cn/Article/details/gt2dhaugzll.html

Java: synchronized (this) { shared++; }
来源：http://dali.ybcxt.top/Article/details/gt2dquiymlf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shuidangran.top/Article/details/gt2oxlqnafz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yuanzhike.top/Article/details/gt2cvnrblyr.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj202588.top/Article/details/gt2vbdssizq.html

[O04] 定义异步函数并等待
来源：http://dali.fzhhl.top/Article/details/gt2avynrzfj.html

Py:   async def f():⏎    await g()
来源：http://dali.aibaodan.cn/Article/details/gt2sjbaasvz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.meibo888.top/Article/details/gt2nmhiscxq.html

JS:   async function f() { await g(); }
来源：http://dali.zdqjudy.top/Article/details/gt2nfeiiqwt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xuanzx.com/Article/details/gt2qvrefxxj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hysaishi.cn/Article/details/gt2ibtduxrv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinqigfzy.top/Article/details/gt2ajdmrcwz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hfpthk.cn/Article/details/gt2aefhnigs.html

C#:   async Task F() { await G(); }
来源：http://dali.smart0.xyz/Article/details/gt2izlvdrtp.html

[O05] 并发执行并等待全部完成
来源：http://dali.aibaodan.cn/Article/details/gt2qsnhvpwe.html

Py:   asyncio.gather(*tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jvaaojsb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hysaishi.cn/Article/details/gt2pcueabic.html

JS:   await Promise.all(tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ljywzuiu.html

TS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gt2yjslffzq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuanzhike.top/Article/details/gt2weykcddo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yongpay.top/Article/details/gt2mqyzaajb.html

Ruby: threads.map(&:join)
来源：http://dali.sysykeji.top/Article/details/gt2mqxpdnif.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.redwolf501.top/Article/details/gt2uhireusm.html

[O06] 使用进程池
来源：http://dali.zhengqikj.top/Article/details/gt2dvziipvo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tianlin.xyz/Article/details/gt2nueeejna.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ybcxt.top/Article/details/gt2nbfnwhev.html

JS:   // child_process / cluster 模块
来源：http://dali.svipenyu.cn/Article/details/gt2cwkpyjch.html

TS:   // child_process / cluster 模块
来源：http://dali.wangshuangyany.cn/Article/details/gt2egbsvsuw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenjidiqi.icu/Article/details/gt2weagzgmq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jitijhcr.html

Ruby: // fork 块
来源：http://dali.kuanghao11.cn/Article/details/gt2vvrybsli.html

C#:   Parallel.For
来源：http://dali.yvedp.cn/Article/details/gt2rczpeppe.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2pgfvzlqt.html

P. 常用工具函数
来源：http://dali.daxiang520.top/Article/details/gt2gozmdklh.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2iwrectiu.html

[P01] 生成 UUID
来源：http://dali.sxryk.cn/Article/details/gt2cjdlazmh.html

Py:   str(uuid.uuid4())
来源：http://dali.iojbl.cn/Article/details/gt2ldfzrxeh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.guowangkeji.top/Article/details/gt2awglmsod.html

JS:   crypto.randomUUID()
来源：http://dali.jinqigufen.top/Article/details/gt2fphphbdy.html

TS:   crypto.randomUUID()
来源：http://dali.yuanzhike.top/Article/details/gt2yzzyhkui.html

Java: UUID.randomUUID().toString()
来源：http://dali.guannengcc.top/Article/details/gt2hkqyjbsa.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yueranfly.top/Article/details/gt2jqbywaix.html

Ruby: SecureRandom.uuid
来源：http://dali.sxryk.cn/Article/details/gt2jkvdjkrm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhongyouzk.top/Article/details/gt2kmcefxhk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gzhubu.top/Article/details/gt2qlfrwolu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shangyingyoupin.top/Article/details/gt2jtfkhxqd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2mchkwjik.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cucudq.cn/Article/details/gt2pleltikx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2euppqmdo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ybcxt.top/Article/details/gt2mzfxdwup.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cheryme.top/Article/details/gt2evozaikk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgfzy.top/Article/details/gt2jubkpaza.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hammf.cn/Article/details/gt2ftvwdqau.html

[P03] 生成短随机字符串
来源：http://dali.zycfv.cn/Article/details/gt2rloriaxh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuanzx.com/Article/details/gt2ohohdvdv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tanke756.top/Article/details/gt2nozkflyg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gogol.net.cn/Article/details/gt2lszfdpxc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hysaishi.cn/Article/details/gt2oqqudeyy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhixingplan.top/Article/details/gt2ipbsrout.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.chenzaomai.com/Article/details/gt2kmibgtsk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pltocjwq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.wangdashe.top/Article/details/gt2bzqhfuet.html

[P04] 求长度
来源：http://dali.xziqi.cn/Article/details/gt2fczlhejc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.andypj.xyz/Article/details/gt2hzvmbqre.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iypefvjf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yanxiufei.cn/Article/details/gt2wwsoubhz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shzxlz.cn/Article/details/gt2jbsqlphw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.dianchejie.cn/Article/details/gt2oauurrmz.html

Go:   len(arr);  len(m)
来源：http://dali.tianlin.xyz/Article/details/gt2oknpnopc.html

Ruby: x.length;  x.size
来源：http://dali.dashuyun.cn/Article/details/gt2djfpcnza.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.dianchejie.cn/Article/details/gt2lthcmnjc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shangyingyoupin.top/Article/details/gt2tgcaizel.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hywenlv.cn/Article/details/gt2nvgisnpl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zycfv.cn/Article/details/gt2cwwucdii.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jqgfzy.top/Article/details/gt2vkqdcmao.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxinkj.top/Article/details/gt2ptkqzukj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jrcwobro.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj20258888.top/Article/details/gt2mhojeowp.html

Ruby: a == b
来源：http://dali.snrcjt.cn/Article/details/gt2vnuvrkey.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tian-w.cn/Article/details/gt2lmzowsgu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhengqikj.top/Article/details/gt2alqqauvm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cqqwz.cn/Article/details/gt2wzufldvb.html

PHP:  if (empty($x)) {}
来源：http://dali.chenlongwang.top/Article/details/gt2ofwfznnj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.daria6918.cn/Article/details/gt2ucfmaleb.html

TS:   if (x == null) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2ubkbpspg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2emdyjlod.html

Go:   if x == nil {}
来源：http://dali.hnqzz.top/Article/details/gt2jfrifnby.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xziqi.cn/Article/details/gt2tmnkjlxq.html

C#:   if (x is null) {}
来源：http://dali.shzxlz.cn/Article/details/gt2vhwrraaq.html

[P07] 防抖与节流
来源：http://dali.xuetiantiany.cn/Article/details/gt2grgbylld.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nuqmwvlw.html

PHP:  // 手写时间戳比较
来源：http://dali.gzhubu.top/Article/details/gt2ncpuvgkq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgufenzy.top/Article/details/gt2wjuekmkv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cheryme.top/Article/details/gt2zaprcspv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.c1oappe.top/Article/details/gt2zhjkjuhl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xziqi.cn/Article/details/gt2ymrrxpoz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj20258.top/Article/details/gt2kyozyine.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xuanzx.com/Article/details/gt2ndxbwffg.html

[P08] 处理浮点精度问题
来源：http://dali.zhongyouzk.top/Article/details/gt2alnbhefe.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jyoumei.cn/Article/details/gt2jdzsgjhw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hfpthk.cn/Article/details/gt2gtpptfpb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ehwqpu.com/Article/details/gt2jrkeahsg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ebgraojq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.aizwys.cn/Article/details/gt2mhgzgeps.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhixingplan.top/Article/details/gt2bqbgueqf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jyoumei.cn/Article/details/gt2erubohyb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.havefunace.top/Article/details/gt2bbppqcdj.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2ltdolske.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.haohaochexian.top/Article/details/gt2idtxkcgc.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2hwacmprr.html

[Q01] 创建表
来源：http://dali.zhongyouzk.top/Article/details/gt2wqsiexsp.html

CREATE TABLE users (
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kajilbvx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fengsongda.top/Article/details/gt2pbmlxusv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.meibo888.top/Article/details/gt2jscljiuu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.aizwys.cn/Article/details/gt2oybfcswz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jqgufenzy.top/Article/details/gt2lhnbuezo.html

);
来源：http://dali.wangdashe.top/Article/details/gt2wrrhipfw.html

[Q02] 创建带外键的表
来源：http://dali.zhongyouzk.top/Article/details/gt2riqweiuh.html

CREATE TABLE orders (
来源：http://dali.iojbl.cn/Article/details/gt2vligjgfi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.316326.xyz/Article/details/gt2keeiieou.html

user_id INT NOT NULL,
来源：http://dali.chenlongwang.top/Article/details/gt2upeqmxof.html

amount DECIMAL(10, 2),
来源：http://dali.xinyue.icu/Article/details/gt2fjecsvxn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yaofueme.html

);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ygtsreab.html

[Q03] 增加列
来源：http://dali.jinqigfzy.top/Article/details/gt2lqfwklvz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yuanzhike.top/Article/details/gt2ttzjohpw.html

[Q04] 修改列类型
来源：http://dali.ppjwa.cn/Article/details/gt2opzriabs.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xuanzx.com/Article/details/gt2caojqxlc.html

[Q05] 重命名列
来源：http://dali.hfpthk.cn/Article/details/gt2yqqfxdrl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yj202588.top/Article/details/gt2qkrvwsvh.html

[Q06] 删除列
来源：http://dali.xuetiantiany.cn/Article/details/gt2rkpnuvwy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hysaishi.cn/Article/details/gt2bovanduf.html

[Q07] 删除表
来源：http://dali.zhongyouzk.top/Article/details/gt2lwpjqvkd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenzaomai.com/Article/details/gt2qbkpgkzz.html

[Q08] 创建普通索引
来源：http://dali.shangyingyoupin.top/Article/details/gt2ffzthmrx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhengqikj.top/Article/details/gt2xiwglrzu.html

[Q09] 创建唯一索引
来源：http://dali.haohaochexian.top/Article/details/gt2wbsxbdfk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yj20258888.top/Article/details/gt2ncyswtxo.html

[Q10] 插入单行
来源：http://dali.sxryk.cn/Article/details/gt2opkaandk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zdqjudy.top/Article/details/gt2hrfetvhw.html

[Q11] 一次插入多行
来源：http://dali.vqdsnc.cn/Article/details/gt2fzdskgjz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.aibaodan.cn/Article/details/gt2cjsucymc.html

[Q12] 插入后取自增 ID
来源：http://dali.jqgufenzy.top/Article/details/gt2guegwzty.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ydzc1.top/Article/details/gt2igxcfhbx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hongshengwenyu.top/Article/details/gt2tvoxtdot.html

[Q13] 忽略重复插入
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ptycixdq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.smart0.xyz/Article/details/gt2jiiriapp.html

[Q14] 存在则更新（upsert）
来源：http://dali.pycfn.com/Article/details/gt2yyfnkggh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cheryme.top/Article/details/gt2pwklgicy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tianlin.xyz/Article/details/gt2rwxuiotv.html

[Q15] 查询全部
来源：http://dali.yuxming.cn/Article/details/gt2ayrugnoy.html

SELECT * FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2pruaipdw.html

[Q16] 查询指定列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qyqtrpaf.html

SELECT id, name FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2bylvsssr.html

[Q17] 条件查询
来源：http://dali.kuanghao11.cn/Article/details/gt2orjzvomu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yanxiufei.cn/Article/details/gt2dpvntjxa.html

[Q18] 模糊匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gt2heyxfdfo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhoulong.xyz/Article/details/gt2yvzaygmg.html

[Q19] 范围查询
来源：http://dali.kuanghao11.cn/Article/details/gt2uayjufvl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nanxinkj.top/Article/details/gt2uvgvkyvb.html

[Q20] IN 列表
来源：http://dali.hnqzz.top/Article/details/gt2jdmzfaej.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tian-w.cn/Article/details/gt2munmelmk.html

[Q21] 空值判断
来源：http://dali.nanxinkj.top/Article/details/gt2zvdvpcdb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.iojbl.cn/Article/details/gt2ybtxasaw.html

[Q22] 排序
来源：http://dali.vqdsnc.cn/Article/details/gt2dlweqlnn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shuidangran.top/Article/details/gt2ftmupurv.html

[Q23] 分页
来源：http://dali.nanxuanxn.top/Article/details/gt2upasddcm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhoulong.xyz/Article/details/gt2oklsuzzf.html

[Q24] 去重
来源：http://dali.jinqigufen.top/Article/details/gt2hhdfpkki.html

SELECT DISTINCT city FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2rhwghlzk.html

[Q25] 只取前 N 条
来源：http://dali.kuanghao11.cn/Article/details/gt2hxjlrtri.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.fengsongda.top/Article/details/gt2msnuwgqa.html

[Q26] 计数
来源：http://dali.hammf.cn/Article/details/gt2uyvxrzqy.html

SELECT COUNT(*) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2jaxsjzrw.html

[Q27] 条件计数
来源：http://dali.xziqi.cn/Article/details/gt2yvmpjbto.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2fmccwavr.html

[Q28] 求和与平均
来源：http://dali.nwbrower.top/Article/details/gt2flhaocua.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gt2zoilgdwd.html

[Q29] 最大最小值
来源：http://dali.yj202588.top/Article/details/gt2eiavbzpg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2gdisvlfn.html

[Q30] 分组统计
来源：http://dali.pycfn.com/Article/details/gt2ugctbxbh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gt2owkhftrr.html

[Q31] 分组后过滤
来源：http://dali.pengpengdd.cyou/Article/details/gt2gkwqkzvl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.meibo888.top/Article/details/gt2lobcsagt.html

[Q32] 分组拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2qjokfbbc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.andypj.xyz/Article/details/gt2nfhmqlqr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ulfzmpfd.html

[Q33] 多列分组
来源：http://dali.tianlin.xyz/Article/details/gt2chgdktqp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hammf.cn/Article/details/gt2kstllcoh.html

[Q34] 每组取第一条
来源：http://dali.havefunace.top/Article/details/gt2qmnvcykr.html

SELECT * FROM (
来源：http://dali.daxiang520.top/Article/details/gt2brkqgxov.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xylfe.cn/Article/details/gt2kcouueay.html

) t WHERE rn = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gulvfgtb.html

[Q35] 内连接
来源：http://dali.fengsongda.top/Article/details/gt2unnungqu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jlsjyb.cn/Article/details/gt2dqksinpk.html

[Q36] 左连接
来源：http://dali.cashguo.top/Article/details/gt2wsedipli.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yangfankeji.com/Article/details/gt2nqfqlwan.html

[Q37] 右连接
来源：http://dali.zhengqikj.top/Article/details/gt2omicuasj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.bjfxy.top/Article/details/gt2qkkfpzlp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.andypj.xyz/Article/details/gt2fbdxpsqe.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jzluegex.html

[Q39] 自连接（查上下级）
来源：http://dali.zycfv.cn/Article/details/gt2mosegkkx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.meibo888.top/Article/details/gt2itoaobmj.html


<!-- 参考信息 -->