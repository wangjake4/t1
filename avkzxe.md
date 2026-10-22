代发 wailian999

Go:   // 手写 map[int]int
来源：http://dali.wangdashe.top/Article/details/gt2qemioxpn.html

Ruby: // 手写 Hash
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pyedbjnp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuetiantiany.cn/Article/details/gt2mqnplqsj.html

[N08] 生成全排列
来源：http://dali.yonumen.top/Article/details/gt2isjjhvsc.html

Py:   itertools.permutations(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2rfabolyh.html

PHP:  // 手写递归交换
来源：http://dali.gotoacloud.top/Article/details/gt2rebiztwi.html

JS:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gt2rokbmqwi.html

TS:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gt2hxqydwag.html

Java: // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gt2eyuuutpv.html

Go:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gt2oehkktst.html

Ruby: arr.permutation.to_a
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sajkcgkt.html

C#:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gt2aelzuxrt.html

[N09] 栈与队列
来源：http://dali.cdnleiting.top/Article/details/gt2qakhujue.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gotoacloud.top/Article/details/gt2ajnvloye.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2xvezfinf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gt2pdjcfkuf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sweek.top/Article/details/gt2gmqoqyvn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.fengsongda.top/Article/details/gt2ndvjklwa.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cdnleiting.top/Article/details/gt2koewlrnn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xinyue.icu/Article/details/gt2wkiweyah.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yonumen.top/Article/details/gt2dwvxyhxd.html

[N10] 链表节点定义
来源：http://dali.xuetiantiany.cn/Article/details/gt2cryiugjv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.kuanghao11.cn/Article/details/gt2rgnfosqj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj20258888.top/Article/details/gt2cpmsmukk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.nanxinkj.top/Article/details/gt2elwppbzj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sweek.top/Article/details/gt2ayspgytd.html

Java: class Node { int v; Node next; }
来源：http://dali.ehwqpu.com/Article/details/gt2umidpacw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yueranfly.top/Article/details/gt2bpfbugik.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hnqzz.top/Article/details/gt2zqqxjmop.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhongyouzk.top/Article/details/gt2dwukqzgy.html

[N11] 二叉树中序遍历
来源：http://dali.sxryk.cn/Article/details/gt2oiletcwx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dpvcbjnx.html

PHP:  // 手写递归函数
来源：http://dali.havefunace.top/Article/details/gt2jpwarqkn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.316326.xyz/Article/details/gt2sonzmkyk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yanxiufei.cn/Article/details/gt2lagxehwk.html

Java: // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tioqnhru.html

Go:   // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zdyfyhmb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.kuanghao11.cn/Article/details/gt2glcufbap.html

C#:   // 手写递归
来源：http://dali.fengsongda.top/Article/details/gt2ubybqzon.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hnqzz.top/Article/details/gt2ssntjgay.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhiwuduotai.top/Article/details/gt2futcenje.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.tanke756.top/Article/details/gt2ohmzzath.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gt2rldonnqi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnxiangtu.top/Article/details/gt2cbvgmpot.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.havefunace.top/Article/details/gt2iyfdakap.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yangfankeji.com/Article/details/gt2uajotabq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.meibo888.top/Article/details/gt2notpnmhi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhongyouzk.top/Article/details/gt2cztyfauq.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2iansynkq.html

O. 并发与异步
来源：http://dali.jiagoushi.top/Article/details/gt2khgedsgs.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2zxkctmlt.html

[O01] 启动一个线程
来源：http://dali.vqdsnc.cn/Article/details/gt2ypywgfeo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.pengpengdd.cyou/Article/details/gt2sgmxvdfi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bwbjxdmj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gogol.net.cn/Article/details/gt2tlddecil.html

TS:   // 同 JS
来源：http://dali.wangdashe.top/Article/details/gt2mjnboecp.html

Java: new Thread(() -> f()).start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2msxikoyy.html

Go:   go f()
来源：http://dali.ydzc1.top/Article/details/gt2lcaylosu.html

Ruby: Thread.new { f }
来源：http://dali.vqdsnc.cn/Article/details/gt2oiygvqys.html

C#:   Task.Run(() => F());
来源：http://dali.shanyushiyangtech.top/Article/details/gt2refoyaco.html

[O02] 使用线程池
来源：http://dali.zhiwuduotai.top/Article/details/gt2hxyugrqm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhengqikj.top/Article/details/gt2agdxioqj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hywenlv.cn/Article/details/gt2ikhgjzac.html

JS:   // worker_threads 线程池
来源：http://dali.andypj.xyz/Article/details/gt2yhxajret.html

TS:   // worker_threads 线程池
来源：http://dali.hnqzz.top/Article/details/gt2fogvenpf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.daria6918.cn/Article/details/gt2lxopupza.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.0kj1m.cn/Article/details/gt2nsrnzxcn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cashguo.top/Article/details/gt2uuvwwkcc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ppjwa.cn/Article/details/gt2dnuldhhq.html

[O03] 加锁保护共享数据
来源：http://dali.gotoacloud.top/Article/details/gt2fvdfxoue.html

Py:   with lock: shared += 1
来源：http://dali.hammf.cn/Article/details/gt2qieqopnz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.aizwys.cn/Article/details/gt2vcxfpkbt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.wangdashe.top/Article/details/gt2axiohvak.html

TS:   // 同 JS
来源：http://dali.hnqzz.top/Article/details/gt2bbmyypfo.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ectpzrnk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gzhubu.top/Article/details/gt2kitnqdjb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2swwgrmlw.html

C#:   lock (gate) { shared++; }
来源：http://dali.sxryk.cn/Article/details/gt2jzmwwpiw.html

[O04] 定义异步函数并等待
来源：http://dali.hnxiangtu.top/Article/details/gt2eavbmyrz.html

Py:   async def f():⏎    await g()
来源：http://dali.aizwys.cn/Article/details/gt2rysuwura.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.havefunace.top/Article/details/gt2rnmcanua.html

JS:   async function f() { await g(); }
来源：http://dali.tianlin.xyz/Article/details/gt2rauhydfh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gt2obskfzrh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jyoumei.cn/Article/details/gt2xepbjulu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xylfe.cn/Article/details/gt2rknfpimt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jiagoushi.top/Article/details/gt2ecnobfsq.html

C#:   async Task F() { await G(); }
来源：http://dali.jyoumei.cn/Article/details/gt2yeyzhaoi.html

[O05] 并发执行并等待全部完成
来源：http://dali.jyoumei.cn/Article/details/gt2npqkvcpi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.pycfn.com/Article/details/gt2vagegtfy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gotoacloud.top/Article/details/gt2ydcwqkcz.html

JS:   await Promise.all(tasks)
来源：http://dali.cheryme.top/Article/details/gt2khyoqivk.html

TS:   await Promise.all(tasks)
来源：http://dali.jlsjyb.cn/Article/details/gt2civcrmvy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tianlin.xyz/Article/details/gt2jdxjcris.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hywenlv.cn/Article/details/gt2kyesmhbk.html

Ruby: threads.map(&:join)
来源：http://dali.cheryme.top/Article/details/gt2fznqccqr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cashguo.top/Article/details/gt2nenpzfaw.html

[O06] 使用进程池
来源：http://dali.sufxvd.cn/Article/details/gt2yggjvxjs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fzhhl.top/Article/details/gt2lnxrimwt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yj20258.top/Article/details/gt2cudccrrb.html

JS:   // child_process / cluster 模块
来源：http://dali.pycfn.com/Article/details/gt2fhhqazkh.html

TS:   // child_process / cluster 模块
来源：http://dali.feifeiyinyue.top/Article/details/gt2ejquukmg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.pengpengdd.cyou/Article/details/gt2jrahiems.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.wangshuangyany.cn/Article/details/gt2iedssmxx.html

Ruby: // fork 块
来源：http://dali.hnxiangtu.top/Article/details/gt2mjgbqnoj.html

C#:   Parallel.For
来源：http://dali.redwolf501.top/Article/details/gt2srvchqbh.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2dfieladf.html

P. 常用工具函数
来源：http://dali.yueranfly.top/Article/details/gt2qjyebzvn.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2waotghsh.html

[P01] 生成 UUID
来源：http://dali.cashguo.top/Article/details/gt2hpjzpvxh.html

Py:   str(uuid.uuid4())
来源：http://dali.zycfv.cn/Article/details/gt2vehwuree.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hysaishi.cn/Article/details/gt2cardsgnp.html

JS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gt2ecwivady.html

TS:   crypto.randomUUID()
来源：http://dali.dianchejie.cn/Article/details/gt2wbflkhbp.html

Java: UUID.randomUUID().toString()
来源：http://dali.9152youxi.cn/Article/details/gt2slwaxbzf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yueranfly.top/Article/details/gt2bevalvdw.html

Ruby: SecureRandom.uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2exgyexry.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xziqi.cn/Article/details/gt2gbzvopzt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.feifeiyinyue.top/Article/details/gt2lrvjegqb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cqqwz.cn/Article/details/gt2exkwtgrx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.birdmap.top/Article/details/gt2bzidxtsx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hnqzz.top/Article/details/gt2sendekyg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ydzc1.top/Article/details/gt2aqxmxpsg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hnqzz.top/Article/details/gt2svwcskpe.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sysykeji.top/Article/details/gt2ynoluadd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2rrigkqmd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.c1oappe.top/Article/details/gt2okdhvnnm.html

[P03] 生成短随机字符串
来源：http://dali.cdnleiting.top/Article/details/gt2oeffeqkj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tianlin.xyz/Article/details/gt2kwnvqenm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jianghu66.top/Article/details/gt2agdkzpge.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.smart0.xyz/Article/details/gt2teqytnrh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2jurlkrgn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ybcxt.top/Article/details/gt2aalfyiwg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shangyingyoupin.top/Article/details/gt2arpuliml.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qhrpfsib.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hammf.cn/Article/details/gt2mazznlrf.html

[P04] 求长度
来源：http://dali.sweek.top/Article/details/gt2bjalbhyr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sufxvd.cn/Article/details/gt2qlefeycz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gt2fkqwgrgi.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ybcxt.top/Article/details/gt2mbfeurko.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.0kj1m.cn/Article/details/gt2gxxknmgn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhixingplan.top/Article/details/gt2xgnavems.html

Go:   len(arr);  len(m)
来源：http://dali.yj20258888.top/Article/details/gt2erfzzuwr.html

Ruby: x.length;  x.size
来源：http://dali.yongpay.top/Article/details/gt2pjyptuee.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.smart0.xyz/Article/details/gt2dbszdgpo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhoulong.xyz/Article/details/gt2fshndwhm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwfxuft.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cucudq.cn/Article/details/gt2ithbrfnc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.nwbrower.top/Article/details/gt2nofxzlpd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnxiangtu.top/Article/details/gt2xwvvioib.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.0kj1m.cn/Article/details/gt2iluulrww.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gt2mzvbbntx.html

Ruby: a == b
来源：http://dali.zhongyouzk.top/Article/details/gt2pnjzigcu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.0kj1m.cn/Article/details/gt2fxjypixc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2deykidla.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.0kj1m.cn/Article/details/gt2vqnwracm.html

PHP:  if (empty($x)) {}
来源：http://dali.yueranfly.top/Article/details/gt2nlrrwxcd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xziqi.cn/Article/details/gt2gypckuts.html

TS:   if (x == null) {}
来源：http://dali.ydzc1.top/Article/details/gt2azkfqmms.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.meibo888.top/Article/details/gt2qcklgcsl.html

Go:   if x == nil {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2zdufmrbr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nanxinkj.top/Article/details/gt2rammwwec.html

C#:   if (x is null) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2teidjmgb.html

[P07] 防抖与节流
来源：http://dali.xinyue.icu/Article/details/gt2jwtfznzh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xuanzx.com/Article/details/gt2yutacevd.html

PHP:  // 手写时间戳比较
来源：http://dali.ehwqpu.com/Article/details/gt2ijavvbih.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gogol.net.cn/Article/details/gt2luqyleyp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.birdmap.top/Article/details/gt2oeddffdy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2xzwxktow.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhongyouzk.top/Article/details/gt2pqkwvojk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yvedp.cn/Article/details/gt2vgotprbg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.guowangkeji.top/Article/details/gt2qibzvugs.html

[P08] 处理浮点精度问题
来源：http://dali.daria6918.cn/Article/details/gt2fxzliwnf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hnxiangtu.top/Article/details/gt2hbwxlcjr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yangfankeji.com/Article/details/gt2yfssxaxx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.iojbl.cn/Article/details/gt2rzoogicr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yvedp.cn/Article/details/gt2oecqdfpg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.quarkkingdee.top/Article/details/gt2wummosmd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ehwqpu.com/Article/details/gt2bbkiazhu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.andypj.xyz/Article/details/gt2xxeiclda.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cdnleiting.top/Article/details/gt2scmhteiw.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2ofmhjent.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sysykeji.top/Article/details/gt2zuanqjew.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2qpjfovpy.html

[Q01] 创建表
来源：http://dali.andypj.xyz/Article/details/gt2htksrjrd.html

CREATE TABLE users (
来源：http://dali.feifeiyinyue.top/Article/details/gt2bnksfixy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dashuyun.cn/Article/details/gt2gscjebpg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zycfv.cn/Article/details/gt2ztqjurnp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinghuilouyu.cn/Article/details/gt2drwmtrrn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.aibaodan.cn/Article/details/gt2uciyssgp.html

);
来源：http://dali.gaohongyu789.top/Article/details/gt2mmvmvstv.html

[Q02] 创建带外键的表
来源：http://dali.wangshuangyany.cn/Article/details/gt2jtofdfgt.html

CREATE TABLE orders (
来源：http://dali.fzhhl.top/Article/details/gt2ugqoyqec.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenzaomai.com/Article/details/gt2dmvonyhg.html

user_id INT NOT NULL,
来源：http://dali.hfpthk.cn/Article/details/gt2azqkkxbo.html

amount DECIMAL(10, 2),
来源：http://dali.redwolf501.top/Article/details/gt2usqnjtct.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenlongwang.top/Article/details/gt2urtgfldm.html

);
来源：http://dali.316326.xyz/Article/details/gt2gvpumxui.html

[Q03] 增加列
来源：http://dali.birdmap.top/Article/details/gt2appdskht.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.c1oappe.top/Article/details/gt2hgohksao.html

[Q04] 修改列类型
来源：http://dali.dianchejie.cn/Article/details/gt2gvpfedyf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yongpay.top/Article/details/gt2gvdgtuug.html

[Q05] 重命名列
来源：http://dali.c1oappe.top/Article/details/gt2ddiyckig.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zycfv.cn/Article/details/gt2sqibdtki.html

[Q06] 删除列
来源：http://dali.gzhubu.top/Article/details/gt2vxcrlbof.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yuxming.cn/Article/details/gt2caimysak.html

[Q07] 删除表
来源：http://dali.ivvv.top/Article/details/gt2oauafeaf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.vqdsnc.cn/Article/details/gt2bgcgeavi.html

[Q08] 创建普通索引
来源：http://dali.meibo888.top/Article/details/gt2kdymnmnp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.nwbrower.top/Article/details/gt2vljeeubv.html

[Q09] 创建唯一索引
来源：http://dali.jqgufenzy.top/Article/details/gt2atdmtwjx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gzhubu.top/Article/details/gt2afanvkoy.html

[Q10] 插入单行
来源：http://dali.cucudq.cn/Article/details/gt2mbpzpfgu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hnqzz.top/Article/details/gt2stgeeigt.html

[Q11] 一次插入多行
来源：http://dali.mhx1999.top/Article/details/gt2tyhtjukm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.daxiang520.top/Article/details/gt2ftntkymn.html

[Q12] 插入后取自增 ID
来源：http://dali.xuanzx.com/Article/details/gt2wvkivyld.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ybcxt.top/Article/details/gt2egrsyylj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nwbrower.top/Article/details/gt2rxopymnn.html

[Q13] 忽略重复插入
来源：http://dali.yueranfly.top/Article/details/gt2swvozrdg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sxryk.cn/Article/details/gt2joqbucqr.html

[Q14] 存在则更新（upsert）
来源：http://dali.shzxlz.cn/Article/details/gt2efckohmo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.dianchejie.cn/Article/details/gt2lzpsckth.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yj20258888.top/Article/details/gt2jurjdehh.html

[Q15] 查询全部
来源：http://dali.mhx1999.top/Article/details/gt2pteaeugb.html

SELECT * FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2rayowaax.html

[Q16] 查询指定列
来源：http://dali.guannengcc.top/Article/details/gt2shgrymja.html

SELECT id, name FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2evjacpbb.html

[Q17] 条件查询
来源：http://dali.jlsjyb.cn/Article/details/gt2pheitdyc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guannengcc.top/Article/details/gt2ywzdsyfv.html

[Q18] 模糊匹配
来源：http://dali.sweek.top/Article/details/gt2mycaqivc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhoulong.xyz/Article/details/gt2tnerdits.html

[Q19] 范围查询
来源：http://dali.birdmap.top/Article/details/gt2ppwpwotr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.aizwys.cn/Article/details/gt2ucgabkor.html

[Q20] IN 列表
来源：http://dali.sxryk.cn/Article/details/gt2wbrptaro.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.havefunace.top/Article/details/gt2hyfkwjpp.html

[Q21] 空值判断
来源：http://dali.tian-w.cn/Article/details/gt2zwkevces.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.fzhhl.top/Article/details/gt2dnivqffh.html

[Q22] 排序
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jvdbxzwp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.nwbrower.top/Article/details/gt2jlikurkm.html

[Q23] 分页
来源：http://dali.tian-w.cn/Article/details/gt2wuoycahd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.9152youxi.cn/Article/details/gt2nexnnwdr.html

[Q24] 去重
来源：http://dali.yongpay.top/Article/details/gt2rrvsjatw.html

SELECT DISTINCT city FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2kyzlepgm.html

[Q25] 只取前 N 条
来源：http://dali.yuxming.cn/Article/details/gt2srlwexco.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zdqjudy.top/Article/details/gt2opajnmim.html

[Q26] 计数
来源：http://dali.ehwqpu.com/Article/details/gt2gpcskndb.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj202588.top/Article/details/gt2tzigckiv.html

[Q27] 条件计数
来源：http://dali.andypj.xyz/Article/details/gt2lhgpwtsz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2sbdjiyvs.html

[Q28] 求和与平均
来源：http://dali.hnqzz.top/Article/details/gt2sudkbibu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gt2ptikgyvp.html

[Q29] 最大最小值
来源：http://dali.zhixingplan.top/Article/details/gt2nonvgltb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2jsljzojc.html

[Q30] 分组统计
来源：http://dali.quarkkingdee.top/Article/details/gt2brrlscvy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jqgfzy.top/Article/details/gt2pftivnit.html

[Q31] 分组后过滤
来源：http://dali.sysykeji.top/Article/details/gt2tejblqlg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.iojbl.cn/Article/details/gt2rombhlrw.html

[Q32] 分组拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gt2iplqtxsg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gt2kvnujxqg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.vqdsnc.cn/Article/details/gt2eozwuacl.html

[Q33] 多列分组
来源：http://dali.dianchejie.cn/Article/details/gt2kgwukzzn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vsnhbtgo.html

[Q34] 每组取第一条
来源：http://dali.shzxlz.cn/Article/details/gt2kaplvvbr.html

SELECT * FROM (
来源：http://dali.birdmap.top/Article/details/gt2dgpzeuag.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.aizwys.cn/Article/details/gt2kjcyebxo.html

) t WHERE rn = 1;
来源：http://dali.hnqzz.top/Article/details/gt2rdhpmnjs.html

[Q35] 内连接
来源：http://dali.meibo888.top/Article/details/gt2okxgknsp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258888.top/Article/details/gt2fldwzlec.html

[Q36] 左连接
来源：http://dali.aibaodan.cn/Article/details/gt2bhimpsnr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hywenlv.cn/Article/details/gt2vdrqnhrd.html

[Q37] 右连接
来源：http://dali.mhx1999.top/Article/details/gt2inmgqjpz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.9152youxi.cn/Article/details/gt2pltaqmge.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnxiangtu.top/Article/details/gt2clrmzyeg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shangyingyoupin.top/Article/details/gt2vljraucw.html

[Q39] 自连接（查上下级）
来源：http://dali.yueranfly.top/Article/details/gt2dfkodslc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenjidiqi.icu/Article/details/gt2ypmdlhbd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hammf.cn/Article/details/gt2evplytwa.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhengqikj.top/Article/details/gt2wdfoqmdl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.bjfxy.top/Article/details/gt2hwmrlmei.html

[Q41] 多表连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vwubgzlp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2erjspwbi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yvedp.cn/Article/details/gt2xzwpumgk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.daxiang520.top/Article/details/gt2ugaqpgev.html

[Q42] 连接条件附加过滤
来源：http://dali.aizwys.cn/Article/details/gt2vrzwkfmb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hammf.cn/Article/details/gt2wzhuprut.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ehwqpu.com/Article/details/gt2ymuwpvsq.html

[Q43] 标量子查询
来源：http://dali.wangdashe.top/Article/details/gt2zoruhlvh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yuxming.cn/Article/details/gt2emzxrsrc.html

[Q44] IN 子查询
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kvkwyptj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hfpthk.cn/Article/details/gt2phrnjkow.html

[Q45] EXISTS 判断存在
来源：http://dali.nanxuanxn.top/Article/details/gt2omotfcha.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangdashe.top/Article/details/gt2ebyfdozy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tanke756.top/Article/details/gt2atqhiyrh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shangyingyoupin.top/Article/details/gt2rqgqgxet.html

[Q47] 与平均值比较
来源：http://dali.jianghu66.top/Article/details/gt2qfxfmkoq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.quarkkingdee.top/Article/details/gt2hagmosqw.html

[Q48] CTE 公用表表达式
来源：http://dali.shuidangran.top/Article/details/gt2ffmqgark.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nanxuanxn.top/Article/details/gt2vrkujkub.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.tian-w.cn/Article/details/gt2wflmqyau.html

[Q49] 更新单行
来源：http://dali.haohaochexian.top/Article/details/gt2eglmmcbm.html


<!-- 参考信息 -->