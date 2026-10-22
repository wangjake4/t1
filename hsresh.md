代发 wailian999

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dksdtkqk.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2phyyytey.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhpreqs.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2hjyluvrz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwimlmcn.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyzdfgi.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rodtmmct.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvkrpum.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrynbpb.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kehlryju.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2opfjgetz.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2whgcisps.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2odxnpmtj.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsdbbei.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgsvwbxs.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsggfob.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmztlqhy.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpicsmd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2uanzyinc.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dizdndsj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkddjkxx.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqkhlau.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrhllks.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2mniksktb.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tbprguij.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbuwuxq.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwniweh.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2btplufxd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ujteuinu.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2btezvsvu.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqnvqwl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbyhtse.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ycyihvrj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmijzek.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zuiwwgqh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2thrutuce.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2gantyycg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnxwnsb.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jecdhrjy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2iftjqswo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwyvexfg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvlgple.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkzknfs.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sauxmsgl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlmwcpl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2dtucjzoi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsapkzr.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxkdang.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnohkqv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2biabymvm.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsultqp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2uggcuqdc.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbaasno.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhmeonf.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2oozlqqpk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2eejmouoa.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dichmvml.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnraempg.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rzasbmhj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmstlydt.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqbiezf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfsjrnf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqunmvxx.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhujktc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkwxzym.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbkpmez.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2yovmqgyk.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mefeqkjk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjwqcum.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2nqiptfrj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2refryfqn.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2niewzqoy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkoinkx.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfzdofe.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqvuojn.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgrljql.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgczxvhj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsfovkr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2gaidohix.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2bldrcreu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zghxwdln.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlgpwby.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqlyigl.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcoopjh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wogqahqr.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuibhcm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlbfukb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkiapzt.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2clmqejlb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqyonkq.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsbouiq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgoiqdll.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvzznud.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2eyarfpkz.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qiznxfpz.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuishuk.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnqeaav.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2wedoyvyi.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uaeqclzf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqmtxcb.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2hmujjpbu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmehcssp.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2dovviwyi.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bppdcmmm.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvoycxhj.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbcrwgq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2rwetcowt.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2zitdwstv.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhcxuhfr.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkbdzgm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2arcdsucc.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wstvqonu.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggilqyyo.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2zltelevb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwqkidv.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbnyper.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2agrncuvt.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtyckiw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bebkwkeu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbnulmv.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvixqhf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnvxbej.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2jpiccqhw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuzdnjm.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpmqcde.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmnweon.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2dledxxmv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2eslvshee.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzipyrs.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhexuut.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcjqqhn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbohpab.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcgdkch.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bejfjlce.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cmeevnam.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2exdnzomz.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2bybmcejh.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qygzpjor.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2znfwptcw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmxxdrs.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnkugbc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2pjluqhxy.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hmemwege.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpskdht.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2gthwnuae.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2fbaayhvi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbpbhom.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsupiub.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tqadhdmb.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2emrgwzky.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2reghfjeh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvocero.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gwafphrr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpqeaeo.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbejvfd.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjckwqm.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2huzaodqz.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtewlnd.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvxdkvs.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2akvtowsf.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzcekri.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvxmqqo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2suucgjnm.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2raqsvimi.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmglmml.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mednqrdz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgivaavg.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2winvrnfk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgbmiuf.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2elmxbzdb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnjyjby.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjekurx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcjlgcz.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjsbcvo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zirrskny.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ykontnds.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2zomuicad.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2smoqjcpf.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsanyqpx.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnegyep.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ieelupzu.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjblnej.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2symebqlw.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2odjdmbbu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqhsqur.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2pzyjfoeu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkhiucf.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ptclnpev.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtrtruh.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqucbdh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwukwid.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2kabthgir.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gubvrfsw.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nhflqblg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlirejh.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2domptoeo.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwonlvl.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhgjkdv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqjzcar.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wuenyusx.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wczcrgvz.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqmoeqo.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlvbkjh.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzarqye.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpgmzbc.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrcafvw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdcirjm.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2xocuyfib.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvuizjxy.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mukogbpw.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2obdxgkcv.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2bgydbmwp.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqgzeru.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2keuxzpob.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmaxnla.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlwkypy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2axzjhopb.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gocubcsx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2iytaiyke.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dibrlarg.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkfdrab.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfrosnb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtbuiqy.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfuuary.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2yoyvsmup.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2lohuqyfl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtiigdo.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xziabiux.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2iinyzhcz.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgpdgpd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvxkptk.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2whnnqtzr.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcqhhth.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2cqsutcig.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcmxxzx.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ensyhzjb.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2sjujejbh.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzscjvc.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jmusciwl.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yizoubxk.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqgjczb.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ajexxzyk.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2saacedlq.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfebxke.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rqavvpaa.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2npslymwq.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gptvsipd.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2aasxjrgi.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzbmzqh.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2kmodbowd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2jzktcfka.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nhiawdnc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvdfpnv.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bksovtfg.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnauejd.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2imibeqoi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqymkeb.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2siyvjkpi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gpojfljs.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbmxort.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2jccrqwbj.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2kbomghzk.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mxoxlmxm.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2aevcbfay.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2slufdvdg.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2usgqjsgi.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cvysruyz.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhtollg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqbrbwi.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rhldoafv.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcntrei.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2lieiczmg.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2vrutkhrt.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkngjtn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmlvqaf.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2egmmyabm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpxwsqi.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ocafubpb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ohiszfsr.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2osqhrjbw.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzcafzx.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kqalkezx.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2vltxkoei.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2diggpwcm.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpaedas.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2puomqnnl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfagmcw.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qznbmetx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2mizzljld.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2roorxdoj.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxxsefs.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2avegrvak.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2lrstfpui.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2lmujcoop.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2skfnoafj.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmzjmiz.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzjtbcq.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsavmxf.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyekpdx.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bgoyliom.html


<!-- 参考信息 -->