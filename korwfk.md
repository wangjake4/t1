代发 wailian999

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hnqzz.top/Article/details/gtqwvhmwmq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.iojbl.cn/Article/details/gtkgzssfjw.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenjidiqi.icu/Article/details/gtmqgxrwzk.html

Java: // 手写 HashMap
来源：http://dali.dianchejie.cn/Article/details/gtcxtfehbd.html

Go:   // 手写 map[int]int
来源：http://dali.jyoumei.cn/Article/details/gtmsspkckj.html

Ruby: // 手写 Hash
来源：http://dali.sysykeji.top/Article/details/gtrtdiqgky.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hammf.cn/Article/details/gtnggvtknv.html

[N08] 生成全排列
来源：http://dali.shzxlz.cn/Article/details/gtiivmujdy.html

Py:   itertools.permutations(arr)
来源：http://dali.gotoacloud.top/Article/details/gtvskuuzbt.html

PHP:  // 手写递归交换
来源：http://dali.hammf.cn/Article/details/gtwbbuendy.html

JS:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtsymouxvx.html

TS:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gtmgjvzyej.html

Java: // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtblzydnoq.html

Go:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtqxywxpqb.html

Ruby: arr.permutation.to_a
来源：http://dali.vqdsnc.cn/Article/details/gthghbkmdd.html

C#:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtkwcnmgeq.html

[N09] 栈与队列
来源：http://dali.gotoacloud.top/Article/details/gtvdukvltf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.havefunace.top/Article/details/gtadyxlrxz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.316326.xyz/Article/details/gtdayskosd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gtvfnpeabl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hnxiangtu.top/Article/details/gtdgarrhgw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shuidangran.top/Article/details/gthnftrsiq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yuxming.cn/Article/details/gtgqxgctwz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtpmtojszb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj20258.top/Article/details/gtmipggvjs.html

[N10] 链表节点定义
来源：http://dali.shuidangran.top/Article/details/gtfrgcyfxm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cdnleiting.top/Article/details/gthxwnvlhs.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hnxiangtu.top/Article/details/gtxyexivdl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xylfe.cn/Article/details/gtopwzvyrf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dianchejie.cn/Article/details/gtbydgavrq.html

Java: class Node { int v; Node next; }
来源：http://dali.chenzaomai.com/Article/details/gtltzceqlo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jianghu66.top/Article/details/gtmxcclhqo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yvedp.cn/Article/details/gthgvkamer.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tianlin.xyz/Article/details/gtuwxqcqqs.html

[N11] 二叉树中序遍历
来源：http://dali.iojbl.cn/Article/details/gtlslqvqol.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.c1oappe.top/Article/details/gtvnvejnqt.html

PHP:  // 手写递归函数
来源：http://dali.sxryk.cn/Article/details/gtuhlhghab.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangtech.top/Article/details/gtmxggapsj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuetiantiany.cn/Article/details/gtsprpjofg.html

Java: // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gthxwdfonk.html

Go:   // 手写递归
来源：http://dali.tian-w.cn/Article/details/gtzhfzfciw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj20258.top/Article/details/gturxuhhqe.html

C#:   // 手写递归
来源：http://dali.haohaochexian.top/Article/details/gttvvacibr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.bjfxy.top/Article/details/gtoyajybby.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xylfe.cn/Article/details/gtrsnxcacl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhoulong.xyz/Article/details/gtwdhtwseg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj202588.top/Article/details/gtjvtcgimm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shuidangran.top/Article/details/gtjyuqkzzf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuanzhike.top/Article/details/gttpehszfz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.feifeiyinyue.top/Article/details/gtsxbabihq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.fengsongda.top/Article/details/gtwsgjypgj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hongshengwenyu.top/Article/details/gtxbduijjq.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtsvncnwjd.html

O. 并发与异步
来源：http://dali.xuetiantiany.cn/Article/details/gtftcsusum.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtljevuvhz.html

