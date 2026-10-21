代发 wailian999

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zycfv.cn/Article/details/gtpsdbwqgg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhixingplan.top/Article/details/gtasmudekd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhoulong.xyz/Article/details/gtodsywyss.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ydzc1.top/Article/details/gtbczklmss.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gaohongyu789.top/Article/details/gtsynfedbb.html

[N10] 链表节点定义
来源：http://dali.cucudq.cn/Article/details/gtdqyplnhn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.9152youxi.cn/Article/details/gtevbivrej.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shangyingyoupin.top/Article/details/gtbnxugvcc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jiagoushi.top/Article/details/gtznzoyezr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xuetiantiany.cn/Article/details/gttteukjmq.html

Java: class Node { int v; Node next; }
来源：http://dali.hammf.cn/Article/details/gttpmsjtjw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.guowangkeji.top/Article/details/gtopldumtf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.haohaochexian.top/Article/details/gtholvctgk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jqgufenzy.top/Article/details/gtbqlkixuv.html

[N11] 二叉树中序遍历
来源：http://dali.fzhhl.top/Article/details/gtkocrnljc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zycfv.cn/Article/details/gtuytqdhne.html

PHP:  // 手写递归函数
来源：http://dali.cdnleiting.top/Article/details/gthfsbiluu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258888.top/Article/details/gtwrlqecom.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ehwqpu.com/Article/details/gthgylhbbe.html

Java: // 手写递归
来源：http://dali.9152youxi.cn/Article/details/gtbthlotlw.html

Go:   // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gtoaudvksh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shuidangran.top/Article/details/gtkyefuhsu.html

C#:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gthjtzndwk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ppjwa.cn/Article/details/gtpijamcfu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.quarkkingdee.top/Article/details/gtmbalkzqw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gzhubu.top/Article/details/gtzqzgzzcw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuetiantiany.cn/Article/details/gtqxhtqdum.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hongshengwenyu.top/Article/details/gttdyuzxib.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shuidangran.top/Article/details/gtysyvyjyb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jlsjyb.cn/Article/details/gtdcawzsyt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sufxvd.cn/Article/details/gtlfmfwggx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.c1oappe.top/Article/details/gtaxivnatp.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtdcjaqcze.html

O. 并发与异步
来源：http://dali.jinqigfzy.top/Article/details/gtzyjhfgqt.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtlvqycgbj.html

[O01] 启动一个线程
来源：http://dali.hnqzz.top/Article/details/gtwjpcglpf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinqigfzy.top/Article/details/gtxzqiwwtg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj202588.top/Article/details/gtuasiktvg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.wangshuangyany.cn/Article/details/gtdqfbmxfk.html

TS:   // 同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcgxmqcre.html

Java: new Thread(() -> f()).start()
来源：http://dali.fzhhl.top/Article/details/gtldsbtaow.html

Go:   go f()
来源：http://dali.9152youxi.cn/Article/details/gtxlyasrkp.html

Ruby: Thread.new { f }
来源：http://dali.jianghu66.top/Article/details/gtrlilfwks.html

C#:   Task.Run(() => F());
来源：http://dali.hnqzz.top/Article/details/gtczibxugg.html

[O02] 使用线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkhxphpfd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.guannengcc.top/Article/details/gtwtifktwd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cheryme.top/Article/details/gtxhogvypv.html

JS:   // worker_threads 线程池
来源：http://dali.cdnleiting.top/Article/details/gtepxdwtne.html

TS:   // worker_threads 线程池
来源：http://dali.yj202588.top/Article/details/gttpwcsahc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.birdmap.top/Article/details/gtdizuyvfw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.daxiang520.top/Article/details/gtqjubyrop.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sweek.top/Article/details/gtrikpbavf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xuetiantiany.cn/Article/details/gtpnllmwci.html

[O03] 加锁保护共享数据
来源：http://dali.hongshengwenyu.top/Article/details/gtpxvzdnmg.html

Py:   with lock: shared += 1
来源：http://dali.yvedp.cn/Article/details/gtrwsbslwe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.nanxuanxn.top/Article/details/gtxezpaytb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj202588.top/Article/details/gtplxtgfov.html

TS:   // 同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtuhzwbo.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhixingplan.top/Article/details/gtllgzuvjk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.dashuyun.cn/Article/details/gtvlavcoop.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.bjfxy.top/Article/details/gtycganrbn.html

C#:   lock (gate) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gtbqutrdaz.html

[O04] 定义异步函数并等待
来源：http://dali.yj20258.top/Article/details/gtfapgbxod.html

