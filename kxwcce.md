代发 wailian999

Java: // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtzgmxzatv.html

Go:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtnlcofbrd.html

Ruby: arr.permutation.to_a
来源：http://dali.gotoacloud.top/Article/details/gtqvgomxqb.html

C#:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gttiehngkc.html

[N09] 栈与队列
来源：http://dali.smart0.xyz/Article/details/gthngaaufx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.fzhhl.top/Article/details/gtgkudcwyd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.bjfxy.top/Article/details/gtxdyjlwvz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj20258.top/Article/details/gtbdzxesdo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinqigufen.top/Article/details/gtckjpveso.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.tianlin.xyz/Article/details/gtufesvquh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.wangdashe.top/Article/details/gtaoetqiyo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.daxiang520.top/Article/details/gtulxbtuyr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.dashuyun.cn/Article/details/gtnxkkzwey.html

[N10] 链表节点定义
来源：http://dali.chenjidiqi.icu/Article/details/gtgechkvvm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hnxiangtu.top/Article/details/gtddxqzijx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tianlin.xyz/Article/details/gtmsfegzgb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yanxiufei.cn/Article/details/gtwwxmwqpt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.wangshuangyany.cn/Article/details/gtnjisaupo.html

Java: class Node { int v; Node next; }
来源：http://dali.jinqigufen.top/Article/details/gtewalyyzm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdqobpfdx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nanxinkj.top/Article/details/gtqokoaaah.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xziqi.cn/Article/details/gtokybxunb.html

[N11] 二叉树中序遍历
来源：http://dali.meibo888.top/Article/details/gtsxsnwzgd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmdyjxuj.html

PHP:  // 手写递归函数
来源：http://dali.hywenlv.cn/Article/details/gtwietuvli.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzptuubgq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guannengcc.top/Article/details/gtosqekcrq.html

Java: // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgcezwwlt.html

Go:   // 手写递归
来源：http://dali.yonumen.top/Article/details/gtawtwaugt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.andypj.xyz/Article/details/gtuptkeade.html

C#:   // 手写递归
来源：http://dali.yuxming.cn/Article/details/gtsaxegpkh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.pycfn.com/Article/details/gtxvxukywz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.feifeiyinyue.top/Article/details/gtrffkofoe.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.wangdashe.top/Article/details/gtzerldiin.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aibaodan.cn/Article/details/gtzrlxpuiu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmnsoxftr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.bjfxy.top/Article/details/gtxnmcseny.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xziqi.cn/Article/details/gtsbxndjvr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xylfe.cn/Article/details/gtfbshlfdq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yangfankeji.com/Article/details/gtmimcaonb.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqdndepot.html

O. 并发与异步
来源：http://dali.cdnleiting.top/Article/details/gtwoecbxai.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtnvmhqajv.html

[O01] 启动一个线程
来源：http://dali.daria6918.cn/Article/details/gtbwnwfxur.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zycfv.cn/Article/details/gtunwprhog.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.mhx1999.top/Article/details/gtzimjchcs.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.redwolf501.top/Article/details/gtfxegtpqh.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gtafcewbxq.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gtaaslhuyi.html

Go:   go f()
来源：http://dali.jqgufenzy.top/Article/details/gtycgbrskf.html

Ruby: Thread.new { f }
来源：http://dali.yangfankeji.com/Article/details/gtiqbmbdyi.html

C#:   Task.Run(() => F());
来源：http://dali.jyoumei.cn/Article/details/gtmtzlaimi.html

[O02] 使用线程池
来源：http://dali.zhengqikj.top/Article/details/gtlquaboqx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yuanzhike.top/Article/details/gtwccrpjfs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cashguo.top/Article/details/gtckqayrtf.html

JS:   // worker_threads 线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjkpzjzao.html

TS:   // worker_threads 线程池
来源：http://dali.sufxvd.cn/Article/details/gtwobmoagm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.meibo888.top/Article/details/gtzkchzqyv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cheryme.top/Article/details/gtgvcrncav.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yvedp.cn/Article/details/gtedhtrlry.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.pengpengdd.cyou/Article/details/gtelsxgzfq.html

[O03] 加锁保护共享数据
来源：http://dali.c1oappe.top/Article/details/gteqsqdfxu.html

Py:   with lock: shared += 1
来源：http://dali.sufxvd.cn/Article/details/gtadldqlkx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.svipenyu.cn/Article/details/gtuhpyaslu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.wangdashe.top/Article/details/gtbohybbpj.html

