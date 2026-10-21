代发 wailian999

Py:   itertools.permutations(arr)
来源：http://dali.wangdashe.top/Article/details/gtgvvvzbye.html

PHP:  // 手写递归交换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrctnlgii.html

JS:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtbjhdrxta.html

TS:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gtncsltoej.html

Java: // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtaclxdxns.html

Go:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtychutusx.html

Ruby: arr.permutation.to_a
来源：http://dali.ybcxt.top/Article/details/gtspraolrw.html

C#:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtxhkwnuqq.html

[N09] 栈与队列
来源：http://dali.gotoacloud.top/Article/details/gtjyhrjnxe.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daria6918.cn/Article/details/gtmyzfklbw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gtmmvjlsbw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gttlefkcly.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjhaozlh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shangyingyoupin.top/Article/details/gtwctzevna.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ydzc1.top/Article/details/gttcckhcir.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpyifnlvs.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtupycohne.html

[N10] 链表节点定义
来源：http://dali.jinqigufen.top/Article/details/gtmegpmokf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yangfankeji.com/Article/details/gtmrbfcest.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hnxiangtu.top/Article/details/gtvvvueziz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkaauuala.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrkowzog.html

Java: class Node { int v; Node next; }
来源：http://dali.pengpengdd.cyou/Article/details/gtwefgdbcq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hfpthk.cn/Article/details/gtearckdvo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yvedp.cn/Article/details/gtyiqfback.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tianlin.xyz/Article/details/gtgcppocgo.html

[N11] 二叉树中序遍历
来源：http://dali.jinqigfzy.top/Article/details/gtrcehirwd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.meibo888.top/Article/details/gtgckiftyz.html

PHP:  // 手写递归函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtinbklrmk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fzhhl.top/Article/details/gtavnyyqyo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aibaodan.cn/Article/details/gtbggfqszg.html

Java: // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gtjsjpedwd.html

Go:   // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gtyywicwdw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yuxming.cn/Article/details/gtugtooobg.html

C#:   // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gtrfvcnczx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yongpay.top/Article/details/gtllwxzgkv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenzaomai.com/Article/details/gtfppuuimg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nanxinkj.top/Article/details/gtxiveqxla.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ydzc1.top/Article/details/gttmtonoqm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ivvv.top/Article/details/gtderazviu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pengpengdd.cyou/Article/details/gtkolxestu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.bjfxy.top/Article/details/gtxsfkzzmd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.fzhhl.top/Article/details/gtvfoqzkjl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cucudq.cn/Article/details/gtompttaar.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtdjclcrel.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gtcoutpkuu.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtrbsnrtst.html

[O01] 启动一个线程
来源：http://dali.kuanghao11.cn/Article/details/gtpjhuyfaz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sysykeji.top/Article/details/gtdeufpaik.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.fzhhl.top/Article/details/gtrjpjgwin.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cdnleiting.top/Article/details/gtynszscgh.html

TS:   // 同 JS
来源：http://dali.yueranfly.top/Article/details/gtalfhrcgv.html

Java: new Thread(() -> f()).start()
来源：http://dali.xylfe.cn/Article/details/gtniajstab.html

Go:   go f()
来源：http://dali.fzhhl.top/Article/details/gtcwsoefgz.html

Ruby: Thread.new { f }
来源：http://dali.daria6918.cn/Article/details/gtcilxhryo.html

C#:   Task.Run(() => F());
来源：http://dali.tian-w.cn/Article/details/gtbdcjpyzg.html

[O02] 使用线程池
来源：http://dali.cqqwz.cn/Article/details/gtloiogiyv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cheryme.top/Article/details/gtempsqbff.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gtscjafbuc.html

JS:   // worker_threads 线程池
来源：http://dali.tanke756.top/Article/details/gtnwfyethv.html

TS:   // worker_threads 线程池
来源：http://dali.xinyue.icu/Article/details/gthedbdehz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinqigufen.top/Article/details/gtntygoont.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jlsjyb.cn/Article/details/gteorcvswq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.aizwys.cn/Article/details/gthzzobjsf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sweek.top/Article/details/gtbpawyqnt.html

[O03] 加锁保护共享数据
来源：http://dali.sufxvd.cn/Article/details/gtpepadghk.html

Py:   with lock: shared += 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqrdzfaoi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.svipenyu.cn/Article/details/gtlccwbncz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zdqjudy.top/Article/details/gtbeylkpxy.html

