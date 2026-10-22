代发 wailian999

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrljxbtk.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lmccdhpg.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2obnvrbtb.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bambpxlb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aczdzufo.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pgepvskr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgcqecf.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwtdpzi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmphaozp.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkxckul.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwesixwv.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rhssuqha.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntojzyew.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2eiialoym.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvswnvu.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqoyfyw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2drejfqdh.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2anqzhffd.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2olheebxa.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrkmbhr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2bjeylaxg.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rejatcjh.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwsejfz.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2eirlomcs.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yegixutl.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2tjukjioj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkyqtbuy.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgnuucx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfjifrh.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rumyrwkl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhccxmta.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfkgvwl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtvfvkg.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2imijuqki.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvffszmk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdaylxf.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxeiapw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtztmob.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2hhflxdcp.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbiqgfx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2znmpwusb.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2keegrkam.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2amxjnsaw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpwspcm.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jydtzygt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bojpwpvd.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2btiytqkp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zymjpswk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlcottw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iegkdrit.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vvenhqmn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhodwod.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgrwbvg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmulees.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2atmcgebo.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2evzlicsh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2lalunmce.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxoyddo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bizmgoum.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ukidgstr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyuvhna.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2cudkkqqb.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdfopgv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfczxtgy.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jigiyjjn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2owxpkaez.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2schwubjv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxstbkjz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpiaijv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2erikhorz.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2djofnpuz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctuajloo.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gbonbnsh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrsybase.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjtakiy.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mccssbss.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2siwqfnej.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwoowtf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxyesev.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hntjyaya.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hphwxipt.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrldcaz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yiahafen.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2otblnfdv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ganchggk.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsmloot.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrlpdbk.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfmgpmg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hplzctuz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2smvjsvph.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2bekgtuxl.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2igxrfumt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdjugfs.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhciqbs.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdxfqiz.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdexusr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdhaukz.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2akrbarmb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2qthemhwt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwwqjhx.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxahbwu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdziclo.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2itxxvyna.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehesivxr.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2etolleyl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2udefnbeu.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gvaaappw.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnsfied.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ffftcfbf.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2brlawoou.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnximmx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2suittwvb.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2sqngqgwu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpnzhgf.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbyrlwg.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmubncu.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkzddsb.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2cnndscwf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjcshrq.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwisfyb.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsgbpvy.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2avqqlkof.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2grmgrdzm.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2idhajykf.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzdxdmz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2rfyyktqw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkxnohf.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kscyzscg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrlljlu.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfjxtlc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2irjpaieb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2kaapsuhj.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjrycms.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsbffmy.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2efptbywh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2gndgftgd.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2updmnfta.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwalbbf.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsmtush.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ithbiitu.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2whyuytov.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bidaphex.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nezvjtyr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtlehfi.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zjyqpocq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aelsrjwa.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tziirroh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gispwvfa.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzaovzx.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhdsqhw.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpsfdse.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zybmrjbq.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rcobkkuh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2cozugctw.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrwahwx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2jailicce.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ditjaocq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqtvzwj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyjxqqg.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfzkfoc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2dctycauf.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmnmqvd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ienvzwiz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yaoejuxl.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzqxghe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ylafhaks.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2wnggizbh.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhsrwyn.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyjsfef.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzjubsc.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ludcexny.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2exrgycza.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ojeinxfz.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2soqqczhb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2cgacfust.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmhuggw.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbsvliy.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vsazmvkt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2caolkcjp.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjjjwet.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2huhqqssa.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdpvhzs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sihhhpwh.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrxjzhj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnwjlud.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqzgfvq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqkrdix.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jadpzafe.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2evwsdvog.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2usflyenq.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwsmyut.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yusyeudg.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2hubyyikd.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqjxjve.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhqcpia.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2esfiqerq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hygzfmbq.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2puwateht.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtzbktb.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuonlou.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ioihakuy.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2txjvszzk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vufqdmiz.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgootvg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2maqlicso.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxvmwyy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tocivavp.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqgtgip.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwxolry.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqkizbj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2phufvcua.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzfixhk.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gobbmwzc.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhrvtth.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqdzzhp.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdcrlmx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdoddij.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bwegjech.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmujwjx.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpbzijz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hezsetmx.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oszqxcta.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdvfrnk.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfmgzbn.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2mludsrdh.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvjepxg.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2stwpuhgv.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cgumdurk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ifokahds.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvrohsd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrhiesy.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cdilvvwc.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtllfrk.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2utzxldsv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awsntxva.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmeleuu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2agbcinim.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjevglx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lluuljyh.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjstdyb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfdwoij.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hqywephu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgtrvwy.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhjgbbb.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tewelvlu.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbrmdhh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqmqzqe.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyjoach.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqiylov.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gvikogrm.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpocika.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnvwxha.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwazskr.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2xidtbeko.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mxaiugui.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2edbtongy.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vrikkbyi.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hegwudwr.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmsrphd.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ukahdswz.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2dlitzufv.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpzghnw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2xsaafhhq.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mlexvnzd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fepfiwwq.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2foethlkt.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkyutiz.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrrufvf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2khluyufm.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2txqosbrk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrzubvo.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmemxka.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfjzija.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvscosg.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2llhdyuiv.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtqzlfs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2asxkzoqn.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xixogtvw.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmdxhxi.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2eccfhopq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2lphmolsx.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2llypbjwq.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2qooskmss.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2jeygpork.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2hxoprbyw.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kuyvnfvb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2jnautzla.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wopjwfjx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2pivgvkcx.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pstltqdx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2aubfceaa.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyhzyjv.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2reshpdwk.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbbztrl.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2puhawkub.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ectilgkg.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2gchhuizi.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxjwinq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyfoqul.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2druzlbks.html


<!-- 参考信息 -->