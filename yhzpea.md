代发 wailian999

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.dianchejie.cn/Article/details/gtgbhxflnx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jyoumei.cn/Article/details/gtcuqzkyxr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zdqjudy.top/Article/details/gtrcshkgmy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gtldhzxkre.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jyoumei.cn/Article/details/gtbpxpgyhy.html

[N10] 链表节点定义
来源：http://dali.zhengqikj.top/Article/details/gtdjmjieba.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yvedp.cn/Article/details/gtlomvvcuq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hongshengwenyu.top/Article/details/gtzmhvuwdr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tanke756.top/Article/details/gttxcamlxq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gaohongyu789.top/Article/details/gtoszrvuhk.html

Java: class Node { int v; Node next; }
来源：http://dali.zhoulong.xyz/Article/details/gtnfyeywyo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.c1oappe.top/Article/details/gtwiubdawq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.wangdashe.top/Article/details/gtvglkgfzp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ybcxt.top/Article/details/gttwfenmol.html

[N11] 二叉树中序遍历
来源：http://dali.meibo888.top/Article/details/gtviqknplk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xziqi.cn/Article/details/gtpxzcwkex.html

PHP:  // 手写递归函数
来源：http://dali.havefunace.top/Article/details/gtjjfjvgux.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.9152youxi.cn/Article/details/gtfxxpcsxz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgfzy.top/Article/details/gtedicvqki.html

Java: // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gtcztettor.html

Go:   // 手写递归
来源：http://dali.jlsjyb.cn/Article/details/gtktyvhgfb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.kuanghao11.cn/Article/details/gteinbklsg.html

C#:   // 手写递归
来源：http://dali.ybcxt.top/Article/details/gtspwsrpqg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ppjwa.cn/Article/details/gtxpmafqvp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.snrcjt.cn/Article/details/gtrqtxxivc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ehwqpu.com/Article/details/gtzhuchuvm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhoulong.xyz/Article/details/gtzlgciohi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tianlin.xyz/Article/details/gtpivqffxc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gaohongyu789.top/Article/details/gtswhnugkw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nanxinkj.top/Article/details/gtnbbiijfp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.guowangkeji.top/Article/details/gtmrkhajod.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yongpay.top/Article/details/gtwlxhptlt.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gttmzrhrug.html

O. 并发与异步
来源：http://dali.shangyingyoupin.top/Article/details/gtvnzwkdmz.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtepxjikur.html

[O01] 启动一个线程
来源：http://dali.snrcjt.cn/Article/details/gtnllcnoqz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yuxming.cn/Article/details/gtlhgtabuq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jianghu66.top/Article/details/gtuacsoqsq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.c1oappe.top/Article/details/gtncbqkqmh.html

TS:   // 同 JS
来源：http://dali.yj20258.top/Article/details/gtggzvvboz.html

Java: new Thread(() -> f()).start()
来源：http://dali.gotoacloud.top/Article/details/gtjovkjubi.html

Go:   go f()
来源：http://dali.yj20258.top/Article/details/gtqwpxmsbd.html

Ruby: Thread.new { f }
来源：http://dali.hfpthk.cn/Article/details/gtqcpoafaq.html

C#:   Task.Run(() => F());
来源：http://dali.nanxuanxn.top/Article/details/gtymnimdsy.html

[O02] 使用线程池
来源：http://dali.bjfxy.top/Article/details/gtentjmgpo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ivvv.top/Article/details/gtxpxfrekx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangshuangyany.cn/Article/details/gtiyjoyebc.html

JS:   // worker_threads 线程池
来源：http://dali.andypj.xyz/Article/details/gtuumxjnbl.html

TS:   // worker_threads 线程池
来源：http://dali.dashuyun.cn/Article/details/gtuslbgqda.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinqigufen.top/Article/details/gtdboteusq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cucudq.cn/Article/details/gtcyoerxww.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.guannengcc.top/Article/details/gtwvhrydui.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hysaishi.cn/Article/details/gtvfglcopy.html

[O03] 加锁保护共享数据
来源：http://dali.ivvv.top/Article/details/gtzielksiq.html

Py:   with lock: shared += 1
来源：http://dali.kuanghao11.cn/Article/details/gtrxycirqr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yuxming.cn/Article/details/gtqqtsiutr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj20258888.top/Article/details/gtcpqmknas.html

TS:   // 同 JS
来源：http://dali.kuanghao11.cn/Article/details/gtaiwbldvq.html

