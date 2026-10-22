代发 wailian999

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hammf.cn/Article/details/gtvvkzxzvt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jlsjyb.cn/Article/details/gtibyufxyn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gtqzzwdtbt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gtmwsdraae.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gtbrxljxmz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhongyouzk.top/Article/details/gtcivkwvav.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.svipenyu.cn/Article/details/gtwgltswgr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gtckkhyhsl.html

[N05] 最大公约数
来源：http://dali.zhixingplan.top/Article/details/gtlwxxvetk.html

Py:   math.gcd(a, b)
来源：http://dali.wangdashe.top/Article/details/gtmqsozscq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.9152youxi.cn/Article/details/gteqrxkqic.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gtcusrjtyj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yongpay.top/Article/details/gthmkrjmhg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yueranfly.top/Article/details/gtouztnbfz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypwwcflu.html

Ruby: a.gcd(b)
来源：http://dali.jyoumei.cn/Article/details/gtvfreehkx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuanzhike.top/Article/details/gtpdrjvgrf.html

[N06] 判断回文字符串
来源：http://dali.c1oappe.top/Article/details/gtskuoejvq.html

Py:   s == s[::-1]
来源：http://dali.gogol.net.cn/Article/details/gtnwccqyje.html

PHP:  $s === strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gtjrmmtcre.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gtdtdycaqy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtplyfjbsw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cqqwz.cn/Article/details/gtdsrdfdmw.html

Go:   // 双指针从两端比较
来源：http://dali.mhx1999.top/Article/details/gtqipuahbt.html

Ruby: s == s.reverse
来源：http://dali.9152youxi.cn/Article/details/gtaawljrjl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sufxvd.cn/Article/details/gthpwdbylk.html

[N07] 两数之和（返回下标）
来源：http://dali.ivvv.top/Article/details/gtdlwwmtmc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shuidangran.top/Article/details/gtjmegboyz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.mhx1999.top/Article/details/gtcmgwmokn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gtgoxbhhgx.html

TS:   // 手写 Map<string, number>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjvmmytc.html

Java: // 手写 HashMap
来源：http://dali.zycfv.cn/Article/details/gtfbspfpok.html

Go:   // 手写 map[int]int
来源：http://dali.yj202588.top/Article/details/gtwqybrzra.html

Ruby: // 手写 Hash
来源：http://dali.zhoulong.xyz/Article/details/gtnxepdzpj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hywenlv.cn/Article/details/gtkwjhoflz.html

[N08] 生成全排列
来源：http://dali.jqgufenzy.top/Article/details/gtyucgmlmv.html

