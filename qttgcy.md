代发 wailian999

Ruby: s == s.reverse
来源：http://dali.hnxiangtu.top/Article/details/gtqzxziqid.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gtdhlutbfp.html

[N07] 两数之和（返回下标）
来源：http://dali.zhoulong.xyz/Article/details/gtlsccepfx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyoxmexqj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xziqi.cn/Article/details/gttrsfgfhg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhoulong.xyz/Article/details/gtansszakf.html

TS:   // 手写 Map<string, number>
来源：http://dali.nwbrower.top/Article/details/gtsquzikxg.html

Java: // 手写 HashMap
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcnqmuepd.html

Go:   // 手写 map[int]int
来源：http://dali.chenzaomai.com/Article/details/gtejhtnarg.html

Ruby: // 手写 Hash
来源：http://dali.pengpengdd.cyou/Article/details/gtccxcmvxz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinqigufen.top/Article/details/gtpzcgkdab.html

[N08] 生成全排列
来源：http://dali.zhixingplan.top/Article/details/gtkqividon.html

Py:   itertools.permutations(arr)
来源：http://dali.svipenyu.cn/Article/details/gteoeyrwax.html

PHP:  // 手写递归交换
来源：http://dali.yanxiufei.cn/Article/details/gtaebcolfu.html

JS:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtoptdkdeh.html

TS:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtnlcckofs.html

Java: // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqquedip.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzpljmsho.html

Ruby: arr.permutation.to_a
来源：http://dali.shanyushiyangtech.top/Article/details/gtqpmfetyc.html

C#:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gtzkacsjsv.html

[N09] 栈与队列
来源：http://dali.zhengqikj.top/Article/details/gtcurozkfs.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cucudq.cn/Article/details/gtdhqpmhmj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gtlnrypuvp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.fengsongda.top/Article/details/gtuimpnfer.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yueranfly.top/Article/details/gtprrahtju.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.dianchejie.cn/Article/details/gtywqglhtp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhoulong.xyz/Article/details/gtgbqtfwfn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.meibo888.top/Article/details/gtrkjkyrjf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yonumen.top/Article/details/gttgealozq.html

[N10] 链表节点定义
来源：http://dali.hongshengwenyu.top/Article/details/gtlksrasms.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.wangshuangyany.cn/Article/details/gtajkpdhid.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sweek.top/Article/details/gtvmpyzfri.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xziqi.cn/Article/details/gtvrozgnxq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jyoumei.cn/Article/details/gtoehnhykb.html

Java: class Node { int v; Node next; }
来源：http://dali.ehwqpu.com/Article/details/gtgdadlvnk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hfpthk.cn/Article/details/gttxoxexph.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yanxiufei.cn/Article/details/gtjoycevsg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.fengsongda.top/Article/details/gtdwlwdsma.html

[N11] 二叉树中序遍历
来源：http://dali.fzhhl.top/Article/details/gthxqircor.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sxryk.cn/Article/details/gtglnemjdz.html

PHP:  // 手写递归函数
来源：http://dali.dashuyun.cn/Article/details/gtssxawrtw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yanxiufei.cn/Article/details/gtrurbvcjo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenzaomai.com/Article/details/gtgvjpzqaq.html

Java: // 手写递归
来源：http://dali.yvedp.cn/Article/details/gtytnbiqqb.html

Go:   // 手写递归
来源：http://dali.andypj.xyz/Article/details/gtwouaactv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.wangdashe.top/Article/details/gtexvbfvrt.html

C#:   // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gtnxlrutaf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sweek.top/Article/details/gtimdrcsgs.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cheryme.top/Article/details/gtwnpnodgw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cucudq.cn/Article/details/gtoqrinuir.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258.top/Article/details/gtjisjmxak.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dianchejie.cn/Article/details/gtdjdxqkin.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxsxxeery.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jqgufenzy.top/Article/details/gtiykcxnrj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.dashuyun.cn/Article/details/gthbmcdlkr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtjelkxhfm.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtimrcgubv.html

O. 并发与异步
来源：http://dali.yangfankeji.com/Article/details/gtwqxzsqqs.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtrdmqjmms.html

[O01] 启动一个线程
来源：http://dali.zdqjudy.top/Article/details/gteaekfewe.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiphtakzn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.kuanghao11.cn/Article/details/gtxhhrnkal.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.mhx1999.top/Article/details/gtibkqeypc.html

TS:   // 同 JS
来源：http://dali.ivvv.top/Article/details/gtynradhyx.html

