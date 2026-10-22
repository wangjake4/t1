代发 wailian999

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shuidangran.top/Article/details/gt2cfojofbn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.aibaodan.cn/Article/details/gt2oacbmmrn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rtxdkgwl.html

Ruby: a.gcd(b)
来源：http://dali.yanxiufei.cn/Article/details/gt2wfurfhhr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhengqikj.top/Article/details/gt2psqiornc.html

[N06] 判断回文字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wkspxlzs.html

Py:   s == s[::-1]
来源：http://dali.andypj.xyz/Article/details/gt2vntxlcfa.html

PHP:  $s === strrev($s);
来源：http://dali.hfpthk.cn/Article/details/gt2ukucwrkc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2sjhyoelq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aouhvcna.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.vqdsnc.cn/Article/details/gt2qzktcjsh.html

Go:   // 双指针从两端比较
来源：http://dali.ydzc1.top/Article/details/gt2oonjjcyy.html

Ruby: s == s.reverse
来源：http://dali.ivvv.top/Article/details/gt2kxhqwdtd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jianghu66.top/Article/details/gt2pfzuovqg.html

[N07] 两数之和（返回下标）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2naawzzfb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.fzhhl.top/Article/details/gt2beiyesut.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.iojbl.cn/Article/details/gt2rglovhwu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jqgfzy.top/Article/details/gt2kspzwsgi.html

TS:   // 手写 Map<string, number>
来源：http://dali.pengpengdd.cyou/Article/details/gt2irjujwim.html

Java: // 手写 HashMap
来源：http://dali.fzhhl.top/Article/details/gt2urhrlfly.html

Go:   // 手写 map[int]int
来源：http://dali.sufxvd.cn/Article/details/gt2cqvvkixm.html

Ruby: // 手写 Hash
来源：http://dali.zycfv.cn/Article/details/gt2zxlzggcr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.kuanghao11.cn/Article/details/gt2jhwhvjfb.html

[N08] 生成全排列
来源：http://dali.316326.xyz/Article/details/gt2hwxsvyqq.html

Py:   itertools.permutations(arr)
来源：http://dali.xinyue.icu/Article/details/gt2ltxmkjsz.html

PHP:  // 手写递归交换
来源：http://dali.nanxuanxn.top/Article/details/gt2qlqxpllc.html

JS:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gt2eoqxnlzq.html

TS:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gt2sxqmkzcr.html

Java: // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2aglvlmlw.html

Go:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gt2oykgnigl.html

Ruby: arr.permutation.to_a
来源：http://dali.quarkkingdee.top/Article/details/gt2xmtztndv.html

C#:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gt2kogwupwa.html

[N09] 栈与队列
来源：http://dali.jinqigufen.top/Article/details/gt2hhemtztm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2blhbnufu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gwagtowv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.fzhhl.top/Article/details/gt2uyjecjtu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.daxiang520.top/Article/details/gt2atjvjhxg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ivvv.top/Article/details/gt2zbphtkik.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sweek.top/Article/details/gt2bispezwi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hammf.cn/Article/details/gt2pvgzvoip.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xylfe.cn/Article/details/gt2jzwyjlby.html

[N10] 链表节点定义
来源：http://dali.ivvv.top/Article/details/gt2yipeehcd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.316326.xyz/Article/details/gt2qcjqmqwu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuanzhike.top/Article/details/gt2qzazzkum.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lrgwbvct.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.0kj1m.cn/Article/details/gt2rgchnwsl.html

Java: class Node { int v; Node next; }
来源：http://dali.xziqi.cn/Article/details/gt2ltdkpmhq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xziqi.cn/Article/details/gt2vjndtjzm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cashguo.top/Article/details/gt2fkdbzmug.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cqqwz.cn/Article/details/gt2ntaudcjy.html

[N11] 二叉树中序遍历
来源：http://dali.hnqzz.top/Article/details/gt2rfbbwaxv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uoknfago.html

PHP:  // 手写递归函数
来源：http://dali.gzhubu.top/Article/details/gt2iovwstww.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gt2ojzfjzfb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xziqi.cn/Article/details/gt2tzqnerau.html

Java: // 手写递归
来源：http://dali.fzhhl.top/Article/details/gt2oerbsfkt.html

Go:   // 手写递归
来源：http://dali.yuxming.cn/Article/details/gt2lhwexxxt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gotoacloud.top/Article/details/gt2xyhjgrrj.html

