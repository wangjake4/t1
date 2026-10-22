代发 wailian999

Ruby: s == s.reverse
来源：http://dali.mhx1999.top/Article/details/gt2vpzhjxio.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.meibo888.top/Article/details/gt2nytabeze.html

[N07] 两数之和（返回下标）
来源：http://dali.ydzc1.top/Article/details/gt2zbclhwes.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cashguo.top/Article/details/gt2abnjxlhp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj20258888.top/Article/details/gt2yhnuxtjy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hhtspqgy.html

TS:   // 手写 Map<string, number>
来源：http://dali.gzhubu.top/Article/details/gt2pxbcagpa.html

Java: // 手写 HashMap
来源：http://dali.yangfankeji.com/Article/details/gt2praljxwa.html

Go:   // 手写 map[int]int
来源：http://dali.aizwys.cn/Article/details/gt2gxrcuhqf.html

Ruby: // 手写 Hash
来源：http://dali.hammf.cn/Article/details/gt2xparxgaa.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2azxongmh.html

[N08] 生成全排列
来源：http://dali.tianlin.xyz/Article/details/gt2pilqojps.html

Py:   itertools.permutations(arr)
来源：http://dali.pycfn.com/Article/details/gt2emrsociq.html

PHP:  // 手写递归交换
来源：http://dali.tanke756.top/Article/details/gt2yelihmns.html

JS:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2mpahdtkm.html

TS:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gt2jgtbrkom.html

Java: // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2zieksmni.html

Go:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gt2kcuvtziw.html

Ruby: arr.permutation.to_a
来源：http://dali.ehwqpu.com/Article/details/gt2nndymcoo.html

C#:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xlnzcmjd.html

[N09] 栈与队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ygekeqdk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nanxinkj.top/Article/details/gt2mlaqwwfv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.316326.xyz/Article/details/gt2nmtvgkvz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gt2fexepfqa.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.smart0.xyz/Article/details/gt2puwcymwo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hammf.cn/Article/details/gt2ppxdmlqh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.havefunace.top/Article/details/gt2kdmsczye.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gt2lyvcpaft.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj202588.top/Article/details/gt2undbbkfj.html

[N10] 链表节点定义
来源：http://dali.zycfv.cn/Article/details/gt2nvqijatr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hysaishi.cn/Article/details/gt2myrfnteh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.havefunace.top/Article/details/gt2xkvzkpee.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vbqqvtbp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jqgfzy.top/Article/details/gt2yplzzihq.html

Java: class Node { int v; Node next; }
来源：http://dali.jqgufenzy.top/Article/details/gt2crszorak.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gzhubu.top/Article/details/gt2hvlwipgs.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nanxuanxn.top/Article/details/gt2ufkpibmc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ydzc1.top/Article/details/gt2jpcrckxr.html

[N11] 二叉树中序遍历
来源：http://dali.redwolf501.top/Article/details/gt2zliodyad.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jyoumei.cn/Article/details/gt2idyajqqf.html

PHP:  // 手写递归函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2kxgvzian.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sweek.top/Article/details/gt2bqredhlm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tian-w.cn/Article/details/gt2hbjmgqwg.html

Java: // 手写递归
来源：http://dali.bjfxy.top/Article/details/gt2tbhvxahb.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2copafdqk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj202588.top/Article/details/gt2ffmoxwpd.html

C#:   // 手写递归
来源：http://dali.daxiang520.top/Article/details/gt2nqcudltp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.svipenyu.cn/Article/details/gt2uwvhgrmx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.quarkkingdee.top/Article/details/gt2rrwjzisf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hywenlv.cn/Article/details/gt2pwxmtuvu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hysaishi.cn/Article/details/gt2ucputshz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhongyouzk.top/Article/details/gt2wlhbgrdu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iismbnrt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenlongwang.top/Article/details/gt2dqvbghwm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ehwqpu.com/Article/details/gt2gsdrksgw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ehwqpu.com/Article/details/gt2dvjfakzk.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2qfgurivn.html

O. 并发与异步
来源：http://dali.ivvv.top/Article/details/gt2wbqztvhy.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2nkzzocsb.html

[O01] 启动一个线程
来源：http://dali.yj202588.top/Article/details/gt2trvjqmgx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hammf.cn/Article/details/gt2caacgppq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sufxvd.cn/Article/details/gt2dbkxdwrf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yuxming.cn/Article/details/gt2dwnfxesl.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2qychxorg.html

Java: new Thread(() -> f()).start()
来源：http://dali.vqdsnc.cn/Article/details/gt2ihzoodqi.html

