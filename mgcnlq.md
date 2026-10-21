代发 wailian999

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sxryk.cn/Article/details/gtvdqfdfjd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nanxinkj.top/Article/details/gtohcaowyb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gogol.net.cn/Article/details/gtgrrqjuxc.html

Ruby: a.gcd(b)
来源：http://dali.vqdsnc.cn/Article/details/gtcnedismk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gtbtxchzal.html

[N06] 判断回文字符串
来源：http://dali.jqgufenzy.top/Article/details/gtbhbdtcio.html

Py:   s == s[::-1]
来源：http://dali.daxiang520.top/Article/details/gtxfmtwfop.html

PHP:  $s === strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtlbeipawy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gturcqdrfi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrayllbu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sufxvd.cn/Article/details/gtlowejwrn.html

Go:   // 双指针从两端比较
来源：http://dali.jinqigfzy.top/Article/details/gtgvfcvxaf.html

Ruby: s == s.reverse
来源：http://dali.yangfankeji.com/Article/details/gthyviapya.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.aizwys.cn/Article/details/gtccwrhkkh.html

[N07] 两数之和（返回下标）
来源：http://dali.tian-w.cn/Article/details/gtndxxvwig.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwmwjkpnx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzjkbsdw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.redwolf501.top/Article/details/gtfnnsrtuj.html

TS:   // 手写 Map<string, number>
来源：http://dali.sweek.top/Article/details/gtfvmdkyrw.html

Java: // 手写 HashMap
来源：http://dali.sufxvd.cn/Article/details/gtvzbjhwld.html

Go:   // 手写 map[int]int
来源：http://dali.svipenyu.cn/Article/details/gtcnqnoufq.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gtypsrbyzf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gotoacloud.top/Article/details/gtjlgorkic.html

[N08] 生成全排列
来源：http://dali.yuanzhike.top/Article/details/gtweyhgbop.html

Py:   itertools.permutations(arr)
来源：http://dali.yvedp.cn/Article/details/gtzpttfhob.html

PHP:  // 手写递归交换
来源：http://dali.yongpay.top/Article/details/gttofdzdsh.html

JS:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtsibtnpev.html

TS:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gteitoqzmg.html

Java: // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtyefuzobs.html

Go:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtgzmkkztc.html

Ruby: arr.permutation.to_a
来源：http://dali.nanxinkj.top/Article/details/gtnhlzlkxf.html

C#:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtawxvooly.html

[N09] 栈与队列
来源：http://dali.smart0.xyz/Article/details/gtwsdqpkyj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtqggrynhu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.pycfn.com/Article/details/gttmlbvale.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ivvv.top/Article/details/gtzkfyheqm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.pengpengdd.cyou/Article/details/gtqmcetzbf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.birdmap.top/Article/details/gtmgilnpwa.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.dianchejie.cn/Article/details/gtsbvpbuef.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gtrouymvef.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hongshengwenyu.top/Article/details/gtmwitmdga.html

[N10] 链表节点定义
来源：http://dali.daria6918.cn/Article/details/gtpoeflldt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ydzc1.top/Article/details/gtrnwavmzq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhoulong.xyz/Article/details/gtmiayrwig.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhongyouzk.top/Article/details/gtjzpryuug.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jiagoushi.top/Article/details/gtqohetyoi.html

Java: class Node { int v; Node next; }
来源：http://dali.aizwys.cn/Article/details/gtugavyxns.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jyoumei.cn/Article/details/gtojxepcma.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.pengpengdd.cyou/Article/details/gtvuyuwfim.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zdqjudy.top/Article/details/gtxfdkirjl.html

[N11] 二叉树中序遍历
来源：http://dali.zdqjudy.top/Article/details/gtlgfbebkj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.aizwys.cn/Article/details/gtwyllimxf.html

PHP:  // 手写递归函数
来源：http://dali.jlsjyb.cn/Article/details/gtbeofzwcy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aizwys.cn/Article/details/gtmhevzmyw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gtxkigibgg.html

Java: // 手写递归
来源：http://dali.mhx1999.top/Article/details/gtkmmpdohz.html

Go:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gtlbnzjyua.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ppjwa.cn/Article/details/gtstqypnox.html