TS:   // 同 JS
来源：http://dali.hnxiangtu.top/Article/details/gtuougrybu.html

Java: synchronized (this) { shared++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtdzcrmvfd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelflnyid.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ehwqpu.com/Article/details/gtoglatcev.html

C#:   lock (gate) { shared++; }
来源：http://dali.snrcjt.cn/Article/details/gtpbkcohuv.html

[O04] 定义异步函数并等待
来源：http://dali.mhx1999.top/Article/details/gtfluaddkq.html

Py:   async def f():⏎    await g()
来源：http://dali.ydzc1.top/Article/details/gthwcakzhv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cashguo.top/Article/details/gtmrfzanmr.html

JS:   async function f() { await g(); }
来源：http://dali.hammf.cn/Article/details/gtdbyildgd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.daria6918.cn/Article/details/gtcavkmdtd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gaohongyu789.top/Article/details/gtkvlahepu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ehwqpu.com/Article/details/gttqbjxiie.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhoulong.xyz/Article/details/gtfaqljeoa.html

C#:   async Task F() { await G(); }
来源：http://dali.zdqjudy.top/Article/details/gtjggjzgrl.html

[O05] 并发执行并等待全部完成
来源：http://dali.snrcjt.cn/Article/details/gtfbkxstzn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jiagoushi.top/Article/details/gtpfdsuihp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nanxinkj.top/Article/details/gtnphbmogv.html

JS:   await Promise.all(tasks)
来源：http://dali.hnqzz.top/Article/details/gtokyntzgz.html

TS:   await Promise.all(tasks)
来源：http://dali.9152youxi.cn/Article/details/gtbwpqsokj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.daxiang520.top/Article/details/gtabbalegv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hammf.cn/Article/details/gttwkhbtww.html

Ruby: threads.map(&:join)
来源：http://dali.dianchejie.cn/Article/details/gtergujsif.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj20258.top/Article/details/gtqirwtynv.html

[O06] 使用进程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gttncfcpxr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.feifeiyinyue.top/Article/details/gtrdbubmrs.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.redwolf501.top/Article/details/gtotoipatc.html

JS:   // child_process / cluster 模块
来源：http://dali.jinghuilouyu.cn/Article/details/gtqcwwufqr.html

TS:   // child_process / cluster 模块
来源：http://dali.zhixingplan.top/Article/details/gthenlpoaj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenzaomai.com/Article/details/gtgraleget.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jlsjyb.cn/Article/details/gtvmroqufo.html

Ruby: // fork 块
来源：http://dali.jiagoushi.top/Article/details/gtxoamzjik.html

C#:   Parallel.For
来源：http://dali.dashuyun.cn/Article/details/gtxksepvlp.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtxbcgypnx.html

P. 常用工具函数
来源：http://dali.yj20258.top/Article/details/gtmvpfqoic.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtzmmezcfy.html

[P01] 生成 UUID
来源：http://dali.shzxlz.cn/Article/details/gtgqyzbpdm.html

Py:   str(uuid.uuid4())
来源：http://dali.jqgufenzy.top/Article/details/gtytugnigj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ybcxt.top/Article/details/gtvcjvsnje.html

JS:   crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gtfzsnkyhq.html

TS:   crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gtqmzrbiuh.html

Java: UUID.randomUUID().toString()
来源：http://dali.hywenlv.cn/Article/details/gtqeehyshu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.dashuyun.cn/Article/details/gtalztfjbh.html

Ruby: SecureRandom.uuid
来源：http://dali.yanxiufei.cn/Article/details/gtnnrspibv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yonumen.top/Article/details/gtjlnkdxvl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.havefunace.top/Article/details/gtoxbshvwd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.fengsongda.top/Article/details/gtmwuotsxo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sufxvd.cn/Article/details/gtjaxqezxb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.andypj.xyz/Article/details/gtmfawbfcx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shzxlz.cn/Article/details/gtcmuupexu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhixingplan.top/Article/details/gtlkfnxlha.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.fengsongda.top/Article/details/gtidxsroom.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yongpay.top/Article/details/gtrttdjeee.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.9152youxi.cn/Article/details/gtdnqiidjy.html

[P03] 生成短随机字符串
来源：http://dali.daria6918.cn/Article/details/gtkuzpeuwq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sysykeji.top/Article/details/gtnrgblwvk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmnbumod.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gaohongyu789.top/Article/details/gtzcszzehi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ehwqpu.com/Article/details/gtrqmozakm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmiuigsnq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgcblqcgn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ppjwa.cn/Article/details/gtqyoxmdhr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ybcxt.top/Article/details/gtrjrimart.html

[P04] 求长度
来源：http://dali.tian-w.cn/Article/details/gtybjoysvp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nanxinkj.top/Article/details/gtewuelpni.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gtnggucwew.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.iojbl.cn/Article/details/gtbuzvfcsr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenlongwang.top/Article/details/gtxawalmnk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.daria6918.cn/Article/details/gtykvzxpzl.html

Go:   len(arr);  len(m)
来源：http://dali.yuanzhike.top/Article/details/gtsewinoem.html

Ruby: x.length;  x.size
来源：http://dali.nanxinkj.top/Article/details/gtqfbsvyhy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hnxiangtu.top/Article/details/gttmrdrxfl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zdqjudy.top/Article/details/gtoipguiys.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shangyingyoupin.top/Article/details/gtkmeufzuw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.svipenyu.cn/Article/details/gtxzouorpt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hysaishi.cn/Article/details/gtvethnnkx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dianchejie.cn/Article/details/gthphwpaup.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinqigufen.top/Article/details/gtintnjlfe.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xylfe.cn/Article/details/gturgtpqeh.html

Ruby: a == b
来源：http://dali.sweek.top/Article/details/gtpryfuava.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xylfe.cn/Article/details/gtdsgahrmm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.0kj1m.cn/Article/details/gtfixghwvx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hywenlv.cn/Article/details/gtuoefzejs.html

PHP:  if (empty($x)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtvraxbhjx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.iojbl.cn/Article/details/gtrumjsqey.html

TS:   if (x == null) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtqeedpbqm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zdqjudy.top/Article/details/gtjpsquibs.html

Go:   if x == nil {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsodzlbbc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.andypj.xyz/Article/details/gtcdokvmvz.html

C#:   if (x is null) {}
来源：http://dali.ivvv.top/Article/details/gtcnlklbvu.html

[P07] 防抖与节流
来源：http://dali.dashuyun.cn/Article/details/gttqgaymzk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yongpay.top/Article/details/gtguekythp.html

PHP:  // 手写时间戳比较
来源：http://dali.yj202588.top/Article/details/gtcmjcvsfy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gtxihekvas.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gtegayfblu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.vqdsnc.cn/Article/details/gtaywjxuby.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.pengpengdd.cyou/Article/details/gtzqunnofz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yanxiufei.cn/Article/details/gtxzuqohxn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yueranfly.top/Article/details/gtpgugmrrv.html

[P08] 处理浮点精度问题
来源：http://dali.aizwys.cn/Article/details/gteqbznzgw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinqigfzy.top/Article/details/gteltoxmta.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hywenlv.cn/Article/details/gtmixaujei.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shuidangran.top/Article/details/gtanvufqte.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.iojbl.cn/Article/details/gttfkllidp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.quarkkingdee.top/Article/details/gtqzqojvft.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhaomingkeji.xyz/Article/details/gtscqgutwo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.svipenyu.cn/Article/details/gtggwmfdqd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gtyuasuyed.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtywqnezhs.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.kuanghao11.cn/Article/details/gtlcmdwmfu.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtorxmtacw.html

[Q01] 创建表
来源：http://dali.yj202588.top/Article/details/gtgupfnqbb.html

CREATE TABLE users (
来源：http://dali.yongpay.top/Article/details/gtioqbxopi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gotoacloud.top/Article/details/gtagiksjwb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.dashuyun.cn/Article/details/gttfmmxrcp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.bjfxy.top/Article/details/gtnketcpyj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.wangshuangyany.cn/Article/details/gtpsdsmbey.html

);
来源：http://dali.xylfe.cn/Article/details/gthdtycqbt.html

[Q02] 创建带外键的表
来源：http://dali.jinqigfzy.top/Article/details/gtmjzrciig.html

CREATE TABLE orders (
来源：http://dali.daria6918.cn/Article/details/gttqrvzzwo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aizwys.cn/Article/details/gtwbbtfgkx.html

user_id INT NOT NULL,
来源：http://dali.jlsjyb.cn/Article/details/gtubkesyoy.html

amount DECIMAL(10, 2),
来源：http://dali.hammf.cn/Article/details/gtasosqmbc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gaohongyu789.top/Article/details/gtrucvkhed.html

);
来源：http://dali.quarkkingdee.top/Article/details/gtgmmeleie.html

[Q03] 增加列
来源：http://dali.sysykeji.top/Article/details/gtqtbckpso.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pycfn.com/Article/details/gtsqgnkslt.html

[Q04] 修改列类型
来源：http://dali.cheryme.top/Article/details/gtvkwoipjy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xziqi.cn/Article/details/gtaztfphqb.html

[Q05] 重命名列
来源：http://dali.chenjidiqi.icu/Article/details/gtbnkybtvs.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hongshengwenyu.top/Article/details/gtkkerwrjk.html

[Q06] 删除列
来源：http://dali.jqgfzy.top/Article/details/gtbxyppuqk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.guowangkeji.top/Article/details/gtmregsrkp.html

[Q07] 删除表
来源：http://dali.gogol.net.cn/Article/details/gtlrabogar.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yongpay.top/Article/details/gtadumyjvt.html

[Q08] 创建普通索引
来源：http://dali.jqgfzy.top/Article/details/gtjsfxxhol.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yanxiufei.cn/Article/details/gtflrkonnf.html

[Q09] 创建唯一索引
来源：http://dali.yueranfly.top/Article/details/gtekxcajrd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sysykeji.top/Article/details/gtkpnqfbfz.html

[Q10] 插入单行
来源：http://dali.jinqigfzy.top/Article/details/gtxocqgwfp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xziqi.cn/Article/details/gthwjddbnl.html

[Q11] 一次插入多行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkeozzolx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gtdmsyvpfy.html

[Q12] 插入后取自增 ID
来源：http://dali.yuanzhike.top/Article/details/gtfsqikkhq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gotoacloud.top/Article/details/gtxlzoqcol.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yongpay.top/Article/details/gtjzoknenb.html

[Q13] 忽略重复插入
来源：http://dali.jlsjyb.cn/Article/details/gttugxxynk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cqqwz.cn/Article/details/gtjeolvynq.html

[Q14] 存在则更新（upsert）
来源：http://dali.yj202588.top/Article/details/gtsodylwab.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.svipenyu.cn/Article/details/gtwbgwfaoi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jyoumei.cn/Article/details/gtbnsbgrem.html

[Q15] 查询全部
来源：http://dali.jqgfzy.top/Article/details/gtnguwkwcv.html

SELECT * FROM users;
来源：http://dali.pycfn.com/Article/details/gthqyforjd.html

[Q16] 查询指定列
来源：http://dali.yangfankeji.com/Article/details/gtzhsmfvjw.html

SELECT id, name FROM users;
来源：http://dali.c1oappe.top/Article/details/gthhdevkhg.html

[Q17] 条件查询
来源：http://dali.kuanghao11.cn/Article/details/gtekwbbqnk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.birdmap.top/Article/details/gtsrfmvywd.html

[Q18] 模糊匹配
来源：http://dali.tian-w.cn/Article/details/gtofovhjpy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhengqikj.top/Article/details/gtsejjgsqv.html

[Q19] 范围查询
来源：http://dali.316326.xyz/Article/details/gtnjrkecxs.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xylfe.cn/Article/details/gtsedfkevb.html

[Q20] IN 列表
来源：http://dali.gzhubu.top/Article/details/gtjtdgvrlb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cashguo.top/Article/details/gtgzglwskm.html

[Q21] 空值判断
来源：http://dali.zdqjudy.top/Article/details/gtkhhqmjjk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nanxinkj.top/Article/details/gtmjmfpjkr.html

[Q22] 排序
来源：http://dali.cdnleiting.top/Article/details/gtekpsqyli.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.bjfxy.top/Article/details/gtixgcfalf.html

[Q23] 分页
来源：http://dali.xylfe.cn/Article/details/gtblayvnwz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.daria6918.cn/Article/details/gtysorofdn.html

[Q24] 去重
来源：http://dali.hywenlv.cn/Article/details/gtqpagstrx.html

SELECT DISTINCT city FROM users;
来源：http://dali.xziqi.cn/Article/details/gtgbiqiuci.html

[Q25] 只取前 N 条
来源：http://dali.vqdsnc.cn/Article/details/gthvkhebuo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.meibo888.top/Article/details/gtewuvjjnr.html

[Q26] 计数
来源：http://dali.chenjidiqi.icu/Article/details/gtxbsuwiuq.html

SELECT COUNT(*) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtcgwvzvrt.html

[Q27] 条件计数
来源：http://dali.guowangkeji.top/Article/details/gtkuvpdrmd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtszdsfszx.html

[Q28] 求和与平均
来源：http://dali.nwbrower.top/Article/details/gtvanjwftd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sweek.top/Article/details/gtthrqcfmx.html

[Q29] 最大最小值
来源：http://dali.yonumen.top/Article/details/gtgzkzlmid.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtcogwsuwg.html

[Q30] 分组统计
来源：http://dali.snrcjt.cn/Article/details/gtypltrbwd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gtxqhxhtew.html

[Q31] 分组后过滤
来源：http://dali.gzhubu.top/Article/details/gtdhpywabs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sufxvd.cn/Article/details/gtbovtkyyy.html

[Q32] 分组拼接字符串
来源：http://dali.nwbrower.top/Article/details/gtjawnzzgy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gteculshzf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.kuanghao11.cn/Article/details/gtjtkmfios.html

[Q33] 多列分组
来源：http://dali.ydzc1.top/Article/details/gtwsbmyihi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.fengsongda.top/Article/details/gtvgfhwnje.html

[Q34] 每组取第一条
来源：http://dali.pycfn.com/Article/details/gtycleocfp.html

SELECT * FROM (
来源：http://dali.guowangkeji.top/Article/details/gtttyorwuu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nwbrower.top/Article/details/gtxceosxql.html

) t WHERE rn = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtbwtfjbny.html

[Q35] 内连接
来源：http://dali.jlsjyb.cn/Article/details/gtsmnfhdxp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenjidiqi.icu/Article/details/gtjstlypfv.html

[Q36] 左连接
来源：http://dali.fengsongda.top/Article/details/gtinmqyqwp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.mhx1999.top/Article/details/gtunedbsul.html

[Q37] 右连接
来源：http://dali.jianghu66.top/Article/details/gtdrrmggou.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ehwqpu.com/Article/details/gtrrwzmkze.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.pengpengdd.cyou/Article/details/gtfjwxlofw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.andypj.xyz/Article/details/gtklnkijuw.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gtnptbgbgp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.birdmap.top/Article/details/gtszvgwmxp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.dashuyun.cn/Article/details/gtrdrspvcz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xylfe.cn/Article/details/gtpflmmpkw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cashguo.top/Article/details/gtqtivlhjw.html

[Q41] 多表连接
来源：http://dali.zhixingplan.top/Article/details/gteedhvzrr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yueranfly.top/Article/details/gtfkhkumxc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yangfankeji.com/Article/details/gtxwtpseza.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gaohongyu789.top/Article/details/gtxvhrhjwo.html

[Q42] 连接条件附加过滤
来源：http://dali.yuanzhike.top/Article/details/gtoevhvwnz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.meibo888.top/Article/details/gtruocevtv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.0kj1m.cn/Article/details/gtysecdzvm.html

[Q43] 标量子查询
来源：http://dali.guowangkeji.top/Article/details/gtklckwzen.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenjidiqi.icu/Article/details/gtvalxqnak.html

[Q44] IN 子查询
来源：http://dali.jianghu66.top/Article/details/gtsrkenqjv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.aizwys.cn/Article/details/gtnjnmssnk.html

[Q45] EXISTS 判断存在
来源：http://dali.ppjwa.cn/Article/details/gtfcucxmsk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.andypj.xyz/Article/details/gtjxbkmlxi.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtntpmejer.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.0kj1m.cn/Article/details/gtqlomunwc.html

[Q47] 与平均值比较
来源：http://dali.yangfankeji.com/Article/details/gtrhaqjtbh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.316326.xyz/Article/details/gtxwpkdglg.html

[Q48] CTE 公用表表达式
来源：http://dali.guannengcc.top/Article/details/gtowlpnbsv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.dashuyun.cn/Article/details/gtsqtzurgj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhoulong.xyz/Article/details/gtrglocdmd.html

[Q49] 更新单行
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmebslde.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gtmlwoaghj.html

[Q50] 批量更新
来源：http://dali.316326.xyz/Article/details/gtyeytiidd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hysaishi.cn/Article/details/gtmdgjbtvb.html

[Q51] 用子查询更新
来源：http://dali.iojbl.cn/Article/details/gtuimdymod.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jyoumei.cn/Article/details/gtebxohbwp.html

[Q52] 删除指定行
来源：http://dali.yuanzhike.top/Article/details/gtlrjihcoc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hysaishi.cn/Article/details/gtdfnwdvuf.html

[Q53] 按条件删除
来源：http://dali.hongshengwenyu.top/Article/details/gtmpzmdotq.html


<!-- 参考信息 -->