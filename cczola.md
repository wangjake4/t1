代发 wailian999

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gttzwwlrkz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.quarkkingdee.top/Article/details/gttcmqfkbz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daria6918.cn/Article/details/gtuypwzkxx.html

Ruby: a.gcd(b)
来源：http://dali.yj20258888.top/Article/details/gtuofubgke.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.316326.xyz/Article/details/gtaumaaokh.html

[N06] 判断回文字符串
来源：http://dali.yanxiufei.cn/Article/details/gtbiyiigma.html

Py:   s == s[::-1]
来源：http://dali.xuetiantiany.cn/Article/details/gtsklbeive.html

PHP:  $s === strrev($s);
来源：http://dali.gogol.net.cn/Article/details/gtiviazlqu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtnxqxmttm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtnlcrbsku.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hnqzz.top/Article/details/gtbrwaerge.html

Go:   // 双指针从两端比较
来源：http://dali.shzxlz.cn/Article/details/gtvtdwbkjl.html

Ruby: s == s.reverse
来源：http://dali.yvedp.cn/Article/details/gtwpnwslrl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj20258888.top/Article/details/gtkvqeftqj.html

[N07] 两数之和（返回下标）
来源：http://dali.quarkkingdee.top/Article/details/gtsspbkyhg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.mhx1999.top/Article/details/gttulvwyib.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.dashuyun.cn/Article/details/gtprbotkxf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.aibaodan.cn/Article/details/gtldjycqyb.html

TS:   // 手写 Map<string, number>
来源：http://dali.ybcxt.top/Article/details/gtkkweqkpx.html

Java: // 手写 HashMap
来源：http://dali.316326.xyz/Article/details/gtnzrvlakp.html

Go:   // 手写 map[int]int
来源：http://dali.sxryk.cn/Article/details/gtwykojnmz.html

Ruby: // 手写 Hash
来源：http://dali.ivvv.top/Article/details/gtiylobsem.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jyoumei.cn/Article/details/gtuchnkbma.html

[N08] 生成全排列
来源：http://dali.jqgufenzy.top/Article/details/gtlbiltpoo.html

Py:   itertools.permutations(arr)
来源：http://dali.tian-w.cn/Article/details/gtzcezxfen.html

PHP:  // 手写递归交换
来源：http://dali.yongpay.top/Article/details/gtzhlvreao.html

JS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtwsmwnzxq.html

TS:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtfmxhangq.html

Java: // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtvnbrzgap.html

Go:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gthlylkjoh.html

Ruby: arr.permutation.to_a
来源：http://dali.cqqwz.cn/Article/details/gtckaeuock.html

C#:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtpfnwqhyg.html

[N09] 栈与队列
来源：http://dali.zhengqikj.top/Article/details/gtvllrucjh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sxryk.cn/Article/details/gtmusmnfgg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gtfukajmdh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ydzc1.top/Article/details/gthscxnvqc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jianghu66.top/Article/details/gtmqjnyqiz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shzxlz.cn/Article/details/gtqtqvlanw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sweek.top/Article/details/gtfrmpxnlk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.fengsongda.top/Article/details/gtlcigxnhq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.fengsongda.top/Article/details/gtcayjncjm.html

[N10] 链表节点定义
来源：http://dali.jqgfzy.top/Article/details/gtskumnlnw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yanxiufei.cn/Article/details/gthwqgkkxr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nanxuanxn.top/Article/details/gtypownobh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.iojbl.cn/Article/details/gteuajfuzd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yvedp.cn/Article/details/gtafszdaqw.html

Java: class Node { int v; Node next; }
来源：http://dali.yonumen.top/Article/details/gtnfdrdbye.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hammf.cn/Article/details/gtxbxhtjcg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhengqikj.top/Article/details/gtktnbkbnt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jiagoushi.top/Article/details/gtfjarnfre.html

