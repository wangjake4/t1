代发 wailian999

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuanzx.com/Article/details/gtnnjyugzw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yongpay.top/Article/details/gtwtvzhfoo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gtcomezvcb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhiwuduotai.top/Article/details/gtxsnorgfm.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtnfpkyrzn.html

O. 并发与异步
来源：http://dali.fzhhl.top/Article/details/gtyvohwdhg.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtnfgyccfv.html

[O01] 启动一个线程
来源：http://dali.jinqigufen.top/Article/details/gtkroyrcxx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhoulong.xyz/Article/details/gtsgvxzdxl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.316326.xyz/Article/details/gtwyuepncu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nanxuanxn.top/Article/details/gtmgtwngep.html

TS:   // 同 JS
来源：http://dali.quarkkingdee.top/Article/details/gtxqzcqwhn.html

Java: new Thread(() -> f()).start()
来源：http://dali.svipenyu.cn/Article/details/gtltsobovu.html

Go:   go f()
来源：http://dali.nanxuanxn.top/Article/details/gtpnxzbaco.html

Ruby: Thread.new { f }
来源：http://dali.hongshengwenyu.top/Article/details/gtmdtajlau.html

C#:   Task.Run(() => F());
来源：http://dali.sweek.top/Article/details/gtuoxprldr.html

[O02] 使用线程池
来源：http://dali.yangfankeji.com/Article/details/gteqgqqucc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shuidangran.top/Article/details/gtteicstdx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.tian-w.cn/Article/details/gtzrkumzmf.html

JS:   // worker_threads 线程池
来源：http://dali.cheryme.top/Article/details/gtjcbffzsv.html

TS:   // worker_threads 线程池
来源：http://dali.tianlin.xyz/Article/details/gtrzwidvxb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yuanzhike.top/Article/details/gtpeojeavd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xuetiantiany.cn/Article/details/gtkoflluvy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.fengsongda.top/Article/details/gtxyqlonfe.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xylfe.cn/Article/details/gtxijsrgpv.html

[O03] 加锁保护共享数据
来源：http://dali.zhiwuduotai.top/Article/details/gtyppecgua.html

Py:   with lock: shared += 1
来源：http://dali.sxryk.cn/Article/details/gtexrfighy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.pengpengdd.cyou/Article/details/gtutyllzmi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.snrcjt.cn/Article/details/gtvbwuaonw.html

TS:   // 同 JS
来源：http://dali.xylfe.cn/Article/details/gtaywvvsrl.html

Java: synchronized (this) { shared++; }
来源：http://dali.jqgufenzy.top/Article/details/gtzdnychdo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodiwohto.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jlsjyb.cn/Article/details/gtvfkynctp.html

C#:   lock (gate) { shared++; }
来源：http://dali.dianchejie.cn/Article/details/gtjyapvnwc.html

[O04] 定义异步函数并等待
来源：http://dali.chenzaomai.com/Article/details/gtplupmwaj.html

Py:   async def f():⏎    await g()
来源：http://dali.bjfxy.top/Article/details/gtmlsdaqjq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.mhx1999.top/Article/details/gtkwlprguj.html

JS:   async function f() { await g(); }
来源：http://dali.hysaishi.cn/Article/details/gtygmvvhhg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj20258.top/Article/details/gtnpvzbdqn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.smart0.xyz/Article/details/gtmqmvpidf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinyuanbaomall.cn/Article/details/gtajrxbwub.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.quarkkingdee.top/Article/details/gtaljleohj.html

C#:   async Task F() { await G(); }
来源：http://dali.jinqigufen.top/Article/details/gtsdexkqln.html

[O05] 并发执行并等待全部完成
来源：http://dali.svipenyu.cn/Article/details/gtgvsfoshj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmapousws.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.tanke756.top/Article/details/gtsgujjnjb.html

JS:   await Promise.all(tasks)
来源：http://dali.gotoacloud.top/Article/details/gtsfrifqtn.html

TS:   await Promise.all(tasks)
来源：http://dali.yonumen.top/Article/details/gtwdegvpjo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqfwiecq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zdqjudy.top/Article/details/gtxdmoqezj.html

Ruby: threads.map(&:join)
来源：http://dali.sysykeji.top/Article/details/gtcuudvgqi.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fengsongda.top/Article/details/gtpvxqaiex.html

[O06] 使用进程池
来源：http://dali.tanke756.top/Article/details/gtegmhsedo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gaohongyu789.top/Article/details/gtqpyyatbl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.wangshuangyany.cn/Article/details/gtprnhcodd.html

JS:   // child_process / cluster 模块
来源：http://dali.tian-w.cn/Article/details/gtuxekoqar.html

