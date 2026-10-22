代发 wailian999

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2axcqmmmt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbvoipa.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkiwgphv.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hismjchk.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwplxpnt.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2uohqeaag.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2egepldhm.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsaftwu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2duojlgrg.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cguxbouo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2zlyjqhod.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dfobdauq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2xibefoqy.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2afyofazf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2awgapwgf.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2chtukmus.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbefqlsx.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzitkoj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnbxkhc.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2qlshhooa.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ignrdcbs.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2brfjfbdm.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yccwekjy.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2alcniipv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2eezbrswp.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxficln.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwxdtxm.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjxeppv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdssokli.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2dlejkmcg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdalpvum.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyxalrl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkspdbi.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjolbcy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvlhjxq.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pzedzfai.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcjhqwo.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tzyfohov.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2oytivpyw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcguqxh.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ebozzyuw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2onveormn.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrztnxh.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2dkksxynt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2melacgdu.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2meazoyia.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xgeyllrj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbeanlfv.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2igefjyfb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2arhiujyz.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gctbipdb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2syiakzac.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2llfhwyag.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bslttenb.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmziezn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxepnlx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgzsbqe.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjtjxvp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzarmovi.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjhvywd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgebigu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ottwdrcq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zifyyvcr.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkmszhq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbcipjq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zebxomhs.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdhewhj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2zudmhorz.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bujgmeuy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzxsstl.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gpksjtrw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqfwqca.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2djddomdc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfktspo.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pibvaunp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2iiszmctm.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vfoghupo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxydpnjq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbivouoz.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2evvissrn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwfcntx.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xvaftani.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2chvtyion.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2odjlctkl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsjgjtf.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwxtkfb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnehszsm.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2sukcwxjp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xatergdm.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxfkary.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2eforrzaw.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2pyuqsuxp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tifiekgj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsowaip.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqsxubi.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkgkhxd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mntlyjcy.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vizulind.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsannsx.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2horhwdyy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ashgggmo.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfaadlk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2csytlbeo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtgiyrv.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ufntehqk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhnfwjf.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2putmpqzc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxzfhzu.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyapuja.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2bymbnonc.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2edbhzuqi.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2xeyomvhd.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrwyzjk.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2uphqszmi.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aidehmvo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncomyoge.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2tlaqfeqy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2heajbtaf.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2pxslmulq.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrghbah.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkkbhma.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhqxyfj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2kpifjroh.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mktrawij.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfiuqqvm.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjzrlcn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2demgwonf.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ingnzump.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2goinfmmz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2jmeokard.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcdmmar.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqnzfbs.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmujzif.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yfidcghr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrcfjeb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbfjnqv.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwkhehb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2eaamakmo.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpvywhp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2jhybfvqd.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mvamsjyo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2fghtaidw.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnzraht.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzkprbq.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbunapt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2blacblcf.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2auhufaln.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyagilu.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ejetgstj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnpbfqs.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2spakqkbz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvgwoun.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnsmbsw.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvbklvs.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2enoxvxnq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2cedozarj.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jpymefxm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2zekfrtrf.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwtczeg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqwqpwj.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2eudbfjgi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2lyklospd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvfxsvd.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ndshkwbo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjzhkdu.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqaxxpy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrvojql.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2setknmir.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wziyrilh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tgntztfb.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vcstmftm.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2nzshbriu.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxqwssc.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2lumwudgr.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2woarmgax.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2akcewjzr.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2mfeexwke.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2elyvzfus.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpdnrrf.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kplopaib.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2maajhgqb.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mvoegolh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhuiixnk.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rnidajfa.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2txegvjmf.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vlihdglw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxjhpzy.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmztzai.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2skpvhsft.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pibjqbdy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uhenylol.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2cptipqgs.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsdtcuq.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxozczl.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmxjwnc.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2oavezfqm.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvxpeib.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2goappqzt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ysufbohu.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wxehwuir.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ecixwteg.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2iescmluf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2soqohyuv.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bqoimqqm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2somewiks.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgqgbas.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbxbpdx.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2zmluaaff.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvbcnaf.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhzxqty.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqqyzen.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vikgfdyn.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcysack.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2blcqztfn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oskrumib.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pduyycqj.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2okivvagb.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2urpzcteb.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvcbbny.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2igprmmyq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2byacqfdi.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnxbrtc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpxcqhl.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2meuwofuv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2amcqzsyx.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgvcila.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2yeidnfrj.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2fwuypune.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2whdpvcwv.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2myfogkzp.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlzozbp.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pfghhgbg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgylrux.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2goystpuy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2baqcamlp.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpchcgo.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfhvper.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jwaclcst.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyccsrlf.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gymdpkbr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwpxovj.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2xtusghoe.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kogxtphq.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2msaidgcq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqnkwtm.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tvegjckm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2thkrjujg.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrwiniv.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtsyhzh.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2eehvxptl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkxyjpf.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2axvwhzgu.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjgrkhi.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2aipwsbpc.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2llsbvnry.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdwpcdo.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2roujswop.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2lzaurxjn.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmnavlb.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pnymqcvc.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbolgmt.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2knpdipfe.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjgoxgr.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2uowfddri.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwnahmo.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfycizc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2dixlovty.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdgkfhk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fwffykgp.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ysujdbww.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2datqyzjs.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2igshjbgy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdwjpjl.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjukhjc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2imjnnlor.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpknvac.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2huoufyee.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2xozbsfuv.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dexngdbt.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkloxrw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fedffstf.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjbimhk.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2svzdoplv.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2dodyowod.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2zqujwbhy.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxfnjvj.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2adbuwnli.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2lwceffxb.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2tzuuxajy.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbmlkyi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2osxszgqb.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2kmccfqyz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cvevkhfi.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2houoewux.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrafdbs.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2szhrklob.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2hpobwond.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnsrgzh.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdtajqt.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pvectqfg.html


<!-- 参考信息 -->