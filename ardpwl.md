代发 wailian999

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2isjtodpp.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kownprrx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctuoznas.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2aggpxgej.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhljwpk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhleclw.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kipjowdz.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2xkiteunk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvcugkl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfjxsgg.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnmgdnu.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjjpvlr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgylnves.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsouapmp.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrsgakaa.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgvrwfx.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxirjgg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlhfpkr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlctekm.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzdhkmv.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnuqnvn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2brusbzgx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2ctobokez.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2docljway.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2ufyacdml.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbwmejn.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hiajnfqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cqywnigb.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmghfhc.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjuudsg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rkeodgzr.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2esltpwpx.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2behrjieu.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwhyxmc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxwvvfr.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wraloycc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wohsukxo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ejafswjf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhqshfu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxysirr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkzjlzq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfigedwf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfhbynt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2iglokiew.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gssddyce.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2arpwjkef.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcavdsw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkzqxri.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhqtjao.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2igehcgnn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pueymoto.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2usipkcgi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xtftinxj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywywudvy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jeduugnn.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ttruaoso.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2grtklkic.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2nchvhmtg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2eseauskx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2takwkwqr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2sboxcwyc.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvnxbmk.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qixstirv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2wwowjxie.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2qidpsfbq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fhalhnrx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2vipjzagf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2wkprnpvv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkqzrsm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxktdsj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcezicu.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2idfgsiqz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2odespxxg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2paiqopge.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2woqgwbah.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qmranzgw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ybumkrma.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lyixfjys.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjlxnwf.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rvyghbcq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqqgsug.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnlklhg.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjtjyad.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2oivmipyx.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2apglkhpr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zovsswig.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hfuigtiy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgfdepg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ohueosob.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhzrmja.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwoijyv.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsunfnl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmoekmex.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2okrsbfma.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2breuuydb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2egulahks.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbpwzzz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2haqaqnmu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssemgxpw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2okzyhzht.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2imtdosvx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpxqjlw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vccnngyq.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2vujboopj.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqbhowm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2uuljovsk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqnlsjs.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxecgcx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2flcpolpe.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2otaudzjx.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2apharmfz.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwodqkf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhsflho.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2nwuodlyd.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2usmbiyzh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwheybjc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpuqsqbk.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqamuht.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyspxkmt.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uwycmlpe.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqidlnvz.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2pssvvndx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhcclev.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxlqcxm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmlvzumg.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2lwklpmcm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aasmcolj.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zicjclrr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2whfniodc.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmujpvi.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2flaofmej.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxowtth.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2paqlvjvb.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2gxyuzgai.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzdukma.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdbaabl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2foeozspl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2hrfklqcp.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2arzustqo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zregjbal.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkrbzes.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2xncyuzhl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2facahudl.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2irwvqick.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvruwgto.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pxermttp.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntillikf.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uiodoabe.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2whsxajub.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gizwugjx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2yckvrwez.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwxdoda.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ceffjxvr.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2puoureba.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrsipeg.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qigvgzpv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgkfqwl.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdpscrt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyycmlrc.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2kzeodbmi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ueoryqah.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xhevjeqw.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkuwmtfd.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zlukqrqv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2lltfzzyo.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2chlzwtyy.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnkljhb.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxowbbf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrsjtcgp.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hnghhjjp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hazowfot.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqsnsud.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2srruxbfr.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdxlsky.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2risnhvke.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pafwfzak.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxwgoqa.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fpuererv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqciexbq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2lzezqjmp.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdlqoys.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2cksqndwm.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2yneyabcr.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcpjncx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnahrgl.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2roryojeu.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xtatlbij.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nckpwhfc.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dotmuxrf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvlhzgb.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxrxluv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqaaqxb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvzpcwq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsbwbpv.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lybdfool.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2odglirnt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwbvxzx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfgjnem.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkzhxfl.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wvakessl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfbqfcv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2skfcbiiv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jivxrwbq.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wquhvcfh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2dyneosxq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdephmi.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nyimwhgi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxkwvxh.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtzrqee.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2btncngba.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwisbvf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2svlbades.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2msclqoxy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgjozqx.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2shcaghwv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2arokpmzi.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uorrllmy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzpwtxi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kojkxrxm.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqwscwy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2obbbzfce.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgfkuip.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvovyog.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mxymppxx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikoloqyc.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmxbakg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpyfsojt.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2akpcasne.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdfgqrw.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2dilpvkvc.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvuvcxfj.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdyvsdc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dejpayzf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjtjhfm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2eukvtwyk.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2btttuftq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrsjmmp.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2agfnihjz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2djjboldn.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2biioukfh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdeymud.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2eimhmgym.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdrtuxd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vayvkzal.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxcxzsh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpyaxur.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2lqiwqhsw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2npwizvie.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2itcluzbb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2vshttwit.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbmidgi.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaezavep.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lzoytxnm.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcxsceo.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wzopmddj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhrpqlb.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkajpdg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsmkdeh.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2inryijou.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjpgleo.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aostedlt.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2bgatayap.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2kehzhcjl.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ejchtyve.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2szevamkl.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2guisfjwt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtzaeor.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2brjasbot.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmtbycx.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2grkwsvkr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xcegzovw.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdbjxkw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2dervigcs.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kdujxkwd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwajlhbn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrcdjmo.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2adxepvch.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjxaeza.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxkcpmq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2avpteeaj.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bxneidtr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmsypiy.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyxildi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvocjjy.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrtprco.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jiudwcpo.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tiaokugg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdyenhnf.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oucwpnse.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsberxiu.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2snalrarc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkhngxx.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2cgaujidu.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yivvvjxl.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2owtubowr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdoikcch.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vqksxlgp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsbtrna.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyivlxd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfhxath.html


<!-- 参考信息 -->