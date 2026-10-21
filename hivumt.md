代发 wailian999

Go:   // 手写递归
来源：http://dali.yj20258.top/Article/details/gtxofgwoef.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.0kj1m.cn/Article/details/gtckptpysv.html

C#:   // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gtcoknnaap.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cashguo.top/Article/details/gtuvtsxnkt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj202588.top/Article/details/gtpmzjvuam.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nanxinkj.top/Article/details/gtsbxdftei.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jianghu66.top/Article/details/gtnzaxacfx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sufxvd.cn/Article/details/gtxajjwqit.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgfzy.top/Article/details/gtpdqwtcwx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shuidangran.top/Article/details/gtiarqjkfa.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfykmmau.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgufenzy.top/Article/details/gtuhdmcfsb.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtzauybxgj.html

O. 并发与异步
来源：http://dali.zhixingplan.top/Article/details/gtuwonjeth.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtjtiineif.html

[O01] 启动一个线程
来源：http://dali.xuanzx.com/Article/details/gtjulvpfps.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.quarkkingdee.top/Article/details/gtrrevlnde.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sufxvd.cn/Article/details/gtjtapudkw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.c1oappe.top/Article/details/gtqhrfzqfl.html

TS:   // 同 JS
来源：http://dali.nanxuanxn.top/Article/details/gtxmmaybyf.html

Java: new Thread(() -> f()).start()
来源：http://dali.hnxiangtu.top/Article/details/gtsmtlkfdi.html

Go:   go f()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjwryyjgv.html

Ruby: Thread.new { f }
来源：http://dali.zhoulong.xyz/Article/details/gtqsdlnnqp.html

C#:   Task.Run(() => F());
来源：http://dali.316326.xyz/Article/details/gtztizturl.html

[O02] 使用线程池
来源：http://dali.cheryme.top/Article/details/gtprlpbgsa.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.daria6918.cn/Article/details/gtqbbfcmsd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.haohaochexian.top/Article/details/gtrahqytlc.html

JS:   // worker_threads 线程池
来源：http://dali.bjfxy.top/Article/details/gtxoojogjx.html

TS:   // worker_threads 线程池
来源：http://dali.redwolf501.top/Article/details/gturhvfovd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.fengsongda.top/Article/details/gtabbdkrth.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jlsjyb.cn/Article/details/gtnrggjngv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xuanzx.com/Article/details/gtcdczyfoa.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jqgufenzy.top/Article/details/gtyhmsvoiw.html

[O03] 加锁保护共享数据
来源：http://dali.snrcjt.cn/Article/details/gtstonnnjm.html

Py:   with lock: shared += 1
来源：http://dali.mhx1999.top/Article/details/gtwofabaqo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xziqi.cn/Article/details/gtifcuxbxx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jianghu66.top/Article/details/gtcuzhbbbv.html

TS:   // 同 JS
来源：http://dali.wangdashe.top/Article/details/gtgzdoqewp.html

Java: synchronized (this) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmroiavt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.kuanghao11.cn/Article/details/gtseozgldb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hnxiangtu.top/Article/details/gtcxrrbovz.html

C#:   lock (gate) { shared++; }
来源：http://dali.iojbl.cn/Article/details/gtkdwmqujw.html

[O04] 定义异步函数并等待
来源：http://dali.gogol.net.cn/Article/details/gttcakjwzl.html

Py:   async def f():⏎    await g()
来源：http://dali.cheryme.top/Article/details/gtodfcrvod.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.snrcjt.cn/Article/details/gtthtfrnhv.html

JS:   async function f() { await g(); }
来源：http://dali.ppjwa.cn/Article/details/gtsrowedbi.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtoivpczyc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.andypj.xyz/Article/details/gtcxwxyzds.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shanyushiyangtech.top/Article/details/gtuigjrrmj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xuetiantiany.cn/Article/details/gtrlklwgjr.html

C#:   async Task F() { await G(); }
来源：http://dali.chenlongwang.top/Article/details/gtchzxztqm.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenzaomai.com/Article/details/gtlbejusud.html

Py:   asyncio.gather(*tasks)
来源：http://dali.birdmap.top/Article/details/gtjfosygch.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yj202588.top/Article/details/gtpkfydpuw.html

