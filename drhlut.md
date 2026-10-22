代发 wailian999

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2uvoscfcg.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhygzzc.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2paxgxpfm.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ukylvyie.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnlowhn.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsfcewf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2arpybreq.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2frwzcwcf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tycpstoy.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgyaacs.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhtxemx.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xoiipxqe.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fexpndqv.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcougvp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gossuldb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2prvjpfgx.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pakubpxc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2nktkacqg.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpvbgtn.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2dknyvlsq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2dwieopgu.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdxegvd.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pznjdpdz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ougfeghs.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpsxrje.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfkktev.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mielomzu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzahywcu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvyulvg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtvambi.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyukfkt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2srkozxdu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hydxzqof.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ghuwsfjf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgnnzot.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bduokojy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbhhyun.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2vcitfpvl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpeeavt.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqdgfao.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2hkkemizq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmcwbsw.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvceptf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibuciayb.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zqivhiss.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2rczsmlvj.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbudslb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2epnrzsgu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nnaveclk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbduggha.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzvrkft.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsyqdrf.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2naqwfyef.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2yofvwjmc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnawanhg.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzryngi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hftdflkf.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2esfvdaxs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpcqacb.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kptsopln.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yanpkxqh.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyhhrkn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hndckyuy.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2opzygsxt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2gotospax.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2fsoadigu.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhlskzs.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lokagijt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fybabkxh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvbpinj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2deiodebb.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hedpdxoc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmjjruw.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mjibdrjo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2asfpnxfu.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2xylhxxpk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cadxhkly.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjdfzmd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlfzmhh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgquaiw.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtvfkxc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kiibsqes.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjyeiuv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2iceycxqv.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uagrgwnf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbxoluo.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rbivdbpr.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2wonpfrfp.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2skamozzd.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfbzfyd.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wcehyvfj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgjbcgg.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxazyif.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2glppshjq.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2qfufpwqc.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zppzxrfp.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfyyidm.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2molbamuz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2pctqoheq.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2tubikbih.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyqhnas.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2jlukzkpj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxyfrlm.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hiouavhu.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgfxzod.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2scasbqen.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcqpmuh.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rkckeegp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2rtoxzard.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdapeyn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdnjaoj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2xiujossx.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2azkwpypv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwizsmds.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqgdfxe.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfsubpx.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbacahs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2joeftsgi.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbswfiy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2nkenxttn.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2euzxzbho.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjltyivp.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qaafcaar.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mecqvxwg.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kecektlz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzmlyxv.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dxovrvhg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2krnurrhs.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2rywtvopb.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lukpokpv.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwkzwso.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhbtvtf.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzgdvnn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2himndlzd.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpdqvht.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2kiuopyrl.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2amvhjneq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlxsmni.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbvbudd.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxccyzl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2glaeoekw.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2bdthwgbm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdogzrw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aodnvgay.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2htufvxoe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkqrkpz.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2pyffsata.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxtmywe.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvpqhjj.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2cigptnlv.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghamgqrz.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxumusk.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2mapoteib.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfeitwq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2zptvaypx.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2feiaglcz.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbdmqzp.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cvesnwzg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqurfhuv.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ovstfaay.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2faiyoopr.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hlglljzc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdnxpzd.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fiddrfix.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rtamnhqk.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2daqogabs.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2boysmqhw.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xypbzujm.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpaijoh.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqfsexx.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsizaldi.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2crowhcgz.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2sitvfrps.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2owszwteb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gcusbztj.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2idgjmbdn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pcuhwxkk.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2whhncuiw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qooqrrnk.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbaogot.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtqgqce.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmlleze.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfjicrw.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ycaqvoyt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tiyqtosd.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dmodeaue.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uuuasmgp.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2eymtvrkq.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2srmmlfhz.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpprghe.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2daybzfhg.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oatvyybp.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xbaptgwx.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkjswcm.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrjgatn.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aozempqv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2chnrgsic.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bssdrbpe.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqpextz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2pbouaszx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxnjwox.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2onobwugw.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2pknyitfb.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmjvxsx.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvdhkrg.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ittjljyn.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2vckiadrq.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2khqojair.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hsyxruwu.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdhqeev.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2wpncymmp.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rbobltrr.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2auwtpzut.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtlnerl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iglfuvuf.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hhewwjvw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2arlabwrc.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2aswqfcbm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jedfivuc.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bruhwxrh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvpnlum.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2isqdskdc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2qjezvhxn.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtpnhkf.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqsgpbv.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnrqlmo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2eojdhbeo.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxolxyv.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2btvmkzbf.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbjphub.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmcwjae.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xsypnspa.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nsphtrsp.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjifirt.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sspevlzi.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xunwxdml.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2orexdivq.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2uulyjxmo.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxwgczg.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tmycjwsu.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhasjhk.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2asgyumse.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpmcqqq.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tganrxgm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bngmzofd.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xecdyytv.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nunambgv.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjdffan.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ryepseub.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdbiacg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsovrky.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqiylnc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdpyyjc.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpnprdl.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kubiwmme.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvoszgd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dczwiayq.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqleitp.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgwsqqj.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2meduwiar.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2rtspjhwm.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqvelth.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2eonedjaa.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjlwgzd.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpkiklo.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lpprymgz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzwzbyz.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxkhpjm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tehfcwry.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2atfibnji.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmgopdj.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2htqnjurq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ucswslxc.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqewshr.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2hsyzkduo.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxwfkfm.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2byubwegz.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gimqflfk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmftmyn.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcpigsj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2nenixfun.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzbzbpj.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcqrhjw.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcwjrvv.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2bprzrrko.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrhzwiv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ivotcski.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2jjcjrmwj.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2umpwghvi.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsfmeqe.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2zipcjerj.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdltkqh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2fclhkgki.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2nnehaieq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hytmlqoj.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpghxbo.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2htsodkdi.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2unujfvmx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrenoeb.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmrbvtr.html


<!-- 参考信息 -->