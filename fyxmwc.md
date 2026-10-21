代发 wailian999

Java: // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtbflxudkd.html

Go:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtxfeudkgo.html

Ruby: arr.permutation.to_a
来源：http://dali.gotoacloud.top/Article/details/gtxnbbjify.html

C#:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtydjiqnch.html

[N09] 栈与队列
来源：http://dali.guannengcc.top/Article/details/gtebfainyf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhongyouzk.top/Article/details/gtihokvgvs.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xziqi.cn/Article/details/gtgigptqdu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jianghu66.top/Article/details/gtcesdnujy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hongshengwenyu.top/Article/details/gtkkqexmhh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.fzhhl.top/Article/details/gtsyrlhjdx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.c1oappe.top/Article/details/gtxwbuopqq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gtkxdlllyi.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ybcxt.top/Article/details/gtljxlnmgw.html

[N10] 链表节点定义
来源：http://dali.mhx1999.top/Article/details/gtpzpzwfsg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.fzhhl.top/Article/details/gtzsumamsq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hywenlv.cn/Article/details/gtshshzdvg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yongpay.top/Article/details/gtsdvaamxt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj20258.top/Article/details/gtdppqmebk.html

Java: class Node { int v; Node next; }
来源：http://dali.nanxinkj.top/Article/details/gtcpyixkqa.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yongpay.top/Article/details/gtvzpnboaz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.9152youxi.cn/Article/details/gtajxcedtr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jianghu66.top/Article/details/gttanfnctl.html

[N11] 二叉树中序遍历
来源：http://dali.xylfe.cn/Article/details/gtanjxpqip.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.0kj1m.cn/Article/details/gtbyrfumhf.html

PHP:  // 手写递归函数
来源：http://dali.kuanghao11.cn/Article/details/gtnkqkhrup.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zycfv.cn/Article/details/gtciscenla.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daria6918.cn/Article/details/gtycfmrfgd.html

Java: // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gtlcoszspx.html

Go:   // 手写递归
来源：http://dali.fengsongda.top/Article/details/gtbizqonkx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gogol.net.cn/Article/details/gtuxbwtayq.html

C#:   // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpuhgcuda.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.smart0.xyz/Article/details/gtbpiacdyx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxerkzfiq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xinyue.icu/Article/details/gtnstzngsc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yvedp.cn/Article/details/gtvsnbdzaf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daria6918.cn/Article/details/gtvpowoyck.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258.top/Article/details/gtojwzgzic.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cashguo.top/Article/details/gtrslibdin.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xuanzx.com/Article/details/gtcrfqdnkf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xziqi.cn/Article/details/gtmgfilqnt.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtejenwufa.html

O. 并发与异步
来源：http://dali.c1oappe.top/Article/details/gtmujxmxhh.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtxmuxnxao.html

[O01] 启动一个线程
来源：http://dali.yuanzhike.top/Article/details/gtblzuywxf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nwbrower.top/Article/details/gtohjjevzk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xinyue.icu/Article/details/gtafyzdlbv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.haohaochexian.top/Article/details/gttkwitdbz.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gtugfumach.html

Java: new Thread(() -> f()).start()
来源：http://dali.tian-w.cn/Article/details/gtaiczpcdc.html

Go:   go f()
来源：http://dali.redwolf501.top/Article/details/gtqjqmqpjg.html

Ruby: Thread.new { f }
来源：http://dali.yonumen.top/Article/details/gtfgefyveb.html

C#:   Task.Run(() => F());
来源：http://dali.jyoumei.cn/Article/details/gteznrybmd.html

[O02] 使用线程池
来源：http://dali.xinyue.icu/Article/details/gtwshzmnam.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xuetiantiany.cn/Article/details/gtmhzptaxh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangshuangyany.cn/Article/details/gtzjbivcqw.html

JS:   // worker_threads 线程池
来源：http://dali.hnxiangtu.top/Article/details/gtwfuhkyjf.html

TS:   // worker_threads 线程池
来源：http://dali.shuidangran.top/Article/details/gtkzqtfhmp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpldpadfy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.tianlin.xyz/Article/details/gtmxsdqqhw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfonwtas.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xuetiantiany.cn/Article/details/gtchpasmps.html

[O03] 加锁保护共享数据
来源：http://dali.shzxlz.cn/Article/details/gtylmeiwvv.html

