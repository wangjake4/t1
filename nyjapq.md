代发 wailian999

TS:   // worker_threads 线程池
来源：http://dali.xuanzx.com/Article/details/gtgujdousf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.birdmap.top/Article/details/gtnupzfvtn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gtjqmjcsyd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhiwuduotai.top/Article/details/gtsstdgoio.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gzhubu.top/Article/details/gtmsbbpgsz.html

[O03] 加锁保护共享数据
来源：http://dali.daria6918.cn/Article/details/gtjgwkkxco.html

Py:   with lock: shared += 1
来源：http://dali.aizwys.cn/Article/details/gtnretrzgp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.andypj.xyz/Article/details/gtatnpfonr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jlsjyb.cn/Article/details/gtslggfcwx.html

TS:   // 同 JS
来源：http://dali.jqgfzy.top/Article/details/gtlnulrsay.html

Java: synchronized (this) { shared++; }
来源：http://dali.sweek.top/Article/details/gtavnskpol.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tanke756.top/Article/details/gtvaozverh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cdnleiting.top/Article/details/gtfnuxzzjj.html

C#:   lock (gate) { shared++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtnjowoxlo.html

[O04] 定义异步函数并等待
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvyzvbfg.html

Py:   async def f():⏎    await g()
来源：http://dali.zhixingplan.top/Article/details/gtxdejhhyl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomignvmd.html

JS:   async function f() { await g(); }
来源：http://dali.fzhhl.top/Article/details/gtwaxorenz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jyoumei.cn/Article/details/gtgdsbhnjr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fzhhl.top/Article/details/gtwfiwtxia.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gogol.net.cn/Article/details/gtcmpyilzh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.tanke756.top/Article/details/gttyimvszy.html

C#:   async Task F() { await G(); }
来源：http://dali.jqgfzy.top/Article/details/gtkorkczkg.html

[O05] 并发执行并等待全部完成
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezbagdrs.html

Py:   asyncio.gather(*tasks)
来源：http://dali.birdmap.top/Article/details/gtgovybiee.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.pengpengdd.cyou/Article/details/gtpwkdvzqe.html

JS:   await Promise.all(tasks)
来源：http://dali.gaohongyu789.top/Article/details/gtvybxcccj.html

TS:   await Promise.all(tasks)
来源：http://dali.jlsjyb.cn/Article/details/gtqajwynar.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hongshengwenyu.top/Article/details/gteckpnbaa.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.pycfn.com/Article/details/gtohaxlyqi.html

Ruby: threads.map(&:join)
来源：http://dali.chenlongwang.top/Article/details/gtclgcdqcn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gaohongyu789.top/Article/details/gtjgexygfa.html

[O06] 使用进程池
来源：http://dali.shuidangran.top/Article/details/gtuianekag.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shzxlz.cn/Article/details/gtoytgwoht.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xziqi.cn/Article/details/gtgpmlpagr.html

JS:   // child_process / cluster 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnuqgxvrh.html

TS:   // child_process / cluster 模块
来源：http://dali.yuxming.cn/Article/details/gtxwrkaatw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenjidiqi.icu/Article/details/gtftolwfky.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.aizwys.cn/Article/details/gtrziugude.html

Ruby: // fork 块
来源：http://dali.pengpengdd.cyou/Article/details/gtmtcazhmo.html

C#:   Parallel.For
来源：http://dali.c1oappe.top/Article/details/gtgyvnluwf.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtixsdsfzc.html

P. 常用工具函数
来源：http://dali.jqgufenzy.top/Article/details/gtqnljckad.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtsgkgrqtt.html

[P01] 生成 UUID
来源：http://dali.zhixingplan.top/Article/details/gtmsjmflbb.html

Py:   str(uuid.uuid4())
来源：http://dali.meibo888.top/Article/details/gthasobgyk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gogol.net.cn/Article/details/gtapxdssno.html

