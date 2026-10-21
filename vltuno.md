代发 wailian999

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.meibo888.top/Article/details/gtwtuljepa.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.c1oappe.top/Article/details/gtnombrlpp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtthfuddym.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gtbxjiqwvt.html

[N05] 最大公约数
来源：http://dali.haohaochexian.top/Article/details/gtxmqlfqim.html

Py:   math.gcd(a, b)
来源：http://dali.sweek.top/Article/details/gtxjivjjyi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.fengsongda.top/Article/details/gtlwwbsntl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gtnkeanjxe.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtsqopvxng.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.aizwys.cn/Article/details/gtxyobsaes.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.wangdashe.top/Article/details/gtxmpddygs.html

Ruby: a.gcd(b)
来源：http://dali.xuanzx.com/Article/details/gtpvofrqze.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yonumen.top/Article/details/gthzqzyerb.html

[N06] 判断回文字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gthxwzhaym.html

Py:   s == s[::-1]
来源：http://dali.c1oappe.top/Article/details/gtxvjvjhzg.html

PHP:  $s === strrev($s);
来源：http://dali.c1oappe.top/Article/details/gtdazmqmgm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gtvsvjoxjx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtsvkyozve.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cashguo.top/Article/details/gtbjkvbscm.html

Go:   // 双指针从两端比较
来源：http://dali.wangdashe.top/Article/details/gtdfsqyrcf.html

Ruby: s == s.reverse
来源：http://dali.guowangkeji.top/Article/details/gtgrmndbgy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zdqjudy.top/Article/details/gtucswzvfm.html

[N07] 两数之和（返回下标）
来源：http://dali.chenzaomai.com/Article/details/gtsrzrueuy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.wangshuangyany.cn/Article/details/gtqpqwmcbi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gogol.net.cn/Article/details/gteotwzjyv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xinyue.icu/Article/details/gtjuofdawf.html

TS:   // 手写 Map<string, number>
来源：http://dali.jlsjyb.cn/Article/details/gtpjemcrzy.html

Java: // 手写 HashMap
来源：http://dali.shuidangran.top/Article/details/gtybwhofah.html

Go:   // 手写 map[int]int
来源：http://dali.kuanghao11.cn/Article/details/gtyicgqwyt.html

Ruby: // 手写 Hash
来源：http://dali.ivvv.top/Article/details/gtnlkjhcbk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinqigfzy.top/Article/details/gtdlzhhntm.html

[N08] 生成全排列
来源：http://dali.daria6918.cn/Article/details/gtmwqlbnqg.html

