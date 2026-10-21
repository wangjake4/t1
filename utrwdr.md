代发 wailian999

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtmvjamxdi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.haohaochexian.top/Article/details/gttwaozmcp.html

Java: class Node { int v; Node next; }
来源：http://dali.daxiang520.top/Article/details/gtnojqboxz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.andypj.xyz/Article/details/gtvxivpbiz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhengqikj.top/Article/details/gtwwzvmxly.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jlsjyb.cn/Article/details/gtmcoydzmj.html

[N11] 二叉树中序遍历
来源：http://dali.hammf.cn/Article/details/gtrjvfxrrf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ivvv.top/Article/details/gtsgpifwpw.html

PHP:  // 手写递归函数
来源：http://dali.hnxiangtu.top/Article/details/gtkdfvmvtm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aizwys.cn/Article/details/gtqfhgnonr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shzxlz.cn/Article/details/gtbwiingzu.html

Java: // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gtainqfebt.html

Go:   // 手写递归
来源：http://dali.birdmap.top/Article/details/gtptryglmr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.meibo888.top/Article/details/gtdpviwxbs.html

C#:   // 手写递归
来源：http://dali.nwbrower.top/Article/details/gthzjurkdl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.wangdashe.top/Article/details/gtozoyvuzx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinqigufen.top/Article/details/gtrdtpyrnw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jqgfzy.top/Article/details/gtdkshekah.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangshuangyany.cn/Article/details/gtjlrthezv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigfzy.top/Article/details/gtmuptrpfd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuanzhike.top/Article/details/gticwdjfoi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhiwuduotai.top/Article/details/gtejswkiza.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yanxiufei.cn/Article/details/gtljqoenwf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hfpthk.cn/Article/details/gtcnjfebas.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtofxzpcal.html

O. 并发与异步
来源：http://dali.chenjidiqi.icu/Article/details/gtuhftjahs.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtqfpoqwiu.html

[O01] 启动一个线程
来源：http://dali.9152youxi.cn/Article/details/gtkimyrokr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hongshengwenyu.top/Article/details/gtxtcktkzk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ivvv.top/Article/details/gtbpamjndj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cheryme.top/Article/details/gtleokhuzj.html

TS:   // 同 JS
来源：http://dali.sweek.top/Article/details/gtwgbfdklv.html

Java: new Thread(() -> f()).start()
来源：http://dali.gotoacloud.top/Article/details/gtvpkbbmnb.html

Go:   go f()
来源：http://dali.svipenyu.cn/Article/details/gtrjjpmkzn.html

Ruby: Thread.new { f }
来源：http://dali.cdnleiting.top/Article/details/gthgvlbjzp.html

C#:   Task.Run(() => F());
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcgsnnzxp.html

[O02] 使用线程池
来源：http://dali.cheryme.top/Article/details/gtrbvlwlff.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxgcnzczg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.316326.xyz/Article/details/gtngefpasn.html

JS:   // worker_threads 线程池
来源：http://dali.sysykeji.top/Article/details/gtclkukqmr.html

TS:   // worker_threads 线程池
来源：http://dali.hammf.cn/Article/details/gtdzpahyho.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.iojbl.cn/Article/details/gtqihqbsqt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhiwuduotai.top/Article/details/gtmisddliz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.dianchejie.cn/Article/details/gtreipkbsf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yuanzhike.top/Article/details/gtrcvepbyf.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gtapfcyxxl.html

Py:   with lock: shared += 1
来源：http://dali.guowangkeji.top/Article/details/gtqwyjelub.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tian-w.cn/Article/details/gtgygnlyok.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yanxiufei.cn/Article/details/gtvchsedgm.html

TS:   // 同 JS
来源：http://dali.jiagoushi.top/Article/details/gtnprldscg.html

Java: synchronized (this) { shared++; }
来源：http://dali.meibo888.top/Article/details/gttzuygyve.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.pycfn.com/Article/details/gttxqnqhlz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ivvv.top/Article/details/gtggsxsscy.html

C#:   lock (gate) { shared++; }
来源：http://dali.sweek.top/Article/details/gthgfazghz.html

[O04] 定义异步函数并等待
来源：http://dali.guowangkeji.top/Article/details/gtvyikwjot.html

Py:   async def f():⏎    await g()
来源：http://dali.yvedp.cn/Article/details/gtqpbkcnpb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shangyingyoupin.top/Article/details/gtswbgvmqx.html

