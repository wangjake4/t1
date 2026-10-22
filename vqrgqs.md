代发 wailian999

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2juhhgtfs.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gehhpqmy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2syazrkbv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlksvatr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2svzikqvi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2jthudngl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2zanswjid.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2hssmchvv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhdlkmv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2lulmbpck.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxpajzc.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmpwjfh.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2fimfpuyw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2rehwchtm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2svjboygc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqgpafd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2baxvqewn.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhujuyod.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2fiuzepbe.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2vbglirij.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzelpeb.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwevofv.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2plxluomr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjiowtre.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2eelwbyyg.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2heogacyx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2plsruoko.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvceetk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlagbsdn.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrawdwb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnijjckt.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdfpsgi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2huqksqoh.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2kjstbwih.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzepean.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxtpcxx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2pchxfkol.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfchwvd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkewkenz.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2grjizthb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlezvdw.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2tbanhvwu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wchppzaf.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2cptsheob.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrthszy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlzsahu.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtzwgao.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfrdwjl.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzughtl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2gaoyvkvp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2szrchepw.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2npjvmtjc.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqhzowa.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbzqymp.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqqxlat.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gieibohe.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhhthjw.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2etjspafk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxyqpte.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2laolkjct.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyngbblg.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjflvdc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxzbmbf.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvffysy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2anyhwrtl.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2plsmrvtb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhxdksd.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2lcftszmb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2uphvsale.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2oybiraql.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzokdmmh.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgvxmwl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2rgoqqfru.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpqmiuk.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlsdaiu.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2pngnrnen.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxubyzw.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2iviteheo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2itlwznfv.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfuyddf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pabafkpa.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfnesrd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2szrhwtjd.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtkdvrb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvaxbqh.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bdosbnnf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2txkoeqju.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzsdlpi.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wolifeik.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2umoylvwl.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2cdaijeks.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2hcyrqinz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmmtrgz.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgemenx.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2goglmfis.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2umxpaqkk.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jivgefii.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ankunmuf.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2blyjnkgv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdvyxyp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2kdoivtrj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2syzdudvl.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ezyvtmut.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqiyqal.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2awgrtkkr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgmccwk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2tiscobcp.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbulkmf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2tcevssny.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2knfcdtdn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmsmwxb.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2osbwwuqk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxfuqvr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2csgwuytl.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2manacjgq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnawyrto.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxqjthb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2pazknetm.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2quqzsubo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqmcckb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbbvzjb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxcmxzj.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cnisnvnj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxstylbn.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsgebzq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnucjlxz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnklwws.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcayttb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfzyklo.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yxijvfzh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2cudeusej.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmtahfv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbzelcg.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjoufnp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2phvmvhhp.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2grtvfdoh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2iziwuhce.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqveopd.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2dscfjgev.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkvwskn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wafedhkn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2njqkbdtg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrrfbru.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ifoslrnp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjesaup.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2meagemkj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2snzararc.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2vycqjgxh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nczznhgf.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2kprgdreu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqnujkv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxkelgh.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wmunedtz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2omwyhrbw.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjifoml.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2guvkpmon.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzeruey.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2holcsmnm.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzaslou.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmlyyud.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2myzypfpa.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2arzqrhzz.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yaulozjl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2akyweair.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2pclbsiox.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2havnfxvr.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2flyxkjwq.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbtqbzk.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxygrev.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdegooa.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjgbqhk.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2oludogbo.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cchwunnh.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwapwvj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsuvwab.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwjfthl.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2omrnivta.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2umgcclbo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wbyavagn.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqpymsd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2kajghsso.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rozdwals.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2itruflfe.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2cvurgvej.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxlpvot.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2lasoxcql.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxnawyh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2uylsiozp.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2aecwxtuj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2kacbtdzk.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ryuxfrvs.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlxwhni.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzfxvpv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkttrdd.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzgildw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqabwwkg.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrztjmb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yigdjoih.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gosuxknb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aexhfequ.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2uskoqfmq.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2assirqop.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2yenwnaiw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2tiukgrjc.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vpyuwjth.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrgadjj.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vudehjuw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2lymisoxa.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2htzhgpbb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpfqprf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2snsqtfzi.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jscrttcc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwxtffa.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2eihvrimu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjeioyo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhsxakq.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nuogpuhh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmrybzf.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vyakzvtp.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2cwegzjhq.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmikpkf.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2fjysmbfm.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2safimebq.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrwntjz.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkedqsr.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwafyvc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2pthjjkoq.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2yxoylqav.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdkvhvu.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtzqyrt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhrwwmf.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgorcdt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvvloqy.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrupfjr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlzzkcp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hrujugmr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtrhbvw.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dlizakbi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2huqrvwzz.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxynfkp.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzciiei.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxuvmprs.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2namnbjdc.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmyshvo.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrzsrny.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ohajoxqy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxpnwzr.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ozohvyde.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gcoomxtv.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrmxwzo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwuxlso.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qebeingu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgyxvjv.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uraavczo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jsuwzknr.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgmjbva.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cocvxbum.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lbiucmxc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ravfrndx.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kvewtfzo.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzhllvg.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfjuoik.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bneasudy.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ooayhknb.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjweliv.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2oxaoryjk.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwdusnt.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2phgqbwpw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqohgei.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbvquil.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nrednknr.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnlvlbk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhgsjuh.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnhjclo.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwvtdfe.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbqyhgo.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2sgupiejy.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdoobbb.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjeddza.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2weagqwes.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sajqptqn.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ytibqbbp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtikxus.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnviipm.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unmoyrhp.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2tzowcach.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqacbxi.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2cofdjrew.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvdyrqs.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2huktrbrq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2egsbvbqz.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2lpenepyh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqhxars.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqhfvkw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ickijnvn.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpdouos.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqsnrsh.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2comzrlfg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2itlgpfgg.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnmxbtf.html


<!-- 参考信息 -->