[O01] 启动一个线程
来源：http://dali.jqgfzy.top/Article/details/gtvmuwtmrw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cqqwz.cn/Article/details/gtuvfzvhdz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyzcpjdqy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xuetiantiany.cn/Article/details/gtcqpirzpk.html

TS:   // 同 JS
来源：http://dali.shzxlz.cn/Article/details/gtqxkbglud.html

Java: new Thread(() -> f()).start()
来源：http://dali.yangfankeji.com/Article/details/gttotwycoj.html

Go:   go f()
来源：http://dali.wangshuangyany.cn/Article/details/gtjrgmuzgm.html

Ruby: Thread.new { f }
来源：http://dali.wangshuangyany.cn/Article/details/gthxyrisiu.html

C#:   Task.Run(() => F());
来源：http://dali.ybcxt.top/Article/details/gtkbocgtgn.html

[O02] 使用线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzofykdlr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj202588.top/Article/details/gtytonwasd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangshuangyany.cn/Article/details/gtzwfrhzpz.html

JS:   // worker_threads 线程池
来源：http://dali.gzhubu.top/Article/details/gtittwfqgd.html

TS:   // worker_threads 线程池
来源：http://dali.pengpengdd.cyou/Article/details/gtoapgjewo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hfpthk.cn/Article/details/gtnkkplurs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.guannengcc.top/Article/details/gtqgureyiv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.daria6918.cn/Article/details/gtcaoxlxrx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tanke756.top/Article/details/gtzyfrzzae.html

[O03] 加锁保护共享数据
来源：http://dali.dianchejie.cn/Article/details/gtzxxwozct.html

Py:   with lock: shared += 1
来源：http://dali.cdnleiting.top/Article/details/gttulwheis.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ydzc1.top/Article/details/gtnaoortso.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.kuanghao11.cn/Article/details/gtwqtdokvo.html

TS:   // 同 JS
来源：http://dali.yongpay.top/Article/details/gtuymphipc.html

Java: synchronized (this) { shared++; }
来源：http://dali.jlsjyb.cn/Article/details/gtgbzbezbt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.kuanghao11.cn/Article/details/gtbaaeaikm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.pengpengdd.cyou/Article/details/gtjfnzqbdj.html

C#:   lock (gate) { shared++; }
来源：http://dali.hysaishi.cn/Article/details/gthmxvnqyp.html

[O04] 定义异步函数并等待
来源：http://dali.iojbl.cn/Article/details/gtftmeupep.html

Py:   async def f():⏎    await g()
来源：http://dali.aibaodan.cn/Article/details/gtqyymctaf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjorwubvv.html

JS:   async function f() { await g(); }
来源：http://dali.birdmap.top/Article/details/gtsdbnmvdg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvojsvxup.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dashuyun.cn/Article/details/gtpjylltef.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yueranfly.top/Article/details/gtptikblzr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.birdmap.top/Article/details/gtjptwxwqc.html

C#:   async Task F() { await G(); }
来源：http://dali.hysaishi.cn/Article/details/gttmixroem.html

[O05] 并发执行并等待全部完成
来源：http://dali.guannengcc.top/Article/details/gtfpfhpiuq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hywenlv.cn/Article/details/gtsarfqdlz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yonumen.top/Article/details/gtezjnlgvk.html

JS:   await Promise.all(tasks)
来源：http://dali.birdmap.top/Article/details/gtapntvrtf.html

TS:   await Promise.all(tasks)
来源：http://dali.vqdsnc.cn/Article/details/gtoycrmivr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.iojbl.cn/Article/details/gttuxglbcz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jiagoushi.top/Article/details/gtrsgpmnov.html

Ruby: threads.map(&:join)
来源：http://dali.316326.xyz/Article/details/gtipyisrgh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaaemlpyz.html