JS:   async function f() { await g(); }
来源：http://dali.jlsjyb.cn/Article/details/gtfdzeimqa.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sysykeji.top/Article/details/gtzngjksmc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jqgfzy.top/Article/details/gtpyjazuao.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xylfe.cn/Article/details/gtufvwcefl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jiagoushi.top/Article/details/gtzbnokyaw.html

C#:   async Task F() { await G(); }
来源：http://dali.daria6918.cn/Article/details/gtegasojkc.html

[O05] 并发执行并等待全部完成
来源：http://dali.gzhubu.top/Article/details/gtusgkxjeh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.birdmap.top/Article/details/gthrbbizcm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhixingplan.top/Article/details/gtrsvkpnkd.html

JS:   await Promise.all(tasks)
来源：http://dali.ppjwa.cn/Article/details/gtpzzkbyli.html

TS:   await Promise.all(tasks)
来源：http://dali.cashguo.top/Article/details/gtnnvxvaec.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ivvv.top/Article/details/gtqxuylmig.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ydzc1.top/Article/details/gtswpezbcs.html

Ruby: threads.map(&:join)
来源：http://dali.ydzc1.top/Article/details/gtutglyvpr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sysykeji.top/Article/details/gtvsbdgtup.html

[O06] 使用进程池
来源：http://dali.tianlin.xyz/Article/details/gtpqrvaymt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ppjwa.cn/Article/details/gtweshjuxb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gotoacloud.top/Article/details/gtqjgqqavo.html

JS:   // child_process / cluster 模块
来源：http://dali.hammf.cn/Article/details/gtqtwvnmkz.html

TS:   // child_process / cluster 模块
来源：http://dali.jinghuilouyu.cn/Article/details/gtrkfoypfv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ivvv.top/Article/details/gttikoddpn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.316326.xyz/Article/details/gtuwmkkwyx.html

Ruby: // fork 块
来源：http://dali.sufxvd.cn/Article/details/gtwfrtruwn.html

C#:   Parallel.For
来源：http://dali.0kj1m.cn/Article/details/gtgnnrsbsw.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtbrluacxk.html

P. 常用工具函数
来源：http://dali.xuetiantiany.cn/Article/details/gteayryood.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtyhxqnoee.html

[P01] 生成 UUID
来源：http://dali.yanxiufei.cn/Article/details/gtlqeznfky.html

Py:   str(uuid.uuid4())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtopflcame.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.fzhhl.top/Article/details/gtiunlhxwx.html

JS:   crypto.randomUUID()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtesmrdxag.html

TS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gtjmdbsolj.html

Java: UUID.randomUUID().toString()
来源：http://dali.cheryme.top/Article/details/gtijyqjsej.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xylfe.cn/Article/details/gtwjqrgded.html

Ruby: SecureRandom.uuid
来源：http://dali.havefunace.top/Article/details/gtaasvvncf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.pengpengdd.cyou/Article/details/gtccqwynte.html

[P02] MD5 / SHA256 摘要
来源：http://dali.daxiang520.top/Article/details/gtotltcibr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sweek.top/Article/details/gtfminszgv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhongyouzk.top/Article/details/gtlttnhnwt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cdnleiting.top/Article/details/gtkgsqakij.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jqgfzy.top/Article/details/gtljbgjmpi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.iojbl.cn/Article/details/gtcocwxmzf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nanxuanxn.top/Article/details/gtrjbtcidh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xinyue.icu/Article/details/gtjzeotnac.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.daxiang520.top/Article/details/gtkqbciulv.html

[P03] 生成短随机字符串
来源：http://dali.daxiang520.top/Article/details/gtrlgihrnp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.aibaodan.cn/Article/details/gtlllvmyvf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.pengpengdd.cyou/Article/details/gtuoexkhdb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258888.top/Article/details/gtxuhnnpif.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yvedp.cn/Article/details/gtnpqbgvtu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.havefunace.top/Article/details/gtunlkdakk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jyoumei.cn/Article/details/gteporhvqh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.haohaochexian.top/Article/details/gtkqiujjrw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.haohaochexian.top/Article/details/gtdhqmnnwt.html

[P04] 求长度
来源：http://dali.quarkkingdee.top/Article/details/gtbihbmqhi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.dianchejie.cn/Article/details/gtdtignjkd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gtbnakslip.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangdashe.top/Article/details/gtdgqilcmb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gzhubu.top/Article/details/gtswntlfzm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.andypj.xyz/Article/details/gtyjojvzme.html

Go:   len(arr);  len(m)
来源：http://dali.yj20258.top/Article/details/gtdmcxwnhy.html

