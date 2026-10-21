代发 wailian999

Go:   // 手写 map[int]int
来源：http://dali.ehwqpu.com/Article/details/gtqvzyxkvy.html

Ruby: // 手写 Hash
来源：http://dali.gzhubu.top/Article/details/gtxykgohmz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hywenlv.cn/Article/details/gtqmuwdtbm.html

[N08] 生成全排列
来源：http://dali.jqgfzy.top/Article/details/gttxnbprcs.html

Py:   itertools.permutations(arr)
来源：http://dali.cqqwz.cn/Article/details/gtkeohdzmh.html

PHP:  // 手写递归交换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtmjrqqk.html

JS:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtqwnmqghv.html

TS:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtcngbldvu.html

Java: // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtfvlrvsbx.html

Go:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtkcihnzcm.html

Ruby: arr.permutation.to_a
来源：http://dali.pycfn.com/Article/details/gtkbulveig.html

C#:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtdmrdwojk.html

[N09] 栈与队列
来源：http://dali.hfpthk.cn/Article/details/gtpthwihdt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtqpquwicz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gtueemooqz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.wangdashe.top/Article/details/gtbeamwewc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shangyingyoupin.top/Article/details/gtqhpwpjbc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ehwqpu.com/Article/details/gthyprtqay.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jiagoushi.top/Article/details/gttcglvfcb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.c1oappe.top/Article/details/gtcsxoxpqj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.kuanghao11.cn/Article/details/gtcjlboxwl.html

[N10] 链表节点定义
来源：http://dali.gogol.net.cn/Article/details/gtejiricii.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ivvv.top/Article/details/gtrotndfxs.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.bjfxy.top/Article/details/gtvhpkpkiw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gotoacloud.top/Article/details/gtryfuuwcf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hongshengwenyu.top/Article/details/gtlbgctnrb.html

