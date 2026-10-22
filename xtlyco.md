代发 wailian999

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dianchejie.cn/Article/details/gtwhpopdqg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.pengpengdd.cyou/Article/details/gtvgfxwdhe.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.kuanghao11.cn/Article/details/gthlrmivhy.html

Ruby: a.gcd(b)
来源：http://dali.hammf.cn/Article/details/gtqvncztbs.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fengsongda.top/Article/details/gtwkmdtryq.html

[N06] 判断回文字符串
来源：http://dali.haohaochexian.top/Article/details/gtorqheldp.html

Py:   s == s[::-1]
来源：http://dali.zdqjudy.top/Article/details/gtbbrihvmu.html

PHP:  $s === strrev($s);
来源：http://dali.yj202588.top/Article/details/gtentmpzuw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtzrtwgcpg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gtpdnrytqb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.birdmap.top/Article/details/gtugdbzhiu.html

Go:   // 双指针从两端比较
来源：http://dali.wangdashe.top/Article/details/gtqpppnogl.html

Ruby: s == s.reverse
来源：http://dali.jiagoushi.top/Article/details/gtoiclcubp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shuidangran.top/Article/details/gtdshyfvcb.html

[N07] 两数之和（返回下标）
来源：http://dali.gzhubu.top/Article/details/gtgoqdlpip.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinghuilouyu.cn/Article/details/gtfyywxpiv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.aizwys.cn/Article/details/gtgplfkfca.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jlsjyb.cn/Article/details/gtyzgjlkrn.html

TS:   // 手写 Map<string, number>
来源：http://dali.yuxming.cn/Article/details/gtqxegiios.html

Java: // 手写 HashMap
来源：http://dali.jiagoushi.top/Article/details/gtqryhlglb.html

Go:   // 手写 map[int]int
来源：http://dali.cdnleiting.top/Article/details/gtddknhdkd.html

Ruby: // 手写 Hash
来源：http://dali.andypj.xyz/Article/details/gtygsdbwtr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sweek.top/Article/details/gtrobdmiol.html

[N08] 生成全排列
来源：http://dali.yongpay.top/Article/details/gtklcvcwai.html

