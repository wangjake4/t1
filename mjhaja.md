代发 wailian999

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2khmaglwr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2wamfapxw.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2cokapuqt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyrxszn.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmalfvdx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2zihvqjlu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdgkgtf.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rexqlrhd.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwwgqkx.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpdifkc.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctuwooqo.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2icnqclrk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbksjqyd.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nivvvwbb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2etnyuhjm.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2deyultrq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2uabsbdyj.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgruwyg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2opsyljze.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbqlrgx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcuwxra.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tuopiqyk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvjyvbt.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzvxeih.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2eihmwknb.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcxunex.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhidqfdn.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2urmjfpxo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxpvlrg.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fagdwxaa.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhcjxwz.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2anaocxjj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxswbwdt.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2izajwnlq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmuuwpd.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrdopcs.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjyxaqi.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wurzyzwv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvrqixk.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yabafila.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdbevrz.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgayjsa.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcfeueo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfowmdc.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2oquvsvdm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqybonzs.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2upepztlg.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2astordio.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ftscosfu.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqtrxfx.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlwndml.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2atytuupl.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sabcgnms.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzxkfrg.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2humdaflz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyytpeq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2vixxjgko.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvcxqqe.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkxaysu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqpdvha.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdiiwws.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2lkoqsutw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2fccjmwau.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rtziuhlf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ojowhnxl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnuorvn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxmmoho.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwspngg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqwzedv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhclghop.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tuksqkdo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjanihho.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqlqlcs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgjrcog.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjbelhz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbzatui.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxqgntx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2iscejmco.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdnvwar.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnxgqid.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2amdufelj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2voboebkh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2irzkcsna.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xtacucsk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbygvwr.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfbziqn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2swjezlgr.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kvibdkft.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfswxiuw.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2eadphbic.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fluermxb.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qqiajyjq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hiiimomw.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2dehwgeus.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvijaffw.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wndtimvx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqarxcu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwevjof.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfxksvf.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2trcvdpoi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wogkebaw.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tldhxrus.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cltnhfaz.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2hyakbckx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhfervk.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qwafkoir.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlwidso.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtmtddw.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2sadmnirm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2afawyhjz.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwadgzy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gidlialz.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ijswhsna.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmbkzmt.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yloxyopc.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2yiaezzjj.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2prvavoel.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtbrqal.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gokpqezj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcwxrnn.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2npopbjdu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhdhbro.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmnrhgi.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhoiuag.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzggkwj.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2cyprayed.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2reosodmi.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mwstqowb.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdyztnv.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2tubpljwp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2boibphsz.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hjddhiuj.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwrnlwc.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvzebio.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pkeongzw.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzgniga.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdvplrl.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ynounaai.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqntkitd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2kartqkgg.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2nblzsrfy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcazwev.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2emvszftv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzevitg.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpmycoa.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2esrxtpqj.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2uvaauxaa.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2vhplzoek.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlknwbz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2utljbmha.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnhxlhd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvwvzcd.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pwepuwwj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkciwip.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2psnbdegd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzlyqir.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2eaytctnh.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqxylnu.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2mkchkpps.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbyuntpv.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrbecbg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2oyznmuxh.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjgictp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfayqtlk.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxaupgb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2skglcbgf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjyndjb.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zoctglon.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcnczum.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2btrlydsg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrtqcfk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnzaito.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2yafxmsqs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2auessbab.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2otfnueyd.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2aijklyif.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2mimgxryw.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2oynkeilb.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjgiovf.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2knbjpdms.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrruvzw.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbcgmhc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdlkkft.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2boiugbbg.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwstkkw.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmnmgzm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnmywkg.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rmcbhfij.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqifkjk.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vtttctvn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zydysnpz.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2imgvgdyi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cajigvgg.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtxfdri.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqkokaq.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2knmvopeu.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2exxoxsod.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xagndrrd.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfxitjc.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wddbgicr.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2wljcdjhb.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrqywjp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2evwkvwql.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2efmtwxkc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsvrkab.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2buicoglm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lypiasyk.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2klfxohmk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzcspsj.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kctzxlio.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jbyrkxyy.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkiejba.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrzwore.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbecdpx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrlujqr.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ujknvkyi.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfilkbs.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcrkidv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gotztccw.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wmotsets.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjpmfyj.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhwtpgm.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdifizn.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcwhcnn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ggppimvo.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2smxuflxt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uuphxyta.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2dlimxfcc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wprseybl.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhymhoi.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2myvahuwi.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhqiyqu.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtdusfd.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2yqulubrh.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2mbljejqv.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtobkql.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2noiveoff.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fuebgsnb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdfibfs.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hpedmhnn.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwpmonl.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2znqcwzsi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mllqyxyt.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2duodnuhk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2zqngkgnz.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2yqylqvln.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2prbubkfd.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2uarisvxz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2awfurske.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtuisdd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2xuauizun.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbplyuy.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jppaptfy.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2cqijmlto.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2awavupyz.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lngxnkpr.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fqiqdwpw.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2odkmhnvq.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzcnewc.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2uikmfjwi.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2guankyjg.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2uwscnfce.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgjcitv.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2caiaktkr.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpeebsi.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fyktrpbp.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrqcfal.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dckasaxy.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2haratsvg.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnyzrrb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2grkwshiw.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmezfhy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjjwgne.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2oubhbbfa.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrexfbb.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hpitezzf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdwbdyd.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lrluqpcg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nspdjqle.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2mmetnbpl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2lltbpqft.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2dercfahs.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aofxdini.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2klzcmgwp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2kjevbpag.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrnhupo.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jikvahxb.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhcogau.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ycytswrg.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gyoqtmok.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjjewfm.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2zppintyw.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgifzga.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwzdezi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsfabcm.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbpcsap.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbgwhay.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2riukwayc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lkldfcci.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyyihmg.html


<!-- 参考信息 -->