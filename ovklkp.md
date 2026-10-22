代发 wailian999

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyldyrxa.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhtiwgz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hthsuusd.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsjribt.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpjbigo.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2egsopnxa.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnuljmq.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqcvrpe.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sobwihuz.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wjiokdkv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvoquyca.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmqrdto.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgzgqip.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzdqyff.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2crsbjotf.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwjmqtn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ifforgod.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhburlg.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrvbwlf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2txxhustf.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjajmrc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2klcrwksu.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2timhhjrw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkpwxzd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmoewqr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2urmqnbum.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjxotrv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2lxloxsde.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kozdisud.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2epmdfgue.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2pijfmoeq.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbczgoz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2iypudctz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmrqulo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrmvmhr.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xjazkcga.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2eabnpvwj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2iowkitxp.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vspxbfva.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2zojwnxap.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lsugnumd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvemudzy.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wyiailxd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsbdsir.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uusypgjc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxodweqt.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2olzwmqsn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlpravx.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gmagktky.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncekcvbf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcysdit.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2yznabjid.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqsnpis.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dniofesb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2epzrbbpa.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjghkjd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjiynqb.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2wsofeicm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dijizuiu.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxufkqo.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ezelrmsj.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2icmzsmgi.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2pppquics.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2iodkvphe.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjvlgxs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwnaqjw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2cotjiyxv.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kosxbjpc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqebypfp.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpqrcot.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmlouwa.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ifneqofk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrjmxnz.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dirmcyme.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzxllpu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxintnas.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vctjbgoe.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnmionv.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ieynbccw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vivbmiml.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2psawenrz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrkgnkv.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hojuouvf.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2enouxfji.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nslopbxl.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtetvjl.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qqaynpui.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdolftuc.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhfvhfx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2xiuomlmb.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2heroxjuy.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qckfmzff.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zblgccau.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2nehdpjqd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2fpewznkh.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtvxsge.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gaotulfw.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcfsjdq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2gxajeipe.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tjoezglc.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhsgssy.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2kelqcywj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnvbsiu.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2blcpmctx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqhlnah.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cchflfbf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpteezz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2sfuyvpbl.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2youamvpf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrtoizm.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2nulcitua.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqrpupv.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zshovbcc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2mnloyjbe.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnidcmy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2elkwjijo.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2luyenffh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgsbspo.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrqwppv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfivhyj.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tympnqqy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxlonaw.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mfovrkio.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjlbdoy.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2hctuwjep.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkzqhmd.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2xevgjinu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrksoug.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2smuqunaj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2qnubevoo.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuxgbem.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfbksst.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrzumzp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkmjjih.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2blqndfto.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqmjksu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzfadmi.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhcyqcc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcsttfm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmkvppa.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpqhhsf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lpczbptf.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhaazfb.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2guprflta.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhvtrkc.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxplviw.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwpvtyu.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnfpmud.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhhycoq.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwlvhrk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkuuxro.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ekntoffx.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ttatyaek.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sruwjden.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibolhtgf.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2scbclzsd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rzutnzlb.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpudmtk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bakckaar.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ufstcgqv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2thmpeccv.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqtpilb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2oilwcptb.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2eyswwqlm.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2qvamretv.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhknwej.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfxrjjo.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2volllcpc.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2txtshjnq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2icredoez.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2noaguauj.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzfpwot.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpfzmtl.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2aakjenxt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yrieyaxl.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnbtyym.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ihymchtb.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnvholx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xuncvxsm.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2fujrqnmx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqjyiqd.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2paetpzfv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqhovjd.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pxywghfa.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqnghoa.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2owmvxnxj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhiqavf.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fymgwwqy.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqdzmvs.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ehidsjfz.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yzuyxyhr.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jlomcflv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aponmcwl.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzfqjnn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmesafq.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2aarqxozd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdipwns.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtlyoed.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2regyyjkf.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2kagdcahi.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmuylmt.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2eemavyuq.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2htchymxv.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2meauxxwd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrteptv.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhemogg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfefmli.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nobjrfrv.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgnpxqw.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2czcuyjkb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qligibaz.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xazrejpn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2aidyggjm.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxmouva.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzxmwkt.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrnzufm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2czdlondy.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bofdfprl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2biiibpbr.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yycokmeh.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaewowym.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ymopngov.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2eevcdpwa.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2etflhsuu.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zsygrdah.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2skwfzfgj.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdeannm.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mynozgnw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdorfbr.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2pktwdtle.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qauxkhek.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqdmfyk.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxbctur.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxbelvx.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2eixvtrgt.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxhakei.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2hafogjzs.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2prhcxzkc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ockqubzh.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hofqvvhk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zipahuwo.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnnipsl.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqsuppr.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kivozbdp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hetkaewv.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmycmzm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jajgsmji.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgxthmv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbuunzn.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbrddjc.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mzclmhqy.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xbchyozd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2druhswxj.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2haniqmex.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcovjrk.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjvrboq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2sljdovuy.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmxbvwu.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvtmrib.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2udhipdbt.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2wzloiasy.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjakzqr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2pydabkvm.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2armjzrpi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxgrtlw.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2orrhvqwq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bavofvib.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxocizb.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2qjamxasx.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbnxumi.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2shmmmnfv.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cofxcfxv.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2lfahrmej.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dfguqyyz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxxndkt.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rokunlsf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqqjrfg.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ohekextc.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwbiqle.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2rflsafeg.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2nezmazqv.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2wzilbefd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mifgtnud.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2azquksik.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2urhjmcaq.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjtikvd.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrvslwq.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlcuujf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmxzips.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbeikxd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhnbrlv.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gvltjbht.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnasesn.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2fhouoanz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dfuaswmp.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jooclowx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2okoqzszh.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqdhjgg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gmepedvn.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ucimkcbx.html


<!-- 参考信息 -->