TS:   // child_process / cluster 模块
来源：http://dali.hnqzz.top/Article/details/gtpoucxvjs.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.nwbrower.top/Article/details/gtubskxmlr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinghuilouyu.cn/Article/details/gtybevshpu.html

Ruby: // fork 块
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbfqtzhi.html

C#:   Parallel.For
来源：http://dali.wangdashe.top/Article/details/gtxbrgxqdm.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtplnzpmqj.html

P. 常用工具函数
来源：http://dali.hywenlv.cn/Article/details/gteleiejbv.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtrcniihlw.html

[P01] 生成 UUID
来源：http://dali.hammf.cn/Article/details/gtqeyyndxw.html

Py:   str(uuid.uuid4())
来源：http://dali.cheryme.top/Article/details/gtpeuqjean.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.wangdashe.top/Article/details/gtyrdsqrwt.html

JS:   crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gtebdlcatk.html

TS:   crypto.randomUUID()
来源：http://dali.dianchejie.cn/Article/details/gtxnxjhmvi.html

Java: UUID.randomUUID().toString()
来源：http://dali.andypj.xyz/Article/details/gtaxslyvyh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cashguo.top/Article/details/gtgqfcjrpo.html

Ruby: SecureRandom.uuid
来源：http://dali.yvedp.cn/Article/details/gtapczcnnw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xuanzx.com/Article/details/gtfwxndrnv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.c1oappe.top/Article/details/gtpjtsgbbw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhixingplan.top/Article/details/gteuhyppip.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ehwqpu.com/Article/details/gtmmdjhgqa.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xylfe.cn/Article/details/gtotfmaqrd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jqgufenzy.top/Article/details/gtmubkqxmr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenlongwang.top/Article/details/gtibjjmseg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nwbrower.top/Article/details/gtailvcdtg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.mhx1999.top/Article/details/gtmacqxxaf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xylfe.cn/Article/details/gttpyjttrf.html

[P03] 生成短随机字符串
来源：http://dali.haohaochexian.top/Article/details/gtzxedqwqe.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.dianchejie.cn/Article/details/gtdoagfosp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hywenlv.cn/Article/details/gtiwogxwtc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tanke756.top/Article/details/gtpjhyhyev.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtwjmhfgev.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nanxinkj.top/Article/details/gtcbqrfjev.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yongpay.top/Article/details/gtnjmooiuo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.pengpengdd.cyou/Article/details/gtzbuurvqb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yuanzhike.top/Article/details/gtmehxwslw.html

[P04] 求长度
来源：http://dali.zhoulong.xyz/Article/details/gttopbiytc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gtmxpncdej.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gtdidcuikz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gtgxmcxmzm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tanke756.top/Article/details/gtfdvkznld.html

Java: list.size();  map.size();  s.length()
来源：http://dali.dianchejie.cn/Article/details/gtfxwcloux.html

Go:   len(arr);  len(m)
来源：http://dali.zhiwuduotai.top/Article/details/gtybdtozoc.html

Ruby: x.length;  x.size
来源：http://dali.gotoacloud.top/Article/details/gtllffscpd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sxryk.cn/Article/details/gtzxdxlfze.html

[P05] 判断两个对象内容是否相等
来源：http://dali.andypj.xyz/Article/details/gtzxzdtvok.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yanxiufei.cn/Article/details/gtsvwhrcst.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nwbrower.top/Article/details/gtetwbhwrx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ivvv.top/Article/details/gtlsgonlth.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sysykeji.top/Article/details/gtnemupmuq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.nwbrower.top/Article/details/gtitjjabur.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zycfv.cn/Article/details/gtlinqltdp.html

Ruby: a == b
来源：http://dali.9152youxi.cn/Article/details/gtmaujzlsp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tanke756.top/Article/details/gtmaznqxjr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xuetiantiany.cn/Article/details/gtqthlbbln.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ppjwa.cn/Article/details/gtojtliddq.html

PHP:  if (empty($x)) {}
来源：http://dali.ehwqpu.com/Article/details/gttnobohlb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.feifeiyinyue.top/Article/details/gthyfbnppt.html

TS:   if (x == null) {}
来源：http://dali.316326.xyz/Article/details/gtpzfinywl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hammf.cn/Article/details/gtzchtytsv.html

Go:   if x == nil {}
来源：http://dali.zhongyouzk.top/Article/details/gteilheseg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.redwolf501.top/Article/details/gtzqpawvnk.html

C#:   if (x is null) {}
来源：http://dali.aizwys.cn/Article/details/gtwmyhhzfz.html

