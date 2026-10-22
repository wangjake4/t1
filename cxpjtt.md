代发 wailian999

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrjhkjr.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhrzezg.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oeheiqyg.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nkubcmsp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmaalnf.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vvuesque.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2zktxtxcb.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2okalxvvc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvcnrkm.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kklbqlrm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2plxcbwom.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkrceve.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvuhgxy.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fhemuyff.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgytpxkz.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2algvcwhp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzvfjic.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjrpgom.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2maxxoulo.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnxvgci.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2gszfhbmi.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2cpruaqjv.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjznpcm.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fsumsbhv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eusbzffz.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mamauucb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyksblgt.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcxpais.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcljqcy.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2osurxazh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2sithwsup.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfzvsnn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmevvhah.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2phweexfg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmeufpyc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2zlltvzxr.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvcqdyk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2afqtpgyl.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2xybaurax.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2oaidksno.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2eadvurhu.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmswdbur.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2eycljubk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpgcqji.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsncxus.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2obgmmwkv.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tiywlhjc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivedcfqk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2adzajhsx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gubdxbub.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdaofrx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjsnjqp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvuktgpl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2pohjqlna.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2fscytqzf.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2maorrphq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpuugms.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2fxteepyn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pneakgqn.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgepufb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2cstgurbo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2beettdea.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xauhsiln.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2nakcwrgy.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gxereeby.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2cefksfok.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2paqjvtov.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpodnxeh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgqxgag.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfcvmkpo.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rricybms.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvktpkip.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcuzzxu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2llhiwhtd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2udnwpmem.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2orrfccjl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwsybaji.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kjagagfk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbzipij.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gzospjui.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uiehygbd.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2aeozujws.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsyiemv.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hfuwkgcd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2shbkmlvq.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2inpkamnt.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjuomilc.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2yebzneqo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykusiobi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2anxkwxiz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmmfcmm.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkfiwrv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzitwcog.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkatwyg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjakjuk.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2hygvxpqa.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2psiooxja.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2gzeibgzb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsnnfps.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrobqyls.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mvknoclu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgszacxt.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsynmde.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjrocuf.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2akwlqtbk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2tossvmrx.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjuhspm.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwthwcyv.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhdhvda.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2qiockjtt.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwmheww.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgrxval.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2htdkifob.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdkgkcv.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2xtticidt.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2podsmqhz.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hniwgyms.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzmfnhl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2adkpvblf.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xerdkomo.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2revgcwdh.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsebeus.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgnbicw.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mjiwcojg.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmzjoty.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2rpyktaps.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lyheprju.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhpvtug.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnubnmz.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxurydy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlqjesa.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2fkggnosu.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mykfvvzc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtnbmqn.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2igxoztfl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzpquet.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuycplm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2sxsofmje.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2uyllvjpz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2nbavoflk.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2bmadqliu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpiabgsa.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xekxvnux.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdauvhgi.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uuomnuet.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgmpivm.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qkozujog.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdccfjqg.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2njhcdfez.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdalctu.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgbgeik.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2aygwzala.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mucfbpvr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2cuacmghb.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvhuzmk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdyvieg.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mnuizelf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2fuojtxit.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkcehzk.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ckonvmcb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2maurfrey.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2cyivfrhw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xonvjxbv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jazpjnhq.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2algaimkn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkwqndy.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2coodpsva.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqktsgh.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhrmcwr.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmumfgk.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mebjtvxg.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sfohwexd.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2etoetlut.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bottitct.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvapfus.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2cavwsvvn.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2znfkknvh.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxgvccu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqelrmbj.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2unszgnli.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvnnwlg.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oiayrfqb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hqktmkst.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qalxtoln.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cellpqoc.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhmwsai.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwbxqfp.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2pqiyniju.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2pymbtoud.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyckvylk.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxwzwxk.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgaodjb.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2quiopmkn.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lgoeolzs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2teoebyps.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvcbduj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jayszaan.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2hejcuwpg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvuyjie.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmopblh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2erwzxbzw.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbzemlw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhwhcug.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ftytpadq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwcmunm.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2aaggvpmz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qocknfcv.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2admzqhsu.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fskafwgj.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2askdydmp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lfapnmej.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtjuquc.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfunxqew.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxkxsrz.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zshtgjtp.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdzsonl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2frlpltpr.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2izxcfutv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrklmcp.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2sorwkvcc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzfnksa.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iazimaxz.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2mppyducw.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2gyeoixtu.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsvnbfl.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2kfydlojb.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwsuzhg.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsknsie.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2epfwsemw.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmikrhh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2yucvifiu.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bnaydked.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqhzlqb.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnjqvsn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvsjtrd.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2sdobuxfs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvsaabd.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmnjvuv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dbymqnre.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ziaixmsd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ukilglyv.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ifttojmc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2qykmhslw.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2acugxxrn.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfkcrqq.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ukizvjiw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbhnpao.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcsjldm.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2dydjvjih.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxwjghc.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrfqaxc.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dznulofm.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hodglbqn.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2kwypsajf.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2edqfsktw.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkxnqly.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxayqcg.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzfeydf.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mjatyopz.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fsagkudb.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2yeduieok.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlmvkzl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2oomxdysl.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2grnplkkk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tbyqkmbl.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcfhljo.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2okoksicx.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jcymgvuq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tumszkro.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjllvln.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dzogwagr.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2hxompnul.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2spxjehnc.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ajeaprbu.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lsduwuai.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcpznfo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2irvpiyho.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxkeffq.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrbzisj.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2qvidbons.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhnvomh.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2piafedqu.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ziodipog.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2oyliqeco.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbhdyfn.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsljlde.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfbnick.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2yccltkju.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2avusvtop.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2unrbsowi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xlguehkg.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmvzrds.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2qihkfgiu.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzqcowd.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2sixlrxiw.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxwxoar.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2lwavumyk.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2phchwlmb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2pubqgwck.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2koynrocv.html


<!-- 参考信息 -->