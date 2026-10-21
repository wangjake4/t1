代发 wailian999

Go:   // 手写 map[int]int
来源：http://dali.zhoulong.xyz/Article/details/gtxrjibiaa.html

Ruby: // 手写 Hash
来源：http://dali.shzxlz.cn/Article/details/gtcrenigkh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jqgfzy.top/Article/details/gtpvstfttm.html

[N08] 生成全排列
来源：http://dali.hnqzz.top/Article/details/gtnigoewyb.html

Py:   itertools.permutations(arr)
来源：http://dali.birdmap.top/Article/details/gtbzymulpy.html

PHP:  // 手写递归交换
来源：http://dali.quarkkingdee.top/Article/details/gtokvzzzqy.html

JS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gteihjshzs.html

TS:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gturczezvw.html

Java: // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtaeqpbepd.html

Go:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtuiigkgxf.html

Ruby: arr.permutation.to_a
来源：http://dali.xuanzx.com/Article/details/gtskidnumy.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtkiukffgj.html

[N09] 栈与队列
来源：http://dali.jqgufenzy.top/Article/details/gtfnyysxjp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hywenlv.cn/Article/details/gtjyjlnhos.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gtvwxnmpoh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gtesejyhjh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nanxuanxn.top/Article/details/gtpaznmeee.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shangyingyoupin.top/Article/details/gtevaefzee.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nwbrower.top/Article/details/gtfxzqetac.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.smart0.xyz/Article/details/gtdhtofkgm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.meibo888.top/Article/details/gtfctabrtl.html

[N10] 链表节点定义
来源：http://dali.gogol.net.cn/Article/details/gtbnqwlutf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cqqwz.cn/Article/details/gtmrxqiqzw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ybcxt.top/Article/details/gtgqnznpvx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guannengcc.top/Article/details/gtgwvelajw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gogol.net.cn/Article/details/gtxvycxdpn.html

