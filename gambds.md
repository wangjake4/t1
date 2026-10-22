代发 wailian999

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2fkevsgwn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2xkthuinr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2rndhdujg.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2aleulync.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qatnfkek.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjihqol.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulguxjjn.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qeprpxpi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfukqnvr.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2eidceytp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2zchlglgr.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmkbgdl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvwqrmw.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2impnizew.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2phynffrw.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ycysomcz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfebvml.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpqlsik.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrulljkj.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqbuxid.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojclfqkm.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2eoprgvkd.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2petevggm.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpdvbuu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwbaruy.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qcerhxzy.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtftswjh.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmvzgqf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fflnxcqf.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2htvzrfyq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgprnaf.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtjwqer.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgubkzej.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2uezaftht.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhmauit.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uirxpvdx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jepugzlx.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvfzgtm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2czthtkod.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2bcoeivex.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2obliawbp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtxkphj.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2vspsgsha.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2bixopcns.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2udhusiqw.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lorzlxyb.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gjojghye.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2agqzpaek.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vckyyuva.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhwpntf.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yvodobbl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmjhmhd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2bknoijdy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfnzwuh.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbhkvbp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbcihcd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2etwwiiwv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2welskusg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2creokqnd.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wqamgmmx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2afjhvqha.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2iqckwkpm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdqgote.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2iclrblet.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2bopuievf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lckbenrf.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2czgzmckj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2aszscbak.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2reqasnhc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkoeukxg.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2izkbxkmr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbytgqhj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwvnvfr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfhkqzq.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qqykipdq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2apivdezs.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tssvompm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2agmcaidp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2itgxzpwz.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2hfldqpvp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjryxsvi.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdvvjcm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2tjciuqwp.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yybonnit.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwtyjbr.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ydijktoq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uirsuzxn.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsosavx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2lciezbza.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2opubncez.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsuyxtyf.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2cmaiwjai.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmwnpqh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvrnlla.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkuneevw.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzcafkh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlfjpmg.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cdymjwhy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpthsxv.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxoyyty.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2clewfsms.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyxrenm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlovizw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywatrwok.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ftatjelb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uecrjnqz.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2febuudrz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjjsdgq.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxumkjj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzytlsq.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkrejoc.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdghehnz.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2axwhlhey.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfwohaq.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mztrxqdj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2qalzmhsb.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2stbyocnx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrlonxq.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqdbxlm.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqurcfyv.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjustmrm.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2rcaufpuw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2aauzmick.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsbfaey.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbxnnnp.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwxcpdj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2xckbhyhw.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrdjbuo.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hszpfqfp.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2thtjrnko.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjydtbh.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgmpuix.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2vsaznqaw.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xctibded.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxhnjtm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ykceadhw.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mspbmxim.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxbhexj.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2opaistzk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2kciptlfv.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rnotdwjf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqbaqtu.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2cdszglow.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvcxrfo.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2qujsxegp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjrojqx.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2crxdwzdw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxsiuoix.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxrzqpw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgatphm.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jraxhlxp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlxkhmw.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2souwqyfb.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvpiluy.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrmwxms.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2uiuysxrb.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2myaanokr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2buebrsnb.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkiropx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2clnlhydo.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbsldkw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbgykqv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgcvkbs.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2clxspmmh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pkryhlel.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2docjnmgz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmuxdhpc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2csikvggr.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qhygurbb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2acbctdno.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcpcejf.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2svtgdvzr.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfnumgv.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2uredsmcj.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcqljfj.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2okokgbwf.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhkntpn.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmuhvgq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbbygfi.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhbxmth.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2itgjugeo.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2psbdipuk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2urbpzzwv.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dusasdos.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ougcxzaw.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bmuufosm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jntrkyzu.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzhqgdj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrozick.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2arrpkpxw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uacltpdf.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2nqljlwmg.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2vndarbeb.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhaajnwt.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sneajpmj.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvvcbqb.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2anuvmydp.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hetdizlr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnkdsex.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2orrohjci.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnkjrtd.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgzdouw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2exsddcbt.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jloglxfo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nvsrxeud.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvxpcnm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2evhfljfs.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxbmuoy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcwjsdp.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2igdjpwwb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wbluprfc.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2awzmwghx.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tztytoda.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkogxjn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sejlqcez.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqljodo.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pierspwc.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgidzbe.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oonafhur.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gesakcgy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsaamew.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tpttgcpn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ieoparan.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqmjdhb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzcpxvy.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xmppyosp.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2nsyfiltt.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnvxefe.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwtvevl.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2gumwexbf.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2opuamrqu.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2awngjanh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwdwikz.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2uovfwbpg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlcmeaa.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rofuxkcd.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgyiyrt.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbctkfr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emaarrxj.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbxvhnc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2lxeiooms.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2jraqnped.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2szsvrxuk.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2cocjwquj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2lldilxov.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwshfsk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2yfoxnncc.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2khudwebi.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqlchaq.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdlvpcw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qbibemwr.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2eytkixxu.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2astpofsh.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2anvcjvxr.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nkndychp.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqcrwiu.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdfngeq.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2hdeaqwol.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eelzqmwy.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nefmbofk.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2injnyxqa.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vyefhpxj.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gabwltbv.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgyctmv.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqumtjy.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lxandwlw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrlacvf.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mototnoj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dtccsjvd.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkvkzah.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2htctgqeb.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfgefcl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2opmlecsq.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtzexbu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hysziucv.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxzwuwj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgmohkl.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvialzy.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwcqpwn.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2skdujtll.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2lkraeekq.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2reqsqjjg.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpnqato.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2uvghlppz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlfklyj.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzrrfdb.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlubxtr.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2oseawsxh.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2syudfzki.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uusbausf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2fqelknyh.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jfsqujie.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvxhyds.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bhaqlfzu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2twlrlmxl.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2faxmwgzs.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2pyypyapw.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqproda.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ekinhuyb.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2srvbdftw.html


<!-- 参考信息 -->