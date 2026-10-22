代发 wailian999

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezykrwxx.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2axjznsru.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2iqeluiab.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnhqmyl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhnvcsn.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2unjgepir.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2choictpc.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxgcyck.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2jguetmnh.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iehnvjht.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2mluuxdpt.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ebyzyupt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2dowaaffs.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qkywwduk.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahluwbtm.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqkjjew.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2grwmryzf.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2koudslit.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2quaegnwa.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnoseis.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwvqiyg.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bncrrnwn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvdlpld.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2irybqbyt.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgainfg.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdjxoaa.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlqjhgv.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uhthwing.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpnknpr.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jcglohjm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnuddpx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2adstiygm.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lthbvzzl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwqaukj.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2qruxugxb.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2tyamkbpj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbqllvm.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2awwnamve.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uwggaeyq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uozkatla.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2upkagaws.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uihtxazs.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2omschflr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynugppza.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfxxzii.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkoenhr.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qeymduze.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2xwarnfgl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2okandmtr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2llifeygy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbggjxt.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2otfzmwel.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2zdajrfma.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhcblqn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mskakjjb.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyjlisw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2syqjvodv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2eabetfkm.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iisetpqw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2fevudvbd.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlkfzlo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2owqjzuik.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpszyss.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzjttcf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zzulddll.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsniottq.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2awgiqmhb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkcagjp.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvkuvck.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhsbccn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdhssjt.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lroxkrpt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhrogdf.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2scineyud.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2tyttskvc.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkuflao.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgchpgv.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdlszws.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfmahel.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbmwqjq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcdqqsy.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2terbbidf.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukijejdc.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcxrcxx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2riiinvfu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyknogh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdbjxwl.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhcjxna.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlrgzjt.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2sguoqndz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfwbtlk.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfzwpvp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkcynis.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2klliwhju.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2kueuhqae.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgleirc.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbjgjkx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yawngvss.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2vuubdblp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwmcdmv.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbtaccf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2aabrwqeh.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnoqwjv.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftetcezo.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pptlhdsc.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxyrcwqo.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tlooubiz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssozwwil.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2cnaiotzu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqmwdbq.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2kwntqlfc.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqnopsl.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxglfpz.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnbgpkb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2eyovdexz.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ixziwhll.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhckdij.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyztxpg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2zijzdvlp.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2twhithmh.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2binypaxr.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnqklzd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvvxqdo.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwkplbe.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2objyhsne.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2htazgyum.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzckgaop.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyosomw.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbgwaam.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpocbal.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2tufnmqqb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqjobmm.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjdveaq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2drcaqvwj.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tysbhszn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkjdeab.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2puslushm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pykfgoom.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qduwxrif.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zucfrdlg.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2slkklkpe.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsjybjb.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xecaprhz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzauiuqx.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2vytjomjr.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2irpdbzmy.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2fkafntgq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdnkrrn.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgedbzo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtcomuk.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxaleok.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2glrenkav.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vupryvgf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2chezrilw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddocvotd.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcraqxn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2cldrmhti.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgwdfvd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgebpjn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hgsfjybc.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjwmaxn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2khpncfbr.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsorfyu.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2onbrbaoj.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzqanpx.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwfwxdh.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhacyre.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfwmjqp.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2vyknakfq.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dewerrob.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpbholb.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbfevjy.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mljdsoyw.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpostzl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tubotlkx.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsldnqx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qakdogds.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2navszkln.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tibhdjfr.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhkgmtt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zbuubumc.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhakqeu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjvltgr.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2otujoigz.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2gucdpzag.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrzwtoa.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2iklijipi.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwvghwl.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2voetthle.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqheesx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvlftdc.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxfhpav.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqfoinr.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxejzbb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vgytrgas.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iifmrrdz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yjyssqxn.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kpoqzdtj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2orccmxfs.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmghedt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sachjlfi.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2exxqezpi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iynobymu.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ombboxaq.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpxzrjx.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmdmxue.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2muvienkc.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ubflnnpn.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqadkdi.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2fjaivpyb.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2umnuheyy.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2unubddpk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2trgcwhtv.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxciwrg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtpollu.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2evbxcvmk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhopojyp.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wvetznkk.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2chotmpog.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2udewxqsn.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2vozttxem.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgibwsr.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhtukjm.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnlraqb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvonefe.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2yowiwpwo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2moexttsy.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lvakikgs.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzimmsaq.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvbsutv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2formltrl.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcdjulz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2vneasukr.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2uoycuahq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtmkexa.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxdrric.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzrvpmb.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ntedprlc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqzleph.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iqaemscs.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlysyws.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2vshghxpp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kygabjui.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdxypxc.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2djxkmiqy.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xnulayhp.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hatowyjs.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xgciixvm.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzgmfgd.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2vmikzvdf.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ncgdevwe.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcjgtlj.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ednedbyw.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fgotxfeq.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2yndltjif.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2foiwufue.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2xeobvjgq.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jjklgmpi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsxjnkg.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxoqxcw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cqczerkb.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jowaizva.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtzwlui.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fknvgwed.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpjrxmr.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvilbcf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ktztpynn.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2nolecblz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxbkpno.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2loddrzwl.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qhivgmof.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2chfumdct.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrskzvu.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bduwfkxg.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2amfuodoa.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2bylzqkmk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2yammdlfc.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vpyictxt.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcenlvu.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxagpul.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzdyyfy.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jmuzinmn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2xchdvgpm.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lumuntbw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2yahsqsck.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsosdxe.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2legvaqfv.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bluezsik.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2qwybcifq.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfwmwtb.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjvwlwm.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbctxnk.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtcqdxp.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lykbbywq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxyxxssx.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjglsdq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2hadyjtgg.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvuoacx.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lswdknxu.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvzobuk.html


<!-- 参考信息 -->