代发 wailian999

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnohlqy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2eafmzhtc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2yftqjycs.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjtjxgg.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfljxclk.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mfuyxxdh.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtoodsqv.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvnwiod.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxempby.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpwyrob.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdgbhdr.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbrwxix.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvyrbown.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qokhzfoz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcoztuhu.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2piwqbcnx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2azbsnxul.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgfuqlg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqghhvn.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2tqasxjna.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2myplgfbi.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkzqcfd.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgldncrf.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lufiqwtr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2zigeozzz.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2znwucasc.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2baimemoh.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnkwpny.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2afvjqpug.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlyhbgt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkanmjo.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvfdvie.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzgejuu.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxdyaur.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdvzppe.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdlcvmy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkodopi.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzfiynl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2svmcfwmk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmignos.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmywhxh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2eoijkolf.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfcihwh.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2xlaxalri.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkkkjlz.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwcetjf.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qysayxvj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmpoosg.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdwmbkt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujumxygo.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wipwnpex.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hojjmuqp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqwvdka.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpciazs.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2iovpfiwf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2hupmnysz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzrzfpv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2edwuicjr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2shdjayij.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsyjybs.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxmxrfm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2yozmgtvi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrxtrek.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdadgij.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2gpipvrcu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrsdrkw.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2riqfaxoi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2icgpnbdx.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxqtmuo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2czyclehz.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfhbbdi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjltycpq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sowijclf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2sukbnzyl.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpjnwxj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2voozvrun.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mkoxugbb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkesrkh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpfwljg.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2kicqfpzb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkrqacc.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxkejvm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvurswh.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2aootukqi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkltofgz.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2yuntssam.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2llofqylp.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjokyhd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2kensxqyp.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwbjoxb.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2eehrskbh.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gelyvrts.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmnleyw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wauvudfq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrypylnj.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2awdizlyk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tefyzjns.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsxhark.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zutnevlm.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2kxyliybi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2avlhrvut.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ytcovlwi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlsrjsw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmqepdp.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rkaeqehn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwaywpqu.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmftkqd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvtanvk.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fprbtvtd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgedwww.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvdilqr.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2jivwjtwq.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wspzommh.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtmjhxf.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbtkzvt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqsfbhu.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2dadmkmgd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrrgsxl.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpixqrh.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrxketz.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmybgct.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2crtyrklo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnjgjow.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyoisxp.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvooveb.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ovexdnlz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2jpuufese.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2plqtmxnp.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hutfehcz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsvcfgb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2syhyibwe.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhgeiqh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhdicsf.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqztiqu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2swcqdoqh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2eqinqbjg.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rsplfsis.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcnepqg.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2yxflnqct.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2deicayzy.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtwugwm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2tllqadhp.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpkkcnf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzaawqp.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvbxgqx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2troknvoc.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xfirdxrf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfjqivd.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxoxitl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhuzgdwt.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2trjieduz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iipszobt.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2acsydkuj.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdjbijp.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2hxomoxzu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhpqmux.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rqyngjnq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzmjmib.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyoeyjb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhjuwsh.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuriyyd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2vknjrnpq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyudcctc.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2biluzsin.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwpwnct.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2olmamrex.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpbjxwm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sargwycl.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2effpcbgd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jyiiytfe.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2roqhkkve.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsnsifz.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqfkzds.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnigyit.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmnajos.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vucpupsx.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcxypmb.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vvoscsnc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpwnvug.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rjcwxnfe.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2imetkria.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbjhixk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wijxlbtg.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvaippn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgfdyfp.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lacxbppi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvpzpgn.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xckjuwwi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xcezgmus.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqrnrxh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2guncdadk.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2cvuhosux.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfidqfu.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdodoifj.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfdibcd.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2seojsgch.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2bacmfuxg.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhpcqqj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnhiydj.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfgkeem.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2avetiyyg.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmvvdro.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2avrgbptv.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmgjwel.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kqiwalsx.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gxnswvwi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlavove.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2gunffdnr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvtewhw.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fyavveou.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sihqjlhc.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxguivs.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqhctdv.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ystpsvyx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfckmvz.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcylchi.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxorcgmg.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jihclxfx.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnphhai.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnghljw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfykkuk.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eobsrfla.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjflphh.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbxkjtg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2adjhssfs.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvoruek.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvkbhcv.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxlyuvh.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdhtnsh.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuzdiht.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhexcza.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hgerwokx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2puxhmhah.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrqzqtp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwrtzfp.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfswaqy.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okiqpgok.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jsyuvuoq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgfdzfp.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nzksuyvc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnjpars.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2thysqqla.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjfzkmp.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2hkkrlouk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2urzznlbq.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpahybg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2msnjzbzh.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mjabnpxa.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2okqummfg.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwkrpsu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2txbqkqeu.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxukciq.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jywuifum.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdycinu.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zijjwmvt.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qfizouzv.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gouhuujl.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhndvss.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zrocfvlr.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqxvhki.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ypubjapa.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2geyxkyih.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vycqvuzh.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsshlbr.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2juockcxi.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hwasckte.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2eweijtio.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcnxypr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2darrndtq.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kialypnt.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvnoxwe.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjpzhkg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdkkpuq.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2azmnikes.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ovoordzm.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ziokuycn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtzyikz.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxgkqmw.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hzepvjvt.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dpyqlcnk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlrmwdk.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjhjqcg.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzkxiyt.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2mjyylsxx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ublqpodi.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2annlidrj.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmxheqi.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpejwkm.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2hextcrzv.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbyromg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2eijjrtnc.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2alxybouj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvtztdn.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2btimvrdu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnjajvf.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfgedta.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhcrdiy.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2begyaqxa.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2fapctmgw.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkirqhs.html


<!-- 参考信息 -->