Go:   go f()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fjepxbbn.html

Ruby: Thread.new { f }
来源：http://dali.316326.xyz/Article/details/gt2insgdbmy.html

C#:   Task.Run(() => F());
来源：http://dali.xinyue.icu/Article/details/gt2fmwluwnm.html

[O02] 使用线程池
来源：http://dali.daxiang520.top/Article/details/gt2ylkrpwud.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhoulong.xyz/Article/details/gt2fftstzaj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.andypj.xyz/Article/details/gt2dskruneg.html

JS:   // worker_threads 线程池
来源：http://dali.yj20258888.top/Article/details/gt2bsjbxqrj.html

TS:   // worker_threads 线程池
来源：http://dali.zycfv.cn/Article/details/gt2pnsynynu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.dianchejie.cn/Article/details/gt2pgcyumgw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.vqdsnc.cn/Article/details/gt2qljbiyxl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.guannengcc.top/Article/details/gt2kreqsykb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jvkrhcuf.html

[O03] 加锁保护共享数据
来源：http://dali.wangshuangyany.cn/Article/details/gt2glusasih.html

Py:   with lock: shared += 1
来源：http://dali.wangdashe.top/Article/details/gt2dtgpxlfx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hywenlv.cn/Article/details/gt2rytbhrep.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sxryk.cn/Article/details/gt2zszzgpzp.html

TS:   // 同 JS
来源：http://dali.yuxming.cn/Article/details/gt2bjowsebq.html

Java: synchronized (this) { shared++; }
来源：http://dali.fengsongda.top/Article/details/gt2odgtzemm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.fzhhl.top/Article/details/gt2zgmpvbap.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xinyue.icu/Article/details/gt2jodjzqyv.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj202588.top/Article/details/gt2tibkipju.html

[O04] 定义异步函数并等待
来源：http://dali.guowangkeji.top/Article/details/gt2vyosofef.html

Py:   async def f():⏎    await g()
来源：http://dali.chenlongwang.top/Article/details/gt2caooyxfk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hnqzz.top/Article/details/gt2rvyhtqzq.html

