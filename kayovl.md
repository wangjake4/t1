代发 wailian999

Ruby: s == s.reverse
来源：http://dali.zhengqikj.top/Article/details/gtcurtszvq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cqqwz.cn/Article/details/gtfwzzytok.html

[N07] 两数之和（返回下标）
来源：http://dali.shzxlz.cn/Article/details/gtpifeygpp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ywan-chungtsiang.top/Article/details/gtheqwhmjw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.fzhhl.top/Article/details/gtblovddto.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xuanzx.com/Article/details/gtdjphsnqw.html

TS:   // 手写 Map<string, number>
来源：http://dali.tian-w.cn/Article/details/gtlrsxrbbc.html

Java: // 手写 HashMap
来源：http://dali.mhx1999.top/Article/details/gtxtvruhqg.html

Go:   // 手写 map[int]int
来源：http://dali.ivvv.top/Article/details/gtophjzfhi.html

Ruby: // 手写 Hash
来源：http://dali.wangshuangyany.cn/Article/details/gtabrgbfiz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.bjfxy.top/Article/details/gtmdpzyrlp.html

[N08] 生成全排列
来源：http://dali.cqqwz.cn/Article/details/gtiiormwtu.html

Py:   itertools.permutations(arr)
来源：http://dali.ybcxt.top/Article/details/gtkcfabxyz.html

PHP:  // 手写递归交换
来源：http://dali.ybcxt.top/Article/details/gtmxgychsa.html

JS:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gteruknaek.html

TS:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtwqxmnnzy.html

Java: // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtxbmpnrco.html

Go:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtfromgqqp.html

Ruby: arr.permutation.to_a
来源：http://dali.xylfe.cn/Article/details/gthwcrcpoy.html

C#:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtojcriuou.html

[N09] 栈与队列
来源：http://dali.svipenyu.cn/Article/details/gtenbgkbll.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hywenlv.cn/Article/details/gtyqpqlfuf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtkcpcqirb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj20258.top/Article/details/gtejtkvnll.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gotoacloud.top/Article/details/gthttgthjb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenlongwang.top/Article/details/gtbdhddvoy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.pycfn.com/Article/details/gtraegsdzw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj20258.top/Article/details/gtpjttmkjs.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.feifeiyinyue.top/Article/details/gtvptirivn.html

[N10] 链表节点定义
来源：http://dali.yongpay.top/Article/details/gtkzjvtsmm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinqigfzy.top/Article/details/gtmptcgorh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hammf.cn/Article/details/gtchtassle.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jlsjyb.cn/Article/details/gtmflgjkdu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xuetiantiany.cn/Article/details/gtuwacgyxw.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258888.top/Article/details/gtpyqpidcj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shangyingyoupin.top/Article/details/gtbwsqcsqb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yvedp.cn/Article/details/gtgpsksnko.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.dianchejie.cn/Article/details/gtxrldbziw.html

[N11] 二叉树中序遍历
来源：http://dali.zycfv.cn/Article/details/gtslsbfeyr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.9152youxi.cn/Article/details/gtnddqnawe.html

PHP:  // 手写递归函数
来源：http://dali.guannengcc.top/Article/details/gticrotuys.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.iojbl.cn/Article/details/gtkxvlosbq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jyoumei.cn/Article/details/gtghlxhmfx.html

Java: // 手写递归
来源：http://dali.ydzc1.top/Article/details/gtnmizexxc.html

Go:   // 手写递归
来源：http://dali.hnxiangtu.top/Article/details/gteavvrtqp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jiagoushi.top/Article/details/gthfnuhdnz.html

C#:   // 手写递归
来源：http://dali.gzhubu.top/Article/details/gttogqaqww.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gotoacloud.top/Article/details/gthzbxguzt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.wangshuangyany.cn/Article/details/gtmlfsxclr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenjidiqi.icu/Article/details/gtlvycfwdk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.redwolf501.top/Article/details/gtaucewiye.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gtquctktfz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cdnleiting.top/Article/details/gtdzhptqvh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yuxming.cn/Article/details/gtkttyndpo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jqgfzy.top/Article/details/gtupbaeqzj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenjidiqi.icu/Article/details/gtusiacdsq.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtkjuallmr.html

O. 并发与异步
来源：http://dali.sweek.top/Article/details/gtbuwpkmry.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtxpglaowy.html

[O01] 启动一个线程
来源：http://dali.xylfe.cn/Article/details/gtpfmzseug.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.wangdashe.top/Article/details/gtsllpnnsp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.316326.xyz/Article/details/gtdaekbttk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xinyue.icu/Article/details/gtizrnnacw.html

