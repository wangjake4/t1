代发 wailian999

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnymuaqc.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrggrnf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ystzybqe.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnkwvgb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgyzktyj.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwclacu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxylguui.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2enurrqvv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnnhfqs.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vvldsatu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpsiory.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2vclhxktp.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2layxtaxe.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcuevxck.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ractjagm.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2rzznewry.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2vvaurvsu.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvgwemy.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtxqnjk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2faywbmmh.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tlopzdes.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjatvlfe.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2irrbmiei.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkoobpxr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2vvevrlkr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zidhoivn.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wkiclczi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhekimo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkxnnmm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqpphoj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2zktyzqhc.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yfouwkvc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2qyaswkrn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2fqoddyhe.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xykaxeoc.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdgzsyx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2tfklofjx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pctvkkjl.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2epavwrli.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2zaieomfs.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zhglgskm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcphnky.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrftxst.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpymjvq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hdetnjnr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjlnfon.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkqmqjb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnodnrb.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqddbni.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2iltoikme.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hieduaoq.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xucqibji.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmviuebw.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mxotipes.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbdlllv.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bitkwfme.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvqngoa.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvrntyb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2emqoaopc.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdmqldu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfxcnpt.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjnvxhf.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2zigvdges.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2bnskifmj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbhlsms.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lojwbccu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2didiwkdw.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhtddjb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbrlbfd.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fyegccgo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwascgw.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2tygwrnqj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxsokzb.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qspmmwbo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwsvynd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mintzwva.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2umhyvawg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jofyghxc.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2aknnsywt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2frpxutlb.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbtnxmy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2gnekaosf.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wufaamfh.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrundgkt.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kethfnve.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayntmlcz.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjxkowl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbzredg.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2sckdahlp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtrolqq.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2urdyfdza.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2znhvtjjf.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fabnehjx.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2avuipsbb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2usjaxriy.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2jkuxkwrt.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbaytig.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2xyphpzck.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdbmalh.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2frbmwyhw.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2euqivmfr.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2nellpefk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvoxtxp.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2npzxchoz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2lmahrhrh.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqdseyp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfcneke.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2pqarstwp.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfadipx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2befzxhhd.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsvkolc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqpqwtp.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdbainp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2prtbjjyx.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2uyozubtd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2feqriquw.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2dkivpezt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpunabo.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcislrt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2teatxcpl.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zcekdrda.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjjysge.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdtrocm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2myzhipvt.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2uytzcitx.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2icwvepis.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbodelw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmuokvf.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhibpuk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2kyupjiie.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdmonbi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxoinplh.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2seudnabs.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2zgeffvpa.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzekegmc.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2erilshuf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2egjpukan.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2kxctrakb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbktcgiy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nejstnbm.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2orpsgrvl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2epnklwqo.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2abjuqzcn.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2hiiqtnvj.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfbipyo.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2okcctiii.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2sshoaytp.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvbxnrn.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsenpwh.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kmajwugg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbqhzff.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2bklfmfvc.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxafter.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2khhsseri.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwfmvjr.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyqglji.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjxkaok.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dizijhyc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjizpiw.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtrfxei.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dsoooahk.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rywlnqns.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rbovegau.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2tywvegzx.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2cshwuuqu.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hckdzldb.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkrwzzm.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2obuwasux.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2zduulrnl.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2stpkucvh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zghlsifd.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2azaagrnu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbbegjk.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjryzxb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wehmngzp.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwrcltk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qirkktka.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzpwrnj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bfyvbwbr.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2qcufqwbc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gpuueggb.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kasnlfuu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkjidpy.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nvupbcmf.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rfserqow.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2sojmodzm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbaxmab.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtrtzeu.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfqmqzc.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpsyvuf.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2awczhxfv.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zakwkxjt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tbiwnceg.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2icdspmlo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tervrmao.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2tuuoednj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sfyzsrvy.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpvkchy.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2scocjpuv.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2qpniuxmy.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsiaifx.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2cqachnwr.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2rivkobnz.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kxanwuak.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbeqsql.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zunymxqu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpzlyij.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hyaqcvkw.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2juexquro.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjpyyjg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sukqpztc.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2aegjnkrt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2jyflshqx.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzirxio.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlkidbl.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2chfasczx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2qstinazn.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxfqrlw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2alrjgffr.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfvpcoj.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ragoeizz.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2durkdfvr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xibcjufq.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lekefkib.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rzldntob.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2shdwsopt.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2luzlbbxb.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tfguhncw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvlgulc.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2vazdwcij.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rhggwkbr.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2noxyjemh.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dukkslxb.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2idcnsujm.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bunxejju.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2uggbzsif.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfdeiac.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjwzlyy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2taiqtvxq.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhaisqk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iogcubfp.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2awoxqexs.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iripdozk.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2suupjkqm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2heufawfg.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dyunrzus.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wszpzytt.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2zlplktjn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2nobbdtjs.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2veioisdq.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zjozswmk.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhcmgfa.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxnmkhg.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2idqdaqnz.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sabriadw.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2odkqgwtd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvnkqza.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzryydq.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2sslazvtj.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2moprteso.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcqakqx.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmuesbi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2nxijsdcx.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzupynd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qsivjkbm.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hmitmirq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ebygache.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jfsaaxvd.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2njlndlyw.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpoavqy.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2telqfxhr.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2oujivfka.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvlgbof.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kjecinbq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ronhtvsb.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zqaenaxh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrqklpf.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2aomzjqrq.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpoumid.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2cwiimqob.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvyefyw.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2wchisomu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2payuyyal.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2eduibcal.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrzgagb.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2axkzluct.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhrzbhv.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvzicpz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2gemkyqvu.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ealnporj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrrgcue.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wmubrleh.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqzmwmy.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ziuqvkqp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlhhiul.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xmsuimdt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2vtuaxmqh.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnynhnz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2yehbdbmt.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2whcwgbkl.html


<!-- 参考信息 -->