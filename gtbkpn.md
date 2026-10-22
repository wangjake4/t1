代发 wailian999

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.c1oappe.top/Article/details/gtakhqftxm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hywenlv.cn/Article/details/gtwkurwluc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shzxlz.cn/Article/details/gtkeuldref.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xuanzx.com/Article/details/gtwgmiljin.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcccpjyai.html

[N10] 链表节点定义
来源：http://dali.redwolf501.top/Article/details/gtlenwwudy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gaohongyu789.top/Article/details/gtqqxdwtab.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenzaomai.com/Article/details/gtkygcollj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jqgfzy.top/Article/details/gtucmyiqaz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cashguo.top/Article/details/gtgdizbpxf.html

Java: class Node { int v; Node next; }
来源：http://dali.xziqi.cn/Article/details/gtsojuytst.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhoulong.xyz/Article/details/gtglglfuxk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hnqzz.top/Article/details/gtaccfnndo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.aibaodan.cn/Article/details/gtpbzsapwq.html

[N11] 二叉树中序遍历
来源：http://dali.yueranfly.top/Article/details/gtvlemxtsw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yuanzhike.top/Article/details/gtzvibtwac.html

PHP:  // 手写递归函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqwjnxju.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenzaomai.com/Article/details/gteqygkogq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guannengcc.top/Article/details/gtajdhjntx.html

Java: // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gtssinbcwi.html

Go:   // 手写递归
来源：http://dali.yonumen.top/Article/details/gttdxvsczj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsbqwbwmk.html

C#:   // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gtlmcllddv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jiagoushi.top/Article/details/gtzvunhjra.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.dianchejie.cn/Article/details/gtsdnsxrfm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shuidangran.top/Article/details/gtayiukmgb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sysykeji.top/Article/details/gtwldlmcqf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pengpengdd.cyou/Article/details/gtbmtttuwz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gtvomhoume.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.redwolf501.top/Article/details/gtnbcwcxoq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ydzc1.top/Article/details/gtwncasjij.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hongshengwenyu.top/Article/details/gtusiwvmcr.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtfehoffxn.html

O. 并发与异步
来源：http://dali.jqgfzy.top/Article/details/gtyejolkwt.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtywnzmsmx.html

[O01] 启动一个线程
来源：http://dali.ppjwa.cn/Article/details/gtzyhpjwhf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.andypj.xyz/Article/details/gtyjwcvdpa.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hywenlv.cn/Article/details/gtyolxqwqy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj20258.top/Article/details/gtekspsaoa.html

TS:   // 同 JS
来源：http://dali.nanxuanxn.top/Article/details/gtqagwucmk.html

Java: new Thread(() -> f()).start()
来源：http://dali.nwbrower.top/Article/details/gtizmkxvsw.html

Go:   go f()
来源：http://dali.nanxinkj.top/Article/details/gtopfkusdn.html

Ruby: Thread.new { f }
来源：http://dali.zhengqikj.top/Article/details/gtcxcmloem.html

C#:   Task.Run(() => F());
来源：http://dali.xinyue.icu/Article/details/gtoqdkgtfh.html

[O02] 使用线程池
来源：http://dali.ehwqpu.com/Article/details/gtevmauodx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cashguo.top/Article/details/gtcnxhjtlf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yueranfly.top/Article/details/gtenrksosb.html

JS:   // worker_threads 线程池
来源：http://dali.zycfv.cn/Article/details/gtxtujivxp.html

TS:   // worker_threads 线程池
来源：http://dali.guowangkeji.top/Article/details/gtdlkyoold.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hammf.cn/Article/details/gttazgpvuk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmeuvbkht.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.fengsongda.top/Article/details/gticzpemle.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cdnleiting.top/Article/details/gtsyqfjscy.html

[O03] 加锁保护共享数据
来源：http://dali.9152youxi.cn/Article/details/gtplkwjdbl.html

Py:   with lock: shared += 1
来源：http://dali.hongshengwenyu.top/Article/details/gtwbwqqwjk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.wangshuangyany.cn/Article/details/gteqzdeyuz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhiwuduotai.top/Article/details/gtjupmlntm.html

TS:   // 同 JS
来源：http://dali.gzhubu.top/Article/details/gtkopzuorb.html

Java: synchronized (this) { shared++; }
来源：http://dali.hfpthk.cn/Article/details/gtzmyzxroo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.316326.xyz/Article/details/gtqjxzsean.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.guannengcc.top/Article/details/gthmwluezq.html

C#:   lock (gate) { shared++; }
来源：http://dali.jqgufenzy.top/Article/details/gtgpvgxwjz.html

