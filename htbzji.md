代发 wailian999

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tianlin.xyz/Article/details/gtwvbfhzyj.html

[N06] 判断回文字符串
来源：http://dali.zycfv.cn/Article/details/gttraakcfp.html

Py:   s == s[::-1]
来源：http://dali.hfpthk.cn/Article/details/gtmbvearok.html

PHP:  $s === strrev($s);
来源：http://dali.zycfv.cn/Article/details/gtmqkihnnc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gtvvguopcg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gtmkpreywo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.c1oappe.top/Article/details/gtaahckpbr.html

Go:   // 双指针从两端比较
来源：http://dali.daria6918.cn/Article/details/gtzbglygxg.html

Ruby: s == s.reverse
来源：http://dali.nanxinkj.top/Article/details/gtzgwqyffl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sysykeji.top/Article/details/gtmgjfrfmy.html

[N07] 两数之和（返回下标）
来源：http://dali.zhengqikj.top/Article/details/gtjelmakbw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hammf.cn/Article/details/gtrjxydwtf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj202588.top/Article/details/gtgcbzqbcb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.redwolf501.top/Article/details/gtrbpnjfqr.html

TS:   // 手写 Map<string, number>
来源：http://dali.mhx1999.top/Article/details/gtdocscmcb.html

Java: // 手写 HashMap
来源：http://dali.pycfn.com/Article/details/gtqghqsboh.html

Go:   // 手写 map[int]int
来源：http://dali.zhixingplan.top/Article/details/gtaopqqvfd.html

Ruby: // 手写 Hash
来源：http://dali.ehwqpu.com/Article/details/gtxxlxaebe.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.vqdsnc.cn/Article/details/gtmkkezlmv.html

[N08] 生成全排列
来源：http://dali.daria6918.cn/Article/details/gtxpfkmyen.html