[P07] 防抖与节流
来源：http://dali.yanxiufei.cn/Article/details/gtcleahbji.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhengqikj.top/Article/details/gtqdihfmsn.html

PHP:  // 手写时间戳比较
来源：http://dali.daxiang520.top/Article/details/gtbzajsjnr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jyoumei.cn/Article/details/gtjfdbhngb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gtgyaescxn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cashguo.top/Article/details/gtjmeuvukp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.guowangkeji.top/Article/details/gtbvcynzbh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gogol.net.cn/Article/details/gtsmpekuig.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hnqzz.top/Article/details/gtgzwfoldq.html

[P08] 处理浮点精度问题
来源：http://dali.yonumen.top/Article/details/gtoqssjinv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jqgfzy.top/Article/details/gtirlgkpvd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtasjksppq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.316326.xyz/Article/details/gtqrwwlibt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.meibo888.top/Article/details/gtlfjtxddb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.aizwys.cn/Article/details/gtxkxndiog.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xylfe.cn/Article/details/gtotxoozih.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.9152youxi.cn/Article/details/gtbypsaweu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ybcxt.top/Article/details/gtasufftcs.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtybzcebgd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yonumen.top/Article/details/gtpmisonjp.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtrdggkbkb.html

[Q01] 创建表
来源：http://dali.dianchejie.cn/Article/details/gtuvfipmpy.html

CREATE TABLE users (
来源：http://dali.tianlin.xyz/Article/details/gtwrlwzfcb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenjidiqi.icu/Article/details/gtojtmkfew.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gzhubu.top/Article/details/gtchycxtof.html

email VARCHAR(100) UNIQUE,
来源：http://dali.c1oappe.top/Article/details/gtgshwokqp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gtbibhzuji.html

);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtycmqriyp.html

[Q02] 创建带外键的表
来源：http://dali.yuanzhike.top/Article/details/gthderkqyo.html

CREATE TABLE orders (
来源：http://dali.gogol.net.cn/Article/details/gtaozrpigp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gtsmhqmspi.html

user_id INT NOT NULL,
来源：http://dali.daxiang520.top/Article/details/gtuwztneho.html

amount DECIMAL(10, 2),
来源：http://dali.jinqigfzy.top/Article/details/gthdfplnuk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nanxinkj.top/Article/details/gthcrtrvlu.html

);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdboagdrr.html

[Q03] 增加列
来源：http://dali.yueranfly.top/Article/details/gtxneplqtk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cheryme.top/Article/details/gtxpssnrrb.html

[Q04] 修改列类型
来源：http://dali.xinyue.icu/Article/details/gtzyxylqzk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcshprykg.html

[Q05] 重命名列
来源：http://dali.andypj.xyz/Article/details/gtmzilxnja.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinqigufen.top/Article/details/gtdljwnprs.html

[Q06] 删除列
来源：http://dali.zycfv.cn/Article/details/gtytaiplju.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ydzc1.top/Article/details/gtappvorfp.html

[Q07] 删除表
来源：http://dali.daxiang520.top/Article/details/gtozvfghzb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.fzhhl.top/Article/details/gtlwxppsvo.html

[Q08] 创建普通索引
来源：http://dali.cdnleiting.top/Article/details/gtjkldshul.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gtjqscmrsr.html

[Q09] 创建唯一索引
来源：http://dali.hnqzz.top/Article/details/gtodxfiyva.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.snrcjt.cn/Article/details/gtxgnnhogw.html

[Q10] 插入单行
来源：http://dali.sxryk.cn/Article/details/gtghfxdqrh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sufxvd.cn/Article/details/gtpgmiscvn.html

[Q11] 一次插入多行
来源：http://dali.gzhubu.top/Article/details/gtgopapyap.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gtozwizhsl.html

[Q12] 插入后取自增 ID
来源：http://dali.gotoacloud.top/Article/details/gtmeibrslr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.316326.xyz/Article/details/gtaxgchvot.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tanke756.top/Article/details/gtokcyvamk.html

[Q13] 忽略重复插入
来源：http://dali.pycfn.com/Article/details/gtoorukibx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.smart0.xyz/Article/details/gtcrnusquz.html

[Q14] 存在则更新（upsert）
来源：http://dali.cheryme.top/Article/details/gtvpoauhqz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jiagoushi.top/Article/details/gtogeissdl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cucudq.cn/Article/details/gtkmngqkrr.html

[Q15] 查询全部
来源：http://dali.jiagoushi.top/Article/details/gtqhnwzpvi.html

SELECT * FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtpnpsyddu.html