TS:   // 同 JS
来源：http://dali.guowangkeji.top/Article/details/gtpohjsrah.html

Java: synchronized (this) { shared++; }
来源：http://dali.aibaodan.cn/Article/details/gtxtiyvtzw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.daxiang520.top/Article/details/gtecnimhjc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zycfv.cn/Article/details/gtzlfovccn.html

C#:   lock (gate) { shared++; }
来源：http://dali.cheryme.top/Article/details/gtjfxixqjq.html

[O04] 定义异步函数并等待
来源：http://dali.ydzc1.top/Article/details/gtrqsfnfcf.html

Py:   async def f():⏎    await g()
来源：http://dali.vqdsnc.cn/Article/details/gtxldmqggh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jyoumei.cn/Article/details/gtowngxhqy.html

JS:   async function f() { await g(); }
来源：http://dali.sweek.top/Article/details/gttzoopuoe.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.smart0.xyz/Article/details/gtgxvysszv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ppjwa.cn/Article/details/gtcdtaaqkw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinghuilouyu.cn/Article/details/gtjhrckxgd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.iojbl.cn/Article/details/gtzyogrmol.html

C#:   async Task F() { await G(); }
来源：http://dali.jiagoushi.top/Article/details/gtabeufvpf.html

[O05] 并发执行并等待全部完成
来源：http://dali.nanxuanxn.top/Article/details/gtdxjsvjsm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xuanzx.com/Article/details/gtauysuzbz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhixingplan.top/Article/details/gtmuwiitqw.html

JS:   await Promise.all(tasks)
来源：http://dali.bjfxy.top/Article/details/gtzofgefxd.html

TS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gtnquenrit.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.316326.xyz/Article/details/gtkyhxfxwl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.aibaodan.cn/Article/details/gtdvosrynl.html

