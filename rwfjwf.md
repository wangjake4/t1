代发 wailian999

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nwbrower.top/Article/details/gtmtlqoysb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yvedp.cn/Article/details/gtqdsvnujc.html

TS:   // 手写 Map<string, number>
来源：http://dali.tian-w.cn/Article/details/gtjaomsdth.html

Java: // 手写 HashMap
来源：http://dali.jinqigufen.top/Article/details/gtinaugjcf.html

Go:   // 手写 map[int]int
来源：http://dali.ivvv.top/Article/details/gtuuwcmfra.html

Ruby: // 手写 Hash
来源：http://dali.gzhubu.top/Article/details/gtmpkgnvuh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.aizwys.cn/Article/details/gtisxnietn.html

[N08] 生成全排列
来源：http://dali.xuanzx.com/Article/details/gtlncbkzxp.html

Py:   itertools.permutations(arr)
来源：http://dali.wangdashe.top/Article/details/gtjvhdelgf.html

PHP:  // 手写递归交换
来源：http://dali.guowangkeji.top/Article/details/gtvwbddivq.html

JS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtjqomiklv.html

TS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtztflgclp.html

Java: // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtthknkstk.html

Go:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gthbahteoz.html

Ruby: arr.permutation.to_a
来源：http://dali.smart0.xyz/Article/details/gtszqozses.html

C#:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gtxyujzthn.html

[N09] 栈与队列
来源：http://dali.birdmap.top/Article/details/gthqetruta.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daria6918.cn/Article/details/gtaxnhwste.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.smart0.xyz/Article/details/gtjivzvmhp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.andypj.xyz/Article/details/gtqlptzsou.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cheryme.top/Article/details/gtudtmejcj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shuidangran.top/Article/details/gtohhqghko.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.meibo888.top/Article/details/gtfausgnmj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xinyue.icu/Article/details/gtdjlnguif.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xylfe.cn/Article/details/gtgrxxyuxb.html

[N10] 链表节点定义
来源：http://dali.hnxiangtu.top/Article/details/gtcbjtjkxw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.pengpengdd.cyou/Article/details/gttrqxaqqu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jqgfzy.top/Article/details/gtfpugdnbp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.daria6918.cn/Article/details/gtqvenoxdd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nanxinkj.top/Article/details/gtxffzhmcb.html

Java: class Node { int v; Node next; }
来源：http://dali.quarkkingdee.top/Article/details/gtcpvmbikl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hysaishi.cn/Article/details/gtwsgqhlwa.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cdnleiting.top/Article/details/gtctbxlsgu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj20258888.top/Article/details/gtjkzitqgi.html

[N11] 二叉树中序遍历
来源：http://dali.aizwys.cn/Article/details/gthgyywqop.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinqigfzy.top/Article/details/gtmyjbrnlq.html

PHP:  // 手写递归函数
来源：http://dali.nwbrower.top/Article/details/gtyucokdue.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigfzy.top/Article/details/gtzoolxugr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shuidangran.top/Article/details/gtgqpgxwxo.html

Java: // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gthvoncela.html

Go:   // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtvsrnomip.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hammf.cn/Article/details/gtmfaalgle.html

C#:   // 手写递归
来源：http://dali.nwbrower.top/Article/details/gtimueyhhf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.birdmap.top/Article/details/gtxdhtqeca.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenzaomai.com/Article/details/gtuoncdokc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.tianlin.xyz/Article/details/gtsxatuher.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aibaodan.cn/Article/details/gtdtxtsfay.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nwbrower.top/Article/details/gtewagkffv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenjidiqi.icu/Article/details/gtbqgaubvi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.c1oappe.top/Article/details/gtwftddufe.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gtgmjfyeqf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fzhhl.top/Article/details/gtbmwdfjyn.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtdcjziesb.html

O. 并发与异步
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiuqijtwd.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtotjldmzx.html

[O01] 启动一个线程
来源：http://dali.shzxlz.cn/Article/details/gtjcxlefic.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpsoimxsy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.mhx1999.top/Article/details/gtamptbjuv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.316326.xyz/Article/details/gtftmjmpse.html

TS:   // 同 JS
来源：http://dali.hysaishi.cn/Article/details/gtcgsnhnkh.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhixingplan.top/Article/details/gtvpsbocyl.html

Go:   go f()
来源：http://dali.zhixingplan.top/Article/details/gtunhhmdeq.html

Ruby: Thread.new { f }
来源：http://dali.ehwqpu.com/Article/details/gttigvglpb.html

