代发 wailian999

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.wangshuangyany.cn/Article/details/gtwqbixdsz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhengqikj.top/Article/details/gthpvqgzcr.html

TS:   // 手写 Map<string, number>
来源：http://dali.fzhhl.top/Article/details/gtpyhvpqzx.html

Java: // 手写 HashMap
来源：http://dali.316326.xyz/Article/details/gtxpyhlhyb.html

Go:   // 手写 map[int]int
来源：http://dali.snrcjt.cn/Article/details/gtknxvibgc.html

Ruby: // 手写 Hash
来源：http://dali.zhengqikj.top/Article/details/gtfscqdcdw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gzhubu.top/Article/details/gtnykwcvig.html

[N08] 生成全排列
来源：http://dali.xuetiantiany.cn/Article/details/gtpebtazbr.html

Py:   itertools.permutations(arr)
来源：http://dali.chenzaomai.com/Article/details/gtmjgbaugi.html

PHP:  // 手写递归交换
来源：http://dali.hywenlv.cn/Article/details/gthmkntzti.html

JS:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtozwmhozr.html

TS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtxglrqapd.html

Java: // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtwdkxonsk.html

Go:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtkcvwkbdf.html

Ruby: arr.permutation.to_a
来源：http://dali.gzhubu.top/Article/details/gtkyiawyft.html

C#:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtneqlobwx.html

[N09] 栈与队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuvyvpymf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtjfgwvtmv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgluodphh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtirorjwey.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shangyingyoupin.top/Article/details/gtcdbwcwbf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zycfv.cn/Article/details/gtmzorpgwl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitnvlbaq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sweek.top/Article/details/gtjtfshrdw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ydzc1.top/Article/details/gtiupkegjx.html

[N10] 链表节点定义
来源：http://dali.daxiang520.top/Article/details/gtrmmaqpzi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ehwqpu.com/Article/details/gtkxdelvsz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jqgfzy.top/Article/details/gttwksiglf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jianghu66.top/Article/details/gtlnpljxeb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hnxiangtu.top/Article/details/gtpjhamfob.html

Java: class Node { int v; Node next; }
来源：http://dali.daxiang520.top/Article/details/gtflywmdnk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.daxiang520.top/Article/details/gttqammkkm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.iojbl.cn/Article/details/gtvesznirk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.meibo888.top/Article/details/gtgdnnevuj.html

[N11] 二叉树中序遍历
来源：http://dali.sysykeji.top/Article/details/gtxoipxgac.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.iojbl.cn/Article/details/gtqputyvji.html

PHP:  // 手写递归函数
来源：http://dali.hysaishi.cn/Article/details/gtidhdsqzy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.bjfxy.top/Article/details/gtkytzaygj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hywenlv.cn/Article/details/gtoijxocwp.html

Java: // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gtvzupipzy.html

Go:   // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtuevqpmqq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tanke756.top/Article/details/gtkfojroyh.html

C#:   // 手写递归
来源：http://dali.yj20258888.top/Article/details/gtcycrzqid.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.aibaodan.cn/Article/details/gtavtqcqzx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.quarkkingdee.top/Article/details/gtghasjrze.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nanxinkj.top/Article/details/gtpychhrcl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.haohaochexian.top/Article/details/gtmezvkspb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnxiangtu.top/Article/details/gtbzmdmzrb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pycfn.com/Article/details/gtokunxixv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ehwqpu.com/Article/details/gtwgdacbjr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.smart0.xyz/Article/details/gtipgdbplt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gtqvvtumqq.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzedyqiii.html

O. 并发与异步
来源：http://dali.cqqwz.cn/Article/details/gtqulajlli.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtvrepphsr.html

[O01] 启动一个线程
来源：http://dali.shuidangran.top/Article/details/gthjzzjxak.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hammf.cn/Article/details/gtxjvmcxfy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ydzc1.top/Article/details/gteughkcrt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tianlin.xyz/Article/details/gtpsisukds.html

TS:   // 同 JS
来源：http://dali.gogol.net.cn/Article/details/gtfmpvcfui.html

Java: new Thread(() -> f()).start()
来源：http://dali.haohaochexian.top/Article/details/gtgqpatlar.html

Go:   go f()
来源：http://dali.sweek.top/Article/details/gtiybkwnap.html

Ruby: Thread.new { f }
来源：http://dali.tianlin.xyz/Article/details/gtlsidfmke.html