Py:   itertools.permutations(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtgvfdnfpx.html

PHP:  // 手写递归交换
来源：http://dali.haohaochexian.top/Article/details/gttealdopq.html

JS:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtsfvureyf.html

TS:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtdvcdlmvm.html

Java: // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtqcrrwois.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkendidq.html

Ruby: arr.permutation.to_a
来源：http://dali.chenzaomai.com/Article/details/gtxkuuehag.html

C#:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gturrnkepc.html

[N09] 栈与队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzxjtsim.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gtuvxifvto.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zycfv.cn/Article/details/gtirdfphzy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtdgegdxxm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sufxvd.cn/Article/details/gtovwlipfa.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.quarkkingdee.top/Article/details/gteuryglih.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jiagoushi.top/Article/details/gtxilsswvy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtddxnulec.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj202588.top/Article/details/gtzsqeroqx.html

[N10] 链表节点定义
来源：http://dali.ehwqpu.com/Article/details/gtrnuscbgy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.nanxuanxn.top/Article/details/gtmkebsnil.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cdnleiting.top/Article/details/gtroaiiaiw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cheryme.top/Article/details/gtegpvxhpd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cdnleiting.top/Article/details/gtwnxsusjm.html

Java: class Node { int v; Node next; }
来源：http://dali.gaohongyu789.top/Article/details/gtfdwefzpu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.pengpengdd.cyou/Article/details/gteddvhvop.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yvedp.cn/Article/details/gtmeyvwmys.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.vqdsnc.cn/Article/details/gtfspkppge.html

[N11] 二叉树中序遍历
来源：http://dali.smart0.xyz/Article/details/gtwisynnwe.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.0kj1m.cn/Article/details/gtrieaeiio.html

PHP:  // 手写递归函数
来源：http://dali.xylfe.cn/Article/details/gtmgygakpv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.andypj.xyz/Article/details/gtyzhtcfpk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yueranfly.top/Article/details/gtbgbgwquf.html

Java: // 手写递归
来源：http://dali.xylfe.cn/Article/details/gtunrhpslg.html

Go:   // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gtdeqrpoaw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.daria6918.cn/Article/details/gtknzotybv.html

C#:   // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gtjcekcirc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xinyue.icu/Article/details/gtcfuijaaa.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.daxiang520.top/Article/details/gtswzadgfo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shuidangran.top/Article/details/gtkdbzgplb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.haohaochexian.top/Article/details/gtsowbjiud.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.c1oappe.top/Article/details/gtwgeahgfm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.bjfxy.top/Article/details/gtzjoonetd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shuidangran.top/Article/details/gtthgarnob.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.0kj1m.cn/Article/details/gtiqvbitwz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ydzc1.top/Article/details/gtjqpsnnuv.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtejpgydqb.html

O. 并发与异步
来源：http://dali.0kj1m.cn/Article/details/gtqjagbduu.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtfwswvmyi.html

[O01] 启动一个线程
来源：http://dali.cashguo.top/Article/details/gtaeitbdyi.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenlongwang.top/Article/details/gtpspietrc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sysykeji.top/Article/details/gtihzokcda.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinqigfzy.top/Article/details/gthstrmetp.html

TS:   // 同 JS
来源：http://dali.bjfxy.top/Article/details/gtketwvpwk.html

Java: new Thread(() -> f()).start()
来源：http://dali.nwbrower.top/Article/details/gthlappmby.html

Go:   go f()
来源：http://dali.zhaomingkeji.xyz/Article/details/gteuhkcftb.html

Ruby: Thread.new { f }
来源：http://dali.cashguo.top/Article/details/gtktlxrkeo.html

C#:   Task.Run(() => F());
来源：http://dali.yanxiufei.cn/Article/details/gtibdfbusm.html

[O02] 使用线程池
来源：http://dali.mhx1999.top/Article/details/gtudebioab.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj20258888.top/Article/details/gtuxmsurlz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.daxiang520.top/Article/details/gtvqwndxgx.html

JS:   // worker_threads 线程池
来源：http://dali.tian-w.cn/Article/details/gtkmzskywe.html

TS:   // worker_threads 线程池
来源：http://dali.shangyingyoupin.top/Article/details/gtkcrpzoag.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jqgufenzy.top/Article/details/gtfyeiwffy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj202588.top/Article/details/gtocyfmdvv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.wangdashe.top/Article/details/gtabibinnj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cdnleiting.top/Article/details/gtfrbzqxaz.html

[O03] 加锁保护共享数据
来源：http://dali.hnqzz.top/Article/details/gtwdobclyv.html

Py:   with lock: shared += 1
来源：http://dali.cashguo.top/Article/details/gthdpmyhtr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.mhx1999.top/Article/details/gtevciyunl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.kuanghao11.cn/Article/details/gtaubkeynx.html

TS:   // 同 JS
来源：http://dali.sxryk.cn/Article/details/gtlbybpbfv.html

Java: synchronized (this) { shared++; }
来源：http://dali.fengsongda.top/Article/details/gttgfebyaf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shangyingyoupin.top/Article/details/gtylfercjf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.daxiang520.top/Article/details/gtdvzzarnu.html

C#:   lock (gate) { shared++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbaleznom.html

[O04] 定义异步函数并等待
来源：http://dali.xuanzx.com/Article/details/gtjzujnyjh.html

Py:   async def f():⏎    await g()
来源：http://dali.ybcxt.top/Article/details/gtigjliihd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.haohaochexian.top/Article/details/gtxosozbgb.html

JS:   async function f() { await g(); }
来源：http://dali.zhixingplan.top/Article/details/gtvwdawmsy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.daxiang520.top/Article/details/gtpnxtvdgu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gtyyhgdyhz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.snrcjt.cn/Article/details/gtwivlnjln.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hnqzz.top/Article/details/gtwomsqcgc.html

C#:   async Task F() { await G(); }
来源：http://dali.aibaodan.cn/Article/details/gtwdvpimut.html

[O05] 并发执行并等待全部完成
来源：http://dali.guowangkeji.top/Article/details/gtpxhayfbl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrxcwosf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.wangshuangyany.cn/Article/details/gtvjcxqycb.html

JS:   await Promise.all(tasks)
来源：http://dali.daria6918.cn/Article/details/gtmvrgotkm.html

TS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gtcldsgkrd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nanxuanxn.top/Article/details/gtmawsdyir.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zdqjudy.top/Article/details/gtpltzlzkl.html

Ruby: threads.map(&:join)
来源：http://dali.yongpay.top/Article/details/gtyjtnzbzf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nanxinkj.top/Article/details/gthliffadz.html

[O06] 使用进程池
来源：http://dali.hongshengwenyu.top/Article/details/gtvwlppvlc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jiagoushi.top/Article/details/gtxrmablsf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sysykeji.top/Article/details/gtxvsrzubw.html

JS:   // child_process / cluster 模块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrixgllha.html

TS:   // child_process / cluster 模块
来源：http://dali.tianlin.xyz/Article/details/gtfubehplh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvhpjnwe.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.chenzaomai.com/Article/details/gtabccraiw.html

Ruby: // fork 块
来源：http://dali.fzhhl.top/Article/details/gttcpynzjh.html

C#:   Parallel.For
来源：http://dali.hfpthk.cn/Article/details/gtzaxaryyc.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtrsxfybqs.html

P. 常用工具函数
来源：http://dali.nanxinkj.top/Article/details/gtlvxygbmd.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtoqxhdysq.html

[P01] 生成 UUID
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwgemivt.html

Py:   str(uuid.uuid4())
来源：http://dali.jianghu66.top/Article/details/gtcnpemolm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sysykeji.top/Article/details/gtotflhwgv.html

JS:   crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gtwxgvknli.html

TS:   crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gtqgpvvuec.html

Java: UUID.randomUUID().toString()
来源：http://dali.shzxlz.cn/Article/details/gtrezopxpg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gzhubu.top/Article/details/gtmygexzsq.html

Ruby: SecureRandom.uuid
来源：http://dali.bjfxy.top/Article/details/gtxlnlmfqn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hfpthk.cn/Article/details/gtbosauizu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hongshengwenyu.top/Article/details/gtewiiyorp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zdqjudy.top/Article/details/gtidhcxhck.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hammf.cn/Article/details/gtkcwdbmed.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlfnblrj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.guowangkeji.top/Article/details/gthtfdxmco.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gotoacloud.top/Article/details/gtvatgjitm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xziqi.cn/Article/details/gtydrbxrqq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinqigfzy.top/Article/details/gtymqataih.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yonumen.top/Article/details/gtvstwndmd.html

[P03] 生成短随机字符串
来源：http://dali.aizwys.cn/Article/details/gtmtgkeixk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hfpthk.cn/Article/details/gthmweylzc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhixingplan.top/Article/details/gtdujopxop.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.0kj1m.cn/Article/details/gtdtfjglhx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daxiang520.top/Article/details/gthyuxjofu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hfpthk.cn/Article/details/gtrrzlkcrb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shanyushiyangtech.top/Article/details/gtwphxvhuu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj20258.top/Article/details/gtelrqchxf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.andypj.xyz/Article/details/gtrnghgapr.html

[P04] 求长度
来源：http://dali.jinqigufen.top/Article/details/gtydnfrpoh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuanzhike.top/Article/details/gtlyaymkpm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtdcfkfroh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.vqdsnc.cn/Article/details/gtdehqdvfg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yueranfly.top/Article/details/gtsrkbqqeg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jiagoushi.top/Article/details/gtgaprjthh.html

Go:   len(arr);  len(m)
来源：http://dali.pycfn.com/Article/details/gtyuffaubq.html

Ruby: x.length;  x.size
来源：http://dali.tianlin.xyz/Article/details/gtbxugtjua.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gogol.net.cn/Article/details/gthzmrghys.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyoumkphq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jyoumei.cn/Article/details/gtqeudpfge.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hnxiangtu.top/Article/details/gtukthntcz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.haohaochexian.top/Article/details/gtnagouvac.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cashguo.top/Article/details/gtvldkcmuz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.316326.xyz/Article/details/gtdejizbba.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yonumen.top/Article/details/gtrbfzftve.html

Ruby: a == b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmtzisrrg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tian-w.cn/Article/details/gtcxwtokqy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.c1oappe.top/Article/details/gtgrpmncuu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ppjwa.cn/Article/details/gteopdywex.html

PHP:  if (empty($x)) {}
来源：http://dali.redwolf501.top/Article/details/gtdbemnfao.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hywenlv.cn/Article/details/gthbxbivek.html

TS:   if (x == null) {}
来源：http://dali.iojbl.cn/Article/details/gtpyqtytlc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gtfkjmlyhi.html

Go:   if x == nil {}
来源：http://dali.xylfe.cn/Article/details/gtayqrmkwk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhongyouzk.top/Article/details/gtquzkekbj.html

C#:   if (x is null) {}
来源：http://dali.yuxming.cn/Article/details/gtxjdoaqrj.html

[P07] 防抖与节流
来源：http://dali.tian-w.cn/Article/details/gtpknswrrc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ybcxt.top/Article/details/gtibnybnyp.html

PHP:  // 手写时间戳比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfrlaxely.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangdashe.top/Article/details/gtpgvnlyyv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gtjfusdawa.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.snrcjt.cn/Article/details/gtywoojyjz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ydzc1.top/Article/details/gtknzbfznk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.pengpengdd.cyou/Article/details/gtielefryj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hysaishi.cn/Article/details/gtasskkyjg.html

[P08] 处理浮点精度问题
来源：http://dali.zhongyouzk.top/Article/details/gtmdlyxbbp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yonumen.top/Article/details/gtbncukfpz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.316326.xyz/Article/details/gtreglaobb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.vqdsnc.cn/Article/details/gtodireayd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.nwbrower.top/Article/details/gthgnwsami.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.quarkkingdee.top/Article/details/gtaaxfcjlg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.andypj.xyz/Article/details/gtguznnatx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yanxiufei.cn/Article/details/gtrlckttzg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.snrcjt.cn/Article/details/gtmklfklyv.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtegijpxyj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.redwolf501.top/Article/details/gtjqotctpg.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtcpblajlg.html

[Q01] 创建表
来源：http://dali.yj20258888.top/Article/details/gtbicrqwdy.html

CREATE TABLE users (
来源：http://dali.hysaishi.cn/Article/details/gtyaojkfyb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigufen.top/Article/details/gtckpyqjbq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ppjwa.cn/Article/details/gtcdbuyzgv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.9152youxi.cn/Article/details/gtzozwdldg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj20258888.top/Article/details/gtygcjhdbg.html

);
来源：http://dali.iojbl.cn/Article/details/gtelljiend.html

[Q02] 创建带外键的表
来源：http://dali.gogol.net.cn/Article/details/gtplpeafje.html

CREATE TABLE orders (
来源：http://dali.chenzaomai.com/Article/details/gtlfoibmxh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cdnleiting.top/Article/details/gtwtfvkuql.html

user_id INT NOT NULL,
来源：http://dali.jqgfzy.top/Article/details/gtkzublccd.html

amount DECIMAL(10, 2),
来源：http://dali.zdqjudy.top/Article/details/gtxsdbfybj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhoulong.xyz/Article/details/gtukrxdrfy.html

);
来源：http://dali.yuanzhike.top/Article/details/gtvsxamfdw.html

[Q03] 增加列
来源：http://dali.tanke756.top/Article/details/gtpodfyhjd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhiwuduotai.top/Article/details/gtyxkthzie.html

[Q04] 修改列类型
来源：http://dali.shuidangran.top/Article/details/gtoxrwpzyz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gaohongyu789.top/Article/details/gtifvkpzeb.html

[Q05] 重命名列
来源：http://dali.sxryk.cn/Article/details/gtqructsoe.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gterpvzcrg.html

[Q06] 删除列
来源：http://dali.cdnleiting.top/Article/details/gtpguctezn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenjidiqi.icu/Article/details/gtzoyfejba.html

[Q07] 删除表
来源：http://dali.shangyingyoupin.top/Article/details/gtdolagedc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zdqjudy.top/Article/details/gtxvyhptvw.html

[Q08] 创建普通索引
来源：http://dali.yonumen.top/Article/details/gtvwqvqesd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yvedp.cn/Article/details/gtyakujehp.html

[Q09] 创建唯一索引
来源：http://dali.svipenyu.cn/Article/details/gtkflhgtab.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.0kj1m.cn/Article/details/gtkvmirzcf.html

[Q10] 插入单行
来源：http://dali.meibo888.top/Article/details/gtjaahcdap.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.guannengcc.top/Article/details/gtwnkatkae.html

[Q11] 一次插入多行
来源：http://dali.hfpthk.cn/Article/details/gtrcxptaxc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.chenjidiqi.icu/Article/details/gtcqzbvkjy.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gthmtjmqwa.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.c1oappe.top/Article/details/gtscypkhmn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tianlin.xyz/Article/details/gtrgykqeja.html

[Q13] 忽略重复插入
来源：http://dali.shangyingyoupin.top/Article/details/gtddxejsbi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pycfn.com/Article/details/gtvqdakbyg.html

[Q14] 存在则更新（upsert）
来源：http://dali.tanke756.top/Article/details/gtgtcskpqy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinqigufen.top/Article/details/gtgjvrfmpe.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jianghu66.top/Article/details/gtcbsnycgl.html

[Q15] 查询全部
来源：http://dali.hywenlv.cn/Article/details/gtudrkzthg.html

SELECT * FROM users;
来源：http://dali.jianghu66.top/Article/details/gtntccaoiq.html

[Q16] 查询指定列
来源：http://dali.xziqi.cn/Article/details/gtgdequesh.html

SELECT id, name FROM users;
来源：http://dali.fzhhl.top/Article/details/gtixxjfvsi.html

[Q17] 条件查询
来源：http://dali.9152youxi.cn/Article/details/gtciohrejy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jyoumei.cn/Article/details/gtsbenriej.html

[Q18] 模糊匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtyzpjvtcy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yonumen.top/Article/details/gtotqfedkv.html

[Q19] 范围查询
来源：http://dali.yuanzhike.top/Article/details/gtradgmnit.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cashguo.top/Article/details/gtwwcmlwle.html

[Q20] IN 列表
来源：http://dali.ybcxt.top/Article/details/gtwxmvyjns.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.daxiang520.top/Article/details/gtceutijck.html

[Q21] 空值判断
来源：http://dali.aibaodan.cn/Article/details/gtbewndnlt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yongpay.top/Article/details/gthdioaeha.html

[Q22] 排序
来源：http://dali.xinyue.icu/Article/details/gtdtkhzfro.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xuanzx.com/Article/details/gtpjptpojm.html

[Q23] 分页
来源：http://dali.xuetiantiany.cn/Article/details/gtmmrnvrcx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gzhubu.top/Article/details/gtdqugkask.html

[Q24] 去重
来源：http://dali.sysykeji.top/Article/details/gtddbnathd.html

SELECT DISTINCT city FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtqbwvsdwk.html

[Q25] 只取前 N 条
来源：http://dali.cheryme.top/Article/details/gtfzdzkzgk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.aizwys.cn/Article/details/gtcjtemfvu.html

[Q26] 计数
来源：http://dali.nwbrower.top/Article/details/gtvkfoufxu.html

SELECT COUNT(*) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtmayodtqj.html

[Q27] 条件计数
来源：http://dali.jqgufenzy.top/Article/details/gtirxyruqy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtyghpcebm.html

[Q28] 求和与平均
来源：http://dali.gogol.net.cn/Article/details/gthtnxiipd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtasuuouda.html

[Q29] 最大最小值
来源：http://dali.gzhubu.top/Article/details/gtyofwzjbn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtlxsglawg.html

[Q30] 分组统计
来源：http://dali.fengsongda.top/Article/details/gtxeejewrs.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gtwcoxzbix.html

[Q31] 分组后过滤
来源：http://dali.quarkkingdee.top/Article/details/gtnbyvsbmq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hywenlv.cn/Article/details/gtyaxopxko.html

[Q32] 分组拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gtgnxjhrfs.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gtefiupztv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jlsjyb.cn/Article/details/gtqnasqizd.html

[Q33] 多列分组
来源：http://dali.iojbl.cn/Article/details/gtgiuzshmy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jqgfzy.top/Article/details/gtrflmsrml.html

[Q34] 每组取第一条
来源：http://dali.guowangkeji.top/Article/details/gtijnhbfmz.html

SELECT * FROM (
来源：http://dali.jinghuilouyu.cn/Article/details/gtizulcqvm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.svipenyu.cn/Article/details/gtndctsoas.html

) t WHERE rn = 1;
来源：http://dali.ppjwa.cn/Article/details/gtqaktaxmq.html

[Q35] 内连接
来源：http://dali.yueranfly.top/Article/details/gtiripyjff.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gtotwhlypd.html

[Q36] 左连接
来源：http://dali.gzhubu.top/Article/details/gtsecsjmki.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.haohaochexian.top/Article/details/gtfpbfxaio.html

[Q37] 右连接
来源：http://dali.feifeiyinyue.top/Article/details/gteymdtvhm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.guannengcc.top/Article/details/gtfikpezzb.html


<!-- 参考信息 -->