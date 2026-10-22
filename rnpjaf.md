代发 wailian999

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ziddngcu.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2wllvfkoy.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnexzfs.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vzaytnib.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2otikkxhs.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsjedfq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2egjdoarp.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyzjmoj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfzizhh.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fylvpoti.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyckdicu.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oyuvawxs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqovqqzx.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jpurlgxf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cffnrfut.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtawlry.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wumjzszx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2woixrtks.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2kvywuvnl.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2celiwvol.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2wfkpgewj.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwkbwxi.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnukucg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iujxfgmw.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwamjho.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtnooxx.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ygampzcf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2twazjzph.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2iilpqrck.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iynaiobh.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfliora.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2tipovbre.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2diyjpyvb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmsfvbj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqekhhc.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbezvsi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2aiupvmel.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2njauwcux.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmgpjfa.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ehozcncd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxvgvbj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtzpdsr.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmdpppr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdywknz.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2laakhhnk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbfvthl.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnljctv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvkveli.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfntleb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcvlxui.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcdmygm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfipsqr.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vegggntf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkslpuo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyaczejs.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdginos.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qflqludg.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqzrdlb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzxllpo.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqlbaui.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnzudwv.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2mibnqzyy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdhcfsq.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tudxeyej.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpbtgmj.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2evgmoofs.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2fitwsauc.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbbwsbo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2lutuotrm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbnhkfs.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxkzdzi.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgrfaby.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wklkvgyo.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2iazvlqww.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhuwoqe.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfrpnan.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wazivegk.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2upylowgg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmnwpte.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2njvwmxjp.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxxqnfq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qaglcmrk.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxmknuc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxatfaj.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pypwotel.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkvxlyy.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lbivwfzf.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyscchc.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlafkxv.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvywakf.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2htqenkzu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2owtkvwcj.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2srsvfusm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2muynsann.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2xvujyona.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzvadzm.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxihwom.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2nionmfas.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfbcqpt.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2nizrtadd.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsjcsyl.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2etepivww.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwkawgg.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zmthknxr.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgciezb.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzjquav.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbvnyom.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqnyzyb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgdqequ.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wefumiom.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2euuticaq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2glmeeaue.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lonkvwza.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2czptbyen.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2wpulpbcw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqdkdhe.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nnafjtvq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2amvacrub.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2exjyfqwy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2qpclhqqw.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlwnsdn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksaslops.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2opoafzam.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2noovxptx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbahkdh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjxjwuu.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqaouvc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwjopss.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvwcweq.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqbxmqf.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2umpavnmn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzgcbdv.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfcskdg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2isoxhyxr.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkarelb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfraipiy.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbrnmzl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxyfyll.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2plapxwwn.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2frjdhepb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ewngdigx.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2attoezwu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsofamrd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkjiehv.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmigege.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hvctfdfm.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2tactgauh.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2uggbqbgc.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2rybdlbwv.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdfkoav.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2thaqbgwb.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tzerhpnb.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxuefna.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqypzuo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzlwfhx.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnhsafb.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rstslkfh.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mcddvqpl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2huzjmfpe.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2curssnjy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vqingewy.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjrgxog.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2exqxaqou.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgpivqf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrnnirk.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvnatlv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jeahecsh.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2tusmsvbw.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2xovumkui.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwootvmc.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2annxouap.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnigagmq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2pelocqhf.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wywabilj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjtrrvu.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xnuguqdp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2znqzqopn.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2lqyckpby.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqwxymo.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vaiibyle.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2phuohajc.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kkirkspy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlitbus.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2hlstqvqn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwbpmvt.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gzextguy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2juctlpgq.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vadpmpzu.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjgfthu.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfmyhdi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxofncfj.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqsfjuw.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrtbzsj.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2zjafvnxf.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2grqgljor.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2razxvwbk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tqemjwpt.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jltbkdgl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2meihvkwv.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnioevq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbsuauj.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2owejlkcv.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2yaprryly.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2pttvmvqb.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcmukwu.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2xpyaffxl.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpzxzsw.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hcikasaf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyppbdy.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jngsbdaw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2coxjcvqw.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cietosdg.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbnvsnq.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bshlpwzq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2duanpura.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgwqsst.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2zknidmka.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2irdroixa.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gstumvqv.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2efckzium.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyzzdtz.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ntminasa.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2lnyerwbv.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2skyskxgp.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2anyuwfkp.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqggwno.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwfhtfl.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwjkznw.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmeasbm.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ayuznshs.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlafabd.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsfxtel.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2cdccnuoo.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2opysrknz.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lgatfsco.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bbavrrek.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jsizdceu.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbeeyhc.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lffnqcpq.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2udwpzngs.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwjhbay.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2docbarwe.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqowexp.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqsvuqo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pansusqx.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2khirohdo.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcqujfr.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mjivyvgs.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjhiiuu.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2oskhauan.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2icsljkub.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2yizddymi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtjppjs.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2qxygzilj.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tswnglct.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwdjtae.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gbifixjp.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qjaagrci.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzynrse.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvbgife.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzsrfhk.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqszefq.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2lljewqpx.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrtsfqq.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrzzjzu.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vrywtuab.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfmkhuh.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2shtoevit.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdfakbv.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nabmdgcl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxntsmy.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cgaajwgi.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvycgiz.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkfuagi.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2peocdote.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxiegus.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2abenredf.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqumeig.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2sioebpuk.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rlowvdyp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2zabimffj.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2frmliteb.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2emutlrej.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2rzytqrrk.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmvthtr.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgkvpur.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkxkzbl.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2suxtvhqe.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2jagdkeng.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmnliqo.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2mtuxtiwq.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ktahagky.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2llhwbonx.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2pemvcjxw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jckthfdr.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zcujhrye.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2djqijkgd.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsgfjxh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2awjpicff.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ickgvior.html


<!-- 参考信息 -->