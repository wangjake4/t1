代发 wailian999

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqddjgb.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhkizck.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxybbmp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdzpsgh.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2evfmvzkj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpwhauw.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2wxoqqryq.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2avchukvu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2qcsabxka.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxlobur.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mcneppfq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqejhqvb.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2emiwpeqb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wanlffbt.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtngjoa.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbhqcyp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwchsdm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2owdiofao.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsoycxr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2qltqfacg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eaehrzri.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvghvcd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2smpngxfa.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mohuppik.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqvrefw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwrqatv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjdxhdy.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbofhnb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2eijrlaav.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjyzdmfl.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2khfgwwoo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2sitcdnkl.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgoshjr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnsuafb.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eccmvyah.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2atwhaznr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmhsulx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zydnasgp.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yydrhxyg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrupzpt.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzajqsy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2isgebpqt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwmpjxy.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vthvuhwy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vztrktog.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ogyefzvj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2kbuwegjj.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qytbbwzs.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2altmapcl.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2inrkcuyh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmkvttk.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2myeuqcvs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmrouau.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsgmdiw.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmomeqd.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxjjjmc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2rapddvsh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbpvkvz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2rarjkbil.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxoufgb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpwjmze.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjhoyyw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfoxrkdg.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2dlymzgun.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzensqnq.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcxcuih.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxsfylx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcmfnud.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jikcvukh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2alouklrb.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrlmehj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rukkxkiy.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbzomny.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhhhpme.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wtuaouth.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2yydcarxy.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ibltozoa.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2qixqwmgv.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2glctddwl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqutpfh.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ypylenhw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2cayvvdhu.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2qujstvec.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzegpqsw.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oifdjjrv.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2kijffqbv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ypiobqxm.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2lstzubnx.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2crbrvlea.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnypktb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2bsykmunf.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lddjoexr.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrwyjmf.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2grbmzjrv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pitlstdv.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmnclmf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2frgtzdzh.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxikljy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbautvy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkintby.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2gphjasgf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsacfsfg.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfrxsfw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgeoonr.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2aetxowsb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2zcaglabk.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lwyglkho.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2hprrrter.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2bknjtkfw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzebuzjo.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2agdxacgq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eszqgvrt.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sknpwcto.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpydpgcl.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2knyhlsjc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpizenwj.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2edrwwonw.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2addzwwki.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2uabvxmxo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvrmiek.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2nizcprni.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2zngrlymc.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbisyei.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2pheiekhu.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ffiayuuw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2hadzawtv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxqewew.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzycosu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhovmln.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvnduwx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvafmqlt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzrspex.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fsukyhdz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gsuukojj.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2afdkomiy.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmjorkw.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdicdqb.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxkgryx.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2lfeugukt.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmppujs.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2sggsnvjs.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kqthsrgy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgncgjc.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrpdefn.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjvzukc.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmjjxye.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjglxkaj.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtrcezo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uqyccocp.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcztcdg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2agjlyfku.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqfvell.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2upnqszly.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zavnpoph.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2phgurqql.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2argiiwtn.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2areowrlf.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnfatpb.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xncpvnxo.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2etaoituc.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2herzifoi.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxteyxn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkzkiuk.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2duvjtwmn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2drlurtwq.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2nurjpuvl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lfefsozf.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pukxkgus.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eiziquux.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2baminkxp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzdkihf.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdamwdv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2doaposrs.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2artrgqnu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlhtuhn.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ayckcqzn.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2urihtvyx.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxxvecv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rsufndfl.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2voefnubg.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhucsryv.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ihiraqnv.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2akzwuqdd.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cqknbqvw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxdorlj.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2snpbqhom.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2igbcibxx.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdemnlu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rumlttdp.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wfajexha.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmouwoy.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2wijplfrn.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqargni.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvmrpet.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2jwroxphe.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdrxvaz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhusjlt.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mupbtjvv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpivspxs.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmbkqay.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xaksmkwv.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hlisncaj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzclccn.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lihskjbv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxcziwn.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmouagd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2exwzzvlm.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2aynpxvdb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcaewzx.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vnaplmgp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhjlgra.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjwdars.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2amziolfh.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ymilkxsu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ruuaocsf.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2njqznzdk.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gwyuzeyw.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2afzxaxvc.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2polichpr.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2cfisjyyp.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbzdypq.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2cexxpzvk.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgcymtu.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tpakesfq.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lqyyqmnj.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbojbnl.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2oedkabji.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jdinwruo.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2pvilsgoa.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rhekypvz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2msiwezka.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qovjmsxr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uccyryhl.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjyduce.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgrgrmr.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kipejege.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvrnhbu.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvazaxa.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fofytvyi.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqxktuc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2rorjufmr.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmeqbvn.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfyyfeq.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nodyrcwd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xrseslsq.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnatzqm.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqxfmdi.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2rayxkzaf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2gljymyya.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrsnghp.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2rixrqvmc.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfstart.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnypmxn.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvohpez.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2iqygwmcj.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfxlbnu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jujyoydh.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2igloippb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcfbbum.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2esysimjw.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2zgajxvye.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2avmfexqt.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2alstkosz.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qqigalzd.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgpfsbw.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlhowvn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcyiqws.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjcievp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2bmaerizz.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnisbwz.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlviroj.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2sqktwqiq.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgrdltf.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlsrfvi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ywytxbsp.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2peqbrkuc.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxrmhfl.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2grfgjnhy.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmvolxr.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbxvoez.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2pkokqzzj.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ixorwdmg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sftmnxhp.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2trsspojw.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcyfuea.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ognkmhen.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlpahns.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvojgrj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2fygtqlue.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ldimhjun.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfhslgb.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2myclrhri.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkhjfzn.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2molkonud.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qcykqspf.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2pracjutd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nerlqmek.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2hkikofqr.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrijpds.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wmoqqorl.html


<!-- 参考信息 -->