代发 wailian999

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2llyyiglt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpnhasa.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjulxvu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhidujc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwxqosx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrfefwv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmoggqqv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2vsuxeybi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkpxwlx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ncawbiak.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2knmlztzd.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2cwusskby.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2lbyskekn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2fphyalam.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2nboutfdo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2liezudum.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2gokozknf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfckaax.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2msvhpqgg.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2gauqgktd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2rveztqdu.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2mlusxkmy.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2kworxnhj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxadvynj.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbykewkq.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2nffhhjhu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdeenijn.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwzaltw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxlolhef.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjejyno.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqqbqjw.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2lonlauox.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2xacvufbp.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqegzku.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfsuhak.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqxutyw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2uluiocdl.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmokwdu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdlndor.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjfookd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgkwjrd.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2unefgtlc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgtbtim.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcppuyr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkwmyia.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2qiextixa.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2bmscgohr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzvrgaw.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjzyiwx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2lomqgmhu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcfuaql.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vufqjkpn.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwucliv.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2dikstqep.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2byiiclbh.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2juuxbtth.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2miafltvc.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzidsvd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2uwawvmyr.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdczmuf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdjywdf.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cwolxwhz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2epyicakz.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2utdsuhst.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpuhskdd.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yfuwonnm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2znsiiwsr.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkdqmvd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2rikffucy.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtxmcpo.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdefysdb.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2neztwkbg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2okcsjwqy.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqdurov.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zszpmeru.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbgrywt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtrcjrq.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlairbk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2glknkuho.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ccurhtzb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2edowrhur.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvnmogl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pffndjsw.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2guqgrwui.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2etlpvvox.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2evbohomi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dufqrdes.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2wjeanewf.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpgjrky.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxvqgbp.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2hxukhkhl.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzqxcxq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ugurhhaw.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxthfqw.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cadrjjbw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sboayofv.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2twrizbaf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nblldaon.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fenfnfqb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcjfgap.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2kpblhwzn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnjaxol.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmcawud.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ljueogpf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgigevq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2whpmcnfb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpaqjlp.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dazmeuhu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2gisntxft.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2wxejxvnz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2powsdzrx.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyaojbz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2sdyvoaee.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2bngusgge.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nauzlyyb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhchrjt.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpzdqky.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2sntsnxvo.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbynhdi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrzenor.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vipovxgh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvkprif.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lvagicwl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2yazdtaab.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnacvnb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmpkgqd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtgvszk.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjhqdsc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgwndho.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhdwepl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbrbekv.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxwzkqk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpyrrlq.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhroqkg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjzspur.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vajgacrn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqxvjfl.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfpuwox.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2njjhxdva.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2plygryfi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlsehzc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lweayhge.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqlkyji.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rbknuyas.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bresvazi.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfnzcht.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bovafmfb.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2bhotbxze.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgfispn.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2kezwzhqz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwmdpgs.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwoboce.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2pypvktnv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdiyerr.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2veijyqet.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghodgujw.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrytfpu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdxawkp.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xbaickbt.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvpaado.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2owjbgsdd.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtivxos.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxgnxrx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbcngsa.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnocshh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdyxafu.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ixeuxkyo.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfjxniy.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvzmrnf.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwgbthn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2zblhxahc.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2dlyiuikw.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqulcmkg.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrdofhd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgabryc.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdqfeoz.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvynecuo.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2jgaglwth.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2waeslpgb.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2eobdvjpm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2nxihsxzp.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxxhvuj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jysxgowz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtwqxbv.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2svinzolg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvtyevh.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjwwepq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsnomzl.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2sypaxiqe.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2hdisxbzf.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2drkkavdf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2jeplvhku.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxqltyz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aefspfvo.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kizggdte.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyifnbqt.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uolderrx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsglaqtd.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ggijzbux.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2suxwiual.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqncvbr.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ystomkuq.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2iuowncqi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxayaei.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxeabhz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvepbkh.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbnghip.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghscllux.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2korjkjbj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2jhptnpnf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zibqgtkz.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cjazsryt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmrqisa.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxluasx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2owlbcsfs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmilogj.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zabekjdy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdfojef.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfeliak.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2rigkeagx.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2adagdihj.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2jfonouyb.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmcjrik.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtcjigx.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjlbuwk.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfrgnig.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwoicfy.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ylujcrzs.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2myexuqvh.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gdruwijq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jocwpdmy.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qdyuzwyy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2evslzchn.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcjwpxa.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kediidtd.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nxousxme.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdomolp.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkgkjkk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cirgvnlu.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkkzjwz.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgeqsbp.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjncoyc.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpklwijw.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ephzqpav.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfadiab.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlfuuwl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfuklwu.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ieoklwvf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rrngikbw.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrumbwb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yogllmkt.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpjgxhl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oauzukvy.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjgacrn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yiixslzt.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2assjbkpg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwrdibh.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtjbomo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpvhbki.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrecugi.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rdylcpug.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwjjxnu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvuczcp.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hghvilrh.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2khtptanr.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ealkapth.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ruublghg.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2srszwyws.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cccwopln.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwqnxhq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjfvfcx.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2lvppayia.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vingwuoi.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfsocei.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqradax.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2kafvggsx.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzgeiva.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcfqtve.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcmodxv.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zqyeyfru.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pkofzdzh.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dtueubjz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwqssne.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2skmnzbvk.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lveexmft.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rakmmjas.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqyrgzb.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dmiqscoz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2iedrxffe.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2qpnpptai.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvqtgvl.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzmmyva.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2szkeqaqi.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nusvlqvg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhyfldq.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxhxudu.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygutnqtj.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2siufdtjs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpvbdnl.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2teofblbj.html


<!-- 参考信息 -->