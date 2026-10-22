代发 wailian999

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2pefadcch.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2vyagmdqk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixroarqc.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpsgaxf.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvwuqld.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lvoyjemo.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpgqsyx.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fganlunk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzvgmgr.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vlugdhqz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2triaxswp.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kpliuwck.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2laxgyupx.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkriugi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2trsbcbjn.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hclhpoia.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dchxocqo.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmsvezn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzihbxz.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2oebeuqun.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2krnoilpv.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvmdhdj.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrvtoza.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpqclvu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhoudho.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2sokjqaur.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqkizpe.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ccndugen.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbktsuh.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qyladdgb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjfcxdm.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzgwcmm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqvusld.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2booasluq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvuyfzk.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pjafwxbz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xogdwdlc.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfphuhl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwjzihs.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlftxsx.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfuchwu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmpuwkt.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkdmtad.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpsahtd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqodhoz.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuwqric.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvntnmr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxqwzix.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zroinmbj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2reikpwdj.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2aweekdmv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2doekskpw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgdnqqe.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hffbaeve.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmrpjvx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2yotbvkwh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtevpocv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2zghrivuo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2wixwjgdq.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pldzezkt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2fibqafbg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2msmycoxs.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvrmfft.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gcndvnbg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2fuajpkry.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxyldag.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uccuxzgd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmylazgm.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpknreo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2gilflbgh.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxqduvy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmznqzsz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vihrwnqu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2smyzgyub.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fyakapdv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2tktgmevf.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzhljrm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2acjgtnjx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzapsix.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjstvjm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbyyphb.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2abihbaao.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ovahyczz.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvpvhjz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2atejkokd.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2fudbksxl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2stuyakab.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vebdudmt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xljwkjmd.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2dahaqdyn.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgfqbno.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqgrtsa.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvslrru.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmaawlo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2edehombv.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2yvduvjml.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sozjpshb.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxypcrh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ardauwvl.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ueowkzin.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cspcrzhe.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xigktalt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2fikmfunb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdeayer.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zjikqixr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbrkrew.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwsiufw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsagcnkq.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjxmoqe.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2hviaapev.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nuikxlxb.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtiqqhm.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zctfpbyg.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqwecvo.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbwrgjp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2oroxbdgd.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxgrqmv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2reqkwhqg.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2niflxuwa.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhsnpdl.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqgjhbf.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqhttwr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ygurbyxd.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvaycjb.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2afiitjyq.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2eisvviwv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2eejpojaw.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wmndmeea.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hydgbyzq.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzflolc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qytoldaa.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2npylaqnf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlzyrpp.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnslpte.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qckxvagg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2weywyxln.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qybzrqxt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyftykfa.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2jvoutxlk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbmaahb.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cuocrbwv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2gmuwbwvk.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ufoefcdw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdvpaol.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ogixothh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezsniojp.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bexfukfz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjovgro.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcackec.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvdmmex.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pgirqely.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2awvepmqd.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrgtnqp.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbwokxr.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkzuvsq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2abljvwes.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2evjmxejk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2aehsphue.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmxgpvh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2utsgpdie.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmkzsvj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2yijedpsf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxapiruu.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mfslhrbu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnjwcuf.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2xadzllxl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2eelzmvlr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2airbxajw.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tdchkffx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdbevfr.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvvpwns.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2iedgdyzw.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2kyokujij.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2exivhgve.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2cpheehva.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vioqnife.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvpqaax.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtbgccc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2uomwhngw.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2iegrunke.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhhbamp.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyfylpr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hanqoppw.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nltcojqb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2blrcwpjs.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzqvlgl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2leoecqgu.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wvitgoqp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlugokf.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2aoeczwxy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ioyhvkwi.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjpfmkf.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2lnomdzsz.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzehanjm.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpkzamo.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2eacrqnis.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2grzkyrbv.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ccctkzsm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xmanragx.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyvgnjt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mugskcpe.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2gsorfnve.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdujhgk.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgwybro.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2edpzugji.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zltxgtkg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwmaeld.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2unfkjesf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcbbjyy.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpoloul.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wibydxqw.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjghkka.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2doehfahq.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2wiitilba.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzutnvw.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pkylidsy.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bckptxbq.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvqqwbx.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqeewwg.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bmljlvkr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cixaxxwv.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzjdewz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnzmdrd.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2stvazycn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2igestpfh.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfrdqjf.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ycukayfc.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2jyaxnbjs.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2grlgyuwn.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjydnzx.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkdzman.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2usriqhzr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2orbfuzxi.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhdecae.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2dftregnd.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzeedvr.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sziczmmj.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ssligwgx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxyklogk.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ejuwjprn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ryaggvyy.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgocqrb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2anyqvioe.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2dfovrhvc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2tstufgqj.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2capvbucp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2tymfjvbo.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qmakitos.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2csezfiiz.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2diiltljo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqvhdye.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ahubeehy.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2guafpuzn.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqgedqc.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jgaziagd.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpvoowh.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2iheuirst.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2tgoqsmyq.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwpigrw.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcvazsz.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tivxwfaz.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgziftc.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwmnekq.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2aynicrqs.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzphzkd.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2nytknosa.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2mrphdndy.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ljlbzkzl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nolbzody.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkhhrno.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwjvdpl.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kjoqthkz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvydaoe.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vsetntxp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hctwrsww.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2yjloocjo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmyafbo.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2nasodddg.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2brtxqijw.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2odcijhoe.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxsrutq.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmkwgdi.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xkplqdzc.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxnbegr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ladguwka.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtuezjh.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2napcxjkj.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgcfmpg.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2nvaxipqn.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ermfedgh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2peabzypk.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzituli.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zouudhrx.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jswsftht.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nylnkhag.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gzherese.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2idjmggay.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjbfeas.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzjvotf.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2aratfclc.html


<!-- 参考信息 -->