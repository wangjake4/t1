代发 wailian999

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sweek.top/Article/details/gtcdrgqgel.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.redwolf501.top/Article/details/gtngmyprle.html

Java: class Node { int v; Node next; }
来源：http://dali.nanxinkj.top/Article/details/gtfrduovlx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.fzhhl.top/Article/details/gtfdqykqrg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.aizwys.cn/Article/details/gtpxoisbmi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jyoumei.cn/Article/details/gttsggtqus.html

[N11] 二叉树中序遍历
来源：http://dali.chenlongwang.top/Article/details/gtxgstssub.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlrmzexap.html

PHP:  // 手写递归函数
来源：http://dali.9152youxi.cn/Article/details/gtxkczirbe.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangdashe.top/Article/details/gtrprjkeii.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ppjwa.cn/Article/details/gtkvsrtlrb.html

Java: // 手写递归
来源：http://dali.havefunace.top/Article/details/gtvreaninv.html

Go:   // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gtghauqvkp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gogol.net.cn/Article/details/gtxbuyypja.html

C#:   // 手写递归
来源：http://dali.jianghu66.top/Article/details/gtbuemtnuw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ybcxt.top/Article/details/gtlrxnksso.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jqgfzy.top/Article/details/gtwmiroawl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.snrcjt.cn/Article/details/gtgyctzuti.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shangyingyoupin.top/Article/details/gteukplnqk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gogol.net.cn/Article/details/gtratloxyf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gogol.net.cn/Article/details/gtelccdrwa.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenzaomai.com/Article/details/gtweompvis.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtglvzpsyd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.andypj.xyz/Article/details/gtxdrwnpab.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtymukwpeq.html

O. 并发与异步
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvapbqvl.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtptoroeam.html

[O01] 启动一个线程
来源：http://dali.meibo888.top/Article/details/gtpoxabsvy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.fzhhl.top/Article/details/gtcyvpckpr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xuetiantiany.cn/Article/details/gtbcojyjcx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.pycfn.com/Article/details/gtekakcsap.html

TS:   // 同 JS
来源：http://dali.jqgufenzy.top/Article/details/gtvcoarwij.html

Java: new Thread(() -> f()).start()
来源：http://dali.hysaishi.cn/Article/details/gtswepaeeh.html

Go:   go f()
来源：http://dali.sysykeji.top/Article/details/gtgdotttjy.html

Ruby: Thread.new { f }
来源：http://dali.tian-w.cn/Article/details/gtzhpdvaut.html

C#:   Task.Run(() => F());
来源：http://dali.redwolf501.top/Article/details/gtcrvheyun.html

[O02] 使用线程池
来源：http://dali.jinqigfzy.top/Article/details/gtjmiwafuv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.bjfxy.top/Article/details/gtfxtkzwfj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangshuangyany.cn/Article/details/gtxmamqcno.html

JS:   // worker_threads 线程池
来源：http://dali.dianchejie.cn/Article/details/gtqzkhmorm.html

TS:   // worker_threads 线程池
来源：http://dali.wangdashe.top/Article/details/gtxvcpovds.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yvedp.cn/Article/details/gtxfnoqvwh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.smart0.xyz/Article/details/gtcxjosaeo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hammf.cn/Article/details/gtczlxpcqd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tianlin.xyz/Article/details/gtotsxihuh.html

[O03] 加锁保护共享数据
来源：http://dali.xylfe.cn/Article/details/gtlnhiqsxi.html

Py:   with lock: shared += 1
来源：http://dali.nanxinkj.top/Article/details/gtttuevxew.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.dianchejie.cn/Article/details/gtwefyfsfy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.dashuyun.cn/Article/details/gtuwpmbede.html

TS:   // 同 JS
来源：http://dali.ydzc1.top/Article/details/gtvelxaezu.html

Java: synchronized (this) { shared++; }
来源：http://dali.nanxuanxn.top/Article/details/gtlpnkizvq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.316326.xyz/Article/details/gthvgdrezv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tanke756.top/Article/details/gtkqmcmont.html

C#:   lock (gate) { shared++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrreszymv.html

[O04] 定义异步函数并等待
来源：http://dali.fzhhl.top/Article/details/gtqxztoasj.html

Py:   async def f():⏎    await g()
来源：http://dali.haohaochexian.top/Article/details/gtulptcmbt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gtbjcerwth.html

