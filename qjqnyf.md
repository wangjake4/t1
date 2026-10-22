代发 wailian999

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenlongwang.top/Article/details/gt2ujnthsux.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.quarkkingdee.top/Article/details/gt2gyskflya.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yvedp.cn/Article/details/gt2uvtrnefr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gt2lckrarro.html

[N05] 最大公约数
来源：http://dali.hywenlv.cn/Article/details/gt2pdwgxrfm.html

Py:   math.gcd(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gt2gfsdoafz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sxryk.cn/Article/details/gt2ampyknsl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ukwbxvyr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ybcxt.top/Article/details/gt2layntokw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yongpay.top/Article/details/gt2onmizlzg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hongshengwenyu.top/Article/details/gt2prgaxcfu.html

Ruby: a.gcd(b)
来源：http://dali.daxiang520.top/Article/details/gt2qassmeoh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hfpthk.cn/Article/details/gt2qfwffmyp.html

[N06] 判断回文字符串
来源：http://dali.mhx1999.top/Article/details/gt2wachslzj.html

Py:   s == s[::-1]
来源：http://dali.gogol.net.cn/Article/details/gt2wngsegqo.html

PHP:  $s === strrev($s);
来源：http://dali.xuanzx.com/Article/details/gt2ipiknsln.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gt2ytyfymsf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gt2hdiqeglg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xuanzx.com/Article/details/gt2mbgaoizv.html

Go:   // 双指针从两端比较
来源：http://dali.gogol.net.cn/Article/details/gt2hujoelhc.html

Ruby: s == s.reverse
来源：http://dali.zhongyouzk.top/Article/details/gt2iccjaksa.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.mhx1999.top/Article/details/gt2vvwrrmoa.html

[N07] 两数之和（返回下标）
来源：http://dali.jlsjyb.cn/Article/details/gt2ewmzdmnn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xziqi.cn/Article/details/gt2bzwfeaeq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hnqzz.top/Article/details/gt2kwhmiruu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yongpay.top/Article/details/gt2nqqtqxfn.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qxivouuo.html

Java: // 手写 HashMap
来源：http://dali.guowangkeji.top/Article/details/gt2nhrdzucd.html

Go:   // 手写 map[int]int
来源：http://dali.ivvv.top/Article/details/gt2mndhyfsf.html

Ruby: // 手写 Hash
来源：http://dali.hfpthk.cn/Article/details/gt2waashrgn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.pengpengdd.cyou/Article/details/gt2qekkqijv.html

[N08] 生成全排列
来源：http://dali.cheryme.top/Article/details/gt2qwbtowqw.html

Py:   itertools.permutations(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2wlgvpwrj.html

PHP:  // 手写递归交换
来源：http://dali.bjfxy.top/Article/details/gt2icdcyplt.html

JS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gt2ytsakqpm.html

TS:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gt2kmquiwpf.html

Java: // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gt2xpdxtfwt.html

Go:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gt2yyqwuibz.html

Ruby: arr.permutation.to_a
来源：http://dali.cashguo.top/Article/details/gt2zvhqzlzg.html

C#:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gt2arlshmcl.html

[N09] 栈与队列
来源：http://dali.zhixingplan.top/Article/details/gt2pwbymecq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zycfv.cn/Article/details/gt2fhwldjki.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gt2nwdcxzdw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gt2dylodqdy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.redwolf501.top/Article/details/gt2hcayupbp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jqgfzy.top/Article/details/gt2ukbcjalk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.c1oappe.top/Article/details/gt2xdrtmlfv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gt2txoelgdv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shangyingyoupin.top/Article/details/gt2rzsziclb.html

[N10] 链表节点定义
来源：http://dali.xziqi.cn/Article/details/gt2ezbqmxwz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hfpthk.cn/Article/details/gt2pvismnlq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xganqtrq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.c1oappe.top/Article/details/gt2jfzwprgm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yangfankeji.com/Article/details/gt2qwwyexud.html

Java: class Node { int v; Node next; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2gtxpwrvi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zycfv.cn/Article/details/gt2svracmqq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.fzhhl.top/Article/details/gt2yupgcztx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yonumen.top/Article/details/gt2bnwmriun.html

[N11] 二叉树中序遍历
来源：http://dali.havefunace.top/Article/details/gt2dtimnbmk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.nanxinkj.top/Article/details/gt2jldutaid.html

PHP:  // 手写递归函数
来源：http://dali.hammf.cn/Article/details/gt2iacnlmdz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenjidiqi.icu/Article/details/gt2nvtaryyh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hywenlv.cn/Article/details/gt2pnpcvdgt.html

Java: // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2yvdvinny.html

Go:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gt2umihqecl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2idbloune.html

C#:   // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gt2jvvtmtgy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.iojbl.cn/Article/details/gt2gnzlhgks.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hnxiangtu.top/Article/details/gt2qxsgequf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.guannengcc.top/Article/details/gt2jktmgzoz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.316326.xyz/Article/details/gt2lonjumzg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dashuyun.cn/Article/details/gt2wpzdjqut.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gt2dbidshtx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.mhx1999.top/Article/details/gt2cxnxnzvp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinqigfzy.top/Article/details/gt2nynejrxc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aizwys.cn/Article/details/gt2ptypdpqx.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2xpfjjrur.html

O. 并发与异步
来源：http://dali.yanxiufei.cn/Article/details/gt2vldtgcid.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2kgebzmnn.html

[O01] 启动一个线程
来源：http://dali.hysaishi.cn/Article/details/gt2vlspbnxo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yanxiufei.cn/Article/details/gt2nkhzbfts.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aibaodan.cn/Article/details/gt2fmcdlxug.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.feifeiyinyue.top/Article/details/gt2octahtip.html

TS:   // 同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gt2rugnewmg.html

Java: new Thread(() -> f()).start()
来源：http://dali.yuanzhike.top/Article/details/gt2nstrmcqx.html

Go:   go f()
来源：http://dali.hfpthk.cn/Article/details/gt2mcxvfefw.html

Ruby: Thread.new { f }
来源：http://dali.daria6918.cn/Article/details/gt2evzalihu.html

C#:   Task.Run(() => F());
来源：http://dali.aibaodan.cn/Article/details/gt2xtanqnlh.html

[O02] 使用线程池
来源：http://dali.cucudq.cn/Article/details/gt2zacbsqfg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.andypj.xyz/Article/details/gt2pztwsgap.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gzhubu.top/Article/details/gt2sihrzupq.html

JS:   // worker_threads 线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xnvhvxrf.html

TS:   // worker_threads 线程池
来源：http://dali.jinqigufen.top/Article/details/gt2byaikwmv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.snrcjt.cn/Article/details/gt2ngqxpzho.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.feifeiyinyue.top/Article/details/gt2pzugdsxk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nwbrower.top/Article/details/gt2ajfldjyt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.birdmap.top/Article/details/gt2phqrczjh.html

[O03] 加锁保护共享数据
来源：http://dali.tanke756.top/Article/details/gt2eeoldati.html

Py:   with lock: shared += 1
来源：http://dali.hfpthk.cn/Article/details/gt2eycafklr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hywenlv.cn/Article/details/gt2ipsyrqrp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.fengsongda.top/Article/details/gt2rnmxhtbi.html

TS:   // 同 JS
来源：http://dali.jqgufenzy.top/Article/details/gt2zcwqawip.html

Java: synchronized (this) { shared++; }
来源：http://dali.redwolf501.top/Article/details/gt2fhdpttvj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhoulong.xyz/Article/details/gt2wmbqxmrm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2nqhwhyfb.html

C#:   lock (gate) { shared++; }
来源：http://dali.daria6918.cn/Article/details/gt2kxjxfesv.html

[O04] 定义异步函数并等待
来源：http://dali.ydzc1.top/Article/details/gt2kdndantg.html

Py:   async def f():⏎    await g()
来源：http://dali.zycfv.cn/Article/details/gt2tqsmekqh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hywenlv.cn/Article/details/gt2xewqsbpz.html

JS:   async function f() { await g(); }
来源：http://dali.0kj1m.cn/Article/details/gt2omqvumyr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2asrpabmx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sufxvd.cn/Article/details/gt2jihmureg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zycfv.cn/Article/details/gt2auaxsway.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cqqwz.cn/Article/details/gt2utzpverm.html

C#:   async Task F() { await G(); }
来源：http://dali.hysaishi.cn/Article/details/gt2xxfsurio.html

[O05] 并发执行并等待全部完成
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lpgzvuif.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tanke756.top/Article/details/gt2ljdoxxbl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhixingplan.top/Article/details/gt2tipoekmg.html

JS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gt2mguudduu.html

TS:   await Promise.all(tasks)
来源：http://dali.cheryme.top/Article/details/gt2twquxrak.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yangfankeji.com/Article/details/gt2ycxcocuf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.aizwys.cn/Article/details/gt2polguovj.html

Ruby: threads.map(&:join)
来源：http://dali.nanxuanxn.top/Article/details/gt2ngwunyiy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yuanzhike.top/Article/details/gt2rdzlsznr.html

[O06] 使用进程池
来源：http://dali.zdqjudy.top/Article/details/gt2pemqndle.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tanke756.top/Article/details/gt2hhmgqhyx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hnxiangtu.top/Article/details/gt2eeiwvrud.html

JS:   // child_process / cluster 模块
来源：http://dali.feifeiyinyue.top/Article/details/gt2yhkollkq.html

TS:   // child_process / cluster 模块
来源：http://dali.ivvv.top/Article/details/gt2zxzcglbw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.9152youxi.cn/Article/details/gt2wxfrjoki.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhoulong.xyz/Article/details/gt2qsbywspt.html

Ruby: // fork 块
来源：http://dali.nwbrower.top/Article/details/gt2daezhyzb.html

C#:   Parallel.For
来源：http://dali.birdmap.top/Article/details/gt2oodtobfm.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2swysrgiz.html

P. 常用工具函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2cxhjrqwc.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2lsmeeugg.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2rslckhyr.html

Py:   str(uuid.uuid4())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cffvoyby.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ppjwa.cn/Article/details/gt2hnimttxk.html

JS:   crypto.randomUUID()
来源：http://dali.haohaochexian.top/Article/details/gt2hfurqdvu.html

TS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gt2owpabcwe.html

Java: UUID.randomUUID().toString()
来源：http://dali.iojbl.cn/Article/details/gt2arwznqaf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xuanzx.com/Article/details/gt2igedvzut.html

Ruby: SecureRandom.uuid
来源：http://dali.hammf.cn/Article/details/gt2tycssrew.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aenoazfy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tanke756.top/Article/details/gt2feizszvw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.daria6918.cn/Article/details/gt2squxmahp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hywenlv.cn/Article/details/gt2fygbxmnu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.snrcjt.cn/Article/details/gt2awkizfoh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zycfv.cn/Article/details/gt2uofgvnqy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xgazivnm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.snrcjt.cn/Article/details/gt2fsfwdklx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ehwqpu.com/Article/details/gt2ienddnpx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.dashuyun.cn/Article/details/gt2plmdscws.html

[P03] 生成短随机字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2knfgjzbf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gotoacloud.top/Article/details/gt2koobyoyh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ybcxt.top/Article/details/gt2wqdhcxiv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ybcxt.top/Article/details/gt2nhqxwcsp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ypippgqf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xinyue.icu/Article/details/gt2sjgqtyqb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zycfv.cn/Article/details/gt2bouzisou.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.bjfxy.top/Article/details/gt2jaboodhh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.svipenyu.cn/Article/details/gt2ywcxsvrp.html

[P04] 求长度
来源：http://dali.fzhhl.top/Article/details/gt2xfwntjcm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hongshengwenyu.top/Article/details/gt2flhlcnnh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gt2mgkgaiub.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhiwuduotai.top/Article/details/gt2ykgfpkbi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnqzz.top/Article/details/gt2phgvjczs.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cucudq.cn/Article/details/gt2zhrkjfsm.html

Go:   len(arr);  len(m)
来源：http://dali.guannengcc.top/Article/details/gt2hciowzzm.html

Ruby: x.length;  x.size
来源：http://dali.nanxinkj.top/Article/details/gt2aounegrv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yonumen.top/Article/details/gt2tpbnxrug.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hfpthk.cn/Article/details/gt2pdbpltrr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hfpthk.cn/Article/details/gt2fjlikqzn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jqgufenzy.top/Article/details/gt2aimaqzgm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hysaishi.cn/Article/details/gt2lfvcjnnl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dashuyun.cn/Article/details/gt2mvqrthpb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yueranfly.top/Article/details/gt2nymsykec.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.nwbrower.top/Article/details/gt2fzdlohps.html

Ruby: a == b
来源：http://dali.fzhhl.top/Article/details/gt2nbdcdwgt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ivvv.top/Article/details/gt2ovydoscf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ppjwa.cn/Article/details/gt2uenplell.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ehwqpu.com/Article/details/gt2qgfxfunv.html

PHP:  if (empty($x)) {}
来源：http://dali.ydzc1.top/Article/details/gt2xwkniipq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ydzc1.top/Article/details/gt2arzciqht.html

TS:   if (x == null) {}
来源：http://dali.mhx1999.top/Article/details/gt2uzwiryhl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yueranfly.top/Article/details/gt2delascns.html

Go:   if x == nil {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ljqdbzln.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.andypj.xyz/Article/details/gt2jnfnpruy.html

C#:   if (x is null) {}
来源：http://dali.sysykeji.top/Article/details/gt2drjrscah.html

[P07] 防抖与节流
来源：http://dali.nanxuanxn.top/Article/details/gt2ycwxgynf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yuanzhike.top/Article/details/gt2ualjnifb.html

PHP:  // 手写时间戳比较
来源：http://dali.zhixingplan.top/Article/details/gt2urcypyso.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gt2etroywgg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gogol.net.cn/Article/details/gt2fstfldtt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2tpcmtcle.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gotoacloud.top/Article/details/gt2egpjxell.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2afwtjwng.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.tian-w.cn/Article/details/gt2muixrscd.html

[P08] 处理浮点精度问题
来源：http://dali.wangshuangyany.cn/Article/details/gt2vuoffxzl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sysykeji.top/Article/details/gt2hbpwduea.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xuanzx.com/Article/details/gt2ftoetedc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.fzhhl.top/Article/details/gt2agkfflku.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mooltbdz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yongpay.top/Article/details/gt2siwmobsr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cashguo.top/Article/details/gt2ptlhwbro.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zycfv.cn/Article/details/gt2moxcyzlg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aqkfdbri.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2idzviwcw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sufxvd.cn/Article/details/gt2awvsawbz.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2qbxryiaf.html

[Q01] 创建表
来源：http://dali.zdqjudy.top/Article/details/gt2zwudhull.html

CREATE TABLE users (
来源：http://dali.fzhhl.top/Article/details/gt2gvdijwig.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnxiangtu.top/Article/details/gt2txtlhlbc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhengqikj.top/Article/details/gt2qqtgcvcn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cucudq.cn/Article/details/gt2agruhzkg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.redwolf501.top/Article/details/gt2lstozkum.html

);
来源：http://dali.smart0.xyz/Article/details/gt2ngrnhpqu.html

[Q02] 创建带外键的表
来源：http://dali.zhoulong.xyz/Article/details/gt2hvbunmad.html

CREATE TABLE orders (
来源：http://dali.yanxiufei.cn/Article/details/gt2xctpntwu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sweek.top/Article/details/gt2ipmoaoyj.html

user_id INT NOT NULL,
来源：http://dali.yonumen.top/Article/details/gt2estkqczq.html

amount DECIMAL(10, 2),
来源：http://dali.svipenyu.cn/Article/details/gt2ughqnsnw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.9152youxi.cn/Article/details/gt2fhnlwafm.html

);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uixjzcda.html

[Q03] 增加列
来源：http://dali.kuanghao11.cn/Article/details/gt2xbwyyvsh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.0kj1m.cn/Article/details/gt2nkwvhlyb.html

[Q04] 修改列类型
来源：http://dali.yuxming.cn/Article/details/gt2rwwmnoqx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yueranfly.top/Article/details/gt2bcnnncyw.html

[Q05] 重命名列
来源：http://dali.tianlin.xyz/Article/details/gt2kagbmfdr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.svipenyu.cn/Article/details/gt2odjatrtx.html

[Q06] 删除列
来源：http://dali.zdqjudy.top/Article/details/gt2izzoyodu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gogol.net.cn/Article/details/gt2akhlmjjo.html

[Q07] 删除表
来源：http://dali.snrcjt.cn/Article/details/gt2hidzigme.html

DROP TABLE IF EXISTS orders;
来源：http://dali.fzhhl.top/Article/details/gt2kfrhwjek.html

[Q08] 创建普通索引
来源：http://dali.xuetiantiany.cn/Article/details/gt2zbljfnbw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.smart0.xyz/Article/details/gt2auabjssp.html

[Q09] 创建唯一索引
来源：http://dali.dianchejie.cn/Article/details/gt2imdwaspl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yanxiufei.cn/Article/details/gt2danyjoov.html

[Q10] 插入单行
来源：http://dali.sxryk.cn/Article/details/gt2oastpcpd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ydzc1.top/Article/details/gt2ajuivgbr.html

[Q11] 一次插入多行
来源：http://dali.bjfxy.top/Article/details/gt2diattbll.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.meibo888.top/Article/details/gt2ymfmbuow.html

[Q12] 插入后取自增 ID
来源：http://dali.pengpengdd.cyou/Article/details/gt2mcryjdhl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yangfankeji.com/Article/details/gt2mojpxlsv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jlsjyb.cn/Article/details/gt2oherwqau.html

[Q13] 忽略重复插入
来源：http://dali.sysykeji.top/Article/details/gt2adqpsbja.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.birdmap.top/Article/details/gt2yqatlrxa.html

[Q14] 存在则更新（upsert）
来源：http://dali.hammf.cn/Article/details/gt2cvrtrlew.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.wangshuangyany.cn/Article/details/gt2tpmnfmvn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ydzc1.top/Article/details/gt2uocvmzpb.html

[Q15] 查询全部
来源：http://dali.ehwqpu.com/Article/details/gt2ubinrery.html

SELECT * FROM users;
来源：http://dali.cashguo.top/Article/details/gt2ekcyprxc.html

[Q16] 查询指定列
来源：http://dali.shzxlz.cn/Article/details/gt2sshclfiq.html

SELECT id, name FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2vrxjtwtm.html

[Q17] 条件查询
来源：http://dali.guowangkeji.top/Article/details/gt2iarckpdi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.meibo888.top/Article/details/gt2pqzwplvd.html

[Q18] 模糊匹配
来源：http://dali.jqgfzy.top/Article/details/gt2wflkmjdd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhongyouzk.top/Article/details/gt2gqvsgblb.html

[Q19] 范围查询
来源：http://dali.guannengcc.top/Article/details/gt2vchgwdls.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.feifeiyinyue.top/Article/details/gt2cbhdjabu.html

[Q20] IN 列表
来源：http://dali.yanxiufei.cn/Article/details/gt2wtgmpeyx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xuanzx.com/Article/details/gt2yyuvcneh.html

[Q21] 空值判断
来源：http://dali.tianlin.xyz/Article/details/gt2ctuqczrx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yongpay.top/Article/details/gt2dzokkzgw.html

[Q22] 排序
来源：http://dali.ydzc1.top/Article/details/gt2tndqebzw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yuxming.cn/Article/details/gt2gkbkosvy.html

[Q23] 分页
来源：http://dali.yuanzhike.top/Article/details/gt2zzdhigch.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenlongwang.top/Article/details/gt2vbrysdir.html

[Q24] 去重
来源：http://dali.guannengcc.top/Article/details/gt2yfnjowvz.html

SELECT DISTINCT city FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2horerzaw.html

[Q25] 只取前 N 条
来源：http://dali.hysaishi.cn/Article/details/gt2kyguwlij.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ppjwa.cn/Article/details/gt2avpsieae.html

[Q26] 计数
来源：http://dali.vqdsnc.cn/Article/details/gt2gztqwxis.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2csgzwrvw.html

[Q27] 条件计数
来源：http://dali.yj20258.top/Article/details/gt2wekdzryd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2ymwvkzsf.html

[Q28] 求和与平均
来源：http://dali.0kj1m.cn/Article/details/gt2yrflghtx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2tipztfmo.html

[Q29] 最大最小值
来源：http://dali.zycfv.cn/Article/details/gt2qxqnanzx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.birdmap.top/Article/details/gt2czflyywp.html

[Q30] 分组统计
来源：http://dali.0kj1m.cn/Article/details/gt2tvxicjsn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gt2utijbbzo.html

[Q31] 分组后过滤
来源：http://dali.yj202588.top/Article/details/gt2rarfxths.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ehwqpu.com/Article/details/gt2advbodlj.html

[Q32] 分组拼接字符串
来源：http://dali.sysykeji.top/Article/details/gt2wgwnqkwe.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gt2hdnocrcl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj20258.top/Article/details/gt2rajagyro.html

[Q33] 多列分组
来源：http://dali.tanke756.top/Article/details/gt2zbxjtjei.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jlsjyb.cn/Article/details/gt2jkqwdujj.html

[Q34] 每组取第一条
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cfqqmyxs.html

SELECT * FROM (
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xbxfvcqv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yongpay.top/Article/details/gt2dsqgvlpr.html

) t WHERE rn = 1;
来源：http://dali.shuidangran.top/Article/details/gt2scmlhqoz.html

[Q35] 内连接
来源：http://dali.fzhhl.top/Article/details/gt2pglilnii.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.svipenyu.cn/Article/details/gt2rqagmzot.html

[Q36] 左连接
来源：http://dali.hnqzz.top/Article/details/gt2lfqanlrp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.c1oappe.top/Article/details/gt2nzeflsvz.html

[Q37] 右连接
来源：http://dali.9152youxi.cn/Article/details/gt2myysyure.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ybcxt.top/Article/details/gt2crumkgtk.html


<!-- 参考信息 -->