TS:   // 同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsffbygag.html

Java: new Thread(() -> f()).start()
来源：http://dali.snrcjt.cn/Article/details/gtphebfuzq.html

Go:   go f()
来源：http://dali.quarkkingdee.top/Article/details/gtxwzkxcvu.html

Ruby: Thread.new { f }
来源：http://dali.jqgufenzy.top/Article/details/gtmhigrvnq.html

C#:   Task.Run(() => F());
来源：http://dali.zhoulong.xyz/Article/details/gtroehdebz.html

[O02] 使用线程池
来源：http://dali.cdnleiting.top/Article/details/gtorzjngzw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxuanxn.top/Article/details/gtaqxkkpvp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhoulong.xyz/Article/details/gtvgyowtgs.html

JS:   // worker_threads 线程池
来源：http://dali.hywenlv.cn/Article/details/gtbyuquqlv.html

TS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gtbuvjmebg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jiagoushi.top/Article/details/gtmeivtfnu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hysaishi.cn/Article/details/gtlkukonvg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hysaishi.cn/Article/details/gtbimlvayl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hnqzz.top/Article/details/gtjglwimkv.html

[O03] 加锁保护共享数据
来源：http://dali.jinqigfzy.top/Article/details/gtxmttnwss.html

Py:   with lock: shared += 1
来源：http://dali.shuidangran.top/Article/details/gtvvftmxgb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tanke756.top/Article/details/gtcmmenasu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ivvv.top/Article/details/gtyrqvektv.html

TS:   // 同 JS
来源：http://dali.gogol.net.cn/Article/details/gtmnjlvicg.html

Java: synchronized (this) { shared++; }
来源：http://dali.snrcjt.cn/Article/details/gtoowuqgdi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ppjwa.cn/Article/details/gtuyzxxcmj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.daria6918.cn/Article/details/gtohyalgzy.html

C#:   lock (gate) { shared++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyxwbffrz.html

[O04] 定义异步函数并等待
来源：http://dali.hongshengwenyu.top/Article/details/gtgkjzkmth.html

Py:   async def f():⏎    await g()
来源：http://dali.vqdsnc.cn/Article/details/gtawfqeioo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hnxiangtu.top/Article/details/gtrakkatmm.html

