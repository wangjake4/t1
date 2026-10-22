代发 wailian999

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvbabrt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tcebityo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kibgyjka.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzigrvsw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vahvactu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjogndm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxwbtmb.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2klcpszvm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcjtjke.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzqcbfv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxkzgli.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzybmis.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcblkcw.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2edropppm.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2tafmibns.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjxsoai.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2eansxiey.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vhejgook.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2mrltmbnj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmyjtde.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2odivofer.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2hauultvd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2utxmwciy.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2qgccvfqo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2kbuozcvi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmtqdui.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxoxaza.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rofkmdhx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2rqryjzek.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjkssme.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkupnfn.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnzxhrl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfrnlrc.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yijovbrj.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2prgoavlw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjhdquh.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbpwiag.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eafngogh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2plaujbbr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gunilapc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2owmnajnk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvzgspj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jakookrw.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2uackvzhy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2epqxdcac.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnwumou.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkhaltc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2puxiiolk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2pghrueso.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2gticdzue.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2glzcujkm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkfopqy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqdlsuk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbvnawx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2coojaplo.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjvmdvk.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2uipjkvto.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnwlbov.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kehjjuuk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2swpldaxi.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtdbahh.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvuuuynr.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxyqzdg.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtxlyyv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xolbjgmr.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2lsegatij.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2spwcxvlt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkixjilp.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrwfqsi.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2suiohnkw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tftsposj.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2phbxrjmn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2osdynsfx.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2aipwvtik.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjhlyhh.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjwqeyf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjuqwja.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvdsmxn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2etfwhbqe.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdbnzqj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggndzbez.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnpotfk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxazqfor.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qmixzwhf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyvqlgc.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2drisapmt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdlfili.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2lxojijpi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2arbfqico.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqdyjgz.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2afykkqql.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fimjhsrq.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2uygxoilu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgjiemv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlnusrf.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2fdflczlu.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cehxfnuy.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2adgwzmtm.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2obvrihqu.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjmmdbv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kaoxqcir.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fppxlqgm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2oyekntap.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2etkisglz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzownft.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgkyucp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbpavva.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2sddkrtzv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2uowauzxu.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxovttt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqhooqn.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2cyebixvz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2fembayar.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpnceqw.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vccbzopt.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnhfgur.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2tuycdjju.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxwidlb.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltusnblz.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2suclgcka.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2njtbijei.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjddbnx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yidqagha.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvplpxu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlqyxcv.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmqlxld.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkokzotf.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxahwbc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsfmliw.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfngpfj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzfrbqj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2lkckgncg.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2cirtbjic.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwzksjv.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzmuzim.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2rkidvtbu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2sccmpjid.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdkucnb.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2frgyokde.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzwfufq.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2txlveatn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qccywkxi.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkeovzk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2siwffrok.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2mdiigaqb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdvmpqf.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2bceefsrm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqjodwf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjslffna.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2itoglvmh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzepvzvb.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gsydryei.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnwxjsy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2rqyirzeq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcpbyvu.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zaplzowq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2jkoscydv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvpuurq.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fobpsihd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbuuuria.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2phobuuxq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmozmair.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mswddqnp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jogyuhmt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcnbvhj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjuemty.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eyoqeeio.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuojmbdj.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uccrebft.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjywwrnr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xoszhbcu.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2yguzwtle.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2huguascj.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwtwnzv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnnlbzb.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrvvzoa.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kanrtgqf.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjlamoa.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtdsvtg.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2biygboqu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2dfuketfr.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdxbgyu.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdxbncj.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2rozhvkvw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2adosqwia.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2egoqxbes.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2mprtvnem.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxiixju.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcnxcgj.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvzumqv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrxbemw.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2rgureono.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rozwgese.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwkojtw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfuqjpg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oonbcrjt.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxyfmhw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2efkboqks.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbcfxye.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovyufubs.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pxoaxcxh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2qillbddl.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hcurhqgc.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2rndvcldf.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzkxfcz.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzrxhrz.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2joienxep.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajruhdhi.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbxoavm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmtvqmn.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpdkuae.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvuqchgc.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzgzhqy.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqmgpzz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2qngxkagw.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ugagdaye.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbetjmny.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2vbovtnvm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2vrccmsdc.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2axcvdvsp.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2immyqahb.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdscifh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pazioigq.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qepnqjlm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2armrxfpk.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2issaityu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddebjfnj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqcuhir.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzslhyd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgkmkff.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2txfesgcr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsmqphl.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhxmkqe.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2smwfsnnu.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2sxakswlw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2obedsghq.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvqjimj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpajqfq.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fczvgxdu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucoardhj.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wotjvrtp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xycabytf.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsmjxim.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2easvyiby.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2irlpbkru.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2skgjsuyl.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpjjuhi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2soidgqwp.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2bywpfhfv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxgfvdi.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2srqqjtal.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikexyerc.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwisdis.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2himdlimd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtroernr.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mhuhmsgp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2sksrjmty.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzlhcoc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gurqocpz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xorxvadt.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbtnjmh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzkfpec.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2elqfpczb.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyqifth.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2inwssayj.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2naremrxg.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2neehamab.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2epznqgdy.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvjvtul.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpinpju.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvppjlle.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fggolqay.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2genrmcfq.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2elnioboq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlbztqm.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gkstewwa.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyhvrfy.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jfouillx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbrqnem.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zxprhqdu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvthrfg.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhrekkm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqwndea.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2wskfwrgr.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2spudqygo.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlklsggh.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2arjwzqly.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmzcvxq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2tasfaprm.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhqvdyx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ddeyxrgp.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2oklmckmj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqmnbog.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxbnglu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wslhpzgp.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxadbsf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xpryxhxd.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhewlzl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmybuyn.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2keioqktb.html


<!-- 参考信息 -->