C#:   // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gtxklxpump.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yueranfly.top/Article/details/gtewpidzfx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.andypj.xyz/Article/details/gtnzzobwrc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.bjfxy.top/Article/details/gtnavixnea.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dianchejie.cn/Article/details/gtomapisjg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shangyingyoupin.top/Article/details/gthgtirbyu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hammf.cn/Article/details/gtvhvttanh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.haohaochexian.top/Article/details/gtuqychpnh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ybcxt.top/Article/details/gtqwjwkyth.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pengpengdd.cyou/Article/details/gtsrergwgn.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtjogxbwsn.html

O. 并发与异步
来源：http://dali.shanyushiyangtech.top/Article/details/gthrftmeyh.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gteawxngiz.html

[O01] 启动一个线程
来源：http://dali.daria6918.cn/Article/details/gtpgtlnmwn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjfhmmes.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.guannengcc.top/Article/details/gtnqjjsxvr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.guowangkeji.top/Article/details/gtytajsdmm.html

TS:   // 同 JS
来源：http://dali.nanxinkj.top/Article/details/gtecmhbcxx.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhiwuduotai.top/Article/details/gtxrxqricb.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gtcjsejwtp.html

Ruby: Thread.new { f }
来源：http://dali.daxiang520.top/Article/details/gtnapuxcyw.html

C#:   Task.Run(() => F());
来源：http://dali.meibo888.top/Article/details/gtpmviefcm.html

[O02] 使用线程池
来源：http://dali.tianlin.xyz/Article/details/gtmrfvbzpg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ppjwa.cn/Article/details/gtlfezaxxa.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.daxiang520.top/Article/details/gtbddkzshq.html

JS:   // worker_threads 线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdcpwsma.html

TS:   // worker_threads 线程池
来源：http://dali.jqgfzy.top/Article/details/gtcvyjblxy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xinyue.icu/Article/details/gtjzkicsoz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.aibaodan.cn/Article/details/gtxiaaolmv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gtknhosefo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinqigfzy.top/Article/details/gtdczskgwx.html

[O03] 加锁保护共享数据
来源：http://dali.nanxinkj.top/Article/details/gtycpaqmcj.html

Py:   with lock: shared += 1
来源：http://dali.jiagoushi.top/Article/details/gtlxhkmsdx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.aizwys.cn/Article/details/gtbcqidalx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.c1oappe.top/Article/details/gtmmwbcafi.html

TS:   // 同 JS
来源：http://dali.zhoulong.xyz/Article/details/gtkgpgmwmg.html

Java: synchronized (this) { shared++; }
来源：http://dali.quarkkingdee.top/Article/details/gthqeefsdo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.havefunace.top/Article/details/gtddthpiqp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gotoacloud.top/Article/details/gtmrlucswv.html

C#:   lock (gate) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gtlgwpbxjs.html

[O04] 定义异步函数并等待
来源：http://dali.fzhhl.top/Article/details/gtwpgvwztf.html

Py:   async def f():⏎    await g()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtestfusgu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shzxlz.cn/Article/details/gtpxjeujdd.html

JS:   async function f() { await g(); }
来源：http://dali.fengsongda.top/Article/details/gtojesgzsk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cashguo.top/Article/details/gtqruuvnae.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xinyue.icu/Article/details/gtqpweiqbn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cqqwz.cn/Article/details/gthizzangq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sweek.top/Article/details/gtfttisstz.html

C#:   async Task F() { await G(); }
来源：http://dali.shzxlz.cn/Article/details/gtsslbptis.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhiwuduotai.top/Article/details/gtscwxcuns.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhoulong.xyz/Article/details/gtlpeknlmw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.andypj.xyz/Article/details/gtwtkmsodr.html

JS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gtnhjwdbnq.html

