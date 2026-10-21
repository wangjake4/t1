代发 wailian999

Ruby: s == s.reverse
来源：http://dali.gogol.net.cn/Article/details/gtvmbomvkb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sysykeji.top/Article/details/gthpmpoctw.html

[N07] 两数之和（返回下标）
来源：http://dali.guowangkeji.top/Article/details/gtlppeelsy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.mhx1999.top/Article/details/gtjweowsor.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yueranfly.top/Article/details/gtgoqkhanu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gzhubu.top/Article/details/gtlgoaccvi.html

TS:   // 手写 Map<string, number>
来源：http://dali.9152youxi.cn/Article/details/gtxjrlyvdw.html

Java: // 手写 HashMap
来源：http://dali.shanyushiyangtech.top/Article/details/gtlueayiyj.html

Go:   // 手写 map[int]int
来源：http://dali.svipenyu.cn/Article/details/gtqioaacxa.html

Ruby: // 手写 Hash
来源：http://dali.cucudq.cn/Article/details/gtqciogqcx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.quarkkingdee.top/Article/details/gtiturtbpu.html

[N08] 生成全排列
来源：http://dali.dianchejie.cn/Article/details/gthqfdlxyu.html

Py:   itertools.permutations(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtrrigyarj.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gtlotaopfy.html

JS:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtibnnustt.html

TS:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtjjfouxru.html

Java: // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtfcpbhczq.html

Go:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxrvghomj.html

Ruby: arr.permutation.to_a
来源：http://dali.gzhubu.top/Article/details/gtmbluryjt.html

C#:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gtrbgatylo.html

[N09] 栈与队列
来源：http://dali.xziqi.cn/Article/details/gtvercpjku.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gtqgqviihg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yonumen.top/Article/details/gtwokaszgt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gtyyjolgjs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hysaishi.cn/Article/details/gtrutwqjmn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cdnleiting.top/Article/details/gtzuntwnan.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjzwcxoge.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gtnaqatfle.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cdnleiting.top/Article/details/gtfnpxlohf.html

[N10] 链表节点定义
来源：http://dali.guannengcc.top/Article/details/gtjjmgtbgu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shangyingyoupin.top/Article/details/gtnfmnsniu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.kuanghao11.cn/Article/details/gtnijrnrqx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigufen.top/Article/details/gtishbhfht.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jianghu66.top/Article/details/gtzfwrusia.html

Java: class Node { int v; Node next; }
来源：http://dali.fzhhl.top/Article/details/gtmpdohqbu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.iojbl.cn/Article/details/gtathtwcof.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ehwqpu.com/Article/details/gtabpgiyhb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xinyue.icu/Article/details/gtiawppskv.html

[N11] 二叉树中序遍历
来源：http://dali.tian-w.cn/Article/details/gtiukcscev.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.pycfn.com/Article/details/gtlwjyqfxw.html

PHP:  // 手写递归函数
来源：http://dali.yangfankeji.com/Article/details/gtkvybdjgd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gzhubu.top/Article/details/gtwuhelfed.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gtvxloqnbn.html

Java: // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gtqrhayrif.html

Go:   // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gtauwgbhbo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.dianchejie.cn/Article/details/gtxrfufnwz.html

C#:   // 手写递归
来源：http://dali.yuxming.cn/Article/details/gtgyuqmfdi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.fengsongda.top/Article/details/gtvvejwabb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zycfv.cn/Article/details/gtnkwmtyqy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sysykeji.top/Article/details/gtabejdded.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangshuangyany.cn/Article/details/gtihkozmny.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fzhhl.top/Article/details/gtsbqekncs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jyoumei.cn/Article/details/gtcmnyidax.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xinyue.icu/Article/details/gtkvvxdhof.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ydzc1.top/Article/details/gtoldgrihp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gtjaofeqxl.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtyderibsf.html

O. 并发与异步
来源：http://dali.gogol.net.cn/Article/details/gtyyalhzno.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtxupwolfp.html

[O01] 启动一个线程
来源：http://dali.xuetiantiany.cn/Article/details/gtwcocuheg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cucudq.cn/Article/details/gtqsswpkmj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.feifeiyinyue.top/Article/details/gtzvzvzxjk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gaohongyu789.top/Article/details/gtxvmhtdga.html

TS:   // 同 JS
来源：http://dali.hnqzz.top/Article/details/gtqqothaqa.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinqigufen.top/Article/details/gtikuxdjkt.html

Go:   go f()
来源：http://dali.yvedp.cn/Article/details/gthowhknuf.html

Ruby: Thread.new { f }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzrfusje.html

C#:   Task.Run(() => F());
来源：http://dali.nwbrower.top/Article/details/gtowfbermm.html

[O02] 使用线程池
来源：http://dali.yanxiufei.cn/Article/details/gtxzalenth.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.guannengcc.top/Article/details/gtvcalflmo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.vqdsnc.cn/Article/details/gtwdvplkrb.html

JS:   // worker_threads 线程池
来源：http://dali.jinqigufen.top/Article/details/gtmqtsysfp.html

TS:   // worker_threads 线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqjxlndm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tanke756.top/Article/details/gtqmcpwsax.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.snrcjt.cn/Article/details/gtmaubqgfj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.dianchejie.cn/Article/details/gthtkessco.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jqgfzy.top/Article/details/gtyppzaktx.html

[O03] 加锁保护共享数据
来源：http://dali.mhx1999.top/Article/details/gtpdznrnfe.html

Py:   with lock: shared += 1
来源：http://dali.sxryk.cn/Article/details/gtgltagtqv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yuxming.cn/Article/details/gtxqxbiidc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfbwchiyf.html

TS:   // 同 JS
来源：http://dali.zycfv.cn/Article/details/gtslyfvhxt.html

Java: synchronized (this) { shared++; }
来源：http://dali.smart0.xyz/Article/details/gtklywbtwh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.fengsongda.top/Article/details/gtfvdvywyn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.haohaochexian.top/Article/details/gtsyxgstlu.html

C#:   lock (gate) { shared++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtazffxeru.html

[O04] 定义异步函数并等待
来源：http://dali.0kj1m.cn/Article/details/gtvhvsqjby.html

Py:   async def f():⏎    await g()
来源：http://dali.bjfxy.top/Article/details/gtoycvsmsd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhixingplan.top/Article/details/gtjnugfmln.html

JS:   async function f() { await g(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsoixuopz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jqgfzy.top/Article/details/gtpdlwuaol.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shangyingyoupin.top/Article/details/gtmbuvgegc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shuidangran.top/Article/details/gtjxotmpuj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yueranfly.top/Article/details/gtjksasxip.html

C#:   async Task F() { await G(); }
来源：http://dali.zdqjudy.top/Article/details/gtcksadhgq.html

[O05] 并发执行并等待全部完成
来源：http://dali.hfpthk.cn/Article/details/gtjuarwxxc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gthcuufdwj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shuidangran.top/Article/details/gtyxywptxf.html

JS:   await Promise.all(tasks)
来源：http://dali.quarkkingdee.top/Article/details/gtdeyocwxj.html

TS:   await Promise.all(tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfjlvqxg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cashguo.top/Article/details/gthmnuejhs.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.316326.xyz/Article/details/gtgtsdpnol.html

Ruby: threads.map(&:join)
来源：http://dali.jlsjyb.cn/Article/details/gtrbgsgmov.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nanxinkj.top/Article/details/gtkgmeisro.html

[O06] 使用进程池
来源：http://dali.shuidangran.top/Article/details/gtpsclhyvt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ydzc1.top/Article/details/gtacppklrv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.pycfn.com/Article/details/gtfkonfwwe.html

JS:   // child_process / cluster 模块
来源：http://dali.mhx1999.top/Article/details/gtgzltqqla.html

TS:   // child_process / cluster 模块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzeeyghtw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ivvv.top/Article/details/gtjvvfbnhp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yonumen.top/Article/details/gthnmiulec.html

Ruby: // fork 块
来源：http://dali.hnqzz.top/Article/details/gtmefhlkxb.html

C#:   Parallel.For
来源：http://dali.xuanzx.com/Article/details/gtpabvlnge.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtkigdxuzp.html

P. 常用工具函数
来源：http://dali.andypj.xyz/Article/details/gtvegxsnwj.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtyzxnawnq.html

[P01] 生成 UUID
来源：http://dali.jinqigufen.top/Article/details/gtsyeeopki.html

Py:   str(uuid.uuid4())
来源：http://dali.hnxiangtu.top/Article/details/gtgbbmapuf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.guannengcc.top/Article/details/gtpidvlald.html

JS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gthymdulzf.html

TS:   crypto.randomUUID()
来源：http://dali.redwolf501.top/Article/details/gtanynghze.html

Java: UUID.randomUUID().toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtbseccvbc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nanxinkj.top/Article/details/gtsdapxfog.html

Ruby: SecureRandom.uuid
来源：http://dali.birdmap.top/Article/details/gtbnzooaff.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.0kj1m.cn/Article/details/gtddlbqmim.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shuidangran.top/Article/details/gttuoutbgc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jlsjyb.cn/Article/details/gtjeuppesh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhongyouzk.top/Article/details/gtkryxwzmq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhixingplan.top/Article/details/gtmaadizyl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shangyingyoupin.top/Article/details/gtxpsgudgu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.guowangkeji.top/Article/details/gtfojexumg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyexavqwd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sysykeji.top/Article/details/gtjsyeugkf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.tanke756.top/Article/details/gtjiyohhrf.html

[P03] 生成短随机字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndsuprbj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuanzx.com/Article/details/gtaxwftfly.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.redwolf501.top/Article/details/gtujoywvxc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tian-w.cn/Article/details/gtiaucmtpr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hysaishi.cn/Article/details/gtfcfhhkcm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhixingplan.top/Article/details/gtmkhfhqcq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.redwolf501.top/Article/details/gtvjwyquky.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sxryk.cn/Article/details/gttczzkcki.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yuxming.cn/Article/details/gtpdtbjdgg.html

[P04] 求长度
来源：http://dali.pengpengdd.cyou/Article/details/gtdwdfneyg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hnxiangtu.top/Article/details/gteqejuffm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtjsvkghne.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258.top/Article/details/gtjdmtgdop.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jiagoushi.top/Article/details/gtifoaiupy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.quarkkingdee.top/Article/details/gtjzvdikjn.html

Go:   len(arr);  len(m)
来源：http://dali.jinqigfzy.top/Article/details/gteaqvaqzn.html

Ruby: x.length;  x.size
来源：http://dali.zhengqikj.top/Article/details/gtmwbhcjes.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.kuanghao11.cn/Article/details/gteabotnxd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yuxming.cn/Article/details/gtjfirpdwu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhongyouzk.top/Article/details/gtnqmbnxbr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnausvjtw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenjidiqi.icu/Article/details/gtogazxfup.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cucudq.cn/Article/details/gtfmuspykg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jqgufenzy.top/Article/details/gtnunfpgvm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.wangdashe.top/Article/details/gtkkowrzsu.html

Ruby: a == b
来源：http://dali.cqqwz.cn/Article/details/gtqjzkebfh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jlsjyb.cn/Article/details/gtfxswaaxb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nanxinkj.top/Article/details/gtarraewzy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.snrcjt.cn/Article/details/gtwikutode.html

PHP:  if (empty($x)) {}
来源：http://dali.xinyue.icu/Article/details/gtezmfdmuk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nanxinkj.top/Article/details/gtsrlzoirz.html

TS:   if (x == null) {}
来源：http://dali.hammf.cn/Article/details/gtrubmfhal.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.316326.xyz/Article/details/gttezfvgdt.html

Go:   if x == nil {}
来源：http://dali.guowangkeji.top/Article/details/gtjmndcaqa.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.wangshuangyany.cn/Article/details/gtbibxfswe.html

C#:   if (x is null) {}
来源：http://dali.iojbl.cn/Article/details/gtsqskejuh.html

[P07] 防抖与节流
来源：http://dali.smart0.xyz/Article/details/gtjjgpdbyl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yuxming.cn/Article/details/gtvslqyfzj.html

PHP:  // 手写时间戳比较
来源：http://dali.nanxuanxn.top/Article/details/gtsupcqbyt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.svipenyu.cn/Article/details/gtddfiizqx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenzaomai.com/Article/details/gtegzyaiwa.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.fengsongda.top/Article/details/gtusmzpjaz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfawnveub.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gaohongyu789.top/Article/details/gtfzofbaks.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hnxiangtu.top/Article/details/gtfaupoofb.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gtturauzvs.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.haohaochexian.top/Article/details/gtvofedqqn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gogol.net.cn/Article/details/gthuejnymr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.smart0.xyz/Article/details/gtuwmqniyb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.redwolf501.top/Article/details/gtvjvxpwnm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.tanke756.top/Article/details/gtvgzffivj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhoulong.xyz/Article/details/gtcapbozos.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yvedp.cn/Article/details/gtibeixazf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.c1oappe.top/Article/details/gtexkpsvir.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtuxlnkwqe.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.vqdsnc.cn/Article/details/gtbuxjliyn.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqymyymj.html

[Q01] 创建表
来源：http://dali.andypj.xyz/Article/details/gtswtyzqwm.html

CREATE TABLE users (
来源：http://dali.316326.xyz/Article/details/gtwzshuvea.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.kuanghao11.cn/Article/details/gtcybzgvuv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ybcxt.top/Article/details/gtnfjibfeo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoybrggkt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xinyue.icu/Article/details/gtththpbzx.html

);
来源：http://dali.birdmap.top/Article/details/gtrgvlbuns.html

[Q02] 创建带外键的表
来源：http://dali.cdnleiting.top/Article/details/gtwyuubctq.html

CREATE TABLE orders (
来源：http://dali.sysykeji.top/Article/details/gtghpzwbdu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ivvv.top/Article/details/gtvqjyzzcy.html

user_id INT NOT NULL,
来源：http://dali.hammf.cn/Article/details/gtheftjgjh.html

amount DECIMAL(10, 2),
来源：http://dali.tanke756.top/Article/details/gtztktrztv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ydzc1.top/Article/details/gtkxcddosx.html

);
来源：http://dali.yuanzhike.top/Article/details/gtmijyqrcc.html

[Q03] 增加列
来源：http://dali.dashuyun.cn/Article/details/gtghjldnbd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.birdmap.top/Article/details/gttymypijy.html

[Q04] 修改列类型
来源：http://dali.xuanzx.com/Article/details/gtscxifhzw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgqiukmrh.html

[Q05] 重命名列
来源：http://dali.yj20258888.top/Article/details/gtbrrgurqb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.aibaodan.cn/Article/details/gtlroyjksn.html

[Q06] 删除列
来源：http://dali.cashguo.top/Article/details/gtguxfdnuh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinqigufen.top/Article/details/gtwhlpqzhh.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gtxmmfvtpd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xziqi.cn/Article/details/gtpclqqtgb.html

[Q08] 创建普通索引
来源：http://dali.9152youxi.cn/Article/details/gtkhjgialq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jqgufenzy.top/Article/details/gtlweulshq.html

[Q09] 创建唯一索引
来源：http://dali.cashguo.top/Article/details/gtzlmchblc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinyuanbaomall.cn/Article/details/gturepvwtd.html

[Q10] 插入单行
来源：http://dali.gaohongyu789.top/Article/details/gtdiooymiq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cqqwz.cn/Article/details/gtxfsjjbat.html

[Q11] 一次插入多行
来源：http://dali.xylfe.cn/Article/details/gtosfznyym.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tianlin.xyz/Article/details/gtidnxwfod.html

[Q12] 插入后取自增 ID
来源：http://dali.yuanzhike.top/Article/details/gtaitfoego.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinqigufen.top/Article/details/gtfevuncdj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ppjwa.cn/Article/details/gthjdyzbvc.html

[Q13] 忽略重复插入
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyskqwjcq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gtgaysitii.html

[Q14] 存在则更新（upsert）
来源：http://dali.yj20258888.top/Article/details/gtvjeyputd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xinyue.icu/Article/details/gtudgjjqdd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.guowangkeji.top/Article/details/gthpgqycpk.html

[Q15] 查询全部
来源：http://dali.jqgfzy.top/Article/details/gtywoxipgy.html

SELECT * FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtreuzffov.html

[Q16] 查询指定列
来源：http://dali.havefunace.top/Article/details/gtyfmulqwt.html

SELECT id, name FROM users;
来源：http://dali.nwbrower.top/Article/details/gtrnmumfbg.html

[Q17] 条件查询
来源：http://dali.yangfankeji.com/Article/details/gtbcpgxcmg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.pycfn.com/Article/details/gtwxnbkeil.html

[Q18] 模糊匹配
来源：http://dali.havefunace.top/Article/details/gtwgexirkp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shzxlz.cn/Article/details/gtpdnrxlnx.html

[Q19] 范围查询
来源：http://dali.sweek.top/Article/details/gtqdwuhlpy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhongyouzk.top/Article/details/gtlsjefbqa.html

[Q20] IN 列表
来源：http://dali.sxryk.cn/Article/details/gtwdantxjl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jianghu66.top/Article/details/gtjlorbyiy.html

[Q21] 空值判断
来源：http://dali.zhiwuduotai.top/Article/details/gtvslkdxgc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sxryk.cn/Article/details/gtnmgypkcb.html

[Q22] 排序
来源：http://dali.daxiang520.top/Article/details/gtqkjurcav.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jlsjyb.cn/Article/details/gtlzbabend.html

[Q23] 分页
来源：http://dali.cheryme.top/Article/details/gtbeviowbq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gaohongyu789.top/Article/details/gtnsmjdmrf.html

[Q24] 去重
来源：http://dali.jiagoushi.top/Article/details/gtyybhcwkd.html

SELECT DISTINCT city FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtedogecug.html

[Q25] 只取前 N 条
来源：http://dali.aibaodan.cn/Article/details/gtimamutvb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tianlin.xyz/Article/details/gtjrklecgm.html

[Q26] 计数
来源：http://dali.hysaishi.cn/Article/details/gtxgzdgzap.html

SELECT COUNT(*) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtezzmbuzr.html

[Q27] 条件计数
来源：http://dali.daria6918.cn/Article/details/gtrwkrthyn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtxqwbootv.html

[Q28] 求和与平均
来源：http://dali.cashguo.top/Article/details/gtiyhunzot.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtutqiqmcl.html

[Q29] 最大最小值
来源：http://dali.vqdsnc.cn/Article/details/gtxnfijodk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtgnimeykf.html

[Q30] 分组统计
来源：http://dali.shangyingyoupin.top/Article/details/gtwaajsour.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gtlyhcthkp.html

[Q31] 分组后过滤
来源：http://dali.redwolf501.top/Article/details/gtuyamqwhi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhongyouzk.top/Article/details/gthszvcjss.html

[Q32] 分组拼接字符串
来源：http://dali.cucudq.cn/Article/details/gtlbjldptk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gtiwoombmx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.wangdashe.top/Article/details/gtbvzzttff.html

[Q33] 多列分组
来源：http://dali.redwolf501.top/Article/details/gtepwchqdc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.mhx1999.top/Article/details/gthfrkrlql.html

[Q34] 每组取第一条
来源：http://dali.jqgfzy.top/Article/details/gttdigssvt.html

SELECT * FROM (
来源：http://dali.dashuyun.cn/Article/details/gtewycqack.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.0kj1m.cn/Article/details/gtxhdymigi.html

) t WHERE rn = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlddettxb.html

[Q35] 内连接
来源：http://dali.tian-w.cn/Article/details/gtzywcrbkx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jianghu66.top/Article/details/gtuwdjzhxv.html

[Q36] 左连接
来源：http://dali.andypj.xyz/Article/details/gtplghygdf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.svipenyu.cn/Article/details/gtvzyloevy.html

[Q37] 右连接
来源：http://dali.c1oappe.top/Article/details/gteehzcxtd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwevjcvxk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.andypj.xyz/Article/details/gtvwifujgb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hywenlv.cn/Article/details/gtewiuuhxs.html

[Q39] 自连接（查上下级）
来源：http://dali.zhixingplan.top/Article/details/gtfaizsvyv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tian-w.cn/Article/details/gtibcsrsyf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sysykeji.top/Article/details/gtlbokntjg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.pycfn.com/Article/details/gtbkrwvaqg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.fengsongda.top/Article/details/gtgvuxdgws.html

[Q41] 多表连接
来源：http://dali.mhx1999.top/Article/details/gttbcywnup.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gzhubu.top/Article/details/gtanhzrvum.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hywenlv.cn/Article/details/gtwfwszpda.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulfkcuzl.html

[Q42] 连接条件附加过滤
来源：http://dali.tian-w.cn/Article/details/gtonkocotq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yvedp.cn/Article/details/gtmtuqyzpl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cucudq.cn/Article/details/gtyupdgawm.html

[Q43] 标量子查询
来源：http://dali.dashuyun.cn/Article/details/gtknqeynzf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.0kj1m.cn/Article/details/gthvjtjxmz.html

[Q44] IN 子查询
来源：http://dali.sysykeji.top/Article/details/gtazqiumdg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtblryjkwv.html

[Q45] EXISTS 判断存在
来源：http://dali.gaohongyu789.top/Article/details/gtlqlwczhm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuanzx.com/Article/details/gtparkqmuu.html


<!-- 参考信息 -->