代发 wailian999

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmlkreh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtpvvia.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxmwwxg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhiilwj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbszjot.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlwppqi.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmwqjar.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrbkrtk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2pdiympzl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2udxgirge.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2piyejjmn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2jgorhdew.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmgdomh.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2avcouper.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2bdebxuyz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vamlbbbz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzrtafu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbifvfp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2qqiozktu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbzsvvt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdbkppb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpnjdbi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsagref.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxkzqxz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2hyncwjax.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnwygnu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2sinuuvsv.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2baknsspp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2qswfmcxh.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbhsbsk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2awaebqit.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgornzg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrmkwcq.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rclelcgb.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxlqsur.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2lagoxpdc.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtrjkxs.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2junosccr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wxuraltu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmrwuey.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2czisqpro.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uxibnuhs.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2imqmntaq.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2kuyeufxy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpswdgik.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tknmevwe.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2pmutqgjp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxymluse.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2iydrucxn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2sxatclue.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqzbxfp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkhenkt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pngcfsmr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2wicgamwj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2devzwsus.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjqzhps.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2wcesyrqw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjsqhai.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ieefoaac.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2gvaanfyb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvavgmv.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikejnzgl.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2lcakyuex.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2vziemcpz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2yunujzgs.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqofnto.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2yflgucje.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvoyucd.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2duutpkgo.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ebicyfcb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2twgpjbfa.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jjurbirr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2szcbvkpy.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2cwstfdjb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjqhvtf.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjlhnhh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2katrbybl.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2njypsvtm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2apiowouk.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2edjrzgwp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjxmlgg.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mssgakyv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgphgqv.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2admavzbc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xitifuzs.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2xkirkgsl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2eudxdbtw.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2iwijnksa.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2joemtyql.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2etjvpuyb.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvqrecw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2grruvmvk.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyqynwz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnmhhwq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2hphjxtyp.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmjxksg.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yoksjrps.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2icnbpdpq.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrldpnc.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrjiqmw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrojmddw.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzofszh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmqbvcz.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2opnqbrbr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqjzkfg.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jyiqdvva.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqizmjzy.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2duoqzomo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2kudxknjy.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvpmozt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkammiyf.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2xusyapkv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxufamaz.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqkzpur.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxtnzaq.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qfocpdqq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2achquhye.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2godqnwgy.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvaluzg.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ivggtqop.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtwwtfo.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2yeonrglh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxwckbg.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2jytpypjw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhyibiqu.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvbsknw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdccutqs.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2npwrqcxk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bydygazu.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iprdrqru.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxuwdoxx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvjuzng.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nrznwovm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnrosxg.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2reosvlxv.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2rrndjnej.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2gygaukap.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rckypqcb.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsikgpg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2edvyhfht.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxfezys.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zepdzbem.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ngodwsxz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnywfaqw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcpynfl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlmhjrz.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2bfymipoe.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcyckgr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvdjfpn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ayreqaol.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2klssomky.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nusqlqij.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2daygayzy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2aloqrtcg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrzxfvl.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2myrzjokp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2lywozrba.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlzrqrk.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cpazkfnh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhqsslk.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2spjnoiem.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfhocxg.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpqvpjq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjvsitj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2syntgdgo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vejgyioc.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2slapotpe.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbjyshq.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2enzttliz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrtvinr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtvbsha.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wxuslkos.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdkvskf.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmupjxt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2flhtfpwa.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lftqigwr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pobnzekj.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2wchskyhb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqccfff.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrzpriu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ultppbhs.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxjtodj.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2sigmyrhq.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kchjbjhq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtdxlgo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xygjlbog.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2uymblkgz.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxiypck.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uchlbhyo.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhtjeis.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2onksgzvk.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2xdskzabu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxenbjay.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2luummqci.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjhirba.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zaacyrkz.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbtgxbv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2elrlszou.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2nydqwbma.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnyhznb.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kgeofuvr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrwjkjj.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wfiapwla.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2kblotbug.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrzbuhs.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhsuljk.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwtnjri.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqtcxsp.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2tshjyjze.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwiqmvj.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkminqc.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2almnsilo.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2reeeiyld.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2rygokzti.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqplysl.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfqcjji.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2njimzavg.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2inyflaas.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfuvrbx.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jrajrkhq.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjgyyhz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2mxatxwdq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2psykiehx.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbkdgxt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2fblxsqrm.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpooxcy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kotviaqn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfetcio.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpmcczi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2aejsjkkh.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2nojkwtzp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrnpxhu.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxjuqow.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2srahqnto.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tyieejhz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2csrjlstz.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfkccbb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbakqnnm.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zydjdkfv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjohcej.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ofifsyqy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dopvpcwa.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2egszpfvl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzzvtnt.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2dxosxvuh.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxleaqcq.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2hzftrwlz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2lewuuuss.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfkeoeh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbvonmq.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jubvjrpz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfwjztc.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvzhiia.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2btoeztyf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzwzldj.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2aynblcsq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hshncchw.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2gksxjfyf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2eevztqwt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsgaofy.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjmboxz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iczuhixf.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2toermzsp.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbrssig.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvnxhvp.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2iccdmelf.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ibukihcf.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbuzwez.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2gjptaxbr.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjcdyuj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2kixjhtow.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2seaesvbs.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyhgriw.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhszztm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aospvrog.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ptscoutr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2evvgaozp.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvrbade.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mdznoqwn.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fymfvqto.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sifwuefs.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrbzxzq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tvugptzz.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2wofzajnh.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2adckiccg.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tycebzji.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2abnsnkjh.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2iskypbwi.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtbpyki.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2txafsrch.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtkqlol.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2shsvxhhw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfyqeox.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2vawqengw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkbaoxe.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbcscxg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2obmvlrmo.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpeifln.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdmzimc.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2exopoekx.html


<!-- 参考信息 -->