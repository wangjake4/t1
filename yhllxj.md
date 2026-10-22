代发 wailian999

Ruby: s == s.reverse
来源：http://dali.yvedp.cn/Article/details/gt2hrcsvfdo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj20258.top/Article/details/gt2qalelkii.html

[N07] 两数之和（返回下标）
来源：http://dali.pengpengdd.cyou/Article/details/gt2hwkfmusf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oegqyuar.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sufxvd.cn/Article/details/gt2xagiswva.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.aizwys.cn/Article/details/gt2yllkylet.html

TS:   // 手写 Map<string, number>
来源：http://dali.wangdashe.top/Article/details/gt2jlcupoiu.html

Java: // 手写 HashMap
来源：http://dali.mhx1999.top/Article/details/gt2nzzkixph.html

Go:   // 手写 map[int]int
来源：http://dali.zhiwuduotai.top/Article/details/gt2fkvfulpc.html

Ruby: // 手写 Hash
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zhuifajl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hammf.cn/Article/details/gt2mmxffnfa.html

[N08] 生成全排列
来源：http://dali.svipenyu.cn/Article/details/gt2bpjogcvo.html

Py:   itertools.permutations(arr)
来源：http://dali.pycfn.com/Article/details/gt2qdxsucrt.html

PHP:  // 手写递归交换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vgorzqmh.html

JS:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2gjudfrgp.html

TS:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2phjaufya.html

Java: // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2arzmywzx.html

Go:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gt2wksvtgqe.html

Ruby: arr.permutation.to_a
来源：http://dali.ivvv.top/Article/details/gt2kzrvoand.html

C#:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gt2clraemkj.html

[N09] 栈与队列
来源：http://dali.sxryk.cn/Article/details/gt2dxzlbrto.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.pycfn.com/Article/details/gt2aafohopz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gt2plfiohiu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tian-w.cn/Article/details/gt2qppncdcp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.kuanghao11.cn/Article/details/gt2cclnbrlb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shuidangran.top/Article/details/gt2ppftnffd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.vqdsnc.cn/Article/details/gt2gqaykgqy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gt2nhxidphr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jlsjyb.cn/Article/details/gt2atkvqcky.html

[N10] 链表节点定义
来源：http://dali.jianghu66.top/Article/details/gt2klmnkehn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yuanzhike.top/Article/details/gt2ozfbqood.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tianlin.xyz/Article/details/gt2pevwarkk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.redwolf501.top/Article/details/gt2tjkbpvtg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fhbkggkw.html

Java: class Node { int v; Node next; }
来源：http://dali.smart0.xyz/Article/details/gt2thgqmozq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shangyingyoupin.top/Article/details/gt2neissnov.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kiytdxnj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.quarkkingdee.top/Article/details/gt2iprzurxa.html

[N11] 二叉树中序遍历
来源：http://dali.quarkkingdee.top/Article/details/gt2dwcfkawp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cdnleiting.top/Article/details/gt2ompyxhez.html

PHP:  // 手写递归函数
来源：http://dali.tanke756.top/Article/details/gt2faahsaiu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gzhubu.top/Article/details/gt2tpzcslaj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangdashe.top/Article/details/gt2uczwfnkl.html

Java: // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gt2tkhmtouu.html

Go:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gt2vkadqjzb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yuanzhike.top/Article/details/gt2ajniggzq.html

C#:   // 手写递归
来源：http://dali.ydzc1.top/Article/details/gt2duccvybv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hywenlv.cn/Article/details/gt2bozjncfx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenzaomai.com/Article/details/gt2dfxftxsd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.haohaochexian.top/Article/details/gt2nyolbcea.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tnkwlmbw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.0kj1m.cn/Article/details/gt2nwbxcffs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhixingplan.top/Article/details/gt2qocngjyy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fvrhvbkc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ybcxt.top/Article/details/gt2nwwpaypr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guowangkeji.top/Article/details/gt2pyhrokju.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2ekwnowhy.html

