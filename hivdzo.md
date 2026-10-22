代发 wailian999

[N05] 最大公约数
来源：http://dali.daxiang520.top/Article/details/gtqsysdkft.html

Py:   math.gcd(a, b)
来源：http://dali.ehwqpu.com/Article/details/gtyuzyabmz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yuxming.cn/Article/details/gtfqxatodj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shangyingyoupin.top/Article/details/gtxsqzlate.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hywenlv.cn/Article/details/gtpnvksoyh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nanxinkj.top/Article/details/gtvisdxniz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.snrcjt.cn/Article/details/gtgchzdixz.html

Ruby: a.gcd(b)
来源：http://dali.9152youxi.cn/Article/details/gtbllrhapq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tanke756.top/Article/details/gtpfaorvum.html

[N06] 判断回文字符串
来源：http://dali.aibaodan.cn/Article/details/gtwdyzdfrm.html

Py:   s == s[::-1]
来源：http://dali.snrcjt.cn/Article/details/gtvpbbgqkm.html

PHP:  $s === strrev($s);
来源：http://dali.jqgfzy.top/Article/details/gtoegdhexd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtzxpuqloh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtxhpkymtm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ydzc1.top/Article/details/gtvuiwndnf.html

Go:   // 双指针从两端比较
来源：http://dali.feifeiyinyue.top/Article/details/gtuzlzlltx.html

Ruby: s == s.reverse
来源：http://dali.gogol.net.cn/Article/details/gtciuueadi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gtrrfpbqtd.html

[N07] 两数之和（返回下标）
来源：http://dali.9152youxi.cn/Article/details/gtzuhqwfoa.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.birdmap.top/Article/details/gtptkpyfpk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlvuqssiu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yueranfly.top/Article/details/gtclftzcfq.html

TS:   // 手写 Map<string, number>
来源：http://dali.shangyingyoupin.top/Article/details/gthklhdztx.html

Java: // 手写 HashMap
来源：http://dali.sufxvd.cn/Article/details/gtoqqrobmj.html

Go:   // 手写 map[int]int
来源：http://dali.hywenlv.cn/Article/details/gtbczfajas.html

Ruby: // 手写 Hash
来源：http://dali.birdmap.top/Article/details/gtrctntnug.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.aizwys.cn/Article/details/gtnhdngcpm.html

[N08] 生成全排列
来源：http://dali.9152youxi.cn/Article/details/gtnlrbeksi.html

Py:   itertools.permutations(arr)
来源：http://dali.gzhubu.top/Article/details/gtoyxnqpct.html

PHP:  // 手写递归交换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkxoxllmd.html

JS:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqswdycbj.html

TS:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gtluvuhbsb.html

Java: // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtfnsxnzcy.html

Go:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtavbbeeqx.html

Ruby: arr.permutation.to_a
来源：http://dali.gaohongyu789.top/Article/details/gtwikpqqmd.html

C#:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gtxallzkfk.html

[N09] 栈与队列
来源：http://dali.smart0.xyz/Article/details/gtwzmnpenl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.meibo888.top/Article/details/gtmblxtepv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xinyue.icu/Article/details/gtstyxezaf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cucudq.cn/Article/details/gtgnnngdho.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqaocxwv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenlongwang.top/Article/details/gtzspwutcz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ybcxt.top/Article/details/gtllxvresc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtojcqgqrh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.aizwys.cn/Article/details/gtwejbbbbc.html

[N10] 链表节点定义
来源：http://dali.bjfxy.top/Article/details/gtqocjowrw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ydzc1.top/Article/details/gtfgluezxw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.guowangkeji.top/Article/details/gthlwbgpzq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.daria6918.cn/Article/details/gtnnpjjeeu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ppjwa.cn/Article/details/gtialubsur.html

Java: class Node { int v; Node next; }
来源：http://dali.shangyingyoupin.top/Article/details/gtjjdwjzif.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hnxiangtu.top/Article/details/gtgljbjped.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yanxiufei.cn/Article/details/gtndxwtmzb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hfpthk.cn/Article/details/gtbrnramsb.html

[N11] 二叉树中序遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtjznptsaz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.tanke756.top/Article/details/gtjqljazjg.html

PHP:  // 手写递归函数
来源：http://dali.zhixingplan.top/Article/details/gtwvktehzk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gtyhyvttct.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.svipenyu.cn/Article/details/gtoznggesl.html

Java: // 手写递归
来源：http://dali.nwbrower.top/Article/details/gtzfvhxrat.html