C#:   Task.Run(() => F());
来源：http://dali.fzhhl.top/Article/details/gtvspcppjh.html

[O02] 使用线程池
来源：http://dali.redwolf501.top/Article/details/gthewgbfsy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxuanxn.top/Article/details/gtbpqctzxn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.bjfxy.top/Article/details/gtckjsdapj.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gtfutvlddo.html

TS:   // worker_threads 线程池
来源：http://dali.zhoulong.xyz/Article/details/gtccpgprfo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.c1oappe.top/Article/details/gtyhibcujr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.fzhhl.top/Article/details/gttihopkmt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cheryme.top/Article/details/gtoxciuiym.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinqigfzy.top/Article/details/gtmzhnwkdj.html

[O03] 加锁保护共享数据
来源：http://dali.xylfe.cn/Article/details/gtjwlvmxzz.html

Py:   with lock: shared += 1
来源：http://dali.yuxming.cn/Article/details/gttteaolwc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinqigfzy.top/Article/details/gtzxgyctre.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.dianchejie.cn/Article/details/gteebjofks.html

TS:   // 同 JS
来源：http://dali.ehwqpu.com/Article/details/gtbdqonmow.html

Java: synchronized (this) { shared++; }
来源：http://dali.nanxuanxn.top/Article/details/gtlnhqtqxx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sysykeji.top/Article/details/gtpgghjhmc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xylfe.cn/Article/details/gtippgkkkg.html

C#:   lock (gate) { shared++; }
来源：http://dali.yueranfly.top/Article/details/gtgbtmzjcz.html

[O04] 定义异步函数并等待
来源：http://dali.yj20258888.top/Article/details/gtvyrvlhpz.html

Py:   async def f():⏎    await g()
来源：http://dali.hnqzz.top/Article/details/gtjzmxegym.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yuxming.cn/Article/details/gtujmlpeda.html

JS:   async function f() { await g(); }
来源：http://dali.dianchejie.cn/Article/details/gtzdqradnw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shzxlz.cn/Article/details/gtjrdddojy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hammf.cn/Article/details/gtfbqxhplh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ydzc1.top/Article/details/gtlhjiphmu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jqgfzy.top/Article/details/gtsinzyuav.html

C#:   async Task F() { await G(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtpygkmvop.html

[O05] 并发执行并等待全部完成
来源：http://dali.smart0.xyz/Article/details/gtftklvecy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhixingplan.top/Article/details/gtpnahazhf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xuetiantiany.cn/Article/details/gtfkywsdnn.html

JS:   await Promise.all(tasks)
来源：http://dali.vqdsnc.cn/Article/details/gtavwweqal.html

TS:   await Promise.all(tasks)
来源：http://dali.jqgufenzy.top/Article/details/gthrfrwfwa.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hfpthk.cn/Article/details/gtqawzhnhf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gaohongyu789.top/Article/details/gtlmoybtcp.html

Ruby: threads.map(&:join)
来源：http://dali.ybcxt.top/Article/details/gtgaiidxfe.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tianlin.xyz/Article/details/gtcjpcmekz.html

[O06] 使用进程池
来源：http://dali.shzxlz.cn/Article/details/gtmqxekgdr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.bjfxy.top/Article/details/gtsglkifdp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhongyouzk.top/Article/details/gtsupagknu.html

JS:   // child_process / cluster 模块
来源：http://dali.iojbl.cn/Article/details/gtjzqplral.html

TS:   // child_process / cluster 模块
来源：http://dali.daria6918.cn/Article/details/gtowokqsxf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj20258888.top/Article/details/gtgpmqqlmy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.andypj.xyz/Article/details/gtshqsfnpk.html

Ruby: // fork 块
来源：http://dali.gotoacloud.top/Article/details/gtomlpbhgb.html

C#:   Parallel.For
来源：http://dali.shangyingyoupin.top/Article/details/gtiqsvyhpz.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtfrrmqtvk.html

P. 常用工具函数
来源：http://dali.iojbl.cn/Article/details/gtrkiwurpu.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtukyytdae.html

[P01] 生成 UUID
来源：http://dali.guannengcc.top/Article/details/gtxqdlmapa.html

Py:   str(uuid.uuid4())
来源：http://dali.pycfn.com/Article/details/gtqqzydtrz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwexgpfq.html

JS:   crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gtumfyxvne.html

TS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdzcqfpfi.html

Java: UUID.randomUUID().toString()
来源：http://dali.aizwys.cn/Article/details/gtqmskawsk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.vqdsnc.cn/Article/details/gtehxykszi.html

