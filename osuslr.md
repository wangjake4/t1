代发 wailian999

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnyiqbn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2qllqtnbc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjaiitb.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2icuhxrik.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnouzcx.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fczccvee.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2urdngyih.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnrvtsq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xobkumjg.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbjzotq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2fimufysy.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iivjhtur.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2amiidnlj.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbgfcwk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfikfqde.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2djaiopfd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2exqmyjnt.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2axzizubg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkbpwgf.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2akiknfiw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgrkbei.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xohhjbqa.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2exhyhoui.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhtafzo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvrpuav.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fovvkcmv.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jimkjoxg.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkbltqa.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbwdsba.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnjjbwt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2onkgcflh.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2krszeswc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmvhjnh.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2skszgdjb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnsmvis.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ytaguvlk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yknptgef.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2teuytqpk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvxnrbj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmxtejy.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2oegfjnkc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnsggga.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2girgcssp.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgeihti.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdjufzq.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2orsrrwwv.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2swhcczuq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2clwcorcl.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbpstfb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxwyjwr.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jffqllxd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bymvxvda.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2vkglntue.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzfavdi.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2smlcyzuy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2blgqkhjs.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlvcldb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhqbhqu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlviqfw.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnthtwh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwmryfy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdvfjfo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmskgpty.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bduquqan.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfnveju.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2swkbwihs.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlozzkm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjyxibr.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oozrltwt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhbggij.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfowpkf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxcukry.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2puqmzsvr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2owrjmqcz.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xhresmfw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrzptby.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbqxifp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjljyolb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgcesjs.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2njyfyvpg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yusxykis.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvkfpzh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwtgzte.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcuelkg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnllmbn.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2tphkkutb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvcldtd.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2eeryhkzq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rpaysinc.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2relacqwq.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpjllxk.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2awaqaeuo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2msmdgofc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbpawtg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtkrnnv.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsrefgu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zigomxgv.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgfwipt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sttdqxts.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2fpshxydj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbhpavb.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2bmaldtyz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnfxueb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2doqtoukg.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzcyhju.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqwasjc.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2djgkmsor.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhutoubk.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pwefmpoj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2opzvkrii.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jbaapfzl.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtyuklo.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpvbswa.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhxozpw.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hyppnkhb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2pydpnbpy.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlfwxrh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjnkhor.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2oaifeacv.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2twkzfgpa.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2camoindw.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2dogrfewp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2xpedpjhj.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfxicxz.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgewqbei.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2wcblbfcw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2yqeicbfj.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzvvenl.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqufgrqx.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2fykaswxy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ximlcnqn.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hasfbhju.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2scuifqdv.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2athkkrco.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvhgckq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2wstdutwr.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2yuaqjpuy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2anlvsxxj.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhsyzjb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2cocuqfdt.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rxibbsbr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjwfxqz.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsgppax.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2gmuasdtd.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2nafokqzb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmqxzut.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzjqrse.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bykdqzgb.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fuyfoavp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkfjlww.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yuyupjwu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnzuckz.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2czxghsxl.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2crhlnxvn.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2naonvjlo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjtopto.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrveebr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2oblvwexv.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhwgqee.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2eioskdez.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqjpaoz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjfifto.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xujpqbkr.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lyoeecmh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtouqxh.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2jezsqkrx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2aszcergh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxogigf.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkceohl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iaprdkqd.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vxeivypw.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2bbaqibcs.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2sgoubyoh.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrqljpv.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwlrdel.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2baelzylm.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzrrrmb.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtkiozb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohuwpxik.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2yserrngm.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ywytoqdh.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rdszqmtp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cphkbism.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2quvoitiq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdbflkn.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jygntgld.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwenupg.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nhaapmsz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmvusrc.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wtefmyvw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uvorzurf.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2frtidjrz.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2noezabuy.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpdpadj.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbecghfe.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbysxlza.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2coddacsy.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uchzzqhl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2repqhpmr.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2omklkdzb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfdobtv.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrqpezm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2adzgahjb.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxkugcg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmlpuco.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hpggmtxi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqiticn.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2pgabikvg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2heaszagx.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2itrwhmxn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2efjbqexb.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdqpyyf.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tngsitwu.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpsqpst.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vpccfrbe.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2eoceqauk.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rgirmxew.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkqpspu.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aeujsyyc.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rsieifto.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zmeemtzc.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbiphmv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmhrxfs.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjxelet.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzfiwbd.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ldggwznm.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ywslxpfp.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhwptqy.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxfwlmf.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmimrau.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwzhrwq.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2urkmipjm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtcynxh.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2boydnozz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2odijoity.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kryokjpx.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kahjhndp.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxjevla.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2agjdaafk.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhaiped.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2svkdygfg.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2qisikwbj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2aicxcxpm.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2taazhsrs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2eebgfaui.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzcajyc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhpxzqe.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cncbmhtl.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmzyfjm.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnvxhag.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2imkqrfbm.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjjmmrm.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qirhmgmg.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2piqifjla.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjxntbx.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmikdcz.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2poodkwfb.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2itcwzpgu.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fryphkou.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfawmaw.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mpunmqar.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2egykuevj.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqlythb.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vapfbakm.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2mumvtknh.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcvkbar.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2gzllktrt.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbkcfjs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbnpyms.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fspemevk.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfxvjkm.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbwrzuu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2cofucjvp.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfgiauq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhwoair.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2cnaezjbn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcqsvmm.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2pyuupshl.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfgjbqh.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2anyvpimz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjwwame.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2khftggkr.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkbqewm.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2pjciqqoj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2rkuakkuv.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcdbczu.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2nayldhux.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2bstttoho.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2aiozdsob.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgcrbmk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2siuntiuz.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkvnmoi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqvwoly.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvjlapn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2aalhsfkr.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcmrufc.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqduzvn.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfgsihs.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdybvbq.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2seqgolbp.html


<!-- 参考信息 -->