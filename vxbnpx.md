代发 wailian999

PHP:  // 手写递归函数
来源：http://dali.ybcxt.top/Article/details/gtsjhliiun.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shangyingyoupin.top/Article/details/gtmlisvhtr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangdashe.top/Article/details/gtzsxvzivh.html

Java: // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gthrlrzmrr.html

Go:   // 手写递归
来源：http://dali.daria6918.cn/Article/details/gtdxbrijyj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.pycfn.com/Article/details/gtfkosuqfs.html

C#:   // 手写递归
来源：http://dali.meibo888.top/Article/details/gtzmbxfjqy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tianlin.xyz/Article/details/gtvjcgmumy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jiagoushi.top/Article/details/gtvyoifrah.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nwbrower.top/Article/details/gtxmuudrrl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gaohongyu789.top/Article/details/gtppkhciwv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.svipenyu.cn/Article/details/gthmvpvqop.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nanxuanxn.top/Article/details/gtwymjedfc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xziqi.cn/Article/details/gtcpnjypmh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtslynbrkf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yonumen.top/Article/details/gtsloccerb.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtmoaiaewn.html

O. 并发与异步
来源：http://dali.shanyushiyangtech.top/Article/details/gtnlvipyzn.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtfphkvday.html

[O01] 启动一个线程
来源：http://dali.jinqigufen.top/Article/details/gtlpvncdfa.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hnxiangtu.top/Article/details/gtuaudnauq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonpwigdf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnqeshdbb.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gtnrrmlfwa.html

Java: new Thread(() -> f()).start()
来源：http://dali.smart0.xyz/Article/details/gtpyfjnkdx.html

Go:   go f()
来源：http://dali.316326.xyz/Article/details/gtkbzcnpdd.html

Ruby: Thread.new { f }
来源：http://dali.fengsongda.top/Article/details/gtdgeqbvch.html

C#:   Task.Run(() => F());
来源：http://dali.iojbl.cn/Article/details/gtsmtbbsda.html

[O02] 使用线程池
来源：http://dali.wangshuangyany.cn/Article/details/gtadyzcmmq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xylfe.cn/Article/details/gtcxqkgqyq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.redwolf501.top/Article/details/gtabkhykhc.html

JS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gtubcdrikz.html

TS:   // worker_threads 线程池
来源：http://dali.yj202588.top/Article/details/gttuykbvld.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.dashuyun.cn/Article/details/gtcmlfvadk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hysaishi.cn/Article/details/gtntrgjdxy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xziqi.cn/Article/details/gtyknrapql.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shangyingyoupin.top/Article/details/gtlhbamhmw.html

[O03] 加锁保护共享数据
来源：http://dali.wangdashe.top/Article/details/gtnhrgdjzw.html

Py:   with lock: shared += 1
来源：http://dali.yj20258.top/Article/details/gtattfuyut.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yangfankeji.com/Article/details/gtffcgezyd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shzxlz.cn/Article/details/gthzezogtu.html

TS:   // 同 JS
来源：http://dali.aibaodan.cn/Article/details/gtgznulloh.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhengqikj.top/Article/details/gtplkbzmhm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tanke756.top/Article/details/gtcouaxndm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.fengsongda.top/Article/details/gtrqbeoiji.html

C#:   lock (gate) { shared++; }
来源：http://dali.9152youxi.cn/Article/details/gttbcbihia.html

[O04] 定义异步函数并等待
来源：http://dali.snrcjt.cn/Article/details/gtksetflgc.html

Py:   async def f():⏎    await g()
来源：http://dali.tian-w.cn/Article/details/gtpeeluwts.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yuxming.cn/Article/details/gtkjoesmvs.html

JS:   async function f() { await g(); }
来源：http://dali.sysykeji.top/Article/details/gtmoeunofg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yuxming.cn/Article/details/gtyxjwppzr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jqgfzy.top/Article/details/gtknyujkhf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.kuanghao11.cn/Article/details/gtapdclvhr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhoulong.xyz/Article/details/gtvqskdzto.html

C#:   async Task F() { await G(); }
来源：http://dali.zhongyouzk.top/Article/details/gtcwiqetys.html

[O05] 并发执行并等待全部完成
来源：http://dali.aizwys.cn/Article/details/gttzxwhnqn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhiwuduotai.top/Article/details/gtpoktqpsd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.tanke756.top/Article/details/gtpkkdlgrh.html