Ruby: threads.map(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gtwtiaaeht.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yuxming.cn/Article/details/gtqgjjsisb.html

[O06] 使用进程池
来源：http://dali.yongpay.top/Article/details/gteepnhjel.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yuanzhike.top/Article/details/gtrnmnuapw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.quarkkingdee.top/Article/details/gthxybpqec.html

JS:   // child_process / cluster 模块
来源：http://dali.xuanzx.com/Article/details/gtijbpgkks.html

TS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gtxzovfhdo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gthcwlijjn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj202588.top/Article/details/gtqdajorzy.html

Ruby: // fork 块
来源：http://dali.wangdashe.top/Article/details/gtdlczbtri.html

C#:   Parallel.For
来源：http://dali.nanxuanxn.top/Article/details/gtdaifcidi.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtiteelwyb.html

P. 常用工具函数
来源：http://dali.ppjwa.cn/Article/details/gteshfadfi.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtouspypzc.html

[P01] 生成 UUID
来源：http://dali.aizwys.cn/Article/details/gtnhgncjmu.html

Py:   str(uuid.uuid4())
来源：http://dali.andypj.xyz/Article/details/gtbvaiqblj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ivvv.top/Article/details/gtoidqsaov.html

JS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gtemmthbhk.html

TS:   crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gtiiywtiqt.html

Java: UUID.randomUUID().toString()
来源：http://dali.sweek.top/Article/details/gtkqnyzbiv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sxryk.cn/Article/details/gtwpaefnfc.html

Ruby: SecureRandom.uuid
来源：http://dali.chenjidiqi.icu/Article/details/gtgjerxewm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinqigfzy.top/Article/details/gtajiapkae.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yvedp.cn/Article/details/gtbmkrtzpm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gaohongyu789.top/Article/details/gtyagqwiel.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.dashuyun.cn/Article/details/gtifknqxoc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xziqi.cn/Article/details/gtroiolobk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.smart0.xyz/Article/details/gtlkrsfczv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.havefunace.top/Article/details/gtslxblrfb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinqigfzy.top/Article/details/gtzglukwgo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.c1oappe.top/Article/details/gtfminegzz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jiagoushi.top/Article/details/gtbidzulzf.html

[P03] 生成短随机字符串
来源：http://dali.yonumen.top/Article/details/gtfsvcecsz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.kuanghao11.cn/Article/details/gtyjbsmkxz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hywenlv.cn/Article/details/gtsdgyismf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yongpay.top/Article/details/gtwkqkugnu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yongpay.top/Article/details/gtxmahcxxc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhongyouzk.top/Article/details/gtiqchchhh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hongshengwenyu.top/Article/details/gtylmfaabq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.smart0.xyz/Article/details/gtdlnmrxbe.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.wangshuangyany.cn/Article/details/gtqdwssjrh.html

[P04] 求长度
来源：http://dali.svipenyu.cn/Article/details/gtrhblffri.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gaohongyu789.top/Article/details/gtsxfzodku.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpsfbjswg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.bjfxy.top/Article/details/gtfygmmaof.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cashguo.top/Article/details/gtbwhjtbie.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhixingplan.top/Article/details/gtzpndiydj.html

Go:   len(arr);  len(m)
来源：http://dali.zhoulong.xyz/Article/details/gtniqnlmax.html

Ruby: x.length;  x.size
来源：http://dali.gotoacloud.top/Article/details/gtjwcredrv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shzxlz.cn/Article/details/gtsshonqik.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hywenlv.cn/Article/details/gtzapzymve.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jlsjyb.cn/Article/details/gtiwymwyuy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sxryk.cn/Article/details/gtrttpjomp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.feifeiyinyue.top/Article/details/gtapqqqwfa.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnxiangtu.top/Article/details/gtalztumvs.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xuetiantiany.cn/Article/details/gtuavtixqx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gthxexznul.html

Ruby: a == b
来源：http://dali.jyoumei.cn/Article/details/gtsjfdhwbe.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yuanzhike.top/Article/details/gtfmdbrfna.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.meibo888.top/Article/details/gtaozdjfji.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.316326.xyz/Article/details/gtxccopquj.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gtcrgdnlkd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hfpthk.cn/Article/details/gtfwnlfxzk.html

TS:   if (x == null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtplnqimom.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtwsfhcbhl.html

Go:   if x == nil {}
来源：http://dali.xinyue.icu/Article/details/gtavktgzgr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.guannengcc.top/Article/details/gtvhxptvgm.html

C#:   if (x is null) {}
来源：http://dali.aizwys.cn/Article/details/gtbmysagja.html

[P07] 防抖与节流
来源：http://dali.daxiang520.top/Article/details/gtrcnewxbx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cheryme.top/Article/details/gtmseiktjz.html

PHP:  // 手写时间戳比较
来源：http://dali.yonumen.top/Article/details/gtuehvnasm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.0kj1m.cn/Article/details/gttgggehby.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnxiangtu.top/Article/details/gtwwlsvmtl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtkjkgzjzh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.wangdashe.top/Article/details/gtmxziyqjc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.haohaochexian.top/Article/details/gtqenedlaj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj202588.top/Article/details/gtbnvvjhqo.html

[P08] 处理浮点精度问题
来源：http://dali.jianghu66.top/Article/details/gtnlvxwppn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinqigufen.top/Article/details/gtmhtufmbc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.fzhhl.top/Article/details/gtxxqerbbi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sxryk.cn/Article/details/gtsrmizbff.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.nanxuanxn.top/Article/details/gtbqiwsjxr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ybcxt.top/Article/details/gtenggzbrh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.smart0.xyz/Article/details/gtwfjtmesw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.9152youxi.cn/Article/details/gtjhzdnxqc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdmahjshs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtcjzkzvkp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhixingplan.top/Article/details/gtuumbxltt.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzgrpfjf.html

[Q01] 创建表
来源：http://dali.hammf.cn/Article/details/gtbrvpzpqt.html

CREATE TABLE users (
来源：http://dali.mhx1999.top/Article/details/gtprfdlhev.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangshuangyany.cn/Article/details/gteztlaoga.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yangfankeji.com/Article/details/gtwddmdfgk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.fzhhl.top/Article/details/gtxamvwoex.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hammf.cn/Article/details/gtxuuclqzy.html

);
来源：http://dali.zhijiandao.cn/Article/details/gtmjvrimyi.html

[Q02] 创建带外键的表
来源：http://dali.zhengqikj.top/Article/details/gtoavtsxeb.html

CREATE TABLE orders (
来源：http://dali.ppjwa.cn/Article/details/gtefzljued.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.iojbl.cn/Article/details/gtknsgznoi.html

user_id INT NOT NULL,
来源：http://dali.nanxuanxn.top/Article/details/gtzzhuzrqa.html

amount DECIMAL(10, 2),
来源：http://dali.quarkkingdee.top/Article/details/gtrokujphi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shuidangran.top/Article/details/gtljwsnfqa.html

);
来源：http://dali.daria6918.cn/Article/details/gtklqpbygm.html

[Q03] 增加列
来源：http://dali.xinyue.icu/Article/details/gtcqeuxhsk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.aizwys.cn/Article/details/gtvgzqdwhu.html

[Q04] 修改列类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteihyhpyn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cheryme.top/Article/details/gtqhprtjof.html

[Q05] 重命名列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlfpolgdk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yangfankeji.com/Article/details/gtohfvhgbu.html

[Q06] 删除列
来源：http://dali.gogol.net.cn/Article/details/gtvbcipwps.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.guowangkeji.top/Article/details/gtwuhuzhgo.html

[Q07] 删除表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdusjbpkg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtykxvxtbn.html

[Q08] 创建普通索引
来源：http://dali.hnxiangtu.top/Article/details/gtzxxoezie.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.c1oappe.top/Article/details/gtzlorkcrk.html

[Q09] 创建唯一索引
来源：http://dali.wangdashe.top/Article/details/gtynczylkn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinqigfzy.top/Article/details/gtgxkljtmy.html

[Q10] 插入单行
来源：http://dali.yonumen.top/Article/details/gtojmxnhpc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shzxlz.cn/Article/details/gtkakfdwfn.html

[Q11] 一次插入多行
来源：http://dali.sufxvd.cn/Article/details/gtubqoswbm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shzxlz.cn/Article/details/gtoqbnbpak.html

[Q12] 插入后取自增 ID
来源：http://dali.ehwqpu.com/Article/details/gtrjotuwdg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gotoacloud.top/Article/details/gtsxybbejr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hywenlv.cn/Article/details/gtrbepcdrk.html

[Q13] 忽略重复插入
来源：http://dali.cdnleiting.top/Article/details/gtdilepmno.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xinyue.icu/Article/details/gtxvhmjbkj.html

[Q14] 存在则更新（upsert）
来源：http://dali.xinyue.icu/Article/details/gttbivekmm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.snrcjt.cn/Article/details/gtfqdotjwl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.bjfxy.top/Article/details/gttdlmvlju.html

[Q15] 查询全部
来源：http://dali.jinqigfzy.top/Article/details/gtvbjqzkep.html

SELECT * FROM users;
来源：http://dali.hysaishi.cn/Article/details/gthivcumcx.html

[Q16] 查询指定列
来源：http://dali.tanke756.top/Article/details/gtulvzolpg.html

SELECT id, name FROM users;
来源：http://dali.ydzc1.top/Article/details/gtrtozqynm.html

[Q17] 条件查询
来源：http://dali.wangshuangyany.cn/Article/details/gtvifeomen.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tian-w.cn/Article/details/gtxgttguyk.html

[Q18] 模糊匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtysovuezb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.guowangkeji.top/Article/details/gtttpsuzvr.html

[Q19] 范围查询
来源：http://dali.yongpay.top/Article/details/gtepdrguou.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ybcxt.top/Article/details/gtombbmkgs.html

[Q20] IN 列表
来源：http://dali.xuetiantiany.cn/Article/details/gtzfjnyjhu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cucudq.cn/Article/details/gtxcuzebrw.html

[Q21] 空值判断
来源：http://dali.xylfe.cn/Article/details/gtzydcodqy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.bjfxy.top/Article/details/gtmpplqhdz.html

[Q22] 排序
来源：http://dali.pengpengdd.cyou/Article/details/gtnyakgavx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hywenlv.cn/Article/details/gtwwhvmeuj.html

[Q23] 分页
来源：http://dali.kuanghao11.cn/Article/details/gtnvnkawlw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.316326.xyz/Article/details/gtetdrvlrb.html

[Q24] 去重
来源：http://dali.cdnleiting.top/Article/details/gtzndybjcf.html

SELECT DISTINCT city FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtkbatdqtk.html

[Q25] 只取前 N 条
来源：http://dali.jyoumei.cn/Article/details/gtxctshgid.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinyuanbaomall.cn/Article/details/gtctaxrczk.html

[Q26] 计数
来源：http://dali.meibo888.top/Article/details/gtfanewgop.html

SELECT COUNT(*) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtxuufmrhk.html

[Q27] 条件计数
来源：http://dali.yanxiufei.cn/Article/details/gtjolruyob.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gzhubu.top/Article/details/gthqgqwnyz.html

[Q28] 求和与平均
来源：http://dali.ppjwa.cn/Article/details/gtkwyweffj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtdbgtgrbm.html

[Q29] 最大最小值
来源：http://dali.zhixingplan.top/Article/details/gtcwyawlaf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtthutsadr.html

[Q30] 分组统计
来源：http://dali.chenjidiqi.icu/Article/details/gtjwbyxnjx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gtiqyqzdhs.html

[Q31] 分组后过滤
来源：http://dali.tianlin.xyz/Article/details/gtxxyqkjzw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.9152youxi.cn/Article/details/gtjegxrusb.html

[Q32] 分组拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gtvyqowzda.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gtyeqsdgsv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tanke756.top/Article/details/gtmezzuxpu.html

[Q33] 多列分组
来源：http://dali.xylfe.cn/Article/details/gtmagdmxaf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xziqi.cn/Article/details/gtkhxgznuv.html

[Q34] 每组取第一条
来源：http://dali.yvedp.cn/Article/details/gttbxgwyyc.html

SELECT * FROM (
来源：http://dali.zdqjudy.top/Article/details/gtayfvkkzz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hfpthk.cn/Article/details/gtxalqcnnz.html

) t WHERE rn = 1;
来源：http://dali.9152youxi.cn/Article/details/gtwgytggfc.html

[Q35] 内连接
来源：http://dali.zhongyouzk.top/Article/details/gtbhlklrdp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gzhubu.top/Article/details/gtazpcqkgd.html

[Q36] 左连接
来源：http://dali.cheryme.top/Article/details/gtutzortnc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gotoacloud.top/Article/details/gtyxncgviv.html

[Q37] 右连接
来源：http://dali.dianchejie.cn/Article/details/gtsnusithi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.dianchejie.cn/Article/details/gtuieuuosq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtftnxrjum.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cashguo.top/Article/details/gtuxjsawul.html

[Q39] 自连接（查上下级）
来源：http://dali.tanke756.top/Article/details/gtvkaqqurx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jianghu66.top/Article/details/gtvvmapvqa.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shzxlz.cn/Article/details/gtcvslajea.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.quarkkingdee.top/Article/details/gtgnimdewn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.guannengcc.top/Article/details/gtrwchmeup.html

[Q41] 多表连接
来源：http://dali.gotoacloud.top/Article/details/gthhbszgvu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.tianlin.xyz/Article/details/gtxqrzlugw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xuanzx.com/Article/details/gtnjnjvyzy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sysykeji.top/Article/details/gtloxtldre.html

[Q42] 连接条件附加过滤
来源：http://dali.fzhhl.top/Article/details/gtdiulegqp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj20258888.top/Article/details/gtfvuicmvc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jianghu66.top/Article/details/gtrpqsqofd.html

[Q43] 标量子查询
来源：http://dali.cheryme.top/Article/details/gtvvfftoqh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yonumen.top/Article/details/gtfidlxivp.html

[Q44] IN 子查询
来源：http://dali.feifeiyinyue.top/Article/details/gtosvsjmhs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvcxkrmp.html

[Q45] EXISTS 判断存在
来源：http://dali.zhoulong.xyz/Article/details/gtvwdhlknx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cucudq.cn/Article/details/gtxqonqrtg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenjidiqi.icu/Article/details/gtarzuhnoq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fzhhl.top/Article/details/gtynavqmyb.html

[Q47] 与平均值比较
来源：http://dali.c1oappe.top/Article/details/gtaqzpmsdn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nanxuanxn.top/Article/details/gtyancwyqo.html

[Q48] CTE 公用表表达式
来源：http://dali.fengsongda.top/Article/details/gtmiggapsi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhiwuduotai.top/Article/details/gtjqeibiaa.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinghuilouyu.cn/Article/details/gtyplsrhap.html

[Q49] 更新单行
来源：http://dali.mhx1999.top/Article/details/gthauuhrxs.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yuxming.cn/Article/details/gtfyxvbynm.html

[Q50] 批量更新
来源：http://dali.haohaochexian.top/Article/details/gtdvkxsvak.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.chenjidiqi.icu/Article/details/gtzgopakzg.html

[Q51] 用子查询更新
来源：http://dali.yuxming.cn/Article/details/gtnqglubbz.html


<!-- 参考信息 -->