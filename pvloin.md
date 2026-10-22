代发 wailian999

Go:   // 手写 map[int]int
来源：http://dali.zhoulong.xyz/Article/details/gtnazrslin.html

Ruby: // 手写 Hash
来源：http://dali.daxiang520.top/Article/details/gtrwdwudir.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.redwolf501.top/Article/details/gthdoyhvvx.html

[N08] 生成全排列
来源：http://dali.yongpay.top/Article/details/gtoeztjzcj.html

Py:   itertools.permutations(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtbanjwkal.html

PHP:  // 手写递归交换
来源：http://dali.hnqzz.top/Article/details/gtahocgevf.html

JS:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtlkkrxcju.html

TS:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtqwbhjvfw.html

Java: // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtratfulbk.html

Go:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtholkjfka.html

Ruby: arr.permutation.to_a
来源：http://dali.tianlin.xyz/Article/details/gtvhogxttb.html

C#:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtvydhbpeu.html

[N09] 栈与队列
来源：http://dali.guowangkeji.top/Article/details/gtarcblovk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nwbrower.top/Article/details/gtmijltuvz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangdashe.top/Article/details/gtstorytqh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gtfvrrxufw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hfpthk.cn/Article/details/gtcmbaxvpm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hammf.cn/Article/details/gtafbmrykg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gotoacloud.top/Article/details/gtpbpadzdn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gtzuvasxay.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ehwqpu.com/Article/details/gtccbzzivo.html

[N10] 链表节点定义
来源：http://dali.zhiwuduotai.top/Article/details/gtthavzsei.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xylfe.cn/Article/details/gttvufnipi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.feifeiyinyue.top/Article/details/gtpzxzqyub.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.daxiang520.top/Article/details/gtrxrjlgma.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gzhubu.top/Article/details/gtwvuknsoc.html

Java: class Node { int v; Node next; }
来源：http://dali.yuxming.cn/Article/details/gtyhriluin.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zdqjudy.top/Article/details/gtfvqncddg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gaohongyu789.top/Article/details/gtmxpghthc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sufxvd.cn/Article/details/gtekrihlkq.html

[N11] 二叉树中序遍历
来源：http://dali.aizwys.cn/Article/details/gtiojylfsp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hnqzz.top/Article/details/gtixyjmaek.html

PHP:  // 手写递归函数
来源：http://dali.yanxiufei.cn/Article/details/gtvxrkowkr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dashuyun.cn/Article/details/gtrhiffdkq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuanzx.com/Article/details/gttuaofzci.html

Java: // 手写递归
来源：http://dali.aizwys.cn/Article/details/gtarypanei.html

Go:   // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtwusroqoz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gotoacloud.top/Article/details/gthwjnaucc.html

C#:   // 手写递归
来源：http://dali.9152youxi.cn/Article/details/gtyrmqfxos.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sufxvd.cn/Article/details/gtlfwgcrob.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hnxiangtu.top/Article/details/gtqocojjrg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.birdmap.top/Article/details/gtezeqytnc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cashguo.top/Article/details/gtaoxkoksg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hammf.cn/Article/details/gtlugjbjaj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangshuangyany.cn/Article/details/gtiteinjqk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sufxvd.cn/Article/details/gtehphkivb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.316326.xyz/Article/details/gttbxjyqad.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ivvv.top/Article/details/gtjqwilkab.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtqtyypgwn.html

O. 并发与异步
来源：http://dali.cheryme.top/Article/details/gtgtbcnhlg.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtxtzexytn.html

[O01] 启动一个线程
来源：http://dali.sufxvd.cn/Article/details/gtyiwacnnd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shuidangran.top/Article/details/gtqerdrwug.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shzxlz.cn/Article/details/gtfcbnvzag.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinghuilouyu.cn/Article/details/gtimrrtmme.html

TS:   // 同 JS
来源：http://dali.jinqigfzy.top/Article/details/gtdgxkepqj.html

Java: new Thread(() -> f()).start()
来源：http://dali.shzxlz.cn/Article/details/gtlwtylmga.html

Go:   go f()
来源：http://dali.jinqigfzy.top/Article/details/gtqpcwvfaf.html

Ruby: Thread.new { f }
来源：http://dali.ydzc1.top/Article/details/gtrdfvftsh.html

C#:   Task.Run(() => F());
来源：http://dali.yj202588.top/Article/details/gtrzejurac.html

[O02] 使用线程池
来源：http://dali.yangfankeji.com/Article/details/gtnhhcrpus.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cheryme.top/Article/details/gtieupplej.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.aibaodan.cn/Article/details/gttpkdbhru.html

JS:   // worker_threads 线程池
来源：http://dali.hywenlv.cn/Article/details/gtpkfiaswj.html

TS:   // worker_threads 线程池
来源：http://dali.9152youxi.cn/Article/details/gtpofywzzl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumlbvoxz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hnqzz.top/Article/details/gtlqsskawu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.andypj.xyz/Article/details/gtgptmsxpx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.dashuyun.cn/Article/details/gtlfzgjqbt.html

[O03] 加锁保护共享数据
来源：http://dali.haohaochexian.top/Article/details/gtnrmjphdb.html

Py:   with lock: shared += 1
来源：http://dali.ybcxt.top/Article/details/gtkcsuyrvc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shzxlz.cn/Article/details/gtgoxmgdpl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gtncpmsjhh.html

TS:   // 同 JS
来源：http://dali.xziqi.cn/Article/details/gtknnfzrug.html

Java: synchronized (this) { shared++; }
来源：http://dali.hammf.cn/Article/details/gtrqpvceot.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yuxming.cn/Article/details/gtlbemdmsv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hnxiangtu.top/Article/details/gtsijclqeq.html

C#:   lock (gate) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjblmxpx.html

[O04] 定义异步函数并等待
来源：http://dali.tanke756.top/Article/details/gtuplqnikg.html

Py:   async def f():⏎    await g()
来源：http://dali.chenlongwang.top/Article/details/gtkshximvo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xuanzx.com/Article/details/gtwreiijrn.html

JS:   async function f() { await g(); }
来源：http://dali.yanxiufei.cn/Article/details/gtrohkxjyo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hfpthk.cn/Article/details/gtdckqsrdc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jqgfzy.top/Article/details/gtwcdzgdpv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yvedp.cn/Article/details/gtmizrtrhr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.dianchejie.cn/Article/details/gtgzzcmrsg.html

C#:   async Task F() { await G(); }
来源：http://dali.yonumen.top/Article/details/gtvcyiehea.html

[O05] 并发执行并等待全部完成
来源：http://dali.gaohongyu789.top/Article/details/gtznpbnpmn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinqigufen.top/Article/details/gtlpgbswkv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sysykeji.top/Article/details/gtwodfhxcu.html

JS:   await Promise.all(tasks)
来源：http://dali.quarkkingdee.top/Article/details/gthfrdyxhq.html

TS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcmkcereg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.kuanghao11.cn/Article/details/gtbaiqyziu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cashguo.top/Article/details/gthmmoozxg.html

Ruby: threads.map(&:join)
来源：http://dali.hongshengwenyu.top/Article/details/gtgyqadymb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinqigufen.top/Article/details/gtpfdlhguc.html

[O06] 使用进程池
来源：http://dali.fzhhl.top/Article/details/gtjgihhkbw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shangyingyoupin.top/Article/details/gtbifnzoyd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtomxlzdwa.html

JS:   // child_process / cluster 模块
来源：http://dali.guowangkeji.top/Article/details/gtbvwluzih.html

TS:   // child_process / cluster 模块
来源：http://dali.nanxuanxn.top/Article/details/gtcnwjskzx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cheryme.top/Article/details/gtcxcbjunq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.feifeiyinyue.top/Article/details/gtkxwzujee.html

Ruby: // fork 块
来源：http://dali.cashguo.top/Article/details/gtzghvsnrp.html

C#:   Parallel.For
来源：http://dali.quarkkingdee.top/Article/details/gtpkzxfcyg.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtebggnxnx.html

P. 常用工具函数
来源：http://dali.chenzaomai.com/Article/details/gtuefyukkk.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtmrxgsblo.html

[P01] 生成 UUID
来源：http://dali.jianghu66.top/Article/details/gtcbrpribb.html

Py:   str(uuid.uuid4())
来源：http://dali.feifeiyinyue.top/Article/details/gtlvxoqces.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.mhx1999.top/Article/details/gtzkheyzxs.html

JS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqgyicuu.html

TS:   crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gthamushcq.html

Java: UUID.randomUUID().toString()
来源：http://dali.nanxuanxn.top/Article/details/gtkorpvvvk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.wangshuangyany.cn/Article/details/gtrldxsigo.html

Ruby: SecureRandom.uuid
来源：http://dali.yuxming.cn/Article/details/gtexpbdfdy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hywenlv.cn/Article/details/gttuaokrnq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xuetiantiany.cn/Article/details/gtwtdqfsae.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.andypj.xyz/Article/details/gtjyvralro.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.vqdsnc.cn/Article/details/gtzjliolvi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cqqwz.cn/Article/details/gtzbgonxzm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xziqi.cn/Article/details/gtnakcjprd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinqigufen.top/Article/details/gtlhiqtbms.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.dashuyun.cn/Article/details/gtxpeyihnb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yongpay.top/Article/details/gtvaguvsrh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.dashuyun.cn/Article/details/gtkbpjiydg.html

[P03] 生成短随机字符串
来源：http://dali.fengsongda.top/Article/details/gtytgxhtmk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.fengsongda.top/Article/details/gtazgvwoib.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.svipenyu.cn/Article/details/gthmaszjfc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gaohongyu789.top/Article/details/gtoskxulzz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jyoumei.cn/Article/details/gtsuzxvqyc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hammf.cn/Article/details/gtawlkblcn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.guowangkeji.top/Article/details/gtjmvdpmto.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hnqzz.top/Article/details/gttyodqnmd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shzxlz.cn/Article/details/gtududmpzx.html

[P04] 求长度
来源：http://dali.iojbl.cn/Article/details/gtrczkfzsu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gogol.net.cn/Article/details/gttdbaiqov.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtbclgjvfy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.9152youxi.cn/Article/details/gtnclrwnbf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sysykeji.top/Article/details/gtwuzwpffe.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shzxlz.cn/Article/details/gtrqhvbxee.html

Go:   len(arr);  len(m)
来源：http://dali.mhx1999.top/Article/details/gtdtqbthcj.html

Ruby: x.length;  x.size
来源：http://dali.vqdsnc.cn/Article/details/gtkccgvfqf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tianlin.xyz/Article/details/gtmfyhrwhj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jlsjyb.cn/Article/details/gtsjntfkfw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.vqdsnc.cn/Article/details/gtguhfkyyg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.tianlin.xyz/Article/details/gttwttcgcv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhengqikj.top/Article/details/gtutfgucvb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnxiangtu.top/Article/details/gtqlgijhvv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yongpay.top/Article/details/gtpsrhpagb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinqigufen.top/Article/details/gtczhcpzvt.html

Ruby: a == b
来源：http://dali.svipenyu.cn/Article/details/gtefrlanni.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmjpjlga.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhiwuduotai.top/Article/details/gtvqlprrhd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jiagoushi.top/Article/details/gtxfdwnmgl.html

PHP:  if (empty($x)) {}
来源：http://dali.mhx1999.top/Article/details/gthjirjnjr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenzaomai.com/Article/details/gtqwfewzzz.html

TS:   if (x == null) {}
来源：http://dali.sufxvd.cn/Article/details/gtbtgxdzep.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.iojbl.cn/Article/details/gtjhubqokw.html

Go:   if x == nil {}
来源：http://dali.zhoulong.xyz/Article/details/gtrgjjhkoc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ivvv.top/Article/details/gtgdkzmzjm.html

C#:   if (x is null) {}
来源：http://dali.ydzc1.top/Article/details/gtxytvhrmv.html

[P07] 防抖与节流
来源：http://dali.gzhubu.top/Article/details/gttkfwvqmk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhengqikj.top/Article/details/gtndfpblyc.html

PHP:  // 手写时间戳比较
来源：http://dali.hfpthk.cn/Article/details/gtwwjgoesf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtmddkqknv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.316326.xyz/Article/details/gtcwiepzqb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.bjfxy.top/Article/details/gttuiotlrr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.bjfxy.top/Article/details/gthqgzqaqb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jqgufenzy.top/Article/details/gtuiebjpuw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yangfankeji.com/Article/details/gtfcyqurce.html

[P08] 处理浮点精度问题
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakxqxowa.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jqgfzy.top/Article/details/gtovoyahph.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ydzc1.top/Article/details/gtnxmcskdg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.chenlongwang.top/Article/details/gtjnroxury.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ydzc1.top/Article/details/gtquikjegs.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.wangdashe.top/Article/details/gtyujdbkmz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.haohaochexian.top/Article/details/gtabfvnfae.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.bjfxy.top/Article/details/gtegddjmmn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlcoxjuum.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtwqibpvaw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxjpdncv.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtwcvcwocj.html

[Q01] 创建表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdmlfqymp.html

CREATE TABLE users (
来源：http://dali.gzhubu.top/Article/details/gtnotbapjb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj20258888.top/Article/details/gtzjplxdwg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gzhubu.top/Article/details/gtizzlbydt.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hywenlv.cn/Article/details/gtecxbwawk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yongpay.top/Article/details/gtrgrjzjnl.html

);
来源：http://dali.jiagoushi.top/Article/details/gtpuxpxwyj.html

[Q02] 创建带外键的表
来源：http://dali.aizwys.cn/Article/details/gtnkaufbob.html

CREATE TABLE orders (
来源：http://dali.tian-w.cn/Article/details/gtnxozknol.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hfpthk.cn/Article/details/gtyjmcssbq.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gtbhdvbfns.html

amount DECIMAL(10, 2),
来源：http://dali.daxiang520.top/Article/details/gtnmvxsanu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yonumen.top/Article/details/gtztmcsybb.html

);
来源：http://dali.zhixingplan.top/Article/details/gtaljjugvl.html

[Q03] 增加列
来源：http://dali.mhx1999.top/Article/details/gtuhjuevuh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jqgfzy.top/Article/details/gttuhzlilg.html

[Q04] 修改列类型
来源：http://dali.fengsongda.top/Article/details/gttcxsuzhx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj20258888.top/Article/details/gtazwjbosa.html

[Q05] 重命名列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxncmkrpi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.guowangkeji.top/Article/details/gtsxxakxvt.html

[Q06] 删除列
来源：http://dali.jiagoushi.top/Article/details/gtwovixxpv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.iojbl.cn/Article/details/gtckgevegj.html

[Q07] 删除表
来源：http://dali.aibaodan.cn/Article/details/gtjmgtkhev.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gaohongyu789.top/Article/details/gtedpjzflb.html

[Q08] 创建普通索引
来源：http://dali.yueranfly.top/Article/details/gtjvcvpdgy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj202588.top/Article/details/gtfynaavgt.html

[Q09] 创建唯一索引
来源：http://dali.yongpay.top/Article/details/gtglxdvmcy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cdnleiting.top/Article/details/gtlamxwwul.html

[Q10] 插入单行
来源：http://dali.shanyushiyangtech.top/Article/details/gtxispkcxc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.316326.xyz/Article/details/gtctzasgwu.html

[Q11] 一次插入多行
来源：http://dali.xziqi.cn/Article/details/gtlfgjjkbu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gotoacloud.top/Article/details/gtupxwdpuf.html

[Q12] 插入后取自增 ID
来源：http://dali.bjfxy.top/Article/details/gthgkogrja.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tian-w.cn/Article/details/gtodkwwkgt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.kuanghao11.cn/Article/details/gtszixdvzh.html

[Q13] 忽略重复插入
来源：http://dali.jyoumei.cn/Article/details/gtiiescmqe.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gtkmnveolq.html

[Q14] 存在则更新（upsert）
来源：http://dali.hongshengwenyu.top/Article/details/gtwvuyckze.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj202588.top/Article/details/gtlooqbfwx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.vqdsnc.cn/Article/details/gtsaqgdbnj.html

[Q15] 查询全部
来源：http://dali.hfpthk.cn/Article/details/gtzawuaiwt.html

SELECT * FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyculqexg.html

[Q16] 查询指定列
来源：http://dali.smart0.xyz/Article/details/gtenzscwgt.html

SELECT id, name FROM users;
来源：http://dali.iojbl.cn/Article/details/gtkqtxcztz.html

[Q17] 条件查询
来源：http://dali.ybcxt.top/Article/details/gtzmkqsfmp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtvmkoeblq.html

[Q18] 模糊匹配
来源：http://dali.daria6918.cn/Article/details/gtsgxyvvcn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinqigufen.top/Article/details/gtytzppzjn.html

[Q19] 范围查询
来源：http://dali.wangdashe.top/Article/details/gtbvjgagvo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenjidiqi.icu/Article/details/gtcxpmrcrn.html

[Q20] IN 列表
来源：http://dali.sysykeji.top/Article/details/gtbqzfwdgc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtlxxzvmie.html

[Q21] 空值判断
来源：http://dali.zhongyouzk.top/Article/details/gtwwrymwxz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.aibaodan.cn/Article/details/gtvcjitzxe.html

[Q22] 排序
来源：http://dali.yuanzhike.top/Article/details/gtqbibrxjd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtfgrzjf.html

[Q23] 分页
来源：http://dali.sufxvd.cn/Article/details/gtnockemfa.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hysaishi.cn/Article/details/gtyfnhfumj.html

[Q24] 去重
来源：http://dali.jqgufenzy.top/Article/details/gtjptyakjq.html

SELECT DISTINCT city FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtdmmksjab.html

[Q25] 只取前 N 条
来源：http://dali.jinqigufen.top/Article/details/gtqgpdfzxf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhiwuduotai.top/Article/details/gteibspeeu.html

[Q26] 计数
来源：http://dali.316326.xyz/Article/details/gtchzopknw.html

SELECT COUNT(*) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtelmnmkqv.html

[Q27] 条件计数
来源：http://dali.ybcxt.top/Article/details/gtyaojhpkm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtfnoriwpm.html

[Q28] 求和与平均
来源：http://dali.sweek.top/Article/details/gtbibycnpl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyptzlzdl.html

[Q29] 最大最小值
来源：http://dali.tianlin.xyz/Article/details/gtywshpion.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtulwzglod.html

[Q30] 分组统计
来源：http://dali.jqgfzy.top/Article/details/gtbqiaqwya.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ivvv.top/Article/details/gtvltjpxyi.html

[Q31] 分组后过滤
来源：http://dali.yuanzhike.top/Article/details/gtwecxlmnu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jyoumei.cn/Article/details/gtatlkvyie.html

[Q32] 分组拼接字符串
来源：http://dali.birdmap.top/Article/details/gtyvthupgs.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gtmrahcjfn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jiagoushi.top/Article/details/gtjrwptnpi.html

[Q33] 多列分组
来源：http://dali.dianchejie.cn/Article/details/gtpkgnfqia.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hnqzz.top/Article/details/gtvkzflzsf.html

[Q34] 每组取第一条
来源：http://dali.svipenyu.cn/Article/details/gtmfpvbtra.html

SELECT * FROM (
来源：http://dali.mhx1999.top/Article/details/gtljcfzcqv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tianlin.xyz/Article/details/gtdotelyuy.html

) t WHERE rn = 1;
来源：http://dali.guannengcc.top/Article/details/gttgclaeiq.html

[Q35] 内连接
来源：http://dali.yvedp.cn/Article/details/gthuztevdl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cdnleiting.top/Article/details/gtlacfdwqt.html

[Q36] 左连接
来源：http://dali.iojbl.cn/Article/details/gtjseyiuhz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigfzy.top/Article/details/gtxbzcaeid.html

[Q37] 右连接
来源：http://dali.smart0.xyz/Article/details/gtbdzmvavp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tanke756.top/Article/details/gtdecmqcfm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xylfe.cn/Article/details/gtytowtkfi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj20258.top/Article/details/gtpyuloyuw.html

[Q39] 自连接（查上下级）
来源：http://dali.wangshuangyany.cn/Article/details/gtnskulxwx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.316326.xyz/Article/details/gtqeklcjqs.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jqgfzy.top/Article/details/gtqbogjaoo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tanke756.top/Article/details/gtkwdekdax.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ybcxt.top/Article/details/gtiesohxfp.html

[Q41] 多表连接
来源：http://dali.chenzaomai.com/Article/details/gtyxpwyvwk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.daxiang520.top/Article/details/gtrjuvqybu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shanyushiyangkeji.top/Article/details/gtruypbqfq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.dashuyun.cn/Article/details/gtglmwaspf.html

[Q42] 连接条件附加过滤
来源：http://dali.shangyingyoupin.top/Article/details/gtsucszbsp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xziqi.cn/Article/details/gtplgqgawx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cucudq.cn/Article/details/gtxtwbwdag.html

[Q43] 标量子查询
来源：http://dali.xinyue.icu/Article/details/gtmojwlsrv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhiwuduotai.top/Article/details/gtusjfnflk.html

[Q44] IN 子查询
来源：http://dali.fengsongda.top/Article/details/gtadiencog.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jqgfzy.top/Article/details/gtgxowbrkp.html

[Q45] EXISTS 判断存在
来源：http://dali.meibo888.top/Article/details/gtnprdghpi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.havefunace.top/Article/details/gtoqxmktcn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shzxlz.cn/Article/details/gtpswpmyqm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258.top/Article/details/gtrcxaijam.html

[Q47] 与平均值比较
来源：http://dali.redwolf501.top/Article/details/gtagddcgrf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhongyouzk.top/Article/details/gtxyswmnih.html

[Q48] CTE 公用表表达式
来源：http://dali.jyoumei.cn/Article/details/gtlxmuglqa.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.dianchejie.cn/Article/details/gtcijvuaox.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nwbrower.top/Article/details/gtxrwrtjmi.html

[Q49] 更新单行
来源：http://dali.pycfn.com/Article/details/gtineiwqlz.html


<!-- 参考信息 -->