代发 wailian999

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqsgmkl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2aloyegio.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwkufqq.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2eetzbsxf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrelmgi.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxrhpoc.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrgaatu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihczgxlm.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hmysoqek.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzhultz.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2urdbvist.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wytvrfdf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhpstdo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ciyyfpoi.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2tciiniel.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvijylt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgymuazb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2jsolgpnp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrbofbo.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcehehy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfgommb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2rkihokgu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmrzryi.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqyrglf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2topxjteq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjirdej.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtmdkik.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfnkjot.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrveymz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2adzzoekh.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xethcsbc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qobjwgme.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kshgxlws.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykeyclyz.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpmzjnf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbbztdw.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mhyjnijr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgaymvtx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqixirk.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbilpfy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2srhbcktg.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtfayde.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhvskxx.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgghbge.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdalnzwz.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2pggnkfly.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2byssqhct.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2grovmosw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2njqwbhjh.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2amghumif.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2woskfyrj.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2urqqspmy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2mymokxbb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvnzkhd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fosdajld.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2opeyzhsb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmtovlm.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2msyzclra.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcimrtnk.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmtxqxu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2floopuen.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2pzeuqomi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2uplcldxw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzcaxqr.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnolynm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzggadiz.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfvxikt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kljvbvsa.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzjestq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqtjnzn.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pvliwmdl.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrmzfnv.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fetnhpri.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqiocica.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ukchilmc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2aprugpud.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2vwspmkce.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbohzqx.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkcpqhx.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2drxglwuh.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hckmuqkn.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlhdouk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2nvsjxxqi.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2aoenjgix.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2emtnqxan.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmeaaca.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2wogvzioa.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2oddlbxpg.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxyzevpl.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2gicaaatr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpeunib.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqnhxbp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvroqpi.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lkknjgey.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2luxpvfkn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkkscxu.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hvptivbl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgvrnok.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2xollhnaw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvaqraw.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwzbppu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2dhaqvylx.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ucaavfam.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgrryxf.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvdnzis.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtaznath.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ozifvluj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbyboxi.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jiigjhjf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2szmawurr.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rqimmlyg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtoqsfw.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ursbmcdu.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kucohqqb.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2dqaoleee.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2owudjhvd.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2llspvkga.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtovgsa.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2brbiuldq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2edesfxmn.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjpjlyo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2yqfqjddj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdeojvxs.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2azzwipsx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkmyzha.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2lphaavze.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wasgtdkm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2euftbweg.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2homxrasj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pevzktvg.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrymwsv.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzxseza.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2bmajdymx.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmnpqno.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqixwrmi.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvyxext.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrlewaf.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbeloir.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2jvknyunp.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2casdeqru.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcjyglk.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xruckpxk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khrjbrkp.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hyghhfgh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yidvxmui.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vuajezst.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2etqzkwpk.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bedxeltf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxmrfea.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ripranqj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ccedqakm.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcoswve.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2knookrpo.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvnmpnd.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmamnxu.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqdyhnh.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnptzdj.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvieiwu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yricgtip.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbtpkrg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lniqgzae.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2jupjeanm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fxplbvni.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rolytycr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jbupuauj.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqwfidt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xapaljgr.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2oietcoxa.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2svjbkfno.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mksfizvz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ochiostj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ucltnqgz.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yajglofv.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhblljb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pahwmqqo.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtsjpjh.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nofgniwl.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hyonukop.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aipnziqf.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oayporkd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2khdgxfek.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2crgkuyet.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxluszgq.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxowzor.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ezthcrlg.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tbiisxrz.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbeexmw.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2icvcewhp.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpkgmqp.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmszfyj.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2etwdcbow.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpjomlj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uglwsdty.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdiwxtf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2haofsvkp.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtvraub.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zteykrdz.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnpxagi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdoaizb.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ssoygmde.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2lbznryvv.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2goqperxi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xmifmrgq.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2jotbjwed.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrlhiem.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfebnci.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2efgqtzzv.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyrpzxp.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmxbjcc.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2rsoqtutl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pubcpmwd.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mdubehqk.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2sazwlcbc.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yyahtwoj.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2solylqdj.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwxzdjx.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mdznsqqa.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcwgrvl.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqtsfxn.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kwuzbnik.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wscqgtsw.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcnxncq.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwtnrgj.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2oefcojea.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmdleqk.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2elhlgmos.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvkykln.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbecdzo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbiybnd.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2znuajopo.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2udqcnwvq.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhthmwm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvvebgc.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ezuwxzir.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxltraq.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2wnigwqxn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2myiabkxr.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2nxngtgiw.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lehgvcrn.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnxsgaa.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2joxwcmrc.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2upayesgm.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvxzjzk.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2edpjpect.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdvqoha.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgvgrbw.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ldetcnzo.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbhcxfo.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2sesjifuv.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfjirhv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcshokw.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjrlmtd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zneqbsid.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjyjgsq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cundmjyd.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhuuyyn.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2dyofhqbg.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tieasala.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ceuizbpv.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgzwzfp.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2btuhjqvg.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pzuwvapy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdcyibyf.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nskhwhop.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2wdufiwnm.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rpibmyqo.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2innuveik.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhougvj.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2aazwvsrp.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvivlyh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrzqzlm.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvpysrg.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2txsojufu.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ipoknnma.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmpyoec.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2axcquxwq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2jogoyprt.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ombggpjl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bklrfezp.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpojrqh.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2moiwcurp.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcrbshe.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jajbllmf.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ulsbssnv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlphlxy.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mczhrvrh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhdxicg.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2vaiagulo.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnqsiuv.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2emglhfoe.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfptxvu.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2djyzdpjp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jjelcalb.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2dffbwmqs.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhhuxcp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzbvqlm.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2spdbdyzq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2talflyke.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmbhvxx.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjydiyn.html


<!-- 参考信息 -->