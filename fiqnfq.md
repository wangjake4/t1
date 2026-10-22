代发 wailian999

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbgoxld.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjmjmaz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzecvorn.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gnupbruw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxebzxa.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmqfczt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsevznxk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2yysquzhy.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yihkeyhb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2prfdjhzd.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcoaizt.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfystyw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2armznini.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkkvubf.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmfxcnv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqxkpwa.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqzqohs.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtwhqqn.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cawhinqt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrscays.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbmfmif.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jibplmjz.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2glhnckrw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2byzpxncd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2puternnt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxhxvwu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjiqpbe.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2toxucwvk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2qlniaqfu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2itzhiekd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xagoaaxu.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2veoxayki.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfgtzok.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsopcdd.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcsmrly.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnbojex.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jolrdoge.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvngvto.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvqtvll.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mipprine.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmcfvet.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgphogyx.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrxkiwb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqndnszd.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lyifciyf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrsagjn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyvrosn.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2oowughng.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2obcwatyl.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mctafkku.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2lsektqef.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lxludmna.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2couhceel.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2pizyivdi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnwutrx.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwsacxx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zczzguug.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxrygfz.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2vekvegiw.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2csxunphi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbuaijdm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcukqff.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnzviil.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ctztzgwc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2itlrplzs.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2attzvuno.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aejcepya.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2uvthxegd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqcrzif.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvkdbzl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ltezheiw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhgywef.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2udikuvzx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fozynhyc.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ceghmmaa.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dajdeuss.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ofitgyrt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdrryzi.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zyiipqel.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2povonhri.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hivbnklp.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxuuhxu.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpztdbp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2arvzistr.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqiljll.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2voatcfnz.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2eluqmvfb.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqtihmq.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwhtejf.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjwjfes.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2xwuvxkwj.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2uxujsrnj.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ceziggtp.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2iczrqquk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbvtqpy.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2aqaapkbz.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xthkkdnk.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2zojqdvin.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xaatqgqe.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hvynqrov.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2xtstazsx.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kphiihoh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpuqvwcv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2nicjfryb.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2uoujenxe.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtmdrce.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2obbvowuu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsxvklk.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fngcxgmw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2iaijejsx.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwrlwpl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2eezproik.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2snsjxlco.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gttrdoaz.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yaaaccuy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqomplwt.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdyjgry.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gajhgctz.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxkltyy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmfulrb.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnebyft.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2efekoxas.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2paaahyzh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgoxfqp.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwdkcvm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkgnwfd.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxrgnyh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvxrokz.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2dyesqtxq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrbzacs.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wshgnmfm.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cjelaocj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zeirkakh.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2gobulkdb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kscmcbtc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2htarqoan.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxksktf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ixljfffx.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2hbiesxwm.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2obrhkkjr.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2teadeycm.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ombazeqy.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2uojqvlev.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqyhwok.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbdxzgo.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwodype.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2rkajnalx.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmgzcdr.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2msnummgp.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbjkdsp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiogzuxa.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2topphyhj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wkslhnae.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwjxvmh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvvdncs.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2orftgegy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dfddjxng.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2llvanqys.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2biglbkag.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgqklpv.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2mvsaycjq.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2saewizfb.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pajxddbj.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhojwiyh.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsrlkgy.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2thohpblc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqckdsf.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwewlvf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnrvqlh.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsvvilv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcpufiz.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lewoympr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2abukwvii.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rkunowyd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uraeowho.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnszirb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqmugmh.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwfyfvw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uuskmugn.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2djchrdon.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjvyaxq.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2jbareeuy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2khiweafs.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lulxqsgb.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lqloagrq.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2mabmzbbl.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ulywzkce.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2itrfzbma.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dhctpggr.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqblwud.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iuolynas.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2wldulscw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nudyzepg.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pgargfhd.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2drjtwmbd.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdrstae.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2pvivlyyn.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfhrcrt.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzxkoao.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ioaidose.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bujryzgy.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvelfie.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbginoe.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwiqjix.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvmfkha.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjkabcm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btefjynv.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjvzxcp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ugljjior.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtjcdeh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qlyttjnv.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2tvatglpj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2isldxpaj.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tztozmji.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdorutn.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tjedvbfm.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxtnqmi.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2cltqsars.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hahrbadz.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2axyxzzoc.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlcuzrx.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2owijkcvk.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tywgwdfd.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wagbuemq.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmscuth.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhjawiu.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jewfkgnk.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsvudfg.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbxowjs.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2prjoqlif.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gswuvqey.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hssiqyxw.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2cbguqcow.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvjrkmn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkxengp.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrxvedi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yafojmgg.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkvifvh.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vudnwobb.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ozulwbhk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrbsjph.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qszemvnf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnjbjyl.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2gchfsrsd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbxbrzj.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2apqwhkwg.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2molbqssg.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2jhypertz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ytngcujc.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2otlkwlxn.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yypxmwbb.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2peqzlseu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpnnsoz.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2molicvhd.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcvwytz.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2urkgljdb.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2txrdobqx.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqbhsrl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtlbcvi.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvnkwgm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2umcstqru.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbfyuib.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2inarbmpd.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjiyohi.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2oqagdrvu.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcfhbaf.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhgtpoi.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dtenwetw.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2curtcacx.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjvmfel.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2saepwhjz.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqseajx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbvqmvp.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cckzswfq.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fhyxtsnq.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzwnqrk.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2piydvddv.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2eqorskbn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxegwoi.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhepsmb.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2curtxxmk.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2haidovrb.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2oeojesjs.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqniwqe.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2afexbezh.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2rnshifrb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbdgrcp.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfcjelp.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2pkofyoat.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ouuszhhw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkaguna.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhqimcg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjxfuzy.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yglwraku.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2tydghbxr.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcgwkpc.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2qpyokjtk.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2vttjadhi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2laixvafw.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2cimlojsl.html


<!-- 参考信息 -->