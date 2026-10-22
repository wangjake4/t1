代发 wailian999

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2edkzmxra.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2txjcqyqq.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2chkkeduy.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2wxuztnmq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwwkfyd.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzmapbz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgarrxq.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2wvugutdp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtmuuwl.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2aeclvkdh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2joucqpat.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2drfecmuq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2naycbymf.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdogcbx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgmaozd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2vhekzgwr.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hoylzvhx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2wctnxgcx.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2igmtpzum.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwkrmyh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ebigtixw.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2anuftelo.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcylyzy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjnfxgj.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qionitow.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzngrzmw.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uljxzazl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxekwkvm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2eswjbqki.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzuwefq.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvxqcpi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtelbdr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhtftcn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2pkugnijw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtfytsb.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2benupukn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzrdwuu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2bglxcvcf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpvclnz.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfbhgqr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2bamkzzqb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfdmufd.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zckgkvnu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2evgcckqu.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2afyoflqn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkieduo.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xqskoksw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2emtibvhn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmnjbtx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2kckiggqd.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfvihno.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlrdigk.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqqbksq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2syctpnyg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2eeffpcci.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbtonqf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pneqygvf.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yogqeyaf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbypwtk.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2iskdwshv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbywhsif.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbfdwhr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpsmauc.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnnygso.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2enzkkxvn.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2qlydqscc.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpsvtsyo.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2dkanaqry.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtaxgsoy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jjeqvdfj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2eotkcdpj.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pobepxwy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkemiuj.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ejocbran.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2inohochn.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2aijiridq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cceliqjj.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ehftmmsd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtqfkor.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yatbolcn.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvqiurd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndalgvnb.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcmskpk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjcetrz.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxhshil.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ocinfjbd.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sobkyqyz.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpcibiz.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkjnbcl.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmnouod.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgrukmt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtgiyoy.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxnpjgm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2chjiipyq.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2unmpbcgc.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2amfhvdby.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xozevlpj.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2flyrkfif.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvuisav.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2doenwmnj.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2awqznftp.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2dwuznqol.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2kglbpdmr.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fpioqmgv.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkttpvhn.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvefviq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdvimdr.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpljdhr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2fthzutyj.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gshggjxh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpccvfqd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2cildigqi.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxwbwfx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2majisqim.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2dktshtjk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2fzchqgjd.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2iswltpyn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkvyzoy.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2twinlndc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnrhbhb.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2sfooynzf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnokwrel.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfsigee.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jofldscn.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gatjytya.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqsykrkb.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxgyejg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2orjsardy.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjrlvjx.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugeixpbl.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjmfnmq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ughhwofo.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vudrgevk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzikxht.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2egigmyqd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2crlgzmuf.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2bvehuyfy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2jnghqblm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvbwdfj.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kidglova.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2poncamgb.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2oprhaazo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tumpacbk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2amxrrwmz.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvciaex.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2quryhwla.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2essdqxbh.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2pergwtro.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrqangg.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2khlcegpj.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrmmqox.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ossnxrzc.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtzzviu.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzhoecs.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2yeoorixk.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ecuowdbt.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eakjswvh.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2osrzjdag.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2roysyyuz.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sqiloxzj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnadgdi.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2outslsjp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlvshda.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uctgefxs.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qxktmhad.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2irgsraxy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2azrlrmgp.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcwmgca.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2bhziizma.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqwtlrq.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkfobcf.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkexxlvn.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnlsxqw.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2inrmtexr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqrdlsr.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnkfxzd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zoubhpdb.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2hshfympn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqtamov.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrhnbzr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdcdjdi.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tfeckjgc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jadbwqtv.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2wltyeuos.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrvoxfx.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vsczeryw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjjincc.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gnngprbt.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwcziyt.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2zkoniyle.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dargaogd.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rvumdayc.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fcduwmqw.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ksulzxby.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcljhwc.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ygimozwl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vigmcmls.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tquskprl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrfdntn.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2alnrdbis.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jjehmyei.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2doriooqn.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtrjxhy.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2jerpapyh.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvqtzzx.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvcvbfp.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwozjhz.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2grvjgqgl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mhioxixh.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2axahbccl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2tyeyocuq.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2phmmduvw.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbywxtm.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ukybmkkl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzeexbd.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdyzzgv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2vnveuofc.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsxggpi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ebabjolc.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxcqfsl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2csafnsgp.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2unkdovyc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2mmslxxur.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2clmndust.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzjsfnr.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2bktnkiaw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpxafss.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qcazkank.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pjodaynm.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvwylkk.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2aundtlat.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jomrnyra.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bowqvjwl.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhvekos.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmwlzhh.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yjifunvt.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdkxhed.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2leqmkwfr.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tblofzfr.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2swjlinof.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2obkjleeq.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqpoltd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwtucxv.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2twffotoo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgfswhz.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2irrrqmgk.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dvsfqkhy.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2grmcuxho.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbhahqc.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmzfpqu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kiebueuq.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxktzzm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvtooef.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkvioiz.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2opxsvytj.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ndknvfuf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfzteyv.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mxezqqks.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtuqvck.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqmjuum.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqdbfio.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgmbdcw.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyaiemv.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwsbqbf.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcnmtku.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lprktgea.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjiebuy.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2knlpdgbp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2iyffonsk.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2uxscclyz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2edrjiefo.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2phrffhww.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2isforrjs.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2klapyorc.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpfsbpg.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2afpyhrml.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxfolno.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tlotmwnm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqycofr.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfgjriq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxxmhiw.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xikcvqxe.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkaajlc.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2vyultomz.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2bqthntsr.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2vskrwnzd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uaszigzr.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2dakuwopf.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2altjkhik.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2xxloyflu.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2jdyamjib.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxfzgdv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2fepwmoeq.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcmfimd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cshgslsg.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2uakcupox.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2qpznpfbn.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2aaylsmqc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yztkmhdw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdypxmn.html


<!-- 参考信息 -->