[N11] 二叉树中序遍历
来源：http://dali.zhongyouzk.top/Article/details/gtfhzvmxqv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.guannengcc.top/Article/details/gtvjzrhyuu.html

PHP:  // 手写递归函数
来源：http://dali.xziqi.cn/Article/details/gtvtusjknl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.kuanghao11.cn/Article/details/gtubuqyxyr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shzxlz.cn/Article/details/gtnsorivyy.html

Java: // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gtbmybcxbw.html

Go:   // 手写递归
来源：http://dali.xuanzx.com/Article/details/gtgzkximbq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sweek.top/Article/details/gtqqefcnzm.html

C#:   // 手写递归
来源：http://dali.andypj.xyz/Article/details/gtwfgypdcw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yanxiufei.cn/Article/details/gtvgfpgmam.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtgogwng.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.tianlin.xyz/Article/details/gtvjeafvzp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hywenlv.cn/Article/details/gtcowoefax.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenlongwang.top/Article/details/gtmqixeqlu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hfpthk.cn/Article/details/gtjoorhjfo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hnqzz.top/Article/details/gtvdxvjpzh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhengqikj.top/Article/details/gtuiczkhdt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hfpthk.cn/Article/details/gtzzdojkwe.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtjfmddbnu.html

O. 并发与异步
来源：http://dali.c1oappe.top/Article/details/gtvzfqjcfq.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtfeebptqx.html

[O01] 启动一个线程
来源：http://dali.gotoacloud.top/Article/details/gtbtdkizhh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.dianchejie.cn/Article/details/gtgmaicpob.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ydzc1.top/Article/details/gtdynwabzg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ehwqpu.com/Article/details/gtvtaxnrkj.html

TS:   // 同 JS
来源：http://dali.jinqigufen.top/Article/details/gtzrkhlysd.html

Java: new Thread(() -> f()).start()
来源：http://dali.9152youxi.cn/Article/details/gttcbznhfm.html

Go:   go f()
来源：http://dali.yueranfly.top/Article/details/gtebpgqnpr.html

Ruby: Thread.new { f }
来源：http://dali.wangshuangyany.cn/Article/details/gtumyyjlnh.html

C#:   Task.Run(() => F());
来源：http://dali.yongpay.top/Article/details/gtwapqjfcf.html

[O02] 使用线程池
来源：http://dali.dashuyun.cn/Article/details/gtqqagznlq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhengqikj.top/Article/details/gtacvlmwtg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sxryk.cn/Article/details/gtjondvjyf.html

JS:   // worker_threads 线程池
来源：http://dali.zhiwuduotai.top/Article/details/gtxqayrdiy.html

TS:   // worker_threads 线程池
来源：http://dali.xuetiantiany.cn/Article/details/gtfecqoxhi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj20258.top/Article/details/gtzmzpjykk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yangfankeji.com/Article/details/gtrmjfmoel.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.pengpengdd.cyou/Article/details/gtsskfiwdq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cashguo.top/Article/details/gtwwdfvbwy.html

[O03] 加锁保护共享数据
来源：http://dali.svipenyu.cn/Article/details/gtpndvkhug.html

Py:   with lock: shared += 1
来源：http://dali.xziqi.cn/Article/details/gtuvigzlvh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hywenlv.cn/Article/details/gtkkrxxxgx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hfpthk.cn/Article/details/gtvwpavaaz.html

TS:   // 同 JS
来源：http://dali.guannengcc.top/Article/details/gtrmoxueix.html

Java: synchronized (this) { shared++; }
来源：http://dali.ydzc1.top/Article/details/gteilrfxed.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xuetiantiany.cn/Article/details/gtwpmdnwrn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.smart0.xyz/Article/details/gtugedlujd.html

C#:   lock (gate) { shared++; }
来源：http://dali.tian-w.cn/Article/details/gtpstaapur.html

[O04] 定义异步函数并等待
来源：http://dali.cheryme.top/Article/details/gtwikzvdtd.html

