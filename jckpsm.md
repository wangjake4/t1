代发 wailian999

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndsoeygy.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwlvyvb.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hssozsxc.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfiqooj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2fwssnmin.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrskoob.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjrxvyd.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcauqbm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2obgennnv.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlpbndp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2raszrlck.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmpecrc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkhnrkj.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnrnpgk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bktqgtip.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nnivxobt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzhhzsn.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2srlunafy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzajjqjd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2seiszibg.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zjizurca.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyovddyr.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2tiaqxmzg.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2bvebmnnn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnxtvcn.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnptvzf.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbrrtue.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnlrkhz.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vihoqhzq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdoywgyz.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2isoiqgrc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jccsmlcm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpqnysd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsqpynr.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjqhtvc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmapbfv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhixqnag.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgzsyox.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzrauuo.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2aovtpolo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2zekndgmb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2oeitgynp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvftqjzg.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxtdcqc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ekagxddh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfyupro.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cookglfe.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqbtpfl.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gawnpgup.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsextxan.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wplpjweq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbphqhp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ulafwdkm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwzslou.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxipecc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2haiellng.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2iijyoith.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpuffvca.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeicxzyw.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvkamky.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2drghphrq.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yutlqqwj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nmorrbih.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yprblxzb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mewykqjk.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtxevwn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrrtvjm.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmrrpcu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpnfnng.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqowybr.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrvqvll.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfcglef.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2umwggeet.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2yddmbzms.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxlbnfs.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwagtlc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfestkqb.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrcioct.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyezazbc.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2mntajqis.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxovyidd.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hjytpwsu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzmpweu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrihbbz.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2tretguyw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcxzssr.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2dctkskko.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yztbmadp.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2awpdifii.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrdkrwh.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhgtixm.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2wghyvyja.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sttkycot.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgynytre.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fcadlvne.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2vttdpyvj.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2mwicbuje.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqrebyl.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdqywub.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgmzuvf.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvabkjlp.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2givhroqi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpaoniz.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2utgdodqb.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oylroyht.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2yjphotjd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2uewzsorm.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkgvpvv.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxgueem.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2uvppksyf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yvecypzv.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gafgwirc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2lggxreph.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwucfxd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzsgtkl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxfexqg.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lcljgztc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2klwlcpgz.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjebdoh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsxvpty.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yuebxnjz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwswuje.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbtqdsq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2kehfirde.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2vutmhowg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcabtitq.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2seobkwbg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjrxbrv.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ohygvpfa.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnumtgd.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvbtfzv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yeowdqaw.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmeqfux.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fabwyvyz.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2axyhbinc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2izxnpygw.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfvsxxh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxfwaqw.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2szxohkku.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjaimybn.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2bobsufgx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ilcfppeq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxkrmor.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2npfujbjf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bqobjkps.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhrmgyz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjrrxsb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pekygluu.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcqdwax.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rotzkbub.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ktycfhto.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsyuzco.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmnwhsx.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcclcti.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqsdpht.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkyufda.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2dyztdjhp.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2whhibxxv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2xcremhxb.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2gvptdlnk.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rmuwvpxy.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gzszmvmd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvtkktq.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmqonhy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qucpiqwr.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gahlmqrf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rtylrtxu.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2apptnaym.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dafamwik.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2phaxctou.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hexnivzn.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xpznewyl.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2dsuvpavs.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwgqgqa.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yoswzgde.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmcuadjo.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxqbnvq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hepkbpza.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zziyhdcb.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wgehiamv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnhxeum.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2xlocdawr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dswycxif.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qkklcnta.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mzttzedg.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2olfphtmx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2buewxibx.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfrknsr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rowvrevc.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2eokrdfum.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yqikflrr.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2foekssdf.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsryvcl.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2xaivlnur.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eyygldnp.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyapatb.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bopurhkh.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbkxfer.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfzybjq.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nmuwvkha.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfhvace.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2phhgcxmg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zquwndut.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2uusxqsad.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xqsfmhky.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aouhbixe.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2oakwdiqy.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpvpddz.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbqxzvc.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlxujdx.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2anvnmerl.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qroyldeo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qsimlqid.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwrlbbj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwwdkue.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ahinqkha.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogyzijel.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2kshxucfr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2busojnqk.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2geipvzum.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2sawplker.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2tadcpcel.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhazruj.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2nrufqahi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbmyxpb.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pnavwepm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ziegleao.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrrnarj.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2htsvrfjc.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2jevowlrt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fenrkpyk.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsvjtzl.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2urgocszf.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxctypa.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zzaoaqki.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2padbhpmk.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pqptxhro.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwwscur.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zdosbrag.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxcsazk.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhkqacm.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ankewyfb.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jppxannw.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mjubbqxu.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2dfysprnb.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyqmkuy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2nstdivsx.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxwcxuv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fadiamch.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xpuynrsi.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ualxrumk.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhzfwuj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2uendsbxp.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2drmjljcy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bapbjhkt.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwegqzw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2vrasqdhd.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2spinccpo.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fnukmfti.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vothagdh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2arscfgkb.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnjfnet.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvtgwjq.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzmiodg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2aizddikf.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2eamfjhle.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2dohpyeuu.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgmswac.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbkkzms.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtfjxkb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2egunyogk.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlimmjt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2raswkviq.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2munxcqbp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cyabanmj.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgaljun.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2trcxqckp.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uujdeasp.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfultyc.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfsaoio.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2njikhekd.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dofmyzmt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmwtowk.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zoinzhho.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2hbppgvwk.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2urmfqauo.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfgiaub.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrgqvqs.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjnrbeb.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2gxacqrph.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rcavrilq.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2geuiijib.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2uimvldvd.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2dchjqeai.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxfwstq.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsgvctt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2tezbgugg.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2syqooebv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ekesidhi.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ngekogfi.html


<!-- 参考信息 -->