Py:   itertools.permutations(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtrlxtpjrd.html

PHP:  // 手写递归交换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzpxbvkgu.html

JS:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtijkcygjg.html

TS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtatrrhfyw.html

Java: // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtjcqxgldx.html

Go:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtnjwyxbxr.html

Ruby: arr.permutation.to_a
来源：http://dali.fzhhl.top/Article/details/gtscjrirwn.html

C#:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gtarysapuw.html

[N09] 栈与队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsaaxaqth.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yuxming.cn/Article/details/gtesfrqlgi.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xinyue.icu/Article/details/gtovastqle.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zycfv.cn/Article/details/gtxvwymugy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sysykeji.top/Article/details/gtpguzjiam.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj202588.top/Article/details/gtlypewwyq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ydzc1.top/Article/details/gtpzaiermq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cheryme.top/Article/details/gtsjdhermg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.meibo888.top/Article/details/gtqhidfpyy.html

[N10] 链表节点定义
来源：http://dali.hywenlv.cn/Article/details/gtzkqhlifm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zdqjudy.top/Article/details/gtseemmsko.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nanxuanxn.top/Article/details/gtqdgktiwg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sweek.top/Article/details/gtlhhqlzzq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhixingplan.top/Article/details/gtkjunijbk.html

Java: class Node { int v; Node next; }
来源：http://dali.tanke756.top/Article/details/gtwdxtgese.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.bjfxy.top/Article/details/gtktuuipbb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nanxinkj.top/Article/details/gtnvptyhqt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ivvv.top/Article/details/gtczcpbdzp.html

[N11] 二叉树中序遍历
来源：http://dali.bjfxy.top/Article/details/gtaacehlkj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hfpthk.cn/Article/details/gtmvzpxyky.html

PHP:  // 手写递归函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtacvcrbzv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cqqwz.cn/Article/details/gtbrndsjbs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhiwuduotai.top/Article/details/gtapgchytk.html

Java: // 手写递归
来源：http://dali.xziqi.cn/Article/details/gtnxwsphmb.html

Go:   // 手写递归
来源：http://dali.aizwys.cn/Article/details/gtdciyddjw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gotoacloud.top/Article/details/gthgosghgb.html

C#:   // 手写递归
来源：http://dali.smart0.xyz/Article/details/gthlhqtowa.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.dashuyun.cn/Article/details/gtsafpglxw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jqgufenzy.top/Article/details/gtoayrrfvf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shzxlz.cn/Article/details/gtitwnanit.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgufenzy.top/Article/details/gtiffazqav.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fengsongda.top/Article/details/gtiefnegay.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258.top/Article/details/gtrajepqco.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.meibo888.top/Article/details/gtifdffcbj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.kuanghao11.cn/Article/details/gtbvadwsch.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gogol.net.cn/Article/details/gtiqmjcxjd.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtykspuffr.html

O. 并发与异步
来源：http://dali.sxryk.cn/Article/details/gteqvnpgkz.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtvjnqxdds.html

[O01] 启动一个线程
来源：http://dali.yj202588.top/Article/details/gtwgkxhqpu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hywenlv.cn/Article/details/gtpedktitb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.wangdashe.top/Article/details/gtgsnsdcyx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.fengsongda.top/Article/details/gtubzgince.html

TS:   // 同 JS
来源：http://dali.zhengqikj.top/Article/details/gtsymmplgv.html

Java: new Thread(() -> f()).start()
来源：http://dali.tanke756.top/Article/details/gtgqkqserv.html

Go:   go f()
来源：http://dali.cdnleiting.top/Article/details/gtkbpqiavj.html

Ruby: Thread.new { f }
来源：http://dali.redwolf501.top/Article/details/gtanwdpeaf.html

C#:   Task.Run(() => F());
来源：http://dali.hysaishi.cn/Article/details/gtcehkueli.html

[O02] 使用线程池
来源：http://dali.chenjidiqi.icu/Article/details/gteyrxdwsq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinqigfzy.top/Article/details/gtduqighhu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ydzc1.top/Article/details/gtphokltyb.html

JS:   // worker_threads 线程池
来源：http://dali.jinqigufen.top/Article/details/gtkaotddwd.html

TS:   // worker_threads 线程池
来源：http://dali.feifeiyinyue.top/Article/details/gtklwfhgfb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yonumen.top/Article/details/gttjsukeym.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhongyouzk.top/Article/details/gtfdruoiei.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shzxlz.cn/Article/details/gtyaprmiak.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.c1oappe.top/Article/details/gtlgxpyonh.html

[O03] 加锁保护共享数据
来源：http://dali.chenlongwang.top/Article/details/gtkjoiuubf.html

Py:   with lock: shared += 1
来源：http://dali.cdnleiting.top/Article/details/gtpkzwhsbv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tanke756.top/Article/details/gtsadbuxiy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhongyouzk.top/Article/details/gtgwfguoxv.html

TS:   // 同 JS
来源：http://dali.316326.xyz/Article/details/gtlshzenuh.html

Java: synchronized (this) { shared++; }
来源：http://dali.jqgufenzy.top/Article/details/gtsjxtkwdz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nwbrower.top/Article/details/gtpgauptfv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yueranfly.top/Article/details/gtbsljhqmn.html

C#:   lock (gate) { shared++; }
来源：http://dali.ydzc1.top/Article/details/gtlzakhkxa.html

[O04] 定义异步函数并等待
来源：http://dali.fzhhl.top/Article/details/gttbjrsbzl.html

Py:   async def f():⏎    await g()
来源：http://dali.hongshengwenyu.top/Article/details/gtpbdxdbte.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhongyouzk.top/Article/details/gtlwyxdohg.html

JS:   async function f() { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gtgvqnirqd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.iojbl.cn/Article/details/gtpagswqdh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.mhx1999.top/Article/details/gtfmvknfab.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jyoumei.cn/Article/details/gtqgtghukn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.birdmap.top/Article/details/gtjjrhlspd.html

C#:   async Task F() { await G(); }
来源：http://dali.zdqjudy.top/Article/details/gtddevzcoi.html

[O05] 并发执行并等待全部完成
来源：http://dali.yonumen.top/Article/details/gtfcwfxjnp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tanke756.top/Article/details/gtjxdazesy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jyoumei.cn/Article/details/gtbyhynbiu.html

JS:   await Promise.all(tasks)
来源：http://dali.gogol.net.cn/Article/details/gtpatyodwz.html

TS:   await Promise.all(tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtumjocffu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.0kj1m.cn/Article/details/gtioqjnjto.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shzxlz.cn/Article/details/gtdjhtqwmb.html

Ruby: threads.map(&:join)
来源：http://dali.nanxuanxn.top/Article/details/gthksscpmg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttnxmpaha.html

[O06] 使用进程池
来源：http://dali.jqgfzy.top/Article/details/gtuvtcywka.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.kuanghao11.cn/Article/details/gthiudwqql.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yonumen.top/Article/details/gtcjhomeov.html

JS:   // child_process / cluster 模块
来源：http://dali.ehwqpu.com/Article/details/gtgwezivby.html

TS:   // child_process / cluster 模块
来源：http://dali.gaohongyu789.top/Article/details/gtsrzpyhmr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.redwolf501.top/Article/details/gtgljbccvw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tianlin.xyz/Article/details/gtzqcbqwvn.html

Ruby: // fork 块
来源：http://dali.yangfankeji.com/Article/details/gthnyctium.html

C#:   Parallel.For
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqsqpnuwd.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtgavsstwj.html

P. 常用工具函数
来源：http://dali.sxryk.cn/Article/details/gtiikmhmxg.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtivqcovbm.html

[P01] 生成 UUID
来源：http://dali.feifeiyinyue.top/Article/details/gtrxdvkzbe.html

Py:   str(uuid.uuid4())
来源：http://dali.nanxinkj.top/Article/details/gtoebrxxao.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nanxuanxn.top/Article/details/gtyvihirsi.html

JS:   crypto.randomUUID()
来源：http://dali.vqdsnc.cn/Article/details/gtpvkbskas.html

TS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gtqcamfxdm.html

Java: UUID.randomUUID().toString()
来源：http://dali.chenlongwang.top/Article/details/gtvpdbivpr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.redwolf501.top/Article/details/gtlxkovxoq.html

Ruby: SecureRandom.uuid
来源：http://dali.nanxuanxn.top/Article/details/gtrfljyakb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.svipenyu.cn/Article/details/gtieybodcx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.havefunace.top/Article/details/gtzlmeauid.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shangyingyoupin.top/Article/details/gtvxlkqbzj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.guannengcc.top/Article/details/gtinstcjii.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.c1oappe.top/Article/details/gtyguahylq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yongpay.top/Article/details/gtakoetjiq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.mhx1999.top/Article/details/gtgfldhgsx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ydzc1.top/Article/details/gthjnrluqd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.havefunace.top/Article/details/gtoxdsyirk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.havefunace.top/Article/details/gtttifqtbd.html

[P03] 生成短随机字符串
来源：http://dali.yvedp.cn/Article/details/gtoexehifz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yonumen.top/Article/details/gtqjldlypr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.snrcjt.cn/Article/details/gtevdzvnsf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxewbqxwq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xylfe.cn/Article/details/gtphywzpkc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yj20258.top/Article/details/gtehfytfii.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yvedp.cn/Article/details/gtthwyzvkb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.316326.xyz/Article/details/gthytlcopc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhiwuduotai.top/Article/details/gtdtonhbok.html

[P04] 求长度
来源：http://dali.jinghuilouyu.cn/Article/details/gttjijxrrn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.316326.xyz/Article/details/gtlnnkoefe.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gthyvwfvly.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgfzy.top/Article/details/gtwfettwgs.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gtdhdzqbrc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstynmdnf.html

Go:   len(arr);  len(m)
来源：http://dali.jqgufenzy.top/Article/details/gtokduaqsz.html

Ruby: x.length;  x.size
来源：http://dali.gotoacloud.top/Article/details/gtrduyydnl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.chenzaomai.com/Article/details/gtrtmbqsaz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.iojbl.cn/Article/details/gtlxxfjrvn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yonumen.top/Article/details/gtqrpgughs.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.dashuyun.cn/Article/details/gtoqflydro.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.c1oappe.top/Article/details/gtsiffnprh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cheryme.top/Article/details/gtvsmoiwqu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.smart0.xyz/Article/details/gtmrhmgqyz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yongpay.top/Article/details/gtqhuygaqs.html

Ruby: a == b
来源：http://dali.jinqigfzy.top/Article/details/gtkkxbvlku.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cucudq.cn/Article/details/gtwlvmkdkr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sysykeji.top/Article/details/gthnqbqsdl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.sweek.top/Article/details/gtyboanqdu.html

PHP:  if (empty($x)) {}
来源：http://dali.chenlongwang.top/Article/details/gtabzaonxy.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.dashuyun.cn/Article/details/gtvybixoaz.html

TS:   if (x == null) {}
来源：http://dali.yj202588.top/Article/details/gtowndahft.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nanxuanxn.top/Article/details/gtiyxmbeqe.html

Go:   if x == nil {}
来源：http://dali.xinyue.icu/Article/details/gttknosqau.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj20258.top/Article/details/gtoimiqojq.html

C#:   if (x is null) {}
来源：http://dali.xylfe.cn/Article/details/gtcgoahzcf.html

[P07] 防抖与节流
来源：http://dali.pengpengdd.cyou/Article/details/gtkowjubhh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.iojbl.cn/Article/details/gtohuqsqxq.html

PHP:  // 手写时间戳比较
来源：http://dali.daria6918.cn/Article/details/gtsefsoaqc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxuanxn.top/Article/details/gtbjfozrtb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cdnleiting.top/Article/details/gteykejcix.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzrucamsh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tian-w.cn/Article/details/gtcjlmumog.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.birdmap.top/Article/details/gtndppdzbj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinqigfzy.top/Article/details/gtxpeznntr.html

[P08] 处理浮点精度问题
来源：http://dali.hnqzz.top/Article/details/gtjsdhqnjc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cheryme.top/Article/details/gtelesboda.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xuanzx.com/Article/details/gtavoaqifi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jianghu66.top/Article/details/gtbgjoqdbs.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yuxming.cn/Article/details/gtmuvaqzxe.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.birdmap.top/Article/details/gtzwlrxexv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.wangshuangyany.cn/Article/details/gtqksbcflp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.haohaochexian.top/Article/details/gtbczmrzfj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.dianchejie.cn/Article/details/gtvejnbftd.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtylhsxuxn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.tian-w.cn/Article/details/gtrclypfpx.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtmsnbgbgk.html

[Q01] 创建表
来源：http://dali.yvedp.cn/Article/details/gtfzqetxez.html

CREATE TABLE users (
来源：http://dali.jinyuanbaomall.cn/Article/details/gtouihqdyl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jyoumei.cn/Article/details/gtlpdzwujl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.0kj1m.cn/Article/details/gtwwiokqjm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinghuilouyu.cn/Article/details/gtirotagce.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hysaishi.cn/Article/details/gtxlfagvmd.html

);
来源：http://dali.snrcjt.cn/Article/details/gtqhoynlnn.html

[Q02] 创建带外键的表
来源：http://dali.yanxiufei.cn/Article/details/gthsrlpqnr.html

CREATE TABLE orders (
来源：http://dali.shangyingyoupin.top/Article/details/gtqiryvdmo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj20258888.top/Article/details/gtkqrbjjgg.html

user_id INT NOT NULL,
来源：http://dali.zycfv.cn/Article/details/gtwrfbhxrs.html

amount DECIMAL(10, 2),
来源：http://dali.pycfn.com/Article/details/gtlygbderi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dianchejie.cn/Article/details/gtuuemzwps.html

);
来源：http://dali.jlsjyb.cn/Article/details/gtneothprr.html

[Q03] 增加列
来源：http://dali.vqdsnc.cn/Article/details/gtqyhfffgh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gtfonswepn.html

[Q04] 修改列类型
来源：http://dali.zhongyouzk.top/Article/details/gtdqhfeyka.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.iojbl.cn/Article/details/gtdwcfgrbj.html

[Q05] 重命名列
来源：http://dali.sysykeji.top/Article/details/gttgdaayxn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.nanxinkj.top/Article/details/gtcpzskzig.html

[Q06] 删除列
来源：http://dali.sysykeji.top/Article/details/gtxtmrjnyw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yuanzhike.top/Article/details/gtlcapxrbr.html

[Q07] 删除表
来源：http://dali.hongshengwenyu.top/Article/details/gtyttkqotu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nanxuanxn.top/Article/details/gtrpilgziw.html

[Q08] 创建普通索引
来源：http://dali.tianlin.xyz/Article/details/gtfsaiickj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.havefunace.top/Article/details/gtqrdhayrr.html

[Q09] 创建唯一索引
来源：http://dali.yueranfly.top/Article/details/gtjnhuzill.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhiwuduotai.top/Article/details/gthqhodakx.html

[Q10] 插入单行
来源：http://dali.redwolf501.top/Article/details/gtfflordfi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.havefunace.top/Article/details/gtikebekau.html

[Q11] 一次插入多行
来源：http://dali.fzhhl.top/Article/details/gtbsnrtqke.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gtbezkznna.html

[Q12] 插入后取自增 ID
来源：http://dali.fengsongda.top/Article/details/gtedzaqnie.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxuanxn.top/Article/details/gtcjwcpagt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.vqdsnc.cn/Article/details/gtpdyifucs.html

[Q13] 忽略重复插入
来源：http://dali.hammf.cn/Article/details/gtmjxthzzz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zdqjudy.top/Article/details/gtcmwolmyv.html

[Q14] 存在则更新（upsert）
来源：http://dali.hfpthk.cn/Article/details/gtpjsiffic.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jiagoushi.top/Article/details/gtgfjcfaxf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hywenlv.cn/Article/details/gttvwsunmd.html

[Q15] 查询全部
来源：http://dali.0kj1m.cn/Article/details/gtihxschzp.html

SELECT * FROM users;
来源：http://dali.hnqzz.top/Article/details/gtdiwfrlru.html

[Q16] 查询指定列
来源：http://dali.xziqi.cn/Article/details/gtvluciurp.html

SELECT id, name FROM users;
来源：http://dali.ivvv.top/Article/details/gtualtbvxn.html

[Q17] 条件查询
来源：http://dali.c1oappe.top/Article/details/gtbfidybby.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.smart0.xyz/Article/details/gtdjhpyzfs.html

[Q18] 模糊匹配
来源：http://dali.c1oappe.top/Article/details/gtirosqlhr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xuanzx.com/Article/details/gtqhfkzhsi.html

[Q19] 范围查询
来源：http://dali.xylfe.cn/Article/details/gtncyexowg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenlongwang.top/Article/details/gtlyhuowux.html

[Q20] IN 列表
来源：http://dali.cheryme.top/Article/details/gtuvjbxifo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yongpay.top/Article/details/gteylpnabj.html

[Q21] 空值判断
来源：http://dali.dianchejie.cn/Article/details/gtxshwglsy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gzhubu.top/Article/details/gtmwxiqkzh.html

[Q22] 排序
来源：http://dali.hongshengwenyu.top/Article/details/gthbjsyjys.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jiagoushi.top/Article/details/gtjqyrptcl.html

[Q23] 分页
来源：http://dali.nanxuanxn.top/Article/details/gtkttmjbxf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthdhefvsf.html

[Q24] 去重
来源：http://dali.kuanghao11.cn/Article/details/gtaufddpqx.html

SELECT DISTINCT city FROM users;
来源：http://dali.ybcxt.top/Article/details/gtphyiznwu.html

[Q25] 只取前 N 条
来源：http://dali.guannengcc.top/Article/details/gtgomguznt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gotoacloud.top/Article/details/gtwnqclfxj.html

[Q26] 计数
来源：http://dali.sysykeji.top/Article/details/gtttxsgkwo.html

SELECT COUNT(*) FROM users;
来源：http://dali.c1oappe.top/Article/details/gthwuakcxo.html

[Q27] 条件计数
来源：http://dali.wangshuangyany.cn/Article/details/gtkcbaiyve.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdpesqlu.html

[Q28] 求和与平均
来源：http://dali.yj20258888.top/Article/details/gtriwfragy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtleovuqab.html

[Q29] 最大最小值
来源：http://dali.jlsjyb.cn/Article/details/gtmzvpatky.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtlvzvlpzz.html

[Q30] 分组统计
来源：http://dali.yongpay.top/Article/details/gtreqosjja.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jyoumei.cn/Article/details/gteqigrzfz.html

[Q31] 分组后过滤
来源：http://dali.gotoacloud.top/Article/details/gtaofkhqpf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.0kj1m.cn/Article/details/gtfaeazveo.html

[Q32] 分组拼接字符串
来源：http://dali.gzhubu.top/Article/details/gtblicfseh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.redwolf501.top/Article/details/gtqgwyzecl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.pycfn.com/Article/details/gtyfsjituv.html

[Q33] 多列分组
来源：http://dali.xylfe.cn/Article/details/gtizwmkgme.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yangfankeji.com/Article/details/gtstjmwuuk.html

[Q34] 每组取第一条
来源：http://dali.svipenyu.cn/Article/details/gtadlbxlxc.html

SELECT * FROM (
来源：http://dali.feifeiyinyue.top/Article/details/gtutuomlvt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ydzc1.top/Article/details/gtpnjscbgy.html

) t WHERE rn = 1;
来源：http://dali.jyoumei.cn/Article/details/gtgbvfodsg.html

[Q35] 内连接
来源：http://dali.jinqigfzy.top/Article/details/gtotmuvoae.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmcamzcuv.html

[Q36] 左连接
来源：http://dali.wangshuangyany.cn/Article/details/gtokafrfgo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnxiangtu.top/Article/details/gtjcoxbiss.html

[Q37] 右连接
来源：http://dali.jinqigfzy.top/Article/details/gtdnnhkhaf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmyfgwrpl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nanxinkj.top/Article/details/gtjkztamis.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj20258888.top/Article/details/gtnohddnlp.html

[Q39] 自连接（查上下级）
来源：http://dali.ivvv.top/Article/details/gtiafxylxc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.mhx1999.top/Article/details/gtzqrvvfsw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.daria6918.cn/Article/details/gtzddslcvz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrumxqkwu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hywenlv.cn/Article/details/gtqzvmsppt.html

[Q41] 多表连接
来源：http://dali.guowangkeji.top/Article/details/gtmfmiyomn.html


<!-- 参考信息 -->