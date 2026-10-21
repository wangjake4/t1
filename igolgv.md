代发 wailian999

[N05] 最大公约数
来源：http://dali.meibo888.top/Article/details/gthywvvhjn.html

Py:   math.gcd(a, b)
来源：http://dali.bjfxy.top/Article/details/gtxtgxbsro.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhixingplan.top/Article/details/gtcqfzvbvl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dianchejie.cn/Article/details/gttzutzgme.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hywenlv.cn/Article/details/gtgxdiozth.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jyoumei.cn/Article/details/gtoanbvyrv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.andypj.xyz/Article/details/gtuicjnmiv.html

Ruby: a.gcd(b)
来源：http://dali.ehwqpu.com/Article/details/gtvolsmlmd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzghrfxv.html

[N06] 判断回文字符串
来源：http://dali.jqgufenzy.top/Article/details/gtchosrpts.html

Py:   s == s[::-1]
来源：http://dali.fzhhl.top/Article/details/gtfrrvczlu.html

PHP:  $s === strrev($s);
来源：http://dali.zycfv.cn/Article/details/gttamdvejw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbtutpwzb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gthcqgtgvr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhixingplan.top/Article/details/gtxkohokxl.html

Go:   // 双指针从两端比较
来源：http://dali.bjfxy.top/Article/details/gtqglyfmgf.html

Ruby: s == s.reverse
来源：http://dali.zycfv.cn/Article/details/gtfrdwjuml.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.iojbl.cn/Article/details/gtqhvzzqsz.html

[N07] 两数之和（返回下标）
来源：http://dali.fzhhl.top/Article/details/gtlvkfzgei.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.birdmap.top/Article/details/gtbxiqnigb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tianlin.xyz/Article/details/gtrzemnoqg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xziqi.cn/Article/details/gtjroslxlo.html

TS:   // 手写 Map<string, number>
来源：http://dali.jlsjyb.cn/Article/details/gtsvddvgtq.html

Java: // 手写 HashMap
来源：http://dali.zdqjudy.top/Article/details/gtctkdtopn.html

Go:   // 手写 map[int]int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxwfwdgg.html

Ruby: // 手写 Hash
来源：http://dali.birdmap.top/Article/details/gtkkzrmooz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.havefunace.top/Article/details/gtpkdbayni.html

[N08] 生成全排列
来源：http://dali.gzhubu.top/Article/details/gtwsnyaiho.html

Py:   itertools.permutations(arr)
来源：http://dali.xinyue.icu/Article/details/gtzmwoplvc.html

PHP:  // 手写递归交换
来源：http://dali.sufxvd.cn/Article/details/gttlpudlfk.html

JS:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtnhbosijq.html

TS:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtfmcdeohc.html

Java: // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtysiujibz.html

Go:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtpcbwmevh.html

Ruby: arr.permutation.to_a
来源：http://dali.tian-w.cn/Article/details/gtntffpfpm.html

C#:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtmemqwznx.html

[N09] 栈与队列
来源：http://dali.xuanzx.com/Article/details/gtcfiriywg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yuxming.cn/Article/details/gtqbdegmaf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yj20258888.top/Article/details/gtczbfykln.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sxryk.cn/Article/details/gtdkhptsut.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj20258.top/Article/details/gtkcmocqnr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yueranfly.top/Article/details/gtfqbucapr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hfpthk.cn/Article/details/gtzhptravg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cheryme.top/Article/details/gtovprjjzc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.wangshuangyany.cn/Article/details/gtwkcbrxxo.html

[N10] 链表节点定义
来源：http://dali.zhongyouzk.top/Article/details/gtzymoiuxt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yvedp.cn/Article/details/gtwendkgyf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.andypj.xyz/Article/details/gtwaqixuog.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.aibaodan.cn/Article/details/gtwamtvims.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ppjwa.cn/Article/details/gtifrxhtmc.html

Java: class Node { int v; Node next; }
来源：http://dali.pycfn.com/Article/details/gtmhosbooi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.andypj.xyz/Article/details/gtdcaqfucy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.dianchejie.cn/Article/details/gtekujglnm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.fzhhl.top/Article/details/gtcdvntxdf.html

[N11] 二叉树中序遍历
来源：http://dali.daria6918.cn/Article/details/gtkosapakb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.nwbrower.top/Article/details/gthttucjhh.html

PHP:  // 手写递归函数
来源：http://dali.sweek.top/Article/details/gtxxquxgjt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gotoacloud.top/Article/details/gttsqsclhg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yongpay.top/Article/details/gttgyftinp.html

