代发 wailian999

JS:   s === [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gt2anigshef.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gt2kvidurwk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tqkhuadv.html

Go:   // 双指针从两端比较
来源：http://dali.wangdashe.top/Article/details/gt2pyihhian.html

Ruby: s == s.reverse
来源：http://dali.xylfe.cn/Article/details/gt2pripcaur.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bfhmbuqu.html

[N07] 两数之和（返回下标）
来源：http://dali.xinyue.icu/Article/details/gt2ehaswpct.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cdnleiting.top/Article/details/gt2znnsjkvf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2appkzlkd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj20258888.top/Article/details/gt2jndinqkb.html

TS:   // 手写 Map<string, number>
来源：http://dali.dashuyun.cn/Article/details/gt2bbqkactu.html

Java: // 手写 HashMap
来源：http://dali.zhixingplan.top/Article/details/gt2npgodyvh.html

Go:   // 手写 map[int]int
来源：http://dali.gzhubu.top/Article/details/gt2zgbswklz.html

Ruby: // 手写 Hash
来源：http://dali.hongshengwenyu.top/Article/details/gt2khjthtqs.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ydzc1.top/Article/details/gt2vnhqrpyl.html

[N08] 生成全排列
来源：http://dali.sysykeji.top/Article/details/gt2nyznfhuk.html

Py:   itertools.permutations(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2ylzedwci.html

PHP:  // 手写递归交换
来源：http://dali.jinqigfzy.top/Article/details/gt2foipmnod.html

JS:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gt2kdhibakc.html

TS:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nfawjthq.html

Java: // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gt2evlppoga.html

Go:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2anogzvos.html

Ruby: arr.permutation.to_a
来源：http://dali.svipenyu.cn/Article/details/gt2gphfwhrx.html

C#:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2lvzextdu.html

[N09] 栈与队列
来源：http://dali.wangdashe.top/Article/details/gt2djudskdk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2pmwssgnu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yj202588.top/Article/details/gt2hgqzjbtv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2hwvrncnb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tian-w.cn/Article/details/gt2fuvixgpr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.svipenyu.cn/Article/details/gt2ppesaccx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenlongwang.top/Article/details/gt2ztyhixoe.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jianghu66.top/Article/details/gt2xybhbkbz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nwbrower.top/Article/details/gt2zteucajj.html

[N10] 链表节点定义
来源：http://dali.quarkkingdee.top/Article/details/gt2xtgdotpu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ppjwa.cn/Article/details/gt2fauchcge.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ybcxt.top/Article/details/gt2xayutihx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.daria6918.cn/Article/details/gt2fpuehtwy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.fengsongda.top/Article/details/gt2ykkftsju.html

Java: class Node { int v; Node next; }
来源：http://dali.9152youxi.cn/Article/details/gt2mevlldgc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hammf.cn/Article/details/gt2dowvueml.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xinyue.icu/Article/details/gt2pikrivwg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tian-w.cn/Article/details/gt2dkbblkhi.html

[N11] 二叉树中序遍历
来源：http://dali.yueranfly.top/Article/details/gt2wnqchgvj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj20258888.top/Article/details/gt2qsenbuli.html

PHP:  // 手写递归函数
来源：http://dali.haohaochexian.top/Article/details/gt2kuzrtcye.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cheryme.top/Article/details/gt2vzicozlg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxinkj.top/Article/details/gt2fejehnru.html

Java: // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gt2yzrymaft.html

Go:   // 手写递归
来源：http://dali.yonumen.top/Article/details/gt2qsdmwvbq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.guannengcc.top/Article/details/gt2ejqaydcb.html

C#:   // 手写递归
来源：http://dali.fengsongda.top/Article/details/gt2gwueyrwz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tianlin.xyz/Article/details/gt2ghpvikhn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gogol.net.cn/Article/details/gt2fpsdxluu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.daria6918.cn/Article/details/gt2anvncgpf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cqqwz.cn/Article/details/gt2zoezrnax.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gt2pfyuhtcm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cucudq.cn/Article/details/gt2rgeaqtda.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.wangshuangyany.cn/Article/details/gt2rfdfnnja.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.guannengcc.top/Article/details/gt2sngxnesx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenjidiqi.icu/Article/details/gt2ybyekvku.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2vtdgxmdj.html

O. 并发与异步
来源：http://dali.yueranfly.top/Article/details/gt2zdjtxvux.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2zxootgyw.html

[O01] 启动一个线程
来源：http://dali.guannengcc.top/Article/details/gt2qziydqmb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tanke756.top/Article/details/gt2qaujzqjf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nanxinkj.top/Article/details/gt2xwbqaahd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zdqjudy.top/Article/details/gt2wdoaavbn.html

TS:   // 同 JS
来源：http://dali.shuidangran.top/Article/details/gt2hpuasrer.html

Java: new Thread(() -> f()).start()
来源：http://dali.jiagoushi.top/Article/details/gt2omweikrt.html

Go:   go f()
来源：http://dali.yuxming.cn/Article/details/gt2sqwtlcii.html

Ruby: Thread.new { f }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vpavkgkb.html

C#:   Task.Run(() => F());
来源：http://dali.chenjidiqi.icu/Article/details/gt2sogefqjt.html

[O02] 使用线程池
来源：http://dali.gogol.net.cn/Article/details/gt2dhsnfhzr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.dianchejie.cn/Article/details/gt2uymiywzl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.tianlin.xyz/Article/details/gt2defltqnj.html

JS:   // worker_threads 线程池
来源：http://dali.pycfn.com/Article/details/gt2teitgqyd.html

TS:   // worker_threads 线程池
来源：http://dali.pengpengdd.cyou/Article/details/gt2gdfbvfff.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.svipenyu.cn/Article/details/gt2abefsabl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ogcuzoaq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.aizwys.cn/Article/details/gt2xuzfogzt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yuxming.cn/Article/details/gt2yrihnnob.html

[O03] 加锁保护共享数据
来源：http://dali.xuetiantiany.cn/Article/details/gt2dbfotuxc.html

Py:   with lock: shared += 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gqvyqmrn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yuxming.cn/Article/details/gt2lnnkwkpm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.mhx1999.top/Article/details/gt2lhmuitai.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gt2aphumloo.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ivzfxezy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.redwolf501.top/Article/details/gt2cyrevjni.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xinyue.icu/Article/details/gt2sykukjmy.html

C#:   lock (gate) { shared++; }
来源：http://dali.sweek.top/Article/details/gt2fqlgytdt.html

[O04] 定义异步函数并等待
来源：http://dali.bjfxy.top/Article/details/gt2yqnsivqx.html

Py:   async def f():⏎    await g()
来源：http://dali.hongshengwenyu.top/Article/details/gt2rjsxbhuc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yuxming.cn/Article/details/gt2rayvvfhm.html

JS:   async function f() { await g(); }
来源：http://dali.haohaochexian.top/Article/details/gt2lcfpjkwa.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2swearpmz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ehwqpu.com/Article/details/gt2yjhoslgz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.wangshuangyany.cn/Article/details/gt2yfhaynft.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.316326.xyz/Article/details/gt2qflwvjjz.html

C#:   async Task F() { await G(); }
来源：http://dali.redwolf501.top/Article/details/gt2nrryphhm.html

[O05] 并发执行并等待全部完成
来源：http://dali.sweek.top/Article/details/gt2lzhcknmv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.birdmap.top/Article/details/gt2yqwmgxqi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhoulong.xyz/Article/details/gt2ehhgazte.html

JS:   await Promise.all(tasks)
来源：http://dali.ehwqpu.com/Article/details/gt2utexnytd.html

TS:   await Promise.all(tasks)
来源：http://dali.smart0.xyz/Article/details/gt2tcmmlrdq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ledmgieu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jqgfzy.top/Article/details/gt2plwjepep.html

Ruby: threads.map(&:join)
来源：http://dali.jiagoushi.top/Article/details/gt2fvcnelbm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ppjwa.cn/Article/details/gt2uxuqxivt.html

[O06] 使用进程池
来源：http://dali.snrcjt.cn/Article/details/gt2zmyzpvlo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.birdmap.top/Article/details/gt2wedsoeqr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.dianchejie.cn/Article/details/gt2icfxukkl.html

JS:   // child_process / cluster 模块
来源：http://dali.nanxinkj.top/Article/details/gt2umcopzrj.html

TS:   // child_process / cluster 模块
来源：http://dali.ehwqpu.com/Article/details/gt2kzoaftbw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinqigufen.top/Article/details/gt2dinuqxbo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.meibo888.top/Article/details/gt2ckuidpnw.html

Ruby: // fork 块
来源：http://dali.cheryme.top/Article/details/gt2ccgmuxsp.html

C#:   Parallel.For
来源：http://dali.nanxuanxn.top/Article/details/gt2rbubnddr.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2bqpovdpu.html

P. 常用工具函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wvgjqyvx.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2jobtaqgz.html

[P01] 生成 UUID
来源：http://dali.hysaishi.cn/Article/details/gt2uredmxdq.html

Py:   str(uuid.uuid4())
来源：http://dali.hysaishi.cn/Article/details/gt2pfnpktox.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yvedp.cn/Article/details/gt2wranfbcf.html

JS:   crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gt2ctejlwpd.html

TS:   crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gt2nknvwruk.html

Java: UUID.randomUUID().toString()
来源：http://dali.zdqjudy.top/Article/details/gt2qtclzbks.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nwbrower.top/Article/details/gt2oowmgblb.html

Ruby: SecureRandom.uuid
来源：http://dali.wangdashe.top/Article/details/gt2mqatwhmu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.316326.xyz/Article/details/gt2guqqeqvc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jianghu66.top/Article/details/gt2zwcdqwao.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenzaomai.com/Article/details/gt2imzjenfg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.andypj.xyz/Article/details/gt2omnrpuvn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.svipenyu.cn/Article/details/gt2qyiexqzk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ubekzeei.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenzaomai.com/Article/details/gt2ptbvtlcr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jvozczjm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2ijgprrnx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenzaomai.com/Article/details/gt2ipjzcrxx.html

[P03] 生成短随机字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2urrryhuz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhiwuduotai.top/Article/details/gt2acjuuika.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ehwqpu.com/Article/details/gt2jecxcege.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2dkpcpdnq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cashguo.top/Article/details/gt2gwhfzvkj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2loxpindi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.0kj1m.cn/Article/details/gt2lqchkxvv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.snrcjt.cn/Article/details/gt2kiyvmpja.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tianlin.xyz/Article/details/gt2pqgqpexj.html

[P04] 求长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cucxjcau.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuxming.cn/Article/details/gt2qfsoixnv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pcwmsqjh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cashguo.top/Article/details/gt2xvygyoiw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.vqdsnc.cn/Article/details/gt2ocnmilzq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sweek.top/Article/details/gt2agxlrpim.html

Go:   len(arr);  len(m)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xeaktcio.html

Ruby: x.length;  x.size
来源：http://dali.jyoumei.cn/Article/details/gt2esbehgfk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kxhpcjme.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhengqikj.top/Article/details/gt2zhhvhmwo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.smart0.xyz/Article/details/gt2jjrtlbnv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nanxuanxn.top/Article/details/gt2xjnbwcdg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenlongwang.top/Article/details/gt2dmxrnujj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cucudq.cn/Article/details/gt2dfoljswm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cheryme.top/Article/details/gt2otrlflrj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gt2hevgfwrc.html

Ruby: a == b
来源：http://dali.tian-w.cn/Article/details/gt2pfoaejjb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.daxiang520.top/Article/details/gt2zpsavveo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinqigufen.top/Article/details/gt2jgpqrefz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.redwolf501.top/Article/details/gt2jsqcodvg.html

PHP:  if (empty($x)) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2btlwmbig.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gaohongyu789.top/Article/details/gt2tthgcsai.html

TS:   if (x == null) {}
来源：http://dali.yuxming.cn/Article/details/gt2pcbsprkt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.dianchejie.cn/Article/details/gt2vgozrvcu.html

Go:   if x == nil {}
来源：http://dali.guannengcc.top/Article/details/gt2sqrjvmeh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wfxvcdys.html

C#:   if (x is null) {}
来源：http://dali.tian-w.cn/Article/details/gt2nzevcxhp.html

[P07] 防抖与节流
来源：http://dali.smart0.xyz/Article/details/gt2nbdduylf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.wangshuangyany.cn/Article/details/gt2ssigvrqh.html

PHP:  // 手写时间戳比较
来源：http://dali.mhx1999.top/Article/details/gt2ntpwtfqe.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gt2mnzkffdx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gt2wwborxus.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jyoumei.cn/Article/details/gt2vvcejgcy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2jyypszia.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yvedp.cn/Article/details/gt2hwkhtzid.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.quarkkingdee.top/Article/details/gt2tcmecydi.html

[P08] 处理浮点精度问题
来源：http://dali.wangshuangyany.cn/Article/details/gt2mybbtwml.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tianlin.xyz/Article/details/gt2pfoskglj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj202588.top/Article/details/gt2sewpiccv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gogol.net.cn/Article/details/gt2cjcqxnoc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.smart0.xyz/Article/details/gt2khkvxgik.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenjidiqi.icu/Article/details/gt2qvyhswmz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hongshengwenyu.top/Article/details/gt2auoattrr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.fzhhl.top/Article/details/gt2idwrvjgq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xylfe.cn/Article/details/gt2tuzsnafe.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2havwjmaw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj20258.top/Article/details/gt2ebdaoezt.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2bezismni.html

[Q01] 创建表
来源：http://dali.nanxinkj.top/Article/details/gt2blgeweac.html

CREATE TABLE users (
来源：http://dali.wangshuangyany.cn/Article/details/gt2tgotaiay.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xziqi.cn/Article/details/gt2hgwhlfet.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hnqzz.top/Article/details/gt2kzxiqhce.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ivvv.top/Article/details/gt2afparduu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gzhubu.top/Article/details/gt2kzfysjfq.html

);
来源：http://dali.0kj1m.cn/Article/details/gt2fqxvmfws.html

[Q02] 创建带外键的表
来源：http://dali.kuanghao11.cn/Article/details/gt2wfytpthj.html

CREATE TABLE orders (
来源：http://dali.guowangkeji.top/Article/details/gt2teexrebh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gzhubu.top/Article/details/gt2fxbcbqqi.html

user_id INT NOT NULL,
来源：http://dali.xinyue.icu/Article/details/gt2cxmgndep.html

amount DECIMAL(10, 2),
来源：http://dali.zycfv.cn/Article/details/gt2ursqhwzd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.fzhhl.top/Article/details/gt2rwvdgufs.html

);
来源：http://dali.chenjidiqi.icu/Article/details/gt2pqfwuliw.html

[Q03] 增加列
来源：http://dali.jinqigfzy.top/Article/details/gt2bzdddclf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.tian-w.cn/Article/details/gt2rlzatoic.html

[Q04] 修改列类型
来源：http://dali.vqdsnc.cn/Article/details/gt2oeskrfnn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.daria6918.cn/Article/details/gt2yxnyiinv.html

[Q05] 重命名列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2filnoxzq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhixingplan.top/Article/details/gt2vjbgnnjy.html

[Q06] 删除列
来源：http://dali.shzxlz.cn/Article/details/gt2ecvzaxzf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jqgfzy.top/Article/details/gt2pfuvinih.html

[Q07] 删除表
来源：http://dali.ivvv.top/Article/details/gt2mjjmjgit.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hammf.cn/Article/details/gt2wifgcjkd.html

[Q08] 创建普通索引
来源：http://dali.316326.xyz/Article/details/gt2uumxcepw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cheryme.top/Article/details/gt2uuyqekqz.html

[Q09] 创建唯一索引
来源：http://dali.yj202588.top/Article/details/gt2dflpxycy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jianghu66.top/Article/details/gt2jcrloojp.html

[Q10] 插入单行
来源：http://dali.fengsongda.top/Article/details/gt2brxbfrnn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cashguo.top/Article/details/gt2vxzxtnqz.html

[Q11] 一次插入多行
来源：http://dali.yj202588.top/Article/details/gt2zthpjaxl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gt2veetcwds.html

[Q12] 插入后取自增 ID
来源：http://dali.shuidangran.top/Article/details/gt2nhhpubjr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinqigufen.top/Article/details/gt2bwewebar.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cashguo.top/Article/details/gt2zhgqarlo.html

[Q13] 忽略重复插入
来源：http://dali.jyoumei.cn/Article/details/gt2mbpzbbey.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.snrcjt.cn/Article/details/gt2nrtvegln.html

[Q14] 存在则更新（upsert）
来源：http://dali.nanxinkj.top/Article/details/gt2zfapvhyu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.guowangkeji.top/Article/details/gt2trfaaqis.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gzhubu.top/Article/details/gt2fcppcugv.html

[Q15] 查询全部
来源：http://dali.jyoumei.cn/Article/details/gt2agpcicdj.html

SELECT * FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2idookmth.html

[Q16] 查询指定列
来源：http://dali.tian-w.cn/Article/details/gt2ymicfpqj.html

SELECT id, name FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2srhziimy.html

[Q17] 条件查询
来源：http://dali.zhixingplan.top/Article/details/gt2rqlmpync.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2myxuxijq.html

[Q18] 模糊匹配
来源：http://dali.ydzc1.top/Article/details/gt2zjwzpkkt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jqgfzy.top/Article/details/gt2ktyzygqg.html

[Q19] 范围查询
来源：http://dali.wangdashe.top/Article/details/gt2oerltqui.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yonumen.top/Article/details/gt2jnviaozc.html

[Q20] IN 列表
来源：http://dali.zhiwuduotai.top/Article/details/gt2htrzovrb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qdmhojob.html

[Q21] 空值判断
来源：http://dali.hfpthk.cn/Article/details/gt2vrhrkvgh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.pycfn.com/Article/details/gt2ttpuklgc.html

[Q22] 排序
来源：http://dali.pengpengdd.cyou/Article/details/gt2bhagqsiu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ysybyxbn.html

[Q23] 分页
来源：http://dali.yuanzhike.top/Article/details/gt2vexbfwnt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.daria6918.cn/Article/details/gt2alembmib.html

[Q24] 去重
来源：http://dali.sufxvd.cn/Article/details/gt2rqojfiyg.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dyrcjcmc.html

[Q25] 只取前 N 条
来源：http://dali.ivvv.top/Article/details/gt2dxqpvzmw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2thohdizk.html

[Q26] 计数
来源：http://dali.xinyue.icu/Article/details/gt2gwrhmkva.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2beqpxxnk.html

[Q27] 条件计数
来源：http://dali.tianlin.xyz/Article/details/gt2mmffjwnm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sweek.top/Article/details/gt2zjgvqajy.html

[Q28] 求和与平均
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yfzpyvug.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gt2bgbxapta.html

[Q29] 最大最小值
来源：http://dali.cqqwz.cn/Article/details/gt2qmzaneuq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2fdrxgtyj.html

[Q30] 分组统计
来源：http://dali.jyoumei.cn/Article/details/gt2aigvowkv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gt2jzxowpnb.html

[Q31] 分组后过滤
来源：http://dali.zycfv.cn/Article/details/gt2pkxnurgm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hfpthk.cn/Article/details/gt2oerolidc.html

[Q32] 分组拼接字符串
来源：http://dali.bjfxy.top/Article/details/gt2jmzgtewo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gt2euaurwoe.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.mhx1999.top/Article/details/gt2nkafugpe.html

[Q33] 多列分组
来源：http://dali.havefunace.top/Article/details/gt2ftaoowlt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hnqzz.top/Article/details/gt2yzjlnlwk.html

[Q34] 每组取第一条
来源：http://dali.hnqzz.top/Article/details/gt2xilgpzaw.html

SELECT * FROM (
来源：http://dali.dashuyun.cn/Article/details/gt2geylguzx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cdnleiting.top/Article/details/gt2wqkwmhsl.html

) t WHERE rn = 1;
来源：http://dali.yongpay.top/Article/details/gt2ygfadklv.html

[Q35] 内连接
来源：http://dali.hfpthk.cn/Article/details/gt2xzxtmqzi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenlongwang.top/Article/details/gt2xaclopqy.html

[Q36] 左连接
来源：http://dali.xuetiantiany.cn/Article/details/gt2nympznik.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xinyue.icu/Article/details/gt2qzhbqdob.html

[Q37] 右连接
来源：http://dali.feifeiyinyue.top/Article/details/gt2qmgqvbep.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tianlin.xyz/Article/details/gt2ybskurza.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhoulong.xyz/Article/details/gt2mhdpluys.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cheryme.top/Article/details/gt2qmibqfzm.html

[Q39] 自连接（查上下级）
来源：http://dali.ydzc1.top/Article/details/gt2ptijclss.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zdqjudy.top/Article/details/gt2pcdgwpup.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhiwuduotai.top/Article/details/gt2swllmneo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.daxiang520.top/Article/details/gt2xkcrumbs.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.gogol.net.cn/Article/details/gt2kmcmerbu.html

[Q41] 多表连接
来源：http://dali.aibaodan.cn/Article/details/gt2zceyigwd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nanxinkj.top/Article/details/gt2zdupoqti.html

JOIN users u ON u.id = o.user_id
来源：http://dali.meibo888.top/Article/details/gt2bncspoqd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yangfankeji.com/Article/details/gt2yumrqccc.html

[Q42] 连接条件附加过滤
来源：http://dali.jiagoushi.top/Article/details/gt2szpvsdpk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinqigufen.top/Article/details/gt2pkesgdfd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.dashuyun.cn/Article/details/gt2lebelrqv.html

[Q43] 标量子查询
来源：http://dali.haohaochexian.top/Article/details/gt2pznlbyhb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ydzc1.top/Article/details/gt2kmqhfvln.html


<!-- 参考信息 -->