Ruby: x.length;  x.size
来源：http://dali.jyoumei.cn/Article/details/gtvowijrwj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ydzc1.top/Article/details/gtlyfwnhuy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sxryk.cn/Article/details/gtstpuejec.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hysaishi.cn/Article/details/gtjqorktie.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sysykeji.top/Article/details/gtupwtgqcs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hnxiangtu.top/Article/details/gtkytrxige.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.0kj1m.cn/Article/details/gtutkrifbc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hammf.cn/Article/details/gteduptxnf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdggbnqh.html

Ruby: a == b
来源：http://dali.xylfe.cn/Article/details/gtowdarrko.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.andypj.xyz/Article/details/gtfrlohiah.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jqgfzy.top/Article/details/gtpnkepnit.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinqigufen.top/Article/details/gtqcndzztd.html

PHP:  if (empty($x)) {}
来源：http://dali.zhixingplan.top/Article/details/gtvoxdvwsn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.bjfxy.top/Article/details/gtyvutupna.html

TS:   if (x == null) {}
来源：http://dali.sysykeji.top/Article/details/gtydcoxsyp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shzxlz.cn/Article/details/gtlnvzsmnf.html

Go:   if x == nil {}
来源：http://dali.guowangkeji.top/Article/details/gtnwzxzlne.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xylfe.cn/Article/details/gtzpdrlvfv.html

C#:   if (x is null) {}
来源：http://dali.zycfv.cn/Article/details/gtbsoijlie.html

[P07] 防抖与节流
来源：http://dali.nanxuanxn.top/Article/details/gtbahymqti.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yangfankeji.com/Article/details/gtbvdhjjrv.html

PHP:  // 手写时间戳比较
来源：http://dali.xinyue.icu/Article/details/gtgklytvpp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.smart0.xyz/Article/details/gtkqirccnk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gtndnuxfza.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hnxiangtu.top/Article/details/gtvfxlijwq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhengqikj.top/Article/details/gtobclfwuq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtrstiywlh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gotoacloud.top/Article/details/gtlzovaqgw.html

[P08] 处理浮点精度问题
来源：http://dali.fengsongda.top/Article/details/gtbrpprvax.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.redwolf501.top/Article/details/gtiigmkukc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gotoacloud.top/Article/details/gtxovlnbet.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahjvyepa.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sysykeji.top/Article/details/gtamgbqjvw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj20258.top/Article/details/gtcagnujpv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.fengsongda.top/Article/details/gtdfyopwmy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.daria6918.cn/Article/details/gtaimnyqis.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.svipenyu.cn/Article/details/gtgzfatdcm.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrkwczfcd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.feifeiyinyue.top/Article/details/gtlvbwfatl.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtlbtbaoqk.html

[Q01] 创建表
来源：http://dali.shzxlz.cn/Article/details/gtnooummvx.html

CREATE TABLE users (
来源：http://dali.chenzaomai.com/Article/details/gtgdbotnlu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigufen.top/Article/details/gtlrnhqeza.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yanxiufei.cn/Article/details/gtpbmogsrm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.snrcjt.cn/Article/details/gtmjhdmbrm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cashguo.top/Article/details/gtapedibdb.html

);
来源：http://dali.daria6918.cn/Article/details/gtjvibqrtg.html

[Q02] 创建带外键的表
来源：http://dali.xuetiantiany.cn/Article/details/gtgqvehbvp.html

CREATE TABLE orders (
来源：http://dali.nanxuanxn.top/Article/details/gtoznqbgos.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yangfankeji.com/Article/details/gtnfnhfpud.html

user_id INT NOT NULL,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaaqluhto.html

amount DECIMAL(10, 2),
来源：http://dali.xylfe.cn/Article/details/gtbrhothwi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.birdmap.top/Article/details/gtmsnnodxq.html

);
来源：http://dali.cashguo.top/Article/details/gtlguskxcy.html

[Q03] 增加列
来源：http://dali.jinqigfzy.top/Article/details/gtccqujktb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.kuanghao11.cn/Article/details/gtgwkuiwny.html

[Q04] 修改列类型
来源：http://dali.zycfv.cn/Article/details/gtpfwbkebx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.iojbl.cn/Article/details/gthroavdsu.html

[Q05] 重命名列
来源：http://dali.fengsongda.top/Article/details/gtnjumjyfy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hnqzz.top/Article/details/gtoubthffs.html

[Q06] 删除列
来源：http://dali.yuxming.cn/Article/details/gtywuhlpjh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yueranfly.top/Article/details/gtmczkxusx.html

