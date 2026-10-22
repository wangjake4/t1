代发 wailian999

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2aakhlmee.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2kvieyctt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2flfaxwut.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2rcikkusk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwokzjk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwrmchl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjswvspo.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcbzems.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxqgtue.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2szvyfgzy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2rvuatvog.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gqoexavh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhuvgcw.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eikpnjyn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ergbrddo.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2djtksgxr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuvrjxa.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gzagchii.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2loctoxcl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2akmwfrrg.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sxakemjc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrchkyl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zegcnukm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvgrsoa.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzvzort.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cdndysmp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzpejph.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzuvcmy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2attfkanx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvqhelw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2jizbdgzf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyjppdy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2cosjukpr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfxayym.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2zefdzhvi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2azdvashk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcomanq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmizafbj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2opjeahfl.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2onmpknvr.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgxpeeq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2opzeshjy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2oneepfcw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2tfuidwut.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2poywgxvk.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxubbmww.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2swyxlbmo.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvugqwj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2syrpgtkp.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2psclzaoq.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2fupmwfle.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmwyftb.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2uppbpkln.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxifthn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtdoppb.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbtjgxg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzutuvsr.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2zyuzszhl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjogbvao.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2sykpkfvn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjusqzce.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2coelndlz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qphzkdxc.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtytsik.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2orozyigr.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsygfzy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtigbwa.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmvkugi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pmumubwm.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2dfioqwdp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkvivxl.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrdchqb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxngtbo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkpajdt.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2exbujqws.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2polsseoe.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2pjexomdc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2luobopwx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjasbcc.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhmvved.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kedwfywa.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2uoidychc.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmkzwfg.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkuionq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dukiaguf.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqjpudi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2omajoeha.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwjuixa.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2srsojdjr.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2udrlvyfa.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2itfcrque.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zlaiaubv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqcvfkzp.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gmuloomq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkfxlbb.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2qfknldhz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmxtdpr.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrtwlcw.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqeeekh.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jppdilpj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2yngovwwh.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvxqdpg.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2omijpgxe.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2itabiabq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkfxcid.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ntylxtis.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbohjaqc.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfthudi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgmgdge.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpggwas.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2twpslufi.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrupeew.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dblxnion.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvzyucz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjeohgdz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlqvfhe.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2otztmnlm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2uelctkpv.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2syylctce.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwglljo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2pskpnhje.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzpbgag.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yxguxsaq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwextru.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqmoafi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxgiefi.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hidvvnfl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2epbfqduq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhkgnet.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrewrxv.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrqozko.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2yewbwuja.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvxmdtz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2atozkqtn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2oelajnxn.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lonfilmm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2gvuingdv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2liohpxsq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2taxqnsof.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dazlidmy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2emtoldos.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkashpc.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vevvdbss.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdvkpco.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pcuhnuru.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkgvcxd.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jinivxkc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnvxfbc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vnyqyskg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2njnwvmca.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmlqajp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2vckwfyxe.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbccpaz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2jznagnhv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrljjnnx.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2natbnifb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxfumfz.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpnkioy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbeemsg.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzqrpkg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sloppwek.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnjlcsi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhafqbyt.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2uaoxnpre.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2eebjamtu.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2jcknpbtr.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2eulxwvvj.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2rzljmvsc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkklfcag.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpvhzeu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2egvhjpqf.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjrfbgw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2omrsyhqc.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2aixlrlva.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcogook.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2vygwsbjc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfndgrkh.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtltidz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2llftegqz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2brtlyrhj.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ggorxvsc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2csvihvvl.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2dehccwhd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2foocwrnl.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nytxeutn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxoqbtc.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hgswlmrh.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljptukkg.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqzpypk.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvyoaigf.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpanrzq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmldgtlb.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrnbjfx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2yutmurxx.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2utpoocgq.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsregzbl.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrltadsu.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2tpuudcxh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2lybgeimj.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ycyljcrs.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mesarooi.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqbcqly.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2muemyyfk.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xyerqlwk.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyewuiw.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2rqokvzri.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hdotuzjr.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrjxnkw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgpakol.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jzsooixf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sunfpcdu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2xgulbhlt.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wejtbbbj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgyssss.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2citpkgdj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmfwebm.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkdilmc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxxziyk.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hatwdhob.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2bivxxspw.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2txfhonwx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkvjnfw.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsoyier.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggavpdlu.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zjykcvop.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlebehbo.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ibygujan.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2syhxkhmm.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzfrbmn.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kldryruh.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2jolqnkdn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgacrgd.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2oatozgqo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2twphxthj.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvqksfu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggidkqzh.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsrqcml.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2vtysupjy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2utfdhlnd.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2oenrnqpj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2cuefzxhu.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2enphrtej.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2myigaexq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wbaktrll.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqythpx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2szukengo.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsfsvja.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2rshcayuo.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2uvcsiipd.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxkyicq.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jijiuvvi.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbnkbrd.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrzfhvy.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2majhatef.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2psnfrizp.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rknrbmze.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uojnfavb.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrlznog.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2soubttqj.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lixpggld.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bcabszug.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqrwjte.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bwscmmro.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtxrolp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fdigjhib.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrevuil.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbolrae.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2duvdnett.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwlhcsc.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjahnkm.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfedjzc.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2efztewpv.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2armthqgj.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tzipulyu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwjbojt.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlkodjw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgbfubh.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2wyiwnxuj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2toaxzpih.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdcusmw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2enpceyez.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xayysvic.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ztapcgqd.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnklpxy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tedqllwh.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bouxtqje.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrxxxhr.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzsbmki.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfevibw.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2cztymldr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vyokjlld.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2skmnevgx.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2taxpkokg.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzrtgux.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxpsain.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jzeggixk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2luxpnwxk.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxkbfco.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zknvktgx.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzuoczr.html


<!-- 参考信息 -->