JS:   crypto.randomUUID()
来源：http://dali.jqgufenzy.top/Article/details/gtdtkywmhz.html

TS:   crypto.randomUUID()
来源：http://dali.yj20258888.top/Article/details/gtznypcaiw.html

Java: UUID.randomUUID().toString()
来源：http://dali.cashguo.top/Article/details/gtocylhcsf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.pengpengdd.cyou/Article/details/gtnqnnehpk.html

Ruby: SecureRandom.uuid
来源：http://dali.yonumen.top/Article/details/gtsauagaaz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zdqjudy.top/Article/details/gtxowzqclw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jiagoushi.top/Article/details/gtcejaverm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tianlin.xyz/Article/details/gtgultfecv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nanxinkj.top/Article/details/gthicbhxbb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jyoumei.cn/Article/details/gtaclwbmxu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tanke756.top/Article/details/gtmzzgvyyg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xylfe.cn/Article/details/gtpjdhaypu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ivvv.top/Article/details/gtnfkmjhtz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.fengsongda.top/Article/details/gtfbfnicwd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sxryk.cn/Article/details/gtpwwrovkj.html

[P03] 生成短随机字符串
来源：http://dali.sxryk.cn/Article/details/gtizdoqheb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj202588.top/Article/details/gtgcikytnv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jqgufenzy.top/Article/details/gtbmgweosm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daxiang520.top/Article/details/gtgcbcpckf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zdqjudy.top/Article/details/gtdlkgrkxu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.fengsongda.top/Article/details/gtiwhsbsyp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cqqwz.cn/Article/details/gtesubvxol.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.snrcjt.cn/Article/details/gtleyxtyoa.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yvedp.cn/Article/details/gthbpmicyj.html

[P04] 求长度
来源：http://dali.kuanghao11.cn/Article/details/gtgtlptbgl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhiwuduotai.top/Article/details/gtipskwvfe.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcfmuyuft.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daxiang520.top/Article/details/gticrpdbkd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dianchejie.cn/Article/details/gtlpcewqpi.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hysaishi.cn/Article/details/gtslxpcpfl.html

Go:   len(arr);  len(m)
来源：http://dali.ppjwa.cn/Article/details/gtbgzltnsh.html

Ruby: x.length;  x.size
来源：http://dali.zhiwuduotai.top/Article/details/gtivvcpgvv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yuxming.cn/Article/details/gtirkhgspn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sxryk.cn/Article/details/gtfjevwbbx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shzxlz.cn/Article/details/gtfbjqnxqo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhiwuduotai.top/Article/details/gtvwxqfvgc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj20258.top/Article/details/gtrtuqwahh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sysykeji.top/Article/details/gtjgptdyaz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.meibo888.top/Article/details/gtyivpajtu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.c1oappe.top/Article/details/gtydbbhpxc.html

Ruby: a == b
来源：http://dali.xinyue.icu/Article/details/gtewvjghqj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.9152youxi.cn/Article/details/gtqbnqzwuw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.mhx1999.top/Article/details/gtearevmtk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.andypj.xyz/Article/details/gtqjfyheej.html

PHP:  if (empty($x)) {}
来源：http://dali.hnxiangtu.top/Article/details/gtaneuwcpu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ydzc1.top/Article/details/gteqrxkfre.html

TS:   if (x == null) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtdzyttcax.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jqgfzy.top/Article/details/gtrdfuawor.html

Go:   if x == nil {}
来源：http://dali.daxiang520.top/Article/details/gtpxmmfsww.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hnxiangtu.top/Article/details/gtdpuzadvu.html

C#:   if (x is null) {}
来源：http://dali.yueranfly.top/Article/details/gtpnsfduqm.html

[P07] 防抖与节流
来源：http://dali.hammf.cn/Article/details/gtjwjgoytx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcmkmwngx.html

