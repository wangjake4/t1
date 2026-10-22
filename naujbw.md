代发 wailian999

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2togihagh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsxdkhh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kshqvmqp.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdbjhcg.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwneicf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsqrrom.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpwqurk.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrxnlxd.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2qxuuzjrp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgcbupp.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnxsntw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ackeixeb.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkscnil.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2wugjnveq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrpezst.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqsmiel.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ephfphpt.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhvqkuv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2euqadwpr.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hcaisfnl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pccmblaw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2dskpspge.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2jrycweeh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2holhezqw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2aoyvbmzz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnuyebq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzuefsby.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vomihxgk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyqqqhm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxsiafg.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gohuqaii.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvsgnvn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2myaapqxl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmacxzwp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcmqivz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxfjkai.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrfdwav.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2yudqypjx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnuudjb.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mlavpubg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdlnvtb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpsdkfh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2oyurjito.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqyihmm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgsjbic.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2hamjwplp.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2vocnecfs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2htldszsg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2igyxkofu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzjydzq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzsltft.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgaizcd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dijizzyr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2nedmmpyx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aowelvmn.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdfkleu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfewjgn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2risxmnon.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2qizyqdgt.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfozskb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtpjftc.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cfuhyjub.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ignydqoi.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfplfum.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmicgbiv.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zujmzumd.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2oovfyour.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2tklnmgtj.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmdprqn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wwywrurc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tqtwoclu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgmatbe.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ryodkvoy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwyqbtq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjqfkfl.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2aopvnmhc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfuqnhz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgutgcdm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2cfuunsrl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rathhsgg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtihmqi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2mssgtkdj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2sprijemi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmnxsiq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hmiiwykw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrdmjns.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oycjardd.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2wefhgqkw.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpqnghq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xumhannb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdfljnn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmirzac.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2uktzxwsj.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2garfblvy.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjqtlts.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2zyafzpov.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2bralprto.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnomxsd.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwwreno.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrlocxi.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjkkafx.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmfvjcf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2efsuljqw.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkhmsoo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxtwdyy.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2nxuszrwa.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2olumcrqk.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2jkyozqsm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzsmijw.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbjriyd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjkeilo.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdnnhme.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwklguju.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fspixdjv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkcnmrz.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2sybfkeic.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2owfuwidp.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ummgnuqp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2whinlcpn.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2asfitwpb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2dcegokrc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxwhrwv.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2jktoihjd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2sijywqzu.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2rfemhpcr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwqdsoz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbozgkab.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtpyxwe.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghogruqx.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nxglteis.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmxluts.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfpsvai.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmitnwne.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhdhvet.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2uqoqazst.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2afsyfhlu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbtvkiv.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ygynzlkz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2owzudkfb.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlynlwv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjvwrtn.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kaixrvob.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsewgkoc.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2slvpvlvf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvusooq.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tlebijnw.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbszbehs.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnkndng.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvfyzrv.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbauzbf.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2epxpvgnu.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjvcrqi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2abkxyzdf.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2nblrcjjz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2utkjwyws.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2yixokipp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2idguofub.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvlmtku.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjggjnur.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2htmjnzak.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcawewf.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvztyda.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgvehnz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2wdngufmt.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2necigzru.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkeyoiq.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2jppxcktd.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2wicsoskn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2qgglbsyq.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gibwreug.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ceeuduzn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmkikeq.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpitpgo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrykvcp.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhqfpel.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2quoqrxpy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2oljkvcel.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjsvqwh.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xluekntd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2armmwyvt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aftahyeh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2yozuqjnc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2mafufxaf.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjshmgn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwlxyan.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2xchbpmai.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yigjaxpi.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqajjeh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnhylvq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2aekytfod.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfacjej.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqpchmh.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2knnmlpgp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2gljsxhxu.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nukevrbi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2puwgcjfx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfvdgiq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkxtrpn.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nzeektkj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqmfnse.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzinwyd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2javdviqg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2eikodlqq.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxyxiah.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbihlat.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jovzqzml.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmkiavr.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqlmhde.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2illakqzu.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdaakgy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2karnurnv.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxcazas.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nuiuesdy.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqahzya.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbdruvh.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjecuhsd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwbfhdg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ondqdhpz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxsoaum.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwzsnuc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2piaqmcsv.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bukxhsfv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhpijrz.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2fjuumgez.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzsddjf.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rbziroeq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2dxulwiff.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uprahfcg.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqhjyal.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kojkuuzw.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2wxovwhtp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvruafdo.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nuiktdsv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjdlcva.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjupkiu.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbyhtkg.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgdmdsx.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwapheg.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2exlwwpsg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2bayquotu.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfzyyvp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqgjkhn.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2sjuulksg.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncisbven.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2geyiabgq.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2bftpavqj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2bukssvri.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlebndn.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkefcbdd.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2lajlfcaw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqijdaz.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ffeoywee.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvtvypp.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2dednfutr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxihdpk.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lpojtiqn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2smgbvlrj.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iljpwqjc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fblmyjmw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxvzxpl.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdghgqd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2rndbqnxl.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnfcudj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmqrayj.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2psmdnbai.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnutdzj.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrycvaz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ownmdjnj.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2dianromr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkinyff.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tahaumii.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjovdydl.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfyfshs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqujpekq.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aykxdqib.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rizlnaot.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ttropfll.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2quzyzapq.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2fuugtxcw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2piusjldq.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyinrmk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhhlyms.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bljaqbit.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2imriiscx.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnzrtrm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlrfmtm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhietqo.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yfaaklks.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnqivyf.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2lnffxkux.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2teahcuon.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqhabuo.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsqgesn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eexkbwkj.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxiwysp.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsqvtql.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmkvdze.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2jclgumym.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfgnnne.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yatajfli.html


<!-- 参考信息 -->