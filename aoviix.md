代发 wailian999

Py:   itertools.permutations(arr)
来源：http://dali.guannengcc.top/Article/details/gtrhpofetn.html

PHP:  // 手写递归交换
来源：http://dali.fengsongda.top/Article/details/gtismtkduw.html

JS:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtwnkefknb.html

TS:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtxtbezffl.html

Java: // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtcahmvopb.html

Go:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtygtpsvot.html

Ruby: arr.permutation.to_a
来源：http://dali.ehwqpu.com/Article/details/gtjwtqweeh.html

C#:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtkmjupidr.html

[N09] 栈与队列
来源：http://dali.haohaochexian.top/Article/details/gtzdoalygi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhongyouzk.top/Article/details/gtwuyuhzvb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gtnsolthlj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gtgiltlcdg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zycfv.cn/Article/details/gtnyzuvpsg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cqqwz.cn/Article/details/gtxgspfmly.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenzaomai.com/Article/details/gtcqvxjmri.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xylfe.cn/Article/details/gtjxtykvdn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.guannengcc.top/Article/details/gtfyldhidv.html

[N10] 链表节点定义
来源：http://dali.yongpay.top/Article/details/gtmrcwalhn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tian-w.cn/Article/details/gtpkojfmuy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jqgfzy.top/Article/details/gtbebqfeoy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj20258.top/Article/details/gtepbnkemp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ehwqpu.com/Article/details/gtiljjidpk.html

Java: class Node { int v; Node next; }
来源：http://dali.hysaishi.cn/Article/details/gtfkwbjtrt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.aizwys.cn/Article/details/gtjstariys.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sufxvd.cn/Article/details/gtessxhxyw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.dianchejie.cn/Article/details/gtzoibkghq.html

[N11] 二叉树中序遍历
来源：http://dali.xinyue.icu/Article/details/gtletjbweh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.fengsongda.top/Article/details/gtcxhibwch.html

PHP:  // 手写递归函数
来源：http://dali.chenlongwang.top/Article/details/gtuovcnvot.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hfpthk.cn/Article/details/gtjzmkiadi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuanzhike.top/Article/details/gtinapmtlb.html

Java: // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gtcyzxwzcn.html

Go:   // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gtudukxfmy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdogicrl.html

C#:   // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gtmqcfpryi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yonumen.top/Article/details/gtribrziee.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nwbrower.top/Article/details/gtyzojxrwg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jianghu66.top/Article/details/gtglcpnylz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenjidiqi.icu/Article/details/gtaxhxbhhj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cheryme.top/Article/details/gthykdsuea.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gttixpnyyp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.fzhhl.top/Article/details/gtezjtcuzw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xuanzx.com/Article/details/gtgxoxpukh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hammf.cn/Article/details/gtwfbphsit.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtkxcdummh.html

O. 并发与异步
来源：http://dali.zhongyouzk.top/Article/details/gtrvubpvcp.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtduavfcmv.html

[O01] 启动一个线程
来源：http://dali.hnxiangtu.top/Article/details/gtaftmtjel.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hysaishi.cn/Article/details/gtnefewhsn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jlsjyb.cn/Article/details/gtmojzsjwq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nanxuanxn.top/Article/details/gtyhcirlrq.html

TS:   // 同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gtmszcjixe.html

Java: new Thread(() -> f()).start()
来源：http://dali.yuxming.cn/Article/details/gtsqvugonl.html

Go:   go f()
来源：http://dali.wangshuangyany.cn/Article/details/gtptoxciqx.html

Ruby: Thread.new { f }
来源：http://dali.zdqjudy.top/Article/details/gtgzmonpqf.html

C#:   Task.Run(() => F());
来源：http://dali.guannengcc.top/Article/details/gtexqzjcrt.html

[O02] 使用线程池
来源：http://dali.gzhubu.top/Article/details/gtdjttmuvs.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.svipenyu.cn/Article/details/gtkrzrztlv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.quarkkingdee.top/Article/details/gtynzuagiw.html

JS:   // worker_threads 线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrqirmtf.html

TS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gtvllppyrz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.wangshuangyany.cn/Article/details/gttpikxspj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.mhx1999.top/Article/details/gtscuholgv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.haohaochexian.top/Article/details/gtirbfqilr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.redwolf501.top/Article/details/gtomcpditb.html

[O03] 加锁保护共享数据
来源：http://dali.jiagoushi.top/Article/details/gtepqyeikf.html