JS:   await Promise.all(tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gtaybazxgy.html

TS:   await Promise.all(tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gtwjmuturn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.redwolf501.top/Article/details/gtbqbdsoyo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskkzbjgd.html

Ruby: threads.map(&:join)
来源：http://dali.zhengqikj.top/Article/details/gtqpyhakex.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.c1oappe.top/Article/details/gtyozrhjxk.html

[O06] 使用进程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmddxuwbs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqtfphfp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xziqi.cn/Article/details/gtvdjvzffx.html

JS:   // child_process / cluster 模块
来源：http://dali.zhengqikj.top/Article/details/gtvusqcwdf.html

TS:   // child_process / cluster 模块
来源：http://dali.sweek.top/Article/details/gtuzqxijpt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.mhx1999.top/Article/details/gtunnoiuip.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhongyouzk.top/Article/details/gtnefvvgwl.html

Ruby: // fork 块
来源：http://dali.jqgufenzy.top/Article/details/gtvdmjviae.html

C#:   Parallel.For
来源：http://dali.yangfankeji.com/Article/details/gtfphgzphu.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtwxajxehq.html

P. 常用工具函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtqnxhwwrr.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtwpskixkd.html

[P01] 生成 UUID
来源：http://dali.pengpengdd.cyou/Article/details/gtqpchegbo.html

Py:   str(uuid.uuid4())
来源：http://dali.jinqigfzy.top/Article/details/gtymzknpxn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.redwolf501.top/Article/details/gtslclzxxk.html

JS:   crypto.randomUUID()
来源：http://dali.xinyue.icu/Article/details/gtubwqojuk.html

TS:   crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gtvkhbnwwa.html

Java: UUID.randomUUID().toString()
来源：http://dali.dianchejie.cn/Article/details/gtqhmgdtbp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.daxiang520.top/Article/details/gtbrekugpy.html

Ruby: SecureRandom.uuid
来源：http://dali.pycfn.com/Article/details/gtjfmyblpq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.fzhhl.top/Article/details/gtklwnbldh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.birdmap.top/Article/details/gtugrxribz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.guannengcc.top/Article/details/gttxpllqtc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.vqdsnc.cn/Article/details/gtroxyuzxo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.vqdsnc.cn/Article/details/gtbwssnlsd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cqqwz.cn/Article/details/gtwkurojob.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.mhx1999.top/Article/details/gtvbzqcifb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.c1oappe.top/Article/details/gtdeugfzrv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj20258.top/Article/details/gtjvbriwxh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jqgufenzy.top/Article/details/gtarohmpjw.html

[P03] 生成短随机字符串
来源：http://dali.ydzc1.top/Article/details/gtyxnjchde.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xylfe.cn/Article/details/gtrnsixdhy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.dianchejie.cn/Article/details/gtwunveahh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fzhhl.top/Article/details/gtltptscwo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cashguo.top/Article/details/gtsmvseqjd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gaohongyu789.top/Article/details/gtxhxgaghc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.guowangkeji.top/Article/details/gtreakzdmg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yueranfly.top/Article/details/gtedsegzfn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhengqikj.top/Article/details/gtolnoqggb.html

[P04] 求长度
来源：http://dali.316326.xyz/Article/details/gtzzegcokf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shzxlz.cn/Article/details/gtkuxgozzm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtjchwdgty.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangshuangyany.cn/Article/details/gtxglsnpmd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sweek.top/Article/details/gtjmdnkymd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shzxlz.cn/Article/details/gtdnoxcyvq.html

Go:   len(arr);  len(m)
来源：http://dali.xuanzx.com/Article/details/gtiydlgipu.html

Ruby: x.length;  x.size
来源：http://dali.andypj.xyz/Article/details/gtritmuagi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhixingplan.top/Article/details/gtpujoshrv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ivvv.top/Article/details/gtsqhlhnwx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.c1oappe.top/Article/details/gthgicnzxq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hammf.cn/Article/details/gtgdpwistd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.daxiang520.top/Article/details/gtnsitwbkd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jlsjyb.cn/Article/details/gtwtcstusu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sysykeji.top/Article/details/gtmtgvnthq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yvedp.cn/Article/details/gtwgrpcwea.html

Ruby: a == b
来源：http://dali.0kj1m.cn/Article/details/gtehmqyikw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.fzhhl.top/Article/details/gtuoouysej.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hnqzz.top/Article/details/gtqgyrihoc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.guowangkeji.top/Article/details/gtfszwqbrd.html

PHP:  if (empty($x)) {}
来源：http://dali.zycfv.cn/Article/details/gtjdokckqy.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.dianchejie.cn/Article/details/gtckxmeuuo.html

TS:   if (x == null) {}
来源：http://dali.ydzc1.top/Article/details/gtnkkgjncc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinqigfzy.top/Article/details/gtxgfiotbl.html

Go:   if x == nil {}
来源：http://dali.hywenlv.cn/Article/details/gtanhwuwgr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hammf.cn/Article/details/gtrsutuvbt.html

C#:   if (x is null) {}
来源：http://dali.cashguo.top/Article/details/gtzmdadfne.html

[P07] 防抖与节流
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaucpepgf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzyedthvf.html

PHP:  // 手写时间戳比较
来源：http://dali.xuanzx.com/Article/details/gtkylvxhvi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcdcocinf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sweek.top/Article/details/gtgwelqmxh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhixingplan.top/Article/details/gtrgefiuvp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinqigufen.top/Article/details/gtdqnauuqs.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yangfankeji.com/Article/details/gtzwdehjkk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yongpay.top/Article/details/gtmofcniqx.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigufen.top/Article/details/gtrufgzprk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hysaishi.cn/Article/details/gtjuovftzl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zdqjudy.top/Article/details/gtxonsskst.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjhvjqlpm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.9152youxi.cn/Article/details/gtvwyumyws.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hysaishi.cn/Article/details/gtdepjxaai.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.iojbl.cn/Article/details/gttfpolqij.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gzhubu.top/Article/details/gttjpgavmi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hysaishi.cn/Article/details/gtcoawpxoa.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtsvlckxlx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yvedp.cn/Article/details/gtvnssxaud.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtujjptmix.html

[Q01] 创建表
来源：http://dali.gogol.net.cn/Article/details/gtbktmijhe.html

CREATE TABLE users (
来源：http://dali.gotoacloud.top/Article/details/gtprekymfq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sxryk.cn/Article/details/gtbmqaqawf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhiwuduotai.top/Article/details/gtxethlrjk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.guannengcc.top/Article/details/gthjdwsojm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj20258.top/Article/details/gtbclsfywt.html

);
来源：http://dali.gotoacloud.top/Article/details/gtmuvthjit.html

[Q02] 创建带外键的表
来源：http://dali.xinyue.icu/Article/details/gtgjqzgesg.html

CREATE TABLE orders (
来源：http://dali.mhx1999.top/Article/details/gtivrpbrox.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj202588.top/Article/details/gtzfioduxi.html

user_id INT NOT NULL,
来源：http://dali.shuidangran.top/Article/details/gtgaljaulu.html

amount DECIMAL(10, 2),
来源：http://dali.meibo888.top/Article/details/gterytccuy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sweek.top/Article/details/gtmuncbxqf.html

);
来源：http://dali.svipenyu.cn/Article/details/gtoiqziryp.html

[Q03] 增加列
来源：http://dali.yj202588.top/Article/details/gtvjwtykqp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ivvv.top/Article/details/gtcqpubycp.html

[Q04] 修改列类型
来源：http://dali.jyoumei.cn/Article/details/gtlerjnwzj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gtmgfxjgki.html

[Q05] 重命名列
来源：http://dali.ivvv.top/Article/details/gtzrnuutot.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.pengpengdd.cyou/Article/details/gtmhpvpngj.html

[Q06] 删除列
来源：http://dali.hywenlv.cn/Article/details/gtfipddrgk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtluqekjxp.html

[Q07] 删除表
来源：http://dali.jqgufenzy.top/Article/details/gtnjluhpaf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.guowangkeji.top/Article/details/gteqgctuhj.html

[Q08] 创建普通索引
来源：http://dali.sufxvd.cn/Article/details/gtighgstof.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hywenlv.cn/Article/details/gtvivtjpea.html

[Q09] 创建唯一索引
来源：http://dali.feifeiyinyue.top/Article/details/gtsyfvmfnp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxvctgao.html

[Q10] 插入单行
来源：http://dali.cucudq.cn/Article/details/gtzivsveiy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.bjfxy.top/Article/details/gttptdmgit.html

[Q11] 一次插入多行
来源：http://dali.pycfn.com/Article/details/gtvhcuyzoa.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xinyue.icu/Article/details/gtbpwpnygw.html

[Q12] 插入后取自增 ID
来源：http://dali.pengpengdd.cyou/Article/details/gtbklehcvw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.chenzaomai.com/Article/details/gtikntqsau.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sweek.top/Article/details/gtqsgcavzz.html

[Q13] 忽略重复插入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzddpfql.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cucudq.cn/Article/details/gtnimwcwmo.html

[Q14] 存在则更新（upsert）
来源：http://dali.jiagoushi.top/Article/details/gtdzlsyswh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.c1oappe.top/Article/details/gtnlecsmzh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.kuanghao11.cn/Article/details/gtsewjpbma.html

[Q15] 查询全部
来源：http://dali.jinghuilouyu.cn/Article/details/gtzknubapx.html

SELECT * FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtmmgukqgn.html

[Q16] 查询指定列
来源：http://dali.yueranfly.top/Article/details/gtzjapbzvb.html

SELECT id, name FROM users;
来源：http://dali.wangdashe.top/Article/details/gtchtxlidw.html

[Q17] 条件查询
来源：http://dali.havefunace.top/Article/details/gtzqobgrgk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jqgfzy.top/Article/details/gtsnfzpyhk.html

[Q18] 模糊匹配
来源：http://dali.yangfankeji.com/Article/details/gthscmnlrn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.haohaochexian.top/Article/details/gteidbfziw.html

[Q19] 范围查询
来源：http://dali.guannengcc.top/Article/details/gtzasmeobh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cdnleiting.top/Article/details/gthrwjpmvj.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gtzgjbqnpj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuxming.cn/Article/details/gtkocnitbt.html

[Q21] 空值判断
来源：http://dali.sxryk.cn/Article/details/gtrqpxcqyn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.0kj1m.cn/Article/details/gtvqpzplvn.html

[Q22] 排序
来源：http://dali.guowangkeji.top/Article/details/gtkcnafzvy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xuetiantiany.cn/Article/details/gtotdiqpeg.html

[Q23] 分页
来源：http://dali.yj202588.top/Article/details/gtmigklirx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlmncwqub.html

[Q24] 去重
来源：http://dali.ehwqpu.com/Article/details/gtbzjslqlv.html

SELECT DISTINCT city FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtaycmcbqh.html

[Q25] 只取前 N 条
来源：http://dali.zhoulong.xyz/Article/details/gtvbbyncck.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sufxvd.cn/Article/details/gtsqzmwyid.html

[Q26] 计数
来源：http://dali.cheryme.top/Article/details/gtkzxucfmy.html

SELECT COUNT(*) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtcwalmfpl.html

[Q27] 条件计数
来源：http://dali.gogol.net.cn/Article/details/gtdbdayubw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtyzkyornv.html

[Q28] 求和与平均
来源：http://dali.zhiwuduotai.top/Article/details/gtrgytusbh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtmjvuazcm.html

[Q29] 最大最小值
来源：http://dali.pycfn.com/Article/details/gtupccigsi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtxkkmzxzy.html

[Q30] 分组统计
来源：http://dali.jqgfzy.top/Article/details/gtfejatuku.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gthyrwvnzm.html

[Q31] 分组后过滤
来源：http://dali.daria6918.cn/Article/details/gtpbxifmxf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yangfankeji.com/Article/details/gtndbebdlh.html

[Q32] 分组拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gtpjjdzogb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gtjyxejxma.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenzaomai.com/Article/details/gtrxwzxxjw.html

[Q33] 多列分组
来源：http://dali.jinqigufen.top/Article/details/gtdeymbrex.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yonumen.top/Article/details/gtcuqobwdb.html

[Q34] 每组取第一条
来源：http://dali.iojbl.cn/Article/details/gtlkrsqqve.html

SELECT * FROM (
来源：http://dali.havefunace.top/Article/details/gtqoxfcifk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.guannengcc.top/Article/details/gtaduhmsdm.html

) t WHERE rn = 1;
来源：http://dali.yangfankeji.com/Article/details/gtbxirfcig.html

[Q35] 内连接
来源：http://dali.guannengcc.top/Article/details/gtinxhcwkx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.316326.xyz/Article/details/gtbuzgrmqf.html

[Q36] 左连接
来源：http://dali.zdqjudy.top/Article/details/gtpnditkgk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yonumen.top/Article/details/gtapbmueys.html

[Q37] 右连接
来源：http://dali.daria6918.cn/Article/details/gtdzagslfw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zdqjudy.top/Article/details/gtrocyrizo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cdnleiting.top/Article/details/gtrwqrujoh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xinyue.icu/Article/details/gtswhluzki.html

[Q39] 自连接（查上下级）
来源：http://dali.pengpengdd.cyou/Article/details/gtwliurxgb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.snrcjt.cn/Article/details/gtbnarudij.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtasdjzutp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ehwqpu.com/Article/details/gtdtfhgmxe.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhoulong.xyz/Article/details/gtfujbaptm.html

[Q41] 多表连接
来源：http://dali.ydzc1.top/Article/details/gtjdolwibh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.wangdashe.top/Article/details/gtqaapuevu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yangfankeji.com/Article/details/gttgutnmmb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hnqzz.top/Article/details/gtbtxdxror.html

[Q42] 连接条件附加过滤
来源：http://dali.316326.xyz/Article/details/gttpevboju.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cdnleiting.top/Article/details/gtnuuejzxi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinqigufen.top/Article/details/gtvzhanacp.html

[Q43] 标量子查询
来源：http://dali.nanxinkj.top/Article/details/gtgkgsgtip.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.tian-w.cn/Article/details/gtvxhlxgaw.html

[Q44] IN 子查询
来源：http://dali.jqgufenzy.top/Article/details/gtlacehhlw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthxzfkefm.html

[Q45] EXISTS 判断存在
来源：http://dali.cheryme.top/Article/details/gtdumapncv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gotoacloud.top/Article/details/gtdbqpxdpy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yuxming.cn/Article/details/gtqxucbewz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xylfe.cn/Article/details/gtdhgbonab.html

[Q47] 与平均值比较
来源：http://dali.sxryk.cn/Article/details/gtvkmoswig.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cucudq.cn/Article/details/gtohiicrxr.html

[Q48] CTE 公用表表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvmosplp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.316326.xyz/Article/details/gtghyujtrx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigufen.top/Article/details/gtshiisjfk.html

[Q49] 更新单行
来源：http://dali.gzhubu.top/Article/details/gttniddhzt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hysaishi.cn/Article/details/gtsndgmzst.html

[Q50] 批量更新
来源：http://dali.zhiwuduotai.top/Article/details/gtrrowpojf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.mhx1999.top/Article/details/gtvioolpdm.html

[Q51] 用子查询更新
来源：http://dali.jinqigufen.top/Article/details/gtkfnscphv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtaqbfrtsp.html

[Q52] 删除指定行
来源：http://dali.cdnleiting.top/Article/details/gtgmkzzohn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yonumen.top/Article/details/gtyfzbnllm.html

[Q53] 按条件删除
来源：http://dali.zhongyouzk.top/Article/details/gtqqkdvkze.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sysykeji.top/Article/details/gtemrlazuy.html

[Q54] 清空表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbgygwnvv.html

TRUNCATE TABLE logs;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlenibeib.html

[Q55] 排名（并列占位）
来源：http://dali.mhx1999.top/Article/details/gtypmmrenc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hammf.cn/Article/details/gtwmthpdxd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hywenlv.cn/Article/details/gtlowazjzc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhiwuduotai.top/Article/details/gtyaykiwax.html

[Q57] 行号
来源：http://dali.hongshengwenyu.top/Article/details/gtydoqnxks.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtpswtsztj.html

[Q58] 累计求和
来源：http://dali.c1oappe.top/Article/details/gtyndeyvyb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ivvv.top/Article/details/gtmolbzvun.html

[Q59] 分组内累计
来源：http://dali.xylfe.cn/Article/details/gtrcadihnx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtpxkpecxv.html

[Q60] 取上一行 / 下一行
来源：http://dali.chenjidiqi.icu/Article/details/gtlvbnahjf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sysykeji.top/Article/details/gtqazmtzjn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.meibo888.top/Article/details/gtlpjwicpy.html

[Q61] 移动平均
来源：http://dali.jqgfzy.top/Article/details/gtfoxsrizg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtpzplmxze.html

[Q62] 分组占比
来源：http://dali.316326.xyz/Article/details/gtshylgxba.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gtiqwbpjmi.html

[Q63] 开启事务
来源：http://dali.guannengcc.top/Article/details/gtcjqxdthb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yueranfly.top/Article/details/gtscjvayde.html

[Q64] 提交事务
来源：http://dali.xinyue.icu/Article/details/gtonihevuf.html

COMMIT;
来源：http://dali.xuanzx.com/Article/details/gtcfkmaoqn.html


<!-- 参考信息 -->