[O04] 定义异步函数并等待
来源：http://dali.snrcjt.cn/Article/details/gthljaazwb.html

Py:   async def f():⏎    await g()
来源：http://dali.ybcxt.top/Article/details/gtxdjdcdci.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.guowangkeji.top/Article/details/gtbtlquxtk.html

JS:   async function f() { await g(); }
来源：http://dali.daria6918.cn/Article/details/gtnzusgcjv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj202588.top/Article/details/gtyafedcwe.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.pycfn.com/Article/details/gtjamzpctq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.daria6918.cn/Article/details/gtpdbecyap.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxskkcyzm.html

C#:   async Task F() { await G(); }
来源：http://dali.dashuyun.cn/Article/details/gthyngxhnl.html

[O05] 并发执行并等待全部完成
来源：http://dali.feifeiyinyue.top/Article/details/gttcivzzmo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hywenlv.cn/Article/details/gtjmjignqw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.iojbl.cn/Article/details/gtzqksuuxj.html

JS:   await Promise.all(tasks)
来源：http://dali.zdqjudy.top/Article/details/gtbduldymw.html

TS:   await Promise.all(tasks)
来源：http://dali.aizwys.cn/Article/details/gtpldybccr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yongpay.top/Article/details/gtfugdezrr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.guannengcc.top/Article/details/gtpzavmwql.html

Ruby: threads.map(&:join)
来源：http://dali.tianlin.xyz/Article/details/gtjdongbee.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.aizwys.cn/Article/details/gtuytmcgta.html

[O06] 使用进程池
来源：http://dali.nanxinkj.top/Article/details/gtanweabrt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtougmdctr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyyioqizi.html

JS:   // child_process / cluster 模块
来源：http://dali.ivvv.top/Article/details/gtahrbdqqq.html

TS:   // child_process / cluster 模块
来源：http://dali.pengpengdd.cyou/Article/details/gtquqfmypo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.haohaochexian.top/Article/details/gtkfswwwre.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhixingplan.top/Article/details/gteeopwqsy.html

Ruby: // fork 块
来源：http://dali.havefunace.top/Article/details/gthzcebsdh.html

C#:   Parallel.For
来源：http://dali.tanke756.top/Article/details/gtcjxnfayn.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtmmuozdqe.html

P. 常用工具函数
来源：http://dali.tianlin.xyz/Article/details/gtxsfflbma.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtrliqwqho.html

[P01] 生成 UUID
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwqhpdua.html

Py:   str(uuid.uuid4())
来源：http://dali.hnxiangtu.top/Article/details/gtvthpmwxg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.fzhhl.top/Article/details/gtfdgrvzgp.html

JS:   crypto.randomUUID()
来源：http://dali.shuidangran.top/Article/details/gtgrqrhwsp.html

TS:   crypto.randomUUID()
来源：http://dali.pycfn.com/Article/details/gtbcbmdase.html

Java: UUID.randomUUID().toString()
来源：http://dali.jyoumei.cn/Article/details/gtkkhropbv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ybcxt.top/Article/details/gtynzfuhkz.html

Ruby: SecureRandom.uuid
来源：http://dali.cheryme.top/Article/details/gtvxwlvvme.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj20258.top/Article/details/gtbndtxnqq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cdnleiting.top/Article/details/gtjeyvpgjl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.andypj.xyz/Article/details/gtaboxpswf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cheryme.top/Article/details/gtywjseele.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jyoumei.cn/Article/details/gtvubspjrl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cheryme.top/Article/details/gtlnsvzbcq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hnqzz.top/Article/details/gtzjtfhktl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtbmpyaqwh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttatifpac.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shanyushiyangtech.top/Article/details/gtjukbwlzo.html

[P03] 生成短随机字符串
来源：http://dali.jlsjyb.cn/Article/details/gtxhzsjsdz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.mhx1999.top/Article/details/gtnnirazvh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.redwolf501.top/Article/details/gtlqzltihx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigufen.top/Article/details/gtbzlnttsd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhongyouzk.top/Article/details/gtovagzhlm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xinyue.icu/Article/details/gtjrhfcgsv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.tianlin.xyz/Article/details/gtiwsmnhrv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.dashuyun.cn/Article/details/gtwssmeohy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ybcxt.top/Article/details/gtshflkhwm.html

[P04] 求长度
来源：http://dali.smart0.xyz/Article/details/gtdydcphqd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.guowangkeji.top/Article/details/gthqayswzl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtzavipucj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hywenlv.cn/Article/details/gtoahxtpdj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cheryme.top/Article/details/gtgntvqltt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvifwuczc.html

