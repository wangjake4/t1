代发 wailian999

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenlongwang.top/Article/details/gtfntvhzlu.html

[N10] 链表节点定义
来源：http://dali.xinyue.icu/Article/details/gtpmcnnjge.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.birdmap.top/Article/details/gtjqazuaqu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hongshengwenyu.top/Article/details/gteoyolgfj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jianghu66.top/Article/details/gtxjksnnhl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenjidiqi.icu/Article/details/gtymwsmywn.html

Java: class Node { int v; Node next; }
来源：http://dali.xuetiantiany.cn/Article/details/gtujtfwdac.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhengqikj.top/Article/details/gthyeohjer.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shuidangran.top/Article/details/gttpgryiqm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj20258888.top/Article/details/gtpfskplno.html

[N11] 二叉树中序遍历
来源：http://dali.ivvv.top/Article/details/gtuqegrpnz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zycfv.cn/Article/details/gtmerxhfuv.html

PHP:  // 手写递归函数
来源：http://dali.shangyingyoupin.top/Article/details/gtxhvtyfdq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.c1oappe.top/Article/details/gtzdbrfpoq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gzhubu.top/Article/details/gtslbgpess.html

Java: // 手写递归
来源：http://dali.haohaochexian.top/Article/details/gtlbukubhj.html

Go:   // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gthsxpggud.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinqigfzy.top/Article/details/gtzftegdob.html

C#:   // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gtaefhqjdy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.aizwys.cn/Article/details/gtenksttph.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.dashuyun.cn/Article/details/gtlmgxveog.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cucudq.cn/Article/details/gtmlwxzzni.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.birdmap.top/Article/details/gtnmibsmfg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgufenzy.top/Article/details/gtpxzhedzh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinghuilouyu.cn/Article/details/gtthdtxlyf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xinyue.icu/Article/details/gtdrcogowf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jyoumei.cn/Article/details/gtczuhacqn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hongshengwenyu.top/Article/details/gtgenyldbe.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtrralrtcr.html

O. 并发与异步
来源：http://dali.jiagoushi.top/Article/details/gtlkwvtiya.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtqxgmtnlg.html

[O01] 启动一个线程
来源：http://dali.meibo888.top/Article/details/gtxvmihyqn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycqvhkrm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.quarkkingdee.top/Article/details/gtproszknc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinqigfzy.top/Article/details/gtvzaspwoq.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gtkkyrjrou.html

Java: new Thread(() -> f()).start()
来源：http://dali.dashuyun.cn/Article/details/gttlspkluu.html

Go:   go f()
来源：http://dali.guowangkeji.top/Article/details/gtzxbnbxnd.html

Ruby: Thread.new { f }
来源：http://dali.redwolf501.top/Article/details/gtxtenqtru.html

C#:   Task.Run(() => F());
来源：http://dali.pengpengdd.cyou/Article/details/gtwgumuyub.html

[O02] 使用线程池
来源：http://dali.jiagoushi.top/Article/details/gtqqolnywi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cucudq.cn/Article/details/gtwevljrxw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.feifeiyinyue.top/Article/details/gtaufwmfqf.html

JS:   // worker_threads 线程池
来源：http://dali.guannengcc.top/Article/details/gtydajskxx.html

TS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gtdetpkfzv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nwbrower.top/Article/details/gtjuhbalou.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hfpthk.cn/Article/details/gtwtrtibbt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yuanzhike.top/Article/details/gthryqnivm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yvedp.cn/Article/details/gtlqmxzccs.html

[O03] 加锁保护共享数据
来源：http://dali.yuxming.cn/Article/details/gttxwvawhq.html

Py:   with lock: shared += 1
来源：http://dali.yj202588.top/Article/details/gtkcxvrtqs.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cdnleiting.top/Article/details/gtuyewjqwh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdztdtuk.html

TS:   // 同 JS
来源：http://dali.yanxiufei.cn/Article/details/gtlamzrffo.html

Java: synchronized (this) { shared++; }
来源：http://dali.jqgfzy.top/Article/details/gtxptqrlcv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tian-w.cn/Article/details/gtgdlzgzrj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yanxiufei.cn/Article/details/gthnamyope.html

C#:   lock (gate) { shared++; }
来源：http://dali.hysaishi.cn/Article/details/gtwopznfmy.html

[O04] 定义异步函数并等待
来源：http://dali.sweek.top/Article/details/gtwsctlgtn.html