PHP:  // 手写时间戳比较
来源：http://dali.pengpengdd.cyou/Article/details/gtbzepuzaw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gtfklqcbzn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gtdgyvpmgk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenlongwang.top/Article/details/gthmagnnyt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gzhubu.top/Article/details/gtmkymcamv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.wangshuangyany.cn/Article/details/gtatryofqe.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbzpwjys.html

[P08] 处理浮点精度问题
来源：http://dali.ppjwa.cn/Article/details/gtqdkdabcn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cqqwz.cn/Article/details/gthbpovezj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jlsjyb.cn/Article/details/gthkgksxvp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcggwjywt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gtcvcjjcvx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.feifeiyinyue.top/Article/details/gtqptgzevn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tianlin.xyz/Article/details/gtfyqktess.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuycmmwpm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.birdmap.top/Article/details/gtooprfpij.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtrdathrpy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigfzy.top/Article/details/gtnajdvpjt.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtbptzcfwk.html

[Q01] 创建表
来源：http://dali.sufxvd.cn/Article/details/gtmumtwwns.html

CREATE TABLE users (
来源：http://dali.tian-w.cn/Article/details/gtntshizhl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yonumen.top/Article/details/gtecfnrqnp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.daria6918.cn/Article/details/gtajxvbzjn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yuanzhike.top/Article/details/gtnkgpjsbm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinqigfzy.top/Article/details/gtdjghgzmg.html

);
来源：http://dali.hongshengwenyu.top/Article/details/gtbqeymgbh.html

[Q02] 创建带外键的表
来源：http://dali.yanxiufei.cn/Article/details/gtsrnxogcw.html