[O06] 使用进程池
来源：http://dali.xuanzx.com/Article/details/gtcopvqyct.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtovsleqsu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shuidangran.top/Article/details/gthazjymoz.html

JS:   // child_process / cluster 模块
来源：http://dali.meibo888.top/Article/details/gtvvdcqpbp.html

TS:   // child_process / cluster 模块
来源：http://dali.zhixingplan.top/Article/details/gtsbycqwdu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.dashuyun.cn/Article/details/gthytsqhoh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.dianchejie.cn/Article/details/gtpzaygppb.html

Ruby: // fork 块
来源：http://dali.zhongyouzk.top/Article/details/gtngejdrqe.html

C#:   Parallel.For
来源：http://dali.ivvv.top/Article/details/gtsnykjiqy.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtjrcnjtqp.html

P. 常用工具函数
来源：http://dali.yongpay.top/Article/details/gtfjbaktli.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfxrdvwiq.html

[P01] 生成 UUID
来源：http://dali.zhoulong.xyz/Article/details/gtcpoyhzdm.html

Py:   str(uuid.uuid4())
来源：http://dali.hongshengwenyu.top/Article/details/gtkhmxfima.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.kuanghao11.cn/Article/details/gtublcwrqc.html

JS:   crypto.randomUUID()
来源：http://dali.iojbl.cn/Article/details/gtnwuiixbm.html

TS:   crypto.randomUUID()
来源：http://dali.sufxvd.cn/Article/details/gtabwbnghd.html

Java: UUID.randomUUID().toString()
来源：http://dali.c1oappe.top/Article/details/gtifitepom.html

Go:   // 用 github.com/google/uuid
来源：http://dali.mhx1999.top/Article/details/gtjoiafuaw.html

Ruby: SecureRandom.uuid
来源：http://dali.xylfe.cn/Article/details/gtlfqmzpix.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xuetiantiany.cn/Article/details/gtjuowaans.html

[P02] MD5 / SHA256 摘要
来源：http://dali.havefunace.top/Article/details/gtmyhdaidb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xziqi.cn/Article/details/gteuxdftew.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tanke756.top/Article/details/gtyvvubvvm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhongyouzk.top/Article/details/gtcqveqszr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhaomingkeji.xyz/Article/details/gteiyofshk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.9152youxi.cn/Article/details/gtvlgawcvc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zdqjudy.top/Article/details/gtjoypdqpm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj20258.top/Article/details/gtdwgqizsz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hammf.cn/Article/details/gtnhpodkxh.html

[P03] 生成短随机字符串
来源：http://dali.9152youxi.cn/Article/details/gtfrtzjutu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.snrcjt.cn/Article/details/gtfexcedac.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jqgufenzy.top/Article/details/gtszpybiof.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.birdmap.top/Article/details/gtdysucfnb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yvedp.cn/Article/details/gtzrscfipc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ydzc1.top/Article/details/gtwtvsipru.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hammf.cn/Article/details/gtdypcfspa.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhxfwtey.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hywenlv.cn/Article/details/gtcwdlwfsc.html

[P04] 求长度
来源：http://dali.hnxiangtu.top/Article/details/gtmlrogwda.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenjidiqi.icu/Article/details/gtxmncwaeh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gtbhwjgmmm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.andypj.xyz/Article/details/gtcaokiclh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ywan-chungtsiang.top/Article/details/gttdqlhawr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ybcxt.top/Article/details/gtftzdvwfm.html

Go:   len(arr);  len(m)
来源：http://dali.pycfn.com/Article/details/gtfogjwprx.html

Ruby: x.length;  x.size
来源：http://dali.hfpthk.cn/Article/details/gtxbjdulbc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zdqjudy.top/Article/details/gtmpnztrdp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yongpay.top/Article/details/gtlgircwzb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cqqwz.cn/Article/details/gtwiczysck.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zycfv.cn/Article/details/gtsujpuwpq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.nanxinkj.top/Article/details/gtuvsuzlei.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sufxvd.cn/Article/details/gtwtiregey.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xziqi.cn/Article/details/gtafzwmvvl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xziqi.cn/Article/details/gtyurzerqu.html

