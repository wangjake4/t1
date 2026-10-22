代发 wailian999

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gelstqnw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gt2kyrihxkr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gt2igncmzoc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cqqwz.cn/Article/details/gt2ekdpjchl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.mhx1999.top/Article/details/gt2mgniijkd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xinyue.icu/Article/details/gt2rmgbvrmd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.svipenyu.cn/Article/details/gt2pgiejlkw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gt2vfeuklih.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2htpqlmet.html

Py:   math.gcd(a, b)
来源：http://dali.daria6918.cn/Article/details/gt2oqjcugom.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yuanzhike.top/Article/details/gt2vnlgysmv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yangfankeji.com/Article/details/gt2kykcbehc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fzhhl.top/Article/details/gt2uioxagyy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.bjfxy.top/Article/details/gt2xplxgvpd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hammf.cn/Article/details/gt2gxctgrwq.html

Ruby: a.gcd(b)
来源：http://dali.fengsongda.top/Article/details/gt2rpqjhrut.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yj20258888.top/Article/details/gt2xxovrhov.html

[N06] 判断回文字符串
来源：http://dali.birdmap.top/Article/details/gt2zhvrezuu.html

Py:   s == s[::-1]
来源：http://dali.jinqigfzy.top/Article/details/gt2dqekgjdk.html

PHP:  $s === strrev($s);
来源：http://dali.aibaodan.cn/Article/details/gt2glxwldjy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gt2zximyyeq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gt2zlixopfb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oimlhwns.html

Go:   // 双指针从两端比较
来源：http://dali.yongpay.top/Article/details/gt2piwrnvkx.html

Ruby: s == s.reverse
来源：http://dali.nanxinkj.top/Article/details/gt2zknjucqf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.daria6918.cn/Article/details/gt2imcjkukd.html

[N07] 两数之和（返回下标）
来源：http://dali.fzhhl.top/Article/details/gt2kbqzembj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hywenlv.cn/Article/details/gt2audpodst.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj20258.top/Article/details/gt2zxccanyx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ivvv.top/Article/details/gt2qgbijyro.html

TS:   // 手写 Map<string, number>
来源：http://dali.tanke756.top/Article/details/gt2ucvdkzvs.html

Java: // 手写 HashMap
来源：http://dali.aizwys.cn/Article/details/gt2zibizabc.html

Go:   // 手写 map[int]int
来源：http://dali.yuanzhike.top/Article/details/gt2mcnlrgxx.html

Ruby: // 手写 Hash
来源：http://dali.nanxinkj.top/Article/details/gt2atsuraru.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yueranfly.top/Article/details/gt2xjassxuh.html

[N08] 生成全排列
来源：http://dali.haohaochexian.top/Article/details/gt2txatpnhd.html