CREATE TABLE orders (
来源：http://dali.sufxvd.cn/Article/details/gtaiqpilay.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.haohaochexian.top/Article/details/gtjvewjodj.html

user_id INT NOT NULL,
来源：http://dali.zhongyouzk.top/Article/details/gtdxsworbw.html

amount DECIMAL(10, 2),
来源：http://dali.cdnleiting.top/Article/details/gtqbkabakb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbewycejq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gtkdmnxxxj.html

[Q03] 增加列
来源：http://dali.sufxvd.cn/Article/details/gtfxruxcba.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sweek.top/Article/details/gtgjhtpcku.html

[Q04] 修改列类型
来源：http://dali.hongshengwenyu.top/Article/details/gtqzjtyjap.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shanyushiyangtech.top/Article/details/gtryrsfxjm.html

[Q05] 重命名列
来源：http://dali.haohaochexian.top/Article/details/gtyplnbcmf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhiwuduotai.top/Article/details/gtpmiotqrd.html

[Q06] 删除列
来源：http://dali.dashuyun.cn/Article/details/gtmqpacvvg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.dianchejie.cn/Article/details/gttlvucuft.html

[Q07] 删除表
来源：http://dali.316326.xyz/Article/details/gtienojicm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.9152youxi.cn/Article/details/gtecqazvpg.html

[Q08] 创建普通索引
来源：http://dali.birdmap.top/Article/details/gtfqefbzpc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhiwuduotai.top/Article/details/gtkfhzlgrm.html

[Q09] 创建唯一索引
来源：http://dali.fengsongda.top/Article/details/gtdgixtrnl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yj20258888.top/Article/details/gtpxecgdhe.html

[Q10] 插入单行
来源：http://dali.nanxuanxn.top/Article/details/gtsjkuzaak.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hnqzz.top/Article/details/gtfpxyusea.html

[Q11] 一次插入多行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwihzzfcj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hnqzz.top/Article/details/gtftenuzba.html

[Q12] 插入后取自增 ID
来源：http://dali.sufxvd.cn/Article/details/gtvdjbvsdf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tianlin.xyz/Article/details/gtjyqwttyo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hammf.cn/Article/details/gtpulnenzn.html

[Q13] 忽略重复插入
来源：http://dali.daxiang520.top/Article/details/gtxtqbfcbv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hnqzz.top/Article/details/gtpljhtuli.html

[Q14] 存在则更新（upsert）
来源：http://dali.cashguo.top/Article/details/gtxnoveebf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gotoacloud.top/Article/details/gtlzjosytv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.pengpengdd.cyou/Article/details/gtdtynqknq.html

[Q15] 查询全部
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvuarxmxt.html

SELECT * FROM users;
来源：http://dali.smart0.xyz/Article/details/gtjocotqgt.html

[Q16] 查询指定列
来源：http://dali.gogol.net.cn/Article/details/gtiiohmkrl.html

SELECT id, name FROM users;
来源：http://dali.xylfe.cn/Article/details/gtlbxpqjbi.html

[Q17] 条件查询
来源：http://dali.dashuyun.cn/Article/details/gtixidyaxz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtemmgbtum.html

[Q18] 模糊匹配
来源：http://dali.sufxvd.cn/Article/details/gtqnagdclj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.daxiang520.top/Article/details/gtftthdkri.html

[Q19] 范围查询
来源：http://dali.xinyue.icu/Article/details/gtlvunkluj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yvedp.cn/Article/details/gtbutpkwyr.html

[Q20] IN 列表
来源：http://dali.ppjwa.cn/Article/details/gthjcjnhsm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuanzhike.top/Article/details/gtqusbbekp.html

[Q21] 空值判断
来源：http://dali.hongshengwenyu.top/Article/details/gtnjsunnir.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.smart0.xyz/Article/details/gtnuiqtzmw.html

[Q22] 排序
来源：http://dali.ppjwa.cn/Article/details/gtbfleorvu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.dashuyun.cn/Article/details/gtvlhxebcf.html

[Q23] 分页
来源：http://dali.dianchejie.cn/Article/details/gtxtdzrjej.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtopmvlvkr.html

[Q24] 去重
来源：http://dali.cucudq.cn/Article/details/gtjszslbdp.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtuedqvfqb.html

[Q25] 只取前 N 条
来源：http://dali.hfpthk.cn/Article/details/gtcwobqmzy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jqgfzy.top/Article/details/gtegjyavlk.html

[Q26] 计数
来源：http://dali.sufxvd.cn/Article/details/gtzuidsuor.html

SELECT COUNT(*) FROM users;
来源：http://dali.tanke756.top/Article/details/gtfpcodvop.html

[Q27] 条件计数
来源：http://dali.dianchejie.cn/Article/details/gtsgazohru.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.bjfxy.top/Article/details/gtzvojydgr.html

[Q28] 求和与平均
来源：http://dali.wangshuangyany.cn/Article/details/gtsosdxcug.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsijixmek.html

[Q29] 最大最小值
来源：http://dali.cucudq.cn/Article/details/gtmbjvauuz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtfqhfekbn.html

[Q30] 分组统计
来源：http://dali.jqgufenzy.top/Article/details/gtmurqfwez.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gtnlryurwv.html

[Q31] 分组后过滤
来源：http://dali.jyoumei.cn/Article/details/gtjgpxirpx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.aizwys.cn/Article/details/gthrxofynw.html

[Q32] 分组拼接字符串
来源：http://dali.tanke756.top/Article/details/gtcoeimydf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgulvlgzn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenjidiqi.icu/Article/details/gtvsciqffq.html

[Q33] 多列分组
来源：http://dali.bjfxy.top/Article/details/gtmzywgipb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xziqi.cn/Article/details/gtnvknlfex.html

[Q34] 每组取第一条
来源：http://dali.hnqzz.top/Article/details/gtmzrkekzu.html

SELECT * FROM (
来源：http://dali.tianlin.xyz/Article/details/gtsklqflhd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hammf.cn/Article/details/gtxnlmdcoa.html

) t WHERE rn = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtbyvyfanm.html

[Q35] 内连接
来源：http://dali.yj20258888.top/Article/details/gtkklhuqoc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnxiangtu.top/Article/details/gtwsocvwgj.html

[Q36] 左连接
来源：http://dali.zhoulong.xyz/Article/details/gtujqiwtwx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxuanxn.top/Article/details/gtbrzgidhq.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gtgbgpmord.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.nanxuanxn.top/Article/details/gtrrebgncq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xuetiantiany.cn/Article/details/gtpnibyqak.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.svipenyu.cn/Article/details/gteswkywgo.html

[Q39] 自连接（查上下级）
来源：http://dali.zhiwuduotai.top/Article/details/gtskthlqpd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xuetiantiany.cn/Article/details/gtzluvwwlj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.svipenyu.cn/Article/details/gtxpqgxuqb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ybcxt.top/Article/details/gtqhdesrmb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhongyouzk.top/Article/details/gtefbypqrf.html

[Q41] 多表连接
来源：http://dali.cdnleiting.top/Article/details/gtvduuemss.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.chenzaomai.com/Article/details/gtcyvykmbj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xinyue.icu/Article/details/gtrgmddgix.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tianlin.xyz/Article/details/gtwaqgqyzv.html

[Q42] 连接条件附加过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtggoiinka.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijznqtgx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ppjwa.cn/Article/details/gtubvatwbt.html

[Q43] 标量子查询
来源：http://dali.smart0.xyz/Article/details/gtniwlswgj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yj202588.top/Article/details/gtzpimbclm.html

[Q44] IN 子查询
来源：http://dali.bjfxy.top/Article/details/gthqwyhdjp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jyoumei.cn/Article/details/gtxrtmkyvv.html

[Q45] EXISTS 判断存在
来源：http://dali.shuidangran.top/Article/details/gtgkqsnrjq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shuidangran.top/Article/details/gtviwjncgd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.quarkkingdee.top/Article/details/gtyamogarg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgufenzy.top/Article/details/gtaetgjhmv.html

[Q47] 与平均值比较
来源：http://dali.zhongyouzk.top/Article/details/gtykctoyzw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.kuanghao11.cn/Article/details/gtungrubdw.html

[Q48] CTE 公用表表达式
来源：http://dali.jlsjyb.cn/Article/details/gtsovgjuqa.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.tianlin.xyz/Article/details/gtjymjlyxo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.kuanghao11.cn/Article/details/gtkzmnooaq.html

[Q49] 更新单行
来源：http://dali.yangfankeji.com/Article/details/gtuwayirow.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gtqyehkrcf.html

[Q50] 批量更新
来源：http://dali.jinghuilouyu.cn/Article/details/gtefuiqong.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj20258888.top/Article/details/gtedzqycgw.html

[Q51] 用子查询更新
来源：http://dali.meibo888.top/Article/details/gtyiiyzbjq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtvomxnkvm.html

[Q52] 删除指定行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpaqktaln.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhoulong.xyz/Article/details/gtlnjpbocp.html

[Q53] 按条件删除
来源：http://dali.fengsongda.top/Article/details/gtdtnrvzaw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zdqjudy.top/Article/details/gtaqtwhibw.html

[Q54] 清空表
来源：http://dali.cashguo.top/Article/details/gtyihucwrz.html

TRUNCATE TABLE logs;
来源：http://dali.cqqwz.cn/Article/details/gthukfwjvb.html

[Q55] 排名（并列占位）
来源：http://dali.aizwys.cn/Article/details/gtskwviblc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zdqjudy.top/Article/details/gttkluxuhs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.haohaochexian.top/Article/details/gtcimscgyu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nwbrower.top/Article/details/gtuqwokcic.html

[Q57] 行号
来源：http://dali.shangyingyoupin.top/Article/details/gtmsynmwkc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtgolqfkdv.html

[Q58] 累计求和
来源：http://dali.nwbrower.top/Article/details/gtqibcvmir.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.andypj.xyz/Article/details/gthulgrwha.html

[Q59] 分组内累计
来源：http://dali.zycfv.cn/Article/details/gtzizvizyv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtciwyjpfp.html

[Q60] 取上一行 / 下一行
来源：http://dali.meibo888.top/Article/details/gtkfemirbm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.316326.xyz/Article/details/gthmkddwia.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtgzjoznpz.html

[Q61] 移动平均
来源：http://dali.guannengcc.top/Article/details/gtuphbqzem.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.meibo888.top/Article/details/gtpmbusgbf.html

[Q62] 分组占比
来源：http://dali.haohaochexian.top/Article/details/gtnsisdyum.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gtaoimytnx.html

[Q63] 开启事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfcgkoinn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.dashuyun.cn/Article/details/gtdoxosiba.html

[Q64] 提交事务
来源：http://dali.guannengcc.top/Article/details/gtsbkbyjxj.html

COMMIT;
来源：http://dali.sysykeji.top/Article/details/gttttqxrib.html

[Q65] 回滚事务
来源：http://dali.chenzaomai.com/Article/details/gtslcgfrsf.html

ROLLBACK;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcdyoiwna.html

[Q66] 行锁查询
来源：http://dali.dashuyun.cn/Article/details/gtasyhdimn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ivvv.top/Article/details/gtuemgpizt.html

[Q67] 设置隔离级别
来源：http://dali.jyoumei.cn/Article/details/gtlcjmxuxw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtevtpywuk.html

[Q68] 保存点
来源：http://dali.chenjidiqi.icu/Article/details/gtcfmukdoe.html

SAVEPOINT sp1;
来源：http://dali.gotoacloud.top/Article/details/gtghfpikea.html

ROLLBACK TO sp1;
来源：http://dali.jinqigufen.top/Article/details/gtwiigumgv.html

[Q69] 查看执行计划
来源：http://dali.yangfankeji.com/Article/details/gtjjmzyuii.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cashguo.top/Article/details/gtpdsmoovk.html

[Q70] 更新统计信息
来源：http://dali.cqqwz.cn/Article/details/gtcsmygxbx.html

ANALYZE TABLE users;
来源：http://dali.dianchejie.cn/Article/details/gthihldzan.html

[Q71] 查看建表语句
来源：http://dali.dashuyun.cn/Article/details/gtunpvxmvd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzlnuqnwi.html

[Q72] 查看索引
来源：http://dali.nanxinkj.top/Article/details/gtugvgyamu.html

SHOW INDEX FROM users;
来源：http://dali.9152youxi.cn/Article/details/gteqtkedlv.html

[Q73] 查看表状态
来源：http://dali.tian-w.cn/Article/details/gtadmkmszd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ehwqpu.com/Article/details/gtxeohjkob.html

[Q74] 强制使用索引
来源：http://dali.fzhhl.top/Article/details/gtfnkqygwo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zycfv.cn/Article/details/gtajdshhul.html

[Q75] 日期格式化
来源：http://dali.yj20258.top/Article/details/gtipqyndjp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtyrdjxakx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yanxiufei.cn/Article/details/gtsxeplbdv.html

[Q76] 按天统计
来源：http://dali.mhx1999.top/Article/details/gtbjfjoazn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhiwuduotai.top/Article/details/gtmrbnpjru.html

[Q77] 时间加减
来源：http://dali.hysaishi.cn/Article/details/gtuvtradbf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinqigufen.top/Article/details/gttitrczvo.html

[Q78] 当前时间
来源：http://dali.aizwys.cn/Article/details/gtbjuklrnj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nwbrower.top/Article/details/gtfcmqpsin.html

[Q79] 字符串拼接
来源：http://dali.jyoumei.cn/Article/details/gtxnlogshk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nanxuanxn.top/Article/details/gthbhyzfzu.html


<!-- 参考信息 -->