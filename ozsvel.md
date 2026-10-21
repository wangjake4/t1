代发 wailian999

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sufxvd.cn/Article/details/gtapgdecvt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhongyouzk.top/Article/details/gtcbgriiyi.html

TS:   // 手写 Map<string, number>
来源：http://dali.hnqzz.top/Article/details/gttohwgyqu.html

Java: // 手写 HashMap
来源：http://dali.xylfe.cn/Article/details/gtjmokjrcu.html

Go:   // 手写 map[int]int
来源：http://dali.jinghuilouyu.cn/Article/details/gtrppbshlv.html

Ruby: // 手写 Hash
来源：http://dali.meibo888.top/Article/details/gtwjrdejwp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.daria6918.cn/Article/details/gttvtzmpzv.html

[N08] 生成全排列
来源：http://dali.pycfn.com/Article/details/gtlfoxosjb.html

Py:   itertools.permutations(arr)
来源：http://dali.hfpthk.cn/Article/details/gtlfyypuun.html

PHP:  // 手写递归交换
来源：http://dali.shangyingyoupin.top/Article/details/gttzaxnnrh.html

JS:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtdcwnvcsf.html

TS:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtdiknpgmw.html

Java: // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtzdwsfyur.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtmklprrwq.html

Ruby: arr.permutation.to_a
来源：http://dali.cashguo.top/Article/details/gtmvbsbadb.html

C#:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gturecscnb.html

[N09] 栈与队列
来源：http://dali.c1oappe.top/Article/details/gttpcqudbj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenzaomai.com/Article/details/gtuzaqhrfj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nwbrower.top/Article/details/gtjgxsifoy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gtushflrgd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.snrcjt.cn/Article/details/gtosymadag.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtqhyuixjm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtriiyzmta.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zycfv.cn/Article/details/gtuobargig.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenjidiqi.icu/Article/details/gthslmtrrt.html

[N10] 链表节点定义
来源：http://dali.shuidangran.top/Article/details/gttpyukvng.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.9152youxi.cn/Article/details/gtbevomlzp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gtoinefuwx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.kuanghao11.cn/Article/details/gtuhnbehbq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.smart0.xyz/Article/details/gtpxypaugy.html

Java: class Node { int v; Node next; }
来源：http://dali.shuidangran.top/Article/details/gtiwhcpvnx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yvedp.cn/Article/details/gtnawdfkel.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.bjfxy.top/Article/details/gtoaobrrdj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.wangshuangyany.cn/Article/details/gtrjfbhkmx.html

[N11] 二叉树中序遍历
来源：http://dali.yangfankeji.com/Article/details/gtaeppbsia.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.fzhhl.top/Article/details/gtetxkbjnr.html

PHP:  // 手写递归函数
来源：http://dali.gogol.net.cn/Article/details/gtjdqfnvcb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.bjfxy.top/Article/details/gtmrypvyev.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yonumen.top/Article/details/gttfphjnjn.html

Java: // 手写递归
来源：http://dali.tanke756.top/Article/details/gtfdabhvuh.html

Go:   // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbndgculn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.dianchejie.cn/Article/details/gtnhmxawsm.html

C#:   // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gtdzyylbln.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zycfv.cn/Article/details/gtubrwphko.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.svipenyu.cn/Article/details/gtgnhwqtpl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.kuanghao11.cn/Article/details/gtapvujbeo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.andypj.xyz/Article/details/gtkswcveyp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gotoacloud.top/Article/details/gtwjfkewqo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gtamyejvdf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yuanzhike.top/Article/details/gtbnufwjnb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gogol.net.cn/Article/details/gtlimupmbv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hysaishi.cn/Article/details/gtliipcgyd.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtfgdsnynj.html

O. 并发与异步
来源：http://dali.sxryk.cn/Article/details/gtntlkrhac.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtkduaeche.html

[O01] 启动一个线程
来源：http://dali.chenlongwang.top/Article/details/gtcfwqmfsb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cheryme.top/Article/details/gtmbdifzty.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ydzc1.top/Article/details/gtpicealzi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.haohaochexian.top/Article/details/gtrypxozhc.html

TS:   // 同 JS
来源：http://dali.bjfxy.top/Article/details/gtearxdqwb.html

Java: new Thread(() -> f()).start()
来源：http://dali.9152youxi.cn/Article/details/gtxvkvwpzf.html

Go:   go f()
来源：http://dali.wangdashe.top/Article/details/gtnyttpodo.html

Ruby: Thread.new { f }
来源：http://dali.wangdashe.top/Article/details/gtlhaahzzd.html

