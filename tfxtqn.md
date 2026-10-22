代发 wailian999

TS:   // worker_threads 线程池
来源：http://dali.andypj.xyz/Article/details/gtwnwnzfsa.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zycfv.cn/Article/details/gtoihdspgt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jyoumei.cn/Article/details/gttugrwaaj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cucudq.cn/Article/details/gtxezluqqk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinyuanbaomall.cn/Article/details/gtztlgwpsc.html

[O03] 加锁保护共享数据
来源：http://dali.yanxiufei.cn/Article/details/gtwcrlfowf.html

Py:   with lock: shared += 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlnbeehdk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhongyouzk.top/Article/details/gtlaipflht.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gtkcegdxxi.html

TS:   // 同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gtwrwwubaw.html

Java: synchronized (this) { shared++; }
来源：http://dali.vqdsnc.cn/Article/details/gtgrqexfzn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tanke756.top/Article/details/gtbekvtnyo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ehwqpu.com/Article/details/gtnybyuryt.html

C#:   lock (gate) { shared++; }
来源：http://dali.gzhubu.top/Article/details/gtdzhrbkao.html

[O04] 定义异步函数并等待
来源：http://dali.iojbl.cn/Article/details/gtqdectmqh.html

Py:   async def f():⏎    await g()
来源：http://dali.chenzaomai.com/Article/details/gtwuvozjjt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cqqwz.cn/Article/details/gttlahfzfs.html

JS:   async function f() { await g(); }
来源：http://dali.gaohongyu789.top/Article/details/gttadoyptk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.fzhhl.top/Article/details/gtjbugpwtw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gogol.net.cn/Article/details/gtzxeqyodl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yangfankeji.com/Article/details/gtlgkiuvxh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ivvv.top/Article/details/gtycxungcn.html

C#:   async Task F() { await G(); }
来源：http://dali.xziqi.cn/Article/details/gtdisvtlir.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinyuanbaomall.cn/Article/details/gtypjlhhzx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gtpnepzapi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xylfe.cn/Article/details/gtadlztlbn.html

JS:   await Promise.all(tasks)
来源：http://dali.chenlongwang.top/Article/details/gtczsklmsy.html

TS:   await Promise.all(tasks)
来源：http://dali.chenzaomai.com/Article/details/gtynvnsary.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cheryme.top/Article/details/gtgkxkrjit.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.andypj.xyz/Article/details/gtpzgxwgvv.html

Ruby: threads.map(&:join)
来源：http://dali.sweek.top/Article/details/gtzbdjifeq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdawudojd.html

[O06] 使用进程池
来源：http://dali.tian-w.cn/Article/details/gtuqncgtjm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.pengpengdd.cyou/Article/details/gtcrcvtxdc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ppjwa.cn/Article/details/gtgwteiksv.html

JS:   // child_process / cluster 模块
来源：http://dali.sysykeji.top/Article/details/gtasmmoizl.html

TS:   // child_process / cluster 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gthswdbucv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shangyingyoupin.top/Article/details/gtpuljwvbo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.dashuyun.cn/Article/details/gtsnhnmcnu.html

Ruby: // fork 块
来源：http://dali.c1oappe.top/Article/details/gtcyljmwug.html

C#:   Parallel.For
来源：http://dali.yuxming.cn/Article/details/gttkcqcuhv.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gttmtccijl.html

P. 常用工具函数
来源：http://dali.shzxlz.cn/Article/details/gtiyicscnh.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtrfntdusk.html

[P01] 生成 UUID
来源：http://dali.fzhhl.top/Article/details/gtrqlcijni.html

Py:   str(uuid.uuid4())
来源：http://dali.gogol.net.cn/Article/details/gtrwydnorb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.fzhhl.top/Article/details/gtujtctydk.html

JS:   crypto.randomUUID()
来源：http://dali.yueranfly.top/Article/details/gtjtktlkpz.html

TS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdnrenrpc.html

Java: UUID.randomUUID().toString()
来源：http://dali.hnqzz.top/Article/details/gtmgkkkfbg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.feifeiyinyue.top/Article/details/gtfkdeknct.html

Ruby: SecureRandom.uuid
来源：http://dali.yvedp.cn/Article/details/gtczacekpi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ppjwa.cn/Article/details/gthgsgjgjz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gaohongyu789.top/Article/details/gtclstkzfb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.fengsongda.top/Article/details/gtbnumwrbr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jlsjyb.cn/Article/details/gtopriitaj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shangyingyoupin.top/Article/details/gtyloixgfq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.guowangkeji.top/Article/details/gtsswuczon.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gogol.net.cn/Article/details/gttcfvjiaf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xziqi.cn/Article/details/gtmznzcpgw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jlsjyb.cn/Article/details/gtglqpkvls.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.snrcjt.cn/Article/details/gtgokdgoda.html

