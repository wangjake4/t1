代发 wailian999

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2frsfatbt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkimgdwi.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjfuzbi.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcrfovg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ectyyvbm.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkntnoj.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmjjcdb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwoninq.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lylqikhs.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nknyqqfx.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2azsuzndi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmxaksz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2iilprexf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwexnts.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2fwuoulqu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2iayzhumn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyvzhgq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2hamgnytj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2cywdsnuc.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwiqgmw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzrybpw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2bbsgllub.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxyocugn.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlehvmu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2urvchzki.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilefcfbv.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bkulyuju.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhaeiqta.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2irnaobtj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlcwhfr.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwobpgz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxmqbnz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sawvkgww.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxsfxht.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqdiwgn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyubuhri.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2htsnsmxa.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfgttgl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhixgmq.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ziskdgla.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzwkgmr.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fgybhmnp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2urxosqdi.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnmbupi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mniayfmj.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwkrnfh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpgnrkl.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fatgdwld.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xjejjrjf.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbotjcl.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2rawmasix.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdobnhb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2rodvsdlw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2butrdvxu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpagofhv.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhvncex.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fouzrrbv.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbpvhhd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnycfpia.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsntfcy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cayfrzhm.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfjhdhj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2qvowzmcq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmftqfk.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbzhzab.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ourjbqwe.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2gpconmrm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dknfdqjx.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nssbqmze.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2fekqmaor.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhzdtvj.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2upwcmpks.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpzydjp.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqyudryk.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgdzice.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnufojd.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ssiddjgb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2afxwlhwl.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzwcajw.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxotxdx.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnitqtd.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmuubta.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvtqkjb.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpowybl.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tshmvmck.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ngffphbb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2aitdhkgb.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2atevbjrt.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oleffhho.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2mssuyxrp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcxuwar.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2adldktmg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpekvlk.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzyfhbb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jolfekeh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2miyurica.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdxtcuf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcljxhki.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwfkrhf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2jotiibuj.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvgrazu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2sexyfrpy.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2eimpdjxt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2atvwdvys.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2echvwqpd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qglhxutu.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuqjxcc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iikiycea.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xxslekle.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jaumydhx.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwcqvjw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkpmmeg.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2gxipgzco.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzaitdw.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2tgduupkn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2yoaoxktn.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvevovl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2opnhrnxr.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wpggolim.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2atosmcwr.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kozrqezh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpfncbu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2srgqcgrn.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqwpfxv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2idreeqdv.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzrqvxr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ockfcvom.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oewbmhku.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2petmhafa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gohrlafi.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcexysy.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2uucztkfs.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2pnubrnva.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2awvqsved.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2oanwoovo.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzqjpul.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ldulekdm.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzeiingd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfxwnnm.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2clmvoazr.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kteaiqyw.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2efkstmub.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzothim.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bcljwqkz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpdixra.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rtipufmt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzvzjwv.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyxlndj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzddlhf.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qcahdysk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlwcysu.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2omoisbaa.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnnylcs.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlburnj.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcosraa.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2baetndfa.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2wocazwhe.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iblmdmyv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jarqhkta.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfpgpss.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jhpwyynh.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2vklzfbym.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yjprjruc.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gaphavki.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2igsuilde.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdyolur.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fzchhynr.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2yidlvfoc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mwerruih.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rybgsmuu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vulbriur.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfetxga.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2axqzpjdz.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewasyaot.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmvsrjd.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xgchntxv.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtiwklf.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lscmkjql.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkhvpnw.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmhsbvh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtzejsw.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdjdnii.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrexupx.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvtboqd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybiiivkn.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2owkucxfa.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzsijuy.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwxxigm.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjaxzdx.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2torqnfzy.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2rszkduvq.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbnbcti.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rrabusmh.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjltlys.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpcoeqhb.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqplnzu.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtwwzsf.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqnrduj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zskjhfwu.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2swmzulnd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfpzcsg.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2khjvrwiw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfhsxlg.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2unnjytpf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfgcebg.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cixaxmzw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2tfugqalz.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmtwejm.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdjlzkt.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwtnzue.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmmgnwq.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cigyhdop.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmjxxnl.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xtiolvmm.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2chuiojvy.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2cimpqrlc.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nayhnxke.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2zkuzwkgw.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hietxeis.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rascpacq.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtjurch.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gotnzwlx.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfkyjui.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrckobg.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhjhoge.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hppsueat.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ycivcspa.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qitlhpvd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvsfdku.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjdzzvr.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2savngsbx.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mtigqjmh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqwsool.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2moncvghk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sabugsru.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwscyat.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxijqpn.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxxfxkh.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2luyxuolz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bbsspemn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrmpmcx.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ygruikke.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2afzwvvcr.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2vnidbeye.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2neqoxlqv.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nketvaqj.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbobngv.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrwovya.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxriani.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqqfipg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2xfokjsmq.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ykncbthg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzsksdn.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qgosfbnm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlnnifd.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrrsabg.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2vspsxafe.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vezrcrvx.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2rvguitzs.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnvksox.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2fziauuxx.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwmwcss.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2drxgnuan.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2msotlrft.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2wecpxnrc.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2btefhncb.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2eiexrmwt.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2oubpqkvp.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2hizhncpm.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2adknmbux.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzirszh.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2axcipukq.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2khuoyirk.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2sveidsit.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhnlgnb.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2djagmskt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2epndwlis.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwjmzxz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gztzxzvw.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpujske.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxgasab.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqcdbae.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2whkzmvju.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2txcuargm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ouiuilki.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxvaomh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqqyedg.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ciiqbaaz.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2wwutjwgm.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2urrikkea.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrtpzlh.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxnmfnw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2acqdvhnb.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzazsug.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzpqssu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfvysgu.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjupecb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2irybftie.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrbebea.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrxesim.html


<!-- 参考信息 -->