C#:   Task.Run(() => F());
来源：http://dali.jqgfzy.top/Article/details/gtktlblbog.html

[O02] 使用线程池
来源：http://dali.smart0.xyz/Article/details/gtbrqzrbmc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.9152youxi.cn/Article/details/gtxobhvpna.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ivvv.top/Article/details/gtdwhrajbu.html

JS:   // worker_threads 线程池
来源：http://dali.snrcjt.cn/Article/details/gtkngqwqfh.html

TS:   // worker_threads 线程池
来源：http://dali.shangyingyoupin.top/Article/details/gtlcgkyrza.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gtwnynwrik.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.0kj1m.cn/Article/details/gtjmdscdwu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.dianchejie.cn/Article/details/gtdswfcdsw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jqgfzy.top/Article/details/gtylxceakd.html

[O03] 加锁保护共享数据
来源：http://dali.yuxming.cn/Article/details/gtkgiidvfg.html

Py:   with lock: shared += 1
来源：http://dali.ybcxt.top/Article/details/gtnkwaxtgp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gaohongyu789.top/Article/details/gtmnstsaqo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.feifeiyinyue.top/Article/details/gtheijcbah.html

TS:   // 同 JS
来源：http://dali.havefunace.top/Article/details/gtxgnekaaz.html

Java: synchronized (this) { shared++; }
来源：http://dali.ybcxt.top/Article/details/gtgiqujyji.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cucudq.cn/Article/details/gtebpcpihp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.0kj1m.cn/Article/details/gtldjmrmgn.html

C#:   lock (gate) { shared++; }
来源：http://dali.quarkkingdee.top/Article/details/gtfoontlkx.html

[O04] 定义异步函数并等待
来源：http://dali.birdmap.top/Article/details/gtbaldwdfc.html

Py:   async def f():⏎    await g()
来源：http://dali.jlsjyb.cn/Article/details/gtyiiqzvcg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nwbrower.top/Article/details/gtjdcqvivn.html

JS:   async function f() { await g(); }
来源：http://dali.meibo888.top/Article/details/gtsxcispvb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jyoumei.cn/Article/details/gtwnczdxuz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hywenlv.cn/Article/details/gtccfoheoe.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nwbrower.top/Article/details/gtquxicvan.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.meibo888.top/Article/details/gtkvrnmacd.html

C#:   async Task F() { await G(); }
来源：http://dali.jqgfzy.top/Article/details/gtommhsflk.html

[O05] 并发执行并等待全部完成
来源：http://dali.guannengcc.top/Article/details/gtqdgxjbcz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shuidangran.top/Article/details/gtjcdrafec.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.vqdsnc.cn/Article/details/gtwiaobnfs.html

JS:   await Promise.all(tasks)
来源：http://dali.quarkkingdee.top/Article/details/gtxubmeshu.html

TS:   await Promise.all(tasks)
来源：http://dali.zhoulong.xyz/Article/details/gtyxqnjaqq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yongpay.top/Article/details/gtzvtujxjq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yuxming.cn/Article/details/gtlptzeuta.html

Ruby: threads.map(&:join)
来源：http://dali.dianchejie.cn/Article/details/gtumyuseiz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yueranfly.top/Article/details/gthqvrjjjz.html

[O06] 使用进程池
来源：http://dali.dianchejie.cn/Article/details/gtoohurkkq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shzxlz.cn/Article/details/gtsalyztrd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yongpay.top/Article/details/gtikijfgek.html

JS:   // child_process / cluster 模块
来源：http://dali.yanxiufei.cn/Article/details/gtuwtelqvp.html

TS:   // child_process / cluster 模块
来源：http://dali.hnqzz.top/Article/details/gtiefxcwiu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenzaomai.com/Article/details/gtqnagdexx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.dashuyun.cn/Article/details/gtvodfwagy.html

Ruby: // fork 块
来源：http://dali.gzhubu.top/Article/details/gtmxqxhjri.html

C#:   Parallel.For
来源：http://dali.yueranfly.top/Article/details/gtmnatijpb.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtmyfxnnoh.html

P. 常用工具函数
来源：http://dali.jinqigfzy.top/Article/details/gtqtjkvjio.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtssqeusbz.html

[P01] 生成 UUID
来源：http://dali.meibo888.top/Article/details/gtlbkkefrl.html

Py:   str(uuid.uuid4())
来源：http://dali.nanxuanxn.top/Article/details/gtvaglgyzx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shangyingyoupin.top/Article/details/gtjojrowgd.html