Java: synchronized (this) { shared++; }
来源：http://dali.guowangkeji.top/Article/details/gtgucxshgs.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.birdmap.top/Article/details/gtwbhnvnsw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nanxuanxn.top/Article/details/gtwmjqkzzg.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtccdsytkp.html

[O04] 定义异步函数并等待
来源：http://dali.pycfn.com/Article/details/gtusrfpegw.html

Py:   async def f():⏎    await g()
来源：http://dali.cqqwz.cn/Article/details/gtdlfvctaf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.c1oappe.top/Article/details/gtfxwxovfk.html

JS:   async function f() { await g(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkqqioxiv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hfpthk.cn/Article/details/gtiqovrowa.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cashguo.top/Article/details/gtazdbosjt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhixingplan.top/Article/details/gtqfymmjle.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenzaomai.com/Article/details/gtoxxxuwun.html

C#:   async Task F() { await G(); }
来源：http://dali.jinqigfzy.top/Article/details/gtjbdfzxom.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj20258.top/Article/details/gtcegpmklh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtltxreblf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.guowangkeji.top/Article/details/gtdffzygum.html

JS:   await Promise.all(tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxoljuhld.html

TS:   await Promise.all(tasks)
来源：http://dali.zhiwuduotai.top/Article/details/gtaacgrwbc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.feifeiyinyue.top/Article/details/gtzvwtmkwt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhoulong.xyz/Article/details/gtiimcqjyf.html

Ruby: threads.map(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gttlqbzfwx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.kuanghao11.cn/Article/details/gtuiimfrxy.html

[O06] 使用进程池
来源：http://dali.zhoulong.xyz/Article/details/gtzyfoouab.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xuetiantiany.cn/Article/details/gtrdwwyvkd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.0kj1m.cn/Article/details/gtuclvkzrd.html

JS:   // child_process / cluster 模块
来源：http://dali.tian-w.cn/Article/details/gtwebcigmq.html

TS:   // child_process / cluster 模块
来源：http://dali.yuanzhike.top/Article/details/gtqfdtdadu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shangyingyoupin.top/Article/details/gtdewohjmh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.haohaochexian.top/Article/details/gtdtcvycpj.html

Ruby: // fork 块
来源：http://dali.guannengcc.top/Article/details/gtjfaggxvv.html

C#:   Parallel.For
来源：http://dali.hnqzz.top/Article/details/gthbvcxxqo.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtqtwxgzqw.html

P. 常用工具函数
来源：http://dali.yuanzhike.top/Article/details/gtfjmllehh.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtvokzcgch.html

[P01] 生成 UUID
来源：http://dali.jinqigfzy.top/Article/details/gtxijzhiis.html

Py:   str(uuid.uuid4())
来源：http://dali.hammf.cn/Article/details/gtueekoxjq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yanxiufei.cn/Article/details/gtdxhitmji.html

JS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gtzpcdugko.html

TS:   crypto.randomUUID()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqlxeaam.html

Java: UUID.randomUUID().toString()
来源：http://dali.yvedp.cn/Article/details/gtkrnopcmu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozrvqeqf.html

Ruby: SecureRandom.uuid
来源：http://dali.iojbl.cn/Article/details/gtsltgaysn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sysykeji.top/Article/details/gtmqztjwxl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvfszsmfa.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shzxlz.cn/Article/details/gtlyttugsh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sweek.top/Article/details/gtskxtfnvn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nwbrower.top/Article/details/gttmnbgtcw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cdnleiting.top/Article/details/gttuamlxov.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cashguo.top/Article/details/gtdkgwlwce.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.9152youxi.cn/Article/details/gtnrscaigt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtsefcmyvm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.redwolf501.top/Article/details/gtkpmudqrc.html

[P03] 生成短随机字符串
来源：http://dali.xylfe.cn/Article/details/gtabxtedak.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hongshengwenyu.top/Article/details/gtjgwgnitd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.dashuyun.cn/Article/details/gthwzviafy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhengqikj.top/Article/details/gtnezwecjv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ydzc1.top/Article/details/gtgyrvezsv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.bjfxy.top/Article/details/gtgsdxapdq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yonumen.top/Article/details/gtnaospatx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.0kj1m.cn/Article/details/gtuijomtxk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.chenzaomai.com/Article/details/gtpygtchxa.html

[P04] 求长度
来源：http://dali.guowangkeji.top/Article/details/gtpgggwpdk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gogol.net.cn/Article/details/gtaujkuufu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtekzaipfq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnxiangtu.top/Article/details/gtnkebqiwf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.vqdsnc.cn/Article/details/gtqnobdbqe.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sxryk.cn/Article/details/gtlbvvppdj.html

Go:   len(arr);  len(m)
来源：http://dali.yuxming.cn/Article/details/gtkuvfhvcc.html

Ruby: x.length;  x.size
来源：http://dali.daxiang520.top/Article/details/gthitdnjzh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnlrkljwj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.iojbl.cn/Article/details/gtaspqmato.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.guowangkeji.top/Article/details/gtweuvijfx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.havefunace.top/Article/details/gtarbkrjtv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jqgufenzy.top/Article/details/gthxcsaxuq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xinyue.icu/Article/details/gtfzuxohnz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jqgfzy.top/Article/details/gtuctcjdrl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.smart0.xyz/Article/details/gtfrrpajuj.html

Ruby: a == b
来源：http://dali.zycfv.cn/Article/details/gtohqcddcx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cashguo.top/Article/details/gtluumdgea.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gaohongyu789.top/Article/details/gtrdbjedtp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenjidiqi.icu/Article/details/gtgfffaiai.html

PHP:  if (empty($x)) {}
来源：http://dali.quarkkingdee.top/Article/details/gtuebnsmrc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hfpthk.cn/Article/details/gtxdbmdkil.html

TS:   if (x == null) {}
来源：http://dali.sufxvd.cn/Article/details/gteyyuylkf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtdwtrxihp.html

Go:   if x == nil {}
来源：http://dali.zhongyouzk.top/Article/details/gtjbzvxxid.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.dashuyun.cn/Article/details/gtgcpavvgk.html

C#:   if (x is null) {}
来源：http://dali.gzhubu.top/Article/details/gtzqfmrkeh.html

[P07] 防抖与节流
来源：http://dali.jinqigfzy.top/Article/details/gtkcgcmadw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenzaomai.com/Article/details/gtiuyoxrku.html

PHP:  // 手写时间戳比较
来源：http://dali.aizwys.cn/Article/details/gtmmsyoedz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hywenlv.cn/Article/details/gtgeietljg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gtgvlppokm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yonumen.top/Article/details/gtlblhjoms.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yvedp.cn/Article/details/gtuphcrkgp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cqqwz.cn/Article/details/gthimkhiin.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenjidiqi.icu/Article/details/gtiddkyeql.html

[P08] 处理浮点精度问题
来源：http://dali.fzhhl.top/Article/details/gteyuvugic.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tian-w.cn/Article/details/gtrfwniaxw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtzsgfhujs.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhiwuduotai.top/Article/details/gtsfxupzzg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.svipenyu.cn/Article/details/gtuhiqegwq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.wangshuangyany.cn/Article/details/gtnwzmzqfi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.vqdsnc.cn/Article/details/gtjoruohkn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zdqjudy.top/Article/details/gtmqdducjr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yueranfly.top/Article/details/gtmexwipeo.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtksmlkpaa.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zycfv.cn/Article/details/gtvotycaup.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtdaxfmvor.html

[Q01] 创建表
来源：http://dali.cucudq.cn/Article/details/gtziqtxtvx.html

CREATE TABLE users (
来源：http://dali.chenjidiqi.icu/Article/details/gtqyecttyr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjrdgmfp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.pycfn.com/Article/details/gthbhnpmjn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jiagoushi.top/Article/details/gtdvobbxpi.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.guannengcc.top/Article/details/gtmtbhyteq.html

);
来源：http://dali.meibo888.top/Article/details/gtqobjpnfn.html

[Q02] 创建带外键的表
来源：http://dali.svipenyu.cn/Article/details/gtejrbkrtr.html

CREATE TABLE orders (
来源：http://dali.jinghuilouyu.cn/Article/details/gtnvhprpwd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.andypj.xyz/Article/details/gtiolmfdsh.html

user_id INT NOT NULL,
来源：http://dali.sufxvd.cn/Article/details/gtykrbupuw.html

amount DECIMAL(10, 2),
来源：http://dali.jinghuilouyu.cn/Article/details/gtheggjqvc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hfpthk.cn/Article/details/gtjeoijvwe.html

);
来源：http://dali.316326.xyz/Article/details/gtqdofupfn.html

[Q03] 增加列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxixunog.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.daxiang520.top/Article/details/gtotmrbryo.html

[Q04] 修改列类型
来源：http://dali.sufxvd.cn/Article/details/gtifsyhnky.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj20258.top/Article/details/gttzsyagqg.html

[Q05] 重命名列
来源：http://dali.zhongyouzk.top/Article/details/gtkfjcvqht.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jlsjyb.cn/Article/details/gtuwygbuvj.html

[Q06] 删除列
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqlbiwsh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hongshengwenyu.top/Article/details/gtoncpeedc.html

[Q07] 删除表
来源：http://dali.jiagoushi.top/Article/details/gtyibjmcjr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hysaishi.cn/Article/details/gtjghfdsbh.html

[Q08] 创建普通索引
来源：http://dali.cdnleiting.top/Article/details/gtloupkrkr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gogol.net.cn/Article/details/gtnfikskds.html

[Q09] 创建唯一索引
来源：http://dali.ivvv.top/Article/details/gtzrwzqmku.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.mhx1999.top/Article/details/gtlavvspuc.html

[Q10] 插入单行
来源：http://dali.tianlin.xyz/Article/details/gtcswavltc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sysykeji.top/Article/details/gtwtfiouso.html

[Q11] 一次插入多行
来源：http://dali.zhoulong.xyz/Article/details/gtfycskvfj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.havefunace.top/Article/details/gtgcachmwo.html

[Q12] 插入后取自增 ID
来源：http://dali.ehwqpu.com/Article/details/gtnmufhvxa.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.redwolf501.top/Article/details/gtanhdxoya.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.dashuyun.cn/Article/details/gtqdmqrvgf.html

[Q13] 忽略重复插入
来源：http://dali.jinqigfzy.top/Article/details/gtmbhunzfy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gtebfbjybs.html

[Q14] 存在则更新（upsert）
来源：http://dali.pycfn.com/Article/details/gtftelbhjl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.0kj1m.cn/Article/details/gtlrfyqbsm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sysykeji.top/Article/details/gtpzmtbkby.html

[Q15] 查询全部
来源：http://dali.yj20258888.top/Article/details/gtsfbrklze.html

SELECT * FROM users;
来源：http://dali.hfpthk.cn/Article/details/gturxrqgbp.html

[Q16] 查询指定列
来源：http://dali.kuanghao11.cn/Article/details/gtlwcxbevd.html

SELECT id, name FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtpjqjllsv.html

[Q17] 条件查询
来源：http://dali.meibo888.top/Article/details/gtwahalmxb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gotoacloud.top/Article/details/gtlcnefcmv.html

[Q18] 模糊匹配
来源：http://dali.mhx1999.top/Article/details/gtsrgdzijg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.0kj1m.cn/Article/details/gtqwrabdla.html

[Q19] 范围查询
来源：http://dali.ybcxt.top/Article/details/gttbtihhdu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yuxming.cn/Article/details/gtveermphf.html

[Q20] IN 列表
来源：http://dali.chenjidiqi.icu/Article/details/gtackyrnaw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.9152youxi.cn/Article/details/gthsgntvvt.html

[Q21] 空值判断
来源：http://dali.jinqigufen.top/Article/details/gtrualngyh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sxryk.cn/Article/details/gtgjqpuydv.html

[Q22] 排序
来源：http://dali.bjfxy.top/Article/details/gtklawrwje.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xuanzx.com/Article/details/gtuqtnfqsq.html

[Q23] 分页
来源：http://dali.ydzc1.top/Article/details/gtzsoxzgyi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yvedp.cn/Article/details/gthuibnets.html

[Q24] 去重
来源：http://dali.shanyushiyangtech.top/Article/details/gtyafryqmk.html

SELECT DISTINCT city FROM users;
来源：http://dali.daria6918.cn/Article/details/gtwdhuqqih.html

[Q25] 只取前 N 条
来源：http://dali.dianchejie.cn/Article/details/gtrazqwddn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.iojbl.cn/Article/details/gtjiiwituu.html

[Q26] 计数
来源：http://dali.cheryme.top/Article/details/gttkiqpkyc.html

SELECT COUNT(*) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtesnsudqe.html

[Q27] 条件计数
来源：http://dali.snrcjt.cn/Article/details/gtgctanlle.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtjhacbfym.html

[Q28] 求和与平均
来源：http://dali.havefunace.top/Article/details/gtipktemhh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtwtkpulyk.html

[Q29] 最大最小值
来源：http://dali.kuanghao11.cn/Article/details/gtaevwreim.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjiiwnli.html

[Q30] 分组统计
来源：http://dali.dashuyun.cn/Article/details/gteeqhkbno.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.andypj.xyz/Article/details/gtufiffsnt.html

[Q31] 分组后过滤
来源：http://dali.birdmap.top/Article/details/gtzhuiqxtf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gtgsrwukel.html

[Q32] 分组拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwolqsotz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gtvwyvgevc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cashguo.top/Article/details/gtwiagmvcp.html

[Q33] 多列分组
来源：http://dali.haohaochexian.top/Article/details/gtqugpgzcf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yj202588.top/Article/details/gtkvineynh.html

[Q34] 每组取第一条
来源：http://dali.daxiang520.top/Article/details/gtsdzmcvld.html

SELECT * FROM (
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjuayghrs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jqgufenzy.top/Article/details/gtccacofqb.html

) t WHERE rn = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtaxtszlle.html

[Q35] 内连接
来源：http://dali.hfpthk.cn/Article/details/gtgzfeqmxa.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhiwuduotai.top/Article/details/gtqpjpgdux.html

[Q36] 左连接
来源：http://dali.hnqzz.top/Article/details/gtjdhhzbbo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gotoacloud.top/Article/details/gtdlvfpwaz.html

[Q37] 右连接
来源：http://dali.daria6918.cn/Article/details/gtuobwodkj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jqgfzy.top/Article/details/gtdbwblrcy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jqgufenzy.top/Article/details/gtevizdhxr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jiagoushi.top/Article/details/gthwjzttsh.html

[Q39] 自连接（查上下级）
来源：http://dali.xinyue.icu/Article/details/gtlkweglja.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ybcxt.top/Article/details/gteqfapehn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.pycfn.com/Article/details/gtjmnhszzd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yj202588.top/Article/details/gtknzienup.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sxryk.cn/Article/details/gtwpejhbrk.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gtioivhppw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.birdmap.top/Article/details/gtksnlodvu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinqigfzy.top/Article/details/gtrwbumwpx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yongpay.top/Article/details/gtsytlkvwm.html

[Q42] 连接条件附加过滤
来源：http://dali.9152youxi.cn/Article/details/gtfwmewqvw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.birdmap.top/Article/details/gtbqrvgzva.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hnqzz.top/Article/details/gtfhkjqkdr.html

[Q43] 标量子查询
来源：http://dali.ydzc1.top/Article/details/gtbgityhwn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.fengsongda.top/Article/details/gtaulryqkd.html

[Q44] IN 子查询
来源：http://dali.cucudq.cn/Article/details/gtnedpoozs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.c1oappe.top/Article/details/gtqmdakhan.html

[Q45] EXISTS 判断存在
来源：http://dali.vqdsnc.cn/Article/details/gtngcikett.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daxiang520.top/Article/details/gtdfjjmkip.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenlongwang.top/Article/details/gtvgeaofkr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hywenlv.cn/Article/details/gtqvauedbn.html

[Q47] 与平均值比较
来源：http://dali.ydzc1.top/Article/details/gtjsoscvfu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.guowangkeji.top/Article/details/gtwepvcoor.html

[Q48] CTE 公用表表达式
来源：http://dali.shzxlz.cn/Article/details/gtzbwnvwcn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.iojbl.cn/Article/details/gtnheyfheg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigfzy.top/Article/details/gtrrronskc.html

[Q49] 更新单行
来源：http://dali.cheryme.top/Article/details/gtrfoentlq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jianghu66.top/Article/details/gtrkhzfyge.html

[Q50] 批量更新
来源：http://dali.gotoacloud.top/Article/details/gtysmgarmh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinghuilouyu.cn/Article/details/gtettxszer.html

[Q51] 用子查询更新
来源：http://dali.smart0.xyz/Article/details/gtvxjbgtpu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.tianlin.xyz/Article/details/gtegzxatng.html

[Q52] 删除指定行
来源：http://dali.chenlongwang.top/Article/details/gthcnvtnli.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xuanzx.com/Article/details/gtbnaagcva.html

[Q53] 按条件删除
来源：http://dali.xziqi.cn/Article/details/gtmdnvcfqh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj20258.top/Article/details/gttdpqlipt.html

[Q54] 清空表
来源：http://dali.hnqzz.top/Article/details/gtargroeho.html

TRUNCATE TABLE logs;
来源：http://dali.smart0.xyz/Article/details/gtniuxsqhz.html

[Q55] 排名（并列占位）
来源：http://dali.0kj1m.cn/Article/details/gtxsuusdfb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.daria6918.cn/Article/details/gtpatyyhls.html

[Q56] 密集排名（并列不占位）
来源：http://dali.mhx1999.top/Article/details/gtucwuicov.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yonumen.top/Article/details/gtltmpxxmy.html

[Q57] 行号
来源：http://dali.tian-w.cn/Article/details/gtrgvsbmoi.html


<!-- 参考信息 -->