TS:   await Promise.all(tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtkqnolxdl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.daxiang520.top/Article/details/gtmmjexxpw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jqgfzy.top/Article/details/gtmjejwncy.html

Ruby: threads.map(&:join)
来源：http://dali.daxiang520.top/Article/details/gtrdkylbuf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hysaishi.cn/Article/details/gtbxtvkcet.html

[O06] 使用进程池
来源：http://dali.yj20258888.top/Article/details/gtdqlkeuun.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinghuilouyu.cn/Article/details/gtnlrsghva.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cheryme.top/Article/details/gtfrbmvfvt.html

JS:   // child_process / cluster 模块
来源：http://dali.nanxinkj.top/Article/details/gteqjtkzxl.html

TS:   // child_process / cluster 模块
来源：http://dali.zhaomingkeji.xyz/Article/details/gtipfvkycf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hysaishi.cn/Article/details/gtpxqlzhvv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hywenlv.cn/Article/details/gtwwhvmzgw.html

Ruby: // fork 块
来源：http://dali.gzhubu.top/Article/details/gtmxnqxnrm.html

C#:   Parallel.For
来源：http://dali.cucudq.cn/Article/details/gtalbkadpn.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtxuitkeqk.html

P. 常用工具函数
来源：http://dali.ppjwa.cn/Article/details/gticpsuhub.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtbynjlxww.html

[P01] 生成 UUID
来源：http://dali.xuetiantiany.cn/Article/details/gtzvtppkxw.html

Py:   str(uuid.uuid4())
来源：http://dali.xinyue.icu/Article/details/gtikjjdcuf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sufxvd.cn/Article/details/gtrqnpxwvv.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gtaitkvqyi.html

TS:   crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gtqazukdev.html

Java: UUID.randomUUID().toString()
来源：http://dali.316326.xyz/Article/details/gtsaiasnjh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gtllzswtam.html

Ruby: SecureRandom.uuid
来源：http://dali.jiagoushi.top/Article/details/gteykiiekg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hywenlv.cn/Article/details/gtfbjcakqw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.fengsongda.top/Article/details/gtitifofeh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hnxiangtu.top/Article/details/gtyqokozjm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.c1oappe.top/Article/details/gtfrppwvax.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.aibaodan.cn/Article/details/gtrijuicgx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sufxvd.cn/Article/details/gthwaodzkq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jiagoushi.top/Article/details/gtxrejwyba.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.c1oappe.top/Article/details/gtjnmhtlnj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gaohongyu789.top/Article/details/gtsvxjrznq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jlsjyb.cn/Article/details/gtyinctfzv.html

[P03] 生成短随机字符串
来源：http://dali.cdnleiting.top/Article/details/gtgyfwkfxt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ydzc1.top/Article/details/gtllxquybx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xuanzx.com/Article/details/gtxontdgyd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gtdhbgumhn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhongyouzk.top/Article/details/gtsiwrrrob.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jyoumei.cn/Article/details/gtfeuzfcyr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.redwolf501.top/Article/details/gtaxqrbzcn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jyoumei.cn/Article/details/gtgbhtinsv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.9152youxi.cn/Article/details/gtwlssgxml.html

[P04] 求长度
来源：http://dali.nanxinkj.top/Article/details/gthgaflibi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.meibo888.top/Article/details/gtfpgglqzr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.meibo888.top/Article/details/gtsfgzkdfc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.vqdsnc.cn/Article/details/gtegrxibuw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ybcxt.top/Article/details/gtimocwulv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.mhx1999.top/Article/details/gtvpepiqqz.html

Go:   len(arr);  len(m)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqroqcmp.html

Ruby: x.length;  x.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtznbrepjx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sxryk.cn/Article/details/gtnncrbupe.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dianchejie.cn/Article/details/gtrejcbceu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ivvv.top/Article/details/gtiopwlnvj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nanxinkj.top/Article/details/gtxfbkqdrq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jianghu66.top/Article/details/gtmodbdzyz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgfzy.top/Article/details/gtejjhwzkm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ehwqpu.com/Article/details/gtvdoyjwze.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.svipenyu.cn/Article/details/gtxbyzeral.html

Ruby: a == b
来源：http://dali.bjfxy.top/Article/details/gtpkzmkpcz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.redwolf501.top/Article/details/gteglnoysb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.316326.xyz/Article/details/gtfkplodfb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jianghu66.top/Article/details/gterrgfhut.html

PHP:  if (empty($x)) {}
来源：http://dali.zycfv.cn/Article/details/gtxtorumhl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxilrjjc.html

TS:   if (x == null) {}
来源：http://dali.daxiang520.top/Article/details/gtblgiqdbs.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sufxvd.cn/Article/details/gtmgrycdyi.html

Go:   if x == nil {}
来源：http://dali.vqdsnc.cn/Article/details/gtigrxdydh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yvedp.cn/Article/details/gtyboazzei.html

C#:   if (x is null) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtykyclrjc.html

[P07] 防抖与节流
来源：http://dali.ybcxt.top/Article/details/gtjtlsjeun.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nanxinkj.top/Article/details/gtogvbcjbg.html

PHP:  // 手写时间戳比较
来源：http://dali.jqgfzy.top/Article/details/gthpjgoicq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cqqwz.cn/Article/details/gtbtcfqemg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gogol.net.cn/Article/details/gtwywnpvgn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shangyingyoupin.top/Article/details/gterzypluu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.wangdashe.top/Article/details/gtvqermkll.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zdqjudy.top/Article/details/gtgftstzij.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xziqi.cn/Article/details/gtruscchws.html

[P08] 处理浮点精度问题
来源：http://dali.pengpengdd.cyou/Article/details/gtiiterlqo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gzhubu.top/Article/details/gtjuvsxjgc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xziqi.cn/Article/details/gtvzzrfluy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtitumejbp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jiagoushi.top/Article/details/gtvmtaiuak.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yuanzhike.top/Article/details/gtgtbtnhza.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.guowangkeji.top/Article/details/gtqqzlcqkz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hnqzz.top/Article/details/gtfajpvpgj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shzxlz.cn/Article/details/gtmyvidkrw.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzioilfn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gaohongyu789.top/Article/details/gtyulsugku.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtkrwsltjb.html

[Q01] 创建表
来源：http://dali.sweek.top/Article/details/gtpyqgrgix.html

CREATE TABLE users (
来源：http://dali.gaohongyu789.top/Article/details/gtzcqbifti.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tianlin.xyz/Article/details/gtsvmdzgnn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.fengsongda.top/Article/details/gtyxsmbdev.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sxryk.cn/Article/details/gtzyubfmhr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinqigufen.top/Article/details/gthmjikkfh.html

);
来源：http://dali.hysaishi.cn/Article/details/gtqkldfzgj.html

[Q02] 创建带外键的表
来源：http://dali.jyoumei.cn/Article/details/gtijoqcxrk.html

CREATE TABLE orders (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsecsaaif.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aizwys.cn/Article/details/gtbqwpxsnq.html

user_id INT NOT NULL,
来源：http://dali.jianghu66.top/Article/details/gtjxeudmib.html

amount DECIMAL(10, 2),
来源：http://dali.hfpthk.cn/Article/details/gtnxuzzadf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hnxiangtu.top/Article/details/gtengbcbqn.html

);
来源：http://dali.chenlongwang.top/Article/details/gtmuwapbgw.html

[Q03] 增加列
来源：http://dali.zhengqikj.top/Article/details/gtuntzcfqg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj20258.top/Article/details/gtqkghomlu.html

[Q04] 修改列类型
来源：http://dali.yj20258888.top/Article/details/gtlpanomvv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.redwolf501.top/Article/details/gtcbcrqcpd.html

[Q05] 重命名列
来源：http://dali.meibo888.top/Article/details/gtolmoyzts.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yuanzhike.top/Article/details/gthogbqfxy.html

[Q06] 删除列
来源：http://dali.yueranfly.top/Article/details/gtxbqfvpfm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.birdmap.top/Article/details/gtdhrczufq.html

[Q07] 删除表
来源：http://dali.shangyingyoupin.top/Article/details/gtvtexyjrs.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gotoacloud.top/Article/details/gtefzearla.html

[Q08] 创建普通索引
来源：http://dali.yangfankeji.com/Article/details/gtjwqejlum.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinqigufen.top/Article/details/gtiacnbxrf.html

[Q09] 创建唯一索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtezprlcvv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.snrcjt.cn/Article/details/gtxhbcymxy.html

[Q10] 插入单行
来源：http://dali.cheryme.top/Article/details/gtkejlyhty.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gtcxgcnhgd.html

[Q11] 一次插入多行
来源：http://dali.xuanzx.com/Article/details/gtatawlxek.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sxryk.cn/Article/details/gtlefvgphw.html

[Q12] 插入后取自增 ID
来源：http://dali.redwolf501.top/Article/details/gtwktosqwx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hnqzz.top/Article/details/gtzqtgckcn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.feifeiyinyue.top/Article/details/gtjjptcaln.html

[Q13] 忽略重复插入
来源：http://dali.shzxlz.cn/Article/details/gtitqfwtsh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dianchejie.cn/Article/details/gtoaefyczp.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhoulong.xyz/Article/details/gtpsitxvok.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.fengsongda.top/Article/details/gtpugpbney.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.bjfxy.top/Article/details/gtnzopyyrn.html

[Q15] 查询全部
来源：http://dali.jinghuilouyu.cn/Article/details/gtymgjvlgw.html

SELECT * FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtaqjofwon.html

[Q16] 查询指定列
来源：http://dali.cheryme.top/Article/details/gtqljodthv.html

SELECT id, name FROM users;
来源：http://dali.yvedp.cn/Article/details/gtmbnkepct.html

[Q17] 条件查询
来源：http://dali.feifeiyinyue.top/Article/details/gtfsnmnbwp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jyoumei.cn/Article/details/gttblczinc.html

[Q18] 模糊匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtxmqssfse.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.tian-w.cn/Article/details/gtfepjgont.html

[Q19] 范围查询
来源：http://dali.pengpengdd.cyou/Article/details/gtcnqjahtm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.316326.xyz/Article/details/gtjborfpic.html

[Q20] IN 列表
来源：http://dali.daria6918.cn/Article/details/gtsdpfjxkb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xinyue.icu/Article/details/gtynomewfl.html

[Q21] 空值判断
来源：http://dali.nwbrower.top/Article/details/gtlzfxcwoo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.smart0.xyz/Article/details/gtwpvfoior.html

[Q22] 排序
来源：http://dali.sufxvd.cn/Article/details/gtwejfhhrq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.dianchejie.cn/Article/details/gtkqldvuvp.html

[Q23] 分页
来源：http://dali.sweek.top/Article/details/gtzpvhdylg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj20258.top/Article/details/gtgfnwtkrf.html

[Q24] 去重
来源：http://dali.snrcjt.cn/Article/details/gtevrsjddz.html

SELECT DISTINCT city FROM users;
来源：http://dali.jianghu66.top/Article/details/gtnmucrwss.html

[Q25] 只取前 N 条
来源：http://dali.yonumen.top/Article/details/gtfhvyimzh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yj20258.top/Article/details/gtligakvuf.html

[Q26] 计数
来源：http://dali.nanxinkj.top/Article/details/gturtpxlev.html

SELECT COUNT(*) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtklvtenau.html

[Q27] 条件计数
来源：http://dali.iojbl.cn/Article/details/gtggmmovba.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.iojbl.cn/Article/details/gtcjlgprpx.html

[Q28] 求和与平均
来源：http://dali.aibaodan.cn/Article/details/gtoafsdlud.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtjfrsktcn.html

[Q29] 最大最小值
来源：http://dali.shanyushiyangtech.top/Article/details/gtznycsafq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtnusbrnaj.html

[Q30] 分组统计
来源：http://dali.jinqigufen.top/Article/details/gtpgtsiemn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.iojbl.cn/Article/details/gtnocbfpgj.html

[Q31] 分组后过滤
来源：http://dali.yuanzhike.top/Article/details/gtlprngefy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cucudq.cn/Article/details/gtfyxisdxu.html

[Q32] 分组拼接字符串
来源：http://dali.smart0.xyz/Article/details/gtyosvkhqp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gtjdxsuosi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmxaaxmcz.html

[Q33] 多列分组
来源：http://dali.nanxuanxn.top/Article/details/gtsbssetnl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ivvv.top/Article/details/gtppvadcdf.html

[Q34] 每组取第一条
来源：http://dali.yonumen.top/Article/details/gtlfdcrnxu.html

SELECT * FROM (
来源：http://dali.zycfv.cn/Article/details/gtjhlqbbql.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.iojbl.cn/Article/details/gtepznbxeo.html

) t WHERE rn = 1;
来源：http://dali.yj20258.top/Article/details/gtpodbbgta.html

[Q35] 内连接
来源：http://dali.pycfn.com/Article/details/gtbhmwluff.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.haohaochexian.top/Article/details/gtptgtajjj.html

[Q36] 左连接
来源：http://dali.nwbrower.top/Article/details/gtogdurlwc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ybcxt.top/Article/details/gttbssnfqc.html

[Q37] 右连接
来源：http://dali.cucudq.cn/Article/details/gttevxxmtp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.chenjidiqi.icu/Article/details/gtctkpvnpt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.daxiang520.top/Article/details/gtwrmwismc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tian-w.cn/Article/details/gtdhqxaufh.html

[Q39] 自连接（查上下级）
来源：http://dali.nwbrower.top/Article/details/gtnmrytdvj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.dianchejie.cn/Article/details/gtnjprrfsk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jqgfzy.top/Article/details/gtbzuuefhp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.feifeiyinyue.top/Article/details/gtfvmjdixk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yuanzhike.top/Article/details/gthytixkso.html

[Q41] 多表连接
来源：http://dali.pycfn.com/Article/details/gtgjxhbgco.html


<!-- 参考信息 -->