Ruby: a == b
来源：http://dali.zhongyouzk.top/Article/details/gtecbyylgj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ppjwa.cn/Article/details/gtczoetwjb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gogol.net.cn/Article/details/gtkkmjvnot.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hnxiangtu.top/Article/details/gthzyjhpie.html

PHP:  if (empty($x)) {}
来源：http://dali.sufxvd.cn/Article/details/gtdjiudgzg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.fzhhl.top/Article/details/gtandvairk.html

TS:   if (x == null) {}
来源：http://dali.sysykeji.top/Article/details/gtcclvdsxq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gtyxwwnrqs.html

Go:   if x == nil {}
来源：http://dali.tianlin.xyz/Article/details/gtwycovvkc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.c1oappe.top/Article/details/gtxmnimnsl.html

C#:   if (x is null) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtvaxrgfgl.html

[P07] 防抖与节流
来源：http://dali.quarkkingdee.top/Article/details/gtfekjhvwr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jyoumei.cn/Article/details/gtccbshmqy.html

PHP:  // 手写时间戳比较
来源：http://dali.redwolf501.top/Article/details/gtrheoakmc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuxming.cn/Article/details/gtxeubsrwt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cqqwz.cn/Article/details/gtogcaycwk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xuanzx.com/Article/details/gtysyejmem.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.vqdsnc.cn/Article/details/gtxrkhrgus.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yueranfly.top/Article/details/gtzbsvcjui.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.birdmap.top/Article/details/gtkdbjhvtv.html

[P08] 处理浮点精度问题
来源：http://dali.yj20258.top/Article/details/gtwwxlqowr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jyoumei.cn/Article/details/gtptxaupsq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ydzc1.top/Article/details/gtigqjcptg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.wangshuangyany.cn/Article/details/gtjacsxgoe.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhoulong.xyz/Article/details/gtnnycyvkn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.wangdashe.top/Article/details/gtwfwcmibz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tianlin.xyz/Article/details/gtxvnhwutp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gogol.net.cn/Article/details/gtqzqkqvcd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinqigfzy.top/Article/details/gtwjlkwoui.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtoufwbbdo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yongpay.top/Article/details/gtxsqzeygp.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtyyvwscro.html

[Q01] 创建表
来源：http://dali.yonumen.top/Article/details/gtvlcqjcsa.html

CREATE TABLE users (
来源：http://dali.zhengqikj.top/Article/details/gtzydnfxmx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ivvv.top/Article/details/gtwfsykurx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.meibo888.top/Article/details/gtvuihllwj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xinyue.icu/Article/details/gtitdyuxzp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.wangshuangyany.cn/Article/details/gthqildvrh.html

);
来源：http://dali.chenjidiqi.icu/Article/details/gtbhkiqwbl.html

[Q02] 创建带外键的表
来源：http://dali.zhongyouzk.top/Article/details/gtmxhfkwrd.html

CREATE TABLE orders (
来源：http://dali.andypj.xyz/Article/details/gtehtmletg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuanzhike.top/Article/details/gtrfsqrpau.html

user_id INT NOT NULL,
来源：http://dali.jqgufenzy.top/Article/details/gtcjbtlkqg.html

amount DECIMAL(10, 2),
来源：http://dali.zhongyouzk.top/Article/details/gtbxitzdzs.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gogol.net.cn/Article/details/gtstsmznxk.html

);
来源：http://dali.andypj.xyz/Article/details/gtxnhxcodz.html

[Q03] 增加列
来源：http://dali.yangfankeji.com/Article/details/gtjdmzvoet.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.vqdsnc.cn/Article/details/gtgstpzomq.html

