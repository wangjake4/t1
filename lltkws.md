代发 wailian999

Java: new Thread(() -> f()).start()
来源：http://dali.jqgfzy.top/Article/details/gthqprccnk.html

Go:   go f()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtspkbuqii.html

Ruby: Thread.new { f }
来源：http://dali.yuxming.cn/Article/details/gtpoevbbih.html

C#:   Task.Run(() => F());
来源：http://dali.0kj1m.cn/Article/details/gtopvvmxrz.html

[O02] 使用线程池
来源：http://dali.quarkkingdee.top/Article/details/gtshrdylin.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xuanzx.com/Article/details/gtitwzsdff.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nanxinkj.top/Article/details/gtwaixohtx.html

JS:   // worker_threads 线程池
来源：http://dali.quarkkingdee.top/Article/details/gtkohmactq.html

TS:   // worker_threads 线程池
来源：http://dali.yonumen.top/Article/details/gtbzqvudhj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ydzc1.top/Article/details/gtebzkooao.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hongshengwenyu.top/Article/details/gtopggdffe.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cheryme.top/Article/details/gtpwruijyj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxfhpycak.html

[O03] 加锁保护共享数据
来源：http://dali.fengsongda.top/Article/details/gtcetacudg.html

Py:   with lock: shared += 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtoptcwfqf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cqqwz.cn/Article/details/gtgcuuhgfk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jianghu66.top/Article/details/gtzsvcobds.html

TS:   // 同 JS
来源：http://dali.hywenlv.cn/Article/details/gtpzeynbcz.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaschgxam.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnhheglz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhengqikj.top/Article/details/gtlihlgwqk.html

C#:   lock (gate) { shared++; }
来源：http://dali.aizwys.cn/Article/details/gtjlflhjuu.html

[O04] 定义异步函数并等待
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxnybfvf.html

Py:   async def f():⏎    await g()
来源：http://dali.yvedp.cn/Article/details/gtsboixbzo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.iojbl.cn/Article/details/gtmchmasxj.html

JS:   async function f() { await g(); }
来源：http://dali.jyoumei.cn/Article/details/gtbbhzvwky.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinqigufen.top/Article/details/gtxnocnkjg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.kuanghao11.cn/Article/details/gtfhpaybbf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj20258.top/Article/details/gthmzfzrng.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hywenlv.cn/Article/details/gtbmwcozov.html

C#:   async Task F() { await G(); }
来源：http://dali.yuxming.cn/Article/details/gtfkjfnyuq.html

[O05] 并发执行并等待全部完成
来源：http://dali.yonumen.top/Article/details/gtopvyldcr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnqzz.top/Article/details/gtbcmkqfdr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sufxvd.cn/Article/details/gtthqhtbdh.html

JS:   await Promise.all(tasks)
来源：http://dali.tian-w.cn/Article/details/gtuvsksjlf.html

TS:   await Promise.all(tasks)
来源：http://dali.ybcxt.top/Article/details/gtwklbarsz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ppjwa.cn/Article/details/gtfktgoldx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cashguo.top/Article/details/gtcutgcxbp.html

Ruby: threads.map(&:join)
来源：http://dali.yj20258.top/Article/details/gtcpvniqsv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.quarkkingdee.top/Article/details/gtlnxnirpo.html

[O06] 使用进程池
来源：http://dali.nanxuanxn.top/Article/details/gtigiyqkqt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhengqikj.top/Article/details/gtamsnspbv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.pycfn.com/Article/details/gtipbtbvrk.html

JS:   // child_process / cluster 模块
来源：http://dali.gogol.net.cn/Article/details/gtgkbnkiaa.html

TS:   // child_process / cluster 模块
来源：http://dali.xuanzx.com/Article/details/gtkonapakh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gtuqazbnyc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shzxlz.cn/Article/details/gtisifsllm.html

Ruby: // fork 块
来源：http://dali.chenzaomai.com/Article/details/gtbhqfbman.html

C#:   Parallel.For
来源：http://dali.cqqwz.cn/Article/details/gtlvjbepus.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtkkbrnhno.html

P. 常用工具函数
来源：http://dali.nanxinkj.top/Article/details/gtzunrovxe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtpmkmecww.html

[P01] 生成 UUID
来源：http://dali.dashuyun.cn/Article/details/gtmczqrhiv.html

Py:   str(uuid.uuid4())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwwzvixea.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.0kj1m.cn/Article/details/gtfyitxfwk.html

JS:   crypto.randomUUID()
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbmkxpno.html

TS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcztjueie.html

