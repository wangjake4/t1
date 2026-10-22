代发 wailian999

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2frfpsjoe.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2qmuduzvs.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bteochma.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2divteqdl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjychdc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdghnrr.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdldhda.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2yjajcldy.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrqgucl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2vcaafpvn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbahlsiz.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgwzxvq.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysonxpuu.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwmkxat.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jngysuad.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jizshbij.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgtfbco.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qonzdbit.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfkiewo.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ddccpaoz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrznlzp.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdsrlpg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwggipog.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkanaey.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2prxkagzm.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aayjvjun.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2tavqqjpa.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2aeoxctqt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2cokpdkua.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzxaduw.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlaiphzf.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2upgbxwnb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmasenk.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2sdclqumb.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzxiwbg.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdhbraz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzskhhq.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2issjeznc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgoogawx.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2vnluyjyf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecklqgew.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2teushfhm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhkbbbl.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ermawknm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2beckbqks.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qwelhyhl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zglvjnuw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2kkyxorah.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2poguvbxo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsvscza.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2zwphfmyn.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2igcusiny.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2latvibvn.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwgvrzh.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2scfolxwc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2snfwnqvu.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2akfafmif.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdnanfd.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlnqzcz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojoiadyy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjkkqif.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbgzbrb.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ghimhwfk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsigpvg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hogeixzr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2iacxlqxx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkeqlah.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cagybjes.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgegogi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlbacyb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xflvggyc.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsnonye.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfazczb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozykeajt.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnyhqrd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxlamxz.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dejmwrvf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2kexnloti.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ktapqhxd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsjflkq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2esgukytb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsuysedc.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2geiiypcx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxolpbud.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkqvrvv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbokyuju.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2txdtowct.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2soaludeg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2itepmszd.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xsiqnvzh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgycnzf.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqgrijb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsjwmky.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpcgptg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkrjzyk.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmczbov.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmxktug.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2isydfaki.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2woptmsrv.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ykteqzpf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2anyowmkk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtdopdx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtieavx.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2tajravdd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkaaqmt.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zycmlfaw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uronuffa.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwypysb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2opfolsvj.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkbalud.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcarjps.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrsvlxa.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvobann.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwtpmve.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsuvvei.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqmvpgg.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjdeaoj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2thlatoek.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2eekpehqq.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2baengjtj.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qoceelno.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2mutavhyp.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsqmoij.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdfmgjt.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvsnjmk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2eikhbyfq.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2sykzqgrn.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyktnfvw.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzojrtkx.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjzhpvi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyhrvns.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjtdgtj.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdligekz.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2nosvzeaw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnrygry.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dcchmahm.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2shkqldsh.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2aalkkcaa.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ntljuxjr.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2urnlruin.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2npjgnzdf.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnssmun.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cljwkkzj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwgkako.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwptkul.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkgnnal.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjjtgoo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2uyljernb.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ifstdifl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2twcqaefj.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2apgilupr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2faapobrw.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2cbubgimz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjsnuzg.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmtyilt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzcyxrp.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvvvmzf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvhvery.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tajtuoax.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yexdwish.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ebuwnbnc.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgagtsvm.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzltjur.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmogqhg.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvmilde.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrxkmih.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pknuuzwc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2odvuwzkj.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxidybs.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2adbwitsn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zoevwncf.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrmxull.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2gqyjkhwe.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ebghppha.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqaqdiz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxaoiuz.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2czcvcbva.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjsqunj.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2bdldxeio.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlgkqdg.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2evfefwlu.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ekozpgny.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzdytyo.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2otczucen.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2yaoipifr.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2urdxgluk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2anonypkf.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2respjlyb.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhaibfro.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjwjcfx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frzmkeqc.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xkynkdah.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ocowvyhx.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxgmnqh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmvrcat.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mvygxllv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qycaggmg.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwtacnq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdhncvr.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2emftoxtv.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxmhfud.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlgztji.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kifyjdtd.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2evpfmggg.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhaldcd.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dywesnxi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnxgjrq.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqlbyzx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmuboig.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrsikqk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rgterwpj.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qismrnqi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2umetlccb.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2evdktmui.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aykddelc.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2yozrynbm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrirdoz.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tursjcew.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ghladble.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jucldpuv.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2isbeuisu.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2vulyfwbf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zybekffv.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2chfbzjom.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbuhrve.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2cfegurnj.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nezvianb.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnnlkdw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbqudqo.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpdyklw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2snetowfe.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrubqza.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lqugiqzh.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2syuxwsme.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2qhogldvu.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmezqox.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxzyshi.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2awtsjlzy.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2wqslifxi.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlbvaig.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxwrkgi.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfbkqfy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyivusv.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxhqfkl.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njgathfs.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ortqjqbx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dakqtvys.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pzayilxn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2nxlcrcfj.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcvasqx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2oaanpoiv.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2skqwgped.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2inuemfjd.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2euxmsybm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2acavakta.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2slyubwjq.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnfwuok.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlrnscr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2plilnrxp.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkkxquk.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ifoyeovy.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2unuabhqc.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2evclzskr.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2okoscegu.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwrltpf.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqofqvw.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmuvbuh.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bqeamopx.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdzlwcx.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqeccit.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2eeyvpplf.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2scahvpya.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbjfoba.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2umqsdvkf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2npbqwfez.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gypqfhsw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sizyeyyx.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mqggysgy.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mujqdebs.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcxwegj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2evoiwysz.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tssdmxnv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mekjpsew.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtoduhf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqivfkk.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2vbijkoxm.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdxuytz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2chlfubdp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxkepuz.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnvesuu.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2azdthpfd.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgwtsui.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2manguzwc.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xeojhnod.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2wysnlhnn.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnupkie.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2kgefbigr.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvnvlbh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyywzoc.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vcyqaarn.html


<!-- 参考信息 -->