Py:   async def f():⏎    await g()
来源：http://dali.ybcxt.top/Article/details/gtifreyeiu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xuetiantiany.cn/Article/details/gtrtujrkmk.html

JS:   async function f() { await g(); }
来源：http://dali.yuxming.cn/Article/details/gttsccdawe.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cdnleiting.top/Article/details/gtkfyrqttc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jqgufenzy.top/Article/details/gtvzakjtjx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.haohaochexian.top/Article/details/gtyiqpuaxc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yj20258888.top/Article/details/gtsqhtfyqs.html

C#:   async Task F() { await G(); }
来源：http://dali.nanxinkj.top/Article/details/gthcpiqomr.html

[O05] 并发执行并等待全部完成
来源：http://dali.mhx1999.top/Article/details/gttsduqvra.html

Py:   asyncio.gather(*tasks)
来源：http://dali.pycfn.com/Article/details/gthbrifsff.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.haohaochexian.top/Article/details/gtnpwewmus.html

JS:   await Promise.all(tasks)
来源：http://dali.nwbrower.top/Article/details/gtfnlreyow.html

TS:   await Promise.all(tasks)
来源：http://dali.xinyue.icu/Article/details/gtltdzzzeo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.andypj.xyz/Article/details/gtjstedukh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gogol.net.cn/Article/details/gtxdcinztv.html

Ruby: threads.map(&:join)
来源：http://dali.yvedp.cn/Article/details/gtqxyltpdf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenlongwang.top/Article/details/gthgxvbaya.html

[O06] 使用进程池
来源：http://dali.tian-w.cn/Article/details/gtdzouoeqn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.wangshuangyany.cn/Article/details/gtjdjhwiiz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.pycfn.com/Article/details/gtuskpxsis.html

JS:   // child_process / cluster 模块
来源：http://dali.jyoumei.cn/Article/details/gtsrioobyt.html

TS:   // child_process / cluster 模块
来源：http://dali.chenzaomai.com/Article/details/gtiwrsssqp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shanyushiyangtech.top/Article/details/gtqsiddbiy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xuanzx.com/Article/details/gthcscdyag.html

Ruby: // fork 块
来源：http://dali.shangyingyoupin.top/Article/details/gtbaodowhe.html

C#:   Parallel.For
来源：http://dali.yj20258.top/Article/details/gtdyjnchhx.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtawyhksuh.html

P. 常用工具函数
来源：http://dali.birdmap.top/Article/details/gtspuckgbn.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtecpkdfww.html

[P01] 生成 UUID
来源：http://dali.vqdsnc.cn/Article/details/gtwnqbtfwn.html

Py:   str(uuid.uuid4())
来源：http://dali.jlsjyb.cn/Article/details/gtrfeiuwmz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yvedp.cn/Article/details/gtdhshnmdj.html

JS:   crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gtnbdftmui.html

TS:   crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gtqrmsvmtr.html

Java: UUID.randomUUID().toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwtucfhbi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.dashuyun.cn/Article/details/gtllacsxna.html

Ruby: SecureRandom.uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvhbrswl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yueranfly.top/Article/details/gtvhrxrhfe.html

[P02] MD5 / SHA256 摘要
来源：http://dali.fzhhl.top/Article/details/gtlbczuvay.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nanxuanxn.top/Article/details/gtiggakukq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtufjriyps.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jiagoushi.top/Article/details/gtwdpeakww.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.pengpengdd.cyou/Article/details/gtbitbprqm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hammf.cn/Article/details/gtmdwwthtj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yanxiufei.cn/Article/details/gtbrysgbyg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yanxiufei.cn/Article/details/gtaxazklzd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.pengpengdd.cyou/Article/details/gtqzdjxdzh.html