JS:   async function f() { await g(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtqybwiigf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.fzhhl.top/Article/details/gtczezhxgr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gtezjhnmoe.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hongshengwenyu.top/Article/details/gtytnaswef.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xinyue.icu/Article/details/gtkkieytza.html

C#:   async Task F() { await G(); }
来源：http://dali.zdqjudy.top/Article/details/gturrkdlsy.html

[O05] 并发执行并等待全部完成
来源：http://dali.xziqi.cn/Article/details/gtoruaelfk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yongpay.top/Article/details/gtprpkdzxh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yueranfly.top/Article/details/gttjwakddf.html

JS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthlpewkfi.html

TS:   await Promise.all(tasks)
来源：http://dali.zycfv.cn/Article/details/gtngsigryc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hongshengwenyu.top/Article/details/gtcbwzwjkv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.wangshuangyany.cn/Article/details/gtyzuewozp.html

Ruby: threads.map(&:join)
来源：http://dali.guowangkeji.top/Article/details/gtqvcnrvol.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cheryme.top/Article/details/gtyqlgkyum.html

[O06] 使用进程池
来源：http://dali.zhengqikj.top/Article/details/gttcougfeg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shzxlz.cn/Article/details/gtaqqtdsfr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.wangdashe.top/Article/details/gtjlawvone.html

JS:   // child_process / cluster 模块
来源：http://dali.xuetiantiany.cn/Article/details/gtigblmpkj.html

TS:   // child_process / cluster 模块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhijlmmt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.aibaodan.cn/Article/details/gtqbnqamjs.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xinyue.icu/Article/details/gtvqerixtj.html

Ruby: // fork 块
来源：http://dali.tianlin.xyz/Article/details/gtfnasyfag.html

C#:   Parallel.For
来源：http://dali.sufxvd.cn/Article/details/gtdcxvyrlt.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtctjdjzfz.html

P. 常用工具函数
来源：http://dali.hnqzz.top/Article/details/gtxjpkmghx.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtslxovjxh.html

[P01] 生成 UUID
来源：http://dali.daxiang520.top/Article/details/gtdhhxcrdq.html

Py:   str(uuid.uuid4())
来源：http://dali.ybcxt.top/Article/details/gtqohptztt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zycfv.cn/Article/details/gtetzhgsrk.html

JS:   crypto.randomUUID()
来源：http://dali.ydzc1.top/Article/details/gtswcstkug.html

TS:   crypto.randomUUID()
来源：http://dali.yj20258888.top/Article/details/gttwkvtmri.html

Java: UUID.randomUUID().toString()
来源：http://dali.cashguo.top/Article/details/gtbmchkhol.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jqgfzy.top/Article/details/gtwfmctkbi.html

Ruby: SecureRandom.uuid
来源：http://dali.gzhubu.top/Article/details/gtpybyxwqz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jiagoushi.top/Article/details/gtmrjmgxjp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj20258.top/Article/details/gtzbldttaj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hammf.cn/Article/details/gtixpnzuhk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbrbvkvg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.snrcjt.cn/Article/details/gtfolzxzyi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ehwqpu.com/Article/details/gtplangqeh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.dianchejie.cn/Article/details/gtxuekfnml.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.bjfxy.top/Article/details/gtjjzjhjho.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yanxiufei.cn/Article/details/gtxoiuzmcu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.havefunace.top/Article/details/gtqzbasocr.html

[P03] 生成短随机字符串
来源：http://dali.nanxuanxn.top/Article/details/gttxckpzmw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yuanzhike.top/Article/details/gtdyobicix.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.feifeiyinyue.top/Article/details/gthvssnzim.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.meibo888.top/Article/details/gtpwpduaaw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.316326.xyz/Article/details/gtpvjsjeiy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.svipenyu.cn/Article/details/gtallzilpj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shangyingyoupin.top/Article/details/gtylbxtaec.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.havefunace.top/Article/details/gtkayvlevm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhoulong.xyz/Article/details/gtgjfaadip.html

[P04] 求长度
来源：http://dali.cheryme.top/Article/details/gtrgwjiefp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhengqikj.top/Article/details/gtqgrpksvz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtzkmotqft.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gtqpwbchbj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fengsongda.top/Article/details/gtppdvrzyd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ybcxt.top/Article/details/gtxcyevpsp.html

Go:   len(arr);  len(m)
来源：http://dali.yonumen.top/Article/details/gtviwtuwry.html

Ruby: x.length;  x.size
来源：http://dali.xinyue.icu/Article/details/gtddtjzucj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ehwqpu.com/Article/details/gtatklhtfy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sufxvd.cn/Article/details/gttjjhjulr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.svipenyu.cn/Article/details/gtwkhmqpiq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.mhx1999.top/Article/details/gtmktoihrj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tanke756.top/Article/details/gtwgpngfrr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.birdmap.top/Article/details/gtwhejhgcc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.chenjidiqi.icu/Article/details/gtfhcrutsj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hfpthk.cn/Article/details/gtkklwobyv.html

Ruby: a == b
来源：http://dali.shanyushiyangtech.top/Article/details/gteslymoek.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenlongwang.top/Article/details/gtiwgaxxms.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jqgfzy.top/Article/details/gtrygnayms.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.guowangkeji.top/Article/details/gtjokteqhp.html

PHP:  if (empty($x)) {}
来源：http://dali.yuanzhike.top/Article/details/gtpyhrhnhu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.quarkkingdee.top/Article/details/gthksetycw.html

TS:   if (x == null) {}
来源：http://dali.zhoulong.xyz/Article/details/gtkpzuemqh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xziqi.cn/Article/details/gtasfktbtn.html

Go:   if x == nil {}
来源：http://dali.gotoacloud.top/Article/details/gtqoqjiarn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yvedp.cn/Article/details/gtfxshocgo.html

C#:   if (x is null) {}
来源：http://dali.guannengcc.top/Article/details/gtthawnucy.html

[P07] 防抖与节流
来源：http://dali.snrcjt.cn/Article/details/gtkxfnbysy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hnxiangtu.top/Article/details/gtwbsapydh.html

PHP:  // 手写时间戳比较
来源：http://dali.ydzc1.top/Article/details/gtlskdazkt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdaqkedyp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.0kj1m.cn/Article/details/gtuuufiwwi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhengqikj.top/Article/details/gttuigrwss.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hammf.cn/Article/details/gthkbvzjwo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ppjwa.cn/Article/details/gtptpzxegh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.quarkkingdee.top/Article/details/gtrpsegvxe.html

[P08] 处理浮点精度问题
来源：http://dali.zhixingplan.top/Article/details/gtmjszpeer.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrakpuwsl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gogol.net.cn/Article/details/gtvxeizqxv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jyoumei.cn/Article/details/gttdsqmzzj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.svipenyu.cn/Article/details/gtfwdkojjo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zdqjudy.top/Article/details/gtyezxdprw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sxryk.cn/Article/details/gtdjxrowhq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenzaomai.com/Article/details/gtycfvrffm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.kuanghao11.cn/Article/details/gtlalmbxiz.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtjunraald.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.c1oappe.top/Article/details/gtsfzppvzh.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtxeqaqsfn.html

[Q01] 创建表
来源：http://dali.birdmap.top/Article/details/gtcdrdehqt.html

CREATE TABLE users (
来源：http://dali.jyoumei.cn/Article/details/gtsrliotvp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.svipenyu.cn/Article/details/gtsxqzepjt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.dashuyun.cn/Article/details/gttziauecs.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yvedp.cn/Article/details/gtkqtjztbk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jianghu66.top/Article/details/gtrjnuascu.html

);
来源：http://dali.smart0.xyz/Article/details/gtmraomlht.html

[Q02] 创建带外键的表
来源：http://dali.daria6918.cn/Article/details/gtexumyekp.html

CREATE TABLE orders (
来源：http://dali.ydzc1.top/Article/details/gtefnzyvye.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenjidiqi.icu/Article/details/gtjslygxhb.html

user_id INT NOT NULL,
来源：http://dali.c1oappe.top/Article/details/gtopnaflei.html

amount DECIMAL(10, 2),
来源：http://dali.yj20258.top/Article/details/gtmfjdnaqg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nwbrower.top/Article/details/gtzxfegnmv.html

);
来源：http://dali.yanxiufei.cn/Article/details/gtypxwdvkv.html

[Q03] 增加列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtomhevdey.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nanxinkj.top/Article/details/gtynkoofnm.html

[Q04] 修改列类型
来源：http://dali.cashguo.top/Article/details/gtbxhpvjev.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmxecpdt.html

[Q05] 重命名列
来源：http://dali.jqgfzy.top/Article/details/gtgslqbffn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shzxlz.cn/Article/details/gtkczcegbp.html

[Q06] 删除列
来源：http://dali.vqdsnc.cn/Article/details/gtrqczxbxh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tanke756.top/Article/details/gtlmtbbivc.html

[Q07] 删除表
来源：http://dali.sysykeji.top/Article/details/gtblvfeegi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jiagoushi.top/Article/details/gtvuhdnalk.html

[Q08] 创建普通索引
来源：http://dali.zhengqikj.top/Article/details/gtrynykmjz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.c1oappe.top/Article/details/gtrohopylm.html

[Q09] 创建唯一索引
来源：http://dali.vqdsnc.cn/Article/details/gtvxeuwovp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gtiwoclyii.html

[Q10] 插入单行
来源：http://dali.sysykeji.top/Article/details/gtbonyshqs.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.guowangkeji.top/Article/details/gtkzstgvnq.html

[Q11] 一次插入多行
来源：http://dali.yj202588.top/Article/details/gtnkvajhnu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sweek.top/Article/details/gtaqdmcccx.html

[Q12] 插入后取自增 ID
来源：http://dali.chenlongwang.top/Article/details/gtqfxcnnmv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhoulong.xyz/Article/details/gtdfqryvxa.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.andypj.xyz/Article/details/gtxyxsanlb.html

[Q13] 忽略重复插入
来源：http://dali.cdnleiting.top/Article/details/gtsoajbkws.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.meibo888.top/Article/details/gtsijkanla.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhixingplan.top/Article/details/gtslsruzbx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ivvv.top/Article/details/gtpleayvgi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hywenlv.cn/Article/details/gtdawborfw.html

[Q15] 查询全部
来源：http://dali.hammf.cn/Article/details/gtxqkltvyw.html

SELECT * FROM users;
来源：http://dali.nwbrower.top/Article/details/gtfesgohgo.html

[Q16] 查询指定列
来源：http://dali.kuanghao11.cn/Article/details/gtfnfzxgvg.html

SELECT id, name FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtfuqqscvq.html

[Q17] 条件查询
来源：http://dali.cashguo.top/Article/details/gtzqjwopxn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinqigufen.top/Article/details/gtvnmhpaez.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gtcylrjvvg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sysykeji.top/Article/details/gtgwccbjpw.html

[Q19] 范围查询
来源：http://dali.chenzaomai.com/Article/details/gtflchbjli.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmcchsiyt.html

[Q20] IN 列表
来源：http://dali.dianchejie.cn/Article/details/gttfjvnynf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jyoumei.cn/Article/details/gtfhtlztxg.html

[Q21] 空值判断
来源：http://dali.ehwqpu.com/Article/details/gteebjmiwx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yangfankeji.com/Article/details/gtjwwzvjgs.html

[Q22] 排序
来源：http://dali.jinqigufen.top/Article/details/gtbqsfiulf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenlongwang.top/Article/details/gtamhvmxff.html

[Q23] 分页
来源：http://dali.guowangkeji.top/Article/details/gtyvnoxuvk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenzaomai.com/Article/details/gtlxbtmbqs.html

[Q24] 去重
来源：http://dali.shzxlz.cn/Article/details/gtlaagcjzk.html

SELECT DISTINCT city FROM users;
来源：http://dali.meibo888.top/Article/details/gtaolkgywi.html

[Q25] 只取前 N 条
来源：http://dali.jyoumei.cn/Article/details/gtgmyvljuw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xinyue.icu/Article/details/gtooiucgpm.html

[Q26] 计数
来源：http://dali.havefunace.top/Article/details/gtztupumlk.html

SELECT COUNT(*) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtucjvnfql.html

[Q27] 条件计数
来源：http://dali.pengpengdd.cyou/Article/details/gtzcujlvgl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtzjzhhbtl.html

[Q28] 求和与平均
来源：http://dali.jinqigfzy.top/Article/details/gtgbjdzbwq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gttijdourm.html

[Q29] 最大最小值
来源：http://dali.shzxlz.cn/Article/details/gtkfvstvnb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtnyadvckp.html

[Q30] 分组统计
来源：http://dali.jinqigfzy.top/Article/details/gtbbgnoehc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gtofbaqtbm.html

[Q31] 分组后过滤
来源：http://dali.tian-w.cn/Article/details/gtvsydqngx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nanxuanxn.top/Article/details/gtgahxuldg.html

[Q32] 分组拼接字符串
来源：http://dali.shuidangran.top/Article/details/gtfzgheleu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gtkmegdndy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nanxuanxn.top/Article/details/gtxoxrelgw.html

[Q33] 多列分组
来源：http://dali.ehwqpu.com/Article/details/gtjsiqyysh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shangyingyoupin.top/Article/details/gtnynxddfu.html

[Q34] 每组取第一条
来源：http://dali.sysykeji.top/Article/details/gtiqmzjoik.html

SELECT * FROM (
来源：http://dali.gogol.net.cn/Article/details/gtlsuguldv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tianlin.xyz/Article/details/gtgluidzdu.html

) t WHERE rn = 1;
来源：http://dali.dashuyun.cn/Article/details/gtnammkueb.html

[Q35] 内连接
来源：http://dali.jqgufenzy.top/Article/details/gtpbwbjmny.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.c1oappe.top/Article/details/gttnelhoiu.html

[Q36] 左连接
来源：http://dali.yonumen.top/Article/details/gtvbczwezp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hysaishi.cn/Article/details/gtjkutlknh.html

[Q37] 右连接
来源：http://dali.bjfxy.top/Article/details/gtpddgaess.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shzxlz.cn/Article/details/gteeyjmigl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jqgufenzy.top/Article/details/gtbviznjjl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.0kj1m.cn/Article/details/gtkbcivfky.html

[Q39] 自连接（查上下级）
来源：http://dali.cheryme.top/Article/details/gtzbbuapms.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.aibaodan.cn/Article/details/gtpesbwyby.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhixingplan.top/Article/details/gtgifxffjl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.havefunace.top/Article/details/gtbarnwynz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ybcxt.top/Article/details/gtpkzckrfm.html

[Q41] 多表连接
来源：http://dali.dianchejie.cn/Article/details/gtegynvhhg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shzxlz.cn/Article/details/gtpoiybihg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sufxvd.cn/Article/details/gtvgonjzfw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xinyue.icu/Article/details/gtmfeimnvl.html

[Q42] 连接条件附加过滤
来源：http://dali.nanxuanxn.top/Article/details/gtabotfeqo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tanke756.top/Article/details/gtiqjmddhs.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yuanzhike.top/Article/details/gtdodozssm.html

[Q43] 标量子查询
来源：http://dali.yj20258888.top/Article/details/gtqpwteqvc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgfzy.top/Article/details/gtykubhzjs.html

[Q44] IN 子查询
来源：http://dali.cashguo.top/Article/details/gtemgufbpw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cdnleiting.top/Article/details/gtygavitgf.html

[Q45] EXISTS 判断存在
来源：http://dali.nanxinkj.top/Article/details/gttqjosibm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.bjfxy.top/Article/details/gtgefgfzfd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenlongwang.top/Article/details/gtzqftazzv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shuidangran.top/Article/details/gtotduirjc.html

[Q47] 与平均值比较
来源：http://dali.yj202588.top/Article/details/gtsxieazsq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yvedp.cn/Article/details/gtemkvinvm.html

[Q48] CTE 公用表表达式
来源：http://dali.tanke756.top/Article/details/gtuiehonco.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jyoumei.cn/Article/details/gtfiwgjzng.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cqqwz.cn/Article/details/gteyzrmgul.html

[Q49] 更新单行
来源：http://dali.feifeiyinyue.top/Article/details/gtnbzcggjc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.aizwys.cn/Article/details/gtfvanadvg.html

[Q50] 批量更新
来源：http://dali.gaohongyu789.top/Article/details/gtwbhigqqo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.guowangkeji.top/Article/details/gthbuyaoku.html

[Q51] 用子查询更新
来源：http://dali.iojbl.cn/Article/details/gteivhysqc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtqesutejk.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gtcbyntjxx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xylfe.cn/Article/details/gtsnweqdkj.html

[Q53] 按条件删除
来源：http://dali.shzxlz.cn/Article/details/gtplfxoavb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhengqikj.top/Article/details/gtzgngmdnc.html

[Q54] 清空表
来源：http://dali.xylfe.cn/Article/details/gtndqumxgl.html

TRUNCATE TABLE logs;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcbrgvavd.html

[Q55] 排名（并列占位）
来源：http://dali.ivvv.top/Article/details/gtzdgpyvrx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.guannengcc.top/Article/details/gtotfvsplr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tianlin.xyz/Article/details/gtqkjbzizo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyulebmfd.html

[Q57] 行号
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwntidbw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yuxming.cn/Article/details/gtzinirxcq.html

[Q58] 累计求和
来源：http://dali.dianchejie.cn/Article/details/gtqripulxa.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtualgcgba.html

[Q59] 分组内累计
来源：http://dali.jqgfzy.top/Article/details/gtvjvgzlko.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtdpaoekya.html

[Q60] 取上一行 / 下一行
来源：http://dali.nanxuanxn.top/Article/details/gtfsfddqho.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.haohaochexian.top/Article/details/gthzcurdvo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtcwficeqw.html


<!-- 参考信息 -->