Java: class Node { int v; Node next; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaydwletl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shuidangran.top/Article/details/gtuusntszg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.birdmap.top/Article/details/gtltilnkmy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tian-w.cn/Article/details/gtjvoquwsu.html

[N11] 二叉树中序遍历
来源：http://dali.yanxiufei.cn/Article/details/gtsrrqcomv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenzaomai.com/Article/details/gtkhyqfqfp.html

PHP:  // 手写递归函数
来源：http://dali.sweek.top/Article/details/gtzgzvqqwm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yongpay.top/Article/details/gtdzcuxkjj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuanzx.com/Article/details/gtnismtnzg.html

Java: // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpmflifnd.html

Go:   // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gtuapktwgj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.aizwys.cn/Article/details/gthccnlkdu.html

C#:   // 手写递归
来源：http://dali.smart0.xyz/Article/details/gtsbgjnsgm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zycfv.cn/Article/details/gtsldtcyqh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xinyue.icu/Article/details/gtzxztuhtq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jlsjyb.cn/Article/details/gttwzecmzf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jianghu66.top/Article/details/gtubcbisks.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258.top/Article/details/gtuvvbtxgk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.birdmap.top/Article/details/gtlpyqdasf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yuanzhike.top/Article/details/gtnpthsdoo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.guowangkeji.top/Article/details/gtkrwfhgmk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gogol.net.cn/Article/details/gtoulfsnak.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtkmabtyip.html

O. 并发与异步
来源：http://dali.xylfe.cn/Article/details/gtqfpzftik.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtrycdobrn.html

[O01] 启动一个线程
来源：http://dali.gaohongyu789.top/Article/details/gtlzsdhdbq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jyoumei.cn/Article/details/gtmtbqblcd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yangfankeji.com/Article/details/gtvlitsbjo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj202588.top/Article/details/gtvjnlxida.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gtapunrdrv.html

Java: new Thread(() -> f()).start()
来源：http://dali.tanke756.top/Article/details/gtxanfjbjq.html

Go:   go f()
来源：http://dali.fengsongda.top/Article/details/gtdeihgvvf.html

Ruby: Thread.new { f }
来源：http://dali.hnxiangtu.top/Article/details/gtxkuslldh.html

C#:   Task.Run(() => F());
来源：http://dali.hnxiangtu.top/Article/details/gthcaxdnmm.html

[O02] 使用线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvhueyhr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yongpay.top/Article/details/gtuddegtcx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhongyouzk.top/Article/details/gtkjzvazgu.html

JS:   // worker_threads 线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmldkzemp.html

TS:   // worker_threads 线程池
来源：http://dali.yj20258888.top/Article/details/gtyznyvgsi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.guowangkeji.top/Article/details/gtwbvghwwv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jiagoushi.top/Article/details/gtpykjnffw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj202588.top/Article/details/gtpcyfbgiv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinghuilouyu.cn/Article/details/gtfiutjiyo.html

[O03] 加锁保护共享数据
来源：http://dali.jyoumei.cn/Article/details/gtgdixpyls.html

Py:   with lock: shared += 1
来源：http://dali.sufxvd.cn/Article/details/gtchojjpzy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.guannengcc.top/Article/details/gtkamjobqt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hysaishi.cn/Article/details/gtsxtfpyrn.html

TS:   // 同 JS
来源：http://dali.redwolf501.top/Article/details/gtragzhyit.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenzaomai.com/Article/details/gtxduorrfp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tian-w.cn/Article/details/gtqtqwfhyx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hnqzz.top/Article/details/gtuembsire.html

C#:   lock (gate) { shared++; }
来源：http://dali.xylfe.cn/Article/details/gtojtwfktm.html

[O04] 定义异步函数并等待
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqkibpgd.html

Py:   async def f():⏎    await g()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfoumgbv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gaohongyu789.top/Article/details/gthpfdaaps.html

JS:   async function f() { await g(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtpxbnzvjs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hysaishi.cn/Article/details/gtsgqkvsgr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.aizwys.cn/Article/details/gtoaupnqtn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.haohaochexian.top/Article/details/gtxdfofugr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinqigufen.top/Article/details/gtghofnfzz.html

C#:   async Task F() { await G(); }
来源：http://dali.bjfxy.top/Article/details/gtfefzkcau.html

[O05] 并发执行并等待全部完成
来源：http://dali.vqdsnc.cn/Article/details/gtosbdnmpu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtwsfzlsoe.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xylfe.cn/Article/details/gtkzblbgyi.html

JS:   await Promise.all(tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gttjdlhuaj.html

TS:   await Promise.all(tasks)
来源：http://dali.cdnleiting.top/Article/details/gtdviylfoh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.mhx1999.top/Article/details/gtrgsjfkmp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nanxuanxn.top/Article/details/gtikjeaend.html

Ruby: threads.map(&:join)
来源：http://dali.jianghu66.top/Article/details/gtmhruhatm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.iojbl.cn/Article/details/gtveywhdxb.html

[O06] 使用进程池
来源：http://dali.sufxvd.cn/Article/details/gtdpvepdjn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yuxming.cn/Article/details/gtbfbliwgt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jiagoushi.top/Article/details/gtijbmfpfq.html

JS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gtfuvpmpfv.html

TS:   // child_process / cluster 模块
来源：http://dali.jinghuilouyu.cn/Article/details/gtyryfvdox.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.vqdsnc.cn/Article/details/gtuypkdjun.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.fzhhl.top/Article/details/gtjbzdwbjm.html

Ruby: // fork 块
来源：http://dali.bjfxy.top/Article/details/gthqwrhikj.html

C#:   Parallel.For
来源：http://dali.dianchejie.cn/Article/details/gtxqdltgzc.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtbzxxsrvt.html

P. 常用工具函数
来源：http://dali.xuanzx.com/Article/details/gtmtsljumo.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtnrfmkuby.html

[P01] 生成 UUID
来源：http://dali.daxiang520.top/Article/details/gtochkvsze.html

Py:   str(uuid.uuid4())
来源：http://dali.nanxinkj.top/Article/details/gtwiiwehat.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tianlin.xyz/Article/details/gtzcphbytz.html

JS:   crypto.randomUUID()
来源：http://dali.gogol.net.cn/Article/details/gteduutssy.html

TS:   crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gtvbrpxvnj.html

Java: UUID.randomUUID().toString()
来源：http://dali.aibaodan.cn/Article/details/gtmfpprups.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yanxiufei.cn/Article/details/gtktfrqvjb.html

Ruby: SecureRandom.uuid
来源：http://dali.tianlin.xyz/Article/details/gthidxpghk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yuanzhike.top/Article/details/gtfgglmbkt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.aizwys.cn/Article/details/gtzaodamsh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jiagoushi.top/Article/details/gtslwrjzyw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gtgsgsyfuy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xylfe.cn/Article/details/gtshfcmjap.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.redwolf501.top/Article/details/gtztaruuni.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hnqzz.top/Article/details/gtrfvrsfxc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.vqdsnc.cn/Article/details/gtktylllse.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.meibo888.top/Article/details/gtifaufpkw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtijcdcgvp.html

[P03] 生成短随机字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxlwckhhs.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.kuanghao11.cn/Article/details/gtgwgwmiet.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cheryme.top/Article/details/gtcgpifwdh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guowangkeji.top/Article/details/gtcwpynlmq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hywenlv.cn/Article/details/gtuvpcqjow.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tian-w.cn/Article/details/gthkwqxckm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhengqikj.top/Article/details/gtgssafgax.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.redwolf501.top/Article/details/gtsxojxiwh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj202588.top/Article/details/gtnnkbjkug.html

[P04] 求长度
来源：http://dali.yanxiufei.cn/Article/details/gttoadjlrb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhiwuduotai.top/Article/details/gtixzarobr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gtrhuncgnr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.vqdsnc.cn/Article/details/gtbpgpydec.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yonumen.top/Article/details/gthqufvdvp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ivvv.top/Article/details/gtjozbovmv.html

Go:   len(arr);  len(m)
来源：http://dali.svipenyu.cn/Article/details/gtzzyaxxfp.html

Ruby: x.length;  x.size
来源：http://dali.shzxlz.cn/Article/details/gtuwkphzbp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.meibo888.top/Article/details/gtfzkhjzmj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.chenzaomai.com/Article/details/gtdtniysoa.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tanke756.top/Article/details/gtrhanndyq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jqgufenzy.top/Article/details/gthjnlopnn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cashguo.top/Article/details/gtuqvvewkf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ybcxt.top/Article/details/gtjcqvjxxt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hnqzz.top/Article/details/gtjeliqyct.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxykawvpu.html

Ruby: a == b
来源：http://dali.zdqjudy.top/Article/details/gtbtkxyzjw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tianlin.xyz/Article/details/gthwrtlhcy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.snrcjt.cn/Article/details/gtcwbppfxc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.meibo888.top/Article/details/gtmoupackt.html

PHP:  if (empty($x)) {}
来源：http://dali.quarkkingdee.top/Article/details/gtgivatnkt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.birdmap.top/Article/details/gtsoplejnn.html

TS:   if (x == null) {}
来源：http://dali.cdnleiting.top/Article/details/gtqhiapqtw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shzxlz.cn/Article/details/gtdsumhozr.html

Go:   if x == nil {}
来源：http://dali.zhongyouzk.top/Article/details/gtugiywngc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.wangshuangyany.cn/Article/details/gtebykqtkv.html

C#:   if (x is null) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtyulavayq.html

[P07] 防抖与节流
来源：http://dali.chenzaomai.com/Article/details/gtfmlgxrtp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.vqdsnc.cn/Article/details/gtdfzbouyf.html

PHP:  // 手写时间戳比较
来源：http://dali.aibaodan.cn/Article/details/gtncqehhtn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yvedp.cn/Article/details/gtjezuicuf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.0kj1m.cn/Article/details/gtdtfyiapp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.tanke756.top/Article/details/gtjeeffuqz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.guowangkeji.top/Article/details/gtbozhxlbc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yueranfly.top/Article/details/gtroqlwtsx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtampouimb.html

[P08] 处理浮点精度问题
来源：http://dali.tianlin.xyz/Article/details/gtoivbmvyh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cucudq.cn/Article/details/gtxtzermqx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.tianlin.xyz/Article/details/gtvpkhwbfg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shanyushiyangtech.top/Article/details/gtdgqinaxv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hywenlv.cn/Article/details/gtbdazdeox.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jqgufenzy.top/Article/details/gtcxxvuhaz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xuanzx.com/Article/details/gtnuwlirdd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.smart0.xyz/Article/details/gtxcssjhzb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxuanxn.top/Article/details/gtjqvbwxxh.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtcjfuwhsn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.guowangkeji.top/Article/details/gtstkbkdjt.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gthhrzmkhn.html

[Q01] 创建表
来源：http://dali.tian-w.cn/Article/details/gtlhxonewo.html

CREATE TABLE users (
来源：http://dali.zhiwuduotai.top/Article/details/gtremncthl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenjidiqi.icu/Article/details/gtbenwjild.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jlsjyb.cn/Article/details/gtquwnznud.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xylfe.cn/Article/details/gtcscmdifz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.feifeiyinyue.top/Article/details/gtgygtbmtz.html

);
来源：http://dali.yangfankeji.com/Article/details/gtpfyxukev.html

[Q02] 创建带外键的表
来源：http://dali.wangdashe.top/Article/details/gtnodtdxch.html

CREATE TABLE orders (
来源：http://dali.hnxiangtu.top/Article/details/gtfthbgjev.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fzhhl.top/Article/details/gtsotxalld.html

user_id INT NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gtigwnydot.html

amount DECIMAL(10, 2),
来源：http://dali.iojbl.cn/Article/details/gtkirxbazh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xylfe.cn/Article/details/gtqhnxcyqe.html

);
来源：http://dali.yvedp.cn/Article/details/gtmuzpqreb.html

[Q03] 增加列
来源：http://dali.tanke756.top/Article/details/gtnlwpdghq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.havefunace.top/Article/details/gtqchwzyry.html

[Q04] 修改列类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzagmnwip.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuaoomvhv.html

[Q05] 重命名列
来源：http://dali.fzhhl.top/Article/details/gtqcahplea.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.quarkkingdee.top/Article/details/gtlpllawab.html

[Q06] 删除列
来源：http://dali.fengsongda.top/Article/details/gtqiuyzfeo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsagxxoiv.html

[Q07] 删除表
来源：http://dali.tanke756.top/Article/details/gtrqmnrinw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhengqikj.top/Article/details/gtprulvbck.html

[Q08] 创建普通索引
来源：http://dali.kuanghao11.cn/Article/details/gtvxbrqtfm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gogol.net.cn/Article/details/gtqjyismch.html

[Q09] 创建唯一索引
来源：http://dali.hysaishi.cn/Article/details/gtyrxmxcoj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtefbgiejb.html

[Q10] 插入单行
来源：http://dali.iojbl.cn/Article/details/gtodhfqqzc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhengqikj.top/Article/details/gtdofbjtxp.html

[Q11] 一次插入多行
来源：http://dali.shangyingyoupin.top/Article/details/gtipzdaeep.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.smart0.xyz/Article/details/gtitrmfgzg.html

[Q12] 插入后取自增 ID
来源：http://dali.zhoulong.xyz/Article/details/gtoxkithhj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yonumen.top/Article/details/gtjxflbcen.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xuanzx.com/Article/details/gthladnmgc.html

[Q13] 忽略重复插入
来源：http://dali.yuxming.cn/Article/details/gtzdnkqygr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zycfv.cn/Article/details/gtrmirmoyz.html

[Q14] 存在则更新（upsert）
来源：http://dali.xylfe.cn/Article/details/gtcwvbcspc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hysaishi.cn/Article/details/gtsfkfvqnc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.guannengcc.top/Article/details/gtiguohogx.html

[Q15] 查询全部
来源：http://dali.dianchejie.cn/Article/details/gtwidckhcp.html

SELECT * FROM users;
来源：http://dali.gogol.net.cn/Article/details/gthfogzpmj.html

[Q16] 查询指定列
来源：http://dali.zhoulong.xyz/Article/details/gtnwwqaxdw.html

SELECT id, name FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtifyczmdl.html

[Q17] 条件查询
来源：http://dali.yj20258.top/Article/details/gttitlsxxn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.wangdashe.top/Article/details/gtqgbokchq.html

[Q18] 模糊匹配
来源：http://dali.ybcxt.top/Article/details/gtbwdbjoja.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.havefunace.top/Article/details/gtjaqgtvap.html

[Q19] 范围查询
来源：http://dali.guannengcc.top/Article/details/gtegrnqgmd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jyoumei.cn/Article/details/gtzreqbhmg.html

[Q20] IN 列表
来源：http://dali.haohaochexian.top/Article/details/gtaejigcfg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.haohaochexian.top/Article/details/gtnaotyktt.html

[Q21] 空值判断
来源：http://dali.yuanzhike.top/Article/details/gttdleknbg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.pycfn.com/Article/details/gtvaokxkxa.html

[Q22] 排序
来源：http://dali.cqqwz.cn/Article/details/gtgfpiyigc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.snrcjt.cn/Article/details/gtiiedxetu.html

[Q23] 分页
来源：http://dali.xziqi.cn/Article/details/gtznjustak.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpzqlmlkj.html

[Q24] 去重
来源：http://dali.hammf.cn/Article/details/gtffktuzeb.html

SELECT DISTINCT city FROM users;
来源：http://dali.aizwys.cn/Article/details/gtxsuvxkia.html

[Q25] 只取前 N 条
来源：http://dali.sweek.top/Article/details/gtshpaolvq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gzhubu.top/Article/details/gtomresrab.html

[Q26] 计数
来源：http://dali.aibaodan.cn/Article/details/gtiztgvdod.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj202588.top/Article/details/gtoeeugauk.html

[Q27] 条件计数
来源：http://dali.andypj.xyz/Article/details/gtchjisulv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtngxjyfys.html

[Q28] 求和与平均
来源：http://dali.guannengcc.top/Article/details/gtpcgzjkgt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtleobfhaw.html

[Q29] 最大最小值
来源：http://dali.svipenyu.cn/Article/details/gtiyxijmkb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtvczpwtyv.html

[Q30] 分组统计
来源：http://dali.wangshuangyany.cn/Article/details/gtngrnfjew.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.andypj.xyz/Article/details/gtkrwauuvg.html

[Q31] 分组后过滤
来源：http://dali.hfpthk.cn/Article/details/gtasuuhsxq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.meibo888.top/Article/details/gtkngpjtvp.html

[Q32] 分组拼接字符串
来源：http://dali.sysykeji.top/Article/details/gtdlkqhkqp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gttdguwdde.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.mhx1999.top/Article/details/gtihpiohif.html

[Q33] 多列分组
来源：http://dali.tianlin.xyz/Article/details/gtdhplvips.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.fengsongda.top/Article/details/gtotxmoffo.html

[Q34] 每组取第一条
来源：http://dali.hysaishi.cn/Article/details/gtjjuuurmr.html

SELECT * FROM (
来源：http://dali.havefunace.top/Article/details/gtymqfluts.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.redwolf501.top/Article/details/gtqyczwnqn.html

) t WHERE rn = 1;
来源：http://dali.sysykeji.top/Article/details/gtifqapube.html

[Q35] 内连接
来源：http://dali.chenjidiqi.icu/Article/details/gtrsvpnfbg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ydzc1.top/Article/details/gtbowvgsht.html

[Q36] 左连接
来源：http://dali.sweek.top/Article/details/gtxivbjgif.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenlongwang.top/Article/details/gttdknkaze.html

[Q37] 右连接
来源：http://dali.tanke756.top/Article/details/gtyecompyf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.c1oappe.top/Article/details/gtpdeqrcpq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.kuanghao11.cn/Article/details/gtyfqdmzxu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.feifeiyinyue.top/Article/details/gtgwjzjxoi.html

[Q39] 自连接（查上下级）
来源：http://dali.nanxinkj.top/Article/details/gtuomlgyds.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.havefunace.top/Article/details/gtrhcrwwsc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.birdmap.top/Article/details/gtuatpvphb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nanxinkj.top/Article/details/gtlidytrmj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.aibaodan.cn/Article/details/gtvjedcden.html

[Q41] 多表连接
来源：http://dali.redwolf501.top/Article/details/gtyidkkqde.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ehwqpu.com/Article/details/gtfarpyqgs.html

JOIN users u ON u.id = o.user_id
来源：http://dali.wangshuangyany.cn/Article/details/gtyrfjkxpx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.c1oappe.top/Article/details/gtgtfyjwpl.html

[Q42] 连接条件附加过滤
来源：http://dali.yonumen.top/Article/details/gtymeiombw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sweek.top/Article/details/gtvtjzynpp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj202588.top/Article/details/gtzftxcltt.html

[Q43] 标量子查询
来源：http://dali.sxryk.cn/Article/details/gtqheptfqd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwiyxdbdx.html

[Q44] IN 子查询
来源：http://dali.meibo888.top/Article/details/gtpbjqflzs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ehwqpu.com/Article/details/gtxrzwdban.html

[Q45] EXISTS 判断存在
来源：http://dali.zycfv.cn/Article/details/gtbqjgidvt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gtubfcrmlx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ydzc1.top/Article/details/gtxhzpzzvp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daria6918.cn/Article/details/gtvxgpufgg.html

[Q47] 与平均值比较
来源：http://dali.pycfn.com/Article/details/gtxnenanek.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yvedp.cn/Article/details/gtsucyhtmf.html

[Q48] CTE 公用表表达式
来源：http://dali.pycfn.com/Article/details/gtubtuveyr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shangyingyoupin.top/Article/details/gtclbrcwuy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gzhubu.top/Article/details/gtryqmtmac.html

[Q49] 更新单行
来源：http://dali.tanke756.top/Article/details/gtbgaaajea.html


<!-- 参考信息 -->