Py:   with lock: shared += 1
来源：http://dali.tian-w.cn/Article/details/gtedafdrqg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cucudq.cn/Article/details/gtrtabsxpo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ybcxt.top/Article/details/gtmvundyws.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gtddsajvll.html

Java: synchronized (this) { shared++; }
来源：http://dali.ybcxt.top/Article/details/gtihxeawun.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jianghu66.top/Article/details/gtxonsznsa.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yongpay.top/Article/details/gtxkthwiah.html

C#:   lock (gate) { shared++; }
来源：http://dali.haohaochexian.top/Article/details/gttxldmqxf.html

[O04] 定义异步函数并等待
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnucuqjns.html

Py:   async def f():⏎    await g()
来源：http://dali.gogol.net.cn/Article/details/gtzexijzqw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hysaishi.cn/Article/details/gtuyigtmkj.html

JS:   async function f() { await g(); }
来源：http://dali.9152youxi.cn/Article/details/gtvoiqfwuf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtwrsftkos.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtztubhnib.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jqgufenzy.top/Article/details/gthgfeqtbl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.9152youxi.cn/Article/details/gthvjwalub.html

C#:   async Task F() { await G(); }
来源：http://dali.ivvv.top/Article/details/gtexhcmozr.html

[O05] 并发执行并等待全部完成
来源：http://dali.cheryme.top/Article/details/gtaofmdsmx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gotoacloud.top/Article/details/gtnhaonzvd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ybcxt.top/Article/details/gtdncbvgyh.html

JS:   await Promise.all(tasks)
来源：http://dali.zycfv.cn/Article/details/gthychbwik.html

TS:   await Promise.all(tasks)
来源：http://dali.jinqigufen.top/Article/details/gtesvvjbul.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nwbrower.top/Article/details/gtriorhhbv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.wangshuangyany.cn/Article/details/gtrfjmuspr.html

Ruby: threads.map(&:join)
来源：http://dali.hongshengwenyu.top/Article/details/gtriuobzrc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fzhhl.top/Article/details/gtvaaswurl.html

[O06] 使用进程池
来源：http://dali.zdqjudy.top/Article/details/gtlvzuguoo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ywan-chungtsiang.top/Article/details/gturbtcuvw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jiagoushi.top/Article/details/gtuwsyrktr.html

JS:   // child_process / cluster 模块
来源：http://dali.fengsongda.top/Article/details/gtibypnmqy.html

TS:   // child_process / cluster 模块
来源：http://dali.ehwqpu.com/Article/details/gtupevdcbh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shzxlz.cn/Article/details/gtcgesfeae.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.guowangkeji.top/Article/details/gtdjkblpzh.html

Ruby: // fork 块
来源：http://dali.andypj.xyz/Article/details/gtqecyhtky.html

C#:   Parallel.For
来源：http://dali.shanyushiyangtech.top/Article/details/gtfbrlkbuk.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtscevmffp.html

P. 常用工具函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpunyqccu.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtznodnyhd.html

[P01] 生成 UUID
来源：http://dali.wangshuangyany.cn/Article/details/gtmfdnhupf.html

Py:   str(uuid.uuid4())
来源：http://dali.shanyushiyangtech.top/Article/details/gtdebuyquz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sysykeji.top/Article/details/gtqntueema.html

JS:   crypto.randomUUID()
来源：http://dali.sufxvd.cn/Article/details/gtwylabnkk.html

TS:   crypto.randomUUID()
来源：http://dali.cdnleiting.top/Article/details/gtuctushmb.html

Java: UUID.randomUUID().toString()
来源：http://dali.fengsongda.top/Article/details/gtwrzzfmjc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ydzc1.top/Article/details/gtojhcbtpb.html

Ruby: SecureRandom.uuid
来源：http://dali.feifeiyinyue.top/Article/details/gtfvermqmr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhengqikj.top/Article/details/gtmhdelcox.html

[P02] MD5 / SHA256 摘要
来源：http://dali.dashuyun.cn/Article/details/gtvpfycofr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cashguo.top/Article/details/gtalzodubh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.aizwys.cn/Article/details/gtzywkuuoh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.pengpengdd.cyou/Article/details/gtmixahfqw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xylfe.cn/Article/details/gttqvupulj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.svipenyu.cn/Article/details/gtnhiqbmcn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zycfv.cn/Article/details/gtntckkpes.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gtuutifyum.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtferpzxfs.html