[P03] 生成短随机字符串
来源：http://dali.0kj1m.cn/Article/details/gtxfmmgzkq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj20258888.top/Article/details/gtvkrnrcvi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sxryk.cn/Article/details/gtleqompge.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.redwolf501.top/Article/details/gthceawwke.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gttzhvodth.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gotoacloud.top/Article/details/gtcauucbec.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sxryk.cn/Article/details/gttdnnwwzz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jqgfzy.top/Article/details/gtnkfkleih.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hfpthk.cn/Article/details/gtpfyfgrxc.html

[P04] 求长度
来源：http://dali.dashuyun.cn/Article/details/gtqtzseabp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.smart0.xyz/Article/details/gtdcwqvhwr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sweek.top/Article/details/gtdoarspul.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbplhgugi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pycfn.com/Article/details/gtivihzgwq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jyoumei.cn/Article/details/gtxyvpeaat.html

Go:   len(arr);  len(m)
来源：http://dali.zdqjudy.top/Article/details/gtvdojqqyn.html

Ruby: x.length;  x.size
来源：http://dali.svipenyu.cn/Article/details/gtodqvuvso.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.pengpengdd.cyou/Article/details/gtqqmgzaqt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhoulong.xyz/Article/details/gtjcoilmjg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sweek.top/Article/details/gtzwxptzln.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jlsjyb.cn/Article/details/gtughmfxyz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xziqi.cn/Article/details/gtpbcciyws.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangdashe.top/Article/details/gtthvwsvmz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hfpthk.cn/Article/details/gtargdmjun.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yueranfly.top/Article/details/gtzlntunye.html

Ruby: a == b
来源：http://dali.tanke756.top/Article/details/gtyzcwqgtc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ydzc1.top/Article/details/gtiukgvybh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.tanke756.top/Article/details/gtlfkajrmw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hywenlv.cn/Article/details/gtqfeylymx.html

PHP:  if (empty($x)) {}
来源：http://dali.jyoumei.cn/Article/details/gtjfwpmyde.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdpujickv.html

TS:   if (x == null) {}
来源：http://dali.yangfankeji.com/Article/details/gtjhsiqpuv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jqgfzy.top/Article/details/gtipcwwcbc.html

Go:   if x == nil {}
来源：http://dali.wangdashe.top/Article/details/gtwkhxagto.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tian-w.cn/Article/details/gtanovmxuq.html

C#:   if (x is null) {}
来源：http://dali.meibo888.top/Article/details/gtfnmvahxu.html

[P07] 防抖与节流
来源：http://dali.guannengcc.top/Article/details/gtaxudkctw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhongyouzk.top/Article/details/gtctxygabt.html

PHP:  // 手写时间戳比较
来源：http://dali.xinyue.icu/Article/details/gtcbhjokmi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gtjtfnxqec.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gtgxmcnlfr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinqigufen.top/Article/details/gtrwmpwsnj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jiagoushi.top/Article/details/gtlsuavovi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtithrxhut.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nwbrower.top/Article/details/gtiyettnxi.html

[P08] 处理浮点精度问题
来源：http://dali.wangdashe.top/Article/details/gtloxmvcxe.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.snrcjt.cn/Article/details/gtwmohpjpg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gzhubu.top/Article/details/gtsrwoswsq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.fengsongda.top/Article/details/gtjqmmvicd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhixingplan.top/Article/details/gtyjcwujre.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrtvcudo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tianlin.xyz/Article/details/gtahfhzdmr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hnqzz.top/Article/details/gtfvmikawv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ppjwa.cn/Article/details/gtvaiugzhu.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtniimteff.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cqqwz.cn/Article/details/gtpfbilalo.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtjuadpndm.html

[Q01] 创建表
来源：http://dali.gotoacloud.top/Article/details/gtvlbuwqdz.html

CREATE TABLE users (
来源：http://dali.hnqzz.top/Article/details/gtfpwzyqix.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daria6918.cn/Article/details/gtihnsirmm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zycfv.cn/Article/details/gtrkmljhbv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yj202588.top/Article/details/gtrgzigcwh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.smart0.xyz/Article/details/gtbbkwwtki.html

);
来源：http://dali.zhixingplan.top/Article/details/gtuybnlkyj.html

[Q02] 创建带外键的表
来源：http://dali.xziqi.cn/Article/details/gtinrobrlb.html

