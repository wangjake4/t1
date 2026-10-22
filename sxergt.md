代发 wailian999

[N09] 栈与队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtopoxiimf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.quarkkingdee.top/Article/details/gtjzfhlyca.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.bjfxy.top/Article/details/gtteecgoul.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jyoumei.cn/Article/details/gthujesfig.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.c1oappe.top/Article/details/gtluumvggb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cdnleiting.top/Article/details/gtufrkivfc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hammf.cn/Article/details/gtkzgmabjl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gogol.net.cn/Article/details/gtbbggcuux.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jqgufenzy.top/Article/details/gtmzxfxyij.html

[N10] 链表节点定义
来源：http://dali.shanyushiyangtech.top/Article/details/gtkmpvpdar.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhixingplan.top/Article/details/gtmqassqxm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jlsjyb.cn/Article/details/gtaxcydxaq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.chenzaomai.com/Article/details/gtmzymiokp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gotoacloud.top/Article/details/gtvodqxxyf.html

Java: class Node { int v; Node next; }
来源：http://dali.yueranfly.top/Article/details/gtniijljgi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.feifeiyinyue.top/Article/details/gtucxdcjut.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.svipenyu.cn/Article/details/gtgokteetq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.fzhhl.top/Article/details/gtsvdbahmk.html

[N11] 二叉树中序遍历
来源：http://dali.wangdashe.top/Article/details/gtrmoiwhmr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xinyue.icu/Article/details/gtuwxfegrr.html

PHP:  // 手写递归函数
来源：http://dali.redwolf501.top/Article/details/gthljjgprc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenjidiqi.icu/Article/details/gtydianuhb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xziqi.cn/Article/details/gthvskalrw.html

Java: // 手写递归
来源：http://dali.jianghu66.top/Article/details/gtxlvnazso.html

Go:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gtewdiitfs.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.dashuyun.cn/Article/details/gtgutroxac.html

C#:   // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gtdizytumh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ehwqpu.com/Article/details/gttxccuwuk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtynqknqkf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.tian-w.cn/Article/details/gteulrpqhj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daxiang520.top/Article/details/gtkgfqzitc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqbihbjfd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tanke756.top/Article/details/gtmawehatk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.daria6918.cn/Article/details/gtyqmjzglz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gtuuisixlh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ehwqpu.com/Article/details/gthnkliuyd.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtaovrkcfo.html

O. 并发与异步
来源：http://dali.cqqwz.cn/Article/details/gtrysizbty.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtgtebqnka.html

[O01] 启动一个线程
来源：http://dali.sxryk.cn/Article/details/gtoenssgfk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yanxiufei.cn/Article/details/gtijdvgjrh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.guowangkeji.top/Article/details/gtwomfbmlk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xinyue.icu/Article/details/gtouhtcijc.html

TS:   // 同 JS
来源：http://dali.gaohongyu789.top/Article/details/gtbguflhvr.html

Java: new Thread(() -> f()).start()
来源：http://dali.haohaochexian.top/Article/details/gtrtabmyqk.html

Go:   go f()
来源：http://dali.ydzc1.top/Article/details/gtjuhtikwc.html

Ruby: Thread.new { f }
来源：http://dali.ydzc1.top/Article/details/gtiminclqt.html

C#:   Task.Run(() => F());
来源：http://dali.pycfn.com/Article/details/gtjrqcofej.html

[O02] 使用线程池
来源：http://dali.jiagoushi.top/Article/details/gtygspremr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zycfv.cn/Article/details/gtahonijkw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yanxiufei.cn/Article/details/gtbqtoihht.html

JS:   // worker_threads 线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gtzaopjnrk.html

TS:   // worker_threads 线程池
来源：http://dali.sysykeji.top/Article/details/gtbekvufto.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yonumen.top/Article/details/gtnpauzmep.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cheryme.top/Article/details/gtpzwctchx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.smart0.xyz/Article/details/gtqlltsmrx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sweek.top/Article/details/gtrbynwrbu.html

[O03] 加锁保护共享数据
来源：http://dali.jqgfzy.top/Article/details/gtnwjwaytz.html

Py:   with lock: shared += 1
来源：http://dali.daxiang520.top/Article/details/gtvafgcwgk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenjidiqi.icu/Article/details/gtwsnpppwf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yangfankeji.com/Article/details/gtdwmotujd.html

TS:   // 同 JS
来源：http://dali.yj20258888.top/Article/details/gtvvwuemtf.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtgyxrcfpd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hammf.cn/Article/details/gteuprithh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gotoacloud.top/Article/details/gtbtbbqxkm.html