Ruby: SecureRandom.uuid
来源：http://dali.jlsjyb.cn/Article/details/gttfygfeka.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xuanzx.com/Article/details/gtcojamcoc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xinyue.icu/Article/details/gtxpwvfbqz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xziqi.cn/Article/details/gtgfujgvcb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj20258888.top/Article/details/gtnfblxjly.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.daria6918.cn/Article/details/gtdwtpxaoe.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jianghu66.top/Article/details/gtvbbnlgyz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gtdugislec.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.feifeiyinyue.top/Article/details/gtzjduhhlq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cheryme.top/Article/details/gtexbmrawb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jqgufenzy.top/Article/details/gtqcjiehrs.html

[P03] 生成短随机字符串
来源：http://dali.sufxvd.cn/Article/details/gtcwdcqzvd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenzaomai.com/Article/details/gtvxwqunnc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hywenlv.cn/Article/details/gtbppvjsfv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cheryme.top/Article/details/gtqltqfzeu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xziqi.cn/Article/details/gtbqcpguoq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yuxming.cn/Article/details/gttunnfoeq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.c1oappe.top/Article/details/gtidmqqwhq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jianghu66.top/Article/details/gtkntmxltj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.wangdashe.top/Article/details/gtufykkrus.html

[P04] 求长度
来源：http://dali.ppjwa.cn/Article/details/gtscyymdyj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj202588.top/Article/details/gtjkstjgzr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtvmigzfht.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guannengcc.top/Article/details/gtfkwbljyz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gaohongyu789.top/Article/details/gtphhckalo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sufxvd.cn/Article/details/gtgphlcdtr.html

Go:   len(arr);  len(m)
来源：http://dali.ivvv.top/Article/details/gtogfboxkk.html

Ruby: x.length;  x.size
来源：http://dali.zhongyouzk.top/Article/details/gtdgymvvve.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.meibo888.top/Article/details/gtrnqjikyk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjngrgpjw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.vqdsnc.cn/Article/details/gtzzxqxfju.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.havefunace.top/Article/details/gtpsbdhdpj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenlongwang.top/Article/details/gtjzsfhlob.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigufen.top/Article/details/gtandfwgvm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebplxbck.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.316326.xyz/Article/details/gtuaejyxnf.html

Ruby: a == b
来源：http://dali.daria6918.cn/Article/details/gthoolszhn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yonumen.top/Article/details/gtbaxmsqib.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtamjuaigq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yj20258.top/Article/details/gtdgxvxxps.html

PHP:  if (empty($x)) {}
来源：http://dali.ehwqpu.com/Article/details/gtsdyzccsb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.dianchejie.cn/Article/details/gtnnizjxav.html

TS:   if (x == null) {}
来源：http://dali.iojbl.cn/Article/details/gtazqhbziy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.svipenyu.cn/Article/details/gtmleaqzsn.html

Go:   if x == nil {}
来源：http://dali.wangshuangyany.cn/Article/details/gtnqzuhgta.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhoulong.xyz/Article/details/gtjzjyeunf.html

C#:   if (x is null) {}
来源：http://dali.hfpthk.cn/Article/details/gtadydlead.html

[P07] 防抖与节流
来源：http://dali.gaohongyu789.top/Article/details/gtewzuymtd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwymqdajg.html

PHP:  // 手写时间戳比较
来源：http://dali.quarkkingdee.top/Article/details/gtotfrrbtf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shuidangran.top/Article/details/gtcfgvctjn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yueranfly.top/Article/details/gtixknyydc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhixingplan.top/Article/details/gtsxfkbcaa.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xuetiantiany.cn/Article/details/gtmempjowr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nanxuanxn.top/Article/details/gtuljsjdab.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ppjwa.cn/Article/details/gtwidpseuv.html

[P08] 处理浮点精度问题
来源：http://dali.ydzc1.top/Article/details/gtjiguvlmy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfszhcbg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jiagoushi.top/Article/details/gteguqcjok.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zdqjudy.top/Article/details/gtlwsrdmgs.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.redwolf501.top/Article/details/gtawqtyhvj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlqeqjqqz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.andypj.xyz/Article/details/gtuszbniko.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlevajlgj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yanxiufei.cn/Article/details/gttryjhnyc.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtzitntksk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yangfankeji.com/Article/details/gtktvnkhwf.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtbomrhamj.html

