代发 wailian999

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqgucip.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kakpcctc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2axanifiz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfuxjlm.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhowydj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdgdiot.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2joahrzoq.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2harqetkp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2opajnhxv.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucktaezv.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkmqfvy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgxtvgs.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rivdbbml.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2flmtkajs.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nmuiooam.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aeercyxq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2xoraduja.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2knvgvtan.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbjxtwk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2uamfpxkc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hubpuqkn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2njimuoao.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjxptno.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjajlcj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2hmblkwek.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2hivbropk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2anjtwzin.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2luykzlpi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnflhbg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlaxfxqm.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwcavev.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukueucnv.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbhrepq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjelxgrh.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzcvywt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fotwbmpz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rerauepz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgledwlm.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkbqmky.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2goibyhws.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhuxrsd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ispfkfuy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrubztpp.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2shznhmqd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2flnmfmwu.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2eurkfpmz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mjykeavy.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvziiey.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2weropxnu.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2svpakkzv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkrflkr.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ebomagqc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2goeuvqap.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2yfoxtlkx.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbwyvps.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2egiasvqu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2chtetnha.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmxjfan.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsdkrmi.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrkmhhi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2owmbdarr.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2izheblbl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptonxrgf.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2laomgjma.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2czydblcg.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwmfufm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2qteftphd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyzhgob.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xaesulxl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybobggrr.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2pckuhbqv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyzjwlj.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2swgdsnsd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbkyesd.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwgcmtk.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2tududygp.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2khefnfsh.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2scumnfin.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jyybhfnk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2uubxmjpg.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrowoij.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2whrrocca.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpklftg.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpsczif.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ostcydml.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2klptwyqs.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpfwivk.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2movrtabs.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2olwduxcv.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2eidkydpt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ysyjsdds.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzzbqtx.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ueebwciz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2qexsbnqi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vkubcemj.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gawstwzr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ernekrfq.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kfetynoa.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjiivtx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2cowdxsib.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqjiumw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkhygry.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2fncevlpl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2inbpqxie.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2irkjenhu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2rjexndfg.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lrudbgaf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrhuont.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2jrupwkzb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2weipvczv.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vsujdohg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnujpsfw.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lehwmpsh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2txcaflab.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhmyekx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sghbpqrv.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2raoqsdoq.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fipgltgr.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlfhxfq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2aihisvzk.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwhqueb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkoewsk.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtvkfhc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2txyvywfk.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2bwuqtzmv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqkfwig.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojubxuvt.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bbokkngv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mphaifoy.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2rprnwphm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2yilxddnw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vgscgknb.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qaabdmnf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bhriolzf.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vowkfrwf.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfzqtge.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2zjspvwim.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2lggbrndo.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2chpoisxq.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgisuhp.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2hipwfzfh.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2olbtjucs.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhvjpga.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2tucdzytr.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2awmoiyqu.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rodidgml.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmeqftlz.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxmbwht.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjjidrg.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpbgzdw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfdqsay.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ahksjpzn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pdyjzskx.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2loerfxdi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhwsstv.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjlllkr.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2exwaszlz.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jssxtdau.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqaskys.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcqjxzn.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2sbozvsem.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzsomfz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgstfna.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gryfszot.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2covzvmas.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqsfowf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxabxdq.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tambzhxg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxxlbdi.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsrlajd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hobdvbnf.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfqksrk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2owgqqdlj.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhcgkeg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bumufspg.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2eeitntep.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnymmzm.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqfuxkb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxxfwrr.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cfufpwhp.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rekpwmdx.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jioqxkjl.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjwjtve.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2frgawsqe.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrvhkmr.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cucnovhd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzeurcs.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2dsudkykn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2buwobuug.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2efnnahpb.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzyehku.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcmvuxb.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2riyzahqm.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2oqszhujs.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ydespevy.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jeuomehv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwzrmpj.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vvojhawx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbckdez.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpfowei.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzfzlob.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2chaqkomz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdomenov.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlirckm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ivckdrda.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ucszmcsf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2uddorxwp.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgacwtq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2onwsikrh.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2llyejzxd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2igazhhoh.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkxmfaw.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgdkxlt.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwrtsgr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfhtxeo.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2yplnolci.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvzzzpr.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wonbllss.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyiwbhl.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qofmihgv.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjxghsh.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2etefebqb.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kelvmkiv.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtsxdtm.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lmanccen.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rszqavoq.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wftbohgc.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyrwtkc.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2vxuqoful.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjnnusm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2alsmelnm.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oabojakm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2scwznrco.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpvoeay.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mnsbchxh.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2inuexrdt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2fjngfrtc.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyoufdk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2krjayqps.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2qfovyyrv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrwdgyq.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmiccxh.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxshfug.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dszvjrkq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fvikdwez.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zaishjyw.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pccmzuka.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2modfjbrm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2apwzjpip.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2csbaoeso.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlwpofe.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxhdwsx.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwzwbaq.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2irywqcat.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2lckzwzmc.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhrzmvi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2skfpkwza.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqrwqto.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2mkaofipo.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2pudguudm.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2whveopsz.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gqyuqeqq.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2lblezytw.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqiqpku.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2wumtcrew.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vkatrqwc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdemsiow.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvsaxfp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqcmlmr.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtqafhk.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbksofx.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2csiwbhjm.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2jaamqusm.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvhugoy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ieysjdqj.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbiwkhk.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2aezmykpq.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2gznxbqce.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2edtpunce.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2khtqwbzc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnetcsz.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2vqivqedi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmrompm.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zfthoafh.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2cunexhqa.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2vopyskgg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvnxdro.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcwyzdb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2tzngmdri.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2elkoqphl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2eydurpol.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2wsimmnfv.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2wqaazbfc.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2srusfsck.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vqeudxfu.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhfoxab.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuzdfrr.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkzvwpm.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2firrvaoh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eoyxmobv.html


<!-- 参考信息 -->