CREATE TABLE orders (
来源：http://dali.yvedp.cn/Article/details/gtqmuettea.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigfzy.top/Article/details/gtkpdvdgfo.html

user_id INT NOT NULL,
来源：http://dali.xziqi.cn/Article/details/gtmqyivwkz.html

amount DECIMAL(10, 2),
来源：http://dali.dashuyun.cn/Article/details/gtwqkfbtih.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xylfe.cn/Article/details/gtzdjnxmxw.html

);
来源：http://dali.dianchejie.cn/Article/details/gtkoahgiai.html

[Q03] 增加列
来源：http://dali.aibaodan.cn/Article/details/gtccleamzt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pengpengdd.cyou/Article/details/gtdkzbzalc.html

[Q04] 修改列类型
来源：http://dali.sufxvd.cn/Article/details/gteixypzkk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.aizwys.cn/Article/details/gtgunnzejn.html

[Q05] 重命名列
来源：http://dali.zhongyouzk.top/Article/details/gtieysdgnr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zycfv.cn/Article/details/gtsoslfewg.html

[Q06] 删除列
来源：http://dali.hammf.cn/Article/details/gtnsrbnaxa.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hywenlv.cn/Article/details/gtfapgycqw.html

[Q07] 删除表
来源：http://dali.meibo888.top/Article/details/gtuvlyxlrl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cucudq.cn/Article/details/gttxhmugqd.html

[Q08] 创建普通索引
来源：http://dali.zdqjudy.top/Article/details/gtjwahfbsy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yonumen.top/Article/details/gtrdoroktf.html

[Q09] 创建唯一索引
来源：http://dali.chenzaomai.com/Article/details/gtohvnqoja.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zycfv.cn/Article/details/gtzxfxyhvx.html

[Q10] 插入单行
来源：http://dali.nwbrower.top/Article/details/gtnzfbtiqv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.aizwys.cn/Article/details/gtnivpdhgc.html

[Q11] 一次插入多行
来源：http://dali.gotoacloud.top/Article/details/gtbwtxcvgr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yuxming.cn/Article/details/gtsijazypp.html

[Q12] 插入后取自增 ID
来源：http://dali.yonumen.top/Article/details/gttkobfwaz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yj20258888.top/Article/details/gtdhnvfips.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.dashuyun.cn/Article/details/gtrhknfkum.html

[Q13] 忽略重复插入
来源：http://dali.cdnleiting.top/Article/details/gtgyxwngeg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.wangdashe.top/Article/details/gtewcvihwd.html

[Q14] 存在则更新（upsert）
来源：http://dali.snrcjt.cn/Article/details/gtduvztixt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.wangdashe.top/Article/details/gtpmtkwijy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.dashuyun.cn/Article/details/gtvfvtvyqc.html

[Q15] 查询全部
来源：http://dali.gaohongyu789.top/Article/details/gtulrzovfi.html

SELECT * FROM users;
来源：http://dali.havefunace.top/Article/details/gtsjaeilqc.html

[Q16] 查询指定列
来源：http://dali.cashguo.top/Article/details/gtdakjpshe.html

SELECT id, name FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtdezksspv.html

[Q17] 条件查询
来源：http://dali.hammf.cn/Article/details/gtdqxjpoau.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gzhubu.top/Article/details/gtfzgzutyx.html

[Q18] 模糊匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjbidaunl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xylfe.cn/Article/details/gtmgwxokyd.html

[Q19] 范围查询
来源：http://dali.yongpay.top/Article/details/gtdpovbmxt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hywenlv.cn/Article/details/gtgwtyutwr.html

[Q20] IN 列表
来源：http://dali.cheryme.top/Article/details/gtmszjeujm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxwsbnopd.html

[Q21] 空值判断
来源：http://dali.yuxming.cn/Article/details/gtbontlouj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jqgfzy.top/Article/details/gtarzpddms.html

[Q22] 排序
来源：http://dali.nanxinkj.top/Article/details/gtucamjtmg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jqgufenzy.top/Article/details/gtrixjfdxp.html

[Q23] 分页
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtktwqnsil.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.redwolf501.top/Article/details/gtwjsshcrr.html

[Q24] 去重
来源：http://dali.vqdsnc.cn/Article/details/gtyppuwoam.html

SELECT DISTINCT city FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbpcawfxm.html

[Q25] 只取前 N 条
来源：http://dali.gogol.net.cn/Article/details/gtukkvgomm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yongpay.top/Article/details/gtialjipeq.html

[Q26] 计数
来源：http://dali.chenzaomai.com/Article/details/gtlngjzrey.html

