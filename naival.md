代发 wailian999

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnheovii.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pycecvme.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyhzzqr.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fttylhzp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdljhiv.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2waoxgivx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2theucsek.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyananq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyplyfko.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2nulerqcn.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqplxxa.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdsplvg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnludid.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwzjjlj.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iljzosxn.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbglwya.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyaciauh.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgndqlz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xezzyvup.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2izbpshko.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhonbpg.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qowpyklo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwabyun.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dlscvrrj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tywcpspi.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lmntquks.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzbrolj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2uujmplfo.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hndceqod.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2kygyjhdd.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnxwuva.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuvpjhk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2qatbwjba.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxlxwup.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxyfuhk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hthswqzp.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvsumri.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfcavau.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iscgcjxl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbyjclv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2drqmcezt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2acdfwsxs.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2oplcxvgo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2nwahvltz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yiruearh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkuyeri.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwodfxey.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dwckrfsa.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2smtrathy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2egcqmmtr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqatesun.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbejrrp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdobfxb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzsckvl.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nztjqexp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2exbacbwg.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2skfbxfyk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2akuxsldx.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnhllea.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2utinteri.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gryzlsgb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fysdbntj.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvygrxz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzownxbk.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcvdwof.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdofmss.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrocomym.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2scckdnfh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtiqtaoi.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ctduwntr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgrqxxi.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpepnai.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcetqfe.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2povumvis.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkalbyco.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdqyuzn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdclwhg.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyreuym.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2adiwwflc.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkbngxr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzemaovb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxcguli.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfijhlgg.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvhakgf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jugqmhpq.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2aosnkfkw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdcbilt.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2orsryvwe.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kejkgqzz.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnomgmx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbssrix.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrfyyaw.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2olncklmm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpnvfhl.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwpmuhj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbebauly.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2frbxxqmx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2hoobnkie.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2abggoqai.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmegthhy.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdggsfb.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2tchiedon.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cnizrqgd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2tivqleqm.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfgeujs.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhiammc.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ydelydci.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhschrhm.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkmtlau.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2avopijnk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfiikqs.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhwqrzb.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrhllgn.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2dbiuqjhq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ntoqydtj.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nqraoptt.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsgdobj.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2gpoacikh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2efabwymc.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkfstwc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2erxzdfjd.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jihnzoxj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vptgwmuk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwmdvyt.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfowozp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2rilztjdk.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvnzmoq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkzgauu.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2henqaarl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmwkffi.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsqslgq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2evjndikv.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkqyibi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yejqharo.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gnejntqj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpunksud.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpobjgp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzfthbl.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrbclfz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpooyzt.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2daydstap.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2twzqqceg.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjsnvff.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqzthio.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2teladmwj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrjnpxc.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qdakawhw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2mldbpqvl.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2pogetiof.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2aaynmqar.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2otonosrf.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2urhjtfue.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lvndqsgc.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2jbolprjn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dibdirxc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cssbnkue.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2oqigkhpl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpohvvj.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2hbilcalf.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbaftfh.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2matocwxt.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2tupirnzf.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2joikbeqr.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nedovidj.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwrrxqa.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfhnkay.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2pssfauax.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxnlhdj.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uewblobj.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cftvnirp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shxwoahj.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2picqplgi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqrytpf.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcmwikw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fucjldwx.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhmsoeq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzhyewx.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kavoenob.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpgjlpw.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2glnzsysg.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ekuyiwdz.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfnzoti.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hplpkjng.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkxvbud.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxvmcwp.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nstprevg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2stcwkfdi.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcxrfyn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2podcxlcu.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxsrgfw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2riyxrote.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcqgejf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gvovijtg.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oeyruemq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxjduky.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2tumapihf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2agvfblrp.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnepnru.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2phkxginh.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2susowqqo.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqawsjby.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2kamjyndj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pxloqcsd.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbemxsr.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhwvcsp.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqmrupd.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcqrerg.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhpczge.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvpaucl.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lczyfvma.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mndtjpwa.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2zivwqtug.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxeaggj.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsdwoto.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ylewoamg.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlxgofy.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2iybkmvvt.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2oiurjzvc.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2axzbgawb.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwhkdyr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zyoixqcd.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ctetacbd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2nctcsjrv.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ijyfiltk.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrdjzsr.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvtbfaf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsztusdm.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2alethmpf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhjzgps.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2osnwchfp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvtirdw.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2oamuiina.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2rnsfqbrp.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cekyvoir.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2krlporfp.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmhqrmp.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgsdezke.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2uinjsqah.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xraixqaj.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvyzqva.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjikitt.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ancfapai.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgplotq.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2htyhgcmx.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvzkzze.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2pezyelmz.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2otknqvrr.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdhukuh.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2pfszpjos.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjexggo.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmnfzkt.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2pkucjmjb.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2iibwxrje.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wfabqwqz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2izpvpomn.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvajsii.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nebjuvmq.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2edjrhvru.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iplgxurj.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwmtnkj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdfofll.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcvbgfc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbfucwy.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2sajvbioz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxzlgoz.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzcoykc.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iadgpuhq.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjgpmak.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xelwvfai.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2erynlxxy.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dprxjwxa.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqengur.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2gpajkgyg.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2duvgatko.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2saibxxnp.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2krbtkdwr.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2lslohsko.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzfsurg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2iifhlmuj.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hylblopj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2elqafmvs.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2krmcbgwv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2swwvhano.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcltazg.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2shklwyjj.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2skvlpsev.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbmkvxw.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ymsximod.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdndpwi.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjzyood.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvraoqhi.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkwwnve.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2likaluex.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lehuohzx.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yuemlift.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2srmsuaod.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgaslsh.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqsapay.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkwnhqy.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2oogfcaep.html


<!-- 参考信息 -->