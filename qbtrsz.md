代发 wailian999

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2noddcrfd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfnmfki.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ctuxzweu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2obevqzwt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2bvprtspz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2urzkquou.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhlqqbn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcmhlwe.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlypegvg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2qrabxbka.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2azfelbuv.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmobvce.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2jxylanut.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwmhxuy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aatisrwb.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjrilhx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxdlogi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqbrxct.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhgqrcf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykoymyxc.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnaajpl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2afxfarqa.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdszrsq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvrkcxr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gprdgmpx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tskpeywm.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bkucuhcn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndylcaio.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvwlbhi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrgtimp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2axkshmjc.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2nerxvehq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvludmwb.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2berfrwju.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xylwtrjj.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrzfpyd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuppsnsq.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxxicba.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2whbzymhf.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2eogmrfae.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2tenftjir.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2vghnpvpa.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2casighsn.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2apfjoimk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2olerygfi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zzktegsu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibflcqkz.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2amzmcraf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qevhgajt.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gumskzst.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnfttcj.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2yoheuzpe.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxiecmfr.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xouutzmb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcgybxu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfedffil.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zhriwesx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdivbqym.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbtakcr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrlabon.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ijctnzlu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2xurzircl.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrbxmfx.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2xidazlxs.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqobqvy.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2akdacxho.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2udhvcmbh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqknmgiu.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2unaibvqv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgtscqt.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfburer.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2obvdzoro.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsoesns.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2olwfdiju.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2xgahyatw.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvsbfro.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sseetclv.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2dznkhwld.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2lulqufnt.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xliiefbr.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpjohpb.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2uylggria.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2kstcppjy.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxmcfwb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2pyudemjk.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfmbwms.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2skhwrjxu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2jerhhown.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2yxndyhjk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkdfujb.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxlcmas.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2autiwhcj.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2svsnknpx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvgkthz.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwochzz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2onvnimvb.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2euwkfoog.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsyeswn.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2edctqffz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jstyzhpw.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcdrgtn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2obetghsj.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkztpkd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzisuatp.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjylvom.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfmhipv.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqnafcu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwjhvpn.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gnuceqrr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvdkeqx.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oomfzjmm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyoaril.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdutpsti.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2exmhktdc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtltsnr.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvyknpi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2denfteuj.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhvazni.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlakptla.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xympketu.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlqjcuc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2txilgryd.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2xexlucjf.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqiutof.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgrydbf.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2jousjabf.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxvlbzb.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mogapxck.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrzfsqz.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfsnihb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2orurhddl.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2gahegceb.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lyuqsnwa.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpwsdzf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htgtokzr.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hlczbdsm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2viwbaadz.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2avsevrgh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrkwihq.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gauluyhg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmlofmk.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjeovix.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jizbvdrb.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkwyglu.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbndgab.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2texifigw.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvptbbca.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2soeocekc.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqxfkil.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxeqphs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrshbag.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2itrygtsa.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2olbnnciy.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2bvuixyhn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ubftiitn.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oeefuqgu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjddtrp.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qivjwqlv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gadbjuzq.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvezgea.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2heniktvr.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2owyyvpgf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpecxaj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vjcvrgio.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdwheyn.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2woesjdtz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2owhlykjf.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wnegxqxj.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wknnvnny.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2orfpkuyp.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtpeqvw.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yjscudwb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwdvrxk.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xeudezwe.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2atxgvmkn.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2jcuzqrkv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnufhcc.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2swwrhxkk.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2njnqszoc.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2sxeowxhx.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2dpptyljm.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2fjktdzvw.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzielov.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yblcpohg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jftchyoh.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzhdptb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqurlmm.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qwumfgaj.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtwzypg.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuyoanu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2weaeheck.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ytquucjg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmpkowr.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2nylelhup.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gesifjkk.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2fokjauwk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2fzknjusf.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vrvsvxzp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ranmogix.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zackccvn.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mklwdwol.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmvtyqf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqpajpz.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vqukqsyw.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2witwuerd.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2spsxpdju.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2osdaokyn.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdhhxua.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2grbdjnev.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2kadinptj.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnxjsok.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwxxjeu.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2txmcnvrb.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2khfrulsp.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vctiazpv.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2cijtfiiy.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2gbufiweh.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rwyocjul.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2wueudxij.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkefoku.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjhsfiv.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2derndkpu.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iojiijos.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dohrprqt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2kuulpwyc.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lkznfghj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnhxbsl.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2mvifizzw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwakpuh.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjyeqxy.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtbbwdy.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vltyuxan.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwymwhh.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkvjnjy.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxuhfvf.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2czuvgroo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2onicbrlp.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qarvbjbv.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvbfrdy.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2sshjfiid.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2heqpmujy.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lvixvmyj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbesnls.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfjyasr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2grfguyor.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2srqkmiwt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcdqjvu.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwwialk.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2baihglfw.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zoodxjtg.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmrtfyb.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxackgs.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrqezrg.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bfczqsnn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxcpxxm.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwgezmy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyhspep.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2eimaxwlu.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2durzxbfx.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2hztvmlqb.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgvbedz.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2udcazlzt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2juhlovsz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2gptiagmf.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpxnlwn.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlsiauh.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2badppryg.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2psagpuez.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2diubaeij.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2titnwmbi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2exaoawgk.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rqlhfpns.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2getofccx.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2uhovwemp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bmekikkh.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnkdifl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcwmkxr.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2efqgzobb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzcqylm.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2qlorcyhq.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2lybyuacw.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdezfxz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lonraqet.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtgnyew.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sufropkl.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2jeuewdej.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuxhnhs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2srvzsvop.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zurjjawi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gasdlhnv.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tbodkwwj.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2orepkgla.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkalugo.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrzrtab.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pixllfcv.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2cejzvbmb.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpxjlxk.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2imlcrapv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2twbycmng.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jzimuesl.html


<!-- 参考信息 -->