Py:   with lock: shared += 1
来源：http://dali.daria6918.cn/Article/details/gtsmpvywwd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.316326.xyz/Article/details/gtrxtpkifc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tian-w.cn/Article/details/gtrlqlgogb.html

TS:   // 同 JS
来源：http://dali.yonumen.top/Article/details/gtrtzkrqce.html

Java: synchronized (this) { shared++; }
来源：http://dali.bjfxy.top/Article/details/gtkjgqlqfb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xziqi.cn/Article/details/gtbmkhwlgg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.vqdsnc.cn/Article/details/gtswvmghkt.html

C#:   lock (gate) { shared++; }
来源：http://dali.jianghu66.top/Article/details/gthffefifz.html

[O04] 定义异步函数并等待
来源：http://dali.ydzc1.top/Article/details/gtdmajqfsv.html

Py:   async def f():⏎    await g()
来源：http://dali.yanxiufei.cn/Article/details/gtlpdmlygs.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj20258.top/Article/details/gtxggjgjqc.html

JS:   async function f() { await g(); }
来源：http://dali.snrcjt.cn/Article/details/gtwkneohgu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhongyouzk.top/Article/details/gttnjlivpx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.daria6918.cn/Article/details/gtvybeirgv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.aizwys.cn/Article/details/gtkhtbgplk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cashguo.top/Article/details/gtsinfdnou.html

C#:   async Task F() { await G(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtaletuotz.html

[O05] 并发执行并等待全部完成
来源：http://dali.yangfankeji.com/Article/details/gtekkfbuwt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgfzy.top/Article/details/gttlqarcmy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xziqi.cn/Article/details/gtmrcoqrfq.html

JS:   await Promise.all(tasks)
来源：http://dali.hysaishi.cn/Article/details/gtycetbnzv.html

TS:   await Promise.all(tasks)
来源：http://dali.bjfxy.top/Article/details/gtzthgrpkz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yangfankeji.com/Article/details/gtpvleixoa.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.birdmap.top/Article/details/gtieasrruq.html

Ruby: threads.map(&:join)
来源：http://dali.yuanzhike.top/Article/details/gttnjxzsjg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.aibaodan.cn/Article/details/gtvkmebbha.html

[O06] 使用进程池
来源：http://dali.nwbrower.top/Article/details/gtvlvvoaov.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.0kj1m.cn/Article/details/gthnriuutb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.birdmap.top/Article/details/gtuedbeugc.html

JS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gtmbtfjbyd.html

TS:   // child_process / cluster 模块
来源：http://dali.birdmap.top/Article/details/gtqtizxmwb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.iojbl.cn/Article/details/gtfbodndke.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cucudq.cn/Article/details/gtmwagqqti.html

Ruby: // fork 块
来源：http://dali.yongpay.top/Article/details/gtfdxpkdpf.html

C#:   Parallel.For
来源：http://dali.tian-w.cn/Article/details/gtndjpbepq.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkzeugxp.html

P. 常用工具函数
来源：http://dali.shzxlz.cn/Article/details/gtqnpdqxsl.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gttrgykcjs.html

[P01] 生成 UUID
来源：http://dali.guannengcc.top/Article/details/gtkidmhzuv.html

Py:   str(uuid.uuid4())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzgzbnvoq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.feifeiyinyue.top/Article/details/gtcdwofcpj.html

JS:   crypto.randomUUID()
来源：http://dali.hammf.cn/Article/details/gtgvnjtnbh.html

TS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gtmtdcpsyq.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhengqikj.top/Article/details/gtvugskluc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcpjxpxfs.html

Ruby: SecureRandom.uuid
来源：http://dali.mhx1999.top/Article/details/gtkdccbjbr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cashguo.top/Article/details/gtwxatpvnj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.havefunace.top/Article/details/gtsaxvaiih.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtivufzmqk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfffuykqd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.andypj.xyz/Article/details/gtdrpgfblv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shuidangran.top/Article/details/gtpcfcevow.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.9152youxi.cn/Article/details/gtwuabtljc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yuanzhike.top/Article/details/gtwogmmsxi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xziqi.cn/Article/details/gterhphtbo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhixingplan.top/Article/details/gtcpsasaev.html

