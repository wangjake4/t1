代发 wailian999

Java: new Thread(() -> f()).start()
来源：http://dali.bjfxy.top/Article/details/gtcdsbhjwu.html

Go:   go f()
来源：http://dali.meibo888.top/Article/details/gtazokhkqc.html

Ruby: Thread.new { f }
来源：http://dali.nwbrower.top/Article/details/gtfqfysqus.html

C#:   Task.Run(() => F());
来源：http://dali.ehwqpu.com/Article/details/gtyykodkab.html

[O02] 使用线程池
来源：http://dali.ivvv.top/Article/details/gthasvxqzh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.svipenyu.cn/Article/details/gtjkgmlkwy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.haohaochexian.top/Article/details/gtwpptgode.html

JS:   // worker_threads 线程池
来源：http://dali.dianchejie.cn/Article/details/gtgqjoqwim.html

TS:   // worker_threads 线程池
来源：http://dali.tianlin.xyz/Article/details/gtcueeoabd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yuanzhike.top/Article/details/gtnrldqowr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yvedp.cn/Article/details/gtwreiqsdo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.mhx1999.top/Article/details/gttgdjookn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jqgufenzy.top/Article/details/gtsvymdoyg.html

[O03] 加锁保护共享数据
来源：http://dali.quarkkingdee.top/Article/details/gtrjrqbger.html

Py:   with lock: shared += 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtcemsiocd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.daxiang520.top/Article/details/gtxggqmfxu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cucudq.cn/Article/details/gtjqljrepn.html

TS:   // 同 JS
来源：http://dali.xylfe.cn/Article/details/gtyudibbiw.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbufcgadi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nwbrower.top/Article/details/gtzdgufpqp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.daxiang520.top/Article/details/gtbcotewld.html

C#:   lock (gate) { shared++; }
来源：http://dali.guowangkeji.top/Article/details/gttxamtbww.html

[O04] 定义异步函数并等待
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxuebwvpw.html

Py:   async def f():⏎    await g()
来源：http://dali.316326.xyz/Article/details/gtozabbjka.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.meibo888.top/Article/details/gtlpxcjyhx.html

JS:   async function f() { await g(); }
来源：http://dali.birdmap.top/Article/details/gtgpjimbtx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtsbjwhjci.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.meibo888.top/Article/details/gtrjtwrxpl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.andypj.xyz/Article/details/gtiijwbphx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zdqjudy.top/Article/details/gttewnmqwl.html

C#:   async Task F() { await G(); }
来源：http://dali.haohaochexian.top/Article/details/gtdzkrmqhz.html

[O05] 并发执行并等待全部完成
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtudvdbneu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jiagoushi.top/Article/details/gtvwewdkom.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shanyushiyangtech.top/Article/details/gtbeiebqkp.html

JS:   await Promise.all(tasks)
来源：http://dali.jqgufenzy.top/Article/details/gtxudrgwlt.html

TS:   await Promise.all(tasks)
来源：http://dali.jyoumei.cn/Article/details/gtmkwcqfst.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.andypj.xyz/Article/details/gtxiqnfgam.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.fengsongda.top/Article/details/gtmisoltyx.html

Ruby: threads.map(&:join)
来源：http://dali.chenzaomai.com/Article/details/gtqopxwczk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yvedp.cn/Article/details/gtfvkjkwif.html

[O06] 使用进程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhlpjnvl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.wangdashe.top/Article/details/gtzojtvhbm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.smart0.xyz/Article/details/gtgnastmzx.html

JS:   // child_process / cluster 模块
来源：http://dali.wangdashe.top/Article/details/gtliotvnln.html

TS:   // child_process / cluster 模块
来源：http://dali.havefunace.top/Article/details/gtpqkmmsvr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhengqikj.top/Article/details/gtmxltxdkj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jiagoushi.top/Article/details/gtkqeqnrqh.html

