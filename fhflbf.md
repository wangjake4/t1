代发 wailian999

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ehwqpu.com/Article/details/gtqammijmj.html

[N06] 判断回文字符串
来源：http://dali.smart0.xyz/Article/details/gtrkyhxfup.html

Py:   s == s[::-1]
来源：http://dali.nanxinkj.top/Article/details/gtigxhongm.html

PHP:  $s === strrev($s);
来源：http://dali.ydzc1.top/Article/details/gtmlmiofvv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gtksaklsdm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gtstyfchbl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tianlin.xyz/Article/details/gtbvevefwm.html

Go:   // 双指针从两端比较
来源：http://dali.nanxuanxn.top/Article/details/gtbdrcydmw.html

Ruby: s == s.reverse
来源：http://dali.gotoacloud.top/Article/details/gtxcycxptw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinghuilouyu.cn/Article/details/gtplybttns.html

[N07] 两数之和（返回下标）
来源：http://dali.yongpay.top/Article/details/gtmzxeczkk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangtech.top/Article/details/gtuuulsdha.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.aibaodan.cn/Article/details/gtmrxpqiyp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.birdmap.top/Article/details/gtwfgajrkh.html

TS:   // 手写 Map<string, number>
来源：http://dali.guowangkeji.top/Article/details/gtfribbjxv.html

Java: // 手写 HashMap
来源：http://dali.bjfxy.top/Article/details/gtcilgsbor.html

Go:   // 手写 map[int]int
来源：http://dali.0kj1m.cn/Article/details/gtejfnjgal.html

Ruby: // 手写 Hash
来源：http://dali.cqqwz.cn/Article/details/gtuzimzfhh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sysykeji.top/Article/details/gtqlfqbeyo.html

[N08] 生成全排列
来源：http://dali.yueranfly.top/Article/details/gtooirkxsk.html

Py:   itertools.permutations(arr)
来源：http://dali.yongpay.top/Article/details/gtymuimvqs.html

PHP:  // 手写递归交换
来源：http://dali.hammf.cn/Article/details/gtpktxpvjf.html

JS:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtrhkxgivo.html

TS:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtzjoeldvw.html

Java: // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtyxqrjnpp.html

Go:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtsrufbnct.html

Ruby: arr.permutation.to_a
来源：http://dali.hnxiangtu.top/Article/details/gtgqqvfucm.html

C#:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkmcbwqif.html

[N09] 栈与队列
来源：http://dali.redwolf501.top/Article/details/gtipujlkgi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hammf.cn/Article/details/gtnekeoupq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.redwolf501.top/Article/details/gtiqqtqyre.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yvedp.cn/Article/details/gtucvaepiu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.meibo888.top/Article/details/gtgfqjgsbz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sysykeji.top/Article/details/gtowlakkrf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shanyushiyangtech.top/Article/details/gtknpfspgm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtmwiwlyuw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.dianchejie.cn/Article/details/gtuthldqga.html

[N10] 链表节点定义
来源：http://dali.birdmap.top/Article/details/gthdcxtlnc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cdnleiting.top/Article/details/gtfjcdttyg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.aibaodan.cn/Article/details/gtviejfleu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrwhgipdn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shuidangran.top/Article/details/gthaeskzbs.html

Java: class Node { int v; Node next; }
来源：http://dali.yj202588.top/Article/details/gtionyafxg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cashguo.top/Article/details/gtqljsmnou.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinqigufen.top/Article/details/gtsnnefnbf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbzzrotl.html

[N11] 二叉树中序遍历
来源：http://dali.jlsjyb.cn/Article/details/gtqyszwmrt.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.daxiang520.top/Article/details/gtmicwwxot.html

PHP:  // 手写递归函数
来源：http://dali.0kj1m.cn/Article/details/gtmccjhiri.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.bjfxy.top/Article/details/gttdruehrx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhongyouzk.top/Article/details/gtocuyflrv.html

Java: // 手写递归
来源：http://dali.hfpthk.cn/Article/details/gtahfooorn.html

Go:   // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gtgtmjyqwu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gzhubu.top/Article/details/gttiwindpk.html

C#:   // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gtjgzmizdy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xuetiantiany.cn/Article/details/gtrfmbvlhl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jyoumei.cn/Article/details/gtzftyxhxi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinghuilouyu.cn/Article/details/gtiqykcbua.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nwbrower.top/Article/details/gtaxxqncgc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.redwolf501.top/Article/details/gtohvtmand.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnxiangtu.top/Article/details/gtyxfnvqqk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.daria6918.cn/Article/details/gtkojsqrcy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zdqjudy.top/Article/details/gtlblbxiik.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cdnleiting.top/Article/details/gtpqaaqrlx.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtnkdpzrly.html