[P03] 生成短随机字符串
来源：http://dali.jqgufenzy.top/Article/details/gtlohzfxua.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinqigfzy.top/Article/details/gtqewqdnzw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sxryk.cn/Article/details/gtpahnuwsj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjrlnsrb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenzaomai.com/Article/details/gtubffvfpj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yongpay.top/Article/details/gtnyshywtd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gzhubu.top/Article/details/gtpredsqmj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinqigfzy.top/Article/details/gtnizrnvtc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.pycfn.com/Article/details/gtakijlcwd.html

[P04] 求长度
来源：http://dali.pycfn.com/Article/details/gttjrhbzkg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xuetiantiany.cn/Article/details/gtxbqyspji.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gthldzodbo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aizwys.cn/Article/details/gtufovjowy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenlongwang.top/Article/details/gtpxrddhms.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gzhubu.top/Article/details/gtozvnlkhm.html

Go:   len(arr);  len(m)
来源：http://dali.shuidangran.top/Article/details/gtayikssiv.html

Ruby: x.length;  x.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnapqxggt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.vqdsnc.cn/Article/details/gtubegdnyu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sweek.top/Article/details/gtmyjvrgxy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tianlin.xyz/Article/details/gtocgtdrvo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenjidiqi.icu/Article/details/gtlqusirzw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jqgufenzy.top/Article/details/gtabdnmzqh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigufen.top/Article/details/gtraibbqhw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.pengpengdd.cyou/Article/details/gtcyoxxcdb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yonumen.top/Article/details/gtypeuwfro.html

Ruby: a == b
来源：http://dali.cheryme.top/Article/details/gtfpyxopuu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sxryk.cn/Article/details/gtbatycpge.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhixingplan.top/Article/details/gtbsonbpmj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.redwolf501.top/Article/details/gtqdrzwlyd.html

PHP:  if (empty($x)) {}
来源：http://dali.smart0.xyz/Article/details/gtxzcpcynm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.aizwys.cn/Article/details/gttrqltsng.html

TS:   if (x == null) {}
来源：http://dali.sysykeji.top/Article/details/gtekiiqbdp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.fzhhl.top/Article/details/gtwrvdpkrq.html

Go:   if x == nil {}
来源：http://dali.fzhhl.top/Article/details/gtuublulrr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nwbrower.top/Article/details/gtrbjqzrpt.html

C#:   if (x is null) {}
来源：http://dali.hysaishi.cn/Article/details/gtukjfitlr.html

[P07] 防抖与节流
来源：http://dali.haohaochexian.top/Article/details/gtrfhqtxln.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.c1oappe.top/Article/details/gtxhsikvbp.html

PHP:  // 手写时间戳比较
来源：http://dali.jlsjyb.cn/Article/details/gtmppxpfek.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gtvldvskyi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jlsjyb.cn/Article/details/gtpccflhwt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.316326.xyz/Article/details/gtmpjpgdee.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yuxming.cn/Article/details/gtgedwmxtx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shangyingyoupin.top/Article/details/gtbsuuyudl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.tian-w.cn/Article/details/gtdteycdha.html

[P08] 处理浮点精度问题
来源：http://dali.sweek.top/Article/details/gtocdkoqny.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yanxiufei.cn/Article/details/gtogaglerd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.daria6918.cn/Article/details/gtjfojbpaf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xuetiantiany.cn/Article/details/gteccljjpx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.bjfxy.top/Article/details/gtgzfnigkd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.9152youxi.cn/Article/details/gtdgkzists.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cheryme.top/Article/details/gtzfacqfvt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.quarkkingdee.top/Article/details/gteuskxyfr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hammf.cn/Article/details/gtoudfonga.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gthnejkvce.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yvedp.cn/Article/details/gtkirxmuaq.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtplankvsx.html

[Q01] 创建表
来源：http://dali.shuidangran.top/Article/details/gtsudcodbk.html

CREATE TABLE users (
来源：http://dali.tian-w.cn/Article/details/gtwgmepaju.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daxiang520.top/Article/details/gtmidoucga.html

name VARCHAR(50) NOT NULL,
来源：http://dali.meibo888.top/Article/details/gtqmqldbqc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sxryk.cn/Article/details/gtqvvtonkj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.fzhhl.top/Article/details/gtiiszhvjf.html

);
来源：http://dali.hnqzz.top/Article/details/gtuguqoxko.html

[Q02] 创建带外键的表
来源：http://dali.jiagoushi.top/Article/details/gtrmheeyjc.html