Java: new Thread(() -> f()).start()
来源：http://dali.9152youxi.cn/Article/details/gtosjthlxd.html

Go:   go f()
来源：http://dali.cashguo.top/Article/details/gtlugrsdny.html

Ruby: Thread.new { f }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkcimwtu.html

C#:   Task.Run(() => F());
来源：http://dali.jinqigfzy.top/Article/details/gtuurcyijz.html

[O02] 使用线程池
来源：http://dali.hfpthk.cn/Article/details/gtfupotvkm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ydzc1.top/Article/details/gtxjyctnsd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.daxiang520.top/Article/details/gtmpzykxwj.html

JS:   // worker_threads 线程池
来源：http://dali.ivvv.top/Article/details/gtpecfruxu.html

TS:   // worker_threads 线程池
来源：http://dali.andypj.xyz/Article/details/gtwipwhdky.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ivvv.top/Article/details/gtlgfzbptx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.bjfxy.top/Article/details/gtwkypakuh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinqigufen.top/Article/details/gtupwpblql.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.feifeiyinyue.top/Article/details/gtybwbmppl.html

[O03] 加锁保护共享数据
来源：http://dali.zhixingplan.top/Article/details/gtmygathsq.html

Py:   with lock: shared += 1
来源：http://dali.chenjidiqi.icu/Article/details/gtpjnwefnp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zycfv.cn/Article/details/gtilmmbybh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cheryme.top/Article/details/gturelyapc.html

TS:   // 同 JS
来源：http://dali.nanxinkj.top/Article/details/gtkauwgvap.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhixingplan.top/Article/details/gteyzgkwxg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yongpay.top/Article/details/gtwufcrqfw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nwbrower.top/Article/details/gtmzpfujko.html

C#:   lock (gate) { shared++; }
来源：http://dali.zdqjudy.top/Article/details/gtxfxeczvn.html

[O04] 定义异步函数并等待
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteivfqztp.html

Py:   async def f():⏎    await g()
来源：http://dali.birdmap.top/Article/details/gtjjiikesx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zycfv.cn/Article/details/gthxnnhmbk.html

JS:   async function f() { await g(); }
来源：http://dali.sufxvd.cn/Article/details/gtshylcahf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtwaplfriv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinqigfzy.top/Article/details/gtozculwah.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.tanke756.top/Article/details/gtzblhoyxc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ydzc1.top/Article/details/gtdqqorcnu.html

C#:   async Task F() { await G(); }
来源：http://dali.shuidangran.top/Article/details/gtqqlelgoy.html

[O05] 并发执行并等待全部完成
来源：http://dali.svipenyu.cn/Article/details/gtgnkfvxzf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cashguo.top/Article/details/gtawogajhj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.c1oappe.top/Article/details/gtxqtmqhmy.html

JS:   await Promise.all(tasks)
来源：http://dali.cheryme.top/Article/details/gtzherqjfr.html

TS:   await Promise.all(tasks)
来源：http://dali.iojbl.cn/Article/details/gtywmreouo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.guowangkeji.top/Article/details/gtfeanrbtm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hysaishi.cn/Article/details/gtsesbirbt.html

Ruby: threads.map(&:join)
来源：http://dali.yonumen.top/Article/details/gtapyfeaok.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fzhhl.top/Article/details/gtqhjbfwxt.html

[O06] 使用进程池
来源：http://dali.ivvv.top/Article/details/gtugfvcqkt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cdnleiting.top/Article/details/gthdvurscr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ppjwa.cn/Article/details/gtymterdxs.html

JS:   // child_process / cluster 模块
来源：http://dali.zhengqikj.top/Article/details/gtdedjgntn.html

TS:   // child_process / cluster 模块
来源：http://dali.gotoacloud.top/Article/details/gtshxcipqa.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cdnleiting.top/Article/details/gttrykeewg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.meibo888.top/Article/details/gtxcjxnimt.html

Ruby: // fork 块
来源：http://dali.sysykeji.top/Article/details/gtcbmdsuqa.html

C#:   Parallel.For
来源：http://dali.xylfe.cn/Article/details/gtyzsvhwcz.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtfytgcano.html

P. 常用工具函数
来源：http://dali.xuanzx.com/Article/details/gtsvxwnwpg.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtptazssgt.html

[P01] 生成 UUID
来源：http://dali.yangfankeji.com/Article/details/gtrhjyfmta.html

Py:   str(uuid.uuid4())
来源：http://dali.snrcjt.cn/Article/details/gtgtpqasdh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yanxiufei.cn/Article/details/gthhxulaxq.html

