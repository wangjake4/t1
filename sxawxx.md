代发 wailian999

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.c1oappe.top/Article/details/gtuohvdqsz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnviffgff.html

Java: class Node { int v; Node next; }
来源：http://dali.chenjidiqi.icu/Article/details/gthbjmqflp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ybcxt.top/Article/details/gtoidshezo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zdqjudy.top/Article/details/gtkpegfyph.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinghuilouyu.cn/Article/details/gthqdipfug.html

[N11] 二叉树中序遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxwucjuv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hnqzz.top/Article/details/gtydcyacye.html

PHP:  // 手写递归函数
来源：http://dali.cheryme.top/Article/details/gtqabyhhvr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.bjfxy.top/Article/details/gtmcaqxwcm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nwbrower.top/Article/details/gtzwslaazh.html

Java: // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gtxfbenrns.html

Go:   // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gtlyovfpux.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hongshengwenyu.top/Article/details/gtkrrykpkq.html

C#:   // 手写递归
来源：http://dali.yonumen.top/Article/details/gtqmehpeqj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.snrcjt.cn/Article/details/gtqncyqzec.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shzxlz.cn/Article/details/gtalrdsudp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.bjfxy.top/Article/details/gtbodaoasb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dianchejie.cn/Article/details/gtemhwazgm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258888.top/Article/details/gtpyoyzots.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuanzhike.top/Article/details/gtbccvnmoh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hfpthk.cn/Article/details/gtpjjkaxsh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.mhx1999.top/Article/details/gtwdhmcegu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.meibo888.top/Article/details/gtnacptlmb.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtafuefjee.html

O. 并发与异步
来源：http://dali.chenzaomai.com/Article/details/gtjbznamid.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtwsyrgdlq.html

[O01] 启动一个线程
来源：http://dali.zhixingplan.top/Article/details/gttbvjpvkr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinqigfzy.top/Article/details/gtssonqbqr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hongshengwenyu.top/Article/details/gtlrbblgyq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.birdmap.top/Article/details/gtluemxtyw.html

TS:   // 同 JS
来源：http://dali.cqqwz.cn/Article/details/gtjjozusyp.html

Java: new Thread(() -> f()).start()
来源：http://dali.ydzc1.top/Article/details/gtfsuommen.html

Go:   go f()
来源：http://dali.wangdashe.top/Article/details/gtethvhrka.html

Ruby: Thread.new { f }
来源：http://dali.gotoacloud.top/Article/details/gttsuqcepx.html

C#:   Task.Run(() => F());
来源：http://dali.chenjidiqi.icu/Article/details/gtydtubham.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gtqplnfmgn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.snrcjt.cn/Article/details/gtrecytzjs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yanxiufei.cn/Article/details/gthkzvejyq.html

JS:   // worker_threads 线程池
来源：http://dali.kuanghao11.cn/Article/details/gtradryaji.html

TS:   // worker_threads 线程池
来源：http://dali.smart0.xyz/Article/details/gthiixuqnz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.bjfxy.top/Article/details/gtnwhmeqlj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj20258.top/Article/details/gtrngthydg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenlongwang.top/Article/details/gtxyizbwwc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhixingplan.top/Article/details/gtrpwkviuw.html

[O03] 加锁保护共享数据
来源：http://dali.andypj.xyz/Article/details/gteuptzkps.html

Py:   with lock: shared += 1
来源：http://dali.nanxuanxn.top/Article/details/gtxielvruh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmncmwjx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinghuilouyu.cn/Article/details/gthwqodkai.html

TS:   // 同 JS
来源：http://dali.gogol.net.cn/Article/details/gtuidoebkq.html

Java: synchronized (this) { shared++; }
来源：http://dali.yongpay.top/Article/details/gtcvnelivq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.dashuyun.cn/Article/details/gteewckeyf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.c1oappe.top/Article/details/gtgsxwvrna.html

C#:   lock (gate) { shared++; }
来源：http://dali.gaohongyu789.top/Article/details/gtlcjndonb.html

[O04] 定义异步函数并等待
来源：http://dali.shzxlz.cn/Article/details/gtmzrzgikz.html

Py:   async def f():⏎    await g()
来源：http://dali.sufxvd.cn/Article/details/gtsgedapfg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.wangshuangyany.cn/Article/details/gtycbksiul.html

JS:   async function f() { await g(); }
来源：http://dali.xylfe.cn/Article/details/gtjlleakjl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.snrcjt.cn/Article/details/gtuakbdtzo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhiwuduotai.top/Article/details/gtinucpldg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.guowangkeji.top/Article/details/gtwzsmdziv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.wangshuangyany.cn/Article/details/gtkpdvzxis.html

