代发 wailian999

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmkhtld.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgvjild.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhxpamw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjcwrss.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wjybarxa.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhyzjwi.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrucwbk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qixvqcgw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmztpdn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpvsbfe.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmkuwlz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxbiemo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxixwdm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkiyaxq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2bopkdlhw.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2phpeofhg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2recklkzk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2qkefddrd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvybinxh.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2enhjbdek.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2fdsfsvlp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdfgkbd.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tinvvplt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2bleskxvj.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmgoipc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsshozx.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ngifbkad.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2omytxjxt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2onzjgeaj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2sejrppmx.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtjsirx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2uunaolmh.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nythidic.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqrtktt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpttyvsz.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vofoppqw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2plzozvkv.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnhkcdf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fqudwvpo.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nvsjyomc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zprzaiiz.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2emenjlzs.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hovphthj.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkvkgnh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2wuuiljrp.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhjcyvq.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnkpaxi.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2oatgnblo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhesliup.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ticbgavk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqlmxtb.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hakrnwow.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttamiyzf.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgaakay.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouerepjm.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2hpomlnie.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wggdcrpe.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfbwwcy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2wnawtuke.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pooqpnhe.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2asonoilg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gigcpmli.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbjhtrf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2albnadvh.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yunnnopf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgmtvgx.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lguwzgub.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhrweed.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbgvpei.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwdgosv.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bzduwctj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqgucdn.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxypvpb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2uycplwuc.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhoeteq.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrqmhti.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnafulr.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2yaoqbsgf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2qciwovna.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2jzakwmbb.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksekwsvy.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2geoeqdrj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2klkdeakl.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bljihndx.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlppiepp.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2sovuttmj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdmowwr.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jyumofgz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2qxucssvz.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2czyaqgok.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgpapyi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2klhcljmk.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2phstnyjd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2abrjbmvb.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2bkyjuvpi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2iihktiaq.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwofyqv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfbphuf.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2njqgezvq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfpnwyr.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfpqkkh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nupdtdlg.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2amvhyzif.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjqfwtxy.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzikmaw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmqvtzj.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2arrtuooq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdqzeqs.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmraejr.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zthvqgkc.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzdokar.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrptrak.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2uoekhqjq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2klddrzhp.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lntacctc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwanyix.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2cepcldow.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwozcyh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbisilua.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pazhejsn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2goehlsbl.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2xykiudoz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2okhhrqwo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkzsola.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2iiseglzd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2egqznznn.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhveyat.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2obcaeula.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2jncncbmq.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2fvapannq.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2yptisoob.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hyksijqe.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2fcscrlgl.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjdpmmc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2uoavgtlf.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2glfcxqnm.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqikixh.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gascdvjb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxkdktv.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbokxkx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtgmzjz.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpglghb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2iaiypvzh.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdbwxkr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvntqsx.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2olbflxhw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2czwhwjoq.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwbjzsg.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmqxefx.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2opdcwifw.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvtmeul.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcgdify.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsajjox.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mknaknol.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tbivjdsf.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwtzxcq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nufcltnz.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmndcmu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgotujg.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmdweiq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lresafss.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2htjkbroy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2umayajxl.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2iqoefxrx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmmidbl.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qxukaqyp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhbalvf.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2heqakdjb.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbceyar.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2irrahogb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nmksetbo.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xaibrgqg.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcrhfeo.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jfefuvcp.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvbstjr.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdoowbo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzzlmtc.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lckthfgl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xergeivc.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2pizfnhab.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sujoegah.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ydyexrlg.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2nnsshmlh.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2rcshxinn.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2reskffnl.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2bcigspgy.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ygetuzir.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnbbprr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmvmckt.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvjview.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqlfuas.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbgysxc.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glyovysc.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkcelyg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlqpevb.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2urwydsib.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqfmddy.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2cdraidfm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zowvkrfa.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlhmnop.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwbrwsm.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2exzgedoy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcmpwic.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nitufrup.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aitkvblj.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkjmfar.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2aynaqdks.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2svygdocy.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyudnsb.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqpybut.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwovbxk.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdiegdh.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdepmlh.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2xnacbulr.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2snduzukg.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pkyyrxav.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwrmuxv.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tzekbbub.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2chyxwlxo.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kqstvvfx.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2elyomhvr.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2dywbdgwv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwecsiq.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2udunfnxi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2roszozel.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zumqcora.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ryotgtcb.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbbmspn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vurzadna.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ncuejeat.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zocakfyo.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2erjgygpn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2fqravbot.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqwetxa.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvuuizs.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ckindndt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcirvlv.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxtowgp.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pxozuzhm.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2acitqsku.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqtbbwo.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2svxccryj.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbiveng.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfqdzhl.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2pewfrynt.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcfxiai.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2fywwurbj.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2exwttbxt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdpjxzj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wkntmdwy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ecffmzhe.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdwvtnv.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2bddkcjih.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jexjwexw.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhsoony.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfciole.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2roozdycj.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2iumowiey.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynoaugws.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2uczkyriq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2jchhdmjk.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vomhmiwi.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmnnwnf.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2xuabvdae.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcfsiel.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2vfeentpe.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzsaifa.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxnyrje.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqnznmx.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2bbebaomu.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjndope.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tisnihil.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbppxpf.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgbuahv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yyceqqvm.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2aoksysrw.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrtklol.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2dpiylqor.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xcggzsho.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kynydsva.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2udwtqbee.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bxusfmjr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2epqmdlno.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ramgqqxi.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2obvomhxc.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2howlxabq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yocixszd.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxnxwsl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2crtjmfsa.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2erwtruel.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2udpwxiag.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqnkpge.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqylxdf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxkvvfz.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ewuunobv.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2waohoihy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drihqlsj.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjrytjq.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lswdykez.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nklwgxwk.html


<!-- 参考信息 -->