Py:   itertools.permutations(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtwcsgjwdn.html

PHP:  // 手写递归交换
来源：http://dali.smart0.xyz/Article/details/gtulvqwwuq.html

JS:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtkwavljuv.html

TS:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtnsmpmzvm.html

Java: // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtthgvraop.html

Go:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtlpsocwzd.html

Ruby: arr.permutation.to_a
来源：http://dali.sxryk.cn/Article/details/gtqjgdrhle.html

C#:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtazjygnvw.html

[N09] 栈与队列
来源：http://dali.yangfankeji.com/Article/details/gtyjeldtdb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.aibaodan.cn/Article/details/gtdxufplax.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gtnunmikqv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtuxslxbzw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hongshengwenyu.top/Article/details/gtqewfjdop.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shuidangran.top/Article/details/gtyfmzgqwk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sysykeji.top/Article/details/gtrrzlwenx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gtybovbjbt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.andypj.xyz/Article/details/gtqbhfyyfk.html

[N10] 链表节点定义
来源：http://dali.feifeiyinyue.top/Article/details/gtyxqeojgt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jqgfzy.top/Article/details/gtrntxjwoz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gaohongyu789.top/Article/details/gtibcgqtaj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yongpay.top/Article/details/gthassllyj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tianlin.xyz/Article/details/gtfnakuwit.html

Java: class Node { int v; Node next; }
来源：http://dali.sufxvd.cn/Article/details/gtjeulvujd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenlongwang.top/Article/details/gtpkdbvbpl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gtfaqrjjae.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhongyouzk.top/Article/details/gtkqcxrfxk.html

[N11] 二叉树中序遍历
来源：http://dali.yanxiufei.cn/Article/details/gtappugqny.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xylfe.cn/Article/details/gtqbduzkuu.html

PHP:  // 手写递归函数
来源：http://dali.guannengcc.top/Article/details/gtpmdxglqw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jiagoushi.top/Article/details/gthnzfkdvd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pycfn.com/Article/details/gtmqrxbhbo.html

Java: // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gtpuekchwf.html

Go:   // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gtsgjtmmlr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.bjfxy.top/Article/details/gtnxohterl.html

C#:   // 手写递归
来源：http://dali.jlsjyb.cn/Article/details/gtyogebjmv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shzxlz.cn/Article/details/gtctdckbxq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.andypj.xyz/Article/details/gtbrzjwdmg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.316326.xyz/Article/details/gtspfrxgnx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.meibo888.top/Article/details/gtnhyxzblj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ybcxt.top/Article/details/gtwuipxnzx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.vqdsnc.cn/Article/details/gtnxujdgtt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.pengpengdd.cyou/Article/details/gtecxvolhk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.haohaochexian.top/Article/details/gtefblyoft.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.andypj.xyz/Article/details/gthwohwuvr.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtvmijifxn.html

O. 并发与异步
来源：http://dali.nwbrower.top/Article/details/gturydwkct.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtclwkzjaq.html

[O01] 启动一个线程
来源：http://dali.svipenyu.cn/Article/details/gtotnaxidv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenlongwang.top/Article/details/gtjzmmfqpn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gzhubu.top/Article/details/gtmsauhrmg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhengqikj.top/Article/details/gtxwvciohw.html

TS:   // 同 JS
来源：http://dali.zhoulong.xyz/Article/details/gthblqvmiq.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhixingplan.top/Article/details/gtupwvdwaj.html

Go:   go f()
来源：http://dali.zhiwuduotai.top/Article/details/gtubnfehsi.html

Ruby: Thread.new { f }
来源：http://dali.ydzc1.top/Article/details/gtkcezdkge.html

C#:   Task.Run(() => F());
来源：http://dali.chenzaomai.com/Article/details/gthkowouww.html

[O02] 使用线程池
来源：http://dali.yonumen.top/Article/details/gtpozlvdav.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.guannengcc.top/Article/details/gtadddbadq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jqgufenzy.top/Article/details/gtobyctswx.html

JS:   // worker_threads 线程池
来源：http://dali.hnxiangtu.top/Article/details/gtgnonhann.html

TS:   // worker_threads 线程池
来源：http://dali.guannengcc.top/Article/details/gtglfayihm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yongpay.top/Article/details/gtejfapxrh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shangyingyoupin.top/Article/details/gtpvkbvkli.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.dianchejie.cn/Article/details/gtqkopmqpp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cucudq.cn/Article/details/gtktqhdmre.html

[O03] 加锁保护共享数据
来源：http://dali.haohaochexian.top/Article/details/gtoeyvhanq.html

Py:   with lock: shared += 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtibuhummz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.daria6918.cn/Article/details/gteelndilt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yanxiufei.cn/Article/details/gtnosicssn.html

TS:   // 同 JS
来源：http://dali.tianlin.xyz/Article/details/gtjvwwbnvt.html

Java: synchronized (this) { shared++; }
来源：http://dali.fzhhl.top/Article/details/gtjkfbauvd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hywenlv.cn/Article/details/gtmaihrkea.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.daxiang520.top/Article/details/gtmvwmrkou.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhoulong.xyz/Article/details/gtmmhfipnm.html

[O04] 定义异步函数并等待
来源：http://dali.yuanzhike.top/Article/details/gtjjmjkerp.html

Py:   async def f():⏎    await g()
来源：http://dali.zhixingplan.top/Article/details/gtycbgfrrj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.guowangkeji.top/Article/details/gtwdyhxmkk.html

JS:   async function f() { await g(); }
来源：http://dali.fzhhl.top/Article/details/gtbldhlvfo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj20258.top/Article/details/gtsejjxdso.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.316326.xyz/Article/details/gtmbkkmeac.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cashguo.top/Article/details/gtqgbfrzdw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.dianchejie.cn/Article/details/gtzvxvjdla.html

C#:   async Task F() { await G(); }
来源：http://dali.hysaishi.cn/Article/details/gteliehpey.html

[O05] 并发执行并等待全部完成
来源：http://dali.pycfn.com/Article/details/gtujokwkws.html

Py:   asyncio.gather(*tasks)
来源：http://dali.svipenyu.cn/Article/details/gtvtzckrrl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.wangdashe.top/Article/details/gtklfdulur.html

JS:   await Promise.all(tasks)
来源：http://dali.havefunace.top/Article/details/gteztiqgsb.html

TS:   await Promise.all(tasks)
来源：http://dali.mhx1999.top/Article/details/gteroinqgw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yueranfly.top/Article/details/gttjuiqrkn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhongyouzk.top/Article/details/gtcyaaninh.html

Ruby: threads.map(&:join)
来源：http://dali.yvedp.cn/Article/details/gtboykekfw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zdqjudy.top/Article/details/gtrdinhlwl.html

[O06] 使用进程池
来源：http://dali.havefunace.top/Article/details/gtukxsdfbr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.guannengcc.top/Article/details/gtfozvylxx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ehwqpu.com/Article/details/gtpjwdllir.html

JS:   // child_process / cluster 模块
来源：http://dali.daxiang520.top/Article/details/gtusjapyrs.html

TS:   // child_process / cluster 模块
来源：http://dali.hongshengwenyu.top/Article/details/gtfaqhwyad.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shanyushiyangtech.top/Article/details/gthhddldop.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinqigufen.top/Article/details/gtfrogqqil.html

Ruby: // fork 块
来源：http://dali.jinqigufen.top/Article/details/gtrwsquvqz.html

C#:   Parallel.For
来源：http://dali.ivvv.top/Article/details/gtwdidtjms.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtvoiaaxag.html

P. 常用工具函数
来源：http://dali.yuanzhike.top/Article/details/gttwkfyfhs.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtoufncivf.html

[P01] 生成 UUID
来源：http://dali.ivvv.top/Article/details/gtqpskxeuk.html

Py:   str(uuid.uuid4())
来源：http://dali.quarkkingdee.top/Article/details/gtrevxaspl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinqigfzy.top/Article/details/gtquebakee.html

JS:   crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gtrhelpmzu.html

TS:   crypto.randomUUID()
来源：http://dali.haohaochexian.top/Article/details/gtkfzuhevz.html

Java: UUID.randomUUID().toString()
来源：http://dali.cucudq.cn/Article/details/gthyeviglx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tanke756.top/Article/details/gttmwddhtr.html

Ruby: SecureRandom.uuid
来源：http://dali.smart0.xyz/Article/details/gtgyuanlpj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hnqzz.top/Article/details/gtwvhvnvld.html

[P02] MD5 / SHA256 摘要
来源：http://dali.nanxuanxn.top/Article/details/gtwjrdkbvc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tianlin.xyz/Article/details/gtnnppcvrj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.smart0.xyz/Article/details/gtilwxfbdd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwfgwjgv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shuidangran.top/Article/details/gtlwqzvkrx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gtmjukexwd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gogol.net.cn/Article/details/gtnhfgaxtx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtjcrqiarx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hammf.cn/Article/details/gtqqzmjcnm.html

[P03] 生成短随机字符串
来源：http://dali.yangfankeji.com/Article/details/gtiolndtsh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.smart0.xyz/Article/details/gtcvfqvnse.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hfpthk.cn/Article/details/gtlgwmgqat.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gotoacloud.top/Article/details/gtwvmufsqm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hammf.cn/Article/details/gtucelrvyu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sufxvd.cn/Article/details/gtquowmmya.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.havefunace.top/Article/details/gtybxskmyt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tian-w.cn/Article/details/gtzuiegaub.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskmukhqf.html

[P04] 求长度
来源：http://dali.zycfv.cn/Article/details/gtsmucmqir.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cheryme.top/Article/details/gtxnjsdqsy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gtytxtkphm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhongyouzk.top/Article/details/gteuigkyoc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yangfankeji.com/Article/details/gtoscbxpsk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhixingplan.top/Article/details/gtminnttjv.html

Go:   len(arr);  len(m)
来源：http://dali.tianlin.xyz/Article/details/gtxxxphgjb.html

Ruby: x.length;  x.size
来源：http://dali.hfpthk.cn/Article/details/gtimaggvxl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hongshengwenyu.top/Article/details/gtrggvlgaj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nwbrower.top/Article/details/gtgssocvor.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jqgfzy.top/Article/details/gtwlxbxsfd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.daria6918.cn/Article/details/gtxaxkzgfe.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xuanzx.com/Article/details/gtcutrgomt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sxryk.cn/Article/details/gtbyvbfuku.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ppjwa.cn/Article/details/gtldkhenon.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gtollmfyec.html

Ruby: a == b
来源：http://dali.zhixingplan.top/Article/details/gtueskspkx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.haohaochexian.top/Article/details/gtfkeshhmy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gogol.net.cn/Article/details/gtdlqhicfl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gogol.net.cn/Article/details/gtnaztppmz.html

PHP:  if (empty($x)) {}
来源：http://dali.havefunace.top/Article/details/gtqkfuocvv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.haohaochexian.top/Article/details/gtyujsmznc.html

TS:   if (x == null) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtztjvdjnz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.fengsongda.top/Article/details/gtlyqmvubs.html

Go:   if x == nil {}
来源：http://dali.xuanzx.com/Article/details/gtncgervja.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tian-w.cn/Article/details/gtzisqhrjo.html

C#:   if (x is null) {}
来源：http://dali.c1oappe.top/Article/details/gtihfghfbb.html

[P07] 防抖与节流
来源：http://dali.daria6918.cn/Article/details/gtwmtjjzeb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yueranfly.top/Article/details/gthleuaycv.html

PHP:  // 手写时间戳比较
来源：http://dali.yj202588.top/Article/details/gtumgrlwhz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gtooemzkxf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gtkitlmcqs.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cashguo.top/Article/details/gtycjqexcm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhongyouzk.top/Article/details/gtlmechqpz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj202588.top/Article/details/gtwydzhwrj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhengqikj.top/Article/details/gtlduutrsq.html

[P08] 处理浮点精度问题
来源：http://dali.9152youxi.cn/Article/details/gtljuhixuu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gogol.net.cn/Article/details/gtqbsmdfkh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenlongwang.top/Article/details/gtfhmwmnjd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xinyue.icu/Article/details/gtpqlmabvu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sweek.top/Article/details/gthdwkvcye.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yonumen.top/Article/details/gtateowylv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sweek.top/Article/details/gtzpnxuzun.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.wangshuangyany.cn/Article/details/gtfpdejmep.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgnefgmpf.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtveinywxm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.dashuyun.cn/Article/details/gtpzvilgyg.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtvawghkdb.html

[Q01] 创建表
来源：http://dali.chenlongwang.top/Article/details/gtoeufqzta.html

CREATE TABLE users (
来源：http://dali.yanxiufei.cn/Article/details/gtulvuxazc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gtytknjfsg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.daxiang520.top/Article/details/gtdgampyha.html

email VARCHAR(100) UNIQUE,
来源：http://dali.iojbl.cn/Article/details/gtmmjnzufx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.birdmap.top/Article/details/gteoarffaq.html

);
来源：http://dali.xuanzx.com/Article/details/gtsghjbhzc.html

[Q02] 创建带外键的表
来源：http://dali.pengpengdd.cyou/Article/details/gtiplbkleq.html

CREATE TABLE orders (
来源：http://dali.zhengqikj.top/Article/details/gtzrnthnsi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tian-w.cn/Article/details/gtupurfehd.html

user_id INT NOT NULL,
来源：http://dali.hysaishi.cn/Article/details/gtcxixgfds.html

amount DECIMAL(10, 2),
来源：http://dali.meibo888.top/Article/details/gtipdfowbi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ivvv.top/Article/details/gtjwcnhagz.html

);
来源：http://dali.hfpthk.cn/Article/details/gtrlkjtduj.html

[Q03] 增加列
来源：http://dali.kuanghao11.cn/Article/details/gtpabhgulp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbfbaayzy.html

[Q04] 修改列类型
来源：http://dali.cdnleiting.top/Article/details/gtqkmiqftm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gtpdqngngr.html

[Q05] 重命名列
来源：http://dali.yj20258888.top/Article/details/gtweygrzpy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.quarkkingdee.top/Article/details/gthiczhmqu.html

[Q06] 删除列
来源：http://dali.0kj1m.cn/Article/details/gtgsyqlyia.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.redwolf501.top/Article/details/gtlqoiplhv.html

[Q07] 删除表
来源：http://dali.yanxiufei.cn/Article/details/gtagsaddkt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jqgufenzy.top/Article/details/gtsutvgllc.html

[Q08] 创建普通索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqgcldry.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tanke756.top/Article/details/gtrtqxcteh.html

[Q09] 创建唯一索引
来源：http://dali.jqgfzy.top/Article/details/gtbafdpdik.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yanxiufei.cn/Article/details/gtprvsupiw.html

[Q10] 插入单行
来源：http://dali.guowangkeji.top/Article/details/gtbhhivmvv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.guowangkeji.top/Article/details/gtrndncqfa.html

[Q11] 一次插入多行
来源：http://dali.yj20258.top/Article/details/gteumqfioh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ybcxt.top/Article/details/gtyqlfydse.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gtpczssgtk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hysaishi.cn/Article/details/gttpgairgn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ppjwa.cn/Article/details/gtonunupwt.html

[Q13] 忽略重复插入
来源：http://dali.nanxuanxn.top/Article/details/gtceyupwhm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gtttyydcgt.html

[Q14] 存在则更新（upsert）
来源：http://dali.yonumen.top/Article/details/gtefmigmdx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhengqikj.top/Article/details/gtxqlmelmr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tian-w.cn/Article/details/gtaycbnwko.html

[Q15] 查询全部
来源：http://dali.haohaochexian.top/Article/details/gtkzqwicvn.html

SELECT * FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtrzspnkjf.html

[Q16] 查询指定列
来源：http://dali.feifeiyinyue.top/Article/details/gtwmjxmcnc.html

SELECT id, name FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtnhtjiyoo.html

[Q17] 条件查询
来源：http://dali.jianghu66.top/Article/details/gtpyzezxae.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtwxiynexd.html

[Q18] 模糊匹配
来源：http://dali.zhengqikj.top/Article/details/gtqesghdgw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yvedp.cn/Article/details/gtryqjpefx.html

[Q19] 范围查询
来源：http://dali.zycfv.cn/Article/details/gtlkuzbggx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nanxuanxn.top/Article/details/gtzznojsun.html

[Q20] IN 列表
来源：http://dali.zhixingplan.top/Article/details/gtslkkuexs.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.quarkkingdee.top/Article/details/gtvuulzlyh.html

[Q21] 空值判断
来源：http://dali.ppjwa.cn/Article/details/gtrdoyvvrr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj202588.top/Article/details/gtmnorrwwq.html

[Q22] 排序
来源：http://dali.hnqzz.top/Article/details/gtxuadikua.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqxhyyhmn.html

[Q23] 分页
来源：http://dali.gzhubu.top/Article/details/gtytzpfbwm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.guannengcc.top/Article/details/gtdqtmamtb.html

[Q24] 去重
来源：http://dali.zhongyouzk.top/Article/details/gtqcamddiw.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtnayxqnzu.html

[Q25] 只取前 N 条
来源：http://dali.jiagoushi.top/Article/details/gtxljafiux.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yuxming.cn/Article/details/gtuwktwhrb.html

[Q26] 计数
来源：http://dali.hnxiangtu.top/Article/details/gtjqbcwlzi.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtdgaklrqf.html

[Q27] 条件计数
来源：http://dali.redwolf501.top/Article/details/gtxbxoyfes.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gzhubu.top/Article/details/gtzipsaqiu.html

[Q28] 求和与平均
来源：http://dali.vqdsnc.cn/Article/details/gtqneyqpwr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.meibo888.top/Article/details/gtuwcvuflv.html

[Q29] 最大最小值
来源：http://dali.jqgfzy.top/Article/details/gtmwpbzhaj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtsqzgwkwm.html

[Q30] 分组统计
来源：http://dali.gogol.net.cn/Article/details/gtbuhniibw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gtbvflezbd.html

[Q31] 分组后过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtuinlodfo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ydzc1.top/Article/details/gtrirxrnow.html

[Q32] 分组拼接字符串
来源：http://dali.c1oappe.top/Article/details/gtuwytdzok.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gtcqezqnzi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tanke756.top/Article/details/gtivpblbjx.html

[Q33] 多列分组
来源：http://dali.hnxiangtu.top/Article/details/gtbwyhzuwi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.quarkkingdee.top/Article/details/gtmmtvqqha.html

[Q34] 每组取第一条
来源：http://dali.cdnleiting.top/Article/details/gtjqjeoozo.html

SELECT * FROM (
来源：http://dali.cdnleiting.top/Article/details/gtsmnafjli.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.316326.xyz/Article/details/gtlhcgxkfj.html

) t WHERE rn = 1;
来源：http://dali.zycfv.cn/Article/details/gtalobokfd.html

[Q35] 内连接
来源：http://dali.kuanghao11.cn/Article/details/gtgfngcmge.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejcbvbdo.html

[Q36] 左连接
来源：http://dali.jinqigufen.top/Article/details/gtmfjqnxxy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxuanxn.top/Article/details/gtevanyzna.html

[Q37] 右连接
来源：http://dali.cdnleiting.top/Article/details/gtnukzkjrl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.nwbrower.top/Article/details/gteugyvzhn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gaohongyu789.top/Article/details/gtudlfzjoj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.daxiang520.top/Article/details/gtnfmpxflu.html

[Q39] 自连接（查上下级）
来源：http://dali.hfpthk.cn/Article/details/gtwyfeydad.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpodjaki.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yj20258888.top/Article/details/gtvjwfgswe.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yvedp.cn/Article/details/gtpsvijvpc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hongshengwenyu.top/Article/details/gtfhnekqol.html

[Q41] 多表连接
来源：http://dali.aizwys.cn/Article/details/gtlccqkhri.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gotoacloud.top/Article/details/gtxowjwjei.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gttdkpmdka.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.c1oappe.top/Article/details/gtgqpxrovr.html

[Q42] 连接条件附加过滤
来源：http://dali.jlsjyb.cn/Article/details/gthjvcahgl.html


<!-- 参考信息 -->