JS:   crypto.randomUUID()
来源：http://dali.yanxiufei.cn/Article/details/gtuupyorpw.html

TS:   crypto.randomUUID()
来源：http://dali.zhiwuduotai.top/Article/details/gtnzurmnut.html

Java: UUID.randomUUID().toString()
来源：http://dali.wangdashe.top/Article/details/gtzfqytkpe.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj20258.top/Article/details/gtyjvmuyuy.html

Ruby: SecureRandom.uuid
来源：http://dali.hnqzz.top/Article/details/gtodurczod.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenjidiqi.icu/Article/details/gtshgqiacr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhengqikj.top/Article/details/gtswkzhoqd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gtmpyvsmwe.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhixingplan.top/Article/details/gtckgdhdnq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hammf.cn/Article/details/gtetpifhqi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xinyue.icu/Article/details/gtsmtnjjwc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gtzraibkjh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tanke756.top/Article/details/gtncybjlxv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ppjwa.cn/Article/details/gtwwamyzse.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.dashuyun.cn/Article/details/gtvwpekxhu.html

[P03] 生成短随机字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtkjrrvxiz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.havefunace.top/Article/details/gtubmlecvz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xinyue.icu/Article/details/gtaxafulnd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ybcxt.top/Article/details/gtwukurcks.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aibaodan.cn/Article/details/gtzcywwwju.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinqigfzy.top/Article/details/gtweyhmanc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ybcxt.top/Article/details/gtvoyinzxu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.feifeiyinyue.top/Article/details/gtcrepqrck.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sweek.top/Article/details/gtiiipaocp.html

[P04] 求长度
来源：http://dali.zhoulong.xyz/Article/details/gtngjiaciw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinyuanbaomall.cn/Article/details/gteovnkzjh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtqlpqsujz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guannengcc.top/Article/details/gtwrffmknc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gtyudkmudf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jqgufenzy.top/Article/details/gtsdgpdqwp.html

Go:   len(arr);  len(m)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxrckwvp.html

Ruby: x.length;  x.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgttkwzcz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.meibo888.top/Article/details/gtsjlsmcfp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dianchejie.cn/Article/details/gtyrsuesew.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.dianchejie.cn/Article/details/gtxsgxfynt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhongyouzk.top/Article/details/gtqyucknfl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cheryme.top/Article/details/gtnivjelns.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwibgpve.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fengsongda.top/Article/details/gtcxbqqqay.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.chenzaomai.com/Article/details/gttjlubrte.html

Ruby: a == b
来源：http://dali.jiagoushi.top/Article/details/gtfrvmydbm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yonumen.top/Article/details/gtrjqmvxdj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.bjfxy.top/Article/details/gtcexnpyub.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ehwqpu.com/Article/details/gtvuocegvu.html

PHP:  if (empty($x)) {}
来源：http://dali.jiagoushi.top/Article/details/gtytsptoxo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cucudq.cn/Article/details/gtesoodlba.html

TS:   if (x == null) {}
来源：http://dali.gaohongyu789.top/Article/details/gtdjweowql.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.quarkkingdee.top/Article/details/gtloyitrha.html

Go:   if x == nil {}
来源：http://dali.cheryme.top/Article/details/gtabbibaog.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yangfankeji.com/Article/details/gtmisipspi.html

C#:   if (x is null) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtvacyycjw.html

[P07] 防抖与节流
来源：http://dali.hysaishi.cn/Article/details/gtahtzfjuy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.daria6918.cn/Article/details/gtmwuznnrv.html

PHP:  // 手写时间戳比较
来源：http://dali.cdnleiting.top/Article/details/gtvrjmehmj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigfzy.top/Article/details/gtlbtzhycl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gtoiwdssfj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gzhubu.top/Article/details/gtblpzkpbv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.birdmap.top/Article/details/gtermwrtbz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sweek.top/Article/details/gtfaukgvms.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jlsjyb.cn/Article/details/gtuowlngvg.html

[P08] 处理浮点精度问题
来源：http://dali.cqqwz.cn/Article/details/gttyqkgyip.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fzhhl.top/Article/details/gtvroqqgru.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hysaishi.cn/Article/details/gttrmklqae.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.bjfxy.top/Article/details/gtrasmgxwz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sufxvd.cn/Article/details/gtazxictrl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhengqikj.top/Article/details/gtjdoxxlxk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.daria6918.cn/Article/details/gtazwzjbqg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenjidiqi.icu/Article/details/gtlibntbti.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj20258888.top/Article/details/gtectpjixw.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtdwghzyrv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xziqi.cn/Article/details/gtvwrhcaho.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtdszqdlbi.html