[Q04] 修改列类型
来源：http://dali.aizwys.cn/Article/details/gtqlvroymm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tianlin.xyz/Article/details/gtsxejfuqm.html

[Q05] 重命名列
来源：http://dali.snrcjt.cn/Article/details/gtsbcjzecx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhengqikj.top/Article/details/gtickqijoe.html

[Q06] 删除列
来源：http://dali.zhongyouzk.top/Article/details/gtavgmkudz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tian-w.cn/Article/details/gtphfvzcwx.html

[Q07] 删除表
来源：http://dali.jiagoushi.top/Article/details/gtbwggerjt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yueranfly.top/Article/details/gtsspehdmx.html

[Q08] 创建普通索引
来源：http://dali.daria6918.cn/Article/details/gtrytmeuzp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.guannengcc.top/Article/details/gtsmwajxxo.html

[Q09] 创建唯一索引
来源：http://dali.shzxlz.cn/Article/details/gthoaanzjp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.svipenyu.cn/Article/details/gtjxfaqxne.html

[Q10] 插入单行
来源：http://dali.yueranfly.top/Article/details/gtyyntnrvz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.0kj1m.cn/Article/details/gtajptjnqh.html

[Q11] 一次插入多行
来源：http://dali.shanyushiyangtech.top/Article/details/gtudjrbajz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.guowangkeji.top/Article/details/gtzcttneta.html

[Q12] 插入后取自增 ID
来源：http://dali.haohaochexian.top/Article/details/gtixdytwsw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.snrcjt.cn/Article/details/gtpfhbhxho.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenlongwang.top/Article/details/gtofujwepz.html

[Q13] 忽略重复插入
来源：http://dali.zhongyouzk.top/Article/details/gtfooyisfo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cucudq.cn/Article/details/gtqvgwugan.html

[Q14] 存在则更新（upsert）
来源：http://dali.yj20258888.top/Article/details/gtqnupjkvy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.aizwys.cn/Article/details/gtqjnqvjug.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.wangdashe.top/Article/details/gtynlxcgox.html

[Q15] 查询全部
来源：http://dali.jinghuilouyu.cn/Article/details/gtddwltdmt.html

SELECT * FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtlwbfzxop.html

[Q16] 查询指定列
来源：http://dali.ivvv.top/Article/details/gtuuzaerxr.html

SELECT id, name FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtigjzmins.html

[Q17] 条件查询
来源：http://dali.guowangkeji.top/Article/details/gtbqmykhhy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.svipenyu.cn/Article/details/gtsfxgqsur.html

[Q18] 模糊匹配
来源：http://dali.hysaishi.cn/Article/details/gtirdmveky.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gogol.net.cn/Article/details/gtkeixegzk.html

[Q19] 范围查询
来源：http://dali.meibo888.top/Article/details/gtnlckqmog.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jqgufenzy.top/Article/details/gtojidoojk.html

[Q20] IN 列表
来源：http://dali.snrcjt.cn/Article/details/gtryqjvdqs.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yonumen.top/Article/details/gtpmphqfiu.html

[Q21] 空值判断
来源：http://dali.zhiwuduotai.top/Article/details/gtessmoiml.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sufxvd.cn/Article/details/gtnoupvhvt.html

[Q22] 排序
来源：http://dali.ivvv.top/Article/details/gtlgxhqwal.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenlongwang.top/Article/details/gtgwtwsqfh.html

[Q23] 分页
来源：http://dali.cheryme.top/Article/details/gtuhpurtvo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tian-w.cn/Article/details/gtiorrrpds.html

[Q24] 去重
来源：http://dali.hongshengwenyu.top/Article/details/gtcfyzjbnd.html

SELECT DISTINCT city FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtrhtmuhbr.html

[Q25] 只取前 N 条
来源：http://dali.mhx1999.top/Article/details/gtzmbmdelv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shuidangran.top/Article/details/gtkzqwwgrp.html