JS:   async function f() { await g(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2upjtdrqr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cdnleiting.top/Article/details/gt2yeqcovpf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dianchejie.cn/Article/details/gt2bmsquyes.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj20258888.top/Article/details/gt2ekeniyun.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhoulong.xyz/Article/details/gt2blvuwnxu.html

C#:   async Task F() { await G(); }
来源：http://dali.xuanzx.com/Article/details/gt2vnpxtluz.html

[O05] 并发执行并等待全部完成
来源：http://dali.wangdashe.top/Article/details/gt2lnodjmuk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.guowangkeji.top/Article/details/gt2lvygbtax.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yj20258888.top/Article/details/gt2wdklabfs.html

JS:   await Promise.all(tasks)
来源：http://dali.sufxvd.cn/Article/details/gt2bbihtkqn.html

TS:   await Promise.all(tasks)
来源：http://dali.aizwys.cn/Article/details/gt2yphabaxr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj20258888.top/Article/details/gt2yxwtpjuu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gotoacloud.top/Article/details/gt2cutqaiug.html

Ruby: threads.map(&:join)
来源：http://dali.ppjwa.cn/Article/details/gt2kfpenebu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sysykeji.top/Article/details/gt2jfnekagf.html

[O06] 使用进程池
来源：http://dali.hysaishi.cn/Article/details/gt2uqneixom.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ivvv.top/Article/details/gt2mkjxqidg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinqigfzy.top/Article/details/gt2vvqbnkmx.html

JS:   // child_process / cluster 模块
来源：http://dali.zhengqikj.top/Article/details/gt2nvcnkxnb.html

TS:   // child_process / cluster 模块
来源：http://dali.chenzaomai.com/Article/details/gt2wxabqtcq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhongyouzk.top/Article/details/gt2zwabsshi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.feifeiyinyue.top/Article/details/gt2xmicdsjb.html

Ruby: // fork 块
来源：http://dali.ivvv.top/Article/details/gt2mooogyha.html

C#:   Parallel.For
来源：http://dali.hnqzz.top/Article/details/gt2rexlpodd.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2eecxzgbo.html

P. 常用工具函数
来源：http://dali.dashuyun.cn/Article/details/gt2taorntlh.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2owmyzrfn.html

[P01] 生成 UUID
来源：http://dali.svipenyu.cn/Article/details/gt2bxtmqidz.html

Py:   str(uuid.uuid4())
来源：http://dali.jiagoushi.top/Article/details/gt2tqnndbhc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.chenzaomai.com/Article/details/gt2yrkzfxbr.html

JS:   crypto.randomUUID()
来源：http://dali.jianghu66.top/Article/details/gt2bnsxsqqk.html

TS:   crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gt2kflyudvc.html

Java: UUID.randomUUID().toString()
来源：http://dali.gzhubu.top/Article/details/gt2cwilblhq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhixingplan.top/Article/details/gt2bhxmatne.html

Ruby: SecureRandom.uuid
来源：http://dali.sufxvd.cn/Article/details/gt2ubnfwhmd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tanke756.top/Article/details/gt2vlgctwsj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.nanxinkj.top/Article/details/gt2gqdtvkwd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yvedp.cn/Article/details/gt2lrkbwsrz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2piyubyqq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ivvv.top/Article/details/gt2iioejxft.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.guannengcc.top/Article/details/gt2lespzkle.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cucudq.cn/Article/details/gt2mdznfqhi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zycfv.cn/Article/details/gt2qkletvig.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.svipenyu.cn/Article/details/gt2kochbrua.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xylfe.cn/Article/details/gt2xqvzzoda.html

[P03] 生成短随机字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2nzmhewhi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.316326.xyz/Article/details/gt2ctzvpzuk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pdouvujm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gt2fbhpwlzi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aizwys.cn/Article/details/gt2lriomrpc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bgponipm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj202588.top/Article/details/gt2myfvghvz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.fzhhl.top/Article/details/gt2nzsclxwp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eqjcqvhu.html

[P04] 求长度
来源：http://dali.sysykeji.top/Article/details/gt2vpcejtoa.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cqqwz.cn/Article/details/gt2cjuokulh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gt2igzwtnhk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.0kj1m.cn/Article/details/gt2dyohryrx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.0kj1m.cn/Article/details/gt2ofdgsckq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cdnleiting.top/Article/details/gt2tnowatjt.html

Go:   len(arr);  len(m)
来源：http://dali.gotoacloud.top/Article/details/gt2ayxreqwc.html

Ruby: x.length;  x.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dbiieixv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yj20258.top/Article/details/gt2hapvtkgt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xziqi.cn/Article/details/gt2gyxtlolu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinqigufen.top/Article/details/gt2szynpgtt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.fzhhl.top/Article/details/gt2lmpgcgak.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bjoewyrk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guowangkeji.top/Article/details/gt2ctpdqsta.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pdgvqiby.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xylfe.cn/Article/details/gt2iyoehekl.html

Ruby: a == b
来源：http://dali.iojbl.cn/Article/details/gt2ixwaoofh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xinyue.icu/Article/details/gt2zppbkrjq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nwbrower.top/Article/details/gt2pchhvzyu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jqgufenzy.top/Article/details/gt2zwzjxjmi.html

PHP:  if (empty($x)) {}
来源：http://dali.cucudq.cn/Article/details/gt2jccaezvu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.meibo888.top/Article/details/gt2nzfznrkc.html

TS:   if (x == null) {}
来源：http://dali.havefunace.top/Article/details/gt2qbuzsyrd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ekmahkqe.html

Go:   if x == nil {}
来源：http://dali.guannengcc.top/Article/details/gt2ajxeeyua.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xylfe.cn/Article/details/gt2uiefcdqe.html

C#:   if (x is null) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2qodyoxwk.html

[P07] 防抖与节流
来源：http://dali.jianghu66.top/Article/details/gt2wcfhwwbk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rcxozlhy.html

PHP:  // 手写时间戳比较
来源：http://dali.guowangkeji.top/Article/details/gt2rzqzkniu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gt2hwtqphcp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aizwys.cn/Article/details/gt2lwodbxud.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.redwolf501.top/Article/details/gt2odpyzoif.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hongshengwenyu.top/Article/details/gt2brdcdvoj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jiagoushi.top/Article/details/gt2ihixmwce.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.tian-w.cn/Article/details/gt2xzwfkazo.html

[P08] 处理浮点精度问题
来源：http://dali.cucudq.cn/Article/details/gt2wkrmhiry.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shangyingyoupin.top/Article/details/gt2nzkhadod.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jyoumei.cn/Article/details/gt2ojnjgebz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.pycfn.com/Article/details/gt2tzqpekjf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2armskbtt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.9152youxi.cn/Article/details/gt2bsefxzwk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.snrcjt.cn/Article/details/gt2cofdezux.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.snrcjt.cn/Article/details/gt2oflstrzn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hysaishi.cn/Article/details/gt2cwuzmpir.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2wnbxfnzw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.pycfn.com/Article/details/gt2cwncfyow.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2kfhgtplj.html

[Q01] 创建表
来源：http://dali.guannengcc.top/Article/details/gt2tqwrghju.html

CREATE TABLE users (
来源：http://dali.gogol.net.cn/Article/details/gt2nuvuikqr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.birdmap.top/Article/details/gt2recvauqe.html

name VARCHAR(50) NOT NULL,
来源：http://dali.daxiang520.top/Article/details/gt2wbrzoawl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iysmwjax.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.dianchejie.cn/Article/details/gt2lqjermwi.html

);
来源：http://dali.gogol.net.cn/Article/details/gt2ptksrxde.html

[Q02] 创建带外键的表
来源：http://dali.jinqigufen.top/Article/details/gt2jstkmwbi.html

CREATE TABLE orders (
来源：http://dali.hysaishi.cn/Article/details/gt2svrbguak.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.smart0.xyz/Article/details/gt2xpklnrya.html

user_id INT NOT NULL,
来源：http://dali.hnqzz.top/Article/details/gt2ypjtdtop.html

amount DECIMAL(10, 2),
来源：http://dali.quarkkingdee.top/Article/details/gt2bnfuztpr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cucudq.cn/Article/details/gt2cfxrtvag.html

);
来源：http://dali.hammf.cn/Article/details/gt2dnpjtodv.html

[Q03] 增加列
来源：http://dali.nwbrower.top/Article/details/gt2klyuzwvr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sufxvd.cn/Article/details/gt2puatvcqn.html

[Q04] 修改列类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2orniwwqb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xuetiantiany.cn/Article/details/gt2bjwnzqac.html

[Q05] 重命名列
来源：http://dali.zhixingplan.top/Article/details/gt2ycgzmoha.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.snrcjt.cn/Article/details/gt2dzznqaiw.html

[Q06] 删除列
来源：http://dali.dashuyun.cn/Article/details/gt2kidqoukc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cqlpabgw.html

[Q07] 删除表
来源：http://dali.xinyue.icu/Article/details/gt2ocazpntt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqgtpwe.html

[Q08] 创建普通索引
来源：http://dali.hongshengwenyu.top/Article/details/gt2pcxwiuyv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.0kj1m.cn/Article/details/gt2dgkmqqfh.html

[Q09] 创建唯一索引
来源：http://dali.sysykeji.top/Article/details/gt2lbycgete.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gt2ueqoydkf.html

[Q10] 插入单行
来源：http://dali.chenlongwang.top/Article/details/gt2hptyfgou.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.fengsongda.top/Article/details/gt2mzhlebcc.html

[Q11] 一次插入多行
来源：http://dali.cashguo.top/Article/details/gt2mrcdpafx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.guowangkeji.top/Article/details/gt2tigrgsll.html

[Q12] 插入后取自增 ID
来源：http://dali.tianlin.xyz/Article/details/gt2bmamuewx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.redwolf501.top/Article/details/gt2pxaexttw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hongshengwenyu.top/Article/details/gt2lyetuktv.html

[Q13] 忽略重复插入
来源：http://dali.tian-w.cn/Article/details/gt2raljnigx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.aizwys.cn/Article/details/gt2eejhfcfu.html

[Q14] 存在则更新（upsert）
来源：http://dali.yongpay.top/Article/details/gt2grlxywwy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.aibaodan.cn/Article/details/gt2xxsfslyq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cucudq.cn/Article/details/gt2deuizmjj.html

[Q15] 查询全部
来源：http://dali.jqgufenzy.top/Article/details/gt2nlcmpttx.html

SELECT * FROM users;
来源：http://dali.pycfn.com/Article/details/gt2gadjvaer.html

[Q16] 查询指定列
来源：http://dali.yueranfly.top/Article/details/gt2lehdzyuy.html

SELECT id, name FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2fpxzqcyv.html

[Q17] 条件查询
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pavwlsmx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hammf.cn/Article/details/gt2aocovhqf.html

[Q18] 模糊匹配
来源：http://dali.chenjidiqi.icu/Article/details/gt2fxcfrbri.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.fengsongda.top/Article/details/gt2cmjzgsco.html

[Q19] 范围查询
来源：http://dali.ybcxt.top/Article/details/gt2qlzpwpuu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ppjwa.cn/Article/details/gt2wcyydwfv.html

[Q20] IN 列表
来源：http://dali.smart0.xyz/Article/details/gt2bayhuywf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sweek.top/Article/details/gt2smxyslsu.html

[Q21] 空值判断
来源：http://dali.feifeiyinyue.top/Article/details/gt2qppjenev.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hnxiangtu.top/Article/details/gt2xecnqoup.html

[Q22] 排序
来源：http://dali.jianghu66.top/Article/details/gt2tdaoimff.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.fengsongda.top/Article/details/gt2uovsusfi.html

[Q23] 分页
来源：http://dali.jinqigfzy.top/Article/details/gt2mvdsgqfz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj20258888.top/Article/details/gt2nrfnavxb.html

[Q24] 去重
来源：http://dali.dashuyun.cn/Article/details/gt2icjexgre.html

SELECT DISTINCT city FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2agnfuqko.html

[Q25] 只取前 N 条
来源：http://dali.haohaochexian.top/Article/details/gt2incurazk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.9152youxi.cn/Article/details/gt2qoshprtm.html

[Q26] 计数
来源：http://dali.9152youxi.cn/Article/details/gt2irrrbgtj.html

SELECT COUNT(*) FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2mzbdmnus.html

[Q27] 条件计数
来源：http://dali.c1oappe.top/Article/details/gt2aginlyjy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2ulgsyqsu.html

[Q28] 求和与平均
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yegsfrrn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gt2oupsvisf.html

[Q29] 最大最小值
来源：http://dali.jianghu66.top/Article/details/gt2nhfxdraq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.havefunace.top/Article/details/gt2wrzylgww.html

[Q30] 分组统计
来源：http://dali.jqgufenzy.top/Article/details/gt2hzsvqntt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gt2eymfjuaf.html

[Q31] 分组后过滤
来源：http://dali.xylfe.cn/Article/details/gt2vvsfxxwi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jqgufenzy.top/Article/details/gt2fbtuuwhu.html

[Q32] 分组拼接字符串
来源：http://dali.gzhubu.top/Article/details/gt2pawinzzf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qttthnxr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cheryme.top/Article/details/gt2hviunato.html

[Q33] 多列分组
来源：http://dali.jinqigfzy.top/Article/details/gt2tmgavuau.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yj202588.top/Article/details/gt2yaonbyga.html

[Q34] 每组取第一条
来源：http://dali.hnxiangtu.top/Article/details/gt2xehaduwp.html

SELECT * FROM (
来源：http://dali.gaohongyu789.top/Article/details/gt2gvoaiypj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.quarkkingdee.top/Article/details/gt2qdzsrynh.html

) t WHERE rn = 1;
来源：http://dali.yj20258888.top/Article/details/gt2nvrbobll.html

[Q35] 内连接
来源：http://dali.ppjwa.cn/Article/details/gt2gfjspbzr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ehlsnynd.html

[Q36] 左连接
来源：http://dali.jyoumei.cn/Article/details/gt2xsrdsexd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ucmxjuqy.html

[Q37] 右连接
来源：http://dali.zhongyouzk.top/Article/details/gt2sfxtfigt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shangyingyoupin.top/Article/details/gt2gxuditvb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jianghu66.top/Article/details/gt2poxnxvou.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.vqdsnc.cn/Article/details/gt2himgoixn.html

[Q39] 自连接（查上下级）
来源：http://dali.yangfankeji.com/Article/details/gt2tuedpbux.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.daria6918.cn/Article/details/gt2oksliikz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yuanzhike.top/Article/details/gt2rdsjdgyr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.aibaodan.cn/Article/details/gt2sgvtxxwb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.smart0.xyz/Article/details/gt2hcxusyib.html

[Q41] 多表连接
来源：http://dali.nanxuanxn.top/Article/details/gt2zscsjxxq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gotoacloud.top/Article/details/gt2xrtdtikf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.c1oappe.top/Article/details/gt2wiozlujd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tjaybldc.html

[Q42] 连接条件附加过滤
来源：http://dali.sxryk.cn/Article/details/gt2tjldjtzh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.vqdsnc.cn/Article/details/gt2mwwaizlh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cdnleiting.top/Article/details/gt2ktwhczwg.html

[Q43] 标量子查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hhllmtev.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.tianlin.xyz/Article/details/gt2nomposod.html

[Q44] IN 子查询
来源：http://dali.sufxvd.cn/Article/details/gt2xgomessr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tian-w.cn/Article/details/gt2yaymdrwm.html

[Q45] EXISTS 判断存在
来源：http://dali.gogol.net.cn/Article/details/gt2pngtbkip.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sweek.top/Article/details/gt2jfkhrbaf.html


<!-- 参考信息 -->