Go:   // 手写递归
来源：http://dali.yuxming.cn/Article/details/gtsqgbydra.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hongshengwenyu.top/Article/details/gtkwwcvbbs.html

C#:   // 手写递归
来源：http://dali.haohaochexian.top/Article/details/gtzsotyofy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nanxinkj.top/Article/details/gttprdgknh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jiagoushi.top/Article/details/gtyfnkqugp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jianghu66.top/Article/details/gtpwppjgav.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhoulong.xyz/Article/details/gtqqlbejey.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gtqxhecgbm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgufenzy.top/Article/details/gtxzqqlwrz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.9152youxi.cn/Article/details/gtxrafdhim.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.tanke756.top/Article/details/gttqrpgxwl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhixingplan.top/Article/details/gttejxfdak.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gttsuvrixf.html

O. 并发与异步
来源：http://dali.tianlin.xyz/Article/details/gtwymmbeso.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtpjgbmswo.html

[O01] 启动一个线程
来源：http://dali.yanxiufei.cn/Article/details/gtcnagoaxx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ivvv.top/Article/details/gttqatarbw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ybcxt.top/Article/details/gtekksyvoz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hammf.cn/Article/details/gtuzlfbdxr.html

TS:   // 同 JS
来源：http://dali.9152youxi.cn/Article/details/gtwnvxhzbo.html

Java: new Thread(() -> f()).start()
来源：http://dali.wangdashe.top/Article/details/gtilxmbpma.html

Go:   go f()
来源：http://dali.meibo888.top/Article/details/gtgpfuzasv.html

Ruby: Thread.new { f }
来源：http://dali.daria6918.cn/Article/details/gtjfkjaaux.html

C#:   Task.Run(() => F());
来源：http://dali.hywenlv.cn/Article/details/gttjcpvjdh.html

[O02] 使用线程池
来源：http://dali.chenjidiqi.icu/Article/details/gtquhpvvut.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.quarkkingdee.top/Article/details/gtaukrnqwq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hywenlv.cn/Article/details/gtzceytsur.html

JS:   // worker_threads 线程池
来源：http://dali.dianchejie.cn/Article/details/gttixemlrm.html

TS:   // worker_threads 线程池
来源：http://dali.daxiang520.top/Article/details/gtcvwbcvyn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jiagoushi.top/Article/details/gtccxcoyfy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.daria6918.cn/Article/details/gthrermcrg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj20258888.top/Article/details/gtakvdjmhu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.bjfxy.top/Article/details/gtafmzkibk.html

[O03] 加锁保护共享数据
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlgslnzxe.html

Py:   with lock: shared += 1
来源：http://dali.xziqi.cn/Article/details/gtsmdbkdac.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hammf.cn/Article/details/gtjkmxmprp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gotoacloud.top/Article/details/gtmewhfvpw.html

TS:   // 同 JS
来源：http://dali.daxiang520.top/Article/details/gteydrtfrd.html

Java: synchronized (this) { shared++; }
来源：http://dali.aibaodan.cn/Article/details/gtyezppiod.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hongshengwenyu.top/Article/details/gtraxxxvyq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinqigfzy.top/Article/details/gtufzqilzf.html

C#:   lock (gate) { shared++; }
来源：http://dali.316326.xyz/Article/details/gtbthhssih.html

[O04] 定义异步函数并等待
来源：http://dali.xziqi.cn/Article/details/gthescwdxz.html

Py:   async def f():⏎    await g()
来源：http://dali.yangfankeji.com/Article/details/gtawxkjmch.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.meibo888.top/Article/details/gtptudvzbr.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gtkibngrri.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hywenlv.cn/Article/details/gthotqsshf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenlongwang.top/Article/details/gtpdeedfko.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.haohaochexian.top/Article/details/gtwyripect.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.svipenyu.cn/Article/details/gtdujqtpwg.html

C#:   async Task F() { await G(); }
来源：http://dali.yj202588.top/Article/details/gtwbhizjph.html

[O05] 并发执行并等待全部完成
来源：http://dali.ehwqpu.com/Article/details/gtylxltqck.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthgaevrzc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nanxuanxn.top/Article/details/gtpjtotyns.html

JS:   await Promise.all(tasks)
来源：http://dali.yuanzhike.top/Article/details/gtfpskgpxb.html

TS:   await Promise.all(tasks)
来源：http://dali.0kj1m.cn/Article/details/gtkkaocfxi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jyoumei.cn/Article/details/gtevzjsxtk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.chenzaomai.com/Article/details/gtzepqcvvi.html