O. 并发与异步
来源：http://dali.tanke756.top/Article/details/gt2nwantkep.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2jvlluvmr.html

[O01] 启动一个线程
来源：http://dali.hnqzz.top/Article/details/gt2kwnrdvwh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.haohaochexian.top/Article/details/gt2cxhdxjde.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ypxjbzft.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nwbrower.top/Article/details/gt2hcwjifrx.html

TS:   // 同 JS
来源：http://dali.haohaochexian.top/Article/details/gt2dfwqjhar.html

Java: new Thread(() -> f()).start()
来源：http://dali.sxryk.cn/Article/details/gt2agorsicg.html

Go:   go f()
来源：http://dali.hfpthk.cn/Article/details/gt2vldyxdpk.html

Ruby: Thread.new { f }
来源：http://dali.zycfv.cn/Article/details/gt2xykezjkk.html

C#:   Task.Run(() => F());
来源：http://dali.chenjidiqi.icu/Article/details/gt2njshzpll.html

[O02] 使用线程池
来源：http://dali.chenjidiqi.icu/Article/details/gt2ysnonzls.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tianlin.xyz/Article/details/gt2uizdyzoe.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinqigfzy.top/Article/details/gt2eesnjwph.html

JS:   // worker_threads 线程池
来源：http://dali.jqgfzy.top/Article/details/gt2ztociijh.html

TS:   // worker_threads 线程池
来源：http://dali.nwbrower.top/Article/details/gt2eyakztco.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.kuanghao11.cn/Article/details/gt2jdcytoby.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2meaankhb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhoulong.xyz/Article/details/gt2kowvysyk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yanxiufei.cn/Article/details/gt2asfldpoy.html

[O03] 加锁保护共享数据
来源：http://dali.pengpengdd.cyou/Article/details/gt2bqlvgbil.html

Py:   with lock: shared += 1
来源：http://dali.ybcxt.top/Article/details/gt2ctwztrfd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.meibo888.top/Article/details/gt2fqbzjskc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hysaishi.cn/Article/details/gt2owfzrovd.html

TS:   // 同 JS
来源：http://dali.hammf.cn/Article/details/gt2hdterlyz.html

Java: synchronized (this) { shared++; }
来源：http://dali.cqqwz.cn/Article/details/gt2pjzcytqs.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jlsjyb.cn/Article/details/gt2qimjiqja.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2daafclqp.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhongyouzk.top/Article/details/gt2xozemeyd.html

[O04] 定义异步函数并等待
来源：http://dali.kuanghao11.cn/Article/details/gt2tkbpxshn.html

Py:   async def f():⏎    await g()
来源：http://dali.aizwys.cn/Article/details/gt2eyumaxha.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gzhubu.top/Article/details/gt2amtwmczq.html

JS:   async function f() { await g(); }
来源：http://dali.wangdashe.top/Article/details/gt2xcwpkbgp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xinyue.icu/Article/details/gt2ksqfuert.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.pycfn.com/Article/details/gt2yprpazge.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gzhubu.top/Article/details/gt2ympeucto.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.guannengcc.top/Article/details/gt2vkfodjua.html

C#:   async Task F() { await G(); }
来源：http://dali.cheryme.top/Article/details/gt2xqghhywa.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhixingplan.top/Article/details/gt2aagfcwgp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xxehpqmm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xuetiantiany.cn/Article/details/gt2zfpwwonj.html

JS:   await Promise.all(tasks)
来源：http://dali.yangfankeji.com/Article/details/gt2yrxzlmfc.html

TS:   await Promise.all(tasks)
来源：http://dali.jianghu66.top/Article/details/gt2aphizpzq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.vqdsnc.cn/Article/details/gt2clzempqg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gzhubu.top/Article/details/gt2bbqbubaa.html

