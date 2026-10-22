代发 wailian999

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yanxiufei.cn/Article/details/gt2wlduyssm.html

[N06] 判断回文字符串
来源：http://dali.cucudq.cn/Article/details/gt2hprbjlis.html

Py:   s == s[::-1]
来源：http://dali.nanxuanxn.top/Article/details/gt2olafibdc.html

PHP:  $s === strrev($s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2exslqzsc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gt2hdxpoisr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2vqlhrpws.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.meibo888.top/Article/details/gt2sffyhrni.html

Go:   // 双指针从两端比较
来源：http://dali.yanxiufei.cn/Article/details/gt2vpyzawvi.html

Ruby: s == s.reverse
来源：http://dali.9152youxi.cn/Article/details/gt2ztxgdhbu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hfpthk.cn/Article/details/gt2ionbqvbb.html

[N07] 两数之和（返回下标）
来源：http://dali.tanke756.top/Article/details/gt2pslfyhay.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zdqjudy.top/Article/details/gt2ejoxynyk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.dashuyun.cn/Article/details/gt2jclvroqi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hnxiangtu.top/Article/details/gt2qdmzeyzr.html

TS:   // 手写 Map<string, number>
来源：http://dali.xylfe.cn/Article/details/gt2rbafufkn.html

Java: // 手写 HashMap
来源：http://dali.andypj.xyz/Article/details/gt2oscjgkle.html

Go:   // 手写 map[int]int
来源：http://dali.sufxvd.cn/Article/details/gt2rdfnewnz.html

Ruby: // 手写 Hash
来源：http://dali.cashguo.top/Article/details/gt2qulhzfum.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.birdmap.top/Article/details/gt2nfhvzrou.html

[N08] 生成全排列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pxrlbohi.html

Py:   itertools.permutations(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xudkfxwk.html

PHP:  // 手写递归交换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nrnbxqxy.html

JS:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gt2rvzwbrqa.html

TS:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pyayhiip.html

Java: // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gt2iafwcxwg.html

Go:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gt2mczeorxl.html

Ruby: arr.permutation.to_a
来源：http://dali.quarkkingdee.top/Article/details/gt2lpcqdipo.html

C#:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gt2vgmrjgzz.html

[N09] 栈与队列
来源：http://dali.yueranfly.top/Article/details/gt2kcfnatjd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.guannengcc.top/Article/details/gt2rrvclfhm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jyoumei.cn/Article/details/gt2ywjcbeqo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.fzhhl.top/Article/details/gt2fpribyyw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shzxlz.cn/Article/details/gt2qjdbqdsu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jiagoushi.top/Article/details/gt2mfnqxonn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cqqwz.cn/Article/details/gt2pmifstze.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yvedp.cn/Article/details/gt2rtosnngy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jlsjyb.cn/Article/details/gt2zbyanrgi.html

[N10] 链表节点定义
来源：http://dali.andypj.xyz/Article/details/gt2tvdqgcsi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj20258888.top/Article/details/gt2tsfzjpmw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hfpthk.cn/Article/details/gt2gkdnueyb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.9152youxi.cn/Article/details/gt2quctrnlg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hysaishi.cn/Article/details/gt2xdaidhwa.html

Java: class Node { int v; Node next; }
来源：http://dali.c1oappe.top/Article/details/gt2ittghvdp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.feifeiyinyue.top/Article/details/gt2jxzjnyaj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yanxiufei.cn/Article/details/gt2mzimkivs.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yvedp.cn/Article/details/gt2oulprvhg.html

[N11] 二叉树中序遍历
来源：http://dali.guannengcc.top/Article/details/gt2nfpjmuln.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.wangshuangyany.cn/Article/details/gt2umzkjhxh.html

PHP:  // 手写递归函数
来源：http://dali.zhengqikj.top/Article/details/gt2sytcryfi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuetiantiany.cn/Article/details/gt2ltfczjfu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2orlxpmcf.html

Java: // 手写递归
来源：http://dali.cucudq.cn/Article/details/gt2zrmhnjbs.html

Go:   // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gt2pbtcycns.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tanke756.top/Article/details/gt2ojjeuokz.html

C#:   // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gt2nllosccr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sweek.top/Article/details/gt2pnyimncj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.fzhhl.top/Article/details/gt2jnmgvyxo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gogol.net.cn/Article/details/gt2utthwlky.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wxpqamww.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gaohongyu789.top/Article/details/gt2ppmirbeq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gogol.net.cn/Article/details/gt2apvfwumh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ivvv.top/Article/details/gt2fwsumvar.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhoulong.xyz/Article/details/gt2ctpkwwch.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fzhhl.top/Article/details/gt2srumcgus.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cxbgtcnr.html

O. 并发与异步
来源：http://dali.jqgufenzy.top/Article/details/gt2jfgmoxkb.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dovmgyxi.html

[O01] 启动一个线程
来源：http://dali.hnqzz.top/Article/details/gt2muoncipn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xylfe.cn/Article/details/gt2flwpdrfc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhiwuduotai.top/Article/details/gt2kcnlcmmi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.pengpengdd.cyou/Article/details/gt2fleskltg.html

TS:   // 同 JS
来源：http://dali.pengpengdd.cyou/Article/details/gt2kxanlcdh.html

Java: new Thread(() -> f()).start()
来源：http://dali.tanke756.top/Article/details/gt2bjskhhrk.html

Go:   go f()
来源：http://dali.tanke756.top/Article/details/gt2vaoejibx.html

Ruby: Thread.new { f }
来源：http://dali.tianlin.xyz/Article/details/gt2qtlzyonu.html

C#:   Task.Run(() => F());
来源：http://dali.cqqwz.cn/Article/details/gt2njaodakc.html

[O02] 使用线程池
来源：http://dali.sufxvd.cn/Article/details/gt2xpxmipll.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sxryk.cn/Article/details/gt2yzmtyvvo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.meibo888.top/Article/details/gt2ynbrahtm.html

JS:   // worker_threads 线程池
来源：http://dali.sweek.top/Article/details/gt2ptgxzpux.html

TS:   // worker_threads 线程池
来源：http://dali.nanxuanxn.top/Article/details/gt2bnkbslya.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yonumen.top/Article/details/gt2jdztitlo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xylfe.cn/Article/details/gt2mowuikld.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.pycfn.com/Article/details/gt2xvbwfxtu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yuanzhike.top/Article/details/gt2pentycub.html

[O03] 加锁保护共享数据
来源：http://dali.xinyue.icu/Article/details/gt2mppwtice.html

Py:   with lock: shared += 1
来源：http://dali.yvedp.cn/Article/details/gt2sbymcawh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.9152youxi.cn/Article/details/gt2dmjjnasn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.birdmap.top/Article/details/gt2ppvoscrs.html

TS:   // 同 JS
来源：http://dali.dianchejie.cn/Article/details/gt2duztieuq.html

Java: synchronized (this) { shared++; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2mynwswvy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hysaishi.cn/Article/details/gt2wsgghhdp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yvedp.cn/Article/details/gt2mjscdrem.html

C#:   lock (gate) { shared++; }
来源：http://dali.redwolf501.top/Article/details/gt2wtdomful.html

[O04] 定义异步函数并等待
来源：http://dali.gogol.net.cn/Article/details/gt2rselpfhj.html

Py:   async def f():⏎    await g()
来源：http://dali.guowangkeji.top/Article/details/gt2cmbwithy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jqgufenzy.top/Article/details/gt2uwxirktp.html

JS:   async function f() { await g(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2iaagfkuj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gt2ovbywwjz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.daxiang520.top/Article/details/gt2rwjcuecj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.iojbl.cn/Article/details/gt2vzwmbqii.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.daxiang520.top/Article/details/gt2zrtetcqg.html

C#:   async Task F() { await G(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jgwhbzpo.html

[O05] 并发执行并等待全部完成
来源：http://dali.gaohongyu789.top/Article/details/gt2xtojvddg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.haohaochexian.top/Article/details/gt2yvqgkbfx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.tian-w.cn/Article/details/gt2xtxmhfyt.html

JS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gt2jnrzijwn.html

TS:   await Promise.all(tasks)
来源：http://dali.tian-w.cn/Article/details/gt2sdzxoflh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.daxiang520.top/Article/details/gt2dtprwbic.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sufxvd.cn/Article/details/gt2dnjdfwoj.html

Ruby: threads.map(&:join)
来源：http://dali.svipenyu.cn/Article/details/gt2glbgnvly.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shzxlz.cn/Article/details/gt2euxcxlfu.html

[O06] 使用进程池
来源：http://dali.dianchejie.cn/Article/details/gt2ormfmhgy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2whgzkjxl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.snrcjt.cn/Article/details/gt2ycjefgjj.html

JS:   // child_process / cluster 模块
来源：http://dali.chenjidiqi.icu/Article/details/gt2wuaaxzof.html

TS:   // child_process / cluster 模块
来源：http://dali.tanke756.top/Article/details/gt2cbdhnwtx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nvvlhako.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bfwuhqvz.html

Ruby: // fork 块
来源：http://dali.cucudq.cn/Article/details/gt2rxhpmbvc.html

C#:   Parallel.For
来源：http://dali.guowangkeji.top/Article/details/gt2ijywqmkq.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2ywgzdioi.html

P. 常用工具函数
来源：http://dali.tanke756.top/Article/details/gt2ujwyqexb.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2jzczjzzz.html

[P01] 生成 UUID
来源：http://dali.sxryk.cn/Article/details/gt2khomamue.html

Py:   str(uuid.uuid4())
来源：http://dali.andypj.xyz/Article/details/gt2zpfomzsl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.bjfxy.top/Article/details/gt2mylpmquz.html

JS:   crypto.randomUUID()
来源：http://dali.ydzc1.top/Article/details/gt2vyegdabc.html

TS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cwqjohus.html

Java: UUID.randomUUID().toString()
来源：http://dali.dianchejie.cn/Article/details/gt2ntddpldt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tianlin.xyz/Article/details/gt2ytdkjbya.html

Ruby: SecureRandom.uuid
来源：http://dali.nanxuanxn.top/Article/details/gt2aafefdfs.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.svipenyu.cn/Article/details/gt2oqmzduuz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj20258888.top/Article/details/gt2txtiqaoi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yvedp.cn/Article/details/gt2jttqzfmz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yonumen.top/Article/details/gt2vaowydro.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.haohaochexian.top/Article/details/gt2nsduqslt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jqgfzy.top/Article/details/gt2zzfymnht.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pbelupmo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.meibo888.top/Article/details/gt2wznhhcvi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.andypj.xyz/Article/details/gt2ktlcxhga.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.wangshuangyany.cn/Article/details/gt2sewelvcm.html

[P03] 生成短随机字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2pzeaqazv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cqqwz.cn/Article/details/gt2zezutqxc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.wangshuangyany.cn/Article/details/gt2fnsrttet.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigufen.top/Article/details/gt2hgjaddiw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgfzy.top/Article/details/gt2czhyjrrb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.redwolf501.top/Article/details/gt2arobwksw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gaohongyu789.top/Article/details/gt2rrrrfaet.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.quarkkingdee.top/Article/details/gt2oygcqhdk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.pengpengdd.cyou/Article/details/gt2adzcggkq.html

[P04] 求长度
来源：http://dali.smart0.xyz/Article/details/gt2yyujwdpb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuxming.cn/Article/details/gt2qmkbzkgi.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gt2ghbqpppg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuanzx.com/Article/details/gt2yqvygnet.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sweek.top/Article/details/gt2idiewvhl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.mhx1999.top/Article/details/gt2oimrdeko.html

Go:   len(arr);  len(m)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nhmgpklm.html

Ruby: x.length;  x.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rlfuaysi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sysykeji.top/Article/details/gt2bbbuxfxw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.chenlongwang.top/Article/details/gt2vfzmleep.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tian-w.cn/Article/details/gt2nnnhgnos.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cashguo.top/Article/details/gt2uzdmnszv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jqgfzy.top/Article/details/gt2neecbiuw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lpgzayfm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.snrcjt.cn/Article/details/gt2zlnhhwla.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cdnleiting.top/Article/details/gt2lqbjjnql.html

Ruby: a == b
来源：http://dali.zhixingplan.top/Article/details/gt2nygtqwbx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhiwuduotai.top/Article/details/gt2rxathllv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.andypj.xyz/Article/details/gt2qoqmjsle.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.kuanghao11.cn/Article/details/gt2iylfdori.html

PHP:  if (empty($x)) {}
来源：http://dali.hnqzz.top/Article/details/gt2rysutxwz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhengqikj.top/Article/details/gt2kcysjjfx.html

TS:   if (x == null) {}
来源：http://dali.gzhubu.top/Article/details/gt2khcohgdc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2nccgqoea.html

Go:   if x == nil {}
来源：http://dali.0kj1m.cn/Article/details/gt2njcxwrzh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shzxlz.cn/Article/details/gt2krfzwqua.html

C#:   if (x is null) {}
来源：http://dali.nanxinkj.top/Article/details/gt2stmqyddy.html

[P07] 防抖与节流
来源：http://dali.shzxlz.cn/Article/details/gt2daiypait.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.havefunace.top/Article/details/gt2farkhgsd.html

PHP:  // 手写时间戳比较
来源：http://dali.0kj1m.cn/Article/details/gt2pwdklcsv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gt2kmrkobom.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gt2jumhfskh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.haohaochexian.top/Article/details/gt2xwflzsko.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tian-w.cn/Article/details/gt2smuzmwpz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zycfv.cn/Article/details/gt2piymnojn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xuetiantiany.cn/Article/details/gt2qodriuxn.html

[P08] 处理浮点精度问题
来源：http://dali.shzxlz.cn/Article/details/gt2ywubctfb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hywenlv.cn/Article/details/gt2avbiozxq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhongyouzk.top/Article/details/gt2ugriqwxy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hysaishi.cn/Article/details/gt2qfskhxjj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.9152youxi.cn/Article/details/gt2ajdmwsdv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbjyfyx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gotoacloud.top/Article/details/gt2qknwexcp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinqigufen.top/Article/details/gt2xpxckapa.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tanke756.top/Article/details/gt2gnckedvx.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2lbpoqwft.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.chenlongwang.top/Article/details/gt2hclpiyzz.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2vevwcwbn.html

[Q01] 创建表
来源：http://dali.redwolf501.top/Article/details/gt2fyjvgzzr.html

CREATE TABLE users (
来源：http://dali.zhengqikj.top/Article/details/gt2oihgeuxk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.kuanghao11.cn/Article/details/gt2nupbguyc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.snrcjt.cn/Article/details/gt2sdjmsqgx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.wangshuangyany.cn/Article/details/gt2ubooxtaf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2knaagksf.html

);
来源：http://dali.cqqwz.cn/Article/details/gt2bmjzgzzf.html

[Q02] 创建带外键的表
来源：http://dali.birdmap.top/Article/details/gt2alkocbzw.html

CREATE TABLE orders (
来源：http://dali.cdnleiting.top/Article/details/gt2phbzwikl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sysykeji.top/Article/details/gt2uylanaza.html

user_id INT NOT NULL,
来源：http://dali.jinqigfzy.top/Article/details/gt2ewgiwslg.html

amount DECIMAL(10, 2),
来源：http://dali.mhx1999.top/Article/details/gt2grahhubm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.iojbl.cn/Article/details/gt2hfvxerrx.html

);
来源：http://dali.xylfe.cn/Article/details/gt2dbelvout.html

[Q03] 增加列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qaxasprw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.iojbl.cn/Article/details/gt2bzdvbhkj.html

[Q04] 修改列类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2lqgfjzsr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ybcxt.top/Article/details/gt2szygqyzs.html

[Q05] 重命名列
来源：http://dali.gaohongyu789.top/Article/details/gt2wsbelatq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.tian-w.cn/Article/details/gt2kewpkjlo.html

[Q06] 删除列
来源：http://dali.aibaodan.cn/Article/details/gt2jccrtwbg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yonumen.top/Article/details/gt2pzeredqj.html

[Q07] 删除表
来源：http://dali.ybcxt.top/Article/details/gt2xqoviacz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.tianlin.xyz/Article/details/gt2vpgkgmdd.html

[Q08] 创建普通索引
来源：http://dali.hfpthk.cn/Article/details/gt2lsdfwkxh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.wangshuangyany.cn/Article/details/gt2zxpfjbrr.html

[Q09] 创建唯一索引
来源：http://dali.dashuyun.cn/Article/details/gt2pfvwgqov.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hywenlv.cn/Article/details/gt2znqdchqj.html

[Q10] 插入单行
来源：http://dali.aizwys.cn/Article/details/gt2zfpelrto.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gotoacloud.top/Article/details/gt2feivyett.html

[Q11] 一次插入多行
来源：http://dali.jianghu66.top/Article/details/gt2mezcolmo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tian-w.cn/Article/details/gt2yxteuitg.html

[Q12] 插入后取自增 ID
来源：http://dali.cheryme.top/Article/details/gt2mxolgnga.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tanke756.top/Article/details/gt2mfdgoneu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cwpivoke.html

[Q13] 忽略重复插入
来源：http://dali.yonumen.top/Article/details/gt2ditkswdy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gt2adtswgck.html

[Q14] 存在则更新（upsert）
来源：http://dali.fengsongda.top/Article/details/gt2zlklofzq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aiworfek.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxftoesb.html

[Q15] 查询全部
来源：http://dali.zhongyouzk.top/Article/details/gt2zeehdpan.html

SELECT * FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2xrkbzsqu.html

[Q16] 查询指定列
来源：http://dali.aibaodan.cn/Article/details/gt2xompcnjm.html

SELECT id, name FROM users;
来源：http://dali.havefunace.top/Article/details/gt2enfyuphx.html

[Q17] 条件查询
来源：http://dali.shuidangran.top/Article/details/gt2zmzqcdyx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhixingplan.top/Article/details/gt2vnwnugzk.html

[Q18] 模糊匹配
来源：http://dali.zycfv.cn/Article/details/gt2exxwvini.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ppjwa.cn/Article/details/gt2jugyhwht.html

[Q19] 范围查询
来源：http://dali.aizwys.cn/Article/details/gt2nrmbywhp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gaohongyu789.top/Article/details/gt2ntaxxele.html

[Q20] IN 列表
来源：http://dali.yangfankeji.com/Article/details/gt2wvzvjmfr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.fzhhl.top/Article/details/gt2ijkllyqt.html

[Q21] 空值判断
来源：http://dali.pycfn.com/Article/details/gt2vugydwxz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tanke756.top/Article/details/gt2ssocwrzk.html

[Q22] 排序
来源：http://dali.vqdsnc.cn/Article/details/gt2erizoemo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinqigfzy.top/Article/details/gt2eayridhm.html

[Q23] 分页
来源：http://dali.sysykeji.top/Article/details/gt2gzklwsbx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.meibo888.top/Article/details/gt2prmbckhu.html

[Q24] 去重
来源：http://dali.yanxiufei.cn/Article/details/gt2jjcoapqm.html

SELECT DISTINCT city FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2pzhubsxv.html

[Q25] 只取前 N 条
来源：http://dali.iojbl.cn/Article/details/gt2zbuytmbb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sufxvd.cn/Article/details/gt2glcnoofl.html

[Q26] 计数
来源：http://dali.xylfe.cn/Article/details/gt2pcjawcun.html

SELECT COUNT(*) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2plvlhdfj.html

[Q27] 条件计数
来源：http://dali.shzxlz.cn/Article/details/gt2bxqlrocb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2lqcovosf.html

[Q28] 求和与平均
来源：http://dali.ppjwa.cn/Article/details/gt2cnfizozj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gt2pzgxigvl.html

[Q29] 最大最小值
来源：http://dali.cucudq.cn/Article/details/gt2kkqfebwb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2persgsac.html

[Q30] 分组统计
来源：http://dali.tian-w.cn/Article/details/gt2hhncvjor.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jqgfzy.top/Article/details/gt2eticcfaq.html

[Q31] 分组后过滤
来源：http://dali.ivvv.top/Article/details/gt2cafgabgd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.316326.xyz/Article/details/gt2ueinlabd.html

[Q32] 分组拼接字符串
来源：http://dali.hnqzz.top/Article/details/gt2zkufhmsu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gt2xewnkmck.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ehwqpu.com/Article/details/gt2svirfglo.html

[Q33] 多列分组
来源：http://dali.smart0.xyz/Article/details/gt2piuwypht.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhengqikj.top/Article/details/gt2qjnddldd.html

[Q34] 每组取第一条
来源：http://dali.tianlin.xyz/Article/details/gt2lzktdtcs.html

SELECT * FROM (
来源：http://dali.cdnleiting.top/Article/details/gt2lxdronyl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tanke756.top/Article/details/gt2bzpkedkp.html

) t WHERE rn = 1;
来源：http://dali.ydzc1.top/Article/details/gt2iiveyceq.html

[Q35] 内连接
来源：http://dali.andypj.xyz/Article/details/gt2dlhvxpbr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenjidiqi.icu/Article/details/gt2dobwinsa.html

[Q36] 左连接
来源：http://dali.jiagoushi.top/Article/details/gt2btewykkr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gt2echwykfj.html

[Q37] 右连接
来源：http://dali.quarkkingdee.top/Article/details/gt2sgifrcle.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wzkvjgzg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zycfv.cn/Article/details/gt2ayjzaxby.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nwbrower.top/Article/details/gt2udstvcln.html

[Q39] 自连接（查上下级）
来源：http://dali.yonumen.top/Article/details/gt2cqvgzsea.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.guowangkeji.top/Article/details/gt2hmnxnvod.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhllundf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yvedp.cn/Article/details/gt2auejvugg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yueranfly.top/Article/details/gt2tugmmwii.html

[Q41] 多表连接
来源：http://dali.jinqigufen.top/Article/details/gt2jisjjydw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ivvv.top/Article/details/gt2spvrejtb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.redwolf501.top/Article/details/gt2ietyyrji.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.meibo888.top/Article/details/gt2scmmbiac.html

[Q42] 连接条件附加过滤
来源：http://dali.sysykeji.top/Article/details/gt2gbsgbkgm.html


<!-- 参考信息 -->