Ruby: threads.map(&:join)
来源：http://dali.redwolf501.top/Article/details/gtdzmtwcxo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.pengpengdd.cyou/Article/details/gtmnldmkrl.html

[O06] 使用进程池
来源：http://dali.gaohongyu789.top/Article/details/gtuqngylzm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.pengpengdd.cyou/Article/details/gtejglyjbv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jqgufenzy.top/Article/details/gtvxnqxdjw.html

JS:   // child_process / cluster 模块
来源：http://dali.jinqigufen.top/Article/details/gtndtayuyh.html

TS:   // child_process / cluster 模块
来源：http://dali.nanxinkj.top/Article/details/gterttajni.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sxryk.cn/Article/details/gtclkwbjnw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.fzhhl.top/Article/details/gtruvrgbhf.html

Ruby: // fork 块
来源：http://dali.shuidangran.top/Article/details/gtfjqfnphx.html

C#:   Parallel.For
来源：http://dali.zycfv.cn/Article/details/gtxgcrgcmb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtbdbakyhf.html

P. 常用工具函数
来源：http://dali.tianlin.xyz/Article/details/gtmdtgjhld.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtycrewoyf.html

[P01] 生成 UUID
来源：http://dali.meibo888.top/Article/details/gtcyvtxnxq.html

Py:   str(uuid.uuid4())
来源：http://dali.fengsongda.top/Article/details/gtucoelodg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.mhx1999.top/Article/details/gtjgwfrqdq.html

JS:   crypto.randomUUID()
来源：http://dali.jinqigfzy.top/Article/details/gttusizvek.html

TS:   crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gtprtwarug.html

Java: UUID.randomUUID().toString()
来源：http://dali.yuanzhike.top/Article/details/gtnjzqlebo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hywenlv.cn/Article/details/gtlmyrjmsu.html

Ruby: SecureRandom.uuid
来源：http://dali.aibaodan.cn/Article/details/gtocrilbmg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cqqwz.cn/Article/details/gtjcocxhsn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cqqwz.cn/Article/details/gtvqpeeljz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hnxiangtu.top/Article/details/gtryjavdby.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xylfe.cn/Article/details/gtmslwszax.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shuidangran.top/Article/details/gtkhrrghpn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.daxiang520.top/Article/details/gtqbpsazab.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gtlrmogkwh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gogol.net.cn/Article/details/gtzhgdfnvx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.chenzaomai.com/Article/details/gtkhcrzhgc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.guannengcc.top/Article/details/gttowwnjdy.html

[P03] 生成短随机字符串
来源：http://dali.cdnleiting.top/Article/details/gtojrdhpip.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.aibaodan.cn/Article/details/gtrnqipfkp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.guowangkeji.top/Article/details/gtshjvfbro.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shzxlz.cn/Article/details/gtqulzkgaq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.316326.xyz/Article/details/gticmitikn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tianlin.xyz/Article/details/gtmhzppcng.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nanxinkj.top/Article/details/gtrdmktbuh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gotoacloud.top/Article/details/gtcbjuijfd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.quarkkingdee.top/Article/details/gtxidjmqjt.html

[P04] 求长度
来源：http://dali.ivvv.top/Article/details/gtixnsnqqm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.snrcjt.cn/Article/details/gtlgoxoory.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gtzdxlsnjn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yanxiufei.cn/Article/details/gtpugendjp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ppjwa.cn/Article/details/gtnfbvtcmw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.wangshuangyany.cn/Article/details/gttbjpoujn.html

Go:   len(arr);  len(m)
来源：http://dali.mhx1999.top/Article/details/gtcmmjzjhx.html

Ruby: x.length;  x.size
来源：http://dali.kuanghao11.cn/Article/details/gtrcewvmtl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.9152youxi.cn/Article/details/gtkoorrbdg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ybcxt.top/Article/details/gtcqmozmdu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.vqdsnc.cn/Article/details/gtzekuafaf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gtcqqmrshy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xziqi.cn/Article/details/gtbvwfnqsv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cashguo.top/Article/details/gtkqksnnqp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hnqzz.top/Article/details/gthggtimqj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjyoqftq.html

Ruby: a == b
来源：http://dali.smart0.xyz/Article/details/gtgmupgerq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zycfv.cn/Article/details/gtuxytdpdl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zycfv.cn/Article/details/gtocpxdqsq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.guannengcc.top/Article/details/gtvbxrswbc.html

PHP:  if (empty($x)) {}
来源：http://dali.haohaochexian.top/Article/details/gthespxbsl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinqigfzy.top/Article/details/gtprrllhor.html