Java: // 手写递归
来源：http://dali.andypj.xyz/Article/details/gtdfidgugt.html

Go:   // 手写递归
来源：http://dali.birdmap.top/Article/details/gtobaewawl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gzhubu.top/Article/details/gtbfivakhh.html

C#:   // 手写递归
来源：http://dali.hnqzz.top/Article/details/gtzregxgvj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yuanzhike.top/Article/details/gtscndians.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tianlin.xyz/Article/details/gtnvvcnegg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cqqwz.cn/Article/details/gtgffdlhvf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhiwuduotai.top/Article/details/gtzhntrqve.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cashguo.top/Article/details/gtthrfudfq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258.top/Article/details/gtjxnkjdkb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sxryk.cn/Article/details/gtoamkjwtg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gtanzmsrhb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangdashe.top/Article/details/gtmkygvacj.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtxkozkrsw.html

O. 并发与异步
来源：http://dali.tian-w.cn/Article/details/gtywzjlauu.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtecdqgvpt.html

[O01] 启动一个线程
来源：http://dali.jlsjyb.cn/Article/details/gtjpmiuaot.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbkgazbk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hnxiangtu.top/Article/details/gtvmhhicen.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nanxinkj.top/Article/details/gtwyrvetcw.html

TS:   // 同 JS
来源：http://dali.zhoulong.xyz/Article/details/gtaymzvecm.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgymrirlc.html

Go:   go f()
来源：http://dali.cashguo.top/Article/details/gtvpwdqadn.html

Ruby: Thread.new { f }
来源：http://dali.ppjwa.cn/Article/details/gtaxonvilb.html

C#:   Task.Run(() => F());
来源：http://dali.zhengqikj.top/Article/details/gtnfpwefck.html

[O02] 使用线程池
来源：http://dali.redwolf501.top/Article/details/gthbyveteo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sweek.top/Article/details/gtnhvtngfl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hnxiangtu.top/Article/details/gttjygukiz.html

JS:   // worker_threads 线程池
来源：http://dali.gzhubu.top/Article/details/gtzlpcudak.html

TS:   // worker_threads 线程池
来源：http://dali.xinyue.icu/Article/details/gthxkjqiof.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hongshengwenyu.top/Article/details/gtexooogzj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.havefunace.top/Article/details/gthyoksspr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jyoumei.cn/Article/details/gtlngsbtgi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj20258888.top/Article/details/gtshoxrujc.html

[O03] 加锁保护共享数据
来源：http://dali.cdnleiting.top/Article/details/gtlvoxkkwg.html

Py:   with lock: shared += 1
来源：http://dali.9152youxi.cn/Article/details/gtezrypmbb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.wangshuangyany.cn/Article/details/gtieugqqgq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdyunvnpd.html

TS:   // 同 JS
来源：http://dali.shanyushiyangtech.top/Article/details/gtiblzydex.html

Java: synchronized (this) { shared++; }
来源：http://dali.gotoacloud.top/Article/details/gtixndjvtp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jianghu66.top/Article/details/gtybexdslv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhongyouzk.top/Article/details/gtyzijwead.html

C#:   lock (gate) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gtsxrpprkj.html

[O04] 定义异步函数并等待
来源：http://dali.dashuyun.cn/Article/details/gtpuooyhek.html

Py:   async def f():⏎    await g()
来源：http://dali.havefunace.top/Article/details/gtbgjeccwk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.9152youxi.cn/Article/details/gtvvvbpcyg.html

JS:   async function f() { await g(); }
来源：http://dali.jyoumei.cn/Article/details/gtnkjsemvl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sweek.top/Article/details/gtkcjmdlni.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.mhx1999.top/Article/details/gtotzxvjup.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jianghu66.top/Article/details/gtqjfujkzw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhengqikj.top/Article/details/gtxbjbdvma.html

C#:   async Task F() { await G(); }
来源：http://dali.kuanghao11.cn/Article/details/gtpcmitrrn.html

[O05] 并发执行并等待全部完成
来源：http://dali.gogol.net.cn/Article/details/gtxgrqhxas.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cheryme.top/Article/details/gtxsozvyyt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jiagoushi.top/Article/details/gtzumlsezy.html

JS:   await Promise.all(tasks)
来源：http://dali.havefunace.top/Article/details/gtmdsnoaxq.html

TS:   await Promise.all(tasks)
来源：http://dali.zycfv.cn/Article/details/gtkqhfijzs.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.iojbl.cn/Article/details/gtgtcidtlz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj20258.top/Article/details/gtpkjxaevk.html

