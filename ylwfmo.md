代发 wailian999

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.snrcjt.cn/Article/details/gtwmkuyyuu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ybcxt.top/Article/details/gtneikqeuj.html

Java: class Node { int v; Node next; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcegsjptp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.birdmap.top/Article/details/gthhkorovw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhengqikj.top/Article/details/gtswmlsbbq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.feifeiyinyue.top/Article/details/gtutpfwrqb.html

[N11] 二叉树中序遍历
来源：http://dali.xinyue.icu/Article/details/gtlwolcaqx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hongshengwenyu.top/Article/details/gtyeivjmuc.html

PHP:  // 手写递归函数
来源：http://dali.ivvv.top/Article/details/gthnkqqsgy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxuanxn.top/Article/details/gttsysumlp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sysykeji.top/Article/details/gtpynmpdfv.html

Java: // 手写递归
来源：http://dali.redwolf501.top/Article/details/gtudcgiick.html

Go:   // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gtvrrctccp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xylfe.cn/Article/details/gtspycaihx.html

C#:   // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gtdyokphnh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hysaishi.cn/Article/details/gtidfejecx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xuanzx.com/Article/details/gthsigbgjr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gzhubu.top/Article/details/gtkcvhszll.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.9152youxi.cn/Article/details/gtnrhljqjh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xinyue.icu/Article/details/gtqbcokepz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shuidangran.top/Article/details/gtfwsmwnle.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ybcxt.top/Article/details/gtxyvvnvnx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.dashuyun.cn/Article/details/gtpsdfrxld.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gtqatwppiy.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtbgxmfyjd.html

O. 并发与异步
来源：http://dali.hongshengwenyu.top/Article/details/gtkpmpgdhw.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtjvlzokqf.html

[O01] 启动一个线程
来源：http://dali.cashguo.top/Article/details/gtxlzaspyg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sweek.top/Article/details/gtusonbkxx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwqbntnm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.snrcjt.cn/Article/details/gtqayboift.html

TS:   // 同 JS
来源：http://dali.zhengqikj.top/Article/details/gtzsddqegm.html

Java: new Thread(() -> f()).start()
来源：http://dali.shangyingyoupin.top/Article/details/gtrfhaqsns.html

Go:   go f()
来源：http://dali.guowangkeji.top/Article/details/gtfapdwdzm.html

Ruby: Thread.new { f }
来源：http://dali.guannengcc.top/Article/details/gtobmtarkd.html

C#:   Task.Run(() => F());
来源：http://dali.guannengcc.top/Article/details/gtsqfkpmdw.html

[O02] 使用线程池
来源：http://dali.xziqi.cn/Article/details/gtabodrptv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ivvv.top/Article/details/gttiykjkqo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gzhubu.top/Article/details/gtavfkixqr.html

JS:   // worker_threads 线程池
来源：http://dali.jqgufenzy.top/Article/details/gtenpwthof.html

TS:   // worker_threads 线程池
来源：http://dali.9152youxi.cn/Article/details/gtdrwtbjti.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sxryk.cn/Article/details/gtvrrdxzew.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.aibaodan.cn/Article/details/gthmpcohhd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xuetiantiany.cn/Article/details/gtebkvedee.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jiagoushi.top/Article/details/gtqbdxflgd.html

[O03] 加锁保护共享数据
来源：http://dali.jyoumei.cn/Article/details/gtdcrzxujc.html

Py:   with lock: shared += 1
来源：http://dali.zhoulong.xyz/Article/details/gtcgwzgvut.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.kuanghao11.cn/Article/details/gtgibtxofg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jlsjyb.cn/Article/details/gtttusptxo.html

TS:   // 同 JS
来源：http://dali.dashuyun.cn/Article/details/gtlibggsim.html

Java: synchronized (this) { shared++; }
来源：http://dali.gaohongyu789.top/Article/details/gtelofcjay.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinqigufen.top/Article/details/gtiuagtbqa.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tianlin.xyz/Article/details/gttiqqgsxl.html

C#:   lock (gate) { shared++; }
来源：http://dali.daxiang520.top/Article/details/gtowyibgpb.html

[O04] 定义异步函数并等待
来源：http://dali.meibo888.top/Article/details/gtrnrpvwdf.html

Py:   async def f():⏎    await g()
来源：http://dali.chenlongwang.top/Article/details/gtdyvgrbhb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.wangshuangyany.cn/Article/details/gtvoplskql.html

JS:   async function f() { await g(); }
来源：http://dali.sysykeji.top/Article/details/gtjlllmrni.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sysykeji.top/Article/details/gtkooemnph.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenlongwang.top/Article/details/gtnmszyszk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj202588.top/Article/details/gtaexwndvv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.dianchejie.cn/Article/details/gttcteessv.html

C#:   async Task F() { await G(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtuurhzdyc.html

[O05] 并发执行并等待全部完成
来源：http://dali.svipenyu.cn/Article/details/gtmpouqiju.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tian-w.cn/Article/details/gtkzzajcbt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gogol.net.cn/Article/details/gtwjghfyyx.html

JS:   await Promise.all(tasks)
来源：http://dali.redwolf501.top/Article/details/gtsnebxskh.html

TS:   await Promise.all(tasks)
来源：http://dali.yueranfly.top/Article/details/gtrxdsksah.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cucudq.cn/Article/details/gttrtbrikd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hywenlv.cn/Article/details/gtcwdkrljv.html

Ruby: threads.map(&:join)
来源：http://dali.aibaodan.cn/Article/details/gtujyohdmh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fzhhl.top/Article/details/gtkhbhbyoi.html

[O06] 使用进程池
来源：http://dali.sweek.top/Article/details/gttwrzkejn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yvedp.cn/Article/details/gthbcucctm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jlsjyb.cn/Article/details/gthybaohjv.html

JS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gtvdmxcbty.html

TS:   // child_process / cluster 模块
来源：http://dali.ybcxt.top/Article/details/gtjrhkmikp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.havefunace.top/Article/details/gtzqipxxfb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jqgufenzy.top/Article/details/gtaenbaghp.html

Ruby: // fork 块
来源：http://dali.meibo888.top/Article/details/gtvcpsqeah.html

C#:   Parallel.For
来源：http://dali.yj20258888.top/Article/details/gtabihgrrh.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtamkxmnsm.html

P. 常用工具函数
来源：http://dali.zhongyouzk.top/Article/details/gtyldibbbp.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtnwpskput.html

[P01] 生成 UUID
来源：http://dali.redwolf501.top/Article/details/gtdhexqbji.html

Py:   str(uuid.uuid4())
来源：http://dali.jqgfzy.top/Article/details/gtqojzddnk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jiagoushi.top/Article/details/gtrcsyscqd.html

JS:   crypto.randomUUID()
来源：http://dali.nanxuanxn.top/Article/details/gtmrmtqcqm.html

TS:   crypto.randomUUID()
来源：http://dali.cdnleiting.top/Article/details/gtpcqkptug.html

Java: UUID.randomUUID().toString()
来源：http://dali.xinyue.icu/Article/details/gtmpxnogdh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hywenlv.cn/Article/details/gtkogqbshj.html

Ruby: SecureRandom.uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxqxkpgz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlshtzhws.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yanxiufei.cn/Article/details/gtbidtibnn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tianlin.xyz/Article/details/gticgwcmjw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhongyouzk.top/Article/details/gteqagtpgz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hysaishi.cn/Article/details/gtzhlabzna.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhiwuduotai.top/Article/details/gtpgjywpfp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gtswlpbpdu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gogol.net.cn/Article/details/gtjymdwyqb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhoulong.xyz/Article/details/gtxqctmisz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jiagoushi.top/Article/details/gtnhtkfegm.html

[P03] 生成短随机字符串
来源：http://dali.xinyue.icu/Article/details/gtqqgtevxf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.dianchejie.cn/Article/details/gtbxhtotin.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgtfupkwj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tanke756.top/Article/details/gttxebgegf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gotoacloud.top/Article/details/gtprwifpnr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.quarkkingdee.top/Article/details/gtkomkjdwx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.c1oappe.top/Article/details/gtrccwzcew.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.mhx1999.top/Article/details/gtckirzfdc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.feifeiyinyue.top/Article/details/gtsmxszpzz.html

[P04] 求长度
来源：http://dali.hongshengwenyu.top/Article/details/gtrvsurdje.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sufxvd.cn/Article/details/gtxlcuqoxa.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtjalqglzr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tianlin.xyz/Article/details/gtcengykzi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gtjnbrjgzk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gtldnymgat.html

Go:   len(arr);  len(m)
来源：http://dali.yongpay.top/Article/details/gtnpihdxsg.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gtaxseduno.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.nwbrower.top/Article/details/gtkgcvzfyv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.wangdashe.top/Article/details/gtsvcdmwvh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.chenjidiqi.icu/Article/details/gtyptvvvxw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.bjfxy.top/Article/details/gtixcgboqt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ppjwa.cn/Article/details/gtxsafmoux.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sweek.top/Article/details/gtkcczvvxc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.9152youxi.cn/Article/details/gtxqjohimk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gtyussrank.html

Ruby: a == b
来源：http://dali.xylfe.cn/Article/details/gtfdmlelqz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhixingplan.top/Article/details/gtmiefswvo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hfpthk.cn/Article/details/gtvcnwzifi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yj202588.top/Article/details/gtksaulhuk.html

PHP:  if (empty($x)) {}
来源：http://dali.pycfn.com/Article/details/gtgwmrihnj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenjidiqi.icu/Article/details/gtvhuuxtrc.html

TS:   if (x == null) {}
来源：http://dali.hysaishi.cn/Article/details/gtsabvnlfo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj20258888.top/Article/details/gthavhgxil.html

Go:   if x == nil {}
来源：http://dali.jianghu66.top/Article/details/gtgwhowavp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hnxiangtu.top/Article/details/gttpyoeubz.html

C#:   if (x is null) {}
来源：http://dali.ppjwa.cn/Article/details/gtmcyrxocp.html

[P07] 防抖与节流
来源：http://dali.pengpengdd.cyou/Article/details/gtagtrnraf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hfpthk.cn/Article/details/gtgsuwidam.html

PHP:  // 手写时间戳比较
来源：http://dali.zhoulong.xyz/Article/details/gtwxxjlcwu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gtxlhygicy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ehwqpu.com/Article/details/gtwumkogaj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jqgfzy.top/Article/details/gthlcrvpst.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.daria6918.cn/Article/details/gtetjxbqqf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cdnleiting.top/Article/details/gtqrzgwqvb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sysykeji.top/Article/details/gtnzcbugvd.html

[P08] 处理浮点精度问题
来源：http://dali.zhoulong.xyz/Article/details/gtrbguielf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj20258.top/Article/details/gttfwyqrih.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.pycfn.com/Article/details/gttrqznkjc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.snrcjt.cn/Article/details/gtweoxiczd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ivvv.top/Article/details/gtpwmopcdd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.svipenyu.cn/Article/details/gtqywlaaqq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnqzz.top/Article/details/gthorlumcl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shuidangran.top/Article/details/gteclmhgat.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hammf.cn/Article/details/gtpmqsnbpc.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gttrwtnntm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhfpnvui.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtejebjdec.html

[Q01] 创建表
来源：http://dali.yueranfly.top/Article/details/gtgscnivuj.html

CREATE TABLE users (
来源：http://dali.yj20258.top/Article/details/gtxraoaett.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.vqdsnc.cn/Article/details/gtmotoqnnx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yongpay.top/Article/details/gtkigpojpo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cucudq.cn/Article/details/gtimixakwf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jianghu66.top/Article/details/gtticoswsw.html

);
来源：http://dali.316326.xyz/Article/details/gtoytfemsp.html

[Q02] 创建带外键的表
来源：http://dali.9152youxi.cn/Article/details/gtgebosmjx.html

CREATE TABLE orders (
来源：http://dali.chenjidiqi.icu/Article/details/gtifczfxrq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigufen.top/Article/details/gtovtsxhsu.html

user_id INT NOT NULL,
来源：http://dali.ivvv.top/Article/details/gtaewrmxgz.html

amount DECIMAL(10, 2),
来源：http://dali.yanxiufei.cn/Article/details/gtxfpgsbuu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.havefunace.top/Article/details/gtzrzvsvxd.html

);
来源：http://dali.pycfn.com/Article/details/gtoraaubis.html

[Q03] 增加列
来源：http://dali.sxryk.cn/Article/details/gtxmerpsqc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.smart0.xyz/Article/details/gtqhdrckwj.html

[Q04] 修改列类型
来源：http://dali.hammf.cn/Article/details/gtolbsdqwr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gogol.net.cn/Article/details/gtjqvljwus.html

[Q05] 重命名列
来源：http://dali.ybcxt.top/Article/details/gtklrxlbmm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.nanxinkj.top/Article/details/gtvnjvvhat.html

[Q06] 删除列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubxdappd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gogol.net.cn/Article/details/gthxpvrkng.html

[Q07] 删除表
来源：http://dali.kuanghao11.cn/Article/details/gtjxstptcq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nanxinkj.top/Article/details/gtpxkoqxje.html

[Q08] 创建普通索引
来源：http://dali.aizwys.cn/Article/details/gtpkiqyxte.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sxryk.cn/Article/details/gtbjkhcalf.html

[Q09] 创建唯一索引
来源：http://dali.gotoacloud.top/Article/details/gttdmvauqs.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cqqwz.cn/Article/details/gttbgbpmuq.html

[Q10] 插入单行
来源：http://dali.hnxiangtu.top/Article/details/gtoftsblfl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gtimyyffmg.html

[Q11] 一次插入多行
来源：http://dali.yanxiufei.cn/Article/details/gtzbnrrvmd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.316326.xyz/Article/details/gtzcchdbvg.html

[Q12] 插入后取自增 ID
来源：http://dali.shuidangran.top/Article/details/gtmnmxoblm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinqigfzy.top/Article/details/gttxuzrjug.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shzxlz.cn/Article/details/gtrxlkxxzh.html

[Q13] 忽略重复插入
来源：http://dali.cucudq.cn/Article/details/gtpmpliqdn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj202588.top/Article/details/gtiyivzlql.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinqigfzy.top/Article/details/gtoqkebcsm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gaohongyu789.top/Article/details/gtvchxcpxq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.vqdsnc.cn/Article/details/gtdkfabnoj.html

[Q15] 查询全部
来源：http://dali.jlsjyb.cn/Article/details/gtnwidygvx.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtndcmrirw.html

[Q16] 查询指定列
来源：http://dali.ivvv.top/Article/details/gteybzhmfj.html

SELECT id, name FROM users;
来源：http://dali.zhengqikj.top/Article/details/gthcwemhcr.html

[Q17] 条件查询
来源：http://dali.wangdashe.top/Article/details/gtcattaucw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gaohongyu789.top/Article/details/gteodscuqx.html

[Q18] 模糊匹配
来源：http://dali.fzhhl.top/Article/details/gtdrpcmmiy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nanxinkj.top/Article/details/gtsdvdwvaw.html

[Q19] 范围查询
来源：http://dali.guannengcc.top/Article/details/gtfsxknzfx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hywenlv.cn/Article/details/gtddfzijiy.html

[Q20] IN 列表
来源：http://dali.yonumen.top/Article/details/gtqpuzxbvh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shzxlz.cn/Article/details/gtqndfhads.html

[Q21] 空值判断
来源：http://dali.ydzc1.top/Article/details/gtlwvbhudq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.smart0.xyz/Article/details/gtpkpkxval.html

[Q22] 排序
来源：http://dali.0kj1m.cn/Article/details/gtfuqczugi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.nanxinkj.top/Article/details/gtkuazslkq.html

[Q23] 分页
来源：http://dali.cucudq.cn/Article/details/gtzinkdmvz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinqigfzy.top/Article/details/gthmlnnobq.html

[Q24] 去重
来源：http://dali.yj20258888.top/Article/details/gttjfxsaeb.html

SELECT DISTINCT city FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtojkawyfw.html

[Q25] 只取前 N 条
来源：http://dali.yueranfly.top/Article/details/gtqxhlargu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.redwolf501.top/Article/details/gttpxgbcbt.html

[Q26] 计数
来源：http://dali.zhixingplan.top/Article/details/gtjzchjauh.html

SELECT COUNT(*) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrtwdrgx.html

[Q27] 条件计数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfxhwfgkv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xuanzx.com/Article/details/gtqxeqzfxe.html

[Q28] 求和与平均
来源：http://dali.pycfn.com/Article/details/gtuvoquzem.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtffhqlxtk.html

[Q29] 最大最小值
来源：http://dali.jiagoushi.top/Article/details/gtvbcxajzi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtbjgtvagg.html

[Q30] 分组统计
来源：http://dali.aibaodan.cn/Article/details/gttgoozjbn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gtnsunuyts.html

[Q31] 分组后过滤
来源：http://dali.cdnleiting.top/Article/details/gtwuiylefw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenzaomai.com/Article/details/gtmusexczc.html

[Q32] 分组拼接字符串
来源：http://dali.yj20258.top/Article/details/gtgxmrefbu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gtotzislwo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.andypj.xyz/Article/details/gtujhlxsbx.html

[Q33] 多列分组
来源：http://dali.zycfv.cn/Article/details/gtiqgxbbzp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.mhx1999.top/Article/details/gtmwgqqtpn.html

[Q34] 每组取第一条
来源：http://dali.haohaochexian.top/Article/details/gtdjmidjxz.html

SELECT * FROM (
来源：http://dali.chenlongwang.top/Article/details/gtyubcnnds.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hnqzz.top/Article/details/gtfeejlplx.html

) t WHERE rn = 1;
来源：http://dali.zhixingplan.top/Article/details/gthpqbeevy.html

[Q35] 内连接
来源：http://dali.cashguo.top/Article/details/gtceoztqqe.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hfpthk.cn/Article/details/gtudqhupxh.html

[Q36] 左连接
来源：http://dali.zycfv.cn/Article/details/gtiqconwth.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gtzptgwtbf.html

[Q37] 右连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvfdusdf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvajjrvsy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yvedp.cn/Article/details/gtexptghhi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gotoacloud.top/Article/details/gtaxkpqcqu.html

[Q39] 自连接（查上下级）
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhwcduet.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gogol.net.cn/Article/details/gtmsvltmlf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.wangdashe.top/Article/details/gtfliinvfi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gotoacloud.top/Article/details/gtrbgnlwvu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hysaishi.cn/Article/details/gtjltopubl.html

[Q41] 多表连接
来源：http://dali.daria6918.cn/Article/details/gtzpanbeya.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.fengsongda.top/Article/details/gtnljtdjmk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.vqdsnc.cn/Article/details/gtgrarxslw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gtmwttkvat.html

[Q42] 连接条件附加过滤
来源：http://dali.sysykeji.top/Article/details/gtrrskwzyu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yueranfly.top/Article/details/gtyortcaoc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.dashuyun.cn/Article/details/gtjjfisvnm.html

[Q43] 标量子查询
来源：http://dali.xuetiantiany.cn/Article/details/gtnbntshsd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.9152youxi.cn/Article/details/gtnaqlisqt.html

[Q44] IN 子查询
来源：http://dali.sxryk.cn/Article/details/gtudukxvdl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cucudq.cn/Article/details/gtljehxltv.html

[Q45] EXISTS 判断存在
来源：http://dali.guowangkeji.top/Article/details/gtrzosxtut.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.snrcjt.cn/Article/details/gtnmraxxlf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ppjwa.cn/Article/details/gtobfwyshg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yanxiufei.cn/Article/details/gtaqzkdqws.html

[Q47] 与平均值比较
来源：http://dali.hnxiangtu.top/Article/details/gtujlaedgj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gzhubu.top/Article/details/gtqqxqcjbk.html

[Q48] CTE 公用表表达式
来源：http://dali.jlsjyb.cn/Article/details/gtyubmenvz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sysykeji.top/Article/details/gtjnbnydog.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.c1oappe.top/Article/details/gtwmekttdj.html

[Q49] 更新单行
来源：http://dali.9152youxi.cn/Article/details/gtnvraucjb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jqgufenzy.top/Article/details/gtizcyekkr.html

[Q50] 批量更新
来源：http://dali.xinyue.icu/Article/details/gtuxurdfgn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gaohongyu789.top/Article/details/gtasnctlwc.html

[Q51] 用子查询更新
来源：http://dali.nanxuanxn.top/Article/details/gtzfjfhlpi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jqgufenzy.top/Article/details/gthtdfujga.html

[Q52] 删除指定行
来源：http://dali.shangyingyoupin.top/Article/details/gtmsgzwdgn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj20258.top/Article/details/gtbuvixpaq.html

[Q53] 按条件删除
来源：http://dali.hnxiangtu.top/Article/details/gtagihokec.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj202588.top/Article/details/gtkgffcxza.html

[Q54] 清空表
来源：http://dali.pycfn.com/Article/details/gtkxnehbzs.html

TRUNCATE TABLE logs;
来源：http://dali.pengpengdd.cyou/Article/details/gtyygefdvk.html

[Q55] 排名（并列占位）
来源：http://dali.redwolf501.top/Article/details/gtgcbtreng.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gthfwvwesd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yueranfly.top/Article/details/gtcatmxhzs.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jianghu66.top/Article/details/gtkxqlmoad.html

[Q57] 行号
来源：http://dali.xylfe.cn/Article/details/gtwspttvip.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.meibo888.top/Article/details/gttoftingp.html

[Q58] 累计求和
来源：http://dali.zhiwuduotai.top/Article/details/gtczonzqlx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjnkwelkh.html

[Q59] 分组内累计
来源：http://dali.tanke756.top/Article/details/gtfjbrenph.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gturqxvmhi.html

[Q60] 取上一行 / 下一行
来源：http://dali.shangyingyoupin.top/Article/details/gtlqbyakij.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.pengpengdd.cyou/Article/details/gtiasgwrqr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtzbcvouan.html


<!-- 参考信息 -->