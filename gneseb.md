代发 wailian999

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2vykkavnt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2qeywbykx.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkywynr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rvntmdgo.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2rtffwypa.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2mqomwrzb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2iygceeux.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnjbhvq.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yosyjade.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2apzzeszk.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iaccgjww.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2clwxlywq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcooxya.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uwquycty.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ictcfbbg.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bukhgjaa.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjehqmzx.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrnddqg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwrxbkc.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbidgew.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzwzcib.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wedqoksz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmgpjky.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2kaohafux.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfrbfor.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbyuesy.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxuuoip.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2aphckjmi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfwhrro.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fynrsnvp.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrckthf.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ddivziob.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2scozbdmx.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbzyxgh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fajuqccn.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvjifio.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2avxznxbd.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmqourd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhiekev.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdjzptx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fahadqow.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfbachq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gufouhkl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgytlun.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kpapctlf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2paehohtb.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2nbuktgzq.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkximwa.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2aonghmzn.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qverwobc.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jyizbzws.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2luwjjuck.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qpyfmpna.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwcxelu.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dathheac.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2odfzdzze.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2azkuqqnl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdhfnhf.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2frirykwf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvowcrp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2btuhhfma.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfotxzrg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2shjbzfrm.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhijfgk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2cykfnjuk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2jazlsmpl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkykcgvi.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkxdxuc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2udqivqrs.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtidybg.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvgjjyq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsojmpt.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfvizif.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzctghk.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtwszxr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2linnnirv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtshqwu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbqfevw.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhyllje.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltoyomvp.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrhxjmf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2auhuntpr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2lupdmdgi.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2durgpuwy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2spasslnr.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqmfukk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2cytzxwls.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jlavgsqy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wiijnkbr.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqdcvvu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pebfbpjr.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqwqovm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2paxysjsc.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrlitfj.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxznttd.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zhndoryb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqgiskg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyytxax.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkdjdwu.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2upbhjczn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwjztmp.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ttorehfm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdzhryt.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ljiysoia.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2irkbrtgh.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2aehbcfid.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2goyeoxje.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmmlfrr.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2agakhxvs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2igekfaqp.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2enupuuhy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmgytjj.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uvswtamj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrdfoyy.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2scdmlkwg.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2omzzlrzx.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbyjepv.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxukmjcn.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxltgmr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrfizkx.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2slgwxdrg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpidhfny.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdnvifu.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnsqkye.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpltbsky.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfcymjh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2aalsnfat.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbxiabb.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnxdsug.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2oexpauev.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2nqidyenr.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rzasgvew.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsvtjuu.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsqeddc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zexkjxlx.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kdguwwdc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqsugni.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ssipfarj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuuebuqv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ofomtsis.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhkfrtg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqqhywh.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrgmaej.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwddhtp.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2maoftowa.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmtlhfw.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhogqsf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2uheabmiw.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2wncpnetj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwjihiv.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lumgvlbp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwxbpoa.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rncqzhgg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbiaecag.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbahtgj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtetedor.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgforir.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vplxnjos.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdydxpr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2hulwwjwr.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gylivazq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2enkmzzgy.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xattvlhq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgcidor.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpxmgrs.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2xwomhfax.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2spjivrvc.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xcypzgxc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tftrmpzj.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2kxaobehm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqbgcrl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gyflnjjo.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvzbkwx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2prncmnxk.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfmekwh.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2zrsjtrti.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2qywvoaam.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqxbfkl.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzalcwq.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzkfgmj.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqfzocp.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uogmnkvn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2eswwfjef.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwtiiib.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhxvcvj.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sodelnhq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqhhthr.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hprhpuoq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvtiuve.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iseljjgo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gxusccfw.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkavzjd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dbsbloxd.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zwczxbrk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wyenxwfd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2mwonundc.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsuoads.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdcbssv.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sicevckw.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2onohenvy.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2edoicujw.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwwcfoj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bjivmqwj.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2oynnlxce.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aaurfwiy.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2zghglvra.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmmrduw.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsbvxlk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2flhzypqg.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oppxvzaz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iwulaepi.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2xirtvllz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjxifvl.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2etuuzalm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqgkdxy.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zlyxfhpo.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2veipgben.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2wobwilhs.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zyacalzv.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlzqjwp.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vkatrdsc.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2mpprqcan.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmgsovw.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2crdstxyc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2arpyxifo.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxsqvir.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qojkfupu.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ephueixn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ywianmff.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2goslubxg.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2jnujzqjg.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2qqivdszm.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqctoag.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfliehj.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxgzqxo.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2grebfmkh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdhierh.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gtuqavdd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2jmizttgi.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcovgbv.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhqanck.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2yktexavy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yckbfspp.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2smrcfkej.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2nzivlvou.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxxxfhf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkmtdrf.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnxbida.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2znwxbupx.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmmvspf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2rhidtkar.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdhnuvl.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyprtxuk.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqfgifh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2snqhnkem.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2idjhpouf.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjldfwb.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwtgtir.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bersaugn.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dihngpib.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mehwlsbw.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2susmdhmt.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjzvydd.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqvcbtb.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2robhuqlj.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtvlxcq.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qooercsl.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2bxawnnqs.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2txnowqwx.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2swyuycdd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnxtxto.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tyulsywl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sxscwcpt.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmpcvbg.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cjyxqkep.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ybebbixo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2fytakzao.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ihihbtci.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmltxyj.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsibyok.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhmflgp.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2oucgdxcj.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2txjofnho.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wajxiavh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkzaqgr.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iktaeiyl.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ythcqokg.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ixblktoz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2qzuyjgtl.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjeyrtl.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2flcrmepo.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2bnazsnay.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzytfkf.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzoqkpu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdlvhjj.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2epdiexzm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2etxdqxpm.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhqnhxm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cpoiexaj.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dksskcgg.html


<!-- 参考信息 -->