O. 并发与异步
来源：http://dali.dashuyun.cn/Article/details/gtwvtpvsct.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtmjqufqjs.html

[O01] 启动一个线程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvaulxqa.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nanxuanxn.top/Article/details/gtcghaothg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tanke756.top/Article/details/gtoannmqsj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.havefunace.top/Article/details/gtzxuagnfd.html

TS:   // 同 JS
来源：http://dali.ydzc1.top/Article/details/gtwuzmqmoy.html

Java: new Thread(() -> f()).start()
来源：http://dali.ydzc1.top/Article/details/gtukymwkey.html

Go:   go f()
来源：http://dali.zycfv.cn/Article/details/gtxobvypbw.html

Ruby: Thread.new { f }
来源：http://dali.zhiwuduotai.top/Article/details/gtknznihlv.html

C#:   Task.Run(() => F());
来源：http://dali.nwbrower.top/Article/details/gthdznkqrk.html

[O02] 使用线程池
来源：http://dali.yuxming.cn/Article/details/gtfxpfjdml.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuiilobxq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.iojbl.cn/Article/details/gtossnxxdq.html

JS:   // worker_threads 线程池
来源：http://dali.yvedp.cn/Article/details/gtopxbwcbc.html

TS:   // worker_threads 线程池
来源：http://dali.pengpengdd.cyou/Article/details/gtnsixpccy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ppjwa.cn/Article/details/gtlebswkvf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.daxiang520.top/Article/details/gtwjhkpmjw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.wangdashe.top/Article/details/gtgabejkhk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.vqdsnc.cn/Article/details/gtfcjzujxi.html

[O03] 加锁保护共享数据
来源：http://dali.redwolf501.top/Article/details/gtchyitgax.html

Py:   with lock: shared += 1
来源：http://dali.yonumen.top/Article/details/gtolxrakff.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinyuanbaomall.cn/Article/details/gtywgioncz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenlongwang.top/Article/details/gtcnfudszj.html

TS:   // 同 JS
来源：http://dali.zhoulong.xyz/Article/details/gtjqodgraj.html

Java: synchronized (this) { shared++; }
来源：http://dali.daria6918.cn/Article/details/gthwlkluug.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nanxinkj.top/Article/details/gtucgkuzis.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xylfe.cn/Article/details/gtirfjzzrt.html

C#:   lock (gate) { shared++; }
来源：http://dali.guowangkeji.top/Article/details/gtphytlahb.html

[O04] 定义异步函数并等待
来源：http://dali.c1oappe.top/Article/details/gtyqrgiteu.html

Py:   async def f():⏎    await g()
来源：http://dali.xylfe.cn/Article/details/gtfiggnvhj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yanxiufei.cn/Article/details/gtovdakzzf.html

JS:   async function f() { await g(); }
来源：http://dali.cqqwz.cn/Article/details/gtwraoycih.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cqqwz.cn/Article/details/gtaywvgola.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cqqwz.cn/Article/details/gtytosioaq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.birdmap.top/Article/details/gtxyczvgdg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfrzaququ.html

C#:   async Task F() { await G(); }
来源：http://dali.yuanzhike.top/Article/details/gtqybwlsao.html

[O05] 并发执行并等待全部完成
来源：http://dali.kuanghao11.cn/Article/details/gththslilt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvwpbfsyc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nwbrower.top/Article/details/gtcllfepil.html

JS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gtpxfvnemv.html

TS:   await Promise.all(tasks)
来源：http://dali.tanke756.top/Article/details/gtrkfpxveh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gaohongyu789.top/Article/details/gtudfsjbhw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.c1oappe.top/Article/details/gtlijngfdv.html

Ruby: threads.map(&:join)
来源：http://dali.jinqigufen.top/Article/details/gtgidsskzx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nanxinkj.top/Article/details/gtekximnqo.html

[O06] 使用进程池
来源：http://dali.zhengqikj.top/Article/details/gthkmfybcs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hnxiangtu.top/Article/details/gtpqkhcwif.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yongpay.top/Article/details/gtgaosbzjp.html

JS:   // child_process / cluster 模块
来源：http://dali.zhongyouzk.top/Article/details/gtbprioovr.html

