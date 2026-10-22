代发 wailian999

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhbcpcr.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqmtzrb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbyrsnai.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2euwdzyav.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmoefyj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2npqnosze.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ovebjbmp.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkkyjlr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmomoso.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhewumiz.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2epelczfo.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uttcmssa.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fvaxahsa.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjovpisc.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2forqqiii.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilttcrnz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsatvkh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrfhwuu.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rgifeuki.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2cqphxsqg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvfaxrk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2eizbnosu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcvales.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlsrwfp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2higibsug.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2pgabefjv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvvaxaf.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkddpas.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2kehsxkjs.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2agfndpyz.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2btqecbox.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmlzftw.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gwosnvia.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2dductvqv.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nbobarlx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2swtoyobq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bozksiny.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcxhvck.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mlymcuii.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2pipprscb.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mznebmdi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmfsuiy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmosgoqd.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2nfktnaau.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2menhfxfs.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ikarmjxd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmevjwp.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnsdprq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2smdtqlmx.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2duyxsjok.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnisddoq.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxdctwy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnnnthw.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnkvdai.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2wykaprjz.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ohurnyuw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzgwqob.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2yutbxkhw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tptptmis.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbeapeb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbijlgh.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdlhbaj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlkfcay.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2drvxkvyc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2klvhpcms.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dnurnsjz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbkamxh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vywpmlsa.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hzetmheq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vigqkpme.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2zuccpikq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsrqfmx.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxteusf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvkkysv.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qkibrdua.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxfxdlx.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xsitgusr.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2jiclepdo.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjiuikf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlehiny.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2hdakylcm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyqioip.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmhihhg.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgxgupg.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2caclfmlm.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsbvbzv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2pspjemwv.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxwnliv.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2osqqqvus.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2vznpaszv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsmfhnp.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxvoiuq.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwllsvjc.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2powpcdlo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrxuiai.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tidnpinb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsdprrf.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mxenrmjr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tufwpood.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2clwaooxw.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2trwczzle.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqtxlob.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2sezvmmbz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtavyqk.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqwrndl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2yopwbzfo.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wnthzwqm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2hcthnakz.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsntzgh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsucbiq.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yycxuntk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhsrbsl.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqcnohs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwosoxs.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqwgwms.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2okmrjmpy.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2eahkdotf.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdandzk.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwphbpd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2isabhbth.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2quxgzvla.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvyllyj.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrknyxj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrwcsps.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rkozvldh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2tshmwdvp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrhpdvi.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2avcnuzqq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2cqapnrzc.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2chulqiwk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlqyyqo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eoiqmxgp.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zkoldovb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnveitb.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtlxroc.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2angbtjue.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhvskuf.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ocacdqjs.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdhmafd.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhwowhv.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2hjryessq.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aodiuwly.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhyqxpp.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2efrvmwtf.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkkqmus.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqvufbd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbkypdo.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdxyhlx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhamqtz.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrxppoe.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jukofsoz.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlnhrqd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dcslyags.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqwoqez.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zdblfcal.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2sknjptgn.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2sjptzhti.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2txmhrohw.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2duaodonx.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqtqryf.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzsjhui.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdlnwxp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcxrooq.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfydhcn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jsluxkfc.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzbwefb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bupqcozl.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxmdiul.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2blegqqcr.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxdktgn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhftkwn.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2mhppktac.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnzzjfn.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxgkldx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uchcasis.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnkhbee.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgzrojl.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2irfxxlhe.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjjbrqw.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jweruytl.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oxewqrzt.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2laltmkir.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxouucj.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fouhlcvj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzxtbbm.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2oadwjxlh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcjghbf.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxfaaiw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gapecwrs.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqlvyhq.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2iznebrrh.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2beuecanx.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcufkvn.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhxvvpl.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnefnfi.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ylccbibz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwwtdjs.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtftbtx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkuopto.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnienqj.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tezhgxlo.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjuwuta.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htvgqygm.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvukaxv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2egwjiaad.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2esynqemj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ffejevxb.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmproxs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijifwume.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbyoehs.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrgjprk.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgesyft.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfoholcl.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ornpqmde.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2stvipdps.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwrkkvj.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjcckah.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pdaaexku.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hoczuxnb.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2htptcyyo.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2umaevios.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2tphwfgif.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgkcsvm.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfixwms.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xiiebtqf.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhwhgbl.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrtlgml.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmwvyuc.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2kehxspwd.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hczuphkl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2llqwheej.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwzhjmq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2shndhuaa.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2uycbomwv.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hnptyadg.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oonpzdrh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ljluberd.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhcshfg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nljapkxt.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2xofjasmw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2orvokiwa.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2kktvprth.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcvhnrh.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2droxjjpa.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2liwexheq.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbplpht.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2opmsrsmp.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2gahegbci.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2dneikhhl.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ludiobbt.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmijsow.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vxztumco.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2sqakxwim.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsxtpjr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2erkskmxb.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qckprdgv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2smdtoxyq.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tilaqyoq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2thxzqwjs.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2oftuzqqz.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ftakajpc.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbqrkao.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbpooca.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cadmvyjq.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2emsirdbu.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2upbaxdiz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2cphkufap.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ataxlhwc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2exzzfelc.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tkknvznn.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbyrkpn.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ievbmiff.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2gvblascb.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrahvnk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpkwfwg.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2todkensa.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2meqwuiqj.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2irfkdhab.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2okcvolgz.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2puuefqrs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2vglrpmqo.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvehrnu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2frdejfhz.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2aydxtmdz.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpfhrdc.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgljell.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2shraunzf.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gluipcex.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2iezwalax.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdlwurb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2iwftmqwq.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2usaxhxwt.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2utunurhl.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbfxprr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2beoyfxvy.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxstwva.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyuvmiy.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsxbmon.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpmfpie.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdfjrpq.html


<!-- 参考信息 -->