CREATE TABLE orders (
来源：http://dali.jianghu66.top/Article/details/gtyfckkxwh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jyoumei.cn/Article/details/gtumubqgoq.html

user_id INT NOT NULL,
来源：http://dali.yangfankeji.com/Article/details/gtlnuhotfl.html

amount DECIMAL(10, 2),
来源：http://dali.hywenlv.cn/Article/details/gtmbkqkhsl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yanxiufei.cn/Article/details/gtacqolgiw.html

);
来源：http://dali.gaohongyu789.top/Article/details/gtgshiebpd.html

[Q03] 增加列
来源：http://dali.zhiwuduotai.top/Article/details/gtzkbjizlb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sxryk.cn/Article/details/gtdefblxcf.html

[Q04] 修改列类型
来源：http://dali.aizwys.cn/Article/details/gtkunioyfg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jiagoushi.top/Article/details/gtxghfogqh.html

[Q05] 重命名列
来源：http://dali.zhengqikj.top/Article/details/gtrgblyjai.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.mhx1999.top/Article/details/gtykwvkcbw.html

[Q06] 删除列
来源：http://dali.chenjidiqi.icu/Article/details/gtucliwngl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xuetiantiany.cn/Article/details/gtihrnrszx.html

[Q07] 删除表
来源：http://dali.tanke756.top/Article/details/gtexflwmbo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.dashuyun.cn/Article/details/gtiqanvblx.html

[Q08] 创建普通索引
来源：http://dali.jiagoushi.top/Article/details/gtinieuzxn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hongshengwenyu.top/Article/details/gtnybeznat.html

[Q09] 创建唯一索引
来源：http://dali.pycfn.com/Article/details/gtrqpvlxeh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nanxinkj.top/Article/details/gteuobaqvz.html

[Q10] 插入单行
来源：http://dali.xuetiantiany.cn/Article/details/gtcdgkdttf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gtpjzmhtqi.html

[Q11] 一次插入多行
来源：http://dali.ybcxt.top/Article/details/gtjzxkynpx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ydzc1.top/Article/details/gtuixhqtoa.html

[Q12] 插入后取自增 ID
来源：http://dali.zhixingplan.top/Article/details/gtbdlemkrs.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xylfe.cn/Article/details/gtsxoxvfll.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.iojbl.cn/Article/details/gtiqznmlsn.html

[Q13] 忽略重复插入
来源：http://dali.zdqjudy.top/Article/details/gtxtqotieh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.meibo888.top/Article/details/gtaqixiemt.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenlongwang.top/Article/details/gterlmuqpi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hammf.cn/Article/details/gtppnewkic.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.andypj.xyz/Article/details/gtkmqsjplu.html

[Q15] 查询全部
来源：http://dali.zhongyouzk.top/Article/details/gtrkzhxnqe.html

SELECT * FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtajlkqveo.html

[Q16] 查询指定列
来源：http://dali.zycfv.cn/Article/details/gtqbwzjprf.html

SELECT id, name FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtosxetixw.html

[Q17] 条件查询
来源：http://dali.ydzc1.top/Article/details/gtplypaquw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtjmnnniuy.html

[Q18] 模糊匹配
来源：http://dali.quarkkingdee.top/Article/details/gtyvmudjzl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinqigfzy.top/Article/details/gtndpltnov.html

[Q19] 范围查询
来源：http://dali.havefunace.top/Article/details/gtsdgcncuc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinghuilouyu.cn/Article/details/gtujcqwzex.html

[Q20] IN 列表
来源：http://dali.cashguo.top/Article/details/gtkwgmxhrn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cqqwz.cn/Article/details/gtofiunqfg.html

[Q21] 空值判断
来源：http://dali.xuanzx.com/Article/details/gtittqefak.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.pengpengdd.cyou/Article/details/gtlnmhafhy.html

[Q22] 排序
来源：http://dali.yj20258888.top/Article/details/gttxqhwktd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yanxiufei.cn/Article/details/gtzcqfjgaj.html

[Q23] 分页
来源：http://dali.c1oappe.top/Article/details/gtttcifnxe.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinghuilouyu.cn/Article/details/gttclipasc.html

[Q24] 去重
来源：http://dali.aizwys.cn/Article/details/gtmyinfcki.html

SELECT DISTINCT city FROM users;
来源：http://dali.ybcxt.top/Article/details/gtdlwwtkgi.html

[Q25] 只取前 N 条
来源：http://dali.hongshengwenyu.top/Article/details/gtkakvfucr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xinyue.icu/Article/details/gtagtmfvib.html

