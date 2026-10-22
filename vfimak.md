代发 wailian999

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2khsughxt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyumszkg.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lriztotv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwlwaue.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvzpnui.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgceroj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkohhqec.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2efhyqapo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2nmadwway.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2sxklqkzl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iryvphtu.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwpiiyi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2vktibnle.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfshhxhn.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bjoohttq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjcrtfd.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbaixpl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2teydilhq.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmbcpwx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2lotsprcg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dghbrsqp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ueslawvu.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bucrdhfd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpeqebh.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdmcuni.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyomwyii.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhbkfhs.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lezyfste.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uidgbntt.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfkitxm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ovftgfcp.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kzuhlmcm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2omvkixtt.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2mmruptaz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxtgxrz.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vllcjrfg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qbimxiyq.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2dhyrcrol.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2omkqdgtg.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvglwyk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2skwtefsd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsxmvfr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrhlreu.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2unluyfzp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkyiavc.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhfcjee.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2edzvnurg.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2xunajust.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwiqsahn.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qggnxskd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvdphiu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2znewvosz.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqmxigq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2riwjewod.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2wahqpbai.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbkcrff.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzoltmq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2puehwzrz.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2meyjikbv.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2seqmmowq.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pdulshou.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2oweyfrnl.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rewnhjza.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2zorlqzry.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqlyhph.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2fugktnjr.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2gipjtfnj.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnvhleb.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmocnhx.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2giftuthl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ynewobgi.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhriaqw.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ietcpspo.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2dimcxxkt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2egavgrod.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fxamhsmq.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ieauwmnc.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2llfxselo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mxevlpxm.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2iduepgdw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmnmpsw.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ytofpvxl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mebfpemn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ixaboygi.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2galbgdph.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwmsald.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2kspiwhox.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2rdckkicn.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fukjpvzd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlayqbz.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvxmzin.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwrdzdg.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2itwqpxdl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfjiksg.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2govjlupb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdysbhz.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2clovrzvf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwebxikm.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2czrxkovb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eldqnduh.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2dnoefxfg.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rveclohe.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2xtryiovn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2fidyqnxr.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2qboybjsa.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2zdialbyw.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvxndob.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtegasr.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwtbxfr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2txewahtq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvsvvwh.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mewovcok.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxizrgg.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnxrivq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwixpvku.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhntijw.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dvolqhgo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2crxavhls.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxqyype.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2znirnqme.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyqbnzi.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2nfghpuqa.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsjvjjq.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkkwpkt.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2udcwivzo.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kdflsrgb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2jiryvbez.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2btuqajsj.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2auggzxhs.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tirsefpl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjphdsek.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxkwaaw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrhuekq.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzckgkg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2euuranua.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jziwdmjz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ktklvvtt.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkhlpfq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtxhuwd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpwahlq.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ojppzmbp.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgvfxqu.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fftrakig.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjytnnj.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2laomgijv.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwfnxws.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aoehzpkm.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvxegku.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mosrmfuc.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzmwkny.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2moytpohk.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtspdxu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsjvpyu.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fssxugxg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ucphfwki.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2lzeczuhs.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yqocmlrr.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nymiyazh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsavxhi.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqvqkws.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2axbzwcro.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqymyem.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pepqkgge.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzaaefn.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fswxseda.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2kemesnwx.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2edyopein.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dswkmxbk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gygdnxws.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2osyixkql.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rwetnmur.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyaxnho.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjagpyo.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhhoczq.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2rorakdbg.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2vraoyoht.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnppumn.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgiiexa.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2snqwjkfa.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2upgxklep.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jmssoqwp.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jutzllmj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2skosdewo.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdbdqfq.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkrkvkf.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdgppkp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uowkqdcu.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2irayaswo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgpfgyp.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqpaefx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzucxuk.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlbhhhp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2exmcnojb.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2iwiyfjfd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2knsiezro.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2btxlzsmm.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrcevxc.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2swfzrorl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2aiounrai.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2etcwmokk.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsflboe.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbermkd.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrfsiba.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnybdlp.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2oiulbmyg.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2btedmskj.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fiofdkni.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nuiletnz.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ankvtbfb.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2axcwrztk.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcoltql.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jwoyhype.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2nihxtwmz.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjlyivd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2dbweepml.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uncdunrg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfynhgg.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2tolkzwmi.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fspjimgy.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vccnjaop.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzvpwcx.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcjlopk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnndjrl.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzrtcyy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2yytdqbby.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2jvttrgbh.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqvqpkf.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjafyyx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2kuilbuvl.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wlanwoix.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2inscjflj.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2iafwkesf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2fqraspax.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2msjnjlpa.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpasiye.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2udnnclja.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2plclqgnt.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfiiotz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsodyud.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqvbzak.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qcaiiebx.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nfntetpn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2uadispsc.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wekhejad.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbpzagi.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gspemlya.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2xooogtri.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2unfzfnbc.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbayseu.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2nksevcyx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqorpgkp.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfgvgrk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzpngim.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2osknizfw.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2giovecuw.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2asucubnm.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzwatfx.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2bktsuucb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nctimwxs.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2oecuxykj.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzhogvr.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2vunmeudj.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfptino.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fuflzcbm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2sulzjppq.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2usidnkmy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2haszmlng.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kclrofmr.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ikijfaxh.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwqsctu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtoesjh.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yypitpxq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxihzqmi.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wsovsitg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qmuholza.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2uacqirqr.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2elnrxlfx.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2mroeyzmi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kypckowu.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpzujfb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjzpvip.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvnzhcz.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2tseswltz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2culqmpjg.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2egaedkui.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwrpulq.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsdxvja.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2okkqezql.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkkhqdu.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzucmxq.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnotnjk.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmyapet.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpryxpif.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2abujlnwe.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nvsxelpb.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxmvtbu.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqtubkk.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lzydhkvf.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpcnrff.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2uymhrkkf.html


<!-- 参考信息 -->