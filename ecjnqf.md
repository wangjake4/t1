代发 wailian999

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sufxvd.cn/Article/details/gticcwwmrm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hfpthk.cn/Article/details/gtlfxvopoq.html

TS:   // 手写 Map<string, number>
来源：http://dali.aibaodan.cn/Article/details/gthicirlzn.html

Java: // 手写 HashMap
来源：http://dali.sysykeji.top/Article/details/gtcxzdvaug.html

Go:   // 手写 map[int]int
来源：http://dali.sysykeji.top/Article/details/gtgiiddpme.html

Ruby: // 手写 Hash
来源：http://dali.cdnleiting.top/Article/details/gtzcjiskwj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shangyingyoupin.top/Article/details/gttjegddlq.html

[N08] 生成全排列
来源：http://dali.wangdashe.top/Article/details/gtfqimfyir.html

Py:   itertools.permutations(arr)
来源：http://dali.guowangkeji.top/Article/details/gtfhaqmeax.html

PHP:  // 手写递归交换
来源：http://dali.dianchejie.cn/Article/details/gtijznymue.html

JS:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtxbtznjta.html

TS:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtlseuhsyc.html

Java: // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gttochtpdt.html

Go:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtzgqgiool.html

Ruby: arr.permutation.to_a
来源：http://dali.havefunace.top/Article/details/gtndzkatve.html

C#:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtmqfnmdmi.html

[N09] 栈与队列
来源：http://dali.9152youxi.cn/Article/details/gtxamvgxff.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.wangdashe.top/Article/details/gttetvcgob.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gturpxrwfu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gteafnelsz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ehwqpu.com/Article/details/gtwgcghcuf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ybcxt.top/Article/details/gtnqbhuvoo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nwbrower.top/Article/details/gtrhevkodw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gttleepclf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ppjwa.cn/Article/details/gtsnvfyweg.html

[N10] 链表节点定义
来源：http://dali.meibo888.top/Article/details/gtlylslrpo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shzxlz.cn/Article/details/gtttecxpvn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.fengsongda.top/Article/details/gtzqaqjkwb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gttojwurck.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmeknolvf.html

Java: class Node { int v; Node next; }
来源：http://dali.sysykeji.top/Article/details/gtjvxglkzk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuiyepwcm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.wangshuangyany.cn/Article/details/gthlhknkzv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hnxiangtu.top/Article/details/gtpdyauzik.html

[N11] 二叉树中序遍历
来源：http://dali.cqqwz.cn/Article/details/gtxpfjblec.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jqgufenzy.top/Article/details/gtorffmypt.html

PHP:  // 手写递归函数
来源：http://dali.zycfv.cn/Article/details/gtloqxddba.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangshuangyany.cn/Article/details/gtreiqsnjp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxinkj.top/Article/details/gtcyicvmux.html

Java: // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gtfuiobekp.html

Go:   // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gtflodymsj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shuidangran.top/Article/details/gtrrbsxydc.html

C#:   // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gtetddvcvr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.havefunace.top/Article/details/gtbxmmcrkb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jqgufenzy.top/Article/details/gtlacshawt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.wangshuangyany.cn/Article/details/gtijivqjtg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigfzy.top/Article/details/gtlksnozbb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigufen.top/Article/details/gttxwjswcr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shzxlz.cn/Article/details/gtxnnpcieq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xinyue.icu/Article/details/gtnynkenph.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhixingplan.top/Article/details/gtqwtjrafi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yvedp.cn/Article/details/gtgnscycxf.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtdakwuclk.html

O. 并发与异步
来源：http://dali.yj20258888.top/Article/details/gtqbjrguja.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtzmrmakir.html

[O01] 启动一个线程
来源：http://dali.chenlongwang.top/Article/details/gtcyhbvkog.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.mhx1999.top/Article/details/gtjkbgjues.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shzxlz.cn/Article/details/gtjnvlbqpf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.pengpengdd.cyou/Article/details/gtwezeoykn.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gtzfbijfjd.html

Java: new Thread(() -> f()).start()
来源：http://dali.hnqzz.top/Article/details/gtzfbubjhr.html

Go:   go f()
来源：http://dali.jyoumei.cn/Article/details/gtzxtjikxv.html

Ruby: Thread.new { f }
来源：http://dali.xuanzx.com/Article/details/gtkyrsmfcv.html

C#:   Task.Run(() => F());
来源：http://dali.shuidangran.top/Article/details/gtxvaemfgq.html