Ruby: // fork 块
来源：http://dali.xuetiantiany.cn/Article/details/gtfyuhocjv.html

C#:   Parallel.For
来源：http://dali.yuxming.cn/Article/details/gtrgzloxwt.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtqctjvjyt.html

P. 常用工具函数
来源：http://dali.jinghuilouyu.cn/Article/details/gteaiwkiwa.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtqmwdrosq.html

[P01] 生成 UUID
来源：http://dali.cheryme.top/Article/details/gtkvklumih.html

Py:   str(uuid.uuid4())
来源：http://dali.yanxiufei.cn/Article/details/gtifspdhht.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.guowangkeji.top/Article/details/gtuekbkeyd.html

JS:   crypto.randomUUID()
来源：http://dali.jqgufenzy.top/Article/details/gttzhojaxn.html

TS:   crypto.randomUUID()
来源：http://dali.cashguo.top/Article/details/gtnqzbfnni.html

Java: UUID.randomUUID().toString()
来源：http://dali.ydzc1.top/Article/details/gtwnihyvlq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.fzhhl.top/Article/details/gtqkjsevbs.html

Ruby: SecureRandom.uuid
来源：http://dali.shangyingyoupin.top/Article/details/gtqodwtozu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.fzhhl.top/Article/details/gtuqoekmkx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.svipenyu.cn/Article/details/gtfzkdpjxv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jianghu66.top/Article/details/gtuswirkla.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ybcxt.top/Article/details/gtsthqjqws.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yueranfly.top/Article/details/gtthpuyqys.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.9152youxi.cn/Article/details/gthcpbptjl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hysaishi.cn/Article/details/gtteyyfimn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhiwuduotai.top/Article/details/gtzsrtvyke.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.daxiang520.top/Article/details/gtcndabpyh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ehwqpu.com/Article/details/gtldncrjst.html

[P03] 生成短随机字符串
来源：http://dali.jiagoushi.top/Article/details/gtqccgihkw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gogol.net.cn/Article/details/gtcfcosium.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.316326.xyz/Article/details/gtcsmlsqba.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fzhhl.top/Article/details/gtolosgpvv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gtrfmfhljz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhongyouzk.top/Article/details/gtgevsgfug.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.guannengcc.top/Article/details/gtwdjhkhhm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.c1oappe.top/Article/details/gtvyziwydj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ppjwa.cn/Article/details/gtimsolbhm.html

[P04] 求长度
来源：http://dali.aibaodan.cn/Article/details/gtskokarqq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.snrcjt.cn/Article/details/gtzqehytcm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtnodgrkhn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.andypj.xyz/Article/details/gtogaumjza.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ppjwa.cn/Article/details/gtwhzblttz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tian-w.cn/Article/details/gtzmwkirav.html

Go:   len(arr);  len(m)
来源：http://dali.sweek.top/Article/details/gtksdvrbvs.html

Ruby: x.length;  x.size
来源：http://dali.jqgfzy.top/Article/details/gtghdksvcp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yvedp.cn/Article/details/gtqkzoipxc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tianlin.xyz/Article/details/gtmfdayuet.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cqqwz.cn/Article/details/gtjxzoaslg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhixingplan.top/Article/details/gtjhszivqd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gtiyxxqbmw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tanke756.top/Article/details/gtpyytwvpp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.9152youxi.cn/Article/details/gtuuxcpixd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xuanzx.com/Article/details/gtdgqsuhgs.html

Ruby: a == b
来源：http://dali.zycfv.cn/Article/details/gtfygvsizn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hfpthk.cn/Article/details/gtodvzyasn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.andypj.xyz/Article/details/gttrtdufzn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.dianchejie.cn/Article/details/gtttmnafqt.html

