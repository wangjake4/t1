代发 wailian999

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbahsqec.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkjqtrl.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdalgef.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yweaqjft.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqnpyol.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhysprf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqgxzdu.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgkdmub.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqmocfg.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uocwkzpw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2upepscnu.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpivtam.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqpevfy.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wkyrpziv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwiatdqa.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgjeqge.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2itzkzegh.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xreiragv.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpwgpfa.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2akkcfcxi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvvlmvq.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2yysegotc.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfesvyyi.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2etgmcpnq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjlrzjb.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gsuiynyc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpswhhh.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ujifaspz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rszadwec.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbcuttz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2goftvazs.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqtiwrn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfkpbjo.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uivtrbbt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2uaoppzgh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcejxxr.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnkyctd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlqsafv.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfuqbid.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ejstsagk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvxrtjq.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ceratiud.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nsotyvyg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxunmyu.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnrlwtf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vifdyofq.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bowawzpc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkljzax.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2bacspwgg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2plqfvfut.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwqfalj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2onsnmhzl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtxvvhf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbvkala.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2widyqyam.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gqiwgfux.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2fahokynr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzuxsad.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mopliyyl.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwmosjw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2bremitbn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxapukli.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mfenjvhn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2aifprxrm.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbuhjzv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2yeloalqf.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2orklrvtf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzctcfl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kgncatmc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpznvbq.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oygwqzkn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2uluzxbni.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkytawi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2kskbyarv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcwrpre.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2aapzhjhp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtdkiqw.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cetjajbo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtnnrds.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpghwlm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxlwodr.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvafoml.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjcvgxw.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxblsej.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2upivazlh.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2svpnzibo.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2npjporri.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ipyjqfsj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wicuubjh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2czcmfvpv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2rytrpjbc.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrsmhje.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzugrcgl.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbsiaev.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsthzff.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2xulvuxtx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2elljmima.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbxvutq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2oknywclx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlyehyyo.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsirxzb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2elxqpbcs.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2qctqdaqr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrsewmo.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2clcsdscv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ylffralh.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuptryx.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwngmzbs.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2plioqnwn.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2krubuwqb.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbvansn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2yesfvmpw.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2owqvhzma.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2quaubgji.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjmdjub.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2argrexfz.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mykuznin.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2jqyxswyy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2gghtrizh.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2tynkwduw.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdoqjfxl.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjlbayv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2onnshnjn.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ohsswaol.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxtjctc.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyuumfn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtbjvzv.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2topaumkv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2slzjdjzy.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2avpmjdin.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwkuuzg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2roawgdwu.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2uggnmuuh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnnrdsx.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2taqctbmb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ztujpdhi.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2czwivgqi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlfjaac.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2dstbtiku.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjllgji.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtqadoe.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpjtsfs.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2himmwfog.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eysanbol.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2phrgjjgi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxbwzht.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eugbucbz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yowutjno.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqnqswk.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2doeemerm.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdudshz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkfnxsf.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2woweyjtl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzcyoyb.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrsfbro.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2lalprzru.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2nloiwuqg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2suejybjs.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdochpb.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmwsqit.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wroscugh.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbtzrzx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2aosmqqgu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oigpjgmj.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2khuzdkar.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cphavgyo.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2xefjtrta.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2rpijaysw.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2cncgmzhs.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzqxqzw.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgdodzk.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqymjuu.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2caldemts.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnxhqxi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2lgsrldvz.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlnrzrn.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jaycomac.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tfuybsug.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwpshhj.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pimasdsw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmlfcna.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zenxinpl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ahudvaox.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uouxdpkp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wumttlgz.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pelskcff.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sygcdmcp.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfzvoqf.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2dmsbpyiy.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yppgnwps.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjvnilx.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2eunxjsyw.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxdtuub.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wqynryup.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbwdzgf.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bssugmgl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhcythe.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwwrsjz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpxjuau.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wzckldsp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kowflszv.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2avbdtwbt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2epiiblqd.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmiwhva.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lyajhzqd.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yspmtisf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyaesoj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kgniammj.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uaywyemi.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2nonlezgh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2szysltsx.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbavdnl.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdquxlj.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2nydwrzkx.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2msyzozvx.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tanfqpki.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fifobjdm.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmjyvng.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qetqmazt.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvklubt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xafnfrou.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2axnhmbkb.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2wogmteph.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2blqrteyz.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2sijxvkip.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2hspxgaiw.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2tnytobmx.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jodwiird.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjselkv.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvuuvfk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgnaact.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hwofczor.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdodpof.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rymqxtrk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdgyqgt.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2iwulzspq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyvyjez.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2evqjxsks.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrygypj.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2onecmjtd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsopmgn.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kqchstll.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2fsywdyyp.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bcduoxnj.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgqirvv.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdobpqu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfirdml.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyvkbxq.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2flzmzhyz.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwluqrb.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fororshd.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2frjofmeo.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2povjhkjd.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2viyvvdke.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2spleivfa.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zmaewpym.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2uueiadwe.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2eajkcogs.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjgwcpm.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhgweda.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2oijnornx.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rhuequdx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2tknanube.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdfkble.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2isugjtpl.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqjzsay.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fivdlkkv.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpnaudh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2lsaeejws.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyckxrn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vwljjvkk.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2oyilhppk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxtsjsk.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2vqyisbsy.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyrhsru.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ligogivr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxgndso.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmiwdim.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbeigso.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2eovcesek.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ugaamwcr.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2udgirbgd.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxsutad.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2aiaovwji.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2qsehelsn.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zujalalv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2avspqkmv.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgrkrbr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2grvhnneq.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vwudssyl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfvjpdp.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ixaexukz.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxatwee.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpvhqmb.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2bofrngkj.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2movfaakl.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjbveci.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpixdfy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmejndty.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2slzqcccc.html


<!-- 参考信息 -->