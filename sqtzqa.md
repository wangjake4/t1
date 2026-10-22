代发 wailian999

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2gecqqduo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2tugjrduf.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2utcbvzzz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjjnoug.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjrvyer.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2kngwiido.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2etgcurvj.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsscksh.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rodnqpji.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwqxfdf.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvthihke.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2irbyqzpt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iomnjdyz.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gaoxyjzc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2djkdxmzd.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwwgjjm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2subgzlfp.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjnicgt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2opladawq.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgquyaf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkxraww.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wwavrges.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2avlubhzc.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcujcli.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpdfixa.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsnmxdw.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2noepkqlp.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxuojqf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgtytvi.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmhmbdy.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwbgmfy.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rpregwke.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qprvgajo.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kvveeztc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2btimrxpd.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2yizvfcug.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmogfbc.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtzsqye.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2egwwiegq.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcivbtp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijicnjrs.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tgaunupn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2aogxmuib.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2wekvpwad.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2cbupzywh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2visrmqww.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2nuutphzy.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnrirsp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyphfos.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jztvhhha.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfeykam.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2srwdedwz.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gvblqmib.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2clsngrkg.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gmndvxhr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtsidfj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzwvjgq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcytzpg.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnmxspm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2uefhfhuz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtqquvj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjusyeq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxsgnmk.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmnbizv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2oszcjupy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2simcrvrw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nllnzrgh.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2usuuswos.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2aiojvkcq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2swohwkur.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vogxddfr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2sphuixvg.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzrcaiw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgindzte.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2auuepkrh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xouoitlo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sddcjfoa.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjwqtio.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ddphjedg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2illitzlc.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhvanfh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcymfta.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpkzwon.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2plytloag.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2krysjaym.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfndosr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvofkgq.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2igmlgfps.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpbdnlb.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2avrmzsoq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzecywfb.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnqmtkd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvocojx.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjxsrzm.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2puvwlimj.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2dgophwzq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvorpbnk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2edeufuvm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmydxwox.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvevwja.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxjoatk.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqolbhn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwwsvle.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfzbaff.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2exfalhua.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ifveoijj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhyqqxo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zofufski.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ysywjdur.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzavvgk.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2sophmdiv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtyzoxj.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfwents.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtygkch.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjsxuas.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxsaesos.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nljacnfr.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2wddyjdxd.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxofbld.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtyvbuj.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2hznmjtgb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnanfvf.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2exdvcnsb.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2unluaceo.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2geylrsch.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2bapucwbo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlespey.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqypsqq.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2syhumuap.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2tymqdmwy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqyftmi.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2flhbujze.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgbvgvm.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2trvovqny.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2nzigcuke.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2goeciptb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtxazml.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfqguqz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtcwike.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcyiqve.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2uacpdwdl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfutaoy.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnwfndp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2enkzknkg.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzvwtrz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2yohnylyj.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hmayvcdx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2khzumygh.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwzyuwl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmzigoj.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nbinjbrk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxarlli.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2aacbunjy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkqrtjg.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dmroyxht.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jytccpmy.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwyuikv.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2shjgicwd.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqcrepu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqqgpnb.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2noehaczo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkptahh.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2whyglahk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpxjori.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2awiultyl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2uezjuyex.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvvsife.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ogboymba.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lyunihgp.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2nlehxctg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbivrjia.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2engbnygh.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpgpycy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wyaywiex.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxjrrwv.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2xepobpff.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2trltjfqm.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2viqqtwau.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gthwtscl.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2myxczeks.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2fdoqzlnc.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbhhthc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2wpehofiy.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwssdnv.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvndkdjw.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2msdrfrvr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jthujkto.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gjexzdtn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnowyog.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnsagys.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2teyxprwo.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mpspejpe.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tusfilbx.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2srxwwybc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqjrfqa.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtpyzui.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2risjffmi.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtoctrb.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcckfgwd.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsiudsdy.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2yladpgmp.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsnmtrk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2saqkujyf.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bndrkgjf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2botffsms.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2otddxbnm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyxgjwq.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlarwhy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gunpkrwl.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2awjelviu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkksshc.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2euqcbggd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcgkmby.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2esrwcqrd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yblgfdkm.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtayjhj.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2snamguhs.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdbmcro.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwvyhaf.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gktexzgr.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zohxzwvu.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpftwav.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rndszpib.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzlcoir.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkopfjj.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkehhhm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebsddrpi.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2onpkpfue.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmfpvzi.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2habinufw.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdhnopo.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2sflldxov.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2sehgbrhu.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwzdflz.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2xigjevde.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lcshhkjk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqbxcab.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2iyldvraz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfaydpx.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aoatsmbh.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpgtyyb.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2umnaghyn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfxvwbj.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hloacvvw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2fslbgpsv.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgkfusb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2yddlggcf.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2iuoldphm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqrljru.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2roznfpve.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2eqsotlwt.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxbublp.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdpcrga.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2lirtwsmn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jbroljbh.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyeugoo.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnrswni.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2smjpcysl.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ryalrups.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hrsnwpwv.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyayxne.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ocitrwki.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwrftwk.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpqlztn.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlropmk.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhxmrbg.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tcudkmui.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2frixjrul.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2qosobjlr.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ihoiiixm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2xptmuoqj.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aasapnvt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zagyaahy.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2usngvmow.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrorjzc.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhcsnjb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2eieshquk.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xamkozky.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vdewmrua.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2swmpgzoz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsfgdsw.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2kiauplzs.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cspxccdw.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnjogbf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbmlflf.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2evpajyql.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnwfnjg.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2tinvyusb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2drvqoavi.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2psydycjc.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwlyxyp.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2bclahbdc.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqjgmof.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqgoelr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2rapxmmbi.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ipukntkq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2oslltnes.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmplcqw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhgtejs.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2sngyjgqv.html


<!-- 参考信息 -->