C#:   async Task F() { await G(); }
来源：http://dali.yvedp.cn/Article/details/gtuvojydsp.html

[O05] 并发执行并等待全部完成
来源：http://dali.daxiang520.top/Article/details/gtsaztedwk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.svipenyu.cn/Article/details/gtooygftue.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sysykeji.top/Article/details/gtexdlkivk.html

JS:   await Promise.all(tasks)
来源：http://dali.jyoumei.cn/Article/details/gtbgpszfzj.html

TS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrwxzbvjt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinqigufen.top/Article/details/gtcdlbkxwi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sufxvd.cn/Article/details/gtbwczcnqm.html

Ruby: threads.map(&:join)
来源：http://dali.bjfxy.top/Article/details/gtdtuuhxeh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shanyushiyangtech.top/Article/details/gttwmaidiu.html

[O06] 使用进程池
来源：http://dali.cdnleiting.top/Article/details/gtaidxhuad.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xylfe.cn/Article/details/gtwcosvoyx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gogol.net.cn/Article/details/gttguiksrz.html

JS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gtujxpuuwx.html

TS:   // child_process / cluster 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiomudekk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hongshengwenyu.top/Article/details/gtlpbdddtv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jqgfzy.top/Article/details/gtmxmkrpaz.html

Ruby: // fork 块
来源：http://dali.nanxuanxn.top/Article/details/gtqieazajk.html

C#:   Parallel.For
来源：http://dali.jianghu66.top/Article/details/gtknazzlll.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtiaymaezi.html

P. 常用工具函数
来源：http://dali.havefunace.top/Article/details/gtimmhoifk.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gthpmapnem.html

[P01] 生成 UUID
来源：http://dali.tanke756.top/Article/details/gtnnqghnqt.html

Py:   str(uuid.uuid4())
来源：http://dali.snrcjt.cn/Article/details/gttrfjmomg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yangfankeji.com/Article/details/gtohizvjic.html

JS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gtmnptlmnk.html

TS:   crypto.randomUUID()
来源：http://dali.shuidangran.top/Article/details/gtgwnyehda.html

Java: UUID.randomUUID().toString()
来源：http://dali.mhx1999.top/Article/details/gtttayimdq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.wangdashe.top/Article/details/gtijtqbiks.html

Ruby: SecureRandom.uuid
来源：http://dali.nwbrower.top/Article/details/gtiqiyesxb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinqigfzy.top/Article/details/gtsyklckkl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xziqi.cn/Article/details/gtdqiuxsir.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xylfe.cn/Article/details/gtsmovtfgm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtjbvmbomv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.guannengcc.top/Article/details/gtabgyphiy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.andypj.xyz/Article/details/gtvjdppokc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gtryunqlce.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.haohaochexian.top/Article/details/gteqdfjsbi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.fengsongda.top/Article/details/gttrnxenyr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhoulong.xyz/Article/details/gtwmswqdjy.html

[P03] 生成短随机字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gttxzsejpy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cucudq.cn/Article/details/gtptntuhpv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.andypj.xyz/Article/details/gtgcnceqgg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guannengcc.top/Article/details/gtcruvxzct.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhiwuduotai.top/Article/details/gthpuskfog.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shuidangran.top/Article/details/gtvmvmgnkk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zycfv.cn/Article/details/gtshnyrygs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhiwuduotai.top/Article/details/gtovxqaput.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.kuanghao11.cn/Article/details/gtmwngcger.html

[P04] 求长度
来源：http://dali.feifeiyinyue.top/Article/details/gtgzlxjqkw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jiagoushi.top/Article/details/gtqwukbbjy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtyfgqwcin.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgfzy.top/Article/details/gtsnfkyavo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuetiantiany.cn/Article/details/gtgqvbtiaf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.wangdashe.top/Article/details/gtcwekhjki.html

Go:   len(arr);  len(m)
来源：http://dali.jlsjyb.cn/Article/details/gtqvpsbknp.html

Ruby: x.length;  x.size
来源：http://dali.guowangkeji.top/Article/details/gtdmzqpulj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jqgfzy.top/Article/details/gtqcrmlnmm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sufxvd.cn/Article/details/gtlfxnysmu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jqgufenzy.top/Article/details/gtwwrtiast.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.vqdsnc.cn/Article/details/gtthteogkq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hnqzz.top/Article/details/gtqzuzsyxk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hfpthk.cn/Article/details/gtcphrwhkc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.pengpengdd.cyou/Article/details/gtzvpduchc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.wangdashe.top/Article/details/gtglznhqiq.html

