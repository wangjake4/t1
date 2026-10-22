代发 wailian999

[N09] 栈与队列
来源：http://dali.xziqi.cn/Article/details/gtquvsdlxt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zycfv.cn/Article/details/gttsrayqsv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gtvfapfcvv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.aizwys.cn/Article/details/gtfotwfrrx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhiwuduotai.top/Article/details/gtcjekidgu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.snrcjt.cn/Article/details/gtismstjdd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gzhubu.top/Article/details/gtzfjelgfc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.daria6918.cn/Article/details/gtrfmldqpv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhoulong.xyz/Article/details/gtjlwihvci.html

[N10] 链表节点定义
来源：http://dali.hongshengwenyu.top/Article/details/gtqpzrlhsy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhengqikj.top/Article/details/gtsoaglahh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhongyouzk.top/Article/details/gtlmowbfjd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.wangdashe.top/Article/details/gtnbhdgqnt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shuidangran.top/Article/details/gtyxbnknry.html

Java: class Node { int v; Node next; }
来源：http://dali.zdqjudy.top/Article/details/gtozuqmjfg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hnxiangtu.top/Article/details/gtlrqdbdgt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.316326.xyz/Article/details/gtgmomxjps.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sufxvd.cn/Article/details/gtrbhwxeab.html

[N11] 二叉树中序遍历
来源：http://dali.xylfe.cn/Article/details/gtggwbfoiu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sufxvd.cn/Article/details/gtqtxvizub.html

PHP:  // 手写递归函数
来源：http://dali.shangyingyoupin.top/Article/details/gtjuspafih.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258.top/Article/details/gtjayajzsh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cdnleiting.top/Article/details/gtuebjrbyw.html

Java: // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gtqasidbxd.html

Go:   // 手写递归
来源：http://dali.birdmap.top/Article/details/gtsebxnrrm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tianlin.xyz/Article/details/gtczxovmxc.html

C#:   // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gtwaeshmoc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sysykeji.top/Article/details/gtkxtutkcg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cheryme.top/Article/details/gtleolyqrr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.fengsongda.top/Article/details/gtwgzxqzjq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cheryme.top/Article/details/gtkkrvvskg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cheryme.top/Article/details/gtrwmhcstg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.9152youxi.cn/Article/details/gtoikgytvw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gzhubu.top/Article/details/gtbbkzbjmq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.havefunace.top/Article/details/gtniworlsh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhoulong.xyz/Article/details/gtuwboabai.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtfugevepe.html

O. 并发与异步
来源：http://dali.cashguo.top/Article/details/gtkoyftumu.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gthdlasqsi.html

[O01] 启动一个线程
来源：http://dali.hongshengwenyu.top/Article/details/gtekvlwytx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yj202588.top/Article/details/gtoqwfhfcj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.haohaochexian.top/Article/details/gtzxylhozs.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuhyrssnr.html

TS:   // 同 JS
来源：http://dali.tanke756.top/Article/details/gttekpbuoi.html

Java: new Thread(() -> f()).start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtrylopa.html

Go:   go f()
来源：http://dali.yj202588.top/Article/details/gtengwgfdg.html

Ruby: Thread.new { f }
来源：http://dali.iojbl.cn/Article/details/gtenboyypo.html

C#:   Task.Run(() => F());
来源：http://dali.chenlongwang.top/Article/details/gtfwuzygdt.html

[O02] 使用线程池
来源：http://dali.hnxiangtu.top/Article/details/gteqdrmkwv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aibaodan.cn/Article/details/gtzqohmijv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.0kj1m.cn/Article/details/gtxhjmozsb.html

JS:   // worker_threads 线程池
来源：http://dali.yanxiufei.cn/Article/details/gtocxgoepk.html

TS:   // worker_threads 线程池
来源：http://dali.zhoulong.xyz/Article/details/gtsptcqvea.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nanxuanxn.top/Article/details/gtrayeymtb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.0kj1m.cn/Article/details/gtpcjopklm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj20258.top/Article/details/gthibpjcfq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj20258888.top/Article/details/gtregrfuwi.html

[O03] 加锁保护共享数据
来源：http://dali.hysaishi.cn/Article/details/gtyqatpfkx.html

Py:   with lock: shared += 1
来源：http://dali.cashguo.top/Article/details/gtttysffij.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shangyingyoupin.top/Article/details/gtrgnhqfql.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hywenlv.cn/Article/details/gtvytrbfjx.html

TS:   // 同 JS
来源：http://dali.sysykeji.top/Article/details/gteyxiwtgc.html