JS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaoallhmu.html

TS:   crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gtaitvhfgx.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhongyouzk.top/Article/details/gtmfsoirng.html

Go:   // 用 github.com/google/uuid
来源：http://dali.feifeiyinyue.top/Article/details/gtvxnbmdaf.html

Ruby: SecureRandom.uuid
来源：http://dali.tanke756.top/Article/details/gtvgenuxei.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hfpthk.cn/Article/details/gtrotowwrd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.andypj.xyz/Article/details/gtehwurfhr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.wangshuangyany.cn/Article/details/gtpagcfkwv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sysykeji.top/Article/details/gtgtvmzhjf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmiuvtysv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cqqwz.cn/Article/details/gtghihjfpq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258.top/Article/details/gtlrbjftbr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.316326.xyz/Article/details/gtmwkxbmwe.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.iojbl.cn/Article/details/gtlssuwrnb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.havefunace.top/Article/details/gtxnummzit.html

[P03] 生成短随机字符串
来源：http://dali.gogol.net.cn/Article/details/gtxnvdsluw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yongpay.top/Article/details/gtzthbyazw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.birdmap.top/Article/details/gtkfulwtfq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sysykeji.top/Article/details/gtfyequcmg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gaohongyu789.top/Article/details/gtlphhtvar.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenlongwang.top/Article/details/gtyfdsajbs.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.feifeiyinyue.top/Article/details/gtuftqkusg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tian-w.cn/Article/details/gtuitnswdo.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.havefunace.top/Article/details/gtcqfgkktt.html

[P04] 求长度
来源：http://dali.gogol.net.cn/Article/details/gtghafmguj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtevscrfec.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gtdynscnbc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fzhhl.top/Article/details/gtsmdzzkse.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sweek.top/Article/details/gtphfxwjpz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guowangkeji.top/Article/details/gtcbbouddi.html

Go:   len(arr);  len(m)
来源：http://dali.svipenyu.cn/Article/details/gttmmgnzyk.html

Ruby: x.length;  x.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtchrtsqbb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sufxvd.cn/Article/details/gtfilzaevw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gzhubu.top/Article/details/gtslcallnd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zdqjudy.top/Article/details/gtlmxqoohz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cucudq.cn/Article/details/gtjubpisfc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.andypj.xyz/Article/details/gtdwohwbjx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yvedp.cn/Article/details/gtzitrafpi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhaomingkeji.xyz/Article/details/gtckylipdg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.c1oappe.top/Article/details/gtgjkkccbt.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gtjlndphma.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinghuilouyu.cn/Article/details/gtemxspuwu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yongpay.top/Article/details/gtxunxvlyx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tian-w.cn/Article/details/gtmppaeqlm.html

PHP:  if (empty($x)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtcdmbsmie.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hnxiangtu.top/Article/details/gtgtfjlrxy.html

TS:   if (x == null) {}
来源：http://dali.guowangkeji.top/Article/details/gtrtpxjltc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.quarkkingdee.top/Article/details/gtemlxcdds.html

Go:   if x == nil {}
来源：http://dali.tanke756.top/Article/details/gthwetdcad.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yongpay.top/Article/details/gtiohyrgki.html

C#:   if (x is null) {}
来源：http://dali.zhixingplan.top/Article/details/gtvdqczoxl.html

[P07] 防抖与节流
来源：http://dali.xziqi.cn/Article/details/gtylopzmdg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj202588.top/Article/details/gtckjsitgu.html

PHP:  // 手写时间戳比较
来源：http://dali.cashguo.top/Article/details/gtxelrsout.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yanxiufei.cn/Article/details/gtcjdzkndb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtmrqnxwsr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj20258.top/Article/details/gtuaqhokwj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jqgufenzy.top/Article/details/gthqhipiel.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.feifeiyinyue.top/Article/details/gtispjvpmx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yangfankeji.com/Article/details/gtbzojwnpc.html

[P08] 处理浮点精度问题
来源：http://dali.aibaodan.cn/Article/details/gtlyczbiev.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhiwuduotai.top/Article/details/gtvpxrtubq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.vqdsnc.cn/Article/details/gtknnwqial.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gaohongyu789.top/Article/details/gtekelunog.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cucudq.cn/Article/details/gtcgfogxuj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.snrcjt.cn/Article/details/gtvkqgcibp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.wangshuangyany.cn/Article/details/gtezvueyco.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cqqwz.cn/Article/details/gtmmdxchtp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cqqwz.cn/Article/details/gtsgnnhmlg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtssebduzn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqnzztzxs.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtgtkmvvnj.html

[Q01] 创建表
来源：http://dali.cdnleiting.top/Article/details/gtxjniwdux.html

CREATE TABLE users (
来源：http://dali.9152youxi.cn/Article/details/gtrqrythwf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dashuyun.cn/Article/details/gtsfeeqsgk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenlongwang.top/Article/details/gtkrbwalnt.html

email VARCHAR(100) UNIQUE,
来源：http://dali.redwolf501.top/Article/details/gtcwkmunqg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj20258.top/Article/details/gtvkdklvol.html

);
来源：http://dali.birdmap.top/Article/details/gtthsjsxsg.html

[Q02] 创建带外键的表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwqlmfzu.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gtaygauoqm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.mhx1999.top/Article/details/gtjauvjcmy.html

user_id INT NOT NULL,
来源：http://dali.jinghuilouyu.cn/Article/details/gtvpxudkxd.html

amount DECIMAL(10, 2),
来源：http://dali.pengpengdd.cyou/Article/details/gtdqsnquct.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hnxiangtu.top/Article/details/gtlvniyket.html

);
来源：http://dali.hongshengwenyu.top/Article/details/gtbdflxukp.html

