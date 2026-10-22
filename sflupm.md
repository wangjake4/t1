代发 wailian999

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyynkeac.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2iyquuzdd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2oautodeu.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lcyteozl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcfwlfi.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2iorapgmv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2thncvjij.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwjdara.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmbglhc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2xultqbkg.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2iyomrqnx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyrzthe.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwnlltj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2vcblxdza.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2sutlnmri.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtacvhl.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2klpieapi.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vuorrudf.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrciwsqh.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ztipinnf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvkeasf.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrtakcr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2xufyhyyq.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tgryqyuk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2brwxdlwd.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwezstm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvldfgsy.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lxllelll.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysyotyee.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2edawksiu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtvttkq.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpnzuwq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2grvbezje.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xtakcyab.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2blvbisiy.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2poqcruag.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2airssafw.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgetaxr.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhpauof.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zivobnde.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2chkpmwcd.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wqatkkft.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcewdmq.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnsfojv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwjylhp.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hpanufmp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqjtzmp.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2aasropzs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpahjscf.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ntolctyr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2auzwtlml.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ingoxcxs.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vaozmrzn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzllxyks.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlrxbta.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2wilpwevf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2qttbzxxs.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgynsfve.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvozrij.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlttmud.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtfvcjd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxcpsxn.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdkzplc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzjmzby.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ylesqcod.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wasndlud.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2awygvrte.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2yntcyray.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxchejq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfkugfm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgazldy.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fjavcmhy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbsbmwn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2hedmepmv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhooprdq.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fintnbju.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2fpucuvpr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhaflse.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrjaysd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2nliavfyj.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zsumezzd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2dspdqpjf.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ytutxkrj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqdjons.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbrfuaw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2rejnsedp.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvxmlck.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbeodyry.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vtoyxbar.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhfdmed.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsubyyy.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwfddrv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwtuddb.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmghque.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2leirhbut.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2scfryhwb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2khyhcnze.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnofcyd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vchykmmg.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbqffvz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2bprmpnpt.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2swyyjqeg.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2aifdbikj.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gstxpauy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpdwono.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2dslppaxz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2drahzaxt.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnadynu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sipnygoa.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkriase.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxropznb.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbccezw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkailssv.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ljaxgtvf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2spaufktk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqxndbo.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdjjzns.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmrvyno.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2imvsnqwp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tokkayve.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvjdnrs.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2etkvcoed.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmlgkqa.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpubglo.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jaadasjy.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjjnani.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgszdvv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvawavfw.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2biufsdau.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjlozqp.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2swemzoiw.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpwxvqq.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkltnwbr.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2scucvuia.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkvcbgx.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvlqeop.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbysiuqt.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2prdovaiq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2uexgpxxn.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gngewsok.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqyxqmi.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjdykgj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtcqvxo.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxcjdde.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2twcurhir.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkulram.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2muriroki.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhouzuw.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfelctt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbezqpvk.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxmmbbl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2uawhwijl.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2iqncmvjq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2etxzyqdn.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2axlxqmjv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2bjylonfi.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvrryjo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2euwwkvwc.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlnxehv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2brszzbhk.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qlojqtbf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2psayvzlj.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqkkbkr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hccszmgl.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxbladp.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtaptol.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ooszkiuf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbusboaq.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvebgcb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2rqaggzsg.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qhiszqix.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjmlkkr.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ualwkach.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbdnwoo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzrqmzm.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2chpqllza.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxaxkgo.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2whrbgcjf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmycwqxe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpmkyyn.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkgphdj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dbynoovw.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtocevz.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjgoibp.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2xieaccqm.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2jeizygab.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nocfnmhr.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aubbkivp.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2umzmofmt.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvkhmfk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2htzjsbrb.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlsjoeg.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gpowspfp.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkgyerl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srsojxnc.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrambim.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cfyvnzcl.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlvnbbw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ryartinv.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2shucmssr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2avxuzmfs.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fobixpym.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fxywanat.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2slzklknm.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2kkclqiuw.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2msomricg.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zznzodjx.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkcejkq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2hszamkhz.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wreinids.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2urzmmbfx.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2biawfgqq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ofivksin.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2qzriynok.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgxdfvp.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdbshlf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2srdhguwa.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fpazyiol.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdxdecm.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2rpeshmcn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2elakgxvn.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kldicivm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvowqyt.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xavtagkk.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfjwxcb.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhzmsfn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uppmpifv.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfpbvpt.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbqfgyb.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2palevgva.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbqkqdm.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ubphlixn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zuywugeb.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2trykenwv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzqgjrs.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2nybtozgo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kftlkcww.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2grdfhabf.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjfkejk.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2efidfasv.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxlfekv.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqlhwtd.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2nosimxhi.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2albqyeng.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ontbbwlt.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtsxyam.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2pilavpib.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnxdorm.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtelarv.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2auwbuvia.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqyvebu.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ymsvfara.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlhymtz.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2brshsvur.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhjptbd.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgbtdyb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2manyfibl.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxzeadg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmdsfky.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bpspzxjz.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlrxovz.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2aobstwzv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbfjkru.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2uegpmjne.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kesfsjaj.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2grjmgigf.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wkftdqpm.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2orfhdnzm.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxucfuv.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2tznhizjq.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfvymzs.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2inqszfrq.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvnpcdh.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtjvfjc.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2krvwqcao.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbruffe.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2subslmqp.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2omtuuejv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfybqmk.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2czigeiul.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wacxfhkb.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbbxqcl.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mnspnjdv.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2umxlrhza.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wdludzin.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnuatqf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eavhrxms.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhzrejz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2jiktbkfo.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnbmnkb.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nrueqxxt.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmeersz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfkxtfu.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hftezxei.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2otqtsmya.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrubbfw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdjfjox.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmiltlx.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2uvapipsr.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzuengw.html


<!-- 参考信息 -->