[Q16] 查询指定列
来源：http://dali.gotoacloud.top/Article/details/gtjbpajsei.html

SELECT id, name FROM users;
来源：http://dali.tian-w.cn/Article/details/gtieviyvtf.html

[Q17] 条件查询
来源：http://dali.nwbrower.top/Article/details/gtfkebgonm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.0kj1m.cn/Article/details/gtotgcuaig.html

[Q18] 模糊匹配
来源：http://dali.tanke756.top/Article/details/gtcbgeydwc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yvedp.cn/Article/details/gtscrcaffz.html

[Q19] 范围查询
来源：http://dali.jinghuilouyu.cn/Article/details/gtlapquehd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenzaomai.com/Article/details/gttssjbkfe.html

[Q20] IN 列表
来源：http://dali.yueranfly.top/Article/details/gtyvkkzxip.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tianlin.xyz/Article/details/gtyzrczrbb.html

[Q21] 空值判断
来源：http://dali.daxiang520.top/Article/details/gtjandtzdh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ydzc1.top/Article/details/gthtedqjuk.html

[Q22] 排序
来源：http://dali.cqqwz.cn/Article/details/gteucpsyab.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xuetiantiany.cn/Article/details/gtmtexamem.html

[Q23] 分页
来源：http://dali.birdmap.top/Article/details/gtgreatcfm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tianlin.xyz/Article/details/gttnsoexnq.html

[Q24] 去重
来源：http://dali.jyoumei.cn/Article/details/gtbmgojizp.html

SELECT DISTINCT city FROM users;
来源：http://dali.redwolf501.top/Article/details/gtchkzteyr.html

[Q25] 只取前 N 条
来源：http://dali.snrcjt.cn/Article/details/gtqqwgxlds.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xylfe.cn/Article/details/gttvjservr.html

[Q26] 计数
来源：http://dali.jinqigufen.top/Article/details/gtprhbpuzf.html

SELECT COUNT(*) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtrjgtvkyz.html

[Q27] 条件计数
来源：http://dali.zhixingplan.top/Article/details/gtlmlblaov.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtkjewftmi.html

[Q28] 求和与平均
来源：http://dali.zhengqikj.top/Article/details/gtnkdcvpxp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtswhokiqp.html

[Q29] 最大最小值
来源：http://dali.316326.xyz/Article/details/gtxeazufqm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtefhbcifz.html

[Q30] 分组统计
来源：http://dali.sysykeji.top/Article/details/gtmqcokbwx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujiowhwa.html

[Q31] 分组后过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxtuujfnj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.vqdsnc.cn/Article/details/gtxwpqdfhy.html

[Q32] 分组拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gteecmebyp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gtqucxrskb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtshhehyje.html

[Q33] 多列分组
来源：http://dali.guannengcc.top/Article/details/gtxdzqwywa.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ydzc1.top/Article/details/gtkqaifkhq.html

[Q34] 每组取第一条
来源：http://dali.xuanzx.com/Article/details/gtrzekxxcv.html

SELECT * FROM (
来源：http://dali.dashuyun.cn/Article/details/gtghfytwkd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yj20258888.top/Article/details/gtspszirfq.html

) t WHERE rn = 1;
来源：http://dali.hywenlv.cn/Article/details/gtiowpfrcx.html

[Q35] 内连接
来源：http://dali.chenlongwang.top/Article/details/gtskjeoonz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.mhx1999.top/Article/details/gtieiazvvg.html

[Q36] 左连接
来源：http://dali.iojbl.cn/Article/details/gtvywozays.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigfzy.top/Article/details/gtygogfeec.html

[Q37] 右连接
来源：http://dali.ybcxt.top/Article/details/gtrawypzgq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.9152youxi.cn/Article/details/gtwxrafkqb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnqzz.top/Article/details/gtjuyetxpr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yangfankeji.com/Article/details/gthtdezgpx.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gtuioxvjqq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nwbrower.top/Article/details/gtnujzhbzj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.meibo888.top/Article/details/gtdjjgwvxx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jlsjyb.cn/Article/details/gtxwatgahr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzmdpqjui.html

[Q41] 多表连接
来源：http://dali.9152youxi.cn/Article/details/gtcwrkagyb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cashguo.top/Article/details/gtznsbomgk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zdqjudy.top/Article/details/gtznjswukb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ydzc1.top/Article/details/gtpizbyohv.html

[Q42] 连接条件附加过滤
来源：http://dali.zhongyouzk.top/Article/details/gtdqybxxho.html

SELECT u.name, o.amount FROM users u
来源：http://dali.quarkkingdee.top/Article/details/gtufivjtrg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nanxinkj.top/Article/details/gtuzegnpdc.html