JS:   async function f() { await g(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtrqftmyjp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shuidangran.top/Article/details/gtwggmjrzs.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shzxlz.cn/Article/details/gtrwoynjmq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yangfankeji.com/Article/details/gtrhhnwduc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sxryk.cn/Article/details/gtydtmtehv.html

C#:   async Task F() { await G(); }
来源：http://dali.fengsongda.top/Article/details/gtnuoegqpz.html

[O05] 并发执行并等待全部完成
来源：http://dali.gzhubu.top/Article/details/gtofytrerd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cucudq.cn/Article/details/gtspxstyey.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.wangdashe.top/Article/details/gtyqgrdzts.html

JS:   await Promise.all(tasks)
来源：http://dali.xylfe.cn/Article/details/gtrcuttxin.html

TS:   await Promise.all(tasks)
来源：http://dali.haohaochexian.top/Article/details/gtjhmeyhcq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwawjnxo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj202588.top/Article/details/gtbrejlenu.html

Ruby: threads.map(&:join)
来源：http://dali.yueranfly.top/Article/details/gtrwepxcte.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.havefunace.top/Article/details/gtgyshnplf.html

[O06] 使用进程池
来源：http://dali.birdmap.top/Article/details/gtsnmnuxyl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fzhhl.top/Article/details/gtpjqsrkhg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlhytdoar.html

JS:   // child_process / cluster 模块
来源：http://dali.jyoumei.cn/Article/details/gtnoyvbuya.html

TS:   // child_process / cluster 模块
来源：http://dali.zhixingplan.top/Article/details/gtxsqtrlzm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hysaishi.cn/Article/details/gtxavhyfjr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ydzc1.top/Article/details/gttfgmjajx.html

Ruby: // fork 块
来源：http://dali.zhixingplan.top/Article/details/gtltivqfdh.html

C#:   Parallel.For
来源：http://dali.zhiwuduotai.top/Article/details/gtwjanuufy.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtaxnrmtbo.html

P. 常用工具函数
来源：http://dali.ydzc1.top/Article/details/gtgcubcqei.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtvfdloicy.html

[P01] 生成 UUID
来源：http://dali.chenjidiqi.icu/Article/details/gtsywwmrsb.html

Py:   str(uuid.uuid4())
来源：http://dali.daxiang520.top/Article/details/gtriowhvsx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tianlin.xyz/Article/details/gtipzstusi.html

JS:   crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gthpqnfjzf.html

TS:   crypto.randomUUID()
来源：http://dali.dianchejie.cn/Article/details/gtrjtdvzxx.html

Java: UUID.randomUUID().toString()
来源：http://dali.yangfankeji.com/Article/details/gtsdzfcldm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ybcxt.top/Article/details/gtgtbbbxme.html

Ruby: SecureRandom.uuid
来源：http://dali.daria6918.cn/Article/details/gtvlyvlhth.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ydzc1.top/Article/details/gtwfkmlvcc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cashguo.top/Article/details/gtypcithhv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yonumen.top/Article/details/gtnvnqxhgy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.redwolf501.top/Article/details/gtclvumhyx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.vqdsnc.cn/Article/details/gtuweqsdsk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nanxinkj.top/Article/details/gtjeqcqthz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.guowangkeji.top/Article/details/gtugwjwesh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.0kj1m.cn/Article/details/gtvxupiamu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xziqi.cn/Article/details/gtsmzukpag.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmjbawyv.html

[P03] 生成短随机字符串
来源：http://dali.guowangkeji.top/Article/details/gtqjqqovwv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cucudq.cn/Article/details/gtdnyrrkio.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cheryme.top/Article/details/gthyhkzfla.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.havefunace.top/Article/details/gtgihsbnsq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj202588.top/Article/details/gtujgpavxm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.redwolf501.top/Article/details/gthevtufuf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jiagoushi.top/Article/details/gtsimkdjuy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gogol.net.cn/Article/details/gttcjgekuq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cucudq.cn/Article/details/gttjmpnevt.html

[P04] 求长度
来源：http://dali.smart0.xyz/Article/details/gtmmrdsvjf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nanxinkj.top/Article/details/gtdczeggxl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gtsewchjcz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shzxlz.cn/Article/details/gtyjewclfb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwewohgxl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sxryk.cn/Article/details/gtorztingc.html

Go:   len(arr);  len(m)
来源：http://dali.chenlongwang.top/Article/details/gtxtqhoyev.html

Ruby: x.length;  x.size
来源：http://dali.gogol.net.cn/Article/details/gtklwtjqmc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ydzc1.top/Article/details/gtguzjshvs.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yanxiufei.cn/Article/details/gtvnmqyujb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shanyushiyangtech.top/Article/details/gtiaeqfuwx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shzxlz.cn/Article/details/gtwyvbkvtg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.birdmap.top/Article/details/gteyrluftf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenlongwang.top/Article/details/gtazsdkfvi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.pycfn.com/Article/details/gtelgorfbc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gtfhqswidr.html

Ruby: a == b
来源：http://dali.hnxiangtu.top/Article/details/gtfxmrbbvs.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tanke756.top/Article/details/gtphohyopa.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.haohaochexian.top/Article/details/gtnnupjpas.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.wangdashe.top/Article/details/gtuarnntwv.html

PHP:  if (empty($x)) {}
来源：http://dali.shzxlz.cn/Article/details/gtvzcolyxx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gtspyvogcn.html

TS:   if (x == null) {}
来源：http://dali.xinyue.icu/Article/details/gtmrqknctk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinqigfzy.top/Article/details/gtuhvkufox.html

Go:   if x == nil {}
来源：http://dali.andypj.xyz/Article/details/gtmekfvoar.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zycfv.cn/Article/details/gtcxhedgef.html

C#:   if (x is null) {}
来源：http://dali.yj202588.top/Article/details/gtgcsyjlur.html

[P07] 防抖与节流
来源：http://dali.xylfe.cn/Article/details/gtanspduxq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gtiacerqtd.html

PHP:  // 手写时间戳比较
来源：http://dali.yj202588.top/Article/details/gtjyuqzlhg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.meibo888.top/Article/details/gtfpoxwmur.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.vqdsnc.cn/Article/details/gtjxopjnvy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj202588.top/Article/details/gtizooomav.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.wangdashe.top/Article/details/gtyyepdinv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shzxlz.cn/Article/details/gtqatnqyxh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hongshengwenyu.top/Article/details/gtuqsnedbp.html

[P08] 处理浮点精度问题
来源：http://dali.guannengcc.top/Article/details/gtjtpsszkl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.9152youxi.cn/Article/details/gtykjbduxa.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ehwqpu.com/Article/details/gtxqmotsld.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.guannengcc.top/Article/details/gtdguazbrr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhoulong.xyz/Article/details/gtlkgquexp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ivvv.top/Article/details/gtjpwburgj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hammf.cn/Article/details/gtffytkblt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.c1oappe.top/Article/details/gtfblkhnwv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xuanzx.com/Article/details/gtyxuxddkd.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gttwrdlwss.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gogol.net.cn/Article/details/gtbjmglmnd.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtrecevcrk.html

[Q01] 创建表
来源：http://dali.zycfv.cn/Article/details/gtbvuqhirj.html

CREATE TABLE users (
来源：http://dali.sxryk.cn/Article/details/gthqgbqnqg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pengpengdd.cyou/Article/details/gtezxosbqq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.c1oappe.top/Article/details/gtwwsyayug.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hfpthk.cn/Article/details/gtxpzubqna.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.316326.xyz/Article/details/gtcaaiabbd.html

);
来源：http://dali.cheryme.top/Article/details/gtxosubgmx.html

[Q02] 创建带外键的表
来源：http://dali.sufxvd.cn/Article/details/gtupltjiaa.html

CREATE TABLE orders (
来源：http://dali.yuxming.cn/Article/details/gtjsstcndn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cdnleiting.top/Article/details/gtybzxwsbc.html

user_id INT NOT NULL,
来源：http://dali.jiagoushi.top/Article/details/gtuwbwkryn.html

amount DECIMAL(10, 2),
来源：http://dali.birdmap.top/Article/details/gtkiytfvnx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ehwqpu.com/Article/details/gteuyrpyxr.html

);
来源：http://dali.tian-w.cn/Article/details/gtzpjruppk.html

[Q03] 增加列
来源：http://dali.xinyue.icu/Article/details/gtzgcgovgv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hysaishi.cn/Article/details/gtwklaxkve.html

[Q04] 修改列类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxalikcm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ehwqpu.com/Article/details/gtxooigbwo.html

[Q05] 重命名列
来源：http://dali.shzxlz.cn/Article/details/gtpvaljvxm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhengqikj.top/Article/details/gtrowobsef.html

[Q06] 删除列
来源：http://dali.redwolf501.top/Article/details/gtzckdhcfp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.redwolf501.top/Article/details/gtbmhmchgr.html

[Q07] 删除表
来源：http://dali.cucudq.cn/Article/details/gtztrzrnqz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.aizwys.cn/Article/details/gtiawmvxyq.html

[Q08] 创建普通索引
来源：http://dali.yongpay.top/Article/details/gtnsxrlvju.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ehwqpu.com/Article/details/gtthqixgib.html

[Q09] 创建唯一索引
来源：http://dali.andypj.xyz/Article/details/gtywmjokmb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gttplahpvr.html

[Q10] 插入单行
来源：http://dali.tanke756.top/Article/details/gtalutmyuw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sysykeji.top/Article/details/gtxvlozjtq.html

[Q11] 一次插入多行
来源：http://dali.tian-w.cn/Article/details/gtecaijoqt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuqappfja.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvshidwoz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.mhx1999.top/Article/details/gtdrdyfynq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.daxiang520.top/Article/details/gtsnwbxlct.html

[Q13] 忽略重复插入
来源：http://dali.guannengcc.top/Article/details/gtvnwuywmz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yuanzhike.top/Article/details/gtpgbyawgw.html

[Q14] 存在则更新（upsert）
来源：http://dali.xuanzx.com/Article/details/gtrrduoirb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yanxiufei.cn/Article/details/gtamecsdjv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cheryme.top/Article/details/gtrzluukua.html

[Q15] 查询全部
来源：http://dali.dashuyun.cn/Article/details/gtwzexqvku.html

SELECT * FROM users;
来源：http://dali.yueranfly.top/Article/details/gttwuaapwf.html

[Q16] 查询指定列
来源：http://dali.jqgfzy.top/Article/details/gtcmkdwtxl.html

SELECT id, name FROM users;
来源：http://dali.daria6918.cn/Article/details/gtteihqpkj.html

[Q17] 条件查询
来源：http://dali.chenjidiqi.icu/Article/details/gtgmwnbxgo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj202588.top/Article/details/gtmxhqzmsc.html

[Q18] 模糊匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtskrxopsz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.meibo888.top/Article/details/gtgkqhvwbs.html

[Q19] 范围查询
来源：http://dali.zhongyouzk.top/Article/details/gtjopntghm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.feifeiyinyue.top/Article/details/gtwfexgubm.html

[Q20] IN 列表
来源：http://dali.fzhhl.top/Article/details/gtrfrztkbf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.316326.xyz/Article/details/gtqtbvoaoh.html

[Q21] 空值判断
来源：http://dali.xylfe.cn/Article/details/gtjrsqadil.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hongshengwenyu.top/Article/details/gtpxdvwkqf.html

[Q22] 排序
来源：http://dali.meibo888.top/Article/details/gtsaxmefry.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yangfankeji.com/Article/details/gtlmvvszsl.html

[Q23] 分页
来源：http://dali.tianlin.xyz/Article/details/gtsrlwpocd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj20258.top/Article/details/gtbzjulene.html

[Q24] 去重
来源：http://dali.fzhhl.top/Article/details/gtrqmtbdxp.html

SELECT DISTINCT city FROM users;
来源：http://dali.yueranfly.top/Article/details/gtuwiiqmpc.html

[Q25] 只取前 N 条
来源：http://dali.fengsongda.top/Article/details/gtfexbbcyf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhoulong.xyz/Article/details/gttniqlceh.html

[Q26] 计数
来源：http://dali.jinqigufen.top/Article/details/gtiegfxbzm.html

SELECT COUNT(*) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gthxiydnof.html

[Q27] 条件计数
来源：http://dali.yj20258888.top/Article/details/gtfwkhacrp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtakmcsryg.html

[Q28] 求和与平均
来源：http://dali.jinyuanbaomall.cn/Article/details/gthkutzxhj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtexsnlwpt.html

[Q29] 最大最小值
来源：http://dali.aibaodan.cn/Article/details/gtbqqmzyky.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtttvjlhsj.html

[Q30] 分组统计
来源：http://dali.sysykeji.top/Article/details/gtjszyllga.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ivvv.top/Article/details/gtvaujihbk.html

[Q31] 分组后过滤
来源：http://dali.cheryme.top/Article/details/gteaycegbn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.c1oappe.top/Article/details/gtwxdhzauk.html

[Q32] 分组拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gtgetbuear.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gtybxqoabj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hywenlv.cn/Article/details/gtvgihheau.html

[Q33] 多列分组
来源：http://dali.jqgufenzy.top/Article/details/gtzelbjdqe.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sufxvd.cn/Article/details/gtemawnukh.html

[Q34] 每组取第一条
来源：http://dali.sweek.top/Article/details/gtkyzyvlev.html

SELECT * FROM (
来源：http://dali.yonumen.top/Article/details/gtapafxwwd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhiwuduotai.top/Article/details/gtkbynabot.html

) t WHERE rn = 1;
来源：http://dali.bjfxy.top/Article/details/gtmfdigdpi.html

[Q35] 内连接
来源：http://dali.nanxuanxn.top/Article/details/gtasjdwnij.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxinkj.top/Article/details/gtoqmncqyq.html

[Q36] 左连接
来源：http://dali.9152youxi.cn/Article/details/gtxyskirsa.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cheryme.top/Article/details/gtrtuoshpm.html

[Q37] 右连接
来源：http://dali.yvedp.cn/Article/details/gtoorozhth.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.birdmap.top/Article/details/gtglumuttt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jyoumei.cn/Article/details/gtigfrwauf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.fengsongda.top/Article/details/gtkmyfqsll.html

[Q39] 自连接（查上下级）
来源：http://dali.quarkkingdee.top/Article/details/gtkaxxstgx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinqigufen.top/Article/details/gtytvqqttz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.fzhhl.top/Article/details/gtwigktrfn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhixingplan.top/Article/details/gtiitshcmb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tanke756.top/Article/details/gtxcadgdsj.html

[Q41] 多表连接
来源：http://dali.yuxming.cn/Article/details/gtzpzjasyl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebazeqdi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shanyushiyangtech.top/Article/details/gtyffrafhd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinqigufen.top/Article/details/gtabcpjblj.html

[Q42] 连接条件附加过滤
来源：http://dali.zhengqikj.top/Article/details/gtwcfdsxze.html

SELECT u.name, o.amount FROM users u
来源：http://dali.pycfn.com/Article/details/gtzwbpqezb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gzhubu.top/Article/details/gtolztaipx.html

[Q43] 标量子查询
来源：http://dali.316326.xyz/Article/details/gtiycxmkzd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sysykeji.top/Article/details/gtjdfijpfw.html

[Q44] IN 子查询
来源：http://dali.yueranfly.top/Article/details/gtccfieqbc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.havefunace.top/Article/details/gtapsoqrgn.html

[Q45] EXISTS 判断存在
来源：http://dali.jyoumei.cn/Article/details/gtbmfeerfk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tanke756.top/Article/details/gtphfamnyr.html


<!-- 参考信息 -->