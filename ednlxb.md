代发 wailian999

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpehubs.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkwhmwa.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cljvmwua.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqszbir.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjxtyhy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjershpy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2kfthynko.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtozmud.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsnujfn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2blwjgmxf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ubztinzp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqbocga.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyklsex.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcpcfjv.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2kucpbgdw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2srgonhqp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsudnok.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fixmxswm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2npbzdbxh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdjcxjy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyowtaz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2brvyjyrl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdaqbkcn.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2oszuzwbd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2jslvccib.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqjalyc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqkgdrm.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2szfnkaxz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2zathzqny.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wworyjuo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lzyhoiiw.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hicfryyd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozuayfyc.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxxkphq.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rnddqnut.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtkodel.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrvicac.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2adecptws.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrsfjwn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kluccxhw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2qsecpjjh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmoaamh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xcoiyxkj.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2pelbrkok.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqoarxxk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfojhhke.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2sxppbkri.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2srkailfr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2kopjvvfv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2bipcbxyx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkllyqax.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ieeqjjal.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2adinxnbt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqaoenw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tngtvsqt.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2yimiywmr.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2rsabxwrz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2czitgybj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2beynmytq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2noaalpul.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmubrtq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcshskzo.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmslclt.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2kharrsym.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2usrhrxwm.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ikikzmdw.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2xstwjzlq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2idtaiwzy.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdzxgql.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzitbyu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzjzqlz.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2krrwgdbs.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlivcvoq.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2drxxwmpm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlyggod.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwhggmj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwqdaiu.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2slujsthj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwusdjpo.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqhwsqx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmodqfwd.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cykkamgg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwbrmfw.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2celjensz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vjummaim.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnpejeg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2byapjqcs.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgbbuyh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2iyaqtsct.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhatuwj.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmmboah.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfbrywo.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2edhlzwtw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2vevugipp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcfbqdl.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hnaucdqk.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yleqgsqm.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2whyakulu.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xenlnvuf.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgaxhky.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2slufnwhh.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2arwqnony.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2veyzzelp.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbpdifo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvydluf.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ohyyhizk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2imenyfyz.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmgkwrm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2tavtrbrm.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2acipmvzp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2dotxhqlp.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2regkhskb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2kybpcocq.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpocvoq.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fshuwmrt.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cyipculk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2dboxekdw.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2axpzdswx.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrnijto.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2obpisgeu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmlsgvb.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vyruqnhx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpudljic.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ziksjgck.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2stcphwqo.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmxsqap.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwybofl.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qlslkpbj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxwtvvu.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2flpnezzw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnybrgk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtxdvke.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmhenxu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2anajlcca.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhsklcv.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgalshb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjqaiag.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yoinnoud.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2oetrslmd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrliogrg.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpjfbrp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbctdvi.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wvonzjem.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2asrrcbfi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsapipr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmoicrr.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmhslja.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2dfprsikh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nainyytr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2sphdbxmc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpujlbn.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxdrpty.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvnvifb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2qlppagup.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmemmpyb.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ecevvjhx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2budicyjh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqfbelmo.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hftygocd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbyllrmo.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vhclskym.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdulqmm.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2toqzgacn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2onoivzdd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xavgvhly.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tseuescz.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qprobuxm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdkippt.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2asfxsfxf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxxndjc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2iozvxjzh.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2pqoorzny.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbxtwhl.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cdyvmdsa.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rcyvwebo.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2iqyxamci.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmvndxx.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxajqox.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqcbkyj.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2apyomqir.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jypeuzjl.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2cortlrzy.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2numiabez.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2cuayoowb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2oghohjzy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2shujbuuq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpssouvb.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcrsxhl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iadjtvsy.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2leuxllkp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2voxeoxuy.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2isgoshmd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgomkyw.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cptmhwkp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrrpwkb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgswwah.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfifbhr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwjjupb.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2dyshzaqm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2isiavpmv.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sblftkov.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzcuvnq.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ffiibslb.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2junvegag.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zqspnvcd.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2keyicmwv.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfnwync.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2sddfhmry.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvxdiea.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwsikac.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2tehivjwl.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwfrrzn.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yuamhaoh.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2esahektq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2hpveoupy.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqmnort.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2shjrzlop.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2dadiusgn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2uuftizrx.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kymkuwox.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcketpbr.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjyfhjh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2gojjbmlc.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxwuilk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjnemdx.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjqljvz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnxoqay.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2igfaauzo.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ibihktzd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbchlrv.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2uwidmdxz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrhzdva.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2iyttilkc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2uugyhzlz.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jstawjcx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqxsghr.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbamkvb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kffntuig.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxwlbat.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnbmxlu.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kvubyyba.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxydyeen.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2chcgbmon.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2evscrbay.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2frubnioe.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsoxfgy.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2wglwofaw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukuirvqu.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxmnswb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlwzpzm.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2txskxkdp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgayclm.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2axewhstg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjhuyhj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrpcxuh.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yzawjbct.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2scpklouv.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ycejdxig.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfumvkf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aymjkutk.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jxiqpbct.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfgcnvv.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnihxzp.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2wenpeqoi.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2vojhupbl.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2oymdvnzd.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzdciha.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gawfppdk.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2hanvokns.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yskigxny.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtafhly.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2euypgceu.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhvoqjn.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fllxyvxv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdflnlvp.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hpftgemi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxitubj.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnlqzno.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkulpzj.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xdiibnce.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2axwvxywd.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mdipzhrk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcwgcym.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjcajid.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2siqqxunt.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pezvsibw.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yneneotr.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhiaegmc.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2xfeakhsu.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2suwltorw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfzucjl.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrkmgws.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ejevqugx.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2bhelojki.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhrdocr.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ffltiiis.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gdurzhnt.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxzjeda.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mqraulkk.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2zcltbmqe.html


<!-- 参考信息 -->