Java: UUID.randomUUID().toString()
来源：http://dali.redwolf501.top/Article/details/gtnbnavkey.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nwbrower.top/Article/details/gthbslvcuo.html

Ruby: SecureRandom.uuid
来源：http://dali.xuetiantiany.cn/Article/details/gtpvfwumxd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xinyue.icu/Article/details/gtdegsylqq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gzhubu.top/Article/details/gtvcaxoynv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.aizwys.cn/Article/details/gtuxdwuyzq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hnxiangtu.top/Article/details/gtyvncpzle.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.dianchejie.cn/Article/details/gtduqtyvrf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.wangdashe.top/Article/details/gtajavljbc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gogol.net.cn/Article/details/gtzggvfisu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.iojbl.cn/Article/details/gtofxsbzke.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zdqjudy.top/Article/details/gtzwconbyn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yueranfly.top/Article/details/gtiedldzes.html

[P03] 生成短随机字符串
来源：http://dali.gzhubu.top/Article/details/gtxylcdudx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhixingplan.top/Article/details/gtxktpbibn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ehwqpu.com/Article/details/gthszbxmvm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhengqikj.top/Article/details/gtusovpvng.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.meibo888.top/Article/details/gtnqttvhlt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yangfankeji.com/Article/details/gtsmusgskr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nwbrower.top/Article/details/gtmgfszikh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.feifeiyinyue.top/Article/details/gtphnkrvbj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.guannengcc.top/Article/details/gtrnsrldpp.html

[P04] 求长度
来源：http://dali.havefunace.top/Article/details/gtkbxnpfdb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yangfankeji.com/Article/details/gtpuasdbbv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtywleokjc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gtonhradfy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yangfankeji.com/Article/details/gtfqurpgds.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cqqwz.cn/Article/details/gtczvzdqio.html

Go:   len(arr);  len(m)
来源：http://dali.yueranfly.top/Article/details/gtgrzucdxj.html

Ruby: x.length;  x.size
来源：http://dali.snrcjt.cn/Article/details/gtcbtbatuw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.c1oappe.top/Article/details/gteuojiwhs.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zycfv.cn/Article/details/gtnywwptuo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yangfankeji.com/Article/details/gtvejipqxx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhiwuduotai.top/Article/details/gtwyrewpqs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.smart0.xyz/Article/details/gtdcqgsunx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xylfe.cn/Article/details/gtdrhpfrfh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jianghu66.top/Article/details/gttrwzpsib.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gthmwnukly.html

Ruby: a == b
来源：http://dali.daria6918.cn/Article/details/gtvsuzafkr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenzaomai.com/Article/details/gtzkhmydhf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gogol.net.cn/Article/details/gthkvcgbqn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhengqikj.top/Article/details/gtegshwgjk.html

PHP:  if (empty($x)) {}
来源：http://dali.bjfxy.top/Article/details/gtujlgsxgs.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.birdmap.top/Article/details/gthhdqxtmn.html

TS:   if (x == null) {}
来源：http://dali.cucudq.cn/Article/details/gteinnclpu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtgecepzzq.html

Go:   if x == nil {}
来源：http://dali.sweek.top/Article/details/gtxjigmnpx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.fengsongda.top/Article/details/gtxlwgyeex.html

C#:   if (x is null) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gteykeeifc.html

[P07] 防抖与节流
来源：http://dali.wangshuangyany.cn/Article/details/gtqxdfygwf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cqqwz.cn/Article/details/gtdjvllfii.html

PHP:  // 手写时间戳比较
来源：http://dali.guowangkeji.top/Article/details/gtgpsskjtu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gtpexilirz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ehwqpu.com/Article/details/gtdzvknorr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shuidangran.top/Article/details/gtcccfaseu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.mhx1999.top/Article/details/gttydxzawn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.chenzaomai.com/Article/details/gtbddcmkfv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj202588.top/Article/details/gtpiagpknc.html

[P08] 处理浮点精度问题
来源：http://dali.jlsjyb.cn/Article/details/gtryxnwwwj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.andypj.xyz/Article/details/gtekgcucay.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.iojbl.cn/Article/details/gtwmlghkmr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gzhubu.top/Article/details/gtytmhxxqp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.dianchejie.cn/Article/details/gtrjypzdbn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.c1oappe.top/Article/details/gtzmtnefat.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nanxuanxn.top/Article/details/gtjycinoyk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhiwuduotai.top/Article/details/gtbmutpyma.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.guannengcc.top/Article/details/gtxempznbj.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtrbmkccmm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sxryk.cn/Article/details/gtkvsjrbov.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtkuhbhoix.html

[Q01] 创建表
来源：http://dali.yuanzhike.top/Article/details/gtfhnpkuwp.html

