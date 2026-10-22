代发 wailian999

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2jmiwqjfu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvwqphr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2czwthqew.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rrycgnif.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqixybrl.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kefjmjop.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkdqvwb.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jphyhjkl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iznxeaik.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rxngdlua.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsnclmw.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zoanldby.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqvpivb.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2buqxupuy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jngzfyxb.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2voqbzlpl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdursino.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbyahkb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgbcdhs.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhralpf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2lalwywxl.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mujwgwbc.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cguseoba.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvbsyse.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2evndbilu.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjqcwmb.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxyuxhsj.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjvkxay.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2haplryay.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2laekltjs.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufibotob.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzfzfpj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqusuwg.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcaubve.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvslzhns.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmapntg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjjqaeh.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpzpwll.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqezhmr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwqjcby.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kglzpkgq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2abxkviec.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2eqryabgt.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2avwmsaps.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxjgccv.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqauuts.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2unluwyia.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpasrcv.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iomgohfb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2noghpwhf.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrpuwzw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhicouuy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgrgukx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjcpltk.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjfzzqe.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2etqycvgj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oavbehgg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2jnplkkrf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgozwnri.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2latwraoe.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2slqevkpr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2cwatzufl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqyetfmu.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qocxnqlt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2hinjogcm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2plerenif.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ywoskxdg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqhusue.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mjluitbq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2lujmnywd.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhfhhle.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2invppwfr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pqejlytz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcfpoko.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqxdiwn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2cueoxrfe.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rlloqhai.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhykywhn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2netijkjj.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2brcliezx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvsptrg.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxncojt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qyeioneo.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmgoqlk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2piavqubx.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2lztxqycb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xblvhsmf.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2oalowwre.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2icjufvvw.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrqnyxk.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrpgyhn.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2pukrvshi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dksdkkhu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2iwndbttu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlbsgka.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vhouoods.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcqydsu.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2auapazic.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkuglbq.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsyoayv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2seazvybo.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rojhdzse.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2osuzwntl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fumiakkj.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjdrwhs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydctthcd.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmqcmot.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfhncox.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnpjscw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2oacgncrb.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2eqaqtsfq.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2twjnflkm.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjqnslt.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfziokg.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mgflstij.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2garyyrrw.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjrhdbg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2qasmjlro.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxuvazi.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrdmwmc.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyewuyol.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ddiorvlf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbjpmtx.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdvrxvx.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpgxvqp.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2zewmyytt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkkllmj.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ivabecle.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpjytae.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2vwenllke.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wofzwxce.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrmibku.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2vcktqolm.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgpamqo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2odfpqdrm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjlvezo.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2kqonwdex.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbezsazi.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2zmeezfel.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2bpixvxzq.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjrekya.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2poujbtrh.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hoymraqr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2arukxxks.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2pulsyyeg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkixvjc.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hqporbxj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2syousupn.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgalcxn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdgvruf.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlzepav.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oibuhszd.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjpqvmv.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkeixfx.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2qabvjdem.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjfbngl.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2covjfrqf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkorunm.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvtjatu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdrhioe.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2cytsrdlo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmnbive.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gehijzbh.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbhsczi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnswgcr.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzfujnt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmzncyg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsohswo.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwknhko.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2izfbqmrx.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2xwuabsnj.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2aqktyptz.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2obsfqqin.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxyahdh.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2yygkmebl.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xndkbaql.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2vffqvrau.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxfrxnx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2fydjslng.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2neqciwck.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sktwffrn.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2irrubjkc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvxjvwx.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zqabvkij.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxchnfo.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gzykrqak.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2waoyseye.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxidgqw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jfigrobr.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qytwyjap.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ulaqxdzz.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsabfib.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2kskodyfx.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrvonnh.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwnacgp.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bypjmqth.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbtcjas.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgftrjs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gowdqngw.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2niteuqxc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsswoou.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtvhxsw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2urswlcup.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sknrxprd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wsytskxh.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2chzemkwv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrbpbzn.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2qklwfeks.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkgwsva.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2diwtrvkz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2njjcmeqp.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tjporjhx.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2apquqlqx.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhxuovz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrwavkn.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpyyocv.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wszdshag.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvhbktx.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oskuyzmu.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfdcpub.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xklisbjv.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lofmdhcf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uuczcqgp.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdppirg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2buupqasu.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2clesiziv.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbuujlbt.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdskgyb.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2zzycqiyf.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2imhabior.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmanjrm.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkyfsfc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcsfdey.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2akaspldl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2losbagzt.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ddewfbbm.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjruuly.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2umdyqrik.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwycpedq.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rpowsvpb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwunwtw.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcmgtwi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2biotgvod.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqmtbte.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2siviuqnt.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ehunpkgc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2nfaajwjj.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2apieaxvh.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxsruun.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2uctexurt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jpyungqi.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2glboklyv.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2dqposrmj.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqhvtye.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nmprylhv.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2uumzjhaw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hglmiugz.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ubevytio.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hktjvzfh.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2thgjvsqx.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2grkclrut.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2acgqiehy.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wzysykpf.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsedkgk.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2pituhtdr.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2aqalzbvc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpqjrwt.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uqztprpt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcxxusp.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdkqoen.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2motvltsm.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxrsuwr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tyangcri.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2oglozncx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2alksyjcz.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2phxrrxgm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjidyry.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbfabmd.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aeawvyvi.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2olendklx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2btvkhnvj.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2thidymlx.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbqxdqz.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvgjope.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2coducsmd.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdrnlzu.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkrdlqq.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2grvqfdik.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2wnthhnqg.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtvubkc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2frxurjig.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwlsgbc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvthusy.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqiqokp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2esslykbi.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpeoyjh.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2sohljggg.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzxkmyq.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2uthrorev.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzgtrae.html


<!-- 参考信息 -->