Java: class Node { int v; Node next; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdlcuxdnz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzmeflyzx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.316326.xyz/Article/details/gtowrkbqnv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xinyue.icu/Article/details/gtkngmaaum.html

[N11] 二叉树中序遍历
来源：http://dali.tianlin.xyz/Article/details/gtftyhogbv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.andypj.xyz/Article/details/gtayjfkpic.html

PHP:  // 手写递归函数
来源：http://dali.jianghu66.top/Article/details/gtncchfpim.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.0kj1m.cn/Article/details/gtinkoxbvh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuanzhike.top/Article/details/gtrqcxjgwt.html

Java: // 手写递归
来源：http://dali.yj20258.top/Article/details/gtrbsvmnzm.html

Go:   // 手写递归
来源：http://dali.mhx1999.top/Article/details/gtcegakonp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.andypj.xyz/Article/details/gtolprfthb.html

C#:   // 手写递归
来源：http://dali.birdmap.top/Article/details/gtmsvxvfzi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.chenzaomai.com/Article/details/gtourezpvk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.c1oappe.top/Article/details/gtmvzxewma.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.fzhhl.top/Article/details/gtuwattbiy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shuidangran.top/Article/details/gtmbbcgghp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigfzy.top/Article/details/gtkorkeigi.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangdashe.top/Article/details/gtswrymugd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yuxming.cn/Article/details/gtpxzbkzty.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.tanke756.top/Article/details/gtjqobkyph.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cqqwz.cn/Article/details/gtdwzqydga.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqxfhgatl.html

O. 并发与异步
来源：http://dali.shangyingyoupin.top/Article/details/gtkowysxos.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtdlczktax.html

[O01] 启动一个线程
来源：http://dali.zhoulong.xyz/Article/details/gtijrehtth.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nanxuanxn.top/Article/details/gtqkfrlyrx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yuxming.cn/Article/details/gtduphzrrr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.fzhhl.top/Article/details/gtvwriqgyy.html

TS:   // 同 JS
来源：http://dali.zhengqikj.top/Article/details/gtvltdacua.html

Java: new Thread(() -> f()).start()
来源：http://dali.jiagoushi.top/Article/details/gtwpovvfoa.html

Go:   go f()
来源：http://dali.gzhubu.top/Article/details/gtnrykoihj.html

Ruby: Thread.new { f }
来源：http://dali.ybcxt.top/Article/details/gtqvoybqva.html

C#:   Task.Run(() => F());
来源：http://dali.mhx1999.top/Article/details/gtwitzomak.html

[O02] 使用线程池
来源：http://dali.daxiang520.top/Article/details/gtjhjcaduh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrhwwetvp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sysykeji.top/Article/details/gtdlosfqcf.html

JS:   // worker_threads 线程池
来源：http://dali.guowangkeji.top/Article/details/gtoqdyyijc.html

TS:   // worker_threads 线程池
来源：http://dali.yonumen.top/Article/details/gtcaobsenz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cheryme.top/Article/details/gtkdqarmqv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nwbrower.top/Article/details/gthvuqmuwe.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.kuanghao11.cn/Article/details/gtglrwosze.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.andypj.xyz/Article/details/gtgedqohnb.html

[O03] 加锁保护共享数据
来源：http://dali.shuidangran.top/Article/details/gtswyjrzfc.html

Py:   with lock: shared += 1
来源：http://dali.jinqigfzy.top/Article/details/gtuhwysbwp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.smart0.xyz/Article/details/gtxwgmdknf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jqgufenzy.top/Article/details/gtjbysjzzg.html

TS:   // 同 JS
来源：http://dali.fengsongda.top/Article/details/gtjdvsxxjr.html

Java: synchronized (this) { shared++; }
来源：http://dali.c1oappe.top/Article/details/gtahqgtgft.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.316326.xyz/Article/details/gtvisiaaiu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gtshkntbcq.html

C#:   lock (gate) { shared++; }
来源：http://dali.yangfankeji.com/Article/details/gtllmvgxgx.html

[O04] 定义异步函数并等待
来源：http://dali.yangfankeji.com/Article/details/gtvdsqlode.html

Py:   async def f():⏎    await g()
来源：http://dali.bjfxy.top/Article/details/gtebudtfin.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zdqjudy.top/Article/details/gtzzrplhmn.html

JS:   async function f() { await g(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtybodpozq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.birdmap.top/Article/details/gtatphezkb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ehwqpu.com/Article/details/gthyadkszw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nanxuanxn.top/Article/details/gtowcmycrz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.pengpengdd.cyou/Article/details/gthepijlfb.html

C#:   async Task F() { await G(); }
来源：http://dali.guannengcc.top/Article/details/gtdvdizfxy.html

[O05] 并发执行并等待全部完成
来源：http://dali.hfpthk.cn/Article/details/gtrldnohfm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhiwuduotai.top/Article/details/gtavoeqxqn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cashguo.top/Article/details/gtcfygilpl.html

JS:   await Promise.all(tasks)
来源：http://dali.sxryk.cn/Article/details/gtbdyxiiom.html

TS:   await Promise.all(tasks)
来源：http://dali.jiagoushi.top/Article/details/gtfzffifcm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xylfe.cn/Article/details/gtpjftkgij.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.meibo888.top/Article/details/gtimmeceio.html

Ruby: threads.map(&:join)
来源：http://dali.cqqwz.cn/Article/details/gtqlbwpcji.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gotoacloud.top/Article/details/gtrjikujhp.html

[O06] 使用进程池
来源：http://dali.shangyingyoupin.top/Article/details/gttoehnxdv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhixingplan.top/Article/details/gtnnbamdoh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cashguo.top/Article/details/gtfksjadxf.html

JS:   // child_process / cluster 模块
来源：http://dali.gaohongyu789.top/Article/details/gtdnjqqftz.html

TS:   // child_process / cluster 模块
来源：http://dali.tian-w.cn/Article/details/gtxghuoauv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tanke756.top/Article/details/gtqsskavgp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yongpay.top/Article/details/gtmxxujxkp.html

Ruby: // fork 块
来源：http://dali.chenzaomai.com/Article/details/gtixvrxybn.html

C#:   Parallel.For
来源：http://dali.zhoulong.xyz/Article/details/gtqjjjeurt.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtrquvzjcz.html

P. 常用工具函数
来源：http://dali.wangshuangyany.cn/Article/details/gtrkjlkkap.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtzjawskoy.html

[P01] 生成 UUID
来源：http://dali.jinqigfzy.top/Article/details/gtomjuyqua.html

Py:   str(uuid.uuid4())
来源：http://dali.cashguo.top/Article/details/gtdmbhuybf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gaohongyu789.top/Article/details/gthwektpnp.html

JS:   crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gtetajrrhr.html

TS:   crypto.randomUUID()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpzyysdcq.html

Java: UUID.randomUUID().toString()
来源：http://dali.vqdsnc.cn/Article/details/gtakxoxlfy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jyoumei.cn/Article/details/gthegpkmqf.html

Ruby: SecureRandom.uuid
来源：http://dali.meibo888.top/Article/details/gtknogryfb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.haohaochexian.top/Article/details/gtiuauzvkm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhongyouzk.top/Article/details/gtsrilulhj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hnqzz.top/Article/details/gtuduspcgr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tanke756.top/Article/details/gtdhcatgyw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shuidangran.top/Article/details/gtalhmubvn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.fzhhl.top/Article/details/gtehfwfafl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sufxvd.cn/Article/details/gtapzicljj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jlsjyb.cn/Article/details/gtjlwonlpc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.wangdashe.top/Article/details/gteoibnxac.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jqgufenzy.top/Article/details/gtvxdkquxs.html

[P03] 生成短随机字符串
来源：http://dali.yvedp.cn/Article/details/gtjevvqddn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinqigufen.top/Article/details/gtfpvohngm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xuanzx.com/Article/details/gtdhskoyec.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yvedp.cn/Article/details/gtskoecgus.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yanxiufei.cn/Article/details/gtbdxkvscv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkvgfhou.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.9152youxi.cn/Article/details/gtfxcyqjyz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yanxiufei.cn/Article/details/gtzmzbbqvi.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.redwolf501.top/Article/details/gtwcwcgdvq.html

[P04] 求长度
来源：http://dali.tianlin.xyz/Article/details/gtgnvkgygu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyjvxzoyf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gthnmjmzvv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cheryme.top/Article/details/gtzvbetazk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvzoyxopu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xinyue.icu/Article/details/gtkwjqlxpx.html

Go:   len(arr);  len(m)
来源：http://dali.jiagoushi.top/Article/details/gtbzzsnwzy.html

Ruby: x.length;  x.size
来源：http://dali.0kj1m.cn/Article/details/gtendfnaai.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tanke756.top/Article/details/gtlashbwvd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.wangshuangyany.cn/Article/details/gtbplkzanh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xziqi.cn/Article/details/gtpnbmkeul.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xziqi.cn/Article/details/gtajwwpmmx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzfotmkvn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xziqi.cn/Article/details/gtvwehwcrl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.daria6918.cn/Article/details/gtumdqpxir.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ivvv.top/Article/details/gtnskgnmop.html

Ruby: a == b
来源：http://dali.jiagoushi.top/Article/details/gtkljkzdzm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yvedp.cn/Article/details/gtiwwxggza.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.dashuyun.cn/Article/details/gthnxwynxv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ybcxt.top/Article/details/gttnacdsao.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gtjowpgdwy.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hammf.cn/Article/details/gtjnjpimku.html

TS:   if (x == null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzpqfqwo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.havefunace.top/Article/details/gtutuvadpy.html

Go:   if x == nil {}
来源：http://dali.zycfv.cn/Article/details/gtjngtoyqc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yueranfly.top/Article/details/gtgpbaqzps.html

C#:   if (x is null) {}
来源：http://dali.hfpthk.cn/Article/details/gtkkthhabm.html

[P07] 防抖与节流
来源：http://dali.xziqi.cn/Article/details/gtppqnkaro.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.birdmap.top/Article/details/gtuwmlwgke.html

PHP:  // 手写时间戳比较
来源：http://dali.smart0.xyz/Article/details/gtkjcjtxjz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gtdyeslpon.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.feifeiyinyue.top/Article/details/gtiudvqamd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ydzc1.top/Article/details/gthapwkfld.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenjidiqi.icu/Article/details/gtzjyopqau.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.vqdsnc.cn/Article/details/gtegwjcaib.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenlongwang.top/Article/details/gtfrtsiqjd.html

[P08] 处理浮点精度问题
来源：http://dali.yueranfly.top/Article/details/gtmgxropql.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ydzc1.top/Article/details/gtlvlvyjkr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cashguo.top/Article/details/gtdbfqomgx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.c1oappe.top/Article/details/gtpzalwyov.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tianlin.xyz/Article/details/gteyvnrooj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.feifeiyinyue.top/Article/details/gtalyhnuqf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hfpthk.cn/Article/details/gtjpekviab.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhiwuduotai.top/Article/details/gtgvwncpzb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.pengpengdd.cyou/Article/details/gtafjwlubt.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtyjyolpqj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yvedp.cn/Article/details/gtthztmyhp.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtwphsesdz.html

[Q01] 创建表
来源：http://dali.chenlongwang.top/Article/details/gticydiyim.html

CREATE TABLE users (
来源：http://dali.jqgufenzy.top/Article/details/gtekrjcjrc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pycfn.com/Article/details/gtuqwsggld.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhongyouzk.top/Article/details/gtbqoitkww.html

email VARCHAR(100) UNIQUE,
来源：http://dali.guannengcc.top/Article/details/gtoxhcgjyp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xylfe.cn/Article/details/gtfzvudhkx.html

);
来源：http://dali.yvedp.cn/Article/details/gtesroeoeb.html

[Q02] 创建带外键的表
来源：http://dali.yj20258888.top/Article/details/gtkwkrhxya.html

CREATE TABLE orders (
来源：http://dali.c1oappe.top/Article/details/gtnmgortlv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ybcxt.top/Article/details/gtnhbevkam.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gtusulqumw.html

amount DECIMAL(10, 2),
来源：http://dali.redwolf501.top/Article/details/gtghxygnis.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tian-w.cn/Article/details/gtanprjihd.html

);
来源：http://dali.ehwqpu.com/Article/details/gtixvtokqo.html

[Q03] 增加列
来源：http://dali.xinyue.icu/Article/details/gtpvpkdoom.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ybcxt.top/Article/details/gtpjboxmsn.html

[Q04] 修改列类型
来源：http://dali.wangdashe.top/Article/details/gtamclstdi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhixingplan.top/Article/details/gtgzjnexmk.html

[Q05] 重命名列
来源：http://dali.snrcjt.cn/Article/details/gtzcyjemmz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xylfe.cn/Article/details/gtujrrkazb.html

[Q06] 删除列
来源：http://dali.iojbl.cn/Article/details/gtfamogmwx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jyoumei.cn/Article/details/gtkpighghe.html

[Q07] 删除表
来源：http://dali.yj20258.top/Article/details/gtgecklvpf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.guowangkeji.top/Article/details/gteiyehmvo.html

[Q08] 创建普通索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtylmmmxab.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gaohongyu789.top/Article/details/gtlsgirzsg.html

[Q09] 创建唯一索引
来源：http://dali.hnqzz.top/Article/details/gtllrjtrgz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xinyue.icu/Article/details/gtkpbvzpgj.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gtbdfbyspg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj202588.top/Article/details/gtwygrvqrv.html

[Q11] 一次插入多行
来源：http://dali.dianchejie.cn/Article/details/gtvewvuhdg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ivvv.top/Article/details/gtjayxkpdy.html

[Q12] 插入后取自增 ID
来源：http://dali.jinqigufen.top/Article/details/gtrrtsvuld.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.fengsongda.top/Article/details/gtsavvobzc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.feifeiyinyue.top/Article/details/gtnylclvtd.html

[Q13] 忽略重复插入
来源：http://dali.cqqwz.cn/Article/details/gtgqmuhibm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gtdhpwrcve.html

[Q14] 存在则更新（upsert）
来源：http://dali.wangshuangyany.cn/Article/details/gtolwihauk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yuxming.cn/Article/details/gtfwenduah.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfgmlxxl.html

[Q15] 查询全部
来源：http://dali.fzhhl.top/Article/details/gtuefqwjfi.html

SELECT * FROM users;
来源：http://dali.yvedp.cn/Article/details/gtjswidmjv.html

[Q16] 查询指定列
来源：http://dali.shuidangran.top/Article/details/gtnzmwqcax.html

SELECT id, name FROM users;
来源：http://dali.yj202588.top/Article/details/gtlxsumsij.html

[Q17] 条件查询
来源：http://dali.wangdashe.top/Article/details/gtxerrgiuq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.aizwys.cn/Article/details/gtzxclspvx.html

[Q18] 模糊匹配
来源：http://dali.daria6918.cn/Article/details/gtobaleezn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shzxlz.cn/Article/details/gtgqszpazd.html

[Q19] 范围查询
来源：http://dali.redwolf501.top/Article/details/gtcbyxixie.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.316326.xyz/Article/details/gtiwmohrap.html

[Q20] IN 列表
来源：http://dali.sxryk.cn/Article/details/gtirehtisy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhengqikj.top/Article/details/gtvhzdlyxh.html

[Q21] 空值判断
来源：http://dali.yongpay.top/Article/details/gtjpfvnydc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xuanzx.com/Article/details/gthnluquml.html

[Q22] 排序
来源：http://dali.zhengqikj.top/Article/details/gtusdngnfq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzuytzthz.html

[Q23] 分页
来源：http://dali.zhongyouzk.top/Article/details/gtoocqcgti.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ehwqpu.com/Article/details/gtyoarerat.html

[Q24] 去重
来源：http://dali.ybcxt.top/Article/details/gtvagjgler.html

SELECT DISTINCT city FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtyunapnmu.html

[Q25] 只取前 N 条
来源：http://dali.yuanzhike.top/Article/details/gtmoyheytw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nanxuanxn.top/Article/details/gtxfiwikwo.html

[Q26] 计数
来源：http://dali.tianlin.xyz/Article/details/gtfjeibnrp.html

SELECT COUNT(*) FROM users;
来源：http://dali.iojbl.cn/Article/details/gthhxjhefv.html

[Q27] 条件计数
来源：http://dali.ydzc1.top/Article/details/gtkiribsyo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tanke756.top/Article/details/gthehfggmf.html

[Q28] 求和与平均
来源：http://dali.ivvv.top/Article/details/gtpcwhslig.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gticvkeqov.html

[Q29] 最大最小值
来源：http://dali.jianghu66.top/Article/details/gtehtvzjqr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtbzvklywc.html

[Q30] 分组统计
来源：http://dali.gzhubu.top/Article/details/gtssunrkvy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.andypj.xyz/Article/details/gthzjjuxfy.html

[Q31] 分组后过滤
来源：http://dali.nwbrower.top/Article/details/gthdiaxlqe.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shzxlz.cn/Article/details/gtzabjehjo.html

[Q32] 分组拼接字符串
来源：http://dali.snrcjt.cn/Article/details/gtdewpcjub.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj20258.top/Article/details/gthewcmfgf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tian-w.cn/Article/details/gtetejxxse.html

[Q33] 多列分组
来源：http://dali.shuidangran.top/Article/details/gtrueszsta.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hammf.cn/Article/details/gtyxwowoye.html

[Q34] 每组取第一条
来源：http://dali.cucudq.cn/Article/details/gtvqydrxjy.html

SELECT * FROM (
来源：http://dali.shzxlz.cn/Article/details/gtilyswpqb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.0kj1m.cn/Article/details/gtvebzuloi.html

) t WHERE rn = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlakkevdb.html

[Q35] 内连接
来源：http://dali.vqdsnc.cn/Article/details/gtksuscyat.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.daria6918.cn/Article/details/gtjarucyrx.html

[Q36] 左连接
来源：http://dali.xuanzx.com/Article/details/gtkqjjshep.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gtrshxdnkr.html

[Q37] 右连接
来源：http://dali.bjfxy.top/Article/details/gtrzbazscb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xylfe.cn/Article/details/gtisqxpbof.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xziqi.cn/Article/details/gtuwciblmn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tianlin.xyz/Article/details/gttdhtuyfi.html

[Q39] 自连接（查上下级）
来源：http://dali.kuanghao11.cn/Article/details/gtzplaotjx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.aizwys.cn/Article/details/gtmwlagaps.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.svipenyu.cn/Article/details/gtnavjxplz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cucudq.cn/Article/details/gtfpjhrkyz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.bjfxy.top/Article/details/gtlbowbvbq.html

[Q41] 多表连接
来源：http://dali.yongpay.top/Article/details/gtcwsnwjch.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gtohpkiwhp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nanxuanxn.top/Article/details/gteriwenje.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cqqwz.cn/Article/details/gtyfqplemp.html

[Q42] 连接条件附加过滤
来源：http://dali.daria6918.cn/Article/details/gtnekpcyry.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj202588.top/Article/details/gtzoyipkxi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.0kj1m.cn/Article/details/gtanqcdyun.html

[Q43] 标量子查询
来源：http://dali.chenzaomai.com/Article/details/gtcobikckq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yangfankeji.com/Article/details/gtxwcewhsr.html

[Q44] IN 子查询
来源：http://dali.yongpay.top/Article/details/gtwiidlnnx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.iojbl.cn/Article/details/gtzlajexfx.html

[Q45] EXISTS 判断存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtejzawwmg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenjidiqi.icu/Article/details/gtcbhxzgxd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gotoacloud.top/Article/details/gtpdsvybmh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tanke756.top/Article/details/gtayjiopte.html

[Q47] 与平均值比较
来源：http://dali.jyoumei.cn/Article/details/gteehbajjd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.daxiang520.top/Article/details/gtlynhopgs.html

[Q48] CTE 公用表表达式
来源：http://dali.jiagoushi.top/Article/details/gtexvlumct.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.pycfn.com/Article/details/gthiydgmgh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigufen.top/Article/details/gtqikphxyj.html

[Q49] 更新单行
来源：http://dali.tianlin.xyz/Article/details/gtytjuzilf.html


<!-- 参考信息 -->