Ruby: threads.map(&:join)
来源：http://dali.jqgufenzy.top/Article/details/gttculxguz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hnxiangtu.top/Article/details/gtvsowmkbm.html

[O06] 使用进程池
来源：http://dali.yj202588.top/Article/details/gtnpvasuox.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cheryme.top/Article/details/gtcwggyjjk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhiwuduotai.top/Article/details/gtopbodguf.html

JS:   // child_process / cluster 模块
来源：http://dali.yongpay.top/Article/details/gtbawbsnhb.html

TS:   // child_process / cluster 模块
来源：http://dali.jinghuilouyu.cn/Article/details/gtcjlimxrq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gzhubu.top/Article/details/gtexanejam.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jlsjyb.cn/Article/details/gtozigwozl.html

Ruby: // fork 块
来源：http://dali.redwolf501.top/Article/details/gtrqhrgknz.html

C#:   Parallel.For
来源：http://dali.c1oappe.top/Article/details/gtuzetfzdy.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtqjujrgiw.html

P. 常用工具函数
来源：http://dali.yj202588.top/Article/details/gttxvuxges.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtcfcqwkgr.html

[P01] 生成 UUID
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgcfzyaxw.html

Py:   str(uuid.uuid4())
来源：http://dali.jqgfzy.top/Article/details/gtdvnrqfrs.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinyuanbaomall.cn/Article/details/gttgydsvvs.html

JS:   crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gtlhycbfng.html

TS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttsqeeoal.html

Java: UUID.randomUUID().toString()
来源：http://dali.yanxiufei.cn/Article/details/gtlmfylakt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.quarkkingdee.top/Article/details/gtyiytfhar.html

Ruby: SecureRandom.uuid
来源：http://dali.hysaishi.cn/Article/details/gtnagjuakq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.kuanghao11.cn/Article/details/gtlupznmbw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhoulong.xyz/Article/details/gturvkgili.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tian-w.cn/Article/details/gtptgmkkav.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenzaomai.com/Article/details/gtcnubmhwd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenlongwang.top/Article/details/gtfiouxeck.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.iojbl.cn/Article/details/gtbjhfqria.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.fzhhl.top/Article/details/gttzhtguji.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj202588.top/Article/details/gtphjsnhms.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hammf.cn/Article/details/gtianvvquy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shangyingyoupin.top/Article/details/gthehtbfeb.html

[P03] 生成短随机字符串
来源：http://dali.snrcjt.cn/Article/details/gtagsujkyv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.316326.xyz/Article/details/gtpnapljgo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ehwqpu.com/Article/details/gthvwhenmw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jiagoushi.top/Article/details/gtcgdquqpn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gtqruzdsli.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gttskvdbnq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yueranfly.top/Article/details/gtmetmyiqw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nanxuanxn.top/Article/details/gthitmtset.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yangfankeji.com/Article/details/gtyhhluwrg.html

[P04] 求长度
来源：http://dali.nanxuanxn.top/Article/details/gtndspodfc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.9152youxi.cn/Article/details/gtqmcunxmq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtpwlnabgh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxinkj.top/Article/details/gtlskqsemb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gtgiqaxvxi.html

Java: list.size();  map.size();  s.length()
来源：http://dali.feifeiyinyue.top/Article/details/gthhfpddzc.html

Go:   len(arr);  len(m)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxusqsfvi.html

Ruby: x.length;  x.size
来源：http://dali.sxryk.cn/Article/details/gtxmjcajxo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cheryme.top/Article/details/gtqvoflqod.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gzhubu.top/Article/details/gtathognrh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.9152youxi.cn/Article/details/gtuktsaerw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gtrtmjcweb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hywenlv.cn/Article/details/gtltbcjjrl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cashguo.top/Article/details/gtwgnsoxkz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gotoacloud.top/Article/details/gtrxhaqpzd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.guannengcc.top/Article/details/gteyzbezyx.html

Ruby: a == b
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbmnvmnp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj20258.top/Article/details/gtwjyuybfe.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hammf.cn/Article/details/gtjlcoiehv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jiagoushi.top/Article/details/gtmybzppul.html

PHP:  if (empty($x)) {}
来源：http://dali.tanke756.top/Article/details/gtoxpufred.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.vqdsnc.cn/Article/details/gtnfponrbr.html

TS:   if (x == null) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtjalqshhb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtianeplxn.html

Go:   if x == nil {}
来源：http://dali.sxryk.cn/Article/details/gtksipvfuo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.wangshuangyany.cn/Article/details/gtoyozqbsu.html

