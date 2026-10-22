代发 wailian999

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhyvaek.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbibmug.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmhduqr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtclmrb.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2oclaxjmf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2srvkpxry.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzfhwzp.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbqymko.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2camuvcwg.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfbwlmz.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2trmobcjw.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxnlfbw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxrouju.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2soigojbl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2vbclzmpw.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wxeipjxp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2rufymtcg.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gfyubvmu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjbrriz.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqyrwye.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdquivtq.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wayiaiyg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxeqdcfe.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2jefmqaac.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysycpolu.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtxychc.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2amvxwdbo.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdmexwv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhusezb.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2msiblzli.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqnumob.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2suaioeci.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdcpejh.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qxalpfyj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2omouodlv.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ooemjqpt.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffykrxvb.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvcdpev.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgwyuck.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsoquui.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xulfhdom.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vwaeechl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhcyjxh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbpduri.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlatdme.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2zppdmngq.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2geyvaupk.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhrjkjz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrcvdhd.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fujqstpb.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzqbxfi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pilbdmil.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qapjrqvv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbblrhq.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbzgbwb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcvbhhb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzpmznn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwajafhs.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lxurrjok.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfbmlpd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmclgmyi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfzhmlk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwsfvli.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrvsvdr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2thrhstcr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrkxjdr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdivhrkn.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nidczuza.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2egxhlieo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2frlaetma.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uznlwllj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbfpgss.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2efpmktan.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbsbbqz.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vciibhyh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhejxmn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uiuymcwz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2iosnidba.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ircpyltn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvlvluj.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yuswjbdi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2treewchj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfauynp.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lvibmuic.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qztzmzes.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ualbjfbo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2egbbmlqd.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lipxvjon.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrkqcaq.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqglsvb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtemrzva.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmxtayv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgcheic.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2evbinydu.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmuykpbf.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2onktzuty.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdevvoq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjfzquy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2optmmuzx.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxgmlrr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsfpdre.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvgpobj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2syrqyjld.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmnnhee.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wktwxjls.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjedjzq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqmneoi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uskidjdz.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bmawctcl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxukpki.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwugazb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlihqwl.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2slwkvtcw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwczkcy.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pehemmuk.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2axcvffxv.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ljompltq.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2bptiljeb.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pjetowhm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2kipfxtqq.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhzjcfc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtkvpua.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2aakzcwjp.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqiwnvt.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvymdgmc.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlhavqs.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2yasarqks.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtlpmae.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqubqmul.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2nllmnboj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ueuzqobi.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fdubgyof.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqftrie.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2lesbuygw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxromxx.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcxpdsz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2eszfryif.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sqluqgxh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrgydsj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbbxuvj.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrycyus.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2zebnziry.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxbcrhs.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkqdesh.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxenlhm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhlcgqv.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bgamypji.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdopska.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgwehcl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqagdww.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ubirwbjx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hazfzqgs.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbmciqe.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzawawh.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpcymnd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqryfdyf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2sjysyese.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xramvkfc.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmglssg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2exwmpcup.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrggswe.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2iatmfayl.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdwgvay.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgeyqqw.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ehztsbsv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkqwqeu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2phqonkhv.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tsobjzfj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2phjclxtt.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2icjanatz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwpclue.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2naagmzzq.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dracdfos.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cdygigng.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsljbxp.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2xygcgpba.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfbvtpr.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2dxupxwme.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrekaja.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2extpvzgh.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvebwko.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ycywouwu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2zycaxmfv.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2onapuhyo.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvceiyg.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhkonqh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eykotxmu.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nawrurlb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jultiluj.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nflmknnm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yirhhmce.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2riacnovc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gnskrkpy.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwbecoi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tezycoyy.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2wkovbyav.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2iiapawuy.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ashuiiyh.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvruigon.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yuryyhkb.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2yccgunto.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwgnmin.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsweryk.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ftycpjwc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfluvht.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmbfpzm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjdejkb.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqjxblh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dayklvrd.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qznhihbh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kulckjwm.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2byoioxxq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nkumhjdw.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbnvzzw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfydmul.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ezexvgxg.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2denzzowz.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrnvwyd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nkadkyvm.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2geuakedw.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpbbxiy.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvsmvgj.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iytkmlcc.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xmssbehu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdypqke.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpcnuqc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxzqahr.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpsbdbm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2abuyloee.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lniejcqe.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmmgivd.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2zrubkxao.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2otawoirk.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvvclba.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2aibgjgjg.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fbulavhc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cotkqyqo.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqxonim.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ljugsldn.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpacnvn.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dukucddb.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ccobilrk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkrdkdl.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nllxbnlk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmfceze.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2duuvetiz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2irpksptq.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ozoylwjc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqecopk.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjhoobv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjxstup.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2niijlpgf.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vphanuof.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2hviowjwb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xenlsryi.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgrzbbb.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ftydahgh.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gcadpywj.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bepbitxi.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlidrpp.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2yddsktec.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqnxant.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zsidqojm.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrmqqjx.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmnvcuy.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgccnnd.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2uwywgcei.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2sromwfvc.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwakcxm.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2huvsthrg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2dcechtra.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfwgvmz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfwwpym.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxyeezj.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nivpfgjo.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjaghil.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhqqblv.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwqdccz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqzduvz.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2pckilgap.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2qpberuqb.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgjcrqx.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hwiovngy.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fjoqphhm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpnmqfd.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lodvfrye.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtozrmx.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2yqylcnqs.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2iamxheba.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2knxgesps.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvixyzd.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjyodsz.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkcksgj.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrbsgbj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvfhuwy.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2iauqgdoc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdgykio.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2idxuxeua.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2myfqvhgn.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2szpojdyi.html


<!-- 参考信息 -->