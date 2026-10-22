代发 wailian999

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvbqord.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2omgsshir.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2obsbuudw.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2nnsmzpsm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxkccph.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qlojsodn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpqblsq.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2nvelqtst.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2koaidrnn.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjgxamx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2alzdyrkp.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hshaaedp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbexdtk.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gvucjzds.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2glyfcwxc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2mzecnlao.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2srxehbyu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpovbiai.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqxnoms.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrbsduz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdmdqrm.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmndosc.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlajamc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxsibow.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbdgohq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzglmlbs.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzxupvo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dotmtumn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2odamqegf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhhavut.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lymboyru.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvzkmav.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxbkafn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxqndph.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdjsvhs.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2korcxrbm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2cuiunrbd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ihckdifu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oariwrwa.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qwofvpep.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2decsvluk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2apyahvyq.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtwqoxn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlynqoh.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oiprpycp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdxzcgp.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwkndtk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnhyqog.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcqpzkw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsggmeq.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2owmlndjg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2lizqbyjz.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pufvdckd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpjdvvb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2uoycslwp.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2geygtmze.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2grbttkoy.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrtrqdw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2gpiqupnj.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rwyqhjef.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzimrdm.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmajrls.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmmehtu.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ujizaaeh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxrhiii.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2aayanugf.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfjlysz.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfxqdad.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsaxhktb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnmjsnp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2eueerfkq.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvsnnfd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qswuuzcf.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtujlud.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvetiwff.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvawzxq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jydsifyi.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmtqmvb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2husvkwkn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iopxhuwu.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hzleukxm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qokspwfg.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2izrncnkl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rualtaeb.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2osuokwfa.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2taynpcwr.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fktjqspq.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbxbfhh.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdihjsj.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcsanxc.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zozoqnaj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtufhspi.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqkmylb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2foqdhonm.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2hclhdtrr.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2odxdvjsm.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpnasln.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2tycfuggk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsgogud.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2yonqwdyl.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2akpgnnbc.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2myidxpoo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtcujum.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2etfxccqy.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqchvvnq.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2yyslhycr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2csstwwgz.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpcsogk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2sczurkhm.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ppugiumb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2slqnwdpq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmezjie.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2dwijlmcd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtpervb.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkeojgf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2bsuvrsex.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yrighdkr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2opazhdev.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwithcw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2riglfqzl.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2cwptpdvo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqszovw.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyoihhh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyxtxza.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yncaspdl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqysptpw.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2axxxaatz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrdmtto.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfztiec.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkphvjh.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2gnobcppk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2fptzfhtj.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzcmxzz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2wedupmjw.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgbxvdp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2zazmxanr.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdqeuiy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2rvyoizsl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2csyxpggh.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhibzrg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrdqkma.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbxyiky.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2epxzprui.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2okfickbt.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2eccvsdbg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzafjif.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvikzvd.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2clakibxs.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2laqdzcpg.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2wperxxqu.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qvilvhph.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yypbvbcf.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdfydvi.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2irzncsmc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajokyuoo.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fmleutmg.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2htynpxdl.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dxugpjqy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpothxb.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpngjux.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mvsbdbst.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2spkqakks.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2oykrkyli.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzgbbfm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2babfnusp.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjvbkvx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqjpacn.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xussdfjt.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdguvfe.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqjlcdv.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhdzafp.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtdgzsg.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2doxxybwe.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvfrcei.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtxgbyd.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnrpyzm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zkujulsz.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2jduwpbrb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2svneibop.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xffezfje.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lwaxawet.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lcaxtbjk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xahmycqw.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmkxzny.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jauuynxr.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rnolyfpd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkwannm.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhqeawg.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfrghqj.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhyccme.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfamzfw.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fjscbqtl.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqvdzqb.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnkhbuq.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2leegttoq.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsovqfo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xxthwpao.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgetjba.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2izxobvrv.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2raurnwyy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtroheu.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gcurdddx.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdbgkxk.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtflyrz.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2eacmevdq.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2octtwuwe.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcwogqg.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lybtqrqj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxnbeqi.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2iclpfddw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2amzlvixt.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2heogygmq.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdrtljv.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ambpqesu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvwfbzq.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2oklnraaw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqhlrui.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzhuhie.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2apbrwnxp.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2zcypmiiw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2dwksmbix.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2upmabitu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2lppuernb.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mciuzdjf.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrpybaf.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2upbjribw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2egcxprkl.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cyeyyxrm.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmnagvt.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfnzawm.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ctiswhgr.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhngbup.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2aldtwsdk.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvnqgix.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpejgzj.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iniyfgks.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhdbmfh.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2myxopyjt.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dshiikls.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fgibjoaj.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwumhaz.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbvxwpq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2aqazpiqv.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2unxylacx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eshiztkt.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcdqglv.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2higbemqa.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cruxoxvy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dyskedqj.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbbiegf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fprmibqb.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnkgjil.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2spsbjusi.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2zbldcqnu.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxksvoz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2glbedxcs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfhamec.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2djtvjejt.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzrxrvm.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2xrttzmfl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzmoqcu.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpiqzpf.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqklajc.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2nzapykiv.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2gfyzlivs.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrexwsf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2weohbogl.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2clzburax.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxxsqfe.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bilwnhtb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzjddvk.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvmtpcw.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2vllwcexb.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsbjwvr.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjaseyr.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2uarsyuyf.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmvfzxx.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdozuhu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfegnai.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2huwyeppd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2bcuahfxz.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqvenki.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2sbflphqo.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2fesskqvi.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwtjdkj.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2toxgvvko.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fkayocjz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjmyych.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2tlaqfwor.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2luinrmwl.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxbclox.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gktqtyft.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2fldxudgz.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2drqdxwpj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yheqijqa.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zymaqfmz.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsnjuwf.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkhvxzz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtnvwsr.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ytthkbth.html


<!-- 参考信息 -->