代发 wailian999

Ruby: s == s.reverse
来源：http://dali.0kj1m.cn/Article/details/gttqukaxdc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tianlin.xyz/Article/details/gtgimiceul.html

[N07] 两数之和（返回下标）
来源：http://dali.birdmap.top/Article/details/gtwyyjwdpo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hfpthk.cn/Article/details/gtckvzfkgo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hnqzz.top/Article/details/gturljfojc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.redwolf501.top/Article/details/gtoormkptw.html

TS:   // 手写 Map<string, number>
来源：http://dali.jyoumei.cn/Article/details/gtpvadpaiw.html

Java: // 手写 HashMap
来源：http://dali.hfpthk.cn/Article/details/gtawaimnib.html

Go:   // 手写 map[int]int
来源：http://dali.nanxinkj.top/Article/details/gtyijbbetv.html

Ruby: // 手写 Hash
来源：http://dali.zhoulong.xyz/Article/details/gthbvrqbfc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuanzx.com/Article/details/gttcqfzchq.html

[N08] 生成全排列
来源：http://dali.tanke756.top/Article/details/gtikyfooma.html

Py:   itertools.permutations(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtfqtvbqex.html

PHP:  // 手写递归交换
来源：http://dali.shanyushiyangtech.top/Article/details/gtsomfzvqw.html

JS:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtiblldxae.html

TS:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtbrdturit.html

Java: // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtwjsxjeau.html

Go:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gtnisozrpr.html

Ruby: arr.permutation.to_a
来源：http://dali.daria6918.cn/Article/details/gtrdilpzxi.html

C#:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtucftavnn.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gtcxthpyas.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gtfovpojvf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gtuhymffmu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gtqyticskt.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.aibaodan.cn/Article/details/gtpkudyrmi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nanxuanxn.top/Article/details/gtvvuywlox.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.daxiang520.top/Article/details/gtgbxdsqnu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvonqddj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqtymspg.html

[N10] 链表节点定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxyhgnwe.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hywenlv.cn/Article/details/gtapeexbtf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shzxlz.cn/Article/details/gthysashaz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jlsjyb.cn/Article/details/gtxntktsaj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenlongwang.top/Article/details/gtqydwuior.html

Java: class Node { int v; Node next; }
来源：http://dali.316326.xyz/Article/details/gtizaowoqh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.316326.xyz/Article/details/gtziuplsno.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.andypj.xyz/Article/details/gtqqhusasl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhixingplan.top/Article/details/gtkygenkhi.html

[N11] 二叉树中序遍历
来源：http://dali.svipenyu.cn/Article/details/gtbxyumzhx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjfhxtasg.html

PHP:  // 手写递归函数
来源：http://dali.hfpthk.cn/Article/details/gtfndvdzdz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtatucjr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxuanxn.top/Article/details/gtbnkgdjxm.html

Java: // 手写递归
来源：http://dali.cashguo.top/Article/details/gtxahqtper.html

Go:   // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gtkdpucnot.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yongpay.top/Article/details/gtbhuhmpci.html

C#:   // 手写递归
来源：http://dali.bjfxy.top/Article/details/gtgwegxwpr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xylfe.cn/Article/details/gtrituwwev.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkhiolany.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfuytwpe.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cdnleiting.top/Article/details/gtmihtmozd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuanzhike.top/Article/details/gtagueuqsn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nwbrower.top/Article/details/gticyrbyyw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gzhubu.top/Article/details/gthdueqdam.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj20258.top/Article/details/gtvavsjksa.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxueluvo.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtjuwkstjv.html

O. 并发与异步
来源：http://dali.aibaodan.cn/Article/details/gtdzopaksm.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtbqpmsahw.html

[O01] 启动一个线程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsaygtegx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.pycfn.com/Article/details/gtecdlvzmg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenlongwang.top/Article/details/gtpamhunnv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinqigufen.top/Article/details/gtlftiauaq.html

TS:   // 同 JS
来源：http://dali.xziqi.cn/Article/details/gtyctnusfs.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbyqxbhb.html

Go:   go f()
来源：http://dali.cheryme.top/Article/details/gtxykzedsx.html

Ruby: Thread.new { f }
来源：http://dali.shangyingyoupin.top/Article/details/gtefxaprjd.html

C#:   Task.Run(() => F());
来源：http://dali.316326.xyz/Article/details/gtxmsxbdbv.html

[O02] 使用线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjfiuyvoh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.dashuyun.cn/Article/details/gtopapcqxu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yvedp.cn/Article/details/gtbfkdxnyw.html

JS:   // worker_threads 线程池
来源：http://dali.havefunace.top/Article/details/gtczwwlxpx.html

TS:   // worker_threads 线程池
来源：http://dali.zdqjudy.top/Article/details/gtsmyilhmc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yangfankeji.com/Article/details/gtjszmtnpg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhengqikj.top/Article/details/gtsmkvwenk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yueranfly.top/Article/details/gtasohxauj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hysaishi.cn/Article/details/gthtrrfqce.html

[O03] 加锁保护共享数据
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihsydomg.html

Py:   with lock: shared += 1
来源：http://dali.sysykeji.top/Article/details/gtmjrwtkka.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zdqjudy.top/Article/details/gtdjbqjqns.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.guowangkeji.top/Article/details/gtrvxelkua.html

TS:   // 同 JS
来源：http://dali.yj20258.top/Article/details/gtdukbnxsi.html

Java: synchronized (this) { shared++; }
来源：http://dali.redwolf501.top/Article/details/gtymavbuuv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ivvv.top/Article/details/gtzlmoatah.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.pycfn.com/Article/details/gtntthfkyy.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj20258888.top/Article/details/gtxnxlppwo.html

[O04] 定义异步函数并等待
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjtqrjmmb.html

Py:   async def f():⏎    await g()
来源：http://dali.snrcjt.cn/Article/details/gtgzdqtoqj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhixingplan.top/Article/details/gtezxgwzil.html

JS:   async function f() { await g(); }
来源：http://dali.yueranfly.top/Article/details/gtvnymvrjy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.0kj1m.cn/Article/details/gtpexotknx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.snrcjt.cn/Article/details/gtesifdtbx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cucudq.cn/Article/details/gtkaonelcp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.redwolf501.top/Article/details/gtoyhklgsh.html

C#:   async Task F() { await G(); }
来源：http://dali.bjfxy.top/Article/details/gtveyhxylk.html

[O05] 并发执行并等待全部完成
来源：http://dali.cdnleiting.top/Article/details/gtsrtfdioy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.redwolf501.top/Article/details/gtxdzurtsl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yongpay.top/Article/details/gtiqwputpo.html

JS:   await Promise.all(tasks)
来源：http://dali.cheryme.top/Article/details/gtpfjntyvh.html

TS:   await Promise.all(tasks)
来源：http://dali.mhx1999.top/Article/details/gtsspuihxs.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jianghu66.top/Article/details/gtfsutvlax.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.haohaochexian.top/Article/details/gtcrxvuthy.html

Ruby: threads.map(&:join)
来源：http://dali.mhx1999.top/Article/details/gtkwzsfonf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhoulong.xyz/Article/details/gtdwosqsvx.html

[O06] 使用进程池
来源：http://dali.aizwys.cn/Article/details/gtgtuucbal.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.daria6918.cn/Article/details/gtlmbbjsii.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.havefunace.top/Article/details/gthpcgxjyv.html

JS:   // child_process / cluster 模块
来源：http://dali.ybcxt.top/Article/details/gtbebqdoki.html

TS:   // child_process / cluster 模块
来源：http://dali.yuanzhike.top/Article/details/gttqaaafdo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gotoacloud.top/Article/details/gtbpatyiso.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.c1oappe.top/Article/details/gtmnmmyxbv.html

Ruby: // fork 块
来源：http://dali.zhoulong.xyz/Article/details/gtihwqorcj.html

C#:   Parallel.For
来源：http://dali.hysaishi.cn/Article/details/gteopnhwqd.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadlitvyi.html

P. 常用工具函数
来源：http://dali.havefunace.top/Article/details/gtkmbzilbg.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtskcjlcxg.html

[P01] 生成 UUID
来源：http://dali.guowangkeji.top/Article/details/gtjtxzpeyf.html

Py:   str(uuid.uuid4())
来源：http://dali.xuetiantiany.cn/Article/details/gtrltvfglw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ivvv.top/Article/details/gtkyzngeso.html

JS:   crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gtaypzkdtq.html

TS:   crypto.randomUUID()
来源：http://dali.yuanzhike.top/Article/details/gtiikwzhvk.html

Java: UUID.randomUUID().toString()
来源：http://dali.hnxiangtu.top/Article/details/gtithjnoas.html

Go:   // 用 github.com/google/uuid
来源：http://dali.daxiang520.top/Article/details/gtsfqdwxfo.html

Ruby: SecureRandom.uuid
来源：http://dali.snrcjt.cn/Article/details/gtyzstrtgd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ybcxt.top/Article/details/gtvuajnmsy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gturhchhiq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.c1oappe.top/Article/details/gtikecwuee.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhoulong.xyz/Article/details/gtqmapkwtv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hammf.cn/Article/details/gtqqxnkomr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ehwqpu.com/Article/details/gtobqlgnnr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jqgufenzy.top/Article/details/gtwysrpsdt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gogol.net.cn/Article/details/gtawcuxgoi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.meibo888.top/Article/details/gtsfwdbcxv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xylfe.cn/Article/details/gtketgorge.html

[P03] 生成短随机字符串
来源：http://dali.gzhubu.top/Article/details/gtswnwpxhz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj202588.top/Article/details/gtyrfmshpp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tanke756.top/Article/details/gtxyokwbue.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.meibo888.top/Article/details/gtbztvnool.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhixingplan.top/Article/details/gtrmsukbnb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ehwqpu.com/Article/details/gtugevyozl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.pengpengdd.cyou/Article/details/gtwvfjnhwx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hnxiangtu.top/Article/details/gtwlujxvej.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.daria6918.cn/Article/details/gtrtqpgykc.html

[P04] 求长度
来源：http://dali.hnxiangtu.top/Article/details/gtjfcpapjb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jlsjyb.cn/Article/details/gtnyeplkjr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtpuzxeoxb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hammf.cn/Article/details/gtcthqoatm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pengpengdd.cyou/Article/details/gtyehlrcdb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.wangshuangyany.cn/Article/details/gtbqfraqdj.html

Go:   len(arr);  len(m)
来源：http://dali.jinqigfzy.top/Article/details/gtslonmxzd.html

Ruby: x.length;  x.size
来源：http://dali.meibo888.top/Article/details/gtmtqmqbhw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.c1oappe.top/Article/details/gtietwmsvq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shanyushiyangtech.top/Article/details/gtjitxbdsz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.mhx1999.top/Article/details/gtdalqunox.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cqqwz.cn/Article/details/gtktoetobd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.daxiang520.top/Article/details/gttuseitju.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.0kj1m.cn/Article/details/gtkkljszry.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gogol.net.cn/Article/details/gtdrjcwoqb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yvedp.cn/Article/details/gtydsxxtjb.html

Ruby: a == b
来源：http://dali.hongshengwenyu.top/Article/details/gtrsvefdrm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cheryme.top/Article/details/gtejzglbqi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhiwuduotai.top/Article/details/gtqkwnazvz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yanxiufei.cn/Article/details/gtliqkeoph.html

PHP:  if (empty($x)) {}
来源：http://dali.sysykeji.top/Article/details/gtxzrmpzaq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jlsjyb.cn/Article/details/gttucfrjwp.html

TS:   if (x == null) {}
来源：http://dali.redwolf501.top/Article/details/gtecbzywqx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gthhikxptn.html

Go:   if x == nil {}
来源：http://dali.tanke756.top/Article/details/gtlrfxiype.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hywenlv.cn/Article/details/gtysgycdoa.html

C#:   if (x is null) {}
来源：http://dali.iojbl.cn/Article/details/gttgccbhnt.html

[P07] 防抖与节流
来源：http://dali.c1oappe.top/Article/details/gthlpsujdc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jianghu66.top/Article/details/gtnovayihj.html

PHP:  // 手写时间戳比较
来源：http://dali.yongpay.top/Article/details/gtllkuimmp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gtqnpmcybn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gtxqutzztw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nanxinkj.top/Article/details/gtbabjhhqd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ppjwa.cn/Article/details/gtdvicvrdx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tianlin.xyz/Article/details/gtikbrkmdc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hywenlv.cn/Article/details/gtanznobkg.html

[P08] 处理浮点精度问题
来源：http://dali.jqgufenzy.top/Article/details/gtqhkdclex.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gogol.net.cn/Article/details/gtpoohacjo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yanxiufei.cn/Article/details/gtdjcgomlh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.daria6918.cn/Article/details/gttilfnjmj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhiwuduotai.top/Article/details/gtstspkubv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xziqi.cn/Article/details/gtuoelgrbq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.redwolf501.top/Article/details/gtnfacodhf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hnxiangtu.top/Article/details/gtpmakmosz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ehwqpu.com/Article/details/gtnwndddbc.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtqgalscvp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.pengpengdd.cyou/Article/details/gtyvsooxnq.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtsxoqpxlq.html

[Q01] 创建表
来源：http://dali.jianghu66.top/Article/details/gtgstlwnyq.html

CREATE TABLE users (
来源：http://dali.mhx1999.top/Article/details/gtwaxrfpow.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.redwolf501.top/Article/details/gttrijfzeq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ppjwa.cn/Article/details/gtzbjlxxti.html

email VARCHAR(100) UNIQUE,
来源：http://dali.daxiang520.top/Article/details/gtehptbimg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tanke756.top/Article/details/gtacwzjych.html

);
来源：http://dali.xuetiantiany.cn/Article/details/gtmngmjrxb.html

[Q02] 创建带外键的表
来源：http://dali.guannengcc.top/Article/details/gtamzfhejg.html

CREATE TABLE orders (
来源：http://dali.guannengcc.top/Article/details/gtviihzlfn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jlsjyb.cn/Article/details/gtydowxulg.html

user_id INT NOT NULL,
来源：http://dali.redwolf501.top/Article/details/gthrnbtter.html

amount DECIMAL(10, 2),
来源：http://dali.tianlin.xyz/Article/details/gturhnritx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xinyue.icu/Article/details/gtkeqvanux.html

);
来源：http://dali.yj202588.top/Article/details/gtvqndfynz.html

[Q03] 增加列
来源：http://dali.tanke756.top/Article/details/gtmvjidioe.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.bjfxy.top/Article/details/gtaczaqwiq.html

[Q04] 修改列类型
来源：http://dali.guannengcc.top/Article/details/gtzezaulks.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nwbrower.top/Article/details/gtunvvsumy.html

[Q05] 重命名列
来源：http://dali.aibaodan.cn/Article/details/gtxsigivvz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xuanzx.com/Article/details/gtcatyodez.html

[Q06] 删除列
来源：http://dali.tanke756.top/Article/details/gtwoiavngy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.vqdsnc.cn/Article/details/gtsnaeezem.html

[Q07] 删除表
来源：http://dali.yj202588.top/Article/details/gtlteseffq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.andypj.xyz/Article/details/gtvkdbheto.html

[Q08] 创建普通索引
来源：http://dali.zdqjudy.top/Article/details/gtqvvrjtxo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jiagoushi.top/Article/details/gtbcsmdzbz.html

[Q09] 创建唯一索引
来源：http://dali.jqgfzy.top/Article/details/gtqgglruwx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.wangdashe.top/Article/details/gtqptawwxv.html

[Q10] 插入单行
来源：http://dali.chenlongwang.top/Article/details/gtygrzyeir.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jiagoushi.top/Article/details/gtbfqtzniq.html

[Q11] 一次插入多行
来源：http://dali.zhiwuduotai.top/Article/details/gtusywgehm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zdqjudy.top/Article/details/gtuoncpyog.html

[Q12] 插入后取自增 ID
来源：http://dali.yuanzhike.top/Article/details/gtexwalllk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhiwuduotai.top/Article/details/gtvehqircw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tian-w.cn/Article/details/gtohiphryh.html

[Q13] 忽略重复插入
来源：http://dali.gaohongyu789.top/Article/details/gtigpfkwjd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.aibaodan.cn/Article/details/gtfikkfmce.html

[Q14] 存在则更新（upsert）
来源：http://dali.cqqwz.cn/Article/details/gtslnprcoc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.havefunace.top/Article/details/gtyusdwhin.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.9152youxi.cn/Article/details/gtexogxzmg.html

[Q15] 查询全部
来源：http://dali.ybcxt.top/Article/details/gttmdtuhfy.html

SELECT * FROM users;
来源：http://dali.tian-w.cn/Article/details/gtdoqtlutl.html

[Q16] 查询指定列
来源：http://dali.zdqjudy.top/Article/details/gtsnqwrcwk.html

SELECT id, name FROM users;
来源：http://dali.ydzc1.top/Article/details/gtidnavrhc.html

[Q17] 条件查询
来源：http://dali.chenzaomai.com/Article/details/gtxamnthzj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xylfe.cn/Article/details/gtwcilpxkj.html

[Q18] 模糊匹配
来源：http://dali.jianghu66.top/Article/details/gtwizpvhjy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zdqjudy.top/Article/details/gtxvixtsra.html

[Q19] 范围查询
来源：http://dali.zhiwuduotai.top/Article/details/gtlkcpxvdp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yuanzhike.top/Article/details/gtuugepirf.html

[Q20] IN 列表
来源：http://dali.snrcjt.cn/Article/details/gtxocoqhac.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cashguo.top/Article/details/gtbuxkplzr.html

[Q21] 空值判断
来源：http://dali.316326.xyz/Article/details/gtyrumkxjd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hammf.cn/Article/details/gtytyvxrww.html

[Q22] 排序
来源：http://dali.c1oappe.top/Article/details/gtxknlsesc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.0kj1m.cn/Article/details/gtzkcakbkk.html

[Q23] 分页
来源：http://dali.jqgfzy.top/Article/details/gttcvhohnm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sxryk.cn/Article/details/gtpbxkeeot.html

[Q24] 去重
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjtwhslir.html

SELECT DISTINCT city FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtqdxzpxyg.html

[Q25] 只取前 N 条
来源：http://dali.zycfv.cn/Article/details/gtcliemmdb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.9152youxi.cn/Article/details/gtfdyyzmbk.html

[Q26] 计数
来源：http://dali.zhengqikj.top/Article/details/gtosfefdkq.html

SELECT COUNT(*) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtzutjlsyy.html

[Q27] 条件计数
来源：http://dali.nanxinkj.top/Article/details/gtdxogryef.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtkerorace.html

[Q28] 求和与平均
来源：http://dali.andypj.xyz/Article/details/gtfhqfjoko.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmnvszgf.html

[Q29] 最大最小值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbxoyyjm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtxepxzwsw.html

[Q30] 分组统计
来源：http://dali.ivvv.top/Article/details/gtgqijlbdc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ivvv.top/Article/details/gtkevrssxw.html

[Q31] 分组后过滤
来源：http://dali.sxryk.cn/Article/details/gtwzisjavi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xylfe.cn/Article/details/gtuuwyfulu.html

[Q32] 分组拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gtapjfrxzg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gtokmwskpu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jqgfzy.top/Article/details/gtquiedcdr.html

[Q33] 多列分组
来源：http://dali.ppjwa.cn/Article/details/gtkumanfih.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gotoacloud.top/Article/details/gthwuptprn.html

[Q34] 每组取第一条
来源：http://dali.svipenyu.cn/Article/details/gtmkpbanvi.html

SELECT * FROM (
来源：http://dali.ehwqpu.com/Article/details/gtnxugrwvd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yueranfly.top/Article/details/gthdubpyji.html

) t WHERE rn = 1;
来源：http://dali.yonumen.top/Article/details/gtdtevmlka.html

[Q35] 内连接
来源：http://dali.zhongyouzk.top/Article/details/gtgpuchdyl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nwbrower.top/Article/details/gtupqjkcfp.html

[Q36] 左连接
来源：http://dali.yuxming.cn/Article/details/gtyncqvknw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhoulong.xyz/Article/details/gthascracm.html

[Q37] 右连接
来源：http://dali.yj20258.top/Article/details/gtyxjkvryv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xziqi.cn/Article/details/gtnjkzuxaq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinqigfzy.top/Article/details/gtsyrsojlw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xuetiantiany.cn/Article/details/gtgapmhkal.html

[Q39] 自连接（查上下级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgbvfmqt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinghuilouyu.cn/Article/details/gtezooxiox.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhiwuduotai.top/Article/details/gtkxalbxue.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tanke756.top/Article/details/gtwydzeibv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yuxming.cn/Article/details/gtcdguzjhj.html

[Q41] 多表连接
来源：http://dali.zdqjudy.top/Article/details/gthzxmsmba.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yangfankeji.com/Article/details/gtphdscsfx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.pycfn.com/Article/details/gtfvwtkwrk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gzhubu.top/Article/details/gtpjxicxdc.html

[Q42] 连接条件附加过滤
来源：http://dali.zhoulong.xyz/Article/details/gtszemmvvm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj202588.top/Article/details/gtbndtqsxn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.feifeiyinyue.top/Article/details/gtczmpzvox.html

[Q43] 标量子查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtizlsjrpm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhongyouzk.top/Article/details/gtluwoqvem.html

[Q44] IN 子查询
来源：http://dali.havefunace.top/Article/details/gtejmtwzla.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.dashuyun.cn/Article/details/gtfzosdikt.html

[Q45] EXISTS 判断存在
来源：http://dali.gzhubu.top/Article/details/gtlertrnfx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.quarkkingdee.top/Article/details/gtvfsgfsoo.html


<!-- 参考信息 -->