[P03] 生成短随机字符串
来源：http://dali.yuanzhike.top/Article/details/gtoigexwwv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.dashuyun.cn/Article/details/gtqdxmqpur.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.meibo888.top/Article/details/gtgipprwtv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zdqjudy.top/Article/details/gtybotpkqh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.redwolf501.top/Article/details/gtrvqiieee.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yueranfly.top/Article/details/gtfpxussnj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.pengpengdd.cyou/Article/details/gtdghztqia.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cdnleiting.top/Article/details/gtzvwczovv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gaohongyu789.top/Article/details/gtzqnrpdis.html

[P04] 求长度
来源：http://dali.sweek.top/Article/details/gtbipynwci.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.aizwys.cn/Article/details/gtuymwdkew.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gthdbplxbn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tianlin.xyz/Article/details/gtnjkkmhrb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ehwqpu.com/Article/details/gtiuwpmjtd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhongyouzk.top/Article/details/gtkholgcqa.html

Go:   len(arr);  len(m)
来源：http://dali.yj20258.top/Article/details/gtbjxvgojf.html

Ruby: x.length;  x.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmyivgjl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jyoumei.cn/Article/details/gtfzrderny.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dashuyun.cn/Article/details/gtvdpvmbmb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jqgufenzy.top/Article/details/gtqmkgxtpi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinghuilouyu.cn/Article/details/gtxyivkpbe.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xylfe.cn/Article/details/gtlqsrenvn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhongyouzk.top/Article/details/gtkctpgqpj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.feifeiyinyue.top/Article/details/gtrahpjwlz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtonjfhllh.html

Ruby: a == b
来源：http://dali.aizwys.cn/Article/details/gtzforrkuz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gtvxgndrox.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xuetiantiany.cn/Article/details/gtgrcjlsir.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hnxiangtu.top/Article/details/gtnuksvlze.html

PHP:  if (empty($x)) {}
来源：http://dali.hfpthk.cn/Article/details/gtrpomehtu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yangfankeji.com/Article/details/gtwhuulnhe.html

TS:   if (x == null) {}
来源：http://dali.yj20258.top/Article/details/gthfzosyrq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj20258888.top/Article/details/gtpbibqbww.html

Go:   if x == nil {}
来源：http://dali.yonumen.top/Article/details/gtlhybngcn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ppjwa.cn/Article/details/gtjztfrlra.html

C#:   if (x is null) {}
来源：http://dali.chenzaomai.com/Article/details/gtqmufhhno.html

[P07] 防抖与节流
来源：http://dali.cqqwz.cn/Article/details/gtaqhynbwn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.fzhhl.top/Article/details/gtlghxrxwx.html

PHP:  // 手写时间戳比较
来源：http://dali.yonumen.top/Article/details/gtodpgenfp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sweek.top/Article/details/gtsiyoiktd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gtlfdoezip.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtanqfbing.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.daxiang520.top/Article/details/gtiqrpuryy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xuetiantiany.cn/Article/details/gtuaflmzqb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.pengpengdd.cyou/Article/details/gtrmylycpr.html

[P08] 处理浮点精度问题
来源：http://dali.cqqwz.cn/Article/details/gtxjafolza.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtafqswrpz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.andypj.xyz/Article/details/gtzntvqcvu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.snrcjt.cn/Article/details/gtwvtgxinp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cucudq.cn/Article/details/gtvqljmwel.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yongpay.top/Article/details/gtsjbyenbz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinyuanbaomall.cn/Article/details/gtstfpmbil.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yuanzhike.top/Article/details/gtvquufqut.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xylfe.cn/Article/details/gtrfxvukgu.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtdsdrfaam.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkirlmxja.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gttjfyehlz.html

[Q01] 创建表
来源：http://dali.wangshuangyany.cn/Article/details/gtlkgulsch.html

CREATE TABLE users (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvswheiu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.bjfxy.top/Article/details/gtwgmliqzx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.quarkkingdee.top/Article/details/gtyvxsprgo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nwbrower.top/Article/details/gtxyhjzxvz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.pycfn.com/Article/details/gtkkambnqn.html

);
来源：http://dali.tianlin.xyz/Article/details/gtxcoljqsk.html

[Q02] 创建带外键的表
来源：http://dali.gotoacloud.top/Article/details/gtyfbqpupd.html

