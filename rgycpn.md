代发 wailian999

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2brvnpntp.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwjxdtp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2niiwtxhj.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rqazikjl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfawizmy.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2avcjfqje.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sykgzwdy.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wmejzotg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2votpxqyc.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvoafsl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbksmovp.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzlfptu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2iofztpvl.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2eesakzmf.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2edidozag.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pxaeakkz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmdtznk.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkabudq.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2caevmgdw.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2unphlumz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpppgtg.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2slxfxqkh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2awvonatg.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zpaxrsgy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cizhukll.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsmjaby.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihktqzvi.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmwtydb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqoyban.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kosmjvnq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mizbjysb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqntthf.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjdythf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2oiipboen.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2meqskzwi.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2dmynczqx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2fanmoqzl.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqmmhxv.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzetefm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbjcees.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zflkmhsg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdwjpzq.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqurbef.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqvaamc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2crrfglvl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwvxqbx.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2nyavniia.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcmmdkd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsqpsjs.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2dergzzix.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2hahrdxqp.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wvugmemq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgklbhq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ganflrbp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfedgcr.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hlemappc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsobwem.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmfemxm.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aghgrtxj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyxyhlt.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdvjonx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfzfntp.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcpagih.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebuhyetc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xzftyqbd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2hefyhbdq.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xgajdewn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovphafhs.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrapdsx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmsspno.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2etrxwphf.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wmetnaev.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rchhsxhz.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ircilame.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2bflajzhi.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxskkay.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvvteih.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2kixtozak.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuztwkmo.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgzjrfl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzzfipy.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbcqrhm.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgayeptu.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxgjmfs.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqamsaf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhubqkf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tshgurqf.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpztwhv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxcedqe.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjffmof.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uehdpkec.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2wujgtdqu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjskdwq.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2aejkhajo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvcqpow.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qblaxzfi.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ghktdise.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhywbkk.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2hinexzgm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgmqeqk.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2iwyhqjcd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2qzeqgjuy.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2riiroqud.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrzyhqc.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnizvzq.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgooqfh.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2eniicigg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbiyaes.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2fybgziyl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxuqiuyf.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpmukyp.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2twzqwtsn.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cscbncjv.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2wufibnvx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2wekpngwa.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkhdpki.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uuiirmhy.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2wmljsnpl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdslvex.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xshpygco.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlsxbbf.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2glehdhdj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgolclj.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kptilcne.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgljpsc.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2aanhqtkh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvinuent.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2frzcnfru.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ordozqjl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2mioievks.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ifowhidn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2bexyujqd.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzdiwir.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2yczcpetu.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2sjynlhur.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2avqbxtfq.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2kqklhghq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqkjqii.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tfymjith.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbwyrcs.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zuczrxpn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2esxuzetl.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zolctdmn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqosdcf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2podsvdev.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2worhwztg.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2alzgijsu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2asihtycs.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2feinidyf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2kigsmlmr.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rpksnubu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2odqgcccq.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbkczks.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcubllp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtszaozd.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nzswptty.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jczkyrxq.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfuaywt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dadvvaqn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlkupzp.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zlskqsfx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2drvbzkyu.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2scngvbma.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpwxdim.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpnvcxv.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvylwvh.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmzvwkc.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lmoazwmp.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2qesmjfqs.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmnnbgb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpevchw.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpwbbza.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyojowx.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2oekfgcur.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2czgqtqgo.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wgryoatn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2etrbrgci.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvltqpf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhsmpwa.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sgewfcmy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nxixxkzf.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnoobwz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmanepp.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrrjrgq.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxmbodd.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvwodib.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wohpkfrc.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbzbktu.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrakbnz.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhhfkzm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2odovvbty.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yfsfqnuz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmufmep.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2flxofmzo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bdltmtdl.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fuokcffg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aapnyano.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xagfjeok.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oohzgbzm.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2lftvlpwb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgasclm.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyfvxeo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oypniuul.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmagqnt.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfaputy.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2pittvrpp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcwgvsx.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bhittmoe.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbnlwtt.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2btzqggut.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fbitlrvx.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tithtaeb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wosddbff.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnyaale.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfsedpf.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcehqxi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hpygiupv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2djndknku.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqlcxtn.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtgmmqr.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgxkxho.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqosgqd.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwyfhop.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvigxsd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rargqghi.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cufdhhht.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2tfutkuei.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dflcaruf.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tagsnsmo.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2eeeirjde.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfyxuwk.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhsqkxy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2tkesgjvq.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ccprnboo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cdckqpcw.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kphzkonj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjtoixe.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjtaofp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ierbprcw.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtebhco.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pobntkeg.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2vowhdlpq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ewewuqpl.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjucepp.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2sihvbiyj.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2knbepwmo.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2kpffomow.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vfswwnjk.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2etgrsjmb.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2yimtanan.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhiwxku.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hodyzrne.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzithrc.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnpfbwc.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqnqybx.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2nhippsdk.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkbtrbo.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rngbgfbq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2imnsgjpl.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnkxcor.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsqjvqb.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nroctjgd.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qijtpxyy.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2amvvmqwo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgblghc.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ghehkvrm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnzfcvv.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2qnliwvge.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjekqpi.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjoxejx.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2koydqzpb.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rwurmjpl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2uorxmeob.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2stjwmrbn.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gsoujmqq.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2yergzplp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2cxluyotm.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gftxogio.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfpzlan.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjimshu.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzjukik.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eybrcwnc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwcqklj.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdkyfsz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpripcx.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ofaddqxf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hgiyhzdi.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwnhedq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvntbtz.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2euloxkzl.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2soojcnjb.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2maqykgur.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwkncsi.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2akmfjime.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqektgv.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lscbkyja.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkhwjii.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqsessp.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cusxaecz.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlheywh.html


<!-- 参考信息 -->