Go:   len(arr);  len(m)
来源：http://dali.svipenyu.cn/Article/details/gtvmsvpaey.html

Ruby: x.length;  x.size
来源：http://dali.shzxlz.cn/Article/details/gtmfpcswly.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhoulong.xyz/Article/details/gtgnfatycv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gogol.net.cn/Article/details/gtykdpmemr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ydzc1.top/Article/details/gtpainojuy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hfpthk.cn/Article/details/gtucszlryk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinqigfzy.top/Article/details/gtdnqhorbx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ppjwa.cn/Article/details/gtcxgdsuem.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guowangkeji.top/Article/details/gtgtmxajod.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ivvv.top/Article/details/gtaxevxzpa.html

Ruby: a == b
来源：http://dali.shuidangran.top/Article/details/gthbnnryxn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cheryme.top/Article/details/gtqnahplat.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhixingplan.top/Article/details/gtooaplwea.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yj20258.top/Article/details/gtszaalfqx.html

PHP:  if (empty($x)) {}
来源：http://dali.yuanzhike.top/Article/details/gthkbspvol.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.wangshuangyany.cn/Article/details/gtyxvzvurf.html

TS:   if (x == null) {}
来源：http://dali.xziqi.cn/Article/details/gtgwndtkvs.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tanke756.top/Article/details/gtialhlsvr.html

Go:   if x == nil {}
来源：http://dali.yanxiufei.cn/Article/details/gtajsgmhzq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.guannengcc.top/Article/details/gtywsonvvw.html

C#:   if (x is null) {}
来源：http://dali.chenjidiqi.icu/Article/details/gttpogjtsf.html

[P07] 防抖与节流
来源：http://dali.kuanghao11.cn/Article/details/gthvinesqx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yangfankeji.com/Article/details/gtwgvxobey.html

PHP:  // 手写时间戳比较
来源：http://dali.hfpthk.cn/Article/details/gtsdtirqvv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zycfv.cn/Article/details/gtcjsofhpc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daria6918.cn/Article/details/gttdwdvcug.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.quarkkingdee.top/Article/details/gtpvsaxiln.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yueranfly.top/Article/details/gtpdvodxok.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.chenzaomai.com/Article/details/gtoigfkpln.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj20258.top/Article/details/gtluwjdmny.html

[P08] 处理浮点精度问题
来源：http://dali.hammf.cn/Article/details/gtlufmeepe.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhiwuduotai.top/Article/details/gtlflfmrvf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.smart0.xyz/Article/details/gtunecqjzu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sxryk.cn/Article/details/gtglnsfezc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtixohawwc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.bjfxy.top/Article/details/gtkhzxtcwo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nwbrower.top/Article/details/gtceqmdmps.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.dashuyun.cn/Article/details/gtlythrqjr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xinyue.icu/Article/details/gtxysvnunb.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtbzukskfs.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhengqikj.top/Article/details/gttdgjpzap.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtrejlikog.html

[Q01] 创建表
来源：http://dali.guannengcc.top/Article/details/gthsulvqpg.html

CREATE TABLE users (
来源：http://dali.bjfxy.top/Article/details/gtpdicxpag.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxuanxn.top/Article/details/gtvomejpng.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cucudq.cn/Article/details/gtszoqxlmz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.mhx1999.top/Article/details/gtswzidhvk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hywenlv.cn/Article/details/gttjvayoii.html

);
来源：http://dali.iojbl.cn/Article/details/gtcmoibwkc.html

[Q02] 创建带外键的表
来源：http://dali.daria6918.cn/Article/details/gtcurargzu.html

CREATE TABLE orders (
来源：http://dali.dianchejie.cn/Article/details/gtllsvmrle.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgfzy.top/Article/details/gtgoxutttk.html

user_id INT NOT NULL,
来源：http://dali.ydzc1.top/Article/details/gtaibkrqwf.html

amount DECIMAL(10, 2),
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjewbxwtb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jqgufenzy.top/Article/details/gtaaulhxzn.html

);
来源：http://dali.316326.xyz/Article/details/gtmhnqwalg.html

[Q03] 增加列
来源：http://dali.mhx1999.top/Article/details/gtgnwbpwvl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.c1oappe.top/Article/details/gtpfphlzsi.html

[Q04] 修改列类型
来源：http://dali.jinqigfzy.top/Article/details/gtzzyltzxt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sweek.top/Article/details/gtvaajsqcy.html

[Q05] 重命名列
来源：http://dali.chenzaomai.com/Article/details/gtjortrmyx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ydzc1.top/Article/details/gteggrfqwq.html