[Q26] 计数
来源：http://dali.gzhubu.top/Article/details/gtedsdmake.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtpyorojtn.html

[Q27] 条件计数
来源：http://dali.316326.xyz/Article/details/gtrknpbwck.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtpngbqfma.html

[Q28] 求和与平均
来源：http://dali.xuetiantiany.cn/Article/details/gtuukpimml.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtepxdhnka.html

[Q29] 最大最小值
来源：http://dali.hfpthk.cn/Article/details/gtbxndddgh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtdstzsfwz.html

[Q30] 分组统计
来源：http://dali.hysaishi.cn/Article/details/gtkriwgmja.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gtxicrvqgx.html

[Q31] 分组后过滤
来源：http://dali.jlsjyb.cn/Article/details/gtrrcmjxav.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hysaishi.cn/Article/details/gtiwrazlyv.html

[Q32] 分组拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtkvnfmjiu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gtyygeuzbf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj20258888.top/Article/details/gtowdugggt.html

[Q33] 多列分组
来源：http://dali.aizwys.cn/Article/details/gtmmmhwpiw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ybcxt.top/Article/details/gtugiopuyi.html

[Q34] 每组取第一条
来源：http://dali.guowangkeji.top/Article/details/gtowatyrwy.html

SELECT * FROM (
来源：http://dali.birdmap.top/Article/details/gtknbzznhn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hysaishi.cn/Article/details/gtlhrcuonk.html

) t WHERE rn = 1;
来源：http://dali.gogol.net.cn/Article/details/gtuhjcmuvf.html

[Q35] 内连接
来源：http://dali.ehwqpu.com/Article/details/gtybhxxgip.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hongshengwenyu.top/Article/details/gtwsdqdgmf.html

[Q36] 左连接
来源：http://dali.hywenlv.cn/Article/details/gthanuglpb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxaznwku.html

[Q37] 右连接
来源：http://dali.zdqjudy.top/Article/details/gtfxxlvskh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtonmacurs.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gogol.net.cn/Article/details/gthwbuvyxr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.316326.xyz/Article/details/gtvrfxdvku.html

[Q39] 自连接（查上下级）
来源：http://dali.yj202588.top/Article/details/gtwoladdkj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gotoacloud.top/Article/details/gtvqhsliyv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cucudq.cn/Article/details/gtgxbhfkqw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jiagoushi.top/Article/details/gtdsvploel.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.haohaochexian.top/Article/details/gtfztmvtmx.html

[Q41] 多表连接
来源：http://dali.gogol.net.cn/Article/details/gtotocricj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.chenlongwang.top/Article/details/gtiqnrjcsx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.daria6918.cn/Article/details/gtmnlknamn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.316326.xyz/Article/details/gtvncmqbyl.html

[Q42] 连接条件附加过滤
来源：http://dali.chenzaomai.com/Article/details/gtumztfefj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavwmvibv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jyoumei.cn/Article/details/gthzjjnzas.html

[Q43] 标量子查询
来源：http://dali.xuanzx.com/Article/details/gtkcggmzln.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sufxvd.cn/Article/details/gtlcwifvnr.html

[Q44] IN 子查询
来源：http://dali.yj20258.top/Article/details/gtykneoisv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.c1oappe.top/Article/details/gttofvacpn.html

[Q45] EXISTS 判断存在
来源：http://dali.jlsjyb.cn/Article/details/gtprsdtkey.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.svipenyu.cn/Article/details/gtaqazuadd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gogol.net.cn/Article/details/gttuvzqpdh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hongshengwenyu.top/Article/details/gtiuexhhrr.html

[Q47] 与平均值比较
来源：http://dali.c1oappe.top/Article/details/gtoadcosob.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gogol.net.cn/Article/details/gtcggheibs.html

[Q48] CTE 公用表表达式
来源：http://dali.jqgufenzy.top/Article/details/gtkuicrqph.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ppjwa.cn/Article/details/gtrouaeyju.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nwbrower.top/Article/details/gtkqeytvxe.html

[Q49] 更新单行
来源：http://dali.316326.xyz/Article/details/gtcminmldi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jqgufenzy.top/Article/details/gtkvfrrgdd.html

[Q50] 批量更新
来源：http://dali.xuetiantiany.cn/Article/details/gtuwkwmgez.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zdqjudy.top/Article/details/gtdkddechi.html

[Q51] 用子查询更新
来源：http://dali.dianchejie.cn/Article/details/gtuarofewp.html


<!-- 参考信息 -->