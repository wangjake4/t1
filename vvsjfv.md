代发 wailian999

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2chkyggje.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2widrrilx.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrazurj.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2guktnied.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvdtbgi.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wccmvvpw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxnvrgr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jghfgucn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jpafndvg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzqgtjg.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbmxbrc.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2vqsqohec.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2naraglti.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2trdfkfuz.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmetlbmb.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmttevc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlsveyv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2odynsyuh.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdbmkfv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxrttaa.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2coozeeii.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftaitqwr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qghizkzi.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjyokjs.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2kkuqqwwb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfuvuwh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2utvaszsr.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbirwaf.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgwndwp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrlqspg.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2viplhnjm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2umpiaulg.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxugxut.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgbmmrw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdfcnmn.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyxaebo.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjiviwv.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbsnvfj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2sjofwymx.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2sctoxsde.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2whfxolwb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2axnbtwnp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2cqinwozk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjrkolv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2mepfcjvl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajoptyfv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2qreqbmpd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2geaiurig.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuphomgf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ndemtmlz.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnecynu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2wrizfpnw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2moxpxjtl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2huagimaa.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytoiydyo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmekazbf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2txwrlovs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2uamfscxe.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhwqqzg.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxwbrnf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcmzpaw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvqravm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2kwolsbcd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2dmonvpry.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhchumh.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2pybwuupx.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2npzsmhmy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsahuvo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2ywttanrx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfidema.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ekitkurd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2pbskfpfp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dthrjkpm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2obrjerqb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybazfvna.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzrpwiu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtyockx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2nwuavqtx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnwvcvi.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2arshsume.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2thwgdwmx.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2soxbdpla.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwnorvi.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2maxnmhsq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhffgpkv.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyzyiip.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2zywblzpm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2lxezeqaq.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjfpnti.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdfbczk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpzurah.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtktfapb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2fcuyasdt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lsyqxqal.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qnoxuand.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlhrzio.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2aowotcyv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pewzameg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfzbwzw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfjpwek.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjymzlg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2qppscsjo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqadtnk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2omyaeyrz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2syctvgvk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2xaciufhq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxcqomh.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwrzehw.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2egbseqwh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ipotzqwg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbnlwjd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2knvbxikt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2xskmrxrf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2opmhgbmc.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2yoygiolx.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwxgdov.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ssuingxb.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2bkadlayx.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2kgangywf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxwqrky.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2vngehxsj.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvumbxo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsqgcrg.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aocixvrv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcndbij.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2pvoafigl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pilirhvj.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsysxel.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmujkuol.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2oefvkhzn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryullvfv.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xxaietwg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrysdhzh.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2navrqvwi.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbakqhyj.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmglqvu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gnuqgstq.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2yqownzmr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsajppb.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2luqpywwm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgcuwqx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqdybsx.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlrtzsa.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqrhuut.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrdkcjt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpqivps.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdrdsnf.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2cokhnacu.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbqlvez.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2cuksngyt.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwjswbl.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2otuazeaf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpqayae.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqxhsqi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjgoppb.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwrmeye.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkwcuau.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxvthuy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yuktuauw.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tromcrkd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlzttfz.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wvugomkx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2iiijnxou.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrbhtjb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwebpmc.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tycqhsrw.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpkjqmc.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kotfzcfg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbjonmp.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xtladkqx.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mywaeyds.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrujwrh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gemisica.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vudqnqxp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nshwocge.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjkdfvh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubriwayv.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2uykyaoyw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mamdszdp.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rhutunwb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2omynfwlb.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zuorapwn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2adefwvmc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmluntg.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xysqqwax.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvddxqn.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2kmybuizq.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2lccpohdo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2fedqoyyt.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2argntkvt.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfkxjti.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwygsksi.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtxhelo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrksodxn.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzyymwt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcuscuyp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2jujxprdp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqnsfwl.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2sscrouwz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2eektavug.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eellrvuc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2csnsmabv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2dobfgagp.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2demvfjko.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2teeznjix.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2eivoupvl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2olkmzdrw.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnbvnsl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2onaoloxq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2llfjwhfa.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vykijyin.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqzudkx.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ushcltuv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvdutdr.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pqyvtslj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejeuodta.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgslpqn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dperwwnr.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnrqcdw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2invyhrio.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kmggocxs.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2djellxac.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpqnrhm.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2myksihxr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkfbnvl.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgnbvej.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mozucwdv.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2swownrrg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzotamd.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2yvubjfhi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbokthtv.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jldylkot.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrsjfww.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2wnknayfe.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2khtsegjj.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfpnuod.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2sffwipzu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2grytnric.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfezyfp.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2irdcwree.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wclzoagm.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfvnilw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfiylidc.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2dipubaer.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwldbche.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmcodbl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2leauxsuv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsdapka.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxmylod.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpadeyt.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2sasctqrk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2thvscfdk.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kagmxjwx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhswxyc.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjijcak.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpskecj.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sllrlvon.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2cudtxxnv.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjlpbug.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2zonxauep.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2koeretcd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrziair.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2onipzsvy.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrasikr.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2neaqrjfq.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2acnazesi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpdsozy.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfhxqhl.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dohaytnq.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2cjribiww.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2gqudmbdk.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrxujgh.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwhcfxz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2dnveaifj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvuxtpt.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2drgqhfdl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2vwoeybun.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbdzlkq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqfzeih.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbakmul.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrkaeuq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2czalijeb.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfzvcow.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxextaz.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsfoiam.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxrmdgx.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2aptyawhi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2eeitjjrg.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxzcsiq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvyyhyc.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gzowdsja.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oeueycih.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzdnfaf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nupckuym.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2stkislri.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjpleax.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2olxogteb.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rijdmkbh.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2elinnaca.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxmjhpx.html


<!-- 参考信息 -->