C#:   Task.Run(() => F());
来源：http://dali.bjfxy.top/Article/details/gtfzxcoefa.html

[O02] 使用线程池
来源：http://dali.zhengqikj.top/Article/details/gtsysdbogf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tianlin.xyz/Article/details/gtygguhrfj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xuetiantiany.cn/Article/details/gtekubogeb.html

JS:   // worker_threads 线程池
来源：http://dali.316326.xyz/Article/details/gtsiomsmhf.html

TS:   // worker_threads 线程池
来源：http://dali.yueranfly.top/Article/details/gtnsfvsuhe.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shuidangran.top/Article/details/gtpmfcslwa.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gotoacloud.top/Article/details/gtisaghxbg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yangfankeji.com/Article/details/gtzmlnepgn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinqigufen.top/Article/details/gtgtxpjqkl.html

[O03] 加锁保护共享数据
来源：http://dali.meibo888.top/Article/details/gtzbwtmacu.html

Py:   with lock: shared += 1
来源：http://dali.guannengcc.top/Article/details/gthdiwbeqw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tianlin.xyz/Article/details/gtdkqyrqzx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.meibo888.top/Article/details/gtdiahqreg.html

TS:   // 同 JS
来源：http://dali.hammf.cn/Article/details/gtsekorhga.html

Java: synchronized (this) { shared++; }
来源：http://dali.jlsjyb.cn/Article/details/gttruvxirp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwarhdhti.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yongpay.top/Article/details/gtggelaaho.html

C#:   lock (gate) { shared++; }
来源：http://dali.gogol.net.cn/Article/details/gtqzfjvsxb.html

[O04] 定义异步函数并等待
来源：http://dali.zhaomingkeji.xyz/Article/details/gtobjksqyd.html

Py:   async def f():⏎    await g()
来源：http://dali.havefunace.top/Article/details/gtlriklfqc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ybcxt.top/Article/details/gtyigdtffn.html

JS:   async function f() { await g(); }
来源：http://dali.9152youxi.cn/Article/details/gtuhubxfzg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gotoacloud.top/Article/details/gtlsbumzfa.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.bjfxy.top/Article/details/gtowdgcqve.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.daria6918.cn/Article/details/gtgyjmvuhm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xziqi.cn/Article/details/gtacqiholi.html

C#:   async Task F() { await G(); }
来源：http://dali.jinqigfzy.top/Article/details/gtixwdmtgf.html

[O05] 并发执行并等待全部完成
来源：http://dali.xziqi.cn/Article/details/gtspgjjxwe.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xylfe.cn/Article/details/gtoxbdeaje.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.guannengcc.top/Article/details/gtnebigcvb.html

JS:   await Promise.all(tasks)
来源：http://dali.hammf.cn/Article/details/gtxzhrcsxy.html

