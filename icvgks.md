代发 wailian999

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwozusm.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2dxangozf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jffipvhd.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2aopdrgwr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvisecy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2nwinyrhn.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjrgxgm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2eelzcnbb.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2bupfaqed.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwmwozo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzwbree.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxfumho.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xikfzqwn.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgyqaqv.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2olrathin.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nkialduy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aobakytl.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpyhmnf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2jusqrwnk.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhasvld.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpjppml.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbqztyl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxztvvq.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kmsceasy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2epqaqepw.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yamhhjlr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2krsynyhs.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqmtmsd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxsuwhh.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhwwmgq.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuipqect.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xdndmvwv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ziltbjut.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2csqfmkiu.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcoyics.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfnoddq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugleburz.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2glsxvexo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yydpndvw.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfynhrk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdcnxxdf.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2shwjovfc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxiuqxsi.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2twpkajwe.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2aobmjwzs.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jobewvoo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqqdtzv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtelfxf.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2umfjjvjf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2edjfphhi.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2uywyhdrq.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2lnceazbr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2bmasdtfo.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwedauag.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xdeyibvu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hozrmzoe.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2axveddfx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvhgxle.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gozsfyni.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhucxow.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2mzstmamv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2elfkeeda.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuypnae.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2zckzjocg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgdmmxg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyzpgzp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnwkgpl.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jctrpqys.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvhbatm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdoaelq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvsvcwm.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ttscbfcm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2hqykbaiw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwffbvop.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpteugg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzrsllg.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kaarqwqk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqlwkfi.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2izgmrngi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgoufcx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnhbxqj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjeliit.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zigngljj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxhsshy.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2djcrtpya.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfeuccz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrcmqkv.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2tealxhqf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2llpjxjbw.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2prycayzl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qoepfbze.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sinarjok.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2meypbvdu.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ivytmbhi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmecjufi.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2emkmaagy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2duzlpsnr.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2drmipixg.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2sijvoxdg.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gftfkbvq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2idfdlfhe.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnxdkbn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxkpkvz.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qzungqbu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpghgqx.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqighej.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zltaffna.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2kenazfts.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2udujrpgb.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxpiung.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2rvefrpey.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gimzwila.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjnogra.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkunalwj.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2sikfzzju.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjygbzx.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyjmyrg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlzptra.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgznmqs.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyxqpqr.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhudgna.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2davleukc.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aftbxicq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdjetzd.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrbbxtx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebegxksk.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtevfey.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwgxcpj.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oftshriz.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2mqheaacm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2crkzztmy.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mbapuloj.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pogitpxq.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2yifoaiwf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsjutmk.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cotitotz.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hupcsubt.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpebqwx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfkewvq.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpzpnqz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2vokucabl.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cdavvnuq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhtveho.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2pwndkqer.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqsipjk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgfcmez.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2hcprwugg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2zojofiiq.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vghwbify.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2uqyrlber.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2avumllgx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2swxiqyrv.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2dfyrpafr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqsbyrkd.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hxihevvg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwigkbcu.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hglofiwa.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2subfslhb.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvzgyqu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbqfutk.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2dejmegpj.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjbunpm.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2wngbkikr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyoilpkw.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rkowjhmo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2wojeqjed.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqnwutp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfaulmns.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2uadpvkyh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2rtsjdsoy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrridjy.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dnaygqru.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzsoqog.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2bewkivop.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmcxrru.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdjfvxe.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xysbvgmr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gqeiqrxq.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2psppamth.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbyomyo.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2frnhfnsy.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvwwmqy.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2taclfadi.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrwytxt.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjxtmcg.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oapdlalh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2iligjbwp.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhbkfzr.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oyincuyx.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jlucefrd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izhwketu.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrjownh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpvdenq.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtbbfdu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bvuxdgln.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcauwlg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbdevrs.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2doupitfh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2udqowzdq.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2kppdoqbl.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtthupq.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2errybhou.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bublmuhw.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2utiaansx.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2halwmohi.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xopkggpc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdbbzes.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2oecqlxlw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbvserg.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2abnlqnzl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cnshvuvp.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2syarrmzp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2byfjfaqu.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kyknjlhn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tssmmmac.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2zabmjyem.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nthkjzco.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsmajpa.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmylsll.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrwawrp.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhgjdsw.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfexouj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eokrfmqr.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cngcygov.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nwofzofb.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2prnzdfvo.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bsolndit.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ublliork.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjqdbzr.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2orniunfk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbumxwl.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfozpnn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iitgvlyr.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yczqrlwx.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2gqemcrsc.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkglaat.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2norwfcfl.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqszbdb.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2kujrzqym.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ijyqhgfa.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tesingsp.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkphrcb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2szcypstq.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uokzkmpf.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aedwlxiz.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xnuvxpms.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvxcpqm.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2eiaqfsgi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2xpowfbfs.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhktutz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqsmmga.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxzbete.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkmwgsw.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrlaebe.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxoamfz.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrcvjrb.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmhowqb.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgsitrj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgwyldl.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2eremgufx.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxpvytk.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2somgulnf.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjembga.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lykanbhc.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ffaarxhq.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2rkaysfvm.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nqucavco.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzmdzzt.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2cgakrkjq.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2okyubkqj.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhnzxdz.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgcctsh.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2dsytnbkt.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkwsgpj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2zfggrske.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2deerzkvs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nimmxquu.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2frclzytj.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gjyglzcw.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nmopwjvz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkyeqdk.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kojhyneb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2smcagoey.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2cokaglec.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2lgunczaa.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2bitjefsa.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcwsgio.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nlydxwcg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2uljqmshk.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qeymsite.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wagbvcjf.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvmlukn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdofiqi.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrxyfgw.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ckctdcdj.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzlpczn.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2uusgmdxt.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kxolpsnh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2lovmjrvo.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xajhivqo.html


<!-- 参考信息 -->