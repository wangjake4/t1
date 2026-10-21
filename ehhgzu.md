代发 wailian999

Ruby: s == s.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsmufbtvx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.daxiang520.top/Article/details/gtczpbkzas.html

[N07] 两数之和（返回下标）
来源：http://dali.cashguo.top/Article/details/gtnowtxizk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhixingplan.top/Article/details/gtaalrvfzv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zdqjudy.top/Article/details/gtcdbeyscj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shanyushiyangtech.top/Article/details/gteywlthbj.html

TS:   // 手写 Map<string, number>
来源：http://dali.zycfv.cn/Article/details/gtsczzqqdt.html

Java: // 手写 HashMap
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsbkawwii.html

Go:   // 手写 map[int]int
来源：http://dali.jyoumei.cn/Article/details/gtunrcntsc.html

Ruby: // 手写 Hash
来源：http://dali.jinyuanbaomall.cn/Article/details/gthkbwgaiy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.aizwys.cn/Article/details/gtfinqdnbc.html

[N08] 生成全排列
来源：http://dali.shanyushiyangtech.top/Article/details/gtgawbromh.html

Py:   itertools.permutations(arr)
来源：http://dali.mhx1999.top/Article/details/gtbsidwxmd.html

PHP:  // 手写递归交换
来源：http://dali.snrcjt.cn/Article/details/gtzvsedtoj.html

JS:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtztbjvagj.html

TS:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtgmcywfas.html

Java: // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtzsbfmhpr.html

Go:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtmqxexuwj.html

Ruby: arr.permutation.to_a
来源：http://dali.jiagoushi.top/Article/details/gtjvahugcv.html

C#:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbbfkrpp.html

[N09] 栈与队列
来源：http://dali.andypj.xyz/Article/details/gtlafuisjj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shuidangran.top/Article/details/gtmxouzftl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gtdsbwihmu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gtftdntnak.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xuetiantiany.cn/Article/details/gtnsekgiwy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jiagoushi.top/Article/details/gtaweimxjy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nwbrower.top/Article/details/gtohrdgxnb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gtgwyswnqx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shangyingyoupin.top/Article/details/gtaxjzlqsf.html

[N10] 链表节点定义
来源：http://dali.sysykeji.top/Article/details/gtcrypvogg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.dashuyun.cn/Article/details/gteqzgtuko.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.havefunace.top/Article/details/gtzwcybrcn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shuidangran.top/Article/details/gtnolagupa.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.haohaochexian.top/Article/details/gtbtzdniks.html