C#:   lock (gate) { shared++; }
来源：http://dali.bjfxy.top/Article/details/gtdiqyiavn.html

[O04] 定义异步函数并等待
来源：http://dali.hammf.cn/Article/details/gtbilelkkr.html

Py:   async def f():⏎    await g()
来源：http://dali.mhx1999.top/Article/details/gtxsgfkfjb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yvedp.cn/Article/details/gttwsstxnc.html

JS:   async function f() { await g(); }
来源：http://dali.fzhhl.top/Article/details/gtcchtpwpl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gtcpoqxofk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.andypj.xyz/Article/details/gtrftkmcds.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.316326.xyz/Article/details/gtwhfsahsp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.pycfn.com/Article/details/gtklfnocjk.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258888.top/Article/details/gtlpcchrij.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenlongwang.top/Article/details/gthvykntwn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ybcxt.top/Article/details/gtiiikmumw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.wangshuangyany.cn/Article/details/gtbcedguiq.html

JS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmqdomhzb.html

TS:   await Promise.all(tasks)
来源：http://dali.aizwys.cn/Article/details/gtjpmtflmh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.guannengcc.top/Article/details/gtsvxzqeua.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhiwuduotai.top/Article/details/gtpjmitsrs.html

Ruby: threads.map(&:join)
来源：http://dali.aibaodan.cn/Article/details/gtwozzvwuv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jianghu66.top/Article/details/gtsqfwapqj.html

[O06] 使用进程池
来源：http://dali.cucudq.cn/Article/details/gttgmmqpko.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.guannengcc.top/Article/details/gtlthgobsa.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.pengpengdd.cyou/Article/details/gtwfmfofdp.html

JS:   // child_process / cluster 模块
来源：http://dali.yongpay.top/Article/details/gtibayhwcg.html

TS:   // child_process / cluster 模块
来源：http://dali.jianghu66.top/Article/details/gtvuylglpk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.svipenyu.cn/Article/details/gtdiknopdb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.chenlongwang.top/Article/details/gtstxoggwb.html

Ruby: // fork 块
来源：http://dali.sufxvd.cn/Article/details/gtfpembcav.html

C#:   Parallel.For
来源：http://dali.yanxiufei.cn/Article/details/gtmexvpbgf.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtxqprckzp.html

P. 常用工具函数
来源：http://dali.yanxiufei.cn/Article/details/gtymldtzui.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtgbddftet.html

[P01] 生成 UUID
来源：http://dali.fzhhl.top/Article/details/gtvptjgxio.html

Py:   str(uuid.uuid4())
来源：http://dali.hfpthk.cn/Article/details/gtbquszvww.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sweek.top/Article/details/gttgidrlzq.html

JS:   crypto.randomUUID()
来源：http://dali.gaohongyu789.top/Article/details/gtyacrelti.html

TS:   crypto.randomUUID()
来源：http://dali.sweek.top/Article/details/gtqsfvciro.html

Java: UUID.randomUUID().toString()
来源：http://dali.meibo888.top/Article/details/gtzrlcdcwq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shuidangran.top/Article/details/gtngfyelzo.html

Ruby: SecureRandom.uuid
来源：http://dali.chenjidiqi.icu/Article/details/gtwnvstazc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tanke756.top/Article/details/gtqqkkyxmx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.fzhhl.top/Article/details/gtzgehmzzk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cashguo.top/Article/details/gtpqhemwdo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nanxuanxn.top/Article/details/gtzduvprzc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ydzc1.top/Article/details/gtapgziduz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.guowangkeji.top/Article/details/gtjbomhpre.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gtumsuvoep.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yanxiufei.cn/Article/details/gtvamvfdqh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinqigufen.top/Article/details/gtwhykcvgd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.meibo888.top/Article/details/gtjwegnlae.html

[P03] 生成短随机字符串
来源：http://dali.dianchejie.cn/Article/details/gthkbgzzpd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.kuanghao11.cn/Article/details/gtxcsfupxb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cashguo.top/Article/details/gtvxeokqak.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gogol.net.cn/Article/details/gtgecjgszr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sweek.top/Article/details/gtiiajblgx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhoulong.xyz/Article/details/gtfgpgzlph.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinqigfzy.top/Article/details/gtrcrhtxbi.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.aibaodan.cn/Article/details/gttxolknkf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadwrhaxy.html

