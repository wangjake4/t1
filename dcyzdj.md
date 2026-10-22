代发 wailian999

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxotkjq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2tgajybhy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgfxgrf.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxkidly.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2siyecmft.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2sivyruci.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2bmagemfr.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kfocjqky.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2yqfwrbtn.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2otjsfurl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2niendfhd.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2neurdeql.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcszhdxw.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rgocfwiv.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dfosndyt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjaxris.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pkokmzuo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jfeibkbg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cqymkhfg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lobigcoo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfplppd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fccfuvfe.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlwatfx.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2aifynmjn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2kylorjts.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjkqizo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2uladdvzt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2enkcciny.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxxvdtm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgfgimr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsdoncb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwbqmqe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dqttinsv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhwwdbj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdgowyg.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhkpcsh.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2opnkkcqt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlfusdb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwlrmkv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqcotss.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2egvacsre.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmzaxbu.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrbjtdf.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2dzsrmenp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2odpkznxw.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkgblwa.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2caomgvqc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmomirqn.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2raympjsl.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlhdehn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2oeybxngp.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oeujicgz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgebzdri.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqfnbdl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2asyiiooj.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2tkuecwux.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmufaqln.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2fxidrqif.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpriqrxi.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzwbbmp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxoizfc.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2loybpams.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2crrjzlpr.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmqlkup.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kumxthbu.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2cdghjjtx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dmogtdyc.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkzqkhw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdlopwr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2khpnjoyp.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2apddxxmu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmwqkbe.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2dapayboi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2jounxksm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ullpeuwj.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmdmomz.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2akxqurly.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsbtnmd.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtuxfvyd.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fplpxuxn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwkilem.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdvztfo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrqkhnf.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvkbzyt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfsaaot.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vgabuzsr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cupjmgqa.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2magmsfsn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dulefdfi.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hdguhzic.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezceqkgp.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2mxblioei.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbxnksh.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2abbuclcw.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugddjywh.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2atovzydm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2opnkooqb.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hrccusxv.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2scnxyrpf.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2asgmztbw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbparwnm.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2phkfmsrm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2feskojmy.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lslmxpgn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssghgwzd.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2axdmdmnd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlpunul.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vaijlhbq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuovgdgt.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hheyolvm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyyjmfmu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2acmpiwxq.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rejxzgvs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhowqpru.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzwwvwt.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtkmecg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2afawzavs.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sitezyux.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2suoqgxwq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhocrbht.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2taujzrur.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxusyth.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lprspxhj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tauzmonn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2skuotenl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2irzhxedz.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gatvfhkk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbesupw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrtnduz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjduoru.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2fptelpnn.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwgoblt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpffwtp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2cycajqja.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhusvxm.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2olyrtsso.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2whyagkxp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkroozs.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bybsuesb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2rueyqiwq.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nunykhbg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgoaisd.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yafbtbdw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuayglyq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwgjdhn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrodzvv.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2smqjexrz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywaxquye.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmceklp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2euybnwno.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhknozwo.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2dihyymfo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpiojrm.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ajamrdsb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2obrckufl.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvhkwqx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iosjtznj.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwcfhfm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2shajbmvh.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2swfjnngb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwpnztu.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2oakzawon.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2plodrjjy.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2cadqritc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2uglxutnn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2slcycqob.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2emyoiugq.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rizkjwah.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpgqumn.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2isbmqcxx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdqomrh.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzvwqns.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgqfjuf.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fliqpjof.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2mjezvlrn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwqqhcv.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2aafrthqd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnmsifn.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgqsnec.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqplqsmc.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcowexd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcvufwu.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2oiodfzff.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzgbgnl.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrkyvhn.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2szivkpus.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tympisjc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2adtptctg.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2khwzcsqk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2csmgmnjb.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2cetuyprj.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpggaqs.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncuoyeuk.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2dpejylzz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2crvcvasl.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2zvonihmf.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdidpava.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2qffhzfzy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqwhisl.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2swzqzlzc.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bovlvbge.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2tkiuuacy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2eycslpjt.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2copcuhcn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmzqeml.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwhuwbu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dteqyxok.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2imwgnuji.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjajlmm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxjvsai.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ghyawvfz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwzqadi.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcummlm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2laodddeu.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hotdhcbb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2qboqnjwu.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcphzlo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwapqfq.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ahscvhda.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2csufvnyw.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnxzqvp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcercll.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lbflfhlu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2csnycyue.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2fpccvzps.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnymyoef.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2anntqydd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2omzzdsag.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wovbmlqu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2douztdit.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqhizof.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2npbxpnhn.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbftcvy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfaydfl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xofaziun.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtbsxom.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2dwolyisn.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2makxvaps.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjevkpr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lodajvfe.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lorvmnrd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xouqcakd.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2joeigtky.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyldcud.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2dlelycqy.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2wshqplxe.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgbckhv.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmqdbjn.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2eqyqahgs.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbbhrfy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2grozlerr.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2leqxsmxb.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nrysumbf.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yydppauv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wunhpqoq.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dpyczqen.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2euprzymk.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2edcfwuef.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2usbbyjin.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jzacbuiy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pfchckct.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2thzioxfh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxzycwz.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxnicry.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2lcomsozv.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbveyfz.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsywtfjq.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2chfmbhsd.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjhynhw.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxinkdt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2btzwrfgn.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2thvjrwju.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxnknkp.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2eonisjbz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvxkilb.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nzicxqpi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzjyrzj.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qqignstu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aplaonsj.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhogqpx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2svajyacd.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2givtnzdg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xermnxkk.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdphzvv.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhqowed.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2svwastti.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wvucswmo.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mukrqrtn.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtitkoa.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxxusgx.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vomaunhj.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjjwwjh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrimfof.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmjanky.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ezsiodkc.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwmnbjc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zviqofbh.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbrdfrf.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2xugqxbzw.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2toanpqmq.html


<!-- 参考信息 -->