[Q43] 标量子查询
来源：http://dali.svipenyu.cn/Article/details/gtuxkbhgwd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.wangshuangyany.cn/Article/details/gtsebsgyhi.html

[Q44] IN 子查询
来源：http://dali.chenjidiqi.icu/Article/details/gtmpwrwfjr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nwbrower.top/Article/details/gtbunwzrmd.html

[Q45] EXISTS 判断存在
来源：http://dali.tianlin.xyz/Article/details/gtzfkqnjwa.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cucudq.cn/Article/details/gtbzxppaxm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gotoacloud.top/Article/details/gtfmmdgpee.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dianchejie.cn/Article/details/gtlhnchhdb.html

[Q47] 与平均值比较
来源：http://dali.yuanzhike.top/Article/details/gtskwzdneo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenlongwang.top/Article/details/gttbxxtdlb.html

[Q48] CTE 公用表表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gtvyycgnen.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yvedp.cn/Article/details/gtequrfagf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nanxinkj.top/Article/details/gtegacdtol.html

[Q49] 更新单行
来源：http://dali.pengpengdd.cyou/Article/details/gtpuffttki.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hysaishi.cn/Article/details/gtpanhhrlo.html

[Q50] 批量更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtosozgllw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yongpay.top/Article/details/gtdmmuplny.html

[Q51] 用子查询更新
来源：http://dali.xinyue.icu/Article/details/gtcndacfzm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zycfv.cn/Article/details/gtiaobmtco.html

[Q52] 删除指定行
来源：http://dali.316326.xyz/Article/details/gtzdlhgizs.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajqwmbzx.html

[Q53] 按条件删除
来源：http://dali.smart0.xyz/Article/details/gthqmxedii.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.pengpengdd.cyou/Article/details/gtmrakcxpp.html

[Q54] 清空表
来源：http://dali.fengsongda.top/Article/details/gtfvozjhch.html

TRUNCATE TABLE logs;
来源：http://dali.c1oappe.top/Article/details/gtmvtinkka.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gtsufgmogt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.wangdashe.top/Article/details/gtjsojvvrr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.0kj1m.cn/Article/details/gtagskaazr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xylfe.cn/Article/details/gtowdgoxlg.html

[Q57] 行号
来源：http://dali.hnxiangtu.top/Article/details/gtctcmiufq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqdfwjdu.html

[Q58] 累计求和
来源：http://dali.316326.xyz/Article/details/gtzoftgjdh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtbratfjdd.html

[Q59] 分组内累计
来源：http://dali.chenjidiqi.icu/Article/details/gtdxywykrp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtrpkjyooj.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gtieerhdwf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.pycfn.com/Article/details/gtjwvtjqaw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ybcxt.top/Article/details/gttcdynkxt.html

[Q61] 移动平均
来源：http://dali.jiagoushi.top/Article/details/gtfgsferzz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtidbmopwa.html

[Q62] 分组占比
来源：http://dali.aibaodan.cn/Article/details/gtuiztjsyp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcnzlwnth.html

[Q63] 开启事务
来源：http://dali.meibo888.top/Article/details/gtycuawhmv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhengqikj.top/Article/details/gtaowmwinc.html

[Q64] 提交事务
来源：http://dali.316326.xyz/Article/details/gtwiwjrkhs.html

COMMIT;
来源：http://dali.tanke756.top/Article/details/gtkudlnozs.html

[Q65] 回滚事务
来源：http://dali.cheryme.top/Article/details/gtaicusobv.html

ROLLBACK;
来源：http://dali.nanxinkj.top/Article/details/gtyfbkperg.html

[Q66] 行锁查询
来源：http://dali.zhongyouzk.top/Article/details/gtjwudtjyd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yvedp.cn/Article/details/gtjiwveene.html

[Q67] 设置隔离级别
来源：http://dali.gotoacloud.top/Article/details/gtbqyvsrdx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yangfankeji.com/Article/details/gtfbagcspn.html

[Q68] 保存点
来源：http://dali.cqqwz.cn/Article/details/gtzytzxdah.html

SAVEPOINT sp1;
来源：http://dali.yvedp.cn/Article/details/gtaizwaqif.html

ROLLBACK TO sp1;
来源：http://dali.aibaodan.cn/Article/details/gtwqnifqda.html

[Q69] 查看执行计划
来源：http://dali.pycfn.com/Article/details/gtqzenvrnu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cashguo.top/Article/details/gttputscsy.html

[Q70] 更新统计信息
来源：http://dali.c1oappe.top/Article/details/gtceoaonby.html


<!-- 参考信息 -->