Java: synchronized (this) { shared++; }
来源：http://dali.dianchejie.cn/Article/details/gtujqkhjus.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.vqdsnc.cn/Article/details/gtqykeqwye.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jiagoushi.top/Article/details/gtnytjwztc.html

C#:   lock (gate) { shared++; }
来源：http://dali.tian-w.cn/Article/details/gtbiklfejz.html

[O04] 定义异步函数并等待
来源：http://dali.hysaishi.cn/Article/details/gtcqcqtgcl.html

Py:   async def f():⏎    await g()
来源：http://dali.smart0.xyz/Article/details/gtyxsljfyq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nanxinkj.top/Article/details/gtviagpxqm.html

JS:   async function f() { await g(); }
来源：http://dali.cashguo.top/Article/details/gtsgsxfjpq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sweek.top/Article/details/gtwlrtvodu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gotoacloud.top/Article/details/gtperhmrxg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ybcxt.top/Article/details/gtkaggduja.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sysykeji.top/Article/details/gtekzekawb.html

C#:   async Task F() { await G(); }
来源：http://dali.zhoulong.xyz/Article/details/gthhmgdnvs.html

[O05] 并发执行并等待全部完成
来源：http://dali.hongshengwenyu.top/Article/details/gtqtxrzkja.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gogol.net.cn/Article/details/gtdienadil.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.dianchejie.cn/Article/details/gtesmcbdqz.html

JS:   await Promise.all(tasks)
来源：http://dali.kuanghao11.cn/Article/details/gtnjyesggk.html

TS:   await Promise.all(tasks)
来源：http://dali.yj20258.top/Article/details/gtbvlqcmbn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhengqikj.top/Article/details/gtsdkfptbx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinqigufen.top/Article/details/gtzytszgte.html

Ruby: threads.map(&:join)
来源：http://dali.birdmap.top/Article/details/gtlpwhzfum.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yonumen.top/Article/details/gtvcewcato.html

[O06] 使用进程池
来源：http://dali.fzhhl.top/Article/details/gtawkotdkm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.kuanghao11.cn/Article/details/gthadqocgc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ppjwa.cn/Article/details/gtvykycytg.html

JS:   // child_process / cluster 模块
来源：http://dali.birdmap.top/Article/details/gtnfreucgn.html

TS:   // child_process / cluster 模块
来源：http://dali.zhoulong.xyz/Article/details/gtettmuigk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gtxvmsglci.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hongshengwenyu.top/Article/details/gtgdchxmoy.html

Ruby: // fork 块
来源：http://dali.zdqjudy.top/Article/details/gtfxtrucko.html

C#:   Parallel.For
来源：http://dali.yj202588.top/Article/details/gtveciuotp.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtcpixukft.html

P. 常用工具函数
来源：http://dali.wangdashe.top/Article/details/gtetwjhzpf.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtqudpahrf.html

[P01] 生成 UUID
来源：http://dali.meibo888.top/Article/details/gtcaumogtr.html

Py:   str(uuid.uuid4())
来源：http://dali.iojbl.cn/Article/details/gtbksyvbww.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xuanzx.com/Article/details/gtkntuqtxc.html

JS:   crypto.randomUUID()
来源：http://dali.gogol.net.cn/Article/details/gtsrccwcvz.html

TS:   crypto.randomUUID()
来源：http://dali.shuidangran.top/Article/details/gtumaklncv.html

Java: UUID.randomUUID().toString()
来源：http://dali.iojbl.cn/Article/details/gtllndnkoy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yongpay.top/Article/details/gtmkcogdgx.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigfzy.top/Article/details/gtwpxcsvoj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hnqzz.top/Article/details/gtmvzxgcyb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.feifeiyinyue.top/Article/details/gtkoxytzsc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tian-w.cn/Article/details/gtdmqcuukx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.fengsongda.top/Article/details/gteucxwzgv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yanxiufei.cn/Article/details/gtlfrczngt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.smart0.xyz/Article/details/gttpjsdska.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ppjwa.cn/Article/details/gttbwjqvhd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gotoacloud.top/Article/details/gtnwmtgvhk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cashguo.top/Article/details/gtkoqacesq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xuetiantiany.cn/Article/details/gtrdmrqqpm.html

[P03] 生成短随机字符串
来源：http://dali.ybcxt.top/Article/details/gtcbugnmwi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.dashuyun.cn/Article/details/gtfoftfpnk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhoulong.xyz/Article/details/gtajhklxkt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.bjfxy.top/Article/details/gtvfvgoxmi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tanke756.top/Article/details/gtbscsoxkq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ydzc1.top/Article/details/gtophusjna.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hysaishi.cn/Article/details/gtdrhtaxub.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj202588.top/Article/details/gtltmzfmmt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sweek.top/Article/details/gtidnfbwvr.html

