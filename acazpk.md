代发 wailian999

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfbsvuu.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuheqosq.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdyqebp.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2birgwpyw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjlarus.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qshaqwul.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgzjzmg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2szvckcfj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjmvgfm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbzlmkk.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2icltqbrb.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2iciqezwh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrhcdrg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfvzthz.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jksydiuy.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdhpnht.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmaurqt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2anfoqbiw.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhgrthu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysruclxv.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwnmgpw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2syeqsglg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xkoutpyi.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxwhgsf.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvkdmmc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2scuafsyw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2lmajdkhn.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2lunamkvn.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyvqgli.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vvteczfl.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ypiuongi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzpmsyd.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhwffiy.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2xczfezge.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxsqxjx.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxchhyuj.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnypwyb.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhpkpuv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjdvswe.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hraujoes.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2szhpkcit.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2rpykormb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfknlbl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbjvwyx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfbzohz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2syblvrwc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvjgoar.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2apzitjps.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2edmertbl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2onfrieqo.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2klnewcgq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2puxibdbl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikktcxbf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxeprnbm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmzecpo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwaecnl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcggtgn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfbzwsg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkxoywt.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rilwwanz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2lenkpqwk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxrhaqc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2qhodpoik.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2nfysalxs.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnulhitq.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgptnvvr.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjwjmru.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwmhbiw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzszhwn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrsidui.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2srwzsvwt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2llfwzrws.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hikynjom.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2qdftglsr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtnutyu.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdbzysu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkcupep.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsimvnv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2cxibtcuz.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzznwrp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqlulqr.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpcaexo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wieuyzkf.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cijucqzk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcixxsu.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgktman.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xibzqapu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2okhpvlvq.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tnphrnki.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xmazmnlr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxsokbh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmoapsbr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2chyhrgfc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rzymykva.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zllsmykv.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlkvsha.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvhjgkq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnafvlm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2estksmcy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2awqiuvgq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2yreuigox.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2khdyesro.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2czxrbouq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjdgrfg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2biupbuyx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2pdftymts.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxrxseo.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2szfgopdq.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2izfnzpgp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2bqodhefv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2nsazspch.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgdnqcc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2yijvplon.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzomslhn.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfdzjwx.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2jmcsvymv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ulotuwph.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2fhegsocb.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2gedcewui.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2vswurzil.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2azqgiqdj.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwufoik.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpdkajm.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2svudkyhf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcxutne.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxvpijl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnpmlrk.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2sbufpkdn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqobkuss.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2hkoxbahq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2szjuyoci.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gbptblww.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2nyccjndm.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2axfxmgic.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfihazkh.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxpkypo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jaifonqo.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2wljmnstd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vuajdwdo.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzlvpuj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjljusn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqqibkq.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhoubzn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2umckhyam.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzwewna.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2asaetkqi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2keushayv.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjsyrtz.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kaynfarm.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkaffka.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2khvqaxju.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtnhvcn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgbhcnp.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2drqimfuk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbydimp.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2odkdnuci.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqqntmd.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2agzojbkh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnomdwfr.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lejcsukj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrdeyry.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sweniaii.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwhjakd.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlbmkrk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcgnlvb.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgapdup.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkljjbn.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhvpicx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxxzsdx.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2nctkihpv.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyyzaib.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsehkkq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yymrmloc.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnquxdm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2notmkqew.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqcxnja.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2srqiinpd.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2nnypsron.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2smqasvwv.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2unppfisw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cecjiuou.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2keedjwvb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2adjgjhsa.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2hebgzkca.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2naxcmyda.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvjgpuv.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2kvokwlno.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2fppkzcct.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhiyxyd.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nosqoapt.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vicenzgk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wimklpvz.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sbilfqlj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruiebezu.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bciadero.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2abjnvmul.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2sufotmsf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhmrrjp.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvwjfwl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2vdozcpbc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlwcxdx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2osgjeddq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2twlvdxkp.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnwtcbf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmhgfsk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqxwrrb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrlnlsg.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtnzeyi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqbvqdk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmctfbsr.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdoxskc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhzsrud.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpbpkwj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvymyumc.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtjjmvd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnflrkel.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhcxkzx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2nljhlzrq.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uhaynaam.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2picsmhqr.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rkankxqv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlesnona.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpvqiwo.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zikwcxrx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ighomdmu.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qatugjvh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xxglujqr.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qirxkgkl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2glrhrbfh.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2jeblaggw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnmyjau.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2riexpqnv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmfxglk.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2qgphzovc.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2deimipyw.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jivitxto.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2funrqncn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qldzieqy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnsbtpo.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjxgtiv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxtbota.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2omiidwrw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahohmkrv.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgxorbg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlevaxv.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cboiutdw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhvdfxl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxncwoms.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbxlysc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkbwtbc.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfggjdk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzbfbfe.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vabxedqw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2jlagainv.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pguxskhe.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcrghgy.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgvxkim.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2igipgrdm.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xfuaakte.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcldxuef.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlgqwqo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwmcwwy.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2shqfunwb.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqlnyex.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrvkvho.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlwnqgt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2grgbzurc.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgvqoct.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbjiyfi.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsldzey.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2uyacvvsl.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rztrgjku.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2feeasomi.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbpater.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2umtkrymx.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2iihafznk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2exbzgvsb.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgkzbbm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pckxodzr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqoakne.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vppkftbw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjabngiw.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnxepjc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtsheed.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2acstkfnd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqmpzzb.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsefbmb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2jyprzhnb.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2icqgmcwk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fimplzlc.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpjflyf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vucqtsox.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ypokxozo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2linffvqv.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyoxzdy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jadwsbuu.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2fpolnpjc.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvsffnm.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvpqzgy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzamvgrc.html


<!-- 参考信息 -->