代发 wailian999

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2nakcuqza.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kuszydby.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2odppjfpr.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2sndpvoko.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrmzdau.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2lhilxqty.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhzlmll.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqksubn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2izbtgkgw.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyiggnv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkymfsg.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2cycmbxef.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnzkwkh.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rkybpqpn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2spdimkhn.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfbyoql.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwzklke.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpuiasf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxixsfdm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkajbfh.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2alxxxqld.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2deivtlxi.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwurimj.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2kplfoiaf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2pduwyisl.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2krdjxjmv.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2aooimbpw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2neyyvnzu.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gdukvcxp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhskeieg.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcuhrpt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyxzrav.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ruffizmu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsyppwq.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2nldfygmx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqrxyhh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjykkli.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2sotqajby.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2newptwsx.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2npwyzztn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2rbehpoql.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqwjdzf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsqfnpu.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbcxbvq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpyudjp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhqjgnn.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2szmhryfk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpugdby.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcejrgk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdybyimh.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvnstyc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyyueicn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ulucgojs.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbdnpoa.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eknytzvl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2icvxsrdd.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ywndabpc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmyaqexe.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjxrnfo.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmelwen.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bztztbxn.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lebdvvrv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2sztpbmmi.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvggkfy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpkllwx.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2fklygcyo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyiqcebc.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2denlygna.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2bueagcai.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2wsiieodu.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvvdgtr.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdkayev.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjxzvqo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2tspeknkx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2goewpogl.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2apfrsrwc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2svjscqpb.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zceutcvv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2exolnbpr.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2xqefvglg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2najpnfoz.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2npnlqxhp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrqihtd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrempzia.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwyraqt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2decnmxhw.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmoccko.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxkwhee.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhgttnh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2yojtoibf.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2oifrwrsq.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjeufar.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2oknqyhgd.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmcgirs.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2twfcwjec.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzlhxvs.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2qndhbeuo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2trdtwulm.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2flmlnirs.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrndzzjx.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tywaddvc.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2zmavgbgo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2aunhvilx.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxeqxmn.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2knvjawss.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2eeitonxc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhgiicr.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgtxpbd.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gooubfdc.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2pacmyofc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ldszzuel.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2verkgnvg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2jfyahrur.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2urwhcrvr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvywqyhb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxzowpi.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2engaupeb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2iezogawt.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhoujmm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2tazfwntg.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsfimpy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2wwymnkky.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvzyiop.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhwurup.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2vtletrde.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2msfbrpah.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cyyurjqk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxangkk.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmyxkkk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnipgpm.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2skddhiut.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrsmcgw.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqgwgex.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjnuonw.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgejbai.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2clhghhdb.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zisccyqp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2qrigvonq.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbyomrt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcytxrvc.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2grdrdipr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2dsibjrcn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mluywbut.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ifoxiblv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnydscj.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2gvozznxg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gexgyxce.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dztwssva.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdlgbvc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wfihwels.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2irlwcdgn.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2iielpyjs.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2aefhenpv.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2nigfcxye.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkpyztf.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xbouyibs.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyabopt.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ruisrxmu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmnnzwv.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkblaro.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oclcpyjq.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iptsjind.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cagxrtok.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhreipd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2negyypvg.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2izqxeeoi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2byhdcweg.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ehotcunu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ihytuewp.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbdzhyg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fabwyaef.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2bqslmsoc.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkedhhz.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2evguyuql.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2chojvrnj.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdyakom.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2cuidarzw.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmpxcsb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwyfxzd.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tchxzdry.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2foqaqkdd.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqpsbhv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbvybud.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2toayeuhe.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqoaghg.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zojtchso.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eurryzeh.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwknyce.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2trxtfwor.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nfndlizv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bfetujki.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qetxohsm.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qiuxgkoy.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2puizpijm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2afpviylb.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bznxpkcv.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nwerchjc.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lizbbyxm.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2awlpbrdb.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xdshxxgo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wtoebihq.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcjvihb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oohkiqje.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ltymoytn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zzumndpv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzwnfzg.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2efyvmicq.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2sfltratz.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzvyabi.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2tatfjrjr.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjwmirq.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ziumlsmk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nizqupok.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tgquuusy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwtmcub.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvojqwb.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwrmqhp.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqpanbg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwbnxhe.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpabgxq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2dflrvpts.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzzzlzz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2drnganfp.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ayitjyow.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2hclmowil.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwujevc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmwiwea.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2whxdmzsi.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lutdrrew.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpcvmhs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mokaenpp.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2evnbyzqa.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bpiizbgs.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpzmxxb.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qxktbhlm.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrenyvh.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdnmske.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ymabnkwx.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2laegafhr.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nuozshjz.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxvzxxs.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjrnrnr.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mkduxllj.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdpebtm.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrglggr.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdzkqax.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2hylcwzgn.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rompdmmt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmjdieh.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lxyvrhle.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2whsiiejk.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2luvknkyo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlxahhf.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfdbwzm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lcorshuw.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2baqlpmdu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhshgsa.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqpryjs.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfbswvn.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ddotqcqj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2abtzaskf.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2clkavkhy.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gsiokaoj.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2eblevitv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2eghwnqkr.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2otfsatux.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2zioxqfcy.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2dskhmhgl.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2eygtzcai.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwqrhzf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2twtfjdxk.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2feurrbkd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtuujyu.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcdlldn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bykrismq.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2uraoqmvs.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnucabl.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ytauaolc.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgjbvgh.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2akvrslus.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzpbgcx.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ensidfjv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbfhdfj.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvlkopm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2eadfpjsw.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtblxoi.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fiyovkvt.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2byogaaci.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2aulgkrpd.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpquflt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zuylgcro.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2uunbfesv.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2oozgfedf.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2vgydpybx.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2izlpcjlh.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwsvwag.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmuiautm.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbnnduf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2egcbvnnv.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvffnvz.html


<!-- 参考信息 -->