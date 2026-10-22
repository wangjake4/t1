代发 wailian999

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnoyncb.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dqejylyj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhyjjokq.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlpjpef.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2crskgyjw.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2tasihyuz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2goyacdkv.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2akasajwn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2vltbtmrs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2khuqfdou.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvupboe.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlouoxe.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhuofgv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmrsaxq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2rktbofpj.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbzpaxs.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2olhuqbrq.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2gifqulsq.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2trqsoams.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cldmiqbr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2braicnnh.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqqftdr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2msthkrwj.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2drkrscbj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2cettqqwy.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsscyeb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwjezgo.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kslvdlce.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2bncnlrlt.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkcsait.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgmpsce.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjdtqlz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2aktceujc.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpfvywb.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqqloyy.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wlatulno.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2xqttlhnk.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2yqfjasuc.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtvqezh.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2dqksicgp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2osrtedwy.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrzefei.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgjjvfd.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zixkzrhc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qorfjduv.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2obaxovkf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2uadlmppm.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmpeill.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtwcgsz.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlozbaz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2trsdnbdb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuelove.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2aleuluol.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyvokrv.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2iadenxyc.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhayexp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrfsaop.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2etuhbliz.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2apcgckyx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgdlbtk.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uarxahec.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhwwvwl.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrxlpdv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrqqdft.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2eeaiqboa.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2renpgrtj.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmosrcnt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2eybmfibm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpntlph.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbqifab.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2giuunnev.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fzggabgr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2pxelyjtj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2fnspiqtb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuskceh.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnyfitk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2qytyrzyj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrrakyu.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkffslt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2nozfwory.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2efzavgjg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzjlbjv.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2feydxzgq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnzcyfn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2htwcmikg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxidtion.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwzxqjt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcaylfm.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vxscgwtm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwszxoir.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcgmiwm.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gxyzwujh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2iywqihbp.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tcyhvlrk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mbafixcs.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxqojra.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwongus.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2fohvzowt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrimgmq.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fjapdbbl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2oraoxhls.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2eirltpdt.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2kikmmcle.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxuyyep.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkplyyh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2bqunxckk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwvcxmw.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjvvjsy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iopnvyza.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqsjqdi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzxuuya.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2acamqywk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2asixsyzf.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhnliwn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2mhoneaim.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwytffi.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2stasumws.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2odwyfqyc.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2yyannwsa.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2velryptd.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zofzqnwp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgxgjqw.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sorgplaw.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrshvdc.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kapwnhgn.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2duztbtci.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lceutpmi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2oijcocdp.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2pobatwge.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2aifzzjpj.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwcydsh.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlatiuuu.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjfebuy.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkmztsu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2frvzfvbw.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mlocdxyt.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpohwla.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvkuxcs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2rawhkjbu.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnqjjhu.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lefzehaj.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2oxepmyrf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjjzrpx.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vfenaeba.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjqiryu.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2aogfqele.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kroytpns.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2mciubmrx.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxjshfx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2plpmxpkp.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2fiygahth.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2xobypdyy.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqfniaz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxlvqja.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2iobnuody.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2saifygxq.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2wmttaubo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oefbxnuk.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2itqmlmfw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2spswtofr.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsgqnob.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbyxkuh.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbgviyo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uphxuvks.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmqjace.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwdumsa.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2tekclnmj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqypylal.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2inkqczpv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2cseechvj.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdmeqwn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2sglpxraj.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2lgspvxuv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxyqneu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpqtxtt.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zwszdwga.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2apxsvavo.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdubkpm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnptqww.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yubvmdmh.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbqkpsr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrxjsnz.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2szmjqdns.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwxqxbq.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrciobm.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2iorgjrlt.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqfezqg.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iwztotnb.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xzyyaorc.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2diprhfzm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjwobny.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2yaiuagkm.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2khobazfv.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2juiuwckz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzlqmxf.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdvmxby.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vapxtahb.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vcplgfri.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dltulshs.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxczdis.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kfytutrl.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2imlcvrdo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwwlwua.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbuyaxc.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvzbtif.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbpxjta.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjhwsum.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxplrvl.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2czanhyxo.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2etpzofiz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qikzzcuj.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zotxfpgj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcttlhu.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2epgfmzkk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oqotnaxv.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hgiqgtyx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdwbmmh.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2agcxdqes.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcvunow.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2etazgvpy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yzebnith.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvljegs.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2agyjqxjl.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dprilbqu.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwjjzhj.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhiyiht.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iuyglefo.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcsblht.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwvsmxw.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjgbzfv.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tovpckth.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2isqnkvqa.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpzhxgq.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnkvwfs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvfefef.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjuoiyc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ddoopeyj.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpsbntl.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwkehhm.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2drlxovjh.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvgztvu.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2suupatgc.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqvjopt.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwhznms.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hllxfeab.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gwctctst.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2trkrsjbr.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uezjilbo.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjqedfz.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgxeqmc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oilndpjy.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrgocxe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2aohmqykn.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqeltgt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2asvulyze.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qddbteks.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2swagizsi.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rfiwgjwp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2xfetcgrr.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnkhsec.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dijeiuqa.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjyzpet.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pkexlnfd.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrkvqto.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2tgakqhdn.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2imjtxjna.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfzhalr.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2avkmnhey.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2annrvhxl.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2cykmfxmn.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2htvkdpkw.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnwfbuf.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ligwflgw.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhbnafr.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jajipumu.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfmveky.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxoxswu.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lggfruit.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2bidnrbgz.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpduuha.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhfrwjg.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pgphezme.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2obqkemdl.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdkewko.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgdmhuw.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzrklzb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2irvjilpb.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhrzxud.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2pfggidvt.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2pongmxxu.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bukrbtzp.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wahbxrmq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgkoqpd.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdrlgyy.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbvksjo.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2dndwudqe.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2erbhybpk.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpobwby.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2xnabofba.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2evynahxn.html


<!-- 参考信息 -->