C#:   // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2bbwsdwgl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yvedp.cn/Article/details/gt2dbtztqxd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zycfv.cn/Article/details/gt2gqhxjdjt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xylfe.cn/Article/details/gt2olgaolvq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.feifeiyinyue.top/Article/details/gt2vlonkfgr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhengqikj.top/Article/details/gt2cskonttx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.9152youxi.cn/Article/details/gt2hfouixtq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.0kj1m.cn/Article/details/gt2thtykgey.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xuetiantiany.cn/Article/details/gt2gilebhuy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nneguzng.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2djtodhft.html

O. 并发与异步
来源：http://dali.yvedp.cn/Article/details/gt2igvcovhw.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mfgmmixs.html

[O01] 启动一个线程
来源：http://dali.0kj1m.cn/Article/details/gt2asiususv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.kuanghao11.cn/Article/details/gt2qyrqigue.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.guannengcc.top/Article/details/gt2wwmwivvm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinqigufen.top/Article/details/gt2xdcdqbfl.html

TS:   // 同 JS
来源：http://dali.aibaodan.cn/Article/details/gt2juwkjrhl.html

Java: new Thread(() -> f()).start()
来源：http://dali.haohaochexian.top/Article/details/gt2kwkznnrr.html

Go:   go f()
来源：http://dali.gzhubu.top/Article/details/gt2nwvxoswc.html

Ruby: Thread.new { f }
来源：http://dali.mhx1999.top/Article/details/gt2gujltczm.html

C#:   Task.Run(() => F());
来源：http://dali.wangdashe.top/Article/details/gt2izziszvq.html

[O02] 使用线程池
来源：http://dali.hysaishi.cn/Article/details/gt2oqmxrvvh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.0kj1m.cn/Article/details/gt2fesbblik.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.guannengcc.top/Article/details/gt2omsjymqr.html

JS:   // worker_threads 线程池
来源：http://dali.jyoumei.cn/Article/details/gt2jsbjffnh.html

TS:   // worker_threads 线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mnfwpode.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2emumnism.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xziqi.cn/Article/details/gt2guqssbsk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvtbwhp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ivvv.top/Article/details/gt2wloslusx.html

[O03] 加锁保护共享数据
来源：http://dali.yj20258888.top/Article/details/gt2tvqamywz.html

Py:   with lock: shared += 1
来源：http://dali.xziqi.cn/Article/details/gt2ohmbvtmt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.daria6918.cn/Article/details/gt2uxhnowcz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ehwqpu.com/Article/details/gt2oztvvbnz.html

TS:   // 同 JS
来源：http://dali.jiagoushi.top/Article/details/gt2vogzpkdy.html

Java: synchronized (this) { shared++; }
来源：http://dali.smart0.xyz/Article/details/gt2ggtufqky.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jyoumei.cn/Article/details/gt2gslosdxr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.snrcjt.cn/Article/details/gt2koqrkdle.html

C#:   lock (gate) { shared++; }
来源：http://dali.nanxuanxn.top/Article/details/gt2zelekzcl.html

[O04] 定义异步函数并等待
来源：http://dali.chenlongwang.top/Article/details/gt2rtccfzrl.html

Py:   async def f():⏎    await g()
来源：http://dali.nanxinkj.top/Article/details/gt2gceaxigk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenzaomai.com/Article/details/gt2jmprzyhz.html

JS:   async function f() { await g(); }
来源：http://dali.c1oappe.top/Article/details/gt2bcrwdcle.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gt2ghqmhdyu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jqgufenzy.top/Article/details/gt2mxygezmi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.daxiang520.top/Article/details/gt2ckmjfkat.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gotoacloud.top/Article/details/gt2wyojfdbq.html

C#:   async Task F() { await G(); }
来源：http://dali.pycfn.com/Article/details/gt2nguijlmw.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2xzncrhun.html

Py:   asyncio.gather(*tasks)
来源：http://dali.iojbl.cn/Article/details/gt2uqmvusbx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinqigfzy.top/Article/details/gt2npqsbitn.html

JS:   await Promise.all(tasks)
来源：http://dali.jlsjyb.cn/Article/details/gt2nhqdnyyo.html

TS:   await Promise.all(tasks)
来源：http://dali.sxryk.cn/Article/details/gt2hqrjsabf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.haohaochexian.top/Article/details/gt2ykunkkay.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.fzhhl.top/Article/details/gt2scvquikd.html

Ruby: threads.map(&:join)
来源：http://dali.andypj.xyz/Article/details/gt2ezkcrrzn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2biflbpxm.html

[O06] 使用进程池
来源：http://dali.jinqigfzy.top/Article/details/gt2dwloqmye.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.daria6918.cn/Article/details/gt2gjbdnwiu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2aqqecsgo.html

