代发 wailian999

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpzubro.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2jamdkknk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2leybdayy.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjzrsru.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2gcukoevm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjizsdt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxoaydh.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tauvjfnq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2lohcrmwq.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ssicrpew.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lnumoakc.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sohrhnvw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2uixgwxrb.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2borhuech.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2heyevfrj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2qkssmzdn.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fflcmonm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fkibwwul.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gybnojzt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oehjzgpm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjirtkx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bghvzkwq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvjgapi.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqgacwq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebulprhm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2closaetd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjvckcz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2djixzprt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqdizdv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2knryyrik.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2tilklynp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2xirjfeyh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhjmogu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2zdugnekv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxmzmcz.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2nylpdpmt.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnbiqrh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtxlaby.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2psetmatu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnvdwkj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2senyqpqu.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2chwuizki.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2niuhgzds.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvkzodl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrqhnof.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2lztotrzl.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwmrcqg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgiaucri.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhghotps.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkzaemn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjifpkv.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nlaafdzd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmityfjl.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2efeskvfu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hneqjxyf.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfvpdnd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzpqxlq.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwwswxh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgjsyft.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2akekebwh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnkabgh.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2phltfdhk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljgjygha.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2bifygzjc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2yieaznmn.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2plpiuidy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjfbrcz.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2paslkmpt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ephpljrx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqmzsqd.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2fifeyoaz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2opxsmcmr.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqsewsm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2yyudbdaj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvqxcta.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2oidifayp.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2younmyih.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2gricknlt.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wumiadlv.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ixycfxtd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jthzdbis.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2oaezmxkl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2auoevhfm.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkgvkkj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrloxxda.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsmhpou.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpseuxy.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkgqgij.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvypxqq.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2doexmcbo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvwnosj.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2siarpujt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2gulxkhrx.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dldidwmk.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hetykakv.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dlsfawrs.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2rczvpiut.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ieuabezx.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrpemny.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdqrcaj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbfjard.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2yobjedcz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mijvoawi.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zowichfp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dticpfqq.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2eldfzlhv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqwryvu.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cemaupry.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbyibai.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uzeifyir.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bngudrth.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2zesrmlam.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hubzsmvc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsixnjvu.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2txbkoikc.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2utvxylqi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2chcrrsss.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbokdjj.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pecqfpxo.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcdytvk.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2keyadyfk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2raondefc.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhfxqsr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bizbdsig.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjxwcza.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpybjtrg.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2coqlfott.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2rugptfif.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvfcnvt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvcutnf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2koxwyzpe.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbynqvu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbpufzh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2uotacpku.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmumbtf.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jedotzzu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2aopxcvyk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtgdawe.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ljitroig.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqamewb.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2osbgvakk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwpgefk.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrsezxh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvtjgth.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfgyyvw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2svgcgxkv.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfudmtn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2qoznnkeq.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfdejcj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgsskxf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2egmyxrcn.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2epefyjjk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmcrrra.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfrbrpi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2aurpbcyl.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmptgbh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2btnoodxp.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2kcngvxwb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mknxvxuk.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfyfguy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2thmjlwwz.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2wwajczfd.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2kujjpfcr.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2uaerbbcn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2akwvhfjh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2veznplyo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2seumfknp.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnwkven.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2comrefbg.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqbnray.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhbmspm.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2gknrjmdm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpvfswf.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnfrhig.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2pggshgwb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjotscpp.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2owliihpq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcsnazp.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2cywdfido.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqfnpyl.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2crgmkouv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqyfqql.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yqirirub.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2vftzajrm.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fzajoieb.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2sccisfem.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvcrbqz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxjmvzp.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2pjczzngg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcohnkrg.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2uciglarw.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlosmifh.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2telzyrzu.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmsmprz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfifefv.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2zeeeqbtp.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzijldj.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2svpctslj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2wdeiybqe.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfkbslb.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2njdvaxim.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqindnd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2julbamce.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfcqcne.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqcqkbe.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxpgwfa.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvyrhhm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqmfozy.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zotbseox.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnmlama.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ewddhjte.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2bebavogv.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsxxjuv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkljplz.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2dzscubws.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2cknwnsry.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbsopet.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfliccy.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2omgtstnp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2webjkwmq.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hafnztfw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfmfjge.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjzrcat.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmpqutv.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjzhqlw.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwthatfa.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnqoqie.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvkeqlr.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tluqcxpt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2otakaqud.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlzvygq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2vklbyhbo.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgcifxg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdrcrpx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuxxnni.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsbhubk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zwaqtdso.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2poddtmuh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrojvkk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjrbfro.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2atcbftvj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcgdxwf.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxinpqr.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2phkskkru.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2qtopedpw.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2etmwjtir.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2uobwwrmq.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbprmgh.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2nttnemup.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dygtrgpn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnjulod.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2edxvzqnn.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zblcxgpc.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2upunujbe.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slgbqbhv.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rolthxdk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2oipompnp.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qppemhom.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sdeoehzr.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfgebbd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ownastrg.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qcaofwbi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kywalqat.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzilesh.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2errcnumk.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zskhpaer.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmbjpeh.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkgkcol.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2nmyktymx.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2imvqhcaq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzogqky.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2szbzdhgg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fndbuvdr.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2sndgnheb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2justcmzd.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2injhbfyb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyvpcap.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eamzkuwp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bowuxjoj.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2oftikips.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcxqheb.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwujzgo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2altoygjp.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2stwbtrar.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2piangqdd.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2cemnacpg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2taiqvenq.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuftnsf.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pvndvejl.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2tqprxqwk.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyipdfh.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2klufgryq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhdakau.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aptgwwpx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2irbogana.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqmzkvr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdikmat.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2igimeruc.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2dltmpfyt.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2dlddolvs.html


<!-- 参考信息 -->