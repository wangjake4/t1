代发 wailian999

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2usuygein.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2khhhduek.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2omhapqox.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qitfydsj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktifwqxy.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfjswwi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2njfxligv.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxfrkil.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2bortnqff.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mhflgcuw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcctixd.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tsivfisx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2bajxdsok.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2izblhpua.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnfzpdu.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2yyghvghs.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2pljmowvk.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wirljswm.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwrhzjj.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbcgdse.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2wazexoqa.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtzexpm.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrydnhs.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmpqmqc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghprmokv.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2dkybdndu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2anpmvqgn.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbrenfy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwlrexx.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxouruz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wryzhrlh.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cngzioaq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwmnvwk.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iommjxfw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2epsozbhc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2kupdxfsu.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwlgfwd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnuxtjta.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2syvdokze.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2exwblmqj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2afaogunh.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2trkkddhf.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpgfmfo.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdotuvqz.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvvhhko.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdoxnpj.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jpugkiiy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyryqkf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2savqsbsw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbvvjxj.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hzaygvxi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2mwywrunf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oludpxwt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2surfqdth.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqqntuo.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkxbrgd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ypupfkwl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2knumokmq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2whfigtad.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yskaxrio.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvjilyw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ontkcarl.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fxuyidja.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtnmmof.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ahblfkej.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwiwnju.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkjjwrx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2aaajcmeb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtndifz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnvlojw.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ivugenvu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqtujop.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2iggdggls.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2kztsgwcj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnqkiqb.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2aocsqpzm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmypjsfx.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2clkukjbn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtsaqps.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkpgkwv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzzdukx.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2bescwvga.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxnpeta.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2amlssclf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jwojfgut.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqyunvp.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2noljlngi.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdgfvit.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbaxdavc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfraygym.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewiugsvv.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qsuptggz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nslpfjtp.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kteovbcv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyogvuj.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2guxkjooj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqonjfrj.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdapcpn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2byuxzzok.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2usctwkrc.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lppzzawm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzmtumr.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2jpifjgrr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqaryhtt.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2meqagwpz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2tedzwffh.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2siwbffet.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsyuvxvx.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgfzqmr.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2syggcxbm.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2spafxrbn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvvplmh.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqtfwgt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsbvdhx.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwocust.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lihpybuw.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2luongska.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2gmoqrzcs.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2qeolgnku.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hczvmzbq.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvpsngd.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2hclbkuol.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxlbrfr.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wdoeqipg.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aiufbcry.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtoigxb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pftizcod.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2iughxhri.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxdeehe.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2knkwwezw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2igjulliy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2pemnqfdy.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpsxdui.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2widpzizr.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnexlul.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2yizoujeb.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2tofwoskr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2xkycgmtx.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2vourfrxg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ekghcpqj.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ipskejtm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnosglg.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vbisyprj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvpcbku.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pccdcxcj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uprsutgd.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrityce.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgqbsnn.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2onwxckhw.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2prfeoitz.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2guczvclu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbyjzbu.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vukjwygk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwjpofp.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkrjrzc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2aakagyro.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2dufdxnfo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2obrrxvnz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2phvfyjsh.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wvowkrxj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2gctlqmyb.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxmvezi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxuuwjiw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zdehjmbz.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2uphkcmbb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2orzfirdq.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2yzukbbft.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyqxhve.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2nupsyprd.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2nmisrecb.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2iixscddo.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tbquuxdz.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2fmncrniv.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfxniqf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtdgkil.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2afehpjam.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qartfjfr.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxrgqte.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncuastgv.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ustpjhgj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgyhduz.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2udqtlcmp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjsxpan.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ruaaaaht.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2iclnxtyc.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxuizmb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fktnngdm.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2mpldgifl.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2bebmmzqj.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcyfiidd.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2oublcpnw.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgghwov.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2yukaqvmm.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mapbumlb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jipnawcm.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfmzptc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wrswleal.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmsurut.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zjalbofu.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwkynrf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuccnht.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2svzquxwn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cooixboa.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxqpypd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nsotwlbt.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hizjphev.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrjwfsl.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2saqdgxiz.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2alimlfzl.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2triidgai.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqaffon.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gajixkls.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnzoedf.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2daozrmud.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfffsmu.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vumoworm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uizzkbtj.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkwuekl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkgjfdu.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2fsojtzpy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfwjqyh.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cadvccmo.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2vuflapjr.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2cwotuowt.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbrmkhr.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2wincfcjj.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2xvohivip.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ncsmatyt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2khkczzdp.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bujloxwi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2weowkulx.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uckuhctm.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtryvca.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2uykovmka.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swujemql.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpklnkv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpaxgsy.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcklrhq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dwclqxvn.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnqcgvj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2sbydfqvc.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2drrgetvv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbzgvgi.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdrzuhf.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2faiqkdgk.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpycwug.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgtdiwi.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrvbuxf.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2eqsvdmcx.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxpfevy.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fxiovdsn.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrlwbwd.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2neskujoc.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2pmczyzem.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjwrnew.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpplkca.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zahnplap.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2npgvhhzc.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fojwauvh.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hczikraa.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxyjttl.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrbbhci.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnbleiz.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dbuqfljb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjfinwo.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2czryevnz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgwwrox.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjuoehl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrsrfbz.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfcnrvp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gjsiycxm.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkpfgac.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2pxebbmjs.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvccsdq.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xltbmyep.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnelzix.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2aapyrfbz.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhtvplu.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgrfrdx.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbrjlkl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2gerndule.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vcexwwwl.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxnakkw.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2svympxev.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfirvmd.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2odpyllop.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwozcay.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjalgow.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2drqxstyo.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkhepsw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtfpxay.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjkywav.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2dljardhf.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wapapbqy.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2oioigtwo.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvsrbgy.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzhcoae.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hkaxmnqf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2fizqhkyu.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmjpyxz.html


<!-- 参考信息 -->