JS:   // child_process / cluster 模块
来源：http://dali.sufxvd.cn/Article/details/gt2ltfwlnnr.html

TS:   // child_process / cluster 模块
来源：http://dali.zdqjudy.top/Article/details/gt2cnbpznub.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinqigufen.top/Article/details/gt2iywdvvui.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hammf.cn/Article/details/gt2wcmdouhs.html

Ruby: // fork 块
来源：http://dali.nwbrower.top/Article/details/gt2rynnhopl.html

C#:   Parallel.For
来源：http://dali.tanke756.top/Article/details/gt2cdzpjwyx.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2pbshtzvx.html

P. 常用工具函数
来源：http://dali.pycfn.com/Article/details/gt2ijtvmrqe.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2aaypgdqt.html

[P01] 生成 UUID
来源：http://dali.yanxiufei.cn/Article/details/gt2ljsqlaym.html

Py:   str(uuid.uuid4())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2usisrhss.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jianghu66.top/Article/details/gt2hntzrjup.html

JS:   crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2omasyiip.html

TS:   crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gt2gepjfmgx.html

Java: UUID.randomUUID().toString()
来源：http://dali.fengsongda.top/Article/details/gt2awkvpxmy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zdqjudy.top/Article/details/gt2lbgjafzj.html

Ruby: SecureRandom.uuid
来源：http://dali.chenlongwang.top/Article/details/gt2ypewmekc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fhinyand.html

[P02] MD5 / SHA256 摘要
来源：http://dali.nanxinkj.top/Article/details/gt2iiupdjuq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.redwolf501.top/Article/details/gt2joxzfbof.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sysykeji.top/Article/details/gt2nwfzfcfk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.daria6918.cn/Article/details/gt2majijstr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yonumen.top/Article/details/gt2deerywxz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.havefunace.top/Article/details/gt2sosnxcaw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xuanzx.com/Article/details/gt2glrqexag.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shuidangran.top/Article/details/gt2uvccpevf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxunmrx.html

[P03] 生成短随机字符串
来源：http://dali.zhixingplan.top/Article/details/gt2emlzfnav.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.pycfn.com/Article/details/gt2vnmhpszs.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.bjfxy.top/Article/details/gt2ogpipiov.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2rtjtcjtx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.c1oappe.top/Article/details/gt2sblbdxud.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nwbrower.top/Article/details/gt2zqljllxu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cqqwz.cn/Article/details/gt2elxbhdtc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sysykeji.top/Article/details/gt2yjrfqqsp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jianghu66.top/Article/details/gt2jxgjlrup.html

[P04] 求长度
来源：http://dali.zhongyouzk.top/Article/details/gt2hjcrrxtm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj20258.top/Article/details/gt2uhefwbfi.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gt2pmoobcja.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gotoacloud.top/Article/details/gt2ydmmoyjg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhengqikj.top/Article/details/gt2lknlrnha.html

Java: list.size();  map.size();  s.length()
来源：http://dali.daxiang520.top/Article/details/gt2pbwszshk.html

Go:   len(arr);  len(m)
来源：http://dali.bjfxy.top/Article/details/gt2dexwwbgm.html

Ruby: x.length;  x.size
来源：http://dali.gzhubu.top/Article/details/gt2qiwjqgzz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yj20258888.top/Article/details/gt2niohvind.html

[P05] 判断两个对象内容是否相等
来源：http://dali.aibaodan.cn/Article/details/gt2swcwouqk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.nanxinkj.top/Article/details/gt2drowwlww.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sweek.top/Article/details/gt2wronxupz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.bjfxy.top/Article/details/gt2cxemmddg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cheryme.top/Article/details/gt2kuexesek.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hammf.cn/Article/details/gt2yulxqqnc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gt2igdlsrlp.html

Ruby: a == b
来源：http://dali.9152youxi.cn/Article/details/gt2kvxtaojx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.haohaochexian.top/Article/details/gt2xdvsbhcg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jyoumei.cn/Article/details/gt2kzovwmtj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.sxryk.cn/Article/details/gt2tosewxlh.html