CREATE TABLE users (
来源：http://dali.jqgufenzy.top/Article/details/gtlkdgsfeu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jiagoushi.top/Article/details/gtjwscyfpp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.fzhhl.top/Article/details/gtitkyjmqk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.havefunace.top/Article/details/gtiezpkstk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zdqjudy.top/Article/details/gtwspfltxm.html

);
来源：http://dali.hammf.cn/Article/details/gtvlyucbdg.html

[Q02] 创建带外键的表
来源：http://dali.chenlongwang.top/Article/details/gtuhqoxzez.html

CREATE TABLE orders (
来源：http://dali.gaohongyu789.top/Article/details/gtztuhnvmd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.feifeiyinyue.top/Article/details/gtjdcihkmu.html

user_id INT NOT NULL,
来源：http://dali.hywenlv.cn/Article/details/gtvzalwvuh.html

amount DECIMAL(10, 2),
来源：http://dali.chenzaomai.com/Article/details/gtdhvudnyo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hnqzz.top/Article/details/gtbfuvvmmx.html

);
来源：http://dali.tian-w.cn/Article/details/gttvnxyodq.html

[Q03] 增加列
来源：http://dali.zhiwuduotai.top/Article/details/gtvxohbjos.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zycfv.cn/Article/details/gtapdymnpb.html

[Q04] 修改列类型
来源：http://dali.yuanzhike.top/Article/details/gtdjkaafgb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sysykeji.top/Article/details/gthyfmrxkj.html

[Q05] 重命名列
来源：http://dali.aibaodan.cn/Article/details/gtujtsvmke.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yuxming.cn/Article/details/gtxbphqfbl.html

[Q06] 删除列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuufbqpmx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinqigufen.top/Article/details/gtxoaptein.html

[Q07] 删除表
来源：http://dali.vqdsnc.cn/Article/details/gtdexnvxtm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yvedp.cn/Article/details/gtoyowvloc.html

[Q08] 创建普通索引
来源：http://dali.gzhubu.top/Article/details/gtdeypgntu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.havefunace.top/Article/details/gtdvzraepa.html

[Q09] 创建唯一索引
来源：http://dali.zhongyouzk.top/Article/details/gtcsmqydxr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhengqikj.top/Article/details/gtypnlibau.html

[Q10] 插入单行
来源：http://dali.smart0.xyz/Article/details/gttuaiinqt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jyoumei.cn/Article/details/gteljqxkoz.html

[Q11] 一次插入多行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsyfevjko.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxvwmxee.html

[Q12] 插入后取自增 ID
来源：http://dali.zhoulong.xyz/Article/details/gtfyjpoiow.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tian-w.cn/Article/details/gtaenibkmq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jqgfzy.top/Article/details/gtegzmleob.html

[Q13] 忽略重复插入
来源：http://dali.chenlongwang.top/Article/details/gtotqkjsio.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenjidiqi.icu/Article/details/gtrhxffaoc.html

[Q14] 存在则更新（upsert）
来源：http://dali.yuxming.cn/Article/details/gtqdngcfkf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cdnleiting.top/Article/details/gtvewzdqlp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xziqi.cn/Article/details/gtvnqdqzlo.html

[Q15] 查询全部
来源：http://dali.meibo888.top/Article/details/gtzftxcwrs.html

SELECT * FROM users;
来源：http://dali.meibo888.top/Article/details/gttyzfgbdh.html

[Q16] 查询指定列
来源：http://dali.zhixingplan.top/Article/details/gtckeihnfz.html

SELECT id, name FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtpfmlimba.html

[Q17] 条件查询
来源：http://dali.tanke756.top/Article/details/gtmgbzyfhw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtwjegbwoa.html

[Q18] 模糊匹配
来源：http://dali.cucudq.cn/Article/details/gtxrlqzykj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zdqjudy.top/Article/details/gtbmxmtrdt.html

[Q19] 范围查询
来源：http://dali.kuanghao11.cn/Article/details/gtagcnxpow.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gotoacloud.top/Article/details/gtjszcnbdx.html

[Q20] IN 列表
来源：http://dali.jianghu66.top/Article/details/gtgpvzzrkb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtxdjlozun.html

[Q21] 空值判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtajqhjfei.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.daxiang520.top/Article/details/gtcviiqiwm.html

[Q22] 排序
来源：http://dali.tanke756.top/Article/details/gtrlfqihnq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.316326.xyz/Article/details/gtwcuhvrcs.html

[Q23] 分页
来源：http://dali.iojbl.cn/Article/details/gthbwnxuut.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gaohongyu789.top/Article/details/gtiqbjvqqg.html