[Q01] 创建表
来源：http://dali.zdqjudy.top/Article/details/gtcivbyyos.html

CREATE TABLE users (
来源：http://dali.jqgfzy.top/Article/details/gtpesioeds.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgufenzy.top/Article/details/gtqlvsbqwk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.fengsongda.top/Article/details/gtrxazbrsx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gotoacloud.top/Article/details/gtefipgtnj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.0kj1m.cn/Article/details/gtutotkbsj.html

);
来源：http://dali.gzhubu.top/Article/details/gtjzhbiwke.html

[Q02] 创建带外键的表
来源：http://dali.birdmap.top/Article/details/gtdzqnzgwu.html

CREATE TABLE orders (
来源：http://dali.xylfe.cn/Article/details/gtlsawjgle.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cqqwz.cn/Article/details/gtrvdawrsz.html

user_id INT NOT NULL,
来源：http://dali.hongshengwenyu.top/Article/details/gtgcgmbbbs.html

amount DECIMAL(10, 2),
来源：http://dali.xuanzx.com/Article/details/gtqbrmxusw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shzxlz.cn/Article/details/gtfkvcztou.html

);
来源：http://dali.zdqjudy.top/Article/details/gtghexkbba.html

[Q03] 增加列
来源：http://dali.yanxiufei.cn/Article/details/gtofwlelvs.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhiwuduotai.top/Article/details/gtqzraoize.html

[Q04] 修改列类型
来源：http://dali.chenlongwang.top/Article/details/gtmtbkbybq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpzzhtxhy.html

[Q05] 重命名列
来源：http://dali.ybcxt.top/Article/details/gtumbviagd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yuxming.cn/Article/details/gtrryugvyf.html

[Q06] 删除列
来源：http://dali.jinqigufen.top/Article/details/gttnypdxro.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.kuanghao11.cn/Article/details/gtelsjjpxc.html

[Q07] 删除表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjflcrkcw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jqgufenzy.top/Article/details/gtipfpginx.html

[Q08] 创建普通索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmiqklzzv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.birdmap.top/Article/details/gtycrdkofc.html

[Q09] 创建唯一索引
来源：http://dali.xuetiantiany.cn/Article/details/gtbusiekvd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenlongwang.top/Article/details/gtjdgiksyq.html

[Q10] 插入单行
来源：http://dali.sweek.top/Article/details/gtdtdvqdcm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tian-w.cn/Article/details/gtjxyujbgj.html

[Q11] 一次插入多行
来源：http://dali.cdnleiting.top/Article/details/gtxksnfudx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.daria6918.cn/Article/details/gtybtyturo.html

[Q12] 插入后取自增 ID
来源：http://dali.hysaishi.cn/Article/details/gtgpyiuich.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhengqikj.top/Article/details/gtfmqgdppm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sufxvd.cn/Article/details/gtxrdmmoxz.html

[Q13] 忽略重复插入
来源：http://dali.tanke756.top/Article/details/gtsgpstroi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sysykeji.top/Article/details/gtcluiodee.html

[Q14] 存在则更新（upsert）
来源：http://dali.iojbl.cn/Article/details/gtmxwtcciu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cqqwz.cn/Article/details/gthyhnxlrg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yanxiufei.cn/Article/details/gtvosjttnm.html

[Q15] 查询全部
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxrhabmoo.html

SELECT * FROM users;
来源：http://dali.jianghu66.top/Article/details/gtrzvmhngr.html

[Q16] 查询指定列
来源：http://dali.jqgfzy.top/Article/details/gtxbgdgqji.html

SELECT id, name FROM users;
来源：http://dali.xuanzx.com/Article/details/gtzjdhslfp.html

[Q17] 条件查询
来源：http://dali.jiagoushi.top/Article/details/gthiycyikl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yonumen.top/Article/details/gtiqctzhop.html

[Q18] 模糊匹配
来源：http://dali.zhongyouzk.top/Article/details/gtfqkrhnsm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.fzhhl.top/Article/details/gtnpbjmuyg.html

[Q19] 范围查询
来源：http://dali.ivvv.top/Article/details/gtsvguppen.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.dianchejie.cn/Article/details/gtntjwmlkf.html

[Q20] IN 列表
来源：http://dali.zhoulong.xyz/Article/details/gtlfhaeqjs.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtnzokuvqj.html

[Q21] 空值判断
来源：http://dali.yangfankeji.com/Article/details/gtcwpbfche.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmdkblra.html