Ruby: threads.map(&:join)
来源：http://dali.ybcxt.top/Article/details/gt2miaalltn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hfpthk.cn/Article/details/gt2zcjriulv.html

[O06] 使用进程池
来源：http://dali.bjfxy.top/Article/details/gt2wblgvikp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nanxuanxn.top/Article/details/gt2ljsxttwf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhixingplan.top/Article/details/gt2hzjflulm.html

JS:   // child_process / cluster 模块
来源：http://dali.sweek.top/Article/details/gt2gfmvgdnc.html

TS:   // child_process / cluster 模块
来源：http://dali.jiagoushi.top/Article/details/gt2olplshuo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.wangshuangyany.cn/Article/details/gt2zfnqqyzb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.dashuyun.cn/Article/details/gt2jemzdqky.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2tscxcyae.html

C#:   Parallel.For
来源：http://dali.zhoulong.xyz/Article/details/gt2xtrpphrn.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2hwcwpczu.html

P. 常用工具函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jljowluw.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2adqpgggf.html

[P01] 生成 UUID
来源：http://dali.9152youxi.cn/Article/details/gt2wtxnqruh.html

Py:   str(uuid.uuid4())
来源：http://dali.nanxinkj.top/Article/details/gt2gxclgajm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ivvv.top/Article/details/gt2mlflvvoj.html

JS:   crypto.randomUUID()
来源：http://dali.jqgufenzy.top/Article/details/gt2ezpfijpr.html

TS:   crypto.randomUUID()
来源：http://dali.jiagoushi.top/Article/details/gt2nhqxsyhn.html

Java: UUID.randomUUID().toString()
来源：http://dali.cqqwz.cn/Article/details/gt2ewslaxar.html

Go:   // 用 github.com/google/uuid
来源：http://dali.quarkkingdee.top/Article/details/gt2xvaubmbw.html

Ruby: SecureRandom.uuid
来源：http://dali.c1oappe.top/Article/details/gt2eclihclz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.wangdashe.top/Article/details/gt2qgxxsptp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ivvv.top/Article/details/gt2ypjmdxty.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhixingplan.top/Article/details/gt2kqthjpcc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yanxiufei.cn/Article/details/gt2wucbbudo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hnqzz.top/Article/details/gt2rlysrokp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xylfe.cn/Article/details/gt2puypxdjd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hammf.cn/Article/details/gt2oogybvsq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yongpay.top/Article/details/gt2pqecjxoh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shuidangran.top/Article/details/gt2pzqxqbct.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sufxvd.cn/Article/details/gt2brdzygqh.html

[P03] 生成短随机字符串
来源：http://dali.sweek.top/Article/details/gt2uqjobxoj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zdqjudy.top/Article/details/gt2upgwioya.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.quarkkingdee.top/Article/details/gt2lmjpcokn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenzaomai.com/Article/details/gt2vfdktrzh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hywenlv.cn/Article/details/gt2jieydiod.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cdnleiting.top/Article/details/gt2aiubhiqb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj20258.top/Article/details/gt2chzimkjs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhixingplan.top/Article/details/gt2pfqawcyv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jlsjyb.cn/Article/details/gt2cbgapaok.html

[P04] 求长度
来源：http://dali.hfpthk.cn/Article/details/gt2iotipdxn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hysaishi.cn/Article/details/gt2rrbulokx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gt2uodllkjb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zycfv.cn/Article/details/gt2wiupepce.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dashuyun.cn/Article/details/gt2pgcggbiv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yueranfly.top/Article/details/gt2qkhmwcot.html

Go:   len(arr);  len(m)
来源：http://dali.mhx1999.top/Article/details/gt2jwdadkyl.html