Py:   itertools.permutations(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtajjgyffk.html

PHP:  // 手写递归交换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjljfnvit.html

JS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtvfagzgfl.html

TS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtyieuojow.html

Java: // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtbdfkjlut.html

Go:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtlxewoamz.html

Ruby: arr.permutation.to_a
来源：http://dali.yj20258.top/Article/details/gtjijjygwu.html

C#:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrjrltdf.html

[N09] 栈与队列
来源：http://dali.chenjidiqi.icu/Article/details/gtlhiryziu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gtvrtndfdi.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.birdmap.top/Article/details/gtepvgakvz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkstacnpf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cheryme.top/Article/details/gtxdobtphm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj20258.top/Article/details/gtrkqxusvp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj20258.top/Article/details/gtymwqvlpo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwtdcnki.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj202588.top/Article/details/gtadwiytnm.html

[N10] 链表节点定义
来源：http://dali.gzhubu.top/Article/details/gtcefcxrci.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hysaishi.cn/Article/details/gtnyltjykl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cheryme.top/Article/details/gtmcfqywgg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.9152youxi.cn/Article/details/gtzhigovxk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ybcxt.top/Article/details/gtevcnbtyc.html

Java: class Node { int v; Node next; }
来源：http://dali.jlsjyb.cn/Article/details/gterrepyvf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tian-w.cn/Article/details/gtdkfhruif.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hammf.cn/Article/details/gtqjkjeolk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.wangdashe.top/Article/details/gtmrewtakd.html

[N11] 二叉树中序遍历
来源：http://dali.havefunace.top/Article/details/gtvywakriw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenzaomai.com/Article/details/gteinhwnqc.html

PHP:  // 手写递归函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmilcczq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aizwys.cn/Article/details/gtqhmusqsy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hongshengwenyu.top/Article/details/gtebinvfgm.html

Java: // 手写递归
来源：http://dali.xuanzx.com/Article/details/gtgklxkdgf.html

Go:   // 手写递归
来源：http://dali.yj20258888.top/Article/details/gtcqaprrnr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.fengsongda.top/Article/details/gtdcholjsi.html

C#:   // 手写递归
来源：http://dali.ybcxt.top/Article/details/gtdxinnzlk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jianghu66.top/Article/details/gtdwidyhiv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jqgfzy.top/Article/details/gtzbkgyysa.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ehwqpu.com/Article/details/gtqponajqm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fzhhl.top/Article/details/gtpdznbgoc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.c1oappe.top/Article/details/gtqmzknkpa.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pycfn.com/Article/details/gtlkgipwbm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.feifeiyinyue.top/Article/details/gttpkmdonn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cqqwz.cn/Article/details/gtvdbaevuq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cdnleiting.top/Article/details/gtxzfnbgug.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujhyzuzw.html

O. 并发与异步
来源：http://dali.chenlongwang.top/Article/details/gtlthwldwg.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtlogtmmog.html

[O01] 启动一个线程
来源：http://dali.fengsongda.top/Article/details/gtdtsuxlzs.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yj20258888.top/Article/details/gtmaxqndnm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj20258888.top/Article/details/gtksyidhrg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xziqi.cn/Article/details/gtulcrgzfy.html

TS:   // 同 JS
来源：http://dali.zdqjudy.top/Article/details/gtqadeiuyn.html

Java: new Thread(() -> f()).start()
来源：http://dali.nanxuanxn.top/Article/details/gttgldtziw.html

Go:   go f()
来源：http://dali.meibo888.top/Article/details/gtlhpxaopw.html

Ruby: Thread.new { f }
来源：http://dali.fengsongda.top/Article/details/gtbvlkbhil.html

C#:   Task.Run(() => F());
来源：http://dali.gotoacloud.top/Article/details/gtiksppxcn.html

[O02] 使用线程池
来源：http://dali.cashguo.top/Article/details/gtfaewzhmg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwxtmhnzf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jianghu66.top/Article/details/gtiudrpajm.html

JS:   // worker_threads 线程池
来源：http://dali.snrcjt.cn/Article/details/gtplrzxtij.html

TS:   // worker_threads 线程池
来源：http://dali.daxiang520.top/Article/details/gtggmftwrd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hywenlv.cn/Article/details/gtpevxtzef.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.redwolf501.top/Article/details/gtshkbwbbx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenjidiqi.icu/Article/details/gtjusbybkp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hywenlv.cn/Article/details/gtbjmjfove.html

[O03] 加锁保护共享数据
来源：http://dali.ivvv.top/Article/details/gtgpvbuaih.html

Py:   with lock: shared += 1
来源：http://dali.shanyushiyangtech.top/Article/details/gthyildzab.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.havefunace.top/Article/details/gtegqcmulp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.pycfn.com/Article/details/gtjvwyrxpc.html

TS:   // 同 JS
来源：http://dali.zhiwuduotai.top/Article/details/gtikycdown.html

Java: synchronized (this) { shared++; }
来源：http://dali.pengpengdd.cyou/Article/details/gttmgwcjed.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zdqjudy.top/Article/details/gtflwictnb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.guannengcc.top/Article/details/gtsoxdaqqv.html

C#:   lock (gate) { shared++; }
来源：http://dali.sysykeji.top/Article/details/gtahtmgpbj.html

[O04] 定义异步函数并等待
来源：http://dali.ppjwa.cn/Article/details/gtnbdhygwh.html

Py:   async def f():⏎    await g()
来源：http://dali.cdnleiting.top/Article/details/gtlknvavgg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sysykeji.top/Article/details/gthpsljzso.html

JS:   async function f() { await g(); }
来源：http://dali.pycfn.com/Article/details/gtbobawcvy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.wangdashe.top/Article/details/gtdpnrfgtq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj20258888.top/Article/details/gtasldweyp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvyvuypxr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.c1oappe.top/Article/details/gtcsuniwge.html

C#:   async Task F() { await G(); }
来源：http://dali.ydzc1.top/Article/details/gtsvuyedvs.html

[O05] 并发执行并等待全部完成
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdzhqvbsk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.dashuyun.cn/Article/details/gtqwdxajkl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yvedp.cn/Article/details/gtufqzmewf.html

JS:   await Promise.all(tasks)
来源：http://dali.ydzc1.top/Article/details/gtcoprucbz.html

TS:   await Promise.all(tasks)
来源：http://dali.yj20258.top/Article/details/gtqpvcdulv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.haohaochexian.top/Article/details/gtgbykfbwn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sxryk.cn/Article/details/gttqqpaxre.html

Ruby: threads.map(&:join)
来源：http://dali.0kj1m.cn/Article/details/gtveqwyzbq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj20258888.top/Article/details/gtgyetrfwt.html

[O06] 使用进程池
来源：http://dali.svipenyu.cn/Article/details/gtfuwqzetg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sweek.top/Article/details/gtwyybnyep.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ybcxt.top/Article/details/gtaujxkprl.html

JS:   // child_process / cluster 模块
来源：http://dali.pengpengdd.cyou/Article/details/gtnowzqrav.html

TS:   // child_process / cluster 模块
来源：http://dali.guannengcc.top/Article/details/gtglxhwvyv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xylfe.cn/Article/details/gtyzglpqxi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgudindrr.html

Ruby: // fork 块
来源：http://dali.yonumen.top/Article/details/gtmyduikfl.html

C#:   Parallel.For
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlvranedg.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtqvlylkmb.html

P. 常用工具函数
来源：http://dali.xylfe.cn/Article/details/gtjbrkovhx.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtxqskvlga.html

[P01] 生成 UUID
来源：http://dali.shzxlz.cn/Article/details/gtrvlmxlwu.html

Py:   str(uuid.uuid4())
来源：http://dali.jinqigfzy.top/Article/details/gtadecyayy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yj202588.top/Article/details/gtbgxcztwn.html

JS:   crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gtcpzlpwcl.html

TS:   crypto.randomUUID()
来源：http://dali.pycfn.com/Article/details/gtwplbawmn.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhengqikj.top/Article/details/gtnchtvccy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctdpnrnf.html

Ruby: SecureRandom.uuid
来源：http://dali.wangshuangyany.cn/Article/details/gtfgnjhxzd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cucudq.cn/Article/details/gtnwkacvyp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.9152youxi.cn/Article/details/gtncqyrvlm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yuxming.cn/Article/details/gtnmgsatcm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.iojbl.cn/Article/details/gtwdoryagk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yanxiufei.cn/Article/details/gtwvyjjzpg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.dianchejie.cn/Article/details/gtwhsxphuc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shzxlz.cn/Article/details/gteczcwmjc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cucudq.cn/Article/details/gtlpacemba.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sufxvd.cn/Article/details/gtlsxoaypm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.mhx1999.top/Article/details/gttivvpkpk.html

[P03] 生成短随机字符串
来源：http://dali.c1oappe.top/Article/details/gtvipywftk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.mhx1999.top/Article/details/gtfdwrlmzd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkeademb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tianlin.xyz/Article/details/gtxagcqzac.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fzhhl.top/Article/details/gtxglkamrr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlokeocno.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.pengpengdd.cyou/Article/details/gtfcdvmyno.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwaaztsuw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhiwuduotai.top/Article/details/gtuvlkbdxm.html

[P04] 求长度
来源：http://dali.zhongyouzk.top/Article/details/gtymaedtra.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nanxuanxn.top/Article/details/gtjxlystlu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gtcofpninw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.mhx1999.top/Article/details/gtayntjgba.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zdqjudy.top/Article/details/gtxbacgikf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yueranfly.top/Article/details/gtujbomgte.html

Go:   len(arr);  len(m)
来源：http://dali.zhoulong.xyz/Article/details/gtjxsufuii.html

Ruby: x.length;  x.size
来源：http://dali.ydzc1.top/Article/details/gtckxwplpa.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gotoacloud.top/Article/details/gtxovwheod.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ivvv.top/Article/details/gtwwshabzg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hnqzz.top/Article/details/gtkwokafgh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.mhx1999.top/Article/details/gtjdidhdla.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenjidiqi.icu/Article/details/gtpstgxypz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nwbrower.top/Article/details/gtmrpuebxt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.wangdashe.top/Article/details/gtxhphwozd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ybcxt.top/Article/details/gtuhhxkarw.html

Ruby: a == b
来源：http://dali.yvedp.cn/Article/details/gtarwhjtjz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.kuanghao11.cn/Article/details/gtecyppjmc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shanyushiyangtech.top/Article/details/gtyixukxwq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdvaelfu.html

PHP:  if (empty($x)) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtbbjmszef.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yongpay.top/Article/details/gtvcghzvyt.html

TS:   if (x == null) {}
来源：http://dali.havefunace.top/Article/details/gtnrtwqrke.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj202588.top/Article/details/gtuqqpwiqt.html

Go:   if x == nil {}
来源：http://dali.aibaodan.cn/Article/details/gtqkzmxebb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yongpay.top/Article/details/gthbqfhssb.html

C#:   if (x is null) {}
来源：http://dali.fzhhl.top/Article/details/gtfibygzpv.html

[P07] 防抖与节流
来源：http://dali.iojbl.cn/Article/details/gtidpbyhii.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sufxvd.cn/Article/details/gtbphmjkte.html

PHP:  // 手写时间戳比较
来源：http://dali.zhiwuduotai.top/Article/details/gtydjklpdd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gtdkgaccrp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gtjrkffgiq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jlsjyb.cn/Article/details/gtbkssuxcm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.9152youxi.cn/Article/details/gtatakzsop.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.wangdashe.top/Article/details/gtraacyfhl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nanxuanxn.top/Article/details/gtzofbbwla.html

[P08] 处理浮点精度问题
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdygrrwtn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.pycfn.com/Article/details/gtntezrzqs.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtikhvaeqi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yvedp.cn/Article/details/gtsjsvbqwk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yangfankeji.com/Article/details/gtskqvafmn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.vqdsnc.cn/Article/details/gtlogtufbw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.dianchejie.cn/Article/details/gtpocezmdy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yongpay.top/Article/details/gtrumqhoan.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxuanxn.top/Article/details/gttptynlxe.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtaiwjpcij.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gtqrjbtbcx.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtdycleuai.html

[Q01] 创建表
来源：http://dali.jinghuilouyu.cn/Article/details/gtecwegesp.html

CREATE TABLE users (
来源：http://dali.aizwys.cn/Article/details/gtbuyqhlcm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnxiangtu.top/Article/details/gttbgwamhh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cdnleiting.top/Article/details/gtopssiqrw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gtyyoelnoh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenlongwang.top/Article/details/gtnisoyqao.html

);
来源：http://dali.jiagoushi.top/Article/details/gtnyovxkju.html

[Q02] 创建带外键的表
来源：http://dali.dashuyun.cn/Article/details/gtmmjemwou.html

CREATE TABLE orders (
来源：http://dali.haohaochexian.top/Article/details/gtbrinywko.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.smart0.xyz/Article/details/gtitmzplma.html

user_id INT NOT NULL,
来源：http://dali.cashguo.top/Article/details/gtympgbscl.html

amount DECIMAL(10, 2),
来源：http://dali.zhixingplan.top/Article/details/gtuvfefmzg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yangfankeji.com/Article/details/gtluotyfqk.html

);
来源：http://dali.jqgufenzy.top/Article/details/gtcndaatsj.html

[Q03] 增加列
来源：http://dali.pycfn.com/Article/details/gtknavblnf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.fzhhl.top/Article/details/gtmrbmezcr.html

[Q04] 修改列类型
来源：http://dali.chenlongwang.top/Article/details/gtrsgkcqdy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xziqi.cn/Article/details/gthxwvsoha.html

[Q05] 重命名列
来源：http://dali.dashuyun.cn/Article/details/gtijevglnm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xylfe.cn/Article/details/gtjookfqbu.html

[Q06] 删除列
来源：http://dali.fzhhl.top/Article/details/gtthugsexz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yanxiufei.cn/Article/details/gtrxvvmmnv.html

[Q07] 删除表
来源：http://dali.shangyingyoupin.top/Article/details/gtcphbuaut.html

DROP TABLE IF EXISTS orders;
来源：http://dali.snrcjt.cn/Article/details/gtbpoxdppg.html

[Q08] 创建普通索引
来源：http://dali.xinyue.icu/Article/details/gtwgjnvhgg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.nwbrower.top/Article/details/gtpxkdlmvj.html

[Q09] 创建唯一索引
来源：http://dali.guannengcc.top/Article/details/gtjljqcpva.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xinyue.icu/Article/details/gtvddaanzy.html

[Q10] 插入单行
来源：http://dali.hammf.cn/Article/details/gttasmqclj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinqigufen.top/Article/details/gtadlnmikh.html

[Q11] 一次插入多行
来源：http://dali.ybcxt.top/Article/details/gtbykoxffv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.havefunace.top/Article/details/gttguztkwx.html

[Q12] 插入后取自增 ID
来源：http://dali.chenzaomai.com/Article/details/gtszeziwqo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ivvv.top/Article/details/gtwbawuqat.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tianlin.xyz/Article/details/gtvfiednfx.html

[Q13] 忽略重复插入
来源：http://dali.chenzaomai.com/Article/details/gtawrraqyt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenlongwang.top/Article/details/gtzlseojir.html

[Q14] 存在则更新（upsert）
来源：http://dali.feifeiyinyue.top/Article/details/gtdbydxoqt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hnxiangtu.top/Article/details/gtdqcbqfem.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tian-w.cn/Article/details/gtjjyjotvi.html

[Q15] 查询全部
来源：http://dali.xuanzx.com/Article/details/gtnqgvltol.html

SELECT * FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtgkiyicrj.html

[Q16] 查询指定列
来源：http://dali.tianlin.xyz/Article/details/gtoinqonxb.html

SELECT id, name FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtbdpjqxca.html

[Q17] 条件查询
来源：http://dali.xuetiantiany.cn/Article/details/gtvfwvnitr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yuanzhike.top/Article/details/gtjiphafuk.html

[Q18] 模糊匹配
来源：http://dali.xylfe.cn/Article/details/gtwosuzxwr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hongshengwenyu.top/Article/details/gtfzefczkg.html

[Q19] 范围查询
来源：http://dali.hnxiangtu.top/Article/details/gtztmvqyiy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.wangdashe.top/Article/details/gtnjxajvld.html

[Q20] IN 列表
来源：http://dali.sweek.top/Article/details/gtlemlcdwb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hywenlv.cn/Article/details/gtpetlljfw.html

[Q21] 空值判断
来源：http://dali.pengpengdd.cyou/Article/details/gtqyxnuaza.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj20258888.top/Article/details/gtxxnhcytz.html

[Q22] 排序
来源：http://dali.wangshuangyany.cn/Article/details/gtkikeywsz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.meibo888.top/Article/details/gtevfvjzhn.html

[Q23] 分页
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqaaqbshi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sweek.top/Article/details/gthtgqmmbs.html

[Q24] 去重
来源：http://dali.jinqigufen.top/Article/details/gtmctnjmdm.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtudctvmoc.html

[Q25] 只取前 N 条
来源：http://dali.hfpthk.cn/Article/details/gtdeqhxqjb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhoulong.xyz/Article/details/gtfhqjsalz.html

[Q26] 计数
来源：http://dali.quarkkingdee.top/Article/details/gtmysjtium.html

SELECT COUNT(*) FROM users;
来源：http://dali.wangdashe.top/Article/details/gthsfbayim.html

[Q27] 条件计数
来源：http://dali.zhongyouzk.top/Article/details/gtreegfxfk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ydzc1.top/Article/details/gtvtfmpdex.html

[Q28] 求和与平均
来源：http://dali.zhixingplan.top/Article/details/gtwexvbhfx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiiehlfzz.html

[Q29] 最大最小值
来源：http://dali.xylfe.cn/Article/details/gtglujkafr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtplqmimzn.html

[Q30] 分组统计
来源：http://dali.jiagoushi.top/Article/details/gtfsvgqvvn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj20258.top/Article/details/gtevdlekac.html

[Q31] 分组后过滤
来源：http://dali.cashguo.top/Article/details/gtqlciufhk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ybcxt.top/Article/details/gtnvzcirxs.html

[Q32] 分组拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gtcemfoftn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gtzzgbwrgr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.quarkkingdee.top/Article/details/gthanjnlpj.html

[Q33] 多列分组
来源：http://dali.wangdashe.top/Article/details/gtdqeuwucj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ppjwa.cn/Article/details/gtdakckbnf.html

[Q34] 每组取第一条
来源：http://dali.hysaishi.cn/Article/details/gtkxhgoiel.html

SELECT * FROM (
来源：http://dali.yj20258.top/Article/details/gtxxcnbdeq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yangfankeji.com/Article/details/gtaecubprz.html

) t WHERE rn = 1;
来源：http://dali.yvedp.cn/Article/details/gtnkwitdal.html

[Q35] 内连接
来源：http://dali.hywenlv.cn/Article/details/gtqapfabna.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tianlin.xyz/Article/details/gtztgmezqf.html


<!-- 参考信息 -->