SELECT COUNT(*) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxsuownkt.html

[Q27] 条件计数
来源：http://dali.jianghu66.top/Article/details/gtraoqngrj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.fzhhl.top/Article/details/gtfvqgarao.html

[Q28] 求和与平均
来源：http://dali.c1oappe.top/Article/details/gtclrxiqeq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcojmcndd.html

[Q29] 最大最小值
来源：http://dali.svipenyu.cn/Article/details/gtijwuqbmm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtidzbklzq.html

[Q30] 分组统计
来源：http://dali.cucudq.cn/Article/details/gtcmhllmdp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gtvjujurzz.html

[Q31] 分组后过滤
来源：http://dali.hywenlv.cn/Article/details/gtuullogei.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cdnleiting.top/Article/details/gttvwmonoj.html

[Q32] 分组拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtjfnpkfed.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gtwjygxoff.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ywan-chungtsiang.top/Article/details/gthshefznr.html

[Q33] 多列分组
来源：http://dali.yvedp.cn/Article/details/gtkhvmmlqs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.svipenyu.cn/Article/details/gtsaurkoec.html

[Q34] 每组取第一条
来源：http://dali.zhiwuduotai.top/Article/details/gtscckfsnl.html

SELECT * FROM (
来源：http://dali.daxiang520.top/Article/details/gtgbutbvya.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.mhx1999.top/Article/details/gtenweujvr.html

) t WHERE rn = 1;
来源：http://dali.daria6918.cn/Article/details/gtzomwtynp.html

[Q35] 内连接
来源：http://dali.mhx1999.top/Article/details/gtwwbmixli.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenzaomai.com/Article/details/gtuszcmhqi.html

[Q36] 左连接
来源：http://dali.mhx1999.top/Article/details/gtwpmnbyem.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gtsmadmkha.html

[Q37] 右连接
来源：http://dali.guowangkeji.top/Article/details/gtujgcnqzk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.fengsongda.top/Article/details/gtjbfgthre.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gotoacloud.top/Article/details/gtbfcmdwdk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gtzprorfzw.html

[Q39] 自连接（查上下级）
来源：http://dali.shangyingyoupin.top/Article/details/gtvfavfmrf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jlsjyb.cn/Article/details/gtekpwemjs.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.birdmap.top/Article/details/gtglkduhpw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.meibo888.top/Article/details/gtxzjybkkt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenlongwang.top/Article/details/gtuwlhpsxd.html

[Q41] 多表连接
来源：http://dali.yuxming.cn/Article/details/gttffocknv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.haohaochexian.top/Article/details/gtdglhpooo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gzhubu.top/Article/details/gtkuzqjtnw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.fengsongda.top/Article/details/gtdtcfrikq.html

[Q42] 连接条件附加过滤
来源：http://dali.ivvv.top/Article/details/gtaeovpqoi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tianlin.xyz/Article/details/gttjyzvgzk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.smart0.xyz/Article/details/gtwlxssjgw.html

[Q43] 标量子查询
来源：http://dali.ybcxt.top/Article/details/gtljbsijwk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.wangdashe.top/Article/details/gtnizqjbks.html

[Q44] IN 子查询
来源：http://dali.shangyingyoupin.top/Article/details/gtvycbhzdc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hfpthk.cn/Article/details/gtalgvggsn.html

[Q45] EXISTS 判断存在
来源：http://dali.sxryk.cn/Article/details/gtbjkeaque.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.9152youxi.cn/Article/details/gtmywgyuos.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.havefunace.top/Article/details/gtcwsyonmb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gtctonlasg.html

[Q47] 与平均值比较
来源：http://dali.jianghu66.top/Article/details/gtofzhsxdc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhiwuduotai.top/Article/details/gtwiecetkt.html

[Q48] CTE 公用表表达式
来源：http://dali.xylfe.cn/Article/details/gtfjwbhbyx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xinyue.icu/Article/details/gtgqbmmjmb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ydzc1.top/Article/details/gtryfgvhyk.html

[Q49] 更新单行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtikdeihfw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.daxiang520.top/Article/details/gtpxsfnemv.html

[Q50] 批量更新
来源：http://dali.jlsjyb.cn/Article/details/gtygjqflqx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jqgufenzy.top/Article/details/gtwoqvstdw.html

[Q51] 用子查询更新
来源：http://dali.chenlongwang.top/Article/details/gtwijynpkx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtammiuoqv.html

[Q52] 删除指定行
来源：http://dali.yongpay.top/Article/details/gtrppiufkd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gtdqbdwwiv.html