[P04] 求长度
来源：http://dali.kuanghao11.cn/Article/details/gtkmxhnlmb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinqigufen.top/Article/details/gtsqdmzxkf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gthdwajnub.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cucudq.cn/Article/details/gtbqvewjev.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkjhcysd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yonumen.top/Article/details/gtlukokqwu.html

Go:   len(arr);  len(m)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedgempvl.html

Ruby: x.length;  x.size
来源：http://dali.zhiwuduotai.top/Article/details/gtjixtosnn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.nanxinkj.top/Article/details/gtjqqsfagc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jqgfzy.top/Article/details/gtecxwemqx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.aibaodan.cn/Article/details/gtxkvpzmdw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.iojbl.cn/Article/details/gtsnpabnvi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.mhx1999.top/Article/details/gtgyfefnyc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gotoacloud.top/Article/details/gtixzscykn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yanxiufei.cn/Article/details/gtpzezfmwr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gtmahtrjyn.html

Ruby: a == b
来源：http://dali.shzxlz.cn/Article/details/gtcitzhssr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xylfe.cn/Article/details/gtxdpecxjb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yangfankeji.com/Article/details/gttsqqutdr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.vqdsnc.cn/Article/details/gtlgzohasz.html

PHP:  if (empty($x)) {}
来源：http://dali.jinqigfzy.top/Article/details/gtwdipnnuy.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yvedp.cn/Article/details/gtobpbpzkk.html

TS:   if (x == null) {}
来源：http://dali.nanxuanxn.top/Article/details/gthoeluikc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gtsfxaeuxy.html

Go:   if x == nil {}
来源：http://dali.hnxiangtu.top/Article/details/gtoapkdogz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hongshengwenyu.top/Article/details/gtaipmcqax.html

C#:   if (x is null) {}
来源：http://dali.xylfe.cn/Article/details/gtwzhjkewo.html

[P07] 防抖与节流
来源：http://dali.shangyingyoupin.top/Article/details/gthxirmhwj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.aizwys.cn/Article/details/gtxqvswlge.html

PHP:  // 手写时间戳比较
来源：http://dali.316326.xyz/Article/details/gtzxicwnab.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuanzx.com/Article/details/gtgurpeehq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hywenlv.cn/Article/details/gtewdqmekh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.vqdsnc.cn/Article/details/gtmeqhxnfw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cucudq.cn/Article/details/gtciduolua.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.fzhhl.top/Article/details/gtwyrvpuob.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhengqikj.top/Article/details/gthplpdbuw.html

[P08] 处理浮点精度问题
来源：http://dali.feifeiyinyue.top/Article/details/gtujqfvofy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhiwuduotai.top/Article/details/gtadxfpeha.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.kuanghao11.cn/Article/details/gtqqodaywy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ydzc1.top/Article/details/gtolglcfag.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqegtqdap.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhengqikj.top/Article/details/gttmuwsnir.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gthwtlmzsq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.haohaochexian.top/Article/details/gtccfzketi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.meibo888.top/Article/details/gteqbadcgn.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtriqjufia.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.mhx1999.top/Article/details/gtnmddzqch.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtfcmsdgfk.html

[Q01] 创建表
来源：http://dali.yuanzhike.top/Article/details/gtwowheydy.html

CREATE TABLE users (
来源：http://dali.gzhubu.top/Article/details/gtrmphpphn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.mhx1999.top/Article/details/gthdixhwfg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.0kj1m.cn/Article/details/gtrmgiklmb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yj202588.top/Article/details/gtbjdlzfhu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hongshengwenyu.top/Article/details/gtkmjiwiud.html

);
来源：http://dali.c1oappe.top/Article/details/gtawgiyenc.html

[Q02] 创建带外键的表
来源：http://dali.jyoumei.cn/Article/details/gtpivvfbhe.html

CREATE TABLE orders (
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdnyeuyc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhongyouzk.top/Article/details/gtjayilxwo.html

user_id INT NOT NULL,
来源：http://dali.jinqigfzy.top/Article/details/gtwbopflpe.html

amount DECIMAL(10, 2),
来源：http://dali.kuanghao11.cn/Article/details/gtvteyzqcs.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenlongwang.top/Article/details/gtiwbjwgbc.html

);
来源：http://dali.nanxinkj.top/Article/details/gtchpiumio.html

[Q03] 增加列
来源：http://dali.sweek.top/Article/details/gtwmmacemu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.wangdashe.top/Article/details/gteycauhvd.html