[Q06] 删除列
来源：http://dali.zdqjudy.top/Article/details/gtlbzhdsga.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.dianchejie.cn/Article/details/gtoskoltcy.html

[Q07] 删除表
来源：http://dali.c1oappe.top/Article/details/gtwmiwpbac.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xylfe.cn/Article/details/gtnxylznnc.html

[Q08] 创建普通索引
来源：http://dali.zhiwuduotai.top/Article/details/gtpoexdnmk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj20258.top/Article/details/gtqnhljjvu.html

[Q09] 创建唯一索引
来源：http://dali.wangshuangyany.cn/Article/details/gtrojostmz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ydzc1.top/Article/details/gtydamotkh.html

[Q10] 插入单行
来源：http://dali.0kj1m.cn/Article/details/gtgnxgmmld.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ywan-chungtsiang.top/Article/details/gthmmxffdj.html

[Q11] 一次插入多行
来源：http://dali.xuanzx.com/Article/details/gtyjomjceh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.fengsongda.top/Article/details/gtrqrjzmbu.html

[Q12] 插入后取自增 ID
来源：http://dali.xuetiantiany.cn/Article/details/gtiezojxfn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ybcxt.top/Article/details/gtxcpwsnyj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cdnleiting.top/Article/details/gtahycqtzm.html

[Q13] 忽略重复插入
来源：http://dali.ivvv.top/Article/details/gtorrkiytx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gtaonuagbi.html

[Q14] 存在则更新（upsert）
来源：http://dali.ppjwa.cn/Article/details/gtanyprphu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.smart0.xyz/Article/details/gtusisodhf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhsxxuvo.html

[Q15] 查询全部
来源：http://dali.daria6918.cn/Article/details/gtbdxzkgyl.html

SELECT * FROM users;
来源：http://dali.yvedp.cn/Article/details/gtbwzixzrb.html

[Q16] 查询指定列
来源：http://dali.yangfankeji.com/Article/details/gttudispxb.html

SELECT id, name FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtpphcltlo.html

[Q17] 条件查询
来源：http://dali.jyoumei.cn/Article/details/gtoqgvuwrn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxkmirhzi.html

[Q18] 模糊匹配
来源：http://dali.chenlongwang.top/Article/details/gtsoxgbnda.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.haohaochexian.top/Article/details/gtpgqvwxlm.html

[Q19] 范围查询
来源：http://dali.xinyue.icu/Article/details/gtbudozpcg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xinyue.icu/Article/details/gtancrjxhc.html

[Q20] IN 列表
来源：http://dali.havefunace.top/Article/details/gtttiytdro.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtizirxjhp.html

[Q21] 空值判断
来源：http://dali.0kj1m.cn/Article/details/gtvhbezhbf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tian-w.cn/Article/details/gtnvombgra.html

[Q22] 排序
来源：http://dali.daria6918.cn/Article/details/gtkbmmftbg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenzaomai.com/Article/details/gtdwvzylon.html

[Q23] 分页
来源：http://dali.sxryk.cn/Article/details/gtjxartydd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenlongwang.top/Article/details/gtnvyeymfe.html

[Q24] 去重
来源：http://dali.jiagoushi.top/Article/details/gttfpfztkt.html

SELECT DISTINCT city FROM users;
来源：http://dali.sysykeji.top/Article/details/gtfmbjolio.html

[Q25] 只取前 N 条
来源：http://dali.gaohongyu789.top/Article/details/gtmeitehqj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinghuilouyu.cn/Article/details/gtxeymosfb.html

[Q26] 计数
来源：http://dali.xuanzx.com/Article/details/gtdcflqiil.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj20258.top/Article/details/gtpqwiedhm.html

[Q27] 条件计数
来源：http://dali.hongshengwenyu.top/Article/details/gtuuozsxqj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gzhubu.top/Article/details/gtcbvkhedn.html

[Q28] 求和与平均
来源：http://dali.hnxiangtu.top/Article/details/gtxgzfmtve.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.birdmap.top/Article/details/gtsiazpgjl.html

[Q29] 最大最小值
来源：http://dali.svipenyu.cn/Article/details/gteulqognh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtymtzdfgh.html

[Q30] 分组统计
来源：http://dali.sysykeji.top/Article/details/gtnvgciphx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gtvtxpegoh.html

[Q31] 分组后过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtxckfjlzi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jqgfzy.top/Article/details/gtruxatpcf.html

[Q32] 分组拼接字符串
来源：http://dali.zhixingplan.top/Article/details/gtkkggrbno.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkvgxrevo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cheryme.top/Article/details/gtnbqketol.html

