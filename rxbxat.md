代发 wailian999

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2gegxuwhc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxmpcwt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fwiyxghc.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2bapuqibd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwcskiv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhxryja.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2uekjdczm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qunkqxvi.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2dlafoizj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2oopszvoh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwudzraz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqavdcm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2crmqvetm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsncmcc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vswlxnqn.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2cjscqidb.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2qowsaoik.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkgsqfa.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kiyrtwkv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqlmihc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgzfhpf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzslmcpn.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfvmpzr.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgmvcjn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjivros.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ybitjoxt.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvsqwgy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqaewmi.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qalpuxra.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjoogqz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqzxllw.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkohugl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwtqwdi.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwmdvxm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvxlwqb.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhcoipg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2mivppaxv.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2sgglchgf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvekrqxg.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqsmsin.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2gocwnzzv.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbcphtn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggatkhvs.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2miuqnwig.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2cjstjzgn.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdltaia.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2awzwbccz.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvaxuij.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2soevbyxj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbfrvna.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcehwzu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvethak.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwalncxk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqqerwo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2edymybnk.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2oogaeqng.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymypehlk.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmlgasb.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfurtiay.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2atkqawla.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hphadtvb.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkjdffa.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2hzaiyzla.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2inmkkuxb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2iypqkboe.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2akpbmvqi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2txbaebxo.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2illrjroa.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnvdfmq.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxsatgo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2raujotkj.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2hclozgft.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvhifxu.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2msrydcqo.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvofwdsx.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwsblku.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2moapqdhr.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2chxpxovo.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2svsdweap.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcdatco.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrbyeta.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcrivgz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sksyidns.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2klyyxnin.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhygruen.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2gdylcbnu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2belaqstv.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qgyohkde.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcqtvij.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ycovkyar.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2whrjlbrb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2xkoposbv.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2srbvhkbx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtyllcm.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfjhqyr.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtggbsc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2junyvosn.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqzhpip.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2akyiljfx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajeoqggm.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ntogxgpz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrsoxne.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqbsnkl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrlkaxg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmdxdrz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnhukzz.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzvnueq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2xciqvoba.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbsknebj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfckcynf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2flceeyuj.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jbasjcuo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2vujkehgy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2epfnjnyi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2omnlkvuo.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oeunbaas.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhxatwk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfnvdbz.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mmypgjqg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsoaibue.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kplrlmtf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnrxtmy.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hkoktjie.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cheorvqy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bndryobl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2sumtlsrp.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mixcfamk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2meztdvft.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wduoyljo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzqpqsg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvlupzo.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zfuowjjj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrisnli.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzmowxm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzxwudu.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkhwgdz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzsnjzb.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2injhhcve.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqnvrkw.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qugsdwxk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hxndqmnd.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdjttfk.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2hluhuxdr.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vuyjejjd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtarhkdj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhtsqle.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvjmmus.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pqyldpvm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aehtnraz.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwecgqo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpuhxbl.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2halvdnav.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mushsthf.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgfnanl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhouwmi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pugthxpu.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfqmyuf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2umbvmgai.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2awzkjoqs.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgoijein.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwkepcu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2hbigfrob.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fhibvfym.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2syyshalf.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kuquelal.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2rufkfsxy.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtxmanc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2quyjldgy.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpgenzj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdrlwcx.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzjgodu.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhluzjz.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bneicnws.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2cguzckxw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2udxqdbuq.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xlquwkvw.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgrrnhx.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ulclkrno.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2zbktamrl.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yskismiu.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2liuqjqec.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2zicigpqy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2gereogpu.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ioauzwjs.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2oeccqmcw.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vrvrovkd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhwmkea.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsctgjj.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjjjzmd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbxhaqf.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2eyegqcoc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxhbdfh.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rvaptqth.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2zgysirkb.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdzrzbh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2mleqocwc.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhcneul.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyidsldr.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yicmcctc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksufqczg.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtwxncg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbocuds.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgrlsok.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eiptnpog.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlonmul.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ortylngv.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2amngtfnl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkvawoz.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2galyzfvy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqczklm.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fyygdfci.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgrnmfz.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2iiuwvmgt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdqlehe.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyvupwu.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sixxxjlb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bocyzcba.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2uateqxcz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcerwrgj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2avihxndf.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcilcaf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tgleblnm.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2xraexgdl.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2svkelnws.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2xidqvvcz.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2awayfkdb.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2syvyooaz.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlagmvq.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2jaudeumt.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqwxbba.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ynivzgjr.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqtjrpm.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwozehs.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgtopjz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2foqleohs.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mqacxuev.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbjpeqq.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rncqyjzo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tshgspjq.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpzwpwy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxylrai.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qvztxhpb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2obdwfcqg.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdhqlzz.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpovsax.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjamuszl.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgyxxuht.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcattdm.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2lckcippa.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dasxuupg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uubfxati.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dwogrgjs.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kipugiqr.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnbbwyh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hdycnvox.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhgcwqx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqcogiy.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kltbitgz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfmeybr.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhkymsx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ktconber.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2irodwpnn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hflbpuii.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nbeodfdn.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfggdwit.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrfrrga.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tovowrtd.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqwgynl.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlzvgfk.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2yymszife.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfgunmn.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2igblcdap.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjfpheg.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2youhtvuq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ualyctuz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2idukgweo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2crfuwgrw.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbpfuww.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2hteidrgg.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxgcyli.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2yoyvynjr.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcxrniy.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrijyuu.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcoykjk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ressgryv.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlilhbz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2omrgqhpk.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ttucojpc.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxuhwdgb.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bwaokiug.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxnojnm.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hvixfkfa.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpmnnou.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnjyioy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpaznrr.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmckedo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2hiegriyz.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjzlwkw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2arbdxgcy.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ityrwfnm.html


<!-- 参考信息 -->