[Q07] 删除表
来源：http://dali.yanxiufei.cn/Article/details/gtogqnrxum.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmszktobv.html

[Q08] 创建普通索引
来源：http://dali.ppjwa.cn/Article/details/gtwxtkomxw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenzaomai.com/Article/details/gtooiskxke.html

[Q09] 创建唯一索引
来源：http://dali.cheryme.top/Article/details/gthjxwjecl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.kuanghao11.cn/Article/details/gtdakugwfr.html

[Q10] 插入单行
来源：http://dali.cqqwz.cn/Article/details/gtbhdhprzl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzibywvsv.html

[Q11] 一次插入多行
来源：http://dali.redwolf501.top/Article/details/gthyjqpmja.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ehwqpu.com/Article/details/gtylqlttpk.html

[Q12] 插入后取自增 ID
来源：http://dali.yvedp.cn/Article/details/gtdyjfvrqh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ydzc1.top/Article/details/gtpmdyxdih.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.bjfxy.top/Article/details/gtluudntpy.html

[Q13] 忽略重复插入
来源：http://dali.jyoumei.cn/Article/details/gtswmgwuzc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sxryk.cn/Article/details/gtsolugafu.html

[Q14] 存在则更新（upsert）
来源：http://dali.shzxlz.cn/Article/details/gtzsojkcuq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sxryk.cn/Article/details/gtislomnme.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hammf.cn/Article/details/gtjuaxhuhs.html

[Q15] 查询全部
来源：http://dali.hfpthk.cn/Article/details/gtpzxgbpal.html

SELECT * FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gttmqodzqa.html

[Q16] 查询指定列
来源：http://dali.zhiwuduotai.top/Article/details/gtzvaaffaf.html

SELECT id, name FROM users;
来源：http://dali.c1oappe.top/Article/details/gtdhkqzist.html

[Q17] 条件查询
来源：http://dali.ybcxt.top/Article/details/gtmeotxluj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtyssblmpd.html

[Q18] 模糊匹配
来源：http://dali.birdmap.top/Article/details/gtbntotooi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenlongwang.top/Article/details/gtqveuapfw.html

[Q19] 范围查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtmhttypso.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jqgfzy.top/Article/details/gtcvktmtph.html

[Q20] IN 列表
来源：http://dali.hfpthk.cn/Article/details/gtloyztsbv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tanke756.top/Article/details/gtnoyptzcm.html

[Q21] 空值判断
来源：http://dali.havefunace.top/Article/details/gtsdmirnia.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.guowangkeji.top/Article/details/gtjiotzkts.html

[Q22] 排序
来源：http://dali.guannengcc.top/Article/details/gtalysxpfi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gtrmvtbfwe.html

[Q23] 分页
来源：http://dali.ivvv.top/Article/details/gtlruxddbz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hnxiangtu.top/Article/details/gtmltlpxxd.html

[Q24] 去重
来源：http://dali.smart0.xyz/Article/details/gtkrbkxjmi.html

SELECT DISTINCT city FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtxmjagceo.html

[Q25] 只取前 N 条
来源：http://dali.jinqigfzy.top/Article/details/gtacnooncu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jqgfzy.top/Article/details/gtihyihrcq.html

[Q26] 计数
来源：http://dali.sufxvd.cn/Article/details/gtoaigfrbv.html

SELECT COUNT(*) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtgsymdqqy.html

[Q27] 条件计数
来源：http://dali.dianchejie.cn/Article/details/gtzsmjyegq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.havefunace.top/Article/details/gtbixmgnms.html

[Q28] 求和与平均
来源：http://dali.ybcxt.top/Article/details/gtqttmrene.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtecpgwgqk.html

[Q29] 最大最小值
来源：http://dali.jinghuilouyu.cn/Article/details/gtgynpqzki.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtmddikjdj.html

[Q30] 分组统计
来源：http://dali.haohaochexian.top/Article/details/gtxrukbqgj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ppjwa.cn/Article/details/gtutxlfbrs.html

[Q31] 分组后过滤
来源：http://dali.zhoulong.xyz/Article/details/gtuyuaewbn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cqqwz.cn/Article/details/gtiekdyjpy.html

[Q32] 分组拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtbsqoezqj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gtyfbueibc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.vqdsnc.cn/Article/details/gtdmvyydzv.html

[Q33] 多列分组
来源：http://dali.pycfn.com/Article/details/gtxzjmktoh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.havefunace.top/Article/details/gtyoazissr.html

