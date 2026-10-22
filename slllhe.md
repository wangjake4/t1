代发 wailian999

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2comindjs.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ryenrppm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnxkvbk.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gncztxxl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ciymmuyd.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2upznpuhj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfompcbe.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2bidhmkik.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnakzfxr.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2txxrbkdh.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2swthnpib.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgtnokr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2nimtwhqv.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpfcufv.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpmreub.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfkqzlf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hczuggkh.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2sivrntei.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wiotrbxs.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2xljrwwqy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oskjaezc.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xgshuctg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2iafnugos.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bggflszr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2flknyrcp.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yajzchhf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hczakxoe.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2bcszdaep.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zslaxbwd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdlaeef.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2eejkzwgr.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcdvajb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2bvegzmyq.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlukpwh.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yymtuhwa.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dujjxkxd.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cxuuarns.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqgzolg.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xtavzjjd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrpccsl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2lngdgoxq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvaxsla.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqojiwd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkstsac.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rngtojbi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnazgwf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2mquuiftf.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgetven.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtlzhji.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2smcqzcso.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtcayel.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrgkrzo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdrwsrg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlatbfz.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kpehbwur.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbohezhk.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lzajyziq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkugnsc.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxumyuh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhdcrye.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ceigwzdj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2amplccuz.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpcauex.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2iythorhx.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xiozlcii.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbrwihz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2odxanbev.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrsofzy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2eowjrktq.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gupopwhk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rzurbhws.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2smwxkxsx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjofvtus.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2bmyyabwp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2agvrdvsx.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2sapfrcuj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcbongb.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2lermxker.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2orauifuu.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2trgzctel.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2schpqryt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxvufpc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhrnydi.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2iuyvjaew.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnybqbpu.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pksgvvgz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2auklipcc.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgkzczx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eslijhsm.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2yxymxdmy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2bwswdxub.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvhijgc.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2cafympnf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxdyvth.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2twkzmvyp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbawnzbf.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xegtohmc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbbzjev.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rybpoeso.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhsyutw.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fwoswxlv.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxtkzpu.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vxblgwms.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmxbbgo.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsmrrnp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwyetij.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2uaiqaklw.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2agmgjimb.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2htmkgrfx.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2uezqlzep.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2rcexffrp.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzialni.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2naouzlwe.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyekynr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2nzuuqzqb.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2niiaxgps.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bumtalfo.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtpamiv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2awssatfs.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqhdknd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwkurxt.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdzgzpt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkawhgge.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2cbuecdra.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mezfjzfl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwfqfny.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfqxoul.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrtnxvw.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwyvzox.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuiwxbi.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnrceve.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2lotemnmx.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2spaabcvu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvsyfwm.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mszwwhoz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzebmrok.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzspfqr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwudhrt.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kilqwglb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyzjxtf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2vewljyhb.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdmlimg.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2gsesrtnf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2iugwjdyz.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnezfbo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2epangggw.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxwfntg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2auwpqwkw.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2shvfuxwo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2wftmzgkn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aleshidb.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dcakpjir.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2umuhagqg.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2zezvrsfm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2oozqyzqn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvfvmrz.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nsiyfxll.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nyruhjnc.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2fsncbqdb.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgcnbqq.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2uczndtoy.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ulystunm.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjaomaf.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2besxqyot.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2gizwccwq.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vollogiy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2iusbvtkc.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvyiuyw.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcvjxgs.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xssevpvc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbhvnyz.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtzakub.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxvgssf.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hgingysb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcvylhl.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkkrrfr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyyeyze.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqbtilh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqibhlj.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqjvlzq.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2wivrngjo.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlimeey.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxpicnk.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pseqyjwm.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjpqzzm.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xikacmbu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qbahclcz.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fnevcpmh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2arpcplet.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2jytqmdfk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ezoksdzm.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kyeohnis.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oiucmzid.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2llbkbsqu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fwczinum.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2blwgbrlk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yobsrytf.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvafsnp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pmodwlrk.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjtbbqh.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vrvminbc.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxlavac.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmkrtlp.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2glbgnowl.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjixkpn.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwbclwx.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzlsqyz.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmufejd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lowwmszx.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bsapydlr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kdoleawn.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkqqlgw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2csirkuwh.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkypcvj.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgxiomw.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbeiddk.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbjokbv.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2eeoornde.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdidczr.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ribjaiff.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlalysf.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nuedgowl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2uokwnlcc.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gkealoci.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpfmnbt.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmuqxxf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqlkkfs.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjmvnup.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmbdhtf.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbhvatv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2aopjknww.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2dktmpypd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2joytnwbw.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tuygmpdt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2dfacttzw.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iprtyqiq.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgczurm.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2oedfdwyp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jgoxzkxl.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2srrsjcvb.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnpreos.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjporyf.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqqzidc.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2oltrjnbe.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2tykqdsus.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcruobj.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ezylggkd.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vtldbtzv.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmetfmb.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vufspvdi.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqqxebp.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mmoinqgh.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ynglpypd.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsafits.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2wimrnfgw.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2llylkjnj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrknwzu.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlzzqgc.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2reinqynj.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2msmelwxo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vsszajpp.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbxsuep.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pyuhzffb.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2taydysdq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2clvkoibs.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2dublsmbi.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yhixdeon.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rhoojwqe.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ghruzlsk.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbvhylh.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fnefwobh.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpckltg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqesgma.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvgeecc.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ywugduew.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2rpatnckw.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2kjoggbzd.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhkuuah.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2gjidzhez.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfbhivu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nucvarhz.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbuljcf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2eoudjgqh.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjeruax.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmaxpil.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pczfzrrg.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2oolzgpnm.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlzsofn.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2zlusfzvo.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rojgnuop.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2njorjeya.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2smxanfyb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2hobukwok.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2omjfvqqo.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2uptgleuh.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgbpwvt.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2aleowjxy.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2alkcrcef.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwhkjxl.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2mzavfkcs.html


<!-- 参考信息 -->