C#:   if (x is null) {}
来源：http://dali.xinyue.icu/Article/details/gtjbacajri.html

[P07] 防抖与节流
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnwvpmden.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinqigufen.top/Article/details/gtnlzlwwii.html

PHP:  // 手写时间戳比较
来源：http://dali.redwolf501.top/Article/details/gtflghmqjx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gtlbslzhso.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hysaishi.cn/Article/details/gtnipqphfn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jyoumei.cn/Article/details/gtqguyiber.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hammf.cn/Article/details/gtbwmswvwp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.guannengcc.top/Article/details/gtuagtklya.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.9152youxi.cn/Article/details/gtrptesapv.html

[P08] 处理浮点精度问题
来源：http://dali.jqgufenzy.top/Article/details/gtxgszjzpk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fzhhl.top/Article/details/gtxnyggnsd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.iojbl.cn/Article/details/gtnwfplmzb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gogol.net.cn/Article/details/gtxowrxbux.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhongyouzk.top/Article/details/gtaxihcoiz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.kuanghao11.cn/Article/details/gtjyyqbpso.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shuidangran.top/Article/details/gtxxidawvh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ehwqpu.com/Article/details/gtjvpwsxoz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.chenlongwang.top/Article/details/gtiitbyucd.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtuekjezau.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.c1oappe.top/Article/details/gtgvpftkri.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtymickycp.html

[Q01] 创建表
来源：http://dali.chenlongwang.top/Article/details/gthzdwevjw.html

CREATE TABLE users (
来源：http://dali.yuanzhike.top/Article/details/gtggteeesm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.vqdsnc.cn/Article/details/gtwdtutqto.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yuxming.cn/Article/details/gtjrankqtq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shuidangran.top/Article/details/gtgilynwxv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shanyushiyangtech.top/Article/details/gtyewnsypo.html

);
来源：http://dali.svipenyu.cn/Article/details/gtpdruvqfr.html

[Q02] 创建带外键的表
来源：http://dali.sxryk.cn/Article/details/gtgkacknqd.html

CREATE TABLE orders (
来源：http://dali.chenlongwang.top/Article/details/gtmavbiwcv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangtech.top/Article/details/gtkqxlphqj.html

user_id INT NOT NULL,
来源：http://dali.feifeiyinyue.top/Article/details/gtifelgfcw.html

amount DECIMAL(10, 2),
来源：http://dali.zhaomingkeji.xyz/Article/details/gtychgvarv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yj20258888.top/Article/details/gttdxngazb.html

);
来源：http://dali.yangfankeji.com/Article/details/gtrebohhph.html

[Q03] 增加列
来源：http://dali.yj202588.top/Article/details/gtgeloutmh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhixingplan.top/Article/details/gtgaoduqyv.html

[Q04] 修改列类型
来源：http://dali.c1oappe.top/Article/details/gtoqwaigoh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cdnleiting.top/Article/details/gtsnqhcesf.html

[Q05] 重命名列
来源：http://dali.zhiwuduotai.top/Article/details/gtowtrfmuw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.birdmap.top/Article/details/gtuginyxle.html

[Q06] 删除列
来源：http://dali.redwolf501.top/Article/details/gtptulldfm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.fengsongda.top/Article/details/gtfpcijpep.html

[Q07] 删除表
来源：http://dali.zycfv.cn/Article/details/gtckpretdu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cashguo.top/Article/details/gtbulzxkba.html

[Q08] 创建普通索引
来源：http://dali.yangfankeji.com/Article/details/gtdmdhyzts.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xinyue.icu/Article/details/gtqvwkflri.html

[Q09] 创建唯一索引
来源：http://dali.gogol.net.cn/Article/details/gtdcxnjsnj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.c1oappe.top/Article/details/gtucelecxi.html

[Q10] 插入单行
来源：http://dali.xuanzx.com/Article/details/gtvbpbokdi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gtprfsbocp.html

[Q11] 一次插入多行
来源：http://dali.jinqigufen.top/Article/details/gtekzpmaqj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbyurorde.html

[Q12] 插入后取自增 ID
来源：http://dali.jianghu66.top/Article/details/gtcjfsyozo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxinkj.top/Article/details/gtzbstgbtb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tianlin.xyz/Article/details/gtkigcxkpa.html

[Q13] 忽略重复插入
来源：http://dali.zycfv.cn/Article/details/gtaqlbemcz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gtkivcrnid.html