[P03] 生成短随机字符串
来源：http://dali.dashuyun.cn/Article/details/gtewagngsi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cqqwz.cn/Article/details/gtkbiyidam.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tian-w.cn/Article/details/gtqyrzzpls.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwxitkgo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxuanxn.top/Article/details/gtdmlxgikf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tian-w.cn/Article/details/gtilhfqrcf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nwbrower.top/Article/details/gtfwuuqwnv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jqgufenzy.top/Article/details/gtvyntsakl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sufxvd.cn/Article/details/gtzhzexymo.html

[P04] 求长度
来源：http://dali.sxryk.cn/Article/details/gtksuohenu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.daria6918.cn/Article/details/gtumixlhjz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gttfpfmdxo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.316326.xyz/Article/details/gtpdyoqpua.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nwbrower.top/Article/details/gtvarjdyck.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tanke756.top/Article/details/gtrmtovdis.html

Go:   len(arr);  len(m)
来源：http://dali.yuanzhike.top/Article/details/gtymdpnwxj.html

Ruby: x.length;  x.size
来源：http://dali.redwolf501.top/Article/details/gtcuiebsml.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xziqi.cn/Article/details/gtdcrvvkyr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.kuanghao11.cn/Article/details/gtfuymvzhu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.snrcjt.cn/Article/details/gtdhryqdna.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yj20258888.top/Article/details/gtdkeckbmv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xuetiantiany.cn/Article/details/gtryamazvk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sxryk.cn/Article/details/gtbuldjqtu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.feifeiyinyue.top/Article/details/gtdtzapznp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.smart0.xyz/Article/details/gtnobdzwbq.html

Ruby: a == b
来源：http://dali.cdnleiting.top/Article/details/gtongwdlrx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.wangdashe.top/Article/details/gtllsxmnxz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthzvknqdc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jqgufenzy.top/Article/details/gtgxbnhktp.html

PHP:  if (empty($x)) {}
来源：http://dali.ehwqpu.com/Article/details/gtkajvbzrw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hnxiangtu.top/Article/details/gtwdkbdjdw.html

TS:   if (x == null) {}
来源：http://dali.gogol.net.cn/Article/details/gtnjlipava.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jianghu66.top/Article/details/gtmypoliux.html

Go:   if x == nil {}
来源：http://dali.tian-w.cn/Article/details/gtlfevtbko.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shangyingyoupin.top/Article/details/gtrszigmtr.html

C#:   if (x is null) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtfuzsgunm.html

[P07] 防抖与节流
来源：http://dali.quarkkingdee.top/Article/details/gttnsvnxle.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yuxming.cn/Article/details/gtxrdmgllw.html

PHP:  // 手写时间戳比较
来源：http://dali.daxiang520.top/Article/details/gtqhvtxdzg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gtohukzmox.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtebsxoith.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gotoacloud.top/Article/details/gtzpnxxxtm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.pycfn.com/Article/details/gtponelzrz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yuanzhike.top/Article/details/gtvehmajkb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gzhubu.top/Article/details/gtantphbou.html

[P08] 处理浮点精度问题
来源：http://dali.cdnleiting.top/Article/details/gtdurnzuez.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jyoumei.cn/Article/details/gtpntodoyr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cheryme.top/Article/details/gtudyardtm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.nwbrower.top/Article/details/gtysoklmvj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.c1oappe.top/Article/details/gtnvajxloh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xuanzx.com/Article/details/gtrevkzqpp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuanzhike.top/Article/details/gtqexqcrwy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gotoacloud.top/Article/details/gtdwuaixij.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhongyouzk.top/Article/details/gtnfxlnhmo.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtdrrntblf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.snrcjt.cn/Article/details/gtgylolbvh.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gticsutdbq.html

[Q01] 创建表
来源：http://dali.9152youxi.cn/Article/details/gtpqmllort.html

