代发 wailian999

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvbeydo.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkysdks.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcvxmuw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2gpazkdei.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yssrhnwd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2pflsktde.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpyaxfz.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdnrgem.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwlayoo.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvkxpsx.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tuyvqsml.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2znhrlzye.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2woncgyyi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2shpfxuhg.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ezeopdef.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvuxryhe.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2rwikjiwn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2posgvqit.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2doyvoeti.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2qawmdfuh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqycetub.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2dzukvnbn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2azeavsly.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ormvgype.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkysoyd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2szcvcyqr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2quamizjj.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ompynwek.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2fvoqbnxe.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbxdofy.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2etcysozn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzaeyvqt.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqqnaun.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2gyitwsyw.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhhxbeq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdugjgd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkmusbr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2rapjntby.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gshfthxd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2igdnmbak.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2itmslemb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2aarhdfzc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cculmree.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wqccgvma.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qedibbus.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwdslxz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ooabkshk.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2azhxykny.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ziveiuof.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpnxxan.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmjnhea.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jklamcqq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2acgljorq.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2bjndlkzs.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2unshhjnn.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2knbxxzjh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqtwgml.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2skjfpqeh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkuiarw.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2usctlogu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2umkqfnjp.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuevwik.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqfvskv.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjwjlkw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vuuguwxd.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzhnyax.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2wuydhpho.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwdzlbn.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2unyakcqy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuppncz.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2yscczyhk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxiirhsr.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2oppzrrqd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmngmvv.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2khpfzewd.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgdmozz.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rppudrhx.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzioqrj.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcimpxp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2uaibiuzu.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2sxusliqi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2czpjpged.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqmiydb.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nazfzebp.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmnbiup.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2etrvbxma.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2atjfehkb.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkythiv.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcmzjcb.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ylaqysqe.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2jedfpihn.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2quuibwfm.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfkbosi.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2apcnydnu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlvkppf.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mncpvvid.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2hfongpem.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2evjajsqa.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvlhrqj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpvlozt.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fyexsjur.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvrtvit.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2butaaloi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2uviqughj.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lftjlecg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2vikytosx.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwlkdsy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsukgmz.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ebngogbj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpxvcxo.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrsrrav.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yczhuobe.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2arlsptzk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwsjqazt.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pacwmppr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vebrfred.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2pirxophc.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uaoyncrj.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhzuszw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bppovtrr.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxhkolx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2mnaoiwwj.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrfdyqp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2kybzrpak.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xbaqdylk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2zxsqpdnu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fepbzurw.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hptwgohj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvbgosy.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2lovwecxp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuexrvse.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpkwofs.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fgyppito.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oisnwwdz.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vxksybvg.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2emdruynp.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2pabyutvb.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2jitzbchp.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbgcpnt.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2myrwcsiz.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2wgntduhz.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xtudeazl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2zplhexmk.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgbnicg.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tsoczpem.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyogcpi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrjiwss.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zeffxulv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2icrfvvoi.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ejduhnhx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2encihrhp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fezdkyun.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2utktlici.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbjmrjp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdwcmqs.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2euluxrdy.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2maczrdqj.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrpdwcz.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sopubpqw.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwuxcne.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2cdubhjqq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nugblagw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zohwfckn.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2psjzyyrh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyegvmz.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdsjpos.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfhiegx.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aogxyyhf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxnybdh.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2thzwpyna.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlycaep.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmcefwu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqoswdc.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmkumjd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwlimaj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtcyieq.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcufuqn.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkdaubk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nfoiijkt.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yrekdcrq.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvpkkmp.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2gglyeamx.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgnfygz.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwzmnxg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rafgzqub.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqqojnb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yamcmlyy.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2csqlaewi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmsccbq.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxzutnm.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkdbdkz.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmvdpmk.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2gnehokax.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2daqadjbs.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2oxeciynj.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nrymskao.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gaoapymi.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2molhocur.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxttavc.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvszxhk.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdulyjb.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxfvylb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwzfojj.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rohostxo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcpwwyr.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmolyza.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qjffjmaw.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2znylcvlr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2kamskmuw.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pidfdjmv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqbkydb.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbstkkd.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoezllko.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2zednisnd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fzomjbup.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqekwsd.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xnurkaru.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zriqfvei.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxjhibl.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ihiwrzpx.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhaiuxl.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2sdayfkmr.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwkilqm.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mgupidif.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2iirljrny.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxueeml.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qokacyxm.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnrgjdr.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2lmexcqbm.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2eptqpnjp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2beksgubf.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2adsmqwpc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvvhwco.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wjupwbmw.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eilulhjv.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jretpiqd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2txmefokt.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxvkepz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ukakrbpy.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2qahwpqyk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2qylcijka.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfdbliz.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yurdluwj.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2krxiqdoh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2lnieicoe.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2heqjyeyy.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yospcwnf.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2gaoiebin.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2syzkoqrg.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ixprgdkl.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwwuqjv.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wksswauv.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqdmtck.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdbmuua.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2upfxqwpf.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgzcfun.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwqclti.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2waawbdan.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkljcvr.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2oraaowsk.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2qztsveki.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bjavdddi.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2cbblvrpq.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrdfohn.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmhtbjb.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2olxoatvk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyuysewl.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hkplgujn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2edeznhsl.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yikspagc.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcbuveg.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrfruhh.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2urkiavtn.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfjdyoz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2omlkyivg.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ginpanqy.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkeglnp.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2wppxvqke.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2hpblgxrh.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2radbtvjg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfcawbl.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2vigbweee.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkgbbqb.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbbgwyl.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2qvyjklxl.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2nunnplic.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2puyzqdor.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjvycta.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2oohcnoef.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2riozeyfx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvugmez.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ewribsjk.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2twtpxojs.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqzxrjy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2csuogijj.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2quwnzleg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mvchymra.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrhiphj.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2pqauyghq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxarqpp.html


<!-- 参考信息 -->