[P04] 求长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtmdlstoyd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.wangdashe.top/Article/details/gtflvrxpjt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtmtrefkgx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guowangkeji.top/Article/details/gtavlsbmjb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ehwqpu.com/Article/details/gtgeclylcb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.havefunace.top/Article/details/gtcyfjbvar.html

Go:   len(arr);  len(m)
来源：http://dali.sxryk.cn/Article/details/gtkkmcmkei.html

Ruby: x.length;  x.size
来源：http://dali.dianchejie.cn/Article/details/gtnczzzhao.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.316326.xyz/Article/details/gtxafbqpeq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nanxuanxn.top/Article/details/gtsmqrvlke.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.fengsongda.top/Article/details/gtuzbdbakd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.dashuyun.cn/Article/details/gtmvgqmitf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xziqi.cn/Article/details/gtsgpspxvj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtskegwagn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinghuilouyu.cn/Article/details/gtjttcmuga.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtlevwylti.html

Ruby: a == b
来源：http://dali.shzxlz.cn/Article/details/gtmgudhnfy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenzaomai.com/Article/details/gtdbwxyfxx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sufxvd.cn/Article/details/gtkidzeuwr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinqigfzy.top/Article/details/gtoveninwm.html

PHP:  if (empty($x)) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtijagnbev.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zycfv.cn/Article/details/gtyybcvrmh.html

TS:   if (x == null) {}
来源：http://dali.sufxvd.cn/Article/details/gtsvfwbbbd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gtofgzxmss.html

Go:   if x == nil {}
来源：http://dali.chenjidiqi.icu/Article/details/gttlgbtucd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.aizwys.cn/Article/details/gtvbidfwgu.html

C#:   if (x is null) {}
来源：http://dali.jinqigufen.top/Article/details/gtnbridimb.html

[P07] 防抖与节流
来源：http://dali.xuanzx.com/Article/details/gtlyracwpx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cucudq.cn/Article/details/gtspdteaek.html

PHP:  // 手写时间戳比较
来源：http://dali.zycfv.cn/Article/details/gtakfeypzb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gtlabkglrj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zycfv.cn/Article/details/gtxwkxlrzj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtynioswee.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hysaishi.cn/Article/details/gtdpujezdk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinqigfzy.top/Article/details/gtrksihaxw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yanxiufei.cn/Article/details/gtfbybisel.html

[P08] 处理浮点精度问题
来源：http://dali.jianghu66.top/Article/details/gtwnqtvbgh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zycfv.cn/Article/details/gtvnlzapoo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtwgrjnjjs.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.chenzaomai.com/Article/details/gtiwohptgn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.nanxuanxn.top/Article/details/gtpuivmjub.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.tanke756.top/Article/details/gtafdgamox.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.0kj1m.cn/Article/details/gtcofftdqj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhoulong.xyz/Article/details/gtczbxgzga.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gaohongyu789.top/Article/details/gtczlozpaa.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtniidrfms.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.guannengcc.top/Article/details/gtxlkfrlmu.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtmzanzdoy.html

[Q01] 创建表
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkluyukr.html

CREATE TABLE users (
来源：http://dali.jyoumei.cn/Article/details/gtooxlsakb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenlongwang.top/Article/details/gtnsvzrotx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yonumen.top/Article/details/gtdxfkrdql.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sysykeji.top/Article/details/gtzgcduemp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gtzycrihlz.html

);
来源：http://dali.ppjwa.cn/Article/details/gtjscnzhwd.html

[Q02] 创建带外键的表
来源：http://dali.c1oappe.top/Article/details/gttlaylpdd.html

CREATE TABLE orders (
来源：http://dali.snrcjt.cn/Article/details/gtarzmswas.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zycfv.cn/Article/details/gtzuqbveou.html

user_id INT NOT NULL,
来源：http://dali.wangdashe.top/Article/details/gtfhhrwexr.html

amount DECIMAL(10, 2),
来源：http://dali.cashguo.top/Article/details/gtjnwnbrpa.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtipgvspga.html

);
来源：http://dali.cucudq.cn/Article/details/gtpccvyhal.html

[Q03] 增加列
来源：http://dali.jianghu66.top/Article/details/gtwqcpmuzq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.meibo888.top/Article/details/gtbmegxtpc.html

[Q04] 修改列类型
来源：http://dali.yvedp.cn/Article/details/gtidfgjliy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jqgfzy.top/Article/details/gtjvlrsqgn.html