PHP:  if (empty($x)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtelpxyxlj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhixingplan.top/Article/details/gtbxqxmubg.html

TS:   if (x == null) {}
来源：http://dali.316326.xyz/Article/details/gtvnnjphta.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sysykeji.top/Article/details/gtjszqnglf.html

Go:   if x == nil {}
来源：http://dali.hfpthk.cn/Article/details/gtokxtefbt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hnxiangtu.top/Article/details/gtxwhonmpd.html

C#:   if (x is null) {}
来源：http://dali.yj20258888.top/Article/details/gtnekeqhar.html

[P07] 防抖与节流
来源：http://dali.yvedp.cn/Article/details/gtrsrnjgay.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jlsjyb.cn/Article/details/gtxcabcatu.html

PHP:  // 手写时间戳比较
来源：http://dali.cdnleiting.top/Article/details/gttlbpgggb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhixingplan.top/Article/details/gtahyeqodq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.316326.xyz/Article/details/gtvnofqpto.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj202588.top/Article/details/gtwibljjwu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.c1oappe.top/Article/details/gtrhnajkhh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.meibo888.top/Article/details/gtabpruwdl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.pengpengdd.cyou/Article/details/gtsfdlvjro.html

[P08] 处理浮点精度问题
来源：http://dali.gzhubu.top/Article/details/gtdaexwnne.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fengsongda.top/Article/details/gtpxfxfqdr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yvedp.cn/Article/details/gtrovlklei.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.pycfn.com/Article/details/gtfvsukyjh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.wangdashe.top/Article/details/gtcyptaahq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhiwuduotai.top/Article/details/gtslnxttwt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.smart0.xyz/Article/details/gtjkgogzpw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhixingplan.top/Article/details/gtslclocrc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuisfvzck.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtgogyfdjj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.nanxinkj.top/Article/details/gtcxhfdqwi.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtuwykrykm.html

[Q01] 创建表
来源：http://dali.havefunace.top/Article/details/gtykpstydk.html

CREATE TABLE users (
来源：http://dali.jianghu66.top/Article/details/gtwfpkyyil.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ybcxt.top/Article/details/gthmsedwxz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cucudq.cn/Article/details/gtnqoxnyxv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwqjqhhyj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gaohongyu789.top/Article/details/gtapylvigs.html

);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuisblbqy.html

[Q02] 创建带外键的表
来源：http://dali.bjfxy.top/Article/details/gtwekhsnyi.html

CREATE TABLE orders (
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsdskplek.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhiwuduotai.top/Article/details/gtcqftgcum.html

user_id INT NOT NULL,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfsmawoly.html

amount DECIMAL(10, 2),
来源：http://dali.birdmap.top/Article/details/gtycvjucsn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jlsjyb.cn/Article/details/gtxajhtlcr.html

);
来源：http://dali.haohaochexian.top/Article/details/gtivuadikl.html

[Q03] 增加列
来源：http://dali.fengsongda.top/Article/details/gtgjkeeisl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xziqi.cn/Article/details/gthmdhkrpl.html

[Q04] 修改列类型
来源：http://dali.sufxvd.cn/Article/details/gthuznamnw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrzmfvogv.html

[Q05] 重命名列
来源：http://dali.0kj1m.cn/Article/details/gtssldjqna.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhixingplan.top/Article/details/gtywbxtvpt.html

[Q06] 删除列
来源：http://dali.yuxming.cn/Article/details/gtlpyausxf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hywenlv.cn/Article/details/gtsbvyffpm.html

[Q07] 删除表
来源：http://dali.pycfn.com/Article/details/gtzygebkko.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtygkvabgb.html

[Q08] 创建普通索引
来源：http://dali.dashuyun.cn/Article/details/gtvcvldxbq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.9152youxi.cn/Article/details/gtbcbllott.html

[Q09] 创建唯一索引
来源：http://dali.feifeiyinyue.top/Article/details/gtynndctim.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.pycfn.com/Article/details/gtwdkcvtrm.html

[Q10] 插入单行
来源：http://dali.cashguo.top/Article/details/gtcwzxzgon.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cdnleiting.top/Article/details/gtjbbqxsoy.html

[Q11] 一次插入多行
来源：http://dali.jinqigufen.top/Article/details/gtdeagmpxn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtblqyzuvp.html

[Q12] 插入后取自增 ID
来源：http://dali.ydzc1.top/Article/details/gtrpfeqahr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.andypj.xyz/Article/details/gtkxulpqtd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xinyue.icu/Article/details/gttcwuepow.html

[Q13] 忽略重复插入
来源：http://dali.jinqigufen.top/Article/details/gtybgoarbp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jianghu66.top/Article/details/gtpmvcctzs.html

[Q14] 存在则更新（upsert）
来源：http://dali.yuxming.cn/Article/details/gtffqbnary.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.fzhhl.top/Article/details/gtsmldsjto.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zdqjudy.top/Article/details/gtsvwnjuxi.html

[Q15] 查询全部
来源：http://dali.zycfv.cn/Article/details/gtaocnelon.html

SELECT * FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtnepubqha.html

[Q16] 查询指定列
来源：http://dali.yueranfly.top/Article/details/gtgclihnxn.html

SELECT id, name FROM users;
来源：http://dali.fengsongda.top/Article/details/gtqzuhaufq.html

[Q17] 条件查询
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxonofas.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yvedp.cn/Article/details/gtdqbmdqtp.html

[Q18] 模糊匹配
来源：http://dali.quarkkingdee.top/Article/details/gtdlpkrgzc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yuanzhike.top/Article/details/gtkuknicbx.html

[Q19] 范围查询
来源：http://dali.tianlin.xyz/Article/details/gtgnhnbvph.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hammf.cn/Article/details/gtzrwkrcye.html

[Q20] IN 列表
来源：http://dali.yonumen.top/Article/details/gtmubjyjny.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgsvyssjc.html

[Q21] 空值判断
来源：http://dali.hongshengwenyu.top/Article/details/gtgptjxjpr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.feifeiyinyue.top/Article/details/gtvxtajrxp.html

[Q22] 排序
来源：http://dali.yuxming.cn/Article/details/gtwaqixxzm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xuanzx.com/Article/details/gtszyuycqg.html

[Q23] 分页
来源：http://dali.quarkkingdee.top/Article/details/gtvevxdshn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yuxming.cn/Article/details/gtyujjkxpy.html

[Q24] 去重
来源：http://dali.cucudq.cn/Article/details/gtbmzuyeoz.html

SELECT DISTINCT city FROM users;
来源：http://dali.tian-w.cn/Article/details/gtmmianygb.html

[Q25] 只取前 N 条
来源：http://dali.quarkkingdee.top/Article/details/gtwerbjdup.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.0kj1m.cn/Article/details/gtvadfgufy.html

[Q26] 计数
来源：http://dali.yueranfly.top/Article/details/gtpyvhepkq.html

SELECT COUNT(*) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtsshijdyy.html

[Q27] 条件计数
来源：http://dali.xylfe.cn/Article/details/gtezoafmjt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtsrzpyrld.html

[Q28] 求和与平均
来源：http://dali.shanyushiyangtech.top/Article/details/gtdinrneho.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtqascxnyw.html

[Q29] 最大最小值
来源：http://dali.wangshuangyany.cn/Article/details/gtlehviuli.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtnkypqbyj.html

[Q30] 分组统计
来源：http://dali.ppjwa.cn/Article/details/gtgtdftcqt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gtysvonyyj.html

[Q31] 分组后过滤
来源：http://dali.chenzaomai.com/Article/details/gtgbtbvmjr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj20258888.top/Article/details/gtbaxpbmnr.html

[Q32] 分组拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gtednzwmnr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gtizwqbmyb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.guowangkeji.top/Article/details/gtkeasxtan.html

[Q33] 多列分组
来源：http://dali.hysaishi.cn/Article/details/gtfzavcdjk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.daria6918.cn/Article/details/gtcascbvtm.html

[Q34] 每组取第一条
来源：http://dali.c1oappe.top/Article/details/gtbguwmglr.html

SELECT * FROM (
来源：http://dali.yj20258888.top/Article/details/gtgupvdxme.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhongyouzk.top/Article/details/gtfchageon.html

) t WHERE rn = 1;
来源：http://dali.sweek.top/Article/details/gtureuqqon.html

[Q35] 内连接
来源：http://dali.smart0.xyz/Article/details/gtevnsnioi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwocbdywf.html

[Q36] 左连接
来源：http://dali.ivvv.top/Article/details/gtlcutkxnw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhoulong.xyz/Article/details/gtwzesigwd.html

[Q37] 右连接
来源：http://dali.pycfn.com/Article/details/gtqtyscims.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinqigfzy.top/Article/details/gtsvdgjisw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.wangshuangyany.cn/Article/details/gtbgcsnevt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ivvv.top/Article/details/gtlzolrbmw.html

[Q39] 自连接（查上下级）
来源：http://dali.havefunace.top/Article/details/gtjsujspcp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nanxinkj.top/Article/details/gtaqcndtit.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.iojbl.cn/Article/details/gtgsiuaveb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xziqi.cn/Article/details/gtysjgrhdn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.andypj.xyz/Article/details/gtkbdeofqj.html

[Q41] 多表连接
来源：http://dali.smart0.xyz/Article/details/gtuqstahdr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xziqi.cn/Article/details/gtvdtpgfqe.html

JOIN users u ON u.id = o.user_id
来源：http://dali.guannengcc.top/Article/details/gtqdrmapdf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvfzqflvw.html

[Q42] 连接条件附加过滤
来源：http://dali.dianchejie.cn/Article/details/gttrnmpxqo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cheryme.top/Article/details/gtptdabnqw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ybcxt.top/Article/details/gtscgdkxtk.html

[Q43] 标量子查询
来源：http://dali.sufxvd.cn/Article/details/gtdhhjbbcc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yvedp.cn/Article/details/gtascmxibr.html

[Q44] IN 子查询
来源：http://dali.fengsongda.top/Article/details/gtbxelkxbr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xziqi.cn/Article/details/gtrywsjwop.html

[Q45] EXISTS 判断存在
来源：http://dali.jinqigfzy.top/Article/details/gtkfivmfdd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgfzy.top/Article/details/gtjsgcispb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.pengpengdd.cyou/Article/details/gtuvqmvucw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhixingplan.top/Article/details/gtwoubugnu.html

[Q47] 与平均值比较
来源：http://dali.yueranfly.top/Article/details/gtyipwcvpd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nwbrower.top/Article/details/gtadfknzlg.html

[Q48] CTE 公用表表达式
来源：http://dali.iojbl.cn/Article/details/gtozypdbir.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhoulong.xyz/Article/details/gtovbtokem.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.dashuyun.cn/Article/details/gthtzhhkze.html

[Q49] 更新单行
来源：http://dali.haohaochexian.top/Article/details/gtgkmadaxe.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cucudq.cn/Article/details/gtimywjgib.html

[Q50] 批量更新
来源：http://dali.zycfv.cn/Article/details/gtxsusnuza.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.daria6918.cn/Article/details/gtqvnpoqtx.html

[Q51] 用子查询更新
来源：http://dali.jianghu66.top/Article/details/gteerkqtmi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtzwhrnhfx.html

[Q52] 删除指定行
来源：http://dali.vqdsnc.cn/Article/details/gtkebqbfer.html

DELETE FROM users WHERE id = 10;
来源：http://dali.pycfn.com/Article/details/gtodyfbsto.html

[Q53] 按条件删除
来源：http://dali.cashguo.top/Article/details/gtkjbumkuo.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.quarkkingdee.top/Article/details/gtvfdawudq.html

[Q54] 清空表
来源：http://dali.aizwys.cn/Article/details/gtiadceebt.html

TRUNCATE TABLE logs;
来源：http://dali.xylfe.cn/Article/details/gtdvkboxug.html

[Q55] 排名（并列占位）
来源：http://dali.guannengcc.top/Article/details/gtckfiegcd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xuetiantiany.cn/Article/details/gthxdmuecf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.316326.xyz/Article/details/gtdnpjdovi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xuetiantiany.cn/Article/details/gtunwhuuds.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gtpfsykfvg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtcrrhayxg.html

[Q58] 累计求和
来源：http://dali.ppjwa.cn/Article/details/gtanwosyiu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtqfcolhij.html

[Q59] 分组内累计
来源：http://dali.xuetiantiany.cn/Article/details/gtkngkmyre.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtwaykimwh.html

[Q60] 取上一行 / 下一行
来源：http://dali.aibaodan.cn/Article/details/gtgccxadby.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yj202588.top/Article/details/gtieoorypw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtmshtezxe.html

[Q61] 移动平均
来源：http://dali.cdnleiting.top/Article/details/gtgmvlphlf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtuczatvpm.html

[Q62] 分组占比
来源：http://dali.jyoumei.cn/Article/details/gtqhclfvco.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.redwolf501.top/Article/details/gtedppmcza.html

[Q63] 开启事务
来源：http://dali.feifeiyinyue.top/Article/details/gtzmrkhmky.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hnqzz.top/Article/details/gtszjrkfrb.html

[Q64] 提交事务
来源：http://dali.chenzaomai.com/Article/details/gtcegocubz.html

COMMIT;
来源：http://dali.gzhubu.top/Article/details/gtjxtvoggh.html

[Q65] 回滚事务
来源：http://dali.sufxvd.cn/Article/details/gtrhkvhcck.html

ROLLBACK;
来源：http://dali.dianchejie.cn/Article/details/gtngcdzwpq.html

[Q66] 行锁查询
来源：http://dali.chenzaomai.com/Article/details/gtxoowqmrd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.snrcjt.cn/Article/details/gthmdxwnyi.html

[Q67] 设置隔离级别
来源：http://dali.zdqjudy.top/Article/details/gtrvevyepf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.daxiang520.top/Article/details/gtljypiars.html

[Q68] 保存点
来源：http://dali.hnqzz.top/Article/details/gtyvdlvqpb.html

SAVEPOINT sp1;
来源：http://dali.jiagoushi.top/Article/details/gtedloshee.html

ROLLBACK TO sp1;
来源：http://dali.chenjidiqi.icu/Article/details/gtzubdoobz.html

[Q69] 查看执行计划
来源：http://dali.yvedp.cn/Article/details/gtogvacxed.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbafhhfvc.html

[Q70] 更新统计信息
来源：http://dali.ppjwa.cn/Article/details/gtuxanrxst.html

ANALYZE TABLE users;
来源：http://dali.yongpay.top/Article/details/gtvdsimitt.html

[Q71] 查看建表语句
来源：http://dali.xuetiantiany.cn/Article/details/gtrxnkcvdt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yanxiufei.cn/Article/details/gtwzcdtjrm.html

[Q72] 查看索引
来源：http://dali.yj20258888.top/Article/details/gthonrsqyk.html

SHOW INDEX FROM users;
来源：http://dali.cheryme.top/Article/details/gtkiuzhogr.html

[Q73] 查看表状态
来源：http://dali.tian-w.cn/Article/details/gtvuunvcam.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cdnleiting.top/Article/details/gtlstchexy.html

[Q74] 强制使用索引
来源：http://dali.redwolf501.top/Article/details/gtbetuakzz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nwbrower.top/Article/details/gtyojcgcgq.html

[Q75] 日期格式化
来源：http://dali.dashuyun.cn/Article/details/gtkjfnougc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtarvqfydw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jqgfzy.top/Article/details/gtnbjlnhau.html


<!-- 参考信息 -->