[Q53] 按条件删除
来源：http://dali.hfpthk.cn/Article/details/gtohmdsfki.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ybcxt.top/Article/details/gtthdblzzc.html

[Q54] 清空表
来源：http://dali.jlsjyb.cn/Article/details/gtaiypgxoe.html

TRUNCATE TABLE logs;
来源：http://dali.gogol.net.cn/Article/details/gthykfsdqt.html

[Q55] 排名（并列占位）
来源：http://dali.haohaochexian.top/Article/details/gtxqfmdaoc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jqgufenzy.top/Article/details/gtrotpobto.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tian-w.cn/Article/details/gtypomuiel.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sysykeji.top/Article/details/gtahodcknh.html

[Q57] 行号
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvzesdtn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.smart0.xyz/Article/details/gtllrepwhf.html

[Q58] 累计求和
来源：http://dali.xziqi.cn/Article/details/gtbgdalkto.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cheryme.top/Article/details/gtllywclnu.html

[Q59] 分组内累计
来源：http://dali.yanxiufei.cn/Article/details/gtmuifxsuz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtmoqztonj.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj20258.top/Article/details/gtgghaboqi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.havefunace.top/Article/details/gtvmsmqbyz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtklmjyfms.html

[Q61] 移动平均
来源：http://dali.guowangkeji.top/Article/details/gthdiqdvbh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtegmppezm.html

[Q62] 分组占比
来源：http://dali.cqqwz.cn/Article/details/gtugolbwoy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gtsiqidxdm.html

[Q63] 开启事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwhvzehc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.c1oappe.top/Article/details/gtoifoisxk.html

[Q64] 提交事务
来源：http://dali.yonumen.top/Article/details/gtaptzdmzg.html

COMMIT;
来源：http://dali.hysaishi.cn/Article/details/gtdohknotm.html

[Q65] 回滚事务
来源：http://dali.iojbl.cn/Article/details/gtopirjhjs.html

ROLLBACK;
来源：http://dali.cucudq.cn/Article/details/gtqcxfxtvl.html

[Q66] 行锁查询
来源：http://dali.pycfn.com/Article/details/gtlchudjqv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jqgufenzy.top/Article/details/gtmfxtubzu.html

[Q67] 设置隔离级别
来源：http://dali.jinqigufen.top/Article/details/gtxbwroomr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.redwolf501.top/Article/details/gtmtrjmblv.html

[Q68] 保存点
来源：http://dali.316326.xyz/Article/details/gtmuzlgahc.html

SAVEPOINT sp1;
来源：http://dali.havefunace.top/Article/details/gtgnhnckdi.html

ROLLBACK TO sp1;
来源：http://dali.cheryme.top/Article/details/gtlgjxlval.html

[Q69] 查看执行计划
来源：http://dali.ivvv.top/Article/details/gtmgphybrh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hysaishi.cn/Article/details/gtighqxksy.html

[Q70] 更新统计信息
来源：http://dali.dashuyun.cn/Article/details/gtbifjbndc.html

ANALYZE TABLE users;
来源：http://dali.guowangkeji.top/Article/details/gttgdsejns.html

[Q71] 查看建表语句
来源：http://dali.nanxinkj.top/Article/details/gtzakgpcwq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cheryme.top/Article/details/gtsdomxbte.html

[Q72] 查看索引
来源：http://dali.smart0.xyz/Article/details/gtrxqecmbj.html

SHOW INDEX FROM users;
来源：http://dali.yongpay.top/Article/details/gtoxbfuiji.html

[Q73] 查看表状态
来源：http://dali.zhaomingkeji.xyz/Article/details/gtekzyvtmy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenlongwang.top/Article/details/gtkltydgyw.html

[Q74] 强制使用索引
来源：http://dali.jinqigfzy.top/Article/details/gtymnstcyw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.birdmap.top/Article/details/gtyorzhmia.html

[Q75] 日期格式化
来源：http://dali.xuetiantiany.cn/Article/details/gtuosgcquo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.tanke756.top/Article/details/gtzkcppwdn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinghuilouyu.cn/Article/details/gtnlnyiwpp.html

[Q76] 按天统计
来源：http://dali.tianlin.xyz/Article/details/gtuswhpkpy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jlsjyb.cn/Article/details/gtzybfoeth.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gtdweqmqzc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenlongwang.top/Article/details/gtdfycdheu.html

[Q78] 当前时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpajpuqtt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhoulong.xyz/Article/details/gtxnygvzwe.html

[Q79] 字符串拼接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiayyeccl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shzxlz.cn/Article/details/gtzxuqquxo.html


<!-- 参考信息 -->