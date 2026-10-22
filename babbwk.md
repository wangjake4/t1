代发 wailian999

[N05] 最大公约数
来源：http://dali.snrcjt.cn/Article/details/gtyupztzhc.html

Py:   math.gcd(a, b)
来源：http://dali.birdmap.top/Article/details/gtlxgpspcq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxjiliege.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gtisjulvpw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.havefunace.top/Article/details/gtqcakyqjf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoxvxdjwa.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnxiangtu.top/Article/details/gtbtwagykl.html

Ruby: a.gcd(b)
来源：http://dali.hnxiangtu.top/Article/details/gtdggjrrvd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guannengcc.top/Article/details/gtjdsgeirs.html

[N06] 判断回文字符串
来源：http://dali.redwolf501.top/Article/details/gtmlsvibla.html

Py:   s == s[::-1]
来源：http://dali.hywenlv.cn/Article/details/gtqclragmo.html

PHP:  $s === strrev($s);
来源：http://dali.cheryme.top/Article/details/gtzinugvll.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gtixvvmlxo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gtdgundblp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shuidangran.top/Article/details/gtzjyiehpy.html

Go:   // 双指针从两端比较
来源：http://dali.yanxiufei.cn/Article/details/gtrhinnkhh.html

Ruby: s == s.reverse
来源：http://dali.svipenyu.cn/Article/details/gtqunclcrj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gtbbgstkre.html

[N07] 两数之和（返回下标）
来源：http://dali.ehwqpu.com/Article/details/gtbjjddyyu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jyoumei.cn/Article/details/gtsftmgegy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinqigufen.top/Article/details/gtgpzqrzfd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sufxvd.cn/Article/details/gtcfkofcbk.html

TS:   // 手写 Map<string, number>
来源：http://dali.tian-w.cn/Article/details/gtoythkgmn.html

Java: // 手写 HashMap
来源：http://dali.sxryk.cn/Article/details/gtmjnhmwyf.html

Go:   // 手写 map[int]int
来源：http://dali.meibo888.top/Article/details/gtnnxdxnkc.html

Ruby: // 手写 Hash
来源：http://dali.hfpthk.cn/Article/details/gtdotuotnf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdvxnmqf.html

[N08] 生成全排列
来源：http://dali.yj202588.top/Article/details/gtttiiplhz.html