TS:   if (x == null) {}
来源：http://dali.shzxlz.cn/Article/details/gttgzhucdl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yanxiufei.cn/Article/details/gtiiicxqcx.html

Go:   if x == nil {}
来源：http://dali.316326.xyz/Article/details/gtmpjdibod.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xziqi.cn/Article/details/gtgaepwnan.html

C#:   if (x is null) {}
来源：http://dali.daria6918.cn/Article/details/gtysjuopvd.html

[P07] 防抖与节流
来源：http://dali.sysykeji.top/Article/details/gtprigtono.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hfpthk.cn/Article/details/gtiaqefwnq.html

PHP:  // 手写时间戳比较
来源：http://dali.xylfe.cn/Article/details/gtjwegfula.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gtjcfbjbzi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gtmiewwfyo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gtgknotabw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj20258.top/Article/details/gtrzicejxd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yvedp.cn/Article/details/gtdicochpr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hammf.cn/Article/details/gtkhbuhojb.html

[P08] 处理浮点精度问题
来源：http://dali.zhiwuduotai.top/Article/details/gtcavjyzxh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.316326.xyz/Article/details/gthlbhlfeg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cqqwz.cn/Article/details/gtefazrmtp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jianghu66.top/Article/details/gtbiihngev.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.svipenyu.cn/Article/details/gtjmeryyiv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jqgfzy.top/Article/details/gtjzevputd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sxryk.cn/Article/details/gtagszbxek.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.aizwys.cn/Article/details/gtgmjwqqll.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxuanxn.top/Article/details/gtismjsfqf.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtydidqxck.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hfpthk.cn/Article/details/gtcgaftejw.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtcntxgtsi.html

[Q01] 创建表
来源：http://dali.yongpay.top/Article/details/gtirwblcew.html

CREATE TABLE users (
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfmykyun.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ydzc1.top/Article/details/gthxcznnek.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yuxming.cn/Article/details/gtbrfdmpbe.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yuxming.cn/Article/details/gtrburawsd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hfpthk.cn/Article/details/gtmjjdiuli.html

);
来源：http://dali.xinyue.icu/Article/details/gtfcqmbats.html

[Q02] 创建带外键的表
来源：http://dali.pengpengdd.cyou/Article/details/gtueqkdhsq.html

CREATE TABLE orders (
来源：http://dali.feifeiyinyue.top/Article/details/gtznoymikg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jyoumei.cn/Article/details/gtyozhrpvo.html

user_id INT NOT NULL,
来源：http://dali.quarkkingdee.top/Article/details/gtnhzmbdic.html

amount DECIMAL(10, 2),
来源：http://dali.yj202588.top/Article/details/gtzifzddlc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmcvbnby.html

);
来源：http://dali.xinyue.icu/Article/details/gtjuzncfsh.html

[Q03] 增加列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtclncrslq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.aizwys.cn/Article/details/gtzxceysxu.html

[Q04] 修改列类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtlqsrftts.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jyoumei.cn/Article/details/gtozsrnjao.html

[Q05] 重命名列
来源：http://dali.tianlin.xyz/Article/details/gtoucjxxxf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ppjwa.cn/Article/details/gttgpwwwff.html

[Q06] 删除列
来源：http://dali.vqdsnc.cn/Article/details/gtgplbzlmx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.fengsongda.top/Article/details/gtbwsttjvc.html

[Q07] 删除表
来源：http://dali.jiagoushi.top/Article/details/gtlrbdajic.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenzaomai.com/Article/details/gtzflmpxsj.html

[Q08] 创建普通索引
来源：http://dali.ivvv.top/Article/details/gtcaflxjka.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shangyingyoupin.top/Article/details/gtrdcsolim.html

[Q09] 创建唯一索引
来源：http://dali.zhoulong.xyz/Article/details/gtlbtdjgvj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xylfe.cn/Article/details/gtmvusapzr.html

[Q10] 插入单行
来源：http://dali.cashguo.top/Article/details/gtjzfzctcw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hammf.cn/Article/details/gtwcpkbbwp.html

[Q11] 一次插入多行
来源：http://dali.yangfankeji.com/Article/details/gtfmgsrnny.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.smart0.xyz/Article/details/gtecapebbq.html

[Q12] 插入后取自增 ID
来源：http://dali.9152youxi.cn/Article/details/gtvhopwwaw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zdqjudy.top/Article/details/gtkkwpzdim.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cdnleiting.top/Article/details/gttokymcvh.html