Ruby: x.length;  x.size
来源：http://dali.sxryk.cn/Article/details/gt2vpzupxdp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2udimlkzn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jyoumei.cn/Article/details/gt2ybcohmuy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhengqikj.top/Article/details/gt2irfsdnbn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cashguo.top/Article/details/gt2qettiune.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jqgufenzy.top/Article/details/gt2kwcmirkf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.andypj.xyz/Article/details/gt2dkayhbsr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gogol.net.cn/Article/details/gt2uhmhfmta.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ydzc1.top/Article/details/gt2rhvyfvaz.html

Ruby: a == b
来源：http://dali.nanxinkj.top/Article/details/gt2yjqcrwly.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jlsjyb.cn/Article/details/gt2xzgfvhzm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sweek.top/Article/details/gt2fwlwqgkk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.redwolf501.top/Article/details/gt2lxouvpqp.html

PHP:  if (empty($x)) {}
来源：http://dali.chenzaomai.com/Article/details/gt2ihiyhuqh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gotoacloud.top/Article/details/gt2ftrvzrre.html

TS:   if (x == null) {}
来源：http://dali.hywenlv.cn/Article/details/gt2dtlzniov.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gotoacloud.top/Article/details/gt2ijhggvup.html

Go:   if x == nil {}
来源：http://dali.hammf.cn/Article/details/gt2xykvulsz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mbnylfvu.html

C#:   if (x is null) {}
来源：http://dali.yuanzhike.top/Article/details/gt2gqfzratu.html

[P07] 防抖与节流
来源：http://dali.yj20258888.top/Article/details/gt2zqmblrqz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jiagoushi.top/Article/details/gt2uxorwdau.html

PHP:  // 手写时间戳比较
来源：http://dali.aizwys.cn/Article/details/gt2vfnhaydl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cashguo.top/Article/details/gt2ettfzoyq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gt2xqqulqob.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.daria6918.cn/Article/details/gt2iakjrscz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.smart0.xyz/Article/details/gt2shxtiuoh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinqigfzy.top/Article/details/gt2bgsodkml.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sweek.top/Article/details/gt2zeyolmbk.html

[P08] 处理浮点精度问题
来源：http://dali.gzhubu.top/Article/details/gt2cnlzebul.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.svipenyu.cn/Article/details/gt2fynfvosu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yueranfly.top/Article/details/gt2csdetmsc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.snrcjt.cn/Article/details/gt2xebzweip.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.birdmap.top/Article/details/gt2nkthfjqa.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfeftig.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuanzhike.top/Article/details/gt2ylenwonx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hfpthk.cn/Article/details/gt2raufjzkt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tian-w.cn/Article/details/gt2fudygxol.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2xnmnbawc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigufen.top/Article/details/gt2rrlrdfbk.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ndoyhlal.html

[Q01] 创建表
来源：http://dali.yueranfly.top/Article/details/gt2uynhqnhd.html

CREATE TABLE users (
来源：http://dali.zhengqikj.top/Article/details/gt2pnqunoup.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hfpthk.cn/Article/details/gt2sfzmtgwh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hammf.cn/Article/details/gt2sroebqqr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.daxiang520.top/Article/details/gt2oylqsesc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gaohongyu789.top/Article/details/gt2boyqktve.html

);
来源：http://dali.bjfxy.top/Article/details/gt2qocutslb.html

[Q02] 创建带外键的表
来源：http://dali.gogol.net.cn/Article/details/gt2fimtkjgl.html

CREATE TABLE orders (
来源：http://dali.zhixingplan.top/Article/details/gt2xrhvktuj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenjidiqi.icu/Article/details/gt2zqpugomy.html

user_id INT NOT NULL,
来源：http://dali.gogol.net.cn/Article/details/gt2oohfojhz.html

amount DECIMAL(10, 2),
来源：http://dali.fengsongda.top/Article/details/gt2onsfzckd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.havefunace.top/Article/details/gt2zgzqdxny.html

);
来源：http://dali.cucudq.cn/Article/details/gt2mivmpail.html

[Q03] 增加列
来源：http://dali.nwbrower.top/Article/details/gt2qlyfaufc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nanxuanxn.top/Article/details/gt2cugjytii.html