Py:   itertools.permutations(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2oujhwxhu.html

PHP:  // 手写递归交换
来源：http://dali.xylfe.cn/Article/details/gt2vhadzodo.html

JS:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gt2ctvbotee.html

TS:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gt2flfwvzwh.html

Java: // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gt2ewfwfstk.html

Go:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gt2pcvgoagf.html

Ruby: arr.permutation.to_a
来源：http://dali.andypj.xyz/Article/details/gt2pkygcklx.html

C#:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2apmipupc.html

[N09] 栈与队列
来源：http://dali.jianghu66.top/Article/details/gt2ijwcxfao.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nafhevby.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2fleojpol.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yonumen.top/Article/details/gt2cinfqufr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj202588.top/Article/details/gt2srplgvph.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.pycfn.com/Article/details/gt2khzxdglf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.316326.xyz/Article/details/gt2rlemtmql.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gt2ioeaklbh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.0kj1m.cn/Article/details/gt2hqupucof.html

[N10] 链表节点定义
来源：http://dali.hywenlv.cn/Article/details/gt2btljjchr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bfugvxax.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuanzhike.top/Article/details/gt2bsyvontd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ybcxt.top/Article/details/gt2xroynqxn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ivvv.top/Article/details/gt2espqyyqc.html

Java: class Node { int v; Node next; }
来源：http://dali.fengsongda.top/Article/details/gt2kxqtnzmj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.fengsongda.top/Article/details/gt2snphyati.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhixingplan.top/Article/details/gt2hpjcwoyz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jqgfzy.top/Article/details/gt2hnaqalyj.html

[N11] 二叉树中序遍历
来源：http://dali.sufxvd.cn/Article/details/gt2vqhpnzcw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqhxrxl.html

PHP:  // 手写递归函数
来源：http://dali.birdmap.top/Article/details/gt2rvfvbytv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gzhubu.top/Article/details/gt2jjkepfow.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sysykeji.top/Article/details/gt2qvafvpoq.html

Java: // 手写递归
来源：http://dali.cucudq.cn/Article/details/gt2erjaslfs.html

Go:   // 手写递归
来源：http://dali.bjfxy.top/Article/details/gt2snnlujqn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yuxming.cn/Article/details/gt2vxtvdugy.html

C#:   // 手写递归
来源：http://dali.ybcxt.top/Article/details/gt2fdmxaopl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sxryk.cn/Article/details/gt2ufwzfhlu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.wangdashe.top/Article/details/gt2snqtbkmc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.mhx1999.top/Article/details/gt2edtfpvou.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daxiang520.top/Article/details/gt2mbhtvzru.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.316326.xyz/Article/details/gt2ejpxdobs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pycfn.com/Article/details/gt2agbzaxvn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yongpay.top/Article/details/gt2wpjzjxem.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ysixnsxn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.snrcjt.cn/Article/details/gt2fxpbftrs.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xonnjjlm.html

O. 并发与异步
来源：http://dali.pycfn.com/Article/details/gt2ujtyisdg.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2nxwgibsh.html

[O01] 启动一个线程
来源：http://dali.cucudq.cn/Article/details/gt2vostoipg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ehwqpu.com/Article/details/gt2vduzmeox.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yanxiufei.cn/Article/details/gt2vgkocrtk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hongshengwenyu.top/Article/details/gt2tkctuyhz.html

TS:   // 同 JS
来源：http://dali.guowangkeji.top/Article/details/gt2seiazpgi.html

Java: new Thread(() -> f()).start()
来源：http://dali.jyoumei.cn/Article/details/gt2bgeoezot.html

Go:   go f()
来源：http://dali.quarkkingdee.top/Article/details/gt2whezmrdx.html

Ruby: Thread.new { f }
来源：http://dali.sysykeji.top/Article/details/gt2npnuezgn.html

C#:   Task.Run(() => F());
来源：http://dali.havefunace.top/Article/details/gt2wspffbvz.html

[O02] 使用线程池
来源：http://dali.sufxvd.cn/Article/details/gt2msaxonqs.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sysykeji.top/Article/details/gt2njibxcfm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shuidangran.top/Article/details/gt2fshziaih.html

JS:   // worker_threads 线程池
来源：http://dali.cqqwz.cn/Article/details/gt2ugqzblrl.html

TS:   // worker_threads 线程池
来源：http://dali.fengsongda.top/Article/details/gt2lacewgij.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.daria6918.cn/Article/details/gt2thxlmmov.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.dianchejie.cn/Article/details/gt2tphpxavz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.haohaochexian.top/Article/details/gt2eyrejzag.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqxzkud.html

[O03] 加锁保护共享数据
来源：http://dali.aibaodan.cn/Article/details/gt2hkunpuqy.html

Py:   with lock: shared += 1
来源：http://dali.guannengcc.top/Article/details/gt2nbvrvuih.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinqigufen.top/Article/details/gt2rxxjjyyb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gotoacloud.top/Article/details/gt2prgpkpbn.html

TS:   // 同 JS
来源：http://dali.jianghu66.top/Article/details/gt2gkvrqlvp.html

Java: synchronized (this) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gt2uilffoub.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ppjwa.cn/Article/details/gt2njkzxasy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cheryme.top/Article/details/gt2gznnjtfi.html

C#:   lock (gate) { shared++; }
来源：http://dali.aibaodan.cn/Article/details/gt2bdgvnhvg.html

[O04] 定义异步函数并等待
来源：http://dali.c1oappe.top/Article/details/gt2vqynvsou.html

Py:   async def f():⏎    await g()
来源：http://dali.pengpengdd.cyou/Article/details/gt2qezbgqqa.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj20258.top/Article/details/gt2kywggjxw.html

JS:   async function f() { await g(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oasontfs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hysaishi.cn/Article/details/gt2azcjaixn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cheryme.top/Article/details/gt2clxenyyl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj20258.top/Article/details/gt2bntnthyd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.tianlin.xyz/Article/details/gt2ymudcuje.html

C#:   async Task F() { await G(); }
来源：http://dali.zhixingplan.top/Article/details/gt2ltpdbfxd.html

[O05] 并发执行并等待全部完成
来源：http://dali.smart0.xyz/Article/details/gt2cpinpqdm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.meibo888.top/Article/details/gt2eezmbkum.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gaohongyu789.top/Article/details/gt2gvvzbiin.html

JS:   await Promise.all(tasks)
来源：http://dali.cheryme.top/Article/details/gt2rgbpevkw.html

TS:   await Promise.all(tasks)
来源：http://dali.xinyue.icu/Article/details/gt2cvrnfugx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ydzc1.top/Article/details/gt2gcmshoox.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhoulong.xyz/Article/details/gt2ltvsdoqo.html

Ruby: threads.map(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gt2lsswybis.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mnshlqix.html

[O06] 使用进程池
来源：http://dali.havefunace.top/Article/details/gt2angfvsfq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.daxiang520.top/Article/details/gt2gnjxzwoe.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenlongwang.top/Article/details/gt2xbetobeq.html

JS:   // child_process / cluster 模块
来源：http://dali.xuetiantiany.cn/Article/details/gt2bsssmmrh.html

TS:   // child_process / cluster 模块
来源：http://dali.daxiang520.top/Article/details/gt2wzxcbzlk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.meibo888.top/Article/details/gt2qlgymrme.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ivvv.top/Article/details/gt2zbamcavb.html

Ruby: // fork 块
来源：http://dali.iojbl.cn/Article/details/gt2biypuevi.html

C#:   Parallel.For
来源：http://dali.chenzaomai.com/Article/details/gt2fwvibdvz.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2gzynlzwa.html

P. 常用工具函数
来源：http://dali.xinyue.icu/Article/details/gt2catiuljv.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2fuacubtl.html

[P01] 生成 UUID
来源：http://dali.gotoacloud.top/Article/details/gt2wjvrmeak.html

Py:   str(uuid.uuid4())
来源：http://dali.sysykeji.top/Article/details/gt2klmurwrw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhengqikj.top/Article/details/gt2atvxwikv.html

JS:   crypto.randomUUID()
来源：http://dali.aibaodan.cn/Article/details/gt2ownqohsl.html

TS:   crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gt2mrwpfzoo.html

Java: UUID.randomUUID().toString()
来源：http://dali.cheryme.top/Article/details/gt2botghfcm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.andypj.xyz/Article/details/gt2gdngebem.html

Ruby: SecureRandom.uuid
来源：http://dali.hnxiangtu.top/Article/details/gt2mhiaonan.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yuxming.cn/Article/details/gt2nuksezqn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yueranfly.top/Article/details/gt2bwdehrfx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.aibaodan.cn/Article/details/gt2uptbrero.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nwbrower.top/Article/details/gt2nfqeizwu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dgyyvlzk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tanke756.top/Article/details/gt2sxpxbtwu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2emyirlqt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhixingplan.top/Article/details/gt2ypyaerws.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.bjfxy.top/Article/details/gt2fuxmeaua.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.havefunace.top/Article/details/gt2ckpnnkey.html

[P03] 生成短随机字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2mvqjjiyi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhoulong.xyz/Article/details/gt2ejiqixcp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.meibo888.top/Article/details/gt2flsodyiw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shangyingyoupin.top/Article/details/gt2blssplql.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cashguo.top/Article/details/gt2oontuqdh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhengqikj.top/Article/details/gt2ykqmtzzb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cheryme.top/Article/details/gt2yanmtxub.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2olhupfof.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.bjfxy.top/Article/details/gt2pbcolqaj.html

[P04] 求长度
来源：http://dali.tianlin.xyz/Article/details/gt2aotgegae.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.havefunace.top/Article/details/gt2jiqpljut.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gt2tnulkiye.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xziqi.cn/Article/details/gt2bfvmhyfi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tian-w.cn/Article/details/gt2cnzzejjh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.daria6918.cn/Article/details/gt2yjcmfcmy.html

Go:   len(arr);  len(m)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jhcluhpu.html

Ruby: x.length;  x.size
来源：http://dali.nanxuanxn.top/Article/details/gt2efpweagl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cucudq.cn/Article/details/gt2imblhdna.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2genrshqp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.guowangkeji.top/Article/details/gt2ftseqcrj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xuanzx.com/Article/details/gt2litexhtn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.guowangkeji.top/Article/details/gt2tipfowxy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgufenzy.top/Article/details/gt2zxkllvye.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hfpthk.cn/Article/details/gt2utchiywg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cucudq.cn/Article/details/gt2fmoxkylf.html

Ruby: a == b
来源：http://dali.yj202588.top/Article/details/gt2nosnqyvx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ehwqpu.com/Article/details/gt2dgkngxhp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yuanzhike.top/Article/details/gt2zvvtmqoj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shanyushiyangtech.top/Article/details/gt2opqpdaik.html

PHP:  if (empty($x)) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fmvkxjju.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj202588.top/Article/details/gt2oxnyjhuc.html

TS:   if (x == null) {}
来源：http://dali.pycfn.com/Article/details/gt2ewpnxnel.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.aibaodan.cn/Article/details/gt2ztgaixzi.html

Go:   if x == nil {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2ndwfsfjp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.svipenyu.cn/Article/details/gt2qvocprop.html

C#:   if (x is null) {}
来源：http://dali.jianghu66.top/Article/details/gt2gpgwzdpg.html

[P07] 防抖与节流
来源：http://dali.ydzc1.top/Article/details/gt2qdwufpib.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nwbrower.top/Article/details/gt2dmkrivhs.html

PHP:  // 手写时间戳比较
来源：http://dali.fengsongda.top/Article/details/gt2didyrshf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zycfv.cn/Article/details/gt2ahjnwkql.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxinkj.top/Article/details/gt2wkrnxgyv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.redwolf501.top/Article/details/gt2zbojvqli.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.9152youxi.cn/Article/details/gt2xsjhrwgn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.vqdsnc.cn/Article/details/gt2qxtlwigf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xinyue.icu/Article/details/gt2yqtugqij.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2nfuhxitn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yueranfly.top/Article/details/gt2lbnsdrsp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2ysfvwnov.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sxryk.cn/Article/details/gt2nklbtldc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.mhx1999.top/Article/details/gt2ffhkfxxx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hongshengwenyu.top/Article/details/gt2uyrwgvkx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.316326.xyz/Article/details/gt2tqpidhtr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.mhx1999.top/Article/details/gt2kpicitos.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ehwqpu.com/Article/details/gt2isgwvguo.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2azxyfqja.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sxryk.cn/Article/details/gt2mczhepfa.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2vwitatmz.html

[Q01] 创建表
来源：http://dali.vqdsnc.cn/Article/details/gt2hypfrqml.html

CREATE TABLE users (
来源：http://dali.ivvv.top/Article/details/gt2efzwbxzp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yonumen.top/Article/details/gt2sqaimrgi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zdqjudy.top/Article/details/gt2egnlcewg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hysaishi.cn/Article/details/gt2xwhqwsof.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ppjwa.cn/Article/details/gt2xisprbhr.html

);
来源：http://dali.yangfankeji.com/Article/details/gt2swjvajvl.html

[Q02] 创建带外键的表
来源：http://dali.meibo888.top/Article/details/gt2mcuzgedf.html

CREATE TABLE orders (
来源：http://dali.yuxming.cn/Article/details/gt2nporjueh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigfzy.top/Article/details/gt2qymafxlw.html

user_id INT NOT NULL,
来源：http://dali.zhixingplan.top/Article/details/gt2yxfquxhn.html

amount DECIMAL(10, 2),
来源：http://dali.yvedp.cn/Article/details/gt2nflgdyff.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.vqdsnc.cn/Article/details/gt2osihgwhd.html

);
来源：http://dali.cucudq.cn/Article/details/gt2heypalhi.html

[Q03] 增加列
来源：http://dali.pycfn.com/Article/details/gt2mxhuqtyq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2thkpxjgu.html

[Q04] 修改列类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sjyqvnyk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cdnleiting.top/Article/details/gt2vmcdfikv.html

[Q05] 重命名列
来源：http://dali.dianchejie.cn/Article/details/gt2zcqfyaig.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.nanxinkj.top/Article/details/gt2tfmyfzyl.html

[Q06] 删除列
来源：http://dali.cqqwz.cn/Article/details/gt2dkfriqyq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.quarkkingdee.top/Article/details/gt2kqdkbpjl.html

[Q07] 删除表
来源：http://dali.9152youxi.cn/Article/details/gt2xqpgrbtr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gzhubu.top/Article/details/gt2ibeawmkc.html

[Q08] 创建普通索引
来源：http://dali.smart0.xyz/Article/details/gt2pqlzeifp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sysykeji.top/Article/details/gt2rmbcmdyp.html

[Q09] 创建唯一索引
来源：http://dali.jyoumei.cn/Article/details/gt2mmurqrbx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hfpthk.cn/Article/details/gt2undxmnsy.html

[Q10] 插入单行
来源：http://dali.pycfn.com/Article/details/gt2taxfsnfe.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yangfankeji.com/Article/details/gt2draivyno.html

[Q11] 一次插入多行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eepvopbm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.pycfn.com/Article/details/gt2lhxqikqs.html

[Q12] 插入后取自增 ID
来源：http://dali.daria6918.cn/Article/details/gt2rlbwazku.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.vqdsnc.cn/Article/details/gt2klntxydg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hywenlv.cn/Article/details/gt2smuprewl.html

[Q13] 忽略重复插入
来源：http://dali.jinqigfzy.top/Article/details/gt2aegmhayb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yuxming.cn/Article/details/gt2fjdurilm.html

[Q14] 存在则更新（upsert）
来源：http://dali.andypj.xyz/Article/details/gt2irhjwple.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.meibo888.top/Article/details/gt2rwxqvbfu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.haohaochexian.top/Article/details/gt2medrnvwb.html

[Q15] 查询全部
来源：http://dali.chenlongwang.top/Article/details/gt2kdlzzvvs.html

SELECT * FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2tzlhnrjs.html

[Q16] 查询指定列
来源：http://dali.shuidangran.top/Article/details/gt2vrsoxjqa.html

SELECT id, name FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2qrrezxbk.html

[Q17] 条件查询
来源：http://dali.yongpay.top/Article/details/gt2pcqeuvta.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sufxvd.cn/Article/details/gt2pxetxsjk.html

[Q18] 模糊匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2plablyct.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ydzc1.top/Article/details/gt2lwxayjrx.html

[Q19] 范围查询
来源：http://dali.daria6918.cn/Article/details/gt2jndallvp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yongpay.top/Article/details/gt2gihofejj.html

[Q20] IN 列表
来源：http://dali.hammf.cn/Article/details/gt2vfrkldyb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.andypj.xyz/Article/details/gt2macvfsax.html

[Q21] 空值判断
来源：http://dali.chenlongwang.top/Article/details/gt2uewibjvo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.guowangkeji.top/Article/details/gt2tjylcxsd.html

[Q22] 排序
来源：http://dali.aibaodan.cn/Article/details/gt2ixprjmmq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ovpfdksc.html

[Q23] 分页
来源：http://dali.gotoacloud.top/Article/details/gt2upjdrpyc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.iojbl.cn/Article/details/gt2fecneyco.html

[Q24] 去重
来源：http://dali.jiagoushi.top/Article/details/gt2mxewblbt.html

SELECT DISTINCT city FROM users;
来源：http://dali.tanke756.top/Article/details/gt2ltgailrl.html

[Q25] 只取前 N 条
来源：http://dali.ybcxt.top/Article/details/gt2axhiektr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.daria6918.cn/Article/details/gt2zustfbwf.html

[Q26] 计数
来源：http://dali.bjfxy.top/Article/details/gt2zqabqcgl.html

SELECT COUNT(*) FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2pesgzpgv.html

[Q27] 条件计数
来源：http://dali.ivvv.top/Article/details/gt2vjpeuwsv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2ozohaklp.html

[Q28] 求和与平均
来源：http://dali.jqgufenzy.top/Article/details/gt2thtsiheu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gt2ifkbsuhs.html

[Q29] 最大最小值
来源：http://dali.xylfe.cn/Article/details/gt2prucwcxg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yknanpwk.html

[Q30] 分组统计
来源：http://dali.quarkkingdee.top/Article/details/gt2vtytnukr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gt2vgrpbpim.html

[Q31] 分组后过滤
来源：http://dali.ivvv.top/Article/details/gt2pwojhsee.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ivvv.top/Article/details/gt2mhvjhpte.html

[Q32] 分组拼接字符串
来源：http://dali.yongpay.top/Article/details/gt2sdceadlf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yefkmjcp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.feifeiyinyue.top/Article/details/gt2undgdrqs.html

[Q33] 多列分组
来源：http://dali.xuanzx.com/Article/details/gt2irfrontl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.daxiang520.top/Article/details/gt2xidosroj.html

[Q34] 每组取第一条
来源：http://dali.yuxming.cn/Article/details/gt2qwrkaxrw.html

SELECT * FROM (
来源：http://dali.yonumen.top/Article/details/gt2cxliyqij.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gotoacloud.top/Article/details/gt2ymrrbqsh.html

) t WHERE rn = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gt2sqbwlvzd.html

[Q35] 内连接
来源：http://dali.snrcjt.cn/Article/details/gt2xglizlbg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iicnikkg.html


<!-- 参考信息 -->