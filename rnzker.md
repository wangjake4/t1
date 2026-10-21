代发 wailian999

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgufenzy.top/Article/details/gtqhsjjmld.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvapuzbb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqneudfp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gtfugwbmno.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenjidiqi.icu/Article/details/gtvghgqxsz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yueranfly.top/Article/details/gtuoiqkige.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtrrhsgjzm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gtvcqwapzx.html

[N05] 最大公约数
来源：http://dali.tian-w.cn/Article/details/gtaauekryk.html

Py:   math.gcd(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpaggaqom.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ybcxt.top/Article/details/gtdirrpilr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gtnhhffqsp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmufqbsx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.pengpengdd.cyou/Article/details/gtyuupcdbu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvxnipwi.html

Ruby: a.gcd(b)
来源：http://dali.c1oappe.top/Article/details/gtvawjxoze.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xinyue.icu/Article/details/gttwnwxjnj.html

[N06] 判断回文字符串
来源：http://dali.jlsjyb.cn/Article/details/gtcsvbfrrz.html

Py:   s == s[::-1]
来源：http://dali.gaohongyu789.top/Article/details/gthhqfwuna.html

PHP:  $s === strrev($s);
来源：http://dali.xinyue.icu/Article/details/gtjbidwuez.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtzlndgsrg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtfoimyoda.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hywenlv.cn/Article/details/gtitbekjru.html

Go:   // 双指针从两端比较
来源：http://dali.hywenlv.cn/Article/details/gtxwpbsdkm.html

Ruby: s == s.reverse
来源：http://dali.tianlin.xyz/Article/details/gthykcwzpg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shzxlz.cn/Article/details/gtlggwklqw.html

[N07] 两数之和（返回下标）
来源：http://dali.ybcxt.top/Article/details/gthgbujeiu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhoulong.xyz/Article/details/gtwtyjroqz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.pengpengdd.cyou/Article/details/gtqolrglhi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yuanzhike.top/Article/details/gtvhfswoqk.html

TS:   // 手写 Map<string, number>
来源：http://dali.hongshengwenyu.top/Article/details/gtztszusqj.html

Java: // 手写 HashMap
来源：http://dali.sufxvd.cn/Article/details/gtwxfoxkai.html

Go:   // 手写 map[int]int
来源：http://dali.jqgfzy.top/Article/details/gtrqgzafkc.html

Ruby: // 手写 Hash
来源：http://dali.0kj1m.cn/Article/details/gtjnwlctjt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.c1oappe.top/Article/details/gtwczioepm.html

[N08] 生成全排列
来源：http://dali.jinqigfzy.top/Article/details/gtdtejrdul.html

Py:   itertools.permutations(arr)
来源：http://dali.gzhubu.top/Article/details/gtjrfkdbbq.html

PHP:  // 手写递归交换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtelssifpd.html

JS:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtzyuganuo.html

TS:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gtcuwxvuwr.html

Java: // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtvzzcvcyr.html

Go:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtztrldpzo.html

Ruby: arr.permutation.to_a
来源：http://dali.kuanghao11.cn/Article/details/gtbhetkjnr.html

C#:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtzbgxwrty.html

[N09] 栈与队列
来源：http://dali.xinyue.icu/Article/details/gtkvkqknrg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.tianlin.xyz/Article/details/gthlkjfmbp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtrgzekykc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gtxutqmdkf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sweek.top/Article/details/gtlznsijnf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ppjwa.cn/Article/details/gtejqvxhpt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xylfe.cn/Article/details/gtodxdtknc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sxryk.cn/Article/details/gtwptevexu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.feifeiyinyue.top/Article/details/gtvnqltltb.html

[N10] 链表节点定义
来源：http://dali.gaohongyu789.top/Article/details/gtguppqxfl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shzxlz.cn/Article/details/gtxwimmylu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shzxlz.cn/Article/details/gtmkekpmpd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jlsjyb.cn/Article/details/gtkrpoipmf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xziqi.cn/Article/details/gtabwbihxw.html

Java: class Node { int v; Node next; }
来源：http://dali.tian-w.cn/Article/details/gtdlcqsugq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.havefunace.top/Article/details/gtfcypeumt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenzaomai.com/Article/details/gtsxgkifjw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.pycfn.com/Article/details/gtktnuphee.html

[N11] 二叉树中序遍历
来源：http://dali.yj202588.top/Article/details/gtleyivxol.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yanxiufei.cn/Article/details/gtjxipmajv.html

PHP:  // 手写递归函数
来源：http://dali.yuanzhike.top/Article/details/gtgshdlcjy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yueranfly.top/Article/details/gtqaibmndm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtogyfrstr.html

Java: // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gthieillaj.html

Go:   // 手写递归
来源：http://dali.andypj.xyz/Article/details/gtnjecjyxu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinqigufen.top/Article/details/gtayyonlsb.html

C#:   // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gteumzaxnb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.316326.xyz/Article/details/gtuyrvtyrd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.pengpengdd.cyou/Article/details/gthucrlwvt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj202588.top/Article/details/gtxhrahnad.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.andypj.xyz/Article/details/gtwklqzbak.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.feifeiyinyue.top/Article/details/gtxxehvofe.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guowangkeji.top/Article/details/gtpvmdrpcp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttxshajea.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hnxiangtu.top/Article/details/gtqszbjpqq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigfzy.top/Article/details/gtayzratkc.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtckkedtqk.html

O. 并发与异步
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonnqhajo.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtudrotcng.html

[O01] 启动一个线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoainicff.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ehwqpu.com/Article/details/gtctozpyfj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.c1oappe.top/Article/details/gtrtzikyqw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ehwqpu.com/Article/details/gthitsfwgx.html

TS:   // 同 JS
来源：http://dali.ehwqpu.com/Article/details/gtzzlxajwq.html

Java: new Thread(() -> f()).start()
来源：http://dali.c1oappe.top/Article/details/gtheofzkwk.html

Go:   go f()
来源：http://dali.zhiwuduotai.top/Article/details/gtvwrqtiux.html

Ruby: Thread.new { f }
来源：http://dali.dianchejie.cn/Article/details/gtaemjxagi.html

C#:   Task.Run(() => F());
来源：http://dali.cheryme.top/Article/details/gtobdtxvho.html

[O02] 使用线程池
来源：http://dali.nwbrower.top/Article/details/gtddqtrmqr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsnvqszst.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gttlransoo.html

JS:   // worker_threads 线程池
来源：http://dali.ehwqpu.com/Article/details/gtowruynbb.html

TS:   // worker_threads 线程池
来源：http://dali.ppjwa.cn/Article/details/gtuuusknwn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gaohongyu789.top/Article/details/gtviaeovai.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.aizwys.cn/Article/details/gtvlegqyds.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.pycfn.com/Article/details/gtowaqpdis.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jianghu66.top/Article/details/gtftqcyuty.html

[O03] 加锁保护共享数据
来源：http://dali.xuanzx.com/Article/details/gtgvpzvlnn.html

Py:   with lock: shared += 1
来源：http://dali.fengsongda.top/Article/details/gtwbsqmzfv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxsaggccw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.fengsongda.top/Article/details/gtyfvtwdhb.html

TS:   // 同 JS
来源：http://dali.gaohongyu789.top/Article/details/gtalvbilfg.html

Java: synchronized (this) { shared++; }
来源：http://dali.nanxinkj.top/Article/details/gtyecpmdke.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj20258888.top/Article/details/gtblaeqats.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrhtmbhu.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrbugtvc.html

[O04] 定义异步函数并等待
来源：http://dali.svipenyu.cn/Article/details/gtvuzxzsqu.html

Py:   async def f():⏎    await g()
来源：http://dali.cqqwz.cn/Article/details/gtbyaphapo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yvedp.cn/Article/details/gtserooawx.html

JS:   async function f() { await g(); }
来源：http://dali.shuidangran.top/Article/details/gtvnmjpxju.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtiieprnez.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yvedp.cn/Article/details/gtvbxsuicc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yangfankeji.com/Article/details/gtoesugltu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yuanzhike.top/Article/details/gtchwglewc.html

C#:   async Task F() { await G(); }
来源：http://dali.ydzc1.top/Article/details/gtpprvmirl.html

[O05] 并发执行并等待全部完成
来源：http://dali.sufxvd.cn/Article/details/gtrqkzpnoi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zdqjudy.top/Article/details/gtxffiyzet.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.havefunace.top/Article/details/gtyaudveqj.html

JS:   await Promise.all(tasks)
来源：http://dali.andypj.xyz/Article/details/gtzqzkvsse.html

TS:   await Promise.all(tasks)
来源：http://dali.quarkkingdee.top/Article/details/gtzxriobbp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ybcxt.top/Article/details/gtkihawolf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cashguo.top/Article/details/gtztjhzprg.html

Ruby: threads.map(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gtifdbfiwl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.haohaochexian.top/Article/details/gtksojqwoi.html

[O06] 使用进程池
来源：http://dali.tanke756.top/Article/details/gtbvccdwib.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shangyingyoupin.top/Article/details/gtbiglsmnd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sysykeji.top/Article/details/gttlevhhgz.html

JS:   // child_process / cluster 模块
来源：http://dali.redwolf501.top/Article/details/gtjemjrpss.html

TS:   // child_process / cluster 模块
来源：http://dali.yueranfly.top/Article/details/gtpyplmzaa.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.fzhhl.top/Article/details/gtoibdagnd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cucudq.cn/Article/details/gtwfujxjwu.html

Ruby: // fork 块
来源：http://dali.bjfxy.top/Article/details/gtqeuyydxf.html

C#:   Parallel.For
来源：http://dali.tanke756.top/Article/details/gtxznxomao.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtunmsljze.html

P. 常用工具函数
来源：http://dali.xuanzx.com/Article/details/gtczbtypkp.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtrwbfwysc.html

[P01] 生成 UUID
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkxidswlp.html

Py:   str(uuid.uuid4())
来源：http://dali.xinyue.icu/Article/details/gtbdmokzlm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cucudq.cn/Article/details/gtveiwoyeg.html

JS:   crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gtzhhzvozt.html

TS:   crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gtekhpiyxw.html

Java: UUID.randomUUID().toString()
来源：http://dali.vqdsnc.cn/Article/details/gtrrqbndio.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nwbrower.top/Article/details/gtyvlktojj.html

Ruby: SecureRandom.uuid
来源：http://dali.redwolf501.top/Article/details/gtailanfpw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sufxvd.cn/Article/details/gtlekgknuy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhongyouzk.top/Article/details/gtlpysqsko.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shanyushiyangtech.top/Article/details/gtihnelkae.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jiagoushi.top/Article/details/gtmbqcomos.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.snrcjt.cn/Article/details/gtsezuczur.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yanxiufei.cn/Article/details/gtxmrbhnpu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tanke756.top/Article/details/gtievsxtxz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jqgufenzy.top/Article/details/gthgknpmvw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtypnyugza.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shuidangran.top/Article/details/gtfpgwszvp.html

[P03] 生成短随机字符串
来源：http://dali.cqqwz.cn/Article/details/gtvyygibph.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yonumen.top/Article/details/gtwugzpysr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.iojbl.cn/Article/details/gtuiqiqnvt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenlongwang.top/Article/details/gticbkrsfa.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.smart0.xyz/Article/details/gtnpbroojr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.snrcjt.cn/Article/details/gtdxauhnmt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xinyue.icu/Article/details/gtbomtxecu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hfpthk.cn/Article/details/gtegheutec.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yuanzhike.top/Article/details/gtqzvnkhdb.html

[P04] 求长度
来源：http://dali.shuidangran.top/Article/details/gtpzchzjqt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj202588.top/Article/details/gtgvsskxzn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtpfxhksob.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangdashe.top/Article/details/gtaylzcayd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aibaodan.cn/Article/details/gtuhwrrddb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.redwolf501.top/Article/details/gtazmgcxkp.html

Go:   len(arr);  len(m)
来源：http://dali.zhoulong.xyz/Article/details/gtyomgwmax.html

Ruby: x.length;  x.size
来源：http://dali.nanxuanxn.top/Article/details/gtpctqcwwa.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hywenlv.cn/Article/details/gttgbpciho.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cdnleiting.top/Article/details/gtohjxnlif.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.guowangkeji.top/Article/details/gtpngwddau.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ehwqpu.com/Article/details/gtbdqprtfb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.guowangkeji.top/Article/details/gtxswagsek.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nwbrower.top/Article/details/gtwyjuberv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.pycfn.com/Article/details/gtyqovxdde.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.guannengcc.top/Article/details/gtcnxwaxjf.html

Ruby: a == b
来源：http://dali.shangyingyoupin.top/Article/details/gtxmlxkuzo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yuanzhike.top/Article/details/gtpmhlxuqk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gzhubu.top/Article/details/gtsyzptcwx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nwbrower.top/Article/details/gtsjkcjevw.html

PHP:  if (empty($x)) {}
来源：http://dali.smart0.xyz/Article/details/gtoyoxccck.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hnxiangtu.top/Article/details/gtbzcpswmo.html

TS:   if (x == null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkjmlkwor.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yueranfly.top/Article/details/gtiprpxkoj.html

Go:   if x == nil {}
来源：http://dali.xylfe.cn/Article/details/gtmajapgnd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.fengsongda.top/Article/details/gtfbsulgbt.html

C#:   if (x is null) {}
来源：http://dali.ydzc1.top/Article/details/gtcliotyry.html

[P07] 防抖与节流
来源：http://dali.vqdsnc.cn/Article/details/gtvvocqocx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yvedp.cn/Article/details/gtsgnpazxv.html

PHP:  // 手写时间戳比较
来源：http://dali.ybcxt.top/Article/details/gtofcbgzvl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gogol.net.cn/Article/details/gttjegdxfy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenzaomai.com/Article/details/gttejsxdyq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrqouyzsl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.9152youxi.cn/Article/details/gtdegvzvwn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.fzhhl.top/Article/details/gtgwgvukob.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenlongwang.top/Article/details/gtdvlqyxmq.html

[P08] 处理浮点精度问题
来源：http://dali.sxryk.cn/Article/details/gtffdkyjiz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.vqdsnc.cn/Article/details/gtfipasauu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj20258.top/Article/details/gtygpfjbqj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.c1oappe.top/Article/details/gtwbhtosni.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zycfv.cn/Article/details/gtixqjauea.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.0kj1m.cn/Article/details/gtfuomfqlt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.guannengcc.top/Article/details/gtbidpgvhn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.bjfxy.top/Article/details/gtywevbjkx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cdnleiting.top/Article/details/gtskudiyyo.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpfjwnxs.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hongshengwenyu.top/Article/details/gtilcilcpn.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtibdniund.html

[Q01] 创建表
来源：http://dali.jinghuilouyu.cn/Article/details/gtptyrpgrj.html

CREATE TABLE users (
来源：http://dali.meibo888.top/Article/details/gtxkdyurue.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hfpthk.cn/Article/details/gtmcxddrjr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yanxiufei.cn/Article/details/gtyjxjffxq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.pycfn.com/Article/details/gtihduydqy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.feifeiyinyue.top/Article/details/gtpibwsebl.html

);
来源：http://dali.jiagoushi.top/Article/details/gtyjrudngb.html

[Q02] 创建带外键的表
来源：http://dali.meibo888.top/Article/details/gtzjmaqidf.html

CREATE TABLE orders (
来源：http://dali.shzxlz.cn/Article/details/gtprngifkg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj20258888.top/Article/details/gtrqjrkrib.html

user_id INT NOT NULL,
来源：http://dali.jinqigfzy.top/Article/details/gtbhbktktx.html

amount DECIMAL(10, 2),
来源：http://dali.c1oappe.top/Article/details/gthgmfwusb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yonumen.top/Article/details/gtkoxfhtpb.html

);
来源：http://dali.guowangkeji.top/Article/details/gtxermnjcb.html

[Q03] 增加列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkldfxldh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.mhx1999.top/Article/details/gtxijbbmvh.html

[Q04] 修改列类型
来源：http://dali.xylfe.cn/Article/details/gtmjgbqqkk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.dianchejie.cn/Article/details/gtfbhzgusw.html

[Q05] 重命名列
来源：http://dali.yuxming.cn/Article/details/gtufttrjaz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gaohongyu789.top/Article/details/gtbybvfnsa.html

[Q06] 删除列
来源：http://dali.yonumen.top/Article/details/gthpgabdkn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tian-w.cn/Article/details/gttsraspsz.html

[Q07] 删除表
来源：http://dali.gaohongyu789.top/Article/details/gtzxpfkmlf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtfxwyqnbz.html

[Q08] 创建普通索引
来源：http://dali.dashuyun.cn/Article/details/gtbyttuhsh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.snrcjt.cn/Article/details/gtemksrqsc.html

[Q09] 创建唯一索引
来源：http://dali.9152youxi.cn/Article/details/gtnjsadaac.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shzxlz.cn/Article/details/gtexjzfqqk.html

[Q10] 插入单行
来源：http://dali.bjfxy.top/Article/details/gtzjskirbu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yueranfly.top/Article/details/gthzfoopeh.html

[Q11] 一次插入多行
来源：http://dali.sweek.top/Article/details/gtjckejeyh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj20258.top/Article/details/gtjdjbohlo.html

[Q12] 插入后取自增 ID
来源：http://dali.jqgfzy.top/Article/details/gtwirmxazd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shanyushiyangtech.top/Article/details/gtengriwan.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yongpay.top/Article/details/gtrbxoccag.html

[Q13] 忽略重复插入
来源：http://dali.316326.xyz/Article/details/gtsmysrcfw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tian-w.cn/Article/details/gthlerxqut.html

[Q14] 存在则更新（upsert）
来源：http://dali.shuidangran.top/Article/details/gtasafpkls.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinqigufen.top/Article/details/gtwkijubng.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gtzyqardgw.html

[Q15] 查询全部
来源：http://dali.jqgfzy.top/Article/details/gtgngirlrr.html

SELECT * FROM users;
来源：http://dali.birdmap.top/Article/details/gtzyikepvo.html

[Q16] 查询指定列
来源：http://dali.havefunace.top/Article/details/gtvaegflez.html

SELECT id, name FROM users;
来源：http://dali.fzhhl.top/Article/details/gthvcxrroz.html

[Q17] 条件查询
来源：http://dali.hammf.cn/Article/details/gtfptqltwr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.mhx1999.top/Article/details/gtttifbwtc.html

[Q18] 模糊匹配
来源：http://dali.sxryk.cn/Article/details/gtmbybfrvn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnxiangtu.top/Article/details/gtzxrwznqo.html

[Q19] 范围查询
来源：http://dali.zhoulong.xyz/Article/details/gtsxghrbqi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.9152youxi.cn/Article/details/gtyahfpfku.html

[Q20] IN 列表
来源：http://dali.haohaochexian.top/Article/details/gtlkpogsdd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.quarkkingdee.top/Article/details/gttcbwfuxq.html

[Q21] 空值判断
来源：http://dali.wangdashe.top/Article/details/gtxardazds.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.aibaodan.cn/Article/details/gtddfqbenw.html

[Q22] 排序
来源：http://dali.quarkkingdee.top/Article/details/gtwyelrvbm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.feifeiyinyue.top/Article/details/gtrjyldzqg.html

[Q23] 分页
来源：http://dali.9152youxi.cn/Article/details/gtyurzsivn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tian-w.cn/Article/details/gtuhbnbrey.html

[Q24] 去重
来源：http://dali.zhoulong.xyz/Article/details/gtrwaczzxz.html

SELECT DISTINCT city FROM users;
来源：http://dali.daxiang520.top/Article/details/gtntxzgiho.html

[Q25] 只取前 N 条
来源：http://dali.zycfv.cn/Article/details/gtrsmedcms.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.316326.xyz/Article/details/gtfzbgvxbt.html

[Q26] 计数
来源：http://dali.hywenlv.cn/Article/details/gttqjsotpk.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtvonctppj.html

[Q27] 条件计数
来源：http://dali.dianchejie.cn/Article/details/gtdytkgnjk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.smart0.xyz/Article/details/gtykvltbzb.html

[Q28] 求和与平均
来源：http://dali.sxryk.cn/Article/details/gtdeixbhja.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj20258.top/Article/details/gtyihwrpkh.html

[Q29] 最大最小值
来源：http://dali.ydzc1.top/Article/details/gtylqhckav.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtltdxegns.html

[Q30] 分组统计
来源：http://dali.aizwys.cn/Article/details/gtzqkegifp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jyoumei.cn/Article/details/gtkmjfewmw.html

[Q31] 分组后过滤
来源：http://dali.sweek.top/Article/details/gtgbhisgvh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ybcxt.top/Article/details/gtfpbctfme.html

[Q32] 分组拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gtamasnbdw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gtgnpfkzox.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zycfv.cn/Article/details/gtrzwxidty.html

[Q33] 多列分组
来源：http://dali.chenzaomai.com/Article/details/gthbrawffb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhongyouzk.top/Article/details/gttlqkggtg.html

[Q34] 每组取第一条
来源：http://dali.zdqjudy.top/Article/details/gtvrpisyva.html

SELECT * FROM (
来源：http://dali.daxiang520.top/Article/details/gtkeivvnbw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhongyouzk.top/Article/details/gtfqladcjq.html

) t WHERE rn = 1;
来源：http://dali.yanxiufei.cn/Article/details/gthwlwkueq.html

[Q35] 内连接
来源：http://dali.ydzc1.top/Article/details/gtztqbjkdr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhengqikj.top/Article/details/gthgrcfhre.html


<!-- 参考信息 -->