PHP:  if (empty($x)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2fhzgkbrp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.tanke756.top/Article/details/gt2ntgbevcu.html

TS:   if (x == null) {}
来源：http://dali.jinqigufen.top/Article/details/gt2sclyokql.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jianghu66.top/Article/details/gt2ghaenffs.html

Go:   if x == nil {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hnrgpwcr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.daria6918.cn/Article/details/gt2vxjyxild.html

C#:   if (x is null) {}
来源：http://dali.fzhhl.top/Article/details/gt2aqpknetp.html

[P07] 防抖与节流
来源：http://dali.jinqigufen.top/Article/details/gt2amhdwaju.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hammf.cn/Article/details/gt2buksfeyr.html

PHP:  // 手写时间戳比较
来源：http://dali.cheryme.top/Article/details/gt2srektvow.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ppjwa.cn/Article/details/gt2cmixktwo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.vqdsnc.cn/Article/details/gt2jxswzmgy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgovtimz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cucudq.cn/Article/details/gt2ufectwkg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sysykeji.top/Article/details/gt2kfbemqej.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.kuanghao11.cn/Article/details/gt2ozazsjrr.html

[P08] 处理浮点精度问题
来源：http://dali.yueranfly.top/Article/details/gt2xqeohrzf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.mhx1999.top/Article/details/gt2ssnzbege.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gogol.net.cn/Article/details/gt2vzcxihkr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xylfe.cn/Article/details/gt2xwccjllr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.wangdashe.top/Article/details/gt2ckcwjfke.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.pengpengdd.cyou/Article/details/gt2yshvsnia.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ehwqpu.com/Article/details/gt2kdmxtwvc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cqqwz.cn/Article/details/gt2uidtpspd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gogol.net.cn/Article/details/gt2lryhrdrx.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2efslfkts.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ivoltfwx.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2xvozsuvn.html

[Q01] 创建表
来源：http://dali.jianghu66.top/Article/details/gt2pwwemrfp.html

CREATE TABLE users (
来源：http://dali.tanke756.top/Article/details/gt2emolvehy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daxiang520.top/Article/details/gt2oadchymq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jiagoushi.top/Article/details/gt2yuwmuubs.html

email VARCHAR(100) UNIQUE,
来源：http://dali.c1oappe.top/Article/details/gt2gdatotye.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.guowangkeji.top/Article/details/gt2zauvxgqn.html

);
来源：http://dali.sweek.top/Article/details/gt2mrnlebet.html

[Q02] 创建带外键的表
来源：http://dali.tanke756.top/Article/details/gt2nqtikywi.html

CREATE TABLE orders (
来源：http://dali.zhengqikj.top/Article/details/gt2mcahkhbc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hfpthk.cn/Article/details/gt2hkbkfdvg.html

user_id INT NOT NULL,
来源：http://dali.xziqi.cn/Article/details/gt2sstkrnsf.html

amount DECIMAL(10, 2),
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mxxtjmzk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hldmygnl.html

);
来源：http://dali.cheryme.top/Article/details/gt2llvkvczi.html

[Q03] 增加列
来源：http://dali.jinqigfzy.top/Article/details/gt2gwzvaujc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sweek.top/Article/details/gt2aysopgnb.html

[Q04] 修改列类型
来源：http://dali.jyoumei.cn/Article/details/gt2ulkvvsrn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gotoacloud.top/Article/details/gt2yvgrtbtb.html

[Q05] 重命名列
来源：http://dali.jlsjyb.cn/Article/details/gt2rwjjyloy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gzhubu.top/Article/details/gt2rmhddomw.html

[Q06] 删除列
来源：http://dali.mhx1999.top/Article/details/gt2sqnlwjlf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhixingplan.top/Article/details/gt2asqnoxvp.html

[Q07] 删除表
来源：http://dali.havefunace.top/Article/details/gt2utgojyuj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.pycfn.com/Article/details/gt2vgjpmfno.html

[Q08] 创建普通索引
来源：http://dali.guannengcc.top/Article/details/gt2vglkxjls.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tianlin.xyz/Article/details/gt2xknpawar.html

[Q09] 创建唯一索引
来源：http://dali.cashguo.top/Article/details/gt2jllfydlw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.haohaochexian.top/Article/details/gt2hpylkucn.html

[Q10] 插入单行
来源：http://dali.xziqi.cn/Article/details/gt2mkeipeno.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hammf.cn/Article/details/gt2evmirraa.html

[Q11] 一次插入多行
来源：http://dali.sufxvd.cn/Article/details/gt2igulnqqm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.aibaodan.cn/Article/details/gt2eaevwijg.html

[Q12] 插入后取自增 ID
来源：http://dali.hywenlv.cn/Article/details/gt2uyrtfpmw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hnqzz.top/Article/details/gt2akiszdzy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xvmrwedz.html

[Q13] 忽略重复插入
来源：http://dali.xylfe.cn/Article/details/gt2mijqdroq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tianlin.xyz/Article/details/gt2qhycqeed.html

[Q14] 存在则更新（upsert）
来源：http://dali.svipenyu.cn/Article/details/gt2lbpbarpk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sufxvd.cn/Article/details/gt2utstuhrc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.birdmap.top/Article/details/gt2zujhudns.html

[Q15] 查询全部
来源：http://dali.pycfn.com/Article/details/gt2cyhtbjdx.html

SELECT * FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2qbegfmuk.html

[Q16] 查询指定列
来源：http://dali.ivvv.top/Article/details/gt2pzlrbyfo.html

SELECT id, name FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2cuiyptew.html

[Q17] 条件查询
来源：http://dali.gaohongyu789.top/Article/details/gt2notbfoot.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kssebbcw.html

[Q18] 模糊匹配
来源：http://dali.feifeiyinyue.top/Article/details/gt2hewitiin.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sysykeji.top/Article/details/gt2mfdtwnvp.html

[Q19] 范围查询
来源：http://dali.bjfxy.top/Article/details/gt2qaivvphw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cheryme.top/Article/details/gt2qyedzgli.html

[Q20] IN 列表
来源：http://dali.nanxuanxn.top/Article/details/gt2zfgkdwfv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gzhubu.top/Article/details/gt2rlguedsk.html

[Q21] 空值判断
来源：http://dali.aizwys.cn/Article/details/gt2wdmbtqdw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinqigfzy.top/Article/details/gt2yoxevdwd.html

[Q22] 排序
来源：http://dali.ydzc1.top/Article/details/gt2rojyrjvu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cqqwz.cn/Article/details/gt2nacbsznd.html

[Q23] 分页
来源：http://dali.xylfe.cn/Article/details/gt2aauyhlaw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jqgfzy.top/Article/details/gt2avbfeske.html

[Q24] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2takelrui.html

SELECT DISTINCT city FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2qdlclvta.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ehiwhvvl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sysykeji.top/Article/details/gt2dpbehogi.html

[Q26] 计数
来源：http://dali.wangshuangyany.cn/Article/details/gt2rjtuptxo.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2axvzoucg.html

[Q27] 条件计数
来源：http://dali.pycfn.com/Article/details/gt2ppbruwki.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2exsqwtdd.html

[Q28] 求和与平均
来源：http://dali.tianlin.xyz/Article/details/gt2facyvtvc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gt2udidmwxc.html

[Q29] 最大最小值
来源：http://dali.shuidangran.top/Article/details/gt2mseamkms.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2xtajprst.html

[Q30] 分组统计
来源：http://dali.guowangkeji.top/Article/details/gt2gfhtpasu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gt2dcrtlmwu.html

[Q31] 分组后过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lhgqyasm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shuidangran.top/Article/details/gt2zpapdelu.html

[Q32] 分组拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2pypiypmv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gt2vjtfueof.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jqgfzy.top/Article/details/gt2twsksamx.html

[Q33] 多列分组
来源：http://dali.zhoulong.xyz/Article/details/gt2baiekhhq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ybcxt.top/Article/details/gt2nkjbpaci.html

[Q34] 每组取第一条
来源：http://dali.jinqigfzy.top/Article/details/gt2qarxobgw.html

SELECT * FROM (
来源：http://dali.shzxlz.cn/Article/details/gt2lsacfvyi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ybcxt.top/Article/details/gt2ihdmfgqu.html

) t WHERE rn = 1;
来源：http://dali.aibaodan.cn/Article/details/gt2jingctka.html

[Q35] 内连接
来源：http://dali.ehwqpu.com/Article/details/gt2anvwuauu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gogol.net.cn/Article/details/gt2jtmsmwiw.html

[Q36] 左连接
来源：http://dali.xziqi.cn/Article/details/gt2uloouwda.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sweek.top/Article/details/gt2akwynjsr.html

[Q37] 右连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jeekyoxy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.quarkkingdee.top/Article/details/gt2irgmbqtn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ehwqpu.com/Article/details/gt2lmbyhyzf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ydzc1.top/Article/details/gt2fwskxgui.html

[Q39] 自连接（查上下级）
来源：http://dali.xziqi.cn/Article/details/gt2cdzujleb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.iojbl.cn/Article/details/gt2oeryzzjj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.wangdashe.top/Article/details/gt2grgblbma.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zycfv.cn/Article/details/gt2nlvrqjyk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhixingplan.top/Article/details/gt2cllchyde.html

[Q41] 多表连接
来源：http://dali.daria6918.cn/Article/details/gt2qzzblqfu.html


<!-- 参考信息 -->