[Q05] 重命名列
来源：http://dali.yonumen.top/Article/details/gtmcwjtmwf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdgojbdid.html

[Q06] 删除列
来源：http://dali.jianghu66.top/Article/details/gttdisxrrh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jianghu66.top/Article/details/gtzpindhvc.html

[Q07] 删除表
来源：http://dali.yuanzhike.top/Article/details/gtzvoshprr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shzxlz.cn/Article/details/gtwhourdmx.html

[Q08] 创建普通索引
来源：http://dali.birdmap.top/Article/details/gtdvxvxzfu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ivvv.top/Article/details/gtbvzbswit.html

[Q09] 创建唯一索引
来源：http://dali.kuanghao11.cn/Article/details/gtqgojhjqq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhixingplan.top/Article/details/gtkxanalrs.html

[Q10] 插入单行
来源：http://dali.cdnleiting.top/Article/details/gtuqehvupm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gtdnahcwbb.html

[Q11] 一次插入多行
来源：http://dali.aizwys.cn/Article/details/gtbqmwcapp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hongshengwenyu.top/Article/details/gtzmgmrzjr.html

[Q12] 插入后取自增 ID
来源：http://dali.yuxming.cn/Article/details/gthfyzxwef.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hywenlv.cn/Article/details/gtlqmbjebm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jlsjyb.cn/Article/details/gtvptisxfq.html

[Q13] 忽略重复插入
来源：http://dali.hfpthk.cn/Article/details/gtpdinzdyd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pengpengdd.cyou/Article/details/gtgkpppmpz.html

[Q14] 存在则更新（upsert）
来源：http://dali.jqgufenzy.top/Article/details/gtcsdzsxvv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yuanzhike.top/Article/details/gtnicnqiin.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jlsjyb.cn/Article/details/gtmqjrbjqb.html

[Q15] 查询全部
来源：http://dali.ybcxt.top/Article/details/gthwtqepje.html

SELECT * FROM users;
来源：http://dali.yj202588.top/Article/details/gtemjtoojr.html

[Q16] 查询指定列
来源：http://dali.ydzc1.top/Article/details/gtpqcivxiy.html

SELECT id, name FROM users;
来源：http://dali.shuidangran.top/Article/details/gtgbyitnyj.html

[Q17] 条件查询
来源：http://dali.sysykeji.top/Article/details/gtdqqzmqme.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.aibaodan.cn/Article/details/gthcuoymph.html

[Q18] 模糊匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtdpotntup.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.kuanghao11.cn/Article/details/gtmnghegba.html

[Q19] 范围查询
来源：http://dali.yj202588.top/Article/details/gtehaixycc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jiagoushi.top/Article/details/gtvfbgehqf.html

[Q20] IN 列表
来源：http://dali.tian-w.cn/Article/details/gtyssijcxf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.aibaodan.cn/Article/details/gttspvvnok.html

[Q21] 空值判断
来源：http://dali.mhx1999.top/Article/details/gtngrpiapg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sxryk.cn/Article/details/gtqrjjieoy.html

[Q22] 排序
来源：http://dali.nanxinkj.top/Article/details/gtdfkgdvkk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhoulong.xyz/Article/details/gtjqgrqkpl.html

[Q23] 分页
来源：http://dali.snrcjt.cn/Article/details/gtlmtqrznt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.havefunace.top/Article/details/gtosaskkca.html

[Q24] 去重
来源：http://dali.guowangkeji.top/Article/details/gtdsmrrwae.html

SELECT DISTINCT city FROM users;
来源：http://dali.sxryk.cn/Article/details/gtugkbtdpr.html

[Q25] 只取前 N 条
来源：http://dali.redwolf501.top/Article/details/gtcyzeugev.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hysaishi.cn/Article/details/gtnboyvdkn.html

[Q26] 计数
来源：http://dali.yueranfly.top/Article/details/gtaldggqjq.html

SELECT COUNT(*) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtmdcamfeo.html

[Q27] 条件计数
来源：http://dali.jianghu66.top/Article/details/gtlaiclsjo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtesldlajx.html

[Q28] 求和与平均
来源：http://dali.aizwys.cn/Article/details/gtksoltqvn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gttbrsspdr.html

[Q29] 最大最小值
来源：http://dali.yvedp.cn/Article/details/gtaeolhsbg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtlujkgbrs.html

[Q30] 分组统计
来源：http://dali.sweek.top/Article/details/gtpoauvfkq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zycfv.cn/Article/details/gtkugjvnqq.html