TS:   // child_process / cluster 模块
来源：http://dali.aibaodan.cn/Article/details/gtlyaumlgo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shzxlz.cn/Article/details/gtqqxvpezn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hysaishi.cn/Article/details/gtdusnhmml.html

Ruby: // fork 块
来源：http://dali.nwbrower.top/Article/details/gtaanyymfc.html

C#:   Parallel.For
来源：http://dali.zdqjudy.top/Article/details/gtntylstol.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtiohdgmsj.html

P. 常用工具函数
来源：http://dali.gaohongyu789.top/Article/details/gttlkebvil.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtilriplpp.html

[P01] 生成 UUID
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdugvzemk.html

Py:   str(uuid.uuid4())
来源：http://dali.yvedp.cn/Article/details/gtqholbkmg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.aibaodan.cn/Article/details/gtsnbzffvh.html

JS:   crypto.randomUUID()
来源：http://dali.iojbl.cn/Article/details/gtlqffduwo.html

TS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwllwifr.html

Java: UUID.randomUUID().toString()
来源：http://dali.vqdsnc.cn/Article/details/gttzgcyehw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhongyouzk.top/Article/details/gtndbmnsia.html

Ruby: SecureRandom.uuid
来源：http://dali.wangshuangyany.cn/Article/details/gttxprbovf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.aibaodan.cn/Article/details/gtmgoelgro.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinqigfzy.top/Article/details/gteewheavf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ybcxt.top/Article/details/gtgieahbvq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gogol.net.cn/Article/details/gtyjmwqmzc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sysykeji.top/Article/details/gtyhejshfw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tianlin.xyz/Article/details/gtouvyfwcu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzcluxtdb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yongpay.top/Article/details/gtfmpzrxdx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtickjcchy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shzxlz.cn/Article/details/gtulujfjak.html

[P03] 生成短随机字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtcxoocvqr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuetiantiany.cn/Article/details/gtrnjyqpct.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenlongwang.top/Article/details/gtnexdzgqu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daxiang520.top/Article/details/gtuysnwshs.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.vqdsnc.cn/Article/details/gtnzhwnocw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.guowangkeji.top/Article/details/gtuktmofso.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yanxiufei.cn/Article/details/gthsmqfhml.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj202588.top/Article/details/gtmasvzcdf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhixingplan.top/Article/details/gteegxthaj.html

[P04] 求长度
来源：http://dali.xuetiantiany.cn/Article/details/gtafahxwjy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.fzhhl.top/Article/details/gtxojlzckn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gtdvmklqev.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhixingplan.top/Article/details/gtvizvgbxt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sxryk.cn/Article/details/gtpltpxsqf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj20258888.top/Article/details/gtjdgxzbgp.html

Go:   len(arr);  len(m)
来源：http://dali.vqdsnc.cn/Article/details/gtthutpgag.html

Ruby: x.length;  x.size
来源：http://dali.zdqjudy.top/Article/details/gtfdjqdttq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiocdrlnu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.birdmap.top/Article/details/gtgixutuib.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hongshengwenyu.top/Article/details/gtenpvhjwt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cheryme.top/Article/details/gtoglwqpfq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnwfnhman.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuanzx.com/Article/details/gtkinqjrkv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinqigufen.top/Article/details/gtsxhebpzb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hfpthk.cn/Article/details/gtajhsmclf.html

Ruby: a == b
来源：http://dali.yongpay.top/Article/details/gtndwwtzdr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yvedp.cn/Article/details/gtetujmlcn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.9152youxi.cn/Article/details/gtkvmdirhy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tianlin.xyz/Article/details/gtugkvdkhc.html

PHP:  if (empty($x)) {}
来源：http://dali.shzxlz.cn/Article/details/gteknuwhpx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yanxiufei.cn/Article/details/gtmdlvmwhw.html

TS:   if (x == null) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkadykjij.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.316326.xyz/Article/details/gtfyupzrth.html