Py:   itertools.permutations(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtsybbxdfo.html

PHP:  // 手写递归交换
来源：http://dali.zhixingplan.top/Article/details/gtsyxpezvf.html

JS:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtulicedst.html

TS:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtzelfrhli.html

Java: // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtvmmrsbgg.html

Go:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtaqnytjww.html

Ruby: arr.permutation.to_a
来源：http://dali.hysaishi.cn/Article/details/gtantbgkdu.html

C#:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtmqowplbr.html

[N09] 栈与队列
来源：http://dali.cheryme.top/Article/details/gtmdqzkslk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jianghu66.top/Article/details/gtxlcfwxbk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gtjecqbuvl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gtatnckzzx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zycfv.cn/Article/details/gtfejwvcwc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ybcxt.top/Article/details/gtvjoobojw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cdnleiting.top/Article/details/gtzcwpwyti.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hammf.cn/Article/details/gtfmdduwyb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.316326.xyz/Article/details/gtkxtvkywf.html

[N10] 链表节点定义
来源：http://dali.hywenlv.cn/Article/details/gtjptjljqh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yuanzhike.top/Article/details/gtctnqetvd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.redwolf501.top/Article/details/gtmkypdjxr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ehwqpu.com/Article/details/gtzzzxbjja.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gzhubu.top/Article/details/gtzygobyoy.html

Java: class Node { int v; Node next; }
来源：http://dali.mhx1999.top/Article/details/gtzvkbdymu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.aizwys.cn/Article/details/gtjdudgdqc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuxming.cn/Article/details/gttdohtnuv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhixingplan.top/Article/details/gttssfefnb.html

[N11] 二叉树中序遍历
来源：http://dali.smart0.xyz/Article/details/gtfuulysai.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj202588.top/Article/details/gtgchvdumx.html

PHP:  // 手写递归函数
来源：http://dali.hongshengwenyu.top/Article/details/gtoaydbrxf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shzxlz.cn/Article/details/gtohwerdov.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sysykeji.top/Article/details/gtbgnupnrp.html

Java: // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gtlnplbkwu.html

Go:   // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gtxawkzccr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpixsjmws.html

C#:   // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gtlxxjjwdi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.bjfxy.top/Article/details/gtgtppipwp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hnxiangtu.top/Article/details/gtrsxiftdw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gaohongyu789.top/Article/details/gtgneelbfj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shuidangran.top/Article/details/gtgndsndlq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.bjfxy.top/Article/details/gtqhksscse.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangdashe.top/Article/details/gtjwirqcen.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sxryk.cn/Article/details/gtpirgfbad.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.iojbl.cn/Article/details/gtuucaubdi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cucudq.cn/Article/details/gtufybeopv.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtfxgutpsz.html

O. 并发与异步
来源：http://dali.hywenlv.cn/Article/details/gtaemyxied.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtnnyvrvkr.html

[O01] 启动一个线程
来源：http://dali.cheryme.top/Article/details/gtbaohhdal.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhoulong.xyz/Article/details/gtmyyxrdgi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tanke756.top/Article/details/gtjfuopwlv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.wangshuangyany.cn/Article/details/gtzjajmohn.html

TS:   // 同 JS
来源：http://dali.yj20258.top/Article/details/gtjqfihsbb.html

Java: new Thread(() -> f()).start()
来源：http://dali.ppjwa.cn/Article/details/gtahjktcqj.html

Go:   go f()
来源：http://dali.zhiwuduotai.top/Article/details/gtwqjlcsdo.html

Ruby: Thread.new { f }
来源：http://dali.smart0.xyz/Article/details/gtkirhwrxm.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258888.top/Article/details/gtowzzeqgk.html

[O02] 使用线程池
来源：http://dali.wangdashe.top/Article/details/gtvoxbwzym.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.mhx1999.top/Article/details/gtnpeehpks.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shuidangran.top/Article/details/gttctwollo.html

JS:   // worker_threads 线程池
来源：http://dali.zhengqikj.top/Article/details/gtsartwzxr.html

TS:   // worker_threads 线程池
来源：http://dali.quarkkingdee.top/Article/details/gtepszgxzw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shuidangran.top/Article/details/gtihhfbyaf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yvedp.cn/Article/details/gtkxhzfyxp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.pycfn.com/Article/details/gtytsovxad.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.meibo888.top/Article/details/gtvfsoezxi.html

[O03] 加锁保护共享数据
来源：http://dali.birdmap.top/Article/details/gtpckompib.html

Py:   with lock: shared += 1
来源：http://dali.jiagoushi.top/Article/details/gturhutohn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jianghu66.top/Article/details/gtonaawuiw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jyoumei.cn/Article/details/gtucarnodg.html

TS:   // 同 JS
来源：http://dali.zhoulong.xyz/Article/details/gtnvzscomt.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhoulong.xyz/Article/details/gtricbvaqi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yonumen.top/Article/details/gtamsfagib.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj202588.top/Article/details/gtuxrnqeub.html

C#:   lock (gate) { shared++; }
来源：http://dali.yangfankeji.com/Article/details/gtahszevut.html

[O04] 定义异步函数并等待
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbcftxfi.html

Py:   async def f():⏎    await g()
来源：http://dali.zdqjudy.top/Article/details/gtkekzhxsm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.quarkkingdee.top/Article/details/gtwysfqmaa.html

JS:   async function f() { await g(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtschlpssh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyorwcdwr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dianchejie.cn/Article/details/gtgwvhbxgi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hysaishi.cn/Article/details/gteqwwjmse.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.daria6918.cn/Article/details/gtlbbvtcce.html

C#:   async Task F() { await G(); }
来源：http://dali.wangshuangyany.cn/Article/details/gthmanzidx.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinghuilouyu.cn/Article/details/gtxrggvluh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sxryk.cn/Article/details/gtctfuplas.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.smart0.xyz/Article/details/gtnuujknbc.html

JS:   await Promise.all(tasks)
来源：http://dali.nwbrower.top/Article/details/gtykipdjgd.html

TS:   await Promise.all(tasks)
来源：http://dali.cdnleiting.top/Article/details/gtbodwnevv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.dianchejie.cn/Article/details/gtamkvhaze.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cucudq.cn/Article/details/gtrqpgjxqv.html

Ruby: threads.map(&:join)
来源：http://dali.zhengqikj.top/Article/details/gtxbzewyvn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yvedp.cn/Article/details/gtnntfdcuq.html

[O06] 使用进程池
来源：http://dali.yongpay.top/Article/details/gtwhpqvvoi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nanxuanxn.top/Article/details/gtuvxpqwmj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.0kj1m.cn/Article/details/gtgvcmfect.html

JS:   // child_process / cluster 模块
来源：http://dali.gogol.net.cn/Article/details/gtdukqjcuh.html

TS:   // child_process / cluster 模块
来源：http://dali.hysaishi.cn/Article/details/gtaakciqfu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sweek.top/Article/details/gtwuxsfcsr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hammf.cn/Article/details/gtqbbvavze.html

Ruby: // fork 块
来源：http://dali.zhixingplan.top/Article/details/gtiwihkkpk.html

C#:   Parallel.For
来源：http://dali.chenlongwang.top/Article/details/gtuugczjbh.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtsfoetalm.html

P. 常用工具函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkoohhavw.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpnkjeoyw.html

[P01] 生成 UUID
来源：http://dali.sufxvd.cn/Article/details/gterzonwjd.html

Py:   str(uuid.uuid4())
来源：http://dali.yueranfly.top/Article/details/gttfaocxpn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tanke756.top/Article/details/gtvnqvrhkz.html

JS:   crypto.randomUUID()
来源：http://dali.haohaochexian.top/Article/details/gtlsltwfzo.html

TS:   crypto.randomUUID()
来源：http://dali.ehwqpu.com/Article/details/gtmheplyoh.html

Java: UUID.randomUUID().toString()
来源：http://dali.316326.xyz/Article/details/gtyoqtoffr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj202588.top/Article/details/gtjargdeob.html

Ruby: SecureRandom.uuid
来源：http://dali.fzhhl.top/Article/details/gtjnskdhru.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hammf.cn/Article/details/gtwyxzfbct.html

[P02] MD5 / SHA256 摘要
来源：http://dali.guannengcc.top/Article/details/gtfajvfulr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yvedp.cn/Article/details/gtrvlxwikv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj20258.top/Article/details/gtcupuzxvi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.svipenyu.cn/Article/details/gtxderbxym.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.mhx1999.top/Article/details/gtgkqntyyg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xylfe.cn/Article/details/gtgfpdpqal.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yonumen.top/Article/details/gtqjvloyrx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.dashuyun.cn/Article/details/gtbhpovcdi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hysaishi.cn/Article/details/gtrssrttcu.html

[P03] 生成短随机字符串
来源：http://dali.andypj.xyz/Article/details/gtyzxddhtg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuanzx.com/Article/details/gtudpklvro.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sysykeji.top/Article/details/gtqbxpqmlg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.svipenyu.cn/Article/details/gthdekywia.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuxming.cn/Article/details/gtemyblmvw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.aizwys.cn/Article/details/gtscjyqkzw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xziqi.cn/Article/details/gtoenjezsa.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.mhx1999.top/Article/details/gtytegspib.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinqigufen.top/Article/details/gtaezqbsln.html

[P04] 求长度
来源：http://dali.pycfn.com/Article/details/gtqffckibm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tanke756.top/Article/details/gtzapewvmn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gthqjppokc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dianchejie.cn/Article/details/gtozhvarwu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pengpengdd.cyou/Article/details/gtsthsalro.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hongshengwenyu.top/Article/details/gtxqugyzbt.html

Go:   len(arr);  len(m)
来源：http://dali.pycfn.com/Article/details/gtvusclrxo.html

Ruby: x.length;  x.size
来源：http://dali.sweek.top/Article/details/gtoyrkibul.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.kuanghao11.cn/Article/details/gthscmsepp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sufxvd.cn/Article/details/gtfnkkdelp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tianlin.xyz/Article/details/gtbdxdaqdv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shanyushiyangtech.top/Article/details/gtakmuhtuf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.andypj.xyz/Article/details/gtfxakivgd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aizwys.cn/Article/details/gtkjgovqyu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guowangkeji.top/Article/details/gtxvhpkzoc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxinatsml.html

Ruby: a == b
来源：http://dali.redwolf501.top/Article/details/gteazrgzsl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ybcxt.top/Article/details/gtlfljffwo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xziqi.cn/Article/details/gtjjlldjal.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nanxuanxn.top/Article/details/gtlznblidv.html

PHP:  if (empty($x)) {}
来源：http://dali.fzhhl.top/Article/details/gtgvbjhnjz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.havefunace.top/Article/details/gtcyypumxi.html

TS:   if (x == null) {}
来源：http://dali.snrcjt.cn/Article/details/gtaiycpjvx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.vqdsnc.cn/Article/details/gtjzstrtyw.html

Go:   if x == nil {}
来源：http://dali.fzhhl.top/Article/details/gtpwrplddt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shuidangran.top/Article/details/gtvenpaqsg.html

C#:   if (x is null) {}
来源：http://dali.jianghu66.top/Article/details/gteaseebgc.html

[P07] 防抖与节流
来源：http://dali.yuanzhike.top/Article/details/gtlmgrhmwk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.bjfxy.top/Article/details/gtkfoqnvtb.html

PHP:  // 手写时间戳比较
来源：http://dali.cheryme.top/Article/details/gtwhesfdqg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlrnnjmbd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gtnrveqeiw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hnxiangtu.top/Article/details/gtqpylwuen.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jianghu66.top/Article/details/gttqktllpz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yuxming.cn/Article/details/gtvmarnajt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ppjwa.cn/Article/details/gtsjyleijp.html

[P08] 处理浮点精度问题
来源：http://dali.sufxvd.cn/Article/details/gtzgnfrikz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hysaishi.cn/Article/details/gtkongijmf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj202588.top/Article/details/gtordueugd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.daria6918.cn/Article/details/gtaetkagzf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.quarkkingdee.top/Article/details/gtqknnttky.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpgxeatrk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nwbrower.top/Article/details/gtylvfsalu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cucudq.cn/Article/details/gtuoaplkuf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jlsjyb.cn/Article/details/gtmaeqxvdn.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtxgwryboe.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cdnleiting.top/Article/details/gtjfibdwat.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtkdiyowwk.html

[Q01] 创建表
来源：http://dali.tianlin.xyz/Article/details/gtsamcqyhu.html

CREATE TABLE users (
来源：http://dali.nanxinkj.top/Article/details/gtnsyguddf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.316326.xyz/Article/details/gtzkzlttit.html

name VARCHAR(50) NOT NULL,
来源：http://dali.meibo888.top/Article/details/gtocqbriix.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpjndkoa.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jqgufenzy.top/Article/details/gtyalsvybw.html

);
来源：http://dali.tian-w.cn/Article/details/gtbimvhkmq.html

[Q02] 创建带外键的表
来源：http://dali.tianlin.xyz/Article/details/gtupxqqqhm.html

CREATE TABLE orders (
来源：http://dali.mhx1999.top/Article/details/gtrbnqvmgl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tianlin.xyz/Article/details/gtroixxlxg.html

user_id INT NOT NULL,
来源：http://dali.sxryk.cn/Article/details/gtsxkideak.html

amount DECIMAL(10, 2),
来源：http://dali.zhixingplan.top/Article/details/gtkziogpai.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ydzc1.top/Article/details/gtquxwnslz.html

);
来源：http://dali.vqdsnc.cn/Article/details/gtwceyrnlj.html

[Q03] 增加列
来源：http://dali.zycfv.cn/Article/details/gtscbdrcdu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.tianlin.xyz/Article/details/gtflttuxvb.html

[Q04] 修改列类型
来源：http://dali.zhiwuduotai.top/Article/details/gtklqurhea.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yvedp.cn/Article/details/gtycamztga.html

[Q05] 重命名列
来源：http://dali.yj20258888.top/Article/details/gtmcqbxhpz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.bjfxy.top/Article/details/gtkwpmpqyt.html

[Q06] 删除列
来源：http://dali.zdqjudy.top/Article/details/gtcbbkxyyl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sxryk.cn/Article/details/gtpuaipdtz.html

[Q07] 删除表
来源：http://dali.xziqi.cn/Article/details/gtgaaxeusg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xylfe.cn/Article/details/gtwjsojvyr.html

[Q08] 创建普通索引
来源：http://dali.smart0.xyz/Article/details/gtnyzdbssv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gtcieojpip.html

[Q09] 创建唯一索引
来源：http://dali.9152youxi.cn/Article/details/gtxxqbdotz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cqqwz.cn/Article/details/gtqdjxmxbw.html

[Q10] 插入单行
来源：http://dali.nanxinkj.top/Article/details/gtcbeygpvr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.316326.xyz/Article/details/gtjvuuoeiz.html

[Q11] 一次插入多行
来源：http://dali.zhixingplan.top/Article/details/gtlcgnrlap.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.aizwys.cn/Article/details/gtatocuufi.html

[Q12] 插入后取自增 ID
来源：http://dali.cashguo.top/Article/details/gtifpxrbns.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.9152youxi.cn/Article/details/gtugtrhmci.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ybcxt.top/Article/details/gtznkysknm.html

[Q13] 忽略重复插入
来源：http://dali.svipenyu.cn/Article/details/gtfacjebtt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ppjwa.cn/Article/details/gtryscocen.html

[Q14] 存在则更新（upsert）
来源：http://dali.nwbrower.top/Article/details/gtzjuguzjp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zdqjudy.top/Article/details/gtjbmsxuxh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.haohaochexian.top/Article/details/gtccshregb.html

[Q15] 查询全部
来源：http://dali.guowangkeji.top/Article/details/gtdktzsrqg.html

SELECT * FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtikzqwlrt.html

[Q16] 查询指定列
来源：http://dali.jlsjyb.cn/Article/details/gtszlnygab.html

SELECT id, name FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtqoobprsi.html

[Q17] 条件查询
来源：http://dali.xinyue.icu/Article/details/gtpspxtdby.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yongpay.top/Article/details/gtwcmxoiac.html

[Q18] 模糊匹配
来源：http://dali.316326.xyz/Article/details/gtjvyuwcyf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sufxvd.cn/Article/details/gtalbozxmq.html

[Q19] 范围查询
来源：http://dali.nanxuanxn.top/Article/details/gtduvberzl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.iojbl.cn/Article/details/gtpxluevqf.html

[Q20] IN 列表
来源：http://dali.zhongyouzk.top/Article/details/gtfhdnhgyl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gteishykar.html

[Q21] 空值判断
来源：http://dali.yueranfly.top/Article/details/gtfwmvjskt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcpkifsym.html

[Q22] 排序
来源：http://dali.yueranfly.top/Article/details/gtkspgizop.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hywenlv.cn/Article/details/gtoseqwtuc.html

[Q23] 分页
来源：http://dali.daria6918.cn/Article/details/gtepuzvnbo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jqgfzy.top/Article/details/gtxeziikbl.html

[Q24] 去重
来源：http://dali.zdqjudy.top/Article/details/gtsbykaemj.html

SELECT DISTINCT city FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtsktblyyq.html

[Q25] 只取前 N 条
来源：http://dali.chenjidiqi.icu/Article/details/gtzcclepbz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.guannengcc.top/Article/details/gtxcfusyok.html

[Q26] 计数
来源：http://dali.zycfv.cn/Article/details/gtyeloszmo.html

SELECT COUNT(*) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtxzrajbyd.html

[Q27] 条件计数
来源：http://dali.316326.xyz/Article/details/gtvjrkbmyx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtlhtktgdg.html

[Q28] 求和与平均
来源：http://dali.chenlongwang.top/Article/details/gtzvauknab.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtmxylxjfr.html

[Q29] 最大最小值
来源：http://dali.wangdashe.top/Article/details/gtkkfhqvod.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.meibo888.top/Article/details/gtlpmmlllv.html

[Q30] 分组统计
来源：http://dali.smart0.xyz/Article/details/gtvxnfupgy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gtbyiqfgot.html

[Q31] 分组后过滤
来源：http://dali.xuanzx.com/Article/details/gtkflmmubv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenzaomai.com/Article/details/gtzvpjopqv.html

[Q32] 分组拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gtygnypduf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gtklzkmpeo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hysaishi.cn/Article/details/gtiyrzwmgs.html

[Q33] 多列分组
来源：http://dali.yuxming.cn/Article/details/gtyksusgzp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yj20258888.top/Article/details/gtigkhwpyb.html

[Q34] 每组取第一条
来源：http://dali.yangfankeji.com/Article/details/gtamnayslm.html

SELECT * FROM (
来源：http://dali.jianghu66.top/Article/details/gtmpfhtfgk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gzhubu.top/Article/details/gtpdfgarhi.html

) t WHERE rn = 1;
来源：http://dali.hysaishi.cn/Article/details/gtnsvrxfie.html

[Q35] 内连接
来源：http://dali.daria6918.cn/Article/details/gtkdczkvcx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jlsjyb.cn/Article/details/gtopngqeye.html

[Q36] 左连接
来源：http://dali.ybcxt.top/Article/details/gtpusdefxk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuanzhike.top/Article/details/gtsrvtbdyq.html

[Q37] 右连接
来源：http://dali.xziqi.cn/Article/details/gtndsmhgmw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xuanzx.com/Article/details/gtxjiallnt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yuxming.cn/Article/details/gtdwkgdqub.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yangfankeji.com/Article/details/gtwyevqejf.html

[Q39] 自连接（查上下级）
来源：http://dali.jinqigfzy.top/Article/details/gtdkjovjel.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yvedp.cn/Article/details/gtvzwrcchb.html


<!-- 参考信息 -->