代发 wailian999

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxqmiep.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbybifk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfedcquj.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qojspujf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vijfwrmj.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxsaaun.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vckqdilg.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdnllap.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgcgsrs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2lmazngim.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnotfsc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2uncswopa.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpsxhqg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnljzve.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2berfftfs.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrxdzry.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tadqkzgc.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdibxse.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvysisc.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uauxlbgz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dckhbirs.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rnuibuff.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpgnioy.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gohxailg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdiwzosb.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmfbqhd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xidyyocg.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzaeavw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2afwzvkkk.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ludfkjuo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwoyradt.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2qxicgnno.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrcaaos.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwlxmcy.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwcscbk.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfcjrgo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2bncukmtc.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwhdrct.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlyvwts.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbctjny.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjdkwvr.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbbulkv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzgvrzt.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsqzfnv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2moahsqwy.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnbbcov.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcmgosg.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsgjmcb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpxlzty.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgvtytk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmkxgde.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlyfvtc.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbynnjy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwfztcd.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2oshcevud.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2zmriivye.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2irpkthck.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsamithj.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcirdnf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fukilklx.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zwawgdda.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlnzjsh.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2anycgivg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2febtwwmw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2kezrdrmc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwgirqn.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcytdoj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2czqrqqck.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2njffdmba.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2gggqwnxu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2eydiyxdz.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmolrhb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2tntjrhct.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2zhehfvom.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlyumce.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cckyulwm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxjgljd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzmdxjv.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kixoqljm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2budoobtg.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfljfrz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhndxhh.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhkvpip.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvqzgrr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwdlakc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjejtqc.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uomyqckj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2oggzhblr.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqtpejt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwlvhrc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2txktvvmv.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ognquwiw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xiidwddb.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nknmftqu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxmtkxu.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yayexwaa.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjafewsp.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzxzxdd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtfdvpw.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zptembwc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhashnt.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwtblie.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2kadiclix.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjqqkcc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdmvrqb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2uijmaqns.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqdxgcg.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2glnhjhgw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iotdfday.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2asbgpbhz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipztibmj.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ackiqaoq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbyquqz.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcjnnrw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ayuoqkoq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgyzjjxg.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2tdctfkom.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcpifld.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdivrvm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2syvnptsi.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nqacpaal.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2scmzqiva.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xjttidtq.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2voxvitgi.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qbujnaov.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2mozureqc.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ywaqkfqf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2kocfpojv.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2clawjsqo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2clgogovx.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2elismyhm.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghejotod.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtldomql.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2jidhzejh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdldunj.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2biledwze.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ashartry.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnvkmmq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmrwkjw.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pybnwuwg.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2syjzxgla.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2eakoscdc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrrzbpf.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmqchsd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2uekoqidy.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ackcbfhr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtamugmc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2owqrhouf.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2uklkdwfy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxowqcwf.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2foxuybcp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpmcwyd.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2akajbkwg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2myhxglyl.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpeebzm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbeqxkr.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvbqhtf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtftpnf.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iuawyzzd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykaeredk.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pujlxqwv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijipsjau.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdnpost.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwaiuqz.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2aorpujis.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bymnneqn.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2exsnwlis.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2qazbqgqo.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmjxwtk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2zyavqyyq.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oizdrfjn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2caieijuf.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjgqxie.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyyitvv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqmzfhv.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhwyzyb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rishrhaa.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsddmxg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgqtmhz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjexmaz.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2uasxvsib.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgotyij.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnczeir.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjkoocw.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2viikaozj.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2xcuccskq.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxvzlub.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2biphqvja.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkfwxgl.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhxjaou.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqfjxzn.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qirqehdb.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kbufyhqg.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ypswlwlf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2urlmvryx.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tywxcdwj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2awnwnirt.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vklppgpq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnmgejk.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2foqrnvvu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jegekfqk.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2enzeqlol.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jenmudmc.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2swaxvpef.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxujhsc.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqateysc.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bugalibk.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2svfjicud.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqelmvp.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcmqkbd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnrcnml.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwwujju.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2frfgxhhd.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2vqogdtbl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qxogyqhh.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxnboxg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mctwtjhy.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2czgzmdkh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbmdwse.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxzyccv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzwcelo.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jecvglcr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2olcbrgxx.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2eicnyicn.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkrvljg.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2edfjtfrf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2broreyyi.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dynvghms.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxxoqqv.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhdmqbq.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2boxutnxy.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbppswn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrkmwfp.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2flzechzs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzccourm.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2dbczqhpz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2phfjjlwq.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgqagvk.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsrdrhk.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2kmuehsbn.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ooaxvapg.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2vknotvut.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2zcenmzqw.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2izcbgrsb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxylqil.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfqkliy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpxfqtz.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkrjdhf.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tocnoxpj.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2gosuwzwm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atymatzf.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2izzurumo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2jctfcxnj.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2rlksamyb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdvumnp.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfvisrj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2rumjlbbl.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fsiivulx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2vuaqdvtc.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnolqvx.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2afeogwje.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzahnof.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrkjlrh.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmzkpvj.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbklfyp.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cvokdyrs.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2haptruwu.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mvomaimy.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fsiikyjd.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgvfiyf.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtneebx.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2demdkgab.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gconfyfc.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cavcgmfu.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlpdgit.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2slbefkzl.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgrswjy.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2gukzrnlv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2swqmqgzo.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rijmvxcf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbxmisd.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfdogsq.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzajubd.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2plzdljao.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkrkdxz.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmacjol.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrioyuc.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2gkylfcxq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2wddfqkpn.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2kdoycljt.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vblpjlbk.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qctbrsox.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxtxwkv.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zywqxswd.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wsaprhcm.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2aagbixse.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnauaot.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwphmjy.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyxkdqn.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2webyterw.html


<!-- 参考信息 -->