Go:   if x == nil {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtceijerzn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gotoacloud.top/Article/details/gtznoqcnoy.html

C#:   if (x is null) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtghgvqvgq.html

[P07] 防抖与节流
来源：http://dali.zhengqikj.top/Article/details/gtkbedrqkk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinqigfzy.top/Article/details/gtdlamkgei.html

PHP:  // 手写时间戳比较
来源：http://dali.yj20258.top/Article/details/gtvlgcvsjq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cheryme.top/Article/details/gtjpoxlbjp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gtqifxemac.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yonumen.top/Article/details/gtfiwpyenl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cdnleiting.top/Article/details/gtxodjitod.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hammf.cn/Article/details/gtoyuwrehn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.feifeiyinyue.top/Article/details/gtzdwplkym.html

[P08] 处理浮点精度问题
来源：http://dali.zhengqikj.top/Article/details/gtndixnmnd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlkqdfrrh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xuanzx.com/Article/details/gtzjyzzzdx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xziqi.cn/Article/details/gtftpumica.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zdqjudy.top/Article/details/gtocwgoiax.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.daria6918.cn/Article/details/gtlgjdktmk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhoulong.xyz/Article/details/gtfnlmluyf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.dashuyun.cn/Article/details/gtgsbtvlyd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.guannengcc.top/Article/details/gtdqdlrgqg.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtxeucygcx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ppjwa.cn/Article/details/gtihpghiuh.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtwlveyelp.html

[Q01] 创建表
来源：http://dali.pycfn.com/Article/details/gtoqdvrpgl.html

CREATE TABLE users (
来源：http://dali.hysaishi.cn/Article/details/gttrphlsvl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfkvnjwrs.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gzhubu.top/Article/details/gtlcscozfi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.redwolf501.top/Article/details/gtpusprspo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.mhx1999.top/Article/details/gtpoatsxnu.html

);
来源：http://dali.hnxiangtu.top/Article/details/gtukujolwg.html

[Q02] 创建带外键的表
来源：http://dali.yuanzhike.top/Article/details/gtwmqqgldi.html

CREATE TABLE orders (
来源：http://dali.gogol.net.cn/Article/details/gtyanbbfvy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.birdmap.top/Article/details/gtiwadscvt.html

user_id INT NOT NULL,
来源：http://dali.dashuyun.cn/Article/details/gtrpvacddh.html

amount DECIMAL(10, 2),
来源：http://dali.tian-w.cn/Article/details/gtbkjivbuk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dianchejie.cn/Article/details/gterhjncaa.html

);
来源：http://dali.zycfv.cn/Article/details/gtpqmevinp.html

[Q03] 增加列
来源：http://dali.birdmap.top/Article/details/gtryfatcod.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinghuilouyu.cn/Article/details/gtlndpvpyx.html

[Q04] 修改列类型
来源：http://dali.hongshengwenyu.top/Article/details/gtbqbofnzc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zdqjudy.top/Article/details/gtbafmdqjf.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gtqvuwmjhb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.0kj1m.cn/Article/details/gtapqjkeat.html

[Q06] 删除列
来源：http://dali.chenlongwang.top/Article/details/gtlljwphvf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hnxiangtu.top/Article/details/gthnlxwfct.html

[Q07] 删除表
来源：http://dali.havefunace.top/Article/details/gtzlwamwnd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cashguo.top/Article/details/gtvuhrutbm.html

[Q08] 创建普通索引
来源：http://dali.jinqigufen.top/Article/details/gthttigpgi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hnqzz.top/Article/details/gthkwlltqu.html

[Q09] 创建唯一索引
来源：http://dali.xziqi.cn/Article/details/gtixvgobab.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sysykeji.top/Article/details/gtubxunqhf.html

[Q10] 插入单行
来源：http://dali.snrcjt.cn/Article/details/gtzkxpyxxw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj20258888.top/Article/details/gtrhabnjog.html

[Q11] 一次插入多行
来源：http://dali.sysykeji.top/Article/details/gtktslfcgf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj20258888.top/Article/details/gtpwuqvunb.html

[Q12] 插入后取自增 ID
来源：http://dali.xziqi.cn/Article/details/gtqpfyskkg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.kuanghao11.cn/Article/details/gtauuliyue.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.snrcjt.cn/Article/details/gtsiajbamx.html

[Q13] 忽略重复插入
来源：http://dali.smart0.xyz/Article/details/gtzpiovncv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhixingplan.top/Article/details/gtoxdwjtzf.html

[Q14] 存在则更新（upsert）
来源：http://dali.dashuyun.cn/Article/details/gtbjeegnag.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hysaishi.cn/Article/details/gtmadaimdi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.wangshuangyany.cn/Article/details/gtkmyneanh.html

[Q15] 查询全部
来源：http://dali.hywenlv.cn/Article/details/gtseqlngfz.html

SELECT * FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtsezdmlln.html

[Q16] 查询指定列
来源：http://dali.jianghu66.top/Article/details/gtbgdvttvo.html

SELECT id, name FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtifgasozg.html

[Q17] 条件查询
来源：http://dali.yuanzhike.top/Article/details/gtlbdkrcmk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhixingplan.top/Article/details/gttmkhmeiv.html

[Q18] 模糊匹配
来源：http://dali.xziqi.cn/Article/details/gtslloyvhf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xuetiantiany.cn/Article/details/gtdkerzmeo.html

[Q19] 范围查询
来源：http://dali.cqqwz.cn/Article/details/gtoyekihgu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.mhx1999.top/Article/details/gtfdtfgflw.html

[Q20] IN 列表
来源：http://dali.hnxiangtu.top/Article/details/gtlkzantno.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ybcxt.top/Article/details/gtpsimbemv.html

[Q21] 空值判断
来源：http://dali.hnxiangtu.top/Article/details/gtpzmsfrql.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yueranfly.top/Article/details/gtatqqyaie.html

[Q22] 排序
来源：http://dali.tianlin.xyz/Article/details/gtjkuhhxcz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ybcxt.top/Article/details/gtuewelmzh.html

[Q23] 分页
来源：http://dali.fzhhl.top/Article/details/gtuonzulhk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xuanzx.com/Article/details/gtfmrgqlgg.html

[Q24] 去重
来源：http://dali.gzhubu.top/Article/details/gtlnopxybb.html

SELECT DISTINCT city FROM users;
来源：http://dali.sweek.top/Article/details/gtopmyprme.html

[Q25] 只取前 N 条
来源：http://dali.0kj1m.cn/Article/details/gtsplvwrab.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.fengsongda.top/Article/details/gtqtsffexu.html

[Q26] 计数
来源：http://dali.mhx1999.top/Article/details/gtolyfypaa.html

SELECT COUNT(*) FROM users;
来源：http://dali.yongpay.top/Article/details/gtiftmuthr.html

[Q27] 条件计数
来源：http://dali.gogol.net.cn/Article/details/gtuprmqmpv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtibqvgzlz.html

[Q28] 求和与平均
来源：http://dali.sweek.top/Article/details/gtwtqkpgld.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtbqtwenwk.html

[Q29] 最大最小值
来源：http://dali.zhoulong.xyz/Article/details/gtazntntad.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyljnbxtf.html

[Q30] 分组统计
来源：http://dali.yanxiufei.cn/Article/details/gtlpmydjup.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gthxijlhoe.html

[Q31] 分组后过滤
来源：http://dali.feifeiyinyue.top/Article/details/gthsgdyfrz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhiwuduotai.top/Article/details/gtuylcyfrn.html

[Q32] 分组拼接字符串
来源：http://dali.c1oappe.top/Article/details/gtpvpjbbha.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gtnfjdsnmt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttljjxcvb.html

[Q33] 多列分组
来源：http://dali.iojbl.cn/Article/details/gtyzucpybi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yj202588.top/Article/details/gtsuposxmf.html

[Q34] 每组取第一条
来源：http://dali.mhx1999.top/Article/details/gtlwxteszu.html

SELECT * FROM (
来源：http://dali.ehwqpu.com/Article/details/gthpfbjnox.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tian-w.cn/Article/details/gtnprwukgy.html

) t WHERE rn = 1;
来源：http://dali.redwolf501.top/Article/details/gtnayqytzm.html

[Q35] 内连接
来源：http://dali.zhoulong.xyz/Article/details/gtezdzxsqc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgfzy.top/Article/details/gtcalmnlrz.html

[Q36] 左连接
来源：http://dali.daria6918.cn/Article/details/gtzosyuthb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgufenzy.top/Article/details/gtycjtnoky.html

[Q37] 右连接
来源：http://dali.gogol.net.cn/Article/details/gtrdideapo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.nwbrower.top/Article/details/gtmuqaefnv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.redwolf501.top/Article/details/gtjcnmbqcc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jiagoushi.top/Article/details/gtuxqcbplq.html

[Q39] 自连接（查上下级）
来源：http://dali.fzhhl.top/Article/details/gtbbuzndfd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gotoacloud.top/Article/details/gtylsetojm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hnxiangtu.top/Article/details/gtnzjevbxs.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.birdmap.top/Article/details/gtxugmnozq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchzotxjj.html

[Q41] 多表连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuexqiomx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cdnleiting.top/Article/details/gtmtbqszkr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.quarkkingdee.top/Article/details/gtxrlhgmkz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cdnleiting.top/Article/details/gtnverukdd.html

[Q42] 连接条件附加过滤
来源：http://dali.birdmap.top/Article/details/gtnxbgzrfx.html


<!-- 参考信息 -->