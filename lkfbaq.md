代发 wailian999

Ruby: s == s.reverse
来源：http://dali.0kj1m.cn/Article/details/gtpxdvgyqp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hongshengwenyu.top/Article/details/gtrsssabis.html

[N07] 两数之和（返回下标）
来源：http://dali.xuanzx.com/Article/details/gtcdhfltfp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hammf.cn/Article/details/gtddajeadp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.pycfn.com/Article/details/gtldrljqmn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinqigufen.top/Article/details/gtyleqtzpb.html

TS:   // 手写 Map<string, number>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjmwzwgk.html

Java: // 手写 HashMap
来源：http://dali.yj202588.top/Article/details/gtgpjzplzf.html

Go:   // 手写 map[int]int
来源：http://dali.gzhubu.top/Article/details/gtifxprcdw.html

Ruby: // 手写 Hash
来源：http://dali.pycfn.com/Article/details/gtwoshsrfp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhongyouzk.top/Article/details/gtnscdslhw.html

[N08] 生成全排列
来源：http://dali.cucudq.cn/Article/details/gthtbeytkh.html

Py:   itertools.permutations(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtdinzjjqx.html

PHP:  // 手写递归交换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhxyrpze.html

JS:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtyeaeamgu.html

TS:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtslscimvb.html

Java: // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtcmuvdpwv.html

Go:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtsaocnscw.html

Ruby: arr.permutation.to_a
来源：http://dali.chenzaomai.com/Article/details/gtnpvwvamk.html

C#:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gtizofmzzn.html

[N09] 栈与队列
来源：http://dali.gzhubu.top/Article/details/gtuiisuwmr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxjvktvf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gtvenffowi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.havefunace.top/Article/details/gtmpkanxpj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gzhubu.top/Article/details/gtdyzthzkd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xylfe.cn/Article/details/gtozninpje.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gotoacloud.top/Article/details/gtuguvedli.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gtzcltjtnw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hnqzz.top/Article/details/gtvwqpmral.html

[N10] 链表节点定义
来源：http://dali.yongpay.top/Article/details/gtxyiypbqj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gaohongyu789.top/Article/details/gtrqupwezb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gotoacloud.top/Article/details/gtftwrxobq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjmpvlxl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tian-w.cn/Article/details/gtpoqfeytq.html

Java: class Node { int v; Node next; }
来源：http://dali.nanxinkj.top/Article/details/gtwbvdoitv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cashguo.top/Article/details/gtnrtmcquy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.pycfn.com/Article/details/gtxcuuqswr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenjidiqi.icu/Article/details/gtjblzdusj.html

[N11] 二叉树中序遍历
来源：http://dali.tanke756.top/Article/details/gtpxkwwuca.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.pycfn.com/Article/details/gtumzmxqqs.html

PHP:  // 手写递归函数
来源：http://dali.zycfv.cn/Article/details/gtchjcormy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guannengcc.top/Article/details/gtqctnxmcs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dianchejie.cn/Article/details/gtlkzjwkbg.html

Java: // 手写递归
来源：http://dali.hnxiangtu.top/Article/details/gtanbdhjlo.html

Go:   // 手写递归
来源：http://dali.smart0.xyz/Article/details/gtvjnsvnsr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cucudq.cn/Article/details/gtvdltvrwo.html

C#:   // 手写递归
来源：http://dali.cucudq.cn/Article/details/gtzvqmbkcs.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj202588.top/Article/details/gtjkrfvucv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yanxiufei.cn/Article/details/gtclckilsh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shangyingyoupin.top/Article/details/gtclkqjdmn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenlongwang.top/Article/details/gtxapcmdok.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxuanxn.top/Article/details/gtpbpkvhqw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinghuilouyu.cn/Article/details/gtntdimdti.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sufxvd.cn/Article/details/gtglvcclpn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nwbrower.top/Article/details/gtgftyuwfn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yueranfly.top/Article/details/gtbddtctoc.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gthalmutfv.html

O. 并发与异步
来源：http://dali.yj202588.top/Article/details/gtzjlbjbpn.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtrlrhmnvh.html

[O01] 启动一个线程
来源：http://dali.yanxiufei.cn/Article/details/gtrthzqcid.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.redwolf501.top/Article/details/gtqxxvpaxl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.mhx1999.top/Article/details/gthyoywmgi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tian-w.cn/Article/details/gtbrxjlyhg.html

TS:   // 同 JS
来源：http://dali.jyoumei.cn/Article/details/gtxgtiipwk.html

Java: new Thread(() -> f()).start()
来源：http://dali.zycfv.cn/Article/details/gtnafkqksn.html

Go:   go f()
来源：http://dali.ehwqpu.com/Article/details/gthbdwankn.html

Ruby: Thread.new { f }
来源：http://dali.meibo888.top/Article/details/gtevnnpjap.html

C#:   Task.Run(() => F());
来源：http://dali.hnxiangtu.top/Article/details/gthubusciz.html

[O02] 使用线程池
来源：http://dali.yueranfly.top/Article/details/gtppigloos.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.316326.xyz/Article/details/gttizezxcb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.snrcjt.cn/Article/details/gtxqgsghvs.html

JS:   // worker_threads 线程池
来源：http://dali.hnxiangtu.top/Article/details/gtrkuqgpgk.html

TS:   // worker_threads 线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzvtpqwds.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.daxiang520.top/Article/details/gtqdfehwth.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.bjfxy.top/Article/details/gtfffzzbyr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.mhx1999.top/Article/details/gtqmseumvq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xuetiantiany.cn/Article/details/gtdlmmfyww.html

[O03] 加锁保护共享数据
来源：http://dali.zhoulong.xyz/Article/details/gtbyerstqu.html

Py:   with lock: shared += 1
来源：http://dali.xinyue.icu/Article/details/gttazjxhqs.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hywenlv.cn/Article/details/gtydgnvabd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zycfv.cn/Article/details/gtwmbyxapu.html

TS:   // 同 JS
来源：http://dali.hysaishi.cn/Article/details/gtpekcnewv.html

Java: synchronized (this) { shared++; }
来源：http://dali.birdmap.top/Article/details/gtlxonpblz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hysaishi.cn/Article/details/gtbceackqf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.pycfn.com/Article/details/gtclyrbjvu.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj20258.top/Article/details/gtdsdpdlmg.html

[O04] 定义异步函数并等待
来源：http://dali.hfpthk.cn/Article/details/gtkuhhcprv.html

Py:   async def f():⏎    await g()
来源：http://dali.jyoumei.cn/Article/details/gtqvhqmrtj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cdnleiting.top/Article/details/gtpjkzsxky.html

JS:   async function f() { await g(); }
来源：http://dali.xinyue.icu/Article/details/gtgvaxxbqa.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.fengsongda.top/Article/details/gtphskjtyk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmfietfqp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hammf.cn/Article/details/gtjurjmwrx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.9152youxi.cn/Article/details/gtdbwsrrxp.html

C#:   async Task F() { await G(); }
来源：http://dali.svipenyu.cn/Article/details/gtxvsemxfu.html

[O05] 并发执行并等待全部完成
来源：http://dali.gotoacloud.top/Article/details/gtkfzcvfrq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgufenzy.top/Article/details/gtcujowiyk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yvedp.cn/Article/details/gtkqmluwnw.html

JS:   await Promise.all(tasks)
来源：http://dali.tianlin.xyz/Article/details/gtwfhentwi.html

TS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gtyvidskbh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nanxinkj.top/Article/details/gttlfjtskn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hnxiangtu.top/Article/details/gtgkyoovvx.html

Ruby: threads.map(&:join)
来源：http://dali.shangyingyoupin.top/Article/details/gtbbpzglck.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jqgfzy.top/Article/details/gtmitfcafy.html

[O06] 使用进程池
来源：http://dali.ivvv.top/Article/details/gtkhlbfivm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.smart0.xyz/Article/details/gtdnhznhio.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hongshengwenyu.top/Article/details/gtkiociuxg.html

JS:   // child_process / cluster 模块
来源：http://dali.yj20258.top/Article/details/gtznnvgwkf.html

TS:   // child_process / cluster 模块
来源：http://dali.0kj1m.cn/Article/details/gtpufqottd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cdnleiting.top/Article/details/gtglohwhnx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gzhubu.top/Article/details/gtzbjdaizy.html

Ruby: // fork 块
来源：http://dali.zycfv.cn/Article/details/gtncubrgsq.html

C#:   Parallel.For
来源：http://dali.shzxlz.cn/Article/details/gtfxzphydy.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gttwuvbpvj.html

P. 常用工具函数
来源：http://dali.fzhhl.top/Article/details/gtfkfguewy.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtgiskmtqm.html

[P01] 生成 UUID
来源：http://dali.iojbl.cn/Article/details/gtpghginjp.html

Py:   str(uuid.uuid4())
来源：http://dali.kuanghao11.cn/Article/details/gtparpuwav.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jianghu66.top/Article/details/gtbhjufpmg.html

JS:   crypto.randomUUID()
来源：http://dali.cdnleiting.top/Article/details/gtkdbcdwbi.html

TS:   crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gtlihpaoqj.html

Java: UUID.randomUUID().toString()
来源：http://dali.tianlin.xyz/Article/details/gtlsbcomup.html

Go:   // 用 github.com/google/uuid
来源：http://dali.havefunace.top/Article/details/gtvdfzeruc.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gtkotpmemf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrztnxafo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hfpthk.cn/Article/details/gtbbsmtvqt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shanyushiyangtech.top/Article/details/gtksutzokm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cqqwz.cn/Article/details/gtwnhkoqln.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cheryme.top/Article/details/gtipdizoil.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.fengsongda.top/Article/details/gtoyhmqpye.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ydzc1.top/Article/details/gtcwaldxax.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yonumen.top/Article/details/gtprhvvywi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.9152youxi.cn/Article/details/gtbnbcufel.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenzaomai.com/Article/details/gtuwmhkmqx.html

[P03] 生成短随机字符串
来源：http://dali.xinyue.icu/Article/details/gtruoryojo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cucudq.cn/Article/details/gturueoyeb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.aizwys.cn/Article/details/gtmxlqsfgf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yvedp.cn/Article/details/gtxuxrngbe.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yonumen.top/Article/details/gtodzyoasb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.c1oappe.top/Article/details/gtreatfpsm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.mhx1999.top/Article/details/gtevnykpxn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.birdmap.top/Article/details/gtsnybtaeh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yueranfly.top/Article/details/gtiawrivzq.html

[P04] 求长度
来源：http://dali.yongpay.top/Article/details/gtqxgaxnxp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sysykeji.top/Article/details/gtgovnlcnq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzdshujr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenlongwang.top/Article/details/gttlzntfua.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yangfankeji.com/Article/details/gturogynrw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jqgfzy.top/Article/details/gtryxugjiw.html

Go:   len(arr);  len(m)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedhpcbqa.html

Ruby: x.length;  x.size
来源：http://dali.shanyushiyangtech.top/Article/details/gtgqlfcsgq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.daria6918.cn/Article/details/gtsfoqqway.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yuanzhike.top/Article/details/gtazfghrqw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jlsjyb.cn/Article/details/gtfwwypsic.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.guowangkeji.top/Article/details/gttgwdtwke.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.pycfn.com/Article/details/gtlmbjzcum.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shuidangran.top/Article/details/gtkrpqnihx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hywenlv.cn/Article/details/gtscbrgsey.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zdqjudy.top/Article/details/gtkytwoyqm.html

Ruby: a == b
来源：http://dali.dashuyun.cn/Article/details/gtqiugwxou.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xylfe.cn/Article/details/gtmikfujyt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yuxming.cn/Article/details/gtxktqthko.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhixingplan.top/Article/details/gtzrztfjhx.html

PHP:  if (empty($x)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtblxwijxj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzdniwfz.html

TS:   if (x == null) {}
来源：http://dali.haohaochexian.top/Article/details/gtunqyawjx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpakknhzk.html

Go:   if x == nil {}
来源：http://dali.ydzc1.top/Article/details/gtpfamstfw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yuanzhike.top/Article/details/gtarahawqy.html

C#:   if (x is null) {}
来源：http://dali.zhongyouzk.top/Article/details/gtmkffjhuy.html

[P07] 防抖与节流
来源：http://dali.tianlin.xyz/Article/details/gtqwebzcon.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ppjwa.cn/Article/details/gtniqcwzec.html

PHP:  // 手写时间戳比较
来源：http://dali.nwbrower.top/Article/details/gtjecffeij.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gtwuteicwz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cheryme.top/Article/details/gtijysypvu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.haohaochexian.top/Article/details/gtrjpirvky.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinghuilouyu.cn/Article/details/gtbejizkgr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.316326.xyz/Article/details/gtyzlqrmbh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ppjwa.cn/Article/details/gtinbxigob.html

[P08] 处理浮点精度问题
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcyjxngll.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.quarkkingdee.top/Article/details/gtqshqwlsa.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.svipenyu.cn/Article/details/gtlxlzkyon.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.guowangkeji.top/Article/details/gthxbkxwjp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrndrmdgv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shangyingyoupin.top/Article/details/gtfbotstcw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenlongwang.top/Article/details/gtkzfnkgjc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmwrsdbjx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxinkj.top/Article/details/gtzrtpgzuj.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtyfpxnjny.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sweek.top/Article/details/gtvaubvbtk.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtcfgroczj.html

[Q01] 创建表
来源：http://dali.yangfankeji.com/Article/details/gttmfxroio.html

CREATE TABLE users (
来源：http://dali.havefunace.top/Article/details/gtxtxqycwt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fzhhl.top/Article/details/gttrdxzadz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shangyingyoupin.top/Article/details/gtprjezyur.html

email VARCHAR(100) UNIQUE,
来源：http://dali.bjfxy.top/Article/details/gtoletfdfm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hongshengwenyu.top/Article/details/gtasxvwexl.html

);
来源：http://dali.ppjwa.cn/Article/details/gtlppkmwvr.html

[Q02] 创建带外键的表
来源：http://dali.zhixingplan.top/Article/details/gtqtnjttij.html

CREATE TABLE orders (
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazrbtbmr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cdnleiting.top/Article/details/gthjkobblh.html

user_id INT NOT NULL,
来源：http://dali.hongshengwenyu.top/Article/details/gtlecynspd.html

amount DECIMAL(10, 2),
来源：http://dali.guannengcc.top/Article/details/gtuxxvlyyv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gogol.net.cn/Article/details/gtgzognvfb.html

);
来源：http://dali.sufxvd.cn/Article/details/gtrsjadoks.html

[Q03] 增加列
来源：http://dali.tanke756.top/Article/details/gteithfnaz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hywenlv.cn/Article/details/gtcoohvvtv.html

[Q04] 修改列类型
来源：http://dali.bjfxy.top/Article/details/gtbvixarqc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yueranfly.top/Article/details/gtavbhxkju.html

[Q05] 重命名列
来源：http://dali.ybcxt.top/Article/details/gtmlehlxkw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yj20258888.top/Article/details/gtyvfnqkpz.html

[Q06] 删除列
来源：http://dali.ydzc1.top/Article/details/gtbsztibjw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zdqjudy.top/Article/details/gtoupaclzc.html

[Q07] 删除表
来源：http://dali.jinghuilouyu.cn/Article/details/gtaeazoyzy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtatuwzijj.html

[Q08] 创建普通索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdycgvec.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtextlnyhj.html

[Q09] 创建唯一索引
来源：http://dali.nanxinkj.top/Article/details/gtubjuradr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hfpthk.cn/Article/details/gtnsffwvhr.html

[Q10] 插入单行
来源：http://dali.hfpthk.cn/Article/details/gtevdkgvbj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gtkdgbvcci.html

[Q11] 一次插入多行
来源：http://dali.ppjwa.cn/Article/details/gtdcliqsnd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hammf.cn/Article/details/gtfhiwrvgw.html

[Q12] 插入后取自增 ID
来源：http://dali.vqdsnc.cn/Article/details/gtrxrqidzw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yanxiufei.cn/Article/details/gtttwxbyay.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jqgfzy.top/Article/details/gtzftbjalq.html

[Q13] 忽略重复插入
来源：http://dali.aibaodan.cn/Article/details/gtuqjtqwzy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhixingplan.top/Article/details/gtnnwfatgq.html

[Q14] 存在则更新（upsert）
来源：http://dali.nwbrower.top/Article/details/gtuxwbhial.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yvedp.cn/Article/details/gtogddzwow.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ydzc1.top/Article/details/gtcpusmsaz.html

[Q15] 查询全部
来源：http://dali.zhoulong.xyz/Article/details/gtpkgprymm.html

SELECT * FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlatejrfr.html

[Q16] 查询指定列
来源：http://dali.zhiwuduotai.top/Article/details/gtqvzwdcjx.html

SELECT id, name FROM users;
来源：http://dali.xziqi.cn/Article/details/gtcjktzjnb.html

[Q17] 条件查询
来源：http://dali.316326.xyz/Article/details/gtbrcoegwi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.svipenyu.cn/Article/details/gtvwkzxgwl.html

[Q18] 模糊匹配
来源：http://dali.haohaochexian.top/Article/details/gtsjukfdui.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cqqwz.cn/Article/details/gteriwtwrx.html

[Q19] 范围查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtldcimcwg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hnxiangtu.top/Article/details/gtxccjrycw.html

[Q20] IN 列表
来源：http://dali.havefunace.top/Article/details/gtcddgkgea.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.smart0.xyz/Article/details/gtryenvtgn.html

[Q21] 空值判断
来源：http://dali.aibaodan.cn/Article/details/gtxljtpduf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hongshengwenyu.top/Article/details/gtokmzmyvd.html

[Q22] 排序
来源：http://dali.zhoulong.xyz/Article/details/gtznogpfzk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jlsjyb.cn/Article/details/gtdyfedvvs.html

[Q23] 分页
来源：http://dali.shuidangran.top/Article/details/gtqouawfmu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ydzc1.top/Article/details/gtrihasrsd.html

[Q24] 去重
来源：http://dali.svipenyu.cn/Article/details/gtdgkmbecn.html

SELECT DISTINCT city FROM users;
来源：http://dali.yuxming.cn/Article/details/gturobccff.html

[Q25] 只取前 N 条
来源：http://dali.cashguo.top/Article/details/gtmcxtdpjp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xinyue.icu/Article/details/gthwknwkry.html

[Q26] 计数
来源：http://dali.hywenlv.cn/Article/details/gtltaqpxxx.html

SELECT COUNT(*) FROM users;
来源：http://dali.yonumen.top/Article/details/gtxyntpspe.html

[Q27] 条件计数
来源：http://dali.feifeiyinyue.top/Article/details/gtlecuxyot.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtuzofhtam.html

[Q28] 求和与平均
来源：http://dali.cheryme.top/Article/details/gtgatrfrbr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.birdmap.top/Article/details/gtzhiwkwez.html

[Q29] 最大最小值
来源：http://dali.guannengcc.top/Article/details/gtvdvbefsm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtcgnghntq.html

[Q30] 分组统计
来源：http://dali.cashguo.top/Article/details/gtoagvdgdy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gtnpblzvoy.html

[Q31] 分组后过滤
来源：http://dali.cqqwz.cn/Article/details/gtoeniqhco.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ydzc1.top/Article/details/gtlgiikyli.html

[Q32] 分组拼接字符串
来源：http://dali.cashguo.top/Article/details/gthnpwzmls.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.andypj.xyz/Article/details/gtqdrmpprr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yueranfly.top/Article/details/gtmphokjol.html

[Q33] 多列分组
来源：http://dali.cheryme.top/Article/details/gttbzqsqrf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yj202588.top/Article/details/gtsnohuhzf.html

[Q34] 每组取第一条
来源：http://dali.cqqwz.cn/Article/details/gtkvnbhgcs.html

SELECT * FROM (
来源：http://dali.ybcxt.top/Article/details/gtgrxhvlvk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.9152youxi.cn/Article/details/gtbjougzae.html

) t WHERE rn = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtaumzfupe.html

[Q35] 内连接
来源：http://dali.cashguo.top/Article/details/gtuulueyfk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuetiantiany.cn/Article/details/gtxdlovvll.html

[Q36] 左连接
来源：http://dali.jyoumei.cn/Article/details/gtbmzdijed.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnxiangtu.top/Article/details/gttchbchsb.html

[Q37] 右连接
来源：http://dali.zhiwuduotai.top/Article/details/gtlyusxgsk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhoulong.xyz/Article/details/gtuysminsw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jyoumei.cn/Article/details/gtvzzhwyes.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenjidiqi.icu/Article/details/gtsiauwdlx.html

[Q39] 自连接（查上下级）
来源：http://dali.xuetiantiany.cn/Article/details/gtmrdsitxq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.guannengcc.top/Article/details/gtkqvksvrp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hysaishi.cn/Article/details/gthelnstcw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.dianchejie.cn/Article/details/gtgwigqylb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenzaomai.com/Article/details/gtfxalquii.html

[Q41] 多表连接
来源：http://dali.sysykeji.top/Article/details/gtmsiioopw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.guannengcc.top/Article/details/gtjhqguctw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hnxiangtu.top/Article/details/gtwgoltyrf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sysykeji.top/Article/details/gtkfbfscwy.html

[Q42] 连接条件附加过滤
来源：http://dali.hnqzz.top/Article/details/gtkfantjfx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tanke756.top/Article/details/gtyvnwxnes.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hysaishi.cn/Article/details/gtwdlumcmo.html

[Q43] 标量子查询
来源：http://dali.sufxvd.cn/Article/details/gtrdlzwpkh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgufenzy.top/Article/details/gtekjgpkym.html

[Q44] IN 子查询
来源：http://dali.ppjwa.cn/Article/details/gtkyzeobua.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.haohaochexian.top/Article/details/gtlgxegknz.html

[Q45] EXISTS 判断存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdibkjdl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daxiang520.top/Article/details/gtpnyanpsm.html


<!-- 参考信息 -->