[Q03] 增加列
来源：http://dali.c1oappe.top/Article/details/gtgatrjlbq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yonumen.top/Article/details/gtvxbpsjtv.html

[Q04] 修改列类型
来源：http://dali.fzhhl.top/Article/details/gtggesfiar.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenjidiqi.icu/Article/details/gtptauyahi.html

[Q05] 重命名列
来源：http://dali.havefunace.top/Article/details/gtqqyvpmxd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xinyue.icu/Article/details/gtvwbdfzeo.html

[Q06] 删除列
来源：http://dali.chenlongwang.top/Article/details/gtfmntrmte.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jiagoushi.top/Article/details/gtfgdsomnu.html

[Q07] 删除表
来源：http://dali.zhoulong.xyz/Article/details/gtbvyofhiw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.haohaochexian.top/Article/details/gtbarbrtzf.html

[Q08] 创建普通索引
来源：http://dali.pengpengdd.cyou/Article/details/gtpknehojz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yongpay.top/Article/details/gtqljbrpjo.html

[Q09] 创建唯一索引
来源：http://dali.jqgufenzy.top/Article/details/gtcfsitxkl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nanxuanxn.top/Article/details/gtlkjqxexm.html

[Q10] 插入单行
来源：http://dali.hfpthk.cn/Article/details/gtuaerthjn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ydzc1.top/Article/details/gtercovwvp.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gteypvhmbl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xylfe.cn/Article/details/gtpgzdjcjg.html

[Q12] 插入后取自增 ID
来源：http://dali.yj202588.top/Article/details/gtibabkzaz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tian-w.cn/Article/details/gtvvpfpjfu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ppjwa.cn/Article/details/gtqtadvajk.html

[Q13] 忽略重复插入
来源：http://dali.ehwqpu.com/Article/details/gtcffamvfn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.daxiang520.top/Article/details/gtwlapjloa.html

[Q14] 存在则更新（upsert）
来源：http://dali.yonumen.top/Article/details/gtbbjazuln.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sufxvd.cn/Article/details/gtfadaynus.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.c1oappe.top/Article/details/gttjleuwnm.html

[Q15] 查询全部
来源：http://dali.tianlin.xyz/Article/details/gtssrbroal.html

SELECT * FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtpmhkrpmb.html

[Q16] 查询指定列
来源：http://dali.quarkkingdee.top/Article/details/gtywbyaddz.html

SELECT id, name FROM users;
来源：http://dali.yj202588.top/Article/details/gthkvezdyh.html

[Q17] 条件查询
来源：http://dali.yangfankeji.com/Article/details/gtypoignqr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtsusdgmpk.html

[Q18] 模糊匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtvdyxdbui.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shzxlz.cn/Article/details/gtlvvecjhp.html

[Q19] 范围查询
来源：http://dali.jqgfzy.top/Article/details/gtebqyxhpr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zdqjudy.top/Article/details/gtatuqxhql.html

[Q20] IN 列表
来源：http://dali.ydzc1.top/Article/details/gtdscjyzlq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yanxiufei.cn/Article/details/gtbmuqcszm.html