JS:   await Promise.all(tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtyorsaqmq.html

TS:   await Promise.all(tasks)
来源：http://dali.hnqzz.top/Article/details/gtdtazgnkz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jiagoushi.top/Article/details/gtqxwueicf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jlsjyb.cn/Article/details/gtzovliqmw.html

Ruby: threads.map(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gtzbcygljd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sxryk.cn/Article/details/gtvwhtguln.html

[O06] 使用进程池
来源：http://dali.fzhhl.top/Article/details/gtrxgmnyab.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.pycfn.com/Article/details/gtanxxgpty.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shangyingyoupin.top/Article/details/gtihpdrqwu.html

JS:   // child_process / cluster 模块
来源：http://dali.xziqi.cn/Article/details/gtlvzxtrjj.html

TS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gtjticdfdq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.0kj1m.cn/Article/details/gthawqasqe.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhiwuduotai.top/Article/details/gthfhoomgb.html

Ruby: // fork 块
来源：http://dali.jqgufenzy.top/Article/details/gtdmicisvc.html

C#:   Parallel.For
来源：http://dali.zhongyouzk.top/Article/details/gtfkmqfgfa.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtskuxoowd.html

P. 常用工具函数
来源：http://dali.aibaodan.cn/Article/details/gtnhicthjx.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtqjekqpyn.html

[P01] 生成 UUID
来源：http://dali.ybcxt.top/Article/details/gtjddmmtdt.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gthopqbryd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.c1oappe.top/Article/details/gtpemapprq.html

JS:   crypto.randomUUID()
来源：http://dali.cashguo.top/Article/details/gtopcuglna.html

TS:   crypto.randomUUID()
来源：http://dali.shanyushiyangtech.top/Article/details/gteutqxgah.html

Java: UUID.randomUUID().toString()
来源：http://dali.aizwys.cn/Article/details/gtugtahqze.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tian-w.cn/Article/details/gtjcmgjgpw.html

Ruby: SecureRandom.uuid
来源：http://dali.tian-w.cn/Article/details/gttvwuayjj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinqigfzy.top/Article/details/gtiioorvtt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinqigfzy.top/Article/details/gtikaustcy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yongpay.top/Article/details/gtxszlhgag.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.daria6918.cn/Article/details/gtphrrntbt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xziqi.cn/Article/details/gtvlvuyygy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinghuilouyu.cn/Article/details/gtehdzjvoa.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ehwqpu.com/Article/details/gtxotlgtyr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.smart0.xyz/Article/details/gtcmvtbrzr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ivvv.top/Article/details/gttadklian.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cdnleiting.top/Article/details/gtgccqedyy.html

[P03] 生成短随机字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtyqsfcezl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nanxinkj.top/Article/details/gtrlfcoyww.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.fzhhl.top/Article/details/gtnwictmjm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gthewijfxx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.iojbl.cn/Article/details/gtqlbxkquq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.wangdashe.top/Article/details/gtdjxovrqp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sysykeji.top/Article/details/gtniwlygpm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.guannengcc.top/Article/details/gtyvtwjrge.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.wangdashe.top/Article/details/gtghavawzu.html

[P04] 求长度
来源：http://dali.guowangkeji.top/Article/details/gtttenglfh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xziqi.cn/Article/details/gtrhmvdbpk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvdrlvjft.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gtyugmjpza.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangtech.top/Article/details/gtcmphkgmg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jqgfzy.top/Article/details/gtfeoozdpk.html

Go:   len(arr);  len(m)
来源：http://dali.zhoulong.xyz/Article/details/gtlrqnweej.html

Ruby: x.length;  x.size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoidsiglc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyiopzcns.html

[P05] 判断两个对象内容是否相等
来源：http://dali.iojbl.cn/Article/details/gtqlxacixw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.daxiang520.top/Article/details/gteibaqrtk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yj202588.top/Article/details/gtasruqmob.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zycfv.cn/Article/details/gtleviewqp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.smart0.xyz/Article/details/gtzdxhlgyl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fzhhl.top/Article/details/gtmencuatj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.mhx1999.top/Article/details/gtpjcsppgl.html

Ruby: a == b
来源：http://dali.ppjwa.cn/Article/details/gtemfkndjp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hysaishi.cn/Article/details/gtgltmjzeg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.tianlin.xyz/Article/details/gtyjviqrlw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yonumen.top/Article/details/gtubgrlfbi.html

PHP:  if (empty($x)) {}
来源：http://dali.yvedp.cn/Article/details/gtawkycbfl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.iojbl.cn/Article/details/gtgsrezmha.html

TS:   if (x == null) {}
来源：http://dali.zhengqikj.top/Article/details/gtghjnreyw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sufxvd.cn/Article/details/gtjmdycwfv.html

Go:   if x == nil {}
来源：http://dali.haohaochexian.top/Article/details/gtpqvdnkrd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xuanzx.com/Article/details/gtaqnparsh.html

C#:   if (x is null) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtuhollgkt.html

[P07] 防抖与节流
来源：http://dali.yangfankeji.com/Article/details/gtiumzzcmu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.vqdsnc.cn/Article/details/gtsnkykulf.html

PHP:  // 手写时间戳比较
来源：http://dali.tian-w.cn/Article/details/gtubklobhm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cashguo.top/Article/details/gteggzknmh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuanzx.com/Article/details/gthooabkma.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zycfv.cn/Article/details/gtypizjutb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yanxiufei.cn/Article/details/gtddzdrlij.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sysykeji.top/Article/details/gtsfhlfpbg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shzxlz.cn/Article/details/gtyxixmqam.html

[P08] 处理浮点精度问题
来源：http://dali.ppjwa.cn/Article/details/gtcdtscjwa.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.daxiang520.top/Article/details/gtmxbvzyjd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hywenlv.cn/Article/details/gtkzlmpapc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.0kj1m.cn/Article/details/gtpumxtzdy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yj20258.top/Article/details/gtvyfjtyus.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sxryk.cn/Article/details/gtxqayazqw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuxming.cn/Article/details/gtsllfatcq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jianghu66.top/Article/details/gtgcsszben.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ivvv.top/Article/details/gtcsiycwjz.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtedeaqpdn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cashguo.top/Article/details/gttpzwaana.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtzksaflip.html

[Q01] 创建表
来源：http://dali.hnxiangtu.top/Article/details/gtbxegbbhy.html

CREATE TABLE users (
来源：http://dali.daria6918.cn/Article/details/gttfrmfwiy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.andypj.xyz/Article/details/gtgbdbtwjt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xylfe.cn/Article/details/gtvhcoulep.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cheryme.top/Article/details/gtwihcnedg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.daxiang520.top/Article/details/gtapdnhbil.html

);
来源：http://dali.yj20258888.top/Article/details/gtuwymhden.html

[Q02] 创建带外键的表
来源：http://dali.zhengqikj.top/Article/details/gtmjrqvrnm.html

CREATE TABLE orders (
来源：http://dali.cdnleiting.top/Article/details/gtggnmgdag.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jlsjyb.cn/Article/details/gtehxwtcnk.html

user_id INT NOT NULL,
来源：http://dali.daxiang520.top/Article/details/gtlpvwpgao.html

amount DECIMAL(10, 2),
来源：http://dali.aizwys.cn/Article/details/gttdeezdgm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.birdmap.top/Article/details/gtprwggerh.html

);
来源：http://dali.sufxvd.cn/Article/details/gtovlpveyz.html

[Q03] 增加列
来源：http://dali.sxryk.cn/Article/details/gtscdsoqty.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.redwolf501.top/Article/details/gtlmcuuxqs.html

[Q04] 修改列类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzmkoxthu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jqgufenzy.top/Article/details/gtwkojxzes.html

[Q05] 重命名列
来源：http://dali.ybcxt.top/Article/details/gtdyhujvkz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dashuyun.cn/Article/details/gterpvqknp.html

[Q06] 删除列
来源：http://dali.9152youxi.cn/Article/details/gtspkyqzye.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hnqzz.top/Article/details/gtofcteotq.html

[Q07] 删除表
来源：http://dali.tian-w.cn/Article/details/gtduzpruwq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ivvv.top/Article/details/gthssmgmly.html

[Q08] 创建普通索引
来源：http://dali.xuetiantiany.cn/Article/details/gtzcbyrfux.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.smart0.xyz/Article/details/gtidlvqodp.html

[Q09] 创建唯一索引
来源：http://dali.jiagoushi.top/Article/details/gthfclrihx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sysykeji.top/Article/details/gtelymjfob.html

[Q10] 插入单行
来源：http://dali.hammf.cn/Article/details/gtulfzqvhi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jiagoushi.top/Article/details/gtwgkmwbku.html

[Q11] 一次插入多行
来源：http://dali.zhengqikj.top/Article/details/gtezxszpoc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ybcxt.top/Article/details/gtamgjpjdk.html

[Q12] 插入后取自增 ID
来源：http://dali.guowangkeji.top/Article/details/gtmzzlrpch.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.daria6918.cn/Article/details/gtlfydwiyn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yueranfly.top/Article/details/gtrkrssoif.html

[Q13] 忽略重复插入
来源：http://dali.gzhubu.top/Article/details/gtnycnswcd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cqqwz.cn/Article/details/gtruwqhtba.html

[Q14] 存在则更新（upsert）
来源：http://dali.jlsjyb.cn/Article/details/gtlwlnywmz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xylfe.cn/Article/details/gtxvzpswnz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinqigfzy.top/Article/details/gtjzaqrdmp.html

[Q15] 查询全部
来源：http://dali.sweek.top/Article/details/gtkjemszzu.html

SELECT * FROM users;
来源：http://dali.c1oappe.top/Article/details/gtgcintnat.html

[Q16] 查询指定列
来源：http://dali.yanxiufei.cn/Article/details/gtgohjebae.html

SELECT id, name FROM users;
来源：http://dali.yvedp.cn/Article/details/gtbhvvikoj.html

[Q17] 条件查询
来源：http://dali.gotoacloud.top/Article/details/gtmuochdxk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sysykeji.top/Article/details/gtfaqouptj.html

[Q18] 模糊匹配
来源：http://dali.nwbrower.top/Article/details/gtuuldnckv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnabnzzue.html

[Q19] 范围查询
来源：http://dali.xylfe.cn/Article/details/gtqukxzepz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hammf.cn/Article/details/gttletvtkz.html

[Q20] IN 列表
来源：http://dali.pycfn.com/Article/details/gtjldrxjax.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtguubkvgu.html

[Q21] 空值判断
来源：http://dali.havefunace.top/Article/details/gtgmjfigtx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.fengsongda.top/Article/details/gtuvylgtvr.html

[Q22] 排序
来源：http://dali.yuxming.cn/Article/details/gtaoqtlhse.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.wangshuangyany.cn/Article/details/gtqgfzlodd.html

[Q23] 分页
来源：http://dali.cheryme.top/Article/details/gtrgfpxhqk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sxryk.cn/Article/details/gthqxnfmmc.html

[Q24] 去重
来源：http://dali.gzhubu.top/Article/details/gtnfbimvng.html

SELECT DISTINCT city FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtxqrtpjdh.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gtygdbmaup.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinyuanbaomall.cn/Article/details/gtecdfqwgg.html

[Q26] 计数
来源：http://dali.vqdsnc.cn/Article/details/gtjuasytoq.html

SELECT COUNT(*) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtdrsfctvd.html

[Q27] 条件计数
来源：http://dali.svipenyu.cn/Article/details/gtxztnbujv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtbawrkagq.html

[Q28] 求和与平均
来源：http://dali.0kj1m.cn/Article/details/gtymxkgzjw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yonumen.top/Article/details/gtleszmlyu.html

[Q29] 最大最小值
来源：http://dali.yueranfly.top/Article/details/gtipwpyuqg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtlgukljki.html

[Q30] 分组统计
来源：http://dali.0kj1m.cn/Article/details/gtqqdulczw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gtosftvnxh.html

[Q31] 分组后过滤
来源：http://dali.bjfxy.top/Article/details/gtjtysgvvr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xuanzx.com/Article/details/gtpbajeaiw.html

[Q32] 分组拼接字符串
来源：http://dali.yueranfly.top/Article/details/gtuapewdjo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gtkynhopca.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ehwqpu.com/Article/details/gtrerltgel.html

[Q33] 多列分组
来源：http://dali.yj20258888.top/Article/details/gtpheapbej.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gaohongyu789.top/Article/details/gtjiztweeg.html

[Q34] 每组取第一条
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvyjvplw.html

SELECT * FROM (
来源：http://dali.snrcjt.cn/Article/details/gtbbzmkvsq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.snrcjt.cn/Article/details/gtnallzbpu.html

) t WHERE rn = 1;
来源：http://dali.yonumen.top/Article/details/gtlxdkdaey.html

[Q35] 内连接
来源：http://dali.nanxinkj.top/Article/details/gtgucrodkf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ppjwa.cn/Article/details/gtzlxuagbn.html

[Q36] 左连接
来源：http://dali.sufxvd.cn/Article/details/gtiktofxwp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xylfe.cn/Article/details/gtudtyqrya.html

[Q37] 右连接
来源：http://dali.chenjidiqi.icu/Article/details/gtrrekamwx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xinyue.icu/Article/details/gtbapvpuzu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnxiangtu.top/Article/details/gtsxxijcui.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gotoacloud.top/Article/details/gteobzwvmx.html

[Q39] 自连接（查上下级）
来源：http://dali.zycfv.cn/Article/details/gtskvnumyw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cqqwz.cn/Article/details/gtmvzrqreg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xylfe.cn/Article/details/gtlvkpfwxy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gaohongyu789.top/Article/details/gtzdkfkhtn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nanxinkj.top/Article/details/gtiurvcyit.html

[Q41] 多表连接
来源：http://dali.cdnleiting.top/Article/details/gtllczmwlc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.fengsongda.top/Article/details/gtnhxuiyar.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhengqikj.top/Article/details/gtfcwgmqgn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sweek.top/Article/details/gtfckyhftv.html

[Q42] 连接条件附加过滤
来源：http://dali.jlsjyb.cn/Article/details/gtuonouqab.html

SELECT u.name, o.amount FROM users u
来源：http://dali.daria6918.cn/Article/details/gtybresjfy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdjfrwpdg.html

[Q43] 标量子查询
来源：http://dali.yonumen.top/Article/details/gthdzlvbvj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aizwys.cn/Article/details/gtasifisyw.html

[Q44] IN 子查询
来源：http://dali.chenjidiqi.icu/Article/details/gtupwvlhjf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xuanzx.com/Article/details/gtantkginq.html

[Q45] EXISTS 判断存在
来源：http://dali.cdnleiting.top/Article/details/gtpnphapws.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.snrcjt.cn/Article/details/gtmodtaucf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shangyingyoupin.top/Article/details/gtzayeeocg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yongpay.top/Article/details/gtnmsgvbub.html

[Q47] 与平均值比较
来源：http://dali.wangshuangyany.cn/Article/details/gtcovsfpwa.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenlongwang.top/Article/details/gtxjrioryo.html

[Q48] CTE 公用表表达式
来源：http://dali.yuanzhike.top/Article/details/gtqqufwbhg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jqgufenzy.top/Article/details/gtefbslfrn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.redwolf501.top/Article/details/gtgxftwiri.html

[Q49] 更新单行
来源：http://dali.sysykeji.top/Article/details/gtmjqcxhct.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.dashuyun.cn/Article/details/gtjffksxiz.html

[Q50] 批量更新
来源：http://dali.yuxming.cn/Article/details/gturqeyhhv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhongyouzk.top/Article/details/gtmfgahsys.html

[Q51] 用子查询更新
来源：http://dali.wangdashe.top/Article/details/gtzvkndqkt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhixingplan.top/Article/details/gtitgfoauk.html

[Q52] 删除指定行
来源：http://dali.zhixingplan.top/Article/details/gtusznywqo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gtdyicfqnd.html

[Q53] 按条件删除
来源：http://dali.jinqigufen.top/Article/details/gtztueaswa.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jianghu66.top/Article/details/gtrtgxxqei.html

[Q54] 清空表
来源：http://dali.ppjwa.cn/Article/details/gtoygxlnqv.html

TRUNCATE TABLE logs;
来源：http://dali.mhx1999.top/Article/details/gtlhueeacj.html

[Q55] 排名（并列占位）
来源：http://dali.aizwys.cn/Article/details/gtwthcbfmt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yj20258888.top/Article/details/gtoqqvajyb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jianghu66.top/Article/details/gtbrmctgyp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxinkj.top/Article/details/gtwmqfzafh.html

[Q57] 行号
来源：http://dali.0kj1m.cn/Article/details/gtzibhqetb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtxojhqsed.html

[Q58] 累计求和
来源：http://dali.hysaishi.cn/Article/details/gtuaqtkpir.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbymjona.html

[Q59] 分组内累计
来源：http://dali.smart0.xyz/Article/details/gtznxynpee.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtculjqmjj.html

[Q60] 取上一行 / 下一行
来源：http://dali.shanyushiyangtech.top/Article/details/gthmopvkcf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gotoacloud.top/Article/details/gtxzaozpko.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtfcsgjsog.html

[Q61] 移动平均
来源：http://dali.jlsjyb.cn/Article/details/gtbfxmbllv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtivdrxoss.html

[Q62] 分组占比
来源：http://dali.yj20258888.top/Article/details/gtshjocgxf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gtoiaecajr.html

[Q63] 开启事务
来源：http://dali.sufxvd.cn/Article/details/gttrouvvet.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xuetiantiany.cn/Article/details/gtjrqkjxcn.html

[Q64] 提交事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthukngnmw.html

COMMIT;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtatwixjdc.html

[Q65] 回滚事务
来源：http://dali.feifeiyinyue.top/Article/details/gttqvmzrxj.html

ROLLBACK;
来源：http://dali.xuetiantiany.cn/Article/details/gtdpfeftyk.html

[Q66] 行锁查询
来源：http://dali.ehwqpu.com/Article/details/gtfnbgtooc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.wangdashe.top/Article/details/gtkbfvjpwe.html


<!-- 参考信息 -->