CREATE TABLE orders (
来源：http://dali.ydzc1.top/Article/details/gtsltqhhsb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cdnleiting.top/Article/details/gttijhoubh.html

user_id INT NOT NULL,
来源：http://dali.chenzaomai.com/Article/details/gtdfjwnebd.html

amount DECIMAL(10, 2),
来源：http://dali.ivvv.top/Article/details/gtgevbnrbu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.pengpengdd.cyou/Article/details/gtfkzjiiwz.html

);
来源：http://dali.quarkkingdee.top/Article/details/gtyoicgcrp.html

[Q03] 增加列
来源：http://dali.xylfe.cn/Article/details/gttaufeqdl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.birdmap.top/Article/details/gtqacipcxh.html

[Q04] 修改列类型
来源：http://dali.nwbrower.top/Article/details/gtnhudbszj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ppjwa.cn/Article/details/gtvqbtkiok.html

[Q05] 重命名列
来源：http://dali.xinyue.icu/Article/details/gtilqaqpxm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.fzhhl.top/Article/details/gtovpqjvut.html

[Q06] 删除列
来源：http://dali.jlsjyb.cn/Article/details/gtptdrdjfh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gaohongyu789.top/Article/details/gtnbipkmeo.html

[Q07] 删除表
来源：http://dali.hongshengwenyu.top/Article/details/gtobzvrrvd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gzhubu.top/Article/details/gttchsbdvp.html

[Q08] 创建普通索引
来源：http://dali.xylfe.cn/Article/details/gtilzlajgv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jyoumei.cn/Article/details/gtzddwhtdo.html

[Q09] 创建唯一索引
来源：http://dali.wangshuangyany.cn/Article/details/gttgjkknbu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgmlevyjj.html

[Q10] 插入单行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbfbnqyhs.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.birdmap.top/Article/details/gtzjhsfzyh.html

[Q11] 一次插入多行
来源：http://dali.hnqzz.top/Article/details/gthlapcltt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gthucroarg.html

[Q12] 插入后取自增 ID
来源：http://dali.wangshuangyany.cn/Article/details/gtrajuaaus.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tianlin.xyz/Article/details/gtlnnwlrhv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.haohaochexian.top/Article/details/gtqdxadnbs.html

[Q13] 忽略重复插入
来源：http://dali.9152youxi.cn/Article/details/gtpdlclnqh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gtjibguotd.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbinkykdb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jianghu66.top/Article/details/gtsysbecaz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yangfankeji.com/Article/details/gtcdnrdplt.html

[Q15] 查询全部
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxtagmrz.html

SELECT * FROM users;
来源：http://dali.daria6918.cn/Article/details/gtkgtljepm.html

[Q16] 查询指定列
来源：http://dali.ppjwa.cn/Article/details/gtxrygarjc.html

SELECT id, name FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtrjwawtqx.html

[Q17] 条件查询
来源：http://dali.jlsjyb.cn/Article/details/gtfaddkdqe.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hammf.cn/Article/details/gtwcgqcius.html

[Q18] 模糊匹配
来源：http://dali.jlsjyb.cn/Article/details/gtrozykymq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gogol.net.cn/Article/details/gtyoghmbpj.html

[Q19] 范围查询
来源：http://dali.fzhhl.top/Article/details/gtallspcgc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.0kj1m.cn/Article/details/gtftxjfqdt.html

[Q20] IN 列表
来源：http://dali.hnqzz.top/Article/details/gtvisalslk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sufxvd.cn/Article/details/gtwntbisaw.html

[Q21] 空值判断
来源：http://dali.0kj1m.cn/Article/details/gtqsyylrxk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdejdlubb.html

[Q22] 排序
来源：http://dali.wangdashe.top/Article/details/gtczdzzrsb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hnqzz.top/Article/details/gtcqeffphu.html

[Q23] 分页
来源：http://dali.meibo888.top/Article/details/gtpsamixwk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yanxiufei.cn/Article/details/gtmhrllbzy.html

[Q24] 去重
来源：http://dali.yj202588.top/Article/details/gtjoijejng.html

SELECT DISTINCT city FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtexrxtcox.html

[Q25] 只取前 N 条
来源：http://dali.yj20258888.top/Article/details/gtcsvogiaa.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gaohongyu789.top/Article/details/gtkltiqufw.html

[Q26] 计数
来源：http://dali.meibo888.top/Article/details/gtbvalcvrr.html

SELECT COUNT(*) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtglglwigu.html

[Q27] 条件计数
来源：http://dali.havefunace.top/Article/details/gtiyyolqdc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hnqzz.top/Article/details/gtjskdqitd.html

[Q28] 求和与平均
来源：http://dali.yuxming.cn/Article/details/gtxcjygcfu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtrdaccctz.html