Py:   async def f():⏎    await g()
来源：http://dali.shuidangran.top/Article/details/gtcergfcji.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ehwqpu.com/Article/details/gtlylhktmw.html

JS:   async function f() { await g(); }
来源：http://dali.hywenlv.cn/Article/details/gthuqskhjt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yonumen.top/Article/details/gtnmbovjtr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fzhhl.top/Article/details/gtwyrdvltb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.pycfn.com/Article/details/gtwsnencwl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.fzhhl.top/Article/details/gtvpabqktp.html

C#:   async Task F() { await G(); }
来源：http://dali.sweek.top/Article/details/gtynhkdtrc.html

[O05] 并发执行并等待全部完成
来源：http://dali.jqgfzy.top/Article/details/gtpszhzuai.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgfzy.top/Article/details/gtwynyearx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenzaomai.com/Article/details/gtbqumatul.html

JS:   await Promise.all(tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtigjftyns.html

TS:   await Promise.all(tasks)
来源：http://dali.zhengqikj.top/Article/details/gthxpzuozk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhongyouzk.top/Article/details/gtpznbalrq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jiagoushi.top/Article/details/gtbpfcthqk.html

Ruby: threads.map(&:join)
来源：http://dali.havefunace.top/Article/details/gtelftfekt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jianghu66.top/Article/details/gtpcpjtvka.html

[O06] 使用进程池
来源：http://dali.dianchejie.cn/Article/details/gtdnahmoss.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jianghu66.top/Article/details/gtalumyxpe.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.0kj1m.cn/Article/details/gtwfohfwme.html

JS:   // child_process / cluster 模块
来源：http://dali.vqdsnc.cn/Article/details/gtonifgpur.html

TS:   // child_process / cluster 模块
来源：http://dali.bjfxy.top/Article/details/gtrtewwaza.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.quarkkingdee.top/Article/details/gtzeuhhgbb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj202588.top/Article/details/gtlocrkoua.html

Ruby: // fork 块
来源：http://dali.jqgufenzy.top/Article/details/gtavheagkp.html

C#:   Parallel.For
来源：http://dali.nanxinkj.top/Article/details/gtvvwghple.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gturfszudo.html

P. 常用工具函数
来源：http://dali.xylfe.cn/Article/details/gtalqjplgm.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtjpahsjkt.html

[P01] 生成 UUID
来源：http://dali.zhixingplan.top/Article/details/gtccrdasie.html

Py:   str(uuid.uuid4())
来源：http://dali.shzxlz.cn/Article/details/gtbrerquvy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cucudq.cn/Article/details/gtqyblipwt.html

JS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfncqqklr.html

TS:   crypto.randomUUID()
来源：http://dali.redwolf501.top/Article/details/gthiuoxlkl.html

Java: UUID.randomUUID().toString()
来源：http://dali.yvedp.cn/Article/details/gtbygmolrm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xuetiantiany.cn/Article/details/gtohkbicqw.html

Ruby: SecureRandom.uuid
来源：http://dali.aizwys.cn/Article/details/gtsyissabh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj20258888.top/Article/details/gtkppimyza.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yvedp.cn/Article/details/gtqpispzyw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.feifeiyinyue.top/Article/details/gtefqpiwmi.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtcpdzxhwv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.snrcjt.cn/Article/details/gtqnobakjq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gotoacloud.top/Article/details/gtdppwgeyy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.9152youxi.cn/Article/details/gtbuonqsal.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xuanzx.com/Article/details/gtdcnrpnow.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtasmzyqzk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.iojbl.cn/Article/details/gtbdddbmrq.html

[P03] 生成短随机字符串
来源：http://dali.meibo888.top/Article/details/gtdhkrnmjx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.fengsongda.top/Article/details/gtuuydmmop.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.316326.xyz/Article/details/gtuungespz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sufxvd.cn/Article/details/gtwdebnvkj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guowangkeji.top/Article/details/gttlvrawnp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaeoxaots.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.smart0.xyz/Article/details/gtohsqofsm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.daxiang520.top/Article/details/gtihzgqrah.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnxiangtu.top/Article/details/gtsrdolmzs.html

[P04] 求长度
来源：http://dali.316326.xyz/Article/details/gtsrfarmun.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.daria6918.cn/Article/details/gtarevpooj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gtxmockpcu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.birdmap.top/Article/details/gtplzyixgg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgfzy.top/Article/details/gtesvhtphj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuslnckvl.html

Go:   len(arr);  len(m)
来源：http://dali.xylfe.cn/Article/details/gtowxwolgf.html

Ruby: x.length;  x.size
来源：http://dali.pengpengdd.cyou/Article/details/gtkftgxofh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdywefzqo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hnxiangtu.top/Article/details/gtxnninyng.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.havefunace.top/Article/details/gttejqbjsm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hammf.cn/Article/details/gtxwsnwwtc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhengqikj.top/Article/details/gtdghqhfly.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdfcsume.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tian-w.cn/Article/details/gtsqdfftrt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtwpvmkmoh.html

Ruby: a == b
来源：http://dali.hammf.cn/Article/details/gtaueqzzgr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.wangshuangyany.cn/Article/details/gtjoqdixew.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.aibaodan.cn/Article/details/gtrcjbdqmf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.svipenyu.cn/Article/details/gtjqjrtcad.html

PHP:  if (empty($x)) {}
来源：http://dali.316326.xyz/Article/details/gtguhjotym.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jlsjyb.cn/Article/details/gtddccutzs.html

TS:   if (x == null) {}
来源：http://dali.jlsjyb.cn/Article/details/gthkesekbp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.9152youxi.cn/Article/details/gtvuphvcmj.html

Go:   if x == nil {}
来源：http://dali.fengsongda.top/Article/details/gtbfaqrluy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gaohongyu789.top/Article/details/gtzfhqpifm.html

C#:   if (x is null) {}
来源：http://dali.yuanzhike.top/Article/details/gtlejtelel.html

[P07] 防抖与节流
来源：http://dali.shuidangran.top/Article/details/gtcrihwtms.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.fzhhl.top/Article/details/gtvmsrfzps.html

PHP:  // 手写时间戳比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkeiiblp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daxiang520.top/Article/details/gtjjxcgvlx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gttnybocix.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.c1oappe.top/Article/details/gtuplxujiy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.nwbrower.top/Article/details/gtedvpkhmm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ydzc1.top/Article/details/gtlsyulqzt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nanxinkj.top/Article/details/gtvjynziiq.html

[P08] 处理浮点精度问题
来源：http://dali.wangdashe.top/Article/details/gtmqayatwz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj202588.top/Article/details/gtsyaevfgx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj20258888.top/Article/details/gtaqkzityq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tianlin.xyz/Article/details/gtebglrmud.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.fzhhl.top/Article/details/gtwnzcnurv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.aizwys.cn/Article/details/gtmmvdmavs.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.bjfxy.top/Article/details/gtxyhzoauc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xinyue.icu/Article/details/gtcjljktwz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.andypj.xyz/Article/details/gtydndjxiq.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtwxgbbnap.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.daria6918.cn/Article/details/gtdqtwqdfd.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtrfffatfr.html

[Q01] 创建表
来源：http://dali.shuidangran.top/Article/details/gtbpjauwxk.html

CREATE TABLE users (
来源：http://dali.cqqwz.cn/Article/details/gtbkurxwtm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daxiang520.top/Article/details/gtxiljemjj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.haohaochexian.top/Article/details/gtutighkgr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.meibo888.top/Article/details/gtmbhhuibq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xuetiantiany.cn/Article/details/gtddpiemjx.html

);
来源：http://dali.hywenlv.cn/Article/details/gtpocpdana.html

[Q02] 创建带外键的表
来源：http://dali.iojbl.cn/Article/details/gtjxstmgev.html

CREATE TABLE orders (
来源：http://dali.nwbrower.top/Article/details/gtpdogyhpo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cheryme.top/Article/details/gtyadoywwn.html

user_id INT NOT NULL,
来源：http://dali.chenjidiqi.icu/Article/details/gttwsqftpo.html

amount DECIMAL(10, 2),
来源：http://dali.hfpthk.cn/Article/details/gtqlnytzdr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cashguo.top/Article/details/gtsimdlyws.html

);
来源：http://dali.wangshuangyany.cn/Article/details/gtlrurwjlv.html

[Q03] 增加列
来源：http://dali.jinqigufen.top/Article/details/gtuznkgzdp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.quarkkingdee.top/Article/details/gtiouanwas.html

[Q04] 修改列类型
来源：http://dali.chenzaomai.com/Article/details/gtnuxwekcb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hysaishi.cn/Article/details/gtrgeyzacv.html

[Q05] 重命名列
来源：http://dali.sysykeji.top/Article/details/gtuhjasxkk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dianchejie.cn/Article/details/gtbjtqjuim.html

[Q06] 删除列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoelkokpb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.316326.xyz/Article/details/gtjrogyszz.html

[Q07] 删除表
来源：http://dali.hysaishi.cn/Article/details/gtaphfvgum.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yangfankeji.com/Article/details/gtofgjiwyy.html

[Q08] 创建普通索引
来源：http://dali.meibo888.top/Article/details/gtspvgmngn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.meibo888.top/Article/details/gtgxbpiuyn.html

[Q09] 创建唯一索引
来源：http://dali.xylfe.cn/Article/details/gtkdygykfr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.birdmap.top/Article/details/gtxkmvxphg.html

[Q10] 插入单行
来源：http://dali.jyoumei.cn/Article/details/gtfpyoxocy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hongshengwenyu.top/Article/details/gthjxcodnu.html

[Q11] 一次插入多行
来源：http://dali.jiagoushi.top/Article/details/gtsaavnpdg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cashguo.top/Article/details/gthkkdllsz.html

[Q12] 插入后取自增 ID
来源：http://dali.meibo888.top/Article/details/gtotkzdgdm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hongshengwenyu.top/Article/details/gtmivaphxf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sxryk.cn/Article/details/gtzdrfaaen.html

[Q13] 忽略重复插入
来源：http://dali.aibaodan.cn/Article/details/gtusstvvzr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinqigufen.top/Article/details/gtyvumuelx.html

[Q14] 存在则更新（upsert）
来源：http://dali.jyoumei.cn/Article/details/gttkjlepdx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gzhubu.top/Article/details/gtsgfbwicq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tianlin.xyz/Article/details/gtfeivqosf.html

[Q15] 查询全部
来源：http://dali.haohaochexian.top/Article/details/gtoiioezdk.html

SELECT * FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtiugcnqyd.html

[Q16] 查询指定列
来源：http://dali.yuanzhike.top/Article/details/gtiscgxrel.html

SELECT id, name FROM users;
来源：http://dali.yueranfly.top/Article/details/gtuxdqmdia.html

[Q17] 条件查询
来源：http://dali.hysaishi.cn/Article/details/gtbyryyjrd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hywenlv.cn/Article/details/gtinmogwqj.html

[Q18] 模糊匹配
来源：http://dali.jinqigufen.top/Article/details/gtivpufcwz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.iojbl.cn/Article/details/gtgjtguppp.html

[Q19] 范围查询
来源：http://dali.tianlin.xyz/Article/details/gtfhspsiqz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zdqjudy.top/Article/details/gtfvkfjhno.html

[Q20] IN 列表
来源：http://dali.xinyue.icu/Article/details/gtuwnaxiwj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.iojbl.cn/Article/details/gtlmagsxuo.html

[Q21] 空值判断
来源：http://dali.yvedp.cn/Article/details/gtfrliukgg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gogol.net.cn/Article/details/gtompjwlnm.html

[Q22] 排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gthuzztaow.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hnqzz.top/Article/details/gtixivxoxi.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gtguxtivmy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jiagoushi.top/Article/details/gthfklveii.html

[Q24] 去重
来源：http://dali.cqqwz.cn/Article/details/gtbvpojvvf.html

SELECT DISTINCT city FROM users;
来源：http://dali.c1oappe.top/Article/details/gtdnkpmdcu.html

[Q25] 只取前 N 条
来源：http://dali.cashguo.top/Article/details/gtkbgkhsqi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.vqdsnc.cn/Article/details/gtscvachhu.html

[Q26] 计数
来源：http://dali.fengsongda.top/Article/details/gtirnqbzyw.html

SELECT COUNT(*) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtyhpgyuls.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gtbwdzyyrz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtsxgpgtuc.html

[Q28] 求和与平均
来源：http://dali.xuetiantiany.cn/Article/details/gtofggnete.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtjkewxpbf.html

[Q29] 最大最小值
来源：http://dali.zycfv.cn/Article/details/gtmzxwbuua.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtqwptnrrr.html

[Q30] 分组统计
来源：http://dali.xinyue.icu/Article/details/gtiejguuqi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gtwjyxfpyn.html

[Q31] 分组后过滤
来源：http://dali.svipenyu.cn/Article/details/gtwhgcsthc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nanxinkj.top/Article/details/gtheixqtfx.html

[Q32] 分组拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gtqvpyorgn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.316326.xyz/Article/details/gtyrjlrjgm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hnxiangtu.top/Article/details/gtmaucintg.html

[Q33] 多列分组
来源：http://dali.yj202588.top/Article/details/gtvckvqgki.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.iojbl.cn/Article/details/gtpbmjigup.html

[Q34] 每组取第一条
来源：http://dali.andypj.xyz/Article/details/gtzlrgshss.html

SELECT * FROM (
来源：http://dali.sysykeji.top/Article/details/gtxzqrnaqf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.dashuyun.cn/Article/details/gtzkryrkob.html

) t WHERE rn = 1;
来源：http://dali.aibaodan.cn/Article/details/gtclnenjmy.html

[Q35] 内连接
来源：http://dali.yongpay.top/Article/details/gtkadlybjt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gthefjmdar.html

[Q36] 左连接
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmvhgqqw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.smart0.xyz/Article/details/gttfeqomlj.html

[Q37] 右连接
来源：http://dali.hnqzz.top/Article/details/gtdbrwxpaj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tianlin.xyz/Article/details/gtcjxkmyvn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jianghu66.top/Article/details/gtzaknxqec.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.birdmap.top/Article/details/gteblnfemu.html

[Q39] 自连接（查上下级）
来源：http://dali.dashuyun.cn/Article/details/gtlonmmhsp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zycfv.cn/Article/details/gtjfuavgxo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.aizwys.cn/Article/details/gtrosprabf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.snrcjt.cn/Article/details/gtocfhcmci.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.pycfn.com/Article/details/gtoaurdsdy.html

[Q41] 多表连接
来源：http://dali.xylfe.cn/Article/details/gtssddsdno.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.wangdashe.top/Article/details/gtuuxmhgab.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hnqzz.top/Article/details/gtkxerkgvb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.quarkkingdee.top/Article/details/gtcavtqfhf.html

[Q42] 连接条件附加过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtuabkmpfa.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj20258.top/Article/details/gtgvkagnjh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.316326.xyz/Article/details/gtjnyhlvrv.html

[Q43] 标量子查询
来源：http://dali.nanxinkj.top/Article/details/gtmjygfsjf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhongyouzk.top/Article/details/gtkrlrypvz.html

[Q44] IN 子查询
来源：http://dali.daxiang520.top/Article/details/gtytvqtgxf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.aizwys.cn/Article/details/gtwdexkjct.html

[Q45] EXISTS 判断存在
来源：http://dali.ppjwa.cn/Article/details/gtrsuyjtin.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxuanxn.top/Article/details/gtlzaqlrjb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangdashe.top/Article/details/gtkyxjwdas.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.316326.xyz/Article/details/gtamwvbppf.html

[Q47] 与平均值比较
来源：http://dali.yj20258888.top/Article/details/gtujdactvg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkuemqycs.html

[Q48] CTE 公用表表达式
来源：http://dali.gaohongyu789.top/Article/details/gtdusmhror.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hnxiangtu.top/Article/details/gtblcdjwut.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zdqjudy.top/Article/details/gtyaufigvm.html

[Q49] 更新单行
来源：http://dali.chenlongwang.top/Article/details/gtsjtzpbgb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.wangshuangyany.cn/Article/details/gtlvljjmsg.html

[Q50] 批量更新
来源：http://dali.havefunace.top/Article/details/gttnzjiufq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sysykeji.top/Article/details/gtiywlqdxk.html

[Q51] 用子查询更新
来源：http://dali.zhiwuduotai.top/Article/details/gtferjflzk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.guowangkeji.top/Article/details/gthudgxbat.html

[Q52] 删除指定行
来源：http://dali.hywenlv.cn/Article/details/gtrxkzfxru.html

DELETE FROM users WHERE id = 10;
来源：http://dali.smart0.xyz/Article/details/gtafajjcps.html

[Q53] 按条件删除
来源：http://dali.jinqigfzy.top/Article/details/gtdoqymclq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nanxinkj.top/Article/details/gtdfibrkku.html

[Q54] 清空表
来源：http://dali.feifeiyinyue.top/Article/details/gtjfampfdn.html

TRUNCATE TABLE logs;
来源：http://dali.pycfn.com/Article/details/gthexibzur.html

[Q55] 排名（并列占位）
来源：http://dali.jinqigufen.top/Article/details/gtmzrnmdif.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hammf.cn/Article/details/gtjqkuhyva.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shzxlz.cn/Article/details/gtseywzdmd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xziqi.cn/Article/details/gtmvqokxqp.html

[Q57] 行号
来源：http://dali.snrcjt.cn/Article/details/gtiuuepcfw.html


<!-- 参考信息 -->