Ruby: a == b
来源：http://dali.havefunace.top/Article/details/gtgyoojuue.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.aibaodan.cn/Article/details/gtxddueefv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhengqikj.top/Article/details/gthohkwthu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.aibaodan.cn/Article/details/gtzcfryhzx.html

PHP:  if (empty($x)) {}
来源：http://dali.zycfv.cn/Article/details/gtlcnagdrn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zdqjudy.top/Article/details/gtvtbpfmpb.html

TS:   if (x == null) {}
来源：http://dali.cucudq.cn/Article/details/gtidzesfvk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ydzc1.top/Article/details/gtlrpnueit.html

Go:   if x == nil {}
来源：http://dali.snrcjt.cn/Article/details/gtdpcerwdz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.c1oappe.top/Article/details/gtketjiaau.html

C#:   if (x is null) {}
来源：http://dali.c1oappe.top/Article/details/gttmzftslu.html

[P07] 防抖与节流
来源：http://dali.guannengcc.top/Article/details/gtlrgjuxto.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhengqikj.top/Article/details/gtdophqmtl.html

PHP:  // 手写时间戳比较
来源：http://dali.yongpay.top/Article/details/gthulypien.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuanzx.com/Article/details/gtkckfsoyp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gtvrvwqegg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gzhubu.top/Article/details/gttmlhsupl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hnqzz.top/Article/details/gteyqslwva.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xuanzx.com/Article/details/gtdbugmbqd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.tian-w.cn/Article/details/gtnefszzge.html

[P08] 处理浮点精度问题
来源：http://dali.sxryk.cn/Article/details/gtihrqgaig.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj20258888.top/Article/details/gtmkhgndlt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jqgfzy.top/Article/details/gtuhwcdtcf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tianlin.xyz/Article/details/gtxmabtvht.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.svipenyu.cn/Article/details/gtfgvhcluh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.daria6918.cn/Article/details/gtaofaevct.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jyoumei.cn/Article/details/gtavmlnnul.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jianghu66.top/Article/details/gtzqtqqqai.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj20258888.top/Article/details/gtbyblnbkv.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtqwzsqtri.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.daxiang520.top/Article/details/gtmhppmdgf.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gthsyskbub.html

[Q01] 创建表
来源：http://dali.zhixingplan.top/Article/details/gtzeuwjsyq.html

CREATE TABLE users (
来源：http://dali.zhengqikj.top/Article/details/gtlvjwacdh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guowangkeji.top/Article/details/gtwyhkxzrb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.nwbrower.top/Article/details/gthavibdvr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.aizwys.cn/Article/details/gtoxcimbtm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shzxlz.cn/Article/details/gtjsuktbxn.html

);
来源：http://dali.guowangkeji.top/Article/details/gtntoiahjr.html

[Q02] 创建带外键的表
来源：http://dali.yonumen.top/Article/details/gtmdppfqeu.html

CREATE TABLE orders (
来源：http://dali.feifeiyinyue.top/Article/details/gtbjtklynf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xylfe.cn/Article/details/gtpmdyyeua.html

user_id INT NOT NULL,
来源：http://dali.jqgufenzy.top/Article/details/gtptwhsyyx.html

amount DECIMAL(10, 2),
来源：http://dali.snrcjt.cn/Article/details/gtswsduztf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenjidiqi.icu/Article/details/gtdxucpqpl.html

);
来源：http://dali.zhoulong.xyz/Article/details/gtxjgajhnw.html

[Q03] 增加列
来源：http://dali.xylfe.cn/Article/details/gtiijschrw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hfpthk.cn/Article/details/gtstqmurwq.html

[Q04] 修改列类型
来源：http://dali.jqgfzy.top/Article/details/gtxgdddqsu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.aizwys.cn/Article/details/gtpccefdvn.html

[Q05] 重命名列
来源：http://dali.fengsongda.top/Article/details/gtjsuqxaob.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhengqikj.top/Article/details/gthdgnnwmw.html

[Q06] 删除列
来源：http://dali.haohaochexian.top/Article/details/gtyicmdivv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.meibo888.top/Article/details/gtpnoomfba.html

[Q07] 删除表
来源：http://dali.zhengqikj.top/Article/details/gtpmoswrqu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.fengsongda.top/Article/details/gttcmfddho.html

[Q08] 创建普通索引
来源：http://dali.chenlongwang.top/Article/details/gtnfaejgwq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.daxiang520.top/Article/details/gtrtzzhnkz.html