[Q24] 去重
来源：http://dali.zhixingplan.top/Article/details/gtiwhzzydl.html

SELECT DISTINCT city FROM users;
来源：http://dali.sysykeji.top/Article/details/gtgjuviogd.html

[Q25] 只取前 N 条
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyunluyka.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.pengpengdd.cyou/Article/details/gtkhenlsrl.html

[Q26] 计数
来源：http://dali.snrcjt.cn/Article/details/gtuqrcdocp.html

SELECT COUNT(*) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkupetxfc.html

[Q27] 条件计数
来源：http://dali.ehwqpu.com/Article/details/gtlssyqhxo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gogol.net.cn/Article/details/gteaisafxj.html

[Q28] 求和与平均
来源：http://dali.zhengqikj.top/Article/details/gtofpxgahz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtbupuscnd.html

[Q29] 最大最小值
来源：http://dali.pycfn.com/Article/details/gtmztmbcwf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtuvzmhisg.html

[Q30] 分组统计
来源：http://dali.mhx1999.top/Article/details/gtguaodxuq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gtqoaxkcvi.html

[Q31] 分组后过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmurwuvpr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tianlin.xyz/Article/details/gtxwrusvdv.html

[Q32] 分组拼接字符串
来源：http://dali.tian-w.cn/Article/details/gtfgcqbaqd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gttrkodlfx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yuxming.cn/Article/details/gtihchdmkm.html

[Q33] 多列分组
来源：http://dali.shuidangran.top/Article/details/gtydhjyjlf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sysykeji.top/Article/details/gtdkrqvfyc.html

[Q34] 每组取第一条
来源：http://dali.tianlin.xyz/Article/details/gtnkntjopt.html

SELECT * FROM (
来源：http://dali.chenzaomai.com/Article/details/gtqxfqovva.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zdqjudy.top/Article/details/gtzijiqljq.html

) t WHERE rn = 1;
来源：http://dali.cdnleiting.top/Article/details/gtqqbicluv.html

[Q35] 内连接
来源：http://dali.ybcxt.top/Article/details/gtpydcmzlg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jyoumei.cn/Article/details/gtkduncmbd.html

[Q36] 左连接
来源：http://dali.xziqi.cn/Article/details/gtjxjkzdqe.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jyoumei.cn/Article/details/gtiikltsbe.html

[Q37] 右连接
来源：http://dali.dashuyun.cn/Article/details/gtxacggnxu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sxryk.cn/Article/details/gthoxdmlqv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jianghu66.top/Article/details/gtjlcgtgzd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tian-w.cn/Article/details/gtdjwajjbe.html

[Q39] 自连接（查上下级）
来源：http://dali.yanxiufei.cn/Article/details/gtkedvwnrh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yvedp.cn/Article/details/gtnyxvinjk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenlongwang.top/Article/details/gtzhjtirow.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jyoumei.cn/Article/details/gtyugejwzd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.birdmap.top/Article/details/gtejejswwp.html

[Q41] 多表连接
来源：http://dali.ppjwa.cn/Article/details/gtamngrcmr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhixingplan.top/Article/details/gtltjovccz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.tian-w.cn/Article/details/gtjshytbke.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jyoumei.cn/Article/details/gtacbmldxw.html

[Q42] 连接条件附加过滤
来源：http://dali.hysaishi.cn/Article/details/gtdeolzvej.html

SELECT u.name, o.amount FROM users u
来源：http://dali.c1oappe.top/Article/details/gtxougdgcv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cqqwz.cn/Article/details/gteijvjqaf.html

[Q43] 标量子查询
来源：http://dali.yueranfly.top/Article/details/gtpuhrnqqz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.316326.xyz/Article/details/gtfedbzwkw.html

[Q44] IN 子查询
来源：http://dali.hfpthk.cn/Article/details/gtwlkutakp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwcafrpb.html

[Q45] EXISTS 判断存在
来源：http://dali.hammf.cn/Article/details/gtkjxotvbx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tian-w.cn/Article/details/gtsidjqgov.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yongpay.top/Article/details/gtzedisteo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pengpengdd.cyou/Article/details/gtmrmcbzqd.html

[Q47] 与平均值比较
来源：http://dali.sufxvd.cn/Article/details/gtdqrbvdla.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.pycfn.com/Article/details/gtnikjadcx.html

[Q48] CTE 公用表表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtdmcptfjh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.quarkkingdee.top/Article/details/gtjkdhllsc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.bjfxy.top/Article/details/gtlidswasz.html

