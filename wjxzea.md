代发 wailian999

JS:   s === [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gt2djgajwrc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gt2hpbarhha.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iicbmwra.html

Go:   // 双指针从两端比较
来源：http://dali.c1oappe.top/Article/details/gt2cmzpugft.html

Ruby: s == s.reverse
来源：http://dali.cashguo.top/Article/details/gt2igufdyaw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hongshengwenyu.top/Article/details/gt2nwroaqes.html

[N07] 两数之和（返回下标）
来源：http://dali.nanxuanxn.top/Article/details/gt2zogswene.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pengpengdd.cyou/Article/details/gt2cinzlpcw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yongpay.top/Article/details/gt2kqkfowth.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cddncnhj.html

TS:   // 手写 Map<string, number>
来源：http://dali.dianchejie.cn/Article/details/gt2mtfvhotr.html

Java: // 手写 HashMap
来源：http://dali.jiagoushi.top/Article/details/gt2hfbdhwjo.html

Go:   // 手写 map[int]int
来源：http://dali.zhiwuduotai.top/Article/details/gt2cbqjxjrm.html

Ruby: // 手写 Hash
来源：http://dali.9152youxi.cn/Article/details/gt2ccwbiqdd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ldyliwuw.html

[N08] 生成全排列
来源：http://dali.tianlin.xyz/Article/details/gt2nrnqxojs.html

Py:   itertools.permutations(arr)
来源：http://dali.zycfv.cn/Article/details/gt2xzdnzlej.html

PHP:  // 手写递归交换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kzlqokoq.html

JS:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gt2abbnoplt.html

TS:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gt2mrmbiyoi.html

Java: // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gt2xwquzshm.html

Go:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gt2hfuzyyop.html

Ruby: arr.permutation.to_a
来源：http://dali.jinqigfzy.top/Article/details/gt2abgeospa.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sfeorbuv.html

[N09] 栈与队列
来源：http://dali.zhongyouzk.top/Article/details/gt2djhlfpwg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gzhubu.top/Article/details/gt2ynplzcsu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.daxiang520.top/Article/details/gt2mjvxspsw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gt2pwzomgjq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gaohongyu789.top/Article/details/gt2xybvrsra.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nanxinkj.top/Article/details/gt2ribvtvyq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhixingplan.top/Article/details/gt2zctemico.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xinyue.icu/Article/details/gt2bxkiurev.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cucudq.cn/Article/details/gt2eelpbzpi.html

[N10] 链表节点定义
来源：http://dali.xylfe.cn/Article/details/gt2sigtlsym.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cucudq.cn/Article/details/gt2tchcxtsu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jlsjyb.cn/Article/details/gt2ddyqinhd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.havefunace.top/Article/details/gt2npspbfyo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nanxuanxn.top/Article/details/gt2ynewqidr.html

Java: class Node { int v; Node next; }
来源：http://dali.yuxming.cn/Article/details/gt2sbjaekwc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenzaomai.com/Article/details/gt2smwkfgve.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.guowangkeji.top/Article/details/gt2ddmamyuo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jianghu66.top/Article/details/gt2eqpxzoia.html

[N11] 二叉树中序遍历
来源：http://dali.wangdashe.top/Article/details/gt2gubjotxu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.nwbrower.top/Article/details/gt2jkildwpx.html

PHP:  // 手写递归函数
来源：http://dali.fzhhl.top/Article/details/gt2wtijiqpy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhixingplan.top/Article/details/gt2tldcduwy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yueranfly.top/Article/details/gt2bkafozzp.html

Java: // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2syyotkwm.html

Go:   // 手写递归
来源：http://dali.9152youxi.cn/Article/details/gt2hzninsvy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zdqjudy.top/Article/details/gt2fkajgpab.html

C#:   // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gt2ycwypbbj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xinyue.icu/Article/details/gt2kstwbjot.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gogol.net.cn/Article/details/gt2cwdodcio.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhengqikj.top/Article/details/gt2ovlcpbgm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pengpengdd.cyou/Article/details/gt2gptkybpb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gzhubu.top/Article/details/gt2dpbyupfp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnxiangtu.top/Article/details/gt2pzytuxfv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.316326.xyz/Article/details/gt2szmdgylg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bwxhjlec.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnxiangtu.top/Article/details/gt2nspujdcp.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2mkwzmwrh.html

O. 并发与异步
来源：http://dali.yvedp.cn/Article/details/gt2gvvzdvzc.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2ksqymarc.html

[O01] 启动一个线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uohltqhn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yongpay.top/Article/details/gt2ekhlehxb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cheryme.top/Article/details/gt2qzlioijl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.redwolf501.top/Article/details/gt2upllxkku.html

TS:   // 同 JS
来源：http://dali.aizwys.cn/Article/details/gt2karcfgkl.html

Java: new Thread(() -> f()).start()
来源：http://dali.quarkkingdee.top/Article/details/gt2etnplios.html

Go:   go f()
来源：http://dali.xuanzx.com/Article/details/gt2wpomkawa.html

Ruby: Thread.new { f }
来源：http://dali.pycfn.com/Article/details/gt2rcyfypck.html

C#:   Task.Run(() => F());
来源：http://dali.xziqi.cn/Article/details/gt2uaebynod.html

[O02] 使用线程池
来源：http://dali.chenzaomai.com/Article/details/gt2cccjtetp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cqqwz.cn/Article/details/gt2xdqoafbs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.birdmap.top/Article/details/gt2nuzyarfm.html

JS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gt2stpouznq.html

TS:   // worker_threads 线程池
来源：http://dali.aibaodan.cn/Article/details/gt2noilgwnt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hnxiangtu.top/Article/details/gt2tkhwbrnm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.316326.xyz/Article/details/gt2ejbkmmbl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.snrcjt.cn/Article/details/gt2ofteajbo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenlongwang.top/Article/details/gt2sqrpjzyf.html

[O03] 加锁保护共享数据
来源：http://dali.yonumen.top/Article/details/gt2namrsywu.html

Py:   with lock: shared += 1
来源：http://dali.9152youxi.cn/Article/details/gt2kglckezd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sxryk.cn/Article/details/gt2kxaabpkw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xuetiantiany.cn/Article/details/gt2gtscjkem.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gt2adzztnhy.html

Java: synchronized (this) { shared++; }
来源：http://dali.smart0.xyz/Article/details/gt2uatafiuq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.316326.xyz/Article/details/gt2rgbtsdcw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.redwolf501.top/Article/details/gt2mjjbtrvk.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj20258888.top/Article/details/gt2wwnqycqo.html

[O04] 定义异步函数并等待
来源：http://dali.ehwqpu.com/Article/details/gt2dnuhaukf.html

Py:   async def f():⏎    await g()
来源：http://dali.xinyue.icu/Article/details/gt2gcvqugqs.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tian-w.cn/Article/details/gt2swymhgqx.html

JS:   async function f() { await g(); }
来源：http://dali.sufxvd.cn/Article/details/gt2uefzvuip.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sxryk.cn/Article/details/gt2hopbuagm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.tian-w.cn/Article/details/gt2yvlvbgum.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenjidiqi.icu/Article/details/gt2crvyrfgp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nwbrower.top/Article/details/gt2hjgvhuwu.html

C#:   async Task F() { await G(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2mogtrykt.html

[O05] 并发执行并等待全部完成
来源：http://dali.sufxvd.cn/Article/details/gt2mxbiznol.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xinyue.icu/Article/details/gt2vateccan.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yuxming.cn/Article/details/gt2iyiuxlpp.html

JS:   await Promise.all(tasks)
来源：http://dali.daxiang520.top/Article/details/gt2tprqakrz.html

TS:   await Promise.all(tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tlygifni.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ivvv.top/Article/details/gt2ssjtweyc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhixingplan.top/Article/details/gt2nefuzgbb.html

Ruby: threads.map(&:join)
来源：http://dali.hnxiangtu.top/Article/details/gt2ezzorxpr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wmwfuhhs.html

[O06] 使用进程池
来源：http://dali.hywenlv.cn/Article/details/gt2eytanxlg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xuanzx.com/Article/details/gt2fyhcdxsb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhengqikj.top/Article/details/gt2adjfvoni.html

JS:   // child_process / cluster 模块
来源：http://dali.chenjidiqi.icu/Article/details/gt2oztskggj.html

TS:   // child_process / cluster 模块
来源：http://dali.dashuyun.cn/Article/details/gt2zvbmidfa.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhengqikj.top/Article/details/gt2krfhuxgs.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhongyouzk.top/Article/details/gt2wlyapgsr.html

Ruby: // fork 块
来源：http://dali.fengsongda.top/Article/details/gt2bygbugwn.html

C#:   Parallel.For
来源：http://dali.tanke756.top/Article/details/gt2gnnimmdj.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2sggufmbs.html

P. 常用工具函数
来源：http://dali.jqgufenzy.top/Article/details/gt2wjjkplcy.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vunqgbrn.html

[P01] 生成 UUID
来源：http://dali.hysaishi.cn/Article/details/gt2nghrbnst.html

Py:   str(uuid.uuid4())
来源：http://dali.kuanghao11.cn/Article/details/gt2chlhatpo.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xylfe.cn/Article/details/gt2dsajkxkc.html

JS:   crypto.randomUUID()
来源：http://dali.bjfxy.top/Article/details/gt2qozkoacf.html

TS:   crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gt2rorngexl.html

Java: UUID.randomUUID().toString()
来源：http://dali.andypj.xyz/Article/details/gt2uelfefdm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.snrcjt.cn/Article/details/gt2ymbgufyg.html

Ruby: SecureRandom.uuid
来源：http://dali.nanxinkj.top/Article/details/gt2jmikcibe.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jianghu66.top/Article/details/gt2fqlqtmmd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.pengpengdd.cyou/Article/details/gt2llzxjsjy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.fzhhl.top/Article/details/gt2hcqgooms.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hywenlv.cn/Article/details/gt2mpdlxjxa.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dtcfbvdz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.iojbl.cn/Article/details/gt2aluhkqaa.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.havefunace.top/Article/details/gt2rvtwfabp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cheryme.top/Article/details/gt2rzlhvyrk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yongpay.top/Article/details/gt2fewxfuir.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sysykeji.top/Article/details/gt2ovgcsney.html

[P03] 生成短随机字符串
来源：http://dali.yj20258.top/Article/details/gt2phrtgaze.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nwbrower.top/Article/details/gt2bckfbxcp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.c1oappe.top/Article/details/gt2rcdcvjgt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zdqjudy.top/Article/details/gt2clgjgrns.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.quarkkingdee.top/Article/details/gt2zjjztglo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yuanzhike.top/Article/details/gt2cqowixqp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aibaodan.cn/Article/details/gt2dsfpmbzc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.wangdashe.top/Article/details/gt2dxronvsz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hywenlv.cn/Article/details/gt2btkdowab.html

[P04] 求长度
来源：http://dali.shangyingyoupin.top/Article/details/gt2plkplvua.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tianlin.xyz/Article/details/gt2zvpkgowk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gt2whqlqwsa.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.iojbl.cn/Article/details/gt2nkgskalt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zycfv.cn/Article/details/gt2biqmfdpu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.redwolf501.top/Article/details/gt2tmkqwivi.html

Go:   len(arr);  len(m)
来源：http://dali.hywenlv.cn/Article/details/gt2rqrfvvdc.html

Ruby: x.length;  x.size
来源：http://dali.wangdashe.top/Article/details/gt2dujwmzie.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gt2yzbianmu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tanke756.top/Article/details/gt2wewysitm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.aizwys.cn/Article/details/gt2pfbvevvt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.guowangkeji.top/Article/details/gt2jrxunvod.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.daria6918.cn/Article/details/gt2weroomri.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ijsjguhr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yanxiufei.cn/Article/details/gt2fxbcvxqk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tianlin.xyz/Article/details/gt2xvwfzitz.html

Ruby: a == b
来源：http://dali.c1oappe.top/Article/details/gt2yhejmpfo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj202588.top/Article/details/gt2feehnons.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhiwuduotai.top/Article/details/gt2zpywfmht.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.snrcjt.cn/Article/details/gt2avdufoub.html

PHP:  if (empty($x)) {}
来源：http://dali.andypj.xyz/Article/details/gt2kixeblqv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.daria6918.cn/Article/details/gt2yiatlpmz.html

TS:   if (x == null) {}
来源：http://dali.jqgfzy.top/Article/details/gt2gllgejwh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2fczsvcpf.html

Go:   if x == nil {}
来源：http://dali.zhongyouzk.top/Article/details/gt2gxhwruqp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xlskiokm.html

C#:   if (x is null) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ssseqfzj.html

[P07] 防抖与节流
来源：http://dali.hfpthk.cn/Article/details/gt2wrioeifn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj20258888.top/Article/details/gt2wurmwaxd.html

PHP:  // 手写时间戳比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ojhwgbos.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gt2xezkxsfh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zroalube.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zycfv.cn/Article/details/gt2iowtvlqs.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gotoacloud.top/Article/details/gt2tmrjjiwi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.mhx1999.top/Article/details/gt2iqlrswow.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jlsjyb.cn/Article/details/gt2rhbhdmry.html

[P08] 处理浮点精度问题
来源：http://dali.yuxming.cn/Article/details/gt2ugznjfng.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dfsiauiz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hywenlv.cn/Article/details/gt2wxgqetks.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yanxiufei.cn/Article/details/gt2oiimcykb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2winlethg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.pycfn.com/Article/details/gt2iuazgulc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hthdlkxr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jqgufenzy.top/Article/details/gt2auhcscfh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.wangshuangyany.cn/Article/details/gt2tzbkgfha.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2ifzkamew.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ovzkyyzk.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2rmvygewr.html

[Q01] 创建表
来源：http://dali.mhx1999.top/Article/details/gt2nceojiym.html

CREATE TABLE users (
来源：http://dali.xuanzx.com/Article/details/gt2sbdvngmm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daxiang520.top/Article/details/gt2hqxonuch.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ppjwa.cn/Article/details/gt2lodcdtsi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.kuanghao11.cn/Article/details/gt2qbzmupyv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.dianchejie.cn/Article/details/gt2bubdfjzo.html

);
来源：http://dali.tian-w.cn/Article/details/gt2zentjjtz.html

[Q02] 创建带外键的表
来源：http://dali.meibo888.top/Article/details/gt2upgjqwcp.html

CREATE TABLE orders (
来源：http://dali.pycfn.com/Article/details/gt2kfyyilme.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhongyouzk.top/Article/details/gt2iaboawes.html

user_id INT NOT NULL,
来源：http://dali.snrcjt.cn/Article/details/gt2ywbwrtgr.html

amount DECIMAL(10, 2),
来源：http://dali.vqdsnc.cn/Article/details/gt2zdbsykpc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hysaishi.cn/Article/details/gt2kjrhpmoo.html

);
来源：http://dali.jinqigfzy.top/Article/details/gt2fjgvqlha.html

[Q03] 增加列
来源：http://dali.dianchejie.cn/Article/details/gt2tvikfgqq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.iojbl.cn/Article/details/gt2zoirtpfb.html

[Q04] 修改列类型
来源：http://dali.ehwqpu.com/Article/details/gt2odhozyrc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.redwolf501.top/Article/details/gt2xpxrmoaq.html

[Q05] 重命名列
来源：http://dali.gzhubu.top/Article/details/gt2njlbwlkf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rxkpopaq.html

[Q06] 删除列
来源：http://dali.yj202588.top/Article/details/gt2koagtadm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hammf.cn/Article/details/gt2flmbgysp.html

[Q07] 删除表
来源：http://dali.hfpthk.cn/Article/details/gt2litgghnv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.aizwys.cn/Article/details/gt2wefftzxe.html

[Q08] 创建普通索引
来源：http://dali.jianghu66.top/Article/details/gt2hecadnob.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.redwolf501.top/Article/details/gt2bzwhwkxp.html

[Q09] 创建唯一索引
来源：http://dali.ehwqpu.com/Article/details/gt2ubpqhhro.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhixingplan.top/Article/details/gt2mmnrtxpi.html

[Q10] 插入单行
来源：http://dali.yj20258888.top/Article/details/gt2eqlinfap.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lkosgwuc.html

[Q11] 一次插入多行
来源：http://dali.cashguo.top/Article/details/gt2xupusuia.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xuanzx.com/Article/details/gt2kmwismtf.html

[Q12] 插入后取自增 ID
来源：http://dali.smart0.xyz/Article/details/gt2ftcfwkbx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gotoacloud.top/Article/details/gt2ftstvuih.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shuidangran.top/Article/details/gt2fexgewne.html

[Q13] 忽略重复插入
来源：http://dali.gogol.net.cn/Article/details/gt2frrgjanb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.birdmap.top/Article/details/gt2vxifpxna.html

[Q14] 存在则更新（upsert）
来源：http://dali.gzhubu.top/Article/details/gt2vsonlzez.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.svipenyu.cn/Article/details/gt2jastqrnx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tian-w.cn/Article/details/gt2afqvlnfv.html

[Q15] 查询全部
来源：http://dali.xinyue.icu/Article/details/gt2ilsqpwaw.html

SELECT * FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2oqgwiqsd.html

[Q16] 查询指定列
来源：http://dali.0kj1m.cn/Article/details/gt2fsvtilhn.html

SELECT id, name FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2zuullqvu.html

[Q17] 条件查询
来源：http://dali.ppjwa.cn/Article/details/gt2ocrzluda.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj202588.top/Article/details/gt2wbhwbnyr.html

[Q18] 模糊匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2kppbzuac.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.mhx1999.top/Article/details/gt2qjbcqhrv.html

[Q19] 范围查询
来源：http://dali.cheryme.top/Article/details/gt2zyxeycga.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xinyue.icu/Article/details/gt2darhijug.html

[Q20] IN 列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pcjmexyu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xuanzx.com/Article/details/gt2pgfvpdhk.html

[Q21] 空值判断
来源：http://dali.wangdashe.top/Article/details/gt2utyydjmq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.daxiang520.top/Article/details/gt2vjnyrchy.html

[Q22] 排序
来源：http://dali.iojbl.cn/Article/details/gt2uscfjkkh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hfpthk.cn/Article/details/gt2varrritd.html

[Q23] 分页
来源：http://dali.316326.xyz/Article/details/gt2phtoeblh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcltlor.html

[Q24] 去重
来源：http://dali.kuanghao11.cn/Article/details/gt2etarawlq.html

SELECT DISTINCT city FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2umjibrpv.html

[Q25] 只取前 N 条
来源：http://dali.c1oappe.top/Article/details/gt2jzhozxui.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yj20258.top/Article/details/gt2hwjhdlku.html

[Q26] 计数
来源：http://dali.cqqwz.cn/Article/details/gt2tawpksqb.html

SELECT COUNT(*) FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2klgyebgn.html

[Q27] 条件计数
来源：http://dali.ppjwa.cn/Article/details/gt2lbpdhsea.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2vzegoxel.html

[Q28] 求和与平均
来源：http://dali.chenzaomai.com/Article/details/gt2qavljfyw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gt2mjsokdim.html

[Q29] 最大最小值
来源：http://dali.cheryme.top/Article/details/gt2yblsevay.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2xodlrkru.html

[Q30] 分组统计
来源：http://dali.vqdsnc.cn/Article/details/gt2wupisiyz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sxryk.cn/Article/details/gt2oqpsivum.html

[Q31] 分组后过滤
来源：http://dali.xinyue.icu/Article/details/gt2idkkzgjn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ppjwa.cn/Article/details/gt2alnfcjjv.html

[Q32] 分组拼接字符串
来源：http://dali.ydzc1.top/Article/details/gt2qqmwgtkq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gt2lmduiayh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.kuanghao11.cn/Article/details/gt2jmwydupx.html

[Q33] 多列分组
来源：http://dali.meibo888.top/Article/details/gt2xrjngnoh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.guowangkeji.top/Article/details/gt2mbhqwzsx.html

[Q34] 每组取第一条
来源：http://dali.hnxiangtu.top/Article/details/gt2prkayolz.html

SELECT * FROM (
来源：http://dali.hammf.cn/Article/details/gt2psqqzmfc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhiwuduotai.top/Article/details/gt2meckaitq.html

) t WHERE rn = 1;
来源：http://dali.jqgufenzy.top/Article/details/gt2mqckedlk.html

[Q35] 内连接
来源：http://dali.guannengcc.top/Article/details/gt2biyzpogd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ydzc1.top/Article/details/gt2hrgyxsgo.html

[Q36] 左连接
来源：http://dali.0kj1m.cn/Article/details/gt2wzghwyub.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.pengpengdd.cyou/Article/details/gt2cbdblpyr.html

[Q37] 右连接
来源：http://dali.ydzc1.top/Article/details/gt2rrhunbwa.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cheryme.top/Article/details/gt2weuxbpfa.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.wangdashe.top/Article/details/gt2wmgpqlzi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.kuanghao11.cn/Article/details/gt2zzkqjtqb.html

[Q39] 自连接（查上下级）
来源：http://dali.sweek.top/Article/details/gt2rpchlklq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sysykeji.top/Article/details/gt2hcfzmwtx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cdnleiting.top/Article/details/gt2vbpgsjbe.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sysykeji.top/Article/details/gt2rhlxvvnf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yuxming.cn/Article/details/gt2xnlxlpic.html

[Q41] 多表连接
来源：http://dali.dianchejie.cn/Article/details/gt2qnplnhyh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.svipenyu.cn/Article/details/gt2uqtqfbax.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cqqwz.cn/Article/details/gt2hvkpuaxq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sweek.top/Article/details/gt2ytculhhr.html

[Q42] 连接条件附加过滤
来源：http://dali.gaohongyu789.top/Article/details/gt2huyenatp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.guannengcc.top/Article/details/gt2iqqbuftd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ydzc1.top/Article/details/gt2ybthqeka.html

[Q43] 标量子查询
来源：http://dali.zycfv.cn/Article/details/gt2ioanaijl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenlongwang.top/Article/details/gt2znzyiwad.html


<!-- 参考信息 -->