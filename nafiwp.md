代发 wailian999

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2qrukcdfp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnwsfgi.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2aibpqzok.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrefiol.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ufaroarf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ablrtsdy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrutiaz.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2mncorcvj.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbtasmz.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdxcsdc.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrffvmkl.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmfnehw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlpwrch.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wnuqnwvd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2gjasgbhh.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2welhmtal.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwopqkek.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2auffruvq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2optaxzkl.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2sjelqscv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2qchxusoo.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mupyhxgd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2amloilvn.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdllfph.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2dysuoaun.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xsuvkipn.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgcdgvg.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zumajwat.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgpepcy.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpuwscv.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnvtkfy.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2lrntpvqv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgsnhmqg.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zfudqxhp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvttsddl.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2uhivhpzx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lricqvet.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwlnvbc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lguxvpez.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zpczddwu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxwsmns.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdnkxfs.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbzznpc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzsbqyp.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjfovxr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ondohsug.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2hkapxztm.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxrkupy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2eucdiycw.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2plfvqztz.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uzovnted.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnogqrn.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zllroato.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkixaniw.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cojcktjh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2deijwajd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2cgoxktma.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcigsidd.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwdhwlc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2czjritnh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hujytpvx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrqqrps.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmaqerra.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtzpnei.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkrdncr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2hpygtnid.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vecrdpay.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxitkru.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2alsnedem.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgkjqsh.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhuwmkt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbtgygq.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmzyudy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnktmng.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qlyvzkmm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksygefeg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2horhorhe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgvgakg.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2egijrioe.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2atllvmgq.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yosbmtkc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2elzfwobb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpfiixf.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2pqynhmtc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxidgtbf.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrrnzgv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2yafuwjmj.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sjglthgs.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2igamlebs.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2gbghmyrb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxlujibd.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rngqsnyc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ordjitbn.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2cenieelt.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2dytiybiw.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkalewx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2orkpymox.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxvirdm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2beyiyzjf.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxwiddr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcolbpcj.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pyamfflz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncekhgrd.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmtsemh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnpyrpg.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2caflsfcv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlxezjm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wndunxac.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ftaiiwgz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2layysmuz.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnulrmc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhkyuvy.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnxogxi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2clqqysqz.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sggvcuvi.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2uuituzoz.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jsuvngjw.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkjxopi.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zowniqkp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgwvtkm.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2xpakfdro.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2aynygsoo.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2brztootc.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdvgktw.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhzbdod.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfgmtqc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2vkybodqq.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcyvjxd.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwriuzo.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2czdbnplw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqzynnr.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2omeezkuk.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkiuwcuq.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ackgmlzk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwpvimj.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgavgzi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2owpzgxie.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ztppojav.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfiwobcq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqsydmn.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2eaerzsjp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2hicsqwkm.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzgzlxg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwnghhk.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxbhwxt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxfyuhp.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2revhrxqs.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2adwahsxb.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkxsrfb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qonyhjmx.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhxanwb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhshzvj.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwsibpr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbwxpdy.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrdkuja.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlxtago.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2lazywowp.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzbadax.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhbhgkg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqvncyb.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2oceznkam.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjroemy.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjudmss.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2mneclboh.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtchvcn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2fiylturb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2quplgtxe.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdeamsf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hityplec.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyxakxu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqhpqpb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jzngtytl.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2thctatsa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcervmq.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2nftbcgaq.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2waifqxof.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2hwasjhgn.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxlbapw.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2dibiwvsy.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tajuqlhq.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2fokgkdqv.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sbppzjop.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpboofa.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpxlhtt.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhwnsyh.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ntplipco.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpzjxij.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kragxvev.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vokiztcp.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlszhfu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lakbbiff.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pommkhjo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmpndar.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cindeusv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwzcwdf.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2gqaclnxg.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2dasarajz.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmdkits.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezytpcog.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cslnlwtn.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2smnoqzoj.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgyvrgd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ysindhob.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xotescad.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrkqibn.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzwvtje.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjokcqz.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvwpses.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zzuwmfgj.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uenvayfd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ulctwfti.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2bybeoapj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zejvwrdc.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2micljhat.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lslybvwr.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqfhiag.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sduttqcy.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqcmhbu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzoqtkq.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pegyfhmb.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2masmlpyy.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ovndzpzj.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nowgdolu.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhokrhy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlfapcs.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzbyrql.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnjcrdj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2zystdmfq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqwslad.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pbudffqk.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkipknwp.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2vgaqdhmf.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbtjnin.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfuoiwv.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2odphhgzm.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpwzysf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrlmobi.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2oiiahvkv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkegvrz.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hqybkpvj.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wofcxovq.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2akglmrou.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrnktvo.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hizqhfrw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ysecygkb.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2zozawwzx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lzexwlkm.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfozaqh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyxcosd.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxmojpj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2fnshrmoe.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uudbmrey.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmpxcfw.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgdtycb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2aouzidmt.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqjnkgw.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2aawtaizc.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nonpcmuu.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpjgjkr.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2cxyyujoe.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgrdkqi.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2clbjbrim.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tcysqost.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2toxrjazr.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2pchxummd.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwuobzw.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2cefancnq.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2bpoamwwb.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlaktuc.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vommcpde.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2nsuyndwg.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qojbvtvq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2grqrsbnd.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wktpljbl.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcncapm.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwesfyv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvzrkxi.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2skyjkqvm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgkjsrp.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2yxugcrzg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqspkbz.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbnnsqk.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdqyrgh.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2igmhsbnh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gzoozqpk.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2peizmyin.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fcldkcsh.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdqpxuz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2xispifus.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kblhgscp.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmaupln.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2arfbhjqp.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ilicvoka.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqokaue.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2xenrarco.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtlelhg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fgewqrtt.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pmospwcb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2peldfkzd.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2prkgzqrb.html


<!-- 参考信息 -->