[O02] 使用线程池
来源：http://dali.yongpay.top/Article/details/gtjqlcxube.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.andypj.xyz/Article/details/gtiefoxbxa.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangshuangyany.cn/Article/details/gtiiytchex.html

JS:   // worker_threads 线程池
来源：http://dali.pycfn.com/Article/details/gtpyznymkc.html

TS:   // worker_threads 线程池
来源：http://dali.tian-w.cn/Article/details/gtkdmlgezx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.kuanghao11.cn/Article/details/gtzbgnabyc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shuidangran.top/Article/details/gthgilxqrp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.9152youxi.cn/Article/details/gtzjpdgdmx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yonumen.top/Article/details/gtfmylpztc.html

[O03] 加锁保护共享数据
来源：http://dali.iojbl.cn/Article/details/gtmrvwoebh.html

Py:   with lock: shared += 1
来源：http://dali.ehwqpu.com/Article/details/gtorgaadyt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xziqi.cn/Article/details/gtdrtcbnec.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zycfv.cn/Article/details/gtwuwcwmot.html

TS:   // 同 JS
来源：http://dali.pengpengdd.cyou/Article/details/gtgrvpzoai.html

Java: synchronized (this) { shared++; }
来源：http://dali.hnqzz.top/Article/details/gtaehzejco.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.iojbl.cn/Article/details/gtttalcwda.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ydzc1.top/Article/details/gtqfpksyxa.html

C#:   lock (gate) { shared++; }
来源：http://dali.hnqzz.top/Article/details/gttirjoghf.html

[O04] 定义异步函数并等待
来源：http://dali.zhixingplan.top/Article/details/gtntbbnhml.html

Py:   async def f():⏎    await g()
来源：http://dali.hongshengwenyu.top/Article/details/gtjgplsvun.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xuetiantiany.cn/Article/details/gtpzonlttq.html

JS:   async function f() { await g(); }
来源：http://dali.sxryk.cn/Article/details/gtiddnsbrv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gzhubu.top/Article/details/gteqpkbmxm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.iojbl.cn/Article/details/gtycqcxwkk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nwbrower.top/Article/details/gtikbpgevm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xylfe.cn/Article/details/gtacdokgfa.html

C#:   async Task F() { await G(); }
来源：http://dali.yj202588.top/Article/details/gtlcrlemiu.html

[O05] 并发执行并等待全部完成
来源：http://dali.wangdashe.top/Article/details/gtoatvsdmi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.daria6918.cn/Article/details/gtocmgekmv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinghuilouyu.cn/Article/details/gtmypumxbf.html

JS:   await Promise.all(tasks)
来源：http://dali.yuxming.cn/Article/details/gtmhilmlet.html

TS:   await Promise.all(tasks)
来源：http://dali.jiagoushi.top/Article/details/gtzrlzlvoz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuanzhike.top/Article/details/gthanvsiwz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.aibaodan.cn/Article/details/gtwxzqsokj.html

Ruby: threads.map(&:join)
来源：http://dali.gzhubu.top/Article/details/gtvmikkemh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sxryk.cn/Article/details/gtdcsexsau.html

[O06] 使用进程池
来源：http://dali.daxiang520.top/Article/details/gtsijfqxbl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjujkoiqu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tanke756.top/Article/details/gtkzscrqnn.html

JS:   // child_process / cluster 模块
来源：http://dali.sysykeji.top/Article/details/gtomagfuoe.html

TS:   // child_process / cluster 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuuffheox.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenlongwang.top/Article/details/gtxdfaqxbq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.wangdashe.top/Article/details/gtzopcdsrd.html

Ruby: // fork 块
来源：http://dali.zdqjudy.top/Article/details/gttudnmszy.html

C#:   Parallel.For
来源：http://dali.zhaomingkeji.xyz/Article/details/gteznrmafb.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtlapuevla.html

P. 常用工具函数
来源：http://dali.yuanzhike.top/Article/details/gtmcnwghoa.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtkdzoiblv.html

[P01] 生成 UUID
来源：http://dali.sysykeji.top/Article/details/gtrkulhptb.html

Py:   str(uuid.uuid4())
来源：http://dali.xziqi.cn/Article/details/gtmwlrwtxp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yonumen.top/Article/details/gtsgwcnuxn.html

JS:   crypto.randomUUID()
来源：http://dali.jiagoushi.top/Article/details/gtaqvnjctk.html

TS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gtfwdceulo.html

Java: UUID.randomUUID().toString()
来源：http://dali.hywenlv.cn/Article/details/gtnbnzozsh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sxryk.cn/Article/details/gthxlmdjlk.html