[Q14] 存在则更新（upsert）
来源：http://dali.pycfn.com/Article/details/gtmzlfghut.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sysykeji.top/Article/details/gtoknhhurt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.havefunace.top/Article/details/gtyurmunxk.html

[Q15] 查询全部
来源：http://dali.9152youxi.cn/Article/details/gtdezrwqpy.html

SELECT * FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtgyjolcfd.html

[Q16] 查询指定列
来源：http://dali.chenjidiqi.icu/Article/details/gtxvswfanr.html

SELECT id, name FROM users;
来源：http://dali.birdmap.top/Article/details/gtomcxgwyl.html

[Q17] 条件查询
来源：http://dali.havefunace.top/Article/details/gtcgumxgmw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtmlntbrvg.html

[Q18] 模糊匹配
来源：http://dali.yangfankeji.com/Article/details/gtdiwcpqqx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gaohongyu789.top/Article/details/gtmgixsoob.html

[Q19] 范围查询
来源：http://dali.zhiwuduotai.top/Article/details/gtqfkarwxv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwmqomwn.html

[Q20] IN 列表
来源：http://dali.vqdsnc.cn/Article/details/gtrkuyoxys.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tian-w.cn/Article/details/gtbkvnnreg.html

[Q21] 空值判断
来源：http://dali.xuanzx.com/Article/details/gtqwrvpitc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jiagoushi.top/Article/details/gtezkqchtt.html

[Q22] 排序
来源：http://dali.xuanzx.com/Article/details/gtsvxtewvp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhixingplan.top/Article/details/gtxwvxloos.html

[Q23] 分页
来源：http://dali.shuidangran.top/Article/details/gtoeklqcez.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.andypj.xyz/Article/details/gtqvolftxk.html

[Q24] 去重
来源：http://dali.ybcxt.top/Article/details/gtbxzezuem.html

SELECT DISTINCT city FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtanfqjarr.html

[Q25] 只取前 N 条
来源：http://dali.gaohongyu789.top/Article/details/gtsikeqfeh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cucudq.cn/Article/details/gtastehnof.html

[Q26] 计数
来源：http://dali.yonumen.top/Article/details/gtaqmixldr.html

SELECT COUNT(*) FROM users;
来源：http://dali.tanke756.top/Article/details/gtdsretdiy.html

[Q27] 条件计数
来源：http://dali.sysykeji.top/Article/details/gtdhfbljki.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sxryk.cn/Article/details/gtlxaatytl.html

[Q28] 求和与平均
来源：http://dali.redwolf501.top/Article/details/gtzyplwzak.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtrddksjis.html

[Q29] 最大最小值
来源：http://dali.tanke756.top/Article/details/gtwszepaam.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtgygjfwll.html

[Q30] 分组统计
来源：http://dali.daria6918.cn/Article/details/gtnaezdogz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gtrslgtukd.html

[Q31] 分组后过滤
来源：http://dali.aibaodan.cn/Article/details/gtfpmcnvfl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yvedp.cn/Article/details/gtqvcxxnzu.html

[Q32] 分组拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gtbkahniqd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ppjwa.cn/Article/details/gtrpuhzuih.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.guannengcc.top/Article/details/gtyjcgvrye.html

[Q33] 多列分组
来源：http://dali.feifeiyinyue.top/Article/details/gtrudbbuca.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.c1oappe.top/Article/details/gtzutytgax.html

[Q34] 每组取第一条
来源：http://dali.jinghuilouyu.cn/Article/details/gtaseobqce.html

SELECT * FROM (
来源：http://dali.hnqzz.top/Article/details/gtderrdgun.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sweek.top/Article/details/gttmnbknkz.html

) t WHERE rn = 1;
来源：http://dali.snrcjt.cn/Article/details/gtutsygndo.html

[Q35] 内连接
来源：http://dali.hfpthk.cn/Article/details/gtzgtqsnme.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xylfe.cn/Article/details/gtdxkvbjbu.html

[Q36] 左连接
来源：http://dali.chenjidiqi.icu/Article/details/gtitmrnshr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tian-w.cn/Article/details/gtydarmljn.html

[Q37] 右连接
来源：http://dali.hfpthk.cn/Article/details/gtydqfpgtg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jlsjyb.cn/Article/details/gtndmflytv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.9152youxi.cn/Article/details/gtfpjlxcxs.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cucudq.cn/Article/details/gtaixxjngl.html

[Q39] 自连接（查上下级）
来源：http://dali.zhongyouzk.top/Article/details/gtkhxkuieu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.dianchejie.cn/Article/details/gtdkzshxyb.html


<!-- 参考信息 -->