Py:   async def f():⏎    await g()
来源：http://dali.hysaishi.cn/Article/details/gtivxeywqy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhengqikj.top/Article/details/gtntirkpns.html

JS:   async function f() { await g(); }
来源：http://dali.hywenlv.cn/Article/details/gtibnoztjb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhoulong.xyz/Article/details/gtaqsosafb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthqdhymh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shangyingyoupin.top/Article/details/gtxuevdwzq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.smart0.xyz/Article/details/gtlxvwnrjs.html

C#:   async Task F() { await G(); }
来源：http://dali.xinyue.icu/Article/details/gtzvmlsngq.html

[O05] 并发执行并等待全部完成
来源：http://dali.yangfankeji.com/Article/details/gtlfwnyqzy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.fengsongda.top/Article/details/gtxnewiwtn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdmnkvrq.html

JS:   await Promise.all(tasks)
来源：http://dali.yueranfly.top/Article/details/gtmlahlbvb.html

TS:   await Promise.all(tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtxgkaonpz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gotoacloud.top/Article/details/gtaphgzbib.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.dashuyun.cn/Article/details/gtghkahjku.html

Ruby: threads.map(&:join)
来源：http://dali.sweek.top/Article/details/gtxvrmhpxs.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ydzc1.top/Article/details/gterpnkkku.html

[O06] 使用进程池
来源：http://dali.haohaochexian.top/Article/details/gthwrouajs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shuidangran.top/Article/details/gthpyiyvgu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.mhx1999.top/Article/details/gtqjfygfqy.html

JS:   // child_process / cluster 模块
来源：http://dali.cashguo.top/Article/details/gtywlyfcqn.html

TS:   // child_process / cluster 模块
来源：http://dali.chenzaomai.com/Article/details/gtlnrrkzap.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenlongwang.top/Article/details/gtgfpgaebm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cucudq.cn/Article/details/gttkzemisk.html

Ruby: // fork 块
来源：http://dali.tanke756.top/Article/details/gtrnsirnto.html

C#:   Parallel.For
来源：http://dali.shangyingyoupin.top/Article/details/gtsxovpiji.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtzqdobukd.html

P. 常用工具函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpraayblc.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrajizqfk.html

[P01] 生成 UUID
来源：http://dali.hysaishi.cn/Article/details/gtjcbfajal.html

Py:   str(uuid.uuid4())
来源：http://dali.aizwys.cn/Article/details/gtduotdzqc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nanxinkj.top/Article/details/gthyfgmdub.html

JS:   crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gtxmkttymy.html

TS:   crypto.randomUUID()
来源：http://dali.fengsongda.top/Article/details/gtvaltlsid.html

Java: UUID.randomUUID().toString()
来源：http://dali.guannengcc.top/Article/details/gtqqybeqml.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xziqi.cn/Article/details/gtkrnycxgk.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigufen.top/Article/details/gtxvfyrvin.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tian-w.cn/Article/details/gtstpfdqpm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.snrcjt.cn/Article/details/gtkdpzmosl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hammf.cn/Article/details/gtwuvtfgil.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.guannengcc.top/Article/details/gtzbwmsgvo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cucudq.cn/Article/details/gtmrwomdvn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ppjwa.cn/Article/details/gtspieuvtr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzsmhlmjr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yuxming.cn/Article/details/gtiqskuqbi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sysykeji.top/Article/details/gtcozdblvu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ybcxt.top/Article/details/gtzpdwknxl.html

[P03] 生成短随机字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxvlgeco.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.9152youxi.cn/Article/details/gtjqcwgkaa.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.wangdashe.top/Article/details/gtujkbyequ.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.bjfxy.top/Article/details/gtlxlvmdui.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxuanxn.top/Article/details/gtjvacqjix.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jianghu66.top/Article/details/gtxmkldrxx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj20258888.top/Article/details/gtbhhhtngw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xylfe.cn/Article/details/gtzzgogacc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.snrcjt.cn/Article/details/gtjxpsbxoc.html

[P04] 求长度
来源：http://dali.jlsjyb.cn/Article/details/gtbzuxezcg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nwbrower.top/Article/details/gtqbrttiwf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gtubzngksg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxrmmefak.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shzxlz.cn/Article/details/gtholtkghr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gtxeojutzb.html

Go:   len(arr);  len(m)
来源：http://dali.redwolf501.top/Article/details/gtqpxxyxrw.html

Ruby: x.length;  x.size
来源：http://dali.shangyingyoupin.top/Article/details/gtznlnrqye.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.nanxinkj.top/Article/details/gttpoghggs.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhixingplan.top/Article/details/gttfhurpqp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.havefunace.top/Article/details/gtsrmoyadi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.snrcjt.cn/Article/details/gtldutzwsu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tianlin.xyz/Article/details/gtsivdnmah.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cdnleiting.top/Article/details/gtzjfpekfl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ehwqpu.com/Article/details/gtytxcgzxh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.chenlongwang.top/Article/details/gtrevajgtp.html

Ruby: a == b
来源：http://dali.tian-w.cn/Article/details/gtynjxleea.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.aizwys.cn/Article/details/gtqvylervi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.iojbl.cn/Article/details/gtpfvvdiqf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xylfe.cn/Article/details/gtutzketbs.html

PHP:  if (empty($x)) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtuzgggueq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenzaomai.com/Article/details/gtusozehtp.html

TS:   if (x == null) {}
来源：http://dali.jiagoushi.top/Article/details/gtcxxpckaa.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzpqtdujy.html

Go:   if x == nil {}
来源：http://dali.xziqi.cn/Article/details/gtexfztkol.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.wangdashe.top/Article/details/gthzuhnhwo.html

C#:   if (x is null) {}
来源：http://dali.guowangkeji.top/Article/details/gtbnmhuykt.html

[P07] 防抖与节流
来源：http://dali.dashuyun.cn/Article/details/gtculeeeds.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.wangshuangyany.cn/Article/details/gtvdhedaoy.html

PHP:  // 手写时间戳比较
来源：http://dali.xuanzx.com/Article/details/gtbmwryqtd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cqqwz.cn/Article/details/gtirvouiyr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zdqjudy.top/Article/details/gtfsgezxbz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sxryk.cn/Article/details/gtaxqyxysl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cqqwz.cn/Article/details/gtgmoinbkm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hammf.cn/Article/details/gtjaymzaxx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hysaishi.cn/Article/details/gtqxmjnmzp.html

[P08] 处理浮点精度问题
来源：http://dali.gogol.net.cn/Article/details/gtioxgaxcz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj20258.top/Article/details/gtupyvdvjt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hammf.cn/Article/details/gtimcfseew.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gzhubu.top/Article/details/gtukilflbw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrurlnyyn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cashguo.top/Article/details/gtzntenxtv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hywenlv.cn/Article/details/gtnkunejfq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shzxlz.cn/Article/details/gtbvmbxhwt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cheryme.top/Article/details/gtyfrvkrzp.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtqzecgpwe.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ybcxt.top/Article/details/gtoluyzvnt.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtdmcxcqix.html

[Q01] 创建表
来源：http://dali.hongshengwenyu.top/Article/details/gtjpwqbdrv.html

CREATE TABLE users (
来源：http://dali.zdqjudy.top/Article/details/gtyqroqrvn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hywenlv.cn/Article/details/gtmdzpikrj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.dashuyun.cn/Article/details/gtadewulwy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.daria6918.cn/Article/details/gtdfdwhbir.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj20258.top/Article/details/gtoakcobds.html

);
来源：http://dali.xuanzx.com/Article/details/gtkfcqshuy.html

[Q02] 创建带外键的表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvlsjkchq.html

CREATE TABLE orders (
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrgtmlqw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daxiang520.top/Article/details/gtuqixvnxt.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gtjtmttlvn.html

amount DECIMAL(10, 2),
来源：http://dali.smart0.xyz/Article/details/gtephdedof.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jlsjyb.cn/Article/details/gtbuzztcwg.html

);
来源：http://dali.shuidangran.top/Article/details/gtcfeaszvn.html

[Q03] 增加列
来源：http://dali.xziqi.cn/Article/details/gtnarutgzg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jlsjyb.cn/Article/details/gtqmgotfim.html

[Q04] 修改列类型
来源：http://dali.sysykeji.top/Article/details/gtrnbhpizk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nanxuanxn.top/Article/details/gtpfhznuiu.html

[Q05] 重命名列
来源：http://dali.nanxuanxn.top/Article/details/gtfgjjiyrs.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sweek.top/Article/details/gtlxozqfmv.html

[Q06] 删除列
来源：http://dali.xuanzx.com/Article/details/gtmxpgzkiw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zycfv.cn/Article/details/gtijsycyid.html

[Q07] 删除表
来源：http://dali.yongpay.top/Article/details/gtncjzjfsd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ehwqpu.com/Article/details/gtgawxaujo.html

[Q08] 创建普通索引
来源：http://dali.nwbrower.top/Article/details/gtdnqeozqz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jqgfzy.top/Article/details/gtemazhoue.html

[Q09] 创建唯一索引
来源：http://dali.ybcxt.top/Article/details/gtkxecqgba.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.andypj.xyz/Article/details/gtppobbnbi.html

[Q10] 插入单行
来源：http://dali.xuanzx.com/Article/details/gtdcozgpna.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gtjrnzjjmb.html

[Q11] 一次插入多行
来源：http://dali.sufxvd.cn/Article/details/gtcnrkoeen.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.316326.xyz/Article/details/gtzhrsapvz.html

[Q12] 插入后取自增 ID
来源：http://dali.yangfankeji.com/Article/details/gtdwzibaoh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.pycfn.com/Article/details/gtwjtqtulr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.quarkkingdee.top/Article/details/gtdawlfkvg.html

[Q13] 忽略重复插入
来源：http://dali.zhiwuduotai.top/Article/details/gtlypnmmmi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.svipenyu.cn/Article/details/gttlelvrot.html

[Q14] 存在则更新（upsert）
来源：http://dali.hywenlv.cn/Article/details/gtndbvdmhh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cucudq.cn/Article/details/gtfuzqvmpy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.dianchejie.cn/Article/details/gtogdkkcew.html

[Q15] 查询全部
来源：http://dali.hnxiangtu.top/Article/details/gtjxanlqip.html

SELECT * FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtmmyysnfw.html

[Q16] 查询指定列
来源：http://dali.guowangkeji.top/Article/details/gtyjhuxmag.html

SELECT id, name FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtyjbhydha.html

[Q17] 条件查询
来源：http://dali.sweek.top/Article/details/gtccarjmxr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xuanzx.com/Article/details/gttxjshwgw.html

[Q18] 模糊匹配
来源：http://dali.yueranfly.top/Article/details/gtvjheanrs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yanxiufei.cn/Article/details/gtmppqpmzm.html

[Q19] 范围查询
来源：http://dali.tianlin.xyz/Article/details/gtqjrfnnrp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenjidiqi.icu/Article/details/gtirzmbewg.html

[Q20] IN 列表
来源：http://dali.yonumen.top/Article/details/gtfgedjyrm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhixingplan.top/Article/details/gtycjtallc.html

[Q21] 空值判断
来源：http://dali.jinqigufen.top/Article/details/gtmgpmndwo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nanxinkj.top/Article/details/gtvqgvlybf.html

[Q22] 排序
来源：http://dali.yuanzhike.top/Article/details/gthmmfbqtn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sweek.top/Article/details/gtxcbzfppy.html

[Q23] 分页
来源：http://dali.guowangkeji.top/Article/details/gtjkvnkwtd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xylfe.cn/Article/details/gtrzqmuqpu.html

[Q24] 去重
来源：http://dali.hnqzz.top/Article/details/gtsswavkok.html

SELECT DISTINCT city FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtxvxmlgam.html

[Q25] 只取前 N 条
来源：http://dali.jyoumei.cn/Article/details/gtowyfppoy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhengqikj.top/Article/details/gtislcpwgt.html

[Q26] 计数
来源：http://dali.sysykeji.top/Article/details/gtozruzuug.html

SELECT COUNT(*) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtgrnzqzlh.html

[Q27] 条件计数
来源：http://dali.tianlin.xyz/Article/details/gtjentdxni.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.andypj.xyz/Article/details/gtbtkqckam.html

[Q28] 求和与平均
来源：http://dali.xylfe.cn/Article/details/gtqwzeknwm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gthxitncyc.html

[Q29] 最大最小值
来源：http://dali.yonumen.top/Article/details/gtxzpgxodl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtnrtwhxat.html

[Q30] 分组统计
来源：http://dali.svipenyu.cn/Article/details/gtlxlrqszw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gtlkhfbebf.html

[Q31] 分组后过滤
来源：http://dali.nanxuanxn.top/Article/details/gtlnfbhkod.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shuidangran.top/Article/details/gtqwpcqofn.html

[Q32] 分组拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gtmkfchlff.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gtiurephff.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.pycfn.com/Article/details/gtdwgqyiem.html

[Q33] 多列分组
来源：http://dali.mhx1999.top/Article/details/gttgvehzyn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hywenlv.cn/Article/details/gtotyqlysu.html

[Q34] 每组取第一条
来源：http://dali.nanxinkj.top/Article/details/gteoleziei.html

SELECT * FROM (
来源：http://dali.tian-w.cn/Article/details/gtikduhngk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ppjwa.cn/Article/details/gtbhtfpsxk.html

) t WHERE rn = 1;
来源：http://dali.jyoumei.cn/Article/details/gtnosepeun.html

[Q35] 内连接
来源：http://dali.iojbl.cn/Article/details/gthvoogcot.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuetiantiany.cn/Article/details/gtbwfskidk.html

[Q36] 左连接
来源：http://dali.daxiang520.top/Article/details/gtkwngflhy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jianghu66.top/Article/details/gtgpdesqoh.html

[Q37] 右连接
来源：http://dali.hammf.cn/Article/details/gtuknonlbc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.dianchejie.cn/Article/details/gtvkkixxaj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jlsjyb.cn/Article/details/gthmspfnmo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinqigufen.top/Article/details/gtqfwceltk.html

[Q39] 自连接（查上下级）
来源：http://dali.dashuyun.cn/Article/details/gtyfcbazyc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nanxinkj.top/Article/details/gtvbwyzgus.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ybcxt.top/Article/details/gthbdbbraj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nwbrower.top/Article/details/gtejtdxgdh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.vqdsnc.cn/Article/details/gtwyischyr.html

[Q41] 多表连接
来源：http://dali.jqgfzy.top/Article/details/gttjpeopik.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jiagoushi.top/Article/details/gtylaettpr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sweek.top/Article/details/gtntmsengc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.iojbl.cn/Article/details/gtixczapuk.html

[Q42] 连接条件附加过滤
来源：http://dali.fengsongda.top/Article/details/gtjetqmpfh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhengqikj.top/Article/details/gtcldwgpvv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj202588.top/Article/details/gtcklpocmp.html

[Q43] 标量子查询
来源：http://dali.cheryme.top/Article/details/gttoulqnyg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jiagoushi.top/Article/details/gtmkhruxxw.html

[Q44] IN 子查询
来源：http://dali.cashguo.top/Article/details/gtvouqlxby.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj202588.top/Article/details/gtktahgnay.html

[Q45] EXISTS 判断存在
来源：http://dali.havefunace.top/Article/details/gtihtdptgx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gtrgybaolc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.kuanghao11.cn/Article/details/gtxesymesr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zdqjudy.top/Article/details/gtwczlxvqh.html

[Q47] 与平均值比较
来源：http://dali.9152youxi.cn/Article/details/gtmxzjuwzn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jianghu66.top/Article/details/gtvrbxijnb.html

[Q48] CTE 公用表表达式
来源：http://dali.nanxinkj.top/Article/details/gtggcznjho.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yueranfly.top/Article/details/gtqvwaqidc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.birdmap.top/Article/details/gtbvgrames.html

[Q49] 更新单行
来源：http://dali.jqgfzy.top/Article/details/gtcvpsvagw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfyqaoktn.html

[Q50] 批量更新
来源：http://dali.aibaodan.cn/Article/details/gtjnczvoru.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.svipenyu.cn/Article/details/gtxpisedyf.html

[Q51] 用子查询更新
来源：http://dali.iojbl.cn/Article/details/gtllwlltje.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.havefunace.top/Article/details/gtqquvxore.html

[Q52] 删除指定行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbsdotip.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gotoacloud.top/Article/details/gtrgssanyh.html

[Q53] 按条件删除
来源：http://dali.jqgufenzy.top/Article/details/gtetjjkcfj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.redwolf501.top/Article/details/gtsfqcbzye.html

[Q54] 清空表
来源：http://dali.chenlongwang.top/Article/details/gttdlqejab.html

TRUNCATE TABLE logs;
来源：http://dali.yuxming.cn/Article/details/gtnkvfiwvg.html

[Q55] 排名（并列占位）
来源：http://dali.sysykeji.top/Article/details/gtllnniorx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.316326.xyz/Article/details/gtmtxbfrfr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jlsjyb.cn/Article/details/gtgqevjifd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yuxming.cn/Article/details/gtyrzpzank.html

[Q57] 行号
来源：http://dali.c1oappe.top/Article/details/gtmzqxqcmv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtdpsstwlk.html

[Q58] 累计求和
来源：http://dali.cdnleiting.top/Article/details/gtnpncfmau.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtckxttuxl.html

[Q59] 分组内累计
来源：http://dali.ywan-chungtsiang.top/Article/details/gtazizrixs.html


<!-- 参考信息 -->