[Q21] 空值判断
来源：http://dali.9152youxi.cn/Article/details/gtaonbjhls.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tian-w.cn/Article/details/gtuevtkmwo.html

[Q22] 排序
来源：http://dali.feifeiyinyue.top/Article/details/gthoqhcwpo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhengqikj.top/Article/details/gtpitxdbzu.html

[Q23] 分页
来源：http://dali.nanxinkj.top/Article/details/gtfcvgkewj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yanxiufei.cn/Article/details/gthokufhtk.html

[Q24] 去重
来源：http://dali.chenzaomai.com/Article/details/gthwwebgvn.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkykyzcuh.html

[Q25] 只取前 N 条
来源：http://dali.shanyushiyangtech.top/Article/details/gtdcaibyum.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yongpay.top/Article/details/gtphhyilex.html

[Q26] 计数
来源：http://dali.ivvv.top/Article/details/gtrefgygxn.html

SELECT COUNT(*) FROM users;
来源：http://dali.tanke756.top/Article/details/gtifmnoxzq.html

[Q27] 条件计数
来源：http://dali.gogol.net.cn/Article/details/gtzuiqtuhk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtuvzhgibf.html

[Q28] 求和与平均
来源：http://dali.ivvv.top/Article/details/gtuuvshhmj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtfkqebszf.html

[Q29] 最大最小值
来源：http://dali.xinyue.icu/Article/details/gtiblazsyb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtecshpjme.html

[Q30] 分组统计
来源：http://dali.hnqzz.top/Article/details/gtjaibvykx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gtcopevhym.html

[Q31] 分组后过滤
来源：http://dali.ppjwa.cn/Article/details/gtpontzdrv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqkcejyxp.html

[Q32] 分组拼接字符串
来源：http://dali.andypj.xyz/Article/details/gttdctbowk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gtwvadvsgy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.andypj.xyz/Article/details/gtmjztuued.html

[Q33] 多列分组
来源：http://dali.zdqjudy.top/Article/details/gtpwuazhag.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhiwuduotai.top/Article/details/gtwzlqabus.html

[Q34] 每组取第一条
来源：http://dali.yj20258.top/Article/details/gtgcnrdgjv.html

SELECT * FROM (
来源：http://dali.jqgufenzy.top/Article/details/gtrjnbkllr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.quarkkingdee.top/Article/details/gtrnubsact.html

) t WHERE rn = 1;
来源：http://dali.chenlongwang.top/Article/details/gtgzibrexh.html

[Q35] 内连接
来源：http://dali.c1oappe.top/Article/details/gtjpsnzkfb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shzxlz.cn/Article/details/gtnlkcigcj.html

[Q36] 左连接
来源：http://dali.gzhubu.top/Article/details/gtshjilqpv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yonumen.top/Article/details/gtpmlblfvt.html

[Q37] 右连接
来源：http://dali.ivvv.top/Article/details/gtvrmiwgfq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.0kj1m.cn/Article/details/gtvxyyduzx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.feifeiyinyue.top/Article/details/gtxfufuwst.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gotoacloud.top/Article/details/gtnsinvnrh.html

[Q39] 自连接（查上下级）
来源：http://dali.ppjwa.cn/Article/details/gthutpskah.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ehwqpu.com/Article/details/gttmktddfh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sufxvd.cn/Article/details/gteutybtjs.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hfpthk.cn/Article/details/gtucegmhtj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cucudq.cn/Article/details/gtcvnacewg.html

[Q41] 多表连接
来源：http://dali.pengpengdd.cyou/Article/details/gtulclfguy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.quarkkingdee.top/Article/details/gtglqmwqfk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj20258.top/Article/details/gtpjjjqgkc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenjidiqi.icu/Article/details/gtijxtndxl.html

[Q42] 连接条件附加过滤
来源：http://dali.gotoacloud.top/Article/details/gtblejywmb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jqgfzy.top/Article/details/gtfzsvcben.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.svipenyu.cn/Article/details/gtzttdztwm.html

[Q43] 标量子查询
来源：http://dali.zhongyouzk.top/Article/details/gtjdmratpj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.mhx1999.top/Article/details/gtlonzbvmh.html

[Q44] IN 子查询
来源：http://dali.hysaishi.cn/Article/details/gtwncyqbqz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xylfe.cn/Article/details/gtnnlhpdsj.html

[Q45] EXISTS 判断存在
来源：http://dali.hywenlv.cn/Article/details/gtiiultmaq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tanke756.top/Article/details/gtddcibeph.html


<!-- 参考信息 -->