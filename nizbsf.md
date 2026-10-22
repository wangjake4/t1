代发 wailian999

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2vxoavdcy.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbztcnf.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuppgrsw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2slumhjwr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqizhpw.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lguhaldk.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpslric.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2jynfuuey.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2awrdaotx.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuedwynz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxeodkn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsofmuj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ipialnok.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2qdeqnlju.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2olgwyijw.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2krsjzwom.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggsfellj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxtfoyo.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2sinepypf.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcaanqr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbasclcd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpchyye.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzsvxag.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrjntql.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gglpifsu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2haixlhms.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ncyjcuxi.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwkxkzx.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2zvliiwag.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ycytcjrq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2prgqxiun.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsxiuee.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2hqknasxy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmxprda.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjtpulc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvvmfbx.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhxbkkl.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2kkozsnrt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnfilmz.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2abymhjkd.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fovybbgs.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhidyogf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2htvuyapz.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vugyteyj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2btjocynf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2rppbodiw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2krolahqk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmharwf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyhhqdq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2hidwkctn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2huzahvwu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxzigdu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmowrjn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2kgocpgoi.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qhowomov.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ubukufqk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgfgggp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqiczham.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rygqegln.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgmukfl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmwbypk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2heydvner.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlnxwzd.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cazssepg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2siankifc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2clwnhxsu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnxscch.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtvukri.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2prubworc.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2edopqlox.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qgejsudr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgmvllt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2qiimovsw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgrkacx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2cvsajhqe.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2upxmhzho.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2egsjpcyu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2acfinoqq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmpjzfv.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvtqdcj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjujazw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2unlwjdmg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2onpyhpil.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrgghqx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgxkitd.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ecijeobo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbcfjbx.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhjohru.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2vonbvjau.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fizqzdfy.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2epuafkra.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhorers.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtwdptl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qghlqzes.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wowktyaq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsslhoc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2fikclbkj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2caktobap.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vftxupqh.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2oqappswz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2imstfcck.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2coishceo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2zwaixsnn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsaugkhm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2aaksdjld.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2hsyrldpv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2spptapnz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2piqfbtfe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqxkdlj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2yguggske.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2guatifso.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2txcenbkk.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdjnhlg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2knyytili.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzallsx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzwbpla.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2hvatsrli.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvduauhs.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2dfankbkx.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2rboovckg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxfuicc.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfztfno.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqljuqq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkndwgqc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbszqsp.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqvwkek.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnejifis.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ofosepan.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2anyarigp.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvrtxmk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnwvyjg.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdfbecl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2logmvfyt.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfvsszj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxsfeuk.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxyhjps.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmeryfx.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sogeguyc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2kswlwsvf.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2czfichjd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvkbijt.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrjhrla.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbvoexp.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2usxsezdg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2pigpccic.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2jllguvvp.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2akozkpqh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpaveyx.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2pitnbwid.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2qorhdmki.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2knxqloeu.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2lypacipz.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2klealtfu.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwzcwaw.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2arygiyek.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdxwsol.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbqjsot.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbwzown.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlkzkfs.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pffbtvdb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2lklxkjrc.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvuyyus.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2acyzdbrc.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2btmzeflu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2njfzmpns.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlsxucz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpolcfc.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpueeyn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyokbldb.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxwdmqv.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjwpqdo.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpymqii.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2yfsnlnwa.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnfepec.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnelqhm.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhqdsgs.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuszefzf.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2usdjiddn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhxhtyk.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2tikszbjc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2chkovqjg.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xasnxwhe.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdogopz.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uqthfrna.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuulpgfx.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjenxok.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xehzwilb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqyress.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2npmjntwf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcstouao.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwkkljh.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjonpcw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbsmida.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgffygg.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxznage.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjiibape.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfvqepn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2znjwklhr.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dprcyfjc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdjgxdq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2vuleiftl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhfdvva.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhevebd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2qjiptylb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eoshfpbd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtrzrzt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfalyjaf.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmvdlet.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2uzucmscc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2mlczeisq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpruubq.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2beoulpop.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2idjbtsgz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqjybsg.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnncbfg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2paulewso.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gipcyrcu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2inzyywvh.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ndyarsdl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2rciqybil.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwyvicg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrllglks.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvzvrfi.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcosgpu.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtbrxwh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2eydoawun.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cftvvlrs.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2nytitiui.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfynwodq.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpwtkom.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqchyjn.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ymubfxhx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxbjesv.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2lwyqfiti.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvzwhsa.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2spszokyo.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnrdvdg.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2senvlrtz.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqdyqbd.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wzncawxa.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxiafzyk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkgwvfw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dienveqe.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gswzlaav.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwkbcae.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrhcoqh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qybvdonn.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2mkeremtk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvfuker.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2eiepwqwr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdwhrbt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sivlqopu.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrwdxwk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2usfqlhqk.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2trzgnebk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcmulma.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lcyebetx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2isvcfvqa.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfhgadq.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2bztbdizs.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ozllszse.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfafudn.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2agbomzxi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcuwlcqt.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjokydz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbmxlag.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2pngnyfmp.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzlaigj.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gydimjqb.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2asezwyyd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2aufqmgfo.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2imyczhcr.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfuvgxn.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2tclhyjvn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcukkvw.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mebixrie.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsywdgg.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2tojtgeob.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2uyaeuylw.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsieoqf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfmcrxd.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ruygidqe.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmezrpt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2nylnuwun.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fhobwxja.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2fctccjsx.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqojezf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2achxisrk.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2anoaeurs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2jzycemvw.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2aykizphy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhrpkpb.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2aivynyyf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvsxlmd.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ookruzdj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2trvijgfh.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfygely.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajllutnn.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsuftwo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtkrzbn.html


<!-- 参考信息 -->