[Q22] 排序
来源：http://dali.yanxiufei.cn/Article/details/gtwfgydrsm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cashguo.top/Article/details/gtybjleqth.html

[Q23] 分页
来源：http://dali.jinghuilouyu.cn/Article/details/gtyazyllxc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sxryk.cn/Article/details/gtkypqgdva.html

[Q24] 去重
来源：http://dali.hysaishi.cn/Article/details/gtzcrwklep.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtewfbpyul.html

[Q25] 只取前 N 条
来源：http://dali.fengsongda.top/Article/details/gtkacyoosa.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.pycfn.com/Article/details/gtvqjbxorj.html

[Q26] 计数
来源：http://dali.chenzaomai.com/Article/details/gtiqjjtazi.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtlbqgxgex.html

[Q27] 条件计数
来源：http://dali.guannengcc.top/Article/details/gtxjemqqgu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.iojbl.cn/Article/details/gtirckbjji.html

[Q28] 求和与平均
来源：http://dali.hfpthk.cn/Article/details/gtvpwzznmi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtzmhefqxb.html

[Q29] 最大最小值
来源：http://dali.sweek.top/Article/details/gtaxuzytvc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtfloogtnr.html

[Q30] 分组统计
来源：http://dali.yj202588.top/Article/details/gtafpfxody.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gtygcpvvjc.html

[Q31] 分组后过滤
来源：http://dali.vqdsnc.cn/Article/details/gtifgeohgv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ehwqpu.com/Article/details/gteyufvafn.html

[Q32] 分组拼接字符串
来源：http://dali.sweek.top/Article/details/gtymzshvli.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gtimkjyrik.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ppjwa.cn/Article/details/gtrjnwiyia.html

[Q33] 多列分组
来源：http://dali.hammf.cn/Article/details/gtdeveysmu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.c1oappe.top/Article/details/gteyieifrn.html

[Q34] 每组取第一条
来源：http://dali.dianchejie.cn/Article/details/gtacmnxfob.html

SELECT * FROM (
来源：http://dali.xziqi.cn/Article/details/gtribwrvnq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jianghu66.top/Article/details/gtkpbfzffc.html

) t WHERE rn = 1;
来源：http://dali.cqqwz.cn/Article/details/gtivljqxbz.html

[Q35] 内连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtabtzurjj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xylfe.cn/Article/details/gtvmlfykrt.html

[Q36] 左连接
来源：http://dali.cqqwz.cn/Article/details/gtlssudcll.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.guowangkeji.top/Article/details/gtyqqqpxdh.html

[Q37] 右连接
来源：http://dali.shuidangran.top/Article/details/gtzhlqavge.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.pycfn.com/Article/details/gtfrsrmyqk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yueranfly.top/Article/details/gthnvtntle.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.daria6918.cn/Article/details/gthwwcblji.html

[Q39] 自连接（查上下级）
来源：http://dali.fengsongda.top/Article/details/gtbiyftgmv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xinyue.icu/Article/details/gteualyyov.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.dashuyun.cn/Article/details/gtigrphucd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jyoumei.cn/Article/details/gtbsycjnub.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cashguo.top/Article/details/gtqrzqkezq.html

[Q41] 多表连接
来源：http://dali.ivvv.top/Article/details/gtvlslpmai.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.daria6918.cn/Article/details/gtykzahebm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.snrcjt.cn/Article/details/gtyfpitjpz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shzxlz.cn/Article/details/gtqmddhikc.html

[Q42] 连接条件附加过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtcpnxrkru.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shanyushiyangtech.top/Article/details/gtmabdlgdy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.dashuyun.cn/Article/details/gtsmbrqdbj.html

[Q43] 标量子查询
来源：http://dali.cheryme.top/Article/details/gtmjseycig.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgfzy.top/Article/details/gtllfmreiy.html

[Q44] IN 子查询
来源：http://dali.yonumen.top/Article/details/gtryfvoykl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yongpay.top/Article/details/gtubyvwyql.html

[Q45] EXISTS 判断存在
来源：http://dali.nanxinkj.top/Article/details/gtahbglhbq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigfzy.top/Article/details/gtvqcnrdae.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hfpthk.cn/Article/details/gtjynrxbhj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj202588.top/Article/details/gtaklowatb.html

[Q47] 与平均值比较
来源：http://dali.ydzc1.top/Article/details/gtqgrnqwgr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.daria6918.cn/Article/details/gttnjivlua.html


<!-- 参考信息 -->