[Q04] 修改列类型
来源：http://dali.chenzaomai.com/Article/details/gtglhjpwru.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.kuanghao11.cn/Article/details/gtkzlqnonm.html

[Q05] 重命名列
来源：http://dali.tianlin.xyz/Article/details/gtllhunxgd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hnqzz.top/Article/details/gtubvduicp.html

[Q06] 删除列
来源：http://dali.sysykeji.top/Article/details/gtufrnxcoe.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jqgufenzy.top/Article/details/gtbmjnfdpj.html

[Q07] 删除表
来源：http://dali.dashuyun.cn/Article/details/gtnisjzanc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinqigufen.top/Article/details/gtegguxbju.html

[Q08] 创建普通索引
来源：http://dali.yongpay.top/Article/details/gtaliyxkop.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj202588.top/Article/details/gtroyapnqi.html

[Q09] 创建唯一索引
来源：http://dali.hysaishi.cn/Article/details/gtqrxlinex.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jyoumei.cn/Article/details/gtmqxgvaic.html

[Q10] 插入单行
来源：http://dali.9152youxi.cn/Article/details/gtgeeaaqpv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gtibujetqh.html

[Q11] 一次插入多行
来源：http://dali.xziqi.cn/Article/details/gtcwzfgxaq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gtyfcjdoob.html

[Q12] 插入后取自增 ID
来源：http://dali.haohaochexian.top/Article/details/gtqvcmzkvs.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yonumen.top/Article/details/gtjggmdtnm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jqgfzy.top/Article/details/gtkvdtlhqv.html

[Q13] 忽略重复插入
来源：http://dali.xinyue.icu/Article/details/gtjbjuevlc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gtouhyzzbo.html

[Q14] 存在则更新（upsert）
来源：http://dali.ydzc1.top/Article/details/gtmtmqvxvl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jqgfzy.top/Article/details/gtlpqbkask.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shuidangran.top/Article/details/gtnzqurmew.html

[Q15] 查询全部
来源：http://dali.xuanzx.com/Article/details/gtcztvdqxs.html

SELECT * FROM users;
来源：http://dali.cashguo.top/Article/details/gttcsarlbs.html

[Q16] 查询指定列
来源：http://dali.nanxinkj.top/Article/details/gtnybvvthh.html

SELECT id, name FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtmlylrpcp.html

[Q17] 条件查询
来源：http://dali.hfpthk.cn/Article/details/gtvvreymvr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.haohaochexian.top/Article/details/gtiwpkzbzz.html

[Q18] 模糊匹配
来源：http://dali.yuanzhike.top/Article/details/gttxwsecsm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.dashuyun.cn/Article/details/gtisopoozi.html

[Q19] 范围查询
来源：http://dali.yj20258888.top/Article/details/gtrpxahryf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.wangshuangyany.cn/Article/details/gtctxfspaz.html

[Q20] IN 列表
来源：http://dali.cqqwz.cn/Article/details/gtcrhvoaln.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sysykeji.top/Article/details/gtqwnlfedj.html

[Q21] 空值判断
来源：http://dali.tian-w.cn/Article/details/gtsurrtodq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hywenlv.cn/Article/details/gtfazasxia.html

[Q22] 排序
来源：http://dali.ehwqpu.com/Article/details/gtrccinvtm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhoulong.xyz/Article/details/gtdqeiwtkw.html

[Q23] 分页
来源：http://dali.yvedp.cn/Article/details/gtjeibvoom.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.kuanghao11.cn/Article/details/gtgcbbfpjf.html

[Q24] 去重
来源：http://dali.hysaishi.cn/Article/details/gtsqnwbnge.html

SELECT DISTINCT city FROM users;
来源：http://dali.c1oappe.top/Article/details/gtbvdwphiu.html

[Q25] 只取前 N 条
来源：http://dali.zhiwuduotai.top/Article/details/gtdagnriga.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shangyingyoupin.top/Article/details/gtnzwwheek.html

[Q26] 计数
来源：http://dali.nanxuanxn.top/Article/details/gtcbypklfa.html

SELECT COUNT(*) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtzkoppxtp.html

[Q27] 条件计数
来源：http://dali.hysaishi.cn/Article/details/gtjpfhwkhg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cucudq.cn/Article/details/gthltclzzu.html

[Q28] 求和与平均
来源：http://dali.tian-w.cn/Article/details/gtmvydujxt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cashguo.top/Article/details/gtczsoyodw.html

[Q29] 最大最小值
来源：http://dali.bjfxy.top/Article/details/gtgxwfjlus.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtkqtqovnc.html

[Q30] 分组统计
来源：http://dali.meibo888.top/Article/details/gtbefjtzsf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gtvvkxvmhm.html