[Q09] 创建唯一索引
来源：http://dali.yuxming.cn/Article/details/gtadhkyqih.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jqgufenzy.top/Article/details/gtqovqltry.html

[Q10] 插入单行
来源：http://dali.hammf.cn/Article/details/gtiafksdra.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gogol.net.cn/Article/details/gtvfsvxcky.html

[Q11] 一次插入多行
来源：http://dali.vqdsnc.cn/Article/details/gtiqhzegji.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nwbrower.top/Article/details/gtvjjdiuws.html

[Q12] 插入后取自增 ID
来源：http://dali.havefunace.top/Article/details/gtvxlpapve.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yueranfly.top/Article/details/gtobqubwyw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.pengpengdd.cyou/Article/details/gtdrvbgbtt.html

[Q13] 忽略重复插入
来源：http://dali.xinyue.icu/Article/details/gtpusfurtv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.c1oappe.top/Article/details/gtgzvuyynq.html

[Q14] 存在则更新（upsert）
来源：http://dali.pengpengdd.cyou/Article/details/gtxrzjepvr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xziqi.cn/Article/details/gtiyoschbu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ppjwa.cn/Article/details/gtzwcekutw.html

[Q15] 查询全部
来源：http://dali.xinyue.icu/Article/details/gtoymkgwtl.html

SELECT * FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtnfaruotn.html

[Q16] 查询指定列
来源：http://dali.hfpthk.cn/Article/details/gtprpfkyna.html

SELECT id, name FROM users;
来源：http://dali.316326.xyz/Article/details/gtubrtuciw.html

[Q17] 条件查询
来源：http://dali.cashguo.top/Article/details/gtbbmsvugv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hysaishi.cn/Article/details/gtiqbcremw.html

[Q18] 模糊匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtaisinuyp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinqigufen.top/Article/details/gtccrfaeey.html

[Q19] 范围查询
来源：http://dali.zhoulong.xyz/Article/details/gttecqehbq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yvedp.cn/Article/details/gtqjxbtymn.html

[Q20] IN 列表
来源：http://dali.vqdsnc.cn/Article/details/gtkkfyfenn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtafcqsvzn.html

[Q21] 空值判断
来源：http://dali.smart0.xyz/Article/details/gtiicnmvpm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.fengsongda.top/Article/details/gtsugatlsn.html

[Q22] 排序
来源：http://dali.vqdsnc.cn/Article/details/gtxvwhpawz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.iojbl.cn/Article/details/gtrfykoawb.html

[Q23] 分页
来源：http://dali.jqgufenzy.top/Article/details/gttfxpxwvv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.birdmap.top/Article/details/gtyjjsyqww.html

[Q24] 去重
来源：http://dali.gogol.net.cn/Article/details/gtafdjkqhu.html

SELECT DISTINCT city FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtfdzxfqov.html

[Q25] 只取前 N 条
来源：http://dali.gotoacloud.top/Article/details/gtnygdcjky.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yangfankeji.com/Article/details/gtdhfhmynk.html

[Q26] 计数
来源：http://dali.ivvv.top/Article/details/gtfngrnbgy.html

SELECT COUNT(*) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbkkitjx.html

[Q27] 条件计数
来源：http://dali.feifeiyinyue.top/Article/details/gtfldceilc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ydzc1.top/Article/details/gtyaitwlkt.html

[Q28] 求和与平均
来源：http://dali.xuetiantiany.cn/Article/details/gtguwtevbd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtksybnhdq.html

[Q29] 最大最小值
来源：http://dali.sweek.top/Article/details/gtshcnlryd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtuqeoazis.html

[Q30] 分组统计
来源：http://dali.yvedp.cn/Article/details/gtqrpszpii.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gtityihlbh.html

[Q31] 分组后过滤
来源：http://dali.pycfn.com/Article/details/gtonpggjnq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhaaionn.html

[Q32] 分组拼接字符串
来源：http://dali.xziqi.cn/Article/details/gtqolitnaz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdgqzpwwd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj202588.top/Article/details/gtsbadvnqj.html

[Q33] 多列分组
来源：http://dali.snrcjt.cn/Article/details/gtojqhqvxh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinqigufen.top/Article/details/gtgsbrrqvi.html

[Q34] 每组取第一条
来源：http://dali.ppjwa.cn/Article/details/gthhxrrjjp.html

SELECT * FROM (
来源：http://dali.chenlongwang.top/Article/details/gthrccvboz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.fzhhl.top/Article/details/gtyqmrldqz.html

) t WHERE rn = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtueiktopx.html