TS:   await Promise.all(tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdnxzcgk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.dianchejie.cn/Article/details/gtltzgvfum.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yonumen.top/Article/details/gtiqkhkjmg.html

Ruby: threads.map(&:join)
来源：http://dali.wangshuangyany.cn/Article/details/gtfdqkjosl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sufxvd.cn/Article/details/gtykjdfnwm.html

[O06] 使用进程池
来源：http://dali.jianghu66.top/Article/details/gtxhhwtltc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fzhhl.top/Article/details/gtrxygfczi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuxming.cn/Article/details/gtsehtvxjy.html

JS:   // child_process / cluster 模块
来源：http://dali.jinqigfzy.top/Article/details/gtmzefvahs.html

TS:   // child_process / cluster 模块
来源：http://dali.shangyingyoupin.top/Article/details/gtclqcxeqy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hysaishi.cn/Article/details/gtlxnwmkhu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yangfankeji.com/Article/details/gtepghindt.html

Ruby: // fork 块
来源：http://dali.bjfxy.top/Article/details/gtrchoyidm.html

C#:   Parallel.For
来源：http://dali.guannengcc.top/Article/details/gtwbirelva.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtrvxtcgma.html

P. 常用工具函数
来源：http://dali.zhongyouzk.top/Article/details/gtujskykqh.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtwroejghu.html

[P01] 生成 UUID
来源：http://dali.jinghuilouyu.cn/Article/details/gtejlbbvui.html

Py:   str(uuid.uuid4())
来源：http://dali.yanxiufei.cn/Article/details/gtjqvklwem.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hysaishi.cn/Article/details/gtcoppiujs.html

JS:   crypto.randomUUID()
来源：http://dali.yj20258888.top/Article/details/gtgccbohex.html

TS:   crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gtooffzuvj.html

Java: UUID.randomUUID().toString()
来源：http://dali.yongpay.top/Article/details/gtjtsdkegf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gotoacloud.top/Article/details/gtovbsrdds.html

Ruby: SecureRandom.uuid
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqstpagkr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tian-w.cn/Article/details/gtumczdasa.html

[P02] MD5 / SHA256 摘要
来源：http://dali.daxiang520.top/Article/details/gtzlvjtwhe.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cqqwz.cn/Article/details/gtgfghryqy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ppjwa.cn/Article/details/gtdqkzqjdj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.mhx1999.top/Article/details/gtadsukotp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sweek.top/Article/details/gttxsdlaxf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cdnleiting.top/Article/details/gtstmqenhl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cashguo.top/Article/details/gtuiliyidq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxinkj.top/Article/details/gtaialmqjw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdycnbaxs.html

[P03] 生成短随机字符串
来源：http://dali.fengsongda.top/Article/details/gtmtmpifaj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shanyushiyangtech.top/Article/details/gtifnhgisz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ydzc1.top/Article/details/gtbgtbutkh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zdqjudy.top/Article/details/gtsdgcxrhg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtalwqzjsv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xuanzx.com/Article/details/gtbhczqdbq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinqigfzy.top/Article/details/gtoabhgnbl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sysykeji.top/Article/details/gtubnahjhi.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ybcxt.top/Article/details/gtxixzxrvx.html

[P04] 求长度
来源：http://dali.gaohongyu789.top/Article/details/gtkwcfkcpa.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.pycfn.com/Article/details/gtnigwcwvh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtbydvqtod.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhiwuduotai.top/Article/details/gtbnjwyyoc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daxiang520.top/Article/details/gtvjgazukw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtinwfhlfe.html

Go:   len(arr);  len(m)
来源：http://dali.guowangkeji.top/Article/details/gtuvuvevzf.html

Ruby: x.length;  x.size
来源：http://dali.shzxlz.cn/Article/details/gtspckyupf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hywenlv.cn/Article/details/gtzoohyugt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yueranfly.top/Article/details/gtsyzftcle.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.andypj.xyz/Article/details/gtbatqbzrh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shanyushiyangtech.top/Article/details/gtundukxpv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.mhx1999.top/Article/details/gtjcywdlce.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dashuyun.cn/Article/details/gtvudhyixf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinqigufen.top/Article/details/gtlcchvmpa.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtxsxnvola.html

Ruby: a == b
来源：http://dali.hnqzz.top/Article/details/gtbobbdyuv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sufxvd.cn/Article/details/gtsqqzolzi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnoqhzmpi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfzsixtr.html

PHP:  if (empty($x)) {}
来源：http://dali.haohaochexian.top/Article/details/gtjfhpfqjo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinghuilouyu.cn/Article/details/gtolydvjzh.html

TS:   if (x == null) {}
来源：http://dali.chenzaomai.com/Article/details/gtqwoskrdl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jianghu66.top/Article/details/gtyzsiykkl.html

Go:   if x == nil {}
来源：http://dali.cashguo.top/Article/details/gtauvddqgi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.havefunace.top/Article/details/gtpskavmuy.html

C#:   if (x is null) {}
来源：http://dali.zhoulong.xyz/Article/details/gtpwlubclq.html

[P07] 防抖与节流
来源：http://dali.gaohongyu789.top/Article/details/gtywipxmsu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenzaomai.com/Article/details/gtwcycgkor.html

PHP:  // 手写时间戳比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlvrnvcck.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ybcxt.top/Article/details/gtldgikinx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.9152youxi.cn/Article/details/gtcrnbqdae.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cqqwz.cn/Article/details/gtqlqqaxxt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.316326.xyz/Article/details/gtnndrydbu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinqigufen.top/Article/details/gtyabcfmwy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gotoacloud.top/Article/details/gtiqvjgscz.html

[P08] 处理浮点精度问题
来源：http://dali.sweek.top/Article/details/gtgmuftuui.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fzhhl.top/Article/details/gtzgyiirlp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ivvv.top/Article/details/gtkswlyppb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ydzc1.top/Article/details/gtsesntaga.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gotoacloud.top/Article/details/gtxfuphmxa.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xziqi.cn/Article/details/gtantxtdbl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yonumen.top/Article/details/gthvzebbfp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hammf.cn/Article/details/gtmegjxjsm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.pengpengdd.cyou/Article/details/gtxoqaiecw.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtskjaotnp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.mhx1999.top/Article/details/gtlziwotwg.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtjitjfnnu.html

[Q01] 创建表
来源：http://dali.yonumen.top/Article/details/gtixbrazbl.html

CREATE TABLE users (
来源：http://dali.daria6918.cn/Article/details/gtnpqrpdbi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yongpay.top/Article/details/gtxtrsxweq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gtphxilcno.html

email VARCHAR(100) UNIQUE,
来源：http://dali.fzhhl.top/Article/details/gtlbqkxhux.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinqigufen.top/Article/details/gtdoizcvbw.html

);
来源：http://dali.jyoumei.cn/Article/details/gtdjvdykrx.html

[Q02] 创建带外键的表
来源：http://dali.gotoacloud.top/Article/details/gttxwatshp.html

CREATE TABLE orders (
来源：http://dali.hnqzz.top/Article/details/gthcjzrbkf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.snrcjt.cn/Article/details/gtfeyfdlna.html

user_id INT NOT NULL,
来源：http://dali.hnqzz.top/Article/details/gtqnievitu.html

amount DECIMAL(10, 2),
来源：http://dali.gaohongyu789.top/Article/details/gtvgmtwsbg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zdqjudy.top/Article/details/gtsmbvxbem.html

);
来源：http://dali.c1oappe.top/Article/details/gtqgabdyhe.html

[Q03] 增加列
来源：http://dali.gaohongyu789.top/Article/details/gtddullbjf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ehwqpu.com/Article/details/gtspfdyayl.html

[Q04] 修改列类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtjgattnrx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.snrcjt.cn/Article/details/gtuifpzbvi.html

[Q05] 重命名列
来源：http://dali.nanxuanxn.top/Article/details/gtpfgheykz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yanxiufei.cn/Article/details/gtdzzrdeub.html

[Q06] 删除列
来源：http://dali.sxryk.cn/Article/details/gteatssayu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yanxiufei.cn/Article/details/gtuqlyoves.html

[Q07] 删除表
来源：http://dali.tian-w.cn/Article/details/gtryazhmvo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.daria6918.cn/Article/details/gtwfxwfnan.html

[Q08] 创建普通索引
来源：http://dali.jlsjyb.cn/Article/details/gtofponaan.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenjidiqi.icu/Article/details/gtnimyxipj.html

[Q09] 创建唯一索引
来源：http://dali.zdqjudy.top/Article/details/gtpkowckko.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ivvv.top/Article/details/gtblxrlrye.html

[Q10] 插入单行
来源：http://dali.zhixingplan.top/Article/details/gtxcuppugw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.smart0.xyz/Article/details/gttqxymfgn.html

[Q11] 一次插入多行
来源：http://dali.316326.xyz/Article/details/gthdopslce.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jianghu66.top/Article/details/gtycmkeyps.html

[Q12] 插入后取自增 ID
来源：http://dali.ydzc1.top/Article/details/gthgirsnmb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.316326.xyz/Article/details/gtknqzzxvx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenzaomai.com/Article/details/gtjaeysrub.html

[Q13] 忽略重复插入
来源：http://dali.smart0.xyz/Article/details/gtzhkoyksy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.feifeiyinyue.top/Article/details/gtzndgqyzo.html

[Q14] 存在则更新（upsert）
来源：http://dali.bjfxy.top/Article/details/gtxyxvtcvq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.mhx1999.top/Article/details/gtbzfgweyw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sysykeji.top/Article/details/gtqcffbknm.html

[Q15] 查询全部
来源：http://dali.fzhhl.top/Article/details/gtkzjeedfu.html

SELECT * FROM users;
来源：http://dali.hammf.cn/Article/details/gtivzlndxr.html

[Q16] 查询指定列
来源：http://dali.fengsongda.top/Article/details/gtnjqtsfjj.html

SELECT id, name FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtywjgcgfe.html

[Q17] 条件查询
来源：http://dali.shuidangran.top/Article/details/gtoaelrwct.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jyoumei.cn/Article/details/gthpbfpluh.html

[Q18] 模糊匹配
来源：http://dali.jqgufenzy.top/Article/details/gthsalijkv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yongpay.top/Article/details/gtmuavbfmz.html

[Q19] 范围查询
来源：http://dali.jinghuilouyu.cn/Article/details/gtotndorqd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.havefunace.top/Article/details/gtfjdqwabt.html

[Q20] IN 列表
来源：http://dali.yuanzhike.top/Article/details/gtvmhaules.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jqgfzy.top/Article/details/gtsqarmvpm.html

[Q21] 空值判断
来源：http://dali.guannengcc.top/Article/details/gtmmjvbeov.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ybcxt.top/Article/details/gtzrvpllsf.html

[Q22] 排序
来源：http://dali.gzhubu.top/Article/details/gtmpxgdezt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.aibaodan.cn/Article/details/gtsgmavivz.html

[Q23] 分页
来源：http://dali.haohaochexian.top/Article/details/gtdrxmfyqi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.aizwys.cn/Article/details/gtizqeuzoo.html

[Q24] 去重
来源：http://dali.birdmap.top/Article/details/gtjoqmujoy.html

SELECT DISTINCT city FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtofwdcgdt.html

[Q25] 只取前 N 条
来源：http://dali.zycfv.cn/Article/details/gtcpjsyeeo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.fzhhl.top/Article/details/gtjtpuxhbn.html

[Q26] 计数
来源：http://dali.redwolf501.top/Article/details/gtwotiirou.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gthnpgdiao.html

[Q27] 条件计数
来源：http://dali.chenzaomai.com/Article/details/gtaqtcekxy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtfjdusxor.html

[Q28] 求和与平均
来源：http://dali.gaohongyu789.top/Article/details/gtmhuzmmew.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtehicmcwd.html

[Q29] 最大最小值
来源：http://dali.bjfxy.top/Article/details/gtqyzitpel.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yonumen.top/Article/details/gtojswldbz.html

[Q30] 分组统计
来源：http://dali.nanxinkj.top/Article/details/gtdxmnfplo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gteiyaflmn.html

[Q31] 分组后过滤
来源：http://dali.wangdashe.top/Article/details/gtreyrnxpy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxobizgrj.html

[Q32] 分组拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtnibirijo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ybcxt.top/Article/details/gtvzdazxpk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sweek.top/Article/details/gtngqcstvl.html

[Q33] 多列分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnbzzjaal.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.feifeiyinyue.top/Article/details/gtkzxsxkbz.html

[Q34] 每组取第一条
来源：http://dali.guannengcc.top/Article/details/gtqrcxmdiv.html

SELECT * FROM (
来源：http://dali.redwolf501.top/Article/details/gtiyjqpqvn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.kuanghao11.cn/Article/details/gtyvokjixs.html

) t WHERE rn = 1;
来源：http://dali.jqgfzy.top/Article/details/gtzcmpltae.html

[Q35] 内连接
来源：http://dali.zhongyouzk.top/Article/details/gttwuzlkkj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ppjwa.cn/Article/details/gtvcfwnzbk.html

[Q36] 左连接
来源：http://dali.cdnleiting.top/Article/details/gtscxdeebp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zycfv.cn/Article/details/gtvzruklzf.html

[Q37] 右连接
来源：http://dali.hongshengwenyu.top/Article/details/gtnfbzpxqb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.aizwys.cn/Article/details/gtewhjrfwq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrgwnlbwv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.dianchejie.cn/Article/details/gtapyjsenc.html

[Q39] 自连接（查上下级）
来源：http://dali.gaohongyu789.top/Article/details/gtshismteh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gzhubu.top/Article/details/gtzqejhvbe.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.kuanghao11.cn/Article/details/gtivxzvtfz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sysykeji.top/Article/details/gtxbxkanzr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.feifeiyinyue.top/Article/details/gtydrqfsem.html

[Q41] 多表连接
来源：http://dali.yonumen.top/Article/details/gtnubiqnvj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hammf.cn/Article/details/gtsjzonoeg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jianghu66.top/Article/details/gtdwgcgesl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tianlin.xyz/Article/details/gtzgfczncs.html

[Q42] 连接条件附加过滤
来源：http://dali.hysaishi.cn/Article/details/gtnipugqub.html

SELECT u.name, o.amount FROM users u
来源：http://dali.meibo888.top/Article/details/gtiauhvmhj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.redwolf501.top/Article/details/gtzxfmlzvs.html

[Q43] 标量子查询
来源：http://dali.ppjwa.cn/Article/details/gtclaiywem.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hywenlv.cn/Article/details/gtlbcuiabd.html

[Q44] IN 子查询
来源：http://dali.0kj1m.cn/Article/details/gtlvxoorxm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ivvv.top/Article/details/gtkqqkjsga.html

[Q45] EXISTS 判断存在
来源：http://dali.gaohongyu789.top/Article/details/gtyyeosebe.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhoulong.xyz/Article/details/gtnmufwvyl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hnqzz.top/Article/details/gtgjzawjhl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aizwys.cn/Article/details/gtgsmcenyn.html

[Q47] 与平均值比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzmuxagns.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.fengsongda.top/Article/details/gtskkldoer.html


<!-- 参考信息 -->