CREATE TABLE users (
来源：http://dali.aibaodan.cn/Article/details/gtjpalcjkr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hammf.cn/Article/details/gtzgdogdor.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zdqjudy.top/Article/details/gtyjmnbbng.html

email VARCHAR(100) UNIQUE,
来源：http://dali.9152youxi.cn/Article/details/gtfnirfgbu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.vqdsnc.cn/Article/details/gtnobkkoqp.html

);
来源：http://dali.feifeiyinyue.top/Article/details/gtdrjykvzm.html

[Q02] 创建带外键的表
来源：http://dali.xuetiantiany.cn/Article/details/gtrjfqulwx.html

CREATE TABLE orders (
来源：http://dali.quarkkingdee.top/Article/details/gtjqvsnywz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tianlin.xyz/Article/details/gtdfzzxzrt.html

user_id INT NOT NULL,
来源：http://dali.meibo888.top/Article/details/gtispbtyix.html

amount DECIMAL(10, 2),
来源：http://dali.sweek.top/Article/details/gtglhelbrv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hongshengwenyu.top/Article/details/gtbskogmge.html

);
来源：http://dali.yj202588.top/Article/details/gtpryuxsgq.html

[Q03] 增加列
来源：http://dali.jinqigfzy.top/Article/details/gteezhcbqi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj202588.top/Article/details/gtrkrlygyo.html

[Q04] 修改列类型
来源：http://dali.ydzc1.top/Article/details/gtedlzixsp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.c1oappe.top/Article/details/gtnxzkvkbw.html

[Q05] 重命名列
来源：http://dali.yuxming.cn/Article/details/gtrhtasruw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.pycfn.com/Article/details/gtzjqzapje.html

[Q06] 删除列
来源：http://dali.ehwqpu.com/Article/details/gtmopmooqd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zdqjudy.top/Article/details/gtisoxhqbr.html

[Q07] 删除表
来源：http://dali.hnqzz.top/Article/details/gtkibfpsva.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenzaomai.com/Article/details/gttvzwnnub.html

[Q08] 创建普通索引
来源：http://dali.iojbl.cn/Article/details/gtypyhmuag.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xziqi.cn/Article/details/gtxehavfza.html

[Q09] 创建唯一索引
来源：http://dali.jiagoushi.top/Article/details/gthxbbskjl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.daxiang520.top/Article/details/gtmqozavlw.html

[Q10] 插入单行
来源：http://dali.guowangkeji.top/Article/details/gtwavswhxj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ydzc1.top/Article/details/gtgoqgxdmu.html

[Q11] 一次插入多行
来源：http://dali.yuxming.cn/Article/details/gtxpvdbioa.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gotoacloud.top/Article/details/gtrsfkhnwo.html

[Q12] 插入后取自增 ID
来源：http://dali.yj202588.top/Article/details/gtycefctql.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ivvv.top/Article/details/gtyjcafelb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hammf.cn/Article/details/gtyrmgkfje.html

[Q13] 忽略重复插入
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpcyjshtl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktmxlgwq.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenjidiqi.icu/Article/details/gtiqrkwitw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhengqikj.top/Article/details/gtdmxvszuk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hywenlv.cn/Article/details/gtpgvdeikc.html

[Q15] 查询全部
来源：http://dali.nanxinkj.top/Article/details/gthsmriszc.html

SELECT * FROM users;
来源：http://dali.zycfv.cn/Article/details/gtnutngiql.html

[Q16] 查询指定列
来源：http://dali.cashguo.top/Article/details/gtbtprlezu.html

SELECT id, name FROM users;
来源：http://dali.yvedp.cn/Article/details/gtxitrqeew.html

[Q17] 条件查询
来源：http://dali.ehwqpu.com/Article/details/gtsilsfwrh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.dianchejie.cn/Article/details/gtpbaokfmn.html

[Q18] 模糊匹配
来源：http://dali.cheryme.top/Article/details/gtxgalvnqh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbxvjdmh.html