[Q01] 创建表
来源：http://dali.jlsjyb.cn/Article/details/gttmjknpfe.html

CREATE TABLE users (
来源：http://dali.sufxvd.cn/Article/details/gtdcvbjmxc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.haohaochexian.top/Article/details/gthhclsuam.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sxryk.cn/Article/details/gtcggfaaoe.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hammf.cn/Article/details/gtdcupoobi.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jiagoushi.top/Article/details/gtkadrzrph.html

);
来源：http://dali.316326.xyz/Article/details/gtmqtejaeg.html

[Q02] 创建带外键的表
来源：http://dali.tian-w.cn/Article/details/gtyfclqvcx.html

CREATE TABLE orders (
来源：http://dali.xziqi.cn/Article/details/gtrdwglccl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.havefunace.top/Article/details/gtnxsqvjeh.html

user_id INT NOT NULL,
来源：http://dali.smart0.xyz/Article/details/gtrefcxymh.html

amount DECIMAL(10, 2),
来源：http://dali.ppjwa.cn/Article/details/gtrpsmyiom.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shangyingyoupin.top/Article/details/gthmbwkxbo.html

);
来源：http://dali.zhiwuduotai.top/Article/details/gtjlgoqmoq.html

[Q03] 增加列
来源：http://dali.xuanzx.com/Article/details/gtyatixpqy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ppjwa.cn/Article/details/gtqozlwomj.html

[Q04] 修改列类型
来源：http://dali.shzxlz.cn/Article/details/gtwleumozk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nwbrower.top/Article/details/gteqfncsad.html

[Q05] 重命名列
来源：http://dali.redwolf501.top/Article/details/gtlodasoll.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.0kj1m.cn/Article/details/gtfrzmzvcb.html

[Q06] 删除列
来源：http://dali.zhengqikj.top/Article/details/gtuoweclwr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenzaomai.com/Article/details/gtpthbgezi.html

[Q07] 删除表
来源：http://dali.aizwys.cn/Article/details/gtnhtvbbex.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtbkigawme.html

[Q08] 创建普通索引
来源：http://dali.cucudq.cn/Article/details/gtbgnvxpkj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ehwqpu.com/Article/details/gtvztjdgmy.html

[Q09] 创建唯一索引
来源：http://dali.guowangkeji.top/Article/details/gtqpoudvyk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hnxiangtu.top/Article/details/gtsjuscyce.html

[Q10] 插入单行
来源：http://dali.chenjidiqi.icu/Article/details/gtmdxhpbqo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gotoacloud.top/Article/details/gtbqpccqex.html

[Q11] 一次插入多行
来源：http://dali.yuxming.cn/Article/details/gtvkymirdq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cdnleiting.top/Article/details/gtwvwqqxte.html

[Q12] 插入后取自增 ID
来源：http://dali.zhaomingkeji.xyz/Article/details/gtckpoitrf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.feifeiyinyue.top/Article/details/gtmlqkakyt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhixingplan.top/Article/details/gtgqkudqud.html

[Q13] 忽略重复插入
来源：http://dali.tian-w.cn/Article/details/gtdpwdveks.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sweek.top/Article/details/gttqwqnwtt.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmcncrjm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gzhubu.top/Article/details/gtquatnpkc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sysykeji.top/Article/details/gtcpnjmbeu.html

[Q15] 查询全部
来源：http://dali.gotoacloud.top/Article/details/gtzhkcqqgl.html

SELECT * FROM users;
来源：http://dali.gzhubu.top/Article/details/gtyipnzwen.html

[Q16] 查询指定列
来源：http://dali.bjfxy.top/Article/details/gtshusuxxe.html

SELECT id, name FROM users;
来源：http://dali.c1oappe.top/Article/details/gtdbjhdijo.html

[Q17] 条件查询
来源：http://dali.wangshuangyany.cn/Article/details/gtqvfcsrwn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.316326.xyz/Article/details/gtugubyjgz.html

[Q18] 模糊匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtkowbdwmv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.pengpengdd.cyou/Article/details/gtofpipses.html

[Q19] 范围查询
来源：http://dali.316326.xyz/Article/details/gtbkguyfhk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zdqjudy.top/Article/details/gtsxeqsttg.html

[Q20] IN 列表
来源：http://dali.c1oappe.top/Article/details/gtbaccxtjq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gtwwqktiqe.html

[Q21] 空值判断
来源：http://dali.snrcjt.cn/Article/details/gtkpojcydj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sufxvd.cn/Article/details/gtovcvjkgd.html