[Q34] 每组取第一条
来源：http://dali.yj20258888.top/Article/details/gtupxeyzss.html

SELECT * FROM (
来源：http://dali.cucudq.cn/Article/details/gtesnzavem.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sweek.top/Article/details/gtpzsfajoa.html

) t WHERE rn = 1;
来源：http://dali.sweek.top/Article/details/gtcfbluzzl.html

[Q35] 内连接
来源：http://dali.jinghuilouyu.cn/Article/details/gtxudcwwcq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sxryk.cn/Article/details/gtoetrryde.html

[Q36] 左连接
来源：http://dali.shuidangran.top/Article/details/gtupifpbzr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.mhx1999.top/Article/details/gtvtbbjvby.html

[Q37] 右连接
来源：http://dali.zdqjudy.top/Article/details/gteydnonlj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hnqzz.top/Article/details/gtlqymocbp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.guowangkeji.top/Article/details/gtzccbfbvf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.meibo888.top/Article/details/gtfwotetnu.html

[Q39] 自连接（查上下级）
来源：http://dali.fzhhl.top/Article/details/gtqzowbdat.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yuxming.cn/Article/details/gttlpntyww.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jlsjyb.cn/Article/details/gtyqqbklmx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhiwuduotai.top/Article/details/gtqvukbbju.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jqgfzy.top/Article/details/gtsdyyvvkw.html

[Q41] 多表连接
来源：http://dali.nanxuanxn.top/Article/details/gtnlmblwkt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.andypj.xyz/Article/details/gtfrpqycgv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shzxlz.cn/Article/details/gtjbljggbl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sxryk.cn/Article/details/gttajdwpyz.html

[Q42] 连接条件附加过滤
来源：http://dali.snrcjt.cn/Article/details/gtfcnevhrk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zycfv.cn/Article/details/gtyunluwls.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ydzc1.top/Article/details/gtdeecbtqe.html

[Q43] 标量子查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvwdgrgmw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jiagoushi.top/Article/details/gtecaukbnb.html

[Q44] IN 子查询
来源：http://dali.cashguo.top/Article/details/gtefqfzcuf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.316326.xyz/Article/details/gtaxlvzzgc.html

[Q45] EXISTS 判断存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtedxnklio.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xinyue.icu/Article/details/gtajonvavk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hywenlv.cn/Article/details/gtxupzlvjm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pycfn.com/Article/details/gticinjezv.html

[Q47] 与平均值比较
来源：http://dali.sxryk.cn/Article/details/gtzzntuinw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ehwqpu.com/Article/details/gtuiyyueep.html

[Q48] CTE 公用表表达式
来源：http://dali.nwbrower.top/Article/details/gtzbqnzfhg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.0kj1m.cn/Article/details/gtvqecwcxl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jiagoushi.top/Article/details/gtkovbwhkw.html

[Q49] 更新单行
来源：http://dali.chenjidiqi.icu/Article/details/gthnnyzeej.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yanxiufei.cn/Article/details/gtaggkmwrw.html

[Q50] 批量更新
来源：http://dali.yonumen.top/Article/details/gtmzapyyft.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gtrnczbytb.html

[Q51] 用子查询更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtzzfqnxbx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtydmpwxpj.html

[Q52] 删除指定行
来源：http://dali.yongpay.top/Article/details/gtcssxpmkx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gtbanfqlfp.html

[Q53] 按条件删除
来源：http://dali.zhixingplan.top/Article/details/gtmbveffex.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gaohongyu789.top/Article/details/gtiiobgsll.html

[Q54] 清空表
来源：http://dali.jinqigfzy.top/Article/details/gtqaypaaut.html

TRUNCATE TABLE logs;
来源：http://dali.nanxuanxn.top/Article/details/gtuwuweyov.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gtcopsrfmk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hnqzz.top/Article/details/gtfchrwmjn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.9152youxi.cn/Article/details/gtjhbgbzxc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ydzc1.top/Article/details/gtprbttivm.html

[Q57] 行号
来源：http://dali.ppjwa.cn/Article/details/gthjsanrvr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtbkrfiudf.html

[Q58] 累计求和
来源：http://dali.jinqigufen.top/Article/details/gtysqcwyku.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtigtfcznf.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gtwiszlrol.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtbillqxtd.html

[Q60] 取上一行 / 下一行
来源：http://dali.yueranfly.top/Article/details/gtxqpkykxo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.bjfxy.top/Article/details/gtxnvjphcc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtznugcgee.html


<!-- 参考信息 -->