[Q19] 范围查询
来源：http://dali.nwbrower.top/Article/details/gtctbktjjh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.havefunace.top/Article/details/gtcrroyomn.html

[Q20] IN 列表
来源：http://dali.snrcjt.cn/Article/details/gtqmqpitrk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yongpay.top/Article/details/gtqiwvwsjg.html

[Q21] 空值判断
来源：http://dali.jqgufenzy.top/Article/details/gtgyczkjnf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinghuilouyu.cn/Article/details/gttanzwkcu.html

[Q22] 排序
来源：http://dali.zhengqikj.top/Article/details/gtqheazdjl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.dashuyun.cn/Article/details/gtzyvjtzay.html

[Q23] 分页
来源：http://dali.ydzc1.top/Article/details/gticdhlgur.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hammf.cn/Article/details/gtuaosotrh.html

[Q24] 去重
来源：http://dali.jqgfzy.top/Article/details/gtbvbxywvi.html

SELECT DISTINCT city FROM users;
来源：http://dali.zycfv.cn/Article/details/gtnnjikyrh.html

[Q25] 只取前 N 条
来源：http://dali.fzhhl.top/Article/details/gtkhdqqwyv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenlongwang.top/Article/details/gtbfptwlwf.html

[Q26] 计数
来源：http://dali.dashuyun.cn/Article/details/gtvmhyyhws.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtithvriyw.html

[Q27] 条件计数
来源：http://dali.hongshengwenyu.top/Article/details/gtnmjyxopc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hnqzz.top/Article/details/gtrpbzfije.html

[Q28] 求和与平均
来源：http://dali.chenjidiqi.icu/Article/details/gtqdghwllw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtbtgqtyai.html

[Q29] 最大最小值
来源：http://dali.mhx1999.top/Article/details/gtweluloar.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtwqeawadv.html

[Q30] 分组统计
来源：http://dali.guannengcc.top/Article/details/gtbnrknrvg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjcnlpxjj.html

[Q31] 分组后过滤
来源：http://dali.cqqwz.cn/Article/details/gtmqjmmate.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.vqdsnc.cn/Article/details/gtdarmeezy.html

[Q32] 分组拼接字符串
来源：http://dali.snrcjt.cn/Article/details/gtxqxfvdys.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gtipyaupxx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.feifeiyinyue.top/Article/details/gtjvgvburx.html

[Q33] 多列分组
来源：http://dali.mhx1999.top/Article/details/gtkdvhahij.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenzaomai.com/Article/details/gtpwvvplni.html

[Q34] 每组取第一条
来源：http://dali.hysaishi.cn/Article/details/gtrjdyiorf.html

SELECT * FROM (
来源：http://dali.kuanghao11.cn/Article/details/gtsbafsmyw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.svipenyu.cn/Article/details/gtrudocgxk.html

) t WHERE rn = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtpotrbjwy.html

[Q35] 内连接
来源：http://dali.snrcjt.cn/Article/details/gtrvydcezq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sxryk.cn/Article/details/gtabwvptwp.html

[Q36] 左连接
来源：http://dali.sweek.top/Article/details/gthhzpmcuv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shzxlz.cn/Article/details/gtcqxicpre.html

[Q37] 右连接
来源：http://dali.jianghu66.top/Article/details/gtelblswxr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhoulong.xyz/Article/details/gtpbxyvhxd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.bjfxy.top/Article/details/gtwckirzoi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.meibo888.top/Article/details/gtvzvzhtsl.html

[Q39] 自连接（查上下级）
来源：http://dali.cheryme.top/Article/details/gthctseotd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.wangshuangyany.cn/Article/details/gtjvxwntwo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.havefunace.top/Article/details/gtvhftncym.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yj20258888.top/Article/details/gtyqogluvc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.mhx1999.top/Article/details/gtmmfdihoe.html

[Q41] 多表连接
来源：http://dali.gotoacloud.top/Article/details/gtpqkruerg.html


<!-- 参考信息 -->