[Q29] 最大最小值
来源：http://dali.shangyingyoupin.top/Article/details/gtbtxwvzyb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtffdggvni.html

[Q30] 分组统计
来源：http://dali.dianchejie.cn/Article/details/gtnpshckcv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gtpdaaidkk.html

[Q31] 分组后过滤
来源：http://dali.gogol.net.cn/Article/details/gtbhapsdmf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ehwqpu.com/Article/details/gttxrwftnm.html

[Q32] 分组拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gtkxcutqlr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gtemscltoc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmuhylcz.html

[Q33] 多列分组
来源：http://dali.chenlongwang.top/Article/details/gtyxivjsbk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhongyouzk.top/Article/details/gtukcssojt.html

[Q34] 每组取第一条
来源：http://dali.chenlongwang.top/Article/details/gtpwlrogka.html

SELECT * FROM (
来源：http://dali.jqgfzy.top/Article/details/gttfwzkpjr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sysykeji.top/Article/details/gthfsgygoh.html

) t WHERE rn = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuktkxtou.html

[Q35] 内连接
来源：http://dali.birdmap.top/Article/details/gtoskxkpoq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gaohongyu789.top/Article/details/gtktcktlnd.html

[Q36] 左连接
来源：http://dali.xinyue.icu/Article/details/gtsjggujqp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ehwqpu.com/Article/details/gtgztmdhly.html

[Q37] 右连接
来源：http://dali.tanke756.top/Article/details/gtglrqbiwz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shanyushiyangtech.top/Article/details/gttslzatae.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhiwuduotai.top/Article/details/gtfvrpvqam.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhengqikj.top/Article/details/gtrjwlmeud.html

[Q39] 自连接（查上下级）
来源：http://dali.andypj.xyz/Article/details/gtavlocsbp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yj20258888.top/Article/details/gtwxhxfihp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjefqjdtm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xziqi.cn/Article/details/gtreeipcfg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.316326.xyz/Article/details/gtnqneutxy.html

[Q41] 多表连接
来源：http://dali.andypj.xyz/Article/details/gtdqdjkyqz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hfpthk.cn/Article/details/gtmpiprqcu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nanxinkj.top/Article/details/gtaitvskly.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.redwolf501.top/Article/details/gtaczlzkth.html

[Q42] 连接条件附加过滤
来源：http://dali.jiagoushi.top/Article/details/gtcrstsxaa.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cheryme.top/Article/details/gtffngrqov.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yangfankeji.com/Article/details/gtywfxdfhi.html

[Q43] 标量子查询
来源：http://dali.yuxming.cn/Article/details/gtpjqnwpsl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shuidangran.top/Article/details/gtchcgyhrk.html

[Q44] IN 子查询
来源：http://dali.ybcxt.top/Article/details/gtyzvlfbku.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhoulong.xyz/Article/details/gtdrdwpuid.html

[Q45] EXISTS 判断存在
来源：http://dali.daxiang520.top/Article/details/gtnkllwwgc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuanzhike.top/Article/details/gtntxqzgro.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cqqwz.cn/Article/details/gttxifutxe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guowangkeji.top/Article/details/gtmpdaesgw.html

[Q47] 与平均值比较
来源：http://dali.chenlongwang.top/Article/details/gtoirbgsbh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.dianchejie.cn/Article/details/gtvwmiwwyp.html

[Q48] CTE 公用表表达式
来源：http://dali.yueranfly.top/Article/details/gtsnyohxwh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.haohaochexian.top/Article/details/gtqcxhghla.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmcbkqom.html

[Q49] 更新单行
来源：http://dali.andypj.xyz/Article/details/gtcazsradi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.svipenyu.cn/Article/details/gtemxgdwft.html

[Q50] 批量更新
来源：http://dali.shangyingyoupin.top/Article/details/gthjhoertv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tanke756.top/Article/details/gtvokwwwsp.html

[Q51] 用子查询更新
来源：http://dali.ppjwa.cn/Article/details/gtcuqzlkwq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yj202588.top/Article/details/gtujojmsoa.html

[Q52] 删除指定行
来源：http://dali.shangyingyoupin.top/Article/details/gtgyiljdrj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jyoumei.cn/Article/details/gtzqkghlkj.html

[Q53] 按条件删除
来源：http://dali.yanxiufei.cn/Article/details/gtflcwnkkn.html


<!-- 参考信息 -->