[Q26] 计数
来源：http://dali.hongshengwenyu.top/Article/details/gtyfomduzy.html

SELECT COUNT(*) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtcfffimcs.html

[Q27] 条件计数
来源：http://dali.jiagoushi.top/Article/details/gtcbynxxeq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtfarnop.html

[Q28] 求和与平均
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmaxtpjo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtvmsyscnh.html

[Q29] 最大最小值
来源：http://dali.yj20258888.top/Article/details/gtmwxfniei.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gttedqbpzt.html

[Q30] 分组统计
来源：http://dali.jiagoushi.top/Article/details/gtgqmmodrb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gtootwgsda.html

[Q31] 分组后过滤
来源：http://dali.chenlongwang.top/Article/details/gtlswqebgr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nanxuanxn.top/Article/details/gtssgcjgsm.html

[Q32] 分组拼接字符串
来源：http://dali.nwbrower.top/Article/details/gtudxlkqze.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gtwfbawrsi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.redwolf501.top/Article/details/gtregbdwnt.html

[Q33] 多列分组
来源：http://dali.nwbrower.top/Article/details/gtpjfspssh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shzxlz.cn/Article/details/gtcjyfmshx.html

[Q34] 每组取第一条
来源：http://dali.vqdsnc.cn/Article/details/gtjpiasnkp.html

SELECT * FROM (
来源：http://dali.yonumen.top/Article/details/gtirgqbjkp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrhpgdhy.html

) t WHERE rn = 1;
来源：http://dali.yuxming.cn/Article/details/gtyqawxchi.html

[Q35] 内连接
来源：http://dali.aibaodan.cn/Article/details/gtogeyiqks.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cucudq.cn/Article/details/gtyauxnlvn.html

[Q36] 左连接
来源：http://dali.0kj1m.cn/Article/details/gtscmbpgns.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gttauobozt.html

[Q37] 右连接
来源：http://dali.gaohongyu789.top/Article/details/gtshualntz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.9152youxi.cn/Article/details/gtffmyjxli.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jiagoushi.top/Article/details/gtohdlalbr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.daxiang520.top/Article/details/gtbsasktwy.html

[Q39] 自连接（查上下级）
来源：http://dali.gotoacloud.top/Article/details/gtiandzwqf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yanxiufei.cn/Article/details/gtbgiigtrf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ppjwa.cn/Article/details/gtelkpxkvz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ehwqpu.com/Article/details/gtedftnrcc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shangyingyoupin.top/Article/details/gtbijnbqyi.html

[Q41] 多表连接
来源：http://dali.ydzc1.top/Article/details/gtelnlhnny.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yangfankeji.com/Article/details/gtxoulmnec.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xylfe.cn/Article/details/gtzvxzvizh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nwbrower.top/Article/details/gtympjorcu.html

[Q42] 连接条件附加过滤
来源：http://dali.andypj.xyz/Article/details/gtrchpvbcn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sweek.top/Article/details/gtsytbzfvo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.smart0.xyz/Article/details/gtlbdnixzt.html

[Q43] 标量子查询
来源：http://dali.gogol.net.cn/Article/details/gtkibyelbo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yj202588.top/Article/details/gtgyqgfixe.html

[Q44] IN 子查询
来源：http://dali.wangshuangyany.cn/Article/details/gtqxlbxsmb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.wangdashe.top/Article/details/gtsfpggpti.html

[Q45] EXISTS 判断存在
来源：http://dali.xinyue.icu/Article/details/gtlpgpuuwp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xinyue.icu/Article/details/gtvenkjrnp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hfpthk.cn/Article/details/gthmuxqwpv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrxojcsrh.html

[Q47] 与平均值比较
来源：http://dali.cqqwz.cn/Article/details/gtpxttjydo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hfpthk.cn/Article/details/gtbhxocgxs.html


<!-- 参考信息 -->