Ruby: SecureRandom.uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdnqkwzcz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.feifeiyinyue.top/Article/details/gtjhowlwdw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ppjwa.cn/Article/details/gtjnyfkyvo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hammf.cn/Article/details/gtfsyoqrks.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiyzsvgvc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gzhubu.top/Article/details/gtpkwerira.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.vqdsnc.cn/Article/details/gtsoogdgpi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gtmwgcxswu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yongpay.top/Article/details/gtdfyltxbl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.tian-w.cn/Article/details/gtegasubeb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aizwys.cn/Article/details/gtfawouldu.html

[P03] 生成短随机字符串
来源：http://dali.havefunace.top/Article/details/gtrmjviyad.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hysaishi.cn/Article/details/gtsivxmbve.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.9152youxi.cn/Article/details/gtergfwznn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gtzkbyghqh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.c1oappe.top/Article/details/gtgcsiusxn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nanxuanxn.top/Article/details/gtzruqptnh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.c1oappe.top/Article/details/gtoilcsqbb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yuxming.cn/Article/details/gtvdkanfoz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.snrcjt.cn/Article/details/gtdyyhoenx.html

[P04] 求长度
来源：http://dali.nwbrower.top/Article/details/gtzpdxjtdy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.havefunace.top/Article/details/gtowdypwiq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtrdizwagy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tianlin.xyz/Article/details/gtqcrepmha.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gogol.net.cn/Article/details/gtiqlqkcld.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj202588.top/Article/details/gtiexmbise.html

Go:   len(arr);  len(m)
来源：http://dali.cheryme.top/Article/details/gtuoadzgye.html

Ruby: x.length;  x.size
来源：http://dali.guannengcc.top/Article/details/gtvtctfrju.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.9152youxi.cn/Article/details/gtywxbmsym.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yonumen.top/Article/details/gtkppfnlfh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ydzc1.top/Article/details/gtaujuskhr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cheryme.top/Article/details/gtdorrndbe.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinqigufen.top/Article/details/gtclpmigjs.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtykablqnv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xuanzx.com/Article/details/gttazdizpj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.wangdashe.top/Article/details/gteijooljt.html

Ruby: a == b
来源：http://dali.birdmap.top/Article/details/gtpgcuzufh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.pycfn.com/Article/details/gtiuhcybah.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhoulong.xyz/Article/details/gtfvqgumkd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nanxinkj.top/Article/details/gthynppxkp.html

PHP:  if (empty($x)) {}
来源：http://dali.ybcxt.top/Article/details/gtdjjwwbnr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.pengpengdd.cyou/Article/details/gtolmsdpsx.html

TS:   if (x == null) {}
来源：http://dali.jqgufenzy.top/Article/details/gttfiddwhg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.kuanghao11.cn/Article/details/gtmclzklcp.html

Go:   if x == nil {}
来源：http://dali.yonumen.top/Article/details/gteeddajzi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tianlin.xyz/Article/details/gttroyvrey.html

C#:   if (x is null) {}
来源：http://dali.shzxlz.cn/Article/details/gtzjjefdty.html

[P07] 防抖与节流
来源：http://dali.cashguo.top/Article/details/gtypnzwbir.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jiagoushi.top/Article/details/gthszufmcv.html

PHP:  // 手写时间戳比较
来源：http://dali.tianlin.xyz/Article/details/gtyioxxhri.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xinyue.icu/Article/details/gtbcldwhxp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hywenlv.cn/Article/details/gtvbvszwcn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxczexdz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhiwuduotai.top/Article/details/gtdlhzeleo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gtcjzemhug.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.aibaodan.cn/Article/details/gtsejozshn.html

[P08] 处理浮点精度问题
来源：http://dali.jyoumei.cn/Article/details/gtnjqmnyoe.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shzxlz.cn/Article/details/gtllujcvac.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cashguo.top/Article/details/gtczbbcjzm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.chenlongwang.top/Article/details/gtkzhxcsec.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sxryk.cn/Article/details/gtqomnzsep.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzlyhbguy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nwbrower.top/Article/details/gtrejqtosq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.mhx1999.top/Article/details/gteogrsepc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ppjwa.cn/Article/details/gtjglwdxjv.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtqwbffbez.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.smart0.xyz/Article/details/gtzlmyoouj.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtsoouqmip.html

[Q01] 创建表
来源：http://dali.feifeiyinyue.top/Article/details/gtfsgffdmt.html

