代发 wailian999

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbbshjs.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lukjjvod.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjzzjki.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2whucfcgm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpeahiof.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbcysmw.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxgipiz.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxpjvzv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2olfqncoq.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzettvc.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmsizzy.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xblqjxuc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxjxsiz.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjeixps.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2smagigfy.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgvkkzm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfdlfaq.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qthocnsq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tflciaql.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jshamqjg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbskcby.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjmlhoz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmqlgqy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnhukzg.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qmulmeqp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2yurtkmfa.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkbzoyd.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2xchjdeoy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2wnflkzeo.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2degkeict.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2svxwrkrg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvoazec.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhduxiu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxitqkyh.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjfihvv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqaqqlex.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2syxcsshd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2irpsxnfc.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwfiwkh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxayxis.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjpplzo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgxrjzi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsbblkl.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcqlkcv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2jlacysvm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfszxhc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2devjkaia.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2exezadhk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2yocufjmv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhaetwo.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2khgayhvn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2upiivdob.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzznrtg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlefqygc.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2acacvpxd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2oophipre.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcxgjeh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyayrdho.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iuurxraf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2giauqiox.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvkjbbr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjjdism.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zayjtmkx.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2puzsbzif.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2limxzggz.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsplysi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2emjiqfml.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zawruryl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kifwgwam.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlujcms.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvngiubh.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbzhmvj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2elseqoox.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2kygjgpmj.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqjyivt.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmekkxk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2oljqcgch.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnzdlik.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwpzbdo.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kvetsjrm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkdbdwj.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnfbeyy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtgahlo.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjnpigc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sukvwwch.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2anyheytn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkwbuai.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjhoizg.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2nwumznbj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2llnrlivm.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjrmilh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gssjrheh.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yfceebai.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2defgfhxa.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2duxsntuk.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzyyeyc.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vftascpz.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovggbjuj.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpqwcxp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2triogibv.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzqaizr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjdtvgn.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsymbfn.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmapdrmw.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2abkljdvu.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqpoiih.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqndayd.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2madwfepp.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uokepydo.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2trvkbjjo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnfowso.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cglrhgur.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2crhlikgk.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpozxqg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2btwnxfxe.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjxjwuc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlesjhw.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmscysp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbjesoa.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2dxagxqqg.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2oplkprmg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbooqgh.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2rawpjeqb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjmuckm.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvwewmq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvnbfpu.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtoghvm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2smgtyexj.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqxoezc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2akniiphn.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2csaajoov.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgzxoly.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hprscndy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vklbkcem.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xaddesdv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmhuhkx.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2joawlmqf.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzltblzt.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2djaqtvhh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwvwttp.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnbpjqn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ajautkyk.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvdwewz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2kywgrumb.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2jevhrnug.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ummlliup.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxyjvrz.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqsfxfn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fssnargn.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkvzfqv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxzocxk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqklpou.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcpxtbg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mtifjfyu.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqtqoge.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2risoyrnb.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2chtfrsjq.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsyllyk.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2telofews.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wtewtnni.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtngape.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2adthbwro.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzwxnpl.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmtlfyw.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfjzkmw.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2msunjtsd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmavhdup.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjzufmv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2efdhvpbr.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kgblmpkg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bnledqti.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ojeulnks.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2scmzrxxn.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2skashenw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2knuriikh.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jwugtejk.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2aujibfft.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpvyzrl.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkulfsiz.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2frkkxfmo.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2jslydgch.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2efszyeaa.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2usbvayej.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxxjjlb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2huliithm.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlshmft.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ysngaonb.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2etsbggjk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrtmtfi.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxokfel.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nnezhqch.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2brmmomzy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zaiirprc.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ffztnnzz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmbksqn.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lgenmwpu.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wkscmvqm.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2zptkfzly.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzatujbe.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsnadsl.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2puhxkxwu.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2uutxhqyb.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrnfetd.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xiabvdyi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsozmdr.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxaiwnv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xqofmjsg.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2mirlclfk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2namnnpyx.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pxschqki.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpjpaia.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2lsozujod.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2grdbafgc.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2sttljhnu.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpzvsez.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2spnishcn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjovunh.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hruxbwns.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2yefpkbca.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpjtdqq.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aheylzrv.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsigqug.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyagatcn.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzsszmt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2takydlne.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2tplepvdr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrlkjnu.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2stckhhtf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmuasja.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqqficz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2eiuxpnpy.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2flwbscyg.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bczhzevs.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmxhdtn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2igxwijhn.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kglzfrig.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2awnftjvi.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kioejqny.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2aeuoysdt.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2drhdpgpk.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ausssphf.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2xrelkcqa.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nimouxtn.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2juvlgrbi.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrftgre.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2iavjozxc.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kutjmujy.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtktjgy.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2egedyjgk.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwkjnqk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkttmcc.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxzroib.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2utglsxxm.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mspompsz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzmadfc.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iqsxzwak.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2mwowrctn.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ptudhsld.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cushtlvj.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrbmtkn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2crjbqecr.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2orcsjcqc.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rdikdhpo.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjcnhyz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2izrmhmlx.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgupgbd.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2norjaony.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgpdlps.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2krvxodbr.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jezhzjyk.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdtlsyb.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2aewpkcrw.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ppetwycp.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eshxfcaa.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxpssay.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnbbpwf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfkiuec.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqqhota.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2egncifub.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2akyrwgqt.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtjkxow.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhsplno.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2tljhrtrc.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2iyftpdep.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2gtednceo.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkmqebk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfioczfy.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zkekilnx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvliuam.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcremag.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yxztuwmt.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2szdgvbtp.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2fivckfja.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2arzfiwsf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lznaqqlv.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdbtfrp.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2lpedaqro.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnethsq.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmjqhms.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjmzcpo.html


<!-- 参考信息 -->