代发 wailian999

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2cciuwzkj.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2mujkvxwo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2paijmajn.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pkyqxrsu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbvrqit.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2suwpqzgu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2utlmcnag.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqugphc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qghzygbq.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2lsualmgq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2evjgljrm.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2bclfmgff.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyihmsj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2musdfnzu.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2elopdzul.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2umxtwgsf.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjtvafk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrgjdqx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpyruhuo.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2plmtjydr.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjaasrn.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wnuvmbim.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvjtfwo.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwqhxlj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zycrkgzr.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cpyrgjex.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2aljcamqf.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nksepodp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2fukffydr.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2esxihacf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jycfslxu.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvunirz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2brosonoq.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2alhfdrot.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2iaiucvzf.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwzrsxu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2mejkqqce.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfxtklm.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2igybabwq.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzwmvwy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2gojlzqlo.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2svzbtcop.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2otuqpiim.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2duoxxmtj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvmyomu.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvmbmrn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhbenvj.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2klhnhwru.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmsuxps.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgvszfa.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wahxvrwi.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqavete.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qihmtxas.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2egkkhepo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgktzmnd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2zguygkzv.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2camvbdpx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvkuryi.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrgqggt.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2joluakbn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2knwqkctc.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzvtqbx.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2flciretj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvsrlsdq.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tormgord.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbytefp.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kqseszof.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2txxdutst.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjgfwaz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbpizus.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2isqmdhlh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2rvudeuxs.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgoojveq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2jiryxtny.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcirknaf.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjynmyd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsgtcfz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2qvianklg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2smpzcqxu.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2objfwmcl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2atrisufr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbosblj.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qemlijkj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2sffoucxo.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnlxpsz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhoouuxn.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nsyqprzw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqspiccu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uxebudqv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xczpuyek.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2raqbourb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgggsqy.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2liuugevq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcwubhj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbalqau.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2myhnuyvj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2oztuzede.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rhryiwfs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsewjeq.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nysqyehk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sndsygfx.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvehhyj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxxalrv.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrokjik.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2yheinorr.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkxzpos.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2omitxhxt.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxseerp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfhplza.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2odmbamof.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2igslgpaw.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2aognfivu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2anccamvq.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzmfmmr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfxupkh.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkbvkkh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhogpel.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrkrokn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwvdfdy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yobngdwp.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2efpprqai.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkcpcge.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvynasr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rytfopfw.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ffuxnkbs.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwerewy.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2buydobjh.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2bveiambh.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2iplsukdt.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuizxfhr.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ifibaxco.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2bykfwcae.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2jhforcty.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdnyoke.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2xuunhlmo.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjobbuzu.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzeuxtt.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbulqzz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2qutjclwt.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2euzdasxv.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqguegup.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2pngvtiwy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2xefiygrm.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsdcamg.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2derlmdtb.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2yulintrt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfdihuu.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rntxfksn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwmqrdm.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdutrmt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2biebgodp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpdblkl.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xsutrydz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbciccef.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbspmkj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcjsvux.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fcctfnmt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsjgaxe.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2edfovcyq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2toesebte.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsmnbti.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2numhvnhs.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2webulqwr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2juqxjpbk.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkbnexu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oidreqrk.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwzurca.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpbfmsg.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbiaemo.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iikuaahg.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2udfztecy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ooklohzw.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2irurpgge.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvmsgfk.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2klpurkbk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgwysvz.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kubpvnud.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxvvuuw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctilbkos.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfghuxw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rwswtvfq.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvuifxn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjnxhvo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vxppsapd.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ggsmfrxf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pshbvjgh.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2udwbzbxb.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2aifjduyn.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2lexipfec.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2suflnikq.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pywjrogo.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2btsevpel.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2yitwufua.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hrocfcot.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmihogz.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lgciuqeq.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpatmht.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2amfcsxfz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kteuvogy.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2trdcdlcr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlitctz.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fepmjqmz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjmksnf.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2esfcspdx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2feozznsr.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xmylepvl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfthjyz.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqsyzvm.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwidgsw.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbevqskd.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2apnbsloe.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhrftws.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjigdzt.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nubqfunz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xamethqv.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2agyhkxrs.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2navvmvfc.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsagefw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dglzycug.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yeaqjasm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvuicbm.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dybngfad.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrqrijv.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2svrgszac.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2evbpngye.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lenourus.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxzqmjr.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2amvfajzf.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fuybjapx.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcrkkff.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbsqnmh.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsztivm.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2buqssvhr.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2exxxoget.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpwpwsi.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmfzwed.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2szftxhwg.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzqmian.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfmczak.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2hryuscam.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2owvnkjjw.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2klpmqtdf.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2yshxxwnb.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2etutosay.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdoqvhq.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2vidosgiz.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2maulnzhd.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwzkxbr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uxodudmv.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qaakucma.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpwjwbx.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mufwxiyf.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygekepfz.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwgufew.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udbqzrcx.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpvechf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2unfricmj.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2gkamodzg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfmauoh.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2mexlqhbc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2lluxwlbg.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fuczgwiq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfigfsn.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqsdhbi.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwuuydbm.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ircwuqbb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2rscownqh.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmoantf.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lcinvacd.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2scpsjjic.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2apjqhzqv.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2brkanord.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2udteinzk.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2erxkncar.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2afsmskia.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qsheidim.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjydfdn.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvkldpz.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2shvvdlkj.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fubzmoob.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2exeeoyay.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2gtahdkep.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkpnacc.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzmyvua.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wigrxmmn.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2erolvums.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xxofgsss.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pmttkhat.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwzhqnx.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2oigqllbe.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcbeuak.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2guebakci.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2zljrlvdy.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2lisccxex.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfjmfos.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxkwndj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvbqova.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2azafoegi.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kxindyrq.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkngvau.html


<!-- 参考信息 -->