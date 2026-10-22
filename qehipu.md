代发 wailian999

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2axjqwzax.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwkdbkx.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ghaftgda.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyeehjxi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcddwma.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvvkumw.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2utjdksfk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2lgixqcwf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrenanx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzqieij.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpmrtxq.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsnbtod.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2uumrokxl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2dadyzgkv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2neegsmjq.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2grmfaaja.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwibyai.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2amuhhnvv.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mzeqssda.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2gydjxftf.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bpyjbdem.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2lodtxiqz.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gutoqsoy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvrmmet.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjzacig.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zikojcpy.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uuyjbsss.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjavimx.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdtlchp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdighbnv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqwhvmp.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2umuuwswx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxgekcks.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2batcicdi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nabkdcye.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcytdhe.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sihcotsa.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2zfyaztqw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2njaoqvdp.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fejpzifb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfumnfn.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwphpzb.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2jicjmxwh.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhgqqpf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2bigjirtp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2talcuoyy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqkdsos.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nasnplxa.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2budhstma.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkepcrn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gemikqgn.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2uizadwda.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbbjzij.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2atwncuxo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2vsghgmug.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsyludx.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyiejoi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsxfpos.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyltqda.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpnmgve.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnjytmn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxrboen.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uienusgb.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2esfbkdzv.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkysobk.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2mklwejtq.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcliayo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqevmdj.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2emphfwqe.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkrudux.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpeftey.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqguemwx.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhebgxfe.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2saqlgrwq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvqjget.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkqzckg.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lccthnqr.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2gismdmbf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2firolqmw.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlpizzk.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2enrgromn.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpvxlhu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lumsizey.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkeqkwq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxsjrmj.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vudeyvwv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dainfxjd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2gihjnads.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ivewecjp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2awgnhsre.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ptummmpj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2xqoxnkrh.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jsruuuek.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2akahiebi.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrcfggc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2slfamnjl.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrqgmvo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqzsvou.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnrddrt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tseshgit.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfgsdci.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdatzch.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dxiufmej.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2klnrhpuh.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2pklnqluw.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qomxhilu.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2muiwjvct.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfrswsx.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwbetxk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2nayejgwu.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvqtheb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjeouhsj.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzxwlmo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2nzckkooo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybazdveq.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsgowmw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2obsarpwp.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2etomuuie.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfgwcsk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfoltat.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jvijhoaa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vewatjqz.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2kozbrmdz.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2sckmmirw.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2temqojas.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2xznjysyk.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjegerdz.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqpckuq.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xdngegrp.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdgweru.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2mggfjnmh.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lbuiizox.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzbxsxq.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxrbtii.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtvyhne.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrmudnw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqqoxso.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqmpjwy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hiroyudj.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nisisnle.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zrffcued.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmwflxx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlwbuyz.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzpeoqn.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2kyilpdrc.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bctxioar.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmztcdmj.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vluoxjot.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2lpekapab.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2awnsijtg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcghgzu.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmjllbk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2upcmcszu.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2lltxztcs.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2emgqvvty.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjsfzdc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbyaaft.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2txpspfcj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kkivuome.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2qteftvvt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpfaife.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnebhup.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jfyieaon.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zopsblrw.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqbntwz.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2vyowxbgn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnwmtvl.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvtlexb.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nuazyixl.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2olkseidm.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsgtnwi.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpjlaym.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyukyvf.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tsilxbki.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uqyjrhgb.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrehdor.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgavmzvt.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxrlvxa.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ayppjeix.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtirspj.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgcmmnw.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2jzceaiqi.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjgxhzj.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sivwpese.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wehrepjr.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsimprx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2cefoyfhl.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfzzcag.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njchsguz.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jamjkpuj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbyxmea.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgvurdh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2icelhieu.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2uuisvpnb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrigxcz.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhjkyqw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2cqugrxee.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbtheui.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2onbyglkp.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2swfrgnwi.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsvlktp.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2gfazfrfj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hupbjscj.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kwogrfnu.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2awvicjvy.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wubxavdr.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxxyctu.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2eszwcgpv.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlfzufw.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrdoval.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ekktfphl.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nchzdrak.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tupyurje.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2clitqzjt.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2svgmaduo.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2awadiwjg.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2taxkvsoc.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2pqshgasv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsbmmyc.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2siwzjaef.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2woggakku.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wyafmxzh.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rtukpmfo.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbomvib.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jbthzioh.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdofwwf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hykzxxed.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2wshnouas.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ecperkrn.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhlcvvc.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gocqqegu.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhbeyey.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2knzgpkuc.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2krsuqacn.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nozmuiyc.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2uidobvqb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2usyhsqjx.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gsaabxhp.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2mirdpolj.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvtisfs.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnwabkj.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhyhjrm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2feefbtfm.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pcroswyb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tbipamgk.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbdnlfs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrzkbje.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hseyundo.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcdmrtz.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bzocsmza.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2xezejhqg.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhtbfso.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbmyvpd.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2veaeqnbh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxteppf.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2pguinluu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2gleziytj.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhzpjwi.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ooghhncd.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2vexikfnk.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2hafkvjkd.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgkesde.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2frryewzx.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwirrkv.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2brqaysaj.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2akifbpzt.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2kpogjegy.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2szzmynlm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2uybubkuj.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2zztwvxcr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yenhrfvf.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzogeqw.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ypijgzqx.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqldyyg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjvugrq.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2umjusdao.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdrxgum.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dyiuwyad.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2huslclys.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2rykzjfst.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkniilo.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbvobwx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxjoxay.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2zleqxqvj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2klkcyfab.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2totoocfd.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2tvewnxam.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2arjgrmlg.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfkqubp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fgowovyw.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2upbsvhps.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2klrsshsk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhyvnrz.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mlskmbih.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2uejwilqf.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xschinpn.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2juxhtfva.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtdkflk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmqlrhq.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nluwdxmr.html


<!-- 参考信息 -->