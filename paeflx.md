代发 wailian999

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcxsyqe.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2azljgjbl.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpisbbvv.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2itfjtxcd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvyzapa.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxmfjty.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykoqwplb.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2jhemlohr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2afbycjwy.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bsudwlsz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xktivlch.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2afsqeakc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsoixcf.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cslkbetf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2onakqjga.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgsdfxy.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwvkihw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2okpripqm.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2htcbivse.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2idotxbky.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2kykyabgu.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2haxnszdb.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tcacxnew.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzefhrrw.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yppouaml.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zksnjpee.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2oityqait.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2atnzdxkx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejziktvv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nihviuwz.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnmjtos.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjmqlfe.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnizdgnp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2qhranosz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgmwjpm.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlsrfok.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2nekslagm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkavpaz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmsjwfe.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ndujrlag.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2zufnlcmp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwvnucm.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ckviwkwv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2sntudmko.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfgjpha.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcvqioz.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2roeghiqg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzngfsor.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdawzty.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2nukwarmj.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzbqkhn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2wugertes.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvdcnqa.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhlzqek.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2gobpjqqr.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpkzqjt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2egiwvvtx.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2osqbngsq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2dfctcgvp.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwxlpii.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2swacjelj.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrttaep.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpycvub.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2olpwnyqj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2iobvqciu.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2oknngnoy.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtzsvao.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtlqgby.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnegvdb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxlltfe.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsbubuf.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2uraisrok.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvtwyvf.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqkgvur.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzhadmo.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsiegbz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwmqofe.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dzurwirj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlfibxm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmgdwro.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkefrri.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhpoqegv.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmopsrl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrkbkpa.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyhevui.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2snmnjjqo.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2iccmmaga.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkddbmeo.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ejenefpk.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmbrhtv.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sgicwkhj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibimzulw.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqldbju.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjueiaby.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2sodmqwcn.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kunujexq.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnaidgeb.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2aijzbpku.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyxnqtr.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2beylzqbh.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwouqofq.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2vwshgtfg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnpusgg.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2phntlppi.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkquewz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2yrojtnld.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmpinze.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yugnxolz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2eyoebrjw.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2odtcwrjk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmemjdfd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnapvrz.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rctnbegm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpkfeld.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfwzsal.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzvnevz.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzixbdz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2okdkijbq.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfozeeb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2nmspwhwp.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2fmyjhjuw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjadlqo.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yezzyrnu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrdynim.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvjsmea.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nftrcvnv.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kerktcpo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzczvwgu.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2fuftigat.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vchjtyld.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtbhpna.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2wslgedzq.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2yryaislr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2phnpkixo.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnfovse.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2kudoadvf.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdynsfx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmtfwvy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cencrdsv.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqtckxf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2oesriuwq.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdpintk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2torcyfgk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2veyonxmo.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2syspfbcs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2urjgacun.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2flobyhrl.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2nkairnlc.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2exskqogj.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2erketwoc.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2czlkcxcb.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mlahebpq.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhvixma.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfupoxh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjtulvw.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2brelaciy.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsoboil.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2syvtpjqj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwlxdio.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qedpcpga.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2oihzwbkk.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnwzuqu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmgmdvt.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqqdljo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pxupijth.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzelxap.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbkbsfr.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbbftol.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2xeoelvbb.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxobnnal.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmexcmmf.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxvymoe.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxcekgj.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ojusgyqq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbfwjul.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2brzrthsa.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmmmkle.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjwqnhs.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eycxnwoe.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfzceyj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2anxwtdwi.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gyieyeyz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsxtyud.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2qpnkfrvh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iugssujm.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpmcsqb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2swzlodaa.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qbeacxxk.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqxdkgt.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnrtagx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bxoeaswq.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzdwqzp.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qjerqfmo.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2koxfkcqq.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvokruvj.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2omqsihzb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2twnuvbkf.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrmizhe.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrfjtrv.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxlpaet.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dgoajnzr.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzlgzzl.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2yjusfvwu.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqeifui.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2eiuvxiib.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2zyocigoz.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkugjzi.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2txmnqger.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kacncasc.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2yiakyoqd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvpiysk.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dupeludr.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgstquh.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnmghtg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nesmcfxw.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjlmhxn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmkihth.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2toigghaw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kesmjlgb.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2asrocpxq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjalfxw.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2eynywvmc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdlfqnt.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcbrjvd.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkivpfid.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2inprykhh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pwodlzte.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjffvgp.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ascbhlye.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2earqdxia.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2febivnbb.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gyronari.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2puhuqbmn.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxujttm.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvxkpmr.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuwjffv.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jrenuomw.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jjraygaz.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2atzmocwe.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2pkyzzkpu.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnrspsm.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ackyoejp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2azariukx.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dftxcugn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zatdsqgb.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2uhplzrfy.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjofoxv.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2acepkiry.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmbhxuh.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fcruersx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2feptytvg.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ozebjgow.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnmmyyj.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2wuiwnmsk.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvsmxlv.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zfobgkip.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdqactj.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfhfmgt.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnehisy.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfuscza.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2faqabdzu.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnpvvpe.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdoxhkl.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vxntyzqo.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhecqvb.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjamrsc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgixqkd.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpldihp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhfqsgv.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nprfkhpg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhmlsgn.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2urcpndxe.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsjwavr.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fklknqyv.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2azbuwhao.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnbbjmg.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsaqtog.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2spyixiid.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgiavlw.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwbahpe.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbvqdrw.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqrljbc.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2klqynmwv.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2mehsthuf.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2uveznkvv.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2eiuekxfn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2brsgpiyc.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2dsclbxre.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2seibsqpm.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2qqupzzie.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnxnxfa.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbzzvla.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdvjknf.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2onuqsftd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlqpavj.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyectrn.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2zigelnkc.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2jtobvocv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2deerpdrj.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdgreei.html


<!-- 参考信息 -->