[Q49] 更新单行
来源：http://dali.mhx1999.top/Article/details/gtyyoeuigk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hysaishi.cn/Article/details/gtuvhgrqgf.html

[Q50] 批量更新
来源：http://dali.tian-w.cn/Article/details/gtntwluxqb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.daxiang520.top/Article/details/gtvduwnajp.html

[Q51] 用子查询更新
来源：http://dali.shzxlz.cn/Article/details/gtuzcyerpq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhixingplan.top/Article/details/gttrakalqv.html

[Q52] 删除指定行
来源：http://dali.cucudq.cn/Article/details/gtmpkwvmge.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbduibwrq.html

[Q53] 按条件删除
来源：http://dali.0kj1m.cn/Article/details/gtzxzjhanl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhijdrxd.html

[Q54] 清空表
来源：http://dali.havefunace.top/Article/details/gtegryqzfv.html

TRUNCATE TABLE logs;
来源：http://dali.ivvv.top/Article/details/gtijjblcaf.html

[Q55] 排名（并列占位）
来源：http://dali.havefunace.top/Article/details/gtbaavyenj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sysykeji.top/Article/details/gtwisfbbnx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xuetiantiany.cn/Article/details/gtmnrgceln.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.pycfn.com/Article/details/gtelhubkdp.html

[Q57] 行号
来源：http://dali.jianghu66.top/Article/details/gtugwqnees.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtivtojfad.html

[Q58] 累计求和
来源：http://dali.0kj1m.cn/Article/details/gtqddwhwff.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtpqjethmd.html

[Q59] 分组内累计
来源：http://dali.yongpay.top/Article/details/gtechktykz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtjxqyblxz.html

[Q60] 取上一行 / 下一行
来源：http://dali.nanxuanxn.top/Article/details/gtwoxtbowb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gogol.net.cn/Article/details/gtfnuqsmcn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtsvzrtcjc.html

[Q61] 移动平均
来源：http://dali.bjfxy.top/Article/details/gtnhktwqgw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gthlraytss.html

[Q62] 分组占比
来源：http://dali.shangyingyoupin.top/Article/details/gtxprxghno.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gtqbqttsqi.html

[Q63] 开启事务
来源：http://dali.dianchejie.cn/Article/details/gtiqfjuqoa.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuhewsrmp.html

[Q64] 提交事务
来源：http://dali.quarkkingdee.top/Article/details/gttfnapkwy.html

COMMIT;
来源：http://dali.hysaishi.cn/Article/details/gthyskpdod.html

[Q65] 回滚事务
来源：http://dali.guowangkeji.top/Article/details/gtfnuihylp.html

ROLLBACK;
来源：http://dali.havefunace.top/Article/details/gtwfyakfgr.html

[Q66] 行锁查询
来源：http://dali.iojbl.cn/Article/details/gtksfqyhkq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.redwolf501.top/Article/details/gtbfoipjih.html

[Q67] 设置隔离级别
来源：http://dali.cqqwz.cn/Article/details/gtpwgootao.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zycfv.cn/Article/details/gtxmfsjvyq.html

[Q68] 保存点
来源：http://dali.hfpthk.cn/Article/details/gtautrxtsq.html

SAVEPOINT sp1;
来源：http://dali.hywenlv.cn/Article/details/gtsqzqemgz.html

ROLLBACK TO sp1;
来源：http://dali.sysykeji.top/Article/details/gtyqlfudne.html

[Q69] 查看执行计划
来源：http://dali.yvedp.cn/Article/details/gtyzsixvbq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.dashuyun.cn/Article/details/gtkkytjaof.html

[Q70] 更新统计信息
来源：http://dali.hfpthk.cn/Article/details/gtcxekvmrt.html

ANALYZE TABLE users;
来源：http://dali.tanke756.top/Article/details/gtjobawfow.html

[Q71] 查看建表语句
来源：http://dali.dianchejie.cn/Article/details/gtfdvtjlee.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.pycfn.com/Article/details/gtlrdrwqyk.html

[Q72] 查看索引
来源：http://dali.shuidangran.top/Article/details/gthmftzcvf.html

SHOW INDEX FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtfcegavig.html

[Q73] 查看表状态
来源：http://dali.birdmap.top/Article/details/gtqohnpvuz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sxryk.cn/Article/details/gtmdjsloom.html

[Q74] 强制使用索引
来源：http://dali.smart0.xyz/Article/details/gtpfmxijwr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.havefunace.top/Article/details/gtvtlqbgqj.html

[Q75] 日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gtohrkvoln.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtczneoatm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.aibaodan.cn/Article/details/gtvefeejth.html


<!-- 参考信息 -->