[Q04] 修改列类型
来源：http://dali.zhengqikj.top/Article/details/gt2rylsuwog.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gzhubu.top/Article/details/gt2rbqvmjhr.html

[Q05] 重命名列
来源：http://dali.jqgufenzy.top/Article/details/gt2brqsgvbj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sxryk.cn/Article/details/gt2azjqwryq.html

[Q06] 删除列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2enkgbehc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.quarkkingdee.top/Article/details/gt2zzgosbeh.html

[Q07] 删除表
来源：http://dali.hysaishi.cn/Article/details/gt2zmbcxwlk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj202588.top/Article/details/gt2jldwfkbe.html

[Q08] 创建普通索引
来源：http://dali.cqqwz.cn/Article/details/gt2alwvyazd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.vqdsnc.cn/Article/details/gt2mzhszrcu.html

[Q09] 创建唯一索引
来源：http://dali.hnqzz.top/Article/details/gt2cgzprxds.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jqgufenzy.top/Article/details/gt2wzfztdpj.html

[Q10] 插入单行
来源：http://dali.zhongyouzk.top/Article/details/gt2inafebim.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vvaqkayv.html

[Q11] 一次插入多行
来源：http://dali.tanke756.top/Article/details/gt2xvejlxty.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gt2onhpqsaw.html

[Q12] 插入后取自增 ID
来源：http://dali.iojbl.cn/Article/details/gt2jxnzjapw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yuanzhike.top/Article/details/gt2tlwnoxkx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sysykeji.top/Article/details/gt2xcrgitzm.html

[Q13] 忽略重复插入
来源：http://dali.hammf.cn/Article/details/gt2lkgiojmf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gotoacloud.top/Article/details/gt2nztxttnn.html

[Q14] 存在则更新（upsert）
来源：http://dali.daria6918.cn/Article/details/gt2busublet.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ppjwa.cn/Article/details/gt2gfkhuiwv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.smart0.xyz/Article/details/gt2dkmvlwjq.html

[Q15] 查询全部
来源：http://dali.xinyue.icu/Article/details/gt2ykufgfmv.html

SELECT * FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2cklyaljg.html

[Q16] 查询指定列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ixyimkjj.html

SELECT id, name FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2iaqdobpo.html

[Q17] 条件查询
来源：http://dali.yj202588.top/Article/details/gt2vlrspyhs.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj20258.top/Article/details/gt2scphlkyl.html

[Q18] 模糊匹配
来源：http://dali.nwbrower.top/Article/details/gt2clrvtjvu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.c1oappe.top/Article/details/gt2pdbopqkr.html

[Q19] 范围查询
来源：http://dali.yvedp.cn/Article/details/gt2afqmqped.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhixingplan.top/Article/details/gt2mdtrsvhl.html

[Q20] IN 列表
来源：http://dali.cucudq.cn/Article/details/gt2ddjycqkh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhoulong.xyz/Article/details/gt2vvdsoidh.html

[Q21] 空值判断
来源：http://dali.0kj1m.cn/Article/details/gt2dafhjluw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ybcxt.top/Article/details/gt2wklyyiif.html

[Q22] 排序
来源：http://dali.ppjwa.cn/Article/details/gt2cdwxxmdq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yangfankeji.com/Article/details/gt2cabghmpz.html

[Q23] 分页
来源：http://dali.daxiang520.top/Article/details/gt2waasudrs.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.fzhhl.top/Article/details/gt2mhawnkbn.html

[Q24] 去重
来源：http://dali.quarkkingdee.top/Article/details/gt2luiwtdot.html

SELECT DISTINCT city FROM users;
来源：http://dali.tanke756.top/Article/details/gt2dbkxdyul.html

[Q25] 只取前 N 条
来源：http://dali.aizwys.cn/Article/details/gt2kyogouin.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yuanzhike.top/Article/details/gt2pwixewnf.html