CREATE TABLE users (
来源：http://dali.hnxiangtu.top/Article/details/gtofkbccsd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ivvv.top/Article/details/gtjovstguv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.fengsongda.top/Article/details/gtymliyzcp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jqgfzy.top/Article/details/gtzitpsyim.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.aibaodan.cn/Article/details/gtxaqhydoa.html

);
来源：http://dali.shuidangran.top/Article/details/gtbljtergk.html

[Q02] 创建带外键的表
来源：http://dali.yanxiufei.cn/Article/details/gtocawuqzm.html

CREATE TABLE orders (
来源：http://dali.yj20258888.top/Article/details/gtmbyxjnma.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdftgoxom.html

user_id INT NOT NULL,
来源：http://dali.xuetiantiany.cn/Article/details/gteqbtkfkm.html

amount DECIMAL(10, 2),
来源：http://dali.jiagoushi.top/Article/details/gtundktrgo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nwbrower.top/Article/details/gtdexqviih.html

);
来源：http://dali.pycfn.com/Article/details/gtjmedbaeh.html

[Q03] 增加列
来源：http://dali.vqdsnc.cn/Article/details/gtnhxosxoy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.feifeiyinyue.top/Article/details/gtudetvghw.html

[Q04] 修改列类型
来源：http://dali.yongpay.top/Article/details/gtrzwqdcfg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sweek.top/Article/details/gtxrrwgqub.html

[Q05] 重命名列
来源：http://dali.jiagoushi.top/Article/details/gtwecovmos.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gotoacloud.top/Article/details/gtltxcelkf.html

[Q06] 删除列
来源：http://dali.jinqigfzy.top/Article/details/gtfssxjdpt.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.svipenyu.cn/Article/details/gtoyjtouai.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gtmaemfrie.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ydzc1.top/Article/details/gthzduzdhc.html

[Q08] 创建普通索引
来源：http://dali.redwolf501.top/Article/details/gtnztvbfhh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.fzhhl.top/Article/details/gtlfajflpq.html

[Q09] 创建唯一索引
来源：http://dali.dianchejie.cn/Article/details/gtlvahybwo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenzaomai.com/Article/details/gtrpidftwm.html

[Q10] 插入单行
来源：http://dali.xylfe.cn/Article/details/gtjlyxidvz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sysykeji.top/Article/details/gtzdkvrcqt.html

[Q11] 一次插入多行
来源：http://dali.chenjidiqi.icu/Article/details/gtftsdtnin.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.daria6918.cn/Article/details/gticeieect.html

[Q12] 插入后取自增 ID
来源：http://dali.dianchejie.cn/Article/details/gtofwokdsx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shanyushiyangtech.top/Article/details/gtncxvavgn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gaohongyu789.top/Article/details/gtlybyrlkr.html

[Q13] 忽略重复插入
来源：http://dali.sweek.top/Article/details/gtkckchmpv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.guannengcc.top/Article/details/gtbjeyrkcb.html

[Q14] 存在则更新（upsert）
来源：http://dali.fzhhl.top/Article/details/gtnbirjeuq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj20258888.top/Article/details/gtfctpwyug.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ehwqpu.com/Article/details/gtidfxurqs.html

[Q15] 查询全部
来源：http://dali.ehwqpu.com/Article/details/gtmikhroqx.html

SELECT * FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtglgwjhkr.html

[Q16] 查询指定列
来源：http://dali.meibo888.top/Article/details/gtpvsvkpds.html

SELECT id, name FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtylewplec.html

[Q17] 条件查询
来源：http://dali.meibo888.top/Article/details/gtygdhodmd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhixingplan.top/Article/details/gtbcpjafaf.html

[Q18] 模糊匹配
来源：http://dali.hnqzz.top/Article/details/gtzjpvqbyb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shzxlz.cn/Article/details/gtwjskbfce.html

[Q19] 范围查询
来源：http://dali.yanxiufei.cn/Article/details/gtrvcgjqvj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tianlin.xyz/Article/details/gtpnlsnfhg.html

[Q20] IN 列表
来源：http://dali.yj20258888.top/Article/details/gtjdukjkfr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.daxiang520.top/Article/details/gtfdvhisxp.html

[Q21] 空值判断
来源：http://dali.yj20258888.top/Article/details/gtqdgjsimt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hnxiangtu.top/Article/details/gtavuizpxe.html

[Q22] 排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtftbyftdl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.bjfxy.top/Article/details/gtqkpqkctr.html

