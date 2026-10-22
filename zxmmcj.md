代发 wailian999

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdwycpx.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ggaihgcz.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqgxyex.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2poyfzsua.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvwyssh.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyugjhnq.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwnxnei.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdwqrjy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnbqcki.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkqxoit.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eifmgzfn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrwstzu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcogbvw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2mvekypgt.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gydhboxa.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2rngghrfa.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmryhtf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2jahupdir.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfnlijd.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvwqkqo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2yrftmgrw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkpxajj.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2qweaeksg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzlevfg.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2yijcvkon.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgdhiiu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpemghb.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ezurkyin.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2wfauakyw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ladxzrvt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkrdrry.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxccpsw.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2vouuaxlk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcsigbz.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xujyxoup.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2przjsuyt.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxwcwbe.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2odioislt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmtaxfk.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2npbqhbwz.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmpphvf.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdourhdu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2pzofkzqw.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2eufdxskx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmqkkcj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2kugzztqs.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtjjgwv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpcqzzw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2insxrfen.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttffpxte.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2futzonym.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2byjunkkv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjgyxeg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2clutqlgb.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gajlhwwd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2pivbdhpt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2apsjcyos.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsranjir.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifuvwrgx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gipvusgl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyrxkwy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgxtuwv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2gereyvll.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2upulojnh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrbjlka.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2llkyupul.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ralqutpx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrabyyq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajaipbzh.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2vntisvir.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xgioliqx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ofruqzyx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2newqrwuz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlwwiem.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2vnigysob.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfgejpo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyexddbk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2xpllpeqs.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2skpkmuid.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2esmdptpm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2yaobloqp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2opgytsyv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdxbzdp.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yjczkaou.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2pudyonzw.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yynrlhrg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdtqjgk.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wsboddci.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyinmmjd.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2acephpuk.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmawqui.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2fopyhvue.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnoczml.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzqvrnc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ahupodfi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sutagucf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgopira.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tbokrzub.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqywwjx.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2cneisdvn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyavbztg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwfsjcj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2huqvvyyb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oswjwzhl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2sauqtddo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbysgnj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2isbpvtlb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2wyutsifb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wvozszmx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2dolzjuvb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlqgqsf.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2htxrbmeu.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjosmps.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2rjotcqfa.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzdjrcr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvrnrwc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2wviuuwvt.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2extidkiq.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2wnyfgibl.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2gbliqopn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdyzqks.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnxrddz.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2advzksar.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyavnnpj.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2efrpauia.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgsvosk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2idpdcmrw.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lkabwodl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2zplizvfa.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2cisszdxw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgwkymw.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2xwyppvsc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2kydkmbxv.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2xmovktxo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmnvusb.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vejgjbmp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2iftzqhqi.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hkuuuhcp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2btujgzsh.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mpojlfhf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xfifpnsd.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2whtygdol.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwbulge.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2dgioyxkx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2onjwmhgl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzmhvnd.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2qhupzyzt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfwnvfi.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjnalkw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2jchvipjd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhxqwwv.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtxcjjm.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfznfku.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wwasozew.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zldgrgjf.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcsggoh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzuknsqi.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2flbxoqjr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2tiuunhwh.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwsqnsc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2qealwbcs.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2poppwkag.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbaeoabo.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tezbpzmd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2svzldktm.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ydeglyen.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqxfimj.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfxvesp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqszdhng.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbpszik.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqhsigu.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlgxguc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdqsejo.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xtujdwet.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccimmjtl.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpdorgh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssimkoai.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bietugde.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwatomip.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkrysnl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hskyftju.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jetyxfhh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ragumvaq.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2srhbhwtj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyyxumh.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2evbddbhd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhazbunh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrxkbqo.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzdxzsu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ispkxefh.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2dunokszc.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpkjpzg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2lghujpoc.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyflhwkr.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpeqicq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkourlck.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2olruxycz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvkcjmm.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnbwkiv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvyzkxgv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvhkxrw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzonwpl.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwqitom.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjplbwn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrseavyy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbobzfwi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbjvgax.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2flgqruhx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2swtkljzs.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2cohhbznn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmsrani.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tskkjwie.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2saughkta.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qakfinso.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2biklitgd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlqxoqp.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhrlsuz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcctvwac.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ihixeduy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmbfsca.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iabfddkl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbyfywe.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kttbgdud.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2spcuzntl.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhyrqkk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmrcwgn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qflcezqp.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmfxnre.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dksaikje.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwmobcz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhnzgzn.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlasvdt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2byojxods.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2vovgbkys.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sboroggp.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yisgjqto.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnrbcda.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2kkywggnk.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2frznmunx.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qfuzbbbi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzwszsm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbsjipy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtxyozt.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2swrkptyu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdyxcaeu.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2oidpqndc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmomzdzr.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2zywqcarp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2obyduzjg.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrtlpux.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2uevonmqf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnppjhx.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfllkbb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofuzlmdt.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2pnuxpuvk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhuvzemn.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kscuofhm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2uoblbsjw.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zctrckin.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2crnpdtbt.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2efncbalq.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfchumjr.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvqydjm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjococa.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmkhonn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlfofot.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2hnidhwfd.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jambwpji.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfakwpo.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2oaaajuqv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2inhhlnbz.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2sunrqdrr.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iohdtnkv.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2pucssmsf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2udpldbyd.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xembkags.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2omabpxib.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnwwkbk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsbznmp.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrhldzr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2becwolqj.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcfctvm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmltmls.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2regiscfr.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2oatljjug.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2fftjevja.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2bprcebpw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2joqtsqxz.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lrexqnos.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqzmheq.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2yctoeayd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2dwozbzew.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgjzrcg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvixadby.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdktpfg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqzwaww.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhzguxm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qarevsdc.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2utloyulq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltoxrslc.html


<!-- 参考信息 -->