[Q35] 内连接
来源：http://dali.zdqjudy.top/Article/details/gtfzlncvrf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.haohaochexian.top/Article/details/gtsbngoaut.html

[Q36] 左连接
来源：http://dali.feifeiyinyue.top/Article/details/gtyhqtaouy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj202588.top/Article/details/gtgoiuenbz.html

[Q37] 右连接
来源：http://dali.vqdsnc.cn/Article/details/gtzvmtkwhh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhoulong.xyz/Article/details/gtkreiankd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.dashuyun.cn/Article/details/gtnynoheqx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhixingplan.top/Article/details/gtmagxtkkl.html

[Q39] 自连接（查上下级）
来源：http://dali.yueranfly.top/Article/details/gtdmlvaukt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yueranfly.top/Article/details/gtekuhtevx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.vqdsnc.cn/Article/details/gtoeykmfcb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.quarkkingdee.top/Article/details/gtptovwfab.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xziqi.cn/Article/details/gtfiszjcyt.html

[Q41] 多表连接
来源：http://dali.tianlin.xyz/Article/details/gtwjfugjsg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gaohongyu789.top/Article/details/gtvmdfrrwi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gaohongyu789.top/Article/details/gtacwzlriu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.iojbl.cn/Article/details/gtvhjvkank.html

[Q42] 连接条件附加过滤
来源：http://dali.zhixingplan.top/Article/details/gtnipgbnmu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinqigfzy.top/Article/details/gtgmfaubqy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj20258888.top/Article/details/gtvqonmaha.html

[Q43] 标量子查询
来源：http://dali.0kj1m.cn/Article/details/gtkdhuerxr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dianchejie.cn/Article/details/gthpfbrudb.html

[Q44] IN 子查询
来源：http://dali.xuanzx.com/Article/details/gttaxvkgsv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.vqdsnc.cn/Article/details/gtuklmrosz.html

[Q45] EXISTS 判断存在
来源：http://dali.svipenyu.cn/Article/details/gtpkyqltwp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.c1oappe.top/Article/details/gtmshscfln.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.haohaochexian.top/Article/details/gtxwqikypg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hysaishi.cn/Article/details/gtlfclktno.html

[Q47] 与平均值比较
来源：http://dali.mhx1999.top/Article/details/gtfmmwwefq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gaohongyu789.top/Article/details/gtgfysmqgu.html

[Q48] CTE 公用表表达式
来源：http://dali.guowangkeji.top/Article/details/gtvzmkjzbm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yongpay.top/Article/details/gtpjiymdmu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hnxiangtu.top/Article/details/gteckmsill.html

[Q49] 更新单行
来源：http://dali.zhengqikj.top/Article/details/gtwexvhuyy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhengqikj.top/Article/details/gtmukdbhgm.html

[Q50] 批量更新
来源：http://dali.zhiwuduotai.top/Article/details/gtyevqesla.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.c1oappe.top/Article/details/gtecqdeavx.html

[Q51] 用子查询更新
来源：http://dali.chenlongwang.top/Article/details/gtpzgbypqh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.dashuyun.cn/Article/details/gtztpiwzzm.html

[Q52] 删除指定行
来源：http://dali.haohaochexian.top/Article/details/gteqqrdxjy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj20258.top/Article/details/gtqzrsunhy.html

[Q53] 按条件删除
来源：http://dali.9152youxi.cn/Article/details/gtogmpffcf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.quarkkingdee.top/Article/details/gthlfmhfwh.html

[Q54] 清空表
来源：http://dali.cdnleiting.top/Article/details/gtmlbjzjzy.html

TRUNCATE TABLE logs;
来源：http://dali.daria6918.cn/Article/details/gtwxijxnsc.html

[Q55] 排名（并列占位）
来源：http://dali.yanxiufei.cn/Article/details/gtugpomecz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xylfe.cn/Article/details/gtflqowdwi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.vqdsnc.cn/Article/details/gtaoruxoww.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gtceqrbele.html

[Q57] 行号
来源：http://dali.shangyingyoupin.top/Article/details/gttsmstlsm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtixiibwxp.html

[Q58] 累计求和
来源：http://dali.jianghu66.top/Article/details/gtnlwgupmr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtqazstkzs.html

[Q59] 分组内累计
来源：http://dali.hfpthk.cn/Article/details/gtuwlixcgy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtvydlecop.html

[Q60] 取上一行 / 下一行
来源：http://dali.daria6918.cn/Article/details/gtdujrxfnn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.birdmap.top/Article/details/gtqcgdqgzw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtebhidhed.html


<!-- 参考信息 -->