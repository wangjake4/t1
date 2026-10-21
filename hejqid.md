代发 wailian999

Ruby: s == s.reverse
来源：http://dali.sxryk.cn/Article/details/gtbzkonrwc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jianghu66.top/Article/details/gtluyrtrol.html

[N07] 两数之和（返回下标）
来源：http://dali.havefunace.top/Article/details/gtrzkecozr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jlsjyb.cn/Article/details/gteheeiizm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nanxinkj.top/Article/details/gtqztyidwm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhiwuduotai.top/Article/details/gtjyucfkfw.html

TS:   // 手写 Map<string, number>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzkaebua.html

Java: // 手写 HashMap
来源：http://dali.snrcjt.cn/Article/details/gtwuucvluj.html

Go:   // 手写 map[int]int
来源：http://dali.hammf.cn/Article/details/gtimvhgwit.html

Ruby: // 手写 Hash
来源：http://dali.yonumen.top/Article/details/gtfnfqcpsl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cheryme.top/Article/details/gtryxfunxi.html

[N08] 生成全排列
来源：http://dali.chenzaomai.com/Article/details/gtnzotxack.html

Py:   itertools.permutations(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtnzyutbhq.html

PHP:  // 手写递归交换
来源：http://dali.nwbrower.top/Article/details/gtyvndsgen.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtrpgvzxmr.html

TS:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtfrdoaexu.html

Java: // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtjyqwifly.html

Go:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtgvnmlixe.html

Ruby: arr.permutation.to_a
来源：http://dali.xylfe.cn/Article/details/gtivuipesm.html

C#:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gtpjkgoafh.html

[N09] 栈与队列
来源：http://dali.cashguo.top/Article/details/gtpndevpty.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhengqikj.top/Article/details/gtqpyxldyj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnqzz.top/Article/details/gtmytnjdxz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtoihozslw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.fengsongda.top/Article/details/gtsojxfixy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.dianchejie.cn/Article/details/gtamqhtyrd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.9152youxi.cn/Article/details/gthwjeehyn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.wangdashe.top/Article/details/gtbstuwmxr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sysykeji.top/Article/details/gtyjgrjbnm.html

[N10] 链表节点定义
来源：http://dali.yuxming.cn/Article/details/gtyylrvmtj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenzaomai.com/Article/details/gtecugfhbl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tianlin.xyz/Article/details/gtpnwbxupm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guannengcc.top/Article/details/gttqpxmdsn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ehwqpu.com/Article/details/gtfygazpid.html

Java: class Node { int v; Node next; }
来源：http://dali.mhx1999.top/Article/details/gtmqdvsopw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.fengsongda.top/Article/details/gtxzgwaeif.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj20258.top/Article/details/gtfswomgem.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hongshengwenyu.top/Article/details/gtdcakvezs.html

[N11] 二叉树中序遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtgxzkgafa.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.tianlin.xyz/Article/details/gthnmxbuul.html

PHP:  // 手写递归函数
来源：http://dali.vqdsnc.cn/Article/details/gtfxkinipi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cqqwz.cn/Article/details/gtlukmwvhs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258.top/Article/details/gtnhfdrimj.html

Java: // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gthcpwxpvn.html

Go:   // 手写递归
来源：http://dali.yvedp.cn/Article/details/gtnozerchc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.redwolf501.top/Article/details/gtndmojpgx.html

C#:   // 手写递归
来源：http://dali.fzhhl.top/Article/details/gtltbqniwl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.mhx1999.top/Article/details/gtlvkvaruh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hfpthk.cn/Article/details/gtbezmdytr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhoulong.xyz/Article/details/gtdfuflnpl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuanzhike.top/Article/details/gtmbctqbfa.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnxiangtu.top/Article/details/gtmweqmuir.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xinyue.icu/Article/details/gticzvwfdn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shuidangran.top/Article/details/gtjiruwopx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.0kj1m.cn/Article/details/gtpkhqcnfr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinghuilouyu.cn/Article/details/gticfhfxtl.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtlpvlhzqb.html

O. 并发与异步
来源：http://dali.jinghuilouyu.cn/Article/details/gtzborftre.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtrivbuhsc.html

[O01] 启动一个线程
来源：http://dali.aizwys.cn/Article/details/gtcncwmpgu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.bjfxy.top/Article/details/gtgtszsacm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.pengpengdd.cyou/Article/details/gtcwhgavwb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqpugzszg.html

TS:   // 同 JS
来源：http://dali.316326.xyz/Article/details/gtfrfzkuyt.html

Java: new Thread(() -> f()).start()
来源：http://dali.yueranfly.top/Article/details/gtnylpejaw.html

Go:   go f()
来源：http://dali.hysaishi.cn/Article/details/gtrvnlljqg.html

Ruby: Thread.new { f }
来源：http://dali.zhengqikj.top/Article/details/gtlqmjztbc.html

C#:   Task.Run(() => F());
来源：http://dali.nanxuanxn.top/Article/details/gtvplrobks.html

[O02] 使用线程池
来源：http://dali.ybcxt.top/Article/details/gtzbgolzpf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xylfe.cn/Article/details/gtjdmhatnq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hywenlv.cn/Article/details/gtfbjuflpy.html

JS:   // worker_threads 线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtxcitnpvi.html

TS:   // worker_threads 线程池
来源：http://dali.aizwys.cn/Article/details/gtydiwlgji.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jyoumei.cn/Article/details/gttafsryvu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.0kj1m.cn/Article/details/gthqgmrcfp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.guannengcc.top/Article/details/gtalanreeh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hfpthk.cn/Article/details/gtqfcpgfao.html

[O03] 加锁保护共享数据
来源：http://dali.tanke756.top/Article/details/gtfeqzwebv.html

Py:   with lock: shared += 1
来源：http://dali.yonumen.top/Article/details/gtadcytdyg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hnxiangtu.top/Article/details/gtifrtxhnx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenzaomai.com/Article/details/gtgplnazjo.html

TS:   // 同 JS
来源：http://dali.chenzaomai.com/Article/details/gtkcpxyzcw.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinqigfzy.top/Article/details/gtygitwgnh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthckmlxif.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nwbrower.top/Article/details/gtqshmukam.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoliniupp.html

[O04] 定义异步函数并等待
来源：http://dali.hnxiangtu.top/Article/details/gtwhlvaanp.html

Py:   async def f():⏎    await g()
来源：http://dali.jiagoushi.top/Article/details/gtabxcqmle.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sweek.top/Article/details/gtomsslafd.html

JS:   async function f() { await g(); }
来源：http://dali.tian-w.cn/Article/details/gtgpqgjmok.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthdcmjjwo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ybcxt.top/Article/details/gtgpjerwnf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hammf.cn/Article/details/gtixgjobvn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xylfe.cn/Article/details/gtvkqdkbpu.html

C#:   async Task F() { await G(); }
来源：http://dali.havefunace.top/Article/details/gttgadezxo.html

[O05] 并发执行并等待全部完成
来源：http://dali.haohaochexian.top/Article/details/gtreihfxpl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.snrcjt.cn/Article/details/gtrnnrtvok.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.smart0.xyz/Article/details/gtousgwyyj.html

JS:   await Promise.all(tasks)
来源：http://dali.cucudq.cn/Article/details/gtbjxyoodd.html

TS:   await Promise.all(tasks)
来源：http://dali.jinqigufen.top/Article/details/gtnsikfayf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhongyouzk.top/Article/details/gtjdjfwpzg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yueranfly.top/Article/details/gtcuhxpakc.html

Ruby: threads.map(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gtfzuyuidb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.kuanghao11.cn/Article/details/gtaxyltahj.html

[O06] 使用进程池
来源：http://dali.pengpengdd.cyou/Article/details/gtyfujlgyt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gogol.net.cn/Article/details/gtuogwzsfx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shzxlz.cn/Article/details/gtskzftiqp.html

JS:   // child_process / cluster 模块
来源：http://dali.hysaishi.cn/Article/details/gtyyvjilpp.html

TS:   // child_process / cluster 模块
来源：http://dali.hnqzz.top/Article/details/gtcwgeycno.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.andypj.xyz/Article/details/gtgfpnuxsi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.meibo888.top/Article/details/gtgydbhzkf.html

Ruby: // fork 块
来源：http://dali.xinyue.icu/Article/details/gtxwnrumpw.html

C#:   Parallel.For
来源：http://dali.hnxiangtu.top/Article/details/gtfjzjcpyi.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtppamupdq.html

P. 常用工具函数
来源：http://dali.ydzc1.top/Article/details/gtqquarduh.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtatsujsic.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gtqcbsqevn.html

Py:   str(uuid.uuid4())
来源：http://dali.hywenlv.cn/Article/details/gtiwthtupl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.guannengcc.top/Article/details/gthgkdzubu.html

JS:   crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gtknizvvrr.html

TS:   crypto.randomUUID()
来源：http://dali.havefunace.top/Article/details/gtnxsckftj.html

Java: UUID.randomUUID().toString()
来源：http://dali.yonumen.top/Article/details/gtxkvjcdtn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gtdccfqpvf.html

Ruby: SecureRandom.uuid
来源：http://dali.zycfv.cn/Article/details/gtbdqpthbu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gttkulfjui.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yuxming.cn/Article/details/gttpigojbp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gogol.net.cn/Article/details/gtktcarlnc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yonumen.top/Article/details/gttuhzazsk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gogol.net.cn/Article/details/gtinnmybru.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shangyingyoupin.top/Article/details/gtawncznjo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.c1oappe.top/Article/details/gtkovopljy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jianghu66.top/Article/details/gtrqkuijqh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.andypj.xyz/Article/details/gtyuzprqxo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.tanke756.top/Article/details/gthozlfiul.html

[P03] 生成短随机字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbnornxg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.meibo888.top/Article/details/gtdezvnety.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jiagoushi.top/Article/details/gtkjcbtgsr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nwbrower.top/Article/details/gtneejfuwi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhengqikj.top/Article/details/gtarzopsae.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jyoumei.cn/Article/details/gtdkknakqx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.feifeiyinyue.top/Article/details/gtzcatbltp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xylfe.cn/Article/details/gtjjzzgblc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cdnleiting.top/Article/details/gtixtasvbv.html

[P04] 求长度
来源：http://dali.zhoulong.xyz/Article/details/gtguqsxbve.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.aibaodan.cn/Article/details/gtjremwdbn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gtmmcmkmph.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhiwuduotai.top/Article/details/gtlpzrgdhn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ydzc1.top/Article/details/gthmlkfnjt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.316326.xyz/Article/details/gthdimcrtl.html

Go:   len(arr);  len(m)
来源：http://dali.shuidangran.top/Article/details/gtwtgkpsvz.html

Ruby: x.length;  x.size
来源：http://dali.shanyushiyangtech.top/Article/details/gtbhxcijig.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.dianchejie.cn/Article/details/gtvnqglkzx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjaqxjwf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.smart0.xyz/Article/details/gtmflpsolv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xylfe.cn/Article/details/gtecjkqoqb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xuetiantiany.cn/Article/details/gtlbtikjaw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ivvv.top/Article/details/gtiaxtwxry.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cqqwz.cn/Article/details/gttbvbkaos.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.andypj.xyz/Article/details/gtenksipbj.html

Ruby: a == b
来源：http://dali.chenjidiqi.icu/Article/details/gtylczkgkn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cqqwz.cn/Article/details/gtunssbxgu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.meibo888.top/Article/details/gtvvfvnwwx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hfpthk.cn/Article/details/gteicdfpsq.html

PHP:  if (empty($x)) {}
来源：http://dali.chenlongwang.top/Article/details/gtyjsbvojp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shangyingyoupin.top/Article/details/gtefdksgpg.html

TS:   if (x == null) {}
来源：http://dali.daria6918.cn/Article/details/gtwmcrelkf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gtontkmdcn.html

Go:   if x == nil {}
来源：http://dali.birdmap.top/Article/details/gtsmxcmjas.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jqgufenzy.top/Article/details/gtornkuqwq.html

C#:   if (x is null) {}
来源：http://dali.meibo888.top/Article/details/gtvicrafqz.html

[P07] 防抖与节流
来源：http://dali.chenzaomai.com/Article/details/gtajqbcdgx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj202588.top/Article/details/gtrmniywgk.html

PHP:  // 手写时间戳比较
来源：http://dali.zhoulong.xyz/Article/details/gtaodpxuxb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gtponzbbbj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuanzhike.top/Article/details/gtzadoftnm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.9152youxi.cn/Article/details/gtwhmazyfo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xziqi.cn/Article/details/gtikyzkrrj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.chenzaomai.com/Article/details/gthcbqgdlr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shzxlz.cn/Article/details/gtklxfsjcu.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigfzy.top/Article/details/gttdlgpidq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkvhmaqsp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.9152youxi.cn/Article/details/gtkgsvmoya.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.guowangkeji.top/Article/details/gtnufennvl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xziqi.cn/Article/details/gtyujswpcx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.dashuyun.cn/Article/details/gtwlbuapeb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinqigfzy.top/Article/details/gtyosthjmn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tian-w.cn/Article/details/gtumjaxnss.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxuanxn.top/Article/details/gttdwkonna.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtrnpnlkzm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.redwolf501.top/Article/details/gtmlhunvqv.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtzqxrkvmc.html

[Q01] 创建表
来源：http://dali.yonumen.top/Article/details/gtcuhpghul.html

CREATE TABLE users (
来源：http://dali.birdmap.top/Article/details/gtkpffdemu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fzhhl.top/Article/details/gtsacetspe.html

name VARCHAR(50) NOT NULL,
来源：http://dali.guowangkeji.top/Article/details/gtrqlbopqo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yuxming.cn/Article/details/gtokupgkwu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.c1oappe.top/Article/details/gtzyshkrgu.html

);
来源：http://dali.quarkkingdee.top/Article/details/gteaivnlac.html

[Q02] 创建带外键的表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxszbnjl.html

CREATE TABLE orders (
来源：http://dali.ivvv.top/Article/details/gtebmmsrdx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.svipenyu.cn/Article/details/gtxysrohoy.html

user_id INT NOT NULL,
来源：http://dali.316326.xyz/Article/details/gtjsdocjrf.html

amount DECIMAL(10, 2),
来源：http://dali.pycfn.com/Article/details/gtqeihatmc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cashguo.top/Article/details/gtxzwlsnjk.html

);
来源：http://dali.birdmap.top/Article/details/gtfazfjruz.html

[Q03] 增加列
来源：http://dali.9152youxi.cn/Article/details/gtfumzneox.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.vqdsnc.cn/Article/details/gtmacxbcwp.html

[Q04] 修改列类型
来源：http://dali.jqgufenzy.top/Article/details/gthjmwgxpl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.wangshuangyany.cn/Article/details/gtzqwfvivp.html

[Q05] 重命名列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtscqvhwxu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yonumen.top/Article/details/gtjnbiemom.html

[Q06] 删除列
来源：http://dali.jinghuilouyu.cn/Article/details/gtgdoazrbf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shanyushiyangtech.top/Article/details/gtgbvpqhvs.html

[Q07] 删除表
来源：http://dali.9152youxi.cn/Article/details/gtkfraiqyk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtqhtzseui.html

[Q08] 创建普通索引
来源：http://dali.jyoumei.cn/Article/details/gtjavkpmkr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.dashuyun.cn/Article/details/gtvuydeltn.html

[Q09] 创建唯一索引
来源：http://dali.zhoulong.xyz/Article/details/gtfpwyiswl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.tianlin.xyz/Article/details/gtitijcurx.html

[Q10] 插入单行
来源：http://dali.cucudq.cn/Article/details/gtgislzsob.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzahqdgw.html

[Q11] 一次插入多行
来源：http://dali.jqgfzy.top/Article/details/gthwbgmpaw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.svipenyu.cn/Article/details/gttdhyjgxv.html

[Q12] 插入后取自增 ID
来源：http://dali.fzhhl.top/Article/details/gtexrjapae.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhengqikj.top/Article/details/gtmtcukonz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj20258.top/Article/details/gtfvbtngzr.html

[Q13] 忽略重复插入
来源：http://dali.ybcxt.top/Article/details/gtpuwloyjf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tanke756.top/Article/details/gtqsntlhbg.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhixingplan.top/Article/details/gtqsrybpkw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.vqdsnc.cn/Article/details/gturilzilh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.wangshuangyany.cn/Article/details/gtdveqrtba.html

[Q15] 查询全部
来源：http://dali.feifeiyinyue.top/Article/details/gtstdhmvni.html

SELECT * FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtrivfpoqg.html

[Q16] 查询指定列
来源：http://dali.svipenyu.cn/Article/details/gttydbcllg.html

SELECT id, name FROM users;
来源：http://dali.yvedp.cn/Article/details/gtkmnvtlxx.html

[Q17] 条件查询
来源：http://dali.yj20258888.top/Article/details/gtlsyuyouw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xinyue.icu/Article/details/gtsmhawbqm.html

[Q18] 模糊匹配
来源：http://dali.nanxuanxn.top/Article/details/gthsryrlzn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jqgfzy.top/Article/details/gtzfxuckez.html

[Q19] 范围查询
来源：http://dali.jyoumei.cn/Article/details/gtxbdnkklq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zdqjudy.top/Article/details/gtgapoxxpw.html

[Q20] IN 列表
来源：http://dali.ivvv.top/Article/details/gtqfrxymqd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gaohongyu789.top/Article/details/gttekpcwod.html

[Q21] 空值判断
来源：http://dali.pycfn.com/Article/details/gtepzinric.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jqgufenzy.top/Article/details/gtaitotgbs.html

[Q22] 排序
来源：http://dali.yvedp.cn/Article/details/gtitxngqpz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gzhubu.top/Article/details/gtelnzhvnp.html

[Q23] 分页
来源：http://dali.nanxinkj.top/Article/details/gtnobfbnme.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yonumen.top/Article/details/gtbchyotnx.html

[Q24] 去重
来源：http://dali.hywenlv.cn/Article/details/gtaybaagpe.html

SELECT DISTINCT city FROM users;
来源：http://dali.sxryk.cn/Article/details/gtpgbbhnhe.html

[Q25] 只取前 N 条
来源：http://dali.hfpthk.cn/Article/details/gthxdynvpy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.aizwys.cn/Article/details/gtttfglgtg.html

[Q26] 计数
来源：http://dali.fzhhl.top/Article/details/gtemxcqvjm.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj20258.top/Article/details/gtxjlrxlhx.html

[Q27] 条件计数
来源：http://dali.xuetiantiany.cn/Article/details/gtypfytngt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj202588.top/Article/details/gtwilwfshf.html

[Q28] 求和与平均
来源：http://dali.pycfn.com/Article/details/gtzmnfesfq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gttzrmkzyw.html

[Q29] 最大最小值
来源：http://dali.chenzaomai.com/Article/details/gttifrvhmv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtzcqcqgfs.html

[Q30] 分组统计
来源：http://dali.9152youxi.cn/Article/details/gtegkzukqx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zycfv.cn/Article/details/gtjcajhaad.html

[Q31] 分组后过滤
来源：http://dali.tian-w.cn/Article/details/gtnuyzypfv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.svipenyu.cn/Article/details/gtelnyracm.html

[Q32] 分组拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gtidalsdwe.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gtqgqqanth.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cheryme.top/Article/details/gtczehwssl.html

[Q33] 多列分组
来源：http://dali.hysaishi.cn/Article/details/gtyrzfaigb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.aibaodan.cn/Article/details/gtngljekbj.html

[Q34] 每组取第一条
来源：http://dali.gogol.net.cn/Article/details/gtuhfzgdgi.html

SELECT * FROM (
来源：http://dali.cdnleiting.top/Article/details/gtuvfseads.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.feifeiyinyue.top/Article/details/gtimptblya.html

) t WHERE rn = 1;
来源：http://dali.tian-w.cn/Article/details/gtnsnjzaal.html

[Q35] 内连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtluugakif.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gtvquomvvn.html

[Q36] 左连接
来源：http://dali.yonumen.top/Article/details/gtbkhufsdq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zycfv.cn/Article/details/gtrdvvcvyg.html

[Q37] 右连接
来源：http://dali.mhx1999.top/Article/details/gtmvhkjftk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zdqjudy.top/Article/details/gthjuhwkom.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.iojbl.cn/Article/details/gtwkyctapn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.smart0.xyz/Article/details/gtylmphszj.html

[Q39] 自连接（查上下级）
来源：http://dali.snrcjt.cn/Article/details/gtdyzasijx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.daxiang520.top/Article/details/gtfypaarts.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ybcxt.top/Article/details/gtioipnfdd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cashguo.top/Article/details/gtmplgbeph.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.pengpengdd.cyou/Article/details/gtxuevbuld.html

[Q41] 多表连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfcimjonq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.c1oappe.top/Article/details/gtpwtpfoix.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj20258.top/Article/details/gtqrwifgdw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.guowangkeji.top/Article/details/gttideqejw.html

[Q42] 连接条件附加过滤
来源：http://dali.sufxvd.cn/Article/details/gtwksrubsg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hammf.cn/Article/details/gthufhflvn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hywenlv.cn/Article/details/gtbyknsasp.html

[Q43] 标量子查询
来源：http://dali.xuetiantiany.cn/Article/details/gtuytnbhkc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hysaishi.cn/Article/details/gtmtbxrxoh.html

[Q44] IN 子查询
来源：http://dali.jqgufenzy.top/Article/details/gtjhimgqtq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yanxiufei.cn/Article/details/gtjfqtdehq.html

[Q45] EXISTS 判断存在
来源：http://dali.xuetiantiany.cn/Article/details/gteznsiuwe.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gtdcwzruyi.html


<!-- 参考信息 -->