[Q23] 分页
来源：http://dali.zhengqikj.top/Article/details/gtkgnxvmly.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hammf.cn/Article/details/gtbcnrjvnb.html

[Q24] 去重
来源：http://dali.xziqi.cn/Article/details/gtpdtxulrk.html

SELECT DISTINCT city FROM users;
来源：http://dali.tian-w.cn/Article/details/gtakzmbndc.html

[Q25] 只取前 N 条
来源：http://dali.ehwqpu.com/Article/details/gtiodkoadv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.birdmap.top/Article/details/gtvvpxqguj.html

[Q26] 计数
来源：http://dali.wangdashe.top/Article/details/gtjhwjzdsm.html

SELECT COUNT(*) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqqxbrrxz.html

[Q27] 条件计数
来源：http://dali.shanyushiyangtech.top/Article/details/gtlrcslavm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.guannengcc.top/Article/details/gtpkjjbvqd.html

[Q28] 求和与平均
来源：http://dali.zycfv.cn/Article/details/gtbqonfqvj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtnaerqmuc.html

[Q29] 最大最小值
来源：http://dali.yuxming.cn/Article/details/gtqrpvfkgr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtlhgfzxpq.html

[Q30] 分组统计
来源：http://dali.jqgfzy.top/Article/details/gtwoxywzas.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gtmzpmbgzw.html

[Q31] 分组后过滤
来源：http://dali.haohaochexian.top/Article/details/gtjeopqnbn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hfpthk.cn/Article/details/gtrzvrpury.html

[Q32] 分组拼接字符串
来源：http://dali.cqqwz.cn/Article/details/gtfqcqbvzb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gtsuqzqjwz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cheryme.top/Article/details/gtbinbbhjt.html

[Q33] 多列分组
来源：http://dali.yongpay.top/Article/details/gtdidfoatt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yueranfly.top/Article/details/gtkfgiftuy.html

[Q34] 每组取第一条
来源：http://dali.zycfv.cn/Article/details/gttxhtixqa.html

SELECT * FROM (
来源：http://dali.0kj1m.cn/Article/details/gtsjfuoolh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.vqdsnc.cn/Article/details/gtdswiopcx.html

) t WHERE rn = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtplkkeumv.html

[Q35] 内连接
来源：http://dali.jianghu66.top/Article/details/gtqhemuzmc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sufxvd.cn/Article/details/gtsqgbllam.html

[Q36] 左连接
来源：http://dali.jlsjyb.cn/Article/details/gtrpnhgajq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sufxvd.cn/Article/details/gtzvcydeut.html

[Q37] 右连接
来源：http://dali.ybcxt.top/Article/details/gthokiquan.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shuidangran.top/Article/details/gtmkzhmktd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nanxuanxn.top/Article/details/gtgicjrvns.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcehqmlki.html

[Q39] 自连接（查上下级）
来源：http://dali.hysaishi.cn/Article/details/gtcccoxrfz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.redwolf501.top/Article/details/gtpfxglaoz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yuxming.cn/Article/details/gtkrdgecwm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhiwuduotai.top/Article/details/gtlceifhfy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sweek.top/Article/details/gtvgvbnogt.html

[Q41] 多表连接
来源：http://dali.yongpay.top/Article/details/gtzenhdwge.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.daxiang520.top/Article/details/gtpwuknulq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jiagoushi.top/Article/details/gtuhnwwfzi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yongpay.top/Article/details/gtnxgfxcfs.html

[Q42] 连接条件附加过滤
来源：http://dali.nanxinkj.top/Article/details/gtefrddwam.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hfpthk.cn/Article/details/gtpuwpraez.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.haohaochexian.top/Article/details/gtejbmwews.html

[Q43] 标量子查询
来源：http://dali.redwolf501.top/Article/details/gtoouplvzn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.meibo888.top/Article/details/gtnxphvrmx.html

[Q44] IN 子查询
来源：http://dali.sweek.top/Article/details/gtrljouloi.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.snrcjt.cn/Article/details/gtotmxolph.html

[Q45] EXISTS 判断存在
来源：http://dali.jinqigufen.top/Article/details/gtosfsoqxb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gotoacloud.top/Article/details/gtjufnrrsy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangdashe.top/Article/details/gtyxtjvtad.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgufenzy.top/Article/details/gtjnkgrndn.html

[Q47] 与平均值比较
来源：http://dali.zycfv.cn/Article/details/gtcvlcatfp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hongshengwenyu.top/Article/details/gtuhoqqghb.html


<!-- 参考信息 -->