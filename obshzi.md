代发 wailian999

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vocfanyb.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsbfdcl.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuggmyyd.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2afxakzfr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2udkwmlhq.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fccqgduj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxrwzkg.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2imsnmsuw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvaabbgb.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbzwpwl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2clhuxumj.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gpobnnzj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2heiswjuc.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cthtkifg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjstvdve.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2usvhnkwv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjxnhaa.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtgfchc.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrppcimc.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgohabn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxtxgkk.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2cquezlhc.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2irhcagig.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2citdshts.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmpocba.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gsibejon.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gytvypey.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrotpny.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpuqmku.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkuwttb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhchhdw.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tnotqyrv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2llhyxdim.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pslplsvk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lawjtlbe.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqdzata.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2douepvuk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2xntkenim.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2rebsbjfv.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2qidytrxj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2rbikmdfr.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aoprgtqf.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vdskqsdy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbhnglg.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdvaduy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmicuks.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2plnsjuyf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pupaghbd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpuqbmy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2asnpuezy.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtgqjav.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2rczczuen.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgycobrh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2enyqbofz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwlacuh.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjhmubs.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2qczmuuyq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvhrpdq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhirhpjb.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nghybgmg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2qjziibnz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvghuxa.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jedbpuhy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqunastd.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bjehlcri.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2jaaqaoep.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxckavl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2agmpdfks.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2oubbwwad.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtaizsg.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zetgqgpa.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2goxxmzgm.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfzxrsu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxcfuzx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlqxbbx.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxljlwf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dolmndjv.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mcashlmk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2waqetdwo.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlvyrgu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwipzma.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2bstdstjh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2krysyhfc.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tfptcyrp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ujreinsj.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2zprhplok.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnugxpny.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2tahaqubm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdgnxha.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2rizkrvwx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmnvwlq.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wuurjmqu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2besomlxu.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrrqdcc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcusjrsc.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2rslalogb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2enfcjohy.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dduguepn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2jnujclpf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2famaflsx.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzxzivx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yswutyqt.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxtneng.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqpybru.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfadqoi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2rjetohdc.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvuoolb.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxwwnha.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2eevnzoid.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrsmvqw.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oglskwqd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbggwmb.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2spzsupuy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyhfqbk.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsuwuoa.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzyldwwf.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjrpzan.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2nueigxqc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2oiasjjlb.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2bzluzncj.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukapamec.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdmemao.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxzbovd.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwexhjh.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxbpecz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2eesvdbai.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rdeachom.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rniwjubd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2efztmelr.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2guftcrdq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifigexcv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2vplosmrc.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqxeusy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccacmodw.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdxkfsl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2joxomqxe.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qjggmxri.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsyxcpp.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nacyjdlt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2nopagada.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2jazkmrlh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pndunner.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxwdllx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjuftdxk.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pscigsbp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufajtysq.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrxccap.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnrqryy.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2qelaatto.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzsxmru.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ayztqjvh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmmeqfr.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxbekbn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2jgntzmgd.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dsottorj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnknnqv.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xapvvhqu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhcvixv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqzhmvw.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgwdfib.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jyodhnbr.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2kmusuazt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhpmhvr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jgazpkvx.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdmikyo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxvbjpp.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjzneyv.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2rnletofm.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzwkgpi.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzpojjp.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nniognxr.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lulaapiv.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdolrlk.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsujvqk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2zojtcbqu.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ykugcylb.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2txnalmkz.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhwirvr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwoneexm.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qppfvpgw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dutefobh.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2icixfvzt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vukgyjxm.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hyufupgt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjownep.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkypzgl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2olajeqrj.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqmwqph.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjmmajm.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcycifnm.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxmjbfr.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kikuwdmp.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2agheiwfn.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvwqrft.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cuiejkmm.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzevkvx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqtgsrd.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpkuabm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2elcitgsu.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sakjwope.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2loaxeonk.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iazyledq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2igopkshz.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2kazxqljx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2crxdnsoo.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tmamzhmn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxxrfkj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kmyxhyej.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjxlqkg.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2wauwqguw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cunrggsp.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cnouifbm.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2awtqgrkx.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnuwjyf.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbybqyha.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tcuynlhs.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvxkcyg.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2plahyqiq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwyvgqk.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgihwqw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpyxwdn.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmjegon.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcllszj.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ythncxap.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2uwleqtvz.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2kyulxpak.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2aqltaqgp.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rrozgrlr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tmocwrwt.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ujighpfx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbbgqmp.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwkcxjl.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qusmzjcg.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqkicmu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kurmlqsk.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kzknffiv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmvmkrc.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyomcin.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2uimflnmb.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2phejkqmp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2fopesgcz.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2thbrgysv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbatekb.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uemgsvez.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpceolue.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qnffpvnl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zirjmqbn.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2waorysre.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2eansobdm.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdfurvq.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjdecek.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zwiivwkb.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2utftuhfx.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2utprlajk.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xezuodnd.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjrdwvt.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcgevaj.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ciussuhc.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ldysiqeh.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hmadnnes.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2widpkdmg.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hjluewau.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmdkcmp.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlputyo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxjnohm.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfweeva.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2diyxoqqs.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cwefcqca.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xashcwjn.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bjuvoklf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rudmtuok.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2kkiqvzzn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2unmtaiko.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2klmlirru.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ckuuoenl.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nryzhgvz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2llhtgfgm.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2deyntnsx.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqdxxce.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2xidnxwoa.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2lszaehzy.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2irdhkgrc.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2tausjdmx.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vadgpbvy.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2fuexedel.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mebmlrig.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2iltbptgj.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2taesmpjm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ducjpzlb.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpukkdo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2flyzilhc.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpcamve.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ufluvqos.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ojditsxp.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2npvxdyzf.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2apydufna.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnlzhhg.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlstcrq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdzpimf.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2oidhloef.html


<!-- 参考信息 -->