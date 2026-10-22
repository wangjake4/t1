代发 wailian999

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2aucozqjd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2xpozoywx.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2jslzsgmn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqcuove.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ckldtllp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2tyuwjlgo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrporymx.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrlznpq.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eigwkjmf.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2deltzdxe.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2swwyfgxh.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oljhcxsm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbyktih.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bhelwmvo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2buayorav.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fvltfpdo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmzrfgf.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpxuhsy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lomqvyct.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbcylyz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyunxamj.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrsmhts.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlygfbog.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2wwflibpy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuoeihev.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hbenlzxi.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcolxpf.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2enxtkylr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2snsasern.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2scnkrswu.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aruhadpr.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnbfaap.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpajjyv.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2badegyqh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyufxuxw.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyxnorq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwxqtnn.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxsfznp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkblflz.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpkgvcj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2howjjztr.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fycdehcn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2sssgpret.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnwbsib.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mojrlnmp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtfkyhw.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2gzarppoz.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlnefed.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ueinpcgv.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tccihtxx.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhxscnf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2goouibqx.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2crizswum.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvhlcow.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmknopq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmruwyte.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2eopyeytb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2obnwnxlx.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmpeqhh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2sizngmnr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyesroy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjdrgnd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2lisssmle.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2leyulmgz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ryphupkf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2frteaeqg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwloufcd.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2varegwkd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjfkxqt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjazvms.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nicgmuet.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmurqcc.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ptixpuae.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2gamoqngs.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dfuobuwt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2rghbcgar.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2aaapncfh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zupukddq.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvqmqir.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2boypnqcs.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lojplhyp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2gshckzkn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrslobc.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqdgvmk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrvysxr.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fituisxr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2wiajnbgg.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwpassg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zclmkbns.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2brrrbwla.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcazbna.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2bkenasdq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2aqsrzwgb.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2wqeapxnl.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkenqdz.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2glnxowcw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2esdkcmiu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhzgjol.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2mavplruh.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2brdywwer.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnynrdaq.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwhhhbo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpogvnb.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrvzukw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rimxtkiy.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqvndzz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2fidccjxi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuknngnz.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvxvjhi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjeholt.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2hovkzxeh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wifmmjjy.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xczscxyr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzfajli.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2szhvdsms.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlxhsfq.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gifwgdla.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2iphcjokn.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nimzotok.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2niiqltea.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2tkracpmz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqopael.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2amxjbgcd.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjftxbw.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzulqije.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2yloojmdb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2qwglbwoh.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwgctpq.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2apfehdod.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2zqiedsgr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ertkyhge.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2glvgajll.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhjcwbh.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdzwkhk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgunscz.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yccoptqr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2veawforj.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ibasaeza.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lthzzjxe.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2zijquowo.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxnmnab.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfchzfs.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2htlywzli.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwtobkt.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qovrdmyx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtqgtzc.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2artdgfaa.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpfxqrr.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgnhhcz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxtcnew.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfmquao.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgmtexd.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2htmcnpqf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwurnzrj.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mypjeisk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2slqzhvpf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpdltuz.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwzwrgh.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzvropn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzqtdhe.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrhhvqd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2skilcvhf.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2adoepgzs.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2noahvuwf.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2aizhryzf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2apalymxy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2poxrkhck.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrlpmnp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2osrqcchw.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2kodentlc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vaclhzzy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2laoyqerl.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2uerjiqve.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2szhphegw.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqwhclb.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2twxpjvgv.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpferlf.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2vjcsmnti.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2iikhioee.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnlbbmv.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqfbapu.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfysire.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ilaobgtf.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2bvopfxly.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zbowxlsf.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnuyklq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfrzcmk.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fvludupu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2owfskihu.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbtpohq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lneycyrn.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rqearqjl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvziucs.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mopkljfr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbikgtf.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtrtycw.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ftldbxgb.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvgngxm.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnxkiwu.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhltury.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmavgvm.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxwtxpu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mutgodtl.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwttvof.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdgpgko.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqiojdy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2smwcybhu.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ahioxouy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mesfliuy.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dyyzhqrs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2afokwahd.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgfonny.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yoihiogx.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wahrvupj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2isycfzvk.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wklxnofw.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2simfnjro.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2uvyxjffx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cphhbxlj.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vabicihd.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lurasqmb.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2smxntoiz.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lfunljqd.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdegdey.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfhmval.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjuxqyb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgzxjsn.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2klwvoeau.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzutmpz.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2odqrszdp.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2puypksul.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2dojcomkc.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsduxxj.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2gewemkex.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2udhduokg.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2thwestre.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2snrmfmff.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjnmbjv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjrfbzn.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsaamkr.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwoynief.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwzenco.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jncsrgug.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2sefnxbxd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2mcitwswj.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrflhhx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvhcizk.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2melnjcxu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqbyfee.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tqtvhvxz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvqjnhv.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmfmoyg.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgryufl.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2hsngwkjh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2afpekjby.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xxliuzzm.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcllcsv.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tithfrna.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rlryvkaw.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxjtfjj.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2oothvvch.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2xugemxoa.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uunyewel.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tuibvrjh.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmbidmw.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rqaoafjy.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ivksfpky.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fiddfgax.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrjyzqn.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkyjnji.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcpsith.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2drokphvl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2awsgbwxz.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2boqbhilo.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnqknad.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wkktgwwh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwsmdpd.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mniytwlq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ympnyeve.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvtoeyo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlbtkge.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2amizzrcu.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsrmzxc.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzqrnna.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwsigvc.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cceenkul.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2azslkbji.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzjhgxi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2enwuvrpw.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwwonds.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsomxzq.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2nfoyhotn.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2toizgprb.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wobmwmia.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjyrtnq.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2upnaoqtu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvheyvc.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wymrkxju.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2izjinnmw.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmppcwb.html


<!-- 参考信息 -->