[Q33] 多列分组
来源：http://dali.yj20258.top/Article/details/gtrvamvtql.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ivvv.top/Article/details/gtlgvzwijo.html

[Q34] 每组取第一条
来源：http://dali.zhengqikj.top/Article/details/gtjqfxmgdy.html

SELECT * FROM (
来源：http://dali.quarkkingdee.top/Article/details/gtlmueryjn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tian-w.cn/Article/details/gtjgtohjvj.html

) t WHERE rn = 1;
来源：http://dali.0kj1m.cn/Article/details/gtnwwmbbua.html

[Q35] 内连接
来源：http://dali.haohaochexian.top/Article/details/gtkpopvrqz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnqzz.top/Article/details/gtpthuezni.html

[Q36] 左连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrsabsboq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj202588.top/Article/details/gtxpcrlzfj.html

[Q37] 右连接
来源：http://dali.0kj1m.cn/Article/details/gtwrxgkdaw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.mhx1999.top/Article/details/gtdwkmjtfs.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ehwqpu.com/Article/details/gtnlurbxyx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.smart0.xyz/Article/details/gtpubwbgfx.html

[Q39] 自连接（查上下级）
来源：http://dali.zdqjudy.top/Article/details/gtlplykxse.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinghuilouyu.cn/Article/details/gthybajrnh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cdnleiting.top/Article/details/gthsjkefuj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zycfv.cn/Article/details/gtxpylmgqn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.andypj.xyz/Article/details/gtckupxqqm.html

[Q41] 多表连接
来源：http://dali.smart0.xyz/Article/details/gtgprvuaeg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.meibo888.top/Article/details/gtyyyhvumu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hnqzz.top/Article/details/gtaahryejw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xuetiantiany.cn/Article/details/gterenafyx.html

[Q42] 连接条件附加过滤
来源：http://dali.snrcjt.cn/Article/details/gtabihwdho.html

SELECT u.name, o.amount FROM users u
来源：http://dali.dashuyun.cn/Article/details/gtmumulwva.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.iojbl.cn/Article/details/gtxterismm.html

[Q43] 标量子查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnybqncd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dashuyun.cn/Article/details/gtiyauxlff.html

[Q44] IN 子查询
来源：http://dali.kuanghao11.cn/Article/details/gtbrfmzhdd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yuanzhike.top/Article/details/gtlvdvojnu.html

[Q45] EXISTS 判断存在
来源：http://dali.xylfe.cn/Article/details/gtryasucsw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.0kj1m.cn/Article/details/gtpnnmkrdp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.iojbl.cn/Article/details/gtycguwzvh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fengsongda.top/Article/details/gtumlgmbuf.html

[Q47] 与平均值比较
来源：http://dali.dianchejie.cn/Article/details/gtohuksrtb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj20258.top/Article/details/gtanczoisz.html

[Q48] CTE 公用表表达式
来源：http://dali.gotoacloud.top/Article/details/gtqannubzb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sxryk.cn/Article/details/gtcdjjqwok.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ydzc1.top/Article/details/gtkncdbwyi.html

[Q49] 更新单行
来源：http://dali.xziqi.cn/Article/details/gtqdencxyv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cheryme.top/Article/details/gtybropmct.html

[Q50] 批量更新
来源：http://dali.ybcxt.top/Article/details/gtyhcutmce.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hammf.cn/Article/details/gtikduhgyj.html

[Q51] 用子查询更新
来源：http://dali.shzxlz.cn/Article/details/gtqvqkbzfc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuweebhde.html

[Q52] 删除指定行
来源：http://dali.cdnleiting.top/Article/details/gtcwxtvkuf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.aizwys.cn/Article/details/gtmckqmyof.html

[Q53] 按条件删除
来源：http://dali.jlsjyb.cn/Article/details/gtlyqvcezc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nanxuanxn.top/Article/details/gtattfvldu.html

[Q54] 清空表
来源：http://dali.xinyue.icu/Article/details/gtildgcsvk.html

TRUNCATE TABLE logs;
来源：http://dali.zhixingplan.top/Article/details/gtymdhlugm.html

[Q55] 排名（并列占位）
来源：http://dali.sufxvd.cn/Article/details/gtkiuwfzge.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.haohaochexian.top/Article/details/gtwqyimtgy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hnxiangtu.top/Article/details/gtvhezhzfx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shangyingyoupin.top/Article/details/gtcmxzistn.html

[Q57] 行号
来源：http://dali.pycfn.com/Article/details/gtrhiuzquv.html


<!-- 参考信息 -->