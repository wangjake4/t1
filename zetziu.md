代发 wailian999

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnicdhz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjajyrd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2klcszdcz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbaqmpzl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vfoiamzi.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2juvfdxro.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcvlhgw.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fvyfvnxo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ddccdgyb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2kqopxukb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2iecwabqj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqztafc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2synojkvo.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhefkdga.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjncogp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjnsppd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2klfdddpf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdthlaf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2vgipdkzd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2imjwsgec.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpbxsya.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2gixowtix.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fexacdbj.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2mjysfnak.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvzzmzc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2pundnaxv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgrinni.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwqqmvb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2bknzjwlf.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxpislp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lvddcmir.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwskwnn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhvsuuo.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zixmpnhj.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2tsshoxqa.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbfayhl.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxnsmxo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwaband.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmjmksv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdhujeb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2qofvvcyu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rccrnenk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbijmke.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgqftgq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntsttxdh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfuwhcrv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2rnsszrdw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgmpuvx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2lypgvfwg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2bqylvfpi.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrhllqe.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2okmpmyjb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbkptpd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2tlznpsse.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpgvnln.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2dscvrpst.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkygpam.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2diefrgja.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jauhzvab.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnwzcqt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2sjypsjzt.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2hixfyiop.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2mkknxevy.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2irfypefr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrtsreb.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlhritx.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdeinnq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2bncnmdda.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2yphzpefw.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2mibjtcgu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2enqgyjyo.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpjuwth.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtabnyi.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfvjdxk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzkiusl.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkhhaeg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdoswauh.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwbcjlx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2alkftist.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbojcau.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2dobpxuxv.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nzldkeey.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgpcqqk.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkmvnyj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcmpuqo.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfjpaof.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ohftiyjj.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2woauyqpb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ebykvbgm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2amqdwmbn.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2hutdldzl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2icdujlch.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpbcvtc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlyshcq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnuhlpa.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ebykrrzc.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qknfbckm.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxgovnx.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpeofier.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xalkcaie.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuxfypp.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqmrxfh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2gheifeks.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpsdsed.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkiuezkh.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2doefowpy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jniynzvq.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qeofzokg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdxczha.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgxgjuy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2mewlmvjl.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2jlavexrk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2hggtfllm.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnyzeuk.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbfnfll.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2gdidotil.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbrdues.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxcahen.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbbrtpp.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfauzhk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpdzaar.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjxwucu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2awercwis.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrxjiox.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyiekbe.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rrafigyn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqivjqwu.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnvbpoi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwincnur.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2afyayonn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tothlful.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ukswvoyh.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2uunqqtbg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2hctphetw.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2qowmsrxw.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2vhurihxk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2vssiasuc.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzdwqwd.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wustqwul.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctymdhee.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2avhdjzpv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vaaanmhp.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvenhzx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdyhyoc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2focmfkgx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2odbpowqq.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqltltl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwtcccr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzvynng.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwiabam.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfkscvm.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yntcdfxe.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzjfvzo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhhioog.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iellptyj.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tencnhby.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2yynxeegk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2htggcecq.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pctknhvu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2beeyeqsl.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbugqsx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2brztqwlz.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2swntynwh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mylyqqhq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2doelgkjp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvbvjms.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vslucowh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwvpuzk.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdiujvi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtwwtqe.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nligbwpg.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2rbumvxab.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gaahcxaw.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lbunjhpk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhtqjyq.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2flpnutne.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxwlzna.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2qrolhzyl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkbaxct.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtripvd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2prtytvwf.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwhvijl.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjvclpz.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2uzufijau.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxfgldc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2awonlxef.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhjbekp.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vupyysfv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhoxdupk.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2aipswprq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdxepkk.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2hgoehdnv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnqfpsg.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2uikkykxe.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjzsnqz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdeifnw.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2evnlfghc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfgqbwv.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ufugihms.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxlavjs.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdxcwet.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2hecyjiwi.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwczsay.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzogviz.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wytqilfw.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2eispitat.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgdolsn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnkqded.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2drkwpryy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgulhujp.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhvssqd.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpjwfpx.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwullet.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyeubim.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2jtaodzdi.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hbygvypt.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsspxbtd.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2prstxyqe.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2panjzbjt.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzhyoci.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkyjnibz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpunsaq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tfooysge.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvwdwbw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2norgbgib.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhycbbz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwztpzy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdyveyw.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbthaqq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ustphzsr.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2mevzhfwi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2epilseeg.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ergheocg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2tpesjkxd.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrmvxok.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvkohed.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjrkbny.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2epwphdli.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rllslwdl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2szwgjisd.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2srizbvxt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pigywxjb.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpcicef.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsdcfic.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2eapftsrn.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyroiljg.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2dppfmgsq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgupmiga.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2lajcbynz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2anoukxap.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmocmxz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjhmusl.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwwmqdz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxfhyfe.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zejlngci.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2edfpwpdf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jheroebz.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmveygz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nddghqok.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2afwldeim.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2izfryvwa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kujjtqdv.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvsghsp.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2gflhqlam.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2gecnkuwv.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2khqfsovv.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbqdzya.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmnzeps.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2vibjtuec.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ceoagsje.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpbjebt.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcaoscf.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbehwhf.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvtjgwr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imhcpfsg.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjyoufc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2huafoivj.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wzekogxk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqzuuhv.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qfspbugw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkbrnxk.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2twkjvtte.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsqlcnz.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2dodebgzb.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2dfizwwuy.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fidagdew.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2guacbjrb.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpljkcfg.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2hsynqbhe.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wanzvbde.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pbeohvbk.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2prdxhbas.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uabtmtkk.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2hccslyut.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpdjphy.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgznehs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2faykexbn.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzoisdt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsmefwd.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2smtqeikk.html


<!-- 参考信息 -->