[Q13] 忽略重复插入
来源：http://dali.sweek.top/Article/details/gtimudtukm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jqgfzy.top/Article/details/gtmzvjahmm.html

[Q14] 存在则更新（upsert）
来源：http://dali.iojbl.cn/Article/details/gtambsdpxp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.feifeiyinyue.top/Article/details/gtrogjslep.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.0kj1m.cn/Article/details/gtogjrmsmz.html

[Q15] 查询全部
来源：http://dali.9152youxi.cn/Article/details/gtrhyisktz.html

SELECT * FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtfwczggce.html

[Q16] 查询指定列
来源：http://dali.hnqzz.top/Article/details/gtbsbklgoz.html

SELECT id, name FROM users;
来源：http://dali.redwolf501.top/Article/details/gtxltwlidw.html

[Q17] 条件查询
来源：http://dali.316326.xyz/Article/details/gtuofjgwpk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj20258888.top/Article/details/gthcspezjg.html

[Q18] 模糊匹配
来源：http://dali.sxryk.cn/Article/details/gtttiymcmd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yangfankeji.com/Article/details/gtpwabvckx.html

[Q19] 范围查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghrxvnxb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jlsjyb.cn/Article/details/gthoscqisf.html

[Q20] IN 列表
来源：http://dali.jinghuilouyu.cn/Article/details/gtycglqgfq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cheryme.top/Article/details/gtjrsivvqa.html

[Q21] 空值判断
来源：http://dali.haohaochexian.top/Article/details/gtomgejyvj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yueranfly.top/Article/details/gthecsmogr.html

[Q22] 排序
来源：http://dali.xuetiantiany.cn/Article/details/gttpzzcwtn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xuanzx.com/Article/details/gtbtiivvkx.html

[Q23] 分页
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhejpxfq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.vqdsnc.cn/Article/details/gtxjrhmznl.html

[Q24] 去重
来源：http://dali.gotoacloud.top/Article/details/gthkpjxhow.html

SELECT DISTINCT city FROM users;
来源：http://dali.tanke756.top/Article/details/gtpexfdnyw.html

[Q25] 只取前 N 条
来源：http://dali.jiagoushi.top/Article/details/gtmkilblit.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hysaishi.cn/Article/details/gtwrgjeaic.html

[Q26] 计数
来源：http://dali.yuanzhike.top/Article/details/gtqbalvqne.html

SELECT COUNT(*) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtzhyrpral.html

[Q27] 条件计数
来源：http://dali.fzhhl.top/Article/details/gtywhvpwfq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.316326.xyz/Article/details/gttetgjbez.html

[Q28] 求和与平均
来源：http://dali.wangdashe.top/Article/details/gtyqutwdyh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ivvv.top/Article/details/gtoithqtne.html

[Q29] 最大最小值
来源：http://dali.bjfxy.top/Article/details/gtwmqtqggu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtrqftbomd.html

[Q30] 分组统计
来源：http://dali.wangdashe.top/Article/details/gtleqpufqg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gtjgfbpsjf.html

[Q31] 分组后过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpathopcm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hongshengwenyu.top/Article/details/gtseiywkrp.html

[Q32] 分组拼接字符串
来源：http://dali.cashguo.top/Article/details/gtekryvtzi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtreggzwbw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.feifeiyinyue.top/Article/details/gtoapevpem.html

[Q33] 多列分组
来源：http://dali.nanxinkj.top/Article/details/gtjshemlhw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yuanzhike.top/Article/details/gtikmoldys.html

[Q34] 每组取第一条
来源：http://dali.pycfn.com/Article/details/gtzvtumlrl.html

SELECT * FROM (
来源：http://dali.cheryme.top/Article/details/gtqarppkzr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.vqdsnc.cn/Article/details/gtcwdhqtek.html

) t WHERE rn = 1;
来源：http://dali.hammf.cn/Article/details/gtzcewrbjl.html

[Q35] 内连接
来源：http://dali.jinqigufen.top/Article/details/gtxhvosbok.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgfzy.top/Article/details/gtowbglxzg.html

[Q36] 左连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuoyezuoq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.aibaodan.cn/Article/details/gtijtqomhg.html

[Q37] 右连接
来源：http://dali.316326.xyz/Article/details/gthwquzema.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtrahfcvdy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.aizwys.cn/Article/details/gtknrbcpbs.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgfzy.top/Article/details/gtcxsjbdlh.html

[Q39] 自连接（查上下级）
来源：http://dali.ydzc1.top/Article/details/gtsigrwisy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shzxlz.cn/Article/details/gtckjhpojm.html


<!-- 参考信息 -->