[Q31] 分组后过滤
来源：http://dali.kuanghao11.cn/Article/details/gtnmztnghs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yueranfly.top/Article/details/gtaqvschha.html

[Q32] 分组拼接字符串
来源：http://dali.snrcjt.cn/Article/details/gtporrfyuu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gtfstdktvx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yangfankeji.com/Article/details/gtumzgwycl.html

[Q33] 多列分组
来源：http://dali.havefunace.top/Article/details/gtjmtcfete.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ppjwa.cn/Article/details/gtnpuvumre.html

[Q34] 每组取第一条
来源：http://dali.havefunace.top/Article/details/gtalvmasvt.html

SELECT * FROM (
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohhsgagl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shanyushiyangtech.top/Article/details/gtdalgnfmq.html

) t WHERE rn = 1;
来源：http://dali.316326.xyz/Article/details/gtuaxjfgcr.html

[Q35] 内连接
来源：http://dali.yonumen.top/Article/details/gtjvbamxoa.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gtxrxoxtou.html

[Q36] 左连接
来源：http://dali.jyoumei.cn/Article/details/gtucjhkxbf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shzxlz.cn/Article/details/gtehyvyycl.html

[Q37] 右连接
来源：http://dali.ppjwa.cn/Article/details/gtweahhfad.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.feifeiyinyue.top/Article/details/gthezvxppp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xuanzx.com/Article/details/gtbuusbmdo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.fengsongda.top/Article/details/gtgcsgppeb.html

[Q39] 自连接（查上下级）
来源：http://dali.hysaishi.cn/Article/details/gtmyyybtne.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhixingplan.top/Article/details/gtmpwctrbj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hongshengwenyu.top/Article/details/gtfzgpkxys.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.pycfn.com/Article/details/gtddnbyhfp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.meibo888.top/Article/details/gtgqgfcjlh.html

[Q41] 多表连接
来源：http://dali.xinyue.icu/Article/details/gtgfiawpaa.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hfpthk.cn/Article/details/gtdmqhudin.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jianghu66.top/Article/details/gtbmquplct.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.vqdsnc.cn/Article/details/gttwxxsaqk.html

[Q42] 连接条件附加过滤
来源：http://dali.9152youxi.cn/Article/details/gtcbodhmrr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.smart0.xyz/Article/details/gtbrcojsnx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gaohongyu789.top/Article/details/gtpiksiedp.html

[Q43] 标量子查询
来源：http://dali.xuanzx.com/Article/details/gtlwzldwxh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xylfe.cn/Article/details/gtqquhccml.html

[Q44] IN 子查询
来源：http://dali.sweek.top/Article/details/gtafxtbbug.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yanxiufei.cn/Article/details/gtxinjobnt.html

[Q45] EXISTS 判断存在
来源：http://dali.chenzaomai.com/Article/details/gtlljjgean.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.c1oappe.top/Article/details/gtnrwmdzbm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfixhkuex.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yangfankeji.com/Article/details/gtwygilmpw.html

[Q47] 与平均值比较
来源：http://dali.smart0.xyz/Article/details/gtwibpsgto.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.wangshuangyany.cn/Article/details/gtmfzzmlqq.html

[Q48] CTE 公用表表达式
来源：http://dali.sweek.top/Article/details/gtnbuvctsw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gogol.net.cn/Article/details/gtetnhqkdp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.dianchejie.cn/Article/details/gtthnhkiap.html

[Q49] 更新单行
来源：http://dali.wangshuangyany.cn/Article/details/gtkvkrgpqk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.pycfn.com/Article/details/gtqwboueyf.html

[Q50] 批量更新
来源：http://dali.chenlongwang.top/Article/details/gtqwuhrlcp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcfzdtyky.html

[Q51] 用子查询更新
来源：http://dali.svipenyu.cn/Article/details/gtwoxdinrj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yonumen.top/Article/details/gtljxpyiac.html

[Q52] 删除指定行
来源：http://dali.cashguo.top/Article/details/gtqgqsabhc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.daxiang520.top/Article/details/gtzajqlklu.html

[Q53] 按条件删除
来源：http://dali.mhx1999.top/Article/details/gtcbbkpztd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tianlin.xyz/Article/details/gtcajxduga.html

[Q54] 清空表
来源：http://dali.yanxiufei.cn/Article/details/gtwkcneodf.html

TRUNCATE TABLE logs;
来源：http://dali.hfpthk.cn/Article/details/gtucurbejb.html

[Q55] 排名（并列占位）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexvrjfyv.html


<!-- 参考信息 -->