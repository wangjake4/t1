代发 wailian999

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yynbxeat.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqrbnzo.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjlfopz.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwwersz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbermcen.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2eopemsdt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2nidxpfgf.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hflulsdp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpojqary.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxqhjuf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yneirhvp.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrpfumm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2etimfyvj.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxmwzgj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdnxyvh.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2diglzbpq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2fadguhim.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jehfsmqh.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlmqhrk.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2izojihay.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpqjmwo.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2smaagrmk.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpbzgbb.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ksupjale.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqoymfz.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bktaueug.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzffzkvm.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2gvubyoct.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzifczx.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pyipiyvo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwzpegr.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rurdkhbj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gusztfqh.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyuzthk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxnvdge.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbknabt.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zusuhula.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxfvqbc.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2hchbldap.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2suhemumb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsziseq.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzyqpgy.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwhhxfn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pafaerue.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjktodc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2trxoxtdz.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nduksxny.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcyiesb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcqwzll.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxafpyp.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmlmhpr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ifprvvsm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2prppwpvu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2vpecknyv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2yydazvxe.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkixjqr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdrmsiz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhswove.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xatfcdhc.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2geobyigp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpbbxbu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjeluve.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jydtucoo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2czeaxddn.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2neljkdjn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnvxfuc.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2odtlofuq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvzjree.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjyjyxm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxjflrx.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2drocvspa.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvdiwjb.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgsjlsx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2iypyieme.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrjhpwh.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2encoqrgc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpybeylb.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwwkjnu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2euvzvbnc.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2evchzbdc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvcxtyp.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxiyzpe.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rofxomtu.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xqeewpkv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxykxyx.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2dozevrcp.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2yuyonjkc.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrakora.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2auvavlqb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvwggqo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocesjthf.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nstskamq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2emhjbszv.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nunyyzdw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kabyshkc.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2alfhdniu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmdfgab.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zygqgsiv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkfjjel.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2idantkqs.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrfqgvn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2knrdrawu.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkhicwf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2znjxhqaq.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mayfucdg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwrzxbn.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzbvuts.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfedruw.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vpajixjb.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjegdrpc.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aodxprme.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2cahgbhsm.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwqzght.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2xujfgoyl.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsmrcvz.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uuraxosd.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2whefaveh.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkntrsz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgizxjv.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2vklcjhmg.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2chqfmsui.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2cjocezkv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2mykxzkcc.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpyeqsu.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqokibyb.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2jzybmclq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhlioog.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgoxfjw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2chldkhdk.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjwtbjm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygudofno.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2aesgfzmu.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2azpxwrkk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnkouzb.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2zypdfanm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2aomaglao.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2djarlskv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkjuwwa.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wwylunhr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxhcvsm.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ooagjnus.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjomovy.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbcqptg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2brrivnlv.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2junvtiiq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2czrjwrzj.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bekkgbzo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyseyebj.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2pipnqpko.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzmxbgj.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2fuytdkmh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2izeilnry.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ipaptrem.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjadaar.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2clejyegp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpbcppy.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzhewlv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2qtykihze.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wraqbryc.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfwelrv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2efhgdbxt.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrfbbax.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyiovmcg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwhzwla.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2eximmkso.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yfoafqsz.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvkdksu.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxoyfvz.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ezutyyoj.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhbkhjw.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2viqvachp.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlbmmey.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2blucncos.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2chcqdksb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2gscnifwr.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mubxbboy.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cpimrqvs.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tirrwekl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oofldyxz.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcbsotv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfbovod.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nonehbha.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ccoqiwsl.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zinyppnr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fjeebnpl.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2serdifak.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2klwetcqb.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2wweumidj.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtawszf.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtjxrkj.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2oijkiyow.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jupikcbl.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrgortm.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cywlzbms.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkjjjsl.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fkuzyysj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oeaslyxt.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdfjafp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2emqotjvh.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbwjzdz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2efpvusck.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfyeqse.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkhjllp.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2vodtqiwx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fprnqikw.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2loqybzyx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrdbrty.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmcmfth.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrqadac.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2iuicvdlt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2krquyilk.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uklltfdu.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ffndcvgo.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2wihlbaka.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yryjmswh.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwuqqqr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzmsklu.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgblecu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yitrbpyb.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2koscpkpz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2svupxnda.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fhstywkb.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhualrf.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqnzqvp.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2eleyhkbs.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzsrzjw.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxqwqud.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnztbiz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2moagvdbl.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsnhcfh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjhanzs.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2snrznxrx.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2reefuoxp.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lghawfqx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrqkrwk.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkupdrh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2jhipttsz.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmjfzyw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzhphqm.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2emejohce.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2muxtphke.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyluonr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdahavu.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2syqfifwd.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnojatkq.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qyknjgkn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2oeootymg.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2popuycwv.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2eueymnft.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2llzpqpks.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2postbrcd.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nmyvybyo.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vqctailh.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkgwidt.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qczjwfvq.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wudajebc.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dpuqxrca.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjotjeh.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrfonpl.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2uxuqnnss.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2fzazugro.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vydxyssq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfphumw.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2agbbceou.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rmroczol.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpfgfju.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgbshwj.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2punxlzgw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2mkufqpyg.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2thyphhuh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vicngcoz.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2kidycjmy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2kafxrmre.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2emraqnwe.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmlbihv.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzqswda.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2banquepd.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlslhrk.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2djyllblu.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2oflhnpzx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhnekmm.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ioptzvby.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmnumxe.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hctozlny.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2rafyiszk.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkmxawf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvmgldz.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2eoelfpae.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lmroxswe.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wretfsxn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nomfqyxr.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbkenzd.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2haybvvng.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2peobxuny.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzimtgr.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnqsmap.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrffvzr.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrgohtx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2iychfjyu.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ouiekrcf.html


<!-- 参考信息 -->