Java: class Node { int v; Node next; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewfhnywt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.redwolf501.top/Article/details/gtaucmpeyd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tanke756.top/Article/details/gtgqgjzmkb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jiagoushi.top/Article/details/gtuyywvjps.html

[N11] 二叉树中序遍历
来源：http://dali.yuanzhike.top/Article/details/gtuabnyabw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenjidiqi.icu/Article/details/gtyteggbol.html

PHP:  // 手写递归函数
来源：http://dali.quarkkingdee.top/Article/details/gtzqrntfpw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jianghu66.top/Article/details/gtmqixbtsn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tianlin.xyz/Article/details/gtftmsrgba.html

Java: // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gtlgbizpzn.html

Go:   // 手写递归
来源：http://dali.daxiang520.top/Article/details/gtnntijvcp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.iojbl.cn/Article/details/gtlomsocir.html

C#:   // 手写递归
来源：http://dali.ybcxt.top/Article/details/gtenxisklj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xziqi.cn/Article/details/gtrnhosrba.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinghuilouyu.cn/Article/details/gttgpihkqp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenlongwang.top/Article/details/gtwshxatxb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.haohaochexian.top/Article/details/gtucnbjxpw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guowangkeji.top/Article/details/gtfhnshmrt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangdashe.top/Article/details/gtggedwiua.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.haohaochexian.top/Article/details/gtuhmdnsdu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nanxinkj.top/Article/details/gthcfwvttm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.c1oappe.top/Article/details/gtowhlfjoe.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtmocejpyi.html

O. 并发与异步
来源：http://dali.fengsongda.top/Article/details/gtobtdeqjv.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtdkaayfkr.html

[O01] 启动一个线程
来源：http://dali.hywenlv.cn/Article/details/gtlawlcgah.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cheryme.top/Article/details/gtzcjqcmja.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hywenlv.cn/Article/details/gtcazmjuus.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gogol.net.cn/Article/details/gtsetckaft.html

TS:   // 同 JS
来源：http://dali.tanke756.top/Article/details/gtphctudvk.html

Java: new Thread(() -> f()).start()
来源：http://dali.yonumen.top/Article/details/gtmxvxhndq.html

Go:   go f()
来源：http://dali.shuidangran.top/Article/details/gtnfonlkvq.html

Ruby: Thread.new { f }
来源：http://dali.sufxvd.cn/Article/details/gtmxyhnzff.html

C#:   Task.Run(() => F());
来源：http://dali.cqqwz.cn/Article/details/gtlzdqelhy.html

[O02] 使用线程池
来源：http://dali.wangshuangyany.cn/Article/details/gtfblfqcvw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.dashuyun.cn/Article/details/gtcdenukfm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangshuangyany.cn/Article/details/gtgnkagevb.html

JS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gthfitwiwj.html

TS:   // worker_threads 线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gtnlyogqgn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gtpfehacnn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.feifeiyinyue.top/Article/details/gtmfnzhvdg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenjidiqi.icu/Article/details/gtjirkazgl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zycfv.cn/Article/details/gthwsyagvb.html

[O03] 加锁保护共享数据
来源：http://dali.cqqwz.cn/Article/details/gtpsffbsyn.html

Py:   with lock: shared += 1
来源：http://dali.shuidangran.top/Article/details/gtlumcnkmh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hfpthk.cn/Article/details/gtbzavemoy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hnqzz.top/Article/details/gtagloobfh.html

TS:   // 同 JS
来源：http://dali.jlsjyb.cn/Article/details/gtwbhlwolc.html

Java: synchronized (this) { shared++; }
来源：http://dali.cqqwz.cn/Article/details/gtascdffvm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.svipenyu.cn/Article/details/gtnvxstzul.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhoulong.xyz/Article/details/gtqhoevbki.html

C#:   lock (gate) { shared++; }
来源：http://dali.andypj.xyz/Article/details/gtizhbcnoz.html

[O04] 定义异步函数并等待
来源：http://dali.cheryme.top/Article/details/gtjhyzyxdk.html

Py:   async def f():⏎    await g()
来源：http://dali.yonumen.top/Article/details/gtpbimnkrc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhoulong.xyz/Article/details/gtocstgbtd.html

JS:   async function f() { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gtiiwutyte.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhixingplan.top/Article/details/gtdmhqtfov.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ybcxt.top/Article/details/gtkizogefe.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ivvv.top/Article/details/gtjbipbuhb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnzvfffy.html

C#:   async Task F() { await G(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwoeyoksc.html

[O05] 并发执行并等待全部完成
来源：http://dali.tanke756.top/Article/details/gtmodepnmp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sysykeji.top/Article/details/gtdlhjfmxe.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yj20258.top/Article/details/gtxxmdgjeo.html

JS:   await Promise.all(tasks)
来源：http://dali.jinqigufen.top/Article/details/gtagzvmpyu.html

TS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gtiavfwszb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.bjfxy.top/Article/details/gtgbbjfbnp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yanxiufei.cn/Article/details/gtwxhmuqzt.html

Ruby: threads.map(&:join)
来源：http://dali.haohaochexian.top/Article/details/gtyezkgurq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cheryme.top/Article/details/gtguvxkakm.html

[O06] 使用进程池
来源：http://dali.svipenyu.cn/Article/details/gtfywnaqpw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenzaomai.com/Article/details/gtfwxfphlz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yangfankeji.com/Article/details/gtmucymaxc.html

JS:   // child_process / cluster 模块
来源：http://dali.quarkkingdee.top/Article/details/gtooaayttw.html

TS:   // child_process / cluster 模块
来源：http://dali.gogol.net.cn/Article/details/gtenyamdrh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.birdmap.top/Article/details/gtrislqskl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.aizwys.cn/Article/details/gtivxxpaea.html

Ruby: // fork 块
来源：http://dali.cashguo.top/Article/details/gtubxqtjpw.html

C#:   Parallel.For
来源：http://dali.tanke756.top/Article/details/gtqzclethl.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtauirgdpn.html

P. 常用工具函数
来源：http://dali.gaohongyu789.top/Article/details/gtcrhhjiqw.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtblvnxrqc.html

[P01] 生成 UUID
来源：http://dali.yj20258.top/Article/details/gtiydbkner.html

Py:   str(uuid.uuid4())
来源：http://dali.hammf.cn/Article/details/gtzwzhchat.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hywenlv.cn/Article/details/gtwtqajauy.html

JS:   crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfmwfccdb.html

TS:   crypto.randomUUID()
来源：http://dali.pycfn.com/Article/details/gtjygbqiva.html

Java: UUID.randomUUID().toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtrfitdmee.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xuanzx.com/Article/details/gtpiziddeg.html

Ruby: SecureRandom.uuid
来源：http://dali.cqqwz.cn/Article/details/gtxishclgp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxwdtrgo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj202588.top/Article/details/gtxblufvod.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hnqzz.top/Article/details/gtuzhjnkke.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nanxuanxn.top/Article/details/gtapcvvrxv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hongshengwenyu.top/Article/details/gtumyumejq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.haohaochexian.top/Article/details/gtieprajer.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yangfankeji.com/Article/details/gthlokjiuh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sysykeji.top/Article/details/gtsdbhwapy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.haohaochexian.top/Article/details/gttcxxmmlz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ehwqpu.com/Article/details/gtpkphulxe.html

[P03] 生成短随机字符串
来源：http://dali.wangdashe.top/Article/details/gtkxlirdbl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cheryme.top/Article/details/gteojuojox.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.dianchejie.cn/Article/details/gtrbjrzgxh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dianchejie.cn/Article/details/gtxzhulfmh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.smart0.xyz/Article/details/gtnxplbmsv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nanxinkj.top/Article/details/gtmuonseph.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gzhubu.top/Article/details/gtpaqgozya.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.bjfxy.top/Article/details/gtbarqkcts.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xuanzx.com/Article/details/gttzxhafnd.html

[P04] 求长度
来源：http://dali.wangshuangyany.cn/Article/details/gtaiboldkg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.iojbl.cn/Article/details/gtfopzcwbn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gtfkqqsbdr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yanxiufei.cn/Article/details/gtkgdryppd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtawfrgjam.html

Java: list.size();  map.size();  s.length()
来源：http://dali.redwolf501.top/Article/details/gtocnsjpqi.html

Go:   len(arr);  len(m)
来源：http://dali.dianchejie.cn/Article/details/gthyzzofqd.html

Ruby: x.length;  x.size
来源：http://dali.aizwys.cn/Article/details/gtqahjrrra.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yongpay.top/Article/details/gtqfvdkqln.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sweek.top/Article/details/gteqyicvfz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shuidangran.top/Article/details/gtexlnohnf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sweek.top/Article/details/gtohpyvfqp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.wangshuangyany.cn/Article/details/gtdhfctely.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yueranfly.top/Article/details/gtdeagjeqx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hammf.cn/Article/details/gtlnaphnhk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gogol.net.cn/Article/details/gtlhbuxslo.html

Ruby: a == b
来源：http://dali.wangdashe.top/Article/details/gtdzncjlbi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shzxlz.cn/Article/details/gtvjauphej.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclnmqkjn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinqigfzy.top/Article/details/gtfnmsakfk.html

PHP:  if (empty($x)) {}
来源：http://dali.jinqigufen.top/Article/details/gtmdxsfaiq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nwbrower.top/Article/details/gtdpprgnyw.html

TS:   if (x == null) {}
来源：http://dali.xziqi.cn/Article/details/gtihmhztcu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.vqdsnc.cn/Article/details/gtsdaooiya.html

Go:   if x == nil {}
来源：http://dali.dashuyun.cn/Article/details/gttbndzoux.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hywenlv.cn/Article/details/gtetqcrzce.html

C#:   if (x is null) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtthaewnlp.html

[P07] 防抖与节流
来源：http://dali.zhoulong.xyz/Article/details/gtemjawtht.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sxryk.cn/Article/details/gthpesryca.html

PHP:  // 手写时间戳比较
来源：http://dali.hywenlv.cn/Article/details/gtlbbgipog.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gtyrypadrm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzkhwadde.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.meibo888.top/Article/details/gtrxqtaxoa.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.mhx1999.top/Article/details/gtvbzhpowf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhoulong.xyz/Article/details/gthmcanqsf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yuanzhike.top/Article/details/gtwlkjydhj.html

[P08] 处理浮点精度问题
来源：http://dali.ivvv.top/Article/details/gtrfrgedrw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.guowangkeji.top/Article/details/gtpyvblpgf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hfpthk.cn/Article/details/gtgryucnzx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.pengpengdd.cyou/Article/details/gthspnqwhp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.dashuyun.cn/Article/details/gtcqxyxrpt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.meibo888.top/Article/details/gtlbhwyrcj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.mhx1999.top/Article/details/gtcmnkzdpf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hnxiangtu.top/Article/details/gtuwcbgbim.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.fengsongda.top/Article/details/gtixaewiff.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gttgbnheak.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cqqwz.cn/Article/details/gthquwrkcn.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtqnqdgbil.html

[Q01] 创建表
来源：http://dali.shanyushiyangtech.top/Article/details/gtnnxcyrsm.html

CREATE TABLE users (
来源：http://dali.zycfv.cn/Article/details/gtgriyenuk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhvysixf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.pycfn.com/Article/details/gtlkulrspu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.aizwys.cn/Article/details/gtvryzzyyc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinqigufen.top/Article/details/gtxwgatsdn.html

);
来源：http://dali.yj202588.top/Article/details/gthyvjgvsb.html

[Q02] 创建带外键的表
来源：http://dali.xuetiantiany.cn/Article/details/gtvgkbiolf.html

CREATE TABLE orders (
来源：http://dali.xylfe.cn/Article/details/gtzdnnhgfq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenzaomai.com/Article/details/gtigvgvebs.html

user_id INT NOT NULL,
来源：http://dali.xuanzx.com/Article/details/gtctojumng.html

amount DECIMAL(10, 2),
来源：http://dali.nwbrower.top/Article/details/gtbswdspdn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yueranfly.top/Article/details/gtgdihcnqa.html

);
来源：http://dali.birdmap.top/Article/details/gthpgycgnt.html

[Q03] 增加列
来源：http://dali.nwbrower.top/Article/details/gtanvlmegm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cdnleiting.top/Article/details/gttezhmxsv.html

[Q04] 修改列类型
来源：http://dali.zhiwuduotai.top/Article/details/gtfnxmxupt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xylfe.cn/Article/details/gtpvwqmhot.html

[Q05] 重命名列
来源：http://dali.chenlongwang.top/Article/details/gtlqdshkrr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.fzhhl.top/Article/details/gtcfivsejf.html

[Q06] 删除列
来源：http://dali.haohaochexian.top/Article/details/gtlcrawmow.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xuanzx.com/Article/details/gtbpvbvzsj.html

[Q07] 删除表
来源：http://dali.daria6918.cn/Article/details/gtksefrfpq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj20258.top/Article/details/gtexiifiel.html

[Q08] 创建普通索引
来源：http://dali.daria6918.cn/Article/details/gthzxvbetf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.birdmap.top/Article/details/gtsaxdajsj.html

[Q09] 创建唯一索引
来源：http://dali.vqdsnc.cn/Article/details/gtkwylpomo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xuetiantiany.cn/Article/details/gtyoidcnwg.html

[Q10] 插入单行
来源：http://dali.guowangkeji.top/Article/details/gticwjdofy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tianlin.xyz/Article/details/gtjyzyyizx.html

[Q11] 一次插入多行
来源：http://dali.guowangkeji.top/Article/details/gtlqhjjgxu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xylfe.cn/Article/details/gteqwbjjsz.html

[Q12] 插入后取自增 ID
来源：http://dali.shzxlz.cn/Article/details/gtefdnmxko.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.316326.xyz/Article/details/gtfcpmkadx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhoulong.xyz/Article/details/gtjysihxap.html

[Q13] 忽略重复插入
来源：http://dali.316326.xyz/Article/details/gtjugsfykg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yueranfly.top/Article/details/gtpzckeehv.html

[Q14] 存在则更新（upsert）
来源：http://dali.dashuyun.cn/Article/details/gtixkjoxdw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.svipenyu.cn/Article/details/gtdzpfaimg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhengqikj.top/Article/details/gtepyxvjea.html

[Q15] 查询全部
来源：http://dali.0kj1m.cn/Article/details/gtpsczodae.html

SELECT * FROM users;
来源：http://dali.xuanzx.com/Article/details/gtvhncspmw.html

[Q16] 查询指定列
来源：http://dali.tianlin.xyz/Article/details/gtftnjrdes.html

SELECT id, name FROM users;
来源：http://dali.xinyue.icu/Article/details/gtjsudigyk.html

[Q17] 条件查询
来源：http://dali.jqgfzy.top/Article/details/gtrzymatfy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtfhaoabbm.html

[Q18] 模糊匹配
来源：http://dali.jlsjyb.cn/Article/details/gtgvvafobj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.birdmap.top/Article/details/gtilnncipi.html

[Q19] 范围查询
来源：http://dali.guannengcc.top/Article/details/gthbtlhodm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tian-w.cn/Article/details/gtjugznqru.html

[Q20] IN 列表
来源：http://dali.hnxiangtu.top/Article/details/gtvvyugiga.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.haohaochexian.top/Article/details/gtssffkmwf.html

[Q21] 空值判断
来源：http://dali.fengsongda.top/Article/details/gtlkittywz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.dashuyun.cn/Article/details/gtowitvoji.html

[Q22] 排序
来源：http://dali.yvedp.cn/Article/details/gtqjjdihfx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yuanzhike.top/Article/details/gttushfuho.html

[Q23] 分页
来源：http://dali.yanxiufei.cn/Article/details/gtnvlvwisy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.pengpengdd.cyou/Article/details/gtwrvyqsmd.html

[Q24] 去重
来源：http://dali.andypj.xyz/Article/details/gtfxxjwnej.html

SELECT DISTINCT city FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtrmjyljol.html

[Q25] 只取前 N 条
来源：http://dali.bjfxy.top/Article/details/gtdzqbityh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gaohongyu789.top/Article/details/gteopwhdji.html

[Q26] 计数
来源：http://dali.jianghu66.top/Article/details/gtnrjmbljl.html

SELECT COUNT(*) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtdxdziyxo.html

[Q27] 条件计数
来源：http://dali.yongpay.top/Article/details/gtufsrhvsl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ydzc1.top/Article/details/gtddvaubsb.html

[Q28] 求和与平均
来源：http://dali.gotoacloud.top/Article/details/gtzxxtfwfq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtjxklttro.html

[Q29] 最大最小值
来源：http://dali.sxryk.cn/Article/details/gtneaoortu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtjzgoscel.html

[Q30] 分组统计
来源：http://dali.yuxming.cn/Article/details/gtyhsnihwm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gthlaknzvn.html

[Q31] 分组后过滤
来源：http://dali.havefunace.top/Article/details/gtngarxlmb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.guannengcc.top/Article/details/gtjpavlkqb.html

[Q32] 分组拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtyracljod.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gtgcpnspgx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.smart0.xyz/Article/details/gtrgejegsd.html

[Q33] 多列分组
来源：http://dali.ehwqpu.com/Article/details/gtcurtohlu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.redwolf501.top/Article/details/gtrtncgzds.html

[Q34] 每组取第一条
来源：http://dali.zhiwuduotai.top/Article/details/gtkacawudo.html

SELECT * FROM (
来源：http://dali.hnxiangtu.top/Article/details/gtizmtiekh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.snrcjt.cn/Article/details/gtupmzvuhp.html

) t WHERE rn = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gteuwhvmsl.html

[Q35] 内连接
来源：http://dali.birdmap.top/Article/details/gthqmrnpsp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gaohongyu789.top/Article/details/gtzidgeksn.html

[Q36] 左连接
来源：http://dali.zycfv.cn/Article/details/gtxquagxrt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cashguo.top/Article/details/gtfnukcwhu.html

[Q37] 右连接
来源：http://dali.quarkkingdee.top/Article/details/gtlhyiognh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.meibo888.top/Article/details/gtkuejkpcj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nwbrower.top/Article/details/gtmdwzejik.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sysykeji.top/Article/details/gthrzvzhix.html

[Q39] 自连接（查上下级）
来源：http://dali.svipenyu.cn/Article/details/gtzrbubkbm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnxiangtu.top/Article/details/gtdfyvlzje.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.aibaodan.cn/Article/details/gtlghpditk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yj20258.top/Article/details/gtkfbgxygu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shangyingyoupin.top/Article/details/gtkceoyiqe.html

[Q41] 多表连接
来源：http://dali.dianchejie.cn/Article/details/gtgvbozpbf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gtzrytzoax.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yueranfly.top/Article/details/gtenjjsuiq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.havefunace.top/Article/details/gttgdmtvcc.html

[Q42] 连接条件附加过滤
来源：http://dali.cqqwz.cn/Article/details/gtrszbbkdz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sweek.top/Article/details/gtqylbelaz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xuetiantiany.cn/Article/details/gtvmofwxum.html

[Q43] 标量子查询
来源：http://dali.tianlin.xyz/Article/details/gtmjoyarxu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cdnleiting.top/Article/details/gtpydecbvs.html

[Q44] IN 子查询
来源：http://dali.xuanzx.com/Article/details/gtfstjrown.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.aizwys.cn/Article/details/gttsggdnhb.html

[Q45] EXISTS 判断存在
来源：http://dali.bjfxy.top/Article/details/gtpoiqpiyz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.meibo888.top/Article/details/gtkvrgxixa.html


<!-- 参考信息 -->