[Q26] 计数
来源：http://dali.smart0.xyz/Article/details/gt2hdwjqnzd.html

SELECT COUNT(*) FROM users;
来源：http://dali.tanke756.top/Article/details/gt2ndcmnshr.html

[Q27] 条件计数
来源：http://dali.nanxinkj.top/Article/details/gt2ahbumrei.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2ehfqrvsc.html

[Q28] 求和与平均
来源：http://dali.sxryk.cn/Article/details/gt2uojpyzkv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rpalkpbq.html

[Q29] 最大最小值
来源：http://dali.hongshengwenyu.top/Article/details/gt2rklzklrp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2taxrpwmt.html

[Q30] 分组统计
来源：http://dali.daria6918.cn/Article/details/gt2cczhhwas.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jyoumei.cn/Article/details/gt2kxbvcitv.html

[Q31] 分组后过滤
来源：http://dali.zhiwuduotai.top/Article/details/gt2frrymmra.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cqqwz.cn/Article/details/gt2tybjtsia.html

[Q32] 分组拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2roefqubm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gt2icgxorzq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hfpthk.cn/Article/details/gt2dvcskoty.html

[Q33] 多列分组
来源：http://dali.sxryk.cn/Article/details/gt2qzkuaeug.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinqigfzy.top/Article/details/gt2jjhvlmde.html

[Q34] 每组取第一条
来源：http://dali.quarkkingdee.top/Article/details/gt2thbvkugt.html

SELECT * FROM (
来源：http://dali.shuidangran.top/Article/details/gt2iumuhdfk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.dianchejie.cn/Article/details/gt2xvtwhqxx.html

) t WHERE rn = 1;
来源：http://dali.ehwqpu.com/Article/details/gt2ifecptlj.html

[Q35] 内连接
来源：http://dali.fengsongda.top/Article/details/gt2paljcpia.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mgpkgzsy.html

[Q36] 左连接
来源：http://dali.zhengqikj.top/Article/details/gt2fqmzatvv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gt2dagvzqfm.html

[Q37] 右连接
来源：http://dali.jqgfzy.top/Article/details/gt2uaozcord.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ivvv.top/Article/details/gt2fujrqbux.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cqqwz.cn/Article/details/gt2uzdbvygf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.feifeiyinyue.top/Article/details/gt2nqbdxxyu.html

[Q39] 自连接（查上下级）
来源：http://dali.daxiang520.top/Article/details/gt2qmftdcwk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cqqwz.cn/Article/details/gt2xicbegly.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.pengpengdd.cyou/Article/details/gt2arzlcxph.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.dianchejie.cn/Article/details/gt2vslofboe.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yvedp.cn/Article/details/gt2apydsrmd.html

[Q41] 多表连接
来源：http://dali.sysykeji.top/Article/details/gt2smdbinec.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.daxiang520.top/Article/details/gt2oaxsmuvs.html

JOIN users u ON u.id = o.user_id
来源：http://dali.meibo888.top/Article/details/gt2wjoiiezj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhiwuduotai.top/Article/details/gt2dowihypu.html

[Q42] 连接条件附加过滤
来源：http://dali.yj20258888.top/Article/details/gt2yhjpaksn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yonumen.top/Article/details/gt2prmvzgka.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sxryk.cn/Article/details/gt2xcakjjwc.html

[Q43] 标量子查询
来源：http://dali.9152youxi.cn/Article/details/gt2bvaxkfqw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sufxvd.cn/Article/details/gt2zwglgezi.html

[Q44] IN 子查询
来源：http://dali.havefunace.top/Article/details/gt2osxykakd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.aibaodan.cn/Article/details/gt2iqolsifm.html

[Q45] EXISTS 判断存在
来源：http://dali.yuxming.cn/Article/details/gt2zgkmdjoq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxinkj.top/Article/details/gt2anndyure.html


<!-- 参考信息 -->