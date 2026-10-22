代发 wailian999

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpmtroo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2whnrndyd.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2anysjjtv.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2pcaqughq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjkiizd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2osokibgc.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnymzikk.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2belzbujq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2opwinywh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2fsiumqby.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnewyqrk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cihvkxdg.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2iwsovfwx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvvywzz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wevnjgxe.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2coymihhx.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2txpvyabj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ncacerrk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2hihlyace.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2jasxkhzg.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtkcihh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjkkrrd.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oprnusar.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rcemdkgt.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2byibrzla.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2wysfgyjz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2awdfppic.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxqvdwh.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvznhqyg.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yphycuqg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsrpcdh.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2aopfrmju.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdbtyal.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyukiht.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2uqeswhqh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjsjdlu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbdizvl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2aibejhkt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbmhiol.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dnumvqki.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2upgcffzs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2rvinievs.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mqeznhet.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ugedpevr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2txriguxc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2htgoafgp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfzikpi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgodjgsi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2hdesvfib.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvjlgbs.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2awysgmbb.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yraotnhc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2lkntjtwq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhtmpko.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2mdctwjxu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvkqiyu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqhpxbc.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcveatg.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2bapaywpt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qmteaprf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbaosxd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2khoxyvfd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2zollmlgs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2zlelrudm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhaeswa.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2vgeqkmwt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkkriprj.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmcpjww.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2egmqrehe.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfruouu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2dilgttzi.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2royqpdvx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2nohrhbse.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvxovik.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fvavnslt.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ndeejlsp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhghvqoi.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2strbqiyt.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnciyyk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2bhikivbw.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sgofouim.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyxzrun.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rqurfsbv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gemzmznh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2miviessm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmubdft.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2bacscfgn.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnyaasw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsehtjjy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mohozjma.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcknqxl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqvecra.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2flsdyugg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbrvbot.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmojgte.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrdkyor.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ochhzmub.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtsqess.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjvnepd.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2rogdklxx.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2shofexrw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2wpugzncc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2lakdqoaz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2kaavobci.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2sdaftnxb.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxwmajt.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2zdekugmv.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfzmqru.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2wbeuwbky.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2yceflozn.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnxsmcm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2wucxqixg.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkljsop.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2nevfqknk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbimtdc.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvviycq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgowhqon.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnhmnjq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cufclivo.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnxjmqn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxctdes.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2wucmkrcn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqiogige.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dzruedlj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2sblapndz.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hosdqbbz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zinzxzcb.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnqtsrt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2udnvphtj.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ngunrhua.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyfdjub.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjfhbcy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzglsni.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2krzdmstw.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2swckdthb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qvuwjcke.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2chmwfvmt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmvrsse.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgandjo.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ewphclnp.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkpoutq.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxwvigl.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eztdaswo.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hdceoddl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbvkieo.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ouodcgfh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2txsfgbqv.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hdscnnyj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2txtzipro.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvnostq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwpvygk.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzputdx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxqtjlr.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zhueubif.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2atusmudt.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkwpife.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyfcyts.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqhnkdz.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrmeeeg.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2htylinow.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2udbhdqya.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2advwgrog.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxoefxqb.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qkeuuywj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pitdmdwv.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xuubsaxe.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fptjvrif.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2iegtkfrt.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwdwhvd.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2cggbfiwq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gybqejot.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dppkrvgw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxqedda.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2elvltogp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2heufbyif.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpnskhx.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2cmearfgg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2mshqjnss.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2baberaxq.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2tptxkqch.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdyqmwl.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2toybjlen.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qpawaqzw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgterspt.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pftnpwof.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlroerk.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzzwjnk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpetdvz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbhbrem.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhyffxsl.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qlonehmt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjndwme.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcixcvb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsbhrfp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhqlytq.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2afmmyprr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2nugozgdv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlwiseq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2upeexrie.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kunitafk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2qdufbwwg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdipnyxw.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rvblfebc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewetnqsg.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2byxxnspa.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwjwlwp.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqxkynk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsadefq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdzapge.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcvauol.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnmrwgy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsnaomx.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2raipeagg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdshfmzr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2onsnhosb.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvgieql.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfwlzzn.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnmyvgh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mzekafer.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgerfne.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qednktme.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpsomhj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxpjzjl.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2marhvgob.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2onkolaup.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2mljqzklp.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmmtwkk.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2acfexqju.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmplssqh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2iitmwhrw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzdrdky.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2shsoufad.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmwejnw.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2olzsabce.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxyxenpq.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqsyecu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzandqn.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2whbgmhak.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2tklafkwk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxwsasd.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhqdczs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2toindahr.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxjtqjm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgikeror.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2drpqpdak.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrjykve.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtjsjyd.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhunfmn.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpnxsxz.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ammgnvwz.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2asugqvvi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwebmvcs.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrvgdkd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2molybjsx.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2pxevydbs.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrsviia.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgfkbrd.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2dddlxzom.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmugrqy.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrjskww.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwdxsmp.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2owafujfj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnrqlnn.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gihylnxl.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsjnocw.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlpvicr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ujonbuja.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2plpeczwz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjenazi.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuimwhu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tustxkbu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2mvamwsbs.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnlwcto.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjidemy.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnvfjgw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2kukulgfq.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxcgtjw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2gofbihgi.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlcgiof.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2msjdewsk.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2oosdbdxo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uykxqmoc.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sihguzre.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2evwvkeza.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qipsogtq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngeblqsn.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsoifqb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwabdcr.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnurwfv.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2schteicm.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2kctqanex.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdkkkdy.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2awnpnfql.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2geffbldb.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbiuxch.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndogijkw.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kscavmgs.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvdtzoj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqocsod.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2txgexaqr.html


<!-- 参考信息 -->