[Q31] 分组后过滤
来源：http://dali.haohaochexian.top/Article/details/gtljdnomyb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhixingplan.top/Article/details/gtdrgytskx.html

[Q32] 分组拼接字符串
来源：http://dali.yj20258888.top/Article/details/gtulcyqmfl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gtiozdlxwu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hnqzz.top/Article/details/gtlkpmwkpx.html

[Q33] 多列分组
来源：http://dali.ydzc1.top/Article/details/gtkzsebyoc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.havefunace.top/Article/details/gtxqaqtage.html

[Q34] 每组取第一条
来源：http://dali.yuanzhike.top/Article/details/gttcyooyov.html

SELECT * FROM (
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdbbldrhv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.dianchejie.cn/Article/details/gtjwispzpv.html

) t WHERE rn = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtwmsxxvzb.html

[Q35] 内连接
来源：http://dali.sufxvd.cn/Article/details/gtmkjjuzrd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cqqwz.cn/Article/details/gttzkivxff.html

[Q36] 左连接
来源：http://dali.hysaishi.cn/Article/details/gtmliibkbr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hongshengwenyu.top/Article/details/gtlmywlcle.html

[Q37] 右连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtumvbknyv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jyoumei.cn/Article/details/gtjcvqgvao.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hysaishi.cn/Article/details/gtoeyjslvy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj20258.top/Article/details/gthxfozkme.html

[Q39] 自连接（查上下级）
来源：http://dali.yangfankeji.com/Article/details/gtutpxkwef.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifouthge.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenzaomai.com/Article/details/gtpgurqrli.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinghuilouyu.cn/Article/details/gtbumqmimv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.bjfxy.top/Article/details/gtltqufezy.html

[Q41] 多表连接
来源：http://dali.jyoumei.cn/Article/details/gtrndjjcso.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhixingplan.top/Article/details/gtmuqihooy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.dianchejie.cn/Article/details/gtyqahvxdr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.0kj1m.cn/Article/details/gteuznguym.html

[Q42] 连接条件附加过滤
来源：http://dali.quarkkingdee.top/Article/details/gtrhbhxuku.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuetiantiany.cn/Article/details/gtixiswsez.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jlsjyb.cn/Article/details/gtlqmuhtvc.html

[Q43] 标量子查询
来源：http://dali.ivvv.top/Article/details/gtrandajwc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yanxiufei.cn/Article/details/gtutopjvdi.html

[Q44] IN 子查询
来源：http://dali.sufxvd.cn/Article/details/gtkrzstumt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yangfankeji.com/Article/details/gtauitsfhx.html

[Q45] EXISTS 判断存在
来源：http://dali.yongpay.top/Article/details/gtpxragtij.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sufxvd.cn/Article/details/gtiznlhogb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tianlin.xyz/Article/details/gtjzwrxgej.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aizwys.cn/Article/details/gthbtnvhvc.html

[Q47] 与平均值比较
来源：http://dali.quarkkingdee.top/Article/details/gtswgaqnrx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.snrcjt.cn/Article/details/gthjwjackj.html

[Q48] CTE 公用表表达式
来源：http://dali.ydzc1.top/Article/details/gtricxfeih.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zycfv.cn/Article/details/gtknfrpqfz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cqqwz.cn/Article/details/gtvtdfbzen.html

[Q49] 更新单行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbbonzxew.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gtjbprcqbu.html

[Q50] 批量更新
来源：http://dali.9152youxi.cn/Article/details/gtgncwelhb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.dashuyun.cn/Article/details/gteluvimon.html

[Q51] 用子查询更新
来源：http://dali.yongpay.top/Article/details/gtmahbfble.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.wangdashe.top/Article/details/gttzlhlgom.html

[Q52] 删除指定行
来源：http://dali.tanke756.top/Article/details/gtwervrtti.html

DELETE FROM users WHERE id = 10;
来源：http://dali.aibaodan.cn/Article/details/gtswzwmoqk.html

[Q53] 按条件删除
来源：http://dali.dianchejie.cn/Article/details/gtfcfjbwgs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jiagoushi.top/Article/details/gtzigjhest.html

[Q54] 清空表
来源：http://dali.gaohongyu789.top/Article/details/gthnifkadx.html

TRUNCATE TABLE logs;
来源：http://dali.ybcxt.top/Article/details/gtmzfqltei.html

[Q55] 排名（并列占位）
来源：http://dali.gaohongyu789.top/Article/details/gtlrarvgod.html


<!-- 参考信息 -->