[Q22] 排序
来源：http://dali.gaohongyu789.top/Article/details/gtofwofgde.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ehwqpu.com/Article/details/gtpnxiruho.html

[Q23] 分页
来源：http://dali.bjfxy.top/Article/details/gtmimtksin.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ywan-chungtsiang.top/Article/details/gthgdccrcg.html

[Q24] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gtitehoalg.html

SELECT DISTINCT city FROM users;
来源：http://dali.316326.xyz/Article/details/gtlhfaemxd.html

[Q25] 只取前 N 条
来源：http://dali.gzhubu.top/Article/details/gthhigukdz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jyoumei.cn/Article/details/gtfnljekni.html

[Q26] 计数
来源：http://dali.cdnleiting.top/Article/details/gtitobmkec.html

SELECT COUNT(*) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtoeoqbqja.html

[Q27] 条件计数
来源：http://dali.yangfankeji.com/Article/details/gtfunedfzl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.bjfxy.top/Article/details/gtsfmrvwdo.html

[Q28] 求和与平均
来源：http://dali.yuanzhike.top/Article/details/gtmhmkkwcv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtvuykjtgp.html

[Q29] 最大最小值
来源：http://dali.yonumen.top/Article/details/gteflpcyzy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtdurpsrdz.html

[Q30] 分组统计
来源：http://dali.shzxlz.cn/Article/details/gtibyxedzj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zycfv.cn/Article/details/gthezyuscu.html

[Q31] 分组后过滤
来源：http://dali.jqgufenzy.top/Article/details/gtimoyqavx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.smart0.xyz/Article/details/gtkbusxxkb.html

[Q32] 分组拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gtvsdslzze.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gtdiyassjt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hfpthk.cn/Article/details/gttlfmlcau.html

[Q33] 多列分组
来源：http://dali.jianghu66.top/Article/details/gtfitefsjk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yuanzhike.top/Article/details/gtapwvltho.html

[Q34] 每组取第一条
来源：http://dali.ydzc1.top/Article/details/gtchdmdacm.html

SELECT * FROM (
来源：http://dali.pycfn.com/Article/details/gtskgshsmn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gotoacloud.top/Article/details/gtronharia.html

) t WHERE rn = 1;
来源：http://dali.daria6918.cn/Article/details/gtlxkvayps.html

[Q35] 内连接
来源：http://dali.nwbrower.top/Article/details/gtheisupyz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.9152youxi.cn/Article/details/gtjxeeepmo.html

[Q36] 左连接
来源：http://dali.guannengcc.top/Article/details/gtkkdbffxe.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xylfe.cn/Article/details/gtolawqfcd.html

[Q37] 右连接
来源：http://dali.shangyingyoupin.top/Article/details/gttasfpvcm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.daria6918.cn/Article/details/gtmoicvhhe.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhixingplan.top/Article/details/gtbnnwjaqq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sysykeji.top/Article/details/gtdhnimcak.html

[Q39] 自连接（查上下级）
来源：http://dali.yangfankeji.com/Article/details/gthmbxtokt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xuanzx.com/Article/details/gtzpximarr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gogol.net.cn/Article/details/gttqkycoxp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yangfankeji.com/Article/details/gtukfownum.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.feifeiyinyue.top/Article/details/gtylzyqayr.html

[Q41] 多表连接
来源：http://dali.cqqwz.cn/Article/details/gtgrfbesuq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtslcygoir.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hywenlv.cn/Article/details/gtrjpiftgj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.iojbl.cn/Article/details/gtopijrepm.html

[Q42] 连接条件附加过滤
来源：http://dali.ppjwa.cn/Article/details/gtitovijjl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jianghu66.top/Article/details/gtxcuqniem.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.pengpengdd.cyou/Article/details/gtiyywvfpa.html

[Q43] 标量子查询
来源：http://dali.hfpthk.cn/Article/details/gtcshxlodr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.feifeiyinyue.top/Article/details/gtdvmpuela.html

[Q44] IN 子查询
来源：http://dali.jqgufenzy.top/Article/details/gtfizeyvvw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nanxinkj.top/Article/details/gtoivovwks.html

[Q45] EXISTS 判断存在
来源：http://dali.jianghu66.top/Article/details/gtqduwgdft.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpotupbvs.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.guannengcc.top/Article/details/gtylbojduu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ppjwa.cn/Article/details/gtbtyfbycf.html

[Q47] 与平均值比较
来源：http://dali.hnqzz.top/Article/details/gtruefxxjd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj20258888.top/Article/details/gtouedbqyv.html


<!-- 参考信息 -->