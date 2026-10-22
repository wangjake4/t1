代发 wailian999

Go:   // 手写 map[int]int
来源：http://dali.smart0.xyz/Article/details/gt2ydvgpjfn.html

Ruby: // 手写 Hash
来源：http://dali.yanxiufei.cn/Article/details/gt2puylmrcg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.guannengcc.top/Article/details/gt2hypnvriq.html

[N08] 生成全排列
来源：http://dali.yj20258888.top/Article/details/gt2eytmuohk.html

Py:   itertools.permutations(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2enaxjcgg.html

PHP:  // 手写递归交换
来源：http://dali.iojbl.cn/Article/details/gt2peceaink.html

JS:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gt2axtelsqs.html

TS:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gt2whavgpey.html

Java: // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gt2iznhqcfg.html

Go:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gt2elesuwbx.html

Ruby: arr.permutation.to_a
来源：http://dali.cheryme.top/Article/details/gt2xpltluee.html

C#:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gt2ncimzhpx.html

[N09] 栈与队列
来源：http://dali.hywenlv.cn/Article/details/gt2hqygiqmu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ydzc1.top/Article/details/gt2yzvqcgow.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gt2onyuxdzd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sxryk.cn/Article/details/gt2hxvdobsq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hammf.cn/Article/details/gt2awmvafuc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rogvkfxj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.dashuyun.cn/Article/details/gt2lvwgfrcr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tanke756.top/Article/details/gt2eyurnyeo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.vqdsnc.cn/Article/details/gt2qphprqzj.html

[N10] 链表节点定义
来源：http://dali.yj202588.top/Article/details/gt2roazbnxi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xuetiantiany.cn/Article/details/gt2sfinbhin.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2rhvaxswm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhoulong.xyz/Article/details/gt2rrzchnef.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.guowangkeji.top/Article/details/gt2thpjylyi.html

Java: class Node { int v; Node next; }
来源：http://dali.havefunace.top/Article/details/gt2yxjjweuq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhengqikj.top/Article/details/gt2lolmsyoa.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.kuanghao11.cn/Article/details/gt2leubopny.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ehwqpu.com/Article/details/gt2lwxapngt.html

[N11] 二叉树中序遍历
来源：http://dali.cucudq.cn/Article/details/gt2aagqbsnm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhoulong.xyz/Article/details/gt2nrqxpkcj.html

PHP:  // 手写递归函数
来源：http://dali.xinyue.icu/Article/details/gt2psleyhff.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sufxvd.cn/Article/details/gt2kfltxjvi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgufenzy.top/Article/details/gt2zdsoubpc.html

Java: // 手写递归
来源：http://dali.gzhubu.top/Article/details/gt2ikzsfasd.html

Go:   // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gt2riokuqjo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pvicidba.html

C#:   // 手写递归
来源：http://dali.xylfe.cn/Article/details/gt2fihtztea.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tian-w.cn/Article/details/gt2dzcfycjg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.andypj.xyz/Article/details/gt2zmhjjotk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yongpay.top/Article/details/gt2asgfyepa.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jlsjyb.cn/Article/details/gt2dzypydgj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2priekunq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.iojbl.cn/Article/details/gt2dglcigec.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.meibo888.top/Article/details/gt2mkvqelcc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zmvyjppb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yongpay.top/Article/details/gt2ktyemeus.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2zceujsfo.html

O. 并发与异步
来源：http://dali.havefunace.top/Article/details/gt2ftzwjrhh.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kopmyhew.html

[O01] 启动一个线程
来源：http://dali.0kj1m.cn/Article/details/gt2ycbxdhvd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gcilemtt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nwbrower.top/Article/details/gt2xkacgixk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.haohaochexian.top/Article/details/gt2ucvondhd.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gt2qyoytjbn.html

Java: new Thread(() -> f()).start()
来源：http://dali.yvedp.cn/Article/details/gt2ryhgsmae.html

Go:   go f()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rnakyolu.html

Ruby: Thread.new { f }
来源：http://dali.svipenyu.cn/Article/details/gt2xeaxvjrq.html

C#:   Task.Run(() => F());
来源：http://dali.bjfxy.top/Article/details/gt2kddptjwg.html

[O02] 使用线程池
来源：http://dali.hywenlv.cn/Article/details/gt2rvthvnqy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.wangdashe.top/Article/details/gt2zcrirznl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.bjfxy.top/Article/details/gt2jvroyxhy.html

JS:   // worker_threads 线程池
来源：http://dali.bjfxy.top/Article/details/gt2nddznvms.html

TS:   // worker_threads 线程池
来源：http://dali.chenzaomai.com/Article/details/gt2akuezfeh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.316326.xyz/Article/details/gt2acxaamva.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gaohongyu789.top/Article/details/gt2rbqswecb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hysaishi.cn/Article/details/gt2ekfgxtzt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gotoacloud.top/Article/details/gt2rvglrpzp.html

[O03] 加锁保护共享数据
来源：http://dali.shzxlz.cn/Article/details/gt2lqonwujf.html

Py:   with lock: shared += 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qurgrefy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uuhkflyn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.bjfxy.top/Article/details/gt2hgajmrwa.html

TS:   // 同 JS
来源：http://dali.haohaochexian.top/Article/details/gt2omhaibcp.html

Java: synchronized (this) { shared++; }
来源：http://dali.xuanzx.com/Article/details/gt2uaqrtiir.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hfpthk.cn/Article/details/gt2usqrmsme.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2atjllono.html

C#:   lock (gate) { shared++; }
来源：http://dali.tian-w.cn/Article/details/gt2wuirleie.html

[O04] 定义异步函数并等待
来源：http://dali.gogol.net.cn/Article/details/gt2cmdssewb.html

Py:   async def f():⏎    await g()
来源：http://dali.svipenyu.cn/Article/details/gt2zwhntysb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2yaaxhtob.html

JS:   async function f() { await g(); }
来源：http://dali.hfpthk.cn/Article/details/gt2qndlhptp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cashguo.top/Article/details/gt2yvenefer.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hnqzz.top/Article/details/gt2ecdhwohh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hywenlv.cn/Article/details/gt2ukpcjktz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nanxuanxn.top/Article/details/gt2whpyqlcw.html

C#:   async Task F() { await G(); }
来源：http://dali.shzxlz.cn/Article/details/gt2xabwpjnv.html

[O05] 并发执行并等待全部完成
来源：http://dali.daxiang520.top/Article/details/gt2vvosnijo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnxiangtu.top/Article/details/gt2dvksnzxx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cashguo.top/Article/details/gt2bbnmqjko.html

JS:   await Promise.all(tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rajqjaas.html

TS:   await Promise.all(tasks)
来源：http://dali.hnqzz.top/Article/details/gt2ilpakoju.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinqigfzy.top/Article/details/gt2ioagmddv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gogol.net.cn/Article/details/gt2lbfwchfl.html

Ruby: threads.map(&:join)
来源：http://dali.haohaochexian.top/Article/details/gt2ejjxuknm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.guowangkeji.top/Article/details/gt2iqppknpn.html

[O06] 使用进程池
来源：http://dali.ybcxt.top/Article/details/gt2nssadjjw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cucudq.cn/Article/details/gt2fgervqdi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yj202588.top/Article/details/gt2vwxiclif.html

JS:   // child_process / cluster 模块
来源：http://dali.c1oappe.top/Article/details/gt2tzhfduha.html

TS:   // child_process / cluster 模块
来源：http://dali.yj20258888.top/Article/details/gt2zgsmnyux.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ykrdrzob.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.bjfxy.top/Article/details/gt2anitojar.html

Ruby: // fork 块
来源：http://dali.gogol.net.cn/Article/details/gt2quocalfi.html

C#:   Parallel.For
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rxxgglyi.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2fhmpwknf.html

P. 常用工具函数
来源：http://dali.jqgufenzy.top/Article/details/gt2rpshqiiu.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2boxlbzsy.html

[P01] 生成 UUID
来源：http://dali.chenlongwang.top/Article/details/gt2setvqzvu.html

Py:   str(uuid.uuid4())
来源：http://dali.jianghu66.top/Article/details/gt2gvjxkjda.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.andypj.xyz/Article/details/gt2bbnlksnt.html

JS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gt2dehrayhx.html

TS:   crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gt2sukxvglv.html

Java: UUID.randomUUID().toString()
来源：http://dali.dashuyun.cn/Article/details/gt2uqhlfcdk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hnqzz.top/Article/details/gt2zmkcbhyx.html

Ruby: SecureRandom.uuid
来源：http://dali.shzxlz.cn/Article/details/gt2strwwzly.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.quarkkingdee.top/Article/details/gt2bqrkackk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hammf.cn/Article/details/gt2zrbdqxvm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj20258.top/Article/details/gt2gsewctdm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.snrcjt.cn/Article/details/gt2yihtpjvg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.snrcjt.cn/Article/details/gt2dsxhoowc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tian-w.cn/Article/details/gt2kkkmihob.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gt2pjqfatwk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hfpthk.cn/Article/details/gt2iqzkhrpz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nwbrower.top/Article/details/gt2bmqyqupz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.fzhhl.top/Article/details/gt2lohoblxp.html

[P03] 生成短随机字符串
来源：http://dali.jqgfzy.top/Article/details/gt2spigmqze.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jyoumei.cn/Article/details/gt2xypmunbr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jqgufenzy.top/Article/details/gt2vkbucdzf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dianchejie.cn/Article/details/gt2jpnbhhwy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuxming.cn/Article/details/gt2wrjpccov.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gotoacloud.top/Article/details/gt2ljphqvbs.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhoulong.xyz/Article/details/gt2mczycyvf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cdnleiting.top/Article/details/gt2ekfmtqfv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.redwolf501.top/Article/details/gt2pljyypzr.html

[P04] 求长度
来源：http://dali.tanke756.top/Article/details/gt2kmlhotkc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.iojbl.cn/Article/details/gt2uxsqimfh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.316326.xyz/Article/details/gt2jgxmacnu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnxiangtu.top/Article/details/gt2pgyeekte.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gt2vqgqmiln.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cucudq.cn/Article/details/gt2zttvjkbs.html

Go:   len(arr);  len(m)
来源：http://dali.xinyue.icu/Article/details/gt2wvoespry.html

Ruby: x.length;  x.size
来源：http://dali.daxiang520.top/Article/details/gt2cqvybxgv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yuanzhike.top/Article/details/gt2wgmzagdb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yuanzhike.top/Article/details/gt2vovgzwpj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.mhx1999.top/Article/details/gt2lmhzcqzy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.feifeiyinyue.top/Article/details/gt2tlicyzlg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yueranfly.top/Article/details/gt2mcgzqhgx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.kuanghao11.cn/Article/details/gt2cddcbkxf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.vqdsnc.cn/Article/details/gt2hgupheds.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fqocrgay.html

Ruby: a == b
来源：http://dali.yj20258888.top/Article/details/gt2jxupqnja.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj20258888.top/Article/details/gt2vfoaresp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2epyifrtn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.birdmap.top/Article/details/gt2dkctsfnm.html

PHP:  if (empty($x)) {}
来源：http://dali.xylfe.cn/Article/details/gt2isfjansa.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zrufwqkz.html

TS:   if (x == null) {}
来源：http://dali.redwolf501.top/Article/details/gt2psqgohxf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nanxinkj.top/Article/details/gt2ozcsaazp.html

Go:   if x == nil {}
来源：http://dali.zhongyouzk.top/Article/details/gt2surukljw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gzhubu.top/Article/details/gt2vkkbltgq.html

C#:   if (x is null) {}
来源：http://dali.yuanzhike.top/Article/details/gt2wxgmvrdg.html

[P07] 防抖与节流
来源：http://dali.dianchejie.cn/Article/details/gt2koqtobqb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.0kj1m.cn/Article/details/gt2ceamxwkl.html

PHP:  // 手写时间戳比较
来源：http://dali.quarkkingdee.top/Article/details/gt2cisyzknz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cheryme.top/Article/details/gt2btezciot.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gt2lywvxkpl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2xncxbydw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.mhx1999.top/Article/details/gt2lzruispi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gzhubu.top/Article/details/gt2yajfnjbq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.quarkkingdee.top/Article/details/gt2rrftlajp.html

[P08] 处理浮点精度问题
来源：http://dali.gotoacloud.top/Article/details/gt2jjrcxhlm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gxjiztsy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zycfv.cn/Article/details/gt2oyffxtzm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.dashuyun.cn/Article/details/gt2estwiakq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenzaomai.com/Article/details/gt2vztczfxu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yangfankeji.com/Article/details/gt2kevyfkez.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gogol.net.cn/Article/details/gt2gyktfhbw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj20258.top/Article/details/gt2okknjijm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.chenzaomai.com/Article/details/gt2unwspvad.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2eygeacsd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shangyingyoupin.top/Article/details/gt2yrpzvsgs.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2yjtbpwjg.html

[Q01] 创建表
来源：http://dali.feifeiyinyue.top/Article/details/gt2btckgoke.html

CREATE TABLE users (
来源：http://dali.tanke756.top/Article/details/gt2udlrpsdi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cdnleiting.top/Article/details/gt2mogtwrrn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shangyingyoupin.top/Article/details/gt2dwenbswm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.316326.xyz/Article/details/gt2jfvcrdvf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tianlin.xyz/Article/details/gt2xuzsdtvg.html

);
来源：http://dali.jinqigufen.top/Article/details/gt2wuntusds.html

[Q02] 创建带外键的表
来源：http://dali.hongshengwenyu.top/Article/details/gt2liogypms.html

CREATE TABLE orders (
来源：http://dali.shzxlz.cn/Article/details/gt2cxypyxqf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.andypj.xyz/Article/details/gt2swvxzsfd.html

user_id INT NOT NULL,
来源：http://dali.birdmap.top/Article/details/gt2rfzohzfo.html

amount DECIMAL(10, 2),
来源：http://dali.ppjwa.cn/Article/details/gt2jkghyjem.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jyoumei.cn/Article/details/gt2ccvzbqkv.html

);
来源：http://dali.guowangkeji.top/Article/details/gt2kqpfznao.html

[Q03] 增加列
来源：http://dali.zhoulong.xyz/Article/details/gt2ouqhsipf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xuanzx.com/Article/details/gt2mmbzvfdv.html

[Q04] 修改列类型
来源：http://dali.yvedp.cn/Article/details/gt2trgrusia.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrelorq.html

[Q05] 重命名列
来源：http://dali.yangfankeji.com/Article/details/gt2tatjcxsu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinqigfzy.top/Article/details/gt2kwbmmjxb.html

[Q06] 删除列
来源：http://dali.yj20258888.top/Article/details/gt2zxckmuhg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.kuanghao11.cn/Article/details/gt2xzfhfiek.html

[Q07] 删除表
来源：http://dali.yanxiufei.cn/Article/details/gt2kfmuwfkp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zycfv.cn/Article/details/gt2gxncouey.html

[Q08] 创建普通索引
来源：http://dali.yanxiufei.cn/Article/details/gt2wuxhysgd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gogol.net.cn/Article/details/gt2qnqxguqi.html

[Q09] 创建唯一索引
来源：http://dali.ppjwa.cn/Article/details/gt2ajiqbvvr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.tanke756.top/Article/details/gt2irzbpjme.html

[Q10] 插入单行
来源：http://dali.jinqigfzy.top/Article/details/gt2ghbgfjwy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.mhx1999.top/Article/details/gt2qwilyata.html

[Q11] 一次插入多行
来源：http://dali.haohaochexian.top/Article/details/gt2bknngeqq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jyoumei.cn/Article/details/gt2ylzmwzjp.html

[Q12] 插入后取自增 ID
来源：http://dali.316326.xyz/Article/details/gt2fpixparf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.svipenyu.cn/Article/details/gt2yflmjoll.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.haohaochexian.top/Article/details/gt2phhneuqi.html

[Q13] 忽略重复插入
来源：http://dali.yonumen.top/Article/details/gt2svjlcqam.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cjcgngbq.html

[Q14] 存在则更新（upsert）
来源：http://dali.redwolf501.top/Article/details/gt2kftstljb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tianlin.xyz/Article/details/gt2mvwfaryb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.316326.xyz/Article/details/gt2tjdmdcpk.html

[Q15] 查询全部
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rzezhtil.html

SELECT * FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2xrvlpbgu.html

[Q16] 查询指定列
来源：http://dali.yvedp.cn/Article/details/gt2jniqkckr.html

SELECT id, name FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2rnzxjgnp.html

[Q17] 条件查询
来源：http://dali.yj20258888.top/Article/details/gt2pmceeadj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinqigufen.top/Article/details/gt2kazskckp.html

[Q18] 模糊匹配
来源：http://dali.sufxvd.cn/Article/details/gt2rnihkwbi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yuanzhike.top/Article/details/gt2kbipihvp.html

[Q19] 范围查询
来源：http://dali.aizwys.cn/Article/details/gt2ufyjrjwx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj20258.top/Article/details/gt2gjgueftl.html

[Q20] IN 列表
来源：http://dali.snrcjt.cn/Article/details/gt2ydzpqdgu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.316326.xyz/Article/details/gt2zzyxmmmp.html

[Q21] 空值判断
来源：http://dali.jinqigfzy.top/Article/details/gt2pxnkrxkx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.c1oappe.top/Article/details/gt2bxlzbqgt.html

[Q22] 排序
来源：http://dali.yj202588.top/Article/details/gt2cxgkjjic.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.tian-w.cn/Article/details/gt2qikfohje.html

[Q23] 分页
来源：http://dali.sweek.top/Article/details/gt2aodjzbzz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2imswwgqz.html

[Q24] 去重
来源：http://dali.gotoacloud.top/Article/details/gt2cuyvhpuh.html

SELECT DISTINCT city FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2fbqmpflm.html

[Q25] 只取前 N 条
来源：http://dali.nanxuanxn.top/Article/details/gt2wyqzhanj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.kuanghao11.cn/Article/details/gt2becvhfqo.html

[Q26] 计数
来源：http://dali.birdmap.top/Article/details/gt2jcjsuwhc.html

SELECT COUNT(*) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2vehpthuq.html

[Q27] 条件计数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kfjtfupp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2bhzrjrbw.html

[Q28] 求和与平均
来源：http://dali.cqqwz.cn/Article/details/gt2chscvfry.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gt2jdwwekhh.html

[Q29] 最大最小值
来源：http://dali.0kj1m.cn/Article/details/gt2xgeopsac.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.meibo888.top/Article/details/gt2oonbtjap.html

[Q30] 分组统计
来源：http://dali.shzxlz.cn/Article/details/gt2ubdyarkp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.daria6918.cn/Article/details/gt2shvhcaps.html

[Q31] 分组后过滤
来源：http://dali.shzxlz.cn/Article/details/gt2khijzvaz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sxryk.cn/Article/details/gt2mftvivgf.html

[Q32] 分组拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gt2rijkigfk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eiojomrz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenlongwang.top/Article/details/gt2hpswdmqq.html

[Q33] 多列分组
来源：http://dali.c1oappe.top/Article/details/gt2spjdcrpw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.tian-w.cn/Article/details/gt2myoxeday.html

[Q34] 每组取第一条
来源：http://dali.yuxming.cn/Article/details/gt2ptboffiq.html

SELECT * FROM (
来源：http://dali.xinyue.icu/Article/details/gt2jvguuman.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ppjwa.cn/Article/details/gt2qrlcagni.html

) t WHERE rn = 1;
来源：http://dali.yueranfly.top/Article/details/gt2iaplvbwe.html

[Q35] 内连接
来源：http://dali.sysykeji.top/Article/details/gt2qevavaok.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2eucmmnhg.html

[Q36] 左连接
来源：http://dali.sweek.top/Article/details/gt2sczqjkgy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2bbhilyfv.html

[Q37] 右连接
来源：http://dali.cheryme.top/Article/details/gt2kggwcolh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sufxvd.cn/Article/details/gt2fpoqyvfd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnxiangtu.top/Article/details/gt2dgdylnvq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cqqwz.cn/Article/details/gt2uqoqggdv.html

[Q39] 自连接（查上下级）
来源：http://dali.dianchejie.cn/Article/details/gt2ujccoxbb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yongpay.top/Article/details/gt2lmsldnhq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cheryme.top/Article/details/gt2tszztyqo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yvedp.cn/Article/details/gt2rdqmattm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cdnleiting.top/Article/details/gt2otqcekva.html

[Q41] 多表连接
来源：http://dali.guowangkeji.top/Article/details/gt2kjwlzurt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinqigufen.top/Article/details/gt2haprqtwm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cashguo.top/Article/details/gt2gpqecewt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jtgoqcoo.html

[Q42] 连接条件附加过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sqxovmyw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.mhx1999.top/Article/details/gt2ceixhftw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hnqzz.top/Article/details/gt2umkzaewd.html

[Q43] 标量子查询
来源：http://dali.yj20258888.top/Article/details/gt2yakeqzrv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aizwys.cn/Article/details/gt2eoardnts.html

[Q44] IN 子查询
来源：http://dali.yuxming.cn/Article/details/gt2epylxmzw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jqgfzy.top/Article/details/gt2ybzayrsv.html

[Q45] EXISTS 判断存在
来源：http://dali.shanyushiyangtech.top/Article/details/gt2snqkncvu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxuanxn.top/Article/details/gt2rjybfmvg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sxryk.cn/Article/details/gt2qpffglko.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuetiantiany.cn/Article/details/gt2sljkmnqe.html

[Q47] 与平均值比较
来源：http://dali.jianghu66.top/Article/details/gt2gnsusbgq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.aizwys.cn/Article/details/gt2oifvuwwg.html

[Q48] CTE 公用表表达式
来源：http://dali.shzxlz.cn/Article/details/gt2yfpneqda.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinqigfzy.top/Article/details/gt2dlyynxom.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cashguo.top/Article/details/gt2nxujnojc.html

[Q49] 更新单行
来源：http://dali.yonumen.top/Article/details/gt2kqqfmplb.html


<!-- 参考信息 -->